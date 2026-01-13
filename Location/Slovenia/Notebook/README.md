Linux in Slovenia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

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

Total: 456

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [9072b841f8](https://linux-hardware.org/?probe=9072b841f8) | Jan 01, 2026 |
| HP            | Pavilion Sleekbook 15 PC    | [78256012a0](https://linux-hardware.org/?probe=78256012a0) | Dec 23, 2025 |
| HP            | Pavilion Sleekbook 15 PC    | [2bfacfd511](https://linux-hardware.org/?probe=2bfacfd511) | Dec 21, 2025 |
| HP            | 255 G7 Notebook PC          | [e19940b575](https://linux-hardware.org/?probe=e19940b575) | Dec 19, 2025 |
| ASUSTek       | ZenBook UX434DA_2nd33DA     | [505562ed52](https://linux-hardware.org/?probe=505562ed52) | Dec 09, 2025 |
| ASUSTek       | UX305FA                     | [71a0dc8d18](https://linux-hardware.org/?probe=71a0dc8d18) | Dec 07, 2025 |
| Lenovo        | ThinkBook 13x G4 IMH 21K... | [7ae5c25cfd](https://linux-hardware.org/?probe=7ae5c25cfd) | Nov 25, 2025 |
| Apple         | MacBookAir7,2               | [fb6ba7b3f2](https://linux-hardware.org/?probe=fb6ba7b3f2) | Nov 21, 2025 |
| Dell          | Precision 7780              | [4e70e419c7](https://linux-hardware.org/?probe=4e70e419c7) | Nov 12, 2025 |
| Dell          | Precision 7780              | [9158b96fc5](https://linux-hardware.org/?probe=9158b96fc5) | Nov 12, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [722ef2692e](https://linux-hardware.org/?probe=722ef2692e) | Oct 19, 2025 |
| Acer          | Aspire A315-42              | [43c5887e23](https://linux-hardware.org/?probe=43c5887e23) | Oct 05, 2025 |
| ASUSTek       | ASUS Vivobook S 16 S3607... | [0ab73c2711](https://linux-hardware.org/?probe=0ab73c2711) | Oct 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HDS... | [d69462d966](https://linux-hardware.org/?probe=d69462d966) | Aug 27, 2025 |
| Fujitsu       | LIFEBOOK A530               | [38c11140f2](https://linux-hardware.org/?probe=38c11140f2) | Aug 22, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [26fc7c00e4](https://linux-hardware.org/?probe=26fc7c00e4) | Aug 22, 2025 |
| Lenovo        | ThinkPad L560 20F2S0D300    | [e03ec0ce88](https://linux-hardware.org/?probe=e03ec0ce88) | Jul 12, 2025 |
| Acer          | V5-171                      | [62a124b6f4](https://linux-hardware.org/?probe=62a124b6f4) | Jun 23, 2025 |
| Lenovo        | ThinkPad L560 20F2S0D300    | [6b76985a0c](https://linux-hardware.org/?probe=6b76985a0c) | Jun 19, 2025 |
| HP            | EliteBook 8460p             | [46e595522a](https://linux-hardware.org/?probe=46e595522a) | Jun 10, 2025 |
| Dell          | Inspiron MM061              | [7f36c93e55](https://linux-hardware.org/?probe=7f36c93e55) | Jun 09, 2025 |
| HP            | ProBook 470 G3              | [c1d6c4f809](https://linux-hardware.org/?probe=c1d6c4f809) | May 31, 2025 |
| A15HV01       | Unknown                     | [bca43f4ea9](https://linux-hardware.org/?probe=bca43f4ea9) | May 17, 2025 |
| Lenovo        | ThinkPad T530 2394BE6       | [c2642ee258](https://linux-hardware.org/?probe=c2642ee258) | May 06, 2025 |
| HP            | Laptop 17-ca3xxx            | [cfbedd157a](https://linux-hardware.org/?probe=cfbedd157a) | May 04, 2025 |
| Lenovo        | ThinkPad T470s 20HGS0NU0... | [96e9e9bd3d](https://linux-hardware.org/?probe=96e9e9bd3d) | Apr 22, 2025 |
| Lenovo        | ThinkPad T470s 20HGS0NU0... | [aff5a1662d](https://linux-hardware.org/?probe=aff5a1662d) | Apr 22, 2025 |
| HP            | EliteBook 8460p             | [4537f56c25](https://linux-hardware.org/?probe=4537f56c25) | Apr 22, 2025 |
| HP            | EliteBook 8460p             | [993cce8978](https://linux-hardware.org/?probe=993cce8978) | Apr 18, 2025 |
| HP            | Pavilion dv6                | [38dc311890](https://linux-hardware.org/?probe=38dc311890) | Apr 13, 2025 |
| HP            | Laptop 17-ca3xxx            | [69d43f7683](https://linux-hardware.org/?probe=69d43f7683) | Apr 13, 2025 |
| Dell          | Inspiron 5570               | [c493fe1018](https://linux-hardware.org/?probe=c493fe1018) | Apr 12, 2025 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [82f95d7c3a](https://linux-hardware.org/?probe=82f95d7c3a) | Apr 11, 2025 |
| Lenovo        | G550 20023                  | [563ed02379](https://linux-hardware.org/?probe=563ed02379) | Apr 09, 2025 |
| Dell          | XPS 15 9570                 | [9cf10a17a2](https://linux-hardware.org/?probe=9cf10a17a2) | Mar 27, 2025 |
| HP            | ProBook 4740s               | [4ea98f44e6](https://linux-hardware.org/?probe=4ea98f44e6) | Mar 26, 2025 |
| HP            | EliteBook 840 G6            | [36d37e0806](https://linux-hardware.org/?probe=36d37e0806) | Mar 26, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [44cd77e7e2](https://linux-hardware.org/?probe=44cd77e7e2) | Mar 24, 2025 |
| Valve         | Jupiter                     | [ffcfda6117](https://linux-hardware.org/?probe=ffcfda6117) | Mar 15, 2025 |
| Dell          | Latitude 7640               | [ad74a7462c](https://linux-hardware.org/?probe=ad74a7462c) | Mar 10, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | [46106e24d9](https://linux-hardware.org/?probe=46106e24d9) | Mar 01, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | [db5519da9a](https://linux-hardware.org/?probe=db5519da9a) | Feb 19, 2025 |
| HP            | EliteBook 8570p             | [1d178716ba](https://linux-hardware.org/?probe=1d178716ba) | Feb 16, 2025 |
| Dell          | Latitude 7640               | [c8241333bf](https://linux-hardware.org/?probe=c8241333bf) | Feb 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [a66027228d](https://linux-hardware.org/?probe=a66027228d) | Jan 31, 2025 |
| Fujitsu Si... | AMILO PRO V3515             | [151f0a32c2](https://linux-hardware.org/?probe=151f0a32c2) | Jan 23, 2025 |
| Acer          | Aspire A515-48M             | [fb4edcd1a4](https://linux-hardware.org/?probe=fb4edcd1a4) | Jan 13, 2025 |
| Acer          | Aspire A515-48M             | [d28d20ca80](https://linux-hardware.org/?probe=d28d20ca80) | Jan 13, 2025 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [d99505e615](https://linux-hardware.org/?probe=d99505e615) | Dec 31, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [ff70c71f76](https://linux-hardware.org/?probe=ff70c71f76) | Dec 26, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8e7f60e511](https://linux-hardware.org/?probe=8e7f60e511) | Dec 23, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b7da8ab4d5](https://linux-hardware.org/?probe=b7da8ab4d5) | Dec 23, 2024 |
| TUXEDO        | Aura 15 Gen1                | [c4af5fafe4](https://linux-hardware.org/?probe=c4af5fafe4) | Dec 21, 2024 |
| Clevo         | W35_37ET                    | [8c4d3d1caa](https://linux-hardware.org/?probe=8c4d3d1caa) | Nov 30, 2024 |
| Clevo         | W35_37ET                    | [4b7ce97c36](https://linux-hardware.org/?probe=4b7ce97c36) | Nov 30, 2024 |
| Dell          | Inspiron 5570               | [d8fe08107c](https://linux-hardware.org/?probe=d8fe08107c) | Nov 27, 2024 |
| ASUSTek       | X510UNR                     | [9fc9d25b5f](https://linux-hardware.org/?probe=9fc9d25b5f) | Nov 24, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [2f352dba44](https://linux-hardware.org/?probe=2f352dba44) | Nov 11, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [d5e9aab0ad](https://linux-hardware.org/?probe=d5e9aab0ad) | Nov 08, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [6bfe7b8d66](https://linux-hardware.org/?probe=6bfe7b8d66) | Nov 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5404CMA... | [cb52c24436](https://linux-hardware.org/?probe=cb52c24436) | Oct 30, 2024 |
| Notebook      | NS5x_NS7xPU                 | [82b158b778](https://linux-hardware.org/?probe=82b158b778) | Oct 30, 2024 |
| HP            | 255 G7 Notebook PC          | [7547bc75a9](https://linux-hardware.org/?probe=7547bc75a9) | Oct 29, 2024 |
| Dell          | Latitude 7640               | [db98adb76d](https://linux-hardware.org/?probe=db98adb76d) | Oct 28, 2024 |
| ASUSTek       | N552VX                      | [125f09bd6b](https://linux-hardware.org/?probe=125f09bd6b) | Oct 27, 2024 |
| Dell          | XPS 15 9530                 | [22b47c8319](https://linux-hardware.org/?probe=22b47c8319) | Oct 25, 2024 |
| Apple         | MacBookPro11,5              | [7680c404f8](https://linux-hardware.org/?probe=7680c404f8) | Sep 29, 2024 |
| Dell          | Latitude 7640               | [c90fe866d1](https://linux-hardware.org/?probe=c90fe866d1) | Sep 26, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [62e1a9a394](https://linux-hardware.org/?probe=62e1a9a394) | Sep 20, 2024 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [ef8c47b1d9](https://linux-hardware.org/?probe=ef8c47b1d9) | Sep 12, 2024 |
| HP            | EliteBook 850 G2            | [564d24fc5f](https://linux-hardware.org/?probe=564d24fc5f) | Sep 10, 2024 |
| HP            | ProBook 450 G6              | [3c8383394f](https://linux-hardware.org/?probe=3c8383394f) | Aug 25, 2024 |
| HP            | ProBook 450 G6              | [6b40bb2382](https://linux-hardware.org/?probe=6b40bb2382) | Aug 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d2bf0e7e39](https://linux-hardware.org/?probe=d2bf0e7e39) | Aug 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S03X1H    | [c4c6048c05](https://linux-hardware.org/?probe=c4c6048c05) | Aug 09, 2024 |
| Dell          | Latitude 7640               | [cd57286388](https://linux-hardware.org/?probe=cd57286388) | Aug 08, 2024 |
| HP            | Compaq 6820s                | [6a3adf5719](https://linux-hardware.org/?probe=6a3adf5719) | Aug 04, 2024 |
| HP            | EliteBook 830 G5            | [0eb2a6c9e7](https://linux-hardware.org/?probe=0eb2a6c9e7) | Aug 02, 2024 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [88e46768ac](https://linux-hardware.org/?probe=88e46768ac) | Jul 27, 2024 |
| Toshiba       | Satellite L650              | [c6baf57189](https://linux-hardware.org/?probe=c6baf57189) | Jul 20, 2024 |
| Acer          | Aspire A515-47              | [2d5cce174d](https://linux-hardware.org/?probe=2d5cce174d) | Jul 10, 2024 |
| Acer          | Aspire A515-47              | [5f4f7526e8](https://linux-hardware.org/?probe=5f4f7526e8) | Jul 10, 2024 |
| HP            | Compaq nw8440 (RH415EA#A... | [c12a51db40](https://linux-hardware.org/?probe=c12a51db40) | Jun 26, 2024 |
| HP            | Compaq nw8440 (RH415EA#A... | [5b21cd9393](https://linux-hardware.org/?probe=5b21cd9393) | Jun 26, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [a40ce4c093](https://linux-hardware.org/?probe=a40ce4c093) | Jun 18, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c9a4221ee5](https://linux-hardware.org/?probe=c9a4221ee5) | Jun 14, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [5b9182e0c0](https://linux-hardware.org/?probe=5b9182e0c0) | Jun 10, 2024 |
| HP            | ProBook 470 G4              | [ad0c9b74a2](https://linux-hardware.org/?probe=ad0c9b74a2) | May 31, 2024 |
| HP            | Laptop 15-ra0xx             | [0be312cffc](https://linux-hardware.org/?probe=0be312cffc) | May 28, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [aa1f7ff9ac](https://linux-hardware.org/?probe=aa1f7ff9ac) | May 21, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0c1cb2dc27](https://linux-hardware.org/?probe=0c1cb2dc27) | May 12, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e3f9b42de5](https://linux-hardware.org/?probe=e3f9b42de5) | May 12, 2024 |
| HP            | EliteBook 840 G4            | [d725ec8595](https://linux-hardware.org/?probe=d725ec8595) | May 09, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | [eac9faa98c](https://linux-hardware.org/?probe=eac9faa98c) | May 03, 2024 |
| Chuwi         | CoreBook X                  | [deafd4078a](https://linux-hardware.org/?probe=deafd4078a) | Apr 20, 2024 |
| HP            | Laptop 15s-eq2xxx           | [16bde4de91](https://linux-hardware.org/?probe=16bde4de91) | Apr 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1b76135004](https://linux-hardware.org/?probe=1b76135004) | Mar 24, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [32321231e1](https://linux-hardware.org/?probe=32321231e1) | Mar 24, 2024 |
| HP            | EliteBook 8570w             | [4b83d77529](https://linux-hardware.org/?probe=4b83d77529) | Mar 10, 2024 |
| HP            | EliteBook 830 G5            | [b999903479](https://linux-hardware.org/?probe=b999903479) | Mar 09, 2024 |
| Acer          | Aspire 5742G                | [ec33f6391f](https://linux-hardware.org/?probe=ec33f6391f) | Feb 27, 2024 |
| Acer          | Aspire 5742G                | [4ab95b25ed](https://linux-hardware.org/?probe=4ab95b25ed) | Feb 24, 2024 |
| HP            | ProBook 4730s               | [e3bd4bfeae](https://linux-hardware.org/?probe=e3bd4bfeae) | Feb 16, 2024 |
| HP            | ProBook 4730s               | [b71e2386cc](https://linux-hardware.org/?probe=b71e2386cc) | Feb 16, 2024 |
| Sony          | SVF1521V1EB                 | [ec01d30645](https://linux-hardware.org/?probe=ec01d30645) | Feb 12, 2024 |
| HP            | ProBook 450 G3              | [d367c2a560](https://linux-hardware.org/?probe=d367c2a560) | Feb 11, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [4ee3aae45e](https://linux-hardware.org/?probe=4ee3aae45e) | Feb 11, 2024 |
| Sony          | SVF1521V1EB                 | [3ec5455de7](https://linux-hardware.org/?probe=3ec5455de7) | Feb 10, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [f5fd1fd3ae](https://linux-hardware.org/?probe=f5fd1fd3ae) | Feb 09, 2024 |
| Acer          | Swift SFX14-51G             | [9649ed5351](https://linux-hardware.org/?probe=9649ed5351) | Feb 05, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [51c4f07d2f](https://linux-hardware.org/?probe=51c4f07d2f) | Feb 04, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [ba4fdf1b5b](https://linux-hardware.org/?probe=ba4fdf1b5b) | Feb 04, 2024 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [3e0e2fd80a](https://linux-hardware.org/?probe=3e0e2fd80a) | Feb 03, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5fac7fde98](https://linux-hardware.org/?probe=5fac7fde98) | Jan 27, 2024 |
| HP            | Pavilion Notebook           | [91f1ca34ad](https://linux-hardware.org/?probe=91f1ca34ad) | Jan 19, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [de6b5ead5b](https://linux-hardware.org/?probe=de6b5ead5b) | Dec 24, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [d153c701cc](https://linux-hardware.org/?probe=d153c701cc) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [398233e395](https://linux-hardware.org/?probe=398233e395) | Dec 23, 2023 |
| Dell          | XPS 15 9500                 | [941f6d849a](https://linux-hardware.org/?probe=941f6d849a) | Dec 18, 2023 |
| Dell          | Precision 5510              | [8157bb9bc9](https://linux-hardware.org/?probe=8157bb9bc9) | Dec 12, 2023 |
| Dell          | Precision 5510              | [a14acbd791](https://linux-hardware.org/?probe=a14acbd791) | Dec 12, 2023 |
| Dell          | Latitude 7490               | [c964863876](https://linux-hardware.org/?probe=c964863876) | Nov 20, 2023 |
| HP            | Stream Notebook PC 13       | [946612aeb4](https://linux-hardware.org/?probe=946612aeb4) | Nov 19, 2023 |
| HP            | Stream Notebook PC 13       | [9cf67aa27c](https://linux-hardware.org/?probe=9cf67aa27c) | Nov 19, 2023 |
| Dynabook      | Satellite Pro C40-G-109     | [32a21ea7ad](https://linux-hardware.org/?probe=32a21ea7ad) | Nov 10, 2023 |
| Lenovo        | ThinkPad T520 4243RU3       | [5095529d19](https://linux-hardware.org/?probe=5095529d19) | Nov 05, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [4ba182f0d5](https://linux-hardware.org/?probe=4ba182f0d5) | Nov 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d64009bcc1](https://linux-hardware.org/?probe=d64009bcc1) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f5d0c4d34a](https://linux-hardware.org/?probe=f5d0c4d34a) | Nov 01, 2023 |
| Fujitsu       | LIFEBOOK S792               | [5eaa7922e7](https://linux-hardware.org/?probe=5eaa7922e7) | Oct 27, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [38046f165d](https://linux-hardware.org/?probe=38046f165d) | Oct 26, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [7830b3ae27](https://linux-hardware.org/?probe=7830b3ae27) | Oct 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [db906f78dd](https://linux-hardware.org/?probe=db906f78dd) | Sep 06, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [aefedc3b34](https://linux-hardware.org/?probe=aefedc3b34) | Sep 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| ASUSTek       | GL503VS                     | [767317b527](https://linux-hardware.org/?probe=767317b527) | Jun 20, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | EliteBook Folio 9470m       | [73720c6437](https://linux-hardware.org/?probe=73720c6437) | Jun 12, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| HP            | ZBook 17 G2                 | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Dell          | Latitude D630               | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ed72b68c39](https://linux-hardware.org/?probe=ed72b68c39) | May 13, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Medion        | E6232                       | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| HP            | ProBook 4730s               | [c4f4cf46cf](https://linux-hardware.org/?probe=c4f4cf46cf) | May 01, 2023 |
| HP            | ProBook 4730s               | [bd90580b35](https://linux-hardware.org/?probe=bd90580b35) | May 01, 2023 |
| Acer          | Nitro AN517-42              | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | XPS 13 9310                 | [5c9b8fef2e](https://linux-hardware.org/?probe=5c9b8fef2e) | Apr 21, 2023 |
| ASUSTek       | UX430UNR                    | [d8ed935b86](https://linux-hardware.org/?probe=d8ed935b86) | Apr 19, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| HP            | 255 G8 Notebook PC          | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| HP            | Compaq 6730s                | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| HP            | ProBook 450 G6              | [acbfa27478](https://linux-hardware.org/?probe=acbfa27478) | Mar 20, 2023 |
| HP            | ProBook 450 G6              | [d8c39b84d1](https://linux-hardware.org/?probe=d8c39b84d1) | Mar 20, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | Latitude 5530               | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| HP            | ZBook 17 G2                 | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Toshiba       | Satellite Pro R50-E         | [b039ed22c6](https://linux-hardware.org/?probe=b039ed22c6) | Mar 01, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| HP            | ProBook 4530s               | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [475265e1f8](https://linux-hardware.org/?probe=475265e1f8) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK A530               | [0698054de0](https://linux-hardware.org/?probe=0698054de0) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK A530               | [122005ade3](https://linux-hardware.org/?probe=122005ade3) | Jan 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [74bf687e30](https://linux-hardware.org/?probe=74bf687e30) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [b3c2be78b3](https://linux-hardware.org/?probe=b3c2be78b3) | Jan 14, 2023 |
| HP            | EliteBook 830 G5            | [6a11a77a53](https://linux-hardware.org/?probe=6a11a77a53) | Jan 12, 2023 |
| HP            | EliteBook 830 G5            | [09f51f5cd3](https://linux-hardware.org/?probe=09f51f5cd3) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [82ca2971d9](https://linux-hardware.org/?probe=82ca2971d9) | Jan 12, 2023 |
| Lenovo        | G50-30 80G0                 | [7c432a386b](https://linux-hardware.org/?probe=7c432a386b) | Jan 11, 2023 |
| Lenovo        | G500 20236                  | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Dell          | Inspiron 1501               | [1bb0000755](https://linux-hardware.org/?probe=1bb0000755) | Dec 16, 2022 |
| HUAWEI        | HKD-WXX                     | [a7b446df37](https://linux-hardware.org/?probe=a7b446df37) | Dec 08, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Toshiba       | Satellite R630              | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [f19b2c0b81](https://linux-hardware.org/?probe=f19b2c0b81) | Dec 03, 2022 |
| ASUSTek       | 1225B                       | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| HUAWEI        | HKD-WXX                     | [5271fa9ef9](https://linux-hardware.org/?probe=5271fa9ef9) | Nov 26, 2022 |
| ASUSTek       | X553MA                      | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Toshiba       | TECRA A11                   | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| HP            | Pavilion g7                 | [19b206ba2f](https://linux-hardware.org/?probe=19b206ba2f) | Sep 25, 2022 |
| HP            | ProBook 4340s               | [668ffa05ea](https://linux-hardware.org/?probe=668ffa05ea) | Sep 18, 2022 |
| HP            | ProBook 4340s               | [1abbd84e9c](https://linux-hardware.org/?probe=1abbd84e9c) | Sep 18, 2022 |
| Toshiba       | TECRA S10                   | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| HP            | Unknown                     | [692825c1eb](https://linux-hardware.org/?probe=692825c1eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [273e5229a4](https://linux-hardware.org/?probe=273e5229a4) | Aug 30, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| Framework     | Laptop                      | [c52019fe10](https://linux-hardware.org/?probe=c52019fe10) | Aug 07, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [b9c35e80d2](https://linux-hardware.org/?probe=b9c35e80d2) | Aug 06, 2022 |
| Lenovo        | B50-30 20382                | [6ab4942a20](https://linux-hardware.org/?probe=6ab4942a20) | Jul 16, 2022 |
| Lenovo        | B50-30 20382                | [d9573dc3e6](https://linux-hardware.org/?probe=d9573dc3e6) | Jul 08, 2022 |
| Dell          | Inspiron 1501               | [f6efa72c1f](https://linux-hardware.org/?probe=f6efa72c1f) | Jul 01, 2022 |
| HP            | 255 G8 Notebook PC          | [cae0332804](https://linux-hardware.org/?probe=cae0332804) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | [e65ead281f](https://linux-hardware.org/?probe=e65ead281f) | Jun 17, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| Toshiba       | Satellite Pro U400          | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | N71Vg                       | [33a6047c0b](https://linux-hardware.org/?probe=33a6047c0b) | May 14, 2022 |
| ASUSTek       | N71Vg                       | [86d9e911f1](https://linux-hardware.org/?probe=86d9e911f1) | May 13, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| HP            | ZBook 17 G2                 | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Dell          | Precision 5540              | [38d9bed727](https://linux-hardware.org/?probe=38d9bed727) | Mar 21, 2022 |
| Fujitsu       | LIFEBOOK S792               | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| HP            | Compaq nw8440 (RH415EA#A... | [55a6d982b3](https://linux-hardware.org/?probe=55a6d982b3) | Mar 07, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| HP            | kip                         | [4d6e1264c7](https://linux-hardware.org/?probe=4d6e1264c7) | Mar 02, 2022 |
| HP            | kip                         | [a6ab5d4d8a](https://linux-hardware.org/?probe=a6ab5d4d8a) | Mar 01, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| HP            | Pavilion dv7                | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| ASUSTek       | X550JX                      | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| HP            | Pavilion dv7                | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| HP            | ProBook 4730s               | [5ffa4bce13](https://linux-hardware.org/?probe=5ffa4bce13) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| HP            | EliteBook 8570w             | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| Acer          | Predator PH317-52           | [ec43c5baa2](https://linux-hardware.org/?probe=ec43c5baa2) | Feb 07, 2022 |
| ASUSTek       | X750LN                      | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | EliteBook 8570w             | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [f2bae7651d](https://linux-hardware.org/?probe=f2bae7651d) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| HP            | ProBook 450 G5              | [8887022aa7](https://linux-hardware.org/?probe=8887022aa7) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [6b40a0f2c5](https://linux-hardware.org/?probe=6b40a0f2c5) | Dec 21, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [31c2b40e84](https://linux-hardware.org/?probe=31c2b40e84) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6238c622ad](https://linux-hardware.org/?probe=6238c622ad) | Dec 18, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [45ac665485](https://linux-hardware.org/?probe=45ac665485) | Dec 10, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [e898d8c017](https://linux-hardware.org/?probe=e898d8c017) | Nov 20, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [e37febb0b3](https://linux-hardware.org/?probe=e37febb0b3) | Nov 18, 2021 |
| HP            | 250 G3                      | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| HP            | 250 G3                      | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | XPS 13 7390                 | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| Dell          | XPS 13 9310                 | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Pavilion dv7                | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| HP            | EliteBook 8760w             | [99fb47dc2b](https://linux-hardware.org/?probe=99fb47dc2b) | Oct 28, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| HP            | EliteBook Folio 9470m       | [f66ba65dc8](https://linux-hardware.org/?probe=f66ba65dc8) | Oct 22, 2021 |
| HP            | EliteBook Folio 9470m       | [1d50915627](https://linux-hardware.org/?probe=1d50915627) | Oct 21, 2021 |
| Toshiba       | Satellite L750              | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | [2cbf85194c](https://linux-hardware.org/?probe=2cbf85194c) | Oct 14, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [f424437bd1](https://linux-hardware.org/?probe=f424437bd1) | Oct 01, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [c85622ebee](https://linux-hardware.org/?probe=c85622ebee) | Sep 29, 2021 |
| HP            | ProBook 450 G1              | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [8c7e729202](https://linux-hardware.org/?probe=8c7e729202) | Aug 19, 2021 |
| HP            | 2000                        | [2909375db3](https://linux-hardware.org/?probe=2909375db3) | Aug 06, 2021 |
| HP            | 2000                        | [df5d5e05c6](https://linux-hardware.org/?probe=df5d5e05c6) | Aug 06, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| HP            | 2000                        | [9fbfcf95d2](https://linux-hardware.org/?probe=9fbfcf95d2) | Jul 29, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| HP            | 2000                        | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| HP            | 2000                        | [f3c7f85988](https://linux-hardware.org/?probe=f3c7f85988) | Jul 21, 2021 |
| HP            | 2000                        | [e6019f1bd3](https://linux-hardware.org/?probe=e6019f1bd3) | Jul 12, 2021 |
| HP            | 2000                        | [6a169f2d87](https://linux-hardware.org/?probe=6a169f2d87) | Jun 22, 2021 |
| HP            | 2000                        | [b2e5075aaf](https://linux-hardware.org/?probe=b2e5075aaf) | Jun 17, 2021 |
| HP            | EliteBook 8440p             | [330d2214c6](https://linux-hardware.org/?probe=330d2214c6) | Jun 10, 2021 |
| HP            | 2000                        | [6a1c91ae8d](https://linux-hardware.org/?probe=6a1c91ae8d) | Jun 07, 2021 |
| Acer          | Nitro AN517-52              | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Lenovo        | ThinkPad T61 8897CTO        | [6cfc0271ba](https://linux-hardware.org/?probe=6cfc0271ba) | Jun 03, 2021 |
| HP            | 250 G7 Notebook PC          | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| HP            | 2000                        | [1469c94a5f](https://linux-hardware.org/?probe=1469c94a5f) | May 17, 2021 |
| HP            | EliteBook 830 G6            | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [c59fd76192](https://linux-hardware.org/?probe=c59fd76192) | Apr 14, 2021 |
| HP            | EliteBook 8440p             | [d0a4124a2a](https://linux-hardware.org/?probe=d0a4124a2a) | Apr 10, 2021 |
| HP            | ProBook 4515s (VC377ES#A... | [2c84f60b0d](https://linux-hardware.org/?probe=2c84f60b0d) | Apr 09, 2021 |
| HP            | ProBook 4740s               | [cf941af09e](https://linux-hardware.org/?probe=cf941af09e) | Apr 08, 2021 |
| Dell          | Latitude 5501               | [474510883b](https://linux-hardware.org/?probe=474510883b) | Mar 22, 2021 |
| HP            | ProBook 450 G5              | [49b951896d](https://linux-hardware.org/?probe=49b951896d) | Mar 17, 2021 |
| ASUSTek       | K72Jr                       | [2d9ae8527d](https://linux-hardware.org/?probe=2d9ae8527d) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | [e434a21940](https://linux-hardware.org/?probe=e434a21940) | Mar 04, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [6fdf12c20c](https://linux-hardware.org/?probe=6fdf12c20c) | Feb 28, 2021 |
| Dell          | XPS 13 7390                 | [9dc547fceb](https://linux-hardware.org/?probe=9dc547fceb) | Feb 26, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [d1ade3e39d](https://linux-hardware.org/?probe=d1ade3e39d) | Feb 08, 2021 |
| Acer          | Aspire A315-42              | [95958aa225](https://linux-hardware.org/?probe=95958aa225) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | [0e552a01e6](https://linux-hardware.org/?probe=0e552a01e6) | Feb 03, 2021 |
| Dell          | XPS 13 7390                 | [1f3dc6c825](https://linux-hardware.org/?probe=1f3dc6c825) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [7e828e295f](https://linux-hardware.org/?probe=7e828e295f) | Jan 20, 2021 |
| HP            | ZBook 15u G3                | [812e100310](https://linux-hardware.org/?probe=812e100310) | Jan 12, 2021 |
| HP            | ZBook 15u G3                | [30332e1d71](https://linux-hardware.org/?probe=30332e1d71) | Jan 12, 2021 |
| HP            | Laptop 15-ra0xx             | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| HP            | ProBook 4730s               | [e7ab1bcd89](https://linux-hardware.org/?probe=e7ab1bcd89) | Jan 06, 2021 |
| HP            | EliteBook 6930p             | [e9c1683321](https://linux-hardware.org/?probe=e9c1683321) | Jan 04, 2021 |
| ASUSTek       | UX31E                       | [912f3fe702](https://linux-hardware.org/?probe=912f3fe702) | Dec 25, 2020 |
| HP            | 255 G7 Notebook PC          | [d759211bb6](https://linux-hardware.org/?probe=d759211bb6) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| ASUSTek       | G771JW                      | [b103133d69](https://linux-hardware.org/?probe=b103133d69) | Dec 16, 2020 |
| Dell          | Inspiron 3542               | [4260174285](https://linux-hardware.org/?probe=4260174285) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| Dell          | Latitude D630               | [92ccc6100c](https://linux-hardware.org/?probe=92ccc6100c) | Dec 05, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [e2ffbd65b4](https://linux-hardware.org/?probe=e2ffbd65b4) | Dec 04, 2020 |
| Acer          | Aspire A315-42              | [1b5583ba18](https://linux-hardware.org/?probe=1b5583ba18) | Nov 23, 2020 |
| HP            | 250 G7 Notebook PC          | [bc3c7d8910](https://linux-hardware.org/?probe=bc3c7d8910) | Nov 22, 2020 |
| HP            | 250 G7 Notebook PC          | [db1f0e1247](https://linux-hardware.org/?probe=db1f0e1247) | Nov 22, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [5978ba6a13](https://linux-hardware.org/?probe=5978ba6a13) | Nov 22, 2020 |
| HP            | 470 G7 Notebook PC          | [f0d3574818](https://linux-hardware.org/?probe=f0d3574818) | Nov 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8783481f8a](https://linux-hardware.org/?probe=8783481f8a) | Nov 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [1298138505](https://linux-hardware.org/?probe=1298138505) | Nov 13, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| HP            | 255 G7 Notebook PC          | [3ad72de5c7](https://linux-hardware.org/?probe=3ad72de5c7) | Oct 09, 2020 |
| HP            | 255 G7 Notebook PC          | [2c625d510e](https://linux-hardware.org/?probe=2c625d510e) | Oct 03, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [1a20b51c58](https://linux-hardware.org/?probe=1a20b51c58) | Sep 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [ca8c660b91](https://linux-hardware.org/?probe=ca8c660b91) | Sep 24, 2020 |
| HP            | 255 G7 Notebook PC          | [8bba4f976e](https://linux-hardware.org/?probe=8bba4f976e) | Sep 20, 2020 |
| Dell          | Vostro 3550                 | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| PC Special... | Fusion IV                   | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [a87567fe16](https://linux-hardware.org/?probe=a87567fe16) | Aug 27, 2020 |
| HP            | ProBook 4540s               | [32346e7861](https://linux-hardware.org/?probe=32346e7861) | Aug 26, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [438b0df832](https://linux-hardware.org/?probe=438b0df832) | Jul 21, 2020 |
| HP            | 2000                        | [1facf761c9](https://linux-hardware.org/?probe=1facf761c9) | Jul 19, 2020 |
| Lenovo        | ThinkPad T420 423662G       | [f0e52bdb36](https://linux-hardware.org/?probe=f0e52bdb36) | Jul 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [b78049616e](https://linux-hardware.org/?probe=b78049616e) | Jul 09, 2020 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [758a8710d7](https://linux-hardware.org/?probe=758a8710d7) | Jun 29, 2020 |
| HP            | ProBook 4540s               | [98a9e4902b](https://linux-hardware.org/?probe=98a9e4902b) | Jun 08, 2020 |
| HP            | ProBook 4540s               | [2b515ca642](https://linux-hardware.org/?probe=2b515ca642) | May 31, 2020 |
| HP            | EliteBook 8540w             | [a8e5567ca8](https://linux-hardware.org/?probe=a8e5567ca8) | May 30, 2020 |
| HP            | EliteBook 840 G6            | [bea6687b8b](https://linux-hardware.org/?probe=bea6687b8b) | May 27, 2020 |
| Acer          | Aspire V3-771               | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| HP            | ProBook 470 G2              | [d39ca7c5fa](https://linux-hardware.org/?probe=d39ca7c5fa) | May 15, 2020 |
| HP            | 15                          | [fa65501be6](https://linux-hardware.org/?probe=fa65501be6) | May 10, 2020 |
| Dell          | Inspiron 5570               | [91d3944426](https://linux-hardware.org/?probe=91d3944426) | May 10, 2020 |
| HP            | 250 G6 Notebook PC          | [ee92e64256](https://linux-hardware.org/?probe=ee92e64256) | May 07, 2020 |
| HP            | ProBook 4515s (VC377ES#A... | [3ec25a2e7a](https://linux-hardware.org/?probe=3ec25a2e7a) | May 01, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [a1de2f2fe9](https://linux-hardware.org/?probe=a1de2f2fe9) | Apr 18, 2020 |
| Lenovo        | ThinkPad T590 20N5S0YN00    | [0efab1d69f](https://linux-hardware.org/?probe=0efab1d69f) | Apr 08, 2020 |
| ASUSTek       | X750LB                      | [a7c5fb20f8](https://linux-hardware.org/?probe=a7c5fb20f8) | Mar 28, 2020 |
| Lenovo        | G510 20238                  | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [ff84ae40b8](https://linux-hardware.org/?probe=ff84ae40b8) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [0877aa97e7](https://linux-hardware.org/?probe=0877aa97e7) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [677f41b346](https://linux-hardware.org/?probe=677f41b346) | Mar 21, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | [48cd703e5b](https://linux-hardware.org/?probe=48cd703e5b) | Mar 05, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | [e6a4ad2c61](https://linux-hardware.org/?probe=e6a4ad2c61) | Mar 04, 2020 |
| HP            | EliteBook 8760w             | [624fd6f7fa](https://linux-hardware.org/?probe=624fd6f7fa) | Mar 01, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [608fef5510](https://linux-hardware.org/?probe=608fef5510) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB002BSC    | [b20e37d478](https://linux-hardware.org/?probe=b20e37d478) | Jan 06, 2020 |
| Dell          | Latitude 5500               | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| HP            | EliteBook 850 G6            | [0d7f336b82](https://linux-hardware.org/?probe=0d7f336b82) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [d853ff31e4](https://linux-hardware.org/?probe=d853ff31e4) | Dec 08, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [25e0799d44](https://linux-hardware.org/?probe=25e0799d44) | Dec 08, 2019 |
| MSI           | GP60 2OD                    | [f450b0d5d4](https://linux-hardware.org/?probe=f450b0d5d4) | Oct 20, 2019 |
| HP            | EliteBook 6930p             | [b11cbf51cb](https://linux-hardware.org/?probe=b11cbf51cb) | Sep 28, 2019 |
| Lenovo        | G585 20137                  | [084d318c5c](https://linux-hardware.org/?probe=084d318c5c) | Sep 16, 2019 |
| Acer          | Aspire E5-573G              | [d2242a3cd4](https://linux-hardware.org/?probe=d2242a3cd4) | Sep 02, 2019 |
| eMachines     | G730                        | [af8b954f82](https://linux-hardware.org/?probe=af8b954f82) | Aug 29, 2019 |
| ASUSTek       | G751JT                      | [a5f96019bd](https://linux-hardware.org/?probe=a5f96019bd) | Aug 04, 2019 |
| eMachines     | G730                        | [5073ea0163](https://linux-hardware.org/?probe=5073ea0163) | Aug 02, 2019 |
| eMachines     | G730                        | [4f0fa60c8d](https://linux-hardware.org/?probe=4f0fa60c8d) | Jul 31, 2019 |
| HP            | Pavilion 15                 | [edf229fa5e](https://linux-hardware.org/?probe=edf229fa5e) | Jul 22, 2019 |
| Toshiba       | QOSMIO X500                 | [34905cb301](https://linux-hardware.org/?probe=34905cb301) | Jul 15, 2019 |
| ASUSTek       | G751JT                      | [3a17d38bdd](https://linux-hardware.org/?probe=3a17d38bdd) | Jul 09, 2019 |
| Lenovo        | ThinkPad T410 2522A92       | [68640c00d9](https://linux-hardware.org/?probe=68640c00d9) | Jun 09, 2019 |
| HP            | Compaq 325                  | [4161a93030](https://linux-hardware.org/?probe=4161a93030) | May 16, 2019 |
| HP            | ProBook 4710s               | [54ed79f58d](https://linux-hardware.org/?probe=54ed79f58d) | May 15, 2019 |
| HP            | Compaq 325                  | [b9dadeece3](https://linux-hardware.org/?probe=b9dadeece3) | May 12, 2019 |
| HP            | Compaq 6720s                | [0e2550055b](https://linux-hardware.org/?probe=0e2550055b) | May 07, 2019 |
| Gigabyte      | P65                         | [6dfb59f508](https://linux-hardware.org/?probe=6dfb59f508) | May 07, 2019 |
| HP            | ZBook 14 G2                 | [e1463c9ca8](https://linux-hardware.org/?probe=e1463c9ca8) | Apr 23, 2019 |
| Lenovo        | ThinkPad W530 24479K4       | [7d56ca80ca](https://linux-hardware.org/?probe=7d56ca80ca) | Apr 22, 2019 |
| ASUSTek       | X751NV                      | [a189d47b9a](https://linux-hardware.org/?probe=a189d47b9a) | Apr 09, 2019 |
| Dell          | Latitude E6500              | [abdbb02998](https://linux-hardware.org/?probe=abdbb02998) | Feb 23, 2019 |
| Medion        | E7218                       | [5d97b97758](https://linux-hardware.org/?probe=5d97b97758) | Dec 16, 2018 |
| HP            | Unknown                     | [696e11ac42](https://linux-hardware.org/?probe=696e11ac42) | Nov 29, 2018 |
| HP            | Unknown                     | [121bf767df](https://linux-hardware.org/?probe=121bf767df) | Nov 29, 2018 |
| Lenovo        | ThinkPad Edge 326054G       | [6754682a3b](https://linux-hardware.org/?probe=6754682a3b) | Sep 16, 2017 |
| Lenovo        | ThinkPad Edge 326054G       | [c208f4b144](https://linux-hardware.org/?probe=c208f4b144) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 28        | 8.83%   |
| Ubuntu 22.04                 | 21        | 6.62%   |
| Ubuntu 18.04                 | 15        | 4.73%   |
| Arch Rolling                 | 10        | 3.15%   |
| Debian 11                    | 9         | 2.84%   |
| Zorin 17                     | 7         | 2.21%   |
| Debian 12                    | 6         | 1.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.58%   |
| Kubuntu 22.04                | 5         | 1.58%   |
| KDE neon 22.04               | 5         | 1.58%   |
| KDE neon 20.04               | 5         | 1.58%   |
| Fedora 37                    | 5         | 1.58%   |
| ArcoLinux Rolling            | 5         | 1.58%   |
| Zorin 16                     | 4         | 1.26%   |
| Zorin 15                     | 4         | 1.26%   |
| OpenMandriva 4.3             | 4         | 1.26%   |
| Fedora 41                    | 4         | 1.26%   |
| Fedora 40                    | 4         | 1.26%   |
| Fedora 34                    | 4         | 1.26%   |
| Fedora 33                    | 4         | 1.26%   |
| Arch                         | 4         | 1.26%   |
| Xubuntu 22.04                | 3         | 0.95%   |
| Xubuntu 20.04                | 3         | 0.95%   |
| Ubuntu 24.04                 | 3         | 0.95%   |
| OpenMandriva 4.2             | 3         | 0.95%   |
| OpenMandriva 24.12           | 3         | 0.95%   |
| Manjaro                      | 3         | 0.95%   |
| Linux Mint 21.3              | 3         | 0.95%   |
| Linux Mint 19.1              | 3         | 0.95%   |
| Kubuntu 21.10                | 3         | 0.95%   |
| Kubuntu 20.04                | 3         | 0.95%   |
| Debian Testing               | 3         | 0.95%   |
| Zorin 18                     | 2         | 0.63%   |
| Ubuntu Unity 16.04           | 2         | 0.63%   |
| Ubuntu Budgie 20.04          | 2         | 0.63%   |
| Ubuntu 21.10                 | 2         | 0.63%   |
| Ubuntu 21.04                 | 2         | 0.63%   |
| Ubuntu 20.10                 | 2         | 0.63%   |
| Ubuntu 19.10                 | 2         | 0.63%   |
| Pop!_OS 22.04                | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 75        | 24.92%  |
| Fedora           | 26        | 8.64%   |
| Debian           | 21        | 6.98%   |
| Linux Mint       | 19        | 6.31%   |
| Kubuntu          | 19        | 6.31%   |
| OpenMandriva     | 18        | 5.98%   |
| Zorin            | 17        | 5.65%   |
| Arch             | 14        | 4.65%   |
| Manjaro          | 11        | 3.65%   |
| KDE neon         | 11        | 3.65%   |
| Endless          | 11        | 3.65%   |
| openSUSE         | 8         | 2.66%   |
| Xubuntu          | 6         | 1.99%   |
| Pop!_OS          | 5         | 1.66%   |
| ArcoLinux        | 5         | 1.66%   |
| EndeavourOS      | 4         | 1.33%   |
| Ubuntu Budgie    | 3         | 1%      |
| Ubuntu Unity     | 2         | 0.66%   |
| ROSA             | 2         | 0.66%   |
| Q4OS             | 2         | 0.66%   |
| NixOS            | 2         | 0.66%   |
| Lubuntu          | 2         | 0.66%   |
| LMDE             | 2         | 0.66%   |
| Kali             | 2         | 0.66%   |
| Gentoo           | 2         | 0.66%   |
| Garuda Linux     | 2         | 0.66%   |
| Elementary       | 2         | 0.66%   |
| Ubuntu MATE      | 1         | 0.33%   |
| org.kde.Platform | 1         | 0.33%   |
| Nobara           | 1         | 0.33%   |
| Dts-distro       | 1         | 0.33%   |
| Clear Linux      | 1         | 0.33%   |
| Chrome OS        | 1         | 0.33%   |
| BlackPanther     | 1         | 0.33%   |
| Artix            | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 4         | 1.14%   |
| 4.18.0-15-generic        | 4         | 1.14%   |
| 6.5.0-10-generic         | 3         | 0.85%   |
| 6.12.1-desktop-1omv2490  | 3         | 0.85%   |
| 5.8.0-41-generic         | 3         | 0.85%   |
| 5.4.0-216-generic        | 3         | 0.85%   |
| 5.3.0-40-generic         | 3         | 0.85%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.85%   |
| 5.15.0-57-generic        | 3         | 0.85%   |
| 5.15.0-56-generic        | 3         | 0.85%   |
| 5.15.0-43-generic        | 3         | 0.85%   |
| 5.13.0-41-generic        | 3         | 0.85%   |
| 5.13.0-30-generic        | 3         | 0.85%   |
| 5.13.0-28-generic        | 3         | 0.85%   |
| 5.13.0-21-generic        | 3         | 0.85%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.85%   |
| 6.8.0-51-generic         | 2         | 0.57%   |
| 6.8.0-49-generic         | 2         | 0.57%   |
| 6.8.0-48-generic         | 2         | 0.57%   |
| 6.8.0-47-generic         | 2         | 0.57%   |
| 6.5.0-45-generic         | 2         | 0.57%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.57%   |
| 6.3.9-arch1-1            | 2         | 0.57%   |
| 6.2.0-36-generic         | 2         | 0.57%   |
| 6.2.0-31-generic         | 2         | 0.57%   |
| 6.14.2-desktop-3omv2590  | 2         | 0.57%   |
| 6.14.0-33-generic        | 2         | 0.57%   |
| 6.13.7-desktop-1omv2590  | 2         | 0.57%   |
| 6.11.0-21-generic        | 2         | 0.57%   |
| 5.8.0-44-generic         | 2         | 0.57%   |
| 5.8.0-14-generic         | 2         | 0.57%   |
| 5.6.0-1-amd64            | 2         | 0.57%   |
| 5.4.0-70-generic         | 2         | 0.57%   |
| 5.4.0-56-generic         | 2         | 0.57%   |
| 5.4.0-54-generic         | 2         | 0.57%   |
| 5.4.0-48-generic         | 2         | 0.57%   |
| 5.4.0-40-generic         | 2         | 0.57%   |
| 5.4.0-33-generic         | 2         | 0.57%   |
| 5.4.0-28-generic         | 2         | 0.57%   |
| 5.4.0-26-generic         | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 10.91%  |
| 5.15.0  | 24        | 7.27%   |
| 5.13.0  | 17        | 5.15%   |
| 6.5.0   | 14        | 4.24%   |
| 6.8.0   | 12        | 3.64%   |
| 5.11.0  | 12        | 3.64%   |
| 4.15.0  | 12        | 3.64%   |
| 5.10.0  | 11        | 3.33%   |
| 5.8.0   | 9         | 2.73%   |
| 6.2.0   | 8         | 2.42%   |
| 6.1.0   | 8         | 2.42%   |
| 5.3.0   | 8         | 2.42%   |
| 4.18.0  | 8         | 2.42%   |
| 5.19.0  | 7         | 2.12%   |
| 6.14.0  | 5         | 1.52%   |
| 5.0.0   | 5         | 1.52%   |
| 6.12.1  | 4         | 1.21%   |
| 6.11.0  | 4         | 1.21%   |
| 5.10.14 | 4         | 1.21%   |
| 6.4.11  | 3         | 0.91%   |
| 5.6.0   | 3         | 0.91%   |
| 5.16.7  | 3         | 0.91%   |
| 6.8.9   | 2         | 0.61%   |
| 6.3.9   | 2         | 0.61%   |
| 6.2.6   | 2         | 0.61%   |
| 6.14.4  | 2         | 0.61%   |
| 6.14.2  | 2         | 0.61%   |
| 6.13.7  | 2         | 0.61%   |
| 6.12.48 | 2         | 0.61%   |
| 6.0.11  | 2         | 0.61%   |
| 5.14.21 | 2         | 0.61%   |
| 5.13.19 | 2         | 0.61%   |
| 6.9.3   | 1         | 0.3%    |
| 6.9.10  | 1         | 0.3%    |
| 6.9.1   | 1         | 0.3%    |
| 6.8.8   | 1         | 0.3%    |
| 6.8.7   | 1         | 0.3%    |
| 6.7.1   | 1         | 0.3%    |
| 6.6.7   | 1         | 0.3%    |
| 6.6.26  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 11.62%  |
| 5.15    | 30        | 9.17%   |
| 5.13    | 20        | 6.12%   |
| 6.8     | 16        | 4.89%   |
| 6.5     | 16        | 4.89%   |
| 6.2     | 15        | 4.59%   |
| 5.10    | 15        | 4.59%   |
| 6.1     | 14        | 4.28%   |
| 5.11    | 14        | 4.28%   |
| 5.8     | 13        | 3.98%   |
| 4.15    | 12        | 3.67%   |
| 6.14    | 10        | 3.06%   |
| 5.19    | 10        | 3.06%   |
| 6.12    | 9         | 2.75%   |
| 5.3     | 9         | 2.75%   |
| 4.18    | 9         | 2.75%   |
| 5.16    | 8         | 2.45%   |
| 6.11    | 7         | 2.14%   |
| 5.14    | 6         | 1.83%   |
| 5.0     | 5         | 1.53%   |
| 6.6     | 4         | 1.22%   |
| 6.4     | 4         | 1.22%   |
| 6.3     | 4         | 1.22%   |
| 6.13    | 4         | 1.22%   |
| 5.9     | 4         | 1.22%   |
| 5.6     | 4         | 1.22%   |
| 5.17    | 4         | 1.22%   |
| 6.9     | 3         | 0.92%   |
| 6.0     | 3         | 0.92%   |
| 5.12    | 3         | 0.92%   |
| 6.17    | 2         | 0.61%   |
| 6.10    | 2         | 0.61%   |
| 5.5     | 2         | 0.61%   |
| 4.19    | 2         | 0.61%   |
| 6.7     | 1         | 0.31%   |
| 5.7     | 1         | 0.31%   |
| 5.18    | 1         | 0.31%   |
| 4.9     | 1         | 0.31%   |
| 4.14    | 1         | 0.31%   |
| 4.1     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 278       | 97.2%   |
| i686   | 8         | 2.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 115       | 38.46%  |
| KDE5          | 57        | 19.06%  |
| Unknown       | 33        | 11.04%  |
| XFCE          | 23        | 7.69%   |
| X-Cinnamon    | 14        | 4.68%   |
| KDE6          | 13        | 4.35%   |
| MATE          | 8         | 2.68%   |
| LXQt          | 5         | 1.67%   |
| i3            | 4         | 1.34%   |
| Budgie        | 4         | 1.34%   |
| KDE           | 3         | 1%      |
| Endless:GNOME | 3         | 1%      |
| Cinnamon      | 3         | 1%      |
| Unity         | 2         | 0.67%   |
| Trinity       | 2         | 0.67%   |
| Pantheon      | 2         | 0.67%   |
| LXDE          | 2         | 0.67%   |
| Openbox       | 1         | 0.33%   |
| none+awesome  | 1         | 0.33%   |
| KDE4          | 1         | 0.33%   |
| Hyprland      | 1         | 0.33%   |
| DWM           | 1         | 0.33%   |
| bspwm         | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 193       | 64.33%  |
| Wayland | 80        | 26.67%  |
| Unknown | 22        | 7.33%   |
| Tty     | 5         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 119       | 39.4%   |
| SDDM    | 67        | 22.19%  |
| GDM3    | 39        | 12.91%  |
| GDM     | 34        | 11.26%  |
| LightDM | 33        | 10.93%  |
| TDM     | 10        | 3.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 164       | 56.16%  |
| sl_SI   | 70        | 23.97%  |
| Unknown | 28        | 9.59%   |
| en_GB   | 13        | 4.45%   |
| en_SI   | 4         | 1.37%   |
| C       | 4         | 1.37%   |
| it_IT   | 3         | 1.03%   |
| hr_HR   | 2         | 0.68%   |
| pt_PT   | 1         | 0.34%   |
| POSIX   | 1         | 0.34%   |
| nl_NL   | 1         | 0.34%   |
| en_BW   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 160       | 54.79%  |
| BIOS | 132       | 45.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 214       | 71.57%  |
| Btrfs   | 36        | 12.04%  |
| Overlay | 19        | 6.35%   |
| Tmpfs   | 17        | 5.69%   |
| Unknown | 8         | 2.68%   |
| Zfs     | 1         | 0.33%   |
| Xfs     | 1         | 0.33%   |
| Rootfs  | 1         | 0.33%   |
| F2fs    | 1         | 0.33%   |
| Ext2    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 129       | 43.29%  |
| GPT     | 127       | 42.62%  |
| MBR     | 42        | 14.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 271       | 92.49%  |
| Yes       | 22        | 7.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 210       | 71.43%  |
| Yes       | 84        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 81        | 28.32%  |
| Lenovo              | 78        | 27.27%  |
| ASUSTek Computer    | 40        | 13.99%  |
| Dell                | 29        | 10.14%  |
| Acer                | 13        | 4.55%   |
| Toshiba             | 10        | 3.5%    |
| Fujitsu             | 4         | 1.4%    |
| TUXEDO              | 3         | 1.05%   |
| HUAWEI              | 3         | 1.05%   |
| Fujitsu Siemens     | 3         | 1.05%   |
| SLIMBOOK            | 2         | 0.7%    |
| MSI                 | 2         | 0.7%    |
| Medion              | 2         | 0.7%    |
| Apple               | 2         | 0.7%    |
| Valve               | 1         | 0.35%   |
| Sony                | 1         | 0.35%   |
| Schenker            | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| PC Specialist       | 1         | 0.35%   |
| Panasonic           | 1         | 0.35%   |
| Notebook            | 1         | 0.35%   |
| Gigabyte Technology | 1         | 0.35%   |
| Framework           | 1         | 0.35%   |
| eMachines           | 1         | 0.35%   |
| Dynabook            | 1         | 0.35%   |
| Clevo               | 1         | 0.35%   |
| Chuwi               | 1         | 0.35%   |
| A15HV01             | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 4         | 1.4%    |
| Dell Inspiron 5570                         | 3         | 1.05%   |
| Unknown                                    | 3         | 1.05%   |
| TUXEDO Aura 15 Gen1                        | 2         | 0.7%    |
| Toshiba Satellite L750                     | 2         | 0.7%    |
| Lenovo V15 G4 AMN 82YU                     | 2         | 0.7%    |
| Lenovo V15 G2 ALC 82KD                     | 2         | 0.7%    |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.7%    |
| HP ProBook 4740s                           | 2         | 0.7%    |
| HP ProBook 4730s                           | 2         | 0.7%    |
| HP ProBook 450 G6                          | 2         | 0.7%    |
| HP Laptop 15-ra0xx                         | 2         | 0.7%    |
| HP EliteBook 8760w                         | 2         | 0.7%    |
| HP EliteBook 8570w                         | 2         | 0.7%    |
| HP EliteBook 840 G6                        | 2         | 0.7%    |
| HP Compaq nw8440 (RH415EA#ABB)             | 2         | 0.7%    |
| HP 255 G8 Notebook PC                      | 2         | 0.7%    |
| Dell XPS 13 9310                           | 2         | 0.7%    |
| Dell Latitude D630                         | 2         | 0.7%    |
| Dell Inspiron 1501                         | 2         | 0.7%    |
| ASUS VivoBook 17_ASUS Laptop X705MA_X705MA | 2         | 0.7%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.7%    |
| Acer Aspire A315-42                        | 2         | 0.7%    |
| Valve Jupiter                              | 1         | 0.35%   |
| TUXEDO Polaris AMD Gen2 (REN)              | 1         | 0.35%   |
| Toshiba TECRA S10                          | 1         | 0.35%   |
| Toshiba TECRA A11                          | 1         | 0.35%   |
| Toshiba Satellite R630                     | 1         | 0.35%   |
| Toshiba Satellite Pro U400                 | 1         | 0.35%   |
| Toshiba Satellite Pro R50-E                | 1         | 0.35%   |
| Toshiba Satellite L650                     | 1         | 0.35%   |
| Toshiba Satellite A100                     | 1         | 0.35%   |
| Toshiba QOSMIO X500                        | 1         | 0.35%   |
| Sony SVF1521V1EB                           | 1         | 0.35%   |
| SLIMBOOK HERO-S-TGL-RTX                    | 1         | 0.35%   |
| SLIMBOOK EXCALIBUR-16-AMD7                 | 1         | 0.35%   |
| Schenker XMG FUSION 15 (XFU15M22)          | 1         | 0.35%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.35%   |
| PC Specialist Fusion IV                    | 1         | 0.35%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 48        | 16.78%  |
| HP ProBook                 | 19        | 6.64%   |
| HP EliteBook               | 18        | 6.29%   |
| Lenovo IdeaPad             | 10        | 3.5%    |
| Dell Latitude              | 9         | 3.15%   |
| Dell Inspiron              | 9         | 3.15%   |
| HP Pavilion                | 8         | 2.8%    |
| ASUS VivoBook              | 8         | 2.8%    |
| Toshiba Satellite          | 7         | 2.45%   |
| HP ZBook                   | 7         | 2.45%   |
| Dell XPS                   | 7         | 2.45%   |
| Acer Aspire                | 7         | 2.45%   |
| HP Compaq                  | 6         | 2.1%    |
| HP 255                     | 6         | 2.1%    |
| ASUS ASUS                  | 6         | 2.1%    |
| Lenovo V15                 | 4         | 1.4%    |
| Lenovo Legion              | 4         | 1.4%    |
| HP Laptop                  | 4         | 1.4%    |
| HP 250                     | 4         | 1.4%    |
| Fujitsu LIFEBOOK           | 4         | 1.4%    |
| ASUS Zenbook               | 4         | 1.4%    |
| Lenovo Yoga                | 3         | 1.05%   |
| Dell Precision             | 3         | 1.05%   |
| Unknown                    | 3         | 1.05%   |
| TUXEDO Aura                | 2         | 0.7%    |
| Toshiba TECRA              | 2         | 0.7%    |
| Lenovo ThinkBook           | 2         | 0.7%    |
| Fujitsu Siemens AMILO      | 2         | 0.7%    |
| ASUS ROG                   | 2         | 0.7%    |
| Acer Predator              | 2         | 0.7%    |
| Acer Nitro                 | 2         | 0.7%    |
| Valve Jupiter              | 1         | 0.35%   |
| TUXEDO Polaris             | 1         | 0.35%   |
| Toshiba QOSMIO             | 1         | 0.35%   |
| Sony SVF1521V1EB           | 1         | 0.35%   |
| SLIMBOOK HERO-S-TGL-RTX    | 1         | 0.35%   |
| SLIMBOOK EXCALIBUR-16-AMD7 | 1         | 0.35%   |
| Schenker XMG               | 1         | 0.35%   |
| Razer Blade                | 1         | 0.35%   |
| PC Specialist Fusion       | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 30        | 10.49%  |
| 2021 | 23        | 8.04%   |
| 2018 | 23        | 8.04%   |
| 2020 | 22        | 7.69%   |
| 2017 | 19        | 6.64%   |
| 2012 | 19        | 6.64%   |
| 2011 | 19        | 6.64%   |
| 2015 | 14        | 4.9%    |
| 2013 | 14        | 4.9%    |
| 2014 | 13        | 4.55%   |
| 2010 | 13        | 4.55%   |
| 2008 | 13        | 4.55%   |
| 2022 | 12        | 4.2%    |
| 2009 | 12        | 4.2%    |
| 2023 | 11        | 3.85%   |
| 2006 | 9         | 3.15%   |
| 2016 | 8         | 2.8%    |
| 2007 | 7         | 2.45%   |
| 2024 | 4         | 1.4%    |
| 2025 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 286       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 261       | 89.69%  |
| Enabled  | 30        | 10.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 21.8%   |
| 3.01-4.0    | 63        | 21.8%   |
| 8.01-16.0   | 61        | 21.11%  |
| 16.01-24.0  | 49        | 16.96%  |
| 32.01-64.0  | 26        | 9%      |
| 1.01-2.0    | 10        | 3.46%   |
| 24.01-32.0  | 7         | 2.42%   |
| 2.01-3.0    | 4         | 1.38%   |
| 64.01-256.0 | 4         | 1.38%   |
| 0.51-1.0    | 2         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 95        | 29.69%  |
| 2.01-3.0   | 78        | 24.38%  |
| 4.01-8.0   | 47        | 14.69%  |
| 3.01-4.0   | 46        | 14.38%  |
| 0.51-1.0   | 25        | 7.81%   |
| 8.01-16.0  | 21        | 6.56%   |
| 16.01-24.0 | 3         | 0.94%   |
| 0.01-0.5   | 3         | 0.94%   |
| 24.01-32.0 | 2         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 231       | 78.84%  |
| 2      | 48        | 16.38%  |
| 3      | 8         | 2.73%   |
| 0      | 5         | 1.71%   |
| 4      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 61.54%  |
| Yes       | 110       | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 241       | 83.68%  |
| No        | 47        | 16.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 97.91%  |
| No        | 6         | 2.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 84.48%  |
| No        | 45        | 15.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 286       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 110       | 34.27%  |
| Kranj                   | 21        | 6.54%   |
| Maribor                 | 11        | 3.43%   |
| Celje                   | 9         | 2.8%    |
| Poljane nad Skofjo Loko | 8         | 2.49%   |
| Trzin                   | 6         | 1.87%   |
| Vrhnika                 | 5         | 1.56%   |
| Žalec                  | 4         | 1.25%   |
| Sempeter pri Gorici     | 4         | 1.25%   |
| Portorož               | 4         | 1.25%   |
| Novo Mesto              | 4         | 1.25%   |
| Medvode                 | 4         | 1.25%   |
| Koper                   | 4         | 1.25%   |
| Velenje                 | 3         | 0.93%   |
| Turnisce                | 3         | 0.93%   |
| Slovenske Konjice       | 3         | 0.93%   |
| Škofja Loka            | 3         | 0.93%   |
| Ptuj                    | 3         | 0.93%   |
| Nova Gorica             | 3         | 0.93%   |
| Murska Sobota           | 3         | 0.93%   |
| Ajdovščina            | 3         | 0.93%   |
| Sostanj                 | 2         | 0.62%   |
| Smarje pri Jelsah       | 2         | 0.62%   |
| Slovenj Gradec          | 2         | 0.62%   |
| Skofljica               | 2         | 0.62%   |
| Sežana                 | 2         | 0.62%   |
| Ruše                   | 2         | 0.62%   |
| Puconci                 | 2         | 0.62%   |
| Petrovce                | 2         | 0.62%   |
| Logatec                 | 2         | 0.62%   |
| Lesce                   | 2         | 0.62%   |
| Kidricevo               | 2         | 0.62%   |
| Kamnik                  | 2         | 0.62%   |
| Izlake                  | 2         | 0.62%   |
| Grosuplje               | 2         | 0.62%   |
| Domžale                | 2         | 0.62%   |
| Blejska Dobrava         | 2         | 0.62%   |
| Žužemberk             | 1         | 0.31%   |
| Zrece                   | 1         | 0.31%   |
| Ziri                    | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 68        | 98     | 20.18%  |
| SanDisk                     | 32        | 37     | 9.5%    |
| Seagate                     | 26        | 31     | 7.72%   |
| Crucial                     | 23        | 34     | 6.82%   |
| Toshiba                     | 22        | 33     | 6.53%   |
| Kingston                    | 22        | 28     | 6.53%   |
| SK hynix                    | 21        | 32     | 6.23%   |
| WDC                         | 20        | 21     | 5.93%   |
| Micron Technology           | 11        | 12     | 3.26%   |
| Unknown                     | 10        | 11     | 2.97%   |
| Hitachi                     | 10        | 13     | 2.97%   |
| HGST                        | 10        | 12     | 2.97%   |
| Intel                       | 8         | 9      | 2.37%   |
| KIOXIA                      | 6         | 7      | 1.78%   |
| Intenso                     | 6         | 7      | 1.78%   |
| JMicron Technology          | 4         | 4      | 1.19%   |
| Fujitsu                     | 4         | 5      | 1.19%   |
| Micron/Crucial Technology   | 3         | 3      | 0.89%   |
| Transcend                   | 2         | 2      | 0.59%   |
| Silicon Motion              | 2         | 3      | 0.59%   |
| PNY                         | 2         | 2      | 0.59%   |
| OCZ                         | 2         | 2      | 0.59%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.59%   |
| LITEON                      | 2         | 2      | 0.59%   |
| Lenovo                      | 2         | 2      | 0.59%   |
| Corsair                     | 2         | 4      | 0.59%   |
| Apple                       | 2         | 2      | 0.59%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.3%    |
| Union Memory                | 1         | 1      | 0.3%    |
| Team                        | 1         | 1      | 0.3%    |
| SABRENT                     | 1         | 1      | 0.3%    |
| Realtek                     | 1         | 1      | 0.3%    |
| Phison                      | 1         | 1      | 0.3%    |
| Patriot                     | 1         | 2      | 0.3%    |
| LITEONIT                    | 1         | 2      | 0.3%    |
| HGST HTS                    | 1         | 1      | 0.3%    |
| Gigabyte Technology         | 1         | 2      | 0.3%    |
| Apacer                      | 1         | 1      | 0.3%    |
| A-DATA Technology           | 1         | 1      | 0.3%    |
| Unknown                     | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 7         | 2.01%   |
| Samsung SSD 850 EVO 250GB                          | 5         | 1.43%   |
| Samsung NVMe SSD Drive 512GB                       | 5         | 1.43%   |
| HGST HTS721010A9E630 1TB                           | 5         | 1.43%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 1.15%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.86%   |
| Seagate ST2000LM015-2E8174 2TB                     | 3         | 0.86%   |
| SanDisk NVMe SSD Drive 512GB                       | 3         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.86%   |
| Hitachi HTS547575A9E384 752GB                      | 3         | 0.86%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 0.86%   |
| Unknown MMC Card  32GB                             | 2         | 0.57%   |
| Unknown MMC Card  128GB                            | 2         | 0.57%   |
| Toshiba THNSN5256GPUK 256GB                        | 2         | 0.57%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 0.57%   |
| Toshiba BG3 NVMe SSD Controller 256GB              | 2         | 0.57%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB            | 2         | 0.57%   |
| SK hynix SC311 SATA 256GB                          | 2         | 0.57%   |
| SK hynix HFM512GD3JX013N 512GB                     | 2         | 0.57%   |
| Seagate ST9750420AS 752GB                          | 2         | 0.57%   |
| Seagate ST9500325AS 500GB                          | 2         | 0.57%   |
| Seagate ST9320423AS 320GB                          | 2         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.57%   |
| SanDisk SSD PLUS 240GB                             | 2         | 0.57%   |
| SanDisk SD9SB8W256G1002 256GB SSD                  | 2         | 0.57%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 0.57%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.57%   |
| Samsung SSD 860 EVO 250GB                          | 2         | 0.57%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.57%   |
| Samsung NVMe SSD Drive 256GB                       | 2         | 0.57%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.57%   |
| Samsung MZVL21T0HCLR-00BL2 1TB                     | 2         | 0.57%   |
| PNY CS900 120GB SSD                                | 2         | 0.57%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 2         | 0.57%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 2         | 0.57%   |
| Lenovo NVMe SSD Drive 256GB                        | 2         | 0.57%   |
| Kingston SV300S37A60G 64GB SSD                     | 2         | 0.57%   |
| Kingston SA400S37480G 480GB SSD                    | 2         | 0.57%   |
| Kingston SA400S37120G 120GB SSD                    | 2         | 0.57%   |
| JMicron Tech 250GB                                 | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 26        | 31     | 34.67%  |
| Toshiba            | 12        | 20     | 16%     |
| Hitachi            | 10        | 13     | 13.33%  |
| HGST               | 10        | 12     | 13.33%  |
| WDC                | 8         | 8      | 10.67%  |
| Fujitsu            | 4         | 5      | 5.33%   |
| Unknown            | 1         | 1      | 1.33%   |
| SABRENT            | 1         | 1      | 1.33%   |
| JMicron Technology | 1         | 1      | 1.33%   |
| Intenso            | 1         | 1      | 1.33%   |
| HGST HTS           | 1         | 1      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 39     | 22.76%  |
| Crucial             | 21        | 32     | 17.07%  |
| SanDisk             | 18        | 21     | 14.63%  |
| Kingston            | 18        | 23     | 14.63%  |
| WDC                 | 5         | 5      | 4.07%   |
| SK hynix            | 4         | 4      | 3.25%   |
| Intenso             | 4         | 5      | 3.25%   |
| Micron Technology   | 3         | 3      | 2.44%   |
| Transcend           | 2         | 2      | 1.63%   |
| PNY                 | 2         | 2      | 1.63%   |
| OCZ                 | 2         | 2      | 1.63%   |
| LITEON              | 2         | 2      | 1.63%   |
| Corsair             | 2         | 4      | 1.63%   |
| Apple               | 2         | 2      | 1.63%   |
| Toshiba             | 1         | 1      | 0.81%   |
| Team                | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Patriot             | 1         | 2      | 0.81%   |
| LITEONIT            | 1         | 2      | 0.81%   |
| JMicron Technology  | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 2      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |
| A-DATA Technology   | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 120       | 167    | 37.74%  |
| SSD     | 112       | 159    | 35.22%  |
| HDD     | 73        | 94     | 22.96%  |
| MMC     | 9         | 10     | 2.83%   |
| Unknown | 4         | 4      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 167       | 244    | 54.22%  |
| NVMe | 120       | 166    | 38.96%  |
| SAS  | 12        | 14     | 3.9%    |
| MMC  | 9         | 10     | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 136       | 183    | 73.12%  |
| 0.51-1.0   | 38        | 50     | 20.43%  |
| 1.01-2.0   | 12        | 20     | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 27.21%  |
| 251-500        | 78        | 25.57%  |
| 501-1000       | 45        | 14.75%  |
| 1-20           | 21        | 6.89%   |
| 51-100         | 20        | 6.56%   |
| 1001-2000      | 19        | 6.23%   |
| 21-50          | 14        | 4.59%   |
| More than 3000 | 10        | 3.28%   |
| 2001-3000      | 9         | 2.95%   |
| Unknown        | 6         | 1.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 119       | 37.42%  |
| 21-50          | 54        | 16.98%  |
| 51-100         | 47        | 14.78%  |
| 101-250        | 41        | 12.89%  |
| 251-500        | 31        | 9.75%   |
| 501-1000       | 13        | 4.09%   |
| Unknown        | 6         | 1.89%   |
| 1001-2000      | 5         | 1.57%   |
| More than 3000 | 1         | 0.31%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                    | 2         | 2      | 9.09%   |
| Crucial CT128MX100SSD1 128GB                                  | 2         | 2      | 9.09%   |
| Toshiba MQ01ABF050 500GB                                      | 1         | 5      | 4.55%   |
| SK hynix HFS256G32MND-2200A 256GB SSD                         | 1         | 1      | 4.55%   |
| Seagate ST98823AS 80GB                                        | 1         | 3      | 4.55%   |
| Seagate ST9750420AS 752GB                                     | 1         | 1      | 4.55%   |
| Seagate ST9500423AS 500GB                                     | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB                                     | 1         | 2      | 4.55%   |
| Seagate ST9160314AS 160GB                                     | 1         | 1      | 4.55%   |
| Seagate ST2000LM015-2E8174 2TB                                | 1         | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 1         | 1      | 4.55%   |
| SanDisk SD7SB2Q512G1001 512GB SSD                             | 1         | 1      | 4.55%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1      | 4.55%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD                | 1         | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB SSD                              | 1         | 1      | 4.55%   |
| Hitachi HTS727550A9E364 500GB                                 | 1         | 1      | 4.55%   |
| Hitachi HTS543280L9SA00 80GB                                  | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                                      | 1         | 1      | 4.55%   |
| Crucial CT250BX100SSD1 250GB                                  | 1         | 1      | 4.55%   |
| Crucial CT120M500SSD1 120GB                                   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 31.82%  |
| Crucial             | 4         | 4      | 18.18%  |
| HGST                | 3         | 3      | 13.64%  |
| Hitachi             | 2         | 2      | 9.09%   |
| Toshiba             | 1         | 5      | 4.55%   |
| SK hynix            | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Kingston            | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 10     | 53.85%  |
| HGST    | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| Toshiba | 1         | 5      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 20     | 59.09%  |
| SSD  | 8         | 8      | 36.36%  |
| NVMe | 1         | 1      | 4.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB                          | 1         | 2      | 50%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 150       | 235    | 50.17%  |
| Works    | 125       | 167    | 41.81%  |
| Malfunc  | 22        | 29     | 7.36%   |
| Failed   | 2         | 3      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 185       | 54.41%  |
| Samsung Electronics              | 46        | 13.53%  |
| AMD                              | 29        | 8.53%   |
| SanDisk                          | 20        | 5.88%   |
| SK hynix                         | 17        | 5%      |
| Toshiba America Info Systems     | 12        | 3.53%   |
| Micron Technology                | 8         | 2.35%   |
| Micron/Crucial Technology        | 4         | 1.18%   |
| KIOXIA                           | 4         | 1.18%   |
| Kingston Technology Company      | 4         | 1.18%   |
| Union Memory (Shenzhen)          | 2         | 0.59%   |
| Silicon Motion                   | 2         | 0.59%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.59%   |
| Lenovo                           | 2         | 0.59%   |
| VIA Technologies                 | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Marvell Technology Group         | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23        | 6.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 6.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 16        | 4.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 4.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 3.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 2.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 2.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 1.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.1%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 3         | 0.83%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.83%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.83%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.83%   |
| Intel SSD 660P Series                                                          | 3         | 0.83%   |
| Intel RST Volume Management Device Controller                                  | 3         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 3         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.83%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 0.83%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.55%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 181       | 51.71%  |
| NVMe | 123       | 35.14%  |
| IDE  | 25        | 7.14%   |
| RAID | 21        | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 228       | 79.72%  |
| AMD    | 58        | 20.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.75%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.75%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 5         | 1.75%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 4         | 1.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.4%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.4%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.05%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 1.05%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.05%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.05%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.05%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.05%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.05%   |
| AMD Ryzen 3 7320U with Radeon Graphics        | 3         | 1.05%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.7%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.7%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 69        | 24.13%  |
| Intel Core i5           | 60        | 20.98%  |
| Other                   | 25        | 8.74%   |
| Intel Core i3           | 21        | 7.34%   |
| Intel Core 2 Duo        | 18        | 6.29%   |
| AMD Ryzen 7             | 18        | 6.29%   |
| Intel Celeron           | 15        | 5.24%   |
| AMD Ryzen 3             | 11        | 3.85%   |
| AMD Ryzen 5             | 10        | 3.5%    |
| Intel Pentium           | 7         | 2.45%   |
| AMD Ryzen 9             | 5         | 1.75%   |
| Intel Genuine           | 4         | 1.4%    |
| Intel Core 2            | 3         | 1.05%   |
| Intel Core              | 3         | 1.05%   |
| AMD Ryzen 7 PRO         | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Core M            | 1         | 0.35%   |
| Intel Celeron Dual-Core | 1         | 0.35%   |
| AMD Turion II Dual-Core | 1         | 0.35%   |
| AMD Turion II           | 1         | 0.35%   |
| AMD Mobile Sempron      | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-60                | 1         | 0.35%   |
| AMD Athlon Neo          | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 131       | 45.8%   |
| 4      | 96        | 33.57%  |
| 8      | 25        | 8.74%   |
| 6      | 17        | 5.94%   |
| 10     | 5         | 1.75%   |
| 16     | 4         | 1.4%    |
| 12     | 3         | 1.05%   |
| 1      | 3         | 1.05%   |
| 20     | 1         | 0.35%   |
| 14     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 286       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 222       | 77.62%  |
| 1      | 64        | 22.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 277       | 96.52%  |
| Unknown        | 6         | 2.09%   |
| 32-bit         | 4         | 1.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 41.14%  |
| 0x206a7    | 13        | 4.35%   |
| 0x306a9    | 12        | 4.01%   |
| 0x806ec    | 11        | 3.68%   |
| 0x40651    | 9         | 3.01%   |
| 0x20655    | 9         | 3.01%   |
| 0x806ea    | 8         | 2.68%   |
| 0x306c3    | 8         | 2.68%   |
| 0x6fd      | 7         | 2.34%   |
| 0x806c1    | 6         | 2.01%   |
| 0x406e3    | 5         | 1.67%   |
| 0x30678    | 5         | 1.67%   |
| 0x10676    | 5         | 1.67%   |
| 0x08108102 | 5         | 1.67%   |
| 0x906ea    | 4         | 1.34%   |
| 0x906e9    | 4         | 1.34%   |
| 0x20652    | 4         | 1.34%   |
| 0x1067a    | 4         | 1.34%   |
| 0x08608103 | 4         | 1.34%   |
| 0xa0652    | 3         | 1%      |
| 0x706e5    | 3         | 1%      |
| 0x6e8      | 3         | 1%      |
| 0x306d4    | 3         | 1%      |
| 0x106e5    | 3         | 1%      |
| 0x0a50000c | 3         | 1%      |
| 0x08608102 | 3         | 1%      |
| 0x08600106 | 3         | 1%      |
| 0x906ed    | 2         | 0.67%   |
| 0x806eb    | 2         | 0.67%   |
| 0x706a1    | 2         | 0.67%   |
| 0x506c9    | 2         | 0.67%   |
| 0x0a404102 | 2         | 0.67%   |
| 0x0810100b | 2         | 0.67%   |
| 0x06001119 | 2         | 0.67%   |
| 0x05000119 | 2         | 0.67%   |
| 0xa0660    | 1         | 0.33%   |
| 0x906a4    | 1         | 0.33%   |
| 0x806e9    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6f6      | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 52        | 18.18%  |
| Unknown           | 27        | 9.44%   |
| IvyBridge         | 21        | 7.34%   |
| Haswell           | 19        | 6.64%   |
| SandyBridge       | 18        | 6.29%   |
| Westmere          | 16        | 5.59%   |
| Skylake           | 12        | 4.2%    |
| Core              | 12        | 4.2%    |
| Penryn            | 11        | 3.85%   |
| TigerLake         | 10        | 3.5%    |
| Silvermont        | 10        | 3.5%    |
| Zen+              | 9         | 3.15%   |
| Zen 3             | 8         | 2.8%    |
| Broadwell         | 8         | 2.8%    |
| Zen 2             | 7         | 2.45%   |
| IceLake           | 7         | 2.45%   |
| Alderlake Hybrid  | 7         | 2.45%   |
| CometLake         | 5         | 1.75%   |
| P6                | 4         | 1.4%    |
| Goldmont plus     | 4         | 1.4%    |
| Piledriver        | 3         | 1.05%   |
| Nehalem           | 3         | 1.05%   |
| K8 Hammer         | 3         | 1.05%   |
| Zen               | 2         | 0.7%    |
| K10               | 2         | 0.7%    |
| Goldmont          | 2         | 0.7%    |
| Bobcat            | 2         | 0.7%    |
| Meteorlake Hybrid | 1         | 0.35%   |
| Jaguar            | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 197       | 53.39%  |
| AMD                              | 95        | 25.75%  |
| Nvidia                           | 75        | 20.33%  |
| VIA Technologies                 | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 3.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 3.69%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 3.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.37%   |
| AMD Lucienne                                                                             | 9         | 2.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.85%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 1.58%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 6         | 1.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.58%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 6         | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.58%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.58%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 5         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.32%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 5         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 1.32%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.06%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.79%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 0.79%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.79%   |
| AMD Mendocino [Radeon 610M]                                                              | 3         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 42.71%  |
| 1 x AMD        | 63        | 21.88%  |
| Intel + Nvidia | 52        | 18.06%  |
| Intel + AMD    | 21        | 7.29%   |
| 1 x Nvidia     | 14        | 4.86%   |
| AMD + Nvidia   | 9         | 3.13%   |
| 2 x Intel      | 2         | 0.69%   |
| 2 x AMD        | 2         | 0.69%   |
| 1 x VIA        | 1         | 0.35%   |
| 1 x SiS        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 242       | 83.45%  |
| Proprietary | 35        | 12.07%  |
| Unknown     | 13        | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 65.54%  |
| 1.01-2.0   | 32        | 10.81%  |
| 0.01-0.5   | 31        | 10.47%  |
| 0.51-1.0   | 19        | 6.42%   |
| 3.01-4.0   | 13        | 4.39%   |
| 5.01-6.0   | 4         | 1.35%   |
| 7.01-8.0   | 2         | 0.68%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 64        | 18.93%  |
| LG Display              | 41        | 12.13%  |
| BOE                     | 39        | 11.54%  |
| Samsung Electronics     | 38        | 11.24%  |
| Chimei Innolux          | 38        | 11.24%  |
| Lenovo                  | 19        | 5.62%   |
| Dell                    | 16        | 4.73%   |
| Chi Mei Optoelectronics | 12        | 3.55%   |
| Sharp                   | 8         | 2.37%   |
| AOC                     | 7         | 2.07%   |
| Goldstar                | 6         | 1.78%   |
| CSO                     | 6         | 1.78%   |
| LG Philips              | 5         | 1.48%   |
| PANDA                   | 4         | 1.18%   |
| TMX                     | 2         | 0.59%   |
| InfoVision              | 2         | 0.59%   |
| Hewlett-Packard         | 2         | 0.59%   |
| HannStar                | 2         | 0.59%   |
| CPT                     | 2         | 0.59%   |
| ASUSTek Computer        | 2         | 0.59%   |
| Apple                   | 2         | 0.59%   |
| Acer                    | 2         | 0.59%   |
| ViewSonic               | 1         | 0.3%    |
| Valve                   | 1         | 0.3%    |
| Unknown (XXX)           | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| Tianma XM               | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| Philips                 | 1         | 0.3%    |
| NEC Computers           | 1         | 0.3%    |
| Medion                  | 1         | 0.3%    |
| LGD                     | 1         | 0.3%    |
| Japannext               | 1         | 0.3%    |
| Iiyama                  | 1         | 0.3%    |
| IBM                     | 1         | 0.3%    |
| HUAWEI                  | 1         | 0.3%    |
| Hitachi                 | 1         | 0.3%    |
| HCG                     | 1         | 0.3%    |
| Gericom                 | 1         | 0.3%    |
| CSOT                    | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 2.03%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 4         | 1.16%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.16%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 3         | 0.87%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 3         | 0.87%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 3         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 3         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 3         | 0.87%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 0.87%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 2         | 0.58%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 2         | 0.58%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch              | 2         | 0.58%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.58%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 2         | 0.58%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch                  | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch           | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1550 1920x1080 344x193mm 15.5-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.58%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.58%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.58%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 2         | 0.58%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch             | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 2         | 0.58%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.58%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.29%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 138       | 43.53%  |
| 1366x768 (WXGA)    | 55        | 17.35%  |
| 1600x900 (HD+)     | 23        | 7.26%   |
| 1920x1200 (WUXGA)  | 17        | 5.36%   |
| 3840x2160 (4K)     | 16        | 5.05%   |
| 2560x1440 (QHD)    | 11        | 3.47%   |
| 1440x900 (WXGA+)   | 11        | 3.47%   |
| 1280x800 (WXGA)    | 9         | 2.84%   |
| 3440x1440          | 7         | 2.21%   |
| 1680x1050 (WSXGA+) | 7         | 2.21%   |
| 2560x1600          | 5         | 1.58%   |
| 2880x1800          | 2         | 0.63%   |
| 2048x1152          | 2         | 0.63%   |
| 1280x1024 (SXGA)   | 2         | 0.63%   |
| 800x1280           | 1         | 0.32%   |
| 3456x2160          | 1         | 0.32%   |
| 3200x1800 (QHD+)   | 1         | 0.32%   |
| 3072x1920          | 1         | 0.32%   |
| 3000x2000          | 1         | 0.32%   |
| 2880x1920          | 1         | 0.32%   |
| 2520x1680          | 1         | 0.32%   |
| 2288x1287          | 1         | 0.32%   |
| 2256x1504          | 1         | 0.32%   |
| 2240x1400          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 1400x1050          | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 141       | 41.59%  |
| 14      | 35        | 10.32%  |
| 17      | 34        | 10.03%  |
| 13      | 34        | 10.03%  |
| 24      | 15        | 4.42%   |
| 27      | 13        | 3.83%   |
| 23      | 11        | 3.24%   |
| 16      | 9         | 2.65%   |
| 34      | 8         | 2.36%   |
| 21      | 6         | 1.77%   |
| 22      | 4         | 1.18%   |
| 12      | 4         | 1.18%   |
| 19      | 3         | 0.88%   |
| 18      | 3         | 0.88%   |
| 54      | 2         | 0.59%   |
| 40      | 2         | 0.59%   |
| 33      | 2         | 0.59%   |
| 11      | 2         | 0.59%   |
| Unknown | 2         | 0.59%   |
| 142     | 1         | 0.29%   |
| 84      | 1         | 0.29%   |
| 65      | 1         | 0.29%   |
| 64      | 1         | 0.29%   |
| 39      | 1         | 0.29%   |
| 38      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 25      | 1         | 0.29%   |
| 7       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 197       | 58.98%  |
| 351-400        | 37        | 11.08%  |
| 501-600        | 34        | 10.18%  |
| 201-300        | 27        | 8.08%   |
| 401-500        | 13        | 3.89%   |
| 701-800        | 11        | 3.29%   |
| 801-900        | 4         | 1.2%    |
| 1001-1500      | 4         | 1.2%    |
| 601-700        | 2         | 0.6%    |
| Unknown        | 2         | 0.6%    |
| More than 2000 | 1         | 0.3%    |
| 1501-2000      | 1         | 0.3%    |
| 1-100          | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 229       | 75.58%  |
| 16/10   | 54        | 17.82%  |
| 21/9    | 8         | 2.64%   |
| 3/2     | 5         | 1.65%   |
| 5/4     | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |
| 4/3     | 1         | 0.33%   |
| 1.00    | 1         | 0.33%   |
| 0.67    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 137       | 40.53%  |
| 81-90          | 53        | 15.68%  |
| 121-130        | 30        | 8.88%   |
| 201-250        | 26        | 7.69%   |
| 71-80          | 14        | 4.14%   |
| 301-350        | 13        | 3.85%   |
| 111-120        | 12        | 3.55%   |
| 351-500        | 11        | 3.25%   |
| 251-300        | 8         | 2.37%   |
| More than 1000 | 6         | 1.78%   |
| 151-200        | 6         | 1.78%   |
| 61-70          | 4         | 1.18%   |
| 131-140        | 4         | 1.18%   |
| 501-1000       | 4         | 1.18%   |
| 91-100         | 3         | 0.89%   |
| 51-60          | 2         | 0.59%   |
| 141-150        | 2         | 0.59%   |
| Unknown        | 2         | 0.59%   |
| 1-40           | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 138       | 42.07%  |
| 101-120       | 89        | 27.13%  |
| 51-100        | 59        | 17.99%  |
| 161-240       | 25        | 7.62%   |
| More than 240 | 11        | 3.35%   |
| 1-50          | 4         | 1.22%   |
| Unknown       | 2         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 232       | 77.85%  |
| 2     | 51        | 17.11%  |
| 3     | 9         | 3.02%   |
| 0     | 6         | 2.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 167       | 36.23%  |
| Realtek Semiconductor             | 140       | 30.37%  |
| Qualcomm Atheros                  | 49        | 10.63%  |
| Broadcom                          | 31        | 6.72%   |
| MediaTek                          | 12        | 2.6%    |
| ASIX Electronics                  | 6         | 1.3%    |
| Samsung Electronics               | 5         | 1.08%   |
| Ralink                            | 5         | 1.08%   |
| Hewlett-Packard                   | 5         | 1.08%   |
| Marvell Technology Group          | 4         | 0.87%   |
| Huawei Technologies               | 4         | 0.87%   |
| Broadcom Limited                  | 4         | 0.87%   |
| Shenzhen Goodix Technology        | 3         | 0.65%   |
| Qualcomm                          | 3         | 0.65%   |
| ASUSTek Computer                  | 3         | 0.65%   |
| Sierra Wireless                   | 2         | 0.43%   |
| Ralink Technology                 | 2         | 0.43%   |
| Lenovo                            | 2         | 0.43%   |
| JMicron Technology                | 2         | 0.43%   |
| Ericsson Business Mobile Networks | 2         | 0.43%   |
| Dell                              | 2         | 0.43%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.22%   |
| Xiaomi                            | 1         | 0.22%   |
| VIA Technologies                  | 1         | 0.22%   |
| TP-Link                           | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| SEGGER                            | 1         | 0.22%   |
| ICS Advent                        | 1         | 0.22%   |
| Google                            | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 93        | 16.29%  |
| Intel Wireless 8265 / 8275                                             | 18        | 3.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 2.98%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.58%   |
| Intel Wireless 7265                                                    | 9         | 1.58%   |
| Intel Wireless 7260                                                    | 9         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 8         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.23%   |
| Intel Wireless 8260                                                    | 7         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 6         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 6         | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 5         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.88%   |
| Intel Centrino Advanced-N 6200                                         | 5         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.7%    |
| Intel Wireless 3165                                                    | 4         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.7%    |
| Intel 82562GT 10/100 Network Connection                                | 4         | 0.7%    |
| Shenzhen Goodix Fingerprint Reader                                     | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 160       | 54.05%  |
| Qualcomm Atheros      | 43        | 14.53%  |
| Realtek Semiconductor | 38        | 12.84%  |
| Broadcom              | 24        | 8.11%   |
| MediaTek              | 10        | 3.38%   |
| Ralink                | 5         | 1.69%   |
| Broadcom Limited      | 3         | 1.01%   |
| ASUSTek Computer      | 3         | 1.01%   |
| Sierra Wireless       | 2         | 0.68%   |
| Ralink Technology     | 2         | 0.68%   |
| Qualcomm              | 2         | 0.68%   |
| Hewlett-Packard       | 2         | 0.68%   |
| Dell                  | 2         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 18        | 6.08%   |
| Intel Wi-Fi 6 AX200                                                  | 15        | 5.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 10        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 3.04%   |
| Intel Wireless 7265                                                  | 9         | 3.04%   |
| Intel Wireless 7260                                                  | 9         | 3.04%   |
| Intel Wi-Fi 6 AX201                                                  | 9         | 3.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 8         | 2.7%    |
| Broadcom BCM43142 802.11b/g/n                                        | 8         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 2.36%   |
| Intel Wireless 8260                                                  | 7         | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 7         | 2.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 6         | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 6         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 6         | 2.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 5         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 5         | 1.69%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 1.35%   |
| Intel Wireless 3165                                                  | 4         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 4         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 4         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 1.01%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 3         | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 3         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.01%   |
| Intel Centrino Advanced-N 6235                                       | 3         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 2         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 126       | 48.28%  |
| Intel                            | 80        | 30.65%  |
| Qualcomm Atheros                 | 11        | 4.21%   |
| Broadcom                         | 11        | 4.21%   |
| ASIX Electronics                 | 6         | 2.3%    |
| Samsung Electronics              | 5         | 1.92%   |
| Marvell Technology Group         | 4         | 1.53%   |
| Huawei Technologies              | 3         | 1.15%   |
| MediaTek                         | 2         | 0.77%   |
| Lenovo                           | 2         | 0.77%   |
| JMicron Technology               | 2         | 0.77%   |
| Xiaomi                           | 1         | 0.38%   |
| VIA Technologies                 | 1         | 0.38%   |
| TP-Link                          | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Qualcomm                         | 1         | 0.38%   |
| ICS Advent                       | 1         | 0.38%   |
| Hewlett-Packard                  | 1         | 0.38%   |
| Google                           | 1         | 0.38%   |
| Broadcom Limited                 | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 93        | 35.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 6.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 5.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 3.77%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 2.26%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 2.26%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.89%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.51%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.51%   |
| Intel 82562GT 10/100 Network Connection                                | 4         | 1.51%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 1.13%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 1.13%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.13%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.13%   |
| Huawei FOA-LX9                                                         | 3         | 1.13%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 1.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.75%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.75%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.75%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.75%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 0.75%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 2         | 0.75%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express               | 2         | 0.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 52.82%  |
| Ethernet | 241       | 45.3%   |
| Modem    | 10        | 1.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 221       | 72.46%  |
| Ethernet | 83        | 27.21%  |
| Modem    | 1         | 0.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 222       | 77.35%  |
| 1     | 64        | 22.3%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 266       | 92.36%  |
| Yes  | 22        | 7.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 116       | 46.96%  |
| IMC Networks                    | 23        | 9.31%   |
| Realtek Semiconductor           | 21        | 8.5%    |
| Broadcom                        | 21        | 8.5%    |
| Qualcomm Atheros Communications | 18        | 7.29%   |
| Hewlett-Packard                 | 9         | 3.64%   |
| Foxconn / Hon Hai               | 9         | 3.64%   |
| Lite-On Technology              | 5         | 2.02%   |
| Ralink                          | 4         | 1.62%   |
| Cambridge Silicon Radio         | 4         | 1.62%   |
| Toshiba                         | 3         | 1.21%   |
| Foxconn International           | 2         | 0.81%   |
| Dell                            | 2         | 0.81%   |
| ASUSTek Computer                | 2         | 0.81%   |
| Askey Computer                  | 2         | 0.81%   |
| Apple                           | 2         | 0.81%   |
| USI                             | 1         | 0.4%    |
| Realtek                         | 1         | 0.4%    |
| Ralink Technology               | 1         | 0.4%    |
| Chicony Electronics             | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 18.22%  |
| Intel AX201 Bluetooth                               | 24        | 9.72%   |
| Intel AX200 Bluetooth                               | 15        | 6.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 5.67%   |
| Realtek Bluetooth Radio                             | 10        | 4.05%   |
| Intel Bluetooth Device                              | 10        | 4.05%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 2.43%   |
| IMC Networks Wireless_Device                        | 6         | 2.43%   |
| IMC Networks Bluetooth Device                       | 6         | 2.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 2.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 2.02%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.21%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.21%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.21%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 1.21%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.81%   |
| Intel AX210 Bluetooth                               | 2         | 0.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.81%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.81%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.81%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.81%   |
| Askey Bluetooth Device                              | 2         | 0.81%   |
| USI Bluetooth Device                                | 1         | 0.4%    |
| Toshiba Askey Bluetooth Module                      | 1         | 0.4%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.4%    |
| Realtek CSR BS8510                                  | 1         | 0.4%    |
| Realtek Bluetooth Radio                             | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 226       | 64.94%  |
| AMD                              | 70        | 20.11%  |
| Nvidia                           | 38        | 10.92%  |
| Lenovo                           | 2         | 0.57%   |
| Hewlett-Packard                  | 2         | 0.57%   |
| VIA Technologies                 | 1         | 0.29%   |
| Texas Instruments                | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samsung Electronics              | 1         | 0.29%   |
| Logitech                         | 1         | 0.29%   |
| KTMicro                          | 1         | 0.29%   |
| JMTek                            | 1         | 0.29%   |
| GN Netcom                        | 1         | 0.29%   |
| Generalplus Technology           | 1         | 0.29%   |
| C-Media Electronics              | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 46        | 10.93%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 5.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 5.23%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 20        | 4.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 4.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 3.33%   |
| AMD Radeon High Definition Audio Controller                                                       | 11        | 2.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.9%    |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.95%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.71%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.71%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 57        | 26.89%  |
| Samsung Electronics | 55        | 25.94%  |
| Micron Technology   | 30        | 14.15%  |
| Kingston            | 14        | 6.6%    |
| Crucial             | 14        | 6.6%    |
| Unknown             | 13        | 6.13%   |
| Ramaxel Technology  | 6         | 2.83%   |
| Nanya Technology    | 6         | 2.83%   |
| Elpida              | 4         | 1.89%   |
| Qimonda             | 3         | 1.42%   |
| A-DATA Technology   | 3         | 1.42%   |
| Wilk                | 1         | 0.47%   |
| Team                | 1         | 0.47%   |
| Shenzhen Longsys    | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| ChangXin Memory     | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 1.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.75%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 3         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.31%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 3         | 1.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.31%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 3         | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 2         | 0.87%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.87%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s              | 2         | 0.87%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.87%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 0.87%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.87%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 2         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.87%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 0.87%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s               | 2         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s     | 2         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s    | 2         | 0.87%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.87%   |
| Micron RAM 16HTF25664HY-667E1 2GB SODIMM DDR2 667MT/s     | 2         | 0.87%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 0.87%   |
| Kingston RAM KHX1600C9S3/8G 8GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| Kingston RAM HP16D3LS1KBGH/4G 4GB SODIMM DDR3 1600MT/s    | 2         | 0.87%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s   | 2         | 0.87%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 0.87%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.44%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.44%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 78        | 44.07%  |
| DDR3   | 51        | 28.81%  |
| DDR2   | 13        | 7.34%   |
| LPDDR4 | 9         | 5.08%   |
| LPDDR5 | 8         | 4.52%   |
| DDR5   | 8         | 4.52%   |
| SDRAM  | 4         | 2.26%   |
| LPDDR3 | 4         | 2.26%   |
| DRAM   | 2         | 1.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 89.33%  |
| Row Of Chips | 18        | 10.11%  |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 70        | 35.9%   |
| 4096  | 45        | 23.08%  |
| 16384 | 38        | 19.49%  |
| 2048  | 22        | 11.28%  |
| 32768 | 10        | 5.13%   |
| 1024  | 8         | 4.1%    |
| 512   | 2         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 38        | 19.49%  |
| 1600    | 38        | 19.49%  |
| 3200    | 31        | 15.9%   |
| 2400    | 12        | 6.15%   |
| 1334    | 12        | 6.15%   |
| 2133    | 8         | 4.1%    |
| 667     | 8         | 4.1%    |
| 6400    | 5         | 2.56%   |
| 1333    | 5         | 2.56%   |
| 5600    | 4         | 2.05%   |
| 4800    | 4         | 2.05%   |
| 4266    | 4         | 2.05%   |
| Unknown | 4         | 2.05%   |
| 4267    | 3         | 1.54%   |
| 1067    | 3         | 1.54%   |
| 533     | 3         | 1.54%   |
| 8400    | 2         | 1.03%   |
| 4199    | 2         | 1.03%   |
| 2048    | 2         | 1.03%   |
| 975     | 2         | 1.03%   |
| 8533    | 1         | 0.51%   |
| 7500    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 1867    | 1         | 0.51%   |
| 800     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 50%     |
| Xerox           | 1         | 25%     |
| Canon           | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Xerox Phaser 3010       | 1         | 25%     |
| HP DeskJet F4200 series | 1         | 25%     |
| HP DeskJet F300 series  | 1         | 25%     |
| Canon PIXMA MP250       | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan 4200F               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 79        | 32.24%  |
| IMC Networks                           | 31        | 12.65%  |
| Quanta                                 | 18        | 7.35%   |
| Microdia                               | 17        | 6.94%   |
| Bison Electronics                      | 17        | 6.94%   |
| Realtek Semiconductor                  | 16        | 6.53%   |
| Sunplus Innovation Technology          | 11        | 4.49%   |
| Lite-On Technology                     | 10        | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.67%   |
| Suyin                                  | 5         | 2.04%   |
| Syntek                                 | 4         | 1.63%   |
| Primax Electronics                     | 4         | 1.63%   |
| Lenovo                                 | 4         | 1.63%   |
| Samsung Electronics                    | 3         | 1.22%   |
| Sonix Technology                       | 2         | 0.82%   |
| Ricoh                                  | 2         | 0.82%   |
| Generalplus Technology                 | 2         | 0.82%   |
| Xiaomi                                 | 1         | 0.41%   |
| Unknown (3730304231393831325530)       | 1         | 0.41%   |
| Silicon Motion                         | 1         | 0.41%   |
| ShineTech                              | 1         | 0.41%   |
| Microsoft                              | 1         | 0.41%   |
| Luxvisions Innotech Limited            | 1         | 0.41%   |
| Logitech                               | 1         | 0.41%   |
| DX-231115-J                            | 1         | 0.41%   |
| BillionPixels                          | 1         | 0.41%   |
| Apple                                  | 1         | 0.41%   |
| Acer                                   | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 19        | 7.69%   |
| Microdia Integrated_Webcam_HD                    | 11        | 4.45%   |
| IMC Networks Integrated Camera                   | 10        | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam                | 8         | 3.24%   |
| Chicony HP HD Camera                             | 7         | 2.83%   |
| Sunplus HP HD Webcam [Fixed]                     | 4         | 1.62%   |
| Quanta HP TrueVision HD Camera                   | 4         | 1.62%   |
| Quanta HP HD Camera                              | 4         | 1.62%   |
| Primax HP HD Webcam [Fixed]                      | 4         | 1.62%   |
| Lite-On HP HD Webcam                             | 4         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 4         | 1.62%   |
| Bison Integrated Camera                          | 4         | 1.62%   |
| Syntek Lenovo EasyCamera                         | 3         | 1.21%   |
| Samsung Galaxy series, misc. (MTP mode)          | 3         | 1.21%   |
| Lite-On Integrated Camera                        | 3         | 1.21%   |
| Lite-On HP HD Camera                             | 3         | 1.21%   |
| Lenovo Integrated Webcam [R5U877]                | 3         | 1.21%   |
| IMC Networks VGA UVC WebCam                      | 3         | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam                    | 3         | 1.21%   |
| Chicony HP Webcam                                | 3         | 1.21%   |
| Chicony HP HD Webcam                             | 3         | 1.21%   |
| Bison SunplusIT Integrated Camera                | 3         | 1.21%   |
| Sunplus HD WebCam                                | 2         | 0.81%   |
| Sonix USB2.0 FHD UVC WebCam                      | 2         | 0.81%   |
| Realtek USB Camera                               | 2         | 0.81%   |
| Realtek Integrated_Webcam_HD                     | 2         | 0.81%   |
| Realtek HP Webcam-101                            | 2         | 0.81%   |
| Realtek Asus laptop camera                       | 2         | 0.81%   |
| Quanta VGA WebCam                                | 2         | 0.81%   |
| Quanta HP Webcam                                 | 2         | 0.81%   |
| Quanta HD Webcam                                 | 2         | 0.81%   |
| Microdia Integrated_Webcam_FHD                   | 2         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.81%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 2         | 0.81%   |
| IMC Networks Integrated Webcam                   | 2         | 0.81%   |
| Generalplus GENERAL WEBCAM                       | 2         | 0.81%   |
| Chicony USB2.0 UVC WebCam                        | 2         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.81%   |
| Chicony USB 2.0 Camera                           | 2         | 0.81%   |
| Chicony Lenovo EasyCamera                        | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 34.29%  |
| Synaptics                  | 21        | 30%     |
| Shenzhen Goodix Technology | 8         | 11.43%  |
| AuthenTec                  | 7         | 10%     |
| Upek                       | 5         | 7.14%   |
| Elan Microelectronics      | 3         | 4.29%   |
| STMicroelectronics         | 2         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 12.86%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 8.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 8.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 5.71%   |
| Validity Sensors VFS491                                                    | 3         | 4.29%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.86%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.86%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.86%   |
| AuthenTec AES2810                                                          | 2         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.43%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.43%   |
| Synaptics UWP WBDI                                                         | 1         | 1.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.43%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.43%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 12        | 48%     |
| Broadcom    | 8         | 32%     |
| O2 Micro    | 3         | 12%     |
| Upek        | 2         | 8%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 48%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 4         | 16%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4%      |
| Broadcom 5880                                                                | 1         | 4%      |
| Broadcom 58200                                                               | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 153       | 51.86%  |
| 1     | 100       | 33.9%   |
| 2     | 38        | 12.88%  |
| 3     | 3         | 1.02%   |
| 10    | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 37.04%  |
| Graphics card            | 33        | 17.46%  |
| Chipcard                 | 21        | 11.11%  |
| Net/wireless             | 19        | 10.05%  |
| Multimedia controller    | 11        | 5.82%   |
| Camera                   | 10        | 5.29%   |
| Bluetooth                | 8         | 4.23%   |
| Communication controller | 6         | 3.17%   |
| Card reader              | 4         | 2.12%   |
| Storage                  | 2         | 1.06%   |
| Sound                    | 1         | 0.53%   |
| Network                  | 1         | 0.53%   |
| Net/ethernet             | 1         | 0.53%   |
| Modem                    | 1         | 0.53%   |
| Flash memory             | 1         | 0.53%   |


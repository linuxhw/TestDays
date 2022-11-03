Gentoo - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

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

Total: 965

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Dell          | Vostro 5490                 | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| Acer          | AOD257                      | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Dell          | Vostro 5490                 | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | AOD257                      | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| Dell          | Precision 5570              | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| Gigabyte      | G5 KD                       | [c0f91f7282](https://linux-hardware.org/?probe=c0f91f7282) | Oct 20, 2022 |
| Gigabyte      | G5 KD                       | [35db9f3cd8](https://linux-hardware.org/?probe=35db9f3cd8) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4644a299f3](https://linux-hardware.org/?probe=4644a299f3) | Oct 18, 2022 |
| Dell          | Precision 7760              | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| Sony          | PCG-GRT230(UC)              | [b33a31225b](https://linux-hardware.org/?probe=b33a31225b) | Oct 18, 2022 |
| HP            | Laptop 14-dk1xxx            | [caf126d0af](https://linux-hardware.org/?probe=caf126d0af) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [41d3e4e97d](https://linux-hardware.org/?probe=41d3e4e97d) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | [f60fd55235](https://linux-hardware.org/?probe=f60fd55235) | Oct 16, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| HP            | EliteBook 830 G6            | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| IBM           | ThinkPad T42 2373K1U        | [934a3226e9](https://linux-hardware.org/?probe=934a3226e9) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Intel Clie... | LAPBC710                    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| HP            | Laptop 15-ra0xx             | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| Alienware     | x14                         | [ad37874de1](https://linux-hardware.org/?probe=ad37874de1) | Oct 05, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [ae4533cfd6](https://linux-hardware.org/?probe=ae4533cfd6) | Oct 03, 2022 |
| MSI           | GE66 Raider 11UE            | [0eb2e22fc1](https://linux-hardware.org/?probe=0eb2e22fc1) | Oct 03, 2022 |
| Sony          | PCG-GRT230(UC)              | [cab24d4c04](https://linux-hardware.org/?probe=cab24d4c04) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| Sony          | PCG-GRT230(UC)              | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| System76      | Gazelle Professional        | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Timi          | TM1604                      | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| win elemen... | MoreFine S500+              | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Purism        | Librem 15 v4                | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Razer         | Blade 15 Studio Edition ... | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | GS63VR 6RF                  | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| HP            | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Toshiba       | Satellite A200              | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| Timi          | RedmiBook 13                | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Dell          | Precision 7550              | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | G3 3500                     | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| Dell          | XPS 17 9710                 | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| HP            | Laptop 14-dk1xxx            | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| HP            | ZBook 15 G3                 | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| HP            | Pavilion Notebook           | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| Lenovo        | Yoga 2 13 20344             | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| HP            | ZBook 15 G3                 | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Dell          | G3 3500                     | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| Apple         | MacBookPro11,3              | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Framework     | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Dell          | XPS 17 9710                 | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Dell          | XPS 17 9710                 | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Samsung       | RC530/RC730                 | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Dell          | Precision 7520              | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Dell          | XPS 15 9570                 | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| MSI           | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Dell          | XPS 17 9710                 | [597fae9cb6](https://linux-hardware.org/?probe=597fae9cb6) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Apple         | MacBookPro6,2               | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| Acer          | Swift SF314-59              | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Samsung       | 700T1C                      | [349d306d37](https://linux-hardware.org/?probe=349d306d37) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| HUAWEI        | HVY-WXX9                    | [f6376ab7d5](https://linux-hardware.org/?probe=f6376ab7d5) | Jan 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| Acer          | Aspire E5-571G              | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| Dell          | Precision 7560              | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [ac139db0b3](https://linux-hardware.org/?probe=ac139db0b3) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | Inspiron 15 5510            | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Framework     | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Dell          | Latitude 5420               | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| Samsung       | 700T1C                      | [f63266db56](https://linux-hardware.org/?probe=f63266db56) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [1bb2b21d60](https://linux-hardware.org/?probe=1bb2b21d60) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| HP            | Compaq 6730b (KE717AV)      | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| HP            | ProBook 430 G5              | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [49148de6c4](https://linux-hardware.org/?probe=49148de6c4) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Dell          | Latitude E7440              | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| Samsung       | RC530/RC730                 | [a4d9d06231](https://linux-hardware.org/?probe=a4d9d06231) | Nov 02, 2021 |
| Dell          | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Dell          | Latitude 5520               | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| Dell          | Latitude E6530              | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| HP            | Pavilion Notebook           | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Samsung       | RC530/RC730                 | [931664ed89](https://linux-hardware.org/?probe=931664ed89) | Oct 04, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| ASUSTek       | Unknown                     | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| Dell          | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| ASUSTek       | GX501VIK                    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| Samsung       | RC530/RC730                 | [4aa6a34c0c](https://linux-hardware.org/?probe=4aa6a34c0c) | Sep 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| Dell          | Latitude 5410               | [97ed647d4c](https://linux-hardware.org/?probe=97ed647d4c) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [9dcddb807d](https://linux-hardware.org/?probe=9dcddb807d) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [572c0c5198](https://linux-hardware.org/?probe=572c0c5198) | Sep 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [36bf3dd55d](https://linux-hardware.org/?probe=36bf3dd55d) | Sep 09, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| HP            | Pavilion g6                 | [1161032a20](https://linux-hardware.org/?probe=1161032a20) | Sep 08, 2021 |
| Dell          | Precision 7560              | [03d7773132](https://linux-hardware.org/?probe=03d7773132) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| ASUSTek       | X550ZA                      | [0d41969b6b](https://linux-hardware.org/?probe=0d41969b6b) | Sep 02, 2021 |
| Dell          | Latitude E6510              | [2ab208b5cd](https://linux-hardware.org/?probe=2ab208b5cd) | Sep 02, 2021 |
| HP            | 255 G6 Notebook PC          | [4f71a8ad02](https://linux-hardware.org/?probe=4f71a8ad02) | Sep 01, 2021 |
| HP            | ZBook 15 G3                 | [d6872bd9e9](https://linux-hardware.org/?probe=d6872bd9e9) | Sep 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| IBM           | ThinkPad T42 2373V4F        | [2362291c05](https://linux-hardware.org/?probe=2362291c05) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [5a606b504c](https://linux-hardware.org/?probe=5a606b504c) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [2af8736235](https://linux-hardware.org/?probe=2af8736235) | Aug 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [aabbe0dbcc](https://linux-hardware.org/?probe=aabbe0dbcc) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| HP            | 255 G6 Notebook PC          | [b776f7f3b7](https://linux-hardware.org/?probe=b776f7f3b7) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [62ba09ac38](https://linux-hardware.org/?probe=62ba09ac38) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 23259H1       | [fb125d2779](https://linux-hardware.org/?probe=fb125d2779) | Aug 25, 2021 |
| Dell          | Inspiron 5415               | [909e2cdc93](https://linux-hardware.org/?probe=909e2cdc93) | Aug 15, 2021 |
| Dell          | Inspiron 5415               | [63594290cf](https://linux-hardware.org/?probe=63594290cf) | Aug 11, 2021 |
| TUXEDO        | Book XC1711                 | [806e284c8a](https://linux-hardware.org/?probe=806e284c8a) | Aug 11, 2021 |
| Jumper        | EZpad                       | [da2436c208](https://linux-hardware.org/?probe=da2436c208) | Aug 11, 2021 |
| Jumper        | EZpad                       | [6215ba7396](https://linux-hardware.org/?probe=6215ba7396) | Aug 10, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ddf6a2277a](https://linux-hardware.org/?probe=ddf6a2277a) | Aug 07, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | X510UR                      | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| TUXEDO        | Book_XA1510                 | [f4f777ed12](https://linux-hardware.org/?probe=f4f777ed12) | Aug 03, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [380758e335](https://linux-hardware.org/?probe=380758e335) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a5a11a0de1](https://linux-hardware.org/?probe=a5a11a0de1) | Jul 28, 2021 |
| Dell          | XPS 15 7590                 | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3de3129139](https://linux-hardware.org/?probe=3de3129139) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6a7c7d9d8](https://linux-hardware.org/?probe=c6a7c7d9d8) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [483690e890](https://linux-hardware.org/?probe=483690e890) | Jul 14, 2021 |
| Dell          | Latitude E6430              | [3dc281ca01](https://linux-hardware.org/?probe=3dc281ca01) | Jul 13, 2021 |
| Dell          | XPS 13 9310                 | [6835266a32](https://linux-hardware.org/?probe=6835266a32) | Jul 10, 2021 |
| Dell          | Latitude E6430              | [f5a73f4d90](https://linux-hardware.org/?probe=f5a73f4d90) | Jul 09, 2021 |
| Dell          | Latitude E6430              | [8d685287ce](https://linux-hardware.org/?probe=8d685287ce) | Jul 09, 2021 |
| HP            | Pavilion Notebook           | [68c41ed42b](https://linux-hardware.org/?probe=68c41ed42b) | Jul 08, 2021 |
| HP            | Pavilion Notebook           | [5a6fca486a](https://linux-hardware.org/?probe=5a6fca486a) | Jul 08, 2021 |
| Acer          | Aspire A315-32              | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| HP            | Pro Tablet 608 G1           | [c1a115b721](https://linux-hardware.org/?probe=c1a115b721) | Jun 28, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [5d9bde452b](https://linux-hardware.org/?probe=5d9bde452b) | Jun 27, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| HUAWEI        | HN-WX9X                     | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Apple         | MacBookPro8,3               | [1453a09197](https://linux-hardware.org/?probe=1453a09197) | Jun 25, 2021 |
| Apple         | MacBookPro8,3               | [94f589e95c](https://linux-hardware.org/?probe=94f589e95c) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [8ac09d11a4](https://linux-hardware.org/?probe=8ac09d11a4) | Jun 20, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [70c10f988f](https://linux-hardware.org/?probe=70c10f988f) | Jun 20, 2021 |
| Dell          | Latitude E7440              | [9302b47a78](https://linux-hardware.org/?probe=9302b47a78) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [8d5844241c](https://linux-hardware.org/?probe=8d5844241c) | Jun 13, 2021 |
| HP            | Laptop 14-dk0xxx            | [9b07d82840](https://linux-hardware.org/?probe=9b07d82840) | Jun 12, 2021 |
| Acer          | Aspire A315-42              | [efab65cf1d](https://linux-hardware.org/?probe=efab65cf1d) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [f1d0d2bda6](https://linux-hardware.org/?probe=f1d0d2bda6) | Jun 09, 2021 |
| Lenovo        | G50-30 80G0                 | [ab9da369c0](https://linux-hardware.org/?probe=ab9da369c0) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [407abb051f](https://linux-hardware.org/?probe=407abb051f) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e6aba1341](https://linux-hardware.org/?probe=5e6aba1341) | Jun 09, 2021 |
| Dell          | Inspiron 7375               | [7704e5289b](https://linux-hardware.org/?probe=7704e5289b) | Jun 07, 2021 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [f8e58be450](https://linux-hardware.org/?probe=f8e58be450) | Jun 03, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [b571e885e2](https://linux-hardware.org/?probe=b571e885e2) | Jun 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [f3f3c323ab](https://linux-hardware.org/?probe=f3f3c323ab) | Jun 03, 2021 |
| Dell          | XPS 13 9300                 | [e85b21841c](https://linux-hardware.org/?probe=e85b21841c) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | [024ffa0922](https://linux-hardware.org/?probe=024ffa0922) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| Dell          | Inspiron 5415               | [bbf1e95976](https://linux-hardware.org/?probe=bbf1e95976) | May 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Inspiron 5415               | [abc4464787](https://linux-hardware.org/?probe=abc4464787) | May 26, 2021 |
| Dell          | Inspiron 5415               | [27c5c40e12](https://linux-hardware.org/?probe=27c5c40e12) | May 26, 2021 |
| Lenovo        | ThinkPad X230 2325BF1       | [0d334af224](https://linux-hardware.org/?probe=0d334af224) | May 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| ASUSTek       | X550ZA                      | [aef8ea73d8](https://linux-hardware.org/?probe=aef8ea73d8) | May 20, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [8a05529e0c](https://linux-hardware.org/?probe=8a05529e0c) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [6daf66a738](https://linux-hardware.org/?probe=6daf66a738) | May 18, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [50b75a0212](https://linux-hardware.org/?probe=50b75a0212) | May 17, 2021 |
| Lenovo        | Yoga 2 13 20344             | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Samsung       | RC530/RC730                 | [1da22350d7](https://linux-hardware.org/?probe=1da22350d7) | May 15, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3135               | [2773a72a9b](https://linux-hardware.org/?probe=2773a72a9b) | May 10, 2021 |
| HP            | ProBook 445 G7              | [6c504fbdf0](https://linux-hardware.org/?probe=6c504fbdf0) | May 10, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [5b8198d382](https://linux-hardware.org/?probe=5b8198d382) | May 08, 2021 |
| Dell          | Inspiron 3135               | [9bcfced245](https://linux-hardware.org/?probe=9bcfced245) | May 07, 2021 |
| Dell          | XPS 13 9310                 | [c3e8ad6826](https://linux-hardware.org/?probe=c3e8ad6826) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| Dell          | G3 3500                     | [f6624959c4](https://linux-hardware.org/?probe=f6624959c4) | May 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1d95f1feca](https://linux-hardware.org/?probe=1d95f1feca) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| Dell          | Inspiron 3542               | [aa72a49a15](https://linux-hardware.org/?probe=aa72a49a15) | Apr 30, 2021 |
| Lenovo        | ThinkPad P50 20EN0006UK     | [6f9d0f45bb](https://linux-hardware.org/?probe=6f9d0f45bb) | Apr 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0bbb4df743](https://linux-hardware.org/?probe=0bbb4df743) | Apr 27, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Dell          | G3 3500                     | [d1a4723065](https://linux-hardware.org/?probe=d1a4723065) | Apr 20, 2021 |
| Dell          | G3 3500                     | [3295e38ea9](https://linux-hardware.org/?probe=3295e38ea9) | Apr 20, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b10d744c6c](https://linux-hardware.org/?probe=b10d744c6c) | Apr 18, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [6d94f31cd6](https://linux-hardware.org/?probe=6d94f31cd6) | Apr 14, 2021 |
| Fujitsu       | LIFEBOOK T901               | [cb4c0ac9a9](https://linux-hardware.org/?probe=cb4c0ac9a9) | Apr 13, 2021 |
| TUXEDO        | N24_25BU                    | [32cc7aa6c2](https://linux-hardware.org/?probe=32cc7aa6c2) | Apr 12, 2021 |
| HP            | Pavilion Notebook           | [5159073240](https://linux-hardware.org/?probe=5159073240) | Apr 11, 2021 |
| HP            | Pavilion Notebook           | [99daea7567](https://linux-hardware.org/?probe=99daea7567) | Apr 11, 2021 |
| Dell          | G3 3500                     | [3510f864f1](https://linux-hardware.org/?probe=3510f864f1) | Apr 10, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5120fd67](https://linux-hardware.org/?probe=7e5120fd67) | Apr 06, 2021 |
| Dell          | Latitude X1                 | [a35f6c0969](https://linux-hardware.org/?probe=a35f6c0969) | Apr 05, 2021 |
| Dell          | Latitude 5480               | [a61529e37c](https://linux-hardware.org/?probe=a61529e37c) | Apr 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| Dell          | Latitude X1                 | [1e053513e0](https://linux-hardware.org/?probe=1e053513e0) | Apr 03, 2021 |
| MSI           | GE62 6QD                    | [d76949a11c](https://linux-hardware.org/?probe=d76949a11c) | Apr 01, 2021 |
| ASUSTek       | N501VW                      | [46863f1f90](https://linux-hardware.org/?probe=46863f1f90) | Mar 24, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| ASUSTek       | 1000H                       | [eda3ceb029](https://linux-hardware.org/?probe=eda3ceb029) | Mar 18, 2021 |
| Dell          | XPS 13 9380                 | [a8f5a8232e](https://linux-hardware.org/?probe=a8f5a8232e) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [65f8817baf](https://linux-hardware.org/?probe=65f8817baf) | Mar 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ed79695034](https://linux-hardware.org/?probe=ed79695034) | Mar 12, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| Dell          | Latitude 5410               | [f7ff0d1881](https://linux-hardware.org/?probe=f7ff0d1881) | Mar 07, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| Dell          | Latitude 5410               | [2f64a4536e](https://linux-hardware.org/?probe=2f64a4536e) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [ebc962c6c8](https://linux-hardware.org/?probe=ebc962c6c8) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d7384efac7](https://linux-hardware.org/?probe=d7384efac7) | Mar 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb357781c5](https://linux-hardware.org/?probe=eb357781c5) | Mar 04, 2021 |
| HP            | Pavilion Notebook           | [18e2e1ba5d](https://linux-hardware.org/?probe=18e2e1ba5d) | Mar 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ff0e82cc06](https://linux-hardware.org/?probe=ff0e82cc06) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [f343af14eb](https://linux-hardware.org/?probe=f343af14eb) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [0cf52b6b45](https://linux-hardware.org/?probe=0cf52b6b45) | Mar 03, 2021 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [723ba4e443](https://linux-hardware.org/?probe=723ba4e443) | Feb 28, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [f9cf2ced7e](https://linux-hardware.org/?probe=f9cf2ced7e) | Feb 28, 2021 |
| Dell          | G3 3500                     | [784b943c30](https://linux-hardware.org/?probe=784b943c30) | Feb 28, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f2ce82aade](https://linux-hardware.org/?probe=f2ce82aade) | Feb 27, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [83b0002691](https://linux-hardware.org/?probe=83b0002691) | Feb 27, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [b8542f3302](https://linux-hardware.org/?probe=b8542f3302) | Feb 27, 2021 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [922d2a406f](https://linux-hardware.org/?probe=922d2a406f) | Feb 26, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| TUXEDO        | Unknown                     | [ad91e37e92](https://linux-hardware.org/?probe=ad91e37e92) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | EliteBook 820 G3            | [e9e3b904a9](https://linux-hardware.org/?probe=e9e3b904a9) | Feb 19, 2021 |
| HP            | ProBook 450 G5              | [757c263c73](https://linux-hardware.org/?probe=757c263c73) | Feb 17, 2021 |
| ASUSTek       | G2SV                        | [2dcd0e4e69](https://linux-hardware.org/?probe=2dcd0e4e69) | Feb 15, 2021 |
| ASUSTek       | G2SV                        | [5b8e446be1](https://linux-hardware.org/?probe=5b8e446be1) | Feb 15, 2021 |
| TUXEDO        | Unknown                     | [c1b424bc28](https://linux-hardware.org/?probe=c1b424bc28) | Feb 15, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [418d6ee98e](https://linux-hardware.org/?probe=418d6ee98e) | Feb 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d2a976e336](https://linux-hardware.org/?probe=d2a976e336) | Feb 13, 2021 |
| HP            | OMEN by Laptop              | [d20f245092](https://linux-hardware.org/?probe=d20f245092) | Feb 13, 2021 |
| Acer          | Nitro AN515-53              | [66e023417c](https://linux-hardware.org/?probe=66e023417c) | Feb 13, 2021 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [de910b3b6f](https://linux-hardware.org/?probe=de910b3b6f) | Feb 11, 2021 |
| HP            | EliteBook 820 G3            | [0dcb414448](https://linux-hardware.org/?probe=0dcb414448) | Feb 10, 2021 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [c77ec688d3](https://linux-hardware.org/?probe=c77ec688d3) | Feb 08, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [d45ff60cd3](https://linux-hardware.org/?probe=d45ff60cd3) | Feb 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [49814ed1ce](https://linux-hardware.org/?probe=49814ed1ce) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1df927bea6](https://linux-hardware.org/?probe=1df927bea6) | Feb 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| Dell          | XPS 13 9370                 | [8e541c3c46](https://linux-hardware.org/?probe=8e541c3c46) | Feb 01, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| Chuwi         | UBook Pro                   | [d82fb9fdaf](https://linux-hardware.org/?probe=d82fb9fdaf) | Jan 26, 2021 |
| Google        | Peppy                       | [0b7e4ccb8e](https://linux-hardware.org/?probe=0b7e4ccb8e) | Jan 26, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [88cf2bc0f5](https://linux-hardware.org/?probe=88cf2bc0f5) | Jan 15, 2021 |
| Lenovo        | Unknown                     | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| IT Channel... | PA70ES                      | [f5671ea0b0](https://linux-hardware.org/?probe=f5671ea0b0) | Jan 11, 2021 |
| ASUSTek       | X555LJ                      | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| HP            | Pavilion dm1                | [db518ed539](https://linux-hardware.org/?probe=db518ed539) | Jan 08, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [ae395b2f7a](https://linux-hardware.org/?probe=ae395b2f7a) | Jan 06, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| ASUSTek       | A7V                         | [79a40b4127](https://linux-hardware.org/?probe=79a40b4127) | Jan 06, 2021 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [d6cb8dec76](https://linux-hardware.org/?probe=d6cb8dec76) | Jan 05, 2021 |
| HP            | ZBook 15 G4                 | [46ee3cd25c](https://linux-hardware.org/?probe=46ee3cd25c) | Jan 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [367d882a57](https://linux-hardware.org/?probe=367d882a57) | Jan 04, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [39cec3e63e](https://linux-hardware.org/?probe=39cec3e63e) | Jan 03, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [96374442c4](https://linux-hardware.org/?probe=96374442c4) | Jan 02, 2021 |
| Unknown       | Unknown                     | [1eb453e2b1](https://linux-hardware.org/?probe=1eb453e2b1) | Jan 02, 2021 |
| Unknown       | Unknown                     | [fee86bed02](https://linux-hardware.org/?probe=fee86bed02) | Dec 31, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [61ce6be19c](https://linux-hardware.org/?probe=61ce6be19c) | Dec 29, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | XPS 13 9380                 | [021a0a73f4](https://linux-hardware.org/?probe=021a0a73f4) | Dec 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8a19941ffe](https://linux-hardware.org/?probe=8a19941ffe) | Dec 26, 2020 |
| ASUSTek       | X550ZE                      | [8cf715c40b](https://linux-hardware.org/?probe=8cf715c40b) | Dec 23, 2020 |
| ASUSTek       | X550ZE                      | [e3e9f32f6d](https://linux-hardware.org/?probe=e3e9f32f6d) | Dec 23, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Unknown       | Unknown                     | [bf1f9d4982](https://linux-hardware.org/?probe=bf1f9d4982) | Dec 17, 2020 |
| Unknown       | Unknown                     | [5f4a9f2dc3](https://linux-hardware.org/?probe=5f4a9f2dc3) | Dec 17, 2020 |
| Dell          | Latitude 7390               | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| Acer          | Swift SF314-42              | [6e2749f503](https://linux-hardware.org/?probe=6e2749f503) | Dec 16, 2020 |
| HP            | Laptop 15-bs0xx             | [6b216f692c](https://linux-hardware.org/?probe=6b216f692c) | Dec 15, 2020 |
| Dell          | XPS 15 7590                 | [4312c9878e](https://linux-hardware.org/?probe=4312c9878e) | Dec 14, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [a4e14d24c6](https://linux-hardware.org/?probe=a4e14d24c6) | Dec 13, 2020 |
| Lenovo        | ThinkPad P52s 20LBS0FF00    | [4826998fda](https://linux-hardware.org/?probe=4826998fda) | Dec 12, 2020 |
| HP            | ProBook 430 G5              | [c9a8c10a8f](https://linux-hardware.org/?probe=c9a8c10a8f) | Dec 10, 2020 |
| Samsung       | RC530/RC730                 | [69c8fa5fee](https://linux-hardware.org/?probe=69c8fa5fee) | Dec 09, 2020 |
| MSI           | GF63 Thin 9SC               | [5a23e8cfc4](https://linux-hardware.org/?probe=5a23e8cfc4) | Dec 06, 2020 |
| Dell          | XPS 13 9370                 | [bd8f5aa7df](https://linux-hardware.org/?probe=bd8f5aa7df) | Dec 05, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Lenovo        | ThinkPad P50 20EQS30D00     | [356758a7d8](https://linux-hardware.org/?probe=356758a7d8) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | [60ec1448d4](https://linux-hardware.org/?probe=60ec1448d4) | Nov 29, 2020 |
| Dell          | Latitude E5500              | [079101f502](https://linux-hardware.org/?probe=079101f502) | Nov 29, 2020 |
| Dell          | XPS 15 9570                 | [613707835e](https://linux-hardware.org/?probe=613707835e) | Nov 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [49a0bab061](https://linux-hardware.org/?probe=49a0bab061) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a175dbabc2](https://linux-hardware.org/?probe=a175dbabc2) | Nov 12, 2020 |
| Dell          | Latitude 5490               | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| HP            | EliteBook 820 G4            | [13e0c5e646](https://linux-hardware.org/?probe=13e0c5e646) | Nov 10, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [3a052bbb91](https://linux-hardware.org/?probe=3a052bbb91) | Nov 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [53efc559ad](https://linux-hardware.org/?probe=53efc559ad) | Nov 08, 2020 |
| Dell          | XPS 13 9360                 | [a6cf5e7036](https://linux-hardware.org/?probe=a6cf5e7036) | Nov 07, 2020 |
| Dell          | Latitude 7410               | [af066ad306](https://linux-hardware.org/?probe=af066ad306) | Nov 04, 2020 |
| Acer          | Nitro AN715-51              | [8cb76bb2f8](https://linux-hardware.org/?probe=8cb76bb2f8) | Nov 03, 2020 |
| Acer          | Nitro AN715-51              | [485080dff0](https://linux-hardware.org/?probe=485080dff0) | Nov 03, 2020 |
| Dell          | G3 3500                     | [fb7c201de0](https://linux-hardware.org/?probe=fb7c201de0) | Nov 01, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [ec44c959a4](https://linux-hardware.org/?probe=ec44c959a4) | Nov 01, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| Lenovo        | B51-80 80LM                 | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| Sony          | VPCSC41FM                   | [a7607a7b93](https://linux-hardware.org/?probe=a7607a7b93) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [ef90a9df54](https://linux-hardware.org/?probe=ef90a9df54) | Oct 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [c15ef33580](https://linux-hardware.org/?probe=c15ef33580) | Oct 25, 2020 |
| Acer          | Aspire E5-571G              | [b52fb33c4d](https://linux-hardware.org/?probe=b52fb33c4d) | Oct 25, 2020 |
| HP            | Pavilion g7                 | [585d199b71](https://linux-hardware.org/?probe=585d199b71) | Oct 25, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [447a3a003d](https://linux-hardware.org/?probe=447a3a003d) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [f8f15c63ad](https://linux-hardware.org/?probe=f8f15c63ad) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [b3df3d26f0](https://linux-hardware.org/?probe=b3df3d26f0) | Oct 24, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f0cf2671f2](https://linux-hardware.org/?probe=f0cf2671f2) | Oct 24, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 455 G7              | [70aaf58443](https://linux-hardware.org/?probe=70aaf58443) | Oct 19, 2020 |
| HP            | Pavilion dv7                | [65917ebd9d](https://linux-hardware.org/?probe=65917ebd9d) | Oct 18, 2020 |
| Dell          | XPS 15 7590                 | [daa70ce737](https://linux-hardware.org/?probe=daa70ce737) | Oct 17, 2020 |
| HP            | EliteBook 820 G4            | [ea2fe3b4dc](https://linux-hardware.org/?probe=ea2fe3b4dc) | Oct 15, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0W10... | [64c3cf228e](https://linux-hardware.org/?probe=64c3cf228e) | Oct 14, 2020 |
| Dell          | Latitude E7270              | [efcbc76194](https://linux-hardware.org/?probe=efcbc76194) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [6199eaf93c](https://linux-hardware.org/?probe=6199eaf93c) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [c04da65193](https://linux-hardware.org/?probe=c04da65193) | Oct 11, 2020 |
| Fujitsu       | LIFEBOOK P770               | [48fc4ff4db](https://linux-hardware.org/?probe=48fc4ff4db) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5cd90973fc](https://linux-hardware.org/?probe=5cd90973fc) | Oct 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c5d15be62](https://linux-hardware.org/?probe=9c5d15be62) | Oct 04, 2020 |
| Dell          | G5 5587                     | [c99b5f8c72](https://linux-hardware.org/?probe=c99b5f8c72) | Oct 02, 2020 |
| ASUSTek       | X555LJ                      | [bd5306ec57](https://linux-hardware.org/?probe=bd5306ec57) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | G3 3500                     | [23b58bcd77](https://linux-hardware.org/?probe=23b58bcd77) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [951fafbea0](https://linux-hardware.org/?probe=951fafbea0) | Sep 19, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [e638fa0818](https://linux-hardware.org/?probe=e638fa0818) | Sep 19, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Lenovo        | Unknown                     | [5107d64dc0](https://linux-hardware.org/?probe=5107d64dc0) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | [9d3b97061b](https://linux-hardware.org/?probe=9d3b97061b) | Sep 15, 2020 |
| HP            | ProBook 450 G5              | [4d67605a9a](https://linux-hardware.org/?probe=4d67605a9a) | Sep 14, 2020 |
| Dell          | G3 3500                     | [73839e86fc](https://linux-hardware.org/?probe=73839e86fc) | Sep 14, 2020 |
| PC Special... | GK7NP5R                     | [2ba7289378](https://linux-hardware.org/?probe=2ba7289378) | Sep 11, 2020 |
| Dell          | Latitude 5501               | [bceeec9520](https://linux-hardware.org/?probe=bceeec9520) | Sep 10, 2020 |
| Dell          | Latitude 5501               | [0df822dc02](https://linux-hardware.org/?probe=0df822dc02) | Sep 09, 2020 |
| Lenovo        | ThinkPad X220 429029G       | [2e86679c2f](https://linux-hardware.org/?probe=2e86679c2f) | Sep 05, 2020 |
| Apple         | MacBookPro12,1              | [0f915dee52](https://linux-hardware.org/?probe=0f915dee52) | Sep 03, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [294fd98c3f](https://linux-hardware.org/?probe=294fd98c3f) | Sep 01, 2020 |
| HUAWEI        | HLY-WX9XX                   | [51bcf816e6](https://linux-hardware.org/?probe=51bcf816e6) | Sep 01, 2020 |
| Apple         | MacBookPro12,1              | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| HP            | Pavilion 11 x360 PC         | [2857ef3b7b](https://linux-hardware.org/?probe=2857ef3b7b) | Aug 30, 2020 |
| Dell          | Latitude 5401               | [fdb1d25e99](https://linux-hardware.org/?probe=fdb1d25e99) | Aug 27, 2020 |
| ASUSTek       | GL552VW                     | [9462a9e9ec](https://linux-hardware.org/?probe=9462a9e9ec) | Aug 26, 2020 |
| ASUSTek       | GL552VW                     | [1e5df72d90](https://linux-hardware.org/?probe=1e5df72d90) | Aug 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [63d74a10a6](https://linux-hardware.org/?probe=63d74a10a6) | Aug 25, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [5590d3f68a](https://linux-hardware.org/?probe=5590d3f68a) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [744c56e875](https://linux-hardware.org/?probe=744c56e875) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a0960a7256](https://linux-hardware.org/?probe=a0960a7256) | Aug 25, 2020 |
| Dell          | XPS 15 7590                 | [1ecbfe31cc](https://linux-hardware.org/?probe=1ecbfe31cc) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [d475ab6b1f](https://linux-hardware.org/?probe=d475ab6b1f) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [25f98c006e](https://linux-hardware.org/?probe=25f98c006e) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [c2d9b7b8f9](https://linux-hardware.org/?probe=c2d9b7b8f9) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [7c299b5384](https://linux-hardware.org/?probe=7c299b5384) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [19586f3d92](https://linux-hardware.org/?probe=19586f3d92) | Aug 23, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [d5c4efd016](https://linux-hardware.org/?probe=d5c4efd016) | Aug 23, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [c82c12e968](https://linux-hardware.org/?probe=c82c12e968) | Aug 22, 2020 |
| Notebook      | N141CU                      | [9c7c4fff3e](https://linux-hardware.org/?probe=9c7c4fff3e) | Aug 22, 2020 |
| Wortmann      | TERRA_MOBILE_1590S          | [ade9df5306](https://linux-hardware.org/?probe=ade9df5306) | Aug 21, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8f067e33b6](https://linux-hardware.org/?probe=8f067e33b6) | Aug 21, 2020 |
| Dell          | G3 3500                     | [093682c4c4](https://linux-hardware.org/?probe=093682c4c4) | Aug 20, 2020 |
| Lenovo        | G580 20150                  | [1e7c1ee27a](https://linux-hardware.org/?probe=1e7c1ee27a) | Aug 20, 2020 |
| Dell          | G3 3500                     | [c64b8a0e61](https://linux-hardware.org/?probe=c64b8a0e61) | Aug 20, 2020 |
| Lenovo        | ThinkPad T590 20N4001YPB    | [c6283736fd](https://linux-hardware.org/?probe=c6283736fd) | Aug 19, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [fd339f3d69](https://linux-hardware.org/?probe=fd339f3d69) | Aug 17, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [19177595c8](https://linux-hardware.org/?probe=19177595c8) | Aug 16, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [9d003ef2fe](https://linux-hardware.org/?probe=9d003ef2fe) | Aug 16, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c7793f1daa](https://linux-hardware.org/?probe=c7793f1daa) | Aug 15, 2020 |
| Apple         | MacBookPro4,1               | [184e80bbc6](https://linux-hardware.org/?probe=184e80bbc6) | Aug 13, 2020 |
| Apple         | MacBookPro4,1               | [64593dd4a6](https://linux-hardware.org/?probe=64593dd4a6) | Aug 13, 2020 |
| Dell          | Inspiron 5755               | [89d1209c2c](https://linux-hardware.org/?probe=89d1209c2c) | Aug 12, 2020 |
| Notebook      | N141CU                      | [38cc94083d](https://linux-hardware.org/?probe=38cc94083d) | Aug 10, 2020 |
| Apple         | MacBookPro8,2               | [1dd9ee1d09](https://linux-hardware.org/?probe=1dd9ee1d09) | Aug 09, 2020 |
| Apple         | MacBookPro8,1               | [092f544ecc](https://linux-hardware.org/?probe=092f544ecc) | Aug 08, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4fe8ac3a02](https://linux-hardware.org/?probe=4fe8ac3a02) | Aug 08, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad X270 20HN002UGE    | [c0b7a3c300](https://linux-hardware.org/?probe=c0b7a3c300) | Aug 07, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a7ae8a6f78](https://linux-hardware.org/?probe=a7ae8a6f78) | Aug 07, 2020 |
| ASUSTek       | X406UAR                     | [97f52734c2](https://linux-hardware.org/?probe=97f52734c2) | Aug 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [d67ba67beb](https://linux-hardware.org/?probe=d67ba67beb) | Aug 05, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Apple         | MacBookPro5,1               | [c896b174a5](https://linux-hardware.org/?probe=c896b174a5) | Aug 03, 2020 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [4c08ca19cf](https://linux-hardware.org/?probe=4c08ca19cf) | Jul 30, 2020 |
| Dell          | Latitude 5500               | [4e1eb098f2](https://linux-hardware.org/?probe=4e1eb098f2) | Jul 28, 2020 |
| Sony          | VPCSC41FM                   | [3a1470664d](https://linux-hardware.org/?probe=3a1470664d) | Jul 24, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [a235d0f3c3](https://linux-hardware.org/?probe=a235d0f3c3) | Jul 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [68c95d0921](https://linux-hardware.org/?probe=68c95d0921) | Jul 17, 2020 |
| Acer          | Nitro AN515-53              | [85bf9e9450](https://linux-hardware.org/?probe=85bf9e9450) | Jul 17, 2020 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [43a917118a](https://linux-hardware.org/?probe=43a917118a) | Jul 14, 2020 |
| XMG           | C504                        | [a97e52282c](https://linux-hardware.org/?probe=a97e52282c) | Jul 13, 2020 |
| System76      | Lemur Pro                   | [ef0445b033](https://linux-hardware.org/?probe=ef0445b033) | Jul 09, 2020 |
| HP            | EliteBook 745 G6            | [b7f42e3bd9](https://linux-hardware.org/?probe=b7f42e3bd9) | Jul 06, 2020 |
| HP            | EliteBook 745 G6            | [d73fb2d895](https://linux-hardware.org/?probe=d73fb2d895) | Jul 05, 2020 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [359f4615fa](https://linux-hardware.org/?probe=359f4615fa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X100e 35089TU      | [6dccb35fcb](https://linux-hardware.org/?probe=6dccb35fcb) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [9729dd440a](https://linux-hardware.org/?probe=9729dd440a) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [26a392b2c1](https://linux-hardware.org/?probe=26a392b2c1) | Jul 03, 2020 |
| Samsung       | R530/R730/P530              | [e1539a8d98](https://linux-hardware.org/?probe=e1539a8d98) | Jul 01, 2020 |
| Dell          | Latitude 5491               | [f861e71f84](https://linux-hardware.org/?probe=f861e71f84) | Jun 28, 2020 |
| Acer          | Nitro AN515-53              | [64802f828b](https://linux-hardware.org/?probe=64802f828b) | Jun 27, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [71beca8605](https://linux-hardware.org/?probe=71beca8605) | Jun 25, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Lenovo        | G710 20252                  | [f83c73bef0](https://linux-hardware.org/?probe=f83c73bef0) | Jun 15, 2020 |
| Dell          | Latitude 5480               | [d0d56fbb1d](https://linux-hardware.org/?probe=d0d56fbb1d) | Jun 14, 2020 |
| Acer          | Nitro AN515-53              | [701ffbf49a](https://linux-hardware.org/?probe=701ffbf49a) | Jun 12, 2020 |
| Dell          | XPS 13 9360                 | [b4be1dd313](https://linux-hardware.org/?probe=b4be1dd313) | Jun 09, 2020 |
| Acer          | Swift SF315-51              | [e703cb72e3](https://linux-hardware.org/?probe=e703cb72e3) | Jun 08, 2020 |
| Dell          | XPS 15 9530                 | [b93caec229](https://linux-hardware.org/?probe=b93caec229) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca7ca5b14e](https://linux-hardware.org/?probe=ca7ca5b14e) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| Dell          | Latitude E5570              | [e7012f0658](https://linux-hardware.org/?probe=e7012f0658) | Jun 05, 2020 |
| Dell          | System XPS L702X            | [a993cb7099](https://linux-hardware.org/?probe=a993cb7099) | Jun 04, 2020 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [b52ad09036](https://linux-hardware.org/?probe=b52ad09036) | Jun 04, 2020 |
| Dell          | XPS 13 9360                 | [e1d648a5f2](https://linux-hardware.org/?probe=e1d648a5f2) | Jun 04, 2020 |
| Lenovo        | ThinkPad L390 20NR001KRT    | [19809108e4](https://linux-hardware.org/?probe=19809108e4) | Jun 04, 2020 |
| Dell          | Inspiron 5577               | [b29e45343d](https://linux-hardware.org/?probe=b29e45343d) | Jun 04, 2020 |
| ASUSTek       | X555LJ                      | [8a0dab5948](https://linux-hardware.org/?probe=8a0dab5948) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [a173aacb52](https://linux-hardware.org/?probe=a173aacb52) | Jun 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d082b8d834](https://linux-hardware.org/?probe=d082b8d834) | Jun 03, 2020 |
| ASUSTek       | UX310UAR                    | [1b9a59e4ca](https://linux-hardware.org/?probe=1b9a59e4ca) | Jun 03, 2020 |
| ASUSTek       | UX410UAR                    | [d3b1cf2698](https://linux-hardware.org/?probe=d3b1cf2698) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [31a6aa1e70](https://linux-hardware.org/?probe=31a6aa1e70) | May 31, 2020 |
| Acer          | Aspire VN7-592G             | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| MSI           | GT63 Titan 8SG              | [85363c0652](https://linux-hardware.org/?probe=85363c0652) | May 25, 2020 |
| Acer          | Aspire V3-771               | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [a37835c09e](https://linux-hardware.org/?probe=a37835c09e) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [017c1e4813](https://linux-hardware.org/?probe=017c1e4813) | May 24, 2020 |
| Chuwi         | LapBook Pro                 | [a4be681659](https://linux-hardware.org/?probe=a4be681659) | May 23, 2020 |
| Timi          | Mi Laptop Air 12.5          | [fea499e36a](https://linux-hardware.org/?probe=fea499e36a) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| Dell          | Latitude E6440              | [cb23d3096c](https://linux-hardware.org/?probe=cb23d3096c) | May 19, 2020 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [25ed02b04a](https://linux-hardware.org/?probe=25ed02b04a) | May 19, 2020 |
| Dell          | Latitude E5540              | [8ea71ba2ae](https://linux-hardware.org/?probe=8ea71ba2ae) | May 19, 2020 |
| Unknown       | Unknown                     | [48a9c9544a](https://linux-hardware.org/?probe=48a9c9544a) | May 16, 2020 |
| Dell          | Latitude 3400               | [0787585d2e](https://linux-hardware.org/?probe=0787585d2e) | May 15, 2020 |
| Dell          | Latitude 3400               | [04b3381928](https://linux-hardware.org/?probe=04b3381928) | May 15, 2020 |
| Lenovo        | IdeaPad Z370                | [81a1579081](https://linux-hardware.org/?probe=81a1579081) | May 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [0efeb1e15a](https://linux-hardware.org/?probe=0efeb1e15a) | May 14, 2020 |
| Dell          | Latitude E6520              | [e275465d57](https://linux-hardware.org/?probe=e275465d57) | May 13, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9e904a50ca](https://linux-hardware.org/?probe=9e904a50ca) | May 12, 2020 |
| Seco          | UDOO x86                    | [62ae920d77](https://linux-hardware.org/?probe=62ae920d77) | May 12, 2020 |
| Toshiba       | Satellite L50-A-16G         | [dea54eb8a1](https://linux-hardware.org/?probe=dea54eb8a1) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [748a1ea384](https://linux-hardware.org/?probe=748a1ea384) | May 11, 2020 |
| ASUSTek       | E402NA                      | [bc0fa6176d](https://linux-hardware.org/?probe=bc0fa6176d) | May 11, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [b2649601d3](https://linux-hardware.org/?probe=b2649601d3) | May 10, 2020 |
| Unknown       | Unknown                     | [7740c04b4b](https://linux-hardware.org/?probe=7740c04b4b) | May 08, 2020 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [e0968088b3](https://linux-hardware.org/?probe=e0968088b3) | May 08, 2020 |
| Apple         | MacBookPro8,2               | [9602f32094](https://linux-hardware.org/?probe=9602f32094) | May 03, 2020 |
| Unknown       | Unknown                     | [97f8a22d28](https://linux-hardware.org/?probe=97f8a22d28) | May 03, 2020 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [be25ab70cb](https://linux-hardware.org/?probe=be25ab70cb) | May 01, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [729a079629](https://linux-hardware.org/?probe=729a079629) | Apr 28, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [6e5f544240](https://linux-hardware.org/?probe=6e5f544240) | Apr 28, 2020 |
| Unknown       | Unknown                     | [eb36ed044f](https://linux-hardware.org/?probe=eb36ed044f) | Apr 26, 2020 |
| Dell          | Latitude E6420              | [f33530c32a](https://linux-hardware.org/?probe=f33530c32a) | Apr 26, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [bf47e6f662](https://linux-hardware.org/?probe=bf47e6f662) | Apr 26, 2020 |
| Dell          | Latitude 7390               | [59c245d756](https://linux-hardware.org/?probe=59c245d756) | Apr 20, 2020 |
| Dell          | Latitude 7390               | [c91eb58962](https://linux-hardware.org/?probe=c91eb58962) | Apr 20, 2020 |
| Dell          | Latitude E5470              | [568a079f29](https://linux-hardware.org/?probe=568a079f29) | Apr 17, 2020 |
| Dell          | Latitude E7440              | [037a28c347](https://linux-hardware.org/?probe=037a28c347) | Apr 17, 2020 |
| Dell          | Latitude E5470              | [c2b554cdcf](https://linux-hardware.org/?probe=c2b554cdcf) | Apr 15, 2020 |
| HP            | x360 310 G1 PC              | [9751d299ad](https://linux-hardware.org/?probe=9751d299ad) | Apr 15, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c80d705080](https://linux-hardware.org/?probe=c80d705080) | Apr 12, 2020 |
| Dell          | Inspiron 7520               | [31c3181139](https://linux-hardware.org/?probe=31c3181139) | Apr 12, 2020 |
| Lenovo        | G570 20079                  | [af1e15f9d1](https://linux-hardware.org/?probe=af1e15f9d1) | Apr 11, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [ca529580d5](https://linux-hardware.org/?probe=ca529580d5) | Apr 10, 2020 |
| Acer          | Aspire V3-331               | [3556b592c2](https://linux-hardware.org/?probe=3556b592c2) | Apr 09, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [89ce2a3948](https://linux-hardware.org/?probe=89ce2a3948) | Apr 05, 2020 |
| Dell          | Precision M4600             | [b88c9f527c](https://linux-hardware.org/?probe=b88c9f527c) | Apr 03, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [de1b814a88](https://linux-hardware.org/?probe=de1b814a88) | Apr 02, 2020 |
| HP            | ProBook 4510s               | [26fb60e010](https://linux-hardware.org/?probe=26fb60e010) | Apr 01, 2020 |
| Acer          | Aspire VN7-571G             | [259bfff741](https://linux-hardware.org/?probe=259bfff741) | Mar 29, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [6bc7d86b9c](https://linux-hardware.org/?probe=6bc7d86b9c) | Mar 28, 2020 |
| HP            | OMEN by Laptop              | [e7e39b1152](https://linux-hardware.org/?probe=e7e39b1152) | Mar 22, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a42a77029d](https://linux-hardware.org/?probe=a42a77029d) | Mar 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | ThinkPad Z61m 945038U       | [e5c5ce1445](https://linux-hardware.org/?probe=e5c5ce1445) | Mar 01, 2020 |
| Dell          | XPS 15 7590                 | [fba41b433f](https://linux-hardware.org/?probe=fba41b433f) | Feb 27, 2020 |
| Acer          | Aspire V3-331               | [98986faf06](https://linux-hardware.org/?probe=98986faf06) | Feb 21, 2020 |
| Acer          | Aspire V3-331               | [400111ccfc](https://linux-hardware.org/?probe=400111ccfc) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| MSI           | GT73EVR 7RF                 | [99e70d86e2](https://linux-hardware.org/?probe=99e70d86e2) | Feb 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d140409c65](https://linux-hardware.org/?probe=d140409c65) | Feb 18, 2020 |
| Acer          | Aspire V3-331               | [68e659c87d](https://linux-hardware.org/?probe=68e659c87d) | Feb 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | [28fbda9ecd](https://linux-hardware.org/?probe=28fbda9ecd) | Feb 11, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [80f496eacd](https://linux-hardware.org/?probe=80f496eacd) | Feb 11, 2020 |
| Acer          | Aspire V3-331               | [1ed27701ea](https://linux-hardware.org/?probe=1ed27701ea) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [5fe84895f2](https://linux-hardware.org/?probe=5fe84895f2) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [bf08aa9738](https://linux-hardware.org/?probe=bf08aa9738) | Feb 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dbdccc5696](https://linux-hardware.org/?probe=dbdccc5696) | Feb 06, 2020 |
| Acer          | Aspire V3-331               | [f970ff6696](https://linux-hardware.org/?probe=f970ff6696) | Feb 05, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [423ca04065](https://linux-hardware.org/?probe=423ca04065) | Jan 30, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [e4e856b6f2](https://linux-hardware.org/?probe=e4e856b6f2) | Jan 30, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [d5fbd58f8b](https://linux-hardware.org/?probe=d5fbd58f8b) | Jan 27, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [88338e7031](https://linux-hardware.org/?probe=88338e7031) | Jan 27, 2020 |
| HP            | Pavilion dv7                | [119a35f980](https://linux-hardware.org/?probe=119a35f980) | Jan 26, 2020 |
| Lenovo        | Y50-70 20378                | [39a9917502](https://linux-hardware.org/?probe=39a9917502) | Jan 24, 2020 |
| MSI           | GE62 6QD                    | [54574b77f2](https://linux-hardware.org/?probe=54574b77f2) | Jan 24, 2020 |
| Lenovo        | Y50-70 20378                | [c34eecb4fb](https://linux-hardware.org/?probe=c34eecb4fb) | Jan 24, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| HP            | ZBook 15 G2                 | [2b62bc6c8a](https://linux-hardware.org/?probe=2b62bc6c8a) | Jan 19, 2020 |
| HP            | ZBook 15 G2                 | [191021f74e](https://linux-hardware.org/?probe=191021f74e) | Jan 19, 2020 |
| Lenovo        | ThinkPad T450s 20BWS3F00... | [cf32529cfe](https://linux-hardware.org/?probe=cf32529cfe) | Jan 09, 2020 |
| Lenovo        | ThinkPad 20QJ001GMX         | [e720c77930](https://linux-hardware.org/?probe=e720c77930) | Jan 09, 2020 |
| Medion        | P6669 MD60147               | [b857f2b82d](https://linux-hardware.org/?probe=b857f2b82d) | Jan 07, 2020 |
| Lenovo        | ThinkPad T490s 20NX007AG... | [12b5e06a49](https://linux-hardware.org/?probe=12b5e06a49) | Jan 04, 2020 |
| Acer          | Aspire A315-42              | [96d84c0576](https://linux-hardware.org/?probe=96d84c0576) | Dec 22, 2019 |
| Acer          | Aspire A315-42              | [e36036a3d5](https://linux-hardware.org/?probe=e36036a3d5) | Dec 21, 2019 |
| Acer          | Aspire A315-42              | [f16e75f852](https://linux-hardware.org/?probe=f16e75f852) | Dec 14, 2019 |
| HP            | EliteBook 840 G6            | [6b2396c6ac](https://linux-hardware.org/?probe=6b2396c6ac) | Dec 08, 2019 |
| Dell          | G3 3779                     | [716cb93844](https://linux-hardware.org/?probe=716cb93844) | Dec 06, 2019 |
| Dell          | Latitude 7390               | [714656669c](https://linux-hardware.org/?probe=714656669c) | Dec 02, 2019 |
| HP            | ZBook 15                    | [196dfe92a3](https://linux-hardware.org/?probe=196dfe92a3) | Nov 27, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [be40a37ea8](https://linux-hardware.org/?probe=be40a37ea8) | Nov 24, 2019 |
| Acer          | Aspire V5-431               | [6a087dd575](https://linux-hardware.org/?probe=6a087dd575) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [3200b20576](https://linux-hardware.org/?probe=3200b20576) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [b7089462b3](https://linux-hardware.org/?probe=b7089462b3) | Nov 16, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ec55fd6791](https://linux-hardware.org/?probe=ec55fd6791) | Oct 06, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e46079e2f8](https://linux-hardware.org/?probe=e46079e2f8) | Oct 06, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [e1dfe6707d](https://linux-hardware.org/?probe=e1dfe6707d) | Oct 06, 2019 |
| Acer          | Aspire E5-511               | [af59a812bc](https://linux-hardware.org/?probe=af59a812bc) | Sep 29, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [215d2a28a4](https://linux-hardware.org/?probe=215d2a28a4) | Aug 15, 2019 |
| Dell          | Latitude 7390               | [d360b45394](https://linux-hardware.org/?probe=d360b45394) | Aug 15, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [e643de7d13](https://linux-hardware.org/?probe=e643de7d13) | Aug 15, 2019 |
| Timi          | Mi Laptop Air 12.5          | [8d36fc215c](https://linux-hardware.org/?probe=8d36fc215c) | Aug 14, 2019 |
| Lenovo        | ThinkPad T440s 20AQ0066M... | [54b33d56bb](https://linux-hardware.org/?probe=54b33d56bb) | Aug 14, 2019 |
| Dell          | Latitude E6430              | [4e38982788](https://linux-hardware.org/?probe=4e38982788) | Aug 13, 2019 |
| Dell          | Latitude 7390               | [05cdc89a9d](https://linux-hardware.org/?probe=05cdc89a9d) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [1369716caa](https://linux-hardware.org/?probe=1369716caa) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [e90e03524b](https://linux-hardware.org/?probe=e90e03524b) | Aug 12, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [65e73516b5](https://linux-hardware.org/?probe=65e73516b5) | Aug 03, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [7b994d2ec2](https://linux-hardware.org/?probe=7b994d2ec2) | Jul 31, 2019 |
| Apple         | MacBookPro1,1               | [46f4e56e3f](https://linux-hardware.org/?probe=46f4e56e3f) | Jul 21, 2019 |
| Apple         | MacBookPro8,2               | [88b8816bfe](https://linux-hardware.org/?probe=88b8816bfe) | Jul 11, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [8556fe8940](https://linux-hardware.org/?probe=8556fe8940) | Jul 11, 2019 |
| Apple         | MacBookPro8,2               | [3d2225e709](https://linux-hardware.org/?probe=3d2225e709) | Jul 11, 2019 |
| Dell          | Latitude E7250              | [64dc3ace03](https://linux-hardware.org/?probe=64dc3ace03) | Jun 17, 2019 |
| Dell          | Latitude E7250              | [02b9759d77](https://linux-hardware.org/?probe=02b9759d77) | Jun 16, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [31a261423c](https://linux-hardware.org/?probe=31a261423c) | Jun 11, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [6a667c9ba7](https://linux-hardware.org/?probe=6a667c9ba7) | Jun 11, 2019 |
| Dell          | Inspiron 7520               | [744af8e456](https://linux-hardware.org/?probe=744af8e456) | Jun 10, 2019 |
| Dell          | Inspiron 7520               | [9ed6957c8b](https://linux-hardware.org/?probe=9ed6957c8b) | Jun 07, 2019 |
| HP            | OMEN by Laptop 15-dc0xxx    | [06ee78ee4d](https://linux-hardware.org/?probe=06ee78ee4d) | Apr 26, 2019 |
| HP            | ProBook 4510s               | [b1ed13a854](https://linux-hardware.org/?probe=b1ed13a854) | Mar 29, 2019 |
| Dell          | Latitude E7250              | [0ee5638d26](https://linux-hardware.org/?probe=0ee5638d26) | Mar 29, 2019 |
| Positivo      | WCBT1013                    | [e6f1ac9248](https://linux-hardware.org/?probe=e6f1ac9248) | Mar 27, 2019 |
| Dell          | Latitude E7250              | [fcd5b5c6f3](https://linux-hardware.org/?probe=fcd5b5c6f3) | Mar 23, 2019 |
| Dell          | Latitude E7250              | [61982fcb92](https://linux-hardware.org/?probe=61982fcb92) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [3c8e2e4aba](https://linux-hardware.org/?probe=3c8e2e4aba) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [ae7e990d2c](https://linux-hardware.org/?probe=ae7e990d2c) | Mar 19, 2019 |
| HP            | OMEN by Laptop              | [7bd53b3ffb](https://linux-hardware.org/?probe=7bd53b3ffb) | Nov 28, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [9a4db5d6fd](https://linux-hardware.org/?probe=9a4db5d6fd) | Nov 14, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [93a71f7e7f](https://linux-hardware.org/?probe=93a71f7e7f) | Nov 14, 2018 |
| Lenovo        | ThinkPad X230 23252UU       | [cefd5e879b](https://linux-hardware.org/?probe=cefd5e879b) | Nov 08, 2018 |
| ASUSTek       | K55VJ                       | [f23b5bf0da](https://linux-hardware.org/?probe=f23b5bf0da) | Nov 01, 2018 |
| Medion        | X783X                       | [852662bdf3](https://linux-hardware.org/?probe=852662bdf3) | Oct 31, 2018 |
| Lenovo        | ThinkPad X1 Carbon 3460B... | [b7014678b5](https://linux-hardware.org/?probe=b7014678b5) | Oct 30, 2018 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [6f9dca6953](https://linux-hardware.org/?probe=6f9dca6953) | Oct 29, 2018 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4438a85b31](https://linux-hardware.org/?probe=4438a85b31) | Oct 26, 2018 |
| ASUSTek       | N73SM                       | [a5a0da657b](https://linux-hardware.org/?probe=a5a0da657b) | Oct 11, 2018 |
| Positivo      | Unknown                     | [d826611187](https://linux-hardware.org/?probe=d826611187) | Sep 24, 2018 |
| HP            | OMEN by Laptop 17-an0xx     | [142d7492c2](https://linux-hardware.org/?probe=142d7492c2) | Sep 16, 2018 |
| HP            | OMEN by Laptop 17-an0xx     | [65292e94a4](https://linux-hardware.org/?probe=65292e94a4) | Sep 16, 2018 |
| Dell          | XPS 13 9370                 | [424d23c5fe](https://linux-hardware.org/?probe=424d23c5fe) | Sep 01, 2018 |
| Dell          | XPS 13 9370                 | [f4ea533636](https://linux-hardware.org/?probe=f4ea533636) | Sep 01, 2018 |
| Acer          | Aspire SW3-016              | [425d589d65](https://linux-hardware.org/?probe=425d589d65) | Apr 01, 2018 |
| Samsung       | R425/R525                   | [eeb54d2d46](https://linux-hardware.org/?probe=eeb54d2d46) | Oct 04, 2017 |
| Samsung       | R425/R525                   | [140a1aad88](https://linux-hardware.org/?probe=140a1aad88) | Oct 04, 2017 |
| Lenovo        | B50-30 20382                | [b4e99f70a9](https://linux-hardware.org/?probe=b4e99f70a9) | Sep 28, 2017 |
| MSI           | GE72 6QF                    | [1c47bc90e4](https://linux-hardware.org/?probe=1c47bc90e4) | Dec 18, 2016 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [25576a8571](https://linux-hardware.org/?probe=25576a8571) | Jul 16, 2016 |
| Samsung       | NC10                        | [3ad0ff0e13](https://linux-hardware.org/?probe=3ad0ff0e13) | Jul 12, 2016 |
| MSI           | GS60 6QC                    | [404f145917](https://linux-hardware.org/?probe=404f145917) | May 18, 2016 |
| Samsung       | NC10                        | [6da4c3c370](https://linux-hardware.org/?probe=6da4c3c370) | Mar 06, 2016 |
| ASUSTek       | N501VW                      | [5b1076ea3c](https://linux-hardware.org/?probe=5b1076ea3c) | Mar 02, 2016 |
| HP            | EliteBook 2540p             | [bd135661d2](https://linux-hardware.org/?probe=bd135661d2) | Feb 11, 2016 |
| HP            | EliteBook 2540p             | [f25f73d78c](https://linux-hardware.org/?probe=f25f73d78c) | Feb 11, 2016 |
| Acer          | Aspire E5-522               | [76013f1c62](https://linux-hardware.org/?probe=76013f1c62) | Feb 04, 2016 |
| Lenovo        | G570 20079                  | [2239d316e8](https://linux-hardware.org/?probe=2239d316e8) | Nov 26, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 243       | 39.64%  |
| Gentoo 2.6     | 199       | 32.46%  |
| Gentoo 2.8     | 143       | 23.33%  |
| Gentoo         | 6         | 0.98%   |
| Gentoo 2.9     | 5         | 0.82%   |
| Gentoo 2.4.1   | 5         | 0.82%   |
| Gentoo 2.3     | 4         | 0.65%   |
| Gentoo 2.2     | 4         | 0.65%   |
| Gentoo Pelikan | 1         | 0.16%   |
| Gentoo 22      | 1         | 0.16%   |
| Gentoo 2.1     | 1         | 0.16%   |
| Gentoo 1       | 1         | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 555       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 16        | 2.26%   |
| 5.10.61-gentoo           | 13        | 1.84%   |
| 5.4.38-gentoo            | 11        | 1.55%   |
| 5.4.80-gentoo-r1         | 9         | 1.27%   |
| 5.4.48-gentoo            | 9         | 1.27%   |
| 5.15.32-gentoo-r1        | 9         | 1.27%   |
| 5.10.76-gentoo-r1        | 8         | 1.13%   |
| 5.10.76-gentoo-r1-x86_64 | 7         | 0.99%   |
| 5.15.59-gentoo-x86_64    | 6         | 0.85%   |
| 5.10.52-gentoo           | 6         | 0.85%   |
| 5.10.27-gentoo-x86_64    | 6         | 0.85%   |
| 5.4.97-gentoo            | 5         | 0.71%   |
| 5.4.60-gentoo            | 5         | 0.71%   |
| 5.4.28-gentoo            | 5         | 0.71%   |
| 5.15.52-gentoo           | 5         | 0.71%   |
| 5.15.32-gentoo-r1-x86_64 | 5         | 0.71%   |
| 5.10.61-gentoo-x86_64    | 5         | 0.71%   |
| 5.8.0-gentoo-r1          | 4         | 0.56%   |
| 5.4.97-gentoo-x86_64     | 4         | 0.56%   |
| 5.4.48-gentoo-x86_64     | 4         | 0.56%   |
| 5.19.0-gentoo-x86_64     | 4         | 0.56%   |
| 5.15.72-gentoo-x86_64    | 4         | 0.56%   |
| 5.15.72-gentoo           | 4         | 0.56%   |
| 5.15.69-gentoo           | 4         | 0.56%   |
| 4.19.97-gentoo           | 4         | 0.56%   |
| 4.14.65-gentoo           | 4         | 0.56%   |
| 5.4.66-gentoo            | 3         | 0.42%   |
| 5.4.38-gentoo-x86_64     | 3         | 0.42%   |
| 5.17.3-gentoo            | 3         | 0.42%   |
| 5.17.1-gentoo-r1         | 3         | 0.42%   |
| 5.15.74-gentoo           | 3         | 0.42%   |
| 5.15.59-gentoo           | 3         | 0.42%   |
| 5.15.52-gentoo-x86_64    | 3         | 0.42%   |
| 5.15.5-gentoo            | 3         | 0.42%   |
| 5.15.41-gentoo-x86_64    | 3         | 0.42%   |
| 5.15.26-gentoo-x86_64    | 3         | 0.42%   |
| 5.15.26-gentoo           | 3         | 0.42%   |
| 5.15.23-gentoo-x86_64    | 3         | 0.42%   |
| 5.15.16-gentoo           | 3         | 0.42%   |
| 5.15.13-gentoo           | 3         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 3.54%   |
| 5.4.48  | 20        | 2.83%   |
| 5.10.76 | 20        | 2.83%   |
| 5.10.61 | 19        | 2.69%   |
| 5.15.32 | 17        | 2.41%   |
| 5.4.38  | 16        | 2.27%   |
| 5.15.59 | 12        | 1.7%    |
| 5.4.97  | 11        | 1.56%   |
| 5.4.80  | 11        | 1.56%   |
| 5.4.28  | 11        | 1.56%   |
| 5.15.52 | 11        | 1.56%   |
| 5.15.72 | 10        | 1.42%   |
| 5.10.52 | 10        | 1.42%   |
| 5.15.11 | 9         | 1.27%   |
| 5.15.69 | 8         | 1.13%   |
| 4.19.97 | 8         | 1.13%   |
| 5.4.72  | 7         | 0.99%   |
| 5.4.60  | 7         | 0.99%   |
| 5.19.0  | 7         | 0.99%   |
| 5.17.1  | 7         | 0.99%   |
| 5.16.0  | 7         | 0.99%   |
| 5.15.41 | 7         | 0.99%   |
| 6.0.0   | 6         | 0.85%   |
| 5.4.66  | 6         | 0.85%   |
| 5.15.26 | 6         | 0.85%   |
| 5.15.23 | 6         | 0.85%   |
| 5.15.10 | 6         | 0.85%   |
| 5.8.0   | 5         | 0.71%   |
| 5.15.5  | 5         | 0.71%   |
| 5.15.13 | 5         | 0.71%   |
| 5.14.9  | 5         | 0.71%   |
| 5.11.0  | 5         | 0.71%   |
| 5.10.4  | 5         | 0.71%   |
| 4.19.57 | 5         | 0.71%   |
| 5.9.1   | 4         | 0.57%   |
| 5.9.0   | 4         | 0.57%   |
| 5.6.15  | 4         | 0.57%   |
| 5.4.92  | 4         | 0.57%   |
| 5.18.1  | 4         | 0.57%   |
| 5.16.10 | 4         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 125       | 19%     |
| 5.10    | 108       | 16.41%  |
| 5.4     | 102       | 15.5%   |
| 4.19    | 33        | 5.02%   |
| 5.17    | 25        | 3.8%    |
| 5.9     | 23        | 3.5%    |
| 5.16    | 23        | 3.5%    |
| 5.6     | 22        | 3.34%   |
| 5.14    | 21        | 3.19%   |
| 5.8     | 19        | 2.89%   |
| 5.18    | 19        | 2.89%   |
| 5.11    | 19        | 2.89%   |
| 5.12    | 17        | 2.58%   |
| 5.7     | 16        | 2.43%   |
| 5.19    | 15        | 2.28%   |
| 5.13    | 13        | 1.98%   |
| 6.0     | 9         | 1.37%   |
| 4.14    | 8         | 1.22%   |
| 5.5     | 7         | 1.06%   |
| 5.3     | 5         | 0.76%   |
| 5.1     | 5         | 0.76%   |
| 4.4     | 5         | 0.76%   |
| 5.2     | 3         | 0.46%   |
| 4.9     | 3         | 0.46%   |
| 4.18    | 3         | 0.46%   |
| 5.0     | 2         | 0.3%    |
| 4.6     | 2         | 0.3%    |
| 4.12    | 2         | 0.3%    |
| 4.5     | 1         | 0.15%   |
| 4.20    | 1         | 0.15%   |
| 4.10    | 1         | 0.15%   |
| 4.1     | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 534       | 96.22%  |
| i686   | 18        | 3.24%   |
| ppc    | 3         | 0.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 266       | 45.24%  |
| KDE5           | 112       | 19.05%  |
| GNOME          | 77        | 13.1%   |
| XFCE           | 44        | 7.48%   |
| KDE            | 24        | 4.08%   |
| MATE           | 13        | 2.21%   |
| dwm            | 9         | 1.53%   |
| LXQt           | 8         | 1.36%   |
| Sway           | 6         | 1.02%   |
| LXDE           | 5         | 0.85%   |
| Xsession       | 4         | 0.68%   |
| openbox        | 3         | 0.51%   |
| X-Cinnamon     | 2         | 0.34%   |
| Cinnamon       | 2         | 0.34%   |
| bspwm          | 2         | 0.34%   |
| awesome        | 2         | 0.34%   |
| xmonad         | 1         | 0.17%   |
| qt5ct          | 1         | 0.17%   |
| LeftWM         | 1         | 0.17%   |
| i3-with-shmlog | 1         | 0.17%   |
| i3             | 1         | 0.17%   |
| GNOME Classic  | 1         | 0.17%   |
| fvwm           | 1         | 0.17%   |
| fluxbox        | 1         | 0.17%   |
| Enlightenment  | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 344       | 58.21%  |
| Unknown | 90        | 15.23%  |
| Tty     | 84        | 14.21%  |
| Wayland | 73        | 12.35%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 290       | 49.91%  |
| SDDM    | 143       | 24.61%  |
| LightDM | 61        | 10.5%   |
| GDM     | 56        | 9.64%   |
| XDM     | 12        | 2.07%   |
| SLiM    | 8         | 1.38%   |
| LXDM    | 6         | 1.03%   |
| GREETD  | 2         | 0.34%   |
| TDM     | 1         | 0.17%   |
| KDM     | 1         | 0.17%   |
| GDM3    | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 223       | 37.93%  |
| Unknown    | 98        | 16.67%  |
| C.UTF8     | 51        | 8.67%   |
| de_DE      | 33        | 5.61%   |
| en_GB      | 32        | 5.44%   |
| ru_RU      | 24        | 4.08%   |
| fr_FR      | 12        | 2.04%   |
| C          | 12        | 2.04%   |
| it_IT      | 10        | 1.7%    |
| en_AU      | 10        | 1.7%    |
| zh_CN      | 7         | 1.19%   |
| es_ES      | 7         | 1.19%   |
| en_CA      | 6         | 1.02%   |
| POSIX      | 5         | 0.85%   |
| el_GR      | 5         | 0.85%   |
| pt_BR      | 4         | 0.68%   |
| pl_PL      | 4         | 0.68%   |
| nl_NL      | 3         | 0.51%   |
| nl_BE      | 3         | 0.51%   |
| cs_CZ      | 3         | 0.51%   |
| uk_UA      | 2         | 0.34%   |
| ja_JP      | 2         | 0.34%   |
| fr_CA      | 2         | 0.34%   |
| es_CL      | 2         | 0.34%   |
| es_AR      | 2         | 0.34%   |
| en_ZA      | 2         | 0.34%   |
| en_US.UTF8 | 2         | 0.34%   |
| en_MX      | 2         | 0.34%   |
| en_IE      | 2         | 0.34%   |
| de_CH      | 2         | 0.34%   |
| ca_ES      | 2         | 0.34%   |
| zh_TW      | 1         | 0.17%   |
| tr_TR.UTF8 | 1         | 0.17%   |
| tr_TR      | 1         | 0.17%   |
| sv_SE      | 1         | 0.17%   |
| ru_UA      | 1         | 0.17%   |
| lt_LT      | 1         | 0.17%   |
| ko_KR      | 1         | 0.17%   |
| fr_BE      | 1         | 0.17%   |
| es_MX      | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 433       | 76.37%  |
| BIOS | 134       | 23.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 342       | 60.64%  |
| Btrfs    | 129       | 22.87%  |
| Unknown  | 23        | 4.08%   |
| Xfs      | 22        | 3.9%    |
| Zfs      | 16        | 2.84%   |
| F2fs     | 15        | 2.66%   |
| XXXXXXX  | 9         | 1.6%    |
| Reiserfs | 2         | 0.35%   |
| Ext3     | 2         | 0.35%   |
| Overlay  | 1         | 0.18%   |
| Jfs      | 1         | 0.18%   |
| Ext2     | 1         | 0.18%   |
| Bcachefs | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 470       | 83.48%  |
| MBR     | 58        | 10.3%   |
| Unknown | 35        | 6.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 422       | 74.3%   |
| Yes       | 146       | 25.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 397       | 69.89%  |
| Yes       | 171       | 30.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 162       | 29.19%  |
| Dell                           | 98        | 17.66%  |
| Hewlett-Packard                | 81        | 14.59%  |
| ASUSTek Computer               | 58        | 10.45%  |
| Acer                           | 30        | 5.41%   |
| MSI                            | 15        | 2.7%    |
| Apple                          | 15        | 2.7%    |
| Timi                           | 10        | 1.8%    |
| HUAWEI                         | 9         | 1.62%   |
| Samsung Electronics            | 8         | 1.44%   |
| TUXEDO                         | 7         | 1.26%   |
| Toshiba                        | 7         | 1.26%   |
| Razer                          | 4         | 0.72%   |
| Notebook                       | 4         | 0.72%   |
| IBM                            | 4         | 0.72%   |
| Unknown                        | 4         | 0.72%   |
| System76                       | 3         | 0.54%   |
| Fujitsu                        | 3         | 0.54%   |
| win element                    | 2         | 0.36%   |
| Sony                           | 2         | 0.36%   |
| Purism                         | 2         | 0.36%   |
| Positivo                       | 2         | 0.36%   |
| Medion                         | 2         | 0.36%   |
| Framework                      | 2         | 0.36%   |
| Chuwi                          | 2         | 0.36%   |
| XMG                            | 1         | 0.18%   |
| Wortmann AG                    | 1         | 0.18%   |
| Valve                          | 1         | 0.18%   |
| SIEMENS                        | 1         | 0.18%   |
| Seco                           | 1         | 0.18%   |
| Schenker                       | 1         | 0.18%   |
| PC Specialist                  | 1         | 0.18%   |
| MOTILE                         | 1         | 0.18%   |
| Matsushita Electric Industrial | 1         | 0.18%   |
| LG Electronics                 | 1         | 0.18%   |
| Jumper                         | 1         | 0.18%   |
| IT Channel Pty                 | 1         | 0.18%   |
| Intel Client Systems           | 1         | 0.18%   |
| Google                         | 1         | 0.18%   |
| Gigabyte Technology            | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 11        | 1.98%   |
| HP Pavilion Notebook                 | 5         | 0.9%    |
| Dell XPS 15 9570                     | 5         | 0.9%    |
| HP OMEN by Laptop                    | 4         | 0.72%   |
| HP Laptop 14-dk1xxx                  | 4         | 0.72%   |
| Dell XPS 17 9710                     | 4         | 0.72%   |
| Dell XPS 13 9310                     | 4         | 0.72%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE | 3         | 0.54%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.54%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 3         | 0.54%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 3         | 0.54%   |
| Dell XPS 15 7590                     | 3         | 0.54%   |
| Dell XPS 13 9370                     | 3         | 0.54%   |
| Dell XPS 13 9360                     | 3         | 0.54%   |
| Dell Latitude E7440                  | 3         | 0.54%   |
| Dell Latitude 7390                   | 3         | 0.54%   |
| ASUS ROG Strix G513QY_G513QY         | 3         | 0.54%   |
| win element MoreFine S500+           | 2         | 0.36%   |
| Toshiba Satellite C850D-118          | 2         | 0.36%   |
| Toshiba NB100                        | 2         | 0.36%   |
| Timi RedmiBook 13 R                  | 2         | 0.36%   |
| MSI GS63VR 6RF                       | 2         | 0.36%   |
| Lenovo ThinkPad T480 20L5CTO1WW      | 2         | 0.36%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB | 2         | 0.36%   |
| Lenovo Legion Y540-15IRH 81SX        | 2         | 0.36%   |
| Lenovo Legion R7000 2020 82B6        | 2         | 0.36%   |
| Lenovo IdeaPad 5 15ITL05 82FG        | 2         | 0.36%   |
| HUAWEI BOHK-WAX9X                    | 2         | 0.36%   |
| HP ProBook 455 G7                    | 2         | 0.36%   |
| HP Pavilion dv7                      | 2         | 0.36%   |
| HP Laptop 15s-eq0xxx                 | 2         | 0.36%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.36%   |
| HP EliteBook 840 G7 Notebook PC      | 2         | 0.36%   |
| Framework Laptop                     | 2         | 0.36%   |
| Dell XPS 13 9380                     | 2         | 0.36%   |
| Dell Precision 7560                  | 2         | 0.36%   |
| Dell Latitude E6530                  | 2         | 0.36%   |
| Dell Latitude E6430                  | 2         | 0.36%   |
| Dell Latitude 5480                   | 2         | 0.36%   |
| Dell Inspiron 5577                   | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 96        | 17.3%   |
| Dell Latitude        | 36        | 6.49%   |
| Dell XPS             | 29        | 5.23%   |
| Lenovo Legion        | 22        | 3.96%   |
| Lenovo IdeaPad       | 21        | 3.78%   |
| HP Pavilion          | 18        | 3.24%   |
| HP EliteBook         | 17        | 3.06%   |
| Acer Aspire          | 17        | 3.06%   |
| HP Laptop            | 14        | 2.52%   |
| Dell Inspiron        | 14        | 2.52%   |
| Unknown              | 11        | 1.98%   |
| HP OMEN              | 10        | 1.8%    |
| ASUS ROG             | 10        | 1.8%    |
| HP ProBook           | 9         | 1.62%   |
| Dell Precision       | 9         | 1.62%   |
| ASUS ZenBook         | 8         | 1.44%   |
| Lenovo Yoga          | 6         | 1.08%   |
| ASUS VivoBook        | 6         | 1.08%   |
| Toshiba Satellite    | 5         | 0.9%    |
| Timi RedmiBook       | 5         | 0.9%    |
| HP ZBook             | 5         | 0.9%    |
| Apple MacBookPro8    | 5         | 0.9%    |
| Acer Swift           | 5         | 0.9%    |
| Acer Nitro           | 5         | 0.9%    |
| Razer Blade          | 4         | 0.72%   |
| Lenovo ThinkBook     | 4         | 0.72%   |
| Timi Mi              | 3         | 0.54%   |
| IBM ThinkPad         | 3         | 0.54%   |
| Fujitsu LIFEBOOK     | 3         | 0.54%   |
| Dell Vostro          | 3         | 0.54%   |
| Dell G3              | 3         | 0.54%   |
| ASUS ASUS            | 3         | 0.54%   |
| win element MoreFine | 2         | 0.36%   |
| TUXEDO Book          | 2         | 0.36%   |
| Toshiba NB100        | 2         | 0.36%   |
| System76 Gazelle     | 2         | 0.36%   |
| Purism Librem        | 2         | 0.36%   |
| MSI GS63VR           | 2         | 0.36%   |
| MSI GF63             | 2         | 0.36%   |
| HUAWEI BOHK-WAX9X    | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 101       | 18.2%   |
| 2019    | 93        | 16.76%  |
| 2021    | 66        | 11.89%  |
| 2018    | 64        | 11.53%  |
| 2017    | 31        | 5.59%   |
| 2014    | 29        | 5.23%   |
| 2015    | 25        | 4.5%    |
| 2012    | 25        | 4.5%    |
| 2016    | 24        | 4.32%   |
| 2011    | 23        | 4.14%   |
| 2022    | 14        | 2.52%   |
| 2013    | 14        | 2.52%   |
| 2008    | 12        | 2.16%   |
| 2010    | 11        | 1.98%   |
| 2006    | 6         | 1.08%   |
| 2009    | 4         | 0.72%   |
| Unknown | 4         | 0.72%   |
| 2007    | 3         | 0.54%   |
| 2005    | 3         | 0.54%   |
| 2004    | 2         | 0.36%   |
| 2003    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 555       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 544       | 97.67%  |
| Enabled  | 13        | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 549       | 98.92%  |
| Yes  | 6         | 1.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 140       | 24.69%  |
| 8.01-16.0   | 126       | 22.22%  |
| 4.01-8.0    | 107       | 18.87%  |
| 32.01-64.0  | 83        | 14.64%  |
| 3.01-4.0    | 35        | 6.17%   |
| 64.01-256.0 | 23        | 4.06%   |
| 24.01-32.0  | 18        | 3.17%   |
| 1.01-2.0    | 14        | 2.47%   |
| 2.01-3.0    | 12        | 2.12%   |
| 0.51-1.0    | 7         | 1.23%   |
| 0.01-0.5    | 2         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 167       | 25.85%  |
| 2.01-3.0   | 106       | 16.41%  |
| 4.01-8.0   | 105       | 16.25%  |
| 3.01-4.0   | 81        | 12.54%  |
| 0.01-0.5   | 67        | 10.37%  |
| 0.51-1.0   | 63        | 9.75%   |
| 8.01-16.0  | 51        | 7.89%   |
| 16.01-24.0 | 4         | 0.62%   |
| 32.01-64.0 | 1         | 0.15%   |
| 24.01-32.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 391       | 68.48%  |
| 2      | 151       | 26.44%  |
| 3      | 21        | 3.68%   |
| 0      | 6         | 1.05%   |
| 4      | 2         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 469       | 83.6%   |
| Yes       | 92        | 16.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 436       | 77.72%  |
| No        | 125       | 22.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 548       | 98.74%  |
| No        | 7         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 482       | 85.77%  |
| No        | 80        | 14.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 98        | 17.5%   |
| Germany      | 79        | 14.11%  |
| Russia       | 47        | 8.39%   |
| France       | 28        | 5%      |
| China        | 28        | 5%      |
| UK           | 22        | 3.93%   |
| Canada       | 18        | 3.21%   |
| Poland       | 17        | 3.04%   |
| Italy        | 17        | 3.04%   |
| Netherlands  | 15        | 2.68%   |
| Australia    | 14        | 2.5%    |
| Spain        | 13        | 2.32%   |
| Czechia      | 13        | 2.32%   |
| Ukraine      | 11        | 1.96%   |
| Sweden       | 10        | 1.79%   |
| Greece       | 10        | 1.79%   |
| Turkey       | 9         | 1.61%   |
| Belgium      | 8         | 1.43%   |
| Switzerland  | 7         | 1.25%   |
| Brazil       | 7         | 1.25%   |
| Mexico       | 6         | 1.07%   |
| India        | 6         | 1.07%   |
| Finland      | 6         | 1.07%   |
| Norway       | 5         | 0.89%   |
| Japan        | 5         | 0.89%   |
| Hong Kong    | 5         | 0.89%   |
| Belarus      | 5         | 0.89%   |
| Austria      | 5         | 0.89%   |
| Romania      | 4         | 0.71%   |
| Portugal     | 4         | 0.71%   |
| South Africa | 3         | 0.54%   |
| Argentina    | 3         | 0.54%   |
| Vietnam      | 2         | 0.36%   |
| Taiwan       | 2         | 0.36%   |
| Slovenia     | 2         | 0.36%   |
| Slovakia     | 2         | 0.36%   |
| Singapore    | 2         | 0.36%   |
| New Zealand  | 2         | 0.36%   |
| Iran         | 2         | 0.36%   |
| Indonesia    | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 23        | 3.79%   |
| Moscow            | 19        | 3.13%   |
| Athens            | 10        | 1.65%   |
| Sydney            | 9         | 1.48%   |
| St Petersburg     | 8         | 1.32%   |
| Munich            | 7         | 1.15%   |
| Prague            | 6         | 0.99%   |
| Kyiv              | 6         | 0.99%   |
| Guangzhou         | 6         | 0.99%   |
| Weatherford       | 5         | 0.82%   |
| Warsaw            | 5         | 0.82%   |
| Paris             | 5         | 0.82%   |
| Minsk             | 5         | 0.82%   |
| Amsterdam         | 5         | 0.82%   |
| Vancouver         | 4         | 0.66%   |
| Milan             | 4         | 0.66%   |
| Los Angeles       | 4         | 0.66%   |
| Istanbul          | 4         | 0.66%   |
| Cieszyn           | 4         | 0.66%   |
| Beijing           | 4         | 0.66%   |
| Wuelfrath         | 3         | 0.49%   |
| Vienna            | 3         | 0.49%   |
| Shenzhen          | 3         | 0.49%   |
| San Jose          | 3         | 0.49%   |
| New York          | 3         | 0.49%   |
| Melbourne         | 3         | 0.49%   |
| Manitowoc         | 3         | 0.49%   |
| London            | 3         | 0.49%   |
| Helsinki          | 3         | 0.49%   |
| Goiânia          | 3         | 0.49%   |
| Frankfurt am Main | 3         | 0.49%   |
| Fort Worth        | 3         | 0.49%   |
| Düsseldorf       | 3         | 0.49%   |
| Chongqing         | 3         | 0.49%   |
| Cape Town         | 3         | 0.49%   |
| Woolwich          | 2         | 0.33%   |
| Winnipeg          | 2         | 0.33%   |
| West Orange       | 2         | 0.33%   |
| Vleuten           | 2         | 0.33%   |
| Vladivostok       | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 176       | 280    | 24.55%  |
| WDC                            | 106       | 142    | 14.78%  |
| Seagate                        | 51        | 68     | 7.11%   |
| SK hynix                       | 49        | 58     | 6.83%   |
| Intel                          | 47        | 71     | 6.56%   |
| Toshiba                        | 42        | 48     | 5.86%   |
| SanDisk                        | 36        | 46     | 5.02%   |
| Kingston                       | 28        | 35     | 3.91%   |
| Unknown                        | 27        | 35     | 3.77%   |
| HGST                           | 25        | 26     | 3.49%   |
| Micron Technology              | 20        | 24     | 2.79%   |
| Crucial                        | 15        | 18     | 2.09%   |
| Hitachi                        | 11        | 11     | 1.53%   |
| KIOXIA                         | 10        | 13     | 1.39%   |
| A-DATA Technology              | 7         | 13     | 0.98%   |
| Apple                          | 6         | 8      | 0.84%   |
| Fujitsu                        | 5         | 7      | 0.7%    |
| LITEON                         | 4         | 7      | 0.56%   |
| Phison                         | 3         | 3      | 0.42%   |
| OCZ                            | 3         | 6      | 0.42%   |
| Lenovo                         | 3         | 5      | 0.42%   |
| China                          | 3         | 5      | 0.42%   |
| Transcend                      | 2         | 5      | 0.28%   |
| Plextor                        | 2         | 2      | 0.28%   |
| Phison Electronics             | 2         | 2      | 0.28%   |
| Netac                          | 2         | 2      | 0.28%   |
| MyDigitalSSD                   | 2         | 2      | 0.28%   |
| LITEONIT                       | 2         | 3      | 0.28%   |
| KIOXIA-EXCERIA                 | 2         | 5      | 0.28%   |
| IBM/Hitachi                    | 2         | 3      | 0.28%   |
| Zheino                         | 1         | 1      | 0.14%   |
| XrayDisk                       | 1         | 1      | 0.14%   |
| XPG                            | 1         | 1      | 0.14%   |
| Union Memory                   | 1         | 1      | 0.14%   |
| UMIS                           | 1         | 1      | 0.14%   |
| T-FORCE                        | 1         | 2      | 0.14%   |
| SPCC                           | 1         | 1      | 0.14%   |
| Solid State Storage Technology | 1         | 1      | 0.14%   |
| ShanDianZhe                    | 1         | 2      | 0.14%   |
| RevuAhn                        | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                             | 16        | 2.09%   |
| Intel SSDPEKNW010T8 1TB                              | 10        | 1.31%   |
| Samsung SSD 850 EVO 250GB                            | 8         | 1.04%   |
| Samsung MZVLB512HBJQ-000L2 512GB                     | 8         | 1.04%   |
| Samsung SSD 980 1TB                                  | 7         | 0.91%   |
| Samsung SSD 860 EVO 500GB                            | 7         | 0.91%   |
| Seagate ST1000LM049-2GH172 1TB                       | 6         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB                       | 6         | 0.78%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 6         | 0.78%   |
| Intel SSDPEKNU512GZ 512GB                            | 6         | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                     | 5         | 0.65%   |
| Unknown MMC Card  16GB                               | 5         | 0.65%   |
| Samsung SSD 980 PRO 2TB                              | 5         | 0.65%   |
| Samsung NVMe SSD Drive 512GB                         | 5         | 0.65%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 4         | 0.52%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                 | 4         | 0.52%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                   | 4         | 0.52%   |
| Toshiba MQ04ABF100 1TB                               | 4         | 0.52%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.52%   |
| Toshiba KXG50ZNV512G NVMe 512GB                      | 4         | 0.52%   |
| SK hynix PC711 NVMe 1TB                              | 4         | 0.52%   |
| Seagate ST2000LX001-1RG174 2TB                       | 4         | 0.52%   |
| Seagate ST1000LM048-2E7172 1TB                       | 4         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB                       | 4         | 0.52%   |
| Samsung SSD 860 QVO 1TB                              | 4         | 0.52%   |
| Samsung SSD 860 EVO 1TB                              | 4         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 4         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 4         | 0.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 4         | 0.52%   |
| Samsung MZVLB512HAJQ-000L7 512GB                     | 4         | 0.52%   |
| Samsung MZVLB512HAJQ-00000 512GB                     | 4         | 0.52%   |
| Kingston SA400S37480G 480GB SSD                      | 4         | 0.52%   |
| Kingston SA400S37240G 240GB SSD                      | 4         | 0.52%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD              | 4         | 0.52%   |
| Intel SSDPEKKF256G8L 256GB                           | 4         | 0.52%   |
| HGST HTS541010A9E680 1TB                             | 4         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 66     | 32.45%  |
| WDC                 | 39        | 46     | 25.83%  |
| HGST                | 25        | 26     | 16.56%  |
| Toshiba             | 19        | 21     | 12.58%  |
| Hitachi             | 11        | 11     | 7.28%   |
| Fujitsu             | 5         | 7      | 3.31%   |
| IBM/Hitachi         | 2         | 3      | 1.32%   |
| Samsung Electronics | 1         | 2      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 105    | 31.84%  |
| SanDisk             | 23        | 32     | 10.31%  |
| Kingston            | 17        | 24     | 7.62%   |
| WDC                 | 15        | 24     | 6.73%   |
| SK hynix            | 12        | 13     | 5.38%   |
| Intel               | 12        | 12     | 5.38%   |
| Crucial             | 12        | 15     | 5.38%   |
| Micron Technology   | 9         | 12     | 4.04%   |
| A-DATA Technology   | 7         | 13     | 3.14%   |
| Toshiba             | 6         | 7      | 2.69%   |
| Apple               | 4         | 5      | 1.79%   |
| OCZ                 | 3         | 6      | 1.35%   |
| China               | 3         | 5      | 1.35%   |
| Transcend           | 2         | 5      | 0.9%    |
| Plextor             | 2         | 2      | 0.9%    |
| Netac               | 2         | 2      | 0.9%    |
| MyDigitalSSD        | 2         | 2      | 0.9%    |
| LITEONIT            | 2         | 3      | 0.9%    |
| Zheino              | 1         | 1      | 0.45%   |
| XrayDisk            | 1         | 1      | 0.45%   |
| SPCC                | 1         | 1      | 0.45%   |
| ShanDianZhe         | 1         | 2      | 0.45%   |
| Seagate             | 1         | 1      | 0.45%   |
| RevuAhn             | 1         | 1      | 0.45%   |
| Phison              | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 1      | 0.45%   |
| LITEON              | 1         | 2      | 0.45%   |
| Lite-On             | 1         | 1      | 0.45%   |
| Linux               | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 2      | 0.45%   |
| Kingmax             | 1         | 1      | 0.45%   |
| KingDian            | 1         | 1      | 0.45%   |
| Hoodisk             | 1         | 1      | 0.45%   |
| Faspeed             | 1         | 1      | 0.45%   |
| e2e4                | 1         | 1      | 0.45%   |
| BIWIN               | 1         | 1      | 0.45%   |
| ASUS-PHISON         | 1         | 2      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 306       | 451    | 44.87%  |
| SSD     | 203       | 310    | 29.77%  |
| HDD     | 144       | 182    | 21.11%  |
| MMC     | 27        | 33     | 3.96%   |
| Unknown | 2         | 4      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 306       | 451    | 47.44%  |
| SATA | 299       | 478    | 46.36%  |
| MMC  | 27        | 33     | 4.19%   |
| SAS  | 13        | 18     | 2.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 208       | 311    | 59.77%  |
| 0.51-1.0   | 122       | 153    | 35.06%  |
| 1.01-2.0   | 17        | 27     | 4.89%   |
| 4.01-10.0  | 1         | 1      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 156       | 26.31%  |
| 101-250        | 132       | 22.26%  |
| 501-1000       | 106       | 17.88%  |
| 1001-2000      | 59        | 9.95%   |
| 51-100         | 36        | 6.07%   |
| 1-20           | 34        | 5.73%   |
| Unknown        | 32        | 5.4%    |
| 21-50          | 16        | 2.7%    |
| 2001-3000      | 12        | 2.02%   |
| More than 3000 | 10        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 157       | 24.96%  |
| 21-50          | 111       | 17.65%  |
| 101-250        | 95        | 15.1%   |
| 251-500        | 86        | 13.67%  |
| 51-100         | 80        | 12.72%  |
| 501-1000       | 45        | 7.15%   |
| Unknown        | 32        | 5.09%   |
| 1001-2000      | 17        | 2.7%    |
| 2001-3000      | 4         | 0.64%   |
| More than 3000 | 2         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                  | 5         | 6      | 8.33%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD   | 4         | 4      | 6.67%   |
| SK hynix HFS256G39TND-N210A 256GB SSD     | 2         | 2      | 3.33%   |
| Seagate ST2000LX001-1RG174 2TB            | 2         | 2      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3      | 3.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 2         | 2      | 3.33%   |
| Samsung Electronics SSD 850 EVO 1TB       | 2         | 2      | 3.33%   |
| WDC WD1600BEVS-22RST0 160GB               | 1         | 1      | 1.67%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 1.67%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 1.67%   |
| WDC WD10EZEX-08M2NA0 1TB                  | 1         | 2      | 1.67%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD  | 1         | 1      | 1.67%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.67%   |
| Toshiba MK6008GAH 64GB                    | 1         | 2      | 1.67%   |
| Toshiba MK4026GAX 40GB                    | 1         | 1      | 1.67%   |
| Toshiba MK1629GSG 160GB                   | 1         | 1      | 1.67%   |
| SK hynix SH920 mSATA 256GB SSD            | 1         | 1      | 1.67%   |
| SK hynix SC210 mSATA 128GB SSD            | 1         | 1      | 1.67%   |
| Seagate ST9750420AS 752GB                 | 1         | 1      | 1.67%   |
| Seagate ST9100824AS 100GB                 | 1         | 1      | 1.67%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 1.67%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1      | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2      | 1.67%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 1      | 1.67%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1      | 1.67%   |
| SanDisk SD9SN8W 128GB SSD                 | 1         | 1      | 1.67%   |
| SanDisk SD7SB2Q512G1001 512GB SSD         | 1         | 1      | 1.67%   |
| Samsung Electronics SSD SM841 mSATA 512GB | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 870 EVO 2TB       | 1         | 1      | 1.67%   |
| Samsung Electronics HM160HC 160GB         | 1         | 1      | 1.67%   |
| LITEON CV8-8E128-HP 128GB SSD             | 1         | 2      | 1.67%   |
| Intel SSDSCKKF256G8H 256GB                | 1         | 1      | 1.67%   |
| Intel SSDSC2BW480A4 480GB                 | 1         | 1      | 1.67%   |
| Intel SSDSC2BW180A3L 180GB                | 1         | 1      | 1.67%   |
| Intel SSDPEKKF256G8L 256GB                | 1         | 1      | 1.67%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB         | 1         | 1      | 1.67%   |
| Hitachi HTS723225L9SA62 250GB             | 1         | 1      | 1.67%   |
| Hitachi HTS547550A9E384 500GB             | 1         | 1      | 1.67%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 1      | 1.67%   |
| Hitachi HTS542525K9A300 250GB             | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 16.95%  |
| HGST                | 7         | 8      | 11.86%  |
| Toshiba             | 5         | 6      | 8.47%   |
| Samsung Electronics | 5         | 5      | 8.47%   |
| WDC                 | 4         | 5      | 6.78%   |
| SK hynix            | 4         | 4      | 6.78%   |
| SanDisk             | 4         | 5      | 6.78%   |
| Kingston            | 4         | 4      | 6.78%   |
| Intel               | 4         | 4      | 6.78%   |
| Hitachi             | 4         | 4      | 6.78%   |
| Fujitsu             | 3         | 3      | 5.08%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| LITEON              | 1         | 2      | 1.69%   |
| IBM/Hitachi         | 1         | 1      | 1.69%   |
| Crucial             | 1         | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 29.41%  |
| HGST                | 7         | 8      | 20.59%  |
| WDC                 | 4         | 5      | 11.76%  |
| Toshiba             | 4         | 5      | 11.76%  |
| Hitachi             | 4         | 4      | 11.76%  |
| Fujitsu             | 3         | 3      | 8.82%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| IBM/Hitachi         | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 39     | 57.63%  |
| SSD  | 23        | 25     | 38.98%  |
| NVMe | 2         | 2      | 3.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 50%     |
| Hitachi HTS721010G9SA00 100GB    | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 469       | 798    | 76.89%  |
| Detected | 81        | 114    | 13.28%  |
| Malfunc  | 58        | 66     | 9.51%   |
| Failed   | 2         | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 337       | 47.13%  |
| Samsung Electronics              | 122       | 17.06%  |
| AMD                              | 74        | 10.35%  |
| SanDisk                          | 64        | 8.95%   |
| SK hynix                         | 37        | 5.17%   |
| Toshiba America Info Systems     | 20        | 2.8%    |
| Kingston Technology Company      | 12        | 1.68%   |
| Micron Technology                | 11        | 1.54%   |
| KIOXIA                           | 11        | 1.54%   |
| Phison Electronics               | 6         | 0.84%   |
| Micron/Crucial Technology        | 3         | 0.42%   |
| Lite-On Technology               | 3         | 0.42%   |
| Union Memory (Shenzhen)          | 2         | 0.28%   |
| Nvidia                           | 2         | 0.28%   |
| Lenovo                           | 2         | 0.28%   |
| JMicron Technology               | 2         | 0.28%   |
| Apple                            | 2         | 0.28%   |
| Solid State Storage Technology   | 1         | 0.14%   |
| Silicon Motion                   | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Seagate Technology               | 1         | 0.14%   |
| ADATA Technology                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 69        | 9.24%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 68        | 9.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 42        | 5.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 37        | 4.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 26        | 3.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 23        | 3.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 22        | 2.95%   |
| Samsung NVMe SSD Controller 980                                                  | 21        | 2.81%   |
| SK hynix Gold P31 SSD                                                            | 20        | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 2.68%   |
| Intel SSD 660P Series                                                            | 19        | 2.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 2.28%   |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 2.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 2.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 1.87%   |
| Micron Non-Volatile memory controller                                            | 11        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 1.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.47%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 1.2%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 9         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.2%    |
| SanDisk Non-Volatile memory controller                                           | 8         | 1.07%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 8         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 1.07%   |
| SK hynix Non-Volatile memory controller                                          | 7         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.8%    |
| Intel Non-Volatile memory controller                                             | 6         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 0.8%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.67%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 330       | 46.15%  |
| NVMe | 311       | 43.5%   |
| RAID | 41        | 5.73%   |
| IDE  | 33        | 4.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 417       | 75.14%  |
| AMD          | 135       | 24.32%  |
| PowerBook5,6 | 1         | 0.18%   |
| PowerBook5,4 | 1         | 0.18%   |
| PowerBook3,4 | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 20        | 3.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 3.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 2.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 2.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 2.34%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 2.34%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 2.34%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 2.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.98%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.98%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 1.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.44%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 8         | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.26%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 1.08%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 1.08%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 1.08%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 5         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.9%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.9%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.9%    |
| Intel Core i9-9880H CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.72%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.72%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.72%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 4         | 0.72%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 185       | 33.33%  |
| Intel Core i5           | 106       | 19.1%   |
| AMD Ryzen 7             | 53        | 9.55%   |
| Other                   | 52        | 9.37%   |
| AMD Ryzen 5             | 24        | 4.32%   |
| AMD Ryzen 7 PRO         | 19        | 3.42%   |
| Intel Core 2 Duo        | 12        | 2.16%   |
| Intel Celeron           | 12        | 2.16%   |
| Intel Atom              | 10        | 1.8%    |
| AMD Ryzen 9             | 10        | 1.8%    |
| Intel Core i9           | 9         | 1.62%   |
| Intel Pentium M         | 8         | 1.44%   |
| AMD Ryzen 3             | 8         | 1.44%   |
| Intel Pentium           | 7         | 1.26%   |
| Intel Core i3           | 6         | 1.08%   |
| AMD A6                  | 5         | 0.9%    |
| Intel Xeon              | 4         | 0.72%   |
| Intel Core m3           | 3         | 0.54%   |
| AMD Ryzen 5 PRO         | 3         | 0.54%   |
| AMD A8                  | 3         | 0.54%   |
| Intel Genuine           | 2         | 0.36%   |
| AMD E1                  | 2         | 0.36%   |
| Intel Pentium Silver    | 1         | 0.18%   |
| Intel Pentium 4         | 1         | 0.18%   |
| Intel Core Duo          | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| Intel Celeron M         | 1         | 0.18%   |
| AMD Turion II Dual-Core | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD Athlon Neo X2       | 1         | 0.18%   |
| AMD Athlon 64           | 1         | 0.18%   |
| AMD Athlon              | 1         | 0.18%   |
| AMD A12                 | 1         | 0.18%   |
| AMD A10                 | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 221       | 39.82%  |
| 2       | 140       | 25.23%  |
| 8       | 94        | 16.94%  |
| 6       | 70        | 12.61%  |
| 1       | 20        | 3.6%    |
| 14      | 4         | 0.72%   |
| 12      | 4         | 0.72%   |
| Unknown | 2         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 553       | 99.64%  |
| Unknown | 2         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 463       | 83.27%  |
| 1       | 91        | 16.37%  |
| Unknown | 2         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 532       | 95.86%  |
| 32-bit         | 20        | 3.6%    |
| Unknown        | 3         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 11.91%  |
| 0x906ea    | 44        | 7.71%   |
| 0x806ea    | 31        | 5.43%   |
| 0x806ec    | 30        | 5.25%   |
| 0x0a50000c | 26        | 4.55%   |
| 0x206a7    | 22        | 3.85%   |
| 0x806c1    | 21        | 3.68%   |
| 0x08600106 | 21        | 3.68%   |
| 0x506e3    | 19        | 3.33%   |
| 0x306a9    | 19        | 3.33%   |
| 0x806e9    | 18        | 3.15%   |
| 0x806d1    | 16        | 2.8%    |
| 0xa0652    | 15        | 2.63%   |
| 0x40651    | 15        | 2.63%   |
| 0x08108109 | 15        | 2.63%   |
| 0x08600103 | 14        | 2.45%   |
| 0x906e9    | 12        | 2.1%    |
| 0x406e3    | 11        | 1.93%   |
| 0x306d4    | 11        | 1.93%   |
| 0x306c3    | 11        | 1.93%   |
| 0x906ed    | 10        | 1.75%   |
| 0x08108102 | 9         | 1.58%   |
| 0x30678    | 8         | 1.4%    |
| 0x906a3    | 7         | 1.23%   |
| 0x806eb    | 7         | 1.23%   |
| 0x08608103 | 7         | 1.23%   |
| 0x08600104 | 6         | 1.05%   |
| 0x6d8      | 5         | 0.88%   |
| 0x706e5    | 4         | 0.7%    |
| 0x1067a    | 4         | 0.7%    |
| 0x706a1    | 3         | 0.53%   |
| 0x6fb      | 3         | 0.53%   |
| 0x406c4    | 3         | 0.53%   |
| 0x106c2    | 3         | 0.53%   |
| 0x10676    | 3         | 0.53%   |
| 0x0a404102 | 3         | 0.53%   |
| 0x08600102 | 3         | 0.53%   |
| 0x06003106 | 3         | 0.53%   |
| 0x806c2    | 2         | 0.35%   |
| 0x6fd      | 2         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 174       | 31.24%  |
| Zen 2            | 48        | 8.62%   |
| Skylake          | 32        | 5.75%   |
| Haswell          | 29        | 5.21%   |
| Zen 3            | 28        | 5.03%   |
| Zen+             | 25        | 4.49%   |
| TigerLake        | 25        | 4.49%   |
| SandyBridge      | 24        | 4.31%   |
| Unknown          | 22        | 3.95%   |
| Icelake          | 21        | 3.77%   |
| IvyBridge        | 20        | 3.59%   |
| CometLake        | 16        | 2.87%   |
| Silvermont       | 12        | 2.15%   |
| P6               | 12        | 2.15%   |
| Broadwell        | 12        | 2.15%   |
| Penryn           | 7         | 1.26%   |
| Alderlake Hybrid | 7         | 1.26%   |
| Westmere         | 6         | 1.08%   |
| Core             | 6         | 1.08%   |
| Bonnell          | 6         | 1.08%   |
| Zen              | 4         | 0.72%   |
| Goldmont plus    | 4         | 0.72%   |
| Steamroller      | 3         | 0.54%   |
| Bobcat           | 3         | 0.54%   |
| Puma             | 2         | 0.36%   |
| K8 Hammer        | 2         | 0.36%   |
| K10 Llano        | 2         | 0.36%   |
| Excavator        | 2         | 0.36%   |
| NetBurst         | 1         | 0.18%   |
| Jaguar           | 1         | 0.18%   |
| Goldmont         | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 375       | 50.74%  |
| Nvidia | 214       | 28.96%  |
| AMD    | 150       | 20.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 51        | 6.7%    |
| AMD Renoir                                                                    | 44        | 5.78%   |
| Intel UHD Graphics 620                                                        | 37        | 4.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 25        | 3.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 25        | 3.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 24        | 3.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 23        | 3.02%   |
| AMD Cezanne                                                                   | 23        | 3.02%   |
| Intel HD Graphics 530                                                         | 19        | 2.5%    |
| Intel HD Graphics 620                                                         | 17        | 2.23%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 17        | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 16        | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 16        | 2.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 14        | 1.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 14        | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 13        | 1.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 12        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 12        | 1.58%   |
| Intel HD Graphics 5500                                                        | 11        | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 11        | 1.45%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 10        | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 10        | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 10        | 1.31%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 9         | 1.18%   |
| Intel HD Graphics 630                                                         | 9         | 1.18%   |
| Nvidia GP108M [GeForce MX150]                                                 | 8         | 1.05%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 8         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 8         | 1.05%   |
| AMD Lucienne                                                                  | 8         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 7         | 0.92%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 7         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 6         | 0.79%   |
| Nvidia TU117M                                                                 | 6         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 6         | 0.79%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 0.66%   |
| AMD Rembrandt [Radeon 680M]                                                   | 5         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 4         | 0.53%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 4         | 0.53%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 4         | 0.53%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 4         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 202       | 36.14%  |
| Intel + Nvidia | 153       | 27.37%  |
| 1 x AMD        | 109       | 19.5%   |
| 1 x Nvidia     | 45        | 8.05%   |
| AMD + Nvidia   | 17        | 3.04%   |
| Intel + AMD    | 13        | 2.33%   |
| 2 x AMD        | 12        | 2.15%   |
| 2 x Intel      | 7         | 1.25%   |
| 2 x Nvidia     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 441       | 77.1%   |
| Proprietary | 111       | 19.41%  |
| Unknown     | 20        | 3.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 56.64%  |
| 0.01-0.5   | 83        | 14.51%  |
| 1.01-2.0   | 58        | 10.14%  |
| 3.01-4.0   | 47        | 8.22%   |
| 0.51-1.0   | 20        | 3.5%    |
| 5.01-6.0   | 18        | 3.15%   |
| 7.01-8.0   | 12        | 2.1%    |
| 8.01-16.0  | 7         | 1.22%   |
| 2.01-3.0   | 3         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 121       | 18.25%  |
| BOE                     | 95        | 14.33%  |
| LG Display              | 89        | 13.42%  |
| Chimei Innolux          | 73        | 11.01%  |
| Samsung Electronics     | 57        | 8.6%    |
| Sharp                   | 41        | 6.18%   |
| Dell                    | 32        | 4.83%   |
| Apple                   | 18        | 2.71%   |
| Lenovo                  | 15        | 2.26%   |
| Chi Mei Optoelectronics | 13        | 1.96%   |
| Hewlett-Packard         | 10        | 1.51%   |
| Goldstar                | 8         | 1.21%   |
| CSO                     | 8         | 1.21%   |
| PANDA                   | 7         | 1.06%   |
| InfoVision              | 6         | 0.9%    |
| BenQ                    | 6         | 0.9%    |
| AOC                     | 6         | 0.9%    |
| Acer                    | 6         | 0.9%    |
| Iiyama                  | 5         | 0.75%   |
| Ancor Communications    | 5         | 0.75%   |
| Philips                 | 4         | 0.6%    |
| ViewSonic               | 3         | 0.45%   |
| Eizo                    | 3         | 0.45%   |
| ASUSTek Computer        | 3         | 0.45%   |
| Sony                    | 2         | 0.3%    |
| MSI                     | 2         | 0.3%    |
| LGD                     | 2         | 0.3%    |
| LG Philips              | 2         | 0.3%    |
| HannStar                | 2         | 0.3%    |
| Gigabyte Technology     | 2         | 0.3%    |
| Fujitsu Siemens         | 2         | 0.3%    |
| CMN                     | 2         | 0.3%    |
| Xiaomi                  | 1         | 0.15%   |
| WST                     | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| TMX                     | 1         | 0.15%   |
| RTK                     | 1         | 0.15%   |
| QBell                   | 1         | 0.15%   |
| Mi                      | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 1.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 7         | 1.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.75%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.45%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 3         | 0.45%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 3         | 0.45%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.45%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.45%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.45%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                     | 3         | 0.45%   |
| Dell U2414H DELA0A3 1920x1080 530x300mm 24.0-inch                     | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.45%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 3         | 0.45%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                 | 3         | 0.45%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.45%   |
| BOE LCD Monitor BOE082B 1920x1080 309x174mm 14.0-inch                 | 3         | 0.45%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 3         | 0.45%   |
| Apple Color LCD APP9C20 1280x854 321x214mm 15.2-inch                  | 3         | 0.45%   |
| Acer T232HL ACR041F 1920x1080 509x286mm 23.0-inch                     | 3         | 0.45%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 2         | 0.3%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.3%    |
| Samsung Electronics U28E570 SAM0D71 3840x2160 608x345mm 27.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 335       | 54.29%  |
| 1366x768 (WXGA)    | 69        | 11.18%  |
| 3840x2160 (4K)     | 36        | 5.83%   |
| 2560x1440 (QHD)    | 33        | 5.35%   |
| 1600x900 (HD+)     | 18        | 2.92%   |
| 3840x2400          | 14        | 2.27%   |
| 1920x1200 (WUXGA)  | 14        | 2.27%   |
| 2560x1600          | 13        | 2.11%   |
| 1280x800 (WXGA)    | 11        | 1.78%   |
| 1440x900 (WXGA+)   | 10        | 1.62%   |
| 1680x1050 (WSXGA+) | 9         | 1.46%   |
| 3440x1440          | 7         | 1.13%   |
| 1024x600           | 6         | 0.97%   |
| 2880x1800          | 5         | 0.81%   |
| 1280x1024 (SXGA)   | 4         | 0.65%   |
| 3200x1800 (QHD+)   | 3         | 0.49%   |
| 2160x1440          | 3         | 0.49%   |
| 1280x854           | 3         | 0.49%   |
| 3840x1080          | 2         | 0.32%   |
| 2256x1504          | 2         | 0.32%   |
| 2048x1152          | 2         | 0.32%   |
| Unknown            | 2         | 0.32%   |
| 800x1280           | 1         | 0.16%   |
| 5040x1080          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3840x1100          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3200x2000          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2520x1680          | 1         | 0.16%   |
| 2304x1440          | 1         | 0.16%   |
| 2288x1287          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x768           | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 247       | 37.54%  |
| 13      | 99        | 15.05%  |
| 14      | 74        | 11.25%  |
| 17      | 45        | 6.84%   |
| 27      | 34        | 5.17%   |
| 24      | 26        | 3.95%   |
| 12      | 26        | 3.95%   |
| 23      | 20        | 3.04%   |
| 16      | 14        | 2.13%   |
| 21      | 10        | 1.52%   |
| 11      | 10        | 1.52%   |
| Unknown | 8         | 1.22%   |
| 34      | 7         | 1.06%   |
| 22      | 5         | 0.76%   |
| 19      | 5         | 0.76%   |
| 10      | 4         | 0.61%   |
| 31      | 3         | 0.46%   |
| 25      | 3         | 0.46%   |
| 18      | 3         | 0.46%   |
| 40      | 2         | 0.3%    |
| 8       | 2         | 0.3%    |
| 142     | 1         | 0.15%   |
| 75      | 1         | 0.15%   |
| 72      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 54      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 43      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 373       | 57.38%  |
| 201-300        | 93        | 14.31%  |
| 501-600        | 76        | 11.69%  |
| 351-400        | 50        | 7.69%   |
| 401-500        | 24        | 3.69%   |
| Unknown        | 8         | 1.23%   |
| 701-800        | 7         | 1.08%   |
| 601-700        | 7         | 1.08%   |
| 1001-1500      | 4         | 0.62%   |
| 801-900        | 3         | 0.46%   |
| 1501-2000      | 2         | 0.31%   |
| 101-200        | 2         | 0.31%   |
| More than 2000 | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 458       | 79.38%  |
| 16/10   | 80        | 13.86%  |
| 3/2     | 14        | 2.43%   |
| 21/9    | 7         | 1.21%   |
| Unknown | 6         | 1.04%   |
| 4/3     | 4         | 0.69%   |
| 5/4     | 3         | 0.52%   |
| 32/9    | 1         | 0.17%   |
| 3.40    | 1         | 0.17%   |
| 3.20    | 1         | 0.17%   |
| 1.00    | 1         | 0.17%   |
| 0.62    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 245       | 37.23%  |
| 81-90          | 125       | 19%     |
| 71-80          | 48        | 7.29%   |
| 201-250        | 46        | 6.99%   |
| 121-130        | 40        | 6.08%   |
| 301-350        | 35        | 5.32%   |
| 61-70          | 24        | 3.65%   |
| 111-120        | 15        | 2.28%   |
| 251-300        | 14        | 2.13%   |
| 51-60          | 11        | 1.67%   |
| 351-500        | 11        | 1.67%   |
| 151-200        | 8         | 1.22%   |
| Unknown        | 8         | 1.22%   |
| More than 1000 | 5         | 0.76%   |
| 501-1000       | 5         | 0.76%   |
| 41-50          | 4         | 0.61%   |
| 141-150        | 4         | 0.61%   |
| 131-140        | 4         | 0.61%   |
| 91-100         | 4         | 0.61%   |
| 1-40           | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 313       | 48.45%  |
| 101-120       | 101       | 15.63%  |
| 51-100        | 94        | 14.55%  |
| 161-240       | 80        | 12.38%  |
| More than 240 | 46        | 7.12%   |
| Unknown       | 8         | 1.24%   |
| 1-50          | 4         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 439       | 75.69%  |
| 2     | 106       | 18.28%  |
| 0     | 21        | 3.62%   |
| 3     | 14        | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 370       | 42.53%  |
| Realtek Semiconductor             | 270       | 31.03%  |
| Qualcomm Atheros                  | 84        | 9.66%   |
| Broadcom                          | 31        | 3.56%   |
| MediaTek                          | 13        | 1.49%   |
| Lenovo                            | 12        | 1.38%   |
| Marvell Technology Group          | 9         | 1.03%   |
| ASIX Electronics                  | 9         | 1.03%   |
| Dell                              | 8         | 0.92%   |
| Sierra Wireless                   | 6         | 0.69%   |
| Qualcomm                          | 6         | 0.69%   |
| Ericsson Business Mobile Networks | 5         | 0.57%   |
| Apple                             | 5         | 0.57%   |
| Samsung Electronics               | 4         | 0.46%   |
| Fibocom                           | 4         | 0.46%   |
| Broadcom Limited                  | 4         | 0.46%   |
| TP-Link                           | 3         | 0.34%   |
| Qualcomm Atheros Communications   | 3         | 0.34%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.23%   |
| Xiaomi                            | 2         | 0.23%   |
| Ralink Technology                 | 2         | 0.23%   |
| Ralink                            | 2         | 0.23%   |
| D-Link System                     | 2         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.11%   |
| Shenzhen Goodix Technology        | 1         | 0.11%   |
| Prusa                             | 1         | 0.11%   |
| Nvidia                            | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Google                            | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |
| BUFFALO                           | 1         | 0.11%   |
| Aquantia                          | 1         | 0.11%   |
| AMD                               | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 188       | 17.62%  |
| Intel Wi-Fi 6 AX200                                                     | 67        | 6.28%   |
| Intel Wireless 8265 / 8275                                              | 44        | 4.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 3.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 31        | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 20        | 1.87%   |
| Intel Wireless 7265                                                     | 20        | 1.87%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.59%   |
| Intel Wireless 7260                                                     | 16        | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                   | 16        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.41%   |
| Intel Wireless 8260                                                     | 14        | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.22%   |
| Intel Wireless 3165                                                     | 12        | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                    | 12        | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 11        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 10        | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                    | 10        | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 9         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                   | 8         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.66%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                   | 7         | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 361       | 62.56%  |
| Realtek Semiconductor           | 73        | 12.65%  |
| Qualcomm Atheros                | 67        | 11.61%  |
| Broadcom                        | 26        | 4.51%   |
| MediaTek                        | 12        | 2.08%   |
| Sierra Wireless                 | 6         | 1.04%   |
| Qualcomm                        | 6         | 1.04%   |
| Dell                            | 6         | 1.04%   |
| FIBOCOM                         | 4         | 0.69%   |
| Qualcomm Atheros Communications | 3         | 0.52%   |
| TP-Link                         | 2         | 0.35%   |
| Ralink Technology               | 2         | 0.35%   |
| Ralink                          | 2         | 0.35%   |
| D-Link System                   | 2         | 0.35%   |
| NetGear                         | 1         | 0.17%   |
| Microsoft                       | 1         | 0.17%   |
| D-Link                          | 1         | 0.17%   |
| BUFFALO                         | 1         | 0.17%   |
| Broadcom Limited                | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 67        | 11.57%  |
| Intel Wireless 8265 / 8275                                              | 44        | 7.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 5.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 3.63%   |
| Intel Wireless 7265                                                     | 20        | 3.45%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 3.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 2.94%   |
| Intel Wireless 7260                                                     | 16        | 2.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.59%   |
| Intel Wireless 8260                                                     | 14        | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.42%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 2.25%   |
| Intel Wireless 3165                                                     | 12        | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 11        | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 10        | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.04%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.69%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 3         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.52%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 0.52%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 3         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 243       | 52.83%  |
| Intel                            | 126       | 27.39%  |
| Qualcomm Atheros                 | 25        | 5.43%   |
| Broadcom                         | 13        | 2.83%   |
| Lenovo                           | 12        | 2.61%   |
| Marvell Technology Group         | 9         | 1.96%   |
| ASIX Electronics                 | 9         | 1.96%   |
| Apple                            | 5         | 1.09%   |
| Samsung Electronics              | 3         | 0.65%   |
| Broadcom Limited                 | 3         | 0.65%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.43%   |
| Xiaomi                           | 2         | 0.43%   |
| TP-Link                          | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Nvidia                           | 1         | 0.22%   |
| JMicron Technology               | 1         | 0.22%   |
| ICS Advent                       | 1         | 0.22%   |
| Huawei Technologies              | 1         | 0.22%   |
| Google                           | 1         | 0.22%   |
| Aquantia                         | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 188       | 40.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 6.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 4.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 3.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 3.43%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 2.57%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 2.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.71%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.07%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.86%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.86%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.86%   |
| Intel Ethernet Connection (14) I219-LM                            | 4         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.64%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.43%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.43%   |
| Intel Ethernet Connection (5) I219-V                              | 2         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.43%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.43%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.43%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 548       | 54.53%  |
| Ethernet | 436       | 43.38%  |
| Modem    | 20        | 1.99%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 432       | 70.7%   |
| Ethernet | 179       | 29.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 378       | 67.99%  |
| 1     | 164       | 29.5%   |
| 3     | 12        | 2.16%   |
| 0     | 2         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 495       | 86.69%  |
| Yes  | 76        | 13.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 306       | 63.35%  |
| Realtek Semiconductor           | 44        | 9.11%   |
| Qualcomm Atheros Communications | 20        | 4.14%   |
| Lite-On Technology              | 17        | 3.52%   |
| IMC Networks                    | 16        | 3.31%   |
| Apple                           | 15        | 3.11%   |
| Foxconn / Hon Hai               | 14        | 2.9%    |
| Broadcom                        | 12        | 2.48%   |
| Realtek                         | 7         | 1.45%   |
| Dell                            | 7         | 1.45%   |
| Cambridge Silicon Radio         | 6         | 1.24%   |
| Toshiba                         | 4         | 0.83%   |
| Hewlett-Packard                 | 4         | 0.83%   |
| ASUSTek Computer                | 3         | 0.62%   |
| Foxconn International           | 2         | 0.41%   |
| USI                             | 1         | 0.21%   |
| Ralink Technology               | 1         | 0.21%   |
| Opticis                         | 1         | 0.21%   |
| Chicony Electronics             | 1         | 0.21%   |
| Askey Computer                  | 1         | 0.21%   |
| Actiontec Electronics           | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 105       | 21.74%  |
| Intel AX200 Bluetooth                               | 64        | 13.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 57        | 11.8%   |
| Intel AX201 Bluetooth                               | 52        | 10.77%  |
| Realtek Bluetooth Radio                             | 22        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 2.69%   |
| Intel AX210 Bluetooth                               | 10        | 2.07%   |
| Apple Bluetooth Host Controller                     | 10        | 2.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.66%   |
| Realtek Bluetooth Radio                             | 7         | 1.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.45%   |
| IMC Networks Wireless_Device                        | 7         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.24%   |
| Intel Bluetooth Device                              | 6         | 1.24%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.24%   |
| Realtek RTL8723B Bluetooth                          | 5         | 1.04%   |
| Lite-On Bluetooth Device                            | 5         | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.62%   |
| IMC Networks Bluetooth Device                       | 3         | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.62%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.62%   |
| Apple Bluetooth HCI                                 | 3         | 0.62%   |
| Toshiba RT Bluetooth Radio                          | 2         | 0.41%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 2         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.41%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.41%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.41%   |
| ASUS Broadcom Bluetooth 2.1                         | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 410       | 54.3%   |
| AMD                                  | 139       | 18.41%  |
| Nvidia                               | 132       | 17.48%  |
| Lenovo                               | 12        | 1.59%   |
| Realtek Semiconductor                | 7         | 0.93%   |
| C-Media Electronics                  | 6         | 0.79%   |
| Plantronics                          | 4         | 0.53%   |
| Logitech                             | 3         | 0.4%    |
| Kingston Technology                  | 3         | 0.4%    |
| Dell                                 | 3         | 0.4%    |
| Blue Microphones                     | 3         | 0.4%    |
| Razer USA                            | 2         | 0.26%   |
| No brand                             | 2         | 0.26%   |
| Hewlett-Packard                      | 2         | 0.26%   |
| GYROCOM C&C                          | 2         | 0.26%   |
| Generalplus Technology               | 2         | 0.26%   |
| Creative Technology                  | 2         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.13%   |
| Texas Instruments                    | 1         | 0.13%   |
| Tdlasunnic                           | 1         | 0.13%   |
| SteelSeries ApS                      | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.13%   |
| Sennheiser Communications            | 1         | 0.13%   |
| Samson Technologies                  | 1         | 0.13%   |
| RODE Microphones                     | 1         | 0.13%   |
| LG Electronics                       | 1         | 0.13%   |
| JMTek                                | 1         | 0.13%   |
| iCreate Technologies                 | 1         | 0.13%   |
| GN Netcom                            | 1         | 0.13%   |
| FiiO Electronics Technology          | 1         | 0.13%   |
| Corsair                              | 1         | 0.13%   |
| Behringer.......                     | 1         | 0.13%   |
| AVer Information                     | 1         | 0.13%   |
| AudioQuest                           | 1         | 0.13%   |
| ATOLL Electronique                   | 1         | 0.13%   |
| Apple                                | 1         | 0.13%   |
| ACTIONS                              | 1         | 0.13%   |
| A4Tech                               | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 115       | 12.62%  |
| Intel Sunrise Point-LP HD Audio                                            | 71        | 7.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 66        | 7.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 60        | 6.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 27        | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 2.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 24        | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 2.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 2.09%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 17        | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.87%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.76%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.76%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 15        | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 1.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 1.43%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 10        | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 8         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.88%   |
| Realtek Semiconductor USB Audio                                            | 7         | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.66%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 0.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 0.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 206       | 32.65%  |
| SK hynix                     | 142       | 22.5%   |
| Micron Technology            | 85        | 13.47%  |
| Kingston                     | 47        | 7.45%   |
| Unknown                      | 36        | 5.71%   |
| Crucial                      | 33        | 5.23%   |
| Ramaxel Technology           | 13        | 2.06%   |
| A-DATA Technology            | 9         | 1.43%   |
| Corsair                      | 8         | 1.27%   |
| Elpida                       | 7         | 1.11%   |
| Transcend                    | 6         | 0.95%   |
| Team                         | 5         | 0.79%   |
| G.Skill                      | 5         | 0.79%   |
| Patriot                      | 4         | 0.63%   |
| Nanya Technology             | 4         | 0.63%   |
| Goodram                      | 4         | 0.63%   |
| Unknown (ABCD)               | 2         | 0.32%   |
| Timetec                      | 2         | 0.32%   |
| AMD                          | 2         | 0.32%   |
| Unknown                      | 2         | 0.32%   |
| Unknown (0x5D00000000000000) | 1         | 0.16%   |
| Teikon                       | 1         | 0.16%   |
| Saikano                      | 1         | 0.16%   |
| Magnum Tech                  | 1         | 0.16%   |
| KLEVV                        | 1         | 0.16%   |
| Goldkey                      | 1         | 0.16%   |
| Avant                        | 1         | 0.16%   |
| Apacer                       | 1         | 0.16%   |
| 48spaces                     | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 11        | 1.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 9         | 1.36%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 9         | 1.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 9         | 1.36%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 9         | 1.36%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s     | 8         | 1.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 8         | 1.21%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 8         | 1.21%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 1.21%   |
| Unknown RAM Module 1GB SODIMM DDR                             | 7         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 7         | 1.06%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s     | 7         | 1.06%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 7         | 1.06%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 0.9%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 6         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 6         | 0.9%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 5         | 0.75%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 5         | 0.75%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 5         | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.75%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 5         | 0.75%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.75%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s         | 5         | 0.75%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s       | 5         | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 4         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 0.6%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 4         | 0.6%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 4         | 0.6%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 4         | 0.6%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 3         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 0.45%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 3         | 0.45%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 3         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 332       | 62.17%  |
| DDR3    | 119       | 22.28%  |
| LPDDR4  | 24        | 4.49%   |
| LPDDR3  | 18        | 3.37%   |
| DDR2    | 15        | 2.81%   |
| DDR     | 10        | 1.87%   |
| SDRAM   | 5         | 0.94%   |
| DDR5    | 4         | 0.75%   |
| LPDDR5  | 3         | 0.56%   |
| Unknown | 3         | 0.56%   |
| DRAM    | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 479       | 89.37%  |
| Row Of Chips | 50        | 9.33%   |
| Chip         | 5         | 0.93%   |
| DIMM         | 2         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 245       | 42.31%  |
| 16384 | 129       | 22.28%  |
| 4096  | 112       | 19.34%  |
| 2048  | 37        | 6.39%   |
| 32768 | 30        | 5.18%   |
| 1024  | 19        | 3.28%   |
| 512   | 4         | 0.69%   |
| 256   | 3         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 158       | 27.15%  |
| 3200    | 135       | 23.2%   |
| 1600    | 85        | 14.6%   |
| 2400    | 40        | 6.87%   |
| 2133    | 34        | 5.84%   |
| 1333    | 17        | 2.92%   |
| Unknown | 14        | 2.41%   |
| 4267    | 12        | 2.06%   |
| 667     | 12        | 2.06%   |
| 1334    | 11        | 1.89%   |
| 1867    | 8         | 1.37%   |
| 8400    | 7         | 1.2%    |
| 4800    | 7         | 1.2%    |
| 3266    | 7         | 1.2%    |
| 1067    | 6         | 1.03%   |
| 800     | 5         | 0.86%   |
| 6400    | 4         | 0.69%   |
| 4266    | 3         | 0.52%   |
| 3733    | 3         | 0.52%   |
| 2933    | 3         | 0.52%   |
| 533     | 3         | 0.52%   |
| 3000    | 2         | 0.34%   |
| 400     | 2         | 0.34%   |
| 4199    | 1         | 0.17%   |
| 1639    | 1         | 0.17%   |
| 1066    | 1         | 0.17%   |
| 133     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 40%     |
| Seiko Epson         | 2         | 20%     |
| Xiaomi              | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| Konica Minolta      | 1         | 10%     |
| Canon               | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 10%     |
| Seiko Epson WF-2510 Series           | 1         | 10%     |
| Seiko Epson AL-M310DN                | 1         | 10%     |
| Samsung CLP-325 Color Laser Printer  | 1         | 10%     |
| Konica Minolta magicolor 1680MF scan | 1         | 10%     |
| HP LaserJet P2055 series             | 1         | 10%     |
| HP Deskjet D1500 series              | 1         | 10%     |
| HP DeskJet 5440                      | 1         | 10%     |
| HP DeskJet 3630 series               | 1         | 10%     |
| Canon CanoScan LiDE 300              | 1         | 10%     |

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
| Chicony Electronics                    | 132       | 27.39%  |
| IMC Networks                           | 65        | 13.49%  |
| Microdia                               | 43        | 8.92%   |
| Realtek Semiconductor                  | 40        | 8.3%    |
| Acer                                   | 38        | 7.88%   |
| Sunplus Innovation Technology          | 27        | 5.6%    |
| Lite-On Technology                     | 19        | 3.94%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 3.94%   |
| Quanta                                 | 18        | 3.73%   |
| Syntek                                 | 12        | 2.49%   |
| Luxvisions Innotech Limited            | 11        | 2.28%   |
| Logitech                               | 10        | 2.07%   |
| Apple                                  | 10        | 2.07%   |
| Samsung Electronics                    | 5         | 1.04%   |
| DigiTech                               | 4         | 0.83%   |
| Z-Star Microelectronics                | 3         | 0.62%   |
| Suyin                                  | 3         | 0.62%   |
| Silicon Motion                         | 2         | 0.41%   |
| Microsoft                              | 2         | 0.41%   |
| LG Electronics                         | 2         | 0.41%   |
| Alcor Micro                            | 2         | 0.41%   |
| USB3.0 HD Audio Capture                | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| ShineTech                              | 1         | 0.21%   |
| Ricoh                                  | 1         | 0.21%   |
| Razer USA                              | 1         | 0.21%   |
| Omnivision                             | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| Intel                                  | 1         | 0.21%   |
| Holitech                               | 1         | 0.21%   |
| Hewlett-Packard                        | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| Cubeternet                             | 1         | 0.21%   |
| AVer Information                       | 1         | 0.21%   |
| Aveo Technology                        | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 40        | 8.18%   |
| Microdia Integrated_Webcam_HD                                  | 30        | 6.13%   |
| IMC Networks Integrated Camera                                 | 29        | 5.93%   |
| Realtek Integrated_Webcam_HD                                   | 20        | 4.09%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 3.07%   |
| Acer Integrated Camera                                         | 15        | 3.07%   |
| Chicony HD Webcam                                              | 14        | 2.86%   |
| Sunplus Integrated_Webcam_HD                                   | 10        | 2.04%   |
| Chicony HP HD Camera                                           | 10        | 2.04%   |
| Chicony USB2.0 Camera                                          | 9         | 1.84%   |
| Lite-On Integrated Camera                                      | 8         | 1.64%   |
| Syntek Integrated Camera                                       | 7         | 1.43%   |
| Sunplus HD WebCam                                              | 5         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 5         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.02%   |
| Chicony HD User Facing                                         | 5         | 1.02%   |
| Apple FaceTime HD Camera                                       | 5         | 1.02%   |
| Acer SunplusIT Integrated Camera                               | 5         | 1.02%   |
| Quanta HP Wide Vision HD Camera                                | 4         | 0.82%   |
| Microdia Integrated Webcam                                     | 4         | 0.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.82%   |
| Logitech HD Pro Webcam C920                                    | 4         | 0.82%   |
| Lite-On TOSHIBA Web Camera - HD                                | 4         | 0.82%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 4         | 0.82%   |
| Chicony ThinkPad T490 Webcam                                   | 4         | 0.82%   |
| Chicony Lenovo EasyCamera                                      | 4         | 0.82%   |
| Chicony EasyCamera                                             | 4         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 4         | 0.82%   |
| Acer BisonCam, NB Pro                                          | 4         | 0.82%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.61%   |
| Sunplus HP Wide Vision HD                                      | 3         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                                   | 3         | 0.61%   |
| Realtek Integrated Webcam HD                                   | 3         | 0.61%   |
| Realtek Integrated Webcam                                      | 3         | 0.61%   |
| Quanta HD Webcam                                               | 3         | 0.61%   |
| Quanta HD User Facing                                          | 3         | 0.61%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 3         | 0.61%   |
| Luxvisions Innotech Limited HP HD Camera                       | 3         | 0.61%   |
| Lite-On HP Wide Vision HD Camera                               | 3         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 53        | 47.32%  |
| Validity Sensors           | 24        | 21.43%  |
| Shenzhen Goodix Technology | 17        | 15.18%  |
| Elan Microelectronics      | 7         | 6.25%   |
| STMicroelectronics         | 4         | 3.57%   |
| AuthenTec                  | 4         | 3.57%   |
| LighTuning Technology      | 2         | 1.79%   |
| Upek                       | 1         | 0.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 22        | 19.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 15        | 13.39%  |
| Shenzhen Goodix  FingerPrint Device                        | 8         | 7.14%   |
| Unknown                                                    | 7         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 5.36%   |
| Elan ELAN:Fingerprint                                      | 6         | 5.36%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 4.46%   |
| Validity Sensors Synaptics WBDI                            | 5         | 4.46%   |
| Shenzhen Goodix FingerPrint                                | 5         | 4.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 3.57%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 2.68%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.68%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 1.79%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 0.89%   |
| Validity Sensors VFS491                                    | 1         | 0.89%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 0.89%   |
| Synaptics WBDI Device                                      | 1         | 0.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 0.89%   |
| LighTuning EgisTec_ES603                                   | 1         | 0.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 0.89%   |
| Elan ELAN:ARM-M4                                           | 1         | 0.89%   |
| AuthenTec Fingerprint Sensor                               | 1         | 0.89%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 34        | 44.74%  |
| Broadcom                  | 30        | 39.47%  |
| Upek                      | 4         | 5.26%   |
| O2 Micro                  | 3         | 3.95%   |
| Yubico.com                | 1         | 1.32%   |
| Purism, SPC               | 1         | 1.32%   |
| Microchip Technology      | 1         | 1.32%   |
| Gemalto (was Gemplus)     | 1         | 1.32%   |
| Aladdin Knowledge Systems | 1         | 1.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 44.74%  |
| Broadcom 5880                                                                | 10        | 13.16%  |
| Broadcom 58200                                                               | 10        | 13.16%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 7.89%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.63%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.32%   |
| Purism, SPC Librem Key                                                       | 1         | 1.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.32%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.32%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 207       | 33.28%  |
| 1     | 159       | 25.56%  |
| 2     | 105       | 16.88%  |
| 3     | 72        | 11.58%  |
| 4     | 43        | 6.91%   |
| 5     | 23        | 3.7%    |
| 6     | 10        | 1.61%   |
| 7     | 2         | 0.32%   |
| 8     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 144       | 16.16%  |
| Camera                   | 124       | 13.92%  |
| Bluetooth                | 117       | 13.13%  |
| Fingerprint reader       | 112       | 12.57%  |
| Graphics card            | 98        | 11%     |
| Chipcard                 | 63        | 7.07%   |
| Card reader              | 58        | 6.51%   |
| Multimedia controller    | 50        | 5.61%   |
| Net/wireless             | 49        | 5.5%    |
| Sound                    | 16        | 1.8%    |
| Modem                    | 13        | 1.46%   |
| Net/ethernet             | 11        | 1.23%   |
| Network                  | 10        | 1.12%   |
| Storage/ata              | 6         | 0.67%   |
| Storage                  | 5         | 0.56%   |
| Storage/ide              | 4         | 0.45%   |
| Firewire controller      | 4         | 0.45%   |
| Tv card                  | 2         | 0.22%   |
| Dvb card                 | 2         | 0.22%   |
| Wireless                 | 1         | 0.11%   |
| Storage/raid             | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |


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

Total: 1004

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3501               | [f9379c4ffb](https://linux-hardware.org/?probe=f9379c4ffb) | Dec 01, 2022 |
| Unknown       | Unknown                     | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [d77cb5ebb0](https://linux-hardware.org/?probe=d77cb5ebb0) | Nov 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Acer          | Swift SF314-57              | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Dell          | Inspiron N5010              | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Unknown       | Unknown                     | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| Lenovo        | G50-30 80G0                 | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9db585ddc5](https://linux-hardware.org/?probe=9db585ddc5) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Acer          | Nitro AN515-58              | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| Acer          | Nitro AN515-43              | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
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
| Gentoo 2.7     | 243       | 38.15%  |
| Gentoo 2.6     | 199       | 31.24%  |
| Gentoo 2.8     | 153       | 24.02%  |
| Gentoo 2.9     | 17        | 2.67%   |
| Gentoo         | 7         | 1.1%    |
| Gentoo 2.4.1   | 5         | 0.78%   |
| Gentoo 2.3     | 4         | 0.63%   |
| Gentoo 2.2     | 4         | 0.63%   |
| Gentoo Pelikan | 1         | 0.16%   |
| Gentoo 22      | 1         | 0.16%   |
| Gentoo 2022    | 1         | 0.16%   |
| Gentoo 2.1     | 1         | 0.16%   |
| Gentoo 1       | 1         | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 575       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 16        | 2.19%   |
| 5.10.61-gentoo           | 13        | 1.78%   |
| 5.4.38-gentoo            | 11        | 1.5%    |
| 5.4.80-gentoo-r1         | 9         | 1.23%   |
| 5.4.48-gentoo            | 9         | 1.23%   |
| 5.15.32-gentoo-r1        | 9         | 1.23%   |
| 5.10.76-gentoo-r1        | 8         | 1.09%   |
| 5.10.76-gentoo-r1-x86_64 | 7         | 0.96%   |
| 5.15.59-gentoo-x86_64    | 6         | 0.82%   |
| 5.10.52-gentoo           | 6         | 0.82%   |
| 5.10.27-gentoo-x86_64    | 6         | 0.82%   |
| 5.4.97-gentoo            | 5         | 0.68%   |
| 5.4.60-gentoo            | 5         | 0.68%   |
| 5.4.28-gentoo            | 5         | 0.68%   |
| 5.15.75-gentoo-x86_64    | 5         | 0.68%   |
| 5.15.72-gentoo-x86_64    | 5         | 0.68%   |
| 5.15.52-gentoo           | 5         | 0.68%   |
| 5.15.32-gentoo-r1-x86_64 | 5         | 0.68%   |
| 5.10.61-gentoo-x86_64    | 5         | 0.68%   |
| 5.8.0-gentoo-r1          | 4         | 0.55%   |
| 5.4.97-gentoo-x86_64     | 4         | 0.55%   |
| 5.4.48-gentoo-x86_64     | 4         | 0.55%   |
| 5.19.0-gentoo-x86_64     | 4         | 0.55%   |
| 5.15.72-gentoo           | 4         | 0.55%   |
| 5.15.69-gentoo           | 4         | 0.55%   |
| 4.19.97-gentoo           | 4         | 0.55%   |
| 4.14.65-gentoo           | 4         | 0.55%   |
| 5.4.66-gentoo            | 3         | 0.41%   |
| 5.4.38-gentoo-x86_64     | 3         | 0.41%   |
| 5.17.3-gentoo            | 3         | 0.41%   |
| 5.17.1-gentoo-r1         | 3         | 0.41%   |
| 5.15.75-gentoo           | 3         | 0.41%   |
| 5.15.74-gentoo           | 3         | 0.41%   |
| 5.15.59-gentoo           | 3         | 0.41%   |
| 5.15.52-gentoo-x86_64    | 3         | 0.41%   |
| 5.15.5-gentoo            | 3         | 0.41%   |
| 5.15.41-gentoo-x86_64    | 3         | 0.41%   |
| 5.15.26-gentoo-x86_64    | 3         | 0.41%   |
| 5.15.26-gentoo           | 3         | 0.41%   |
| 5.15.23-gentoo-x86_64    | 3         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 3.42%   |
| 5.4.48  | 20        | 2.74%   |
| 5.10.76 | 20        | 2.74%   |
| 5.10.61 | 19        | 2.6%    |
| 5.15.32 | 17        | 2.33%   |
| 5.4.38  | 16        | 2.19%   |
| 5.15.59 | 12        | 1.64%   |
| 5.4.97  | 11        | 1.51%   |
| 5.4.80  | 11        | 1.51%   |
| 5.4.28  | 11        | 1.51%   |
| 5.15.72 | 11        | 1.51%   |
| 5.15.52 | 11        | 1.51%   |
| 5.10.52 | 10        | 1.37%   |
| 5.15.75 | 9         | 1.23%   |
| 5.15.11 | 9         | 1.23%   |
| 5.15.69 | 8         | 1.1%    |
| 4.19.97 | 8         | 1.1%    |
| 6.0.0   | 7         | 0.96%   |
| 5.4.72  | 7         | 0.96%   |
| 5.4.60  | 7         | 0.96%   |
| 5.19.0  | 7         | 0.96%   |
| 5.17.1  | 7         | 0.96%   |
| 5.16.0  | 7         | 0.96%   |
| 5.15.41 | 7         | 0.96%   |
| 5.4.66  | 6         | 0.82%   |
| 5.15.26 | 6         | 0.82%   |
| 5.15.23 | 6         | 0.82%   |
| 5.15.10 | 6         | 0.82%   |
| 5.8.0   | 5         | 0.68%   |
| 5.15.5  | 5         | 0.68%   |
| 5.15.13 | 5         | 0.68%   |
| 5.14.9  | 5         | 0.68%   |
| 5.11.0  | 5         | 0.68%   |
| 5.10.4  | 5         | 0.68%   |
| 4.19.57 | 5         | 0.68%   |
| 6.0.6   | 4         | 0.55%   |
| 5.9.1   | 4         | 0.55%   |
| 5.9.0   | 4         | 0.55%   |
| 5.6.15  | 4         | 0.55%   |
| 5.4.92  | 4         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 134       | 19.68%  |
| 5.10    | 108       | 15.86%  |
| 5.4     | 102       | 14.98%  |
| 4.19    | 33        | 4.85%   |
| 5.17    | 25        | 3.67%   |
| 5.9     | 23        | 3.38%   |
| 5.16    | 23        | 3.38%   |
| 5.6     | 22        | 3.23%   |
| 5.14    | 22        | 3.23%   |
| 6.0     | 21        | 3.08%   |
| 5.18    | 20        | 2.94%   |
| 5.8     | 19        | 2.79%   |
| 5.11    | 19        | 2.79%   |
| 5.12    | 17        | 2.5%    |
| 5.7     | 16        | 2.35%   |
| 5.19    | 15        | 2.2%    |
| 5.13    | 13        | 1.91%   |
| 4.14    | 8         | 1.17%   |
| 5.5     | 7         | 1.03%   |
| 5.3     | 5         | 0.73%   |
| 5.1     | 5         | 0.73%   |
| 4.4     | 5         | 0.73%   |
| 5.2     | 3         | 0.44%   |
| 4.9     | 3         | 0.44%   |
| 4.18    | 3         | 0.44%   |
| 5.0     | 2         | 0.29%   |
| 4.6     | 2         | 0.29%   |
| 4.12    | 2         | 0.29%   |
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
| x86_64 | 554       | 96.35%  |
| i686   | 18        | 3.13%   |
| ppc    | 3         | 0.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 267       | 43.91%  |
| KDE5           | 120       | 19.74%  |
| GNOME          | 80        | 13.16%  |
| XFCE           | 47        | 7.73%   |
| KDE            | 24        | 3.95%   |
| MATE           | 13        | 2.14%   |
| DWM            | 9         | 1.48%   |
| sway           | 8         | 1.32%   |
| LXQt           | 8         | 1.32%   |
| LXDE           | 5         | 0.82%   |
| XSession       | 4         | 0.66%   |
| openbox        | 3         | 0.49%   |
| X-Cinnamon     | 2         | 0.33%   |
| Trinity        | 2         | 0.33%   |
| Enlightenment  | 2         | 0.33%   |
| Cinnamon       | 2         | 0.33%   |
| bspwm          | 2         | 0.33%   |
| awesome        | 2         | 0.33%   |
| xmonad         | 1         | 0.16%   |
| qt5ct          | 1         | 0.16%   |
| LeftWM         | 1         | 0.16%   |
| i3-with-shmlog | 1         | 0.16%   |
| i3             | 1         | 0.16%   |
| GNOME Classic  | 1         | 0.16%   |
| fvwm           | 1         | 0.16%   |
| fluxbox        | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 357       | 58.33%  |
| Unknown | 92        | 15.03%  |
| Tty     | 86        | 14.05%  |
| Wayland | 77        | 12.58%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 293       | 48.75%  |
| SDDM    | 152       | 25.29%  |
| LightDM | 65        | 10.82%  |
| GDM     | 56        | 9.32%   |
| XDM     | 13        | 2.16%   |
| SLiM    | 8         | 1.33%   |
| LXDM    | 6         | 1%      |
| TDM     | 3         | 0.5%    |
| GREETD  | 3         | 0.5%    |
| KDM     | 1         | 0.17%   |
| GDM3    | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 230       | 37.83%  |
| Unknown    | 99        | 16.28%  |
| C.UTF8     | 53        | 8.72%   |
| de_DE      | 34        | 5.59%   |
| en_GB      | 33        | 5.43%   |
| ru_RU      | 27        | 4.44%   |
| C          | 13        | 2.14%   |
| fr_FR      | 12        | 1.97%   |
| it_IT      | 11        | 1.81%   |
| en_AU      | 10        | 1.64%   |
| zh_CN      | 8         | 1.32%   |
| es_ES      | 7         | 1.15%   |
| en_CA      | 7         | 1.15%   |
| POSIX      | 5         | 0.82%   |
| pl_PL      | 5         | 0.82%   |
| el_GR      | 5         | 0.82%   |
| pt_BR      | 4         | 0.66%   |
| nl_NL      | 3         | 0.49%   |
| nl_BE      | 3         | 0.49%   |
| cs_CZ      | 3         | 0.49%   |
| uk_UA      | 2         | 0.33%   |
| ja_JP      | 2         | 0.33%   |
| fr_CA      | 2         | 0.33%   |
| es_CL      | 2         | 0.33%   |
| es_AR      | 2         | 0.33%   |
| en_ZA      | 2         | 0.33%   |
| en_US.UTF8 | 2         | 0.33%   |
| en_MX      | 2         | 0.33%   |
| en_IE      | 2         | 0.33%   |
| de_CH      | 2         | 0.33%   |
| ca_ES      | 2         | 0.33%   |
| zh_TW      | 1         | 0.16%   |
| tr_TR.UTF8 | 1         | 0.16%   |
| tr_TR      | 1         | 0.16%   |
| sv_SE      | 1         | 0.16%   |
| ru_UA      | 1         | 0.16%   |
| lt_LT      | 1         | 0.16%   |
| ko_KR      | 1         | 0.16%   |
| fr_BE      | 1         | 0.16%   |
| es_MX      | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 449       | 76.36%  |
| BIOS | 139       | 23.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 355       | 60.79%  |
| Btrfs    | 134       | 22.95%  |
| Unknown  | 23        | 3.94%   |
| Xfs      | 22        | 3.77%   |
| Zfs      | 17        | 2.91%   |
| F2fs     | 16        | 2.74%   |
| XXXXXXX  | 9         | 1.54%   |
| Reiserfs | 2         | 0.34%   |
| Ext3     | 2         | 0.34%   |
| Overlay  | 1         | 0.17%   |
| Jfs      | 1         | 0.17%   |
| Ext2     | 1         | 0.17%   |
| Bcachefs | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 489       | 83.88%  |
| MBR     | 59        | 10.12%  |
| Unknown | 35        | 6%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 438       | 74.36%  |
| Yes       | 151       | 25.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 409       | 69.56%  |
| Yes       | 179       | 30.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 166       | 28.87%  |
| Dell                           | 101       | 17.57%  |
| Hewlett-Packard                | 83        | 14.43%  |
| ASUSTek Computer               | 61        | 10.61%  |
| Acer                           | 33        | 5.74%   |
| MSI                            | 16        | 2.78%   |
| Apple                          | 15        | 2.61%   |
| Timi                           | 10        | 1.74%   |
| HUAWEI                         | 10        | 1.74%   |
| Toshiba                        | 8         | 1.39%   |
| Samsung Electronics            | 8         | 1.39%   |
| TUXEDO                         | 7         | 1.22%   |
| Razer                          | 5         | 0.87%   |
| Unknown                        | 5         | 0.87%   |
| Notebook                       | 4         | 0.7%    |
| IBM                            | 4         | 0.7%    |
| System76                       | 3         | 0.52%   |
| Fujitsu                        | 3         | 0.52%   |
| win element                    | 2         | 0.35%   |
| Sony                           | 2         | 0.35%   |
| Purism                         | 2         | 0.35%   |
| Positivo                       | 2         | 0.35%   |
| Medion                         | 2         | 0.35%   |
| Framework                      | 2         | 0.35%   |
| Chuwi                          | 2         | 0.35%   |
| XMG                            | 1         | 0.17%   |
| Wortmann AG                    | 1         | 0.17%   |
| Valve                          | 1         | 0.17%   |
| SIEMENS                        | 1         | 0.17%   |
| Seco                           | 1         | 0.17%   |
| Schenker                       | 1         | 0.17%   |
| PC Specialist                  | 1         | 0.17%   |
| MOTILE                         | 1         | 0.17%   |
| Matsushita Electric Industrial | 1         | 0.17%   |
| LG Electronics                 | 1         | 0.17%   |
| Jumper                         | 1         | 0.17%   |
| IT Channel Pty                 | 1         | 0.17%   |
| Intel Client Systems           | 1         | 0.17%   |
| Google                         | 1         | 0.17%   |
| Gigabyte Technology            | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 12        | 2.09%   |
| HP Pavilion Notebook                 | 5         | 0.87%   |
| Dell XPS 15 9570                     | 5         | 0.87%   |
| HP OMEN by Laptop                    | 4         | 0.7%    |
| HP Laptop 14-dk1xxx                  | 4         | 0.7%    |
| Dell XPS 17 9710                     | 4         | 0.7%    |
| Dell XPS 13 9310                     | 4         | 0.7%    |
| ASUS ROG Strix G513QY_G513QY         | 4         | 0.7%    |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE | 3         | 0.52%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.52%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 3         | 0.52%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 3         | 0.52%   |
| Dell XPS 15 7590                     | 3         | 0.52%   |
| Dell XPS 13 9370                     | 3         | 0.52%   |
| Dell XPS 13 9360                     | 3         | 0.52%   |
| Dell Latitude E7440                  | 3         | 0.52%   |
| Dell Latitude 7390                   | 3         | 0.52%   |
| win element MoreFine S500+           | 2         | 0.35%   |
| Toshiba Satellite C850D-118          | 2         | 0.35%   |
| Toshiba NB100                        | 2         | 0.35%   |
| Timi RedmiBook 13 R                  | 2         | 0.35%   |
| MSI GS63VR 6RF                       | 2         | 0.35%   |
| Lenovo ThinkPad T480 20L5CTO1WW      | 2         | 0.35%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB | 2         | 0.35%   |
| Lenovo Legion Y540-15IRH 81SX        | 2         | 0.35%   |
| Lenovo Legion R7000 2020 82B6        | 2         | 0.35%   |
| Lenovo IdeaPad 5 15ITL05 82FG        | 2         | 0.35%   |
| HUAWEI KLVL-WXX9                     | 2         | 0.35%   |
| HUAWEI BOHK-WAX9X                    | 2         | 0.35%   |
| HP ProBook 455 G7                    | 2         | 0.35%   |
| HP Pavilion dv7                      | 2         | 0.35%   |
| HP Laptop 15s-eq0xxx                 | 2         | 0.35%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.35%   |
| HP EliteBook 840 G7 Notebook PC      | 2         | 0.35%   |
| HP EliteBook 820 G3                  | 2         | 0.35%   |
| Framework Laptop                     | 2         | 0.35%   |
| Dell XPS 13 9380                     | 2         | 0.35%   |
| Dell Precision 7560                  | 2         | 0.35%   |
| Dell Latitude E6530                  | 2         | 0.35%   |
| Dell Latitude E6430                  | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 98        | 17.04%  |
| Dell Latitude        | 36        | 6.26%   |
| Dell XPS             | 29        | 5.04%   |
| Lenovo Legion        | 22        | 3.83%   |
| Lenovo IdeaPad       | 21        | 3.65%   |
| HP Pavilion          | 19        | 3.3%    |
| HP EliteBook         | 18        | 3.13%   |
| Acer Aspire          | 17        | 2.96%   |
| Dell Inspiron        | 16        | 2.78%   |
| HP Laptop            | 14        | 2.43%   |
| ASUS ROG             | 12        | 2.09%   |
| Unknown              | 12        | 2.09%   |
| HP OMEN              | 10        | 1.74%   |
| Dell Precision       | 10        | 1.74%   |
| HP ProBook           | 9         | 1.57%   |
| ASUS ZenBook         | 8         | 1.39%   |
| Lenovo Yoga          | 7         | 1.22%   |
| Acer Nitro           | 7         | 1.22%   |
| Toshiba Satellite    | 6         | 1.04%   |
| ASUS VivoBook        | 6         | 1.04%   |
| Acer Swift           | 6         | 1.04%   |
| Timi RedmiBook       | 5         | 0.87%   |
| Razer Blade          | 5         | 0.87%   |
| HP ZBook             | 5         | 0.87%   |
| Apple MacBookPro8    | 5         | 0.87%   |
| Lenovo ThinkBook     | 4         | 0.7%    |
| Timi Mi              | 3         | 0.52%   |
| IBM ThinkPad         | 3         | 0.52%   |
| Fujitsu LIFEBOOK     | 3         | 0.52%   |
| Dell Vostro          | 3         | 0.52%   |
| Dell G3              | 3         | 0.52%   |
| ASUS ASUS            | 3         | 0.52%   |
| win element MoreFine | 2         | 0.35%   |
| TUXEDO Book          | 2         | 0.35%   |
| Toshiba NB100        | 2         | 0.35%   |
| System76 Gazelle     | 2         | 0.35%   |
| Purism Librem        | 2         | 0.35%   |
| MSI GS63VR           | 2         | 0.35%   |
| MSI GF63             | 2         | 0.35%   |
| HUAWEI KLVL-WXX9     | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 103       | 17.91%  |
| 2019    | 98        | 17.04%  |
| 2021    | 69        | 12%     |
| 2018    | 64        | 11.13%  |
| 2017    | 32        | 5.57%   |
| 2014    | 31        | 5.39%   |
| 2015    | 26        | 4.52%   |
| 2016    | 25        | 4.35%   |
| 2012    | 25        | 4.35%   |
| 2011    | 23        | 4%      |
| 2022    | 18        | 3.13%   |
| 2013    | 14        | 2.43%   |
| 2010    | 12        | 2.09%   |
| 2008    | 12        | 2.09%   |
| 2006    | 6         | 1.04%   |
| 2009    | 4         | 0.7%    |
| Unknown | 4         | 0.7%    |
| 2007    | 3         | 0.52%   |
| 2005    | 3         | 0.52%   |
| 2004    | 2         | 0.35%   |
| 2003    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 575       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 564       | 97.75%  |
| Enabled  | 13        | 2.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 569       | 98.96%  |
| Yes  | 6         | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 143       | 24.36%  |
| 8.01-16.0   | 131       | 22.32%  |
| 4.01-8.0    | 111       | 18.91%  |
| 32.01-64.0  | 88        | 14.99%  |
| 3.01-4.0    | 37        | 6.3%    |
| 64.01-256.0 | 24        | 4.09%   |
| 24.01-32.0  | 18        | 3.07%   |
| 1.01-2.0    | 14        | 2.39%   |
| 2.01-3.0    | 12        | 2.04%   |
| 0.51-1.0    | 7         | 1.19%   |
| 0.01-0.5    | 2         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 174       | 26.05%  |
| 2.01-3.0   | 111       | 16.62%  |
| 4.01-8.0   | 107       | 16.02%  |
| 3.01-4.0   | 82        | 12.28%  |
| 0.01-0.5   | 68        | 10.18%  |
| 0.51-1.0   | 64        | 9.58%   |
| 8.01-16.0  | 55        | 8.23%   |
| 16.01-24.0 | 5         | 0.75%   |
| 32.01-64.0 | 1         | 0.15%   |
| 24.01-32.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 403       | 68.19%  |
| 2      | 159       | 26.9%   |
| 3      | 21        | 3.55%   |
| 0      | 6         | 1.02%   |
| 4      | 2         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 487       | 83.97%  |
| Yes       | 93        | 16.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 452       | 77.8%   |
| No        | 129       | 22.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 568       | 98.78%  |
| No        | 7         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 500       | 85.91%  |
| No        | 82        | 14.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 99        | 17.04%  |
| Germany      | 80        | 13.77%  |
| Russia       | 51        | 8.78%   |
| France       | 30        | 5.16%   |
| China        | 30        | 5.16%   |
| UK           | 22        | 3.79%   |
| Canada       | 20        | 3.44%   |
| Poland       | 18        | 3.1%    |
| Italy        | 18        | 3.1%    |
| Netherlands  | 16        | 2.75%   |
| Australia    | 15        | 2.58%   |
| Spain        | 13        | 2.24%   |
| Czechia      | 13        | 2.24%   |
| Ukraine      | 11        | 1.89%   |
| Sweden       | 11        | 1.89%   |
| Greece       | 10        | 1.72%   |
| Turkey       | 9         | 1.55%   |
| Belgium      | 8         | 1.38%   |
| Switzerland  | 7         | 1.2%    |
| India        | 7         | 1.2%    |
| Brazil       | 7         | 1.2%    |
| Mexico       | 6         | 1.03%   |
| Japan        | 6         | 1.03%   |
| Finland      | 6         | 1.03%   |
| Norway       | 5         | 0.86%   |
| Hong Kong    | 5         | 0.86%   |
| Belarus      | 5         | 0.86%   |
| Austria      | 5         | 0.86%   |
| Romania      | 4         | 0.69%   |
| Portugal     | 4         | 0.69%   |
| South Africa | 3         | 0.52%   |
| Slovakia     | 3         | 0.52%   |
| Argentina    | 3         | 0.52%   |
| Vietnam      | 2         | 0.34%   |
| Taiwan       | 2         | 0.34%   |
| Slovenia     | 2         | 0.34%   |
| Singapore    | 2         | 0.34%   |
| New Zealand  | 2         | 0.34%   |
| Nepal        | 2         | 0.34%   |
| Iran         | 2         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 23        | 3.66%   |
| Moscow            | 20        | 3.18%   |
| Sydney            | 10        | 1.59%   |
| Athens            | 10        | 1.59%   |
| St Petersburg     | 8         | 1.27%   |
| Munich            | 7         | 1.11%   |
| Guangzhou         | 7         | 1.11%   |
| Warsaw            | 6         | 0.95%   |
| Prague            | 6         | 0.95%   |
| Kyiv              | 6         | 0.95%   |
| Amsterdam         | 6         | 0.95%   |
| Weatherford       | 5         | 0.79%   |
| Paris             | 5         | 0.79%   |
| Minsk             | 5         | 0.79%   |
| Milan             | 5         | 0.79%   |
| Los Angeles       | 5         | 0.79%   |
| Vancouver         | 4         | 0.64%   |
| Istanbul          | 4         | 0.64%   |
| Cieszyn           | 4         | 0.64%   |
| Beijing           | 4         | 0.64%   |
| Wuelfrath         | 3         | 0.48%   |
| Vienna            | 3         | 0.48%   |
| Shenzhen          | 3         | 0.48%   |
| San Jose          | 3         | 0.48%   |
| Perm              | 3         | 0.48%   |
| New York          | 3         | 0.48%   |
| Melbourne         | 3         | 0.48%   |
| Manitowoc         | 3         | 0.48%   |
| London            | 3         | 0.48%   |
| Helsinki          | 3         | 0.48%   |
| Goiânia          | 3         | 0.48%   |
| Frankfurt am Main | 3         | 0.48%   |
| Fort Worth        | 3         | 0.48%   |
| Düsseldorf       | 3         | 0.48%   |
| Chongqing         | 3         | 0.48%   |
| Cape Town         | 3         | 0.48%   |
| Woolwich          | 2         | 0.32%   |
| Winnipeg          | 2         | 0.32%   |
| West Orange       | 2         | 0.32%   |
| Vleuten           | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 181       | 288    | 24.33%  |
| WDC                            | 107       | 143    | 14.38%  |
| Seagate                        | 52        | 69     | 6.99%   |
| SK hynix                       | 50        | 59     | 6.72%   |
| Intel                          | 48        | 72     | 6.45%   |
| Toshiba                        | 44        | 50     | 5.91%   |
| SanDisk                        | 39        | 49     | 5.24%   |
| Kingston                       | 28        | 35     | 3.76%   |
| Unknown                        | 27        | 35     | 3.63%   |
| HGST                           | 26        | 28     | 3.49%   |
| Micron Technology              | 22        | 26     | 2.96%   |
| Crucial                        | 15        | 18     | 2.02%   |
| Hitachi                        | 11        | 11     | 1.48%   |
| KIOXIA                         | 10        | 13     | 1.34%   |
| A-DATA Technology              | 7         | 13     | 0.94%   |
| Apple                          | 6         | 8      | 0.81%   |
| Fujitsu                        | 5         | 7      | 0.67%   |
| China                          | 5         | 8      | 0.67%   |
| Phison Electronics             | 4         | 4      | 0.54%   |
| LITEON                         | 4         | 7      | 0.54%   |
| Phison                         | 3         | 3      | 0.4%    |
| OCZ                            | 3         | 6      | 0.4%    |
| Lenovo                         | 3         | 5      | 0.4%    |
| Kingston Technology Company    | 3         | 3      | 0.4%    |
| Transcend                      | 2         | 5      | 0.27%   |
| Plextor                        | 2         | 2      | 0.27%   |
| Netac                          | 2         | 2      | 0.27%   |
| MyDigitalSSD                   | 2         | 2      | 0.27%   |
| LITEONIT                       | 2         | 3      | 0.27%   |
| KIOXIA-EXCERIA                 | 2         | 5      | 0.27%   |
| IBM/Hitachi                    | 2         | 3      | 0.27%   |
| Zheino                         | 1         | 1      | 0.13%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.13%   |
| XrayDisk                       | 1         | 1      | 0.13%   |
| XPG                            | 1         | 1      | 0.13%   |
| Union Memory                   | 1         | 1      | 0.13%   |
| UMIS                           | 1         | 1      | 0.13%   |
| T-FORCE                        | 1         | 2      | 0.13%   |
| SPCC                           | 1         | 1      | 0.13%   |
| Solid State Storage Technology | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                             | 17        | 2.14%   |
| Intel SSDPEKNW010T8 1TB                              | 10        | 1.26%   |
| Samsung SSD 850 EVO 250GB                            | 8         | 1.01%   |
| Samsung MZVLB512HBJQ-000L2 512GB                     | 8         | 1.01%   |
| Samsung SSD 980 1TB                                  | 7         | 0.88%   |
| Samsung SSD 860 EVO 500GB                            | 7         | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 7         | 0.88%   |
| Seagate ST1000LM049-2GH172 1TB                       | 6         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 0.75%   |
| Samsung SSD 970 EVO Plus 500GB                       | 6         | 0.75%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 6         | 0.75%   |
| Intel SSDPEKNU512GZ 512GB                            | 6         | 0.75%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                     | 5         | 0.63%   |
| Unknown MMC Card  16GB                               | 5         | 0.63%   |
| Toshiba MQ04ABF100 1TB                               | 5         | 0.63%   |
| Samsung SSD 980 PRO 2TB                              | 5         | 0.63%   |
| Samsung NVMe SSD Drive 512GB                         | 5         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 5         | 0.63%   |
| HGST HTS541010A9E680 1TB                             | 5         | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 4         | 0.5%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                 | 4         | 0.5%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                   | 4         | 0.5%    |
| Toshiba MQ01ABF050 500GB                             | 4         | 0.5%    |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.5%    |
| Toshiba KXG50ZNV512G NVMe 512GB                      | 4         | 0.5%    |
| SK hynix PC711 NVMe 1TB                              | 4         | 0.5%    |
| Seagate ST2000LX001-1RG174 2TB                       | 4         | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB                       | 4         | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 250GB                       | 4         | 0.5%    |
| Samsung SSD 860 QVO 1TB                              | 4         | 0.5%    |
| Samsung SSD 860 EVO 1TB                              | 4         | 0.5%    |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 4         | 0.5%    |
| Samsung MZVLB512HAJQ-000L7 512GB                     | 4         | 0.5%    |
| Samsung MZVLB512HAJQ-00000 512GB                     | 4         | 0.5%    |
| Kingston SA400S37480G 480GB SSD                      | 4         | 0.5%    |
| Kingston SA400S37240G 240GB SSD                      | 4         | 0.5%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD              | 4         | 0.5%    |
| Intel SSDPEKKF256G8L 256GB                           | 4         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 66     | 31.82%  |
| WDC                 | 39        | 46     | 25.32%  |
| HGST                | 26        | 28     | 16.88%  |
| Toshiba             | 21        | 23     | 13.64%  |
| Hitachi             | 11        | 11     | 7.14%   |
| Fujitsu             | 5         | 7      | 3.25%   |
| IBM/Hitachi         | 2         | 3      | 1.3%    |
| Samsung Electronics | 1         | 2      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 105    | 31.3%   |
| SanDisk             | 24        | 33     | 10.43%  |
| Kingston            | 17        | 24     | 7.39%   |
| WDC                 | 16        | 25     | 6.96%   |
| SK hynix            | 12        | 13     | 5.22%   |
| Intel               | 12        | 12     | 5.22%   |
| Crucial             | 12        | 15     | 5.22%   |
| Micron Technology   | 9         | 12     | 3.91%   |
| A-DATA Technology   | 7         | 13     | 3.04%   |
| Toshiba             | 6         | 7      | 2.61%   |
| China               | 5         | 8      | 2.17%   |
| Apple               | 4         | 5      | 1.74%   |
| OCZ                 | 3         | 6      | 1.3%    |
| Transcend           | 2         | 5      | 0.87%   |
| Seagate             | 2         | 2      | 0.87%   |
| Plextor             | 2         | 2      | 0.87%   |
| Netac               | 2         | 2      | 0.87%   |
| MyDigitalSSD        | 2         | 2      | 0.87%   |
| LITEONIT            | 2         | 3      | 0.87%   |
| Zheino              | 1         | 1      | 0.43%   |
| XrayDisk            | 1         | 1      | 0.43%   |
| SPCC                | 1         | 1      | 0.43%   |
| ShanDianZhe         | 1         | 2      | 0.43%   |
| RevuAhn             | 1         | 1      | 0.43%   |
| Phison              | 1         | 1      | 0.43%   |
| Mushkin             | 1         | 1      | 0.43%   |
| LITEON              | 1         | 2      | 0.43%   |
| Lite-On             | 1         | 1      | 0.43%   |
| Linux               | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 2      | 0.43%   |
| Kingmax             | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| Hoodisk             | 1         | 1      | 0.43%   |
| Faspeed             | 1         | 1      | 0.43%   |
| e2e4                | 1         | 1      | 0.43%   |
| BIWIN               | 1         | 1      | 0.43%   |
| ASUS-PHISON         | 1         | 2      | 0.43%   |
| Unknown             | 1         | 2      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 320       | 473    | 45.45%  |
| SSD     | 208       | 318    | 29.55%  |
| HDD     | 147       | 186    | 20.88%  |
| MMC     | 27        | 33     | 3.84%   |
| Unknown | 2         | 4      | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 320       | 471    | 47.98%  |
| SATA | 307       | 492    | 46.03%  |
| MMC  | 27        | 33     | 4.05%   |
| SAS  | 13        | 18     | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 213       | 319    | 59.83%  |
| 0.51-1.0   | 125       | 157    | 35.11%  |
| 1.01-2.0   | 17        | 27     | 4.78%   |
| 4.01-10.0  | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 161       | 26.26%  |
| 101-250        | 137       | 22.35%  |
| 501-1000       | 110       | 17.94%  |
| 1001-2000      | 61        | 9.95%   |
| 51-100         | 37        | 6.04%   |
| 1-20           | 34        | 5.55%   |
| Unknown        | 33        | 5.38%   |
| 21-50          | 16        | 2.61%   |
| More than 3000 | 12        | 1.96%   |
| 2001-3000      | 12        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 159       | 24.42%  |
| 21-50          | 115       | 17.67%  |
| 101-250        | 100       | 15.36%  |
| 251-500        | 90        | 13.82%  |
| 51-100         | 80        | 12.29%  |
| 501-1000       | 49        | 7.53%   |
| Unknown        | 33        | 5.07%   |
| 1001-2000      | 17        | 2.61%   |
| 2001-3000      | 6         | 0.92%   |
| More than 3000 | 2         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                      | Notebooks | Drives | Percent |
|------------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                   | 5         | 6      | 7.94%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD                    | 3         | 3      | 4.76%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                      | 2         | 2      | 3.17%   |
| Seagate ST2000LX001-1RG174 2TB                             | 2         | 2      | 3.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                         | 2         | 3      | 3.17%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                        | 2         | 2      | 3.17%   |
| Samsung Electronics SSD 850 EVO 1TB                        | 2         | 2      | 3.17%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                           | 1         | 1      | 1.59%   |
| WDC WD1600BEVS-22RST0 160GB                                | 1         | 1      | 1.59%   |
| WDC WD10SPZX-24Z10T0 1TB                                   | 1         | 1      | 1.59%   |
| WDC WD10JPVX-75JC3T0 1TB                                   | 1         | 1      | 1.59%   |
| WDC WD10EZEX-08M2NA0 1TB                                   | 1         | 2      | 1.59%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD                   | 1         | 1      | 1.59%   |
| Toshiba MQ01ABF050 500GB                                   | 1         | 1      | 1.59%   |
| Toshiba MK6008GAH 64GB                                     | 1         | 2      | 1.59%   |
| Toshiba MK4026GAX 40GB                                     | 1         | 1      | 1.59%   |
| Toshiba MK1629GSG 160GB                                    | 1         | 1      | 1.59%   |
| SK hynix SH920 mSATA 256GB SSD                             | 1         | 1      | 1.59%   |
| SK hynix SC210 mSATA 128GB SSD                             | 1         | 1      | 1.59%   |
| Seagate ST9750420AS 752GB                                  | 1         | 1      | 1.59%   |
| Seagate ST9100824AS 100GB                                  | 1         | 1      | 1.59%   |
| Seagate ST320LT007-9ZV142 320GB                            | 1         | 1      | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB                             | 1         | 1      | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB                             | 1         | 2      | 1.59%   |
| Seagate ST1000LM014-1EJ164 1TB                             | 1         | 1      | 1.59%   |
| SanDisk SSD PLUS 480GB                                     | 1         | 1      | 1.59%   |
| SanDisk SD9SN8W 128GB SSD                                  | 1         | 1      | 1.59%   |
| SanDisk SD7SB2Q512G1001 512GB SSD                          | 1         | 1      | 1.59%   |
| Samsung Electronics SSD SM841 mSATA 512GB                  | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 870 EVO 2TB                        | 1         | 1      | 1.59%   |
| Samsung Electronics HM160HC 160GB                          | 1         | 1      | 1.59%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 1024GB | 1         | 2      | 1.59%   |
| LITEON CV8-8E128-HP 128GB SSD                              | 1         | 2      | 1.59%   |
| Kingston Technology Company KC2000 NVMe SSD 2TB            | 1         | 1      | 1.59%   |
| Intel SSDSCKKF256G8H 256GB                                 | 1         | 1      | 1.59%   |
| Intel SSDSC2BW480A4 480GB                                  | 1         | 1      | 1.59%   |
| Intel SSDSC2BW180A3L 180GB                                 | 1         | 1      | 1.59%   |
| Intel SSDPEKKF256G8L 256GB                                 | 1         | 1      | 1.59%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB                          | 1         | 1      | 1.59%   |
| Hitachi HTS723225L9SA62 250GB                              | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 10        | 12     | 16.13%  |
| HGST                        | 8         | 9      | 12.9%   |
| WDC                         | 5         | 6      | 8.06%   |
| Toshiba                     | 5         | 6      | 8.06%   |
| Samsung Electronics         | 5         | 5      | 8.06%   |
| SK hynix                    | 4         | 4      | 6.45%   |
| SanDisk                     | 4         | 5      | 6.45%   |
| Intel                       | 4         | 4      | 6.45%   |
| Hitachi                     | 4         | 4      | 6.45%   |
| Kingston                    | 3         | 3      | 4.84%   |
| Fujitsu                     | 3         | 3      | 4.84%   |
| A-DATA Technology           | 2         | 2      | 3.23%   |
| Realtek Semiconductor       | 1         | 2      | 1.61%   |
| LITEON                      | 1         | 2      | 1.61%   |
| Kingston Technology Company | 1         | 1      | 1.61%   |
| IBM/Hitachi                 | 1         | 1      | 1.61%   |
| Crucial                     | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 28.57%  |
| HGST                | 8         | 9      | 22.86%  |
| WDC                 | 4         | 5      | 11.43%  |
| Toshiba             | 4         | 5      | 11.43%  |
| Hitachi             | 4         | 4      | 11.43%  |
| Fujitsu             | 3         | 3      | 8.57%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| IBM/Hitachi         | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 40     | 56.45%  |
| SSD  | 23        | 25     | 37.1%   |
| NVMe | 4         | 5      | 6.45%   |

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
| Works    | 488       | 828    | 77.22%  |
| Detected | 81        | 114    | 12.82%  |
| Malfunc  | 61        | 70     | 9.65%   |
| Failed   | 2         | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 348       | 46.9%   |
| Samsung Electronics              | 126       | 16.98%  |
| AMD                              | 76        | 10.24%  |
| SanDisk                          | 65        | 8.76%   |
| SK hynix                         | 38        | 5.12%   |
| Toshiba America Info Systems     | 20        | 2.7%    |
| Kingston Technology Company      | 14        | 1.89%   |
| Micron Technology                | 13        | 1.75%   |
| KIOXIA                           | 11        | 1.48%   |
| Phison Electronics               | 7         | 0.94%   |
| Micron/Crucial Technology        | 3         | 0.4%    |
| Lite-On Technology               | 3         | 0.4%    |
| Union Memory (Shenzhen)          | 2         | 0.27%   |
| Silicon Motion                   | 2         | 0.27%   |
| Nvidia                           | 2         | 0.27%   |
| Lenovo                           | 2         | 0.27%   |
| JMicron Technology               | 2         | 0.27%   |
| Apple                            | 2         | 0.27%   |
| Yangtze Memory Technologies      | 1         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| Seagate Technology               | 1         | 0.13%   |
| Realtek Semiconductor            | 1         | 0.13%   |
| ADATA Technology                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72        | 9.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 70        | 9.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 44        | 5.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 38        | 4.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 26        | 3.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 24        | 3.09%   |
| Samsung NVMe SSD Controller 980                                                | 22        | 2.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 2.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 20        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 20        | 2.58%   |
| Intel SSD 660P Series                                                          | 19        | 2.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 2.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 2.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 1.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 1.8%    |
| Micron Non-Volatile memory controller                                          | 13        | 1.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.16%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 9         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.16%   |
| SanDisk Non-Volatile memory controller                                         | 8         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 8         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 1.03%   |
| SK hynix Non-Volatile memory controller                                        | 7         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.9%    |
| Intel Non-Volatile memory controller                                           | 7         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.9%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 6         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 0.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 0.77%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 5         | 0.64%   |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 340       | 45.82%  |
| NVMe | 325       | 43.8%   |
| RAID | 44        | 5.93%   |
| IDE  | 33        | 4.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 431       | 74.96%  |
| AMD          | 141       | 24.52%  |
| PowerBook5,6 | 1         | 0.17%   |
| PowerBook5,4 | 1         | 0.17%   |
| PowerBook3,4 | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 20        | 3.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 3.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 2.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 2.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 2.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 2.26%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 2.26%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 2.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 2.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.91%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 1.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.39%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 8         | 1.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.22%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 1.04%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.04%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 5         | 0.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.87%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.87%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 4         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.7%    |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 192       | 33.39%  |
| Intel Core i5           | 108       | 18.78%  |
| Other                   | 55        | 9.57%   |
| AMD Ryzen 7             | 54        | 9.39%   |
| AMD Ryzen 5             | 27        | 4.7%    |
| AMD Ryzen 7 PRO         | 19        | 3.3%    |
| Intel Core 2 Duo        | 12        | 2.09%   |
| Intel Celeron           | 12        | 2.09%   |
| AMD Ryzen 9             | 11        | 1.91%   |
| Intel Atom              | 10        | 1.74%   |
| Intel Core i9           | 9         | 1.57%   |
| Intel Pentium M         | 8         | 1.39%   |
| Intel Core i3           | 8         | 1.39%   |
| AMD Ryzen 3             | 8         | 1.39%   |
| Intel Pentium           | 7         | 1.22%   |
| AMD A6                  | 5         | 0.87%   |
| Intel Xeon              | 4         | 0.7%    |
| AMD Ryzen 5 PRO         | 4         | 0.7%    |
| Intel Core m3           | 3         | 0.52%   |
| AMD A8                  | 3         | 0.52%   |
| Intel Genuine           | 2         | 0.35%   |
| AMD E1                  | 2         | 0.35%   |
| Intel Pentium Silver    | 1         | 0.17%   |
| Intel Pentium 4         | 1         | 0.17%   |
| Intel Core Duo          | 1         | 0.17%   |
| Intel Core 2            | 1         | 0.17%   |
| Intel Celeron M         | 1         | 0.17%   |
| AMD Turion II Dual-Core | 1         | 0.17%   |
| AMD E                   | 1         | 0.17%   |
| AMD Athlon Neo X2       | 1         | 0.17%   |
| AMD Athlon 64           | 1         | 0.17%   |
| AMD Athlon              | 1         | 0.17%   |
| AMD A12                 | 1         | 0.17%   |
| AMD A10                 | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 228       | 39.65%  |
| 2       | 144       | 25.04%  |
| 8       | 96        | 16.7%   |
| 6       | 74        | 12.87%  |
| 1       | 20        | 3.48%   |
| 14      | 6         | 1.04%   |
| 12      | 5         | 0.87%   |
| Unknown | 2         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 573       | 99.65%  |
| Unknown | 2         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 483       | 83.85%  |
| 1       | 91        | 15.8%   |
| Unknown | 2         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 552       | 96%     |
| 32-bit         | 20        | 3.48%   |
| Unknown        | 3         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 12.16%  |
| 0x906ea    | 44        | 7.43%   |
| 0x806ec    | 32        | 5.41%   |
| 0x806ea    | 32        | 5.41%   |
| 0x0a50000c | 27        | 4.56%   |
| 0x206a7    | 23        | 3.89%   |
| 0x08600106 | 22        | 3.72%   |
| 0x806c1    | 21        | 3.55%   |
| 0x506e3    | 20        | 3.38%   |
| 0x306a9    | 19        | 3.21%   |
| 0x806e9    | 18        | 3.04%   |
| 0x806d1    | 16        | 2.7%    |
| 0x08108109 | 16        | 2.7%    |
| 0xa0652    | 15        | 2.53%   |
| 0x40651    | 15        | 2.53%   |
| 0x08600103 | 14        | 2.36%   |
| 0x906e9    | 12        | 2.03%   |
| 0x406e3    | 12        | 2.03%   |
| 0x906ed    | 11        | 1.86%   |
| 0x306d4    | 11        | 1.86%   |
| 0x306c3    | 11        | 1.86%   |
| 0x906a3    | 10        | 1.69%   |
| 0x08108102 | 9         | 1.52%   |
| 0x30678    | 8         | 1.35%   |
| 0x08608103 | 8         | 1.35%   |
| 0x806eb    | 7         | 1.18%   |
| 0x08600104 | 6         | 1.01%   |
| 0x706e5    | 5         | 0.84%   |
| 0x6d8      | 5         | 0.84%   |
| 0x1067a    | 4         | 0.68%   |
| 0x706a1    | 3         | 0.51%   |
| 0x6fb      | 3         | 0.51%   |
| 0x406c4    | 3         | 0.51%   |
| 0x20655    | 3         | 0.51%   |
| 0x106c2    | 3         | 0.51%   |
| 0x10676    | 3         | 0.51%   |
| 0x0a404102 | 3         | 0.51%   |
| 0x08600102 | 3         | 0.51%   |
| 0x06003106 | 3         | 0.51%   |
| 0x806c2    | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 177       | 30.68%  |
| Zen 2            | 50        | 8.67%   |
| Skylake          | 34        | 5.89%   |
| Zen 3            | 30        | 5.2%    |
| Haswell          | 29        | 5.03%   |
| Zen+             | 26        | 4.51%   |
| TigerLake        | 25        | 4.33%   |
| SandyBridge      | 25        | 4.33%   |
| Icelake          | 23        | 3.99%   |
| Unknown          | 23        | 3.99%   |
| IvyBridge        | 20        | 3.47%   |
| CometLake        | 16        | 2.77%   |
| Broadwell        | 14        | 2.43%   |
| Silvermont       | 12        | 2.08%   |
| P6               | 12        | 2.08%   |
| Alderlake Hybrid | 10        | 1.73%   |
| Westmere         | 7         | 1.21%   |
| Penryn           | 7         | 1.21%   |
| Core             | 6         | 1.04%   |
| Bonnell          | 6         | 1.04%   |
| Zen              | 4         | 0.69%   |
| Goldmont plus    | 4         | 0.69%   |
| Steamroller      | 3         | 0.52%   |
| Bobcat           | 3         | 0.52%   |
| Puma             | 2         | 0.35%   |
| K8 Hammer        | 2         | 0.35%   |
| K10 Llano        | 2         | 0.35%   |
| Excavator        | 2         | 0.35%   |
| NetBurst         | 1         | 0.17%   |
| Jaguar           | 1         | 0.17%   |
| Goldmont         | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 387       | 50.65%  |
| Nvidia | 219       | 28.66%  |
| AMD    | 158       | 20.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 52        | 6.61%   |
| AMD Renoir                                                                    | 46        | 5.84%   |
| Intel UHD Graphics 620                                                        | 38        | 4.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 26        | 3.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 25        | 3.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 25        | 3.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 25        | 3.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 23        | 2.92%   |
| Intel HD Graphics 530                                                         | 19        | 2.41%   |
| Intel HD Graphics 620                                                         | 17        | 2.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 17        | 2.16%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 17        | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 16        | 2.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 14        | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 14        | 1.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 14        | 1.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 13        | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 13        | 1.65%   |
| Intel HD Graphics 5500                                                        | 12        | 1.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 11        | 1.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 10        | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 10        | 1.27%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 10        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 10        | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                 | 9         | 1.14%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 9         | 1.14%   |
| Intel HD Graphics 630                                                         | 9         | 1.14%   |
| AMD Lucienne                                                                  | 9         | 1.14%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 8         | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 8         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 7         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 6         | 0.76%   |
| Nvidia TU117M                                                                 | 6         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 6         | 0.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                   | 5         | 0.64%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 5         | 0.64%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 4         | 0.51%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 4         | 0.51%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 4         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 210       | 36.27%  |
| Intel + Nvidia | 156       | 26.94%  |
| 1 x AMD        | 114       | 19.69%  |
| 1 x Nvidia     | 46        | 7.94%   |
| AMD + Nvidia   | 18        | 3.11%   |
| Intel + AMD    | 14        | 2.42%   |
| 2 x AMD        | 13        | 2.25%   |
| 2 x Intel      | 7         | 1.21%   |
| 2 x Nvidia     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 456       | 77.03%  |
| Proprietary | 116       | 19.59%  |
| Unknown     | 20        | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 336       | 56.66%  |
| 0.01-0.5   | 86        | 14.5%   |
| 1.01-2.0   | 61        | 10.29%  |
| 3.01-4.0   | 47        | 7.93%   |
| 0.51-1.0   | 21        | 3.54%   |
| 5.01-6.0   | 18        | 3.04%   |
| 7.01-8.0   | 13        | 2.19%   |
| 8.01-16.0  | 8         | 1.35%   |
| 2.01-3.0   | 3         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 125       | 18.14%  |
| BOE                     | 98        | 14.22%  |
| LG Display              | 94        | 13.64%  |
| Chimei Innolux          | 74        | 10.74%  |
| Samsung Electronics     | 57        | 8.27%   |
| Sharp                   | 43        | 6.24%   |
| Dell                    | 36        | 5.22%   |
| Apple                   | 18        | 2.61%   |
| Lenovo                  | 15        | 2.18%   |
| Chi Mei Optoelectronics | 13        | 1.89%   |
| Hewlett-Packard         | 10        | 1.45%   |
| Goldstar                | 9         | 1.31%   |
| CSO                     | 9         | 1.31%   |
| PANDA                   | 8         | 1.16%   |
| Acer                    | 7         | 1.02%   |
| InfoVision              | 6         | 0.87%   |
| BenQ                    | 6         | 0.87%   |
| AOC                     | 6         | 0.87%   |
| Philips                 | 5         | 0.73%   |
| Iiyama                  | 5         | 0.73%   |
| Ancor Communications    | 5         | 0.73%   |
| ViewSonic               | 3         | 0.44%   |
| Eizo                    | 3         | 0.44%   |
| ASUSTek Computer        | 3         | 0.44%   |
| TMX                     | 2         | 0.29%   |
| Sony                    | 2         | 0.29%   |
| MSI                     | 2         | 0.29%   |
| LGD                     | 2         | 0.29%   |
| LG Philips              | 2         | 0.29%   |
| HannStar                | 2         | 0.29%   |
| Gigabyte Technology     | 2         | 0.29%   |
| Fujitsu Siemens         | 2         | 0.29%   |
| CMN                     | 2         | 0.29%   |
| Xiaomi                  | 1         | 0.15%   |
| WST                     | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| RTK                     | 1         | 0.15%   |
| QBell                   | 1         | 0.15%   |
| Mi                      | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 1.15%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.15%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 7         | 1%      |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 7         | 1%      |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.72%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.72%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.43%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 3         | 0.43%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 3         | 0.43%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.43%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 3         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 3         | 0.43%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.43%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.43%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                     | 3         | 0.43%   |
| Dell U2414H DELA0A3 1920x1080 530x300mm 24.0-inch                     | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.43%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 3         | 0.43%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                 | 3         | 0.43%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.43%   |
| BOE LCD Monitor BOE082B 1920x1080 309x174mm 14.0-inch                 | 3         | 0.43%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 3         | 0.43%   |
| Apple Color LCD APP9C20 1280x854 321x214mm 15.2-inch                  | 3         | 0.43%   |
| Acer T232HL ACR041F 1920x1080 509x286mm 23.0-inch                     | 3         | 0.43%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 2         | 0.29%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 344       | 53.92%  |
| 1366x768 (WXGA)    | 70        | 10.97%  |
| 3840x2160 (4K)     | 40        | 6.27%   |
| 2560x1440 (QHD)    | 34        | 5.33%   |
| 1600x900 (HD+)     | 18        | 2.82%   |
| 1920x1200 (WUXGA)  | 15        | 2.35%   |
| 3840x2400          | 14        | 2.19%   |
| 2560x1600          | 14        | 2.19%   |
| 1280x800 (WXGA)    | 11        | 1.72%   |
| 1440x900 (WXGA+)   | 10        | 1.57%   |
| 1680x1050 (WSXGA+) | 9         | 1.41%   |
| 3440x1440          | 7         | 1.1%    |
| 2880x1800          | 6         | 0.94%   |
| 1024x600           | 6         | 0.94%   |
| 2160x1440          | 4         | 0.63%   |
| 1280x1024 (SXGA)   | 4         | 0.63%   |
| 3200x1800 (QHD+)   | 3         | 0.47%   |
| 1280x854           | 3         | 0.47%   |
| 3840x1080          | 2         | 0.31%   |
| 3200x2000          | 2         | 0.31%   |
| 2256x1504          | 2         | 0.31%   |
| 2048x1152          | 2         | 0.31%   |
| Unknown            | 2         | 0.31%   |
| 800x1280           | 1         | 0.16%   |
| 5040x1080          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3840x1100          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2520x1680          | 1         | 0.16%   |
| 2304x1440          | 1         | 0.16%   |
| 2288x1287          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| 1280x768           | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 255       | 37.28%  |
| 13      | 100       | 14.62%  |
| 14      | 79        | 11.55%  |
| 17      | 47        | 6.87%   |
| 27      | 38        | 5.56%   |
| 12      | 27        | 3.95%   |
| 24      | 26        | 3.8%    |
| 23      | 20        | 2.92%   |
| 16      | 15        | 2.19%   |
| 21      | 13        | 1.9%    |
| 11      | 10        | 1.46%   |
| Unknown | 8         | 1.17%   |
| 34      | 7         | 1.02%   |
| 22      | 5         | 0.73%   |
| 19      | 5         | 0.73%   |
| 10      | 4         | 0.58%   |
| 31      | 3         | 0.44%   |
| 25      | 3         | 0.44%   |
| 18      | 3         | 0.44%   |
| 58      | 2         | 0.29%   |
| 8       | 2         | 0.29%   |
| 142     | 1         | 0.15%   |
| 75      | 1         | 0.15%   |
| 72      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 54      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
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
| 301-350        | 386       | 57.1%   |
| 201-300        | 96        | 14.2%   |
| 501-600        | 79        | 11.69%  |
| 351-400        | 52        | 7.69%   |
| 401-500        | 27        | 3.99%   |
| 601-700        | 8         | 1.18%   |
| Unknown        | 8         | 1.18%   |
| 701-800        | 7         | 1.04%   |
| 1001-1500      | 7         | 1.04%   |
| 1501-2000      | 2         | 0.3%    |
| 101-200        | 2         | 0.3%    |
| More than 2000 | 1         | 0.15%   |
| 801-900        | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 472       | 79.19%  |
| 16/10   | 84        | 14.09%  |
| 3/2     | 15        | 2.52%   |
| 21/9    | 7         | 1.17%   |
| Unknown | 6         | 1.01%   |
| 4/3     | 4         | 0.67%   |
| 5/4     | 3         | 0.5%    |
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
| 101-110        | 253       | 36.99%  |
| 81-90          | 130       | 19.01%  |
| 71-80          | 49        | 7.16%   |
| 201-250        | 48        | 7.02%   |
| 121-130        | 42        | 6.14%   |
| 301-350        | 39        | 5.7%    |
| 61-70          | 25        | 3.65%   |
| 111-120        | 16        | 2.34%   |
| 251-300        | 14        | 2.05%   |
| 51-60          | 11        | 1.61%   |
| 351-500        | 11        | 1.61%   |
| 151-200        | 9         | 1.32%   |
| More than 1000 | 8         | 1.17%   |
| Unknown        | 8         | 1.17%   |
| 41-50          | 4         | 0.58%   |
| 141-150        | 4         | 0.58%   |
| 131-140        | 4         | 0.58%   |
| 91-100         | 4         | 0.58%   |
| 501-1000       | 3         | 0.44%   |
| 1-40           | 2         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 321       | 47.84%  |
| 101-120       | 103       | 15.35%  |
| 51-100        | 95        | 14.16%  |
| 161-240       | 87        | 12.97%  |
| More than 240 | 50        | 7.45%   |
| Unknown       | 8         | 1.19%   |
| 1-50          | 7         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 454       | 75.67%  |
| 2     | 109       | 18.17%  |
| 0     | 21        | 3.5%    |
| 3     | 16        | 2.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 382       | 42.4%   |
| Realtek Semiconductor             | 283       | 31.41%  |
| Qualcomm Atheros                  | 88        | 9.77%   |
| Broadcom                          | 31        | 3.44%   |
| MediaTek                          | 14        | 1.55%   |
| Lenovo                            | 12        | 1.33%   |
| ASIX Electronics                  | 10        | 1.11%   |
| Marvell Technology Group          | 9         | 1%      |
| Dell                              | 8         | 0.89%   |
| Sierra Wireless                   | 6         | 0.67%   |
| Qualcomm                          | 6         | 0.67%   |
| Ericsson Business Mobile Networks | 5         | 0.55%   |
| Apple                             | 5         | 0.55%   |
| Samsung Electronics               | 4         | 0.44%   |
| Fibocom                           | 4         | 0.44%   |
| Broadcom Limited                  | 4         | 0.44%   |
| TP-Link                           | 3         | 0.33%   |
| Qualcomm Atheros Communications   | 3         | 0.33%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.22%   |
| Xiaomi                            | 2         | 0.22%   |
| Ralink Technology                 | 2         | 0.22%   |
| Ralink                            | 2         | 0.22%   |
| D-Link System                     | 2         | 0.22%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 194       | 17.57%  |
| Intel Wi-Fi 6 AX200                                                     | 67        | 6.07%   |
| Intel Wireless 8265 / 8275                                              | 45        | 4.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 34        | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.81%   |
| Intel Wireless 7265                                                     | 20        | 1.81%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.54%   |
| Intel Wireless 7260                                                     | 16        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                   | 16        | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.36%   |
| Intel Wireless 8260                                                     | 15        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.09%   |
| Intel Wireless 3165                                                     | 12        | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                    | 12        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                          | 11        | 1%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 10        | 0.91%   |
| Intel Ethernet Connection (6) I219-V                                    | 10        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                   | 8         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 7         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.63%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                   | 7         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 373       | 62.48%  |
| Realtek Semiconductor           | 76        | 12.73%  |
| Qualcomm Atheros                | 71        | 11.89%  |
| Broadcom                        | 26        | 4.36%   |
| MediaTek                        | 13        | 2.18%   |
| Sierra Wireless                 | 6         | 1.01%   |
| Qualcomm                        | 6         | 1.01%   |
| Dell                            | 6         | 1.01%   |
| Fibocom                         | 4         | 0.67%   |
| Qualcomm Atheros Communications | 3         | 0.5%    |
| TP-Link                         | 2         | 0.34%   |
| Ralink Technology               | 2         | 0.34%   |
| Ralink                          | 2         | 0.34%   |
| D-Link System                   | 2         | 0.34%   |
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
| Intel Wi-Fi 6 AX200                                                     | 67        | 11.19%  |
| Intel Wireless 8265 / 8275                                              | 45        | 7.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 5.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 3.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 3.34%   |
| Intel Wireless 7265                                                     | 20        | 3.34%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 3.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 3.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 2.84%   |
| Intel Wireless 7260                                                     | 16        | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.5%    |
| Intel Wireless 8260                                                     | 15        | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 2%      |
| Intel Wireless 3165                                                     | 12        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 1.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 11        | 1.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 7         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1%      |
| Intel Wireless-AC 9260                                                  | 6         | 1%      |
| Intel Centrino Advanced-N 6235                                          | 6         | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.67%   |
| Intel Wireless 3160                                                     | 4         | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.67%   |
| Sierra Wireless EM7455                                                  | 3         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.5%    |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 255       | 53.46%  |
| Intel                            | 128       | 26.83%  |
| Qualcomm Atheros                 | 27        | 5.66%   |
| Broadcom                         | 13        | 2.73%   |
| Lenovo                           | 12        | 2.52%   |
| ASIX Electronics                 | 10        | 2.1%    |
| Marvell Technology Group         | 9         | 1.89%   |
| Apple                            | 5         | 1.05%   |
| Samsung Electronics              | 3         | 0.63%   |
| Broadcom Limited                 | 3         | 0.63%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.42%   |
| Xiaomi                           | 2         | 0.42%   |
| TP-Link                          | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Nvidia                           | 1         | 0.21%   |
| JMicron Technology               | 1         | 0.21%   |
| ICS Advent                       | 1         | 0.21%   |
| Huawei Technologies              | 1         | 0.21%   |
| Google                           | 1         | 0.21%   |
| Aquantia                         | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 194       | 40.08%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 7.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 4.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 3.31%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 2.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 2.07%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 2.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.83%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.83%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.83%   |
| Intel Ethernet Connection (14) I219-LM                            | 4         | 0.83%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.62%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.41%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.41%   |
| Intel Ethernet Connection (5) I219-V                              | 2         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.41%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 568       | 54.56%  |
| Ethernet | 452       | 43.42%  |
| Modem    | 20        | 1.92%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 449       | 70.82%  |
| Ethernet | 185       | 29.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 391       | 67.88%  |
| 1     | 171       | 29.69%  |
| 3     | 12        | 2.08%   |
| 0     | 2         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 507       | 85.79%  |
| Yes  | 84        | 14.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 317       | 63.15%  |
| Realtek Semiconductor           | 46        | 9.16%   |
| Qualcomm Atheros Communications | 22        | 4.38%   |
| Lite-On Technology              | 18        | 3.59%   |
| IMC Networks                    | 16        | 3.19%   |
| Foxconn / Hon Hai               | 15        | 2.99%   |
| Apple                           | 15        | 2.99%   |
| Broadcom                        | 12        | 2.39%   |
| Realtek                         | 8         | 1.59%   |
| Dell                            | 8         | 1.59%   |
| Cambridge Silicon Radio         | 6         | 1.2%    |
| Toshiba                         | 4         | 0.8%    |
| Hewlett-Packard                 | 4         | 0.8%    |
| ASUSTek Computer                | 3         | 0.6%    |
| Foxconn International           | 2         | 0.4%    |
| USI                             | 1         | 0.2%    |
| Ralink Technology               | 1         | 0.2%    |
| Opticis                         | 1         | 0.2%    |
| Chicony Electronics             | 1         | 0.2%    |
| Askey Computer                  | 1         | 0.2%    |
| Actiontec Electronics           | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 108       | 21.51%  |
| Intel AX200 Bluetooth                               | 64        | 12.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 57        | 11.35%  |
| Intel AX201 Bluetooth                               | 54        | 10.76%  |
| Realtek Bluetooth Radio                             | 28        | 5.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 2.59%   |
| Intel AX210 Bluetooth                               | 11        | 2.19%   |
| Apple Bluetooth Host Controller                     | 10        | 1.99%   |
| Realtek Bluetooth Radio                             | 8         | 1.59%   |
| Intel Bluetooth Device                              | 8         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.39%   |
| IMC Networks Wireless_Device                        | 7         | 1.39%   |
| Lite-On Bluetooth Device                            | 6         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.2%    |
| IMC Networks Bluetooth Radio                        | 6         | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.2%    |
| Realtek RTL8723B Bluetooth                          | 5         | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.8%    |
| IMC Networks Bluetooth Device                       | 3         | 0.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.6%    |
| Dell DW375 Bluetooth Module                         | 3         | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.6%    |
| Apple Bluetooth HCI                                 | 3         | 0.6%    |
| Toshiba RT Bluetooth Radio                          | 2         | 0.4%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 2         | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.4%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 2         | 0.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.4%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.4%    |
| ASUS Broadcom Bluetooth 2.1                         | 2         | 0.4%    |
| Apple Bluetooth USB Host Controller                 | 2         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 424       | 54.29%  |
| AMD                                  | 146       | 18.69%  |
| Nvidia                               | 134       | 17.16%  |
| Lenovo                               | 12        | 1.54%   |
| Realtek Semiconductor                | 8         | 1.02%   |
| C-Media Electronics                  | 6         | 0.77%   |
| Plantronics                          | 4         | 0.51%   |
| Logitech                             | 3         | 0.38%   |
| Kingston Technology                  | 3         | 0.38%   |
| Dell                                 | 3         | 0.38%   |
| Blue Microphones                     | 3         | 0.38%   |
| Razer USA                            | 2         | 0.26%   |
| No brand                             | 2         | 0.26%   |
| Hewlett-Packard                      | 2         | 0.26%   |
| GYROCOM C&C                          | 2         | 0.26%   |
| GN Netcom                            | 2         | 0.26%   |
| Generalplus Technology               | 2         | 0.26%   |
| Creative Technology                  | 2         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.13%   |
| Texas Instruments                    | 1         | 0.13%   |
| Tdlasunnic                           | 1         | 0.13%   |
| Synaptics                            | 1         | 0.13%   |
| SteelSeries ApS                      | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.13%   |
| Sennheiser Communications            | 1         | 0.13%   |
| Samson Technologies                  | 1         | 0.13%   |
| RODE Microphones                     | 1         | 0.13%   |
| LG Electronics                       | 1         | 0.13%   |
| JMTek                                | 1         | 0.13%   |
| iCreate Technologies                 | 1         | 0.13%   |
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
| AMD Family 17h/19h HD Audio Controller                                     | 120       | 12.7%   |
| Intel Sunrise Point-LP HD Audio                                            | 73        | 7.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71        | 7.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 61        | 6.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 2.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 24        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 2.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 2.12%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 17        | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.69%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 15        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 1.48%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 1.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 1.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 13        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 1.06%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.06%   |
| Realtek Semiconductor USB Audio                                            | 8         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.85%   |
| Nvidia TU104 HD Audio Controller                                           | 8         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 210       | 32.16%  |
| SK hynix                     | 146       | 22.36%  |
| Micron Technology            | 89        | 13.63%  |
| Kingston                     | 53        | 8.12%   |
| Unknown                      | 36        | 5.51%   |
| Crucial                      | 34        | 5.21%   |
| Ramaxel Technology           | 13        | 1.99%   |
| Corsair                      | 9         | 1.38%   |
| A-DATA Technology            | 9         | 1.38%   |
| Elpida                       | 7         | 1.07%   |
| Transcend                    | 6         | 0.92%   |
| Team                         | 6         | 0.92%   |
| Nanya Technology             | 5         | 0.77%   |
| G.Skill                      | 5         | 0.77%   |
| Patriot                      | 4         | 0.61%   |
| Goodram                      | 4         | 0.61%   |
| Unknown (ABCD)               | 2         | 0.31%   |
| Timetec                      | 2         | 0.31%   |
| AMD                          | 2         | 0.31%   |
| Unknown                      | 2         | 0.31%   |
| Unknown (0x5D00000000000000) | 1         | 0.15%   |
| Teikon                       | 1         | 0.15%   |
| Saikano                      | 1         | 0.15%   |
| Magnum Tech                  | 1         | 0.15%   |
| KLEVV                        | 1         | 0.15%   |
| Goldkey                      | 1         | 0.15%   |
| Avant                        | 1         | 0.15%   |
| Apacer                       | 1         | 0.15%   |
| 48spaces                     | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 11        | 1.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 10        | 1.46%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 9         | 1.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 9         | 1.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 9         | 1.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 8         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 8         | 1.16%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 8         | 1.16%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 1.16%   |
| Unknown RAM Module 1GB SODIMM DDR                             | 7         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 1.02%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 7         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 7         | 1.02%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s        | 7         | 1.02%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 7         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 7         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 6         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 6         | 0.87%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 5         | 0.73%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 5         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.73%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 5         | 0.73%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.73%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s         | 5         | 0.73%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 5         | 0.73%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s       | 5         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 4         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 4         | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 4         | 0.58%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s      | 4         | 0.58%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 4         | 0.58%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 4         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 4         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 344       | 62.09%  |
| DDR3    | 122       | 22.02%  |
| LPDDR4  | 26        | 4.69%   |
| LPDDR3  | 19        | 3.43%   |
| DDR2    | 15        | 2.71%   |
| DDR     | 10        | 1.81%   |
| SDRAM   | 5         | 0.9%    |
| DDR5    | 5         | 0.9%    |
| LPDDR5  | 4         | 0.72%   |
| Unknown | 3         | 0.54%   |
| DRAM    | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 494       | 88.85%  |
| Row Of Chips | 55        | 9.89%   |
| Chip         | 5         | 0.9%    |
| DIMM         | 2         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 255       | 42.5%   |
| 16384 | 131       | 21.83%  |
| 4096  | 116       | 19.33%  |
| 2048  | 39        | 6.5%    |
| 32768 | 33        | 5.5%    |
| 1024  | 19        | 3.17%   |
| 512   | 4         | 0.67%   |
| 256   | 3         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 162       | 26.96%  |
| 3200    | 141       | 23.46%  |
| 1600    | 87        | 14.48%  |
| 2400    | 40        | 6.66%   |
| 2133    | 37        | 6.16%   |
| 1333    | 17        | 2.83%   |
| Unknown | 14        | 2.33%   |
| 4267    | 12        | 2%      |
| 1334    | 12        | 2%      |
| 667     | 12        | 2%      |
| 4800    | 8         | 1.33%   |
| 1867    | 8         | 1.33%   |
| 8400    | 7         | 1.16%   |
| 3266    | 7         | 1.16%   |
| 1067    | 6         | 1%      |
| 6400    | 5         | 0.83%   |
| 800     | 5         | 0.83%   |
| 3733    | 4         | 0.67%   |
| 4266    | 3         | 0.5%    |
| 2933    | 3         | 0.5%    |
| 533     | 3         | 0.5%    |
| 3000    | 2         | 0.33%   |
| 400     | 2         | 0.33%   |
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
| Chicony Electronics                    | 133       | 26.65%  |
| IMC Networks                           | 71        | 14.23%  |
| Microdia                               | 45        | 9.02%   |
| Realtek Semiconductor                  | 42        | 8.42%   |
| Acer                                   | 40        | 8.02%   |
| Sunplus Innovation Technology          | 27        | 5.41%   |
| Quanta                                 | 20        | 4.01%   |
| Lite-On Technology                     | 20        | 4.01%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 4.01%   |
| Syntek                                 | 12        | 2.4%    |
| Logitech                               | 10        | 2%      |
| Apple                                  | 10        | 2%      |
| Luxvisions Innotech Limited            | 8         | 1.6%    |
| Samsung Electronics                    | 5         | 1%      |
| DigiTech                               | 4         | 0.8%    |
| Z-Star Microelectronics                | 3         | 0.6%    |
| Suyin                                  | 3         | 0.6%    |
| Silicon Motion                         | 2         | 0.4%    |
| Microsoft                              | 2         | 0.4%    |
| LG Electronics                         | 2         | 0.4%    |
| DJKANA19IDX53W                         | 2         | 0.4%    |
| Alcor Micro                            | 2         | 0.4%    |
| USB3.0 HD Audio Capture                | 1         | 0.2%    |
| Sonix Technology                       | 1         | 0.2%    |
| ShineTech                              | 1         | 0.2%    |
| S1F0009330LB620L4100030N               | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| Razer USA                              | 1         | 0.2%    |
| Omnivision                             | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| Intel                                  | 1         | 0.2%    |
| Holitech                               | 1         | 0.2%    |
| Hewlett-Packard                        | 1         | 0.2%    |
| Google                                 | 1         | 0.2%    |
| Genesys Logic                          | 1         | 0.2%    |
| Cubeternet                             | 1         | 0.2%    |
| AVer Information                       | 1         | 0.2%    |
| Aveo Technology                        | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 40        | 7.91%   |
| Microdia Integrated_Webcam_HD                                  | 31        | 6.13%   |
| IMC Networks Integrated Camera                                 | 30        | 5.93%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 4.15%   |
| Acer Integrated Camera                                         | 17        | 3.36%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 16        | 3.16%   |
| Chicony HD WebCam                                              | 15        | 2.96%   |
| Sunplus Integrated_Webcam_HD                                   | 10        | 1.98%   |
| Chicony HP HD Camera                                           | 10        | 1.98%   |
| Chicony USB2.0 Camera                                          | 9         | 1.78%   |
| Lite-On Integrated Camera                                      | 8         | 1.58%   |
| Syntek Integrated Camera                                       | 7         | 1.38%   |
| Sunplus HD WebCam                                              | 5         | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 5         | 0.99%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 0.99%   |
| Chicony HD User Facing                                         | 5         | 0.99%   |
| Apple FaceTime HD Camera                                       | 5         | 0.99%   |
| Acer SunplusIT Integrated Camera                               | 5         | 0.99%   |
| Quanta HP Wide Vision HD Camera                                | 4         | 0.79%   |
| Quanta HD User Facing                                          | 4         | 0.79%   |
| Microdia Integrated Webcam                                     | 4         | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.79%   |
| Logitech HD Pro Webcam C920                                    | 4         | 0.79%   |
| Lite-On TOSHIBA Web Camera - HD                                | 4         | 0.79%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 4         | 0.79%   |
| IMC Networks ov9734_azurewave_camera                           | 4         | 0.79%   |
| Chicony ThinkPad T490 Webcam                                   | 4         | 0.79%   |
| Chicony Lenovo EasyCamera                                      | 4         | 0.79%   |
| Chicony EasyCamera                                             | 4         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 4         | 0.79%   |
| Acer BisonCam, NB Pro                                          | 4         | 0.79%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.59%   |
| Sunplus HP Wide Vision HD                                      | 3         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                                   | 3         | 0.59%   |
| Realtek USB Camera                                             | 3         | 0.59%   |
| Realtek Integrated Webcam HD                                   | 3         | 0.59%   |
| Realtek Integrated Webcam                                      | 3         | 0.59%   |
| Quanta HD Webcam                                               | 3         | 0.59%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 3         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 55        | 46.61%  |
| Validity Sensors           | 25        | 21.19%  |
| Shenzhen Goodix Technology | 18        | 15.25%  |
| Elan Microelectronics      | 8         | 6.78%   |
| STMicroelectronics         | 4         | 3.39%   |
| AuthenTec                  | 4         | 3.39%   |
| LighTuning Technology      | 3         | 2.54%   |
| Upek                       | 1         | 0.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 23        | 19.49%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 15        | 12.71%  |
| Shenzhen Goodix  Fingerprint Device                        | 9         | 7.63%   |
| Unknown                                                    | 8         | 6.78%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 5.93%   |
| Elan ELAN:Fingerprint                                      | 6         | 5.08%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 4.24%   |
| Validity Sensors Synaptics WBDI                            | 5         | 4.24%   |
| Shenzhen Goodix FingerPrint                                | 5         | 4.24%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 3.39%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 3.39%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 2.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.54%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 2         | 1.69%   |
| Elan ELAN:ARM-M4                                           | 2         | 1.69%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 0.85%   |
| Validity Sensors VFS491                                    | 1         | 0.85%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 0.85%   |
| Synaptics WBDI Device                                      | 1         | 0.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.85%   |
| AuthenTec Fingerprint Sensor                               | 1         | 0.85%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 35        | 45.45%  |
| Broadcom                  | 30        | 38.96%  |
| Upek                      | 4         | 5.19%   |
| O2 Micro                  | 3         | 3.9%    |
| Yubico.com                | 1         | 1.3%    |
| Purism, SPC               | 1         | 1.3%    |
| Microchip Technology      | 1         | 1.3%    |
| Gemalto (was Gemplus)     | 1         | 1.3%    |
| Aladdin Knowledge Systems | 1         | 1.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 45.45%  |
| Broadcom 5880                                                                | 10        | 12.99%  |
| Broadcom 58200                                                               | 10        | 12.99%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 7.79%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.19%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 5.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.6%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.3%    |
| Purism, SPC Librem Key                                                       | 1         | 1.3%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.3%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.3%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 211       | 32.81%  |
| 1     | 170       | 26.44%  |
| 2     | 107       | 16.64%  |
| 3     | 75        | 11.66%  |
| 4     | 43        | 6.69%   |
| 5     | 24        | 3.73%   |
| 6     | 10        | 1.56%   |
| 7     | 2         | 0.31%   |
| 8     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 151       | 16.34%  |
| Camera                   | 129       | 13.96%  |
| Bluetooth                | 123       | 13.31%  |
| Fingerprint reader       | 118       | 12.77%  |
| Graphics card            | 101       | 10.93%  |
| Chipcard                 | 63        | 6.82%   |
| Card reader              | 59        | 6.39%   |
| Net/wireless             | 52        | 5.63%   |
| Multimedia controller    | 50        | 5.41%   |
| Sound                    | 16        | 1.73%   |
| Modem                    | 14        | 1.52%   |
| Net/ethernet             | 11        | 1.19%   |
| Network                  | 10        | 1.08%   |
| Storage/ata              | 7         | 0.76%   |
| Storage                  | 5         | 0.54%   |
| Storage/ide              | 4         | 0.43%   |
| Firewire controller      | 4         | 0.43%   |
| Tv card                  | 2         | 0.22%   |
| Dvb card                 | 2         | 0.22%   |
| Wireless                 | 1         | 0.11%   |
| Storage/raid             | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |


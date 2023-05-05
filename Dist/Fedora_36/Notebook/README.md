Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 1641

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5521               | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Sony          | SVS13A25PXB                 | [a31acd0a66](https://linux-hardware.org/?probe=a31acd0a66) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Sony          | SVS13A25PXB                 | [06138dd58a](https://linux-hardware.org/?probe=06138dd58a) | Apr 24, 2023 |
| BTO           | 17X1183                     | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Acer          | Aspire E1-572               | [acf5e9b9f5](https://linux-hardware.org/?probe=acf5e9b9f5) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| Dell          | XPS 15 9520                 | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Dell          | Inspiron N5110              | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| HUAWEI        | HN-WX9X                     | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| HP            | Laptop 15-db1xxx            | [08df29b00e](https://linux-hardware.org/?probe=08df29b00e) | Mar 18, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| HP            | ProBook 450 G4              | [72af4386e5](https://linux-hardware.org/?probe=72af4386e5) | Mar 06, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [40516fd80e](https://linux-hardware.org/?probe=40516fd80e) | Mar 01, 2023 |
| Acer          | TravelMate P633-V           | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Acer          | Swift SF314-54              | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| Lenovo        | 3000 N200 0769BAG           | [f8f410eb2a](https://linux-hardware.org/?probe=f8f410eb2a) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| Lenovo        | IdeaPad S340-14IML 81N9     | [58e620077b](https://linux-hardware.org/?probe=58e620077b) | Jan 29, 2023 |
| Dell          | Latitude 7480               | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| Dell          | Latitude 3420               | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| HP            | ENVY Laptop 17-ce0xxx       | [1a0f3869dd](https://linux-hardware.org/?probe=1a0f3869dd) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Acer          | Nitro AN515-54              | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Apple         | MacBookPro11,3              | [c94f291c81](https://linux-hardware.org/?probe=c94f291c81) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [e78a057172](https://linux-hardware.org/?probe=e78a057172) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| HP            | ProBook 4520s               | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
| HP            | 240 G8                      | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| Dell          | XPS 15 9550                 | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Dell          | Inspiron 5580               | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Dell          | Latitude E7240              | [ca82922df4](https://linux-hardware.org/?probe=ca82922df4) | Jan 01, 2023 |
| Acer          | Aspire 4750                 | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [1c46a3fdd3](https://linux-hardware.org/?probe=1c46a3fdd3) | Dec 29, 2022 |
| MSI           | Modern 15 A5M               | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| MSI           | GT60                        | [3917ca13e3](https://linux-hardware.org/?probe=3917ca13e3) | Dec 26, 2022 |
| Samsung       | 550XBE/350XBE               | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Toshiba       | Satellite C75D-B            | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| Toshiba       | Satellite C850-C5K          | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| Acer          | Aspire A515-52              | [b052f8434a](https://linux-hardware.org/?probe=b052f8434a) | Dec 20, 2022 |
| MSI           | GL63 8RC                    | [6a5bc85513](https://linux-hardware.org/?probe=6a5bc85513) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| Dell          | XPS 15 9570                 | [b7b1ed9d8b](https://linux-hardware.org/?probe=b7b1ed9d8b) | Dec 12, 2022 |
| Samsung       | 930X5J/910S5J/940X5J        | [deb721084b](https://linux-hardware.org/?probe=deb721084b) | Dec 11, 2022 |
| Dell          | G5 5505                     | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [ad87e1559a](https://linux-hardware.org/?probe=ad87e1559a) | Dec 09, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Laptop 14-dk1xxx            | [1c73b61db3](https://linux-hardware.org/?probe=1c73b61db3) | Dec 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| HP            | Laptop 14-dk1xxx            | [3e50ee3f94](https://linux-hardware.org/?probe=3e50ee3f94) | Dec 07, 2022 |
| HP            | Laptop 17-ak0xx             | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | 245 G7                      | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [41a365e56e](https://linux-hardware.org/?probe=41a365e56e) | Dec 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [38d691df3b](https://linux-hardware.org/?probe=38d691df3b) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| HP            | EliteBook 820 G3            | [2414a84e4f](https://linux-hardware.org/?probe=2414a84e4f) | Dec 02, 2022 |
| HP            | EliteBook 8570w             | [a4ae0cdd6a](https://linux-hardware.org/?probe=a4ae0cdd6a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| Dell          | XPS 13 9300                 | [43fe4ed852](https://linux-hardware.org/?probe=43fe4ed852) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f96032f10](https://linux-hardware.org/?probe=0f96032f10) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| Dell          | Precision 5510              | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | [3b9a05e385](https://linux-hardware.org/?probe=3b9a05e385) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | [489ded27aa](https://linux-hardware.org/?probe=489ded27aa) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| HP            | Laptop 17-by0xxx            | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [f5cbe0bfa2](https://linux-hardware.org/?probe=f5cbe0bfa2) | Nov 19, 2022 |
| Lenovo        | Legion 5 82B5               | [907810c0ac](https://linux-hardware.org/?probe=907810c0ac) | Nov 18, 2022 |
| Exo           | Smart XS1                   | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| Dell          | Latitude 5530               | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| Dell          | XPS 15 9570                 | [69b281a787](https://linux-hardware.org/?probe=69b281a787) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [76d056b728](https://linux-hardware.org/?probe=76d056b728) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Alienware     | Area-51m                    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Acer          | Swift SF314-512             | [eb533b483e](https://linux-hardware.org/?probe=eb533b483e) | Nov 12, 2022 |
| Dell          | Latitude E6420              | [056daa7806](https://linux-hardware.org/?probe=056daa7806) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [68e5509696](https://linux-hardware.org/?probe=68e5509696) | Nov 11, 2022 |
| Dell          | XPS 15 9510                 | [2db7764d25](https://linux-hardware.org/?probe=2db7764d25) | Nov 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [f927960881](https://linux-hardware.org/?probe=f927960881) | Nov 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Monster       | ABRA A5 V15.6               | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [7973c1467f](https://linux-hardware.org/?probe=7973c1467f) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QQS44Q00     | [29ddbee669](https://linux-hardware.org/?probe=29ddbee669) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [17c345f111](https://linux-hardware.org/?probe=17c345f111) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | [d224ed7da8](https://linux-hardware.org/?probe=d224ed7da8) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S24N00    | [0b17fc5246](https://linux-hardware.org/?probe=0b17fc5246) | Nov 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | [33b2dbfcc2](https://linux-hardware.org/?probe=33b2dbfcc2) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | [265707c6a3](https://linux-hardware.org/?probe=265707c6a3) | Nov 08, 2022 |
| HP            | Notebook                    | [5cbade7533](https://linux-hardware.org/?probe=5cbade7533) | Nov 08, 2022 |
| Dell          | Latitude 3410               | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f207bc4c3](https://linux-hardware.org/?probe=3f207bc4c3) | Nov 07, 2022 |
| ASUSTek       | FX503VD                     | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| Dell          | Inspiron 7720               | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| Toshiba       | Satellite C660              | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Quanta        | TWS                         | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [af69f66287](https://linux-hardware.org/?probe=af69f66287) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [d9952c90a5](https://linux-hardware.org/?probe=d9952c90a5) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | [fb8bc290d6](https://linux-hardware.org/?probe=fb8bc290d6) | Nov 05, 2022 |
| TUXEDO        | Stellaris Intel Gen4        | [2b4987c9e8](https://linux-hardware.org/?probe=2b4987c9e8) | Nov 05, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | G50-70 20351                | [e29a593971](https://linux-hardware.org/?probe=e29a593971) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | [f0f862d5c5](https://linux-hardware.org/?probe=f0f862d5c5) | Nov 05, 2022 |
| ASUSTek       | X750JN                      | [3c8b130af7](https://linux-hardware.org/?probe=3c8b130af7) | Nov 05, 2022 |
| Dell          | Latitude 5591               | [e0e1ffe014](https://linux-hardware.org/?probe=e0e1ffe014) | Nov 05, 2022 |
| Dell          | Latitude 5591               | [b649030512](https://linux-hardware.org/?probe=b649030512) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| MSI           | Bravo 15 B5DD               | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [4e666fbb8f](https://linux-hardware.org/?probe=4e666fbb8f) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Acer          | Aspire E5-575G              | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Packard Be... | EasyNote LX                 | [41070f6bfe](https://linux-hardware.org/?probe=41070f6bfe) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| HP            | ZBook 15 G4                 | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0c186f330b](https://linux-hardware.org/?probe=0c186f330b) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d53ffb628](https://linux-hardware.org/?probe=2d53ffb628) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | EliteBook 850 G6            | [3480a7be5a](https://linux-hardware.org/?probe=3480a7be5a) | Nov 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [7a2dab8dde](https://linux-hardware.org/?probe=7a2dab8dde) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Acer          | Predator G9-591             | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| Toshiba       | Satellite S55-A             | [cfc6040185](https://linux-hardware.org/?probe=cfc6040185) | Nov 03, 2022 |
| MSI           | Katana GF76 12UE            | [4359d2a528](https://linux-hardware.org/?probe=4359d2a528) | Nov 02, 2022 |
| Dell          | Inspiron 7577               | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| Unknown       | Unknown                     | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Dell          | Latitude 3420               | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| HUAWEI        | BOHB-WAX9                   | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Dell          | Precision M6700             | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude E7450              | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| LincPlus      | P1                          | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| Dell          | Latitude 5500               | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| System76      | Galago UltraPro             | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| Dell          | Latitude E6420              | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Lenovo        | B560                        | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Framework     | Laptop                      | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| Framework     | Laptop                      | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Dell          | Precision 7760              | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Notebook      | W230SS                      | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Dell          | Latitude E5450              | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| Framework     | Laptop                      | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 15                          | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| HP            | Laptop                      | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| Framework     | Laptop                      | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| Dell          | Precision 5560              | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Dell          | Latitude 5420               | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Dell          | G3 3779                     | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| Dell          | Precision 5560              | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| AZW           | SEi                         | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| Notebook      | W230SS                      | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| Dell          | Latitude E5450              | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | XPS 13 9305                 | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [3969240177](https://linux-hardware.org/?probe=3969240177) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Dell          | Latitude 5511               | [3193c29c67](https://linux-hardware.org/?probe=3193c29c67) | Sep 04, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [57f8a4e96b](https://linux-hardware.org/?probe=57f8a4e96b) | Sep 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f0bcadac2f](https://linux-hardware.org/?probe=f0bcadac2f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 2320HPU       | [a8ba64ec12](https://linux-hardware.org/?probe=a8ba64ec12) | Sep 04, 2022 |
| HUAWEI        | KLVD-WXX9                   | [cc383de755](https://linux-hardware.org/?probe=cc383de755) | Sep 04, 2022 |
| Lenovo        | ThinkPad E560 20EV000RGE    | [5b69ce9986](https://linux-hardware.org/?probe=5b69ce9986) | Sep 04, 2022 |
| Acer          | AS VN7-571G                 | [1c14fbaf96](https://linux-hardware.org/?probe=1c14fbaf96) | Sep 04, 2022 |
| Dell          | Latitude 5420               | [b236b791c1](https://linux-hardware.org/?probe=b236b791c1) | Sep 04, 2022 |
| Lenovo        | 3000 N200 0769BAG           | [33fcb3e2b3](https://linux-hardware.org/?probe=33fcb3e2b3) | Sep 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c4db289b99](https://linux-hardware.org/?probe=c4db289b99) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [dc3fd2d992](https://linux-hardware.org/?probe=dc3fd2d992) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Dell          | Vostro 1320                 | [e66853cc37](https://linux-hardware.org/?probe=e66853cc37) | Sep 03, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | UX310UQK                    | [ed392e6b79](https://linux-hardware.org/?probe=ed392e6b79) | Sep 03, 2022 |
| ASUSTek       | GL503VM                     | [43cbef1764](https://linux-hardware.org/?probe=43cbef1764) | Sep 03, 2022 |
| MSI           | GP72MVR 7RFX                | [f370d7bbc3](https://linux-hardware.org/?probe=f370d7bbc3) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b73e153667](https://linux-hardware.org/?probe=b73e153667) | Sep 03, 2022 |
| HP            | Stream Notebook PC 13       | [d6c9e33a55](https://linux-hardware.org/?probe=d6c9e33a55) | Sep 03, 2022 |
| MSI           | Modern 14 B11MOL            | [92d3e81be7](https://linux-hardware.org/?probe=92d3e81be7) | Sep 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [cec0b91aa9](https://linux-hardware.org/?probe=cec0b91aa9) | Sep 03, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001JIX     | [30eb9dcb39](https://linux-hardware.org/?probe=30eb9dcb39) | Sep 03, 2022 |
| Alienware     | 14                          | [f30f3ddf3d](https://linux-hardware.org/?probe=f30f3ddf3d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [33ae7d4c4b](https://linux-hardware.org/?probe=33ae7d4c4b) | Sep 03, 2022 |
| Acer          | Swift SF315-41              | [634777751a](https://linux-hardware.org/?probe=634777751a) | Sep 02, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [006c26eaa0](https://linux-hardware.org/?probe=006c26eaa0) | Sep 02, 2022 |
| Acer          | Swift SF315-41              | [dd250df1ef](https://linux-hardware.org/?probe=dd250df1ef) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | G50-45 80E3                 | [a8e1884f32](https://linux-hardware.org/?probe=a8e1884f32) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| Dell          | Inspiron 5558               | [203baa4d7f](https://linux-hardware.org/?probe=203baa4d7f) | Sep 02, 2022 |
| Dell          | Latitude E6400              | [c781ec4733](https://linux-hardware.org/?probe=c781ec4733) | Sep 02, 2022 |
| Chuwi         | HeroBook Air                | [1ac18273da](https://linux-hardware.org/?probe=1ac18273da) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| Dell          | Latitude E5570              | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| Dell          | Precision 5750              | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| HP            | Pavilion dv6                | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| Acer          | Aspire E1-522               | [f4f0162d9a](https://linux-hardware.org/?probe=f4f0162d9a) | Aug 21, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| Acer          | Popcorn                     | [1c3d0d6b87](https://linux-hardware.org/?probe=1c3d0d6b87) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HP            | ENVY Notebook               | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| HONOR         | NBD-WXX9                    | [1fdf41de8b](https://linux-hardware.org/?probe=1fdf41de8b) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [ad8ec93f74](https://linux-hardware.org/?probe=ad8ec93f74) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [81be616c6b](https://linux-hardware.org/?probe=81be616c6b) | Aug 19, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| Acidanther... | MacBookPro12,1              | [6afa5c842e](https://linux-hardware.org/?probe=6afa5c842e) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [cfc3d5853c](https://linux-hardware.org/?probe=cfc3d5853c) | Aug 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [8aea7a68ee](https://linux-hardware.org/?probe=8aea7a68ee) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| MSI           | Modern 14 B11SBL            | [ad56f2a352](https://linux-hardware.org/?probe=ad56f2a352) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Eluktronic... | MAX-17                      | [b0aec6f095](https://linux-hardware.org/?probe=b0aec6f095) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0793e37f62](https://linux-hardware.org/?probe=0793e37f62) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Acer          | Aspire A715-42G             | [fbeff3bff5](https://linux-hardware.org/?probe=fbeff3bff5) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| HP            | Laptop 17-by0xxx            | [59db95ffee](https://linux-hardware.org/?probe=59db95ffee) | Aug 16, 2022 |
| Lenovo        | ThinkBook Plus 20TG         | [1f39fbc5a8](https://linux-hardware.org/?probe=1f39fbc5a8) | Aug 16, 2022 |
| Panasonic     | CFMX4-1                     | [01074aea14](https://linux-hardware.org/?probe=01074aea14) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| HP            | Pavilion TS 15              | [22194522c7](https://linux-hardware.org/?probe=22194522c7) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d9f8a6ea69](https://linux-hardware.org/?probe=d9f8a6ea69) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Sony          | VPCS131FM                   | [22e32938e6](https://linux-hardware.org/?probe=22e32938e6) | Aug 14, 2022 |
| Toshiba       | TECRA R940                  | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | XPS 15 9550                 | [ad3ad84c75](https://linux-hardware.org/?probe=ad3ad84c75) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| AXDIA Inte... | WINPAD V10                  | [a44a9b065b](https://linux-hardware.org/?probe=a44a9b065b) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Unknown       | Unknown                     | [dbf529a586](https://linux-hardware.org/?probe=dbf529a586) | Aug 14, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [ca9974d27e](https://linux-hardware.org/?probe=ca9974d27e) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Dell          | G3 3590                     | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 15 9510                 | [3cb2744dbe](https://linux-hardware.org/?probe=3cb2744dbe) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| HP            | ProBook 440 G7              | [ee57cf772f](https://linux-hardware.org/?probe=ee57cf772f) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | Pavilion 17                 | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Sony          | SVT15115CXS                 | [f7915ecf99](https://linux-hardware.org/?probe=f7915ecf99) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Acer          | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [05042a439b](https://linux-hardware.org/?probe=05042a439b) | Aug 11, 2022 |
| AZW           | SEi                         | [fb26f11a19](https://linux-hardware.org/?probe=fb26f11a19) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Dell          | XPS 13 7390                 | [149d92cd3e](https://linux-hardware.org/?probe=149d92cd3e) | Aug 10, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| Lenovo        | Z40-70 20366                | [2378dda760](https://linux-hardware.org/?probe=2378dda760) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HUAWEI        | MACH-WX9                    | [18f9226bc0](https://linux-hardware.org/?probe=18f9226bc0) | Aug 09, 2022 |
| Timi          | TM1701                      | [676fc52004](https://linux-hardware.org/?probe=676fc52004) | Aug 09, 2022 |
| MSI           | Prestige 15 A10SC           | [9471547f71](https://linux-hardware.org/?probe=9471547f71) | Aug 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [1a95dd7974](https://linux-hardware.org/?probe=1a95dd7974) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [30a447f95c](https://linux-hardware.org/?probe=30a447f95c) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| Alienware     | x17 R2                      | [4e7fe87198](https://linux-hardware.org/?probe=4e7fe87198) | Aug 07, 2022 |
| Acer          | Aspire 7741                 | [bc1daa0005](https://linux-hardware.org/?probe=bc1daa0005) | Aug 07, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9d837de022](https://linux-hardware.org/?probe=9d837de022) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [438f5cce2a](https://linux-hardware.org/?probe=438f5cce2a) | Aug 07, 2022 |
| Toshiba       | Satellite Pro L300D         | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [572cb48d3c](https://linux-hardware.org/?probe=572cb48d3c) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8f7a78b973](https://linux-hardware.org/?probe=8f7a78b973) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2eb53b5701](https://linux-hardware.org/?probe=2eb53b5701) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| HP            | Laptop 17-by4xxx            | [7867c6d24c](https://linux-hardware.org/?probe=7867c6d24c) | Aug 05, 2022 |
| Acer          | Aspire 7741                 | [eae703cf6f](https://linux-hardware.org/?probe=eae703cf6f) | Aug 05, 2022 |
| Acer          | Aspire A515-51              | [6c5e2de730](https://linux-hardware.org/?probe=6c5e2de730) | Aug 05, 2022 |
| HP            | ZBook 15 G3                 | [d59939b336](https://linux-hardware.org/?probe=d59939b336) | Aug 05, 2022 |
| Acer          | Aspire V3-572               | [dadff5cef8](https://linux-hardware.org/?probe=dadff5cef8) | Aug 05, 2022 |
| Gateway       | NE56R                       | [44de22f108](https://linux-hardware.org/?probe=44de22f108) | Aug 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [ec2efe1636](https://linux-hardware.org/?probe=ec2efe1636) | Aug 04, 2022 |
| MSI           | Modern 14 A10M              | [f8a0b1d6e6](https://linux-hardware.org/?probe=f8a0b1d6e6) | Aug 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| HP            | Snappy                      | [0a73175862](https://linux-hardware.org/?probe=0a73175862) | Aug 03, 2022 |
| HP            | Laptop 17-by4xxx            | [711cf515aa](https://linux-hardware.org/?probe=711cf515aa) | Aug 03, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 4290KJ6       | [ef5ee2a01e](https://linux-hardware.org/?probe=ef5ee2a01e) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [492d014205](https://linux-hardware.org/?probe=492d014205) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | ProBook 4540s               | [c96c493e64](https://linux-hardware.org/?probe=c96c493e64) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| ASUSTek       | X750JN                      | [b321cd29a8](https://linux-hardware.org/?probe=b321cd29a8) | Aug 02, 2022 |
| Dell          | Precision 5530              | [a5177f0edb](https://linux-hardware.org/?probe=a5177f0edb) | Aug 02, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Dell          | Latitude D620               | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| Clevo         | M570TU                      | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Notebook                    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64       | 109       | 8.12%   |
| 6.0.5-200.fc36.x86_64        | 69        | 5.14%   |
| 5.18.13-200.fc36.x86_64      | 61        | 4.55%   |
| 5.18.11-200.fc36.x86_64      | 50        | 3.73%   |
| 5.19.16-200.fc36.x86_64      | 46        | 3.43%   |
| 5.17.11-300.fc36.x86_64      | 46        | 3.43%   |
| 5.18.16-200.fc36.x86_64      | 45        | 3.35%   |
| 5.17.6-300.fc36.x86_64       | 43        | 3.2%    |
| 5.19.9-200.fc36.x86_64       | 42        | 3.13%   |
| 5.18.17-200.fc36.x86_64      | 40        | 2.98%   |
| 5.19.8-200.fc36.x86_64       | 38        | 2.83%   |
| 5.18.5-200.fc36.x86_64       | 38        | 2.83%   |
| 5.19.6-200.fc36.x86_64       | 36        | 2.68%   |
| 5.17.13-300.fc36.x86_64      | 36        | 2.68%   |
| 5.19.4-200.fc36.x86_64       | 33        | 2.46%   |
| 5.19.15-201.fc36.x86_64      | 33        | 2.46%   |
| 5.19.11-200.fc36.x86_64      | 30        | 2.24%   |
| 5.17.8-300.fc36.x86_64       | 29        | 2.16%   |
| 5.18.9-200.fc36.x86_64       | 28        | 2.09%   |
| 5.17.12-300.fc36.x86_64      | 27        | 2.01%   |
| 5.19.13-200.fc36.x86_64      | 26        | 1.94%   |
| 5.18.6-200.fc36.x86_64       | 26        | 1.94%   |
| 5.19.14-200.fc36.x86_64      | 25        | 1.86%   |
| 5.18.19-200.fc36.x86_64      | 25        | 1.86%   |
| 5.17.7-300.fc36.x86_64       | 24        | 1.79%   |
| 5.18.7-200.fc36.x86_64       | 23        | 1.71%   |
| 5.18.18-200.fc36.x86_64      | 22        | 1.64%   |
| 5.18.10-200.fc36.x86_64      | 21        | 1.56%   |
| 5.17.9-300.fc36.x86_64       | 21        | 1.56%   |
| 5.19.12-200.fc36.x86_64      | 18        | 1.34%   |
| 5.17.1-300.fc36.x86_64       | 16        | 1.19%   |
| 5.17.3-302.fc36.x86_64       | 15        | 1.12%   |
| 5.17.2-300.fc36.x86_64       | 13        | 0.97%   |
| 5.19.10-200.fc36.x86_64      | 12        | 0.89%   |
| 5.17.0-0.rc7.116.fc36.x86_64 | 12        | 0.89%   |
| 6.0.7-200.fc36.x86_64        | 9         | 0.67%   |
| 6.0.10-200.fc36.x86_64       | 9         | 0.67%   |
| 6.0.9-200.fc36.x86_64        | 8         | 0.6%    |
| 6.0.15-200.fc36.x86_64       | 8         | 0.6%    |
| 5.19.7-200.fc36.x86_64       | 7         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 111       | 8.27%   |
| 6.0.5   | 69        | 5.14%   |
| 5.18.13 | 62        | 4.62%   |
| 5.18.11 | 50        | 3.73%   |
| 5.19.16 | 46        | 3.43%   |
| 5.18.16 | 46        | 3.43%   |
| 5.17.11 | 46        | 3.43%   |
| 5.19.9  | 43        | 3.2%    |
| 5.17.6  | 43        | 3.2%    |
| 5.18.5  | 42        | 3.13%   |
| 5.18.17 | 40        | 2.98%   |
| 5.19.8  | 38        | 2.83%   |
| 5.19.6  | 37        | 2.76%   |
| 5.17.13 | 36        | 2.68%   |
| 5.19.4  | 34        | 2.53%   |
| 5.19.15 | 34        | 2.53%   |
| 5.19.11 | 30        | 2.24%   |
| 5.17.8  | 29        | 2.16%   |
| 5.18.9  | 28        | 2.09%   |
| 5.18.6  | 28        | 2.09%   |
| 5.17.12 | 27        | 2.01%   |
| 5.19.13 | 26        | 1.94%   |
| 5.19.14 | 25        | 1.86%   |
| 5.18.19 | 25        | 1.86%   |
| 5.18.18 | 25        | 1.86%   |
| 5.17.7  | 25        | 1.86%   |
| 5.18.10 | 24        | 1.79%   |
| 5.18.7  | 23        | 1.71%   |
| 5.17.9  | 21        | 1.56%   |
| 5.19.12 | 19        | 1.42%   |
| 5.17.0  | 17        | 1.27%   |
| 5.17.3  | 16        | 1.19%   |
| 5.17.1  | 16        | 1.19%   |
| 5.17.2  | 13        | 0.97%   |
| 5.19.10 | 12        | 0.89%   |
| 6.0.9   | 9         | 0.67%   |
| 6.0.7   | 9         | 0.67%   |
| 6.0.10  | 9         | 0.67%   |
| 6.0.15  | 8         | 0.6%    |
| 5.19.7  | 7         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 396       | 30.53%  |
| 5.18    | 387       | 29.84%  |
| 5.19    | 344       | 26.52%  |
| 6.0     | 132       | 10.18%  |
| 6.1     | 18        | 1.39%   |
| 6.2     | 8         | 0.62%   |
| 5.16    | 5         | 0.39%   |
| 5.15    | 5         | 0.39%   |
| 5.14    | 2         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1218      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 940       | 76.42%  |
| KDE5          | 185       | 15.04%  |
| Unknown       | 29        | 2.36%   |
| XFCE          | 23        | 1.87%   |
| X-Cinnamon    | 14        | 1.14%   |
| i3            | 8         | 0.65%   |
| MATE          | 7         | 0.57%   |
| Cinnamon      | 6         | 0.49%   |
| LXQt          | 4         | 0.33%   |
| sway          | 3         | 0.24%   |
| GNOME Classic | 2         | 0.16%   |
| awesome       | 2         | 0.16%   |
| openbox       | 1         | 0.08%   |
| LXDE          | 1         | 0.08%   |
| KDE:old       | 1         | 0.08%   |
| fluxbox       | 1         | 0.08%   |
| dwm           | 1         | 0.08%   |
| Deepin        | 1         | 0.08%   |
| bspwm         | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 926       | 75.1%   |
| X11     | 287       | 23.28%  |
| Unknown | 15        | 1.22%   |
| Tty     | 5         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 602       | 49.02%  |
| GDM     | 461       | 37.54%  |
| SDDM    | 96        | 7.82%   |
| LightDM | 67        | 5.46%   |
| Ly      | 1         | 0.08%   |
| KDM     | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 682       | 55.76%  |
| ru_RU   | 78        | 6.38%   |
| en_GB   | 65        | 5.31%   |
| it_IT   | 56        | 4.58%   |
| pt_BR   | 44        | 3.6%    |
| de_DE   | 44        | 3.6%    |
| fr_FR   | 31        | 2.53%   |
| es_ES   | 23        | 1.88%   |
| pl_PL   | 21        | 1.72%   |
| en_AU   | 21        | 1.72%   |
| en_IN   | 19        | 1.55%   |
| en_CA   | 15        | 1.23%   |
| es_MX   | 12        | 0.98%   |
| tr_TR   | 8         | 0.65%   |
| es_CL   | 7         | 0.57%   |
| Unknown | 6         | 0.49%   |
| ru_UA   | 5         | 0.41%   |
| pt_PT   | 5         | 0.41%   |
| nl_NL   | 5         | 0.41%   |
| hu_HU   | 5         | 0.41%   |
| de_AT   | 5         | 0.41%   |
| sv_SE   | 4         | 0.33%   |
| fr_BE   | 4         | 0.33%   |
| en_NZ   | 4         | 0.33%   |
| da_DK   | 4         | 0.33%   |
| cs_CZ   | 4         | 0.33%   |
| es_CO   | 3         | 0.25%   |
| es_AR   | 3         | 0.25%   |
| en_NL   | 3         | 0.25%   |
| en_IL   | 3         | 0.25%   |
| zh_CN   | 2         | 0.16%   |
| nl_BE   | 2         | 0.16%   |
| nb_NO   | 2         | 0.16%   |
| hr_HR   | 2         | 0.16%   |
| en_ZA   | 2         | 0.16%   |
| en_PH   | 2         | 0.16%   |
| en_IE   | 2         | 0.16%   |
| en_DK   | 2         | 0.16%   |
| de_CH   | 2         | 0.16%   |
| sr_RS   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1038      | 84.8%   |
| BIOS | 186       | 15.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 982       | 80.49%  |
| Ext4    | 214       | 17.54%  |
| Xfs     | 20        | 1.64%   |
| F2fs    | 2         | 0.16%   |
| Zfs     | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 607       | 49.35%  |
| GPT     | 565       | 45.93%  |
| MBR     | 58        | 4.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1102      | 89.96%  |
| Yes       | 123       | 10.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 974       | 79.45%  |
| Yes       | 252       | 20.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 357       | 29.31%  |
| Dell                   | 196       | 16.09%  |
| Hewlett-Packard        | 190       | 15.6%   |
| ASUSTek Computer       | 135       | 11.08%  |
| Acer                   | 70        | 5.75%   |
| MSI                    | 37        | 3.04%   |
| Apple                  | 37        | 3.04%   |
| HUAWEI                 | 27        | 2.22%   |
| Framework              | 13        | 1.07%   |
| Toshiba                | 12        | 0.99%   |
| Samsung Electronics    | 11        | 0.9%    |
| Timi                   | 10        | 0.82%   |
| Notebook               | 10        | 0.82%   |
| Sony                   | 9         | 0.74%   |
| Unknown                | 6         | 0.49%   |
| TUXEDO                 | 5         | 0.41%   |
| Gigabyte Technology    | 5         | 0.41%   |
| Chuwi                  | 5         | 0.41%   |
| Alienware              | 5         | 0.41%   |
| Positivo               | 4         | 0.33%   |
| VALE                   | 3         | 0.25%   |
| System76               | 3         | 0.25%   |
| Panasonic              | 3         | 0.25%   |
| LG Electronics         | 3         | 0.25%   |
| HONOR                  | 3         | 0.25%   |
| GPU Company            | 3         | 0.25%   |
| Google                 | 3         | 0.25%   |
| Fujitsu                | 3         | 0.25%   |
| Avell High Performance | 3         | 0.25%   |
| UNOWHY                 | 2         | 0.16%   |
| Razer                  | 2         | 0.16%   |
| Packard Bell           | 2         | 0.16%   |
| Itautec                | 2         | 0.16%   |
| GPD                    | 2         | 0.16%   |
| GEO                    | 2         | 0.16%   |
| Gateway                | 2         | 0.16%   |
| Exo                    | 2         | 0.16%   |
| Acidanthera            | 2         | 0.16%   |
| Wiltronic              | 1         | 0.08%   |
| VIT                    | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 1.07%   |
| Framework Laptop                       | 9         | 0.74%   |
| Dell XPS 15 9570                       | 8         | 0.66%   |
| HP Notebook                            | 7         | 0.57%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 6         | 0.49%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 5         | 0.41%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 5         | 0.41%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 5         | 0.41%   |
| HP Pavilion g6                         | 5         | 0.41%   |
| HP EliteBook 8470p                     | 5         | 0.41%   |
| Dell XPS 15 9510                       | 5         | 0.41%   |
| Dell Latitude E6420                    | 5         | 0.41%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 5         | 0.41%   |
| Apple MacBookPro12,1                   | 5         | 0.41%   |
| Lenovo ThinkBook 15-IIL 20SM           | 4         | 0.33%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 4         | 0.33%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 4         | 0.33%   |
| Framework Laptop (12th Gen Intel Core) | 4         | 0.33%   |
| Dell XPS 15 9520                       | 4         | 0.33%   |
| Dell XPS 13 9310                       | 4         | 0.33%   |
| ASUS ROG Strix G513QY_G513QY           | 4         | 0.33%   |
| Apple MacBookPro9,2                    | 4         | 0.33%   |
| Timi Redmi Book Pro 15 2022            | 3         | 0.25%   |
| Lenovo ThinkBook 16p Gen 2 20YM        | 3         | 0.25%   |
| Lenovo ThinkBook 15 G3 ACL 21A4        | 3         | 0.25%   |
| Lenovo ThinkBook 14 G3 ACL 21A2        | 3         | 0.25%   |
| Lenovo IdeaPad S340-14API 81NB         | 3         | 0.25%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.25%   |
| Lenovo IdeaPad 5 15ITL05 82FG          | 3         | 0.25%   |
| HUAWEI NBLK-WAX9X                      | 3         | 0.25%   |
| HUAWEI NBLB-WAX9N                      | 3         | 0.25%   |
| HUAWEI KLVL-WXXW                       | 3         | 0.25%   |
| HUAWEI BOD-WXX9                        | 3         | 0.25%   |
| HP ProBook 650 G1                      | 3         | 0.25%   |
| HP Pavilion Laptop 15-cs0xxx           | 3         | 0.25%   |
| HP EliteBook 8460p                     | 3         | 0.25%   |
| HP EliteBook 840 G3                    | 3         | 0.25%   |
| HP 250 G7 Notebook PC                  | 3         | 0.25%   |
| Dell XPS 17 9710                       | 3         | 0.25%   |
| Dell XPS 15 9550                       | 3         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 193       | 15.85%  |
| Lenovo IdeaPad     | 88        | 7.22%   |
| Dell Inspiron      | 57        | 4.68%   |
| Dell Latitude      | 52        | 4.27%   |
| Dell XPS           | 49        | 4.02%   |
| HP Pavilion        | 38        | 3.12%   |
| Acer Aspire        | 37        | 3.04%   |
| ASUS ROG           | 35        | 2.87%   |
| HP Laptop          | 33        | 2.71%   |
| HP EliteBook       | 31        | 2.55%   |
| ASUS VivoBook      | 31        | 2.55%   |
| HP ProBook         | 28        | 2.3%    |
| Lenovo ThinkBook   | 24        | 1.97%   |
| Dell Precision     | 19        | 1.56%   |
| Lenovo Legion      | 17        | 1.4%    |
| HP ZBook           | 13        | 1.07%   |
| Framework Laptop   | 13        | 1.07%   |
| ASUS ASUS          | 13        | 1.07%   |
| Acer Nitro         | 13        | 1.07%   |
| Unknown            | 13        | 1.07%   |
| Lenovo Yoga        | 12        | 0.99%   |
| Dell Vostro        | 11        | 0.9%    |
| Toshiba Satellite  | 10        | 0.82%   |
| Acer Swift         | 10        | 0.82%   |
| MSI Modern         | 9         | 0.74%   |
| HP ENVY            | 9         | 0.74%   |
| HP Notebook        | 7         | 0.57%   |
| ASUS Zenbook       | 7         | 0.57%   |
| ASUS TUF           | 6         | 0.49%   |
| MSI Prestige       | 5         | 0.41%   |
| Dell G3            | 5         | 0.41%   |
| Apple MacBookPro12 | 5         | 0.41%   |
| HP OMEN            | 4         | 0.33%   |
| HP 250             | 4         | 0.33%   |
| Apple MacBookPro9  | 4         | 0.33%   |
| Apple MacBookPro11 | 4         | 0.33%   |
| Acer Predator      | 4         | 0.33%   |
| VALE Notebook      | 3         | 0.25%   |
| Timi Redmi         | 3         | 0.25%   |
| MSI Bravo          | 3         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 248       | 20.36%  |
| 2020 | 189       | 15.52%  |
| 2019 | 133       | 10.92%  |
| 2018 | 110       | 9.03%   |
| 2022 | 87        | 7.14%   |
| 2017 | 70        | 5.75%   |
| 2016 | 61        | 5.01%   |
| 2013 | 61        | 5.01%   |
| 2015 | 59        | 4.84%   |
| 2012 | 58        | 4.76%   |
| 2014 | 46        | 3.78%   |
| 2011 | 46        | 3.78%   |
| 2010 | 21        | 1.72%   |
| 2009 | 15        | 1.23%   |
| 2008 | 12        | 0.99%   |
| 2007 | 1         | 0.08%   |
| 2006 | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1218      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 969       | 79.23%  |
| Enabled  | 254       | 20.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1212      | 99.51%  |
| Yes  | 6         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 358       | 29.22%  |
| 16.01-24.0  | 269       | 21.96%  |
| 8.01-16.0   | 262       | 21.39%  |
| 32.01-64.0  | 154       | 12.57%  |
| 3.01-4.0    | 112       | 9.14%   |
| 64.01-256.0 | 30        | 2.45%   |
| 24.01-32.0  | 20        | 1.63%   |
| 1.01-2.0    | 18        | 1.47%   |
| 2.01-3.0    | 2         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 397       | 30.85%  |
| 2.01-3.0   | 338       | 26.26%  |
| 3.01-4.0   | 308       | 23.93%  |
| 1.01-2.0   | 139       | 10.8%   |
| 8.01-16.0  | 90        | 6.99%   |
| 16.01-24.0 | 7         | 0.54%   |
| 24.01-32.0 | 4         | 0.31%   |
| 0.51-1.0   | 4         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 889       | 72.51%  |
| 2      | 292       | 23.82%  |
| 3      | 33        | 2.69%   |
| 4      | 5         | 0.41%   |
| 0      | 4         | 0.33%   |
| 5      | 2         | 0.16%   |
| 6      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 991       | 81.23%  |
| Yes       | 229       | 18.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 858       | 70.21%  |
| No        | 364       | 29.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1202      | 98.69%  |
| No        | 16        | 1.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1056      | 86.35%  |
| No        | 167       | 13.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 222       | 18.12%  |
| Russia      | 93        | 7.59%   |
| Italy       | 90        | 7.35%   |
| Germany     | 86        | 7.02%   |
| Brazil      | 66        | 5.39%   |
| India       | 53        | 4.33%   |
| France      | 39        | 3.18%   |
| Poland      | 36        | 2.94%   |
| Netherlands | 32        | 2.61%   |
| UK          | 31        | 2.53%   |
| Mexico      | 30        | 2.45%   |
| Spain       | 29        | 2.37%   |
| Australia   | 29        | 2.37%   |
| Turkey      | 27        | 2.2%    |
| Canada      | 22        | 1.8%    |
| Indonesia   | 18        | 1.47%   |
| Belgium     | 17        | 1.39%   |
| Argentina   | 15        | 1.22%   |
| Czechia     | 12        | 0.98%   |
| Austria     | 12        | 0.98%   |
| Portugal    | 11        | 0.9%    |
| Sweden      | 10        | 0.82%   |
| Romania     | 10        | 0.82%   |
| Hungary     | 10        | 0.82%   |
| Belarus     | 10        | 0.82%   |
| Norway      | 9         | 0.73%   |
| Chile       | 9         | 0.73%   |
| Switzerland | 8         | 0.65%   |
| Denmark     | 8         | 0.65%   |
| Ireland     | 7         | 0.57%   |
| Finland     | 7         | 0.57%   |
| Croatia     | 7         | 0.57%   |
| Colombia    | 7         | 0.57%   |
| Ukraine     | 6         | 0.49%   |
| Philippines | 6         | 0.49%   |
| Kenya       | 6         | 0.49%   |
| Israel      | 6         | 0.49%   |
| Egypt       | 6         | 0.49%   |
| Japan       | 5         | 0.41%   |
| Bulgaria    | 5         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 30        | 2.37%   |
| St Petersburg      | 20        | 1.58%   |
| Sao Paulo          | 13        | 1.03%   |
| Melbourne          | 12        | 0.95%   |
| Istanbul           | 12        | 0.95%   |
| Warsaw             | 11        | 0.87%   |
| Milan              | 10        | 0.79%   |
| Berlin             | 10        | 0.79%   |
| Rome               | 8         | 0.63%   |
| Paris              | 8         | 0.63%   |
| Munich             | 8         | 0.63%   |
| Mexico City        | 8         | 0.63%   |
| Prague             | 7         | 0.55%   |
| Minsk              | 7         | 0.55%   |
| Chicago            | 7         | 0.55%   |
| Oslo               | 6         | 0.47%   |
| Nairobi            | 6         | 0.47%   |
| Lisbon             | 6         | 0.47%   |
| Kolkata            | 6         | 0.47%   |
| Izmir              | 6         | 0.47%   |
| Budapest           | 6         | 0.47%   |
| Brisbane           | 6         | 0.47%   |
| Bengaluru          | 6         | 0.47%   |
| Zagreb             | 5         | 0.4%    |
| Verona             | 5         | 0.4%    |
| Sydney             | 5         | 0.4%    |
| Sofia              | 5         | 0.4%    |
| Santiago           | 5         | 0.4%    |
| Samara             | 5         | 0.4%    |
| New York           | 5         | 0.4%    |
| Jakarta            | 5         | 0.4%    |
| Helsinki           | 5         | 0.4%    |
| Chennai            | 5         | 0.4%    |
| Cairo              | 5         | 0.4%    |
| Bucharest          | 5         | 0.4%    |
| Zurich             | 4         | 0.32%   |
| Vienna             | 4         | 0.32%   |
| Stockholm          | 4         | 0.32%   |
| Santo Domingo Este | 4         | 0.32%   |
| Rio de Janeiro     | 4         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 323       | 403    | 20.97%  |
| WDC                            | 154       | 170    | 10%     |
| SanDisk                        | 107       | 126    | 6.95%   |
| Seagate                        | 101       | 118    | 6.56%   |
| SK hynix                       | 98        | 109    | 6.36%   |
| Toshiba                        | 78        | 90     | 5.06%   |
| Unknown                        | 71        | 85     | 4.61%   |
| Micron Technology              | 70        | 79     | 4.55%   |
| Intel                          | 68        | 82     | 4.42%   |
| Kingston                       | 65        | 71     | 4.22%   |
| Crucial                        | 49        | 57     | 3.18%   |
| KIOXIA                         | 36        | 45     | 2.34%   |
| A-DATA Technology              | 25        | 27     | 1.62%   |
| HGST                           | 21        | 24     | 1.36%   |
| Apple                          | 19        | 20     | 1.23%   |
| Phison                         | 17        | 17     | 1.1%    |
| Silicon Motion                 | 14        | 14     | 0.91%   |
| Hitachi                        | 13        | 13     | 0.84%   |
| China                          | 12        | 13     | 0.78%   |
| PNY                            | 9         | 11     | 0.58%   |
| LITEON                         | 9         | 9      | 0.58%   |
| Unknown                        | 9         | 9      | 0.58%   |
| UMIS                           | 8         | 9      | 0.52%   |
| SSSTC                          | 8         | 8      | 0.52%   |
| Phison Electronics             | 7         | 7      | 0.45%   |
| ADATA Technology               | 7         | 7      | 0.45%   |
| Patriot                        | 6         | 7      | 0.39%   |
| XPG                            | 5         | 8      | 0.32%   |
| Transcend                      | 5         | 6      | 0.32%   |
| SPCC                           | 5         | 5      | 0.32%   |
| Netac                          | 5         | 5      | 0.32%   |
| Intenso                        | 5         | 5      | 0.32%   |
| Union Memory (Shenzhen)        | 4         | 5      | 0.26%   |
| Team                           | 4         | 4      | 0.26%   |
| SABRENT                        | 4         | 4      | 0.26%   |
| Realtek Semiconductor          | 4         | 4      | 0.26%   |
| Micron/Crucial Technology      | 4         | 4      | 0.26%   |
| LITEONIT                       | 4         | 4      | 0.26%   |
| Lenovo                         | 4         | 6      | 0.26%   |
| Solid State Storage Technology | 3         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB                       | 24        | 1.49%   |
| Seagate ST1000LM035-1RK172 970GB                   | 23        | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 22        | 1.37%   |
| Samsung NVMe SSD Drive 512GB                       | 19        | 1.18%   |
| Samsung NVMe SSD Drive 256GB                       | 18        | 1.12%   |
| Intel NVMe SSD Drive 512GB                         | 15        | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 14        | 0.87%   |
| Unknown MMC Card  64GB                             | 13        | 0.81%   |
| Samsung NVMe SSD Drive 1TB                         | 13        | 0.81%   |
| Samsung NVMe SSD Drive 1024GB                      | 13        | 0.81%   |
| Kingston SA400S37240G 240GB SSD                    | 13        | 0.81%   |
| HGST HTS721010A9E630 1TB                           | 13        | 0.81%   |
| SK hynix NVMe SSD Drive 512GB                      | 12        | 0.75%   |
| Micron NVMe SSD Drive 512GB                        | 12        | 0.75%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 11        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 10        | 0.62%   |
| Toshiba MQ04ABF100 1TB                             | 9         | 0.56%   |
| SanDisk NVMe SSD Drive 1024GB                      | 9         | 0.56%   |
| Samsung SSD 860 EVO 250GB                          | 9         | 0.56%   |
| Samsung NVMe SSD Drive 500GB                       | 9         | 0.56%   |
| Unknown                                            | 9         | 0.56%   |
| Unknown MMC Card  32GB                             | 8         | 0.5%    |
| Unknown MMC Card  128GB                            | 8         | 0.5%    |
| Samsung SSD 980 PRO 1TB                            | 8         | 0.5%    |
| Samsung MZALQ512HBLU-00BL2 512GB                   | 8         | 0.5%    |
| KIOXIA NVMe SSD Drive 512GB                        | 8         | 0.5%    |
| Toshiba NVMe SSD Drive 512GB                       | 7         | 0.44%   |
| Toshiba MQ01ABD100 1TB                             | 7         | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                      | 7         | 0.44%   |
| SK hynix NVMe SSD Drive 1024GB                     | 7         | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                         | 7         | 0.44%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.44%   |
| Crucial CT500MX500SSD1 500GB                       | 7         | 0.44%   |
| Toshiba NVMe SSD Drive 256GB                       | 6         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB                    | 6         | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB                     | 6         | 0.37%   |
| Samsung SSD 980 1TB                                | 6         | 0.37%   |
| Samsung SSD 860 EVO 1TB                            | 6         | 0.37%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                     | 6         | 0.37%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                     | 6         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 96        | 113    | 39.83%  |
| WDC                | 65        | 73     | 26.97%  |
| Toshiba            | 35        | 40     | 14.52%  |
| HGST               | 21        | 24     | 8.71%   |
| Hitachi            | 13        | 13     | 5.39%   |
| Unknown            | 3         | 4      | 1.24%   |
| Fujitsu            | 3         | 3      | 1.24%   |
| Apple              | 2         | 2      | 0.83%   |
| USB3.0             | 1         | 1      | 0.41%   |
| JMicron Technology | 1         | 2      | 0.41%   |
| IB-AC703           | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 96        | 115    | 23.24%  |
| Crucial             | 43        | 51     | 10.41%  |
| SanDisk             | 40        | 51     | 9.69%   |
| Kingston            | 40        | 44     | 9.69%   |
| WDC                 | 22        | 25     | 5.33%   |
| Intel               | 16        | 21     | 3.87%   |
| Micron Technology   | 14        | 15     | 3.39%   |
| Apple               | 13        | 13     | 3.15%   |
| China               | 11        | 12     | 2.66%   |
| A-DATA Technology   | 11        | 12     | 2.66%   |
| SK hynix            | 10        | 11     | 2.42%   |
| PNY                 | 8         | 9      | 1.94%   |
| LITEON              | 7         | 7      | 1.69%   |
| Transcend           | 5         | 6      | 1.21%   |
| Patriot             | 5         | 6      | 1.21%   |
| Netac               | 5         | 5      | 1.21%   |
| Toshiba             | 4         | 5      | 0.97%   |
| LITEONIT            | 4         | 4      | 0.97%   |
| Intenso             | 4         | 4      | 0.97%   |
| SPCC                | 3         | 3      | 0.73%   |
| Lexar               | 3         | 3      | 0.73%   |
| Team                | 2         | 2      | 0.48%   |
| Seagate             | 2         | 2      | 0.48%   |
| OCZ                 | 2         | 2      | 0.48%   |
| KingDian            | 2         | 2      | 0.48%   |
| GOODRAM             | 2         | 4      | 0.48%   |
| GLOWAY              | 2         | 2      | 0.48%   |
| Gigabyte Technology | 2         | 3      | 0.48%   |
| GALAX               | 2         | 2      | 0.48%   |
| Apacer              | 2         | 2      | 0.48%   |
| Unknown             | 2         | 2      | 0.48%   |
| XrayDisk            | 1         | 1      | 0.24%   |
| Win Memory          | 1         | 1      | 0.24%   |
| WDC WDS2            | 1         | 1      | 0.24%   |
| walram              | 1         | 1      | 0.24%   |
| Vaseky              | 1         | 1      | 0.24%   |
| TO Exter            | 1         | 1      | 0.24%   |
| Teclast             | 1         | 1      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| Ramsta              | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 740       | 922    | 51.46%  |
| SSD     | 373       | 478    | 25.94%  |
| HDD     | 235       | 276    | 16.34%  |
| MMC     | 70        | 87     | 4.87%   |
| Unknown | 20        | 20     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 739       | 918    | 52.52%  |
| SATA | 548       | 719    | 38.95%  |
| MMC  | 70        | 87     | 4.98%   |
| SAS  | 50        | 59     | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 376       | 461    | 60.16%  |
| 0.51-1.0   | 209       | 244    | 33.44%  |
| 1.01-2.0   | 31        | 40     | 4.96%   |
| 3.01-4.0   | 5         | 5      | 0.8%    |
| 4.01-10.0  | 3         | 3      | 0.48%   |
| 10.01-20.0 | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 282       | 22.69%  |
| 251-500        | 251       | 20.19%  |
| 101-250        | 178       | 14.32%  |
| 1-20           | 158       | 12.71%  |
| 1001-2000      | 157       | 12.63%  |
| Unknown        | 95        | 7.64%   |
| 51-100         | 49        | 3.94%   |
| More than 3000 | 31        | 2.49%   |
| 2001-3000      | 29        | 2.33%   |
| 21-50          | 13        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 418       | 32.66%  |
| 21-50          | 220       | 17.19%  |
| 101-250        | 176       | 13.75%  |
| 51-100         | 148       | 11.56%  |
| 251-500        | 125       | 9.77%   |
| Unknown        | 95        | 7.42%   |
| 501-1000       | 76        | 5.94%   |
| 1001-2000      | 15        | 1.17%   |
| 2001-3000      | 4         | 0.31%   |
| More than 3000 | 3         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 5      | 5.88%   |
| HGST HTS721010A9E630 1TB                     | 3         | 3      | 5.88%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2         | 3      | 3.92%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 2      | 3.92%   |
| WDC WD6400BPVT-75HXZT3 640GB                 | 1         | 1      | 1.96%   |
| WDC WD6400BEVT-22A0RT0 640GB                 | 1         | 1      | 1.96%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.96%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 1.96%   |
| WDC WD5000LPCX-00VHAT0 500GB                 | 1         | 1      | 1.96%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.96%   |
| walram SSD 120G                              | 1         | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.96%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 1.96%   |
| Toshiba MK3275GSX 320GB                      | 1         | 2      | 1.96%   |
| Toshiba MK2556GSY 250GB                      | 1         | 1      | 1.96%   |
| Toshiba HDWJ105 500GB                        | 1         | 1      | 1.96%   |
| SK hynix HFS512G39TND-N210A 512GB SSD        | 1         | 1      | 1.96%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 1.96%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 1.96%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 1.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1         | 1      | 1.96%   |
| Seagate ST1000LM048-2E7172 1TB               | 1         | 1      | 1.96%   |
| Seagate ST1000LM035-1RK172 970GB             | 1         | 1      | 1.96%   |
| SanDisk SSD PLUS 1000GB                      | 1         | 2      | 1.96%   |
| SanDisk SD6SB1M128G1022 128GB SSD            | 1         | 1      | 1.96%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 980 PRO 500GB        | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 1.96%   |
| Samsung Electronics MZVKW512HMJP-000H1 512GB | 1         | 1      | 1.96%   |
| PNY SSD2SC120G3LC726B104-370P 120GB          | 1         | 1      | 1.96%   |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 1.96%   |
| OCZ-VERTEX3 MI 120GB SSD                     | 1         | 1      | 1.96%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 1.96%   |
| LITEONIT LCS-128M6S-HP 128GB SSD             | 1         | 1      | 1.96%   |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 2      | 1.96%   |
| Kingston SHFS37A120G 120GB SSD               | 1         | 1      | 1.96%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 1.96%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 19.61%  |
| WDC                 | 6         | 6      | 11.76%  |
| Toshiba             | 5         | 6      | 9.8%    |
| Samsung Electronics | 5         | 6      | 9.8%    |
| Hitachi             | 5         | 5      | 9.8%    |
| SanDisk             | 3         | 4      | 5.88%   |
| HGST                | 3         | 3      | 5.88%   |
| SK hynix            | 2         | 2      | 3.92%   |
| Crucial             | 2         | 3      | 3.92%   |
| walram              | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| Origin              | 1         | 1      | 1.96%   |
| OCZ-VERTEX3         | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| Lenovo              | 1         | 2      | 1.96%   |
| Kingston            | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 33.33%  |
| WDC     | 6         | 6      | 20%     |
| Toshiba | 5         | 6      | 16.67%  |
| Hitachi | 5         | 5      | 16.67%  |
| HGST    | 3         | 3      | 10%     |
| Fujitsu | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 33     | 58.82%  |
| SSD  | 16        | 19     | 31.37%  |
| NVMe | 5         | 6      | 9.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 684       | 1000   | 52.9%   |
| Works    | 559       | 724    | 43.23%  |
| Malfunc  | 49        | 58     | 3.79%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 704       | 44.42%  |
| Samsung Electronics                     | 240       | 15.14%  |
| AMD                                     | 134       | 8.45%   |
| SanDisk                                 | 132       | 8.33%   |
| SK hynix                                | 87        | 5.49%   |
| Micron Technology                       | 55        | 3.47%   |
| Toshiba America Info Systems            | 44        | 2.78%   |
| KIOXIA                                  | 32        | 2.02%   |
| Phison Electronics                      | 28        | 1.77%   |
| Kingston Technology Company             | 27        | 1.7%    |
| ADATA Technology                        | 24        | 1.51%   |
| Silicon Motion                          | 16        | 1.01%   |
| Solid State Storage Technology          | 11        | 0.69%   |
| Micron/Crucial Technology               | 10        | 0.63%   |
| Union Memory (Shenzhen)                 | 9         | 0.57%   |
| Nvidia                                  | 5         | 0.32%   |
| Realtek Semiconductor                   | 4         | 0.25%   |
| Marvell Technology Group                | 4         | 0.25%   |
| Lite-On Technology                      | 4         | 0.25%   |
| Lenovo                                  | 4         | 0.25%   |
| Apple                                   | 4         | 0.25%   |
| Seagate Technology                      | 2         | 0.13%   |
| Yangtze Memory Technologies             | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| Unknown                                 | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 129       | 7.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 97        | 5.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 89        | 5.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 76        | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 71        | 4.28%   |
| Samsung NVMe SSD Controller 980                                                | 68        | 4.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 3.98%   |
| Micron NVMe Storage Controller                                                 | 55        | 3.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 47        | 2.83%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 44        | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 44        | 2.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 43        | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 39        | 2.35%   |
| Intel Tiger Lake-LP SATA Controller                                            | 37        | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 32        | 1.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 26        | 1.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 25        | 1.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 1.51%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 24        | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 24        | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 21        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 21        | 1.27%   |
| Intel Non-Volatile memory controller                                           | 20        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 1.21%   |
| Intel SSD 660P Series                                                          | 19        | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 1.02%   |
| SanDisk NVMe Controller                                                        | 16        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.96%   |
| SK hynix BC511                                                                 | 14        | 0.84%   |
| SanDisk Non-Volatile memory controller                                         | 14        | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 13        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 12        | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 12        | 0.72%   |
| Solid State Storage Non-Volatile memory controller                             | 11        | 0.66%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 11        | 0.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 11        | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 0.6%    |
| Phison E12 NVMe Controller                                                     | 10        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 733       | 46.04%  |
| SATA | 702       | 44.1%   |
| RAID | 143       | 8.98%   |
| IDE  | 14        | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 926       | 76.03%  |
| AMD     | 291       | 23.89%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 3.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 3.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 28        | 2.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 1.97%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 1.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 22        | 1.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 22        | 1.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 1.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 14        | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.07%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 0.99%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.99%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 12        | 0.99%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 11        | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.82%   |
| Intel 12th Gen Core i7-12700H                 | 10        | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 10        | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.74%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.74%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.66%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 8         | 0.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.66%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 7         | 0.57%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 7         | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 309       | 25.37%  |
| Intel Core i5                  | 256       | 21.02%  |
| Other                          | 196       | 16.09%  |
| AMD Ryzen 5                    | 96        | 7.88%   |
| AMD Ryzen 7                    | 90        | 7.39%   |
| Intel Core i3                  | 60        | 4.93%   |
| Intel Celeron                  | 42        | 3.45%   |
| AMD Ryzen 9                    | 28        | 2.3%    |
| AMD Ryzen 7 PRO                | 20        | 1.64%   |
| Intel Core 2 Duo               | 17        | 1.4%    |
| Intel Core i9                  | 13        | 1.07%   |
| AMD Ryzen 3                    | 13        | 1.07%   |
| Intel Pentium                  | 12        | 0.99%   |
| Intel Atom                     | 11        | 0.9%    |
| AMD Ryzen 5 PRO                | 10        | 0.82%   |
| AMD A10                        | 9         | 0.74%   |
| Intel Pentium Silver           | 6         | 0.49%   |
| AMD A6                         | 5         | 0.41%   |
| Intel Xeon                     | 4         | 0.33%   |
| AMD E1                         | 3         | 0.25%   |
| AMD A8                         | 3         | 0.25%   |
| AMD A4                         | 3         | 0.25%   |
| Intel Pentium Dual-Core        | 1         | 0.08%   |
| Intel Core m5                  | 1         | 0.08%   |
| Intel Core 2                   | 1         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.08%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.08%   |
| AMD PRO A8                     | 1         | 0.08%   |
| AMD PRO A10                    | 1         | 0.08%   |
| AMD Phenom II                  | 1         | 0.08%   |
| AMD Athlon II Dual-Core        | 1         | 0.08%   |
| AMD Athlon II                  | 1         | 0.08%   |
| AMD Athlon                     | 1         | 0.08%   |
| AMD A12                        | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 470       | 38.59%  |
| 2      | 389       | 31.94%  |
| 8      | 165       | 13.55%  |
| 6      | 148       | 12.15%  |
| 14     | 20        | 1.64%   |
| 12     | 16        | 1.31%   |
| 10     | 6         | 0.49%   |
| 1      | 2         | 0.16%   |
| 16     | 1         | 0.08%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1218      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1077      | 88.35%  |
| 1      | 142       | 11.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1218      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 110       | 8.99%   |
| 0x306a9    | 68        | 5.56%   |
| 0x806ea    | 63        | 5.15%   |
| Unknown    | 61        | 4.99%   |
| 0x806ec    | 56        | 4.58%   |
| 0x0a50000c | 56        | 4.58%   |
| 0x906ea    | 48        | 3.92%   |
| 0x206a7    | 48        | 3.92%   |
| 0x806e9    | 46        | 3.76%   |
| 0x40651    | 44        | 3.6%    |
| 0xa0652    | 40        | 3.27%   |
| 0x08600106 | 35        | 2.86%   |
| 0x08108109 | 35        | 2.86%   |
| 0x406e3    | 34        | 2.78%   |
| 0x906a3    | 33        | 2.7%    |
| 0x306d4    | 33        | 2.7%    |
| 0x08608103 | 31        | 2.53%   |
| 0x806d1    | 24        | 1.96%   |
| 0x506e3    | 24        | 1.96%   |
| 0x306c3    | 23        | 1.88%   |
| 0x906e9    | 22        | 1.8%    |
| 0x706e5    | 20        | 1.64%   |
| 0x706a8    | 16        | 1.31%   |
| 0x0a404101 | 15        | 1.23%   |
| 0x08108102 | 15        | 1.23%   |
| 0x806eb    | 14        | 1.14%   |
| 0x20655    | 13        | 1.06%   |
| 0x0a404102 | 13        | 1.06%   |
| 0x08600104 | 13        | 1.06%   |
| 0x806c2    | 11        | 0.9%    |
| 0x1067a    | 10        | 0.82%   |
| 0x906ed    | 9         | 0.74%   |
| 0x30678    | 9         | 0.74%   |
| 0x08608102 | 9         | 0.74%   |
| 0x08600103 | 9         | 0.74%   |
| 0x506c9    | 8         | 0.65%   |
| 0x406c4    | 7         | 0.57%   |
| 0x10676    | 7         | 0.57%   |
| 0x906a4    | 6         | 0.49%   |
| 0x706a1    | 6         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 276       | 22.64%  |
| TigerLake        | 124       | 10.17%  |
| Haswell          | 74        | 6.07%   |
| Unknown          | 74        | 6.07%   |
| IvyBridge        | 70        | 5.74%   |
| Zen 3            | 68        | 5.58%   |
| Zen 2            | 61        | 5%      |
| Skylake          | 61        | 5%      |
| Zen+             | 51        | 4.18%   |
| SandyBridge      | 49        | 4.02%   |
| Icelake          | 47        | 3.86%   |
| CometLake        | 46        | 3.77%   |
| Alderlake Hybrid | 41        | 3.36%   |
| Broadwell        | 34        | 2.79%   |
| Silvermont       | 23        | 1.89%   |
| Goldmont plus    | 22        | 1.8%    |
| Westmere         | 20        | 1.64%   |
| Penryn           | 18        | 1.48%   |
| Zen              | 11        | 0.9%    |
| Excavator        | 11        | 0.9%    |
| Goldmont         | 8         | 0.66%   |
| Tremont          | 5         | 0.41%   |
| Jaguar           | 5         | 0.41%   |
| Puma             | 4         | 0.33%   |
| Piledriver       | 4         | 0.33%   |
| Nehalem          | 3         | 0.25%   |
| K10              | 3         | 0.25%   |
| K8 Hammer        | 1         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.08%   |
| K10 Llano        | 1         | 0.08%   |
| Core             | 1         | 0.08%   |
| Bonnell          | 1         | 0.08%   |
| Bobcat           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 873       | 53.79%  |
| Nvidia | 410       | 25.26%  |
| AMD    | 340       | 20.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 7%      |
| Intel UHD Graphics 620                                                                   | 64        | 3.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 3.74%   |
| AMD Renoir                                                                               | 61        | 3.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 59        | 3.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 53        | 3.2%    |
| Intel HD Graphics 620                                                                    | 47        | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 2.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 2.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 2.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 2.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 2.41%   |
| AMD Lucienne                                                                             | 40        | 2.41%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 36        | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 31        | 1.87%   |
| AMD Rembrandt [Radeon 680M]                                                              | 29        | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 28        | 1.69%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.45%   |
| Intel HD Graphics 530                                                                    | 21        | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 18        | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 18        | 1.09%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 17        | 1.03%   |
| Intel HD Graphics 630                                                                    | 16        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 13        | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 13        | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 0.78%   |
| Nvidia TU117M                                                                            | 10        | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 10        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 0.6%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 9         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 533       | 43.72%  |
| Intel + Nvidia | 300       | 24.61%  |
| 1 x AMD        | 208       | 17.06%  |
| AMD + Nvidia   | 65        | 5.33%   |
| 1 x Nvidia     | 43        | 3.53%   |
| Intel + AMD    | 37        | 3.04%   |
| 2 x AMD        | 30        | 2.46%   |
| Other          | 1         | 0.08%   |
| 2 x Nvidia     | 1         | 0.08%   |
| 2 x Intel      | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1026      | 83.96%  |
| Proprietary | 186       | 15.22%  |
| Unknown     | 10        | 0.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 700       | 57.05%  |
| 1.01-2.0   | 173       | 14.1%   |
| 0.01-0.5   | 158       | 12.88%  |
| 3.01-4.0   | 87        | 7.09%   |
| 0.51-1.0   | 60        | 4.89%   |
| 7.01-8.0   | 19        | 1.55%   |
| 5.01-6.0   | 17        | 1.39%   |
| 8.01-16.0  | 7         | 0.57%   |
| 2.01-3.0   | 6         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 269       | 18.01%  |
| BOE                     | 263       | 17.6%   |
| Chimei Innolux          | 197       | 13.19%  |
| LG Display              | 173       | 11.58%  |
| Samsung Electronics     | 94        | 6.29%   |
| Dell                    | 61        | 4.08%   |
| Sharp                   | 57        | 3.82%   |
| Goldstar                | 52        | 3.48%   |
| Apple                   | 38        | 2.54%   |
| PANDA                   | 32        | 2.14%   |
| Lenovo                  | 29        | 1.94%   |
| CSO                     | 26        | 1.74%   |
| Hewlett-Packard         | 23        | 1.54%   |
| Philips                 | 20        | 1.34%   |
| BenQ                    | 16        | 1.07%   |
| Chi Mei Optoelectronics | 15        | 1%      |
| InfoVision              | 14        | 0.94%   |
| Acer                    | 13        | 0.87%   |
| AOC                     | 12        | 0.8%    |
| TMX                     | 11        | 0.74%   |
| ViewSonic               | 8         | 0.54%   |
| Iiyama                  | 6         | 0.4%    |
| Ancor Communications    | 6         | 0.4%    |
| MSI                     | 4         | 0.27%   |
| Vizio                   | 3         | 0.2%    |
| Toshiba                 | 3         | 0.2%    |
| JDI                     | 3         | 0.2%    |
| CTO                     | 3         | 0.2%    |
| SKY                     | 2         | 0.13%   |
| Panasonic               | 2         | 0.13%   |
| ONN                     | 2         | 0.13%   |
| Mi                      | 2         | 0.13%   |
| KDC                     | 2         | 0.13%   |
| HKC                     | 2         | 0.13%   |
| Gigabyte Technology     | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| ASUSTek Computer        | 2         | 0.13%   |
| YCT                     | 1         | 0.07%   |
| VIE                     | 1         | 0.07%   |
| Vestel Elektronik       | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 14        | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch   | 14        | 0.92%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch            | 13        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch | 11        | 0.73%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch            | 11        | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 9         | 0.59%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch   | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch | 7         | 0.46%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch            | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch   | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch   | 7         | 0.46%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch     | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 6         | 0.4%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 6         | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch             | 6         | 0.4%    |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch   | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch   | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch   | 6         | 0.4%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 5         | 0.33%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch     | 5         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 5         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch     | 5         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 5         | 0.33%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch            | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch  | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch | 5         | 0.33%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch            | 5         | 0.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 5         | 0.33%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch    | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch    | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch    | 5         | 0.33%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch          | 4         | 0.26%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch          | 4         | 0.26%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch          | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 703       | 51.05%  |
| 1366x768 (WXGA)    | 241       | 17.5%   |
| 3840x2160 (4K)     | 72        | 5.23%   |
| 2560x1440 (QHD)    | 63        | 4.58%   |
| 1920x1200 (WUXGA)  | 49        | 3.56%   |
| 1600x900 (HD+)     | 45        | 3.27%   |
| 2560x1600          | 35        | 2.54%   |
| 3440x1440          | 20        | 1.45%   |
| 2880x1800          | 18        | 1.31%   |
| 1280x800 (WXGA)    | 17        | 1.23%   |
| 3840x2400          | 16        | 1.16%   |
| 2560x1080          | 13        | 0.94%   |
| 2256x1504          | 13        | 0.94%   |
| 1440x900 (WXGA+)   | 13        | 0.94%   |
| 2160x1440          | 10        | 0.73%   |
| 1280x1024 (SXGA)   | 9         | 0.65%   |
| 3456x2160          | 5         | 0.36%   |
| 3200x2000          | 4         | 0.29%   |
| 2240x1400          | 4         | 0.29%   |
| 3072x1920          | 3         | 0.22%   |
| 2520x1680          | 3         | 0.22%   |
| 1680x1050 (WSXGA+) | 3         | 0.22%   |
| 1360x768           | 3         | 0.22%   |
| 3840x1600          | 2         | 0.15%   |
| 3200x1800 (QHD+)   | 2         | 0.15%   |
| 3000x2000          | 2         | 0.15%   |
| 3840x1080          | 1         | 0.07%   |
| 2560x2880          | 1         | 0.07%   |
| 2400x1600          | 1         | 0.07%   |
| 2304x1440          | 1         | 0.07%   |
| 1920x550           | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1024x768 (XGA)     | 1         | 0.07%   |
| 1024x600           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 554       | 36.93%  |
| 13      | 239       | 15.93%  |
| 14      | 231       | 15.4%   |
| 17      | 85        | 5.67%   |
| 27      | 76        | 5.07%   |
| 24      | 52        | 3.47%   |
| 23      | 43        | 2.87%   |
| 21      | 36        | 2.4%    |
| 16      | 32        | 2.13%   |
| 12      | 30        | 2%      |
| 34      | 29        | 1.93%   |
| 31      | 20        | 1.33%   |
| 11      | 12        | 0.8%    |
| 19      | 8         | 0.53%   |
| 20      | 7         | 0.47%   |
| 84      | 6         | 0.4%    |
| 18      | 5         | 0.33%   |
| 40      | 4         | 0.27%   |
| Unknown | 4         | 0.27%   |
| 35      | 3         | 0.2%    |
| 29      | 3         | 0.2%    |
| 22      | 3         | 0.2%    |
| 42      | 2         | 0.13%   |
| 37      | 2         | 0.13%   |
| 32      | 2         | 0.13%   |
| 25      | 2         | 0.13%   |
| 10      | 2         | 0.13%   |
| 69      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 50      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 925       | 62.29%  |
| 201-300     | 162       | 10.91%  |
| 501-600     | 157       | 10.57%  |
| 351-400     | 96        | 6.46%   |
| 401-500     | 57        | 3.84%   |
| 701-800     | 31        | 2.09%   |
| 601-700     | 29        | 1.95%   |
| 801-900     | 11        | 0.74%   |
| 1501-2000   | 7         | 0.47%   |
| 1001-1500   | 4         | 0.27%   |
| Unknown     | 4         | 0.27%   |
| 901-1000    | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1024      | 80%     |
| 16/10   | 175       | 13.67%  |
| 21/9    | 36        | 2.81%   |
| 3/2     | 29        | 2.27%   |
| 5/4     | 8         | 0.63%   |
| 4/3     | 3         | 0.23%   |
| 32/9    | 3         | 0.23%   |
| 0.89    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 556       | 37.19%  |
| 81-90          | 384       | 25.69%  |
| 201-250        | 107       | 7.16%   |
| 71-80          | 82        | 5.48%   |
| 301-350        | 78        | 5.22%   |
| 121-130        | 76        | 5.08%   |
| 351-500        | 55        | 3.68%   |
| 111-120        | 30        | 2.01%   |
| 61-70          | 29        | 1.94%   |
| 151-200        | 21        | 1.4%    |
| 251-300        | 20        | 1.34%   |
| 51-60          | 12        | 0.8%    |
| More than 1000 | 10        | 0.67%   |
| 501-1000       | 10        | 0.67%   |
| 141-150        | 9         | 0.6%    |
| 131-140        | 6         | 0.4%    |
| 91-100         | 4         | 0.27%   |
| Unknown        | 4         | 0.27%   |
| 41-50          | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 699       | 47.71%  |
| 101-120       | 296       | 20.2%   |
| 51-100        | 201       | 13.72%  |
| 161-240       | 182       | 12.42%  |
| More than 240 | 79        | 5.39%   |
| 1-50          | 4         | 0.27%   |
| Unknown       | 4         | 0.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 923       | 74.5%   |
| 2     | 263       | 21.23%  |
| 3     | 30        | 2.42%   |
| 0     | 16        | 1.29%   |
| 4     | 6         | 0.48%   |
| 5     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 708       | 38.86%  |
| Realtek Semiconductor             | 630       | 34.58%  |
| Qualcomm Atheros                  | 170       | 9.33%   |
| Broadcom                          | 79        | 4.34%   |
| MediaTek                          | 66        | 3.62%   |
| Broadcom Limited                  | 20        | 1.1%    |
| Lenovo                            | 15        | 0.82%   |
| TP-Link                           | 12        | 0.66%   |
| DisplayLink                       | 12        | 0.66%   |
| Qualcomm                          | 11        | 0.6%    |
| ASIX Electronics                  | 10        | 0.55%   |
| Sierra Wireless                   | 9         | 0.49%   |
| Samsung Electronics               | 7         | 0.38%   |
| Ralink                            | 7         | 0.38%   |
| Ralink Technology                 | 6         | 0.33%   |
| Nvidia                            | 5         | 0.27%   |
| Huawei Technologies               | 5         | 0.27%   |
| T & A Mobile Phones               | 4         | 0.22%   |
| Hewlett-Packard                   | 4         | 0.22%   |
| Ericsson Business Mobile Networks | 4         | 0.22%   |
| Dell                              | 4         | 0.22%   |
| Apple                             | 4         | 0.22%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.16%   |
| Xiaomi                            | 2         | 0.11%   |
| OPPO Electronics                  | 2         | 0.11%   |
| Microsoft                         | 2         | 0.11%   |
| Marvell Technology Group          | 2         | 0.11%   |
| Google                            | 2         | 0.11%   |
| Fibocom                           | 2         | 0.11%   |
| D-Link                            | 2         | 0.11%   |
| Belkin Components                 | 2         | 0.11%   |
| Shenzhen Goodix Technology        | 1         | 0.05%   |
| NetGear                           | 1         | 0.05%   |
| MicroPython                       | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| Linksys                           | 1         | 0.05%   |
| IMC Networks                      | 1         | 0.05%   |
| ICS Advent                        | 1         | 0.05%   |
| Edimax Technology                 | 1         | 0.05%   |
| D-Link System                     | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 366       | 16.61%  |
| Intel Wi-Fi 6 AX201                                               | 92        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 3.72%   |
| Intel Wi-Fi 6 AX200                                               | 80        | 3.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 69        | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 60        | 2.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 53        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 2.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 47        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 44        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 42        | 1.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 40        | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 39        | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 36        | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 32        | 1.45%   |
| Intel Wireless 7265                                               | 30        | 1.36%   |
| Intel Wireless 8260                                               | 29        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29        | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 1.04%   |
| Intel Wireless 7260                                               | 23        | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 21        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 19        | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 19        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.82%   |
| Intel Wireless 3165                                               | 17        | 0.77%   |
| Intel Wireless-AC 9260                                            | 16        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 0.5%    |
| Intel Wireless 3160                                               | 11        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 687       | 54.96%  |
| Realtek Semiconductor | 207       | 16.56%  |
| Qualcomm Atheros      | 154       | 12.32%  |
| MediaTek              | 65        | 5.2%    |
| Broadcom              | 65        | 5.2%    |
| Broadcom Limited      | 17        | 1.36%   |
| Qualcomm              | 10        | 0.8%    |
| TP-Link               | 9         | 0.72%   |
| Sierra Wireless       | 8         | 0.64%   |
| Ralink                | 7         | 0.56%   |
| Ralink Technology     | 6         | 0.48%   |
| Microsoft             | 2         | 0.16%   |
| Fibocom               | 2         | 0.16%   |
| Dell                  | 2         | 0.16%   |
| Belkin Components     | 2         | 0.16%   |
| NetGear               | 1         | 0.08%   |
| Linksys               | 1         | 0.08%   |
| IMC Networks          | 1         | 0.08%   |
| Edimax Technology     | 1         | 0.08%   |
| D-Link System         | 1         | 0.08%   |
| D-Link                | 1         | 0.08%   |
| ASUSTek Computer      | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 92        | 7.34%   |
| Intel Wi-Fi 6 AX200                                            | 80        | 6.38%   |
| Intel Wireless 8265 / 8275                                     | 60        | 4.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 53        | 4.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 47        | 3.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 44        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 42        | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 40        | 3.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 39        | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 2.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 32        | 2.55%   |
| Intel Wireless 7265                                            | 30        | 2.39%   |
| Intel Wireless 8260                                            | 29        | 2.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23        | 1.83%   |
| Intel Wireless 7260                                            | 23        | 1.83%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 19        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 19        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.44%   |
| Intel Wireless 3165                                            | 17        | 1.36%   |
| Intel Wireless-AC 9260                                         | 16        | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.96%   |
| Intel Wireless 3160                                            | 11        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.8%    |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter       | 9         | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 9         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 9         | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 8         | 0.64%   |
| Realtek 802.11ac NIC                                           | 7         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 542       | 59.43%  |
| Intel                         | 237       | 25.99%  |
| Qualcomm Atheros              | 31        | 3.4%    |
| Broadcom                      | 24        | 2.63%   |
| Lenovo                        | 14        | 1.54%   |
| DisplayLink                   | 12        | 1.32%   |
| ASIX Electronics              | 10        | 1.1%    |
| Samsung Electronics           | 5         | 0.55%   |
| Nvidia                        | 5         | 0.55%   |
| TP-Link                       | 4         | 0.44%   |
| Huawei Technologies           | 4         | 0.44%   |
| Apple                         | 4         | 0.44%   |
| Broadcom Limited              | 3         | 0.33%   |
| Xiaomi                        | 2         | 0.22%   |
| OPPO Electronics              | 2         | 0.22%   |
| OnePlus Technology (Shenzhen) | 2         | 0.22%   |
| Marvell Technology Group      | 2         | 0.22%   |
| Google                        | 2         | 0.22%   |
| T & A Mobile Phones           | 1         | 0.11%   |
| Sierra Wireless               | 1         | 0.11%   |
| Qualcomm                      | 1         | 0.11%   |
| MediaTek                      | 1         | 0.11%   |
| ICS Advent                    | 1         | 0.11%   |
| Hewlett-Packard               | 1         | 0.11%   |
| D-Link                        | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 366       | 39.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 8.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 69        | 7.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 5.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 1.94%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 1.94%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 1.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.08%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.65%   |
| DisplayLink USB3.0 Dual Video Dock                                | 6         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.43%   |
| Lenovo ThinkPad Lan                                               | 4         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.43%   |
| Intel Ethernet Connection (14) I219-LM                            | 4         | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                            | 4         | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1203      | 57.81%  |
| Ethernet | 857       | 41.18%  |
| Modem    | 17        | 0.82%   |
| Unknown  | 4         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1054      | 81.9%   |
| Ethernet | 232       | 18.03%  |
| Modem    | 1         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 753       | 61.82%  |
| 1     | 429       | 35.22%  |
| 0     | 21        | 1.72%   |
| 3     | 15        | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 920       | 74.98%  |
| Yes  | 307       | 25.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 576       | 54.08%  |
| Realtek Semiconductor           | 137       | 12.86%  |
| Qualcomm Atheros Communications | 87        | 8.17%   |
| IMC Networks                    | 56        | 5.26%   |
| Broadcom                        | 49        | 4.6%    |
| Foxconn / Hon Hai               | 44        | 4.13%   |
| Lite-On Technology              | 33        | 3.1%    |
| Apple                           | 31        | 2.91%   |
| Realtek                         | 12        | 1.13%   |
| Cambridge Silicon Radio         | 11        | 1.03%   |
| Ralink                          | 7         | 0.66%   |
| Toshiba                         | 5         | 0.47%   |
| Hewlett-Packard                 | 5         | 0.47%   |
| Dell                            | 4         | 0.38%   |
| USI                             | 2         | 0.19%   |
| Opticis                         | 2         | 0.19%   |
| ASUSTek Computer                | 2         | 0.19%   |
| Qcom                            | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 159       | 14.92%  |
| Intel AX201 Bluetooth                               | 146       | 13.7%   |
| Realtek Bluetooth Radio                             | 94        | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 8.72%   |
| Intel AX200 Bluetooth                               | 79        | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 65        | 6.1%    |
| Intel AX210 Bluetooth                               | 38        | 3.56%   |
| IMC Networks Wireless_Device                        | 31        | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.35%   |
| Intel Bluetooth Device                              | 25        | 2.35%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 2.16%   |
| Apple Bluetooth Host Controller                     | 21        | 1.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.22%   |
| Realtek 802.11ac WLAN Adapter                       | 12        | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.03%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 9         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.75%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.66%   |
| Lite-On Wireless_Device                             | 7         | 0.66%   |
| Lite-On Bluetooth Device                            | 7         | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.66%   |
| IMC Networks Bluetooth Device                       | 6         | 0.56%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.47%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.38%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.38%   |
| Lite-On Bluetooth Radio                             | 3         | 0.28%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 909       | 57.28%  |
| AMD                                  | 304       | 19.16%  |
| Nvidia                               | 223       | 14.05%  |
| Lenovo                               | 20        | 1.26%   |
| C-Media Electronics                  | 15        | 0.95%   |
| Realtek Semiconductor                | 12        | 0.76%   |
| GN Netcom                            | 12        | 0.76%   |
| Logitech                             | 8         | 0.5%    |
| Hewlett-Packard                      | 7         | 0.44%   |
| Plantronics                          | 6         | 0.38%   |
| Texas Instruments                    | 4         | 0.25%   |
| Samson Technologies                  | 4         | 0.25%   |
| Conexant Systems                     | 4         | 0.25%   |
| Apple                                | 4         | 0.25%   |
| XMOS                                 | 3         | 0.19%   |
| Creative Technology                  | 3         | 0.19%   |
| Corsair                              | 3         | 0.19%   |
| ASUSTek Computer                     | 3         | 0.19%   |
| Yamaha                               | 2         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.13%   |
| Sony                                 | 2         | 0.13%   |
| Sennheiser Communications            | 2         | 0.13%   |
| PreSonus Audio Electronics           | 2         | 0.13%   |
| No brand                             | 2         | 0.13%   |
| Kingston Technology                  | 2         | 0.13%   |
| JMTek                                | 2         | 0.13%   |
| Generalplus Technology               | 2         | 0.13%   |
| Focusrite-Novation                   | 2         | 0.13%   |
| BEHRINGER International              | 2         | 0.13%   |
| Syntek                               | 1         | 0.06%   |
| Sennheiser electronic                | 1         | 0.06%   |
| Samsung Electronics                  | 1         | 0.06%   |
| RODE Microphones                     | 1         | 0.06%   |
| RME                                  | 1         | 0.06%   |
| Razer USA                            | 1         | 0.06%   |
| Medeli Electronics                   | 1         | 0.06%   |
| FiiO Electronics Technology          | 1         | 0.06%   |
| fifinemicrophone.com                 | 1         | 0.06%   |
| FIFINE Microphones                   | 1         | 0.06%   |
| DSEA A/S                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 251       | 12.75%  |
| Intel Sunrise Point-LP HD Audio                                            | 151       | 7.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 146       | 7.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 124       | 6.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 80        | 4.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 2.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 2.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 47        | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 45        | 2.29%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 2.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 43        | 2.18%   |
| Intel Comet Lake PCH cAVS                                                  | 40        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 39        | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 1.73%   |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 30        | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29        | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 28        | 1.42%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 26        | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26        | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 25        | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 23        | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23        | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 22        | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 22        | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 21        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 0.91%   |
| AMD FCH Azalia Controller                                                  | 15        | 0.76%   |
| Nvidia Audio device                                                        | 14        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 0.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12        | 0.61%   |
| Realtek Semiconductor USB Audio                                            | 11        | 0.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 11        | 0.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.46%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 240       | 31.29%  |
| SK hynix                                         | 167       | 21.77%  |
| Micron Technology                                | 123       | 16.04%  |
| Kingston                                         | 51        | 6.65%   |
| Crucial                                          | 46        | 6%      |
| Unknown                                          | 29        | 3.78%   |
| Ramaxel Technology                               | 24        | 3.13%   |
| A-DATA Technology                                | 17        | 2.22%   |
| Unknown (ABCD)                                   | 12        | 1.56%   |
| Patriot                                          | 9         | 1.17%   |
| Smart                                            | 6         | 0.78%   |
| Nanya Technology                                 | 6         | 0.78%   |
| Team                                             | 5         | 0.65%   |
| G.Skill                                          | 5         | 0.65%   |
| Unknown                                          | 5         | 0.65%   |
| Elpida                                           | 4         | 0.52%   |
| Silicon Power                                    | 2         | 0.26%   |
| Corsair                                          | 2         | 0.26%   |
| ChangXin Memory                                  | 2         | 0.26%   |
| V-GEN                                            | 1         | 0.13%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.13%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.13%   |
| Smart Brazil                                     | 1         | 0.13%   |
| Sesame                                           | 1         | 0.13%   |
| Qimonda                                          | 1         | 0.13%   |
| PNY                                              | 1         | 0.13%   |
| Neo Forza                                        | 1         | 0.13%   |
| Kllisre                                          | 1         | 0.13%   |
| Hikvision                                        | 1         | 0.13%   |
| Goldkey                                          | 1         | 0.13%   |
| Atermiter                                        | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.63%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 12        | 1.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 1.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.25%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 1%      |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.75%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.75%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.63%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.63%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.63%   |
| Unknown                                                          | 5         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.5%    |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 4         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.5%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.5%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.5%    |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 4         | 0.5%    |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 4         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 387       | 60.37%  |
| DDR3    | 140       | 21.84%  |
| LPDDR4  | 50        | 7.8%    |
| LPDDR3  | 24        | 3.74%   |
| LPDDR5  | 14        | 2.18%   |
| DDR5    | 14        | 2.18%   |
| Unknown | 6         | 0.94%   |
| DDR2    | 4         | 0.62%   |
| SDRAM   | 1         | 0.16%   |
| DDR     | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 548       | 82.65%  |
| Row Of Chips | 107       | 16.14%  |
| Chip         | 5         | 0.75%   |
| Unknown      | 2         | 0.3%    |
| DIMM         | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 301       | 43.56%  |
| 4096  | 190       | 27.5%   |
| 16384 | 124       | 17.95%  |
| 2048  | 40        | 5.79%   |
| 32768 | 30        | 4.34%   |
| 1024  | 4         | 0.58%   |
| 3072  | 2         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 217       | 31.82%  |
| 2667    | 139       | 20.38%  |
| 1600    | 104       | 15.25%  |
| 2400    | 44        | 6.45%   |
| 2133    | 34        | 4.99%   |
| 4267    | 22        | 3.23%   |
| 6400    | 16        | 2.35%   |
| 4800    | 16        | 2.35%   |
| 1334    | 15        | 2.2%    |
| 1333    | 14        | 2.05%   |
| 1867    | 13        | 1.91%   |
| 3266    | 10        | 1.47%   |
| 1067    | 8         | 1.17%   |
| 8400    | 6         | 0.88%   |
| 4266    | 6         | 0.88%   |
| Unknown | 5         | 0.73%   |
| 3733    | 3         | 0.44%   |
| 667     | 3         | 0.44%   |
| 1066    | 2         | 0.29%   |
| 2800    | 1         | 0.15%   |
| 2048    | 1         | 0.15%   |
| 1777    | 1         | 0.15%   |
| 1200    | 1         | 0.15%   |
| 533     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 4         | 57.14%  |
| Prolific Technology | 1         | 14.29%  |
| NXP Semiconductors  | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| NXP Semiconductors Printer-80 | 1         | 14.29%  |
| Canon TR150 series            | 1         | 14.29%  |
| Canon PIXMA MG3600 Series     | 1         | 14.29%  |
| Canon PIXMA MG3500 Series     | 1         | 14.29%  |
| Canon MF3110                  | 1         | 14.29%  |
| Brother DCP-T220              | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 210                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 275       | 23.71%  |
| IMC Networks                           | 157       | 13.53%  |
| Microdia                               | 104       | 8.97%   |
| Realtek Semiconductor                  | 93        | 8.02%   |
| Quanta                                 | 70        | 6.03%   |
| Bison Electronics                      | 54        | 4.66%   |
| Sunplus Innovation Technology          | 52        | 4.48%   |
| Acer                                   | 52        | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 50        | 4.31%   |
| Luxvisions Innotech Limited            | 37        | 3.19%   |
| Syntek                                 | 34        | 2.93%   |
| Logitech                               | 27        | 2.33%   |
| Apple                                  | 26        | 2.24%   |
| Lite-On Technology                     | 24        | 2.07%   |
| Suyin                                  | 15        | 1.29%   |
| Silicon Motion                         | 11        | 0.95%   |
| Ricoh                                  | 11        | 0.95%   |
| Samsung Electronics                    | 9         | 0.78%   |
| Alcor Micro                            | 8         | 0.69%   |
| Primax Electronics                     | 7         | 0.6%    |
| SunplusIT                              | 5         | 0.43%   |
| Sonix Technology                       | 5         | 0.43%   |
| Lenovo                                 | 4         | 0.34%   |
| icSpring                               | 4         | 0.34%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| Razer USA                              | 2         | 0.17%   |
| KYE Systems (Mouse Systems)            | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| BKX-210918                             | 2         | 0.17%   |
| ARC International                      | 2         | 0.17%   |
| Y Media                                | 1         | 0.09%   |
| Xiaomi                                 | 1         | 0.09%   |
| vivo                                   | 1         | 0.09%   |
| USB Camera CS                          | 1         | 0.09%   |
| ShineTech                              | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| Linux Foundation                       | 1         | 0.09%   |
| Jieli Technology                       | 1         | 0.09%   |
| Intel                                  | 1         | 0.09%   |
| Importek                               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 101       | 8.65%   |
| Microdia Integrated_Webcam_HD                        | 71        | 6.08%   |
| IMC Networks Integrated Camera                       | 60        | 5.14%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 50        | 4.28%   |
| Realtek Integrated_Webcam_HD                         | 37        | 3.17%   |
| Chicony HD Webcam                                    | 29        | 2.49%   |
| Syntek Integrated Camera                             | 25        | 2.14%   |
| Acer Integrated Camera                               | 23        | 1.97%   |
| Sunplus Integrated_Webcam_HD                         | 20        | 1.71%   |
| Quanta HD User Facing                                | 16        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 16        | 1.37%   |
| Chicony Integrated Camera (1280x720@30)              | 15        | 1.29%   |
| Bison HD Webcam                                      | 14        | 1.2%    |
| Quanta HP TrueVision HD Camera                       | 12        | 1.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 12        | 1.03%   |
| Lite-On Integrated Camera                            | 12        | 1.03%   |
| Bison Integrated Camera                              | 12        | 1.03%   |
| Quanta HP HD Camera                                  | 10        | 0.86%   |
| Chicony HP Wide Vision HD Camera                     | 10        | 0.86%   |
| Chicony HP TrueVision HD Camera                      | 10        | 0.86%   |
| Chicony HP HD Camera                                 | 10        | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)              | 9         | 0.77%   |
| IMC Networks HD Camera                               | 9         | 0.77%   |
| Primax HP HD Webcam [Fixed]                          | 7         | 0.6%    |
| Luxvisions Innotech Limited Integrated RGB Camera    | 7         | 0.6%    |
| Logitech HD Pro Webcam C920                          | 7         | 0.6%    |
| Chicony USB2.0 Camera                                | 7         | 0.6%    |
| Chicony USB 2.0 Camera                               | 7         | 0.6%    |
| Chicony EasyCamera                                   | 7         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 7         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 7         | 0.6%    |
| Bison SunplusIT Integrated Camera                    | 7         | 0.6%    |
| Bison HD Camera                                      | 7         | 0.6%    |
| Apple FaceTime HD Camera                             | 7         | 0.6%    |
| Apple Built-in iSight                                | 7         | 0.6%    |
| Acer Lenovo EasyCamera                               | 7         | 0.6%    |
| Sunplus HD WebCam                                    | 6         | 0.51%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 6         | 0.51%   |
| Logitech C920 PRO HD Webcam                          | 6         | 0.51%   |
| Chicony USB2.0 HD UVC WebCam                         | 6         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 112       | 38.23%  |
| Validity Sensors           | 69        | 23.55%  |
| Shenzhen Goodix Technology | 59        | 20.14%  |
| Elan Microelectronics      | 17        | 5.8%    |
| LighTuning Technology      | 13        | 4.44%   |
| Upek                       | 10        | 3.41%   |
| AuthenTec                  | 8         | 2.73%   |
| Focal-systems.Corp         | 3         | 1.02%   |
| STMicroelectronics         | 1         | 0.34%   |
| Dell                       | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 17.06%  |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 12.63%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 6.48%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 5.12%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 4.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3.41%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.41%   |
| Validity Sensors VFS491                                                    | 9         | 3.07%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.07%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 3.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 2.73%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.39%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 2.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.39%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.39%   |
| Synaptics UWP WBDI Device                                                  | 6         | 2.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.71%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.71%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.37%   |
| Synaptics UWP WBDI                                                         | 4         | 1.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.02%   |
| Synaptics  WBDI                                                            | 3         | 1.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.02%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.02%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 1.02%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.68%   |
| Synaptics WBDI Device                                                      | 2         | 0.68%   |
| Synaptics WBDI                                                             | 2         | 0.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.68%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.34%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.34%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.34%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.34%   |
| AuthenTec AES2810                                                          | 1         | 0.34%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 48        | 47.06%  |
| Broadcom                   | 35        | 34.31%  |
| Upek                       | 7         | 6.86%   |
| Lenovo                     | 6         | 5.88%   |
| O2 Micro                   | 2         | 1.96%   |
| SCM Microsystems           | 1         | 0.98%   |
| OmniKey                    | 1         | 0.98%   |
| Gemalto (was Gemplus)      | 1         | 0.98%   |
| Athena Smartcard Solutions | 1         | 0.98%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 46.08%  |
| Broadcom 58200                                                               | 13        | 12.75%  |
| Broadcom 5880                                                                | 8         | 7.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 6.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.86%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.86%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.9%    |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.98%   |
| OmniKey CardMan 1021                                                         | 1         | 0.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.98%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.98%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.98%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.98%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.98%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 683       | 55.3%   |
| 1     | 457       | 37%     |
| 2     | 82        | 6.64%   |
| 3     | 11        | 0.89%   |
| 8     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 288       | 44.58%  |
| Graphics card         | 145       | 22.45%  |
| Multimedia controller | 62        | 9.6%    |
| Camera                | 39        | 6.04%   |
| Net/wireless          | 34        | 5.26%   |
| Chipcard              | 22        | 3.41%   |
| Bluetooth             | 19        | 2.94%   |
| Card reader           | 11        | 1.7%    |
| Storage               | 9         | 1.39%   |
| Network               | 7         | 1.08%   |
| Net/ethernet          | 4         | 0.62%   |
| Modem                 | 4         | 0.62%   |
| Sound                 | 2         | 0.31%   |


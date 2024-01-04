Linux in Latvia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Latvia/Desktop/README.md) and [notebooks](/Location/Latvia/Notebook/README.md).

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

Total: 556

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Precision M4800             | Notebook    | [47508330f1](https://linux-hardware.org/?probe=47508330f1) | Dec 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [552bc11608](https://linux-hardware.org/?probe=552bc11608) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| MSI           | H61M-E33                    | Desktop     | [ed1dc1d923](https://linux-hardware.org/?probe=ed1dc1d923) | Dec 09, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [6667f9e88d](https://linux-hardware.org/?probe=6667f9e88d) | Dec 08, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| Biostar       | B450MH                      | Desktop     | [e490dfb129](https://linux-hardware.org/?probe=e490dfb129) | Dec 02, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [68c7c96b9b](https://linux-hardware.org/?probe=68c7c96b9b) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| Wortmann      | CR700                       | Notebook    | [0c5f9ff4c6](https://linux-hardware.org/?probe=0c5f9ff4c6) | Nov 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [dc40a2bbb1](https://linux-hardware.org/?probe=dc40a2bbb1) | Nov 10, 2023 |
| Wortmann      | CR700                       | Notebook    | [45ed4d1320](https://linux-hardware.org/?probe=45ed4d1320) | Nov 07, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS2... | Convertible | [04a6b532f4](https://linux-hardware.org/?probe=04a6b532f4) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Wortmann      | CR700                       | Notebook    | [916c9bceda](https://linux-hardware.org/?probe=916c9bceda) | Oct 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [75cbcab213](https://linux-hardware.org/?probe=75cbcab213) | Oct 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [0d897e53cf](https://linux-hardware.org/?probe=0d897e53cf) | Sep 21, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [432c1d0b94](https://linux-hardware.org/?probe=432c1d0b94) | Sep 18, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7f55f1b615](https://linux-hardware.org/?probe=7f55f1b615) | Sep 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| HP            | 0A9Ch                       | Desktop     | [f5d07e235d](https://linux-hardware.org/?probe=f5d07e235d) | Aug 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1d9653f23a](https://linux-hardware.org/?probe=1d9653f23a) | Aug 13, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [d552e1a450](https://linux-hardware.org/?probe=d552e1a450) | Aug 08, 2023 |
| Wortmann      | CR700                       | Notebook    | [2f3379e14e](https://linux-hardware.org/?probe=2f3379e14e) | Jul 31, 2023 |
| HP            | ProBook 4530s               | Notebook    | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| Gigabyte      | GA-A55M-S2HP                | Other       | [5b1e00b374](https://linux-hardware.org/?probe=5b1e00b374) | Jul 26, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [cf3b586958](https://linux-hardware.org/?probe=cf3b586958) | Jul 22, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [ce4d4f4137](https://linux-hardware.org/?probe=ce4d4f4137) | Jul 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [9b40832f50](https://linux-hardware.org/?probe=9b40832f50) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| Sony          | VPCCW2S8E                   | Notebook    | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| Wortmann      | CR700                       | Notebook    | [b198dccb29](https://linux-hardware.org/?probe=b198dccb29) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | Notebook    | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| Gigabyte      | P55V6                       | Notebook    | [63d0cd064b](https://linux-hardware.org/?probe=63d0cd064b) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [228a46e465](https://linux-hardware.org/?probe=228a46e465) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [17ed1704c5](https://linux-hardware.org/?probe=17ed1704c5) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [82bab4dd6d](https://linux-hardware.org/?probe=82bab4dd6d) | Jun 04, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [e3dca941cf](https://linux-hardware.org/?probe=e3dca941cf) | May 28, 2023 |
| Wortmann      | CR700                       | Notebook    | [189f1ae92b](https://linux-hardware.org/?probe=189f1ae92b) | May 27, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9327ef1887](https://linux-hardware.org/?probe=9327ef1887) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [bf551b2767](https://linux-hardware.org/?probe=bf551b2767) | May 14, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [66b49186cb](https://linux-hardware.org/?probe=66b49186cb) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1909a7f824](https://linux-hardware.org/?probe=1909a7f824) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [6e0d5c7f28](https://linux-hardware.org/?probe=6e0d5c7f28) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [136fd4098d](https://linux-hardware.org/?probe=136fd4098d) | May 01, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [70899bc374](https://linux-hardware.org/?probe=70899bc374) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [d65df3295e](https://linux-hardware.org/?probe=d65df3295e) | Apr 11, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [5a1cd8556c](https://linux-hardware.org/?probe=5a1cd8556c) | Apr 01, 2023 |
| Biostar       | B550MX/E PRO                | Desktop     | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA8h                       | Desktop     | [fecbec6708](https://linux-hardware.org/?probe=fecbec6708) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| Acer          | Extensa 5630                | Notebook    | [e78d4a3c28](https://linux-hardware.org/?probe=e78d4a3c28) | Mar 14, 2023 |
| Wortmann      | CR700                       | Notebook    | [a48e22ffc5](https://linux-hardware.org/?probe=a48e22ffc5) | Mar 07, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [3574e6c0f8](https://linux-hardware.org/?probe=3574e6c0f8) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [455b0e1401](https://linux-hardware.org/?probe=455b0e1401) | Feb 23, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| MSI           | B75A-G43                    | Desktop     | [bf426ce3c3](https://linux-hardware.org/?probe=bf426ce3c3) | Feb 18, 2023 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [9d36ad089c](https://linux-hardware.org/?probe=9d36ad089c) | Feb 18, 2023 |
| Dell          | Latitude 5330               | Notebook    | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| HP            | ProLiant DL320 G6           | Server      | [0d3689fed9](https://linux-hardware.org/?probe=0d3689fed9) | Feb 09, 2023 |
| Gigabyte      | H55M-D2H                    | Desktop     | [652695efb0](https://linux-hardware.org/?probe=652695efb0) | Feb 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [8f81628b59](https://linux-hardware.org/?probe=8f81628b59) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | Notebook    | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [e98a955b1a](https://linux-hardware.org/?probe=e98a955b1a) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Wortmann      | CR700                       | Notebook    | [0d40cf0690](https://linux-hardware.org/?probe=0d40cf0690) | Jan 22, 2023 |
| MSI           | CR500                       | Notebook    | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9cb7b18b35](https://linux-hardware.org/?probe=9cb7b18b35) | Jan 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [95e7b7d833](https://linux-hardware.org/?probe=95e7b7d833) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [8026c0d5b2](https://linux-hardware.org/?probe=8026c0d5b2) | Jan 17, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4f28b4be44](https://linux-hardware.org/?probe=4f28b4be44) | Jan 15, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4884803279](https://linux-hardware.org/?probe=4884803279) | Jan 10, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [49b7bb70f3](https://linux-hardware.org/?probe=49b7bb70f3) | Jan 10, 2023 |
| HP            | 2AED                        | All in one  | [9a324c230d](https://linux-hardware.org/?probe=9a324c230d) | Jan 09, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [625bf5665f](https://linux-hardware.org/?probe=625bf5665f) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [68bd2484a1](https://linux-hardware.org/?probe=68bd2484a1) | Jan 04, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| HP            | G62                         | Notebook    | [4d80c95e73](https://linux-hardware.org/?probe=4d80c95e73) | Dec 18, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [cc139ec3a3](https://linux-hardware.org/?probe=cc139ec3a3) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [b3c750c720](https://linux-hardware.org/?probe=b3c750c720) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| ASUSTek       | F3Sg                        | Notebook    | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d9a78cb529](https://linux-hardware.org/?probe=d9a78cb529) | Nov 30, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [3d6a965dd4](https://linux-hardware.org/?probe=3d6a965dd4) | Nov 30, 2022 |
| ASUSTek       | G751JL                      | Notebook    | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [6c97b310fb](https://linux-hardware.org/?probe=6c97b310fb) | Nov 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [4768ab429e](https://linux-hardware.org/?probe=4768ab429e) | Nov 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| Wortmann      | CR700                       | Notebook    | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | Notebook    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e267cad212](https://linux-hardware.org/?probe=e267cad212) | Oct 20, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [69adb866e0](https://linux-hardware.org/?probe=69adb866e0) | Oct 20, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [734baf54fa](https://linux-hardware.org/?probe=734baf54fa) | Oct 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9aa6d6be1](https://linux-hardware.org/?probe=e9aa6d6be1) | Jul 06, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e854926e0](https://linux-hardware.org/?probe=8e854926e0) | May 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| HP            | 2AAC                        | Desktop     | [1f6b08507e](https://linux-hardware.org/?probe=1f6b08507e) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [e483a6e634](https://linux-hardware.org/?probe=e483a6e634) | Apr 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | Notebook    | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [83df25aace](https://linux-hardware.org/?probe=83df25aace) | Feb 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [9dfc1ac601](https://linux-hardware.org/?probe=9dfc1ac601) | Feb 12, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [0848fdb73f](https://linux-hardware.org/?probe=0848fdb73f) | Feb 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [36f709712b](https://linux-hardware.org/?probe=36f709712b) | Feb 08, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [834bc65728](https://linux-hardware.org/?probe=834bc65728) | Feb 04, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [887e40e6c7](https://linux-hardware.org/?probe=887e40e6c7) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| MSI           | P55-GD65                    | Desktop     | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [a864c07042](https://linux-hardware.org/?probe=a864c07042) | Dec 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | Notebook    | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | Notebook    | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| HP            | 304Bh                       | Desktop     | [643a84ae14](https://linux-hardware.org/?probe=643a84ae14) | Oct 26, 2021 |
| HP            | 304Bh                       | Desktop     | [b7bd300808](https://linux-hardware.org/?probe=b7bd300808) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [5b32c9197c](https://linux-hardware.org/?probe=5b32c9197c) | Aug 28, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [8cd8b7faa5](https://linux-hardware.org/?probe=8cd8b7faa5) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | Notebook    | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | Notebook    | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | Notebook    | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | Notebook    | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | Notebook    | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | Notebook    | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| MSI           | H310M PRO-VD                | Desktop     | [42ade7f952](https://linux-hardware.org/?probe=42ade7f952) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| Dell          | Latitude 5520               | Notebook    | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [25a9c64af7](https://linux-hardware.org/?probe=25a9c64af7) | May 29, 2021 |
| Acer          | AO725                       | Notebook    | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [2d479e2946](https://linux-hardware.org/?probe=2d479e2946) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [621d19b1f1](https://linux-hardware.org/?probe=621d19b1f1) | May 15, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [796bb8e1b8](https://linux-hardware.org/?probe=796bb8e1b8) | May 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4d87fd7e46](https://linux-hardware.org/?probe=4d87fd7e46) | Apr 13, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d2a175100f](https://linux-hardware.org/?probe=d2a175100f) | Mar 22, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [344b4339b4](https://linux-hardware.org/?probe=344b4339b4) | Mar 17, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1194a50093](https://linux-hardware.org/?probe=1194a50093) | Mar 16, 2021 |
| HP            | 18E7                        | Desktop     | [d0fb912292](https://linux-hardware.org/?probe=d0fb912292) | Mar 09, 2021 |
| Acer          | F671CR R01-C0               | Desktop     | [7a4637f10b](https://linux-hardware.org/?probe=7a4637f10b) | Mar 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [0ac539b524](https://linux-hardware.org/?probe=0ac539b524) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [dbde42fa23](https://linux-hardware.org/?probe=dbde42fa23) | Mar 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a49a1ff054](https://linux-hardware.org/?probe=a49a1ff054) | Feb 27, 2021 |
| HP            | 304Bh                       | Desktop     | [92c6653702](https://linux-hardware.org/?probe=92c6653702) | Feb 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3bc6f280d8](https://linux-hardware.org/?probe=3bc6f280d8) | Feb 19, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [0cfdd76052](https://linux-hardware.org/?probe=0cfdd76052) | Feb 08, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | Notebook    | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | P5GD1-VM                    | Desktop     | [863b2fd0bf](https://linux-hardware.org/?probe=863b2fd0bf) | Jan 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb2b38d97f](https://linux-hardware.org/?probe=cb2b38d97f) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b1abefa3c](https://linux-hardware.org/?probe=5b1abefa3c) | Jan 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [e734d18206](https://linux-hardware.org/?probe=e734d18206) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [b85445cf41](https://linux-hardware.org/?probe=b85445cf41) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [81b3dbf5fd](https://linux-hardware.org/?probe=81b3dbf5fd) | Jan 02, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c3b94fff22](https://linux-hardware.org/?probe=c3b94fff22) | Dec 31, 2020 |
| ASUSTek       | N56VM                       | Notebook    | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [2eede62ff5](https://linux-hardware.org/?probe=2eede62ff5) | Dec 26, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8cf512e3a9](https://linux-hardware.org/?probe=8cf512e3a9) | Dec 26, 2020 |
| ASUSTek       | P5K PRO                     | Desktop     | [0e58a56cfb](https://linux-hardware.org/?probe=0e58a56cfb) | Dec 26, 2020 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [bb01071f16](https://linux-hardware.org/?probe=bb01071f16) | Dec 15, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| Acer          | Aspire E5-774G              | Notebook    | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| MSI           | B75A-G43                    | Desktop     | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| ASUSTek       | F9S                         | Notebook    | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | Notebook    | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f2ff00472b](https://linux-hardware.org/?probe=f2ff00472b) | Nov 07, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bdb367a3b2](https://linux-hardware.org/?probe=bdb367a3b2) | Nov 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [5139c9e029](https://linux-hardware.org/?probe=5139c9e029) | Nov 01, 2020 |
| Acer          | Aspire E1-570               | Notebook    | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7ac6a6dab5](https://linux-hardware.org/?probe=7ac6a6dab5) | Oct 27, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [3ea3e1a644](https://linux-hardware.org/?probe=3ea3e1a644) | Oct 26, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [c9a44de2e0](https://linux-hardware.org/?probe=c9a44de2e0) | Oct 26, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [4e526c6262](https://linux-hardware.org/?probe=4e526c6262) | Oct 14, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [a37fe628b4](https://linux-hardware.org/?probe=a37fe628b4) | Oct 04, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [c6cf49892e](https://linux-hardware.org/?probe=c6cf49892e) | Oct 04, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [a6c2ba4977](https://linux-hardware.org/?probe=a6c2ba4977) | Oct 04, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ebefa289ab](https://linux-hardware.org/?probe=ebefa289ab) | Sep 30, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [2702ecbebe](https://linux-hardware.org/?probe=2702ecbebe) | Sep 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [177f17803c](https://linux-hardware.org/?probe=177f17803c) | Aug 24, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | Notebook    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b68bc64592](https://linux-hardware.org/?probe=b68bc64592) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d5429ba62e](https://linux-hardware.org/?probe=d5429ba62e) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | Notebook    | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [625d32881c](https://linux-hardware.org/?probe=625d32881c) | May 29, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | Notebook    | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d6cb669e](https://linux-hardware.org/?probe=d6d6cb669e) | Apr 29, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [31631f3ea5](https://linux-hardware.org/?probe=31631f3ea5) | Apr 23, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [8f1f828d49](https://linux-hardware.org/?probe=8f1f828d49) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [95e2b82808](https://linux-hardware.org/?probe=95e2b82808) | Mar 26, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [9fcf5501fb](https://linux-hardware.org/?probe=9fcf5501fb) | Mar 26, 2020 |
| IBM           | 8215ZCL                     | Desktop     | [8f44ceaa1e](https://linux-hardware.org/?probe=8f44ceaa1e) | Mar 26, 2020 |
| Dell          | Latitude E6230              | Notebook    | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | Notebook    | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | Notebook    | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [2d568b2e9d](https://linux-hardware.org/?probe=2d568b2e9d) | Feb 19, 2020 |
| ASUSTek       | BU401LAV                    | Notebook    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| MSI           | Z370 SLI PLUS               | Desktop     | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | Notebook    | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | Notebook    | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [9deccd0d74](https://linux-hardware.org/?probe=9deccd0d74) | Jan 24, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e005197c6c](https://linux-hardware.org/?probe=e005197c6c) | Jan 09, 2020 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5af3a0243a](https://linux-hardware.org/?probe=5af3a0243a) | Jan 06, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [70297101fe](https://linux-hardware.org/?probe=70297101fe) | Dec 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Dell          | 0RJ290                      | Desktop     | [21ae6dbdf0](https://linux-hardware.org/?probe=21ae6dbdf0) | Dec 16, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | Notebook    | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bab2716ff6](https://linux-hardware.org/?probe=bab2716ff6) | Dec 02, 2019 |
| Dell          | Latitude D630               | Notebook    | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | Notebook    | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | Notebook    | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | Notebook    | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | Notebook    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | Notebook    | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | Notebook    | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a6d137277e](https://linux-hardware.org/?probe=a6d137277e) | Sep 18, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [2fc2bdd742](https://linux-hardware.org/?probe=2fc2bdd742) | Sep 14, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5110001e92](https://linux-hardware.org/?probe=5110001e92) | Sep 14, 2019 |
| Gigabyte      | Z87P-D3                     | Desktop     | [a7e732af2a](https://linux-hardware.org/?probe=a7e732af2a) | Aug 26, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [5c290c18c9](https://linux-hardware.org/?probe=5c290c18c9) | Aug 18, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | 0A60h                       | Desktop     | [b031cf2f9c](https://linux-hardware.org/?probe=b031cf2f9c) | Jul 30, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | Notebook    | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| MSI           | FM2-A55M-E33                | Desktop     | [426ae68b93](https://linux-hardware.org/?probe=426ae68b93) | Jun 29, 2019 |
| MSI           | B85-G41 PC Mate             | Desktop     | [0f3dccfe4e](https://linux-hardware.org/?probe=0f3dccfe4e) | Jun 26, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | Notebook    | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | Notebook    | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | Notebook    | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | Notebook    | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [5e414bc536](https://linux-hardware.org/?probe=5e414bc536) | Mar 14, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | Notebook    | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [3437fc1ab6](https://linux-hardware.org/?probe=3437fc1ab6) | Feb 12, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [f08ce9bd47](https://linux-hardware.org/?probe=f08ce9bd47) | Jan 09, 2019 |
| Dell          | Inspiron 1720               | Notebook    | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | Notebook    | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | Notebook    | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | Notebook    | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | Notebook    | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Dell          | 0WK833                      | Desktop     | [17e742f811](https://linux-hardware.org/?probe=17e742f811) | Jul 11, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Dell          | 0WK833                      | Desktop     | [d118bf168b](https://linux-hardware.org/?probe=d118bf168b) | Jun 28, 2018 |
| Dell          | 0WK833                      | Desktop     | [0e39368786](https://linux-hardware.org/?probe=0e39368786) | Jun 28, 2018 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [c401108ba6](https://linux-hardware.org/?probe=c401108ba6) | Jun 20, 2018 |
| Acer          | Aspire V5-552G              | Notebook    | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Gigabyte      | H55M-D2H                    | Desktop     | [e4e92393a0](https://linux-hardware.org/?probe=e4e92393a0) | Mar 08, 2018 |
| Dell          | XPS MXC062                  | Notebook    | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | Notebook    | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [f4d998043d](https://linux-hardware.org/?probe=f4d998043d) | Jan 29, 2018 |
| ASUSTek       | K73BE                       | Notebook    | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| ASUSTek       | A88XM-A                     | Desktop     | [f7b8e36550](https://linux-hardware.org/?probe=f7b8e36550) | Jan 21, 2018 |
| Acer          | F671CR R01-C0               | Desktop     | [a5b92562b9](https://linux-hardware.org/?probe=a5b92562b9) | Dec 26, 2017 |
| MSI           | MS-7519                     | Desktop     | [81563b0ef8](https://linux-hardware.org/?probe=81563b0ef8) | Nov 18, 2017 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | Notebook    | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| MSI           | MS-7519                     | Desktop     | [5e4728fda0](https://linux-hardware.org/?probe=5e4728fda0) | Sep 17, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | Notebook    | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | Notebook    | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| ASRock        | G31M-GS                     | Desktop     | [7a4eee4480](https://linux-hardware.org/?probe=7a4eee4480) | May 31, 2017 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [bfab333807](https://linux-hardware.org/?probe=bfab333807) | May 03, 2017 |
| Acer          | EG31M R01-A2                | Desktop     | [018dafc2d0](https://linux-hardware.org/?probe=018dafc2d0) | Apr 27, 2017 |
| eMachines     | Unknown                     | Notebook    | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | Notebook    | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | Notebook    | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | P5Q                         | Desktop     | [26e2520232](https://linux-hardware.org/?probe=26e2520232) | Nov 11, 2016 |
| ASUSTek       | K53SD                       | Notebook    | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | Notebook    | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | Notebook    | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Latvia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 32        | 8.12%   |
| ROSA R11           | 19        | 4.82%   |
| Ubuntu 18.04       | 15        | 3.81%   |
| Ubuntu 22.04       | 14        | 3.55%   |
| ROSA R10           | 12        | 3.05%   |
| Arch Rolling       | 12        | 3.05%   |
| ROSA R9            | 10        | 2.54%   |
| KDE neon 20.04     | 9         | 2.28%   |
| Pop!_OS 22.04      | 8         | 2.03%   |
| Debian 11          | 8         | 2.03%   |
| Arch               | 8         | 2.03%   |
| ROSA R8.1          | 7         | 1.78%   |
| OpenMandriva 4.3   | 7         | 1.78%   |
| ROSA R11.1         | 6         | 1.52%   |
| OpenMandriva 23.01 | 6         | 1.52%   |
| Linux Mint 20.3    | 6         | 1.52%   |
| Linux Mint 20.1    | 6         | 1.52%   |
| Fedora 37          | 6         | 1.52%   |
| Xubuntu 20.04      | 5         | 1.27%   |
| ROSA R8            | 5         | 1.27%   |
| Pop!_OS 21.04      | 5         | 1.27%   |
| Pop!_OS 20.10      | 5         | 1.27%   |
| Manjaro            | 5         | 1.27%   |
| Linux Mint 21.1    | 5         | 1.27%   |
| Linux Mint 21      | 5         | 1.27%   |
| Ubuntu 19.10       | 4         | 1.02%   |
| ROSA 12.3          | 4         | 1.02%   |
| ROSA 12.2          | 4         | 1.02%   |
| OpenMandriva 4.50  | 4         | 1.02%   |
| Linux Mint 19      | 4         | 1.02%   |
| KDE neon 22.04     | 4         | 1.02%   |
| Fedora 38          | 4         | 1.02%   |
| Debian Testing     | 4         | 1.02%   |
| Debian 12          | 4         | 1.02%   |
| ArcoLinux Rolling  | 4         | 1.02%   |
| Zorin 16           | 3         | 0.76%   |
| ROSA 12.1          | 3         | 0.76%   |
| OpenMandriva 4.2   | 3         | 0.76%   |
| OpenMandriva 23.08 | 3         | 0.76%   |
| Linux Mint 20.2    | 3         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 80        | 22.41%  |
| ROSA          | 54        | 15.13%  |
| Linux Mint    | 36        | 10.08%  |
| OpenMandriva  | 24        | 6.72%   |
| Fedora        | 22        | 6.16%   |
| Arch          | 20        | 5.6%    |
| Pop!_OS       | 19        | 5.32%   |
| Debian        | 17        | 4.76%   |
| KDE neon      | 13        | 3.64%   |
| Manjaro       | 11        | 3.08%   |
| Xubuntu       | 8         | 2.24%   |
| Kubuntu       | 6         | 1.68%   |
| ArcoLinux     | 5         | 1.4%    |
| Zorin         | 3         | 0.84%   |
| openSUSE      | 3         | 0.84%   |
| Kali          | 3         | 0.84%   |
| Garuda Linux  | 3         | 0.84%   |
| Endless       | 3         | 0.84%   |
| EndeavourOS   | 3         | 0.84%   |
| Elementary    | 3         | 0.84%   |
| Ubuntu Unity  | 2         | 0.56%   |
| SteamOS       | 2         | 0.56%   |
| Lubuntu       | 2         | 0.56%   |
| Clear Linux   | 2         | 0.56%   |
| Void Linux    | 1         | 0.28%   |
| Ubuntu MATE   | 1         | 0.28%   |
| Ubuntu Budgie | 1         | 0.28%   |
| Solus         | 1         | 0.28%   |
| Puppy         | 1         | 0.28%   |
| Peppermint    | 1         | 0.28%   |
| Parrot        | 1         | 0.28%   |
| Oracle Linux  | 1         | 0.28%   |
| NixOS         | 1         | 0.28%   |
| MX            | 1         | 0.28%   |
| LMDE          | 1         | 0.28%   |
| GNOME OS      | 1         | 0.28%   |
| ALT Linux     | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 10        | 2.26%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 9         | 2.04%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 8         | 1.81%   |
| 5.16.7-desktop-1omv4003            | 7         | 1.58%   |
| 6.1.1-desktop-1omv2290             | 6         | 1.36%   |
| 5.4.0-42-generic                   | 6         | 1.36%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 1.13%   |
| 5.4.0-58-generic                   | 4         | 0.9%    |
| 5.4.0-132-generic                  | 4         | 0.9%    |
| 5.4.0-122-generic                  | 4         | 0.9%    |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 4         | 0.9%    |
| 6.5.7-200.fc38.x86_64              | 3         | 0.68%   |
| 6.2.6-76060206-generic             | 3         | 0.68%   |
| 5.8.0-7630-generic                 | 3         | 0.68%   |
| 5.4.83-generic-2rosa-x86_64        | 3         | 0.68%   |
| 5.4.0-80-generic                   | 3         | 0.68%   |
| 5.4.0-66-generic                   | 3         | 0.68%   |
| 5.4.0-54-generic                   | 3         | 0.68%   |
| 5.4.0-52-generic                   | 3         | 0.68%   |
| 5.15.0-86-generic                  | 3         | 0.68%   |
| 5.15.0-67-generic                  | 3         | 0.68%   |
| 5.15.0-58-generic                  | 3         | 0.68%   |
| 5.13.0-25-generic                  | 3         | 0.68%   |
| 5.12.4-desktop-1omv4050            | 3         | 0.68%   |
| 5.10.14-desktop-1omv4002           | 3         | 0.68%   |
| 5.0.0-37-generic                   | 3         | 0.68%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 0.68%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 0.68%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 0.68%   |
| 6.4.11-desktop-1omv2390            | 2         | 0.45%   |
| 6.2.6-desktop-1omv2390             | 2         | 0.45%   |
| 6.2.0-26-generic                   | 2         | 0.45%   |
| 6.2.0-20-generic                   | 2         | 0.45%   |
| 5.8.0-48-generic                   | 2         | 0.45%   |
| 5.8.0-25-generic                   | 2         | 0.45%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.45%   |
| 5.4.0-67-generic                   | 2         | 0.45%   |
| 5.4.0-47-generic                   | 2         | 0.45%   |
| 5.4.0-26-generic                   | 2         | 0.45%   |
| 5.4.0-100-generic                  | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 54        | 13.14%  |
| 4.15.0  | 32        | 7.79%   |
| 5.15.0  | 27        | 6.57%   |
| 5.13.0  | 15        | 3.65%   |
| 5.8.0   | 14        | 3.41%   |
| 5.11.0  | 14        | 3.41%   |
| 4.9.20  | 11        | 2.68%   |
| 5.3.0   | 10        | 2.43%   |
| 5.10.0  | 10        | 2.43%   |
| 6.2.0   | 9         | 2.19%   |
| 5.19.0  | 8         | 1.95%   |
| 4.9.60  | 8         | 1.95%   |
| 6.1.1   | 7         | 1.7%    |
| 5.16.7  | 7         | 1.7%    |
| 5.0.0   | 6         | 1.46%   |
| 6.2.6   | 5         | 1.22%   |
| 5.10.74 | 5         | 1.22%   |
| 4.18.0  | 5         | 1.22%   |
| 4.9.155 | 4         | 0.97%   |
| 4.1.34  | 4         | 0.97%   |
| 6.5.7   | 3         | 0.73%   |
| 6.5.0   | 3         | 0.73%   |
| 6.1.0   | 3         | 0.73%   |
| 5.4.83  | 3         | 0.73%   |
| 5.17.1  | 3         | 0.73%   |
| 5.14.0  | 3         | 0.73%   |
| 5.12.4  | 3         | 0.73%   |
| 5.10.14 | 3         | 0.73%   |
| 4.9.41  | 3         | 0.73%   |
| 6.6.1   | 2         | 0.49%   |
| 6.4.11  | 2         | 0.49%   |
| 6.1.9   | 2         | 0.49%   |
| 6.0.9   | 2         | 0.49%   |
| 6.0.7   | 2         | 0.49%   |
| 5.9.0   | 2         | 0.49%   |
| 5.4.72  | 2         | 0.49%   |
| 5.4.32  | 2         | 0.49%   |
| 5.17.5  | 2         | 0.49%   |
| 5.16.15 | 2         | 0.49%   |
| 5.15.79 | 2         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 62        | 15.46%  |
| 5.15    | 39        | 9.73%   |
| 4.15    | 32        | 7.98%   |
| 4.9     | 27        | 6.73%   |
| 5.10    | 24        | 5.99%   |
| 5.13    | 20        | 4.99%   |
| 6.1     | 19        | 4.74%   |
| 5.11    | 19        | 4.74%   |
| 5.8     | 18        | 4.49%   |
| 6.2     | 14        | 3.49%   |
| 5.19    | 12        | 2.99%   |
| 5.16    | 12        | 2.99%   |
| 6.0     | 11        | 2.74%   |
| 5.3     | 10        | 2.49%   |
| 5.12    | 8         | 2%      |
| 6.5     | 7         | 1.75%   |
| 5.17    | 6         | 1.5%    |
| 5.0     | 6         | 1.5%    |
| 6.6     | 5         | 1.25%   |
| 5.18    | 5         | 1.25%   |
| 5.14    | 5         | 1.25%   |
| 4.18    | 5         | 1.25%   |
| 4.1     | 5         | 1.25%   |
| 6.4     | 4         | 1%      |
| 5.9     | 4         | 1%      |
| 6.3     | 3         | 0.75%   |
| 5.5     | 3         | 0.75%   |
| 5.2     | 3         | 0.75%   |
| 5.6     | 2         | 0.5%    |
| 4.4     | 2         | 0.5%    |
| 4.19    | 2         | 0.5%    |
| 4.13    | 2         | 0.5%    |
| 4.10    | 2         | 0.5%    |
| 5.7     | 1         | 0.25%   |
| 4.8     | 1         | 0.25%   |
| 4.20    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 325       | 95.31%  |
| i686    | 13        | 3.81%   |
| aarch64 | 3         | 0.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 129       | 35.05%  |
| KDE5       | 84        | 22.83%  |
| KDE4       | 34        | 9.24%   |
| Unknown    | 32        | 8.7%    |
| XFCE       | 25        | 6.79%   |
| X-Cinnamon | 18        | 4.89%   |
| MATE       | 15        | 4.08%   |
| KDE        | 9         | 2.45%   |
| LXQt       | 4         | 1.09%   |
| Cinnamon   | 4         | 1.09%   |
| Budgie     | 4         | 1.09%   |
| Pantheon   | 3         | 0.82%   |
| Unity      | 2         | 0.54%   |
| Deepin     | 2         | 0.54%   |
| sway       | 1         | 0.27%   |
| LXDE       | 1         | 0.27%   |
| i3         | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 271       | 76.99%  |
| Wayland | 59        | 16.76%  |
| Unknown | 13        | 3.69%   |
| Tty     | 9         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 143       | 39.39%  |
| SDDM    | 70        | 19.28%  |
| GDM     | 44        | 12.12%  |
| KDM     | 34        | 9.37%   |
| LightDM | 30        | 8.26%   |
| GDM3    | 24        | 6.61%   |
| TDM     | 15        | 4.13%   |
| SLiM    | 1         | 0.28%   |
| MDM     | 1         | 0.28%   |
| LDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 168       | 46.8%   |
| Unknown     | 65        | 18.11%  |
| lv_LV       | 46        | 12.81%  |
| ru_RU       | 43        | 11.98%  |
| en_GB       | 17        | 4.74%   |
| C           | 10        | 2.79%   |
| ru_RU.UTF_8 | 2         | 0.56%   |
| en_AG       | 2         | 0.56%   |
| de_DE       | 2         | 0.56%   |
| POSIX       | 1         | 0.28%   |
| osa_US      | 1         | 0.28%   |
| fr_FR       | 1         | 0.28%   |
| cv_RU       | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 194       | 56.07%  |
| EFI  | 152       | 43.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 255       | 71.63%  |
| Btrfs   | 36        | 10.11%  |
| Unknown | 28        | 7.87%   |
| Overlay | 23        | 6.46%   |
| Tmpfs   | 9         | 2.53%   |
| Zfs     | 2         | 0.56%   |
| Xfs     | 1         | 0.28%   |
| Ext3    | 1         | 0.28%   |
| Aufs    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 154       | 42.9%   |
| GPT     | 134       | 37.33%  |
| MBR     | 71        | 19.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 306       | 85.96%  |
| Yes       | 50        | 14.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 256       | 72.73%  |
| Yes       | 96        | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 67        | 19.65%  |
| Lenovo                               | 56        | 16.42%  |
| Hewlett-Packard                      | 40        | 11.73%  |
| Dell                                 | 34        | 9.97%   |
| Acer                                 | 27        | 7.92%   |
| MSI                                  | 24        | 7.04%   |
| Gigabyte Technology                  | 23        | 6.74%   |
| ASRock                               | 13        | 3.81%   |
| Toshiba                              | 6         | 1.76%   |
| Intel                                | 6         | 1.76%   |
| Fujitsu Siemens                      | 6         | 1.76%   |
| Samsung Electronics                  | 4         | 1.17%   |
| Apple                                | 4         | 1.17%   |
| Packard Bell                         | 3         | 0.88%   |
| HUAWEI                               | 3         | 0.88%   |
| Biostar                              | 3         | 0.88%   |
| TUXEDO                               | 2         | 0.59%   |
| Raspberry Pi Foundation              | 2         | 0.59%   |
| Wortmann AG                          | 1         | 0.29%   |
| Valve                                | 1         | 0.29%   |
| Timi                                 | 1         | 0.29%   |
| Sony                                 | 1         | 0.29%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.29%   |
| Rockchip                             | 1         | 0.29%   |
| Razer                                | 1         | 0.29%   |
| Quanta                               | 1         | 0.29%   |
| IBM                                  | 1         | 0.29%   |
| Hardkernel                           | 1         | 0.29%   |
| Fujitsu                              | 1         | 0.29%   |
| Foxconn                              | 1         | 0.29%   |
| eMachines                            | 1         | 0.29%   |
| Chuwi                                | 1         | 0.29%   |
| Advent                               | 1         | 0.29%   |
| Acidanthera                          | 1         | 0.29%   |
| ABIT                                 | 1         | 0.29%   |
| Unknown                              | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 6         | 1.76%   |
| HP EliteBook 840 G3                                   | 3         | 0.88%   |
| ASUS X553MA                                           | 3         | 0.88%   |
| Unknown                                               | 3         | 0.88%   |
| Toshiba Satellite C660                                | 2         | 0.59%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.59%   |
| MSI MS-7721                                           | 2         | 0.59%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.59%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.59%   |
| HP G62                                                | 2         | 0.59%   |
| HP EliteBook 8440p                                    | 2         | 0.59%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.59%   |
| Gigabyte G33M-S2                                      | 2         | 0.59%   |
| Gigabyte B550 AORUS PRO V2                            | 2         | 0.59%   |
| Gigabyte 946GMX-S2                                    | 2         | 0.59%   |
| Fujitsu Siemens LIFEBOOK S6420                        | 2         | 0.59%   |
| Dell OptiPlex 7020                                    | 2         | 0.59%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.59%   |
| ASUS X551MA                                           | 2         | 0.59%   |
| ASUS TUF Gaming X570-PLUS                             | 2         | 0.59%   |
| Apple MacBookPro8,1                                   | 2         | 0.59%   |
| Wortmann AG CR700                                     | 1         | 0.29%   |
| Valve Jupiter                                         | 1         | 0.29%   |
| TUXEDO Gemini Gen2                                    | 1         | 0.29%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.29%   |
| Toshiba Satellite L750                                | 1         | 0.29%   |
| Toshiba Satellite L350                                | 1         | 0.29%   |
| Toshiba Satellite C50D-B                              | 1         | 0.29%   |
| Timi A35S                                             | 1         | 0.29%   |
| Sony VPCCW2S8E                                        | 1         | 0.29%   |
| Shenzhen Meigao Electronic Equipment UM450            | 1         | 0.29%   |
| Samsung R528/R728                                     | 1         | 0.29%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.29%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.29%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.29%   |
| Rockchip Orange Pi 5                                  | 1         | 0.29%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.29%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.29%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.29%   |
| Packard Bell EasyNote LM85                            | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 31        | 9.09%   |
| Acer Aspire              | 17        | 4.99%   |
| HP EliteBook             | 12        | 3.52%   |
| Dell Inspiron            | 11        | 3.23%   |
| Lenovo IdeaPad           | 10        | 2.93%   |
| Dell Latitude            | 10        | 2.93%   |
| Dell OptiPlex            | 7         | 2.05%   |
| Toshiba Satellite        | 6         | 1.76%   |
| ASUS All                 | 6         | 1.76%   |
| HP ProBook               | 5         | 1.47%   |
| HP Pavilion              | 5         | 1.47%   |
| ASUS VivoBook            | 5         | 1.47%   |
| ASUS ROG                 | 5         | 1.47%   |
| ASUS PRIME               | 5         | 1.47%   |
| Lenovo Legion            | 4         | 1.17%   |
| ASUS Zenbook             | 4         | 1.17%   |
| ASUS TUF                 | 4         | 1.17%   |
| Packard Bell EasyNote    | 3         | 0.88%   |
| HP Compaq                | 3         | 0.88%   |
| HP 250                   | 3         | 0.88%   |
| Fujitsu Siemens LIFEBOOK | 3         | 0.88%   |
| ASUS X553MA              | 3         | 0.88%   |
| Unknown                  | 3         | 0.88%   |
| RPi Raspberry            | 2         | 0.59%   |
| MSI MS-7721              | 2         | 0.59%   |
| MSI Katana               | 2         | 0.59%   |
| Lenovo Yoga              | 2         | 0.59%   |
| Lenovo ThinkBook         | 2         | 0.59%   |
| HP Laptop                | 2         | 0.59%   |
| HP G62                   | 2         | 0.59%   |
| Gigabyte G33M-S2         | 2         | 0.59%   |
| Gigabyte B550            | 2         | 0.59%   |
| Gigabyte 946GMX-S2       | 2         | 0.59%   |
| Fujitsu Siemens AMILO    | 2         | 0.59%   |
| Dell XPS                 | 2         | 0.59%   |
| Dell Precision           | 2         | 0.59%   |
| ASUS X551MA              | 2         | 0.59%   |
| ASUS P5Q                 | 2         | 0.59%   |
| ASUS ASUS                | 2         | 0.59%   |
| Apple MacBookPro8        | 2         | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 33        | 9.68%   |
| 2019    | 32        | 9.38%   |
| 2012    | 26        | 7.62%   |
| 2008    | 23        | 6.74%   |
| 2018    | 22        | 6.45%   |
| 2014    | 22        | 6.45%   |
| 2007    | 21        | 6.16%   |
| 2020    | 19        | 5.57%   |
| 2011    | 19        | 5.57%   |
| 2017    | 18        | 5.28%   |
| 2015    | 18        | 5.28%   |
| 2010    | 18        | 5.28%   |
| 2009    | 17        | 4.99%   |
| 2021    | 15        | 4.4%    |
| 2022    | 12        | 3.52%   |
| 2016    | 11        | 3.23%   |
| 2006    | 6         | 1.76%   |
| 2023    | 5         | 1.47%   |
| Unknown | 3         | 0.88%   |
| 2004    | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 216       | 63.34%  |
| Desktop        | 111       | 32.55%  |
| Convertible    | 5         | 1.47%   |
| System on chip | 3         | 0.88%   |
| Mini pc        | 3         | 0.88%   |
| Other          | 1         | 0.29%   |
| All in one     | 1         | 0.29%   |
| Server         | 1         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 321       | 93.31%  |
| Enabled  | 23        | 6.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 340       | 99.71%  |
| Yes  | 1         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 85        | 24.36%  |
| 4.01-8.0        | 80        | 22.92%  |
| 8.01-16.0       | 60        | 17.19%  |
| 16.01-24.0      | 54        | 15.47%  |
| 32.01-64.0      | 32        | 9.17%   |
| 1.01-2.0        | 14        | 4.01%   |
| 2.01-3.0        | 12        | 3.44%   |
| 24.01-32.0      | 7         | 2.01%   |
| 64.01-256.0     | 2         | 0.57%   |
| 0.51-1.0        | 2         | 0.57%   |
| More than 256.0 | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 126       | 32.23%  |
| 2.01-3.0   | 94        | 24.04%  |
| 4.01-8.0   | 55        | 14.07%  |
| 0.51-1.0   | 52        | 13.3%   |
| 3.01-4.0   | 42        | 10.74%  |
| 8.01-16.0  | 17        | 4.35%   |
| 16.01-24.0 | 3         | 0.77%   |
| 24.01-32.0 | 1         | 0.26%   |
| 0.01-0.5   | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 222       | 62.54%  |
| 2      | 81        | 22.82%  |
| 3      | 31        | 8.73%   |
| 4      | 12        | 3.38%   |
| 5      | 4         | 1.13%   |
| 6      | 2         | 0.56%   |
| 0      | 2         | 0.56%   |
| 7      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 204       | 58.45%  |
| Yes       | 145       | 41.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 310       | 90.38%  |
| No        | 33        | 9.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 76.32%  |
| No        | 81        | 23.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 57.23%  |
| No        | 148       | 42.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Latvia  | 341       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Riga                    | 257       | 70.41%  |
| Liepāja                | 10        | 2.74%   |
| Jelgava                 | 10        | 2.74%   |
| Daugavpils              | 8         | 2.19%   |
| Ventspils               | 6         | 1.64%   |
| Salaspils               | 5         | 1.37%   |
| Jūrmala                | 5         | 1.37%   |
| Adazi                   | 5         | 1.37%   |
| Iecava                  | 4         | 1.1%    |
| Valmiera                | 3         | 0.82%   |
| Limbaži                | 3         | 0.82%   |
| Jēkabpils              | 3         | 0.82%   |
| Jaunmarupe              | 3         | 0.82%   |
| Talsi                   | 2         | 0.55%   |
| Saulkrasti              | 2         | 0.55%   |
| Rēzekne                | 2         | 0.55%   |
| Ogre                    | 2         | 0.55%   |
| Malpils                 | 2         | 0.55%   |
| Kuldīga                | 2         | 0.55%   |
| Cēsis                  | 2         | 0.55%   |
| Aizkraukle              | 2         | 0.55%   |
| Zvejniekciems           | 1         | 0.27%   |
| Ulbroka                 | 1         | 0.27%   |
| Tukums                  | 1         | 0.27%   |
| Tiraine                 | 1         | 0.27%   |
| Smiltene                | 1         | 0.27%   |
| Saulkalne               | 1         | 0.27%   |
| Saldus                  | 1         | 0.27%   |
| Roya                    | 1         | 0.27%   |
| Ragana                  | 1         | 0.27%   |
| Pļaviņas              | 1         | 0.27%   |
| Nereta                  | 1         | 0.27%   |
| Mirnijs                 | 1         | 0.27%   |
| Lizums                  | 1         | 0.27%   |
| Lielvārde              | 1         | 0.27%   |
| Ķekava                 | 1         | 0.27%   |
| Jēkabpils Municipality | 1         | 0.27%   |
| Inčukalns              | 1         | 0.27%   |
| Gulbene                 | 1         | 0.27%   |
| Garkalne                | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 81        | 109    | 16.53%  |
| Samsung Electronics          | 79        | 126    | 16.12%  |
| WDC                          | 71        | 110    | 14.49%  |
| Kingston                     | 45        | 69     | 9.18%   |
| Toshiba                      | 30        | 35     | 6.12%   |
| Crucial                      | 17        | 26     | 3.47%   |
| Hitachi                      | 16        | 21     | 3.27%   |
| Intel                        | 13        | 21     | 2.65%   |
| Unknown                      | 11        | 15     | 2.24%   |
| HGST                         | 11        | 20     | 2.24%   |
| Micron Technology            | 10        | 11     | 2.04%   |
| A-DATA Technology            | 9         | 11     | 1.84%   |
| SK hynix                     | 8         | 8      | 1.63%   |
| SanDisk                      | 8         | 18     | 1.63%   |
| SPCC                         | 5         | 7      | 1.02%   |
| Patriot                      | 5         | 11     | 1.02%   |
| Kingston Technology Company  | 5         | 6      | 1.02%   |
| KIOXIA                       | 4         | 6      | 0.82%   |
| Transcend                    | 3         | 3      | 0.61%   |
| Phison Electronics           | 3         | 4      | 0.61%   |
| OCZ                          | 3         | 4      | 0.61%   |
| Intenso                      | 3         | 3      | 0.61%   |
| GOODRAM                      | 3         | 8      | 0.61%   |
| XPG                          | 2         | 2      | 0.41%   |
| Silicon Motion               | 2         | 2      | 0.41%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.41%   |
| Phison                       | 2         | 2      | 0.41%   |
| Netac                        | 2         | 2      | 0.41%   |
| LITEON                       | 2         | 2      | 0.41%   |
| Lexar                        | 2         | 2      | 0.41%   |
| Integral                     | 2         | 2      | 0.41%   |
| China                        | 2         | 2      | 0.41%   |
| Verbatim                     | 1         | 1      | 0.2%    |
| USB                          | 1         | 1      | 0.2%    |
| Union Memory (Shenzhen)      | 1         | 1      | 0.2%    |
| RSH-338H                     | 1         | 2      | 0.2%    |
| Realtek Semiconductor        | 1         | 1      | 0.2%    |
| Realtek                      | 1         | 1      | 0.2%    |
| PNY                          | 1         | 1      | 0.2%    |
| Plextor                      | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 12        | 2.25%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 1.31%   |
| Kingston SV300S37A120G 120GB SSD                    | 7         | 1.31%   |
| Samsung SSD 850 EVO 500GB                           | 6         | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5         | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5         | 0.94%   |
| Crucial CT1000MX500SSD1 1TB                         | 5         | 0.94%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB                      | 4         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 0.75%   |
| Samsung SSD 970 EVO Plus 500GB                      | 4         | 0.75%   |
| Kingston SV300S37A240G 240GB SSD                    | 4         | 0.75%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 0.75%   |
| WDC WD2000JD-00HBB0 200GB                           | 3         | 0.56%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.56%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 0.56%   |
| Seagate ST500DM005 HD502HJ 500GB                    | 3         | 0.56%   |
| Seagate ST3500418AS 500GB                           | 3         | 0.56%   |
| Samsung SSD 870 QVO 1TB                             | 3         | 0.56%   |
| Samsung SSD 650 120GB                               | 3         | 0.56%   |
| Samsung NVMe SSD Drive 500GB                        | 3         | 0.56%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 3         | 0.56%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 3         | 0.56%   |
| Patriot Burst 240GB SSD                             | 3         | 0.56%   |
| Kingston SV300S37A60G 64GB SSD                      | 3         | 0.56%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.56%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.56%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 0.56%   |
| Hitachi HTS545050B9A300 500GB                       | 3         | 0.56%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.56%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.56%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 0.56%   |
| Crucial CT120BX500SSD1 120GB                        | 3         | 0.56%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 2         | 0.38%   |
| WDC WD6003FZBX-00K5WB0 6TB                          | 2         | 0.38%   |
| WDC WD5002AALX-00J37A0 500GB                        | 2         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.38%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 109    | 37.85%  |
| WDC                 | 61        | 93     | 28.5%   |
| Toshiba             | 25        | 30     | 11.68%  |
| Samsung Electronics | 16        | 24     | 7.48%   |
| Hitachi             | 16        | 21     | 7.48%   |
| HGST                | 11        | 20     | 5.14%   |
| USB                 | 1         | 1      | 0.47%   |
| Maxtor              | 1         | 1      | 0.47%   |
| IBM/Hitachi         | 1         | 1      | 0.47%   |
| Fujitsu             | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 41        | 64     | 24.7%   |
| Samsung Electronics | 38        | 58     | 22.89%  |
| Crucial             | 17        | 26     | 10.24%  |
| A-DATA Technology   | 9         | 11     | 5.42%   |
| WDC                 | 7         | 8      | 4.22%   |
| SPCC                | 5         | 7      | 3.01%   |
| Patriot             | 5         | 11     | 3.01%   |
| Intel               | 4         | 9      | 2.41%   |
| SanDisk             | 3         | 6      | 1.81%   |
| OCZ                 | 3         | 4      | 1.81%   |
| Micron Technology   | 3         | 3      | 1.81%   |
| Intenso             | 3         | 3      | 1.81%   |
| GOODRAM             | 3         | 8      | 1.81%   |
| Transcend           | 2         | 2      | 1.2%    |
| LITEON              | 2         | 2      | 1.2%    |
| Integral            | 2         | 2      | 1.2%    |
| China               | 2         | 2      | 1.2%    |
| Verbatim            | 1         | 1      | 0.6%    |
| Toshiba             | 1         | 1      | 0.6%    |
| PNY                 | 1         | 1      | 0.6%    |
| Plextor             | 1         | 1      | 0.6%    |
| Platinet            | 1         | 1      | 0.6%    |
| Mushkin             | 1         | 2      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| LITEON C            | 1         | 1      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.6%    |
| KingSpec            | 1         | 1      | 0.6%    |
| KingFast            | 1         | 2      | 0.6%    |
| JMicron Technology  | 1         | 2      | 0.6%    |
| GLOWAY              | 1         | 2      | 0.6%    |
| CHN25SATAS1         | 1         | 1      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |
| Unknown             | 1         | 3      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 180       | 301    | 41.19%  |
| SSD     | 144       | 249    | 32.95%  |
| NVMe    | 100       | 138    | 22.88%  |
| MMC     | 9         | 13     | 2.06%   |
| Unknown | 4         | 20     | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 266       | 548    | 68.56%  |
| NVMe | 100       | 137    | 25.77%  |
| SAS  | 13        | 23     | 3.35%   |
| MMC  | 9         | 13     | 2.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 211       | 365    | 63.94%  |
| 0.51-1.0   | 92        | 143    | 27.88%  |
| 1.01-2.0   | 19        | 32     | 5.76%   |
| 2.01-3.0   | 3         | 5      | 0.91%   |
| 4.01-10.0  | 3         | 3      | 0.91%   |
| 3.01-4.0   | 2         | 2      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 114       | 30.32%  |
| 251-500        | 78        | 20.74%  |
| 501-1000       | 45        | 11.97%  |
| 1001-2000      | 34        | 9.04%   |
| 51-100         | 32        | 8.51%   |
| 1-20           | 30        | 7.98%   |
| 21-50          | 13        | 3.46%   |
| More than 3000 | 11        | 2.93%   |
| 2001-3000      | 11        | 2.93%   |
| Unknown        | 8         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 159       | 40.87%  |
| 21-50          | 56        | 14.4%   |
| 101-250        | 48        | 12.34%  |
| 51-100         | 43        | 11.05%  |
| 251-500        | 32        | 8.23%   |
| 501-1000       | 25        | 6.43%   |
| 1001-2000      | 13        | 3.34%   |
| Unknown        | 8         | 2.06%   |
| 2001-3000      | 4         | 1.03%   |
| More than 3000 | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 4.69%   |
| WDC WD20EARX-00PASB0 2TB              | 2         | 4      | 3.13%   |
| WDC WD2000JD-00HBB0 200GB             | 2         | 4      | 3.13%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 7      | 3.13%   |
| Samsung Electronics SP2504C 250GB     | 2         | 2      | 3.13%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 7      | 3.13%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 2      | 3.13%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 3.13%   |
| A-DATA Technology SU800NS38 512GB SSD | 2         | 3      | 3.13%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1         | 1      | 1.56%   |
| WDC WD800JD-60MSA1 80GB               | 1         | 1      | 1.56%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 1.56%   |
| WDC WD5001AALS-00L3B2 500GB           | 1         | 1      | 1.56%   |
| WDC WD5001AALS-00E3A0 500GB           | 1         | 1      | 1.56%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 1.56%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 1.56%   |
| WDC WD3200BEVT-75ZCT0 320GB           | 1         | 4      | 1.56%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1         | 1      | 1.56%   |
| WDC WD1600BEVS-60RST0 160GB           | 1         | 1      | 1.56%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 1.56%   |
| WDC WD Green 2.5 1000GB               | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.56%   |
| Toshiba MK8034GSX 80GB                | 1         | 1      | 1.56%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.56%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.56%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.56%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.56%   |
| Seagate ST9500325AS 500GB             | 1         | 3      | 1.56%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.56%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.56%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.56%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 1.56%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.56%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 1.56%   |
| Seagate ST340016A 40GB                | 1         | 1      | 1.56%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.56%   |
| Seagate ST3250312AS 250GB             | 1         | 1      | 1.56%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.56%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.56%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 28     | 32.79%  |
| WDC                 | 14        | 23     | 22.95%  |
| Samsung Electronics | 7         | 12     | 11.48%  |
| HGST                | 6         | 9      | 9.84%   |
| Toshiba             | 5         | 5      | 8.2%    |
| Kingston            | 3         | 3      | 4.92%   |
| Hitachi             | 3         | 3      | 4.92%   |
| A-DATA Technology   | 2         | 3      | 3.28%   |
| CHN25SATAS1         | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 28     | 37.74%  |
| WDC                 | 13        | 21     | 24.53%  |
| Samsung Electronics | 6         | 11     | 11.32%  |
| HGST                | 6         | 9      | 11.32%  |
| Toshiba             | 5         | 5      | 9.43%   |
| Hitachi             | 3         | 3      | 5.66%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 77     | 83.02%  |
| SSD  | 7         | 8      | 13.21%  |
| NVMe | 2         | 2      | 3.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 166       | 335    | 44.15%  |
| Works    | 157       | 297    | 41.76%  |
| Malfunc  | 51        | 87     | 13.56%  |
| Failed   | 2         | 2      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 243       | 57.04%  |
| AMD                              | 59        | 13.85%  |
| Samsung Electronics              | 35        | 8.22%   |
| SanDisk                          | 12        | 2.82%   |
| Kingston Technology Company      | 9         | 2.11%   |
| SK hynix                         | 8         | 1.88%   |
| Nvidia                           | 7         | 1.64%   |
| Micron Technology                | 7         | 1.64%   |
| JMicron Technology               | 7         | 1.64%   |
| Phison Electronics               | 5         | 1.17%   |
| Marvell Technology Group         | 5         | 1.17%   |
| KIOXIA                           | 5         | 1.17%   |
| ADATA Technology                 | 4         | 0.94%   |
| Toshiba America Info Systems     | 3         | 0.7%    |
| Silicon Motion                   | 3         | 0.7%    |
| ASMedia Technology               | 3         | 0.7%    |
| Union Memory (Shenzhen)          | 2         | 0.47%   |
| Shenzhen Longsys Electronics     | 2         | 0.47%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.47%   |
| Transcend                        | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Silicon Image                    | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| Lite-On Technology               | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 42        | 8.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 4.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 2.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 1.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 10        | 1.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.2%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1%      |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 5         | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1%      |
| JMicron JMB368 IDE controller                                                  | 5         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1%      |
| AMD FCH IDE Controller                                                         | 5         | 1%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.8%    |
| Nvidia MCP61 SATA Controller                                                   | 4         | 0.8%    |
| Nvidia MCP61 IDE                                                               | 4         | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 0.8%    |
| Intel SSD 660P Series                                                          | 4         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 251       | 57.18%  |
| NVMe | 103       | 23.46%  |
| IDE  | 64        | 14.58%  |
| RAID | 21        | 4.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 261       | 76.54%  |
| AMD    | 77        | 22.58%  |
| ARM    | 3         | 0.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.47%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.47%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.17%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.88%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 0.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.88%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.88%   |
| ARM Processor                                 | 3         | 0.88%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.59%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.59%   |
| Intel Pentium D CPU 3.40GHz                   | 2         | 0.59%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.59%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.59%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 73        | 21.41%  |
| Intel Core i7           | 49        | 14.37%  |
| Intel Core i3           | 31        | 9.09%   |
| Other                   | 27        | 7.92%   |
| Intel Core 2 Duo        | 25        | 7.33%   |
| AMD Ryzen 5             | 19        | 5.57%   |
| Intel Celeron           | 17        | 4.99%   |
| AMD Ryzen 7             | 11        | 3.23%   |
| Intel Pentium           | 9         | 2.64%   |
| AMD A8                  | 7         | 2.05%   |
| Intel Pentium Dual-Core | 6         | 1.76%   |
| Intel Pentium Dual      | 6         | 1.76%   |
| Intel Pentium D         | 5         | 1.47%   |
| Intel Core 2 Quad       | 5         | 1.47%   |
| Intel Core 2            | 5         | 1.47%   |
| AMD Ryzen 9             | 4         | 1.17%   |
| AMD Ryzen 7 PRO         | 4         | 1.17%   |
| AMD FX                  | 4         | 1.17%   |
| Intel Xeon              | 3         | 0.88%   |
| Intel Genuine           | 3         | 0.88%   |
| AMD Athlon 64 X2        | 3         | 0.88%   |
| AMD A10                 | 3         | 0.88%   |
| AMD Turion 64 X2 Mobile | 2         | 0.59%   |
| AMD Ryzen Threadripper  | 2         | 0.59%   |
| AMD Ryzen 5 PRO         | 2         | 0.59%   |
| AMD Ryzen 3             | 2         | 0.59%   |
| AMD E1                  | 2         | 0.59%   |
| AMD Athlon II X2        | 2         | 0.59%   |
| Intel Pentium Gold      | 1         | 0.29%   |
| Intel Pentium 4         | 1         | 0.29%   |
| Intel Atom              | 1         | 0.29%   |
| AMD Sempron             | 1         | 0.29%   |
| AMD E2                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD C-70                | 1         | 0.29%   |
| AMD Athlon II X4        | 1         | 0.29%   |
| AMD Athlon II X3        | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 169       | 49.27%  |
| 4       | 102       | 29.74%  |
| 6       | 26        | 7.58%   |
| 8       | 18        | 5.25%   |
| 1       | 7         | 2.04%   |
| 3       | 5         | 1.46%   |
| 12      | 4         | 1.17%   |
| 16      | 3         | 0.87%   |
| 10      | 3         | 0.87%   |
| 24      | 2         | 0.58%   |
| 14      | 2         | 0.58%   |
| Unknown | 2         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 338       | 99.12%  |
| 2       | 2         | 0.59%   |
| Unknown | 1         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 211       | 61.52%  |
| 1       | 130       | 37.9%   |
| Unknown | 2         | 0.58%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 337       | 98.83%  |
| Unknown        | 3         | 0.88%   |
| 32-bit         | 1         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 23.65%  |
| 0x306c3    | 17        | 4.84%   |
| 0x306a9    | 17        | 4.84%   |
| 0x1067a    | 17        | 4.84%   |
| 0x206a7    | 15        | 4.27%   |
| 0x6fd      | 12        | 3.42%   |
| 0x906ea    | 11        | 3.13%   |
| 0x406e3    | 11        | 3.13%   |
| 0x30678    | 9         | 2.56%   |
| 0x20655    | 8         | 2.28%   |
| 0x10676    | 7         | 1.99%   |
| 0x06001119 | 7         | 1.99%   |
| 0x806ec    | 6         | 1.71%   |
| 0x806c1    | 6         | 1.71%   |
| 0x506e3    | 6         | 1.71%   |
| 0x306d4    | 6         | 1.71%   |
| 0x40651    | 5         | 1.42%   |
| 0x08701021 | 5         | 1.42%   |
| 0x906e9    | 4         | 1.14%   |
| 0x806ea    | 4         | 1.14%   |
| 0x806e9    | 4         | 1.14%   |
| 0x6fb      | 4         | 1.14%   |
| 0x08108102 | 4         | 1.14%   |
| 0xa0652    | 3         | 0.85%   |
| 0x6f6      | 3         | 0.85%   |
| 0x20652    | 3         | 0.85%   |
| 0x0a50000d | 3         | 0.85%   |
| 0x06000852 | 3         | 0.85%   |
| 0x05000119 | 3         | 0.85%   |
| 0xf65      | 2         | 0.57%   |
| 0xf47      | 2         | 0.57%   |
| 0x906ed    | 2         | 0.57%   |
| 0x906a3    | 2         | 0.57%   |
| 0x706a1    | 2         | 0.57%   |
| 0x6fa      | 2         | 0.57%   |
| 0x6f2      | 2         | 0.57%   |
| 0x406c3    | 2         | 0.57%   |
| 0x106e5    | 2         | 0.57%   |
| 0x0a50000c | 2         | 0.57%   |
| 0x0a404102 | 2         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 12.32%  |
| Haswell          | 28        | 8.21%   |
| Core             | 26        | 7.62%   |
| Penryn           | 25        | 7.33%   |
| IvyBridge        | 22        | 6.45%   |
| SandyBridge      | 21        | 6.16%   |
| Skylake          | 20        | 5.87%   |
| Zen 2            | 17        | 4.99%   |
| Westmere         | 14        | 4.11%   |
| Silvermont       | 13        | 3.81%   |
| Zen 3            | 11        | 3.23%   |
| TigerLake        | 11        | 3.23%   |
| Piledriver       | 10        | 2.93%   |
| Unknown          | 10        | 2.93%   |
| Zen+             | 9         | 2.64%   |
| Broadwell        | 7         | 2.05%   |
| Alderlake Hybrid | 7         | 2.05%   |
| NetBurst         | 6         | 1.76%   |
| K8 Hammer        | 6         | 1.76%   |
| Zen              | 4         | 1.17%   |
| Nehalem          | 4         | 1.17%   |
| CometLake        | 4         | 1.17%   |
| K10              | 3         | 0.88%   |
| IceLake          | 3         | 0.88%   |
| Goldmont plus    | 3         | 0.88%   |
| Bobcat           | 3         | 0.88%   |
| Steamroller      | 2         | 0.59%   |
| Puma             | 2         | 0.59%   |
| Jaguar           | 2         | 0.59%   |
| Excavator        | 2         | 0.59%   |
| P6               | 1         | 0.29%   |
| K10 Llano        | 1         | 0.29%   |
| Goldmont         | 1         | 0.29%   |
| Bulldozer        | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 195       | 48.63%  |
| Nvidia | 117       | 29.18%  |
| AMD    | 89        | 22.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 14        | 3.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 13        | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 11        | 2.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 10        | 2.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 10        | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 2.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 8         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 1.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 5         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5         | 1.2%    |
| Intel HD Graphics 620                                                         | 5         | 1.2%    |
| Intel HD Graphics 5500                                                        | 5         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 0.96%   |
| Intel UHD Graphics 620                                                        | 4         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 4         | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 4         | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 3         | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 0.72%   |
| Intel HD Graphics 530                                                         | 3         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3         | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 3         | 0.72%   |
| AMD Turks XT [Radeon HD 6670/7670]                                            | 3         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.48%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 2         | 0.48%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 0.48%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 2         | 0.48%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 40.23%  |
| 1 x AMD        | 68        | 19.83%  |
| 1 x Nvidia     | 66        | 19.24%  |
| Intel + Nvidia | 46        | 13.41%  |
| 2 x AMD        | 8         | 2.33%   |
| Intel + AMD    | 8         | 2.33%   |
| AMD + Nvidia   | 4         | 1.17%   |
| Other          | 3         | 0.87%   |
| 2 x Nvidia     | 1         | 0.29%   |
| 2 x Intel      | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 269       | 76.64%  |
| Proprietary | 66        | 18.8%   |
| Unknown     | 16        | 4.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 48.58%  |
| 1.01-2.0   | 51        | 14.49%  |
| 0.01-0.5   | 51        | 14.49%  |
| 0.51-1.0   | 30        | 8.52%   |
| 3.01-4.0   | 22        | 6.25%   |
| 7.01-8.0   | 12        | 3.41%   |
| 5.01-6.0   | 10        | 2.84%   |
| 8.01-16.0  | 3         | 0.85%   |
| 2.01-3.0   | 1         | 0.28%   |
| 16.01-24.0 | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 58        | 15.89%  |
| Samsung Electronics     | 56        | 15.34%  |
| LG Display              | 38        | 10.41%  |
| BOE                     | 28        | 7.67%   |
| Dell                    | 25        | 6.85%   |
| Chimei Innolux          | 25        | 6.85%   |
| Goldstar                | 24        | 6.58%   |
| BenQ                    | 15        | 4.11%   |
| Philips                 | 11        | 3.01%   |
| Lenovo                  | 9         | 2.47%   |
| Hewlett-Packard         | 8         | 2.19%   |
| AOC                     | 8         | 2.19%   |
| Chi Mei Optoelectronics | 7         | 1.92%   |
| Ancor Communications    | 7         | 1.92%   |
| PANDA                   | 5         | 1.37%   |
| Unknown                 | 3         | 0.82%   |
| LG Electronics          | 3         | 0.82%   |
| Apple                   | 3         | 0.82%   |
| ViewSonic               | 2         | 0.55%   |
| Sony                    | 2         | 0.55%   |
| Seiko/Epson             | 2         | 0.55%   |
| NEC Computers           | 2         | 0.55%   |
| LG Philips              | 2         | 0.55%   |
| InfoVision              | 2         | 0.55%   |
| Hitachi                 | 2         | 0.55%   |
| Arnos Instruments       | 2         | 0.55%   |
| Acer                    | 2         | 0.55%   |
| Xiaomi                  | 1         | 0.27%   |
| Wacom                   | 1         | 0.27%   |
| Tianma XM               | 1         | 0.27%   |
| Sharp                   | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| Plain Tree Systems      | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| IBM                     | 1         | 0.27%   |
| HYO                     | 1         | 0.27%   |
| FUS                     | 1         | 0.27%   |
| AUS                     | 1         | 0.27%   |
| ASUSTek Computer        | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.79%   |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                     | 3         | 0.79%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.79%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch        | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.53%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 2         | 0.53%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.53%   |
| LG Electronics LCD Monitor LG TV 1920x1080                               | 2         | 0.53%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                     | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.53%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.53%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.53%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.53%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.53%   |
| Dell LCD Monitor U2414H                                                  | 2         | 0.53%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.53%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                       | 2         | 0.53%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                        | 2         | 0.53%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch    | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 129       | 37.28%  |
| 1366x768 (WXGA)    | 70        | 20.23%  |
| 3840x2160 (4K)     | 19        | 5.49%   |
| 1600x900 (HD+)     | 19        | 5.49%   |
| 1280x1024 (SXGA)   | 17        | 4.91%   |
| 2560x1440 (QHD)    | 16        | 4.62%   |
| 1280x800 (WXGA)    | 14        | 4.05%   |
| 1440x900 (WXGA+)   | 12        | 3.47%   |
| 1680x1050 (WSXGA+) | 10        | 2.89%   |
| 1920x1200 (WUXGA)  | 8         | 2.31%   |
| 2560x1080          | 5         | 1.45%   |
| Unknown            | 5         | 1.45%   |
| 3440x1440          | 3         | 0.87%   |
| 1360x768           | 3         | 0.87%   |
| 4480x1440          | 2         | 0.58%   |
| 1024x768 (XGA)     | 2         | 0.58%   |
| 7680x2160          | 1         | 0.29%   |
| 3840x1080          | 1         | 0.29%   |
| 3520x1200          | 1         | 0.29%   |
| 3456x2160          | 1         | 0.29%   |
| 3000x2000          | 1         | 0.29%   |
| 2960x1050          | 1         | 0.29%   |
| 2880x1800          | 1         | 0.29%   |
| 2560x1600          | 1         | 0.29%   |
| 2288x1287          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 1280x960           | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 117       | 32.23%  |
| 17      | 29        | 7.99%   |
| 24      | 28        | 7.71%   |
| 14      | 26        | 7.16%   |
| 13      | 25        | 6.89%   |
| Unknown | 21        | 5.79%   |
| 27      | 19        | 5.23%   |
| 23      | 15        | 4.13%   |
| 19      | 13        | 3.58%   |
| 12      | 11        | 3.03%   |
| 21      | 9         | 2.48%   |
| 34      | 6         | 1.65%   |
| 22      | 6         | 1.65%   |
| 20      | 6         | 1.65%   |
| 40      | 5         | 1.38%   |
| 25      | 5         | 1.38%   |
| 18      | 5         | 1.38%   |
| 16      | 3         | 0.83%   |
| 11      | 3         | 0.83%   |
| 65      | 2         | 0.55%   |
| 35      | 2         | 0.55%   |
| 31      | 2         | 0.55%   |
| 142     | 1         | 0.28%   |
| 84      | 1         | 0.28%   |
| 43      | 1         | 0.28%   |
| 33      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 162       | 45.38%  |
| 501-600        | 62        | 17.37%  |
| 351-400        | 34        | 9.52%   |
| 401-500        | 29        | 8.12%   |
| 201-300        | 26        | 7.28%   |
| Unknown        | 21        | 5.88%   |
| 801-900        | 7         | 1.96%   |
| 701-800        | 7         | 1.96%   |
| 601-700        | 4         | 1.12%   |
| 1001-1500      | 2         | 0.56%   |
| More than 2000 | 1         | 0.28%   |
| 1501-2000      | 1         | 0.28%   |
| 901-1000       | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 231       | 70%     |
| 16/10   | 48        | 14.55%  |
| Unknown | 19        | 5.76%   |
| 5/4     | 18        | 5.45%   |
| 21/9    | 8         | 2.42%   |
| 3/2     | 3         | 0.91%   |
| 4/3     | 2         | 0.61%   |
| 1.00    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 115       | 31.94%  |
| 201-250        | 50        | 13.89%  |
| 81-90          | 42        | 11.67%  |
| 151-200        | 24        | 6.67%   |
| Unknown        | 21        | 5.83%   |
| 121-130        | 20        | 5.56%   |
| 301-350        | 19        | 5.28%   |
| 61-70          | 11        | 3.06%   |
| 351-500        | 11        | 3.06%   |
| 251-300        | 11        | 3.06%   |
| 141-150        | 10        | 2.78%   |
| 71-80          | 8         | 2.22%   |
| 501-1000       | 6         | 1.67%   |
| More than 1000 | 3         | 0.83%   |
| 51-60          | 3         | 0.83%   |
| 91-100         | 3         | 0.83%   |
| 131-140        | 2         | 0.56%   |
| 111-120        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 116       | 32.77%  |
| 121-160       | 101       | 28.53%  |
| 101-120       | 92        | 25.99%  |
| Unknown       | 21        | 5.93%   |
| 161-240       | 17        | 4.8%    |
| 1-50          | 4         | 1.13%   |
| More than 240 | 3         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 288       | 82.76%  |
| 2     | 43        | 12.36%  |
| 0     | 11        | 3.16%   |
| 3     | 6         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 180       | 34.75%  |
| Intel                             | 159       | 30.69%  |
| Qualcomm Atheros                  | 61        | 11.78%  |
| Broadcom                          | 31        | 5.98%   |
| Broadcom Limited                  | 11        | 2.12%   |
| TP-Link                           | 9         | 1.74%   |
| Ralink                            | 9         | 1.74%   |
| Marvell Technology Group          | 9         | 1.74%   |
| Ralink Technology                 | 6         | 1.16%   |
| Nvidia                            | 6         | 1.16%   |
| Samsung Electronics               | 5         | 0.97%   |
| MediaTek                          | 5         | 0.97%   |
| Xiaomi                            | 4         | 0.77%   |
| vivo                              | 3         | 0.58%   |
| Lenovo                            | 3         | 0.58%   |
| U-Blox                            | 2         | 0.39%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| Hewlett-Packard                   | 2         | 0.39%   |
| ASIX Electronics                  | 2         | 0.39%   |
| Wilocity                          | 1         | 0.19%   |
| Sundance Technology Inc / IC Plus | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| Google                            | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Aquantia                          | 1         | 0.19%   |
| 3Com                              | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 126       | 20.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 4.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.96%   |
| Intel Wireless 8260                                               | 11        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.31%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.31%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.15%   |
| Intel Wireless 3160                                               | 7         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.82%   |
| Intel Wireless 7260                                               | 5         | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.65%   |
| Intel Wireless-AC 9260                                            | 4         | 0.65%   |
| Intel Wireless 7265                                               | 4         | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.65%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.49%   |
| vivo 1820                                                         | 3         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 49.07%  |
| Qualcomm Atheros                | 48        | 17.84%  |
| Realtek Semiconductor           | 33        | 12.27%  |
| Broadcom                        | 18        | 6.69%   |
| TP-Link                         | 9         | 3.35%   |
| Ralink                          | 9         | 3.35%   |
| Ralink Technology               | 6         | 2.23%   |
| Broadcom Limited                | 6         | 2.23%   |
| MediaTek                        | 3         | 1.12%   |
| Qualcomm Atheros Communications | 2         | 0.74%   |
| Wilocity                        | 1         | 0.37%   |
| Qualcomm                        | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 11        | 4.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 3.69%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.95%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.95%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.58%   |
| Intel Wireless 3160                                                     | 7         | 2.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.85%   |
| Intel Wireless 7260                                                     | 5         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 1.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.48%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.48%   |
| Intel Wireless 7265                                                     | 4         | 1.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.48%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.11%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.74%   |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.74%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 171       | 52.13%  |
| Intel                             | 75        | 22.87%  |
| Qualcomm Atheros                  | 20        | 6.1%    |
| Broadcom                          | 18        | 5.49%   |
| Marvell Technology Group          | 9         | 2.74%   |
| Nvidia                            | 6         | 1.83%   |
| Broadcom Limited                  | 5         | 1.52%   |
| Xiaomi                            | 4         | 1.22%   |
| vivo                              | 3         | 0.91%   |
| Samsung Electronics               | 3         | 0.91%   |
| Lenovo                            | 3         | 0.91%   |
| MediaTek                          | 2         | 0.61%   |
| ASIX Electronics                  | 2         | 0.61%   |
| Sundance Technology Inc / IC Plus | 1         | 0.3%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.3%    |
| Huawei Technologies               | 1         | 0.3%    |
| Hewlett-Packard                   | 1         | 0.3%    |
| Google                            | 1         | 0.3%    |
| Aquantia                          | 1         | 0.3%    |
| 3Com                              | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 126       | 37.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 8.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.9%    |
| vivo 1820                                                         | 3         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 3         | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 3         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 3         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 3         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.9%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.6%    |
| Lenovo ThinkPad Lan                                               | 2         | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.6%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2         | 0.6%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.6%    |
| ASIX AX88772B                                                     | 2         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 310       | 53.82%  |
| WiFi     | 261       | 45.31%  |
| Modem    | 5         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 214       | 60.97%  |
| Ethernet | 137       | 39.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 213       | 62.46%  |
| 1     | 115       | 33.72%  |
| 0     | 7         | 2.05%   |
| 3     | 6         | 1.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 325       | 95.03%  |
| Yes  | 17        | 4.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 45.45%  |
| Realtek Semiconductor           | 19        | 9.6%    |
| Lite-On Technology              | 13        | 6.57%   |
| IMC Networks                    | 13        | 6.57%   |
| Qualcomm Atheros Communications | 12        | 6.06%   |
| Broadcom                        | 11        | 5.56%   |
| Cambridge Silicon Radio         | 9         | 4.55%   |
| Dell                            | 5         | 2.53%   |
| Apple                           | 5         | 2.53%   |
| Hewlett-Packard                 | 4         | 2.02%   |
| Toshiba                         | 3         | 1.52%   |
| ASUSTek Computer                | 3         | 1.52%   |
| Ralink                          | 2         | 1.01%   |
| Foxconn / Hon Hai               | 2         | 1.01%   |
| USI                             | 1         | 0.51%   |
| Taiyo Yuden                     | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |
| Qcom                            | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |
| Fujitsu                         | 1         | 0.51%   |
| Edimax Technology               | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 16.67%  |
| Intel Bluetooth Device                              | 20        | 10.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 7.07%   |
| Realtek Bluetooth Radio                             | 11        | 5.56%   |
| Intel AX200 Bluetooth                               | 10        | 5.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.53%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 2.02%   |
| Intel AX210 Bluetooth                               | 4         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.52%   |
| Lite-On Bluetooth Device                            | 3         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.52%   |
| IMC Networks Bluetooth Device                       | 3         | 1.52%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.01%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.01%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.01%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.01%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.01%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.01%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.01%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.01%   |
| Apple Bluetooth Host Controller                     | 2         | 1.01%   |
| USI Bluetooth Device                                | 1         | 0.51%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.51%   |
| Toshiba Bluetooth Device                            | 1         | 0.51%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.51%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.51%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 255       | 54.84%  |
| AMD                              | 89        | 19.14%  |
| Nvidia                           | 77        | 16.56%  |
| C-Media Electronics              | 10        | 2.15%   |
| Logitech                         | 4         | 0.86%   |
| Creative Technology              | 4         | 0.86%   |
| Realtek Semiconductor            | 3         | 0.65%   |
| Yamaha                           | 2         | 0.43%   |
| Focusrite-Novation               | 2         | 0.43%   |
| Creative Labs                    | 2         | 0.43%   |
| Texas Instruments                | 1         | 0.22%   |
| Syntek                           | 1         | 0.22%   |
| SteelSeries ApS                  | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| RODE Microphones                 | 1         | 0.22%   |
| Razer USA                        | 1         | 0.22%   |
| Microsoft                        | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| Kingston Technology              | 1         | 0.22%   |
| JMTek                            | 1         | 0.22%   |
| GYROCOM C&C                      | 1         | 0.22%   |
| GN Netcom                        | 1         | 0.22%   |
| FIFINE 683 Microphone            | 1         | 0.22%   |
| AudioQuest                       | 1         | 0.22%   |
| ASUSTek Computer                 | 1         | 0.22%   |
| ASRock                           | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                            | 24        | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 22        | 4.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 3.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 2.94%   |
| AMD FCH Azalia Controller                                                  | 15        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 2.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.29%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.1%    |
| AMD Trinity HDMI Audio Controller                                          | 6         | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.92%   |
| Nvidia MCP61 High Definition Audio                                         | 4         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 47        | 18.8%   |
| Unknown                                 | 44        | 17.6%   |
| SK hynix                                | 44        | 17.6%   |
| Kingston                                | 40        | 16%     |
| Micron Technology                       | 18        | 7.2%    |
| Crucial                                 | 17        | 6.8%    |
| Corsair                                 | 10        | 4%      |
| G.Skill                                 | 9         | 3.6%    |
| GOODRAM                                 | 3         | 1.2%    |
| Elpida                                  | 3         | 1.2%    |
| A-DATA Technology                       | 3         | 1.2%    |
| Ramaxel Technology                      | 2         | 0.8%    |
| Toshiba                                 | 1         | 0.4%    |
| Team                                    | 1         | 0.4%    |
| Silicon Power Computer & Communications | 1         | 0.4%    |
| Silicon Power                           | 1         | 0.4%    |
| Ramos Technology                        | 1         | 0.4%    |
| PNY                                     | 1         | 0.4%    |
| Patriot                                 | 1         | 0.4%    |
| Nanya Technology                        | 1         | 0.4%    |
| ASint Technology                        | 1         | 0.4%    |
| Unknown                                 | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 5         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s | 4         | 1.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 3         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 3         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 3         | 1.09%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 3         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.09%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s  | 3         | 1.09%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 2         | 0.73%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                     | 2         | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 2         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 2         | 0.73%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2         | 0.73%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 2         | 0.73%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 2         | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.73%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.73%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s  | 2         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.73%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s  | 2         | 0.73%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.73%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.73%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 0.73%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s     | 2         | 0.73%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s    | 2         | 0.73%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s       | 2         | 0.73%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s      | 2         | 0.73%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s      | 2         | 0.73%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s   | 2         | 0.73%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s               | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s             | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 77        | 37.75%  |
| DDR4    | 76        | 37.25%  |
| DDR2    | 20        | 9.8%    |
| Unknown | 11        | 5.39%   |
| SDRAM   | 7         | 3.43%   |
| LPDDR5  | 3         | 1.47%   |
| LPDDR4  | 3         | 1.47%   |
| DDR     | 3         | 1.47%   |
| DDR5    | 2         | 0.98%   |
| LPDDR3  | 1         | 0.49%   |
| DRAM    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 67.82%  |
| DIMM         | 58        | 28.71%  |
| Row Of Chips | 6         | 2.97%   |
| Chip         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 72        | 30.9%   |
| 8192  | 66        | 28.33%  |
| 2048  | 47        | 20.17%  |
| 16384 | 26        | 11.16%  |
| 1024  | 13        | 5.58%   |
| 32768 | 7         | 3%      |
| 512   | 2         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 47        | 20%     |
| 2667    | 29        | 12.34%  |
| 3200    | 24        | 10.21%  |
| 1333    | 20        | 8.51%   |
| 667     | 20        | 8.51%   |
| 2133    | 14        | 5.96%   |
| 2400    | 11        | 4.68%   |
| 1334    | 11        | 4.68%   |
| 800     | 6         | 2.55%   |
| Unknown | 6         | 2.55%   |
| 1066    | 5         | 2.13%   |
| 533     | 4         | 1.7%    |
| 6400    | 3         | 1.28%   |
| 3600    | 3         | 1.28%   |
| 1867    | 3         | 1.28%   |
| 4267    | 2         | 0.85%   |
| 3466    | 2         | 0.85%   |
| 3266    | 2         | 0.85%   |
| 3000    | 2         | 0.85%   |
| 1800    | 2         | 0.85%   |
| 1639    | 2         | 0.85%   |
| 1067    | 2         | 0.85%   |
| 8400    | 1         | 0.43%   |
| 5600    | 1         | 0.43%   |
| 5200    | 1         | 0.43%   |
| 4199    | 1         | 0.43%   |
| 3866    | 1         | 0.43%   |
| 3800    | 1         | 0.43%   |
| 3533    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 2666    | 1         | 0.43%   |
| 2134    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 1866    | 1         | 0.43%   |
| 1632    | 1         | 0.43%   |
| 975     | 1         | 0.43%   |
| 200     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 46.15%  |
| Samsung Electronics | 4         | 30.77%  |
| Seiko Epson         | 1         | 7.69%   |
| Canon               | 1         | 7.69%   |
| Brother Industries  | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP LaserJet 1018          | 2         | 15.38%  |
| Seiko Epson L3110 Series  | 1         | 7.69%   |
| Samsung SCX-4216F Scanner | 1         | 7.69%   |
| Samsung SCX-4100 Scanner  | 1         | 7.69%   |
| Samsung SCX-3200 Series   | 1         | 7.69%   |
| Samsung Composite Device  | 1         | 7.69%   |
| HP Officejet 4500 G510g-m | 1         | 7.69%   |
| HP LaserJet P1102         | 1         | 7.69%   |
| HP LaserJet 1010          | 1         | 7.69%   |
| HP DeskJet 5940           | 1         | 7.69%   |
| Canon PIXMA MG3000 series | 1         | 7.69%   |
| Brother DCP-L2510D series | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 2         | 50%     |
| Seiko Epson    | 1         | 25%     |
| Canon          | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB                | 2         | 50%     |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 55        | 25.23%  |
| IMC Networks                           | 22        | 10.09%  |
| Realtek Semiconductor                  | 18        | 8.26%   |
| Microdia                               | 16        | 7.34%   |
| Logitech                               | 11        | 5.05%   |
| Bison Electronics                      | 11        | 5.05%   |
| Suyin                                  | 9         | 4.13%   |
| Sunplus Innovation Technology          | 8         | 3.67%   |
| Quanta                                 | 8         | 3.67%   |
| Lite-On Technology                     | 8         | 3.67%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.75%   |
| Syntek                                 | 5         | 2.29%   |
| Apple                                  | 5         | 2.29%   |
| Z-Star Microelectronics                | 4         | 1.83%   |
| Silicon Motion                         | 3         | 1.38%   |
| Acer                                   | 3         | 1.38%   |
| Samsung Electronics                    | 2         | 0.92%   |
| Ricoh                                  | 2         | 0.92%   |
| Luxvisions Innotech Limited            | 2         | 0.92%   |
| Genesys Logic                          | 2         | 0.92%   |
| Tobii Technology AB                    | 1         | 0.46%   |
| Sonix Technology                       | 1         | 0.46%   |
| Shinetech                              | 1         | 0.46%   |
| Razer USA                              | 1         | 0.46%   |
| Primax Electronics                     | 1         | 0.46%   |
| Pixart Imaging                         | 1         | 0.46%   |
| OmniVision Technologies                | 1         | 0.46%   |
| Microsoft                              | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| KYE Systems (Mouse Systems)            | 1         | 0.46%   |
| GEMBIRD                                | 1         | 0.46%   |
| DigiTech                               | 1         | 0.46%   |
| Cubeternet                             | 1         | 0.46%   |
| Arkmicro Technologies                  | 1         | 0.46%   |
| ALi                                    | 1         | 0.46%   |
| A4Tech                                 | 1         | 0.46%   |
| 8SSC21D67422V1SR28902JL                | 1         | 0.46%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 10        | 4.52%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 3.17%   |
| IMC Networks Integrated Camera           | 6         | 2.71%   |
| Realtek Integrated_Webcam_HD             | 5         | 2.26%   |
| Lite-On Integrated Camera                | 5         | 2.26%   |
| Chicony HD WebCam                        | 5         | 2.26%   |
| Realtek USB Camera                       | 4         | 1.81%   |
| Chicony USB2.0 HD UVC WebCam             | 4         | 1.81%   |
| Chicony HP HD Camera                     | 4         | 1.81%   |
| Chicony HD User Facing                   | 4         | 1.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 3         | 1.36%   |
| Sunplus ASUS USB2.0 Webcam               | 3         | 1.36%   |
| Realtek Integrated Webcam                | 3         | 1.36%   |
| Microdia Integrated_Webcam_HD            | 3         | 1.36%   |
| Microdia Integrated Webcam               | 3         | 1.36%   |
| Logitech Webcam C270                     | 3         | 1.36%   |
| Chicony USB2.0 VGA UVC WebCam            | 3         | 1.36%   |
| Chicony Integrated Camera (1280x720@30)  | 3         | 1.36%   |
| Apple iPhone 5/5C/5S/6/SE                | 3         | 1.36%   |
| Z-Star A4 TECH HD PC Camera              | 2         | 0.9%    |
| Suyin HD WebCam                          | 2         | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 0.9%    |
| Realtek HP Webcam                        | 2         | 0.9%    |
| Quanta HD Webcam                         | 2         | 0.9%    |
| Microdia USB 2.0 Camera                  | 2         | 0.9%    |
| Microdia Lenovo EasyCamera               | 2         | 0.9%    |
| Logitech Webcam C170                     | 2         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 0.9%    |
| IMC Networks USB2.0 UVC HD Webcam        | 2         | 0.9%    |
| Genesys Logic Camera                     | 2         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD          | 2         | 0.9%    |
| Chicony HP Truevision HD camera          | 2         | 0.9%    |
| Chicony HP HD Webcam                     | 2         | 0.9%    |
| Chicony CNF9055 Toshiba Webcam           | 2         | 0.9%    |
| Bison Lenovo EasyCamera                  | 2         | 0.9%    |
| Bison Integrated Camera                  | 2         | 0.9%    |
| Bison HD Webcam                          | 2         | 0.9%    |
| Z-Star Venus USB2.0 Camera               | 1         | 0.45%   |
| Z-Star Vega USB 2.0 Camera               | 1         | 0.45%   |
| Tobii AB EyeChip                         | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 38.78%  |
| Synaptics                  | 14        | 28.57%  |
| AuthenTec                  | 5         | 10.2%   |
| Upek                       | 3         | 6.12%   |
| Shenzhen Goodix Technology | 3         | 6.12%   |
| STMicroelectronics         | 2         | 4.08%   |
| Elan Microelectronics      | 2         | 4.08%   |
| LighTuning Technology      | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 10.2%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 8.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 8.16%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 6.12%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6.12%   |
| Validity Sensors VFS491                                                    | 2         | 4.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.08%   |
| Synaptics UWP WBDI Device                                                  | 2         | 4.08%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 4.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.04%   |
| Synaptics WBDI                                                             | 1         | 2.04%   |
| Synaptics UWP WBDI                                                         | 1         | 2.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.04%   |
| AuthenTec AES1600                                                          | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 18        | 60%     |
| Broadcom         | 7         | 23.33%  |
| Lenovo           | 2         | 6.67%   |
| Upek             | 1         | 3.33%   |
| SCM Microsystems | 1         | 3.33%   |
| O2 Micro         | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 18        | 60%     |
| Broadcom 58200                                             | 5         | 16.67%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 3.33%   |
| Broadcom 5880                                              | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 241       | 68.66%  |
| 1     | 79        | 22.51%  |
| 2     | 26        | 7.41%   |
| 3     | 4         | 1.14%   |
| 4     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 35.25%  |
| Graphics card            | 32        | 23.02%  |
| Chipcard                 | 24        | 17.27%  |
| Net/wireless             | 12        | 8.63%   |
| Multimedia controller    | 6         | 4.32%   |
| Camera                   | 5         | 3.6%    |
| Communication controller | 4         | 2.88%   |
| Storage                  | 2         | 1.44%   |
| Bluetooth                | 2         | 1.44%   |
| Storage/raid             | 1         | 0.72%   |
| Net/ethernet             | 1         | 0.72%   |
| Card reader              | 1         | 0.72%   |


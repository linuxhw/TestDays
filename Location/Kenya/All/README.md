Linux in Kenya - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Kenya/Desktop/README.md) and [notebooks](/Location/Kenya/Notebook/README.md).

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

Total: 413

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0XR1GT A00                  | Desktop     | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2430... | Notebook    | [658d6f150e](https://linux-hardware.org/?probe=658d6f150e) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [8df2c91111](https://linux-hardware.org/?probe=8df2c91111) | Oct 29, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [85caa55933](https://linux-hardware.org/?probe=85caa55933) | Oct 14, 2023 |
| HP            | 18E7                        | Desktop     | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9f4ab6a725](https://linux-hardware.org/?probe=9f4ab6a725) | Oct 11, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a6ac161796](https://linux-hardware.org/?probe=a6ac161796) | Sep 24, 2023 |
| Endless       | EF20EA                      | Notebook    | [492a9e4f5e](https://linux-hardware.org/?probe=492a9e4f5e) | Sep 23, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [fd6d63df98](https://linux-hardware.org/?probe=fd6d63df98) | Sep 15, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | Desktop     | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [c8ef60f2e0](https://linux-hardware.org/?probe=c8ef60f2e0) | Sep 12, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c8e3010177](https://linux-hardware.org/?probe=c8e3010177) | Sep 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [71dad1a9b9](https://linux-hardware.org/?probe=71dad1a9b9) | Sep 09, 2023 |
| Lenovo        | NOK                         | Desktop     | [30f2c89249](https://linux-hardware.org/?probe=30f2c89249) | Sep 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1d1c8e33ff](https://linux-hardware.org/?probe=1d1c8e33ff) | Sep 06, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [b3a358a06f](https://linux-hardware.org/?probe=b3a358a06f) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [40f2588fd0](https://linux-hardware.org/?probe=40f2588fd0) | Aug 31, 2023 |
| HP            | Notebook                    | Notebook    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| HP            | Notebook                    | Notebook    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [837cbb2cf1](https://linux-hardware.org/?probe=837cbb2cf1) | Aug 13, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | Notebook    | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c24d904ffb](https://linux-hardware.org/?probe=c24d904ffb) | Aug 06, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [695a7fad0f](https://linux-hardware.org/?probe=695a7fad0f) | Aug 03, 2023 |
| HP            | Notebook                    | Notebook    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [fef5d6f571](https://linux-hardware.org/?probe=fef5d6f571) | Jul 26, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [352cc6e31d](https://linux-hardware.org/?probe=352cc6e31d) | Jul 17, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [b815c86777](https://linux-hardware.org/?probe=b815c86777) | Jul 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | 3047h                       | Desktop     | [e60df0b6d1](https://linux-hardware.org/?probe=e60df0b6d1) | Jun 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [88e2f62c6d](https://linux-hardware.org/?probe=88e2f62c6d) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [04329cdc14](https://linux-hardware.org/?probe=04329cdc14) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6f4c06d514](https://linux-hardware.org/?probe=6f4c06d514) | Jun 14, 2023 |
| HP            | ProBook 4530s               | Notebook    | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Dell          | Latitude E5510              | Notebook    | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | Notebook    | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [08a1ae22b7](https://linux-hardware.org/?probe=08a1ae22b7) | May 25, 2023 |
| HP            | 15                          | Notebook    | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [46015ea246](https://linux-hardware.org/?probe=46015ea246) | May 10, 2023 |
| Fujitsu       | T900                        | Notebook    | [d0233bc511](https://linux-hardware.org/?probe=d0233bc511) | May 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [b5602599f8](https://linux-hardware.org/?probe=b5602599f8) | May 06, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [082029ecf5](https://linux-hardware.org/?probe=082029ecf5) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [e2f37d94cd](https://linux-hardware.org/?probe=e2f37d94cd) | May 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c8b979d035](https://linux-hardware.org/?probe=c8b979d035) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7f30bca791](https://linux-hardware.org/?probe=7f30bca791) | Apr 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [52ada88fb1](https://linux-hardware.org/?probe=52ada88fb1) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| Unknown       | Q-790                       | Desktop     | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [c90d525ee8](https://linux-hardware.org/?probe=c90d525ee8) | Mar 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [d5ba09feb1](https://linux-hardware.org/?probe=d5ba09feb1) | Mar 27, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d1ba8cb8e9](https://linux-hardware.org/?probe=d1ba8cb8e9) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [049eafecc8](https://linux-hardware.org/?probe=049eafecc8) | Mar 20, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | UX32LA                      | Notebook    | [3432e951dd](https://linux-hardware.org/?probe=3432e951dd) | Mar 06, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [73794bde33](https://linux-hardware.org/?probe=73794bde33) | Mar 03, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c9f0a04fcf](https://linux-hardware.org/?probe=c9f0a04fcf) | Feb 10, 2023 |
| HP            | 3047h                       | Desktop     | [bdb6af834f](https://linux-hardware.org/?probe=bdb6af834f) | Feb 08, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [311514a737](https://linux-hardware.org/?probe=311514a737) | Feb 07, 2023 |
| Toshiba       | Satellite C850D-B615        | Notebook    | [66a7f0123f](https://linux-hardware.org/?probe=66a7f0123f) | Feb 07, 2023 |
| Dell          | 0C8810                      | Desktop     | [1df9a88e4a](https://linux-hardware.org/?probe=1df9a88e4a) | Feb 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [caedc4c130](https://linux-hardware.org/?probe=caedc4c130) | Jan 29, 2023 |
| HP            | 630                         | Notebook    | [837878455e](https://linux-hardware.org/?probe=837878455e) | Jan 28, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5ad0221a16](https://linux-hardware.org/?probe=5ad0221a16) | Jan 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d0fe42d2fd](https://linux-hardware.org/?probe=d0fe42d2fd) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [940d192ea9](https://linux-hardware.org/?probe=940d192ea9) | Jan 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3bc61d7363](https://linux-hardware.org/?probe=3bc61d7363) | Jan 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cae0a5557a](https://linux-hardware.org/?probe=cae0a5557a) | Jan 12, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [00780c7a70](https://linux-hardware.org/?probe=00780c7a70) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [54eaec4178](https://linux-hardware.org/?probe=54eaec4178) | Jan 10, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [56e25a5805](https://linux-hardware.org/?probe=56e25a5805) | Dec 28, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [3e518355b6](https://linux-hardware.org/?probe=3e518355b6) | Dec 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [eccd29cfac](https://linux-hardware.org/?probe=eccd29cfac) | Dec 17, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [0de958194e](https://linux-hardware.org/?probe=0de958194e) | Dec 15, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [84c7e04946](https://linux-hardware.org/?probe=84c7e04946) | Dec 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [580fb6172f](https://linux-hardware.org/?probe=580fb6172f) | Dec 07, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [645418a0dd](https://linux-hardware.org/?probe=645418a0dd) | Nov 30, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [2a4bb490d0](https://linux-hardware.org/?probe=2a4bb490d0) | Nov 29, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [a05b99b00e](https://linux-hardware.org/?probe=a05b99b00e) | Nov 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [713f71652e](https://linux-hardware.org/?probe=713f71652e) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [34d3046ea4](https://linux-hardware.org/?probe=34d3046ea4) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [ff4e869df2](https://linux-hardware.org/?probe=ff4e869df2) | Nov 03, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ceb11d7b3](https://linux-hardware.org/?probe=2ceb11d7b3) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c3d640129](https://linux-hardware.org/?probe=5c3d640129) | Oct 29, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [7654e5f9c4](https://linux-hardware.org/?probe=7654e5f9c4) | Oct 26, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [7848c6d520](https://linux-hardware.org/?probe=7848c6d520) | Oct 26, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [43ce2df718](https://linux-hardware.org/?probe=43ce2df718) | Oct 12, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| HP            | 15                          | Notebook    | [28e8e01768](https://linux-hardware.org/?probe=28e8e01768) | Sep 28, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| HP            | 097Ch                       | Desktop     | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| HP            | 1493                        | Desktop     | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | Notebook    | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | 3397                        | Desktop     | [0679103825](https://linux-hardware.org/?probe=0679103825) | Jun 13, 2022 |
| HP            | 3397                        | Desktop     | [e86ba79fcf](https://linux-hardware.org/?probe=e86ba79fcf) | Jun 09, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [1f7a666022](https://linux-hardware.org/?probe=1f7a666022) | Jun 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Notebook      | P65xHP                      | Notebook    | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [94684071ed](https://linux-hardware.org/?probe=94684071ed) | May 05, 2022 |
| Dell          | Latitude 3340               | Notebook    | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Dell          | Latitude 3340               | Notebook    | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [ef1693c88f](https://linux-hardware.org/?probe=ef1693c88f) | Apr 07, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| HP            | 83EB                        | All in one  | [26fea5e4f7](https://linux-hardware.org/?probe=26fea5e4f7) | Mar 19, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [ec8ec429fc](https://linux-hardware.org/?probe=ec8ec429fc) | Mar 07, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c66cc8aa4e](https://linux-hardware.org/?probe=c66cc8aa4e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Lenovo        | ThinkPad T490s 20NYS8J90... | Notebook    | [c1aee9b559](https://linux-hardware.org/?probe=c1aee9b559) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| HP            | Presario CQ56               | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fac2fc3940](https://linux-hardware.org/?probe=fac2fc3940) | Jan 13, 2022 |
| Lenovo        | ThinkPad X240 20AL00CQAU    | Notebook    | [9f36bf55ba](https://linux-hardware.org/?probe=9f36bf55ba) | Jan 11, 2022 |
| HP            | Presario CQ56               | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | Notebook    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dff30c5ec8](https://linux-hardware.org/?probe=dff30c5ec8) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| Chuwi         | HeroBook Air                | Notebook    | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [820951b4af](https://linux-hardware.org/?probe=820951b4af) | Nov 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [022146ab90](https://linux-hardware.org/?probe=022146ab90) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c5620beab2](https://linux-hardware.org/?probe=c5620beab2) | Nov 07, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [94ac3dba1a](https://linux-hardware.org/?probe=94ac3dba1a) | Nov 07, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [516eabe645](https://linux-hardware.org/?probe=516eabe645) | Nov 02, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [170dd8b241](https://linux-hardware.org/?probe=170dd8b241) | Oct 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [ab55e1ade6](https://linux-hardware.org/?probe=ab55e1ade6) | Sep 22, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [40bf0d5bb0](https://linux-hardware.org/?probe=40bf0d5bb0) | Sep 17, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [b5a01103fd](https://linux-hardware.org/?probe=b5a01103fd) | Sep 14, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [a5290e7cb6](https://linux-hardware.org/?probe=a5290e7cb6) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [27b0daea73](https://linux-hardware.org/?probe=27b0daea73) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [b89fc8114f](https://linux-hardware.org/?probe=b89fc8114f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c642d92231](https://linux-hardware.org/?probe=c642d92231) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c374609a3e](https://linux-hardware.org/?probe=c374609a3e) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c9de881b72](https://linux-hardware.org/?probe=c9de881b72) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [10e46eeaf3](https://linux-hardware.org/?probe=10e46eeaf3) | Jul 25, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [88afb2e5a1](https://linux-hardware.org/?probe=88afb2e5a1) | Jul 23, 2021 |
| Acer          | Veriton X680G               | Desktop     | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b3a36bf681](https://linux-hardware.org/?probe=b3a36bf681) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [0f54d945d0](https://linux-hardware.org/?probe=0f54d945d0) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [daa99f3a24](https://linux-hardware.org/?probe=daa99f3a24) | Jul 15, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [6c9393a9d6](https://linux-hardware.org/?probe=6c9393a9d6) | Jul 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [e60c71a5e1](https://linux-hardware.org/?probe=e60c71a5e1) | Jun 25, 2021 |
| IBM           | Node 1, Processor Card      | Server      | [be2298910b](https://linux-hardware.org/?probe=be2298910b) | Jun 24, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [9d9ecee1b9](https://linux-hardware.org/?probe=9d9ecee1b9) | Jun 20, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Unknown       | Unknown                     | Phone       | [7948d69684](https://linux-hardware.org/?probe=7948d69684) | Jun 05, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [549f1c8bd1](https://linux-hardware.org/?probe=549f1c8bd1) | May 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [304747e4c6](https://linux-hardware.org/?probe=304747e4c6) | May 23, 2021 |
| IP3 Tech      | AB1                         | Mini pc     | [b2cc37b9ac](https://linux-hardware.org/?probe=b2cc37b9ac) | May 21, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [2c35ee27d9](https://linux-hardware.org/?probe=2c35ee27d9) | May 20, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [11b99bedb6](https://linux-hardware.org/?probe=11b99bedb6) | May 13, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [a71cb329b2](https://linux-hardware.org/?probe=a71cb329b2) | May 12, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [dc61da2d5e](https://linux-hardware.org/?probe=dc61da2d5e) | May 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [e8771a4577](https://linux-hardware.org/?probe=e8771a4577) | May 01, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ee57ec30cd](https://linux-hardware.org/?probe=ee57ec30cd) | Apr 28, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [95c380139d](https://linux-hardware.org/?probe=95c380139d) | Apr 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b35c15fb6b](https://linux-hardware.org/?probe=b35c15fb6b) | Apr 25, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [561287f5a8](https://linux-hardware.org/?probe=561287f5a8) | Apr 06, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [ecac5c48dc](https://linux-hardware.org/?probe=ecac5c48dc) | Apr 02, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [95f53c1b72](https://linux-hardware.org/?probe=95f53c1b72) | Mar 19, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [585322e740](https://linux-hardware.org/?probe=585322e740) | Mar 19, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [b345b644ae](https://linux-hardware.org/?probe=b345b644ae) | Mar 18, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [89e652d12d](https://linux-hardware.org/?probe=89e652d12d) | Mar 18, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [a4d5cb7e11](https://linux-hardware.org/?probe=a4d5cb7e11) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [31915e8c0b](https://linux-hardware.org/?probe=31915e8c0b) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [e166e551cd](https://linux-hardware.org/?probe=e166e551cd) | Mar 09, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [10c98c982d](https://linux-hardware.org/?probe=10c98c982d) | Mar 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [09037a0a1b](https://linux-hardware.org/?probe=09037a0a1b) | Mar 06, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron N5030              | Notebook    | [47077a37f2](https://linux-hardware.org/?probe=47077a37f2) | Feb 25, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [c4ab183609](https://linux-hardware.org/?probe=c4ab183609) | Feb 24, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [55c54121f8](https://linux-hardware.org/?probe=55c54121f8) | Feb 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3311619921](https://linux-hardware.org/?probe=3311619921) | Feb 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b573c1e746](https://linux-hardware.org/?probe=b573c1e746) | Feb 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [eda69993ed](https://linux-hardware.org/?probe=eda69993ed) | Feb 17, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [66c8150e0d](https://linux-hardware.org/?probe=66c8150e0d) | Feb 14, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96be56a30d](https://linux-hardware.org/?probe=96be56a30d) | Feb 13, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [336989b30d](https://linux-hardware.org/?probe=336989b30d) | Feb 10, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [439563e244](https://linux-hardware.org/?probe=439563e244) | Feb 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [38d7cb1271](https://linux-hardware.org/?probe=38d7cb1271) | Feb 06, 2021 |
| Dell          | Inspiron 3580               | Notebook    | [417752f660](https://linux-hardware.org/?probe=417752f660) | Jan 30, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f56f2da985](https://linux-hardware.org/?probe=f56f2da985) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52s 20LB0021US    | Notebook    | [4e50af07df](https://linux-hardware.org/?probe=4e50af07df) | Jan 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [671c83ebf7](https://linux-hardware.org/?probe=671c83ebf7) | Jan 27, 2021 |
| HP            | ProBook 6560b               | Notebook    | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [e2f7ccd4ad](https://linux-hardware.org/?probe=e2f7ccd4ad) | Jan 14, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [9b2af2d13c](https://linux-hardware.org/?probe=9b2af2d13c) | Jan 13, 2021 |
| HP            | ProBook 6560b               | Notebook    | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Endless       | EF20EA                      | Notebook    | [c216bffe9d](https://linux-hardware.org/?probe=c216bffe9d) | Dec 20, 2020 |
| Endless       | EF20EA                      | Notebook    | [e2409b47e2](https://linux-hardware.org/?probe=e2409b47e2) | Dec 20, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [c3c7909b48](https://linux-hardware.org/?probe=c3c7909b48) | Dec 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c764c0655e](https://linux-hardware.org/?probe=c764c0655e) | Dec 16, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | Notebook    | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [885a64d9d3](https://linux-hardware.org/?probe=885a64d9d3) | Dec 12, 2020 |
| ASUSTek       | X202EV                      | Notebook    | [b3b2381999](https://linux-hardware.org/?probe=b3b2381999) | Nov 25, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X240 20AMS4J900    | Notebook    | [8a54e51f5a](https://linux-hardware.org/?probe=8a54e51f5a) | Nov 17, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [7c1f9ebdef](https://linux-hardware.org/?probe=7c1f9ebdef) | Nov 12, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [ccefa81140](https://linux-hardware.org/?probe=ccefa81140) | Nov 12, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [5c863855cc](https://linux-hardware.org/?probe=5c863855cc) | Nov 11, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [372e62dd5a](https://linux-hardware.org/?probe=372e62dd5a) | Nov 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [6b0122d8c2](https://linux-hardware.org/?probe=6b0122d8c2) | Nov 06, 2020 |
| HP            | 3396                        | Desktop     | [12e6dc258e](https://linux-hardware.org/?probe=12e6dc258e) | Oct 31, 2020 |
| HP            | 3396                        | Desktop     | [876ee024dc](https://linux-hardware.org/?probe=876ee024dc) | Oct 31, 2020 |
| HP            | Spectre x360 Convertible    | Convertible | [b4e75e63fb](https://linux-hardware.org/?probe=b4e75e63fb) | Oct 30, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1f1909639](https://linux-hardware.org/?probe=e1f1909639) | Oct 25, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1bbf1beb6](https://linux-hardware.org/?probe=e1bbf1beb6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [a2eb617037](https://linux-hardware.org/?probe=a2eb617037) | Oct 16, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6ea891ad6b](https://linux-hardware.org/?probe=6ea891ad6b) | Oct 13, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [8307343ab3](https://linux-hardware.org/?probe=8307343ab3) | Oct 09, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [2c6d570678](https://linux-hardware.org/?probe=2c6d570678) | Oct 09, 2020 |
| Unknown       | Unknown                     | Phone       | [6f31ab4962](https://linux-hardware.org/?probe=6f31ab4962) | Oct 03, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5b0c257b43](https://linux-hardware.org/?probe=5b0c257b43) | Oct 02, 2020 |
| Dell          | Latitude D820               | Notebook    | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [47a129fdd0](https://linux-hardware.org/?probe=47a129fdd0) | Sep 28, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ebcb037006](https://linux-hardware.org/?probe=ebcb037006) | Sep 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8232648226](https://linux-hardware.org/?probe=8232648226) | Sep 20, 2020 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [37985e0340](https://linux-hardware.org/?probe=37985e0340) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [92ee6a03be](https://linux-hardware.org/?probe=92ee6a03be) | Sep 14, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [f51d9347e3](https://linux-hardware.org/?probe=f51d9347e3) | Sep 10, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [6e6f79b651](https://linux-hardware.org/?probe=6e6f79b651) | Sep 10, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc38793462](https://linux-hardware.org/?probe=dc38793462) | Sep 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [4d64af6a38](https://linux-hardware.org/?probe=4d64af6a38) | Sep 07, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [6e93ef18ce](https://linux-hardware.org/?probe=6e93ef18ce) | Sep 03, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [19a0f0bfdc](https://linux-hardware.org/?probe=19a0f0bfdc) | Sep 03, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [9c70b1dad4](https://linux-hardware.org/?probe=9c70b1dad4) | Sep 02, 2020 |
| MSI           | 0A90                        | Desktop     | [4f8d53458d](https://linux-hardware.org/?probe=4f8d53458d) | Aug 11, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [31f100c680](https://linux-hardware.org/?probe=31f100c680) | Aug 10, 2020 |
| MSI           | 0A90                        | Desktop     | [04bdc6569a](https://linux-hardware.org/?probe=04bdc6569a) | Aug 09, 2020 |
| MSI           | 2AE0                        | Desktop     | [54a32fea6e](https://linux-hardware.org/?probe=54a32fea6e) | Aug 02, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [2a88596017](https://linux-hardware.org/?probe=2a88596017) | Jul 30, 2020 |
| HP            | Pavilion Laptop 15t-cs20... | Notebook    | [f778796026](https://linux-hardware.org/?probe=f778796026) | Jul 16, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [551521f7c9](https://linux-hardware.org/?probe=551521f7c9) | Jul 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [a1265cca74](https://linux-hardware.org/?probe=a1265cca74) | Jul 11, 2020 |
| Dell          | 0VNP2H A00                  | Desktop     | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [412f31bc06](https://linux-hardware.org/?probe=412f31bc06) | Jul 01, 2020 |
| Lenovo        | ThinkPad L480 20LTS1RE0Y    | Notebook    | [76ef35dd77](https://linux-hardware.org/?probe=76ef35dd77) | Jun 26, 2020 |
| HP            | 0AA8h                       | Desktop     | [e60c30f572](https://linux-hardware.org/?probe=e60c30f572) | Jun 25, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4f747e9c8a](https://linux-hardware.org/?probe=4f747e9c8a) | Jun 25, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [21efc22417](https://linux-hardware.org/?probe=21efc22417) | Jun 21, 2020 |
| Dell          | Latitude 3150               | Notebook    | [0299c15a34](https://linux-hardware.org/?probe=0299c15a34) | Jun 20, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [6277131dfd](https://linux-hardware.org/?probe=6277131dfd) | Jun 20, 2020 |
| HP            | 0AA8h                       | Desktop     | [4017115305](https://linux-hardware.org/?probe=4017115305) | Jun 19, 2020 |
| HP            | 0AA8h                       | Desktop     | [752505c134](https://linux-hardware.org/?probe=752505c134) | Jun 17, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [f16d9a4077](https://linux-hardware.org/?probe=f16d9a4077) | Jun 17, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [530934acb0](https://linux-hardware.org/?probe=530934acb0) | Jun 17, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [0e66f9df2c](https://linux-hardware.org/?probe=0e66f9df2c) | Jun 16, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [620453a9dc](https://linux-hardware.org/?probe=620453a9dc) | Jun 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [483d2473b0](https://linux-hardware.org/?probe=483d2473b0) | Jun 15, 2020 |
| Getac         | V110                        | Notebook    | [4e3a330cb5](https://linux-hardware.org/?probe=4e3a330cb5) | Jun 13, 2020 |
| HP            | 3032h                       | Desktop     | [8aa1dd8ecd](https://linux-hardware.org/?probe=8aa1dd8ecd) | Jun 13, 2020 |
| Toshiba       | R84SAU2                     | Notebook    | [d59976ae7f](https://linux-hardware.org/?probe=d59976ae7f) | Jun 10, 2020 |
| Acer          | Aspire A315-33              | Notebook    | [c0eeb5a67b](https://linux-hardware.org/?probe=c0eeb5a67b) | Jun 03, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [e903b1af8a](https://linux-hardware.org/?probe=e903b1af8a) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [5d99be49f0](https://linux-hardware.org/?probe=5d99be49f0) | May 31, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [75e6d735a0](https://linux-hardware.org/?probe=75e6d735a0) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [6b4292fc06](https://linux-hardware.org/?probe=6b4292fc06) | May 30, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [bdab68c78a](https://linux-hardware.org/?probe=bdab68c78a) | May 25, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [8240cd4643](https://linux-hardware.org/?probe=8240cd4643) | May 17, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [227b4dc4ec](https://linux-hardware.org/?probe=227b4dc4ec) | May 15, 2020 |
| Apple         | MacBookPro3,1               | Notebook    | [5ca063ed58](https://linux-hardware.org/?probe=5ca063ed58) | May 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [7a885b703e](https://linux-hardware.org/?probe=7a885b703e) | May 10, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [0420235572](https://linux-hardware.org/?probe=0420235572) | May 08, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [a8caa085de](https://linux-hardware.org/?probe=a8caa085de) | May 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [85b487e27d](https://linux-hardware.org/?probe=85b487e27d) | May 02, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [32e3129638](https://linux-hardware.org/?probe=32e3129638) | May 02, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cc8b2bc724](https://linux-hardware.org/?probe=cc8b2bc724) | Apr 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | Notebook    | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | Notebook    | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [a26feb7507](https://linux-hardware.org/?probe=a26feb7507) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [2807f4c586](https://linux-hardware.org/?probe=2807f4c586) | Mar 12, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [b634560d95](https://linux-hardware.org/?probe=b634560d95) | Mar 01, 2020 |
| HP            | 09F0h                       | Desktop     | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP            | 09F0h                       | Desktop     | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [eb1591f00c](https://linux-hardware.org/?probe=eb1591f00c) | Dec 23, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [6f8fd31c2c](https://linux-hardware.org/?probe=6f8fd31c2c) | Dec 19, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [a18a54d051](https://linux-hardware.org/?probe=a18a54d051) | Oct 30, 2019 |
| Dell          | Latitude E6220              | Notebook    | [37cf274f19](https://linux-hardware.org/?probe=37cf274f19) | Oct 30, 2019 |
| HP            | EliteBook 820 G2            | Notebook    | [05b4f35642](https://linux-hardware.org/?probe=05b4f35642) | Oct 11, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f0f19467e3](https://linux-hardware.org/?probe=f0f19467e3) | Sep 04, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [2ec595f039](https://linux-hardware.org/?probe=2ec595f039) | Sep 03, 2019 |
| HP            | ENVY TS 15                  | Notebook    | [054a6961ec](https://linux-hardware.org/?probe=054a6961ec) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | Notebook    | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f9f9fbd6bd](https://linux-hardware.org/?probe=f9f9fbd6bd) | Aug 06, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [e2c04796a0](https://linux-hardware.org/?probe=e2c04796a0) | Jul 25, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [70e21ebad0](https://linux-hardware.org/?probe=70e21ebad0) | Jun 30, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [25b5bf978a](https://linux-hardware.org/?probe=25b5bf978a) | Jun 29, 2019 |
| HP            | 0AA0h                       | Desktop     | [1787c13656](https://linux-hardware.org/?probe=1787c13656) | Jun 15, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [8f23861866](https://linux-hardware.org/?probe=8f23861866) | Jun 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [57dd20a793](https://linux-hardware.org/?probe=57dd20a793) | Jun 03, 2019 |
| Dell          | Inspiron 5570               | Notebook    | [86722cf4ab](https://linux-hardware.org/?probe=86722cf4ab) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [ca99cb8e00](https://linux-hardware.org/?probe=ca99cb8e00) | Apr 10, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [2f1b160149](https://linux-hardware.org/?probe=2f1b160149) | Nov 19, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9cfa1aef75](https://linux-hardware.org/?probe=9cfa1aef75) | Jun 20, 2018 |
| EUROCOM       | Q6                          | Notebook    | [001ab8c139](https://linux-hardware.org/?probe=001ab8c139) | Jun 02, 2018 |
| EUROCOM       | Q6                          | Notebook    | [15b4e0daf2](https://linux-hardware.org/?probe=15b4e0daf2) | Jun 02, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9fcaed033f](https://linux-hardware.org/?probe=9fcaed033f) | Mar 09, 2018 |
| Sony          | VGN-NS295J                  | Notebook    | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | Notebook    | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 14.89%  |
| Ubuntu 22.04                 | 30        | 9.71%   |
| Ubuntu 18.04                 | 19        | 6.15%   |
| Zorin 16                     | 7         | 2.27%   |
| Linux Mint 20.3              | 7         | 2.27%   |
| Fedora 36                    | 7         | 2.27%   |
| Arch Rolling                 | 7         | 2.27%   |
| Zorin 15                     | 6         | 1.94%   |
| Manjaro                      | 6         | 1.94%   |
| Fedora 38                    | 6         | 1.94%   |
| Ubuntu 23.04                 | 5         | 1.62%   |
| Pop!_OS 20.04                | 5         | 1.62%   |
| OpenMandriva 4.2             | 5         | 1.62%   |
| Arch                         | 5         | 1.62%   |
| Ubuntu 20.10                 | 4         | 1.29%   |
| Ubuntu 19.04                 | 4         | 1.29%   |
| Linux Mint 21                | 4         | 1.29%   |
| Fedora 37                    | 4         | 1.29%   |
| Debian 11                    | 4         | 1.29%   |
| ArcoLinux Rolling            | 4         | 1.29%   |
| Ubuntu 21.10                 | 3         | 0.97%   |
| Ubuntu 21.04                 | 3         | 0.97%   |
| Q4OS 3                       | 3         | 0.97%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.97%   |
| Linux Mint 21.2              | 3         | 0.97%   |
| Linux Mint 20.2              | 3         | 0.97%   |
| Fedora 35                    | 3         | 0.97%   |
| Fedora 33                    | 3         | 0.97%   |
| Fedora 32                    | 3         | 0.97%   |
| Ubuntu 19.10                 | 2         | 0.65%   |
| Pop!_OS 22.04                | 2         | 0.65%   |
| Pop!_OS 20.10                | 2         | 0.65%   |
| Parrot 5.3                   | 2         | 0.65%   |
| Parrot 5.1                   | 2         | 0.65%   |
| OpenMandriva 4.3             | 2         | 0.65%   |
| Linux Mint 19                | 2         | 0.65%   |
| Kali 2023.3                  | 2         | 0.65%   |
| Kali 2023.2                  | 2         | 0.65%   |
| Kali 2022.3                  | 2         | 0.65%   |
| Kali 2020.1                  | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 111       | 38.41%  |
| Fedora        | 25        | 8.65%   |
| Linux Mint    | 19        | 6.57%   |
| Zorin         | 13        | 4.5%    |
| Arch          | 12        | 4.15%   |
| Endless       | 11        | 3.81%   |
| OpenMandriva  | 10        | 3.46%   |
| Manjaro       | 10        | 3.46%   |
| Pop!_OS       | 9         | 3.11%   |
| Kali          | 9         | 3.11%   |
| Parrot        | 8         | 2.77%   |
| Debian        | 7         | 2.42%   |
| Elementary    | 5         | 1.73%   |
| ArcoLinux     | 4         | 1.38%   |
| Q4OS          | 3         | 1.04%   |
| openSUSE      | 3         | 1.04%   |
| Ubuntu MATE   | 2         | 0.69%   |
| ROSA          | 2         | 0.69%   |
| RHEL          | 2         | 0.69%   |
| Lubuntu       | 2         | 0.69%   |
| KDE neon      | 2         | 0.69%   |
| Garuda Linux  | 2         | 0.69%   |
| Deepin        | 2         | 0.69%   |
| BlackPanther  | 2         | 0.69%   |
| Android       | 2         | 0.69%   |
| Xubuntu       | 1         | 0.35%   |
| Ubuntu Studio | 1         | 0.35%   |
| Ubuntu Budgie | 1         | 0.35%   |
| Rocky Linux   | 1         | 0.35%   |
| Nobara        | 1         | 0.35%   |
| Mageia        | 1         | 0.35%   |
| LMDE          | 1         | 0.35%   |
| Lilidog       | 1         | 0.35%   |
| CentOS        | 1         | 0.35%   |
| blendOS       | 1         | 0.35%   |
| antiX         | 1         | 0.35%   |
| Alpine        | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 1.81%   |
| 5.4.0-42-generic         | 5         | 1.51%   |
| 5.15.0-58-generic        | 5         | 1.51%   |
| 5.15.0-52-generic        | 5         | 1.51%   |
| 5.15.0-41-generic        | 5         | 1.51%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.51%   |
| 5.4.0-52-generic         | 4         | 1.2%    |
| 5.19.0-41-generic        | 4         | 1.2%    |
| 5.11.0-38-generic        | 4         | 1.2%    |
| 6.2.0-32-generic         | 3         | 0.9%    |
| 5.8.0-43-generic         | 3         | 0.9%    |
| 5.4.0-58-generic         | 3         | 0.9%    |
| 5.4.0-45-generic         | 3         | 0.9%    |
| 5.4.0-37-generic         | 3         | 0.9%    |
| 5.4.0-137-generic        | 3         | 0.9%    |
| 5.3.0-28-generic         | 3         | 0.9%    |
| 5.19.0-38-generic        | 3         | 0.9%    |
| 5.19.0-35-generic        | 3         | 0.9%    |
| 5.15.0-53-generic        | 3         | 0.9%    |
| 4.19.0-17-amd64          | 3         | 0.9%    |
| 6.3.0-kali1-amd64        | 2         | 0.6%    |
| 6.1.0-kali7-amd64        | 2         | 0.6%    |
| 5.9.13-200.fc33.x86_64   | 2         | 0.6%    |
| 5.8.4-200.fc32.x86_64    | 2         | 0.6%    |
| 5.8.0-63-generic         | 2         | 0.6%    |
| 5.8.0-59-generic         | 2         | 0.6%    |
| 5.8.0-55-generic         | 2         | 0.6%    |
| 5.8.0-50-generic         | 2         | 0.6%    |
| 5.4.0-67-generic         | 2         | 0.6%    |
| 5.4.0-65-generic         | 2         | 0.6%    |
| 5.4.0-54-generic         | 2         | 0.6%    |
| 5.4.0-48-generic         | 2         | 0.6%    |
| 5.4.0-47-generic         | 2         | 0.6%    |
| 5.4.0-33-generic         | 2         | 0.6%    |
| 5.4.0-19-generic         | 2         | 0.6%    |
| 5.3.0-62-generic         | 2         | 0.6%    |
| 5.19.9-200.fc36.x86_64   | 2         | 0.6%    |
| 5.18.13-200.fc36.x86_64  | 2         | 0.6%    |
| 5.18.0-14parrot1-amd64   | 2         | 0.6%    |
| 5.16.7-desktop-1omv4003  | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 16.24%  |
| 5.15.0  | 28        | 8.92%   |
| 5.8.0   | 24        | 7.64%   |
| 5.11.0  | 17        | 5.41%   |
| 5.19.0  | 12        | 3.82%   |
| 5.13.0  | 12        | 3.82%   |
| 4.15.0  | 12        | 3.82%   |
| 5.3.0   | 10        | 3.18%   |
| 5.0.0   | 9         | 2.87%   |
| 6.2.0   | 8         | 2.55%   |
| 6.1.0   | 7         | 2.23%   |
| 5.10.0  | 6         | 1.91%   |
| 5.10.14 | 5         | 1.59%   |
| 5.18.0  | 4         | 1.27%   |
| 4.19.0  | 4         | 1.27%   |
| 4.18.0  | 4         | 1.27%   |
| 5.19.9  | 3         | 0.96%   |
| 5.16.7  | 3         | 0.96%   |
| 5.14.0  | 3         | 0.96%   |
| 6.4.8   | 2         | 0.64%   |
| 6.3.4   | 2         | 0.64%   |
| 6.3.0   | 2         | 0.64%   |
| 6.1.52  | 2         | 0.64%   |
| 5.9.13  | 2         | 0.64%   |
| 5.8.4   | 2         | 0.64%   |
| 5.18.13 | 2         | 0.64%   |
| 5.17.5  | 2         | 0.64%   |
| 5.13.19 | 2         | 0.64%   |
| 4.18.16 | 2         | 0.64%   |
| 6.5.7   | 1         | 0.32%   |
| 6.5.6   | 1         | 0.32%   |
| 6.5.5   | 1         | 0.32%   |
| 6.5.2   | 1         | 0.32%   |
| 6.5.0   | 1         | 0.32%   |
| 6.4.15  | 1         | 0.32%   |
| 6.4.14  | 1         | 0.32%   |
| 6.4.11  | 1         | 0.32%   |
| 6.3.8   | 1         | 0.32%   |
| 6.3.6   | 1         | 0.32%   |
| 6.3.5   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 16.4%   |
| 5.15    | 33        | 10.61%  |
| 5.8     | 27        | 8.68%   |
| 5.19    | 21        | 6.75%   |
| 5.11    | 18        | 5.79%   |
| 6.1     | 15        | 4.82%   |
| 5.10    | 15        | 4.82%   |
| 5.13    | 14        | 4.5%    |
| 6.2     | 12        | 3.86%   |
| 4.15    | 12        | 3.86%   |
| 5.3     | 10        | 3.22%   |
| 5.0     | 10        | 3.22%   |
| 6.3     | 7         | 2.25%   |
| 5.16    | 7         | 2.25%   |
| 5.18    | 6         | 1.93%   |
| 5.14    | 6         | 1.93%   |
| 4.18    | 6         | 1.93%   |
| 6.5     | 5         | 1.61%   |
| 6.4     | 5         | 1.61%   |
| 4.19    | 5         | 1.61%   |
| 6.0     | 3         | 0.96%   |
| 5.9     | 3         | 0.96%   |
| 5.6     | 3         | 0.96%   |
| 5.17    | 3         | 0.96%   |
| 4.9     | 3         | 0.96%   |
| 5.2     | 2         | 0.64%   |
| 5.12    | 2         | 0.64%   |
| 5.7     | 1         | 0.32%   |
| 5.5     | 1         | 0.32%   |
| 5.1     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.16    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |
| 3.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 274       | 97.86%  |
| i686    | 4         | 1.43%   |
| armv8l  | 1         | 0.36%   |
| aarch64 | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 168       | 57.73%  |
| KDE5            | 33        | 11.34%  |
| Unknown         | 28        | 9.62%   |
| X-Cinnamon      | 17        | 5.84%   |
| XFCE            | 14        | 4.81%   |
| MATE            | 9         | 3.09%   |
| Pantheon        | 5         | 1.72%   |
| KDE             | 4         | 1.37%   |
| LXQt            | 2         | 0.69%   |
| KDE4            | 2         | 0.69%   |
| Cinnamon        | 2         | 0.69%   |
| awesome         | 2         | 0.69%   |
| openbox         | 1         | 0.34%   |
| GNOME Flashback | 1         | 0.34%   |
| DWM             | 1         | 0.34%   |
| Deepin          | 1         | 0.34%   |
| DDE             | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 196       | 67.59%  |
| Wayland | 75        | 25.86%  |
| Unknown | 15        | 5.17%   |
| Tty     | 4         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 131       | 45.33%  |
| GDM3    | 44        | 15.22%  |
| GDM     | 39        | 13.49%  |
| SDDM    | 37        | 12.8%   |
| LightDM | 31        | 10.73%  |
| TDM     | 5         | 1.73%   |
| KDM     | 2         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 214       | 75.35%  |
| en_GB   | 33        | 11.62%  |
| Unknown | 30        | 10.56%  |
| C       | 6         | 2.11%   |
| en_AG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 154       | 53.66%  |
| EFI  | 133       | 46.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 217       | 76.41%  |
| Btrfs   | 32        | 11.27%  |
| Overlay | 17        | 5.99%   |
| Tmpfs   | 9         | 3.17%   |
| Unknown | 5         | 1.76%   |
| Xfs     | 3         | 1.06%   |
| Zfs     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 140       | 48.95%  |
| GPT     | 106       | 37.06%  |
| MBR     | 40        | 13.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 245       | 86.88%  |
| Yes       | 37        | 13.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 68.44%  |
| Yes       | 89        | 31.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 120       | 42.86%  |
| Lenovo                      | 53        | 18.93%  |
| Dell                        | 38        | 13.57%  |
| ASUSTek Computer            | 11        | 3.93%   |
| Toshiba                     | 8         | 2.86%   |
| MSI                         | 5         | 1.79%   |
| Acer                        | 5         | 1.79%   |
| Gigabyte Technology         | 4         | 1.43%   |
| Unknown                     | 4         | 1.43%   |
| Samsung Electronics         | 3         | 1.07%   |
| Apple                       | 3         | 1.07%   |
| Endless                     | 2         | 0.71%   |
| Chuwi                       | 2         | 0.71%   |
| ASRock                      | 2         | 0.71%   |
| TECNO                       | 1         | 0.36%   |
| Sony                        | 1         | 0.36%   |
| SLIMBOOK                    | 1         | 0.36%   |
| Panasonic                   | 1         | 0.36%   |
| Notebook                    | 1         | 0.36%   |
| LG Electronics              | 1         | 0.36%   |
| IP3 Tech                    | 1         | 0.36%   |
| Intel                       | 1         | 0.36%   |
| Insyde                      | 1         | 0.36%   |
| IBM                         | 1         | 0.36%   |
| I-Life Digital Technologies | 1         | 0.36%   |
| HUAWEI                      | 1         | 0.36%   |
| Getac                       | 1         | 0.36%   |
| Fujitsu                     | 1         | 0.36%   |
| Foxconn                     | 1         | 0.36%   |
| EVOC                        | 1         | 0.36%   |
| EUROCOM                     | 1         | 0.36%   |
| Eluktronics                 | 1         | 0.36%   |
| Clevo                       | 1         | 0.36%   |
| AMI                         | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| HP EliteBook 840 G1               | 7         | 2.5%    |
| Unknown                           | 6         | 2.14%   |
| HP EliteBook 840 G3               | 5         | 1.79%   |
| HP EliteBook Folio 9470m          | 4         | 1.43%   |
| Dell XPS 13 9310                  | 4         | 1.43%   |
| HP Notebook                       | 3         | 1.07%   |
| HP EliteBook Folio 9480m          | 3         | 1.07%   |
| HP EliteBook 8460p                | 3         | 1.07%   |
| HP EliteBook 2570p                | 3         | 1.07%   |
| HP 15                             | 3         | 1.07%   |
| Toshiba Satellite C660            | 2         | 0.71%   |
| MSI MS-7C02                       | 2         | 0.71%   |
| Lenovo IdeaPad S340-14IIL 81VV    | 2         | 0.71%   |
| Lenovo G50-80 80E5                | 2         | 0.71%   |
| HP Spectre x360 Convertible       | 2         | 0.71%   |
| HP ProBook 6560b                  | 2         | 0.71%   |
| HP ProBook 640 G1                 | 2         | 0.71%   |
| HP ProBook 4540s                  | 2         | 0.71%   |
| HP ProBook 440 G5                 | 2         | 0.71%   |
| HP Pavilion Laptop 15-cs3xxx      | 2         | 0.71%   |
| HP ENVY 15                        | 2         | 0.71%   |
| HP EliteBook 8440p                | 2         | 0.71%   |
| HP EliteBook 840 G2               | 2         | 0.71%   |
| HP Compaq Mini 110c-1100          | 2         | 0.71%   |
| HP 630                            | 2         | 0.71%   |
| HP 15 Notebook PC                 | 2         | 0.71%   |
| Endless EF20EA                    | 2         | 0.71%   |
| Dell OptiPlex 7010                | 2         | 0.71%   |
| Dell Latitude E6410               | 2         | 0.71%   |
| Dell Inspiron 5767                | 2         | 0.71%   |
| ASUS X540NA                       | 2         | 0.71%   |
| Toshiba TECRA A50-A               | 1         | 0.36%   |
| Toshiba Satellite L50-B           | 1         | 0.36%   |
| Toshiba Satellite C850D-B615      | 1         | 0.36%   |
| Toshiba R84SAU2                   | 1         | 0.36%   |
| Toshiba dynabook Satellite B554/M | 1         | 0.36%   |
| Toshiba dynabook R731/E           | 1         | 0.36%   |
| TECNO WinPad 2                    | 1         | 0.36%   |
| Sony VGN-NS295J                   | 1         | 0.36%   |
| SLIMBOOK PROX14-AMD               | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 42        | 15%     |
| Lenovo ThinkPad        | 26        | 9.29%   |
| HP ProBook             | 18        | 6.43%   |
| Lenovo IdeaPad         | 12        | 4.29%   |
| Dell OptiPlex          | 12        | 4.29%   |
| HP Pavilion            | 10        | 3.57%   |
| HP Compaq              | 10        | 3.57%   |
| Dell Latitude          | 10        | 3.57%   |
| HP ENVY                | 9         | 3.21%   |
| Dell Inspiron          | 9         | 3.21%   |
| Unknown                | 6         | 2.14%   |
| HP Laptop              | 5         | 1.79%   |
| HP 15                  | 5         | 1.79%   |
| Dell XPS               | 5         | 1.79%   |
| Toshiba Satellite      | 4         | 1.43%   |
| HP Spectre             | 4         | 1.43%   |
| Acer Aspire            | 4         | 1.43%   |
| Lenovo Legion          | 3         | 1.07%   |
| HP Notebook            | 3         | 1.07%   |
| Toshiba dynabook       | 2         | 0.71%   |
| MSI MS-7C02            | 2         | 0.71%   |
| Lenovo ThinkCentre     | 2         | 0.71%   |
| Lenovo G50-80          | 2         | 0.71%   |
| HP ZBook               | 2         | 0.71%   |
| HP 630                 | 2         | 0.71%   |
| Endless EF20EA         | 2         | 0.71%   |
| ASUS X540NA            | 2         | 0.71%   |
| Toshiba TECRA          | 1         | 0.36%   |
| Toshiba R84SAU2        | 1         | 0.36%   |
| TECNO WinPad           | 1         | 0.36%   |
| Sony VGN-NS295J        | 1         | 0.36%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.36%   |
| Samsung RC410          | 1         | 0.36%   |
| Samsung 300E5EV        | 1         | 0.36%   |
| Samsung 300E4C         | 1         | 0.36%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.36%   |
| Notebook P65xHP        | 1         | 0.36%   |
| MSI MS-7D31            | 1         | 0.36%   |
| MSI 500-007A           | 1         | 0.36%   |
| MSI 0A90               | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 29        | 10.36%  |
| 2018    | 27        | 9.64%   |
| 2016    | 25        | 8.93%   |
| 2012    | 25        | 8.93%   |
| 2015    | 24        | 8.57%   |
| 2019    | 23        | 8.21%   |
| 2011    | 20        | 7.14%   |
| 2014    | 19        | 6.79%   |
| 2017    | 18        | 6.43%   |
| 2020    | 17        | 6.07%   |
| 2010    | 15        | 5.36%   |
| 2021    | 9         | 3.21%   |
| 2022    | 6         | 2.14%   |
| 2008    | 6         | 2.14%   |
| 2007    | 5         | 1.79%   |
| 2009    | 3         | 1.07%   |
| 2006    | 3         | 1.07%   |
| Unknown | 3         | 1.07%   |
| 2005    | 2         | 0.71%   |
| 2004    | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 213       | 76.07%  |
| Desktop     | 44        | 15.71%  |
| Convertible | 17        | 6.07%   |
| Phone       | 2         | 0.71%   |
| Mini pc     | 2         | 0.71%   |
| All in one  | 1         | 0.36%   |
| Server      | 1         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 261       | 91.9%   |
| Enabled  | 23        | 8.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 280       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 80        | 28.17%  |
| 3.01-4.0        | 70        | 24.65%  |
| 8.01-16.0       | 44        | 15.49%  |
| 16.01-24.0      | 41        | 14.44%  |
| 1.01-2.0        | 22        | 7.75%   |
| 32.01-64.0      | 13        | 4.58%   |
| 64.01-256.0     | 5         | 1.76%   |
| 24.01-32.0      | 3         | 1.06%   |
| 0.51-1.0        | 3         | 1.06%   |
| 2.01-3.0        | 2         | 0.7%    |
| More than 256.0 | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 84        | 26.75%  |
| 1.01-2.0    | 81        | 25.8%   |
| 4.01-8.0    | 56        | 17.83%  |
| 3.01-4.0    | 56        | 17.83%  |
| 0.51-1.0    | 22        | 7.01%   |
| 8.01-16.0   | 10        | 3.18%   |
| 0.01-0.5    | 3         | 0.96%   |
| 64.01-256.0 | 1         | 0.32%   |
| Unknown     | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 220       | 76.92%  |
| 2      | 49        | 17.13%  |
| 4      | 5         | 1.75%   |
| 3      | 5         | 1.75%   |
| 0      | 3         | 1.05%   |
| 10     | 1         | 0.35%   |
| 8      | 1         | 0.35%   |
| 6      | 1         | 0.35%   |
| 5      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 64.29%  |
| Yes       | 100       | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 82.5%   |
| No        | 49        | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 87.19%  |
| No        | 36        | 12.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 67.84%  |
| No        | 91        | 32.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 280       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Computers | Percent |
|-----------|-----------|---------|
| Nairobi   | 262       | 90.66%  |
| Mombasa   | 4         | 1.38%   |
| Nakuru    | 3         | 1.04%   |
| Kiambu    | 3         | 1.04%   |
| Nyeri     | 2         | 0.69%   |
| Kikuyu    | 2         | 0.69%   |
| Eldoret   | 2         | 0.69%   |
| Wote      | 1         | 0.35%   |
| Rongai    | 1         | 0.35%   |
| Nyahururu | 1         | 0.35%   |
| Narok     | 1         | 0.35%   |
| Nanyuki   | 1         | 0.35%   |
| Murang'a  | 1         | 0.35%   |
| Maralal   | 1         | 0.35%   |
| Machakos  | 1         | 0.35%   |
| Kisii     | 1         | 0.35%   |
| Kericho   | 1         | 0.35%   |
| Embakasi  | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 81        | 108    | 23.68%  |
| WDC                         | 46        | 56     | 13.45%  |
| Samsung Electronics         | 39        | 56     | 11.4%   |
| Toshiba                     | 37        | 42     | 10.82%  |
| HGST                        | 20        | 32     | 5.85%   |
| Unknown                     | 19        | 26     | 5.56%   |
| Sandisk                     | 14        | 17     | 4.09%   |
| Hitachi                     | 12        | 15     | 3.51%   |
| Intel                       | 7         | 9      | 2.05%   |
| Micron Technology           | 6         | 7      | 1.75%   |
| Crucial                     | 6         | 8      | 1.75%   |
| SPCC                        | 5         | 9      | 1.46%   |
| MARSHAL                     | 5         | 5      | 1.46%   |
| SK hynix                    | 4         | 5      | 1.17%   |
| Lexar                       | 4         | 4      | 1.17%   |
| Kingston                    | 4         | 6      | 1.17%   |
| Unknown                     | 4         | 4      | 1.17%   |
| Team                        | 2         | 2      | 0.58%   |
| Maxtor                      | 2         | 2      | 0.58%   |
| LITEON                      | 2         | 2      | 0.58%   |
| HUAWEI                      | 2         | 2      | 0.58%   |
| China                       | 2         | 2      | 0.58%   |
| Apple                       | 2         | 2      | 0.58%   |
| A-DATA Technology           | 2         | 2      | 0.58%   |
| Union Memory                | 1         | 1      | 0.29%   |
| TCSUNBOW                    | 1         | 1      | 0.29%   |
| Plextor                     | 1         | 1      | 0.29%   |
| Netac                       | 1         | 1      | 0.29%   |
| Micron/Crucial Technology   | 1         | 2      | 0.29%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.29%   |
| MAX                         | 1         | 1      | 0.29%   |
| LITEONIT                    | 1         | 1      | 0.29%   |
| Lite-On Technology          | 1         | 2      | 0.29%   |
| KINGBANK                    | 1         | 1      | 0.29%   |
| Hjwdz                       | 1         | 1      | 0.29%   |
| Golden                      | 1         | 1      | 0.29%   |
| FZ                          | 1         | 1      | 0.29%   |
| Eluktro                     | 1         | 1      | 0.29%   |
| CARLSTEIN                   | 1         | 4      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 12        | 3.36%   |
| Seagate ST500LT012-9WS142 500GB                   | 7         | 1.96%   |
| HGST HTS725050A7E630 500GB                        | 7         | 1.96%   |
| Toshiba MQ04ABF100 1TB                            | 6         | 1.68%   |
| Seagate ST9500325AS 500GB                         | 6         | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 1.68%   |
| Unknown MMC Card  64GB                            | 5         | 1.4%    |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.4%    |
| Samsung NVMe SSD Drive 512GB                      | 5         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5         | 1.4%    |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.12%   |
| Seagate ST500LT012-1DG142 500GB                   | 4         | 1.12%   |
| Seagate ST500LM021-1KJ152 500GB                   | 4         | 1.12%   |
| Samsung SSD 960 EVO 1TB                           | 4         | 1.12%   |
| Unknown                                           | 4         | 1.12%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 3         | 0.84%   |
| WDC WD3200AAJS-56M0A0 320GB                       | 3         | 0.84%   |
| WDC PC SN730 NVMe 512GB                           | 3         | 0.84%   |
| Unknown MMC Card  32GB                            | 3         | 0.84%   |
| SPCC M.2 PCIe SSD 512GB                           | 3         | 0.84%   |
| Seagate ST500DM002-1BD142 500GB                   | 3         | 0.84%   |
| MARSHAL MAL2500SA-T54L 500GB                      | 3         | 0.84%   |
| HGST HTS541010A9E680 1TB                          | 3         | 0.84%   |
| Crucial CT2050MX300SSD1 2TB                       | 3         | 0.84%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.56%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 2         | 0.56%   |
| WDC WD2500BEKT-75PVMT0 250GB                      | 2         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.56%   |
| Unknown NCard  32GB                               | 2         | 0.56%   |
| Unknown MMC Card                                  | 2         | 0.56%   |
| Toshiba MQ01ABD050V 497GB                         | 2         | 0.56%   |
| Toshiba DT01ACA100 1TB                            | 2         | 0.56%   |
| Team T253X2001T 1TB SSD                           | 2         | 0.56%   |
| SPCC Solid State Disk 256GB                       | 2         | 0.56%   |
| Seagate ST500VT000-1DK142 500GB                   | 2         | 0.56%   |
| Seagate ST500VT000-1BS142 500GB                   | 2         | 0.56%   |
| Seagate ST500LM030-1RK17D 500GB                   | 2         | 0.56%   |
| Seagate ST3320418AS 320GB                         | 2         | 0.56%   |
| Seagate ST3250318AS 250GB                         | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 107    | 41.88%  |
| WDC                 | 37        | 46     | 19.37%  |
| Toshiba             | 31        | 36     | 16.23%  |
| HGST                | 20        | 32     | 10.47%  |
| Hitachi             | 12        | 15     | 6.28%   |
| MARSHAL             | 5         | 5      | 2.62%   |
| Samsung Electronics | 2         | 2      | 1.05%   |
| Maxtor              | 2         | 2      | 1.05%   |
| Unknown             | 1         | 1      | 0.52%   |
| Unknown             | 1         | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 18     | 17.65%  |
| SanDisk             | 10        | 11     | 14.71%  |
| Crucial             | 6         | 8      | 8.82%   |
| Micron Technology   | 4         | 5      | 5.88%   |
| WDC                 | 3         | 4      | 4.41%   |
| Lexar               | 3         | 3      | 4.41%   |
| Kingston            | 3         | 5      | 4.41%   |
| Intel               | 3         | 3      | 4.41%   |
| Toshiba             | 2         | 2      | 2.94%   |
| Team                | 2         | 2      | 2.94%   |
| SPCC                | 2         | 3      | 2.94%   |
| LITEON              | 2         | 2      | 2.94%   |
| China               | 2         | 2      | 2.94%   |
| Unknown             | 2         | 2      | 2.94%   |
| TCSUNBOW            | 1         | 1      | 1.47%   |
| SK hynix            | 1         | 1      | 1.47%   |
| Plextor             | 1         | 1      | 1.47%   |
| Netac               | 1         | 1      | 1.47%   |
| MAX                 | 1         | 1      | 1.47%   |
| LITEONIT            | 1         | 1      | 1.47%   |
| KINGBANK            | 1         | 1      | 1.47%   |
| Golden              | 1         | 1      | 1.47%   |
| FZ                  | 1         | 1      | 1.47%   |
| Eluktro             | 1         | 1      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |
| A-DATA Technology   | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 172       | 247    | 53.58%  |
| SSD     | 64        | 82     | 19.94%  |
| NVMe    | 62        | 82     | 19.31%  |
| MMC     | 18        | 24     | 5.61%   |
| Unknown | 5         | 8      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 218       | 332    | 71.95%  |
| NVMe | 62        | 82     | 20.46%  |
| MMC  | 18        | 24     | 5.94%   |
| SAS  | 5         | 5      | 1.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 224    | 67.93%  |
| 0.51-1.0   | 61        | 78     | 25.74%  |
| 1.01-2.0   | 10        | 18     | 4.22%   |
| 3.01-4.0   | 2         | 5      | 0.84%   |
| 4.01-10.0  | 2         | 3      | 0.84%   |
| 2.01-3.0   | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 25.93%  |
| 101-250        | 71        | 23.91%  |
| 501-1000       | 49        | 16.5%   |
| 51-100         | 29        | 9.76%   |
| 1001-2000      | 22        | 7.41%   |
| Unknown        | 13        | 4.38%   |
| 1-20           | 12        | 4.04%   |
| More than 3000 | 8         | 2.69%   |
| 21-50          | 8         | 2.69%   |
| 2001-3000      | 8         | 2.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 81        | 26.64%  |
| 101-250        | 52        | 17.11%  |
| 21-50          | 51        | 16.78%  |
| 51-100         | 45        | 14.8%   |
| 251-500        | 32        | 10.53%  |
| 501-1000       | 15        | 4.93%   |
| Unknown        | 13        | 4.28%   |
| 1001-2000      | 10        | 3.29%   |
| More than 3000 | 4         | 1.32%   |
| 2001-3000      | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 7.32%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD050V 497GB             | 2         | 2      | 4.88%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 4.88%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 4.88%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 4.88%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 2.44%   |
| WDC WD5000AZLX-08K2TA0 500GB          | 1         | 1      | 2.44%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 2.44%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.44%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 2.44%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 2.44%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 2.44%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.44%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.44%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.44%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 2.44%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 2.44%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.44%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 2.44%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 2.44%   |
| HGST HTS721010A9 1TB                  | 1         | 2      | 2.44%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.44%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 2.44%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 2.44%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 2.44%   |
| Unknown                               | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 13        | 13     | 32.5%   |
| Toshiba  | 8         | 8      | 20%     |
| WDC      | 6         | 6      | 15%     |
| HGST     | 6         | 10     | 15%     |
| MARSHAL  | 2         | 2      | 5%      |
| Hitachi  | 2         | 3      | 5%      |
| SK hynix | 1         | 1      | 2.5%    |
| Crucial  | 1         | 2      | 2.5%    |
| Unknown  | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 13     | 34.21%  |
| Toshiba | 8         | 8      | 21.05%  |
| WDC     | 6         | 6      | 15.79%  |
| HGST    | 6         | 10     | 15.79%  |
| MARSHAL | 2         | 2      | 5.26%   |
| Hitachi | 2         | 3      | 5.26%   |
| Unknown | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 43     | 94.87%  |
| SSD  | 2         | 3      | 5.13%   |

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
| Detected | 166       | 246    | 56.46%  |
| Works    | 90        | 151    | 30.61%  |
| Malfunc  | 38        | 46     | 12.93%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 230       | 73.72%  |
| Samsung Electronics          | 27        | 8.65%   |
| AMD                          | 16        | 5.13%   |
| SanDisk                      | 10        | 3.21%   |
| Toshiba America Info Systems | 4         | 1.28%   |
| SK hynix                     | 3         | 0.96%   |
| Silicon Motion               | 3         | 0.96%   |
| Shenzhen Longsys Electronics | 2         | 0.64%   |
| Micron Technology            | 2         | 0.64%   |
| LSI Logic / Symbios Logic    | 2         | 0.64%   |
| ASMedia Technology           | 2         | 0.64%   |
| Union Memory (Shenzhen)      | 1         | 0.32%   |
| Realtek Semiconductor        | 1         | 0.32%   |
| Micron/Crucial Technology    | 1         | 0.32%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.32%   |
| Marvell Technology Group     | 1         | 0.32%   |
| Lite-On Technology           | 1         | 0.32%   |
| Kingston Technology Company  | 1         | 0.32%   |
| JMicron Technology           | 1         | 0.32%   |
| Broadcom / LSI               | 1         | 0.32%   |
| Apple                        | 1         | 0.32%   |
| ADATA Technology             | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 35        | 10.23%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 6.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 4.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 4.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 4.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 3.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.34%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 1.46%   |
| Intel SATA Controller [RAID mode]                                                | 5         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.17%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.58%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.58%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 200       | 62.5%   |
| NVMe | 62        | 19.38%  |
| RAID | 31        | 9.69%   |
| IDE  | 26        | 8.13%   |
| SCSI | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 256       | 91.43%  |
| AMD    | 22        | 7.86%   |
| ARM    | 2         | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 2.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 2.14%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 2.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 6         | 2.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.14%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 6         | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 4         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.43%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.07%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.07%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.07%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.07%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.07%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.07%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 1.07%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.07%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.07%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.07%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.71%   |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.71%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.71%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 0.71%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.71%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 86        | 30.71%  |
| Intel Core i7           | 65        | 23.21%  |
| Intel Core i3           | 27        | 9.64%   |
| Intel Celeron           | 20        | 7.14%   |
| Other                   | 16        | 5.71%   |
| Intel Atom              | 9         | 3.21%   |
| Intel Core 2 Duo        | 7         | 2.5%    |
| AMD Ryzen 7             | 7         | 2.5%    |
| AMD Ryzen 5             | 6         | 2.14%   |
| Intel Pentium           | 5         | 1.79%   |
| Intel Xeon              | 4         | 1.43%   |
| Intel Pentium 4         | 4         | 1.43%   |
| Intel Pentium Dual-Core | 3         | 1.07%   |
| Intel Core i9           | 3         | 1.07%   |
| Intel Core 2            | 3         | 1.07%   |
| Intel Core 2 Quad       | 2         | 0.71%   |
| AMD FX                  | 2         | 0.71%   |
| AMD A10                 | 2         | 0.71%   |
| Intel Pentium Dual      | 1         | 0.36%   |
| Intel Genuine           | 1         | 0.36%   |
| Intel Core m3           | 1         | 0.36%   |
| ARM AArch64             | 1         | 0.36%   |
| AMD Ryzen Threadripper  | 1         | 0.36%   |
| AMD Ryzen 9             | 1         | 0.36%   |
| AMD Phenom II X3        | 1         | 0.36%   |
| AMD E2                  | 1         | 0.36%   |
| AMD A4                  | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 161       | 57.5%   |
| 4       | 79        | 28.21%  |
| 6       | 12        | 4.29%   |
| 8       | 10        | 3.57%   |
| 1       | 7         | 2.5%    |
| 3       | 3         | 1.07%   |
| 10      | 2         | 0.71%   |
| 32      | 1         | 0.36%   |
| 20      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |
| 14      | 1         | 0.36%   |
| 12      | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 278       | 99.29%  |
| 2      | 2         | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 214       | 76.43%  |
| 1       | 65        | 23.21%  |
| Unknown | 1         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 277       | 98.93%  |
| 32-bit         | 2         | 0.71%   |
| Unknown        | 1         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 29.15%  |
| 0x306a9    | 26        | 8.81%   |
| 0x206a7    | 20        | 6.78%   |
| 0x40651    | 15        | 5.08%   |
| 0x406e3    | 14        | 4.75%   |
| 0x306c3    | 11        | 3.73%   |
| 0x806ea    | 8         | 2.71%   |
| 0x806c1    | 8         | 2.71%   |
| 0x306d4    | 8         | 2.71%   |
| 0x806ec    | 7         | 2.37%   |
| 0x906ea    | 6         | 2.03%   |
| 0x30678    | 6         | 2.03%   |
| 0x20655    | 6         | 2.03%   |
| 0x1067a    | 6         | 2.03%   |
| 0x706e5    | 4         | 1.36%   |
| 0x506e3    | 4         | 1.36%   |
| 0x406c4    | 4         | 1.36%   |
| 0x806e9    | 3         | 1.02%   |
| 0x706a8    | 3         | 1.02%   |
| 0x0800820d | 3         | 1.02%   |
| 0x906e9    | 2         | 0.68%   |
| 0x806eb    | 2         | 0.68%   |
| 0x706a1    | 2         | 0.68%   |
| 0x6fd      | 2         | 0.68%   |
| 0x6f6      | 2         | 0.68%   |
| 0x406c3    | 2         | 0.68%   |
| 0x106c2    | 2         | 0.68%   |
| 0x10676    | 2         | 0.68%   |
| 0x08608103 | 2         | 0.68%   |
| 0x08600106 | 2         | 0.68%   |
| 0xf65      | 1         | 0.34%   |
| 0xf49      | 1         | 0.34%   |
| 0xf43      | 1         | 0.34%   |
| 0xa0652    | 1         | 0.34%   |
| 0x906ec    | 1         | 0.34%   |
| 0x906a4    | 1         | 0.34%   |
| 0x90661    | 1         | 0.34%   |
| 0x806c2    | 1         | 0.34%   |
| 0x6fa      | 1         | 0.34%   |
| 0x6f7      | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 16.07%  |
| Haswell          | 39        | 13.93%  |
| Skylake          | 28        | 10%     |
| IvyBridge        | 27        | 9.64%   |
| SandyBridge      | 22        | 7.86%   |
| Silvermont       | 16        | 5.71%   |
| Broadwell        | 13        | 4.64%   |
| Westmere         | 11        | 3.93%   |
| TigerLake        | 10        | 3.57%   |
| Penryn           | 8         | 2.86%   |
| IceLake          | 8         | 2.86%   |
| Core             | 8         | 2.86%   |
| Zen+             | 6         | 2.14%   |
| Zen 2            | 5         | 1.79%   |
| Goldmont plus    | 5         | 1.79%   |
| NetBurst         | 4         | 1.43%   |
| Alderlake Hybrid | 4         | 1.43%   |
| Unknown          | 4         | 1.43%   |
| Goldmont         | 3         | 1.07%   |
| Zen 3            | 2         | 0.71%   |
| Piledriver       | 2         | 0.71%   |
| Excavator        | 2         | 0.71%   |
| Bonnell          | 2         | 0.71%   |
| Tremont          | 1         | 0.36%   |
| Steamroller      | 1         | 0.36%   |
| P6               | 1         | 0.36%   |
| K10              | 1         | 0.36%   |
| CometLake        | 1         | 0.36%   |
| Bobcat           | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 233       | 74.68%  |
| Nvidia                     | 39        | 12.5%   |
| AMD                        | 39        | 12.5%   |
| Matrox Electronics Systems | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 6.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 6.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.27%   |
| Intel HD Graphics 5500                                                                   | 13        | 4.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 3.76%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 3.13%   |
| Intel HD Graphics 620                                                                    | 9         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.19%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.25%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.94%   |
| Intel HD Graphics 530                                                                    | 3         | 0.94%   |
| Intel HD Graphics 500                                                                    | 3         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.63%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.63%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 200       | 70.92%  |
| 1 x AMD        | 26        | 9.22%   |
| 1 x Nvidia     | 21        | 7.45%   |
| Intel + Nvidia | 17        | 6.03%   |
| Intel + AMD    | 12        | 4.26%   |
| Other          | 2         | 0.71%   |
| 2 x Intel      | 2         | 0.71%   |
| 2 x AMD        | 1         | 0.35%   |
| 1 x Matrox     | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 263       | 93.26%  |
| Proprietary | 15        | 5.32%   |
| Unknown     | 4         | 1.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 77.46%  |
| 1.01-2.0   | 21        | 7.39%   |
| 0.01-0.5   | 17        | 5.99%   |
| 3.01-4.0   | 9         | 3.17%   |
| 0.51-1.0   | 8         | 2.82%   |
| 7.01-8.0   | 7         | 2.46%   |
| 5.01-6.0   | 1         | 0.35%   |
| 8.01-16.0  | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 20.89%  |
| Chimei Innolux          | 41        | 14.04%  |
| LG Display              | 34        | 11.64%  |
| BOE                     | 33        | 11.3%   |
| Hewlett-Packard         | 26        | 8.9%    |
| Samsung Electronics     | 24        | 8.22%   |
| Dell                    | 14        | 4.79%   |
| InfoVision              | 7         | 2.4%    |
| Sharp                   | 6         | 2.05%   |
| Sony                    | 5         | 1.71%   |
| Lenovo                  | 5         | 1.71%   |
| Chi Mei Optoelectronics | 4         | 1.37%   |
| Apple                   | 4         | 1.37%   |
| LG Philips              | 3         | 1.03%   |
| KDC                     | 3         | 1.03%   |
| HannStar                | 3         | 1.03%   |
| Unknown (XXX)           | 2         | 0.68%   |
| NEC Computers           | 2         | 0.68%   |
| CSO                     | 2         | 0.68%   |
| BenQ                    | 2         | 0.68%   |
| Acer                    | 2         | 0.68%   |
| VIE                     | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| Sceptre Tech            | 1         | 0.34%   |
| S2-Tek                  | 1         | 0.34%   |
| Planar                  | 1         | 0.34%   |
| Hitachi                 | 1         | 0.34%   |
| Eizo                    | 1         | 0.34%   |
| CVT                     | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 5         | 1.69%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.36%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.02%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 1.02%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.02%   |
| Sony TV SNY6F02 1360x768                                                 | 2         | 0.68%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch        | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.68%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 2         | 0.68%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 2         | 0.68%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                     | 2         | 0.68%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.68%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch               | 2         | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.68%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                         | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch          | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.68%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.68%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.68%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.68%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                    | 1         | 0.34%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080    | 1         | 0.34%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.34%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.34%   |
| Sony TV SNYEF03 1600x900                                                 | 1         | 0.34%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                            | 1         | 0.34%   |
| Sony TV SNY0902 1920x1080                                                | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 107       | 37.81%  |
| 1920x1080 (FHD)    | 93        | 32.86%  |
| 1600x900 (HD+)     | 20        | 7.07%   |
| 1280x1024 (SXGA)   | 10        | 3.53%   |
| 3840x2160 (4K)     | 9         | 3.18%   |
| 1920x1200 (WUXGA)  | 6         | 2.12%   |
| 1440x900 (WXGA+)   | 6         | 2.12%   |
| 1280x800 (WXGA)    | 6         | 2.12%   |
| 2560x1440 (QHD)    | 4         | 1.41%   |
| 1680x1050 (WSXGA+) | 3         | 1.06%   |
| 1360x768           | 3         | 1.06%   |
| 1024x768 (XGA)     | 2         | 0.71%   |
| 1024x600           | 2         | 0.71%   |
| Unknown            | 2         | 0.71%   |
| 3840x2400          | 1         | 0.35%   |
| 3440x1440          | 1         | 0.35%   |
| 3200x1800 (QHD+)   | 1         | 0.35%   |
| 3200x1080          | 1         | 0.35%   |
| 3072x1920          | 1         | 0.35%   |
| 2560x1600          | 1         | 0.35%   |
| 2560x1080          | 1         | 0.35%   |
| 2160x1440          | 1         | 0.35%   |
| 1920x1280          | 1         | 0.35%   |
| 1600x1200          | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 28.97%  |
| 13      | 56        | 19.31%  |
| 14      | 50        | 17.24%  |
| 21      | 10        | 3.45%   |
| 12      | 10        | 3.45%   |
| 17      | 9         | 3.1%    |
| 11      | 9         | 3.1%    |
| 19      | 8         | 2.76%   |
| 23      | 7         | 2.41%   |
| 27      | 6         | 2.07%   |
| 24      | 6         | 2.07%   |
| 18      | 6         | 2.07%   |
| 72      | 4         | 1.38%   |
| 22      | 3         | 1.03%   |
| 20      | 3         | 1.03%   |
| 10      | 3         | 1.03%   |
| Unknown | 3         | 1.03%   |
| 84      | 2         | 0.69%   |
| 46      | 2         | 0.69%   |
| 34      | 2         | 0.69%   |
| 16      | 2         | 0.69%   |
| 54      | 1         | 0.34%   |
| 42      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 31      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 168       | 58.74%  |
| 201-300     | 48        | 16.78%  |
| 501-600     | 20        | 6.99%   |
| 401-500     | 20        | 6.99%   |
| 351-400     | 13        | 4.55%   |
| 1501-2000   | 6         | 2.1%    |
| Unknown     | 3         | 1.05%   |
| 801-900     | 2         | 0.7%    |
| 1001-1500   | 2         | 0.7%    |
| 901-1000    | 2         | 0.7%    |
| 701-800     | 1         | 0.35%   |
| 601-700     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 227       | 82.55%  |
| 16/10   | 29        | 10.55%  |
| 5/4     | 10        | 3.64%   |
| Unknown | 3         | 1.09%   |
| 4/3     | 2         | 0.73%   |
| 3/2     | 2         | 0.73%   |
| 21/9    | 2         | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 28.82%  |
| 81-90          | 81        | 28.13%  |
| 71-80          | 25        | 8.68%   |
| 201-250        | 18        | 6.25%   |
| 151-200        | 14        | 4.86%   |
| 61-70          | 10        | 3.47%   |
| 141-150        | 10        | 3.47%   |
| 51-60          | 9         | 3.13%   |
| More than 1000 | 7         | 2.43%   |
| 301-350        | 6         | 2.08%   |
| 251-300        | 5         | 1.74%   |
| 501-1000       | 4         | 1.39%   |
| 351-500        | 3         | 1.04%   |
| 41-50          | 3         | 1.04%   |
| 121-130        | 3         | 1.04%   |
| Unknown        | 3         | 1.04%   |
| 111-120        | 2         | 0.69%   |
| 131-140        | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 95        | 33.69%  |
| 121-160       | 94        | 33.33%  |
| 51-100        | 55        | 19.5%   |
| 161-240       | 21        | 7.45%   |
| More than 240 | 7         | 2.48%   |
| 1-50          | 7         | 2.48%   |
| Unknown       | 3         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 239       | 83.28%  |
| 2     | 38        | 13.24%  |
| 0     | 9         | 3.14%   |
| 3     | 1         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 172       | 40.86%  |
| Realtek Semiconductor             | 114       | 27.08%  |
| Qualcomm Atheros                  | 46        | 10.93%  |
| Broadcom                          | 25        | 5.94%   |
| MediaTek                          | 9         | 2.14%   |
| Hewlett-Packard                   | 8         | 1.9%    |
| Samsung Electronics               | 6         | 1.43%   |
| Broadcom Limited                  | 6         | 1.43%   |
| Ralink                            | 4         | 0.95%   |
| OPPO Electronics                  | 4         | 0.95%   |
| Huawei Technologies               | 4         | 0.95%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.71%   |
| Xiaomi                            | 3         | 0.71%   |
| Sierra Wireless                   | 3         | 0.71%   |
| Ralink Technology                 | 3         | 0.71%   |
| Marvell Technology Group          | 3         | 0.71%   |
| T & A Mobile Phones               | 2         | 0.48%   |
| Ericsson Business Mobile Networks | 2         | 0.48%   |
| Spreadtrum Communications         | 1         | 0.24%   |
| Qualcomm                          | 1         | 0.24%   |
| LSI                               | 1         | 0.24%   |
| IBM                               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 12.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 4.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.16%   |
| Intel Wireless 7260                                               | 21        | 3.97%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 3.02%   |
| Intel Wireless 8260                                               | 14        | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 2.46%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 2.46%   |
| Intel Wireless 8265 / 8275                                        | 12        | 2.27%   |
| Intel Wireless 7265                                               | 12        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.51%   |
| MediaTek Wiko U316AT                                              | 8         | 1.51%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.51%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.95%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.76%   |
| OPPO RMX2027                                                      | 4         | 0.76%   |
| Intel Wireless 3160                                               | 4         | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.76%   |
| HP lt4112 Gobi 4G Module Network Device                           | 4         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.76%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 3         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 139       | 53.67%  |
| Realtek Semiconductor             | 44        | 16.99%  |
| Qualcomm Atheros                  | 40        | 15.44%  |
| Broadcom                          | 19        | 7.34%   |
| Hewlett-Packard                   | 5         | 1.93%   |
| Ralink                            | 4         | 1.54%   |
| Sierra Wireless                   | 3         | 1.16%   |
| Ralink Technology                 | 3         | 1.16%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |
| Broadcom Limited                  | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 21        | 8.11%   |
| Intel Wireless 8260                                            | 14        | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 5.02%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.63%   |
| Intel Wireless 7265                                            | 12        | 4.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 4.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 3.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.47%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 3.09%   |
| Intel Wi-Fi 6 AX200                                            | 8         | 3.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 3.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 2.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 6         | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 2.32%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.54%   |
| Intel Wireless 3160                                            | 4         | 1.54%   |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.54%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.16%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.16%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.77%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.77%   |
| Intel Wireless-AC 9260                                         | 2         | 0.77%   |
| Intel Wireless 3165                                            | 2         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 110       | 41.67%  |
| Realtek Semiconductor      | 94        | 35.61%  |
| Qualcomm Atheros           | 9         | 3.41%   |
| MediaTek                   | 9         | 3.41%   |
| Broadcom                   | 7         | 2.65%   |
| Samsung Electronics        | 6         | 2.27%   |
| Broadcom Limited           | 5         | 1.89%   |
| OPPO Electronics           | 4         | 1.52%   |
| ZTE WCDMA Technologies MSM | 3         | 1.14%   |
| Xiaomi                     | 3         | 1.14%   |
| Marvell Technology Group   | 3         | 1.14%   |
| Hewlett-Packard            | 3         | 1.14%   |
| T & A Mobile Phones        | 2         | 0.76%   |
| Huawei Technologies        | 2         | 0.76%   |
| Spreadtrum Communications  | 1         | 0.38%   |
| Qualcomm                   | 1         | 0.38%   |
| LSI                        | 1         | 0.38%   |
| IBM                        | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 23.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 9.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 8.24%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 5.99%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 4.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3%      |
| MediaTek Wiko U316AT                                              | 8         | 3%      |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.25%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.87%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.87%   |
| OPPO RMX2027                                                      | 4         | 1.5%    |
| Intel Ethernet Connection I217-V                                  | 4         | 1.5%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.5%    |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 3         | 1.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.75%   |
| T & A Mobile Phones Alcatel 1                                     | 2         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.75%   |
| MediaTek RMX3085                                                  | 2         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.75%   |
| Huawei E353/E3131                                                 | 2         | 0.75%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.75%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| Spreadtrum meizu C9                                               | 1         | 0.37%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 245       | 51.15%  |
| Ethernet | 231       | 48.23%  |
| Modem    | 3         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 72.95%  |
| Ethernet | 76        | 27.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 176       | 62.63%  |
| 1     | 89        | 31.67%  |
| 0     | 11        | 3.91%   |
| 3     | 3         | 1.07%   |
| 6     | 1         | 0.36%   |
| 4     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 273       | 97.5%   |
| Yes  | 7         | 2.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 58.55%  |
| Qualcomm Atheros Communications | 23        | 11.92%  |
| Realtek Semiconductor           | 17        | 8.81%   |
| Broadcom                        | 12        | 6.22%   |
| IMC Networks                    | 4         | 2.07%   |
| Hewlett-Packard                 | 4         | 2.07%   |
| Ralink                          | 3         | 1.55%   |
| Lite-On Technology              | 3         | 1.55%   |
| Cambridge Silicon Radio         | 3         | 1.55%   |
| Toshiba                         | 2         | 1.04%   |
| Dell                            | 2         | 1.04%   |
| Apple                           | 2         | 1.04%   |
| Taiyo Yuden                     | 1         | 0.52%   |
| Realtek                         | 1         | 0.52%   |
| Foxconn / Hon Hai               | 1         | 0.52%   |
| Alps Electric                   | 1         | 0.52%   |
| Unknown                         | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 32.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 7.25%   |
| Intel AX201 Bluetooth                               | 13        | 6.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 6.22%   |
| Realtek Bluetooth Radio                             | 11        | 5.7%    |
| Intel AX200 Bluetooth                               | 8         | 4.15%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.59%   |
| Intel Bluetooth Device                              | 5         | 2.59%   |
| Broadcom HP Portable SoftSailing                    | 5         | 2.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.07%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.55%   |
| IMC Networks Bluetooth Device                       | 3         | 1.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.55%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.04%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.04%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.52%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.52%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.52%   |
| Realtek Bluetooth Radio                             | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.52%   |
| Lite-On Bluetooth Device                            | 1         | 0.52%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.52%   |
| Intel AX210 Bluetooth                               | 1         | 0.52%   |
| IMC Networks Bluetooth                              | 1         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.52%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 246       | 77.36%  |
| AMD                         | 29        | 9.12%   |
| Nvidia                      | 23        | 7.23%   |
| Texas Instruments           | 3         | 0.94%   |
| Generalplus Technology      | 3         | 0.94%   |
| Realtek Semiconductor       | 2         | 0.63%   |
| Lenovo                      | 2         | 0.63%   |
| C-Media Electronics         | 2         | 0.63%   |
| Turtle Beach                | 1         | 0.31%   |
| Micro Star International    | 1         | 0.31%   |
| Medeli Electronics          | 1         | 0.31%   |
| JMTek                       | 1         | 0.31%   |
| GN Netcom                   | 1         | 0.31%   |
| Giga-Byte Technology        | 1         | 0.31%   |
| FiiO Electronics Technology | 1         | 0.31%   |
| Apple                       | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 46        | 12.01%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 6.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 5.74%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 4.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 3.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.31%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.78%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.78%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.78%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.52%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.52%   |
| Lenovo T2224zD                                                                                    | 2         | 0.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.52%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 30.46%  |
| SK hynix            | 50        | 25.38%  |
| Micron Technology   | 23        | 11.68%  |
| Kingston            | 14        | 7.11%   |
| Unknown             | 12        | 6.09%   |
| Crucial             | 10        | 5.08%   |
| Elpida              | 7         | 3.55%   |
| Ramaxel Technology  | 5         | 2.54%   |
| A-DATA Technology   | 3         | 1.52%   |
| G.Skill             | 2         | 1.02%   |
| Apacer              | 2         | 1.02%   |
| TwinMOS             | 1         | 0.51%   |
| Timetec             | 1         | 0.51%   |
| Team                | 1         | 0.51%   |
| Qimonda             | 1         | 0.51%   |
| Patriot             | 1         | 0.51%   |
| Nanya Technology    | 1         | 0.51%   |
| Corsair             | 1         | 0.51%   |
| Avant               | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 3.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 3.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.96%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 4         | 1.96%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 1.47%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 3         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 1.47%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 0.98%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.98%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.98%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.98%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s     | 2         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.98%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.98%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 2         | 0.98%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.98%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 2         | 0.98%   |
| Apacer RAM 76.A302G.C4D0B 2GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.49%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s             | 1         | 0.49%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s          | 1         | 0.49%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 70        | 46.36%  |
| DDR4   | 58        | 38.41%  |
| LPDDR4 | 6         | 3.97%   |
| DDR2   | 6         | 3.97%   |
| LPDDR3 | 5         | 3.31%   |
| SDRAM  | 3         | 1.99%   |
| DDR5   | 2         | 1.32%   |
| DDR    | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 74.05%  |
| Row Of Chips | 19        | 12.03%  |
| DIMM         | 16        | 10.13%  |
| Chip         | 6         | 3.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 39.88%  |
| 8192  | 49        | 28.32%  |
| 2048  | 23        | 13.29%  |
| 16384 | 21        | 12.14%  |
| 1024  | 6         | 3.47%   |
| 32768 | 4         | 2.31%   |
| 512   | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 33.73%  |
| 2667    | 31        | 18.34%  |
| 3200    | 15        | 8.88%   |
| 2133    | 11        | 6.51%   |
| 1333    | 11        | 6.51%   |
| 1334    | 9         | 5.33%   |
| 4267    | 6         | 3.55%   |
| 2400    | 6         | 3.55%   |
| 1867    | 4         | 2.37%   |
| 667     | 3         | 1.78%   |
| 3600    | 2         | 1.18%   |
| 3266    | 2         | 1.18%   |
| 800     | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| 8400    | 1         | 0.59%   |
| 5800    | 1         | 0.59%   |
| 4800    | 1         | 0.59%   |
| 4199    | 1         | 0.59%   |
| 3800    | 1         | 0.59%   |
| 2666    | 1         | 0.59%   |
| 2000    | 1         | 0.59%   |
| 1067    | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP LaserJet M101-M106 | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 66        | 29.86%  |
| Cheng Uei Precision Industry (Foxlink) | 30        | 13.57%  |
| Lite-On Technology                     | 13        | 5.88%   |
| Sunplus Innovation Technology          | 12        | 5.43%   |
| Realtek Semiconductor                  | 12        | 5.43%   |
| IMC Networks                           | 11        | 4.98%   |
| Syntek                                 | 10        | 4.52%   |
| Microdia                               | 10        | 4.52%   |
| Bison Electronics                      | 10        | 4.52%   |
| Acer                                   | 9         | 4.07%   |
| Quanta                                 | 4         | 1.81%   |
| Apple                                  | 4         | 1.81%   |
| Silicon Motion                         | 3         | 1.36%   |
| Samsung Electronics                    | 3         | 1.36%   |
| Logitech                               | 3         | 1.36%   |
| Unknown                                | 2         | 0.9%    |
| Suyin                                  | 2         | 0.9%    |
| Ricoh                                  | 2         | 0.9%    |
| Luxvisions Innotech Limited            | 2         | 0.9%    |
| Importek                               | 2         | 0.9%    |
| Alcor Micro                            | 2         | 0.9%    |
| Z-Star Microelectronics                | 1         | 0.45%   |
| Xiaomi                                 | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| MacroSilicon                           | 1         | 0.45%   |
| LG Electronics                         | 1         | 0.45%   |
| icSpring                               | 1         | 0.45%   |
| DigiTech                               | 1         | 0.45%   |
| Cubeternet                             | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 14        | 6.28%   |
| Chicony HP HD Webcam                                                       | 8         | 3.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3.14%   |
| Syntek Integrated Camera                                                   | 6         | 2.69%   |
| Lite-On HP HD Camera                                                       | 6         | 2.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.69%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.24%   |
| Lite-On HP HD Webcam                                                       | 5         | 2.24%   |
| Chicony HP HD Camera                                                       | 5         | 2.24%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.79%   |
| Chicony HP HD Webcam [Fixed]                                               | 4         | 1.79%   |
| Chicony Chicony USB 2.0 Camera                                             | 4         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.79%   |
| Acer Integrated Camera                                                     | 4         | 1.79%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.35%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.35%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 1.35%   |
| Chicony HD Webcam                                                          | 3         | 1.35%   |
| Bison Integrated Camera                                                    | 3         | 1.35%   |
| Acer ThinkPad P50 Integrated Camera                                        | 3         | 1.35%   |
| Unknown USB Camera                                                         | 2         | 0.9%    |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.9%    |
| Syntek EasyCamera                                                          | 2         | 0.9%    |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.9%    |
| Sunplus HP Truevision Full HD                                              | 2         | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.9%    |
| Realtek Integrated Webcam                                                  | 2         | 0.9%    |
| Realtek FULL HD 1080P Webcam                                               | 2         | 0.9%    |
| Logitech Webcam C270                                                       | 2         | 0.9%    |
| Importek HP Webcam-50                                                      | 2         | 0.9%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 0.9%    |
| IMC Networks Integrated Camera                                             | 2         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.9%    |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.9%    |
| Chicony HP Webcam                                                          | 2         | 0.9%    |
| Chicony HP Truevision HD camera                                            | 2         | 0.9%    |
| Chicony HP Truevision HD                                                   | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 51        | 68%     |
| Synaptics                  | 14        | 18.67%  |
| Shenzhen Goodix Technology | 6         | 8%      |
| AuthenTec                  | 2         | 2.67%   |
| LighTuning Technology      | 1         | 1.33%   |
| Elan Microelectronics      | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 24%     |
| Validity Sensors VFS491                                                    | 9         | 12%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 5.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 5.33%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 3         | 4%      |
| Synaptics WBDI Device                                                      | 3         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 2.67%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.33%   |
| Synaptics UWP WBDI                                                         | 1         | 1.33%   |
| Synaptics  WBDI                                                            | 1         | 1.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.33%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 45.45%  |
| Alcor Micro | 3         | 27.27%  |
| Upek        | 2         | 18.18%  |
| O2 Micro    | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 27.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 177       | 62.54%  |
| 1     | 87        | 30.74%  |
| 2     | 17        | 6.01%   |
| 3     | 2         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 74        | 58.27%  |
| Graphics card            | 13        | 10.24%  |
| Chipcard                 | 10        | 7.87%   |
| Net/wireless             | 7         | 5.51%   |
| Net/ethernet             | 4         | 3.15%   |
| Multimedia controller    | 4         | 3.15%   |
| Camera                   | 4         | 3.15%   |
| Storage                  | 3         | 2.36%   |
| Communication controller | 3         | 2.36%   |
| Bluetooth                | 3         | 2.36%   |
| Unassigned class         | 1         | 0.79%   |
| Sound                    | 1         | 0.79%   |


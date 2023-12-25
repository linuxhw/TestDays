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

Total: 424

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 0968h                       | Desktop     | [b1fb94198e](https://linux-hardware.org/?probe=b1fb94198e) | Dec 10, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [a1a93224e4](https://linux-hardware.org/?probe=a1a93224e4) | Dec 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [d24b2b8298](https://linux-hardware.org/?probe=d24b2b8298) | Nov 28, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [17b5d35090](https://linux-hardware.org/?probe=17b5d35090) | Nov 19, 2023 |
| Dell          | Latitude 5300               | Notebook    | [8f1ed5747c](https://linux-hardware.org/?probe=8f1ed5747c) | Nov 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| Dell          | Latitude 3380               | Notebook    | [f88c4741cc](https://linux-hardware.org/?probe=f88c4741cc) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
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
| Ubuntu 20.04                 | 46        | 14.56%  |
| Ubuntu 22.04                 | 31        | 9.81%   |
| Ubuntu 18.04                 | 19        | 6.01%   |
| Zorin 16                     | 8         | 2.53%   |
| Linux Mint 20.3              | 7         | 2.22%   |
| Fedora 36                    | 7         | 2.22%   |
| Arch Rolling                 | 7         | 2.22%   |
| Zorin 15                     | 6         | 1.9%    |
| Manjaro                      | 6         | 1.9%    |
| Fedora 38                    | 6         | 1.9%    |
| Ubuntu 23.04                 | 5         | 1.58%   |
| Pop!_OS 20.04                | 5         | 1.58%   |
| OpenMandriva 4.2             | 5         | 1.58%   |
| Arch                         | 5         | 1.58%   |
| Ubuntu 20.10                 | 4         | 1.27%   |
| Ubuntu 19.04                 | 4         | 1.27%   |
| Linux Mint 21                | 4         | 1.27%   |
| Fedora 37                    | 4         | 1.27%   |
| Debian 12                    | 4         | 1.27%   |
| Debian 11                    | 4         | 1.27%   |
| ArcoLinux Rolling            | 4         | 1.27%   |
| Ubuntu 21.10                 | 3         | 0.95%   |
| Ubuntu 21.04                 | 3         | 0.95%   |
| Q4OS 3                       | 3         | 0.95%   |
| Pop!_OS 22.04                | 3         | 0.95%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.95%   |
| Linux Mint 21.2              | 3         | 0.95%   |
| Linux Mint 20.2              | 3         | 0.95%   |
| Kali 2023.3                  | 3         | 0.95%   |
| Fedora 35                    | 3         | 0.95%   |
| Fedora 33                    | 3         | 0.95%   |
| Fedora 32                    | 3         | 0.95%   |
| Ubuntu 19.10                 | 2         | 0.63%   |
| Pop!_OS 20.10                | 2         | 0.63%   |
| Parrot 5.3                   | 2         | 0.63%   |
| Parrot 5.1                   | 2         | 0.63%   |
| OpenMandriva 4.3             | 2         | 0.63%   |
| Linux Mint 19                | 2         | 0.63%   |
| Kali 2023.2                  | 2         | 0.63%   |
| Kali 2022.3                  | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 113       | 38.18%  |
| Fedora        | 25        | 8.45%   |
| Linux Mint    | 19        | 6.42%   |
| Zorin         | 14        | 4.73%   |
| Arch          | 12        | 4.05%   |
| Endless       | 11        | 3.72%   |
| Pop!_OS       | 10        | 3.38%   |
| OpenMandriva  | 10        | 3.38%   |
| Manjaro       | 10        | 3.38%   |
| Kali          | 10        | 3.38%   |
| Debian        | 9         | 3.04%   |
| Parrot        | 8         | 2.7%    |
| Elementary    | 5         | 1.69%   |
| ArcoLinux     | 4         | 1.35%   |
| Q4OS          | 3         | 1.01%   |
| openSUSE      | 3         | 1.01%   |
| Ubuntu MATE   | 2         | 0.68%   |
| ROSA          | 2         | 0.68%   |
| RHEL          | 2         | 0.68%   |
| Lubuntu       | 2         | 0.68%   |
| KDE neon      | 2         | 0.68%   |
| Garuda Linux  | 2         | 0.68%   |
| Deepin        | 2         | 0.68%   |
| BlackPanther  | 2         | 0.68%   |
| Android       | 2         | 0.68%   |
| Xubuntu       | 1         | 0.34%   |
| Ubuntu Studio | 1         | 0.34%   |
| Ubuntu Budgie | 1         | 0.34%   |
| Rocky Linux   | 1         | 0.34%   |
| Nobara        | 1         | 0.34%   |
| Mageia        | 1         | 0.34%   |
| LMDE          | 1         | 0.34%   |
| Lilidog       | 1         | 0.34%   |
| CentOS        | 1         | 0.34%   |
| blendOS       | 1         | 0.34%   |
| antiX         | 1         | 0.34%   |
| Alpine        | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 1.77%   |
| 5.4.0-42-generic         | 5         | 1.47%   |
| 5.15.0-58-generic        | 5         | 1.47%   |
| 5.15.0-52-generic        | 5         | 1.47%   |
| 5.15.0-41-generic        | 5         | 1.47%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.47%   |
| 5.4.0-52-generic         | 4         | 1.18%   |
| 5.19.0-41-generic        | 4         | 1.18%   |
| 5.11.0-38-generic        | 4         | 1.18%   |
| 6.3.0-kali1-amd64        | 3         | 0.88%   |
| 6.2.0-32-generic         | 3         | 0.88%   |
| 5.8.0-43-generic         | 3         | 0.88%   |
| 5.4.0-58-generic         | 3         | 0.88%   |
| 5.4.0-45-generic         | 3         | 0.88%   |
| 5.4.0-37-generic         | 3         | 0.88%   |
| 5.4.0-137-generic        | 3         | 0.88%   |
| 5.3.0-28-generic         | 3         | 0.88%   |
| 5.19.0-38-generic        | 3         | 0.88%   |
| 5.19.0-35-generic        | 3         | 0.88%   |
| 5.15.0-53-generic        | 3         | 0.88%   |
| 4.19.0-17-amd64          | 3         | 0.88%   |
| 6.1.0-kali7-amd64        | 2         | 0.59%   |
| 5.9.13-200.fc33.x86_64   | 2         | 0.59%   |
| 5.8.4-200.fc32.x86_64    | 2         | 0.59%   |
| 5.8.0-63-generic         | 2         | 0.59%   |
| 5.8.0-59-generic         | 2         | 0.59%   |
| 5.8.0-55-generic         | 2         | 0.59%   |
| 5.8.0-50-generic         | 2         | 0.59%   |
| 5.4.0-67-generic         | 2         | 0.59%   |
| 5.4.0-65-generic         | 2         | 0.59%   |
| 5.4.0-54-generic         | 2         | 0.59%   |
| 5.4.0-48-generic         | 2         | 0.59%   |
| 5.4.0-47-generic         | 2         | 0.59%   |
| 5.4.0-33-generic         | 2         | 0.59%   |
| 5.4.0-19-generic         | 2         | 0.59%   |
| 5.3.0-62-generic         | 2         | 0.59%   |
| 5.19.9-200.fc36.x86_64   | 2         | 0.59%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.59%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.59%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 15.89%  |
| 5.15.0  | 29        | 9.03%   |
| 5.8.0   | 24        | 7.48%   |
| 5.11.0  | 17        | 5.3%    |
| 5.19.0  | 12        | 3.74%   |
| 5.13.0  | 12        | 3.74%   |
| 4.15.0  | 12        | 3.74%   |
| 5.3.0   | 10        | 3.12%   |
| 6.2.0   | 9         | 2.8%    |
| 6.1.0   | 9         | 2.8%    |
| 5.0.0   | 9         | 2.8%    |
| 5.10.0  | 6         | 1.87%   |
| 5.10.14 | 5         | 1.56%   |
| 5.18.0  | 4         | 1.25%   |
| 4.19.0  | 4         | 1.25%   |
| 4.18.0  | 4         | 1.25%   |
| 6.3.0   | 3         | 0.93%   |
| 5.19.9  | 3         | 0.93%   |
| 5.16.7  | 3         | 0.93%   |
| 5.14.0  | 3         | 0.93%   |
| 6.5.6   | 2         | 0.62%   |
| 6.5.0   | 2         | 0.62%   |
| 6.4.8   | 2         | 0.62%   |
| 6.3.4   | 2         | 0.62%   |
| 6.1.52  | 2         | 0.62%   |
| 5.9.13  | 2         | 0.62%   |
| 5.8.4   | 2         | 0.62%   |
| 5.18.13 | 2         | 0.62%   |
| 5.17.5  | 2         | 0.62%   |
| 5.13.19 | 2         | 0.62%   |
| 4.18.16 | 2         | 0.62%   |
| 6.5.7   | 1         | 0.31%   |
| 6.5.5   | 1         | 0.31%   |
| 6.5.2   | 1         | 0.31%   |
| 6.4.15  | 1         | 0.31%   |
| 6.4.14  | 1         | 0.31%   |
| 6.4.11  | 1         | 0.31%   |
| 6.3.8   | 1         | 0.31%   |
| 6.3.6   | 1         | 0.31%   |
| 6.3.5   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 16.04%  |
| 5.15    | 34        | 10.69%  |
| 5.8     | 27        | 8.49%   |
| 5.19    | 21        | 6.6%    |
| 5.11    | 18        | 5.66%   |
| 6.1     | 17        | 5.35%   |
| 5.10    | 15        | 4.72%   |
| 5.13    | 14        | 4.4%    |
| 6.2     | 13        | 4.09%   |
| 4.15    | 12        | 3.77%   |
| 5.3     | 10        | 3.14%   |
| 5.0     | 10        | 3.14%   |
| 6.3     | 8         | 2.52%   |
| 6.5     | 7         | 2.2%    |
| 5.16    | 7         | 2.2%    |
| 5.18    | 6         | 1.89%   |
| 5.14    | 6         | 1.89%   |
| 4.18    | 6         | 1.89%   |
| 6.4     | 5         | 1.57%   |
| 4.19    | 5         | 1.57%   |
| 6.0     | 3         | 0.94%   |
| 5.9     | 3         | 0.94%   |
| 5.6     | 3         | 0.94%   |
| 5.17    | 3         | 0.94%   |
| 4.9     | 3         | 0.94%   |
| 5.2     | 2         | 0.63%   |
| 5.12    | 2         | 0.63%   |
| 5.7     | 1         | 0.31%   |
| 5.5     | 1         | 0.31%   |
| 5.1     | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |
| 4.16    | 1         | 0.31%   |
| 4.13    | 1         | 0.31%   |
| 3.10    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 280       | 97.56%  |
| i686    | 5         | 1.74%   |
| armv8l  | 1         | 0.35%   |
| aarch64 | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 174       | 58.39%  |
| KDE5            | 33        | 11.07%  |
| Unknown         | 28        | 9.4%    |
| X-Cinnamon      | 17        | 5.7%    |
| XFCE            | 15        | 5.03%   |
| MATE            | 9         | 3.02%   |
| Pantheon        | 5         | 1.68%   |
| KDE             | 4         | 1.34%   |
| LXQt            | 2         | 0.67%   |
| KDE4            | 2         | 0.67%   |
| Cinnamon        | 2         | 0.67%   |
| awesome         | 2         | 0.67%   |
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
| X11     | 199       | 67%     |
| Wayland | 79        | 26.6%   |
| Unknown | 15        | 5.05%   |
| Tty     | 4         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 44.93%  |
| GDM3    | 48        | 16.22%  |
| GDM     | 39        | 13.18%  |
| SDDM    | 37        | 12.5%   |
| LightDM | 32        | 10.81%  |
| TDM     | 5         | 1.69%   |
| KDM     | 2         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 220       | 75.6%   |
| en_GB   | 33        | 11.34%  |
| Unknown | 30        | 10.31%  |
| C       | 7         | 2.41%   |
| en_AG   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 157       | 53.4%   |
| EFI  | 137       | 46.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 223       | 76.63%  |
| Btrfs   | 32        | 11%     |
| Overlay | 17        | 5.84%   |
| Tmpfs   | 10        | 3.44%   |
| Unknown | 5         | 1.72%   |
| Xfs     | 3         | 1.03%   |
| Zfs     | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 48.46%  |
| GPT     | 110       | 37.54%  |
| MBR     | 41        | 13.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 252       | 87.2%   |
| Yes       | 37        | 12.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 198       | 68.51%  |
| Yes       | 91        | 31.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 122       | 42.51%  |
| Lenovo                      | 55        | 19.16%  |
| Dell                        | 41        | 14.29%  |
| ASUSTek Computer            | 11        | 3.83%   |
| Toshiba                     | 8         | 2.79%   |
| MSI                         | 5         | 1.74%   |
| Acer                        | 5         | 1.74%   |
| Gigabyte Technology         | 4         | 1.39%   |
| Unknown                     | 4         | 1.39%   |
| Samsung Electronics         | 3         | 1.05%   |
| Apple                       | 3         | 1.05%   |
| Endless                     | 2         | 0.7%    |
| Chuwi                       | 2         | 0.7%    |
| ASRock                      | 2         | 0.7%    |
| TECNO                       | 1         | 0.35%   |
| Sony                        | 1         | 0.35%   |
| SLIMBOOK                    | 1         | 0.35%   |
| Panasonic                   | 1         | 0.35%   |
| Notebook                    | 1         | 0.35%   |
| LG Electronics              | 1         | 0.35%   |
| IP3 Tech                    | 1         | 0.35%   |
| Intel                       | 1         | 0.35%   |
| Insyde                      | 1         | 0.35%   |
| IBM                         | 1         | 0.35%   |
| I-Life Digital Technologies | 1         | 0.35%   |
| HUAWEI                      | 1         | 0.35%   |
| Getac                       | 1         | 0.35%   |
| Fujitsu                     | 1         | 0.35%   |
| Foxconn                     | 1         | 0.35%   |
| EVOC                        | 1         | 0.35%   |
| EUROCOM                     | 1         | 0.35%   |
| Eluktronics                 | 1         | 0.35%   |
| Clevo                       | 1         | 0.35%   |
| AMI                         | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| HP EliteBook 840 G1               | 7         | 2.44%   |
| Unknown                           | 6         | 2.09%   |
| HP EliteBook 840 G3               | 5         | 1.74%   |
| HP EliteBook Folio 9470m          | 4         | 1.39%   |
| Dell XPS 13 9310                  | 4         | 1.39%   |
| HP ProBook 4540s                  | 3         | 1.05%   |
| HP Notebook                       | 3         | 1.05%   |
| HP EliteBook Folio 9480m          | 3         | 1.05%   |
| HP EliteBook 8460p                | 3         | 1.05%   |
| HP EliteBook 2570p                | 3         | 1.05%   |
| HP 15                             | 3         | 1.05%   |
| Toshiba Satellite C660            | 2         | 0.7%    |
| MSI MS-7C02                       | 2         | 0.7%    |
| Lenovo IdeaPad S340-14IIL 81VV    | 2         | 0.7%    |
| Lenovo IdeaPad 3 14ITL6 82H7      | 2         | 0.7%    |
| Lenovo G50-80 80E5                | 2         | 0.7%    |
| HP Spectre x360 Convertible       | 2         | 0.7%    |
| HP ProBook 6560b                  | 2         | 0.7%    |
| HP ProBook 640 G1                 | 2         | 0.7%    |
| HP ProBook 440 G5                 | 2         | 0.7%    |
| HP Pavilion Laptop 15-cs3xxx      | 2         | 0.7%    |
| HP ENVY 15                        | 2         | 0.7%    |
| HP EliteBook 8440p                | 2         | 0.7%    |
| HP EliteBook 840 G2               | 2         | 0.7%    |
| HP Compaq Mini 110c-1100          | 2         | 0.7%    |
| HP 630                            | 2         | 0.7%    |
| HP 15 Notebook PC                 | 2         | 0.7%    |
| Endless EF20EA                    | 2         | 0.7%    |
| Dell OptiPlex 7010                | 2         | 0.7%    |
| Dell Latitude E6410               | 2         | 0.7%    |
| Dell Inspiron 5767                | 2         | 0.7%    |
| ASUS X540NA                       | 2         | 0.7%    |
| Toshiba TECRA A50-A               | 1         | 0.35%   |
| Toshiba Satellite L50-B           | 1         | 0.35%   |
| Toshiba Satellite C850D-B615      | 1         | 0.35%   |
| Toshiba R84SAU2                   | 1         | 0.35%   |
| Toshiba dynabook Satellite B554/M | 1         | 0.35%   |
| Toshiba dynabook R731/E           | 1         | 0.35%   |
| TECNO WinPad 2                    | 1         | 0.35%   |
| Sony VGN-NS295J                   | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 42        | 14.63%  |
| Lenovo ThinkPad        | 26        | 9.06%   |
| HP ProBook             | 19        | 6.62%   |
| Lenovo IdeaPad         | 14        | 4.88%   |
| Dell OptiPlex          | 12        | 4.18%   |
| Dell Latitude          | 12        | 4.18%   |
| HP Compaq              | 11        | 3.83%   |
| HP Pavilion            | 10        | 3.48%   |
| HP ENVY                | 9         | 3.14%   |
| Dell Inspiron          | 9         | 3.14%   |
| Dell XPS               | 6         | 2.09%   |
| Unknown                | 6         | 2.09%   |
| HP Laptop              | 5         | 1.74%   |
| HP 15                  | 5         | 1.74%   |
| Toshiba Satellite      | 4         | 1.39%   |
| HP Spectre             | 4         | 1.39%   |
| Acer Aspire            | 4         | 1.39%   |
| Lenovo Legion          | 3         | 1.05%   |
| HP Notebook            | 3         | 1.05%   |
| Toshiba dynabook       | 2         | 0.7%    |
| MSI MS-7C02            | 2         | 0.7%    |
| Lenovo ThinkCentre     | 2         | 0.7%    |
| Lenovo G50-80          | 2         | 0.7%    |
| HP ZBook               | 2         | 0.7%    |
| HP 630                 | 2         | 0.7%    |
| Endless EF20EA         | 2         | 0.7%    |
| ASUS X540NA            | 2         | 0.7%    |
| Toshiba TECRA          | 1         | 0.35%   |
| Toshiba R84SAU2        | 1         | 0.35%   |
| TECNO WinPad           | 1         | 0.35%   |
| Sony VGN-NS295J        | 1         | 0.35%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.35%   |
| Samsung RC410          | 1         | 0.35%   |
| Samsung 300E5EV        | 1         | 0.35%   |
| Samsung 300E4C         | 1         | 0.35%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.35%   |
| Notebook P65xHP        | 1         | 0.35%   |
| MSI MS-7D31            | 1         | 0.35%   |
| MSI 500-007A           | 1         | 0.35%   |
| MSI 0A90               | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 29        | 10.1%   |
| 2018    | 27        | 9.41%   |
| 2012    | 26        | 9.06%   |
| 2019    | 25        | 8.71%   |
| 2016    | 25        | 8.71%   |
| 2015    | 23        | 8.01%   |
| 2014    | 20        | 6.97%   |
| 2011    | 20        | 6.97%   |
| 2017    | 19        | 6.62%   |
| 2020    | 17        | 5.92%   |
| 2010    | 15        | 5.23%   |
| 2021    | 11        | 3.83%   |
| 2022    | 6         | 2.09%   |
| 2008    | 6         | 2.09%   |
| 2007    | 5         | 1.74%   |
| 2009    | 3         | 1.05%   |
| 2006    | 3         | 1.05%   |
| Unknown | 3         | 1.05%   |
| 2005    | 2         | 0.7%    |
| 2004    | 2         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 218       | 75.96%  |
| Desktop     | 45        | 15.68%  |
| Convertible | 18        | 6.27%   |
| Phone       | 2         | 0.7%    |
| Mini pc     | 2         | 0.7%    |
| All in one  | 1         | 0.35%   |
| Server      | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 266       | 91.41%  |
| Enabled  | 25        | 8.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 287       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 82        | 28.18%  |
| 3.01-4.0        | 73        | 25.09%  |
| 8.01-16.0       | 44        | 15.12%  |
| 16.01-24.0      | 43        | 14.78%  |
| 1.01-2.0        | 22        | 7.56%   |
| 32.01-64.0      | 13        | 4.47%   |
| 64.01-256.0     | 5         | 1.72%   |
| 24.01-32.0      | 3         | 1.03%   |
| 0.51-1.0        | 3         | 1.03%   |
| 2.01-3.0        | 2         | 0.69%   |
| More than 256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 89        | 27.73%  |
| 1.01-2.0    | 81        | 25.23%  |
| 4.01-8.0    | 57        | 17.76%  |
| 3.01-4.0    | 57        | 17.76%  |
| 0.51-1.0    | 22        | 6.85%   |
| 8.01-16.0   | 10        | 3.12%   |
| 0.01-0.5    | 3         | 0.93%   |
| 64.01-256.0 | 1         | 0.31%   |
| Unknown     | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 225       | 76.79%  |
| 2      | 51        | 17.41%  |
| 4      | 5         | 1.71%   |
| 3      | 5         | 1.71%   |
| 0      | 3         | 1.02%   |
| 10     | 1         | 0.34%   |
| 8      | 1         | 0.34%   |
| 6      | 1         | 0.34%   |
| 5      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 185       | 64.46%  |
| Yes       | 102       | 35.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 81.88%  |
| No        | 52        | 18.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 252       | 87.5%   |
| No        | 36        | 12.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 67.93%  |
| No        | 93        | 32.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 287       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Computers | Percent |
|-----------|-----------|---------|
| Nairobi   | 269       | 90.88%  |
| Mombasa   | 4         | 1.35%   |
| Nakuru    | 3         | 1.01%   |
| Kiambu    | 3         | 1.01%   |
| Nyeri     | 2         | 0.68%   |
| Kikuyu    | 2         | 0.68%   |
| Eldoret   | 2         | 0.68%   |
| Wote      | 1         | 0.34%   |
| Rongai    | 1         | 0.34%   |
| Nyahururu | 1         | 0.34%   |
| Narok     | 1         | 0.34%   |
| Nanyuki   | 1         | 0.34%   |
| Murang'a  | 1         | 0.34%   |
| Maralal   | 1         | 0.34%   |
| Machakos  | 1         | 0.34%   |
| Kisii     | 1         | 0.34%   |
| Kericho   | 1         | 0.34%   |
| Embakasi  | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 85        | 112    | 24.15%  |
| WDC                         | 46        | 56     | 13.07%  |
| Toshiba                     | 39        | 44     | 11.08%  |
| Samsung Electronics         | 39        | 56     | 11.08%  |
| HGST                        | 21        | 33     | 5.97%   |
| Unknown                     | 19        | 26     | 5.4%    |
| SanDisk                     | 14        | 17     | 3.98%   |
| Hitachi                     | 12        | 15     | 3.41%   |
| Intel                       | 7         | 9      | 1.99%   |
| Micron Technology           | 6         | 7      | 1.7%    |
| Crucial                     | 6         | 8      | 1.7%    |
| SPCC                        | 5         | 9      | 1.42%   |
| MARSHAL                     | 5         | 5      | 1.42%   |
| SK hynix                    | 4         | 5      | 1.14%   |
| Lexar                       | 4         | 4      | 1.14%   |
| Kingston                    | 4         | 6      | 1.14%   |
| Unknown                     | 4         | 4      | 1.14%   |
| Maxtor                      | 3         | 3      | 0.85%   |
| Team                        | 2         | 2      | 0.57%   |
| LITEON                      | 2         | 2      | 0.57%   |
| HUAWEI                      | 2         | 2      | 0.57%   |
| China                       | 2         | 2      | 0.57%   |
| Apple                       | 2         | 2      | 0.57%   |
| A-DATA Technology           | 2         | 2      | 0.57%   |
| Union Memory                | 1         | 1      | 0.28%   |
| TCSUNBOW                    | 1         | 1      | 0.28%   |
| Silicon Motion              | 1         | 1      | 0.28%   |
| Plextor                     | 1         | 1      | 0.28%   |
| Netac                       | 1         | 1      | 0.28%   |
| Micron/Crucial Technology   | 1         | 2      | 0.28%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.28%   |
| MAX                         | 1         | 1      | 0.28%   |
| LITEONIT                    | 1         | 1      | 0.28%   |
| Lite-On Technology          | 1         | 2      | 0.28%   |
| KIOXIA                      | 1         | 1      | 0.28%   |
| KINGBANK                    | 1         | 1      | 0.28%   |
| Hjwdz                       | 1         | 1      | 0.28%   |
| Golden                      | 1         | 1      | 0.28%   |
| FZ                          | 1         | 1      | 0.28%   |
| Eluktro                     | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 13        | 3.54%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 1.91%   |
| Seagate ST500LT012-9WS142 500GB                     | 7         | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 1.91%   |
| HGST HTS725050A7E630 500GB                          | 7         | 1.91%   |
| Seagate ST9500325AS 500GB                           | 6         | 1.63%   |
| Unknown MMC Card  64GB                              | 5         | 1.36%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 1.36%   |
| Samsung NVMe SSD Drive 512GB                        | 5         | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 1.36%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 1.09%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 1.09%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 1.09%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.09%   |
| Samsung SSD 960 EVO 1TB                             | 4         | 1.09%   |
| Unknown                                             | 4         | 1.09%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 3         | 0.82%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 3         | 0.82%   |
| WDC PC SN730 NVMe 512GB                             | 3         | 0.82%   |
| Unknown MMC Card  32GB                              | 3         | 0.82%   |
| SPCC M.2 PCIe SSD 512GB                             | 3         | 0.82%   |
| Seagate ST3320418AS 320GB                           | 3         | 0.82%   |
| MARSHAL MAL2500SA-T54L 500GB                        | 3         | 0.82%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.82%   |
| Crucial CT2050MX300SSD1 2TB                         | 3         | 0.82%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.54%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 2         | 0.54%   |
| WDC WD2500BEKT-75PVMT0 250GB                        | 2         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 0.54%   |
| Unknown NCard  32GB                                 | 2         | 0.54%   |
| Unknown MMC Card                                    | 2         | 0.54%   |
| Toshiba MQ01ABD050V 500GB                           | 2         | 0.54%   |
| Toshiba DT01ACA100 1TB                              | 2         | 0.54%   |
| Team T253X2001T 1TB SSD                             | 2         | 0.54%   |
| SPCC Solid State Disk 256GB                         | 2         | 0.54%   |
| Seagate ST500VT000-1DK142 500GB                     | 2         | 0.54%   |
| Seagate ST500VT000-1BS142 500GB                     | 2         | 0.54%   |
| Seagate ST500LM030-1RK17D 500GB                     | 2         | 0.54%   |
| Seagate ST3250318AS 250GB                           | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 84        | 111    | 42.42%  |
| WDC                 | 37        | 46     | 18.69%  |
| Toshiba             | 32        | 37     | 16.16%  |
| HGST                | 21        | 33     | 10.61%  |
| Hitachi             | 12        | 15     | 6.06%   |
| MARSHAL             | 5         | 5      | 2.53%   |
| Maxtor              | 3         | 3      | 1.52%   |
| Samsung Electronics | 2         | 2      | 1.01%   |
| Unknown             | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 18     | 17.39%  |
| SanDisk             | 10        | 11     | 14.49%  |
| Crucial             | 6         | 8      | 8.7%    |
| Micron Technology   | 4         | 5      | 5.8%    |
| WDC                 | 3         | 4      | 4.35%   |
| Toshiba             | 3         | 3      | 4.35%   |
| Lexar               | 3         | 3      | 4.35%   |
| Kingston            | 3         | 5      | 4.35%   |
| Intel               | 3         | 3      | 4.35%   |
| Team                | 2         | 2      | 2.9%    |
| SPCC                | 2         | 3      | 2.9%    |
| LITEON              | 2         | 2      | 2.9%    |
| China               | 2         | 2      | 2.9%    |
| Unknown             | 2         | 2      | 2.9%    |
| TCSUNBOW            | 1         | 1      | 1.45%   |
| SK hynix            | 1         | 1      | 1.45%   |
| Plextor             | 1         | 1      | 1.45%   |
| Netac               | 1         | 1      | 1.45%   |
| MAX                 | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| KINGBANK            | 1         | 1      | 1.45%   |
| Golden              | 1         | 1      | 1.45%   |
| FZ                  | 1         | 1      | 1.45%   |
| Eluktro             | 1         | 1      | 1.45%   |
| Apple               | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 178       | 254    | 53.94%  |
| SSD     | 65        | 83     | 19.7%   |
| NVMe    | 64        | 84     | 19.39%  |
| MMC     | 18        | 24     | 5.45%   |
| Unknown | 5         | 8      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 224       | 340    | 72.03%  |
| NVMe | 64        | 84     | 20.58%  |
| MMC  | 18        | 24     | 5.79%   |
| SAS  | 5         | 5      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 229    | 67.62%  |
| 0.51-1.0   | 65        | 82     | 26.64%  |
| 1.01-2.0   | 9         | 17     | 3.69%   |
| 3.01-4.0   | 2         | 5      | 0.82%   |
| 4.01-10.0  | 2         | 3      | 0.82%   |
| 2.01-3.0   | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 78        | 25.66%  |
| 101-250        | 74        | 24.34%  |
| 501-1000       | 51        | 16.78%  |
| 51-100         | 30        | 9.87%   |
| 1001-2000      | 22        | 7.24%   |
| Unknown        | 13        | 4.28%   |
| 1-20           | 12        | 3.95%   |
| More than 3000 | 8         | 2.63%   |
| 21-50          | 8         | 2.63%   |
| 2001-3000      | 8         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 83        | 26.69%  |
| 21-50          | 55        | 17.68%  |
| 101-250        | 53        | 17.04%  |
| 51-100         | 45        | 14.47%  |
| 251-500        | 32        | 10.29%  |
| 501-1000       | 15        | 4.82%   |
| Unknown        | 13        | 4.18%   |
| 1001-2000      | 10        | 3.22%   |
| More than 3000 | 4         | 1.29%   |
| 2001-3000      | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 7.14%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 4.76%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.76%   |
| Toshiba MQ01ABD050V 500GB             | 2         | 2      | 4.76%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 4.76%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 4.76%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AZLX-08K2TA0 500GB          | 1         | 1      | 2.38%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 2.38%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.38%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 2.38%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 2.38%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 2.38%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.38%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 2.38%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.38%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 2.38%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 2.38%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.38%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 2.38%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 2.38%   |
| HGST HTS721010A9 1TB                  | 1         | 2      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.38%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 2.38%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 2.38%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 2.38%   |
| Unknown                               | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 14        | 14     | 34.15%  |
| Toshiba  | 8         | 8      | 19.51%  |
| WDC      | 6         | 6      | 14.63%  |
| HGST     | 6         | 10     | 14.63%  |
| MARSHAL  | 2         | 2      | 4.88%   |
| Hitachi  | 2         | 3      | 4.88%   |
| SK hynix | 1         | 1      | 2.44%   |
| Crucial  | 1         | 2      | 2.44%   |
| Unknown  | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 35.9%   |
| Toshiba | 8         | 8      | 20.51%  |
| WDC     | 6         | 6      | 15.38%  |
| HGST    | 6         | 10     | 15.38%  |
| MARSHAL | 2         | 2      | 5.13%   |
| Hitachi | 2         | 3      | 5.13%   |
| Unknown | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 44     | 95%     |
| SSD  | 2         | 3      | 5%      |

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
| Detected | 169       | 251    | 55.96%  |
| Works    | 94        | 155    | 31.13%  |
| Malfunc  | 39        | 47     | 12.91%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 236       | 73.75%  |
| Samsung Electronics          | 27        | 8.44%   |
| AMD                          | 16        | 5%      |
| SanDisk                      | 10        | 3.13%   |
| Toshiba America Info Systems | 4         | 1.25%   |
| Silicon Motion               | 4         | 1.25%   |
| SK hynix                     | 3         | 0.94%   |
| Shenzhen Longsys Electronics | 2         | 0.63%   |
| Micron Technology            | 2         | 0.63%   |
| LSI Logic / Symbios Logic    | 2         | 0.63%   |
| ASMedia Technology           | 2         | 0.63%   |
| Union Memory (Shenzhen)      | 1         | 0.31%   |
| Realtek Semiconductor        | 1         | 0.31%   |
| Micron/Crucial Technology    | 1         | 0.31%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.31%   |
| Marvell Technology Group     | 1         | 0.31%   |
| Lite-On Technology           | 1         | 0.31%   |
| KIOXIA                       | 1         | 0.31%   |
| Kingston Technology Company  | 1         | 0.31%   |
| JMicron Technology           | 1         | 0.31%   |
| Broadcom / LSI               | 1         | 0.31%   |
| Apple                        | 1         | 0.31%   |
| ADATA Technology             | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 36        | 10.26%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 6.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 5.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 4.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 3.99%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 3.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 3.42%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 1.42%   |
| Intel SATA Controller [RAID mode]                                                | 5         | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.42%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.57%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.57%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 205       | 62.5%   |
| NVMe | 64        | 19.51%  |
| RAID | 31        | 9.45%   |
| IDE  | 27        | 8.23%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 263       | 91.64%  |
| AMD    | 22        | 7.67%   |
| ARM    | 2         | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 2.09%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 2.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 6         | 2.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 6         | 2.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.39%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 1.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 4         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.39%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.05%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.05%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.05%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.05%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.05%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.7%    |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.7%    |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.7%    |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.7%    |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 0.7%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 89        | 31.01%  |
| Intel Core i7           | 66        | 23%     |
| Intel Core i3           | 27        | 9.41%   |
| Intel Celeron           | 21        | 7.32%   |
| Other                   | 17        | 5.92%   |
| Intel Atom              | 9         | 3.14%   |
| Intel Core 2 Duo        | 7         | 2.44%   |
| AMD Ryzen 7             | 7         | 2.44%   |
| AMD Ryzen 5             | 6         | 2.09%   |
| Intel Pentium 4         | 5         | 1.74%   |
| Intel Pentium           | 5         | 1.74%   |
| Intel Xeon              | 4         | 1.39%   |
| Intel Pentium Dual-Core | 3         | 1.05%   |
| Intel Core i9           | 3         | 1.05%   |
| Intel Core 2            | 3         | 1.05%   |
| Intel Core 2 Quad       | 2         | 0.7%    |
| AMD FX                  | 2         | 0.7%    |
| AMD A10                 | 2         | 0.7%    |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core m3           | 1         | 0.35%   |
| ARM AArch64             | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Phenom II X3        | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 164       | 57.14%  |
| 4       | 82        | 28.57%  |
| 6       | 12        | 4.18%   |
| 8       | 10        | 3.48%   |
| 1       | 8         | 2.79%   |
| 3       | 3         | 1.05%   |
| 10      | 2         | 0.7%    |
| 32      | 1         | 0.35%   |
| 20      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 14      | 1         | 0.35%   |
| 12      | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 285       | 99.3%   |
| 2      | 2         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 220       | 76.66%  |
| 1       | 66        | 23%     |
| Unknown | 1         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 283       | 98.61%  |
| 32-bit         | 3         | 1.05%   |
| Unknown        | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 29.8%   |
| 0x306a9    | 26        | 8.61%   |
| 0x206a7    | 20        | 6.62%   |
| 0x40651    | 15        | 4.97%   |
| 0x406e3    | 14        | 4.64%   |
| 0x306c3    | 11        | 3.64%   |
| 0x806c1    | 9         | 2.98%   |
| 0x806ea    | 8         | 2.65%   |
| 0x306d4    | 8         | 2.65%   |
| 0x806ec    | 7         | 2.32%   |
| 0x906ea    | 6         | 1.99%   |
| 0x30678    | 6         | 1.99%   |
| 0x20655    | 6         | 1.99%   |
| 0x1067a    | 6         | 1.99%   |
| 0x706e5    | 5         | 1.66%   |
| 0x506e3    | 4         | 1.32%   |
| 0x406c4    | 4         | 1.32%   |
| 0x806e9    | 3         | 0.99%   |
| 0x706a8    | 3         | 0.99%   |
| 0x0800820d | 3         | 0.99%   |
| 0x906e9    | 2         | 0.66%   |
| 0x806eb    | 2         | 0.66%   |
| 0x706a1    | 2         | 0.66%   |
| 0x6fd      | 2         | 0.66%   |
| 0x6f6      | 2         | 0.66%   |
| 0x406c3    | 2         | 0.66%   |
| 0x106c2    | 2         | 0.66%   |
| 0x10676    | 2         | 0.66%   |
| 0x08608103 | 2         | 0.66%   |
| 0x08600106 | 2         | 0.66%   |
| 0xf65      | 1         | 0.33%   |
| 0xf49      | 1         | 0.33%   |
| 0xf43      | 1         | 0.33%   |
| 0xf41      | 1         | 0.33%   |
| 0xa0652    | 1         | 0.33%   |
| 0x906ec    | 1         | 0.33%   |
| 0x906a4    | 1         | 0.33%   |
| 0x90661    | 1         | 0.33%   |
| 0x806c2    | 1         | 0.33%   |
| 0x6fa      | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 47        | 16.38%  |
| Haswell          | 39        | 13.59%  |
| Skylake          | 28        | 9.76%   |
| IvyBridge        | 28        | 9.76%   |
| SandyBridge      | 22        | 7.67%   |
| Silvermont       | 16        | 5.57%   |
| Broadwell        | 13        | 4.53%   |
| Westmere         | 11        | 3.83%   |
| TigerLake        | 11        | 3.83%   |
| IceLake          | 9         | 3.14%   |
| Penryn           | 8         | 2.79%   |
| Core             | 8         | 2.79%   |
| Zen+             | 6         | 2.09%   |
| Goldmont plus    | 6         | 2.09%   |
| Zen 2            | 5         | 1.74%   |
| NetBurst         | 5         | 1.74%   |
| Alderlake Hybrid | 4         | 1.39%   |
| Unknown          | 4         | 1.39%   |
| Goldmont         | 3         | 1.05%   |
| Zen 3            | 2         | 0.7%    |
| Piledriver       | 2         | 0.7%    |
| Excavator        | 2         | 0.7%    |
| Bonnell          | 2         | 0.7%    |
| Tremont          | 1         | 0.35%   |
| Steamroller      | 1         | 0.35%   |
| P6               | 1         | 0.35%   |
| K10              | 1         | 0.35%   |
| CometLake        | 1         | 0.35%   |
| Bobcat           | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 240       | 75.24%  |
| Nvidia                     | 39        | 12.23%  |
| AMD                        | 39        | 12.23%  |
| Matrox Electronics Systems | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 6.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 6.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 6.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.98%   |
| Intel HD Graphics 5500                                                                   | 13        | 3.98%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.36%   |
| Intel HD Graphics 620                                                                    | 10        | 3.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.53%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.22%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.92%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.92%   |
| Intel HD Graphics 530                                                                    | 3         | 0.92%   |
| Intel HD Graphics 500                                                                    | 3         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.92%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.92%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.61%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.61%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 206       | 71.28%  |
| 1 x AMD        | 26        | 9%      |
| 1 x Nvidia     | 21        | 7.27%   |
| Intel + Nvidia | 17        | 5.88%   |
| Intel + AMD    | 12        | 4.15%   |
| 2 x Intel      | 3         | 1.04%   |
| Other          | 2         | 0.69%   |
| 2 x AMD        | 1         | 0.35%   |
| 1 x Matrox     | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 270       | 93.43%  |
| Proprietary | 15        | 5.19%   |
| Unknown     | 4         | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 227       | 78.01%  |
| 1.01-2.0   | 21        | 7.22%   |
| 0.01-0.5   | 17        | 5.84%   |
| 3.01-4.0   | 9         | 3.09%   |
| 0.51-1.0   | 8         | 2.75%   |
| 7.01-8.0   | 7         | 2.41%   |
| 5.01-6.0   | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 20.74%  |
| Chimei Innolux          | 43        | 14.38%  |
| LG Display              | 34        | 11.37%  |
| BOE                     | 34        | 11.37%  |
| Hewlett-Packard         | 26        | 8.7%    |
| Samsung Electronics     | 24        | 8.03%   |
| Dell                    | 15        | 5.02%   |
| Sharp                   | 7         | 2.34%   |
| InfoVision              | 7         | 2.34%   |
| Sony                    | 5         | 1.67%   |
| Lenovo                  | 5         | 1.67%   |
| Chi Mei Optoelectronics | 5         | 1.67%   |
| Apple                   | 4         | 1.34%   |
| LG Philips              | 3         | 1%      |
| KDC                     | 3         | 1%      |
| HannStar                | 3         | 1%      |
| Unknown (XXX)           | 2         | 0.67%   |
| NEC Computers           | 2         | 0.67%   |
| CSO                     | 2         | 0.67%   |
| BenQ                    | 2         | 0.67%   |
| Acer                    | 2         | 0.67%   |
| VIE                     | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |
| Sceptre Tech            | 1         | 0.33%   |
| S2-Tek                  | 1         | 0.33%   |
| Planar                  | 1         | 0.33%   |
| Hitachi                 | 1         | 0.33%   |
| Eizo                    | 1         | 0.33%   |
| CVT                     | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 5         | 1.66%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 1.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.32%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 0.99%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.99%   |
| Sony TV SNY6F02 1360x768                                                 | 2         | 0.66%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch        | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.66%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 2         | 0.66%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.66%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                     | 2         | 0.66%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.66%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch               | 2         | 0.66%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.66%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.66%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.66%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.66%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.66%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                    | 1         | 0.33%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080    | 1         | 0.33%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.33%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.33%   |
| Sony TV SNYEF03 1600x900                                                 | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 37.93%  |
| 1920x1080 (FHD)    | 96        | 33.1%   |
| 1600x900 (HD+)     | 20        | 6.9%    |
| 1280x1024 (SXGA)   | 10        | 3.45%   |
| 3840x2160 (4K)     | 9         | 3.1%    |
| 1920x1200 (WUXGA)  | 6         | 2.07%   |
| 1440x900 (WXGA+)   | 6         | 2.07%   |
| 1280x800 (WXGA)    | 6         | 2.07%   |
| 2560x1440 (QHD)    | 4         | 1.38%   |
| 1680x1050 (WSXGA+) | 3         | 1.03%   |
| 1360x768           | 3         | 1.03%   |
| 3840x2400          | 2         | 0.69%   |
| 1024x768 (XGA)     | 2         | 0.69%   |
| 1024x600           | 2         | 0.69%   |
| Unknown            | 2         | 0.69%   |
| 3440x1440          | 1         | 0.34%   |
| 3200x1800 (QHD+)   | 1         | 0.34%   |
| 3200x1080          | 1         | 0.34%   |
| 3072x1920          | 1         | 0.34%   |
| 2560x1600          | 1         | 0.34%   |
| 2560x1080          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1920x1280          | 1         | 0.34%   |
| 1600x1200          | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 85        | 28.62%  |
| 13      | 60        | 20.2%   |
| 14      | 50        | 16.84%  |
| 12      | 11        | 3.7%    |
| 21      | 10        | 3.37%   |
| 17      | 9         | 3.03%   |
| 11      | 9         | 3.03%   |
| 19      | 8         | 2.69%   |
| 27      | 7         | 2.36%   |
| 23      | 7         | 2.36%   |
| 24      | 6         | 2.02%   |
| 18      | 6         | 2.02%   |
| 72      | 4         | 1.35%   |
| 22      | 3         | 1.01%   |
| 20      | 3         | 1.01%   |
| 10      | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 84      | 2         | 0.67%   |
| 46      | 2         | 0.67%   |
| 34      | 2         | 0.67%   |
| 16      | 2         | 0.67%   |
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
| 301-350     | 171       | 58.36%  |
| 201-300     | 51        | 17.41%  |
| 501-600     | 21        | 7.17%   |
| 401-500     | 20        | 6.83%   |
| 351-400     | 13        | 4.44%   |
| 1501-2000   | 6         | 2.05%   |
| Unknown     | 3         | 1.02%   |
| 801-900     | 2         | 0.68%   |
| 1001-1500   | 2         | 0.68%   |
| 901-1000    | 2         | 0.68%   |
| 701-800     | 1         | 0.34%   |
| 601-700     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 233       | 82.62%  |
| 16/10   | 30        | 10.64%  |
| 5/4     | 10        | 3.55%   |
| Unknown | 3         | 1.06%   |
| 4/3     | 2         | 0.71%   |
| 3/2     | 2         | 0.71%   |
| 21/9    | 2         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 84        | 28.47%  |
| 81-90          | 83        | 28.14%  |
| 71-80          | 27        | 9.15%   |
| 201-250        | 18        | 6.1%    |
| 151-200        | 14        | 4.75%   |
| 61-70          | 11        | 3.73%   |
| 141-150        | 10        | 3.39%   |
| 51-60          | 9         | 3.05%   |
| More than 1000 | 7         | 2.37%   |
| 301-350        | 7         | 2.37%   |
| 251-300        | 5         | 1.69%   |
| 501-1000       | 4         | 1.36%   |
| 351-500        | 3         | 1.02%   |
| 41-50          | 3         | 1.02%   |
| 121-130        | 3         | 1.02%   |
| Unknown        | 3         | 1.02%   |
| 111-120        | 2         | 0.68%   |
| 131-140        | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 96        | 33.22%  |
| 101-120       | 96        | 33.22%  |
| 51-100        | 57        | 19.72%  |
| 161-240       | 22        | 7.61%   |
| More than 240 | 8         | 2.77%   |
| 1-50          | 7         | 2.42%   |
| Unknown       | 3         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 244       | 82.99%  |
| 2     | 39        | 13.27%  |
| 0     | 10        | 3.4%    |
| 3     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 175       | 40.51%  |
| Realtek Semiconductor             | 119       | 27.55%  |
| Qualcomm Atheros                  | 47        | 10.88%  |
| Broadcom                          | 25        | 5.79%   |
| MediaTek                          | 9         | 2.08%   |
| Hewlett-Packard                   | 8         | 1.85%   |
| Broadcom Limited                  | 7         | 1.62%   |
| Samsung Electronics               | 6         | 1.39%   |
| Ralink                            | 5         | 1.16%   |
| OPPO Electronics                  | 4         | 0.93%   |
| Huawei Technologies               | 4         | 0.93%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.69%   |
| Xiaomi                            | 3         | 0.69%   |
| Sierra Wireless                   | 3         | 0.69%   |
| Ralink Technology                 | 3         | 0.69%   |
| Marvell Technology Group          | 3         | 0.69%   |
| T & A Mobile Phones               | 2         | 0.46%   |
| Ericsson Business Mobile Networks | 2         | 0.46%   |
| Spreadtrum Communications         | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| LSI                               | 1         | 0.23%   |
| IBM                               | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 12.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 4.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.07%   |
| Intel Wireless 7260                                               | 21        | 3.88%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 2.96%   |
| Intel Wireless 8260                                               | 14        | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 2.4%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 2.4%    |
| Intel Wireless 8265 / 8275                                        | 12        | 2.22%   |
| Intel Wireless 7265                                               | 12        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10        | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.66%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.48%   |
| MediaTek X55                                                      | 8         | 1.48%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 1.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.92%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.74%   |
| OPPO RMX3623                                                      | 4         | 0.74%   |
| Intel Wireless 3160                                               | 4         | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.74%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.74%   |
| HP lt4112 Gobi 4G Module Network Device                           | 4         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.74%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 3         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 142       | 53.38%  |
| Realtek Semiconductor             | 46        | 17.29%  |
| Qualcomm Atheros                  | 41        | 15.41%  |
| Broadcom                          | 19        | 7.14%   |
| Ralink                            | 5         | 1.88%   |
| Hewlett-Packard                   | 5         | 1.88%   |
| Sierra Wireless                   | 3         | 1.13%   |
| Ralink Technology                 | 3         | 1.13%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| Broadcom Limited                  | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 21        | 7.89%   |
| Intel Wireless 8260                                            | 14        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 4.89%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.51%   |
| Intel Wireless 7265                                            | 12        | 4.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 4.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.38%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 3.38%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 3.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 3.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 2.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 6         | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.26%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.5%    |
| Intel Wireless 3160                                            | 4         | 1.5%    |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.13%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.75%   |
| Intel Wireless-AC 9260                                         | 2         | 0.75%   |
| Intel Wireless 3165                                            | 2         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 111       | 41.73%  |
| Realtek Semiconductor      | 97        | 36.47%  |
| Qualcomm Atheros           | 9         | 3.38%   |
| MediaTek                   | 9         | 3.38%   |
| Broadcom                   | 7         | 2.63%   |
| Broadcom Limited           | 6         | 2.26%   |
| OPPO Electronics           | 4         | 1.5%    |
| ZTE WCDMA Technologies MSM | 3         | 1.13%   |
| Xiaomi                     | 3         | 1.13%   |
| Samsung Electronics        | 3         | 1.13%   |
| Marvell Technology Group   | 3         | 1.13%   |
| Hewlett-Packard            | 3         | 1.13%   |
| T & A Mobile Phones        | 2         | 0.75%   |
| Huawei Technologies        | 2         | 0.75%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 24.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 9.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 8.18%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 5.95%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 4.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.97%   |
| MediaTek X55                                                      | 8         | 2.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.23%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.86%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.86%   |
| OPPO RMX3623                                                      | 4         | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.49%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 3         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.12%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 3         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.74%   |
| T & A Mobile Phones Alcatel 1                                     | 2         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.74%   |
| MediaTek P8                                                       | 2         | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.74%   |
| Huawei E353/E3131                                                 | 2         | 0.74%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.37%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 252       | 51.12%  |
| Ethernet | 235       | 47.67%  |
| Modem    | 6         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 73.01%  |
| Ethernet | 78        | 26.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 179       | 62.15%  |
| 1     | 93        | 32.29%  |
| 0     | 11        | 3.82%   |
| 3     | 3         | 1.04%   |
| 6     | 1         | 0.35%   |
| 4     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 280       | 97.56%  |
| Yes  | 7         | 2.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 58.08%  |
| Qualcomm Atheros Communications | 24        | 12.12%  |
| Realtek Semiconductor           | 18        | 9.09%   |
| Broadcom                        | 12        | 6.06%   |
| Ralink                          | 4         | 2.02%   |
| IMC Networks                    | 4         | 2.02%   |
| Hewlett-Packard                 | 4         | 2.02%   |
| Lite-On Technology              | 3         | 1.52%   |
| Cambridge Silicon Radio         | 3         | 1.52%   |
| Toshiba                         | 2         | 1.01%   |
| Dell                            | 2         | 1.01%   |
| Apple                           | 2         | 1.01%   |
| Taiyo Yuden                     | 1         | 0.51%   |
| Realtek                         | 1         | 0.51%   |
| Foxconn / Hon Hai               | 1         | 0.51%   |
| Alps Electric                   | 1         | 0.51%   |
| Unknown                         | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 31.82%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 7.07%   |
| Intel AX201 Bluetooth                               | 14        | 7.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 6.57%   |
| Realtek Bluetooth Radio                             | 12        | 6.06%   |
| Intel AX200 Bluetooth                               | 9         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.53%   |
| Broadcom HP Portable SoftSailing                    | 5         | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.02%   |
| Ralink RT3290 Bluetooth                             | 4         | 2.02%   |
| Intel Bluetooth Device                              | 4         | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.52%   |
| IMC Networks Bluetooth Device                       | 3         | 1.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.52%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.01%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.01%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.51%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.51%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.51%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.51%   |
| Lite-On Bluetooth Device                            | 1         | 0.51%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.51%   |
| Intel AX210 Bluetooth                               | 1         | 0.51%   |
| IMC Networks Bluetooth                              | 1         | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.51%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 253       | 77.85%  |
| AMD                         | 29        | 8.92%   |
| Nvidia                      | 23        | 7.08%   |
| Texas Instruments           | 3         | 0.92%   |
| Generalplus Technology      | 3         | 0.92%   |
| Realtek Semiconductor       | 2         | 0.62%   |
| Lenovo                      | 2         | 0.62%   |
| C-Media Electronics         | 2         | 0.62%   |
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
| Intel Sunrise Point-LP HD Audio                                                                   | 47        | 12.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 6.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 5.64%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 3.33%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 2.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.28%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.77%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.77%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.77%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.51%   |
| Lenovo T2224zD                                                                                    | 2         | 0.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.51%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 61        | 30.05%  |
| SK hynix            | 51        | 25.12%  |
| Micron Technology   | 24        | 11.82%  |
| Kingston            | 15        | 7.39%   |
| Unknown             | 13        | 6.4%    |
| Crucial             | 11        | 5.42%   |
| Elpida              | 7         | 3.45%   |
| Ramaxel Technology  | 5         | 2.46%   |
| A-DATA Technology   | 3         | 1.48%   |
| G.Skill             | 2         | 0.99%   |
| Apacer              | 2         | 0.99%   |
| TwinMOS             | 1         | 0.49%   |
| Timetec             | 1         | 0.49%   |
| Team                | 1         | 0.49%   |
| Qimonda             | 1         | 0.49%   |
| Patriot             | 1         | 0.49%   |
| Nanya Technology    | 1         | 0.49%   |
| Corsair             | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 3.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 3.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 1.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.9%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 4         | 1.9%    |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 1.43%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 1.43%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 0.95%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.95%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.95%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 0.95%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 0.95%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.95%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.95%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 2         | 0.95%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 2         | 0.95%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.95%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 2         | 0.95%   |
| Apacer RAM 76.A302G.C4D0B 2GB SODIMM DDR3 1600MT/s           | 2         | 0.95%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                      | 1         | 0.48%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s             | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 70        | 44.87%  |
| DDR4   | 60        | 38.46%  |
| LPDDR4 | 7         | 4.49%   |
| DDR2   | 6         | 3.85%   |
| LPDDR3 | 5         | 3.21%   |
| SDRAM  | 4         | 2.56%   |
| DDR5   | 2         | 1.28%   |
| DDR    | 2         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 73.46%  |
| Row Of Chips | 20        | 12.35%  |
| DIMM         | 17        | 10.49%  |
| Chip         | 6         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 38.55%  |
| 8192  | 50        | 27.93%  |
| 16384 | 24        | 13.41%  |
| 2048  | 24        | 13.41%  |
| 1024  | 7         | 3.91%   |
| 32768 | 4         | 2.23%   |
| 512   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 32.76%  |
| 2667    | 32        | 18.39%  |
| 3200    | 15        | 8.62%   |
| 2133    | 11        | 6.32%   |
| 1333    | 11        | 6.32%   |
| 1334    | 9         | 5.17%   |
| 4267    | 7         | 4.02%   |
| 2400    | 6         | 3.45%   |
| 1867    | 4         | 2.3%    |
| 667     | 4         | 2.3%    |
| 3600    | 2         | 1.15%   |
| 3266    | 2         | 1.15%   |
| 800     | 2         | 1.15%   |
| Unknown | 2         | 1.15%   |
| 8400    | 1         | 0.57%   |
| 5800    | 1         | 0.57%   |
| 4800    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3800    | 1         | 0.57%   |
| 2666    | 1         | 0.57%   |
| 2000    | 1         | 0.57%   |
| 1067    | 1         | 0.57%   |
| 400     | 1         | 0.57%   |
| 333     | 1         | 0.57%   |

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
| Chicony Electronics                    | 68        | 30.09%  |
| Cheng Uei Precision Industry (Foxlink) | 30        | 13.27%  |
| Bison Electronics                      | 16        | 7.08%   |
| Realtek Semiconductor                  | 14        | 6.19%   |
| Lite-On Technology                     | 13        | 5.75%   |
| Sunplus Innovation Technology          | 12        | 5.31%   |
| Syntek                                 | 11        | 4.87%   |
| IMC Networks                           | 11        | 4.87%   |
| Microdia                               | 10        | 4.42%   |
| Quanta                                 | 4         | 1.77%   |
| Apple                                  | 4         | 1.77%   |
| Silicon Motion                         | 3         | 1.33%   |
| Samsung Electronics                    | 3         | 1.33%   |
| Logitech                               | 3         | 1.33%   |
| Acer                                   | 3         | 1.33%   |
| Unknown                                | 2         | 0.88%   |
| Suyin                                  | 2         | 0.88%   |
| Ricoh                                  | 2         | 0.88%   |
| Luxvisions Innotech Limited            | 2         | 0.88%   |
| Importek                               | 2         | 0.88%   |
| Alcor Micro                            | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| Xiaomi                                 | 1         | 0.44%   |
| Primax Electronics                     | 1         | 0.44%   |
| MacroSilicon                           | 1         | 0.44%   |
| LG Electronics                         | 1         | 0.44%   |
| icSpring                               | 1         | 0.44%   |
| DigiTech                               | 1         | 0.44%   |
| Cubeternet                             | 1         | 0.44%   |
| ALi                                    | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 15        | 6.58%   |
| Chicony HP HD Webcam                                                       | 8         | 3.51%   |
| Syntek Integrated Camera                                                   | 7         | 3.07%   |
| Lite-On HP HD Camera                                                       | 7         | 3.07%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3.07%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.63%   |
| Bison Integrated Camera                                                    | 6         | 2.63%   |
| Chicony HP HD Webcam [Fixed]                                               | 5         | 2.19%   |
| Chicony HP HD Camera                                                       | 5         | 2.19%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.75%   |
| Lite-On HP HD Webcam                                                       | 4         | 1.75%   |
| Chicony Chicony USB 2.0 Camera                                             | 4         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.75%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.32%   |
| Realtek Integrated Webcam                                                  | 3         | 1.32%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.32%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.32%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 1.32%   |
| Chicony HD Webcam                                                          | 3         | 1.32%   |
| Bison ThinkPad P50 Integrated Camera                                       | 3         | 1.32%   |
| Unknown USB Camera                                                         | 2         | 0.88%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.88%   |
| Syntek EasyCamera                                                          | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.88%   |
| Sunplus HP Truevision Full HD                                              | 2         | 0.88%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.88%   |
| Realtek FULL HD 1080P Webcam                                               | 2         | 0.88%   |
| Logitech Webcam C270                                                       | 2         | 0.88%   |
| Importek HP Webcam-50                                                      | 2         | 0.88%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 0.88%   |
| IMC Networks Integrated Camera                                             | 2         | 0.88%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.88%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.88%   |
| Chicony HP Webcam                                                          | 2         | 0.88%   |
| Chicony HP Truevision HD camera                                            | 2         | 0.88%   |
| Chicony HP Truevision HD                                                   | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 68.42%  |
| Synaptics                  | 14        | 18.42%  |
| Shenzhen Goodix Technology | 6         | 7.89%   |
| AuthenTec                  | 2         | 2.63%   |
| LighTuning Technology      | 1         | 1.32%   |
| Elan Microelectronics      | 1         | 1.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 23.68%  |
| Validity Sensors VFS491                                                    | 10        | 13.16%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 5.26%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.95%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.95%   |
| Synaptics WBDI Device                                                      | 3         | 3.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 2.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.63%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.32%   |
| Synaptics UWP WBDI                                                         | 1         | 1.32%   |
| Synaptics  WBDI                                                            | 1         | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.32%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.32%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 50%     |
| Alcor Micro | 3         | 25%     |
| Upek        | 2         | 16.67%  |
| O2 Micro    | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 176       | 60.69%  |
| 1     | 93        | 32.07%  |
| 2     | 19        | 6.55%   |
| 3     | 2         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 75        | 54.74%  |
| Graphics card            | 18        | 13.14%  |
| Chipcard                 | 11        | 8.03%   |
| Net/wireless             | 7         | 5.11%   |
| Multimedia controller    | 5         | 3.65%   |
| Bluetooth                | 5         | 3.65%   |
| Net/ethernet             | 4         | 2.92%   |
| Camera                   | 4         | 2.92%   |
| Storage                  | 3         | 2.19%   |
| Communication controller | 3         | 2.19%   |
| Unassigned class         | 1         | 0.73%   |
| Sound                    | 1         | 0.73%   |


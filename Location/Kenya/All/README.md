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

Total: 432

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G2            | Notebook    | [4a3954a4c1](https://linux-hardware.org/?probe=4a3954a4c1) | Feb 02, 2024 |
| HP            | ProBook 440 G1              | Notebook    | [1a7d0f5488](https://linux-hardware.org/?probe=1a7d0f5488) | Feb 01, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [130befb564](https://linux-hardware.org/?probe=130befb564) | Jan 16, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [385ad48703](https://linux-hardware.org/?probe=385ad48703) | Jan 16, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [20eede7cbf](https://linux-hardware.org/?probe=20eede7cbf) | Jan 12, 2024 |
| ASUSTek       | X540NA                      | Notebook    | [1f6d0e42df](https://linux-hardware.org/?probe=1f6d0e42df) | Jan 10, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [01a010ceeb](https://linux-hardware.org/?probe=01a010ceeb) | Jan 02, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
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
| Ubuntu 20.04                 | 46        | 14.24%  |
| Ubuntu 22.04                 | 33        | 10.22%  |
| Ubuntu 18.04                 | 19        | 5.88%   |
| Zorin 16                     | 8         | 2.48%   |
| Arch Rolling                 | 8         | 2.48%   |
| Linux Mint 20.3              | 7         | 2.17%   |
| Fedora 38                    | 7         | 2.17%   |
| Fedora 36                    | 7         | 2.17%   |
| Zorin 15                     | 6         | 1.86%   |
| Manjaro                      | 6         | 1.86%   |
| Ubuntu 23.04                 | 5         | 1.55%   |
| Pop!_OS 20.04                | 5         | 1.55%   |
| OpenMandriva 4.2             | 5         | 1.55%   |
| Arch                         | 5         | 1.55%   |
| Ubuntu 20.10                 | 4         | 1.24%   |
| Ubuntu 19.04                 | 4         | 1.24%   |
| Linux Mint 21                | 4         | 1.24%   |
| Fedora 37                    | 4         | 1.24%   |
| Debian 12                    | 4         | 1.24%   |
| Debian 11                    | 4         | 1.24%   |
| ArcoLinux Rolling            | 4         | 1.24%   |
| Ubuntu 21.10                 | 3         | 0.93%   |
| Ubuntu 21.04                 | 3         | 0.93%   |
| Q4OS 3                       | 3         | 0.93%   |
| Pop!_OS 22.04                | 3         | 0.93%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.93%   |
| Linux Mint 21.2              | 3         | 0.93%   |
| Linux Mint 20.2              | 3         | 0.93%   |
| Kali 2023.3                  | 3         | 0.93%   |
| Fedora 35                    | 3         | 0.93%   |
| Fedora 33                    | 3         | 0.93%   |
| Fedora 32                    | 3         | 0.93%   |
| Ubuntu 19.10                 | 2         | 0.62%   |
| Pop!_OS 20.10                | 2         | 0.62%   |
| Parrot 5.3                   | 2         | 0.62%   |
| Parrot 5.1                   | 2         | 0.62%   |
| OpenMandriva 4.3             | 2         | 0.62%   |
| Linux Mint 19                | 2         | 0.62%   |
| Kali 2023.2                  | 2         | 0.62%   |
| Kali 2022.3                  | 2         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 115       | 37.95%  |
| Fedora        | 26        | 8.58%   |
| Linux Mint    | 19        | 6.27%   |
| Zorin         | 14        | 4.62%   |
| Arch          | 13        | 4.29%   |
| Endless       | 12        | 3.96%   |
| OpenMandriva  | 11        | 3.63%   |
| Kali          | 11        | 3.63%   |
| Pop!_OS       | 10        | 3.3%    |
| Manjaro       | 10        | 3.3%    |
| Debian        | 9         | 2.97%   |
| Parrot        | 8         | 2.64%   |
| Elementary    | 5         | 1.65%   |
| ArcoLinux     | 4         | 1.32%   |
| Q4OS          | 3         | 0.99%   |
| openSUSE      | 3         | 0.99%   |
| Ubuntu MATE   | 2         | 0.66%   |
| ROSA          | 2         | 0.66%   |
| RHEL          | 2         | 0.66%   |
| Lubuntu       | 2         | 0.66%   |
| KDE neon      | 2         | 0.66%   |
| Garuda Linux  | 2         | 0.66%   |
| Deepin        | 2         | 0.66%   |
| BlackPanther  | 2         | 0.66%   |
| Android       | 2         | 0.66%   |
| Xubuntu       | 1         | 0.33%   |
| Ubuntu Studio | 1         | 0.33%   |
| Ubuntu Budgie | 1         | 0.33%   |
| Rocky Linux   | 1         | 0.33%   |
| Nobara        | 1         | 0.33%   |
| Mageia        | 1         | 0.33%   |
| LMDE          | 1         | 0.33%   |
| Lilidog       | 1         | 0.33%   |
| CentOS        | 1         | 0.33%   |
| blendOS       | 1         | 0.33%   |
| antiX         | 1         | 0.33%   |
| Alpine        | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 1.73%   |
| 5.4.0-42-generic         | 5         | 1.44%   |
| 5.15.0-58-generic        | 5         | 1.44%   |
| 5.15.0-52-generic        | 5         | 1.44%   |
| 5.15.0-41-generic        | 5         | 1.44%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.44%   |
| 5.4.0-52-generic         | 4         | 1.15%   |
| 5.19.0-41-generic        | 4         | 1.15%   |
| 5.11.0-38-generic        | 4         | 1.15%   |
| 6.3.0-kali1-amd64        | 3         | 0.86%   |
| 6.2.0-32-generic         | 3         | 0.86%   |
| 5.8.0-43-generic         | 3         | 0.86%   |
| 5.4.0-58-generic         | 3         | 0.86%   |
| 5.4.0-45-generic         | 3         | 0.86%   |
| 5.4.0-37-generic         | 3         | 0.86%   |
| 5.4.0-137-generic        | 3         | 0.86%   |
| 5.3.0-28-generic         | 3         | 0.86%   |
| 5.19.0-38-generic        | 3         | 0.86%   |
| 5.19.0-35-generic        | 3         | 0.86%   |
| 5.15.0-53-generic        | 3         | 0.86%   |
| 4.19.0-17-amd64          | 3         | 0.86%   |
| 6.5.0-10-generic         | 2         | 0.58%   |
| 6.1.0-kali7-amd64        | 2         | 0.58%   |
| 5.9.13-200.fc33.x86_64   | 2         | 0.58%   |
| 5.8.4-200.fc32.x86_64    | 2         | 0.58%   |
| 5.8.0-63-generic         | 2         | 0.58%   |
| 5.8.0-59-generic         | 2         | 0.58%   |
| 5.8.0-55-generic         | 2         | 0.58%   |
| 5.8.0-50-generic         | 2         | 0.58%   |
| 5.4.0-67-generic         | 2         | 0.58%   |
| 5.4.0-65-generic         | 2         | 0.58%   |
| 5.4.0-54-generic         | 2         | 0.58%   |
| 5.4.0-48-generic         | 2         | 0.58%   |
| 5.4.0-47-generic         | 2         | 0.58%   |
| 5.4.0-33-generic         | 2         | 0.58%   |
| 5.4.0-19-generic         | 2         | 0.58%   |
| 5.3.0-62-generic         | 2         | 0.58%   |
| 5.19.9-200.fc36.x86_64   | 2         | 0.58%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.58%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 15.55%  |
| 5.15.0  | 30        | 9.15%   |
| 5.8.0   | 24        | 7.32%   |
| 5.11.0  | 17        | 5.18%   |
| 5.19.0  | 12        | 3.66%   |
| 5.13.0  | 12        | 3.66%   |
| 4.15.0  | 12        | 3.66%   |
| 5.3.0   | 10        | 3.05%   |
| 6.2.0   | 9         | 2.74%   |
| 6.1.0   | 9         | 2.74%   |
| 5.0.0   | 9         | 2.74%   |
| 5.10.0  | 6         | 1.83%   |
| 5.10.14 | 5         | 1.52%   |
| 6.5.0   | 4         | 1.22%   |
| 5.18.0  | 4         | 1.22%   |
| 4.19.0  | 4         | 1.22%   |
| 4.18.0  | 4         | 1.22%   |
| 6.3.0   | 3         | 0.91%   |
| 5.19.9  | 3         | 0.91%   |
| 5.16.7  | 3         | 0.91%   |
| 5.14.0  | 3         | 0.91%   |
| 6.5.6   | 2         | 0.61%   |
| 6.4.8   | 2         | 0.61%   |
| 6.3.4   | 2         | 0.61%   |
| 6.1.52  | 2         | 0.61%   |
| 5.9.13  | 2         | 0.61%   |
| 5.8.4   | 2         | 0.61%   |
| 5.18.13 | 2         | 0.61%   |
| 5.17.5  | 2         | 0.61%   |
| 5.13.19 | 2         | 0.61%   |
| 4.18.16 | 2         | 0.61%   |
| 6.6.9   | 1         | 0.3%    |
| 6.6.2   | 1         | 0.3%    |
| 6.6.13  | 1         | 0.3%    |
| 6.6.11  | 1         | 0.3%    |
| 6.5.7   | 1         | 0.3%    |
| 6.5.5   | 1         | 0.3%    |
| 6.5.2   | 1         | 0.3%    |
| 6.4.15  | 1         | 0.3%    |
| 6.4.14  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 15.69%  |
| 5.15    | 35        | 10.77%  |
| 5.8     | 27        | 8.31%   |
| 5.19    | 21        | 6.46%   |
| 5.11    | 18        | 5.54%   |
| 6.1     | 17        | 5.23%   |
| 5.10    | 15        | 4.62%   |
| 5.13    | 14        | 4.31%   |
| 6.2     | 13        | 4%      |
| 4.15    | 12        | 3.69%   |
| 5.3     | 10        | 3.08%   |
| 5.0     | 10        | 3.08%   |
| 6.5     | 9         | 2.77%   |
| 6.3     | 8         | 2.46%   |
| 5.16    | 7         | 2.15%   |
| 5.18    | 6         | 1.85%   |
| 5.14    | 6         | 1.85%   |
| 4.18    | 6         | 1.85%   |
| 6.4     | 5         | 1.54%   |
| 4.19    | 5         | 1.54%   |
| 6.6     | 4         | 1.23%   |
| 6.0     | 3         | 0.92%   |
| 5.9     | 3         | 0.92%   |
| 5.6     | 3         | 0.92%   |
| 5.17    | 3         | 0.92%   |
| 4.9     | 3         | 0.92%   |
| 5.2     | 2         | 0.62%   |
| 5.12    | 2         | 0.62%   |
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
| x86_64  | 286       | 97.61%  |
| i686    | 5         | 1.71%   |
| armv8l  | 1         | 0.34%   |
| aarch64 | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 178       | 58.55%  |
| KDE5            | 34        | 11.18%  |
| Unknown         | 28        | 9.21%   |
| X-Cinnamon      | 17        | 5.59%   |
| XFCE            | 15        | 4.93%   |
| MATE            | 9         | 2.96%   |
| Pantheon        | 5         | 1.64%   |
| KDE             | 4         | 1.32%   |
| LXQt            | 2         | 0.66%   |
| KDE4            | 2         | 0.66%   |
| Cinnamon        | 2         | 0.66%   |
| awesome         | 2         | 0.66%   |
| openbox         | 1         | 0.33%   |
| GNOME Flashback | 1         | 0.33%   |
| Endless:GNOME   | 1         | 0.33%   |
| DWM             | 1         | 0.33%   |
| Deepin          | 1         | 0.33%   |
| DDE             | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 200       | 66.01%  |
| Wayland | 84        | 27.72%  |
| Unknown | 15        | 4.95%   |
| Tty     | 4         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 135       | 44.7%   |
| GDM3    | 51        | 16.89%  |
| GDM     | 39        | 12.91%  |
| SDDM    | 38        | 12.58%  |
| LightDM | 32        | 10.6%   |
| TDM     | 5         | 1.66%   |
| KDM     | 2         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 226       | 76.09%  |
| en_GB   | 33        | 11.11%  |
| Unknown | 30        | 10.1%   |
| C       | 7         | 2.36%   |
| en_AG   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 160       | 53.33%  |
| EFI  | 140       | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 226       | 76.09%  |
| Btrfs   | 33        | 11.11%  |
| Overlay | 17        | 5.72%   |
| Tmpfs   | 12        | 4.04%   |
| Unknown | 5         | 1.68%   |
| Xfs     | 3         | 1.01%   |
| Zfs     | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 144       | 48.16%  |
| GPT     | 114       | 38.13%  |
| MBR     | 41        | 13.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 258       | 87.46%  |
| Yes       | 37        | 12.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 202       | 68.47%  |
| Yes       | 93        | 31.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 125       | 42.66%  |
| Lenovo                      | 55        | 18.77%  |
| Dell                        | 43        | 14.68%  |
| ASUSTek Computer            | 12        | 4.1%    |
| Toshiba                     | 8         | 2.73%   |
| MSI                         | 5         | 1.71%   |
| Acer                        | 5         | 1.71%   |
| Gigabyte Technology         | 4         | 1.37%   |
| Unknown                     | 4         | 1.37%   |
| Samsung Electronics         | 3         | 1.02%   |
| Apple                       | 3         | 1.02%   |
| Endless                     | 2         | 0.68%   |
| Chuwi                       | 2         | 0.68%   |
| ASRock                      | 2         | 0.68%   |
| TECNO                       | 1         | 0.34%   |
| Sony                        | 1         | 0.34%   |
| SLIMBOOK                    | 1         | 0.34%   |
| Panasonic                   | 1         | 0.34%   |
| Notebook                    | 1         | 0.34%   |
| LG Electronics              | 1         | 0.34%   |
| IP3 Tech                    | 1         | 0.34%   |
| Intel                       | 1         | 0.34%   |
| Insyde                      | 1         | 0.34%   |
| IBM                         | 1         | 0.34%   |
| I-Life Digital Technologies | 1         | 0.34%   |
| HUAWEI                      | 1         | 0.34%   |
| Getac                       | 1         | 0.34%   |
| Fujitsu                     | 1         | 0.34%   |
| Foxconn                     | 1         | 0.34%   |
| EVOC                        | 1         | 0.34%   |
| EUROCOM                     | 1         | 0.34%   |
| Eluktronics                 | 1         | 0.34%   |
| Clevo                       | 1         | 0.34%   |
| AMI                         | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| HP EliteBook 840 G1               | 7         | 2.39%   |
| Unknown                           | 6         | 2.05%   |
| HP EliteBook 840 G3               | 5         | 1.71%   |
| HP EliteBook Folio 9470m          | 4         | 1.37%   |
| Dell XPS 13 9310                  | 4         | 1.37%   |
| HP ProBook 4540s                  | 3         | 1.02%   |
| HP Notebook                       | 3         | 1.02%   |
| HP EliteBook Folio 9480m          | 3         | 1.02%   |
| HP EliteBook 8460p                | 3         | 1.02%   |
| HP EliteBook 840 G2               | 3         | 1.02%   |
| HP EliteBook 2570p                | 3         | 1.02%   |
| HP 15                             | 3         | 1.02%   |
| Dell OptiPlex 7010                | 3         | 1.02%   |
| ASUS X540NA                       | 3         | 1.02%   |
| Toshiba Satellite C660            | 2         | 0.68%   |
| MSI MS-7C02                       | 2         | 0.68%   |
| Lenovo IdeaPad S340-14IIL 81VV    | 2         | 0.68%   |
| Lenovo IdeaPad 3 14ITL6 82H7      | 2         | 0.68%   |
| Lenovo G50-80 80E5                | 2         | 0.68%   |
| HP Spectre x360 Convertible       | 2         | 0.68%   |
| HP ProBook 6560b                  | 2         | 0.68%   |
| HP ProBook 640 G1                 | 2         | 0.68%   |
| HP ProBook 440 G5                 | 2         | 0.68%   |
| HP Pavilion Laptop 15-cs3xxx      | 2         | 0.68%   |
| HP ENVY 15                        | 2         | 0.68%   |
| HP EliteBook 8440p                | 2         | 0.68%   |
| HP Compaq Mini 110c-1100          | 2         | 0.68%   |
| HP 630                            | 2         | 0.68%   |
| HP 15 Notebook PC                 | 2         | 0.68%   |
| Endless EF20EA                    | 2         | 0.68%   |
| Dell Latitude E6410               | 2         | 0.68%   |
| Dell Inspiron 5767                | 2         | 0.68%   |
| Toshiba TECRA A50-A               | 1         | 0.34%   |
| Toshiba Satellite L50-B           | 1         | 0.34%   |
| Toshiba Satellite C850D-B615      | 1         | 0.34%   |
| Toshiba R84SAU2                   | 1         | 0.34%   |
| Toshiba dynabook Satellite B554/M | 1         | 0.34%   |
| Toshiba dynabook R731/E           | 1         | 0.34%   |
| TECNO WinPad 2                    | 1         | 0.34%   |
| Sony VGN-NS295J                   | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 43        | 14.68%  |
| Lenovo ThinkPad        | 26        | 8.87%   |
| HP ProBook             | 20        | 6.83%   |
| Lenovo IdeaPad         | 14        | 4.78%   |
| Dell OptiPlex          | 13        | 4.44%   |
| Dell Latitude          | 12        | 4.1%    |
| HP Compaq              | 11        | 3.75%   |
| HP Pavilion            | 10        | 3.41%   |
| Dell Inspiron          | 10        | 3.41%   |
| HP ENVY                | 9         | 3.07%   |
| HP Laptop              | 6         | 2.05%   |
| Dell XPS               | 6         | 2.05%   |
| Unknown                | 6         | 2.05%   |
| HP 15                  | 5         | 1.71%   |
| Toshiba Satellite      | 4         | 1.37%   |
| HP Spectre             | 4         | 1.37%   |
| Acer Aspire            | 4         | 1.37%   |
| Lenovo Legion          | 3         | 1.02%   |
| HP Notebook            | 3         | 1.02%   |
| ASUS X540NA            | 3         | 1.02%   |
| Toshiba dynabook       | 2         | 0.68%   |
| MSI MS-7C02            | 2         | 0.68%   |
| Lenovo ThinkCentre     | 2         | 0.68%   |
| Lenovo G50-80          | 2         | 0.68%   |
| HP ZBook               | 2         | 0.68%   |
| HP 630                 | 2         | 0.68%   |
| Endless EF20EA         | 2         | 0.68%   |
| Toshiba TECRA          | 1         | 0.34%   |
| Toshiba R84SAU2        | 1         | 0.34%   |
| TECNO WinPad           | 1         | 0.34%   |
| Sony VGN-NS295J        | 1         | 0.34%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.34%   |
| Samsung RC410          | 1         | 0.34%   |
| Samsung 300E5EV        | 1         | 0.34%   |
| Samsung 300E4C         | 1         | 0.34%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.34%   |
| Notebook P65xHP        | 1         | 0.34%   |
| MSI MS-7D31            | 1         | 0.34%   |
| MSI 500-007A           | 1         | 0.34%   |
| MSI 0A90               | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 30        | 10.24%  |
| 2018    | 27        | 9.22%   |
| 2019    | 26        | 8.87%   |
| 2016    | 25        | 8.53%   |
| 2012    | 25        | 8.53%   |
| 2015    | 24        | 8.19%   |
| 2014    | 21        | 7.17%   |
| 2017    | 20        | 6.83%   |
| 2011    | 20        | 6.83%   |
| 2020    | 18        | 6.14%   |
| 2010    | 15        | 5.12%   |
| 2021    | 11        | 3.75%   |
| 2008    | 7         | 2.39%   |
| 2022    | 6         | 2.05%   |
| 2007    | 5         | 1.71%   |
| 2009    | 3         | 1.02%   |
| 2006    | 3         | 1.02%   |
| Unknown | 3         | 1.02%   |
| 2005    | 2         | 0.68%   |
| 2004    | 2         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 223       | 76.11%  |
| Desktop     | 46        | 15.7%   |
| Convertible | 18        | 6.14%   |
| Phone       | 2         | 0.68%   |
| Mini pc     | 2         | 0.68%   |
| All in one  | 1         | 0.34%   |
| Server      | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 272       | 91.58%  |
| Enabled  | 25        | 8.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 293       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 82        | 27.61%  |
| 3.01-4.0        | 74        | 24.92%  |
| 8.01-16.0       | 46        | 15.49%  |
| 16.01-24.0      | 45        | 15.15%  |
| 1.01-2.0        | 22        | 7.41%   |
| 32.01-64.0      | 13        | 4.38%   |
| 64.01-256.0     | 5         | 1.68%   |
| 24.01-32.0      | 4         | 1.35%   |
| 0.51-1.0        | 3         | 1.01%   |
| 2.01-3.0        | 2         | 0.67%   |
| More than 256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 90        | 27.36%  |
| 1.01-2.0    | 83        | 25.23%  |
| 3.01-4.0    | 60        | 18.24%  |
| 4.01-8.0    | 59        | 17.93%  |
| 0.51-1.0    | 22        | 6.69%   |
| 8.01-16.0   | 10        | 3.04%   |
| 0.01-0.5    | 3         | 0.91%   |
| 64.01-256.0 | 1         | 0.3%    |
| Unknown     | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 231       | 77.26%  |
| 2      | 51        | 17.06%  |
| 4      | 5         | 1.67%   |
| 3      | 5         | 1.67%   |
| 0      | 3         | 1%      |
| 10     | 1         | 0.33%   |
| 8      | 1         | 0.33%   |
| 6      | 1         | 0.33%   |
| 5      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 63.48%  |
| Yes       | 107       | 36.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 81.91%  |
| No        | 53        | 18.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 87.76%  |
| No        | 36        | 12.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 202       | 68.24%  |
| No        | 94        | 31.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 293       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Computers | Percent |
|-----------|-----------|---------|
| Nairobi   | 274       | 90.73%  |
| Mombasa   | 4         | 1.32%   |
| Nakuru    | 3         | 0.99%   |
| Kiambu    | 3         | 0.99%   |
| Nyeri     | 2         | 0.66%   |
| Kikuyu    | 2         | 0.66%   |
| Eldoret   | 2         | 0.66%   |
| Wote      | 1         | 0.33%   |
| Rongai    | 1         | 0.33%   |
| Nyahururu | 1         | 0.33%   |
| Narok     | 1         | 0.33%   |
| Nanyuki   | 1         | 0.33%   |
| Murang'a  | 1         | 0.33%   |
| Maralal   | 1         | 0.33%   |
| Machakos  | 1         | 0.33%   |
| Kisii     | 1         | 0.33%   |
| Kericho   | 1         | 0.33%   |
| Kabarnet  | 1         | 0.33%   |
| Embakasi  | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 86        | 113    | 24.02%  |
| WDC                         | 47        | 57     | 13.13%  |
| Toshiba                     | 40        | 45     | 11.17%  |
| Samsung Electronics         | 40        | 59     | 11.17%  |
| HGST                        | 21        | 34     | 5.87%   |
| Unknown                     | 19        | 26     | 5.31%   |
| SanDisk                     | 14        | 17     | 3.91%   |
| Hitachi                     | 12        | 15     | 3.35%   |
| Intel                       | 7         | 9      | 1.96%   |
| Micron Technology           | 6         | 7      | 1.68%   |
| Crucial                     | 6         | 8      | 1.68%   |
| SPCC                        | 5         | 9      | 1.4%    |
| MARSHAL                     | 5         | 5      | 1.4%    |
| Lexar                       | 5         | 5      | 1.4%    |
| SK hynix                    | 4         | 5      | 1.12%   |
| Kingston                    | 4         | 6      | 1.12%   |
| Unknown                     | 4         | 4      | 1.12%   |
| Maxtor                      | 3         | 3      | 0.84%   |
| Team                        | 2         | 2      | 0.56%   |
| LITEON                      | 2         | 2      | 0.56%   |
| KIOXIA                      | 2         | 2      | 0.56%   |
| HUAWEI                      | 2         | 2      | 0.56%   |
| China                       | 2         | 2      | 0.56%   |
| Apple                       | 2         | 2      | 0.56%   |
| A-DATA Technology           | 2         | 2      | 0.56%   |
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
| KINGBANK                    | 1         | 1      | 0.28%   |
| Hjwdz                       | 1         | 1      | 0.28%   |
| Golden                      | 1         | 1      | 0.28%   |
| FZ                          | 1         | 1      | 0.28%   |
| Eluktro                     | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 14        | 3.74%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 1.87%   |
| Seagate ST500LT012-9WS142 500GB                   | 7         | 1.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 7         | 1.87%   |
| HGST HTS725050A7E630 500GB                        | 7         | 1.87%   |
| Seagate ST9500325AS 500GB                         | 6         | 1.6%    |
| Unknown MMC Card  64GB                            | 5         | 1.34%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.34%   |
| Samsung NVMe SSD Drive 512GB                      | 5         | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5         | 1.34%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.07%   |
| Seagate ST500LT012-1DG142 500GB                   | 4         | 1.07%   |
| Seagate ST500LM021-1KJ152 500GB                   | 4         | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                   | 4         | 1.07%   |
| Samsung SSD 960 EVO 1TB                           | 4         | 1.07%   |
| Unknown                                           | 4         | 1.07%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 3         | 0.8%    |
| WDC WD3200AAJS-56M0A0 320GB                       | 3         | 0.8%    |
| WDC PC SN730 NVMe 512GB                           | 3         | 0.8%    |
| Unknown MMC Card  32GB                            | 3         | 0.8%    |
| Toshiba MQ01ABD050V 500GB                         | 3         | 0.8%    |
| SPCC M.2 PCIe SSD 512GB                           | 3         | 0.8%    |
| Seagate ST3320418AS 320GB                         | 3         | 0.8%    |
| MARSHAL MAL2500SA-T54L 500GB                      | 3         | 0.8%    |
| HGST HTS541010A9E680 1TB                          | 3         | 0.8%    |
| Crucial CT2050MX300SSD1 2TB                       | 3         | 0.8%    |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 2         | 0.53%   |
| WDC WD2500BEKT-75PVMT0 250GB                      | 2         | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.53%   |
| Unknown NCard  32GB                               | 2         | 0.53%   |
| Unknown MMC Card                                  | 2         | 0.53%   |
| Toshiba DT01ACA100 1TB                            | 2         | 0.53%   |
| Team T253X2001T 1024GB SSD                        | 2         | 0.53%   |
| SPCC Solid State Disk 256GB                       | 2         | 0.53%   |
| Seagate ST500VT000-1DK142 500GB                   | 2         | 0.53%   |
| Seagate ST500VT000-1BS142 500GB                   | 2         | 0.53%   |
| Seagate ST500LM030-1RK17D 500GB                   | 2         | 0.53%   |
| Seagate ST3250318AS 250GB                         | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 112    | 42.29%  |
| WDC                 | 38        | 47     | 18.91%  |
| Toshiba             | 33        | 38     | 16.42%  |
| HGST                | 21        | 34     | 10.45%  |
| Hitachi             | 12        | 15     | 5.97%   |
| MARSHAL             | 5         | 5      | 2.49%   |
| Maxtor              | 3         | 3      | 1.49%   |
| Samsung Electronics | 2         | 2      | 1%      |
| Unknown             | 1         | 1      | 0.5%    |
| Unknown             | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 18     | 17.14%  |
| SanDisk             | 10        | 11     | 14.29%  |
| Crucial             | 6         | 8      | 8.57%   |
| Micron Technology   | 4         | 5      | 5.71%   |
| Lexar               | 4         | 4      | 5.71%   |
| WDC                 | 3         | 4      | 4.29%   |
| Toshiba             | 3         | 3      | 4.29%   |
| Kingston            | 3         | 5      | 4.29%   |
| Intel               | 3         | 3      | 4.29%   |
| Team                | 2         | 2      | 2.86%   |
| SPCC                | 2         | 3      | 2.86%   |
| LITEON              | 2         | 2      | 2.86%   |
| China               | 2         | 2      | 2.86%   |
| Unknown             | 2         | 2      | 2.86%   |
| TCSUNBOW            | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| Plextor             | 1         | 1      | 1.43%   |
| Netac               | 1         | 1      | 1.43%   |
| MAX                 | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| KINGBANK            | 1         | 1      | 1.43%   |
| Golden              | 1         | 1      | 1.43%   |
| FZ                  | 1         | 1      | 1.43%   |
| Eluktro             | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 181       | 258    | 53.71%  |
| NVMe    | 67        | 88     | 19.88%  |
| SSD     | 66        | 84     | 19.58%  |
| MMC     | 18        | 24     | 5.34%   |
| Unknown | 5         | 8      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 228       | 345    | 71.7%   |
| NVMe | 67        | 88     | 21.07%  |
| MMC  | 18        | 24     | 5.66%   |
| SAS  | 5         | 5      | 1.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 229    | 66.53%  |
| 0.51-1.0   | 69        | 85     | 27.82%  |
| 1.01-2.0   | 9         | 19     | 3.63%   |
| 3.01-4.0   | 2         | 5      | 0.81%   |
| 4.01-10.0  | 2         | 3      | 0.81%   |
| 2.01-3.0   | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 79        | 25.4%   |
| 101-250        | 77        | 24.76%  |
| 501-1000       | 54        | 17.36%  |
| 51-100         | 30        | 9.65%   |
| 1001-2000      | 22        | 7.07%   |
| Unknown        | 13        | 4.18%   |
| 1-20           | 12        | 3.86%   |
| More than 3000 | 8         | 2.57%   |
| 21-50          | 8         | 2.57%   |
| 2001-3000      | 8         | 2.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 85        | 26.65%  |
| 21-50          | 56        | 17.55%  |
| 101-250        | 55        | 17.24%  |
| 51-100         | 47        | 14.73%  |
| 251-500        | 33        | 10.34%  |
| 501-1000       | 15        | 4.7%    |
| Unknown        | 13        | 4.08%   |
| 1001-2000      | 10        | 3.13%   |
| More than 3000 | 4         | 1.25%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050V 500GB             | 3         | 3      | 6.82%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 6.82%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 4.55%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.55%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 4.55%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 4.55%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 2.27%   |
| WDC WD5000AZLX-08K2TA0 500GB          | 1         | 1      | 2.27%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 2.27%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 2.27%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.27%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 2.27%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 2.27%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 2.27%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.27%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.27%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.27%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 2.27%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.27%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 2.27%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 2.27%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.27%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 2.27%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 2.27%   |
| HGST HTS721010A9 1TB                  | 1         | 2      | 2.27%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.27%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 2.27%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 2.27%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 2.27%   |
| Unknown                               | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 14        | 14     | 32.56%  |
| Toshiba  | 9         | 9      | 20.93%  |
| WDC      | 7         | 7      | 16.28%  |
| HGST     | 6         | 10     | 13.95%  |
| MARSHAL  | 2         | 2      | 4.65%   |
| Hitachi  | 2         | 3      | 4.65%   |
| SK hynix | 1         | 1      | 2.33%   |
| Crucial  | 1         | 2      | 2.33%   |
| Unknown  | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 34.15%  |
| Toshiba | 9         | 9      | 21.95%  |
| WDC     | 7         | 7      | 17.07%  |
| HGST    | 6         | 10     | 14.63%  |
| MARSHAL | 2         | 2      | 4.88%   |
| Hitachi | 2         | 3      | 4.88%   |
| Unknown | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 46     | 95.24%  |
| SSD  | 2         | 3      | 4.76%   |

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
| Detected | 173       | 258    | 56.17%  |
| Works    | 94        | 155    | 30.52%  |
| Malfunc  | 41        | 49     | 13.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 242       | 73.56%  |
| Samsung Electronics          | 29        | 8.81%   |
| AMD                          | 16        | 4.86%   |
| SanDisk                      | 10        | 3.04%   |
| Toshiba America Info Systems | 4         | 1.22%   |
| Silicon Motion               | 4         | 1.22%   |
| SK hynix                     | 3         | 0.91%   |
| Shenzhen Longsys Electronics | 2         | 0.61%   |
| Micron Technology            | 2         | 0.61%   |
| LSI Logic / Symbios Logic    | 2         | 0.61%   |
| KIOXIA                       | 2         | 0.61%   |
| ASMedia Technology           | 2         | 0.61%   |
| Union Memory (Shenzhen)      | 1         | 0.3%    |
| Realtek Semiconductor        | 1         | 0.3%    |
| Micron/Crucial Technology    | 1         | 0.3%    |
| MAXIO Technology (Hangzhou)  | 1         | 0.3%    |
| Marvell Technology Group     | 1         | 0.3%    |
| Lite-On Technology           | 1         | 0.3%    |
| Kingston Technology Company  | 1         | 0.3%    |
| JMicron Technology           | 1         | 0.3%    |
| Broadcom / LSI               | 1         | 0.3%    |
| Apple                        | 1         | 0.3%    |
| ADATA Technology             | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 36        | 10%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 6.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 3.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 3.61%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6         | 1.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.39%   |
| Intel SATA Controller [RAID mode]                                                | 5         | 1.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.11%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3         | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.56%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.56%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 210       | 62.31%  |
| NVMe | 67        | 19.88%  |
| RAID | 32        | 9.5%    |
| IDE  | 27        | 8.01%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 269       | 91.81%  |
| AMD    | 22        | 7.51%   |
| ARM    | 2         | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 2.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 2.05%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 2.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 6         | 2.05%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.05%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 6         | 2.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.37%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 1.37%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 4         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.37%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.37%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.02%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.02%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.02%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.02%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.02%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.02%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.02%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.68%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.68%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.68%   |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.68%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 90        | 30.72%  |
| Intel Core i7           | 68        | 23.21%  |
| Intel Core i3           | 27        | 9.22%   |
| Intel Celeron           | 23        | 7.85%   |
| Other                   | 17        | 5.8%    |
| Intel Atom              | 9         | 3.07%   |
| Intel Core 2 Duo        | 7         | 2.39%   |
| AMD Ryzen 7             | 7         | 2.39%   |
| AMD Ryzen 5             | 6         | 2.05%   |
| Intel Pentium 4         | 5         | 1.71%   |
| Intel Pentium           | 5         | 1.71%   |
| Intel Xeon              | 4         | 1.37%   |
| Intel Pentium Dual-Core | 3         | 1.02%   |
| Intel Core i9           | 3         | 1.02%   |
| Intel Core 2            | 3         | 1.02%   |
| Intel Core 2 Quad       | 2         | 0.68%   |
| AMD FX                  | 2         | 0.68%   |
| AMD A10                 | 2         | 0.68%   |
| Intel Pentium Gold      | 1         | 0.34%   |
| Intel Pentium Dual      | 1         | 0.34%   |
| Intel Genuine           | 1         | 0.34%   |
| Intel Core m3           | 1         | 0.34%   |
| ARM AArch64             | 1         | 0.34%   |
| AMD Ryzen Threadripper  | 1         | 0.34%   |
| AMD Ryzen 9             | 1         | 0.34%   |
| AMD Phenom II X3        | 1         | 0.34%   |
| AMD E2                  | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 169       | 57.68%  |
| 4       | 83        | 28.33%  |
| 6       | 12        | 4.1%    |
| 8       | 10        | 3.41%   |
| 1       | 8         | 2.73%   |
| 3       | 3         | 1.02%   |
| 10      | 2         | 0.68%   |
| 32      | 1         | 0.34%   |
| 20      | 1         | 0.34%   |
| 16      | 1         | 0.34%   |
| 14      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 291       | 99.32%  |
| 2      | 2         | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 224       | 76.45%  |
| 1       | 68        | 23.21%  |
| Unknown | 1         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 289       | 98.63%  |
| 32-bit         | 3         | 1.02%   |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 31.17%  |
| 0x306a9    | 26        | 8.44%   |
| 0x206a7    | 20        | 6.49%   |
| 0x40651    | 15        | 4.87%   |
| 0x406e3    | 14        | 4.55%   |
| 0x306c3    | 11        | 3.57%   |
| 0x806c1    | 9         | 2.92%   |
| 0x806ea    | 8         | 2.6%    |
| 0x306d4    | 8         | 2.6%    |
| 0x806ec    | 7         | 2.27%   |
| 0x906ea    | 6         | 1.95%   |
| 0x30678    | 6         | 1.95%   |
| 0x20655    | 6         | 1.95%   |
| 0x1067a    | 6         | 1.95%   |
| 0x706e5    | 5         | 1.62%   |
| 0x506e3    | 4         | 1.3%    |
| 0x406c4    | 4         | 1.3%    |
| 0x806e9    | 3         | 0.97%   |
| 0x706a8    | 3         | 0.97%   |
| 0x0800820d | 3         | 0.97%   |
| 0x906e9    | 2         | 0.65%   |
| 0x806eb    | 2         | 0.65%   |
| 0x706a1    | 2         | 0.65%   |
| 0x6fd      | 2         | 0.65%   |
| 0x6f6      | 2         | 0.65%   |
| 0x406c3    | 2         | 0.65%   |
| 0x106c2    | 2         | 0.65%   |
| 0x10676    | 2         | 0.65%   |
| 0x08608103 | 2         | 0.65%   |
| 0x08600106 | 2         | 0.65%   |
| 0xf65      | 1         | 0.32%   |
| 0xf49      | 1         | 0.32%   |
| 0xf43      | 1         | 0.32%   |
| 0xf41      | 1         | 0.32%   |
| 0xa0652    | 1         | 0.32%   |
| 0x906ec    | 1         | 0.32%   |
| 0x906a4    | 1         | 0.32%   |
| 0x90661    | 1         | 0.32%   |
| 0x806c2    | 1         | 0.32%   |
| 0x6fa      | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 16.38%  |
| Haswell          | 40        | 13.65%  |
| IvyBridge        | 29        | 9.9%    |
| Skylake          | 28        | 9.56%   |
| SandyBridge      | 22        | 7.51%   |
| Silvermont       | 16        | 5.46%   |
| Broadwell        | 14        | 4.78%   |
| TigerLake        | 12        | 4.1%    |
| Westmere         | 11        | 3.75%   |
| IceLake          | 9         | 3.07%   |
| Penryn           | 8         | 2.73%   |
| Core             | 8         | 2.73%   |
| Zen+             | 6         | 2.05%   |
| Goldmont plus    | 6         | 2.05%   |
| Zen 2            | 5         | 1.71%   |
| NetBurst         | 5         | 1.71%   |
| Goldmont         | 4         | 1.37%   |
| Alderlake Hybrid | 4         | 1.37%   |
| Unknown          | 4         | 1.37%   |
| Zen 3            | 2         | 0.68%   |
| Piledriver       | 2         | 0.68%   |
| Excavator        | 2         | 0.68%   |
| Bonnell          | 2         | 0.68%   |
| Tremont          | 1         | 0.34%   |
| Steamroller      | 1         | 0.34%   |
| P6               | 1         | 0.34%   |
| K10              | 1         | 0.34%   |
| CometLake        | 1         | 0.34%   |
| Bobcat           | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 245       | 75.38%  |
| Nvidia                     | 40        | 12.31%  |
| AMD                        | 39        | 12%     |
| Matrox Electronics Systems | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 6.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 6.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 6.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.01%   |
| Intel HD Graphics 5500                                                                   | 14        | 4.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.9%    |
| Intel UHD Graphics 620                                                                   | 12        | 3.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.3%    |
| Intel HD Graphics 620                                                                    | 10        | 3%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.1%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.2%    |
| Intel HD Graphics 500                                                                    | 4         | 1.2%    |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.9%    |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.9%    |
| Intel HD Graphics 530                                                                    | 3         | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.9%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.6%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.6%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.6%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.6%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.6%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 211       | 71.53%  |
| 1 x AMD        | 26        | 8.81%   |
| 1 x Nvidia     | 22        | 7.46%   |
| Intel + Nvidia | 17        | 5.76%   |
| Intel + AMD    | 12        | 4.07%   |
| 2 x Intel      | 3         | 1.02%   |
| Other          | 2         | 0.68%   |
| 2 x AMD        | 1         | 0.34%   |
| 1 x Matrox     | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 276       | 93.56%  |
| Proprietary | 15        | 5.08%   |
| Unknown     | 4         | 1.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 232       | 78.11%  |
| 1.01-2.0   | 21        | 7.07%   |
| 0.01-0.5   | 17        | 5.72%   |
| 3.01-4.0   | 10        | 3.37%   |
| 0.51-1.0   | 8         | 2.69%   |
| 7.01-8.0   | 7         | 2.36%   |
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
| AU Optronics            | 65        | 21.31%  |
| Chimei Innolux          | 44        | 14.43%  |
| BOE                     | 35        | 11.48%  |
| LG Display              | 34        | 11.15%  |
| Hewlett-Packard         | 27        | 8.85%   |
| Samsung Electronics     | 24        | 7.87%   |
| Dell                    | 15        | 4.92%   |
| Sharp                   | 7         | 2.3%    |
| InfoVision              | 7         | 2.3%    |
| Sony                    | 5         | 1.64%   |
| Lenovo                  | 5         | 1.64%   |
| Chi Mei Optoelectronics | 5         | 1.64%   |
| Apple                   | 4         | 1.31%   |
| LG Philips              | 3         | 0.98%   |
| KDC                     | 3         | 0.98%   |
| HannStar                | 3         | 0.98%   |
| Unknown (XXX)           | 2         | 0.66%   |
| NEC Computers           | 2         | 0.66%   |
| CSO                     | 2         | 0.66%   |
| BenQ                    | 2         | 0.66%   |
| Acer                    | 2         | 0.66%   |
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
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.62%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 5         | 1.62%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 1.62%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 0.97%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.97%   |
| Sony TV SNY6F02 1360x768                                                 | 2         | 0.65%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch        | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.65%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.65%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                     | 2         | 0.65%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.65%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch               | 2         | 0.65%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.65%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.65%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.65%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                    | 1         | 0.32%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080    | 1         | 0.32%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.32%   |
| Unknown (XXX) Beyond TV XXX2851 2560x1440 1209x680mm 54.6-inch           | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 114       | 38.51%  |
| 1920x1080 (FHD)    | 97        | 32.77%  |
| 1600x900 (HD+)     | 21        | 7.09%   |
| 1280x1024 (SXGA)   | 10        | 3.38%   |
| 3840x2160 (4K)     | 9         | 3.04%   |
| 1920x1200 (WUXGA)  | 6         | 2.03%   |
| 1440x900 (WXGA+)   | 6         | 2.03%   |
| 1280x800 (WXGA)    | 6         | 2.03%   |
| 2560x1440 (QHD)    | 4         | 1.35%   |
| 1680x1050 (WSXGA+) | 3         | 1.01%   |
| 1360x768           | 3         | 1.01%   |
| 3840x2400          | 2         | 0.68%   |
| 1024x768 (XGA)     | 2         | 0.68%   |
| 1024x600           | 2         | 0.68%   |
| Unknown            | 2         | 0.68%   |
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
| 15      | 88        | 29.04%  |
| 13      | 62        | 20.46%  |
| 14      | 50        | 16.5%   |
| 12      | 11        | 3.63%   |
| 21      | 10        | 3.3%    |
| 17      | 9         | 2.97%   |
| 11      | 9         | 2.97%   |
| 19      | 8         | 2.64%   |
| 27      | 7         | 2.31%   |
| 23      | 7         | 2.31%   |
| 24      | 6         | 1.98%   |
| 18      | 6         | 1.98%   |
| 72      | 4         | 1.32%   |
| 20      | 4         | 1.32%   |
| 22      | 3         | 0.99%   |
| 10      | 3         | 0.99%   |
| Unknown | 3         | 0.99%   |
| 84      | 2         | 0.66%   |
| 46      | 2         | 0.66%   |
| 34      | 2         | 0.66%   |
| 16      | 2         | 0.66%   |
| 54      | 1         | 0.33%   |
| 42      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 31      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 176       | 58.86%  |
| 201-300     | 51        | 17.06%  |
| 501-600     | 21        | 7.02%   |
| 401-500     | 21        | 7.02%   |
| 351-400     | 13        | 4.35%   |
| 1501-2000   | 6         | 2.01%   |
| Unknown     | 3         | 1%      |
| 801-900     | 2         | 0.67%   |
| 1001-1500   | 2         | 0.67%   |
| 901-1000    | 2         | 0.67%   |
| 701-800     | 1         | 0.33%   |
| 601-700     | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 239       | 82.99%  |
| 16/10   | 30        | 10.42%  |
| 5/4     | 10        | 3.47%   |
| Unknown | 3         | 1.04%   |
| 4/3     | 2         | 0.69%   |
| 3/2     | 2         | 0.69%   |
| 21/9    | 2         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 28.9%   |
| 81-90          | 85        | 28.24%  |
| 71-80          | 27        | 8.97%   |
| 201-250        | 18        | 5.98%   |
| 151-200        | 15        | 4.98%   |
| 61-70          | 11        | 3.65%   |
| 141-150        | 10        | 3.32%   |
| 51-60          | 9         | 2.99%   |
| More than 1000 | 7         | 2.33%   |
| 301-350        | 7         | 2.33%   |
| 251-300        | 5         | 1.66%   |
| 501-1000       | 4         | 1.33%   |
| 351-500        | 3         | 1%      |
| 41-50          | 3         | 1%      |
| 121-130        | 3         | 1%      |
| Unknown        | 3         | 1%      |
| 111-120        | 2         | 0.66%   |
| 131-140        | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 100       | 33.9%   |
| 121-160       | 97        | 32.88%  |
| 51-100        | 58        | 19.66%  |
| 161-240       | 22        | 7.46%   |
| More than 240 | 8         | 2.71%   |
| 1-50          | 7         | 2.37%   |
| Unknown       | 3         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 251       | 83.39%  |
| 2     | 39        | 12.96%  |
| 0     | 10        | 3.32%   |
| 3     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 178       | 40.36%  |
| Realtek Semiconductor             | 123       | 27.89%  |
| Qualcomm Atheros                  | 49        | 11.11%  |
| Broadcom                          | 25        | 5.67%   |
| MediaTek                          | 9         | 2.04%   |
| Hewlett-Packard                   | 8         | 1.81%   |
| Broadcom Limited                  | 7         | 1.59%   |
| Samsung Electronics               | 6         | 1.36%   |
| Ralink                            | 5         | 1.13%   |
| OPPO Electronics                  | 4         | 0.91%   |
| Huawei Technologies               | 4         | 0.91%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.68%   |
| Xiaomi                            | 3         | 0.68%   |
| Sierra Wireless                   | 3         | 0.68%   |
| Ralink Technology                 | 3         | 0.68%   |
| Marvell Technology Group          | 3         | 0.68%   |
| T & A Mobile Phones               | 2         | 0.45%   |
| Ericsson Business Mobile Networks | 2         | 0.45%   |
| Spreadtrum Communications         | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| LSI                               | 1         | 0.23%   |
| IBM                               | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 12.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 4.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 4.17%   |
| Intel Wireless 7260                                                    | 22        | 3.99%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 2.54%   |
| Intel Wireless 8260                                                    | 14        | 2.54%   |
| Intel Wireless 7265                                                    | 13        | 2.36%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 2.36%   |
| Intel Wireless 8265 / 8275                                             | 12        | 2.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 11        | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.81%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.45%   |
| MediaTek File-CD Gadget                                                | 8         | 1.45%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 7         | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 6         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.91%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.91%   |
| Intel Centrino Advanced-N 6200                                         | 5         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.73%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 4         | 0.73%   |
| Intel Wireless 3160                                                    | 4         | 0.73%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.73%   |
| HP lt4112 Gobi 4G Module Network Device                                | 4         | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 0.73%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                          | 3         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 144       | 52.94%  |
| Realtek Semiconductor             | 48        | 17.65%  |
| Qualcomm Atheros                  | 43        | 15.81%  |
| Broadcom                          | 19        | 6.99%   |
| Ralink                            | 5         | 1.84%   |
| Hewlett-Packard                   | 5         | 1.84%   |
| Sierra Wireless                   | 3         | 1.1%    |
| Ralink Technology                 | 3         | 1.1%    |
| Ericsson Business Mobile Networks | 1         | 0.37%   |
| Broadcom Limited                  | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 22        | 8.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 5.15%   |
| Intel Wireless 8260                                            | 14        | 5.15%   |
| Intel Wireless 7265                                            | 13        | 4.78%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.68%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 3.31%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 2.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 2.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 6         | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.84%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.47%   |
| Intel Wireless 3160                                            | 4         | 1.47%   |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.1%    |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.74%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.74%   |
| Intel Wireless 3165                                            | 2         | 0.74%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 113       | 41.39%  |
| Realtek Semiconductor      | 99        | 36.26%  |
| Qualcomm Atheros           | 9         | 3.3%    |
| MediaTek                   | 9         | 3.3%    |
| Broadcom                   | 7         | 2.56%   |
| Samsung Electronics        | 6         | 2.2%    |
| Broadcom Limited           | 6         | 2.2%    |
| OPPO Electronics           | 4         | 1.47%   |
| ZTE WCDMA Technologies MSM | 3         | 1.1%    |
| Xiaomi                     | 3         | 1.1%    |
| Marvell Technology Group   | 3         | 1.1%    |
| Hewlett-Packard            | 3         | 1.1%    |
| T & A Mobile Phones        | 2         | 0.73%   |
| Huawei Technologies        | 2         | 0.73%   |
| Spreadtrum Communications  | 1         | 0.37%   |
| Qualcomm                   | 1         | 0.37%   |
| LSI                        | 1         | 0.37%   |
| IBM                        | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 24.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 9.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 8.33%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 5.8%    |
| Intel Ethernet Connection I219-LM                                      | 13        | 4.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 2.9%    |
| MediaTek File-CD Gadget                                                | 8         | 2.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 2.17%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.81%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.81%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 4         | 1.45%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.45%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.45%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.45%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                          | 3         | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.09%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.09%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.09%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 3         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.72%   |
| T & A Mobile Phones TCL 30 XE 5G                                       | 2         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.72%   |
| MediaTek moto e22                                                      | 2         | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2         | 0.72%   |
| Huawei E353/E3131                                                      | 2         | 0.72%   |
| HP lt4120 Snapdragon X5 LTE                                            | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.36%   |
| Spreadtrum Unisoc Phone                                                | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.36%   |
| Qualcomm Android                                                       | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 258       | 51.5%   |
| Ethernet | 240       | 47.9%   |
| Modem    | 3         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 216       | 72.97%  |
| Ethernet | 80        | 27.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 181       | 61.56%  |
| 1     | 96        | 32.65%  |
| 0     | 11        | 3.74%   |
| 3     | 4         | 1.36%   |
| 6     | 1         | 0.34%   |
| 4     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 286       | 97.61%  |
| Yes  | 7         | 2.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 57.64%  |
| Qualcomm Atheros Communications | 25        | 12.32%  |
| Realtek Semiconductor           | 19        | 9.36%   |
| Broadcom                        | 12        | 5.91%   |
| Ralink                          | 4         | 1.97%   |
| Lite-On Technology              | 4         | 1.97%   |
| IMC Networks                    | 4         | 1.97%   |
| Hewlett-Packard                 | 4         | 1.97%   |
| Cambridge Silicon Radio         | 3         | 1.48%   |
| Toshiba                         | 2         | 0.99%   |
| Dell                            | 2         | 0.99%   |
| Apple                           | 2         | 0.99%   |
| Taiyo Yuden                     | 1         | 0.49%   |
| Realtek                         | 1         | 0.49%   |
| Foxconn / Hon Hai               | 1         | 0.49%   |
| Alps Electric                   | 1         | 0.49%   |
| Unknown                         | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 65        | 32.02%  |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.9%    |
| Intel AX201 Bluetooth                               | 14        | 6.9%    |
| Realtek Bluetooth Radio                             | 13        | 6.4%    |
| Intel AX200 Bluetooth                               | 9         | 4.43%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.46%   |
| Intel Bluetooth Device                              | 5         | 2.46%   |
| Broadcom HP Portable SoftSailing                    | 5         | 2.46%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.97%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.48%   |
| IMC Networks Bluetooth Device                       | 3         | 1.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.48%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.99%   |
| Lite-On Bluetooth Device                            | 2         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.99%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.99%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.49%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.49%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.49%   |
| Realtek Bluetooth Radio                             | 1         | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.49%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.49%   |
| Intel AX210 Bluetooth                               | 1         | 0.49%   |
| IMC Networks Bluetooth                              | 1         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.49%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.49%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 259       | 78.01%  |
| AMD                         | 29        | 8.73%   |
| Nvidia                      | 24        | 7.23%   |
| Texas Instruments           | 3         | 0.9%    |
| Generalplus Technology      | 3         | 0.9%    |
| Realtek Semiconductor       | 2         | 0.6%    |
| Lenovo                      | 2         | 0.6%    |
| C-Media Electronics         | 2         | 0.6%    |
| Turtle Beach                | 1         | 0.3%    |
| Micro Star International    | 1         | 0.3%    |
| Medeli Electronics          | 1         | 0.3%    |
| JMTek                       | 1         | 0.3%    |
| GN Netcom                   | 1         | 0.3%    |
| Giga-Byte Technology        | 1         | 0.3%    |
| FiiO Electronics Technology | 1         | 0.3%    |
| Apple                       | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 47        | 11.78%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 5.51%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 4.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 3.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 3.51%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 3.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.25%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1%      |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.75%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Lenovo T2224zD                                                                                    | 2         | 0.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.5%    |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.5%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 30.73%  |
| SK hynix            | 51        | 24.88%  |
| Micron Technology   | 24        | 11.71%  |
| Kingston            | 15        | 7.32%   |
| Unknown             | 13        | 6.34%   |
| Crucial             | 11        | 5.37%   |
| Elpida              | 7         | 3.41%   |
| Ramaxel Technology  | 5         | 2.44%   |
| A-DATA Technology   | 3         | 1.46%   |
| G.Skill             | 2         | 0.98%   |
| Apacer              | 2         | 0.98%   |
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
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 3.3%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 7         | 3.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 4         | 1.89%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 1.42%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 1.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 1.42%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 1.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 0.94%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.94%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.94%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.94%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 0.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.94%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.94%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.94%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 2         | 0.94%   |
| Apacer RAM 76.A302G.C4D0B 2GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                      | 1         | 0.47%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s             | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 72        | 45.57%  |
| DDR4   | 60        | 37.97%  |
| LPDDR4 | 7         | 4.43%   |
| DDR2   | 6         | 3.8%    |
| LPDDR3 | 5         | 3.16%   |
| SDRAM  | 4         | 2.53%   |
| DDR5   | 2         | 1.27%   |
| DDR    | 2         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 120       | 73.17%  |
| Row Of Chips | 20        | 12.2%   |
| DIMM         | 18        | 10.98%  |
| Chip         | 6         | 3.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 38.12%  |
| 8192  | 52        | 28.73%  |
| 16384 | 24        | 13.26%  |
| 2048  | 24        | 13.26%  |
| 1024  | 7         | 3.87%   |
| 32768 | 4         | 2.21%   |
| 512   | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 59        | 33.52%  |
| 2667    | 32        | 18.18%  |
| 3200    | 15        | 8.52%   |
| 2133    | 11        | 6.25%   |
| 1333    | 11        | 6.25%   |
| 1334    | 9         | 5.11%   |
| 4267    | 7         | 3.98%   |
| 2400    | 6         | 3.41%   |
| 1867    | 4         | 2.27%   |
| 667     | 4         | 2.27%   |
| 3600    | 2         | 1.14%   |
| 3266    | 2         | 1.14%   |
| 800     | 2         | 1.14%   |
| Unknown | 2         | 1.14%   |
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
| Chicony Electronics                    | 69        | 29.87%  |
| Cheng Uei Precision Industry (Foxlink) | 31        | 13.42%  |
| Realtek Semiconductor                  | 14        | 6.06%   |
| Lite-On Technology                     | 14        | 6.06%   |
| Bison Electronics                      | 14        | 6.06%   |
| Sunplus Innovation Technology          | 13        | 5.63%   |
| IMC Networks                           | 12        | 5.19%   |
| Syntek                                 | 11        | 4.76%   |
| Microdia                               | 10        | 4.33%   |
| Acer                                   | 5         | 2.16%   |
| Quanta                                 | 4         | 1.73%   |
| Apple                                  | 4         | 1.73%   |
| Silicon Motion                         | 3         | 1.3%    |
| Samsung Electronics                    | 3         | 1.3%    |
| Logitech                               | 3         | 1.3%    |
| Unknown                                | 2         | 0.87%   |
| Suyin                                  | 2         | 0.87%   |
| Ricoh                                  | 2         | 0.87%   |
| Luxvisions Innotech Limited            | 2         | 0.87%   |
| Importek                               | 2         | 0.87%   |
| Alcor Micro                            | 2         | 0.87%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
| Xiaomi                                 | 1         | 0.43%   |
| USB Camera                             | 1         | 0.43%   |
| Primax Electronics                     | 1         | 0.43%   |
| MacroSilicon                           | 1         | 0.43%   |
| LG Electronics                         | 1         | 0.43%   |
| DigiTech                               | 1         | 0.43%   |
| Cubeternet                             | 1         | 0.43%   |
| ALi                                    | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 15        | 6.44%   |
| Chicony HP HD Webcam                                                       | 8         | 3.43%   |
| Syntek Integrated Camera                                                   | 7         | 3%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3%      |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.58%   |
| Lite-On HP HD Webcam                                                       | 6         | 2.58%   |
| Lite-On HP HD Camera                                                       | 6         | 2.58%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.58%   |
| Chicony USB 2.0 Camera                                                     | 5         | 2.15%   |
| Chicony HP HD Webcam [Fixed]                                               | 5         | 2.15%   |
| Chicony HP HD Camera                                                       | 5         | 2.15%   |
| Bison Integrated Camera                                                    | 5         | 2.15%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.72%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.29%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.29%   |
| Realtek Integrated Webcam                                                  | 3         | 1.29%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.29%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 1.29%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 1.29%   |
| Chicony HD Webcam                                                          | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 3         | 1.29%   |
| Bison ThinkPad P50 Integrated Camera                                       | 3         | 1.29%   |
| Unknown USB Camera                                                         | 2         | 0.86%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.86%   |
| Syntek EasyCamera                                                          | 2         | 0.86%   |
| Sunplus HP Truevision Full HD                                              | 2         | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.86%   |
| Realtek FULL HD 1080P Webcam                                               | 2         | 0.86%   |
| Logitech Webcam C270                                                       | 2         | 0.86%   |
| Importek HP Webcam-50                                                      | 2         | 0.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 0.86%   |
| IMC Networks Integrated Camera                                             | 2         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.86%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.86%   |
| Chicony HP Webcam                                                          | 2         | 0.86%   |
| Chicony HP Truevision HD                                                   | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 53        | 68.83%  |
| Synaptics                  | 14        | 18.18%  |
| Shenzhen Goodix Technology | 6         | 7.79%   |
| AuthenTec                  | 2         | 2.6%    |
| LighTuning Technology      | 1         | 1.3%    |
| Elan Microelectronics      | 1         | 1.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 24.68%  |
| Validity Sensors VFS491                                                    | 10        | 12.99%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 5.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 5.19%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.9%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.9%    |
| Synaptics WBDI Device                                                      | 3         | 3.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 2.6%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.6%    |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.3%    |
| Synaptics UWP WBDI                                                         | 1         | 1.3%    |
| Synaptics  WBDI                                                            | 1         | 1.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.3%    |
| Elan ELAN:ARM-M4                                                           | 1         | 1.3%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.3%    |

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
| 0     | 183       | 61.82%  |
| 1     | 92        | 31.08%  |
| 2     | 19        | 6.42%   |
| 3     | 2         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 76        | 55.88%  |
| Graphics card            | 16        | 11.76%  |
| Chipcard                 | 11        | 8.09%   |
| Net/wireless             | 7         | 5.15%   |
| Multimedia controller    | 5         | 3.68%   |
| Bluetooth                | 5         | 3.68%   |
| Net/ethernet             | 4         | 2.94%   |
| Camera                   | 4         | 2.94%   |
| Storage                  | 3         | 2.21%   |
| Communication controller | 3         | 2.21%   |
| Unassigned class         | 1         | 0.74%   |
| Sound                    | 1         | 0.74%   |


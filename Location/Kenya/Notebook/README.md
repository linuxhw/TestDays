Linux in Kenya - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

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

Total: 334

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G2            | [4a3954a4c1](https://linux-hardware.org/?probe=4a3954a4c1) | Feb 02, 2024 |
| HP            | ProBook 440 G1              | [1a7d0f5488](https://linux-hardware.org/?probe=1a7d0f5488) | Feb 01, 2024 |
| HP            | Laptop 15-dy2xxx            | [130befb564](https://linux-hardware.org/?probe=130befb564) | Jan 16, 2024 |
| Dell          | Inspiron 3583               | [385ad48703](https://linux-hardware.org/?probe=385ad48703) | Jan 16, 2024 |
| ASUSTek       | X540NA                      | [1f6d0e42df](https://linux-hardware.org/?probe=1f6d0e42df) | Jan 10, 2024 |
| HP            | EliteBook 830 G5            | [01a010ceeb](https://linux-hardware.org/?probe=01a010ceeb) | Jan 02, 2024 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [a1a93224e4](https://linux-hardware.org/?probe=a1a93224e4) | Dec 02, 2023 |
| HP            | ProBook 4540s               | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| Dell          | Latitude 5300               | [8f1ed5747c](https://linux-hardware.org/?probe=8f1ed5747c) | Nov 18, 2023 |
| HP            | ProBook 4540s               | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| HP            | ProBook 4540s               | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| Dell          | Latitude 3380               | [f88c4741cc](https://linux-hardware.org/?probe=f88c4741cc) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2430... | [658d6f150e](https://linux-hardware.org/?probe=658d6f150e) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | [8df2c91111](https://linux-hardware.org/?probe=8df2c91111) | Oct 29, 2023 |
| Lenovo        | G50-80 80E5                 | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Acer          | Aspire 5920G                | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP            | EliteBook Revolve 810 G3    | [85caa55933](https://linux-hardware.org/?probe=85caa55933) | Oct 14, 2023 |
| HP            | EliteBook 830 G5            | [9f4ab6a725](https://linux-hardware.org/?probe=9f4ab6a725) | Oct 11, 2023 |
| HP            | EliteBook 830 G5            | [a6ac161796](https://linux-hardware.org/?probe=a6ac161796) | Sep 24, 2023 |
| Endless       | EF20EA                      | [492a9e4f5e](https://linux-hardware.org/?probe=492a9e4f5e) | Sep 23, 2023 |
| HP            | EliteBook 840 G1            | [fd6d63df98](https://linux-hardware.org/?probe=fd6d63df98) | Sep 15, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Dell          | XPS 13 9310                 | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| HP            | EliteBook 840 G1            | [71dad1a9b9](https://linux-hardware.org/?probe=71dad1a9b9) | Sep 09, 2023 |
| HP            | EliteBook 840 G1            | [1d1c8e33ff](https://linux-hardware.org/?probe=1d1c8e33ff) | Sep 06, 2023 |
| HP            | EliteBook Folio 9470m       | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | [b3a358a06f](https://linux-hardware.org/?probe=b3a358a06f) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | [40f2588fd0](https://linux-hardware.org/?probe=40f2588fd0) | Aug 31, 2023 |
| HP            | Notebook                    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| HP            | Notebook                    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| HP            | ProBook 430 G1              | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| HP            | ProBook 4540s               | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Lenovo        | G50-80 80E5                 | [837cbb2cf1](https://linux-hardware.org/?probe=837cbb2cf1) | Aug 13, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| HP            | EliteBook 840 G1            | [c24d904ffb](https://linux-hardware.org/?probe=c24d904ffb) | Aug 06, 2023 |
| HP            | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| HP            | EliteBook 840 G1            | [695a7fad0f](https://linux-hardware.org/?probe=695a7fad0f) | Aug 03, 2023 |
| HP            | Notebook                    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| HP            | ProBook 450 G3              | [fef5d6f571](https://linux-hardware.org/?probe=fef5d6f571) | Jul 26, 2023 |
| HP            | ProBook 650 G2              | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| HP            | EliteBook 840 G1            | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [352cc6e31d](https://linux-hardware.org/?probe=352cc6e31d) | Jul 17, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| Apple         | MacBookAir4,1               | [b815c86777](https://linux-hardware.org/?probe=b815c86777) | Jul 07, 2023 |
| HP            | ENVY 15                     | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [04329cdc14](https://linux-hardware.org/?probe=04329cdc14) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6f4c06d514](https://linux-hardware.org/?probe=6f4c06d514) | Jun 14, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Dell          | Latitude E5510              | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| HP            | 15                          | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HP            | EliteBook 840 G3            | [46015ea246](https://linux-hardware.org/?probe=46015ea246) | May 10, 2023 |
| Fujitsu       | T900                        | [d0233bc511](https://linux-hardware.org/?probe=d0233bc511) | May 06, 2023 |
| HP            | EliteBook 840 G1            | [b5602599f8](https://linux-hardware.org/?probe=b5602599f8) | May 06, 2023 |
| HP            | Notebook                    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | [082029ecf5](https://linux-hardware.org/?probe=082029ecf5) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | [e2f37d94cd](https://linux-hardware.org/?probe=e2f37d94cd) | May 05, 2023 |
| HP            | EliteBook 840 G1            | [c8b979d035](https://linux-hardware.org/?probe=c8b979d035) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Dell          | Latitude E6410              | [52ada88fb1](https://linux-hardware.org/?probe=52ada88fb1) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| HP            | Laptop 14-dq2xxx            | [c90d525ee8](https://linux-hardware.org/?probe=c90d525ee8) | Mar 31, 2023 |
| HP            | EliteBook 2570p             | [d5ba09feb1](https://linux-hardware.org/?probe=d5ba09feb1) | Mar 27, 2023 |
| Dell          | XPS 13 9350                 | [d1ba8cb8e9](https://linux-hardware.org/?probe=d1ba8cb8e9) | Mar 24, 2023 |
| Dell          | XPS 13 9310                 | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | UX32LA                      | [3432e951dd](https://linux-hardware.org/?probe=3432e951dd) | Mar 06, 2023 |
| Lenovo        | E51-80 80QB                 | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | E51-80 80QB                 | [73794bde33](https://linux-hardware.org/?probe=73794bde33) | Mar 03, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c9f0a04fcf](https://linux-hardware.org/?probe=c9f0a04fcf) | Feb 10, 2023 |
| HP            | EliteBook 8460p             | [311514a737](https://linux-hardware.org/?probe=311514a737) | Feb 07, 2023 |
| Toshiba       | Satellite C850D-B615        | [66a7f0123f](https://linux-hardware.org/?probe=66a7f0123f) | Feb 07, 2023 |
| HP            | EliteBook 8460p             | [caedc4c130](https://linux-hardware.org/?probe=caedc4c130) | Jan 29, 2023 |
| HP            | 630                         | [837878455e](https://linux-hardware.org/?probe=837878455e) | Jan 28, 2023 |
| HP            | EliteBook 840 G5            | [5ad0221a16](https://linux-hardware.org/?probe=5ad0221a16) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [940d192ea9](https://linux-hardware.org/?probe=940d192ea9) | Jan 20, 2023 |
| HP            | EliteBook 8460p             | [3bc61d7363](https://linux-hardware.org/?probe=3bc61d7363) | Jan 15, 2023 |
| HP            | EliteBook 8460p             | [00780c7a70](https://linux-hardware.org/?probe=00780c7a70) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | [54eaec4178](https://linux-hardware.org/?probe=54eaec4178) | Jan 10, 2023 |
| HP            | EliteBook 2570p             | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| HP            | EliteBook 840 G3            | [3e518355b6](https://linux-hardware.org/?probe=3e518355b6) | Dec 17, 2022 |
| HP            | EliteBook 840 G3            | [eccd29cfac](https://linux-hardware.org/?probe=eccd29cfac) | Dec 17, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [645418a0dd](https://linux-hardware.org/?probe=645418a0dd) | Nov 30, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [2a4bb490d0](https://linux-hardware.org/?probe=2a4bb490d0) | Nov 29, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [a05b99b00e](https://linux-hardware.org/?probe=a05b99b00e) | Nov 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| HP            | ProBook 650 G2              | [713f71652e](https://linux-hardware.org/?probe=713f71652e) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | [34d3046ea4](https://linux-hardware.org/?probe=34d3046ea4) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | [ff4e869df2](https://linux-hardware.org/?probe=ff4e869df2) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2ceb11d7b3](https://linux-hardware.org/?probe=2ceb11d7b3) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5c3d640129](https://linux-hardware.org/?probe=5c3d640129) | Oct 29, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [7654e5f9c4](https://linux-hardware.org/?probe=7654e5f9c4) | Oct 26, 2022 |
| HP            | ProBook 650 G2              | [7848c6d520](https://linux-hardware.org/?probe=7848c6d520) | Oct 26, 2022 |
| HP            | ProBook 450 G7              | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| HP            | ProBook 650 G2              | [43ce2df718](https://linux-hardware.org/?probe=43ce2df718) | Oct 12, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Dell          | Inspiron 1525               | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| HP            | 15                          | [28e8e01768](https://linux-hardware.org/?probe=28e8e01768) | Sep 28, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | EliteBook 8440p             | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| HP            | ENVY 15                     | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| ASUSTek       | X540NA                      | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| HP            | Unknown                     | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | EliteBook 840 G3            | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Notebook      | P65xHP                      | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| HP            | EliteBook 840 G3            | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| HP            | ProBook 440 G6              | [94684071ed](https://linux-hardware.org/?probe=94684071ed) | May 05, 2022 |
| Dell          | Latitude 3340               | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Dell          | Latitude 3340               | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | EliteBook Folio 9480m       | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Lenovo        | ThinkPad T490s 20NYS8J90... | [c1aee9b559](https://linux-hardware.org/?probe=c1aee9b559) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| Lenovo        | V14-IGL 82C2                | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | EliteBook 840 G2            | [fac2fc3940](https://linux-hardware.org/?probe=fac2fc3940) | Jan 13, 2022 |
| Lenovo        | ThinkPad X240 20AL00CQAU    | [9f36bf55ba](https://linux-hardware.org/?probe=9f36bf55ba) | Jan 11, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Inspiron 3543               | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dff30c5ec8](https://linux-hardware.org/?probe=dff30c5ec8) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| Chuwi         | HeroBook Air                | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Dell          | XPS 13 9310                 | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [820951b4af](https://linux-hardware.org/?probe=820951b4af) | Nov 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [022146ab90](https://linux-hardware.org/?probe=022146ab90) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [516eabe645](https://linux-hardware.org/?probe=516eabe645) | Nov 02, 2021 |
| Chuwi         | GemiBook                    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| HP            | ProBook 640 G1              | [170dd8b241](https://linux-hardware.org/?probe=170dd8b241) | Oct 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| HP            | Laptop 15-ra0xx             | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | EliteBook 820 G1            | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire V3-572P              | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Apple         | MacBookPro16,1              | [ab55e1ade6](https://linux-hardware.org/?probe=ab55e1ade6) | Sep 22, 2021 |
| Acer          | Aspire 5749Z                | [40bf0d5bb0](https://linux-hardware.org/?probe=40bf0d5bb0) | Sep 17, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Toshiba       | Satellite C660              | [27b0daea73](https://linux-hardware.org/?probe=27b0daea73) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | EliteBook Folio 9480m       | [b89fc8114f](https://linux-hardware.org/?probe=b89fc8114f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c642d92231](https://linux-hardware.org/?probe=c642d92231) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c374609a3e](https://linux-hardware.org/?probe=c374609a3e) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c9de881b72](https://linux-hardware.org/?probe=c9de881b72) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [10e46eeaf3](https://linux-hardware.org/?probe=10e46eeaf3) | Jul 25, 2021 |
| HP            | EliteBook 840 G3            | [88afb2e5a1](https://linux-hardware.org/?probe=88afb2e5a1) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 640 G1              | [b3a36bf681](https://linux-hardware.org/?probe=b3a36bf681) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | [0f54d945d0](https://linux-hardware.org/?probe=0f54d945d0) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | [daa99f3a24](https://linux-hardware.org/?probe=daa99f3a24) | Jul 15, 2021 |
| HP            | ProBook 640 G1              | [6c9393a9d6](https://linux-hardware.org/?probe=6c9393a9d6) | Jul 08, 2021 |
| HP            | EliteBook 840 G1            | [e60c71a5e1](https://linux-hardware.org/?probe=e60c71a5e1) | Jun 25, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [9d9ecee1b9](https://linux-hardware.org/?probe=9d9ecee1b9) | Jun 20, 2021 |
| HP            | Laptop 15-bw0xx             | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Lenovo        | V130-14IKB 81HQ             | [549f1c8bd1](https://linux-hardware.org/?probe=549f1c8bd1) | May 25, 2021 |
| HP            | EliteBook 840 G2            | [304747e4c6](https://linux-hardware.org/?probe=304747e4c6) | May 23, 2021 |
| Dell          | Inspiron 3543               | [11b99bedb6](https://linux-hardware.org/?probe=11b99bedb6) | May 13, 2021 |
| Lenovo        | V330-14IKB 81B0             | [a71cb329b2](https://linux-hardware.org/?probe=a71cb329b2) | May 12, 2021 |
| Lenovo        | V330-14IKB 81B0             | [dc61da2d5e](https://linux-hardware.org/?probe=dc61da2d5e) | May 09, 2021 |
| Dell          | Inspiron 3543               | [e8771a4577](https://linux-hardware.org/?probe=e8771a4577) | May 01, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ee57ec30cd](https://linux-hardware.org/?probe=ee57ec30cd) | Apr 28, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [95c380139d](https://linux-hardware.org/?probe=95c380139d) | Apr 28, 2021 |
| Toshiba       | dynabook R731/E             | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| HP            | EliteBook Folio 9470m       | [561287f5a8](https://linux-hardware.org/?probe=561287f5a8) | Apr 06, 2021 |
| HP            | 15 Notebook PC              | [ecac5c48dc](https://linux-hardware.org/?probe=ecac5c48dc) | Apr 02, 2021 |
| HP            | EliteBook 840 G6            | [95f53c1b72](https://linux-hardware.org/?probe=95f53c1b72) | Mar 19, 2021 |
| HP            | EliteBook 840 G6            | [585322e740](https://linux-hardware.org/?probe=585322e740) | Mar 19, 2021 |
| Toshiba       | Satellite L50-B             | [b345b644ae](https://linux-hardware.org/?probe=b345b644ae) | Mar 18, 2021 |
| HP            | ProBook 640 G1              | [89e652d12d](https://linux-hardware.org/?probe=89e652d12d) | Mar 18, 2021 |
| Toshiba       | dynabook Satellite B554/... | [31915e8c0b](https://linux-hardware.org/?probe=31915e8c0b) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | [e166e551cd](https://linux-hardware.org/?probe=e166e551cd) | Mar 09, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [10c98c982d](https://linux-hardware.org/?probe=10c98c982d) | Mar 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [09037a0a1b](https://linux-hardware.org/?probe=09037a0a1b) | Mar 06, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron N5030              | [47077a37f2](https://linux-hardware.org/?probe=47077a37f2) | Feb 25, 2021 |
| Toshiba       | Satellite L50-B             | [c4ab183609](https://linux-hardware.org/?probe=c4ab183609) | Feb 24, 2021 |
| Toshiba       | Satellite L50-B             | [55c54121f8](https://linux-hardware.org/?probe=55c54121f8) | Feb 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [3311619921](https://linux-hardware.org/?probe=3311619921) | Feb 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [b573c1e746](https://linux-hardware.org/?probe=b573c1e746) | Feb 17, 2021 |
| HP            | EliteBook 8470p             | [eda69993ed](https://linux-hardware.org/?probe=eda69993ed) | Feb 17, 2021 |
| HP            | Laptop 15-da1xxx            | [66c8150e0d](https://linux-hardware.org/?probe=66c8150e0d) | Feb 14, 2021 |
| HP            | EliteBook 8470p             | [96be56a30d](https://linux-hardware.org/?probe=96be56a30d) | Feb 13, 2021 |
| TECNO         | WinPad 2                    | [336989b30d](https://linux-hardware.org/?probe=336989b30d) | Feb 10, 2021 |
| TECNO         | WinPad 2                    | [439563e244](https://linux-hardware.org/?probe=439563e244) | Feb 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [38d7cb1271](https://linux-hardware.org/?probe=38d7cb1271) | Feb 06, 2021 |
| Dell          | Inspiron 3580               | [417752f660](https://linux-hardware.org/?probe=417752f660) | Jan 30, 2021 |
| Lenovo        | ThinkPad P52s 20LB0021US    | [4e50af07df](https://linux-hardware.org/?probe=4e50af07df) | Jan 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [671c83ebf7](https://linux-hardware.org/?probe=671c83ebf7) | Jan 27, 2021 |
| HP            | ProBook 6560b               | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| HP            | Compaq Mini 110c-1100       | [e2f7ccd4ad](https://linux-hardware.org/?probe=e2f7ccd4ad) | Jan 14, 2021 |
| ASUSTek       | X540NA                      | [9b2af2d13c](https://linux-hardware.org/?probe=9b2af2d13c) | Jan 13, 2021 |
| HP            | ProBook 6560b               | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| HP            | EliteBook Folio 9470m       | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Endless       | EF20EA                      | [c216bffe9d](https://linux-hardware.org/?probe=c216bffe9d) | Dec 20, 2020 |
| Endless       | EF20EA                      | [e2409b47e2](https://linux-hardware.org/?probe=e2409b47e2) | Dec 20, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [c3c7909b48](https://linux-hardware.org/?probe=c3c7909b48) | Dec 20, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| I-Life Dig... | ZED AIR PRO                 | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Dell          | Inspiron 3543               | [885a64d9d3](https://linux-hardware.org/?probe=885a64d9d3) | Dec 12, 2020 |
| ASUSTek       | X202EV                      | [b3b2381999](https://linux-hardware.org/?probe=b3b2381999) | Nov 25, 2020 |
| HP            | Compaq Mini 110c-1100       | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X240 20AMS4J900    | [8a54e51f5a](https://linux-hardware.org/?probe=8a54e51f5a) | Nov 17, 2020 |
| HP            | Laptop 15-da1xxx            | [7c1f9ebdef](https://linux-hardware.org/?probe=7c1f9ebdef) | Nov 12, 2020 |
| HP            | EliteBook 8460p             | [ccefa81140](https://linux-hardware.org/?probe=ccefa81140) | Nov 12, 2020 |
| HP            | ZBook 15 G2                 | [5c863855cc](https://linux-hardware.org/?probe=5c863855cc) | Nov 11, 2020 |
| Dell          | Inspiron 3543               | [372e62dd5a](https://linux-hardware.org/?probe=372e62dd5a) | Nov 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [6b0122d8c2](https://linux-hardware.org/?probe=6b0122d8c2) | Nov 06, 2020 |
| Dell          | Latitude E6420              | [e1f1909639](https://linux-hardware.org/?probe=e1f1909639) | Oct 25, 2020 |
| Dell          | Latitude E6420              | [e1bbf1beb6](https://linux-hardware.org/?probe=e1bbf1beb6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | [a2eb617037](https://linux-hardware.org/?probe=a2eb617037) | Oct 16, 2020 |
| Dell          | Inspiron 3543               | [5b0c257b43](https://linux-hardware.org/?probe=5b0c257b43) | Oct 02, 2020 |
| Dell          | Latitude D820               | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Inspiron 3543               | [47a129fdd0](https://linux-hardware.org/?probe=47a129fdd0) | Sep 28, 2020 |
| Dell          | Inspiron 3543               | [ebcb037006](https://linux-hardware.org/?probe=ebcb037006) | Sep 28, 2020 |
| HP            | EliteBook 8460p             | [8232648226](https://linux-hardware.org/?probe=8232648226) | Sep 20, 2020 |
| Samsung       | RC410/RC510/RC710           | [37985e0340](https://linux-hardware.org/?probe=37985e0340) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | [92ee6a03be](https://linux-hardware.org/?probe=92ee6a03be) | Sep 14, 2020 |
| ASUSTek       | UX305CA                     | [f51d9347e3](https://linux-hardware.org/?probe=f51d9347e3) | Sep 10, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [6e6f79b651](https://linux-hardware.org/?probe=6e6f79b651) | Sep 10, 2020 |
| HP            | EliteBook 840 G2            | [4d64af6a38](https://linux-hardware.org/?probe=4d64af6a38) | Sep 07, 2020 |
| ASUSTek       | X551MA                      | [6e93ef18ce](https://linux-hardware.org/?probe=6e93ef18ce) | Sep 03, 2020 |
| HP            | EliteBook Folio 9480m       | [19a0f0bfdc](https://linux-hardware.org/?probe=19a0f0bfdc) | Sep 03, 2020 |
| HP            | ProBook 440 G5              | [9c70b1dad4](https://linux-hardware.org/?probe=9c70b1dad4) | Sep 02, 2020 |
| HP            | EliteBook 840 G2            | [31f100c680](https://linux-hardware.org/?probe=31f100c680) | Aug 10, 2020 |
| HP            | EliteBook 840 G2            | [2a88596017](https://linux-hardware.org/?probe=2a88596017) | Jul 30, 2020 |
| HP            | Pavilion Laptop 15t-cs20... | [f778796026](https://linux-hardware.org/?probe=f778796026) | Jul 16, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [412f31bc06](https://linux-hardware.org/?probe=412f31bc06) | Jul 01, 2020 |
| Lenovo        | ThinkPad L480 20LTS1RE0Y    | [76ef35dd77](https://linux-hardware.org/?probe=76ef35dd77) | Jun 26, 2020 |
| HP            | EliteBook Folio 9470m       | [4f747e9c8a](https://linux-hardware.org/?probe=4f747e9c8a) | Jun 25, 2020 |
| HP            | ProBook 440 G2              | [21efc22417](https://linux-hardware.org/?probe=21efc22417) | Jun 21, 2020 |
| Dell          | Latitude 3150               | [0299c15a34](https://linux-hardware.org/?probe=0299c15a34) | Jun 20, 2020 |
| HP            | Pavilion x2 Detachable      | [6277131dfd](https://linux-hardware.org/?probe=6277131dfd) | Jun 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [f16d9a4077](https://linux-hardware.org/?probe=f16d9a4077) | Jun 17, 2020 |
| ASUSTek       | X540NA                      | [530934acb0](https://linux-hardware.org/?probe=530934acb0) | Jun 17, 2020 |
| HP            | Pavilion x2 Detachable      | [0e66f9df2c](https://linux-hardware.org/?probe=0e66f9df2c) | Jun 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [483d2473b0](https://linux-hardware.org/?probe=483d2473b0) | Jun 15, 2020 |
| Getac         | V110                        | [4e3a330cb5](https://linux-hardware.org/?probe=4e3a330cb5) | Jun 13, 2020 |
| Toshiba       | R84SAU2                     | [d59976ae7f](https://linux-hardware.org/?probe=d59976ae7f) | Jun 10, 2020 |
| Acer          | Aspire A315-33              | [c0eeb5a67b](https://linux-hardware.org/?probe=c0eeb5a67b) | Jun 03, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [e903b1af8a](https://linux-hardware.org/?probe=e903b1af8a) | May 31, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [75e6d735a0](https://linux-hardware.org/?probe=75e6d735a0) | May 31, 2020 |
| Dell          | Inspiron 5767               | [bdab68c78a](https://linux-hardware.org/?probe=bdab68c78a) | May 25, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [227b4dc4ec](https://linux-hardware.org/?probe=227b4dc4ec) | May 15, 2020 |
| Apple         | MacBookPro3,1               | [5ca063ed58](https://linux-hardware.org/?probe=5ca063ed58) | May 11, 2020 |
| Dell          | Latitude E6410              | [7a885b703e](https://linux-hardware.org/?probe=7a885b703e) | May 10, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | [85b487e27d](https://linux-hardware.org/?probe=85b487e27d) | May 02, 2020 |
| Dell          | Inspiron 5767               | [32e3129638](https://linux-hardware.org/?probe=32e3129638) | May 02, 2020 |
| Dell          | Latitude 7490               | [cc8b2bc724](https://linux-hardware.org/?probe=cc8b2bc724) | Apr 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| ASUSTek       | X540SAA                     | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
| HP            | Pavilion x2 Detachable      | [b634560d95](https://linux-hardware.org/?probe=b634560d95) | Mar 01, 2020 |
| HP            | ENVY TS 15                  | [eb1591f00c](https://linux-hardware.org/?probe=eb1591f00c) | Dec 23, 2019 |
| Dell          | Latitude E6220              | [37cf274f19](https://linux-hardware.org/?probe=37cf274f19) | Oct 30, 2019 |
| HP            | EliteBook 820 G2            | [05b4f35642](https://linux-hardware.org/?probe=05b4f35642) | Oct 11, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| EVOC          | P7xxTM1-(G)                 | [f0f19467e3](https://linux-hardware.org/?probe=f0f19467e3) | Sep 04, 2019 |
| EVOC          | P7xxTM1-(G)                 | [2ec595f039](https://linux-hardware.org/?probe=2ec595f039) | Sep 03, 2019 |
| HP            | ENVY TS 15                  | [054a6961ec](https://linux-hardware.org/?probe=054a6961ec) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| EVOC          | P7xxTM1-(G)                 | [f9f9fbd6bd](https://linux-hardware.org/?probe=f9f9fbd6bd) | Aug 06, 2019 |
| HP            | EliteBook 8440p             | [e2c04796a0](https://linux-hardware.org/?probe=e2c04796a0) | Jul 25, 2019 |
| HP            | OMEN by Laptop              | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
| HP            | EliteBook 840 G1            | [70e21ebad0](https://linux-hardware.org/?probe=70e21ebad0) | Jun 30, 2019 |
| HP            | EliteBook 840 G1            | [25b5bf978a](https://linux-hardware.org/?probe=25b5bf978a) | Jun 29, 2019 |
| HP            | ProBook 450 G1              | [8f23861866](https://linux-hardware.org/?probe=8f23861866) | Jun 04, 2019 |
| Unknown       | Unknown                     | [57dd20a793](https://linux-hardware.org/?probe=57dd20a793) | Jun 03, 2019 |
| Dell          | Inspiron 5570               | [86722cf4ab](https://linux-hardware.org/?probe=86722cf4ab) | May 05, 2019 |
| HP            | Notebook                    | [ca99cb8e00](https://linux-hardware.org/?probe=ca99cb8e00) | Apr 10, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | [2f1b160149](https://linux-hardware.org/?probe=2f1b160149) | Nov 19, 2018 |
| Clevo         | P7xxDM2-(G)                 | [9cfa1aef75](https://linux-hardware.org/?probe=9cfa1aef75) | Jun 20, 2018 |
| EUROCOM       | Q6                          | [001ab8c139](https://linux-hardware.org/?probe=001ab8c139) | Jun 02, 2018 |
| EUROCOM       | Q6                          | [15b4e0daf2](https://linux-hardware.org/?probe=15b4e0daf2) | Jun 02, 2018 |
| Clevo         | P7xxDM2-(G)                 | [9fcaed033f](https://linux-hardware.org/?probe=9fcaed033f) | Mar 09, 2018 |
| Sony          | VGN-NS295J                  | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 33        | 13.36%  |
| Ubuntu 22.04                 | 28        | 11.34%  |
| Ubuntu 18.04                 | 15        | 6.07%   |
| Zorin 16                     | 7         | 2.83%   |
| Linux Mint 20.3              | 6         | 2.43%   |
| Fedora 36                    | 6         | 2.43%   |
| Arch Rolling                 | 6         | 2.43%   |
| Ubuntu 23.04                 | 5         | 2.02%   |
| Manjaro                      | 5         | 2.02%   |
| Fedora 38                    | 5         | 2.02%   |
| Zorin 15                     | 4         | 1.62%   |
| Ubuntu 20.10                 | 4         | 1.62%   |
| Ubuntu 19.04                 | 4         | 1.62%   |
| Pop!_OS 20.04                | 4         | 1.62%   |
| OpenMandriva 4.2             | 4         | 1.62%   |
| Arch                         | 4         | 1.62%   |
| Ubuntu 21.04                 | 3         | 1.21%   |
| Q4OS 3                       | 3         | 1.21%   |
| Pop!_OS 22.04                | 3         | 1.21%   |
| Linux Mint 20.2              | 3         | 1.21%   |
| Kali 2023.3                  | 3         | 1.21%   |
| Fedora 37                    | 3         | 1.21%   |
| Debian 11                    | 3         | 1.21%   |
| Ubuntu 21.10                 | 2         | 0.81%   |
| Ubuntu 19.10                 | 2         | 0.81%   |
| Parrot 5.3                   | 2         | 0.81%   |
| Parrot 5.1                   | 2         | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.81%   |
| Linux Mint 21.2              | 2         | 0.81%   |
| Linux Mint 19                | 2         | 0.81%   |
| Kali 2023.2                  | 2         | 0.81%   |
| Kali 2022.3                  | 2         | 0.81%   |
| Fedora 35                    | 2         | 0.81%   |
| Fedora 32                    | 2         | 0.81%   |
| Endless 3.9.4                | 2         | 0.81%   |
| Endless 3.9.2                | 2         | 0.81%   |
| Endless 3.9.1                | 2         | 0.81%   |
| Debian 12                    | 2         | 0.81%   |
| Xubuntu 20.04                | 1         | 0.4%    |
| Ubuntu MATE 21.04            | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 92        | 40%     |
| Fedora        | 18        | 7.83%   |
| Linux Mint    | 14        | 6.09%   |
| Zorin         | 11        | 4.78%   |
| Kali          | 10        | 4.35%   |
| Endless       | 10        | 4.35%   |
| Arch          | 10        | 4.35%   |
| Pop!_OS       | 9         | 3.91%   |
| Manjaro       | 9         | 3.91%   |
| Parrot        | 8         | 3.48%   |
| OpenMandriva  | 6         | 2.61%   |
| Debian        | 6         | 2.61%   |
| Q4OS          | 3         | 1.3%    |
| Ubuntu MATE   | 2         | 0.87%   |
| ROSA          | 2         | 0.87%   |
| RHEL          | 2         | 0.87%   |
| openSUSE      | 2         | 0.87%   |
| Elementary    | 2         | 0.87%   |
| Xubuntu       | 1         | 0.43%   |
| Ubuntu Budgie | 1         | 0.43%   |
| Rocky Linux   | 1         | 0.43%   |
| Nobara        | 1         | 0.43%   |
| Lubuntu       | 1         | 0.43%   |
| LMDE          | 1         | 0.43%   |
| Lilidog       | 1         | 0.43%   |
| KDE neon      | 1         | 0.43%   |
| Garuda Linux  | 1         | 0.43%   |
| Deepin        | 1         | 0.43%   |
| blendOS       | 1         | 0.43%   |
| BlackPanther  | 1         | 0.43%   |
| antiX         | 1         | 0.43%   |
| Alpine        | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 2.26%   |
| 5.15.0-58-generic        | 4         | 1.5%    |
| 5.15.0-52-generic        | 4         | 1.5%    |
| 5.11.0-38-generic        | 4         | 1.5%    |
| 5.10.14-desktop-1omv4002 | 4         | 1.5%    |
| 6.3.0-kali1-amd64        | 3         | 1.13%   |
| 5.4.0-58-generic         | 3         | 1.13%   |
| 5.4.0-52-generic         | 3         | 1.13%   |
| 5.4.0-45-generic         | 3         | 1.13%   |
| 5.4.0-42-generic         | 3         | 1.13%   |
| 5.19.0-38-generic        | 3         | 1.13%   |
| 5.15.0-53-generic        | 3         | 1.13%   |
| 5.15.0-41-generic        | 3         | 1.13%   |
| 4.19.0-17-amd64          | 3         | 1.13%   |
| 6.5.0-10-generic         | 2         | 0.75%   |
| 6.2.0-32-generic         | 2         | 0.75%   |
| 6.1.0-kali7-amd64        | 2         | 0.75%   |
| 5.8.0-59-generic         | 2         | 0.75%   |
| 5.8.0-43-generic         | 2         | 0.75%   |
| 5.4.0-67-generic         | 2         | 0.75%   |
| 5.4.0-65-generic         | 2         | 0.75%   |
| 5.4.0-54-generic         | 2         | 0.75%   |
| 5.4.0-48-generic         | 2         | 0.75%   |
| 5.4.0-47-generic         | 2         | 0.75%   |
| 5.4.0-37-generic         | 2         | 0.75%   |
| 5.4.0-137-generic        | 2         | 0.75%   |
| 5.3.0-28-generic         | 2         | 0.75%   |
| 5.19.0-41-generic        | 2         | 0.75%   |
| 5.19.0-35-generic        | 2         | 0.75%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.75%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.75%   |
| 5.15.0-46-generic        | 2         | 0.75%   |
| 5.13.19-2-MANJARO        | 2         | 0.75%   |
| 5.13.0-27-generic        | 2         | 0.75%   |
| 5.11.0-37-generic        | 2         | 0.75%   |
| 5.11.0-35-generic        | 2         | 0.75%   |
| 5.11.0-34-generic        | 2         | 0.75%   |
| 6.6.9-amd64              | 1         | 0.38%   |
| 6.6.13-100.fc38.x86_64   | 1         | 0.38%   |
| 6.5.7-200.fc38.x86_64    | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 15.54%  |
| 5.15.0  | 24        | 9.56%   |
| 5.8.0   | 18        | 7.17%   |
| 5.11.0  | 15        | 5.98%   |
| 4.15.0  | 11        | 4.38%   |
| 6.2.0   | 8         | 3.19%   |
| 5.19.0  | 8         | 3.19%   |
| 6.1.0   | 7         | 2.79%   |
| 5.3.0   | 7         | 2.79%   |
| 5.13.0  | 7         | 2.79%   |
| 5.0.0   | 7         | 2.79%   |
| 5.10.0  | 5         | 1.99%   |
| 6.5.0   | 4         | 1.59%   |
| 5.18.0  | 4         | 1.59%   |
| 5.10.14 | 4         | 1.59%   |
| 4.19.0  | 4         | 1.59%   |
| 6.3.0   | 3         | 1.2%    |
| 5.14.0  | 3         | 1.2%    |
| 4.18.0  | 3         | 1.2%    |
| 6.4.8   | 2         | 0.8%    |
| 6.3.4   | 2         | 0.8%    |
| 6.1.52  | 2         | 0.8%    |
| 5.19.9  | 2         | 0.8%    |
| 5.18.13 | 2         | 0.8%    |
| 5.17.5  | 2         | 0.8%    |
| 5.16.7  | 2         | 0.8%    |
| 5.13.19 | 2         | 0.8%    |
| 6.6.9   | 1         | 0.4%    |
| 6.6.13  | 1         | 0.4%    |
| 6.5.7   | 1         | 0.4%    |
| 6.5.6   | 1         | 0.4%    |
| 6.4.14  | 1         | 0.4%    |
| 6.4.11  | 1         | 0.4%    |
| 6.3.6   | 1         | 0.4%    |
| 6.3.5   | 1         | 0.4%    |
| 6.2.9   | 1         | 0.4%    |
| 6.2.6   | 1         | 0.4%    |
| 6.2.15  | 1         | 0.4%    |
| 6.2.11  | 1         | 0.4%    |
| 6.1.50  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 15.66%  |
| 5.15    | 26        | 10.44%  |
| 5.8     | 20        | 8.03%   |
| 5.11    | 16        | 6.43%   |
| 6.1     | 13        | 5.22%   |
| 5.19    | 13        | 5.22%   |
| 6.2     | 12        | 4.82%   |
| 5.10    | 12        | 4.82%   |
| 4.15    | 11        | 4.42%   |
| 5.13    | 9         | 3.61%   |
| 5.0     | 8         | 3.21%   |
| 6.3     | 7         | 2.81%   |
| 5.3     | 7         | 2.81%   |
| 6.5     | 6         | 2.41%   |
| 5.18    | 6         | 2.41%   |
| 5.14    | 6         | 2.41%   |
| 4.19    | 5         | 2.01%   |
| 6.4     | 4         | 1.61%   |
| 5.16    | 4         | 1.61%   |
| 4.18    | 4         | 1.61%   |
| 5.6     | 3         | 1.2%    |
| 5.17    | 3         | 1.2%    |
| 6.6     | 2         | 0.8%    |
| 6.0     | 2         | 0.8%    |
| 5.9     | 2         | 0.8%    |
| 5.2     | 2         | 0.8%    |
| 4.9     | 2         | 0.8%    |
| 5.7     | 1         | 0.4%    |
| 5.5     | 1         | 0.4%    |
| 5.1     | 1         | 0.4%    |
| 4.16    | 1         | 0.4%    |
| 4.13    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 219       | 98.21%  |
| i686   | 4         | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 139       | 59.91%  |
| KDE5            | 22        | 9.48%   |
| Unknown         | 22        | 9.48%   |
| XFCE            | 13        | 5.6%    |
| X-Cinnamon      | 12        | 5.17%   |
| MATE            | 9         | 3.88%   |
| KDE             | 4         | 1.72%   |
| Pantheon        | 2         | 0.86%   |
| KDE4            | 2         | 0.86%   |
| openbox         | 1         | 0.43%   |
| LXQt            | 1         | 0.43%   |
| GNOME Flashback | 1         | 0.43%   |
| Endless:GNOME   | 1         | 0.43%   |
| Deepin          | 1         | 0.43%   |
| Cinnamon        | 1         | 0.43%   |
| awesome         | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 153       | 65.95%  |
| Wayland | 66        | 28.45%  |
| Unknown | 11        | 4.74%   |
| Tty     | 2         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 44.59%  |
| GDM3    | 40        | 17.32%  |
| GDM     | 33        | 14.29%  |
| SDDM    | 24        | 10.39%  |
| LightDM | 24        | 10.39%  |
| TDM     | 5         | 2.16%   |
| KDM     | 2         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 170       | 75.56%  |
| en_GB   | 24        | 10.67%  |
| Unknown | 24        | 10.67%  |
| C       | 6         | 2.67%   |
| en_AG   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 120       | 52.63%  |
| EFI  | 108       | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 177       | 78.67%  |
| Btrfs   | 23        | 10.22%  |
| Overlay | 10        | 4.44%   |
| Tmpfs   | 9         | 4%      |
| Xfs     | 3         | 1.33%   |
| Unknown | 2         | 0.89%   |
| Zfs     | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 46.72%  |
| GPT     | 90        | 39.3%   |
| MBR     | 32        | 13.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 88.44%  |
| Yes       | 26        | 11.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 159       | 70.67%  |
| Yes       | 66        | 29.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 98        | 43.95%  |
| Lenovo                      | 51        | 22.87%  |
| Dell                        | 26        | 11.66%  |
| ASUSTek Computer            | 10        | 4.48%   |
| Toshiba                     | 8         | 3.59%   |
| Acer                        | 4         | 1.79%   |
| Samsung Electronics         | 3         | 1.35%   |
| Apple                       | 3         | 1.35%   |
| Endless                     | 2         | 0.9%    |
| Chuwi                       | 2         | 0.9%    |
| TECNO                       | 1         | 0.45%   |
| Sony                        | 1         | 0.45%   |
| SLIMBOOK                    | 1         | 0.45%   |
| Panasonic                   | 1         | 0.45%   |
| Notebook                    | 1         | 0.45%   |
| LG Electronics              | 1         | 0.45%   |
| Insyde                      | 1         | 0.45%   |
| I-Life Digital Technologies | 1         | 0.45%   |
| HUAWEI                      | 1         | 0.45%   |
| Getac                       | 1         | 0.45%   |
| Fujitsu                     | 1         | 0.45%   |
| EVOC                        | 1         | 0.45%   |
| EUROCOM                     | 1         | 0.45%   |
| Eluktronics                 | 1         | 0.45%   |
| Clevo                       | 1         | 0.45%   |
| Unknown                     | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook 840 G1                     | 7         | 3.14%   |
| HP EliteBook 840 G3                     | 5         | 2.24%   |
| HP EliteBook Folio 9470m                | 4         | 1.79%   |
| Dell XPS 13 9310                        | 4         | 1.79%   |
| HP ProBook 4540s                        | 3         | 1.35%   |
| HP Notebook                             | 3         | 1.35%   |
| HP EliteBook Folio 9480m                | 3         | 1.35%   |
| HP EliteBook 8460p                      | 3         | 1.35%   |
| HP EliteBook 840 G2                     | 3         | 1.35%   |
| HP EliteBook 2570p                      | 3         | 1.35%   |
| HP 15                                   | 3         | 1.35%   |
| ASUS X540NA                             | 3         | 1.35%   |
| Unknown                                 | 3         | 1.35%   |
| Toshiba Satellite C660                  | 2         | 0.9%    |
| Lenovo IdeaPad S340-14IIL 81VV          | 2         | 0.9%    |
| Lenovo IdeaPad 3 14ITL6 82H7            | 2         | 0.9%    |
| Lenovo G50-80 80E5                      | 2         | 0.9%    |
| HP ProBook 6560b                        | 2         | 0.9%    |
| HP ProBook 640 G1                       | 2         | 0.9%    |
| HP ProBook 440 G5                       | 2         | 0.9%    |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 0.9%    |
| HP ENVY 15                              | 2         | 0.9%    |
| HP EliteBook 8440p                      | 2         | 0.9%    |
| HP Compaq Mini 110c-1100                | 2         | 0.9%    |
| HP 630                                  | 2         | 0.9%    |
| HP 15 Notebook PC                       | 2         | 0.9%    |
| Endless EF20EA                          | 2         | 0.9%    |
| Dell Latitude E6410                     | 2         | 0.9%    |
| Dell Inspiron 5767                      | 2         | 0.9%    |
| Toshiba TECRA A50-A                     | 1         | 0.45%   |
| Toshiba Satellite L50-B                 | 1         | 0.45%   |
| Toshiba Satellite C850D-B615            | 1         | 0.45%   |
| Toshiba R84SAU2                         | 1         | 0.45%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.45%   |
| Toshiba dynabook R731/E                 | 1         | 0.45%   |
| TECNO WinPad 2                          | 1         | 0.45%   |
| Sony VGN-NS295J                         | 1         | 0.45%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.45%   |
| Samsung RC410/RC510/RC710               | 1         | 0.45%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 41        | 18.39%  |
| Lenovo ThinkPad        | 24        | 10.76%  |
| HP ProBook             | 20        | 8.97%   |
| Lenovo IdeaPad         | 14        | 6.28%   |
| Dell Latitude          | 12        | 5.38%   |
| Dell Inspiron          | 9         | 4.04%   |
| HP Pavilion            | 8         | 3.59%   |
| HP Laptop              | 6         | 2.69%   |
| HP ENVY                | 5         | 2.24%   |
| HP 15                  | 5         | 2.24%   |
| Dell XPS               | 5         | 2.24%   |
| Toshiba Satellite      | 4         | 1.79%   |
| Acer Aspire            | 4         | 1.79%   |
| Lenovo Legion          | 3         | 1.35%   |
| HP Notebook            | 3         | 1.35%   |
| ASUS X540NA            | 3         | 1.35%   |
| Unknown                | 3         | 1.35%   |
| Toshiba dynabook       | 2         | 0.9%    |
| Lenovo G50-80          | 2         | 0.9%    |
| HP Compaq              | 2         | 0.9%    |
| HP 630                 | 2         | 0.9%    |
| Endless EF20EA         | 2         | 0.9%    |
| Toshiba TECRA          | 1         | 0.45%   |
| Toshiba R84SAU2        | 1         | 0.45%   |
| TECNO WinPad           | 1         | 0.45%   |
| Sony VGN-NS295J        | 1         | 0.45%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.45%   |
| Samsung RC410          | 1         | 0.45%   |
| Samsung 300E5EV        | 1         | 0.45%   |
| Samsung 300E4C         | 1         | 0.45%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.45%   |
| Notebook P65xHP        | 1         | 0.45%   |
| LG LW25-B7HG           | 1         | 0.45%   |
| Lenovo Z50-75          | 1         | 0.45%   |
| Lenovo V330-14IKB      | 1         | 0.45%   |
| Lenovo V310-15ISK      | 1         | 0.45%   |
| Lenovo V14-IGL         | 1         | 0.45%   |
| Lenovo V130-14IKB      | 1         | 0.45%   |
| Lenovo V110-15ISK      | 1         | 0.45%   |
| Lenovo ThinkBook       | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 24        | 10.76%  |
| 2016    | 23        | 10.31%  |
| 2019    | 21        | 9.42%   |
| 2012    | 21        | 9.42%   |
| 2018    | 19        | 8.52%   |
| 2014    | 19        | 8.52%   |
| 2015    | 18        | 8.07%   |
| 2011    | 16        | 7.17%   |
| 2017    | 15        | 6.73%   |
| 2020    | 13        | 5.83%   |
| 2010    | 12        | 5.38%   |
| 2021    | 9         | 4.04%   |
| 2008    | 3         | 1.35%   |
| 2006    | 3         | 1.35%   |
| 2022    | 2         | 0.9%    |
| 2009    | 2         | 0.9%    |
| 2007    | 2         | 0.9%    |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 223       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 206       | 91.15%  |
| Enabled  | 20        | 8.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 223       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 32%     |
| 3.01-4.0    | 60        | 26.67%  |
| 8.01-16.0   | 34        | 15.11%  |
| 16.01-24.0  | 28        | 12.44%  |
| 1.01-2.0    | 15        | 6.67%   |
| 32.01-64.0  | 7         | 3.11%   |
| 24.01-32.0  | 3         | 1.33%   |
| 64.01-256.0 | 3         | 1.33%   |
| 0.51-1.0    | 2         | 0.89%   |
| 2.01-3.0    | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 73        | 28.97%  |
| 1.01-2.0  | 64        | 25.4%   |
| 3.01-4.0  | 49        | 19.44%  |
| 4.01-8.0  | 42        | 16.67%  |
| 0.51-1.0  | 17        | 6.75%   |
| 8.01-16.0 | 6         | 2.38%   |
| 0.01-0.5  | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 191       | 83.41%  |
| 2      | 31        | 13.54%  |
| 0      | 3         | 1.31%   |
| 10     | 1         | 0.44%   |
| 8      | 1         | 0.44%   |
| 4      | 1         | 0.44%   |
| 3      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 62.78%  |
| Yes       | 83        | 37.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 82.51%  |
| No        | 39        | 17.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 95.54%  |
| No        | 10        | 4.46%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 77.43%  |
| No        | 51        | 22.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 223       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Notebooks | Percent |
|-----------|-----------|---------|
| Nairobi   | 208       | 90.04%  |
| Mombasa   | 3         | 1.3%    |
| Kiambu    | 3         | 1.3%    |
| Nakuru    | 2         | 0.87%   |
| Kikuyu    | 2         | 0.87%   |
| Eldoret   | 2         | 0.87%   |
| Wote      | 1         | 0.43%   |
| Rongai    | 1         | 0.43%   |
| Nyeri     | 1         | 0.43%   |
| Nyahururu | 1         | 0.43%   |
| Narok     | 1         | 0.43%   |
| Nanyuki   | 1         | 0.43%   |
| Murang'a  | 1         | 0.43%   |
| Maralal   | 1         | 0.43%   |
| Machakos  | 1         | 0.43%   |
| Kisii     | 1         | 0.43%   |
| Embakasi  | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 58        | 78     | 23.02%  |
| WDC                         | 31        | 38     | 12.3%   |
| Toshiba                     | 31        | 36     | 12.3%   |
| Samsung Electronics         | 29        | 42     | 11.51%  |
| HGST                        | 16        | 26     | 6.35%   |
| Unknown                     | 14        | 18     | 5.56%   |
| SanDisk                     | 9         | 11     | 3.57%   |
| Hitachi                     | 9         | 12     | 3.57%   |
| Micron Technology           | 6         | 7      | 2.38%   |
| Crucial                     | 6         | 8      | 2.38%   |
| MARSHAL                     | 5         | 5      | 1.98%   |
| Lexar                       | 5         | 5      | 1.98%   |
| SK hynix                    | 3         | 3      | 1.19%   |
| Kingston                    | 3         | 5      | 1.19%   |
| SPCC                        | 2         | 2      | 0.79%   |
| Apple                       | 2         | 2      | 0.79%   |
| A-DATA Technology           | 2         | 2      | 0.79%   |
| Unknown                     | 2         | 2      | 0.79%   |
| Union Memory                | 1         | 1      | 0.4%    |
| TCSUNBOW                    | 1         | 1      | 0.4%    |
| Silicon Motion              | 1         | 1      | 0.4%    |
| Plextor                     | 1         | 1      | 0.4%    |
| Netac                       | 1         | 1      | 0.4%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.4%    |
| MAX                         | 1         | 1      | 0.4%    |
| LITEONIT                    | 1         | 1      | 0.4%    |
| LITEON                      | 1         | 1      | 0.4%    |
| Lite-On Technology          | 1         | 2      | 0.4%    |
| KIOXIA                      | 1         | 1      | 0.4%    |
| KINGBANK                    | 1         | 1      | 0.4%    |
| Intel                       | 1         | 1      | 0.4%    |
| HUAWEI                      | 1         | 1      | 0.4%    |
| Hjwdz                       | 1         | 1      | 0.4%    |
| Golden                      | 1         | 1      | 0.4%    |
| Eluktro                     | 1         | 1      | 0.4%    |
| China                       | 1         | 1      | 0.4%    |
| CARLSTEIN                   | 1         | 4      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 12        | 4.63%   |
| Seagate ST500LT012-9WS142 500GB                   | 7         | 2.7%    |
| HGST HTS725050A7E630 500GB                        | 7         | 2.7%    |
| Toshiba MQ04ABF100 1TB                            | 6         | 2.32%   |
| Seagate ST9500325AS 500GB                         | 6         | 2.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 1.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5         | 1.93%   |
| Unknown MMC Card  64GB                            | 4         | 1.54%   |
| Toshiba MQ01ABF050 500GB                          | 4         | 1.54%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.54%   |
| Seagate ST500LT012-1DG142 500GB                   | 4         | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB                   | 4         | 1.54%   |
| Samsung SSD 960 EVO 1TB                           | 4         | 1.54%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 3         | 1.16%   |
| WDC PC SN730 NVMe 512GB                           | 3         | 1.16%   |
| Unknown MMC Card  32GB                            | 3         | 1.16%   |
| MARSHAL MAL2500SA-T54L 500GB                      | 3         | 1.16%   |
| Crucial CT2050MX300SSD1 2TB                       | 3         | 1.16%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.77%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 2         | 0.77%   |
| WDC WD2500BEKT-75PVMT0 250GB                      | 2         | 0.77%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.77%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.77%   |
| Unknown NCard  32GB                               | 2         | 0.77%   |
| Toshiba MQ01ABD050V 500GB                         | 2         | 0.77%   |
| Seagate ST500VT000-1DK142 500GB                   | 2         | 0.77%   |
| Seagate ST500LM030-1RK17D 500GB                   | 2         | 0.77%   |
| Seagate ST250LT003-9YG14C 250GB                   | 2         | 0.77%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 2         | 0.77%   |
| Samsung SSD PM830 2.5 7mm 128GB                   | 2         | 0.77%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.77%   |
| Samsung NVMe SSD Drive 512GB                      | 2         | 0.77%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD          | 2         | 0.77%   |
| Lexar 512GB SSD                                   | 2         | 0.77%   |
| Hitachi HTS545032B9A300 320GB                     | 2         | 0.77%   |
| HGST HTS725032A7E630 320GB                        | 2         | 0.77%   |
| HGST HTS545050A7E380 500GB                        | 2         | 0.77%   |
| HGST HTS541010A9E680 1TB                          | 2         | 0.77%   |
| Unknown                                           | 2         | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 78     | 42.03%  |
| Toshiba             | 26        | 31     | 18.84%  |
| WDC                 | 23        | 29     | 16.67%  |
| HGST                | 16        | 26     | 11.59%  |
| Hitachi             | 9         | 12     | 6.52%   |
| MARSHAL             | 5         | 5      | 3.62%   |
| Samsung Electronics | 1         | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 9      | 15.69%  |
| Samsung Electronics | 8         | 11     | 15.69%  |
| Crucial             | 6         | 8      | 11.76%  |
| Micron Technology   | 4         | 5      | 7.84%   |
| Lexar               | 4         | 4      | 7.84%   |
| WDC                 | 3         | 4      | 5.88%   |
| Toshiba             | 2         | 2      | 3.92%   |
| Kingston            | 2         | 4      | 3.92%   |
| TCSUNBOW            | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| MAX                 | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| KINGBANK            | 1         | 1      | 1.96%   |
| Golden              | 1         | 1      | 1.96%   |
| Eluktro             | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 135       | 182    | 54.22%  |
| SSD     | 50        | 61     | 20.08%  |
| NVMe    | 46        | 57     | 18.47%  |
| MMC     | 15        | 19     | 6.02%   |
| Unknown | 3         | 6      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 176       | 245    | 73.03%  |
| NVMe | 46        | 57     | 19.09%  |
| MMC  | 15        | 19     | 6.22%   |
| SAS  | 4         | 4      | 1.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 165    | 68.51%  |
| 0.51-1.0   | 52        | 63     | 28.73%  |
| 1.01-2.0   | 4         | 11     | 2.21%   |
| 3.01-4.0   | 1         | 4      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 62        | 26.61%  |
| 101-250        | 62        | 26.61%  |
| 501-1000       | 39        | 16.74%  |
| 51-100         | 22        | 9.44%   |
| 1001-2000      | 13        | 5.58%   |
| 1-20           | 10        | 4.29%   |
| Unknown        | 9         | 3.86%   |
| 21-50          | 7         | 3%      |
| 2001-3000      | 6         | 2.58%   |
| More than 3000 | 3         | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 26.86%  |
| 21-50          | 44        | 18.18%  |
| 101-250        | 42        | 17.36%  |
| 51-100         | 39        | 16.12%  |
| 251-500        | 25        | 10.33%  |
| 501-1000       | 10        | 4.13%   |
| Unknown        | 9         | 3.72%   |
| 1001-2000      | 4         | 1.65%   |
| More than 3000 | 3         | 1.24%   |
| 2001-3000      | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 8.82%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 5.88%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 5.88%   |
| Toshiba MQ01ABD050V 500GB             | 2         | 2      | 5.88%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 5.88%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 5.88%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 2.94%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 2.94%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.94%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 2.94%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 2.94%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.94%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.94%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 2.94%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 2.94%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.94%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 2.94%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 2.94%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.94%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 2.94%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 2.94%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 10        | 10     | 30.3%   |
| Toshiba  | 7         | 7      | 21.21%  |
| WDC      | 5         | 5      | 15.15%  |
| HGST     | 5         | 8      | 15.15%  |
| MARSHAL  | 2         | 2      | 6.06%   |
| Hitachi  | 2         | 3      | 6.06%   |
| SK hynix | 1         | 1      | 3.03%   |
| Crucial  | 1         | 2      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 32.26%  |
| Toshiba | 7         | 7      | 22.58%  |
| WDC     | 5         | 5      | 16.13%  |
| HGST    | 5         | 8      | 16.13%  |
| MARSHAL | 2         | 2      | 6.45%   |
| Hitachi | 2         | 3      | 6.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 35     | 93.94%  |
| SSD  | 2         | 3      | 6.06%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 129       | 183    | 55.84%  |
| Works    | 70        | 104    | 30.3%   |
| Malfunc  | 32        | 38     | 13.85%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 190       | 77.87%  |
| Samsung Electronics          | 22        | 9.02%   |
| AMD                          | 7         | 2.87%   |
| SanDisk                      | 6         | 2.46%   |
| Toshiba America Info Systems | 3         | 1.23%   |
| Silicon Motion               | 3         | 1.23%   |
| SK hynix                     | 2         | 0.82%   |
| Micron Technology            | 2         | 0.82%   |
| Union Memory (Shenzhen)      | 1         | 0.41%   |
| Shenzhen Longsys Electronics | 1         | 0.41%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.41%   |
| Lite-On Technology           | 1         | 0.41%   |
| KIOXIA                       | 1         | 0.41%   |
| Kingston Technology Company  | 1         | 0.41%   |
| ASMedia Technology           | 1         | 0.41%   |
| Apple                        | 1         | 0.41%   |
| ADATA Technology             | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 32        | 12.6%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 22        | 8.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 20        | 7.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 16        | 6.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 14        | 5.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 13        | 5.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 12        | 4.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 12        | 4.72%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 7         | 2.76%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 6         | 2.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 6         | 2.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 6         | 2.36%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 5         | 1.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 4         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 4         | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 4         | 1.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 3         | 1.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 3         | 1.18%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 3         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 3         | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 3         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 3         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 3         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 3         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                                                     | 3         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 3         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 2         | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 2         | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 2         | 0.79%   |
| Micron 2200S NVMe SSD [Cassandra]                                                                                  | 2         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 2         | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                                                      | 2         | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 2         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 0.79%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                                                              | 1         | 0.39%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                                                | 1         | 0.39%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.39%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                                          | 1         | 0.39%   |
| Samsung NVMe SSD Controller SM951/PM951                                                                            | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 172       | 69.35%  |
| NVMe | 46        | 18.55%  |
| RAID | 20        | 8.06%   |
| IDE  | 10        | 4.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 212       | 95.07%  |
| AMD    | 11        | 4.93%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 3.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 2.24%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 2.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 2.24%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 5         | 2.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 2.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 1.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 1.79%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 4         | 1.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.79%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.35%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.35%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.35%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.35%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.35%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.35%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.35%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.35%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.9%    |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.9%    |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 0.9%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.9%    |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 0.9%    |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 35.43%  |
| Intel Core i7           | 56        | 25.11%  |
| Intel Core i3           | 20        | 8.97%   |
| Intel Celeron           | 20        | 8.97%   |
| Other                   | 9         | 4.04%   |
| Intel Atom              | 9         | 4.04%   |
| Intel Pentium           | 5         | 2.24%   |
| AMD Ryzen 7             | 4         | 1.79%   |
| Intel Core i9           | 3         | 1.35%   |
| Intel Core 2 Duo        | 3         | 1.35%   |
| AMD Ryzen 5             | 3         | 1.35%   |
| Intel Pentium Dual-Core | 2         | 0.9%    |
| Intel Core 2            | 2         | 0.9%    |
| AMD A10                 | 2         | 0.9%    |
| Intel Pentium Gold      | 1         | 0.45%   |
| Intel Pentium Dual      | 1         | 0.45%   |
| Intel Genuine           | 1         | 0.45%   |
| Intel Core m3           | 1         | 0.45%   |
| AMD FX                  | 1         | 0.45%   |
| AMD E2                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 150       | 67.26%  |
| 4       | 57        | 25.56%  |
| 8       | 7         | 3.14%   |
| 6       | 5         | 2.24%   |
| 1       | 2         | 0.9%    |
| 14      | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 223       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 180       | 80.72%  |
| 1       | 42        | 18.83%  |
| Unknown | 1         | 0.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 98.65%  |
| 32-bit         | 2         | 0.9%    |
| Unknown        | 1         | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 32.19%  |
| 0x306a9    | 20        | 8.58%   |
| 0x206a7    | 17        | 7.3%    |
| 0x40651    | 15        | 6.44%   |
| 0x406e3    | 12        | 5.15%   |
| 0x306c3    | 9         | 3.86%   |
| 0x306d4    | 8         | 3.43%   |
| 0x806ec    | 6         | 2.58%   |
| 0x806ea    | 6         | 2.58%   |
| 0x806c1    | 6         | 2.58%   |
| 0x30678    | 5         | 2.15%   |
| 0x20655    | 5         | 2.15%   |
| 0x406c4    | 4         | 1.72%   |
| 0x906ea    | 3         | 1.29%   |
| 0x806e9    | 3         | 1.29%   |
| 0x706e5    | 3         | 1.29%   |
| 0x706a8    | 3         | 1.29%   |
| 0x1067a    | 3         | 1.29%   |
| 0x906e9    | 2         | 0.86%   |
| 0x806eb    | 2         | 0.86%   |
| 0x706a1    | 2         | 0.86%   |
| 0x6fd      | 2         | 0.86%   |
| 0x406c3    | 2         | 0.86%   |
| 0x106c2    | 2         | 0.86%   |
| 0x08608103 | 2         | 0.86%   |
| 0x08600106 | 2         | 0.86%   |
| 0xa0652    | 1         | 0.43%   |
| 0x906ec    | 1         | 0.43%   |
| 0x806c2    | 1         | 0.43%   |
| 0x6fa      | 1         | 0.43%   |
| 0x6f6      | 1         | 0.43%   |
| 0x6f2      | 1         | 0.43%   |
| 0x506e3    | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |
| 0x30673    | 1         | 0.43%   |
| 0x0a50000d | 1         | 0.43%   |
| 0x08600103 | 1         | 0.43%   |
| 0x08108109 | 1         | 0.43%   |
| 0x0600611a | 1         | 0.43%   |
| 0x05000119 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 17.94%  |
| Haswell          | 34        | 15.25%  |
| Skylake          | 22        | 9.87%   |
| IvyBridge        | 22        | 9.87%   |
| SandyBridge      | 19        | 8.52%   |
| Silvermont       | 15        | 6.73%   |
| Broadwell        | 14        | 6.28%   |
| TigerLake        | 9         | 4.04%   |
| Westmere         | 8         | 3.59%   |
| IceLake          | 7         | 3.14%   |
| Goldmont plus    | 6         | 2.69%   |
| Core             | 5         | 2.24%   |
| Zen 2            | 3         | 1.35%   |
| Penryn           | 3         | 1.35%   |
| Goldmont         | 3         | 1.35%   |
| Excavator        | 2         | 0.9%    |
| Bonnell          | 2         | 0.9%    |
| Unknown          | 2         | 0.9%    |
| Zen+             | 1         | 0.45%   |
| Zen 3            | 1         | 0.45%   |
| Steamroller      | 1         | 0.45%   |
| P6               | 1         | 0.45%   |
| CometLake        | 1         | 0.45%   |
| Bobcat           | 1         | 0.45%   |
| Alderlake Hybrid | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 200       | 79.68%  |
| AMD    | 26        | 10.36%  |
| Nvidia | 25        | 9.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 8.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 8.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 7.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.59%   |
| Intel HD Graphics 5500                                                                   | 14        | 5.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 4.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 4.26%   |
| Intel UHD Graphics 620                                                                   | 10        | 3.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.1%    |
| Intel HD Graphics 620                                                                    | 8         | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 3.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.33%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.16%   |
| Intel HD Graphics 500                                                                    | 3         | 1.16%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.78%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.78%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.78%   |
| AMD Lucienne                                                                             | 2         | 0.78%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.39%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.39%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.39%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.39%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.39%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.39%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 171       | 76.68%  |
| Intel + Nvidia | 16        | 7.17%   |
| 1 x AMD        | 14        | 6.28%   |
| Intel + AMD    | 11        | 4.93%   |
| 1 x Nvidia     | 8         | 3.59%   |
| 2 x Intel      | 2         | 0.9%    |
| 2 x AMD        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 213       | 94.67%  |
| Proprietary | 11        | 4.89%   |
| Unknown     | 1         | 0.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 81.42%  |
| 1.01-2.0   | 16        | 7.08%   |
| 0.01-0.5   | 13        | 5.75%   |
| 3.01-4.0   | 5         | 2.21%   |
| 7.01-8.0   | 4         | 1.77%   |
| 0.51-1.0   | 3         | 1.33%   |
| 5.01-6.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 26.38%  |
| Chimei Innolux          | 44        | 18.72%  |
| BOE                     | 33        | 14.04%  |
| LG Display              | 29        | 12.34%  |
| Samsung Electronics     | 20        | 8.51%   |
| Hewlett-Packard         | 9         | 3.83%   |
| Sharp                   | 5         | 2.13%   |
| Chi Mei Optoelectronics | 5         | 2.13%   |
| Apple                   | 4         | 1.7%    |
| LG Philips              | 3         | 1.28%   |
| KDC                     | 3         | 1.28%   |
| InfoVision              | 3         | 1.28%   |
| Lenovo                  | 2         | 0.85%   |
| HannStar                | 2         | 0.85%   |
| Dell                    | 2         | 0.85%   |
| CSO                     | 2         | 0.85%   |
| Unknown (XXX)           | 1         | 0.43%   |
| Sony                    | 1         | 0.43%   |
| Planar                  | 1         | 0.43%   |
| NEC Computers           | 1         | 0.43%   |
| Eizo                    | 1         | 0.43%   |
| CVT                     | 1         | 0.43%   |
| Acer                    | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 5         | 2.13%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 2.13%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 1.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.85%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.85%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.85%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.85%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.85%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.85%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.85%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.85%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.43%   |
| Sony TV SNY6F02 1360x768                                                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 1         | 0.43%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.43%   |
| Samsung Electronics S27E650 SAM0CCA 1920x1080 598x336mm 27.0-inch        | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 111       | 48.68%  |
| 1920x1080 (FHD)    | 68        | 29.82%  |
| 1600x900 (HD+)     | 18        | 7.89%   |
| 1280x800 (WXGA)    | 6         | 2.63%   |
| 3840x2160 (4K)     | 4         | 1.75%   |
| 1920x1200 (WUXGA)  | 3         | 1.32%   |
| 1440x900 (WXGA+)   | 3         | 1.32%   |
| 1360x768           | 2         | 0.88%   |
| 1024x600           | 2         | 0.88%   |
| 3840x2400          | 1         | 0.44%   |
| 3200x1800 (QHD+)   | 1         | 0.44%   |
| 3072x1920          | 1         | 0.44%   |
| 2560x1600          | 1         | 0.44%   |
| 2560x1440 (QHD)    | 1         | 0.44%   |
| 2560x1080          | 1         | 0.44%   |
| 2160x1440          | 1         | 0.44%   |
| 1680x1050 (WSXGA+) | 1         | 0.44%   |
| 1600x1200          | 1         | 0.44%   |
| 1280x1024 (SXGA)   | 1         | 0.44%   |
| Unknown            | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 81        | 34.62%  |
| 13      | 53        | 22.65%  |
| 14      | 49        | 20.94%  |
| 12      | 10        | 4.27%   |
| 11      | 9         | 3.85%   |
| 17      | 5         | 2.14%   |
| 23      | 3         | 1.28%   |
| 10      | 3         | 1.28%   |
| 27      | 2         | 0.85%   |
| 24      | 2         | 0.85%   |
| 21      | 2         | 0.85%   |
| 20      | 2         | 0.85%   |
| 18      | 2         | 0.85%   |
| 16      | 2         | 0.85%   |
| 84      | 1         | 0.43%   |
| 72      | 1         | 0.43%   |
| 46      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 34      | 1         | 0.43%   |
| 31      | 1         | 0.43%   |
| 26      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 70.09%  |
| 201-300     | 41        | 17.52%  |
| 501-600     | 8         | 3.42%   |
| 351-400     | 8         | 3.42%   |
| 401-500     | 6         | 2.56%   |
| 801-900     | 2         | 0.85%   |
| 1501-2000   | 2         | 0.85%   |
| 601-700     | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |
| Unknown     | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 89.14%  |
| 16/10   | 19        | 8.6%    |
| 5/4     | 1         | 0.45%   |
| 4/3     | 1         | 0.45%   |
| 3/2     | 1         | 0.45%   |
| 21/9    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 83        | 35.47%  |
| 101-110        | 80        | 34.19%  |
| 71-80          | 19        | 8.12%   |
| 61-70          | 10        | 4.27%   |
| 51-60          | 9         | 3.85%   |
| 201-250        | 7         | 2.99%   |
| 41-50          | 3         | 1.28%   |
| 151-200        | 3         | 1.28%   |
| 141-150        | 3         | 1.28%   |
| 121-130        | 3         | 1.28%   |
| More than 1000 | 2         | 0.85%   |
| 351-500        | 2         | 0.85%   |
| 301-350        | 2         | 0.85%   |
| 111-120        | 2         | 0.85%   |
| 501-1000       | 2         | 0.85%   |
| 251-300        | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |
| 91-100         | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 91        | 39.22%  |
| 101-120       | 89        | 38.36%  |
| 51-100        | 30        | 12.93%  |
| 161-240       | 13        | 5.6%    |
| More than 240 | 5         | 2.16%   |
| 1-50          | 3         | 1.29%   |
| Unknown       | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 199       | 86.52%  |
| 2     | 26        | 11.3%   |
| 0     | 4         | 1.74%   |
| 3     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 133       | 39.47%  |
| Realtek Semiconductor             | 95        | 28.19%  |
| Qualcomm Atheros                  | 46        | 13.65%  |
| Broadcom                          | 19        | 5.64%   |
| Hewlett-Packard                   | 7         | 2.08%   |
| Ralink                            | 5         | 1.48%   |
| Samsung Electronics               | 4         | 1.19%   |
| MediaTek                          | 4         | 1.19%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.89%   |
| Sierra Wireless                   | 3         | 0.89%   |
| Marvell Technology Group          | 3         | 0.89%   |
| Huawei Technologies               | 3         | 0.89%   |
| T & A Mobile Phones               | 2         | 0.59%   |
| Ralink Technology                 | 2         | 0.59%   |
| OPPO Electronics                  | 2         | 0.59%   |
| Ericsson Business Mobile Networks | 2         | 0.59%   |
| Broadcom Limited                  | 2         | 0.59%   |
| Spreadtrum Communications         | 1         | 0.3%    |
| LSI                               | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 53        | 12.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 5.34%   |
| Intel Wireless 7260                                                    | 22        | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 4.64%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 3.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 3.25%   |
| Intel Wireless 8260                                                    | 13        | 3.02%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 2.32%   |
| Intel Wireless 7265                                                    | 10        | 2.32%   |
| Intel Wireless 8265 / 8275                                             | 8         | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 5         | 1.16%   |
| Intel Centrino Advanced-N 6200                                         | 5         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.93%   |
| Intel Wireless 3160                                                    | 4         | 0.93%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.93%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.93%   |
| HP lt4112 Gobi 4G Module Network Device                                | 4         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 0.93%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                          | 3         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.7%    |
| MediaTek File-CD Gadget                                                | 3         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 3         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 52.86%  |
| Qualcomm Atheros                  | 41        | 18.06%  |
| Realtek Semiconductor             | 32        | 14.1%   |
| Broadcom                          | 17        | 7.49%   |
| Ralink                            | 5         | 2.2%    |
| Hewlett-Packard                   | 5         | 2.2%    |
| Sierra Wireless                   | 3         | 1.32%   |
| Ralink Technology                 | 2         | 0.88%   |
| Ericsson Business Mobile Networks | 1         | 0.44%   |
| Broadcom Limited                  | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 22        | 9.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 6.17%   |
| Intel Wireless 8260                                            | 13        | 5.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 4.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.41%   |
| Intel Wireless 7265                                            | 10        | 4.41%   |
| Intel Wireless 8265 / 8275                                     | 8         | 3.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 3.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.64%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.2%    |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 2.2%    |
| Intel Centrino Advanced-N 6200                                 | 5         | 2.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.76%   |
| Intel Wireless 3160                                            | 4         | 1.76%   |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.32%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 0.88%   |
| Sierra Wireless EM7455                                         | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 84        | 41.79%  |
| Realtek Semiconductor      | 81        | 40.3%   |
| Qualcomm Atheros           | 8         | 3.98%   |
| Samsung Electronics        | 4         | 1.99%   |
| MediaTek                   | 4         | 1.99%   |
| ZTE WCDMA Technologies MSM | 3         | 1.49%   |
| Marvell Technology Group   | 3         | 1.49%   |
| Broadcom                   | 3         | 1.49%   |
| T & A Mobile Phones        | 2         | 1%      |
| OPPO Electronics           | 2         | 1%      |
| Huawei Technologies        | 2         | 1%      |
| Hewlett-Packard            | 2         | 1%      |
| Spreadtrum Communications  | 1         | 0.5%    |
| LSI                        | 1         | 0.5%    |
| Broadcom Limited           | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 53        | 26.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 11.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 9.9%    |
| Intel Ethernet Connection I218-LM                                      | 16        | 7.92%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 5.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 2.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 2.97%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 2.48%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.98%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.98%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.98%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                          | 3         | 1.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 1.49%   |
| MediaTek File-CD Gadget                                                | 3         | 1.49%   |
| T & A Mobile Phones TCL 30 XE 5G                                       | 2         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.99%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.99%   |
| Huawei E353/E3131                                                      | 2         | 0.99%   |
| HP lt4120 Snapdragon X5 LTE                                            | 2         | 0.99%   |
| Spreadtrum Unisoc Phone                                                | 1         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.5%    |
| MediaTek moto e22                                                      | 1         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.5%    |
| LSI ET-131x PCI-E Ethernet Controller                                  | 1         | 0.5%    |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.5%    |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express               | 1         | 0.5%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 214       | 53.5%   |
| Ethernet | 184       | 46%     |
| Modem    | 2         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 81.03%  |
| Ethernet | 44        | 18.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 75%     |
| 1     | 44        | 19.64%  |
| 0     | 9         | 4.02%   |
| 3     | 3         | 1.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 218       | 97.76%  |
| Yes  | 5         | 2.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 53.41%  |
| Qualcomm Atheros Communications | 25        | 14.2%   |
| Realtek Semiconductor           | 17        | 9.66%   |
| Broadcom                        | 12        | 6.82%   |
| Ralink                          | 4         | 2.27%   |
| Lite-On Technology              | 4         | 2.27%   |
| IMC Networks                    | 4         | 2.27%   |
| Hewlett-Packard                 | 4         | 2.27%   |
| Toshiba                         | 2         | 1.14%   |
| Dell                            | 2         | 1.14%   |
| Apple                           | 2         | 1.14%   |
| Taiyo Yuden                     | 1         | 0.57%   |
| Realtek                         | 1         | 0.57%   |
| Foxconn / Hon Hai               | 1         | 0.57%   |
| Cambridge Silicon Radio         | 1         | 0.57%   |
| Alps Electric                   | 1         | 0.57%   |
| Unknown                         | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 57        | 32.39%  |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 7.95%   |
| Realtek Bluetooth Radio                             | 13        | 7.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 6.25%   |
| Intel AX201 Bluetooth                               | 9         | 5.11%   |
| Intel AX200 Bluetooth                               | 6         | 3.41%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.84%   |
| Broadcom HP Portable SoftSailing                    | 5         | 2.84%   |
| Ralink RT3290 Bluetooth                             | 4         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.7%    |
| IMC Networks Bluetooth Device                       | 3         | 1.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.7%    |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.14%   |
| Lite-On Bluetooth Device                            | 2         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.14%   |
| Intel Bluetooth Device                              | 2         | 1.14%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.14%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.57%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.57%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.57%   |
| Realtek Bluetooth Radio                             | 1         | 0.57%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.57%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.57%   |
| Intel AX210 Bluetooth                               | 1         | 0.57%   |
| IMC Networks Bluetooth                              | 1         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.57%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 204       | 85.36%  |
| AMD                         | 15        | 6.28%   |
| Nvidia                      | 11        | 4.6%    |
| Realtek Semiconductor       | 2         | 0.84%   |
| Generalplus Technology      | 2         | 0.84%   |
| Turtle Beach                | 1         | 0.42%   |
| Texas Instruments           | 1         | 0.42%   |
| GN Netcom                   | 1         | 0.42%   |
| FiiO Electronics Technology | 1         | 0.42%   |
| Apple                       | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 13.56%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 7.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 7.46%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 7.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 6.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 4.75%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 4.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 4.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 3.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 2.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.68%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.68%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.68%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.68%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.34%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.34%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.34%   |
| Realtek Semiconductor HP Banff                                                                    | 1         | 0.34%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.34%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.34%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 34.15%  |
| SK hynix            | 40        | 24.39%  |
| Micron Technology   | 19        | 11.59%  |
| Unknown             | 12        | 7.32%   |
| Kingston            | 10        | 6.1%    |
| Elpida              | 6         | 3.66%   |
| Ramaxel Technology  | 5         | 3.05%   |
| Crucial             | 5         | 3.05%   |
| A-DATA Technology   | 3         | 1.83%   |
| Apacer              | 2         | 1.22%   |
| Timetec             | 1         | 0.61%   |
| Qimonda             | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| Avant               | 1         | 0.61%   |
| Unknown             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 4.14%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 7         | 4.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 2.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 2.37%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 4         | 2.37%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 1.78%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 1.78%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 1.78%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 1.18%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 1.18%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.18%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.18%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.18%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 1.18%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 2         | 1.18%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 1.18%   |
| Apacer RAM 76.A302G.C4D0B 2GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.59%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.59%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.59%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s           | 1         | 0.59%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 62        | 50.41%  |
| DDR4   | 46        | 37.4%   |
| DDR2   | 6         | 4.88%   |
| LPDDR4 | 3         | 2.44%   |
| LPDDR3 | 3         | 2.44%   |
| SDRAM  | 1         | 0.81%   |
| DDR5   | 1         | 0.81%   |
| DDR    | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 113       | 85.61%  |
| Row Of Chips | 14        | 10.61%  |
| Chip         | 5         | 3.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 58        | 40.28%  |
| 8192  | 40        | 27.78%  |
| 2048  | 20        | 13.89%  |
| 16384 | 18        | 12.5%   |
| 1024  | 5         | 3.47%   |
| 32768 | 2         | 1.39%   |
| 512   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 51        | 36.69%  |
| 2667    | 26        | 18.71%  |
| 3200    | 12        | 8.63%   |
| 2133    | 10        | 7.19%   |
| 1334    | 9         | 6.47%   |
| 1333    | 8         | 5.76%   |
| 2400    | 5         | 3.6%    |
| 4267    | 3         | 2.16%   |
| 667     | 3         | 2.16%   |
| 3266    | 2         | 1.44%   |
| 1867    | 2         | 1.44%   |
| 800     | 2         | 1.44%   |
| Unknown | 2         | 1.44%   |
| 8400    | 1         | 0.72%   |
| 4800    | 1         | 0.72%   |
| 4199    | 1         | 0.72%   |
| 1067    | 1         | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 62        | 29.95%  |
| Cheng Uei Precision Industry (Foxlink) | 29        | 14.01%  |
| Bison Electronics                      | 14        | 6.76%   |
| Lite-On Technology                     | 12        | 5.8%    |
| Syntek                                 | 11        | 5.31%   |
| Sunplus Innovation Technology          | 11        | 5.31%   |
| Realtek Semiconductor                  | 10        | 4.83%   |
| Microdia                               | 10        | 4.83%   |
| IMC Networks                           | 10        | 4.83%   |
| Acer                                   | 5         | 2.42%   |
| Quanta                                 | 4         | 1.93%   |
| Apple                                  | 4         | 1.93%   |
| Silicon Motion                         | 3         | 1.45%   |
| Samsung Electronics                    | 3         | 1.45%   |
| Unknown                                | 2         | 0.97%   |
| Suyin                                  | 2         | 0.97%   |
| Ricoh                                  | 2         | 0.97%   |
| Luxvisions Innotech Limited            | 2         | 0.97%   |
| Logitech                               | 2         | 0.97%   |
| Importek                               | 2         | 0.97%   |
| Alcor Micro                            | 2         | 0.97%   |
| USB Camera                             | 1         | 0.48%   |
| Primax Electronics                     | 1         | 0.48%   |
| LG Electronics                         | 1         | 0.48%   |
| DigiTech                               | 1         | 0.48%   |
| ALi                                    | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 14        | 6.73%   |
| Chicony HP HD Webcam                                                       | 8         | 3.85%   |
| Syntek Integrated Camera                                                   | 7         | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3.37%   |
| Lite-On HP HD Webcam                                                       | 6         | 2.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.88%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.4%    |
| Lite-On HP HD Camera                                                       | 5         | 2.4%    |
| Chicony USB 2.0 Camera                                                     | 5         | 2.4%    |
| Chicony HP HD Webcam [Fixed]                                               | 5         | 2.4%    |
| Bison Integrated Camera                                                    | 5         | 2.4%    |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.92%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.44%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.44%   |
| Realtek Integrated Webcam                                                  | 3         | 1.44%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.44%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 1.44%   |
| Chicony HP HD Camera                                                       | 3         | 1.44%   |
| Chicony HD Webcam                                                          | 3         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 3         | 1.44%   |
| Bison ThinkPad P50 Integrated Camera                                       | 3         | 1.44%   |
| Unknown USB Camera                                                         | 2         | 0.96%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.96%   |
| Syntek EasyCamera                                                          | 2         | 0.96%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.96%   |
| Importek HP Webcam-50                                                      | 2         | 0.96%   |
| IMC Networks Integrated Camera                                             | 2         | 0.96%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.96%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 0.96%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.96%   |
| Chicony HP Webcam                                                          | 2         | 0.96%   |
| Chicony HP Truevision HD                                                   | 2         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 2         | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 2         | 0.96%   |
| Acer Integrated Camera                                                     | 2         | 0.96%   |
| USB Camera USB Camera                                                      | 1         | 0.48%   |
| Suyin HP Webcam                                                            | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 49        | 69.01%  |
| Synaptics                  | 12        | 16.9%   |
| Shenzhen Goodix Technology | 6         | 8.45%   |
| AuthenTec                  | 2         | 2.82%   |
| LighTuning Technology      | 1         | 1.41%   |
| Elan Microelectronics      | 1         | 1.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 26.76%  |
| Validity Sensors VFS491                                                    | 10        | 14.08%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.63%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 4.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.23%   |
| Synaptics WBDI Device                                                      | 3         | 4.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 2.82%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.82%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.41%   |
| Synaptics  WBDI                                                            | 1         | 1.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.41%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 50%     |
| Alcor Micro | 3         | 25%     |
| Upek        | 2         | 16.67%  |
| O2 Micro    | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 133       | 58.85%  |
| 1     | 74        | 32.74%  |
| 2     | 17        | 7.52%   |
| 3     | 2         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 61.4%   |
| Chipcard                 | 11        | 9.65%   |
| Graphics card            | 10        | 8.77%   |
| Net/wireless             | 6         | 5.26%   |
| Bluetooth                | 5         | 4.39%   |
| Camera                   | 4         | 3.51%   |
| Storage                  | 3         | 2.63%   |
| Net/ethernet             | 2         | 1.75%   |
| Communication controller | 2         | 1.75%   |
| Sound                    | 1         | 0.88%   |


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

Total: 293

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 33        | 15.14%  |
| Ubuntu 22.04                 | 22        | 10.09%  |
| Ubuntu 18.04                 | 15        | 6.88%   |
| Zorin 16                     | 6         | 2.75%   |
| Linux Mint 20.3              | 6         | 2.75%   |
| Fedora 36                    | 6         | 2.75%   |
| Manjaro                      | 5         | 2.29%   |
| Zorin 15                     | 4         | 1.83%   |
| Ubuntu 23.04                 | 4         | 1.83%   |
| Ubuntu 20.10                 | 4         | 1.83%   |
| Ubuntu 19.04                 | 4         | 1.83%   |
| Pop!_OS 20.04                | 4         | 1.83%   |
| OpenMandriva 4.2             | 4         | 1.83%   |
| Arch Rolling                 | 4         | 1.83%   |
| Arch                         | 4         | 1.83%   |
| Ubuntu 21.04                 | 3         | 1.38%   |
| Q4OS 3                       | 3         | 1.38%   |
| Linux Mint 20.2              | 3         | 1.38%   |
| Fedora 37                    | 3         | 1.38%   |
| Debian 11                    | 3         | 1.38%   |
| Ubuntu 21.10                 | 2         | 0.92%   |
| Ubuntu 19.10                 | 2         | 0.92%   |
| Pop!_OS 22.04                | 2         | 0.92%   |
| Parrot 5.3                   | 2         | 0.92%   |
| Parrot 5.1                   | 2         | 0.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.92%   |
| Linux Mint 19                | 2         | 0.92%   |
| Kali 2023.2                  | 2         | 0.92%   |
| Kali 2022.3                  | 2         | 0.92%   |
| Fedora 35                    | 2         | 0.92%   |
| Fedora 32                    | 2         | 0.92%   |
| Endless 3.9.4                | 2         | 0.92%   |
| Endless 3.9.2                | 2         | 0.92%   |
| Endless 3.9.1                | 2         | 0.92%   |
| Xubuntu 20.04                | 1         | 0.46%   |
| Ubuntu MATE 21.04            | 1         | 0.46%   |
| Ubuntu MATE 20.04            | 1         | 0.46%   |
| Ubuntu Budgie 20.04          | 1         | 0.46%   |
| Ubuntu 22.10                 | 1         | 0.46%   |
| Ubuntu 16.04                 | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 84        | 41.58%  |
| Fedora        | 15        | 7.43%   |
| Linux Mint    | 12        | 5.94%   |
| Zorin         | 10        | 4.95%   |
| Pop!_OS       | 8         | 3.96%   |
| Parrot        | 8         | 3.96%   |
| Manjaro       | 8         | 3.96%   |
| Endless       | 8         | 3.96%   |
| Arch          | 8         | 3.96%   |
| Kali          | 6         | 2.97%   |
| OpenMandriva  | 5         | 2.48%   |
| Debian        | 5         | 2.48%   |
| Q4OS          | 3         | 1.49%   |
| Ubuntu MATE   | 2         | 0.99%   |
| ROSA          | 2         | 0.99%   |
| RHEL          | 2         | 0.99%   |
| openSUSE      | 2         | 0.99%   |
| Elementary    | 2         | 0.99%   |
| Xubuntu       | 1         | 0.5%    |
| Ubuntu Budgie | 1         | 0.5%    |
| Nobara        | 1         | 0.5%    |
| Lubuntu       | 1         | 0.5%    |
| LMDE          | 1         | 0.5%    |
| Lilidog       | 1         | 0.5%    |
| KDE neon      | 1         | 0.5%    |
| Garuda Linux  | 1         | 0.5%    |
| Deepin        | 1         | 0.5%    |
| blendOS       | 1         | 0.5%    |
| BlackPanther  | 1         | 0.5%    |
| antiX         | 1         | 0.5%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 2.56%   |
| 5.15.0-58-generic        | 4         | 1.71%   |
| 5.15.0-52-generic        | 4         | 1.71%   |
| 5.11.0-38-generic        | 4         | 1.71%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.71%   |
| 5.4.0-58-generic         | 3         | 1.28%   |
| 5.4.0-52-generic         | 3         | 1.28%   |
| 5.4.0-45-generic         | 3         | 1.28%   |
| 5.4.0-42-generic         | 3         | 1.28%   |
| 5.19.0-38-generic        | 3         | 1.28%   |
| 5.15.0-53-generic        | 3         | 1.28%   |
| 5.15.0-41-generic        | 3         | 1.28%   |
| 4.19.0-17-amd64          | 3         | 1.28%   |
| 6.1.0-kali7-amd64        | 2         | 0.85%   |
| 5.8.0-59-generic         | 2         | 0.85%   |
| 5.8.0-43-generic         | 2         | 0.85%   |
| 5.4.0-67-generic         | 2         | 0.85%   |
| 5.4.0-65-generic         | 2         | 0.85%   |
| 5.4.0-54-generic         | 2         | 0.85%   |
| 5.4.0-48-generic         | 2         | 0.85%   |
| 5.4.0-47-generic         | 2         | 0.85%   |
| 5.4.0-37-generic         | 2         | 0.85%   |
| 5.4.0-137-generic        | 2         | 0.85%   |
| 5.3.0-28-generic         | 2         | 0.85%   |
| 5.19.0-41-generic        | 2         | 0.85%   |
| 5.19.0-35-generic        | 2         | 0.85%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.85%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.85%   |
| 5.15.0-46-generic        | 2         | 0.85%   |
| 5.13.19-2-MANJARO        | 2         | 0.85%   |
| 5.13.0-27-generic        | 2         | 0.85%   |
| 5.11.0-37-generic        | 2         | 0.85%   |
| 5.11.0-34-generic        | 2         | 0.85%   |
| 6.4.8-arch1-1            | 1         | 0.43%   |
| 6.3.6-arch1-1            | 1         | 0.43%   |
| 6.3.5-060305-generic     | 1         | 0.43%   |
| 6.3.4-arch1-1            | 1         | 0.43%   |
| 6.3.4-1-default          | 1         | 0.43%   |
| 6.3.0-kali1-amd64        | 1         | 0.43%   |
| 6.2.9-200.fc37.x86_64    | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 17.57%  |
| 5.15.0  | 21        | 9.46%   |
| 5.8.0   | 18        | 8.11%   |
| 5.11.0  | 14        | 6.31%   |
| 4.15.0  | 11        | 4.95%   |
| 5.19.0  | 8         | 3.6%    |
| 5.3.0   | 7         | 3.15%   |
| 5.13.0  | 7         | 3.15%   |
| 5.0.0   | 7         | 3.15%   |
| 6.1.0   | 6         | 2.7%    |
| 5.10.0  | 5         | 2.25%   |
| 5.18.0  | 4         | 1.8%    |
| 5.10.14 | 4         | 1.8%    |
| 4.19.0  | 4         | 1.8%    |
| 4.18.0  | 3         | 1.35%   |
| 6.3.4   | 2         | 0.9%    |
| 6.2.0   | 2         | 0.9%    |
| 5.19.9  | 2         | 0.9%    |
| 5.18.13 | 2         | 0.9%    |
| 5.17.5  | 2         | 0.9%    |
| 5.16.7  | 2         | 0.9%    |
| 5.14.0  | 2         | 0.9%    |
| 5.13.19 | 2         | 0.9%    |
| 6.4.8   | 1         | 0.45%   |
| 6.3.6   | 1         | 0.45%   |
| 6.3.5   | 1         | 0.45%   |
| 6.3.0   | 1         | 0.45%   |
| 6.2.9   | 1         | 0.45%   |
| 6.2.6   | 1         | 0.45%   |
| 6.2.15  | 1         | 0.45%   |
| 6.2.11  | 1         | 0.45%   |
| 6.1.29  | 1         | 0.45%   |
| 6.1.15  | 1         | 0.45%   |
| 6.0.12  | 1         | 0.45%   |
| 6.0.0   | 1         | 0.45%   |
| 5.9.14  | 1         | 0.45%   |
| 5.9.13  | 1         | 0.45%   |
| 5.8.4   | 1         | 0.45%   |
| 5.8.12  | 1         | 0.45%   |
| 5.7.17  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 17.73%  |
| 5.15    | 23        | 10.45%  |
| 5.8     | 20        | 9.09%   |
| 5.11    | 15        | 6.82%   |
| 5.19    | 13        | 5.91%   |
| 5.10    | 12        | 5.45%   |
| 4.15    | 11        | 5%      |
| 5.13    | 9         | 4.09%   |
| 6.1     | 8         | 3.64%   |
| 5.0     | 8         | 3.64%   |
| 5.3     | 7         | 3.18%   |
| 6.2     | 6         | 2.73%   |
| 5.18    | 6         | 2.73%   |
| 6.3     | 5         | 2.27%   |
| 5.14    | 5         | 2.27%   |
| 4.19    | 5         | 2.27%   |
| 5.16    | 4         | 1.82%   |
| 4.18    | 4         | 1.82%   |
| 5.6     | 3         | 1.36%   |
| 5.17    | 3         | 1.36%   |
| 6.0     | 2         | 0.91%   |
| 5.9     | 2         | 0.91%   |
| 5.2     | 2         | 0.91%   |
| 4.9     | 2         | 0.91%   |
| 6.4     | 1         | 0.45%   |
| 5.7     | 1         | 0.45%   |
| 5.5     | 1         | 0.45%   |
| 5.1     | 1         | 0.45%   |
| 4.16    | 1         | 0.45%   |
| 4.13    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 98.48%  |
| i686   | 3         | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 122       | 60.1%   |
| Unknown         | 20        | 9.85%   |
| KDE5            | 19        | 9.36%   |
| X-Cinnamon      | 11        | 5.42%   |
| XFCE            | 9         | 4.43%   |
| MATE            | 9         | 4.43%   |
| KDE             | 4         | 1.97%   |
| Pantheon        | 2         | 0.99%   |
| KDE4            | 2         | 0.99%   |
| openbox         | 1         | 0.49%   |
| LXQt            | 1         | 0.49%   |
| GNOME Flashback | 1         | 0.49%   |
| Deepin          | 1         | 0.49%   |
| Cinnamon        | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 139       | 67.8%   |
| Wayland | 54        | 26.34%  |
| Unknown | 11        | 5.37%   |
| Tty     | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 47.55%  |
| GDM3    | 31        | 15.2%   |
| GDM     | 31        | 15.2%   |
| SDDM    | 20        | 9.8%    |
| LightDM | 18        | 8.82%   |
| TDM     | 5         | 2.45%   |
| KDM     | 2         | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 151       | 75.5%   |
| Unknown | 24        | 12%     |
| en_GB   | 22        | 11%     |
| C       | 2         | 1%      |
| en_AG   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 108       | 53.47%  |
| EFI  | 94        | 46.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 162       | 81%     |
| Btrfs   | 20        | 10%     |
| Overlay | 9         | 4.5%    |
| Tmpfs   | 4         | 2%      |
| Xfs     | 2         | 1%      |
| Unknown | 2         | 1%      |
| Zfs     | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 101       | 49.51%  |
| GPT     | 75        | 36.76%  |
| MBR     | 28        | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 88%     |
| Yes       | 24        | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 70.85%  |
| Yes       | 58        | 29.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 86        | 43.43%  |
| Lenovo                      | 44        | 22.22%  |
| Dell                        | 23        | 11.62%  |
| ASUSTek Computer            | 9         | 4.55%   |
| Toshiba                     | 8         | 4.04%   |
| Acer                        | 4         | 2.02%   |
| Samsung Electronics         | 3         | 1.52%   |
| Apple                       | 3         | 1.52%   |
| Chuwi                       | 2         | 1.01%   |
| TECNO                       | 1         | 0.51%   |
| Sony                        | 1         | 0.51%   |
| SLIMBOOK                    | 1         | 0.51%   |
| Panasonic                   | 1         | 0.51%   |
| Notebook                    | 1         | 0.51%   |
| Insyde                      | 1         | 0.51%   |
| I-Life Digital Technologies | 1         | 0.51%   |
| HUAWEI                      | 1         | 0.51%   |
| Getac                       | 1         | 0.51%   |
| Fujitsu                     | 1         | 0.51%   |
| EVOC                        | 1         | 0.51%   |
| EUROCOM                     | 1         | 0.51%   |
| Endless                     | 1         | 0.51%   |
| Eluktronics                 | 1         | 0.51%   |
| Clevo                       | 1         | 0.51%   |
| Unknown                     | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook 840 G1                     | 6         | 3.03%   |
| HP EliteBook 840 G3                     | 5         | 2.53%   |
| Dell XPS 13 9310                        | 4         | 2.02%   |
| HP Notebook                             | 3         | 1.52%   |
| HP EliteBook Folio 9480m                | 3         | 1.52%   |
| HP EliteBook Folio 9470m                | 3         | 1.52%   |
| HP EliteBook 8460p                      | 3         | 1.52%   |
| HP EliteBook 2570p                      | 3         | 1.52%   |
| HP 15                                   | 3         | 1.52%   |
| Unknown                                 | 3         | 1.52%   |
| Toshiba Satellite C660                  | 2         | 1.01%   |
| Lenovo IdeaPad S340-14IIL 81VV          | 2         | 1.01%   |
| HP ProBook 6560b                        | 2         | 1.01%   |
| HP ProBook 640 G1                       | 2         | 1.01%   |
| HP ProBook 440 G5                       | 2         | 1.01%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.01%   |
| HP ENVY 15                              | 2         | 1.01%   |
| HP EliteBook 8440p                      | 2         | 1.01%   |
| HP EliteBook 840 G2                     | 2         | 1.01%   |
| HP Compaq Mini 110c-1100                | 2         | 1.01%   |
| HP 630                                  | 2         | 1.01%   |
| HP 15 Notebook PC                       | 2         | 1.01%   |
| Dell Latitude E6410                     | 2         | 1.01%   |
| Dell Inspiron 5767                      | 2         | 1.01%   |
| ASUS X540NA                             | 2         | 1.01%   |
| Toshiba TECRA A50-A                     | 1         | 0.51%   |
| Toshiba Satellite L50-B                 | 1         | 0.51%   |
| Toshiba Satellite C850D-B615            | 1         | 0.51%   |
| Toshiba R84SAU2                         | 1         | 0.51%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.51%   |
| Toshiba dynabook R731/E                 | 1         | 0.51%   |
| TECNO WinPad 2                          | 1         | 0.51%   |
| Sony VGN-NS295J                         | 1         | 0.51%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.51%   |
| Samsung RC410/RC510/RC710               | 1         | 0.51%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.51%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.51%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.51%   |
| Notebook P65xHP                         | 1         | 0.51%   |
| Lenovo Z50-75 80EC                      | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 35        | 17.68%  |
| Lenovo ThinkPad        | 22        | 11.11%  |
| HP ProBook             | 16        | 8.08%   |
| Lenovo IdeaPad         | 11        | 5.56%   |
| Dell Latitude          | 10        | 5.05%   |
| HP Pavilion            | 8         | 4.04%   |
| Dell Inspiron          | 8         | 4.04%   |
| HP Laptop              | 5         | 2.53%   |
| HP 15                  | 5         | 2.53%   |
| Dell XPS               | 5         | 2.53%   |
| Toshiba Satellite      | 4         | 2.02%   |
| HP ENVY                | 4         | 2.02%   |
| Acer Aspire            | 4         | 2.02%   |
| Lenovo Legion          | 3         | 1.52%   |
| HP Notebook            | 3         | 1.52%   |
| Unknown                | 3         | 1.52%   |
| Toshiba dynabook       | 2         | 1.01%   |
| HP Compaq              | 2         | 1.01%   |
| HP 630                 | 2         | 1.01%   |
| ASUS X540NA            | 2         | 1.01%   |
| Toshiba TECRA          | 1         | 0.51%   |
| Toshiba R84SAU2        | 1         | 0.51%   |
| TECNO WinPad           | 1         | 0.51%   |
| Sony VGN-NS295J        | 1         | 0.51%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.51%   |
| Samsung RC410          | 1         | 0.51%   |
| Samsung 300E5EV        | 1         | 0.51%   |
| Samsung 300E4C         | 1         | 0.51%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.51%   |
| Notebook P65xHP        | 1         | 0.51%   |
| Lenovo Z50-75          | 1         | 0.51%   |
| Lenovo V330-14IKB      | 1         | 0.51%   |
| Lenovo V310-15ISK      | 1         | 0.51%   |
| Lenovo V14-IGL         | 1         | 0.51%   |
| Lenovo V130-14IKB      | 1         | 0.51%   |
| Lenovo V110-15ISK      | 1         | 0.51%   |
| Lenovo ThinkBook       | 1         | 0.51%   |
| Lenovo E51-80          | 1         | 0.51%   |
| Insyde i101c           | 1         | 0.51%   |
| I-Life Digital ZED     | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 23        | 11.62%  |
| 2013    | 22        | 11.11%  |
| 2012    | 19        | 9.6%    |
| 2019    | 18        | 9.09%   |
| 2018    | 18        | 9.09%   |
| 2011    | 16        | 8.08%   |
| 2015    | 15        | 7.58%   |
| 2014    | 14        | 7.07%   |
| 2017    | 13        | 6.57%   |
| 2020    | 12        | 6.06%   |
| 2010    | 12        | 6.06%   |
| 2021    | 7         | 3.54%   |
| 2009    | 2         | 1.01%   |
| 2008    | 2         | 1.01%   |
| 2007    | 2         | 1.01%   |
| 2006    | 2         | 1.01%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 198       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 185       | 92.04%  |
| Enabled  | 16        | 7.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 31%     |
| 3.01-4.0    | 56        | 28%     |
| 8.01-16.0   | 30        | 15%     |
| 16.01-24.0  | 24        | 12%     |
| 1.01-2.0    | 14        | 7%      |
| 32.01-64.0  | 7         | 3.5%    |
| 64.01-256.0 | 3         | 1.5%    |
| 24.01-32.0  | 2         | 1%      |
| 2.01-3.0    | 1         | 0.5%    |
| 0.51-1.0    | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 64        | 28.83%  |
| 1.01-2.0  | 59        | 26.58%  |
| 3.01-4.0  | 40        | 18.02%  |
| 4.01-8.0  | 37        | 16.67%  |
| 0.51-1.0  | 17        | 7.66%   |
| 8.01-16.0 | 5         | 2.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 169       | 83.25%  |
| 2      | 28        | 13.79%  |
| 0      | 2         | 0.99%   |
| 10     | 1         | 0.49%   |
| 8      | 1         | 0.49%   |
| 4      | 1         | 0.49%   |
| 3      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 60.61%  |
| Yes       | 78        | 39.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 83.33%  |
| No        | 33        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 95.48%  |
| No        | 9         | 4.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 76%     |
| No        | 48        | 24%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 198       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Nairobi  | 184       | 89.76%  |
| Mombasa  | 3         | 1.46%   |
| Kiambu   | 3         | 1.46%   |
| Nakuru   | 2         | 0.98%   |
| Kikuyu   | 2         | 0.98%   |
| Eldoret  | 2         | 0.98%   |
| Wote     | 1         | 0.49%   |
| Rongai   | 1         | 0.49%   |
| Nyeri    | 1         | 0.49%   |
| Narok    | 1         | 0.49%   |
| Nanyuki  | 1         | 0.49%   |
| Murang'a | 1         | 0.49%   |
| Maralal  | 1         | 0.49%   |
| Machakos | 1         | 0.49%   |
| Kisii    | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 72     | 24.11%  |
| Toshiba             | 28        | 33     | 12.5%   |
| WDC                 | 27        | 34     | 12.05%  |
| Samsung Electronics | 26        | 37     | 11.61%  |
| HGST                | 14        | 24     | 6.25%   |
| Unknown             | 12        | 16     | 5.36%   |
| Sandisk             | 9         | 10     | 4.02%   |
| Hitachi             | 9         | 11     | 4.02%   |
| Micron Technology   | 6         | 7      | 2.68%   |
| Crucial             | 6         | 8      | 2.68%   |
| MARSHAL             | 5         | 5      | 2.23%   |
| Lexar               | 4         | 4      | 1.79%   |
| SK hynix            | 3         | 3      | 1.34%   |
| Kingston            | 3         | 5      | 1.34%   |
| SPCC                | 2         | 2      | 0.89%   |
| Apple               | 2         | 2      | 0.89%   |
| TCSUNBOW            | 1         | 1      | 0.45%   |
| Plextor             | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| MAX                 | 1         | 1      | 0.45%   |
| LITEONIT            | 1         | 1      | 0.45%   |
| KINGBANK            | 1         | 1      | 0.45%   |
| Intel               | 1         | 1      | 0.45%   |
| HUAWEI              | 1         | 1      | 0.45%   |
| Hjwdz               | 1         | 1      | 0.45%   |
| Golden              | 1         | 1      | 0.45%   |
| Eluktro             | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |
| CARLSTEIN           | 1         | 4      | 0.45%   |
| A-DATA Technology   | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 4.33%   |
| Seagate ST500LT012-9WS142 500GB                     | 7         | 3.03%   |
| HGST HTS725050A7E630 500GB                          | 6         | 2.6%    |
| Toshiba MQ04ABF100 1TB                              | 5         | 2.16%   |
| Seagate ST9500325AS 500GB                           | 5         | 2.16%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 1.73%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 1.73%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 1.73%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 1.73%   |
| Samsung SSD 960 EVO 1TB                             | 4         | 1.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 1.73%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 3         | 1.3%    |
| WDC PC SN730 NVMe 512GB                             | 3         | 1.3%    |
| Unknown MMC Card  64GB                              | 3         | 1.3%    |
| Unknown MMC Card  32GB                              | 3         | 1.3%    |
| MARSHAL MAL2500SA-T54L 500GB                        | 3         | 1.3%    |
| Crucial CT2050MX300SSD1 2TB                         | 3         | 1.3%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.87%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 2         | 0.87%   |
| WDC WD2500BEKT-75PVMT0 250GB                        | 2         | 0.87%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 0.87%   |
| Unknown NCard  32GB                                 | 2         | 0.87%   |
| Toshiba MQ01ABD050V 500GB                           | 2         | 0.87%   |
| Seagate ST500VT000-1DK142 500GB                     | 2         | 0.87%   |
| Seagate ST500LM030-1RK17D 500GB                     | 2         | 0.87%   |
| Seagate ST250LT003-9YG14C 250GB                     | 2         | 0.87%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 2         | 0.87%   |
| Samsung SSD PM830 2.5 7mm 128GB                     | 2         | 0.87%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.87%   |
| Samsung NVMe SSD Drive 256GB                        | 2         | 0.87%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD            | 2         | 0.87%   |
| Hitachi HTS545032B9A300 320GB                       | 2         | 0.87%   |
| HGST HTS725032A7E630 320GB                          | 2         | 0.87%   |
| HGST HTS541010A9E680 1TB                            | 2         | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.43%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD                      | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.43%   |
| WDC WD5000LPCX-22VHAT1 500GB                        | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 72     | 42.52%  |
| Toshiba             | 24        | 29     | 18.9%   |
| WDC                 | 20        | 26     | 15.75%  |
| HGST                | 14        | 24     | 11.02%  |
| Hitachi             | 9         | 11     | 7.09%   |
| MARSHAL             | 5         | 5      | 3.94%   |
| Samsung Electronics | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 9      | 17.39%  |
| Samsung Electronics | 8         | 11     | 17.39%  |
| Crucial             | 6         | 8      | 13.04%  |
| Micron Technology   | 4         | 5      | 8.7%    |
| Lexar               | 3         | 3      | 6.52%   |
| WDC                 | 2         | 3      | 4.35%   |
| Kingston            | 2         | 4      | 4.35%   |
| Toshiba             | 1         | 1      | 2.17%   |
| TCSUNBOW            | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| Netac               | 1         | 1      | 2.17%   |
| MAX                 | 1         | 1      | 2.17%   |
| LITEONIT            | 1         | 1      | 2.17%   |
| KINGBANK            | 1         | 1      | 2.17%   |
| Golden              | 1         | 1      | 2.17%   |
| Eluktro             | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 124       | 168    | 55.86%  |
| SSD     | 45        | 56     | 20.27%  |
| NVMe    | 38        | 44     | 17.12%  |
| MMC     | 12        | 16     | 5.41%   |
| Unknown | 3         | 6      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 160       | 226    | 74.77%  |
| NVMe | 38        | 44     | 17.76%  |
| MMC  | 12        | 16     | 5.61%   |
| SAS  | 4         | 4      | 1.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 116       | 154    | 70.3%   |
| 0.51-1.0   | 43        | 54     | 26.06%  |
| 1.01-2.0   | 5         | 12     | 3.03%   |
| 3.01-4.0   | 1         | 4      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 59        | 28.64%  |
| 101-250        | 51        | 24.76%  |
| 501-1000       | 32        | 15.53%  |
| 51-100         | 17        | 8.25%   |
| 1001-2000      | 13        | 6.31%   |
| 1-20           | 9         | 4.37%   |
| Unknown        | 9         | 4.37%   |
| 21-50          | 7         | 3.4%    |
| 2001-3000      | 6         | 2.91%   |
| More than 3000 | 3         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 55        | 25.82%  |
| 21-50          | 38        | 17.84%  |
| 101-250        | 36        | 16.9%   |
| 51-100         | 36        | 16.9%   |
| 251-500        | 21        | 9.86%   |
| 501-1000       | 10        | 4.69%   |
| Unknown        | 9         | 4.23%   |
| 1001-2000      | 4         | 1.88%   |
| More than 3000 | 3         | 1.41%   |
| 2001-3000      | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 9.38%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 6.25%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 6.25%   |
| Toshiba MQ01ABD050V 500GB             | 2         | 2      | 6.25%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 6.25%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 3.13%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.13%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 3.13%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 3.13%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 3.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 3.13%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 3.13%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 3.13%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 3.13%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 3.13%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 3.13%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 3.13%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 3.13%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 3.13%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 10        | 10     | 32.26%  |
| Toshiba  | 7         | 7      | 22.58%  |
| WDC      | 4         | 4      | 12.9%   |
| HGST     | 4         | 7      | 12.9%   |
| MARSHAL  | 2         | 2      | 6.45%   |
| Hitachi  | 2         | 2      | 6.45%   |
| SK hynix | 1         | 1      | 3.23%   |
| Crucial  | 1         | 2      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 34.48%  |
| Toshiba | 7         | 7      | 24.14%  |
| WDC     | 4         | 4      | 13.79%  |
| HGST    | 4         | 7      | 13.79%  |
| MARSHAL | 2         | 2      | 6.9%    |
| Hitachi | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 32     | 93.55%  |
| SSD  | 2         | 3      | 6.45%   |

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
| Detected | 115       | 165    | 56.37%  |
| Works    | 59        | 90     | 28.92%  |
| Malfunc  | 30        | 35     | 14.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 170       | 79.07%  |
| Samsung Electronics          | 19        | 8.84%   |
| AMD                          | 7         | 3.26%   |
| SanDisk                      | 6         | 2.79%   |
| Toshiba America Info Systems | 3         | 1.4%    |
| SK hynix                     | 2         | 0.93%   |
| Silicon Motion               | 2         | 0.93%   |
| Micron Technology            | 2         | 0.93%   |
| Shenzhen Longsys Electronics | 1         | 0.47%   |
| Kingston Technology Company  | 1         | 0.47%   |
| ASMedia Technology           | 1         | 0.47%   |
| Apple                        | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 12.95%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 20        | 8.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 4.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 4.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 4.46%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 3.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 2.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 2.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.79%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.34%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.34%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.34%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.89%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.89%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.45%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 1         | 0.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.45%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.45%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.45%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.45%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 1         | 0.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.45%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 154       | 70%     |
| NVMe | 38        | 17.27%  |
| RAID | 19        | 8.64%   |
| IDE  | 9         | 4.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 187       | 94.44%  |
| AMD    | 11        | 5.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 3.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 2.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 2.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 5         | 2.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 2.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 2.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 4         | 2.02%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 2.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.52%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.52%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.52%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.52%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.52%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.01%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 1.01%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.01%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 1.01%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.01%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.01%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.01%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.01%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.01%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 69        | 34.85%  |
| Intel Core i7           | 51        | 25.76%  |
| Intel Core i3           | 19        | 9.6%    |
| Intel Celeron           | 16        | 8.08%   |
| Intel Atom              | 8         | 4.04%   |
| Other                   | 7         | 3.54%   |
| Intel Pentium           | 5         | 2.53%   |
| AMD Ryzen 7             | 4         | 2.02%   |
| Intel Core i9           | 3         | 1.52%   |
| Intel Core 2 Duo        | 3         | 1.52%   |
| AMD Ryzen 5             | 3         | 1.52%   |
| Intel Pentium Dual-Core | 2         | 1.01%   |
| Intel Core 2            | 2         | 1.01%   |
| AMD A10                 | 2         | 1.01%   |
| Intel Pentium Dual      | 1         | 0.51%   |
| Intel Core m3           | 1         | 0.51%   |
| AMD FX                  | 1         | 0.51%   |
| AMD E2                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 130       | 65.66%  |
| 4       | 53        | 26.77%  |
| 8       | 7         | 3.54%   |
| 6       | 5         | 2.53%   |
| 1       | 2         | 1.01%   |
| Unknown | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 161       | 81.31%  |
| 1       | 36        | 18.18%  |
| Unknown | 1         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 98.99%  |
| 32-bit         | 2         | 1.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 27.05%  |
| 0x306a9    | 18        | 8.7%    |
| 0x206a7    | 17        | 8.21%   |
| 0x40651    | 15        | 7.25%   |
| 0x406e3    | 11        | 5.31%   |
| 0x306c3    | 9         | 4.35%   |
| 0x306d4    | 7         | 3.38%   |
| 0x806ec    | 6         | 2.9%    |
| 0x806ea    | 6         | 2.9%    |
| 0x806c1    | 5         | 2.42%   |
| 0x30678    | 5         | 2.42%   |
| 0x20655    | 5         | 2.42%   |
| 0x906ea    | 3         | 1.45%   |
| 0x806e9    | 3         | 1.45%   |
| 0x706e5    | 3         | 1.45%   |
| 0x406c4    | 3         | 1.45%   |
| 0x1067a    | 3         | 1.45%   |
| 0x906e9    | 2         | 0.97%   |
| 0x806eb    | 2         | 0.97%   |
| 0x706a8    | 2         | 0.97%   |
| 0x706a1    | 2         | 0.97%   |
| 0x6fd      | 2         | 0.97%   |
| 0x406c3    | 2         | 0.97%   |
| 0x106c2    | 2         | 0.97%   |
| 0x08608103 | 2         | 0.97%   |
| 0x08600106 | 2         | 0.97%   |
| 0xa0652    | 1         | 0.48%   |
| 0x906ec    | 1         | 0.48%   |
| 0x806c2    | 1         | 0.48%   |
| 0x6fa      | 1         | 0.48%   |
| 0x6f6      | 1         | 0.48%   |
| 0x6f2      | 1         | 0.48%   |
| 0x506e3    | 1         | 0.48%   |
| 0x506c9    | 1         | 0.48%   |
| 0x30673    | 1         | 0.48%   |
| 0x0a50000d | 1         | 0.48%   |
| 0x08600103 | 1         | 0.48%   |
| 0x08108109 | 1         | 0.48%   |
| 0x0600611a | 1         | 0.48%   |
| 0x05000119 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 36        | 18.18%  |
| Haswell       | 31        | 15.66%  |
| Skylake       | 19        | 9.6%    |
| SandyBridge   | 19        | 9.6%    |
| IvyBridge     | 19        | 9.6%    |
| Silvermont    | 14        | 7.07%   |
| Broadwell     | 10        | 5.05%   |
| Westmere      | 8         | 4.04%   |
| TigerLake     | 7         | 3.54%   |
| IceLake       | 7         | 3.54%   |
| Core          | 5         | 2.53%   |
| Goldmont plus | 4         | 2.02%   |
| Zen 2         | 3         | 1.52%   |
| Penryn        | 3         | 1.52%   |
| Goldmont      | 2         | 1.01%   |
| Excavator     | 2         | 1.01%   |
| Bonnell       | 2         | 1.01%   |
| Unknown       | 2         | 1.01%   |
| Zen+          | 1         | 0.51%   |
| Zen 3         | 1         | 0.51%   |
| Steamroller   | 1         | 0.51%   |
| CometLake     | 1         | 0.51%   |
| Bobcat        | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 175       | 78.13%  |
| Nvidia | 25        | 11.16%  |
| AMD    | 24        | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 8.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 8.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 7.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 6.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.8%    |
| Intel HD Graphics 5500                                                                   | 10        | 4.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 4.37%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.06%   |
| Intel HD Graphics 620                                                                    | 7         | 3.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.06%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 2.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.75%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.31%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.31%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.87%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.87%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.87%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.87%   |
| Intel HD Graphics 500                                                                    | 2         | 0.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.87%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.87%   |
| AMD Renoir                                                                               | 2         | 0.87%   |
| AMD Lucienne                                                                             | 2         | 0.87%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.44%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.44%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.44%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.44%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.44%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 150       | 75.76%  |
| Intel + Nvidia | 16        | 8.08%   |
| 1 x AMD        | 14        | 7.07%   |
| Intel + AMD    | 9         | 4.55%   |
| 1 x Nvidia     | 8         | 4.04%   |
| 2 x AMD        | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 188       | 94%     |
| Proprietary | 11        | 5.5%    |
| Unknown     | 1         | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 80.1%   |
| 1.01-2.0   | 14        | 6.97%   |
| 0.01-0.5   | 13        | 6.47%   |
| 3.01-4.0   | 5         | 2.49%   |
| 7.01-8.0   | 4         | 1.99%   |
| 0.51-1.0   | 3         | 1.49%   |
| 5.01-6.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 54        | 26.09%  |
| Chimei Innolux          | 36        | 17.39%  |
| BOE                     | 29        | 14.01%  |
| LG Display              | 28        | 13.53%  |
| Samsung Electronics     | 20        | 9.66%   |
| Hewlett-Packard         | 8         | 3.86%   |
| Sharp                   | 5         | 2.42%   |
| Apple                   | 4         | 1.93%   |
| InfoVision              | 3         | 1.45%   |
| Chi Mei Optoelectronics | 3         | 1.45%   |
| LG Philips              | 2         | 0.97%   |
| Lenovo                  | 2         | 0.97%   |
| KDC                     | 2         | 0.97%   |
| HannStar                | 2         | 0.97%   |
| CSO                     | 2         | 0.97%   |
| Unknown (XXX)           | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| Planar                  | 1         | 0.48%   |
| Eizo                    | 1         | 0.48%   |
| Dell                    | 1         | 0.48%   |
| CVT                     | 1         | 0.48%   |
| Acer                    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.93%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 4         | 1.93%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 4         | 1.93%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 1.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 1.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.45%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 1.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.97%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.97%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.97%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.97%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.97%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.97%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.97%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.48%   |
| Sony TV SNY6F02 1360x768                                                 | 1         | 0.48%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.48%   |
| Samsung Electronics S27E650 SAM0CCA 1920x1080 598x336mm 27.0-inch        | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 97        | 48.26%  |
| 1920x1080 (FHD)    | 59        | 29.35%  |
| 1600x900 (HD+)     | 17        | 8.46%   |
| 1280x800 (WXGA)    | 5         | 2.49%   |
| 3840x2160 (4K)     | 4         | 1.99%   |
| 1920x1200 (WUXGA)  | 3         | 1.49%   |
| 1440x900 (WXGA+)   | 3         | 1.49%   |
| 1360x768           | 2         | 1%      |
| 1024x600           | 2         | 1%      |
| 3840x2400          | 1         | 0.5%    |
| 3200x1800 (QHD+)   | 1         | 0.5%    |
| 3072x1920          | 1         | 0.5%    |
| 2560x1440 (QHD)    | 1         | 0.5%    |
| 2560x1080          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1280x1024 (SXGA)   | 1         | 0.5%    |
| Unknown            | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 74        | 35.92%  |
| 14      | 46        | 22.33%  |
| 13      | 44        | 21.36%  |
| 12      | 7         | 3.4%    |
| 11      | 7         | 3.4%    |
| 17      | 5         | 2.43%   |
| 10      | 3         | 1.46%   |
| 27      | 2         | 0.97%   |
| 24      | 2         | 0.97%   |
| 23      | 2         | 0.97%   |
| 20      | 2         | 0.97%   |
| 18      | 2         | 0.97%   |
| 84      | 1         | 0.49%   |
| 72      | 1         | 0.49%   |
| 46      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 21      | 1         | 0.49%   |
| 19      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 147       | 71.36%  |
| 201-300     | 33        | 16.02%  |
| 351-400     | 8         | 3.88%   |
| 501-600     | 7         | 3.4%    |
| 401-500     | 5         | 2.43%   |
| 1501-2000   | 2         | 0.97%   |
| 801-900     | 1         | 0.49%   |
| 601-700     | 1         | 0.49%   |
| 901-1000    | 1         | 0.49%   |
| Unknown     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 89.23%  |
| 16/10   | 17        | 8.72%   |
| 5/4     | 1         | 0.51%   |
| 3/2     | 1         | 0.51%   |
| 21/9    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 74        | 35.92%  |
| 101-110        | 73        | 35.44%  |
| 71-80          | 16        | 7.77%   |
| 61-70          | 7         | 3.4%    |
| 51-60          | 7         | 3.4%    |
| 201-250        | 5         | 2.43%   |
| 41-50          | 3         | 1.46%   |
| 151-200        | 3         | 1.46%   |
| 141-150        | 3         | 1.46%   |
| 121-130        | 3         | 1.46%   |
| More than 1000 | 2         | 0.97%   |
| 351-500        | 2         | 0.97%   |
| 301-350        | 2         | 0.97%   |
| 251-300        | 1         | 0.49%   |
| 131-140        | 1         | 0.49%   |
| 111-120        | 1         | 0.49%   |
| 501-1000       | 1         | 0.49%   |
| 91-100         | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 81        | 39.32%  |
| 121-160       | 79        | 38.35%  |
| 51-100        | 27        | 13.11%  |
| 161-240       | 10        | 4.85%   |
| More than 240 | 5         | 2.43%   |
| 1-50          | 3         | 1.46%   |
| Unknown       | 1         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 175       | 86.21%  |
| 2     | 23        | 11.33%  |
| 0     | 4         | 1.97%   |
| 3     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 118       | 39.46%  |
| Realtek Semiconductor             | 82        | 27.42%  |
| Qualcomm Atheros                  | 43        | 14.38%  |
| Broadcom                          | 18        | 6.02%   |
| Hewlett-Packard                   | 6         | 2.01%   |
| Samsung Electronics               | 4         | 1.34%   |
| ZTE WCDMA Technologies MSM        | 3         | 1%      |
| Sierra Wireless                   | 3         | 1%      |
| Ralink                            | 3         | 1%      |
| MediaTek                          | 3         | 1%      |
| Marvell Technology Group          | 3         | 1%      |
| Huawei Technologies               | 3         | 1%      |
| T & A Mobile Phones               | 2         | 0.67%   |
| Ralink Technology                 | 2         | 0.67%   |
| Ericsson Business Mobile Networks | 2         | 0.67%   |
| Broadcom Limited                  | 2         | 0.67%   |
| Spreadtrum Communications         | 1         | 0.33%   |
| OPPO Electronics                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 11.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 5.71%   |
| Intel Wireless 7260                                               | 20        | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 4.94%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 4.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 3.38%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.86%   |
| Intel Wireless 8260                                               | 10        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.34%   |
| Intel Wireless 7265                                               | 8         | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.3%    |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.04%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 3         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.78%   |
| HP lt4112 Gobi 4G Module Network Device                           | 3         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 3         | 0.78%   |
| T & A Mobile Phones Alcatel 1                                     | 2         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 105       | 52.24%  |
| Qualcomm Atheros                  | 38        | 18.91%  |
| Realtek Semiconductor             | 28        | 13.93%  |
| Broadcom                          | 16        | 7.96%   |
| Hewlett-Packard                   | 4         | 1.99%   |
| Sierra Wireless                   | 3         | 1.49%   |
| Ralink                            | 3         | 1.49%   |
| Ralink Technology                 | 2         | 1%      |
| Ericsson Business Mobile Networks | 1         | 0.5%    |
| Broadcom Limited                  | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 20        | 9.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 6.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 5.47%   |
| Intel Wireless 8260                                            | 10        | 4.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.48%   |
| Intel Wireless 7265                                            | 8         | 3.98%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 3.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.99%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.49%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 2.49%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 2.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.49%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1%      |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1%      |
| Ralink MT7601U Wireless Adapter                                | 2         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1%      |
| Intel Wireless 3160                                            | 2         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1%      |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1%      |
| Intel Centrino Advanced-N 6235                                 | 2         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1%      |
| Sierra Wireless EM7455                                         | 1         | 0.5%    |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.5%    |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 76        | 42.7%   |
| Realtek Semiconductor      | 72        | 40.45%  |
| Qualcomm Atheros           | 8         | 4.49%   |
| ZTE WCDMA Technologies MSM | 3         | 1.69%   |
| MediaTek                   | 3         | 1.69%   |
| Marvell Technology Group   | 3         | 1.69%   |
| Broadcom                   | 3         | 1.69%   |
| T & A Mobile Phones        | 2         | 1.12%   |
| Huawei Technologies        | 2         | 1.12%   |
| Hewlett-Packard            | 2         | 1.12%   |
| Spreadtrum Communications  | 1         | 0.56%   |
| Samsung Electronics        | 1         | 0.56%   |
| OPPO Electronics           | 1         | 0.56%   |
| Broadcom Limited           | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 25.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 12.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 10.61%  |
| Intel Ethernet Connection I218-LM                                 | 16        | 8.94%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 6.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.79%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.79%   |
| Intel Ethernet Connection I217-V                                  | 4         | 2.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.23%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 2.23%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 3         | 1.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.68%   |
| T & A Mobile Phones Alcatel 1                                     | 2         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.12%   |
| MediaTek Titan pocket                                             | 2         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.12%   |
| Huawei E353/E3131                                                 | 2         | 1.12%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 1.12%   |
| Spreadtrum Spreadtrum Phone                                       | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 0.56%   |
| MediaTek 100026191                                                | 1         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.56%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 52.78%  |
| Ethernet | 165       | 45.83%  |
| Modem    | 5         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 81.86%  |
| Ethernet | 37        | 18.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 76.38%  |
| 1     | 37        | 18.59%  |
| 0     | 8         | 4.02%   |
| 3     | 2         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 194       | 97.98%  |
| Yes  | 4         | 2.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 53.29%  |
| Qualcomm Atheros Communications | 23        | 15.13%  |
| Realtek Semiconductor           | 14        | 9.21%   |
| Broadcom                        | 11        | 7.24%   |
| IMC Networks                    | 4         | 2.63%   |
| Hewlett-Packard                 | 4         | 2.63%   |
| Lite-On Technology              | 3         | 1.97%   |
| Toshiba                         | 2         | 1.32%   |
| Ralink                          | 2         | 1.32%   |
| Dell                            | 2         | 1.32%   |
| Apple                           | 2         | 1.32%   |
| Taiyo Yuden                     | 1         | 0.66%   |
| Realtek                         | 1         | 0.66%   |
| Foxconn / Hon Hai               | 1         | 0.66%   |
| Alps Electric                   | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 47        | 30.92%  |
| Qualcomm Atheros  Bluetooth Device               | 12        | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 11        | 7.24%   |
| Realtek Bluetooth Radio                          | 10        | 6.58%   |
| Intel AX201 Bluetooth                            | 9         | 5.92%   |
| Intel AX200 Bluetooth                            | 5         | 3.29%   |
| Broadcom HP Portable SoftSailing                 | 5         | 3.29%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 4         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 1.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 3         | 1.97%   |
| Qualcomm Atheros AR3011 Bluetooth                | 3         | 1.97%   |
| IMC Networks Bluetooth Device                    | 3         | 1.97%   |
| HP Broadcom 2070 Bluetooth Combo                 | 3         | 1.97%   |
| Ralink RT3290 Bluetooth                          | 2         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                 | 2         | 1.32%   |
| Dell DW375 Bluetooth Module                      | 2         | 1.32%   |
| Broadcom HP Portable Bumble Bee                  | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 1.32%   |
| Toshiba RT Bluetooth Radio                       | 1         | 0.66%   |
| Toshiba Atheros AR3012 Bluetooth                 | 1         | 0.66%   |
| Taiyo Yuden Bluetooth Device                     | 1         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 1         | 0.66%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 0.66%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.66%   |
| Lite-On Bluetooth Device                         | 1         | 0.66%   |
| Lite-On Atheros Bluetooth                        | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.66%   |
| Intel AX210 Bluetooth                            | 1         | 0.66%   |
| IMC Networks Bluetooth                           | 1         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 0.66%   |
| Broadcom BCM2070 Bluetooth Device                | 1         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                      | 1         | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 0.66%   |
| Apple Bluetooth HCI                              | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 180       | 84.11%  |
| AMD                         | 15        | 7.01%   |
| Nvidia                      | 11        | 5.14%   |
| Generalplus Technology      | 2         | 0.93%   |
| Turtle Beach                | 1         | 0.47%   |
| Texas Instruments           | 1         | 0.47%   |
| Realtek Semiconductor       | 1         | 0.47%   |
| GN Netcom                   | 1         | 0.47%   |
| FiiO Electronics Technology | 1         | 0.47%   |
| Apple                       | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 35        | 13.31%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 7.6%    |
| Intel 8 Series HD Audio Controller                                                                | 19        | 7.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 7.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 7.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 4.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.8%    |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 2.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.76%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.76%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.76%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.38%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.38%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.38%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.38%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 33.57%  |
| SK hynix            | 35        | 24.48%  |
| Micron Technology   | 16        | 11.19%  |
| Kingston            | 10        | 6.99%   |
| Unknown             | 9         | 6.29%   |
| Elpida              | 6         | 4.2%    |
| Ramaxel Technology  | 5         | 3.5%    |
| Crucial             | 4         | 2.8%    |
| A-DATA Technology   | 3         | 2.1%    |
| Timetec             | 1         | 0.7%    |
| Qimonda             | 1         | 0.7%    |
| Patriot             | 1         | 0.7%    |
| Nanya Technology    | 1         | 0.7%    |
| Avant               | 1         | 0.7%    |
| Apacer              | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 4.76%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 6         | 4.08%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 2.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 2.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 2.04%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 2.04%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 2.04%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 1.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.36%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.36%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 1.36%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 1.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s             | 2         | 1.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 1.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 1.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 1.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.36%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 1.36%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.68%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.68%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.68%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 55        | 50.93%  |
| DDR4   | 40        | 37.04%  |
| DDR2   | 5         | 4.63%   |
| LPDDR4 | 3         | 2.78%   |
| LPDDR3 | 3         | 2.78%   |
| SDRAM  | 1         | 0.93%   |
| DDR    | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 86.09%  |
| Row Of Chips | 13        | 11.3%   |
| Chip         | 3         | 2.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 40.32%  |
| 8192  | 35        | 28.23%  |
| 2048  | 18        | 14.52%  |
| 16384 | 14        | 11.29%  |
| 1024  | 5         | 4.03%   |
| 32768 | 2         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 44        | 36.07%  |
| 2667    | 24        | 19.67%  |
| 3200    | 12        | 9.84%   |
| 1334    | 8         | 6.56%   |
| 2133    | 7         | 5.74%   |
| 1333    | 7         | 5.74%   |
| 2400    | 4         | 3.28%   |
| 4267    | 3         | 2.46%   |
| 667     | 3         | 2.46%   |
| 3266    | 2         | 1.64%   |
| 1867    | 2         | 1.64%   |
| 800     | 2         | 1.64%   |
| 8400    | 1         | 0.82%   |
| 4199    | 1         | 0.82%   |
| 1067    | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

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
| Chicony Electronics                    | 58        | 31.52%  |
| Cheng Uei Precision Industry (Foxlink) | 24        | 13.04%  |
| Syntek                                 | 10        | 5.43%   |
| Sunplus Innovation Technology          | 10        | 5.43%   |
| Microdia                               | 10        | 5.43%   |
| Lite-On Technology                     | 9         | 4.89%   |
| Bison Electronics                      | 9         | 4.89%   |
| Realtek Semiconductor                  | 8         | 4.35%   |
| Acer                                   | 8         | 4.35%   |
| IMC Networks                           | 7         | 3.8%    |
| Apple                                  | 4         | 2.17%   |
| Silicon Motion                         | 3         | 1.63%   |
| Samsung Electronics                    | 3         | 1.63%   |
| Quanta                                 | 3         | 1.63%   |
| Suyin                                  | 2         | 1.09%   |
| Ricoh                                  | 2         | 1.09%   |
| Luxvisions Innotech Limited            | 2         | 1.09%   |
| Logitech                               | 2         | 1.09%   |
| Importek                               | 2         | 1.09%   |
| Alcor Micro                            | 2         | 1.09%   |
| Unknown                                | 1         | 0.54%   |
| Primax Electronics                     | 1         | 0.54%   |
| LG Electronics                         | 1         | 0.54%   |
| icSpring                               | 1         | 0.54%   |
| DigiTech                               | 1         | 0.54%   |
| ALi                                    | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 12        | 6.49%   |
| Chicony HP HD Webcam                                                       | 8         | 4.32%   |
| Syntek Integrated Camera                                                   | 6         | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 6         | 3.24%   |
| Chicony USB 2.0 Camera                                                     | 5         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 5         | 2.7%    |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.16%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.16%   |
| Lite-On HP HD Webcam                                                       | 4         | 2.16%   |
| Lite-On HP HD Camera                                                       | 4         | 2.16%   |
| Chicony HP HD Webcam [Fixed]                                               | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 2.16%   |
| Acer Integrated Camera                                                     | 4         | 2.16%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.62%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.62%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.62%   |
| Chicony HP HD Camera                                                       | 3         | 1.62%   |
| Chicony HD Webcam                                                          | 3         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 3         | 1.62%   |
| Bison Integrated Camera                                                    | 3         | 1.62%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 1.08%   |
| Syntek EasyCamera                                                          | 2         | 1.08%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 1.08%   |
| Realtek Integrated Webcam                                                  | 2         | 1.08%   |
| Importek HP Webcam-50                                                      | 2         | 1.08%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.08%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 1.08%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.08%   |
| Chicony HP Webcam                                                          | 2         | 1.08%   |
| Chicony HP Truevision HD camera                                            | 2         | 1.08%   |
| Chicony HP Truevision HD                                                   | 2         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 2         | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 1.08%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.08%   |
| Unknown USB Camera                                                         | 1         | 0.54%   |
| Suyin HP Webcam                                                            | 1         | 0.54%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.54%   |
| Sunplus UNIQUESKY_CAR_CAMERA                                               | 1         | 0.54%   |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 66.15%  |
| Synaptics                  | 12        | 18.46%  |
| Shenzhen Goodix Technology | 6         | 9.23%   |
| AuthenTec                  | 2         | 3.08%   |
| LighTuning Technology      | 1         | 1.54%   |
| Elan Microelectronics      | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 26.15%  |
| Validity Sensors VFS491                                                    | 8         | 12.31%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.15%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 6.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.62%   |
| Synaptics WBDI Device                                                      | 3         | 4.62%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 3.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.08%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 3.08%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.54%   |
| Synaptics  WBDI                                                            | 1         | 1.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.54%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.54%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| Upek        | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 116       | 57.71%  |
| 1     | 68        | 33.83%  |
| 2     | 15        | 7.46%   |
| 3     | 2         | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 64        | 62.14%  |
| Graphics card            | 11        | 10.68%  |
| Chipcard                 | 9         | 8.74%   |
| Net/wireless             | 5         | 4.85%   |
| Camera                   | 4         | 3.88%   |
| Storage                  | 3         | 2.91%   |
| Net/ethernet             | 2         | 1.94%   |
| Communication controller | 2         | 1.94%   |
| Bluetooth                | 2         | 1.94%   |
| Sound                    | 1         | 0.97%   |


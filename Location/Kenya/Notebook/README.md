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

Total: 388

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 830 G8 Noteboo... | [dd7ea1bfca](https://linux-hardware.org/?probe=dd7ea1bfca) | Jan 03, 2025 |
| Acer          | Predator PT516-51s          | [ba15b5dd07](https://linux-hardware.org/?probe=ba15b5dd07) | Dec 27, 2024 |
| HP            | EliteBook 820 G3            | [4804abe046](https://linux-hardware.org/?probe=4804abe046) | Dec 26, 2024 |
| HP            | EliteBook 820 G3            | [cf6ba1ead2](https://linux-hardware.org/?probe=cf6ba1ead2) | Dec 25, 2024 |
| Dell          | Latitude 7420               | [754cef3d2f](https://linux-hardware.org/?probe=754cef3d2f) | Dec 20, 2024 |
| HP            | EliteBook Folio 9480m       | [7d0e5bbe48](https://linux-hardware.org/?probe=7d0e5bbe48) | Dec 14, 2024 |
| HP            | EliteBook 735 G5            | [747ae84f9e](https://linux-hardware.org/?probe=747ae84f9e) | Dec 12, 2024 |
| HP            | ProBook 430 G2              | [7d778aaa23](https://linux-hardware.org/?probe=7d778aaa23) | Dec 04, 2024 |
| HP            | EliteBook 840 G1            | [cf93e45cdf](https://linux-hardware.org/?probe=cf93e45cdf) | Dec 02, 2024 |
| HP            | EliteBook 840 G1            | [c791f3500c](https://linux-hardware.org/?probe=c791f3500c) | Dec 02, 2024 |
| HP            | ProBook 6560b               | [a7224d17ca](https://linux-hardware.org/?probe=a7224d17ca) | Dec 01, 2024 |
| Jemper        | EZPAD WS_reserve            | [120200526f](https://linux-hardware.org/?probe=120200526f) | Nov 23, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | [71d4704433](https://linux-hardware.org/?probe=71d4704433) | Nov 18, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | [102430b4e4](https://linux-hardware.org/?probe=102430b4e4) | Nov 18, 2024 |
| HP            | EliteBook 830 G8 Noteboo... | [6c93a82662](https://linux-hardware.org/?probe=6c93a82662) | Nov 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [f4d3b8c11f](https://linux-hardware.org/?probe=f4d3b8c11f) | Nov 06, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [386606f6bd](https://linux-hardware.org/?probe=386606f6bd) | Nov 04, 2024 |
| TECNO         | WinPad 2                    | [1cb685a8f9](https://linux-hardware.org/?probe=1cb685a8f9) | Oct 19, 2024 |
| HP            | EliteBook Folio 9480m       | [738c69c20e](https://linux-hardware.org/?probe=738c69c20e) | Oct 10, 2024 |
| HP            | EliteBook 840 G1            | [ce808338c2](https://linux-hardware.org/?probe=ce808338c2) | Oct 03, 2024 |
| HP            | EliteBook Folio 9480m       | [55eb1cb193](https://linux-hardware.org/?probe=55eb1cb193) | Sep 28, 2024 |
| SLIMBOOK      | Executive                   | [bf66c459b2](https://linux-hardware.org/?probe=bf66c459b2) | Sep 27, 2024 |
| HP            | EliteBook Folio 9480m       | [915bab9e91](https://linux-hardware.org/?probe=915bab9e91) | Sep 27, 2024 |
| HP            | EliteBook 8460p             | [d28a7d92f7](https://linux-hardware.org/?probe=d28a7d92f7) | Sep 08, 2024 |
| HP            | EliteBook 8460p             | [375da72314](https://linux-hardware.org/?probe=375da72314) | Sep 08, 2024 |
| HP            | EliteBook 840 G5            | [9a594bf56d](https://linux-hardware.org/?probe=9a594bf56d) | Sep 06, 2024 |
| HP            | EliteBook 850 G5            | [a8047158de](https://linux-hardware.org/?probe=a8047158de) | Aug 31, 2024 |
| HP            | ProBook 6470b               | [0f3e431d44](https://linux-hardware.org/?probe=0f3e431d44) | Aug 27, 2024 |
| Dell          | Latitude D430               | [4346500f96](https://linux-hardware.org/?probe=4346500f96) | Aug 16, 2024 |
| HP            | EliteBook 840 G1            | [9d398bbfc9](https://linux-hardware.org/?probe=9d398bbfc9) | Aug 13, 2024 |
| Lenovo        | B51-30 80LK                 | [e4f72a3222](https://linux-hardware.org/?probe=e4f72a3222) | Aug 08, 2024 |
| Lenovo        | B51-30 80LK                 | [8003cbb98e](https://linux-hardware.org/?probe=8003cbb98e) | Aug 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [4f54877e82](https://linux-hardware.org/?probe=4f54877e82) | Aug 06, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [d9b8f3df7b](https://linux-hardware.org/?probe=d9b8f3df7b) | Aug 02, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [d243d082ff](https://linux-hardware.org/?probe=d243d082ff) | Jul 13, 2024 |
| Toshiba       | TECRA X40-E                 | [f8de6267c6](https://linux-hardware.org/?probe=f8de6267c6) | Jul 12, 2024 |
| Dell          | Latitude E7450              | [13e9eb3e22](https://linux-hardware.org/?probe=13e9eb3e22) | Jul 05, 2024 |
| HP            | Laptop 15-da1xxx            | [99828b86d7](https://linux-hardware.org/?probe=99828b86d7) | Jun 28, 2024 |
| HP            | EliteBook 820 G3            | [7ab8af1195](https://linux-hardware.org/?probe=7ab8af1195) | Jun 21, 2024 |
| HP            | EliteBook 820 G3            | [ae95ca44f4](https://linux-hardware.org/?probe=ae95ca44f4) | Jun 21, 2024 |
| HP            | 630                         | [8b8b94da0e](https://linux-hardware.org/?probe=8b8b94da0e) | Jun 18, 2024 |
| HP            | ProBook 650 G2              | [9ffce6984c](https://linux-hardware.org/?probe=9ffce6984c) | Jun 07, 2024 |
| HP            | ProBook 450 G6              | [f655bfbf19](https://linux-hardware.org/?probe=f655bfbf19) | May 31, 2024 |
| HP            | ProBook 450 G6              | [9f1460dd7f](https://linux-hardware.org/?probe=9f1460dd7f) | May 19, 2024 |
| Toshiba       | TECRA X40-E                 | [e5f6efb109](https://linux-hardware.org/?probe=e5f6efb109) | May 14, 2024 |
| Lenovo        | ThinkPad P72 20MCS1A400     | [2fb5a9e91b](https://linux-hardware.org/?probe=2fb5a9e91b) | May 02, 2024 |
| Lenovo        | ThinkPad P72 20MCS1A400     | [11cfebd1f9](https://linux-hardware.org/?probe=11cfebd1f9) | May 02, 2024 |
| HP            | EliteBook 840 G1            | [9ad3b0be60](https://linux-hardware.org/?probe=9ad3b0be60) | Apr 24, 2024 |
| Dell          | Inspiron 3542               | [290ea848f0](https://linux-hardware.org/?probe=290ea848f0) | Apr 19, 2024 |
| HP            | ZBook 15 G6                 | [e8ad21a64f](https://linux-hardware.org/?probe=e8ad21a64f) | Apr 11, 2024 |
| HP            | EliteBook 2760p             | [438956801b](https://linux-hardware.org/?probe=438956801b) | Apr 09, 2024 |
| HP            | EliteBook 2760p             | [9ab7018eab](https://linux-hardware.org/?probe=9ab7018eab) | Apr 04, 2024 |
| HP            | EliteBook 830 G5            | [7ac30f9e22](https://linux-hardware.org/?probe=7ac30f9e22) | Mar 18, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [29aa21542a](https://linux-hardware.org/?probe=29aa21542a) | Feb 22, 2024 |
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
| Ubuntu 22.04                 | 33        | 11.34%  |
| Ubuntu 20.04                 | 33        | 11.34%  |
| Ubuntu 18.04                 | 15        | 5.15%   |
| Arch Rolling                 | 10        | 3.44%   |
| Zorin 16                     | 7         | 2.41%   |
| Ubuntu 24.04                 | 7         | 2.41%   |
| Linux Mint 20.3              | 6         | 2.06%   |
| Fedora 40                    | 6         | 2.06%   |
| Fedora 36                    | 6         | 2.06%   |
| Ubuntu 23.04                 | 5         | 1.72%   |
| Manjaro                      | 5         | 1.72%   |
| Fedora 38                    | 5         | 1.72%   |
| Zorin 17                     | 4         | 1.37%   |
| Zorin 15                     | 4         | 1.37%   |
| Ubuntu 20.10                 | 4         | 1.37%   |
| Ubuntu 19.04                 | 4         | 1.37%   |
| Pop!_OS 20.04                | 4         | 1.37%   |
| OpenMandriva 4.2             | 4         | 1.37%   |
| Debian 12                    | 4         | 1.37%   |
| Arch                         | 4         | 1.37%   |
| Ubuntu 21.04                 | 3         | 1.03%   |
| Q4OS 3                       | 3         | 1.03%   |
| Pop!_OS 22.04                | 3         | 1.03%   |
| Linux Mint 20.2              | 3         | 1.03%   |
| Kali 2023.3                  | 3         | 1.03%   |
| Fedora 37                    | 3         | 1.03%   |
| Debian 11                    | 3         | 1.03%   |
| Ubuntu 23.10                 | 2         | 0.69%   |
| Ubuntu 21.10                 | 2         | 0.69%   |
| Ubuntu 19.10                 | 2         | 0.69%   |
| Parrot 5.3                   | 2         | 0.69%   |
| Parrot 5.1                   | 2         | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.69%   |
| Linux Mint 21.2              | 2         | 0.69%   |
| Linux Mint 19                | 2         | 0.69%   |
| Kali 2024.2                  | 2         | 0.69%   |
| Kali 2023.2                  | 2         | 0.69%   |
| Kali 2022.3                  | 2         | 0.69%   |
| Fedora 35                    | 2         | 0.69%   |
| Fedora 32                    | 2         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 105       | 38.6%   |
| Fedora        | 25        | 9.19%   |
| Zorin         | 15        | 5.51%   |
| Linux Mint    | 15        | 5.51%   |
| Arch          | 14        | 5.15%   |
| Kali          | 13        | 4.78%   |
| Manjaro       | 10        | 3.68%   |
| Endless       | 10        | 3.68%   |
| Pop!_OS       | 9         | 3.31%   |
| Parrot        | 9         | 3.31%   |
| Debian        | 8         | 2.94%   |
| OpenMandriva  | 6         | 2.21%   |
| Q4OS          | 3         | 1.1%    |
| Ubuntu MATE   | 2         | 0.74%   |
| Ubuntu Budgie | 2         | 0.74%   |
| ROSA          | 2         | 0.74%   |
| RHEL          | 2         | 0.74%   |
| openSUSE      | 2         | 0.74%   |
| Elementary    | 2         | 0.74%   |
| blendOS       | 2         | 0.74%   |
| ArcoLinux     | 2         | 0.74%   |
| Xubuntu       | 1         | 0.37%   |
| Rocky Linux   | 1         | 0.37%   |
| Nobara        | 1         | 0.37%   |
| MX            | 1         | 0.37%   |
| Lubuntu       | 1         | 0.37%   |
| LMDE          | 1         | 0.37%   |
| Lilidog       | 1         | 0.37%   |
| KDE neon      | 1         | 0.37%   |
| Garuda Linux  | 1         | 0.37%   |
| EndeavourOS   | 1         | 0.37%   |
| Deepin        | 1         | 0.37%   |
| BlackPanther  | 1         | 0.37%   |
| antiX         | 1         | 0.37%   |
| Alpine        | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 1.93%   |
| 6.8.0-45-generic         | 4         | 1.29%   |
| 5.15.0-58-generic        | 4         | 1.29%   |
| 5.15.0-52-generic        | 4         | 1.29%   |
| 5.11.0-38-generic        | 4         | 1.29%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.29%   |
| 6.3.0-kali1-amd64        | 3         | 0.96%   |
| 5.4.0-58-generic         | 3         | 0.96%   |
| 5.4.0-52-generic         | 3         | 0.96%   |
| 5.4.0-45-generic         | 3         | 0.96%   |
| 5.4.0-42-generic         | 3         | 0.96%   |
| 5.19.0-38-generic        | 3         | 0.96%   |
| 5.15.0-53-generic        | 3         | 0.96%   |
| 5.15.0-41-generic        | 3         | 0.96%   |
| 6.8.9-arch1-2            | 2         | 0.64%   |
| 6.8.0-49-generic         | 2         | 0.64%   |
| 6.6.9-amd64              | 2         | 0.64%   |
| 6.5.0-41-generic         | 2         | 0.64%   |
| 6.5.0-27-generic         | 2         | 0.64%   |
| 6.5.0-10-generic         | 2         | 0.64%   |
| 6.2.0-32-generic         | 2         | 0.64%   |
| 6.1.0-kali7-amd64        | 2         | 0.64%   |
| 6.1.0-21-686-pae         | 2         | 0.64%   |
| 5.8.0-59-generic         | 2         | 0.64%   |
| 5.8.0-43-generic         | 2         | 0.64%   |
| 5.4.0-67-generic         | 2         | 0.64%   |
| 5.4.0-65-generic         | 2         | 0.64%   |
| 5.4.0-54-generic         | 2         | 0.64%   |
| 5.4.0-48-generic         | 2         | 0.64%   |
| 5.4.0-47-generic         | 2         | 0.64%   |
| 5.4.0-37-generic         | 2         | 0.64%   |
| 5.4.0-137-generic        | 2         | 0.64%   |
| 5.3.0-28-generic         | 2         | 0.64%   |
| 5.19.0-41-generic        | 2         | 0.64%   |
| 5.19.0-35-generic        | 2         | 0.64%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.64%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.64%   |
| 5.15.0-46-generic        | 2         | 0.64%   |
| 5.13.19-2-MANJARO        | 2         | 0.64%   |
| 5.13.0-27-generic        | 2         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 13.18%  |
| 5.15.0  | 24        | 8.11%   |
| 5.8.0   | 18        | 6.08%   |
| 5.11.0  | 15        | 5.07%   |
| 6.8.0   | 14        | 4.73%   |
| 6.5.0   | 12        | 4.05%   |
| 4.15.0  | 11        | 3.72%   |
| 6.1.0   | 10        | 3.38%   |
| 6.2.0   | 8         | 2.7%    |
| 5.19.0  | 8         | 2.7%    |
| 5.3.0   | 7         | 2.36%   |
| 5.13.0  | 7         | 2.36%   |
| 5.0.0   | 7         | 2.36%   |
| 5.10.0  | 5         | 1.69%   |
| 5.18.0  | 4         | 1.35%   |
| 5.10.14 | 4         | 1.35%   |
| 4.19.0  | 4         | 1.35%   |
| 6.3.0   | 3         | 1.01%   |
| 5.14.0  | 3         | 1.01%   |
| 4.18.0  | 3         | 1.01%   |
| 6.8.9   | 2         | 0.68%   |
| 6.8.11  | 2         | 0.68%   |
| 6.6.9   | 2         | 0.68%   |
| 6.4.8   | 2         | 0.68%   |
| 6.3.4   | 2         | 0.68%   |
| 6.1.52  | 2         | 0.68%   |
| 5.19.9  | 2         | 0.68%   |
| 5.18.13 | 2         | 0.68%   |
| 5.17.5  | 2         | 0.68%   |
| 5.16.7  | 2         | 0.68%   |
| 5.13.19 | 2         | 0.68%   |
| 6.9.8   | 1         | 0.34%   |
| 6.9.2   | 1         | 0.34%   |
| 6.8.5   | 1         | 0.34%   |
| 6.8.2   | 1         | 0.34%   |
| 6.6.15  | 1         | 0.34%   |
| 6.6.13  | 1         | 0.34%   |
| 6.5.7   | 1         | 0.34%   |
| 6.5.6   | 1         | 0.34%   |
| 6.4.14  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 13.27%  |
| 5.15    | 26        | 8.84%   |
| 6.8     | 20        | 6.8%    |
| 5.8     | 20        | 6.8%    |
| 6.1     | 16        | 5.44%   |
| 5.11    | 16        | 5.44%   |
| 6.5     | 14        | 4.76%   |
| 5.19    | 13        | 4.42%   |
| 6.2     | 12        | 4.08%   |
| 5.10    | 12        | 4.08%   |
| 4.15    | 11        | 3.74%   |
| 5.13    | 9         | 3.06%   |
| 5.0     | 8         | 2.72%   |
| 6.3     | 7         | 2.38%   |
| 5.3     | 7         | 2.38%   |
| 5.18    | 6         | 2.04%   |
| 5.14    | 6         | 2.04%   |
| 6.11    | 5         | 1.7%    |
| 4.19    | 5         | 1.7%    |
| 6.6     | 4         | 1.36%   |
| 6.4     | 4         | 1.36%   |
| 6.10    | 4         | 1.36%   |
| 5.16    | 4         | 1.36%   |
| 4.18    | 4         | 1.36%   |
| 5.6     | 3         | 1.02%   |
| 5.17    | 3         | 1.02%   |
| 6.9     | 2         | 0.68%   |
| 6.0     | 2         | 0.68%   |
| 5.9     | 2         | 0.68%   |
| 5.2     | 2         | 0.68%   |
| 4.9     | 2         | 0.68%   |
| 6.12    | 1         | 0.34%   |
| 5.7     | 1         | 0.34%   |
| 5.5     | 1         | 0.34%   |
| 5.1     | 1         | 0.34%   |
| 4.16    | 1         | 0.34%   |
| 4.13    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 257       | 97.72%  |
| i686   | 6         | 2.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 166       | 60.81%  |
| Unknown         | 26        | 9.52%   |
| KDE5            | 25        | 9.16%   |
| XFCE            | 15        | 5.49%   |
| X-Cinnamon      | 13        | 4.76%   |
| MATE            | 11        | 4.03%   |
| KDE             | 4         | 1.47%   |
| Pantheon        | 2         | 0.73%   |
| KDE4            | 2         | 0.73%   |
| openbox         | 1         | 0.37%   |
| LXQt            | 1         | 0.37%   |
| KDE6            | 1         | 0.37%   |
| GNOME Flashback | 1         | 0.37%   |
| Endless:GNOME   | 1         | 0.37%   |
| Deepin          | 1         | 0.37%   |
| Cinnamon        | 1         | 0.37%   |
| Budgie          | 1         | 0.37%   |
| awesome         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 170       | 62.5%   |
| Wayland | 87        | 31.99%  |
| Unknown | 13        | 4.78%   |
| Tty     | 2         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 114       | 41.91%  |
| GDM3    | 53        | 19.49%  |
| GDM     | 37        | 13.6%   |
| LightDM | 30        | 11.03%  |
| SDDM    | 29        | 10.66%  |
| TDM     | 5         | 1.84%   |
| KDM     | 2         | 0.74%   |
| GREETD  | 2         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 199       | 74.81%  |
| en_GB   | 31        | 11.65%  |
| Unknown | 24        | 9.02%   |
| C       | 11        | 4.14%   |
| en_AG   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 139       | 51.87%  |
| EFI  | 129       | 48.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 204       | 76.69%  |
| Btrfs   | 31        | 11.65%  |
| Tmpfs   | 15        | 5.64%   |
| Overlay | 10        | 3.76%   |
| Xfs     | 3         | 1.13%   |
| Unknown | 2         | 0.75%   |
| Zfs     | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 118       | 43.7%   |
| GPT     | 114       | 42.22%  |
| MBR     | 38        | 14.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 238       | 89.81%  |
| Yes       | 27        | 10.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 190       | 71.16%  |
| Yes       | 77        | 28.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 123       | 46.77%  |
| Lenovo                      | 56        | 21.29%  |
| Dell                        | 30        | 11.41%  |
| Toshiba                     | 10        | 3.8%    |
| ASUSTek Computer            | 10        | 3.8%    |
| Acer                        | 5         | 1.9%    |
| Samsung Electronics         | 3         | 1.14%   |
| Apple                       | 3         | 1.14%   |
| TECNO                       | 2         | 0.76%   |
| SLIMBOOK                    | 2         | 0.76%   |
| Endless                     | 2         | 0.76%   |
| Chuwi                       | 2         | 0.76%   |
| Sony                        | 1         | 0.38%   |
| Panasonic                   | 1         | 0.38%   |
| Notebook                    | 1         | 0.38%   |
| LG Electronics              | 1         | 0.38%   |
| Jemper                      | 1         | 0.38%   |
| Insyde                      | 1         | 0.38%   |
| I-Life Digital Technologies | 1         | 0.38%   |
| HUAWEI                      | 1         | 0.38%   |
| Getac                       | 1         | 0.38%   |
| Fujitsu                     | 1         | 0.38%   |
| EVOC                        | 1         | 0.38%   |
| EUROCOM                     | 1         | 0.38%   |
| Eluktronics                 | 1         | 0.38%   |
| Clevo                       | 1         | 0.38%   |
| Unknown                     | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| HP EliteBook 840 G1            | 10        | 3.8%    |
| HP EliteBook Folio 9480m       | 6         | 2.28%   |
| HP EliteBook 840 G3            | 5         | 1.9%    |
| HP EliteBook Folio 9470m       | 4         | 1.52%   |
| HP EliteBook 8460p             | 4         | 1.52%   |
| Dell XPS 13 9310               | 4         | 1.52%   |
| HP ProBook 6560b               | 3         | 1.14%   |
| HP ProBook 4540s               | 3         | 1.14%   |
| HP Notebook                    | 3         | 1.14%   |
| HP EliteBook 840 G2            | 3         | 1.14%   |
| HP EliteBook 820 G3            | 3         | 1.14%   |
| HP EliteBook 2570p             | 3         | 1.14%   |
| HP 630                         | 3         | 1.14%   |
| HP 15                          | 3         | 1.14%   |
| ASUS X540NA                    | 3         | 1.14%   |
| Unknown                        | 3         | 1.14%   |
| Toshiba TECRA X40-E            | 2         | 0.76%   |
| Toshiba Satellite C660         | 2         | 0.76%   |
| TECNO WinPad 2                 | 2         | 0.76%   |
| Lenovo IdeaPad S340-14IIL 81VV | 2         | 0.76%   |
| Lenovo IdeaPad 3 14ITL6 82H7   | 2         | 0.76%   |
| Lenovo G50-80 80E5             | 2         | 0.76%   |
| HP ProBook 650 G2              | 2         | 0.76%   |
| HP ProBook 6470b               | 2         | 0.76%   |
| HP ProBook 640 G1              | 2         | 0.76%   |
| HP ProBook 450 G6              | 2         | 0.76%   |
| HP ProBook 440 G5              | 2         | 0.76%   |
| HP Pavilion Laptop 15-cs3xxx   | 2         | 0.76%   |
| HP Laptop 15-da1xxx            | 2         | 0.76%   |
| HP ENVY 15                     | 2         | 0.76%   |
| HP EliteBook 8440p             | 2         | 0.76%   |
| HP EliteBook 840 G5            | 2         | 0.76%   |
| HP Compaq Mini 110c-1100       | 2         | 0.76%   |
| HP 15 Notebook PC              | 2         | 0.76%   |
| Endless EF20EA                 | 2         | 0.76%   |
| Dell Latitude E6410            | 2         | 0.76%   |
| Dell Inspiron 5767             | 2         | 0.76%   |
| Toshiba TECRA A50-A            | 1         | 0.38%   |
| Toshiba Satellite L50-B        | 1         | 0.38%   |
| Toshiba Satellite C850D-B615   | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 55        | 20.91%  |
| Lenovo ThinkPad        | 27        | 10.27%  |
| HP ProBook             | 27        | 10.27%  |
| Dell Latitude          | 15        | 5.7%    |
| Lenovo IdeaPad         | 14        | 5.32%   |
| Dell Inspiron          | 10        | 3.8%    |
| HP Pavilion            | 8         | 3.04%   |
| HP Laptop              | 7         | 2.66%   |
| HP ENVY                | 6         | 2.28%   |
| HP 15                  | 5         | 1.9%    |
| Dell XPS               | 5         | 1.9%    |
| Toshiba Satellite      | 4         | 1.52%   |
| Lenovo Legion          | 4         | 1.52%   |
| Acer Aspire            | 4         | 1.52%   |
| Toshiba TECRA          | 3         | 1.14%   |
| HP Notebook            | 3         | 1.14%   |
| HP 630                 | 3         | 1.14%   |
| ASUS X540NA            | 3         | 1.14%   |
| Unknown                | 3         | 1.14%   |
| Toshiba dynabook       | 2         | 0.76%   |
| TECNO WinPad           | 2         | 0.76%   |
| Lenovo G50-80          | 2         | 0.76%   |
| HP ZBook               | 2         | 0.76%   |
| HP Compaq              | 2         | 0.76%   |
| Endless EF20EA         | 2         | 0.76%   |
| Toshiba R84SAU2        | 1         | 0.38%   |
| Sony VGN-NS295J        | 1         | 0.38%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.38%   |
| SLIMBOOK Executive     | 1         | 0.38%   |
| Samsung RC410          | 1         | 0.38%   |
| Samsung 300E5EV        | 1         | 0.38%   |
| Samsung 300E4C         | 1         | 0.38%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.38%   |
| Notebook P65xHP        | 1         | 0.38%   |
| LG LW25-B7HG           | 1         | 0.38%   |
| Lenovo Z50-75          | 1         | 0.38%   |
| Lenovo V330-14IKB      | 1         | 0.38%   |
| Lenovo V310-15ISK      | 1         | 0.38%   |
| Lenovo V14-IGL         | 1         | 0.38%   |
| Lenovo V130-14IKB      | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 28        | 10.65%  |
| 2019    | 25        | 9.51%   |
| 2018    | 25        | 9.51%   |
| 2016    | 25        | 9.51%   |
| 2014    | 25        | 9.51%   |
| 2012    | 22        | 8.37%   |
| 2015    | 20        | 7.6%    |
| 2011    | 20        | 7.6%    |
| 2020    | 17        | 6.46%   |
| 2017    | 17        | 6.46%   |
| 2010    | 12        | 4.56%   |
| 2021    | 11        | 4.18%   |
| 2022    | 3         | 1.14%   |
| 2008    | 3         | 1.14%   |
| 2007    | 3         | 1.14%   |
| 2006    | 3         | 1.14%   |
| 2009    | 2         | 0.76%   |
| 2024    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 263       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 244       | 91.73%  |
| Enabled  | 22        | 8.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 263       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 84        | 31.46%  |
| 3.01-4.0    | 64        | 23.97%  |
| 8.01-16.0   | 41        | 15.36%  |
| 16.01-24.0  | 37        | 13.86%  |
| 1.01-2.0    | 17        | 6.37%   |
| 32.01-64.0  | 12        | 4.49%   |
| 64.01-256.0 | 5         | 1.87%   |
| 24.01-32.0  | 3         | 1.12%   |
| 0.51-1.0    | 3         | 1.12%   |
| 2.01-3.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 81        | 27.65%  |
| 1.01-2.0  | 69        | 23.55%  |
| 4.01-8.0  | 58        | 19.8%   |
| 3.01-4.0  | 57        | 19.45%  |
| 0.51-1.0  | 18        | 6.14%   |
| 8.01-16.0 | 9         | 3.07%   |
| 0.01-0.5  | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 222       | 82.22%  |
| 2      | 39        | 14.44%  |
| 0      | 5         | 1.85%   |
| 10     | 1         | 0.37%   |
| 8      | 1         | 0.37%   |
| 4      | 1         | 0.37%   |
| 3      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 66.16%  |
| Yes       | 89        | 33.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 81.75%  |
| No        | 48        | 18.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 95.08%  |
| No        | 13        | 4.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 78.57%  |
| No        | 57        | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 263       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Nairobi      | 239       | 87.87%  |
| Mombasa      | 6         | 2.21%   |
| Kiambu       | 3         | 1.1%    |
| Embakasi     | 3         | 1.1%    |
| Nyahururu    | 2         | 0.74%   |
| Nakuru       | 2         | 0.74%   |
| Machakos     | 2         | 0.74%   |
| Kikuyu       | 2         | 0.74%   |
| Eldoret      | 2         | 0.74%   |
| Wote         | 1         | 0.37%   |
| Rongai       | 1         | 0.37%   |
| Nyeri        | 1         | 0.37%   |
| Narok        | 1         | 0.37%   |
| Nanyuki      | 1         | 0.37%   |
| Murang'a     | 1         | 0.37%   |
| Maralal      | 1         | 0.37%   |
| Mairo Inya   | 1         | 0.37%   |
| Loglogo      | 1         | 0.37%   |
| Kisii        | 1         | 0.37%   |
| Archers Post | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 65        | 85     | 21.96%  |
| Samsung Electronics         | 38        | 52     | 12.84%  |
| Toshiba                     | 37        | 44     | 12.5%   |
| WDC                         | 33        | 40     | 11.15%  |
| HGST                        | 18        | 28     | 6.08%   |
| Unknown                     | 16        | 20     | 5.41%   |
| SanDisk                     | 10        | 12     | 3.38%   |
| Hitachi                     | 10        | 13     | 3.38%   |
| Micron Technology           | 9         | 10     | 3.04%   |
| Crucial                     | 6         | 8      | 2.03%   |
| SK hynix                    | 5         | 5      | 1.69%   |
| MARSHAL                     | 5         | 5      | 1.69%   |
| Lexar                       | 5         | 5      | 1.69%   |
| LITEON                      | 3         | 3      | 1.01%   |
| Kingston                    | 3         | 5      | 1.01%   |
| SPCC                        | 2         | 2      | 0.68%   |
| Silicon Motion              | 2         | 3      | 0.68%   |
| Intel                       | 2         | 2      | 0.68%   |
| China                       | 2         | 2      | 0.68%   |
| Apple                       | 2         | 2      | 0.68%   |
| A-DATA Technology           | 2         | 2      | 0.68%   |
| Unknown                     | 2         | 2      | 0.68%   |
| Union Memory                | 1         | 1      | 0.34%   |
| Team                        | 1         | 2      | 0.34%   |
| TCSUNBOW                    | 1         | 1      | 0.34%   |
| Plextor                     | 1         | 1      | 0.34%   |
| Phison Electronics          | 1         | 2      | 0.34%   |
| Netac                       | 1         | 1      | 0.34%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.34%   |
| MAX                         | 1         | 1      | 0.34%   |
| LITEONIT                    | 1         | 1      | 0.34%   |
| Lite-On Technology          | 1         | 2      | 0.34%   |
| KIOXIA                      | 1         | 1      | 0.34%   |
| KINGBANK                    | 1         | 1      | 0.34%   |
| HUAWEI                      | 1         | 1      | 0.34%   |
| Hjwdz                       | 1         | 1      | 0.34%   |
| Gritronix                   | 1         | 2      | 0.34%   |
| Golden                      | 1         | 1      | 0.34%   |
| Eluktro                     | 1         | 1      | 0.34%   |
| CARLSTEIN                   | 1         | 5      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 13        | 4.28%   |
| HGST HTS725050A7E630 500GB                            | 8         | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                       | 7         | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 7         | 2.3%    |
| Unknown MMC Card  64GB                                | 6         | 1.97%   |
| Toshiba MQ04ABF100 1TB                                | 6         | 1.97%   |
| Seagate ST9500325AS 500GB                             | 6         | 1.97%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 1.64%   |
| Toshiba MQ01ABD100 1TB                                | 4         | 1.32%   |
| Seagate ST500VT000-1DK142 500GB                       | 4         | 1.32%   |
| Seagate ST500LT012-1DG142 500GB                       | 4         | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB                       | 4         | 1.32%   |
| Samsung SSD 960 EVO 1TB                               | 4         | 1.32%   |
| WDC WD5000LPCX-60VHAT0 500GB                          | 3         | 0.99%   |
| WDC PC SN730 NVMe 512GB                               | 3         | 0.99%   |
| Unknown MMC Card  32GB                                | 3         | 0.99%   |
| Toshiba MQ01ABD050V 500GB                             | 3         | 0.99%   |
| Seagate ST500LM000-1EJ162 500GB                       | 3         | 0.99%   |
| MARSHAL MAL2500SA-T54L 500GB                          | 3         | 0.99%   |
| Crucial CT2050MX300SSD1 2TB                           | 3         | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 2         | 0.66%   |
| WDC WD5000LPCX-24VHAT0 500GB                          | 2         | 0.66%   |
| WDC WD5000LPCX-24C6HT0 500GB                          | 2         | 0.66%   |
| WDC WD2500BEKT-75PVMT0 250GB                          | 2         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 2         | 0.66%   |
| Unknown NCard  32GB                                   | 2         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.66%   |
| Seagate ST500LM030-1RK17D 500GB                       | 2         | 0.66%   |
| Seagate ST250LT003-9YG14C 250GB                       | 2         | 0.66%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                    | 2         | 0.66%   |
| Seagate ST1000VT001-1RE172 1TB                        | 2         | 0.66%   |
| Samsung SSD PM830 2.5 7mm 128GB                       | 2         | 0.66%   |
| Samsung NVMe SSD Drive 512GB                          | 2         | 0.66%   |
| Samsung NVMe SSD Drive 256GB                          | 2         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 2         | 0.66%   |
| Samsung MZVLQ256HBJD-00BH1 256GB                      | 2         | 0.66%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD              | 2         | 0.66%   |
| LITEON L8H-256V2G-HP 256GB SSD                        | 2         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 85     | 42.21%  |
| Toshiba             | 30        | 37     | 19.48%  |
| WDC                 | 24        | 30     | 15.58%  |
| HGST                | 18        | 28     | 11.69%  |
| Hitachi             | 10        | 13     | 6.49%   |
| MARSHAL             | 5         | 5      | 3.25%   |
| Samsung Electronics | 2         | 2      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 13     | 16.13%  |
| SanDisk             | 9         | 10     | 14.52%  |
| Crucial             | 6         | 8      | 9.68%   |
| Micron Technology   | 5         | 6      | 8.06%   |
| Lexar               | 4         | 4      | 6.45%   |
| WDC                 | 3         | 4      | 4.84%   |
| SK hynix            | 3         | 3      | 4.84%   |
| LITEON              | 3         | 3      | 4.84%   |
| Toshiba             | 2         | 2      | 3.23%   |
| Kingston            | 2         | 4      | 3.23%   |
| China               | 2         | 2      | 3.23%   |
| TCSUNBOW            | 1         | 1      | 1.61%   |
| Plextor             | 1         | 1      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| MAX                 | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| KINGBANK            | 1         | 1      | 1.61%   |
| Gritronix           | 1         | 2      | 1.61%   |
| Golden              | 1         | 1      | 1.61%   |
| Eluktro             | 1         | 1      | 1.61%   |
| ASMT                | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |
| Unknown             | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 151       | 200    | 51.71%  |
| NVMe    | 61        | 76     | 20.89%  |
| SSD     | 60        | 73     | 20.55%  |
| MMC     | 17        | 21     | 5.82%   |
| Unknown | 3         | 7      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 197       | 275    | 70.36%  |
| NVMe | 61        | 76     | 21.79%  |
| MMC  | 17        | 21     | 6.07%   |
| SAS  | 5         | 5      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 145       | 191    | 70.73%  |
| 0.51-1.0   | 54        | 66     | 26.34%  |
| 1.01-2.0   | 5         | 12     | 2.44%   |
| 3.01-4.0   | 1         | 4      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 28.1%   |
| 101-250        | 69        | 25.18%  |
| 501-1000       | 48        | 17.52%  |
| 51-100         | 26        | 9.49%   |
| 1001-2000      | 14        | 5.11%   |
| 1-20           | 11        | 4.01%   |
| Unknown        | 10        | 3.65%   |
| 21-50          | 8         | 2.92%   |
| 2001-3000      | 6         | 2.19%   |
| More than 3000 | 5         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 26.32%  |
| 21-50          | 53        | 18.6%   |
| 101-250        | 50        | 17.54%  |
| 51-100         | 47        | 16.49%  |
| 251-500        | 28        | 9.82%   |
| 501-1000       | 13        | 4.56%   |
| Unknown        | 10        | 3.51%   |
| 1001-2000      | 5         | 1.75%   |
| More than 3000 | 3         | 1.05%   |
| 2001-3000      | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050V 500GB             | 3         | 3      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 7.14%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 4.76%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.76%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 4.76%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 4.76%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 4.76%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 2.38%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 2.38%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.38%   |
| Toshiba MK8009GAH 80GB                | 1         | 1      | 2.38%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 2.38%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 2.38%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 2.38%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1      | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.38%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.38%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 2.38%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 2.38%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 2.38%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.38%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 2.38%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 2.38%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.38%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 2.38%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 2.38%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 34.15%  |
| Toshiba             | 9         | 9      | 21.95%  |
| HGST                | 6         | 9      | 14.63%  |
| WDC                 | 5         | 5      | 12.2%   |
| MARSHAL             | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 3      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| Crucial             | 1         | 2      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 35.9%   |
| Toshiba             | 9         | 9      | 23.08%  |
| HGST                | 6         | 9      | 15.38%  |
| WDC                 | 5         | 5      | 12.82%  |
| MARSHAL             | 2         | 2      | 5.13%   |
| Hitachi             | 2         | 3      | 5.13%   |
| Samsung Electronics | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 43     | 95.12%  |
| SSD  | 2         | 3      | 4.88%   |

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
| Detected | 144       | 202    | 52.94%  |
| Works    | 88        | 129    | 32.35%  |
| Malfunc  | 40        | 46     | 14.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 220       | 76.12%  |
| Samsung Electronics          | 28        | 9.69%   |
| AMD                          | 8         | 2.77%   |
| SanDisk                      | 7         | 2.42%   |
| Toshiba America Info Systems | 5         | 1.73%   |
| Silicon Motion               | 4         | 1.38%   |
| Micron Technology            | 4         | 1.38%   |
| SK hynix                     | 2         | 0.69%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.69%   |
| Union Memory (Shenzhen)      | 1         | 0.35%   |
| Shenzhen Longsys Electronics | 1         | 0.35%   |
| Phison Electronics           | 1         | 0.35%   |
| Lite-On Technology           | 1         | 0.35%   |
| KIOXIA                       | 1         | 0.35%   |
| Kingston Technology Company  | 1         | 0.35%   |
| ASMedia Technology           | 1         | 0.35%   |
| Apple                        | 1         | 0.35%   |
| ADATA Technology             | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 36        | 12%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 28        | 9.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 21        | 7%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 20        | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 18        | 6%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 15        | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 14        | 4.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 12        | 4%      |
| Intel Volume Management Device NVMe RAID Controller                                                                | 9         | 3%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 8         | 2.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 8         | 2.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 6         | 2%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 5         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 5         | 1.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 4         | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 4         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4         | 1.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 4         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 4         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 4         | 1.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 3         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 3         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 3         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 3         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 3         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 3         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                                                     | 3         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 3         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 3         | 1%      |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 2         | 0.67%   |
| Micron 2200S NVMe SSD [Cassandra]                                                                                  | 2         | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 0.67%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 2         | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 2         | 0.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                                                      | 2         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 0.67%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                                                              | 1         | 0.33%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                                               | 1         | 0.33%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                                                | 1         | 0.33%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 194       | 66.21%  |
| NVMe | 61        | 20.82%  |
| RAID | 27        | 9.22%   |
| IDE  | 11        | 3.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 250       | 95.06%  |
| AMD    | 13        | 4.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 8         | 3.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 7         | 2.66%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 6         | 2.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 2.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 1.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 5         | 1.9%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 5         | 1.9%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 1.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 1.52%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 4         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 1.52%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.14%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 3         | 1.14%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.14%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 3         | 1.14%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.14%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 1.14%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.14%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.14%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.76%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 97        | 36.88%  |
| Intel Core i7           | 65        | 24.71%  |
| Intel Celeron           | 22        | 8.37%   |
| Intel Core i3           | 21        | 7.98%   |
| Other                   | 14        | 5.32%   |
| Intel Atom              | 11        | 4.18%   |
| Intel Pentium           | 5         | 1.9%    |
| Intel Core 2 Duo        | 4         | 1.52%   |
| AMD Ryzen 7             | 4         | 1.52%   |
| AMD Ryzen 5             | 4         | 1.52%   |
| Intel Core i9           | 3         | 1.14%   |
| Intel Pentium Dual-Core | 2         | 0.76%   |
| Intel Core 2            | 2         | 0.76%   |
| AMD A10                 | 2         | 0.76%   |
| Intel Pentium Gold      | 1         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.38%   |
| Intel Genuine           | 1         | 0.38%   |
| Intel Core m3           | 1         | 0.38%   |
| AMD Ryzen 3 PRO         | 1         | 0.38%   |
| AMD FX                  | 1         | 0.38%   |
| AMD E2                  | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 169       | 64.26%  |
| 4       | 71        | 27%     |
| 6       | 10        | 3.8%    |
| 8       | 8         | 3.04%   |
| 14      | 2         | 0.76%   |
| 1       | 2         | 0.76%   |
| Unknown | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 263       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 214       | 81.37%  |
| 1       | 48        | 18.25%  |
| Unknown | 1         | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 260       | 98.86%  |
| 32-bit         | 2         | 0.76%   |
| Unknown        | 1         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 41.24%  |
| 0x306a9    | 21        | 7.66%   |
| 0x206a7    | 18        | 6.57%   |
| 0x40651    | 15        | 5.47%   |
| 0x406e3    | 12        | 4.38%   |
| 0x306c3    | 9         | 3.28%   |
| 0x306d4    | 8         | 2.92%   |
| 0x806ec    | 6         | 2.19%   |
| 0x806ea    | 6         | 2.19%   |
| 0x806c1    | 6         | 2.19%   |
| 0x30678    | 5         | 1.82%   |
| 0x20655    | 5         | 1.82%   |
| 0x406c4    | 4         | 1.46%   |
| 0x906ea    | 3         | 1.09%   |
| 0x806e9    | 3         | 1.09%   |
| 0x706e5    | 3         | 1.09%   |
| 0x706a8    | 3         | 1.09%   |
| 0x6fd      | 3         | 1.09%   |
| 0x1067a    | 3         | 1.09%   |
| 0x906e9    | 2         | 0.73%   |
| 0x806eb    | 2         | 0.73%   |
| 0x706a1    | 2         | 0.73%   |
| 0x406c3    | 2         | 0.73%   |
| 0x106c2    | 2         | 0.73%   |
| 0x08608103 | 2         | 0.73%   |
| 0x08600106 | 2         | 0.73%   |
| 0xa0652    | 1         | 0.36%   |
| 0x906ec    | 1         | 0.36%   |
| 0x806c2    | 1         | 0.36%   |
| 0x6fa      | 1         | 0.36%   |
| 0x6f6      | 1         | 0.36%   |
| 0x6f2      | 1         | 0.36%   |
| 0x506e3    | 1         | 0.36%   |
| 0x506c9    | 1         | 0.36%   |
| 0x30673    | 1         | 0.36%   |
| 0x0a50000d | 1         | 0.36%   |
| 0x08600103 | 1         | 0.36%   |
| 0x08108109 | 1         | 0.36%   |
| 0x0600611a | 1         | 0.36%   |
| 0x05000119 | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 19.01%  |
| Haswell          | 41        | 15.59%  |
| Skylake          | 25        | 9.51%   |
| SandyBridge      | 23        | 8.75%   |
| IvyBridge        | 23        | 8.75%   |
| Silvermont       | 18        | 6.84%   |
| Broadwell        | 16        | 6.08%   |
| TigerLake        | 12        | 4.56%   |
| Westmere         | 8         | 3.04%   |
| IceLake          | 7         | 2.66%   |
| Goldmont plus    | 6         | 2.28%   |
| Core             | 6         | 2.28%   |
| Zen 2            | 3         | 1.14%   |
| Penryn           | 3         | 1.14%   |
| Goldmont         | 3         | 1.14%   |
| CometLake        | 3         | 1.14%   |
| Unknown          | 3         | 1.14%   |
| Zen 3            | 2         | 0.76%   |
| Excavator        | 2         | 0.76%   |
| Bonnell          | 2         | 0.76%   |
| Alderlake Hybrid | 2         | 0.76%   |
| Zen+             | 1         | 0.38%   |
| Zen              | 1         | 0.38%   |
| Steamroller      | 1         | 0.38%   |
| P6               | 1         | 0.38%   |
| Bobcat           | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 235       | 78.33%  |
| Nvidia | 36        | 12%     |
| AMD    | 29        | 9.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 9.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 7.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.49%   |
| Intel HD Graphics 5500                                                                   | 16        | 5.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 4.87%   |
| Intel UHD Graphics 620                                                                   | 14        | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.57%   |
| Intel HD Graphics 620                                                                    | 8         | 2.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.62%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.97%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.97%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.97%   |
| Intel HD Graphics 500                                                                    | 3         | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.97%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.65%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.65%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 0.65%   |
| AMD Lucienne                                                                             | 2         | 0.65%   |
| AMD Barcelo                                                                              | 2         | 0.65%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.32%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.32%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.32%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 196       | 74.52%  |
| Intel + Nvidia | 25        | 9.51%   |
| 1 x AMD        | 17        | 6.46%   |
| Intel + AMD    | 11        | 4.18%   |
| 1 x Nvidia     | 10        | 3.8%    |
| 2 x Intel      | 3         | 1.14%   |
| 2 x AMD        | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 244       | 92.08%  |
| Proprietary | 18        | 6.79%   |
| Unknown     | 3         | 1.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 221       | 83.08%  |
| 1.01-2.0   | 17        | 6.39%   |
| 0.01-0.5   | 13        | 4.89%   |
| 3.01-4.0   | 5         | 1.88%   |
| 7.01-8.0   | 4         | 1.5%    |
| 5.01-6.0   | 3         | 1.13%   |
| 0.51-1.0   | 3         | 1.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 74        | 26.33%  |
| Chimei Innolux          | 47        | 16.73%  |
| BOE                     | 46        | 16.37%  |
| LG Display              | 35        | 12.46%  |
| Samsung Electronics     | 25        | 8.9%    |
| Hewlett-Packard         | 12        | 4.27%   |
| Sharp                   | 5         | 1.78%   |
| Chi Mei Optoelectronics | 5         | 1.78%   |
| Apple                   | 4         | 1.42%   |
| LG Philips              | 3         | 1.07%   |
| Lenovo                  | 3         | 1.07%   |
| KDC                     | 3         | 1.07%   |
| InfoVision              | 3         | 1.07%   |
| CSO                     | 3         | 1.07%   |
| Unknown (XXX)           | 2         | 0.71%   |
| HannStar                | 2         | 0.71%   |
| Dell                    | 2         | 0.71%   |
| Sony                    | 1         | 0.36%   |
| Planar                  | 1         | 0.36%   |
| NEC Computers           | 1         | 0.36%   |
| Goldstar                | 1         | 0.36%   |
| Eizo                    | 1         | 0.36%   |
| CVT                     | 1         | 0.36%   |
| Acer                    | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.78%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 5         | 1.78%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 1.78%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 4         | 1.42%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.07%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 3         | 1.07%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.07%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 1.07%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 1.07%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 1.07%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.07%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.07%   |
| AU Optronics LCD Monitor AUO233E 1600x900 309x174mm 14.0-inch            | 3         | 1.07%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.07%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 2         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 2         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 2         | 0.71%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch             | 2         | 0.71%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 2         | 0.71%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.71%   |
| Hewlett-Packard V214a HPN348C 1920x1080 458x258mm 20.7-inch              | 2         | 0.71%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch          | 2         | 0.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.71%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 2         | 0.71%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.71%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.71%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.71%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.71%   |
| BOE LCD Monitor BOE063A 1366x768 277x156mm 12.5-inch                     | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 126       | 46.49%  |
| 1920x1080 (FHD)    | 85        | 31.37%  |
| 1600x900 (HD+)     | 22        | 8.12%   |
| 1280x800 (WXGA)    | 8         | 2.95%   |
| 3840x2160 (4K)     | 6         | 2.21%   |
| 2560x1600          | 3         | 1.11%   |
| 1920x1200 (WUXGA)  | 3         | 1.11%   |
| 1440x900 (WXGA+)   | 3         | 1.11%   |
| 2560x1440 (QHD)    | 2         | 0.74%   |
| 1360x768           | 2         | 0.74%   |
| 1024x600           | 2         | 0.74%   |
| 3840x2400          | 1         | 0.37%   |
| 3200x1800 (QHD+)   | 1         | 0.37%   |
| 3072x1920          | 1         | 0.37%   |
| 2560x1080          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1680x1050 (WSXGA+) | 1         | 0.37%   |
| 1600x1200          | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |
| Unknown            | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 95        | 33.93%  |
| 14      | 62        | 22.14%  |
| 13      | 58        | 20.71%  |
| 12      | 14        | 5%      |
| 11      | 9         | 3.21%   |
| 17      | 7         | 2.5%    |
| 20      | 4         | 1.43%   |
| 16      | 4         | 1.43%   |
| 27      | 3         | 1.07%   |
| 23      | 3         | 1.07%   |
| 18      | 3         | 1.07%   |
| 10      | 3         | 1.07%   |
| 31      | 2         | 0.71%   |
| 24      | 2         | 0.71%   |
| 21      | 2         | 0.71%   |
| 84      | 1         | 0.36%   |
| 72      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 46      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 34      | 1         | 0.36%   |
| 26      | 1         | 0.36%   |
| 19      | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 194       | 69.53%  |
| 201-300     | 48        | 17.2%   |
| 351-400     | 10        | 3.58%   |
| 501-600     | 9         | 3.23%   |
| 401-500     | 9         | 3.23%   |
| 801-900     | 2         | 0.72%   |
| 601-700     | 2         | 0.72%   |
| 1501-2000   | 2         | 0.72%   |
| 1001-1500   | 1         | 0.36%   |
| 901-1000    | 1         | 0.36%   |
| Unknown     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 232       | 89.23%  |
| 16/10   | 23        | 8.85%   |
| 5/4     | 1         | 0.38%   |
| 4/3     | 1         | 0.38%   |
| 3/2     | 1         | 0.38%   |
| 21/9    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 98        | 35%     |
| 101-110        | 94        | 33.57%  |
| 71-80          | 22        | 7.86%   |
| 61-70          | 14        | 5%      |
| 51-60          | 9         | 3.21%   |
| 201-250        | 7         | 2.5%    |
| 151-200        | 5         | 1.79%   |
| 121-130        | 5         | 1.79%   |
| 141-150        | 4         | 1.43%   |
| 111-120        | 4         | 1.43%   |
| More than 1000 | 3         | 1.07%   |
| 351-500        | 3         | 1.07%   |
| 41-50          | 3         | 1.07%   |
| 301-350        | 3         | 1.07%   |
| 501-1000       | 2         | 0.71%   |
| 251-300        | 1         | 0.36%   |
| 131-140        | 1         | 0.36%   |
| 91-100         | 1         | 0.36%   |
| Unknown        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 113       | 40.79%  |
| 101-120       | 103       | 37.18%  |
| 51-100        | 34        | 12.27%  |
| 161-240       | 17        | 6.14%   |
| More than 240 | 6         | 2.17%   |
| 1-50          | 3         | 1.08%   |
| Unknown       | 1         | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 232       | 85.93%  |
| 2     | 32        | 11.85%  |
| 0     | 5         | 1.85%   |
| 3     | 1         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 164       | 41.84%  |
| Realtek Semiconductor             | 107       | 27.3%   |
| Qualcomm Atheros                  | 48        | 12.24%  |
| Broadcom                          | 22        | 5.61%   |
| Hewlett-Packard                   | 7         | 1.79%   |
| Samsung Electronics               | 6         | 1.53%   |
| Ralink                            | 5         | 1.28%   |
| MediaTek                          | 5         | 1.28%   |
| Broadcom Limited                  | 4         | 1.02%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.77%   |
| Sierra Wireless                   | 3         | 0.77%   |
| OPPO Electronics                  | 3         | 0.77%   |
| Marvell Technology Group          | 3         | 0.77%   |
| Huawei Technologies               | 3         | 0.77%   |
| T & A Mobile Phones               | 2         | 0.51%   |
| Spreadtrum Communications         | 2         | 0.51%   |
| Ralink Technology                 | 2         | 0.51%   |
| Ericsson Business Mobile Networks | 2         | 0.51%   |
| LSI                               | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 12.48%  |
| Intel Wireless 7260                                                    | 28        | 5.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 4.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 4.75%   |
| Intel Ethernet Connection I218-LM                                      | 22        | 4.36%   |
| Intel Wireless 8260                                                    | 16        | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 2.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 14        | 2.77%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 2.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 2.18%   |
| Intel Wireless 8265 / 8275                                             | 11        | 2.18%   |
| Intel Wireless 7265                                                    | 10        | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.78%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.58%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 5         | 0.99%   |
| Intel Centrino Advanced-N 6200                                         | 5         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 5         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.79%   |
| Intel Wireless 3160                                                    | 4         | 0.79%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.79%   |
| HP lt4112 Gobi 4G Module Network Device                                | 4         | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.79%   |
| ZTE WCDMA MSM ZTE Mobile Broadband                                     | 3         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 149       | 56.65%  |
| Qualcomm Atheros      | 43        | 16.35%  |
| Realtek Semiconductor | 33        | 12.55%  |
| Broadcom              | 19        | 7.22%   |
| Ralink                | 5         | 1.9%    |
| Hewlett-Packard       | 5         | 1.9%    |
| Sierra Wireless       | 3         | 1.14%   |
| Broadcom Limited      | 3         | 1.14%   |
| Ralink Technology     | 2         | 0.76%   |
| MediaTek              | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 28        | 10.65%  |
| Intel Wireless 8260                                            | 16        | 6.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 5.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 5.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 4.18%   |
| Intel Wireless 8265 / 8275                                     | 11        | 4.18%   |
| Intel Wireless 7265                                            | 10        | 3.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 3.42%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 3.04%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 2.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.9%    |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.9%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 1.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.52%   |
| Intel Wireless 3160                                            | 4         | 1.52%   |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.14%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 104       | 44.83%  |
| Realtek Semiconductor     | 93        | 40.09%  |
| Qualcomm Atheros          | 8         | 3.45%   |
| MediaTek                  | 4         | 1.72%   |
| Broadcom                  | 4         | 1.72%   |
| Samsung Electronics       | 3         | 1.29%   |
| OPPO Electronics          | 3         | 1.29%   |
| Marvell Technology Group  | 3         | 1.29%   |
| T & A Mobile Phones       | 2         | 0.86%   |
| Spreadtrum Communications | 2         | 0.86%   |
| Huawei Technologies       | 2         | 0.86%   |
| Hewlett-Packard           | 2         | 0.86%   |
| LSI                       | 1         | 0.43%   |
| Broadcom Limited          | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 27.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 10.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 10.3%   |
| Intel Ethernet Connection I218-LM                                      | 22        | 9.44%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 5.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 3.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 3%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 2.58%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 2.15%   |
| Intel Ethernet Connection I219-V                                       | 4         | 1.72%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.72%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.72%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.29%   |
| MediaTek Infinix SMART 5                                               | 3         | 1.29%   |
| T & A Mobile Phones TCL 50 NXTPAPER 5G                                 | 2         | 0.86%   |
| Spreadtrum Unisoc Phone                                                | 2         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.86%   |
| OPPO OnePlus Nord 4                                                    | 2         | 0.86%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.86%   |
| Huawei E353/E3131                                                      | 2         | 0.86%   |
| HP HP lt4120 Snapdragon X5 LTE                                         | 2         | 0.86%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.86%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.43%   |
| OPPO CPH2477                                                           | 1         | 0.43%   |
| MediaTek TANK2                                                         | 1         | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.43%   |
| LSI ET-131x PCI-E Ethernet Controller                                  | 1         | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 52.84%  |
| Ethernet | 215       | 45.26%  |
| Modem    | 9         | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 218       | 81.04%  |
| Ethernet | 49        | 18.22%  |
| Modem    | 2         | 0.74%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 201       | 75.56%  |
| 1     | 50        | 18.8%   |
| 0     | 11        | 4.14%   |
| 3     | 4         | 1.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 255       | 96.96%  |
| Yes  | 8         | 3.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 56.67%  |
| Qualcomm Atheros Communications | 27        | 12.86%  |
| Realtek Semiconductor           | 18        | 8.57%   |
| Broadcom                        | 14        | 6.67%   |
| Hewlett-Packard                 | 6         | 2.86%   |
| Ralink                          | 4         | 1.9%    |
| Lite-On Technology              | 4         | 1.9%    |
| IMC Networks                    | 4         | 1.9%    |
| Toshiba                         | 2         | 0.95%   |
| Foxconn / Hon Hai               | 2         | 0.95%   |
| Dell                            | 2         | 0.95%   |
| Cambridge Silicon Radio         | 2         | 0.95%   |
| Apple                           | 2         | 0.95%   |
| Taiyo Yuden                     | 1         | 0.48%   |
| Realtek                         | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |
| Unknown                         | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 68        | 32.38%  |
| Intel AX201 Bluetooth                               | 17        | 8.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.67%   |
| Realtek Bluetooth Radio                             | 10        | 4.76%   |
| Intel AX200 Bluetooth                               | 7         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 2.38%   |
| Broadcom HP Portable SoftSailing                    | 5         | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.9%    |
| Ralink RT3290 Bluetooth                             | 4         | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.9%    |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.9%    |
| Realtek 802.11ac WLAN Adapter                       | 3         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.43%   |
| Intel AX210 Bluetooth                               | 3         | 1.43%   |
| IMC Networks Bluetooth Device                       | 3         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.95%   |
| Lite-On Bluetooth Device                            | 2         | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.95%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.95%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.48%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.48%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.48%   |
| Realtek Bluetooth Radio                             | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.48%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.48%   |
| Intel AX211 Bluetooth                               | 1         | 0.48%   |
| IMC Networks Bluetooth                              | 1         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 240       | 84.21%  |
| AMD                         | 18        | 6.32%   |
| Nvidia                      | 17        | 5.96%   |
| Realtek Semiconductor       | 2         | 0.7%    |
| Generalplus Technology      | 2         | 0.7%    |
| Turtle Beach                | 1         | 0.35%   |
| Toshiba                     | 1         | 0.35%   |
| Texas Instruments           | 1         | 0.35%   |
| GN Netcom                   | 1         | 0.35%   |
| FiiO Electronics Technology | 1         | 0.35%   |
| Apple                       | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 47        | 13.35%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 29        | 8.24%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 7.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 4.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 4.55%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 3.13%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 9         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.57%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.57%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.57%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.28%   |
| Toshiba Toshiba Thunderbolt3 Dock Audio                                                           | 1         | 0.28%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.28%   |
| Realtek Semiconductor HP Banff                                                                    | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 65        | 32.99%  |
| SK hynix            | 49        | 24.87%  |
| Micron Technology   | 24        | 12.18%  |
| Unknown             | 13        | 6.6%    |
| Kingston            | 11        | 5.58%   |
| Ramaxel Technology  | 6         | 3.05%   |
| Elpida              | 6         | 3.05%   |
| Crucial             | 5         | 2.54%   |
| A-DATA Technology   | 4         | 2.03%   |
| Timetec             | 2         | 1.02%   |
| Lexar               | 2         | 1.02%   |
| Apacer              | 2         | 1.02%   |
| Unknown             | 2         | 1.02%   |
| Wilk                | 1         | 0.51%   |
| Team                | 1         | 0.51%   |
| Qimonda             | 1         | 0.51%   |
| Patriot             | 1         | 0.51%   |
| Nanya Technology    | 1         | 0.51%   |
| Avant               | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 8         | 3.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 7         | 3.45%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 4         | 1.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 4         | 1.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 1.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.97%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 4         | 1.97%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 1.48%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.48%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 3         | 1.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 3         | 1.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 1.48%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 0.99%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.99%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.99%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 0.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.99%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.99%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 2         | 0.99%   |
| Micron RAM 16JTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.99%   |
| Apacer RAM 76.A302G.C4D0B 2GB SODIMM DDR3 1600MT/s           | 2         | 0.99%   |
| Unknown                                                      | 2         | 0.99%   |
| Wilk RAM GR5600S564L46/32G 32GB SODIMM DDR5 5600MT/s         | 1         | 0.49%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 72        | 48.32%  |
| DDR4   | 59        | 39.6%   |
| DDR2   | 6         | 4.03%   |
| LPDDR4 | 4         | 2.68%   |
| LPDDR3 | 3         | 2.01%   |
| DDR5   | 2         | 1.34%   |
| DDR    | 2         | 1.34%   |
| SDRAM  | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 138       | 86.79%  |
| Row Of Chips | 15        | 9.43%   |
| Chip         | 6         | 3.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 61        | 35.26%  |
| 8192  | 56        | 32.37%  |
| 16384 | 23        | 13.29%  |
| 2048  | 21        | 12.14%  |
| 1024  | 6         | 3.47%   |
| 32768 | 5         | 2.89%   |
| 512   | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 35.71%  |
| 2667    | 33        | 19.64%  |
| 3200    | 17        | 10.12%  |
| 2133    | 14        | 8.33%   |
| 1334    | 10        | 5.95%   |
| 1333    | 8         | 4.76%   |
| 2400    | 5         | 2.98%   |
| 4267    | 4         | 2.38%   |
| 667     | 3         | 1.79%   |
| 3266    | 2         | 1.19%   |
| 1867    | 2         | 1.19%   |
| 800     | 2         | 1.19%   |
| Unknown | 2         | 1.19%   |
| 8400    | 1         | 0.6%    |
| 5600    | 1         | 0.6%    |
| 4800    | 1         | 0.6%    |
| 4199    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| 533     | 1         | 0.6%    |

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
| Chicony Electronics                    | 74        | 30.58%  |
| Cheng Uei Precision Industry (Foxlink) | 35        | 14.46%  |
| Bison Electronics                      | 17        | 7.02%   |
| Lite-On Technology                     | 15        | 6.2%    |
| Sunplus Innovation Technology          | 14        | 5.79%   |
| Syntek                                 | 11        | 4.55%   |
| Microdia                               | 11        | 4.55%   |
| Realtek Semiconductor                  | 10        | 4.13%   |
| IMC Networks                           | 10        | 4.13%   |
| Quanta                                 | 8         | 3.31%   |
| Samsung Electronics                    | 5         | 2.07%   |
| Apple                                  | 4         | 1.65%   |
| Silicon Motion                         | 3         | 1.24%   |
| Luxvisions Innotech Limited            | 3         | 1.24%   |
| Acer                                   | 3         | 1.24%   |
| Unknown                                | 2         | 0.83%   |
| Suyin                                  | 2         | 0.83%   |
| Ricoh                                  | 2         | 0.83%   |
| Logitech                               | 2         | 0.83%   |
| Importek                               | 2         | 0.83%   |
| Alcor Micro                            | 2         | 0.83%   |
| SunplusIT                              | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| LG Electronics                         | 1         | 0.41%   |
| icSpring                               | 1         | 0.41%   |
| DigiTech                               | 1         | 0.41%   |
| ALi                                    | 1         | 0.41%   |
| Unknown                                | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 16        | 6.56%   |
| Chicony HP HD Webcam                                                       | 12        | 4.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 9         | 3.69%   |
| Syntek Integrated Camera                                                   | 7         | 2.87%   |
| Lite-On HP HD Webcam                                                       | 7         | 2.87%   |
| Lite-On HP HD Camera                                                       | 7         | 2.87%   |
| Bison Integrated Camera                                                    | 7         | 2.87%   |
| Chicony HP HD Webcam [Fixed]                                               | 6         | 2.46%   |
| Chicony HP HD Camera                                                       | 6         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.46%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.05%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 2.05%   |
| Chicony USB 2.0 Camera                                                     | 5         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 5         | 2.05%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.64%   |
| Sunplus HP HD Webcam [Fixed]                                               | 4         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 4         | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.64%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.64%   |
| Realtek Integrated Webcam                                                  | 3         | 1.23%   |
| Quanta HP HD Camera                                                        | 3         | 1.23%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 1.23%   |
| Chicony HD Webcam                                                          | 3         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 3         | 1.23%   |
| Bison ThinkPad P50 Integrated Camera                                       | 3         | 1.23%   |
| Unknown USB Camera                                                         | 2         | 0.82%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.82%   |
| Syntek EasyCamera                                                          | 2         | 0.82%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.82%   |
| Importek HP Webcam-50                                                      | 2         | 0.82%   |
| IMC Networks Integrated Camera                                             | 2         | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 0.82%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 0.82%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.82%   |
| Chicony HP Webcam                                                          | 2         | 0.82%   |
| Chicony HP Truevision HD                                                   | 2         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101                       | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 57        | 67.86%  |
| Synaptics                  | 17        | 20.24%  |
| Shenzhen Goodix Technology | 6         | 7.14%   |
| AuthenTec                  | 2         | 2.38%   |
| LighTuning Technology      | 1         | 1.19%   |
| Elan Microelectronics      | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 26.19%  |
| Validity Sensors VFS491                                                    | 11        | 13.1%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 8.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 4.76%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 4.76%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.57%   |
| Synaptics WBDI Device                                                      | 3         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.38%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.19%   |
| Synaptics  WBDI                                                            | 1         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.19%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.19%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 41.18%  |
| Alcor Micro | 6         | 35.29%  |
| Upek        | 2         | 11.76%  |
| O2 Micro    | 2         | 11.76%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 35.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 17.65%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 11.76%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.76%  |
| Broadcom 5880                                                                | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 159       | 59.77%  |
| 1     | 84        | 31.58%  |
| 2     | 21        | 7.89%   |
| 3     | 2         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 82        | 62.12%  |
| Chipcard                 | 16        | 12.12%  |
| Graphics card            | 11        | 8.33%   |
| Net/wireless             | 6         | 4.55%   |
| Bluetooth                | 5         | 3.79%   |
| Camera                   | 4         | 3.03%   |
| Storage                  | 3         | 2.27%   |
| Net/ethernet             | 2         | 1.52%   |
| Communication controller | 2         | 1.52%   |
| Sound                    | 1         | 0.76%   |


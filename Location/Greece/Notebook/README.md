Linux in Greece - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

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

Total: 813

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Inspiron 5567               | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | Latitude D630               | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| HP            | G7000                       | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Acer          | Aspire 5750G                | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| Sony          | VGN-AW11XU_Q                | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| Dell          | Latitude 7420               | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Dell          | Latitude E7470              | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Toshiba       | Satellite C50-B             | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| Dell          | Inspiron 3593               | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Toshiba       | Satellite C50-A-19T         | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| ASUSTek       | X550CA                      | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| e-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| e-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| HP            | Pavilion 11 x360 PC         | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| HP            | EliteBook 8570p             | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [8306c8cf0d](https://linux-hardware.org/?probe=8306c8cf0d) | Jan 12, 2022 |
| Unknown       | Unknown                     | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| HP            | Notebook                    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| HP            | Compaq 6730s                | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| HP            | EliteBook 8570p             | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Dell          | Inspiron 3585               | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | [64a10ac62b](https://linux-hardware.org/?probe=64a10ac62b) | Dec 15, 2021 |
| Sony          | SVE1113M1EB                 | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| HP            | G62                         | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | [20984b7808](https://linux-hardware.org/?probe=20984b7808) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| Dell          | Inspiron 3585               | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | G70-35 80Q5                 | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| Toshiba       | Satellite C855-27U          | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Sony          | SVF1521A1EW                 | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Unknown       | Unknown                     | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Acer          | Aspire 5735                 | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| ASUSTek       | X550CC                      | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Acer          | Aspire 5742                 | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| Sony          | SVE1513Y1ESI                | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| HP            | Notebook                    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| ARIMA         | W651UI                      | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | Alpha 17 A4DEK              | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8bf300aa62](https://linux-hardware.org/?probe=8bf300aa62) | Oct 05, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| HP            | Pavilion g6                 | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Sony          | VGN-FW510F                  | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Apple         | MacBookPro8,2               | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | [4718ed26ca](https://linux-hardware.org/?probe=4718ed26ca) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Dell          | Inspiron 15 5510            | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [877e0e98a4](https://linux-hardware.org/?probe=877e0e98a4) | Aug 27, 2021 |
| Sony          | SVT1122B2EW                 | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [dcf6e0d950](https://linux-hardware.org/?probe=dcf6e0d950) | Aug 22, 2021 |
| Sony          | SVT1122B2EW                 | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [05298cb71d](https://linux-hardware.org/?probe=05298cb71d) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Acer          | Aspire A517-51G             | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| HP            | Pavilion g6                 | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [63fdc16b6d](https://linux-hardware.org/?probe=63fdc16b6d) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| Dell          | Latitude 5410               | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| Sony          | VGN-FW510F                  | [a9d13b1ccb](https://linux-hardware.org/?probe=a9d13b1ccb) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |
| Dell          | Latitude D531               | [5a671e0dc0](https://linux-hardware.org/?probe=5a671e0dc0) | Jul 06, 2021 |
| Dell          | Latitude D531               | [bc3e80d306](https://linux-hardware.org/?probe=bc3e80d306) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| HP            | Laptop 15-bs1xx             | [f57bd1d1d8](https://linux-hardware.org/?probe=f57bd1d1d8) | Jul 04, 2021 |
| HP            | 255 G7 Notebook PC          | [3fcdda6371](https://linux-hardware.org/?probe=3fcdda6371) | Jul 04, 2021 |
| Sony          | VGN-FW510F                  | [16d31cc8f1](https://linux-hardware.org/?probe=16d31cc8f1) | Jul 02, 2021 |
| HP            | 255 G7 Notebook PC          | [0812ba2f1d](https://linux-hardware.org/?probe=0812ba2f1d) | Jul 01, 2021 |
| Sony          | VGN-FW510F                  | [e72a35c178](https://linux-hardware.org/?probe=e72a35c178) | Jun 26, 2021 |
| Chuwi         | GemiBook Pro                | [03f12de5a1](https://linux-hardware.org/?probe=03f12de5a1) | Jun 17, 2021 |
| HP            | 255 G7 Notebook PC          | [7563cf4f19](https://linux-hardware.org/?probe=7563cf4f19) | Jun 16, 2021 |
| HP            | 255 G7 Notebook PC          | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| Dell          | Latitude 7400               | [c58ebb3bf8](https://linux-hardware.org/?probe=c58ebb3bf8) | Jun 15, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| Chuwi         | GemiBook Pro                | [7a4b730903](https://linux-hardware.org/?probe=7a4b730903) | Jun 13, 2021 |
| Dell          | Vostro 3500                 | [128de02660](https://linux-hardware.org/?probe=128de02660) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | [e8a90de6cd](https://linux-hardware.org/?probe=e8a90de6cd) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Sony          | VGN-FW510F                  | [88362a4659](https://linux-hardware.org/?probe=88362a4659) | Jun 10, 2021 |
| Sony          | VGN-FW510F                  | [d87f3ea107](https://linux-hardware.org/?probe=d87f3ea107) | Jun 10, 2021 |
| HP            | Compaq 6910p                | [5b4d256824](https://linux-hardware.org/?probe=5b4d256824) | Jun 10, 2021 |
| Dell          | Inspiron 5559               | [356b7fd3c6](https://linux-hardware.org/?probe=356b7fd3c6) | Jun 09, 2021 |
| ASUSTek       | N550JV                      | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| PLAISIO CO... | TURBO-X                     | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [ef4e2ca66f](https://linux-hardware.org/?probe=ef4e2ca66f) | Jun 03, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [2ff583b918](https://linux-hardware.org/?probe=2ff583b918) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [bd16a61719](https://linux-hardware.org/?probe=bd16a61719) | May 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [da0e32387a](https://linux-hardware.org/?probe=da0e32387a) | May 31, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | [b9c73baf1d](https://linux-hardware.org/?probe=b9c73baf1d) | May 25, 2021 |
| Lenovo        | G500 20236                  | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| HP            | Pavilion Notebook           | [10cf947d23](https://linux-hardware.org/?probe=10cf947d23) | May 24, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| HP            | G62                         | [72f8505e51](https://linux-hardware.org/?probe=72f8505e51) | May 20, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [ead418c0a3](https://linux-hardware.org/?probe=ead418c0a3) | May 17, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [8312f6899d](https://linux-hardware.org/?probe=8312f6899d) | May 17, 2021 |
| Dell          | Precision 3551              | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3537               | [3038e4027b](https://linux-hardware.org/?probe=3038e4027b) | May 14, 2021 |
| HP            | Compaq 6735s                | [b3d6b7770a](https://linux-hardware.org/?probe=b3d6b7770a) | May 13, 2021 |
| HP            | Compaq 6735s                | [cb89b8188f](https://linux-hardware.org/?probe=cb89b8188f) | May 13, 2021 |
| HP            | Unknown                     | [d11a5ff11b](https://linux-hardware.org/?probe=d11a5ff11b) | May 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e6848fb30e](https://linux-hardware.org/?probe=e6848fb30e) | May 13, 2021 |
| Notebook      | W65_67SF                    | [342074c2e1](https://linux-hardware.org/?probe=342074c2e1) | May 13, 2021 |
| Notebook      | W65_67SF                    | [54aedd8090](https://linux-hardware.org/?probe=54aedd8090) | May 13, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [643481b28f](https://linux-hardware.org/?probe=643481b28f) | May 10, 2021 |
| MSI           | GF75 Thin 10SCSR            | [d88c558cda](https://linux-hardware.org/?probe=d88c558cda) | May 09, 2021 |
| HP            | Pavilion Notebook           | [7e483f822d](https://linux-hardware.org/?probe=7e483f822d) | May 09, 2021 |
| HP            | Unknown                     | [923ee16061](https://linux-hardware.org/?probe=923ee16061) | May 08, 2021 |
| HP            | Pavilion Notebook           | [993f3384ed](https://linux-hardware.org/?probe=993f3384ed) | May 08, 2021 |
| Notebook      | W65_67SF                    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Sony          | SVE1513R1EB                 | [e87dd3a1c3](https://linux-hardware.org/?probe=e87dd3a1c3) | May 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| Lenovo        | B590 20208                  | [f483fd5a3b](https://linux-hardware.org/?probe=f483fd5a3b) | May 04, 2021 |
| HP            | Compaq 6735s                | [f50dd52975](https://linux-hardware.org/?probe=f50dd52975) | May 03, 2021 |
| Unknown       | Unknown                     | [6f9d6686f3](https://linux-hardware.org/?probe=6f9d6686f3) | May 03, 2021 |
| HP            | Unknown                     | [3b8a91fb03](https://linux-hardware.org/?probe=3b8a91fb03) | May 03, 2021 |
| HP            | Pavilion Notebook           | [79a8f7d7d8](https://linux-hardware.org/?probe=79a8f7d7d8) | May 03, 2021 |
| Apple         | MacBookPro8,1               | [ad00f41e81](https://linux-hardware.org/?probe=ad00f41e81) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | Pavilion Notebook           | [5feda7dcc9](https://linux-hardware.org/?probe=5feda7dcc9) | May 02, 2021 |
| HP            | G62                         | [327a8383cf](https://linux-hardware.org/?probe=327a8383cf) | Apr 30, 2021 |
| HP            | G62                         | [d2eaf7d20f](https://linux-hardware.org/?probe=d2eaf7d20f) | Apr 30, 2021 |
| Acer          | AO756                       | [f398615a01](https://linux-hardware.org/?probe=f398615a01) | Apr 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | G3 3590                     | [5fe47837ac](https://linux-hardware.org/?probe=5fe47837ac) | Apr 19, 2021 |
| Toshiba       | Satellite C850D-119         | [7c519e9719](https://linux-hardware.org/?probe=7c519e9719) | Apr 17, 2021 |
| Google        | Coral                       | [d0fef96a1b](https://linux-hardware.org/?probe=d0fef96a1b) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Acer          | Predator G3-571             | [2db50fb736](https://linux-hardware.org/?probe=2db50fb736) | Apr 12, 2021 |
| HP            | 255 G1                      | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | 255 G8 Notebook PC          | [fd8afa6f02](https://linux-hardware.org/?probe=fd8afa6f02) | Apr 11, 2021 |
| HP            | 255 G8 Notebook PC          | [166de8c643](https://linux-hardware.org/?probe=166de8c643) | Apr 11, 2021 |
| Hampoo        | Cherry Trail CR V200        | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| Toshiba       | Satellite C850D-119         | [743700573c](https://linux-hardware.org/?probe=743700573c) | Apr 04, 2021 |
| MSI           | GF75 Thin 10SCSR            | [4c5b57df0f](https://linux-hardware.org/?probe=4c5b57df0f) | Apr 03, 2021 |
| Acer          | Aspire A315-51              | [a6ad1251de](https://linux-hardware.org/?probe=a6ad1251de) | Mar 30, 2021 |
| Toshiba       | Satellite L500              | [d11d1f9916](https://linux-hardware.org/?probe=d11d1f9916) | Mar 28, 2021 |
| Quest         | GTN1408                     | [e0a15c69a8](https://linux-hardware.org/?probe=e0a15c69a8) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Dell          | Latitude D530               | [bd67bc09cd](https://linux-hardware.org/?probe=bd67bc09cd) | Mar 22, 2021 |
| Acer          | Aspire 5750G                | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| ASUSTek       | X556UQK                     | [67d33fc829](https://linux-hardware.org/?probe=67d33fc829) | Mar 19, 2021 |
| ASUSTek       | N552VX                      | [79120776d5](https://linux-hardware.org/?probe=79120776d5) | Mar 14, 2021 |
| ASUSTek       | N552VX                      | [2bb101d8ca](https://linux-hardware.org/?probe=2bb101d8ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| Teclast       | F15                         | [2a9e97f18c](https://linux-hardware.org/?probe=2a9e97f18c) | Mar 10, 2021 |
| HP            | Notebook                    | [26fdd1f108](https://linux-hardware.org/?probe=26fdd1f108) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Acer          | Aspire E5-771G              | [693347465d](https://linux-hardware.org/?probe=693347465d) | Mar 06, 2021 |
| Info Quest... | GTN1408                     | [571eedb776](https://linux-hardware.org/?probe=571eedb776) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| Dell          | Latitude E6400              | [ebe53e8b99](https://linux-hardware.org/?probe=ebe53e8b99) | Feb 28, 2021 |
| Dell          | Inspiron 5567               | [e2ede83088](https://linux-hardware.org/?probe=e2ede83088) | Feb 27, 2021 |
| Dell          | Inspiron 5567               | [951acd6af9](https://linux-hardware.org/?probe=951acd6af9) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [cada48fb79](https://linux-hardware.org/?probe=cada48fb79) | Feb 27, 2021 |
| ASUSTek       | UX305CA                     | [65b536ca2f](https://linux-hardware.org/?probe=65b536ca2f) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c501aa1f72](https://linux-hardware.org/?probe=c501aa1f72) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| Dell          | Latitude E6400              | [256426a815](https://linux-hardware.org/?probe=256426a815) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | Pavilion AB7                | [410cf90e15](https://linux-hardware.org/?probe=410cf90e15) | Feb 20, 2021 |
| Fujitsu       | LIFEBOOK NH570              | [9b2fc1e55f](https://linux-hardware.org/?probe=9b2fc1e55f) | Feb 19, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| HP            | Laptop 15-db0xxx            | [9e831f773a](https://linux-hardware.org/?probe=9e831f773a) | Feb 17, 2021 |
| Dell          | Studio 1557                 | [bf361a7ed3](https://linux-hardware.org/?probe=bf361a7ed3) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Dell          | Precision M6400             | [2bd1a24330](https://linux-hardware.org/?probe=2bd1a24330) | Feb 14, 2021 |
| HP            | ProBook 450 G5              | [3e6fa8f362](https://linux-hardware.org/?probe=3e6fa8f362) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| Teclast       | F15                         | [1c7d49b0b0](https://linux-hardware.org/?probe=1c7d49b0b0) | Feb 13, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [654141e59d](https://linux-hardware.org/?probe=654141e59d) | Feb 13, 2021 |
| HP            | G62                         | [efd6ef9818](https://linux-hardware.org/?probe=efd6ef9818) | Feb 12, 2021 |
| Fujitsu Si... | AMILO Li 1818               | [68c7aa1fa1](https://linux-hardware.org/?probe=68c7aa1fa1) | Feb 09, 2021 |
| Lenovo        | G510 20238                  | [0022cd41e5](https://linux-hardware.org/?probe=0022cd41e5) | Feb 06, 2021 |
| Lenovo        | Y50-70 20378                | [a95bc37d1f](https://linux-hardware.org/?probe=a95bc37d1f) | Feb 03, 2021 |
| HP            | G62                         | [273bf04457](https://linux-hardware.org/?probe=273bf04457) | Feb 03, 2021 |
| HP            | G62                         | [a74ecdb45c](https://linux-hardware.org/?probe=a74ecdb45c) | Feb 03, 2021 |
| Lenovo        | G510 20238                  | [fff0e370f8](https://linux-hardware.org/?probe=fff0e370f8) | Feb 01, 2021 |
| Lenovo        | G510 20238                  | [4acc63b6b4](https://linux-hardware.org/?probe=4acc63b6b4) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| HP            | Pavilion Sleekbook 15       | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| Acer          | Aspire A517-51G             | [7b7f7244e6](https://linux-hardware.org/?probe=7b7f7244e6) | Jan 28, 2021 |
| Lenovo        | G510 20238                  | [c53a37fb5a](https://linux-hardware.org/?probe=c53a37fb5a) | Jan 28, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| HP            | Pavilion Notebook           | [ce1a55614c](https://linux-hardware.org/?probe=ce1a55614c) | Jan 28, 2021 |
| HP            | Unknown                     | [b7892094b3](https://linux-hardware.org/?probe=b7892094b3) | Jan 27, 2021 |
| IBM           | ThinkPad T41 2373271        | [71daf2c5b4](https://linux-hardware.org/?probe=71daf2c5b4) | Jan 26, 2021 |
| Fujitsu       | AMILO Pi 3560               | [a54f523eae](https://linux-hardware.org/?probe=a54f523eae) | Jan 26, 2021 |
| HP            | 255 G7 Notebook PC          | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Toshiba       | Satellite L50-B             | [6e7fe8b488](https://linux-hardware.org/?probe=6e7fe8b488) | Jan 18, 2021 |
| Toshiba       | Satellite L50-B             | [df23913572](https://linux-hardware.org/?probe=df23913572) | Jan 18, 2021 |
| HP            | 550                         | [384b3f65ed](https://linux-hardware.org/?probe=384b3f65ed) | Jan 18, 2021 |
| Acer          | Aspire 1410                 | [c7045484b1](https://linux-hardware.org/?probe=c7045484b1) | Jan 16, 2021 |
| Sony          | VPCS11X9E                   | [279fb61afa](https://linux-hardware.org/?probe=279fb61afa) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [a137e1b57f](https://linux-hardware.org/?probe=a137e1b57f) | Jan 11, 2021 |
| Medion        | P6612                       | [5e83afdaae](https://linux-hardware.org/?probe=5e83afdaae) | Jan 11, 2021 |
| Dell          | G3 3579                     | [d48d0d6f85](https://linux-hardware.org/?probe=d48d0d6f85) | Jan 11, 2021 |
| HP            | 550                         | [10da4607b5](https://linux-hardware.org/?probe=10da4607b5) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| Dell          | Precision 3551              | [1f3d433e7b](https://linux-hardware.org/?probe=1f3d433e7b) | Jan 07, 2021 |
| Dell          | Precision 3551              | [b9869afb9a](https://linux-hardware.org/?probe=b9869afb9a) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [2040f17b4e](https://linux-hardware.org/?probe=2040f17b4e) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [7758717ed0](https://linux-hardware.org/?probe=7758717ed0) | Jan 07, 2021 |
| Unknown       | Unknown                     | [394c90d235](https://linux-hardware.org/?probe=394c90d235) | Jan 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [010507185c](https://linux-hardware.org/?probe=010507185c) | Jan 03, 2021 |
| HP            | G62                         | [26fedb2989](https://linux-hardware.org/?probe=26fedb2989) | Jan 03, 2021 |
| Sony          | VGN-CR11S_W                 | [e7b02a15dc](https://linux-hardware.org/?probe=e7b02a15dc) | Dec 30, 2020 |
| Sony          | VGN-CR11S_W                 | [3bbbfe0bd8](https://linux-hardware.org/?probe=3bbbfe0bd8) | Dec 30, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [33e1b7b962](https://linux-hardware.org/?probe=33e1b7b962) | Dec 28, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [7463092751](https://linux-hardware.org/?probe=7463092751) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [502b2847a6](https://linux-hardware.org/?probe=502b2847a6) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [29cadd906c](https://linux-hardware.org/?probe=29cadd906c) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | Inspiron 5567               | [4bed00686e](https://linux-hardware.org/?probe=4bed00686e) | Dec 27, 2020 |
| Lenovo        | 3000 G530 444624G           | [34e6d98329](https://linux-hardware.org/?probe=34e6d98329) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| HP            | Pavilion dv7                | [cc13d41ddd](https://linux-hardware.org/?probe=cc13d41ddd) | Dec 25, 2020 |
| Dell          | XPS 15 7590                 | [2974690eda](https://linux-hardware.org/?probe=2974690eda) | Dec 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Dell          | G3 3590                     | [aaea8a972b](https://linux-hardware.org/?probe=aaea8a972b) | Dec 23, 2020 |
| HP            | Laptop 15-db0xxx            | [fe62a9556e](https://linux-hardware.org/?probe=fe62a9556e) | Dec 21, 2020 |
| HP            | Laptop 15-db0xxx            | [08f4092908](https://linux-hardware.org/?probe=08f4092908) | Dec 21, 2020 |
| HP            | Pavilion Notebook           | [5e08a85ebc](https://linux-hardware.org/?probe=5e08a85ebc) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | [508111c39d](https://linux-hardware.org/?probe=508111c39d) | Dec 20, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Lenovo        | IdeaPad S210 Touch 20257    | [faacb1a39b](https://linux-hardware.org/?probe=faacb1a39b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X220 4291W3B       | [0cb7ed54d1](https://linux-hardware.org/?probe=0cb7ed54d1) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Dell          | Latitude D520               | [7f5d3e9a40](https://linux-hardware.org/?probe=7f5d3e9a40) | Dec 19, 2020 |
| Lenovo        | 3000 G530 444624G           | [fb187878c5](https://linux-hardware.org/?probe=fb187878c5) | Dec 16, 2020 |
| ASUSTek       | X550CC                      | [d8723f48ef](https://linux-hardware.org/?probe=d8723f48ef) | Dec 15, 2020 |
| Sony          | VPCCB2S1E                   | [dadaeb0257](https://linux-hardware.org/?probe=dadaeb0257) | Dec 14, 2020 |
| Sony          | VPCCB2S1E                   | [b08942a95c](https://linux-hardware.org/?probe=b08942a95c) | Dec 14, 2020 |
| Sony          | VGN-CR11S_W                 | [96a49970af](https://linux-hardware.org/?probe=96a49970af) | Dec 11, 2020 |
| Lenovo        | G50-80 80L0                 | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Sony          | VGN-CR11S_W                 | [9f07e6181c](https://linux-hardware.org/?probe=9f07e6181c) | Dec 10, 2020 |
| HP            | OMEN by HP Laptop           | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7becb585e](https://linux-hardware.org/?probe=b7becb585e) | Dec 08, 2020 |
| Intel         | CAPELL VALLEY CRB           | [59d2069d40](https://linux-hardware.org/?probe=59d2069d40) | Dec 07, 2020 |
| Intel         | CAPELL VALLEY CRB           | [ce350750e3](https://linux-hardware.org/?probe=ce350750e3) | Dec 05, 2020 |
| Toshiba       | Satellite C850D-119         | [4a0f2ef22e](https://linux-hardware.org/?probe=4a0f2ef22e) | Dec 05, 2020 |
| HP            | Pavilion dv7                | [ea3cf2d030](https://linux-hardware.org/?probe=ea3cf2d030) | Dec 04, 2020 |
| Lenovo        | G70-35 80Q5                 | [455f011c08](https://linux-hardware.org/?probe=455f011c08) | Dec 03, 2020 |
| ASUSTek       | X556UQK                     | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [09b180815e](https://linux-hardware.org/?probe=09b180815e) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Lenovo        | G70-35 80Q5                 | [23ee81bd5e](https://linux-hardware.org/?probe=23ee81bd5e) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Sony          | VPCW12J1E                   | [7f54f3a6f0](https://linux-hardware.org/?probe=7f54f3a6f0) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Acer          | Predator G5-793             | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| Acer          | Aspire 5738                 | [c34c324fc5](https://linux-hardware.org/?probe=c34c324fc5) | Nov 28, 2020 |
| HP            | EliteBook 850 G5            | [e261ebbf0e](https://linux-hardware.org/?probe=e261ebbf0e) | Nov 26, 2020 |
| Toshiba       | Satellite P500              | [25e5577463](https://linux-hardware.org/?probe=25e5577463) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| Dell          | Inspiron 3537               | [0bc23c46e1](https://linux-hardware.org/?probe=0bc23c46e1) | Nov 23, 2020 |
| Acer          | Aspire 9500                 | [14c016a2f9](https://linux-hardware.org/?probe=14c016a2f9) | Nov 22, 2020 |
| HP            | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [00c9bbbec5](https://linux-hardware.org/?probe=00c9bbbec5) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [baae1bd1ef](https://linux-hardware.org/?probe=baae1bd1ef) | Nov 20, 2020 |
| HP            | 14                          | [99583d854a](https://linux-hardware.org/?probe=99583d854a) | Nov 20, 2020 |
| Dell          | Inspiron 3542               | [6647cfca50](https://linux-hardware.org/?probe=6647cfca50) | Nov 18, 2020 |
| HP            | Pavilion g6                 | [4a521aad50](https://linux-hardware.org/?probe=4a521aad50) | Nov 16, 2020 |
| Clevo         | W55xEU                      | [932e7d8f27](https://linux-hardware.org/?probe=932e7d8f27) | Nov 16, 2020 |
| HP            | Laptop 17-ca1xxx            | [43e0f99b97](https://linux-hardware.org/?probe=43e0f99b97) | Nov 14, 2020 |
| HUAWEI        | KLVL-WXX9                   | [bd2dcac2ac](https://linux-hardware.org/?probe=bd2dcac2ac) | Nov 12, 2020 |
| Fujitsu Si... | AMILO Li1705                | [3233bbc0ec](https://linux-hardware.org/?probe=3233bbc0ec) | Nov 12, 2020 |
| MSI           | GE70 2OC\2OE                | [ba1376cdb9](https://linux-hardware.org/?probe=ba1376cdb9) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [0c0bf4e794](https://linux-hardware.org/?probe=0c0bf4e794) | Nov 11, 2020 |
| Dell          | Inspiron 3593               | [005da6030a](https://linux-hardware.org/?probe=005da6030a) | Nov 11, 2020 |
| ASUSTek       | X540LJ                      | [3a7e7932f2](https://linux-hardware.org/?probe=3a7e7932f2) | Nov 10, 2020 |
| Dell          | Latitude 7400               | [95aa8c5f82](https://linux-hardware.org/?probe=95aa8c5f82) | Nov 04, 2020 |
| HP            | Pavilion Notebook           | [5b2b100711](https://linux-hardware.org/?probe=5b2b100711) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b30631ff4c](https://linux-hardware.org/?probe=b30631ff4c) | Nov 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5a78c67deb](https://linux-hardware.org/?probe=5a78c67deb) | Oct 30, 2020 |
| HP            | 15                          | [8ebe037b8f](https://linux-hardware.org/?probe=8ebe037b8f) | Oct 29, 2020 |
| Toshiba       | Satellite C850D-119         | [493e216eea](https://linux-hardware.org/?probe=493e216eea) | Oct 25, 2020 |
| HP            | 255 G1                      | [bfd456834c](https://linux-hardware.org/?probe=bfd456834c) | Oct 24, 2020 |
| Toshiba       | Satellite P200              | [84d2d0d8cf](https://linux-hardware.org/?probe=84d2d0d8cf) | Oct 21, 2020 |
| Toshiba       | Satellite P200              | [932b71224c](https://linux-hardware.org/?probe=932b71224c) | Oct 21, 2020 |
| HP            | Pavilion x2 Detachable      | [b7f2a6ef39](https://linux-hardware.org/?probe=b7f2a6ef39) | Oct 21, 2020 |
| Dell          | XPS L502X                   | [dc6eea4b63](https://linux-hardware.org/?probe=dc6eea4b63) | Oct 17, 2020 |
| Clevo         | M660SE                      | [01a8ac7cd9](https://linux-hardware.org/?probe=01a8ac7cd9) | Oct 14, 2020 |
| HP            | Pavilion Notebook           | [bd93e81149](https://linux-hardware.org/?probe=bd93e81149) | Oct 14, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4974ae8ad2](https://linux-hardware.org/?probe=4974ae8ad2) | Oct 13, 2020 |
| Sony          | VPCCB2S1E                   | [8a80ad4971](https://linux-hardware.org/?probe=8a80ad4971) | Oct 13, 2020 |
| Clevo         | M660SE                      | [9bd883acaa](https://linux-hardware.org/?probe=9bd883acaa) | Oct 12, 2020 |
| Dell          | G3 3590                     | [e710fb7efe](https://linux-hardware.org/?probe=e710fb7efe) | Oct 12, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [941d9edff3](https://linux-hardware.org/?probe=941d9edff3) | Oct 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [33f4f77db5](https://linux-hardware.org/?probe=33f4f77db5) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [8700c3217b](https://linux-hardware.org/?probe=8700c3217b) | Oct 10, 2020 |
| HP            | Notebook                    | [1e6bba57b7](https://linux-hardware.org/?probe=1e6bba57b7) | Oct 09, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [a6569d4074](https://linux-hardware.org/?probe=a6569d4074) | Oct 09, 2020 |
| Acer          | AO531h                      | [af1d7d28cc](https://linux-hardware.org/?probe=af1d7d28cc) | Oct 07, 2020 |
| Acer          | Aspire 5738                 | [f814a33c4c](https://linux-hardware.org/?probe=f814a33c4c) | Oct 07, 2020 |
| HP            | Pavilion g6                 | [c1ff9eb372](https://linux-hardware.org/?probe=c1ff9eb372) | Oct 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2436dcb42a](https://linux-hardware.org/?probe=2436dcb42a) | Oct 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [815070f834](https://linux-hardware.org/?probe=815070f834) | Oct 02, 2020 |
| Lenovo        | ThinkPad E580 20KS006GUK    | [43cd14b799](https://linux-hardware.org/?probe=43cd14b799) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | XPS M1530                   | [dc08069215](https://linux-hardware.org/?probe=dc08069215) | Sep 29, 2020 |
| Sony          | VPCM13M1E                   | [139119fce3](https://linux-hardware.org/?probe=139119fce3) | Sep 28, 2020 |
| Sony          | VPCM13M1E                   | [40da79e9dc](https://linux-hardware.org/?probe=40da79e9dc) | Sep 28, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [f6809ca4e3](https://linux-hardware.org/?probe=f6809ca4e3) | Sep 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [135cb18944](https://linux-hardware.org/?probe=135cb18944) | Sep 26, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | Pavilion g6                 | [7ed6ea1d8e](https://linux-hardware.org/?probe=7ed6ea1d8e) | Sep 24, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [301fab4ca7](https://linux-hardware.org/?probe=301fab4ca7) | Sep 17, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Toshiba       | Satellite L750              | [04b3b93310](https://linux-hardware.org/?probe=04b3b93310) | Sep 13, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [9149c8b59c](https://linux-hardware.org/?probe=9149c8b59c) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [d549f8665d](https://linux-hardware.org/?probe=d549f8665d) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [41a8975f07](https://linux-hardware.org/?probe=41a8975f07) | Sep 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | Aspire A315-31              | [118b474cc3](https://linux-hardware.org/?probe=118b474cc3) | Sep 06, 2020 |
| Dell          | Latitude 5400               | [1ae84c03c5](https://linux-hardware.org/?probe=1ae84c03c5) | Sep 02, 2020 |
| HP            | 15                          | [5b582297ed](https://linux-hardware.org/?probe=5b582297ed) | Sep 02, 2020 |
| Dell          | Inspiron 7720               | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| HP            | Compaq 6735s                | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| Dell          | Inspiron 7559               | [85dd645b39](https://linux-hardware.org/?probe=85dd645b39) | Aug 16, 2020 |
| Lenovo        | V145-15AST 81MT             | [8b03ada262](https://linux-hardware.org/?probe=8b03ada262) | Aug 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [a9262f65c0](https://linux-hardware.org/?probe=a9262f65c0) | Aug 15, 2020 |
| Dell          | Vostro 5481                 | [fc1a36f64d](https://linux-hardware.org/?probe=fc1a36f64d) | Aug 13, 2020 |
| Toshiba       | Satellite P200D             | [9bb94d56ed](https://linux-hardware.org/?probe=9bb94d56ed) | Aug 06, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [20185e7b49](https://linux-hardware.org/?probe=20185e7b49) | Aug 04, 2020 |
| Hampoo        | Cherry Trail CR V200        | [62925bc138](https://linux-hardware.org/?probe=62925bc138) | Aug 01, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [50226c4586](https://linux-hardware.org/?probe=50226c4586) | Jul 30, 2020 |
| Dell          | Inspiron 5567               | [25489b5aa4](https://linux-hardware.org/?probe=25489b5aa4) | Jul 29, 2020 |
| Dell          | Inspiron 5567               | [d690a1848c](https://linux-hardware.org/?probe=d690a1848c) | Jul 29, 2020 |
| HP            | 250 G6 Notebook PC          | [7b6b423b68](https://linux-hardware.org/?probe=7b6b423b68) | Jul 23, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [192dd297bd](https://linux-hardware.org/?probe=192dd297bd) | Jul 22, 2020 |
| Dell          | G3 3590                     | [0bfa0fdeb2](https://linux-hardware.org/?probe=0bfa0fdeb2) | Jul 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [b73a34930b](https://linux-hardware.org/?probe=b73a34930b) | Jul 21, 2020 |
| HP            | ElitePad 1000 G2            | [58738fe100](https://linux-hardware.org/?probe=58738fe100) | Jul 17, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| Dell          | Inspiron 3543               | [39df7edbea](https://linux-hardware.org/?probe=39df7edbea) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [717049c98f](https://linux-hardware.org/?probe=717049c98f) | Jul 07, 2020 |
| Acer          | Aspire A315-53G             | [b6506c9a23](https://linux-hardware.org/?probe=b6506c9a23) | Jul 07, 2020 |
| Fujitsu       | LIFEBOOK E751               | [6f4a149255](https://linux-hardware.org/?probe=6f4a149255) | Jul 02, 2020 |
| Lenovo        | G40-30 80FY                 | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Notebook      | NJ50_70CU                   | [5c9684cdab](https://linux-hardware.org/?probe=5c9684cdab) | Jun 29, 2020 |
| Lenovo        | G40-30 80FY                 | [157e79f788](https://linux-hardware.org/?probe=157e79f788) | Jun 28, 2020 |
| Lenovo        | G40-30 80FY                 | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| Notebook      | NJ50_70CU                   | [427a02d3bc](https://linux-hardware.org/?probe=427a02d3bc) | Jun 27, 2020 |
| Dell          | Inspiron 15-3552            | [9b7f2ae65e](https://linux-hardware.org/?probe=9b7f2ae65e) | Jun 25, 2020 |
| HP            | ZBook 15                    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| HP            | ProBook 6560b               | [5db87fcc49](https://linux-hardware.org/?probe=5db87fcc49) | Jun 24, 2020 |
| HP            | ProBook 6560b               | [9a78de8ed6](https://linux-hardware.org/?probe=9a78de8ed6) | Jun 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [31b59ae094](https://linux-hardware.org/?probe=31b59ae094) | Jun 24, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [68f2706e1c](https://linux-hardware.org/?probe=68f2706e1c) | Jun 22, 2020 |
| Sony          | VGN-N31Z_W                  | [9dbeef64ee](https://linux-hardware.org/?probe=9dbeef64ee) | Jun 22, 2020 |
| ASUSTek       | K52JU                       | [38a9288b85](https://linux-hardware.org/?probe=38a9288b85) | Jun 21, 2020 |
| ASUSTek       | K52JU                       | [a07e2655ec](https://linux-hardware.org/?probe=a07e2655ec) | Jun 21, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b388cd0a96](https://linux-hardware.org/?probe=b388cd0a96) | Jun 20, 2020 |
| ASUSTek       | X556UQK                     | [c6c57358a6](https://linux-hardware.org/?probe=c6c57358a6) | Jun 18, 2020 |
| Toshiba       | Satellite A300D             | [872199f2c5](https://linux-hardware.org/?probe=872199f2c5) | Jun 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eaccc0249f](https://linux-hardware.org/?probe=eaccc0249f) | Jun 17, 2020 |
| Toshiba       | Satellite A300D             | [8e0f23dc31](https://linux-hardware.org/?probe=8e0f23dc31) | Jun 16, 2020 |
| HP            | 15                          | [7644a7713f](https://linux-hardware.org/?probe=7644a7713f) | Jun 16, 2020 |
| Acer          | Aspire 3935                 | [3957942dc1](https://linux-hardware.org/?probe=3957942dc1) | Jun 10, 2020 |
| HP            | Pavilion dv7                | [27d5196b74](https://linux-hardware.org/?probe=27d5196b74) | May 30, 2020 |
| Lenovo        | V330-14ARR 81B1             | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| HP            | 255 G7 Notebook PC          | [e4bba31386](https://linux-hardware.org/?probe=e4bba31386) | May 29, 2020 |
| HP            | 255 G7 Notebook PC          | [bd6ea57435](https://linux-hardware.org/?probe=bd6ea57435) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [2b4ff1e9b6](https://linux-hardware.org/?probe=2b4ff1e9b6) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [8e54bbb3e2](https://linux-hardware.org/?probe=8e54bbb3e2) | May 29, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [9975194681](https://linux-hardware.org/?probe=9975194681) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [a8a351b9b3](https://linux-hardware.org/?probe=a8a351b9b3) | May 28, 2020 |
| HP            | Pavilion g6                 | [1fd4402991](https://linux-hardware.org/?probe=1fd4402991) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [15696a9c46](https://linux-hardware.org/?probe=15696a9c46) | May 28, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [0d35855885](https://linux-hardware.org/?probe=0d35855885) | May 25, 2020 |
| Lenovo        | ThinkPad T580 20L90023RT    | [a7b6c79ac0](https://linux-hardware.org/?probe=a7b6c79ac0) | May 24, 2020 |
| HP            | Pavilion dv7                | [9d4e0753f6](https://linux-hardware.org/?probe=9d4e0753f6) | May 23, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [43e3fadb97](https://linux-hardware.org/?probe=43e3fadb97) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Dell          | Latitude E6410              | [7c8e49e14c](https://linux-hardware.org/?probe=7c8e49e14c) | May 22, 2020 |
| HP            | Unknown                     | [0be27afc58](https://linux-hardware.org/?probe=0be27afc58) | May 22, 2020 |
| HP            | Compaq Presario C700        | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Pavilion g6                 | [31a778de5b](https://linux-hardware.org/?probe=31a778de5b) | May 18, 2020 |
| HP            | Pavilion g6                 | [68952aafce](https://linux-hardware.org/?probe=68952aafce) | May 18, 2020 |
| HP            | Pavilion g6                 | [619ed13a7f](https://linux-hardware.org/?probe=619ed13a7f) | May 18, 2020 |
| HP            | Pavilion g6                 | [24f89ac1d4](https://linux-hardware.org/?probe=24f89ac1d4) | May 18, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [fa51e14d38](https://linux-hardware.org/?probe=fa51e14d38) | May 17, 2020 |
| Intel         | CAPELL VALLEY CRB           | [67b7ec6a84](https://linux-hardware.org/?probe=67b7ec6a84) | May 17, 2020 |
| HP            | Pavilion g6                 | [de917a6cdc](https://linux-hardware.org/?probe=de917a6cdc) | May 17, 2020 |
| HP            | Pavilion g6                 | [f5334be644](https://linux-hardware.org/?probe=f5334be644) | May 17, 2020 |
| Notebook      | W65_67SH                    | [497422c9fc](https://linux-hardware.org/?probe=497422c9fc) | May 16, 2020 |
| Notebook      | W65_67SH                    | [9559aff349](https://linux-hardware.org/?probe=9559aff349) | May 16, 2020 |
| HP            | Pavilion Notebook           | [01b6eef865](https://linux-hardware.org/?probe=01b6eef865) | May 14, 2020 |
| HP            | Pavilion Notebook           | [1cb7e4e70a](https://linux-hardware.org/?probe=1cb7e4e70a) | May 13, 2020 |
| HP            | Pavilion Notebook           | [75714d5542](https://linux-hardware.org/?probe=75714d5542) | May 13, 2020 |
| Dell          | Latitude E5410              | [b51e124387](https://linux-hardware.org/?probe=b51e124387) | May 13, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [d225d411f9](https://linux-hardware.org/?probe=d225d411f9) | May 13, 2020 |
| HP            | 250 G4                      | [adc4529aff](https://linux-hardware.org/?probe=adc4529aff) | May 12, 2020 |
| Lenovo        | ThinkPad X230 23245D4       | [740b68266b](https://linux-hardware.org/?probe=740b68266b) | May 12, 2020 |
| Dell          | G3 3590                     | [85e10bcd60](https://linux-hardware.org/?probe=85e10bcd60) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [bd8e53be4e](https://linux-hardware.org/?probe=bd8e53be4e) | May 11, 2020 |
| HP            | Pavilion Notebook           | [70466d71d3](https://linux-hardware.org/?probe=70466d71d3) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| HP            | G5000 (GF767EA#B1A)         | [39fd61954e](https://linux-hardware.org/?probe=39fd61954e) | May 10, 2020 |
| Dell          | Inspiron 3542               | [231fda4e89](https://linux-hardware.org/?probe=231fda4e89) | May 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS0110B    | [9da7641ead](https://linux-hardware.org/?probe=9da7641ead) | May 07, 2020 |
| Pegatron      | D15R                        | [9b128d4d23](https://linux-hardware.org/?probe=9b128d4d23) | May 05, 2020 |
| Pegatron      | D15R                        | [25cf2e91d8](https://linux-hardware.org/?probe=25cf2e91d8) | May 05, 2020 |
| Sony          | VGN-CR590E                  | [cb2c7466cc](https://linux-hardware.org/?probe=cb2c7466cc) | May 04, 2020 |
| Acer          | Aspire 5100                 | [0b4ce05d4b](https://linux-hardware.org/?probe=0b4ce05d4b) | May 03, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | [f77cb5d716](https://linux-hardware.org/?probe=f77cb5d716) | Apr 30, 2020 |
| Lenovo        | G580 20150                  | [158ef386df](https://linux-hardware.org/?probe=158ef386df) | Apr 29, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7deee5c6f4](https://linux-hardware.org/?probe=7deee5c6f4) | Apr 28, 2020 |
| HP            | ProBook 6560b               | [f7e0abeaf2](https://linux-hardware.org/?probe=f7e0abeaf2) | Apr 27, 2020 |
| HP            | Pavilion g6                 | [166222e5c9](https://linux-hardware.org/?probe=166222e5c9) | Apr 26, 2020 |
| HP            | Pavilion g6                 | [e5e0d5140e](https://linux-hardware.org/?probe=e5e0d5140e) | Apr 25, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6770cf29bb](https://linux-hardware.org/?probe=6770cf29bb) | Apr 25, 2020 |
| Sony          | VGN-FE41E                   | [1d8645be3f](https://linux-hardware.org/?probe=1d8645be3f) | Apr 24, 2020 |
| Apple         | MacBook5,2                  | [33530c3091](https://linux-hardware.org/?probe=33530c3091) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | [b6d0779fb0](https://linux-hardware.org/?probe=b6d0779fb0) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | [fbb9346ad4](https://linux-hardware.org/?probe=fbb9346ad4) | Apr 21, 2020 |
| Toshiba       | Satellite L450D             | [7f26f2d180](https://linux-hardware.org/?probe=7f26f2d180) | Apr 20, 2020 |
| HP            | Unknown                     | [6cd3c0a036](https://linux-hardware.org/?probe=6cd3c0a036) | Apr 19, 2020 |
| HP            | Unknown                     | [7a5b60f20c](https://linux-hardware.org/?probe=7a5b60f20c) | Apr 19, 2020 |
| HP            | Unknown                     | [97ca26d3d7](https://linux-hardware.org/?probe=97ca26d3d7) | Apr 19, 2020 |
| Toshiba       | Satellite L450D             | [f541e27fef](https://linux-hardware.org/?probe=f541e27fef) | Apr 14, 2020 |
| Toshiba       | Satellite L450D             | [dd6245c9f1](https://linux-hardware.org/?probe=dd6245c9f1) | Apr 14, 2020 |
| HP            | Compaq 6710b (GR680EA#B1... | [fb9d604f9d](https://linux-hardware.org/?probe=fb9d604f9d) | Apr 13, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [85350a43d3](https://linux-hardware.org/?probe=85350a43d3) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0fb509f423](https://linux-hardware.org/?probe=0fb509f423) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Lenovo        | G510 20238                  | [72f97922cc](https://linux-hardware.org/?probe=72f97922cc) | Apr 09, 2020 |
| Lenovo        | G510 20238                  | [126766dead](https://linux-hardware.org/?probe=126766dead) | Apr 09, 2020 |
| Dell          | Inspiron 5558               | [9ecfa320c9](https://linux-hardware.org/?probe=9ecfa320c9) | Apr 08, 2020 |
| Dell          | G3 3590                     | [9466a720ff](https://linux-hardware.org/?probe=9466a720ff) | Apr 07, 2020 |
| HP            | Pavilion dv7                | [88ff5b44b7](https://linux-hardware.org/?probe=88ff5b44b7) | Apr 07, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| HP            | Presario CQ62               | [3821156090](https://linux-hardware.org/?probe=3821156090) | Apr 06, 2020 |
| ASUSTek       | X540LJ                      | [3818f5dd9e](https://linux-hardware.org/?probe=3818f5dd9e) | Apr 05, 2020 |
| Dell          | Inspiron 1750               | [3b7ede7bc6](https://linux-hardware.org/?probe=3b7ede7bc6) | Apr 05, 2020 |
| HP            | Pavilion dv7                | [88debf96e8](https://linux-hardware.org/?probe=88debf96e8) | Apr 04, 2020 |
| HP            | Pavilion dv7                | [a7adf60c3c](https://linux-hardware.org/?probe=a7adf60c3c) | Apr 04, 2020 |
| HP            | Pavilion dv7                | [2287c81b7d](https://linux-hardware.org/?probe=2287c81b7d) | Apr 04, 2020 |
| HP            | Pavilion dv7                | [d64ce74086](https://linux-hardware.org/?probe=d64ce74086) | Apr 04, 2020 |
| Sony          | VGN-CR590E                  | [121394a15c](https://linux-hardware.org/?probe=121394a15c) | Apr 03, 2020 |
| Dell          | G3 3590                     | [795e283ee9](https://linux-hardware.org/?probe=795e283ee9) | Apr 01, 2020 |
| E-shop.gr     | Innovator M1589             | [be146dfa67](https://linux-hardware.org/?probe=be146dfa67) | Mar 31, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [9c2eef7d10](https://linux-hardware.org/?probe=9c2eef7d10) | Mar 31, 2020 |
| Lenovo        | G50-70 20351                | [199d2287e2](https://linux-hardware.org/?probe=199d2287e2) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Apple         | MacBook1,1                  | [27d210b0e2](https://linux-hardware.org/?probe=27d210b0e2) | Mar 30, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b9f6bf0ad4](https://linux-hardware.org/?probe=b9f6bf0ad4) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| Dell          | G3 3590                     | [6b8e66d086](https://linux-hardware.org/?probe=6b8e66d086) | Mar 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [220c3c60b0](https://linux-hardware.org/?probe=220c3c60b0) | Mar 28, 2020 |
| Dell          | Inspiron 3543               | [ae5dbcbc69](https://linux-hardware.org/?probe=ae5dbcbc69) | Mar 27, 2020 |
| Dell          | Inspiron 3543               | [5d80035b8d](https://linux-hardware.org/?probe=5d80035b8d) | Mar 27, 2020 |
| Dell          | G3 3590                     | [fb1cee5bb2](https://linux-hardware.org/?probe=fb1cee5bb2) | Mar 27, 2020 |
| HP            | Compaq Mini 110c-1000       | [ba8efb8d78](https://linux-hardware.org/?probe=ba8efb8d78) | Mar 26, 2020 |
| Lenovo        | G50-70 20351                | [4fff19bf83](https://linux-hardware.org/?probe=4fff19bf83) | Mar 24, 2020 |
| Lenovo        | G50-70 20351                | [d361a95cae](https://linux-hardware.org/?probe=d361a95cae) | Mar 24, 2020 |
| Dell          | G3 3590                     | [68c4b5c3e4](https://linux-hardware.org/?probe=68c4b5c3e4) | Mar 24, 2020 |
| Dell          | G3 3590                     | [05edd2dcde](https://linux-hardware.org/?probe=05edd2dcde) | Mar 24, 2020 |
| Dell          | G3 3590                     | [ff14d5222d](https://linux-hardware.org/?probe=ff14d5222d) | Mar 24, 2020 |
| Sony          | VGN-NR11Z_S                 | [69fb7aa4d4](https://linux-hardware.org/?probe=69fb7aa4d4) | Mar 23, 2020 |
| HP            | ProBook 6560b               | [40d00a5fb1](https://linux-hardware.org/?probe=40d00a5fb1) | Mar 16, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | [a6b3d80476](https://linux-hardware.org/?probe=a6b3d80476) | Mar 11, 2020 |
| Lenovo        | ThinkPad T470 20HD000LUK    | [9c47172207](https://linux-hardware.org/?probe=9c47172207) | Mar 08, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | [ef4dbc4e8b](https://linux-hardware.org/?probe=ef4dbc4e8b) | Mar 06, 2020 |
| Lenovo        | ThinkPad T420 4236Q23       | [65d50c61eb](https://linux-hardware.org/?probe=65d50c61eb) | Mar 05, 2020 |
| Acer          | Aspire A315-53G             | [150b9c6b6d](https://linux-hardware.org/?probe=150b9c6b6d) | Feb 25, 2020 |
| Compal        | Unknown                     | [56b05900a0](https://linux-hardware.org/?probe=56b05900a0) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | [270e63cceb](https://linux-hardware.org/?probe=270e63cceb) | Feb 23, 2020 |
| Acer          | Aspire A315-51              | [77543de863](https://linux-hardware.org/?probe=77543de863) | Feb 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f3fe28b459](https://linux-hardware.org/?probe=f3fe28b459) | Feb 19, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [6beff5886c](https://linux-hardware.org/?probe=6beff5886c) | Feb 19, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [55a53b12ce](https://linux-hardware.org/?probe=55a53b12ce) | Feb 15, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [745a30749e](https://linux-hardware.org/?probe=745a30749e) | Feb 15, 2020 |
| HP            | EliteBook 8460p             | [b57c6ec496](https://linux-hardware.org/?probe=b57c6ec496) | Feb 12, 2020 |
| Chuwi         | HeroBook                    | [c63663b03e](https://linux-hardware.org/?probe=c63663b03e) | Feb 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b350a4e79](https://linux-hardware.org/?probe=7b350a4e79) | Feb 07, 2020 |
| HP            | 15                          | [16b52341f5](https://linux-hardware.org/?probe=16b52341f5) | Feb 04, 2020 |
| Acer          | TravelMate 2490             | [a93e1d86a8](https://linux-hardware.org/?probe=a93e1d86a8) | Jan 27, 2020 |
| VERO          | K147                        | [9f10ca8308](https://linux-hardware.org/?probe=9f10ca8308) | Jan 26, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMH    | [3a02dced23](https://linux-hardware.org/?probe=3a02dced23) | Jan 14, 2020 |
| Lenovo        | ThinkPad L412 0585W28       | [8ba74bb2b0](https://linux-hardware.org/?probe=8ba74bb2b0) | Jan 13, 2020 |
| Sony          | VGN-FW21M                   | [cda530b21f](https://linux-hardware.org/?probe=cda530b21f) | Jan 12, 2020 |
| HP            | 650                         | [41d463f623](https://linux-hardware.org/?probe=41d463f623) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [b883b5c1af](https://linux-hardware.org/?probe=b883b5c1af) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [76920bc1b7](https://linux-hardware.org/?probe=76920bc1b7) | Jan 03, 2020 |
| Acer          | Aspire 5755G                | [99f3d96106](https://linux-hardware.org/?probe=99f3d96106) | Dec 31, 2019 |
| HP            | 255 G6 Notebook PC          | [4d572c7a12](https://linux-hardware.org/?probe=4d572c7a12) | Dec 31, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [1a90ac4588](https://linux-hardware.org/?probe=1a90ac4588) | Dec 26, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [966b8a2a9a](https://linux-hardware.org/?probe=966b8a2a9a) | Dec 23, 2019 |
| ASUSTek       | X551MA                      | [cc9b263062](https://linux-hardware.org/?probe=cc9b263062) | Dec 23, 2019 |
| HP            | EliteBook 8440p             | [d1c32bf428](https://linux-hardware.org/?probe=d1c32bf428) | Dec 21, 2019 |
| HP            | EliteBook 8460p             | [00c6afae23](https://linux-hardware.org/?probe=00c6afae23) | Dec 19, 2019 |
| Acer          | Aspire A315-31              | [702d379dd6](https://linux-hardware.org/?probe=702d379dd6) | Dec 17, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [6498ff99ee](https://linux-hardware.org/?probe=6498ff99ee) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [b27320fd81](https://linux-hardware.org/?probe=b27320fd81) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [38e30cfe23](https://linux-hardware.org/?probe=38e30cfe23) | Dec 14, 2019 |
| Insyde        | CherryTrail                 | [deeda709d2](https://linux-hardware.org/?probe=deeda709d2) | Dec 07, 2019 |
| Insyde        | CherryTrail                 | [81201a03c1](https://linux-hardware.org/?probe=81201a03c1) | Dec 07, 2019 |
| HP            | 650                         | [1433fef646](https://linux-hardware.org/?probe=1433fef646) | Dec 03, 2019 |
| HP            | 650                         | [2a96c9ca75](https://linux-hardware.org/?probe=2a96c9ca75) | Dec 03, 2019 |
| HP            | 650                         | [9e558b592d](https://linux-hardware.org/?probe=9e558b592d) | Dec 03, 2019 |
| HP            | 650                         | [4a1d85a63b](https://linux-hardware.org/?probe=4a1d85a63b) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4db92d49fe](https://linux-hardware.org/?probe=4db92d49fe) | Nov 30, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [495e998bda](https://linux-hardware.org/?probe=495e998bda) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [d73b2ac7d1](https://linux-hardware.org/?probe=d73b2ac7d1) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [20a9604e39](https://linux-hardware.org/?probe=20a9604e39) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [5fd6ae6ef8](https://linux-hardware.org/?probe=5fd6ae6ef8) | Nov 28, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [bf342390e8](https://linux-hardware.org/?probe=bf342390e8) | Nov 24, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Dell          | Precision M3800             | [b133f93faa](https://linux-hardware.org/?probe=b133f93faa) | Nov 10, 2019 |
| Toshiba       | Satellite P755              | [673d423adc](https://linux-hardware.org/?probe=673d423adc) | Nov 10, 2019 |
| Toshiba       | Satellite L50D-B            | [eb4b70f853](https://linux-hardware.org/?probe=eb4b70f853) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [231e9df41d](https://linux-hardware.org/?probe=231e9df41d) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [3b759734b2](https://linux-hardware.org/?probe=3b759734b2) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [fe505beff6](https://linux-hardware.org/?probe=fe505beff6) | Nov 03, 2019 |
| Pegatron      | A15                         | [291f1aae6d](https://linux-hardware.org/?probe=291f1aae6d) | Oct 29, 2019 |
| HP            | Pavilion Notebook           | [87a279150a](https://linux-hardware.org/?probe=87a279150a) | Oct 26, 2019 |
| HP            | 630                         | [99ab4364d4](https://linux-hardware.org/?probe=99ab4364d4) | Oct 26, 2019 |
| Acer          | AOD270                      | [fbe9c7eee3](https://linux-hardware.org/?probe=fbe9c7eee3) | Oct 25, 2019 |
| Acer          | AOD270                      | [a00a0bd225](https://linux-hardware.org/?probe=a00a0bd225) | Oct 25, 2019 |
| Acer          | AOD270                      | [1797ad8387](https://linux-hardware.org/?probe=1797ad8387) | Oct 25, 2019 |
| Acer          | AOD270                      | [cfabf3084a](https://linux-hardware.org/?probe=cfabf3084a) | Oct 25, 2019 |
| HP            | Presario CQ57               | [758c395c78](https://linux-hardware.org/?probe=758c395c78) | Oct 23, 2019 |
| Acer          | AOD270                      | [1ae1144336](https://linux-hardware.org/?probe=1ae1144336) | Oct 19, 2019 |
| Sony          | SVE1512C6EW                 | [cc73d5214f](https://linux-hardware.org/?probe=cc73d5214f) | Sep 23, 2019 |
| Lenovo        | N22 80S6                    | [5850aa007f](https://linux-hardware.org/?probe=5850aa007f) | Sep 09, 2019 |
| Toshiba       | Satellite S855D             | [b0e8c02a13](https://linux-hardware.org/?probe=b0e8c02a13) | Sep 07, 2019 |
| ASUSTek       | X541NA                      | [dad09e76f4](https://linux-hardware.org/?probe=dad09e76f4) | Sep 05, 2019 |
| HP            | Compaq Presario C700        | [f05eb74bea](https://linux-hardware.org/?probe=f05eb74bea) | Aug 31, 2019 |
| HP            | Pavilion 15                 | [2f3cb20593](https://linux-hardware.org/?probe=2f3cb20593) | Aug 30, 2019 |
| Lenovo        | G550 20023                  | [d6126ff072](https://linux-hardware.org/?probe=d6126ff072) | Aug 30, 2019 |
| HP            | Pavilion 15                 | [61616fc1bf](https://linux-hardware.org/?probe=61616fc1bf) | Aug 10, 2019 |
| HP            | Pavilion 15                 | [dc6c804e81](https://linux-hardware.org/?probe=dc6c804e81) | Jul 26, 2019 |
| HP            | Pavilion 15                 | [3652e8f3c6](https://linux-hardware.org/?probe=3652e8f3c6) | Jul 26, 2019 |
| Pegatron      | A15                         | [1b6dcb6a34](https://linux-hardware.org/?probe=1b6dcb6a34) | Jul 20, 2019 |
| Lenovo        | N22 80S6                    | [5d140c644e](https://linux-hardware.org/?probe=5d140c644e) | Jul 19, 2019 |
| Lenovo        | N22 80S6                    | [a22adedc47](https://linux-hardware.org/?probe=a22adedc47) | Jul 19, 2019 |
| Lenovo        | N22 80S6                    | [97f993a2ca](https://linux-hardware.org/?probe=97f993a2ca) | Jul 19, 2019 |
| Packard Be... | EasyNote MH35               | [eb538975bd](https://linux-hardware.org/?probe=eb538975bd) | Jul 13, 2019 |
| HP            | Pavilion zd8000 (EL033EA... | [91c7ae2180](https://linux-hardware.org/?probe=91c7ae2180) | Jul 12, 2019 |
| HP            | Compaq Presario CQ60        | [265a212fdc](https://linux-hardware.org/?probe=265a212fdc) | Jun 02, 2019 |
| HP            | Compaq Presario CQ60        | [324a4ad8f5](https://linux-hardware.org/?probe=324a4ad8f5) | Jun 02, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [5834730131](https://linux-hardware.org/?probe=5834730131) | May 31, 2019 |
| HP            | Compaq Presario CQ60        | [4e935854b3](https://linux-hardware.org/?probe=4e935854b3) | May 26, 2019 |
| Lenovo        | V510-15IKB 80WQ             | [a8db92bb48](https://linux-hardware.org/?probe=a8db92bb48) | May 23, 2019 |
| MSI           | GE70 2PC                    | [347632684e](https://linux-hardware.org/?probe=347632684e) | May 10, 2019 |
| Dell          | Inspiron 3537               | [b57530d6a4](https://linux-hardware.org/?probe=b57530d6a4) | May 07, 2019 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [bf6bd6c60d](https://linux-hardware.org/?probe=bf6bd6c60d) | May 06, 2019 |
| Fujitsu Si... | AMILO Xi 2428               | [7f4acc9070](https://linux-hardware.org/?probe=7f4acc9070) | May 03, 2019 |
| Dell          | Inspiron 3521               | [5913b022e4](https://linux-hardware.org/?probe=5913b022e4) | May 01, 2019 |
| Toshiba       | Satellite S855D             | [134772dba8](https://linux-hardware.org/?probe=134772dba8) | Apr 30, 2019 |
| Toshiba       | Satellite S855D             | [5dd018b04a](https://linux-hardware.org/?probe=5dd018b04a) | Apr 28, 2019 |
| Toshiba       | Satellite S855D             | [6cfd5556fd](https://linux-hardware.org/?probe=6cfd5556fd) | Apr 28, 2019 |
| Toshiba       | Satellite S855D             | [b1213b7b31](https://linux-hardware.org/?probe=b1213b7b31) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [90cf61c66f](https://linux-hardware.org/?probe=90cf61c66f) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [820530546d](https://linux-hardware.org/?probe=820530546d) | Apr 28, 2019 |
| HP            | Pavilion g6                 | [50125f8815](https://linux-hardware.org/?probe=50125f8815) | Apr 25, 2019 |
| Dell          | Inspiron 5323               | [d25db8c5f1](https://linux-hardware.org/?probe=d25db8c5f1) | Apr 24, 2019 |
| Dell          | Inspiron 3543               | [b028e3e4f9](https://linux-hardware.org/?probe=b028e3e4f9) | Apr 18, 2019 |
| Intel         | Calistoga & ICH7M Chipse... | [146663e5c0](https://linux-hardware.org/?probe=146663e5c0) | Apr 17, 2019 |
| Info Quest... | GTN1408                     | [968a29d212](https://linux-hardware.org/?probe=968a29d212) | Apr 06, 2019 |
| HP            | Pavilion x2 Detachable      | [f91e0fbe6b](https://linux-hardware.org/?probe=f91e0fbe6b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | [72dfd27f3b](https://linux-hardware.org/?probe=72dfd27f3b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | [7dfc4ddd35](https://linux-hardware.org/?probe=7dfc4ddd35) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [bfc5bebd38](https://linux-hardware.org/?probe=bfc5bebd38) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [b0a5ef56cb](https://linux-hardware.org/?probe=b0a5ef56cb) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [4d7df702b8](https://linux-hardware.org/?probe=4d7df702b8) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [1b08ea07c0](https://linux-hardware.org/?probe=1b08ea07c0) | Apr 05, 2019 |
| Dell          | Inspiron 3576               | [132c5c22bb](https://linux-hardware.org/?probe=132c5c22bb) | Mar 24, 2019 |
| Dell          | Inspiron 3576               | [df5ad730b4](https://linux-hardware.org/?probe=df5ad730b4) | Mar 18, 2019 |
| Dell          | Inspiron 3576               | [a88f966e70](https://linux-hardware.org/?probe=a88f966e70) | Mar 18, 2019 |
| Toshiba       | Satellite C660D             | [884f236bc9](https://linux-hardware.org/?probe=884f236bc9) | Mar 14, 2019 |
| Toshiba       | Satellite C660D             | [ec10f22ef4](https://linux-hardware.org/?probe=ec10f22ef4) | Mar 12, 2019 |
| Sony          | VGN-SZ71XN_C                | [afbc222743](https://linux-hardware.org/?probe=afbc222743) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | [37cc1206c6](https://linux-hardware.org/?probe=37cc1206c6) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | [75a71aa3ec](https://linux-hardware.org/?probe=75a71aa3ec) | Mar 10, 2019 |
| ASUSTek       | X555BA                      | [79a6f78b23](https://linux-hardware.org/?probe=79a6f78b23) | Mar 07, 2019 |
| Acer          | Aspire 5935                 | [454098b840](https://linux-hardware.org/?probe=454098b840) | Mar 04, 2019 |
| HP            | Pavilion dv5                | [cfd60bad2b](https://linux-hardware.org/?probe=cfd60bad2b) | Feb 23, 2019 |
| Dell          | Inspiron 3543               | [f4642a0a54](https://linux-hardware.org/?probe=f4642a0a54) | Feb 17, 2019 |
| Dell          | Inspiron 3543               | [bf3ef7e629](https://linux-hardware.org/?probe=bf3ef7e629) | Feb 17, 2019 |
| Dell          | Inspiron 5555               | [65100107dc](https://linux-hardware.org/?probe=65100107dc) | Feb 16, 2019 |
| HP            | 15                          | [30a42ae5dc](https://linux-hardware.org/?probe=30a42ae5dc) | Feb 13, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [5a68cab2c0](https://linux-hardware.org/?probe=5a68cab2c0) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [d2e0a7dddf](https://linux-hardware.org/?probe=d2e0a7dddf) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [103dc16b24](https://linux-hardware.org/?probe=103dc16b24) | Jan 24, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [e7121f92f8](https://linux-hardware.org/?probe=e7121f92f8) | Jan 20, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b72be1d6f](https://linux-hardware.org/?probe=5b72be1d6f) | Jan 01, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [44d69d32d5](https://linux-hardware.org/?probe=44d69d32d5) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [ac9ae784ed](https://linux-hardware.org/?probe=ac9ae784ed) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [9947b5b177](https://linux-hardware.org/?probe=9947b5b177) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [5100558204](https://linux-hardware.org/?probe=5100558204) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [3cc96f096e](https://linux-hardware.org/?probe=3cc96f096e) | Dec 28, 2018 |
| Dell          | Inspiron 3542               | [a630fe7049](https://linux-hardware.org/?probe=a630fe7049) | Dec 25, 2018 |
| Dell          | Inspiron 3542               | [cd0695d1aa](https://linux-hardware.org/?probe=cd0695d1aa) | Dec 25, 2018 |
| Dell          | Inspiron 3521               | [f56872fdba](https://linux-hardware.org/?probe=f56872fdba) | Dec 15, 2018 |
| Dell          | Inspiron 3521               | [a3e64442a6](https://linux-hardware.org/?probe=a3e64442a6) | Dec 15, 2018 |
| Acer          | Aspire A315-31              | [03420d4e05](https://linux-hardware.org/?probe=03420d4e05) | Dec 03, 2018 |
| Acer          | Aspire A315-31              | [5afd838dfc](https://linux-hardware.org/?probe=5afd838dfc) | Dec 03, 2018 |
| Sony          | VGN-AR41L                   | [e80a4c81ba](https://linux-hardware.org/?probe=e80a4c81ba) | Nov 17, 2018 |
| Sony          | VGN-AR41L                   | [33c85bd949](https://linux-hardware.org/?probe=33c85bd949) | Nov 17, 2018 |
| HP            | 630                         | [375f1ecc8e](https://linux-hardware.org/?probe=375f1ecc8e) | Nov 11, 2018 |
| Fujitsu       | LIFEBOOK S760               | [e5a9a2740a](https://linux-hardware.org/?probe=e5a9a2740a) | Nov 03, 2018 |
| Lenovo        | ThinkPad X201 3680BW9       | [b2ac9f5577](https://linux-hardware.org/?probe=b2ac9f5577) | Nov 03, 2018 |
| HP            | Notebook                    | [643f8c70bb](https://linux-hardware.org/?probe=643f8c70bb) | Oct 30, 2018 |
| Lenovo        | G700 20251                  | [25cef818bf](https://linux-hardware.org/?probe=25cef818bf) | Oct 22, 2018 |
| HP            | Notebook                    | [8be002c789](https://linux-hardware.org/?probe=8be002c789) | Oct 21, 2018 |
| HP            | EliteBook 820 G1            | [5ffb2eac69](https://linux-hardware.org/?probe=5ffb2eac69) | Jun 12, 2018 |
| Lenovo        | ThinkPad X230 2320LFG       | [e96e3e911f](https://linux-hardware.org/?probe=e96e3e911f) | Jun 12, 2018 |
| Dell          | Latitude D530               | [37fd80baa9](https://linux-hardware.org/?probe=37fd80baa9) | May 18, 2018 |
| Dell          | Latitude D530               | [4a84b665e6](https://linux-hardware.org/?probe=4a84b665e6) | May 18, 2018 |
| Lenovo        | G510 20238                  | [f39685a972](https://linux-hardware.org/?probe=f39685a972) | Apr 22, 2018 |
| HP            | G62                         | [4fd190da5e](https://linux-hardware.org/?probe=4fd190da5e) | Apr 18, 2018 |
| Clevo         | W251ESQ/W270ESQ             | [a9eccff022](https://linux-hardware.org/?probe=a9eccff022) | Aug 01, 2017 |
| ASUSTek       | UX31E                       | [6be30c42a9](https://linux-hardware.org/?probe=6be30c42a9) | Jun 28, 2017 |
| Dell          | Inspiron 5558               | [ffc88e7749](https://linux-hardware.org/?probe=ffc88e7749) | Apr 23, 2017 |
| Toshiba       | TECRA R850                  | [6f44cbe917](https://linux-hardware.org/?probe=6f44cbe917) | Mar 14, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 82        | 15.53%  |
| Ubuntu 18.04       | 63        | 11.93%  |
| OpenMandriva 4.2   | 14        | 2.65%   |
| KDE neon 20.04     | 13        | 2.46%   |
| Linux Mint 19.3    | 12        | 2.27%   |
| Zorin 15           | 10        | 1.89%   |
| Ubuntu 19.10       | 10        | 1.89%   |
| Debian 10          | 10        | 1.89%   |
| Xubuntu 20.04      | 9         | 1.7%    |
| Pop!_OS 20.04      | 9         | 1.7%    |
| Linux Mint 20.1    | 9         | 1.7%    |
| Fedora 35          | 9         | 1.7%    |
| Debian 11          | 9         | 1.7%    |
| Arch Rolling       | 9         | 1.7%    |
| Pop!_OS 21.04      | 8         | 1.52%   |
| Manjaro            | 8         | 1.52%   |
| Linux Mint 20.2    | 8         | 1.52%   |
| Arch               | 8         | 1.52%   |
| Xubuntu 18.04      | 7         | 1.33%   |
| Ubuntu 21.10       | 7         | 1.33%   |
| ROSA R10           | 7         | 1.33%   |
| Pop!_OS 20.10      | 7         | 1.33%   |
| Kubuntu 20.04      | 7         | 1.33%   |
| Gentoo 2.7         | 7         | 1.33%   |
| Zorin 16           | 6         | 1.14%   |
| Ubuntu 21.04       | 6         | 1.14%   |
| Ubuntu 19.04       | 6         | 1.14%   |
| OpenMandriva 4.3   | 6         | 1.14%   |
| ArcoLinux Rolling  | 6         | 1.14%   |
| Ubuntu 20.10       | 5         | 0.95%   |
| Linux Mint 20      | 5         | 0.95%   |
| Fedora 33          | 5         | 0.95%   |
| Fedora 32          | 5         | 0.95%   |
| Ubuntu 18.10       | 4         | 0.76%   |
| Pop!_OS 21.10      | 4         | 0.76%   |
| Gentoo 2.6         | 4         | 0.76%   |
| Fedora 34          | 4         | 0.76%   |
| Ubuntu MATE 20.04  | 3         | 0.57%   |
| Ubuntu 16.04       | 3         | 0.57%   |
| ROSA R8.1          | 3         | 0.57%   |
| Manjaro 20.0.3     | 3         | 0.57%   |
| LMDE 4             | 3         | 0.57%   |
| LinuxFX 11         | 3         | 0.57%   |
| Linux Mint 20.3    | 3         | 0.57%   |
| Linux Mint 19.1    | 3         | 0.57%   |
| ALT Linux 10.0     | 3         | 0.57%   |
| Xero Rolling       | 2         | 0.38%   |
| ROSA R9            | 2         | 0.38%   |
| ROSA R11           | 2         | 0.38%   |
| openSUSE Leap-15.3 | 2         | 0.38%   |
| OpenMandriva 4.50  | 2         | 0.38%   |
| Manjaro 21.1.6     | 2         | 0.38%   |
| Manjaro 20.2       | 2         | 0.38%   |
| Manjaro 20.1       | 2         | 0.38%   |
| Linux Mint 19.2    | 2         | 0.38%   |
| Kubuntu 20.10      | 2         | 0.38%   |
| Gentoo 2.8         | 2         | 0.38%   |
| Fedora 31          | 2         | 0.38%   |
| Fedora 30          | 2         | 0.38%   |
| Endless 3.7.3      | 2         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 179       | 35.66%  |
| Linux Mint    | 42        | 8.37%   |
| Pop!_OS       | 26        | 5.18%   |
| Fedora        | 25        | 4.98%   |
| OpenMandriva  | 23        | 4.58%   |
| Debian        | 22        | 4.38%   |
| Manjaro       | 20        | 3.98%   |
| Zorin         | 17        | 3.39%   |
| Xubuntu       | 17        | 3.39%   |
| Arch          | 16        | 3.19%   |
| Endless       | 14        | 2.79%   |
| ROSA          | 13        | 2.59%   |
| KDE neon      | 13        | 2.59%   |
| Kubuntu       | 10        | 1.99%   |
| Gentoo        | 8         | 1.59%   |
| ArcoLinux     | 7         | 1.39%   |
| Ubuntu MATE   | 5         | 1%      |
| Ubuntu Budgie | 3         | 0.6%    |
| LMDE          | 3         | 0.6%    |
| LinuxFX       | 3         | 0.6%    |
| Kali          | 3         | 0.6%    |
| EndeavourOS   | 3         | 0.6%    |
| Elementary    | 3         | 0.6%    |
| BlackPanther  | 3         | 0.6%    |
| ALT Linux     | 3         | 0.6%    |
| Xero          | 2         | 0.4%    |
| Peppermint    | 2         | 0.4%    |
| openSUSE      | 2         | 0.4%    |
| Lubuntu       | 2         | 0.4%    |
| CentOS        | 2         | 0.4%    |
| Void Linux    | 1         | 0.2%    |
| Solus         | 1         | 0.2%    |
| Parrot        | 1         | 0.2%    |
| MX            | 1         | 0.2%    |
| Mageia        | 1         | 0.2%    |
| GNOME OS      | 1         | 0.2%    |
| Devuan        | 1         | 0.2%    |
| Deepin        | 1         | 0.2%    |
| Chrome OS     | 1         | 0.2%    |
| BlackArch     | 1         | 0.2%    |
| Artix         | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-58-generic                | 15        | 2.59%   |
| 5.4.0-42-generic                | 13        | 2.25%   |
| 5.10.14-desktop-1omv4002        | 13        | 2.25%   |
| 5.4.0-29-generic                | 8         | 1.38%   |
| 5.4.0-48-generic                | 7         | 1.21%   |
| 5.4.0-65-generic                | 6         | 1.04%   |
| 5.3.0-45-generic                | 6         | 1.04%   |
| 5.16.7-desktop-1omv4003         | 6         | 1.04%   |
| 5.11.0-38-generic               | 6         | 1.04%   |
| 5.8.0-55-generic                | 5         | 0.86%   |
| 5.4.0-37-generic                | 5         | 0.86%   |
| 5.3.0-46-generic                | 5         | 0.86%   |
| 5.3.0-42-generic                | 5         | 0.86%   |
| 5.13.0-39-generic               | 5         | 0.86%   |
| 5.11.0-7620-generic             | 5         | 0.86%   |
| 5.11.0-7614-generic             | 5         | 0.86%   |
| 5.0.0-37-generic                | 5         | 0.86%   |
| 4.15.0-47-generic               | 5         | 0.86%   |
| 5.8.0-7630-generic              | 4         | 0.69%   |
| 5.8.0-48-generic                | 4         | 0.69%   |
| 5.8.0-43-generic                | 4         | 0.69%   |
| 5.4.0-91-generic                | 4         | 0.69%   |
| 5.4.0-72-generic                | 4         | 0.69%   |
| 5.4.0-66-generic                | 4         | 0.69%   |
| 5.4.0-56-generic                | 4         | 0.69%   |
| 5.4.0-54-generic                | 4         | 0.69%   |
| 5.4.0-52-generic                | 4         | 0.69%   |
| 5.3.0-51-generic                | 4         | 0.69%   |
| 5.13.0-30-generic               | 4         | 0.69%   |
| 5.11.0-40-generic               | 4         | 0.69%   |
| 5.11.0-37-generic               | 4         | 0.69%   |
| 5.11.0-35-generic               | 4         | 0.69%   |
| 5.0.0-23-generic                | 4         | 0.69%   |
| 5.0.0-13-generic                | 4         | 0.69%   |
| 5.8.0-7642-generic              | 3         | 0.52%   |
| 5.8.0-63-generic                | 3         | 0.52%   |
| 5.4.0-81-generic                | 3         | 0.52%   |
| 5.4.0-33-generic                | 3         | 0.52%   |
| 5.4.0-26-generic                | 3         | 0.52%   |
| 5.3.0-62-generic                | 3         | 0.52%   |
| 5.3.0-28-generic                | 3         | 0.52%   |
| 5.3.0-26-generic                | 3         | 0.52%   |
| 5.13.0-28-generic               | 3         | 0.52%   |
| 5.11.0-46-generic               | 3         | 0.52%   |
| 5.11.0-41-generic               | 3         | 0.52%   |
| 5.11.0-27-generic               | 3         | 0.52%   |
| 5.11.0-17-generic               | 3         | 0.52%   |
| 5.10.88-std-def-alt1            | 3         | 0.52%   |
| 5.10.0-13-amd64                 | 3         | 0.52%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 0.52%   |
| 4.18.0-10-generic               | 3         | 0.52%   |
| 4.15.0-91-generic               | 3         | 0.52%   |
| 4.15.0-54-generic               | 3         | 0.52%   |
| 4.15.0-45-generic               | 3         | 0.52%   |
| 5.9.16-1-MANJARO                | 2         | 0.35%   |
| 5.9.11-200.fc33.x86_64          | 2         | 0.35%   |
| 5.8.6-1-MANJARO                 | 2         | 0.35%   |
| 5.8.18-1-MANJARO                | 2         | 0.35%   |
| 5.8.0-59-generic                | 2         | 0.35%   |
| 5.8.0-53-generic                | 2         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 118       | 21.53%  |
| 5.11.0  | 50        | 9.12%   |
| 4.15.0  | 44        | 8.03%   |
| 5.8.0   | 40        | 7.3%    |
| 5.3.0   | 37        | 6.75%   |
| 5.13.0  | 24        | 4.38%   |
| 5.0.0   | 21        | 3.83%   |
| 5.10.14 | 13        | 2.37%   |
| 4.18.0  | 13        | 2.37%   |
| 4.19.0  | 11        | 2.01%   |
| 5.10.0  | 10        | 1.82%   |
| 5.16.7  | 6         | 1.09%   |
| 5.9.11  | 5         | 0.91%   |
| 5.11.12 | 4         | 0.73%   |
| 5.10.88 | 4         | 0.73%   |
| 4.9.20  | 4         | 0.73%   |
| 5.8.18  | 3         | 0.55%   |
| 5.7.2   | 3         | 0.55%   |
| 5.3.18  | 3         | 0.55%   |
| 5.15.5  | 3         | 0.55%   |
| 4.9.60  | 3         | 0.55%   |
| 5.9.16  | 2         | 0.36%   |
| 5.8.6   | 2         | 0.36%   |
| 5.8.16  | 2         | 0.36%   |
| 5.5.13  | 2         | 0.36%   |
| 5.4.77  | 2         | 0.36%   |
| 5.17.1  | 2         | 0.36%   |
| 5.15.32 | 2         | 0.36%   |
| 5.15.19 | 2         | 0.36%   |
| 5.15.16 | 2         | 0.36%   |
| 5.15.0  | 2         | 0.36%   |
| 5.14.14 | 2         | 0.36%   |
| 5.14.10 | 2         | 0.36%   |
| 5.14.0  | 2         | 0.36%   |
| 5.12.4  | 2         | 0.36%   |
| 5.12.14 | 2         | 0.36%   |
| 5.11.11 | 2         | 0.36%   |
| 5.10.70 | 2         | 0.36%   |
| 5.10.31 | 2         | 0.36%   |
| 4.1.38  | 2         | 0.36%   |
| 5.9.7   | 1         | 0.18%   |
| 5.9.6   | 1         | 0.18%   |
| 5.9.3   | 1         | 0.18%   |
| 5.9.14  | 1         | 0.18%   |
| 5.9.13  | 1         | 0.18%   |
| 5.9.1   | 1         | 0.18%   |
| 5.9.0   | 1         | 0.18%   |
| 5.8.9   | 1         | 0.18%   |
| 5.8.7   | 1         | 0.18%   |
| 5.8.5   | 1         | 0.18%   |
| 5.8.15  | 1         | 0.18%   |
| 5.8.14  | 1         | 0.18%   |
| 5.8.12  | 1         | 0.18%   |
| 5.8.10  | 1         | 0.18%   |
| 5.8.1   | 1         | 0.18%   |
| 5.7.5   | 1         | 0.18%   |
| 5.7.19  | 1         | 0.18%   |
| 5.7.0   | 1         | 0.18%   |
| 5.6.8   | 1         | 0.18%   |
| 5.6.6   | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 129       | 23.89%  |
| 5.11    | 61        | 11.3%   |
| 5.8     | 54        | 10%     |
| 4.15    | 44        | 8.15%   |
| 5.3     | 43        | 7.96%   |
| 5.10    | 41        | 7.59%   |
| 5.13    | 28        | 5.19%   |
| 5.0     | 22        | 4.07%   |
| 5.15    | 15        | 2.78%   |
| 4.18    | 14        | 2.59%   |
| 5.9     | 12        | 2.22%   |
| 5.16    | 12        | 2.22%   |
| 4.19    | 11        | 2.04%   |
| 4.9     | 9         | 1.67%   |
| 5.14    | 8         | 1.48%   |
| 5.12    | 7         | 1.3%    |
| 5.7     | 6         | 1.11%   |
| 5.6     | 6         | 1.11%   |
| 5.5     | 6         | 1.11%   |
| 5.17    | 4         | 0.74%   |
| 4.1     | 2         | 0.37%   |
| 5.2     | 1         | 0.19%   |
| 4.20    | 1         | 0.19%   |
| 4.16    | 1         | 0.19%   |
| 4.10    | 1         | 0.19%   |
| 3.16    | 1         | 0.19%   |
| 3.10    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 450       | 92.98%  |
| i686   | 34        | 7.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| GNOME               | 218       | 42.83%  |
| Unknown             | 74        | 14.54%  |
| KDE5                | 66        | 12.97%  |
| XFCE                | 47        | 9.23%   |
| X-Cinnamon          | 35        | 6.88%   |
| KDE                 | 19        | 3.73%   |
| MATE                | 17        | 3.34%   |
| KDE4                | 7         | 1.38%   |
| Budgie              | 5         | 0.98%   |
| Unity               | 3         | 0.59%   |
| Pantheon            | 3         | 0.59%   |
| Cinnamon            | 3         | 0.59%   |
| LXQt                | 2         | 0.39%   |
| LXDE                | 2         | 0.39%   |
| i3                  | 2         | 0.39%   |
| GNOME Classic       | 2         | 0.39%   |
| openbox             | 1         | 0.2%    |
| Deepin              | 1         | 0.2%    |
| awesome             | 1         | 0.2%    |
| /usr/bin/startxfce4 | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 406       | 81.53%  |
| Wayland | 43        | 8.63%   |
| Unknown | 40        | 8.03%   |
| Tty     | 9         | 1.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 309       | 61.55%  |
| SDDM    | 57        | 11.35%  |
| GDM     | 52        | 10.36%  |
| LightDM | 36        | 7.17%   |
| GDM3    | 21        | 4.18%   |
| TDM     | 16        | 3.19%   |
| KDM     | 7         | 1.39%   |
| XDM     | 2         | 0.4%    |
| SLiM    | 1         | 0.2%    |
| Ly      | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 261       | 52.3%   |
| el_GR   | 135       | 27.05%  |
| Unknown | 73        | 14.63%  |
| en_GB   | 11        | 2.2%    |
| de_DE   | 5         | 1%      |
| C       | 4         | 0.8%    |
| POSIX   | 2         | 0.4%    |
| fr_FR   | 2         | 0.4%    |
| ru_RU   | 1         | 0.2%    |
| pl_PL   | 1         | 0.2%    |
| it_IT   | 1         | 0.2%    |
| hu_HU   | 1         | 0.2%    |
| C.UTF8  | 1         | 0.2%    |
| anp_IN  | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 269       | 54.34%  |
| EFI  | 226       | 45.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 398       | 80.4%   |
| Btrfs   | 36        | 7.27%   |
| Overlay | 30        | 6.06%   |
| Unknown | 27        | 5.45%   |
| Zfs     | 3         | 0.61%   |
| Tmpfs   | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 326       | 66.13%  |
| GPT     | 111       | 22.52%  |
| MBR     | 56        | 11.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 428       | 86.82%  |
| Yes       | 65        | 13.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 346       | 71.05%  |
| Yes       | 141       | 28.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 110       | 22.73%  |
| Lenovo                  | 90        | 18.6%   |
| Dell                    | 78        | 16.12%  |
| Acer                    | 40        | 8.26%   |
| ASUSTek Computer        | 37        | 7.64%   |
| Toshiba                 | 24        | 4.96%   |
| Sony                    | 23        | 4.75%   |
| Fujitsu Siemens         | 9         | 1.86%   |
| Fujitsu                 | 9         | 1.86%   |
| Apple                   | 6         | 1.24%   |
| Unknown                 | 6         | 1.24%   |
| Notebook                | 5         | 1.03%   |
| HUAWEI                  | 5         | 1.03%   |
| Clevo                   | 5         | 1.03%   |
| MSI                     | 4         | 0.83%   |
| Teclast                 | 3         | 0.62%   |
| Samsung Electronics     | 3         | 0.62%   |
| Pegatron                | 2         | 0.41%   |
| Intel                   | 2         | 0.41%   |
| Insyde                  | 2         | 0.41%   |
| Info Quest Technologies | 2         | 0.41%   |
| Hampoo                  | 2         | 0.41%   |
| e-shop.gr               | 2         | 0.41%   |
| Chuwi                   | 2         | 0.41%   |
| VERO                    | 1         | 0.21%   |
| TUXEDO                  | 1         | 0.21%   |
| Schenker                | 1         | 0.21%   |
| Quest                   | 1         | 0.21%   |
| PLAISIO COMPUTERS SA    | 1         | 0.21%   |
| PC Specialist           | 1         | 0.21%   |
| Packard Bell            | 1         | 0.21%   |
| Medion                  | 1         | 0.21%   |
| IBM                     | 1         | 0.21%   |
| Google                  | 1         | 0.21%   |
| Compal                  | 1         | 0.21%   |
| ARIMA                   | 1         | 0.21%   |
| Alienware               | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 11        | 2.27%   |
| HP Pavilion g6                         | 6         | 1.24%   |
| HP Notebook                            | 6         | 1.24%   |
| Dell Inspiron 3542                     | 5         | 1.03%   |
| HP G62                                 | 4         | 0.83%   |
| HP 255 G7 Notebook PC                  | 4         | 0.83%   |
| Dell Inspiron 3537                     | 4         | 0.83%   |
| Lenovo G510 20238                      | 3         | 0.62%   |
| HP Pavilion dv7                        | 3         | 0.62%   |
| Dell Inspiron 5567                     | 3         | 0.62%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.62%   |
| Acer Aspire A315-51                    | 3         | 0.62%   |
| Acer Aspire A315-31                    | 3         | 0.62%   |
| Toshiba Satellite C850D-119            | 2         | 0.41%   |
| Toshiba NB100                          | 2         | 0.41%   |
| Teclast F15                            | 2         | 0.41%   |
| Sony VPCM13M1E                         | 2         | 0.41%   |
| Sony VPCCB2S1E                         | 2         | 0.41%   |
| Notebook W54_W94_W955TU,-T,-C          | 2         | 0.41%   |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.41%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.41%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.41%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 2         | 0.41%   |
| Lenovo G700 20251                      | 2         | 0.41%   |
| Lenovo G70-35 80Q5                     | 2         | 0.41%   |
| Lenovo G50-70 20351                    | 2         | 0.41%   |
| Lenovo G40-30 80FY                     | 2         | 0.41%   |
| Intel Calistoga & ICH7M Chipset        | 2         | 0.41%   |
| Insyde CherryTrail                     | 2         | 0.41%   |
| HUAWEI NBLK-WAX9X                      | 2         | 0.41%   |
| HP ProBook 6560b                       | 2         | 0.41%   |
| HP Pavilion x2 Detachable              | 2         | 0.41%   |
| HP Pavilion Notebook                   | 2         | 0.41%   |
| HP Pavilion 15                         | 2         | 0.41%   |
| HP Laptop 17-ca1xxx                    | 2         | 0.41%   |
| HP EliteBook 8460p                     | 2         | 0.41%   |
| HP Compaq Presario C700                | 2         | 0.41%   |
| HP Compaq 6735s                        | 2         | 0.41%   |
| HP 255 G6 Notebook PC                  | 2         | 0.41%   |
| HP 255 G1                              | 2         | 0.41%   |
| HP 250 G3                              | 2         | 0.41%   |
| Hampoo Magic 11.6                      | 2         | 0.41%   |
| Fujitsu Siemens AMILO Xi 2428          | 2         | 0.41%   |
| Dell XPS 15 7590                       | 2         | 0.41%   |
| Dell Precision 3551                    | 2         | 0.41%   |
| Dell Latitude E7470                    | 2         | 0.41%   |
| Dell Latitude D530                     | 2         | 0.41%   |
| Dell Latitude 7420                     | 2         | 0.41%   |
| Dell Latitude 7400                     | 2         | 0.41%   |
| Dell Inspiron 5559                     | 2         | 0.41%   |
| Dell Inspiron 5558                     | 2         | 0.41%   |
| Dell Inspiron 3593                     | 2         | 0.41%   |
| Dell Inspiron 3543                     | 2         | 0.41%   |
| Dell Inspiron 3521                     | 2         | 0.41%   |
| Dell Inspiron 15 7000 Gaming           | 2         | 0.41%   |
| Clevo M740TU(N)/M760TU(N)/W7X0TUN      | 2         | 0.41%   |
| ASUS X556UQK                           | 2         | 0.41%   |
| ASUS X550CC                            | 2         | 0.41%   |
| ASUS X540LJ                            | 2         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X412DA_X412DA | 2         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 36        | 7.44%   |
| Lenovo ThinkPad       | 34        | 7.02%   |
| Acer Aspire           | 32        | 6.61%   |
| HP Pavilion           | 29        | 5.99%   |
| Lenovo IdeaPad        | 26        | 5.37%   |
| Dell Latitude         | 25        | 5.17%   |
| Toshiba Satellite     | 21        | 4.34%   |
| Unknown               | 11        | 2.27%   |
| HP Compaq             | 10        | 2.07%   |
| HP 255                | 10        | 2.07%   |
| HP EliteBook          | 9         | 1.86%   |
| ASUS VivoBook         | 9         | 1.86%   |
| HP Laptop             | 8         | 1.65%   |
| HP ProBook            | 7         | 1.45%   |
| Fujitsu Siemens AMILO | 7         | 1.45%   |
| Fujitsu LIFEBOOK      | 7         | 1.45%   |
| HP Notebook           | 6         | 1.24%   |
| HP 250                | 5         | 1.03%   |
| Dell Precision        | 5         | 1.03%   |
| ASUS TUF              | 5         | 1.03%   |
| HP G62                | 4         | 0.83%   |
| Dell XPS              | 4         | 0.83%   |
| Dell Vostro           | 4         | 0.83%   |
| Lenovo Legion         | 3         | 0.62%   |
| Lenovo G510           | 3         | 0.62%   |
| HP Presario           | 3         | 0.62%   |
| HP ENVY               | 3         | 0.62%   |
| Toshiba NB100         | 2         | 0.41%   |
| Teclast F15           | 2         | 0.41%   |
| Sony VPCM13M1E        | 2         | 0.41%   |
| Sony VPCCB2S1E        | 2         | 0.41%   |
| Notebook W65          | 2         | 0.41%   |
| Notebook W54          | 2         | 0.41%   |
| MSI GE70              | 2         | 0.41%   |
| Lenovo G700           | 2         | 0.41%   |
| Lenovo G70-35         | 2         | 0.41%   |
| Lenovo G50-70         | 2         | 0.41%   |
| Lenovo G40-30         | 2         | 0.41%   |
| Intel Calistoga       | 2         | 0.41%   |
| Insyde CherryTrail    | 2         | 0.41%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.41%   |
| Hampoo Magic          | 2         | 0.41%   |
| Dell Studio           | 2         | 0.41%   |
| Dell G3               | 2         | 0.41%   |
| Clevo M740TU(N)       | 2         | 0.41%   |
| ASUS X556UQK          | 2         | 0.41%   |
| ASUS X550CC           | 2         | 0.41%   |
| ASUS X540LJ           | 2         | 0.41%   |
| Apple MacBookPro8     | 2         | 0.41%   |
| Acer TravelMate       | 2         | 0.41%   |
| Acer Predator         | 2         | 0.41%   |
| VERO K147             | 1         | 0.21%   |
| TUXEDO Aura           | 1         | 0.21%   |
| Toshiba TECRA         | 1         | 0.21%   |
| Teclast F7            | 1         | 0.21%   |
| Sony VPCW12J1E        | 1         | 0.21%   |
| Sony VPCS11X9E        | 1         | 0.21%   |
| Sony VGN-SZ71XN       | 1         | 0.21%   |
| Sony VGN-NR11Z        | 1         | 0.21%   |
| Sony VGN-N31Z         | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 53        | 10.95%  |
| 2013 | 41        | 8.47%   |
| 2017 | 38        | 7.85%   |
| 2011 | 37        | 7.64%   |
| 2008 | 36        | 7.44%   |
| 2012 | 33        | 6.82%   |
| 2018 | 32        | 6.61%   |
| 2020 | 30        | 6.2%    |
| 2014 | 29        | 5.99%   |
| 2009 | 29        | 5.99%   |
| 2015 | 27        | 5.58%   |
| 2010 | 26        | 5.37%   |
| 2007 | 25        | 5.17%   |
| 2016 | 24        | 4.96%   |
| 2021 | 8         | 1.65%   |
| 2006 | 8         | 1.65%   |
| 2005 | 6         | 1.24%   |
| 2004 | 2         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 484       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 435       | 89.14%  |
| Enabled  | 53        | 10.86%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 483       | 99.79%  |
| Yes  | 1         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 154       | 31.43%  |
| 4.01-8.0    | 126       | 25.71%  |
| 8.01-16.0   | 72        | 14.69%  |
| 1.01-2.0    | 53        | 10.82%  |
| 16.01-24.0  | 44        | 8.98%   |
| 2.01-3.0    | 17        | 3.47%   |
| 32.01-64.0  | 11        | 2.24%   |
| 0.51-1.0    | 11        | 2.24%   |
| 24.01-32.0  | 1         | 0.2%    |
| 64.01-256.0 | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 234       | 43.66%  |
| 2.01-3.0   | 136       | 25.37%  |
| 0.51-1.0   | 57        | 10.63%  |
| 3.01-4.0   | 50        | 9.33%   |
| 4.01-8.0   | 40        | 7.46%   |
| 8.01-16.0  | 9         | 1.68%   |
| 0.01-0.5   | 8         | 1.49%   |
| 24.01-32.0 | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 358       | 72.47%  |
| 2      | 122       | 24.7%   |
| 3      | 7         | 1.42%   |
| 0      | 5         | 1.01%   |
| 6      | 1         | 0.2%    |
| 4      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 259       | 53.29%  |
| Yes       | 227       | 46.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 417       | 85.98%  |
| No        | 68        | 14.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 477       | 98.35%  |
| No        | 8         | 1.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 73.06%  |
| No        | 132       | 26.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Greece  | 484       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Athens       | 262       | 51.17%  |
| Thessaloniki | 78        | 15.23%  |
| Chalcis      | 12        | 2.34%   |
| Heraklion    | 9         | 1.76%   |
| Volos        | 8         | 1.56%   |
| Piraeus      | 7         | 1.37%   |
| Larissa      | 7         | 1.37%   |
| Trikala      | 6         | 1.17%   |
| Kavala       | 5         | 0.98%   |
| Katerini     | 5         | 0.98%   |
| Ioannina     | 5         | 0.98%   |
| Corinth      | 5         | 0.98%   |
| PÃ¡trai    | 4         | 0.78%   |
| Lamia        | 4         | 0.78%   |
| Xanthi       | 3         | 0.59%   |
| Rhodes       | 3         | 0.59%   |
| Ptolemaida   | 3         | 0.59%   |
| Corfu        | 3         | 0.59%   |
| Chania       | 3         | 0.59%   |
| Vergina      | 2         | 0.39%   |
| Sparti       | 2         | 0.39%   |
| Serres       | 2         | 0.39%   |
| Salamina     | 2         | 0.39%   |
| Rethymno     | 2         | 0.39%   |
| PГЎtrai    | 2         | 0.39%   |
| Loutraki     | 2         | 0.39%   |
| Kymi         | 2         | 0.39%   |
| Kiato        | 2         | 0.39%   |
| Keratsini    | 2         | 0.39%   |
| Kalamata     | 2         | 0.39%   |
| Ilioupoli    | 2         | 0.39%   |
| Fira         | 2         | 0.39%   |
| Zakynthos    | 1         | 0.2%    |
| Voula        | 1         | 0.2%    |
| Vonitsa      | 1         | 0.2%    |
| Tripoli      | 1         | 0.2%    |
| Thebes       | 1         | 0.2%    |
| Thassos      | 1         | 0.2%    |
| Skydra       | 1         | 0.2%    |
| Samos        | 1         | 0.2%    |
| Rafina       | 1         | 0.2%    |
| Preveza      | 1         | 0.2%    |
| Peristeri    | 1         | 0.2%    |
| Peraia       | 1         | 0.2%    |
| Pasalimani   | 1         | 0.2%    |
| Paros        | 1         | 0.2%    |
| Old Faliron  | 1         | 0.2%    |
| Nemea        | 1         | 0.2%    |
| Nea Smyrni   | 1         | 0.2%    |
| Nea Moudania | 1         | 0.2%    |
| Naousa       | 1         | 0.2%    |
| Nafplion     | 1         | 0.2%    |
| Nafpaktos    | 1         | 0.2%    |
| Molaoi       | 1         | 0.2%    |
| Moires       | 1         | 0.2%    |
| Meliki       | 1         | 0.2%    |
| Megara       | 1         | 0.2%    |
| Malia        | 1         | 0.2%    |
| Limnos       | 1         | 0.2%    |
| Lavrio       | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 82        | 112    | 13.76%  |
| Seagate                        | 76        | 95     | 12.75%  |
| Samsung Electronics            | 67        | 81     | 11.24%  |
| Toshiba                        | 61        | 75     | 10.23%  |
| SanDisk                        | 41        | 48     | 6.88%   |
| Kingston                       | 39        | 50     | 6.54%   |
| Unknown                        | 34        | 54     | 5.7%    |
| SK Hynix                       | 24        | 34     | 4.03%   |
| Hitachi                        | 22        | 22     | 3.69%   |
| Patriot                        | 20        | 21     | 3.36%   |
| HGST                           | 18        | 21     | 3.02%   |
| Fujitsu                        | 16        | 16     | 2.68%   |
| Micron Technology              | 12        | 15     | 2.01%   |
| Crucial                        | 9         | 10     | 1.51%   |
| Intenso                        | 8         | 9      | 1.34%   |
| Intel                          | 8         | 9      | 1.34%   |
| Team                           | 7         | 13     | 1.17%   |
| KIOXIA                         | 5         | 5      | 0.84%   |
| OCZ                            | 4         | 4      | 0.67%   |
| JMicron                        | 4         | 4      | 0.67%   |
| Transcend                      | 3         | 3      | 0.5%    |
| Teclast                        | 3         | 3      | 0.5%    |
| Gigabyte Technology            | 2         | 2      | 0.34%   |
| Apple                          | 2         | 2      | 0.34%   |
| Unknown                        | 2         | 2      | 0.34%   |
| XPG                            | 1         | 1      | 0.17%   |
| WDC WDS                        | 1         | 1      | 0.17%   |
| Verbatim                       | 1         | 1      | 0.17%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.17%   |
| SSSTC                          | 1         | 1      | 0.17%   |
| Solid State Storage Technology | 1         | 1      | 0.17%   |
| SMI                            | 1         | 1      | 0.17%   |
| PNY                            | 1         | 1      | 0.17%   |
| PLEXTOR                        | 1         | 1      | 0.17%   |
| Phison                         | 1         | 1      | 0.17%   |
| OCZ-AGIL                       | 1         | 1      | 0.17%   |
| Netac                          | 1         | 1      | 0.17%   |
| Mushkin                        | 1         | 1      | 0.17%   |
| Micron/Crucial Technology      | 1         | 1      | 0.17%   |
| LITEON                         | 1         | 1      | 0.17%   |
| Leven                          | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.17%   |
| KingSpec                       | 1         | 1      | 0.17%   |
| IBM/Hitachi                    | 1         | 1      | 0.17%   |
| HGST HUS                       | 1         | 2      | 0.17%   |
| Hewlett-Packard                | 1         | 1      | 0.17%   |
| EMTEC                          | 1         | 4      | 0.17%   |
| DREVO                          | 1         | 1      | 0.17%   |
| ASUS-PHISON                    | 1         | 2      | 0.17%   |
| ASMT                           | 1         | 1      | 0.17%   |
| Apacer                         | 1         | 1      | 0.17%   |
| A-DATA Technology              | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 14        | 2.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 2.13%   |
| SK Hynix NVMe SSD Drive 256GB       | 10        | 1.64%   |
| Toshiba MQ01ABF050 500GB            | 9         | 1.47%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 1.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.31%   |
| Samsung SSD 860 EVO 500GB           | 8         | 1.31%   |
| Unknown MMC Card  64GB              | 7         | 1.15%   |
| Toshiba MQ01ABD100 1TB              | 7         | 1.15%   |
| Samsung SSD 860 EVO 250GB           | 7         | 1.15%   |
| Patriot Burst 120GB SSD             | 7         | 1.15%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 0.98%   |
| HGST HTS545050A7E680 500GB          | 6         | 0.98%   |
| Unknown MMC Card  128GB             | 5         | 0.82%   |
| Sandisk NVMe SSD Drive 256GB        | 5         | 0.82%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.82%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 0.82%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.82%   |
| Fujitsu MHY2200BH 200GB             | 5         | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4         | 0.65%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.65%   |
| Sandisk NVMe SSD Drive 512GB        | 4         | 0.65%   |
| Patriot Burst 480GB SSD             | 4         | 0.65%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 3         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB            | 3         | 0.49%   |
| Unknown MMC Card  2GB               | 3         | 0.49%   |
| Unknown MMC Card  16GB              | 3         | 0.49%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.49%   |
| Seagate ST9500420AS 500GB           | 3         | 0.49%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 0.49%   |
| SanDisk DF4032  32GB                | 3         | 0.49%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 0.49%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 0.49%   |
| Patriot Burst 240GB SSD             | 3         | 0.49%   |
| JMicron Generic 160GB               | 3         | 0.49%   |
| Intenso External USB 3.0 4TB        | 3         | 0.49%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.33%   |
| WDC WD800BEVE-00UYT0 80GB           | 2         | 0.33%   |
| WDC WD5000BPKT-00PK4T0 500GB        | 2         | 0.33%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 0.33%   |
| WDC WD2500BEVT-60ZCT1 250GB         | 2         | 0.33%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 0.33%   |
| WDC WD1600BEVS-22RST0 160GB         | 2         | 0.33%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 0.33%   |
| WDC WD10SPZX-21Z10T0 1TB            | 2         | 0.33%   |
| WDC WD10SPSX-75A6WT0 1TB            | 2         | 0.33%   |
| WDC WD10JPVX-75JC3T0 1TB            | 2         | 0.33%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.33%   |
| Unknown MMC Card  7GB               | 2         | 0.33%   |
| Transcend TS120GSSD220S 120GB       | 2         | 0.33%   |
| Toshiba NVMe SSD Drive 512GB        | 2         | 0.33%   |
| Toshiba NVMe SSD Drive 256GB        | 2         | 0.33%   |
| Toshiba MQ01ACF050 500GB            | 2         | 0.33%   |
| Toshiba MQ01ACF032 320GB            | 2         | 0.33%   |
| Toshiba MQ01ABD100M 1TB             | 2         | 0.33%   |
| Toshiba MK3276GSX 320GB             | 2         | 0.33%   |
| Toshiba MK2555GSX 250GB             | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 92     | 30.08%  |
| WDC                 | 59        | 73     | 23.98%  |
| Toshiba             | 44        | 56     | 17.89%  |
| Hitachi             | 22        | 22     | 8.94%   |
| HGST                | 18        | 21     | 7.32%   |
| Fujitsu             | 16        | 16     | 6.5%    |
| Samsung Electronics | 8         | 9      | 3.25%   |
| Intenso             | 3         | 4      | 1.22%   |
| IBM/Hitachi         | 1         | 1      | 0.41%   |
| Apple               | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 50     | 19.91%  |
| Kingston            | 33        | 43     | 15.64%  |
| SanDisk             | 28        | 33     | 13.27%  |
| Patriot             | 20        | 21     | 9.48%   |
| WDC                 | 14        | 27     | 6.64%   |
| Toshiba             | 8         | 9      | 3.79%   |
| Team                | 7         | 13     | 3.32%   |
| Micron Technology   | 7         | 8      | 3.32%   |
| Crucial             | 7         | 8      | 3.32%   |
| Intenso             | 5         | 5      | 2.37%   |
| OCZ                 | 4         | 4      | 1.9%    |
| Intel               | 4         | 4      | 1.9%    |
| Transcend           | 3         | 3      | 1.42%   |
| Teclast             | 3         | 3      | 1.42%   |
| SK Hynix            | 3         | 3      | 1.42%   |
| JMicron             | 3         | 3      | 1.42%   |
| Gigabyte Technology | 2         | 2      | 0.95%   |
| WDC WDS             | 1         | 1      | 0.47%   |
| Verbatim            | 1         | 1      | 0.47%   |
| PNY                 | 1         | 1      | 0.47%   |
| PLEXTOR             | 1         | 1      | 0.47%   |
| OCZ-AGIL            | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| Mushkin             | 1         | 1      | 0.47%   |
| Leven               | 1         | 1      | 0.47%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 1      | 0.47%   |
| EMTEC               | 1         | 4      | 0.47%   |
| DREVO               | 1         | 1      | 0.47%   |
| ASUS-PHISON         | 1         | 2      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |
| Apacer              | 1         | 1      | 0.47%   |
| A-DATA Technology   | 1         | 1      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 240       | 295    | 41.88%  |
| SSD     | 201       | 261    | 35.08%  |
| NVMe    | 90        | 119    | 15.71%  |
| MMC     | 37        | 61     | 6.46%   |
| Unknown | 5         | 6      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 392       | 538    | 73%     |
| NVMe | 90        | 119    | 16.76%  |
| MMC  | 37        | 61     | 6.89%   |
| SAS  | 18        | 24     | 3.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 331       | 431    | 77.16%  |
| 0.51-1.0   | 86        | 110    | 20.05%  |
| 1.01-2.0   | 8         | 10     | 1.86%   |
| 3.01-4.0   | 3         | 4      | 0.7%    |
| 2.01-3.0   | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 169       | 33.2%   |
| 251-500        | 119       | 23.38%  |
| 501-1000       | 58        | 11.39%  |
| 51-100         | 50        | 9.82%   |
| 1-20           | 37        | 7.27%   |
| 21-50          | 34        | 6.68%   |
| 1001-2000      | 23        | 4.52%   |
| Unknown        | 10        | 1.96%   |
| More than 3000 | 5         | 0.98%   |
| 2001-3000      | 4         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 232       | 44.62%  |
| 21-50          | 95        | 18.27%  |
| 51-100         | 61        | 11.73%  |
| 101-250        | 60        | 11.54%  |
| 251-500        | 34        | 6.54%   |
| 501-1000       | 14        | 2.69%   |
| 1001-2000      | 11        | 2.12%   |
| Unknown        | 10        | 1.92%   |
| More than 3000 | 3         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 3         | 3      | 12%     |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 4%      |
| WDC WD3200BEVT-26ZCT0 320GB           | 1         | 1      | 4%      |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 1      | 4%      |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 4%      |
| Toshiba MQ01ABD100M 1TB               | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB              | 1         | 3      | 4%      |
| SK Hynix SC210 mSATA 256GB SSD        | 1         | 1      | 4%      |
| Seagate ST980811AS 80GB               | 1         | 1      | 4%      |
| Seagate ST9320325AS 320GB             | 1         | 1      | 4%      |
| Seagate ST9160310AS 160GB             | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4%      |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 4%      |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 4      | 4%      |
| SanDisk SSD U100 128GB                | 1         | 1      | 4%      |
| SanDisk SSD PLUS 240GB                | 1         | 1      | 4%      |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 4%      |
| OCZ-AGIL ITY3 120GB SSD               | 1         | 1      | 4%      |
| Kingston RBUSNS8180DS3128GJ 128GB SSD | 1         | 1      | 4%      |
| Hitachi HTS723216L9A360 160GB         | 1         | 1      | 4%      |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 4%      |
| Fujitsu MHT2080BH 80GB                | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 28%     |
| WDC                 | 3         | 3      | 12%     |
| Toshiba             | 3         | 5      | 12%     |
| HGST                | 3         | 3      | 12%     |
| SanDisk             | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |
| SK Hynix            | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| OCZ-AGIL            | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 10     | 36.84%  |
| WDC     | 3         | 3      | 15.79%  |
| Toshiba | 3         | 5      | 15.79%  |
| HGST    | 3         | 3      | 15.79%  |
| Hitachi | 2         | 2      | 10.53%  |
| Fujitsu | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 24     | 76%     |
| SSD  | 5         | 5      | 20%     |
| NVMe | 1         | 1      | 4%      |

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
| Detected | 343       | 513    | 67.52%  |
| Works    | 140       | 199    | 27.56%  |
| Malfunc  | 25        | 30     | 4.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 353       | 67.24%  |
| AMD                              | 68        | 12.95%  |
| SK Hynix                         | 20        | 3.81%   |
| Samsung Electronics              | 19        | 3.62%   |
| Sandisk                          | 17        | 3.24%   |
| Toshiba America Info Systems     | 9         | 1.71%   |
| KIOXIA                           | 6         | 1.14%   |
| Kingston Technology Company      | 6         | 1.14%   |
| Micron Technology                | 5         | 0.95%   |
| Nvidia                           | 4         | 0.76%   |
| VIA Technologies                 | 3         | 0.57%   |
| Union Memory (Shenzhen)          | 2         | 0.38%   |
| Silicon Image                    | 2         | 0.38%   |
| Micron/Crucial Technology        | 2         | 0.38%   |
| JMicron Technology               | 2         | 0.38%   |
| Solid State Storage Technology   | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Seagate Technology               | 1         | 0.19%   |
| Phison Electronics               | 1         | 0.19%   |
| Lite-On Technology               | 1         | 0.19%   |
| ASMedia Technology               | 1         | 0.19%   |
| ADATA Technology                 | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 55        | 9.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 36        | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 5.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 32        | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 5.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 3.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 3.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 3.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 2.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 2.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 13        | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 2.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 1.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 1.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 1.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 9         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 7         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.2%    |
| SK Hynix BC511                                                                   | 6         | 1.03%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 6         | 1.03%   |
| KIOXIA Non-Volatile memory controller                                            | 6         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.03%   |
| SK Hynix Non-Volatile memory controller                                          | 5         | 0.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.85%   |
| Sandisk PC SN520 NVMe SSD                                                        | 5         | 0.85%   |
| Micron Non-Volatile memory controller                                            | 5         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.68%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.68%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 4         | 0.68%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.51%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.51%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 3         | 0.51%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.51%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 3         | 0.51%   |
| AMD SB600 IDE                                                                    | 3         | 0.51%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.34%   |
| VIA VT8237A SATA 2-Port Controller                                               | 2         | 0.34%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.34%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.34%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 2         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.34%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.34%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.34%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.34%   |
| Intel SSD 660P Series                                                            | 2         | 0.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 0.34%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 365       | 65.18%  |
| NVMe | 93        | 16.61%  |
| IDE  | 78        | 13.93%  |
| RAID | 24        | 4.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 388       | 80.17%  |
| AMD          | 95        | 19.63%  |
| CentaurHauls | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 12        | 2.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 10        | 2.07%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 8         | 1.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 7         | 1.45%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 7         | 1.45%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 6         | 1.24%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 6         | 1.24%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 6         | 1.24%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 6         | 1.24%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 5         | 1.03%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 5         | 1.03%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 5         | 1.03%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 5         | 1.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 5         | 1.03%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 5         | 1.03%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 4         | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 4         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 4         | 0.83%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 4         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 0.83%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 4         | 0.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 0.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 4         | 0.83%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 4         | 0.83%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 4         | 0.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 4         | 0.83%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 4         | 0.83%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 3         | 0.62%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 3         | 0.62%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 3         | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 3         | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 3         | 0.62%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 3         | 0.62%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 3         | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 3         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 3         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 3         | 0.62%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 3         | 0.62%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3         | 0.62%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz            | 3         | 0.62%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 3         | 0.62%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 3         | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 3         | 0.62%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 3         | 0.62%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 0.62%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 3         | 0.62%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G    | 3         | 0.62%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 3         | 0.62%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 2         | 0.41%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 2         | 0.41%   |
| Intel Pentium CPU 2117U @ 1.80GHz               | 2         | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 0.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 2         | 0.41%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 93        | 19.21%  |
| Intel Core i7                  | 80        | 16.53%  |
| Intel Core 2 Duo               | 49        | 10.12%  |
| Intel Core i3                  | 41        | 8.47%   |
| Intel Celeron                  | 34        | 7.02%   |
| Intel Atom                     | 26        | 5.37%   |
| AMD Ryzen 5                    | 24        | 4.96%   |
| Intel Pentium                  | 19        | 3.93%   |
| Other                          | 11        | 2.27%   |
| AMD Ryzen 7                    | 11        | 2.27%   |
| AMD Ryzen 3                    | 8         | 1.65%   |
| Intel Core 2                   | 7         | 1.45%   |
| AMD E1                         | 7         | 1.45%   |
| AMD A6                         | 7         | 1.45%   |
| AMD A4                         | 7         | 1.45%   |
| Intel Pentium Dual-Core        | 6         | 1.24%   |
| AMD A10                        | 6         | 1.24%   |
| Intel Pentium Dual             | 5         | 1.03%   |
| Intel Celeron M                | 5         | 1.03%   |
| Intel Pentium M                | 4         | 0.83%   |
| Intel Genuine                  | 4         | 0.83%   |
| AMD A8                         | 4         | 0.83%   |
| AMD Ryzen 7 PRO                | 3         | 0.62%   |
| Intel Celeron Dual-Core        | 2         | 0.41%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.41%   |
| AMD Turion                     | 2         | 0.41%   |
| AMD Sempron                    | 2         | 0.41%   |
| AMD E                          | 2         | 0.41%   |
| AMD Athlon 64 X2               | 2         | 0.41%   |
| Intel Pentium 4                | 1         | 0.21%   |
| Intel Core m3                  | 1         | 0.21%   |
| Intel Core Duo                 | 1         | 0.21%   |
| Intel Core 2 Extreme           | 1         | 0.21%   |
| CentaurHauls VIA C7            | 1         | 0.21%   |
| AMD V140                       | 1         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.21%   |
| AMD Turion 64 Mobile           | 1         | 0.21%   |
| AMD Ryzen 5 PRO                | 1         | 0.21%   |
| AMD E2                         | 1         | 0.21%   |
| AMD Athlon II Dual-Core        | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 291       | 60.12%  |
| 4      | 136       | 28.1%   |
| 1      | 30        | 6.2%    |
| 6      | 18        | 3.72%   |
| 8      | 9         | 1.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 484       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 283       | 58.47%  |
| 1      | 200       | 41.32%  |
| 8      | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 452       | 92.81%  |
| 32-bit         | 23        | 4.72%   |
| Unknown        | 12        | 2.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 17.6%   |
| 0x206a7    | 37        | 7.4%    |
| 0x40651    | 22        | 4.4%    |
| 0x306a9    | 22        | 4.4%    |
| 0x1067a    | 19        | 3.8%    |
| 0x806ea    | 15        | 3%      |
| 0x306c3    | 15        | 3%      |
| 0x08108102 | 15        | 3%      |
| 0x6fd      | 14        | 2.8%    |
| 0x10676    | 13        | 2.6%    |
| 0x806e9    | 12        | 2.4%    |
| 0x906ea    | 11        | 2.2%    |
| 0x306d4    | 11        | 2.2%    |
| 0x806ec    | 10        | 2%      |
| 0x506c9    | 10        | 2%      |
| 0x30678    | 10        | 2%      |
| 0x406c4    | 9         | 1.8%    |
| 0x406c3    | 9         | 1.8%    |
| 0x106c2    | 9         | 1.8%    |
| 0x20655    | 8         | 1.6%    |
| 0x08108109 | 8         | 1.6%    |
| 0x806c1    | 7         | 1.4%    |
| 0x406e3    | 7         | 1.4%    |
| 0x20652    | 7         | 1.4%    |
| 0x6d8      | 6         | 1.2%    |
| 0x05000119 | 6         | 1.2%    |
| 0x06006705 | 5         | 1%      |
| 0x906e9    | 4         | 0.8%    |
| 0x706e5    | 4         | 0.8%    |
| 0x706a1    | 4         | 0.8%    |
| 0x6fb      | 4         | 0.8%    |
| 0x6f6      | 4         | 0.8%    |
| 0x6ec      | 4         | 0.8%    |
| 0x08600106 | 4         | 0.8%    |
| 0x0810100b | 4         | 0.8%    |
| 0x806eb    | 3         | 0.6%    |
| 0x506e3    | 3         | 0.6%    |
| 0x106e5    | 3         | 0.6%    |
| 0x08600104 | 3         | 0.6%    |
| 0x07030105 | 3         | 0.6%    |
| 0x0600611a | 3         | 0.6%    |
| 0x03000027 | 3         | 0.6%    |
| 0x02000032 | 3         | 0.6%    |
| 0xa0652    | 2         | 0.4%    |
| 0x706a8    | 2         | 0.4%    |
| 0x6f2      | 2         | 0.4%    |
| 0x6e8      | 2         | 0.4%    |
| 0x30661    | 2         | 0.4%    |
| 0x106ca    | 2         | 0.4%    |
| 0x10661    | 2         | 0.4%    |
| 0x07030106 | 2         | 0.4%    |
| 0x06006704 | 2         | 0.4%    |
| 0x02000057 | 2         | 0.4%    |
| 0xf43      | 1         | 0.2%    |
| 0xa0660    | 1         | 0.2%    |
| 0x906ed    | 1         | 0.2%    |
| 0x806d1    | 1         | 0.2%    |
| 0x6fa      | 1         | 0.2%    |
| 0x695      | 1         | 0.2%    |
| 0x0a50000c | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 65        | 13.43%  |
| SandyBridge     | 41        | 8.47%   |
| Haswell         | 41        | 8.47%   |
| Penryn          | 40        | 8.26%   |
| Core            | 33        | 6.82%   |
| Silvermont      | 30        | 6.2%    |
| IvyBridge       | 30        | 6.2%    |
| Zen+            | 27        | 5.58%   |
| Westmere        | 18        | 3.72%   |
| Skylake         | 14        | 2.89%   |
| P6              | 13        | 2.69%   |
| Bonnell         | 13        | 2.69%   |
| Excavator       | 12        | 2.48%   |
| Broadwell       | 12        | 2.48%   |
| Zen 2           | 11        | 2.27%   |
| Goldmont        | 10        | 2.07%   |
| Zen             | 8         | 1.65%   |
| TigerLake       | 8         | 1.65%   |
| Bobcat          | 8         | 1.65%   |
| Puma            | 7         | 1.45%   |
| IceLake         | 6         | 1.24%   |
| Goldmont plus   | 6         | 1.24%   |
| K8 Hammer       | 5         | 1.03%   |
| K8 & K10 hybrid | 5         | 1.03%   |
| K10 Llano       | 4         | 0.83%   |
| CometLake       | 4         | 0.83%   |
| Piledriver      | 3         | 0.62%   |
| Nehalem         | 3         | 0.62%   |
| Zen 3           | 2         | 0.41%   |
| K10             | 2         | 0.41%   |
| NetBurst        | 1         | 0.21%   |
| Jaguar          | 1         | 0.21%   |
| Unknown         | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 320       | 53.87%  |
| AMD                              | 150       | 25.25%  |
| Nvidia                           | 120       | 20.2%   |
| VIA Technologies                 | 3         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 5.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 3.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 2.98%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 2.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 2.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 2.19%   |
| Intel HD Graphics 620                                                                    | 13        | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.88%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.72%   |
| AMD Renoir                                                                               | 11        | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.41%   |
| Intel HD Graphics 500                                                                    | 9         | 1.41%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 8         | 1.25%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.1%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 1.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.94%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 6         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.78%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.78%   |
| Intel HD Graphics 530                                                                    | 5         | 0.78%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 5         | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 0.63%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.63%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.63%   |
| Intel HD Graphics 630                                                                    | 4         | 0.63%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.63%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.47%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.47%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.47%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.47%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 3         | 0.47%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 0.47%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.47%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 0.47%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                               | 3         | 0.47%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.47%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 3         | 0.47%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 213       | 43.92%  |
| 1 x AMD        | 104       | 21.44%  |
| Intel + Nvidia | 79        | 16.29%  |
| 1 x Nvidia     | 38        | 7.84%   |
| Intel + AMD    | 28        | 5.77%   |
| 2 x AMD        | 15        | 3.09%   |
| 1 x VIA        | 3         | 0.62%   |
| AMD + Nvidia   | 3         | 0.62%   |
| Other          | 1         | 0.21%   |
| 1 x SiS        | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 429       | 87.91%  |
| Proprietary | 45        | 9.22%   |
| Unknown     | 14        | 2.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 259       | 52.01%  |
| 0.01-0.5   | 90        | 18.07%  |
| 1.01-2.0   | 73        | 14.66%  |
| 0.51-1.0   | 38        | 7.63%   |
| 3.01-4.0   | 32        | 6.43%   |
| 5.01-6.0   | 5         | 1%      |
| 2.01-3.0   | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 92        | 18.22%  |
| LG Display              | 89        | 17.62%  |
| BOE                     | 69        | 13.66%  |
| Chimei Innolux          | 62        | 12.28%  |
| Samsung Electronics     | 61        | 12.08%  |
| Chi Mei Optoelectronics | 19        | 3.76%   |
| Goldstar                | 15        | 2.97%   |
| LG Philips              | 13        | 2.57%   |
| Dell                    | 12        | 2.38%   |
| Lenovo                  | 11        | 2.18%   |
| CPT                     | 7         | 1.39%   |
| Apple                   | 7         | 1.39%   |
| HannStar                | 5         | 0.99%   |
| Sharp                   | 4         | 0.79%   |
| PANDA                   | 4         | 0.79%   |
| AOC                     | 4         | 0.79%   |
| Vestel Elektronik       | 3         | 0.59%   |
| Sony                    | 3         | 0.59%   |
| Quanta Display          | 3         | 0.59%   |
| InfoVision              | 3         | 0.59%   |
| Philips                 | 2         | 0.4%    |
| Iiyama                  | 2         | 0.4%    |
| CSO                     | 2         | 0.4%    |
| ZLX                     | 1         | 0.2%    |
| TSL                     | 1         | 0.2%    |
| Toshiba                 | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| Nvidia                  | 1         | 0.2%    |
| LPL                     | 1         | 0.2%    |
| LGD                     | 1         | 0.2%    |
| JRY                     | 1         | 0.2%    |
| InnoLux Display         | 1         | 0.2%    |
| Hewlett-Packard         | 1         | 0.2%    |
| Eizo                    | 1         | 0.2%    |
| BenQ                    | 1         | 0.2%    |
| ASUSTek Computer        | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.97%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 1.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 6         | 1.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 1.18%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 5         | 0.98%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 4         | 0.79%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.79%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.79%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.79%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.79%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch     | 3         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 3         | 0.59%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch    | 3         | 0.59%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 3         | 0.59%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.59%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 3         | 0.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.59%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.59%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.59%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.59%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.59%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch        | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.39%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.39%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 2         | 0.39%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 2         | 0.39%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch            | 2         | 0.39%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.39%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.39%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.39%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch             | 2         | 0.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.39%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 2         | 0.39%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.39%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                    | 2         | 0.39%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 175       | 36.38%  |
| 1920x1080 (FHD)    | 173       | 35.97%  |
| 1280x800 (WXGA)    | 45        | 9.36%   |
| 1600x900 (HD+)     | 21        | 4.37%   |
| 1440x900 (WXGA+)   | 12        | 2.49%   |
| 3840x2160 (4K)     | 9         | 1.87%   |
| 1024x600           | 9         | 1.87%   |
| 2560x1440 (QHD)    | 8         | 1.66%   |
| 1280x1024 (SXGA)   | 5         | 1.04%   |
| 1024x768 (XGA)     | 5         | 1.04%   |
| 1920x1200 (WUXGA)  | 4         | 0.83%   |
| 1360x768           | 3         | 0.62%   |
| 2160x1440          | 2         | 0.42%   |
| 1600x1200          | 2         | 0.42%   |
| 3200x1800 (QHD+)   | 1         | 0.21%   |
| 2880x1800          | 1         | 0.21%   |
| 2624x900           | 1         | 0.21%   |
| 2560x1600          | 1         | 0.21%   |
| 2560x1080          | 1         | 0.21%   |
| 1680x945           | 1         | 0.21%   |
| 1680x1050 (WSXGA+) | 1         | 0.21%   |
| 1024x576           | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 266       | 52.67%  |
| 13      | 53        | 10.5%   |
| 14      | 45        | 8.91%   |
| 17      | 38        | 7.52%   |
| 27      | 13        | 2.57%   |
| 21      | 11        | 2.18%   |
| 11      | 11        | 2.18%   |
| 23      | 10        | 1.98%   |
| 10      | 10        | 1.98%   |
| 12      | 9         | 1.78%   |
| 24      | 6         | 1.19%   |
| Unknown | 6         | 1.19%   |
| 84      | 4         | 0.79%   |
| 18      | 4         | 0.79%   |
| 54      | 3         | 0.59%   |
| 8       | 3         | 0.59%   |
| 33      | 2         | 0.4%    |
| 31      | 2         | 0.4%    |
| 20      | 2         | 0.4%    |
| 72      | 1         | 0.2%    |
| 49      | 1         | 0.2%    |
| 34      | 1         | 0.2%    |
| 25      | 1         | 0.2%    |
| 22      | 1         | 0.2%    |
| 19      | 1         | 0.2%    |
| 16      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 341       | 67.93%  |
| 201-300     | 53        | 10.56%  |
| 351-400     | 39        | 7.77%   |
| 501-600     | 27        | 5.38%   |
| 401-500     | 18        | 3.59%   |
| Unknown     | 6         | 1.2%    |
| 1501-2000   | 5         | 1%      |
| 1001-1500   | 4         | 0.8%    |
| 701-800     | 3         | 0.6%    |
| 601-700     | 3         | 0.6%    |
| 101-200     | 3         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 376       | 82.1%   |
| 16/10   | 62        | 13.54%  |
| 4/3     | 7         | 1.53%   |
| 5/4     | 5         | 1.09%   |
| Unknown | 4         | 0.87%   |
| 3/2     | 3         | 0.66%   |
| 21/9    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 265       | 52.48%  |
| 81-90          | 80        | 15.84%  |
| 201-250        | 26        | 5.15%   |
| 121-130        | 26        | 5.15%   |
| 71-80          | 18        | 3.56%   |
| 301-350        | 13        | 2.57%   |
| 51-60          | 11        | 2.18%   |
| 41-50          | 10        | 1.98%   |
| More than 1000 | 9         | 1.78%   |
| 61-70          | 9         | 1.78%   |
| 131-140        | 9         | 1.78%   |
| 151-200        | 6         | 1.19%   |
| 141-150        | 6         | 1.19%   |
| Unknown        | 6         | 1.19%   |
| 351-500        | 5         | 0.99%   |
| 1-40           | 3         | 0.59%   |
| 251-300        | 1         | 0.2%    |
| 111-120        | 1         | 0.2%    |
| 91-100         | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 178       | 35.74%  |
| 121-160       | 174       | 34.94%  |
| 51-100        | 108       | 21.69%  |
| 161-240       | 20        | 4.02%   |
| More than 240 | 6         | 1.2%    |
| 1-50          | 6         | 1.2%    |
| Unknown       | 6         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 423       | 85.11%  |
| 2     | 55        | 11.07%  |
| 0     | 14        | 2.82%   |
| 3     | 5         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 284       | 35.28%  |
| Intel                                 | 218       | 27.08%  |
| Qualcomm Atheros                      | 122       | 15.16%  |
| Broadcom                              | 64        | 7.95%   |
| Marvell Technology Group              | 20        | 2.48%   |
| Broadcom Limited                      | 17        | 2.11%   |
| Ralink                                | 14        | 1.74%   |
| TP-Link                               | 8         | 0.99%   |
| Ralink Technology                     | 5         | 0.62%   |
| Qualcomm Atheros Communications       | 4         | 0.5%    |
| Ericsson Business Mobile Networks     | 4         | 0.5%    |
| Sierra Wireless                       | 3         | 0.37%   |
| Nvidia                                | 3         | 0.37%   |
| MEDIATEK                              | 3         | 0.37%   |
| JMicron Technology                    | 3         | 0.37%   |
| Huawei Technologies                   | 3         | 0.37%   |
| Hewlett-Packard                       | 3         | 0.37%   |
| Dell                                  | 3         | 0.37%   |
| VIA Technologies                      | 2         | 0.25%   |
| NetGear                               | 2         | 0.25%   |
| Edimax Technology                     | 2         | 0.25%   |
| D-Link                                | 2         | 0.25%   |
| Xiaomi                                | 1         | 0.12%   |
| Toshiba                               | 1         | 0.12%   |
| Sitecom Europe                        | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.12%   |
| Samsung Electronics                   | 1         | 0.12%   |
| Linksys                               | 1         | 0.12%   |
| InProComm                             | 1         | 0.12%   |
| Google                                | 1         | 0.12%   |
| Fujitsu Siemens Computers             | 1         | 0.12%   |
| Belkin Components                     | 1         | 0.12%   |
| Attansic Technology                   | 1         | 0.12%   |
| ASUSTek Computer                      | 1         | 0.12%   |
| ASIX Electronics                      | 1         | 0.12%   |
| AMD                                   | 1         | 0.12%   |
| Accton Technology                     | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 142       | 14.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 93        | 9.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 22        | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.09%   |
| Intel Wireless 8265 / 8275                                              | 20        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 17        | 1.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 1.57%   |
| Intel Wireless 3165                                                     | 15        | 1.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 1.36%   |
| Intel Wireless 7260                                                     | 12        | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.05%   |
| Intel WiFi Link 5100                                                    | 10        | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.94%   |
| Intel Wireless 7265                                                     | 9         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 0.94%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.94%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 0.73%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 0.73%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.63%   |
| Intel Wireless 3160                                                     | 6         | 0.63%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.63%   |
| Intel Wireless 8260                                                     | 5         | 0.52%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 5         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 5         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.31%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.31%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.31%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 3         | 0.31%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                    | 3         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 207       | 40.35%  |
| Qualcomm Atheros                      | 106       | 20.66%  |
| Realtek Semiconductor                 | 96        | 18.71%  |
| Broadcom                              | 45        | 8.77%   |
| Ralink                                | 14        | 2.73%   |
| Broadcom Limited                      | 8         | 1.56%   |
| TP-Link                               | 7         | 1.36%   |
| Ralink Technology                     | 5         | 0.97%   |
| Qualcomm Atheros Communications       | 4         | 0.78%   |
| Sierra Wireless                       | 2         | 0.39%   |
| NetGear                               | 2         | 0.39%   |
| MediaTek                              | 2         | 0.39%   |
| Hewlett-Packard                       | 2         | 0.39%   |
| Edimax Technology                     | 2         | 0.39%   |
| D-Link                                | 2         | 0.39%   |
| Sitecom Europe                        | 1         | 0.19%   |
| Linksys                               | 1         | 0.19%   |
| InProComm                             | 1         | 0.19%   |
| Fujitsu Siemens Computers             | 1         | 0.19%   |
| Dell                                  | 1         | 0.19%   |
| Belkin Components                     | 1         | 0.19%   |
| ASUSTek Computer                      | 1         | 0.19%   |
| Accton Technology                     | 1         | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 4.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 4.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 22        | 4.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 3.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 3.89%   |
| Intel Wireless 8265 / 8275                                              | 20        | 3.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 3.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 3.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.92%   |
| Intel Wireless 3165                                                     | 15        | 2.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 2.53%   |
| Intel Wireless 7260                                                     | 12        | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.95%   |
| Intel WiFi Link 5100                                                    | 10        | 1.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.95%   |
| Intel Wireless 7265                                                     | 9         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.75%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 1.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.36%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.17%   |
| Intel Wireless 3160                                                     | 6         | 1.17%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.17%   |
| Intel Wireless 8260                                                     | 5         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.58%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.58%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 3         | 0.58%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.58%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 2         | 0.39%   |
| Sierra Wireless MC8305 Modem                                            | 2         | 0.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.39%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 2         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.39%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.39%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.39%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 256       | 60.81%  |
| Intel                            | 66        | 15.68%  |
| Qualcomm Atheros                 | 28        | 6.65%   |
| Broadcom                         | 23        | 5.46%   |
| Marvell Technology Group         | 20        | 4.75%   |
| Broadcom Limited                 | 12        | 2.85%   |
| Nvidia                           | 3         | 0.71%   |
| JMicron Technology               | 3         | 0.71%   |
| VIA Technologies                 | 2         | 0.48%   |
| Xiaomi                           | 1         | 0.24%   |
| TP-Link                          | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Sierra Wireless                  | 1         | 0.24%   |
| Samsung Electronics              | 1         | 0.24%   |
| Huawei Technologies              | 1         | 0.24%   |
| Attansic Technology              | 1         | 0.24%   |
| ASIX Electronics                 | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 142       | 33.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 93        | 21.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 4.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 2.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 2.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 1.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.42%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.18%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 1.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.71%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 0.71%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 3         | 0.71%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.71%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.71%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 3         | 0.71%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.47%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.47%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.47%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.47%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.47%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 2         | 0.47%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.47%   |
| Broadcom BCM4401 100Base-T                                                     | 2         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.24%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.24%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.24%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.24%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.24%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.24%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.24%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.24%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.24%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 477       | 52.3%   |
| Ethernet | 417       | 45.72%  |
| Modem    | 18        | 1.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 406       | 65.17%  |
| Ethernet | 215       | 34.51%  |
| Modem    | 2         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 392       | 80.49%  |
| 1     | 79        | 16.22%  |
| 0     | 12        | 2.46%   |
| 3     | 4         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 397       | 79.72%  |
| Yes  | 101       | 20.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 33.89%  |
| Realtek Semiconductor           | 56        | 15.56%  |
| Qualcomm Atheros Communications | 42        | 11.67%  |
| Broadcom                        | 23        | 6.39%   |
| IMC Networks                    | 15        | 4.17%   |
| Toshiba                         | 14        | 3.89%   |
| Foxconn / Hon Hai               | 14        | 3.89%   |
| Lite-On Technology              | 12        | 3.33%   |
| Hewlett-Packard                 | 12        | 3.33%   |
| Ralink                          | 8         | 2.22%   |
| Cambridge Silicon Radio         | 8         | 2.22%   |
| Foxconn International           | 6         | 1.67%   |
| Apple                           | 6         | 1.67%   |
| Alps Electric                   | 5         | 1.39%   |
| Realtek                         | 4         | 1.11%   |
| Dell                            | 4         | 1.11%   |
| Ralink Technology               | 3         | 0.83%   |
| Askey Computer                  | 3         | 0.83%   |
| ASUSTek Computer                | 2         | 0.56%   |
| Syntek                          | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 64        | 17.78%  |
| Realtek Bluetooth Radio                             | 32        | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 4.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 3.61%   |
| Intel AX201 Bluetooth                               | 12        | 3.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 2.5%    |
| Ralink RT3290 Bluetooth                             | 8         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 2.22%   |
| Intel AX200 Bluetooth                               | 8         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 2.22%   |
| Realtek RTL8723B Bluetooth                          | 7         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.39%   |
| Toshiba RT Bluetooth Radio                          | 4         | 1.11%   |
| Toshiba Bluetooth Device                            | 4         | 1.11%   |
| Realtek Bluetooth Radio                             | 4         | 1.11%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.11%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.11%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.11%   |
| Realtek RTL8723A Bluetooth                          | 3         | 0.83%   |
| Lite-On Bluetooth Device                            | 3         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.83%   |
| Intel Bluetooth Device                              | 3         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.83%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.83%   |
| Askey Bluetooth Device                              | 3         | 0.83%   |
| Apple Bluetooth Host Controller                     | 3         | 0.83%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.56%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 2         | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 2         | 0.56%   |
| IMC Networks Bluetooth Device                       | 2         | 0.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 2         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.56%   |
| Broadcom Bluetooth 2.1 Device                       | 2         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.56%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.56%   |
| Alps Electric Bluetooth Adapter                     | 2         | 0.56%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 0.56%   |
| Toshiba BCM43142A0                                  | 1         | 0.28%   |
| Toshiba Askey for                                   | 1         | 0.28%   |
| Syntek 802.11g + Bluetooth Wireless Adapter         | 1         | 0.28%   |
| Realtek 802.11n WLAN Adapter                        | 1         | 0.28%   |
| Ralink CSR BS8510                                   | 1         | 0.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.28%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.28%   |
| IMC Networks Broadcom Bluetooth 2.1                 | 1         | 0.28%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.28%   |
| IMC Networks Bluetooth Module                       | 1         | 0.28%   |
| IMC Networks Bluetooth                              | 1         | 0.28%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 371       | 66.49%  |
| AMD                              | 116       | 20.79%  |
| Nvidia                           | 49        | 8.78%   |
| C-Media Electronics              | 4         | 0.72%   |
| VIA Technologies                 | 3         | 0.54%   |
| Creative Technology              | 3         | 0.54%   |
| Barco Display Systems            | 3         | 0.54%   |
| Logitech                         | 2         | 0.36%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| Guillemot                        | 1         | 0.18%   |
| GN Netcom                        | 1         | 0.18%   |
| CMX Systems                      | 1         | 0.18%   |
| bestechnic                       | 1         | 0.18%   |
| BEHRINGER International          | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 6.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 5.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 40        | 5.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 37        | 5.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 4.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 4.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 3.6%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 3.46%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 3.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 3.31%   |
| AMD FCH Azalia Controller                                                                         | 22        | 3.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 1.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.15%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.01%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.01%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.72%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.58%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.43%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.43%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.29%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.29%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.29%   |
| Barco Display Systems USBGH1XK                                                                    | 2         | 0.29%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 2         | 0.29%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.29%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.29%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 64        | 26.56%  |
| Samsung Electronics | 64        | 26.56%  |
| Micron Technology   | 26        | 10.79%  |
| Unknown             | 20        | 8.3%    |
| Kingston            | 18        | 7.47%   |
| Ramaxel Technology  | 9         | 3.73%   |
| Crucial             | 9         | 3.73%   |
| Transcend           | 5         | 2.07%   |
| Elpida              | 5         | 2.07%   |
| Corsair             | 5         | 2.07%   |
| Unknown (ABCD)      | 4         | 1.66%   |
| A-DATA Technology   | 4         | 1.66%   |
| Nanya Technology    | 3         | 1.24%   |
| Toshiba             | 1         | 0.41%   |
| Team                | 1         | 0.41%   |
| Infineon            | 1         | 0.41%   |
| G.Skill             | 1         | 0.41%   |
| Apacer              | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 1.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.93%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 1.54%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.54%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 1.16%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 1.16%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.16%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.16%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.77%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 2         | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 0.77%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                   | 2         | 0.77%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s               | 2         | 0.77%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.77%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.77%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.77%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.77%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.77%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 2         | 0.77%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.77%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.77%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                       | 2         | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 0.77%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 2         | 0.77%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.77%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.77%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s             | 2         | 0.77%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| Nanya RAM NT2GT64U8HD0BN-3C 2GB SODIMM DDR 667MT/s                  | 2         | 0.77%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 2         | 0.77%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.77%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.77%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3                       | 2         | 0.77%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 2         | 0.77%   |
| Crucial RAM CT8G4SFS824A.C8FDD1 8GB SODIMM DDR4 2400MT/s            | 2         | 0.77%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 2         | 0.77%   |
| Corsair RAM CMSO4GX3M1C1600C11 4GB SODIMM DDR3 1600MT/s             | 2         | 0.77%   |
| Unknown RAM Module 8GB SODIMM DDR3 667MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3 667MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR2                               | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 400MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR                                | 1         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 40%     |
| DDR3    | 80        | 38.1%   |
| DDR2    | 24        | 11.43%  |
| LPDDR4  | 10        | 4.76%   |
| SDRAM   | 5         | 2.38%   |
| LPDDR3  | 3         | 1.43%   |
| DDR     | 2         | 0.95%   |
| DRAM    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 193       | 92.79%  |
| Row Of Chips | 11        | 5.29%   |
| DIMM         | 3         | 1.44%   |
| Unknown      | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 80        | 34.78%  |
| 8192  | 74        | 32.17%  |
| 2048  | 42        | 18.26%  |
| 16384 | 17        | 7.39%   |
| 1024  | 12        | 5.22%   |
| 512   | 4         | 1.74%   |
| 256   | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 58        | 25.55%  |
| 2667    | 46        | 20.26%  |
| 3200    | 21        | 9.25%   |
| 2400    | 21        | 9.25%   |
| 1334    | 11        | 4.85%   |
| 667     | 11        | 4.85%   |
| Unknown | 11        | 4.85%   |
| 2133    | 8         | 3.52%   |
| 1333    | 8         | 3.52%   |
| 1067    | 6         | 2.64%   |
| 3266    | 5         | 2.2%    |
| 1066    | 4         | 1.76%   |
| 533     | 4         | 1.76%   |
| 4267    | 3         | 1.32%   |
| 4199    | 3         | 1.32%   |
| 800     | 2         | 0.88%   |
| 2048    | 1         | 0.44%   |
| 1867    | 1         | 0.44%   |
| 1639    | 1         | 0.44%   |
| 975     | 1         | 0.44%   |
| 400     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 3         | 33.33%  |
| Konica Minolta      | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 3         | 33.33%  |
| Konica Minolta magicolor 1680MF scan | 1         | 11.11%  |
| HP OfficeJet 6200                    | 1         | 11.11%  |
| HP LaserJet P1102                    | 1         | 11.11%  |
| HP Laser 107a                        | 1         | 11.11%  |
| HP Color Laser 150nw                 | 1         | 11.11%  |
| Brother HL-2030 Laser Printer        | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 1200 CU Plus | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 99        | 23.97%  |
| IMC Networks                           | 45        | 10.9%   |
| Realtek Semiconductor                  | 42        | 10.17%  |
| Acer                                   | 37        | 8.96%   |
| Microdia                               | 33        | 7.99%   |
| Suyin                                  | 29        | 7.02%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 4.12%   |
| Sunplus Innovation Technology          | 16        | 3.87%   |
| Ricoh                                  | 14        | 3.39%   |
| Quanta                                 | 13        | 3.15%   |
| Lite-On Technology                     | 11        | 2.66%   |
| Alcor Micro                            | 10        | 2.42%   |
| Syntek                                 | 7         | 1.69%   |
| Silicon Motion                         | 4         | 0.97%   |
| Logitech                               | 4         | 0.97%   |
| Lenovo                                 | 4         | 0.97%   |
| Apple                                  | 4         | 0.97%   |
| Z-Star Microelectronics                | 3         | 0.73%   |
| Samsung Electronics                    | 3         | 0.73%   |
| Luxvisions Innotech Limited            | 3         | 0.73%   |
| Genesys Logic                          | 2         | 0.48%   |
| ALi                                    | 2         | 0.48%   |
| Sonix Technology                       | 1         | 0.24%   |
| Primax Electronics                     | 1         | 0.24%   |
| Pixart Imaging                         | 1         | 0.24%   |
| OmniVision Technologies                | 1         | 0.24%   |
| Leap Motion                            | 1         | 0.24%   |
| Intel                                  | 1         | 0.24%   |
| Importek                               | 1         | 0.24%   |
| Generalplus Technology                 | 1         | 0.24%   |
| GEMBIRD                                | 1         | 0.24%   |
| eMPIA Technology                       | 1         | 0.24%   |
| Arkmicro Technologies                  | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 17        | 4.12%   |
| Microdia Integrated_Webcam_HD                       | 13        | 3.15%   |
| IMC Networks Integrated Camera                      | 12        | 2.91%   |
| Chicony Integrated Camera                           | 12        | 2.91%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 2.66%   |
| Chicony HP Truevision HD                            | 10        | 2.42%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 2.18%   |
| Realtek USB Camera                                  | 8         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 7         | 1.69%   |
| Acer Lenovo EasyCamera                              | 7         | 1.69%   |
| Chicony USB 2.0 Camera                              | 6         | 1.45%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 1.45%   |
| Acer BisonCam, NB Pro                               | 6         | 1.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.21%   |
| Chicony HP Webcam                                   | 5         | 1.21%   |
| Syntek Integrated Camera                            | 4         | 0.97%   |
| Suyin Integrated_Webcam_HD                          | 4         | 0.97%   |
| Realtek Lenovo EasyCamera                           | 4         | 0.97%   |
| Quanta VGA WebCam                                   | 4         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.97%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.97%   |
| Chicony HD Webcam                                   | 4         | 0.97%   |
| Alcor Micro USB 2.0 Camera                          | 4         | 0.97%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 3         | 0.73%   |
| Suyin HP Truevision HD                              | 3         | 0.73%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 3         | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.73%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 0.73%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 3         | 0.73%   |
| Ricoh USB2.0 Camera                                 | 3         | 0.73%   |
| Realtek USB2.0 HD UVC WebCam                        | 3         | 0.73%   |
| Realtek Integrated Webcam                           | 3         | 0.73%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.73%   |
| Logitech HD Pro Webcam C920                         | 3         | 0.73%   |
| Lite-On Integrated Camera                           | 3         | 0.73%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.73%   |
| Chicony VGA WebCam                                  | 3         | 0.73%   |
| Chicony HP Integrated Webcam                        | 3         | 0.73%   |
| Chicony HP HD Webcam                                | 3         | 0.73%   |
| Chicony EasyCamera                                  | 3         | 0.73%   |
| Chicony CKF7063 Webcam (HP)                         | 3         | 0.73%   |
| Alcor Micro HP Webcam-101                           | 3         | 0.73%   |
| Acer USB2.0 Camera                                  | 3         | 0.73%   |
| Acer SunplusIT Integrated Camera                    | 3         | 0.73%   |
| Acer Lenovo Integrated Webcam                       | 3         | 0.73%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.48%   |
| Suyin USB 2.0 Camera                                | 2         | 0.48%   |
| Suyin Acer HD Crystal Eye webcam                    | 2         | 0.48%   |
| Sunplus Integrated_Webcam_FHD                       | 2         | 0.48%   |
| Silicon Motion Lenovo EasyCamera                    | 2         | 0.48%   |
| Ricoh Sony Vaio Integrated Webcam                   | 2         | 0.48%   |
| Realtek Integrated Webcam HD                        | 2         | 0.48%   |
| Quanta HP Webcam                                    | 2         | 0.48%   |
| Quanta HD Webcam                                    | 2         | 0.48%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 0.48%   |
| Microdia Integrated Webcam                          | 2         | 0.48%   |
| Microdia HP Integrated Webcam                       | 2         | 0.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 27.94%  |
| Synaptics                  | 14        | 20.59%  |
| AuthenTec                  | 12        | 17.65%  |
| Upek                       | 10        | 14.71%  |
| Shenzhen Goodix Technology | 9         | 13.24%  |
| Elan Microelectronics      | 2         | 2.94%   |
| STMicroelectronics         | 1         | 1.47%   |
| LighTuning Technology      | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 13.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 8.82%   |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 8.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 8.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.88%   |
| Synaptics  WBDI                                                            | 3         | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.41%   |
| AuthenTec AES2810                                                          | 3         | 4.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.94%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.94%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.94%   |
| Unknown                                                                    | 2         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.47%   |
| Validity Sensors VFS491                                                    | 1         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.47%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.47%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.47%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.47%   |
| AuthenTec AES1600                                                          | 1         | 1.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 54.05%  |
| Alcor Micro | 7         | 18.92%  |
| O2 Micro    | 4         | 10.81%  |
| Upek        | 3         | 8.11%   |
| Lenovo      | 2         | 5.41%   |
| Yubico.com  | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 8         | 21.62%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 18.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 18.92%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10.81%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 8.11%   |
| Broadcom 5880                                                                | 3         | 8.11%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.41%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 311       | 62.7%   |
| 1     | 149       | 30.04%  |
| 2     | 31        | 6.25%   |
| 3     | 4         | 0.81%   |
| 6     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 68        | 31.05%  |
| Chipcard                 | 33        | 15.07%  |
| Graphics card            | 31        | 14.16%  |
| Net/wireless             | 27        | 12.33%  |
| Bluetooth                | 17        | 7.76%   |
| Multimedia controller    | 11        | 5.02%   |
| Camera                   | 6         | 2.74%   |
| Storage                  | 5         | 2.28%   |
| Modem                    | 5         | 2.28%   |
| Flash memory             | 4         | 1.83%   |
| Communication controller | 3         | 1.37%   |
| Sound                    | 2         | 0.91%   |
| Net/ethernet             | 2         | 0.91%   |
| Card reader              | 2         | 0.91%   |
| Tv card                  | 1         | 0.46%   |
| Network                  | 1         | 0.46%   |
| Firewire controller      | 1         | 0.46%   |


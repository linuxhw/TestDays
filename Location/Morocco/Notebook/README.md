Linux in Morocco - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 303

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| HP            | Bloog                       | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| Acer          | Nitro AN515-53              | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| Dell          | Latitude 5540               | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Dell          | Latitude 5289               | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| SINTRONES     | AMB-5000G1                  | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| Dell          | Latitude 5490               | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | Pavilion g6                 | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Acer          | Aspire One 522              | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Apple         | MacBookPro13,3              | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| HP            | Pavilion Power Laptop 15... | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| Razer         | Blade Pro 17 (2019)         | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| HP            | Pavilion Power Laptop 15... | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 15                          | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| HP            | Notebook                    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| HP            | Pavilion Sleekbook 15       | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| HP            | Pavilion dv7                | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| Dell          | Latitude E6440              | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| HP            | 650                         | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| Dell          | Latitude E6440              | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| Dell          | Latitude E5270              | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| Lenovo        | G50-70 20351                | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 250 G3                      | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Dell          | Inspiron 3521               | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| ASUSTek       | F5VL                        | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 34        | 15.25%  |
| Ubuntu 22.04       | 16        | 7.17%   |
| Ubuntu 18.04       | 13        | 5.83%   |
| KDE neon 20.04     | 10        | 4.48%   |
| OpenMandriva 4.3   | 9         | 4.04%   |
| Debian 11          | 9         | 4.04%   |
| Pop!_OS 22.04      | 7         | 3.14%   |
| OpenMandriva 4.2   | 6         | 2.69%   |
| Linux Mint 20.2    | 6         | 2.69%   |
| Zorin 16           | 5         | 2.24%   |
| OpenMandriva 23.01 | 5         | 2.24%   |
| Ubuntu Unity 16.04 | 4         | 1.79%   |
| Ubuntu 20.10       | 4         | 1.79%   |
| Ubuntu 19.10       | 4         | 1.79%   |
| Linux Mint 20.3    | 4         | 1.79%   |
| ArcoLinux Rolling  | 4         | 1.79%   |
| Arch               | 4         | 1.79%   |
| Manjaro            | 3         | 1.35%   |
| Linux Mint 21.1    | 3         | 1.35%   |
| Fedora 38          | 3         | 1.35%   |
| Xubuntu 20.04      | 2         | 0.9%    |
| Xero Rolling       | 2         | 0.9%    |
| Void Linux         | 2         | 0.9%    |
| Ubuntu 23.04       | 2         | 0.9%    |
| Ubuntu 21.10       | 2         | 0.9%    |
| Ubuntu 21.04       | 2         | 0.9%    |
| Pop!_OS 21.10      | 2         | 0.9%    |
| Linux Mint 21      | 2         | 0.9%    |
| Linux Mint 19.3    | 2         | 0.9%    |
| Kali 2019.4        | 2         | 0.9%    |
| Fedora 37          | 2         | 0.9%    |
| Fedora 36          | 2         | 0.9%    |
| Arch Rolling       | 2         | 0.9%    |
| Zorin 15           | 1         | 0.45%   |
| Ubuntu Unity 20.04 | 1         | 0.45%   |
| Ubuntu MATE 22.10  | 1         | 0.45%   |
| Ubuntu MATE 20.04  | 1         | 0.45%   |
| Ubuntu 19.04       | 1         | 0.45%   |
| Ubuntu 16.04       | 1         | 0.45%   |
| Ubuntu             | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 74        | 35.07%  |
| OpenMandriva | 19        | 9%      |
| Linux Mint   | 17        | 8.06%   |
| Pop!_OS      | 11        | 5.21%   |
| KDE neon     | 11        | 5.21%   |
| Debian       | 11        | 5.21%   |
| Fedora       | 8         | 3.79%   |
| Kali         | 7         | 3.32%   |
| Zorin        | 6         | 2.84%   |
| Manjaro      | 6         | 2.84%   |
| Arch         | 6         | 2.84%   |
| Ubuntu Unity | 5         | 2.37%   |
| ArcoLinux    | 4         | 1.9%    |
| Endless      | 3         | 1.42%   |
| Elementary   | 3         | 1.42%   |
| Xubuntu      | 2         | 0.95%   |
| Xero         | 2         | 0.95%   |
| Void Linux   | 2         | 0.95%   |
| Ubuntu MATE  | 2         | 0.95%   |
| SteamOS      | 2         | 0.95%   |
| openSUSE     | 2         | 0.95%   |
| EndeavourOS  | 2         | 0.95%   |
| RHEL         | 1         | 0.47%   |
| Parrot       | 1         | 0.47%   |
| Nobara       | 1         | 0.47%   |
| CentOS       | 1         | 0.47%   |
| BunsenLabs   | 1         | 0.47%   |
| blendOS      | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 3.81%   |
| 5.10.14-desktop-1omv4002 | 6         | 2.54%   |
| 6.1.1-desktop-1omv2290   | 5         | 2.12%   |
| 5.13.0-40-generic        | 5         | 2.12%   |
| 6.2.0-33-generic         | 4         | 1.69%   |
| 5.8.0-43-generic         | 4         | 1.69%   |
| 5.4.0-58-generic         | 4         | 1.69%   |
| 5.4.0-48-generic         | 4         | 1.69%   |
| 5.4.0-42-generic         | 3         | 1.27%   |
| 5.3.0-40-generic         | 3         | 1.27%   |
| 5.17.5-76051705-generic  | 3         | 1.27%   |
| 5.13.0-27-generic        | 3         | 1.27%   |
| 5.11.0-37-generic        | 3         | 1.27%   |
| 6.2.6-76060206-generic   | 2         | 0.85%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.85%   |
| 5.8.0-48-generic         | 2         | 0.85%   |
| 5.8.0-38-generic         | 2         | 0.85%   |
| 5.8.0-33-generic         | 2         | 0.85%   |
| 5.4.0-96-generic         | 2         | 0.85%   |
| 5.4.0-88-generic         | 2         | 0.85%   |
| 5.4.0-65-generic         | 2         | 0.85%   |
| 5.4.0-37-generic         | 2         | 0.85%   |
| 5.4.0-33-generic         | 2         | 0.85%   |
| 5.4.0-29-generic         | 2         | 0.85%   |
| 5.3.0-kali2-686-pae      | 2         | 0.85%   |
| 5.3.0-51-generic         | 2         | 0.85%   |
| 5.3.0-28-generic         | 2         | 0.85%   |
| 5.19.0-41-generic        | 2         | 0.85%   |
| 5.19.0-38-generic        | 2         | 0.85%   |
| 5.18.19_1                | 2         | 0.85%   |
| 5.15.0-58-generic        | 2         | 0.85%   |
| 5.15.0-53-generic        | 2         | 0.85%   |
| 5.15.0-50-generic        | 2         | 0.85%   |
| 5.15.0-46-generic        | 2         | 0.85%   |
| 5.14.14-arch1-1          | 2         | 0.85%   |
| 5.13.0-19-generic        | 2         | 0.85%   |
| 5.11.0-7612-generic      | 2         | 0.85%   |
| 5.11.0-46-generic        | 2         | 0.85%   |
| 5.11.0-36-generic        | 2         | 0.85%   |
| 5.10.0-21-amd64          | 2         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 15.38%  |
| 5.15.0  | 16        | 7.24%   |
| 5.8.0   | 14        | 6.33%   |
| 5.13.0  | 13        | 5.88%   |
| 5.11.0  | 12        | 5.43%   |
| 4.15.0  | 12        | 5.43%   |
| 5.3.0   | 10        | 4.52%   |
| 5.10.0  | 10        | 4.52%   |
| 5.16.7  | 9         | 4.07%   |
| 5.19.0  | 8         | 3.62%   |
| 5.10.14 | 6         | 2.71%   |
| 5.0.0   | 6         | 2.71%   |
| 6.2.0   | 5         | 2.26%   |
| 6.1.1   | 5         | 2.26%   |
| 6.2.6   | 3         | 1.36%   |
| 5.17.5  | 3         | 1.36%   |
| 4.18.0  | 3         | 1.36%   |
| 6.2.14  | 2         | 0.9%    |
| 6.1.0   | 2         | 0.9%    |
| 5.18.19 | 2         | 0.9%    |
| 5.16.0  | 2         | 0.9%    |
| 5.14.14 | 2         | 0.9%    |
| 4.19.0  | 2         | 0.9%    |
| 6.5.3   | 1         | 0.45%   |
| 6.4.9   | 1         | 0.45%   |
| 6.4.6   | 1         | 0.45%   |
| 6.3.7   | 1         | 0.45%   |
| 6.3.6   | 1         | 0.45%   |
| 6.3.4   | 1         | 0.45%   |
| 6.3.2   | 1         | 0.45%   |
| 6.2.9   | 1         | 0.45%   |
| 6.2.10  | 1         | 0.45%   |
| 6.1.7   | 1         | 0.45%   |
| 6.1.6   | 1         | 0.45%   |
| 6.0.14  | 1         | 0.45%   |
| 6.0.12  | 1         | 0.45%   |
| 6.0.0   | 1         | 0.45%   |
| 5.8.15  | 1         | 0.45%   |
| 5.8.1   | 1         | 0.45%   |
| 5.7.15  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 15.38%  |
| 5.15    | 22        | 9.95%   |
| 5.10    | 17        | 7.69%   |
| 5.8     | 16        | 7.24%   |
| 5.13    | 14        | 6.33%   |
| 5.11    | 14        | 6.33%   |
| 6.2     | 12        | 5.43%   |
| 5.16    | 12        | 5.43%   |
| 4.15    | 12        | 5.43%   |
| 5.19    | 11        | 4.98%   |
| 5.3     | 10        | 4.52%   |
| 6.1     | 9         | 4.07%   |
| 5.17    | 6         | 2.71%   |
| 5.0     | 6         | 2.71%   |
| 6.3     | 4         | 1.81%   |
| 5.18    | 4         | 1.81%   |
| 6.0     | 3         | 1.36%   |
| 5.14    | 3         | 1.36%   |
| 4.18    | 3         | 1.36%   |
| 6.4     | 2         | 0.9%    |
| 4.19    | 2         | 0.9%    |
| 6.5     | 1         | 0.45%   |
| 5.7     | 1         | 0.45%   |
| 4.4     | 1         | 0.45%   |
| 4.14    | 1         | 0.45%   |
| 4.13    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 200       | 96.62%  |
| i686   | 7         | 3.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 108       | 50.7%   |
| KDE5            | 40        | 18.78%  |
| Unknown         | 14        | 6.57%   |
| X-Cinnamon      | 13        | 6.1%    |
| XFCE            | 12        | 5.63%   |
| KDE             | 7         | 3.29%   |
| Unity           | 5         | 2.35%   |
| Pantheon        | 3         | 1.41%   |
| MATE            | 3         | 1.41%   |
| GNOME Flashback | 2         | 0.94%   |
| Cinnamon        | 2         | 0.94%   |
| xmonad          | 1         | 0.47%   |
| sway            | 1         | 0.47%   |
| i3              | 1         | 0.47%   |
| Budgie          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 165       | 77.46%  |
| Wayland | 40        | 18.78%  |
| Unknown | 7         | 3.29%   |
| Tty     | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 48.39%  |
| SDDM    | 35        | 16.13%  |
| GDM     | 31        | 14.29%  |
| GDM3    | 25        | 11.52%  |
| LightDM | 18        | 8.29%   |
| TDM     | 3         | 1.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 119       | 57.21%  |
| fr_FR   | 58        | 27.88%  |
| Unknown | 13        | 6.25%   |
| en_GB   | 8         | 3.85%   |
| de_DE   | 3         | 1.44%   |
| fr_MA   | 1         | 0.48%   |
| fr_BE   | 1         | 0.48%   |
| es_ES   | 1         | 0.48%   |
| en_AG   | 1         | 0.48%   |
| C       | 1         | 0.48%   |
| ar_MA   | 1         | 0.48%   |
| ar_EG   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 124       | 59.33%  |
| EFI  | 85        | 40.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 168       | 80.38%  |
| Overlay | 21        | 10.05%  |
| Btrfs   | 14        | 6.7%    |
| Xfs     | 2         | 0.96%   |
| Tmpfs   | 2         | 0.96%   |
| Unknown | 2         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 49.76%  |
| GPT     | 71        | 33.65%  |
| MBR     | 35        | 16.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 87.02%  |
| Yes       | 27        | 12.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 67.46%  |
| Yes       | 68        | 32.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 66        | 31.88%  |
| Dell                | 37        | 17.87%  |
| Lenovo              | 36        | 17.39%  |
| ASUSTek Computer    | 17        | 8.21%   |
| Acer                | 9         | 4.35%   |
| Toshiba             | 8         | 3.86%   |
| Apple               | 4         | 1.93%   |
| Sony                | 3         | 1.45%   |
| Packard Bell        | 3         | 1.45%   |
| Timi                | 2         | 0.97%   |
| Samsung Electronics | 2         | 0.97%   |
| HUAWEI              | 2         | 0.97%   |
| eMachines           | 2         | 0.97%   |
| Unknown             | 2         | 0.97%   |
| Valve               | 1         | 0.48%   |
| TUXEDO              | 1         | 0.48%   |
| TrekStor            | 1         | 0.48%   |
| SINTRONES           | 1         | 0.48%   |
| Razer               | 1         | 0.48%   |
| Medion              | 1         | 0.48%   |
| Mediacom            | 1         | 0.48%   |
| GPD                 | 1         | 0.48%   |
| Google              | 1         | 0.48%   |
| Gigabyte Technology | 1         | 0.48%   |
| Fujitsu Siemens     | 1         | 0.48%   |
| Clevo               | 1         | 0.48%   |
| Casper              | 1         | 0.48%   |
| American Megatrends | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP EliteBook 8440p                         | 4         | 1.93%   |
| HP Pavilion g6                             | 3         | 1.45%   |
| HP Laptop 15-dw3xxx                        | 3         | 1.45%   |
| HP EliteBook 840 G2                        | 3         | 1.45%   |
| ASUS X540LA                                | 3         | 1.45%   |
| Unknown                                    | 3         | 1.45%   |
| Timi TM1701                                | 2         | 0.97%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.97%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 0.97%   |
| HP ZBook 15                                | 2         | 0.97%   |
| HP ProBook 650 G1                          | 2         | 0.97%   |
| HP ProBook 6470b                           | 2         | 0.97%   |
| HP Notebook                                | 2         | 0.97%   |
| HP EliteBook 8460p                         | 2         | 0.97%   |
| HP 250 G5 Notebook PC                      | 2         | 0.97%   |
| Dell Latitude E7450                        | 2         | 0.97%   |
| Dell Latitude E6520                        | 2         | 0.97%   |
| Dell Latitude E6410                        | 2         | 0.97%   |
| Acer Aspire ES1-523                        | 2         | 0.97%   |
| Valve Jupiter                              | 1         | 0.48%   |
| TUXEDO N13xWU                              | 1         | 0.48%   |
| TrekStor Surfbook W2                       | 1         | 0.48%   |
| Toshiba Satellite Pro C650                 | 1         | 0.48%   |
| Toshiba Satellite L750                     | 1         | 0.48%   |
| Toshiba Satellite L50-B                    | 1         | 0.48%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.48%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.48%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.48%   |
| Toshiba Satellite C855-1LG                 | 1         | 0.48%   |
| Toshiba Satellite C660                     | 1         | 0.48%   |
| Sony VPCEH1L8E                             | 1         | 0.48%   |
| Sony VGN-FW11L                             | 1         | 0.48%   |
| Sony SVE14122CAW                           | 1         | 0.48%   |
| SINTRONES AMB-5000G1                       | 1         | 0.48%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.48%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.48%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.48%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.48%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.48%   |
| Packard Bell EasyNote TK85                 | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 30        | 14.49%  |
| Lenovo ThinkPad       | 21        | 10.14%  |
| HP EliteBook          | 18        | 8.7%    |
| HP ProBook            | 10        | 4.83%   |
| HP Pavilion           | 10        | 4.83%   |
| HP Laptop             | 9         | 4.35%   |
| Toshiba Satellite     | 8         | 3.86%   |
| Lenovo IdeaPad        | 6         | 2.9%    |
| Acer Aspire           | 6         | 2.9%    |
| HP 250                | 5         | 2.42%   |
| Packard Bell EasyNote | 3         | 1.45%   |
| Lenovo ThinkBook      | 3         | 1.45%   |
| HP ZBook              | 3         | 1.45%   |
| ASUS X540LA           | 3         | 1.45%   |
| Unknown               | 3         | 1.45%   |
| Timi TM1701           | 2         | 0.97%   |
| HP Notebook           | 2         | 0.97%   |
| HP Compaq             | 2         | 0.97%   |
| Dell Vostro           | 2         | 0.97%   |
| Dell Precision        | 2         | 0.97%   |
| Dell Inspiron         | 2         | 0.97%   |
| Valve Jupiter         | 1         | 0.48%   |
| TUXEDO N13xWU         | 1         | 0.48%   |
| TrekStor Surfbook     | 1         | 0.48%   |
| Sony VPCEH1L8E        | 1         | 0.48%   |
| Sony VGN-FW11L        | 1         | 0.48%   |
| Sony SVE14122CAW      | 1         | 0.48%   |
| SINTRONES AMB-5000G1  | 1         | 0.48%   |
| Samsung 355V4C        | 1         | 0.48%   |
| Samsung 300E4A        | 1         | 0.48%   |
| Razer Blade           | 1         | 0.48%   |
| Medion P7615          | 1         | 0.48%   |
| Mediacom WinPad       | 1         | 0.48%   |
| Lenovo Z70-80         | 1         | 0.48%   |
| Lenovo V310-15IKB     | 1         | 0.48%   |
| Lenovo S21e-20        | 1         | 0.48%   |
| Lenovo IdeaPadFlex    | 1         | 0.48%   |
| Lenovo G50-70         | 1         | 0.48%   |
| Lenovo B50-30         | 1         | 0.48%   |
| HUAWEI NBLB-WAX9N     | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 21        | 10.14%  |
| 2010 | 21        | 10.14%  |
| 2011 | 20        | 9.66%   |
| 2014 | 18        | 8.7%    |
| 2018 | 17        | 8.21%   |
| 2016 | 17        | 8.21%   |
| 2015 | 17        | 8.21%   |
| 2020 | 15        | 7.25%   |
| 2017 | 12        | 5.8%    |
| 2012 | 11        | 5.31%   |
| 2021 | 10        | 4.83%   |
| 2019 | 10        | 4.83%   |
| 2009 | 5         | 2.42%   |
| 2008 | 4         | 1.93%   |
| 2007 | 3         | 1.45%   |
| 2022 | 2         | 0.97%   |
| 2006 | 2         | 0.97%   |
| 2023 | 1         | 0.48%   |
| 2005 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 207       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 197       | 93.81%  |
| Enabled  | 13        | 6.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 205       | 99.03%  |
| Yes  | 2         | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 73        | 34.93%  |
| 3.01-4.0   | 57        | 27.27%  |
| 8.01-16.0  | 30        | 14.35%  |
| 16.01-24.0 | 23        | 11%     |
| 1.01-2.0   | 12        | 5.74%   |
| 32.01-64.0 | 5         | 2.39%   |
| 2.01-3.0   | 4         | 1.91%   |
| 24.01-32.0 | 3         | 1.44%   |
| 0.51-1.0   | 2         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 82        | 36.61%  |
| 2.01-3.0  | 71        | 31.7%   |
| 4.01-8.0  | 30        | 13.39%  |
| 3.01-4.0  | 29        | 12.95%  |
| 0.51-1.0  | 9         | 4.02%   |
| 8.01-16.0 | 3         | 1.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 174       | 83.25%  |
| 2      | 31        | 14.83%  |
| 3      | 4         | 1.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 53.62%  |
| Yes       | 96        | 46.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 88.41%  |
| No        | 24        | 11.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 98.56%  |
| No        | 3         | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 72.38%  |
| No        | 58        | 27.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 207       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 47        | 21.17%  |
| Rabat            | 22        | 9.91%   |
| Marrakesh        | 22        | 9.91%   |
| Fes              | 16        | 7.21%   |
| Agadir           | 16        | 7.21%   |
| Tangier          | 12        | 5.41%   |
| Kenitra          | 11        | 4.95%   |
| Salé            | 10        | 4.5%    |
| Oujda            | 8         | 3.6%    |
| Meknes           | 8         | 3.6%    |
| Khouribga        | 7         | 3.15%   |
| Nador            | 5         | 2.25%   |
| Tiznit           | 3         | 1.35%   |
| El Jadida        | 3         | 1.35%   |
| Beni Mellal      | 3         | 1.35%   |
| Temara           | 2         | 0.9%    |
| Taza             | 2         | 0.9%    |
| Guelmim          | 2         | 0.9%    |
| Youssoufia       | 1         | 0.45%   |
| Tit Mellil       | 1         | 0.45%   |
| Tétouan         | 1         | 0.45%   |
| Targuist         | 1         | 0.45%   |
| Taourirt         | 1         | 0.45%   |
| Skhirate         | 1         | 0.45%   |
| Sidi Slimane     | 1         | 0.45%   |
| Sidi Kacem       | 1         | 0.45%   |
| Settat           | 1         | 0.45%   |
| Sefrou           | 1         | 0.45%   |
| Safi             | 1         | 0.45%   |
| Mohammedia       | 1         | 0.45%   |
| Midelt           | 1         | 0.45%   |
| Ksar El Kebir    | 1         | 0.45%   |
| Khemisset        | 1         | 0.45%   |
| Karia Ba Mohamed | 1         | 0.45%   |
| Inezgane         | 1         | 0.45%   |
| Errachidia       | 1         | 0.45%   |
| Berkane          | 1         | 0.45%   |
| Aousserd         | 1         | 0.45%   |
| Al Aaroui        | 1         | 0.45%   |
| Agdz             | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 39        | 48     | 16.46%  |
| Toshiba                     | 33        | 41     | 13.92%  |
| Samsung Electronics         | 29        | 36     | 12.24%  |
| WDC                         | 28        | 36     | 11.81%  |
| Unknown                     | 13        | 19     | 5.49%   |
| Sandisk                     | 10        | 10     | 4.22%   |
| Hitachi                     | 10        | 11     | 4.22%   |
| HGST                        | 8         | 8      | 3.38%   |
| Kingston                    | 6         | 7      | 2.53%   |
| Intel                       | 6         | 7      | 2.53%   |
| Apple                       | 6         | 6      | 2.53%   |
| SK hynix                    | 5         | 5      | 2.11%   |
| KIOXIA                      | 4         | 4      | 1.69%   |
| PNY                         | 3         | 4      | 1.27%   |
| LITEON                      | 3         | 3      | 1.27%   |
| China                       | 3         | 4      | 1.27%   |
| Micron Technology           | 2         | 3      | 0.84%   |
| KingDian                    | 2         | 6      | 0.84%   |
| GOODRAM                     | 2         | 2      | 0.84%   |
| Fujitsu                     | 2         | 2      | 0.84%   |
| Crucial                     | 2         | 2      | 0.84%   |
| Unknown                     | 2         | 2      | 0.84%   |
| TwinMOS                     | 1         | 1      | 0.42%   |
| Transcend                   | 1         | 1      | 0.42%   |
| ShiJi                       | 1         | 2      | 0.42%   |
| RCESSD                      | 1         | 1      | 0.42%   |
| Phison                      | 1         | 1      | 0.42%   |
| O2 Micro                    | 1         | 1      | 0.42%   |
| MSI                         | 1         | 1      | 0.42%   |
| LITEONIT                    | 1         | 1      | 0.42%   |
| Kingston Technology Company | 1         | 1      | 0.42%   |
| KingSpec                    | 1         | 1      | 0.42%   |
| KingFast                    | 1         | 2      | 0.42%   |
| Intenso                     | 1         | 2      | 0.42%   |
| Indilinx                    | 1         | 1      | 0.42%   |
| IBM/Hitachi                 | 1         | 1      | 0.42%   |
| Hewlett-Packard             | 1         | 1      | 0.42%   |
| BIWIN                       | 1         | 1      | 0.42%   |
| Apacer                      | 1         | 1      | 0.42%   |
| A-DATA Technology           | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 5         | 2.03%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 2.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 2.03%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.63%   |
| Toshiba MQ01ABD050 500GB               | 4         | 1.63%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.63%   |
| Toshiba MQ01ACF050 500GB               | 3         | 1.22%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.22%   |
| Seagate ST9500325AS 500GB              | 3         | 1.22%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.22%   |
| HGST HTS545050A7E680 500GB             | 3         | 1.22%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.81%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.81%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.81%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 0.81%   |
| Unknown MMC Card  32GB                 | 2         | 0.81%   |
| Unknown MMC Card  16GB                 | 2         | 0.81%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.81%   |
| Toshiba KXG50ZNV256G 256GB             | 2         | 0.81%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.81%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.81%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.81%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.81%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 0.81%   |
| Hitachi HTS542525K9A300 250GB          | 2         | 0.81%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.81%   |
| Unknown                                | 2         | 0.81%   |
| WDC WDS256G1X0C-00ENX0 256GB           | 1         | 0.41%   |
| WDC WD5000LPCX-60VHAT1 500GB           | 1         | 0.41%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.41%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.41%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.41%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 1         | 0.41%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.41%   |
| WDC WD2500BPVT-22ZEST0 250GB           | 1         | 0.41%   |
| WDC WD2500BEVT-22A23T0 208GB           | 1         | 0.41%   |
| WDC WD2500BEKT-60V5T1 250GB            | 1         | 0.41%   |
| WDC WD2500BEKT-60A25T1 250GB           | 1         | 0.41%   |
| WDC WD1600BEVS-60VAT0 160GB            | 1         | 0.41%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 48     | 33.91%  |
| Toshiba             | 27        | 31     | 23.48%  |
| WDC                 | 24        | 32     | 20.87%  |
| Hitachi             | 10        | 11     | 8.7%    |
| HGST                | 8         | 8      | 6.96%   |
| Samsung Electronics | 2         | 2      | 1.74%   |
| Fujitsu             | 2         | 2      | 1.74%   |
| Apple               | 2         | 2      | 1.74%   |
| IBM/Hitachi         | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 14.52%  |
| SanDisk             | 8         | 8      | 12.9%   |
| Kingston            | 5         | 6      | 8.06%   |
| SK hynix            | 3         | 3      | 4.84%   |
| PNY                 | 3         | 4      | 4.84%   |
| LITEON              | 3         | 3      | 4.84%   |
| China               | 3         | 4      | 4.84%   |
| Apple               | 3         | 3      | 4.84%   |
| Micron Technology   | 2         | 3      | 3.23%   |
| KingDian            | 2         | 6      | 3.23%   |
| Intel               | 2         | 3      | 3.23%   |
| GOODRAM             | 2         | 2      | 3.23%   |
| Crucial             | 2         | 2      | 3.23%   |
| TwinMOS             | 1         | 1      | 1.61%   |
| Transcend           | 1         | 1      | 1.61%   |
| Toshiba             | 1         | 1      | 1.61%   |
| RCESSD              | 1         | 1      | 1.61%   |
| MSI                 | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |
| KingFast            | 1         | 1      | 1.61%   |
| Indilinx            | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 1      | 1.61%   |
| BIWIN               | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |
| 2.5"                | 1         | 1      | 1.61%   |
| Unknown             | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 113       | 137    | 49.13%  |
| SSD     | 60        | 74     | 26.09%  |
| NVMe    | 41        | 52     | 17.83%  |
| MMC     | 13        | 19     | 5.65%   |
| Unknown | 3         | 6      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 215    | 75%     |
| NVMe | 41        | 52     | 18.64%  |
| MMC  | 13        | 19     | 5.91%   |
| SAS  | 1         | 2      | 0.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 156    | 75.29%  |
| 0.51-1.0   | 40        | 53     | 23.53%  |
| 1.01-2.0   | 2         | 2      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 29.11%  |
| 251-500        | 58        | 27.23%  |
| 51-100         | 26        | 12.21%  |
| 501-1000       | 20        | 9.39%   |
| 1-20           | 19        | 8.92%   |
| 21-50          | 16        | 7.51%   |
| 1001-2000      | 6         | 2.82%   |
| Unknown        | 3         | 1.41%   |
| More than 3000 | 2         | 0.94%   |
| 2001-3000      | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 96        | 42.67%  |
| 21-50          | 55        | 24.44%  |
| 101-250        | 30        | 13.33%  |
| 51-100         | 29        | 12.89%  |
| 251-500        | 7         | 3.11%   |
| Unknown        | 3         | 1.33%   |
| More than 3000 | 2         | 0.89%   |
| 501-1000       | 2         | 0.89%   |
| 1001-2000      | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 10%     |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 10%     |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 6.67%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 3.33%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 3.33%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 5      | 3.33%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 3.33%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 3.33%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 3.33%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 3.33%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.33%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 3.33%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 3.33%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 3.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.33%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 3.33%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 3.33%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 3.33%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 26.67%  |
| Seagate             | 8         | 8      | 26.67%  |
| Hitachi             | 4         | 5      | 13.33%  |
| WDC                 | 3         | 7      | 10%     |
| HGST                | 2         | 2      | 6.67%   |
| SanDisk             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 29.63%  |
| Seagate | 8         | 8      | 29.63%  |
| Hitachi | 4         | 5      | 14.81%  |
| WDC     | 3         | 7      | 11.11%  |
| HGST    | 2         | 2      | 7.41%   |
| Fujitsu | 1         | 1      | 3.7%    |
| Apple   | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 32     | 90%     |
| SSD  | 3         | 3      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22A23T0 208GB               | 1         | 2      | 50%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 125       | 170    | 56.05%  |
| Works    | 66        | 80     | 29.6%   |
| Malfunc  | 30        | 35     | 13.45%  |
| Failed   | 2         | 3      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 169       | 75.45%  |
| Samsung Electronics              | 20        | 8.93%   |
| AMD                              | 13        | 5.8%    |
| Toshiba America Info Systems     | 5         | 2.23%   |
| SanDisk                          | 5         | 2.23%   |
| KIOXIA                           | 4         | 1.79%   |
| SK hynix                         | 2         | 0.89%   |
| Kingston Technology Company      | 2         | 0.89%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Phison Electronics               | 1         | 0.45%   |
| O2 Micro                         | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 23        | 9.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 7.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 15        | 6.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 5.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 4.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 3.33%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 3.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.08%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.83%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 0.83%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.83%   |
| Intel SSD 660P Series                                                            | 2         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.42%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.42%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.42%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.42%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.42%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 153       | 65.38%  |
| NVMe | 41        | 17.52%  |
| RAID | 32        | 13.68%  |
| IDE  | 8         | 3.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 190       | 91.79%  |
| AMD    | 17        | 8.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 3.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 2.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 2.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 2.42%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.45%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.45%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.97%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.97%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.97%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.97%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.97%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 2         | 0.97%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.97%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 0.97%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 2         | 0.97%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 0.97%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 2         | 0.97%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.97%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 0.97%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.97%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 0.97%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 81        | 39.13%  |
| Intel Core i7           | 37        | 17.87%  |
| Intel Core i3           | 27        | 13.04%  |
| Other                   | 13        | 6.28%   |
| Intel Core 2 Duo        | 10        | 4.83%   |
| Intel Celeron           | 9         | 4.35%   |
| Intel Atom              | 5         | 2.42%   |
| AMD E1                  | 3         | 1.45%   |
| Intel Pentium Dual-Core | 2         | 0.97%   |
| AMD Ryzen 7             | 2         | 0.97%   |
| AMD Ryzen 5             | 2         | 0.97%   |
| AMD C-60                | 2         | 0.97%   |
| AMD A8                  | 2         | 0.97%   |
| AMD A6                  | 2         | 0.97%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium M         | 1         | 0.48%   |
| Intel Pentium Gold      | 1         | 0.48%   |
| Intel Pentium           | 1         | 0.48%   |
| Intel Genuine           | 1         | 0.48%   |
| Intel Core 2            | 1         | 0.48%   |
| Intel Celeron M         | 1         | 0.48%   |
| AMD Ryzen 9             | 1         | 0.48%   |
| AMD Ryzen 7 PRO         | 1         | 0.48%   |
| AMD A4                  | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 134       | 64.73%  |
| 4      | 56        | 27.05%  |
| 8      | 5         | 2.42%   |
| 6      | 5         | 2.42%   |
| 1      | 5         | 2.42%   |
| 10     | 2         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 164       | 79.23%  |
| 1      | 43        | 20.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 97.58%  |
| 32-bit         | 3         | 1.45%   |
| Unknown        | 2         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 24.88%  |
| 0x206a7    | 17        | 7.98%   |
| 0x306d4    | 14        | 6.57%   |
| 0x40651    | 11        | 5.16%   |
| 0x806ea    | 10        | 4.69%   |
| 0x806ec    | 9         | 4.23%   |
| 0x306c3    | 9         | 4.23%   |
| 0x20655    | 9         | 4.23%   |
| 0x306a9    | 8         | 3.76%   |
| 0x806c1    | 7         | 3.29%   |
| 0x406e3    | 6         | 2.82%   |
| 0x1067a    | 6         | 2.82%   |
| 0x806e9    | 5         | 2.35%   |
| 0x20652    | 5         | 2.35%   |
| 0x6fd      | 4         | 1.88%   |
| 0x506e3    | 4         | 1.88%   |
| 0x30678    | 4         | 1.88%   |
| 0x0a50000c | 3         | 1.41%   |
| 0x906ea    | 2         | 0.94%   |
| 0x406c4    | 2         | 0.94%   |
| 0x406c3    | 2         | 0.94%   |
| 0x10676    | 2         | 0.94%   |
| 0x07030105 | 2         | 0.94%   |
| 0x0700010f | 2         | 0.94%   |
| 0xb06a3    | 1         | 0.47%   |
| 0x906e9    | 1         | 0.47%   |
| 0x806eb    | 1         | 0.47%   |
| 0x806d1    | 1         | 0.47%   |
| 0x706e5    | 1         | 0.47%   |
| 0x706a1    | 1         | 0.47%   |
| 0x6ec      | 1         | 0.47%   |
| 0x6e8      | 1         | 0.47%   |
| 0x6d8      | 1         | 0.47%   |
| 0x30673    | 1         | 0.47%   |
| 0x30661    | 1         | 0.47%   |
| 0x08108102 | 1         | 0.47%   |
| 0x06006705 | 1         | 0.47%   |
| 0x06001119 | 1         | 0.47%   |
| 0x05000119 | 1         | 0.47%   |
| 0x05000101 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 17.39%  |
| Haswell          | 27        | 13.04%  |
| SandyBridge      | 19        | 9.18%   |
| Westmere         | 18        | 8.7%    |
| Broadwell        | 17        | 8.21%   |
| Skylake          | 15        | 7.25%   |
| Silvermont       | 10        | 4.83%   |
| IvyBridge        | 10        | 4.83%   |
| TigerLake        | 9         | 4.35%   |
| Penryn           | 9         | 4.35%   |
| Core             | 5         | 2.42%   |
| Icelake          | 4         | 1.93%   |
| Zen 3            | 3         | 1.45%   |
| P6               | 3         | 1.45%   |
| Bobcat           | 3         | 1.45%   |
| Unknown          | 3         | 1.45%   |
| Zen+             | 2         | 0.97%   |
| Puma             | 2         | 0.97%   |
| Jaguar           | 2         | 0.97%   |
| Goldmont plus    | 2         | 0.97%   |
| Bonnell          | 2         | 0.97%   |
| Alderlake Hybrid | 2         | 0.97%   |
| Piledriver       | 1         | 0.48%   |
| K10 Llano        | 1         | 0.48%   |
| Excavator        | 1         | 0.48%   |
| CometLake        | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 68.48%  |
| Nvidia | 51        | 19.84%  |
| AMD    | 30        | 11.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.92%   |
| Intel HD Graphics 5500                                                                   | 16        | 6.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 6.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 5.77%   |
| Intel UHD Graphics 620                                                                   | 12        | 4.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 3.46%   |
| Intel HD Graphics 620                                                                    | 8         | 3.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.54%   |
| Intel HD Graphics 530                                                                    | 4         | 1.54%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.15%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.15%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.15%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.77%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.77%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.77%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.77%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.77%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.77%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.77%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.77%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 61.06%  |
| Intel + Nvidia | 42        | 20.19%  |
| 1 x AMD        | 22        | 10.58%  |
| 1 x Nvidia     | 9         | 4.33%   |
| Intel + AMD    | 7         | 3.37%   |
| AMD + Nvidia   | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 179       | 84.43%  |
| Proprietary | 24        | 11.32%  |
| Unknown     | 9         | 4.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 72.17%  |
| 1.01-2.0   | 25        | 11.79%  |
| 0.01-0.5   | 20        | 9.43%   |
| 3.01-4.0   | 8         | 3.77%   |
| 0.51-1.0   | 5         | 2.36%   |
| 2.01-3.0   | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 41        | 19.62%  |
| Chimei Innolux          | 37        | 17.7%   |
| AU Optronics            | 36        | 17.22%  |
| Samsung Electronics     | 29        | 13.88%  |
| BOE                     | 27        | 12.92%  |
| InfoVision              | 6         | 2.87%   |
| Lenovo                  | 4         | 1.91%   |
| Hewlett-Packard         | 4         | 1.91%   |
| Dell                    | 4         | 1.91%   |
| Chi Mei Optoelectronics | 4         | 1.91%   |
| Apple                   | 4         | 1.91%   |
| LG Philips              | 3         | 1.44%   |
| Sharp                   | 2         | 0.96%   |
| Valve                   | 1         | 0.48%   |
| TMX                     | 1         | 0.48%   |
| PANDA                   | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| LGD                     | 1         | 0.48%   |
| IBM                     | 1         | 0.48%   |
| Goldstar                | 1         | 0.48%   |
| CNC                     | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.9%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.43%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.43%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.95%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.95%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.95%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.95%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.95%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 0.95%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.95%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.95%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.48%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.48%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 48.28%  |
| 1920x1080 (FHD)    | 59        | 29.06%  |
| 1600x900 (HD+)     | 15        | 7.39%   |
| 1280x800 (WXGA)    | 7         | 3.45%   |
| 1440x900 (WXGA+)   | 4         | 1.97%   |
| 1680x1050 (WSXGA+) | 3         | 1.48%   |
| 1024x600           | 3         | 1.48%   |
| 3840x2160 (4K)     | 2         | 0.99%   |
| 800x1280           | 1         | 0.49%   |
| 3840x2400          | 1         | 0.49%   |
| 2880x1800          | 1         | 0.49%   |
| 2560x1600          | 1         | 0.49%   |
| 2560x1440 (QHD)    | 1         | 0.49%   |
| 2520x1680          | 1         | 0.49%   |
| 1920x1200 (WUXGA)  | 1         | 0.49%   |
| 1680x945           | 1         | 0.49%   |
| 1400x1050          | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x1024 (SXGA)   | 1         | 0.49%   |
| 1024x768 (XGA)     | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 114       | 54.29%  |
| 14      | 28        | 13.33%  |
| 13      | 22        | 10.48%  |
| 12      | 12        | 5.71%   |
| 17      | 7         | 3.33%   |
| 18      | 5         | 2.38%   |
| 23      | 4         | 1.9%    |
| 24      | 3         | 1.43%   |
| 11      | 3         | 1.43%   |
| 22      | 2         | 0.95%   |
| 10      | 2         | 0.95%   |
| 84      | 1         | 0.48%   |
| 32      | 1         | 0.48%   |
| 31      | 1         | 0.48%   |
| 27      | 1         | 0.48%   |
| 19      | 1         | 0.48%   |
| 16      | 1         | 0.48%   |
| 7       | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 151       | 71.9%   |
| 201-300     | 27        | 12.86%  |
| 351-400     | 13        | 6.19%   |
| 501-600     | 8         | 3.81%   |
| 401-500     | 6         | 2.86%   |
| 701-800     | 1         | 0.48%   |
| 601-700     | 1         | 0.48%   |
| 1501-2000   | 1         | 0.48%   |
| 1-100       | 1         | 0.48%   |
| Unknown     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 176       | 87.56%  |
| 16/10   | 18        | 8.96%   |
| 4/3     | 2         | 1%      |
| 3/2     | 2         | 1%      |
| 5/4     | 1         | 0.5%    |
| 0.67    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 113       | 53.81%  |
| 81-90          | 42        | 20%     |
| 61-70          | 12        | 5.71%   |
| 71-80          | 7         | 3.33%   |
| 201-250        | 7         | 3.33%   |
| 121-130        | 5         | 2.38%   |
| 141-150        | 4         | 1.9%    |
| 51-60          | 3         | 1.43%   |
| 351-500        | 2         | 0.95%   |
| 41-50          | 2         | 0.95%   |
| 251-300        | 2         | 0.95%   |
| 151-200        | 2         | 0.95%   |
| 131-140        | 2         | 0.95%   |
| 111-120        | 2         | 0.95%   |
| More than 1000 | 1         | 0.48%   |
| 1-40           | 1         | 0.48%   |
| 301-350        | 1         | 0.48%   |
| 91-100         | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 92        | 44.02%  |
| 121-160       | 70        | 33.49%  |
| 51-100        | 29        | 13.88%  |
| 161-240       | 14        | 6.7%    |
| More than 240 | 2         | 0.96%   |
| 1-50          | 1         | 0.48%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 189       | 90%     |
| 2     | 16        | 7.62%   |
| 0     | 5         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 109       | 33.75%  |
| Realtek Semiconductor    | 96        | 29.72%  |
| Qualcomm Atheros         | 47        | 14.55%  |
| Broadcom                 | 34        | 10.53%  |
| Ralink Technology        | 8         | 2.48%   |
| Ralink                   | 5         | 1.55%   |
| Broadcom Limited         | 4         | 1.24%   |
| Xiaomi                   | 3         | 0.93%   |
| Dell                     | 3         | 0.93%   |
| Sierra Wireless          | 2         | 0.62%   |
| Samsung Electronics      | 2         | 0.62%   |
| Lenovo                   | 2         | 0.62%   |
| TP-Link                  | 1         | 0.31%   |
| Qualcomm                 | 1         | 0.31%   |
| Nvidia                   | 1         | 0.31%   |
| MediaTek                 | 1         | 0.31%   |
| Marvell Technology Group | 1         | 0.31%   |
| JMicron Technology       | 1         | 0.31%   |
| Huawei Technologies      | 1         | 0.31%   |
| Arduino SA               | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 14.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 5.11%   |
| Intel Wireless 7265                                               | 12        | 2.92%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.68%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.19%   |
| Intel Wireless 8260                                               | 9         | 2.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.7%    |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.7%    |
| Ralink MT7601U Wireless Adapter                                   | 6         | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 1.46%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.22%   |
| Intel Wireless 7260                                               | 5         | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.22%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.73%   |
| Intel WiFi Link 5100                                              | 3         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 46.3%   |
| Qualcomm Atheros      | 42        | 19.44%  |
| Realtek Semiconductor | 27        | 12.5%   |
| Broadcom              | 24        | 11.11%  |
| Ralink Technology     | 8         | 3.7%    |
| Ralink                | 5         | 2.31%   |
| Broadcom Limited      | 4         | 1.85%   |
| Sierra Wireless       | 2         | 0.93%   |
| Dell                  | 2         | 0.93%   |
| TP-Link               | 1         | 0.46%   |
| MediaTek              | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 12        | 5.56%   |
| Intel Wireless 8265 / 8275                                     | 11        | 5.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 4.17%   |
| Intel Wireless 8260                                            | 9         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.24%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 3.24%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.31%   |
| Intel Wireless 7260                                            | 5         | 2.31%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.31%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.85%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.85%   |
| Intel WiFi Link 5100                                           | 3         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.39%   |
| Sierra Wireless EM7455                                         | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.93%   |
| Intel Wireless 3165                                            | 2         | 0.93%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.93%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 86        | 45.03%  |
| Intel                    | 69        | 36.13%  |
| Broadcom                 | 13        | 6.81%   |
| Qualcomm Atheros         | 11        | 5.76%   |
| Xiaomi                   | 3         | 1.57%   |
| Samsung Electronics      | 2         | 1.05%   |
| Lenovo                   | 2         | 1.05%   |
| Qualcomm                 | 1         | 0.52%   |
| Nvidia                   | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| JMicron Technology       | 1         | 0.52%   |
| Huawei Technologies      | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 30.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 10.94%  |
| Intel 82577LM Gigabit Network Connection                          | 11        | 5.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.21%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 4.69%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.13%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.08%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.04%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.04%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.52%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.52%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.52%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 52.56%  |
| Ethernet | 182       | 46.67%  |
| Modem    | 3         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 83.17%  |
| Ethernet | 35        | 16.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 176       | 84.62%  |
| 1     | 27        | 12.98%  |
| 0     | 3         | 1.44%   |
| 7     | 1         | 0.48%   |
| 3     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 207       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 43.42%  |
| Realtek Semiconductor           | 19        | 12.5%   |
| Qualcomm Atheros Communications | 18        | 11.84%  |
| Broadcom                        | 10        | 6.58%   |
| IMC Networks                    | 8         | 5.26%   |
| Dell                            | 7         | 4.61%   |
| Ralink                          | 5         | 3.29%   |
| Lite-On Technology              | 5         | 3.29%   |
| Hewlett-Packard                 | 5         | 3.29%   |
| Apple                           | 3         | 1.97%   |
| Toshiba                         | 1         | 0.66%   |
| Foxconn International           | 1         | 0.66%   |
| Foxconn / Hon Hai               | 1         | 0.66%   |
| Cambridge Silicon Radio         | 1         | 0.66%   |
| ASUSTek Computer                | 1         | 0.66%   |
| Alps Electric                   | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 23.68%  |
| Realtek Bluetooth Radio                             | 12        | 7.89%   |
| Intel AX201 Bluetooth                               | 10        | 6.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.61%   |
| IMC Networks Bluetooth Device                       | 6         | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.29%   |
| Ralink RT3290 Bluetooth                             | 5         | 3.29%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 3.29%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 2.63%   |
| Dell DW375 Bluetooth Module                         | 4         | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.97%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.97%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.32%   |
| Intel AX200 Bluetooth                               | 2         | 1.32%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.32%   |
| Toshiba Bluetooth Device                            | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.66%   |
| Intel Bluetooth Device                              | 1         | 0.66%   |
| IMC Networks Wireless_Device                        | 1         | 0.66%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.66%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.66%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.66%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.66%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 186       | 76.86%  |
| Nvidia                           | 25        | 10.33%  |
| AMD                              | 22        | 9.09%   |
| Lenovo                           | 2         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Nordic Semiconductor ASA         | 1         | 0.41%   |
| Logitech                         | 1         | 0.41%   |
| GN Netcom                        | 1         | 0.41%   |
| Generalplus Technology           | 1         | 0.41%   |
| Focusrite-Novation               | 1         | 0.41%   |
| ASUSTek Computer                 | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 10.03%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 6.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 5.69%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 5.69%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.35%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 3.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.01%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1%      |
| Nvidia Audio device                                                                               | 3         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1%      |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.67%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.33%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.33%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.93%  |
| SK hynix            | 33        | 24.09%  |
| Micron Technology   | 20        | 14.6%   |
| Kingston            | 17        | 12.41%  |
| Unknown             | 5         | 3.65%   |
| Ramaxel Technology  | 4         | 2.92%   |
| Elpida              | 4         | 2.92%   |
| A-DATA Technology   | 4         | 2.92%   |
| Crucial             | 3         | 2.19%   |
| Nanya Technology    | 2         | 1.46%   |
| Transcend           | 1         | 0.73%   |
| Toshiba             | 1         | 0.73%   |
| Sesame              | 1         | 0.73%   |
| ASint Technology    | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 2.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 2.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 3         | 2.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 1.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.34%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 1.34%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s    | 2         | 1.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.34%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 1.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.34%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1866MT/s       | 2         | 1.34%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.34%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 1.34%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s      | 2         | 1.34%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 1.34%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 0.67%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 1         | 0.67%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s           | 1         | 0.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 0.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s             | 1         | 0.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s       | 1         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 56        | 51.85%  |
| DDR4    | 37        | 34.26%  |
| LPDDR4  | 4         | 3.7%    |
| DDR2    | 4         | 3.7%    |
| LPDDR3  | 3         | 2.78%   |
| Unknown | 2         | 1.85%   |
| SDRAM   | 1         | 0.93%   |
| DDR5    | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 92.52%  |
| Row Of Chips | 5         | 4.67%   |
| Unknown      | 2         | 1.87%   |
| DIMM         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 48        | 39.34%  |
| 8192  | 45        | 36.89%  |
| 2048  | 16        | 13.11%  |
| 16384 | 10        | 8.2%    |
| 1024  | 3         | 2.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 39        | 33.05%  |
| 2667    | 20        | 16.95%  |
| 3200    | 14        | 11.86%  |
| 1334    | 13        | 11.02%  |
| 2400    | 6         | 5.08%   |
| 2133    | 5         | 4.24%   |
| 1333    | 4         | 3.39%   |
| 1066    | 3         | 2.54%   |
| 1867    | 2         | 1.69%   |
| 975     | 2         | 1.69%   |
| 800     | 2         | 1.69%   |
| Unknown | 2         | 1.69%   |
| 4800    | 1         | 0.85%   |
| 4267    | 1         | 0.85%   |
| 4199    | 1         | 0.85%   |
| 3266    | 1         | 0.85%   |
| 1067    | 1         | 0.85%   |
| 667     | 1         | 0.85%   |

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
| Chicony Electronics                    | 49        | 28%     |
| IMC Networks                           | 18        | 10.29%  |
| Realtek Semiconductor                  | 17        | 9.71%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 9.14%   |
| Sunplus Innovation Technology          | 11        | 6.29%   |
| Suyin                                  | 10        | 5.71%   |
| Lite-On Technology                     | 9         | 5.14%   |
| Microdia                               | 8         | 4.57%   |
| Quanta                                 | 7         | 4%      |
| Bison Electronics                      | 5         | 2.86%   |
| Syntek                                 | 4         | 2.29%   |
| Ricoh                                  | 4         | 2.29%   |
| Apple                                  | 3         | 1.71%   |
| Luxvisions Innotech Limited            | 2         | 1.14%   |
| ALi                                    | 2         | 1.14%   |
| Z-Star Microelectronics                | 1         | 0.57%   |
| Sunplus Technology                     | 1         | 0.57%   |
| Sonix Technology                       | 1         | 0.57%   |
| Silicon Motion                         | 1         | 0.57%   |
| ShineTech                              | 1         | 0.57%   |
| OPPO Electronics                       | 1         | 0.57%   |
| Logitech                               | 1         | 0.57%   |
| icSpring                               | 1         | 0.57%   |
| Alcor Micro                            | 1         | 0.57%   |
| Acer                                   | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 4%      |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 3.43%   |
| IMC Networks Integrated Camera                              | 5         | 2.86%   |
| Chicony HP Webcam                                           | 5         | 2.86%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 2.29%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.71%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.71%   |
| Realtek USB Camera                                          | 3         | 1.71%   |
| Microdia Integrated Webcam                                  | 3         | 1.71%   |
| Lite-On HP HD Webcam                                        | 3         | 1.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.71%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.71%   |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.71%   |
| Chicony HP HD Webcam                                        | 3         | 1.71%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.14%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 1.14%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.14%   |
| Sunplus HP Universal Camera                                 | 2         | 1.14%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.14%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 1.14%   |
| Quanta HD Webcam                                            | 2         | 1.14%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.14%   |
| Lite-On HP HD Camera                                        | 2         | 1.14%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.14%   |
| IMC Networks Integrated Webcam                              | 2         | 1.14%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.14%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.14%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.14%   |
| Chicony HP Truevision HD                                    | 2         | 1.14%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.14%   |
| Bison Integrated Camera                                     | 2         | 1.14%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.57%   |
| Syntek Integrated Camera                                    | 1         | 0.57%   |
| Syntek EasyCamera                                           | 1         | 0.57%   |
| Suyin WebCam                                                | 1         | 0.57%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 66.67%  |
| Synaptics                  | 6         | 14.29%  |
| Elan Microelectronics      | 4         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 4.76%   |
| Upek                       | 1         | 2.38%   |
| Focal-systems.Corp         | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 26.19%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 11.9%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 9.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.14%   |
| Validity Sensors VFS491                                                    | 2         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.76%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.38%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.38%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 66.67%  |
| Alcor Micro | 6         | 20%     |
| O2 Micro    | 4         | 13.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 13.33%  |
| Broadcom 5880                                                                | 4         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 54.93%  |
| 1     | 75        | 35.21%  |
| 2     | 16        | 7.51%   |
| 3     | 4         | 1.88%   |
| 5     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 42        | 34.15%  |
| Chipcard                 | 26        | 21.14%  |
| Graphics card            | 22        | 17.89%  |
| Net/wireless             | 8         | 6.5%    |
| Bluetooth                | 6         | 4.88%   |
| Storage                  | 5         | 4.07%   |
| Camera                   | 4         | 3.25%   |
| Sound                    | 2         | 1.63%   |
| Net/ethernet             | 2         | 1.63%   |
| Communication controller | 2         | 1.63%   |
| Unassigned class         | 1         | 0.81%   |
| Network                  | 1         | 0.81%   |
| Multimedia controller    | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |


Linux in Morocco - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Morocco/Desktop/README.md) and [notebooks](/Location/Morocco/Notebook/README.md).

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

Total: 570

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | OptiPlex 745                | Desktop     | [578cc6d8f1](https://linux-hardware.org/?probe=578cc6d8f1) | Jan 06, 2025 |
| HP            | ProBook 650 G2              | Notebook    | [b2fc855e3e](https://linux-hardware.org/?probe=b2fc855e3e) | Jan 03, 2025 |
| Dell          | Vostro 1500                 | Notebook    | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [b007439528](https://linux-hardware.org/?probe=b007439528) | Dec 26, 2024 |
| HP            | 8B4D 100                    | All in one  | [24eb20636b](https://linux-hardware.org/?probe=24eb20636b) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [91cdbe5df9](https://linux-hardware.org/?probe=91cdbe5df9) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [32e2211a4c](https://linux-hardware.org/?probe=32e2211a4c) | Dec 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [dae98f533a](https://linux-hardware.org/?probe=dae98f533a) | Dec 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [5655debff7](https://linux-hardware.org/?probe=5655debff7) | Dec 19, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [524c33e748](https://linux-hardware.org/?probe=524c33e748) | Dec 16, 2024 |
| HP            | 8054                        | Desktop     | [3196c09967](https://linux-hardware.org/?probe=3196c09967) | Dec 16, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c936aa4e5](https://linux-hardware.org/?probe=3c936aa4e5) | Dec 16, 2024 |
| HP            | ProBook 6570b               | Notebook    | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| HP            | G62                         | Notebook    | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| HP            | Pavilion dv6                | Notebook    | [92fe6246ab](https://linux-hardware.org/?probe=92fe6246ab) | Dec 09, 2024 |
| Lenovo        | ThinkPad X1 Tablet 20GHS... | Tablet      | [18960c0bf8](https://linux-hardware.org/?probe=18960c0bf8) | Dec 08, 2024 |
| HP            | Pavilion g6                 | Notebook    | [36c4171d06](https://linux-hardware.org/?probe=36c4171d06) | Nov 21, 2024 |
| HP            | ProBook 6560b               | Notebook    | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [79d938cc3f](https://linux-hardware.org/?probe=79d938cc3f) | Nov 20, 2024 |
| HP            | 8055                        | Desktop     | [25559cfc60](https://linux-hardware.org/?probe=25559cfc60) | Nov 20, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [d5389c9065](https://linux-hardware.org/?probe=d5389c9065) | Nov 19, 2024 |
| Google        | Drawman                     | Notebook    | [46c461a6e2](https://linux-hardware.org/?probe=46c461a6e2) | Nov 18, 2024 |
| HP            | Notebook                    | Notebook    | [19d1189e7b](https://linux-hardware.org/?probe=19d1189e7b) | Nov 08, 2024 |
| Dell          | Latitude 7490               | Notebook    | [92bf691a6c](https://linux-hardware.org/?probe=92bf691a6c) | Nov 04, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7e072971d7](https://linux-hardware.org/?probe=7e072971d7) | Nov 04, 2024 |
| HP            | Notebook                    | Notebook    | [abea0efa1e](https://linux-hardware.org/?probe=abea0efa1e) | Nov 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [ce28c4199d](https://linux-hardware.org/?probe=ce28c4199d) | Oct 29, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [eef263185a](https://linux-hardware.org/?probe=eef263185a) | Oct 22, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| Dell          | Latitude 5420               | Notebook    | [622540975d](https://linux-hardware.org/?probe=622540975d) | Oct 10, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [533e95fac4](https://linux-hardware.org/?probe=533e95fac4) | Oct 09, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [c40e4f6c66](https://linux-hardware.org/?probe=c40e4f6c66) | Oct 09, 2024 |
| HP            | 8057                        | All in one  | [83a63f311a](https://linux-hardware.org/?probe=83a63f311a) | Oct 08, 2024 |
| HP            | 18E4                        | Desktop     | [9b22068827](https://linux-hardware.org/?probe=9b22068827) | Oct 04, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [f71728ea0e](https://linux-hardware.org/?probe=f71728ea0e) | Sep 20, 2024 |
| Packard Be... | ENNS44HR                    | Notebook    | [b47db91782](https://linux-hardware.org/?probe=b47db91782) | Sep 20, 2024 |
| Dell          | Latitude 7490               | Notebook    | [2e22221506](https://linux-hardware.org/?probe=2e22221506) | Sep 19, 2024 |
| Dell          | Latitude 7490               | Notebook    | [b8cce215a5](https://linux-hardware.org/?probe=b8cce215a5) | Sep 18, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [266c779453](https://linux-hardware.org/?probe=266c779453) | Sep 12, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [d75576c2f8](https://linux-hardware.org/?probe=d75576c2f8) | Sep 09, 2024 |
| Dell          | Inspiron 7548               | Notebook    | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [0f53ca6134](https://linux-hardware.org/?probe=0f53ca6134) | Aug 26, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [206392c090](https://linux-hardware.org/?probe=206392c090) | Aug 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [c349c2ef99](https://linux-hardware.org/?probe=c349c2ef99) | Aug 17, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [073d286abd](https://linux-hardware.org/?probe=073d286abd) | Aug 14, 2024 |
| Dell          | Precision M4600             | Notebook    | [fee987030c](https://linux-hardware.org/?probe=fee987030c) | Aug 12, 2024 |
| Dell          | Precision M4600             | Notebook    | [7decf1dba0](https://linux-hardware.org/?probe=7decf1dba0) | Aug 11, 2024 |
| Dell          | Latitude 5420               | Notebook    | [4017046879](https://linux-hardware.org/?probe=4017046879) | Aug 08, 2024 |
| HP            | 15                          | Notebook    | [89bd9fcc15](https://linux-hardware.org/?probe=89bd9fcc15) | Aug 05, 2024 |
| HP            | 15                          | Notebook    | [97a7e86ff2](https://linux-hardware.org/?probe=97a7e86ff2) | Aug 05, 2024 |
| HP            | 0B40h                       | Desktop     | [4e504e2f3a](https://linux-hardware.org/?probe=4e504e2f3a) | Aug 05, 2024 |
| HP            | 18E7                        | Desktop     | [a91cb43a38](https://linux-hardware.org/?probe=a91cb43a38) | Jul 30, 2024 |
| HP            | 18E7                        | Desktop     | [b426107c33](https://linux-hardware.org/?probe=b426107c33) | Jul 29, 2024 |
| HP            | 18E7                        | Desktop     | [5d7f84157a](https://linux-hardware.org/?probe=5d7f84157a) | Jul 27, 2024 |
| HP            | 18E7                        | Desktop     | [f1679be146](https://linux-hardware.org/?probe=f1679be146) | Jul 27, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9eed9965d0](https://linux-hardware.org/?probe=9eed9965d0) | Jul 25, 2024 |
| HP            | 872C                        | Mini pc     | [89a2238ddd](https://linux-hardware.org/?probe=89a2238ddd) | Jul 25, 2024 |
| HP            | 872C                        | Mini pc     | [1357e6cd79](https://linux-hardware.org/?probe=1357e6cd79) | Jul 25, 2024 |
| Dell          | 0MN1TX A01                  | Desktop     | [99e899cbb0](https://linux-hardware.org/?probe=99e899cbb0) | Jul 22, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [682ee2b1d0](https://linux-hardware.org/?probe=682ee2b1d0) | Jul 21, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [8cafc4b7db](https://linux-hardware.org/?probe=8cafc4b7db) | Jul 19, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [add07540e5](https://linux-hardware.org/?probe=add07540e5) | Jul 09, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [b8bf8326fd](https://linux-hardware.org/?probe=b8bf8326fd) | Jul 06, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | Notebook    | [43fb16f634](https://linux-hardware.org/?probe=43fb16f634) | Jul 03, 2024 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| HP            | 0AA8h                       | Desktop     | [bb1f36cf41](https://linux-hardware.org/?probe=bb1f36cf41) | Jun 17, 2024 |
| HP            | EliteBook 8740w             | Notebook    | [158dce1091](https://linux-hardware.org/?probe=158dce1091) | Jun 17, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8bf9046adc](https://linux-hardware.org/?probe=8bf9046adc) | Jun 02, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [d7bb8a4ea8](https://linux-hardware.org/?probe=d7bb8a4ea8) | May 17, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [1c55e1acf7](https://linux-hardware.org/?probe=1c55e1acf7) | May 08, 2024 |
| HP            | Laptop 15-ra0xx             | Notebook    | [4d00a746ff](https://linux-hardware.org/?probe=4d00a746ff) | May 02, 2024 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [e436c09a5c](https://linux-hardware.org/?probe=e436c09a5c) | Apr 30, 2024 |
| ACCENT        | SMART 140                   | Notebook    | [49fb07fe3f](https://linux-hardware.org/?probe=49fb07fe3f) | Apr 27, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Dell          | Latitude E7240              | Notebook    | [71103e976e](https://linux-hardware.org/?probe=71103e976e) | Apr 21, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [5b99cd208d](https://linux-hardware.org/?probe=5b99cd208d) | Apr 17, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | Notebook    | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| Lenovo        | 32E6 NOK                    | Desktop     | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| HP            | ZBook 17 G5                 | Notebook    | [2b22c5c485](https://linux-hardware.org/?probe=2b22c5c485) | Apr 07, 2024 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [e73c5851aa](https://linux-hardware.org/?probe=e73c5851aa) | Mar 30, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [a5606e10ad](https://linux-hardware.org/?probe=a5606e10ad) | Mar 27, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [91112364b8](https://linux-hardware.org/?probe=91112364b8) | Mar 26, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [1c72f8459c](https://linux-hardware.org/?probe=1c72f8459c) | Mar 26, 2024 |
| Dell          | Latitude 5480               | Notebook    | [ff785a4ce1](https://linux-hardware.org/?probe=ff785a4ce1) | Mar 22, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [3b5d0f6921](https://linux-hardware.org/?probe=3b5d0f6921) | Mar 19, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [0339864371](https://linux-hardware.org/?probe=0339864371) | Mar 09, 2024 |
| Dell          | Latitude 5289               | Notebook    | [fe338e3231](https://linux-hardware.org/?probe=fe338e3231) | Mar 09, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [979a30bf92](https://linux-hardware.org/?probe=979a30bf92) | Mar 09, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [66558a86e4](https://linux-hardware.org/?probe=66558a86e4) | Mar 09, 2024 |
| Dell          | Latitude E5550              | Notebook    | [4832591086](https://linux-hardware.org/?probe=4832591086) | Mar 08, 2024 |
| HP            | 212B                        | Desktop     | [781ec8e8f8](https://linux-hardware.org/?probe=781ec8e8f8) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [87afd5cfa6](https://linux-hardware.org/?probe=87afd5cfa6) | Mar 02, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [f44261baba](https://linux-hardware.org/?probe=f44261baba) | Feb 24, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [949f1cd85d](https://linux-hardware.org/?probe=949f1cd85d) | Feb 23, 2024 |
| Lenovo        | 32CB SDK0T76530 WIN 3556... | Desktop     | [c71cf6708c](https://linux-hardware.org/?probe=c71cf6708c) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2537VTC       | Notebook    | [a393686fff](https://linux-hardware.org/?probe=a393686fff) | Feb 18, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [2df79d1eff](https://linux-hardware.org/?probe=2df79d1eff) | Feb 17, 2024 |
| Acer          | Swift SFX14-51G             | Notebook    | [038f3ddc2e](https://linux-hardware.org/?probe=038f3ddc2e) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [a3d2bf6949](https://linux-hardware.org/?probe=a3d2bf6949) | Feb 10, 2024 |
| Dell          | Latitude 5510               | Notebook    | [e0d5fe1c62](https://linux-hardware.org/?probe=e0d5fe1c62) | Feb 07, 2024 |
| HP            | 620                         | Notebook    | [523cfc94c0](https://linux-hardware.org/?probe=523cfc94c0) | Feb 03, 2024 |
| HP            | ProBook 5320m               | Notebook    | [3be604f862](https://linux-hardware.org/?probe=3be604f862) | Feb 03, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [366174cd75](https://linux-hardware.org/?probe=366174cd75) | Feb 02, 2024 |
| HP            | 15                          | Notebook    | [b99530abd5](https://linux-hardware.org/?probe=b99530abd5) | Feb 01, 2024 |
| HP            | 15                          | Notebook    | [874ae10280](https://linux-hardware.org/?probe=874ae10280) | Feb 01, 2024 |
| HP            | 620                         | Notebook    | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Dell          | 02K9CR A01                  | Desktop     | [72df486f35](https://linux-hardware.org/?probe=72df486f35) | Jan 31, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [4cb29324fc](https://linux-hardware.org/?probe=4cb29324fc) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [dea06ca305](https://linux-hardware.org/?probe=dea06ca305) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [83eec08588](https://linux-hardware.org/?probe=83eec08588) | Jan 30, 2024 |
| Sony          | VPCF12A4E                   | Notebook    | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| HP            | ProBook 6560b               | Notebook    | [7b9f78e8df](https://linux-hardware.org/?probe=7b9f78e8df) | Jan 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| Dell          | Latitude 7390               | Notebook    | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [106a150b97](https://linux-hardware.org/?probe=106a150b97) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [f6b222e444](https://linux-hardware.org/?probe=f6b222e444) | Jan 06, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [0af2ce345e](https://linux-hardware.org/?probe=0af2ce345e) | Jan 06, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| HP            | 18E7                        | Desktop     | [f5115e035f](https://linux-hardware.org/?probe=f5115e035f) | Dec 30, 2023 |
| Dell          | Latitude E5470              | Notebook    | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| HP            | 090Ch                       | Desktop     | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [4053f6be95](https://linux-hardware.org/?probe=4053f6be95) | Dec 12, 2023 |
| HP            | 18E7                        | Desktop     | [dad5884f78](https://linux-hardware.org/?probe=dad5884f78) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Dell          | OptiPlex 745                | Desktop     | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [db3f0ac717](https://linux-hardware.org/?probe=db3f0ac717) | Oct 31, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| LG Electro... | R310-K.AP31B                | Notebook    | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| HP            | 1998                        | Desktop     | [d37c482ca8](https://linux-hardware.org/?probe=d37c482ca8) | Oct 19, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [a5a8709f77](https://linux-hardware.org/?probe=a5a8709f77) | Oct 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [e66ff52b09](https://linux-hardware.org/?probe=e66ff52b09) | Oct 13, 2023 |
| HP            | 18E4                        | Desktop     | [6707337e0c](https://linux-hardware.org/?probe=6707337e0c) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Dell          | 077RRV A00                  | Desktop     | [5ebc4171ff](https://linux-hardware.org/?probe=5ebc4171ff) | Sep 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | Notebook    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| HP            | Bloog                       | Notebook    | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| HP            | 3031h                       | Desktop     | [4ce70764b2](https://linux-hardware.org/?probe=4ce70764b2) | Aug 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| HP            | 158A                        | Desktop     | [4d915b56e7](https://linux-hardware.org/?probe=4d915b56e7) | Jul 08, 2023 |
| HP            | 0AECh D                     | Desktop     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | Latitude 5540               | Notebook    | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| HP            | 21F5 0A                     | Desktop     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| Dell          | Latitude 5289               | Notebook    | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | Notebook    | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | Notebook    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| HP            | 1589                        | Desktop     | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | Notebook    | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | Notebook    | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | Notebook    | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | 0AECh D                     | Desktop     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | Notebook    | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | Notebook    | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | Notebook    | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | Notebook    | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| HP            | 18E7                        | Desktop     | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | Notebook    | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [15582a281d](https://linux-hardware.org/?probe=15582a281d) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [57fa4478d0](https://linux-hardware.org/?probe=57fa4478d0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | Notebook    | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | Notebook    | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | Notebook    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | 2AA2                        | Desktop     | [36f40353c8](https://linux-hardware.org/?probe=36f40353c8) | Oct 25, 2022 |
| Linx          | LINX12X64                   | Tablet      | [132f0a1803](https://linux-hardware.org/?probe=132f0a1803) | Oct 24, 2022 |
| Linx          | LINX12X64                   | Tablet      | [5f78d7109f](https://linux-hardware.org/?probe=5f78d7109f) | Oct 24, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | Notebook    | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| HP            | 1497                        | Desktop     | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [805d4161a8](https://linux-hardware.org/?probe=805d4161a8) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | Notebook    | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | Notebook    | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [90197434fc](https://linux-hardware.org/?probe=90197434fc) | Aug 08, 2022 |
| HP            | 198E                        | Desktop     | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | Desktop     | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| Dell          | Latitude D620               | Notebook    | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | Notebook    | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [45ad38e728](https://linux-hardware.org/?probe=45ad38e728) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d809b304eb](https://linux-hardware.org/?probe=d809b304eb) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | Notebook    | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| HP            | 18E4                        | Desktop     | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | Notebook    | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | Notebook    | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | 3396                        | Desktop     | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| HP            | 1589                        | Desktop     | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | Notebook    | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| HP            | 8054                        | Desktop     | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | Desktop     | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8a415c9db8](https://linux-hardware.org/?probe=8a415c9db8) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3027f5288e](https://linux-hardware.org/?probe=3027f5288e) | Dec 04, 2021 |
| HP            | 1998                        | Desktop     | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | Notebook    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| Apple         | MacBookPro13,3              | Notebook    | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | 1589                        | Desktop     | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | Notebook    | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | Notebook    | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| HP            | 3032h                       | Desktop     | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | Notebook    | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| HP            | 18E7                        | Desktop     | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [99c878cd5e](https://linux-hardware.org/?probe=99c878cd5e) | Sep 04, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | 0AACh                       | Desktop     | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | Desktop     | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 15                          | Notebook    | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| HP            | 339A                        | Desktop     | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | Desktop     | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | Desktop     | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | Desktop     | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| Foxconn       | 2ACA                        | Desktop     | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | Notebook    | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | Desktop     | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| HP            | Notebook                    | Notebook    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | Notebook    | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | Notebook    | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| Acer          | AO722                       | Notebook    | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | Notebook    | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| HP            | 158A                        | Desktop     | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| Dell          | Latitude E6440              | Notebook    | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 650                         | Notebook    | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | Notebook    | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | Notebook    | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| Dell          | Latitude E6440              | Notebook    | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| Dell          | 0MWYPT A01                  | Desktop     | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | Notebook    | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| HP            | 3398                        | Desktop     | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| Dell          | Latitude E5270              | Notebook    | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| HP            | 3397                        | Desktop     | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | Notebook    | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | Notebook    | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | Notebook    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| HP            | 0A04h                       | Desktop     | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | Desktop     | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | Notebook    | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 3397                        | Desktop     | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 250 G3                      | Notebook    | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | Notebook    | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Unknown       | Unknown                     | Phone       | [4ff689998e](https://linux-hardware.org/?probe=4ff689998e) | Feb 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | Notebook    | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | Notebook    | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | Notebook    | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | Notebook    | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| HP            | 1494                        | Desktop     | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | Notebook    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | Notebook    | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | Notebook    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Dell          | 0D28YY A03                  | Desktop     | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | Notebook    | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| ASUSTek       | F5VL                        | Notebook    | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |
| Dell          | 0DR845                      | Desktop     | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Morocco/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 44        | 10.16%  |
| Ubuntu 22.04       | 38        | 8.78%   |
| Ubuntu 18.04       | 17        | 3.93%   |
| Debian 11          | 16        | 3.7%    |
| OpenMandriva 4.2   | 12        | 2.77%   |
| Fedora 39          | 12        | 2.77%   |
| Arch Rolling       | 12        | 2.77%   |
| KDE neon 20.04     | 11        | 2.54%   |
| ArcoLinux Rolling  | 11        | 2.54%   |
| OpenMandriva 4.3   | 10        | 2.31%   |
| Zorin 16           | 9         | 2.08%   |
| Pop!_OS 22.04      | 8         | 1.85%   |
| Zorin 17           | 7         | 1.62%   |
| Linux Mint 20.2    | 7         | 1.62%   |
| Fedora 38          | 7         | 1.62%   |
| OpenMandriva 23.01 | 6         | 1.39%   |
| Fedora 40          | 6         | 1.39%   |
| Ubuntu Unity 16.04 | 5         | 1.15%   |
| Ubuntu 24.04       | 5         | 1.15%   |
| Ubuntu 20.10       | 5         | 1.15%   |
| OpenMandriva 4.50  | 5         | 1.15%   |
| OpenMandriva 24.12 | 5         | 1.15%   |
| Linux Mint 20.3    | 5         | 1.15%   |
| Fedora 33          | 5         | 1.15%   |
| Elementary 7.1     | 5         | 1.15%   |
| Debian 12          | 5         | 1.15%   |
| Xero Rolling       | 4         | 0.92%   |
| Ubuntu 19.10       | 4         | 0.92%   |
| OpenMandriva 5.0   | 4         | 0.92%   |
| Linux Mint 21      | 4         | 0.92%   |
| Arch               | 4         | 0.92%   |
| Ubuntu 23.10       | 3         | 0.69%   |
| OpenMandriva 23.08 | 3         | 0.69%   |
| Manjaro            | 3         | 0.69%   |
| Linux Mint 21.3    | 3         | 0.69%   |
| Linux Mint 21.1    | 3         | 0.69%   |
| Linux Mint 19.3    | 3         | 0.69%   |
| Kali 2023.3        | 3         | 0.69%   |
| Fedora 41          | 3         | 0.69%   |
| Zorin 15           | 2         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 120       | 29.56%  |
| OpenMandriva | 45        | 11.08%  |
| Fedora       | 36        | 8.87%   |
| Linux Mint   | 25        | 6.16%   |
| Debian       | 23        | 5.67%   |
| Zorin        | 18        | 4.43%   |
| Arch         | 15        | 3.69%   |
| Pop!_OS      | 14        | 3.45%   |
| Kali         | 14        | 3.45%   |
| KDE neon     | 13        | 3.2%    |
| ArcoLinux    | 11        | 2.71%   |
| Manjaro      | 8         | 1.97%   |
| Elementary   | 7         | 1.72%   |
| Ubuntu Unity | 6         | 1.48%   |
| Xero         | 4         | 0.99%   |
| Xubuntu      | 3         | 0.74%   |
| Ubuntu MATE  | 3         | 0.74%   |
| Lubuntu      | 3         | 0.74%   |
| Endless      | 3         | 0.74%   |
| EndeavourOS  | 3         | 0.74%   |
| Void Linux   | 2         | 0.49%   |
| SteamOS      | 2         | 0.49%   |
| Raspbian     | 2         | 0.49%   |
| Parrot       | 2         | 0.49%   |
| openSUSE     | 2         | 0.49%   |
| Nobara       | 2         | 0.49%   |
| NixOS        | 2         | 0.49%   |
| Kubuntu      | 2         | 0.49%   |
| Garuda Linux | 2         | 0.49%   |
| CentOS       | 2         | 0.49%   |
| BlackPanther | 2         | 0.49%   |
| ROSA         | 1         | 0.25%   |
| RHEL         | 1         | 0.25%   |
| Pear OS      | 1         | 0.25%   |
| LMDE         | 1         | 0.25%   |
| Linux Lite   | 1         | 0.25%   |
| Deepin       | 1         | 0.25%   |
| BunsenLabs   | 1         | 0.25%   |
| blendOS      | 1         | 0.25%   |
| Bazzite      | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 2.63%   |
| 5.16.7-desktop-1omv4003  | 11        | 2.41%   |
| 6.2.0-33-generic         | 6         | 1.32%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.32%   |
| 6.12.1-desktop-1omv2490  | 5         | 1.1%    |
| 5.8.0-43-generic         | 5         | 1.1%    |
| 5.4.0-58-generic         | 5         | 1.1%    |
| 5.4.0-48-generic         | 5         | 1.1%    |
| 5.13.0-40-generic        | 5         | 1.1%    |
| 6.8.0-45-generic         | 4         | 0.88%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.88%   |
| 5.4.0-42-generic         | 4         | 0.88%   |
| 5.15.0-46-generic        | 4         | 0.88%   |
| 5.12.4-desktop-1omv4050  | 4         | 0.88%   |
| 5.11.0-37-generic        | 4         | 0.88%   |
| 6.8.4-200.fc39.x86_64    | 3         | 0.66%   |
| 6.6.2-desktop-1omv2390   | 3         | 0.66%   |
| 6.5.0-26-generic         | 3         | 0.66%   |
| 6.5.0-21-generic         | 3         | 0.66%   |
| 6.5.0-14-generic         | 3         | 0.66%   |
| 6.2.0-37-generic         | 3         | 0.66%   |
| 5.3.0-40-generic         | 3         | 0.66%   |
| 5.19.0-41-generic        | 3         | 0.66%   |
| 5.19.0-38-generic        | 3         | 0.66%   |
| 5.17.5-76051705-generic  | 3         | 0.66%   |
| 5.15.0-58-generic        | 3         | 0.66%   |
| 5.15.0-52-generic        | 3         | 0.66%   |
| 5.15.0-41-generic        | 3         | 0.66%   |
| 5.13.0-27-generic        | 3         | 0.66%   |
| 5.10.0-21-amd64          | 3         | 0.66%   |
| 6.8.0-39-generic         | 2         | 0.44%   |
| 6.7.9-arch1-1            | 2         | 0.44%   |
| 6.7.9-200.fc39.x86_64    | 2         | 0.44%   |
| 6.5.0-35-generic         | 2         | 0.44%   |
| 6.5.0-28-generic         | 2         | 0.44%   |
| 6.5.0-15-generic         | 2         | 0.44%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.44%   |
| 6.2.6-76060206-generic   | 2         | 0.44%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.44%   |
| 6.2.0-39-generic         | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 9.4%    |
| 5.15.0  | 41        | 9.4%    |
| 6.5.0   | 21        | 4.82%   |
| 5.8.0   | 18        | 4.13%   |
| 5.11.0  | 17        | 3.9%    |
| 5.10.0  | 17        | 3.9%    |
| 4.15.0  | 17        | 3.9%    |
| 6.2.0   | 15        | 3.44%   |
| 5.13.0  | 14        | 3.21%   |
| 5.3.0   | 12        | 2.75%   |
| 5.10.14 | 12        | 2.75%   |
| 5.16.7  | 11        | 2.52%   |
| 5.19.0  | 10        | 2.29%   |
| 6.8.0   | 9         | 2.06%   |
| 6.1.0   | 8         | 1.83%   |
| 6.1.1   | 6         | 1.38%   |
| 5.0.0   | 6         | 1.38%   |
| 6.12.1  | 5         | 1.15%   |
| 4.18.0  | 5         | 1.15%   |
| 6.7.9   | 4         | 0.92%   |
| 6.4.11  | 4         | 0.92%   |
| 6.10.3  | 4         | 0.92%   |
| 5.12.4  | 4         | 0.92%   |
| 6.8.4   | 3         | 0.69%   |
| 6.6.2   | 3         | 0.69%   |
| 6.2.9   | 3         | 0.69%   |
| 6.2.6   | 3         | 0.69%   |
| 6.11.2  | 3         | 0.69%   |
| 5.17.5  | 3         | 0.69%   |
| 5.14.0  | 3         | 0.69%   |
| 4.19.0  | 3         | 0.69%   |
| 6.9.6   | 2         | 0.46%   |
| 6.9.5   | 2         | 0.46%   |
| 6.8.7   | 2         | 0.46%   |
| 6.5.5   | 2         | 0.46%   |
| 6.5.3   | 2         | 0.46%   |
| 6.4.6   | 2         | 0.46%   |
| 6.4.10  | 2         | 0.46%   |
| 6.2.14  | 2         | 0.46%   |
| 6.11.5  | 2         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 11.03%  |
| 5.4     | 41        | 9.43%   |
| 5.10    | 35        | 8.05%   |
| 6.5     | 28        | 6.44%   |
| 6.2     | 24        | 5.52%   |
| 5.8     | 21        | 4.83%   |
| 5.11    | 20        | 4.6%    |
| 4.15    | 17        | 3.91%   |
| 6.8     | 16        | 3.68%   |
| 6.1     | 16        | 3.68%   |
| 5.13    | 16        | 3.68%   |
| 6.6     | 15        | 3.45%   |
| 5.19    | 14        | 3.22%   |
| 5.16    | 14        | 3.22%   |
| 5.3     | 12        | 2.76%   |
| 6.10    | 10        | 2.3%    |
| 6.4     | 9         | 2.07%   |
| 6.11    | 8         | 1.84%   |
| 6.9     | 7         | 1.61%   |
| 6.3     | 6         | 1.38%   |
| 6.12    | 6         | 1.38%   |
| 5.17    | 6         | 1.38%   |
| 5.14    | 6         | 1.38%   |
| 5.0     | 6         | 1.38%   |
| 4.18    | 6         | 1.38%   |
| 6.7     | 5         | 1.15%   |
| 5.18    | 5         | 1.15%   |
| 6.0     | 4         | 0.92%   |
| 5.12    | 4         | 0.92%   |
| 4.19    | 3         | 0.69%   |
| 5.7     | 1         | 0.23%   |
| 5.6     | 1         | 0.23%   |
| 4.9     | 1         | 0.23%   |
| 4.4     | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| 4.13    | 1         | 0.23%   |
| 3.18    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 384       | 96.48%  |
| i686   | 11        | 2.76%   |
| armv8l | 1         | 0.25%   |
| armv7l | 1         | 0.25%   |
| armv6l | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 209       | 50.73%  |
| KDE5            | 71        | 17.23%  |
| Unknown         | 33        | 8.01%   |
| XFCE            | 23        | 5.58%   |
| X-Cinnamon      | 19        | 4.61%   |
| KDE             | 8         | 1.94%   |
| Pantheon        | 7         | 1.7%    |
| Unity           | 6         | 1.46%   |
| MATE            | 6         | 1.46%   |
| KDE6            | 6         | 1.46%   |
| LXQt            | 4         | 0.97%   |
| i3              | 4         | 0.97%   |
| LXDE            | 3         | 0.73%   |
| Cinnamon        | 3         | 0.73%   |
| GNOME Flashback | 2         | 0.49%   |
| xmonad          | 1         | 0.24%   |
| sway            | 1         | 0.24%   |
| qtile           | 1         | 0.24%   |
| KDE4            | 1         | 0.24%   |
| Hyprland        | 1         | 0.24%   |
| DDE             | 1         | 0.24%   |
| Budgie          | 1         | 0.24%   |
| bspwm           | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 268       | 65.21%  |
| Wayland | 121       | 29.44%  |
| Unknown | 15        | 3.65%   |
| Tty     | 7         | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 42.82%  |
| SDDM    | 78        | 18.66%  |
| GDM3    | 62        | 14.83%  |
| GDM     | 51        | 12.2%   |
| LightDM | 43        | 10.29%  |
| TDM     | 4         | 0.96%   |
| KDM     | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 229       | 56.82%  |
| fr_FR   | 114       | 28.29%  |
| Unknown | 22        | 5.46%   |
| en_GB   | 16        | 3.97%   |
| C       | 6         | 1.49%   |
| de_DE   | 3         | 0.74%   |
| it_IT   | 2         | 0.5%    |
| es_ES   | 2         | 0.5%    |
| en_AG   | 2         | 0.5%    |
| ar_MA   | 2         | 0.5%    |
| fr_MA   | 1         | 0.25%   |
| fr_CH   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| ar_EG   | 1         | 0.25%   |
| ar_DZ   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 238       | 59.35%  |
| EFI  | 163       | 40.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 286       | 70.97%  |
| Btrfs   | 46        | 11.41%  |
| Overlay | 45        | 11.17%  |
| Tmpfs   | 16        | 3.97%   |
| Xfs     | 5         | 1.24%   |
| Unknown | 5         | 1.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 44.2%   |
| GPT     | 157       | 38.77%  |
| MBR     | 69        | 17.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 85.54%  |
| Yes       | 58        | 14.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 264       | 65.35%  |
| Yes       | 140       | 34.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 143       | 36.02%  |
| Dell                    | 68        | 17.13%  |
| Lenovo                  | 62        | 15.62%  |
| ASUSTek Computer        | 33        | 8.31%   |
| Acer                    | 14        | 3.53%   |
| Toshiba                 | 11        | 2.77%   |
| Apple                   | 7         | 1.76%   |
| Sony                    | 4         | 1.01%   |
| Packard Bell            | 4         | 1.01%   |
| Gigabyte Technology     | 4         | 1.01%   |
| Foxconn                 | 4         | 1.01%   |
| Unknown                 | 4         | 1.01%   |
| Samsung Electronics     | 3         | 0.76%   |
| Fujitsu                 | 3         | 0.76%   |
| Timi                    | 2         | 0.5%    |
| Raspberry Pi Foundation | 2         | 0.5%    |
| MSI                     | 2         | 0.5%    |
| Medion                  | 2         | 0.5%    |
| HUAWEI                  | 2         | 0.5%    |
| Google                  | 2         | 0.5%    |
| eMachines               | 2         | 0.5%    |
| American Megatrends     | 2         | 0.5%    |
| Valve                   | 1         | 0.25%   |
| TUXEDO                  | 1         | 0.25%   |
| TrekStor                | 1         | 0.25%   |
| Thomson                 | 1         | 0.25%   |
| SINTRONES               | 1         | 0.25%   |
| Razer                   | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |
| Mediacom                | 1         | 0.25%   |
| Linx                    | 1         | 0.25%   |
| LG Electronics          | 1         | 0.25%   |
| GPD                     | 1         | 0.25%   |
| Fujitsu Siemens         | 1         | 0.25%   |
| ECS                     | 1         | 0.25%   |
| Clevo                   | 1         | 0.25%   |
| Casper                  | 1         | 0.25%   |
| ASRock                  | 1         | 0.25%   |
| ACCENT                  | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 5         | 1.26%   |
| HP ProDesk 600 G1 TWR                  | 4         | 1.01%   |
| HP EliteBook 8440p                     | 4         | 1.01%   |
| HP Pavilion g6                         | 3         | 0.76%   |
| HP Notebook                            | 3         | 0.76%   |
| HP Laptop 15-dw3xxx                    | 3         | 0.76%   |
| HP EliteDesk 800 G1 TWR                | 3         | 0.76%   |
| HP EliteDesk 800 G1 SFF                | 3         | 0.76%   |
| HP EliteBook 840 G3                    | 3         | 0.76%   |
| HP EliteBook 840 G2                    | 3         | 0.76%   |
| ASUS X540LA                            | 3         | 0.76%   |
| Toshiba Satellite C660                 | 2         | 0.5%    |
| Timi TM1701                            | 2         | 0.5%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.5%    |
| Lenovo IdeaPad S145-15IIL 81W8         | 2         | 0.5%    |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.5%    |
| HP ZBook 15                            | 2         | 0.5%    |
| HP Z620 Workstation                    | 2         | 0.5%    |
| HP ProDesk 600 G1 SFF                  | 2         | 0.5%    |
| HP ProBook 6560b                       | 2         | 0.5%    |
| HP ProBook 650 G1                      | 2         | 0.5%    |
| HP ProBook 6470b                       | 2         | 0.5%    |
| HP ProBook 640 G1                      | 2         | 0.5%    |
| HP ProBook 450 G0                      | 2         | 0.5%    |
| HP Pavilion 15                         | 2         | 0.5%    |
| HP Laptop 15-ra0xx                     | 2         | 0.5%    |
| HP Laptop 15-bs0xx                     | 2         | 0.5%    |
| HP EliteDesk 800 G2 SFF                | 2         | 0.5%    |
| HP EliteBook 8460p                     | 2         | 0.5%    |
| HP EliteBook 840 G5                    | 2         | 0.5%    |
| HP EliteBook 830 G5                    | 2         | 0.5%    |
| HP Compaq Elite 8300 SFF               | 2         | 0.5%    |
| HP Compaq Elite 8300 CMT               | 2         | 0.5%    |
| HP Compaq dc7900 Small Form Factor     | 2         | 0.5%    |
| HP Compaq dc7800 Convertible Minitower | 2         | 0.5%    |
| HP Compaq 8200 Elite CMT PC            | 2         | 0.5%    |
| HP 250 G5 Notebook PC                  | 2         | 0.5%    |
| Dell Vostro 3500                       | 2         | 0.5%    |
| Dell OptiPlex 790                      | 2         | 0.5%    |
| Dell OptiPlex 7010                     | 2         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 38        | 9.57%   |
| Lenovo ThinkPad       | 32        | 8.06%   |
| HP EliteBook          | 27        | 6.8%    |
| HP Compaq             | 19        | 4.79%   |
| HP ProBook            | 18        | 4.53%   |
| HP Pavilion           | 12        | 3.02%   |
| Toshiba Satellite     | 11        | 2.77%   |
| HP Laptop             | 11        | 2.77%   |
| HP EliteDesk          | 10        | 2.52%   |
| Dell OptiPlex         | 10        | 2.52%   |
| Lenovo IdeaPad        | 9         | 2.27%   |
| Acer Aspire           | 9         | 2.27%   |
| HP ProDesk            | 8         | 2.02%   |
| Lenovo ThinkCentre    | 7         | 1.76%   |
| Dell Precision        | 7         | 1.76%   |
| Dell Vostro           | 6         | 1.51%   |
| HP ZBook              | 5         | 1.26%   |
| HP 250                | 5         | 1.26%   |
| ASUS ROG              | 5         | 1.26%   |
| Unknown               | 5         | 1.26%   |
| Dell Inspiron         | 4         | 1.01%   |
| Packard Bell EasyNote | 3         | 0.76%   |
| Lenovo ThinkBook      | 3         | 0.76%   |
| HP Notebook           | 3         | 0.76%   |
| Dell XPS              | 3         | 0.76%   |
| ASUS ZenBook          | 3         | 0.76%   |
| ASUS X540LA           | 3         | 0.76%   |
| Timi TM1701           | 2         | 0.5%    |
| RPi Raspberry         | 2         | 0.5%    |
| Lenovo ThinkStation   | 2         | 0.5%    |
| HP Z620               | 2         | 0.5%    |
| HP OMEN               | 2         | 0.5%    |
| HP dc5000             | 2         | 0.5%    |
| Fujitsu LIFEBOOK      | 2         | 0.5%    |
| ASUS X555LD           | 2         | 0.5%    |
| ASUS VivoBook         | 2         | 0.5%    |
| ASUS PRIME            | 2         | 0.5%    |
| Acer Nitro            | 2         | 0.5%    |
| Valve Jupiter         | 1         | 0.25%   |
| TUXEDO N13xWU         | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 43        | 10.83%  |
| 2018    | 38        | 9.57%   |
| 2011    | 35        | 8.82%   |
| 2014    | 32        | 8.06%   |
| 2010    | 32        | 8.06%   |
| 2016    | 29        | 7.3%    |
| 2020    | 25        | 6.3%    |
| 2012    | 25        | 6.3%    |
| 2015    | 22        | 5.54%   |
| 2017    | 20        | 5.04%   |
| 2021    | 19        | 4.79%   |
| 2019    | 18        | 4.53%   |
| 2007    | 12        | 3.02%   |
| 2008    | 11        | 2.77%   |
| 2022    | 9         | 2.27%   |
| 2009    | 9         | 2.27%   |
| 2023    | 5         | 1.26%   |
| 2024    | 4         | 1.01%   |
| 2006    | 3         | 0.76%   |
| 2004    | 3         | 0.76%   |
| Unknown | 2         | 0.5%    |
| 2005    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 285       | 71.79%  |
| Desktop        | 95        | 23.93%  |
| Convertible    | 7         | 1.76%   |
| All in one     | 4         | 1.01%   |
| System on chip | 2         | 0.5%    |
| Tablet         | 2         | 0.5%    |
| Phone          | 1         | 0.25%   |
| Mini pc        | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 380       | 94.53%  |
| Enabled  | 22        | 5.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 394       | 99.24%  |
| Yes  | 3         | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 33.67%  |
| 3.01-4.0    | 91        | 22.69%  |
| 16.01-24.0  | 56        | 13.97%  |
| 8.01-16.0   | 54        | 13.47%  |
| 1.01-2.0    | 24        | 5.99%   |
| 32.01-64.0  | 17        | 4.24%   |
| 24.01-32.0  | 8         | 2%      |
| 2.01-3.0    | 7         | 1.75%   |
| 64.01-256.0 | 6         | 1.5%    |
| 0.51-1.0    | 2         | 0.5%    |
| 0.01-0.5    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 146       | 33.64%  |
| 2.01-3.0  | 132       | 30.41%  |
| 4.01-8.0  | 68        | 15.67%  |
| 3.01-4.0  | 52        | 11.98%  |
| 0.51-1.0  | 24        | 5.53%   |
| 8.01-16.0 | 8         | 1.84%   |
| 0.01-0.5  | 4         | 0.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 301       | 75.06%  |
| 2      | 77        | 19.2%   |
| 3      | 18        | 4.49%   |
| 4      | 5         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 56.42%  |
| Yes       | 173       | 43.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 351       | 88.41%  |
| No        | 46        | 11.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 356       | 89.22%  |
| No        | 43        | 10.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 61.19%  |
| No        | 156       | 38.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 397       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Casablanca             | 116       | 26.85%  |
| Marrakesh              | 44        | 10.19%  |
| Agadir                 | 32        | 7.41%   |
| Rabat                  | 30        | 6.94%   |
| Fes                    | 30        | 6.94%   |
| Tangier                | 22        | 5.09%   |
| Salé                  | 19        | 4.4%    |
| Kenitra                | 17        | 3.94%   |
| Oujda                  | 15        | 3.47%   |
| Meknes                 | 14        | 3.24%   |
| Khouribga              | 7         | 1.62%   |
| El Jadida              | 6         | 1.39%   |
| Tiznit                 | 5         | 1.16%   |
| Taza                   | 5         | 1.16%   |
| Nador                  | 5         | 1.16%   |
| Tétouan               | 4         | 0.93%   |
| Safi                   | 4         | 0.93%   |
| Berkane                | 4         | 0.93%   |
| Beni Mellal            | 4         | 0.93%   |
| Temara                 | 3         | 0.69%   |
| Guelmim                | 3         | 0.69%   |
| Youssoufia             | 2         | 0.46%   |
| Skhirate               | 2         | 0.46%   |
| Mohammedia             | 2         | 0.46%   |
| Martil                 | 2         | 0.46%   |
| Berrechid              | 2         | 0.46%   |
| Azamor                 | 2         | 0.46%   |
| Tit Mellil             | 1         | 0.23%   |
| Targuist               | 1         | 0.23%   |
| Taourirt               | 1         | 0.23%   |
| Taounate               | 1         | 0.23%   |
| Sidi Slimane           | 1         | 0.23%   |
| Sidi Lmokhtar          | 1         | 0.23%   |
| Sidi Kacem             | 1         | 0.23%   |
| Sidi Allal El Bahraoui | 1         | 0.23%   |
| Settat                 | 1         | 0.23%   |
| Sefrou                 | 1         | 0.23%   |
| Oulmes                 | 1         | 0.23%   |
| Ouirgane               | 1         | 0.23%   |
| Oued Zem               | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 71        | 91     | 14.43%  |
| Samsung Electronics         | 70        | 84     | 14.23%  |
| WDC                         | 69        | 90     | 14.02%  |
| Toshiba                     | 50        | 68     | 10.16%  |
| Hitachi                     | 25        | 30     | 5.08%   |
| Unknown                     | 23        | 30     | 4.67%   |
| SanDisk                     | 20        | 22     | 4.07%   |
| SK hynix                    | 15        | 18     | 3.05%   |
| Intel                       | 15        | 17     | 3.05%   |
| HGST                        | 15        | 17     | 3.05%   |
| Micron Technology           | 11        | 14     | 2.24%   |
| Kingston                    | 10        | 16     | 2.03%   |
| Apple                       | 8         | 8      | 1.63%   |
| China                       | 7         | 8      | 1.42%   |
| PNY                         | 6         | 7      | 1.22%   |
| LITEON                      | 6         | 6      | 1.22%   |
| KIOXIA                      | 6         | 6      | 1.22%   |
| Unknown                     | 5         | 5      | 1.02%   |
| Fujitsu                     | 4         | 4      | 0.81%   |
| Crucial                     | 4         | 5      | 0.81%   |
| Phison                      | 3         | 4      | 0.61%   |
| KingFast                    | 3         | 4      | 0.61%   |
| TwinMOS                     | 2         | 2      | 0.41%   |
| Supersonic                  | 2         | 6      | 0.41%   |
| LITEONIT                    | 2         | 2      | 0.41%   |
| Lexar                       | 2         | 2      | 0.41%   |
| Kingston Technology Company | 2         | 2      | 0.41%   |
| KingDian                    | 2         | 8      | 0.41%   |
| GOODRAM                     | 2         | 2      | 0.41%   |
| AFOX                        | 2         | 2      | 0.41%   |
| Transcend                   | 1         | 1      | 0.2%    |
| Team                        | 1         | 1      | 0.2%    |
| SPCC                        | 1         | 2      | 0.2%    |
| Silicon Motion              | 1         | 1      | 0.2%    |
| ShiJi                       | 1         | 2      | 0.2%    |
| SG                          | 1         | 1      | 0.2%    |
| Realtek Semiconductor       | 1         | 1      | 0.2%    |
| RCESSD                      | 1         | 1      | 0.2%    |
| Phison Electronics          | 1         | 1      | 0.2%    |
| O2 Micro                    | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 6         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 1.16%   |
| Unknown MMC Card  64GB                              | 5         | 0.97%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.97%   |
| Unknown                                             | 5         | 0.97%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 4         | 0.78%   |
| Unknown MMC Card  32GB                              | 4         | 0.78%   |
| Toshiba MQ01ABD050 500GB                            | 4         | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 0.78%   |
| Samsung NVMe SSD Drive 512GB                        | 4         | 0.78%   |
| Samsung MZVLW256HEHP-000L7 256GB                    | 4         | 0.78%   |
| Intel SSDSC2BF180A4H 180GB                          | 4         | 0.78%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.78%   |
| Toshiba MQ01ACF050 500GB                            | 3         | 0.58%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.58%   |
| Seagate ST9500325AS 500GB                           | 3         | 0.58%   |
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 0.58%   |
| Seagate ST3250312AS 250GB                           | 3         | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 0.58%   |
| Samsung NVMe SSD Drive 256GB                        | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3         | 0.58%   |
| LITEON IT LCS-128L9S-HP 128GB SSD                   | 3         | 0.58%   |
| Hitachi HUA723020ALA641 2TB                         | 3         | 0.58%   |
| HGST HTS725050A7E630 500GB                          | 3         | 0.58%   |
| WDC WD800JD-00LSA0 80GB                             | 2         | 0.39%   |
| WDC WD5000LPCX-80VHAT1 500GB                        | 2         | 0.39%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 2         | 0.39%   |
| WDC WD5000AZLX-60K2TA0 500GB                        | 2         | 0.39%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 2         | 0.39%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 0.39%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 2         | 0.39%   |
| Unknown MMC Card  16GB                              | 2         | 0.39%   |
| TwinMOS SSD 256GB                                   | 2         | 0.39%   |
| Toshiba MQ01ABD050V -63 500GB                       | 2         | 0.39%   |
| Toshiba KXG50ZNV256G 256GB                          | 2         | 0.39%   |
| Toshiba DT01ACA100 LENOVO 1TB                       | 2         | 0.39%   |
| Supersonic SUPERSONIC256 256GB                      | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 91     | 30.47%  |
| WDC                 | 63        | 84     | 27.04%  |
| Toshiba             | 40        | 50     | 17.17%  |
| Hitachi             | 25        | 30     | 10.73%  |
| HGST                | 15        | 17     | 6.44%   |
| Samsung Electronics | 8         | 11     | 3.43%   |
| Fujitsu             | 4         | 4      | 1.72%   |
| Apple               | 3         | 3      | 1.29%   |
| Maxtor              | 1         | 1      | 0.43%   |
| Magnetic Data       | 1         | 1      | 0.43%   |
| IBM/Hitachi         | 1         | 1      | 0.43%   |
| HPE                 | 1         | 2      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 32     | 19.7%   |
| SanDisk             | 10        | 11     | 7.58%   |
| Kingston            | 9         | 15     | 6.82%   |
| Micron Technology   | 8         | 11     | 6.06%   |
| Intel               | 7         | 8      | 5.3%    |
| China               | 7         | 8      | 5.3%    |
| PNY                 | 6         | 7      | 4.55%   |
| LITEON              | 6         | 6      | 4.55%   |
| SK hynix            | 4         | 6      | 3.03%   |
| Crucial             | 4         | 5      | 3.03%   |
| Unknown             | 4         | 4      | 3.03%   |
| Toshiba             | 3         | 3      | 2.27%   |
| KingFast            | 3         | 3      | 2.27%   |
| Apple               | 3         | 3      | 2.27%   |
| TwinMOS             | 2         | 2      | 1.52%   |
| Supersonic          | 2         | 3      | 1.52%   |
| LITEONIT            | 2         | 2      | 1.52%   |
| Lexar               | 2         | 2      | 1.52%   |
| KingDian            | 2         | 8      | 1.52%   |
| GOODRAM             | 2         | 2      | 1.52%   |
| AFOX                | 2         | 2      | 1.52%   |
| WDC                 | 1         | 1      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| Team                | 1         | 1      | 0.76%   |
| SPCC                | 1         | 2      | 0.76%   |
| RCESSD              | 1         | 1      | 0.76%   |
| Mushkin             | 1         | 1      | 0.76%   |
| MSI                 | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Indilinx            | 1         | 1      | 0.76%   |
| HS-SSD-E100         | 1         | 1      | 0.76%   |
| Hewlett-Packard     | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| Geonix              | 1         | 1      | 0.76%   |
| BIWIN               | 1         | 1      | 0.76%   |
| Bestoss             | 1         | 1      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |
| A-DATA Technology   | 1         | 1      | 0.76%   |
| 2.5"                | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 215       | 295    | 46.94%  |
| SSD     | 125       | 162    | 27.29%  |
| NVMe    | 92        | 118    | 20.09%  |
| MMC     | 22        | 29     | 4.8%    |
| Unknown | 4         | 10     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 311       | 462    | 72.49%  |
| NVMe | 92        | 117    | 21.45%  |
| MMC  | 22        | 29     | 5.13%   |
| SAS  | 4         | 6      | 0.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 241       | 324    | 72.16%  |
| 0.51-1.0   | 80        | 115    | 23.95%  |
| 1.01-2.0   | 9         | 13     | 2.69%   |
| 2.01-3.0   | 2         | 3      | 0.6%    |
| 3.01-4.0   | 1         | 1      | 0.3%    |
| 4.01-10.0  | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 128       | 31.07%  |
| 251-500        | 99        | 24.03%  |
| 1-20           | 43        | 10.44%  |
| 501-1000       | 42        | 10.19%  |
| 51-100         | 41        | 9.95%   |
| 21-50          | 25        | 6.07%   |
| 1001-2000      | 17        | 4.13%   |
| Unknown        | 8         | 1.94%   |
| More than 3000 | 7         | 1.7%    |
| 2001-3000      | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 181       | 41.9%   |
| 21-50          | 97        | 22.45%  |
| 101-250        | 57        | 13.19%  |
| 51-100         | 53        | 12.27%  |
| 251-500        | 21        | 4.86%   |
| Unknown        | 8         | 1.85%   |
| 501-1000       | 6         | 1.39%   |
| More than 3000 | 4         | 0.93%   |
| 1001-2000      | 4         | 0.93%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 5.26%   |
| Seagate ST9500325AS 500GB                        | 3         | 4      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                  | 2         | 2      | 3.51%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 3.51%   |
| Hitachi HDS721680PLA380 80GB                     | 2         | 3      | 3.51%   |
| HGST HTS545050A7E680 500GB                       | 2         | 3      | 3.51%   |
| WDC WD800AAJS-60WAA0 80GB                        | 1         | 1      | 1.75%   |
| WDC WD7500BPKX-80HPJT0 752GB                     | 1         | 1      | 1.75%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 1.75%   |
| WDC WD2500BEVS-22UST0 250GB                      | 1         | 1      | 1.75%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 1.75%   |
| WDC WD2500AAJS-60Z0A0 250GB                      | 1         | 1      | 1.75%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 2      | 1.75%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 7      | 1.75%   |
| WDC WD10JPVT-00A1YT0 1TB                         | 1         | 1      | 1.75%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 1.75%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 1.75%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 1.75%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 1.75%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 1.75%   |
| Seagate ST9500423AS 500GB                        | 1         | 1      | 1.75%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.75%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 1.75%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST340016A 40GB                           | 1         | 1      | 1.75%   |
| Seagate ST340014AS 40GB                          | 1         | 1      | 1.75%   |
| Seagate ST3250312AS 250GB                        | 1         | 1      | 1.75%   |
| Seagate ST3160318AS 160GB                        | 1         | 1      | 1.75%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 1.75%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.75%   |
| Samsung Electronics MZ7PD128HAFV-000H7 128GB SSD | 1         | 1      | 1.75%   |
| Samsung Electronics HD080HJ/ 80GB                | 1         | 1      | 1.75%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 1.75%   |
| Maxtor 6E040L0 41GB                              | 1         | 1      | 1.75%   |
| Kingston SA400S37480G 480GB SSD                  | 1         | 2      | 1.75%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 1.75%   |
| HPE MM1000GBKAL 1TB                              | 1         | 2      | 1.75%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 29.82%  |
| WDC                 | 9         | 16     | 15.79%  |
| Toshiba             | 8         | 8      | 14.04%  |
| Hitachi             | 6         | 8      | 10.53%  |
| HGST                | 5         | 6      | 8.77%   |
| Samsung Electronics | 3         | 3      | 5.26%   |
| Fujitsu             | 2         | 2      | 3.51%   |
| SanDisk             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Maxtor              | 1         | 1      | 1.75%   |
| Kingston            | 1         | 2      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| HPE                 | 1         | 2      | 1.75%   |
| Apple               | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 33.33%  |
| WDC                 | 9         | 16     | 17.65%  |
| Toshiba             | 8         | 8      | 15.69%  |
| Hitachi             | 6         | 8      | 11.76%  |
| HGST                | 5         | 6      | 9.8%    |
| Fujitsu             | 2         | 2      | 3.92%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| Maxtor              | 1         | 1      | 1.96%   |
| HPE                 | 1         | 2      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 63     | 89.29%  |
| SSD  | 6         | 7      | 10.71%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 40%     |
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 20%     |
| SK hynix BC501 NVMe 256GB                  | 1         | 1      | 20%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 5      | 60%     |
| SK hynix            | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 223       | 332    | 51.86%  |
| Works    | 146       | 205    | 33.95%  |
| Malfunc  | 56        | 70     | 13.02%  |
| Failed   | 5         | 7      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 319       | 71.85%  |
| Samsung Electronics              | 38        | 8.56%   |
| AMD                              | 25        | 5.63%   |
| SanDisk                          | 13        | 2.93%   |
| SK hynix                         | 11        | 2.48%   |
| Toshiba America Info Systems     | 7         | 1.58%   |
| KIOXIA                           | 6         | 1.35%   |
| Phison Electronics               | 4         | 0.9%    |
| Nvidia                           | 3         | 0.68%   |
| Micron Technology                | 3         | 0.68%   |
| Kingston Technology Company      | 3         | 0.68%   |
| Silicon Integrated Systems [SiS] | 2         | 0.45%   |
| Solidigm                         | 1         | 0.23%   |
| Silicon Motion                   | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| O2 Micro                         | 1         | 0.23%   |
| Micron/Crucial Technology        | 1         | 0.23%   |
| LSI Logic / Symbios Logic        | 1         | 0.23%   |
| JMicron Technology               | 1         | 0.23%   |
| Broadcom / LSI                   | 1         | 0.23%   |
| Apple                            | 1         | 0.23%   |
| ADATA Technology                 | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 5.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 28        | 5.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 27        | 5.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 23        | 4.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19        | 3.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 3.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 3.17%   |
| Intel SATA Controller [RAID mode]                                                       | 15        | 2.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 14        | 2.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 2.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 1.98%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 9         | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 4         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.79%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 3         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3         | 0.6%    |
| Phison E12 NVMe Controller                                                              | 3         | 0.6%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.6%    |
| Intel SSD 660P Series                                                                   | 3         | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 3         | 0.6%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 0.6%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 273       | 58.46%  |
| NVMe | 92        | 19.7%   |
| RAID | 58        | 12.42%  |
| IDE  | 40        | 8.57%   |
| SAS  | 3         | 0.64%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 359       | 90.43%  |
| AMD    | 35        | 8.82%   |
| ARM    | 3         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 9         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 1.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 7         | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 1.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 6         | 1.51%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6         | 1.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 6         | 1.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 5         | 1.26%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 5         | 1.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 1.26%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5         | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.26%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 5         | 1.26%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 5         | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 1.26%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 5         | 1.26%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.01%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.01%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.01%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.76%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 0.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 0.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.76%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2         | 0.5%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.5%    |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 145       | 36.52%  |
| Intel Core i7           | 63        | 15.87%  |
| Intel Core i3           | 45        | 11.34%  |
| Other                   | 32        | 8.06%   |
| Intel Core 2 Duo        | 20        | 5.04%   |
| Intel Celeron           | 14        | 3.53%   |
| Intel Xeon              | 11        | 2.77%   |
| Intel Atom              | 8         | 2.02%   |
| AMD Ryzen 5             | 8         | 2.02%   |
| AMD Ryzen 7             | 5         | 1.26%   |
| Intel Pentium Dual-Core | 4         | 1.01%   |
| Intel Pentium           | 3         | 0.76%   |
| AMD Ryzen 9             | 3         | 0.76%   |
| AMD E1                  | 3         | 0.76%   |
| Intel Pentium 4         | 2         | 0.5%    |
| Intel Core i9           | 2         | 0.5%    |
| Intel Core 2            | 2         | 0.5%    |
| ARM BCM                 | 2         | 0.5%    |
| AMD C-60                | 2         | 0.5%    |
| AMD Athlon 64 X2        | 2         | 0.5%    |
| AMD A8                  | 2         | 0.5%    |
| AMD A6                  | 2         | 0.5%    |
| Intel Pentium Silver    | 1         | 0.25%   |
| Intel Pentium M         | 1         | 0.25%   |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| Intel Core m5           | 1         | 0.25%   |
| Intel Core 2 Quad       | 1         | 0.25%   |
| Intel Core              | 1         | 0.25%   |
| Intel Celeron M         | 1         | 0.25%   |
| ARM AArch64             | 1         | 0.25%   |
| AMD Ryzen 7 PRO         | 1         | 0.25%   |
| AMD Ryzen 3 PRO         | 1         | 0.25%   |
| AMD Ryzen 3             | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD Athlon XP           | 1         | 0.25%   |
| AMD A4                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 209       | 52.64%  |
| 4      | 134       | 33.75%  |
| 6      | 17        | 4.28%   |
| 8      | 11        | 2.77%   |
| 1      | 10        | 2.52%   |
| 12     | 5         | 1.26%   |
| 16     | 4         | 1.01%   |
| 10     | 4         | 1.01%   |
| 14     | 2         | 0.5%    |
| 24     | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 392       | 98.74%  |
| 2      | 5         | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 280       | 70.53%  |
| 1      | 117       | 29.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 387       | 97.48%  |
| 32-bit         | 6         | 1.51%   |
| Unknown        | 4         | 1.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 42.65%  |
| 0x206a7    | 27        | 6.62%   |
| 0x306c3    | 19        | 4.66%   |
| 0x306a9    | 17        | 4.17%   |
| 0x806ea    | 14        | 3.43%   |
| 0x306d4    | 14        | 3.43%   |
| 0x40651    | 12        | 2.94%   |
| 0x806ec    | 10        | 2.45%   |
| 0x20655    | 9         | 2.21%   |
| 0x1067a    | 9         | 2.21%   |
| 0x806c1    | 7         | 1.72%   |
| 0x506e3    | 7         | 1.72%   |
| 0x806e9    | 6         | 1.47%   |
| 0x6fd      | 6         | 1.47%   |
| 0x406e3    | 6         | 1.47%   |
| 0x20652    | 5         | 1.23%   |
| 0x30678    | 4         | 0.98%   |
| 0x10676    | 4         | 0.98%   |
| 0x906e9    | 3         | 0.74%   |
| 0x90675    | 3         | 0.74%   |
| 0x6fb      | 3         | 0.74%   |
| 0x206d7    | 3         | 0.74%   |
| 0x0a50000c | 3         | 0.74%   |
| 0x08701021 | 3         | 0.74%   |
| 0x906ea    | 2         | 0.49%   |
| 0x706e5    | 2         | 0.49%   |
| 0x406c4    | 2         | 0.49%   |
| 0x406c3    | 2         | 0.49%   |
| 0x08108102 | 2         | 0.49%   |
| 0x07030105 | 2         | 0.49%   |
| 0x0700010f | 2         | 0.49%   |
| 0x05000119 | 2         | 0.49%   |
| 0xf41      | 1         | 0.25%   |
| 0xf29      | 1         | 0.25%   |
| 0xb06a3    | 1         | 0.25%   |
| 0x806eb    | 1         | 0.25%   |
| 0x806d1    | 1         | 0.25%   |
| 0x706a1    | 1         | 0.25%   |
| 0x6ec      | 1         | 0.25%   |
| 0x6e8      | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 59        | 14.86%  |
| KabyLake         | 56        | 14.11%  |
| SandyBridge      | 37        | 9.32%   |
| Skylake          | 34        | 8.56%   |
| Westmere         | 26        | 6.55%   |
| IvyBridge        | 26        | 6.55%   |
| Broadwell        | 21        | 5.29%   |
| Penryn           | 18        | 4.53%   |
| TigerLake        | 17        | 4.28%   |
| Silvermont       | 14        | 3.53%   |
| Unknown          | 14        | 3.53%   |
| Core             | 12        | 3.02%   |
| Alderlake Hybrid | 9         | 2.27%   |
| Zen 3            | 7         | 1.76%   |
| Icelake          | 6         | 1.51%   |
| Zen 2            | 5         | 1.26%   |
| Zen+             | 4         | 1.01%   |
| Bobcat           | 4         | 1.01%   |
| P6               | 3         | 0.76%   |
| CometLake        | 3         | 0.76%   |
| Bonnell          | 3         | 0.76%   |
| Puma             | 2         | 0.5%    |
| NetBurst         | 2         | 0.5%    |
| Nehalem          | 2         | 0.5%    |
| K8 Hammer        | 2         | 0.5%    |
| Jaguar           | 2         | 0.5%    |
| Goldmont plus    | 2         | 0.5%    |
| Piledriver       | 1         | 0.25%   |
| K6               | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| K10              | 1         | 0.25%   |
| Gracemont        | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |
| Excavator        | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 314       | 66.67%  |
| Nvidia                           | 100       | 21.23%  |
| AMD                              | 56        | 11.89%  |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 6.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 5.02%   |
| Intel UHD Graphics 620                                                                   | 21        | 4.39%   |
| Intel HD Graphics 5500                                                                   | 19        | 3.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 3.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 3.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 3.14%   |
| Intel HD Graphics 530                                                                    | 14        | 2.93%   |
| Intel HD Graphics 620                                                                    | 11        | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.26%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.05%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 4         | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.84%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.63%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 3         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.63%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.63%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.63%   |
| Intel HD Graphics 630                                                                    | 3         | 0.63%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 3         | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 239       | 60.05%  |
| Intel + Nvidia | 58        | 14.57%  |
| 1 x AMD        | 40        | 10.05%  |
| 1 x Nvidia     | 38        | 9.55%   |
| Intel + AMD    | 12        | 3.02%   |
| Other          | 3         | 0.75%   |
| AMD + Nvidia   | 3         | 0.75%   |
| 2 x Intel      | 2         | 0.5%    |
| 2 x Nvidia     | 1         | 0.25%   |
| 2 x AMD        | 1         | 0.25%   |
| 1 x SiS        | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 331       | 82.13%  |
| Proprietary | 44        | 10.92%  |
| Unknown     | 28        | 6.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 72.17%  |
| 1.01-2.0   | 41        | 10.1%   |
| 0.01-0.5   | 34        | 8.37%   |
| 3.01-4.0   | 17        | 4.19%   |
| 0.51-1.0   | 16        | 3.94%   |
| 7.01-8.0   | 4         | 0.99%   |
| 2.01-3.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 56        | 14.47%  |
| AU Optronics            | 54        | 13.95%  |
| LG Display              | 52        | 13.44%  |
| Chimei Innolux          | 50        | 12.92%  |
| BOE                     | 42        | 10.85%  |
| Hewlett-Packard         | 23        | 5.94%   |
| Dell                    | 22        | 5.68%   |
| Lenovo                  | 10        | 2.58%   |
| InfoVision              | 9         | 2.33%   |
| Sharp                   | 7         | 1.81%   |
| Goldstar                | 7         | 1.81%   |
| Apple                   | 7         | 1.81%   |
| LG Philips              | 5         | 1.29%   |
| Chi Mei Optoelectronics | 5         | 1.29%   |
| Iiyama                  | 4         | 1.03%   |
| BenQ                    | 3         | 0.78%   |
| Acer                    | 3         | 0.78%   |
| Philips                 | 2         | 0.52%   |
| PANDA                   | 2         | 0.52%   |
| MSI                     | 2         | 0.52%   |
| HannStar                | 2         | 0.52%   |
| Fujitsu Siemens         | 2         | 0.52%   |
| Ancor Communications    | 2         | 0.52%   |
| Valve                   | 1         | 0.26%   |
| TMX                     | 1         | 0.26%   |
| TCL                     | 1         | 0.26%   |
| Sony                    | 1         | 0.26%   |
| RTK                     | 1         | 0.26%   |
| NEC Computers           | 1         | 0.26%   |
| NCS                     | 1         | 0.26%   |
| MiTAC                   | 1         | 0.26%   |
| Mi                      | 1         | 0.26%   |
| Medion                  | 1         | 0.26%   |
| LGD                     | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| CNC                     | 1         | 0.26%   |
| ASUSTek Computer        | 1         | 0.26%   |
| AOC                     | 1         | 0.26%   |
| Unknown                 | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 0.77%   |
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                        | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 0.77%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.77%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.51%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                          | 2         | 0.51%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch              | 2         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.51%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.51%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.51%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch             | 2         | 0.51%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch                | 2         | 0.51%   |
| Dell S2719H DELD0CE 1920x1080 600x340mm 27.2-inch                        | 2         | 0.51%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                        | 2         | 0.51%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 294x165mm 13.3-inch         | 2         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.51%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 2         | 0.51%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO42EC 1366x768 344x193mm 15.5-inch            | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 132       | 34.83%  |
| 1366x768 (WXGA)    | 130       | 34.3%   |
| 1600x900 (HD+)     | 25        | 6.6%    |
| 1440x900 (WXGA+)   | 14        | 3.69%   |
| 1680x1050 (WSXGA+) | 13        | 3.43%   |
| 1280x1024 (SXGA)   | 12        | 3.17%   |
| 3840x2160 (4K)     | 11        | 2.9%    |
| 1280x800 (WXGA)    | 10        | 2.64%   |
| 2560x1440 (QHD)    | 5         | 1.32%   |
| 1920x1200 (WUXGA)  | 5         | 1.32%   |
| 1024x600           | 4         | 1.06%   |
| 3840x2400          | 2         | 0.53%   |
| 2880x1800          | 2         | 0.53%   |
| 2560x1600          | 2         | 0.53%   |
| 2240x1400          | 2         | 0.53%   |
| 800x1280           | 1         | 0.26%   |
| 2520x1680          | 1         | 0.26%   |
| 2160x1440          | 1         | 0.26%   |
| 1920x515           | 1         | 0.26%   |
| 1680x945           | 1         | 0.26%   |
| 1400x1050          | 1         | 0.26%   |
| 1360x768           | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |
| 1152x864           | 1         | 0.26%   |
| 1024x768 (XGA)     | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 150       | 38.46%  |
| 13      | 43        | 11.03%  |
| 14      | 42        | 10.77%  |
| 24      | 20        | 5.13%   |
| 17      | 20        | 5.13%   |
| 12      | 16        | 4.1%    |
| 23      | 15        | 3.85%   |
| 19      | 12        | 3.08%   |
| 22      | 11        | 2.82%   |
| 27      | 10        | 2.56%   |
| 18      | 9         | 2.31%   |
| 21      | 8         | 2.05%   |
| Unknown | 6         | 1.54%   |
| 20      | 5         | 1.28%   |
| 11      | 4         | 1.03%   |
| 31      | 3         | 0.77%   |
| 16      | 3         | 0.77%   |
| 10      | 3         | 0.77%   |
| 84      | 2         | 0.51%   |
| 54      | 2         | 0.51%   |
| 72      | 1         | 0.26%   |
| 58      | 1         | 0.26%   |
| 52      | 1         | 0.26%   |
| 43      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| 7       | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 219       | 56.59%  |
| 201-300     | 44        | 11.37%  |
| 501-600     | 41        | 10.59%  |
| 401-500     | 39        | 10.08%  |
| 351-400     | 23        | 5.94%   |
| Unknown     | 6         | 1.55%   |
| 601-700     | 5         | 1.29%   |
| 1001-1500   | 4         | 1.03%   |
| 1501-2000   | 3         | 0.78%   |
| 701-800     | 1         | 0.26%   |
| 901-1000    | 1         | 0.26%   |
| 1-100       | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 295       | 78.46%  |
| 16/10   | 55        | 14.63%  |
| 5/4     | 12        | 3.19%   |
| Unknown | 5         | 1.33%   |
| 4/3     | 4         | 1.06%   |
| 3/2     | 3         | 0.8%    |
| 3.73    | 1         | 0.27%   |
| 0.67    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 150       | 38.66%  |
| 81-90          | 68        | 17.53%  |
| 201-250        | 43        | 11.08%  |
| 151-200        | 23        | 5.93%   |
| 71-80          | 15        | 3.87%   |
| 61-70          | 15        | 3.87%   |
| 141-150        | 12        | 3.09%   |
| 301-350        | 10        | 2.58%   |
| 121-130        | 10        | 2.58%   |
| More than 1000 | 7         | 1.8%    |
| 251-300        | 7         | 1.8%    |
| Unknown        | 6         | 1.55%   |
| 51-60          | 4         | 1.03%   |
| 351-500        | 4         | 1.03%   |
| 111-120        | 4         | 1.03%   |
| 41-50          | 3         | 0.77%   |
| 131-140        | 3         | 0.77%   |
| 91-100         | 2         | 0.52%   |
| 1-40           | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 134       | 34.9%   |
| 121-160       | 103       | 26.82%  |
| 51-100        | 99        | 25.78%  |
| 161-240       | 31        | 8.07%   |
| 1-50          | 7         | 1.82%   |
| Unknown       | 6         | 1.56%   |
| More than 240 | 4         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 359       | 89.08%  |
| 2     | 28        | 6.95%   |
| 0     | 16        | 3.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 234       | 37.99%  |
| Realtek Semiconductor            | 158       | 25.65%  |
| Qualcomm Atheros                 | 62        | 10.06%  |
| Broadcom                         | 51        | 8.28%   |
| Ralink Technology                | 34        | 5.52%   |
| Ralink                           | 15        | 2.44%   |
| TP-Link                          | 9         | 1.46%   |
| Broadcom Limited                 | 9         | 1.46%   |
| Sierra Wireless                  | 6         | 0.97%   |
| Marvell Technology Group         | 5         | 0.81%   |
| Dell                             | 5         | 0.81%   |
| Xiaomi                           | 3         | 0.49%   |
| Samsung Electronics              | 3         | 0.49%   |
| Nvidia                           | 3         | 0.49%   |
| MediaTek                         | 2         | 0.32%   |
| Lenovo                           | 2         | 0.32%   |
| Huawei Technologies              | 2         | 0.32%   |
| D-Link System                    | 2         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Qualcomm Atheros Communications  | 1         | 0.16%   |
| Qualcomm                         | 1         | 0.16%   |
| NetGear                          | 1         | 0.16%   |
| Microchip Technology             | 1         | 0.16%   |
| JMicron Technology               | 1         | 0.16%   |
| Gemtek                           | 1         | 0.16%   |
| Fibocom                          | 1         | 0.16%   |
| D-Link                           | 1         | 0.16%   |
| Arduino SA                       | 1         | 0.16%   |
| Aquantia                         | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 95        | 12.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 31        | 4.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 3.92%   |
| Intel Wireless 8265 / 8275                                             | 23        | 3.01%   |
| Intel Ethernet Connection I217-LM                                      | 23        | 3.01%   |
| Ralink MT7601U Wireless Adapter                                        | 18        | 2.35%   |
| Intel Wireless 8260                                                    | 18        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                         | 14        | 1.83%   |
| Intel Wireless 7265                                                    | 13        | 1.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 1.7%    |
| Intel 82577LM Gigabit Network Connection                               | 13        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.44%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 1.31%   |
| Intel Centrino Advanced-N 6200                                         | 10        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 10        | 1.31%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 1.05%   |
| Intel Wireless 7260                                                    | 8         | 1.05%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.05%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 7         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 7         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                         | 5         | 0.65%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 161       | 41.82%  |
| Qualcomm Atheros                | 56        | 14.55%  |
| Realtek Semiconductor           | 48        | 12.47%  |
| Broadcom                        | 37        | 9.61%   |
| Ralink Technology               | 34        | 8.83%   |
| Ralink                          | 15        | 3.9%    |
| TP-Link                         | 9         | 2.34%   |
| Broadcom Limited                | 7         | 1.82%   |
| Sierra Wireless                 | 6         | 1.56%   |
| Dell                            | 4         | 1.04%   |
| MediaTek                        | 2         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| NetGear                         | 1         | 0.26%   |
| Gemtek                          | 1         | 0.26%   |
| Fibocom                         | 1         | 0.26%   |
| D-Link System                   | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 23        | 5.91%   |
| Ralink MT7601U Wireless Adapter                                | 18        | 4.63%   |
| Intel Wireless 8260                                            | 18        | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 3.86%   |
| Ralink RT5370 Wireless Adapter                                 | 14        | 3.6%    |
| Intel Wireless 7265                                            | 13        | 3.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.83%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 2.57%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 2.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 2.57%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 2.06%   |
| Intel Wireless 7260                                            | 8         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 2.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.29%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.29%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.29%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.03%   |
| Intel WiFi Link 5100                                           | 4         | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 4         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.03%   |
| Sierra Wireless EM7455                                         | 3         | 0.77%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.77%   |
| Intel Wireless 3165                                            | 3         | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.77%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 3         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 170       | 46.58%  |
| Realtek Semiconductor            | 136       | 37.26%  |
| Broadcom                         | 20        | 5.48%   |
| Qualcomm Atheros                 | 13        | 3.56%   |
| Marvell Technology Group         | 5         | 1.37%   |
| Xiaomi                           | 3         | 0.82%   |
| Nvidia                           | 3         | 0.82%   |
| Broadcom Limited                 | 3         | 0.82%   |
| Samsung Electronics              | 2         | 0.55%   |
| Lenovo                           | 2         | 0.55%   |
| Huawei Technologies              | 2         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Qualcomm                         | 1         | 0.27%   |
| Microchip Technology             | 1         | 0.27%   |
| JMicron Technology               | 1         | 0.27%   |
| D-Link System                    | 1         | 0.27%   |
| Aquantia                         | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 95        | 25.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 31        | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 8.06%   |
| Intel Ethernet Connection I217-LM                                      | 23        | 6.18%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 4.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 3.49%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 3.49%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 2.42%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 2.15%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 2.15%   |
| Intel Ethernet Connection I217-V                                       | 5         | 1.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 1.08%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.81%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.81%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.81%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.81%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.81%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 3         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.54%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 0.54%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.54%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2         | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.54%   |
| Intel 82578DM Gigabit Network Connection                               | 2         | 0.54%   |
| Huawei FOA-LX9                                                         | 2         | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.54%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                    | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 356       | 50.14%  |
| Ethernet | 350       | 49.3%   |
| Modem    | 4         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 296       | 73.45%  |
| Ethernet | 107       | 26.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 267       | 67.09%  |
| 1     | 114       | 28.64%  |
| 0     | 9         | 2.26%   |
| 3     | 7         | 1.76%   |
| 7     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 397       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 46.34%  |
| Realtek Semiconductor           | 27        | 10.98%  |
| Qualcomm Atheros Communications | 23        | 9.35%   |
| Broadcom                        | 18        | 7.32%   |
| IMC Networks                    | 9         | 3.66%   |
| Dell                            | 8         | 3.25%   |
| Cambridge Silicon Radio         | 8         | 3.25%   |
| Lite-On Technology              | 7         | 2.85%   |
| Hewlett-Packard                 | 7         | 2.85%   |
| Apple                           | 7         | 2.85%   |
| Ralink                          | 5         | 2.03%   |
| Toshiba                         | 4         | 1.63%   |
| Foxconn / Hon Hai               | 4         | 1.63%   |
| ASUSTek Computer                | 2         | 0.81%   |
| Ralink Technology               | 1         | 0.41%   |
| Foxconn International           | 1         | 0.41%   |
| Alps Electric                   | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 23.58%  |
| Intel AX201 Bluetooth                               | 20        | 8.13%   |
| Realtek Bluetooth Radio                             | 18        | 7.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 4.47%   |
| Intel AX200 Bluetooth                               | 10        | 4.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 3.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 3.25%   |
| Intel AX211 Bluetooth                               | 7         | 2.85%   |
| IMC Networks Bluetooth Device                       | 7         | 2.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 2.44%   |
| Ralink RT3290 Bluetooth                             | 5         | 2.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 2.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.03%   |
| Dell DW375 Bluetooth Module                         | 5         | 2.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.63%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.22%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.22%   |
| Toshiba Bluetooth Device                            | 2         | 0.81%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.81%   |
| Dell Wireless 360 Bluetooth                         | 2         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.81%   |
| Apple Bluetooth Host Controller                     | 2         | 0.81%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.41%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.41%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.41%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.41%   |
| Lite-On Bluetooth Device                            | 1         | 0.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.41%   |
| IMC Networks Wireless_Device                        | 1         | 0.41%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 353       | 72.93%  |
| Nvidia                                       | 63        | 13.02%  |
| AMD                                          | 46        | 9.5%    |
| GN Netcom                                    | 3         | 0.62%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.41%   |
| Lenovo                                       | 2         | 0.41%   |
| EDFIER                                       | 2         | 0.41%   |
| ASUSTek Computer                             | 2         | 0.41%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.21%   |
| Trust                                        | 1         | 0.21%   |
| Nordic Semiconductor ASA                     | 1         | 0.21%   |
| Medeli Electronics                           | 1         | 0.21%   |
| Logitech                                     | 1         | 0.21%   |
| Kingston Technology                          | 1         | 0.21%   |
| Hewlett-Packard                              | 1         | 0.21%   |
| Generalplus Technology                       | 1         | 0.21%   |
| GEMBIRD                                      | 1         | 0.21%   |
| Focusrite-Novation                           | 1         | 0.21%   |
| C-Media Electronics                          | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 49        | 8.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 5.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 4.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 4.29%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 4.29%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 3.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 3.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 3.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 2.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 2.74%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 14        | 2.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.03%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.03%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.86%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 5         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.69%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4         | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 89        | 30.69%  |
| SK hynix                                | 75        | 25.86%  |
| Micron Technology                       | 36        | 12.41%  |
| Kingston                                | 27        | 9.31%   |
| Unknown                                 | 9         | 3.1%    |
| Ramaxel Technology                      | 7         | 2.41%   |
| Nanya Technology                        | 6         | 2.07%   |
| Elpida                                  | 6         | 2.07%   |
| A-DATA Technology                       | 6         | 2.07%   |
| Crucial                                 | 5         | 1.72%   |
| Corsair                                 | 4         | 1.38%   |
| Transcend                               | 2         | 0.69%   |
| Sesame                                  | 2         | 0.69%   |
| Qimonda                                 | 2         | 0.69%   |
| Unknown                                 | 2         | 0.69%   |
| Wilk                                    | 1         | 0.34%   |
| Unknown (83DA)                          | 1         | 0.34%   |
| Unknown (0B85)                          | 1         | 0.34%   |
| Toshiba                                 | 1         | 0.34%   |
| Team                                    | 1         | 0.34%   |
| TakeMS                                  | 1         | 0.34%   |
| Silicon Power Computer & Communications | 1         | 0.34%   |
| Silicon Power                           | 1         | 0.34%   |
| G.Skill                                 | 1         | 0.34%   |
| Avant                                   | 1         | 0.34%   |
| ASint Technology                        | 1         | 0.34%   |
| Apacer                                  | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 1.58%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 4         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 1.27%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 4         | 1.27%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 3         | 0.95%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s        | 3         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 3         | 0.95%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 0.95%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 3         | 0.95%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s              | 3         | 0.95%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 3         | 0.95%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 2         | 0.63%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s        | 2         | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.63%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.63%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.63%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.63%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s    | 2         | 0.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 0.63%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.63%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 2         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.63%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s       | 2         | 0.63%   |
| Micron RAM 8KTF51264HZ-1G6P1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 96        | 42.48%  |
| DDR4    | 88        | 38.94%  |
| DDR2    | 11        | 4.87%   |
| SDRAM   | 10        | 4.42%   |
| LPDDR4  | 5         | 2.21%   |
| LPDDR3  | 5         | 2.21%   |
| LPDDR5  | 4         | 1.77%   |
| DDR5    | 3         | 1.33%   |
| Unknown | 3         | 1.33%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 152       | 69.41%  |
| DIMM         | 51        | 23.29%  |
| Row Of Chips | 12        | 5.48%   |
| Unknown      | 2         | 0.91%   |
| RIMM         | 1         | 0.46%   |
| Chip         | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 89        | 35.6%   |
| 8192  | 84        | 33.6%   |
| 2048  | 31        | 12.4%   |
| 16384 | 27        | 10.8%   |
| 1024  | 11        | 4.4%    |
| 32768 | 4         | 1.6%    |
| 512   | 2         | 0.8%    |
| 256   | 1         | 0.4%    |
| 128   | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 25.1%   |
| 2667    | 35        | 13.94%  |
| 3200    | 29        | 11.55%  |
| 2133    | 18        | 7.17%   |
| 2400    | 15        | 5.98%   |
| 1334    | 15        | 5.98%   |
| 1333    | 15        | 5.98%   |
| 667     | 7         | 2.79%   |
| Unknown | 5         | 1.99%   |
| 1867    | 4         | 1.59%   |
| 1648    | 4         | 1.59%   |
| 1067    | 4         | 1.59%   |
| 1066    | 4         | 1.59%   |
| 800     | 4         | 1.59%   |
| 6400    | 3         | 1.2%    |
| 3600    | 3         | 1.2%    |
| 4800    | 2         | 0.8%    |
| 4199    | 2         | 0.8%    |
| 3266    | 2         | 0.8%    |
| 2666    | 2         | 0.8%    |
| 975     | 2         | 0.8%    |
| 7467    | 1         | 0.4%    |
| 5600    | 1         | 0.4%    |
| 4267    | 1         | 0.4%    |
| 4000    | 1         | 0.4%    |
| 3733    | 1         | 0.4%    |
| 3467    | 1         | 0.4%    |
| 1866    | 1         | 0.4%    |
| 1800    | 1         | 0.4%    |
| 1639    | 1         | 0.4%    |
| 1331    | 1         | 0.4%    |
| 400     | 1         | 0.4%    |
| 333     | 1         | 0.4%    |
| 266     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Konica Minolta  | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Konica Minolta C364Series | 1         | 20%     |
| HP LaserJet P1005         | 1         | 20%     |
| HP LaserJet M402dn        | 1         | 20%     |
| HP Deskjet 3510 series    | 1         | 20%     |
| Canon MB2000 series       | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 72        | 27.38%  |
| IMC Networks                           | 25        | 9.51%   |
| Realtek Semiconductor                  | 21        | 7.98%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 7.6%    |
| Sunplus Innovation Technology          | 17        | 6.46%   |
| Lite-On Technology                     | 15        | 5.7%    |
| Quanta                                 | 13        | 4.94%   |
| Microdia                               | 13        | 4.94%   |
| Suyin                                  | 12        | 4.56%   |
| Bison Electronics                      | 7         | 2.66%   |
| Apple                                  | 7         | 2.66%   |
| Luxvisions Innotech Limited            | 6         | 2.28%   |
| Syntek                                 | 4         | 1.52%   |
| Ricoh                                  | 4         | 1.52%   |
| Alcor Micro                            | 4         | 1.52%   |
| Logitech                               | 3         | 1.14%   |
| Z-Star Microelectronics                | 2         | 0.76%   |
| Silicon Motion                         | 2         | 0.76%   |
| Shinetech                              | 2         | 0.76%   |
| ALi                                    | 2         | 0.76%   |
| Acer                                   | 2         | 0.76%   |
| Sunplus Technology                     | 1         | 0.38%   |
| Sonix Technology                       | 1         | 0.38%   |
| Samsung Electronics                    | 1         | 0.38%   |
| OPPO Electronics                       | 1         | 0.38%   |
| OmniVision Technologies                | 1         | 0.38%   |
| Nebraska Furniture Mart                | 1         | 0.38%   |
| LG Innotek                             | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| Jieli Technology                       | 1         | 0.38%   |
| icSpring                               | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 12        | 4.53%   |
| IMC Networks Integrated Camera                              | 8         | 3.02%   |
| Chicony HP Webcam                                           | 7         | 2.64%   |
| Lite-On HP HD Camera                                        | 6         | 2.26%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 2.26%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 1.89%   |
| Realtek Integrated_Webcam_HD                                | 5         | 1.89%   |
| Microdia Integrated_Webcam_HD                               | 5         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 4         | 1.51%   |
| Microdia Integrated Webcam                                  | 4         | 1.51%   |
| Lite-On HP HD Webcam                                        | 4         | 1.51%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 1.51%   |
| Chicony HP HD Camera                                        | 4         | 1.51%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 1.51%   |
| Realtek USB Camera                                          | 3         | 1.13%   |
| Quanta HP Wide Vision HD Camera                             | 3         | 1.13%   |
| Quanta HD WebCam                                            | 3         | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.13%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.13%   |
| Chicony TOSHIBA Web Camera - HD                             | 3         | 1.13%   |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.13%   |
| Chicony HP HD Webcam [Fixed]                                | 3         | 1.13%   |
| Chicony HP HD Webcam                                        | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 3         | 1.13%   |
| Syntek Lenovo EasyCamera                                    | 2         | 0.75%   |
| Suyin Sony Visual Communication Camera                      | 2         | 0.75%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 0.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.75%   |
| Sunplus HP Universal Camera                                 | 2         | 0.75%   |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 0.75%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 0.75%   |
| Realtek Integrated Webcam_HD                                | 2         | 0.75%   |
| Realtek Integrated Webcam HD                                | 2         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 0.75%   |
| Luxvisions Innotech Limited HP HD Camera                    | 2         | 0.75%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 0.75%   |
| IMC Networks Integrated Webcam                              | 2         | 0.75%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 38        | 66.67%  |
| Synaptics                  | 10        | 17.54%  |
| Elan Microelectronics      | 4         | 7.02%   |
| Upek                       | 2         | 3.51%   |
| Shenzhen Goodix Technology | 2         | 3.51%   |
| Focal-systems.Corp         | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 21.05%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.53%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 8.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 8.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.26%   |
| Validity Sensors VFS491                                                    | 2         | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.51%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.51%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.75%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 64.29%  |
| Alcor Micro | 10        | 23.81%  |
| O2 Micro    | 4         | 9.52%   |
| Lenovo      | 1         | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 26.19%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 14.29%  |
| Broadcom 5880                                                                | 6         | 14.29%  |
| Broadcom 58200                                                               | 4         | 9.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 254       | 62.25%  |
| 1     | 118       | 28.92%  |
| 2     | 29        | 7.11%   |
| 3     | 5         | 1.23%   |
| 5     | 2         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 29.23%  |
| Graphics card            | 41        | 21.03%  |
| Chipcard                 | 35        | 17.95%  |
| Net/wireless             | 21        | 10.77%  |
| Communication controller | 7         | 3.59%   |
| Storage                  | 6         | 3.08%   |
| Camera                   | 6         | 3.08%   |
| Bluetooth                | 6         | 3.08%   |
| Unassigned class         | 5         | 2.56%   |
| Multimedia controller    | 4         | 2.05%   |
| Sound                    | 3         | 1.54%   |
| Net/ethernet             | 2         | 1.03%   |
| Network                  | 1         | 0.51%   |
| Modem                    | 1         | 0.51%   |


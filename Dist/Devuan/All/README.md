Devuan - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Devuan/Desktop/README.md) and [notebooks](/Dist/Devuan/Notebook/README.md).

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

Total: 120

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | Notebook    | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [a698baa5f6](https://linux-hardware.org/?probe=a698baa5f6) | Jun 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [5da801634f](https://linux-hardware.org/?probe=5da801634f) | Jun 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | Desktop     | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | Notebook    | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [1aa66a62c4](https://linux-hardware.org/?probe=1aa66a62c4) | Mar 26, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                       | Desktop     | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | Notebook    | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| HP            | 1495                        | Desktop     | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | Notebook    | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| Toshiba       | Satellite M40X              | Notebook    | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ffd8fa11af](https://linux-hardware.org/?probe=ffd8fa11af) | Sep 16, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d65f9a48fd](https://linux-hardware.org/?probe=d65f9a48fd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | Notebook    | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | Notebook    | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | Notebook    | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| HP            | 1825                        | Desktop     | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| Google        | Panther                     | Desktop     | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| HP            | ProBook 6475b               | Notebook    | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | Notebook    | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [ee6bb68e8c](https://linux-hardware.org/?probe=ee6bb68e8c) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L                | Desktop     | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4               | Desktop     | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Dell          | 0GXM1W A04                  | Desktop     | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Dell          | Precision 7530              | Notebook    | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b708be8d9e](https://linux-hardware.org/?probe=b708be8d9e) | Nov 10, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Intel         | HURONRIVER                  | Desktop     | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | Desktop     | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| Nokia         | N900                        | Notebook    | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | Notebook    | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | Notebook    | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| HP            | 1791                        | Desktop     | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [32b487459e](https://linux-hardware.org/?probe=32b487459e) | Sep 16, 2020 |
| ASUSTek       | K52F                        | Notebook    | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | Notebook    | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                        | Desktop     | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | Notebook    | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | Notebook    | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| ASUSTek       | P5PE-VM                     | Desktop     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| Dell          | Inspiron 1564               | Notebook    | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | Notebook    | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |
| ASRock        | G31M-VS2                    | Desktop     | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                     | Desktop     | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [59ca47d9e7](https://linux-hardware.org/?probe=59ca47d9e7) | Apr 12, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 37        | 37.37%  |
| Devuan 3                | 30        | 30.3%   |
| Devuan Testing/unstable | 15        | 15.15%  |
| Devuan 2.1              | 7         | 7.07%   |
| Devuan 5                | 5         | 5.05%   |
| Devuan                  | 2         | 2.02%   |
| Devuan 3.0              | 1         | 1.01%   |
| Devuan 2.0              | 1         | 1.01%   |
| Devuan 1.0.0            | 1         | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 92        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 9         | 8.82%   |
| 5.10.0-8-amd64            | 7         | 6.86%   |
| 4.19.0-9-amd64            | 6         | 5.88%   |
| 4.19.0-14-amd64           | 6         | 5.88%   |
| 4.19.0-16-amd64           | 5         | 4.9%    |
| 5.10.0-13-amd64           | 4         | 3.92%   |
| 5.10.0-11-amd64           | 4         | 3.92%   |
| 5.10.0-10-amd64           | 4         | 3.92%   |
| 5.7.0-2-amd64             | 3         | 2.94%   |
| 4.19.0-12-amd64           | 3         | 2.94%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 1.96%   |
| 5.18.0-1-amd64            | 2         | 1.96%   |
| 5.15.0-2-amd64            | 2         | 1.96%   |
| 5.10.0-6-amd64            | 2         | 1.96%   |
| 5.10.0-14-amd64           | 2         | 1.96%   |
| 4.19.0-17-amd64           | 2         | 1.96%   |
| 4.19.0-13-amd64           | 2         | 1.96%   |
| 4.19.0-10-amd64           | 2         | 1.96%   |
| 5.9.0-4-amd64             | 1         | 0.98%   |
| 5.9.0-1-amd64             | 1         | 0.98%   |
| 5.8.0-3-amd64             | 1         | 0.98%   |
| 5.8.0-1-amd64             | 1         | 0.98%   |
| 5.7.19-server1            | 1         | 0.98%   |
| 5.7.0-1-amd64             | 1         | 0.98%   |
| 5.6.0-2-amd64             | 1         | 0.98%   |
| 5.16.0-1-amd64            | 1         | 0.98%   |
| 5.15.5-xanmod1            | 1         | 0.98%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 0.98%   |
| 5.14.0-kali2-amd64        | 1         | 0.98%   |
| 5.14.0-4-amd64            | 1         | 0.98%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 0.98%   |
| 5.10.0-7-amd64            | 1         | 0.98%   |
| 5.10.0-5-amd64            | 1         | 0.98%   |
| 5.10.0-4-amd64            | 1         | 0.98%   |
| 5.10.0-2-amd64            | 1         | 0.98%   |
| 5.10.0-15-amd64           | 1         | 0.98%   |
| 5.10.0-1-amd64            | 1         | 0.98%   |
| 5.1.21                    | 1         | 0.98%   |
| 5.0.7                     | 1         | 0.98%   |
| 4.9.0-15-amd64            | 1         | 0.98%   |
| 4.9.0-14-amd64            | 1         | 0.98%   |
| 4.9.0-14-686-pae          | 1         | 0.98%   |
| 4.9.0-14-686              | 1         | 0.98%   |
| 4.9.0-11-amd64            | 1         | 0.98%   |
| 4.9.0-11-686-pae          | 1         | 0.98%   |
| 4.9.0-11-686              | 1         | 0.98%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 0.98%   |
| 4.4.195-antix.1-amd64-smp | 1         | 0.98%   |
| 4.19.112                  | 1         | 0.98%   |
| 4.19.0-17-686-pae         | 1         | 0.98%   |
| 4.19.0-1-amd64            | 1         | 0.98%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 0.98%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 37        | 37.37%  |
| 4.19.0   | 27        | 27.27%  |
| 4.9.0    | 8         | 8.08%   |
| 5.7.0    | 6         | 6.06%   |
| 5.15.0   | 3         | 3.03%   |
| 5.9.0    | 2         | 2.02%   |
| 5.8.0    | 2         | 2.02%   |
| 5.18.0   | 2         | 2.02%   |
| 5.14.0   | 2         | 2.02%   |
| 5.7.19   | 1         | 1.01%   |
| 5.6.0    | 1         | 1.01%   |
| 5.16.0   | 1         | 1.01%   |
| 5.15.5   | 1         | 1.01%   |
| 5.11.0   | 1         | 1.01%   |
| 5.1.21   | 1         | 1.01%   |
| 5.0.7    | 1         | 1.01%   |
| 4.4.195  | 1         | 1.01%   |
| 4.19.112 | 1         | 1.01%   |
| 4.18.0   | 1         | 1.01%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 37        | 37.37%  |
| 4.19    | 28        | 28.28%  |
| 4.9     | 8         | 8.08%   |
| 5.7     | 7         | 7.07%   |
| 5.15    | 4         | 4.04%   |
| 5.9     | 2         | 2.02%   |
| 5.8     | 2         | 2.02%   |
| 5.18    | 2         | 2.02%   |
| 5.14    | 2         | 2.02%   |
| 5.6     | 1         | 1.01%   |
| 5.16    | 1         | 1.01%   |
| 5.11    | 1         | 1.01%   |
| 5.1     | 1         | 1.01%   |
| 5.0     | 1         | 1.01%   |
| 4.4     | 1         | 1.01%   |
| 4.18    | 1         | 1.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 92.39%  |
| i686   | 6         | 6.52%   |
| armv7l | 1         | 1.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 39        | 39.8%   |
| MATE       | 14        | 14.29%  |
| KDE5       | 14        | 14.29%  |
| Unknown    | 14        | 14.29%  |
| i3         | 5         | 5.1%    |
| LXDE       | 4         | 4.08%   |
| LXQt       | 2         | 2.04%   |
| Cinnamon   | 2         | 2.04%   |
| X-Cinnamon | 1         | 1.02%   |
| Openbox    | 1         | 1.02%   |
| GNOME      | 1         | 1.02%   |
| awesome    | 1         | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 88.3%   |
| Tty     | 8         | 8.51%   |
| Unknown | 3         | 3.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 36        | 37.89%  |
| Unknown | 25        | 26.32%  |
| LightDM | 24        | 25.26%  |
| SDDM    | 6         | 6.32%   |
| XDM     | 2         | 2.11%   |
| NODM    | 1         | 1.05%   |
| GDM3    | 1         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 28        | 29.79%  |
| en_GB       | 18        | 19.15%  |
| ru_RU       | 8         | 8.51%   |
| Unknown     | 7         | 7.45%   |
| C           | 5         | 5.32%   |
| pt_BR       | 4         | 4.26%   |
| fr_FR       | 4         | 4.26%   |
| sk_SK       | 3         | 3.19%   |
| en_AU       | 3         | 3.19%   |
| pl_PL       | 2         | 2.13%   |
| fr_BE       | 2         | 2.13%   |
| es_ES       | 2         | 2.13%   |
| en_NZ       | 2         | 2.13%   |
| it_IT       | 1         | 1.06%   |
| es_SV       | 1         | 1.06%   |
| en_US.utf-8 | 1         | 1.06%   |
| en_SG       | 1         | 1.06%   |
| en_CA       | 1         | 1.06%   |
| de_AT       | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 54        | 58.06%  |
| EFI  | 39        | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 78        | 84.78%  |
| Unknown | 5         | 5.43%   |
| Btrfs   | 4         | 4.35%   |
| Overlay | 2         | 2.17%   |
| OveXlay | 1         | 1.09%   |
| Ext3    | 1         | 1.09%   |
| Ext2    | 1         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 50        | 51.55%  |
| MBR     | 37        | 38.14%  |
| Unknown | 10        | 10.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 75.53%  |
| Yes       | 23        | 24.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 75.27%  |
| Yes       | 23        | 24.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 18.48%  |
| ASUSTek Computer    | 12        | 13.04%  |
| Gigabyte Technology | 10        | 10.87%  |
| Dell                | 10        | 10.87%  |
| Hewlett-Packard     | 9         | 9.78%   |
| Acer                | 5         | 5.43%   |
| MSI                 | 4         | 4.35%   |
| ASRock              | 4         | 4.35%   |
| Toshiba             | 2         | 2.17%   |
| Intel               | 2         | 2.17%   |
| Fujitsu Siemens     | 2         | 2.17%   |
| Teclast             | 1         | 1.09%   |
| Sun Microsystems    | 1         | 1.09%   |
| Samsung Electronics | 1         | 1.09%   |
| Online Labs         | 1         | 1.09%   |
| Notebook            | 1         | 1.09%   |
| Nokia               | 1         | 1.09%   |
| MTC                 | 1         | 1.09%   |
| Microsoft           | 1         | 1.09%   |
| IP3 Tech            | 1         | 1.09%   |
| IBM                 | 1         | 1.09%   |
| Google              | 1         | 1.09%   |
| Fujitsu             | 1         | 1.09%   |
| Chuwi               | 1         | 1.09%   |
| Apple               | 1         | 1.09%   |
| AMI                 | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite M40X                                                                   | 1         | 1.09%   |
| Toshiba Satellite L655                                                                   | 1         | 1.09%   |
| Teclast F6 Plus                                                                          | 1         | 1.09%   |
| Sun Microsystems Ultra 24                                                                | 1         | 1.09%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.09%   |
| Online Labs SR                                                                           | 1         | 1.09%   |
| Notebook W230ST                                                                          | 1         | 1.09%   |
| Nokia N900                                                                               | 1         | 1.09%   |
| MTC Montara-GML                                                                          | 1         | 1.09%   |
| MSI MS-7B84                                                                              | 1         | 1.09%   |
| MSI MS-7B53                                                                              | 1         | 1.09%   |
| MSI MS-7A34                                                                              | 1         | 1.09%   |
| MSI MS-1688                                                                              | 1         | 1.09%   |
| Microsoft Surface Pro 4                                                                  | 1         | 1.09%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 1.09%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 1.09%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.09%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.09%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.09%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.09%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.09%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.09%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.09%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.09%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.09%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.09%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.09%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.09%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.09%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.09%   |
| IP3 Tech HeroBox                                                                         | 1         | 1.09%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 1.09%   |
| Intel AHV                                                                                | 1         | 1.09%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.09%   |
| HP Z220 SFF Workstation                                                                  | 1         | 1.09%   |
| HP ProDesk 600 G1 SFF                                                                    | 1         | 1.09%   |
| HP ProBook 6475b                                                                         | 1         | 1.09%   |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 1.09%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.09%   |
| HP Notebook                                                                              | 1         | 1.09%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 1.09%   |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 1.09%   |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 1.09%   |
| Google Panther                                                                           | 1         | 1.09%   |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 1.09%   |
| Gigabyte P55A-UD3                                                                        | 1         | 1.09%   |
| Gigabyte MZGLKBP-00                                                                      | 1         | 1.09%   |
| Gigabyte H310M S2H 2.0                                                                   | 1         | 1.09%   |
| Gigabyte H170-HD3-CF                                                                     | 1         | 1.09%   |
| Gigabyte H170-HD3                                                                        | 1         | 1.09%   |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 1.09%   |
| Gigabyte B75M-D3V                                                                        | 1         | 1.09%   |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 1.09%   |
| Gigabyte 970A-DS3P                                                                       | 1         | 1.09%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.09%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.09%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.09%   |
| Dell Precision 7530                                                                      | 1         | 1.09%   |
| Dell OptiPlex 9020                                                                       | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 13.04%  |
| Dell OptiPlex           | 4         | 4.35%   |
| Dell Latitude           | 4         | 4.35%   |
| Acer Aspire             | 4         | 4.35%   |
| Lenovo IdeaPad          | 3         | 3.26%   |
| Toshiba Satellite       | 2         | 2.17%   |
| HP Pavilion             | 2         | 2.17%   |
| ASUS PRIME              | 2         | 2.17%   |
| Teclast F6              | 1         | 1.09%   |
| Sun Microsystems Ultra  | 1         | 1.09%   |
| Samsung 355V4C          | 1         | 1.09%   |
| Online Labs SR          | 1         | 1.09%   |
| Notebook W230ST         | 1         | 1.09%   |
| Nokia N900              | 1         | 1.09%   |
| MTC Montara-GML         | 1         | 1.09%   |
| MSI MS-7B84             | 1         | 1.09%   |
| MSI MS-7B53             | 1         | 1.09%   |
| MSI MS-7A34             | 1         | 1.09%   |
| MSI MS-1688             | 1         | 1.09%   |
| Microsoft Surface       | 1         | 1.09%   |
| Lenovo Yoga             | 1         | 1.09%   |
| Lenovo ThinkStation     | 1         | 1.09%   |
| IP3 Tech HeroBox        | 1         | 1.09%   |
| Intel D815EEA           | 1         | 1.09%   |
| Intel AHV               | 1         | 1.09%   |
| IBM ThinkPad            | 1         | 1.09%   |
| HP Z220                 | 1         | 1.09%   |
| HP ProDesk              | 1         | 1.09%   |
| HP ProBook              | 1         | 1.09%   |
| HP Notebook             | 1         | 1.09%   |
| HP Laptop               | 1         | 1.09%   |
| HP EliteDesk            | 1         | 1.09%   |
| HP Compaq               | 1         | 1.09%   |
| Google Panther          | 1         | 1.09%   |
| Gigabyte Z390           | 1         | 1.09%   |
| Gigabyte P55A-UD3       | 1         | 1.09%   |
| Gigabyte MZGLKBP-00     | 1         | 1.09%   |
| Gigabyte H310M          | 1         | 1.09%   |
| Gigabyte H170-HD3-CF    | 1         | 1.09%   |
| Gigabyte H170-HD3       | 1         | 1.09%   |
| Gigabyte GA-G41M-ES2L   | 1         | 1.09%   |
| Gigabyte B75M-D3V       | 1         | 1.09%   |
| Gigabyte B450           | 1         | 1.09%   |
| Gigabyte 970A-DS3P      | 1         | 1.09%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.09%   |
| Fujitsu Siemens AMILO   | 1         | 1.09%   |
| Fujitsu LIFEBOOK        | 1         | 1.09%   |
| Dell Precision          | 1         | 1.09%   |
| Dell Inspiron           | 1         | 1.09%   |
| Chuwi Hi10              | 1         | 1.09%   |
| ASUS X555LJ             | 1         | 1.09%   |
| ASUS ROG                | 1         | 1.09%   |
| ASUS P5PE-VM            | 1         | 1.09%   |
| ASUS P5G41T-M           | 1         | 1.09%   |
| ASUS Maximus            | 1         | 1.09%   |
| ASUS K55VJ              | 1         | 1.09%   |
| ASUS K52F               | 1         | 1.09%   |
| ASUS F1A55-M            | 1         | 1.09%   |
| ASUS EX-A320M-GAMING    | 1         | 1.09%   |
| ASUS All                | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 12        | 13.04%  |
| 2012    | 11        | 11.96%  |
| 2019    | 10        | 10.87%  |
| 2011    | 7         | 7.61%   |
| 2014    | 6         | 6.52%   |
| 2017    | 5         | 5.43%   |
| 2015    | 5         | 5.43%   |
| 2013    | 5         | 5.43%   |
| 2009    | 5         | 5.43%   |
| 2016    | 4         | 4.35%   |
| 2010    | 4         | 4.35%   |
| 2008    | 4         | 4.35%   |
| 2021    | 3         | 3.26%   |
| 2006    | 3         | 3.26%   |
| 2020    | 2         | 2.17%   |
| 2007    | 2         | 2.17%   |
| 2005    | 2         | 2.17%   |
| 2000    | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 46.74%  |
| Desktop     | 41        | 44.57%  |
| Tablet      | 3         | 3.26%   |
| Mini pc     | 3         | 3.26%   |
| Convertible | 2         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 91        | 98.91%  |
| Enabled  | 1         | 1.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 96.74%  |
| Yes  | 3         | 3.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 22.83%  |
| 4.01-8.0    | 20        | 21.74%  |
| 16.01-24.0  | 17        | 18.48%  |
| 3.01-4.0    | 14        | 15.22%  |
| 32.01-64.0  | 7         | 7.61%   |
| 1.01-2.0    | 6         | 6.52%   |
| 0.01-0.5    | 3         | 3.26%   |
| 2.01-3.0    | 2         | 2.17%   |
| 64.01-256.0 | 2         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 36        | 36%     |
| 4.01-8.0   | 19        | 19%     |
| 2.01-3.0   | 17        | 17%     |
| 0.51-1.0   | 13        | 13%     |
| 3.01-4.0   | 7         | 7%      |
| 0.01-0.5   | 4         | 4%      |
| 8.01-16.0  | 3         | 3%      |
| 32.01-64.0 | 1         | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 61.96%  |
| 2      | 17        | 18.48%  |
| 3      | 9         | 9.78%   |
| 4      | 5         | 5.43%   |
| 5      | 3         | 3.26%   |
| 6      | 1         | 1.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 65.59%  |
| Yes       | 32        | 34.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 90.22%  |
| No        | 9         | 9.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 61.29%  |
| No        | 36        | 38.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 63.04%  |
| Yes       | 34        | 36.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 9         | 9.78%   |
| USA         | 8         | 8.7%    |
| France      | 8         | 8.7%    |
| Germany     | 7         | 7.61%   |
| Ukraine     | 6         | 6.52%   |
| Brazil      | 6         | 6.52%   |
| Poland      | 4         | 4.35%   |
| Grenada     | 4         | 4.35%   |
| UK          | 3         | 3.26%   |
| Slovakia    | 3         | 3.26%   |
| Netherlands | 3         | 3.26%   |
| Australia   | 3         | 3.26%   |
| New Zealand | 2         | 2.17%   |
| Israel      | 2         | 2.17%   |
| Hungary     | 2         | 2.17%   |
| Finland     | 2         | 2.17%   |
| Argentina   | 2         | 2.17%   |
| Vietnam     | 1         | 1.09%   |
| Switzerland | 1         | 1.09%   |
| Spain       | 1         | 1.09%   |
| South Korea | 1         | 1.09%   |
| Singapore   | 1         | 1.09%   |
| Puerto Rico | 1         | 1.09%   |
| Portugal    | 1         | 1.09%   |
| Norway      | 1         | 1.09%   |
| Mexico      | 1         | 1.09%   |
| Italy       | 1         | 1.09%   |
| Indonesia   | 1         | 1.09%   |
| India       | 1         | 1.09%   |
| Greece      | 1         | 1.09%   |
| El Salvador | 1         | 1.09%   |
| Canada      | 1         | 1.09%   |
| Belgium     | 1         | 1.09%   |
| Belarus     | 1         | 1.09%   |
| Austria     | 1         | 1.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Saint George's       | 4         | 4.35%   |
| Bagnolet             | 4         | 4.35%   |
| Bratislava           | 3         | 3.26%   |
| Wroclaw              | 2         | 2.17%   |
| Volzhskiy            | 2         | 2.17%   |
| Tel Aviv             | 2         | 2.17%   |
| Sydney               | 2         | 2.17%   |
| Sao Paulo            | 2         | 2.17%   |
| Rio de Janeiro       | 2         | 2.17%   |
| Nadudvar             | 2         | 2.17%   |
| Kyiv                 | 2         | 2.17%   |
| Auckland             | 2         | 2.17%   |
| Yakutsk              | 1         | 1.09%   |
| Windisch             | 1         | 1.09%   |
| Vladikavkaz          | 1         | 1.09%   |
| Trubchëvsk          | 1         | 1.09%   |
| Toronto              | 1         | 1.09%   |
| Thessaloniki         | 1         | 1.09%   |
| Tangerang            | 1         | 1.09%   |
| Talavera de la Reina | 1         | 1.09%   |
| Staunton             | 1         | 1.09%   |
| St Petersburg        | 1         | 1.09%   |
| Singapore            | 1         | 1.09%   |
| Seongbuk-gu          | 1         | 1.09%   |
| San Salvador         | 1         | 1.09%   |
| Saint-Herblain       | 1         | 1.09%   |
| Reutlingen           | 1         | 1.09%   |
| Renkum               | 1         | 1.09%   |
| Praia Grande         | 1         | 1.09%   |
| Poperinge            | 1         | 1.09%   |
| Paris                | 1         | 1.09%   |
| Oslo                 | 1         | 1.09%   |
| Oleksandriya         | 1         | 1.09%   |
| Novopskov            | 1         | 1.09%   |
| Norman               | 1         | 1.09%   |
| Neuilly-Saint-Front  | 1         | 1.09%   |
| Nérac               | 1         | 1.09%   |
| Muenster-Sarmsheim   | 1         | 1.09%   |
| Moscow               | 1         | 1.09%   |
| Milan                | 1         | 1.09%   |
| Miedziana Gora       | 1         | 1.09%   |
| Miami                | 1         | 1.09%   |
| Maladzyechna         | 1         | 1.09%   |
| Loosdrecht           | 1         | 1.09%   |
| Leonding             | 1         | 1.09%   |
| Leipzig              | 1         | 1.09%   |
| Leeds                | 1         | 1.09%   |
| Kouvola              | 1         | 1.09%   |
| Kochi                | 1         | 1.09%   |
| Kirov                | 1         | 1.09%   |
| Katzenbach           | 1         | 1.09%   |
| Katowice             | 1         | 1.09%   |
| Karlsruhe            | 1         | 1.09%   |
| Jyväskylä          | 1         | 1.09%   |
| Hollywood            | 1         | 1.09%   |
| Hermosillo           | 1         | 1.09%   |
| Hayden               | 1         | 1.09%   |
| Hanoi                | 1         | 1.09%   |
| Great Bend           | 1         | 1.09%   |
| Fulham               | 1         | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 42     | 18.66%  |
| Seagate             | 17        | 25     | 12.69%  |
| Kingston            | 12        | 14     | 8.96%   |
| Samsung Electronics | 11        | 17     | 8.21%   |
| Unknown             | 6         | 8      | 4.48%   |
| Toshiba             | 6         | 6      | 4.48%   |
| Crucial             | 5         | 6      | 3.73%   |
| Hitachi             | 4         | 4      | 2.99%   |
| SK hynix            | 3         | 3      | 2.24%   |
| SanDisk             | 3         | 3      | 2.24%   |
| PNY                 | 3         | 3      | 2.24%   |
| Netac               | 3         | 3      | 2.24%   |
| HGST                | 3         | 3      | 2.24%   |
| Fujitsu             | 3         | 3      | 2.24%   |
| Micron Technology   | 2         | 2      | 1.49%   |
| Hewlett-Packard     | 2         | 3      | 1.49%   |
| Dogfish             | 2         | 2      | 1.49%   |
| A-DATA Technology   | 2         | 2      | 1.49%   |
| WD MediaMax         | 1         | 3      | 0.75%   |
| Union Memory        | 1         | 2      | 0.75%   |
| UMIS                | 1         | 1      | 0.75%   |
| Transcend           | 1         | 2      | 0.75%   |
| Teclast             | 1         | 1      | 0.75%   |
| Team                | 1         | 1      | 0.75%   |
| Smart               | 1         | 1      | 0.75%   |
| SABRENT             | 1         | 2      | 0.75%   |
| Patriot             | 1         | 1      | 0.75%   |
| Mushkin             | 1         | 1      | 0.75%   |
| Maxtor              | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 3      | 0.75%   |
| Lenovo              | 1         | 1      | 0.75%   |
| Kston               | 1         | 1      | 0.75%   |
| KIOXIA              | 1         | 1      | 0.75%   |
| KingFast            | 1         | 1      | 0.75%   |
| KingDian            | 1         | 1      | 0.75%   |
| Intel               | 1         | 1      | 0.75%   |
| IBM/Hitachi         | 1         | 1      | 0.75%   |
| HXY                 | 1         | 1      | 0.75%   |
| Goodram             | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                | 3         | 1.99%   |
| Kingston SA400S37120G 120GB SSD    | 3         | 1.99%   |
| Kingston SA2000M8250G 250GB        | 3         | 1.99%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 2         | 1.32%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 1.32%   |
| WDC WD10EARX-00N0YB0 1TB           | 2         | 1.32%   |
| Seagate ST2000DX002-2DV164 2TB     | 2         | 1.32%   |
| Samsung SSD 860 EVO 250GB          | 2         | 1.32%   |
| Kingston SA400S37480G 480GB SSD    | 2         | 1.32%   |
| Kingston SA400S37240G 240GB SSD    | 2         | 1.32%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.66%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.66%   |
| WDC WD800BB-00JHC0 80GB            | 1         | 0.66%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 0.66%   |
| WDC WD5001AALS-00L3B2 500GB        | 1         | 0.66%   |
| WDC WD5001AALS-00E3A0 500GB        | 1         | 0.66%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1         | 0.66%   |
| WDC WD5000AZLX-75K2TA0 500GB       | 1         | 0.66%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 0.66%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.66%   |
| WDC WD3200BEVT-22A23T0 320GB       | 1         | 0.66%   |
| WDC WD3200BEVE-00A0HT0 320GB       | 1         | 0.66%   |
| WDC WD2500BEKT-00A25T0 250GB       | 1         | 0.66%   |
| WDC WD20PURZ-85GU6Y0 2TB           | 1         | 0.66%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 0.66%   |
| WDC WD1200JS-55NCB1 120GB          | 1         | 0.66%   |
| WDC WD10SPZX-22Z10T1 1TB           | 1         | 0.66%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 0.66%   |
| WDC WD10EZRX-00D8PB0 1TB           | 1         | 0.66%   |
| WDC WD10EZEX-75M2NA0 1TB           | 1         | 0.66%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1         | 0.66%   |
| WDC WD10EZEX-22BN5A0 1TB           | 1         | 0.66%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 0.66%   |
| WDC WD10EZEX-00BBHA0 1TB           | 1         | 0.66%   |
| WDC WD10EURX-63FH1Y0 1TB           | 1         | 0.66%   |
| WD MediaMax WL500GSA3272 500GB     | 1         | 0.66%   |
| Unknown SD64G  64GB                | 1         | 0.66%   |
| Unknown SD04G  4GB                 | 1         | 0.66%   |
| Unknown SD  8GB                    | 1         | 0.66%   |
| Unknown S0J9F8  64GB               | 1         | 0.66%   |
| Unknown MMC32G  32GB               | 1         | 0.66%   |
| Unknown MMC Card  32GB             | 1         | 0.66%   |
| Unknown MMC Card  16GB             | 1         | 0.66%   |
| Unknown MMC Card  128GB            | 1         | 0.66%   |
| Union Memory RTOTJ128VGD2EYX 128GB | 1         | 0.66%   |
| UMIS RPFTJ256PDD2MWX 256GB         | 1         | 0.66%   |
| Transcend TS128GSSD370S 128GB      | 1         | 0.66%   |
| Toshiba MQ04ABF100 1TB             | 1         | 0.66%   |
| Toshiba MQ02ABF100 1TB             | 1         | 0.66%   |
| Toshiba MK1252GSX 120GB            | 1         | 0.66%   |
| Toshiba KXG60ZNV512G NVMe 512GB    | 1         | 0.66%   |
| Toshiba HDWD110 1TB                | 1         | 0.66%   |
| Toshiba DT01ACA100 1TB             | 1         | 0.66%   |
| Teclast 256GB NS550-2242 SSD       | 1         | 0.66%   |
| Team T253X1120G 120GB SSD          | 1         | 0.66%   |
| Smart SSD SZ9MSE mSATA 256GB       | 1         | 0.66%   |
| SK hynix SH920 mSATA 128GB SSD     | 1         | 0.66%   |
| SK hynix PC611 NVMe 1TB            | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 22        | 38     | 38.6%   |
| Seagate         | 17        | 25     | 29.82%  |
| Toshiba         | 5         | 5      | 8.77%   |
| Hitachi         | 4         | 4      | 7.02%   |
| HGST            | 3         | 3      | 5.26%   |
| Fujitsu         | 3         | 3      | 5.26%   |
| Maxtor          | 1         | 1      | 1.75%   |
| IBM/Hitachi     | 1         | 1      | 1.75%   |
| Hewlett-Packard | 1         | 2      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 17.65%  |
| Samsung Electronics | 6         | 7      | 11.76%  |
| WDC                 | 3         | 4      | 5.88%   |
| SanDisk             | 3         | 3      | 5.88%   |
| PNY                 | 3         | 3      | 5.88%   |
| Netac               | 3         | 3      | 5.88%   |
| Crucial             | 3         | 3      | 5.88%   |
| Micron Technology   | 2         | 2      | 3.92%   |
| Dogfish             | 2         | 2      | 3.92%   |
| A-DATA Technology   | 2         | 2      | 3.92%   |
| Union Memory        | 1         | 2      | 1.96%   |
| Transcend           | 1         | 2      | 1.96%   |
| Teclast             | 1         | 1      | 1.96%   |
| Team                | 1         | 1      | 1.96%   |
| Smart               | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Mushkin             | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| LITEON              | 1         | 3      | 1.96%   |
| Kston               | 1         | 1      | 1.96%   |
| KingDian            | 1         | 1      | 1.96%   |
| HXY                 | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| Goodram             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 49        | 82     | 40.16%  |
| SSD     | 47        | 58     | 38.52%  |
| NVMe    | 18        | 26     | 14.75%  |
| MMC     | 6         | 8      | 4.92%   |
| Unknown | 2         | 4      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 79        | 138    | 74.53%  |
| NVMe | 17        | 24     | 16.04%  |
| MMC  | 6         | 8      | 5.66%   |
| SAS  | 4         | 8      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 83     | 64.89%  |
| 0.51-1.0   | 21        | 40     | 22.34%  |
| 1.01-2.0   | 8         | 13     | 8.51%   |
| 3.01-4.0   | 3         | 3      | 3.19%   |
| 4.01-10.0  | 1         | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 21.65%  |
| 101-250        | 19        | 19.59%  |
| 1001-2000      | 14        | 14.43%  |
| 501-1000       | 10        | 10.31%  |
| 51-100         | 9         | 9.28%   |
| 21-50          | 8         | 8.25%   |
| Unknown        | 6         | 6.19%   |
| More than 3000 | 4         | 4.12%   |
| 2001-3000      | 3         | 3.09%   |
| 1-20           | 3         | 3.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 27.08%  |
| 101-250        | 24        | 25%     |
| 21-50          | 11        | 11.46%  |
| 51-100         | 9         | 9.38%   |
| 1001-2000      | 7         | 7.29%   |
| 501-1000       | 7         | 7.29%   |
| Unknown        | 6         | 6.25%   |
| 251-500        | 4         | 4.17%   |
| More than 3000 | 2         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 2         | 2      | 12.5%   |
| WDC WD5000LPVX-00V0TT0 500GB      | 1         | 1      | 6.25%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 6.25%   |
| WDC WD10EARX-00N0YB0 1TB          | 1         | 1      | 6.25%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 6.25%   |
| Toshiba MQ02ABF100 1TB            | 1         | 1      | 6.25%   |
| SK hynix SH920 mSATA 128GB SSD    | 1         | 1      | 6.25%   |
| Maxtor 6E040L0 41GB               | 1         | 1      | 6.25%   |
| Kingston SA400S37120G 120GB SSD   | 1         | 1      | 6.25%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 6.25%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 6.25%   |
| Hitachi HDS721616PLA380 160GB     | 1         | 1      | 6.25%   |
| HGST HTE721010A9E630 1TB          | 1         | 1      | 6.25%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 2      | 6.25%   |
| Fujitsu MHV2060BH PL 64GB         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 31.25%  |
| Hitachi         | 3         | 3      | 18.75%  |
| Toshiba         | 2         | 2      | 12.5%   |
| SK hynix        | 1         | 1      | 6.25%   |
| Maxtor          | 1         | 1      | 6.25%   |
| Kingston        | 1         | 1      | 6.25%   |
| HGST            | 1         | 1      | 6.25%   |
| Hewlett-Packard | 1         | 2      | 6.25%   |
| Fujitsu         | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 35.71%  |
| Hitachi         | 3         | 3      | 21.43%  |
| Toshiba         | 2         | 2      | 14.29%  |
| Maxtor          | 1         | 1      | 7.14%   |
| HGST            | 1         | 1      | 7.14%   |
| Hewlett-Packard | 1         | 2      | 7.14%   |
| Fujitsu         | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Works    | 70        | 120    | 65.42%  |
| Detected | 22        | 41     | 20.56%  |
| Malfunc  | 15        | 17     | 14.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 67        | 61.47%  |
| AMD                              | 16        | 14.68%  |
| Samsung Electronics              | 5         | 4.59%   |
| Kingston Technology Company      | 4         | 3.67%   |
| SK hynix                         | 2         | 1.83%   |
| Micron/Crucial Technology        | 2         | 1.83%   |
| Marvell Technology Group         | 2         | 1.83%   |
| VIA Technologies                 | 1         | 0.92%   |
| Union Memory (Shenzhen)          | 1         | 0.92%   |
| Toshiba America Info Systems     | 1         | 0.92%   |
| Silicon Integrated Systems [SiS] | 1         | 0.92%   |
| Nvidia                           | 1         | 0.92%   |
| Lenovo                           | 1         | 0.92%   |
| KIOXIA                           | 1         | 0.92%   |
| Integrated Technology Express    | 1         | 0.92%   |
| Broadcom / LSI                   | 1         | 0.92%   |
| ASMedia Technology               | 1         | 0.92%   |
| Adaptec                          | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 9.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 4%      |
| Kingston Company A2000 NVMe SSD                                                        | 4         | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 3.2%    |
| Intel SATA Controller [RAID mode]                                                      | 4         | 3.2%    |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 3.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 2.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 2.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 2.4%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.6%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.6%    |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 0.8%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.8%    |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.8%    |
| SK hynix BC511                                                                         | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.8%    |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.8%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.8%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                | 1         | 0.8%    |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.8%    |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.8%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                       | 1         | 0.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.8%    |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.8%    |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 0.8%    |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 0.8%    |
| Integrated Express IT8213 IDE Controller                                               | 1         | 0.8%    |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                     | 1         | 0.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 65        | 60.75%  |
| NVMe | 17        | 15.89%  |
| IDE  | 17        | 15.89%  |
| RAID | 7         | 6.54%   |
| SCSI | 1         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 81.52%  |
| AMD    | 16        | 17.39%  |
| ARM    | 1         | 1.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 3.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 3.23%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 2.15%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 2.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.15%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 2.15%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 1.08%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 1.08%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 1.08%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 1.08%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.08%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.08%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 1.08%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.08%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 1.08%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.08%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.08%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.08%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 1.08%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.08%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.08%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 1.08%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.08%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.08%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.08%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.08%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.08%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1         | 1.08%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 1.08%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1         | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.08%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.08%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.08%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.08%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.08%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.08%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.08%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.08%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.08%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.08%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.08%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.08%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.08%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.08%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24        | 25.81%  |
| Intel Core i7           | 11        | 11.83%  |
| Intel Core i3           | 9         | 9.68%   |
| Intel Celeron           | 5         | 5.38%   |
| Intel Core 2 Duo        | 4         | 4.3%    |
| AMD Ryzen 5             | 4         | 4.3%    |
| Intel Xeon              | 3         | 3.23%   |
| Intel Core 2            | 3         | 3.23%   |
| Other                   | 2         | 2.15%   |
| Intel Pentium M         | 2         | 2.15%   |
| Intel Pentium Dual-Core | 2         | 2.15%   |
| Intel Pentium Dual      | 2         | 2.15%   |
| Intel Pentium           | 2         | 2.15%   |
| Intel Core i9           | 2         | 2.15%   |
| Intel Atom              | 2         | 2.15%   |
| AMD Ryzen 3             | 2         | 2.15%   |
| Intel Pentium Silver    | 1         | 1.08%   |
| Intel Pentium Gold      | 1         | 1.08%   |
| Intel Pentium 4         | 1         | 1.08%   |
| Intel Core 2 Quad       | 1         | 1.08%   |
| Intel Celeron M         | 1         | 1.08%   |
| AMD Sempron             | 1         | 1.08%   |
| AMD Ryzen 7             | 1         | 1.08%   |
| AMD FX                  | 1         | 1.08%   |
| AMD E2                  | 1         | 1.08%   |
| AMD E                   | 1         | 1.08%   |
| AMD A8                  | 1         | 1.08%   |
| AMD A6                  | 1         | 1.08%   |
| AMD A4                  | 1         | 1.08%   |
| AMD A10                 | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 44.57%  |
| 4      | 30        | 32.61%  |
| 6      | 10        | 10.87%  |
| 1      | 8         | 8.7%    |
| 8      | 2         | 2.17%   |
| 10     | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 46        | 50%     |
| 1      | 46        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 92.39%  |
| 32-bit         | 4         | 4.35%   |
| Unknown        | 3         | 3.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 22.34%  |
| 0x306a9    | 6         | 6.38%   |
| 0x206a7    | 6         | 6.38%   |
| 0x906ea    | 5         | 5.32%   |
| 0x306c3    | 5         | 5.32%   |
| 0x1067a    | 5         | 5.32%   |
| 0x806ec    | 4         | 4.26%   |
| 0x306d4    | 3         | 3.19%   |
| 0x706a1    | 2         | 2.13%   |
| 0x6f6      | 2         | 2.13%   |
| 0x406e3    | 2         | 2.13%   |
| 0x40651    | 2         | 2.13%   |
| 0x20655    | 2         | 2.13%   |
| 0xf49      | 1         | 1.06%   |
| 0xa0655    | 1         | 1.06%   |
| 0xa0653    | 1         | 1.06%   |
| 0x906ed    | 1         | 1.06%   |
| 0x906e9    | 1         | 1.06%   |
| 0x806ea    | 1         | 1.06%   |
| 0x706a8    | 1         | 1.06%   |
| 0x6fd      | 1         | 1.06%   |
| 0x6d8      | 1         | 1.06%   |
| 0x695      | 1         | 1.06%   |
| 0x686      | 1         | 1.06%   |
| 0x506e3    | 1         | 1.06%   |
| 0x406d8    | 1         | 1.06%   |
| 0x406c4    | 1         | 1.06%   |
| 0x30678    | 1         | 1.06%   |
| 0x20652    | 1         | 1.06%   |
| 0x106e5    | 1         | 1.06%   |
| 0x10676    | 1         | 1.06%   |
| 0x08701021 | 1         | 1.06%   |
| 0x08701013 | 1         | 1.06%   |
| 0x08608103 | 1         | 1.06%   |
| 0x0800820d | 1         | 1.06%   |
| 0x08001138 | 1         | 1.06%   |
| 0x08001129 | 1         | 1.06%   |
| 0x07030105 | 1         | 1.06%   |
| 0x0600611a | 1         | 1.06%   |
| 0x05000119 | 1         | 1.06%   |
| 0x05000101 | 1         | 1.06%   |
| 0x03000027 | 1         | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 15.22%  |
| IvyBridge     | 8         | 8.7%    |
| Haswell       | 8         | 8.7%    |
| Penryn        | 7         | 7.61%   |
| SandyBridge   | 6         | 6.52%   |
| Westmere      | 4         | 4.35%   |
| Skylake       | 4         | 4.35%   |
| Silvermont    | 4         | 4.35%   |
| P6            | 4         | 4.35%   |
| Core          | 4         | 4.35%   |
| Broadwell     | 4         | 4.35%   |
| Goldmont plus | 3         | 3.26%   |
| Zen+          | 2         | 2.17%   |
| Zen 2         | 2         | 2.17%   |
| Zen           | 2         | 2.17%   |
| Piledriver    | 2         | 2.17%   |
| Nehalem       | 2         | 2.17%   |
| Excavator     | 2         | 2.17%   |
| CometLake     | 2         | 2.17%   |
| Bobcat        | 2         | 2.17%   |
| Unknown       | 2         | 2.17%   |
| Puma          | 1         | 1.09%   |
| NetBurst      | 1         | 1.09%   |
| K8 Hammer     | 1         | 1.09%   |
| K10 Llano     | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 55.56%  |
| AMD                              | 24        | 24.24%  |
| Nvidia                           | 19        | 19.19%  |
| Silicon Integrated Systems [SiS] | 1         | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.76%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.81%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.86%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.9%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.95%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.95%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.95%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.95%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.95%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.95%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 0.95%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.95%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.95%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 0.95%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 0.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.95%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.95%   |
| Intel HD Graphics 630                                                                    | 1         | 0.95%   |
| Intel HD Graphics 620                                                                    | 1         | 0.95%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.95%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.95%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.95%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.95%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.95%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.95%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.95%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.95%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                     | 1         | 0.95%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                    | 1         | 0.95%   |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1         | 0.95%   |
| AMD RV350 [Radeon 9550]                                                                  | 1         | 0.95%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                                      | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 47.83%  |
| 1 x AMD        | 19        | 20.65%  |
| 1 x Nvidia     | 13        | 14.13%  |
| Intel + Nvidia | 6         | 6.52%   |
| Other          | 3         | 3.26%   |
| 2 x AMD        | 3         | 3.26%   |
| Intel + AMD    | 2         | 2.17%   |
| 2 x Intel      | 1         | 1.09%   |
| 1 x SiS        | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 77        | 82.8%   |
| Proprietary | 10        | 10.75%  |
| Unknown     | 6         | 6.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 61.29%  |
| 0.01-0.5   | 13        | 13.98%  |
| 0.51-1.0   | 7         | 7.53%   |
| 3.01-4.0   | 5         | 5.38%   |
| 1.01-2.0   | 5         | 5.38%   |
| 2.01-3.0   | 3         | 3.23%   |
| 7.01-8.0   | 2         | 2.15%   |
| 5.01-6.0   | 1         | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 15.46%  |
| LG Display              | 13        | 13.4%   |
| AU Optronics            | 9         | 9.28%   |
| Hewlett-Packard         | 7         | 7.22%   |
| Goldstar                | 6         | 6.19%   |
| Chimei Innolux          | 5         | 5.15%   |
| Philips                 | 4         | 4.12%   |
| Lenovo                  | 4         | 4.12%   |
| AOC                     | 4         | 4.12%   |
| Dell                    | 3         | 3.09%   |
| BOE                     | 3         | 3.09%   |
| Acer                    | 3         | 3.09%   |
| PANDA                   | 2         | 2.06%   |
| Iiyama                  | 2         | 2.06%   |
| Chi Mei Optoelectronics | 2         | 2.06%   |
| ViewSonic               | 1         | 1.03%   |
| Unknown                 | 1         | 1.03%   |
| Toshiba                 | 1         | 1.03%   |
| STD                     | 1         | 1.03%   |
| Sony                    | 1         | 1.03%   |
| MStar                   | 1         | 1.03%   |
| MSI                     | 1         | 1.03%   |
| InnoLux Display         | 1         | 1.03%   |
| InfoVision              | 1         | 1.03%   |
| HJW                     | 1         | 1.03%   |
| Hisense                 | 1         | 1.03%   |
| eMachines               | 1         | 1.03%   |
| Eizo                    | 1         | 1.03%   |
| CVT                     | 1         | 1.03%   |
| Ancor Communications    | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.98%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.98%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.98%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.98%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.99%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 0.99%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.99%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                      | 1         | 0.99%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                          | 1         | 0.99%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch      | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1         | 0.99%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch      | 1         | 0.99%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.99%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.99%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.99%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.99%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.99%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.99%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 0.99%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 0.99%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 0.99%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 0.99%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 1         | 0.99%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                 | 1         | 0.99%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0540 1920x1080 340x190mm 15.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch            | 1         | 0.99%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1         | 0.99%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                | 1         | 0.99%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                | 1         | 0.99%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                | 1         | 0.99%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch       | 1         | 0.99%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 1         | 0.99%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1         | 0.99%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1         | 0.99%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 0.99%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                  | 1         | 0.99%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1         | 0.99%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 473x296mm 22.0-inch           | 1         | 0.99%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 1         | 0.99%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1         | 0.99%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch              | 1         | 0.99%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 40%     |
| 1366x768 (WXGA)    | 26        | 27.37%  |
| 3840x2160 (4K)     | 7         | 7.37%   |
| 1280x1024 (SXGA)   | 5         | 5.26%   |
| 1440x900 (WXGA+)   | 4         | 4.21%   |
| 1600x900 (HD+)     | 2         | 2.11%   |
| 1600x1200          | 2         | 2.11%   |
| 1280x800 (WXGA)    | 2         | 2.11%   |
| Unknown            | 2         | 2.11%   |
| 5760x1080          | 1         | 1.05%   |
| 3440x1440          | 1         | 1.05%   |
| 3000x2000          | 1         | 1.05%   |
| 2736x1824          | 1         | 1.05%   |
| 2288x1287          | 1         | 1.05%   |
| 1920x1200 (WUXGA)  | 1         | 1.05%   |
| 1680x1050 (WSXGA+) | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 22.11%  |
| 21      | 15        | 15.79%  |
| 14      | 7         | 7.37%   |
| 12      | 7         | 7.37%   |
| 24      | 6         | 6.32%   |
| 13      | 6         | 6.32%   |
| 27      | 5         | 5.26%   |
| 23      | 5         | 5.26%   |
| 17      | 4         | 4.21%   |
| 31      | 3         | 3.16%   |
| 19      | 3         | 3.16%   |
| 18      | 3         | 3.16%   |
| Unknown | 2         | 2.11%   |
| 142     | 1         | 1.05%   |
| 72      | 1         | 1.05%   |
| 54      | 1         | 1.05%   |
| 52      | 1         | 1.05%   |
| 40      | 1         | 1.05%   |
| 34      | 1         | 1.05%   |
| 22      | 1         | 1.05%   |
| 11      | 1         | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 30        | 32.97%  |
| 401-500        | 18        | 19.78%  |
| 501-600        | 15        | 16.48%  |
| 201-300        | 13        | 14.29%  |
| 351-400        | 4         | 4.4%    |
| 601-700        | 3         | 3.3%    |
| 1001-1500      | 2         | 2.2%    |
| Unknown        | 2         | 2.2%    |
| More than 2000 | 1         | 1.1%    |
| 801-900        | 1         | 1.1%    |
| 701-800        | 1         | 1.1%    |
| 1501-2000      | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 63        | 74.12%  |
| 16/10   | 8         | 9.41%   |
| 4/3     | 4         | 4.71%   |
| 5/4     | 3         | 3.53%   |
| 3/2     | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| 6/5     | 1         | 1.18%   |
| 21/9    | 1         | 1.18%   |
| 1.00    | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 19        | 20.43%  |
| 101-110        | 19        | 20.43%  |
| 151-200        | 9         | 9.68%   |
| 81-90          | 8         | 8.6%    |
| 61-70          | 7         | 7.53%   |
| 71-80          | 5         | 5.38%   |
| 301-350        | 5         | 5.38%   |
| More than 1000 | 4         | 4.3%    |
| 351-500        | 4         | 4.3%    |
| 141-150        | 4         | 4.3%    |
| 111-120        | 2         | 2.15%   |
| Unknown        | 2         | 2.15%   |
| 51-60          | 1         | 1.08%   |
| 251-300        | 1         | 1.08%   |
| 131-140        | 1         | 1.08%   |
| 121-130        | 1         | 1.08%   |
| 501-1000       | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 33        | 35.87%  |
| 51-100        | 30        | 32.61%  |
| 121-160       | 17        | 18.48%  |
| 1-50          | 4         | 4.35%   |
| 161-240       | 4         | 4.35%   |
| More than 240 | 2         | 2.17%   |
| Unknown       | 2         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 78.72%  |
| 2     | 12        | 12.77%  |
| 3     | 4         | 4.26%   |
| 0     | 4         | 4.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 33.58%  |
| Intel                            | 44        | 32.84%  |
| Qualcomm Atheros                 | 21        | 15.67%  |
| Ralink Technology                | 3         | 2.24%   |
| Marvell Technology Group         | 3         | 2.24%   |
| TP-Link                          | 2         | 1.49%   |
| Sierra Wireless                  | 2         | 1.49%   |
| NetGear                          | 2         | 1.49%   |
| JMicron Technology               | 2         | 1.49%   |
| Broadcom Limited                 | 2         | 1.49%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.75%   |
| VIA Technologies                 | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Samsung Electronics              | 1         | 0.75%   |
| Ralink                           | 1         | 0.75%   |
| Nvidia                           | 1         | 0.75%   |
| MediaTek                         | 1         | 0.75%   |
| Broadcom                         | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 31        | 20.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 5.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.95%   |
| Intel Wireless 7265                                                     | 3         | 1.95%   |
| Intel Wireless 7260                                                     | 3         | 1.95%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.95%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 1.95%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.95%   |
| Sierra Wireless EM7455                                                  | 2         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.3%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.3%    |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.3%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.3%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.3%    |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                          | 1         | 0.65%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.65%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.65%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.65%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.65%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.65%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.65%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.65%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.65%   |
| Intel Wireless 8260                                                     | 1         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.65%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.65%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.65%   |
| Intel Ethernet Controller I225-V                                        | 1         | 0.65%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                        | 1         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Qualcomm Atheros         | 19        | 31.67%  |
| Intel                    | 19        | 31.67%  |
| Realtek Semiconductor    | 8         | 13.33%  |
| Ralink Technology        | 3         | 5%      |
| Sierra Wireless          | 2         | 3.33%   |
| NetGear                  | 2         | 3.33%   |
| Broadcom Limited         | 2         | 3.33%   |
| TP-Link                  | 1         | 1.67%   |
| Ralink                   | 1         | 1.67%   |
| MediaTek                 | 1         | 1.67%   |
| Marvell Technology Group | 1         | 1.67%   |
| Broadcom                 | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5%      |
| Intel Wireless 7265                                                     | 3         | 5%      |
| Intel Wireless 7260                                                     | 3         | 5%      |
| Sierra Wireless EM7455                                                  | 2         | 3.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 3.33%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.33%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.67%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.67%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.67%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.67%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.67%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.67%   |
| Intel Wireless 8260                                                     | 1         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.67%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.67%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 40        | 44.44%  |
| Intel                            | 36        | 40%     |
| Qualcomm Atheros                 | 4         | 4.44%   |
| Marvell Technology Group         | 2         | 2.22%   |
| JMicron Technology               | 2         | 2.22%   |
| ZTE WCDMA Technologies MSM       | 1         | 1.11%   |
| VIA Technologies                 | 1         | 1.11%   |
| TP-Link                          | 1         | 1.11%   |
| Silicon Integrated Systems [SiS] | 1         | 1.11%   |
| Samsung Electronics              | 1         | 1.11%   |
| Nvidia                           | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 34.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.49%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 3.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.2%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.2%    |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 1.1%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.1%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.1%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.1%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.1%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.1%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 1         | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 1         | 1.1%    |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.1%    |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.1%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.1%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.1%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 58.04%  |
| WiFi     | 57        | 39.86%  |
| Modem    | 3         | 2.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 55.21%  |
| WiFi     | 43        | 44.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 52.69%  |
| 1     | 38        | 40.86%  |
| 0     | 4         | 4.3%    |
| 5     | 1         | 1.08%   |
| 3     | 1         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 83        | 90.22%  |
| Yes  | 9         | 9.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 31.43%  |
| Qualcomm Atheros Communications | 5         | 14.29%  |
| Realtek Semiconductor           | 4         | 11.43%  |
| Broadcom                        | 4         | 11.43%  |
| Lite-On Technology              | 2         | 5.71%   |
| IMC Networks                    | 2         | 5.71%   |
| Cambridge Silicon Radio         | 2         | 5.71%   |
| Ralink                          | 1         | 2.86%   |
| Marvell Semiconductor           | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Dell                            | 1         | 2.86%   |
| Apple                           | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20%     |
| Realtek Bluetooth Radio                             | 4         | 11.43%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 5.71%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.86%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Bluetooth Device                              | 1         | 2.86%   |
| IMC Networks Bluetooth Device                       | 1         | 2.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.86%   |
| Foxconn / Hon Hai BT                                | 1         | 2.86%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 56.56%  |
| AMD                              | 20        | 16.39%  |
| Nvidia                           | 15        | 12.3%   |
| Plantronics                      | 2         | 1.64%   |
| Creative Labs                    | 2         | 1.64%   |
| Texas Instruments                | 1         | 0.82%   |
| TEAC                             | 1         | 0.82%   |
| Silicon Integrated Systems [SiS] | 1         | 0.82%   |
| Realtek Semiconductor            | 1         | 0.82%   |
| M-Audio                          | 1         | 0.82%   |
| Logitech                         | 1         | 0.82%   |
| KORG                             | 1         | 0.82%   |
| GYROCOM C&C                      | 1         | 0.82%   |
| Elite Silicon                    | 1         | 0.82%   |
| DCMT Technology                  | 1         | 0.82%   |
| Cirrus Logic                     | 1         | 0.82%   |
| C-Media Electronics              | 1         | 0.82%   |
| Blue Microphones                 | 1         | 0.82%   |
| ASUSTek Computer                 | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 6.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 4.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.74%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.74%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 2.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 2.05%   |
| Plantronics HD1                                                            | 2         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.37%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.37%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.37%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.68%   |
| TEAC US-1800                                                               | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.68%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1         | 0.68%   |
| M-Audio M-Audio 1x1                                                        | 1         | 0.68%   |
| Logitech USB Headset                                                       | 1         | 0.68%   |
| KORG nanoKONTROL studio controller                                         | 1         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.68%   |
| Intel Audio device                                                         | 1         | 0.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.68%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.68%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 0.68%   |
| Elite Silicon USB Audio Device                                             | 1         | 0.68%   |
| DCMT Technology USB Condenser Microphone                                   | 1         | 0.68%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1         | 0.68%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.68%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 0.68%   |
| ASUSTek Computer XONAR SOUND CARD                                          | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 20.21%  |
| Unknown             | 18        | 19.15%  |
| Kingston            | 12        | 12.77%  |
| SK hynix            | 10        | 10.64%  |
| Micron Technology   | 6         | 6.38%   |
| Corsair             | 6         | 6.38%   |
| Crucial             | 5         | 5.32%   |
| A-DATA Technology   | 5         | 5.32%   |
| G.Skill             | 4         | 4.26%   |
| Nanya Technology    | 3         | 3.19%   |
| Unknown (ABCD)      | 2         | 2.13%   |
| Smart               | 1         | 1.06%   |
| Goodram             | 1         | 1.06%   |
| Avant               | 1         | 1.06%   |
| Apacer              | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 1.85%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 1.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.85%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 2         | 1.85%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.85%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s               | 2         | 1.85%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                         | 1         | 0.93%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                           | 1         | 0.93%   |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                        | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.93%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.93%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 1024MB DIMM DDR                                  | 1         | 0.93%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s               | 1         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.93%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.93%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.93%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                       | 1         | 0.93%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.93%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.93%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                | 1         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.93%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.93%   |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.93%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.93%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 1         | 0.93%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.93%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 36        | 44.44%  |
| DDR4    | 26        | 32.1%   |
| SDRAM   | 4         | 4.94%   |
| DDR     | 4         | 4.94%   |
| LPDDR3  | 3         | 3.7%    |
| DDR2    | 3         | 3.7%    |
| LPDDR4  | 2         | 2.47%   |
| Unknown | 2         | 2.47%   |
| DRAM    | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 52.5%   |
| DIMM         | 35        | 43.75%  |
| Row Of Chips | 3         | 3.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 32.63%  |
| 4096  | 26        | 27.37%  |
| 2048  | 17        | 17.89%  |
| 16384 | 10        | 10.53%  |
| 1024  | 5         | 5.26%   |
| 32768 | 2         | 2.11%   |
| 512   | 1         | 1.05%   |
| 256   | 1         | 1.05%   |
| 128   | 1         | 1.05%   |
| 64    | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 24.14%  |
| 2667    | 14        | 16.09%  |
| 2400    | 8         | 9.2%    |
| 1333    | 8         | 9.2%    |
| Unknown | 6         | 6.9%    |
| 2133    | 4         | 4.6%    |
| 1067    | 4         | 4.6%    |
| 3600    | 3         | 3.45%   |
| 4199    | 2         | 2.3%    |
| 3200    | 2         | 2.3%    |
| 1867    | 2         | 2.3%    |
| 1800    | 2         | 2.3%    |
| 800     | 2         | 2.3%    |
| 667     | 2         | 2.3%    |
| 3400    | 1         | 1.15%   |
| 2666    | 1         | 1.15%   |
| 1334    | 1         | 1.15%   |
| 1200    | 1         | 1.15%   |
| 1066    | 1         | 1.15%   |
| 400     | 1         | 1.15%   |
| 100     | 1         | 1.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 2         | 50%     |
| Custom Engineering SPA | 1         | 25%     |
| Brother Industries     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| HP ENVY 5000 series             | 1         | 25%     |
| HP Deskjet 1050 J410            | 1         | 25%     |
| Custom Engineering SPA KUBE USB | 1         | 25%     |
| Brother HL-L2375DW series       | 1         | 25%     |

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
| Chicony Electronics                    | 16        | 34.04%  |
| Microdia                               | 4         | 8.51%   |
| Acer                                   | 4         | 8.51%   |
| Sunplus Innovation Technology          | 3         | 6.38%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.38%   |
| Suyin                                  | 2         | 4.26%   |
| Logitech                               | 2         | 4.26%   |
| KYE Systems (Mouse Systems)            | 2         | 4.26%   |
| Z-Star Microelectronics                | 1         | 2.13%   |
| Softkinetic                            | 1         | 2.13%   |
| Samsung Electronics                    | 1         | 2.13%   |
| Realtek Semiconductor                  | 1         | 2.13%   |
| Mustek Systems                         | 1         | 2.13%   |
| Microsoft                              | 1         | 2.13%   |
| MacroSilicon                           | 1         | 2.13%   |
| Lite-On Technology                     | 1         | 2.13%   |
| IMC Networks                           | 1         | 2.13%   |
| GEMBIRD                                | 1         | 2.13%   |
| Cubeternet                             | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 14.89%  |
| Acer BisonCam, NB Pro                                           | 2         | 4.26%   |
| Z-Star A4 tech USB2.0 Camera                                    | 1         | 2.13%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 2.13%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 2.13%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.13%   |
| Sunplus FHD Camera Microphone                                   | 1         | 2.13%   |
| Sunplus Asus Webcam                                             | 1         | 2.13%   |
| Softkinetic DepthSense 325                                      | 1         | 2.13%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.13%   |
| Realtek USB CAMERA                                              | 1         | 2.13%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 2.13%   |
| Microsoft LifeCam Studio                                        | 1         | 2.13%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 2.13%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.13%   |
| Microdia Camera                                                 | 1         | 2.13%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 2.13%   |
| MacroSilicon MiraBox Capture                                    | 1         | 2.13%   |
| Logitech Webcam C270                                            | 1         | 2.13%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.13%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 2.13%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                      | 1         | 2.13%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                       | 1         | 2.13%   |
| IMC Networks Integrated Webcam                                  | 1         | 2.13%   |
| GEMBIRD USB2.0 PC CAMERA                                        | 1         | 2.13%   |
| Cubeternet GL-UPC822 UVC WebCam                                 | 1         | 2.13%   |
| Chicony WebCam                                                  | 1         | 2.13%   |
| Chicony VGA WebCam                                              | 1         | 2.13%   |
| Chicony Thinkpad T430 camera                                    | 1         | 2.13%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 2.13%   |
| Chicony Lenovo EasyCamera                                       | 1         | 2.13%   |
| Chicony HP TrueVision HD                                        | 1         | 2.13%   |
| Chicony HD WebCam                                               | 1         | 2.13%   |
| Chicony EasyCamera                                              | 1         | 2.13%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 2.13%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 2.13%   |
| Acer Integrated Camera                                          | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 25%     |
| Upek               | 1         | 25%     |
| Synaptics          | 1         | 25%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 75.53%  |
| 1     | 15        | 15.96%  |
| 2     | 6         | 6.38%   |
| 3     | 2         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 22.22%  |
| Chipcard                 | 5         | 18.52%  |
| Fingerprint reader       | 4         | 14.81%  |
| Communication controller | 3         | 11.11%  |
| Net/wireless             | 2         | 7.41%   |
| Multimedia controller    | 2         | 7.41%   |
| Camera                   | 2         | 7.41%   |
| Bluetooth                | 2         | 7.41%   |
| Firewire controller      | 1         | 3.7%    |


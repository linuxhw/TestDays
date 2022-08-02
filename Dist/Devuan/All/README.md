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

Total: 128

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | X99S MPOWER                 | Desktop     | [a3c1523b6b](https://linux-hardware.org/?probe=a3c1523b6b) | Jul 27, 2022 |
| Sony          | VPCEE23FX                   | Notebook    | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | Notebook    | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
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
| Devuan 4                | 42        | 39.25%  |
| Devuan 3                | 30        | 28.04%  |
| Devuan Testing/unstable | 15        | 14.02%  |
| Devuan 5                | 8         | 7.48%   |
| Devuan 2.1              | 7         | 6.54%   |
| Devuan                  | 2         | 1.87%   |
| Devuan 3.0              | 1         | 0.93%   |
| Devuan 2.0              | 1         | 0.93%   |
| Devuan 1.0.0            | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 100       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 10        | 9.09%   |
| 5.10.0-8-amd64            | 7         | 6.36%   |
| 4.19.0-9-amd64            | 6         | 5.45%   |
| 4.19.0-14-amd64           | 6         | 5.45%   |
| 4.19.0-16-amd64           | 5         | 4.55%   |
| 5.10.0-13-amd64           | 4         | 3.64%   |
| 5.10.0-11-amd64           | 4         | 3.64%   |
| 5.10.0-10-amd64           | 4         | 3.64%   |
| 5.7.0-2-amd64             | 3         | 2.73%   |
| 4.19.0-12-amd64           | 3         | 2.73%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 1.82%   |
| 5.18.0-2-amd64            | 2         | 1.82%   |
| 5.18.0-1-amd64            | 2         | 1.82%   |
| 5.15.0-2-amd64            | 2         | 1.82%   |
| 5.10.0-6-amd64            | 2         | 1.82%   |
| 5.10.0-16-amd64           | 2         | 1.82%   |
| 5.10.0-15-amd64           | 2         | 1.82%   |
| 5.10.0-14-amd64           | 2         | 1.82%   |
| 4.19.0-17-amd64           | 2         | 1.82%   |
| 4.19.0-13-amd64           | 2         | 1.82%   |
| 4.19.0-10-amd64           | 2         | 1.82%   |
| 5.9.0-4-amd64             | 1         | 0.91%   |
| 5.9.0-1-amd64             | 1         | 0.91%   |
| 5.8.0-3-amd64             | 1         | 0.91%   |
| 5.8.0-1-amd64             | 1         | 0.91%   |
| 5.7.19-server1            | 1         | 0.91%   |
| 5.7.0-1-amd64             | 1         | 0.91%   |
| 5.6.0-2-amd64             | 1         | 0.91%   |
| 5.18.14-devuan            | 1         | 0.91%   |
| 5.16.0-1-amd64            | 1         | 0.91%   |
| 5.15.5-xanmod1            | 1         | 0.91%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 0.91%   |
| 5.14.0-kali2-amd64        | 1         | 0.91%   |
| 5.14.0-4-amd64            | 1         | 0.91%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 0.91%   |
| 5.10.0-7-amd64            | 1         | 0.91%   |
| 5.10.0-5-amd64            | 1         | 0.91%   |
| 5.10.0-4-amd64            | 1         | 0.91%   |
| 5.10.0-2-amd64            | 1         | 0.91%   |
| 5.10.0-1-amd64            | 1         | 0.91%   |
| 5.1.21                    | 1         | 0.91%   |
| 5.0.7                     | 1         | 0.91%   |
| 4.9.0-15-amd64            | 1         | 0.91%   |
| 4.9.0-14-amd64            | 1         | 0.91%   |
| 4.9.0-14-686-pae          | 1         | 0.91%   |
| 4.9.0-14-686              | 1         | 0.91%   |
| 4.9.0-11-amd64            | 1         | 0.91%   |
| 4.9.0-11-686-pae          | 1         | 0.91%   |
| 4.9.0-11-686              | 1         | 0.91%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 0.91%   |
| 4.4.195-antix.1-amd64-smp | 1         | 0.91%   |
| 4.19.112                  | 1         | 0.91%   |
| 4.19.0-20-amd64           | 1         | 0.91%   |
| 4.19.0-17-686-pae         | 1         | 0.91%   |
| 4.19.0-1-amd64            | 1         | 0.91%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 0.91%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 41        | 38.32%  |
| 4.19.0   | 28        | 26.17%  |
| 4.9.0    | 8         | 7.48%   |
| 5.7.0    | 6         | 5.61%   |
| 5.18.0   | 4         | 3.74%   |
| 5.15.0   | 3         | 2.8%    |
| 5.9.0    | 2         | 1.87%   |
| 5.8.0    | 2         | 1.87%   |
| 5.14.0   | 2         | 1.87%   |
| 5.7.19   | 1         | 0.93%   |
| 5.6.0    | 1         | 0.93%   |
| 5.18.14  | 1         | 0.93%   |
| 5.16.0   | 1         | 0.93%   |
| 5.15.5   | 1         | 0.93%   |
| 5.11.0   | 1         | 0.93%   |
| 5.1.21   | 1         | 0.93%   |
| 5.0.7    | 1         | 0.93%   |
| 4.4.195  | 1         | 0.93%   |
| 4.19.112 | 1         | 0.93%   |
| 4.18.0   | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 41        | 38.32%  |
| 4.19    | 29        | 27.1%   |
| 4.9     | 8         | 7.48%   |
| 5.7     | 7         | 6.54%   |
| 5.18    | 5         | 4.67%   |
| 5.15    | 4         | 3.74%   |
| 5.9     | 2         | 1.87%   |
| 5.8     | 2         | 1.87%   |
| 5.14    | 2         | 1.87%   |
| 5.6     | 1         | 0.93%   |
| 5.16    | 1         | 0.93%   |
| 5.11    | 1         | 0.93%   |
| 5.1     | 1         | 0.93%   |
| 5.0     | 1         | 0.93%   |
| 4.4     | 1         | 0.93%   |
| 4.18    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 93        | 93%     |
| i686   | 6         | 6%      |
| armv7l | 1         | 1%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 41        | 38.68%  |
| Unknown    | 17        | 16.04%  |
| MATE       | 16        | 15.09%  |
| KDE5       | 14        | 13.21%  |
| i3         | 5         | 4.72%   |
| LXDE       | 4         | 3.77%   |
| LXQt       | 2         | 1.89%   |
| GNOME      | 2         | 1.89%   |
| Cinnamon   | 2         | 1.89%   |
| X-Cinnamon | 1         | 0.94%   |
| Openbox    | 1         | 0.94%   |
| awesome    | 1         | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 91        | 89.22%  |
| Tty     | 8         | 7.84%   |
| Unknown | 3         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 39        | 37.86%  |
| Unknown | 27        | 26.21%  |
| LightDM | 26        | 25.24%  |
| SDDM    | 6         | 5.83%   |
| XDM     | 2         | 1.94%   |
| GDM3    | 2         | 1.94%   |
| NODM    | 1         | 0.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 32        | 31.37%  |
| en_GB       | 19        | 18.63%  |
| ru_RU       | 8         | 7.84%   |
| Unknown     | 7         | 6.86%   |
| C           | 5         | 4.9%    |
| pt_BR       | 4         | 3.92%   |
| fr_FR       | 4         | 3.92%   |
| es_ES       | 4         | 3.92%   |
| sk_SK       | 3         | 2.94%   |
| en_AU       | 3         | 2.94%   |
| pl_PL       | 2         | 1.96%   |
| fr_BE       | 2         | 1.96%   |
| en_NZ       | 2         | 1.96%   |
| it_IT       | 1         | 0.98%   |
| es_SV       | 1         | 0.98%   |
| en_US.utf-8 | 1         | 0.98%   |
| en_SG       | 1         | 0.98%   |
| en_CA       | 1         | 0.98%   |
| de_DE       | 1         | 0.98%   |
| de_AT       | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 58        | 57.43%  |
| EFI  | 43        | 42.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 85%     |
| Btrfs   | 5         | 5%      |
| Unknown | 5         | 5%      |
| Overlay | 2         | 2%      |
| OveXlay | 1         | 1%      |
| Ext3    | 1         | 1%      |
| Ext2    | 1         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 54        | 51.43%  |
| MBR     | 41        | 39.05%  |
| Unknown | 10        | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 76.47%  |
| Yes       | 24        | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 74.26%  |
| Yes       | 26        | 25.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 18%     |
| Dell                | 13        | 13%     |
| ASUSTek Computer    | 12        | 12%     |
| Gigabyte Technology | 10        | 10%     |
| Hewlett-Packard     | 9         | 9%      |
| MSI                 | 6         | 6%      |
| Acer                | 5         | 5%      |
| ASRock              | 4         | 4%      |
| Toshiba             | 3         | 3%      |
| Intel               | 2         | 2%      |
| Fujitsu Siemens     | 2         | 2%      |
| Teclast             | 1         | 1%      |
| Sun Microsystems    | 1         | 1%      |
| Sony                | 1         | 1%      |
| Samsung Electronics | 1         | 1%      |
| Online Labs         | 1         | 1%      |
| Notebook            | 1         | 1%      |
| Nokia               | 1         | 1%      |
| MTC                 | 1         | 1%      |
| Microsoft           | 1         | 1%      |
| IP3 Tech            | 1         | 1%      |
| IBM                 | 1         | 1%      |
| Google              | 1         | 1%      |
| Fujitsu             | 1         | 1%      |
| Chuwi               | 1         | 1%      |
| Apple               | 1         | 1%      |
| AMI                 | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 1%      |
| Toshiba Satellite M40X                                                                   | 1         | 1%      |
| Toshiba Satellite L655                                                                   | 1         | 1%      |
| Teclast F6 Plus                                                                          | 1         | 1%      |
| Sun Microsystems Ultra 24                                                                | 1         | 1%      |
| Sony VPCEE23FX                                                                           | 1         | 1%      |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1%      |
| Online Labs SR                                                                           | 1         | 1%      |
| Notebook W230ST                                                                          | 1         | 1%      |
| Nokia N900                                                                               | 1         | 1%      |
| MTC Montara-GML                                                                          | 1         | 1%      |
| MSI MS-7B84                                                                              | 1         | 1%      |
| MSI MS-7B53                                                                              | 1         | 1%      |
| MSI MS-7A34                                                                              | 1         | 1%      |
| MSI MS-7885                                                                              | 1         | 1%      |
| MSI MS-1688                                                                              | 1         | 1%      |
| MSI Modern 15 A5M                                                                        | 1         | 1%      |
| Microsoft Surface Pro 4                                                                  | 1         | 1%      |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 1%      |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1%      |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 1%      |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1%      |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1%      |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1%      |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1%      |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1%      |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1%      |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 1%      |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1%      |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1%      |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1%      |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1%      |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1%      |
| Lenovo IdeaPad Z370                                                                      | 1         | 1%      |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1%      |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1%      |
| IP3 Tech HeroBox                                                                         | 1         | 1%      |
| Intel D815EEA AAA45884-401                                                               | 1         | 1%      |
| Intel AHV                                                                                | 1         | 1%      |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1%      |
| HP Z220 SFF Workstation                                                                  | 1         | 1%      |
| HP ProDesk 600 G1 SFF                                                                    | 1         | 1%      |
| HP ProBook 6475b                                                                         | 1         | 1%      |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 1%      |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1%      |
| HP Notebook                                                                              | 1         | 1%      |
| HP Laptop 17-cp0xxx                                                                      | 1         | 1%      |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 1%      |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 1%      |
| Google Panther                                                                           | 1         | 1%      |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 1%      |
| Gigabyte P55A-UD3                                                                        | 1         | 1%      |
| Gigabyte MZGLKBP-00                                                                      | 1         | 1%      |
| Gigabyte H310M S2H 2.0                                                                   | 1         | 1%      |
| Gigabyte H170-HD3-CF                                                                     | 1         | 1%      |
| Gigabyte H170-HD3                                                                        | 1         | 1%      |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 1%      |
| Gigabyte B75M-D3V                                                                        | 1         | 1%      |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 1%      |
| Gigabyte 970A-DS3P                                                                       | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 12%     |
| Dell Latitude           | 6         | 6%      |
| Dell OptiPlex           | 4         | 4%      |
| Acer Aspire             | 4         | 4%      |
| Toshiba Satellite       | 3         | 3%      |
| Lenovo IdeaPad          | 3         | 3%      |
| HP Pavilion             | 2         | 2%      |
| ASUS PRIME              | 2         | 2%      |
| Teclast F6              | 1         | 1%      |
| Sun Microsystems Ultra  | 1         | 1%      |
| Sony VPCEE23FX          | 1         | 1%      |
| Samsung 355V4C          | 1         | 1%      |
| Online Labs SR          | 1         | 1%      |
| Notebook W230ST         | 1         | 1%      |
| Nokia N900              | 1         | 1%      |
| MTC Montara-GML         | 1         | 1%      |
| MSI MS-7B84             | 1         | 1%      |
| MSI MS-7B53             | 1         | 1%      |
| MSI MS-7A34             | 1         | 1%      |
| MSI MS-7885             | 1         | 1%      |
| MSI MS-1688             | 1         | 1%      |
| MSI Modern              | 1         | 1%      |
| Microsoft Surface       | 1         | 1%      |
| Lenovo Yoga             | 1         | 1%      |
| Lenovo V310-14ISK       | 1         | 1%      |
| Lenovo ThinkStation     | 1         | 1%      |
| IP3 Tech HeroBox        | 1         | 1%      |
| Intel D815EEA           | 1         | 1%      |
| Intel AHV               | 1         | 1%      |
| IBM ThinkPad            | 1         | 1%      |
| HP Z220                 | 1         | 1%      |
| HP ProDesk              | 1         | 1%      |
| HP ProBook              | 1         | 1%      |
| HP Notebook             | 1         | 1%      |
| HP Laptop               | 1         | 1%      |
| HP EliteDesk            | 1         | 1%      |
| HP Compaq               | 1         | 1%      |
| Google Panther          | 1         | 1%      |
| Gigabyte Z390           | 1         | 1%      |
| Gigabyte P55A-UD3       | 1         | 1%      |
| Gigabyte MZGLKBP-00     | 1         | 1%      |
| Gigabyte H310M          | 1         | 1%      |
| Gigabyte H170-HD3-CF    | 1         | 1%      |
| Gigabyte H170-HD3       | 1         | 1%      |
| Gigabyte GA-G41M-ES2L   | 1         | 1%      |
| Gigabyte B75M-D3V       | 1         | 1%      |
| Gigabyte B450           | 1         | 1%      |
| Gigabyte 970A-DS3P      | 1         | 1%      |
| Fujitsu Siemens ESPRIMO | 1         | 1%      |
| Fujitsu Siemens AMILO   | 1         | 1%      |
| Fujitsu LIFEBOOK        | 1         | 1%      |
| Dell Vostro             | 1         | 1%      |
| Dell Precision          | 1         | 1%      |
| Dell Inspiron           | 1         | 1%      |
| Chuwi Hi10              | 1         | 1%      |
| ASUS X555LJ             | 1         | 1%      |
| ASUS ROG                | 1         | 1%      |
| ASUS P5PE-VM            | 1         | 1%      |
| ASUS P5G41T-M           | 1         | 1%      |
| ASUS Maximus            | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 13        | 13%     |
| 2012    | 11        | 11%     |
| 2019    | 10        | 10%     |
| 2017    | 7         | 7%      |
| 2014    | 7         | 7%      |
| 2011    | 7         | 7%      |
| 2013    | 6         | 6%      |
| 2010    | 6         | 6%      |
| 2016    | 5         | 5%      |
| 2009    | 5         | 5%      |
| 2021    | 4         | 4%      |
| 2015    | 4         | 4%      |
| 2008    | 4         | 4%      |
| 2006    | 3         | 3%      |
| 2020    | 2         | 2%      |
| 2007    | 2         | 2%      |
| 2005    | 2         | 2%      |
| 2000    | 1         | 1%      |
| Unknown | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 49        | 49%     |
| Desktop     | 43        | 43%     |
| Tablet      | 3         | 3%      |
| Mini pc     | 3         | 3%      |
| Convertible | 2         | 2%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 98        | 98%     |
| Enabled  | 2         | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 97%     |
| Yes  | 3         | 3%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 24%     |
| 4.01-8.0    | 20        | 20%     |
| 16.01-24.0  | 19        | 19%     |
| 3.01-4.0    | 16        | 16%     |
| 32.01-64.0  | 8         | 8%      |
| 1.01-2.0    | 6         | 6%      |
| 0.01-0.5    | 3         | 3%      |
| 2.01-3.0    | 2         | 2%      |
| 64.01-256.0 | 2         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 41        | 37.96%  |
| 4.01-8.0   | 21        | 19.44%  |
| 2.01-3.0   | 18        | 16.67%  |
| 0.51-1.0   | 13        | 12.04%  |
| 3.01-4.0   | 7         | 6.48%   |
| 0.01-0.5   | 4         | 3.7%    |
| 8.01-16.0  | 3         | 2.78%   |
| 32.01-64.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 61%     |
| 2      | 19        | 19%     |
| 3      | 10        | 10%     |
| 4      | 5         | 5%      |
| 5      | 4         | 4%      |
| 6      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 64.36%  |
| Yes       | 36        | 35.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 90%     |
| No        | 10        | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 62.38%  |
| No        | 38        | 37.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 63%     |
| Yes       | 37        | 37%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 9%      |
| Russia      | 9         | 9%      |
| Germany     | 8         | 8%      |
| France      | 8         | 8%      |
| Ukraine     | 7         | 7%      |
| Brazil      | 6         | 6%      |
| UK          | 4         | 4%      |
| Poland      | 4         | 4%      |
| Grenada     | 4         | 4%      |
| Spain       | 3         | 3%      |
| Slovakia    | 3         | 3%      |
| Netherlands | 3         | 3%      |
| Australia   | 3         | 3%      |
| New Zealand | 2         | 2%      |
| Israel      | 2         | 2%      |
| Indonesia   | 2         | 2%      |
| Hungary     | 2         | 2%      |
| Finland     | 2         | 2%      |
| Argentina   | 2         | 2%      |
| Vietnam     | 1         | 1%      |
| Switzerland | 1         | 1%      |
| South Korea | 1         | 1%      |
| Singapore   | 1         | 1%      |
| Serbia      | 1         | 1%      |
| Puerto Rico | 1         | 1%      |
| Portugal    | 1         | 1%      |
| Norway      | 1         | 1%      |
| Mexico      | 1         | 1%      |
| Italy       | 1         | 1%      |
| India       | 1         | 1%      |
| Greece      | 1         | 1%      |
| El Salvador | 1         | 1%      |
| Canada      | 1         | 1%      |
| Belgium     | 1         | 1%      |
| Belarus     | 1         | 1%      |
| Austria     | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Saint George's       | 4         | 4%      |
| Bagnolet             | 4         | 4%      |
| Bratislava           | 3         | 3%      |
| Wroclaw              | 2         | 2%      |
| Volzhskiy            | 2         | 2%      |
| Tel Aviv             | 2         | 2%      |
| Sydney               | 2         | 2%      |
| Sao Paulo            | 2         | 2%      |
| Rio de Janeiro       | 2         | 2%      |
| Nadudvar             | 2         | 2%      |
| Kyiv                 | 2         | 2%      |
| Auckland             | 2         | 2%      |
| Yakutsk              | 1         | 1%      |
| Windisch             | 1         | 1%      |
| Wildberg             | 1         | 1%      |
| Vladikavkaz          | 1         | 1%      |
| Trubchëvsk          | 1         | 1%      |
| Toronto              | 1         | 1%      |
| Thessaloniki         | 1         | 1%      |
| Tangerang            | 1         | 1%      |
| Talavera de la Reina | 1         | 1%      |
| Staunton             | 1         | 1%      |
| St Petersburg        | 1         | 1%      |
| Singapore            | 1         | 1%      |
| Seongbuk-gu          | 1         | 1%      |
| San Salvador         | 1         | 1%      |
| Saint-Herblain       | 1         | 1%      |
| Reutlingen           | 1         | 1%      |
| Renkum               | 1         | 1%      |
| Praia Grande         | 1         | 1%      |
| Poperinge            | 1         | 1%      |
| Paris                | 1         | 1%      |
| Oslo                 | 1         | 1%      |
| Oleksandriya         | 1         | 1%      |
| Okehampton           | 1         | 1%      |
| Novopskov            | 1         | 1%      |
| Norman               | 1         | 1%      |
| Neuilly-Saint-Front  | 1         | 1%      |
| Nérac               | 1         | 1%      |
| Muenster-Sarmsheim   | 1         | 1%      |
| Moscow               | 1         | 1%      |
| Milan                | 1         | 1%      |
| Miedziana Gora       | 1         | 1%      |
| Miami                | 1         | 1%      |
| Maladzyechna         | 1         | 1%      |
| Madrid               | 1         | 1%      |
| Loosdrecht           | 1         | 1%      |
| Leonding             | 1         | 1%      |
| Leipzig              | 1         | 1%      |
| Leeds                | 1         | 1%      |
| Kouvola              | 1         | 1%      |
| Kochi                | 1         | 1%      |
| Kirov                | 1         | 1%      |
| Kharkiv              | 1         | 1%      |
| Katzenbach           | 1         | 1%      |
| Katowice             | 1         | 1%      |
| Karlsruhe            | 1         | 1%      |
| Jyväskylä          | 1         | 1%      |
| Holt                 | 1         | 1%      |
| Hollywood            | 1         | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 47     | 19.59%  |
| Seagate             | 21        | 29     | 14.19%  |
| Samsung Electronics | 13        | 19     | 8.78%   |
| Kingston            | 13        | 15     | 8.78%   |
| Unknown             | 6         | 8      | 4.05%   |
| Toshiba             | 6         | 6      | 4.05%   |
| Crucial             | 6         | 8      | 4.05%   |
| SK hynix            | 4         | 4      | 2.7%    |
| SanDisk             | 4         | 4      | 2.7%    |
| Hitachi             | 4         | 4      | 2.7%    |
| PNY                 | 3         | 3      | 2.03%   |
| Netac               | 3         | 3      | 2.03%   |
| HGST                | 3         | 3      | 2.03%   |
| Fujitsu             | 3         | 3      | 2.03%   |
| Micron Technology   | 2         | 2      | 1.35%   |
| Hewlett-Packard     | 2         | 3      | 1.35%   |
| Dogfish             | 2         | 2      | 1.35%   |
| A-DATA Technology   | 2         | 2      | 1.35%   |
| WD MediaMax         | 1         | 3      | 0.68%   |
| Union Memory        | 1         | 2      | 0.68%   |
| UMIS                | 1         | 1      | 0.68%   |
| Transcend           | 1         | 2      | 0.68%   |
| Teclast             | 1         | 1      | 0.68%   |
| Team                | 1         | 1      | 0.68%   |
| Smart               | 1         | 1      | 0.68%   |
| SABRENT             | 1         | 2      | 0.68%   |
| Patriot             | 1         | 1      | 0.68%   |
| Mushkin             | 1         | 1      | 0.68%   |
| Maxtor              | 1         | 1      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| LITEON              | 1         | 3      | 0.68%   |
| Lenovo              | 1         | 1      | 0.68%   |
| Kston               | 1         | 1      | 0.68%   |
| KIOXIA              | 1         | 1      | 0.68%   |
| KingFast            | 1         | 1      | 0.68%   |
| KingDian            | 1         | 1      | 0.68%   |
| Intel               | 1         | 1      | 0.68%   |
| IBM/Hitachi         | 1         | 1      | 0.68%   |
| HXY                 | 1         | 1      | 0.68%   |
| GOODRAM             | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                  | 3         | 1.81%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.81%   |
| Kingston SA2000M8250G 250GB          | 3         | 1.81%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.2%    |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 1.2%    |
| Seagate ST3500418AS 500GB            | 2         | 1.2%    |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 1.2%    |
| Samsung SSD 860 EVO 250GB            | 2         | 1.2%    |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.2%    |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.2%    |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.6%    |
| WDC WD800BB-00JHC0 80GB              | 1         | 0.6%    |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.6%    |
| WDC WD5001AALS-00L3B2 500GB          | 1         | 0.6%    |
| WDC WD5001AALS-00E3A0 500GB          | 1         | 0.6%    |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.6%    |
| WDC WD5000AZLX-75K2TA0 500GB         | 1         | 0.6%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.6%    |
| WDC WD40EDAZ-11SLVB0 4TB             | 1         | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.6%    |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.6%    |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.6%    |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.6%    |
| WDC WD20PURZ-85GU6Y0 2TB             | 1         | 0.6%    |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 0.6%    |
| WDC WD1200JS-55NCB1 120GB            | 1         | 0.6%    |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.6%    |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.6%    |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.6%    |
| WDC WD10JFCX-68N6GN0 1TB             | 1         | 0.6%    |
| WDC WD10EZRX-00D8PB0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-75M2NA0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-22BN5A0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-00BBHA0 1TB             | 1         | 0.6%    |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 0.6%    |
| WDC PC SN540 SDDPNPF-512G-1032 512GB | 1         | 0.6%    |
| WD MediaMax WL500GSA3272 500GB       | 1         | 0.6%    |
| Unknown SD64G  64GB                  | 1         | 0.6%    |
| Unknown SD04G  4GB                   | 1         | 0.6%    |
| Unknown SD  8GB                      | 1         | 0.6%    |
| Unknown S0J9F8  64GB                 | 1         | 0.6%    |
| Unknown MMC32G  32GB                 | 1         | 0.6%    |
| Unknown MMC Card  32GB               | 1         | 0.6%    |
| Unknown MMC Card  16GB               | 1         | 0.6%    |
| Unknown MMC Card  128GB              | 1         | 0.6%    |
| Union Memory RTOTJ128VGD2EYX 128GB   | 1         | 0.6%    |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 0.6%    |
| Transcend TS128GSSD370S 128GB        | 1         | 0.6%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.6%    |
| Toshiba MQ02ABF100 1TB               | 1         | 0.6%    |
| Toshiba MK1252GSX 120GB              | 1         | 0.6%    |
| Toshiba KXG60ZNV512G NVMe 512GB      | 1         | 0.6%    |
| Toshiba HDWD110 1TB                  | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 25        | 41     | 38.46%  |
| Seagate         | 21        | 29     | 32.31%  |
| Toshiba         | 5         | 5      | 7.69%   |
| Hitachi         | 4         | 4      | 6.15%   |
| HGST            | 3         | 3      | 4.62%   |
| Fujitsu         | 3         | 3      | 4.62%   |
| SABRENT         | 1         | 2      | 1.54%   |
| Maxtor          | 1         | 1      | 1.54%   |
| IBM/Hitachi     | 1         | 1      | 1.54%   |
| Hewlett-Packard | 1         | 2      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 11     | 17.54%  |
| Samsung Electronics | 8         | 9      | 14.04%  |
| SanDisk             | 4         | 4      | 7.02%   |
| Crucial             | 4         | 5      | 7.02%   |
| WDC                 | 3         | 4      | 5.26%   |
| PNY                 | 3         | 3      | 5.26%   |
| Netac               | 3         | 3      | 5.26%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| Dogfish             | 2         | 2      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| Union Memory        | 1         | 2      | 1.75%   |
| Transcend           | 1         | 2      | 1.75%   |
| Teclast             | 1         | 1      | 1.75%   |
| Team                | 1         | 1      | 1.75%   |
| Smart               | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| Mushkin             | 1         | 1      | 1.75%   |
| LITEONIT            | 1         | 1      | 1.75%   |
| LITEON              | 1         | 3      | 1.75%   |
| Kston               | 1         | 1      | 1.75%   |
| KingDian            | 1         | 1      | 1.75%   |
| HXY                 | 1         | 1      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 55        | 91     | 41.35%  |
| SSD     | 51        | 65     | 38.35%  |
| NVMe    | 19        | 26     | 14.29%  |
| MMC     | 6         | 8      | 4.51%   |
| Unknown | 2         | 4      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 151    | 74.14%  |
| NVMe | 19        | 26     | 16.38%  |
| MMC  | 6         | 8      | 5.17%   |
| SAS  | 5         | 9      | 4.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 93     | 63.81%  |
| 0.51-1.0   | 24        | 44     | 22.86%  |
| 1.01-2.0   | 8         | 13     | 7.62%   |
| 3.01-4.0   | 5         | 5      | 4.76%   |
| 4.01-10.0  | 1         | 1      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 20.95%  |
| 101-250        | 21        | 20%     |
| 1001-2000      | 14        | 13.33%  |
| 501-1000       | 13        | 12.38%  |
| 51-100         | 10        | 9.52%   |
| 21-50          | 8         | 7.62%   |
| Unknown        | 6         | 5.71%   |
| More than 3000 | 5         | 4.76%   |
| 2001-3000      | 3         | 2.86%   |
| 1-20           | 3         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 27        | 25.96%  |
| 101-250        | 25        | 24.04%  |
| 21-50          | 13        | 12.5%   |
| 51-100         | 10        | 9.62%   |
| 1001-2000      | 7         | 6.73%   |
| 501-1000       | 7         | 6.73%   |
| 251-500        | 6         | 5.77%   |
| Unknown        | 6         | 5.77%   |
| More than 3000 | 2         | 1.92%   |
| 2001-3000      | 1         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 2         | 2      | 11.11%  |
| WDC WD5000LPVX-00V0TT0 500GB      | 1         | 1      | 5.56%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 5.56%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 5.56%   |
| WDC WD10EARX-00N0YB0 1TB          | 1         | 1      | 5.56%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 5.56%   |
| Toshiba MQ02ABF100 1TB            | 1         | 1      | 5.56%   |
| SK hynix SH920 mSATA 128GB SSD    | 1         | 1      | 5.56%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 5.56%   |
| Maxtor 6E040L0 41GB               | 1         | 1      | 5.56%   |
| Kingston SA400S37120G 120GB SSD   | 1         | 1      | 5.56%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 5.56%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 5.56%   |
| Hitachi HDS721616PLA380 160GB     | 1         | 1      | 5.56%   |
| HGST HTE721010A9E630 1TB          | 1         | 1      | 5.56%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 2      | 5.56%   |
| Fujitsu MHV2060BH PL 64GB         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 33.33%  |
| Hitachi         | 3         | 3      | 16.67%  |
| Toshiba         | 2         | 2      | 11.11%  |
| SK hynix        | 1         | 1      | 5.56%   |
| Seagate         | 1         | 1      | 5.56%   |
| Maxtor          | 1         | 1      | 5.56%   |
| Kingston        | 1         | 1      | 5.56%   |
| HGST            | 1         | 1      | 5.56%   |
| Hewlett-Packard | 1         | 2      | 5.56%   |
| Fujitsu         | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 37.5%   |
| Hitachi         | 3         | 3      | 18.75%  |
| Toshiba         | 2         | 2      | 12.5%   |
| Seagate         | 1         | 1      | 6.25%   |
| Maxtor          | 1         | 1      | 6.25%   |
| HGST            | 1         | 1      | 6.25%   |
| Hewlett-Packard | 1         | 2      | 6.25%   |
| Fujitsu         | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 88.89%  |
| SSD  | 2         | 2      | 11.11%  |

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
| Works    | 77        | 133    | 65.81%  |
| Detected | 23        | 42     | 19.66%  |
| Malfunc  | 17        | 19     | 14.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 61.86%  |
| AMD                              | 17        | 14.41%  |
| Samsung Electronics              | 5         | 4.24%   |
| Kingston Technology Company      | 4         | 3.39%   |
| SK hynix                         | 2         | 1.69%   |
| SanDisk                          | 2         | 1.69%   |
| Micron/Crucial Technology        | 2         | 1.69%   |
| Marvell Technology Group         | 2         | 1.69%   |
| VIA Technologies                 | 1         | 0.85%   |
| Union Memory (Shenzhen)          | 1         | 0.85%   |
| Toshiba America Info Systems     | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |
| Nvidia                           | 1         | 0.85%   |
| Lenovo                           | 1         | 0.85%   |
| KIOXIA                           | 1         | 0.85%   |
| Integrated Technology Express    | 1         | 0.85%   |
| Broadcom / LSI                   | 1         | 0.85%   |
| ASMedia Technology               | 1         | 0.85%   |
| Adaptec                          | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 8.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 3.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 3.68%   |
| Kingston Company A2000 NVMe SSD                                                        | 4         | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 2.94%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 4         | 2.94%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 2.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.21%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.47%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 1.47%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 0.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.74%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.74%   |
| SK hynix BC511                                                                         | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.74%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.74%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.74%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.74%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                | 1         | 0.74%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.74%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 0.74%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.74%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                             | 1         | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                       | 1         | 0.74%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                       | 1         | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.74%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.74%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 0.74%   |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 71        | 60.68%  |
| NVMe | 19        | 16.24%  |
| IDE  | 18        | 15.38%  |
| RAID | 8         | 6.84%   |
| SCSI | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 81%     |
| AMD    | 18        | 18%     |
| ARM    | 1         | 1%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.97%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.98%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.98%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.98%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.99%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.99%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.99%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.99%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.99%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.99%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.99%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.99%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.99%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.99%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.99%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.99%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.99%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.99%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.99%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.99%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.99%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.99%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.99%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.99%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1         | 0.99%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 0.99%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1         | 0.99%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 0.99%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 0.99%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 0.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 0.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 0.99%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.99%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 0.99%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 0.99%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 24.75%  |
| Intel Core i7           | 15        | 14.85%  |
| Intel Core i3           | 10        | 9.9%    |
| Intel Celeron           | 5         | 4.95%   |
| Intel Core 2 Duo        | 4         | 3.96%   |
| AMD Ryzen 5             | 4         | 3.96%   |
| Intel Xeon              | 3         | 2.97%   |
| Intel Core 2            | 3         | 2.97%   |
| Other                   | 2         | 1.98%   |
| Intel Pentium M         | 2         | 1.98%   |
| Intel Pentium Dual-Core | 2         | 1.98%   |
| Intel Pentium Dual      | 2         | 1.98%   |
| Intel Pentium           | 2         | 1.98%   |
| Intel Core i9           | 2         | 1.98%   |
| Intel Atom              | 2         | 1.98%   |
| AMD Ryzen 7             | 2         | 1.98%   |
| AMD Ryzen 3             | 2         | 1.98%   |
| Intel Pentium Silver    | 1         | 0.99%   |
| Intel Pentium Gold      | 1         | 0.99%   |
| Intel Pentium 4         | 1         | 0.99%   |
| Intel Core 2 Quad       | 1         | 0.99%   |
| Intel Celeron M         | 1         | 0.99%   |
| AMD Sempron             | 1         | 0.99%   |
| AMD FX                  | 1         | 0.99%   |
| AMD E2                  | 1         | 0.99%   |
| AMD E                   | 1         | 0.99%   |
| AMD Athlon II           | 1         | 0.99%   |
| AMD A8                  | 1         | 0.99%   |
| AMD A6                  | 1         | 0.99%   |
| AMD A4                  | 1         | 0.99%   |
| AMD A10                 | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 46        | 46%     |
| 4      | 31        | 31%     |
| 6      | 11        | 11%     |
| 1      | 8         | 8%      |
| 8      | 3         | 3%      |
| 10     | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 100       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 53        | 53%     |
| 1      | 47        | 47%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 93%     |
| 32-bit         | 4         | 4%      |
| Unknown        | 3         | 3%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 20.59%  |
| 0x306a9    | 6         | 5.88%   |
| 0x206a7    | 6         | 5.88%   |
| 0x906ea    | 5         | 4.9%    |
| 0x406e3    | 5         | 4.9%    |
| 0x306c3    | 5         | 4.9%    |
| 0x1067a    | 5         | 4.9%    |
| 0x806ec    | 4         | 3.92%   |
| 0x40651    | 3         | 2.94%   |
| 0x306d4    | 3         | 2.94%   |
| 0x706a1    | 2         | 1.96%   |
| 0x6f6      | 2         | 1.96%   |
| 0x20655    | 2         | 1.96%   |
| 0x106e5    | 2         | 1.96%   |
| 0x08608103 | 2         | 1.96%   |
| 0xf49      | 1         | 0.98%   |
| 0xa0655    | 1         | 0.98%   |
| 0xa0653    | 1         | 0.98%   |
| 0x906ed    | 1         | 0.98%   |
| 0x906e9    | 1         | 0.98%   |
| 0x806ea    | 1         | 0.98%   |
| 0x706a8    | 1         | 0.98%   |
| 0x6fd      | 1         | 0.98%   |
| 0x6d8      | 1         | 0.98%   |
| 0x695      | 1         | 0.98%   |
| 0x686      | 1         | 0.98%   |
| 0x506e3    | 1         | 0.98%   |
| 0x406d8    | 1         | 0.98%   |
| 0x406c4    | 1         | 0.98%   |
| 0x306f2    | 1         | 0.98%   |
| 0x30678    | 1         | 0.98%   |
| 0x20652    | 1         | 0.98%   |
| 0x10676    | 1         | 0.98%   |
| 0x08701021 | 1         | 0.98%   |
| 0x08701013 | 1         | 0.98%   |
| 0x0800820d | 1         | 0.98%   |
| 0x08001138 | 1         | 0.98%   |
| 0x08001129 | 1         | 0.98%   |
| 0x07030105 | 1         | 0.98%   |
| 0x0600611a | 1         | 0.98%   |
| 0x05000119 | 1         | 0.98%   |
| 0x05000101 | 1         | 0.98%   |
| 0x03000027 | 1         | 0.98%   |
| 0x010000b6 | 1         | 0.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 14%     |
| Haswell       | 10        | 10%     |
| IvyBridge     | 8         | 8%      |
| Skylake       | 7         | 7%      |
| Penryn        | 7         | 7%      |
| SandyBridge   | 6         | 6%      |
| Westmere      | 4         | 4%      |
| Silvermont    | 4         | 4%      |
| P6            | 4         | 4%      |
| Core          | 4         | 4%      |
| Broadwell     | 4         | 4%      |
| Nehalem       | 3         | 3%      |
| Goldmont plus | 3         | 3%      |
| Unknown       | 3         | 3%      |
| Zen+          | 2         | 2%      |
| Zen 2         | 2         | 2%      |
| Zen           | 2         | 2%      |
| Piledriver    | 2         | 2%      |
| Excavator     | 2         | 2%      |
| CometLake     | 2         | 2%      |
| Bobcat        | 2         | 2%      |
| Puma          | 1         | 1%      |
| NetBurst      | 1         | 1%      |
| K8 Hammer     | 1         | 1%      |
| K10 Llano     | 1         | 1%      |
| K10           | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 59        | 54.63%  |
| AMD                              | 26        | 24.07%  |
| Nvidia                           | 22        | 20.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.51%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.51%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.63%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.75%   |
| AMD Lucienne                                                                             | 2         | 1.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.75%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.88%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.88%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.88%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.88%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.88%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.88%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.88%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 0.88%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.88%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 0.88%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.88%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.88%   |
| Intel HD Graphics 630                                                                    | 1         | 0.88%   |
| Intel HD Graphics 620                                                                    | 1         | 0.88%   |
| Intel HD Graphics 520                                                                    | 1         | 0.88%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.88%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.88%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.88%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 0.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 47%     |
| 1 x AMD        | 21        | 21%     |
| 1 x Nvidia     | 15        | 15%     |
| Intel + Nvidia | 7         | 7%      |
| Other          | 3         | 3%      |
| 2 x AMD        | 3         | 3%      |
| Intel + AMD    | 2         | 2%      |
| 2 x Intel      | 1         | 1%      |
| 1 x SiS        | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 83        | 82.18%  |
| Proprietary | 12        | 11.88%  |
| Unknown     | 6         | 5.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 59.41%  |
| 0.01-0.5   | 16        | 15.84%  |
| 0.51-1.0   | 7         | 6.93%   |
| 1.01-2.0   | 6         | 5.94%   |
| 3.01-4.0   | 5         | 4.95%   |
| 7.01-8.0   | 3         | 2.97%   |
| 2.01-3.0   | 3         | 2.97%   |
| 5.01-6.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 15.09%  |
| Samsung Electronics     | 15        | 14.15%  |
| AU Optronics            | 11        | 10.38%  |
| Hewlett-Packard         | 7         | 6.6%    |
| Goldstar                | 6         | 5.66%   |
| Chimei Innolux          | 5         | 4.72%   |
| Philips                 | 4         | 3.77%   |
| Lenovo                  | 4         | 3.77%   |
| BOE                     | 4         | 3.77%   |
| AOC                     | 4         | 3.77%   |
| Dell                    | 3         | 2.83%   |
| Acer                    | 3         | 2.83%   |
| Unknown                 | 2         | 1.89%   |
| PANDA                   | 2         | 1.89%   |
| Iiyama                  | 2         | 1.89%   |
| Chi Mei Optoelectronics | 2         | 1.89%   |
| ___                     | 1         | 0.94%   |
| ViewSonic               | 1         | 0.94%   |
| Toshiba                 | 1         | 0.94%   |
| STD                     | 1         | 0.94%   |
| Sony                    | 1         | 0.94%   |
| MStar                   | 1         | 0.94%   |
| MSI                     | 1         | 0.94%   |
| InnoLux Display         | 1         | 0.94%   |
| InfoVision              | 1         | 0.94%   |
| HJW                     | 1         | 0.94%   |
| Hisense                 | 1         | 0.94%   |
| eMachines               | 1         | 0.94%   |
| Eizo                    | 1         | 0.94%   |
| CVT                     | 1         | 0.94%   |
| CHI                     | 1         | 0.94%   |
| Ancor Communications    | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.82%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.82%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.82%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.91%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.91%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.91%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 0.91%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.91%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                      | 1         | 0.91%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                          | 1         | 0.91%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.91%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.91%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1         | 0.91%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch      | 1         | 0.91%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.91%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.91%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.91%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.91%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.91%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.91%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 0.91%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 0.91%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 0.91%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 0.91%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.91%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                | 1         | 0.91%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0540 1920x1080 340x190mm 15.3-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch            | 1         | 0.91%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1         | 0.91%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1         | 0.91%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                | 1         | 0.91%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                | 1         | 0.91%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch       | 1         | 0.91%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 1         | 0.91%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1         | 0.91%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1         | 0.91%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 0.91%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                  | 1         | 0.91%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1         | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 39.42%  |
| 1366x768 (WXGA)    | 29        | 27.88%  |
| 3840x2160 (4K)     | 7         | 6.73%   |
| 1440x900 (WXGA+)   | 5         | 4.81%   |
| 1280x1024 (SXGA)   | 5         | 4.81%   |
| 1600x900 (HD+)     | 2         | 1.92%   |
| 1600x1200          | 2         | 1.92%   |
| 1280x800 (WXGA)    | 2         | 1.92%   |
| Unknown            | 2         | 1.92%   |
| 5760x1080          | 1         | 0.96%   |
| 3440x1440          | 1         | 0.96%   |
| 3000x2000          | 1         | 0.96%   |
| 2736x1824          | 1         | 0.96%   |
| 2288x1287          | 1         | 0.96%   |
| 1920x1200 (WUXGA)  | 1         | 0.96%   |
| 1680x1050 (WSXGA+) | 1         | 0.96%   |
| 1360x768           | 1         | 0.96%   |
| 1024x768 (XGA)     | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 23.08%  |
| 21      | 15        | 14.42%  |
| 12      | 9         | 8.65%   |
| 14      | 7         | 6.73%   |
| 13      | 7         | 6.73%   |
| 24      | 6         | 5.77%   |
| 27      | 5         | 4.81%   |
| 23      | 5         | 4.81%   |
| 17      | 4         | 3.85%   |
| Unknown | 4         | 3.85%   |
| 31      | 3         | 2.88%   |
| 19      | 3         | 2.88%   |
| 18      | 3         | 2.88%   |
| 72      | 2         | 1.92%   |
| 142     | 1         | 0.96%   |
| 54      | 1         | 0.96%   |
| 52      | 1         | 0.96%   |
| 40      | 1         | 0.96%   |
| 34      | 1         | 0.96%   |
| 22      | 1         | 0.96%   |
| 11      | 1         | 0.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 34        | 34%     |
| 401-500        | 18        | 18%     |
| 501-600        | 15        | 15%     |
| 201-300        | 15        | 15%     |
| 351-400        | 4         | 4%      |
| Unknown        | 4         | 4%      |
| 601-700        | 3         | 3%      |
| 1501-2000      | 2         | 2%      |
| 1001-1500      | 2         | 2%      |
| More than 2000 | 1         | 1%      |
| 801-900        | 1         | 1%      |
| 701-800        | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 70        | 75.27%  |
| 16/10   | 8         | 8.6%    |
| 4/3     | 4         | 4.3%    |
| 5/4     | 3         | 3.23%   |
| Unknown | 3         | 3.23%   |
| 3/2     | 2         | 2.15%   |
| 6/5     | 1         | 1.08%   |
| 21/9    | 1         | 1.08%   |
| 1.00    | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 21.57%  |
| 201-250        | 19        | 18.63%  |
| 81-90          | 9         | 8.82%   |
| 61-70          | 9         | 8.82%   |
| 151-200        | 9         | 8.82%   |
| More than 1000 | 5         | 4.9%    |
| 71-80          | 5         | 4.9%    |
| 301-350        | 5         | 4.9%    |
| 351-500        | 4         | 3.92%   |
| 141-150        | 4         | 3.92%   |
| Unknown        | 4         | 3.92%   |
| 111-120        | 2         | 1.96%   |
| 51-60          | 1         | 0.98%   |
| 251-300        | 1         | 0.98%   |
| 131-140        | 1         | 0.98%   |
| 121-130        | 1         | 0.98%   |
| 501-1000       | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 34.65%  |
| 51-100        | 30        | 29.7%   |
| 121-160       | 20        | 19.8%   |
| 1-50          | 5         | 4.95%   |
| 161-240       | 5         | 4.95%   |
| Unknown       | 4         | 3.96%   |
| More than 240 | 2         | 1.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 80        | 78.43%  |
| 2     | 14        | 13.73%  |
| 3     | 4         | 3.92%   |
| 0     | 4         | 3.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 48        | 33.33%  |
| Realtek Semiconductor            | 47        | 32.64%  |
| Qualcomm Atheros                 | 23        | 15.97%  |
| Ralink Technology                | 3         | 2.08%   |
| Marvell Technology Group         | 3         | 2.08%   |
| TP-Link                          | 2         | 1.39%   |
| Sierra Wireless                  | 2         | 1.39%   |
| NetGear                          | 2         | 1.39%   |
| MediaTek                         | 2         | 1.39%   |
| JMicron Technology               | 2         | 1.39%   |
| Broadcom Limited                 | 2         | 1.39%   |
| Broadcom                         | 2         | 1.39%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.69%   |
| VIA Technologies                 | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Samsung Electronics              | 1         | 0.69%   |
| Ralink                           | 1         | 0.69%   |
| Nvidia                           | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 33        | 19.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 5.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.4%    |
| Intel Wireless 7260                                                     | 4         | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.8%    |
| Intel Wireless 7265                                                     | 3         | 1.8%    |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.8%    |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.8%    |
| Sierra Wireless EM7455                                                  | 2         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.2%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.2%    |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.2%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.2%    |
| Intel Wireless 8265 / 8275                                              | 2         | 1.2%    |
| Intel Wireless 8260                                                     | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.2%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.2%    |
| ZTE WCDMA MSM ZTE MSM                                                   | 1         | 0.6%    |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.6%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.6%    |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.6%    |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.6%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.6%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.6%    |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.6%    |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.6%    |
| Intel Ethernet Controller I225-V                                        | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 33.33%  |
| Qualcomm Atheros         | 21        | 31.82%  |
| Realtek Semiconductor    | 8         | 12.12%  |
| Ralink Technology        | 3         | 4.55%   |
| Sierra Wireless          | 2         | 3.03%   |
| NetGear                  | 2         | 3.03%   |
| MediaTek                 | 2         | 3.03%   |
| Broadcom Limited         | 2         | 3.03%   |
| TP-Link                  | 1         | 1.52%   |
| Ralink                   | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| Broadcom                 | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 6.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 6.06%   |
| Intel Wireless 7260                                                     | 4         | 6.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.55%   |
| Intel Wireless 7265                                                     | 3         | 4.55%   |
| Sierra Wireless EM7455                                                  | 2         | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 3.03%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.03%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.03%   |
| Intel Wireless 8260                                                     | 2         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 3.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.52%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.52%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.52%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.52%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.52%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.52%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.52%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 42        | 43.3%   |
| Intel                            | 40        | 41.24%  |
| Qualcomm Atheros                 | 4         | 4.12%   |
| Marvell Technology Group         | 2         | 2.06%   |
| JMicron Technology               | 2         | 2.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 1.03%   |
| VIA Technologies                 | 1         | 1.03%   |
| TP-Link                          | 1         | 1.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.03%   |
| Samsung Electronics              | 1         | 1.03%   |
| Nvidia                           | 1         | 1.03%   |
| Broadcom                         | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 33.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.1%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 3.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.04%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 1.02%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.02%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.02%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.02%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.02%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.02%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.02%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.02%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 90        | 57.69%  |
| WiFi     | 63        | 40.38%  |
| Modem    | 3         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56        | 54.37%  |
| WiFi     | 47        | 45.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 53.47%  |
| 1     | 41        | 40.59%  |
| 0     | 4         | 3.96%   |
| 5     | 1         | 0.99%   |
| 3     | 1         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 90%     |
| Yes  | 10        | 10%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 34.21%  |
| Qualcomm Atheros Communications | 6         | 15.79%  |
| Realtek Semiconductor           | 4         | 10.53%  |
| Broadcom                        | 4         | 10.53%  |
| Lite-On Technology              | 2         | 5.26%   |
| IMC Networks                    | 2         | 5.26%   |
| Cambridge Silicon Radio         | 2         | 5.26%   |
| Ralink                          | 1         | 2.63%   |
| Marvell Semiconductor           | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Dell                            | 1         | 2.63%   |
| Apple                           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 23.68%  |
| Realtek Bluetooth Radio                             | 4         | 10.53%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 10.53%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.26%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 5.26%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.63%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.63%   |
| Intel AX201 Bluetooth                               | 1         | 2.63%   |
| IMC Networks Bluetooth Device                       | 1         | 2.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.63%   |
| Foxconn / Hon Hai BT                                | 1         | 2.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 75        | 56.82%  |
| AMD                              | 22        | 16.67%  |
| Nvidia                           | 17        | 12.88%  |
| Plantronics                      | 2         | 1.52%   |
| Creative Labs                    | 2         | 1.52%   |
| Texas Instruments                | 1         | 0.76%   |
| TEAC                             | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |
| Realtek Semiconductor            | 1         | 0.76%   |
| M-Audio                          | 1         | 0.76%   |
| Logitech                         | 1         | 0.76%   |
| KORG                             | 1         | 0.76%   |
| GYROCOM C&C                      | 1         | 0.76%   |
| Elite Silicon                    | 1         | 0.76%   |
| DCMT Technology                  | 1         | 0.76%   |
| Cirrus Logic                     | 1         | 0.76%   |
| C-Media Electronics              | 1         | 0.76%   |
| Blue Microphones                 | 1         | 0.76%   |
| ASUSTek Computer                 | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 4.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.52%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.52%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.89%   |
| Plantronics HD1                                                            | 2         | 1.26%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.26%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.26%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.26%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.63%   |
| TEAC US-1800                                                               | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.63%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.63%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1         | 0.63%   |
| M-Audio M-Audio 1x1                                                        | 1         | 0.63%   |
| Logitech USB Headset                                                       | 1         | 0.63%   |
| KORG nanoKONTROL studio controller                                         | 1         | 0.63%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.63%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 0.63%   |
| Intel Audio device                                                         | 1         | 0.63%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.63%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 0.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.63%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 0.63%   |
| Elite Silicon USB Audio Device                                             | 1         | 0.63%   |
| DCMT Technology USB Condenser Microphone                                   | 1         | 0.63%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1         | 0.63%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 21.78%  |
| Unknown             | 19        | 18.81%  |
| SK hynix            | 12        | 11.88%  |
| Kingston            | 12        | 11.88%  |
| Micron Technology   | 6         | 5.94%   |
| Corsair             | 6         | 5.94%   |
| G.Skill             | 5         | 4.95%   |
| Crucial             | 5         | 4.95%   |
| A-DATA Technology   | 5         | 4.95%   |
| Nanya Technology    | 3         | 2.97%   |
| Unknown (ABCD)      | 2         | 1.98%   |
| Smart               | 1         | 0.99%   |
| Goodram             | 1         | 0.99%   |
| Avant               | 1         | 0.99%   |
| Apacer              | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 2.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.71%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.71%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.71%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s            | 2         | 1.71%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.85%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.85%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.85%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 0.85%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.85%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.85%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 0.85%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s                  | 1         | 0.85%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.85%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s                  | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.85%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.85%   |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.85%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 44.94%  |
| DDR4    | 29        | 32.58%  |
| SDRAM   | 4         | 4.49%   |
| DDR     | 4         | 4.49%   |
| LPDDR3  | 3         | 3.37%   |
| DDR2    | 3         | 3.37%   |
| Unknown | 3         | 3.37%   |
| LPDDR4  | 2         | 2.25%   |
| DRAM    | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 54.02%  |
| DIMM         | 37        | 42.53%  |
| Row Of Chips | 3         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 34.31%  |
| 4096  | 28        | 27.45%  |
| 2048  | 17        | 16.67%  |
| 16384 | 11        | 10.78%  |
| 1024  | 5         | 4.9%    |
| 32768 | 2         | 1.96%   |
| 512   | 1         | 0.98%   |
| 256   | 1         | 0.98%   |
| 128   | 1         | 0.98%   |
| 64    | 1         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 24        | 25.26%  |
| 2667    | 15        | 15.79%  |
| 2400    | 9         | 9.47%   |
| 1333    | 8         | 8.42%   |
| Unknown | 7         | 7.37%   |
| 3200    | 4         | 4.21%   |
| 2133    | 4         | 4.21%   |
| 1067    | 4         | 4.21%   |
| 3600    | 3         | 3.16%   |
| 4199    | 2         | 2.11%   |
| 1867    | 2         | 2.11%   |
| 1800    | 2         | 2.11%   |
| 800     | 2         | 2.11%   |
| 667     | 2         | 2.11%   |
| 3400    | 1         | 1.05%   |
| 2666    | 1         | 1.05%   |
| 1334    | 1         | 1.05%   |
| 1200    | 1         | 1.05%   |
| 1066    | 1         | 1.05%   |
| 400     | 1         | 1.05%   |
| 100     | 1         | 1.05%   |

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
| Chicony Electronics                    | 19        | 35.19%  |
| Sunplus Innovation Technology          | 4         | 7.41%   |
| Microdia                               | 4         | 7.41%   |
| Acer                                   | 4         | 7.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Suyin                                  | 2         | 3.7%    |
| Realtek Semiconductor                  | 2         | 3.7%    |
| Logitech                               | 2         | 3.7%    |
| KYE Systems (Mouse Systems)            | 2         | 3.7%    |
| Cubeternet                             | 2         | 3.7%    |
| Z-Star Microelectronics                | 1         | 1.85%   |
| Softkinetic                            | 1         | 1.85%   |
| Samsung Electronics                    | 1         | 1.85%   |
| Quanta                                 | 1         | 1.85%   |
| Mustek Systems                         | 1         | 1.85%   |
| Microsoft                              | 1         | 1.85%   |
| MacroSilicon                           | 1         | 1.85%   |
| Lite-On Technology                     | 1         | 1.85%   |
| IMC Networks                           | 1         | 1.85%   |
| GEMBIRD                                | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 12.96%  |
| Sunplus Integrated_Webcam_HD                                    | 2         | 3.7%    |
| Cubeternet GL-UPC822 UVC WebCam                                 | 2         | 3.7%    |
| Chicony HD Webcam                                               | 2         | 3.7%    |
| Chicony EasyCamera                                              | 2         | 3.7%    |
| Acer BisonCam, NB Pro                                           | 2         | 3.7%    |
| Z-Star Vimicro USB Camera (Altair)                              | 1         | 1.85%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 1.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 1.85%   |
| Sunplus Laptop Integrated Webcam HD                             | 1         | 1.85%   |
| Sunplus ASUS USB2.0 Webcam                                      | 1         | 1.85%   |
| Softkinetic DepthSense 325                                      | 1         | 1.85%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 1.85%   |
| Realtek USB CAMERA                                              | 1         | 1.85%   |
| Realtek Integrated Webcam_HD                                    | 1         | 1.85%   |
| Quanta Sony Visual Communication Camera                         | 1         | 1.85%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 1.85%   |
| Microsoft LifeCam Studio                                        | 1         | 1.85%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 1.85%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.85%   |
| Microdia Camera                                                 | 1         | 1.85%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 1.85%   |
| MacroSilicon USB3.0 HD VIDEO                                    | 1         | 1.85%   |
| Logitech Webcam C270                                            | 1         | 1.85%   |
| Logitech HD Pro Webcam C920                                     | 1         | 1.85%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 1.85%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                       | 1         | 1.85%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera                | 1         | 1.85%   |
| IMC Networks Integrated Webcam                                  | 1         | 1.85%   |
| GEMBIRD USB2.0 PC CAMERA                                        | 1         | 1.85%   |
| Chicony WebCam                                                  | 1         | 1.85%   |
| Chicony VGA WebCam                                              | 1         | 1.85%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 1.85%   |
| Chicony Thinkpad T430 camera                                    | 1         | 1.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 1.85%   |
| Chicony Lenovo EasyCamera                                       | 1         | 1.85%   |
| Chicony HP TrueVision HD                                        | 1         | 1.85%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 1.85%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 1.85%   |
| Acer Integrated Camera                                          | 1         | 1.85%   |

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
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 2         | 22.22%  |
| Lenovo      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 58200                                                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 77        | 75.49%  |
| 1     | 17        | 16.67%  |
| 2     | 6         | 5.88%   |
| 3     | 2         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 20.69%  |
| Chipcard                 | 6         | 20.69%  |
| Fingerprint reader       | 4         | 13.79%  |
| Communication controller | 3         | 10.34%  |
| Net/wireless             | 2         | 6.9%    |
| Multimedia controller    | 2         | 6.9%    |
| Camera                   | 2         | 6.9%    |
| Bluetooth                | 2         | 6.9%    |
| Unassigned class         | 1         | 3.45%   |
| Firewire controller      | 1         | 3.45%   |


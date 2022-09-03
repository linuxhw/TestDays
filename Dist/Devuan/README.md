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

Total: 132

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 43        | 39.81%  |
| Devuan 3                | 30        | 27.78%  |
| Devuan Testing/unstable | 15        | 13.89%  |
| Devuan 5                | 8         | 7.41%   |
| Devuan 2.1              | 7         | 6.48%   |
| Devuan                  | 2         | 1.85%   |
| Devuan 3.0              | 1         | 0.93%   |
| Devuan 2.0              | 1         | 0.93%   |
| Devuan 1.0.0            | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 101       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 10        | 8.85%   |
| 5.10.0-8-amd64            | 7         | 6.19%   |
| 4.19.0-9-amd64            | 6         | 5.31%   |
| 4.19.0-14-amd64           | 6         | 5.31%   |
| 5.10.0-16-amd64           | 5         | 4.42%   |
| 4.19.0-16-amd64           | 5         | 4.42%   |
| 5.10.0-13-amd64           | 4         | 3.54%   |
| 5.10.0-11-amd64           | 4         | 3.54%   |
| 5.10.0-10-amd64           | 4         | 3.54%   |
| 5.7.0-2-amd64             | 3         | 2.65%   |
| 4.19.0-12-amd64           | 3         | 2.65%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 1.77%   |
| 5.18.0-2-amd64            | 2         | 1.77%   |
| 5.18.0-1-amd64            | 2         | 1.77%   |
| 5.15.0-2-amd64            | 2         | 1.77%   |
| 5.10.0-6-amd64            | 2         | 1.77%   |
| 5.10.0-15-amd64           | 2         | 1.77%   |
| 5.10.0-14-amd64           | 2         | 1.77%   |
| 4.19.0-17-amd64           | 2         | 1.77%   |
| 4.19.0-13-amd64           | 2         | 1.77%   |
| 4.19.0-10-amd64           | 2         | 1.77%   |
| 5.9.0-4-amd64             | 1         | 0.88%   |
| 5.9.0-1-amd64             | 1         | 0.88%   |
| 5.8.0-3-amd64             | 1         | 0.88%   |
| 5.8.0-1-amd64             | 1         | 0.88%   |
| 5.7.19-server1            | 1         | 0.88%   |
| 5.7.0-1-amd64             | 1         | 0.88%   |
| 5.6.0-2-amd64             | 1         | 0.88%   |
| 5.18.14-devuan            | 1         | 0.88%   |
| 5.16.0-1-amd64            | 1         | 0.88%   |
| 5.15.5-xanmod1            | 1         | 0.88%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 0.88%   |
| 5.14.0-kali2-amd64        | 1         | 0.88%   |
| 5.14.0-4-amd64            | 1         | 0.88%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 0.88%   |
| 5.10.0-7-amd64            | 1         | 0.88%   |
| 5.10.0-5-amd64            | 1         | 0.88%   |
| 5.10.0-4-amd64            | 1         | 0.88%   |
| 5.10.0-2-amd64            | 1         | 0.88%   |
| 5.10.0-1-amd64            | 1         | 0.88%   |
| 5.1.21                    | 1         | 0.88%   |
| 5.0.7                     | 1         | 0.88%   |
| 4.9.0-15-amd64            | 1         | 0.88%   |
| 4.9.0-14-amd64            | 1         | 0.88%   |
| 4.9.0-14-686-pae          | 1         | 0.88%   |
| 4.9.0-14-686              | 1         | 0.88%   |
| 4.9.0-11-amd64            | 1         | 0.88%   |
| 4.9.0-11-686-pae          | 1         | 0.88%   |
| 4.9.0-11-686              | 1         | 0.88%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 0.88%   |
| 4.4.195-antix.1-amd64-smp | 1         | 0.88%   |
| 4.19.112                  | 1         | 0.88%   |
| 4.19.0-20-amd64           | 1         | 0.88%   |
| 4.19.0-17-686-pae         | 1         | 0.88%   |
| 4.19.0-1-amd64            | 1         | 0.88%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 0.88%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 42        | 38.89%  |
| 4.19.0   | 28        | 25.93%  |
| 4.9.0    | 8         | 7.41%   |
| 5.7.0    | 6         | 5.56%   |
| 5.18.0   | 4         | 3.7%    |
| 5.15.0   | 3         | 2.78%   |
| 5.9.0    | 2         | 1.85%   |
| 5.8.0    | 2         | 1.85%   |
| 5.14.0   | 2         | 1.85%   |
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

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 42        | 38.89%  |
| 4.19    | 29        | 26.85%  |
| 4.9     | 8         | 7.41%   |
| 5.7     | 7         | 6.48%   |
| 5.18    | 5         | 4.63%   |
| 5.15    | 4         | 3.7%    |
| 5.9     | 2         | 1.85%   |
| 5.8     | 2         | 1.85%   |
| 5.14    | 2         | 1.85%   |
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

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 93.07%  |
| i686   | 6         | 5.94%   |
| armv7l | 1         | 0.99%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 42        | 39.25%  |
| Unknown    | 17        | 15.89%  |
| MATE       | 16        | 14.95%  |
| KDE5       | 14        | 13.08%  |
| i3         | 5         | 4.67%   |
| LXDE       | 4         | 3.74%   |
| LXQt       | 2         | 1.87%   |
| GNOME      | 2         | 1.87%   |
| Cinnamon   | 2         | 1.87%   |
| X-Cinnamon | 1         | 0.93%   |
| Openbox    | 1         | 0.93%   |
| awesome    | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 92        | 89.32%  |
| Tty     | 8         | 7.77%   |
| Unknown | 3         | 2.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 39        | 37.5%   |
| Unknown | 28        | 26.92%  |
| LightDM | 26        | 25%     |
| SDDM    | 6         | 5.77%   |
| XDM     | 2         | 1.92%   |
| GDM3    | 2         | 1.92%   |
| NODM    | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 32        | 31.07%  |
| en_GB       | 19        | 18.45%  |
| ru_RU       | 8         | 7.77%   |
| Unknown     | 7         | 6.8%    |
| pt_BR       | 5         | 4.85%   |
| C           | 5         | 4.85%   |
| fr_FR       | 4         | 3.88%   |
| es_ES       | 4         | 3.88%   |
| sk_SK       | 3         | 2.91%   |
| en_AU       | 3         | 2.91%   |
| pl_PL       | 2         | 1.94%   |
| fr_BE       | 2         | 1.94%   |
| en_NZ       | 2         | 1.94%   |
| it_IT       | 1         | 0.97%   |
| es_SV       | 1         | 0.97%   |
| en_US.utf-8 | 1         | 0.97%   |
| en_SG       | 1         | 0.97%   |
| en_CA       | 1         | 0.97%   |
| de_DE       | 1         | 0.97%   |
| de_AT       | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 59        | 57.84%  |
| EFI  | 43        | 42.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 86        | 85.15%  |
| Btrfs   | 5         | 4.95%   |
| Unknown | 5         | 4.95%   |
| Overlay | 2         | 1.98%   |
| OveXlay | 1         | 0.99%   |
| Ext3    | 1         | 0.99%   |
| Ext2    | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 54        | 50.94%  |
| MBR     | 41        | 38.68%  |
| Unknown | 11        | 10.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 76.7%   |
| Yes       | 24        | 23.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 74.51%  |
| Yes       | 26        | 25.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 17.82%  |
| Dell                | 13        | 12.87%  |
| ASUSTek Computer    | 12        | 11.88%  |
| Gigabyte Technology | 10        | 9.9%    |
| Hewlett-Packard     | 9         | 8.91%   |
| MSI                 | 6         | 5.94%   |
| Acer                | 5         | 4.95%   |
| ASRock              | 4         | 3.96%   |
| Toshiba             | 3         | 2.97%   |
| Intel               | 2         | 1.98%   |
| Fujitsu Siemens     | 2         | 1.98%   |
| Teclast             | 1         | 0.99%   |
| Sun Microsystems    | 1         | 0.99%   |
| Sony                | 1         | 0.99%   |
| Samsung Electronics | 1         | 0.99%   |
| Online Labs         | 1         | 0.99%   |
| Notebook            | 1         | 0.99%   |
| Nokia               | 1         | 0.99%   |
| MTC                 | 1         | 0.99%   |
| Microsoft           | 1         | 0.99%   |
| IP3 Tech            | 1         | 0.99%   |
| IBM                 | 1         | 0.99%   |
| Google              | 1         | 0.99%   |
| Fujitsu             | 1         | 0.99%   |
| Chuwi               | 1         | 0.99%   |
| CCE                 | 1         | 0.99%   |
| Apple               | 1         | 0.99%   |
| AMI                 | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.99%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.99%   |
| Toshiba Satellite L655                                                                   | 1         | 0.99%   |
| Teclast F6 Plus                                                                          | 1         | 0.99%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.99%   |
| Sony VPCEE23FX                                                                           | 1         | 0.99%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.99%   |
| Online Labs SR                                                                           | 1         | 0.99%   |
| Notebook W230ST                                                                          | 1         | 0.99%   |
| Nokia N900                                                                               | 1         | 0.99%   |
| MTC Montara-GML                                                                          | 1         | 0.99%   |
| MSI MS-7B84                                                                              | 1         | 0.99%   |
| MSI MS-7B53                                                                              | 1         | 0.99%   |
| MSI MS-7A34                                                                              | 1         | 0.99%   |
| MSI MS-7885                                                                              | 1         | 0.99%   |
| MSI MS-1688                                                                              | 1         | 0.99%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.99%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.99%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.99%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.99%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.99%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.99%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.99%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.99%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.99%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.99%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.99%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 0.99%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 0.99%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 0.99%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 0.99%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 0.99%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 0.99%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 0.99%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 0.99%   |
| IP3 Tech HeroBox                                                                         | 1         | 0.99%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 0.99%   |
| Intel AHV                                                                                | 1         | 0.99%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 0.99%   |
| HP Z220 SFF Workstation                                                                  | 1         | 0.99%   |
| HP ProDesk 600 G1 SFF                                                                    | 1         | 0.99%   |
| HP ProBook 6475b                                                                         | 1         | 0.99%   |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 0.99%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 0.99%   |
| HP Notebook                                                                              | 1         | 0.99%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 0.99%   |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 0.99%   |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 0.99%   |
| Google Panther                                                                           | 1         | 0.99%   |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 0.99%   |
| Gigabyte P55A-UD3                                                                        | 1         | 0.99%   |
| Gigabyte MZGLKBP-00                                                                      | 1         | 0.99%   |
| Gigabyte H310M S2H 2.0                                                                   | 1         | 0.99%   |
| Gigabyte H170-HD3-CF                                                                     | 1         | 0.99%   |
| Gigabyte H170-HD3                                                                        | 1         | 0.99%   |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 0.99%   |
| Gigabyte B75M-D3V                                                                        | 1         | 0.99%   |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 0.99%   |
| Gigabyte 970A-DS3P                                                                       | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 11.88%  |
| Dell Latitude           | 6         | 5.94%   |
| Dell OptiPlex           | 4         | 3.96%   |
| Acer Aspire             | 4         | 3.96%   |
| Toshiba Satellite       | 3         | 2.97%   |
| Lenovo IdeaPad          | 3         | 2.97%   |
| HP Pavilion             | 2         | 1.98%   |
| ASUS PRIME              | 2         | 1.98%   |
| Teclast F6              | 1         | 0.99%   |
| Sun Microsystems Ultra  | 1         | 0.99%   |
| Sony VPCEE23FX          | 1         | 0.99%   |
| Samsung 355V4C          | 1         | 0.99%   |
| Online Labs SR          | 1         | 0.99%   |
| Notebook W230ST         | 1         | 0.99%   |
| Nokia N900              | 1         | 0.99%   |
| MTC Montara-GML         | 1         | 0.99%   |
| MSI MS-7B84             | 1         | 0.99%   |
| MSI MS-7B53             | 1         | 0.99%   |
| MSI MS-7A34             | 1         | 0.99%   |
| MSI MS-7885             | 1         | 0.99%   |
| MSI MS-1688             | 1         | 0.99%   |
| MSI Modern              | 1         | 0.99%   |
| Microsoft Surface       | 1         | 0.99%   |
| Lenovo Yoga             | 1         | 0.99%   |
| Lenovo V310-14ISK       | 1         | 0.99%   |
| Lenovo ThinkStation     | 1         | 0.99%   |
| IP3 Tech HeroBox        | 1         | 0.99%   |
| Intel D815EEA           | 1         | 0.99%   |
| Intel AHV               | 1         | 0.99%   |
| IBM ThinkPad            | 1         | 0.99%   |
| HP Z220                 | 1         | 0.99%   |
| HP ProDesk              | 1         | 0.99%   |
| HP ProBook              | 1         | 0.99%   |
| HP Notebook             | 1         | 0.99%   |
| HP Laptop               | 1         | 0.99%   |
| HP EliteDesk            | 1         | 0.99%   |
| HP Compaq               | 1         | 0.99%   |
| Google Panther          | 1         | 0.99%   |
| Gigabyte Z390           | 1         | 0.99%   |
| Gigabyte P55A-UD3       | 1         | 0.99%   |
| Gigabyte MZGLKBP-00     | 1         | 0.99%   |
| Gigabyte H310M          | 1         | 0.99%   |
| Gigabyte H170-HD3-CF    | 1         | 0.99%   |
| Gigabyte H170-HD3       | 1         | 0.99%   |
| Gigabyte GA-G41M-ES2L   | 1         | 0.99%   |
| Gigabyte B75M-D3V       | 1         | 0.99%   |
| Gigabyte B450           | 1         | 0.99%   |
| Gigabyte 970A-DS3P      | 1         | 0.99%   |
| Fujitsu Siemens ESPRIMO | 1         | 0.99%   |
| Fujitsu Siemens AMILO   | 1         | 0.99%   |
| Fujitsu LIFEBOOK        | 1         | 0.99%   |
| Dell Vostro             | 1         | 0.99%   |
| Dell Precision          | 1         | 0.99%   |
| Dell Inspiron           | 1         | 0.99%   |
| Chuwi Hi10              | 1         | 0.99%   |
| CCE Capella             | 1         | 0.99%   |
| ASUS X555LJ             | 1         | 0.99%   |
| ASUS ROG                | 1         | 0.99%   |
| ASUS P5PE-VM            | 1         | 0.99%   |
| ASUS P5G41T-M           | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 13        | 12.87%  |
| 2012    | 11        | 10.89%  |
| 2019    | 10        | 9.9%    |
| 2017    | 7         | 6.93%   |
| 2014    | 7         | 6.93%   |
| 2011    | 7         | 6.93%   |
| 2010    | 7         | 6.93%   |
| 2013    | 6         | 5.94%   |
| 2016    | 5         | 4.95%   |
| 2009    | 5         | 4.95%   |
| 2021    | 4         | 3.96%   |
| 2015    | 4         | 3.96%   |
| 2008    | 4         | 3.96%   |
| 2006    | 3         | 2.97%   |
| 2020    | 2         | 1.98%   |
| 2007    | 2         | 1.98%   |
| 2005    | 2         | 1.98%   |
| 2000    | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 50        | 49.5%   |
| Desktop     | 43        | 42.57%  |
| Tablet      | 3         | 2.97%   |
| Mini pc     | 3         | 2.97%   |
| Convertible | 2         | 1.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 99        | 98.02%  |
| Enabled  | 2         | 1.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 97.03%  |
| Yes  | 3         | 2.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 23.76%  |
| 4.01-8.0    | 20        | 19.8%   |
| 16.01-24.0  | 19        | 18.81%  |
| 3.01-4.0    | 16        | 15.84%  |
| 32.01-64.0  | 8         | 7.92%   |
| 1.01-2.0    | 6         | 5.94%   |
| 2.01-3.0    | 3         | 2.97%   |
| 0.01-0.5    | 3         | 2.97%   |
| 64.01-256.0 | 2         | 1.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 42        | 38.18%  |
| 4.01-8.0   | 21        | 19.09%  |
| 2.01-3.0   | 18        | 16.36%  |
| 0.51-1.0   | 13        | 11.82%  |
| 3.01-4.0   | 7         | 6.36%   |
| 0.01-0.5   | 5         | 4.55%   |
| 8.01-16.0  | 3         | 2.73%   |
| 32.01-64.0 | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 60.78%  |
| 2      | 20        | 19.61%  |
| 3      | 10        | 9.8%    |
| 4      | 5         | 4.9%    |
| 5      | 4         | 3.92%   |
| 6      | 1         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 63.73%  |
| Yes       | 37        | 36.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 90.1%   |
| No        | 10        | 9.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 62.75%  |
| No        | 38        | 37.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 63.73%  |
| Yes       | 37        | 36.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 8.82%   |
| Russia      | 9         | 8.82%   |
| Germany     | 8         | 7.84%   |
| France      | 8         | 7.84%   |
| Ukraine     | 7         | 6.86%   |
| Brazil      | 7         | 6.86%   |
| UK          | 4         | 3.92%   |
| Slovakia    | 4         | 3.92%   |
| Poland      | 4         | 3.92%   |
| Grenada     | 4         | 3.92%   |
| Spain       | 3         | 2.94%   |
| Netherlands | 3         | 2.94%   |
| Australia   | 3         | 2.94%   |
| New Zealand | 2         | 1.96%   |
| Israel      | 2         | 1.96%   |
| Indonesia   | 2         | 1.96%   |
| Hungary     | 2         | 1.96%   |
| Finland     | 2         | 1.96%   |
| Argentina   | 2         | 1.96%   |
| Vietnam     | 1         | 0.98%   |
| Switzerland | 1         | 0.98%   |
| South Korea | 1         | 0.98%   |
| Singapore   | 1         | 0.98%   |
| Serbia      | 1         | 0.98%   |
| Puerto Rico | 1         | 0.98%   |
| Portugal    | 1         | 0.98%   |
| Norway      | 1         | 0.98%   |
| Mexico      | 1         | 0.98%   |
| Italy       | 1         | 0.98%   |
| India       | 1         | 0.98%   |
| Greece      | 1         | 0.98%   |
| El Salvador | 1         | 0.98%   |
| Canada      | 1         | 0.98%   |
| Belgium     | 1         | 0.98%   |
| Belarus     | 1         | 0.98%   |
| Austria     | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Saint George's       | 4         | 3.92%   |
| Bratislava           | 4         | 3.92%   |
| Bagnolet             | 4         | 3.92%   |
| Wroclaw              | 2         | 1.96%   |
| Volzhskiy            | 2         | 1.96%   |
| Tel Aviv             | 2         | 1.96%   |
| Sydney               | 2         | 1.96%   |
| Sao Paulo            | 2         | 1.96%   |
| Rio de Janeiro       | 2         | 1.96%   |
| Nadudvar             | 2         | 1.96%   |
| Kyiv                 | 2         | 1.96%   |
| Auckland             | 2         | 1.96%   |
| Yakutsk              | 1         | 0.98%   |
| Windisch             | 1         | 0.98%   |
| Wildberg             | 1         | 0.98%   |
| Vladikavkaz          | 1         | 0.98%   |
| Trubchëvsk          | 1         | 0.98%   |
| Toronto              | 1         | 0.98%   |
| Thessaloniki         | 1         | 0.98%   |
| Tangerang            | 1         | 0.98%   |
| Talavera de la Reina | 1         | 0.98%   |
| Staunton             | 1         | 0.98%   |
| St Petersburg        | 1         | 0.98%   |
| Singapore            | 1         | 0.98%   |
| Seongbuk-gu          | 1         | 0.98%   |
| San Salvador         | 1         | 0.98%   |
| Saint-Herblain       | 1         | 0.98%   |
| Reutlingen           | 1         | 0.98%   |
| Renkum               | 1         | 0.98%   |
| Praia Grande         | 1         | 0.98%   |
| Poperinge            | 1         | 0.98%   |
| Paris                | 1         | 0.98%   |
| Oslo                 | 1         | 0.98%   |
| Oleksandriya         | 1         | 0.98%   |
| Okehampton           | 1         | 0.98%   |
| Novopskov            | 1         | 0.98%   |
| Norman               | 1         | 0.98%   |
| Neuilly-Saint-Front  | 1         | 0.98%   |
| Nérac               | 1         | 0.98%   |
| Muenster-Sarmsheim   | 1         | 0.98%   |
| Moscow               | 1         | 0.98%   |
| Milan                | 1         | 0.98%   |
| Miedziana Gora       | 1         | 0.98%   |
| Miami                | 1         | 0.98%   |
| Maladzyechna         | 1         | 0.98%   |
| Madrid               | 1         | 0.98%   |
| Loosdrecht           | 1         | 0.98%   |
| Leonding             | 1         | 0.98%   |
| Leipzig              | 1         | 0.98%   |
| Leeds                | 1         | 0.98%   |
| Kouvola              | 1         | 0.98%   |
| Kochi                | 1         | 0.98%   |
| Kirov                | 1         | 0.98%   |
| Kharkiv              | 1         | 0.98%   |
| Katzenbach           | 1         | 0.98%   |
| Katowice             | 1         | 0.98%   |
| Karlsruhe            | 1         | 0.98%   |
| Jyväskylä          | 1         | 0.98%   |
| Holt                 | 1         | 0.98%   |
| Hollywood            | 1         | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 47     | 19.33%  |
| Seagate             | 21        | 29     | 14%     |
| Samsung Electronics | 13        | 19     | 8.67%   |
| Kingston            | 13        | 16     | 8.67%   |
| Unknown             | 7         | 9      | 4.67%   |
| Toshiba             | 7         | 7      | 4.67%   |
| Crucial             | 6         | 8      | 4%      |
| SK hynix            | 4         | 4      | 2.67%   |
| SanDisk             | 4         | 4      | 2.67%   |
| Hitachi             | 4         | 4      | 2.67%   |
| PNY                 | 3         | 3      | 2%      |
| Netac               | 3         | 3      | 2%      |
| HGST                | 3         | 3      | 2%      |
| Fujitsu             | 3         | 3      | 2%      |
| Micron Technology   | 2         | 2      | 1.33%   |
| Hewlett-Packard     | 2         | 3      | 1.33%   |
| Dogfish             | 2         | 2      | 1.33%   |
| A-DATA Technology   | 2         | 2      | 1.33%   |
| WD MediaMax         | 1         | 3      | 0.67%   |
| Union Memory        | 1         | 2      | 0.67%   |
| UMIS                | 1         | 1      | 0.67%   |
| Transcend           | 1         | 2      | 0.67%   |
| Teclast             | 1         | 1      | 0.67%   |
| Team                | 1         | 1      | 0.67%   |
| Smart               | 1         | 1      | 0.67%   |
| SABRENT             | 1         | 2      | 0.67%   |
| Patriot             | 1         | 1      | 0.67%   |
| Mushkin             | 1         | 1      | 0.67%   |
| Maxtor              | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| LITEON              | 1         | 4      | 0.67%   |
| Lenovo              | 1         | 1      | 0.67%   |
| Kston               | 1         | 1      | 0.67%   |
| KIOXIA              | 1         | 1      | 0.67%   |
| KingFast            | 1         | 1      | 0.67%   |
| KingDian            | 1         | 1      | 0.67%   |
| Intel               | 1         | 1      | 0.67%   |
| IBM/Hitachi         | 1         | 1      | 0.67%   |
| HXY                 | 1         | 1      | 0.67%   |
| GOODRAM             | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                  | 3         | 1.79%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.79%   |
| Kingston SA2000M8250G 250GB          | 3         | 1.79%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 1.19%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.19%   |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 1.19%   |
| Seagate ST3500418AS 500GB            | 2         | 1.19%   |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 1.19%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.19%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.19%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.19%   |
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
| Unknown MMC Card  8GB                | 1         | 0.6%    |
| Unknown MMC Card  32GB               | 1         | 0.6%    |
| Unknown MMC Card  16GB               | 1         | 0.6%    |
| Unknown MMC Card  128GB              | 1         | 0.6%    |
| Union Memory RTOTJ128VGD2EYX 128GB   | 1         | 0.6%    |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 0.6%    |
| Transcend TS128GSSD370S 128GB        | 1         | 0.6%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.6%    |
| Toshiba MQ02ABF100 1TB               | 1         | 0.6%    |
| Toshiba MK5065GSX 500GB              | 1         | 0.6%    |
| Toshiba MK1252GSX 120GB              | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 25        | 41     | 37.88%  |
| Seagate         | 21        | 29     | 31.82%  |
| Toshiba         | 6         | 6      | 9.09%   |
| Hitachi         | 4         | 4      | 6.06%   |
| HGST            | 3         | 3      | 4.55%   |
| Fujitsu         | 3         | 3      | 4.55%   |
| SABRENT         | 1         | 2      | 1.52%   |
| Maxtor          | 1         | 1      | 1.52%   |
| IBM/Hitachi     | 1         | 1      | 1.52%   |
| Hewlett-Packard | 1         | 2      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 12     | 17.54%  |
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
| LITEON              | 1         | 4      | 1.75%   |
| Kston               | 1         | 1      | 1.75%   |
| KingDian            | 1         | 1      | 1.75%   |
| HXY                 | 1         | 1      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 56        | 92     | 41.48%  |
| SSD     | 51        | 67     | 37.78%  |
| NVMe    | 19        | 26     | 14.07%  |
| MMC     | 7         | 9      | 5.19%   |
| Unknown | 2         | 4      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 154    | 73.73%  |
| NVMe | 19        | 26     | 16.1%   |
| MMC  | 7         | 9      | 5.93%   |
| SAS  | 5         | 9      | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 96     | 64.76%  |
| 0.51-1.0   | 23        | 44     | 21.9%   |
| 1.01-2.0   | 8         | 13     | 7.62%   |
| 3.01-4.0   | 5         | 5      | 4.76%   |
| 4.01-10.0  | 1         | 1      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 21.7%   |
| 101-250        | 21        | 19.81%  |
| 1001-2000      | 14        | 13.21%  |
| 501-1000       | 13        | 12.26%  |
| 51-100         | 10        | 9.43%   |
| 21-50          | 8         | 7.55%   |
| Unknown        | 6         | 5.66%   |
| More than 3000 | 5         | 4.72%   |
| 2001-3000      | 3         | 2.83%   |
| 1-20           | 3         | 2.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 26.67%  |
| 101-250        | 25        | 23.81%  |
| 21-50          | 13        | 12.38%  |
| 51-100         | 10        | 9.52%   |
| 1001-2000      | 7         | 6.67%   |
| 501-1000       | 7         | 6.67%   |
| 251-500        | 6         | 5.71%   |
| Unknown        | 6         | 5.71%   |
| More than 3000 | 2         | 1.9%    |
| 2001-3000      | 1         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 77        | 135    | 64.71%  |
| Detected | 25        | 44     | 21.01%  |
| Malfunc  | 17        | 19     | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 74        | 62.18%  |
| AMD                              | 17        | 14.29%  |
| Samsung Electronics              | 5         | 4.2%    |
| Kingston Technology Company      | 4         | 3.36%   |
| SK hynix                         | 2         | 1.68%   |
| SanDisk                          | 2         | 1.68%   |
| Micron/Crucial Technology        | 2         | 1.68%   |
| Marvell Technology Group         | 2         | 1.68%   |
| VIA Technologies                 | 1         | 0.84%   |
| Union Memory (Shenzhen)          | 1         | 0.84%   |
| Toshiba America Info Systems     | 1         | 0.84%   |
| Silicon Integrated Systems [SiS] | 1         | 0.84%   |
| Nvidia                           | 1         | 0.84%   |
| Lenovo                           | 1         | 0.84%   |
| KIOXIA                           | 1         | 0.84%   |
| Integrated Technology Express    | 1         | 0.84%   |
| Broadcom / LSI                   | 1         | 0.84%   |
| ASMedia Technology               | 1         | 0.84%   |
| Adaptec                          | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 8.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 3.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 3.65%   |
| Kingston Company A2000 NVMe SSD                                                        | 4         | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 2.92%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 2.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 4         | 2.92%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 2.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 2.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 2.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 2.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 2.19%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.46%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 1.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 1.46%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 0.73%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.73%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.73%   |
| SK hynix BC511                                                                         | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.73%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.73%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.73%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.73%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                | 1         | 0.73%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.73%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                             | 1         | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                       | 1         | 0.73%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                       | 1         | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.73%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.73%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 0.73%   |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 61.02%  |
| NVMe | 19        | 16.1%   |
| IDE  | 18        | 15.25%  |
| RAID | 8         | 6.78%   |
| SCSI | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 81.19%  |
| AMD    | 18        | 17.82%  |
| ARM    | 1         | 0.99%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.94%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.96%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.96%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.96%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.98%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.98%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.98%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.98%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.98%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.98%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.98%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.98%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.98%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.98%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.98%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.98%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.98%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.98%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.98%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.98%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.98%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.98%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.98%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.98%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.98%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.98%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.98%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.98%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1         | 0.98%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 0.98%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1         | 0.98%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 0.98%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 0.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 0.98%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 0.98%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 0.98%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 0.98%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 0.98%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.98%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 0.98%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 24.51%  |
| Intel Core i7           | 15        | 14.71%  |
| Intel Core i3           | 11        | 10.78%  |
| Intel Celeron           | 5         | 4.9%    |
| Intel Core 2 Duo        | 4         | 3.92%   |
| AMD Ryzen 5             | 4         | 3.92%   |
| Intel Xeon              | 3         | 2.94%   |
| Intel Core 2            | 3         | 2.94%   |
| Other                   | 2         | 1.96%   |
| Intel Pentium M         | 2         | 1.96%   |
| Intel Pentium Dual-Core | 2         | 1.96%   |
| Intel Pentium Dual      | 2         | 1.96%   |
| Intel Pentium           | 2         | 1.96%   |
| Intel Core i9           | 2         | 1.96%   |
| Intel Atom              | 2         | 1.96%   |
| AMD Ryzen 7             | 2         | 1.96%   |
| AMD Ryzen 3             | 2         | 1.96%   |
| Intel Pentium Silver    | 1         | 0.98%   |
| Intel Pentium Gold      | 1         | 0.98%   |
| Intel Pentium 4         | 1         | 0.98%   |
| Intel Core 2 Quad       | 1         | 0.98%   |
| Intel Celeron M         | 1         | 0.98%   |
| AMD Sempron             | 1         | 0.98%   |
| AMD FX                  | 1         | 0.98%   |
| AMD E2                  | 1         | 0.98%   |
| AMD E                   | 1         | 0.98%   |
| AMD Athlon II           | 1         | 0.98%   |
| AMD A8                  | 1         | 0.98%   |
| AMD A6                  | 1         | 0.98%   |
| AMD A4                  | 1         | 0.98%   |
| AMD A10                 | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 47        | 46.53%  |
| 4      | 31        | 30.69%  |
| 6      | 11        | 10.89%  |
| 1      | 8         | 7.92%   |
| 8      | 3         | 2.97%   |
| 10     | 1         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 101       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 53.47%  |
| 1      | 47        | 46.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 94        | 93.07%  |
| 32-bit         | 4         | 3.96%   |
| Unknown        | 3         | 2.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 22.12%  |
| 0x306a9    | 6         | 5.77%   |
| 0x206a7    | 6         | 5.77%   |
| 0x906ea    | 5         | 4.81%   |
| 0x406e3    | 5         | 4.81%   |
| 0x306c3    | 5         | 4.81%   |
| 0x1067a    | 5         | 4.81%   |
| 0x806ec    | 4         | 3.85%   |
| 0x40651    | 3         | 2.88%   |
| 0x306d4    | 3         | 2.88%   |
| 0x706a1    | 2         | 1.92%   |
| 0x6f6      | 2         | 1.92%   |
| 0x20655    | 2         | 1.92%   |
| 0x106e5    | 2         | 1.92%   |
| 0x08608103 | 2         | 1.92%   |
| 0xf49      | 1         | 0.96%   |
| 0xa0655    | 1         | 0.96%   |
| 0xa0653    | 1         | 0.96%   |
| 0x906ed    | 1         | 0.96%   |
| 0x906e9    | 1         | 0.96%   |
| 0x806ea    | 1         | 0.96%   |
| 0x706a8    | 1         | 0.96%   |
| 0x6fd      | 1         | 0.96%   |
| 0x6d8      | 1         | 0.96%   |
| 0x695      | 1         | 0.96%   |
| 0x686      | 1         | 0.96%   |
| 0x506e3    | 1         | 0.96%   |
| 0x406d8    | 1         | 0.96%   |
| 0x406c4    | 1         | 0.96%   |
| 0x306f2    | 1         | 0.96%   |
| 0x30678    | 1         | 0.96%   |
| 0x20652    | 1         | 0.96%   |
| 0x10676    | 1         | 0.96%   |
| 0x08701021 | 1         | 0.96%   |
| 0x08701013 | 1         | 0.96%   |
| 0x0800820d | 1         | 0.96%   |
| 0x08001138 | 1         | 0.96%   |
| 0x08001129 | 1         | 0.96%   |
| 0x07030105 | 1         | 0.96%   |
| 0x0600611a | 1         | 0.96%   |
| 0x05000119 | 1         | 0.96%   |
| 0x05000101 | 1         | 0.96%   |
| 0x03000027 | 1         | 0.96%   |
| 0x010000b6 | 1         | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 13.86%  |
| Haswell       | 10        | 9.9%    |
| IvyBridge     | 8         | 7.92%   |
| Skylake       | 7         | 6.93%   |
| Penryn        | 7         | 6.93%   |
| SandyBridge   | 6         | 5.94%   |
| Westmere      | 5         | 4.95%   |
| Silvermont    | 4         | 3.96%   |
| P6            | 4         | 3.96%   |
| Core          | 4         | 3.96%   |
| Broadwell     | 4         | 3.96%   |
| Nehalem       | 3         | 2.97%   |
| Goldmont plus | 3         | 2.97%   |
| Unknown       | 3         | 2.97%   |
| Zen+          | 2         | 1.98%   |
| Zen 2         | 2         | 1.98%   |
| Zen           | 2         | 1.98%   |
| Piledriver    | 2         | 1.98%   |
| Excavator     | 2         | 1.98%   |
| CometLake     | 2         | 1.98%   |
| Bobcat        | 2         | 1.98%   |
| Puma          | 1         | 0.99%   |
| NetBurst      | 1         | 0.99%   |
| K8 Hammer     | 1         | 0.99%   |
| K10 Llano     | 1         | 0.99%   |
| K10           | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 60        | 55.05%  |
| AMD                              | 26        | 23.85%  |
| Nvidia                           | 22        | 20.18%  |
| Silicon Integrated Systems [SiS] | 1         | 0.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.48%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.48%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.61%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.74%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.74%   |
| AMD Lucienne                                                                             | 2         | 1.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.87%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.87%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.87%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.87%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.87%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.87%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.87%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.87%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 0.87%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.87%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.87%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 0.87%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.87%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.87%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.87%   |
| Intel HD Graphics 630                                                                    | 1         | 0.87%   |
| Intel HD Graphics 620                                                                    | 1         | 0.87%   |
| Intel HD Graphics 520                                                                    | 1         | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.87%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.87%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.87%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.87%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.87%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.87%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 0.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 47.52%  |
| 1 x AMD        | 21        | 20.79%  |
| 1 x Nvidia     | 15        | 14.85%  |
| Intel + Nvidia | 7         | 6.93%   |
| Other          | 3         | 2.97%   |
| 2 x AMD        | 3         | 2.97%   |
| Intel + AMD    | 2         | 1.98%   |
| 2 x Intel      | 1         | 0.99%   |
| 1 x SiS        | 1         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 82.35%  |
| Proprietary | 12        | 11.76%  |
| Unknown     | 6         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 59.8%   |
| 0.01-0.5   | 16        | 15.69%  |
| 0.51-1.0   | 7         | 6.86%   |
| 1.01-2.0   | 6         | 5.88%   |
| 3.01-4.0   | 5         | 4.9%    |
| 7.01-8.0   | 3         | 2.94%   |
| 2.01-3.0   | 3         | 2.94%   |
| 5.01-6.0   | 1         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 15.89%  |
| Samsung Electronics     | 15        | 14.02%  |
| AU Optronics            | 11        | 10.28%  |
| Hewlett-Packard         | 7         | 6.54%   |
| Goldstar                | 6         | 5.61%   |
| Chimei Innolux          | 5         | 4.67%   |
| Philips                 | 4         | 3.74%   |
| Lenovo                  | 4         | 3.74%   |
| BOE                     | 4         | 3.74%   |
| AOC                     | 4         | 3.74%   |
| Dell                    | 3         | 2.8%    |
| Acer                    | 3         | 2.8%    |
| Unknown                 | 2         | 1.87%   |
| PANDA                   | 2         | 1.87%   |
| Iiyama                  | 2         | 1.87%   |
| Chi Mei Optoelectronics | 2         | 1.87%   |
| ___                     | 1         | 0.93%   |
| ViewSonic               | 1         | 0.93%   |
| Toshiba                 | 1         | 0.93%   |
| STD                     | 1         | 0.93%   |
| Sony                    | 1         | 0.93%   |
| MStar                   | 1         | 0.93%   |
| MSI                     | 1         | 0.93%   |
| InnoLux Display         | 1         | 0.93%   |
| InfoVision              | 1         | 0.93%   |
| HJW                     | 1         | 0.93%   |
| Hisense                 | 1         | 0.93%   |
| eMachines               | 1         | 0.93%   |
| Eizo                    | 1         | 0.93%   |
| CVT                     | 1         | 0.93%   |
| CHI                     | 1         | 0.93%   |
| Ancor Communications    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.8%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.8%    |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.8%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.8%    |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 0.9%    |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.9%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.9%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 0.9%    |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.9%    |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                      | 1         | 0.9%    |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                          | 1         | 0.9%    |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.9%    |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch      | 1         | 0.9%    |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.9%    |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.9%    |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.9%    |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.9%    |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.9%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.9%    |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 0.9%    |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 0.9%    |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 0.9%    |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 0.9%    |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                        | 1         | 0.9%    |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 1         | 0.9%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch            | 1         | 0.9%    |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1         | 0.9%    |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1         | 0.9%    |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                | 1         | 0.9%    |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                | 1         | 0.9%    |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch       | 1         | 0.9%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 1         | 0.9%    |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1         | 0.9%    |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1         | 0.9%    |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 0.9%    |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                  | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 39.05%  |
| 1366x768 (WXGA)    | 30        | 28.57%  |
| 3840x2160 (4K)     | 7         | 6.67%   |
| 1440x900 (WXGA+)   | 5         | 4.76%   |
| 1280x1024 (SXGA)   | 5         | 4.76%   |
| 1600x900 (HD+)     | 2         | 1.9%    |
| 1600x1200          | 2         | 1.9%    |
| 1280x800 (WXGA)    | 2         | 1.9%    |
| Unknown            | 2         | 1.9%    |
| 5760x1080          | 1         | 0.95%   |
| 3440x1440          | 1         | 0.95%   |
| 3000x2000          | 1         | 0.95%   |
| 2736x1824          | 1         | 0.95%   |
| 2288x1287          | 1         | 0.95%   |
| 1920x1200 (WUXGA)  | 1         | 0.95%   |
| 1680x1050 (WSXGA+) | 1         | 0.95%   |
| 1360x768           | 1         | 0.95%   |
| 1024x768 (XGA)     | 1         | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 22.86%  |
| 21      | 15        | 14.29%  |
| 12      | 9         | 8.57%   |
| 14      | 8         | 7.62%   |
| 13      | 7         | 6.67%   |
| 24      | 6         | 5.71%   |
| 27      | 5         | 4.76%   |
| 23      | 5         | 4.76%   |
| 17      | 4         | 3.81%   |
| Unknown | 4         | 3.81%   |
| 31      | 3         | 2.86%   |
| 19      | 3         | 2.86%   |
| 18      | 3         | 2.86%   |
| 72      | 2         | 1.9%    |
| 142     | 1         | 0.95%   |
| 54      | 1         | 0.95%   |
| 52      | 1         | 0.95%   |
| 40      | 1         | 0.95%   |
| 34      | 1         | 0.95%   |
| 22      | 1         | 0.95%   |
| 11      | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 35        | 34.65%  |
| 401-500        | 18        | 17.82%  |
| 501-600        | 15        | 14.85%  |
| 201-300        | 15        | 14.85%  |
| 351-400        | 4         | 3.96%   |
| Unknown        | 4         | 3.96%   |
| 601-700        | 3         | 2.97%   |
| 1501-2000      | 2         | 1.98%   |
| 1001-1500      | 2         | 1.98%   |
| More than 2000 | 1         | 0.99%   |
| 801-900        | 1         | 0.99%   |
| 701-800        | 1         | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 75.53%  |
| 16/10   | 8         | 8.51%   |
| 4/3     | 4         | 4.26%   |
| 5/4     | 3         | 3.19%   |
| Unknown | 3         | 3.19%   |
| 3/2     | 2         | 2.13%   |
| 6/5     | 1         | 1.06%   |
| 21/9    | 1         | 1.06%   |
| 1.00    | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 21.36%  |
| 201-250        | 19        | 18.45%  |
| 81-90          | 10        | 9.71%   |
| 61-70          | 9         | 8.74%   |
| 151-200        | 9         | 8.74%   |
| More than 1000 | 5         | 4.85%   |
| 71-80          | 5         | 4.85%   |
| 301-350        | 5         | 4.85%   |
| 351-500        | 4         | 3.88%   |
| 141-150        | 4         | 3.88%   |
| Unknown        | 4         | 3.88%   |
| 111-120        | 2         | 1.94%   |
| 51-60          | 1         | 0.97%   |
| 251-300        | 1         | 0.97%   |
| 131-140        | 1         | 0.97%   |
| 121-130        | 1         | 0.97%   |
| 501-1000       | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 36        | 35.29%  |
| 51-100        | 30        | 29.41%  |
| 121-160       | 20        | 19.61%  |
| 1-50          | 5         | 4.9%    |
| 161-240       | 5         | 4.9%    |
| Unknown       | 4         | 3.92%   |
| More than 240 | 2         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 78.64%  |
| 2     | 14        | 13.59%  |
| 3     | 4         | 3.88%   |
| 0     | 4         | 3.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 33.1%   |
| Intel                            | 48        | 33.1%   |
| Qualcomm Atheros                 | 23        | 15.86%  |
| Ralink Technology                | 3         | 2.07%   |
| Marvell Technology Group         | 3         | 2.07%   |
| TP-Link                          | 2         | 1.38%   |
| Sierra Wireless                  | 2         | 1.38%   |
| NetGear                          | 2         | 1.38%   |
| MediaTek                         | 2         | 1.38%   |
| JMicron Technology               | 2         | 1.38%   |
| Broadcom Limited                 | 2         | 1.38%   |
| Broadcom                         | 2         | 1.38%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.69%   |
| VIA Technologies                 | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Samsung Electronics              | 1         | 0.69%   |
| Ralink                           | 1         | 0.69%   |
| Nvidia                           | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 33        | 19.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 5.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.37%   |
| Intel Wireless 7260                                                     | 4         | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.78%   |
| Intel Wireless 7265                                                     | 3         | 1.78%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.78%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 1.78%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.78%   |
| Sierra Wireless EM7455                                                  | 2         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.18%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.18%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.18%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.18%   |
| Intel Wireless 8260                                                     | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.18%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.18%   |
| ZTE WCDMA MSM ZTE Mobile Broadband Station                              | 1         | 0.59%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.59%   |
| TP-Link TL-WN722N v2                                                    | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.59%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.59%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.59%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.59%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.59%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.59%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.59%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.59%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.59%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.59%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.59%   |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 32.84%  |
| Qualcomm Atheros         | 21        | 31.34%  |
| Realtek Semiconductor    | 9         | 13.43%  |
| Ralink Technology        | 3         | 4.48%   |
| Sierra Wireless          | 2         | 2.99%   |
| NetGear                  | 2         | 2.99%   |
| MediaTek                 | 2         | 2.99%   |
| Broadcom Limited         | 2         | 2.99%   |
| TP-Link                  | 1         | 1.49%   |
| Ralink                   | 1         | 1.49%   |
| Marvell Technology Group | 1         | 1.49%   |
| Broadcom                 | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.97%   |
| Intel Wireless 7260                                                     | 4         | 5.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 5.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.48%   |
| Intel Wireless 7265                                                     | 3         | 4.48%   |
| Sierra Wireless EM7455                                                  | 2         | 2.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.99%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.99%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.99%   |
| Intel Wireless 8260                                                     | 2         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.99%   |
| TP-Link TL-WN722N v2                                                    | 1         | 1.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.49%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.49%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.49%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.49%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.49%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.49%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.49%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.49%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.49%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.49%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 43        | 44.33%  |
| Intel                            | 40        | 41.24%  |
| Qualcomm Atheros                 | 4         | 4.12%   |
| Marvell Technology Group         | 2         | 2.06%   |
| JMicron Technology               | 2         | 2.06%   |
| VIA Technologies                 | 1         | 1.03%   |
| TP-Link                          | 1         | 1.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.03%   |
| Samsung Electronics              | 1         | 1.03%   |
| Nvidia                           | 1         | 1.03%   |
| Broadcom                         | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 33.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 6.12%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 3.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.04%   |
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

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 57.23%  |
| WiFi     | 64        | 40.25%  |
| Modem    | 4         | 2.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 52.88%  |
| WiFi     | 48        | 46.15%  |
| Modem    | 1         | 0.96%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 55        | 53.92%  |
| 1     | 41        | 40.2%   |
| 0     | 4         | 3.92%   |
| 5     | 1         | 0.98%   |
| 3     | 1         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 90.1%   |
| Yes  | 10        | 9.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


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

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 57.14%  |
| AMD                              | 22        | 16.54%  |
| Nvidia                           | 17        | 12.78%  |
| Plantronics                      | 2         | 1.5%    |
| Creative Labs                    | 2         | 1.5%    |
| Texas Instruments                | 1         | 0.75%   |
| TEAC                             | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Realtek Semiconductor            | 1         | 0.75%   |
| M-Audio                          | 1         | 0.75%   |
| Logitech                         | 1         | 0.75%   |
| KORG                             | 1         | 0.75%   |
| GYROCOM C&C                      | 1         | 0.75%   |
| Elite Silicon                    | 1         | 0.75%   |
| DCMT Technology                  | 1         | 0.75%   |
| Cirrus Logic                     | 1         | 0.75%   |
| C-Media Electronics              | 1         | 0.75%   |
| Blue Microphones                 | 1         | 0.75%   |
| ASUSTek Computer                 | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 5%      |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.5%    |
| AMD FCH Azalia Controller                                                  | 4         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.88%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.88%   |
| Plantronics HD1                                                            | 2         | 1.25%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.25%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.25%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.25%   |
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
| Logitech H390 headset with microphone                                      | 1         | 0.63%   |
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

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 1.71%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 1.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.71%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 2         | 1.71%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.71%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s               | 2         | 1.71%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                         | 1         | 0.85%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                           | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 0.85%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                          | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.85%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                          | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                          | 1         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR                                  | 1         | 0.85%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s               | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 1         | 0.85%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.85%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.85%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                       | 1         | 0.85%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s                     | 1         | 0.85%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.85%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s                     | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                | 1         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.85%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.85%   |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 54.02%  |
| DIMM         | 37        | 42.53%  |
| Row Of Chips | 3         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 34.31%  |
| 4096  | 29        | 28.43%  |
| 2048  | 16        | 15.69%  |
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

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 2         | 50%     |
| Custom Engineering SPA | 1         | 25%     |
| Brother Industries     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 34.55%  |
| Microdia                               | 5         | 9.09%   |
| Sunplus Innovation Technology          | 4         | 7.27%   |
| Acer                                   | 4         | 7.27%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.45%   |
| Suyin                                  | 2         | 3.64%   |
| Realtek Semiconductor                  | 2         | 3.64%   |
| Logitech                               | 2         | 3.64%   |
| KYE Systems (Mouse Systems)            | 2         | 3.64%   |
| Cubeternet                             | 2         | 3.64%   |
| Z-Star Microelectronics                | 1         | 1.82%   |
| Softkinetic                            | 1         | 1.82%   |
| Samsung Electronics                    | 1         | 1.82%   |
| Quanta                                 | 1         | 1.82%   |
| Mustek Systems                         | 1         | 1.82%   |
| Microsoft                              | 1         | 1.82%   |
| MacroSilicon                           | 1         | 1.82%   |
| Lite-On Technology                     | 1         | 1.82%   |
| IMC Networks                           | 1         | 1.82%   |
| GEMBIRD                                | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 12.73%  |
| Cubeternet GL-UPC822 UVC WebCam                                 | 2         | 3.64%   |
| Chicony HD Webcam                                               | 2         | 3.64%   |
| Chicony EasyCamera                                              | 2         | 3.64%   |
| Acer BisonCam, NB Pro                                           | 2         | 3.64%   |
| Z-Star A4 TECH USB2.0 PC Camera E                               | 1         | 1.82%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 1.82%   |
| Sunplus Laptop Integrated Webcam HD                             | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.82%   |
| Sunplus Depstech webcam MIC                                     | 1         | 1.82%   |
| Sunplus ASUS USB2.0 Webcam                                      | 1         | 1.82%   |
| Softkinetic DepthSense 325                                      | 1         | 1.82%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 1.82%   |
| Realtek USB CAMERA                                              | 1         | 1.82%   |
| Realtek Integrated Webcam_HD                                    | 1         | 1.82%   |
| Quanta Sony Visual Communication Camera                         | 1         | 1.82%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 1.82%   |
| Microsoft LifeCam Studio                                        | 1         | 1.82%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 1.82%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 1.82%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.82%   |
| Microdia Camera                                                 | 1         | 1.82%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 1.82%   |
| MacroSilicon USB Video                                          | 1         | 1.82%   |
| Logitech Webcam C270                                            | 1         | 1.82%   |
| Logitech HD Pro Webcam C920                                     | 1         | 1.82%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 1.82%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                      | 1         | 1.82%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                       | 1         | 1.82%   |
| IMC Networks Integrated Webcam                                  | 1         | 1.82%   |
| GEMBIRD USB2.0 PC CAMERA                                        | 1         | 1.82%   |
| Chicony WebCam                                                  | 1         | 1.82%   |
| Chicony VGA WebCam                                              | 1         | 1.82%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 1.82%   |
| Chicony Thinkpad T430 camera                                    | 1         | 1.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 1.82%   |
| Chicony Lenovo EasyCamera                                       | 1         | 1.82%   |
| Chicony HP TrueVision HD                                        | 1         | 1.82%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 1.82%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 1.82%   |
| Acer Integrated Camera                                          | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 25%     |
| Upek               | 1         | 25%     |
| Synaptics          | 1         | 25%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 2         | 22.22%  |
| Lenovo      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 78        | 75.73%  |
| 1     | 17        | 16.5%   |
| 2     | 6         | 5.83%   |
| 3     | 2         | 1.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


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


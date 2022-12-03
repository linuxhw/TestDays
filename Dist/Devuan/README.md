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

Total: 141

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
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
| Devuan 4                | 48        | 42.11%  |
| Devuan 3                | 30        | 26.32%  |
| Devuan Testing/unstable | 15        | 13.16%  |
| Devuan 5                | 9         | 7.89%   |
| Devuan 2.1              | 7         | 6.14%   |
| Devuan                  | 2         | 1.75%   |
| Devuan 3.0              | 1         | 0.88%   |
| Devuan 2.0              | 1         | 0.88%   |
| Devuan 1.0.0            | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 107       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 10        | 8.33%   |
| 5.10.0-8-amd64            | 7         | 5.83%   |
| 4.19.0-9-amd64            | 6         | 5%      |
| 4.19.0-14-amd64           | 6         | 5%      |
| 5.10.0-16-amd64           | 5         | 4.17%   |
| 4.19.0-16-amd64           | 5         | 4.17%   |
| 5.10.0-13-amd64           | 4         | 3.33%   |
| 5.10.0-11-amd64           | 4         | 3.33%   |
| 5.10.0-10-amd64           | 4         | 3.33%   |
| 5.7.0-2-amd64             | 3         | 2.5%    |
| 5.10.0-19-amd64           | 3         | 2.5%    |
| 5.10.0-18-amd64           | 3         | 2.5%    |
| 4.19.0-12-amd64           | 3         | 2.5%    |
| 5.7.0-0.bpo.2-amd64       | 2         | 1.67%   |
| 5.18.0-2-amd64            | 2         | 1.67%   |
| 5.18.0-1-amd64            | 2         | 1.67%   |
| 5.15.0-2-amd64            | 2         | 1.67%   |
| 5.10.0-6-amd64            | 2         | 1.67%   |
| 5.10.0-15-amd64           | 2         | 1.67%   |
| 5.10.0-14-amd64           | 2         | 1.67%   |
| 4.19.0-17-amd64           | 2         | 1.67%   |
| 4.19.0-13-amd64           | 2         | 1.67%   |
| 4.19.0-10-amd64           | 2         | 1.67%   |
| 5.9.0-4-amd64             | 1         | 0.83%   |
| 5.9.0-1-amd64             | 1         | 0.83%   |
| 5.8.0-3-amd64             | 1         | 0.83%   |
| 5.8.0-1-amd64             | 1         | 0.83%   |
| 5.7.19-server1            | 1         | 0.83%   |
| 5.7.0-1-amd64             | 1         | 0.83%   |
| 5.6.0-2-amd64             | 1         | 0.83%   |
| 5.19.0-2-amd64            | 1         | 0.83%   |
| 5.18.14-devuan            | 1         | 0.83%   |
| 5.16.0-1-amd64            | 1         | 0.83%   |
| 5.15.5-xanmod1            | 1         | 0.83%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 0.83%   |
| 5.14.0-kali2-amd64        | 1         | 0.83%   |
| 5.14.0-4-amd64            | 1         | 0.83%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 0.83%   |
| 5.10.0-7-amd64            | 1         | 0.83%   |
| 5.10.0-5-amd64            | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 47        | 41.23%  |
| 4.19.0   | 28        | 24.56%  |
| 4.9.0    | 8         | 7.02%   |
| 5.7.0    | 6         | 5.26%   |
| 5.18.0   | 4         | 3.51%   |
| 5.15.0   | 3         | 2.63%   |
| 5.9.0    | 2         | 1.75%   |
| 5.8.0    | 2         | 1.75%   |
| 5.14.0   | 2         | 1.75%   |
| 5.7.19   | 1         | 0.88%   |
| 5.6.0    | 1         | 0.88%   |
| 5.19.0   | 1         | 0.88%   |
| 5.18.14  | 1         | 0.88%   |
| 5.16.0   | 1         | 0.88%   |
| 5.15.5   | 1         | 0.88%   |
| 5.11.0   | 1         | 0.88%   |
| 5.1.21   | 1         | 0.88%   |
| 5.0.7    | 1         | 0.88%   |
| 4.4.195  | 1         | 0.88%   |
| 4.19.112 | 1         | 0.88%   |
| 4.18.0   | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 41.23%  |
| 4.19    | 29        | 25.44%  |
| 4.9     | 8         | 7.02%   |
| 5.7     | 7         | 6.14%   |
| 5.18    | 5         | 4.39%   |
| 5.15    | 4         | 3.51%   |
| 5.9     | 2         | 1.75%   |
| 5.8     | 2         | 1.75%   |
| 5.14    | 2         | 1.75%   |
| 5.6     | 1         | 0.88%   |
| 5.19    | 1         | 0.88%   |
| 5.16    | 1         | 0.88%   |
| 5.11    | 1         | 0.88%   |
| 5.1     | 1         | 0.88%   |
| 5.0     | 1         | 0.88%   |
| 4.4     | 1         | 0.88%   |
| 4.18    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 93.46%  |
| i686   | 6         | 5.61%   |
| armv7l | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 43        | 38.05%  |
| Unknown    | 18        | 15.93%  |
| MATE       | 16        | 14.16%  |
| KDE5       | 16        | 14.16%  |
| LXDE       | 5         | 4.42%   |
| i3         | 5         | 4.42%   |
| Cinnamon   | 3         | 2.65%   |
| LXQt       | 2         | 1.77%   |
| GNOME      | 2         | 1.77%   |
| X-Cinnamon | 1         | 0.88%   |
| Openbox    | 1         | 0.88%   |
| awesome    | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 98        | 89.91%  |
| Tty     | 8         | 7.34%   |
| Unknown | 3         | 2.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 40        | 36.36%  |
| Unknown | 30        | 27.27%  |
| LightDM | 28        | 25.45%  |
| SDDM    | 7         | 6.36%   |
| XDM     | 2         | 1.82%   |
| GDM3    | 2         | 1.82%   |
| NODM    | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 34        | 31.19%  |
| en_GB       | 19        | 17.43%  |
| ru_RU       | 8         | 7.34%   |
| Unknown     | 7         | 6.42%   |
| C           | 6         | 5.5%    |
| pt_BR       | 5         | 4.59%   |
| fr_FR       | 4         | 3.67%   |
| es_ES       | 4         | 3.67%   |
| sk_SK       | 3         | 2.75%   |
| fr_BE       | 3         | 2.75%   |
| en_AU       | 3         | 2.75%   |
| pl_PL       | 2         | 1.83%   |
| it_IT       | 2         | 1.83%   |
| en_NZ       | 2         | 1.83%   |
| ru_UA       | 1         | 0.92%   |
| es_SV       | 1         | 0.92%   |
| en_US.utf-8 | 1         | 0.92%   |
| en_SG       | 1         | 0.92%   |
| en_CA       | 1         | 0.92%   |
| de_DE       | 1         | 0.92%   |
| de_AT       | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 62        | 57.41%  |
| EFI  | 46        | 42.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 92        | 85.98%  |
| Btrfs   | 5         | 4.67%   |
| Unknown | 5         | 4.67%   |
| Overlay | 2         | 1.87%   |
| OveXlay | 1         | 0.93%   |
| Ext3    | 1         | 0.93%   |
| Ext2    | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 58        | 51.79%  |
| MBR     | 42        | 37.5%   |
| Unknown | 12        | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 77.98%  |
| Yes       | 24        | 22.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 75.93%  |
| Yes       | 26        | 24.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 18.69%  |
| Dell                | 14        | 13.08%  |
| ASUSTek Computer    | 14        | 13.08%  |
| Hewlett-Packard     | 10        | 9.35%   |
| Gigabyte Technology | 10        | 9.35%   |
| MSI                 | 6         | 5.61%   |
| Acer                | 5         | 4.67%   |
| ASRock              | 4         | 3.74%   |
| Toshiba             | 3         | 2.8%    |
| Intel               | 2         | 1.87%   |
| Fujitsu Siemens     | 2         | 1.87%   |
| Teclast             | 1         | 0.93%   |
| Sun Microsystems    | 1         | 0.93%   |
| Sony                | 1         | 0.93%   |
| Samsung Electronics | 1         | 0.93%   |
| Online Labs         | 1         | 0.93%   |
| Notebook            | 1         | 0.93%   |
| Nokia               | 1         | 0.93%   |
| MTC                 | 1         | 0.93%   |
| Microsoft           | 1         | 0.93%   |
| IP3 Tech            | 1         | 0.93%   |
| IBM                 | 1         | 0.93%   |
| Google              | 1         | 0.93%   |
| Fujitsu             | 1         | 0.93%   |
| Chuwi               | 1         | 0.93%   |
| CCE                 | 1         | 0.93%   |
| Apple               | 1         | 0.93%   |
| AMI                 | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.93%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.93%   |
| Toshiba Satellite L655                                                                   | 1         | 0.93%   |
| Teclast F6 Plus                                                                          | 1         | 0.93%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.93%   |
| Sony VPCEE23FX                                                                           | 1         | 0.93%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.93%   |
| Online Labs SR                                                                           | 1         | 0.93%   |
| Notebook W230ST                                                                          | 1         | 0.93%   |
| Nokia N900                                                                               | 1         | 0.93%   |
| MTC Montara-GML                                                                          | 1         | 0.93%   |
| MSI MS-7B84                                                                              | 1         | 0.93%   |
| MSI MS-7B53                                                                              | 1         | 0.93%   |
| MSI MS-7A34                                                                              | 1         | 0.93%   |
| MSI MS-7885                                                                              | 1         | 0.93%   |
| MSI MS-1688                                                                              | 1         | 0.93%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.93%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.93%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.93%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.93%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.93%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.93%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.93%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.93%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.93%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.93%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 0.93%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 0.93%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 0.93%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 0.93%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 0.93%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 0.93%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 0.93%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 0.93%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 0.93%   |
| Lenovo G50-30 80G0                                                                       | 1         | 0.93%   |
| IP3 Tech HeroBox                                                                         | 1         | 0.93%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 12.15%  |
| Dell Latitude          | 7         | 6.54%   |
| Dell OptiPlex          | 4         | 3.74%   |
| Acer Aspire            | 4         | 3.74%   |
| Toshiba Satellite      | 3         | 2.8%    |
| Lenovo IdeaPad         | 3         | 2.8%    |
| ASUS PRIME             | 3         | 2.8%    |
| HP Pavilion            | 2         | 1.87%   |
| HP Laptop              | 2         | 1.87%   |
| ASUS ROG               | 2         | 1.87%   |
| Teclast F6             | 1         | 0.93%   |
| Sun Microsystems Ultra | 1         | 0.93%   |
| Sony VPCEE23FX         | 1         | 0.93%   |
| Samsung 355V4C         | 1         | 0.93%   |
| Online Labs SR         | 1         | 0.93%   |
| Notebook W230ST        | 1         | 0.93%   |
| Nokia N900             | 1         | 0.93%   |
| MTC Montara-GML        | 1         | 0.93%   |
| MSI MS-7B84            | 1         | 0.93%   |
| MSI MS-7B53            | 1         | 0.93%   |
| MSI MS-7A34            | 1         | 0.93%   |
| MSI MS-7885            | 1         | 0.93%   |
| MSI MS-1688            | 1         | 0.93%   |
| MSI Modern             | 1         | 0.93%   |
| Microsoft Surface      | 1         | 0.93%   |
| Lenovo Yoga            | 1         | 0.93%   |
| Lenovo V310-14ISK      | 1         | 0.93%   |
| Lenovo ThinkStation    | 1         | 0.93%   |
| Lenovo G50-30          | 1         | 0.93%   |
| IP3 Tech HeroBox       | 1         | 0.93%   |
| Intel D815EEA          | 1         | 0.93%   |
| Intel AHV              | 1         | 0.93%   |
| IBM ThinkPad           | 1         | 0.93%   |
| HP Z220                | 1         | 0.93%   |
| HP ProDesk             | 1         | 0.93%   |
| HP ProBook             | 1         | 0.93%   |
| HP Notebook            | 1         | 0.93%   |
| HP EliteDesk           | 1         | 0.93%   |
| HP Compaq              | 1         | 0.93%   |
| Google Panther         | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 14        | 13.08%  |
| 2012    | 12        | 11.21%  |
| 2019    | 10        | 9.35%   |
| 2017    | 8         | 7.48%   |
| 2014    | 7         | 6.54%   |
| 2013    | 7         | 6.54%   |
| 2011    | 7         | 6.54%   |
| 2010    | 7         | 6.54%   |
| 2016    | 5         | 4.67%   |
| 2009    | 5         | 4.67%   |
| 2021    | 4         | 3.74%   |
| 2015    | 4         | 3.74%   |
| 2008    | 4         | 3.74%   |
| 2020    | 3         | 2.8%    |
| 2006    | 3         | 2.8%    |
| 2007    | 2         | 1.87%   |
| 2005    | 2         | 1.87%   |
| 2022    | 1         | 0.93%   |
| 2000    | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 54        | 50.47%  |
| Desktop     | 45        | 42.06%  |
| Tablet      | 3         | 2.8%    |
| Mini pc     | 3         | 2.8%    |
| Convertible | 2         | 1.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 105       | 98.13%  |
| Enabled  | 2         | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 96.26%  |
| Yes  | 4         | 3.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 22.43%  |
| 4.01-8.0    | 22        | 20.56%  |
| 16.01-24.0  | 20        | 18.69%  |
| 3.01-4.0    | 17        | 15.89%  |
| 32.01-64.0  | 10        | 9.35%   |
| 1.01-2.0    | 6         | 5.61%   |
| 2.01-3.0    | 3         | 2.8%    |
| 0.01-0.5    | 3         | 2.8%    |
| 64.01-256.0 | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 45        | 38.79%  |
| 4.01-8.0   | 22        | 18.97%  |
| 2.01-3.0   | 18        | 15.52%  |
| 0.51-1.0   | 13        | 11.21%  |
| 3.01-4.0   | 8         | 6.9%    |
| 0.01-0.5   | 5         | 4.31%   |
| 8.01-16.0  | 4         | 3.45%   |
| 32.01-64.0 | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 60.19%  |
| 2      | 20        | 18.52%  |
| 3      | 12        | 11.11%  |
| 4      | 5         | 4.63%   |
| 5      | 4         | 3.7%    |
| 6      | 2         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 62.04%  |
| Yes       | 41        | 37.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 90.65%  |
| No        | 10        | 9.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 62.96%  |
| No        | 40        | 37.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 61.11%  |
| Yes       | 42        | 38.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 9.26%   |
| Russia      | 10        | 9.26%   |
| Germany     | 8         | 7.41%   |
| France      | 8         | 7.41%   |
| Ukraine     | 7         | 6.48%   |
| Brazil      | 7         | 6.48%   |
| UK          | 4         | 3.7%    |
| Slovakia    | 4         | 3.7%    |
| Poland      | 4         | 3.7%    |
| Netherlands | 4         | 3.7%    |
| Grenada     | 4         | 3.7%    |
| Spain       | 3         | 2.78%   |
| Australia   | 3         | 2.78%   |
| New Zealand | 2         | 1.85%   |
| Italy       | 2         | 1.85%   |
| Israel      | 2         | 1.85%   |
| Indonesia   | 2         | 1.85%   |
| Hungary     | 2         | 1.85%   |
| Finland     | 2         | 1.85%   |
| Belgium     | 2         | 1.85%   |
| Argentina   | 2         | 1.85%   |
| Vietnam     | 1         | 0.93%   |
| Switzerland | 1         | 0.93%   |
| South Korea | 1         | 0.93%   |
| Singapore   | 1         | 0.93%   |
| Serbia      | 1         | 0.93%   |
| Puerto Rico | 1         | 0.93%   |
| Portugal    | 1         | 0.93%   |
| Norway      | 1         | 0.93%   |
| Mexico      | 1         | 0.93%   |
| India       | 1         | 0.93%   |
| Greece      | 1         | 0.93%   |
| El Salvador | 1         | 0.93%   |
| Canada      | 1         | 0.93%   |
| Bulgaria    | 1         | 0.93%   |
| Belarus     | 1         | 0.93%   |
| Austria     | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Saint George's       | 4         | 3.7%    |
| Bratislava           | 4         | 3.7%    |
| Bagnolet             | 4         | 3.7%    |
| Wroclaw              | 2         | 1.85%   |
| Volzhskiy            | 2         | 1.85%   |
| Tel Aviv             | 2         | 1.85%   |
| Sydney               | 2         | 1.85%   |
| Sao Paulo            | 2         | 1.85%   |
| Rio de Janeiro       | 2         | 1.85%   |
| Nadudvar             | 2         | 1.85%   |
| Milan                | 2         | 1.85%   |
| Kyiv                 | 2         | 1.85%   |
| Auckland             | 2         | 1.85%   |
| Amsterdam            | 2         | 1.85%   |
| Yakutsk              | 1         | 0.93%   |
| Windisch             | 1         | 0.93%   |
| Wildberg             | 1         | 0.93%   |
| Vladikavkaz          | 1         | 0.93%   |
| Vise                 | 1         | 0.93%   |
| Trubchëvsk          | 1         | 0.93%   |
| Toronto              | 1         | 0.93%   |
| Thessaloniki         | 1         | 0.93%   |
| Tangerang            | 1         | 0.93%   |
| Talavera de la Reina | 1         | 0.93%   |
| Staunton             | 1         | 0.93%   |
| St Petersburg        | 1         | 0.93%   |
| Sofia                | 1         | 0.93%   |
| Singapore            | 1         | 0.93%   |
| Seongbuk-gu          | 1         | 0.93%   |
| San Salvador         | 1         | 0.93%   |
| Saint-Herblain       | 1         | 0.93%   |
| Reutlingen           | 1         | 0.93%   |
| Renkum               | 1         | 0.93%   |
| Praia Grande         | 1         | 0.93%   |
| Poperinge            | 1         | 0.93%   |
| Paris                | 1         | 0.93%   |
| Oslo                 | 1         | 0.93%   |
| Oleksandriya         | 1         | 0.93%   |
| Okehampton           | 1         | 0.93%   |
| Novopskov            | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 48     | 18.29%  |
| Seagate             | 21        | 29     | 12.8%   |
| Samsung Electronics | 15        | 23     | 9.15%   |
| Kingston            | 15        | 18     | 9.15%   |
| Unknown             | 8         | 10     | 4.88%   |
| Toshiba             | 8         | 8      | 4.88%   |
| Crucial             | 6         | 8      | 3.66%   |
| SanDisk             | 5         | 5      | 3.05%   |
| SK hynix            | 4         | 4      | 2.44%   |
| PNY                 | 4         | 4      | 2.44%   |
| Hitachi             | 4         | 4      | 2.44%   |
| HGST                | 4         | 4      | 2.44%   |
| Team                | 3         | 3      | 1.83%   |
| Netac               | 3         | 3      | 1.83%   |
| Fujitsu             | 3         | 3      | 1.83%   |
| Micron Technology   | 2         | 2      | 1.22%   |
| Maxtor              | 2         | 2      | 1.22%   |
| Hewlett-Packard     | 2         | 3      | 1.22%   |
| Dogfish             | 2         | 2      | 1.22%   |
| A-DATA Technology   | 2         | 2      | 1.22%   |
| WD MediaMax         | 1         | 3      | 0.61%   |
| Union Memory        | 1         | 2      | 0.61%   |
| UMIS                | 1         | 1      | 0.61%   |
| Transcend           | 1         | 2      | 0.61%   |
| Teclast             | 1         | 1      | 0.61%   |
| Smart               | 1         | 1      | 0.61%   |
| SABRENT             | 1         | 2      | 0.61%   |
| Patriot             | 1         | 1      | 0.61%   |
| Mushkin             | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| LITEON              | 1         | 4      | 0.61%   |
| Lenovo              | 1         | 1      | 0.61%   |
| Kston               | 1         | 1      | 0.61%   |
| KIOXIA              | 1         | 1      | 0.61%   |
| KingFast            | 1         | 1      | 0.61%   |
| KingDian            | 1         | 1      | 0.61%   |
| Intenso             | 1         | 1      | 0.61%   |
| Intel               | 1         | 1      | 0.61%   |
| IBM/Hitachi         | 1         | 1      | 0.61%   |
| HXY                 | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| PNY CS900 240GB SSD              | 4         | 2.17%   |
| Kingston SA400S37480G 480GB SSD  | 3         | 1.63%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.63%   |
| Kingston SA2000M8250G 250GB      | 3         | 1.63%   |
| WDC WD5000BPVT-24HXZT3 500GB     | 2         | 1.09%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 1.09%   |
| WDC WD10EARX-00N0YB0 1TB         | 2         | 1.09%   |
| Unknown MMC Card  128GB          | 2         | 1.09%   |
| Seagate ST3500418AS 500GB        | 2         | 1.09%   |
| Seagate ST2000DX002-2DV164 2TB   | 2         | 1.09%   |
| Samsung SSD 980 1TB              | 2         | 1.09%   |
| Samsung SSD 860 EVO 250GB        | 2         | 1.09%   |
| Samsung SSD 850 EVO 250GB        | 2         | 1.09%   |
| Kingston SA400S37960G 960GB SSD  | 2         | 1.09%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 1.09%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1         | 0.54%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 0.54%   |
| WDC WD800BB-00JHC0 80GB          | 1         | 0.54%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 0.54%   |
| WDC WD5001AALS-00L3B2 500GB      | 1         | 0.54%   |
| WDC WD5001AALS-00E3A0 500GB      | 1         | 0.54%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1         | 0.54%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1         | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1         | 0.54%   |
| WDC WD40EDAZ-11SLVB0 4TB         | 1         | 0.54%   |
| WDC WD3200BPVT-22JJ5T0 320GB     | 1         | 0.54%   |
| WDC WD3200BEVT-22A23T0 320GB     | 1         | 0.54%   |
| WDC WD3200BEVE-00A0HT0 320GB     | 1         | 0.54%   |
| WDC WD2500BEKT-00A25T0 250GB     | 1         | 0.54%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1         | 0.54%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1         | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1         | 0.54%   |
| WDC WD1200JS-55NCB1 120GB        | 1         | 0.54%   |
| WDC WD10SPZX-22Z10T1 1TB         | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB         | 1         | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.54%   |
| WDC WD10JFCX-68N6GN0 1TB         | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 42     | 37.68%  |
| Seagate             | 21        | 29     | 30.43%  |
| Toshiba             | 6         | 6      | 8.7%    |
| Hitachi             | 4         | 4      | 5.8%    |
| HGST                | 4         | 4      | 5.8%    |
| Fujitsu             | 3         | 3      | 4.35%   |
| Maxtor              | 2         | 2      | 2.9%    |
| Samsung Electronics | 1         | 1      | 1.45%   |
| IBM/Hitachi         | 1         | 1      | 1.45%   |
| Hewlett-Packard     | 1         | 2      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 14     | 18.46%  |
| Samsung Electronics | 10        | 11     | 15.38%  |
| SanDisk             | 4         | 4      | 6.15%   |
| PNY                 | 4         | 4      | 6.15%   |
| Crucial             | 4         | 5      | 6.15%   |
| WDC                 | 3         | 4      | 4.62%   |
| Team                | 3         | 3      | 4.62%   |
| Netac               | 3         | 3      | 4.62%   |
| SK hynix            | 2         | 2      | 3.08%   |
| Micron Technology   | 2         | 2      | 3.08%   |
| Dogfish             | 2         | 2      | 3.08%   |
| A-DATA Technology   | 2         | 2      | 3.08%   |
| Union Memory        | 1         | 2      | 1.54%   |
| Transcend           | 1         | 2      | 1.54%   |
| Teclast             | 1         | 1      | 1.54%   |
| Smart               | 1         | 1      | 1.54%   |
| Patriot             | 1         | 1      | 1.54%   |
| Mushkin             | 1         | 1      | 1.54%   |
| LITEONIT            | 1         | 1      | 1.54%   |
| LITEON              | 1         | 4      | 1.54%   |
| Kston               | 1         | 1      | 1.54%   |
| KingDian            | 1         | 1      | 1.54%   |
| Intenso             | 1         | 1      | 1.54%   |
| HXY                 | 1         | 1      | 1.54%   |
| Hewlett-Packard     | 1         | 1      | 1.54%   |
| GOODRAM             | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 57        | 75     | 39.04%  |
| HDD     | 57        | 94     | 39.04%  |
| NVMe    | 22        | 31     | 15.07%  |
| MMC     | 8         | 10     | 5.48%   |
| Unknown | 2         | 4      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 166    | 73.23%  |
| NVMe | 21        | 29     | 16.54%  |
| MMC  | 8         | 10     | 6.3%    |
| SAS  | 5         | 9      | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 101    | 64.6%   |
| 0.51-1.0   | 25        | 48     | 22.12%  |
| 1.01-2.0   | 9         | 14     | 7.96%   |
| 3.01-4.0   | 4         | 4      | 3.54%   |
| 4.01-10.0  | 2         | 2      | 1.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 21.24%  |
| 101-250        | 23        | 20.35%  |
| 1001-2000      | 15        | 13.27%  |
| 501-1000       | 15        | 13.27%  |
| 51-100         | 10        | 8.85%   |
| 21-50          | 8         | 7.08%   |
| More than 3000 | 6         | 5.31%   |
| Unknown        | 6         | 5.31%   |
| 2001-3000      | 3         | 2.65%   |
| 1-20           | 3         | 2.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 27.03%  |
| 101-250        | 25        | 22.52%  |
| 21-50          | 13        | 11.71%  |
| 51-100         | 11        | 9.91%   |
| 501-1000       | 8         | 7.21%   |
| 251-500        | 7         | 6.31%   |
| 1001-2000      | 7         | 6.31%   |
| Unknown        | 6         | 5.41%   |
| More than 3000 | 2         | 1.8%    |
| 2001-3000      | 2         | 1.8%    |

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
| Hitachi HDS721616PLA380 164GB     | 1         | 1      | 5.56%   |
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
| Works    | 82        | 147    | 65.08%  |
| Detected | 27        | 48     | 21.43%  |
| Malfunc  | 17        | 19     | 13.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 60.47%  |
| AMD                              | 19        | 14.73%  |
| Samsung Electronics              | 6         | 4.65%   |
| Kingston Technology Company      | 4         | 3.1%    |
| SanDisk                          | 3         | 2.33%   |
| Toshiba America Info Systems     | 2         | 1.55%   |
| SK hynix                         | 2         | 1.55%   |
| Micron/Crucial Technology        | 2         | 1.55%   |
| Marvell Technology Group         | 2         | 1.55%   |
| VIA Technologies                 | 1         | 0.78%   |
| Union Memory (Shenzhen)          | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Nvidia                           | 1         | 0.78%   |
| Lenovo                           | 1         | 0.78%   |
| KIOXIA                           | 1         | 0.78%   |
| Integrated Technology Express    | 1         | 0.78%   |
| Chelsio Communications           | 1         | 0.78%   |
| Broadcom / LSI                   | 1         | 0.78%   |
| ASMedia Technology               | 1         | 0.78%   |
| Adaptec                          | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 8.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 4.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 3.38%   |
| Kingston Company A2000 NVMe SSD                                                | 4         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.7%    |
| Intel SATA Controller [RAID mode]                                              | 4         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.7%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 2.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.03%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.35%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.35%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.35%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1         | 0.68%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.68%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.68%   |
| SK hynix BC511                                                                 | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.68%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 61.42%  |
| NVMe | 21        | 16.54%  |
| IDE  | 18        | 14.17%  |
| RAID | 8         | 6.3%    |
| SCSI | 2         | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 86        | 80.37%  |
| AMD    | 20        | 18.69%  |
| ARM    | 1         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.85%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.85%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.85%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.93%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.93%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.93%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.93%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.93%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.93%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.93%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.93%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.93%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.93%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.93%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.93%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.93%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.93%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.93%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.93%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.93%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.93%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 23.15%  |
| Intel Core i7           | 17        | 15.74%  |
| Intel Core i3           | 11        | 10.19%  |
| Intel Celeron           | 6         | 5.56%   |
| Intel Core 2 Duo        | 4         | 3.7%    |
| AMD Ryzen 5             | 4         | 3.7%    |
| Intel Xeon              | 3         | 2.78%   |
| Intel Pentium           | 3         | 2.78%   |
| Intel Core 2            | 3         | 2.78%   |
| AMD Ryzen 7             | 3         | 2.78%   |
| Other                   | 2         | 1.85%   |
| Intel Pentium M         | 2         | 1.85%   |
| Intel Pentium Dual-Core | 2         | 1.85%   |
| Intel Pentium Dual      | 2         | 1.85%   |
| Intel Core i9           | 2         | 1.85%   |
| Intel Atom              | 2         | 1.85%   |
| AMD Ryzen 3             | 2         | 1.85%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium Gold      | 1         | 0.93%   |
| Intel Pentium 4         | 1         | 0.93%   |
| Intel Core 2 Quad       | 1         | 0.93%   |
| Intel Celeron M         | 1         | 0.93%   |
| AMD Sempron             | 1         | 0.93%   |
| AMD Ryzen Threadripper  | 1         | 0.93%   |
| AMD FX                  | 1         | 0.93%   |
| AMD E2                  | 1         | 0.93%   |
| AMD E                   | 1         | 0.93%   |
| AMD Athlon II           | 1         | 0.93%   |
| AMD A8                  | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A4                  | 1         | 0.93%   |
| AMD A10                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 45.79%  |
| 4      | 33        | 30.84%  |
| 6      | 11        | 10.28%  |
| 1      | 8         | 7.48%   |
| 8      | 4         | 3.74%   |
| 12     | 1         | 0.93%   |
| 10     | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 54.21%  |
| 1      | 49        | 45.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 93.46%  |
| 32-bit         | 4         | 3.74%   |
| Unknown        | 3         | 2.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 22.73%  |
| 0x306c3    | 6         | 5.45%   |
| 0x306a9    | 6         | 5.45%   |
| 0x206a7    | 6         | 5.45%   |
| 0x906ea    | 5         | 4.55%   |
| 0x406e3    | 5         | 4.55%   |
| 0x1067a    | 5         | 4.55%   |
| 0x806ec    | 4         | 3.64%   |
| 0x706a1    | 3         | 2.73%   |
| 0x40651    | 3         | 2.73%   |
| 0x306d4    | 3         | 2.73%   |
| 0x6f6      | 2         | 1.82%   |
| 0x30678    | 2         | 1.82%   |
| 0x20655    | 2         | 1.82%   |
| 0x106e5    | 2         | 1.82%   |
| 0x08608103 | 2         | 1.82%   |
| 0xf49      | 1         | 0.91%   |
| 0xa0655    | 1         | 0.91%   |
| 0xa0653    | 1         | 0.91%   |
| 0x906ed    | 1         | 0.91%   |
| 0x906e9    | 1         | 0.91%   |
| 0x806ea    | 1         | 0.91%   |
| 0x706a8    | 1         | 0.91%   |
| 0x6fd      | 1         | 0.91%   |
| 0x6d8      | 1         | 0.91%   |
| 0x695      | 1         | 0.91%   |
| 0x686      | 1         | 0.91%   |
| 0x506e3    | 1         | 0.91%   |
| 0x406d8    | 1         | 0.91%   |
| 0x406c4    | 1         | 0.91%   |
| 0x306f2    | 1         | 0.91%   |
| 0x20652    | 1         | 0.91%   |
| 0x10676    | 1         | 0.91%   |
| 0x0a20120a | 1         | 0.91%   |
| 0x08701021 | 1         | 0.91%   |
| 0x08701013 | 1         | 0.91%   |
| 0x0800820d | 1         | 0.91%   |
| 0x08001138 | 1         | 0.91%   |
| 0x08001129 | 1         | 0.91%   |
| 0x07030105 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 13.08%  |
| Haswell       | 11        | 10.28%  |
| IvyBridge     | 9         | 8.41%   |
| Skylake       | 7         | 6.54%   |
| Penryn        | 7         | 6.54%   |
| SandyBridge   | 6         | 5.61%   |
| Westmere      | 5         | 4.67%   |
| Silvermont    | 5         | 4.67%   |
| P6            | 4         | 3.74%   |
| Goldmont plus | 4         | 3.74%   |
| Core          | 4         | 3.74%   |
| Broadwell     | 4         | 3.74%   |
| Zen           | 3         | 2.8%    |
| Nehalem       | 3         | 2.8%    |
| Unknown       | 3         | 2.8%    |
| Zen+          | 2         | 1.87%   |
| Zen 2         | 2         | 1.87%   |
| Piledriver    | 2         | 1.87%   |
| Excavator     | 2         | 1.87%   |
| CometLake     | 2         | 1.87%   |
| Bobcat        | 2         | 1.87%   |
| Zen 3         | 1         | 0.93%   |
| Puma          | 1         | 0.93%   |
| NetBurst      | 1         | 0.93%   |
| K8 Hammer     | 1         | 0.93%   |
| K10 Llano     | 1         | 0.93%   |
| K10           | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 54.7%   |
| AMD                              | 27        | 23.08%  |
| Nvidia                           | 25        | 21.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 4.88%   |
| Intel Core Processor Integrated Graphics Controller                         | 5         | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 4.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 3.25%   |
| Intel HD Graphics 5500                                                      | 4         | 3.25%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.63%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2         | 1.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.63%   |
| AMD Lucienne                                                                | 2         | 1.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.63%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1         | 0.81%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1         | 0.81%   |
| Nvidia GT218 [GeForce 310]                                                  | 1         | 0.81%   |
| Nvidia GP107M [GeForce MX150]                                               | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.81%   |
| Nvidia GM108M [GeForce 930M]                                                | 1         | 0.81%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.81%   |
| Nvidia GK106M [GeForce GTX 765M]                                            | 1         | 0.81%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.81%   |
| Nvidia GF108M [NVS 5400M]                                                   | 1         | 0.81%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 1         | 0.81%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.81%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1         | 0.81%   |
| Nvidia C79 [GeForce 9400]                                                   | 1         | 0.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 46.73%  |
| 1 x AMD        | 22        | 20.56%  |
| 1 x Nvidia     | 16        | 14.95%  |
| Intel + Nvidia | 9         | 8.41%   |
| Other          | 3         | 2.8%    |
| 2 x AMD        | 3         | 2.8%    |
| Intel + AMD    | 2         | 1.87%   |
| 2 x Intel      | 1         | 0.93%   |
| 1 x SiS        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 89        | 82.41%  |
| Proprietary | 13        | 12.04%  |
| Unknown     | 6         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 59.26%  |
| 0.01-0.5   | 16        | 14.81%  |
| 0.51-1.0   | 8         | 7.41%   |
| 3.01-4.0   | 7         | 6.48%   |
| 1.01-2.0   | 6         | 5.56%   |
| 7.01-8.0   | 3         | 2.78%   |
| 2.01-3.0   | 3         | 2.78%   |
| 5.01-6.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 15.04%  |
| LG Display              | 17        | 15.04%  |
| AU Optronics            | 12        | 10.62%  |
| Hewlett-Packard         | 8         | 7.08%   |
| Goldstar                | 6         | 5.31%   |
| Chimei Innolux          | 6         | 5.31%   |
| Philips                 | 4         | 3.54%   |
| Lenovo                  | 4         | 3.54%   |
| BOE                     | 4         | 3.54%   |
| AOC                     | 4         | 3.54%   |
| Iiyama                  | 3         | 2.65%   |
| Dell                    | 3         | 2.65%   |
| Acer                    | 3         | 2.65%   |
| Unknown                 | 2         | 1.77%   |
| PANDA                   | 2         | 1.77%   |
| Chi Mei Optoelectronics | 2         | 1.77%   |
| ___                     | 1         | 0.88%   |
| ViewSonic               | 1         | 0.88%   |
| Toshiba                 | 1         | 0.88%   |
| STD                     | 1         | 0.88%   |
| Sony                    | 1         | 0.88%   |
| MStar                   | 1         | 0.88%   |
| MSI                     | 1         | 0.88%   |
| InnoLux Display         | 1         | 0.88%   |
| InfoVision              | 1         | 0.88%   |
| HJW                     | 1         | 0.88%   |
| Hisense                 | 1         | 0.88%   |
| eMachines               | 1         | 0.88%   |
| Eizo                    | 1         | 0.88%   |
| CVT                     | 1         | 0.88%   |
| CHI                     | 1         | 0.88%   |
| Ancor Communications    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.71%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.71%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.71%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.85%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.85%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.85%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 0.85%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.85%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                      | 1         | 0.85%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                          | 1         | 0.85%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.85%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch      | 1         | 0.85%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.85%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.85%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.85%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.85%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.85%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.85%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 0.85%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 0.85%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 0.85%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 0.85%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                      | 1         | 0.85%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                  | 1         | 0.85%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 38.74%  |
| 1366x768 (WXGA)    | 31        | 27.93%  |
| 3840x2160 (4K)     | 8         | 7.21%   |
| 1440x900 (WXGA+)   | 5         | 4.5%    |
| 1280x1024 (SXGA)   | 5         | 4.5%    |
| 1600x900 (HD+)     | 3         | 2.7%    |
| 3440x1440          | 2         | 1.8%    |
| 1600x1200          | 2         | 1.8%    |
| 1280x800 (WXGA)    | 2         | 1.8%    |
| Unknown            | 2         | 1.8%    |
| 5760x1080          | 1         | 0.9%    |
| 3000x2000          | 1         | 0.9%    |
| 2736x1824          | 1         | 0.9%    |
| 2288x1287          | 1         | 0.9%    |
| 1920x1200 (WUXGA)  | 1         | 0.9%    |
| 1680x1050 (WSXGA+) | 1         | 0.9%    |
| 1360x768           | 1         | 0.9%    |
| 1024x768 (XGA)     | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 23.42%  |
| 21      | 15        | 13.51%  |
| 12      | 9         | 8.11%   |
| 14      | 8         | 7.21%   |
| 13      | 8         | 7.21%   |
| 24      | 6         | 5.41%   |
| 23      | 6         | 5.41%   |
| 27      | 5         | 4.5%    |
| 17      | 5         | 4.5%    |
| Unknown | 4         | 3.6%    |
| 31      | 3         | 2.7%    |
| 19      | 3         | 2.7%    |
| 18      | 3         | 2.7%    |
| 72      | 2         | 1.8%    |
| 34      | 2         | 1.8%    |
| 142     | 1         | 0.9%    |
| 54      | 1         | 0.9%    |
| 52      | 1         | 0.9%    |
| 40      | 1         | 0.9%    |
| 22      | 1         | 0.9%    |
| 11      | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 38        | 35.51%  |
| 401-500        | 18        | 16.82%  |
| 501-600        | 16        | 14.95%  |
| 201-300        | 15        | 14.02%  |
| 351-400        | 5         | 4.67%   |
| Unknown        | 4         | 3.74%   |
| 601-700        | 3         | 2.8%    |
| 701-800        | 2         | 1.87%   |
| 1501-2000      | 2         | 1.87%   |
| 1001-1500      | 2         | 1.87%   |
| More than 2000 | 1         | 0.93%   |
| 801-900        | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 76%     |
| 16/10   | 8         | 8%      |
| 4/3     | 4         | 4%      |
| 5/4     | 3         | 3%      |
| Unknown | 3         | 3%      |
| 3/2     | 2         | 2%      |
| 21/9    | 2         | 2%      |
| 6/5     | 1         | 1%      |
| 1.00    | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 22.02%  |
| 201-250        | 20        | 18.35%  |
| 81-90          | 11        | 10.09%  |
| 61-70          | 9         | 8.26%   |
| 151-200        | 9         | 8.26%   |
| More than 1000 | 5         | 4.59%   |
| 71-80          | 5         | 4.59%   |
| 351-500        | 5         | 4.59%   |
| 301-350        | 5         | 4.59%   |
| 141-150        | 4         | 3.67%   |
| Unknown        | 4         | 3.67%   |
| 121-130        | 2         | 1.83%   |
| 111-120        | 2         | 1.83%   |
| 51-60          | 1         | 0.92%   |
| 251-300        | 1         | 0.92%   |
| 131-140        | 1         | 0.92%   |
| 501-1000       | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 40        | 37.04%  |
| 51-100        | 31        | 28.7%   |
| 121-160       | 21        | 19.44%  |
| 1-50          | 5         | 4.63%   |
| 161-240       | 5         | 4.63%   |
| Unknown       | 4         | 3.7%    |
| More than 240 | 2         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 87        | 79.82%  |
| 2     | 14        | 12.84%  |
| 3     | 4         | 3.67%   |
| 0     | 4         | 3.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 33.55%  |
| Realtek Semiconductor            | 50        | 32.26%  |
| Qualcomm Atheros                 | 23        | 14.84%  |
| Ralink Technology                | 4         | 2.58%   |
| Marvell Technology Group         | 3         | 1.94%   |
| Broadcom                         | 3         | 1.94%   |
| TP-Link                          | 2         | 1.29%   |
| Sierra Wireless                  | 2         | 1.29%   |
| Samsung Electronics              | 2         | 1.29%   |
| NetGear                          | 2         | 1.29%   |
| MediaTek                         | 2         | 1.29%   |
| JMicron Technology               | 2         | 1.29%   |
| Broadcom Limited                 | 2         | 1.29%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.65%   |
| VIA Technologies                 | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Ralink                           | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| Chelsio Communications           | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 35        | 19.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 5.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 3.3%    |
| Intel Wireless 7260                                                     | 5         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.2%    |
| Intel Ethernet Connection I217-LM                                       | 4         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.65%   |
| Intel Wireless 7265                                                     | 3         | 1.65%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 1.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.65%   |
| Sierra Wireless EM7455                                                  | 2         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.1%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.1%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.1%    |
| Intel Wireless 8265 / 8275                                              | 2         | 1.1%    |
| Intel Wireless 8260                                                     | 2         | 1.1%    |
| Intel Ethernet Controller I225-V                                        | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.1%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.1%    |
| ZTE WCDMA MSM USB SCSI CD-ROM                                           | 1         | 0.55%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.55%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.55%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 25        | 34.72%  |
| Qualcomm Atheros         | 21        | 29.17%  |
| Realtek Semiconductor    | 9         | 12.5%   |
| Ralink Technology        | 4         | 5.56%   |
| Sierra Wireless          | 2         | 2.78%   |
| NetGear                  | 2         | 2.78%   |
| MediaTek                 | 2         | 2.78%   |
| Broadcom Limited         | 2         | 2.78%   |
| Broadcom                 | 2         | 2.78%   |
| TP-Link                  | 1         | 1.39%   |
| Ralink                   | 1         | 1.39%   |
| Marvell Technology Group | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 5         | 6.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 6.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.17%   |
| Intel Wireless 7265                                                     | 3         | 4.17%   |
| Sierra Wireless EM7455                                                  | 2         | 2.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.78%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.78%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.78%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 2.78%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.78%   |
| Intel Wireless 8260                                                     | 2         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.39%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.39%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.39%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.39%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.39%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.39%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.39%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.39%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.39%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.39%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 42.86%  |
| Intel                            | 43        | 40.95%  |
| Qualcomm Atheros                 | 4         | 3.81%   |
| Samsung Electronics              | 2         | 1.9%    |
| Marvell Technology Group         | 2         | 1.9%    |
| JMicron Technology               | 2         | 1.9%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.95%   |
| VIA Technologies                 | 1         | 0.95%   |
| TP-Link                          | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |
| Nvidia                           | 1         | 0.95%   |
| Chelsio Communications           | 1         | 0.95%   |
| Broadcom                         | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 32.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.61%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 2.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.87%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.87%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 0.93%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.93%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 57.74%  |
| WiFi     | 68        | 40.48%  |
| Modem    | 3         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 58        | 52.73%  |
| WiFi     | 52        | 47.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 54.63%  |
| 1     | 42        | 38.89%  |
| 0     | 4         | 3.7%    |
| 7     | 1         | 0.93%   |
| 5     | 1         | 0.93%   |
| 3     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 89.72%  |
| Yes  | 11        | 10.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 34.88%  |
| Qualcomm Atheros Communications | 6         | 13.95%  |
| Realtek Semiconductor           | 4         | 9.3%    |
| Broadcom                        | 4         | 9.3%    |
| Lite-On Technology              | 2         | 4.65%   |
| IMC Networks                    | 2         | 4.65%   |
| Dell                            | 2         | 4.65%   |
| Cambridge Silicon Radio         | 2         | 4.65%   |
| Ralink                          | 1         | 2.33%   |
| Marvell Semiconductor           | 1         | 2.33%   |
| Foxconn International           | 1         | 2.33%   |
| Foxconn / Hon Hai               | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |
| Apple                           | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 23.26%  |
| Realtek Bluetooth Radio                             | 4         | 9.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4.65%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 4.65%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.33%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| Intel AX201 Bluetooth                               | 1         | 2.33%   |
| IMC Networks Bluetooth Device                       | 1         | 2.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.33%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2.33%   |
| Foxconn / Hon Hai BT                                | 1         | 2.33%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 80        | 56.74%  |
| AMD                              | 23        | 16.31%  |
| Nvidia                           | 19        | 13.48%  |
| Creative Labs                    | 3         | 2.13%   |
| Plantronics                      | 2         | 1.42%   |
| Texas Instruments                | 1         | 0.71%   |
| TEAC                             | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |
| Realtek Semiconductor            | 1         | 0.71%   |
| M-Audio                          | 1         | 0.71%   |
| Logitech                         | 1         | 0.71%   |
| KORG                             | 1         | 0.71%   |
| GYROCOM C&C                      | 1         | 0.71%   |
| Elite Silicon                    | 1         | 0.71%   |
| DCMT Technology                  | 1         | 0.71%   |
| Cirrus Logic                     | 1         | 0.71%   |
| C-Media Electronics              | 1         | 0.71%   |
| Blue Microphones                 | 1         | 0.71%   |
| ASUSTek Computer                 | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 5.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.71%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.35%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.76%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.76%   |
| Plantronics HD1                                                            | 2         | 1.18%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.18%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.18%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.18%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.59%   |
| TEAC US-1800                                                               | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 20.95%  |
| Unknown             | 20        | 19.05%  |
| SK hynix            | 12        | 11.43%  |
| Kingston            | 12        | 11.43%  |
| Corsair             | 7         | 6.67%   |
| Micron Technology   | 6         | 5.71%   |
| G.Skill             | 5         | 4.76%   |
| Crucial             | 5         | 4.76%   |
| A-DATA Technology   | 5         | 4.76%   |
| Nanya Technology    | 3         | 2.86%   |
| Unknown (ABCD)      | 2         | 1.9%    |
| Team                | 1         | 0.95%   |
| Smart               | 1         | 0.95%   |
| Ramaxel Technology  | 1         | 0.95%   |
| GOODRAM             | 1         | 0.95%   |
| Avant               | 1         | 0.95%   |
| Apacer              | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 2.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.65%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.65%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.65%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s            | 2         | 1.65%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.83%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.83%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 0.83%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s               | 1         | 0.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.83%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 0.83%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 0.83%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s                  | 1         | 0.83%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 44.09%  |
| DDR4    | 32        | 34.41%  |
| SDRAM   | 4         | 4.3%    |
| DDR     | 4         | 4.3%    |
| LPDDR3  | 3         | 3.23%   |
| DDR2    | 3         | 3.23%   |
| Unknown | 3         | 3.23%   |
| LPDDR4  | 2         | 2.15%   |
| DRAM    | 1         | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 53.85%  |
| DIMM         | 39        | 42.86%  |
| Row Of Chips | 3         | 3.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 35.51%  |
| 4096  | 28        | 26.17%  |
| 2048  | 16        | 14.95%  |
| 16384 | 14        | 13.08%  |
| 1024  | 5         | 4.67%   |
| 32768 | 2         | 1.87%   |
| 512   | 1         | 0.93%   |
| 256   | 1         | 0.93%   |
| 128   | 1         | 0.93%   |
| 64    | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 25        | 25.25%  |
| 2667    | 16        | 16.16%  |
| 2400    | 10        | 10.1%   |
| 1333    | 8         | 8.08%   |
| Unknown | 7         | 7.07%   |
| 3200    | 5         | 5.05%   |
| 2133    | 4         | 4.04%   |
| 1067    | 4         | 4.04%   |
| 3600    | 3         | 3.03%   |
| 4199    | 2         | 2.02%   |
| 1867    | 2         | 2.02%   |
| 1800    | 2         | 2.02%   |
| 800     | 2         | 2.02%   |
| 667     | 2         | 2.02%   |
| 3400    | 1         | 1.01%   |
| 2666    | 1         | 1.01%   |
| 1334    | 1         | 1.01%   |
| 1200    | 1         | 1.01%   |
| 1066    | 1         | 1.01%   |
| 400     | 1         | 1.01%   |
| 100     | 1         | 1.01%   |

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
| Chicony Electronics                    | 20        | 35.09%  |
| Microdia                               | 5         | 8.77%   |
| Sunplus Innovation Technology          | 4         | 7.02%   |
| Acer                                   | 4         | 7.02%   |
| Realtek Semiconductor                  | 3         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.26%   |
| Suyin                                  | 2         | 3.51%   |
| Logitech                               | 2         | 3.51%   |
| KYE Systems (Mouse Systems)            | 2         | 3.51%   |
| Cubeternet                             | 2         | 3.51%   |
| Z-Star Microelectronics                | 1         | 1.75%   |
| Softkinetic                            | 1         | 1.75%   |
| Samsung Electronics                    | 1         | 1.75%   |
| Quanta                                 | 1         | 1.75%   |
| Mustek Systems                         | 1         | 1.75%   |
| Microsoft                              | 1         | 1.75%   |
| MacroSilicon                           | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| IMC Networks                           | 1         | 1.75%   |
| GEMBIRD                                | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 8         | 14.04%  |
| Cubeternet GL-UPC822 UVC WebCam            | 2         | 3.51%   |
| Chicony HD Webcam                          | 2         | 3.51%   |
| Chicony EasyCamera                         | 2         | 3.51%   |
| Acer BisonCam, NB Pro                      | 2         | 3.51%   |
| Z-Star Vimicro USB Camera (Altair)         | 1         | 1.75%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 1         | 1.75%   |
| Sunplus Laptop Integrated Webcam HD        | 1         | 1.75%   |
| Sunplus Integrated_Webcam_HD               | 1         | 1.75%   |
| Sunplus FHD Camera Microphone              | 1         | 1.75%   |
| Sunplus Asus Webcam                        | 1         | 1.75%   |
| Softkinetic DepthSense 325                 | 1         | 1.75%   |
| Samsung Galaxy series, misc. (MTP mode)    | 1         | 1.75%   |
| Realtek Lenovo EasyCamera                  | 1         | 1.75%   |
| Realtek Integrated Webcam_HD               | 1         | 1.75%   |
| Realtek HD 720P Webcam                     | 1         | 1.75%   |
| Quanta Sony Visual Communication Camera    | 1         | 1.75%   |
| Mustek Systems USB 2.0 PC Camera           | 1         | 1.75%   |
| Microsoft LifeCam Studio                   | 1         | 1.75%   |
| Microdia WebCam SC-13HDL12639P             | 1         | 1.75%   |
| Microdia Sonix USB 2.0 Camera              | 1         | 1.75%   |
| Microdia Dell Integrated HD Webcam         | 1         | 1.75%   |
| Microdia Camera                            | 1         | 1.75%   |
| Microdia 1.3 MPixel Integrated Webcam      | 1         | 1.75%   |
| MacroSilicon USB Video                     | 1         | 1.75%   |
| Logitech Webcam C270                       | 1         | 1.75%   |
| Logitech HD Pro Webcam C920                | 1         | 1.75%   |
| Lite-On HP Wide Vision HD Camera           | 1         | 1.75%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1         | 1.75%   |
| KYE Systems (Mouse Systems) FaceCam 1000X  | 1         | 1.75%   |
| IMC Networks Integrated Webcam             | 1         | 1.75%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1         | 1.75%   |
| Chicony WebCam                             | 1         | 1.75%   |
| Chicony VGA WebCam                         | 1         | 1.75%   |
| Chicony TOSHIBA Web Camera - FHD           | 1         | 1.75%   |
| Chicony Thinkpad T430 camera               | 1         | 1.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 1         | 1.75%   |
| Chicony Lenovo EasyCamera                  | 1         | 1.75%   |
| Chicony HP TrueVision HD                   | 1         | 1.75%   |

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
| Broadcom    | 7         | 70%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 73.39%  |
| 1     | 18        | 16.51%  |
| 2     | 8         | 7.34%   |
| 3     | 2         | 1.83%   |
| 5     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 20.59%  |
| Chipcard                 | 7         | 20.59%  |
| Fingerprint reader       | 4         | 11.76%  |
| Communication controller | 4         | 11.76%  |
| Net/wireless             | 3         | 8.82%   |
| Multimedia controller    | 2         | 5.88%   |
| Camera                   | 2         | 5.88%   |
| Bluetooth                | 2         | 5.88%   |
| Unassigned class         | 1         | 2.94%   |
| Net/ethernet             | 1         | 2.94%   |
| Firewire controller      | 1         | 2.94%   |


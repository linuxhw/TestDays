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

Total: 164

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | G5 5505                     | Notebook    | [2552b456b6](https://linux-hardware.org/?probe=2552b456b6) | Mar 29, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [98ba3a9ce6](https://linux-hardware.org/?probe=98ba3a9ce6) | Mar 25, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [f22446cb1d](https://linux-hardware.org/?probe=f22446cb1d) | Mar 16, 2023 |
| Google        | Bluebird                    | Notebook    | [2d18088551](https://linux-hardware.org/?probe=2d18088551) | Mar 15, 2023 |
| Dell          | Latitude E6230              | Notebook    | [49a9844be8](https://linux-hardware.org/?probe=49a9844be8) | Mar 15, 2023 |
| AMI           | Intel                       | Desktop     | [c2c28fa7e4](https://linux-hardware.org/?probe=c2c28fa7e4) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [60cd9db1c5](https://linux-hardware.org/?probe=60cd9db1c5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| MSI           | A320M PRO-E                 | Desktop     | [3e441c86f1](https://linux-hardware.org/?probe=3e441c86f1) | Feb 20, 2023 |
| HP            | 829A                        | Mini pc     | [8791cd83c7](https://linux-hardware.org/?probe=8791cd83c7) | Feb 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| MSI           | H67MS-E43                   | Desktop     | [47a6655b3b](https://linux-hardware.org/?probe=47a6655b3b) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [63ea9a161f](https://linux-hardware.org/?probe=63ea9a161f) | Jan 31, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [f4349052b8](https://linux-hardware.org/?probe=f4349052b8) | Jan 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [beeeff23a5](https://linux-hardware.org/?probe=beeeff23a5) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
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
| Devuan 4                | 60        | 44.12%  |
| Devuan 3                | 30        | 22.06%  |
| Devuan 5                | 18        | 13.24%  |
| Devuan Testing/unstable | 15        | 11.03%  |
| Devuan 2.1              | 7         | 5.15%   |
| Devuan                  | 3         | 2.21%   |
| Devuan 3.0              | 1         | 0.74%   |
| Devuan 2.0              | 1         | 0.74%   |
| Devuan 1.0.0            | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 128       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-9-amd64        | 10        | 6.99%   |
| 5.10.0-8-amd64        | 7         | 4.9%    |
| 5.10.0-21-amd64       | 6         | 4.2%    |
| 5.10.0-16-amd64       | 6         | 4.2%    |
| 4.19.0-9-amd64        | 6         | 4.2%    |
| 4.19.0-14-amd64       | 6         | 4.2%    |
| 4.19.0-16-amd64       | 5         | 3.5%    |
| 5.10.0-19-amd64       | 4         | 2.8%    |
| 5.10.0-18-amd64       | 4         | 2.8%    |
| 5.10.0-13-amd64       | 4         | 2.8%    |
| 5.10.0-11-amd64       | 4         | 2.8%    |
| 5.10.0-10-amd64       | 4         | 2.8%    |
| 6.1.0-6-amd64         | 3         | 2.1%    |
| 5.7.0-2-amd64         | 3         | 2.1%    |
| 5.10.0-20-amd64       | 3         | 2.1%    |
| 4.19.0-12-amd64       | 3         | 2.1%    |
| 6.0.0-5-amd64         | 2         | 1.4%    |
| 5.7.0-0.bpo.2-amd64   | 2         | 1.4%    |
| 5.18.0-2-amd64        | 2         | 1.4%    |
| 5.18.0-1-amd64        | 2         | 1.4%    |
| 5.15.0-2-amd64        | 2         | 1.4%    |
| 5.10.0-6-amd64        | 2         | 1.4%    |
| 5.10.0-15-amd64       | 2         | 1.4%    |
| 5.10.0-14-amd64       | 2         | 1.4%    |
| 4.19.0-17-amd64       | 2         | 1.4%    |
| 4.19.0-13-amd64       | 2         | 1.4%    |
| 4.19.0-10-amd64       | 2         | 1.4%    |
| 6.1.0-2-amd64         | 1         | 0.7%    |
| 6.1.0-0.deb11.5-amd64 | 1         | 0.7%    |
| 6.0.0-2-amd64         | 1         | 0.7%    |
| 6.0.0-0.deb11.6-amd64 | 1         | 0.7%    |
| 5.9.0-4-amd64         | 1         | 0.7%    |
| 5.9.0-1-amd64         | 1         | 0.7%    |
| 5.8.0-3-amd64         | 1         | 0.7%    |
| 5.8.0-1-amd64         | 1         | 0.7%    |
| 5.7.19-server1        | 1         | 0.7%    |
| 5.7.0-1-amd64         | 1         | 0.7%    |
| 5.6.0-2-amd64         | 1         | 0.7%    |
| 5.19.0-2-amd64        | 1         | 0.7%    |
| 5.18.14-devuan        | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 58        | 42.65%  |
| 4.19.0   | 28        | 20.59%  |
| 4.9.0    | 8         | 5.88%   |
| 5.7.0    | 6         | 4.41%   |
| 6.1.0    | 5         | 3.68%   |
| 6.0.0    | 4         | 2.94%   |
| 5.18.0   | 4         | 2.94%   |
| 5.15.0   | 3         | 2.21%   |
| 5.9.0    | 2         | 1.47%   |
| 5.8.0    | 2         | 1.47%   |
| 5.14.0   | 2         | 1.47%   |
| 5.7.19   | 1         | 0.74%   |
| 5.6.0    | 1         | 0.74%   |
| 5.19.0   | 1         | 0.74%   |
| 5.18.14  | 1         | 0.74%   |
| 5.18.11  | 1         | 0.74%   |
| 5.16.0   | 1         | 0.74%   |
| 5.15.5   | 1         | 0.74%   |
| 5.11.0   | 1         | 0.74%   |
| 5.10.162 | 1         | 0.74%   |
| 5.1.21   | 1         | 0.74%   |
| 5.0.7    | 1         | 0.74%   |
| 4.4.195  | 1         | 0.74%   |
| 4.19.112 | 1         | 0.74%   |
| 4.18.0   | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 59        | 43.38%  |
| 4.19    | 29        | 21.32%  |
| 4.9     | 8         | 5.88%   |
| 5.7     | 7         | 5.15%   |
| 5.18    | 6         | 4.41%   |
| 6.1     | 5         | 3.68%   |
| 6.0     | 4         | 2.94%   |
| 5.15    | 4         | 2.94%   |
| 5.9     | 2         | 1.47%   |
| 5.8     | 2         | 1.47%   |
| 5.14    | 2         | 1.47%   |
| 5.6     | 1         | 0.74%   |
| 5.19    | 1         | 0.74%   |
| 5.16    | 1         | 0.74%   |
| 5.11    | 1         | 0.74%   |
| 5.1     | 1         | 0.74%   |
| 5.0     | 1         | 0.74%   |
| 4.4     | 1         | 0.74%   |
| 4.18    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 94.53%  |
| i686   | 6         | 4.69%   |
| armv7l | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 55        | 40.74%  |
| KDE5       | 19        | 14.07%  |
| Unknown    | 19        | 14.07%  |
| MATE       | 18        | 13.33%  |
| i3         | 7         | 5.19%   |
| LXDE       | 6         | 4.44%   |
| GNOME      | 3         | 2.22%   |
| Cinnamon   | 3         | 2.22%   |
| LXQt       | 2         | 1.48%   |
| X-Cinnamon | 1         | 0.74%   |
| Openbox    | 1         | 0.74%   |
| awesome    | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 117       | 90%     |
| Tty     | 10        | 7.69%   |
| Unknown | 3         | 2.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 49        | 37.12%  |
| LightDM | 35        | 26.52%  |
| Unknown | 32        | 24.24%  |
| SDDM    | 9         | 6.82%   |
| XDM     | 2         | 1.52%   |
| NODM    | 2         | 1.52%   |
| GDM3    | 2         | 1.52%   |
| LXDM    | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 47        | 35.88%  |
| en_GB       | 21        | 16.03%  |
| ru_RU       | 11        | 8.4%    |
| Unknown     | 7         | 5.34%   |
| C           | 6         | 4.58%   |
| pt_BR       | 5         | 3.82%   |
| fr_FR       | 4         | 3.05%   |
| es_ES       | 4         | 3.05%   |
| sk_SK       | 3         | 2.29%   |
| fr_BE       | 3         | 2.29%   |
| en_AU       | 3         | 2.29%   |
| pl_PL       | 2         | 1.53%   |
| it_IT       | 2         | 1.53%   |
| en_NZ       | 2         | 1.53%   |
| de_DE       | 2         | 1.53%   |
| de_AT       | 2         | 1.53%   |
| ru_UA       | 1         | 0.76%   |
| es_SV       | 1         | 0.76%   |
| es_MX       | 1         | 0.76%   |
| en_US.utf-8 | 1         | 0.76%   |
| en_SG       | 1         | 0.76%   |
| en_CA       | 1         | 0.76%   |
| de_CH       | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 72        | 55.81%  |
| EFI  | 57        | 44.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 109       | 85.16%  |
| Btrfs   | 7         | 5.47%   |
| Unknown | 5         | 3.91%   |
| Xfs     | 2         | 1.56%   |
| Overlay | 2         | 1.56%   |
| OveXlay | 1         | 0.78%   |
| Ext3    | 1         | 0.78%   |
| Ext2    | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 71        | 53.38%  |
| MBR     | 49        | 36.84%  |
| Unknown | 13        | 9.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 79.23%  |
| Yes       | 27        | 20.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 76.74%  |
| Yes       | 30        | 23.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 17.19%  |
| Dell                | 20        | 15.63%  |
| ASUSTek Computer    | 15        | 11.72%  |
| Hewlett-Packard     | 14        | 10.94%  |
| Gigabyte Technology | 12        | 9.38%   |
| MSI                 | 8         | 6.25%   |
| Acer                | 6         | 4.69%   |
| ASRock              | 4         | 3.13%   |
| Toshiba             | 3         | 2.34%   |
| Intel               | 2         | 1.56%   |
| Google              | 2         | 1.56%   |
| Fujitsu Siemens     | 2         | 1.56%   |
| AMI                 | 2         | 1.56%   |
| Teclast             | 1         | 0.78%   |
| Sun Microsystems    | 1         | 0.78%   |
| Sony                | 1         | 0.78%   |
| Samsung Electronics | 1         | 0.78%   |
| Online Labs         | 1         | 0.78%   |
| Notebook            | 1         | 0.78%   |
| Nokia               | 1         | 0.78%   |
| MTC                 | 1         | 0.78%   |
| Microsoft           | 1         | 0.78%   |
| IP3 Tech            | 1         | 0.78%   |
| IBM                 | 1         | 0.78%   |
| Fujitsu             | 1         | 0.78%   |
| Chuwi               | 1         | 0.78%   |
| CCE                 | 1         | 0.78%   |
| Apple               | 1         | 0.78%   |
| Unknown             | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.78%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.78%   |
| Toshiba Satellite L655                                                                   | 1         | 0.78%   |
| Teclast F6 Plus                                                                          | 1         | 0.78%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.78%   |
| Sony VPCEE23FX                                                                           | 1         | 0.78%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.78%   |
| Online Labs SR                                                                           | 1         | 0.78%   |
| Notebook W230ST                                                                          | 1         | 0.78%   |
| Nokia N900                                                                               | 1         | 0.78%   |
| MTC Montara-GML                                                                          | 1         | 0.78%   |
| MSI MS-7B84                                                                              | 1         | 0.78%   |
| MSI MS-7B53                                                                              | 1         | 0.78%   |
| MSI MS-7A36                                                                              | 1         | 0.78%   |
| MSI MS-7A34                                                                              | 1         | 0.78%   |
| MSI MS-7885                                                                              | 1         | 0.78%   |
| MSI MS-7678                                                                              | 1         | 0.78%   |
| MSI MS-1688                                                                              | 1         | 0.78%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.78%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.78%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.78%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.78%   |
| Lenovo ThinkStation P330 Tiny 30CES09U00                                                 | 1         | 0.78%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.78%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.78%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 0.78%   |
| Lenovo ThinkPad T560 20FJS1J200                                                          | 1         | 0.78%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 0.78%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 0.78%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 0.78%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 0.78%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 0.78%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 0.78%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 10.94%  |
| Dell Latitude          | 9         | 7.03%   |
| Acer Aspire            | 5         | 3.91%   |
| Dell OptiPlex          | 4         | 3.13%   |
| Toshiba Satellite      | 3         | 2.34%   |
| Lenovo IdeaPad         | 3         | 2.34%   |
| HP Laptop              | 3         | 2.34%   |
| ASUS PRIME             | 3         | 2.34%   |
| Lenovo ThinkStation    | 2         | 1.56%   |
| HP ProBook             | 2         | 1.56%   |
| HP Pavilion            | 2         | 1.56%   |
| HP EliteDesk           | 2         | 1.56%   |
| Dell Inspiron          | 2         | 1.56%   |
| ASUS ROG               | 2         | 1.56%   |
| Teclast F6             | 1         | 0.78%   |
| Sun Microsystems Ultra | 1         | 0.78%   |
| Sony VPCEE23FX         | 1         | 0.78%   |
| Samsung 355V4C         | 1         | 0.78%   |
| Online Labs SR         | 1         | 0.78%   |
| Notebook W230ST        | 1         | 0.78%   |
| Nokia N900             | 1         | 0.78%   |
| MTC Montara-GML        | 1         | 0.78%   |
| MSI MS-7B84            | 1         | 0.78%   |
| MSI MS-7B53            | 1         | 0.78%   |
| MSI MS-7A36            | 1         | 0.78%   |
| MSI MS-7A34            | 1         | 0.78%   |
| MSI MS-7885            | 1         | 0.78%   |
| MSI MS-7678            | 1         | 0.78%   |
| MSI MS-1688            | 1         | 0.78%   |
| MSI Modern             | 1         | 0.78%   |
| Microsoft Surface      | 1         | 0.78%   |
| Lenovo Yoga            | 1         | 0.78%   |
| Lenovo V310-14ISK      | 1         | 0.78%   |
| Lenovo G50-30          | 1         | 0.78%   |
| IP3 Tech HeroBox       | 1         | 0.78%   |
| Intel D815EEA          | 1         | 0.78%   |
| Intel AHV              | 1         | 0.78%   |
| IBM ThinkPad           | 1         | 0.78%   |
| HP Z220                | 1         | 0.78%   |
| HP ProDesk             | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 17        | 13.28%  |
| 2012    | 13        | 10.16%  |
| 2019    | 11        | 8.59%   |
| 2013    | 10        | 7.81%   |
| 2011    | 9         | 7.03%   |
| 2017    | 8         | 6.25%   |
| 2014    | 8         | 6.25%   |
| 2016    | 7         | 5.47%   |
| 2010    | 7         | 5.47%   |
| 2021    | 6         | 4.69%   |
| 2020    | 6         | 4.69%   |
| 2009    | 5         | 3.91%   |
| 2015    | 4         | 3.13%   |
| 2008    | 4         | 3.13%   |
| 2022    | 3         | 2.34%   |
| 2006    | 3         | 2.34%   |
| 2007    | 2         | 1.56%   |
| 2005    | 2         | 1.56%   |
| 2023    | 1         | 0.78%   |
| 2000    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 67        | 52.34%  |
| Desktop     | 50        | 39.06%  |
| Mini pc     | 5         | 3.91%   |
| Tablet      | 3         | 2.34%   |
| Convertible | 2         | 1.56%   |
| Server      | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 126       | 98.44%  |
| Enabled  | 2         | 1.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 96.09%  |
| Yes  | 5         | 3.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 22.66%  |
| 16.01-24.0  | 28        | 21.88%  |
| 4.01-8.0    | 27        | 21.09%  |
| 3.01-4.0    | 18        | 14.06%  |
| 32.01-64.0  | 11        | 8.59%   |
| 1.01-2.0    | 6         | 4.69%   |
| 2.01-3.0    | 3         | 2.34%   |
| 0.01-0.5    | 3         | 2.34%   |
| 64.01-256.0 | 2         | 1.56%   |
| 24.01-32.0  | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 51        | 36.96%  |
| 4.01-8.0   | 27        | 19.57%  |
| 2.01-3.0   | 19        | 13.77%  |
| 0.51-1.0   | 15        | 10.87%  |
| 3.01-4.0   | 14        | 10.14%  |
| 8.01-16.0  | 6         | 4.35%   |
| 0.01-0.5   | 5         | 3.62%   |
| 32.01-64.0 | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 81        | 62.79%  |
| 2      | 24        | 18.6%   |
| 3      | 13        | 10.08%  |
| 4      | 5         | 3.88%   |
| 5      | 4         | 3.1%    |
| 6      | 2         | 1.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 63.57%  |
| Yes       | 47        | 36.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 90.63%  |
| No        | 12        | 9.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 64.62%  |
| No        | 46        | 35.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 56.15%  |
| Yes       | 57        | 43.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 12.4%   |
| Russia      | 11        | 8.53%   |
| Germany     | 10        | 7.75%   |
| France      | 9         | 6.98%   |
| Ukraine     | 7         | 5.43%   |
| Brazil      | 7         | 5.43%   |
| UK          | 5         | 3.88%   |
| Slovakia    | 5         | 3.88%   |
| Poland      | 4         | 3.1%    |
| Netherlands | 4         | 3.1%    |
| Grenada     | 4         | 3.1%    |
| Spain       | 3         | 2.33%   |
| Italy       | 3         | 2.33%   |
| Australia   | 3         | 2.33%   |
| Switzerland | 2         | 1.55%   |
| Portugal    | 2         | 1.55%   |
| New Zealand | 2         | 1.55%   |
| Mexico      | 2         | 1.55%   |
| Israel      | 2         | 1.55%   |
| Indonesia   | 2         | 1.55%   |
| Hungary     | 2         | 1.55%   |
| Georgia     | 2         | 1.55%   |
| Finland     | 2         | 1.55%   |
| Belgium     | 2         | 1.55%   |
| Austria     | 2         | 1.55%   |
| Argentina   | 2         | 1.55%   |
| Vietnam     | 1         | 0.78%   |
| South Korea | 1         | 0.78%   |
| Singapore   | 1         | 0.78%   |
| Serbia      | 1         | 0.78%   |
| Romania     | 1         | 0.78%   |
| Puerto Rico | 1         | 0.78%   |
| Norway      | 1         | 0.78%   |
| India       | 1         | 0.78%   |
| Greece      | 1         | 0.78%   |
| El Salvador | 1         | 0.78%   |
| China       | 1         | 0.78%   |
| Canada      | 1         | 0.78%   |
| Bulgaria    | 1         | 0.78%   |
| Belarus     | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Bratislava           | 5         | 3.85%   |
| Bagnolet             | 5         | 3.85%   |
| Saint George's       | 4         | 3.08%   |
| Wroclaw              | 2         | 1.54%   |
| Volzhskiy            | 2         | 1.54%   |
| Tel Aviv             | 2         | 1.54%   |
| Tbilisi              | 2         | 1.54%   |
| Sydney               | 2         | 1.54%   |
| Sao Paulo            | 2         | 1.54%   |
| Rio de Janeiro       | 2         | 1.54%   |
| Nadudvar             | 2         | 1.54%   |
| Milan                | 2         | 1.54%   |
| Kyiv                 | 2         | 1.54%   |
| Auckland             | 2         | 1.54%   |
| Amsterdam            | 2         | 1.54%   |
| Yakutsk              | 1         | 0.77%   |
| Xiamen               | 1         | 0.77%   |
| Wulkaprodersdorf     | 1         | 0.77%   |
| Windisch             | 1         | 0.77%   |
| Willich              | 1         | 0.77%   |
| Wildberg             | 1         | 0.77%   |
| Vladikavkaz          | 1         | 0.77%   |
| Vise                 | 1         | 0.77%   |
| Vandergrift          | 1         | 0.77%   |
| Trubchëvsk          | 1         | 0.77%   |
| Toronto              | 1         | 0.77%   |
| Thessaloniki         | 1         | 0.77%   |
| Tangerang            | 1         | 0.77%   |
| Talavera de la Reina | 1         | 0.77%   |
| Swannanoa            | 1         | 0.77%   |
| Sunderland           | 1         | 0.77%   |
| Staunton             | 1         | 0.77%   |
| St Petersburg        | 1         | 0.77%   |
| Sofia                | 1         | 0.77%   |
| Singapore            | 1         | 0.77%   |
| Siena                | 1         | 0.77%   |
| Seongbuk-gu          | 1         | 0.77%   |
| San Salvador         | 1         | 0.77%   |
| Saint-Herblain       | 1         | 0.77%   |
| Saint Andrew         | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 52     | 17.37%  |
| Seagate             | 22        | 30     | 11.58%  |
| Samsung Electronics | 20        | 29     | 10.53%  |
| Kingston            | 15        | 18     | 7.89%   |
| Unknown             | 11        | 13     | 5.79%   |
| Toshiba             | 9         | 9      | 4.74%   |
| Crucial             | 8         | 10     | 4.21%   |
| SanDisk             | 7         | 7      | 3.68%   |
| SK hynix            | 5         | 5      | 2.63%   |
| PNY                 | 5         | 6      | 2.63%   |
| Hitachi             | 5         | 5      | 2.63%   |
| HGST                | 4         | 4      | 2.11%   |
| Team                | 3         | 3      | 1.58%   |
| Netac               | 3         | 3      | 1.58%   |
| Fujitsu             | 3         | 3      | 1.58%   |
| Micron Technology   | 2         | 2      | 1.05%   |
| Maxtor              | 2         | 2      | 1.05%   |
| LITEON              | 2         | 5      | 1.05%   |
| Lenovo              | 2         | 2      | 1.05%   |
| Intel               | 2         | 2      | 1.05%   |
| Hewlett-Packard     | 2         | 3      | 1.05%   |
| Dogfish             | 2         | 2      | 1.05%   |
| A-DATA Technology   | 2         | 2      | 1.05%   |
| WD MediaMax         | 1         | 3      | 0.53%   |
| Union Memory        | 1         | 2      | 0.53%   |
| UMIS                | 1         | 1      | 0.53%   |
| Transcend           | 1         | 2      | 0.53%   |
| Teclast             | 1         | 1      | 0.53%   |
| Smart               | 1         | 1      | 0.53%   |
| SABRENT             | 1         | 2      | 0.53%   |
| Plextor             | 1         | 1      | 0.53%   |
| Patriot             | 1         | 1      | 0.53%   |
| Mushkin             | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| Kston               | 1         | 1      | 0.53%   |
| KIOXIA              | 1         | 1      | 0.53%   |
| KingFast            | 1         | 1      | 0.53%   |
| KingDian            | 1         | 1      | 0.53%   |
| Intenso             | 1         | 1      | 0.53%   |
| IBM/Hitachi         | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                  | 4         | 1.9%    |
| Unknown MMC Card  128GB              | 3         | 1.42%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.42%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.42%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.42%   |
| Kingston SA2000M8250G 250GB          | 3         | 1.42%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 0.95%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.95%   |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 0.95%   |
| Unknown MMC Card  32GB               | 2         | 0.95%   |
| Seagate ST3500418AS 500GB            | 2         | 0.95%   |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 0.95%   |
| Samsung SSD 980 1TB                  | 2         | 0.95%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.95%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.95%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB | 2         | 0.95%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.95%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.95%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.95%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.95%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.47%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.47%   |
| WDC WD800BB-00JHC0 80GB              | 1         | 0.47%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.47%   |
| WDC WD5001AALS-00L3B2 500GB          | 1         | 0.47%   |
| WDC WD5001AALS-00E3A0 500GB          | 1         | 0.47%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.47%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 1         | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.47%   |
| WDC WD40EDAZ-11SLVB0 4TB             | 1         | 0.47%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.47%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.47%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.47%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.47%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 1         | 0.47%   |
| WDC WD20EZRX-00DC0B0 2TB             | 1         | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 44     | 36.49%  |
| Seagate             | 22        | 30     | 29.73%  |
| Toshiba             | 7         | 7      | 9.46%   |
| Hitachi             | 5         | 5      | 6.76%   |
| HGST                | 4         | 4      | 5.41%   |
| Fujitsu             | 3         | 3      | 4.05%   |
| Maxtor              | 2         | 2      | 2.7%    |
| Samsung Electronics | 1         | 1      | 1.35%   |
| SABRENT             | 1         | 2      | 1.35%   |
| IBM/Hitachi         | 1         | 1      | 1.35%   |
| Hewlett-Packard     | 1         | 2      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 17.95%  |
| Kingston            | 12        | 14     | 15.38%  |
| Crucial             | 6         | 7      | 7.69%   |
| SanDisk             | 5         | 5      | 6.41%   |
| PNY                 | 5         | 6      | 6.41%   |
| WDC                 | 4         | 5      | 5.13%   |
| Team                | 3         | 3      | 3.85%   |
| Netac               | 3         | 3      | 3.85%   |
| SK hynix            | 2         | 2      | 2.56%   |
| Micron Technology   | 2         | 2      | 2.56%   |
| LITEON              | 2         | 5      | 2.56%   |
| Dogfish             | 2         | 2      | 2.56%   |
| A-DATA Technology   | 2         | 2      | 2.56%   |
| Union Memory        | 1         | 2      | 1.28%   |
| Transcend           | 1         | 2      | 1.28%   |
| Teclast             | 1         | 1      | 1.28%   |
| Smart               | 1         | 1      | 1.28%   |
| Plextor             | 1         | 1      | 1.28%   |
| Patriot             | 1         | 1      | 1.28%   |
| Mushkin             | 1         | 1      | 1.28%   |
| LITEONIT            | 1         | 1      | 1.28%   |
| Kston               | 1         | 1      | 1.28%   |
| KingDian            | 1         | 1      | 1.28%   |
| Intenso             | 1         | 1      | 1.28%   |
| HXY                 | 1         | 1      | 1.28%   |
| Hewlett-Packard     | 1         | 1      | 1.28%   |
| GOODRAM             | 1         | 1      | 1.28%   |
| Emtec               | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 70        | 89     | 40.7%   |
| HDD     | 61        | 101    | 35.47%  |
| NVMe    | 28        | 36     | 16.28%  |
| MMC     | 11        | 13     | 6.4%    |
| Unknown | 2         | 4      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 185    | 70.67%  |
| NVMe | 28        | 36     | 18.67%  |
| MMC  | 11        | 13     | 7.33%   |
| SAS  | 5         | 9      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 118    | 65.35%  |
| 0.51-1.0   | 28        | 51     | 22.05%  |
| 1.01-2.0   | 9         | 14     | 7.09%   |
| 3.01-4.0   | 4         | 4      | 3.15%   |
| 4.01-10.0  | 2         | 2      | 1.57%   |
| 2.01-3.0   | 1         | 1      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 30        | 22.39%  |
| 101-250        | 28        | 20.9%   |
| 501-1000       | 19        | 14.18%  |
| 1001-2000      | 16        | 11.94%  |
| 51-100         | 11        | 8.21%   |
| 21-50          | 10        | 7.46%   |
| More than 3000 | 6         | 4.48%   |
| Unknown        | 6         | 4.48%   |
| 2001-3000      | 4         | 2.99%   |
| 1-20           | 4         | 2.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 27.82%  |
| 101-250        | 28        | 21.05%  |
| 21-50          | 15        | 11.28%  |
| 51-100         | 13        | 9.77%   |
| 251-500        | 11        | 8.27%   |
| 501-1000       | 10        | 7.52%   |
| 1001-2000      | 9         | 6.77%   |
| Unknown        | 6         | 4.51%   |
| More than 3000 | 2         | 1.5%    |
| 2001-3000      | 2         | 1.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 2         | 2      | 10.53%  |
| WDC WD5000LPVX-00V0TT0 500GB      | 1         | 1      | 5.26%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 5.26%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 5.26%   |
| WDC WD10EARX-00N0YB0 1TB          | 1         | 1      | 5.26%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 5.26%   |
| Toshiba MQ02ABF100 1TB            | 1         | 1      | 5.26%   |
| SK hynix SH920 mSATA 128GB SSD    | 1         | 1      | 5.26%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 5.26%   |
| Maxtor 6E040L0 41GB               | 1         | 1      | 5.26%   |
| Kingston SA400S37120G 120GB SSD   | 1         | 1      | 5.26%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 5.26%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 5.26%   |
| Hitachi HDS721616PLA380 160GB     | 1         | 1      | 5.26%   |
| HGST HTE721010A9E630 1TB          | 1         | 1      | 5.26%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 2      | 5.26%   |
| Fujitsu MHV2060BH PL 64GB         | 1         | 1      | 5.26%   |
| China SSD 256GB                   | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 31.58%  |
| Hitachi         | 3         | 3      | 15.79%  |
| Toshiba         | 2         | 2      | 10.53%  |
| SK hynix        | 1         | 1      | 5.26%   |
| Seagate         | 1         | 1      | 5.26%   |
| Maxtor          | 1         | 1      | 5.26%   |
| Kingston        | 1         | 1      | 5.26%   |
| HGST            | 1         | 1      | 5.26%   |
| Hewlett-Packard | 1         | 2      | 5.26%   |
| Fujitsu         | 1         | 1      | 5.26%   |
| China           | 1         | 1      | 5.26%   |

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
| HDD  | 16        | 17     | 84.21%  |
| SSD  | 3         | 3      | 15.79%  |

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
| Works    | 98        | 170    | 66.22%  |
| Detected | 32        | 53     | 21.62%  |
| Malfunc  | 18        | 20     | 12.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 92        | 60.53%  |
| AMD                              | 22        | 14.47%  |
| Samsung Electronics              | 8         | 5.26%   |
| SanDisk                          | 5         | 3.29%   |
| Kingston Technology Company      | 4         | 2.63%   |
| SK hynix                         | 3         | 1.97%   |
| Toshiba America Info Systems     | 2         | 1.32%   |
| Micron/Crucial Technology        | 2         | 1.32%   |
| Marvell Technology Group         | 2         | 1.32%   |
| Lenovo                           | 2         | 1.32%   |
| VIA Technologies                 | 1         | 0.66%   |
| Union Memory (Shenzhen)          | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Nvidia                           | 1         | 0.66%   |
| KIOXIA                           | 1         | 0.66%   |
| Integrated Technology Express    | 1         | 0.66%   |
| Chelsio Communications           | 1         | 0.66%   |
| Broadcom / LSI                   | 1         | 0.66%   |
| ASMedia Technology               | 1         | 0.66%   |
| Adaptec                          | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 8.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 2.84%   |
| Kingston Company A2000 NVMe SSD                                                | 4         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.27%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.7%    |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.14%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.14%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.14%   |
| AMD FCH SATA Controller D                                                      | 2         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.14%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1         | 0.57%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.57%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.57%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.57%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.57%   |
| SK hynix BC511                                                                 | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 60.53%  |
| NVMe | 28        | 18.42%  |
| IDE  | 20        | 13.16%  |
| RAID | 10        | 6.58%   |
| SCSI | 2         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 103       | 80.47%  |
| AMD    | 24        | 18.75%  |
| ARM    | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.55%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.55%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.55%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.55%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.55%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.78%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.78%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.78%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.78%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.78%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.78%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.78%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.78%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.78%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.78%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.78%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.78%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.78%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.78%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.78%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-8700T CPU @ 2.40GHz           | 1         | 0.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.78%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.78%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.78%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.78%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 21.71%  |
| Intel Core i7           | 23        | 17.83%  |
| Intel Core i3           | 13        | 10.08%  |
| Intel Celeron           | 8         | 6.2%    |
| AMD Ryzen 5             | 6         | 4.65%   |
| Other                   | 4         | 3.1%    |
| Intel Xeon              | 4         | 3.1%    |
| Intel Core 2 Duo        | 4         | 3.1%    |
| Intel Pentium           | 3         | 2.33%   |
| Intel Core 2            | 3         | 2.33%   |
| Intel Atom              | 3         | 2.33%   |
| AMD Ryzen 7             | 3         | 2.33%   |
| Intel Pentium M         | 2         | 1.55%   |
| Intel Pentium Dual-Core | 2         | 1.55%   |
| Intel Pentium Dual      | 2         | 1.55%   |
| Intel Core i9           | 2         | 1.55%   |
| AMD Ryzen 3             | 2         | 1.55%   |
| Intel Pentium Silver    | 1         | 0.78%   |
| Intel Pentium Gold      | 1         | 0.78%   |
| Intel Pentium 4         | 1         | 0.78%   |
| Intel Core 2 Quad       | 1         | 0.78%   |
| Intel Celeron M         | 1         | 0.78%   |
| AMD Sempron             | 1         | 0.78%   |
| AMD Ryzen Threadripper  | 1         | 0.78%   |
| AMD Ryzen 7 PRO         | 1         | 0.78%   |
| AMD FX                  | 1         | 0.78%   |
| AMD E2                  | 1         | 0.78%   |
| AMD E                   | 1         | 0.78%   |
| AMD Athlon II           | 1         | 0.78%   |
| AMD Athlon              | 1         | 0.78%   |
| AMD A8                  | 1         | 0.78%   |
| AMD A6                  | 1         | 0.78%   |
| AMD A4                  | 1         | 0.78%   |
| AMD A10                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 59        | 46.09%  |
| 4      | 40        | 31.25%  |
| 6      | 14        | 10.94%  |
| 1      | 8         | 6.25%   |
| 8      | 5         | 3.91%   |
| 12     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 128       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 74        | 57.81%  |
| 1      | 54        | 42.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 121       | 94.53%  |
| 32-bit         | 4         | 3.13%   |
| Unknown        | 3         | 2.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 23.48%  |
| 0x306c3    | 9         | 6.82%   |
| 0x306a9    | 7         | 5.3%    |
| 0x206a7    | 7         | 5.3%    |
| 0x906ea    | 6         | 4.55%   |
| 0x1067a    | 6         | 4.55%   |
| 0x406e3    | 5         | 3.79%   |
| 0x806ec    | 4         | 3.03%   |
| 0x706a1    | 3         | 2.27%   |
| 0x40651    | 3         | 2.27%   |
| 0x306d4    | 3         | 2.27%   |
| 0x706a8    | 2         | 1.52%   |
| 0x6f6      | 2         | 1.52%   |
| 0x506e3    | 2         | 1.52%   |
| 0x406c4    | 2         | 1.52%   |
| 0x30678    | 2         | 1.52%   |
| 0x20655    | 2         | 1.52%   |
| 0x106e5    | 2         | 1.52%   |
| 0x08701021 | 2         | 1.52%   |
| 0x08608103 | 2         | 1.52%   |
| 0xf49      | 1         | 0.76%   |
| 0xa0655    | 1         | 0.76%   |
| 0xa0653    | 1         | 0.76%   |
| 0x906ed    | 1         | 0.76%   |
| 0x906e9    | 1         | 0.76%   |
| 0x806ea    | 1         | 0.76%   |
| 0x806c1    | 1         | 0.76%   |
| 0x6fd      | 1         | 0.76%   |
| 0x6d8      | 1         | 0.76%   |
| 0x695      | 1         | 0.76%   |
| 0x686      | 1         | 0.76%   |
| 0x506c9    | 1         | 0.76%   |
| 0x406d8    | 1         | 0.76%   |
| 0x306f2    | 1         | 0.76%   |
| 0x20652    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x0a601203 | 1         | 0.76%   |
| 0x0a20120a | 1         | 0.76%   |
| 0x08701013 | 1         | 0.76%   |
| 0x08600106 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 13.28%  |
| Haswell       | 15        | 11.72%  |
| IvyBridge     | 10        | 7.81%   |
| Skylake       | 9         | 7.03%   |
| SandyBridge   | 7         | 5.47%   |
| Penryn        | 7         | 5.47%   |
| Silvermont    | 6         | 4.69%   |
| Westmere      | 5         | 3.91%   |
| Goldmont plus | 5         | 3.91%   |
| Zen 2         | 4         | 3.13%   |
| Zen           | 4         | 3.13%   |
| P6            | 4         | 3.13%   |
| Nehalem       | 4         | 3.13%   |
| Core          | 4         | 3.13%   |
| Broadwell     | 4         | 3.13%   |
| Unknown       | 4         | 3.13%   |
| Zen+          | 2         | 1.56%   |
| TigerLake     | 2         | 1.56%   |
| Piledriver    | 2         | 1.56%   |
| Excavator     | 2         | 1.56%   |
| CometLake     | 2         | 1.56%   |
| Bobcat        | 2         | 1.56%   |
| Zen 3         | 1         | 0.78%   |
| Puma          | 1         | 0.78%   |
| NetBurst      | 1         | 0.78%   |
| K8 Hammer     | 1         | 0.78%   |
| K10 Llano     | 1         | 0.78%   |
| K10           | 1         | 0.78%   |
| Goldmont      | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 79        | 56.43%  |
| AMD                              | 33        | 23.57%  |
| Nvidia                           | 27        | 19.29%  |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.4%    |
| Intel HD Graphics 5500                                                                   | 4         | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.36%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.36%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.36%   |
| Intel HD Graphics 620                                                                    | 2         | 1.36%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.36%   |
| AMD Lucienne                                                                             | 2         | 1.36%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.68%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.68%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.68%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.68%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.68%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.68%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.68%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 48.44%  |
| 1 x AMD        | 26        | 20.31%  |
| 1 x Nvidia     | 17        | 13.28%  |
| Intel + Nvidia | 10        | 7.81%   |
| Other          | 4         | 3.13%   |
| 2 x AMD        | 4         | 3.13%   |
| Intel + AMD    | 3         | 2.34%   |
| 2 x Intel      | 1         | 0.78%   |
| 1 x SiS        | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 83.72%  |
| Proprietary | 14        | 10.85%  |
| Unknown     | 7         | 5.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 62.6%   |
| 0.01-0.5   | 17        | 12.98%  |
| 3.01-4.0   | 9         | 6.87%   |
| 0.51-1.0   | 9         | 6.87%   |
| 1.01-2.0   | 6         | 4.58%   |
| 7.01-8.0   | 3         | 2.29%   |
| 2.01-3.0   | 3         | 2.29%   |
| 5.01-6.0   | 2         | 1.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 14.6%   |
| LG Display              | 19        | 13.87%  |
| AU Optronics            | 14        | 10.22%  |
| Chimei Innolux          | 10        | 7.3%    |
| Hewlett-Packard         | 9         | 6.57%   |
| Goldstar                | 6         | 4.38%   |
| Philips                 | 5         | 3.65%   |
| BOE                     | 5         | 3.65%   |
| Acer                    | 5         | 3.65%   |
| PANDA                   | 4         | 2.92%   |
| Lenovo                  | 4         | 2.92%   |
| Iiyama                  | 4         | 2.92%   |
| Dell                    | 4         | 2.92%   |
| AOC                     | 4         | 2.92%   |
| Unknown                 | 3         | 2.19%   |
| MStar                   | 2         | 1.46%   |
| Chi Mei Optoelectronics | 2         | 1.46%   |
| Ancor Communications    | 2         | 1.46%   |
| ___                     | 1         | 0.73%   |
| ViewSonic               | 1         | 0.73%   |
| Toshiba                 | 1         | 0.73%   |
| STD                     | 1         | 0.73%   |
| Sony                    | 1         | 0.73%   |
| Sharp                   | 1         | 0.73%   |
| MSI                     | 1         | 0.73%   |
| InnoLux Display         | 1         | 0.73%   |
| InfoVision              | 1         | 0.73%   |
| HJW                     | 1         | 0.73%   |
| Hisense                 | 1         | 0.73%   |
| eMachines               | 1         | 0.73%   |
| Eizo                    | 1         | 0.73%   |
| CVT                     | 1         | 0.73%   |
| CHI                     | 1         | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 1.42%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.42%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch      | 2         | 1.42%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                        | 2         | 1.42%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.42%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.42%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.71%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.71%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.71%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.71%   |
| STD HDMI TV STD00C7 1360x768 698x392mm 31.5-inch                       | 1         | 0.71%   |
| Sony TV SNY3002 1920x1080 708x398mm 32.0-inch                          | 1         | 0.71%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.71%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.71%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM0503 1920x1080                      | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.71%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.71%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.71%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.71%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1         | 0.71%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.71%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.71%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 0.71%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 0.71%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 0.71%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 41.04%  |
| 1366x768 (WXGA)    | 35        | 26.12%  |
| 3840x2160 (4K)     | 9         | 6.72%   |
| 1600x900 (HD+)     | 6         | 4.48%   |
| 1440x900 (WXGA+)   | 6         | 4.48%   |
| 1280x1024 (SXGA)   | 5         | 3.73%   |
| 3440x1440          | 2         | 1.49%   |
| 2288x1287          | 2         | 1.49%   |
| 1600x1200          | 2         | 1.49%   |
| 1280x800 (WXGA)    | 2         | 1.49%   |
| Unknown            | 2         | 1.49%   |
| 5760x1080          | 1         | 0.75%   |
| 3000x2000          | 1         | 0.75%   |
| 2736x1824          | 1         | 0.75%   |
| 2048x1152          | 1         | 0.75%   |
| 1920x1200 (WUXGA)  | 1         | 0.75%   |
| 1680x1050 (WSXGA+) | 1         | 0.75%   |
| 1360x768           | 1         | 0.75%   |
| 1024x768 (XGA)     | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 22.96%  |
| 21      | 15        | 11.11%  |
| 14      | 11        | 8.15%   |
| 24      | 10        | 7.41%   |
| 12      | 10        | 7.41%   |
| 13      | 9         | 6.67%   |
| 23      | 8         | 5.93%   |
| 27      | 6         | 4.44%   |
| 17      | 6         | 4.44%   |
| Unknown | 5         | 3.7%    |
| 19      | 4         | 2.96%   |
| 31      | 3         | 2.22%   |
| 18      | 3         | 2.22%   |
| 142     | 2         | 1.48%   |
| 72      | 2         | 1.48%   |
| 52      | 2         | 1.48%   |
| 34      | 2         | 1.48%   |
| 11      | 2         | 1.48%   |
| 54      | 1         | 0.74%   |
| 40      | 1         | 0.74%   |
| 22      | 1         | 0.74%   |
| 20      | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 46        | 35.11%  |
| 501-600        | 23        | 17.56%  |
| 401-500        | 20        | 15.27%  |
| 201-300        | 18        | 13.74%  |
| 351-400        | 6         | 4.58%   |
| Unknown        | 5         | 3.82%   |
| 601-700        | 3         | 2.29%   |
| 1001-1500      | 3         | 2.29%   |
| More than 2000 | 2         | 1.53%   |
| 701-800        | 2         | 1.53%   |
| 1501-2000      | 2         | 1.53%   |
| 801-900        | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 78.33%  |
| 16/10   | 9         | 7.5%    |
| 4/3     | 4         | 3.33%   |
| 5/4     | 3         | 2.5%    |
| Unknown | 3         | 2.5%    |
| 3/2     | 2         | 1.67%   |
| 21/9    | 2         | 1.67%   |
| 1.00    | 2         | 1.67%   |
| 6/5     | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 21.8%   |
| 201-250        | 26        | 19.55%  |
| 81-90          | 14        | 10.53%  |
| 151-200        | 11        | 8.27%   |
| 61-70          | 10        | 7.52%   |
| More than 1000 | 7         | 5.26%   |
| 71-80          | 6         | 4.51%   |
| 301-350        | 6         | 4.51%   |
| 351-500        | 5         | 3.76%   |
| Unknown        | 5         | 3.76%   |
| 141-150        | 4         | 3.01%   |
| 121-130        | 3         | 2.26%   |
| 51-60          | 2         | 1.5%    |
| 111-120        | 2         | 1.5%    |
| 251-300        | 1         | 0.75%   |
| 131-140        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 32.58%  |
| 51-100        | 39        | 29.55%  |
| 121-160       | 30        | 22.73%  |
| 1-50          | 7         | 5.3%    |
| 161-240       | 6         | 4.55%   |
| Unknown       | 5         | 3.79%   |
| More than 240 | 2         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 104       | 80%     |
| 2     | 17        | 13.08%  |
| 3     | 5         | 3.85%   |
| 0     | 4         | 3.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 63        | 33.87%  |
| Realtek Semiconductor            | 59        | 31.72%  |
| Qualcomm Atheros                 | 26        | 13.98%  |
| Broadcom                         | 6         | 3.23%   |
| Ralink Technology                | 5         | 2.69%   |
| Samsung Electronics              | 3         | 1.61%   |
| MediaTek                         | 3         | 1.61%   |
| Marvell Technology Group         | 3         | 1.61%   |
| TP-Link                          | 2         | 1.08%   |
| Sierra Wireless                  | 2         | 1.08%   |
| NetGear                          | 2         | 1.08%   |
| JMicron Technology               | 2         | 1.08%   |
| Broadcom Limited                 | 2         | 1.08%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.54%   |
| VIA Technologies                 | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Ralink                           | 1         | 0.54%   |
| Nvidia                           | 1         | 0.54%   |
| DisplayLink                      | 1         | 0.54%   |
| Dell                             | 1         | 0.54%   |
| Chelsio Communications           | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 42        | 19.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 5.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 2.74%   |
| Intel Wireless 7260                                                     | 5         | 2.28%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.83%   |
| Intel Ethernet Connection (7) I219-LM                                   | 4         | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 1.37%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.37%   |
| Intel Wireless 8260                                                     | 3         | 1.37%   |
| Intel Wireless 7265                                                     | 3         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.37%   |
| Intel Ethernet Controller I225-V                                        | 3         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.37%   |
| Sierra Wireless EM7455                                                  | 2         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.91%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.91%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 0.91%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.91%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.91%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                           | 1         | 0.46%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 33        | 37.08%  |
| Qualcomm Atheros         | 23        | 25.84%  |
| Realtek Semiconductor    | 12        | 13.48%  |
| Ralink Technology        | 5         | 5.62%   |
| MediaTek                 | 3         | 3.37%   |
| Broadcom                 | 3         | 3.37%   |
| Sierra Wireless          | 2         | 2.25%   |
| NetGear                  | 2         | 2.25%   |
| Broadcom Limited         | 2         | 2.25%   |
| TP-Link                  | 1         | 1.12%   |
| Ralink                   | 1         | 1.12%   |
| Marvell Technology Group | 1         | 1.12%   |
| Dell                     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 5         | 5.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 5.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.49%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.37%   |
| Intel Wireless 8260                                                     | 3         | 3.37%   |
| Intel Wireless 7265                                                     | 3         | 3.37%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.37%   |
| Sierra Wireless EM7455                                                  | 2         | 2.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.25%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.25%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.25%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 2.25%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.25%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.12%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.12%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.12%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.12%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.12%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.12%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.12%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.12%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 53        | 42.4%   |
| Intel                            | 50        | 40%     |
| Qualcomm Atheros                 | 5         | 4%      |
| Samsung Electronics              | 3         | 2.4%    |
| Broadcom                         | 3         | 2.4%    |
| Marvell Technology Group         | 2         | 1.6%    |
| JMicron Technology               | 2         | 1.6%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.8%    |
| VIA Technologies                 | 1         | 0.8%    |
| TP-Link                          | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] | 1         | 0.8%    |
| Nvidia                           | 1         | 0.8%    |
| DisplayLink                      | 1         | 0.8%    |
| Chelsio Communications           | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 33.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 8.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 4.72%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 3.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.36%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.57%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 0.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.79%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.79%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.79%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 0.79%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.79%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 57.14%  |
| WiFi     | 84        | 41.38%  |
| Modem    | 3         | 1.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 53.08%  |
| WiFi     | 61        | 46.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 70        | 53.85%  |
| 1     | 53        | 40.77%  |
| 0     | 4         | 3.08%   |
| 7     | 1         | 0.77%   |
| 5     | 1         | 0.77%   |
| 3     | 1         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 87.5%   |
| Yes  | 16        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 39.66%  |
| Realtek Semiconductor           | 6         | 10.34%  |
| Qualcomm Atheros Communications | 6         | 10.34%  |
| Broadcom                        | 4         | 6.9%    |
| Lite-On Technology              | 3         | 5.17%   |
| IMC Networks                    | 3         | 5.17%   |
| Cambridge Silicon Radio         | 3         | 5.17%   |
| Foxconn / Hon Hai               | 2         | 3.45%   |
| Dell                            | 2         | 3.45%   |
| Ralink                          | 1         | 1.72%   |
| MediaTek                        | 1         | 1.72%   |
| Marvell Semiconductor           | 1         | 1.72%   |
| Foxconn International           | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |
| Apple                           | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 20.69%  |
| Realtek Bluetooth Radio                             | 6         | 10.34%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.9%    |
| Intel AX200 Bluetooth                               | 3         | 5.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 3.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.72%   |
| MediaTek Wireless_Device                            | 1         | 1.72%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.72%   |
| Intel AX201 Bluetooth                               | 1         | 1.72%   |
| IMC Networks Bluetooth Device                       | 1         | 1.72%   |
| IMC Networks BCM20702A0                             | 1         | 1.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.72%   |
| Foxconn / Hon Hai BT                                | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.72%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96        | 57.14%  |
| AMD                              | 28        | 16.67%  |
| Nvidia                           | 20        | 11.9%   |
| C-Media Electronics              | 4         | 2.38%   |
| Creative Labs                    | 3         | 1.79%   |
| Plantronics                      | 2         | 1.19%   |
| Texas Instruments                | 1         | 0.6%    |
| TEAC                             | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Sennheiser Communications        | 1         | 0.6%    |
| Realtek Semiconductor            | 1         | 0.6%    |
| M-Audio                          | 1         | 0.6%    |
| Logitech                         | 1         | 0.6%    |
| KORG                             | 1         | 0.6%    |
| GYROCOM C&C                      | 1         | 0.6%    |
| Giga-Byte Technology             | 1         | 0.6%    |
| Elite Silicon                    | 1         | 0.6%    |
| DCMT Technology                  | 1         | 0.6%    |
| Cirrus Logic                     | 1         | 0.6%    |
| Blue Microphones                 | 1         | 0.6%    |
| ASUSTek Computer                 | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 5.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 4.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 4.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 4.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 2.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.95%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.95%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.95%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.46%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.46%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.46%   |
| Plantronics HD1                                                            | 2         | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.98%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 0.98%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 0.98%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.98%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.98%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 20%     |
| Unknown             | 21        | 16.15%  |
| SK hynix            | 16        | 12.31%  |
| Kingston            | 16        | 12.31%  |
| Corsair             | 9         | 6.92%   |
| Micron Technology   | 8         | 6.15%   |
| G.Skill             | 6         | 4.62%   |
| Crucial             | 6         | 4.62%   |
| A-DATA Technology   | 6         | 4.62%   |
| Unknown (ABCD)      | 3         | 2.31%   |
| Nanya Technology    | 3         | 2.31%   |
| Unknown             | 2         | 1.54%   |
| Unknown (130B)      | 1         | 0.77%   |
| Team                | 1         | 0.77%   |
| Smart               | 1         | 0.77%   |
| Ramaxel Technology  | 1         | 0.77%   |
| GOODRAM             | 1         | 0.77%   |
| Avant               | 1         | 0.77%   |
| Apacer              | 1         | 0.77%   |
| 4ea5                | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 2.01%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.34%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 2         | 1.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.34%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.34%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Unknown                                                          | 2         | 1.34%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 0.67%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.67%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.67%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.67%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.67%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 0.67%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s               | 1         | 0.67%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.67%   |
| Unknown (130B) RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.67%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2933MT/s            | 1         | 0.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1066MT/s                     | 1         | 0.67%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 43.36%  |
| DDR4    | 40        | 35.4%   |
| SDRAM   | 4         | 3.54%   |
| LPDDR4  | 4         | 3.54%   |
| LPDDR3  | 4         | 3.54%   |
| DDR     | 4         | 3.54%   |
| DDR2    | 3         | 2.65%   |
| Unknown | 3         | 2.65%   |
| DRAM    | 1         | 0.88%   |
| DDR5    | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 54.46%  |
| DIMM         | 45        | 40.18%  |
| Row Of Chips | 4         | 3.57%   |
| Chip         | 1         | 0.89%   |
| Unknown      | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 47        | 36.72%  |
| 4096  | 35        | 27.34%  |
| 16384 | 18        | 14.06%  |
| 2048  | 17        | 13.28%  |
| 1024  | 5         | 3.91%   |
| 32768 | 2         | 1.56%   |
| 512   | 1         | 0.78%   |
| 256   | 1         | 0.78%   |
| 128   | 1         | 0.78%   |
| 64    | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 26.23%  |
| 2667    | 18        | 14.75%  |
| 2400    | 13        | 10.66%  |
| 1333    | 9         | 7.38%   |
| 3200    | 7         | 5.74%   |
| Unknown | 7         | 5.74%   |
| 2133    | 6         | 4.92%   |
| 3600    | 4         | 3.28%   |
| 1067    | 4         | 3.28%   |
| 4199    | 2         | 1.64%   |
| 3400    | 2         | 1.64%   |
| 1867    | 2         | 1.64%   |
| 1800    | 2         | 1.64%   |
| 1066    | 2         | 1.64%   |
| 800     | 2         | 1.64%   |
| 667     | 2         | 1.64%   |
| 4800    | 1         | 0.82%   |
| 3534    | 1         | 0.82%   |
| 3266    | 1         | 0.82%   |
| 2933    | 1         | 0.82%   |
| 1334    | 1         | 0.82%   |
| 1200    | 1         | 0.82%   |
| 400     | 1         | 0.82%   |
| 100     | 1         | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 2         | 33.33%  |
| Samsung Electronics    | 1         | 16.67%  |
| Custom Engineering SPA | 1         | 16.67%  |
| Canon                  | 1         | 16.67%  |
| Brother Industries     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-4600 Series         | 1         | 16.67%  |
| HP ENVY 5000 series             | 1         | 16.67%  |
| HP Deskjet 1050 J410            | 1         | 16.67%  |
| Custom Engineering SPA KUBE USB | 1         | 16.67%  |
| Canon G1010 series              | 1         | 16.67%  |
| Brother HL-L2375DW series       | 1         | 16.67%  |

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
| Chicony Electronics                    | 24        | 35.29%  |
| Microdia                               | 8         | 11.76%  |
| Sunplus Innovation Technology          | 5         | 7.35%   |
| Realtek Semiconductor                  | 4         | 5.88%   |
| Logitech                               | 3         | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.41%   |
| Suyin                                  | 2         | 2.94%   |
| Lite-On Technology                     | 2         | 2.94%   |
| KYE Systems (Mouse Systems)            | 2         | 2.94%   |
| Cubeternet                             | 2         | 2.94%   |
| Bison Electronics                      | 2         | 2.94%   |
| Acer                                   | 2         | 2.94%   |
| Z-Star Microelectronics                | 1         | 1.47%   |
| Softkinetic                            | 1         | 1.47%   |
| Samsung Electronics                    | 1         | 1.47%   |
| Quanta                                 | 1         | 1.47%   |
| Mustek Systems                         | 1         | 1.47%   |
| Microsoft                              | 1         | 1.47%   |
| MacroSilicon                           | 1         | 1.47%   |
| IMC Networks                           | 1         | 1.47%   |
| GEMBIRD                                | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 8         | 11.76%  |
| Logitech HD Pro Webcam C920               | 2         | 2.94%   |
| Cubeternet GL-UPC822 UVC WebCam           | 2         | 2.94%   |
| Chicony HP TrueVision HD Camera           | 2         | 2.94%   |
| Chicony HD Webcam                         | 2         | 2.94%   |
| Chicony EasyCamera                        | 2         | 2.94%   |
| Acer BisonCam, NB Pro                     | 2         | 2.94%   |
| Z-Star Vimicro USB Camera (Altair)        | 1         | 1.47%   |
| Suyin Acer/Lenovo Webcam [CN0316]         | 1         | 1.47%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 1         | 1.47%   |
| Sunplus WEMISS CM-A1                      | 1         | 1.47%   |
| Sunplus Laptop Integrated Webcam HD       | 1         | 1.47%   |
| Sunplus Integrated_Webcam_HD              | 1         | 1.47%   |
| Sunplus Asus Webcam                       | 1         | 1.47%   |
| Sunplus 720p HD Camera                    | 1         | 1.47%   |
| Softkinetic DepthSense 325                | 1         | 1.47%   |
| Samsung Galaxy A5 (MTP)                   | 1         | 1.47%   |
| Realtek Lenovo EasyCamera                 | 1         | 1.47%   |
| Realtek Integrated_Webcam_HD              | 1         | 1.47%   |
| Realtek Integrated Webcam_HD              | 1         | 1.47%   |
| Realtek HD 720P Webcam                    | 1         | 1.47%   |
| Quanta Sony Visual Communication Camera   | 1         | 1.47%   |
| Mustek Systems USB 2.0 PC Camera          | 1         | 1.47%   |
| Microsoft LifeCam Studio                  | 1         | 1.47%   |
| Microdia Webcam Vitade AF                 | 1         | 1.47%   |
| Microdia WebCam SC-13HDL12639P            | 1         | 1.47%   |
| Microdia Sonix USB 2.0 Camera             | 1         | 1.47%   |
| Microdia Integrated_Webcam_HD             | 1         | 1.47%   |
| Microdia Integrated Webcam                | 1         | 1.47%   |
| Microdia Dell Integrated HD Webcam        | 1         | 1.47%   |
| Microdia Camera                           | 1         | 1.47%   |
| Microdia 1.3 MPixel Integrated Webcam     | 1         | 1.47%   |
| MacroSilicon USB Video                    | 1         | 1.47%   |
| Logitech Webcam C270                      | 1         | 1.47%   |
| Lite-On HP Wide Vision HD Camera          | 1         | 1.47%   |
| Lite-On HP HD Webcam                      | 1         | 1.47%   |
| KYE Systems (Mouse Systems) PC-W3 Camera  | 1         | 1.47%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1         | 1.47%   |
| IMC Networks Integrated Webcam            | 1         | 1.47%   |
| GEMBIRD USB2.0 PC CAMERA                  | 1         | 1.47%   |

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
| Broadcom    | 8         | 66.67%  |
| Alcor Micro | 3         | 25%     |
| Lenovo      | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Broadcom 5880                                                                | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 98        | 75.38%  |
| 1     | 22        | 16.92%  |
| 2     | 7         | 5.38%   |
| 3     | 2         | 1.54%   |
| 5     | 1         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 8         | 22.22%  |
| Chipcard                 | 8         | 22.22%  |
| Fingerprint reader       | 4         | 11.11%  |
| Communication controller | 4         | 11.11%  |
| Net/wireless             | 3         | 8.33%   |
| Multimedia controller    | 2         | 5.56%   |
| Camera                   | 2         | 5.56%   |
| Bluetooth                | 2         | 5.56%   |
| Unassigned class         | 1         | 2.78%   |
| Net/ethernet             | 1         | 2.78%   |
| Firewire controller      | 1         | 2.78%   |


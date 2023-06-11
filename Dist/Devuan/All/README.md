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

Total: 180

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Bravo 15 A4DDR              | Notebook    | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [54f07f7d96](https://linux-hardware.org/?probe=54f07f7d96) | May 12, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [36022cb1ac](https://linux-hardware.org/?probe=36022cb1ac) | May 11, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [96e067f5c8](https://linux-hardware.org/?probe=96e067f5c8) | Apr 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [549f922cf6](https://linux-hardware.org/?probe=549f922cf6) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a9aa9ab39f](https://linux-hardware.org/?probe=a9aa9ab39f) | Apr 13, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [491da3c2c2](https://linux-hardware.org/?probe=491da3c2c2) | Apr 10, 2023 |
| Google        | Cyan                        | Notebook    | [f32e15dfef](https://linux-hardware.org/?probe=f32e15dfef) | Apr 09, 2023 |
| MSI           | PH67A-C43                   | Desktop     | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [ec45a753a5](https://linux-hardware.org/?probe=ec45a753a5) | Apr 02, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 69        | 46.62%  |
| Devuan 3                | 30        | 20.27%  |
| Devuan 5                | 21        | 14.19%  |
| Devuan Testing/unstable | 15        | 10.14%  |
| Devuan 2.1              | 7         | 4.73%   |
| Devuan                  | 3         | 2.03%   |
| Devuan 3.0              | 1         | 0.68%   |
| Devuan 2.0              | 1         | 0.68%   |
| Devuan 1.0.0            | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 140       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 13        | 8.28%   |
| 5.10.0-9-amd64        | 10        | 6.37%   |
| 5.10.0-8-amd64        | 7         | 4.46%   |
| 5.10.0-16-amd64       | 6         | 3.82%   |
| 4.19.0-9-amd64        | 6         | 3.82%   |
| 4.19.0-14-amd64       | 6         | 3.82%   |
| 4.19.0-16-amd64       | 5         | 3.18%   |
| 5.10.0-19-amd64       | 4         | 2.55%   |
| 5.10.0-18-amd64       | 4         | 2.55%   |
| 5.10.0-13-amd64       | 4         | 2.55%   |
| 5.10.0-11-amd64       | 4         | 2.55%   |
| 5.10.0-10-amd64       | 4         | 2.55%   |
| 6.1.0-6-amd64         | 3         | 1.91%   |
| 5.7.0-2-amd64         | 3         | 1.91%   |
| 5.10.0-20-amd64       | 3         | 1.91%   |
| 4.19.0-12-amd64       | 3         | 1.91%   |
| 6.0.0-5-amd64         | 2         | 1.27%   |
| 5.7.0-0.bpo.2-amd64   | 2         | 1.27%   |
| 5.18.0-2-amd64        | 2         | 1.27%   |
| 5.18.0-1-amd64        | 2         | 1.27%   |
| 5.15.0-2-amd64        | 2         | 1.27%   |
| 5.10.0-6-amd64        | 2         | 1.27%   |
| 5.10.0-15-amd64       | 2         | 1.27%   |
| 5.10.0-14-amd64       | 2         | 1.27%   |
| 4.19.0-17-amd64       | 2         | 1.27%   |
| 4.19.0-13-amd64       | 2         | 1.27%   |
| 4.19.0-10-amd64       | 2         | 1.27%   |
| 6.2.12                | 1         | 0.64%   |
| 6.1.7                 | 1         | 0.64%   |
| 6.1.25                | 1         | 0.64%   |
| 6.1.0-9-amd64         | 1         | 0.64%   |
| 6.1.0-7-amd64         | 1         | 0.64%   |
| 6.1.0-2-amd64         | 1         | 0.64%   |
| 6.1.0-0.deb11.6-amd64 | 1         | 0.64%   |
| 6.1.0-0.deb11.5-amd64 | 1         | 0.64%   |
| 6.0.0-2-amd64         | 1         | 0.64%   |
| 6.0.0-0.deb11.6-amd64 | 1         | 0.64%   |
| 5.9.0-4-amd64         | 1         | 0.64%   |
| 5.9.0-1-amd64         | 1         | 0.64%   |
| 5.8.0-3-amd64         | 1         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 65        | 43.62%  |
| 4.19.0   | 28        | 18.79%  |
| 6.1.0    | 8         | 5.37%   |
| 4.9.0    | 8         | 5.37%   |
| 5.7.0    | 6         | 4.03%   |
| 6.0.0    | 4         | 2.68%   |
| 5.18.0   | 4         | 2.68%   |
| 5.15.0   | 3         | 2.01%   |
| 5.9.0    | 2         | 1.34%   |
| 5.8.0    | 2         | 1.34%   |
| 5.14.0   | 2         | 1.34%   |
| 6.2.12   | 1         | 0.67%   |
| 6.1.7    | 1         | 0.67%   |
| 6.1.25   | 1         | 0.67%   |
| 5.7.19   | 1         | 0.67%   |
| 5.6.0    | 1         | 0.67%   |
| 5.19.0   | 1         | 0.67%   |
| 5.18.14  | 1         | 0.67%   |
| 5.18.11  | 1         | 0.67%   |
| 5.16.0   | 1         | 0.67%   |
| 5.15.5   | 1         | 0.67%   |
| 5.11.0   | 1         | 0.67%   |
| 5.10.162 | 1         | 0.67%   |
| 5.1.21   | 1         | 0.67%   |
| 5.0.7    | 1         | 0.67%   |
| 4.4.195  | 1         | 0.67%   |
| 4.19.112 | 1         | 0.67%   |
| 4.18.0   | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 66        | 44.3%   |
| 4.19    | 29        | 19.46%  |
| 6.1     | 10        | 6.71%   |
| 4.9     | 8         | 5.37%   |
| 5.7     | 7         | 4.7%    |
| 5.18    | 6         | 4.03%   |
| 6.0     | 4         | 2.68%   |
| 5.15    | 4         | 2.68%   |
| 5.9     | 2         | 1.34%   |
| 5.8     | 2         | 1.34%   |
| 5.14    | 2         | 1.34%   |
| 6.2     | 1         | 0.67%   |
| 5.6     | 1         | 0.67%   |
| 5.19    | 1         | 0.67%   |
| 5.16    | 1         | 0.67%   |
| 5.11    | 1         | 0.67%   |
| 5.1     | 1         | 0.67%   |
| 5.0     | 1         | 0.67%   |
| 4.4     | 1         | 0.67%   |
| 4.18    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 133       | 95%     |
| i686   | 6         | 4.29%   |
| armv7l | 1         | 0.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| XFCE          | 56        | 37.84%  |
| KDE5          | 23        | 15.54%  |
| Unknown       | 21        | 14.19%  |
| MATE          | 20        | 13.51%  |
| i3            | 7         | 4.73%   |
| LXDE          | 6         | 4.05%   |
| GNOME         | 4         | 2.7%    |
| Cinnamon      | 4         | 2.7%    |
| LXQt          | 2         | 1.35%   |
| Enlightenment | 2         | 1.35%   |
| X-Cinnamon    | 1         | 0.68%   |
| Openbox       | 1         | 0.68%   |
| awesome       | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 126       | 88.11%  |
| Tty     | 12        | 8.39%   |
| Unknown | 4         | 2.8%    |
| Wayland | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 51        | 35.42%  |
| LightDM | 39        | 27.08%  |
| Unknown | 34        | 23.61%  |
| SDDM    | 12        | 8.33%   |
| XDM     | 2         | 1.39%   |
| NODM    | 2         | 1.39%   |
| GDM3    | 2         | 1.39%   |
| Ly      | 1         | 0.69%   |
| LXDM    | 1         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 54        | 37.76%  |
| en_GB       | 24        | 16.78%  |
| ru_RU       | 11        | 7.69%   |
| Unknown     | 8         | 5.59%   |
| C           | 6         | 4.2%    |
| pt_BR       | 5         | 3.5%    |
| fr_FR       | 4         | 2.8%    |
| es_ES       | 4         | 2.8%    |
| sk_SK       | 3         | 2.1%    |
| fr_BE       | 3         | 2.1%    |
| en_AU       | 3         | 2.1%    |
| de_DE       | 3         | 2.1%    |
| pl_PL       | 2         | 1.4%    |
| it_IT       | 2         | 1.4%    |
| en_NZ       | 2         | 1.4%    |
| de_AT       | 2         | 1.4%    |
| ru_UA       | 1         | 0.7%    |
| es_SV       | 1         | 0.7%    |
| es_MX       | 1         | 0.7%    |
| en_US.utf-8 | 1         | 0.7%    |
| en_SG       | 1         | 0.7%    |
| en_CA       | 1         | 0.7%    |
| de_CH       | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 52.48%  |
| EFI  | 67        | 47.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 83.57%  |
| Btrfs   | 8         | 5.71%   |
| Xfs     | 5         | 3.57%   |
| Unknown | 5         | 3.57%   |
| Overlay | 2         | 1.43%   |
| OveXlay | 1         | 0.71%   |
| Ext3    | 1         | 0.71%   |
| Ext2    | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 81        | 55.86%  |
| MBR     | 50        | 34.48%  |
| Unknown | 14        | 9.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 79.58%  |
| Yes       | 29        | 20.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 75.89%  |
| Yes       | 34        | 24.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 19.29%  |
| Dell                | 20        | 14.29%  |
| ASUSTek Computer    | 16        | 11.43%  |
| Hewlett-Packard     | 15        | 10.71%  |
| Gigabyte Technology | 12        | 8.57%   |
| MSI                 | 11        | 7.86%   |
| Acer                | 6         | 4.29%   |
| ASRock              | 4         | 2.86%   |
| Toshiba             | 3         | 2.14%   |
| Google              | 3         | 2.14%   |
| Intel               | 2         | 1.43%   |
| Fujitsu Siemens     | 2         | 1.43%   |
| AMI                 | 2         | 1.43%   |
| Teclast             | 1         | 0.71%   |
| Sun Microsystems    | 1         | 0.71%   |
| Sony                | 1         | 0.71%   |
| Samsung Electronics | 1         | 0.71%   |
| Online Labs         | 1         | 0.71%   |
| Notebook            | 1         | 0.71%   |
| Nokia               | 1         | 0.71%   |
| MTC                 | 1         | 0.71%   |
| Microsoft           | 1         | 0.71%   |
| IP3 Tech            | 1         | 0.71%   |
| IBM                 | 1         | 0.71%   |
| HUAWEI              | 1         | 0.71%   |
| Fujitsu             | 1         | 0.71%   |
| Chuwi               | 1         | 0.71%   |
| CCE                 | 1         | 0.71%   |
| Apple               | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.71%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.71%   |
| Toshiba Satellite L655                                                                   | 1         | 0.71%   |
| Teclast F6 Plus                                                                          | 1         | 0.71%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.71%   |
| Sony VPCEE23FX                                                                           | 1         | 0.71%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.71%   |
| Online Labs SR                                                                           | 1         | 0.71%   |
| Notebook W230ST                                                                          | 1         | 0.71%   |
| Nokia N900                                                                               | 1         | 0.71%   |
| MTC Montara-GML                                                                          | 1         | 0.71%   |
| MSI MS-7B84                                                                              | 1         | 0.71%   |
| MSI MS-7B53                                                                              | 1         | 0.71%   |
| MSI MS-7A38                                                                              | 1         | 0.71%   |
| MSI MS-7A36                                                                              | 1         | 0.71%   |
| MSI MS-7A34                                                                              | 1         | 0.71%   |
| MSI MS-7885                                                                              | 1         | 0.71%   |
| MSI MS-7678                                                                              | 1         | 0.71%   |
| MSI MS-7673                                                                              | 1         | 0.71%   |
| MSI MS-1688                                                                              | 1         | 0.71%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.71%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 0.71%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.71%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.71%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.71%   |
| Lenovo ThinkStation P330 Tiny 30CES09U00                                                 | 1         | 0.71%   |
| Lenovo ThinkStation P330 30C5S1LQ00                                                      | 1         | 0.71%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.71%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.71%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.71%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.71%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.71%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.71%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.71%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 0.71%   |
| Lenovo ThinkPad T560 20FJS1J200                                                          | 1         | 0.71%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 0.71%   |
| Lenovo ThinkPad T480 20L5CTO1WW                                                          | 1         | 0.71%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 11.43%  |
| Dell Latitude          | 9         | 6.43%   |
| Acer Aspire            | 5         | 3.57%   |
| Lenovo IdeaPad         | 4         | 2.86%   |
| Dell OptiPlex          | 4         | 2.86%   |
| ASUS PRIME             | 4         | 2.86%   |
| Toshiba Satellite      | 3         | 2.14%   |
| Lenovo ThinkStation    | 3         | 2.14%   |
| HP Laptop              | 3         | 2.14%   |
| HP ProBook             | 2         | 1.43%   |
| HP Pavilion            | 2         | 1.43%   |
| HP EliteDesk           | 2         | 1.43%   |
| Dell Inspiron          | 2         | 1.43%   |
| ASUS ROG               | 2         | 1.43%   |
| Teclast F6             | 1         | 0.71%   |
| Sun Microsystems Ultra | 1         | 0.71%   |
| Sony VPCEE23FX         | 1         | 0.71%   |
| Samsung 355V4C         | 1         | 0.71%   |
| Online Labs SR         | 1         | 0.71%   |
| Notebook W230ST        | 1         | 0.71%   |
| Nokia N900             | 1         | 0.71%   |
| MTC Montara-GML        | 1         | 0.71%   |
| MSI MS-7B84            | 1         | 0.71%   |
| MSI MS-7B53            | 1         | 0.71%   |
| MSI MS-7A38            | 1         | 0.71%   |
| MSI MS-7A36            | 1         | 0.71%   |
| MSI MS-7A34            | 1         | 0.71%   |
| MSI MS-7885            | 1         | 0.71%   |
| MSI MS-7678            | 1         | 0.71%   |
| MSI MS-7673            | 1         | 0.71%   |
| MSI MS-1688            | 1         | 0.71%   |
| MSI Modern             | 1         | 0.71%   |
| MSI Bravo              | 1         | 0.71%   |
| Microsoft Surface      | 1         | 0.71%   |
| Lenovo Yoga            | 1         | 0.71%   |
| Lenovo V310-14ISK      | 1         | 0.71%   |
| Lenovo S20-30          | 1         | 0.71%   |
| Lenovo G50-30          | 1         | 0.71%   |
| IP3 Tech HeroBox       | 1         | 0.71%   |
| Intel D815EEA          | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 20        | 14.29%  |
| 2019    | 14        | 10%     |
| 2012    | 13        | 9.29%   |
| 2013    | 10        | 7.14%   |
| 2011    | 10        | 7.14%   |
| 2014    | 9         | 6.43%   |
| 2017    | 8         | 5.71%   |
| 2020    | 7         | 5%      |
| 2016    | 7         | 5%      |
| 2010    | 7         | 5%      |
| 2021    | 6         | 4.29%   |
| 2015    | 5         | 3.57%   |
| 2009    | 5         | 3.57%   |
| 2022    | 4         | 2.86%   |
| 2008    | 4         | 2.86%   |
| 2006    | 3         | 2.14%   |
| 2023    | 2         | 1.43%   |
| 2007    | 2         | 1.43%   |
| 2005    | 2         | 1.43%   |
| 2000    | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 74        | 52.86%  |
| Desktop     | 55        | 39.29%  |
| Mini pc     | 5         | 3.57%   |
| Tablet      | 3         | 2.14%   |
| Convertible | 2         | 1.43%   |
| Server      | 1         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 137       | 97.86%  |
| Enabled  | 3         | 2.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 134       | 95.71%  |
| Yes  | 6         | 4.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 30        | 21.43%  |
| 4.01-8.0    | 29        | 20.71%  |
| 16.01-24.0  | 29        | 20.71%  |
| 3.01-4.0    | 19        | 13.57%  |
| 32.01-64.0  | 15        | 10.71%  |
| 1.01-2.0    | 7         | 5%      |
| 64.01-256.0 | 4         | 2.86%   |
| 2.01-3.0    | 3         | 2.14%   |
| 0.01-0.5    | 3         | 2.14%   |
| 24.01-32.0  | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 54        | 35.76%  |
| 4.01-8.0   | 28        | 18.54%  |
| 2.01-3.0   | 19        | 12.58%  |
| 3.01-4.0   | 18        | 11.92%  |
| 0.51-1.0   | 16        | 10.6%   |
| 8.01-16.0  | 8         | 5.3%    |
| 0.01-0.5   | 5         | 3.31%   |
| 16.01-24.0 | 2         | 1.32%   |
| 32.01-64.0 | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 63.12%  |
| 2      | 25        | 17.73%  |
| 3      | 14        | 9.93%   |
| 4      | 5         | 3.55%   |
| 5      | 4         | 2.84%   |
| 6      | 3         | 2.13%   |
| 7      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 65.96%  |
| Yes       | 48        | 34.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 90%     |
| No        | 14        | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 64.08%  |
| No        | 51        | 35.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 54.23%  |
| Yes       | 65        | 45.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 14.18%  |
| Germany     | 12        | 8.51%   |
| Russia      | 11        | 7.8%    |
| France      | 11        | 7.8%    |
| Ukraine     | 7         | 4.96%   |
| Brazil      | 7         | 4.96%   |
| UK          | 5         | 3.55%   |
| Slovakia    | 5         | 3.55%   |
| Poland      | 5         | 3.55%   |
| Spain       | 4         | 2.84%   |
| Netherlands | 4         | 2.84%   |
| Grenada     | 4         | 2.84%   |
| Italy       | 3         | 2.13%   |
| Australia   | 3         | 2.13%   |
| Switzerland | 2         | 1.42%   |
| Portugal    | 2         | 1.42%   |
| New Zealand | 2         | 1.42%   |
| Mexico      | 2         | 1.42%   |
| Israel      | 2         | 1.42%   |
| Indonesia   | 2         | 1.42%   |
| Hungary     | 2         | 1.42%   |
| Georgia     | 2         | 1.42%   |
| Finland     | 2         | 1.42%   |
| Belgium     | 2         | 1.42%   |
| Austria     | 2         | 1.42%   |
| Argentina   | 2         | 1.42%   |
| Vietnam     | 1         | 0.71%   |
| South Korea | 1         | 0.71%   |
| Singapore   | 1         | 0.71%   |
| Serbia      | 1         | 0.71%   |
| Romania     | 1         | 0.71%   |
| Puerto Rico | 1         | 0.71%   |
| Norway      | 1         | 0.71%   |
| Lithuania   | 1         | 0.71%   |
| India       | 1         | 0.71%   |
| Greece      | 1         | 0.71%   |
| El Salvador | 1         | 0.71%   |
| China       | 1         | 0.71%   |
| Canada      | 1         | 0.71%   |
| Bulgaria    | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Bratislava           | 5         | 3.52%   |
| Bagnolet             | 5         | 3.52%   |
| Saint George's       | 4         | 2.82%   |
| Wroclaw              | 2         | 1.41%   |
| Volzhskiy            | 2         | 1.41%   |
| Tel Aviv             | 2         | 1.41%   |
| Tbilisi              | 2         | 1.41%   |
| Sydney               | 2         | 1.41%   |
| Sao Paulo            | 2         | 1.41%   |
| Rio de Janeiro       | 2         | 1.41%   |
| Nadudvar             | 2         | 1.41%   |
| Milan                | 2         | 1.41%   |
| Madrid               | 2         | 1.41%   |
| Kyiv                 | 2         | 1.41%   |
| Ft. Washington       | 2         | 1.41%   |
| Auckland             | 2         | 1.41%   |
| Amsterdam            | 2         | 1.41%   |
| Yakutsk              | 1         | 0.7%    |
| Xiamen               | 1         | 0.7%    |
| Windisch             | 1         | 0.7%    |
| Willich              | 1         | 0.7%    |
| Wildberg             | 1         | 0.7%    |
| Waterford            | 1         | 0.7%    |
| Vladikavkaz          | 1         | 0.7%    |
| Vise                 | 1         | 0.7%    |
| Vilnius              | 1         | 0.7%    |
| Trubchëvsk          | 1         | 0.7%    |
| Toronto              | 1         | 0.7%    |
| Thessaloniki         | 1         | 0.7%    |
| Tejgaon              | 1         | 0.7%    |
| Tangerang            | 1         | 0.7%    |
| Talavera de la Reina | 1         | 0.7%    |
| Staunton             | 1         | 0.7%    |
| St Petersburg        | 1         | 0.7%    |
| Sofia                | 1         | 0.7%    |
| Singapore            | 1         | 0.7%    |
| Siena                | 1         | 0.7%    |
| Seongbuk-gu          | 1         | 0.7%    |
| Seaham               | 1         | 0.7%    |
| San Salvador         | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 59     | 18.66%  |
| Seagate             | 24        | 34     | 11.48%  |
| Samsung Electronics | 23        | 36     | 11%     |
| Kingston            | 16        | 19     | 7.66%   |
| Unknown             | 12        | 14     | 5.74%   |
| Toshiba             | 10        | 10     | 4.78%   |
| SanDisk             | 9         | 9      | 4.31%   |
| Crucial             | 8         | 10     | 3.83%   |
| Hitachi             | 6         | 6      | 2.87%   |
| SK hynix            | 5         | 5      | 2.39%   |
| PNY                 | 5         | 6      | 2.39%   |
| HGST                | 4         | 4      | 1.91%   |
| Team                | 3         | 3      | 1.44%   |
| Netac               | 3         | 3      | 1.44%   |
| LITEON              | 3         | 6      | 1.44%   |
| Fujitsu             | 3         | 3      | 1.44%   |
| Micron Technology   | 2         | 2      | 0.96%   |
| Maxtor              | 2         | 2      | 0.96%   |
| Lenovo              | 2         | 2      | 0.96%   |
| Intel               | 2         | 2      | 0.96%   |
| Hewlett-Packard     | 2         | 3      | 0.96%   |
| Dogfish             | 2         | 2      | 0.96%   |
| A-DATA Technology   | 2         | 2      | 0.96%   |
| WD MediaMax         | 1         | 3      | 0.48%   |
| Union Memory        | 1         | 2      | 0.48%   |
| UMIS                | 1         | 1      | 0.48%   |
| Transcend           | 1         | 2      | 0.48%   |
| Teclast             | 1         | 1      | 0.48%   |
| Smart               | 1         | 1      | 0.48%   |
| SABRENT             | 1         | 2      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| Mushkin             | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Kston               | 1         | 1      | 0.48%   |
| KIOXIA              | 1         | 1      | 0.48%   |
| KingFast            | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                  | 4         | 1.72%   |
| Unknown MMC Card  32GB               | 3         | 1.29%   |
| Unknown MMC Card  128GB              | 3         | 1.29%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.29%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.29%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.29%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.29%   |
| Kingston SA2000M8250G 250GB          | 3         | 1.29%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.86%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.86%   |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 0.86%   |
| Seagate ST3500418AS 500GB            | 2         | 0.86%   |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 0.86%   |
| Samsung SSD 980 1TB                  | 2         | 0.86%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.86%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.86%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB | 2         | 0.86%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.86%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.86%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.86%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.43%   |
| WDC WD800BB-00JHC0 80GB              | 1         | 0.43%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.43%   |
| WDC WD7500AALX-009BA0 752GB          | 1         | 0.43%   |
| WDC WD5001AALS-00L3B2 500GB          | 1         | 0.43%   |
| WDC WD5001AALS-00E3A0 500GB          | 1         | 0.43%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.43%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 1         | 0.43%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.43%   |
| WDC WD40EDAZ-11SLVB0 4TB             | 1         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.43%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.43%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.43%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.43%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 1         | 0.43%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 48     | 37.97%  |
| Seagate             | 23        | 33     | 29.11%  |
| Toshiba             | 7         | 7      | 8.86%   |
| Hitachi             | 6         | 6      | 7.59%   |
| HGST                | 4         | 4      | 5.06%   |
| Fujitsu             | 3         | 3      | 3.8%    |
| Maxtor              | 2         | 2      | 2.53%   |
| Samsung Electronics | 1         | 1      | 1.27%   |
| IBM/Hitachi         | 1         | 1      | 1.27%   |
| HPE                 | 1         | 2      | 1.27%   |
| Hewlett-Packard     | 1         | 2      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 17     | 18.07%  |
| Kingston            | 13        | 15     | 15.66%  |
| SanDisk             | 6         | 6      | 7.23%   |
| Crucial             | 6         | 7      | 7.23%   |
| WDC                 | 5         | 6      | 6.02%   |
| PNY                 | 5         | 6      | 6.02%   |
| Team                | 3         | 3      | 3.61%   |
| Netac               | 3         | 3      | 3.61%   |
| SK hynix            | 2         | 2      | 2.41%   |
| Micron Technology   | 2         | 2      | 2.41%   |
| LITEON              | 2         | 5      | 2.41%   |
| Dogfish             | 2         | 2      | 2.41%   |
| A-DATA Technology   | 2         | 2      | 2.41%   |
| Union Memory        | 1         | 2      | 1.2%    |
| Transcend           | 1         | 2      | 1.2%    |
| Teclast             | 1         | 1      | 1.2%    |
| Smart               | 1         | 1      | 1.2%    |
| SABRENT             | 1         | 2      | 1.2%    |
| Plextor             | 1         | 1      | 1.2%    |
| Patriot             | 1         | 1      | 1.2%    |
| Mushkin             | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| Kston               | 1         | 1      | 1.2%    |
| KingDian            | 1         | 1      | 1.2%    |
| Intenso             | 1         | 1      | 1.2%    |
| HXY                 | 1         | 1      | 1.2%    |
| Hewlett-Packard     | 1         | 1      | 1.2%    |
| GOODRAM             | 1         | 1      | 1.2%    |
| Emtec               | 1         | 1      | 1.2%    |
| China               | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 73        | 96     | 38.62%  |
| HDD     | 65        | 109    | 34.39%  |
| NVMe    | 36        | 46     | 19.05%  |
| MMC     | 12        | 14     | 6.35%   |
| Unknown | 3         | 5      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 200    | 67.27%  |
| NVMe | 36        | 46     | 21.82%  |
| MMC  | 12        | 14     | 7.27%   |
| SAS  | 6         | 10     | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 121    | 63.04%  |
| 0.51-1.0   | 30        | 54     | 21.74%  |
| 1.01-2.0   | 12        | 19     | 8.7%    |
| 3.01-4.0   | 6         | 7      | 4.35%   |
| 2.01-3.0   | 1         | 1      | 0.72%   |
| 10.01-20.0 | 1         | 2      | 0.72%   |
| 4.01-10.0  | 1         | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 34        | 23.29%  |
| 101-250        | 29        | 19.86%  |
| 501-1000       | 21        | 14.38%  |
| 1001-2000      | 17        | 11.64%  |
| 21-50          | 12        | 8.22%   |
| 51-100         | 11        | 7.53%   |
| More than 3000 | 8         | 5.48%   |
| Unknown        | 6         | 4.11%   |
| 2001-3000      | 4         | 2.74%   |
| 1-20           | 4         | 2.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 41        | 28.08%  |
| 101-250        | 32        | 21.92%  |
| 21-50          | 15        | 10.27%  |
| 251-500        | 14        | 9.59%   |
| 51-100         | 13        | 8.9%    |
| 501-1000       | 10        | 6.85%   |
| 1001-2000      | 9         | 6.16%   |
| Unknown        | 6         | 4.11%   |
| More than 3000 | 3         | 2.05%   |
| 2001-3000      | 3         | 2.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB          | 2         | 2      | 9.52%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 4.76%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 4.76%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 4.76%   |
| WDC WD10EARX-00N0YB0 1TB              | 1         | 1      | 4.76%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 4.76%   |
| Toshiba MQ02ABF100 1TB                | 1         | 1      | 4.76%   |
| SK hynix SH920 mSATA 128GB SSD        | 1         | 1      | 4.76%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 4.76%   |
| Maxtor 6E040L0 41GB                   | 1         | 1      | 4.76%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 4.76%   |
| HPE MB4000GEFNA 4TB                   | 1         | 2      | 4.76%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 4.76%   |
| Hitachi HTS726060M9AT00 56GB          | 1         | 1      | 4.76%   |
| Hitachi HDS721616PLA380 160GB         | 1         | 1      | 4.76%   |
| HGST HTE721010A9E630 1TB              | 1         | 1      | 4.76%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1         | 2      | 4.76%   |
| Fujitsu MHV2060BH PL 64GB             | 1         | 1      | 4.76%   |
| China SSD 256GB                       | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 28.57%  |
| Hitachi             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Seagate             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Maxtor              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| HPE                 | 1         | 2      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 2      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 35.29%  |
| Hitachi         | 3         | 3      | 17.65%  |
| Toshiba         | 2         | 2      | 11.76%  |
| Seagate         | 1         | 1      | 5.88%   |
| Maxtor          | 1         | 1      | 5.88%   |
| HPE             | 1         | 2      | 5.88%   |
| HGST            | 1         | 1      | 5.88%   |
| Hewlett-Packard | 1         | 2      | 5.88%   |
| Fujitsu         | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 19     | 80.95%  |
| SSD  | 3         | 3      | 14.29%  |
| NVMe | 1         | 1      | 4.76%   |

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
| Works    | 108       | 191    | 66.26%  |
| Detected | 35        | 56     | 21.47%  |
| Malfunc  | 20        | 23     | 12.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 57.74%  |
| AMD                              | 24        | 14.29%  |
| Samsung Electronics              | 11        | 6.55%   |
| SanDisk                          | 8         | 4.76%   |
| Kingston Technology Company      | 4         | 2.38%   |
| Toshiba America Info Systems     | 3         | 1.79%   |
| SK hynix                         | 3         | 1.79%   |
| Micron/Crucial Technology        | 2         | 1.19%   |
| Marvell Technology Group         | 2         | 1.19%   |
| Lenovo                           | 2         | 1.19%   |
| VIA Technologies                 | 1         | 0.6%    |
| Union Memory (Shenzhen)          | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Nvidia                           | 1         | 0.6%    |
| LSI Logic / Symbios Logic        | 1         | 0.6%    |
| Lite-On Technology               | 1         | 0.6%    |
| KIOXIA                           | 1         | 0.6%    |
| Integrated Technology Express    | 1         | 0.6%    |
| Chelsio Communications           | 1         | 0.6%    |
| Broadcom / LSI                   | 1         | 0.6%    |
| ASMedia Technology               | 1         | 0.6%    |
| Adaptec                          | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17        | 8.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 4.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 3.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 3.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.05%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 2.05%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 2.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 2.05%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 1.03%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.03%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 1.03%   |
| Lenovo Non-Volatile memory controller                                                   | 2         | 1.03%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.03%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                  | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.03%   |
| AMD FCH SATA Controller D                                                               | 2         | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.03%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 99        | 58.58%  |
| NVMe | 36        | 21.3%   |
| IDE  | 21        | 12.43%  |
| RAID | 11        | 6.51%   |
| SCSI | 2         | 1.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 79.29%  |
| AMD    | 28        | 20%     |
| ARM    | 1         | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.13%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.42%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.42%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.42%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.42%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.42%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.71%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1         | 0.71%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.71%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.71%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.71%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.71%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.71%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.71%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.71%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.71%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.71%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.71%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.71%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.71%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.71%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.71%   |
| Intel Core i7-8700T CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.71%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 20.57%  |
| Intel Core i7           | 26        | 18.44%  |
| Intel Core i3           | 13        | 9.22%   |
| Intel Celeron           | 10        | 7.09%   |
| AMD Ryzen 5             | 8         | 5.67%   |
| Other                   | 5         | 3.55%   |
| Intel Xeon              | 5         | 3.55%   |
| AMD Ryzen 7             | 5         | 3.55%   |
| Intel Core 2 Duo        | 4         | 2.84%   |
| Intel Pentium           | 3         | 2.13%   |
| Intel Core 2            | 3         | 2.13%   |
| Intel Atom              | 3         | 2.13%   |
| Intel Pentium M         | 2         | 1.42%   |
| Intel Pentium Dual-Core | 2         | 1.42%   |
| Intel Pentium Dual      | 2         | 1.42%   |
| Intel Core i9           | 2         | 1.42%   |
| AMD Ryzen 3             | 2         | 1.42%   |
| Intel Pentium Silver    | 1         | 0.71%   |
| Intel Pentium Gold      | 1         | 0.71%   |
| Intel Pentium 4         | 1         | 0.71%   |
| Intel Core 2 Quad       | 1         | 0.71%   |
| Intel Celeron M         | 1         | 0.71%   |
| AMD Sempron             | 1         | 0.71%   |
| AMD Ryzen Threadripper  | 1         | 0.71%   |
| AMD Ryzen 7 PRO         | 1         | 0.71%   |
| AMD FX                  | 1         | 0.71%   |
| AMD E2                  | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |
| AMD Athlon II           | 1         | 0.71%   |
| AMD Athlon              | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A6                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |
| AMD A10                 | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 60        | 42.86%  |
| 4      | 45        | 32.14%  |
| 6      | 18        | 12.86%  |
| 1      | 8         | 5.71%   |
| 8      | 6         | 4.29%   |
| 12     | 2         | 1.43%   |
| 10     | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 57.86%  |
| 1      | 59        | 42.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 133       | 95%     |
| 32-bit         | 4         | 2.86%   |
| Unknown        | 3         | 2.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 22.92%  |
| 0x306c3    | 9         | 6.25%   |
| 0x206a7    | 8         | 5.56%   |
| 0x906ea    | 7         | 4.86%   |
| 0x306a9    | 7         | 4.86%   |
| 0x1067a    | 6         | 4.17%   |
| 0x406e3    | 5         | 3.47%   |
| 0x806ec    | 4         | 2.78%   |
| 0x706a1    | 3         | 2.08%   |
| 0x406c4    | 3         | 2.08%   |
| 0x40651    | 3         | 2.08%   |
| 0x306d4    | 3         | 2.08%   |
| 0x906ed    | 2         | 1.39%   |
| 0x806ea    | 2         | 1.39%   |
| 0x706a8    | 2         | 1.39%   |
| 0x6f6      | 2         | 1.39%   |
| 0x506e3    | 2         | 1.39%   |
| 0x30678    | 2         | 1.39%   |
| 0x20655    | 2         | 1.39%   |
| 0x106e5    | 2         | 1.39%   |
| 0x08701021 | 2         | 1.39%   |
| 0x08608103 | 2         | 1.39%   |
| 0x0810100b | 2         | 1.39%   |
| 0x0800820d | 2         | 1.39%   |
| 0xf49      | 1         | 0.69%   |
| 0xa0655    | 1         | 0.69%   |
| 0xa0653    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x906a3    | 1         | 0.69%   |
| 0x806c1    | 1         | 0.69%   |
| 0x6fd      | 1         | 0.69%   |
| 0x6d8      | 1         | 0.69%   |
| 0x695      | 1         | 0.69%   |
| 0x686      | 1         | 0.69%   |
| 0x506c9    | 1         | 0.69%   |
| 0x406d8    | 1         | 0.69%   |
| 0x306f2    | 1         | 0.69%   |
| 0x20652    | 1         | 0.69%   |
| 0x10676    | 1         | 0.69%   |
| 0x0a601203 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 14.18%  |
| Haswell          | 16        | 11.35%  |
| IvyBridge        | 10        | 7.09%   |
| Skylake          | 9         | 6.38%   |
| Silvermont       | 8         | 5.67%   |
| SandyBridge      | 8         | 5.67%   |
| Penryn           | 7         | 4.96%   |
| Zen 2            | 5         | 3.55%   |
| Zen              | 5         | 3.55%   |
| Westmere         | 5         | 3.55%   |
| Goldmont plus    | 5         | 3.55%   |
| Unknown          | 5         | 3.55%   |
| Zen+             | 4         | 2.84%   |
| P6               | 4         | 2.84%   |
| Nehalem          | 4         | 2.84%   |
| Core             | 4         | 2.84%   |
| Broadwell        | 4         | 2.84%   |
| TigerLake        | 2         | 1.42%   |
| Piledriver       | 2         | 1.42%   |
| Excavator        | 2         | 1.42%   |
| CometLake        | 2         | 1.42%   |
| Bobcat           | 2         | 1.42%   |
| Zen 3            | 1         | 0.71%   |
| Puma             | 1         | 0.71%   |
| NetBurst         | 1         | 0.71%   |
| K8 Hammer        | 1         | 0.71%   |
| K10 Llano        | 1         | 0.71%   |
| K10              | 1         | 0.71%   |
| Goldmont         | 1         | 0.71%   |
| Alderlake Hybrid | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 55.26%  |
| AMD                              | 37        | 24.34%  |
| Nvidia                           | 30        | 19.74%  |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.13%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.88%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.25%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.25%   |
| Intel HD Graphics 620                                                                    | 2         | 1.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.25%   |
| AMD Renoir                                                                               | 2         | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.25%   |
| AMD Lucienne                                                                             | 2         | 1.25%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.63%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.63%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.63%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.63%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.63%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.63%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 47.86%  |
| 1 x AMD        | 29        | 20.71%  |
| 1 x Nvidia     | 20        | 14.29%  |
| Intel + Nvidia | 10        | 7.14%   |
| 2 x AMD        | 5         | 3.57%   |
| Other          | 4         | 2.86%   |
| Intel + AMD    | 3         | 2.14%   |
| 2 x Intel      | 1         | 0.71%   |
| 1 x SiS        | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 118       | 83.69%  |
| Proprietary | 16        | 11.35%  |
| Unknown     | 7         | 4.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 62.24%  |
| 0.01-0.5   | 18        | 12.59%  |
| 0.51-1.0   | 10        | 6.99%   |
| 3.01-4.0   | 9         | 6.29%   |
| 1.01-2.0   | 7         | 4.9%    |
| 7.01-8.0   | 5         | 3.5%    |
| 2.01-3.0   | 3         | 2.1%    |
| 5.01-6.0   | 2         | 1.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 13.16%  |
| LG Display              | 19        | 12.5%   |
| AU Optronics            | 18        | 11.84%  |
| Chimei Innolux          | 11        | 7.24%   |
| Hewlett-Packard         | 9         | 5.92%   |
| BOE                     | 7         | 4.61%   |
| Philips                 | 6         | 3.95%   |
| Goldstar                | 6         | 3.95%   |
| Dell                    | 6         | 3.95%   |
| Acer                    | 6         | 3.95%   |
| Lenovo                  | 5         | 3.29%   |
| Unknown                 | 4         | 2.63%   |
| PANDA                   | 4         | 2.63%   |
| Iiyama                  | 4         | 2.63%   |
| AOC                     | 4         | 2.63%   |
| Ancor Communications    | 3         | 1.97%   |
| MStar                   | 2         | 1.32%   |
| Chi Mei Optoelectronics | 2         | 1.32%   |
| ___                     | 1         | 0.66%   |
| ViewSonic               | 1         | 0.66%   |
| Toshiba                 | 1         | 0.66%   |
| STD                     | 1         | 0.66%   |
| Sony                    | 1         | 0.66%   |
| Sharp                   | 1         | 0.66%   |
| MSI                     | 1         | 0.66%   |
| InnoLux Display         | 1         | 0.66%   |
| InfoVision              | 1         | 0.66%   |
| HJW                     | 1         | 0.66%   |
| Hisense                 | 1         | 0.66%   |
| eMachines               | 1         | 0.66%   |
| Eizo                    | 1         | 0.66%   |
| CVT                     | 1         | 0.66%   |
| CHI                     | 1         | 0.66%   |
| BenQ                    | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 1.28%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.28%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch      | 2         | 1.28%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 2         | 1.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.28%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.28%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                      | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 2         | 1.28%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 0.64%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                 | 1         | 0.64%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.64%   |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1         | 0.64%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.64%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                      | 1         | 0.64%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                          | 1         | 0.64%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.64%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.64%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0503 1920x1080                      | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.64%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.64%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.64%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.64%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1         | 0.64%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1         | 0.64%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1         | 0.64%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 41.89%  |
| 1366x768 (WXGA)    | 37        | 25%     |
| 3840x2160 (4K)     | 9         | 6.08%   |
| 1600x900 (HD+)     | 6         | 4.05%   |
| 1440x900 (WXGA+)   | 6         | 4.05%   |
| 1280x1024 (SXGA)   | 6         | 4.05%   |
| 1920x1200 (WUXGA)  | 3         | 2.03%   |
| 3440x1440          | 2         | 1.35%   |
| 2288x1287          | 2         | 1.35%   |
| 1600x1200          | 2         | 1.35%   |
| 1280x800 (WXGA)    | 2         | 1.35%   |
| Unknown            | 2         | 1.35%   |
| 5760x1080          | 1         | 0.68%   |
| 3000x2000          | 1         | 0.68%   |
| 2736x1824          | 1         | 0.68%   |
| 2560x1440 (QHD)    | 1         | 0.68%   |
| 2160x1440          | 1         | 0.68%   |
| 2048x1152          | 1         | 0.68%   |
| 1680x1050 (WSXGA+) | 1         | 0.68%   |
| 1360x768           | 1         | 0.68%   |
| 1024x768 (XGA)     | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 21.48%  |
| 21      | 15        | 10.07%  |
| 24      | 13        | 8.72%   |
| 14      | 13        | 8.72%   |
| 13      | 11        | 7.38%   |
| 12      | 10        | 6.71%   |
| 27      | 8         | 5.37%   |
| 23      | 8         | 5.37%   |
| Unknown | 7         | 4.7%    |
| 17      | 6         | 4.03%   |
| 19      | 4         | 2.68%   |
| 11      | 4         | 2.68%   |
| 31      | 3         | 2.01%   |
| 18      | 3         | 2.01%   |
| 142     | 2         | 1.34%   |
| 72      | 2         | 1.34%   |
| 52      | 2         | 1.34%   |
| 34      | 2         | 1.34%   |
| 54      | 1         | 0.67%   |
| 40      | 1         | 0.67%   |
| 22      | 1         | 0.67%   |
| 20      | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 50        | 34.48%  |
| 501-600        | 28        | 19.31%  |
| 201-300        | 21        | 14.48%  |
| 401-500        | 20        | 13.79%  |
| Unknown        | 7         | 4.83%   |
| 351-400        | 6         | 4.14%   |
| 601-700        | 3         | 2.07%   |
| 1001-1500      | 3         | 2.07%   |
| More than 2000 | 2         | 1.38%   |
| 701-800        | 2         | 1.38%   |
| 1501-2000      | 2         | 1.38%   |
| 801-900        | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 77.44%  |
| 16/10   | 10        | 7.52%   |
| Unknown | 5         | 3.76%   |
| 4/3     | 4         | 3.01%   |
| 5/4     | 3         | 2.26%   |
| 3/2     | 3         | 2.26%   |
| 21/9    | 2         | 1.5%    |
| 1.00    | 2         | 1.5%    |
| 6/5     | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 33        | 22.3%   |
| 101-110        | 30        | 20.27%  |
| 81-90          | 17        | 11.49%  |
| 61-70          | 10        | 6.76%   |
| 301-350        | 8         | 5.41%   |
| More than 1000 | 7         | 4.73%   |
| 71-80          | 7         | 4.73%   |
| 151-200        | 7         | 4.73%   |
| Unknown        | 7         | 4.73%   |
| 351-500        | 5         | 3.38%   |
| 51-60          | 4         | 2.7%    |
| 141-150        | 4         | 2.7%    |
| 121-130        | 3         | 2.03%   |
| 251-300        | 2         | 1.35%   |
| 111-120        | 2         | 1.35%   |
| 131-140        | 1         | 0.68%   |
| 501-1000       | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 44        | 30.14%  |
| 101-120       | 43        | 29.45%  |
| 121-160       | 35        | 23.97%  |
| 161-240       | 8         | 5.48%   |
| 1-50          | 7         | 4.79%   |
| Unknown       | 7         | 4.79%   |
| More than 240 | 2         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 113       | 79.02%  |
| 2     | 21        | 14.69%  |
| 3     | 5         | 3.5%    |
| 0     | 4         | 2.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 33.99%  |
| Realtek Semiconductor            | 66        | 32.51%  |
| Qualcomm Atheros                 | 27        | 13.3%   |
| Broadcom                         | 7         | 3.45%   |
| Ralink Technology                | 5         | 2.46%   |
| Samsung Electronics              | 3         | 1.48%   |
| MediaTek                         | 3         | 1.48%   |
| Marvell Technology Group         | 3         | 1.48%   |
| TP-Link                          | 2         | 0.99%   |
| Sierra Wireless                  | 2         | 0.99%   |
| NetGear                          | 2         | 0.99%   |
| JMicron Technology               | 2         | 0.99%   |
| Broadcom Limited                 | 2         | 0.99%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.49%   |
| VIA Technologies                 | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Ralink                           | 1         | 0.49%   |
| Nvidia                           | 1         | 0.49%   |
| Huawei Technologies              | 1         | 0.49%   |
| DisplayLink                      | 1         | 0.49%   |
| Dell                             | 1         | 0.49%   |
| Chelsio Communications           | 1         | 0.49%   |
| ASIX Electronics                 | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 47        | 19.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.09%   |
| Intel Wireless 7260                                                     | 5         | 2.09%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 2.09%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 2.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.67%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.67%   |
| Intel Wireless 7265                                                     | 4         | 1.67%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 1.26%   |
| Intel Wireless 8260                                                     | 3         | 1.26%   |
| Intel Ethernet Controller I225-V                                        | 3         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.26%   |
| Sierra Wireless EM7455                                                  | 2         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.84%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.84%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 0.84%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.84%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.84%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.84%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.84%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.84%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                     | 1         | 0.42%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 38.54%  |
| Qualcomm Atheros         | 24        | 25%     |
| Realtek Semiconductor    | 13        | 13.54%  |
| Ralink Technology        | 5         | 5.21%   |
| Broadcom                 | 4         | 4.17%   |
| MediaTek                 | 3         | 3.13%   |
| Sierra Wireless          | 2         | 2.08%   |
| NetGear                  | 2         | 2.08%   |
| Broadcom Limited         | 2         | 2.08%   |
| TP-Link                  | 1         | 1.04%   |
| Ralink                   | 1         | 1.04%   |
| Marvell Technology Group | 1         | 1.04%   |
| Dell                     | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.21%   |
| Intel Wireless 7260                                                     | 5         | 5.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 5.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 4         | 4.17%   |
| Intel Wireless 7265                                                     | 4         | 4.17%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 4.17%   |
| Intel Wireless 8260                                                     | 3         | 3.13%   |
| Sierra Wireless EM7455                                                  | 2         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.08%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.08%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 2.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.08%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.04%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.04%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.04%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.04%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.04%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.04%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.04%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 43.07%  |
| Intel                            | 54        | 39.42%  |
| Qualcomm Atheros                 | 5         | 3.65%   |
| Samsung Electronics              | 3         | 2.19%   |
| Broadcom                         | 3         | 2.19%   |
| Marvell Technology Group         | 2         | 1.46%   |
| JMicron Technology               | 2         | 1.46%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.73%   |
| VIA Technologies                 | 1         | 0.73%   |
| TP-Link                          | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] | 1         | 0.73%   |
| Nvidia                           | 1         | 0.73%   |
| Huawei Technologies              | 1         | 0.73%   |
| DisplayLink                      | 1         | 0.73%   |
| Chelsio Communications           | 1         | 0.73%   |
| ASIX Electronics                 | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 33.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 7.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5%      |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 3.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.14%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.43%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.43%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 0.71%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.71%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.71%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.71%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.71%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.71%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 57.27%  |
| WiFi     | 91        | 41.36%  |
| Modem    | 3         | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 53.15%  |
| WiFi     | 67        | 46.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 74        | 52.11%  |
| 1     | 60        | 42.25%  |
| 0     | 4         | 2.82%   |
| 3     | 2         | 1.41%   |
| 7     | 1         | 0.7%    |
| 5     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 87.14%  |
| Yes  | 18        | 12.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 40.91%  |
| Qualcomm Atheros Communications | 7         | 10.61%  |
| Realtek Semiconductor           | 6         | 9.09%   |
| Broadcom                        | 4         | 6.06%   |
| Lite-On Technology              | 3         | 4.55%   |
| IMC Networks                    | 3         | 4.55%   |
| Cambridge Silicon Radio         | 3         | 4.55%   |
| Foxconn International           | 2         | 3.03%   |
| Foxconn / Hon Hai               | 2         | 3.03%   |
| Dell                            | 2         | 3.03%   |
| ASUSTek Computer                | 2         | 3.03%   |
| Realtek                         | 1         | 1.52%   |
| Ralink                          | 1         | 1.52%   |
| MediaTek                        | 1         | 1.52%   |
| Marvell Semiconductor           | 1         | 1.52%   |
| Apple                           | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 21.21%  |
| Realtek Bluetooth Radio                             | 6         | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.06%   |
| Intel AX200 Bluetooth                               | 4         | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.03%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 3.03%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 3.03%   |
| ASUS ASUS USB-BT500                                 | 2         | 3.03%   |
| Realtek Bluetooth Radio                             | 1         | 1.52%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.52%   |
| MediaTek Wireless_Device                            | 1         | 1.52%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.52%   |
| Intel Bluetooth Device                              | 1         | 1.52%   |
| Intel AX201 Bluetooth                               | 1         | 1.52%   |
| IMC Networks Bluetooth Device                       | 1         | 1.52%   |
| IMC Networks BCM20702A0                             | 1         | 1.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.52%   |
| Foxconn / Hon Hai BT                                | 1         | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.52%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 55.38%  |
| AMD                              | 33        | 17.74%  |
| Nvidia                           | 23        | 12.37%  |
| Creative Labs                    | 4         | 2.15%   |
| C-Media Electronics              | 4         | 2.15%   |
| Plantronics                      | 2         | 1.08%   |
| Texas Instruments                | 1         | 0.54%   |
| TEAC                             | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Sennheiser Communications        | 1         | 0.54%   |
| Realtek Semiconductor            | 1         | 0.54%   |
| M-Audio                          | 1         | 0.54%   |
| Logitech                         | 1         | 0.54%   |
| KORG                             | 1         | 0.54%   |
| GYROCOM C&C                      | 1         | 0.54%   |
| Giga-Byte Technology             | 1         | 0.54%   |
| Focusrite-Novation               | 1         | 0.54%   |
| Elite Silicon                    | 1         | 0.54%   |
| DCMT Technology                  | 1         | 0.54%   |
| Cirrus Logic                     | 1         | 0.54%   |
| Blue Microphones                 | 1         | 0.54%   |
| Avance Logic                     | 1         | 0.54%   |
| ASUSTek Computer                 | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 4.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 3.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 3.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.77%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.77%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.77%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.33%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.33%   |
| Plantronics HD1                                                            | 2         | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.88%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 0.88%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 0.88%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.88%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 20.98%  |
| Unknown             | 21        | 14.69%  |
| SK hynix            | 18        | 12.59%  |
| Kingston            | 18        | 12.59%  |
| Corsair             | 12        | 8.39%   |
| Micron Technology   | 8         | 5.59%   |
| G.Skill             | 7         | 4.9%    |
| Crucial             | 6         | 4.2%    |
| A-DATA Technology   | 6         | 4.2%    |
| Unknown (ABCD)      | 3         | 2.1%    |
| Nanya Technology    | 3         | 2.1%    |
| Ramaxel Technology  | 2         | 1.4%    |
| Unknown             | 2         | 1.4%    |
| Unknown (130B)      | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| Smart               | 1         | 0.7%    |
| GOODRAM             | 1         | 0.7%    |
| Avant               | 1         | 0.7%    |
| Apacer              | 1         | 0.7%    |
| 4ea5                | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.23%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.23%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.23%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 1.23%   |
| Unknown                                                          | 2         | 1.23%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.61%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 0.61%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.61%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.61%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 0.61%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s               | 1         | 0.61%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.61%   |
| Unknown (130B) RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s           | 1         | 0.61%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 51        | 41.13%  |
| DDR4    | 49        | 39.52%  |
| SDRAM   | 4         | 3.23%   |
| LPDDR4  | 4         | 3.23%   |
| LPDDR3  | 4         | 3.23%   |
| DDR     | 4         | 3.23%   |
| DDR2    | 3         | 2.42%   |
| Unknown | 3         | 2.42%   |
| DRAM    | 1         | 0.81%   |
| DDR5    | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 54.47%  |
| DIMM         | 50        | 40.65%  |
| Row Of Chips | 4         | 3.25%   |
| Chip         | 1         | 0.81%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 51        | 36.43%  |
| 4096  | 37        | 26.43%  |
| 16384 | 22        | 15.71%  |
| 2048  | 18        | 12.86%  |
| 1024  | 5         | 3.57%   |
| 32768 | 3         | 2.14%   |
| 512   | 1         | 0.71%   |
| 256   | 1         | 0.71%   |
| 128   | 1         | 0.71%   |
| 64    | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 25.19%  |
| 2667    | 22        | 16.3%   |
| 2400    | 13        | 9.63%   |
| 3200    | 9         | 6.67%   |
| 1333    | 9         | 6.67%   |
| 2133    | 7         | 5.19%   |
| Unknown | 7         | 5.19%   |
| 3600    | 4         | 2.96%   |
| 1067    | 4         | 2.96%   |
| 3400    | 3         | 2.22%   |
| 1867    | 3         | 2.22%   |
| 4199    | 2         | 1.48%   |
| 3266    | 2         | 1.48%   |
| 1800    | 2         | 1.48%   |
| 1066    | 2         | 1.48%   |
| 800     | 2         | 1.48%   |
| 667     | 2         | 1.48%   |
| 4800    | 1         | 0.74%   |
| 3666    | 1         | 0.74%   |
| 3534    | 1         | 0.74%   |
| 2933    | 1         | 0.74%   |
| 1334    | 1         | 0.74%   |
| 1200    | 1         | 0.74%   |
| 400     | 1         | 0.74%   |
| 100     | 1         | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 32.47%  |
| Microdia                               | 8         | 10.39%  |
| Sunplus Innovation Technology          | 5         | 6.49%   |
| Logitech                               | 5         | 6.49%   |
| Realtek Semiconductor                  | 4         | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.19%   |
| IMC Networks                           | 3         | 3.9%    |
| Bison Electronics                      | 3         | 3.9%    |
| Acer                                   | 3         | 3.9%    |
| Suyin                                  | 2         | 2.6%    |
| Lite-On Technology                     | 2         | 2.6%    |
| KYE Systems (Mouse Systems)            | 2         | 2.6%    |
| Cubeternet                             | 2         | 2.6%    |
| Z-Star Microelectronics                | 1         | 1.3%    |
| Softkinetic                            | 1         | 1.3%    |
| Samsung Electronics                    | 1         | 1.3%    |
| Quanta                                 | 1         | 1.3%    |
| Mustek Systems                         | 1         | 1.3%    |
| Microsoft                              | 1         | 1.3%    |
| MacroSilicon                           | 1         | 1.3%    |
| Hauppauge                              | 1         | 1.3%    |
| GEMBIRD                                | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 8         | 10.39%  |
| Logitech HD Pro Webcam C920               | 3         | 3.9%    |
| Chicony HD WebCam                         | 3         | 3.9%    |
| Cubeternet GL-UPC822 UVC WebCam           | 2         | 2.6%    |
| Chicony HP TrueVision HD Camera           | 2         | 2.6%    |
| Chicony EasyCamera                        | 2         | 2.6%    |
| Acer BisonCam, NB Pro                     | 2         | 2.6%    |
| Z-Star A4 TECH USB2.0 PC Camera E         | 1         | 1.3%    |
| Suyin Acer/Lenovo Webcam [CN0316]         | 1         | 1.3%    |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 1         | 1.3%    |
| Sunplus Laptop Integrated Webcam HD       | 1         | 1.3%    |
| Sunplus Integrated_Webcam_HD              | 1         | 1.3%    |
| Sunplus FHD Camera Microphone             | 1         | 1.3%    |
| Sunplus Asus Webcam                       | 1         | 1.3%    |
| Sunplus 720p HD Camera                    | 1         | 1.3%    |
| Softkinetic DepthSense 325                | 1         | 1.3%    |
| Samsung Galaxy series, misc. (MTP mode)   | 1         | 1.3%    |
| Realtek Lenovo EasyCamera                 | 1         | 1.3%    |
| Realtek Integrated_Webcam_HD              | 1         | 1.3%    |
| Realtek Integrated Webcam_HD              | 1         | 1.3%    |
| Realtek HD 720P Webcam                    | 1         | 1.3%    |
| Quanta Sony Visual Communication Camera   | 1         | 1.3%    |
| Mustek Systems USB 2.0 PC Camera          | 1         | 1.3%    |
| Microsoft LifeCam Studio                  | 1         | 1.3%    |
| Microdia Webcam Vitade AF                 | 1         | 1.3%    |
| Microdia WebCam SC-13HDL12639P            | 1         | 1.3%    |
| Microdia Sonix USB 2.0 Camera             | 1         | 1.3%    |
| Microdia Integrated_Webcam_HD             | 1         | 1.3%    |
| Microdia Integrated Webcam                | 1         | 1.3%    |
| Microdia Dell Integrated HD Webcam        | 1         | 1.3%    |
| Microdia Camera                           | 1         | 1.3%    |
| Microdia 1.3 MPixel Integrated Webcam     | 1         | 1.3%    |
| MacroSilicon usb video                    | 1         | 1.3%    |
| Logitech Webcam C270                      | 1         | 1.3%    |
| Logitech BRIO Ultra HD Webcam             | 1         | 1.3%    |
| Lite-On HP Wide Vision HD Camera          | 1         | 1.3%    |
| Lite-On HP HD Webcam                      | 1         | 1.3%    |
| KYE Systems (Mouse Systems) PC-W3 Camera  | 1         | 1.3%    |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1         | 1.3%    |
| IMC Networks Lenovo EasyCamera            | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 20%     |
| Upek                       | 1         | 20%     |
| Synaptics                  | 1         | 20%     |
| STMicroelectronics         | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 57.14%  |
| Alcor Micro | 5         | 35.71%  |
| Lenovo      | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 35.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 14.29%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 107       | 74.83%  |
| 1     | 25        | 17.48%  |
| 2     | 7         | 4.9%    |
| 3     | 3         | 2.1%    |
| 5     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 9         | 21.95%  |
| Graphics card            | 8         | 19.51%  |
| Fingerprint reader       | 5         | 12.2%   |
| Net/wireless             | 4         | 9.76%   |
| Communication controller | 4         | 9.76%   |
| Camera                   | 3         | 7.32%   |
| Unassigned class         | 2         | 4.88%   |
| Multimedia controller    | 2         | 4.88%   |
| Bluetooth                | 2         | 4.88%   |
| Net/ethernet             | 1         | 2.44%   |
| Firewire controller      | 1         | 2.44%   |


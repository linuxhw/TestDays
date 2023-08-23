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

Total: 194

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | T200TA                      | Notebook    | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Supermicro    | X10SRG-F                    | Desktop     | [3bdaa7bfef](https://linux-hardware.org/?probe=3bdaa7bfef) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [67febbf0c0](https://linux-hardware.org/?probe=67febbf0c0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [606780c010](https://linux-hardware.org/?probe=606780c010) | Jul 24, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Dell          | Latitude E5500              | Notebook    | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Nokia         | N900                        | Notebook    | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | Notebook    | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 77        | 48.43%  |
| Devuan 3                | 31        | 19.5%   |
| Devuan 5                | 22        | 13.84%  |
| Devuan Testing/unstable | 15        | 9.43%   |
| Devuan 2.1              | 7         | 4.4%    |
| Devuan                  | 3         | 1.89%   |
| Devuan 6                | 1         | 0.63%   |
| Devuan 3.0              | 1         | 0.63%   |
| Devuan 2.0              | 1         | 0.63%   |
| Devuan 1.0.0            | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 151       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 13        | 7.69%   |
| 5.10.0-9-amd64        | 10        | 5.92%   |
| 5.10.0-8-amd64        | 7         | 4.14%   |
| 5.10.0-23-amd64       | 6         | 3.55%   |
| 5.10.0-16-amd64       | 6         | 3.55%   |
| 4.19.0-9-amd64        | 6         | 3.55%   |
| 4.19.0-14-amd64       | 6         | 3.55%   |
| 4.19.0-16-amd64       | 5         | 2.96%   |
| 5.10.0-19-amd64       | 4         | 2.37%   |
| 5.10.0-18-amd64       | 4         | 2.37%   |
| 5.10.0-13-amd64       | 4         | 2.37%   |
| 5.10.0-11-amd64       | 4         | 2.37%   |
| 5.10.0-10-amd64       | 4         | 2.37%   |
| 6.1.0-6-amd64         | 3         | 1.78%   |
| 5.7.0-2-amd64         | 3         | 1.78%   |
| 5.10.0-20-amd64       | 3         | 1.78%   |
| 4.19.0-12-amd64       | 3         | 1.78%   |
| 4.19.0-10-amd64       | 3         | 1.78%   |
| 6.0.0-5-amd64         | 2         | 1.18%   |
| 5.7.0-0.bpo.2-amd64   | 2         | 1.18%   |
| 5.18.0-2-amd64        | 2         | 1.18%   |
| 5.18.0-1-amd64        | 2         | 1.18%   |
| 5.15.0-2-amd64        | 2         | 1.18%   |
| 5.10.0-6-amd64        | 2         | 1.18%   |
| 5.10.0-15-amd64       | 2         | 1.18%   |
| 5.10.0-14-amd64       | 2         | 1.18%   |
| 4.19.0-17-amd64       | 2         | 1.18%   |
| 4.19.0-13-amd64       | 2         | 1.18%   |
| 6.3.0-2-amd64         | 1         | 0.59%   |
| 6.2.12                | 1         | 0.59%   |
| 6.1.9                 | 1         | 0.59%   |
| 6.1.7                 | 1         | 0.59%   |
| 6.1.25                | 1         | 0.59%   |
| 6.1.0-9-amd64         | 1         | 0.59%   |
| 6.1.0-7-amd64         | 1         | 0.59%   |
| 6.1.0-2-amd64         | 1         | 0.59%   |
| 6.1.0-10-amd64        | 1         | 0.59%   |
| 6.1.0-0.deb11.7-amd64 | 1         | 0.59%   |
| 6.1.0-0.deb11.6-amd64 | 1         | 0.59%   |
| 6.1.0-0.deb11.5-amd64 | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 72        | 45%     |
| 4.19.0   | 29        | 18.13%  |
| 6.1.0    | 9         | 5.63%   |
| 4.9.0    | 8         | 5%      |
| 5.7.0    | 6         | 3.75%   |
| 6.0.0    | 4         | 2.5%    |
| 5.18.0   | 4         | 2.5%    |
| 5.15.0   | 3         | 1.88%   |
| 5.9.0    | 2         | 1.25%   |
| 5.8.0    | 2         | 1.25%   |
| 5.14.0   | 2         | 1.25%   |
| 6.3.0    | 1         | 0.63%   |
| 6.2.12   | 1         | 0.63%   |
| 6.1.9    | 1         | 0.63%   |
| 6.1.7    | 1         | 0.63%   |
| 6.1.25   | 1         | 0.63%   |
| 5.7.19   | 1         | 0.63%   |
| 5.6.0    | 1         | 0.63%   |
| 5.19.0   | 1         | 0.63%   |
| 5.18.14  | 1         | 0.63%   |
| 5.18.11  | 1         | 0.63%   |
| 5.16.0   | 1         | 0.63%   |
| 5.15.5   | 1         | 0.63%   |
| 5.11.0   | 1         | 0.63%   |
| 5.10.162 | 1         | 0.63%   |
| 5.1.21   | 1         | 0.63%   |
| 5.0.7    | 1         | 0.63%   |
| 4.4.195  | 1         | 0.63%   |
| 4.19.112 | 1         | 0.63%   |
| 4.18.0   | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 73        | 45.63%  |
| 4.19    | 30        | 18.75%  |
| 6.1     | 12        | 7.5%    |
| 4.9     | 8         | 5%      |
| 5.7     | 7         | 4.38%   |
| 5.18    | 6         | 3.75%   |
| 6.0     | 4         | 2.5%    |
| 5.15    | 4         | 2.5%    |
| 5.9     | 2         | 1.25%   |
| 5.8     | 2         | 1.25%   |
| 5.14    | 2         | 1.25%   |
| 6.3     | 1         | 0.63%   |
| 6.2     | 1         | 0.63%   |
| 5.6     | 1         | 0.63%   |
| 5.19    | 1         | 0.63%   |
| 5.16    | 1         | 0.63%   |
| 5.11    | 1         | 0.63%   |
| 5.1     | 1         | 0.63%   |
| 5.0     | 1         | 0.63%   |
| 4.4     | 1         | 0.63%   |
| 4.18    | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 94.7%   |
| i686   | 6         | 3.97%   |
| armv7l | 2         | 1.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| XFCE          | 62        | 38.99%  |
| KDE5          | 25        | 15.72%  |
| Unknown       | 23        | 14.47%  |
| MATE          | 20        | 12.58%  |
| i3            | 7         | 4.4%    |
| LXDE          | 6         | 3.77%   |
| Cinnamon      | 5         | 3.14%   |
| GNOME         | 4         | 2.52%   |
| LXQt          | 2         | 1.26%   |
| Enlightenment | 2         | 1.26%   |
| X-Cinnamon    | 1         | 0.63%   |
| Openbox       | 1         | 0.63%   |
| awesome       | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 135       | 87.66%  |
| Tty         | 12        | 7.79%   |
| Unknown     | 5         | 3.25%   |
| Wayland     | 1         | 0.65%   |
| Unspecified | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 56        | 36.13%  |
| LightDM | 41        | 26.45%  |
| Unknown | 37        | 23.87%  |
| SDDM    | 13        | 8.39%   |
| XDM     | 2         | 1.29%   |
| NODM    | 2         | 1.29%   |
| GDM3    | 2         | 1.29%   |
| Ly      | 1         | 0.65%   |
| LXDM    | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 60        | 38.96%  |
| en_GB       | 25        | 16.23%  |
| ru_RU       | 11        | 7.14%   |
| Unknown     | 8         | 5.19%   |
| C           | 6         | 3.9%    |
| pt_BR       | 5         | 3.25%   |
| fr_FR       | 5         | 3.25%   |
| es_ES       | 4         | 2.6%    |
| de_DE       | 4         | 2.6%    |
| sk_SK       | 3         | 1.95%   |
| fr_BE       | 3         | 1.95%   |
| en_AU       | 3         | 1.95%   |
| pl_PL       | 2         | 1.3%    |
| it_IT       | 2         | 1.3%    |
| en_NZ       | 2         | 1.3%    |
| de_AT       | 2         | 1.3%    |
| ru_UA       | 1         | 0.65%   |
| ru_RU.utf-8 | 1         | 0.65%   |
| es_SV       | 1         | 0.65%   |
| es_MX       | 1         | 0.65%   |
| en_ZA       | 1         | 0.65%   |
| en_US.utf-8 | 1         | 0.65%   |
| en_SG       | 1         | 0.65%   |
| en_CA       | 1         | 0.65%   |
| de_CH       | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 81        | 53.29%  |
| EFI  | 71        | 46.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 83.44%  |
| Btrfs   | 8         | 5.3%    |
| Xfs     | 5         | 3.31%   |
| Unknown | 5         | 3.31%   |
| Overlay | 3         | 1.99%   |
| Ext3    | 2         | 1.32%   |
| OveXlay | 1         | 0.66%   |
| Ext2    | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 86        | 55.13%  |
| MBR     | 56        | 35.9%   |
| Unknown | 14        | 8.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 77.78%  |
| Yes       | 34        | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 75.66%  |
| Yes       | 37        | 24.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 18.54%  |
| Dell                | 21        | 13.91%  |
| ASUSTek Computer    | 17        | 11.26%  |
| Hewlett-Packard     | 16        | 10.6%   |
| Gigabyte Technology | 13        | 8.61%   |
| MSI                 | 12        | 7.95%   |
| Acer                | 6         | 3.97%   |
| Toshiba             | 4         | 2.65%   |
| ASRock              | 4         | 2.65%   |
| Google              | 3         | 1.99%   |
| Samsung Electronics | 2         | 1.32%   |
| Nokia               | 2         | 1.32%   |
| Intel               | 2         | 1.32%   |
| Fujitsu Siemens     | 2         | 1.32%   |
| AMI                 | 2         | 1.32%   |
| Teclast             | 1         | 0.66%   |
| Supermicro          | 1         | 0.66%   |
| Sun Microsystems    | 1         | 0.66%   |
| Sony                | 1         | 0.66%   |
| Online Labs         | 1         | 0.66%   |
| Notebook            | 1         | 0.66%   |
| MTC                 | 1         | 0.66%   |
| Microsoft           | 1         | 0.66%   |
| LORD ELECTRONICS    | 1         | 0.66%   |
| IP3 Tech            | 1         | 0.66%   |
| IBM                 | 1         | 0.66%   |
| HUAWEI              | 1         | 0.66%   |
| Fujitsu             | 1         | 0.66%   |
| Chuwi               | 1         | 0.66%   |
| CCE                 | 1         | 0.66%   |
| Apple               | 1         | 0.66%   |
| Unknown             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nokia N900                                                                               | 2         | 1.32%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.66%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.66%   |
| Toshiba Satellite L655                                                                   | 1         | 0.66%   |
| Toshiba Satellite L300                                                                   | 1         | 0.66%   |
| Teclast F6 Plus                                                                          | 1         | 0.66%   |
| Supermicro SYS-1018GR-T                                                                  | 1         | 0.66%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.66%   |
| Sony VPCEE23FX                                                                           | 1         | 0.66%   |
| Samsung 550XDA                                                                           | 1         | 0.66%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.66%   |
| Online Labs SR                                                                           | 1         | 0.66%   |
| Notebook W230ST                                                                          | 1         | 0.66%   |
| MTC Montara-GML                                                                          | 1         | 0.66%   |
| MSI MS-7B86                                                                              | 1         | 0.66%   |
| MSI MS-7B84                                                                              | 1         | 0.66%   |
| MSI MS-7B53                                                                              | 1         | 0.66%   |
| MSI MS-7A38                                                                              | 1         | 0.66%   |
| MSI MS-7A36                                                                              | 1         | 0.66%   |
| MSI MS-7A34                                                                              | 1         | 0.66%   |
| MSI MS-7885                                                                              | 1         | 0.66%   |
| MSI MS-7678                                                                              | 1         | 0.66%   |
| MSI MS-7673                                                                              | 1         | 0.66%   |
| MSI MS-1688                                                                              | 1         | 0.66%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.66%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 0.66%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.66%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design                                        | 1         | 0.66%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.66%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.66%   |
| Lenovo ThinkStation P330 Tiny 30CES09U00                                                 | 1         | 0.66%   |
| Lenovo ThinkStation P330 30C5S1LQ00                                                      | 1         | 0.66%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.66%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.66%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.66%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 17        | 11.26%  |
| Dell Latitude           | 10        | 6.62%   |
| Acer Aspire             | 5         | 3.31%   |
| Toshiba Satellite       | 4         | 2.65%   |
| Lenovo IdeaPad          | 4         | 2.65%   |
| Dell OptiPlex           | 4         | 2.65%   |
| ASUS PRIME              | 4         | 2.65%   |
| Lenovo ThinkStation     | 3         | 1.99%   |
| HP Laptop               | 3         | 1.99%   |
| Nokia N900              | 2         | 1.32%   |
| HP ProBook              | 2         | 1.32%   |
| HP Pavilion             | 2         | 1.32%   |
| HP EliteDesk            | 2         | 1.32%   |
| Dell Inspiron           | 2         | 1.32%   |
| ASUS ROG                | 2         | 1.32%   |
| Teclast F6              | 1         | 0.66%   |
| Supermicro SYS-1018GR-T | 1         | 0.66%   |
| Sun Microsystems Ultra  | 1         | 0.66%   |
| Sony VPCEE23FX          | 1         | 0.66%   |
| Samsung 550XDA          | 1         | 0.66%   |
| Samsung 355V4C          | 1         | 0.66%   |
| Online Labs SR          | 1         | 0.66%   |
| Notebook W230ST         | 1         | 0.66%   |
| MTC Montara-GML         | 1         | 0.66%   |
| MSI MS-7B86             | 1         | 0.66%   |
| MSI MS-7B84             | 1         | 0.66%   |
| MSI MS-7B53             | 1         | 0.66%   |
| MSI MS-7A38             | 1         | 0.66%   |
| MSI MS-7A36             | 1         | 0.66%   |
| MSI MS-7A34             | 1         | 0.66%   |
| MSI MS-7885             | 1         | 0.66%   |
| MSI MS-7678             | 1         | 0.66%   |
| MSI MS-7673             | 1         | 0.66%   |
| MSI MS-1688             | 1         | 0.66%   |
| MSI Modern              | 1         | 0.66%   |
| MSI Bravo               | 1         | 0.66%   |
| Microsoft Surface       | 1         | 0.66%   |
| LORD ELECTRONICS LORD   | 1         | 0.66%   |
| Lenovo Yoga             | 1         | 0.66%   |
| Lenovo V310-14ISK       | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 20        | 13.25%  |
| 2019    | 18        | 11.92%  |
| 2012    | 13        | 8.61%   |
| 2014    | 10        | 6.62%   |
| 2013    | 10        | 6.62%   |
| 2011    | 10        | 6.62%   |
| 2017    | 8         | 5.3%    |
| 2016    | 8         | 5.3%    |
| 2021    | 7         | 4.64%   |
| 2020    | 7         | 4.64%   |
| 2010    | 7         | 4.64%   |
| 2009    | 6         | 3.97%   |
| 2008    | 6         | 3.97%   |
| 2015    | 5         | 3.31%   |
| 2022    | 4         | 2.65%   |
| 2006    | 3         | 1.99%   |
| 2023    | 2         | 1.32%   |
| 2007    | 2         | 1.32%   |
| 2005    | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 2000    | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 81        | 53.64%  |
| Desktop     | 59        | 39.07%  |
| Mini pc     | 5         | 3.31%   |
| Tablet      | 3         | 1.99%   |
| Convertible | 2         | 1.32%   |
| Server      | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 148       | 97.37%  |
| Enabled  | 4         | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 145       | 96.03%  |
| Yes  | 6         | 3.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 20.39%  |
| 16.01-24.0  | 31        | 20.39%  |
| 8.01-16.0   | 30        | 19.74%  |
| 3.01-4.0    | 22        | 14.47%  |
| 32.01-64.0  | 16        | 10.53%  |
| 1.01-2.0    | 8         | 5.26%   |
| 64.01-256.0 | 5         | 3.29%   |
| 2.01-3.0    | 4         | 2.63%   |
| 0.01-0.5    | 4         | 2.63%   |
| 24.01-32.0  | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 36.2%   |
| 4.01-8.0   | 30        | 18.4%   |
| 2.01-3.0   | 20        | 12.27%  |
| 3.01-4.0   | 18        | 11.04%  |
| 0.51-1.0   | 18        | 11.04%  |
| 8.01-16.0  | 8         | 4.91%   |
| 0.01-0.5   | 7         | 4.29%   |
| 16.01-24.0 | 2         | 1.23%   |
| 32.01-64.0 | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 61.84%  |
| 2      | 28        | 18.42%  |
| 3      | 17        | 11.18%  |
| 4      | 5         | 3.29%   |
| 5      | 4         | 2.63%   |
| 6      | 3         | 1.97%   |
| 7      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 66.45%  |
| Yes       | 51        | 33.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 90.07%  |
| No        | 15        | 9.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 63.4%   |
| No        | 56        | 36.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 55.56%  |
| Yes       | 68        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 13.16%  |
| Germany      | 14        | 9.21%   |
| Russia       | 13        | 8.55%   |
| France       | 13        | 8.55%   |
| Brazil       | 8         | 5.26%   |
| Ukraine      | 7         | 4.61%   |
| UK           | 5         | 3.29%   |
| Slovakia     | 5         | 3.29%   |
| Poland       | 5         | 3.29%   |
| Spain        | 4         | 2.63%   |
| Netherlands  | 4         | 2.63%   |
| Grenada      | 4         | 2.63%   |
| Portugal     | 3         | 1.97%   |
| Italy        | 3         | 1.97%   |
| Australia    | 3         | 1.97%   |
| Switzerland  | 2         | 1.32%   |
| New Zealand  | 2         | 1.32%   |
| Mexico       | 2         | 1.32%   |
| Israel       | 2         | 1.32%   |
| Indonesia    | 2         | 1.32%   |
| Hungary      | 2         | 1.32%   |
| Georgia      | 2         | 1.32%   |
| Finland      | 2         | 1.32%   |
| Canada       | 2         | 1.32%   |
| Belgium      | 2         | 1.32%   |
| Austria      | 2         | 1.32%   |
| Argentina    | 2         | 1.32%   |
| Vietnam      | 1         | 0.66%   |
| Tunisia      | 1         | 0.66%   |
| South Korea  | 1         | 0.66%   |
| South Africa | 1         | 0.66%   |
| Singapore    | 1         | 0.66%   |
| Serbia       | 1         | 0.66%   |
| Romania      | 1         | 0.66%   |
| Puerto Rico  | 1         | 0.66%   |
| Norway       | 1         | 0.66%   |
| Lithuania    | 1         | 0.66%   |
| India        | 1         | 0.66%   |
| Greece       | 1         | 0.66%   |
| El Salvador  | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Bratislava           | 5         | 3.27%   |
| Bagnolet             | 5         | 3.27%   |
| Saint George's       | 4         | 2.61%   |
| Wroclaw              | 2         | 1.31%   |
| Volzhskiy            | 2         | 1.31%   |
| Toronto              | 2         | 1.31%   |
| Tel Aviv             | 2         | 1.31%   |
| Tbilisi              | 2         | 1.31%   |
| Sydney               | 2         | 1.31%   |
| Sao Paulo            | 2         | 1.31%   |
| Rio de Janeiro       | 2         | 1.31%   |
| Nadudvar             | 2         | 1.31%   |
| Milan                | 2         | 1.31%   |
| Madrid               | 2         | 1.31%   |
| Lisbon               | 2         | 1.31%   |
| Kyiv                 | 2         | 1.31%   |
| Ft. Washington       | 2         | 1.31%   |
| Auckland             | 2         | 1.31%   |
| Amsterdam            | 2         | 1.31%   |
| Yakutsk              | 1         | 0.65%   |
| Xiamen               | 1         | 0.65%   |
| Windisch             | 1         | 0.65%   |
| Willich              | 1         | 0.65%   |
| Wildberg             | 1         | 0.65%   |
| Waterford            | 1         | 0.65%   |
| Vladikavkaz          | 1         | 0.65%   |
| Vise                 | 1         | 0.65%   |
| Vilnius              | 1         | 0.65%   |
| Valbonne             | 1         | 0.65%   |
| Trubchëvsk          | 1         | 0.65%   |
| Thessaloniki         | 1         | 0.65%   |
| Tejgaon              | 1         | 0.65%   |
| Tangerang            | 1         | 0.65%   |
| Talavera de la Reina | 1         | 0.65%   |
| Syktyvkar            | 1         | 0.65%   |
| Staunton             | 1         | 0.65%   |
| St Petersburg        | 1         | 0.65%   |
| Sofia                | 1         | 0.65%   |
| Singapore            | 1         | 0.65%   |
| Siena                | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 42        | 62     | 18.58%  |
| Seagate             | 29        | 40     | 12.83%  |
| Samsung Electronics | 23        | 37     | 10.18%  |
| Kingston            | 16        | 19     | 7.08%   |
| Unknown             | 14        | 18     | 6.19%   |
| Toshiba             | 10        | 10     | 4.42%   |
| SanDisk             | 9         | 9      | 3.98%   |
| Crucial             | 9         | 11     | 3.98%   |
| Hitachi             | 7         | 7      | 3.1%    |
| SK hynix            | 5         | 5      | 2.21%   |
| PNY                 | 5         | 6      | 2.21%   |
| HGST                | 4         | 4      | 1.77%   |
| Team                | 3         | 3      | 1.33%   |
| Netac               | 3         | 3      | 1.33%   |
| Micron Technology   | 3         | 4      | 1.33%   |
| LITEON              | 3         | 6      | 1.33%   |
| Intel               | 3         | 3      | 1.33%   |
| Fujitsu             | 3         | 3      | 1.33%   |
| Maxtor              | 2         | 2      | 0.88%   |
| Lenovo              | 2         | 2      | 0.88%   |
| Hewlett-Packard     | 2         | 3      | 0.88%   |
| Dogfish             | 2         | 2      | 0.88%   |
| China               | 2         | 2      | 0.88%   |
| A-DATA Technology   | 2         | 2      | 0.88%   |
| WD MediaMax         | 1         | 3      | 0.44%   |
| Union Memory        | 1         | 2      | 0.44%   |
| UMIS                | 1         | 1      | 0.44%   |
| Transcend           | 1         | 2      | 0.44%   |
| Teclast             | 1         | 1      | 0.44%   |
| Supermicro          | 1         | 1      | 0.44%   |
| Smart               | 1         | 1      | 0.44%   |
| SABRENT             | 1         | 2      | 0.44%   |
| Plextor             | 1         | 1      | 0.44%   |
| Patriot             | 1         | 1      | 0.44%   |
| Mushkin             | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| Lexar               | 1         | 1      | 0.44%   |
| Kston               | 1         | 1      | 0.44%   |
| KIOXIA              | 1         | 1      | 0.44%   |
| KingFast            | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 5         | 1.99%   |
| PNY CS900 240GB SSD                  | 4         | 1.59%   |
| Unknown MMC Card  128GB              | 3         | 1.2%    |
| Samsung SSD 850 EVO 250GB            | 3         | 1.2%    |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.2%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.2%    |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.2%    |
| Kingston SA2000M8250G 250GB          | 3         | 1.2%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.8%    |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.8%    |
| WDC WD10EZEX-00BBHA0 1TB             | 2         | 0.8%    |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 0.8%    |
| Seagate ST3500418AS 500GB            | 2         | 0.8%    |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.8%    |
| Samsung SSD 980 1TB                  | 2         | 0.8%    |
| Samsung SSD 860 EVO 250GB            | 2         | 0.8%    |
| Samsung SSD 850 EVO 500GB            | 2         | 0.8%    |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB | 2         | 0.8%    |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.8%    |
| Hitachi HDS721616PLA380 160GB        | 2         | 0.8%    |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.8%    |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.8%    |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.4%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.4%    |
| WDC WD800BB-00JHC0 80GB              | 1         | 0.4%    |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.4%    |
| WDC WD7500AALX-009BA0 752GB          | 1         | 0.4%    |
| WDC WD5001AALS-00L3B2 500GB          | 1         | 0.4%    |
| WDC WD5001AALS-00E3A0 500GB          | 1         | 0.4%    |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.4%    |
| WDC WD5000AZLX-75K2TA0 500GB         | 1         | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.4%    |
| WDC WD40EDAZ-11SLVB0 4TB             | 1         | 0.4%    |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.4%    |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 51     | 37.5%   |
| Seagate             | 28        | 39     | 31.82%  |
| Toshiba             | 7         | 7      | 7.95%   |
| Hitachi             | 7         | 7      | 7.95%   |
| HGST                | 4         | 4      | 4.55%   |
| Fujitsu             | 3         | 3      | 3.41%   |
| Maxtor              | 2         | 2      | 2.27%   |
| Samsung Electronics | 1         | 1      | 1.14%   |
| IBM/Hitachi         | 1         | 1      | 1.14%   |
| HPE                 | 1         | 2      | 1.14%   |
| Hewlett-Packard     | 1         | 2      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 17     | 17.65%  |
| Kingston            | 13        | 15     | 15.29%  |
| SanDisk             | 6         | 6      | 7.06%   |
| Crucial             | 6         | 7      | 7.06%   |
| WDC                 | 5         | 6      | 5.88%   |
| PNY                 | 5         | 6      | 5.88%   |
| Team                | 3         | 3      | 3.53%   |
| Netac               | 3         | 3      | 3.53%   |
| SK hynix            | 2         | 2      | 2.35%   |
| Micron Technology   | 2         | 2      | 2.35%   |
| LITEON              | 2         | 5      | 2.35%   |
| Dogfish             | 2         | 2      | 2.35%   |
| China               | 2         | 2      | 2.35%   |
| A-DATA Technology   | 2         | 2      | 2.35%   |
| Union Memory        | 1         | 2      | 1.18%   |
| Transcend           | 1         | 2      | 1.18%   |
| Teclast             | 1         | 1      | 1.18%   |
| Supermicro          | 1         | 1      | 1.18%   |
| Smart               | 1         | 1      | 1.18%   |
| Plextor             | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| Mushkin             | 1         | 1      | 1.18%   |
| LITEONIT            | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| Kston               | 1         | 1      | 1.18%   |
| KingDian            | 1         | 1      | 1.18%   |
| Intenso             | 1         | 1      | 1.18%   |
| HXY                 | 1         | 1      | 1.18%   |
| Hewlett-Packard     | 1         | 1      | 1.18%   |
| GOODRAM             | 1         | 1      | 1.18%   |
| Emtec               | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 75        | 97     | 36.76%  |
| HDD     | 72        | 119    | 35.29%  |
| NVMe    | 40        | 53     | 19.61%  |
| MMC     | 14        | 18     | 6.86%   |
| Unknown | 3         | 5      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 119       | 213    | 66.85%  |
| NVMe | 39        | 51     | 21.91%  |
| MMC  | 14        | 18     | 7.87%   |
| SAS  | 6         | 10     | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 129    | 62.84%  |
| 0.51-1.0   | 32        | 56     | 21.62%  |
| 1.01-2.0   | 14        | 21     | 9.46%   |
| 3.01-4.0   | 5         | 6      | 3.38%   |
| 4.01-10.0  | 3         | 3      | 2.03%   |
| 2.01-3.0   | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 35        | 22.29%  |
| 101-250        | 32        | 20.38%  |
| 501-1000       | 22        | 14.01%  |
| 1001-2000      | 17        | 10.83%  |
| 21-50          | 13        | 8.28%   |
| 51-100         | 13        | 8.28%   |
| More than 3000 | 9         | 5.73%   |
| Unknown        | 6         | 3.82%   |
| 2001-3000      | 5         | 3.18%   |
| 1-20           | 5         | 3.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 29.11%  |
| 101-250        | 32        | 20.25%  |
| 21-50          | 17        | 10.76%  |
| 251-500        | 15        | 9.49%   |
| 51-100         | 15        | 9.49%   |
| 1001-2000      | 10        | 6.33%   |
| 501-1000       | 10        | 6.33%   |
| Unknown        | 6         | 3.8%    |
| 2001-3000      | 4         | 2.53%   |
| More than 3000 | 3         | 1.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB          | 2         | 2      | 7.69%   |
| Hitachi HDS721616PLA380 160GB         | 2         | 2      | 7.69%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 3.85%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 3.85%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 3.85%   |
| WDC WD10EARX-00N0YB0 1TB              | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 3.85%   |
| Toshiba MQ02ABF100 1TB                | 1         | 1      | 3.85%   |
| SK hynix SH920 mSATA 128GB SSD        | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 3.85%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 3.85%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 3.85%   |
| Maxtor 6E040L0 41GB                   | 1         | 1      | 3.85%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 3.85%   |
| HPE MB4000GEFNA 4TB                   | 1         | 2      | 3.85%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 3.85%   |
| Hitachi HTS726060M9AT00 56GB          | 1         | 1      | 3.85%   |
| HGST HTE721010A9E630 1TB              | 1         | 1      | 3.85%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1         | 2      | 3.85%   |
| Fujitsu MHV2060BH PL 64GB             | 1         | 1      | 3.85%   |
| China SSD 256GB                       | 1         | 1      | 3.85%   |
| China SATA SSD 64GB                   | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 26.92%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Seagate             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| China               | 2         | 2      | 7.69%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| HPE                 | 1         | 2      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 2      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 7         | 7      | 33.33%  |
| Hitachi         | 4         | 4      | 19.05%  |
| Seagate         | 3         | 3      | 14.29%  |
| Toshiba         | 2         | 2      | 9.52%   |
| Maxtor          | 1         | 1      | 4.76%   |
| HPE             | 1         | 2      | 4.76%   |
| HGST            | 1         | 1      | 4.76%   |
| Hewlett-Packard | 1         | 2      | 4.76%   |
| Fujitsu         | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 23     | 80.77%  |
| SSD  | 4         | 4      | 15.38%  |
| NVMe | 1         | 1      | 3.85%   |

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
| Works    | 114       | 204    | 64.77%  |
| Detected | 37        | 60     | 21.02%  |
| Malfunc  | 25        | 28     | 14.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 104       | 58.43%  |
| AMD                              | 25        | 14.04%  |
| Samsung Electronics              | 11        | 6.18%   |
| SanDisk                          | 8         | 4.49%   |
| Kingston Technology Company      | 4         | 2.25%   |
| Toshiba America Info Systems     | 3         | 1.69%   |
| SK hynix                         | 3         | 1.69%   |
| Micron/Crucial Technology        | 3         | 1.69%   |
| Marvell Technology Group         | 2         | 1.12%   |
| Lenovo                           | 2         | 1.12%   |
| VIA Technologies                 | 1         | 0.56%   |
| Union Memory (Shenzhen)          | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Nvidia                           | 1         | 0.56%   |
| Micron Technology                | 1         | 0.56%   |
| LSI Logic / Symbios Logic        | 1         | 0.56%   |
| Lite-On Technology               | 1         | 0.56%   |
| KIOXIA                           | 1         | 0.56%   |
| Integrated Technology Express    | 1         | 0.56%   |
| Chelsio Communications           | 1         | 0.56%   |
| Broadcom / LSI                   | 1         | 0.56%   |
| ASMedia Technology               | 1         | 0.56%   |
| Adaptec                          | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 8.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 4.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 3.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 2.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 2.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 2.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.91%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 1.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 1.91%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 1.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.91%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.44%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.44%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.44%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3         | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 0.96%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                          | 2         | 0.96%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                  | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.96%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.96%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.48%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                                   | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 106       | 58.89%  |
| NVMe | 39        | 21.67%  |
| IDE  | 22        | 12.22%  |
| RAID | 11        | 6.11%   |
| SCSI | 2         | 1.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 120       | 79.47%  |
| AMD    | 29        | 19.21%  |
| ARM    | 2         | 1.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.97%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.97%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.32%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.32%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.32%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2         | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.32%   |
| ARM Nokia RX-51 board Processor             | 2         | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 1.32%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.32%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.32%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.66%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.66%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1         | 0.66%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.66%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.66%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.66%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.66%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.66%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.66%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.66%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.66%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.66%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.66%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.66%   |
| Intel Genuine CPU T1600 @ 1.66GHz           | 1         | 0.66%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.66%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 0.66%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.66%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.66%   |
| Intel Core i7-8700T CPU @ 2.40GHz           | 1         | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 21.05%  |
| Intel Core i7           | 26        | 17.11%  |
| Intel Core i3           | 13        | 8.55%   |
| Intel Celeron           | 10        | 6.58%   |
| AMD Ryzen 5             | 8         | 5.26%   |
| Other                   | 7         | 4.61%   |
| Intel Xeon              | 6         | 3.95%   |
| AMD Ryzen 7             | 6         | 3.95%   |
| Intel Core 2 Duo        | 5         | 3.29%   |
| Intel Atom              | 4         | 2.63%   |
| Intel Pentium           | 3         | 1.97%   |
| Intel Core 2            | 3         | 1.97%   |
| Intel Pentium M         | 2         | 1.32%   |
| Intel Pentium Dual-Core | 2         | 1.32%   |
| Intel Pentium Dual      | 2         | 1.32%   |
| Intel Core i9           | 2         | 1.32%   |
| Intel Core 2 Quad       | 2         | 1.32%   |
| AMD Ryzen 3             | 2         | 1.32%   |
| Intel Pentium Silver    | 1         | 0.66%   |
| Intel Pentium Gold      | 1         | 0.66%   |
| Intel Pentium 4         | 1         | 0.66%   |
| Intel Genuine           | 1         | 0.66%   |
| Intel Celeron M         | 1         | 0.66%   |
| AMD Sempron             | 1         | 0.66%   |
| AMD Ryzen Threadripper  | 1         | 0.66%   |
| AMD Ryzen 7 PRO         | 1         | 0.66%   |
| AMD FX                  | 1         | 0.66%   |
| AMD E2                  | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |
| AMD Athlon II           | 1         | 0.66%   |
| AMD Athlon              | 1         | 0.66%   |
| AMD A8                  | 1         | 0.66%   |
| AMD A6                  | 1         | 0.66%   |
| AMD A4                  | 1         | 0.66%   |
| AMD A10                 | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 64        | 42.38%  |
| 4      | 49        | 32.45%  |
| 6      | 19        | 12.58%  |
| 1      | 9         | 5.96%   |
| 8      | 7         | 4.64%   |
| 12     | 2         | 1.32%   |
| 10     | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 151       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 85        | 56.29%  |
| 1      | 66        | 43.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 94.7%   |
| 32-bit         | 4         | 2.65%   |
| Unknown        | 4         | 2.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 23.08%  |
| 0x306c3    | 10        | 6.41%   |
| 0x206a7    | 8         | 5.13%   |
| 0x1067a    | 8         | 5.13%   |
| 0x906ea    | 7         | 4.49%   |
| 0x306a9    | 7         | 4.49%   |
| 0x806ec    | 5         | 3.21%   |
| 0x406e3    | 5         | 3.21%   |
| 0x706a1    | 3         | 1.92%   |
| 0x406c4    | 3         | 1.92%   |
| 0x40651    | 3         | 1.92%   |
| 0x306d4    | 3         | 1.92%   |
| 0x30678    | 3         | 1.92%   |
| 0x20655    | 3         | 1.92%   |
| 0x0800820d | 3         | 1.92%   |
| 0x906ed    | 2         | 1.28%   |
| 0x806ea    | 2         | 1.28%   |
| 0x806c1    | 2         | 1.28%   |
| 0x706a8    | 2         | 1.28%   |
| 0x6f6      | 2         | 1.28%   |
| 0x506e3    | 2         | 1.28%   |
| 0x106e5    | 2         | 1.28%   |
| 0x08701021 | 2         | 1.28%   |
| 0x08608103 | 2         | 1.28%   |
| 0x0810100b | 2         | 1.28%   |
| 0xf49      | 1         | 0.64%   |
| 0xa0655    | 1         | 0.64%   |
| 0xa0653    | 1         | 0.64%   |
| 0x906e9    | 1         | 0.64%   |
| 0x906a3    | 1         | 0.64%   |
| 0x6fd      | 1         | 0.64%   |
| 0x6d8      | 1         | 0.64%   |
| 0x695      | 1         | 0.64%   |
| 0x686      | 1         | 0.64%   |
| 0x506c9    | 1         | 0.64%   |
| 0x406f1    | 1         | 0.64%   |
| 0x406d8    | 1         | 0.64%   |
| 0x306f2    | 1         | 0.64%   |
| 0x20652    | 1         | 0.64%   |
| 0x10676    | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 13.82%  |
| Haswell          | 17        | 11.18%  |
| IvyBridge        | 10        | 6.58%   |
| Skylake          | 9         | 5.92%   |
| Silvermont       | 9         | 5.92%   |
| Penryn           | 9         | 5.92%   |
| SandyBridge      | 8         | 5.26%   |
| Westmere         | 6         | 3.95%   |
| Unknown          | 6         | 3.95%   |
| Zen+             | 5         | 3.29%   |
| Zen 2            | 5         | 3.29%   |
| Zen              | 5         | 3.29%   |
| Goldmont plus    | 5         | 3.29%   |
| Core             | 5         | 3.29%   |
| Broadwell        | 5         | 3.29%   |
| P6               | 4         | 2.63%   |
| Nehalem          | 4         | 2.63%   |
| TigerLake        | 3         | 1.97%   |
| Piledriver       | 2         | 1.32%   |
| Excavator        | 2         | 1.32%   |
| CometLake        | 2         | 1.32%   |
| Bobcat           | 2         | 1.32%   |
| Zen 3            | 1         | 0.66%   |
| Puma             | 1         | 0.66%   |
| NetBurst         | 1         | 0.66%   |
| K8 Hammer        | 1         | 0.66%   |
| K10 Llano        | 1         | 0.66%   |
| K10              | 1         | 0.66%   |
| Goldmont         | 1         | 0.66%   |
| Alderlake Hybrid | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 92        | 56.79%  |
| AMD                              | 37        | 22.84%  |
| Nvidia                           | 31        | 19.14%  |
| Silicon Integrated Systems [SiS] | 1         | 0.62%   |
| ASPEED Technology                | 1         | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 3.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.35%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 1.76%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.18%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.18%   |
| Intel HD Graphics 620                                                                    | 2         | 1.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.18%   |
| AMD Renoir                                                                               | 2         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.18%   |
| AMD Lucienne                                                                             | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.59%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.59%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.59%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.59%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.59%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 49.67%  |
| 1 x AMD        | 29        | 19.21%  |
| 1 x Nvidia     | 21        | 13.91%  |
| Intel + Nvidia | 10        | 6.62%   |
| Other          | 5         | 3.31%   |
| 2 x AMD        | 5         | 3.31%   |
| Intel + AMD    | 3         | 1.99%   |
| 2 x Intel      | 1         | 0.66%   |
| 1 x SiS        | 1         | 0.66%   |
| 1 x ASPEED     | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 127       | 83.55%  |
| Proprietary | 17        | 11.18%  |
| Unknown     | 8         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 64.29%  |
| 0.01-0.5   | 18        | 11.69%  |
| 0.51-1.0   | 10        | 6.49%   |
| 3.01-4.0   | 9         | 5.84%   |
| 1.01-2.0   | 7         | 4.55%   |
| 7.01-8.0   | 5         | 3.25%   |
| 5.01-6.0   | 3         | 1.95%   |
| 2.01-3.0   | 3         | 1.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 14.11%  |
| LG Display              | 19        | 11.66%  |
| AU Optronics            | 18        | 11.04%  |
| Chimei Innolux          | 11        | 6.75%   |
| BOE                     | 10        | 6.13%   |
| Hewlett-Packard         | 9         | 5.52%   |
| Dell                    | 8         | 4.91%   |
| Philips                 | 7         | 4.29%   |
| Lenovo                  | 6         | 3.68%   |
| Goldstar                | 6         | 3.68%   |
| Acer                    | 6         | 3.68%   |
| AOC                     | 5         | 3.07%   |
| Unknown                 | 4         | 2.45%   |
| PANDA                   | 4         | 2.45%   |
| Iiyama                  | 4         | 2.45%   |
| Ancor Communications    | 3         | 1.84%   |
| MStar                   | 2         | 1.23%   |
| Chi Mei Optoelectronics | 2         | 1.23%   |
| ___                     | 1         | 0.61%   |
| ViewSonic               | 1         | 0.61%   |
| Toshiba                 | 1         | 0.61%   |
| STD                     | 1         | 0.61%   |
| Sony                    | 1         | 0.61%   |
| Sharp                   | 1         | 0.61%   |
| MSI                     | 1         | 0.61%   |
| InnoLux Display         | 1         | 0.61%   |
| InfoVision              | 1         | 0.61%   |
| HJW                     | 1         | 0.61%   |
| Hisense                 | 1         | 0.61%   |
| eMachines               | 1         | 0.61%   |
| Eizo                    | 1         | 0.61%   |
| CVT                     | 1         | 0.61%   |
| CHI                     | 1         | 0.61%   |
| BenQ                    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 1.2%    |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 1.2%    |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch      | 2         | 1.2%    |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 2         | 1.2%    |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 2         | 1.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.2%    |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 1.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.2%    |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                      | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 1.2%    |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 0.6%    |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.6%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.6%    |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1         | 0.6%    |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.6%    |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                      | 1         | 0.6%    |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                          | 1         | 0.6%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.6%    |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.6%    |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch    | 1         | 0.6%    |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0503 1920x1080                      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 0.6%    |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 0.6%    |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 41.4%   |
| 1366x768 (WXGA)    | 38        | 24.2%   |
| 3840x2160 (4K)     | 9         | 5.73%   |
| 1600x900 (HD+)     | 7         | 4.46%   |
| 1280x1024 (SXGA)   | 7         | 4.46%   |
| 1440x900 (WXGA+)   | 6         | 3.82%   |
| 1920x1200 (WUXGA)  | 4         | 2.55%   |
| 1280x800 (WXGA)    | 3         | 1.91%   |
| 3440x1440          | 2         | 1.27%   |
| 2560x1440 (QHD)    | 2         | 1.27%   |
| 2288x1287          | 2         | 1.27%   |
| 1600x1200          | 2         | 1.27%   |
| Unknown            | 2         | 1.27%   |
| 5760x1080          | 1         | 0.64%   |
| 3000x2000          | 1         | 0.64%   |
| 2736x1824          | 1         | 0.64%   |
| 2160x1440          | 1         | 0.64%   |
| 2048x1152          | 1         | 0.64%   |
| 1680x1050 (WSXGA+) | 1         | 0.64%   |
| 1360x768           | 1         | 0.64%   |
| 1024x768 (XGA)     | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 21.25%  |
| 24      | 15        | 9.38%   |
| 21      | 15        | 9.38%   |
| 14      | 15        | 9.38%   |
| 13      | 11        | 6.88%   |
| 12      | 10        | 6.25%   |
| 27      | 9         | 5.63%   |
| Unknown | 9         | 5.63%   |
| 23      | 8         | 5%      |
| 17      | 7         | 4.38%   |
| 11      | 5         | 3.13%   |
| 19      | 4         | 2.5%    |
| 31      | 3         | 1.88%   |
| 18      | 3         | 1.88%   |
| 142     | 2         | 1.25%   |
| 72      | 2         | 1.25%   |
| 52      | 2         | 1.25%   |
| 34      | 2         | 1.25%   |
| 54      | 1         | 0.63%   |
| 46      | 1         | 0.63%   |
| 22      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 55        | 35.48%  |
| 501-600        | 30        | 19.35%  |
| 201-300        | 22        | 14.19%  |
| 401-500        | 20        | 12.9%   |
| Unknown        | 9         | 5.81%   |
| 351-400        | 6         | 3.87%   |
| 1001-1500      | 4         | 2.58%   |
| 601-700        | 3         | 1.94%   |
| More than 2000 | 2         | 1.29%   |
| 701-800        | 2         | 1.29%   |
| 1501-2000      | 2         | 1.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 108       | 76.06%  |
| 16/10   | 12        | 8.45%   |
| Unknown | 6         | 4.23%   |
| 5/4     | 4         | 2.82%   |
| 4/3     | 4         | 2.82%   |
| 3/2     | 3         | 2.11%   |
| 21/9    | 2         | 1.41%   |
| 1.00    | 2         | 1.41%   |
| 6/5     | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 33        | 20.75%  |
| 101-110        | 32        | 20.13%  |
| 81-90          | 19        | 11.95%  |
| 61-70          | 10        | 6.29%   |
| 301-350        | 9         | 5.66%   |
| Unknown        | 9         | 5.66%   |
| More than 1000 | 7         | 4.4%    |
| 71-80          | 7         | 4.4%    |
| 151-200        | 7         | 4.4%    |
| 51-60          | 5         | 3.14%   |
| 351-500        | 5         | 3.14%   |
| 141-150        | 5         | 3.14%   |
| 251-300        | 4         | 2.52%   |
| 121-130        | 3         | 1.89%   |
| 111-120        | 2         | 1.26%   |
| 131-140        | 1         | 0.63%   |
| 501-1000       | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 46        | 29.49%  |
| 101-120       | 45        | 28.85%  |
| 121-160       | 38        | 24.36%  |
| Unknown       | 9         | 5.77%   |
| 1-50          | 8         | 5.13%   |
| 161-240       | 8         | 5.13%   |
| More than 240 | 2         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 123       | 79.87%  |
| 2     | 22        | 14.29%  |
| 3     | 5         | 3.25%   |
| 0     | 4         | 2.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 74        | 34.26%  |
| Realtek Semiconductor            | 72        | 33.33%  |
| Qualcomm Atheros                 | 27        | 12.5%   |
| Broadcom                         | 8         | 3.7%    |
| Ralink Technology                | 5         | 2.31%   |
| Samsung Electronics              | 3         | 1.39%   |
| MediaTek                         | 3         | 1.39%   |
| Marvell Technology Group         | 3         | 1.39%   |
| TP-Link                          | 2         | 0.93%   |
| Sierra Wireless                  | 2         | 0.93%   |
| NetGear                          | 2         | 0.93%   |
| JMicron Technology               | 2         | 0.93%   |
| Broadcom Limited                 | 2         | 0.93%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.46%   |
| VIA Technologies                 | 1         | 0.46%   |
| Solarflare Communications        | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Ralink                           | 1         | 0.46%   |
| Nvidia                           | 1         | 0.46%   |
| Huawei Technologies              | 1         | 0.46%   |
| DisplayLink                      | 1         | 0.46%   |
| Dell                             | 1         | 0.46%   |
| Chelsio Communications           | 1         | 0.46%   |
| ASIX Electronics                 | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 50        | 19.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.95%   |
| Intel Wireless 7260                                                     | 5         | 1.95%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.95%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.95%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.56%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.56%   |
| Intel Wireless 7265                                                     | 4         | 1.56%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 1.17%   |
| Intel Wireless 8260                                                     | 3         | 1.17%   |
| Intel Ethernet Controller I225-V                                        | 3         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.17%   |
| Sierra Wireless EM7455                                                  | 2         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.78%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.78%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.78%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 40.2%   |
| Qualcomm Atheros         | 24        | 23.53%  |
| Realtek Semiconductor    | 15        | 14.71%  |
| Ralink Technology        | 5         | 4.9%    |
| Broadcom                 | 4         | 3.92%   |
| MediaTek                 | 3         | 2.94%   |
| Sierra Wireless          | 2         | 1.96%   |
| NetGear                  | 2         | 1.96%   |
| Broadcom Limited         | 2         | 1.96%   |
| TP-Link                  | 1         | 0.98%   |
| Ralink                   | 1         | 0.98%   |
| Marvell Technology Group | 1         | 0.98%   |
| Dell                     | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 4.9%    |
| Intel Wireless 7260                                                     | 5         | 4.9%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 4.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.92%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.92%   |
| Intel Wireless 7265                                                     | 4         | 3.92%   |
| Intel Wireless 8260                                                     | 3         | 2.94%   |
| Sierra Wireless EM7455                                                  | 2         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.96%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.96%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.96%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.96%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.98%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.98%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.98%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.98%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.98%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.98%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 65        | 43.92%  |
| Intel                            | 57        | 38.51%  |
| Qualcomm Atheros                 | 5         | 3.38%   |
| Broadcom                         | 4         | 2.7%    |
| Samsung Electronics              | 3         | 2.03%   |
| Marvell Technology Group         | 2         | 1.35%   |
| JMicron Technology               | 2         | 1.35%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.68%   |
| VIA Technologies                 | 1         | 0.68%   |
| TP-Link                          | 1         | 0.68%   |
| Solarflare Communications        | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Nvidia                           | 1         | 0.68%   |
| Huawei Technologies              | 1         | 0.68%   |
| DisplayLink                      | 1         | 0.68%   |
| Chelsio Communications           | 1         | 0.68%   |
| ASIX Electronics                 | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 33.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 7.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.96%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 3.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.99%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.32%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.32%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.32%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 0.66%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.66%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.66%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.66%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.66%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.66%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.66%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 136       | 57.63%  |
| WiFi     | 97        | 41.1%   |
| Modem    | 3         | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 81        | 52.94%  |
| WiFi     | 72        | 47.06%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 78        | 50.98%  |
| 1     | 64        | 41.83%  |
| 0     | 6         | 3.92%   |
| 3     | 2         | 1.31%   |
| 7     | 1         | 0.65%   |
| 5     | 1         | 0.65%   |
| 4     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 87.42%  |
| Yes  | 19        | 12.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 42.03%  |
| Qualcomm Atheros Communications | 7         | 10.14%  |
| Realtek Semiconductor           | 6         | 8.7%    |
| Broadcom                        | 4         | 5.8%    |
| Lite-On Technology              | 3         | 4.35%   |
| IMC Networks                    | 3         | 4.35%   |
| Cambridge Silicon Radio         | 3         | 4.35%   |
| Foxconn International           | 2         | 2.9%    |
| Foxconn / Hon Hai               | 2         | 2.9%    |
| Dell                            | 2         | 2.9%    |
| ASUSTek Computer                | 2         | 2.9%    |
| TP-Link                         | 1         | 1.45%   |
| Realtek                         | 1         | 1.45%   |
| Ralink                          | 1         | 1.45%   |
| MediaTek                        | 1         | 1.45%   |
| Marvell Semiconductor           | 1         | 1.45%   |
| Apple                           | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 20.29%  |
| Realtek Bluetooth Radio                             | 6         | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 7.25%   |
| Intel AX200 Bluetooth                               | 5         | 7.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.9%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.9%    |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 2.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 2.9%    |
| ASUS ASUS USB-BT500                                 | 2         | 2.9%    |
| TP-Link UB500 Adapter                               | 1         | 1.45%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.45%   |
| MediaTek Wireless_Device                            | 1         | 1.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.45%   |
| Intel Bluetooth Device                              | 1         | 1.45%   |
| Intel AX201 Bluetooth                               | 1         | 1.45%   |
| IMC Networks Bluetooth Device                       | 1         | 1.45%   |
| IMC Networks BCM20702A0                             | 1         | 1.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.45%   |
| Foxconn / Hon Hai BT                                | 1         | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.45%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 56.12%  |
| AMD                              | 34        | 17.35%  |
| Nvidia                           | 24        | 12.24%  |
| Creative Labs                    | 4         | 2.04%   |
| C-Media Electronics              | 4         | 2.04%   |
| Plantronics                      | 2         | 1.02%   |
| Texas Instruments                | 1         | 0.51%   |
| TEAC                             | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Sennheiser Communications        | 1         | 0.51%   |
| Realtek Semiconductor            | 1         | 0.51%   |
| M-Audio                          | 1         | 0.51%   |
| Logitech                         | 1         | 0.51%   |
| KORG                             | 1         | 0.51%   |
| GYROCOM C&C                      | 1         | 0.51%   |
| Giga-Byte Technology             | 1         | 0.51%   |
| Generalplus Technology           | 1         | 0.51%   |
| FUXIN                            | 1         | 0.51%   |
| Focusrite-Novation               | 1         | 0.51%   |
| Elite Silicon                    | 1         | 0.51%   |
| Cirrus Logic                     | 1         | 0.51%   |
| Blue Microphones                 | 1         | 0.51%   |
| Avance Logic                     | 1         | 0.51%   |
| ASUSTek Computer                 | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 4.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 2.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 2.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.69%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.27%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.27%   |
| Plantronics HD1                                                            | 2         | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.84%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 0.84%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 0.84%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 20%     |
| Unknown             | 22        | 14.19%  |
| SK hynix            | 20        | 12.9%   |
| Kingston            | 18        | 11.61%  |
| Corsair             | 14        | 9.03%   |
| Micron Technology   | 10        | 6.45%   |
| G.Skill             | 7         | 4.52%   |
| Crucial             | 6         | 3.87%   |
| A-DATA Technology   | 6         | 3.87%   |
| Unknown (ABCD)      | 3         | 1.94%   |
| Nanya Technology    | 3         | 1.94%   |
| Unknown             | 3         | 1.94%   |
| Ramaxel Technology  | 2         | 1.29%   |
| Unknown (F785)      | 1         | 0.65%   |
| Unknown (130B)      | 1         | 0.65%   |
| Transcend           | 1         | 0.65%   |
| Team                | 1         | 0.65%   |
| Smart               | 1         | 0.65%   |
| GOODRAM             | 1         | 0.65%   |
| Avant               | 1         | 0.65%   |
| Apacer              | 1         | 0.65%   |
| A Force             | 1         | 0.65%   |
| 4ea5                | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 3         | 1.71%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 3         | 1.71%   |
| Unknown                                                           | 3         | 1.71%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 2         | 1.14%   |
| Unknown RAM Module 1024MB SODIMM DDR                              | 2         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1.14%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 2         | 1.14%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 1.14%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s             | 2         | 1.14%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                         | 1         | 0.57%   |
| Unknown RAM Module 512MB SODIMM DDR                               | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                          | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM SDRAM                              | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR                                | 1         | 0.57%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                | 1         | 0.57%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s             | 1         | 0.57%   |
| Unknown (F785) RAM Module 16GB SODIMM DDR4 3200MT/s               | 1         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 1         | 0.57%   |
| Unknown (130B) RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 54        | 40.3%   |
| DDR4    | 53        | 39.55%  |
| SDRAM   | 5         | 3.73%   |
| DDR2    | 5         | 3.73%   |
| LPDDR4  | 4         | 2.99%   |
| LPDDR3  | 4         | 2.99%   |
| DDR     | 4         | 2.99%   |
| Unknown | 3         | 2.24%   |
| DRAM    | 1         | 0.75%   |
| DDR5    | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 54.89%  |
| DIMM         | 54        | 40.6%   |
| Row Of Chips | 4         | 3.01%   |
| Chip         | 1         | 0.75%   |
| Unknown      | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 35.53%  |
| 4096  | 41        | 26.97%  |
| 16384 | 24        | 15.79%  |
| 2048  | 19        | 12.5%   |
| 1024  | 7         | 4.61%   |
| 32768 | 3         | 1.97%   |
| 512   | 1         | 0.66%   |
| 256   | 1         | 0.66%   |
| 128   | 1         | 0.66%   |
| 64    | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 36        | 24.66%  |
| 2667    | 22        | 15.07%  |
| 2400    | 13        | 8.9%    |
| 3200    | 11        | 7.53%   |
| 1333    | 9         | 6.16%   |
| 2133    | 8         | 5.48%   |
| Unknown | 7         | 4.79%   |
| 1067    | 5         | 3.42%   |
| 3600    | 4         | 2.74%   |
| 3400    | 4         | 2.74%   |
| 1867    | 3         | 2.05%   |
| 1800    | 3         | 2.05%   |
| 1066    | 3         | 2.05%   |
| 667     | 3         | 2.05%   |
| 4199    | 2         | 1.37%   |
| 3266    | 2         | 1.37%   |
| 800     | 2         | 1.37%   |
| 4800    | 1         | 0.68%   |
| 3666    | 1         | 0.68%   |
| 3534    | 1         | 0.68%   |
| 2933    | 1         | 0.68%   |
| 1334    | 1         | 0.68%   |
| 1200    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |
| 400     | 1         | 0.68%   |
| 100     | 1         | 0.68%   |

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
| Chicony Electronics                    | 25        | 31.25%  |
| Microdia                               | 8         | 10%     |
| Logitech                               | 6         | 7.5%    |
| Sunplus Innovation Technology          | 5         | 6.25%   |
| Realtek Semiconductor                  | 4         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5%      |
| Acer                                   | 4         | 5%      |
| IMC Networks                           | 3         | 3.75%   |
| Suyin                                  | 2         | 2.5%    |
| Quanta                                 | 2         | 2.5%    |
| Lite-On Technology                     | 2         | 2.5%    |
| KYE Systems (Mouse Systems)            | 2         | 2.5%    |
| Cubeternet                             | 2         | 2.5%    |
| Bison Electronics                      | 2         | 2.5%    |
| Z-Star Microelectronics                | 1         | 1.25%   |
| Softkinetic                            | 1         | 1.25%   |
| Samsung Electronics                    | 1         | 1.25%   |
| Mustek Systems                         | 1         | 1.25%   |
| Microsoft                              | 1         | 1.25%   |
| MacroSilicon                           | 1         | 1.25%   |
| kingcome                               | 1         | 1.25%   |
| Hauppauge                              | 1         | 1.25%   |
| GEMBIRD                                | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 8         | 10%     |
| Chicony HD WebCam                          | 3         | 3.75%   |
| Logitech Webcam C270                       | 2         | 2.5%    |
| Logitech HD Pro Webcam C920                | 2         | 2.5%    |
| Cubeternet GL-UPC822 UVC WebCam            | 2         | 2.5%    |
| Chicony HP TrueVision HD Camera            | 2         | 2.5%    |
| Chicony EasyCamera                         | 2         | 2.5%    |
| Acer BisonCam, NB Pro                      | 2         | 2.5%    |
| Z-Star Vimicro USB Camera (Altair)         | 1         | 1.25%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 1         | 1.25%   |
| Sunplus Laptop Integrated Webcam HD        | 1         | 1.25%   |
| Sunplus Integrated_Webcam_HD               | 1         | 1.25%   |
| Sunplus Asus Webcam                        | 1         | 1.25%   |
| Sunplus 720p HD Camera                     | 1         | 1.25%   |
| Sunplus 1080P Webcam                       | 1         | 1.25%   |
| Softkinetic DepthSense 325                 | 1         | 1.25%   |
| Samsung Galaxy series, misc. (MTP mode)    | 1         | 1.25%   |
| Realtek Lenovo EasyCamera                  | 1         | 1.25%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.25%   |
| Realtek Integrated Webcam_HD               | 1         | 1.25%   |
| Realtek HD 720P Webcam                     | 1         | 1.25%   |
| Quanta Sony Visual Communication Camera    | 1         | 1.25%   |
| Quanta HP HD Camera                        | 1         | 1.25%   |
| Mustek Systems USB 2.0 PC Camera           | 1         | 1.25%   |
| Microsoft LifeCam Studio                   | 1         | 1.25%   |
| Microdia Webcam Vitade AF                  | 1         | 1.25%   |
| Microdia WebCam SC-13HDL12639P             | 1         | 1.25%   |
| Microdia Sonix USB 2.0 Camera              | 1         | 1.25%   |
| Microdia Integrated_Webcam_HD              | 1         | 1.25%   |
| Microdia Integrated Webcam                 | 1         | 1.25%   |
| Microdia Dell Integrated HD Webcam         | 1         | 1.25%   |
| Microdia Camera                            | 1         | 1.25%   |
| Microdia 1.3 MPixel Integrated Webcam      | 1         | 1.25%   |
| MacroSilicon USB Video                     | 1         | 1.25%   |
| Logitech C920 PRO HD Webcam                | 1         | 1.25%   |
| Logitech BRIO Ultra HD Webcam              | 1         | 1.25%   |
| Lite-On HP Wide Vision HD Camera           | 1         | 1.25%   |
| Lite-On HP HD Webcam                       | 1         | 1.25%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Validity Sensors           | 1         | 14.29%  |
| Upek                       | 1         | 14.29%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 14.29%  |
| Synaptics Fingerprint scanner                          | 1         | 14.29%  |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 57.14%  |
| Alcor Micro | 5         | 35.71%  |
| Lenovo      | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 115       | 74.19%  |
| 1     | 28        | 18.06%  |
| 2     | 8         | 5.16%   |
| 3     | 3         | 1.94%   |
| 5     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 9         | 19.57%  |
| Graphics card            | 8         | 17.39%  |
| Fingerprint reader       | 7         | 15.22%  |
| Net/wireless             | 5         | 10.87%  |
| Communication controller | 5         | 10.87%  |
| Unassigned class         | 3         | 6.52%   |
| Camera                   | 3         | 6.52%   |
| Multimedia controller    | 2         | 4.35%   |
| Bluetooth                | 2         | 4.35%   |
| Net/ethernet             | 1         | 2.17%   |
| Firewire controller      | 1         | 2.17%   |


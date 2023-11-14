Alpine - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Alpine/Desktop/README.md) and [notebooks](/Dist/Alpine/Notebook/README.md).

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

Total: 209

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | Desktop     | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | Desktop     | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | Desktop     | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2ea9aa9b27](https://linux-hardware.org/?probe=2ea9aa9b27) | Aug 02, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3dcdce4c6d](https://linux-hardware.org/?probe=3dcdce4c6d) | Aug 02, 2023 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASUSTek       | Z170-E                      | Desktop     | [8be9720ca6](https://linux-hardware.org/?probe=8be9720ca6) | Jun 29, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | Notebook    | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [b303b8ce0d](https://linux-hardware.org/?probe=b303b8ce0d) | Jun 07, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [8b904db6cf](https://linux-hardware.org/?probe=8b904db6cf) | Jun 06, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [0ad2309a50](https://linux-hardware.org/?probe=0ad2309a50) | Jun 05, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [374a3fef00](https://linux-hardware.org/?probe=374a3fef00) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [413d6e5373](https://linux-hardware.org/?probe=413d6e5373) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | Desktop     | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | Notebook    | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ab9f37ab3a](https://linux-hardware.org/?probe=ab9f37ab3a) | Oct 27, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| HP            | 1493                        | Desktop     | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | Desktop     | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [a7f61e2b9b](https://linux-hardware.org/?probe=a7f61e2b9b) | May 28, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | Desktop     | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | Notebook    | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Haier         | U144S                       | Notebook    | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a72ab8595e](https://linux-hardware.org/?probe=a72ab8595e) | Jan 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6deddd3d32](https://linux-hardware.org/?probe=6deddd3d32) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | Notebook    | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f483ddc44f](https://linux-hardware.org/?probe=f483ddc44f) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | Notebook    | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Dell          | 02YRK5 A02                  | Desktop     | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | Notebook    | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [84ed224f36](https://linux-hardware.org/?probe=84ed224f36) | Nov 24, 2021 |
| HP            | 21B4 A01                    | Desktop     | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [0297d0f732](https://linux-hardware.org/?probe=0297d0f732) | Oct 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [45b1bba577](https://linux-hardware.org/?probe=45b1bba577) | Oct 24, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [6f87d9f9b8](https://linux-hardware.org/?probe=6f87d9f9b8) | Oct 01, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [2668fd795b](https://linux-hardware.org/?probe=2668fd795b) | Oct 01, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [254589b0bd](https://linux-hardware.org/?probe=254589b0bd) | Sep 16, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [f5bdbbea34](https://linux-hardware.org/?probe=f5bdbbea34) | Sep 15, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Pegatron      | Deepcam                     | Notebook    | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | Notebook    | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | Notebook    | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| Dell          | 0DPRKF A07                  | Server      | [dee1f70644](https://linux-hardware.org/?probe=dee1f70644) | Mar 28, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| F5 Network... | PCA-0377-05                 | Server      | [14c76e0c83](https://linux-hardware.org/?probe=14c76e0c83) | Feb 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0a01176cbe](https://linux-hardware.org/?probe=0a01176cbe) | Feb 23, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | Notebook    | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | Notebook    | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | Notebook    | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| HP            | 2B0D A01                    | All in one  | [5c13b7bb96](https://linux-hardware.org/?probe=5c13b7bb96) | Nov 03, 2020 |
| Google        | Samus                       | Notebook    | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | Desktop     | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Lenovo        | 314C SDK0J40697 WIN 3305... | Mini pc     | [0f66b49a44](https://linux-hardware.org/?probe=0f66b49a44) | Sep 17, 2020 |
| Dell          | 0PU052                      | Desktop     | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Supermicro    | X10SLL-F                    | Server      | [dfbdbb0676](https://linux-hardware.org/?probe=dfbdbb0676) | Aug 25, 2020 |
| ASUSTek       | TS10                        | Desktop     | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| ASRock        | J3455M                      | Desktop     | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | Notebook    | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | Desktop     | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| Intel         | Merrifield                  | Tablet      | [d1f5e15d8c](https://linux-hardware.org/?probe=d1f5e15d8c) | May 23, 2020 |
| HP            | ZBook 15 G5                 | Notebook    | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | Notebook    | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | Notebook    | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | Notebook    | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |
| Unknown       | i855GM/E-ITE8712            | Desktop     | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | Desktop     | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 7.28%   |
| Alpine 3.18.0               | 10        | 6.62%   |
| Alpine 3.15.0               | 10        | 6.62%   |
| Alpine 3.16.0               | 9         | 5.96%   |
| Alpine 3.18.3               | 7         | 4.64%   |
| Alpine 3.15.4               | 7         | 4.64%   |
| Alpine 3.15.0_alpha20210804 | 7         | 4.64%   |
| Alpine 3.17_alpha20220809   | 5         | 3.31%   |
| Alpine 3.17.2               | 5         | 3.31%   |
| Alpine 3.14.0               | 5         | 3.31%   |
| Alpine 3.18.2               | 4         | 2.65%   |
| Alpine 3.17.1               | 4         | 2.65%   |
| Alpine 3.17.0               | 4         | 2.65%   |
| Alpine 3.16.1               | 4         | 2.65%   |
| Alpine 3.14.2               | 4         | 2.65%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.65%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.65%   |
| Alpine 3.11.2               | 4         | 2.65%   |
| Alpine 3.19_alpha20230901   | 3         | 1.99%   |
| Alpine 3.18.4               | 3         | 1.99%   |
| Alpine 3.16.2               | 3         | 1.99%   |
| Alpine 3.13.1               | 3         | 1.99%   |
| Alpine 3.13.0_alpha20201218 | 3         | 1.99%   |
| Alpine 3.18_alpha20230329   | 2         | 1.32%   |
| Alpine 3.16.3               | 2         | 1.32%   |
| Alpine 3.15.6               | 2         | 1.32%   |
| Alpine 3.13.5               | 2         | 1.32%   |
| Alpine 3.13.2               | 2         | 1.32%   |
| Alpine 3.12.3               | 2         | 1.32%   |
| Alpine 3.8.4                | 1         | 0.66%   |
| Alpine 3.17.4               | 1         | 0.66%   |
| Alpine 3.17.3               | 1         | 0.66%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.66%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.66%   |
| Alpine 3.15.2               | 1         | 0.66%   |
| Alpine 3.15.0_rc5           | 1         | 0.66%   |
| Alpine 3.14.3               | 1         | 0.66%   |
| Alpine 3.14.0_alpha20210212 | 1         | 0.66%   |
| Alpine 3.13.6               | 1         | 0.66%   |
| Alpine 3.13.3               | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 139       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.4.43-1-lts     | 8         | 5.19%   |
| 6.1.57-0-lts     | 3         | 1.95%   |
| 6.1.32-0-lts     | 3         | 1.95%   |
| 5.15.86-0-lts    | 3         | 1.95%   |
| 5.15.60-0-lts    | 3         | 1.95%   |
| 5.15.16-0-lts    | 3         | 1.95%   |
| 5.10.61-0-lts    | 3         | 1.95%   |
| 6.1.51-0-lts     | 2         | 1.3%    |
| 6.1.28-2-lts     | 2         | 1.3%    |
| 5.4.84-0-lts     | 2         | 1.3%    |
| 5.4.83-0-lts     | 2         | 1.3%    |
| 5.17.9-0-edge    | 2         | 1.3%    |
| 5.15.74-0-lts    | 2         | 1.3%    |
| 5.15.59-0-lts    | 2         | 1.3%    |
| 5.15.47-0-lts    | 2         | 1.3%    |
| 5.15.46-1-lts    | 2         | 1.3%    |
| 5.15.41-0-lts    | 2         | 1.3%    |
| 5.15.4-0-lts     | 2         | 1.3%    |
| 5.15.12-0-lts    | 2         | 1.3%    |
| 5.10.68-0-lts    | 2         | 1.3%    |
| 5.10.16-0-lts    | 2         | 1.3%    |
| 6.4.4-0-edge     | 1         | 0.65%   |
| 6.3.3-0-edge     | 1         | 0.65%   |
| 6.2.0-36-generic | 1         | 0.65%   |
| 6.1.55-2-lts     | 1         | 0.65%   |
| 6.1.55-0-lts     | 1         | 0.65%   |
| 6.1.54-0-lts     | 1         | 0.65%   |
| 6.1.53-0-lts     | 1         | 0.65%   |
| 6.1.52-0-lts     | 1         | 0.65%   |
| 6.1.46-0-lts     | 1         | 0.65%   |
| 6.1.42-0-lts     | 1         | 0.65%   |
| 6.1.39-0-lts     | 1         | 0.65%   |
| 6.1.36-0-lts     | 1         | 0.65%   |
| 6.1.34-0-lts     | 1         | 0.65%   |
| 6.1.34           | 1         | 0.65%   |
| 6.1.30-0-lts     | 1         | 0.65%   |
| 6.1.24-0-lts     | 1         | 0.65%   |
| 6.1.11-0-edge    | 1         | 0.65%   |
| 6.0.10-0-edge    | 1         | 0.65%   |
| 5.8.12-0-edge    | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 5.23%   |
| 6.1.57  | 3         | 1.96%   |
| 6.1.32  | 3         | 1.96%   |
| 5.15.86 | 3         | 1.96%   |
| 5.15.60 | 3         | 1.96%   |
| 5.15.16 | 3         | 1.96%   |
| 5.10.61 | 3         | 1.96%   |
| 6.1.55  | 2         | 1.31%   |
| 6.1.51  | 2         | 1.31%   |
| 6.1.34  | 2         | 1.31%   |
| 6.1.28  | 2         | 1.31%   |
| 5.4.84  | 2         | 1.31%   |
| 5.4.83  | 2         | 1.31%   |
| 5.19.0  | 2         | 1.31%   |
| 5.17.9  | 2         | 1.31%   |
| 5.15.74 | 2         | 1.31%   |
| 5.15.59 | 2         | 1.31%   |
| 5.15.47 | 2         | 1.31%   |
| 5.15.46 | 2         | 1.31%   |
| 5.15.41 | 2         | 1.31%   |
| 5.15.4  | 2         | 1.31%   |
| 5.15.12 | 2         | 1.31%   |
| 5.15.0  | 2         | 1.31%   |
| 5.10.68 | 2         | 1.31%   |
| 5.10.16 | 2         | 1.31%   |
| 6.4.4   | 1         | 0.65%   |
| 6.3.3   | 1         | 0.65%   |
| 6.2.0   | 1         | 0.65%   |
| 6.1.54  | 1         | 0.65%   |
| 6.1.53  | 1         | 0.65%   |
| 6.1.52  | 1         | 0.65%   |
| 6.1.46  | 1         | 0.65%   |
| 6.1.42  | 1         | 0.65%   |
| 6.1.39  | 1         | 0.65%   |
| 6.1.36  | 1         | 0.65%   |
| 6.1.30  | 1         | 0.65%   |
| 6.1.24  | 1         | 0.65%   |
| 6.1.11  | 1         | 0.65%   |
| 6.0.10  | 1         | 0.65%   |
| 5.8.12  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 50        | 33.78%  |
| 6.1     | 24        | 16.22%  |
| 5.4     | 23        | 15.54%  |
| 5.10    | 23        | 15.54%  |
| 5.17    | 4         | 2.7%    |
| 3.10    | 3         | 2.03%   |
| 5.8     | 2         | 1.35%   |
| 5.19    | 2         | 1.35%   |
| 5.14    | 2         | 1.35%   |
| 4.4     | 2         | 1.35%   |
| 3.18    | 2         | 1.35%   |
| 6.4     | 1         | 0.68%   |
| 6.3     | 1         | 0.68%   |
| 6.2     | 1         | 0.68%   |
| 6.0     | 1         | 0.68%   |
| 5.7     | 1         | 0.68%   |
| 5.6     | 1         | 0.68%   |
| 5.18    | 1         | 0.68%   |
| 5.16    | 1         | 0.68%   |
| 5.13    | 1         | 0.68%   |
| 5.12    | 1         | 0.68%   |
| 4.14    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 115       | 82.73%  |
| i686    | 16        | 11.51%  |
| aarch64 | 4         | 2.88%   |
| armv7l  | 3         | 2.16%   |
| i586    | 1         | 0.72%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 111       | 79.86%  |
| XFCE    | 13        | 9.35%   |
| GNOME   | 6         | 4.32%   |
| KDE5    | 3         | 2.16%   |
| sway    | 2         | 1.44%   |
| LXQt    | 2         | 1.44%   |
| KDE     | 1         | 0.72%   |
| i3      | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 83        | 58.45%  |
| X11     | 49        | 34.51%  |
| Wayland | 9         | 6.34%   |
| Tty     | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 111       | 79.29%  |
| LightDM | 20        | 14.29%  |
| SDDM    | 3         | 2.14%   |
| GDM     | 3         | 2.14%   |
| LXDM    | 2         | 1.43%   |
| XDM     | 1         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 88        | 61.54%  |
| Unknown | 43        | 30.07%  |
| en_US   | 7         | 4.9%    |
| ru_RU   | 3         | 2.1%    |
| pt_BR   | 1         | 0.7%    |
| en_GB   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 93        | 65.96%  |
| EFI  | 48        | 34.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 113       | 79.58%  |
| Btrfs   | 9         | 6.34%   |
| Overlay | 8         | 5.63%   |
| Tmpfs   | 5         | 3.52%   |
| F2fs    | 2         | 1.41%   |
| Unknown | 2         | 1.41%   |
| Zfs     | 1         | 0.7%    |
| Rootfs  | 1         | 0.7%    |
| Ext2    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 90        | 62.07%  |
| GPT     | 39        | 26.9%   |
| MBR     | 16        | 11.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 86.52%  |
| Yes       | 19        | 13.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 92.25%  |
| Yes       | 11        | 7.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 21        | 15.11%  |
| Hewlett-Packard         | 19        | 13.67%  |
| ASUSTek Computer        | 15        | 10.79%  |
| Lenovo                  | 14        | 10.07%  |
| ASRock                  | 8         | 5.76%   |
| Intel                   | 6         | 4.32%   |
| Gigabyte Technology     | 6         | 4.32%   |
| Unknown                 | 6         | 4.32%   |
| Acer                    | 5         | 3.6%    |
| Fujitsu                 | 4         | 2.88%   |
| Toshiba                 | 3         | 2.16%   |
| MSI                     | 3         | 2.16%   |
| IBM                     | 3         | 2.16%   |
| Google                  | 3         | 2.16%   |
| Raspberry Pi Foundation | 2         | 1.44%   |
| Gateway                 | 2         | 1.44%   |
| Apple                   | 2         | 1.44%   |
| VIA Technologies        | 1         | 0.72%   |
| UGREEN                  | 1         | 0.72%   |
| Synology                | 1         | 0.72%   |
| Supermicro              | 1         | 0.72%   |
| Sony                    | 1         | 0.72%   |
| Shuttle                 | 1         | 0.72%   |
| Pegatron                | 1         | 0.72%   |
| Olivetti                | 1         | 0.72%   |
| Notebook                | 1         | 0.72%   |
| LG Electronics          | 1         | 0.72%   |
| Inventec                | 1         | 0.72%   |
| Haier                   | 1         | 0.72%   |
| Fanless Mini PC         | 1         | 0.72%   |
| F5 Networks             | 1         | 0.72%   |
| eMachines               | 1         | 0.72%   |
| ECS                     | 1         | 0.72%   |
| AMI                     | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 4.32%   |
| Dell Dell Thin Client Desktop 3030 LT    | 3         | 2.16%   |
| HP ProLiant DL360 G6                     | 2         | 1.44%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.44%   |
| ASUS All Series                          | 2         | 1.44%   |
| VIA KM266APro-835                        | 1         | 0.72%   |
| UGREEN DX4600                            | 1         | 0.72%   |
| Toshiba WT8-A                            | 1         | 0.72%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.72%   |
| Toshiba Satellite M645                   | 1         | 0.72%   |
| Synology DS1019+                         | 1         | 0.72%   |
| Supermicro X10SLL-F                      | 1         | 0.72%   |
| Sony VGN-UX27GN                          | 1         | 0.72%   |
| Shuttle DS81D                            | 1         | 0.72%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.72%   |
| RPi Raspberry Pi                         | 1         | 0.72%   |
| Pegatron Deepcam                         | 1         | 0.72%   |
| Olivetti Spring Peak                     | 1         | 0.72%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.72%   |
| MSI MS-7C82                              | 1         | 0.72%   |
| MSI MS-7877                              | 1         | 0.72%   |
| MSI GL72M 7REX                           | 1         | 0.72%   |
| LG LW25-B7HG                             | 1         | 0.72%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.72%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.72%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.72%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.72%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.72%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.72%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.72%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.72%   |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.72%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.72%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.72%   |
| Lenovo H535 10117                        | 1         | 0.72%   |
| Lenovo Flex 2-14 20404                   | 1         | 0.72%   |
| Inventec D CLASS                         | 1         | 0.72%   |
| Intel NUC6i7KYB H90766-406               | 1         | 0.72%   |
| Intel Merrifield                         | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 8         | 5.76%   |
| Lenovo ThinkPad     | 7         | 5.04%   |
| Unknown             | 6         | 4.32%   |
| Dell OptiPlex       | 5         | 3.6%    |
| Acer Aspire         | 5         | 3.6%    |
| HP ProLiant         | 3         | 2.16%   |
| HP EliteBook        | 3         | 2.16%   |
| Dell Dell           | 3         | 2.16%   |
| Toshiba Satellite   | 2         | 1.44%   |
| RPi Raspberry       | 2         | 1.44%   |
| Lenovo ThinkCentre  | 2         | 1.44%   |
| HP Presario         | 2         | 1.44%   |
| HP Compaq           | 2         | 1.44%   |
| Gigabyte Z490I      | 2         | 1.44%   |
| Dell XPS            | 2         | 1.44%   |
| ASUS PRIME          | 2         | 1.44%   |
| ASUS All            | 2         | 1.44%   |
| VIA KM266APro-835   | 1         | 0.72%   |
| UGREEN DX4600       | 1         | 0.72%   |
| Toshiba WT8-A       | 1         | 0.72%   |
| Synology DS1019+    | 1         | 0.72%   |
| Supermicro X10SLL-F | 1         | 0.72%   |
| Sony VGN-UX27GN     | 1         | 0.72%   |
| Shuttle DS81D       | 1         | 0.72%   |
| Pegatron Deepcam    | 1         | 0.72%   |
| Olivetti Spring     | 1         | 0.72%   |
| Notebook NV4XMB     | 1         | 0.72%   |
| MSI MS-7C82         | 1         | 0.72%   |
| MSI MS-7877         | 1         | 0.72%   |
| MSI GL72M           | 1         | 0.72%   |
| LG LW25-B7HG        | 1         | 0.72%   |
| Lenovo Yoga         | 1         | 0.72%   |
| Lenovo V14-ADA      | 1         | 0.72%   |
| Lenovo IdeaPad      | 1         | 0.72%   |
| Lenovo H535         | 1         | 0.72%   |
| Lenovo Flex         | 1         | 0.72%   |
| Inventec D          | 1         | 0.72%   |
| Intel NUC6i7KYB     | 1         | 0.72%   |
| Intel Merrifield    | 1         | 0.72%   |
| Intel ECO           | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 18        | 12.95%  |
| 2018    | 11        | 7.91%   |
| 2012    | 11        | 7.91%   |
| 2013    | 9         | 6.47%   |
| 2010    | 9         | 6.47%   |
| 2020    | 8         | 5.76%   |
| 2019    | 8         | 5.76%   |
| 2016    | 8         | 5.76%   |
| Unknown | 8         | 5.76%   |
| 2017    | 7         | 5.04%   |
| 2015    | 6         | 4.32%   |
| 2011    | 6         | 4.32%   |
| 2006    | 6         | 4.32%   |
| 2021    | 5         | 3.6%    |
| 2009    | 5         | 3.6%    |
| 2022    | 3         | 2.16%   |
| 2007    | 3         | 2.16%   |
| 2023    | 2         | 1.44%   |
| 2005    | 2         | 1.44%   |
| 2008    | 1         | 0.72%   |
| 2004    | 1         | 0.72%   |
| 2001    | 1         | 0.72%   |
| 1999    | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 67        | 48.2%   |
| Desktop        | 49        | 35.25%  |
| Mini pc        | 10        | 7.19%   |
| Server         | 5         | 3.6%    |
| System on chip | 4         | 2.88%   |
| Tablet         | 2         | 1.44%   |
| Convertible    | 1         | 0.72%   |
| All in one     | 1         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 139       | 99.29%  |
| Enabled  | 1         | 0.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 97.84%  |
| Yes  | 3         | 2.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 29        | 19.86%  |
| 3.01-4.0        | 28        | 19.18%  |
| 16.01-24.0      | 22        | 15.07%  |
| 8.01-16.0       | 17        | 11.64%  |
| 1.01-2.0        | 13        | 8.9%    |
| 0.51-1.0        | 12        | 8.22%   |
| 32.01-64.0      | 10        | 6.85%   |
| 2.01-3.0        | 5         | 3.42%   |
| 64.01-256.0     | 5         | 3.42%   |
| 0.01-0.5        | 4         | 2.74%   |
| More than 256.0 | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 44        | 29.73%  |
| 1.01-2.0  | 31        | 20.95%  |
| 0.51-1.0  | 27        | 18.24%  |
| 2.01-3.0  | 15        | 10.14%  |
| 3.01-4.0  | 11        | 7.43%   |
| 4.01-8.0  | 9         | 6.08%   |
| 8.01-16.0 | 5         | 3.38%   |
| 0         | 3         | 2.03%   |
| Unknown   | 3         | 2.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 63.19%  |
| 2      | 28        | 19.44%  |
| 3      | 8         | 5.56%   |
| 4      | 7         | 4.86%   |
| 5      | 3         | 2.08%   |
| 14     | 2         | 1.39%   |
| 0      | 2         | 1.39%   |
| 12     | 1         | 0.69%   |
| 10     | 1         | 0.69%   |
| 7      | 1         | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 80.14%  |
| Yes       | 28        | 19.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 85.61%  |
| No        | 20        | 14.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 58.16%  |
| No        | 59        | 41.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 58.87%  |
| Yes       | 58        | 41.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34        | 23.45%  |
| Germany      | 16        | 11.03%  |
| Canada       | 13        | 8.97%   |
| Russia       | 12        | 8.28%   |
| UK           | 9         | 6.21%   |
| Brazil       | 6         | 4.14%   |
| Sweden       | 5         | 3.45%   |
| Spain        | 5         | 3.45%   |
| Australia    | 4         | 2.76%   |
| Norway       | 3         | 2.07%   |
| China        | 3         | 2.07%   |
| Portugal     | 2         | 1.38%   |
| Poland       | 2         | 1.38%   |
| Netherlands  | 2         | 1.38%   |
| Mexico       | 2         | 1.38%   |
| Italy        | 2         | 1.38%   |
| Guatemala    | 2         | 1.38%   |
| Argentina    | 2         | 1.38%   |
| Venezuela    | 1         | 0.69%   |
| Ukraine      | 1         | 0.69%   |
| UAE          | 1         | 0.69%   |
| Switzerland  | 1         | 0.69%   |
| South Korea  | 1         | 0.69%   |
| South Africa | 1         | 0.69%   |
| Slovakia     | 1         | 0.69%   |
| Philippines  | 1         | 0.69%   |
| Pakistan     | 1         | 0.69%   |
| Kenya        | 1         | 0.69%   |
| Jamaica      | 1         | 0.69%   |
| Israel       | 1         | 0.69%   |
| Indonesia    | 1         | 0.69%   |
| Hungary      | 1         | 0.69%   |
| Greece       | 1         | 0.69%   |
| France       | 1         | 0.69%   |
| Finland      | 1         | 0.69%   |
| Egypt        | 1         | 0.69%   |
| Denmark      | 1         | 0.69%   |
| Czechia      | 1         | 0.69%   |
| Austria      | 1         | 0.69%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 4.73%   |
| St Petersburg     | 6         | 4.05%   |
| Manitowoc         | 5         | 3.38%   |
| Vernon            | 4         | 2.7%    |
| Moscow            | 3         | 2.03%   |
| Sydney            | 2         | 1.35%   |
| Stratford         | 2         | 1.35%   |
| Siegsdorf         | 2         | 1.35%   |
| Guatemala City    | 2         | 1.35%   |
| Gothenburg        | 2         | 1.35%   |
| Fulham            | 2         | 1.35%   |
| Frankfurt am Main | 2         | 1.35%   |
| As                | 2         | 1.35%   |
| Zurich            | 1         | 0.68%   |
| Zhangzhou         | 1         | 0.68%   |
| Yakima            | 1         | 0.68%   |
| Vejle             | 1         | 0.68%   |
| Vancouver         | 1         | 0.68%   |
| Tymovskoye        | 1         | 0.68%   |
| Tuusula           | 1         | 0.68%   |
| Turin             | 1         | 0.68%   |
| Traunstein        | 1         | 0.68%   |
| Topeka            | 1         | 0.68%   |
| Thornhill         | 1         | 0.68%   |
| Thame             | 1         | 0.68%   |
| Tampa             | 1         | 0.68%   |
| Stuttgart         | 1         | 0.68%   |
| Stockholm         | 1         | 0.68%   |
| Stewartstown      | 1         | 0.68%   |
| Somerset          | 1         | 0.68%   |
| Ski               | 1         | 0.68%   |
| Sisteron          | 1         | 0.68%   |
| Semily            | 1         | 0.68%   |
| Seattle           | 1         | 0.68%   |
| Sao Paulo         | 1         | 0.68%   |
| San Mateo         | 1         | 0.68%   |
| Salzburg          | 1         | 0.68%   |
| Saarbrücken      | 1         | 0.68%   |
| Rzeszów          | 1         | 0.68%   |
| Rostock           | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 48     | 14%     |
| WDC                         | 24        | 54     | 12%     |
| Unknown                     | 18        | 22     | 9%      |
| Seagate                     | 17        | 47     | 8.5%    |
| Toshiba                     | 16        | 18     | 8%      |
| Hitachi                     | 11        | 11     | 5.5%    |
| Kingston                    | 10        | 14     | 5%      |
| HGST                        | 10        | 10     | 5%      |
| Crucial                     | 10        | 18     | 5%      |
| Intel                       | 7         | 11     | 3.5%    |
| SK hynix                    | 6         | 8      | 3%      |
| SanDisk                     | 6         | 8      | 3%      |
| A-DATA Technology           | 6         | 8      | 3%      |
| SPCC                        | 3         | 3      | 1.5%    |
| Transcend                   | 2         | 2      | 1%      |
| LITEON                      | 2         | 2      | 1%      |
| Intenso                     | 2         | 2      | 1%      |
| Fujitsu                     | 2         | 2      | 1%      |
| STEC                        | 1         | 1      | 0.5%    |
| SINTECHI                    | 1         | 1      | 0.5%    |
| Secure                      | 1         | 1      | 0.5%    |
| PNY                         | 1         | 1      | 0.5%    |
| Phison Electronics          | 1         | 1      | 0.5%    |
| NETAPP                      | 1         | 1      | 0.5%    |
| Micron Technology           | 1         | 1      | 0.5%    |
| Lexar                       | 1         | 1      | 0.5%    |
| KIOXIA                      | 1         | 1      | 0.5%    |
| Kingston Technology Company | 1         | 1      | 0.5%    |
| Kingmax                     | 1         | 1      | 0.5%    |
| KC600                       | 1         | 1      | 0.5%    |
| JMicron Technology          | 1         | 1      | 0.5%    |
| IBM                         | 1         | 1      | 0.5%    |
| Emtec                       | 1         | 1      | 0.5%    |
| Dell                        | 1         | 2      | 0.5%    |
| China                       | 1         | 1      | 0.5%    |
| Apple                       | 1         | 3      | 0.5%    |
| AMD                         | 1         | 1      | 0.5%    |
| Unknown                     | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                            | 5         | 2.13%   |
| Unknown MMC Card  4GB                             | 4         | 1.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.7%    |
| Unknown MMC Card  32GB                            | 3         | 1.28%   |
| WDC WD3000BLFS-60YBU2 304GB                       | 2         | 0.85%   |
| Unknown MMC Card  64GB                            | 2         | 0.85%   |
| Unknown MMC Card                                  | 2         | 0.85%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.85%   |
| Toshiba MQ01ABD075 752GB                          | 2         | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 2         | 0.85%   |
| Seagate ST4000VN008-2DR1 4TB                      | 2         | 0.85%   |
| Seagate ST380815AS 80GB                           | 2         | 0.85%   |
| Samsung SSD 960 EVO 500GB                         | 2         | 0.85%   |
| Samsung SSD 870 QVO 1TB                           | 2         | 0.85%   |
| Samsung SSD 870 EVO 1TB                           | 2         | 0.85%   |
| Samsung NVMe SSD Drive 1024GB                     | 2         | 0.85%   |
| Kingston SV300S37A120G 120GB SSD                  | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.85%   |
| Kingston SA400S3 120GB SSD                        | 2         | 0.85%   |
| Intenso SSD 128GB                                 | 2         | 0.85%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 0.85%   |
| Crucial CT120BX500SSD1 120GB                      | 2         | 0.85%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 0.85%   |
| WDC WDS500G2X0C-00L350 500GB                      | 1         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.43%   |
| WDC WDS500G2B0A 500GB SSD                         | 1         | 0.43%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.43%   |
| WDC WDS250G2B0B 250GB SSD                         | 1         | 0.43%   |
| WDC WDS250G2B0A 250GB SSD                         | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 0.43%   |
| WDC WD80EMAZ-00WJTA0 8TB                          | 1         | 0.43%   |
| WDC WD80EFAX-68LHPN0 8TB                          | 1         | 0.43%   |
| WDC WD800AAJS-00 80GB                             | 1         | 0.43%   |
| WDC WD7500BPKT-80PK4T0 752GB                      | 1         | 0.43%   |
| WDC WD5003ABYZ-0 500GB                            | 1         | 0.43%   |
| WDC WD5000BEVT-22ZAT0 500GB                       | 1         | 0.43%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1         | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 1         | 0.43%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1         | 0.43%   |
| WDC WD3200AAKX-0 320GB                            | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 45     | 23.38%  |
| Seagate             | 17        | 47     | 22.08%  |
| Toshiba             | 13        | 14     | 16.88%  |
| Hitachi             | 11        | 11     | 14.29%  |
| HGST                | 10        | 10     | 12.99%  |
| Samsung Electronics | 4         | 7      | 5.19%   |
| Fujitsu             | 2         | 2      | 2.6%    |
| SINTECHI            | 1         | 1      | 1.3%    |
| IBM                 | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 18     | 15.94%  |
| Kingston            | 10        | 12     | 14.49%  |
| Crucial             | 10        | 18     | 14.49%  |
| Intel               | 5         | 7      | 7.25%   |
| WDC                 | 4         | 6      | 5.8%    |
| A-DATA Technology   | 4         | 4      | 5.8%    |
| SPCC                | 3         | 3      | 4.35%   |
| SanDisk             | 3         | 4      | 4.35%   |
| Transcend           | 2         | 2      | 2.9%    |
| SK hynix            | 2         | 3      | 2.9%    |
| LITEON              | 2         | 2      | 2.9%    |
| Intenso             | 2         | 2      | 2.9%    |
| Toshiba             | 1         | 1      | 1.45%   |
| Secure              | 1         | 1      | 1.45%   |
| PNY                 | 1         | 1      | 1.45%   |
| Micron Technology   | 1         | 1      | 1.45%   |
| Lexar               | 1         | 1      | 1.45%   |
| Kingmax             | 1         | 1      | 1.45%   |
| KC600               | 1         | 1      | 1.45%   |
| Emtec               | 1         | 1      | 1.45%   |
| Dell                | 1         | 2      | 1.45%   |
| China               | 1         | 1      | 1.45%   |
| AMD                 | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 138    | 38.51%  |
| SSD     | 56        | 93     | 32.18%  |
| NVMe    | 32        | 55     | 18.39%  |
| MMC     | 18        | 23     | 10.34%  |
| Unknown | 1         | 2      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 227    | 65.38%  |
| NVMe | 31        | 54     | 19.87%  |
| MMC  | 18        | 23     | 11.54%  |
| SAS  | 5         | 7      | 3.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 139    | 66.4%   |
| 0.51-1.0   | 23        | 34     | 18.4%   |
| 3.01-4.0   | 5         | 16     | 4%      |
| 4.01-10.0  | 5         | 21     | 4%      |
| 1.01-2.0   | 4         | 6      | 3.2%    |
| 10.01-20.0 | 3         | 13     | 2.4%    |
| 2.01-3.0   | 2         | 2      | 1.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 20.14%  |
| Unknown        | 26        | 18.06%  |
| 1-20           | 25        | 17.36%  |
| 251-500        | 14        | 9.72%   |
| 21-50          | 12        | 8.33%   |
| 501-1000       | 12        | 8.33%   |
| 1001-2000      | 8         | 5.56%   |
| More than 3000 | 7         | 4.86%   |
| 51-100         | 7         | 4.86%   |
| 2001-3000      | 4         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 55.94%  |
| Unknown        | 26        | 18.18%  |
| 251-500        | 9         | 6.29%   |
| 21-50          | 9         | 6.29%   |
| 51-100         | 8         | 5.59%   |
| 501-1000       | 4         | 2.8%    |
| 101-250        | 3         | 2.1%    |
| 1001-2000      | 2         | 1.4%    |
| More than 3000 | 1         | 0.7%    |
| 2001-3000      | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 9.09%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 4.55%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 4.55%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 4.55%   |
| Secure Net 256GB SSD                           | 1         | 1      | 4.55%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 4.55%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 4.55%   |
| Samsung Electronics SSD PM81 128GB             | 1         | 1      | 4.55%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 4.55%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 4.55%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 4.55%   |
| Kingmax SSD 120G                               | 1         | 1      | 4.55%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 4.55%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 4.55%   |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 4.55%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 4.55%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 4.55%   |
| HGST HTS725050A7 500GB                         | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 4.55%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 4.55%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 22.73%  |
| WDC                 | 3         | 15     | 13.64%  |
| Samsung Electronics | 3         | 5      | 13.64%  |
| HGST                | 3         | 3      | 13.64%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Secure              | 1         | 1      | 4.55%   |
| Seagate             | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Kingmax             | 1         | 1      | 4.55%   |
| A-DATA Technology   | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 31.25%  |
| WDC                 | 3         | 15     | 18.75%  |
| HGST                | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 4      | 12.5%   |
| Seagate             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 30     | 72.73%  |
| SSD  | 5         | 5      | 22.73%  |
| NVMe | 1         | 1      | 4.55%   |

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
| Works    | 87        | 198    | 56.49%  |
| Detected | 47        | 77     | 30.52%  |
| Malfunc  | 20        | 36     | 12.99%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 56.79%  |
| Samsung Electronics          | 17        | 10.49%  |
| AMD                          | 17        | 10.49%  |
| SanDisk                      | 5         | 3.09%   |
| LSI Logic / Symbios Logic    | 4         | 2.47%   |
| SK hynix                     | 3         | 1.85%   |
| Marvell Technology Group     | 3         | 1.85%   |
| ADATA Technology             | 3         | 1.85%   |
| VIA Technologies             | 2         | 1.23%   |
| Nvidia                       | 2         | 1.23%   |
| KIOXIA                       | 2         | 1.23%   |
| Hewlett-Packard              | 2         | 1.23%   |
| ASMedia Technology           | 2         | 1.23%   |
| Adaptec                      | 2         | 1.23%   |
| Toshiba America Info Systems | 1         | 0.62%   |
| Promise Technology           | 1         | 0.62%   |
| Phison Electronics           | 1         | 0.62%   |
| Micron/Crucial Technology    | 1         | 0.62%   |
| Kingston Technology Company  | 1         | 0.62%   |
| Broadcom / LSI               | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 6.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 5.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 5.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 3.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 2.59%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 2.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.55%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2         | 1.04%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.04%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.04%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2         | 1.04%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 87        | 55.41%  |
| NVMe | 30        | 19.11%  |
| IDE  | 23        | 14.65%  |
| RAID | 13        | 8.28%   |
| SAS  | 4         | 2.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 112       | 79.43%  |
| AMD          | 21        | 14.89%  |
| ARM          | 6         | 4.26%   |
| CentaurHauls | 1         | 0.71%   |
| Unknown      | 1         | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Celeron CPU N2807 @ 1.58GHz      | 3         | 2.07%   |
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 1.38%   |
| Intel Pentium M processor 1.70GHz      | 2         | 1.38%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 1.38%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 1.38%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 1.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 2         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 1.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 1.38%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 1.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 1.38%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 1.38%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2         | 1.38%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 1.38%   |
| ARM Processor                          | 2         | 1.38%   |
| AMD FX-8350 Eight-Core Processor       | 2         | 1.38%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 0.69%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 0.69%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 0.69%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 0.69%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 0.69%   |
| Intel Pentium M processor 1.60GHz      | 1         | 0.69%   |
| Intel Pentium M processor 1.50GHz      | 1         | 0.69%   |
| Intel Pentium III (Coppermine)         | 1         | 0.69%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1         | 0.69%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 0.69%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 0.69%   |
| Intel Mobile Pentium MMX               | 1         | 0.69%   |
| Intel Genuine CPU T2400 @ 1.83GHz      | 1         | 0.69%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 0.69%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 0.69%   |
| Intel Core m3-8100Y CPU @ 1.10GHz      | 1         | 0.69%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 0.69%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1         | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1         | 0.69%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 0.69%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 0.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 30        | 20.83%  |
| Intel Celeron        | 17        | 11.81%  |
| Other                | 14        | 9.72%   |
| Intel Core i7        | 12        | 8.33%   |
| Intel Core i3        | 11        | 7.64%   |
| Intel Atom           | 9         | 6.25%   |
| Intel Xeon           | 6         | 4.17%   |
| Intel Pentium M      | 4         | 2.78%   |
| Intel Pentium        | 3         | 2.08%   |
| Intel Core i9        | 3         | 2.08%   |
| Intel Core 2 Duo     | 3         | 2.08%   |
| AMD Ryzen 7          | 3         | 2.08%   |
| Intel Genuine        | 2         | 1.39%   |
| Intel Core 2         | 2         | 1.39%   |
| AMD Ryzen 5          | 2         | 1.39%   |
| AMD FX               | 2         | 1.39%   |
| AMD A4               | 2         | 1.39%   |
| Intel Xeon Gold      | 1         | 0.69%   |
| Intel Pentium III    | 1         | 0.69%   |
| Intel Pentium Dual   | 1         | 0.69%   |
| Intel Core Solo      | 1         | 0.69%   |
| Intel Core m3        | 1         | 0.69%   |
| Intel Celeron M      | 1         | 0.69%   |
| ARM BCM              | 1         | 0.69%   |
| ARM ARMv7            | 1         | 0.69%   |
| ARM AArch64          | 1         | 0.69%   |
| AMD Turion 64 Mobile | 1         | 0.69%   |
| AMD Sempron          | 1         | 0.69%   |
| AMD Ryzen 9          | 1         | 0.69%   |
| AMD Ryzen 3          | 1         | 0.69%   |
| AMD G                | 1         | 0.69%   |
| AMD E2               | 1         | 0.69%   |
| AMD E1               | 1         | 0.69%   |
| AMD A8               | 1         | 0.69%   |
| AMD A6               | 1         | 0.69%   |
| AMD A10              | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 58        | 40.56%  |
| 4       | 44        | 30.77%  |
| 1       | 16        | 11.19%  |
| 8       | 6         | 4.2%    |
| 12      | 4         | 2.8%    |
| 6       | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| 10      | 2         | 1.4%    |
| 32      | 1         | 0.7%    |
| 24      | 1         | 0.7%    |
| 16      | 1         | 0.7%    |
| 14      | 1         | 0.7%    |
| 3       | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 131       | 93.57%  |
| 2       | 4         | 2.86%   |
| Unknown | 4         | 2.86%   |
| 0       | 1         | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 72        | 51.8%   |
| 2       | 63        | 45.32%  |
| Unknown | 4         | 2.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 74        | 52.11%  |
| 32-bit, 64-bit | 62        | 43.66%  |
| 32-bit         | 5         | 3.52%   |
| 64-bit         | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 57.43%  |
| 0x306c3    | 7         | 4.73%   |
| 0x306a9    | 5         | 3.38%   |
| 0x30678    | 5         | 3.38%   |
| 0x906ea    | 4         | 2.7%    |
| 0x206c2    | 3         | 2.03%   |
| 0x806eb    | 2         | 1.35%   |
| 0x506c9    | 2         | 1.35%   |
| 0x406c4    | 2         | 1.35%   |
| 0x206a7    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x106e5    | 2         | 1.35%   |
| 0x106ca    | 2         | 1.35%   |
| 0x06006704 | 2         | 1.35%   |
| 0xb0671    | 1         | 0.68%   |
| 0xa0671    | 1         | 0.68%   |
| 0xa0655    | 1         | 0.68%   |
| 0x906a3    | 1         | 0.68%   |
| 0x90672    | 1         | 0.68%   |
| 0x806ec    | 1         | 0.68%   |
| 0x806c1    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x6fd      | 1         | 0.68%   |
| 0x6f2      | 1         | 0.68%   |
| 0x6d8      | 1         | 0.68%   |
| 0x683      | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x1067a    | 1         | 0.68%   |
| 0x08701021 | 1         | 0.68%   |
| 0x08108109 | 1         | 0.68%   |
| 0x08108102 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x0800820d | 1         | 0.68%   |
| 0x06000817 | 1         | 0.68%   |
| 0x05000101 | 1         | 0.68%   |
| 0x010000b6 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 15        | 10.42%  |
| KabyLake         | 15        | 10.42%  |
| Haswell          | 13        | 9.03%   |
| Unknown          | 12        | 8.33%   |
| P6               | 8         | 5.56%   |
| Westmere         | 7         | 4.86%   |
| SandyBridge      | 7         | 4.86%   |
| IvyBridge        | 7         | 4.86%   |
| Skylake          | 6         | 4.17%   |
| Goldmont         | 5         | 3.47%   |
| Penryn           | 4         | 2.78%   |
| Broadwell        | 4         | 2.78%   |
| Bonnell          | 4         | 2.78%   |
| Zen+             | 3         | 2.08%   |
| Piledriver       | 3         | 2.08%   |
| Excavator        | 3         | 2.08%   |
| Core             | 3         | 2.08%   |
| CometLake        | 3         | 2.08%   |
| Alderlake Hybrid | 3         | 2.08%   |
| Zen 2            | 2         | 1.39%   |
| TigerLake        | 2         | 1.39%   |
| Nehalem          | 2         | 1.39%   |
| Jaguar           | 2         | 1.39%   |
| IceLake          | 2         | 1.39%   |
| Bobcat           | 2         | 1.39%   |
| Zen 3            | 1         | 0.69%   |
| Zen              | 1         | 0.69%   |
| Puma             | 1         | 0.69%   |
| K8 Hammer        | 1         | 0.69%   |
| K6               | 1         | 0.69%   |
| K10              | 1         | 0.69%   |
| Goldmont plus    | 1         | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 96        | 64.43%  |
| AMD                        | 31        | 20.81%  |
| Nvidia                     | 13        | 8.72%   |
| Matrox Electronics Systems | 4         | 2.68%   |
| VIA Technologies           | 2         | 1.34%   |
| Neomagic                   | 2         | 1.34%   |
| ASPEED Technology          | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 7.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.55%   |
| Intel HD Graphics 500                                                                    | 4         | 2.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.78%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.78%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.78%   |
| AMD ES1000                                                                               | 3         | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.18%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.18%   |
| Intel HD Graphics 630                                                                    | 2         | 1.18%   |
| Intel HD Graphics 620                                                                    | 2         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.18%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.18%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.18%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.18%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.18%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.18%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1         | 0.59%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.59%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.59%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 78        | 54.17%  |
| 1 x AMD         | 25        | 17.36%  |
| Other           | 8         | 5.56%   |
| 2 x Intel       | 7         | 4.86%   |
| Intel + Nvidia  | 7         | 4.86%   |
| 1 x Nvidia      | 4         | 2.78%   |
| Intel + AMD     | 4         | 2.78%   |
| 1 x Matrox      | 3         | 2.08%   |
| 1 x Neomagic    | 2         | 1.39%   |
| 2 x AMD         | 1         | 0.69%   |
| 1 x VIA         | 1         | 0.69%   |
| Nvidia + Matrox | 1         | 0.69%   |
| 1 x ASPEED      | 1         | 0.69%   |
| AMD + VIA       | 1         | 0.69%   |
| AMD + Nvidia    | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 81.82%  |
| Unknown     | 23        | 16.08%  |
| Proprietary | 3         | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 85.11%  |
| 0.01-0.5   | 9         | 6.38%   |
| 7.01-8.0   | 3         | 2.13%   |
| 1.01-2.0   | 3         | 2.13%   |
| 3.01-4.0   | 2         | 1.42%   |
| 0.51-1.0   | 2         | 1.42%   |
| 2.01-3.0   | 1         | 0.71%   |
| 8.01-16.0  | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 12.61%  |
| LG Display              | 11        | 9.24%   |
| Dell                    | 10        | 8.4%    |
| Samsung Electronics     | 9         | 7.56%   |
| BOE                     | 8         | 6.72%   |
| Goldstar                | 7         | 5.88%   |
| Chimei Innolux          | 7         | 5.88%   |
| BenQ                    | 5         | 4.2%    |
| AOC                     | 4         | 3.36%   |
| LG Philips              | 3         | 2.52%   |
| InfoVision              | 3         | 2.52%   |
| Hewlett-Packard         | 3         | 2.52%   |
| Chi Mei Optoelectronics | 3         | 2.52%   |
| Acer                    | 3         | 2.52%   |
| Sharp                   | 2         | 1.68%   |
| Philips                 | 2         | 1.68%   |
| Lenovo                  | 2         | 1.68%   |
| Jean                    | 2         | 1.68%   |
| ViewSonic               | 1         | 0.84%   |
| Sony                    | 1         | 0.84%   |
| SKY                     | 1         | 0.84%   |
| Sceptre Tech            | 1         | 0.84%   |
| Quanta Display          | 1         | 0.84%   |
| PANDA                   | 1         | 0.84%   |
| ONN                     | 1         | 0.84%   |
| Mi                      | 1         | 0.84%   |
| KVM                     | 1         | 0.84%   |
| HannStar                | 1         | 0.84%   |
| Envision                | 1         | 0.84%   |
| Elo Touch               | 1         | 0.84%   |
| Element                 | 1         | 0.84%   |
| EDI                     | 1         | 0.84%   |
| DENON                   | 1         | 0.84%   |
| CTC                     | 1         | 0.84%   |
| CSO                     | 1         | 0.84%   |
| CPT                     | 1         | 0.84%   |
| Belinea                 | 1         | 0.84%   |
| Apple                   | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 3         | 2.34%   |
| Dell 2009W DEL4041 1680x1050 433x271mm 20.1-inch                      | 3         | 2.34%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.56%   |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.56%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.78%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.78%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.78%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.78%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.78%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch    | 1         | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.78%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.78%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.78%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.78%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.78%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1         | 0.78%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.78%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.78%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.78%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 0.78%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 0.78%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch          | 1         | 0.78%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 26.72%  |
| 1366x768 (WXGA)    | 26        | 22.41%  |
| 1680x1050 (WSXGA+) | 7         | 6.03%   |
| 3840x2160 (4K)     | 6         | 5.17%   |
| 1280x800 (WXGA)    | 6         | 5.17%   |
| 1280x1024 (SXGA)   | 6         | 5.17%   |
| 2560x1440 (QHD)    | 5         | 4.31%   |
| 3440x1440          | 4         | 3.45%   |
| 1920x1200 (WUXGA)  | 4         | 3.45%   |
| 1024x768 (XGA)     | 4         | 3.45%   |
| 1600x900 (HD+)     | 3         | 2.59%   |
| 1024x600           | 3         | 2.59%   |
| 2560x1080          | 2         | 1.72%   |
| 1440x900 (WXGA+)   | 2         | 1.72%   |
| 1360x768           | 2         | 1.72%   |
| 1280x768           | 2         | 1.72%   |
| 2880x1800          | 1         | 0.86%   |
| 2560x1700          | 1         | 0.86%   |
| 1280x960           | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 26        | 21.67%  |
| 14     | 13        | 10.83%  |
| 13     | 9         | 7.5%    |
| 17     | 8         | 6.67%   |
| 27     | 7         | 5.83%   |
| 24     | 6         | 5%      |
| 23     | 6         | 5%      |
| 20     | 5         | 4.17%   |
| 11     | 5         | 4.17%   |
| 34     | 4         | 3.33%   |
| 21     | 4         | 3.33%   |
| 19     | 4         | 3.33%   |
| 12     | 4         | 3.33%   |
| 22     | 3         | 2.5%    |
| 10     | 3         | 2.5%    |
| 32     | 2         | 1.67%   |
| 31     | 2         | 1.67%   |
| 18     | 2         | 1.67%   |
| 72     | 1         | 0.83%   |
| 65     | 1         | 0.83%   |
| 60     | 1         | 0.83%   |
| 40     | 1         | 0.83%   |
| 29     | 1         | 0.83%   |
| 25     | 1         | 0.83%   |
| 16     | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 42.48%  |
| 501-600     | 17        | 15.04%  |
| 201-300     | 15        | 13.27%  |
| 401-500     | 13        | 11.5%   |
| 351-400     | 7         | 6.19%   |
| 701-800     | 5         | 4.42%   |
| 601-700     | 4         | 3.54%   |
| 1001-1500   | 2         | 1.77%   |
| 801-900     | 1         | 0.88%   |
| 1501-2000   | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 69        | 65.09%  |
| 16/10 | 20        | 18.87%  |
| 5/4   | 6         | 5.66%   |
| 21/9  | 5         | 4.72%   |
| 4/3   | 4         | 3.77%   |
| 6/5   | 1         | 0.94%   |
| 3/2   | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 21.93%  |
| 81-90          | 19        | 16.67%  |
| 201-250        | 14        | 12.28%  |
| 151-200        | 10        | 8.77%   |
| 301-350        | 8         | 7.02%   |
| 351-500        | 7         | 6.14%   |
| 51-60          | 5         | 4.39%   |
| 141-150        | 5         | 4.39%   |
| 71-80          | 4         | 3.51%   |
| More than 1000 | 3         | 2.63%   |
| 61-70          | 3         | 2.63%   |
| 41-50          | 3         | 2.63%   |
| 251-300        | 2         | 1.75%   |
| 131-140        | 2         | 1.75%   |
| 121-130        | 2         | 1.75%   |
| 111-120        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 36.45%  |
| 101-120       | 30        | 28.04%  |
| 121-160       | 25        | 23.36%  |
| 1-50          | 7         | 6.54%   |
| 161-240       | 4         | 3.74%   |
| More than 240 | 2         | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 96        | 66.67%  |
| 0     | 37        | 25.69%  |
| 2     | 9         | 6.25%   |
| 4     | 1         | 0.69%   |
| 3     | 1         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 70        | 34.15%  |
| Intel                           | 64        | 31.22%  |
| Qualcomm Atheros                | 21        | 10.24%  |
| Broadcom                        | 19        | 9.27%   |
| Xiaomi                          | 3         | 1.46%   |
| Marvell Technology Group        | 3         | 1.46%   |
| VIA Technologies                | 2         | 0.98%   |
| Qualcomm Atheros Communications | 2         | 0.98%   |
| Qualcomm                        | 2         | 0.98%   |
| MediaTek                        | 2         | 0.98%   |
| LSI                             | 2         | 0.98%   |
| Broadcom Limited                | 2         | 0.98%   |
| TP-Link                         | 1         | 0.49%   |
| T & A Mobile Phones             | 1         | 0.49%   |
| Sigma Designs                   | 1         | 0.49%   |
| Nvidia                          | 1         | 0.49%   |
| NetGear                         | 1         | 0.49%   |
| Microchip Technology            | 1         | 0.49%   |
| Mellanox Technologies           | 1         | 0.49%   |
| Google                          | 1         | 0.49%   |
| Dresden Elektronik              | 1         | 0.49%   |
| DisplayLink                     | 1         | 0.49%   |
| D-Link System                   | 1         | 0.49%   |
| ASIX Electronics                | 1         | 0.49%   |
| AMD                             | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 17.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.78%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.59%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.19%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.19%   |
| Intel Wireless 7265                                               | 3         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.79%   |
| Intel Wireless-AC 9260                                            | 2         | 0.79%   |
| Intel Wireless 8260                                               | 2         | 0.79%   |
| Intel Wireless 3160                                               | 2         | 0.79%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.79%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.79%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.79%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.79%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 45.05%  |
| Qualcomm Atheros                | 18        | 19.78%  |
| Broadcom                        | 12        | 13.19%  |
| Realtek Semiconductor           | 11        | 12.09%  |
| Qualcomm Atheros Communications | 2         | 2.2%    |
| MediaTek                        | 2         | 2.2%    |
| Broadcom Limited                | 2         | 2.2%    |
| TP-Link                         | 1         | 1.1%    |
| NetGear                         | 1         | 1.1%    |
| Marvell Technology Group        | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 9         | 9.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 3.19%   |
| Intel Wireless 7265                                                            | 3         | 3.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3         | 3.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.13%   |
| Intel Wireless-AC 9260                                                         | 2         | 2.13%   |
| Intel Wireless 8260                                                            | 2         | 2.13%   |
| Intel Wireless 3160                                                            | 2         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 2.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 2         | 2.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 2.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.06%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.06%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.06%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.06%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.06%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1         | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.06%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.06%   |
| Intel Wireless 7260                                                            | 1         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 47.1%   |
| Intel                    | 41        | 29.71%  |
| Broadcom                 | 11        | 7.97%   |
| Qualcomm Atheros         | 4         | 2.9%    |
| Xiaomi                   | 3         | 2.17%   |
| VIA Technologies         | 2         | 1.45%   |
| Qualcomm                 | 2         | 1.45%   |
| Marvell Technology Group | 2         | 1.45%   |
| T & A Mobile Phones      | 1         | 0.72%   |
| Nvidia                   | 1         | 0.72%   |
| Microchip Technology     | 1         | 0.72%   |
| Mellanox Technologies    | 1         | 0.72%   |
| LSI                      | 1         | 0.72%   |
| DisplayLink              | 1         | 0.72%   |
| D-Link System            | 1         | 0.72%   |
| ASIX Electronics         | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 29.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 4.73%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 2.7%    |
| Intel I210 Gigabit Network Connection                             | 4         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 2.03%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.03%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.35%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.35%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.68%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 0.68%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.68%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.68%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.68%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.68%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 0.68%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.68%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.68%   |
| Intel Ethernet Controller I219-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 56.19%  |
| WiFi     | 82        | 39.05%  |
| Modem    | 8         | 3.81%   |
| Unknown  | 2         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 81        | 62.31%  |
| WiFi     | 49        | 37.69%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 51.06%  |
| 1     | 50        | 35.46%  |
| 0     | 11        | 7.8%    |
| 4     | 3         | 2.13%   |
| 3     | 3         | 2.13%   |
| 5     | 2         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 82.86%  |
| Yes  | 24        | 17.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 40%     |
| Qualcomm Atheros Communications | 5         | 7.69%   |
| IMC Networks                    | 5         | 7.69%   |
| Cambridge Silicon Radio         | 5         | 7.69%   |
| Broadcom                        | 5         | 7.69%   |
| Realtek Semiconductor           | 3         | 4.62%   |
| Lite-On Technology              | 3         | 4.62%   |
| Apple                           | 3         | 4.62%   |
| Foxconn / Hon Hai               | 2         | 3.08%   |
| Toshiba                         | 1         | 1.54%   |
| MediaTek                        | 1         | 1.54%   |
| Marvell Semiconductor           | 1         | 1.54%   |
| Hewlett-Packard                 | 1         | 1.54%   |
| Edimax Technology               | 1         | 1.54%   |
| ASUSTek Computer                | 1         | 1.54%   |
| Alps Electric                   | 1         | 1.54%   |
| Actions                         | 1         | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 13.85%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.69%   |
| Intel AX201 Bluetooth                               | 5         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.62%   |
| Realtek Bluetooth Radio                             | 2         | 3.08%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.08%   |
| Intel Bluetooth Device                              | 2         | 3.08%   |
| Intel AX200 Bluetooth                               | 2         | 3.08%   |
| IMC Networks Bluetooth Device                       | 2         | 3.08%   |
| Apple Bluetooth Host Controller                     | 2         | 3.08%   |
| Toshiba Bluetooth Device                            | 1         | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.54%   |
| MediaTek Wireless_Device                            | 1         | 1.54%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.54%   |
| Intel AX210 Bluetooth                               | 1         | 1.54%   |
| IMC Networks Wireless_Device                        | 1         | 1.54%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.54%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.54%   |
| Edimax Bluetooth Adapter                            | 1         | 1.54%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.54%   |
| Broadcom BCM20702A0                                 | 1         | 1.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.54%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.54%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.54%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.54%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.54%   |
| Actions general adapter                             | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 95        | 66.43%  |
| AMD                                  | 26        | 18.18%  |
| Nvidia                               | 6         | 4.2%    |
| VIA Technologies                     | 2         | 1.4%    |
| Logitech                             | 2         | 1.4%    |
| C-Media Electronics                  | 2         | 1.4%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.7%    |
| Texas Instruments                    | 1         | 0.7%    |
| Sennheiser Communications            | 1         | 0.7%    |
| RODE Microphones                     | 1         | 0.7%    |
| Realtek Semiconductor                | 1         | 0.7%    |
| Native Instruments                   | 1         | 0.7%    |
| Generalplus Technology               | 1         | 0.7%    |
| Creative Labs                        | 1         | 0.7%    |
| Cirrus Logic                         | 1         | 0.7%    |
| Apple                                | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 4.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 2.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.69%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 2.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.61%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.08%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.08%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.08%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                                                     | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 17.04%  |
| Unknown             | 22        | 16.3%   |
| SK hynix            | 20        | 14.81%  |
| Crucial             | 14        | 10.37%  |
| Micron Technology   | 11        | 8.15%   |
| Kingston            | 10        | 7.41%   |
| Elpida              | 9         | 6.67%   |
| Corsair             | 5         | 3.7%    |
| A-DATA Technology   | 4         | 2.96%   |
| Nanya Technology    | 2         | 1.48%   |
| Visipro             | 1         | 0.74%   |
| Unknown (ABCD)      | 1         | 0.74%   |
| Transcend           | 1         | 0.74%   |
| Team                | 1         | 0.74%   |
| Ramaxel Technology  | 1         | 0.74%   |
| Qimonda             | 1         | 0.74%   |
| PNY                 | 1         | 0.74%   |
| Patriot             | 1         | 0.74%   |
| Novatech            | 1         | 0.74%   |
| Lexar               | 1         | 0.74%   |
| Hewlett-Packard     | 1         | 0.74%   |
| Gold Key            | 1         | 0.74%   |
| G.Skill             | 1         | 0.74%   |
| Cors                | 1         | 0.74%   |
| Unknown             | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 1.96%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.31%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 1.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.31%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 1.31%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 1.31%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.65%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.65%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.65%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 0.65%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.65%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 56        | 50%     |
| DDR4    | 28        | 25%     |
| SDRAM   | 7         | 6.25%   |
| LPDDR3  | 5         | 4.46%   |
| DDR2    | 4         | 3.57%   |
| DDR     | 4         | 3.57%   |
| LPDDR4  | 3         | 2.68%   |
| DRAM    | 2         | 1.79%   |
| DDR5    | 2         | 1.79%   |
| Unknown | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 54.05%  |
| DIMM         | 43        | 38.74%  |
| Row Of Chips | 6         | 5.41%   |
| Unknown      | 2         | 1.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 32.26%  |
| 4096  | 36        | 29.03%  |
| 2048  | 19        | 15.32%  |
| 1024  | 10        | 8.06%   |
| 512   | 6         | 4.84%   |
| 32768 | 5         | 4.03%   |
| 16384 | 5         | 4.03%   |
| 128   | 2         | 1.61%   |
| 256   | 1         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 27.34%  |
| Unknown | 12        | 9.38%   |
| 1333    | 11        | 8.59%   |
| 2667    | 10        | 7.81%   |
| 2400    | 9         | 7.03%   |
| 3200    | 7         | 5.47%   |
| 1334    | 7         | 5.47%   |
| 2133    | 5         | 3.91%   |
| 3600    | 4         | 3.13%   |
| 1867    | 3         | 2.34%   |
| 1067    | 3         | 2.34%   |
| 3800    | 2         | 1.56%   |
| 1866    | 2         | 1.56%   |
| 1066    | 2         | 1.56%   |
| 667     | 2         | 1.56%   |
| 8400    | 1         | 0.78%   |
| 5808    | 1         | 0.78%   |
| 4800    | 1         | 0.78%   |
| 4267    | 1         | 0.78%   |
| 4199    | 1         | 0.78%   |
| 3266    | 1         | 0.78%   |
| 3000    | 1         | 0.78%   |
| 2200    | 1         | 0.78%   |
| 1800    | 1         | 0.78%   |
| 1400    | 1         | 0.78%   |
| 1331    | 1         | 0.78%   |
| 1200    | 1         | 0.78%   |
| 800     | 1         | 0.78%   |
| 533     | 1         | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1020 | 1         | 50%     |
| HP Deskjet 3050A | 1         | 50%     |

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
| Chicony Electronics                    | 13        | 19.7%   |
| Realtek Semiconductor                  | 8         | 12.12%  |
| Microdia                               | 7         | 10.61%  |
| IMC Networks                           | 5         | 7.58%   |
| Bison Electronics                      | 5         | 7.58%   |
| Suyin                                  | 4         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.06%   |
| Quanta                                 | 3         | 4.55%   |
| Z-Star Microelectronics                | 2         | 3.03%   |
| Sunplus Innovation Technology          | 2         | 3.03%   |
| Apple                                  | 2         | 3.03%   |
| Trust                                  | 1         | 1.52%   |
| Syntek                                 | 1         | 1.52%   |
| Silicon Motion                         | 1         | 1.52%   |
| Samsung Electronics                    | 1         | 1.52%   |
| Ricoh                                  | 1         | 1.52%   |
| MacroSilicon                           | 1         | 1.52%   |
| Luxvisions Innotech Limited            | 1         | 1.52%   |
| Logitech                               | 1         | 1.52%   |
| Lite-On Technology                     | 1         | 1.52%   |
| Linux Foundation                       | 1         | 1.52%   |
| Lenovo                                 | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 5.97%   |
| Microdia Integrated_Webcam_HD                       | 3         | 4.48%   |
| IMC Networks Integrated Camera                      | 3         | 4.48%   |
| Chicony HD Webcam                                   | 3         | 4.48%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.99%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.99%   |
| Chicony Integrated Camera                           | 2         | 2.99%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 1.49%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 1.49%   |
| Trust QHD Webcam                                    | 1         | 1.49%   |
| Syntek EasyCamera                                   | 1         | 1.49%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.49%   |
| Suyin HP TrueVision HD                              | 1         | 1.49%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 1.49%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.49%   |
| Sunplus HP Universal Camera                         | 1         | 1.49%   |
| Sunplus HD WebCam                                   | 1         | 1.49%   |
| Silicon Motion NCM-G102                             | 1         | 1.49%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.49%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.49%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.49%   |
| Realtek USB Camera                                  | 1         | 1.49%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.49%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.49%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.49%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.49%   |
| Microdia Integrated Webcam                          | 1         | 1.49%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 1.49%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.49%   |
| Logitech Webcam C270                                | 1         | 1.49%   |
| Logitech Webcam C170                                | 1         | 1.49%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.49%   |
| Linux Foundation EEM Gadget                         | 1         | 1.49%   |
| Lenovo Integrated Webcam                            | 1         | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.49%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.49%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.49%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.49%   |
| Chicony HP HD Camera                                | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| AuthenTec                  | 2         | 22.22%  |
| STMicroelectronics         | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 62.33%  |
| 1     | 32        | 21.92%  |
| 2     | 15        | 10.27%  |
| 4     | 4         | 2.74%   |
| 3     | 3         | 2.05%   |
| 7     | 1         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 24        | 27.27%  |
| Communication controller | 12        | 13.64%  |
| Net/wireless             | 9         | 10.23%  |
| Fingerprint reader       | 8         | 9.09%   |
| Modem                    | 7         | 7.95%   |
| Bluetooth                | 5         | 5.68%   |
| Camera                   | 4         | 4.55%   |
| Network                  | 3         | 3.41%   |
| Multimedia controller    | 3         | 3.41%   |
| Unassigned class         | 2         | 2.27%   |
| Storage/ata              | 2         | 2.27%   |
| Sound                    | 2         | 2.27%   |
| Net/ethernet             | 2         | 2.27%   |
| Chipcard                 | 2         | 2.27%   |
| Unclassified device      | 1         | 1.14%   |
| Storage                  | 1         | 1.14%   |
| Card reader              | 1         | 1.14%   |


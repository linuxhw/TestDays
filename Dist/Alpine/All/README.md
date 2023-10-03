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

Total: 197

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 7.53%   |
| Alpine 3.18.0               | 10        | 6.85%   |
| Alpine 3.15.0               | 10        | 6.85%   |
| Alpine 3.16.0               | 9         | 6.16%   |
| Alpine 3.18.3               | 7         | 4.79%   |
| Alpine 3.15.4               | 7         | 4.79%   |
| Alpine 3.15.0_alpha20210804 | 7         | 4.79%   |
| Alpine 3.17_alpha20220809   | 5         | 3.42%   |
| Alpine 3.17.2               | 5         | 3.42%   |
| Alpine 3.14.0               | 5         | 3.42%   |
| Alpine 3.18.2               | 4         | 2.74%   |
| Alpine 3.17.1               | 4         | 2.74%   |
| Alpine 3.17.0               | 4         | 2.74%   |
| Alpine 3.16.1               | 4         | 2.74%   |
| Alpine 3.14.2               | 4         | 2.74%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.74%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.74%   |
| Alpine 3.11.2               | 4         | 2.74%   |
| Alpine 3.16.2               | 3         | 2.05%   |
| Alpine 3.13.1               | 3         | 2.05%   |
| Alpine 3.13.0_alpha20201218 | 3         | 2.05%   |
| Alpine 3.18_alpha20230329   | 2         | 1.37%   |
| Alpine 3.16.3               | 2         | 1.37%   |
| Alpine 3.15.6               | 2         | 1.37%   |
| Alpine 3.13.5               | 2         | 1.37%   |
| Alpine 3.13.2               | 2         | 1.37%   |
| Alpine 3.12.3               | 2         | 1.37%   |
| Alpine 3.8.4                | 1         | 0.68%   |
| Alpine 3.19_alpha20230901   | 1         | 0.68%   |
| Alpine 3.17.4               | 1         | 0.68%   |
| Alpine 3.17.3               | 1         | 0.68%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.68%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.68%   |
| Alpine 3.15.2               | 1         | 0.68%   |
| Alpine 3.15.0_rc5           | 1         | 0.68%   |
| Alpine 3.14.3               | 1         | 0.68%   |
| Alpine 3.14.0_alpha20210212 | 1         | 0.68%   |
| Alpine 3.13.6               | 1         | 0.68%   |
| Alpine 3.13.3               | 1         | 0.68%   |
| Alpine 3.13.0_rc2           | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 134       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 5.44%   |
| 6.1.32-0-lts           | 3         | 2.04%   |
| 5.15.86-0-lts          | 3         | 2.04%   |
| 5.15.60-0-lts          | 3         | 2.04%   |
| 5.15.16-0-lts          | 3         | 2.04%   |
| 5.10.61-0-lts          | 3         | 2.04%   |
| 6.1.51-0-lts           | 2         | 1.36%   |
| 6.1.28-2-lts           | 2         | 1.36%   |
| 5.4.84-0-lts           | 2         | 1.36%   |
| 5.4.83-0-lts           | 2         | 1.36%   |
| 5.17.9-0-edge          | 2         | 1.36%   |
| 5.15.74-0-lts          | 2         | 1.36%   |
| 5.15.59-0-lts          | 2         | 1.36%   |
| 5.15.47-0-lts          | 2         | 1.36%   |
| 5.15.46-1-lts          | 2         | 1.36%   |
| 5.15.41-0-lts          | 2         | 1.36%   |
| 5.15.4-0-lts           | 2         | 1.36%   |
| 5.15.12-0-lts          | 2         | 1.36%   |
| 5.10.68-0-lts          | 2         | 1.36%   |
| 5.10.16-0-lts          | 2         | 1.36%   |
| 6.4.4-0-edge           | 1         | 0.68%   |
| 6.3.3-0-edge           | 1         | 0.68%   |
| 6.1.54-0-lts           | 1         | 0.68%   |
| 6.1.53-0-lts           | 1         | 0.68%   |
| 6.1.52-0-lts           | 1         | 0.68%   |
| 6.1.46-0-lts           | 1         | 0.68%   |
| 6.1.42-0-lts           | 1         | 0.68%   |
| 6.1.39-0-lts           | 1         | 0.68%   |
| 6.1.36-0-lts           | 1         | 0.68%   |
| 6.1.34-0-lts           | 1         | 0.68%   |
| 6.1.34                 | 1         | 0.68%   |
| 6.1.30-0-lts           | 1         | 0.68%   |
| 6.1.24-0-lts           | 1         | 0.68%   |
| 6.1.11-0-edge          | 1         | 0.68%   |
| 6.0.10-0-edge          | 1         | 0.68%   |
| 5.8.12-0-edge          | 1         | 0.68%   |
| 5.8.0                  | 1         | 0.68%   |
| 5.7.4                  | 1         | 0.68%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 0.68%   |
| 5.4.99                 | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 5.44%   |
| 6.1.32  | 3         | 2.04%   |
| 5.15.86 | 3         | 2.04%   |
| 5.15.60 | 3         | 2.04%   |
| 5.15.16 | 3         | 2.04%   |
| 5.10.61 | 3         | 2.04%   |
| 6.1.51  | 2         | 1.36%   |
| 6.1.34  | 2         | 1.36%   |
| 6.1.28  | 2         | 1.36%   |
| 5.4.84  | 2         | 1.36%   |
| 5.4.83  | 2         | 1.36%   |
| 5.19.0  | 2         | 1.36%   |
| 5.17.9  | 2         | 1.36%   |
| 5.15.74 | 2         | 1.36%   |
| 5.15.59 | 2         | 1.36%   |
| 5.15.47 | 2         | 1.36%   |
| 5.15.46 | 2         | 1.36%   |
| 5.15.41 | 2         | 1.36%   |
| 5.15.4  | 2         | 1.36%   |
| 5.15.12 | 2         | 1.36%   |
| 5.15.0  | 2         | 1.36%   |
| 5.10.68 | 2         | 1.36%   |
| 5.10.16 | 2         | 1.36%   |
| 6.4.4   | 1         | 0.68%   |
| 6.3.3   | 1         | 0.68%   |
| 6.1.54  | 1         | 0.68%   |
| 6.1.53  | 1         | 0.68%   |
| 6.1.52  | 1         | 0.68%   |
| 6.1.46  | 1         | 0.68%   |
| 6.1.42  | 1         | 0.68%   |
| 6.1.39  | 1         | 0.68%   |
| 6.1.36  | 1         | 0.68%   |
| 6.1.30  | 1         | 0.68%   |
| 6.1.24  | 1         | 0.68%   |
| 6.1.11  | 1         | 0.68%   |
| 6.0.10  | 1         | 0.68%   |
| 5.8.12  | 1         | 0.68%   |
| 5.8.0   | 1         | 0.68%   |
| 5.7.4   | 1         | 0.68%   |
| 5.6.2   | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 50        | 35.21%  |
| 5.4     | 23        | 16.2%   |
| 5.10    | 23        | 16.2%   |
| 6.1     | 19        | 13.38%  |
| 5.17    | 4         | 2.82%   |
| 3.10    | 3         | 2.11%   |
| 5.8     | 2         | 1.41%   |
| 5.19    | 2         | 1.41%   |
| 5.14    | 2         | 1.41%   |
| 4.4     | 2         | 1.41%   |
| 3.18    | 2         | 1.41%   |
| 6.4     | 1         | 0.7%    |
| 6.3     | 1         | 0.7%    |
| 6.0     | 1         | 0.7%    |
| 5.7     | 1         | 0.7%    |
| 5.6     | 1         | 0.7%    |
| 5.18    | 1         | 0.7%    |
| 5.16    | 1         | 0.7%    |
| 5.13    | 1         | 0.7%    |
| 5.12    | 1         | 0.7%    |
| 4.14    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 111       | 82.84%  |
| i686    | 15        | 11.19%  |
| aarch64 | 4         | 2.99%   |
| armv7l  | 3         | 2.24%   |
| i586    | 1         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 107       | 79.85%  |
| XFCE    | 13        | 9.7%    |
| GNOME   | 6         | 4.48%   |
| KDE5    | 3         | 2.24%   |
| sway    | 2         | 1.49%   |
| LXQt    | 1         | 0.75%   |
| KDE     | 1         | 0.75%   |
| i3      | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 59.56%  |
| X11     | 45        | 33.09%  |
| Wayland | 9         | 6.62%   |
| Tty     | 1         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 80%     |
| LightDM | 18        | 13.33%  |
| SDDM    | 3         | 2.22%   |
| GDM     | 3         | 2.22%   |
| LXDM    | 2         | 1.48%   |
| XDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 85        | 61.59%  |
| Unknown | 41        | 29.71%  |
| en_US   | 7         | 5.07%   |
| ru_RU   | 3         | 2.17%   |
| pt_BR   | 1         | 0.72%   |
| en_GB   | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 90        | 66.18%  |
| EFI  | 46        | 33.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 78.83%  |
| Btrfs   | 9         | 6.57%   |
| Overlay | 8         | 5.84%   |
| Tmpfs   | 5         | 3.65%   |
| F2fs    | 2         | 1.46%   |
| Unknown | 2         | 1.46%   |
| Zfs     | 1         | 0.73%   |
| Rootfs  | 1         | 0.73%   |
| Ext2    | 1         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 87        | 62.14%  |
| GPT     | 37        | 26.43%  |
| MBR     | 16        | 11.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 86.67%  |
| Yes       | 18        | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 92.7%   |
| Yes       | 10        | 7.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 21        | 15.67%  |
| Hewlett-Packard         | 19        | 14.18%  |
| ASUSTek Computer        | 15        | 11.19%  |
| Lenovo                  | 14        | 10.45%  |
| Intel                   | 6         | 4.48%   |
| ASRock                  | 6         | 4.48%   |
| Unknown                 | 6         | 4.48%   |
| Gigabyte Technology     | 5         | 3.73%   |
| Acer                    | 5         | 3.73%   |
| Fujitsu                 | 4         | 2.99%   |
| Toshiba                 | 3         | 2.24%   |
| MSI                     | 3         | 2.24%   |
| IBM                     | 3         | 2.24%   |
| Google                  | 3         | 2.24%   |
| Raspberry Pi Foundation | 2         | 1.49%   |
| Gateway                 | 2         | 1.49%   |
| Apple                   | 2         | 1.49%   |
| VIA Technologies        | 1         | 0.75%   |
| UGREEN                  | 1         | 0.75%   |
| Synology                | 1         | 0.75%   |
| Supermicro              | 1         | 0.75%   |
| Sony                    | 1         | 0.75%   |
| Shuttle                 | 1         | 0.75%   |
| Pegatron                | 1         | 0.75%   |
| Olivetti                | 1         | 0.75%   |
| Notebook                | 1         | 0.75%   |
| LG Electronics          | 1         | 0.75%   |
| Haier                   | 1         | 0.75%   |
| Fanless Mini PC         | 1         | 0.75%   |
| F5 Networks             | 1         | 0.75%   |
| eMachines               | 1         | 0.75%   |
| AMI                     | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 4.48%   |
| Dell Dell Thin Client Desktop 3030 LT    | 3         | 2.24%   |
| HP ProLiant DL360 G6                     | 2         | 1.49%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.49%   |
| ASUS All Series                          | 2         | 1.49%   |
| VIA KM266APro-835                        | 1         | 0.75%   |
| UGREEN DX4600                            | 1         | 0.75%   |
| Toshiba WT8-A                            | 1         | 0.75%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.75%   |
| Toshiba Satellite M645                   | 1         | 0.75%   |
| Synology DS1019+                         | 1         | 0.75%   |
| Supermicro X10SLL-F                      | 1         | 0.75%   |
| Sony VGN-UX27GN                          | 1         | 0.75%   |
| Shuttle DS81D                            | 1         | 0.75%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.75%   |
| RPi Raspberry Pi                         | 1         | 0.75%   |
| Pegatron Deepcam                         | 1         | 0.75%   |
| Olivetti Spring Peak                     | 1         | 0.75%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.75%   |
| MSI MS-7C82                              | 1         | 0.75%   |
| MSI MS-7877                              | 1         | 0.75%   |
| MSI GL72M 7REX                           | 1         | 0.75%   |
| LG LW25-B7HG                             | 1         | 0.75%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.75%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.75%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.75%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.75%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.75%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.75%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.75%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.75%   |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.75%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.75%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 1         | 0.75%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.75%   |
| Lenovo H535 10117                        | 1         | 0.75%   |
| Intel NUC6i7KYB H90766-406               | 1         | 0.75%   |
| Intel Merrifield                         | 1         | 0.75%   |
| Intel ECO 44 G7                          | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 8         | 5.97%   |
| Lenovo ThinkPad     | 7         | 5.22%   |
| Unknown             | 6         | 4.48%   |
| Dell OptiPlex       | 5         | 3.73%   |
| Acer Aspire         | 5         | 3.73%   |
| HP ProLiant         | 3         | 2.24%   |
| HP EliteBook        | 3         | 2.24%   |
| Dell Dell           | 3         | 2.24%   |
| Toshiba Satellite   | 2         | 1.49%   |
| RPi Raspberry       | 2         | 1.49%   |
| Lenovo ThinkCentre  | 2         | 1.49%   |
| HP Presario         | 2         | 1.49%   |
| HP Compaq           | 2         | 1.49%   |
| Gigabyte Z490I      | 2         | 1.49%   |
| Dell XPS            | 2         | 1.49%   |
| ASUS PRIME          | 2         | 1.49%   |
| ASUS All            | 2         | 1.49%   |
| VIA KM266APro-835   | 1         | 0.75%   |
| UGREEN DX4600       | 1         | 0.75%   |
| Toshiba WT8-A       | 1         | 0.75%   |
| Synology DS1019+    | 1         | 0.75%   |
| Supermicro X10SLL-F | 1         | 0.75%   |
| Sony VGN-UX27GN     | 1         | 0.75%   |
| Shuttle DS81D       | 1         | 0.75%   |
| Pegatron Deepcam    | 1         | 0.75%   |
| Olivetti Spring     | 1         | 0.75%   |
| Notebook NV4XMB     | 1         | 0.75%   |
| MSI MS-7C82         | 1         | 0.75%   |
| MSI MS-7877         | 1         | 0.75%   |
| MSI GL72M           | 1         | 0.75%   |
| LG LW25-B7HG        | 1         | 0.75%   |
| Lenovo Yoga         | 1         | 0.75%   |
| Lenovo V14-ADA      | 1         | 0.75%   |
| Lenovo ThinkBook    | 1         | 0.75%   |
| Lenovo IdeaPad      | 1         | 0.75%   |
| Lenovo H535         | 1         | 0.75%   |
| Intel NUC6i7KYB     | 1         | 0.75%   |
| Intel Merrifield    | 1         | 0.75%   |
| Intel ECO           | 1         | 0.75%   |
| Intel DQ67SW        | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 16        | 11.94%  |
| 2018    | 12        | 8.96%   |
| 2012    | 10        | 7.46%   |
| 2010    | 9         | 6.72%   |
| 2020    | 8         | 5.97%   |
| 2019    | 8         | 5.97%   |
| 2016    | 8         | 5.97%   |
| 2013    | 8         | 5.97%   |
| Unknown | 8         | 5.97%   |
| 2017    | 7         | 5.22%   |
| 2015    | 6         | 4.48%   |
| 2011    | 6         | 4.48%   |
| 2006    | 6         | 4.48%   |
| 2021    | 5         | 3.73%   |
| 2009    | 5         | 3.73%   |
| 2022    | 3         | 2.24%   |
| 2007    | 3         | 2.24%   |
| 2005    | 2         | 1.49%   |
| 2023    | 1         | 0.75%   |
| 2008    | 1         | 0.75%   |
| 2004    | 1         | 0.75%   |
| 1999    | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 67        | 50%     |
| Desktop        | 44        | 32.84%  |
| Mini pc        | 10        | 7.46%   |
| Server         | 5         | 3.73%   |
| System on chip | 4         | 2.99%   |
| Tablet         | 2         | 1.49%   |
| Convertible    | 1         | 0.75%   |
| All in one     | 1         | 0.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 134       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 97.76%  |
| Yes  | 3         | 2.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 28        | 20%     |
| 3.01-4.0        | 26        | 18.57%  |
| 16.01-24.0      | 22        | 15.71%  |
| 8.01-16.0       | 16        | 11.43%  |
| 1.01-2.0        | 13        | 9.29%   |
| 0.51-1.0        | 11        | 7.86%   |
| 32.01-64.0      | 10        | 7.14%   |
| 2.01-3.0        | 5         | 3.57%   |
| 64.01-256.0     | 4         | 2.86%   |
| 0.01-0.5        | 4         | 2.86%   |
| More than 256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 43        | 30.07%  |
| 1.01-2.0  | 29        | 20.28%  |
| 0.51-1.0  | 27        | 18.88%  |
| 2.01-3.0  | 15        | 10.49%  |
| 3.01-4.0  | 11        | 7.69%   |
| 4.01-8.0  | 7         | 4.9%    |
| 8.01-16.0 | 5         | 3.5%    |
| 0         | 3         | 2.1%    |
| Unknown   | 3         | 2.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 63.04%  |
| 2      | 28        | 20.29%  |
| 3      | 8         | 5.8%    |
| 4      | 6         | 4.35%   |
| 14     | 2         | 1.45%   |
| 5      | 2         | 1.45%   |
| 0      | 2         | 1.45%   |
| 12     | 1         | 0.72%   |
| 10     | 1         | 0.72%   |
| 7      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 80.15%  |
| Yes       | 27        | 19.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 85.07%  |
| No        | 20        | 14.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 58.82%  |
| No        | 56        | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 58.09%  |
| Yes       | 57        | 41.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 33        | 23.91%  |
| Germany      | 15        | 10.87%  |
| Canada       | 13        | 9.42%   |
| Russia       | 12        | 8.7%    |
| UK           | 9         | 6.52%   |
| Spain        | 5         | 3.62%   |
| Brazil       | 5         | 3.62%   |
| Sweden       | 4         | 2.9%    |
| Australia    | 4         | 2.9%    |
| China        | 3         | 2.17%   |
| Portugal     | 2         | 1.45%   |
| Poland       | 2         | 1.45%   |
| Norway       | 2         | 1.45%   |
| Netherlands  | 2         | 1.45%   |
| Mexico       | 2         | 1.45%   |
| Italy        | 2         | 1.45%   |
| Guatemala    | 2         | 1.45%   |
| Venezuela    | 1         | 0.72%   |
| Ukraine      | 1         | 0.72%   |
| UAE          | 1         | 0.72%   |
| Switzerland  | 1         | 0.72%   |
| South Korea  | 1         | 0.72%   |
| South Africa | 1         | 0.72%   |
| Slovakia     | 1         | 0.72%   |
| Pakistan     | 1         | 0.72%   |
| Kenya        | 1         | 0.72%   |
| Jamaica      | 1         | 0.72%   |
| Israel       | 1         | 0.72%   |
| Indonesia    | 1         | 0.72%   |
| Hungary      | 1         | 0.72%   |
| Greece       | 1         | 0.72%   |
| France       | 1         | 0.72%   |
| Finland      | 1         | 0.72%   |
| Egypt        | 1         | 0.72%   |
| Denmark      | 1         | 0.72%   |
| Czechia      | 1         | 0.72%   |
| Austria      | 1         | 0.72%   |
| Argentina    | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 4.96%   |
| St Petersburg     | 6         | 4.26%   |
| Manitowoc         | 5         | 3.55%   |
| Vernon            | 4         | 2.84%   |
| Moscow            | 3         | 2.13%   |
| Sydney            | 2         | 1.42%   |
| Stratford         | 2         | 1.42%   |
| Siegsdorf         | 2         | 1.42%   |
| Guatemala City    | 2         | 1.42%   |
| Gothenburg        | 2         | 1.42%   |
| Fulham            | 2         | 1.42%   |
| Frankfurt am Main | 2         | 1.42%   |
| As                | 2         | 1.42%   |
| Zurich            | 1         | 0.71%   |
| Zhangzhou         | 1         | 0.71%   |
| Yakima            | 1         | 0.71%   |
| Vejle             | 1         | 0.71%   |
| Vancouver         | 1         | 0.71%   |
| Tymovskoye        | 1         | 0.71%   |
| Tuusula           | 1         | 0.71%   |
| Turin             | 1         | 0.71%   |
| Traunstein        | 1         | 0.71%   |
| Topeka            | 1         | 0.71%   |
| Thornhill         | 1         | 0.71%   |
| Thame             | 1         | 0.71%   |
| Tampa             | 1         | 0.71%   |
| Stuttgart         | 1         | 0.71%   |
| Stockholm         | 1         | 0.71%   |
| Stewartstown      | 1         | 0.71%   |
| Somerset          | 1         | 0.71%   |
| Sisteron          | 1         | 0.71%   |
| Semily            | 1         | 0.71%   |
| Seattle           | 1         | 0.71%   |
| Sao Paulo         | 1         | 0.71%   |
| San Mateo         | 1         | 0.71%   |
| Salzburg          | 1         | 0.71%   |
| Saarbrücken      | 1         | 0.71%   |
| Rzeszów          | 1         | 0.71%   |
| Rostock           | 1         | 0.71%   |
| Redwood City      | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 26        | 38     | 13.47%  |
| WDC                         | 23        | 53     | 11.92%  |
| Unknown                     | 18        | 22     | 9.33%   |
| Seagate                     | 17        | 47     | 8.81%   |
| Toshiba                     | 15        | 17     | 7.77%   |
| Hitachi                     | 11        | 11     | 5.7%    |
| Kingston                    | 10        | 12     | 5.18%   |
| HGST                        | 9         | 9      | 4.66%   |
| Crucial                     | 9         | 17     | 4.66%   |
| Intel                       | 7         | 11     | 3.63%   |
| SK hynix                    | 6         | 8      | 3.11%   |
| Sandisk                     | 6         | 8      | 3.11%   |
| A-DATA Technology           | 6         | 8      | 3.11%   |
| SPCC                        | 3         | 3      | 1.55%   |
| Transcend                   | 2         | 2      | 1.04%   |
| LITEON                      | 2         | 2      | 1.04%   |
| Fujitsu                     | 2         | 2      | 1.04%   |
| STEC                        | 1         | 1      | 0.52%   |
| SINTECHI                    | 1         | 1      | 0.52%   |
| Secure                      | 1         | 1      | 0.52%   |
| PNY                         | 1         | 1      | 0.52%   |
| Phison Electronics          | 1         | 1      | 0.52%   |
| NETAPP                      | 1         | 1      | 0.52%   |
| Micron Technology           | 1         | 1      | 0.52%   |
| Lexar                       | 1         | 1      | 0.52%   |
| KIOXIA                      | 1         | 1      | 0.52%   |
| Kingston Technology Company | 1         | 1      | 0.52%   |
| Kingmax                     | 1         | 1      | 0.52%   |
| KC600                       | 1         | 1      | 0.52%   |
| JMicron Technology          | 1         | 1      | 0.52%   |
| Intenso                     | 1         | 1      | 0.52%   |
| IBM                         | 1         | 1      | 0.52%   |
| Emtec                       | 1         | 1      | 0.52%   |
| Dell                        | 1         | 2      | 0.52%   |
| China                       | 1         | 1      | 0.52%   |
| Apple                       | 1         | 3      | 0.52%   |
| AMD                         | 1         | 1      | 0.52%   |
| Unknown                     | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                              | 5         | 2.25%   |
| Unknown MMC Card  4GB                               | 4         | 1.8%    |
| Unknown MMC Card  32GB                              | 3         | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 1.35%   |
| WDC WD3000BLFS-60YBU2 304GB                         | 2         | 0.9%    |
| Unknown MMC Card  64GB                              | 2         | 0.9%    |
| Unknown MMC Card                                    | 2         | 0.9%    |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.9%    |
| Toshiba MQ01ABD075 752GB                            | 2         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.9%    |
| Seagate ST4000VN008-2DR1 4TB                        | 2         | 0.9%    |
| Seagate ST380815AS 80GB                             | 2         | 0.9%    |
| Samsung SSD 960 EVO 500GB                           | 2         | 0.9%    |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.9%    |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.9%    |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.9%    |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.9%    |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.9%    |
| Crucial CT120BX500SSD1 120GB                        | 2         | 0.9%    |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.9%    |
| WDC WDS500G2X0C-00L350 500GB                        | 1         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.45%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.45%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.45%   |
| WDC WDS250G2B0B 250GB SSD                           | 1         | 0.45%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.45%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.45%   |
| WDC WD80EFAX-68LHPN0 8TB                            | 1         | 0.45%   |
| WDC WD800AAJS-00 80GB                               | 1         | 0.45%   |
| WDC WD7500BPKT-80PK4T0 752GB                        | 1         | 0.45%   |
| WDC WD5003ABYZ-0 500GB                              | 1         | 0.45%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 0.45%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1         | 0.45%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1         | 0.45%   |
| WDC WD3200AAKX-0 320GB                              | 1         | 0.45%   |
| WDC WD20EZRZ-00Z 2TB                                | 1         | 0.45%   |
| WDC WD1600JS-60NCB1 160GB                           | 1         | 0.45%   |
| WDC WD1600BEVT-2 160GB                              | 1         | 0.45%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 44     | 23.29%  |
| Seagate             | 17        | 47     | 23.29%  |
| Toshiba             | 12        | 13     | 16.44%  |
| Hitachi             | 11        | 11     | 15.07%  |
| HGST                | 9         | 9      | 12.33%  |
| Samsung Electronics | 3         | 5      | 4.11%   |
| Fujitsu             | 2         | 2      | 2.74%   |
| SINTECHI            | 1         | 1      | 1.37%   |
| IBM                 | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 15.15%  |
| Kingston            | 9         | 10     | 13.64%  |
| Crucial             | 9         | 17     | 13.64%  |
| Intel               | 5         | 7      | 7.58%   |
| WDC                 | 4         | 6      | 6.06%   |
| A-DATA Technology   | 4         | 4      | 6.06%   |
| SPCC                | 3         | 3      | 4.55%   |
| SanDisk             | 3         | 4      | 4.55%   |
| Transcend           | 2         | 2      | 3.03%   |
| SK hynix            | 2         | 3      | 3.03%   |
| LITEON              | 2         | 2      | 3.03%   |
| Toshiba             | 1         | 1      | 1.52%   |
| Secure              | 1         | 1      | 1.52%   |
| PNY                 | 1         | 1      | 1.52%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| Lexar               | 1         | 1      | 1.52%   |
| Kingmax             | 1         | 1      | 1.52%   |
| KC600               | 1         | 1      | 1.52%   |
| JMicron Technology  | 1         | 1      | 1.52%   |
| Intenso             | 1         | 1      | 1.52%   |
| Emtec               | 1         | 1      | 1.52%   |
| Dell                | 1         | 2      | 1.52%   |
| China               | 1         | 1      | 1.52%   |
| AMD                 | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 133    | 38.32%  |
| SSD     | 54        | 84     | 32.34%  |
| NVMe    | 30        | 52     | 17.96%  |
| MMC     | 18        | 23     | 10.78%  |
| Unknown | 1         | 2      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 212    | 64.67%  |
| NVMe | 30        | 52     | 20%     |
| MMC  | 18        | 23     | 12%     |
| SAS  | 5         | 7      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 129    | 65.29%  |
| 0.51-1.0   | 24        | 31     | 19.83%  |
| 3.01-4.0   | 5         | 16     | 4.13%   |
| 4.01-10.0  | 5         | 21     | 4.13%   |
| 10.01-20.0 | 3         | 13     | 2.48%   |
| 1.01-2.0   | 3         | 5      | 2.48%   |
| 2.01-3.0   | 2         | 2      | 1.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 20.86%  |
| Unknown        | 25        | 17.99%  |
| 1-20           | 24        | 17.27%  |
| 251-500        | 12        | 8.63%   |
| 501-1000       | 12        | 8.63%   |
| 21-50          | 11        | 7.91%   |
| 1001-2000      | 8         | 5.76%   |
| More than 3000 | 7         | 5.04%   |
| 51-100         | 7         | 5.04%   |
| 2001-3000      | 4         | 2.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 77        | 55.8%   |
| Unknown        | 25        | 18.12%  |
| 21-50          | 9         | 6.52%   |
| 251-500        | 8         | 5.8%    |
| 51-100         | 8         | 5.8%    |
| 501-1000       | 4         | 2.9%    |
| 101-250        | 3         | 2.17%   |
| 1001-2000      | 2         | 1.45%   |
| More than 3000 | 1         | 0.72%   |
| 2001-3000      | 1         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 84        | 183    | 56.38%  |
| Detected | 45        | 75     | 30.2%   |
| Malfunc  | 20        | 36     | 13.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 89        | 57.05%  |
| Samsung Electronics          | 16        | 10.26%  |
| AMD                          | 16        | 10.26%  |
| SanDisk                      | 5         | 3.21%   |
| LSI Logic / Symbios Logic    | 4         | 2.56%   |
| SK hynix                     | 3         | 1.92%   |
| Marvell Technology Group     | 3         | 1.92%   |
| ADATA Technology             | 3         | 1.92%   |
| Nvidia                       | 2         | 1.28%   |
| KIOXIA                       | 2         | 1.28%   |
| Hewlett-Packard              | 2         | 1.28%   |
| ASMedia Technology           | 2         | 1.28%   |
| Adaptec                      | 2         | 1.28%   |
| VIA Technologies             | 1         | 0.64%   |
| Toshiba America Info Systems | 1         | 0.64%   |
| Promise Technology           | 1         | 0.64%   |
| Phison Electronics           | 1         | 0.64%   |
| Micron/Crucial Technology    | 1         | 0.64%   |
| Kingston Technology Company  | 1         | 0.64%   |
| Broadcom / LSI               | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 7.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 5.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 5.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 3.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 2.73%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 2.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.64%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.64%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.09%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.09%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.09%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2         | 1.09%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.55%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.55%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 83        | 54.97%  |
| NVMe | 29        | 19.21%  |
| IDE  | 22        | 14.57%  |
| RAID | 13        | 8.61%   |
| SAS  | 4         | 2.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 109       | 80.15%  |
| AMD     | 20        | 14.71%  |
| ARM     | 6         | 4.41%   |
| Unknown | 1         | 0.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Celeron CPU N2807 @ 1.58GHz      | 3         | 2.17%   |
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 1.45%   |
| Intel Pentium M processor 1.70GHz      | 2         | 1.45%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 1.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 1.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 1.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 1.45%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 1.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 1.45%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 1.45%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 1.45%   |
| ARM Processor                          | 2         | 1.45%   |
| AMD FX-8350 Eight-Core Processor       | 2         | 1.45%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 0.72%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 0.72%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 0.72%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 0.72%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 0.72%   |
| Intel Pentium M processor 1.60GHz      | 1         | 0.72%   |
| Intel Pentium M processor 1.50GHz      | 1         | 0.72%   |
| Intel Pentium III (Coppermine)         | 1         | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 0.72%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1         | 0.72%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 0.72%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 0.72%   |
| Intel Mobile Pentium MMX               | 1         | 0.72%   |
| Intel Genuine CPU T2400 @ 1.83GHz      | 1         | 0.72%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 0.72%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 0.72%   |
| Intel Core m3-8100Y CPU @ 1.10GHz      | 1         | 0.72%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 0.72%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1         | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 0.72%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.72%   |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 29        | 21.01%  |
| Intel Celeron        | 16        | 11.59%  |
| Other                | 12        | 8.7%    |
| Intel Core i7        | 12        | 8.7%    |
| Intel Core i3        | 10        | 7.25%   |
| Intel Atom           | 9         | 6.52%   |
| Intel Xeon           | 6         | 4.35%   |
| Intel Pentium M      | 4         | 2.9%    |
| Intel Pentium        | 3         | 2.17%   |
| Intel Core i9        | 3         | 2.17%   |
| Intel Core 2 Duo     | 3         | 2.17%   |
| AMD Ryzen 7          | 3         | 2.17%   |
| Intel Genuine        | 2         | 1.45%   |
| Intel Core 2         | 2         | 1.45%   |
| AMD Ryzen 5          | 2         | 1.45%   |
| AMD FX               | 2         | 1.45%   |
| AMD A4               | 2         | 1.45%   |
| Intel Xeon Gold      | 1         | 0.72%   |
| Intel Pentium III    | 1         | 0.72%   |
| Intel Pentium Dual   | 1         | 0.72%   |
| Intel Core Solo      | 1         | 0.72%   |
| Intel Core m3        | 1         | 0.72%   |
| Intel Celeron M      | 1         | 0.72%   |
| ARM BCM              | 1         | 0.72%   |
| ARM ARMv7            | 1         | 0.72%   |
| ARM AArch64          | 1         | 0.72%   |
| AMD Turion 64 Mobile | 1         | 0.72%   |
| AMD Sempron          | 1         | 0.72%   |
| AMD Ryzen 9          | 1         | 0.72%   |
| AMD Ryzen 3          | 1         | 0.72%   |
| AMD E2               | 1         | 0.72%   |
| AMD E1               | 1         | 0.72%   |
| AMD A8               | 1         | 0.72%   |
| AMD A6               | 1         | 0.72%   |
| AMD A10              | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 55        | 40.15%  |
| 4       | 43        | 31.39%  |
| 1       | 15        | 10.95%  |
| 8       | 6         | 4.38%   |
| 12      | 4         | 2.92%   |
| 6       | 4         | 2.92%   |
| Unknown | 4         | 2.92%   |
| 10      | 2         | 1.46%   |
| 32      | 1         | 0.73%   |
| 16      | 1         | 0.73%   |
| 14      | 1         | 0.73%   |
| 3       | 1         | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 126       | 93.33%  |
| 2       | 4         | 2.96%   |
| Unknown | 4         | 2.96%   |
| 0       | 1         | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 69        | 51.49%  |
| 2       | 61        | 45.52%  |
| Unknown | 4         | 2.99%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 72        | 52.55%  |
| 32-bit, 64-bit | 59        | 43.07%  |
| 32-bit         | 5         | 3.65%   |
| 64-bit         | 1         | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 58.45%  |
| 0x306c3    | 7         | 4.93%   |
| 0x306a9    | 5         | 3.52%   |
| 0x906ea    | 4         | 2.82%   |
| 0x30678    | 4         | 2.82%   |
| 0x206c2    | 3         | 2.11%   |
| 0x806eb    | 2         | 1.41%   |
| 0x506c9    | 2         | 1.41%   |
| 0x406c4    | 2         | 1.41%   |
| 0x206a7    | 2         | 1.41%   |
| 0x20655    | 2         | 1.41%   |
| 0x106e5    | 2         | 1.41%   |
| 0x106ca    | 2         | 1.41%   |
| 0x06006704 | 2         | 1.41%   |
| 0xa0655    | 1         | 0.7%    |
| 0x906a3    | 1         | 0.7%    |
| 0x90672    | 1         | 0.7%    |
| 0x806ec    | 1         | 0.7%    |
| 0x806c1    | 1         | 0.7%    |
| 0x706e5    | 1         | 0.7%    |
| 0x6fd      | 1         | 0.7%    |
| 0x6f2      | 1         | 0.7%    |
| 0x6d8      | 1         | 0.7%    |
| 0x683      | 1         | 0.7%    |
| 0x506e3    | 1         | 0.7%    |
| 0x306d4    | 1         | 0.7%    |
| 0x1067a    | 1         | 0.7%    |
| 0x08701021 | 1         | 0.7%    |
| 0x08108109 | 1         | 0.7%    |
| 0x08108102 | 1         | 0.7%    |
| 0x0810100b | 1         | 0.7%    |
| 0x0800820d | 1         | 0.7%    |
| 0x06000817 | 1         | 0.7%    |
| 0x010000b6 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 10.87%  |
| Silvermont       | 14        | 10.14%  |
| Haswell          | 11        | 7.97%   |
| Unknown          | 11        | 7.97%   |
| P6               | 8         | 5.8%    |
| Westmere         | 7         | 5.07%   |
| SandyBridge      | 7         | 5.07%   |
| IvyBridge        | 7         | 5.07%   |
| Skylake          | 6         | 4.35%   |
| Goldmont         | 5         | 3.62%   |
| Penryn           | 4         | 2.9%    |
| Broadwell        | 4         | 2.9%    |
| Bonnell          | 4         | 2.9%    |
| Zen+             | 3         | 2.17%   |
| Piledriver       | 3         | 2.17%   |
| Excavator        | 3         | 2.17%   |
| Core             | 3         | 2.17%   |
| CometLake        | 3         | 2.17%   |
| Zen 2            | 2         | 1.45%   |
| TigerLake        | 2         | 1.45%   |
| Nehalem          | 2         | 1.45%   |
| Jaguar           | 2         | 1.45%   |
| IceLake          | 2         | 1.45%   |
| Alderlake Hybrid | 2         | 1.45%   |
| Zen 3            | 1         | 0.72%   |
| Zen              | 1         | 0.72%   |
| Puma             | 1         | 0.72%   |
| K8 Hammer        | 1         | 0.72%   |
| K6               | 1         | 0.72%   |
| K10              | 1         | 0.72%   |
| Goldmont plus    | 1         | 0.72%   |
| Bobcat           | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 93        | 65.49%  |
| AMD                        | 29        | 20.42%  |
| Nvidia                     | 12        | 8.45%   |
| Matrox Electronics Systems | 4         | 2.82%   |
| Neomagic                   | 2         | 1.41%   |
| VIA Technologies           | 1         | 0.7%    |
| ASPEED Technology          | 1         | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 6.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 3.16%   |
| Intel HD Graphics 500                                                                    | 4         | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.9%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.9%    |
| Intel HD Graphics 5500                                                                   | 3         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.9%    |
| AMD ES1000                                                                               | 3         | 1.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.27%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.27%   |
| Intel HD Graphics 630                                                                    | 2         | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.27%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.27%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.27%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.63%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.63%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.63%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 76        | 55.07%  |
| 1 x AMD         | 24        | 17.39%  |
| Other           | 8         | 5.8%    |
| 2 x Intel       | 7         | 5.07%   |
| Intel + Nvidia  | 6         | 4.35%   |
| 1 x Nvidia      | 4         | 2.9%    |
| 1 x Matrox      | 3         | 2.17%   |
| Intel + AMD     | 3         | 2.17%   |
| 1 x Neomagic    | 2         | 1.45%   |
| 2 x AMD         | 1         | 0.72%   |
| 1 x VIA         | 1         | 0.72%   |
| Nvidia + Matrox | 1         | 0.72%   |
| 1 x ASPEED      | 1         | 0.72%   |
| AMD + Nvidia    | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 113       | 81.88%  |
| Unknown     | 22        | 15.94%  |
| Proprietary | 3         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 85.93%  |
| 0.01-0.5   | 8         | 5.93%   |
| 7.01-8.0   | 3         | 2.22%   |
| 1.01-2.0   | 3         | 2.22%   |
| 0.51-1.0   | 2         | 1.48%   |
| 3.01-4.0   | 1         | 0.74%   |
| 2.01-3.0   | 1         | 0.74%   |
| 8.01-16.0  | 1         | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 12.5%   |
| LG Display              | 10        | 8.93%   |
| Dell                    | 9         | 8.04%   |
| Samsung Electronics     | 8         | 7.14%   |
| BOE                     | 8         | 7.14%   |
| Chimei Innolux          | 7         | 6.25%   |
| Goldstar                | 6         | 5.36%   |
| BenQ                    | 5         | 4.46%   |
| AOC                     | 4         | 3.57%   |
| LG Philips              | 3         | 2.68%   |
| InfoVision              | 3         | 2.68%   |
| Hewlett-Packard         | 3         | 2.68%   |
| Chi Mei Optoelectronics | 3         | 2.68%   |
| Acer                    | 3         | 2.68%   |
| Sharp                   | 2         | 1.79%   |
| Philips                 | 2         | 1.79%   |
| Lenovo                  | 2         | 1.79%   |
| Jean                    | 2         | 1.79%   |
| ViewSonic               | 1         | 0.89%   |
| Sony                    | 1         | 0.89%   |
| SKY                     | 1         | 0.89%   |
| Quanta Display          | 1         | 0.89%   |
| PANDA                   | 1         | 0.89%   |
| ONN                     | 1         | 0.89%   |
| Mi                      | 1         | 0.89%   |
| KVM                     | 1         | 0.89%   |
| HannStar                | 1         | 0.89%   |
| Envision                | 1         | 0.89%   |
| Elo Touch               | 1         | 0.89%   |
| Element                 | 1         | 0.89%   |
| EDI                     | 1         | 0.89%   |
| DENON                   | 1         | 0.89%   |
| CTC                     | 1         | 0.89%   |
| CSO                     | 1         | 0.89%   |
| CPT                     | 1         | 0.89%   |
| Apple                   | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 2.52%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2         | 1.68%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.68%   |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.68%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.84%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.84%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.84%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.84%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1         | 0.84%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch    | 1         | 0.84%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.84%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.84%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.84%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.84%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.84%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 1         | 0.84%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1         | 0.84%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.84%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.84%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.84%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.84%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 0.84%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch          | 1         | 0.84%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 0.84%   |
| InfoVision LCD Monitor IVO0489 1366x768 344x193mm 15.5-inch           | 1         | 0.84%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 530x300mm 24.0-inch          | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 27.27%  |
| 1366x768 (WXGA)    | 26        | 23.64%  |
| 3840x2160 (4K)     | 6         | 5.45%   |
| 1680x1050 (WSXGA+) | 6         | 5.45%   |
| 1280x800 (WXGA)    | 6         | 5.45%   |
| 2560x1440 (QHD)    | 5         | 4.55%   |
| 1280x1024 (SXGA)   | 5         | 4.55%   |
| 1920x1200 (WUXGA)  | 4         | 3.64%   |
| 3440x1440          | 3         | 2.73%   |
| 1600x900 (HD+)     | 3         | 2.73%   |
| 1024x768 (XGA)     | 3         | 2.73%   |
| 1024x600           | 3         | 2.73%   |
| 2560x1080          | 2         | 1.82%   |
| 1440x900 (WXGA+)   | 2         | 1.82%   |
| 1280x768           | 2         | 1.82%   |
| 2880x1800          | 1         | 0.91%   |
| 2560x1700          | 1         | 0.91%   |
| 1360x768           | 1         | 0.91%   |
| 1280x960           | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 25        | 22.12%  |
| 14     | 12        | 10.62%  |
| 13     | 9         | 7.96%   |
| 17     | 8         | 7.08%   |
| 27     | 7         | 6.19%   |
| 24     | 6         | 5.31%   |
| 23     | 6         | 5.31%   |
| 20     | 5         | 4.42%   |
| 11     | 5         | 4.42%   |
| 21     | 4         | 3.54%   |
| 12     | 4         | 3.54%   |
| 34     | 3         | 2.65%   |
| 19     | 3         | 2.65%   |
| 10     | 3         | 2.65%   |
| 31     | 2         | 1.77%   |
| 22     | 2         | 1.77%   |
| 72     | 1         | 0.88%   |
| 65     | 1         | 0.88%   |
| 60     | 1         | 0.88%   |
| 40     | 1         | 0.88%   |
| 32     | 1         | 0.88%   |
| 29     | 1         | 0.88%   |
| 25     | 1         | 0.88%   |
| 18     | 1         | 0.88%   |
| 16     | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 42.59%  |
| 501-600     | 17        | 15.74%  |
| 201-300     | 15        | 13.89%  |
| 401-500     | 12        | 11.11%  |
| 351-400     | 6         | 5.56%   |
| 701-800     | 4         | 3.7%    |
| 601-700     | 4         | 3.7%    |
| 1001-1500   | 2         | 1.85%   |
| 801-900     | 1         | 0.93%   |
| 1501-2000   | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 67        | 66.34%  |
| 16/10 | 20        | 19.8%   |
| 5/4   | 6         | 5.94%   |
| 21/9  | 4         | 3.96%   |
| 4/3   | 3         | 2.97%   |
| 3/2   | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 22.02%  |
| 81-90          | 18        | 16.51%  |
| 201-250        | 14        | 12.84%  |
| 151-200        | 9         | 8.26%   |
| 301-350        | 8         | 7.34%   |
| 351-500        | 6         | 5.5%    |
| 51-60          | 5         | 4.59%   |
| 71-80          | 4         | 3.67%   |
| 141-150        | 4         | 3.67%   |
| More than 1000 | 3         | 2.75%   |
| 61-70          | 3         | 2.75%   |
| 41-50          | 3         | 2.75%   |
| 251-300        | 2         | 1.83%   |
| 131-140        | 2         | 1.83%   |
| 121-130        | 2         | 1.83%   |
| 111-120        | 1         | 0.92%   |
| 501-1000       | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 36        | 35.29%  |
| 101-120       | 30        | 29.41%  |
| 121-160       | 24        | 23.53%  |
| 1-50          | 6         | 5.88%   |
| 161-240       | 4         | 3.92%   |
| More than 240 | 2         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 91        | 65.94%  |
| 0     | 36        | 26.09%  |
| 2     | 9         | 6.52%   |
| 4     | 1         | 0.72%   |
| 3     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 67        | 34.18%  |
| Intel                           | 62        | 31.63%  |
| Qualcomm Atheros                | 20        | 10.2%   |
| Broadcom                        | 19        | 9.69%   |
| Xiaomi                          | 3         | 1.53%   |
| Marvell Technology Group        | 3         | 1.53%   |
| Qualcomm Atheros Communications | 2         | 1.02%   |
| Qualcomm                        | 2         | 1.02%   |
| MediaTek                        | 2         | 1.02%   |
| LSI                             | 2         | 1.02%   |
| Broadcom Limited                | 2         | 1.02%   |
| VIA Technologies                | 1         | 0.51%   |
| T & A Mobile Phones             | 1         | 0.51%   |
| Sigma Designs                   | 1         | 0.51%   |
| Nvidia                          | 1         | 0.51%   |
| Microchip Technology            | 1         | 0.51%   |
| Mellanox Technologies           | 1         | 0.51%   |
| Google                          | 1         | 0.51%   |
| Dresden Elektronik              | 1         | 0.51%   |
| DisplayLink                     | 1         | 0.51%   |
| D-Link System                   | 1         | 0.51%   |
| ASIX Electronics                | 1         | 0.51%   |
| AMD                             | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 16.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.68%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.26%   |
| Intel Wireless 7265                                               | 3         | 1.26%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.84%   |
| Intel Wireless-AC 9260                                            | 2         | 0.84%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.84%   |
| Intel Wireless 8260                                               | 2         | 0.84%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.84%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.84%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.84%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.84%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 45.35%  |
| Qualcomm Atheros                | 17        | 19.77%  |
| Broadcom                        | 12        | 13.95%  |
| Realtek Semiconductor           | 11        | 12.79%  |
| Qualcomm Atheros Communications | 2         | 2.33%   |
| MediaTek                        | 2         | 2.33%   |
| Broadcom Limited                | 2         | 2.33%   |
| Marvell Technology Group        | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 9.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 3.45%   |
| Intel Wireless 7265                                                            | 3         | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.3%    |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.3%    |
| Intel Wireless-AC 9260                                                         | 2         | 2.3%    |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.3%    |
| Intel Wireless 8260                                                            | 2         | 2.3%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 2.3%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 2         | 2.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 2.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.15%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.15%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.15%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.15%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.15%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.15%   |
| Intel Wireless 7260                                                            | 1         | 1.15%   |
| Intel Wireless 3160                                                            | 1         | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 1.15%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 46.62%  |
| Intel                    | 40        | 30.08%  |
| Broadcom                 | 11        | 8.27%   |
| Qualcomm Atheros         | 4         | 3.01%   |
| Xiaomi                   | 3         | 2.26%   |
| Qualcomm                 | 2         | 1.5%    |
| Marvell Technology Group | 2         | 1.5%    |
| VIA Technologies         | 1         | 0.75%   |
| T & A Mobile Phones      | 1         | 0.75%   |
| Nvidia                   | 1         | 0.75%   |
| Microchip Technology     | 1         | 0.75%   |
| Mellanox Technologies    | 1         | 0.75%   |
| LSI                      | 1         | 0.75%   |
| DisplayLink              | 1         | 0.75%   |
| D-Link System            | 1         | 0.75%   |
| ASIX Electronics         | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 28.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 7.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 4.96%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 2.84%   |
| Intel I210 Gigabit Network Connection                             | 4         | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 2.13%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.42%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.42%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.71%   |
| T & A Mobile Phones Alcatel 3X                                    | 1         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.71%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.71%   |
| Qualcomm POCO M2 Pro                                              | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.71%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.71%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.71%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.71%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 0.71%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.71%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 113       | 55.67%  |
| WiFi     | 80        | 39.41%  |
| Modem    | 8         | 3.94%   |
| Unknown  | 2         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 61.6%   |
| WiFi     | 48        | 38.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 52.21%  |
| 1     | 47        | 34.56%  |
| 0     | 11        | 8.09%   |
| 4     | 3         | 2.21%   |
| 5     | 2         | 1.47%   |
| 3     | 2         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 82.96%  |
| Yes  | 23        | 17.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 39.68%  |
| IMC Networks                    | 5         | 7.94%   |
| Cambridge Silicon Radio         | 5         | 7.94%   |
| Broadcom                        | 5         | 7.94%   |
| Qualcomm Atheros Communications | 4         | 6.35%   |
| Realtek Semiconductor           | 3         | 4.76%   |
| Lite-On Technology              | 3         | 4.76%   |
| Apple                           | 3         | 4.76%   |
| Foxconn / Hon Hai               | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| MediaTek                        | 1         | 1.59%   |
| Marvell Semiconductor           | 1         | 1.59%   |
| Hewlett-Packard                 | 1         | 1.59%   |
| Edimax Technology               | 1         | 1.59%   |
| ASUSTek Computer                | 1         | 1.59%   |
| Alps Electric                   | 1         | 1.59%   |
| Actions                         | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 14.29%  |
| Intel AX201 Bluetooth                               | 5         | 7.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 7.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.76%   |
| Realtek Bluetooth Radio                             | 2         | 3.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.17%   |
| Intel AX200 Bluetooth                               | 2         | 3.17%   |
| IMC Networks Bluetooth Device                       | 2         | 3.17%   |
| Apple Bluetooth Host Controller                     | 2         | 3.17%   |
| Toshiba Bluetooth Device                            | 1         | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.59%   |
| MediaTek Wireless_Device                            | 1         | 1.59%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.59%   |
| Intel AX210 Bluetooth                               | 1         | 1.59%   |
| IMC Networks Wireless_Device                        | 1         | 1.59%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.59%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.59%   |
| Edimax Bluetooth Adapter                            | 1         | 1.59%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.59%   |
| Broadcom BCM20702A0                                 | 1         | 1.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.59%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.59%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.59%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.59%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.59%   |
| Actions general adapter                             | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 92        | 67.15%  |
| AMD                                  | 25        | 18.25%  |
| Nvidia                               | 6         | 4.38%   |
| Logitech                             | 2         | 1.46%   |
| C-Media Electronics                  | 2         | 1.46%   |
| VIA Technologies                     | 1         | 0.73%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.73%   |
| Texas Instruments                    | 1         | 0.73%   |
| Sennheiser Communications            | 1         | 0.73%   |
| RODE Microphones                     | 1         | 0.73%   |
| Realtek Semiconductor                | 1         | 0.73%   |
| Native Instruments                   | 1         | 0.73%   |
| Generalplus Technology               | 1         | 0.73%   |
| Cirrus Logic                         | 1         | 0.73%   |
| Apple                                | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 4.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.89%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 2.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.73%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 1.16%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.16%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.16%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.16%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.58%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                                                     | 1         | 0.58%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.58%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.58%   |
| RODE Microphones RODE NT-USB Mini                                                                 | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 22        | 17.19%  |
| Samsung Electronics | 22        | 17.19%  |
| SK hynix            | 20        | 15.63%  |
| Crucial             | 14        | 10.94%  |
| Micron Technology   | 11        | 8.59%   |
| Kingston            | 9         | 7.03%   |
| Elpida              | 9         | 7.03%   |
| Corsair             | 5         | 3.91%   |
| A-DATA Technology   | 3         | 2.34%   |
| Nanya Technology    | 2         | 1.56%   |
| Unknown (ABCD)      | 1         | 0.78%   |
| Transcend           | 1         | 0.78%   |
| Team                | 1         | 0.78%   |
| Ramaxel Technology  | 1         | 0.78%   |
| Qimonda             | 1         | 0.78%   |
| PNY                 | 1         | 0.78%   |
| Patriot             | 1         | 0.78%   |
| Hewlett-Packard     | 1         | 0.78%   |
| Gold Key            | 1         | 0.78%   |
| Cors                | 1         | 0.78%   |
| Unknown             | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 2.07%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.38%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 1.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.38%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 1.38%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 1.38%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.69%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.69%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 0.69%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.69%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.69%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 0.69%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 54        | 49.54%  |
| DDR4    | 28        | 25.69%  |
| SDRAM   | 7         | 6.42%   |
| LPDDR3  | 5         | 4.59%   |
| DDR2    | 4         | 3.67%   |
| DDR     | 4         | 3.67%   |
| LPDDR4  | 3         | 2.75%   |
| DRAM    | 2         | 1.83%   |
| DDR5    | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 54.63%  |
| DIMM         | 41        | 37.96%  |
| Row Of Chips | 6         | 5.56%   |
| Unknown      | 2         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 33.06%  |
| 4096  | 35        | 28.93%  |
| 2048  | 18        | 14.88%  |
| 1024  | 10        | 8.26%   |
| 512   | 6         | 4.96%   |
| 16384 | 5         | 4.13%   |
| 32768 | 4         | 3.31%   |
| 128   | 2         | 1.65%   |
| 256   | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 27.64%  |
| Unknown | 12        | 9.76%   |
| 1333    | 10        | 8.13%   |
| 2667    | 9         | 7.32%   |
| 2400    | 9         | 7.32%   |
| 3200    | 7         | 5.69%   |
| 1334    | 7         | 5.69%   |
| 2133    | 5         | 4.07%   |
| 3600    | 4         | 3.25%   |
| 1867    | 3         | 2.44%   |
| 1067    | 3         | 2.44%   |
| 1866    | 2         | 1.63%   |
| 1066    | 2         | 1.63%   |
| 667     | 2         | 1.63%   |
| 8400    | 1         | 0.81%   |
| 4800    | 1         | 0.81%   |
| 4267    | 1         | 0.81%   |
| 4199    | 1         | 0.81%   |
| 3800    | 1         | 0.81%   |
| 3266    | 1         | 0.81%   |
| 3000    | 1         | 0.81%   |
| 2200    | 1         | 0.81%   |
| 1800    | 1         | 0.81%   |
| 1400    | 1         | 0.81%   |
| 1331    | 1         | 0.81%   |
| 1200    | 1         | 0.81%   |
| 800     | 1         | 0.81%   |
| 533     | 1         | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 20.63%  |
| Realtek Semiconductor                  | 7         | 11.11%  |
| Microdia                               | 6         | 9.52%   |
| IMC Networks                           | 5         | 7.94%   |
| Suyin                                  | 4         | 6.35%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.35%   |
| Quanta                                 | 3         | 4.76%   |
| Bison Electronics                      | 3         | 4.76%   |
| Z-Star Microelectronics                | 2         | 3.17%   |
| Sunplus Innovation Technology          | 2         | 3.17%   |
| Apple                                  | 2         | 3.17%   |
| Trust                                  | 1         | 1.59%   |
| Syntek                                 | 1         | 1.59%   |
| Silicon Motion                         | 1         | 1.59%   |
| Samsung Electronics                    | 1         | 1.59%   |
| Ricoh                                  | 1         | 1.59%   |
| MacroSilicon                           | 1         | 1.59%   |
| Luxvisions Innotech Limited            | 1         | 1.59%   |
| Logitech                               | 1         | 1.59%   |
| Lite-On Technology                     | 1         | 1.59%   |
| Linux Foundation                       | 1         | 1.59%   |
| Lenovo                                 | 1         | 1.59%   |
| Acer                                   | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 3         | 4.69%   |
| IMC Networks Integrated Camera                      | 3         | 4.69%   |
| Chicony HD Webcam                                   | 3         | 4.69%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 3.13%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 3.13%   |
| Chicony Integrated Camera                           | 2         | 3.13%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 1.56%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 1.56%   |
| Trust QHD Webcam                                    | 1         | 1.56%   |
| Syntek EasyCamera                                   | 1         | 1.56%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.56%   |
| Suyin HP TrueVision HD                              | 1         | 1.56%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 1.56%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.56%   |
| Sunplus HP Universal Camera                         | 1         | 1.56%   |
| Sunplus HD WebCam                                   | 1         | 1.56%   |
| Silicon Motion NCM-G102                             | 1         | 1.56%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.56%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.56%   |
| Realtek USB Camera                                  | 1         | 1.56%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.56%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.56%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.56%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.56%   |
| Microdia Integrated Webcam                          | 1         | 1.56%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 1.56%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.56%   |
| Logitech Webcam C270                                | 1         | 1.56%   |
| Logitech Webcam C170                                | 1         | 1.56%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.56%   |
| Linux Foundation EEM Gadget                         | 1         | 1.56%   |
| Lenovo Integrated Webcam                            | 1         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.56%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.56%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.56%   |
| Chicony HP HD Camera                                | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 86        | 61.43%  |
| 1     | 32        | 22.86%  |
| 2     | 14        | 10%     |
| 4     | 4         | 2.86%   |
| 3     | 3         | 2.14%   |
| 7     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 24        | 27.59%  |
| Communication controller | 12        | 13.79%  |
| Net/wireless             | 8         | 9.2%    |
| Fingerprint reader       | 8         | 9.2%    |
| Modem                    | 7         | 8.05%   |
| Bluetooth                | 5         | 5.75%   |
| Camera                   | 4         | 4.6%    |
| Network                  | 3         | 3.45%   |
| Multimedia controller    | 3         | 3.45%   |
| Unassigned class         | 2         | 2.3%    |
| Storage/ata              | 2         | 2.3%    |
| Sound                    | 2         | 2.3%    |
| Net/ethernet             | 2         | 2.3%    |
| Chipcard                 | 2         | 2.3%    |
| Unclassified device      | 1         | 1.15%   |
| Storage                  | 1         | 1.15%   |
| Card reader              | 1         | 1.15%   |


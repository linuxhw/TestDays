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

Total: 178

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 03KWTV A02                  | Desktop     | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Dell          | 03KWTV A02                  | Desktop     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Dell          | 0J1C3P A00                  | Desktop     | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
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
| Dell          | 03KWTV A02                  | Desktop     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Dell          | 03KWTV A02                  | Desktop     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 11        | 8.09%   |
| Alpine 3.15.0               | 10        | 7.35%   |
| Alpine 3.18.0               | 9         | 6.62%   |
| Alpine 3.16.0               | 9         | 6.62%   |
| Alpine 3.15.0_alpha20210804 | 7         | 5.15%   |
| Alpine 3.15.4               | 6         | 4.41%   |
| Alpine 3.17_alpha20220809   | 5         | 3.68%   |
| Alpine 3.17.2               | 5         | 3.68%   |
| Alpine 3.14.0               | 5         | 3.68%   |
| Alpine 3.18.2               | 4         | 2.94%   |
| Alpine 3.17.1               | 4         | 2.94%   |
| Alpine 3.17.0               | 4         | 2.94%   |
| Alpine 3.16.1               | 4         | 2.94%   |
| Alpine 3.14.2               | 4         | 2.94%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.94%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.94%   |
| Alpine 3.11.2               | 4         | 2.94%   |
| Alpine 3.16.2               | 3         | 2.21%   |
| Alpine 3.13.1               | 3         | 2.21%   |
| Alpine 3.13.0_alpha20201218 | 3         | 2.21%   |
| Alpine 3.18_alpha20230329   | 2         | 1.47%   |
| Alpine 3.16.3               | 2         | 1.47%   |
| Alpine 3.15.6               | 2         | 1.47%   |
| Alpine 3.13.5               | 2         | 1.47%   |
| Alpine 3.13.2               | 2         | 1.47%   |
| Alpine 3.12.3               | 2         | 1.47%   |
| Alpine 3.8.4                | 1         | 0.74%   |
| Alpine 3.17.4               | 1         | 0.74%   |
| Alpine 3.17.3               | 1         | 0.74%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.74%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.74%   |
| Alpine 3.15.2               | 1         | 0.74%   |
| Alpine 3.15.0_rc5           | 1         | 0.74%   |
| Alpine 3.14.3               | 1         | 0.74%   |
| Alpine 3.14.0_alpha20210212 | 1         | 0.74%   |
| Alpine 3.13.6               | 1         | 0.74%   |
| Alpine 3.13.3               | 1         | 0.74%   |
| Alpine 3.13.0_rc2           | 1         | 0.74%   |
| Alpine 3.12.7               | 1         | 0.74%   |
| Alpine 3.12.1               | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 125       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 5.88%   |
| 5.15.86-0-lts          | 3         | 2.21%   |
| 5.15.60-0-lts          | 3         | 2.21%   |
| 5.15.16-0-lts          | 3         | 2.21%   |
| 5.10.61-0-lts          | 3         | 2.21%   |
| 6.1.32-0-lts           | 2         | 1.47%   |
| 6.1.28-2-lts           | 2         | 1.47%   |
| 5.4.84-0-lts           | 2         | 1.47%   |
| 5.4.83-0-lts           | 2         | 1.47%   |
| 5.17.9-0-edge          | 2         | 1.47%   |
| 5.15.74-0-lts          | 2         | 1.47%   |
| 5.15.59-0-lts          | 2         | 1.47%   |
| 5.15.47-0-lts          | 2         | 1.47%   |
| 5.15.46-1-lts          | 2         | 1.47%   |
| 5.15.41-0-lts          | 2         | 1.47%   |
| 5.15.4-0-lts           | 2         | 1.47%   |
| 5.15.12-0-lts          | 2         | 1.47%   |
| 5.10.68-0-lts          | 2         | 1.47%   |
| 5.10.16-0-lts          | 2         | 1.47%   |
| 6.4.4-0-edge           | 1         | 0.74%   |
| 6.3.3-0-edge           | 1         | 0.74%   |
| 6.1.42-0-lts           | 1         | 0.74%   |
| 6.1.39-0-lts           | 1         | 0.74%   |
| 6.1.36-0-lts           | 1         | 0.74%   |
| 6.1.34-0-lts           | 1         | 0.74%   |
| 6.1.34                 | 1         | 0.74%   |
| 6.1.30-0-lts           | 1         | 0.74%   |
| 6.1.24-0-lts           | 1         | 0.74%   |
| 6.1.11-0-edge          | 1         | 0.74%   |
| 6.0.10-0-edge          | 1         | 0.74%   |
| 5.8.12-0-edge          | 1         | 0.74%   |
| 5.8.0                  | 1         | 0.74%   |
| 5.7.4                  | 1         | 0.74%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 0.74%   |
| 5.4.99                 | 1         | 0.74%   |
| 5.4.73-0-lts           | 1         | 0.74%   |
| 5.4.72-0-lts           | 1         | 0.74%   |
| 5.4.65-0-lts           | 1         | 0.74%   |
| 5.4.64-0-lts           | 1         | 0.74%   |
| 5.4.6-0-lts            | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 5.88%   |
| 5.15.86 | 3         | 2.21%   |
| 5.15.60 | 3         | 2.21%   |
| 5.15.16 | 3         | 2.21%   |
| 5.10.61 | 3         | 2.21%   |
| 6.1.34  | 2         | 1.47%   |
| 6.1.32  | 2         | 1.47%   |
| 6.1.28  | 2         | 1.47%   |
| 5.4.84  | 2         | 1.47%   |
| 5.4.83  | 2         | 1.47%   |
| 5.19.0  | 2         | 1.47%   |
| 5.17.9  | 2         | 1.47%   |
| 5.15.74 | 2         | 1.47%   |
| 5.15.59 | 2         | 1.47%   |
| 5.15.47 | 2         | 1.47%   |
| 5.15.46 | 2         | 1.47%   |
| 5.15.41 | 2         | 1.47%   |
| 5.15.4  | 2         | 1.47%   |
| 5.15.12 | 2         | 1.47%   |
| 5.10.68 | 2         | 1.47%   |
| 5.10.16 | 2         | 1.47%   |
| 6.4.4   | 1         | 0.74%   |
| 6.3.3   | 1         | 0.74%   |
| 6.1.42  | 1         | 0.74%   |
| 6.1.39  | 1         | 0.74%   |
| 6.1.36  | 1         | 0.74%   |
| 6.1.30  | 1         | 0.74%   |
| 6.1.24  | 1         | 0.74%   |
| 6.1.11  | 1         | 0.74%   |
| 6.0.10  | 1         | 0.74%   |
| 5.8.12  | 1         | 0.74%   |
| 5.8.0   | 1         | 0.74%   |
| 5.7.4   | 1         | 0.74%   |
| 5.6.2   | 1         | 0.74%   |
| 5.4.99  | 1         | 0.74%   |
| 5.4.73  | 1         | 0.74%   |
| 5.4.72  | 1         | 0.74%   |
| 5.4.65  | 1         | 0.74%   |
| 5.4.64  | 1         | 0.74%   |
| 5.4.6   | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 36.64%  |
| 5.4     | 23        | 17.56%  |
| 5.10    | 23        | 17.56%  |
| 6.1     | 12        | 9.16%   |
| 5.17    | 4         | 3.05%   |
| 3.10    | 3         | 2.29%   |
| 5.8     | 2         | 1.53%   |
| 5.19    | 2         | 1.53%   |
| 5.14    | 2         | 1.53%   |
| 4.4     | 2         | 1.53%   |
| 6.4     | 1         | 0.76%   |
| 6.3     | 1         | 0.76%   |
| 6.0     | 1         | 0.76%   |
| 5.7     | 1         | 0.76%   |
| 5.6     | 1         | 0.76%   |
| 5.18    | 1         | 0.76%   |
| 5.16    | 1         | 0.76%   |
| 5.13    | 1         | 0.76%   |
| 5.12    | 1         | 0.76%   |
| 4.14    | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 105       | 84%     |
| i686    | 14        | 11.2%   |
| aarch64 | 3         | 2.4%    |
| armv7l  | 2         | 1.6%    |
| i586    | 1         | 0.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 102       | 81.6%   |
| XFCE    | 9         | 7.2%    |
| GNOME   | 6         | 4.8%    |
| KDE5    | 3         | 2.4%    |
| sway    | 2         | 1.6%    |
| LXQt    | 1         | 0.8%    |
| KDE     | 1         | 0.8%    |
| i3      | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 60.63%  |
| X11     | 40        | 31.5%   |
| Wayland | 9         | 7.09%   |
| Tty     | 1         | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 103       | 81.75%  |
| LightDM | 16        | 12.7%   |
| GDM     | 3         | 2.38%   |
| SDDM    | 2         | 1.59%   |
| XDM     | 1         | 0.79%   |
| LXDM    | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 78        | 60.94%  |
| Unknown | 39        | 30.47%  |
| en_US   | 7         | 5.47%   |
| ru_RU   | 2         | 1.56%   |
| pt_BR   | 1         | 0.78%   |
| en_GB   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 82        | 65.08%  |
| EFI  | 44        | 34.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 77.95%  |
| Btrfs   | 9         | 7.09%   |
| Overlay | 8         | 6.3%    |
| Tmpfs   | 5         | 3.94%   |
| F2fs    | 2         | 1.57%   |
| Unknown | 2         | 1.57%   |
| Zfs     | 1         | 0.79%   |
| Ext2    | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 62.31%  |
| GPT     | 34        | 26.15%  |
| MBR     | 15        | 11.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 86.51%  |
| Yes       | 17        | 13.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 92.91%  |
| Yes       | 9         | 7.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 20        | 16%     |
| Hewlett-Packard         | 17        | 13.6%   |
| ASUSTek Computer        | 14        | 11.2%   |
| Lenovo                  | 13        | 10.4%   |
| Intel                   | 6         | 4.8%    |
| Gigabyte Technology     | 5         | 4%      |
| ASRock                  | 5         | 4%      |
| Acer                    | 5         | 4%      |
| Fujitsu                 | 4         | 3.2%    |
| Unknown                 | 4         | 3.2%    |
| Toshiba                 | 3         | 2.4%    |
| MSI                     | 3         | 2.4%    |
| IBM                     | 3         | 2.4%    |
| Google                  | 3         | 2.4%    |
| Raspberry Pi Foundation | 2         | 1.6%    |
| Gateway                 | 2         | 1.6%    |
| Apple                   | 2         | 1.6%    |
| VIA Technologies        | 1         | 0.8%    |
| UGREEN                  | 1         | 0.8%    |
| Synology                | 1         | 0.8%    |
| Supermicro              | 1         | 0.8%    |
| Sony                    | 1         | 0.8%    |
| Shuttle                 | 1         | 0.8%    |
| Pegatron                | 1         | 0.8%    |
| Olivetti                | 1         | 0.8%    |
| Notebook                | 1         | 0.8%    |
| Haier                   | 1         | 0.8%    |
| Fanless Mini PC         | 1         | 0.8%    |
| F5 Networks             | 1         | 0.8%    |
| eMachines               | 1         | 0.8%    |
| AMI                     | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 3.2%    |
| HP ProLiant DL360 G6                     | 2         | 1.6%    |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.6%    |
| Dell Dell Thin Client Desktop 3030 LT    | 2         | 1.6%    |
| ASUS All Series                          | 2         | 1.6%    |
| VIA KM266APro-835                        | 1         | 0.8%    |
| UGREEN DX4600                            | 1         | 0.8%    |
| Toshiba WT8-A                            | 1         | 0.8%    |
| Toshiba Satellite Pro L50-A              | 1         | 0.8%    |
| Toshiba Satellite M645                   | 1         | 0.8%    |
| Synology DS1019+                         | 1         | 0.8%    |
| Supermicro X10SLL-F                      | 1         | 0.8%    |
| Sony VGN-UX27GN                          | 1         | 0.8%    |
| Shuttle DS81D                            | 1         | 0.8%    |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.8%    |
| RPi Raspberry Pi                         | 1         | 0.8%    |
| Pegatron Deepcam                         | 1         | 0.8%    |
| Olivetti Spring Peak                     | 1         | 0.8%    |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.8%    |
| MSI MS-7C82                              | 1         | 0.8%    |
| MSI MS-7877                              | 1         | 0.8%    |
| MSI GL72M 7REX                           | 1         | 0.8%    |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.8%    |
| Lenovo V14-ADA 82C6                      | 1         | 0.8%    |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.8%    |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.8%    |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.8%    |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.8%    |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.8%    |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.8%    |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.8%    |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.8%    |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.8%    |
| Lenovo H535 10117                        | 1         | 0.8%    |
| Intel NUC6i7KYB H90766-406               | 1         | 0.8%    |
| Intel Merrifield                         | 1         | 0.8%    |
| Intel ECO 44 G7                          | 1         | 0.8%    |
| Intel DQ67SW                             | 1         | 0.8%    |
| Intel DH61BF AAG81311-101                | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 7         | 5.6%    |
| Dell Inspiron       | 7         | 5.6%    |
| Dell OptiPlex       | 5         | 4%      |
| Acer Aspire         | 5         | 4%      |
| Unknown             | 4         | 3.2%    |
| HP ProLiant         | 3         | 2.4%    |
| HP EliteBook        | 3         | 2.4%    |
| Toshiba Satellite   | 2         | 1.6%    |
| RPi Raspberry       | 2         | 1.6%    |
| Lenovo ThinkCentre  | 2         | 1.6%    |
| HP Compaq           | 2         | 1.6%    |
| Gigabyte Z490I      | 2         | 1.6%    |
| Dell XPS            | 2         | 1.6%    |
| Dell Dell           | 2         | 1.6%    |
| ASUS PRIME          | 2         | 1.6%    |
| ASUS All            | 2         | 1.6%    |
| VIA KM266APro-835   | 1         | 0.8%    |
| UGREEN DX4600       | 1         | 0.8%    |
| Toshiba WT8-A       | 1         | 0.8%    |
| Synology DS1019+    | 1         | 0.8%    |
| Supermicro X10SLL-F | 1         | 0.8%    |
| Sony VGN-UX27GN     | 1         | 0.8%    |
| Shuttle DS81D       | 1         | 0.8%    |
| Pegatron Deepcam    | 1         | 0.8%    |
| Olivetti Spring     | 1         | 0.8%    |
| Notebook NV4XMB     | 1         | 0.8%    |
| MSI MS-7C82         | 1         | 0.8%    |
| MSI MS-7877         | 1         | 0.8%    |
| MSI GL72M           | 1         | 0.8%    |
| Lenovo Yoga         | 1         | 0.8%    |
| Lenovo V14-ADA      | 1         | 0.8%    |
| Lenovo IdeaPad      | 1         | 0.8%    |
| Lenovo H535         | 1         | 0.8%    |
| Intel NUC6i7KYB     | 1         | 0.8%    |
| Intel Merrifield    | 1         | 0.8%    |
| Intel ECO           | 1         | 0.8%    |
| Intel DQ67SW        | 1         | 0.8%    |
| Intel DH61BF        | 1         | 0.8%    |
| Intel D525MW        | 1         | 0.8%    |
| IBM ThinkPad        | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 16        | 12.8%   |
| 2018    | 11        | 8.8%    |
| 2012    | 10        | 8%      |
| 2020    | 8         | 6.4%    |
| 2019    | 8         | 6.4%    |
| 2013    | 8         | 6.4%    |
| 2010    | 8         | 6.4%    |
| 2016    | 7         | 5.6%    |
| 2017    | 6         | 4.8%    |
| 2015    | 6         | 4.8%    |
| 2011    | 6         | 4.8%    |
| Unknown | 6         | 4.8%    |
| 2021    | 5         | 4%      |
| 2009    | 5         | 4%      |
| 2006    | 4         | 3.2%    |
| 2022    | 3         | 2.4%    |
| 2007    | 2         | 1.6%    |
| 2005    | 2         | 1.6%    |
| 2023    | 1         | 0.8%    |
| 2008    | 1         | 0.8%    |
| 2004    | 1         | 0.8%    |
| 1999    | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 61        | 48.8%   |
| Desktop        | 43        | 34.4%   |
| Mini pc        | 9         | 7.2%    |
| Server         | 5         | 4%      |
| System on chip | 3         | 2.4%    |
| Tablet         | 2         | 1.6%    |
| Convertible    | 1         | 0.8%    |
| All in one     | 1         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 97.6%   |
| Yes  | 3         | 2.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 28        | 21.54%  |
| 3.01-4.0        | 24        | 18.46%  |
| 16.01-24.0      | 21        | 16.15%  |
| 8.01-16.0       | 14        | 10.77%  |
| 32.01-64.0      | 10        | 7.69%   |
| 0.51-1.0        | 10        | 7.69%   |
| 1.01-2.0        | 9         | 6.92%   |
| 2.01-3.0        | 5         | 3.85%   |
| 64.01-256.0     | 4         | 3.08%   |
| 0.01-0.5        | 4         | 3.08%   |
| More than 256.0 | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 41        | 31.06%  |
| 1.01-2.0  | 26        | 19.7%   |
| 0.51-1.0  | 23        | 17.42%  |
| 2.01-3.0  | 13        | 9.85%   |
| 3.01-4.0  | 11        | 8.33%   |
| 4.01-8.0  | 7         | 5.3%    |
| 8.01-16.0 | 5         | 3.79%   |
| 0         | 3         | 2.27%   |
| Unknown   | 3         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 64.84%  |
| 2      | 22        | 17.19%  |
| 3      | 8         | 6.25%   |
| 4      | 6         | 4.69%   |
| 14     | 2         | 1.56%   |
| 5      | 2         | 1.56%   |
| 0      | 2         | 1.56%   |
| 12     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |
| 7      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 78.57%  |
| Yes       | 27        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 85.6%   |
| No        | 18        | 14.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 59.52%  |
| No        | 51        | 40.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 57.14%  |
| Yes       | 54        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 32        | 25.2%   |
| Germany      | 13        | 10.24%  |
| Russia       | 11        | 8.66%   |
| Canada       | 10        | 7.87%   |
| UK           | 9         | 7.09%   |
| Brazil       | 5         | 3.94%   |
| Sweden       | 4         | 3.15%   |
| Spain        | 4         | 3.15%   |
| Australia    | 4         | 3.15%   |
| China        | 3         | 2.36%   |
| Portugal     | 2         | 1.57%   |
| Poland       | 2         | 1.57%   |
| Norway       | 2         | 1.57%   |
| Italy        | 2         | 1.57%   |
| Guatemala    | 2         | 1.57%   |
| Venezuela    | 1         | 0.79%   |
| Ukraine      | 1         | 0.79%   |
| UAE          | 1         | 0.79%   |
| Switzerland  | 1         | 0.79%   |
| South Korea  | 1         | 0.79%   |
| South Africa | 1         | 0.79%   |
| Slovakia     | 1         | 0.79%   |
| Pakistan     | 1         | 0.79%   |
| Netherlands  | 1         | 0.79%   |
| Mexico       | 1         | 0.79%   |
| Jamaica      | 1         | 0.79%   |
| Israel       | 1         | 0.79%   |
| Indonesia    | 1         | 0.79%   |
| Hungary      | 1         | 0.79%   |
| Greece       | 1         | 0.79%   |
| France       | 1         | 0.79%   |
| Finland      | 1         | 0.79%   |
| Egypt        | 1         | 0.79%   |
| Denmark      | 1         | 0.79%   |
| Czechia      | 1         | 0.79%   |
| Austria      | 1         | 0.79%   |
| Argentina    | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 5.38%   |
| St Petersburg     | 6         | 4.62%   |
| Manitowoc         | 5         | 3.85%   |
| Vernon            | 3         | 2.31%   |
| Sydney            | 2         | 1.54%   |
| Stratford         | 2         | 1.54%   |
| Siegsdorf         | 2         | 1.54%   |
| Moscow            | 2         | 1.54%   |
| Guatemala City    | 2         | 1.54%   |
| Gothenburg        | 2         | 1.54%   |
| Fulham            | 2         | 1.54%   |
| Frankfurt am Main | 2         | 1.54%   |
| As                | 2         | 1.54%   |
| Zurich            | 1         | 0.77%   |
| Zhangzhou         | 1         | 0.77%   |
| Yakima            | 1         | 0.77%   |
| Vejle             | 1         | 0.77%   |
| Vancouver         | 1         | 0.77%   |
| Tymovskoye        | 1         | 0.77%   |
| Tuusula           | 1         | 0.77%   |
| Turin             | 1         | 0.77%   |
| Topeka            | 1         | 0.77%   |
| Thame             | 1         | 0.77%   |
| Tampa             | 1         | 0.77%   |
| Stockholm         | 1         | 0.77%   |
| Stewartstown      | 1         | 0.77%   |
| Somerset          | 1         | 0.77%   |
| Sisteron          | 1         | 0.77%   |
| Semily            | 1         | 0.77%   |
| Seattle           | 1         | 0.77%   |
| Sao Paulo         | 1         | 0.77%   |
| San Mateo         | 1         | 0.77%   |
| Salzburg          | 1         | 0.77%   |
| Saarbrücken      | 1         | 0.77%   |
| Rzeszów          | 1         | 0.77%   |
| Rostock           | 1         | 0.77%   |
| Redwood City      | 1         | 0.77%   |
| Purdys            | 1         | 0.77%   |
| Plymouth          | 1         | 0.77%   |
| Penza             | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 23        | 32     | 13.37%  |
| WDC                         | 20        | 50     | 11.63%  |
| Unknown                     | 15        | 18     | 8.72%   |
| Seagate                     | 15        | 43     | 8.72%   |
| Toshiba                     | 11        | 13     | 6.4%    |
| Hitachi                     | 11        | 11     | 6.4%    |
| Kingston                    | 9         | 10     | 5.23%   |
| Crucial                     | 9         | 17     | 5.23%   |
| HGST                        | 8         | 8      | 4.65%   |
| SK hynix                    | 6         | 8      | 3.49%   |
| Sandisk                     | 6         | 8      | 3.49%   |
| Intel                       | 6         | 10     | 3.49%   |
| A-DATA Technology           | 6         | 8      | 3.49%   |
| Transcend                   | 2         | 2      | 1.16%   |
| SPCC                        | 2         | 2      | 1.16%   |
| LITEON                      | 2         | 2      | 1.16%   |
| Fujitsu                     | 2         | 2      | 1.16%   |
| STEC                        | 1         | 1      | 0.58%   |
| PNY                         | 1         | 1      | 0.58%   |
| Phison Electronics          | 1         | 1      | 0.58%   |
| NETAPP                      | 1         | 1      | 0.58%   |
| Micron Technology           | 1         | 1      | 0.58%   |
| Lexar                       | 1         | 1      | 0.58%   |
| KIOXIA                      | 1         | 1      | 0.58%   |
| Kingston Technology Company | 1         | 1      | 0.58%   |
| Kingmax                     | 1         | 1      | 0.58%   |
| KC600                       | 1         | 1      | 0.58%   |
| JMicron Technology          | 1         | 1      | 0.58%   |
| Intenso                     | 1         | 1      | 0.58%   |
| IBM                         | 1         | 1      | 0.58%   |
| Emtec                       | 1         | 1      | 0.58%   |
| Dell                        | 1         | 2      | 0.58%   |
| China                       | 1         | 1      | 0.58%   |
| Apple                       | 1         | 3      | 0.58%   |
| AMD                         | 1         | 1      | 0.58%   |
| Unknown                     | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                              | 4         | 2.06%   |
| Unknown MMC Card  4GB                               | 3         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 1.55%   |
| WDC WD3000BLFS-60YBU2 304GB                         | 2         | 1.03%   |
| Unknown MMC Card  64GB                              | 2         | 1.03%   |
| Unknown MMC Card  32GB                              | 2         | 1.03%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.03%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 1.03%   |
| Seagate ST4000VN008-2DR1 4TB                        | 2         | 1.03%   |
| Samsung SSD 960 EVO 500GB                           | 2         | 1.03%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 1.03%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.03%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 1.03%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 1.03%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 1.03%   |
| Crucial CT120BX500SSD1 120GB                        | 2         | 1.03%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.03%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.52%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.52%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.52%   |
| WDC WDS250G2B0B 250GB SSD                           | 1         | 0.52%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.52%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.52%   |
| WDC WD80EFAX-68LHPN0 8TB                            | 1         | 0.52%   |
| WDC WD800AAJS-00 80GB                               | 1         | 0.52%   |
| WDC WD5003ABYZ-0 500GB                              | 1         | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 0.52%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1         | 0.52%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1         | 0.52%   |
| WDC WD3200AAKX-0 320GB                              | 1         | 0.52%   |
| WDC WD20EZRZ-00Z 2TB                                | 1         | 0.52%   |
| WDC WD1600BEVT-2 160GB                              | 1         | 0.52%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1         | 0.52%   |
| WDC WD140EDFZ-11A0VA0 14TB                          | 1         | 0.52%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1         | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.52%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 1         | 0.52%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 42     | 23.08%  |
| Seagate             | 15        | 43     | 23.08%  |
| Hitachi             | 11        | 11     | 16.92%  |
| Toshiba             | 9         | 10     | 13.85%  |
| HGST                | 8         | 8      | 12.31%  |
| Samsung Electronics | 3         | 5      | 4.62%   |
| Fujitsu             | 2         | 2      | 3.08%   |
| JMicron Technology  | 1         | 1      | 1.54%   |
| IBM                 | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 15.25%  |
| Crucial             | 9         | 17     | 15.25%  |
| Samsung Electronics | 8         | 10     | 13.56%  |
| WDC                 | 4         | 6      | 6.78%   |
| Intel               | 4         | 6      | 6.78%   |
| A-DATA Technology   | 4         | 4      | 6.78%   |
| SanDisk             | 3         | 4      | 5.08%   |
| Transcend           | 2         | 2      | 3.39%   |
| SPCC                | 2         | 2      | 3.39%   |
| SK hynix            | 2         | 3      | 3.39%   |
| LITEON              | 2         | 2      | 3.39%   |
| PNY                 | 1         | 1      | 1.69%   |
| Micron Technology   | 1         | 1      | 1.69%   |
| Lexar               | 1         | 1      | 1.69%   |
| Kingmax             | 1         | 1      | 1.69%   |
| KC600               | 1         | 1      | 1.69%   |
| Intenso             | 1         | 1      | 1.69%   |
| Emtec               | 1         | 1      | 1.69%   |
| Dell                | 1         | 2      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| AMD                 | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 58        | 123    | 37.42%  |
| SSD     | 52        | 77     | 33.55%  |
| NVMe    | 29        | 45     | 18.71%  |
| MMC     | 15        | 19     | 9.68%   |
| Unknown | 1         | 2      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 195    | 64.75%  |
| NVMe | 29        | 45     | 20.86%  |
| MMC  | 15        | 19     | 10.79%  |
| SAS  | 5         | 7      | 3.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 117    | 66.67%  |
| 0.51-1.0   | 22        | 29     | 19.82%  |
| 3.01-4.0   | 4         | 15     | 3.6%    |
| 4.01-10.0  | 4         | 20     | 3.6%    |
| 10.01-20.0 | 3         | 13     | 2.7%    |
| 2.01-3.0   | 2         | 2      | 1.8%    |
| 1.01-2.0   | 2         | 4      | 1.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 21.71%  |
| 1-20           | 23        | 17.83%  |
| Unknown        | 21        | 16.28%  |
| 251-500        | 12        | 9.3%    |
| 501-1000       | 12        | 9.3%    |
| 21-50          | 10        | 7.75%   |
| 1001-2000      | 8         | 6.2%    |
| More than 3000 | 7         | 5.43%   |
| 2001-3000      | 4         | 3.1%    |
| 51-100         | 4         | 3.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 72        | 56.25%  |
| Unknown        | 21        | 16.41%  |
| 251-500        | 8         | 6.25%   |
| 21-50          | 8         | 6.25%   |
| 51-100         | 8         | 6.25%   |
| 501-1000       | 4         | 3.13%   |
| 101-250        | 3         | 2.34%   |
| 1001-2000      | 2         | 1.56%   |
| More than 3000 | 1         | 0.78%   |
| 2001-3000      | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 10.53%  |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 5.26%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 5.26%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 5.26%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 5.26%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 5.26%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 5.26%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 5.26%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 5.26%   |
| Kingmax SSD 120G                               | 1         | 1      | 5.26%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 5.26%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 5.26%   |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 5.26%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 5.26%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 5.26%   |
| HGST HTS725050A7 500GB                         | 1         | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.26%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 26.32%  |
| WDC                 | 3         | 15     | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 4      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Seagate             | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Kingmax             | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 33.33%  |
| WDC                 | 3         | 15     | 20%     |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 4      | 13.33%  |
| HGST                | 2         | 2      | 13.33%  |
| Seagate             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 29     | 78.95%  |
| SSD  | 3         | 3      | 15.79%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 79        | 166    | 57.66%  |
| Detected | 40        | 67     | 29.2%   |
| Malfunc  | 18        | 33     | 13.14%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 84        | 57.93%  |
| Samsung Electronics          | 14        | 9.66%   |
| AMD                          | 14        | 9.66%   |
| SanDisk                      | 4         | 2.76%   |
| LSI Logic / Symbios Logic    | 4         | 2.76%   |
| SK hynix                     | 3         | 2.07%   |
| Marvell Technology Group     | 3         | 2.07%   |
| ADATA Technology             | 3         | 2.07%   |
| KIOXIA                       | 2         | 1.38%   |
| Hewlett-Packard              | 2         | 1.38%   |
| ASMedia Technology           | 2         | 1.38%   |
| Adaptec                      | 2         | 1.38%   |
| VIA Technologies             | 1         | 0.69%   |
| Toshiba America Info Systems | 1         | 0.69%   |
| Promise Technology           | 1         | 0.69%   |
| Phison Electronics           | 1         | 0.69%   |
| Nvidia                       | 1         | 0.69%   |
| Micron/Crucial Technology    | 1         | 0.69%   |
| Kingston Technology Company  | 1         | 0.69%   |
| Broadcom / LSI               | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 6.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 5.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 5.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 3.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 3.11%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.48%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.86%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.24%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.24%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.24%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.24%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.24%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2         | 1.24%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.62%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.62%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.62%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 81        | 56.25%  |
| NVMe | 28        | 19.44%  |
| IDE  | 18        | 12.5%   |
| RAID | 13        | 9.03%   |
| SAS  | 4         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 103       | 81.75%  |
| AMD     | 18        | 14.29%  |
| ARM     | 4         | 3.17%   |
| Unknown | 1         | 0.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 1.57%   |
| Intel Pentium M processor 1.70GHz      | 2         | 1.57%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 1.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 1.57%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 1.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 1.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 1.57%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 1.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 1.57%   |
| Intel Celeron CPU N2807 @ 1.58GHz      | 2         | 1.57%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 1.57%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 1.57%   |
| ARM Processor                          | 2         | 1.57%   |
| AMD FX-8350 Eight-Core Processor       | 2         | 1.57%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 0.79%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 0.79%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 0.79%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 0.79%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 0.79%   |
| Intel Pentium M processor 1.60GHz      | 1         | 0.79%   |
| Intel Pentium M processor 1.50GHz      | 1         | 0.79%   |
| Intel Pentium III (Coppermine)         | 1         | 0.79%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 0.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1         | 0.79%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 0.79%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 0.79%   |
| Intel Mobile Pentium MMX               | 1         | 0.79%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 0.79%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 0.79%   |
| Intel Core m3-8100Y CPU @ 1.10GHz      | 1         | 0.79%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 0.79%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1         | 0.79%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1         | 0.79%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 0.79%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 0.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.79%   |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 0.79%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz      | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 27        | 21.26%  |
| Intel Celeron      | 15        | 11.81%  |
| Other              | 12        | 9.45%   |
| Intel Core i7      | 11        | 8.66%   |
| Intel Core i3      | 9         | 7.09%   |
| Intel Atom         | 9         | 7.09%   |
| Intel Xeon         | 6         | 4.72%   |
| Intel Pentium M    | 4         | 3.15%   |
| Intel Pentium      | 3         | 2.36%   |
| Intel Core i9      | 3         | 2.36%   |
| Intel Core 2 Duo   | 3         | 2.36%   |
| AMD Ryzen 7        | 3         | 2.36%   |
| AMD FX             | 2         | 1.57%   |
| AMD A4             | 2         | 1.57%   |
| Intel Xeon Gold    | 1         | 0.79%   |
| Intel Pentium III  | 1         | 0.79%   |
| Intel Pentium Dual | 1         | 0.79%   |
| Intel Genuine      | 1         | 0.79%   |
| Intel Core Solo    | 1         | 0.79%   |
| Intel Core m3      | 1         | 0.79%   |
| Intel Core 2       | 1         | 0.79%   |
| Intel Celeron M    | 1         | 0.79%   |
| ARM BCM            | 1         | 0.79%   |
| AMD Sempron        | 1         | 0.79%   |
| AMD Ryzen 9        | 1         | 0.79%   |
| AMD Ryzen 5        | 1         | 0.79%   |
| AMD Ryzen 3        | 1         | 0.79%   |
| AMD E2             | 1         | 0.79%   |
| AMD E1             | 1         | 0.79%   |
| AMD A8             | 1         | 0.79%   |
| AMD A6             | 1         | 0.79%   |
| AMD A10            | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 51        | 40.16%  |
| 4       | 40        | 31.5%   |
| 1       | 14        | 11.02%  |
| 8       | 6         | 4.72%   |
| 12      | 4         | 3.15%   |
| 6       | 4         | 3.15%   |
| 10      | 2         | 1.57%   |
| Unknown | 2         | 1.57%   |
| 32      | 1         | 0.79%   |
| 16      | 1         | 0.79%   |
| 14      | 1         | 0.79%   |
| 3       | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 119       | 94.44%  |
| 2       | 4         | 3.17%   |
| Unknown | 2         | 1.59%   |
| 0       | 1         | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 64        | 51.2%   |
| 2       | 59        | 47.2%   |
| Unknown | 2         | 1.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 66        | 51.56%  |
| 32-bit, 64-bit | 56        | 43.75%  |
| 32-bit         | 5         | 3.91%   |
| 64-bit         | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 58.78%  |
| 0x306c3    | 7         | 5.34%   |
| 0x306a9    | 5         | 3.82%   |
| 0x30678    | 4         | 3.05%   |
| 0x906ea    | 3         | 2.29%   |
| 0x206c2    | 3         | 2.29%   |
| 0x806eb    | 2         | 1.53%   |
| 0x506c9    | 2         | 1.53%   |
| 0x406c4    | 2         | 1.53%   |
| 0x206a7    | 2         | 1.53%   |
| 0x106e5    | 2         | 1.53%   |
| 0x106ca    | 2         | 1.53%   |
| 0x06006704 | 2         | 1.53%   |
| 0xa0655    | 1         | 0.76%   |
| 0x906a3    | 1         | 0.76%   |
| 0x90672    | 1         | 0.76%   |
| 0x806c1    | 1         | 0.76%   |
| 0x706e5    | 1         | 0.76%   |
| 0x6fd      | 1         | 0.76%   |
| 0x6d8      | 1         | 0.76%   |
| 0x683      | 1         | 0.76%   |
| 0x506e3    | 1         | 0.76%   |
| 0x306d4    | 1         | 0.76%   |
| 0x20655    | 1         | 0.76%   |
| 0x1067a    | 1         | 0.76%   |
| 0x08701021 | 1         | 0.76%   |
| 0x08108109 | 1         | 0.76%   |
| 0x0810100b | 1         | 0.76%   |
| 0x0800820d | 1         | 0.76%   |
| 0x06000817 | 1         | 0.76%   |
| 0x010000b6 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 13        | 10.24%  |
| KabyLake         | 13        | 10.24%  |
| Haswell          | 11        | 8.66%   |
| Unknown          | 9         | 7.09%   |
| SandyBridge      | 7         | 5.51%   |
| P6               | 7         | 5.51%   |
| IvyBridge        | 7         | 5.51%   |
| Westmere         | 6         | 4.72%   |
| Skylake          | 5         | 3.94%   |
| Goldmont         | 5         | 3.94%   |
| Penryn           | 4         | 3.15%   |
| Broadwell        | 4         | 3.15%   |
| Bonnell          | 4         | 3.15%   |
| Piledriver       | 3         | 2.36%   |
| Excavator        | 3         | 2.36%   |
| CometLake        | 3         | 2.36%   |
| Zen+             | 2         | 1.57%   |
| Zen 2            | 2         | 1.57%   |
| TigerLake        | 2         | 1.57%   |
| Nehalem          | 2         | 1.57%   |
| Jaguar           | 2         | 1.57%   |
| IceLake          | 2         | 1.57%   |
| Core             | 2         | 1.57%   |
| Alderlake Hybrid | 2         | 1.57%   |
| Zen 3            | 1         | 0.79%   |
| Zen              | 1         | 0.79%   |
| Puma             | 1         | 0.79%   |
| K6               | 1         | 0.79%   |
| K10              | 1         | 0.79%   |
| Goldmont plus    | 1         | 0.79%   |
| Bobcat           | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 87        | 65.91%  |
| AMD                        | 27        | 20.45%  |
| Nvidia                     | 10        | 7.58%   |
| Matrox Electronics Systems | 4         | 3.03%   |
| Neomagic                   | 2         | 1.52%   |
| VIA Technologies           | 1         | 0.76%   |
| ASPEED Technology          | 1         | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 7.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 5.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 3.62%   |
| Intel HD Graphics 500                                                                    | 4         | 2.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.17%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 2.17%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.17%   |
| AMD ES1000                                                                               | 3         | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.45%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.45%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.45%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.45%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.72%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.72%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.72%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1         | 0.72%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.72%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 0.72%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 0.72%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 71        | 55.91%  |
| 1 x AMD         | 23        | 18.11%  |
| Other           | 6         | 4.72%   |
| 2 x Intel       | 6         | 4.72%   |
| Intel + Nvidia  | 5         | 3.94%   |
| 1 x Nvidia      | 4         | 3.15%   |
| 1 x Matrox      | 3         | 2.36%   |
| Intel + AMD     | 3         | 2.36%   |
| 1 x Neomagic    | 2         | 1.57%   |
| 2 x AMD         | 1         | 0.79%   |
| 1 x VIA         | 1         | 0.79%   |
| Nvidia + Matrox | 1         | 0.79%   |
| 1 x ASPEED      | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 107       | 83.59%  |
| Unknown     | 19        | 14.84%  |
| Proprietary | 2         | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 86.4%   |
| 0.01-0.5   | 7         | 5.6%    |
| 7.01-8.0   | 3         | 2.4%    |
| 1.01-2.0   | 3         | 2.4%    |
| 0.51-1.0   | 2         | 1.6%    |
| 3.01-4.0   | 1         | 0.8%    |
| 8.01-16.0  | 1         | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 12.75%  |
| LG Display              | 10        | 9.8%    |
| Dell                    | 9         | 8.82%   |
| BOE                     | 8         | 7.84%   |
| Samsung Electronics     | 7         | 6.86%   |
| Goldstar                | 6         | 5.88%   |
| Chimei Innolux          | 6         | 5.88%   |
| BenQ                    | 5         | 4.9%    |
| AOC                     | 4         | 3.92%   |
| Chi Mei Optoelectronics | 3         | 2.94%   |
| Acer                    | 3         | 2.94%   |
| Sharp                   | 2         | 1.96%   |
| LG Philips              | 2         | 1.96%   |
| Lenovo                  | 2         | 1.96%   |
| Jean                    | 2         | 1.96%   |
| InfoVision              | 2         | 1.96%   |
| Hewlett-Packard         | 2         | 1.96%   |
| ViewSonic               | 1         | 0.98%   |
| Sony                    | 1         | 0.98%   |
| SKY                     | 1         | 0.98%   |
| Philips                 | 1         | 0.98%   |
| ONN                     | 1         | 0.98%   |
| Mi                      | 1         | 0.98%   |
| KVM                     | 1         | 0.98%   |
| HannStar                | 1         | 0.98%   |
| Envision                | 1         | 0.98%   |
| Elo Touch               | 1         | 0.98%   |
| EDI                     | 1         | 0.98%   |
| DENON                   | 1         | 0.98%   |
| CTC                     | 1         | 0.98%   |
| CSO                     | 1         | 0.98%   |
| CPT                     | 1         | 0.98%   |
| Apple                   | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 2.86%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2         | 1.9%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.9%    |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.9%    |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.95%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.95%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.95%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.95%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.95%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.95%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 1         | 0.95%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1         | 0.95%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.95%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.95%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 0.95%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 0.95%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch          | 1         | 0.95%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 0.95%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 0.95%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch          | 1         | 0.95%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 509x286mm 23.0-inch      | 1         | 0.95%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 0.95%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 0.95%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 0.95%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch              | 1         | 0.95%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 0.95%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 27        | 26.47%  |
| 1366x768 (WXGA)    | 26        | 25.49%  |
| 3840x2160 (4K)     | 6         | 5.88%   |
| 1680x1050 (WSXGA+) | 6         | 5.88%   |
| 2560x1440 (QHD)    | 5         | 4.9%    |
| 1280x800 (WXGA)    | 5         | 4.9%    |
| 1280x1024 (SXGA)   | 5         | 4.9%    |
| 3440x1440          | 3         | 2.94%   |
| 1920x1200 (WUXGA)  | 3         | 2.94%   |
| 1024x768 (XGA)     | 3         | 2.94%   |
| 1024x600           | 3         | 2.94%   |
| 2560x1080          | 2         | 1.96%   |
| 1600x900 (HD+)     | 2         | 1.96%   |
| 1440x900 (WXGA+)   | 2         | 1.96%   |
| 2880x1800          | 1         | 0.98%   |
| 2560x1700          | 1         | 0.98%   |
| 1360x768           | 1         | 0.98%   |
| 1280x768           | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 22        | 21.78%  |
| 14     | 10        | 9.9%    |
| 13     | 9         | 8.91%   |
| 17     | 7         | 6.93%   |
| 27     | 6         | 5.94%   |
| 24     | 5         | 4.95%   |
| 23     | 5         | 4.95%   |
| 11     | 5         | 4.95%   |
| 21     | 4         | 3.96%   |
| 20     | 4         | 3.96%   |
| 34     | 3         | 2.97%   |
| 19     | 3         | 2.97%   |
| 12     | 3         | 2.97%   |
| 10     | 3         | 2.97%   |
| 31     | 2         | 1.98%   |
| 22     | 2         | 1.98%   |
| 65     | 1         | 0.99%   |
| 60     | 1         | 0.99%   |
| 40     | 1         | 0.99%   |
| 32     | 1         | 0.99%   |
| 29     | 1         | 0.99%   |
| 25     | 1         | 0.99%   |
| 18     | 1         | 0.99%   |
| 16     | 1         | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 41%     |
| 501-600     | 16        | 16%     |
| 201-300     | 14        | 14%     |
| 401-500     | 12        | 12%     |
| 351-400     | 6         | 6%      |
| 701-800     | 4         | 4%      |
| 601-700     | 4         | 4%      |
| 1001-1500   | 2         | 2%      |
| 801-900     | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 67.02%  |
| 16/10 | 18        | 19.15%  |
| 5/4   | 5         | 5.32%   |
| 21/9  | 4         | 4.26%   |
| 4/3   | 3         | 3.19%   |
| 3/2   | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 21.78%  |
| 81-90          | 16        | 15.84%  |
| 201-250        | 14        | 13.86%  |
| 151-200        | 9         | 8.91%   |
| 301-350        | 7         | 6.93%   |
| 351-500        | 6         | 5.94%   |
| 51-60          | 5         | 4.95%   |
| 71-80          | 4         | 3.96%   |
| 41-50          | 3         | 2.97%   |
| 141-150        | 3         | 2.97%   |
| More than 1000 | 2         | 1.98%   |
| 61-70          | 2         | 1.98%   |
| 251-300        | 2         | 1.98%   |
| 131-140        | 2         | 1.98%   |
| 121-130        | 2         | 1.98%   |
| 111-120        | 1         | 0.99%   |
| 501-1000       | 1         | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 35.79%  |
| 101-120       | 29        | 30.53%  |
| 121-160       | 21        | 22.11%  |
| 1-50          | 5         | 5.26%   |
| 161-240       | 4         | 4.21%   |
| More than 240 | 2         | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 85        | 66.41%  |
| 0     | 32        | 25%     |
| 2     | 9         | 7.03%   |
| 4     | 1         | 0.78%   |
| 3     | 1         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 61        | 33.15%  |
| Intel                           | 59        | 32.07%  |
| Qualcomm Atheros                | 20        | 10.87%  |
| Broadcom                        | 18        | 9.78%   |
| Xiaomi                          | 3         | 1.63%   |
| Marvell Technology Group        | 3         | 1.63%   |
| Qualcomm Atheros Communications | 2         | 1.09%   |
| Qualcomm                        | 2         | 1.09%   |
| MediaTek                        | 2         | 1.09%   |
| Broadcom Limited                | 2         | 1.09%   |
| VIA Technologies                | 1         | 0.54%   |
| T & A Mobile Phones             | 1         | 0.54%   |
| Sigma Designs                   | 1         | 0.54%   |
| Nvidia                          | 1         | 0.54%   |
| Microchip Technology            | 1         | 0.54%   |
| Mellanox Technologies           | 1         | 0.54%   |
| LSI                             | 1         | 0.54%   |
| Google                          | 1         | 0.54%   |
| Dresden Elektronik              | 1         | 0.54%   |
| DisplayLink                     | 1         | 0.54%   |
| D-Link System                   | 1         | 0.54%   |
| ASIX Electronics                | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 16.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.78%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.31%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.39%   |
| Intel Wireless 7265                                               | 3         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.93%   |
| Intel Wireless-AC 9260                                            | 2         | 0.93%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.93%   |
| Intel Wireless 8260                                               | 2         | 0.93%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.93%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.93%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.93%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.46%   |
| T & A Mobile Phones Alcatel 3X                                    | 1         | 0.46%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                   | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 48.1%   |
| Qualcomm Atheros                | 17        | 21.52%  |
| Broadcom                        | 10        | 12.66%  |
| Realtek Semiconductor           | 7         | 8.86%   |
| Qualcomm Atheros Communications | 2         | 2.53%   |
| MediaTek                        | 2         | 2.53%   |
| Broadcom Limited                | 2         | 2.53%   |
| Marvell Technology Group        | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 10.13%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 3.8%    |
| Intel Wireless 7265                                                            | 3         | 3.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3         | 3.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 3.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.53%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.53%   |
| Intel Wireless-AC 9260                                                         | 2         | 2.53%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.53%   |
| Intel Wireless 8260                                                            | 2         | 2.53%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.53%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.53%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 2.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 2         | 2.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.27%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.27%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.27%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.27%   |
| Intel Wireless 7260                                                            | 1         | 1.27%   |
| Intel Wireless 3160                                                            | 1         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 1.27%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.27%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.27%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.27%   |
| Intel Centrino Wireless-N 105                                                  | 1         | 1.27%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 45.53%  |
| Intel                    | 37        | 30.08%  |
| Broadcom                 | 11        | 8.94%   |
| Qualcomm Atheros         | 4         | 3.25%   |
| Xiaomi                   | 3         | 2.44%   |
| Qualcomm                 | 2         | 1.63%   |
| Marvell Technology Group | 2         | 1.63%   |
| VIA Technologies         | 1         | 0.81%   |
| T & A Mobile Phones      | 1         | 0.81%   |
| Nvidia                   | 1         | 0.81%   |
| Microchip Technology     | 1         | 0.81%   |
| Mellanox Technologies    | 1         | 0.81%   |
| DisplayLink              | 1         | 0.81%   |
| D-Link System            | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 27.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.69%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.91%   |
| Intel I210 Gigabit Network Connection                             | 4         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 2.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 2.34%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.56%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.56%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.56%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.56%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.56%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.78%   |
| T & A Mobile Phones Alcatel 3X                                    | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.78%   |
| Qualcomm SM6150-IDP _SN:488AC473                                  | 1         | 0.78%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.78%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.78%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.78%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.78%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.78%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.78%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.78%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 55.79%  |
| WiFi     | 75        | 39.47%  |
| Modem    | 7         | 3.68%   |
| Unknown  | 2         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 61.21%  |
| WiFi     | 45        | 38.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 51.97%  |
| 1     | 45        | 35.43%  |
| 0     | 9         | 7.09%   |
| 4     | 3         | 2.36%   |
| 5     | 2         | 1.57%   |
| 3     | 2         | 1.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 82.54%  |
| Yes  | 22        | 17.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 43.86%  |
| Broadcom                        | 5         | 8.77%   |
| Qualcomm Atheros Communications | 4         | 7.02%   |
| IMC Networks                    | 4         | 7.02%   |
| Cambridge Silicon Radio         | 4         | 7.02%   |
| Lite-On Technology              | 3         | 5.26%   |
| Realtek Semiconductor           | 2         | 3.51%   |
| Apple                           | 2         | 3.51%   |
| Toshiba                         | 1         | 1.75%   |
| MediaTek                        | 1         | 1.75%   |
| Marvell Semiconductor           | 1         | 1.75%   |
| Hewlett-Packard                 | 1         | 1.75%   |
| Foxconn / Hon Hai               | 1         | 1.75%   |
| ASUSTek Computer                | 1         | 1.75%   |
| Alps Electric                   | 1         | 1.75%   |
| Actions                         | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 15.79%  |
| Intel AX201 Bluetooth                               | 5         | 8.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 7.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 7.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.26%   |
| Realtek Bluetooth Radio                             | 2         | 3.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.51%   |
| Intel AX200 Bluetooth                               | 2         | 3.51%   |
| IMC Networks Bluetooth Device                       | 2         | 3.51%   |
| Toshiba Bluetooth Device                            | 1         | 1.75%   |
| MediaTek Wireless_Device                            | 1         | 1.75%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.75%   |
| Intel AX210 Bluetooth                               | 1         | 1.75%   |
| IMC Networks Wireless_Device                        | 1         | 1.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.75%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.75%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.75%   |
| Broadcom BCM20702A0                                 | 1         | 1.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.75%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.75%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.75%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.75%   |
| Apple Bluetooth Host Controller                     | 1         | 1.75%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.75%   |
| Actions general adapter                             | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 86        | 67.72%  |
| AMD                                  | 23        | 18.11%  |
| Nvidia                               | 4         | 3.15%   |
| Logitech                             | 2         | 1.57%   |
| C-Media Electronics                  | 2         | 1.57%   |
| VIA Technologies                     | 1         | 0.79%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.79%   |
| Texas Instruments                    | 1         | 0.79%   |
| Sennheiser Communications            | 1         | 0.79%   |
| RODE Microphones                     | 1         | 0.79%   |
| Realtek Semiconductor                | 1         | 0.79%   |
| Native Instruments                   | 1         | 0.79%   |
| Generalplus Technology               | 1         | 0.79%   |
| Cirrus Logic                         | 1         | 0.79%   |
| Apple                                | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 3.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 3.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 3.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 3.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.29%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.97%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.32%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.32%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.32%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.32%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.66%   |
| Thesycon Systemsoftware & Consulting D10                                                          | 1         | 0.66%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.66%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.66%   |
| RODE Microphones RODE NT-USB Mini                                                                 | 1         | 0.66%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 16.95%  |
| Unknown             | 19        | 16.1%   |
| SK hynix            | 19        | 16.1%   |
| Crucial             | 14        | 11.86%  |
| Micron Technology   | 10        | 8.47%   |
| Elpida              | 9         | 7.63%   |
| Kingston            | 8         | 6.78%   |
| Corsair             | 4         | 3.39%   |
| A-DATA Technology   | 3         | 2.54%   |
| Nanya Technology    | 2         | 1.69%   |
| Unknown (ABCD)      | 1         | 0.85%   |
| Transcend           | 1         | 0.85%   |
| Team                | 1         | 0.85%   |
| Ramaxel Technology  | 1         | 0.85%   |
| Qimonda             | 1         | 0.85%   |
| Patriot             | 1         | 0.85%   |
| Hewlett-Packard     | 1         | 0.85%   |
| Gold Key            | 1         | 0.85%   |
| Cors                | 1         | 0.85%   |
| Unknown             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 2.4%    |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.6%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 1.6%    |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 1.6%    |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 1.6%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.8%    |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.8%    |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.8%    |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.8%    |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.8%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.8%    |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.8%    |
| Unknown RAM Module 128MB DIMM                                    | 1         | 0.8%    |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.8%    |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.8%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.8%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.8%    |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 0.8%    |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.8%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.8%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                | 1         | 0.8%    |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s             | 1         | 0.8%    |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 52.48%  |
| DDR4    | 26        | 25.74%  |
| SDRAM   | 5         | 4.95%   |
| LPDDR3  | 5         | 4.95%   |
| DDR     | 4         | 3.96%   |
| LPDDR4  | 3         | 2.97%   |
| DDR2    | 2         | 1.98%   |
| DRAM    | 1         | 0.99%   |
| DDR5    | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 55%     |
| DIMM         | 38        | 38%     |
| Row Of Chips | 5         | 5%      |
| Unknown      | 2         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 37        | 33.33%  |
| 4096  | 32        | 28.83%  |
| 2048  | 18        | 16.22%  |
| 1024  | 8         | 7.21%   |
| 16384 | 5         | 4.5%    |
| 32768 | 4         | 3.6%    |
| 512   | 4         | 3.6%    |
| 128   | 2         | 1.8%    |
| 256   | 1         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 30.28%  |
| 1333    | 9         | 8.26%   |
| Unknown | 9         | 8.26%   |
| 2400    | 8         | 7.34%   |
| 2667    | 7         | 6.42%   |
| 1334    | 7         | 6.42%   |
| 3200    | 6         | 5.5%    |
| 2133    | 5         | 4.59%   |
| 3600    | 4         | 3.67%   |
| 1867    | 3         | 2.75%   |
| 1866    | 2         | 1.83%   |
| 1067    | 2         | 1.83%   |
| 1066    | 2         | 1.83%   |
| 8400    | 1         | 0.92%   |
| 4800    | 1         | 0.92%   |
| 4267    | 1         | 0.92%   |
| 4199    | 1         | 0.92%   |
| 3800    | 1         | 0.92%   |
| 2200    | 1         | 0.92%   |
| 1800    | 1         | 0.92%   |
| 1400    | 1         | 0.92%   |
| 1200    | 1         | 0.92%   |
| 800     | 1         | 0.92%   |
| 667     | 1         | 0.92%   |
| 533     | 1         | 0.92%   |

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
| HP LaserJet 1020 | 1         | 100%    |

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
| Chicony Electronics                    | 13        | 22.81%  |
| Realtek Semiconductor                  | 7         | 12.28%  |
| Microdia                               | 6         | 10.53%  |
| Suyin                                  | 4         | 7.02%   |
| IMC Networks                           | 4         | 7.02%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.02%   |
| Z-Star Microelectronics                | 2         | 3.51%   |
| Sunplus Innovation Technology          | 2         | 3.51%   |
| Quanta                                 | 2         | 3.51%   |
| Bison Electronics                      | 2         | 3.51%   |
| Apple                                  | 2         | 3.51%   |
| Trust                                  | 1         | 1.75%   |
| Syntek                                 | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| MacroSilicon                           | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Linux Foundation                       | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| Acer                                   | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 3         | 5.26%   |
| IMC Networks Integrated Camera                                | 3         | 5.26%   |
| Chicony HD Webcam                                             | 3         | 5.26%   |
| Realtek Acer 640 x 480 laptop camera                          | 2         | 3.51%   |
| Microdia Laptop_Integrated_Webcam_2M                          | 2         | 3.51%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 3.51%   |
| Chicony Integrated Camera                                     | 2         | 3.51%   |
| Z-Star Vimicro USB2.0 Camera                                  | 1         | 1.75%   |
| Z-Star Vega USB 2.0 Camera.                                   | 1         | 1.75%   |
| Trust QHD Webcam                                              | 1         | 1.75%   |
| Syntek EasyCamera                                             | 1         | 1.75%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 1.75%   |
| Suyin HP TrueVision HD                                        | 1         | 1.75%   |
| Suyin HP High Definition 1MP Webcam                           | 1         | 1.75%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.75%   |
| Sunplus HP Universal Camera                                   | 1         | 1.75%   |
| Sunplus HD WebCam                                             | 1         | 1.75%   |
| Silicon Motion NCM-G102                                       | 1         | 1.75%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870]           | 1         | 1.75%   |
| Realtek USB2.0 HD UVC WebCam                                  | 1         | 1.75%   |
| Realtek USB Camera                                            | 1         | 1.75%   |
| Quanta USB2.0 HD UVC WebCam                                   | 1         | 1.75%   |
| Quanta HP TrueVision HD Camera                                | 1         | 1.75%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                | 1         | 1.75%   |
| Microdia Integrated Webcam                                    | 1         | 1.75%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]                 | 1         | 1.75%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.75%   |
| Linux Foundation EEM Gadget                                   | 1         | 1.75%   |
| Lenovo Integrated Webcam                                      | 1         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 1.75%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.75%   |
| Chicony USB2.0 FHD UVC WebCam                                 | 1         | 1.75%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 1.75%   |
| Chicony HP Webcam [2 MP Macro]                                | 1         | 1.75%   |
| Chicony HP HD Camera                                          | 1         | 1.75%   |
| Chicony CNF9055 Toshiba Webcam                                | 1         | 1.75%   |
| Chicony CNF8243 Webcam                                        | 1         | 1.75%   |
| Chicony 2.0M UVC Webcam / CNF7129                             | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                 | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 42.86%  |
| AuthenTec          | 2         | 28.57%  |
| Synaptics          | 1         | 14.29%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 14.29%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 14.29%  |

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
| 0     | 81        | 62.31%  |
| 1     | 29        | 22.31%  |
| 2     | 13        | 10%     |
| 4     | 4         | 3.08%   |
| 3     | 2         | 1.54%   |
| 7     | 1         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 23        | 28.75%  |
| Communication controller | 12        | 15%     |
| Net/wireless             | 8         | 10%     |
| Fingerprint reader       | 7         | 8.75%   |
| Modem                    | 6         | 7.5%    |
| Bluetooth                | 4         | 5%      |
| Network                  | 3         | 3.75%   |
| Camera                   | 3         | 3.75%   |
| Unassigned class         | 2         | 2.5%    |
| Storage/ata              | 2         | 2.5%    |
| Sound                    | 2         | 2.5%    |
| Net/ethernet             | 2         | 2.5%    |
| Multimedia controller    | 2         | 2.5%    |
| Chipcard                 | 2         | 2.5%    |
| Unclassified device      | 1         | 1.25%   |
| Storage                  | 1         | 1.25%   |


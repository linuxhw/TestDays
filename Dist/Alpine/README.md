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

Total: 151

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Dell          | 0J1C3P A00                  | Desktop     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Dell          | 0J1C3P A00                  | Desktop     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Dell          | 0J1C3P A00                  | Desktop     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 11        | 9.32%   |
| Alpine 3.15.0               | 10        | 8.47%   |
| Alpine 3.16.0               | 9         | 7.63%   |
| Alpine 3.15.0_alpha20210804 | 7         | 5.93%   |
| Alpine 3.17_alpha20220809   | 5         | 4.24%   |
| Alpine 3.17.2               | 5         | 4.24%   |
| Alpine 3.14.0               | 5         | 4.24%   |
| Alpine 3.17.1               | 4         | 3.39%   |
| Alpine 3.17.0               | 4         | 3.39%   |
| Alpine 3.16.1               | 4         | 3.39%   |
| Alpine 3.15.4               | 4         | 3.39%   |
| Alpine 3.14.2               | 4         | 3.39%   |
| Alpine 3.13.0_alpha20200917 | 4         | 3.39%   |
| Alpine 3.13.0_alpha20200626 | 4         | 3.39%   |
| Alpine 3.11.2               | 4         | 3.39%   |
| Alpine 3.16.2               | 3         | 2.54%   |
| Alpine 3.13.1               | 3         | 2.54%   |
| Alpine 3.13.0_alpha20201218 | 3         | 2.54%   |
| Alpine 3.16.3               | 2         | 1.69%   |
| Alpine 3.15.6               | 2         | 1.69%   |
| Alpine 3.13.5               | 2         | 1.69%   |
| Alpine 3.13.2               | 2         | 1.69%   |
| Alpine 3.12.3               | 2         | 1.69%   |
| Alpine 3.8.4                | 1         | 0.85%   |
| Alpine 3.17.3               | 1         | 0.85%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.85%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.85%   |
| Alpine 3.15.2               | 1         | 0.85%   |
| Alpine 3.15.0_rc5           | 1         | 0.85%   |
| Alpine 3.14.3               | 1         | 0.85%   |
| Alpine 3.14.0_alpha20210212 | 1         | 0.85%   |
| Alpine 3.13.6               | 1         | 0.85%   |
| Alpine 3.13.3               | 1         | 0.85%   |
| Alpine 3.13.0_rc2           | 1         | 0.85%   |
| Alpine 3.12.7               | 1         | 0.85%   |
| Alpine 3.12.1               | 1         | 0.85%   |
| Alpine 3.12.0_rc1           | 1         | 0.85%   |
| Alpine 3.11.5               | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 109       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 6.72%   |
| 5.15.86-0-lts          | 3         | 2.52%   |
| 5.15.60-0-lts          | 3         | 2.52%   |
| 5.15.16-0-lts          | 3         | 2.52%   |
| 5.10.61-0-lts          | 3         | 2.52%   |
| 5.4.84-0-lts           | 2         | 1.68%   |
| 5.4.83-0-lts           | 2         | 1.68%   |
| 5.17.9-0-edge          | 2         | 1.68%   |
| 5.15.74-0-lts          | 2         | 1.68%   |
| 5.15.59-0-lts          | 2         | 1.68%   |
| 5.15.47-0-lts          | 2         | 1.68%   |
| 5.15.46-1-lts          | 2         | 1.68%   |
| 5.15.41-0-lts          | 2         | 1.68%   |
| 5.15.4-0-lts           | 2         | 1.68%   |
| 5.15.12-0-lts          | 2         | 1.68%   |
| 5.10.68-0-lts          | 2         | 1.68%   |
| 5.10.16-0-lts          | 2         | 1.68%   |
| 6.1.11-0-edge          | 1         | 0.84%   |
| 6.0.10-0-edge          | 1         | 0.84%   |
| 5.8.12-0-edge          | 1         | 0.84%   |
| 5.8.0                  | 1         | 0.84%   |
| 5.7.4                  | 1         | 0.84%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 0.84%   |
| 5.4.99                 | 1         | 0.84%   |
| 5.4.73-0-lts           | 1         | 0.84%   |
| 5.4.72-0-lts           | 1         | 0.84%   |
| 5.4.65-0-lts           | 1         | 0.84%   |
| 5.4.64-0-lts           | 1         | 0.84%   |
| 5.4.6-0-lts            | 1         | 0.84%   |
| 5.4.58-0-lts           | 1         | 0.84%   |
| 5.4.57-0-lts           | 1         | 0.84%   |
| 5.4.46-0-lts           | 1         | 0.84%   |
| 5.4.27-0-lts           | 1         | 0.84%   |
| 5.4.111-0-lts          | 1         | 0.84%   |
| 5.4.0-77-generic       | 1         | 0.84%   |
| 5.19.0-rc8-kukui+      | 1         | 0.84%   |
| 5.18.0-0-asahi         | 1         | 0.84%   |
| 5.17.3-0-edge          | 1         | 0.84%   |
| 5.17.0-0-edge          | 1         | 0.84%   |
| 5.16.12-may            | 1         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 6.72%   |
| 5.15.86 | 3         | 2.52%   |
| 5.15.60 | 3         | 2.52%   |
| 5.15.16 | 3         | 2.52%   |
| 5.10.61 | 3         | 2.52%   |
| 5.4.84  | 2         | 1.68%   |
| 5.4.83  | 2         | 1.68%   |
| 5.17.9  | 2         | 1.68%   |
| 5.15.74 | 2         | 1.68%   |
| 5.15.59 | 2         | 1.68%   |
| 5.15.47 | 2         | 1.68%   |
| 5.15.46 | 2         | 1.68%   |
| 5.15.41 | 2         | 1.68%   |
| 5.15.4  | 2         | 1.68%   |
| 5.15.12 | 2         | 1.68%   |
| 5.10.68 | 2         | 1.68%   |
| 5.10.16 | 2         | 1.68%   |
| 6.1.11  | 1         | 0.84%   |
| 6.0.10  | 1         | 0.84%   |
| 5.8.12  | 1         | 0.84%   |
| 5.8.0   | 1         | 0.84%   |
| 5.7.4   | 1         | 0.84%   |
| 5.6.2   | 1         | 0.84%   |
| 5.4.99  | 1         | 0.84%   |
| 5.4.73  | 1         | 0.84%   |
| 5.4.72  | 1         | 0.84%   |
| 5.4.65  | 1         | 0.84%   |
| 5.4.64  | 1         | 0.84%   |
| 5.4.6   | 1         | 0.84%   |
| 5.4.58  | 1         | 0.84%   |
| 5.4.57  | 1         | 0.84%   |
| 5.4.46  | 1         | 0.84%   |
| 5.4.27  | 1         | 0.84%   |
| 5.4.111 | 1         | 0.84%   |
| 5.4.0   | 1         | 0.84%   |
| 5.19.0  | 1         | 0.84%   |
| 5.18.0  | 1         | 0.84%   |
| 5.17.3  | 1         | 0.84%   |
| 5.17.0  | 1         | 0.84%   |
| 5.16.12 | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 46        | 40.35%  |
| 5.4     | 23        | 20.18%  |
| 5.10    | 23        | 20.18%  |
| 5.17    | 4         | 3.51%   |
| 3.10    | 3         | 2.63%   |
| 5.8     | 2         | 1.75%   |
| 5.14    | 2         | 1.75%   |
| 6.1     | 1         | 0.88%   |
| 6.0     | 1         | 0.88%   |
| 5.7     | 1         | 0.88%   |
| 5.6     | 1         | 0.88%   |
| 5.19    | 1         | 0.88%   |
| 5.18    | 1         | 0.88%   |
| 5.16    | 1         | 0.88%   |
| 5.13    | 1         | 0.88%   |
| 5.12    | 1         | 0.88%   |
| 4.4     | 1         | 0.88%   |
| 4.14    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 91        | 83.49%  |
| i686    | 12        | 11.01%  |
| aarch64 | 3         | 2.75%   |
| armv7l  | 2         | 1.83%   |
| i586    | 1         | 0.92%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 91        | 83.49%  |
| XFCE    | 9         | 8.26%   |
| GNOME   | 4         | 3.67%   |
| sway    | 2         | 1.83%   |
| KDE5    | 1         | 0.92%   |
| KDE     | 1         | 0.92%   |
| i3      | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 61.26%  |
| X11     | 35        | 31.53%  |
| Wayland | 7         | 6.31%   |
| Tty     | 1         | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 89        | 80.91%  |
| LightDM | 16        | 14.55%  |
| GDM     | 2         | 1.82%   |
| XDM     | 1         | 0.91%   |
| SDDM    | 1         | 0.91%   |
| LXDM    | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 68        | 60.71%  |
| Unknown | 34        | 30.36%  |
| en_US   | 7         | 6.25%   |
| ru_RU   | 2         | 1.79%   |
| en_GB   | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 67.89%  |
| EFI  | 35        | 32.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 78.38%  |
| Overlay | 7         | 6.31%   |
| Btrfs   | 7         | 6.31%   |
| Tmpfs   | 4         | 3.6%    |
| F2fs    | 2         | 1.8%    |
| Unknown | 2         | 1.8%    |
| Zfs     | 1         | 0.9%    |
| Ext2    | 1         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 61.95%  |
| GPT     | 30        | 26.55%  |
| MBR     | 13        | 11.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 88.18%  |
| Yes       | 13        | 11.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 92.73%  |
| Yes       | 8         | 7.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 17        | 15.6%   |
| Hewlett-Packard         | 16        | 14.68%  |
| Lenovo                  | 13        | 11.93%  |
| ASUSTek Computer        | 12        | 11.01%  |
| Intel                   | 5         | 4.59%   |
| Acer                    | 5         | 4.59%   |
| Gigabyte Technology     | 4         | 3.67%   |
| Fujitsu                 | 4         | 3.67%   |
| ASRock                  | 4         | 3.67%   |
| Unknown                 | 4         | 3.67%   |
| IBM                     | 3         | 2.75%   |
| Raspberry Pi Foundation | 2         | 1.83%   |
| MSI                     | 2         | 1.83%   |
| Google                  | 2         | 1.83%   |
| Gateway                 | 2         | 1.83%   |
| VIA Technologies        | 1         | 0.92%   |
| Toshiba                 | 1         | 0.92%   |
| Synology                | 1         | 0.92%   |
| Supermicro              | 1         | 0.92%   |
| Sony                    | 1         | 0.92%   |
| Shuttle                 | 1         | 0.92%   |
| Pegatron                | 1         | 0.92%   |
| Olivetti                | 1         | 0.92%   |
| Haier                   | 1         | 0.92%   |
| Fanless Mini PC         | 1         | 0.92%   |
| F5 Networks             | 1         | 0.92%   |
| eMachines               | 1         | 0.92%   |
| Apple                   | 1         | 0.92%   |
| AMI                     | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 3.67%   |
| HP ProLiant DL360 G6                     | 2         | 1.83%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.83%   |
| Dell Precision 3660                      | 2         | 1.83%   |
| ASUS All Series                          | 2         | 1.83%   |
| VIA KM266APro-835                        | 1         | 0.92%   |
| Toshiba Satellite M645                   | 1         | 0.92%   |
| Synology DS1019+                         | 1         | 0.92%   |
| Supermicro X10SLL-F                      | 1         | 0.92%   |
| Sony VGN-UX27GN                          | 1         | 0.92%   |
| Shuttle DS81D                            | 1         | 0.92%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.92%   |
| RPi Raspberry Pi                         | 1         | 0.92%   |
| Pegatron Deepcam                         | 1         | 0.92%   |
| Olivetti Spring Peak                     | 1         | 0.92%   |
| MSI MS-7877                              | 1         | 0.92%   |
| MSI GL72M 7REX                           | 1         | 0.92%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.92%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.92%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.92%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.92%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.92%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.92%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.92%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.92%   |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.92%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.92%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.92%   |
| Lenovo H535 10117                        | 1         | 0.92%   |
| Intel NUC6i7KYB H90766-406               | 1         | 0.92%   |
| Intel Merrifield                         | 1         | 0.92%   |
| Intel DQ67SW                             | 1         | 0.92%   |
| Intel DH61BF AAG81311-101                | 1         | 0.92%   |
| Intel D525MW AAE93082-401                | 1         | 0.92%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 0.92%   |
| IBM 26446AG                              | 1         | 0.92%   |
| IBM 264070A                              | 1         | 0.92%   |
| HP ZBook 15 G5                           | 1         | 0.92%   |
| HP Stream 7 Tablet                       | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 7         | 6.42%   |
| Dell Inspiron       | 7         | 6.42%   |
| Acer Aspire         | 5         | 4.59%   |
| Dell OptiPlex       | 4         | 3.67%   |
| Unknown             | 4         | 3.67%   |
| HP ProLiant         | 3         | 2.75%   |
| HP EliteBook        | 3         | 2.75%   |
| RPi Raspberry       | 2         | 1.83%   |
| Lenovo ThinkCentre  | 2         | 1.83%   |
| HP Compaq           | 2         | 1.83%   |
| Gigabyte Z490I      | 2         | 1.83%   |
| Dell XPS            | 2         | 1.83%   |
| Dell Precision      | 2         | 1.83%   |
| ASUS PRIME          | 2         | 1.83%   |
| ASUS All            | 2         | 1.83%   |
| VIA KM266APro-835   | 1         | 0.92%   |
| Toshiba Satellite   | 1         | 0.92%   |
| Synology DS1019+    | 1         | 0.92%   |
| Supermicro X10SLL-F | 1         | 0.92%   |
| Sony VGN-UX27GN     | 1         | 0.92%   |
| Shuttle DS81D       | 1         | 0.92%   |
| Pegatron Deepcam    | 1         | 0.92%   |
| Olivetti Spring     | 1         | 0.92%   |
| MSI MS-7877         | 1         | 0.92%   |
| MSI GL72M           | 1         | 0.92%   |
| Lenovo Yoga         | 1         | 0.92%   |
| Lenovo V14-ADA      | 1         | 0.92%   |
| Lenovo IdeaPad      | 1         | 0.92%   |
| Lenovo H535         | 1         | 0.92%   |
| Intel NUC6i7KYB     | 1         | 0.92%   |
| Intel Merrifield    | 1         | 0.92%   |
| Intel DQ67SW        | 1         | 0.92%   |
| Intel DH61BF        | 1         | 0.92%   |
| Intel D525MW        | 1         | 0.92%   |
| IBM ThinkPad        | 1         | 0.92%   |
| IBM 26446AG         | 1         | 0.92%   |
| IBM 264070A         | 1         | 0.92%   |
| HP ZBook            | 1         | 0.92%   |
| HP Stream           | 1         | 0.92%   |
| HP ProBook          | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 16        | 14.68%  |
| 2018    | 10        | 9.17%   |
| 2012    | 9         | 8.26%   |
| 2019    | 8         | 7.34%   |
| 2010    | 8         | 7.34%   |
| 2016    | 6         | 5.5%    |
| 2013    | 6         | 5.5%    |
| Unknown | 6         | 5.5%    |
| 2020    | 5         | 4.59%   |
| 2015    | 5         | 4.59%   |
| 2011    | 5         | 4.59%   |
| 2009    | 5         | 4.59%   |
| 2021    | 4         | 3.67%   |
| 2017    | 4         | 3.67%   |
| 2006    | 3         | 2.75%   |
| 2022    | 2         | 1.83%   |
| 2007    | 2         | 1.83%   |
| 2005    | 2         | 1.83%   |
| 2008    | 1         | 0.92%   |
| 2004    | 1         | 0.92%   |
| 1999    | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 55        | 50.46%  |
| Desktop        | 37        | 33.94%  |
| Mini pc        | 5         | 4.59%   |
| Server         | 5         | 4.59%   |
| System on chip | 3         | 2.75%   |
| Tablet         | 2         | 1.83%   |
| Convertible    | 1         | 0.92%   |
| All in one     | 1         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 98.17%  |
| Yes  | 2         | 1.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 26        | 23.01%  |
| 3.01-4.0        | 23        | 20.35%  |
| 16.01-24.0      | 18        | 15.93%  |
| 8.01-16.0       | 12        | 10.62%  |
| 0.51-1.0        | 9         | 7.96%   |
| 32.01-64.0      | 6         | 5.31%   |
| 1.01-2.0        | 6         | 5.31%   |
| 2.01-3.0        | 5         | 4.42%   |
| 0.01-0.5        | 4         | 3.54%   |
| 64.01-256.0     | 3         | 2.65%   |
| More than 256.0 | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 34        | 29.57%  |
| 1.01-2.0  | 24        | 20.87%  |
| 0.51-1.0  | 21        | 18.26%  |
| 2.01-3.0  | 10        | 8.7%    |
| 3.01-4.0  | 9         | 7.83%   |
| 4.01-8.0  | 6         | 5.22%   |
| 8.01-16.0 | 5         | 4.35%   |
| 0         | 3         | 2.61%   |
| Unknown   | 3         | 2.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 64.29%  |
| 2      | 21        | 18.75%  |
| 3      | 8         | 7.14%   |
| 4      | 4         | 3.57%   |
| 14     | 2         | 1.79%   |
| 12     | 1         | 0.89%   |
| 10     | 1         | 0.89%   |
| 7      | 1         | 0.89%   |
| 5      | 1         | 0.89%   |
| 0      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 77.98%  |
| Yes       | 24        | 22.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 85.32%  |
| No        | 16        | 14.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 62.39%  |
| No        | 41        | 37.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 56.88%  |
| Yes       | 47        | 43.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 28        | 25.45%  |
| Russia       | 11        | 10%     |
| Canada       | 10        | 9.09%   |
| UK           | 9         | 8.18%   |
| Germany      | 8         | 7.27%   |
| Sweden       | 4         | 3.64%   |
| Brazil       | 4         | 3.64%   |
| Spain        | 3         | 2.73%   |
| Australia    | 3         | 2.73%   |
| Portugal     | 2         | 1.82%   |
| Poland       | 2         | 1.82%   |
| Norway       | 2         | 1.82%   |
| Italy        | 2         | 1.82%   |
| Guatemala    | 2         | 1.82%   |
| Venezuela    | 1         | 0.91%   |
| Ukraine      | 1         | 0.91%   |
| Switzerland  | 1         | 0.91%   |
| South Korea  | 1         | 0.91%   |
| South Africa | 1         | 0.91%   |
| Slovakia     | 1         | 0.91%   |
| Pakistan     | 1         | 0.91%   |
| Mexico       | 1         | 0.91%   |
| Jamaica      | 1         | 0.91%   |
| Indonesia    | 1         | 0.91%   |
| Hungary      | 1         | 0.91%   |
| Greece       | 1         | 0.91%   |
| France       | 1         | 0.91%   |
| Finland      | 1         | 0.91%   |
| Egypt        | 1         | 0.91%   |
| Denmark      | 1         | 0.91%   |
| Czechia      | 1         | 0.91%   |
| China        | 1         | 0.91%   |
| Austria      | 1         | 0.91%   |
| Argentina    | 1         | 0.91%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 6         | 5.31%   |
| Springfield    | 6         | 5.31%   |
| Manitowoc      | 5         | 4.42%   |
| Vernon         | 3         | 2.65%   |
| Sydney         | 2         | 1.77%   |
| Stratford      | 2         | 1.77%   |
| Moscow         | 2         | 1.77%   |
| Guatemala City | 2         | 1.77%   |
| Gothenburg     | 2         | 1.77%   |
| Fulham         | 2         | 1.77%   |
| As             | 2         | 1.77%   |
| Zurich         | 1         | 0.88%   |
| Vejle          | 1         | 0.88%   |
| Vancouver      | 1         | 0.88%   |
| Tymovskoye     | 1         | 0.88%   |
| Tuusula        | 1         | 0.88%   |
| Turin          | 1         | 0.88%   |
| Topeka         | 1         | 0.88%   |
| Thame          | 1         | 0.88%   |
| Tampa          | 1         | 0.88%   |
| Stockholm      | 1         | 0.88%   |
| Stewartstown   | 1         | 0.88%   |
| Sisteron       | 1         | 0.88%   |
| Semily         | 1         | 0.88%   |
| Seattle        | 1         | 0.88%   |
| Sao Paulo      | 1         | 0.88%   |
| San Mateo      | 1         | 0.88%   |
| Salzburg       | 1         | 0.88%   |
| Saarbrücken   | 1         | 0.88%   |
| Rzeszów       | 1         | 0.88%   |
| Rostock        | 1         | 0.88%   |
| Redwood City   | 1         | 0.88%   |
| Purdys         | 1         | 0.88%   |
| Plymouth       | 1         | 0.88%   |
| Penza          | 1         | 0.88%   |
| Ottawa         | 1         | 0.88%   |
| Oberhausen     | 1         | 0.88%   |
| Oakville       | 1         | 0.88%   |
| Nuremberg      | 1         | 0.88%   |
| Northampton    | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 26     | 12.41%  |
| WDC                 | 17        | 46     | 11.72%  |
| Seagate             | 14        | 40     | 9.66%   |
| Unknown             | 11        | 14     | 7.59%   |
| Hitachi             | 11        | 11     | 7.59%   |
| Toshiba             | 10        | 12     | 6.9%    |
| Kingston            | 8         | 9      | 5.52%   |
| HGST                | 7         | 7      | 4.83%   |
| Crucial             | 7         | 15     | 4.83%   |
| SK hynix            | 5         | 7      | 3.45%   |
| Intel               | 5         | 9      | 3.45%   |
| Sandisk             | 4         | 5      | 2.76%   |
| A-DATA Technology   | 4         | 4      | 2.76%   |
| Transcend           | 2         | 2      | 1.38%   |
| LITEON              | 2         | 2      | 1.38%   |
| Fujitsu             | 2         | 2      | 1.38%   |
| STEC                | 1         | 1      | 0.69%   |
| SPCC                | 1         | 1      | 0.69%   |
| Phison Electronics  | 1         | 1      | 0.69%   |
| NETAPP              | 1         | 1      | 0.69%   |
| Micron Technology   | 1         | 1      | 0.69%   |
| Lexar               | 1         | 1      | 0.69%   |
| KIOXIA              | 1         | 1      | 0.69%   |
| Kingmax             | 1         | 1      | 0.69%   |
| KC600               | 1         | 1      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.69%   |
| Intenso             | 1         | 1      | 0.69%   |
| IBM                 | 1         | 1      | 0.69%   |
| Emtec               | 1         | 1      | 0.69%   |
| Dell                | 1         | 2      | 0.69%   |
| China               | 1         | 1      | 0.69%   |
| Apple               | 1         | 3      | 0.69%   |
| AMD                 | 1         | 1      | 0.69%   |
| Unknown             | 1         | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                              | 3         | 1.84%   |
| WDC WD3000BLFS-60YBU2 304GB                         | 2         | 1.23%   |
| Unknown MMC Card  32GB                              | 2         | 1.23%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.23%   |
| Seagate ST4000VN008-2DR1 4TB                        | 2         | 1.23%   |
| Samsung SSD 960 EVO 500GB                           | 2         | 1.23%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 1.23%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 1.23%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 1.23%   |
| Crucial CT120BX500SSD1 120GB                        | 2         | 1.23%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.23%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.61%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.61%   |
| WDC WDS250G2B0B 250GB SSD                           | 1         | 0.61%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.61%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.61%   |
| WDC WD80EFAX-68LHPN0 8TB                            | 1         | 0.61%   |
| WDC WD800AAJS-00 80GB                               | 1         | 0.61%   |
| WDC WD5003ABYZ-0 500GB                              | 1         | 0.61%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 0.61%   |
| WDC WD3200AAKX-0 320GB                              | 1         | 0.61%   |
| WDC WD20EZRZ-00Z 2TB                                | 1         | 0.61%   |
| WDC WD1600BEVT-2 160GB                              | 1         | 0.61%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1         | 0.61%   |
| WDC WD140EDFZ-11A0VA0 14TB                          | 1         | 0.61%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.61%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 0.61%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 0.61%   |
| Unknown SD64G  64GB                                 | 1         | 0.61%   |
| Unknown SD32G  32GB                                 | 1         | 0.61%   |
| Unknown SD16G  32GB                                 | 1         | 0.61%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 0.61%   |
| Unknown MMC Card  64GB                              | 1         | 0.61%   |
| Unknown MMC Card  4GB                               | 1         | 0.61%   |
| Unknown MMC Card                                    | 1         | 0.61%   |
| Transcend TS128GSSD420I 128GB                       | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 40     | 24.56%  |
| WDC                 | 12        | 39     | 21.05%  |
| Hitachi             | 11        | 11     | 19.3%   |
| Toshiba             | 8         | 9      | 14.04%  |
| HGST                | 7         | 7      | 12.28%  |
| Samsung Electronics | 2         | 4      | 3.51%   |
| Fujitsu             | 2         | 2      | 3.51%   |
| IBM                 | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 9      | 15.38%  |
| Crucial             | 7         | 15     | 13.46%  |
| Samsung Electronics | 6         | 8      | 11.54%  |
| WDC                 | 4         | 5      | 7.69%   |
| A-DATA Technology   | 4         | 4      | 7.69%   |
| SanDisk             | 3         | 4      | 5.77%   |
| Intel               | 3         | 5      | 5.77%   |
| Transcend           | 2         | 2      | 3.85%   |
| SK hynix            | 2         | 3      | 3.85%   |
| LITEON              | 2         | 2      | 3.85%   |
| SPCC                | 1         | 1      | 1.92%   |
| Micron Technology   | 1         | 1      | 1.92%   |
| Lexar               | 1         | 1      | 1.92%   |
| Kingmax             | 1         | 1      | 1.92%   |
| KC600               | 1         | 1      | 1.92%   |
| JMicron Technology  | 1         | 1      | 1.92%   |
| Intenso             | 1         | 1      | 1.92%   |
| Emtec               | 1         | 1      | 1.92%   |
| Dell                | 1         | 2      | 1.92%   |
| China               | 1         | 1      | 1.92%   |
| AMD                 | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 113    | 38.64%  |
| SSD     | 46        | 69     | 34.85%  |
| NVMe    | 23        | 33     | 17.42%  |
| MMC     | 11        | 15     | 8.33%   |
| Unknown | 1         | 2      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 177    | 67.77%  |
| NVMe | 23        | 33     | 19.01%  |
| MMC  | 11        | 15     | 9.09%   |
| SAS  | 5         | 7      | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 110    | 70.41%  |
| 0.51-1.0   | 16        | 22     | 16.33%  |
| 4.01-10.0  | 4         | 20     | 4.08%   |
| 3.01-4.0   | 3         | 14     | 3.06%   |
| 2.01-3.0   | 2         | 2      | 2.04%   |
| 10.01-20.0 | 2         | 10     | 2.04%   |
| 1.01-2.0   | 2         | 4      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 23.89%  |
| 1-20           | 20        | 17.7%   |
| Unknown        | 17        | 15.04%  |
| 251-500        | 10        | 8.85%   |
| 21-50          | 10        | 8.85%   |
| 501-1000       | 9         | 7.96%   |
| 1001-2000      | 7         | 6.19%   |
| More than 3000 | 5         | 4.42%   |
| 2001-3000      | 4         | 3.54%   |
| 51-100         | 4         | 3.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 58.04%  |
| Unknown        | 17        | 15.18%  |
| 21-50          | 8         | 7.14%   |
| 51-100         | 7         | 6.25%   |
| 251-500        | 5         | 4.46%   |
| 501-1000       | 4         | 3.57%   |
| 101-250        | 3         | 2.68%   |
| More than 3000 | 1         | 0.89%   |
| 2001-3000      | 1         | 0.89%   |
| 1001-2000      | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 11.76%  |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 5.88%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 5.88%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 5.88%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 5.88%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 5.88%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 5.88%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 5.88%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 5.88%   |
| Kingmax SSD 120G                               | 1         | 1      | 5.88%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 5.88%   |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 5.88%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 5.88%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 29.41%  |
| WDC                 | 3         | 15     | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Samsung Electronics | 2         | 4      | 11.76%  |
| Seagate             | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Kingmax             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 35.71%  |
| WDC                 | 3         | 15     | 21.43%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 4      | 14.29%  |
| Seagate             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 28     | 82.35%  |
| SSD  | 3         | 3      | 17.65%  |

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
| Works    | 73        | 151    | 60.83%  |
| Detected | 30        | 50     | 25%     |
| Malfunc  | 17        | 31     | 14.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 75        | 60.48%  |
| AMD                          | 13        | 10.48%  |
| Samsung Electronics          | 12        | 9.68%   |
| LSI Logic / Symbios Logic    | 4         | 3.23%   |
| SK hynix                     | 2         | 1.61%   |
| SanDisk                      | 2         | 1.61%   |
| KIOXIA                       | 2         | 1.61%   |
| Hewlett-Packard              | 2         | 1.61%   |
| Adaptec                      | 2         | 1.61%   |
| VIA Technologies             | 1         | 0.81%   |
| Toshiba America Info Systems | 1         | 0.81%   |
| Promise Technology           | 1         | 0.81%   |
| Phison Electronics           | 1         | 0.81%   |
| Nvidia                       | 1         | 0.81%   |
| Micron/Crucial Technology    | 1         | 0.81%   |
| Marvell Technology Group     | 1         | 0.81%   |
| Broadcom / LSI               | 1         | 0.81%   |
| ASMedia Technology           | 1         | 0.81%   |
| ADATA Technology             | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 5.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 4.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 3.68%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.47%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 1.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.47%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 1.47%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2         | 1.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.74%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.74%   |
| SanDisk NVMe Controller                                                        | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.74%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.74%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1         | 0.74%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.74%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.74%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 56.69%  |
| NVMe | 22        | 17.32%  |
| IDE  | 16        | 12.6%   |
| RAID | 13        | 10.24%  |
| SAS  | 4         | 3.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 88        | 80%     |
| AMD     | 17        | 15.45%  |
| ARM     | 4         | 3.64%   |
| Unknown | 1         | 0.91%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 1.82%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 1.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 1.82%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 1.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 1.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 1.82%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 1.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 1.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 1.82%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 1.82%   |
| ARM Processor                          | 2         | 1.82%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 0.91%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 0.91%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 0.91%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 0.91%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 0.91%   |
| Intel Pentium M processor 1.70GHz      | 1         | 0.91%   |
| Intel Pentium M processor 1.60GHz      | 1         | 0.91%   |
| Intel Pentium M processor 1.50GHz      | 1         | 0.91%   |
| Intel Pentium III (Coppermine)         | 1         | 0.91%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 0.91%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1         | 0.91%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 0.91%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 0.91%   |
| Intel Mobile Pentium MMX               | 1         | 0.91%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 0.91%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 0.91%   |
| Intel Core m3-8100Y CPU @ 1.10GHz      | 1         | 0.91%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1         | 0.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 0.91%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 0.91%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.91%   |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 0.91%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz      | 1         | 0.91%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 21        | 19.09%  |
| Intel Celeron      | 11        | 10%     |
| Intel Core i7      | 10        | 9.09%   |
| Other              | 9         | 8.18%   |
| Intel Core i3      | 9         | 8.18%   |
| Intel Atom         | 8         | 7.27%   |
| Intel Xeon         | 6         | 5.45%   |
| Intel Pentium M    | 3         | 2.73%   |
| Intel Pentium      | 3         | 2.73%   |
| Intel Core i9      | 3         | 2.73%   |
| Intel Core 2 Duo   | 3         | 2.73%   |
| AMD Ryzen 7        | 3         | 2.73%   |
| AMD A4             | 2         | 1.82%   |
| Intel Xeon Gold    | 1         | 0.91%   |
| Intel Pentium III  | 1         | 0.91%   |
| Intel Pentium Dual | 1         | 0.91%   |
| Intel Genuine      | 1         | 0.91%   |
| Intel Core Solo    | 1         | 0.91%   |
| Intel Core m3      | 1         | 0.91%   |
| Intel Core 2       | 1         | 0.91%   |
| Intel Celeron M    | 1         | 0.91%   |
| ARM BCM            | 1         | 0.91%   |
| AMD Sempron        | 1         | 0.91%   |
| AMD Ryzen 9        | 1         | 0.91%   |
| AMD Ryzen 5        | 1         | 0.91%   |
| AMD Ryzen 3        | 1         | 0.91%   |
| AMD FX             | 1         | 0.91%   |
| AMD E2             | 1         | 0.91%   |
| AMD E1             | 1         | 0.91%   |
| AMD A8             | 1         | 0.91%   |
| AMD A6             | 1         | 0.91%   |
| AMD A10            | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 40.91%  |
| 4       | 34        | 30.91%  |
| 1       | 13        | 11.82%  |
| 8       | 5         | 4.55%   |
| 12      | 4         | 3.64%   |
| 10      | 2         | 1.82%   |
| 6       | 2         | 1.82%   |
| Unknown | 2         | 1.82%   |
| 32      | 1         | 0.91%   |
| 16      | 1         | 0.91%   |
| 3       | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 103       | 93.64%  |
| 2       | 4         | 3.64%   |
| Unknown | 2         | 1.82%   |
| 0       | 1         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 54        | 49.54%  |
| 2       | 53        | 48.62%  |
| Unknown | 2         | 1.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 59        | 53.15%  |
| 32-bit, 64-bit | 46        | 41.44%  |
| 32-bit         | 5         | 4.5%    |
| 64-bit         | 1         | 0.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 57.02%  |
| 0x306c3    | 6         | 5.26%   |
| 0x306a9    | 5         | 4.39%   |
| 0x30678    | 4         | 3.51%   |
| 0x206c2    | 3         | 2.63%   |
| 0x906ea    | 2         | 1.75%   |
| 0x806eb    | 2         | 1.75%   |
| 0x506c9    | 2         | 1.75%   |
| 0x406c4    | 2         | 1.75%   |
| 0x206a7    | 2         | 1.75%   |
| 0x106e5    | 2         | 1.75%   |
| 0x106ca    | 2         | 1.75%   |
| 0x06006704 | 2         | 1.75%   |
| 0xa0655    | 1         | 0.88%   |
| 0x90672    | 1         | 0.88%   |
| 0x706e5    | 1         | 0.88%   |
| 0x6fd      | 1         | 0.88%   |
| 0x6d8      | 1         | 0.88%   |
| 0x683      | 1         | 0.88%   |
| 0x506e3    | 1         | 0.88%   |
| 0x306d4    | 1         | 0.88%   |
| 0x20655    | 1         | 0.88%   |
| 0x1067a    | 1         | 0.88%   |
| 0x08701021 | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |
| 0x0810100b | 1         | 0.88%   |
| 0x0800820d | 1         | 0.88%   |
| 0x010000b6 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 10%     |
| Haswell          | 10        | 9.09%   |
| Silvermont       | 9         | 8.18%   |
| Unknown          | 8         | 7.27%   |
| IvyBridge        | 7         | 6.36%   |
| Westmere         | 6         | 5.45%   |
| SandyBridge      | 6         | 5.45%   |
| P6               | 6         | 5.45%   |
| Goldmont         | 5         | 4.55%   |
| Penryn           | 4         | 3.64%   |
| Broadwell        | 4         | 3.64%   |
| Bonnell          | 4         | 3.64%   |
| Skylake          | 3         | 2.73%   |
| Excavator        | 3         | 2.73%   |
| Zen+             | 2         | 1.82%   |
| Zen 2            | 2         | 1.82%   |
| Piledriver       | 2         | 1.82%   |
| Nehalem          | 2         | 1.82%   |
| Jaguar           | 2         | 1.82%   |
| IceLake          | 2         | 1.82%   |
| Core             | 2         | 1.82%   |
| CometLake        | 2         | 1.82%   |
| Zen 3            | 1         | 0.91%   |
| Zen              | 1         | 0.91%   |
| Puma             | 1         | 0.91%   |
| K6               | 1         | 0.91%   |
| K10              | 1         | 0.91%   |
| Goldmont plus    | 1         | 0.91%   |
| Bobcat           | 1         | 0.91%   |
| Alderlake Hybrid | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 74        | 64.91%  |
| AMD                        | 23        | 20.18%  |
| Nvidia                     | 9         | 7.89%   |
| Matrox Electronics Systems | 4         | 3.51%   |
| Neomagic                   | 2         | 1.75%   |
| VIA Technologies           | 1         | 0.88%   |
| ASPEED Technology          | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 4.27%   |
| Intel HD Graphics 500                                                                    | 4         | 3.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.56%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.56%   |
| AMD ES1000                                                                               | 3         | 2.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.71%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 1.71%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.71%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.71%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.71%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.85%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.85%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.85%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1         | 0.85%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.85%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 0.85%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 0.85%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 0.85%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.85%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.85%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.85%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.85%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 61        | 55.45%  |
| 1 x AMD         | 19        | 17.27%  |
| Other           | 6         | 5.45%   |
| 2 x Intel       | 5         | 4.55%   |
| 1 x Nvidia      | 4         | 3.64%   |
| 1 x Matrox      | 3         | 2.73%   |
| Intel + Nvidia  | 3         | 2.73%   |
| Intel + AMD     | 3         | 2.73%   |
| 1 x Neomagic    | 2         | 1.82%   |
| 2 x AMD         | 1         | 0.91%   |
| 1 x VIA         | 1         | 0.91%   |
| Nvidia + Matrox | 1         | 0.91%   |
| 1 x ASPEED      | 1         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 92        | 82.14%  |
| Unknown     | 18        | 16.07%  |
| Proprietary | 2         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 86.24%  |
| 0.01-0.5   | 7         | 6.42%   |
| 1.01-2.0   | 3         | 2.75%   |
| 7.01-8.0   | 2         | 1.83%   |
| 3.01-4.0   | 1         | 0.92%   |
| 8.01-16.0  | 1         | 0.92%   |
| 0.51-1.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 12.94%  |
| LG Display              | 9         | 10.59%  |
| Dell                    | 8         | 9.41%   |
| Samsung Electronics     | 7         | 8.24%   |
| Chimei Innolux          | 6         | 7.06%   |
| BOE                     | 6         | 7.06%   |
| Goldstar                | 3         | 3.53%   |
| Chi Mei Optoelectronics | 3         | 3.53%   |
| BenQ                    | 3         | 3.53%   |
| AOC                     | 3         | 3.53%   |
| Acer                    | 3         | 3.53%   |
| LG Philips              | 2         | 2.35%   |
| Lenovo                  | 2         | 2.35%   |
| InfoVision              | 2         | 2.35%   |
| Hewlett-Packard         | 2         | 2.35%   |
| ViewSonic               | 1         | 1.18%   |
| Sony                    | 1         | 1.18%   |
| SKY                     | 1         | 1.18%   |
| Sharp                   | 1         | 1.18%   |
| ONN                     | 1         | 1.18%   |
| Mi                      | 1         | 1.18%   |
| KVM                     | 1         | 1.18%   |
| HannStar                | 1         | 1.18%   |
| Envision                | 1         | 1.18%   |
| Elo Touch               | 1         | 1.18%   |
| EDI                     | 1         | 1.18%   |
| DENON                   | 1         | 1.18%   |
| CTC                     | 1         | 1.18%   |
| CSO                     | 1         | 1.18%   |
| CPT                     | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 3.53%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2         | 2.35%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 2.35%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 1.18%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 1.18%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 1.18%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 1.18%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 1.18%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 1.18%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1         | 1.18%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 1.18%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.18%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 1.18%   |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.18%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 1.18%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.18%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch          | 1         | 1.18%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 509x286mm 23.0-inch      | 1         | 1.18%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.18%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 1.18%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.18%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 1         | 1.18%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch            | 1         | 1.18%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch               | 1         | 1.18%   |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                 | 1         | 1.18%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                      | 1         | 1.18%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.18%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 24        | 28.24%  |
| 1920x1080 (FHD)    | 22        | 25.88%  |
| 1280x800 (WXGA)    | 5         | 5.88%   |
| 1280x1024 (SXGA)   | 5         | 5.88%   |
| 3840x2160 (4K)     | 4         | 4.71%   |
| 2560x1440 (QHD)    | 4         | 4.71%   |
| 1680x1050 (WSXGA+) | 4         | 4.71%   |
| 1024x600           | 3         | 3.53%   |
| 3440x1440          | 2         | 2.35%   |
| 1920x1200 (WUXGA)  | 2         | 2.35%   |
| 1600x900 (HD+)     | 2         | 2.35%   |
| 1024x768 (XGA)     | 2         | 2.35%   |
| 2880x1800          | 1         | 1.18%   |
| 2560x1700          | 1         | 1.18%   |
| 2560x1080          | 1         | 1.18%   |
| 1440x900 (WXGA+)   | 1         | 1.18%   |
| 1360x768           | 1         | 1.18%   |
| 1280x768           | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 20        | 23.53%  |
| 13     | 9         | 10.59%  |
| 14     | 8         | 9.41%   |
| 17     | 7         | 8.24%   |
| 27     | 4         | 4.71%   |
| 23     | 4         | 4.71%   |
| 21     | 4         | 4.71%   |
| 20     | 4         | 4.71%   |
| 11     | 4         | 4.71%   |
| 24     | 3         | 3.53%   |
| 12     | 3         | 3.53%   |
| 10     | 3         | 3.53%   |
| 34     | 2         | 2.35%   |
| 31     | 2         | 2.35%   |
| 19     | 2         | 2.35%   |
| 65     | 1         | 1.18%   |
| 60     | 1         | 1.18%   |
| 40     | 1         | 1.18%   |
| 32     | 1         | 1.18%   |
| 29     | 1         | 1.18%   |
| 25     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 43.53%  |
| 201-300     | 13        | 15.29%  |
| 501-600     | 11        | 12.94%  |
| 401-500     | 8         | 9.41%   |
| 351-400     | 6         | 7.06%   |
| 601-700     | 4         | 4.71%   |
| 701-800     | 3         | 3.53%   |
| 1001-1500   | 2         | 2.35%   |
| 801-900     | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 71.25%  |
| 16/10 | 12        | 15%     |
| 5/4   | 5         | 6.25%   |
| 21/9  | 3         | 3.75%   |
| 4/3   | 2         | 2.5%    |
| 3/2   | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 22.35%  |
| 81-90          | 14        | 16.47%  |
| 201-250        | 10        | 11.76%  |
| 151-200        | 7         | 8.24%   |
| 351-500        | 5         | 5.88%   |
| 301-350        | 5         | 5.88%   |
| 71-80          | 4         | 4.71%   |
| 51-60          | 4         | 4.71%   |
| 41-50          | 3         | 3.53%   |
| 141-150        | 3         | 3.53%   |
| More than 1000 | 2         | 2.35%   |
| 61-70          | 2         | 2.35%   |
| 131-140        | 2         | 2.35%   |
| 121-130        | 2         | 2.35%   |
| 251-300        | 1         | 1.18%   |
| 111-120        | 1         | 1.18%   |
| 501-1000       | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 28        | 34.57%  |
| 51-100        | 25        | 30.86%  |
| 121-160       | 17        | 20.99%  |
| 1-50          | 5         | 6.17%   |
| 161-240       | 4         | 4.94%   |
| More than 240 | 2         | 2.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 65.77%  |
| 0     | 29        | 26.13%  |
| 2     | 8         | 7.21%   |
| 4     | 1         | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 55        | 33.74%  |
| Intel                           | 49        | 30.06%  |
| Qualcomm Atheros                | 19        | 11.66%  |
| Broadcom                        | 17        | 10.43%  |
| Xiaomi                          | 3         | 1.84%   |
| Marvell Technology Group        | 3         | 1.84%   |
| Qualcomm Atheros Communications | 2         | 1.23%   |
| Qualcomm                        | 2         | 1.23%   |
| Broadcom Limited                | 2         | 1.23%   |
| VIA Technologies                | 1         | 0.61%   |
| T & A Mobile Phones             | 1         | 0.61%   |
| Sigma Designs                   | 1         | 0.61%   |
| Nvidia                          | 1         | 0.61%   |
| Microchip Technology            | 1         | 0.61%   |
| Mellanox Technologies           | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| LSI                             | 1         | 0.61%   |
| Google                          | 1         | 0.61%   |
| Dresden Elektronik              | 1         | 0.61%   |
| D-Link System                   | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 16.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.17%   |
| Intel Ethernet Controller I225-V                                  | 4         | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.59%   |
| Intel I210 Gigabit Network Connection                             | 3         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.06%   |
| Intel Wireless-AC 9260                                            | 2         | 1.06%   |
| Intel Wireless 8260                                               | 2         | 1.06%   |
| Intel Wireless 7265                                               | 2         | 1.06%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.06%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.06%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.06%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.06%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.53%   |
| T & A Mobile Phones Unisoc Phone                                  | 1         | 0.53%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                   | 1         | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 46.48%  |
| Qualcomm Atheros                | 16        | 22.54%  |
| Broadcom                        | 9         | 12.68%  |
| Realtek Semiconductor           | 7         | 9.86%   |
| Qualcomm Atheros Communications | 2         | 2.82%   |
| Broadcom Limited                | 2         | 2.82%   |
| MediaTek                        | 1         | 1.41%   |
| Marvell Technology Group        | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 9.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 4.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3         | 4.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 4.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.82%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.82%   |
| Intel Wireless-AC 9260                                                         | 2         | 2.82%   |
| Intel Wireless 8260                                                            | 2         | 2.82%   |
| Intel Wireless 7265                                                            | 2         | 2.82%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 2.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.41%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.41%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.41%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1         | 1.41%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.41%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.41%   |
| Intel Wireless 7260                                                            | 1         | 1.41%   |
| Intel Wireless 3160                                                            | 1         | 1.41%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.41%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.41%   |
| Intel Centrino Wireless-N 105                                                  | 1         | 1.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 1.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.41%   |
| Intel Centrino Wireless-N 100                                                  | 1         | 1.41%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 47.62%  |
| Intel                    | 30        | 28.57%  |
| Broadcom                 | 10        | 9.52%   |
| Xiaomi                   | 3         | 2.86%   |
| Qualcomm Atheros         | 3         | 2.86%   |
| Qualcomm                 | 2         | 1.9%    |
| Marvell Technology Group | 2         | 1.9%    |
| VIA Technologies         | 1         | 0.95%   |
| Nvidia                   | 1         | 0.95%   |
| Microchip Technology     | 1         | 0.95%   |
| Mellanox Technologies    | 1         | 0.95%   |
| D-Link System            | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 28.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 4         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.7%    |
| Intel I210 Gigabit Network Connection                             | 3         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.85%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.85%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.85%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.85%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.93%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.93%   |
| Qualcomm QM215-QRD _SN:E72764DE                                   | 1         | 0.93%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.93%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.93%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.93%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.93%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.93%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 54.12%  |
| WiFi     | 68        | 40%     |
| Modem    | 7         | 4.12%   |
| Unknown  | 3         | 1.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 58.42%  |
| WiFi     | 42        | 41.58%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 53.15%  |
| 1     | 37        | 33.33%  |
| 0     | 8         | 7.21%   |
| 4     | 3         | 2.7%    |
| 5     | 2         | 1.8%    |
| 3     | 2         | 1.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 86.36%  |
| Yes  | 15        | 13.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 41.67%  |
| Qualcomm Atheros Communications | 4         | 8.33%   |
| Cambridge Silicon Radio         | 4         | 8.33%   |
| Broadcom                        | 4         | 8.33%   |
| Lite-On Technology              | 3         | 6.25%   |
| IMC Networks                    | 3         | 6.25%   |
| Realtek Semiconductor           | 2         | 4.17%   |
| MediaTek                        | 1         | 2.08%   |
| Marvell Semiconductor           | 1         | 2.08%   |
| Hewlett-Packard                 | 1         | 2.08%   |
| Foxconn / Hon Hai               | 1         | 2.08%   |
| ASUSTek Computer                | 1         | 2.08%   |
| Apple                           | 1         | 2.08%   |
| Alps Electric                   | 1         | 2.08%   |
| Actions                         | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 14.58%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.25%   |
| Intel AX201 Bluetooth                               | 3         | 6.25%   |
| Realtek Bluetooth Radio                             | 2         | 4.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4.17%   |
| Intel AX200 Bluetooth                               | 2         | 4.17%   |
| IMC Networks Bluetooth Device                       | 2         | 4.17%   |
| MediaTek Wireless_Device                            | 1         | 2.08%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.08%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.08%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.08%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.08%   |
| Broadcom BCM20702A0                                 | 1         | 2.08%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.08%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.08%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.08%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.08%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.08%   |
| Actions general adapter                             | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 73        | 68.22%  |
| AMD                                  | 19        | 17.76%  |
| Nvidia                               | 4         | 3.74%   |
| VIA Technologies                     | 1         | 0.93%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.93%   |
| Texas Instruments                    | 1         | 0.93%   |
| Sennheiser Communications            | 1         | 0.93%   |
| RODE Microphones                     | 1         | 0.93%   |
| Realtek Semiconductor                | 1         | 0.93%   |
| Native Instruments                   | 1         | 0.93%   |
| Logitech                             | 1         | 0.93%   |
| Generalplus Technology               | 1         | 0.93%   |
| Cirrus Logic                         | 1         | 0.93%   |
| C-Media Electronics                  | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 5.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 4.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.94%   |
| AMD FCH Azalia Controller                                                  | 5         | 3.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 3.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.36%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.36%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.36%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 1.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.57%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.57%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 1.57%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.57%   |
| AMD High Definition Audio Controller                                       | 2         | 1.57%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.79%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1         | 0.79%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.79%   |
| Sennheiser Communications Sennheiser USB headset                           | 1         | 0.79%   |
| RODE Microphones RODE NT-USB Mini                                          | 1         | 0.79%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.79%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.79%   |
| Native Instruments Komplete Audio 2                                        | 1         | 0.79%   |
| Logitech G435 Wireless Gaming Headset                                      | 1         | 0.79%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 19        | 18.1%   |
| Unknown             | 17        | 16.19%  |
| Samsung Electronics | 17        | 16.19%  |
| Crucial             | 11        | 10.48%  |
| Micron Technology   | 10        | 9.52%   |
| Elpida              | 9         | 8.57%   |
| Kingston            | 6         | 5.71%   |
| Corsair             | 3         | 2.86%   |
| A-DATA Technology   | 3         | 2.86%   |
| Unknown (ABCD)      | 1         | 0.95%   |
| Transcend           | 1         | 0.95%   |
| Team                | 1         | 0.95%   |
| Ramaxel Technology  | 1         | 0.95%   |
| Qimonda             | 1         | 0.95%   |
| Patriot             | 1         | 0.95%   |
| Nanya Technology    | 1         | 0.95%   |
| Hewlett-Packard     | 1         | 0.95%   |
| Cors                | 1         | 0.95%   |
| Unknown             | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 2.68%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.79%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 1.79%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 1.79%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 1.79%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.89%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.89%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.89%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.89%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.89%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.89%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.89%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.89%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.89%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 0.89%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.89%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 0.89%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.89%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s             | 1         | 0.89%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 50        | 56.18%  |
| DDR4    | 20        | 22.47%  |
| SDRAM   | 4         | 4.49%   |
| LPDDR3  | 4         | 4.49%   |
| DDR     | 4         | 4.49%   |
| LPDDR4  | 3         | 3.37%   |
| DDR2    | 2         | 2.25%   |
| DRAM    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 52.81%  |
| DIMM         | 36        | 40.45%  |
| Row Of Chips | 5         | 5.62%   |
| Unknown      | 1         | 1.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 32        | 32.65%  |
| 8192  | 31        | 31.63%  |
| 2048  | 17        | 17.35%  |
| 1024  | 6         | 6.12%   |
| 512   | 4         | 4.08%   |
| 16384 | 3         | 3.06%   |
| 32768 | 2         | 2.04%   |
| 128   | 2         | 2.04%   |
| 256   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 32.99%  |
| 1333    | 9         | 9.28%   |
| 2400    | 8         | 8.25%   |
| Unknown | 8         | 8.25%   |
| 1334    | 7         | 7.22%   |
| 2667    | 5         | 5.15%   |
| 2133    | 5         | 5.15%   |
| 3200    | 4         | 4.12%   |
| 3600    | 3         | 3.09%   |
| 1867    | 2         | 2.06%   |
| 1866    | 2         | 2.06%   |
| 4267    | 1         | 1.03%   |
| 4199    | 1         | 1.03%   |
| 3800    | 1         | 1.03%   |
| 2200    | 1         | 1.03%   |
| 1800    | 1         | 1.03%   |
| 1400    | 1         | 1.03%   |
| 1200    | 1         | 1.03%   |
| 1067    | 1         | 1.03%   |
| 1066    | 1         | 1.03%   |
| 800     | 1         | 1.03%   |
| 667     | 1         | 1.03%   |
| 533     | 1         | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 12        | 24.49%  |
| Realtek Semiconductor                  | 6         | 12.24%  |
| Microdia                               | 5         | 10.2%   |
| Suyin                                  | 4         | 8.16%   |
| IMC Networks                           | 4         | 8.16%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.12%   |
| Z-Star Microelectronics                | 2         | 4.08%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Quanta                                 | 2         | 4.08%   |
| Acer                                   | 2         | 4.08%   |
| Syntek                                 | 1         | 2.04%   |
| Silicon Motion                         | 1         | 2.04%   |
| Ricoh                                  | 1         | 2.04%   |
| MacroSilicon                           | 1         | 2.04%   |
| Linux Foundation                       | 1         | 2.04%   |
| Lenovo                                 | 1         | 2.04%   |
| Apple                                  | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                | 3         | 6.12%   |
| Realtek Integrated_Webcam_HD                                  | 2         | 4.08%   |
| Realtek Acer 640 x 480 laptop camera                          | 2         | 4.08%   |
| Microdia Laptop_Integrated_Webcam_2M                          | 2         | 4.08%   |
| Chicony Integrated Camera                                     | 2         | 4.08%   |
| Chicony HD WebCam                                             | 2         | 4.08%   |
| Z-Star Vimicro USB2.0 Camera                                  | 1         | 2.04%   |
| Z-Star A4 TECH USB2.0 PC Camera J                             | 1         | 2.04%   |
| Syntek EasyCamera                                             | 1         | 2.04%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 2.04%   |
| Suyin HP TrueVision HD                                        | 1         | 2.04%   |
| Suyin HP High Definition 1MP Webcam                           | 1         | 2.04%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 2.04%   |
| Sunplus HP Universal Camera                                   | 1         | 2.04%   |
| Sunplus HD WebCam                                             | 1         | 2.04%   |
| Silicon Motion NCM-G102                                       | 1         | 2.04%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870]           | 1         | 2.04%   |
| Realtek USB2.0 HD UVC WebCam                                  | 1         | 2.04%   |
| Realtek USB Camera                                            | 1         | 2.04%   |
| Quanta USB2.0 HD UVC WebCam                                   | 1         | 2.04%   |
| Quanta HP TrueVision HD Camera                                | 1         | 2.04%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 2.04%   |
| Microdia Integrated Webcam                                    | 1         | 2.04%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]                 | 1         | 2.04%   |
| Linux Foundation EEM Gadget                                   | 1         | 2.04%   |
| Lenovo Integrated Webcam                                      | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 2.04%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 2.04%   |
| Chicony USB2.0 FHD UVC WebCam                                 | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 2.04%   |
| Chicony HP Webcam [2 MP Macro]                                | 1         | 2.04%   |
| Chicony HP HD Camera                                          | 1         | 2.04%   |
| Chicony CNF9055 Toshiba Webcam                                | 1         | 2.04%   |
| Chicony CNF8243 Webcam                                        | 1         | 2.04%   |
| Chicony 2.0M UVC Webcam / CNF7129                             | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                 | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam              | 1         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                               | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 42.86%  |
| AuthenTec          | 2         | 28.57%  |
| Synaptics          | 1         | 14.29%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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
| 0     | 69        | 61.06%  |
| 1     | 26        | 23.01%  |
| 2     | 13        | 11.5%   |
| 4     | 2         | 1.77%   |
| 3     | 2         | 1.77%   |
| 5     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 26.87%  |
| Communication controller | 9         | 13.43%  |
| Net/wireless             | 7         | 10.45%  |
| Fingerprint reader       | 7         | 10.45%  |
| Modem                    | 6         | 8.96%   |
| Network                  | 3         | 4.48%   |
| Camera                   | 3         | 4.48%   |
| Bluetooth                | 3         | 4.48%   |
| Unassigned class         | 2         | 2.99%   |
| Sound                    | 2         | 2.99%   |
| Multimedia controller    | 2         | 2.99%   |
| Chipcard                 | 2         | 2.99%   |
| Unclassified device      | 1         | 1.49%   |
| Storage                  | 1         | 1.49%   |
| Net/ethernet             | 1         | 1.49%   |


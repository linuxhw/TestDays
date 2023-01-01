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

Total: 128

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Dell          | 04WYPY A04                  | Server      | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Dell          | 04WYPY A04                  | Server      | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 11        | 10.48%  |
| Alpine 3.15.0               | 10        | 9.52%   |
| Alpine 3.16.0               | 9         | 8.57%   |
| Alpine 3.15.0_alpha20210804 | 7         | 6.67%   |
| Alpine 3.17_alpha20220809   | 5         | 4.76%   |
| Alpine 3.14.0               | 5         | 4.76%   |
| Alpine 3.15.4               | 4         | 3.81%   |
| Alpine 3.14.2               | 4         | 3.81%   |
| Alpine 3.13.0_alpha20200917 | 4         | 3.81%   |
| Alpine 3.13.0_alpha20200626 | 4         | 3.81%   |
| Alpine 3.11.2               | 4         | 3.81%   |
| Alpine 3.16.2               | 3         | 2.86%   |
| Alpine 3.16.1               | 3         | 2.86%   |
| Alpine 3.13.1               | 3         | 2.86%   |
| Alpine 3.13.0_alpha20201218 | 3         | 2.86%   |
| Alpine 3.17.0               | 2         | 1.9%    |
| Alpine 3.16.3               | 2         | 1.9%    |
| Alpine 3.15.6               | 2         | 1.9%    |
| Alpine 3.13.5               | 2         | 1.9%    |
| Alpine 3.13.2               | 2         | 1.9%    |
| Alpine 3.12.3               | 2         | 1.9%    |
| Alpine 3.8.4                | 1         | 0.95%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.95%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.95%   |
| Alpine 3.15.2               | 1         | 0.95%   |
| Alpine 3.15.0_rc5           | 1         | 0.95%   |
| Alpine 3.14.3               | 1         | 0.95%   |
| Alpine 3.14.0_alpha20210212 | 1         | 0.95%   |
| Alpine 3.13.6               | 1         | 0.95%   |
| Alpine 3.13.3               | 1         | 0.95%   |
| Alpine 3.13.0_rc2           | 1         | 0.95%   |
| Alpine 3.12.7               | 1         | 0.95%   |
| Alpine 3.12.1               | 1         | 0.95%   |
| Alpine 3.12.0_rc1           | 1         | 0.95%   |
| Alpine 3.11.5               | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 96        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 7.55%   |
| 5.15.60-0-lts          | 3         | 2.83%   |
| 5.15.16-0-lts          | 3         | 2.83%   |
| 5.10.61-0-lts          | 3         | 2.83%   |
| 5.4.84-0-lts           | 2         | 1.89%   |
| 5.4.83-0-lts           | 2         | 1.89%   |
| 5.17.9-0-edge          | 2         | 1.89%   |
| 5.15.74-0-lts          | 2         | 1.89%   |
| 5.15.59-0-lts          | 2         | 1.89%   |
| 5.15.47-0-lts          | 2         | 1.89%   |
| 5.15.46-1-lts          | 2         | 1.89%   |
| 5.15.41-0-lts          | 2         | 1.89%   |
| 5.15.4-0-lts           | 2         | 1.89%   |
| 5.15.12-0-lts          | 2         | 1.89%   |
| 5.10.68-0-lts          | 2         | 1.89%   |
| 5.10.16-0-lts          | 2         | 1.89%   |
| 6.0.10-0-edge          | 1         | 0.94%   |
| 5.8.12-0-edge          | 1         | 0.94%   |
| 5.8.0                  | 1         | 0.94%   |
| 5.7.4                  | 1         | 0.94%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 0.94%   |
| 5.4.99                 | 1         | 0.94%   |
| 5.4.73-0-lts           | 1         | 0.94%   |
| 5.4.72-0-lts           | 1         | 0.94%   |
| 5.4.65-0-lts           | 1         | 0.94%   |
| 5.4.64-0-lts           | 1         | 0.94%   |
| 5.4.6-0-lts            | 1         | 0.94%   |
| 5.4.58-0-lts           | 1         | 0.94%   |
| 5.4.57-0-lts           | 1         | 0.94%   |
| 5.4.46-0-lts           | 1         | 0.94%   |
| 5.4.27-0-lts           | 1         | 0.94%   |
| 5.4.111-0-lts          | 1         | 0.94%   |
| 5.4.0-77-generic       | 1         | 0.94%   |
| 5.19.0-rc8-kukui+      | 1         | 0.94%   |
| 5.18.0-0-asahi         | 1         | 0.94%   |
| 5.17.3-0-edge          | 1         | 0.94%   |
| 5.17.0-0-edge          | 1         | 0.94%   |
| 5.16.12-may            | 1         | 0.94%   |
| 5.16.1-may             | 1         | 0.94%   |
| 5.15.85-0-lts          | 1         | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 7.55%   |
| 5.15.60 | 3         | 2.83%   |
| 5.15.16 | 3         | 2.83%   |
| 5.10.61 | 3         | 2.83%   |
| 5.4.84  | 2         | 1.89%   |
| 5.4.83  | 2         | 1.89%   |
| 5.17.9  | 2         | 1.89%   |
| 5.15.74 | 2         | 1.89%   |
| 5.15.59 | 2         | 1.89%   |
| 5.15.47 | 2         | 1.89%   |
| 5.15.46 | 2         | 1.89%   |
| 5.15.41 | 2         | 1.89%   |
| 5.15.4  | 2         | 1.89%   |
| 5.15.12 | 2         | 1.89%   |
| 5.10.68 | 2         | 1.89%   |
| 5.10.16 | 2         | 1.89%   |
| 6.0.10  | 1         | 0.94%   |
| 5.8.12  | 1         | 0.94%   |
| 5.8.0   | 1         | 0.94%   |
| 5.7.4   | 1         | 0.94%   |
| 5.6.2   | 1         | 0.94%   |
| 5.4.99  | 1         | 0.94%   |
| 5.4.73  | 1         | 0.94%   |
| 5.4.72  | 1         | 0.94%   |
| 5.4.65  | 1         | 0.94%   |
| 5.4.64  | 1         | 0.94%   |
| 5.4.6   | 1         | 0.94%   |
| 5.4.58  | 1         | 0.94%   |
| 5.4.57  | 1         | 0.94%   |
| 5.4.46  | 1         | 0.94%   |
| 5.4.27  | 1         | 0.94%   |
| 5.4.111 | 1         | 0.94%   |
| 5.4.0   | 1         | 0.94%   |
| 5.19.0  | 1         | 0.94%   |
| 5.18.0  | 1         | 0.94%   |
| 5.17.3  | 1         | 0.94%   |
| 5.17.0  | 1         | 0.94%   |
| 5.16.12 | 1         | 0.94%   |
| 5.16.1  | 1         | 0.94%   |
| 5.15.85 | 1         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 34        | 33.66%  |
| 5.4     | 23        | 22.77%  |
| 5.10    | 23        | 22.77%  |
| 5.17    | 4         | 3.96%   |
| 3.10    | 3         | 2.97%   |
| 5.8     | 2         | 1.98%   |
| 5.14    | 2         | 1.98%   |
| 6.0     | 1         | 0.99%   |
| 5.7     | 1         | 0.99%   |
| 5.6     | 1         | 0.99%   |
| 5.19    | 1         | 0.99%   |
| 5.18    | 1         | 0.99%   |
| 5.16    | 1         | 0.99%   |
| 5.13    | 1         | 0.99%   |
| 5.12    | 1         | 0.99%   |
| 4.4     | 1         | 0.99%   |
| 4.14    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 78        | 81.25%  |
| i686    | 12        | 12.5%   |
| aarch64 | 3         | 3.13%   |
| armv7l  | 2         | 2.08%   |
| i586    | 1         | 1.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 83        | 86.46%  |
| XFCE    | 5         | 5.21%   |
| GNOME   | 4         | 4.17%   |
| sway    | 1         | 1.04%   |
| KDE5    | 1         | 1.04%   |
| KDE     | 1         | 1.04%   |
| i3      | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 63.27%  |
| X11     | 29        | 29.59%  |
| Wayland | 6         | 6.12%   |
| Tty     | 1         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 80        | 82.47%  |
| LightDM | 12        | 12.37%  |
| GDM     | 2         | 2.06%   |
| XDM     | 1         | 1.03%   |
| SDDM    | 1         | 1.03%   |
| LXDM    | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 60        | 60.61%  |
| Unknown | 31        | 31.31%  |
| en_US   | 5         | 5.05%   |
| ru_RU   | 2         | 2.02%   |
| en_GB   | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 67        | 69.79%  |
| EFI  | 29        | 30.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 78.57%  |
| Overlay | 6         | 6.12%   |
| Btrfs   | 6         | 6.12%   |
| Tmpfs   | 4         | 4.08%   |
| F2fs    | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| Ext2    | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 60%     |
| GPT     | 27        | 27%     |
| MBR     | 13        | 13%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 87.63%  |
| Yes       | 12        | 12.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 92.78%  |
| Yes       | 7         | 7.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 16        | 16.67%  |
| Dell                    | 16        | 16.67%  |
| ASUSTek Computer        | 11        | 11.46%  |
| Lenovo                  | 9         | 9.38%   |
| Intel                   | 4         | 4.17%   |
| Acer                    | 4         | 4.17%   |
| Unknown                 | 4         | 4.17%   |
| IBM                     | 3         | 3.13%   |
| Gigabyte Technology     | 3         | 3.13%   |
| Fujitsu                 | 3         | 3.13%   |
| ASRock                  | 3         | 3.13%   |
| Raspberry Pi Foundation | 2         | 2.08%   |
| MSI                     | 2         | 2.08%   |
| Gateway                 | 2         | 2.08%   |
| VIA Technologies        | 1         | 1.04%   |
| Toshiba                 | 1         | 1.04%   |
| Synology                | 1         | 1.04%   |
| Supermicro              | 1         | 1.04%   |
| Sony                    | 1         | 1.04%   |
| Shuttle                 | 1         | 1.04%   |
| Pegatron                | 1         | 1.04%   |
| Haier                   | 1         | 1.04%   |
| Google                  | 1         | 1.04%   |
| Fanless Mini PC         | 1         | 1.04%   |
| F5 Networks             | 1         | 1.04%   |
| eMachines               | 1         | 1.04%   |
| Apple                   | 1         | 1.04%   |
| AMI                     | 1         | 1.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 4.17%   |
| HP ProLiant DL360 G6                     | 2         | 2.08%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 2.08%   |
| ASUS All Series                          | 2         | 2.08%   |
| VIA KM266APro-835                        | 1         | 1.04%   |
| Toshiba Satellite M645                   | 1         | 1.04%   |
| Synology DS1019+                         | 1         | 1.04%   |
| Supermicro X10SLL-F                      | 1         | 1.04%   |
| Sony VGN-UX27GN                          | 1         | 1.04%   |
| Shuttle DS81D                            | 1         | 1.04%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 1.04%   |
| RPi Raspberry Pi                         | 1         | 1.04%   |
| Pegatron Deepcam                         | 1         | 1.04%   |
| MSI MS-7877                              | 1         | 1.04%   |
| MSI GL72M 7REX                           | 1         | 1.04%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.04%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.04%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.04%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.04%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.04%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.04%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 1.04%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.04%   |
| Lenovo H535 10117                        | 1         | 1.04%   |
| Intel NUC6i7KYB H90766-406               | 1         | 1.04%   |
| Intel Merrifield                         | 1         | 1.04%   |
| Intel DQ67SW                             | 1         | 1.04%   |
| Intel DH61BF AAG81311-101                | 1         | 1.04%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.04%   |
| IBM 26446AG                              | 1         | 1.04%   |
| IBM 264070A                              | 1         | 1.04%   |
| HP ZBook 15 G5                           | 1         | 1.04%   |
| HP Stream 7 Tablet                       | 1         | 1.04%   |
| HP ProLiant MicroServer Gen8             | 1         | 1.04%   |
| HP ProBook 4310s                         | 1         | 1.04%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.04%   |
| HP Mini 110-3500                         | 1         | 1.04%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.04%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.04%   |
| HP EliteBook 8460p                       | 1         | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 6         | 6.25%   |
| Lenovo ThinkPad     | 5         | 5.21%   |
| Dell OptiPlex       | 4         | 4.17%   |
| Acer Aspire         | 4         | 4.17%   |
| Unknown             | 4         | 4.17%   |
| HP ProLiant         | 3         | 3.13%   |
| HP EliteBook        | 3         | 3.13%   |
| RPi Raspberry       | 2         | 2.08%   |
| HP Compaq           | 2         | 2.08%   |
| Gigabyte Z490I      | 2         | 2.08%   |
| Dell XPS            | 2         | 2.08%   |
| Dell PowerEdge      | 2         | 2.08%   |
| ASUS All            | 2         | 2.08%   |
| VIA KM266APro-835   | 1         | 1.04%   |
| Toshiba Satellite   | 1         | 1.04%   |
| Synology DS1019+    | 1         | 1.04%   |
| Supermicro X10SLL-F | 1         | 1.04%   |
| Sony VGN-UX27GN     | 1         | 1.04%   |
| Shuttle DS81D       | 1         | 1.04%   |
| Pegatron Deepcam    | 1         | 1.04%   |
| MSI MS-7877         | 1         | 1.04%   |
| MSI GL72M           | 1         | 1.04%   |
| Lenovo Yoga         | 1         | 1.04%   |
| Lenovo ThinkCentre  | 1         | 1.04%   |
| Lenovo IdeaPad      | 1         | 1.04%   |
| Lenovo H535         | 1         | 1.04%   |
| Intel NUC6i7KYB     | 1         | 1.04%   |
| Intel Merrifield    | 1         | 1.04%   |
| Intel DQ67SW        | 1         | 1.04%   |
| Intel DH61BF        | 1         | 1.04%   |
| IBM ThinkPad        | 1         | 1.04%   |
| IBM 26446AG         | 1         | 1.04%   |
| IBM 264070A         | 1         | 1.04%   |
| HP ZBook            | 1         | 1.04%   |
| HP Stream           | 1         | 1.04%   |
| HP ProBook          | 1         | 1.04%   |
| HP Presario         | 1         | 1.04%   |
| HP Mini             | 1         | 1.04%   |
| HP Laptop           | 1         | 1.04%   |
| HP ENVY             | 1         | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 15        | 15.63%  |
| 2018    | 8         | 8.33%   |
| 2010    | 8         | 8.33%   |
| 2019    | 7         | 7.29%   |
| 2012    | 7         | 7.29%   |
| Unknown | 6         | 6.25%   |
| 2020    | 5         | 5.21%   |
| 2016    | 5         | 5.21%   |
| 2013    | 5         | 5.21%   |
| 2009    | 5         | 5.21%   |
| 2017    | 4         | 4.17%   |
| 2015    | 4         | 4.17%   |
| 2021    | 3         | 3.13%   |
| 2011    | 3         | 3.13%   |
| 2006    | 3         | 3.13%   |
| 2007    | 2         | 2.08%   |
| 2005    | 2         | 2.08%   |
| 2022    | 1         | 1.04%   |
| 2008    | 1         | 1.04%   |
| 2004    | 1         | 1.04%   |
| 1999    | 1         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 47        | 48.96%  |
| Desktop        | 31        | 32.29%  |
| Server         | 6         | 6.25%   |
| Mini pc        | 5         | 5.21%   |
| System on chip | 3         | 3.13%   |
| Tablet         | 2         | 2.08%   |
| Convertible    | 1         | 1.04%   |
| All in one     | 1         | 1.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 96        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 98.96%  |
| Yes  | 1         | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 21        | 21%     |
| 4.01-8.0        | 20        | 20%     |
| 16.01-24.0      | 15        | 15%     |
| 8.01-16.0       | 12        | 12%     |
| 0.51-1.0        | 9         | 9%      |
| 32.01-64.0      | 6         | 6%      |
| 1.01-2.0        | 6         | 6%      |
| 2.01-3.0        | 4         | 4%      |
| 64.01-256.0     | 3         | 3%      |
| 0.01-0.5        | 3         | 3%      |
| More than 256.0 | 1         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 32        | 31.37%  |
| 1.01-2.0  | 20        | 19.61%  |
| 0.51-1.0  | 17        | 16.67%  |
| 3.01-4.0  | 9         | 8.82%   |
| 2.01-3.0  | 8         | 7.84%   |
| 4.01-8.0  | 6         | 5.88%   |
| 8.01-16.0 | 5         | 4.9%    |
| Unknown   | 3         | 2.94%   |
| 0         | 2         | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 63.64%  |
| 2      | 19        | 19.19%  |
| 3      | 7         | 7.07%   |
| 4      | 4         | 4.04%   |
| 14     | 2         | 2.02%   |
| 10     | 1         | 1.01%   |
| 7      | 1         | 1.01%   |
| 5      | 1         | 1.01%   |
| 0      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 77.08%  |
| Yes       | 22        | 22.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 86.46%  |
| No        | 13        | 13.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 58.33%  |
| No        | 40        | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 61.46%  |
| Yes       | 37        | 38.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 25.77%  |
| Russia       | 9         | 9.28%   |
| UK           | 8         | 8.25%   |
| Germany      | 8         | 8.25%   |
| Canada       | 8         | 8.25%   |
| Sweden       | 4         | 4.12%   |
| Brazil       | 3         | 3.09%   |
| Australia    | 3         | 3.09%   |
| Spain        | 2         | 2.06%   |
| Portugal     | 2         | 2.06%   |
| Poland       | 2         | 2.06%   |
| Norway       | 2         | 2.06%   |
| Guatemala    | 2         | 2.06%   |
| Venezuela    | 1         | 1.03%   |
| Ukraine      | 1         | 1.03%   |
| Switzerland  | 1         | 1.03%   |
| South Korea  | 1         | 1.03%   |
| South Africa | 1         | 1.03%   |
| Slovakia     | 1         | 1.03%   |
| Pakistan     | 1         | 1.03%   |
| Mexico       | 1         | 1.03%   |
| Italy        | 1         | 1.03%   |
| Indonesia    | 1         | 1.03%   |
| Hungary      | 1         | 1.03%   |
| Greece       | 1         | 1.03%   |
| France       | 1         | 1.03%   |
| Egypt        | 1         | 1.03%   |
| Denmark      | 1         | 1.03%   |
| Czechia      | 1         | 1.03%   |
| China        | 1         | 1.03%   |
| Austria      | 1         | 1.03%   |
| Argentina    | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 6         | 6%      |
| Springfield    | 6         | 6%      |
| Manitowoc      | 5         | 5%      |
| Vernon         | 2         | 2%      |
| Sydney         | 2         | 2%      |
| Stratford      | 2         | 2%      |
| Guatemala City | 2         | 2%      |
| Gothenburg     | 2         | 2%      |
| Fulham         | 2         | 2%      |
| As             | 2         | 2%      |
| Zurich         | 1         | 1%      |
| Vejle          | 1         | 1%      |
| Vancouver      | 1         | 1%      |
| Tymovskoye     | 1         | 1%      |
| Topeka         | 1         | 1%      |
| Thame          | 1         | 1%      |
| Tampa          | 1         | 1%      |
| Stockholm      | 1         | 1%      |
| Stewartstown   | 1         | 1%      |
| Sisteron       | 1         | 1%      |
| Semily         | 1         | 1%      |
| Sao Paulo      | 1         | 1%      |
| San Mateo      | 1         | 1%      |
| Salzburg       | 1         | 1%      |
| Saarbrücken   | 1         | 1%      |
| Rzeszów       | 1         | 1%      |
| Rostock        | 1         | 1%      |
| Redwood City   | 1         | 1%      |
| Purdys         | 1         | 1%      |
| Plymouth       | 1         | 1%      |
| Penza          | 1         | 1%      |
| Ottawa         | 1         | 1%      |
| Oberhausen     | 1         | 1%      |
| Oakville       | 1         | 1%      |
| Nuremberg      | 1         | 1%      |
| Milwaukee      | 1         | 1%      |
| Merrill        | 1         | 1%      |
| Mérida        | 1         | 1%      |
| Mankato        | 1         | 1%      |
| Malmo          | 1         | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 24     | 12.7%   |
| WDC                 | 14        | 39     | 11.11%  |
| Seagate             | 13        | 35     | 10.32%  |
| Unknown             | 10        | 12     | 7.94%   |
| Hitachi             | 10        | 10     | 7.94%   |
| Kingston            | 8         | 9      | 6.35%   |
| Toshiba             | 7         | 9      | 5.56%   |
| HGST                | 6         | 6      | 4.76%   |
| Crucial             | 6         | 14     | 4.76%   |
| Intel               | 5         | 9      | 3.97%   |
| SK hynix            | 4         | 6      | 3.17%   |
| A-DATA Technology   | 3         | 3      | 2.38%   |
| Transcend           | 2         | 2      | 1.59%   |
| SanDisk             | 2         | 2      | 1.59%   |
| LITEON              | 2         | 2      | 1.59%   |
| STEC                | 1         | 1      | 0.79%   |
| SPCC                | 1         | 1      | 0.79%   |
| NETAPP              | 1         | 1      | 0.79%   |
| Micron Technology   | 1         | 1      | 0.79%   |
| Lexar               | 1         | 1      | 0.79%   |
| KIOXIA              | 1         | 1      | 0.79%   |
| Kingmax             | 1         | 1      | 0.79%   |
| KC600               | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| Intenso             | 1         | 1      | 0.79%   |
| IBM                 | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Emtec               | 1         | 1      | 0.79%   |
| Dell                | 1         | 2      | 0.79%   |
| China               | 1         | 1      | 0.79%   |
| Apple               | 1         | 3      | 0.79%   |
| AMD                 | 1         | 1      | 0.79%   |
| Unknown             | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  16GB               | 3         | 2.17%   |
| WDC WD3000BLFS-60YBU2 304GB          | 2         | 1.45%   |
| Seagate ST4000VN008-2DR1 4TB         | 2         | 1.45%   |
| Samsung SSD 960 EVO 500GB            | 2         | 1.45%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 1.45%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 1.45%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.45%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 1.45%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.72%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.72%   |
| WDC WD80EMAZ-00WJTA0 8TB             | 1         | 0.72%   |
| WDC WD80EFAX-68LHPN0 8TB             | 1         | 0.72%   |
| WDC WD800AAJS-00 80GB                | 1         | 0.72%   |
| WDC WD5003ABYZ-0 500GB               | 1         | 0.72%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 0.72%   |
| WDC WD3200AAKX-0 320GB               | 1         | 0.72%   |
| WDC WD20EZRZ-00Z 2TB                 | 1         | 0.72%   |
| WDC WD1600BEVT-2 160GB               | 1         | 0.72%   |
| WDC WD140EDFZ-11A0VA0 14TB           | 1         | 0.72%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.72%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 0.72%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 0.72%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB | 1         | 0.72%   |
| Unknown SD64G  64GB                  | 1         | 0.72%   |
| Unknown SD32G  32GB                  | 1         | 0.72%   |
| Unknown SD16G  32GB                  | 1         | 0.72%   |
| Unknown NVMe SSD Drive 1024GB        | 1         | 0.72%   |
| Unknown MMC Card  4GB                | 1         | 0.72%   |
| Unknown MMC Card  32GB               | 1         | 0.72%   |
| Unknown MMC Card                     | 1         | 0.72%   |
| Transcend TS128GSSD420I 128GB        | 1         | 0.72%   |
| Transcend SSD 1GB                    | 1         | 0.72%   |
| Toshiba NVMe SSD Drive 256GB         | 1         | 0.72%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.72%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.72%   |
| Toshiba MQ01ABD1 1TB                 | 1         | 0.72%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.72%   |
| Toshiba MK4009GAL 40GB               | 1         | 0.72%   |
| Toshiba MK3252GS 320GB               | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 35     | 26.53%  |
| WDC                 | 11        | 35     | 22.45%  |
| Hitachi             | 10        | 10     | 20.41%  |
| HGST                | 6         | 6      | 12.24%  |
| Toshiba             | 5         | 6      | 10.2%   |
| Samsung Electronics | 2         | 4      | 4.08%   |
| IBM                 | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 9      | 17.02%  |
| Samsung Electronics | 6         | 8      | 12.77%  |
| Crucial             | 6         | 14     | 12.77%  |
| Intel               | 3         | 5      | 6.38%   |
| A-DATA Technology   | 3         | 3      | 6.38%   |
| WDC                 | 2         | 2      | 4.26%   |
| Transcend           | 2         | 2      | 4.26%   |
| SK hynix            | 2         | 3      | 4.26%   |
| SanDisk             | 2         | 2      | 4.26%   |
| LITEON              | 2         | 2      | 4.26%   |
| SPCC                | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| Lexar               | 1         | 1      | 2.13%   |
| Kingmax             | 1         | 1      | 2.13%   |
| KC600               | 1         | 1      | 2.13%   |
| JMicron Technology  | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Emtec               | 1         | 1      | 2.13%   |
| Dell                | 1         | 2      | 2.13%   |
| China               | 1         | 1      | 2.13%   |
| AMD                 | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 45        | 98     | 38.46%  |
| SSD     | 42        | 62     | 35.9%   |
| NVMe    | 19        | 28     | 16.24%  |
| MMC     | 10        | 13     | 8.55%   |
| Unknown | 1         | 2      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 155    | 68.22%  |
| NVMe | 19        | 28     | 17.76%  |
| MMC  | 10        | 13     | 9.35%   |
| SAS  | 5         | 7      | 4.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 100    | 72.94%  |
| 0.51-1.0   | 14        | 19     | 16.47%  |
| 3.01-4.0   | 3         | 14     | 3.53%   |
| 4.01-10.0  | 3         | 19     | 3.53%   |
| 1.01-2.0   | 2         | 4      | 2.35%   |
| 10.01-20.0 | 1         | 4      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 24%     |
| 1-20           | 17        | 17%     |
| Unknown        | 15        | 15%     |
| 21-50          | 10        | 10%     |
| 251-500        | 9         | 9%      |
| 501-1000       | 9         | 9%      |
| 1001-2000      | 5         | 5%      |
| 2001-3000      | 4         | 4%      |
| 51-100         | 4         | 4%      |
| More than 3000 | 3         | 3%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 58.59%  |
| Unknown   | 15        | 15.15%  |
| 21-50     | 7         | 7.07%   |
| 51-100    | 7         | 7.07%   |
| 251-500   | 4         | 4.04%   |
| 101-250   | 3         | 3.03%   |
| 501-1000  | 3         | 3.03%   |
| 2001-3000 | 1         | 1.01%   |
| 1001-2000 | 1         | 1.01%   |

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
| Works    | 65        | 139    | 60.75%  |
| Detected | 25        | 33     | 23.36%  |
| Malfunc  | 17        | 31     | 15.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 68        | 62.96%  |
| Samsung Electronics          | 10        | 9.26%   |
| AMD                          | 10        | 9.26%   |
| LSI Logic / Symbios Logic    | 3         | 2.78%   |
| KIOXIA                       | 2         | 1.85%   |
| Hewlett-Packard              | 2         | 1.85%   |
| Adaptec                      | 2         | 1.85%   |
| VIA Technologies             | 1         | 0.93%   |
| Toshiba America Info Systems | 1         | 0.93%   |
| SK hynix                     | 1         | 0.93%   |
| SanDisk                      | 1         | 0.93%   |
| Promise Technology           | 1         | 0.93%   |
| Nvidia                       | 1         | 0.93%   |
| Micron/Crucial Technology    | 1         | 0.93%   |
| Marvell Technology Group     | 1         | 0.93%   |
| Broadcom / LSI               | 1         | 0.93%   |
| ASMedia Technology           | 1         | 0.93%   |
| ADATA Technology             | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 6.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 5.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 5.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 3.36%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 3         | 2.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 1.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.68%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.68%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2         | 1.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.84%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.84%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.84%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1         | 0.84%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.84%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.84%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.84%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.84%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 56.25%  |
| NVMe | 18        | 16.07%  |
| IDE  | 15        | 13.39%  |
| RAID | 13        | 11.61%  |
| SAS  | 3         | 2.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 79        | 81.44%  |
| AMD     | 13        | 13.4%   |
| ARM     | 4         | 4.12%   |
| Unknown | 1         | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 2.06%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 2.06%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 2.06%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 2.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 2.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 2.06%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 2.06%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 2.06%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 2.06%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 2.06%   |
| ARM Processor                          | 2         | 2.06%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 1.03%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 1.03%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 1.03%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 1.03%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 1.03%   |
| Intel Pentium M processor 1.70GHz      | 1         | 1.03%   |
| Intel Pentium M processor 1.60GHz      | 1         | 1.03%   |
| Intel Pentium M processor 1.50GHz      | 1         | 1.03%   |
| Intel Pentium III (Coppermine)         | 1         | 1.03%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 1.03%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 1.03%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 1.03%   |
| Intel Mobile Pentium MMX               | 1         | 1.03%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 1.03%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 1.03%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 1.03%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 1.03%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.03%   |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 1.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.03%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz      | 1         | 1.03%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.03%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz      | 1         | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 18        | 18.56%  |
| Intel Celeron      | 11        | 11.34%  |
| Other              | 9         | 9.28%   |
| Intel Core i7      | 8         | 8.25%   |
| Intel Core i3      | 8         | 8.25%   |
| Intel Atom         | 7         | 7.22%   |
| Intel Xeon         | 6         | 6.19%   |
| Intel Pentium M    | 3         | 3.09%   |
| Intel Core i9      | 3         | 3.09%   |
| Intel Core 2 Duo   | 3         | 3.09%   |
| Intel Pentium      | 2         | 2.06%   |
| AMD A4             | 2         | 2.06%   |
| Intel Xeon Gold    | 1         | 1.03%   |
| Intel Pentium III  | 1         | 1.03%   |
| Intel Pentium Dual | 1         | 1.03%   |
| Intel Genuine      | 1         | 1.03%   |
| Intel Core Solo    | 1         | 1.03%   |
| Intel Core 2       | 1         | 1.03%   |
| Intel Celeron M    | 1         | 1.03%   |
| ARM BCM            | 1         | 1.03%   |
| AMD Sempron        | 1         | 1.03%   |
| AMD Ryzen 9        | 1         | 1.03%   |
| AMD Ryzen 7        | 1         | 1.03%   |
| AMD Ryzen 5        | 1         | 1.03%   |
| AMD FX             | 1         | 1.03%   |
| AMD E1             | 1         | 1.03%   |
| AMD A8             | 1         | 1.03%   |
| AMD A6             | 1         | 1.03%   |
| AMD A10            | 1         | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 37        | 38.14%  |
| 4       | 32        | 32.99%  |
| 1       | 12        | 12.37%  |
| 12      | 4         | 4.12%   |
| 8       | 3         | 3.09%   |
| 10      | 2         | 2.06%   |
| 6       | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |
| 32      | 1         | 1.03%   |
| 16      | 1         | 1.03%   |
| 3       | 1         | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 91        | 93.81%  |
| 2       | 4         | 4.12%   |
| Unknown | 2         | 2.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 50        | 52.08%  |
| 2       | 44        | 45.83%  |
| Unknown | 2         | 2.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 50        | 51.02%  |
| 32-bit, 64-bit | 42        | 42.86%  |
| 32-bit         | 5         | 5.1%    |
| 64-bit         | 1         | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 56.44%  |
| 0x306c3    | 5         | 4.95%   |
| 0x306a9    | 4         | 3.96%   |
| 0x30678    | 4         | 3.96%   |
| 0x206c2    | 3         | 2.97%   |
| 0x906ea    | 2         | 1.98%   |
| 0x506c9    | 2         | 1.98%   |
| 0x406c4    | 2         | 1.98%   |
| 0x206a7    | 2         | 1.98%   |
| 0x106e5    | 2         | 1.98%   |
| 0x106ca    | 2         | 1.98%   |
| 0x06006704 | 2         | 1.98%   |
| 0xa0655    | 1         | 0.99%   |
| 0x90672    | 1         | 0.99%   |
| 0x806eb    | 1         | 0.99%   |
| 0x706e5    | 1         | 0.99%   |
| 0x6fd      | 1         | 0.99%   |
| 0x6d8      | 1         | 0.99%   |
| 0x683      | 1         | 0.99%   |
| 0x506e3    | 1         | 0.99%   |
| 0x306d4    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x1067a    | 1         | 0.99%   |
| 0x08701021 | 1         | 0.99%   |
| 0x0810100b | 1         | 0.99%   |
| 0x010000b6 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 9         | 9.28%   |
| Haswell          | 9         | 9.28%   |
| KabyLake         | 8         | 8.25%   |
| Unknown          | 8         | 8.25%   |
| Westmere         | 6         | 6.19%   |
| P6               | 6         | 6.19%   |
| IvyBridge        | 6         | 6.19%   |
| SandyBridge      | 5         | 5.15%   |
| Penryn           | 4         | 4.12%   |
| Goldmont         | 4         | 4.12%   |
| Skylake          | 3         | 3.09%   |
| Excavator        | 3         | 3.09%   |
| Broadwell        | 3         | 3.09%   |
| Bonnell          | 3         | 3.09%   |
| Zen 2            | 2         | 2.06%   |
| Piledriver       | 2         | 2.06%   |
| Nehalem          | 2         | 2.06%   |
| Jaguar           | 2         | 2.06%   |
| IceLake          | 2         | 2.06%   |
| Core             | 2         | 2.06%   |
| CometLake        | 2         | 2.06%   |
| Zen              | 1         | 1.03%   |
| Puma             | 1         | 1.03%   |
| K6               | 1         | 1.03%   |
| K10              | 1         | 1.03%   |
| Goldmont plus    | 1         | 1.03%   |
| Alderlake Hybrid | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 64        | 64.65%  |
| AMD                        | 20        | 20.2%   |
| Nvidia                     | 7         | 7.07%   |
| Matrox Electronics Systems | 4         | 4.04%   |
| Neomagic                   | 2         | 2.02%   |
| VIA Technologies           | 1         | 1.01%   |
| ASPEED Technology          | 1         | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 6.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 3.92%   |
| Intel HD Graphics 500                                                                    | 4         | 3.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.94%   |
| AMD ES1000                                                                               | 3         | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.96%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 1.96%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.96%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.96%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.96%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.96%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.96%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.98%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.98%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.98%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1         | 0.98%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.98%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 0.98%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 0.98%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 0.98%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.98%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.98%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.98%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.98%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.98%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 52        | 53.61%  |
| 1 x AMD         | 17        | 17.53%  |
| Other           | 6         | 6.19%   |
| 2 x Intel       | 5         | 5.15%   |
| 1 x Nvidia      | 3         | 3.09%   |
| 1 x Matrox      | 3         | 3.09%   |
| Intel + Nvidia  | 3         | 3.09%   |
| 1 x Neomagic    | 2         | 2.06%   |
| Intel + AMD     | 2         | 2.06%   |
| 2 x AMD         | 1         | 1.03%   |
| 1 x VIA         | 1         | 1.03%   |
| Nvidia + Matrox | 1         | 1.03%   |
| 1 x ASPEED      | 1         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 80        | 80.81%  |
| Unknown     | 17        | 17.17%  |
| Proprietary | 2         | 2.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 86.46%  |
| 0.01-0.5   | 7         | 7.29%   |
| 7.01-8.0   | 2         | 2.08%   |
| 1.01-2.0   | 2         | 2.08%   |
| 3.01-4.0   | 1         | 1.04%   |
| 0.51-1.0   | 1         | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 11.84%  |
| LG Display              | 8         | 10.53%  |
| Samsung Electronics     | 7         | 9.21%   |
| Dell                    | 7         | 9.21%   |
| Chimei Innolux          | 6         | 7.89%   |
| BOE                     | 4         | 5.26%   |
| Chi Mei Optoelectronics | 3         | 3.95%   |
| BenQ                    | 3         | 3.95%   |
| AOC                     | 3         | 3.95%   |
| Acer                    | 3         | 3.95%   |
| LG Philips              | 2         | 2.63%   |
| Hewlett-Packard         | 2         | 2.63%   |
| Goldstar                | 2         | 2.63%   |
| ViewSonic               | 1         | 1.32%   |
| Sony                    | 1         | 1.32%   |
| SKY                     | 1         | 1.32%   |
| Sharp                   | 1         | 1.32%   |
| ONN                     | 1         | 1.32%   |
| Mi                      | 1         | 1.32%   |
| Lenovo                  | 1         | 1.32%   |
| KVM                     | 1         | 1.32%   |
| InfoVision              | 1         | 1.32%   |
| HannStar                | 1         | 1.32%   |
| Envision                | 1         | 1.32%   |
| Elo Touch               | 1         | 1.32%   |
| EDI                     | 1         | 1.32%   |
| DENON                   | 1         | 1.32%   |
| CTC                     | 1         | 1.32%   |
| CSO                     | 1         | 1.32%   |
| CPT                     | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 3.9%    |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2         | 2.6%    |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 1.3%    |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 1.3%    |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 1.3%    |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 1.3%    |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.3%    |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1         | 1.3%    |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 1.3%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.3%    |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 1.3%    |
| KVM LCD Monitor 19" 1 9" KVM4308 1280x1024 338x270mm 17.0-inch        | 1         | 1.3%    |
| InfoVision LCD Monitor IVO0489 1366x768 344x193mm 15.5-inch           | 1         | 1.3%    |
| Hewlett-Packard VH240a HPN3499 1920x1080 530x300mm 24.0-inch          | 1         | 1.3%    |
| Hewlett-Packard All-in-One HWP421A 1920x1080 509x286mm 23.0-inch      | 1         | 1.3%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 1         | 1.3%    |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 1.3%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.3%    |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch            | 1         | 1.3%    |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch               | 1         | 1.3%    |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                 | 1         | 1.3%    |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                      | 1         | 1.3%    |
| Dell U2518D DEL413A 2560x1440 550x310mm 24.9-inch                     | 1         | 1.3%    |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                     | 1         | 1.3%    |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1         | 1.3%    |
| Dell E151FPb DELA005 1024x768 310x230mm 15.2-inch                     | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 20        | 26.32%  |
| 1920x1080 (FHD)    | 19        | 25%     |
| 1280x800 (WXGA)    | 5         | 6.58%   |
| 1280x1024 (SXGA)   | 5         | 6.58%   |
| 1680x1050 (WSXGA+) | 4         | 5.26%   |
| 3840x2160 (4K)     | 3         | 3.95%   |
| 2560x1440 (QHD)    | 3         | 3.95%   |
| 1024x600           | 3         | 3.95%   |
| 3440x1440          | 2         | 2.63%   |
| 1920x1200 (WUXGA)  | 2         | 2.63%   |
| 1600x900 (HD+)     | 2         | 2.63%   |
| 1024x768 (XGA)     | 2         | 2.63%   |
| 2880x1800          | 1         | 1.32%   |
| 2560x1700          | 1         | 1.32%   |
| 2560x1080          | 1         | 1.32%   |
| 1440x900 (WXGA+)   | 1         | 1.32%   |
| 1360x768           | 1         | 1.32%   |
| 1280x768           | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 17        | 22.08%  |
| 13     | 9         | 11.69%  |
| 17     | 7         | 9.09%   |
| 14     | 6         | 7.79%   |
| 23     | 4         | 5.19%   |
| 21     | 4         | 5.19%   |
| 20     | 4         | 5.19%   |
| 27     | 3         | 3.9%    |
| 24     | 3         | 3.9%    |
| 12     | 3         | 3.9%    |
| 10     | 3         | 3.9%    |
| 34     | 2         | 2.6%    |
| 19     | 2         | 2.6%    |
| 11     | 2         | 2.6%    |
| 65     | 1         | 1.3%    |
| 60     | 1         | 1.3%    |
| 54     | 1         | 1.3%    |
| 40     | 1         | 1.3%    |
| 32     | 1         | 1.3%    |
| 31     | 1         | 1.3%    |
| 29     | 1         | 1.3%    |
| 25     | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 41.56%  |
| 201-300     | 11        | 14.29%  |
| 501-600     | 10        | 12.99%  |
| 401-500     | 8         | 10.39%  |
| 351-400     | 6         | 7.79%   |
| 701-800     | 3         | 3.9%    |
| 601-700     | 3         | 3.9%    |
| 1001-1500   | 3         | 3.9%    |
| 801-900     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 67.61%  |
| 16/10 | 12        | 16.9%   |
| 5/4   | 5         | 7.04%   |
| 21/9  | 3         | 4.23%   |
| 4/3   | 2         | 2.82%   |
| 3/2   | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 20.78%  |
| 81-90          | 12        | 15.58%  |
| 201-250        | 10        | 12.99%  |
| 151-200        | 7         | 9.09%   |
| 71-80          | 4         | 5.19%   |
| 351-500        | 4         | 5.19%   |
| 301-350        | 4         | 5.19%   |
| More than 1000 | 3         | 3.9%    |
| 41-50          | 3         | 3.9%    |
| 141-150        | 3         | 3.9%    |
| 61-70          | 2         | 2.6%    |
| 51-60          | 2         | 2.6%    |
| 131-140        | 2         | 2.6%    |
| 121-130        | 2         | 2.6%    |
| 251-300        | 1         | 1.3%    |
| 111-120        | 1         | 1.3%    |
| 501-1000       | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 25        | 34.25%  |
| 51-100        | 25        | 34.25%  |
| 121-160       | 11        | 15.07%  |
| 1-50          | 6         | 8.22%   |
| 161-240       | 4         | 5.48%   |
| More than 240 | 2         | 2.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 62        | 63.27%  |
| 0     | 27        | 27.55%  |
| 2     | 8         | 8.16%   |
| 4     | 1         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 48        | 33.8%   |
| Intel                           | 39        | 27.46%  |
| Qualcomm Atheros                | 18        | 12.68%  |
| Broadcom                        | 17        | 11.97%  |
| Xiaomi                          | 3         | 2.11%   |
| Marvell Technology Group        | 3         | 2.11%   |
| Qualcomm Atheros Communications | 2         | 1.41%   |
| Qualcomm                        | 2         | 1.41%   |
| VIA Technologies                | 1         | 0.7%    |
| T & A Mobile Phones             | 1         | 0.7%    |
| Sigma Designs                   | 1         | 0.7%    |
| Nvidia                          | 1         | 0.7%    |
| Microchip Technology            | 1         | 0.7%    |
| Mellanox Technologies           | 1         | 0.7%    |
| LSI                             | 1         | 0.7%    |
| Dresden Elektronik              | 1         | 0.7%    |
| D-Link System                   | 1         | 0.7%    |
| Broadcom Limited                | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 26        | 15.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 4.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 1.82%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.82%   |
| Intel Ethernet Controller I225-V                                               | 3         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.21%   |
| Intel Wireless 8260                                                            | 2         | 1.21%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.21%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 1.21%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.21%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 1.21%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.61%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.61%   |
| T & A Mobile Phones A509DL                                                     | 1         | 0.61%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                | 1         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.61%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.61%   |
| Qualcomm Nokia 5.4                                                             | 1         | 0.61%   |
| Qualcomm MegaFon M150-4                                                        | 1         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.61%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.61%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 43.1%   |
| Qualcomm Atheros                | 15        | 25.86%  |
| Broadcom                        | 9         | 15.52%  |
| Realtek Semiconductor           | 5         | 8.62%   |
| Qualcomm Atheros Communications | 2         | 3.45%   |
| Marvell Technology Group        | 1         | 1.72%   |
| Broadcom Limited                | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 12.07%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 5.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 5.17%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 3.45%   |
| Intel Wireless 8260                                                            | 2         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 3.45%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.72%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.72%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.72%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.72%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.72%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.72%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.72%   |
| Intel Wireless 7265                                                            | 1         | 1.72%   |
| Intel Wireless 7260                                                            | 1         | 1.72%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.72%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.72%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 1.72%   |
| Broadcom BRCM4378 Wireless Network Adapter                                     | 1         | 1.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 1.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1         | 1.72%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 1         | 1.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 1.72%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 47.37%  |
| Intel                    | 25        | 26.32%  |
| Broadcom                 | 10        | 10.53%  |
| Xiaomi                   | 3         | 3.16%   |
| Qualcomm Atheros         | 3         | 3.16%   |
| Qualcomm                 | 2         | 2.11%   |
| Marvell Technology Group | 2         | 2.11%   |
| VIA Technologies         | 1         | 1.05%   |
| Nvidia                   | 1         | 1.05%   |
| Microchip Technology     | 1         | 1.05%   |
| Mellanox Technologies    | 1         | 1.05%   |
| D-Link System            | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 26.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 9.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.08%   |
| Intel I210 Gigabit Network Connection                             | 3         | 3.06%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.04%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 2.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.02%   |
| Qualcomm Nokia 5.4                                                | 1         | 1.02%   |
| Qualcomm MegaFon M150-4                                           | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.02%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.02%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 1.02%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.02%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.02%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.02%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.02%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1         | 1.02%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.02%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 1.02%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 82        | 55.78%  |
| WiFi     | 56        | 38.1%   |
| Modem    | 6         | 4.08%   |
| Unknown  | 3         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 60.23%  |
| WiFi     | 35        | 39.77%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 51.02%  |
| 1     | 33        | 33.67%  |
| 0     | 8         | 8.16%   |
| 4     | 3         | 3.06%   |
| 5     | 2         | 2.04%   |
| 3     | 2         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 86.6%   |
| Yes  | 13        | 13.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 40.54%  |
| Qualcomm Atheros Communications | 4         | 10.81%  |
| Lite-On Technology              | 3         | 8.11%   |
| IMC Networks                    | 3         | 8.11%   |
| Broadcom                        | 3         | 8.11%   |
| Cambridge Silicon Radio         | 2         | 5.41%   |
| Realtek Semiconductor           | 1         | 2.7%    |
| Marvell Semiconductor           | 1         | 2.7%    |
| Hewlett-Packard                 | 1         | 2.7%    |
| Foxconn / Hon Hai               | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |
| Apple                           | 1         | 2.7%    |
| Alps Electric                   | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 13.51%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 10.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.11%   |
| Intel AX201 Bluetooth                               | 3         | 8.11%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.41%   |
| Intel AX200 Bluetooth                               | 2         | 5.41%   |
| IMC Networks Bluetooth Device                       | 2         | 5.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.41%   |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.7%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.7%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.7%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.7%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.7%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.7%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 64        | 70.33%  |
| AMD                                  | 15        | 16.48%  |
| Nvidia                               | 2         | 2.2%    |
| VIA Technologies                     | 1         | 1.1%    |
| Thesycon Systemsoftware & Consulting | 1         | 1.1%    |
| Texas Instruments                    | 1         | 1.1%    |
| Sennheiser Communications            | 1         | 1.1%    |
| RODE Microphones                     | 1         | 1.1%    |
| Realtek Semiconductor                | 1         | 1.1%    |
| Native Instruments                   | 1         | 1.1%    |
| Logitech                             | 1         | 1.1%    |
| Cirrus Logic                         | 1         | 1.1%    |
| C-Media Electronics                  | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 5.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 3.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.74%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.87%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.87%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.87%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.87%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 1.87%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.87%   |
| AMD High Definition Audio Controller                                       | 2         | 1.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.87%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.93%   |
| Thesycon Systemsoftware & Consulting MX5                                   | 1         | 0.93%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.93%   |
| Sennheiser Communications Sennheiser USB headset                           | 1         | 0.93%   |
| RODE Microphones RODE NT-USB Mini                                          | 1         | 0.93%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.93%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.93%   |
| Native Instruments Komplete Audio 2                                        | 1         | 0.93%   |
| Logitech G435 Wireless Gaming Headset                                      | 1         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.93%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.93%   |
| Intel Multimedia audio controller                                          | 1         | 0.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 16        | 17.39%  |
| SK hynix            | 16        | 17.39%  |
| Samsung Electronics | 15        | 16.3%   |
| Micron Technology   | 9         | 9.78%   |
| Crucial             | 9         | 9.78%   |
| Elpida              | 8         | 8.7%    |
| Kingston            | 6         | 6.52%   |
| Corsair             | 3         | 3.26%   |
| A-DATA Technology   | 3         | 3.26%   |
| Unknown (ABCD)      | 1         | 1.09%   |
| Transcend           | 1         | 1.09%   |
| Qimonda             | 1         | 1.09%   |
| Patriot             | 1         | 1.09%   |
| Nanya Technology    | 1         | 1.09%   |
| Hewlett-Packard     | 1         | 1.09%   |
| Cors                | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.02%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 2.02%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.02%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 2.02%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 2.02%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.01%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.01%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.01%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.01%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.01%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.01%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 1.01%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.01%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.01%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 1.01%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.01%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 1.01%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 1         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.01%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s             | 1         | 1.01%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.01%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.01%   |
| SK hynix RAM H5TC4G63AFR-PBA 1GB SODIMM DDR3 1600MT/s            | 1         | 1.01%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.01%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 45        | 56.25%  |
| DDR4    | 17        | 21.25%  |
| SDRAM   | 4         | 5%      |
| DDR     | 4         | 5%      |
| LPDDR4  | 3         | 3.75%   |
| LPDDR3  | 3         | 3.75%   |
| DDR2    | 2         | 2.5%    |
| DRAM    | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 51.9%   |
| DIMM         | 34        | 43.04%  |
| Row Of Chips | 4         | 5.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 29        | 32.95%  |
| 4096  | 28        | 31.82%  |
| 2048  | 15        | 17.05%  |
| 1024  | 5         | 5.68%   |
| 512   | 4         | 4.55%   |
| 16384 | 3         | 3.41%   |
| 128   | 2         | 2.27%   |
| 32768 | 1         | 1.14%   |
| 256   | 1         | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 33.33%  |
| 1333    | 9         | 10.34%  |
| Unknown | 8         | 9.2%    |
| 2400    | 7         | 8.05%   |
| 1334    | 6         | 6.9%    |
| 2133    | 5         | 5.75%   |
| 2667    | 4         | 4.6%    |
| 3600    | 3         | 3.45%   |
| 3200    | 3         | 3.45%   |
| 1866    | 2         | 2.3%    |
| 4267    | 1         | 1.15%   |
| 4199    | 1         | 1.15%   |
| 2200    | 1         | 1.15%   |
| 1867    | 1         | 1.15%   |
| 1800    | 1         | 1.15%   |
| 1400    | 1         | 1.15%   |
| 1200    | 1         | 1.15%   |
| 1067    | 1         | 1.15%   |
| 1066    | 1         | 1.15%   |
| 667     | 1         | 1.15%   |
| 533     | 1         | 1.15%   |

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
| Chicony Electronics                    | 12        | 29.27%  |
| Realtek Semiconductor                  | 5         | 12.2%   |
| Suyin                                  | 4         | 9.76%   |
| Microdia                               | 3         | 7.32%   |
| Z-Star Microelectronics                | 2         | 4.88%   |
| Sunplus Innovation Technology          | 2         | 4.88%   |
| IMC Networks                           | 2         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Syntek                                 | 1         | 2.44%   |
| Silicon Motion                         | 1         | 2.44%   |
| Ricoh                                  | 1         | 2.44%   |
| Quanta                                 | 1         | 2.44%   |
| MacroSilicon                           | 1         | 2.44%   |
| Linux Foundation                       | 1         | 2.44%   |
| Lenovo                                 | 1         | 2.44%   |
| Apple                                  | 1         | 2.44%   |
| Acer                                   | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 4.88%   |
| Chicony Integrated Camera                           | 2         | 4.88%   |
| Chicony HD WebCam                                   | 2         | 4.88%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 2.44%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 2.44%   |
| Syntek EasyCamera                                   | 1         | 2.44%   |
| Suyin Integrated_Webcam_HD                          | 1         | 2.44%   |
| Suyin HP TrueVision HD                              | 1         | 2.44%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 2.44%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.44%   |
| Sunplus HP Universal Camera                         | 1         | 2.44%   |
| Sunplus HD WebCam                                   | 1         | 2.44%   |
| Silicon Motion NCM-G102                             | 1         | 2.44%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 2.44%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 2.44%   |
| Realtek USB Camera                                  | 1         | 2.44%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 2.44%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.44%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 2.44%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.44%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.44%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 2.44%   |
| Linux Foundation EEM Gadget                         | 1         | 2.44%   |
| Lenovo Integrated Webcam                            | 1         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.44%   |
| IMC Networks Integrated Camera                      | 1         | 2.44%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.44%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 2.44%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.44%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.44%   |
| Chicony HP HD Camera                                | 1         | 2.44%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.44%   |
| Chicony CNF8243 Webcam                              | 1         | 2.44%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.44%   |
| Apple iPhone5/5C/5S/6                               | 1         | 2.44%   |
| Acer BisonCam, NB Pro                               | 1         | 2.44%   |

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
| 0     | 62        | 62%     |
| 1     | 24        | 24%     |
| 2     | 9         | 9%      |
| 4     | 2         | 2%      |
| 3     | 2         | 2%      |
| 5     | 1         | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 28.07%  |
| Fingerprint reader       | 7         | 12.28%  |
| Communication controller | 7         | 12.28%  |
| Net/wireless             | 5         | 8.77%   |
| Modem                    | 5         | 8.77%   |
| Network                  | 3         | 5.26%   |
| Unassigned class         | 2         | 3.51%   |
| Sound                    | 2         | 3.51%   |
| Multimedia controller    | 2         | 3.51%   |
| Chipcard                 | 2         | 3.51%   |
| Camera                   | 2         | 3.51%   |
| Unclassified device      | 1         | 1.75%   |
| Storage                  | 1         | 1.75%   |
| Net/ethernet             | 1         | 1.75%   |
| Bluetooth                | 1         | 1.75%   |


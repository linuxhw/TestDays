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

Total: 121

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 11.11%  |
| Alpine 3.15.0               | 10        | 10.1%   |
| Alpine 3.16.0               | 9         | 9.09%   |
| Alpine 3.15.0_alpha20210804 | 7         | 7.07%   |
| Alpine 3.14.0               | 5         | 5.05%   |
| Alpine 3.17_alpha20220809   | 4         | 4.04%   |
| Alpine 3.15.4               | 4         | 4.04%   |
| Alpine 3.14.2               | 4         | 4.04%   |
| Alpine 3.13.0_alpha20200917 | 4         | 4.04%   |
| Alpine 3.13.0_alpha20200626 | 4         | 4.04%   |
| Alpine 3.11.2               | 4         | 4.04%   |
| Alpine 3.16.1               | 3         | 3.03%   |
| Alpine 3.13.1               | 3         | 3.03%   |
| Alpine 3.13.0_alpha20201218 | 3         | 3.03%   |
| Alpine 3.16.2               | 2         | 2.02%   |
| Alpine 3.15.6               | 2         | 2.02%   |
| Alpine 3.13.5               | 2         | 2.02%   |
| Alpine 3.13.2               | 2         | 2.02%   |
| Alpine 3.12.3               | 2         | 2.02%   |
| Alpine 3.8.4                | 1         | 1.01%   |
| Alpine 3.16.0_alpha20220328 | 1         | 1.01%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.01%   |
| Alpine 3.15.2               | 1         | 1.01%   |
| Alpine 3.15.0_rc5           | 1         | 1.01%   |
| Alpine 3.14.3               | 1         | 1.01%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.01%   |
| Alpine 3.13.6               | 1         | 1.01%   |
| Alpine 3.13.3               | 1         | 1.01%   |
| Alpine 3.13.0_rc2           | 1         | 1.01%   |
| Alpine 3.12.7               | 1         | 1.01%   |
| Alpine 3.12.1               | 1         | 1.01%   |
| Alpine 3.12.0_rc1           | 1         | 1.01%   |
| Alpine 3.11.5               | 1         | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 90        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 8%      |
| 5.15.60-0-lts          | 3         | 3%      |
| 5.15.16-0-lts          | 3         | 3%      |
| 5.10.61-0-lts          | 3         | 3%      |
| 5.4.84-0-lts           | 2         | 2%      |
| 5.4.83-0-lts           | 2         | 2%      |
| 5.17.9-0-edge          | 2         | 2%      |
| 5.15.59-0-lts          | 2         | 2%      |
| 5.15.47-0-lts          | 2         | 2%      |
| 5.15.46-1-lts          | 2         | 2%      |
| 5.15.41-0-lts          | 2         | 2%      |
| 5.15.4-0-lts           | 2         | 2%      |
| 5.15.12-0-lts          | 2         | 2%      |
| 5.10.68-0-lts          | 2         | 2%      |
| 5.10.16-0-lts          | 2         | 2%      |
| 5.8.12-0-edge          | 1         | 1%      |
| 5.8.0                  | 1         | 1%      |
| 5.7.4                  | 1         | 1%      |
| 5.6.2-xanmod1-1-xanmod | 1         | 1%      |
| 5.4.99                 | 1         | 1%      |
| 5.4.73-0-lts           | 1         | 1%      |
| 5.4.72-0-lts           | 1         | 1%      |
| 5.4.65-0-lts           | 1         | 1%      |
| 5.4.64-0-lts           | 1         | 1%      |
| 5.4.6-0-lts            | 1         | 1%      |
| 5.4.58-0-lts           | 1         | 1%      |
| 5.4.57-0-lts           | 1         | 1%      |
| 5.4.46-0-lts           | 1         | 1%      |
| 5.4.27-0-lts           | 1         | 1%      |
| 5.4.111-0-lts          | 1         | 1%      |
| 5.4.0-77-generic       | 1         | 1%      |
| 5.19.0-rc8-kukui+      | 1         | 1%      |
| 5.18.0-0-asahi         | 1         | 1%      |
| 5.17.3-0-edge          | 1         | 1%      |
| 5.17.0-0-edge          | 1         | 1%      |
| 5.16.12-may            | 1         | 1%      |
| 5.16.1-may             | 1         | 1%      |
| 5.15.74-0-lts          | 1         | 1%      |
| 5.15.73-0-lts          | 1         | 1%      |
| 5.15.70-0-lts          | 1         | 1%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 8%      |
| 5.15.60 | 3         | 3%      |
| 5.15.16 | 3         | 3%      |
| 5.10.61 | 3         | 3%      |
| 5.4.84  | 2         | 2%      |
| 5.4.83  | 2         | 2%      |
| 5.17.9  | 2         | 2%      |
| 5.15.59 | 2         | 2%      |
| 5.15.47 | 2         | 2%      |
| 5.15.46 | 2         | 2%      |
| 5.15.41 | 2         | 2%      |
| 5.15.4  | 2         | 2%      |
| 5.15.12 | 2         | 2%      |
| 5.10.68 | 2         | 2%      |
| 5.10.16 | 2         | 2%      |
| 5.8.12  | 1         | 1%      |
| 5.8.0   | 1         | 1%      |
| 5.7.4   | 1         | 1%      |
| 5.6.2   | 1         | 1%      |
| 5.4.99  | 1         | 1%      |
| 5.4.73  | 1         | 1%      |
| 5.4.72  | 1         | 1%      |
| 5.4.65  | 1         | 1%      |
| 5.4.64  | 1         | 1%      |
| 5.4.6   | 1         | 1%      |
| 5.4.58  | 1         | 1%      |
| 5.4.57  | 1         | 1%      |
| 5.4.46  | 1         | 1%      |
| 5.4.27  | 1         | 1%      |
| 5.4.111 | 1         | 1%      |
| 5.4.0   | 1         | 1%      |
| 5.19.0  | 1         | 1%      |
| 5.18.0  | 1         | 1%      |
| 5.17.3  | 1         | 1%      |
| 5.17.0  | 1         | 1%      |
| 5.16.12 | 1         | 1%      |
| 5.16.1  | 1         | 1%      |
| 5.15.74 | 1         | 1%      |
| 5.15.73 | 1         | 1%      |
| 5.15.70 | 1         | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 30        | 31.58%  |
| 5.4     | 23        | 24.21%  |
| 5.10    | 23        | 24.21%  |
| 5.17    | 4         | 4.21%   |
| 3.10    | 3         | 3.16%   |
| 5.8     | 2         | 2.11%   |
| 5.7     | 1         | 1.05%   |
| 5.6     | 1         | 1.05%   |
| 5.19    | 1         | 1.05%   |
| 5.18    | 1         | 1.05%   |
| 5.16    | 1         | 1.05%   |
| 5.14    | 1         | 1.05%   |
| 5.13    | 1         | 1.05%   |
| 5.12    | 1         | 1.05%   |
| 4.4     | 1         | 1.05%   |
| 4.14    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 73        | 81.11%  |
| i686    | 12        | 13.33%  |
| aarch64 | 3         | 3.33%   |
| i586    | 1         | 1.11%   |
| armv7l  | 1         | 1.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 85.56%  |
| XFCE    | 5         | 5.56%   |
| GNOME   | 4         | 4.44%   |
| sway    | 1         | 1.11%   |
| KDE5    | 1         | 1.11%   |
| KDE     | 1         | 1.11%   |
| i3      | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 63.04%  |
| X11     | 27        | 29.35%  |
| Wayland | 6         | 6.52%   |
| Tty     | 1         | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 76        | 83.52%  |
| LightDM | 10        | 10.99%  |
| GDM     | 2         | 2.2%    |
| XDM     | 1         | 1.1%    |
| SDDM    | 1         | 1.1%    |
| LXDM    | 1         | 1.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 55        | 59.14%  |
| Unknown | 30        | 32.26%  |
| en_US   | 5         | 5.38%   |
| ru_RU   | 2         | 2.15%   |
| en_GB   | 1         | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 63        | 70%     |
| EFI  | 27        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 79.35%  |
| Overlay | 5         | 5.43%   |
| Btrfs   | 5         | 5.43%   |
| Tmpfs   | 4         | 4.35%   |
| F2fs    | 2         | 2.17%   |
| Unknown | 2         | 2.17%   |
| Ext2    | 1         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 58.51%  |
| GPT     | 27        | 28.72%  |
| MBR     | 12        | 12.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 87.91%  |
| Yes       | 11        | 12.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 92.31%  |
| Yes       | 7         | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 16        | 17.78%  |
| Dell                    | 13        | 14.44%  |
| ASUSTek Computer        | 11        | 12.22%  |
| Lenovo                  | 9         | 10%     |
| Intel                   | 4         | 4.44%   |
| Acer                    | 4         | 4.44%   |
| Unknown                 | 4         | 4.44%   |
| IBM                     | 3         | 3.33%   |
| ASRock                  | 3         | 3.33%   |
| MSI                     | 2         | 2.22%   |
| Gigabyte Technology     | 2         | 2.22%   |
| Gateway                 | 2         | 2.22%   |
| Fujitsu                 | 2         | 2.22%   |
| VIA Technologies        | 1         | 1.11%   |
| Toshiba                 | 1         | 1.11%   |
| Synology                | 1         | 1.11%   |
| Supermicro              | 1         | 1.11%   |
| Sony                    | 1         | 1.11%   |
| Shuttle                 | 1         | 1.11%   |
| Raspberry Pi Foundation | 1         | 1.11%   |
| Pegatron                | 1         | 1.11%   |
| Haier                   | 1         | 1.11%   |
| Google                  | 1         | 1.11%   |
| Fanless Mini PC         | 1         | 1.11%   |
| F5 Networks             | 1         | 1.11%   |
| eMachines               | 1         | 1.11%   |
| Apple                   | 1         | 1.11%   |
| AMI                     | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 4.44%   |
| HP ProLiant DL360 G6                     | 2         | 2.22%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 2.22%   |
| ASUS All Series                          | 2         | 2.22%   |
| VIA KM266APro-835                        | 1         | 1.11%   |
| Toshiba Satellite M645                   | 1         | 1.11%   |
| Synology DS1019+                         | 1         | 1.11%   |
| Supermicro X10SLL-F                      | 1         | 1.11%   |
| Sony VGN-UX27GN                          | 1         | 1.11%   |
| Shuttle DS81D                            | 1         | 1.11%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 1.11%   |
| Pegatron Deepcam                         | 1         | 1.11%   |
| MSI MS-7877                              | 1         | 1.11%   |
| MSI GL72M 7REX                           | 1         | 1.11%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.11%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.11%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.11%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.11%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.11%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.11%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 1.11%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.11%   |
| Lenovo H535 10117                        | 1         | 1.11%   |
| Intel NUC6i7KYB H90766-406               | 1         | 1.11%   |
| Intel Merrifield                         | 1         | 1.11%   |
| Intel DQ67SW                             | 1         | 1.11%   |
| Intel DH61BF AAG81311-101                | 1         | 1.11%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.11%   |
| IBM 26446AG                              | 1         | 1.11%   |
| IBM 264070A                              | 1         | 1.11%   |
| HP ZBook 15 G5                           | 1         | 1.11%   |
| HP Stream 7 Tablet                       | 1         | 1.11%   |
| HP ProLiant MicroServer Gen8             | 1         | 1.11%   |
| HP ProBook 4310s                         | 1         | 1.11%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.11%   |
| HP Mini 110-3500                         | 1         | 1.11%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.11%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.11%   |
| HP EliteBook 8460p                       | 1         | 1.11%   |
| HP EliteBook 2740p                       | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 5.56%   |
| Dell Inspiron       | 5         | 5.56%   |
| Acer Aspire         | 4         | 4.44%   |
| Unknown             | 4         | 4.44%   |
| HP ProLiant         | 3         | 3.33%   |
| HP EliteBook        | 3         | 3.33%   |
| Dell OptiPlex       | 3         | 3.33%   |
| HP Compaq           | 2         | 2.22%   |
| Gigabyte Z490I      | 2         | 2.22%   |
| Dell XPS            | 2         | 2.22%   |
| Dell PowerEdge      | 2         | 2.22%   |
| ASUS All            | 2         | 2.22%   |
| VIA KM266APro-835   | 1         | 1.11%   |
| Toshiba Satellite   | 1         | 1.11%   |
| Synology DS1019+    | 1         | 1.11%   |
| Supermicro X10SLL-F | 1         | 1.11%   |
| Sony VGN-UX27GN     | 1         | 1.11%   |
| Shuttle DS81D       | 1         | 1.11%   |
| RPi Raspberry       | 1         | 1.11%   |
| Pegatron Deepcam    | 1         | 1.11%   |
| MSI MS-7877         | 1         | 1.11%   |
| MSI GL72M           | 1         | 1.11%   |
| Lenovo Yoga         | 1         | 1.11%   |
| Lenovo ThinkCentre  | 1         | 1.11%   |
| Lenovo IdeaPad      | 1         | 1.11%   |
| Lenovo H535         | 1         | 1.11%   |
| Intel NUC6i7KYB     | 1         | 1.11%   |
| Intel Merrifield    | 1         | 1.11%   |
| Intel DQ67SW        | 1         | 1.11%   |
| Intel DH61BF        | 1         | 1.11%   |
| IBM ThinkPad        | 1         | 1.11%   |
| IBM 26446AG         | 1         | 1.11%   |
| IBM 264070A         | 1         | 1.11%   |
| HP ZBook            | 1         | 1.11%   |
| HP Stream           | 1         | 1.11%   |
| HP ProBook          | 1         | 1.11%   |
| HP Presario         | 1         | 1.11%   |
| HP Mini             | 1         | 1.11%   |
| HP Laptop           | 1         | 1.11%   |
| HP ENVY             | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 15        | 16.67%  |
| 2018    | 8         | 8.89%   |
| 2019    | 7         | 7.78%   |
| 2010    | 7         | 7.78%   |
| 2013    | 6         | 6.67%   |
| 2016    | 5         | 5.56%   |
| 2012    | 5         | 5.56%   |
| 2009    | 5         | 5.56%   |
| Unknown | 5         | 5.56%   |
| 2017    | 4         | 4.44%   |
| 2015    | 4         | 4.44%   |
| 2021    | 3         | 3.33%   |
| 2020    | 3         | 3.33%   |
| 2011    | 3         | 3.33%   |
| 2006    | 3         | 3.33%   |
| 2007    | 2         | 2.22%   |
| 2005    | 2         | 2.22%   |
| 2008    | 1         | 1.11%   |
| 2004    | 1         | 1.11%   |
| 1999    | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 46        | 51.11%  |
| Desktop        | 27        | 30%     |
| Server         | 6         | 6.67%   |
| Mini pc        | 5         | 5.56%   |
| System on chip | 2         | 2.22%   |
| Tablet         | 2         | 2.22%   |
| Convertible    | 1         | 1.11%   |
| All in one     | 1         | 1.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 90        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 98.89%  |
| Yes  | 1         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 21        | 22.34%  |
| 4.01-8.0        | 18        | 19.15%  |
| 16.01-24.0      | 14        | 14.89%  |
| 8.01-16.0       | 12        | 12.77%  |
| 0.51-1.0        | 8         | 8.51%   |
| 1.01-2.0        | 6         | 6.38%   |
| 32.01-64.0      | 4         | 4.26%   |
| 2.01-3.0        | 4         | 4.26%   |
| 64.01-256.0     | 3         | 3.19%   |
| 0.01-0.5        | 3         | 3.19%   |
| More than 256.0 | 1         | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 30        | 31.25%  |
| 1.01-2.0  | 19        | 19.79%  |
| 0.51-1.0  | 16        | 16.67%  |
| 3.01-4.0  | 9         | 9.38%   |
| 2.01-3.0  | 7         | 7.29%   |
| 4.01-8.0  | 6         | 6.25%   |
| 8.01-16.0 | 4         | 4.17%   |
| Unknown   | 3         | 3.13%   |
| 0         | 2         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 63.44%  |
| 2      | 18        | 19.35%  |
| 3      | 6         | 6.45%   |
| 4      | 4         | 4.3%    |
| 14     | 2         | 2.15%   |
| 10     | 1         | 1.08%   |
| 7      | 1         | 1.08%   |
| 5      | 1         | 1.08%   |
| 0      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 76.67%  |
| Yes       | 21        | 23.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 85.56%  |
| No        | 13        | 14.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 60%     |
| No        | 36        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 60%     |
| Yes       | 36        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 26.37%  |
| Russia       | 9         | 9.89%   |
| UK           | 8         | 8.79%   |
| Canada       | 8         | 8.79%   |
| Germany      | 7         | 7.69%   |
| Sweden       | 4         | 4.4%    |
| Brazil       | 3         | 3.3%    |
| Australia    | 3         | 3.3%    |
| Spain        | 2         | 2.2%    |
| Poland       | 2         | 2.2%    |
| Norway       | 2         | 2.2%    |
| Guatemala    | 2         | 2.2%    |
| Venezuela    | 1         | 1.1%    |
| Ukraine      | 1         | 1.1%    |
| Switzerland  | 1         | 1.1%    |
| South Korea  | 1         | 1.1%    |
| South Africa | 1         | 1.1%    |
| Slovakia     | 1         | 1.1%    |
| Portugal     | 1         | 1.1%    |
| Pakistan     | 1         | 1.1%    |
| Mexico       | 1         | 1.1%    |
| Italy        | 1         | 1.1%    |
| Indonesia    | 1         | 1.1%    |
| France       | 1         | 1.1%    |
| Egypt        | 1         | 1.1%    |
| Czechia      | 1         | 1.1%    |
| China        | 1         | 1.1%    |
| Austria      | 1         | 1.1%    |
| Argentina    | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 6         | 6.38%   |
| Springfield    | 5         | 5.32%   |
| Manitowoc      | 5         | 5.32%   |
| Vernon         | 2         | 2.13%   |
| Sydney         | 2         | 2.13%   |
| Stratford      | 2         | 2.13%   |
| Guatemala City | 2         | 2.13%   |
| Gothenburg     | 2         | 2.13%   |
| Fulham         | 2         | 2.13%   |
| As             | 2         | 2.13%   |
| Zurich         | 1         | 1.06%   |
| Vancouver      | 1         | 1.06%   |
| Tymovskoye     | 1         | 1.06%   |
| Topeka         | 1         | 1.06%   |
| Thame          | 1         | 1.06%   |
| Tampa          | 1         | 1.06%   |
| Stockholm      | 1         | 1.06%   |
| Stewartstown   | 1         | 1.06%   |
| Sisteron       | 1         | 1.06%   |
| Semily         | 1         | 1.06%   |
| Sao Paulo      | 1         | 1.06%   |
| San Mateo      | 1         | 1.06%   |
| Salzburg       | 1         | 1.06%   |
| Saarbrücken   | 1         | 1.06%   |
| Rzeszów       | 1         | 1.06%   |
| Rostock        | 1         | 1.06%   |
| Redwood City   | 1         | 1.06%   |
| Purdys         | 1         | 1.06%   |
| Plymouth       | 1         | 1.06%   |
| Penza          | 1         | 1.06%   |
| Ottawa         | 1         | 1.06%   |
| Oakville       | 1         | 1.06%   |
| Nuremberg      | 1         | 1.06%   |
| Milwaukee      | 1         | 1.06%   |
| Merrill        | 1         | 1.06%   |
| Mérida        | 1         | 1.06%   |
| Mankato        | 1         | 1.06%   |
| Malmo          | 1         | 1.06%   |
| Madrid         | 1         | 1.06%   |
| London         | 1         | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 39     | 11.86%  |
| Samsung Electronics | 14        | 21     | 11.86%  |
| Seagate             | 13        | 35     | 11.02%  |
| Unknown             | 9         | 11     | 7.63%   |
| Hitachi             | 9         | 9      | 7.63%   |
| Kingston            | 7         | 8      | 5.93%   |
| Toshiba             | 6         | 8      | 5.08%   |
| HGST                | 6         | 6      | 5.08%   |
| Intel               | 5         | 9      | 4.24%   |
| Crucial             | 5         | 13     | 4.24%   |
| SK hynix            | 4         | 6      | 3.39%   |
| A-DATA Technology   | 3         | 3      | 2.54%   |
| Transcend           | 2         | 2      | 1.69%   |
| SanDisk             | 2         | 2      | 1.69%   |
| LITEON              | 2         | 2      | 1.69%   |
| STEC                | 1         | 1      | 0.85%   |
| SPCC                | 1         | 1      | 0.85%   |
| NETAPP              | 1         | 1      | 0.85%   |
| Micron Technology   | 1         | 1      | 0.85%   |
| Lexar               | 1         | 1      | 0.85%   |
| Kingmax             | 1         | 1      | 0.85%   |
| KC600               | 1         | 1      | 0.85%   |
| JMicron Technology  | 1         | 1      | 0.85%   |
| Intenso             | 1         | 1      | 0.85%   |
| IBM                 | 1         | 1      | 0.85%   |
| Fujitsu             | 1         | 1      | 0.85%   |
| Emtec               | 1         | 1      | 0.85%   |
| Dell                | 1         | 2      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| Apple               | 1         | 3      | 0.85%   |
| AMD                 | 1         | 1      | 0.85%   |
| Unknown             | 1         | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD3000BLFS-60YBU2 304GB          | 2         | 1.55%   |
| Unknown MMC Card  16GB               | 2         | 1.55%   |
| Seagate ST4000VN008-2DR1 4TB         | 2         | 1.55%   |
| Samsung SSD 960 EVO 500GB            | 2         | 1.55%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.55%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 1.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.78%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.78%   |
| WDC WD80EMAZ-00WJTA0 8TB             | 1         | 0.78%   |
| WDC WD80EFAX-68LHPN0 8TB             | 1         | 0.78%   |
| WDC WD800AAJS-00 80GB                | 1         | 0.78%   |
| WDC WD5003ABYZ-0 500GB               | 1         | 0.78%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 0.78%   |
| WDC WD3200AAKX-0 320GB               | 1         | 0.78%   |
| WDC WD20EZRZ-00Z 2TB                 | 1         | 0.78%   |
| WDC WD1600BEVT-2 160GB               | 1         | 0.78%   |
| WDC WD140EDFZ-11A0VA0 14TB           | 1         | 0.78%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.78%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 0.78%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 0.78%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB | 1         | 0.78%   |
| Unknown SD64G  64GB                  | 1         | 0.78%   |
| Unknown SD32G  32GB                  | 1         | 0.78%   |
| Unknown SD16G  32GB                  | 1         | 0.78%   |
| Unknown NVMe SSD Drive 1024GB        | 1         | 0.78%   |
| Unknown MMC Card  4GB                | 1         | 0.78%   |
| Unknown MMC Card  32GB               | 1         | 0.78%   |
| Unknown MMC Card                     | 1         | 0.78%   |
| Transcend TS128GSSD420I 128GB        | 1         | 0.78%   |
| Transcend SSD 1GB                    | 1         | 0.78%   |
| Toshiba NVMe SSD Drive 256GB         | 1         | 0.78%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.78%   |
| Toshiba MQ01ABD1 1TB                 | 1         | 0.78%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.78%   |
| Toshiba MK4009GAL 40GB               | 1         | 0.78%   |
| Toshiba MK3252GS 320GB               | 1         | 0.78%   |
| Toshiba KXG5AZNV256G 256GB           | 1         | 0.78%   |
| Toshiba KBG40ZPZ512G NVMe 512GB      | 1         | 0.78%   |
| STEC SDT5A-S200SS 200GB              | 1         | 0.78%   |
| SPCC Solid State Disk 256GB          | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 35     | 27.66%  |
| WDC                 | 11        | 35     | 23.4%   |
| Hitachi             | 9         | 9      | 19.15%  |
| HGST                | 6         | 6      | 12.77%  |
| Toshiba             | 4         | 5      | 8.51%   |
| Samsung Electronics | 2         | 4      | 4.26%   |
| IBM                 | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 8      | 16.28%  |
| Samsung Electronics | 5         | 7      | 11.63%  |
| Crucial             | 5         | 13     | 11.63%  |
| Intel               | 3         | 5      | 6.98%   |
| A-DATA Technology   | 3         | 3      | 6.98%   |
| WDC                 | 2         | 2      | 4.65%   |
| Transcend           | 2         | 2      | 4.65%   |
| SK hynix            | 2         | 3      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| LITEON              | 2         | 2      | 4.65%   |
| SPCC                | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Lexar               | 1         | 1      | 2.33%   |
| Kingmax             | 1         | 1      | 2.33%   |
| KC600               | 1         | 1      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| Emtec               | 1         | 1      | 2.33%   |
| Dell                | 1         | 2      | 2.33%   |
| China               | 1         | 1      | 2.33%   |
| AMD                 | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 44        | 96     | 39.64%  |
| SSD     | 40        | 58     | 36.04%  |
| NVMe    | 17        | 26     | 15.32%  |
| MMC     | 9         | 12     | 8.11%   |
| Unknown | 1         | 2      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 150    | 70%     |
| NVMe | 16        | 25     | 16%     |
| MMC  | 9         | 12     | 9%      |
| SAS  | 5         | 7      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 96     | 73.17%  |
| 0.51-1.0   | 13        | 17     | 15.85%  |
| 3.01-4.0   | 3         | 14     | 3.66%   |
| 4.01-10.0  | 3         | 19     | 3.66%   |
| 1.01-2.0   | 2         | 4      | 2.44%   |
| 10.01-20.0 | 1         | 4      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 23.4%   |
| 1-20           | 16        | 17.02%  |
| Unknown        | 13        | 13.83%  |
| 21-50          | 10        | 10.64%  |
| 251-500        | 9         | 9.57%   |
| 501-1000       | 9         | 9.57%   |
| 1001-2000      | 5         | 5.32%   |
| 51-100         | 4         | 4.26%   |
| More than 3000 | 3         | 3.19%   |
| 2001-3000      | 3         | 3.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 56        | 60.22%  |
| Unknown   | 13        | 13.98%  |
| 51-100    | 7         | 7.53%   |
| 21-50     | 6         | 6.45%   |
| 251-500   | 3         | 3.23%   |
| 101-250   | 3         | 3.23%   |
| 501-1000  | 3         | 3.23%   |
| 2001-3000 | 1         | 1.08%   |
| 1001-2000 | 1         | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 12.5%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 6.25%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 6.25%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 6.25%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 6.25%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 6.25%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 6.25%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 6.25%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 6.25%   |
| Kingmax SSD 120G                               | 1         | 1      | 6.25%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 6.25%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 6.25%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 6.25%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 25%     |
| WDC                 | 3         | 15     | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 4      | 12.5%   |
| Seagate             | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Kingmax             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 30.77%  |
| WDC                 | 3         | 15     | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Samsung Electronics | 2         | 4      | 15.38%  |
| Seagate             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 27     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

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
| Works    | 61        | 133    | 61%     |
| Detected | 23        | 31     | 23%     |
| Malfunc  | 16        | 30     | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 64%     |
| AMD                          | 9         | 9%      |
| Samsung Electronics          | 8         | 8%      |
| LSI Logic / Symbios Logic    | 3         | 3%      |
| Hewlett-Packard              | 2         | 2%      |
| Adaptec                      | 2         | 2%      |
| VIA Technologies             | 1         | 1%      |
| Toshiba America Info Systems | 1         | 1%      |
| SK hynix                     | 1         | 1%      |
| SanDisk                      | 1         | 1%      |
| Promise Technology           | 1         | 1%      |
| Nvidia                       | 1         | 1%      |
| Micron/Crucial Technology    | 1         | 1%      |
| Marvell Technology Group     | 1         | 1%      |
| KIOXIA                       | 1         | 1%      |
| Broadcom / LSI               | 1         | 1%      |
| ASMedia Technology           | 1         | 1%      |
| ADATA Technology             | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 7.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 6.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 5.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 5.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 3.7%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 3         | 2.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.85%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 1.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.85%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 2         | 1.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.93%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.93%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.93%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                        | 1         | 0.93%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.93%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.93%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.93%   |
| Intel SSD 600P Series                                                            | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 58.42%  |
| NVMe | 15        | 14.85%  |
| IDE  | 14        | 13.86%  |
| RAID | 10        | 9.9%    |
| SAS  | 3         | 2.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 75        | 82.42%  |
| AMD     | 12        | 13.19%  |
| ARM     | 3         | 3.3%    |
| Unknown | 1         | 1.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 2.2%    |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 2.2%    |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 2.2%    |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 2.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 2.2%    |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2         | 2.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 2.2%    |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 2.2%    |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 2.2%    |
| ARM Processor                          | 2         | 2.2%    |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 1.1%    |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 1.1%    |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 1.1%    |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 1.1%    |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 1.1%    |
| Intel Pentium M processor 1.70GHz      | 1         | 1.1%    |
| Intel Pentium M processor 1.60GHz      | 1         | 1.1%    |
| Intel Pentium M processor 1.50GHz      | 1         | 1.1%    |
| Intel Pentium III (Coppermine)         | 1         | 1.1%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 1.1%    |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 1.1%    |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 1.1%    |
| Intel Mobile Pentium MMX               | 1         | 1.1%    |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 1.1%    |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 1.1%    |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 1.1%    |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 1.1%    |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 1.1%    |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.1%    |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 1.1%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.1%    |
| Intel Core i7 CPU Q 820 @ 1.73GHz      | 1         | 1.1%    |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1         | 1.1%    |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.1%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz      | 1         | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 1.1%    |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 17        | 18.68%  |
| Intel Celeron      | 11        | 12.09%  |
| Intel Core i7      | 8         | 8.79%   |
| Other              | 7         | 7.69%   |
| Intel Core i3      | 7         | 7.69%   |
| Intel Atom         | 7         | 7.69%   |
| Intel Xeon         | 6         | 6.59%   |
| Intel Pentium M    | 3         | 3.3%    |
| Intel Core i9      | 3         | 3.3%    |
| Intel Core 2 Duo   | 3         | 3.3%    |
| Intel Pentium      | 2         | 2.2%    |
| AMD A4             | 2         | 2.2%    |
| Intel Xeon Gold    | 1         | 1.1%    |
| Intel Pentium III  | 1         | 1.1%    |
| Intel Pentium Dual | 1         | 1.1%    |
| Intel Genuine      | 1         | 1.1%    |
| Intel Core Solo    | 1         | 1.1%    |
| Intel Core 2       | 1         | 1.1%    |
| Intel Celeron M    | 1         | 1.1%    |
| AMD Sempron        | 1         | 1.1%    |
| AMD Ryzen 7        | 1         | 1.1%    |
| AMD Ryzen 5        | 1         | 1.1%    |
| AMD FX             | 1         | 1.1%    |
| AMD E1             | 1         | 1.1%    |
| AMD A8             | 1         | 1.1%    |
| AMD A6             | 1         | 1.1%    |
| AMD A10            | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 36        | 39.56%  |
| 4       | 31        | 34.07%  |
| 1       | 12        | 13.19%  |
| 8       | 3         | 3.3%    |
| 12      | 2         | 2.2%    |
| 10      | 2         | 2.2%    |
| 6       | 2         | 2.2%    |
| 32      | 1         | 1.1%    |
| 3       | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 86        | 94.51%  |
| 2       | 4         | 4.4%    |
| Unknown | 1         | 1.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 48        | 53.33%  |
| 2       | 41        | 45.56%  |
| Unknown | 1         | 1.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 46        | 50%     |
| 32-bit, 64-bit | 40        | 43.48%  |
| 32-bit         | 5         | 5.43%   |
| 64-bit         | 1         | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 55.79%  |
| 0x306c3    | 5         | 5.26%   |
| 0x306a9    | 4         | 4.21%   |
| 0x30678    | 4         | 4.21%   |
| 0x206c2    | 3         | 3.16%   |
| 0x906ea    | 2         | 2.11%   |
| 0x506c9    | 2         | 2.11%   |
| 0x406c4    | 2         | 2.11%   |
| 0x206a7    | 2         | 2.11%   |
| 0x106e5    | 2         | 2.11%   |
| 0x106ca    | 2         | 2.11%   |
| 0x06006704 | 2         | 2.11%   |
| 0xa0655    | 1         | 1.05%   |
| 0x806eb    | 1         | 1.05%   |
| 0x706e5    | 1         | 1.05%   |
| 0x6fd      | 1         | 1.05%   |
| 0x6d8      | 1         | 1.05%   |
| 0x683      | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x306d4    | 1         | 1.05%   |
| 0x20655    | 1         | 1.05%   |
| 0x1067a    | 1         | 1.05%   |
| 0x0810100b | 1         | 1.05%   |
| 0x010000b6 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 9         | 9.89%   |
| Haswell       | 9         | 9.89%   |
| KabyLake      | 8         | 8.79%   |
| P6            | 6         | 6.59%   |
| IvyBridge     | 6         | 6.59%   |
| Unknown       | 6         | 6.59%   |
| Westmere      | 5         | 5.49%   |
| SandyBridge   | 4         | 4.4%    |
| Penryn        | 4         | 4.4%    |
| Goldmont      | 4         | 4.4%    |
| Skylake       | 3         | 3.3%    |
| Excavator     | 3         | 3.3%    |
| Broadwell     | 3         | 3.3%    |
| Bonnell       | 3         | 3.3%    |
| Piledriver    | 2         | 2.2%    |
| Nehalem       | 2         | 2.2%    |
| Jaguar        | 2         | 2.2%    |
| IceLake       | 2         | 2.2%    |
| Core          | 2         | 2.2%    |
| CometLake     | 2         | 2.2%    |
| Zen 2         | 1         | 1.1%    |
| Zen           | 1         | 1.1%    |
| Puma          | 1         | 1.1%    |
| K6            | 1         | 1.1%    |
| K10           | 1         | 1.1%    |
| Goldmont plus | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 60        | 63.83%  |
| AMD                        | 19        | 20.21%  |
| Nvidia                     | 7         | 7.45%   |
| Matrox Electronics Systems | 4         | 4.26%   |
| Neomagic                   | 2         | 2.13%   |
| VIA Technologies           | 1         | 1.06%   |
| ASPEED Technology          | 1         | 1.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 7.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 4.12%   |
| Intel HD Graphics 500                                                                    | 4         | 4.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.09%   |
| AMD ES1000                                                                               | 3         | 3.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.06%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 2.06%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 2.06%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.06%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.06%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 2.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 2.06%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.03%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.03%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.03%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1         | 1.03%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.03%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.03%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.03%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.03%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.03%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.03%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.03%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.03%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.03%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 48        | 52.75%  |
| 1 x AMD         | 16        | 17.58%  |
| Other           | 5         | 5.49%   |
| 2 x Intel       | 5         | 5.49%   |
| 1 x Nvidia      | 3         | 3.3%    |
| 1 x Matrox      | 3         | 3.3%    |
| Intel + Nvidia  | 3         | 3.3%    |
| 1 x Neomagic    | 2         | 2.2%    |
| Intel + AMD     | 2         | 2.2%    |
| 2 x AMD         | 1         | 1.1%    |
| 1 x VIA         | 1         | 1.1%    |
| Nvidia + Matrox | 1         | 1.1%    |
| 1 x ASPEED      | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 76        | 81.72%  |
| Unknown     | 15        | 16.13%  |
| Proprietary | 2         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 86.67%  |
| 0.01-0.5   | 7         | 7.78%   |
| 1.01-2.0   | 2         | 2.22%   |
| 7.01-8.0   | 1         | 1.11%   |
| 3.01-4.0   | 1         | 1.11%   |
| 0.51-1.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 12.16%  |
| Samsung Electronics     | 7         | 9.46%   |
| LG Display              | 7         | 9.46%   |
| Dell                    | 7         | 9.46%   |
| Chimei Innolux          | 6         | 8.11%   |
| BOE                     | 4         | 5.41%   |
| Chi Mei Optoelectronics | 3         | 4.05%   |
| BenQ                    | 3         | 4.05%   |
| AOC                     | 3         | 4.05%   |
| Acer                    | 3         | 4.05%   |
| LG Philips              | 2         | 2.7%    |
| Hewlett-Packard         | 2         | 2.7%    |
| Goldstar                | 2         | 2.7%    |
| ViewSonic               | 1         | 1.35%   |
| Sony                    | 1         | 1.35%   |
| SKY                     | 1         | 1.35%   |
| Sharp                   | 1         | 1.35%   |
| ONN                     | 1         | 1.35%   |
| Mi                      | 1         | 1.35%   |
| Lenovo                  | 1         | 1.35%   |
| KVM                     | 1         | 1.35%   |
| InfoVision              | 1         | 1.35%   |
| HannStar                | 1         | 1.35%   |
| Envision                | 1         | 1.35%   |
| Elo Touch               | 1         | 1.35%   |
| EDI                     | 1         | 1.35%   |
| DENON                   | 1         | 1.35%   |
| CSO                     | 1         | 1.35%   |
| CPT                     | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 4%      |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2         | 2.67%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 1.33%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 1.33%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 1.33%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 1.33%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 1.33%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 1.33%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1         | 1.33%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 1.33%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.33%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 1.33%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.33%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 1.33%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 1.33%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 1.33%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 1.33%   |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.33%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.33%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch          | 1         | 1.33%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 509x286mm 23.0-inch      | 1         | 1.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.33%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 1.33%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.33%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch            | 1         | 1.33%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch               | 1         | 1.33%   |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                 | 1         | 1.33%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                       | 1         | 1.33%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.33%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                     | 1         | 1.33%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1         | 1.33%   |
| Dell E151FPb DELA005 1024x768 304x228mm 15.0-inch                     | 1         | 1.33%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 25.68%  |
| 1366x768 (WXGA)    | 19        | 25.68%  |
| 1280x800 (WXGA)    | 5         | 6.76%   |
| 1280x1024 (SXGA)   | 5         | 6.76%   |
| 1680x1050 (WSXGA+) | 4         | 5.41%   |
| 3840x2160 (4K)     | 3         | 4.05%   |
| 2560x1440 (QHD)    | 3         | 4.05%   |
| 1024x600           | 3         | 4.05%   |
| 3440x1440          | 2         | 2.7%    |
| 1920x1200 (WUXGA)  | 2         | 2.7%    |
| 1600x900 (HD+)     | 2         | 2.7%    |
| 2880x1800          | 1         | 1.35%   |
| 2560x1700          | 1         | 1.35%   |
| 2560x1080          | 1         | 1.35%   |
| 1440x900 (WXGA+)   | 1         | 1.35%   |
| 1360x768           | 1         | 1.35%   |
| 1280x768           | 1         | 1.35%   |
| 1024x768 (XGA)     | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 15        | 20%     |
| 13     | 9         | 12%     |
| 17     | 7         | 9.33%   |
| 14     | 6         | 8%      |
| 23     | 4         | 5.33%   |
| 21     | 4         | 5.33%   |
| 20     | 4         | 5.33%   |
| 27     | 3         | 4%      |
| 24     | 3         | 4%      |
| 12     | 3         | 4%      |
| 10     | 3         | 4%      |
| 34     | 2         | 2.67%   |
| 31     | 2         | 2.67%   |
| 19     | 2         | 2.67%   |
| 11     | 2         | 2.67%   |
| 65     | 1         | 1.33%   |
| 54     | 1         | 1.33%   |
| 40     | 1         | 1.33%   |
| 32     | 1         | 1.33%   |
| 29     | 1         | 1.33%   |
| 25     | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 40%     |
| 201-300     | 11        | 14.67%  |
| 501-600     | 10        | 13.33%  |
| 401-500     | 8         | 10.67%  |
| 351-400     | 6         | 8%      |
| 601-700     | 4         | 5.33%   |
| 701-800     | 3         | 4%      |
| 1001-1500   | 2         | 2.67%   |
| 801-900     | 1         | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 68.12%  |
| 16/10 | 12        | 17.39%  |
| 5/4   | 5         | 7.25%   |
| 21/9  | 3         | 4.35%   |
| 4/3   | 1         | 1.45%   |
| 3/2   | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 20%     |
| 81-90          | 12        | 16%     |
| 201-250        | 10        | 13.33%  |
| 151-200        | 7         | 9.33%   |
| 351-500        | 5         | 6.67%   |
| 71-80          | 4         | 5.33%   |
| 301-350        | 4         | 5.33%   |
| 41-50          | 3         | 4%      |
| 141-150        | 3         | 4%      |
| More than 1000 | 2         | 2.67%   |
| 61-70          | 2         | 2.67%   |
| 51-60          | 2         | 2.67%   |
| 131-140        | 2         | 2.67%   |
| 121-130        | 2         | 2.67%   |
| 251-300        | 1         | 1.33%   |
| 501-1000       | 1         | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 24        | 33.8%   |
| 51-100        | 24        | 33.8%   |
| 121-160       | 12        | 16.9%   |
| 1-50          | 5         | 7.04%   |
| 161-240       | 4         | 5.63%   |
| More than 240 | 2         | 2.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 65.22%  |
| 0     | 24        | 26.09%  |
| 2     | 7         | 7.61%   |
| 4     | 1         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 46        | 34.07%  |
| Intel                           | 36        | 26.67%  |
| Qualcomm Atheros                | 18        | 13.33%  |
| Broadcom                        | 16        | 11.85%  |
| Xiaomi                          | 3         | 2.22%   |
| Marvell Technology Group        | 3         | 2.22%   |
| Qualcomm Atheros Communications | 2         | 1.48%   |
| Qualcomm                        | 2         | 1.48%   |
| VIA Technologies                | 1         | 0.74%   |
| T & A Mobile Phones             | 1         | 0.74%   |
| Sigma Designs                   | 1         | 0.74%   |
| Nvidia                          | 1         | 0.74%   |
| Mellanox Technologies           | 1         | 0.74%   |
| LSI                             | 1         | 0.74%   |
| Dresden Elektronik              | 1         | 0.74%   |
| D-Link System                   | 1         | 0.74%   |
| Broadcom Limited                | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 26        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 4.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 1.92%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.28%   |
| Intel Wireless 8260                                                            | 2         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.28%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 1.28%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 1.28%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.64%   |
| T & A Mobile Phones Spreadtrum Phone                                           | 1         | 0.64%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                | 1         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.64%   |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                                         | 1         | 0.64%   |
| Qualcomm Mobile Router                                                         | 1         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.64%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.64%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.64%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.64%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.64%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 44.64%  |
| Qualcomm Atheros                | 15        | 26.79%  |
| Broadcom                        | 8         | 14.29%  |
| Realtek Semiconductor           | 4         | 7.14%   |
| Qualcomm Atheros Communications | 2         | 3.57%   |
| Marvell Technology Group        | 1         | 1.79%   |
| Broadcom Limited                | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 12.5%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 5.36%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 3.57%   |
| Intel Wireless 8260                                                            | 2         | 3.57%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 3.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.79%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.79%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.79%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.79%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.79%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.79%   |
| Intel Wireless 7265                                                            | 1         | 1.79%   |
| Intel Wireless 7260                                                            | 1         | 1.79%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.79%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.79%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.79%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 1.79%   |
| Broadcom BRCM4378 Wireless Network Adapter                                     | 1         | 1.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1         | 1.79%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 1         | 1.79%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 1.79%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 48.31%  |
| Intel                    | 22        | 24.72%  |
| Broadcom                 | 10        | 11.24%  |
| Xiaomi                   | 3         | 3.37%   |
| Qualcomm Atheros         | 3         | 3.37%   |
| Qualcomm                 | 2         | 2.25%   |
| Marvell Technology Group | 2         | 2.25%   |
| VIA Technologies         | 1         | 1.12%   |
| Nvidia                   | 1         | 1.12%   |
| Mellanox Technologies    | 1         | 1.12%   |
| D-Link System            | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.59%   |
| Intel I210 Gigabit Network Connection                             | 3         | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 2.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.2%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.2%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.1%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.1%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.1%    |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                            | 1         | 1.1%    |
| Qualcomm Mobile Router                                            | 1         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 1         | 1.1%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.1%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.1%    |
| Intel WiMAX Connection 2400m                                      | 1         | 1.1%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.1%    |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82567V-4 Gigabit Network Connection                         | 1         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.1%    |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 1.1%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.1%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                    | 1         | 1.1%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 54.68%  |
| WiFi     | 54        | 38.85%  |
| Modem    | 6         | 4.32%   |
| Unknown  | 3         | 2.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 59.04%  |
| WiFi     | 34        | 40.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 52.17%  |
| 1     | 30        | 32.61%  |
| 0     | 7         | 7.61%   |
| 4     | 3         | 3.26%   |
| 5     | 2         | 2.17%   |
| 3     | 2         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 86.81%  |
| Yes  | 12        | 13.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 41.67%  |
| Qualcomm Atheros Communications | 4         | 11.11%  |
| Lite-On Technology              | 3         | 8.33%   |
| IMC Networks                    | 3         | 8.33%   |
| Broadcom                        | 3         | 8.33%   |
| Realtek Semiconductor           | 1         | 2.78%   |
| Marvell Semiconductor           | 1         | 2.78%   |
| Hewlett-Packard                 | 1         | 2.78%   |
| Foxconn / Hon Hai               | 1         | 2.78%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |
| ASUSTek Computer                | 1         | 2.78%   |
| Apple                           | 1         | 2.78%   |
| Alps Electric                   | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 13.89%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.33%   |
| Intel AX201 Bluetooth                               | 3         | 8.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.56%   |
| Intel AX200 Bluetooth                               | 2         | 5.56%   |
| IMC Networks Bluetooth Device                       | 2         | 5.56%   |
| Realtek Bluetooth Radio                             | 1         | 2.78%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.78%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.78%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.78%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.78%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.78%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.78%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 60        | 69.77%  |
| AMD                                  | 14        | 16.28%  |
| Nvidia                               | 2         | 2.33%   |
| VIA Technologies                     | 1         | 1.16%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.16%   |
| Texas Instruments                    | 1         | 1.16%   |
| Sennheiser Communications            | 1         | 1.16%   |
| RODE Microphones                     | 1         | 1.16%   |
| Realtek Semiconductor                | 1         | 1.16%   |
| Native Instruments                   | 1         | 1.16%   |
| Logitech                             | 1         | 1.16%   |
| Cirrus Logic                         | 1         | 1.16%   |
| C-Media Electronics                  | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 3.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.96%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.98%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.98%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.98%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.98%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 1.98%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.98%   |
| AMD High Definition Audio Controller                                       | 2         | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.98%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.99%   |
| Thesycon Systemsoftware & Consulting D10s                                  | 1         | 0.99%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.99%   |
| Sennheiser Communications Sennheiser USB headset                           | 1         | 0.99%   |
| RODE Microphones RODE NT-USB Mini                                          | 1         | 0.99%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.99%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.99%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.99%   |
| Native Instruments Komplete Audio 2                                        | 1         | 0.99%   |
| Logitech G435 Wireless Gaming Headset                                      | 1         | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.99%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.99%   |
| Intel Multimedia audio controller                                          | 1         | 0.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.99%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 16        | 18.39%  |
| SK hynix            | 15        | 17.24%  |
| Samsung Electronics | 15        | 17.24%  |
| Crucial             | 9         | 10.34%  |
| Elpida              | 8         | 9.2%    |
| Micron Technology   | 7         | 8.05%   |
| Kingston            | 6         | 6.9%    |
| A-DATA Technology   | 3         | 3.45%   |
| Corsair             | 2         | 2.3%    |
| Unknown (ABCD)      | 1         | 1.15%   |
| Transcend           | 1         | 1.15%   |
| Qimonda             | 1         | 1.15%   |
| Patriot             | 1         | 1.15%   |
| Hewlett-Packard     | 1         | 1.15%   |
| Cors                | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 3.19%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.13%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.13%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 2.13%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 2.13%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.06%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.06%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 1.06%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.06%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 1.06%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT151R7BFR4C-G7 4096MB DIMM DDR3 1066MT/s          | 1         | 1.06%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.06%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.06%   |
| SK hynix RAM H5TC4G63AFR-PBA 1GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.06%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 43        | 56.58%  |
| DDR4    | 15        | 19.74%  |
| SDRAM   | 4         | 5.26%   |
| DDR     | 4         | 5.26%   |
| LPDDR4  | 3         | 3.95%   |
| LPDDR3  | 3         | 3.95%   |
| DDR2    | 2         | 2.63%   |
| DRAM    | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 52%     |
| DIMM         | 32        | 42.67%  |
| Row Of Chips | 4         | 5.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 32.53%  |
| 4096  | 27        | 32.53%  |
| 2048  | 14        | 16.87%  |
| 1024  | 5         | 6.02%   |
| 512   | 4         | 4.82%   |
| 16384 | 3         | 3.61%   |
| 128   | 2         | 2.41%   |
| 256   | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 32.93%  |
| 1333    | 9         | 10.98%  |
| Unknown | 8         | 9.76%   |
| 2400    | 7         | 8.54%   |
| 2133    | 5         | 6.1%    |
| 1334    | 5         | 6.1%    |
| 2667    | 4         | 4.88%   |
| 3600    | 2         | 2.44%   |
| 3200    | 2         | 2.44%   |
| 1866    | 2         | 2.44%   |
| 4267    | 1         | 1.22%   |
| 4199    | 1         | 1.22%   |
| 2200    | 1         | 1.22%   |
| 1867    | 1         | 1.22%   |
| 1800    | 1         | 1.22%   |
| 1400    | 1         | 1.22%   |
| 1200    | 1         | 1.22%   |
| 1067    | 1         | 1.22%   |
| 1066    | 1         | 1.22%   |
| 667     | 1         | 1.22%   |
| 533     | 1         | 1.22%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 30.77%  |
| Realtek Semiconductor                  | 5         | 12.82%  |
| Suyin                                  | 4         | 10.26%  |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Microdia                               | 2         | 5.13%   |
| IMC Networks                           | 2         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.13%   |
| Z-Star Microelectronics                | 1         | 2.56%   |
| Syntek                                 | 1         | 2.56%   |
| Silicon Motion                         | 1         | 2.56%   |
| Ricoh                                  | 1         | 2.56%   |
| Quanta                                 | 1         | 2.56%   |
| MacroSilicon                           | 1         | 2.56%   |
| Linux Foundation                       | 1         | 2.56%   |
| Lenovo                                 | 1         | 2.56%   |
| Apple                                  | 1         | 2.56%   |
| Acer                                   | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 5.13%   |
| Chicony Integrated Camera                           | 2         | 5.13%   |
| Chicony HD WebCam                                   | 2         | 5.13%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 2.56%   |
| Syntek EasyCamera                                   | 1         | 2.56%   |
| Suyin Integrated_Webcam_HD                          | 1         | 2.56%   |
| Suyin HP TrueVision HD                              | 1         | 2.56%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 2.56%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.56%   |
| Sunplus HP Universal Camera                         | 1         | 2.56%   |
| Sunplus HD WebCam                                   | 1         | 2.56%   |
| Silicon Motion NCM-G102                             | 1         | 2.56%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 2.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 2.56%   |
| Realtek USB Camera                                  | 1         | 2.56%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 2.56%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.56%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 2.56%   |
| Linux Foundation EEM Gadget                         | 1         | 2.56%   |
| Lenovo Integrated Webcam                            | 1         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.56%   |
| IMC Networks Integrated Camera                      | 1         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.56%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.56%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.56%   |
| Chicony HP HD Camera                                | 1         | 2.56%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.56%   |
| Chicony CNF8243 Webcam                              | 1         | 2.56%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.56%   |
| Acer BisonCam, NB Pro                               | 1         | 2.56%   |

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
| 0     | 57        | 60.64%  |
| 1     | 23        | 24.47%  |
| 2     | 9         | 9.57%   |
| 3     | 3         | 3.19%   |
| 5     | 1         | 1.06%   |
| 4     | 1         | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 25.45%  |
| Fingerprint reader       | 7         | 12.73%  |
| Communication controller | 7         | 12.73%  |
| Net/wireless             | 5         | 9.09%   |
| Modem                    | 5         | 9.09%   |
| Network                  | 3         | 5.45%   |
| Unassigned class         | 2         | 3.64%   |
| Sound                    | 2         | 3.64%   |
| Multimedia controller    | 2         | 3.64%   |
| Chipcard                 | 2         | 3.64%   |
| Camera                   | 2         | 3.64%   |
| Unclassified device      | 1         | 1.82%   |
| Storage                  | 1         | 1.82%   |
| Net/ethernet             | 1         | 1.82%   |
| Bluetooth                | 1         | 1.82%   |


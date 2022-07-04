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

Total: 104

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Alpine 3.12.0               | 11        | 12.94%  |
| Alpine 3.15.0               | 10        | 11.76%  |
| Alpine 3.16.0               | 7         | 8.24%   |
| Alpine 3.15.0_alpha20210804 | 7         | 8.24%   |
| Alpine 3.14.0               | 5         | 5.88%   |
| Alpine 3.14.2               | 4         | 4.71%   |
| Alpine 3.13.0_alpha20200917 | 4         | 4.71%   |
| Alpine 3.13.0_alpha20200626 | 4         | 4.71%   |
| Alpine 3.11.2               | 4         | 4.71%   |
| Alpine 3.15.4               | 3         | 3.53%   |
| Alpine 3.13.1               | 3         | 3.53%   |
| Alpine 3.13.0_alpha20201218 | 3         | 3.53%   |
| Alpine 3.13.5               | 2         | 2.35%   |
| Alpine 3.13.2               | 2         | 2.35%   |
| Alpine 3.12.3               | 2         | 2.35%   |
| Alpine 3.8.4                | 1         | 1.18%   |
| Alpine 3.16.0_alpha20220328 | 1         | 1.18%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.18%   |
| Alpine 3.15.2               | 1         | 1.18%   |
| Alpine 3.15.0_rc5           | 1         | 1.18%   |
| Alpine 3.14.3               | 1         | 1.18%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.18%   |
| Alpine 3.13.6               | 1         | 1.18%   |
| Alpine 3.13.3               | 1         | 1.18%   |
| Alpine 3.13.0_rc2           | 1         | 1.18%   |
| Alpine 3.12.7               | 1         | 1.18%   |
| Alpine 3.12.1               | 1         | 1.18%   |
| Alpine 3.12.0_rc1           | 1         | 1.18%   |
| Alpine 3.11.5               | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 9.3%    |
| 5.15.16-0-lts          | 3         | 3.49%   |
| 5.10.61-0-lts          | 3         | 3.49%   |
| 5.4.84-0-lts           | 2         | 2.33%   |
| 5.4.83-0-lts           | 2         | 2.33%   |
| 5.17.9-0-edge          | 2         | 2.33%   |
| 5.15.47-0-lts          | 2         | 2.33%   |
| 5.15.41-0-lts          | 2         | 2.33%   |
| 5.15.4-0-lts           | 2         | 2.33%   |
| 5.15.12-0-lts          | 2         | 2.33%   |
| 5.10.68-0-lts          | 2         | 2.33%   |
| 5.10.16-0-lts          | 2         | 2.33%   |
| 5.8.12-0-edge          | 1         | 1.16%   |
| 5.8.0                  | 1         | 1.16%   |
| 5.7.4                  | 1         | 1.16%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.16%   |
| 5.4.99                 | 1         | 1.16%   |
| 5.4.73-0-lts           | 1         | 1.16%   |
| 5.4.72-0-lts           | 1         | 1.16%   |
| 5.4.65-0-lts           | 1         | 1.16%   |
| 5.4.64-0-lts           | 1         | 1.16%   |
| 5.4.6-0-lts            | 1         | 1.16%   |
| 5.4.58-0-lts           | 1         | 1.16%   |
| 5.4.57-0-lts           | 1         | 1.16%   |
| 5.4.46-0-lts           | 1         | 1.16%   |
| 5.4.27-0-lts           | 1         | 1.16%   |
| 5.4.111-0-lts          | 1         | 1.16%   |
| 5.4.0-77-generic       | 1         | 1.16%   |
| 5.17.3-0-edge          | 1         | 1.16%   |
| 5.17.0-0-edge          | 1         | 1.16%   |
| 5.16.12-may            | 1         | 1.16%   |
| 5.16.1-may             | 1         | 1.16%   |
| 5.15.46-1-lts          | 1         | 1.16%   |
| 5.15.38-0-lts          | 1         | 1.16%   |
| 5.15.37-0-lts          | 1         | 1.16%   |
| 5.15.34                | 1         | 1.16%   |
| 5.15.30-0-lts          | 1         | 1.16%   |
| 5.15.28-0-lts          | 1         | 1.16%   |
| 5.15.26-0-lts          | 1         | 1.16%   |
| 5.15.17-0-lts          | 1         | 1.16%   |
| 5.14.8-0-edge          | 1         | 1.16%   |
| 5.13.0-0-edge          | 1         | 1.16%   |
| 5.12.8-0-edge          | 1         | 1.16%   |
| 5.10.83-v8             | 1         | 1.16%   |
| 5.10.81                | 1         | 1.16%   |
| 5.10.72-1-lts          | 1         | 1.16%   |
| 5.10.70-0-lts          | 1         | 1.16%   |
| 5.10.69-0-lts          | 1         | 1.16%   |
| 5.10.66-0-lts          | 1         | 1.16%   |
| 5.10.5-0-lts           | 1         | 1.16%   |
| 5.10.44-0-lts          | 1         | 1.16%   |
| 5.10.43-0-lts          | 1         | 1.16%   |
| 5.10.42-0-legacy       | 1         | 1.16%   |
| 5.10.4-0-lts           | 1         | 1.16%   |
| 5.10.38-0-lts          | 1         | 1.16%   |
| 5.10.29-0-lts          | 1         | 1.16%   |
| 5.10.24-0-lts          | 1         | 1.16%   |
| 5.10.12-0-lts          | 1         | 1.16%   |
| 5.10.11-0-lts          | 1         | 1.16%   |
| 5.10.108               | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.43   | 8         | 9.3%    |
| 5.15.16  | 3         | 3.49%   |
| 5.10.61  | 3         | 3.49%   |
| 5.4.84   | 2         | 2.33%   |
| 5.4.83   | 2         | 2.33%   |
| 5.17.9   | 2         | 2.33%   |
| 5.15.47  | 2         | 2.33%   |
| 5.15.41  | 2         | 2.33%   |
| 5.15.4   | 2         | 2.33%   |
| 5.15.12  | 2         | 2.33%   |
| 5.10.68  | 2         | 2.33%   |
| 5.10.16  | 2         | 2.33%   |
| 5.8.12   | 1         | 1.16%   |
| 5.8.0    | 1         | 1.16%   |
| 5.7.4    | 1         | 1.16%   |
| 5.6.2    | 1         | 1.16%   |
| 5.4.99   | 1         | 1.16%   |
| 5.4.73   | 1         | 1.16%   |
| 5.4.72   | 1         | 1.16%   |
| 5.4.65   | 1         | 1.16%   |
| 5.4.64   | 1         | 1.16%   |
| 5.4.6    | 1         | 1.16%   |
| 5.4.58   | 1         | 1.16%   |
| 5.4.57   | 1         | 1.16%   |
| 5.4.46   | 1         | 1.16%   |
| 5.4.27   | 1         | 1.16%   |
| 5.4.111  | 1         | 1.16%   |
| 5.4.0    | 1         | 1.16%   |
| 5.17.3   | 1         | 1.16%   |
| 5.17.0   | 1         | 1.16%   |
| 5.16.12  | 1         | 1.16%   |
| 5.16.1   | 1         | 1.16%   |
| 5.15.46  | 1         | 1.16%   |
| 5.15.38  | 1         | 1.16%   |
| 5.15.37  | 1         | 1.16%   |
| 5.15.34  | 1         | 1.16%   |
| 5.15.30  | 1         | 1.16%   |
| 5.15.28  | 1         | 1.16%   |
| 5.15.26  | 1         | 1.16%   |
| 5.15.17  | 1         | 1.16%   |
| 5.14.8   | 1         | 1.16%   |
| 5.13.0   | 1         | 1.16%   |
| 5.12.8   | 1         | 1.16%   |
| 5.10.83  | 1         | 1.16%   |
| 5.10.81  | 1         | 1.16%   |
| 5.10.72  | 1         | 1.16%   |
| 5.10.70  | 1         | 1.16%   |
| 5.10.69  | 1         | 1.16%   |
| 5.10.66  | 1         | 1.16%   |
| 5.10.5   | 1         | 1.16%   |
| 5.10.44  | 1         | 1.16%   |
| 5.10.43  | 1         | 1.16%   |
| 5.10.42  | 1         | 1.16%   |
| 5.10.4   | 1         | 1.16%   |
| 5.10.38  | 1         | 1.16%   |
| 5.10.29  | 1         | 1.16%   |
| 5.10.24  | 1         | 1.16%   |
| 5.10.12  | 1         | 1.16%   |
| 5.10.11  | 1         | 1.16%   |
| 5.10.108 | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 28.05%  |
| 5.10    | 23        | 28.05%  |
| 5.15    | 19        | 23.17%  |
| 5.17    | 4         | 4.88%   |
| 3.10    | 3         | 3.66%   |
| 5.8     | 2         | 2.44%   |
| 5.7     | 1         | 1.22%   |
| 5.6     | 1         | 1.22%   |
| 5.16    | 1         | 1.22%   |
| 5.14    | 1         | 1.22%   |
| 5.13    | 1         | 1.22%   |
| 5.12    | 1         | 1.22%   |
| 4.4     | 1         | 1.22%   |
| 4.14    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 67        | 84.81%  |
| i686    | 9         | 11.39%  |
| i586    | 1         | 1.27%   |
| armv7l  | 1         | 1.27%   |
| aarch64 | 1         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 84.81%  |
| XFCE    | 4         | 5.06%   |
| GNOME   | 4         | 5.06%   |
| sway    | 1         | 1.27%   |
| KDE5    | 1         | 1.27%   |
| KDE     | 1         | 1.27%   |
| i3      | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 61.73%  |
| X11     | 24        | 29.63%  |
| Wayland | 6         | 7.41%   |
| Tty     | 1         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 85%     |
| LightDM | 8         | 10%     |
| XDM     | 1         | 1.25%   |
| SDDM    | 1         | 1.25%   |
| LXDM    | 1         | 1.25%   |
| GDM     | 1         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 46        | 56.79%  |
| Unknown | 27        | 33.33%  |
| en_US   | 5         | 6.17%   |
| ru_RU   | 2         | 2.47%   |
| en_GB   | 1         | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 55        | 69.62%  |
| EFI  | 24        | 30.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 79.01%  |
| Overlay | 5         | 6.17%   |
| Btrfs   | 5         | 6.17%   |
| Tmpfs   | 3         | 3.7%    |
| Unknown | 2         | 2.47%   |
| F2fs    | 1         | 1.23%   |
| Ext2    | 1         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 56.63%  |
| GPT     | 24        | 28.92%  |
| MBR     | 12        | 14.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 89.87%  |
| Yes       | 8         | 10.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 91.25%  |
| Yes       | 7         | 8.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 14        | 17.72%  |
| Dell                    | 12        | 15.19%  |
| ASUSTek Computer        | 11        | 13.92%  |
| Lenovo                  | 9         | 11.39%  |
| Acer                    | 4         | 5.06%   |
| IBM                     | 3         | 3.8%    |
| MSI                     | 2         | 2.53%   |
| Intel                   | 2         | 2.53%   |
| Gigabyte Technology     | 2         | 2.53%   |
| ASRock                  | 2         | 2.53%   |
| Unknown                 | 2         | 2.53%   |
| VIA Technologies        | 1         | 1.27%   |
| Synology                | 1         | 1.27%   |
| Supermicro              | 1         | 1.27%   |
| Sony                    | 1         | 1.27%   |
| Shuttle                 | 1         | 1.27%   |
| Raspberry Pi Foundation | 1         | 1.27%   |
| Pegatron                | 1         | 1.27%   |
| Haier                   | 1         | 1.27%   |
| Google                  | 1         | 1.27%   |
| Gateway                 | 1         | 1.27%   |
| Fujitsu                 | 1         | 1.27%   |
| Fanless Mini PC         | 1         | 1.27%   |
| F5 Networks             | 1         | 1.27%   |
| eMachines               | 1         | 1.27%   |
| Apple                   | 1         | 1.27%   |
| AMI                     | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP ProLiant DL360 G6                     | 2         | 2.53%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 2.53%   |
| ASUS All Series                          | 2         | 2.53%   |
| Unknown                                  | 2         | 2.53%   |
| VIA KM266APro-835                        | 1         | 1.27%   |
| Synology DS1019+                         | 1         | 1.27%   |
| Supermicro X10SLL-F                      | 1         | 1.27%   |
| Sony VGN-UX27GN                          | 1         | 1.27%   |
| Shuttle DS81D                            | 1         | 1.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 1.27%   |
| Pegatron Deepcam                         | 1         | 1.27%   |
| MSI MS-7877                              | 1         | 1.27%   |
| MSI GL72M 7REX                           | 1         | 1.27%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.27%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.27%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.27%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.27%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.27%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 1.27%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.27%   |
| Lenovo H535 10117                        | 1         | 1.27%   |
| Intel NUC6i7KYB H90766-406               | 1         | 1.27%   |
| Intel Merrifield                         | 1         | 1.27%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.27%   |
| IBM 26446AG                              | 1         | 1.27%   |
| IBM 264070A                              | 1         | 1.27%   |
| HP ZBook 15 G5                           | 1         | 1.27%   |
| HP Stream 7 Tablet                       | 1         | 1.27%   |
| HP ProLiant MicroServer Gen8             | 1         | 1.27%   |
| HP ProBook 4310s                         | 1         | 1.27%   |
| HP Mini 110-3500                         | 1         | 1.27%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.27%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.27%   |
| HP EliteBook 8460p                       | 1         | 1.27%   |
| HP EliteBook 2740p                       | 1         | 1.27%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.27%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.27%   |
| HP 23-p030na                             | 1         | 1.27%   |
| Haier U144S                              | 1         | 1.27%   |
| Google Samus                             | 1         | 1.27%   |
| Gateway MX3631m                          | 1         | 1.27%   |
| Fujitsu PRIMERGY TX100 S2                | 1         | 1.27%   |
| Fanless Mini PC Quieter2                 | 1         | 1.27%   |
| F5 Networks C117                         | 1         | 1.27%   |
| eMachines EL1352G                        | 1         | 1.27%   |
| Dell XPS 15 7590                         | 1         | 1.27%   |
| Dell XPS 13 7390 2-in-1                  | 1         | 1.27%   |
| Dell Studio 1747                         | 1         | 1.27%   |
| Dell PowerEdge T640                      | 1         | 1.27%   |
| Dell PowerEdge R510                      | 1         | 1.27%   |
| Dell OptiPlex 755                        | 1         | 1.27%   |
| Dell OptiPlex 3020M                      | 1         | 1.27%   |
| Dell OptiPlex 3010                       | 1         | 1.27%   |
| Dell Inspiron MM061                      | 1         | 1.27%   |
| Dell Inspiron 5566                       | 1         | 1.27%   |
| Dell Inspiron 3647                       | 1         | 1.27%   |
| Dell Inspiron 3180                       | 1         | 1.27%   |
| ASUS ZenBook UX431FA                     | 1         | 1.27%   |
| ASUS X555LAB                             | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 5         | 6.33%   |
| Dell Inspiron            | 4         | 5.06%   |
| Acer Aspire              | 4         | 5.06%   |
| HP ProLiant              | 3         | 3.8%    |
| HP EliteBook             | 3         | 3.8%    |
| Dell OptiPlex            | 3         | 3.8%    |
| Gigabyte Z490I           | 2         | 2.53%   |
| Dell XPS                 | 2         | 2.53%   |
| Dell PowerEdge           | 2         | 2.53%   |
| ASUS All                 | 2         | 2.53%   |
| Unknown                  | 2         | 2.53%   |
| VIA KM266APro-835        | 1         | 1.27%   |
| Synology DS1019+         | 1         | 1.27%   |
| Supermicro X10SLL-F      | 1         | 1.27%   |
| Sony VGN-UX27GN          | 1         | 1.27%   |
| Shuttle DS81D            | 1         | 1.27%   |
| RPi Raspberry            | 1         | 1.27%   |
| Pegatron Deepcam         | 1         | 1.27%   |
| MSI MS-7877              | 1         | 1.27%   |
| MSI GL72M                | 1         | 1.27%   |
| Lenovo Yoga              | 1         | 1.27%   |
| Lenovo ThinkCentre       | 1         | 1.27%   |
| Lenovo IdeaPad           | 1         | 1.27%   |
| Lenovo H535              | 1         | 1.27%   |
| Intel NUC6i7KYB          | 1         | 1.27%   |
| Intel Merrifield         | 1         | 1.27%   |
| IBM ThinkPad             | 1         | 1.27%   |
| IBM 26446AG              | 1         | 1.27%   |
| IBM 264070A              | 1         | 1.27%   |
| HP ZBook                 | 1         | 1.27%   |
| HP Stream                | 1         | 1.27%   |
| HP ProBook               | 1         | 1.27%   |
| HP Mini                  | 1         | 1.27%   |
| HP Laptop                | 1         | 1.27%   |
| HP ENVY                  | 1         | 1.27%   |
| HP Compaq                | 1         | 1.27%   |
| HP 23-p030na             | 1         | 1.27%   |
| Haier U144S              | 1         | 1.27%   |
| Google Samus             | 1         | 1.27%   |
| Gateway MX3631m          | 1         | 1.27%   |
| Fujitsu PRIMERGY         | 1         | 1.27%   |
| Fanless Mini PC Quieter2 | 1         | 1.27%   |
| F5 Networks C117         | 1         | 1.27%   |
| eMachines EL1352G        | 1         | 1.27%   |
| Dell Studio              | 1         | 1.27%   |
| ASUS ZenBook             | 1         | 1.27%   |
| ASUS X555LAB             | 1         | 1.27%   |
| ASUS X550EA              | 1         | 1.27%   |
| ASUS X200MA              | 1         | 1.27%   |
| ASUS TS10                | 1         | 1.27%   |
| ASUS PRIME               | 1         | 1.27%   |
| ASUS P8H67-V             | 1         | 1.27%   |
| ASUS N10Jc               | 1         | 1.27%   |
| ASUS E502SA              | 1         | 1.27%   |
| ASRock J3455M            | 1         | 1.27%   |
| ASRock D1800B-ITX        | 1         | 1.27%   |
| Apple Macmini6           | 1         | 1.27%   |
| AMI Aptio                | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 14        | 17.72%  |
| 2019    | 7         | 8.86%   |
| 2018    | 7         | 8.86%   |
| 2010    | 6         | 7.59%   |
| 2016    | 5         | 6.33%   |
| 2009    | 5         | 6.33%   |
| 2017    | 4         | 5.06%   |
| 2015    | 4         | 5.06%   |
| 2012    | 4         | 5.06%   |
| 2021    | 3         | 3.8%    |
| 2020    | 3         | 3.8%    |
| 2013    | 3         | 3.8%    |
| 2006    | 3         | 3.8%    |
| Unknown | 3         | 3.8%    |
| 2011    | 2         | 2.53%   |
| 2007    | 2         | 2.53%   |
| 2008    | 1         | 1.27%   |
| 2005    | 1         | 1.27%   |
| 2004    | 1         | 1.27%   |
| 1999    | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 42        | 53.16%  |
| Desktop        | 21        | 26.58%  |
| Server         | 6         | 7.59%   |
| Mini pc        | 5         | 6.33%   |
| Tablet         | 2         | 2.53%   |
| System on chip | 1         | 1.27%   |
| Convertible    | 1         | 1.27%   |
| All in one     | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 98.73%  |
| Yes  | 1         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 17        | 20.73%  |
| 4.01-8.0        | 15        | 18.29%  |
| 16.01-24.0      | 14        | 17.07%  |
| 8.01-16.0       | 11        | 13.41%  |
| 0.51-1.0        | 7         | 8.54%   |
| 1.01-2.0        | 5         | 6.1%    |
| 32.01-64.0      | 4         | 4.88%   |
| 64.01-256.0     | 3         | 3.66%   |
| 0.01-0.5        | 3         | 3.66%   |
| 2.01-3.0        | 2         | 2.44%   |
| More than 256.0 | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 24        | 28.57%  |
| 1.01-2.0  | 15        | 17.86%  |
| 0.51-1.0  | 15        | 17.86%  |
| 3.01-4.0  | 9         | 10.71%  |
| 4.01-8.0  | 6         | 7.14%   |
| 2.01-3.0  | 6         | 7.14%   |
| 8.01-16.0 | 4         | 4.76%   |
| Unknown   | 3         | 3.57%   |
| 0         | 2         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 63.41%  |
| 2      | 16        | 19.51%  |
| 4      | 4         | 4.88%   |
| 3      | 4         | 4.88%   |
| 14     | 2         | 2.44%   |
| 10     | 1         | 1.22%   |
| 7      | 1         | 1.22%   |
| 5      | 1         | 1.22%   |
| 0      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 75.95%  |
| Yes       | 19        | 24.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 84.81%  |
| No        | 12        | 15.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 63.29%  |
| No        | 29        | 36.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 55.7%   |
| Yes       | 35        | 44.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 21        | 26.25%  |
| Russia       | 9         | 11.25%  |
| Canada       | 8         | 10%     |
| UK           | 7         | 8.75%   |
| Germany      | 5         | 6.25%   |
| Sweden       | 4         | 5%      |
| Spain        | 2         | 2.5%    |
| Norway       | 2         | 2.5%    |
| Guatemala    | 2         | 2.5%    |
| Brazil       | 2         | 2.5%    |
| Venezuela    | 1         | 1.25%   |
| Ukraine      | 1         | 1.25%   |
| Switzerland  | 1         | 1.25%   |
| South Korea  | 1         | 1.25%   |
| South Africa | 1         | 1.25%   |
| Slovakia     | 1         | 1.25%   |
| Portugal     | 1         | 1.25%   |
| Poland       | 1         | 1.25%   |
| Pakistan     | 1         | 1.25%   |
| Mexico       | 1         | 1.25%   |
| Italy        | 1         | 1.25%   |
| Indonesia    | 1         | 1.25%   |
| France       | 1         | 1.25%   |
| Egypt        | 1         | 1.25%   |
| Czechia      | 1         | 1.25%   |
| China        | 1         | 1.25%   |
| Austria      | 1         | 1.25%   |
| Australia    | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| St Petersburg    | 6         | 7.41%   |
| Manitowoc        | 5         | 6.17%   |
| Vernon           | 2         | 2.47%   |
| Stratford        | 2         | 2.47%   |
| Springfield      | 2         | 2.47%   |
| Guatemala City   | 2         | 2.47%   |
| Gothenburg       | 2         | 2.47%   |
| Fulham           | 2         | 2.47%   |
| As               | 2         | 2.47%   |
| Zurich           | 1         | 1.23%   |
| Vancouver        | 1         | 1.23%   |
| Tymovskoye       | 1         | 1.23%   |
| Topeka           | 1         | 1.23%   |
| Thame            | 1         | 1.23%   |
| Tampa            | 1         | 1.23%   |
| Sydney           | 1         | 1.23%   |
| Stockholm        | 1         | 1.23%   |
| Stewartstown     | 1         | 1.23%   |
| Sisteron         | 1         | 1.23%   |
| Semily           | 1         | 1.23%   |
| Sao Paulo        | 1         | 1.23%   |
| San Mateo        | 1         | 1.23%   |
| Salzburg         | 1         | 1.23%   |
| Rzeszów         | 1         | 1.23%   |
| Rostock          | 1         | 1.23%   |
| Redwood City     | 1         | 1.23%   |
| Purdys           | 1         | 1.23%   |
| Plymouth         | 1         | 1.23%   |
| Penza            | 1         | 1.23%   |
| Ottawa           | 1         | 1.23%   |
| Oakville         | 1         | 1.23%   |
| Nuremberg        | 1         | 1.23%   |
| Merrill          | 1         | 1.23%   |
| Mérida          | 1         | 1.23%   |
| Mankato          | 1         | 1.23%   |
| Malmo            | 1         | 1.23%   |
| Madrid           | 1         | 1.23%   |
| London           | 1         | 1.23%   |
| Lindavista Norte | 1         | 1.23%   |
| Lincoln          | 1         | 1.23%   |
| Leipzig          | 1         | 1.23%   |
| Larkspur         | 1         | 1.23%   |
| Lahore           | 1         | 1.23%   |
| Kirkland         | 1         | 1.23%   |
| Kharkiv          | 1         | 1.23%   |
| Kaliningrad      | 1         | 1.23%   |
| Johannesburg     | 1         | 1.23%   |
| Jember           | 1         | 1.23%   |
| Hampstead        | 1         | 1.23%   |
| Hamburg          | 1         | 1.23%   |
| Goyang-si        | 1         | 1.23%   |
| Funchal          | 1         | 1.23%   |
| Franklin         | 1         | 1.23%   |
| Dallas           | 1         | 1.23%   |
| Cologne          | 1         | 1.23%   |
| Chapel Hill      | 1         | 1.23%   |
| Cairo            | 1         | 1.23%   |
| Brockport        | 1         | 1.23%   |
| Bratislava       | 1         | 1.23%   |
| Boucherville     | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 21     | 13.33%  |
| WDC                 | 13        | 37     | 12.38%  |
| Seagate             | 11        | 29     | 10.48%  |
| Unknown             | 9         | 11     | 8.57%   |
| Hitachi             | 8         | 8      | 7.62%   |
| HGST                | 6         | 6      | 5.71%   |
| Toshiba             | 5         | 6      | 4.76%   |
| Intel               | 5         | 9      | 4.76%   |
| Crucial             | 5         | 11     | 4.76%   |
| SK hynix            | 4         | 6      | 3.81%   |
| Kingston            | 4         | 5      | 3.81%   |
| Transcend           | 2         | 2      | 1.9%    |
| SanDisk             | 2         | 2      | 1.9%    |
| LITEON              | 2         | 2      | 1.9%    |
| A-DATA Technology   | 2         | 2      | 1.9%    |
| STEC                | 1         | 1      | 0.95%   |
| SPCC                | 1         | 1      | 0.95%   |
| NETAPP              | 1         | 1      | 0.95%   |
| Lexar               | 1         | 1      | 0.95%   |
| Kingmax             | 1         | 1      | 0.95%   |
| KC600               | 1         | 1      | 0.95%   |
| JMicron Technology  | 1         | 1      | 0.95%   |
| Intenso             | 1         | 1      | 0.95%   |
| IBM                 | 1         | 1      | 0.95%   |
| EMTEC               | 1         | 1      | 0.95%   |
| Dell                | 1         | 1      | 0.95%   |
| China               | 1         | 1      | 0.95%   |
| AMD                 | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WD3000BLFS-60YBU2 304GB               | 2         | 1.75%   |
| Unknown MMC Card  16GB                    | 2         | 1.75%   |
| Seagate ST4000VN008-2DR1 4TB              | 2         | 1.75%   |
| Samsung SSD 960 EVO 500GB                 | 2         | 1.75%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.75%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.88%   |
| WDC WDS250G2B0A 250GB SSD                 | 1         | 0.88%   |
| WDC WD80EMAZ-00WJTA0 8TB                  | 1         | 0.88%   |
| WDC WD80EFAX-68LHPN0 8TB                  | 1         | 0.88%   |
| WDC WD800AAJS-00 80GB                     | 1         | 0.88%   |
| WDC WD5003ABYZ-0 500GB                    | 1         | 0.88%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 0.88%   |
| WDC WD20EZRZ-00Z 2TB                      | 1         | 0.88%   |
| WDC WD140EDFZ-11A0VA0 14TB                | 1         | 0.88%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.88%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 0.88%   |
| WDC WD10EZEX-21M2NA0 1TB                  | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 0.88%   |
| Unknown SD64G  64GB                       | 1         | 0.88%   |
| Unknown SD32G  32GB                       | 1         | 0.88%   |
| Unknown SD16G  32GB                       | 1         | 0.88%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 0.88%   |
| Unknown MMC Card  4GB                     | 1         | 0.88%   |
| Unknown MMC Card  32GB                    | 1         | 0.88%   |
| Unknown MMC Card                          | 1         | 0.88%   |
| Transcend TS128GSSD420I 128GB             | 1         | 0.88%   |
| Transcend SSD 1GB                         | 1         | 0.88%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.88%   |
| Toshiba MK4009GAL 40GB                    | 1         | 0.88%   |
| Toshiba MK3252GS 320GB                    | 1         | 0.88%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 0.88%   |
| Toshiba KBG40ZPZ512G NVMe 512GB           | 1         | 0.88%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD       | 1         | 0.88%   |
| STEC SDT5A-S200SS 200GB                   | 1         | 0.88%   |
| SPCC Solid State Disk 256GB               | 1         | 0.88%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 0.88%   |
| SK hynix SC300 M.2 2280 256 256GB SSD     | 1         | 0.88%   |
| SK hynix HFS480G3H2X069N 480GB            | 1         | 0.88%   |
| SK hynix HBG4e  32GB                      | 1         | 0.88%   |
| Seagate ST98823A 80GB                     | 1         | 0.88%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 0.88%   |
| Seagate ST4000VN008-2DR166 4TB            | 1         | 0.88%   |
| Seagate ST380815AS 80GB                   | 1         | 0.88%   |
| Seagate ST3500418AS 500GB                 | 1         | 0.88%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 0.88%   |
| Seagate ST2000DL001-9VT1 2TB              | 1         | 0.88%   |
| Seagate ST1000LM048-2E71 1TB              | 1         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 0.88%   |
| SanDisk SSD PLUS 480GB                    | 1         | 0.88%   |
| SanDisk SDSA6MM 16GB SSD                  | 1         | 0.88%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 0.88%   |
| Samsung SSD 980 500GB                     | 1         | 0.88%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 0.88%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 0.88%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 0.88%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 0.88%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 0.88%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 29     | 26.19%  |
| WDC                 | 10        | 33     | 23.81%  |
| Hitachi             | 8         | 8      | 19.05%  |
| HGST                | 6         | 6      | 14.29%  |
| Toshiba             | 3         | 3      | 7.14%   |
| Samsung Electronics | 2         | 4      | 4.76%   |
| JMicron Technology  | 1         | 1      | 2.38%   |
| IBM                 | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 13.16%  |
| Crucial             | 5         | 11     | 13.16%  |
| Kingston            | 4         | 5      | 10.53%  |
| Intel               | 3         | 5      | 7.89%   |
| WDC                 | 2         | 2      | 5.26%   |
| Transcend           | 2         | 2      | 5.26%   |
| SK hynix            | 2         | 3      | 5.26%   |
| SanDisk             | 2         | 2      | 5.26%   |
| LITEON              | 2         | 2      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| SPCC                | 1         | 1      | 2.63%   |
| Lexar               | 1         | 1      | 2.63%   |
| Kingmax             | 1         | 1      | 2.63%   |
| KC600               | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| EMTEC               | 1         | 1      | 2.63%   |
| Dell                | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| AMD                 | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 39        | 85     | 39.8%   |
| SSD     | 35        | 50     | 35.71%  |
| NVMe    | 15        | 22     | 15.31%  |
| MMC     | 8         | 11     | 8.16%   |
| Unknown | 1         | 2      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 130    | 68.54%  |
| NVMe | 15        | 22     | 16.85%  |
| MMC  | 8         | 11     | 8.99%   |
| SAS  | 5         | 7      | 5.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 83     | 71.23%  |
| 0.51-1.0   | 12        | 15     | 16.44%  |
| 1.01-2.0   | 3         | 5      | 4.11%   |
| 4.01-10.0  | 3         | 19     | 4.11%   |
| 3.01-4.0   | 2         | 9      | 2.74%   |
| 10.01-20.0 | 1         | 4      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 19.51%  |
| 1-20           | 16        | 19.51%  |
| Unknown        | 11        | 13.41%  |
| 21-50          | 10        | 12.2%   |
| 251-500        | 8         | 9.76%   |
| 501-1000       | 8         | 9.76%   |
| 1001-2000      | 5         | 6.1%    |
| 2001-3000      | 3         | 3.66%   |
| 51-100         | 3         | 3.66%   |
| More than 3000 | 2         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 50        | 61.73%  |
| Unknown   | 11        | 13.58%  |
| 51-100    | 6         | 7.41%   |
| 21-50     | 4         | 4.94%   |
| 251-500   | 3         | 3.7%    |
| 101-250   | 3         | 3.7%    |
| 501-1000  | 3         | 3.7%    |
| 1001-2000 | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB       | 2         | 14     | 14.29%  |
| Toshiba MK4009GAL 40GB            | 1         | 1      | 7.14%   |
| Toshiba MK3252GS 320GB            | 1         | 1      | 7.14%   |
| Seagate ST2000LM015-2E81 2TB      | 1         | 1      | 7.14%   |
| SanDisk SDSA6MM 16GB SSD          | 1         | 1      | 7.14%   |
| Samsung Electronics SP0411N 40GB  | 1         | 2      | 7.14%   |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 7.14%   |
| Kingmax SSD 120G                  | 1         | 1      | 7.14%   |
| Hitachi HTS725025A9A364 250GB     | 1         | 1      | 7.14%   |
| Hitachi HTS723232A7A364 320GB     | 1         | 1      | 7.14%   |
| Hitachi HTS72101 99GB             | 1         | 1      | 7.14%   |
| Hitachi HTC426040G9AT00 40GB      | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 28.57%  |
| WDC                 | 2         | 14     | 14.29%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 4      | 14.29%  |
| Seagate             | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Kingmax             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 33.33%  |
| WDC                 | 2         | 14     | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Samsung Electronics | 2         | 4      | 16.67%  |
| Seagate             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 26     | 85.71%  |
| SSD  | 2         | 2      | 14.29%  |

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
| Works    | 52        | 113    | 59.77%  |
| Detected | 21        | 29     | 24.14%  |
| Malfunc  | 14        | 28     | 16.09%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 56        | 62.22%  |
| Samsung Electronics          | 8         | 8.89%   |
| AMD                          | 8         | 8.89%   |
| LSI Logic / Symbios Logic    | 3         | 3.33%   |
| Hewlett-Packard              | 2         | 2.22%   |
| Adaptec                      | 2         | 2.22%   |
| VIA Technologies             | 1         | 1.11%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| SK hynix                     | 1         | 1.11%   |
| SanDisk                      | 1         | 1.11%   |
| Nvidia                       | 1         | 1.11%   |
| Micron/Crucial Technology    | 1         | 1.11%   |
| Marvell Technology Group     | 1         | 1.11%   |
| KIOXIA                       | 1         | 1.11%   |
| Broadcom / LSI               | 1         | 1.11%   |
| ASMedia Technology           | 1         | 1.11%   |
| ADATA Technology             | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 7.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 6.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 6.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 4.12%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 3         | 3.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 2.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 2.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 2.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.06%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.06%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 2         | 2.06%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.03%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.03%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.03%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.03%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.03%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.03%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.03%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 1.03%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.03%   |
| Intel SSD 600P Series                                                            | 1         | 1.03%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.03%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 1.03%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 1.03%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1         | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.03%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.03%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 1.03%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.03%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                          | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                          | 1         | 1.03%   |
| HP Smart Array Gen8 Controllers                                                  | 1         | 1.03%   |
| HP Smart Array G6 controllers                                                    | 1         | 1.03%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 56.67%  |
| NVMe | 15        | 16.67%  |
| IDE  | 12        | 13.33%  |
| RAID | 9         | 10%     |
| SAS  | 3         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 83.75%  |
| AMD    | 11        | 13.75%  |
| ARM    | 2         | 2.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz         | 2         | 2.5%    |
| Intel Core i9-10900 CPU @ 2.80GHz      | 2         | 2.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2         | 2.5%    |
| Intel Core i5-4590T CPU @ 2.00GHz      | 2         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 2.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 2.5%    |
| Intel Celeron CPU J3455 @ 1.50GHz      | 2         | 2.5%    |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 2.5%    |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1         | 1.25%   |
| Intel Xeon E-2176M CPU @ 2.70GHz       | 1         | 1.25%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 1.25%   |
| Intel Xeon CPU L5630 @ 2.13GHz         | 1         | 1.25%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz   | 1         | 1.25%   |
| Intel Pentium M processor 1.60GHz      | 1         | 1.25%   |
| Intel Pentium M processor 1.50GHz      | 1         | 1.25%   |
| Intel Pentium III (Coppermine)         | 1         | 1.25%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1         | 1.25%   |
| Intel Pentium CPU N3710 @ 1.60GHz      | 1         | 1.25%   |
| Intel Pentium CPU D1508 @ 2.20GHz      | 1         | 1.25%   |
| Intel Mobile Pentium MMX               | 1         | 1.25%   |
| Intel Genuine CPU 4000 @ 500MHz        | 1         | 1.25%   |
| Intel Core Solo CPU U1500 @ 1.33GHz    | 1         | 1.25%   |
| Intel Core i9-9980HK CPU @ 2.40GHz     | 1         | 1.25%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 1.25%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz     | 1         | 1.25%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.25%   |
| Intel Core i7-3615QM CPU @ 2.30GHz     | 1         | 1.25%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.25%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz      | 1         | 1.25%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1         | 1.25%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.25%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.25%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz      | 1         | 1.25%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1         | 1.25%   |
| Intel Core i5-3317U CPU @ 1.70GHz      | 1         | 1.25%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz     | 1         | 1.25%   |
| Intel Core i5 CPU M 560 @ 2.67GHz      | 1         | 1.25%   |
| Intel Core i3-5020U CPU @ 2.20GHz      | 1         | 1.25%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 1         | 1.25%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1         | 1.25%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1         | 1.25%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz   | 1         | 1.25%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz   | 1         | 1.25%   |
| Intel Core 2 Duo CPU P7570 @ 2.26GHz   | 1         | 1.25%   |
| Intel Core 2 CPU T7200 @ 2.00GHz       | 1         | 1.25%   |
| Intel Celeron M processor 1.00GHz      | 1         | 1.25%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 1         | 1.25%   |
| Intel Celeron CPU N3350 @ 1.10GHz      | 1         | 1.25%   |
| Intel Celeron CPU N2830 @ 2.16GHz      | 1         | 1.25%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 1         | 1.25%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1         | 1.25%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1         | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1         | 1.25%   |
| Intel Atom Processor E3930 @ 1.30GHz   | 1         | 1.25%   |
| Intel Atom CPU Z3735G @ 1.33GHz        | 1         | 1.25%   |
| Intel Atom CPU N270 @ 1.60GHz          | 1         | 1.25%   |
| Intel Atom CPU E3825 @ 1.33GHz         | 1         | 1.25%   |
| ARM Processor                          | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 14        | 17.5%   |
| Intel Celeron      | 10        | 12.5%   |
| Intel Core i7      | 8         | 10%     |
| Intel Atom         | 7         | 8.75%   |
| Intel Xeon         | 6         | 7.5%    |
| Other              | 5         | 6.25%   |
| Intel Core i3      | 4         | 5%      |
| Intel Core i9      | 3         | 3.75%   |
| Intel Core 2 Duo   | 3         | 3.75%   |
| Intel Pentium M    | 2         | 2.5%    |
| Intel Pentium      | 2         | 2.5%    |
| AMD A4             | 2         | 2.5%    |
| Intel Xeon Gold    | 1         | 1.25%   |
| Intel Pentium III  | 1         | 1.25%   |
| Intel Pentium Dual | 1         | 1.25%   |
| Intel Genuine      | 1         | 1.25%   |
| Intel Core Solo    | 1         | 1.25%   |
| Intel Core 2       | 1         | 1.25%   |
| Intel Celeron M    | 1         | 1.25%   |
| AMD Sempron        | 1         | 1.25%   |
| AMD Ryzen 7        | 1         | 1.25%   |
| AMD Ryzen 5        | 1         | 1.25%   |
| AMD FX             | 1         | 1.25%   |
| AMD A8             | 1         | 1.25%   |
| AMD A6             | 1         | 1.25%   |
| AMD A10            | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 36.25%  |
| 4       | 28        | 35%     |
| 1       | 11        | 13.75%  |
| 8       | 3         | 3.75%   |
| 12      | 2         | 2.5%    |
| 10      | 2         | 2.5%    |
| 6       | 2         | 2.5%    |
| 32      | 1         | 1.25%   |
| 3       | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 75        | 93.75%  |
| 2       | 4         | 5%      |
| Unknown | 1         | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 42        | 53.16%  |
| 2       | 36        | 45.57%  |
| Unknown | 1         | 1.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 46.91%  |
| Unknown        | 38        | 46.91%  |
| 32-bit         | 5         | 6.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 51.22%  |
| 0x306c3    | 5         | 6.1%    |
| 0x30678    | 4         | 4.88%   |
| 0x306a9    | 3         | 3.66%   |
| 0x206c2    | 3         | 3.66%   |
| 0x906ea    | 2         | 2.44%   |
| 0x506c9    | 2         | 2.44%   |
| 0x406c4    | 2         | 2.44%   |
| 0x206a7    | 2         | 2.44%   |
| 0x106e5    | 2         | 2.44%   |
| 0x106ca    | 2         | 2.44%   |
| 0x06006704 | 2         | 2.44%   |
| 0xa0655    | 1         | 1.22%   |
| 0x806eb    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x6fd      | 1         | 1.22%   |
| 0x6d8      | 1         | 1.22%   |
| 0x683      | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x306d4    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |
| 0x010000b6 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 9         | 11.25%  |
| KabyLake      | 8         | 10%     |
| Haswell       | 7         | 8.75%   |
| P6            | 5         | 6.25%   |
| Westmere      | 4         | 5%      |
| IvyBridge     | 4         | 5%      |
| Goldmont      | 4         | 5%      |
| Unknown       | 4         | 5%      |
| Skylake       | 3         | 3.75%   |
| SandyBridge   | 3         | 3.75%   |
| Penryn        | 3         | 3.75%   |
| Excavator     | 3         | 3.75%   |
| Broadwell     | 3         | 3.75%   |
| Bonnell       | 3         | 3.75%   |
| Piledriver    | 2         | 2.5%    |
| Nehalem       | 2         | 2.5%    |
| IceLake       | 2         | 2.5%    |
| Core          | 2         | 2.5%    |
| CometLake     | 2         | 2.5%    |
| Zen 2         | 1         | 1.25%   |
| Zen           | 1         | 1.25%   |
| Puma          | 1         | 1.25%   |
| K6            | 1         | 1.25%   |
| K10           | 1         | 1.25%   |
| Jaguar        | 1         | 1.25%   |
| Goldmont plus | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 52        | 61.9%   |
| AMD                        | 18        | 21.43%  |
| Nvidia                     | 6         | 7.14%   |
| Matrox Electronics Systems | 4         | 4.76%   |
| Neomagic                   | 2         | 2.38%   |
| VIA Technologies           | 1         | 1.19%   |
| ASPEED Technology          | 1         | 1.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 8.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 4.6%    |
| Intel HD Graphics 500                                                                    | 4         | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.45%   |
| AMD ES1000                                                                               | 3         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.3%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 2.3%    |
| Intel HD Graphics 5500                                                                   | 2         | 2.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.3%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 2.3%    |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.15%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.15%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.15%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.15%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.15%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.15%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.15%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.15%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.15%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.15%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.15%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.15%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.15%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.15%   |
| Intel Iris Pro Graphics 580                                                              | 1         | 1.15%   |
| Intel HD Graphics 630                                                                    | 1         | 1.15%   |
| Intel HD Graphics 620                                                                    | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.15%   |
| Intel Display controller                                                                 | 1         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.15%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 1.15%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 1.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.15%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.15%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.15%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1         | 1.15%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.15%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1         | 1.15%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.15%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.15%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.15%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 1.15%   |
| AMD Renoir                                                                               | 1         | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.15%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.15%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 43        | 53.75%  |
| 1 x AMD         | 16        | 20%     |
| Other           | 3         | 3.75%   |
| 2 x Intel       | 3         | 3.75%   |
| 1 x Matrox      | 3         | 3.75%   |
| Intel + Nvidia  | 3         | 3.75%   |
| 1 x Nvidia      | 2         | 2.5%    |
| 1 x Neomagic    | 2         | 2.5%    |
| 2 x AMD         | 1         | 1.25%   |
| 1 x VIA         | 1         | 1.25%   |
| Nvidia + Matrox | 1         | 1.25%   |
| Intel + AMD     | 1         | 1.25%   |
| 1 x ASPEED      | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 81.71%  |
| Unknown     | 13        | 15.85%  |
| Proprietary | 2         | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 84.81%  |
| 0.01-0.5   | 7         | 8.86%   |
| 1.01-2.0   | 2         | 2.53%   |
| 7.01-8.0   | 1         | 1.27%   |
| 3.01-4.0   | 1         | 1.27%   |
| 0.51-1.0   | 1         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 12.12%  |
| Samsung Electronics     | 7         | 10.61%  |
| LG Display              | 6         | 9.09%   |
| Dell                    | 5         | 7.58%   |
| Chimei Innolux          | 5         | 7.58%   |
| BOE                     | 4         | 6.06%   |
| AOC                     | 3         | 4.55%   |
| Acer                    | 3         | 4.55%   |
| LG Philips              | 2         | 3.03%   |
| Hewlett-Packard         | 2         | 3.03%   |
| Goldstar                | 2         | 3.03%   |
| Chi Mei Optoelectronics | 2         | 3.03%   |
| BenQ                    | 2         | 3.03%   |
| ViewSonic               | 1         | 1.52%   |
| Sony                    | 1         | 1.52%   |
| SKY                     | 1         | 1.52%   |
| Sharp                   | 1         | 1.52%   |
| ONN                     | 1         | 1.52%   |
| Mi                      | 1         | 1.52%   |
| Lenovo                  | 1         | 1.52%   |
| KVM                     | 1         | 1.52%   |
| InfoVision              | 1         | 1.52%   |
| HannStar                | 1         | 1.52%   |
| Envision                | 1         | 1.52%   |
| EDI                     | 1         | 1.52%   |
| DENON                   | 1         | 1.52%   |
| CSO                     | 1         | 1.52%   |
| CPT                     | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch         | 2         | 2.99%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch                 | 1         | 1.49%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                       | 1         | 1.49%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                     | 1         | 1.49%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                  | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1210x680mm 54.6-inch   | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch     | 1         | 1.49%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 1         | 1.49%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 1.49%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                         | 1         | 1.49%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.49%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 1.49%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 1.49%   |
| KVM LCD Monitor 1 7" KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.49%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 1.49%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 530x300mm 24.0-inch             | 1         | 1.49%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 477x268mm 21.5-inch         | 1         | 1.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.49%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 1.49%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.49%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 1.49%   |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                    | 1         | 1.49%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 1.49%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                        | 1         | 1.49%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                        | 1         | 1.49%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                        | 1         | 1.49%   |
| Dell E151FPb DELA005 1024x768 304x228mm 15.0-inch                        | 1         | 1.49%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                         | 1         | 1.49%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 1.49%   |
| CPT LCD Monitor CPT04E2 1024x600 222x130mm 10.1-inch                     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 1.49%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 1.49%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                       | 1         | 1.49%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch           | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 27.27%  |
| 1366x768 (WXGA)    | 17        | 25.76%  |
| 1280x1024 (SXGA)   | 4         | 6.06%   |
| 3840x2160 (4K)     | 3         | 4.55%   |
| 2560x1440 (QHD)    | 3         | 4.55%   |
| 1280x800 (WXGA)    | 3         | 4.55%   |
| 1024x600           | 3         | 4.55%   |
| 3440x1440          | 2         | 3.03%   |
| 1920x1200 (WUXGA)  | 2         | 3.03%   |
| 1680x1050 (WSXGA+) | 2         | 3.03%   |
| 1600x900 (HD+)     | 2         | 3.03%   |
| 2880x1800          | 1         | 1.52%   |
| 2560x1700          | 1         | 1.52%   |
| 2560x1080          | 1         | 1.52%   |
| 1440x900 (WXGA+)   | 1         | 1.52%   |
| 1360x768           | 1         | 1.52%   |
| 1280x768           | 1         | 1.52%   |
| 1024x768 (XGA)     | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 13        | 19.4%   |
| 13     | 8         | 11.94%  |
| 17     | 6         | 8.96%   |
| 14     | 5         | 7.46%   |
| 23     | 4         | 5.97%   |
| 27     | 3         | 4.48%   |
| 24     | 3         | 4.48%   |
| 21     | 3         | 4.48%   |
| 11     | 3         | 4.48%   |
| 10     | 3         | 4.48%   |
| 34     | 2         | 2.99%   |
| 31     | 2         | 2.99%   |
| 20     | 2         | 2.99%   |
| 19     | 2         | 2.99%   |
| 12     | 2         | 2.99%   |
| 65     | 1         | 1.49%   |
| 54     | 1         | 1.49%   |
| 40     | 1         | 1.49%   |
| 32     | 1         | 1.49%   |
| 29     | 1         | 1.49%   |
| 25     | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 37.31%  |
| 201-300     | 11        | 16.42%  |
| 501-600     | 10        | 14.93%  |
| 351-400     | 6         | 8.96%   |
| 401-500     | 5         | 7.46%   |
| 601-700     | 4         | 5.97%   |
| 701-800     | 3         | 4.48%   |
| 1001-1500   | 2         | 2.99%   |
| 801-900     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 72.13%  |
| 16/10 | 8         | 13.11%  |
| 5/4   | 4         | 6.56%   |
| 21/9  | 3         | 4.92%   |
| 4/3   | 1         | 1.64%   |
| 3/2   | 1         | 1.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 19.4%   |
| 81-90          | 10        | 14.93%  |
| 201-250        | 9         | 13.43%  |
| 351-500        | 5         | 7.46%   |
| 151-200        | 5         | 7.46%   |
| 71-80          | 4         | 5.97%   |
| 301-350        | 4         | 5.97%   |
| 51-60          | 3         | 4.48%   |
| 41-50          | 3         | 4.48%   |
| More than 1000 | 2         | 2.99%   |
| 141-150        | 2         | 2.99%   |
| 131-140        | 2         | 2.99%   |
| 121-130        | 2         | 2.99%   |
| 61-70          | 1         | 1.49%   |
| 251-300        | 1         | 1.49%   |
| 501-1000       | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 20        | 31.75%  |
| 51-100        | 20        | 31.75%  |
| 121-160       | 12        | 19.05%  |
| 1-50          | 5         | 7.94%   |
| 161-240       | 4         | 6.35%   |
| More than 240 | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 64.2%   |
| 0     | 21        | 25.93%  |
| 2     | 7         | 8.64%   |
| 4     | 1         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 40        | 33.61%  |
| Intel                           | 31        | 26.05%  |
| Qualcomm Atheros                | 16        | 13.45%  |
| Broadcom                        | 15        | 12.61%  |
| Marvell Technology Group        | 3         | 2.52%   |
| Xiaomi                          | 2         | 1.68%   |
| Qualcomm                        | 2         | 1.68%   |
| VIA Technologies                | 1         | 0.84%   |
| T & A Mobile Phones             | 1         | 0.84%   |
| Sigma Designs                   | 1         | 0.84%   |
| Qualcomm Atheros Communications | 1         | 0.84%   |
| Nvidia                          | 1         | 0.84%   |
| Mellanox Technologies           | 1         | 0.84%   |
| LSI                             | 1         | 0.84%   |
| Dresden Elektronik              | 1         | 0.84%   |
| D-Link System                   | 1         | 0.84%   |
| Broadcom Limited                | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 17.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 4.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 2.19%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.46%   |
| Intel Wireless 8260                                                            | 2         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.46%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.46%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.73%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.73%   |
| T & A Mobile Phones A509DL                                                     | 1         | 0.73%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                | 1         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.73%   |
| Qualcomm Redmi 9T                                                              | 1         | 0.73%   |
| Qualcomm POCO F2 Pro                                                           | 1         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.73%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.73%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.73%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.73%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.73%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.73%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.73%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.73%   |
| LSI WinModem 56k                                                               | 1         | 0.73%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.73%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.73%   |
| Intel Wireless 7265                                                            | 1         | 0.73%   |
| Intel Wireless 7260                                                            | 1         | 0.73%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 0.73%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.73%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.73%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 0.73%   |
| Intel DH8900CC Null Device                                                     | 1         | 0.73%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 45.1%   |
| Qualcomm Atheros                | 14        | 27.45%  |
| Broadcom                        | 7         | 13.73%  |
| Realtek Semiconductor           | 4         | 7.84%   |
| Qualcomm Atheros Communications | 1         | 1.96%   |
| Marvell Technology Group        | 1         | 1.96%   |
| Broadcom Limited                | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 11.76%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 3.92%   |
| Intel Wireless 8260                                                            | 2         | 3.92%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 3.92%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 3.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 3.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.96%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 1.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.96%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.96%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.96%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.96%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.96%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.96%   |
| Intel Wireless 7265                                                            | 1         | 1.96%   |
| Intel Wireless 7260                                                            | 1         | 1.96%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.96%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.96%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.96%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1         | 1.96%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 1         | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 1.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 48.05%  |
| Intel                    | 18        | 23.38%  |
| Broadcom                 | 10        | 12.99%  |
| Xiaomi                   | 2         | 2.6%    |
| Qualcomm Atheros         | 2         | 2.6%    |
| Qualcomm                 | 2         | 2.6%    |
| Marvell Technology Group | 2         | 2.6%    |
| VIA Technologies         | 1         | 1.3%    |
| Nvidia                   | 1         | 1.3%    |
| Mellanox Technologies    | 1         | 1.3%    |
| D-Link System            | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 24        | 30.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 6         | 7.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 5         | 6.33%   |
| Intel I210 Gigabit Network Connection                                 | 3         | 3.8%    |
| Intel Ethernet Controller I225-V                                      | 2         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 2.53%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                        | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1         | 1.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.27%   |
| Qualcomm Redmi 9T                                                     | 1         | 1.27%   |
| Qualcomm POCO F2 Pro                                                  | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.27%   |
| Nvidia MCP61 Ethernet                                                 | 1         | 1.27%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller               | 1         | 1.27%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                  | 1         | 1.27%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.27%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.27%   |
| Intel 82583V Gigabit Network Connection                               | 1         | 1.27%   |
| Intel 82578DM Gigabit Network Connection                              | 1         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                              | 1         | 1.27%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1         | 1.27%   |
| Intel 82541GI Gigabit Ethernet Controller                             | 1         | 1.27%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1         | 1.27%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                        | 1         | 1.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                     | 1         | 1.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.27%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 1.27%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                 | 1         | 1.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 1.27%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.27%   |
| Broadcom BCM4401-B0 100Base-TX                                        | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 53.66%  |
| WiFi     | 50        | 40.65%  |
| Modem    | 5         | 4.07%   |
| Unknown  | 2         | 1.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 55.41%  |
| WiFi     | 33        | 44.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 44        | 55%     |
| 1     | 24        | 30%     |
| 0     | 6         | 7.5%    |
| 4     | 3         | 3.75%   |
| 5     | 2         | 2.5%    |
| 3     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 86.25%  |
| Yes  | 11        | 13.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 42.86%  |
| Qualcomm Atheros Communications | 3         | 8.57%   |
| Lite-On Technology              | 3         | 8.57%   |
| IMC Networks                    | 3         | 8.57%   |
| Broadcom                        | 3         | 8.57%   |
| Realtek Semiconductor           | 1         | 2.86%   |
| Marvell Semiconductor           | 1         | 2.86%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |
| Apple                           | 1         | 2.86%   |
| Alps Electric                   | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.57%   |
| Intel Bluetooth Device                              | 3         | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.71%   |
| Intel AX200 Bluetooth                               | 2         | 5.71%   |
| IMC Networks Bluetooth Device                       | 2         | 5.71%   |
| Realtek Bluetooth Radio                             | 1         | 2.86%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.86%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.86%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.86%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.86%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.86%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 53        | 69.74%  |
| AMD                                  | 13        | 17.11%  |
| Nvidia                               | 2         | 2.63%   |
| VIA Technologies                     | 1         | 1.32%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.32%   |
| Texas Instruments                    | 1         | 1.32%   |
| Sennheiser Communications            | 1         | 1.32%   |
| Realtek Semiconductor                | 1         | 1.32%   |
| Logitech                             | 1         | 1.32%   |
| Cirrus Logic                         | 1         | 1.32%   |
| C-Media Electronics                  | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 4.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 4.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.33%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 3.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.22%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.22%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.22%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.22%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.11%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 1.11%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.11%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.11%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.11%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.11%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Logitech G435 Wireless Gaming Headset                                                             | 1         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.11%   |
| Intel USB PnP Sound Device                                                                        | 1         | 1.11%   |
| Intel Multimedia audio controller                                                                 | 1         | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.11%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.11%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.11%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 1.11%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.11%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                          | 1         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.11%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.11%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 20%     |
| Unknown             | 14        | 18.67%  |
| Samsung Electronics | 10        | 13.33%  |
| Crucial             | 9         | 12%     |
| Micron Technology   | 6         | 8%      |
| Elpida              | 6         | 8%      |
| Kingston            | 4         | 5.33%   |
| A-DATA Technology   | 3         | 4%      |
| Corsair             | 2         | 2.67%   |
| Unknown (ABCD)      | 1         | 1.33%   |
| Transcend           | 1         | 1.33%   |
| Qimonda             | 1         | 1.33%   |
| Patriot             | 1         | 1.33%   |
| Hewlett-Packard     | 1         | 1.33%   |
| Cors                | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                                 | 2         | 2.5%    |
| Unknown RAM Module 1GB SODIMM DDR                                   | 2         | 2.5%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 2         | 2.5%    |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s            | 2         | 2.5%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.25%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 1.25%   |
| Unknown RAM Module 512MB DIMM                                       | 1         | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                 | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                       | 1         | 1.25%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                        | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 1.25%   |
| Unknown RAM Module 128MB DIMM DRAM                                  | 1         | 1.25%   |
| Unknown RAM Module 128MB DIMM                                       | 1         | 1.25%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.25%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s                  | 1         | 1.25%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.25%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 1.25%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8192MB DIMM DDR3 1600MT/s             | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 1.25%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.25%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s                | 1         | 1.25%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 1.25%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 1.25%   |
| SK hynix RAM H5TC4G63AFR-PBA 1GB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.25%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.25%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.25%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s               | 1         | 1.25%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s              | 1         | 1.25%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                 | 1         | 1.25%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.25%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.25%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1         | 1.25%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.25%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s           | 1         | 1.25%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s                 | 1         | 1.25%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.25%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s               | 1         | 1.25%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s                 | 1         | 1.25%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s                 | 1         | 1.25%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s              | 1         | 1.25%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                                | 1         | 1.25%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s           | 1         | 1.25%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s                 | 1         | 1.25%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 36        | 54.55%  |
| DDR4    | 15        | 22.73%  |
| LPDDR4  | 3         | 4.55%   |
| LPDDR3  | 3         | 4.55%   |
| DDR     | 3         | 4.55%   |
| SDRAM   | 2         | 3.03%   |
| DDR2    | 2         | 3.03%   |
| DRAM    | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 53.03%  |
| DIMM         | 27        | 40.91%  |
| Row Of Chips | 4         | 6.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 36.11%  |
| 4096  | 22        | 30.56%  |
| 2048  | 10        | 13.89%  |
| 1024  | 5         | 6.94%   |
| 16384 | 3         | 4.17%   |
| 512   | 3         | 4.17%   |
| 128   | 2         | 2.78%   |
| 256   | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 30.43%  |
| 2400    | 7         | 10.14%  |
| 1333    | 7         | 10.14%  |
| Unknown | 7         | 10.14%  |
| 2133    | 5         | 7.25%   |
| 2667    | 4         | 5.8%    |
| 1334    | 4         | 5.8%    |
| 3600    | 2         | 2.9%    |
| 1866    | 2         | 2.9%    |
| 4267    | 1         | 1.45%   |
| 3200    | 1         | 1.45%   |
| 1867    | 1         | 1.45%   |
| 1800    | 1         | 1.45%   |
| 1400    | 1         | 1.45%   |
| 1200    | 1         | 1.45%   |
| 1067    | 1         | 1.45%   |
| 1066    | 1         | 1.45%   |
| 667     | 1         | 1.45%   |
| 533     | 1         | 1.45%   |

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
| Chicony Electronics                    | 11        | 29.73%  |
| Realtek Semiconductor                  | 5         | 13.51%  |
| Suyin                                  | 3         | 8.11%   |
| Sunplus Innovation Technology          | 2         | 5.41%   |
| Microdia                               | 2         | 5.41%   |
| IMC Networks                           | 2         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.41%   |
| Z-Star Microelectronics                | 1         | 2.7%    |
| Syntek                                 | 1         | 2.7%    |
| Silicon Motion                         | 1         | 2.7%    |
| Ricoh                                  | 1         | 2.7%    |
| Quanta                                 | 1         | 2.7%    |
| MacroSilicon                           | 1         | 2.7%    |
| Linux Foundation                       | 1         | 2.7%    |
| Lenovo                                 | 1         | 2.7%    |
| Apple                                  | 1         | 2.7%    |
| Acer                                   | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 5.41%   |
| Chicony Integrated Camera                           | 2         | 5.41%   |
| Chicony HD WebCam                                   | 2         | 5.41%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 2.7%    |
| Syntek EasyCamera                                   | 1         | 2.7%    |
| Suyin HP Truevision HD                              | 1         | 2.7%    |
| Suyin HP High Definition 1MP Webcam                 | 1         | 2.7%    |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.7%    |
| Sunplus HP Universal Camera                         | 1         | 2.7%    |
| Sunplus HD WebCam                                   | 1         | 2.7%    |
| Silicon Motion NCM-G102                             | 1         | 2.7%    |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 2.7%    |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 2.7%    |
| Realtek USB Camera                                  | 1         | 2.7%    |
| Realtek Acer 640 x 480 laptop camera                | 1         | 2.7%    |
| Quanta HP TrueVision HD Camera                      | 1         | 2.7%    |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.7%    |
| Microdia Integrated_Webcam_HD                       | 1         | 2.7%    |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 2.7%    |
| Linux Foundation EEM Gadget                         | 1         | 2.7%    |
| Lenovo Integrated Webcam                            | 1         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.7%    |
| IMC Networks Integrated Camera                      | 1         | 2.7%    |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.7%    |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.7%    |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.7%    |
| Chicony HP HD Camera                                | 1         | 2.7%    |
| Chicony CNF8243 Webcam                              | 1         | 2.7%    |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.7%    |
| Acer HP Webcam                                      | 1         | 2.7%    |

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
| 0     | 48        | 58.54%  |
| 1     | 22        | 26.83%  |
| 2     | 7         | 8.54%   |
| 3     | 3         | 3.66%   |
| 5     | 1         | 1.22%   |
| 4     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 25.49%  |
| Fingerprint reader       | 7         | 13.73%  |
| Communication controller | 7         | 13.73%  |
| Net/wireless             | 4         | 7.84%   |
| Modem                    | 4         | 7.84%   |
| Unassigned class         | 2         | 3.92%   |
| Sound                    | 2         | 3.92%   |
| Network                  | 2         | 3.92%   |
| Multimedia controller    | 2         | 3.92%   |
| Chipcard                 | 2         | 3.92%   |
| Camera                   | 2         | 3.92%   |
| Unclassified device      | 1         | 1.96%   |
| Storage                  | 1         | 1.96%   |
| Net/ethernet             | 1         | 1.96%   |
| Bluetooth                | 1         | 1.96%   |


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

Total: 89

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ASRock        | J3455M                      | Desktop     | [a838270927](https://linux-hardware.org/?probe=a838270927) | Jul 03, 2020 |
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
| Alpine 3.12.0               | 11        | 14.67%  |
| Alpine 3.15.0               | 10        | 13.33%  |
| Alpine 3.15.0_alpha20210804 | 7         | 9.33%   |
| Alpine 3.14.0               | 5         | 6.67%   |
| Alpine 3.14.2               | 4         | 5.33%   |
| Alpine 3.13.0_alpha20200917 | 4         | 5.33%   |
| Alpine 3.13.0_alpha20200626 | 4         | 5.33%   |
| Alpine 3.11.2               | 4         | 5.33%   |
| Alpine 3.13.1               | 3         | 4%      |
| Alpine 3.13.0_alpha20201218 | 3         | 4%      |
| Alpine 3.13.5               | 2         | 2.67%   |
| Alpine 3.13.2               | 2         | 2.67%   |
| Alpine 3.12.3               | 2         | 2.67%   |
| Alpine 3.8.4                | 1         | 1.33%   |
| Alpine 3.16.0_alpha20220328 | 1         | 1.33%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.33%   |
| Alpine 3.15.4               | 1         | 1.33%   |
| Alpine 3.15.2               | 1         | 1.33%   |
| Alpine 3.15.0_rc5           | 1         | 1.33%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.33%   |
| Alpine 3.13.6               | 1         | 1.33%   |
| Alpine 3.13.3               | 1         | 1.33%   |
| Alpine 3.13.0_rc2           | 1         | 1.33%   |
| Alpine 3.12.7               | 1         | 1.33%   |
| Alpine 3.12.1               | 1         | 1.33%   |
| Alpine 3.12.0_rc1           | 1         | 1.33%   |
| Alpine 3.11.5               | 1         | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 70        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 10.53%  |
| 5.15.16-0-lts          | 3         | 3.95%   |
| 5.10.61-0-lts          | 3         | 3.95%   |
| 5.4.84-0-lts           | 2         | 2.63%   |
| 5.4.83-0-lts           | 2         | 2.63%   |
| 5.15.4-0-lts           | 2         | 2.63%   |
| 5.15.12-0-lts          | 2         | 2.63%   |
| 5.10.68-0-lts          | 2         | 2.63%   |
| 5.10.16-0-lts          | 2         | 2.63%   |
| 5.8.12-0-edge          | 1         | 1.32%   |
| 5.8.0                  | 1         | 1.32%   |
| 5.7.4                  | 1         | 1.32%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.32%   |
| 5.4.99                 | 1         | 1.32%   |
| 5.4.73-0-lts           | 1         | 1.32%   |
| 5.4.72-0-lts           | 1         | 1.32%   |
| 5.4.65-0-lts           | 1         | 1.32%   |
| 5.4.64-0-lts           | 1         | 1.32%   |
| 5.4.6-0-lts            | 1         | 1.32%   |
| 5.4.58-0-lts           | 1         | 1.32%   |
| 5.4.57-0-lts           | 1         | 1.32%   |
| 5.4.46-0-lts           | 1         | 1.32%   |
| 5.4.27-0-lts           | 1         | 1.32%   |
| 5.4.111-0-lts          | 1         | 1.32%   |
| 5.4.0-77-generic       | 1         | 1.32%   |
| 5.17.3-0-edge          | 1         | 1.32%   |
| 5.17.0-0-edge          | 1         | 1.32%   |
| 5.16.12-may            | 1         | 1.32%   |
| 5.16.1-may             | 1         | 1.32%   |
| 5.15.34                | 1         | 1.32%   |
| 5.15.30-0-lts          | 1         | 1.32%   |
| 5.15.28-0-lts          | 1         | 1.32%   |
| 5.15.26-0-lts          | 1         | 1.32%   |
| 5.15.17-0-lts          | 1         | 1.32%   |
| 5.14.8-0-edge          | 1         | 1.32%   |
| 5.13.0-0-edge          | 1         | 1.32%   |
| 5.12.8-0-edge          | 1         | 1.32%   |
| 5.10.83-v8             | 1         | 1.32%   |
| 5.10.81                | 1         | 1.32%   |
| 5.10.72-1-lts          | 1         | 1.32%   |
| 5.10.70-0-lts          | 1         | 1.32%   |
| 5.10.69-0-lts          | 1         | 1.32%   |
| 5.10.66-0-lts          | 1         | 1.32%   |
| 5.10.5-0-lts           | 1         | 1.32%   |
| 5.10.44-0-lts          | 1         | 1.32%   |
| 5.10.43-0-lts          | 1         | 1.32%   |
| 5.10.42-0-legacy       | 1         | 1.32%   |
| 5.10.4-0-lts           | 1         | 1.32%   |
| 5.10.38-0-lts          | 1         | 1.32%   |
| 5.10.29-0-lts          | 1         | 1.32%   |
| 5.10.24-0-lts          | 1         | 1.32%   |
| 5.10.12-0-lts          | 1         | 1.32%   |
| 5.10.11-0-lts          | 1         | 1.32%   |
| 5.10.1-0-lts           | 1         | 1.32%   |
| 4.4.59+                | 1         | 1.32%   |
| 4.14.89-0-vanilla      | 1         | 1.32%   |
| 3.10.98-poky-edison+   | 1         | 1.32%   |
| 3.10.18                | 1         | 1.32%   |
| 3.10.105               | 1         | 1.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.43   | 8         | 10.53%  |
| 5.15.16  | 3         | 3.95%   |
| 5.10.61  | 3         | 3.95%   |
| 5.4.84   | 2         | 2.63%   |
| 5.4.83   | 2         | 2.63%   |
| 5.15.4   | 2         | 2.63%   |
| 5.15.12  | 2         | 2.63%   |
| 5.10.68  | 2         | 2.63%   |
| 5.10.16  | 2         | 2.63%   |
| 5.8.12   | 1         | 1.32%   |
| 5.8.0    | 1         | 1.32%   |
| 5.7.4    | 1         | 1.32%   |
| 5.6.2    | 1         | 1.32%   |
| 5.4.99   | 1         | 1.32%   |
| 5.4.73   | 1         | 1.32%   |
| 5.4.72   | 1         | 1.32%   |
| 5.4.65   | 1         | 1.32%   |
| 5.4.64   | 1         | 1.32%   |
| 5.4.6    | 1         | 1.32%   |
| 5.4.58   | 1         | 1.32%   |
| 5.4.57   | 1         | 1.32%   |
| 5.4.46   | 1         | 1.32%   |
| 5.4.27   | 1         | 1.32%   |
| 5.4.111  | 1         | 1.32%   |
| 5.4.0    | 1         | 1.32%   |
| 5.17.3   | 1         | 1.32%   |
| 5.17.0   | 1         | 1.32%   |
| 5.16.12  | 1         | 1.32%   |
| 5.16.1   | 1         | 1.32%   |
| 5.15.34  | 1         | 1.32%   |
| 5.15.30  | 1         | 1.32%   |
| 5.15.28  | 1         | 1.32%   |
| 5.15.26  | 1         | 1.32%   |
| 5.15.17  | 1         | 1.32%   |
| 5.14.8   | 1         | 1.32%   |
| 5.13.0   | 1         | 1.32%   |
| 5.12.8   | 1         | 1.32%   |
| 5.10.83  | 1         | 1.32%   |
| 5.10.81  | 1         | 1.32%   |
| 5.10.72  | 1         | 1.32%   |
| 5.10.70  | 1         | 1.32%   |
| 5.10.69  | 1         | 1.32%   |
| 5.10.66  | 1         | 1.32%   |
| 5.10.5   | 1         | 1.32%   |
| 5.10.44  | 1         | 1.32%   |
| 5.10.43  | 1         | 1.32%   |
| 5.10.42  | 1         | 1.32%   |
| 5.10.4   | 1         | 1.32%   |
| 5.10.38  | 1         | 1.32%   |
| 5.10.29  | 1         | 1.32%   |
| 5.10.24  | 1         | 1.32%   |
| 5.10.12  | 1         | 1.32%   |
| 5.10.11  | 1         | 1.32%   |
| 5.10.1   | 1         | 1.32%   |
| 4.4.59   | 1         | 1.32%   |
| 4.14.89  | 1         | 1.32%   |
| 3.10.98  | 1         | 1.32%   |
| 3.10.18  | 1         | 1.32%   |
| 3.10.105 | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 31.94%  |
| 5.10    | 22        | 30.56%  |
| 5.15    | 12        | 16.67%  |
| 3.10    | 3         | 4.17%   |
| 5.8     | 2         | 2.78%   |
| 5.17    | 2         | 2.78%   |
| 5.7     | 1         | 1.39%   |
| 5.6     | 1         | 1.39%   |
| 5.16    | 1         | 1.39%   |
| 5.14    | 1         | 1.39%   |
| 5.13    | 1         | 1.39%   |
| 5.12    | 1         | 1.39%   |
| 4.4     | 1         | 1.39%   |
| 4.14    | 1         | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 61        | 87.14%  |
| i686    | 6         | 8.57%   |
| i586    | 1         | 1.43%   |
| armv7l  | 1         | 1.43%   |
| aarch64 | 1         | 1.43%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 82.86%  |
| XFCE    | 4         | 5.71%   |
| GNOME   | 4         | 5.71%   |
| sway    | 1         | 1.43%   |
| KDE5    | 1         | 1.43%   |
| KDE     | 1         | 1.43%   |
| i3      | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 45        | 63.38%  |
| X11     | 20        | 28.17%  |
| Wayland | 5         | 7.04%   |
| Tty     | 1         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 90.14%  |
| LightDM | 3         | 4.23%   |
| XDM     | 1         | 1.41%   |
| SDDM    | 1         | 1.41%   |
| LXDM    | 1         | 1.41%   |
| GDM     | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 40        | 56.34%  |
| Unknown | 23        | 32.39%  |
| en_US   | 5         | 7.04%   |
| ru_RU   | 2         | 2.82%   |
| en_GB   | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 48        | 68.57%  |
| EFI  | 22        | 31.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 77.46%  |
| Btrfs   | 5         | 7.04%   |
| Overlay | 4         | 5.63%   |
| Tmpfs   | 3         | 4.23%   |
| Unknown | 2         | 2.82%   |
| F2fs    | 1         | 1.41%   |
| Ext2    | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 54.05%  |
| GPT     | 24        | 32.43%  |
| MBR     | 10        | 13.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 90%     |
| Yes       | 7         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 91.55%  |
| Yes       | 6         | 8.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 13        | 18.57%  |
| Dell                    | 12        | 17.14%  |
| Lenovo                  | 8         | 11.43%  |
| ASUSTek Computer        | 8         | 11.43%  |
| Acer                    | 4         | 5.71%   |
| Intel                   | 2         | 2.86%   |
| IBM                     | 2         | 2.86%   |
| Gigabyte Technology     | 2         | 2.86%   |
| ASRock                  | 2         | 2.86%   |
| Unknown                 | 2         | 2.86%   |
| VIA Technologies        | 1         | 1.43%   |
| Synology                | 1         | 1.43%   |
| Supermicro              | 1         | 1.43%   |
| Shuttle                 | 1         | 1.43%   |
| Raspberry Pi Foundation | 1         | 1.43%   |
| Pegatron                | 1         | 1.43%   |
| MSI                     | 1         | 1.43%   |
| Haier                   | 1         | 1.43%   |
| Google                  | 1         | 1.43%   |
| Gateway                 | 1         | 1.43%   |
| Fujitsu                 | 1         | 1.43%   |
| F5 Networks             | 1         | 1.43%   |
| eMachines               | 1         | 1.43%   |
| Apple                   | 1         | 1.43%   |
| AMI                     | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP ProLiant DL360 G6                     | 2         | 2.86%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 2.86%   |
| Unknown                                  | 2         | 2.86%   |
| VIA KM266APro-835                        | 1         | 1.43%   |
| Synology DS1019+                         | 1         | 1.43%   |
| Supermicro X10SLL-F                      | 1         | 1.43%   |
| Shuttle DS81D                            | 1         | 1.43%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 1.43%   |
| Pegatron Deepcam                         | 1         | 1.43%   |
| MSI GL72M 7REX                           | 1         | 1.43%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.43%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.43%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.43%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.43%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.43%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 1.43%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.43%   |
| Intel NUC6i7KYB H90766-406               | 1         | 1.43%   |
| Intel Merrifield                         | 1         | 1.43%   |
| IBM 26446AG                              | 1         | 1.43%   |
| IBM 264070A                              | 1         | 1.43%   |
| HP ZBook 15 G5                           | 1         | 1.43%   |
| HP Stream 7 Tablet                       | 1         | 1.43%   |
| HP ProLiant MicroServer Gen8             | 1         | 1.43%   |
| HP ProBook 4310s                         | 1         | 1.43%   |
| HP Mini 110-3500                         | 1         | 1.43%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.43%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.43%   |
| HP EliteBook 2740p                       | 1         | 1.43%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.43%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.43%   |
| HP 23-p030na                             | 1         | 1.43%   |
| Haier U144S                              | 1         | 1.43%   |
| Google Samus                             | 1         | 1.43%   |
| Gateway MX3631m                          | 1         | 1.43%   |
| Fujitsu PRIMERGY TX100 S2                | 1         | 1.43%   |
| F5 Networks C117                         | 1         | 1.43%   |
| eMachines EL1352G                        | 1         | 1.43%   |
| Dell XPS 15 7590                         | 1         | 1.43%   |
| Dell XPS 13 7390 2-in-1                  | 1         | 1.43%   |
| Dell Studio 1747                         | 1         | 1.43%   |
| Dell PowerEdge T640                      | 1         | 1.43%   |
| Dell PowerEdge R510                      | 1         | 1.43%   |
| Dell OptiPlex 755                        | 1         | 1.43%   |
| Dell OptiPlex 3020M                      | 1         | 1.43%   |
| Dell OptiPlex 3010                       | 1         | 1.43%   |
| Dell Inspiron MM061                      | 1         | 1.43%   |
| Dell Inspiron 5566                       | 1         | 1.43%   |
| Dell Inspiron 3647                       | 1         | 1.43%   |
| Dell Inspiron 3180                       | 1         | 1.43%   |
| ASUS ZenBook UX431FA                     | 1         | 1.43%   |
| ASUS X550EA                              | 1         | 1.43%   |
| ASUS X200MA                              | 1         | 1.43%   |
| ASUS TS10                                | 1         | 1.43%   |
| ASUS PRIME H370M-PLUS                    | 1         | 1.43%   |
| ASUS P8H67-V                             | 1         | 1.43%   |
| ASUS E502SA                              | 1         | 1.43%   |
| ASUS All Series                          | 1         | 1.43%   |
| ASRock J3455M                            | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 7.14%   |
| Dell Inspiron       | 4         | 5.71%   |
| Acer Aspire         | 4         | 5.71%   |
| HP ProLiant         | 3         | 4.29%   |
| Dell OptiPlex       | 3         | 4.29%   |
| HP EliteBook        | 2         | 2.86%   |
| Gigabyte Z490I      | 2         | 2.86%   |
| Dell XPS            | 2         | 2.86%   |
| Dell PowerEdge      | 2         | 2.86%   |
| Unknown             | 2         | 2.86%   |
| VIA KM266APro-835   | 1         | 1.43%   |
| Synology DS1019+    | 1         | 1.43%   |
| Supermicro X10SLL-F | 1         | 1.43%   |
| Shuttle DS81D       | 1         | 1.43%   |
| RPi Raspberry       | 1         | 1.43%   |
| Pegatron Deepcam    | 1         | 1.43%   |
| MSI GL72M           | 1         | 1.43%   |
| Lenovo Yoga         | 1         | 1.43%   |
| Lenovo ThinkCentre  | 1         | 1.43%   |
| Lenovo IdeaPad      | 1         | 1.43%   |
| Intel NUC6i7KYB     | 1         | 1.43%   |
| Intel Merrifield    | 1         | 1.43%   |
| IBM 26446AG         | 1         | 1.43%   |
| IBM 264070A         | 1         | 1.43%   |
| HP ZBook            | 1         | 1.43%   |
| HP Stream           | 1         | 1.43%   |
| HP ProBook          | 1         | 1.43%   |
| HP Mini             | 1         | 1.43%   |
| HP Laptop           | 1         | 1.43%   |
| HP ENVY             | 1         | 1.43%   |
| HP Compaq           | 1         | 1.43%   |
| HP 23-p030na        | 1         | 1.43%   |
| Haier U144S         | 1         | 1.43%   |
| Google Samus        | 1         | 1.43%   |
| Gateway MX3631m     | 1         | 1.43%   |
| Fujitsu PRIMERGY    | 1         | 1.43%   |
| F5 Networks C117    | 1         | 1.43%   |
| eMachines EL1352G   | 1         | 1.43%   |
| Dell Studio         | 1         | 1.43%   |
| ASUS ZenBook        | 1         | 1.43%   |
| ASUS X550EA         | 1         | 1.43%   |
| ASUS X200MA         | 1         | 1.43%   |
| ASUS TS10           | 1         | 1.43%   |
| ASUS PRIME          | 1         | 1.43%   |
| ASUS P8H67-V        | 1         | 1.43%   |
| ASUS E502SA         | 1         | 1.43%   |
| ASUS All            | 1         | 1.43%   |
| ASRock J3455M       | 1         | 1.43%   |
| ASRock D1800B-ITX   | 1         | 1.43%   |
| Apple Macmini6      | 1         | 1.43%   |
| AMI Aptio           | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 11        | 15.71%  |
| 2019    | 7         | 10%     |
| 2018    | 7         | 10%     |
| 2010    | 6         | 8.57%   |
| 2016    | 5         | 7.14%   |
| 2017    | 4         | 5.71%   |
| 2015    | 4         | 5.71%   |
| 2009    | 4         | 5.71%   |
| 2020    | 3         | 4.29%   |
| 2013    | 3         | 4.29%   |
| 2012    | 3         | 4.29%   |
| Unknown | 3         | 4.29%   |
| 2021    | 2         | 2.86%   |
| 2007    | 2         | 2.86%   |
| 2011    | 1         | 1.43%   |
| 2008    | 1         | 1.43%   |
| 2006    | 1         | 1.43%   |
| 2005    | 1         | 1.43%   |
| 2004    | 1         | 1.43%   |
| 1999    | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 37        | 52.86%  |
| Desktop        | 18        | 25.71%  |
| Server         | 6         | 8.57%   |
| Mini pc        | 4         | 5.71%   |
| Tablet         | 2         | 2.86%   |
| System on chip | 1         | 1.43%   |
| Convertible    | 1         | 1.43%   |
| All in one     | 1         | 1.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 70        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 98.57%  |
| Yes  | 1         | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 14        | 19.18%  |
| 16.01-24.0      | 14        | 19.18%  |
| 4.01-8.0        | 13        | 17.81%  |
| 8.01-16.0       | 11        | 15.07%  |
| 0.51-1.0        | 6         | 8.22%   |
| 1.01-2.0        | 4         | 5.48%   |
| 32.01-64.0      | 3         | 4.11%   |
| 64.01-256.0     | 3         | 4.11%   |
| 0.01-0.5        | 3         | 4.11%   |
| More than 256.0 | 1         | 1.37%   |
| 2.01-3.0        | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 21        | 28.38%  |
| 1.01-2.0  | 13        | 17.57%  |
| 0.51-1.0  | 11        | 14.86%  |
| 3.01-4.0  | 8         | 10.81%  |
| 4.01-8.0  | 6         | 8.11%   |
| 2.01-3.0  | 6         | 8.11%   |
| 8.01-16.0 | 4         | 5.41%   |
| Unknown   | 3         | 4.05%   |
| 0         | 2         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 61.11%  |
| 2      | 14        | 19.44%  |
| 4      | 4         | 5.56%   |
| 3      | 4         | 5.56%   |
| 14     | 2         | 2.78%   |
| 10     | 1         | 1.39%   |
| 7      | 1         | 1.39%   |
| 5      | 1         | 1.39%   |
| 0      | 1         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 78.57%  |
| Yes       | 15        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 82.86%  |
| No        | 12        | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 61.43%  |
| No        | 27        | 38.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 55.71%  |
| Yes       | 31        | 44.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 19        | 26.76%  |
| Russia       | 7         | 9.86%   |
| Canada       | 7         | 9.86%   |
| UK           | 5         | 7.04%   |
| Sweden       | 4         | 5.63%   |
| Germany      | 4         | 5.63%   |
| Norway       | 2         | 2.82%   |
| Guatemala    | 2         | 2.82%   |
| Brazil       | 2         | 2.82%   |
| Venezuela    | 1         | 1.41%   |
| Ukraine      | 1         | 1.41%   |
| Switzerland  | 1         | 1.41%   |
| Spain        | 1         | 1.41%   |
| South Korea  | 1         | 1.41%   |
| South Africa | 1         | 1.41%   |
| Slovakia     | 1         | 1.41%   |
| Portugal     | 1         | 1.41%   |
| Poland       | 1         | 1.41%   |
| Pakistan     | 1         | 1.41%   |
| Mexico       | 1         | 1.41%   |
| Italy        | 1         | 1.41%   |
| Indonesia    | 1         | 1.41%   |
| France       | 1         | 1.41%   |
| Egypt        | 1         | 1.41%   |
| Czechia      | 1         | 1.41%   |
| China        | 1         | 1.41%   |
| Austria      | 1         | 1.41%   |
| Australia    | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| St Petersburg      | 5         | 6.94%   |
| Manitowoc          | 5         | 6.94%   |
| Vernon             | 2         | 2.78%   |
| Stratford          | 2         | 2.78%   |
| Stockholm          | 2         | 2.78%   |
| Guatemala City     | 2         | 2.78%   |
| As                 | 2         | 2.78%   |
| Zurich             | 1         | 1.39%   |
| Verona             | 1         | 1.39%   |
| Tymovskoye         | 1         | 1.39%   |
| Topeka             | 1         | 1.39%   |
| Thame              | 1         | 1.39%   |
| Tanvald            | 1         | 1.39%   |
| Tampa              | 1         | 1.39%   |
| Sydney             | 1         | 1.39%   |
| Suwon              | 1         | 1.39%   |
| Street             | 1         | 1.39%   |
| Sisteron           | 1         | 1.39%   |
| Sant Pere de Ribes | 1         | 1.39%   |
| Sankt PГ¶lten    | 1         | 1.39%   |
| San Mateo          | 1         | 1.39%   |
| RzeszГіw         | 1         | 1.39%   |
| Rostock            | 1         | 1.39%   |
| Redwood City       | 1         | 1.39%   |
| Plymouth           | 1         | 1.39%   |
| Ottawa             | 1         | 1.39%   |
| Nuremberg          | 1         | 1.39%   |
| MГ©rida          | 1         | 1.39%   |
| Munich             | 1         | 1.39%   |
| Merrill            | 1         | 1.39%   |
| Mankato            | 1         | 1.39%   |
| Mamaroneck         | 1         | 1.39%   |
| London             | 1         | 1.39%   |
| Lincoln            | 1         | 1.39%   |
| Larkspur           | 1         | 1.39%   |
| Lahore             | 1         | 1.39%   |
| Kitchener          | 1         | 1.39%   |
| Kirkland           | 1         | 1.39%   |
| Kharkiv            | 1         | 1.39%   |
| Kaliningrad        | 1         | 1.39%   |
| Johannesburg       | 1         | 1.39%   |
| Jember             | 1         | 1.39%   |
| Indaiatuba         | 1         | 1.39%   |
| Hilden             | 1         | 1.39%   |
| Hampstead          | 1         | 1.39%   |
| Gothenburg         | 1         | 1.39%   |
| Funchal            | 1         | 1.39%   |
| Franklin           | 1         | 1.39%   |
| Ecatepec           | 1         | 1.39%   |
| Dallas             | 1         | 1.39%   |
| Chapel Hill        | 1         | 1.39%   |
| Cairo              | 1         | 1.39%   |
| Brockport          | 1         | 1.39%   |
| Bratislava         | 1         | 1.39%   |
| Boucherville       | 1         | 1.39%   |
| Belém             | 1         | 1.39%   |
| Beijing            | 1         | 1.39%   |
| Barrow in Furness  | 1         | 1.39%   |
| Bandhagen          | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 36     | 12.77%  |
| Samsung Electronics | 12        | 19     | 12.77%  |
| Seagate             | 11        | 29     | 11.7%   |
| Unknown             | 7         | 9      | 7.45%   |
| Hitachi             | 6         | 6      | 6.38%   |
| Intel               | 5         | 9      | 5.32%   |
| HGST                | 5         | 5      | 5.32%   |
| Crucial             | 5         | 11     | 5.32%   |
| Toshiba             | 4         | 5      | 4.26%   |
| SK Hynix            | 4         | 6      | 4.26%   |
| Kingston            | 4         | 4      | 4.26%   |
| Transcend           | 2         | 2      | 2.13%   |
| SanDisk             | 2         | 2      | 2.13%   |
| LITEON              | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| STEC                | 1         | 1      | 1.06%   |
| SPCC                | 1         | 1      | 1.06%   |
| NETAPP              | 1         | 1      | 1.06%   |
| Lexar               | 1         | 1      | 1.06%   |
| KC600               | 1         | 1      | 1.06%   |
| JMicron             | 1         | 1      | 1.06%   |
| Intenso             | 1         | 1      | 1.06%   |
| IBM                 | 1         | 1      | 1.06%   |
| Dell                | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| AMD                 | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WD3000BLFS-60YBU2 304GB               | 2         | 1.94%   |
| Unknown MMC Card  16GB                    | 2         | 1.94%   |
| Seagate ST4000VN008-2DR1 4TB              | 2         | 1.94%   |
| Samsung SSD 960 EVO 500GB                 | 2         | 1.94%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.94%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.94%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.97%   |
| WDC WDS250G2B0A 250GB SSD                 | 1         | 0.97%   |
| WDC WD80EMAZ-00WJTA0 8TB                  | 1         | 0.97%   |
| WDC WD80EFAX-68LHPN0 8TB                  | 1         | 0.97%   |
| WDC WD5003ABYZ-0 500GB                    | 1         | 0.97%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 0.97%   |
| WDC WD20EZRZ-00Z 2TB                      | 1         | 0.97%   |
| WDC WD140EDFZ-11A0VA0 14TB                | 1         | 0.97%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.97%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 0.97%   |
| WDC WD10EZEX-21M2NA0 1TB                  | 1         | 0.97%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 0.97%   |
| Unknown SD64G  64GB                       | 1         | 0.97%   |
| Unknown SD16G  32GB                       | 1         | 0.97%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 0.97%   |
| Unknown MMC Card  4GB                     | 1         | 0.97%   |
| Unknown MMC Card  32GB                    | 1         | 0.97%   |
| Transcend TS128GSSD420I 128GB             | 1         | 0.97%   |
| Transcend SSD 1GB                         | 1         | 0.97%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.97%   |
| Toshiba MK3252GS 320GB                    | 1         | 0.97%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 0.97%   |
| Toshiba KBG40ZPZ512G NVMe 512GB           | 1         | 0.97%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD       | 1         | 0.97%   |
| STEC SDT5A-S200SS 200GB                   | 1         | 0.97%   |
| SPCC Solid State Disk 256GB               | 1         | 0.97%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 0.97%   |
| SK Hynix SC300 M.2 2280 256 256GB SSD     | 1         | 0.97%   |
| SK Hynix HFS480G3H2X069N 480GB            | 1         | 0.97%   |
| SK Hynix HBG4e  32GB                      | 1         | 0.97%   |
| Seagate ST98823A 80GB                     | 1         | 0.97%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 0.97%   |
| Seagate ST4000VN008-2DR166 4TB            | 1         | 0.97%   |
| Seagate ST380815AS 80GB                   | 1         | 0.97%   |
| Seagate ST3500418AS 500GB                 | 1         | 0.97%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 0.97%   |
| Seagate ST2000DL001-9VT1 2TB              | 1         | 0.97%   |
| Seagate ST1000LM048-2E71 1TB              | 1         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 0.97%   |
| SanDisk SSD PLUS 480GB                    | 1         | 0.97%   |
| SanDisk SDSA6MM 16GB SSD                  | 1         | 0.97%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 0.97%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 0.97%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 0.97%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 0.97%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 0.97%   |
| Samsung SP0411N 34GB                      | 1         | 0.97%   |
| Samsung Portable SSD T5 1TB               | 1         | 0.97%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 0.97%   |
| Samsung MZVLB512HBJQ-000L7 512GB          | 1         | 0.97%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 0.97%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 29     | 30.56%  |
| WDC                 | 9         | 32     | 25%     |
| Hitachi             | 6         | 6      | 16.67%  |
| HGST                | 5         | 5      | 13.89%  |
| Toshiba             | 2         | 2      | 5.56%   |
| Samsung Electronics | 2         | 4      | 5.56%   |
| IBM                 | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 13.51%  |
| Crucial             | 5         | 11     | 13.51%  |
| Kingston            | 4         | 4      | 10.81%  |
| Intel               | 3         | 5      | 8.11%   |
| WDC                 | 2         | 2      | 5.41%   |
| Transcend           | 2         | 2      | 5.41%   |
| SK Hynix            | 2         | 3      | 5.41%   |
| SanDisk             | 2         | 2      | 5.41%   |
| LITEON              | 2         | 2      | 5.41%   |
| A-DATA Technology   | 2         | 2      | 5.41%   |
| SPCC                | 1         | 1      | 2.7%    |
| Lexar               | 1         | 1      | 2.7%    |
| KC600               | 1         | 1      | 2.7%    |
| JMicron             | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Dell                | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| AMD                 | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 33        | 48     | 38.37%  |
| HDD     | 33        | 79     | 38.37%  |
| NVMe    | 13        | 20     | 15.12%  |
| MMC     | 6         | 9      | 6.98%   |
| Unknown | 1         | 2      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 122    | 69.23%  |
| NVMe | 13        | 20     | 16.67%  |
| MMC  | 6         | 9      | 7.69%   |
| SAS  | 5         | 7      | 6.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 77     | 70.77%  |
| 0.51-1.0   | 11        | 14     | 16.92%  |
| 4.01-10.0  | 3         | 19     | 4.62%   |
| 3.01-4.0   | 2         | 9      | 3.08%   |
| 1.01-2.0   | 2         | 4      | 3.08%   |
| 10.01-20.0 | 1         | 4      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 18.06%  |
| 1-20           | 12        | 16.67%  |
| Unknown        | 11        | 15.28%  |
| 21-50          | 9         | 12.5%   |
| 251-500        | 8         | 11.11%  |
| 501-1000       | 7         | 9.72%   |
| 1001-2000      | 4         | 5.56%   |
| 2001-3000      | 3         | 4.17%   |
| 51-100         | 3         | 4.17%   |
| More than 3000 | 2         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 41        | 57.75%  |
| Unknown   | 11        | 15.49%  |
| 51-100    | 6         | 8.45%   |
| 21-50     | 4         | 5.63%   |
| 101-250   | 3         | 4.23%   |
| 501-1000  | 3         | 4.23%   |
| 251-500   | 2         | 2.82%   |
| 1001-2000 | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB       | 2         | 14     | 20%     |
| Toshiba MK3252GS 320GB            | 1         | 1      | 10%     |
| Seagate ST2000LM015-2E81 2TB      | 1         | 1      | 10%     |
| SanDisk SDSA6MM 16GB SSD          | 1         | 1      | 10%     |
| Samsung Electronics SP0411N 34GB  | 1         | 2      | 10%     |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 10%     |
| Hitachi HTS725025A9A364 250GB     | 1         | 1      | 10%     |
| Hitachi HTS72101 99GB             | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 14     | 20%     |
| Samsung Electronics | 2         | 4      | 20%     |
| Hitachi             | 2         | 2      | 20%     |
| Toshiba             | 1         | 1      | 10%     |
| Seagate             | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 14     | 22.22%  |
| Samsung Electronics | 2         | 4      | 22.22%  |
| Hitachi             | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 23     | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Works    | 48        | 108    | 63.16%  |
| Detected | 18        | 26     | 23.68%  |
| Malfunc  | 10        | 24     | 13.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 48        | 60.76%  |
| Samsung Electronics          | 7         | 8.86%   |
| AMD                          | 7         | 8.86%   |
| LSI Logic / Symbios Logic    | 3         | 3.8%    |
| Hewlett-Packard              | 2         | 2.53%   |
| VIA Technologies             | 1         | 1.27%   |
| Toshiba America Info Systems | 1         | 1.27%   |
| SK Hynix                     | 1         | 1.27%   |
| Sandisk                      | 1         | 1.27%   |
| Nvidia                       | 1         | 1.27%   |
| Micron/Crucial Technology    | 1         | 1.27%   |
| Marvell Technology Group     | 1         | 1.27%   |
| KIOXIA                       | 1         | 1.27%   |
| Broadcom / LSI               | 1         | 1.27%   |
| ASMedia Technology           | 1         | 1.27%   |
| ADATA Technology             | 1         | 1.27%   |
| Adaptec                      | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 6.98%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 6.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 5.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 4.65%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 3         | 3.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.33%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.16%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.16%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 1.16%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.16%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.16%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.16%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.16%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 1.16%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.16%   |
| Intel SSD 600P Series                                                            | 1         | 1.16%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.16%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 1.16%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.16%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1         | 1.16%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.16%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.16%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                          | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                          | 1         | 1.16%   |
| HP Smart Array Gen8 Controllers                                                  | 1         | 1.16%   |
| HP Smart Array G6 controllers                                                    | 1         | 1.16%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.16%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.16%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 45        | 56.96%  |
| NVMe | 14        | 17.72%  |
| IDE  | 9         | 11.39%  |
| RAID | 8         | 10.13%  |
| SAS  | 3         | 3.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 83.1%   |
| AMD    | 10        | 14.08%  |
| ARM    | 2         | 2.82%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz                         | 2         | 2.82%   |
| Intel Core i9-10900 CPU @ 2.80GHz                      | 2         | 2.82%   |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 2         | 2.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 2.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 2         | 2.82%   |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 2.82%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz                     | 1         | 1.41%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 1.41%   |
| Intel Xeon CPU X3430 @ 2.40GHz                         | 1         | 1.41%   |
| Intel Xeon CPU L5630 @ 2.13GHz                         | 1         | 1.41%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz                   | 1         | 1.41%   |
| Intel Pentium M processor 1.60GHz                      | 1         | 1.41%   |
| Intel Pentium III (Coppermine)                         | 1         | 1.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz                 | 1         | 1.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 1.41%   |
| Intel Pentium CPU D1508 @ 2.20GHz                      | 1         | 1.41%   |
| Intel Mobile Pentium MMX                               | 1         | 1.41%   |
| Intel Genuine CPU 4000 @ 500MHz                        | 1         | 1.41%   |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 1.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz                      | 1         | 1.41%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz                     | 1         | 1.41%   |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 1.41%   |
| Intel Core i7-4790K CPU @ 4.00GHz                      | 1         | 1.41%   |
| Intel Core i7-3615QM CPU @ 2.30GHz                     | 1         | 1.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                     | 1         | 1.41%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 1.41%   |
| Intel Core i5-8400 CPU @ 2.80GHz                       | 1         | 1.41%   |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 1.41%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 1.41%   |
| Intel Core i5-3450 CPU @ 3.10GHz                       | 1         | 1.41%   |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz                      | 1         | 1.41%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 1.41%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 1.41%   |
| Intel Core i3-4150 CPU @ 3.50GHz                       | 1         | 1.41%   |
| Intel Core i3-3220T CPU @ 2.80GHz                      | 1         | 1.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz                       | 1         | 1.41%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 1.41%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 1.41%   |
| Intel Core 2 Duo CPU P7570 @ 2.26GHz                   | 1         | 1.41%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 1.41%   |
| Intel Celeron M processor 1.00GHz                      | 1         | 1.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 1.41%   |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 1.41%   |
| Intel Celeron CPU J1800 @ 2.41GHz                      | 1         | 1.41%   |
| Intel Celeron CPU G1850 @ 2.90GHz                      | 1         | 1.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz                      | 1         | 1.41%   |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 1.41%   |
| Intel Atom CPU Z3735G @ 1.33GHz                        | 1         | 1.41%   |
| Intel Atom CPU E3825 @ 1.33GHz                         | 1         | 1.41%   |
| ARM Processor                                          | 1         | 1.41%   |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 1.41%   |
| AMD Sempron 145 Processor                              | 1         | 1.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 1.41%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx          | 1         | 1.41%   |
| AMD Mobile Duron processor                             | 1         | 1.41%   |
| AMD FX-8350 Eight-Core Processor                       | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 13        | 18.31%  |
| Intel Celeron      | 8         | 11.27%  |
| Intel Core i7      | 7         | 9.86%   |
| Intel Xeon         | 6         | 8.45%   |
| Intel Atom         | 6         | 8.45%   |
| Other              | 5         | 7.04%   |
| Intel Core i9      | 3         | 4.23%   |
| Intel Core i3      | 3         | 4.23%   |
| Intel Core 2 Duo   | 3         | 4.23%   |
| Intel Pentium      | 2         | 2.82%   |
| AMD A4             | 2         | 2.82%   |
| Intel Xeon Gold    | 1         | 1.41%   |
| Intel Pentium M    | 1         | 1.41%   |
| Intel Pentium III  | 1         | 1.41%   |
| Intel Pentium Dual | 1         | 1.41%   |
| Intel Genuine      | 1         | 1.41%   |
| Intel Core 2       | 1         | 1.41%   |
| Intel Celeron M    | 1         | 1.41%   |
| AMD Sempron        | 1         | 1.41%   |
| AMD Ryzen 7        | 1         | 1.41%   |
| AMD Ryzen 5        | 1         | 1.41%   |
| AMD FX             | 1         | 1.41%   |
| AMD A6             | 1         | 1.41%   |
| AMD A10            | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27        | 38.03%  |
| 4       | 24        | 33.8%   |
| 1       | 8         | 11.27%  |
| 8       | 3         | 4.23%   |
| 12      | 2         | 2.82%   |
| 10      | 2         | 2.82%   |
| 6       | 2         | 2.82%   |
| 32      | 1         | 1.41%   |
| 3       | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 66        | 92.96%  |
| 2       | 4         | 5.63%   |
| Unknown | 1         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 37        | 52.86%  |
| 2       | 32        | 45.71%  |
| Unknown | 1         | 1.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 51.39%  |
| Unknown        | 31        | 43.06%  |
| 32-bit         | 4         | 5.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 47.95%  |
| 0x306c3    | 4         | 5.48%   |
| 0x30678    | 4         | 5.48%   |
| 0x306a9    | 3         | 4.11%   |
| 0x206c2    | 3         | 4.11%   |
| 0x906ea    | 2         | 2.74%   |
| 0x506c9    | 2         | 2.74%   |
| 0x406c4    | 2         | 2.74%   |
| 0x106e5    | 2         | 2.74%   |
| 0x106ca    | 2         | 2.74%   |
| 0x06006704 | 2         | 2.74%   |
| 0xa0655    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x706e5    | 1         | 1.37%   |
| 0x6fd      | 1         | 1.37%   |
| 0x6d8      | 1         | 1.37%   |
| 0x683      | 1         | 1.37%   |
| 0x506e3    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x206a7    | 1         | 1.37%   |
| 0x1067a    | 1         | 1.37%   |
| 0x0810100b | 1         | 1.37%   |
| 0x010000b6 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 8         | 11.27%  |
| KabyLake    | 8         | 11.27%  |
| Haswell     | 6         | 8.45%   |
| Westmere    | 4         | 5.63%   |
| IvyBridge   | 4         | 5.63%   |
| Goldmont    | 4         | 5.63%   |
| Unknown     | 4         | 5.63%   |
| Skylake     | 3         | 4.23%   |
| Penryn      | 3         | 4.23%   |
| P6          | 3         | 4.23%   |
| Excavator   | 3         | 4.23%   |
| SandyBridge | 2         | 2.82%   |
| Nehalem     | 2         | 2.82%   |
| IceLake     | 2         | 2.82%   |
| Core        | 2         | 2.82%   |
| CometLake   | 2         | 2.82%   |
| Broadwell   | 2         | 2.82%   |
| Bonnell     | 2         | 2.82%   |
| Zen 2       | 1         | 1.41%   |
| Zen         | 1         | 1.41%   |
| Puma        | 1         | 1.41%   |
| Piledriver  | 1         | 1.41%   |
| K6          | 1         | 1.41%   |
| K10         | 1         | 1.41%   |
| Jaguar      | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 45        | 60%     |
| AMD                        | 16        | 21.33%  |
| Nvidia                     | 6         | 8%      |
| Matrox Electronics Systems | 4         | 5.33%   |
| Neomagic                   | 2         | 2.67%   |
| VIA Technologies           | 1         | 1.33%   |
| ASPEED Technology          | 1         | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 7.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 5.26%   |
| Intel HD Graphics 500                                                                    | 4         | 5.26%   |
| AMD ES1000                                                                               | 3         | 3.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.63%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 2.63%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.32%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.32%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.32%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.32%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.32%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.32%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.32%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.32%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.32%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.32%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.32%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.32%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.32%   |
| Intel Iris Pro Graphics 580                                                              | 1         | 1.32%   |
| Intel HD Graphics 630                                                                    | 1         | 1.32%   |
| Intel HD Graphics 620                                                                    | 1         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.32%   |
| Intel Display controller                                                                 | 1         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.32%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 1.32%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 1.32%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.32%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.32%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.32%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.32%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.32%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.32%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 1.32%   |
| AMD Renoir                                                                               | 1         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.32%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.32%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 37        | 52.11%  |
| 1 x AMD         | 14        | 19.72%  |
| Other           | 3         | 4.23%   |
| 1 x Matrox      | 3         | 4.23%   |
| Intel + Nvidia  | 3         | 4.23%   |
| 2 x Intel       | 2         | 2.82%   |
| 1 x Nvidia      | 2         | 2.82%   |
| 1 x Neomagic    | 2         | 2.82%   |
| 2 x AMD         | 1         | 1.41%   |
| 1 x VIA         | 1         | 1.41%   |
| Nvidia + Matrox | 1         | 1.41%   |
| Intel + AMD     | 1         | 1.41%   |
| 1 x ASPEED      | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 58        | 79.45%  |
| Unknown     | 13        | 17.81%  |
| Proprietary | 2         | 2.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 84.29%  |
| 0.01-0.5   | 7         | 10%     |
| 1.01-2.0   | 2         | 2.86%   |
| 7.01-8.0   | 1         | 1.43%   |
| 0.51-1.0   | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 13.56%  |
| Samsung Electronics     | 6         | 10.17%  |
| LG Display              | 5         | 8.47%   |
| Chimei Innolux          | 5         | 8.47%   |
| Dell                    | 4         | 6.78%   |
| BOE                     | 4         | 6.78%   |
| AOC                     | 3         | 5.08%   |
| LG Philips              | 2         | 3.39%   |
| Hewlett-Packard         | 2         | 3.39%   |
| Goldstar                | 2         | 3.39%   |
| Chi Mei Optoelectronics | 2         | 3.39%   |
| Acer                    | 2         | 3.39%   |
| ViewSonic               | 1         | 1.69%   |
| Sony                    | 1         | 1.69%   |
| SKY                     | 1         | 1.69%   |
| Sharp                   | 1         | 1.69%   |
| Mi                      | 1         | 1.69%   |
| Lenovo                  | 1         | 1.69%   |
| KVM                     | 1         | 1.69%   |
| InfoVision              | 1         | 1.69%   |
| HannStar                | 1         | 1.69%   |
| Envision                | 1         | 1.69%   |
| EDI                     | 1         | 1.69%   |
| DENON                   | 1         | 1.69%   |
| CSO                     | 1         | 1.69%   |
| BenQ                    | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch         | 2         | 3.33%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch                 | 1         | 1.67%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                       | 1         | 1.67%   |
| SKY Coocaa TV SKY0001 1920x1080                                          | 1         | 1.67%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                  | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch     | 1         | 1.67%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                         | 1         | 1.67%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 1.67%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.67%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 1.67%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 1.67%   |
| KVM LCD Monitor 1 7" KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.67%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 1.67%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch             | 1         | 1.67%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 477x268mm 21.5-inch         | 1         | 1.67%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 1.67%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 1.67%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.67%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 1.67%   |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                    | 1         | 1.67%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 1.67%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                        | 1         | 1.67%   |
| Dell P2311H DEL4066 1920x1080 510x290mm 23.1-inch                        | 1         | 1.67%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                        | 1         | 1.67%   |
| Dell E151FPb DELA005 1024x768 304x228mm 15.0-inch                        | 1         | 1.67%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 1.67%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 1.67%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                        | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch           | 1         | 1.67%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                       | 1         | 1.67%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                         | 1         | 1.67%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                         | 1         | 1.67%   |
| Acer V173 ACR002F 1280x1024 338x270mm 17.0-inch                          | 1         | 1.67%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                        | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 25.42%  |
| 1366x768 (WXGA)    | 15        | 25.42%  |
| 1280x1024 (SXGA)   | 4         | 6.78%   |
| 3840x2160 (4K)     | 3         | 5.08%   |
| 2560x1440 (QHD)    | 3         | 5.08%   |
| 1280x800 (WXGA)    | 3         | 5.08%   |
| 3440x1440          | 2         | 3.39%   |
| 1920x1200 (WUXGA)  | 2         | 3.39%   |
| 1600x900 (HD+)     | 2         | 3.39%   |
| 1024x600           | 2         | 3.39%   |
| 2880x1800          | 1         | 1.69%   |
| 2560x1700          | 1         | 1.69%   |
| 2560x1080          | 1         | 1.69%   |
| 1680x1050 (WSXGA+) | 1         | 1.69%   |
| 1440x900 (WXGA+)   | 1         | 1.69%   |
| 1360x768           | 1         | 1.69%   |
| 1280x768           | 1         | 1.69%   |
| 1024x768 (XGA)     | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 12        | 20%     |
| 13      | 8         | 13.33%  |
| 17      | 6         | 10%     |
| 14      | 4         | 6.67%   |
| 27      | 3         | 5%      |
| 23      | 3         | 5%      |
| 21      | 3         | 5%      |
| 11      | 3         | 5%      |
| 34      | 2         | 3.33%   |
| 24      | 2         | 3.33%   |
| 19      | 2         | 3.33%   |
| 12      | 2         | 3.33%   |
| 10      | 2         | 3.33%   |
| 65      | 1         | 1.67%   |
| 54      | 1         | 1.67%   |
| 32      | 1         | 1.67%   |
| 31      | 1         | 1.67%   |
| 29      | 1         | 1.67%   |
| 25      | 1         | 1.67%   |
| 20      | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 38.33%  |
| 201-300     | 10        | 16.67%  |
| 501-600     | 8         | 13.33%  |
| 351-400     | 6         | 10%     |
| 401-500     | 4         | 6.67%   |
| 701-800     | 3         | 5%      |
| 601-700     | 3         | 5%      |
| 1001-1500   | 2         | 3.33%   |
| Unknown     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 70.91%  |
| 16/10 | 7         | 12.73%  |
| 5/4   | 4         | 7.27%   |
| 21/9  | 3         | 5.45%   |
| 4/3   | 1         | 1.82%   |
| 3/2   | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 20%     |
| 81-90          | 9         | 15%     |
| 201-250        | 7         | 11.67%  |
| 71-80          | 4         | 6.67%   |
| 351-500        | 4         | 6.67%   |
| 301-350        | 4         | 6.67%   |
| 151-200        | 4         | 6.67%   |
| 51-60          | 3         | 5%      |
| More than 1000 | 2         | 3.33%   |
| 41-50          | 2         | 3.33%   |
| 141-150        | 2         | 3.33%   |
| 131-140        | 2         | 3.33%   |
| 121-130        | 2         | 3.33%   |
| 61-70          | 1         | 1.67%   |
| 251-300        | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 18        | 31.58%  |
| 51-100        | 15        | 26.32%  |
| 121-160       | 12        | 21.05%  |
| 1-50          | 5         | 8.77%   |
| 161-240       | 4         | 7.02%   |
| More than 240 | 2         | 3.51%   |
| Unknown       | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 46        | 63.89%  |
| 0     | 19        | 26.39%  |
| 2     | 6         | 8.33%   |
| 4     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 34        | 33.33%  |
| Intel                           | 27        | 26.47%  |
| Broadcom                        | 14        | 13.73%  |
| Qualcomm Atheros                | 13        | 12.75%  |
| Xiaomi                          | 2         | 1.96%   |
| Marvell Technology Group        | 2         | 1.96%   |
| VIA Technologies                | 1         | 0.98%   |
| Sigma Designs                   | 1         | 0.98%   |
| Qualcomm Atheros Communications | 1         | 0.98%   |
| Qualcomm                        | 1         | 0.98%   |
| Nvidia                          | 1         | 0.98%   |
| Mellanox Technologies           | 1         | 0.98%   |
| LSI                             | 1         | 0.98%   |
| Dresden Elektronik              | 1         | 0.98%   |
| D-Link System                   | 1         | 0.98%   |
| Broadcom Limited                | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19        | 16.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 2.56%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 2.56%   |
| Intel Wireless 8260                                                            | 2         | 1.71%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.71%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.71%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.85%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                | 1         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.85%   |
| Qualcomm Mobile Router                                                         | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.85%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.85%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.85%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.85%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.85%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| LSI WinModem 56k                                                               | 1         | 0.85%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.85%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.85%   |
| Intel Wireless 7260                                                            | 1         | 0.85%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.85%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 0.85%   |
| Intel DH8900CC Null Device                                                     | 1         | 0.85%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 0.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 1         | 0.85%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.85%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 45.45%  |
| Qualcomm Atheros                | 11        | 25%     |
| Broadcom                        | 7         | 15.91%  |
| Realtek Semiconductor           | 3         | 6.82%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| Marvell Technology Group        | 1         | 2.27%   |
| Broadcom Limited                | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 13.64%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 6.82%   |
| Intel Wireless 8260                                                            | 2         | 4.55%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 2.27%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.27%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.27%   |
| Intel Wireless-AC 9260                                                         | 1         | 2.27%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.27%   |
| Intel Wireless 7260                                                            | 1         | 2.27%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.27%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.27%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.27%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 2.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1         | 2.27%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 1         | 2.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.27%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 46.97%  |
| Intel                    | 16        | 24.24%  |
| Broadcom                 | 9         | 13.64%  |
| Xiaomi                   | 2         | 3.03%   |
| Qualcomm Atheros         | 2         | 3.03%   |
| VIA Technologies         | 1         | 1.52%   |
| Qualcomm                 | 1         | 1.52%   |
| Nvidia                   | 1         | 1.52%   |
| Mellanox Technologies    | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| D-Link System            | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 19        | 27.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 6         | 8.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 4         | 5.88%   |
| Intel I210 Gigabit Network Connection                                 | 3         | 4.41%   |
| Intel Ethernet Controller I225-V                                      | 2         | 2.94%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                        | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1         | 1.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.47%   |
| Qualcomm Mobile Router                                                | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1         | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.47%   |
| Nvidia MCP61 Ethernet                                                 | 1         | 1.47%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller               | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.47%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.47%   |
| Intel 82583V Gigabit Network Connection                               | 1         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 1         | 1.47%   |
| Intel 82578DM Gigabit Network Connection                              | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.47%   |
| Intel 82567LM Gigabit Network Connection                              | 1         | 1.47%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1         | 1.47%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1         | 1.47%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                        | 1         | 1.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                     | 1         | 1.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.47%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                 | 1         | 1.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 1.47%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.47%   |
| Broadcom BCM4401-B0 100Base-TX                                        | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 54.29%  |
| WiFi     | 43        | 40.95%  |
| Modem    | 4         | 3.81%   |
| Unknown  | 1         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 59.74%  |
| WiFi     | 31        | 40.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 53.52%  |
| 1     | 22        | 30.99%  |
| 0     | 6         | 8.45%   |
| 4     | 3         | 4.23%   |
| 5     | 1         | 1.41%   |
| 3     | 1         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 85.92%  |
| Yes  | 10        | 14.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 45.16%  |
| Qualcomm Atheros Communications | 3         | 9.68%   |
| Lite-On Technology              | 3         | 9.68%   |
| IMC Networks                    | 3         | 9.68%   |
| Broadcom                        | 3         | 9.68%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| Marvell Semiconductor           | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |
| Cambridge Silicon Radio         | 1         | 3.23%   |
| Apple                           | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 12.9%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 9.68%   |
| Intel Bluetooth Device                              | 3         | 9.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 9.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 6.45%   |
| Intel AX200 Bluetooth                               | 2         | 6.45%   |
| IMC Networks Bluetooth Device                       | 2         | 6.45%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.23%   |
| Lite-On Bluetooth Device                            | 1         | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.23%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.23%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.23%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.23%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 45        | 68.18%  |
| AMD                                  | 11        | 16.67%  |
| Nvidia                               | 2         | 3.03%   |
| VIA Technologies                     | 1         | 1.52%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.52%   |
| Texas Instruments                    | 1         | 1.52%   |
| Sennheiser Communications            | 1         | 1.52%   |
| Realtek Semiconductor                | 1         | 1.52%   |
| Logitech                             | 1         | 1.52%   |
| Cirrus Logic                         | 1         | 1.52%   |
| C-Media Electronics                  | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 5.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 5.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 5.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 3.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.56%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.56%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.28%   |
| Thesycon Systemsoftware & Consulting D10s                                                         | 1         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.28%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.28%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Logitech G435 Wireless Gaming Headset                                                             | 1         | 1.28%   |
| Intel USB PnP Sound Device                                                                        | 1         | 1.28%   |
| Intel Multimedia audio controller                                                                 | 1         | 1.28%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.28%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.28%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.28%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.28%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.28%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 22.73%  |
| Unknown             | 11        | 16.67%  |
| Samsung Electronics | 9         | 13.64%  |
| Crucial             | 8         | 12.12%  |
| Micron Technology   | 5         | 7.58%   |
| ELPIDA              | 5         | 7.58%   |
| Kingston            | 3         | 4.55%   |
| Corsair             | 2         | 3.03%   |
| A-DATA Technology   | 2         | 3.03%   |
| Unknown (ABCD)      | 1         | 1.52%   |
| Transcend           | 1         | 1.52%   |
| Qimonda             | 1         | 1.52%   |
| Patriot             | 1         | 1.52%   |
| Hewlett-Packard     | 1         | 1.52%   |
| Cors                | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.86%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 2.86%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.43%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.43%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.43%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.43%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.43%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 1.43%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.43%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 1.43%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT41GU7MFR8C-PB 8192MB DIMM DDR3 1600MT/s          | 1         | 1.43%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.43%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s             | 1         | 1.43%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 1.43%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.43%   |
| SK Hynix RAM H5TC4G63AFR_PBA 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.43%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 1.43%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s              | 1         | 1.43%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.43%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.43%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.43%   |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s              | 1         | 1.43%   |
| Patriot RAM PSD38G16002 8192MB DIMM DDR3 1600MT/s                | 1         | 1.43%   |
| Micron RAM MT53E1G32D4NQ_046 8192MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.43%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s        | 1         | 1.43%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s              | 1         | 1.43%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s            | 1         | 1.43%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 1         | 1.43%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s           | 1         | 1.43%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                             | 1         | 1.43%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s        | 1         | 1.43%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 1         | 1.43%   |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 1.43%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s               | 1         | 1.43%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 1.43%   |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s        | 1         | 1.43%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s            | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 31        | 54.39%  |
| DDR4    | 14        | 24.56%  |
| LPDDR4  | 3         | 5.26%   |
| LPDDR3  | 3         | 5.26%   |
| DDR2    | 2         | 3.51%   |
| SDRAM   | 1         | 1.75%   |
| DRAM    | 1         | 1.75%   |
| DDR     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 52.63%  |
| DIMM         | 23        | 40.35%  |
| Row Of Chips | 4         | 7.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 38.71%  |
| 4096  | 18        | 29.03%  |
| 2048  | 9         | 14.52%  |
| 1024  | 4         | 6.45%   |
| 16384 | 3         | 4.84%   |
| 128   | 2         | 3.23%   |
| 512   | 1         | 1.61%   |
| 256   | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 30%     |
| 1333    | 7         | 11.67%  |
| 2400    | 6         | 10%     |
| 2133    | 5         | 8.33%   |
| 2667    | 4         | 6.67%   |
| Unknown | 4         | 6.67%   |
| 1334    | 3         | 5%      |
| 3600    | 2         | 3.33%   |
| 4267    | 1         | 1.67%   |
| 3200    | 1         | 1.67%   |
| 1867    | 1         | 1.67%   |
| 1866    | 1         | 1.67%   |
| 1800    | 1         | 1.67%   |
| 1400    | 1         | 1.67%   |
| 1200    | 1         | 1.67%   |
| 1067    | 1         | 1.67%   |
| 1066    | 1         | 1.67%   |
| 667     | 1         | 1.67%   |
| 533     | 1         | 1.67%   |

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
| Chicony Electronics                    | 10        | 30.3%   |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Suyin                                  | 3         | 9.09%   |
| Microdia                               | 2         | 6.06%   |
| IMC Networks                           | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.06%   |
| Z-Star Microelectronics                | 1         | 3.03%   |
| Syntek                                 | 1         | 3.03%   |
| Sunplus Innovation Technology          | 1         | 3.03%   |
| Silicon Motion                         | 1         | 3.03%   |
| Quanta                                 | 1         | 3.03%   |
| MacroSilicon                           | 1         | 3.03%   |
| Linux Foundation                       | 1         | 3.03%   |
| Lenovo                                 | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |
| Acer                                   | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 2         | 6.06%   |
| Chicony Integrated Camera                        | 2         | 6.06%   |
| Chicony HD WebCam                                | 2         | 6.06%   |
| Z-Star A4 TECH USB2.0 PC Camera J                | 1         | 3.03%   |
| Syntek EasyCamera                                | 1         | 3.03%   |
| Suyin HP TrueVision HD                           | 1         | 3.03%   |
| Suyin HP High Definition 1MP Webcam              | 1         | 3.03%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 3.03%   |
| Sunplus HD WebCam                                | 1         | 3.03%   |
| Silicon Motion NCM-G102                          | 1         | 3.03%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 3.03%   |
| Realtek Acer 640 x 480 laptop camera             | 1         | 3.03%   |
| Quanta HP TrueVision HD Camera                   | 1         | 3.03%   |
| Microdia Laptop_Integrated_Webcam_2M             | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                    | 1         | 3.03%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]    | 1         | 3.03%   |
| Linux Foundation EEM Gadget                      | 1         | 3.03%   |
| Lenovo Integrated Webcam                         | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                | 1         | 3.03%   |
| IMC Networks Integrated Camera                   | 1         | 3.03%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.03%   |
| Chicony USB2.0 FHD UVC WebCam                    | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)          | 1         | 3.03%   |
| Chicony HP Webcam [2 MP Macro]                   | 1         | 3.03%   |
| Chicony HP HD Camera                             | 1         | 3.03%   |
| Chicony CNF8243 Webcam                           | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE                        | 1         | 3.03%   |
| Acer HP Webcam                                   | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| AuthenTec        | 2         | 33.33%  |
| Synaptics        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 16.67%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 43        | 59.72%  |
| 1     | 19        | 26.39%  |
| 2     | 5         | 6.94%   |
| 3     | 3         | 4.17%   |
| 5     | 1         | 1.39%   |
| 4     | 1         | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 25%     |
| Fingerprint reader       | 6         | 13.64%  |
| Communication controller | 6         | 13.64%  |
| Net/wireless             | 4         | 9.09%   |
| Modem                    | 3         | 6.82%   |
| Unassigned class         | 2         | 4.55%   |
| Sound                    | 2         | 4.55%   |
| Multimedia controller    | 2         | 4.55%   |
| Camera                   | 2         | 4.55%   |
| Unclassified device      | 1         | 2.27%   |
| Storage                  | 1         | 2.27%   |
| Network                  | 1         | 2.27%   |
| Net/ethernet             | 1         | 2.27%   |
| Chipcard                 | 1         | 2.27%   |
| Bluetooth                | 1         | 2.27%   |


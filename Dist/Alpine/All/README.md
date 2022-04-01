Alpine - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Alpine/Desktop/README.md) and [notebooks](/Dist/Alpine/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 86

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 15.28%  |
| Alpine 3.15.0               | 9         | 12.5%   |
| Alpine 3.15.0_alpha20210804 | 7         | 9.72%   |
| Alpine 3.14.0               | 5         | 6.94%   |
| Alpine 3.14.2               | 4         | 5.56%   |
| Alpine 3.13.0_alpha20200917 | 4         | 5.56%   |
| Alpine 3.13.0_alpha20200626 | 4         | 5.56%   |
| Alpine 3.11.2               | 4         | 5.56%   |
| Alpine 3.13.1               | 3         | 4.17%   |
| Alpine 3.13.0_alpha20201218 | 3         | 4.17%   |
| Alpine 3.13.5               | 2         | 2.78%   |
| Alpine 3.13.2               | 2         | 2.78%   |
| Alpine 3.12.3               | 2         | 2.78%   |
| Alpine 3.8.4                | 1         | 1.39%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.39%   |
| Alpine 3.15.2               | 1         | 1.39%   |
| Alpine 3.15.0_rc5           | 1         | 1.39%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.39%   |
| Alpine 3.13.6               | 1         | 1.39%   |
| Alpine 3.13.3               | 1         | 1.39%   |
| Alpine 3.13.0_rc2           | 1         | 1.39%   |
| Alpine 3.12.7               | 1         | 1.39%   |
| Alpine 3.12.1               | 1         | 1.39%   |
| Alpine 3.12.0_rc1           | 1         | 1.39%   |
| Alpine 3.11.5               | 1         | 1.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 67        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.4.43-1-lts           | 8         | 10.96%  |
| 5.15.16-0-lts          | 3         | 4.11%   |
| 5.10.61-0-lts          | 3         | 4.11%   |
| 5.4.84-0-lts           | 2         | 2.74%   |
| 5.4.83-0-lts           | 2         | 2.74%   |
| 5.15.4-0-lts           | 2         | 2.74%   |
| 5.15.12-0-lts          | 2         | 2.74%   |
| 5.10.68-0-lts          | 2         | 2.74%   |
| 5.10.16-0-lts          | 2         | 2.74%   |
| 5.8.12-0-edge          | 1         | 1.37%   |
| 5.8.0                  | 1         | 1.37%   |
| 5.7.4                  | 1         | 1.37%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.37%   |
| 5.4.99                 | 1         | 1.37%   |
| 5.4.73-0-lts           | 1         | 1.37%   |
| 5.4.72-0-lts           | 1         | 1.37%   |
| 5.4.65-0-lts           | 1         | 1.37%   |
| 5.4.64-0-lts           | 1         | 1.37%   |
| 5.4.6-0-lts            | 1         | 1.37%   |
| 5.4.58-0-lts           | 1         | 1.37%   |
| 5.4.57-0-lts           | 1         | 1.37%   |
| 5.4.46-0-lts           | 1         | 1.37%   |
| 5.4.27-0-lts           | 1         | 1.37%   |
| 5.4.111-0-lts          | 1         | 1.37%   |
| 5.4.0-77-generic       | 1         | 1.37%   |
| 5.17.0-0-edge          | 1         | 1.37%   |
| 5.16.12-may            | 1         | 1.37%   |
| 5.16.1-may             | 1         | 1.37%   |
| 5.15.30-0-lts          | 1         | 1.37%   |
| 5.15.28-0-lts          | 1         | 1.37%   |
| 5.15.26-0-lts          | 1         | 1.37%   |
| 5.15.17-0-lts          | 1         | 1.37%   |
| 5.14.8-0-edge          | 1         | 1.37%   |
| 5.13.0-0-edge          | 1         | 1.37%   |
| 5.12.8-0-edge          | 1         | 1.37%   |
| 5.10.81                | 1         | 1.37%   |
| 5.10.72-1-lts          | 1         | 1.37%   |
| 5.10.70-0-lts          | 1         | 1.37%   |
| 5.10.69-0-lts          | 1         | 1.37%   |
| 5.10.66-0-lts          | 1         | 1.37%   |
| 5.10.5-0-lts           | 1         | 1.37%   |
| 5.10.44-0-lts          | 1         | 1.37%   |
| 5.10.43-0-lts          | 1         | 1.37%   |
| 5.10.42-0-legacy       | 1         | 1.37%   |
| 5.10.4-0-lts           | 1         | 1.37%   |
| 5.10.38-0-lts          | 1         | 1.37%   |
| 5.10.29-0-lts          | 1         | 1.37%   |
| 5.10.24-0-lts          | 1         | 1.37%   |
| 5.10.12-0-lts          | 1         | 1.37%   |
| 5.10.11-0-lts          | 1         | 1.37%   |
| 5.10.1-0-lts           | 1         | 1.37%   |
| 4.4.59+                | 1         | 1.37%   |
| 4.14.89-0-vanilla      | 1         | 1.37%   |
| 3.10.98-poky-edison+   | 1         | 1.37%   |
| 3.10.18                | 1         | 1.37%   |
| 3.10.105               | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.43   | 8         | 10.96%  |
| 5.15.16  | 3         | 4.11%   |
| 5.10.61  | 3         | 4.11%   |
| 5.4.84   | 2         | 2.74%   |
| 5.4.83   | 2         | 2.74%   |
| 5.15.4   | 2         | 2.74%   |
| 5.15.12  | 2         | 2.74%   |
| 5.10.68  | 2         | 2.74%   |
| 5.10.16  | 2         | 2.74%   |
| 5.8.12   | 1         | 1.37%   |
| 5.8.0    | 1         | 1.37%   |
| 5.7.4    | 1         | 1.37%   |
| 5.6.2    | 1         | 1.37%   |
| 5.4.99   | 1         | 1.37%   |
| 5.4.73   | 1         | 1.37%   |
| 5.4.72   | 1         | 1.37%   |
| 5.4.65   | 1         | 1.37%   |
| 5.4.64   | 1         | 1.37%   |
| 5.4.6    | 1         | 1.37%   |
| 5.4.58   | 1         | 1.37%   |
| 5.4.57   | 1         | 1.37%   |
| 5.4.46   | 1         | 1.37%   |
| 5.4.27   | 1         | 1.37%   |
| 5.4.111  | 1         | 1.37%   |
| 5.4.0    | 1         | 1.37%   |
| 5.17.0   | 1         | 1.37%   |
| 5.16.12  | 1         | 1.37%   |
| 5.16.1   | 1         | 1.37%   |
| 5.15.30  | 1         | 1.37%   |
| 5.15.28  | 1         | 1.37%   |
| 5.15.26  | 1         | 1.37%   |
| 5.15.17  | 1         | 1.37%   |
| 5.14.8   | 1         | 1.37%   |
| 5.13.0   | 1         | 1.37%   |
| 5.12.8   | 1         | 1.37%   |
| 5.10.81  | 1         | 1.37%   |
| 5.10.72  | 1         | 1.37%   |
| 5.10.70  | 1         | 1.37%   |
| 5.10.69  | 1         | 1.37%   |
| 5.10.66  | 1         | 1.37%   |
| 5.10.5   | 1         | 1.37%   |
| 5.10.44  | 1         | 1.37%   |
| 5.10.43  | 1         | 1.37%   |
| 5.10.42  | 1         | 1.37%   |
| 5.10.4   | 1         | 1.37%   |
| 5.10.38  | 1         | 1.37%   |
| 5.10.29  | 1         | 1.37%   |
| 5.10.24  | 1         | 1.37%   |
| 5.10.12  | 1         | 1.37%   |
| 5.10.11  | 1         | 1.37%   |
| 5.10.1   | 1         | 1.37%   |
| 4.4.59   | 1         | 1.37%   |
| 4.14.89  | 1         | 1.37%   |
| 3.10.98  | 1         | 1.37%   |
| 3.10.18  | 1         | 1.37%   |
| 3.10.105 | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 33.33%  |
| 5.10    | 21        | 30.43%  |
| 5.15    | 11        | 15.94%  |
| 3.10    | 3         | 4.35%   |
| 5.8     | 2         | 2.9%    |
| 5.7     | 1         | 1.45%   |
| 5.6     | 1         | 1.45%   |
| 5.17    | 1         | 1.45%   |
| 5.16    | 1         | 1.45%   |
| 5.14    | 1         | 1.45%   |
| 5.13    | 1         | 1.45%   |
| 5.12    | 1         | 1.45%   |
| 4.4     | 1         | 1.45%   |
| 4.14    | 1         | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 88.06%  |
| i686   | 6         | 8.96%   |
| i586   | 1         | 1.49%   |
| armv7l | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 83.58%  |
| XFCE    | 4         | 5.97%   |
| GNOME   | 4         | 5.97%   |
| KDE5    | 1         | 1.49%   |
| KDE     | 1         | 1.49%   |
| i3      | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 64.71%  |
| X11     | 19        | 27.94%  |
| Wayland | 4         | 5.88%   |
| Tty     | 1         | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 89.71%  |
| LightDM | 3         | 4.41%   |
| XDM     | 1         | 1.47%   |
| SDDM    | 1         | 1.47%   |
| LXDM    | 1         | 1.47%   |
| GDM     | 1         | 1.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 39        | 57.35%  |
| Unknown | 22        | 32.35%  |
| en_US   | 4         | 5.88%   |
| ru_RU   | 2         | 2.94%   |
| en_GB   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 48        | 71.64%  |
| EFI  | 19        | 28.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 79.41%  |
| Btrfs   | 5         | 7.35%   |
| Tmpfs   | 3         | 4.41%   |
| Overlay | 2         | 2.94%   |
| Unknown | 2         | 2.94%   |
| F2fs    | 1         | 1.47%   |
| Ext2    | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 53.52%  |
| GPT     | 23        | 32.39%  |
| MBR     | 10        | 14.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 89.55%  |
| Yes       | 7         | 10.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 91.18%  |
| Yes       | 6         | 8.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 17.91%  |
| Dell                | 12        | 17.91%  |
| Lenovo              | 8         | 11.94%  |
| ASUSTek Computer    | 7         | 10.45%  |
| Acer                | 4         | 5.97%   |
| Intel               | 2         | 2.99%   |
| IBM                 | 2         | 2.99%   |
| Gigabyte Technology | 2         | 2.99%   |
| ASRock              | 2         | 2.99%   |
| Unknown             | 2         | 2.99%   |
| VIA Technologies    | 1         | 1.49%   |
| Synology            | 1         | 1.49%   |
| Supermicro          | 1         | 1.49%   |
| Shuttle             | 1         | 1.49%   |
| Pegatron            | 1         | 1.49%   |
| MSI                 | 1         | 1.49%   |
| Haier               | 1         | 1.49%   |
| Google              | 1         | 1.49%   |
| Gateway             | 1         | 1.49%   |
| Fujitsu             | 1         | 1.49%   |
| F5 Networks         | 1         | 1.49%   |
| eMachines           | 1         | 1.49%   |
| Apple               | 1         | 1.49%   |
| AMI                 | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP ProLiant DL360 G6                     | 2         | 2.99%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 2.99%   |
| Unknown                                  | 2         | 2.99%   |
| VIA KM266APro-835                        | 1         | 1.49%   |
| Synology DS1019+                         | 1         | 1.49%   |
| Supermicro X10SLL-F                      | 1         | 1.49%   |
| Shuttle DS81D                            | 1         | 1.49%   |
| Pegatron Deepcam                         | 1         | 1.49%   |
| MSI GL72M 7REX                           | 1         | 1.49%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.49%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.49%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.49%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.49%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.49%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 1.49%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.49%   |
| Intel NUC6i7KYB H90766-406               | 1         | 1.49%   |
| Intel Merrifield                         | 1         | 1.49%   |
| IBM 26446AG                              | 1         | 1.49%   |
| IBM 264070A                              | 1         | 1.49%   |
| HP ZBook 15 G5                           | 1         | 1.49%   |
| HP Stream 7 Tablet                       | 1         | 1.49%   |
| HP ProLiant MicroServer Gen8             | 1         | 1.49%   |
| HP Mini 110-3500                         | 1         | 1.49%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.49%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.49%   |
| HP EliteBook 2740p                       | 1         | 1.49%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.49%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.49%   |
| HP 23-p030na                             | 1         | 1.49%   |
| Haier U144S                              | 1         | 1.49%   |
| Google Samus                             | 1         | 1.49%   |
| Gateway MX3631m                          | 1         | 1.49%   |
| Fujitsu PRIMERGY TX100 S2                | 1         | 1.49%   |
| F5 Networks C117                         | 1         | 1.49%   |
| eMachines EL1352G                        | 1         | 1.49%   |
| Dell XPS 15 7590                         | 1         | 1.49%   |
| Dell XPS 13 7390 2-in-1                  | 1         | 1.49%   |
| Dell Studio 1747                         | 1         | 1.49%   |
| Dell PowerEdge T640                      | 1         | 1.49%   |
| Dell PowerEdge R510                      | 1         | 1.49%   |
| Dell OptiPlex 755                        | 1         | 1.49%   |
| Dell OptiPlex 3020M                      | 1         | 1.49%   |
| Dell OptiPlex 3010                       | 1         | 1.49%   |
| Dell Inspiron MM061                      | 1         | 1.49%   |
| Dell Inspiron 5566                       | 1         | 1.49%   |
| Dell Inspiron 3647                       | 1         | 1.49%   |
| Dell Inspiron 3180                       | 1         | 1.49%   |
| ASUS ZenBook UX431FA                     | 1         | 1.49%   |
| ASUS X550EA                              | 1         | 1.49%   |
| ASUS X200MA                              | 1         | 1.49%   |
| ASUS TS10                                | 1         | 1.49%   |
| ASUS PRIME H370M-PLUS                    | 1         | 1.49%   |
| ASUS P8H67-V                             | 1         | 1.49%   |
| ASUS E502SA                              | 1         | 1.49%   |
| ASRock J3455M                            | 1         | 1.49%   |
| ASRock D1800B-ITX                        | 1         | 1.49%   |
| Apple Macmini6,2                         | 1         | 1.49%   |
| AMI Aptio CRB                            | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 7.46%   |
| Dell Inspiron       | 4         | 5.97%   |
| Acer Aspire         | 4         | 5.97%   |
| HP ProLiant         | 3         | 4.48%   |
| Dell OptiPlex       | 3         | 4.48%   |
| HP EliteBook        | 2         | 2.99%   |
| Gigabyte Z490I      | 2         | 2.99%   |
| Dell XPS            | 2         | 2.99%   |
| Dell PowerEdge      | 2         | 2.99%   |
| Unknown             | 2         | 2.99%   |
| VIA KM266APro-835   | 1         | 1.49%   |
| Synology DS1019+    | 1         | 1.49%   |
| Supermicro X10SLL-F | 1         | 1.49%   |
| Shuttle DS81D       | 1         | 1.49%   |
| Pegatron Deepcam    | 1         | 1.49%   |
| MSI GL72M           | 1         | 1.49%   |
| Lenovo Yoga         | 1         | 1.49%   |
| Lenovo ThinkCentre  | 1         | 1.49%   |
| Lenovo IdeaPad      | 1         | 1.49%   |
| Intel NUC6i7KYB     | 1         | 1.49%   |
| Intel Merrifield    | 1         | 1.49%   |
| IBM 26446AG         | 1         | 1.49%   |
| IBM 264070A         | 1         | 1.49%   |
| HP ZBook            | 1         | 1.49%   |
| HP Stream           | 1         | 1.49%   |
| HP Mini             | 1         | 1.49%   |
| HP Laptop           | 1         | 1.49%   |
| HP ENVY             | 1         | 1.49%   |
| HP Compaq           | 1         | 1.49%   |
| HP 23-p030na        | 1         | 1.49%   |
| Haier U144S         | 1         | 1.49%   |
| Google Samus        | 1         | 1.49%   |
| Gateway MX3631m     | 1         | 1.49%   |
| Fujitsu PRIMERGY    | 1         | 1.49%   |
| F5 Networks C117    | 1         | 1.49%   |
| eMachines EL1352G   | 1         | 1.49%   |
| Dell Studio         | 1         | 1.49%   |
| ASUS ZenBook        | 1         | 1.49%   |
| ASUS X550EA         | 1         | 1.49%   |
| ASUS X200MA         | 1         | 1.49%   |
| ASUS TS10           | 1         | 1.49%   |
| ASUS PRIME          | 1         | 1.49%   |
| ASUS P8H67-V        | 1         | 1.49%   |
| ASUS E502SA         | 1         | 1.49%   |
| ASRock J3455M       | 1         | 1.49%   |
| ASRock D1800B-ITX   | 1         | 1.49%   |
| Apple Macmini6      | 1         | 1.49%   |
| AMI Aptio           | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 10        | 14.93%  |
| 2019    | 7         | 10.45%  |
| 2018    | 7         | 10.45%  |
| 2016    | 5         | 7.46%   |
| 2010    | 5         | 7.46%   |
| 2017    | 4         | 5.97%   |
| 2015    | 4         | 5.97%   |
| 2009    | 4         | 5.97%   |
| 2020    | 3         | 4.48%   |
| 2013    | 3         | 4.48%   |
| 2012    | 3         | 4.48%   |
| 2021    | 2         | 2.99%   |
| 2011    | 2         | 2.99%   |
| 2007    | 2         | 2.99%   |
| Unknown | 2         | 2.99%   |
| 2006    | 1         | 1.49%   |
| 2005    | 1         | 1.49%   |
| 2004    | 1         | 1.49%   |
| 1999    | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 53.73%  |
| Desktop     | 17        | 25.37%  |
| Server      | 6         | 8.96%   |
| Mini pc     | 4         | 5.97%   |
| Tablet      | 2         | 2.99%   |
| Convertible | 1         | 1.49%   |
| All in one  | 1         | 1.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 67        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 98.51%  |
| Yes  | 1         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 14        | 20%     |
| 16.01-24.0      | 13        | 18.57%  |
| 4.01-8.0        | 12        | 17.14%  |
| 8.01-16.0       | 11        | 15.71%  |
| 0.51-1.0        | 6         | 8.57%   |
| 1.01-2.0        | 4         | 5.71%   |
| 32.01-64.0      | 3         | 4.29%   |
| 64.01-256.0     | 3         | 4.29%   |
| 0.01-0.5        | 3         | 4.29%   |
| More than 256.0 | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 21        | 29.58%  |
| 1.01-2.0  | 12        | 16.9%   |
| 0.51-1.0  | 9         | 12.68%  |
| 3.01-4.0  | 8         | 11.27%  |
| 4.01-8.0  | 6         | 8.45%   |
| 2.01-3.0  | 6         | 8.45%   |
| 8.01-16.0 | 4         | 5.63%   |
| Unknown   | 3         | 4.23%   |
| 0         | 2         | 2.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 60.87%  |
| 2      | 14        | 20.29%  |
| 4      | 4         | 5.8%    |
| 3      | 3         | 4.35%   |
| 14     | 2         | 2.9%    |
| 10     | 1         | 1.45%   |
| 7      | 1         | 1.45%   |
| 5      | 1         | 1.45%   |
| 0      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 80.6%   |
| Yes       | 13        | 19.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 83.58%  |
| No        | 11        | 16.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 62.69%  |
| No        | 25        | 37.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 55.22%  |
| Yes       | 30        | 44.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 27.94%  |
| Russia      | 7         | 10.29%  |
| Canada      | 7         | 10.29%  |
| UK          | 5         | 7.35%   |
| Germany     | 4         | 5.88%   |
| Sweden      | 3         | 4.41%   |
| Norway      | 2         | 2.94%   |
| Guatemala   | 2         | 2.94%   |
| Brazil      | 2         | 2.94%   |
| Venezuela   | 1         | 1.47%   |
| Ukraine     | 1         | 1.47%   |
| Switzerland | 1         | 1.47%   |
| Spain       | 1         | 1.47%   |
| South Korea | 1         | 1.47%   |
| Slovakia    | 1         | 1.47%   |
| Portugal    | 1         | 1.47%   |
| Poland      | 1         | 1.47%   |
| Pakistan    | 1         | 1.47%   |
| Mexico      | 1         | 1.47%   |
| Italy       | 1         | 1.47%   |
| Indonesia   | 1         | 1.47%   |
| France      | 1         | 1.47%   |
| Egypt       | 1         | 1.47%   |
| Czechia     | 1         | 1.47%   |
| Austria     | 1         | 1.47%   |
| Australia   | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| St Petersburg      | 5         | 7.25%   |
| Manitowoc          | 5         | 7.25%   |
| Vernon             | 2         | 2.9%    |
| Stratford          | 2         | 2.9%    |
| Guatemala City     | 2         | 2.9%    |
| As                 | 2         | 2.9%    |
| Zurich             | 1         | 1.45%   |
| Verona             | 1         | 1.45%   |
| Tymovskoye         | 1         | 1.45%   |
| Topeka             | 1         | 1.45%   |
| Thame              | 1         | 1.45%   |
| Tanvald            | 1         | 1.45%   |
| Tampa              | 1         | 1.45%   |
| Sydney             | 1         | 1.45%   |
| Suwon              | 1         | 1.45%   |
| Street             | 1         | 1.45%   |
| Stockholm          | 1         | 1.45%   |
| Sisteron           | 1         | 1.45%   |
| Sant Pere de Ribes | 1         | 1.45%   |
| Sankt PГ¶lten    | 1         | 1.45%   |
| San Mateo          | 1         | 1.45%   |
| RzeszГіw         | 1         | 1.45%   |
| Rostock            | 1         | 1.45%   |
| Redwood City       | 1         | 1.45%   |
| Plymouth           | 1         | 1.45%   |
| Ottawa             | 1         | 1.45%   |
| Nuremberg          | 1         | 1.45%   |
| MГ©rida          | 1         | 1.45%   |
| Munich             | 1         | 1.45%   |
| Merrill            | 1         | 1.45%   |
| Mankato            | 1         | 1.45%   |
| Mamaroneck         | 1         | 1.45%   |
| London             | 1         | 1.45%   |
| Lincoln            | 1         | 1.45%   |
| Larkspur           | 1         | 1.45%   |
| Lahore             | 1         | 1.45%   |
| Kitchener          | 1         | 1.45%   |
| Kirkland           | 1         | 1.45%   |
| Kharkiv            | 1         | 1.45%   |
| Kaliningrad        | 1         | 1.45%   |
| Jember             | 1         | 1.45%   |
| Indaiatuba         | 1         | 1.45%   |
| Hilden             | 1         | 1.45%   |
| Hampstead          | 1         | 1.45%   |
| Gothenburg         | 1         | 1.45%   |
| Funchal            | 1         | 1.45%   |
| Franklin           | 1         | 1.45%   |
| Ecatepec           | 1         | 1.45%   |
| Dallas             | 1         | 1.45%   |
| Chapel Hill        | 1         | 1.45%   |
| Cairo              | 1         | 1.45%   |
| Brockport          | 1         | 1.45%   |
| Bratislava         | 1         | 1.45%   |
| Boucherville       | 1         | 1.45%   |
| Belém             | 1         | 1.45%   |
| Barrow in Furness  | 1         | 1.45%   |
| Bandhagen          | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 19     | 13.48%  |
| WDC                 | 11        | 35     | 12.36%  |
| Seagate             | 10        | 28     | 11.24%  |
| Unknown             | 6         | 8      | 6.74%   |
| Hitachi             | 5         | 5      | 5.62%   |
| HGST                | 5         | 5      | 5.62%   |
| Crucial             | 5         | 11     | 5.62%   |
| Toshiba             | 4         | 5      | 4.49%   |
| SK Hynix            | 4         | 6      | 4.49%   |
| Kingston            | 4         | 4      | 4.49%   |
| Intel               | 4         | 8      | 4.49%   |
| Transcend           | 2         | 2      | 2.25%   |
| SanDisk             | 2         | 2      | 2.25%   |
| LITEON              | 2         | 2      | 2.25%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| STEC                | 1         | 1      | 1.12%   |
| SPCC                | 1         | 1      | 1.12%   |
| NETAPP              | 1         | 1      | 1.12%   |
| Lexar               | 1         | 1      | 1.12%   |
| KC600               | 1         | 1      | 1.12%   |
| JMicron             | 1         | 1      | 1.12%   |
| Intenso             | 1         | 1      | 1.12%   |
| IBM                 | 1         | 1      | 1.12%   |
| Dell                | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| AMD                 | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WD3000BLFS-60YBU2 304GB               | 2         | 2.04%   |
| Unknown MMC Card  16GB                    | 2         | 2.04%   |
| Seagate ST4000VN008-2DR1 4TB              | 2         | 2.04%   |
| Samsung SSD 960 EVO 500GB                 | 2         | 2.04%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 2.04%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 2.04%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 1.02%   |
| WDC WDS250G2B0A 250GB SSD                 | 1         | 1.02%   |
| WDC WD80EMAZ-00WJTA0 8TB                  | 1         | 1.02%   |
| WDC WD80EFAX-68LHPN0 8TB                  | 1         | 1.02%   |
| WDC WD5003ABYZ-0 500GB                    | 1         | 1.02%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 1.02%   |
| WDC WD20EZRZ-00Z 2TB                      | 1         | 1.02%   |
| WDC WD140EDFZ-11A0VA0 14TB                | 1         | 1.02%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.02%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 1.02%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 1.02%   |
| Unknown SD64G  64GB                       | 1         | 1.02%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 1.02%   |
| Unknown MMC Card  4GB                     | 1         | 1.02%   |
| Unknown MMC Card  32GB                    | 1         | 1.02%   |
| Transcend TS128GSSD420I 128GB             | 1         | 1.02%   |
| Transcend SSD 1GB                         | 1         | 1.02%   |
| Toshiba NVMe SSD Drive 256GB              | 1         | 1.02%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.02%   |
| Toshiba MK3252GS 320GB                    | 1         | 1.02%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.02%   |
| Toshiba KBG40ZPZ512G NVMe 512GB           | 1         | 1.02%   |
| STEC SDT5A-S200SS 200GB                   | 1         | 1.02%   |
| SPCC Solid State Disk 256GB               | 1         | 1.02%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 1.02%   |
| SK Hynix SC300 M.2 2280 256 256GB SSD     | 1         | 1.02%   |
| SK Hynix HFS480G3H2X069N 480GB            | 1         | 1.02%   |
| SK Hynix HBG4e  32GB                      | 1         | 1.02%   |
| Seagate ST98823A 80GB                     | 1         | 1.02%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 1.02%   |
| Seagate ST4000VN008-2DR166 4TB            | 1         | 1.02%   |
| Seagate ST380815AS 80GB                   | 1         | 1.02%   |
| Seagate ST3500418AS 500GB                 | 1         | 1.02%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 1.02%   |
| Seagate ST2000DL001-9VT1 2TB              | 1         | 1.02%   |
| Seagate ST1000LM048-2E71 1TB              | 1         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.02%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1.02%   |
| SanDisk SDSA6MM 16GB SSD                  | 1         | 1.02%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.02%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 1.02%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 1.02%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 1.02%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 1.02%   |
| Samsung SP0411N 40GB                      | 1         | 1.02%   |
| Samsung Portable SSD T5 1TB               | 1         | 1.02%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.02%   |
| Samsung MZVLB512HBJQ-000L7 512GB          | 1         | 1.02%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 1.02%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 1.02%   |
| Samsung HM160HI 160GB                     | 1         | 1.02%   |
| NETAPP X423_HCOBE900A10 900GB             | 1         | 1.02%   |
| LITEON CV3-CE128 128GB SSD                | 1         | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 28     | 30.3%   |
| WDC                 | 8         | 31     | 24.24%  |
| Hitachi             | 5         | 5      | 15.15%  |
| HGST                | 5         | 5      | 15.15%  |
| Toshiba             | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 4      | 6.06%   |
| IBM                 | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 13.89%  |
| Crucial             | 5         | 11     | 13.89%  |
| Kingston            | 4         | 4      | 11.11%  |
| WDC                 | 2         | 2      | 5.56%   |
| Transcend           | 2         | 2      | 5.56%   |
| SK Hynix            | 2         | 3      | 5.56%   |
| SanDisk             | 2         | 2      | 5.56%   |
| LITEON              | 2         | 2      | 5.56%   |
| Intel               | 2         | 4      | 5.56%   |
| A-DATA Technology   | 2         | 2      | 5.56%   |
| SPCC                | 1         | 1      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| KC600               | 1         | 1      | 2.78%   |
| JMicron             | 1         | 1      | 2.78%   |
| Intenso             | 1         | 1      | 2.78%   |
| Dell                | 1         | 1      | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| AMD                 | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 32        | 47     | 39.02%  |
| HDD     | 31        | 76     | 37.8%   |
| NVMe    | 13        | 20     | 15.85%  |
| MMC     | 5         | 8      | 6.1%    |
| Unknown | 1         | 2      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 118    | 69.33%  |
| NVMe | 13        | 20     | 17.33%  |
| SAS  | 5         | 7      | 6.67%   |
| MMC  | 5         | 8      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 74     | 69.84%  |
| 0.51-1.0   | 10        | 12     | 15.87%  |
| 1.01-2.0   | 3         | 5      | 4.76%   |
| 4.01-10.0  | 3         | 19     | 4.76%   |
| 3.01-4.0   | 2         | 9      | 3.17%   |
| 10.01-20.0 | 1         | 4      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 17.39%  |
| 1-20           | 12        | 17.39%  |
| Unknown        | 11        | 15.94%  |
| 21-50          | 9         | 13.04%  |
| 251-500        | 8         | 11.59%  |
| 501-1000       | 7         | 10.14%  |
| 2001-3000      | 3         | 4.35%   |
| 1001-2000      | 3         | 4.35%   |
| 51-100         | 3         | 4.35%   |
| More than 3000 | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 40        | 58.82%  |
| Unknown  | 11        | 16.18%  |
| 51-100   | 6         | 8.82%   |
| 21-50    | 4         | 5.88%   |
| 501-1000 | 3         | 4.41%   |
| 251-500  | 2         | 2.94%   |
| 101-250  | 2         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB       | 2         | 14     | 20%     |
| Toshiba MK3252GS 320GB            | 1         | 1      | 10%     |
| Seagate ST2000LM015-2E81 2TB      | 1         | 1      | 10%     |
| SanDisk SDSA6MM 16GB SSD          | 1         | 1      | 10%     |
| Samsung Electronics SP0411N 40GB  | 1         | 2      | 10%     |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 10%     |
| Hitachi HTS725025A9A364 250GB     | 1         | 1      | 10%     |
| Hitachi HTS72101 99GB             | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 47        | 105    | 64.38%  |
| Detected | 16        | 24     | 21.92%  |
| Malfunc  | 10        | 24     | 13.7%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 59.74%  |
| Samsung Electronics          | 7         | 9.09%   |
| AMD                          | 7         | 9.09%   |
| LSI Logic / Symbios Logic    | 3         | 3.9%    |
| Hewlett-Packard              | 2         | 2.6%    |
| VIA Technologies             | 1         | 1.3%    |
| Toshiba America Info Systems | 1         | 1.3%    |
| SK Hynix                     | 1         | 1.3%    |
| Sandisk                      | 1         | 1.3%    |
| Nvidia                       | 1         | 1.3%    |
| Micron/Crucial Technology    | 1         | 1.3%    |
| Marvell Technology Group     | 1         | 1.3%    |
| KIOXIA                       | 1         | 1.3%    |
| Broadcom / LSI               | 1         | 1.3%    |
| ASMedia Technology           | 1         | 1.3%    |
| ADATA Technology             | 1         | 1.3%    |
| Adaptec                      | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 7.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 5.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 4.76%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 3         | 3.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.38%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.38%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.19%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.19%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 1.19%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.19%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.19%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.19%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 1.19%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.19%   |
| Intel SSD 600P Series                                                            | 1         | 1.19%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.19%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 1.19%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 1.19%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1         | 1.19%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.19%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.19%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.19%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.19%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                          | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                          | 1         | 1.19%   |
| HP Smart Array Gen8 Controllers                                                  | 1         | 1.19%   |
| HP Smart Array G6 controllers                                                    | 1         | 1.19%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.19%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.19%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 43        | 55.84%  |
| NVMe | 14        | 18.18%  |
| IDE  | 9         | 11.69%  |
| RAID | 8         | 10.39%  |
| SAS  | 3         | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 57        | 83.82%  |
| AMD    | 10        | 14.71%  |
| ARM    | 1         | 1.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5640 @ 2.27GHz                         | 2         | 2.94%   |
| Intel Core i9-10900 CPU @ 2.80GHz                      | 2         | 2.94%   |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 2         | 2.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 2.94%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 2         | 2.94%   |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 2.94%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz                     | 1         | 1.47%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 1.47%   |
| Intel Xeon CPU X3430 @ 2.40GHz                         | 1         | 1.47%   |
| Intel Xeon CPU L5630 @ 2.13GHz                         | 1         | 1.47%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz                   | 1         | 1.47%   |
| Intel Pentium M processor 1.60GHz                      | 1         | 1.47%   |
| Intel Pentium III (Coppermine)                         | 1         | 1.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz                 | 1         | 1.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 1.47%   |
| Intel Pentium CPU D1508 @ 2.20GHz                      | 1         | 1.47%   |
| Intel Mobile Pentium MMX                               | 1         | 1.47%   |
| Intel Genuine CPU 4000 @ 500MHz                        | 1         | 1.47%   |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 1.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz                      | 1         | 1.47%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz                     | 1         | 1.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 1.47%   |
| Intel Core i7-3615QM CPU @ 2.30GHz                     | 1         | 1.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                     | 1         | 1.47%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 1.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz                       | 1         | 1.47%   |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 1.47%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 1.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 1.47%   |
| Intel Core i5-3450 CPU @ 3.10GHz                       | 1         | 1.47%   |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz                      | 1         | 1.47%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 1.47%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 1.47%   |
| Intel Core i3-4150 CPU @ 3.50GHz                       | 1         | 1.47%   |
| Intel Core i3-3220T CPU @ 2.80GHz                      | 1         | 1.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz                       | 1         | 1.47%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 1.47%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 1.47%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 1.47%   |
| Intel Celeron M processor 1.00GHz                      | 1         | 1.47%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 1.47%   |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 1.47%   |
| Intel Celeron CPU J1800 @ 2.41GHz                      | 1         | 1.47%   |
| Intel Celeron CPU G1850 @ 2.90GHz                      | 1         | 1.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz                      | 1         | 1.47%   |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 1.47%   |
| Intel Atom CPU Z3735G @ 1.33GHz                        | 1         | 1.47%   |
| Intel Atom CPU E3825 @ 1.33GHz                         | 1         | 1.47%   |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 1.47%   |
| AMD Sempron 145 Processor                              | 1         | 1.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 1.47%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx          | 1         | 1.47%   |
| AMD Mobile Duron processor                             | 1         | 1.47%   |
| AMD FX-8350 Eight-Core Processor                       | 1         | 1.47%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1         | 1.47%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G          | 1         | 1.47%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics            | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 13        | 19.12%  |
| Intel Celeron      | 8         | 11.76%  |
| Intel Xeon         | 6         | 8.82%   |
| Intel Core i7      | 6         | 8.82%   |
| Intel Atom         | 6         | 8.82%   |
| Other              | 4         | 5.88%   |
| Intel Core i9      | 3         | 4.41%   |
| Intel Core i3      | 3         | 4.41%   |
| Intel Pentium      | 2         | 2.94%   |
| Intel Core 2 Duo   | 2         | 2.94%   |
| AMD A4             | 2         | 2.94%   |
| Intel Xeon Gold    | 1         | 1.47%   |
| Intel Pentium M    | 1         | 1.47%   |
| Intel Pentium III  | 1         | 1.47%   |
| Intel Pentium Dual | 1         | 1.47%   |
| Intel Genuine      | 1         | 1.47%   |
| Intel Core 2       | 1         | 1.47%   |
| Intel Celeron M    | 1         | 1.47%   |
| AMD Sempron        | 1         | 1.47%   |
| AMD Ryzen 7        | 1         | 1.47%   |
| AMD Ryzen 5        | 1         | 1.47%   |
| AMD FX             | 1         | 1.47%   |
| AMD A6             | 1         | 1.47%   |
| AMD A10            | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 38.24%  |
| 4      | 23        | 33.82%  |
| 1      | 8         | 11.76%  |
| 8      | 3         | 4.41%   |
| 12     | 2         | 2.94%   |
| 10     | 2         | 2.94%   |
| 6      | 2         | 2.94%   |
| 32     | 1         | 1.47%   |
| 3      | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 94.12%  |
| 2      | 4         | 5.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 53.73%  |
| 2      | 31        | 46.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 52.17%  |
| Unknown        | 29        | 42.03%  |
| 32-bit         | 4         | 5.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 48.57%  |
| 0x30678    | 4         | 5.71%   |
| 0x306c3    | 3         | 4.29%   |
| 0x306a9    | 3         | 4.29%   |
| 0x206c2    | 3         | 4.29%   |
| 0x906ea    | 2         | 2.86%   |
| 0x506c9    | 2         | 2.86%   |
| 0x406c4    | 2         | 2.86%   |
| 0x106e5    | 2         | 2.86%   |
| 0x106ca    | 2         | 2.86%   |
| 0x06006704 | 2         | 2.86%   |
| 0xa0655    | 1         | 1.43%   |
| 0x806eb    | 1         | 1.43%   |
| 0x706e5    | 1         | 1.43%   |
| 0x6fd      | 1         | 1.43%   |
| 0x6d8      | 1         | 1.43%   |
| 0x683      | 1         | 1.43%   |
| 0x506e3    | 1         | 1.43%   |
| 0x306d4    | 1         | 1.43%   |
| 0x206a7    | 1         | 1.43%   |
| 0x0810100b | 1         | 1.43%   |
| 0x010000b6 | 1         | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 8         | 11.76%  |
| KabyLake    | 8         | 11.76%  |
| Haswell     | 5         | 7.35%   |
| Westmere    | 4         | 5.88%   |
| IvyBridge   | 4         | 5.88%   |
| Goldmont    | 4         | 5.88%   |
| Skylake     | 3         | 4.41%   |
| P6          | 3         | 4.41%   |
| Excavator   | 3         | 4.41%   |
| Unknown     | 3         | 4.41%   |
| SandyBridge | 2         | 2.94%   |
| Penryn      | 2         | 2.94%   |
| Nehalem     | 2         | 2.94%   |
| IceLake     | 2         | 2.94%   |
| Core        | 2         | 2.94%   |
| CometLake   | 2         | 2.94%   |
| Broadwell   | 2         | 2.94%   |
| Bonnell     | 2         | 2.94%   |
| Zen 2       | 1         | 1.47%   |
| Zen         | 1         | 1.47%   |
| Puma        | 1         | 1.47%   |
| Piledriver  | 1         | 1.47%   |
| K6          | 1         | 1.47%   |
| K10         | 1         | 1.47%   |
| Jaguar      | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 43        | 59.72%  |
| AMD                        | 15        | 20.83%  |
| Nvidia                     | 6         | 8.33%   |
| Matrox Electronics Systems | 4         | 5.56%   |
| Neomagic                   | 2         | 2.78%   |
| VIA Technologies           | 1         | 1.39%   |
| ASPEED Technology          | 1         | 1.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 8.22%   |
| Intel HD Graphics 500                                                                    | 4         | 5.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 4.11%   |
| AMD ES1000                                                                               | 3         | 4.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.74%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 2.74%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.74%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.37%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.37%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.37%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.37%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.37%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.37%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.37%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.37%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.37%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.37%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.37%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.37%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.37%   |
| Intel Iris Pro Graphics 580                                                              | 1         | 1.37%   |
| Intel HD Graphics 630                                                                    | 1         | 1.37%   |
| Intel HD Graphics 620                                                                    | 1         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.37%   |
| Intel Display controller                                                                 | 1         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.37%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 1.37%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 1.37%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.37%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.37%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.37%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.37%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.37%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.37%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.37%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 1.37%   |
| AMD Renoir                                                                               | 1         | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.37%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.37%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 37        | 54.41%  |
| 1 x AMD         | 13        | 19.12%  |
| 1 x Matrox      | 3         | 4.41%   |
| Intel + Nvidia  | 3         | 4.41%   |
| Other           | 2         | 2.94%   |
| 1 x Nvidia      | 2         | 2.94%   |
| 1 x Neomagic    | 2         | 2.94%   |
| 2 x Intel       | 1         | 1.47%   |
| 2 x AMD         | 1         | 1.47%   |
| 1 x VIA         | 1         | 1.47%   |
| Nvidia + Matrox | 1         | 1.47%   |
| Intel + AMD     | 1         | 1.47%   |
| 1 x ASPEED      | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 80%     |
| Unknown     | 12        | 17.14%  |
| Proprietary | 2         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 85.07%  |
| 0.01-0.5   | 7         | 10.45%  |
| 1.01-2.0   | 2         | 2.99%   |
| 0.51-1.0   | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 14.81%  |
| Samsung Electronics     | 5         | 9.26%   |
| Chimei Innolux          | 5         | 9.26%   |
| LG Display              | 4         | 7.41%   |
| Dell                    | 4         | 7.41%   |
| BOE                     | 4         | 7.41%   |
| LG Philips              | 2         | 3.7%    |
| Hewlett-Packard         | 2         | 3.7%    |
| Goldstar                | 2         | 3.7%    |
| Chi Mei Optoelectronics | 2         | 3.7%    |
| AOC                     | 2         | 3.7%    |
| Acer                    | 2         | 3.7%    |
| ViewSonic               | 1         | 1.85%   |
| Sony                    | 1         | 1.85%   |
| Sharp                   | 1         | 1.85%   |
| Lenovo                  | 1         | 1.85%   |
| KVM                     | 1         | 1.85%   |
| InfoVision              | 1         | 1.85%   |
| HannStar                | 1         | 1.85%   |
| Envision                | 1         | 1.85%   |
| EDI                     | 1         | 1.85%   |
| DENON                   | 1         | 1.85%   |
| CSO                     | 1         | 1.85%   |
| BenQ                    | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch         | 2         | 3.7%    |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch                 | 1         | 1.85%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                       | 1         | 1.85%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                  | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch     | 1         | 1.85%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 1.85%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.85%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 1.85%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 1.85%   |
| KVM LCD Monitor 1 7" KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.85%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 1.85%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch             | 1         | 1.85%   |
| Hewlett-Packard All-in-One HWP421A 1920x1080 509x286mm 23.0-inch         | 1         | 1.85%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 1.85%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 1.85%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.85%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 1.85%   |
| EDI VGA TO HDMI EDI1209 1920x1080 480x270mm 21.7-inch                    | 1         | 1.85%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 1.85%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                        | 1         | 1.85%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                        | 1         | 1.85%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                        | 1         | 1.85%   |
| Dell E151FPb DELA005 1024x768 304x228mm 15.0-inch                        | 1         | 1.85%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 1.85%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 1.85%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch           | 1         | 1.85%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                       | 1         | 1.85%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                         | 1         | 1.85%   |
| Acer V173 ACR002F 1280x1024 338x270mm 17.0-inch                          | 1         | 1.85%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                        | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 14        | 25.93%  |
| 1920x1080 (FHD)    | 13        | 24.07%  |
| 3840x2160 (4K)     | 3         | 5.56%   |
| 1280x800 (WXGA)    | 3         | 5.56%   |
| 1280x1024 (SXGA)   | 3         | 5.56%   |
| 3440x1440          | 2         | 3.7%    |
| 2560x1440 (QHD)    | 2         | 3.7%    |
| 1920x1200 (WUXGA)  | 2         | 3.7%    |
| 1600x900 (HD+)     | 2         | 3.7%    |
| 1024x600           | 2         | 3.7%    |
| 2880x1800          | 1         | 1.85%   |
| 2560x1700          | 1         | 1.85%   |
| 2560x1080          | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1440x900 (WXGA+)   | 1         | 1.85%   |
| 1360x768           | 1         | 1.85%   |
| 1280x768           | 1         | 1.85%   |
| 1024x768 (XGA)     | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 22.22%  |
| 13     | 7         | 12.96%  |
| 17     | 6         | 11.11%  |
| 14     | 4         | 7.41%   |
| 23     | 3         | 5.56%   |
| 11     | 3         | 5.56%   |
| 34     | 2         | 3.7%    |
| 27     | 2         | 3.7%    |
| 24     | 2         | 3.7%    |
| 21     | 2         | 3.7%    |
| 12     | 2         | 3.7%    |
| 10     | 2         | 3.7%    |
| 65     | 1         | 1.85%   |
| 32     | 1         | 1.85%   |
| 31     | 1         | 1.85%   |
| 29     | 1         | 1.85%   |
| 25     | 1         | 1.85%   |
| 20     | 1         | 1.85%   |
| 19     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 42.59%  |
| 201-300     | 9         | 16.67%  |
| 501-600     | 7         | 12.96%  |
| 351-400     | 5         | 9.26%   |
| 701-800     | 3         | 5.56%   |
| 601-700     | 3         | 5.56%   |
| 401-500     | 3         | 5.56%   |
| 1001-1500   | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 70.59%  |
| 16/10 | 7         | 13.73%  |
| 5/4   | 3         | 5.88%   |
| 21/9  | 3         | 5.88%   |
| 4/3   | 1         | 1.96%   |
| 3/2   | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 22.22%  |
| 81-90          | 9         | 16.67%  |
| 201-250        | 6         | 11.11%  |
| 351-500        | 4         | 7.41%   |
| 71-80          | 3         | 5.56%   |
| 51-60          | 3         | 5.56%   |
| 301-350        | 3         | 5.56%   |
| 151-200        | 3         | 5.56%   |
| 41-50          | 2         | 3.7%    |
| 141-150        | 2         | 3.7%    |
| 131-140        | 2         | 3.7%    |
| 121-130        | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 61-70          | 1         | 1.85%   |
| 251-300        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 16        | 30.77%  |
| 51-100        | 14        | 26.92%  |
| 121-160       | 12        | 23.08%  |
| 1-50          | 4         | 7.69%   |
| 161-240       | 4         | 7.69%   |
| More than 240 | 2         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 63.77%  |
| 0     | 19        | 27.54%  |
| 2     | 6         | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 33        | 33.33%  |
| Intel                           | 26        | 26.26%  |
| Broadcom                        | 14        | 14.14%  |
| Qualcomm Atheros                | 13        | 13.13%  |
| Xiaomi                          | 2         | 2.02%   |
| VIA Technologies                | 1         | 1.01%   |
| Sigma Designs                   | 1         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 1.01%   |
| Qualcomm                        | 1         | 1.01%   |
| Nvidia                          | 1         | 1.01%   |
| Mellanox Technologies           | 1         | 1.01%   |
| Marvell Technology Group        | 1         | 1.01%   |
| LSI                             | 1         | 1.01%   |
| Dresden Elektronik              | 1         | 1.01%   |
| D-Link System                   | 1         | 1.01%   |
| Broadcom Limited                | 1         | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 18        | 15.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 2.63%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 2.63%   |
| Intel Wireless 8260                                                            | 2         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.75%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.88%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.88%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.88%   |
| Qualcomm Redmi Note 7                                                          | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.88%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.88%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.88%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.88%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.88%   |
| LSI WinModem 56k                                                               | 1         | 0.88%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.88%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.88%   |
| Intel Wireless 7260                                                            | 1         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 0.88%   |
| Intel DH8900CC Null Device                                                     | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 0.88%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 1         | 0.88%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.88%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.88%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                  | 1         | 0.88%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 44.19%  |
| Qualcomm Atheros                | 11        | 25.58%  |
| Broadcom                        | 7         | 16.28%  |
| Realtek Semiconductor           | 3         | 6.98%   |
| Qualcomm Atheros Communications | 1         | 2.33%   |
| Marvell Technology Group        | 1         | 2.33%   |
| Broadcom Limited                | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 13.95%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 6.98%   |
| Intel Wireless 8260                                                            | 2         | 4.65%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 4.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 4.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 4.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 4.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 2.33%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.33%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.33%   |
| Intel Wireless-AC 9260                                                         | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.33%   |
| Intel Wireless 7260                                                            | 1         | 2.33%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 2.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.33%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1         | 2.33%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 1         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 46.88%  |
| Intel                 | 16        | 25%     |
| Broadcom              | 9         | 14.06%  |
| Xiaomi                | 2         | 3.13%   |
| Qualcomm Atheros      | 2         | 3.13%   |
| VIA Technologies      | 1         | 1.56%   |
| Qualcomm              | 1         | 1.56%   |
| Nvidia                | 1         | 1.56%   |
| Mellanox Technologies | 1         | 1.56%   |
| D-Link System         | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 18        | 27.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 6         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 4         | 6.06%   |
| Intel I210 Gigabit Network Connection                                 | 3         | 4.55%   |
| Intel Ethernet Controller I225-V                                      | 2         | 3.03%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                        | 2         | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1         | 1.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.52%   |
| Qualcomm Redmi Note 7                                                 | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.52%   |
| Nvidia MCP61 Ethernet                                                 | 1         | 1.52%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.52%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (6) I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.52%   |
| Intel 82583V Gigabit Network Connection                               | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 1         | 1.52%   |
| Intel 82578DM Gigabit Network Connection                              | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                              | 1         | 1.52%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1         | 1.52%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1         | 1.52%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                        | 1         | 1.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                     | 1         | 1.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.52%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                 | 1         | 1.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 1.52%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.52%   |
| Broadcom BCM4401-B0 100Base-TX                                        | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 53.92%  |
| WiFi     | 42        | 41.18%  |
| Modem    | 4         | 3.92%   |
| Unknown  | 1         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 44        | 58.67%  |
| WiFi     | 31        | 41.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 54.41%  |
| 1     | 21        | 30.88%  |
| 0     | 5         | 7.35%   |
| 4     | 3         | 4.41%   |
| 5     | 1         | 1.47%   |
| 3     | 1         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 86.76%  |
| Yes  | 9         | 13.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 46.67%  |
| Qualcomm Atheros Communications | 3         | 10%     |
| Lite-On Technology              | 3         | 10%     |
| IMC Networks                    | 3         | 10%     |
| Broadcom                        | 3         | 10%     |
| Realtek Semiconductor           | 1         | 3.33%   |
| Marvell Semiconductor           | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Apple                           | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 10%     |
| Intel AX201 Bluetooth                               | 3         | 10%     |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 6.67%   |
| Intel AX200 Bluetooth                               | 2         | 6.67%   |
| IMC Networks Bluetooth Device                       | 2         | 6.67%   |
| Realtek Bluetooth Radio                             | 1         | 3.33%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.33%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.33%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 43        | 69.35%  |
| AMD                       | 10        | 16.13%  |
| Nvidia                    | 2         | 3.23%   |
| VIA Technologies          | 1         | 1.61%   |
| Texas Instruments         | 1         | 1.61%   |
| Sennheiser Communications | 1         | 1.61%   |
| Realtek Semiconductor     | 1         | 1.61%   |
| Logitech                  | 1         | 1.61%   |
| Cirrus Logic              | 1         | 1.61%   |
| C-Media Electronics       | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 5.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 4.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 4.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 4.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 4.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.74%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.74%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.74%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.37%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.37%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.37%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.37%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.37%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Logitech G435 Wireless Gaming Headset                                                             | 1         | 1.37%   |
| Intel USB PnP Sound Device                                                                        | 1         | 1.37%   |
| Intel Multimedia audio controller                                                                 | 1         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.37%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.37%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.37%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.37%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.37%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 23.44%  |
| Unknown             | 11        | 17.19%  |
| Samsung Electronics | 9         | 14.06%  |
| Crucial             | 8         | 12.5%   |
| Micron Technology   | 5         | 7.81%   |
| Elpida              | 5         | 7.81%   |
| Kingston            | 2         | 3.13%   |
| Corsair             | 2         | 3.13%   |
| A-DATA Technology   | 2         | 3.13%   |
| Unknown (ABCD)      | 1         | 1.56%   |
| Transcend           | 1         | 1.56%   |
| Qimonda             | 1         | 1.56%   |
| Hewlett-Packard     | 1         | 1.56%   |
| Cors                | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 2         | 2.99%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s            | 2         | 2.99%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 1.49%   |
| Unknown RAM Module 512MB DIMM                                       | 1         | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                       | 1         | 1.49%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                        | 1         | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 1.49%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 1.49%   |
| Unknown RAM Module 128MB DIMM DRAM                                  | 1         | 1.49%   |
| Unknown RAM Module 128MB DIMM                                       | 1         | 1.49%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.49%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s                  | 1         | 1.49%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.49%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.49%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.49%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.49%   |
| SK Hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 1.49%   |
| SK Hynix RAM HMT41GU7MFR8C-PB 8192MB DIMM DDR3 1600MT/s             | 1         | 1.49%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 1.49%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.49%   |
| SK Hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s                | 1         | 1.49%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 1.49%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 1.49%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| SK Hynix RAM H5TC4G63AFR-PBA 1GB SODIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.49%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.49%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s               | 1         | 1.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s                 | 1         | 1.49%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                 | 1         | 1.49%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.49%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.49%   |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s                 | 1         | 1.49%   |
| Micron RAM MT53E1G32D4NQ_046 8192MB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.49%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s           | 1         | 1.49%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s                 | 1         | 1.49%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.49%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s               | 1         | 1.49%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s              | 1         | 1.49%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                                | 1         | 1.49%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s           | 1         | 1.49%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 1         | 1.49%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 1         | 1.49%   |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s               | 1         | 1.49%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s                  | 1         | 1.49%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.49%   |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Crucial RAM CT102464BF186D.M16 8GB SODIMM DDR3 1867MT/s             | 1         | 1.49%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8192MB DIMM DDR4 2400MT/s           | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 53.57%  |
| DDR4    | 14        | 25%     |
| LPDDR4  | 3         | 5.36%   |
| LPDDR3  | 3         | 5.36%   |
| DDR2    | 2         | 3.57%   |
| SDRAM   | 1         | 1.79%   |
| DRAM    | 1         | 1.79%   |
| DDR     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 53.57%  |
| DIMM         | 22        | 39.29%  |
| Row Of Chips | 4         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 38.33%  |
| 4096  | 18        | 30%     |
| 2048  | 8         | 13.33%  |
| 1024  | 4         | 6.67%   |
| 16384 | 3         | 5%      |
| 128   | 2         | 3.33%   |
| 512   | 1         | 1.67%   |
| 256   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 29.31%  |
| 1333    | 7         | 12.07%  |
| 2400    | 6         | 10.34%  |
| 2667    | 4         | 6.9%    |
| 2133    | 4         | 6.9%    |
| Unknown | 4         | 6.9%    |
| 1334    | 3         | 5.17%   |
| 3600    | 2         | 3.45%   |
| 4267    | 1         | 1.72%   |
| 3200    | 1         | 1.72%   |
| 1867    | 1         | 1.72%   |
| 1866    | 1         | 1.72%   |
| 1800    | 1         | 1.72%   |
| 1400    | 1         | 1.72%   |
| 1200    | 1         | 1.72%   |
| 1067    | 1         | 1.72%   |
| 1066    | 1         | 1.72%   |
| 667     | 1         | 1.72%   |
| 533     | 1         | 1.72%   |

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
| Chicony Electronics                    | 9         | 29.03%  |
| Realtek Semiconductor                  | 4         | 12.9%   |
| Suyin                                  | 3         | 9.68%   |
| Microdia                               | 2         | 6.45%   |
| IMC Networks                           | 2         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.45%   |
| Syntek                                 | 1         | 3.23%   |
| Sunplus Innovation Technology          | 1         | 3.23%   |
| Silicon Motion                         | 1         | 3.23%   |
| Quanta                                 | 1         | 3.23%   |
| MacroSilicon                           | 1         | 3.23%   |
| Linux Foundation                       | 1         | 3.23%   |
| Lenovo                                 | 1         | 3.23%   |
| Apple                                  | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 2         | 6.45%   |
| Chicony Integrated Camera                        | 2         | 6.45%   |
| Chicony HD WebCam                                | 2         | 6.45%   |
| Syntek EasyCamera                                | 1         | 3.23%   |
| Suyin HP TrueVision HD                           | 1         | 3.23%   |
| Suyin HP High Definition 1MP Webcam              | 1         | 3.23%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 3.23%   |
| Sunplus HD WebCam                                | 1         | 3.23%   |
| Silicon Motion NCM-G102                          | 1         | 3.23%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 3.23%   |
| Realtek Acer 640 x 480 laptop camera             | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera                   | 1         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_2M             | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                    | 1         | 3.23%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]    | 1         | 3.23%   |
| Linux Foundation EEM Gadget                      | 1         | 3.23%   |
| Lenovo Integrated Webcam                         | 1         | 3.23%   |
| IMC Networks USB2.0 HD UVC WebCam                | 1         | 3.23%   |
| IMC Networks Integrated Camera                   | 1         | 3.23%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.23%   |
| Chicony USB2.0 FHD UVC WebCam                    | 1         | 3.23%   |
| Chicony Integrated Camera (1280x720@30)          | 1         | 3.23%   |
| Chicony HP Webcam [2 MP Macro]                   | 1         | 3.23%   |
| Chicony HP HD Camera                             | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.23%   |
| Apple iPhone 5/5C/5S/6/SE                        | 1         | 3.23%   |
| Acer HP Webcam                                   | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Synaptics        | 1         | 20%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 20%     |
| AuthenTec AES2810                                                          | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 59.42%  |
| 1     | 19        | 27.54%  |
| 2     | 5         | 7.25%   |
| 3     | 2         | 2.9%    |
| 5     | 1         | 1.45%   |
| 4     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 24.39%  |
| Communication controller | 6         | 14.63%  |
| Fingerprint reader       | 5         | 12.2%   |
| Net/wireless             | 3         | 7.32%   |
| Modem                    | 3         | 7.32%   |
| Unassigned class         | 2         | 4.88%   |
| Sound                    | 2         | 4.88%   |
| Multimedia controller    | 2         | 4.88%   |
| Camera                   | 2         | 4.88%   |
| Unclassified device      | 1         | 2.44%   |
| Storage                  | 1         | 2.44%   |
| Network                  | 1         | 2.44%   |
| Net/ethernet             | 1         | 2.44%   |
| Chipcard                 | 1         | 2.44%   |
| Bluetooth                | 1         | 2.44%   |


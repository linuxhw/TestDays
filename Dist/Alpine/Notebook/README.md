Alpine - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 65

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Google   | Leona                       | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| Dell     | Inspiron 3558               | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo   | ThinkPad X131e 33711Q7      | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Lenovo   | ThinkPad X131e 33711Q7      | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| Dell     | Inspiron N5010              | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell     | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| HP       | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Toshiba  | Satellite M645              | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba  | Satellite M645              | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell     | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu  | LIFEBOOK P702               | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Sony     | VGN-UX27GN                  | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM      | ThinkPad X40 2371LBG        | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP       | EliteBook 8460p             | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| ASUSTek  | X555LAB                     | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| HP       | ENVY Sleekbook 6 PC         | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP       | ENVY Sleekbook 6 PC         | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek  | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek  | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP       | ProBook 4310s               | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Haier    | U144S                       | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer     | Aspire E5-553G              | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo   | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell     | XPS 15 7590                 | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek  | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| ASUSTek  | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP       | EliteBook 1040 G3 Notebo... | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| MSI      | GL72M 7REX                  | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Lenovo   | ThinkPad W700 2752RZ2       | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Dell     | Inspiron MM061              | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| ASUSTek  | X550EA                      | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP       | Compaq Mini CQ10-600        | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo   | IdeaPad 320-15AST 80XV      | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo   | Yoga 14sARH 2021 82LB       | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown  | Unknown                     | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| Pegatron | Deepcam                     | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| HP       | EliteBook 2740p             | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP       | EliteBook 2740p             | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek  | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP       | Laptop 14-dq1xxx            | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM      | 264070A                     | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP       | Mini 110-3500               | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP       | ENVY Sleekbook 6 PC         | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Acer     | Aspire ES1-512              | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer     | Aspire 5920G                | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP       | Compaq Mini CQ10-600        | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway  | MX3631m                     | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell     | Studio 1747                 | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| Dell     | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell     | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek  | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM      | 26446AG                     | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM      | 26446AG                     | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| Google   | Samus                       | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Dell     | Inspiron 5566               | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Apple    | MacBook7,1                  | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Lenovo   | ThinkPad 11e 20ED001HUS     | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer     | Aspire ES1-111M             | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| Lenovo   | ThinkPad E485 20KUCTO1WW    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| HP       | ZBook 15 G5                 | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology | DS1019+                     | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology | DS1019+                     | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology | DS1019+                     | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.16.0               | 6         | 11.32%  |
| Alpine 3.15.0               | 6         | 11.32%  |
| Alpine 3.15.0_alpha20210804 | 4         | 7.55%   |
| Alpine 3.14.0               | 4         | 7.55%   |
| Alpine 3.12.0               | 4         | 7.55%   |
| Alpine 3.17.0               | 3         | 5.66%   |
| Alpine 3.16.2               | 2         | 3.77%   |
| Alpine 3.14.2               | 2         | 3.77%   |
| Alpine 3.13.5               | 2         | 3.77%   |
| Alpine 3.13.0_alpha20201218 | 2         | 3.77%   |
| Alpine 3.13.0_alpha20200917 | 2         | 3.77%   |
| Alpine 3.11.2               | 2         | 3.77%   |
| Alpine 3.17_alpha20220809   | 1         | 1.89%   |
| Alpine 3.17.1               | 1         | 1.89%   |
| Alpine 3.16.1               | 1         | 1.89%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.89%   |
| Alpine 3.15.4               | 1         | 1.89%   |
| Alpine 3.15.2               | 1         | 1.89%   |
| Alpine 3.15.0_rc5           | 1         | 1.89%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.89%   |
| Alpine 3.13.1               | 1         | 1.89%   |
| Alpine 3.13.0_rc2           | 1         | 1.89%   |
| Alpine 3.13.0_alpha20200626 | 1         | 1.89%   |
| Alpine 3.12.3               | 1         | 1.89%   |
| Alpine 3.12.1               | 1         | 1.89%   |
| Alpine 3.11.5               | 1         | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.83-0-lts           | 2         | 3.7%    |
| 5.4.43-1-lts           | 2         | 3.7%    |
| 5.15.86-0-lts          | 2         | 3.7%    |
| 5.15.59-0-lts          | 2         | 3.7%    |
| 5.15.47-0-lts          | 2         | 3.7%    |
| 5.15.41-0-lts          | 2         | 3.7%    |
| 5.15.4-0-lts           | 2         | 3.7%    |
| 5.8.12-0-edge          | 1         | 1.85%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.85%   |
| 5.4.84-0-lts           | 1         | 1.85%   |
| 5.4.72-0-lts           | 1         | 1.85%   |
| 5.4.64-0-lts           | 1         | 1.85%   |
| 5.4.46-0-lts           | 1         | 1.85%   |
| 5.4.27-0-lts           | 1         | 1.85%   |
| 5.17.9-0-edge          | 1         | 1.85%   |
| 5.17.0-0-edge          | 1         | 1.85%   |
| 5.16.12-may            | 1         | 1.85%   |
| 5.16.1-may             | 1         | 1.85%   |
| 5.15.89-0-lts          | 1         | 1.85%   |
| 5.15.85-0-lts          | 1         | 1.85%   |
| 5.15.73-0-lts          | 1         | 1.85%   |
| 5.15.60-0-lts          | 1         | 1.85%   |
| 5.15.46-1-lts          | 1         | 1.85%   |
| 5.15.37-0-lts          | 1         | 1.85%   |
| 5.15.34                | 1         | 1.85%   |
| 5.15.30-0-lts          | 1         | 1.85%   |
| 5.15.28-0-lts          | 1         | 1.85%   |
| 5.15.26-0-lts          | 1         | 1.85%   |
| 5.15.16-0-lts          | 1         | 1.85%   |
| 5.15.12-0-lts          | 1         | 1.85%   |
| 5.14.8-0-edge          | 1         | 1.85%   |
| 5.13.0-0-edge          | 1         | 1.85%   |
| 5.12.8-0-edge          | 1         | 1.85%   |
| 5.10.70-0-lts          | 1         | 1.85%   |
| 5.10.69-0-lts          | 1         | 1.85%   |
| 5.10.68-0-lts          | 1         | 1.85%   |
| 5.10.61-0-lts          | 1         | 1.85%   |
| 5.10.5-0-lts           | 1         | 1.85%   |
| 5.10.44-0-lts          | 1         | 1.85%   |
| 5.10.43-0-lts          | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.83  | 2         | 3.7%    |
| 5.4.43  | 2         | 3.7%    |
| 5.15.86 | 2         | 3.7%    |
| 5.15.59 | 2         | 3.7%    |
| 5.15.47 | 2         | 3.7%    |
| 5.15.41 | 2         | 3.7%    |
| 5.15.4  | 2         | 3.7%    |
| 5.8.12  | 1         | 1.85%   |
| 5.6.2   | 1         | 1.85%   |
| 5.4.84  | 1         | 1.85%   |
| 5.4.72  | 1         | 1.85%   |
| 5.4.64  | 1         | 1.85%   |
| 5.4.46  | 1         | 1.85%   |
| 5.4.27  | 1         | 1.85%   |
| 5.17.9  | 1         | 1.85%   |
| 5.17.0  | 1         | 1.85%   |
| 5.16.12 | 1         | 1.85%   |
| 5.16.1  | 1         | 1.85%   |
| 5.15.89 | 1         | 1.85%   |
| 5.15.85 | 1         | 1.85%   |
| 5.15.73 | 1         | 1.85%   |
| 5.15.60 | 1         | 1.85%   |
| 5.15.46 | 1         | 1.85%   |
| 5.15.37 | 1         | 1.85%   |
| 5.15.34 | 1         | 1.85%   |
| 5.15.30 | 1         | 1.85%   |
| 5.15.28 | 1         | 1.85%   |
| 5.15.26 | 1         | 1.85%   |
| 5.15.16 | 1         | 1.85%   |
| 5.15.12 | 1         | 1.85%   |
| 5.14.8  | 1         | 1.85%   |
| 5.13.0  | 1         | 1.85%   |
| 5.12.8  | 1         | 1.85%   |
| 5.10.70 | 1         | 1.85%   |
| 5.10.69 | 1         | 1.85%   |
| 5.10.68 | 1         | 1.85%   |
| 5.10.61 | 1         | 1.85%   |
| 5.10.5  | 1         | 1.85%   |
| 5.10.44 | 1         | 1.85%   |
| 5.10.43 | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 22        | 42.31%  |
| 5.10    | 11        | 21.15%  |
| 5.4     | 9         | 17.31%  |
| 5.17    | 2         | 3.85%   |
| 5.8     | 1         | 1.92%   |
| 5.6     | 1         | 1.92%   |
| 5.16    | 1         | 1.92%   |
| 5.14    | 1         | 1.92%   |
| 5.13    | 1         | 1.92%   |
| 5.12    | 1         | 1.92%   |
| 4.4     | 1         | 1.92%   |
| 3.10    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 82%     |
| i686   | 7         | 14%     |
| i586   | 1         | 2%      |
| armv7l | 1         | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 76%     |
| XFCE    | 6         | 12%     |
| GNOME   | 4         | 8%      |
| sway    | 1         | 2%      |
| KDE5    | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 23        | 44.23%  |
| Unknown | 23        | 44.23%  |
| Wayland | 6         | 11.54%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 72%     |
| LightDM | 10        | 20%     |
| XDM     | 1         | 2%      |
| SDDM    | 1         | 2%      |
| LXDM    | 1         | 2%      |
| GDM     | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 30        | 57.69%  |
| Unknown | 15        | 28.85%  |
| en_US   | 5         | 9.62%   |
| ru_RU   | 1         | 1.92%   |
| en_GB   | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 36        | 72%     |
| EFI  | 14        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 78.43%  |
| Btrfs   | 5         | 9.8%    |
| Tmpfs   | 2         | 3.92%   |
| Overlay | 1         | 1.96%   |
| F2fs    | 1         | 1.96%   |
| Ext2    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 62.75%  |
| GPT     | 12        | 23.53%  |
| MBR     | 7         | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 90.2%   |
| Yes       | 5         | 9.8%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 92%     |
| Yes       | 4         | 8%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 10        | 20%     |
| Lenovo           | 8         | 16%     |
| Dell             | 8         | 16%     |
| ASUSTek Computer | 6         | 12%     |
| Acer             | 4         | 8%      |
| IBM              | 3         | 6%      |
| Google           | 2         | 4%      |
| Toshiba          | 1         | 2%      |
| Synology         | 1         | 2%      |
| Sony             | 1         | 2%      |
| Pegatron         | 1         | 2%      |
| MSI              | 1         | 2%      |
| Haier            | 1         | 2%      |
| Gateway          | 1         | 2%      |
| Fujitsu          | 1         | 2%      |
| Unknown          | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite M645                   | 1         | 2%      |
| Synology DS1019+                         | 1         | 2%      |
| Sony VGN-UX27GN                          | 1         | 2%      |
| Pegatron Deepcam                         | 1         | 2%      |
| MSI GL72M 7REX                           | 1         | 2%      |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 2%      |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 2%      |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 2%      |
| Lenovo ThinkPad T420 42364F2             | 1         | 2%      |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 2%      |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 2%      |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 2%      |
| IBM ThinkPad X40 2371LBG                 | 1         | 2%      |
| IBM 26446AG                              | 1         | 2%      |
| IBM 264070A                              | 1         | 2%      |
| HP ZBook 15 G5                           | 1         | 2%      |
| HP ProBook 4310s                         | 1         | 2%      |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 2%      |
| HP Mini 110-3500                         | 1         | 2%      |
| HP Laptop 14-dq1xxx                      | 1         | 2%      |
| HP ENVY Sleekbook 6 PC                   | 1         | 2%      |
| HP EliteBook 8460p                       | 1         | 2%      |
| HP EliteBook 2740p                       | 1         | 2%      |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 2%      |
| HP Compaq Mini CQ10-600                  | 1         | 2%      |
| Haier U144S                              | 1         | 2%      |
| Google Samus                             | 1         | 2%      |
| Google Leona                             | 1         | 2%      |
| Gateway MX3631m                          | 1         | 2%      |
| Fujitsu LIFEBOOK P702                    | 1         | 2%      |
| Dell XPS 15 7590                         | 1         | 2%      |
| Dell Studio 1747                         | 1         | 2%      |
| Dell Inspiron N5010                      | 1         | 2%      |
| Dell Inspiron MM061                      | 1         | 2%      |
| Dell Inspiron 5566                       | 1         | 2%      |
| Dell Inspiron 5447                       | 1         | 2%      |
| Dell Inspiron 3558                       | 1         | 2%      |
| Dell Inspiron 3180                       | 1         | 2%      |
| ASUS ZenBook UX431FA                     | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 6         | 12%     |
| Dell Inspiron     | 6         | 12%     |
| Acer Aspire       | 4         | 8%      |
| HP EliteBook      | 3         | 6%      |
| Toshiba Satellite | 1         | 2%      |
| Synology DS1019+  | 1         | 2%      |
| Sony VGN-UX27GN   | 1         | 2%      |
| Pegatron Deepcam  | 1         | 2%      |
| MSI GL72M         | 1         | 2%      |
| Lenovo Yoga       | 1         | 2%      |
| Lenovo IdeaPad    | 1         | 2%      |
| IBM ThinkPad      | 1         | 2%      |
| IBM 26446AG       | 1         | 2%      |
| IBM 264070A       | 1         | 2%      |
| HP ZBook          | 1         | 2%      |
| HP ProBook        | 1         | 2%      |
| HP Presario       | 1         | 2%      |
| HP Mini           | 1         | 2%      |
| HP Laptop         | 1         | 2%      |
| HP ENVY           | 1         | 2%      |
| HP Compaq         | 1         | 2%      |
| Haier U144S       | 1         | 2%      |
| Google Samus      | 1         | 2%      |
| Google Leona      | 1         | 2%      |
| Gateway MX3631m   | 1         | 2%      |
| Fujitsu LIFEBOOK  | 1         | 2%      |
| Dell XPS          | 1         | 2%      |
| Dell Studio       | 1         | 2%      |
| ASUS ZenBook      | 1         | 2%      |
| ASUS X555LAB      | 1         | 2%      |
| ASUS X550EA       | 1         | 2%      |
| ASUS X200MA       | 1         | 2%      |
| ASUS N10Jc        | 1         | 2%      |
| ASUS E502SA       | 1         | 2%      |
| Unknown           | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2014    | 6         | 12%     |
| 2019    | 5         | 10%     |
| 2018    | 5         | 10%     |
| 2010    | 5         | 10%     |
| 2012    | 4         | 8%      |
| 2017    | 3         | 6%      |
| 2006    | 3         | 6%      |
| 2021    | 2         | 4%      |
| 2016    | 2         | 4%      |
| 2015    | 2         | 4%      |
| 2011    | 2         | 4%      |
| 2009    | 2         | 4%      |
| 2005    | 2         | 4%      |
| Unknown | 2         | 4%      |
| 2022    | 1         | 2%      |
| 2013    | 1         | 2%      |
| 2008    | 1         | 2%      |
| 2007    | 1         | 2%      |
| 1999    | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 50        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 96%     |
| Yes  | 2         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 27.45%  |
| 3.01-4.0    | 12        | 23.53%  |
| 16.01-24.0  | 5         | 9.8%    |
| 8.01-16.0   | 5         | 9.8%    |
| 1.01-2.0    | 4         | 7.84%   |
| 0.51-1.0    | 4         | 7.84%   |
| 2.01-3.0    | 3         | 5.88%   |
| 0.01-0.5    | 2         | 3.92%   |
| 32.01-64.0  | 1         | 1.96%   |
| 64.01-256.0 | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 16        | 30.77%  |
| 1.01-2.0  | 12        | 23.08%  |
| 0.51-1.0  | 8         | 15.38%  |
| 2.01-3.0  | 5         | 9.62%   |
| 4.01-8.0  | 4         | 7.69%   |
| 3.01-4.0  | 3         | 5.77%   |
| 0         | 2         | 3.85%   |
| 8.01-16.0 | 1         | 1.92%   |
| Unknown   | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 74.51%  |
| 2      | 11        | 21.57%  |
| 7      | 1         | 1.96%   |
| 0      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 66%     |
| Yes       | 17        | 34%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 80%     |
| No        | 10        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 92%     |
| No        | 4         | 8%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 58%     |
| No        | 21        | 42%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 14        | 28%     |
| UK           | 5         | 10%     |
| Canada       | 5         | 10%     |
| Russia       | 4         | 8%      |
| Germany      | 3         | 6%      |
| Brazil       | 3         | 6%      |
| Australia    | 2         | 4%      |
| Venezuela    | 1         | 2%      |
| Spain        | 1         | 2%      |
| South Africa | 1         | 2%      |
| Slovakia     | 1         | 2%      |
| Portugal     | 1         | 2%      |
| Poland       | 1         | 2%      |
| Mexico       | 1         | 2%      |
| Jamaica      | 1         | 2%      |
| Italy        | 1         | 2%      |
| Hungary      | 1         | 2%      |
| Guatemala    | 1         | 2%      |
| France       | 1         | 2%      |
| Egypt        | 1         | 2%      |
| Czechia      | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| St Petersburg    | 3         | 5.88%   |
| Stratford        | 2         | 3.92%   |
| Springfield      | 2         | 3.92%   |
| Fulham           | 2         | 3.92%   |
| Vernon           | 1         | 1.96%   |
| Tymovskoye       | 1         | 1.96%   |
| Tampa            | 1         | 1.96%   |
| Sydney           | 1         | 1.96%   |
| Stewartstown     | 1         | 1.96%   |
| Sisteron         | 1         | 1.96%   |
| Semily           | 1         | 1.96%   |
| Seattle          | 1         | 1.96%   |
| Sao Paulo        | 1         | 1.96%   |
| San Mateo        | 1         | 1.96%   |
| Saarbrücken     | 1         | 1.96%   |
| Rzeszów         | 1         | 1.96%   |
| Rostock          | 1         | 1.96%   |
| Purdys           | 1         | 1.96%   |
| Oakville         | 1         | 1.96%   |
| Northampton      | 1         | 1.96%   |
| Merrill          | 1         | 1.96%   |
| Mérida          | 1         | 1.96%   |
| Manitowoc        | 1         | 1.96%   |
| Madrid           | 1         | 1.96%   |
| Lindavista Norte | 1         | 1.96%   |
| Lincoln          | 1         | 1.96%   |
| Leipzig          | 1         | 1.96%   |
| Larkspur         | 1         | 1.96%   |
| Kingston         | 1         | 1.96%   |
| Kecskemét       | 1         | 1.96%   |
| Johannesburg     | 1         | 1.96%   |
| Hampstead        | 1         | 1.96%   |
| Guatemala City   | 1         | 1.96%   |
| Funchal          | 1         | 1.96%   |
| Franklin         | 1         | 1.96%   |
| Ejido            | 1         | 1.96%   |
| Dallas           | 1         | 1.96%   |
| Corrego Novo     | 1         | 1.96%   |
| Chapel Hill      | 1         | 1.96%   |
| Cairo            | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 11.86%  |
| Samsung Electronics | 6         | 7      | 10.17%  |
| Kingston            | 6         | 7      | 10.17%  |
| Unknown             | 5         | 7      | 8.47%   |
| Toshiba             | 5         | 7      | 8.47%   |
| Seagate             | 4         | 13     | 6.78%   |
| WDC                 | 3         | 4      | 5.08%   |
| HGST                | 3         | 3      | 5.08%   |
| Intel               | 2         | 4      | 3.39%   |
| Fujitsu             | 2         | 2      | 3.39%   |
| Crucial             | 2         | 2      | 3.39%   |
| SPCC                | 1         | 1      | 1.69%   |
| SK hynix            | 1         | 1      | 1.69%   |
| SanDisk             | 1         | 1      | 1.69%   |
| Micron Technology   | 1         | 1      | 1.69%   |
| LITEON              | 1         | 1      | 1.69%   |
| KC600               | 1         | 1      | 1.69%   |
| JMicron Technology  | 1         | 1      | 1.69%   |
| Intenso             | 1         | 1      | 1.69%   |
| IBM                 | 1         | 1      | 1.69%   |
| Emtec               | 1         | 1      | 1.69%   |
| Dell                | 1         | 2      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| AMD                 | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                    | 2         | 3.17%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 3.17%   |
| Kingston SV300S37A120G 120GB SSD          | 2         | 3.17%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 3.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 1.59%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 1.59%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 1.59%   |
| Unknown SD32G  32GB                       | 1         | 1.59%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 1.59%   |
| Unknown MMC Card  64GB                    | 1         | 1.59%   |
| Unknown MMC Card  32GB                    | 1         | 1.59%   |
| Toshiba NVMe SSD Drive 256GB              | 1         | 1.59%   |
| Toshiba MQ01ABD1 1TB                      | 1         | 1.59%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.59%   |
| Toshiba MK4009GAL 40GB                    | 1         | 1.59%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.59%   |
| SPCC Solid State Disk 256GB               | 1         | 1.59%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 1.59%   |
| Seagate ST98823A 80GB                     | 1         | 1.59%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 1.59%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.59%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1.59%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 1.59%   |
| Samsung Portable SSD T5 1TB               | 1         | 1.59%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.59%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 1.59%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 1.59%   |
| Samsung HM160HI 160GB                     | 1         | 1.59%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD       | 1         | 1.59%   |
| LITEON CV1-8B128-HP 128GB SSD             | 1         | 1.59%   |
| Kingston SUV500MS480G 480GB SSD           | 1         | 1.59%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 1.59%   |
| Kingston RBU-SUS151S364GD 64GB SSD        | 1         | 1.59%   |
| Kingston KC600 128GB SSD                  | 1         | 1.59%   |
| KC600 SSD 128GB                           | 1         | 1.59%   |
| JMicron Generic 500GB                     | 1         | 1.59%   |
| Intenso SSD 128GB                         | 1         | 1.59%   |
| Intel SSDPEKKA256G7 256GB                 | 1         | 1.59%   |
| Intel HBRPEKNX0101AHO 16GB                | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 30.43%  |
| Toshiba             | 4         | 5      | 17.39%  |
| Seagate             | 4         | 13     | 17.39%  |
| HGST                | 3         | 3      | 13.04%  |
| Fujitsu             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 2      | 4.35%   |
| IBM                 | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 26.09%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| SPCC                | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |
| KC600               | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| Intenso             | 1         | 1      | 4.35%   |
| Emtec               | 1         | 1      | 4.35%   |
| Dell                | 1         | 2      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| AMD                 | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 34     | 41.82%  |
| SSD  | 20        | 25     | 36.36%  |
| NVMe | 8         | 14     | 14.55%  |
| MMC  | 4         | 5      | 7.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 56     | 72.73%  |
| NVMe | 8         | 14     | 14.55%  |
| MMC  | 4         | 5      | 7.27%   |
| SAS  | 3         | 3      | 5.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 40     | 79.07%  |
| 0.51-1.0   | 7         | 8      | 16.28%  |
| 1.01-2.0   | 1         | 1      | 2.33%   |
| 4.01-10.0  | 1         | 10     | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 28.85%  |
| 1-20           | 9         | 17.31%  |
| 251-500        | 6         | 11.54%  |
| Unknown        | 6         | 11.54%  |
| 21-50          | 5         | 9.62%   |
| 501-1000       | 5         | 9.62%   |
| 1001-2000      | 3         | 5.77%   |
| 51-100         | 2         | 3.85%   |
| More than 3000 | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 34        | 65.38%  |
| Unknown  | 6         | 11.54%  |
| 21-50    | 4         | 7.69%   |
| 101-250  | 3         | 5.77%   |
| 51-100   | 3         | 5.77%   |
| 501-1000 | 2         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 11.11%  |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 11.11%  |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 11.11%  |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 11.11%  |
| Hitachi HTS72101 99GB                          | 1         | 1      | 11.11%  |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 11.11%  |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 44.44%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Micron Technology   | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 50%     |
| Toshiba             | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 2      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 31        | 51     | 57.41%  |
| Detected | 14        | 17     | 25.93%  |
| Malfunc  | 9         | 10     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 71.7%   |
| AMD                          | 7         | 13.21%  |
| Samsung Electronics          | 3         | 5.66%   |
| Toshiba America Info Systems | 1         | 1.89%   |
| SK hynix                     | 1         | 1.89%   |
| SanDisk                      | 1         | 1.89%   |
| Marvell Technology Group     | 1         | 1.89%   |
| ADATA Technology             | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 7         | 12.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 5.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 5.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 3         | 5.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 3         | 5.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 3         | 5.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 2         | 3.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 3.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 3.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 2         | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 3.57%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 3.57%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.79%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.79%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller             | 1         | 1.79%   |
| Intel SSD 600P Series                                                        | 1         | 1.79%   |
| Intel Non-Volatile memory controller                                         | 1         | 1.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 1.79%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 1.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                  | 1         | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 64.81%  |
| IDE  | 9         | 16.67%  |
| NVMe | 8         | 14.81%  |
| RAID | 2         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 82%     |
| AMD    | 8         | 16%     |
| ARM    | 1         | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                      | 2         | 4%      |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 4%      |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 4%      |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 2%      |
| Intel Pentium M processor 1.70GHz                      | 1         | 2%      |
| Intel Pentium M processor 1.60GHz                      | 1         | 2%      |
| Intel Pentium M processor 1.50GHz                      | 1         | 2%      |
| Intel Pentium III (Coppermine)                         | 1         | 2%      |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 2%      |
| Intel Mobile Pentium MMX                               | 1         | 2%      |
| Intel Core Solo CPU U1500 @ 1.33GHz                    | 1         | 2%      |
| Intel Core m3-8100Y CPU @ 1.10GHz                      | 1         | 2%      |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 2%      |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 2%      |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 2%      |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 2%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 2%      |
| Intel Core i5-5200U CPU @ 2.20GHz                      | 1         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz                      | 1         | 2%      |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 2%      |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 2%      |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 2%      |
| Intel Core i5 CPU M 480 @ 2.67GHz                      | 1         | 2%      |
| Intel Core i3-5020U CPU @ 2.20GHz                      | 1         | 2%      |
| Intel Core i3-3110M CPU @ 2.40GHz                      | 1         | 2%      |
| Intel Core i3 CPU M 350 @ 2.27GHz                      | 1         | 2%      |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 2%      |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 2%      |
| Intel Core 2 Duo CPU P7570 @ 2.26GHz                   | 1         | 2%      |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 2%      |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 2%      |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 1         | 2%      |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 2%      |
| Intel Atom CPU N270 @ 1.60GHz                          | 1         | 2%      |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 2%      |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 13        | 26%     |
| Intel Celeron     | 5         | 10%     |
| Intel Atom        | 4         | 8%      |
| Other             | 3         | 6%      |
| Intel Pentium M   | 3         | 6%      |
| Intel Core i3     | 3         | 6%      |
| Intel Core 2 Duo  | 3         | 6%      |
| Intel Core i7     | 2         | 4%      |
| AMD A4            | 2         | 4%      |
| Intel Xeon        | 1         | 2%      |
| Intel Pentium III | 1         | 2%      |
| Intel Pentium     | 1         | 2%      |
| Intel Core Solo   | 1         | 2%      |
| Intel Core m3     | 1         | 2%      |
| Intel Core i9     | 1         | 2%      |
| Intel Core 2      | 1         | 2%      |
| AMD Ryzen 7       | 1         | 2%      |
| AMD Ryzen 5       | 1         | 2%      |
| AMD E2            | 1         | 2%      |
| AMD A6            | 1         | 2%      |
| AMD A10           | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 54%     |
| 4      | 10        | 20%     |
| 1      | 9         | 18%     |
| 8      | 2         | 4%      |
| 6      | 1         | 2%      |
| 3      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 52%     |
| 2      | 24        | 48%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 25        | 49.02%  |
| 32-bit, 64-bit | 23        | 45.1%   |
| 32-bit         | 3         | 5.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 57.69%  |
| 0x30678    | 3         | 5.77%   |
| 0x306a9    | 2         | 3.85%   |
| 0x206a7    | 2         | 3.85%   |
| 0x106ca    | 2         | 3.85%   |
| 0x06006704 | 2         | 3.85%   |
| 0x906ea    | 1         | 1.92%   |
| 0x806eb    | 1         | 1.92%   |
| 0x706e5    | 1         | 1.92%   |
| 0x683      | 1         | 1.92%   |
| 0x506c9    | 1         | 1.92%   |
| 0x406c4    | 1         | 1.92%   |
| 0x306d4    | 1         | 1.92%   |
| 0x20655    | 1         | 1.92%   |
| 0x106e5    | 1         | 1.92%   |
| 0x1067a    | 1         | 1.92%   |
| 0x0810100b | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 14%     |
| P6          | 5         | 10%     |
| Silvermont  | 4         | 8%      |
| Westmere    | 3         | 6%      |
| Penryn      | 3         | 6%      |
| Goldmont    | 3         | 6%      |
| Excavator   | 3         | 6%      |
| Broadwell   | 3         | 6%      |
| Bonnell     | 3         | 6%      |
| SandyBridge | 2         | 4%      |
| IvyBridge   | 2         | 4%      |
| Unknown     | 2         | 4%      |
| Zen 2       | 1         | 2%      |
| Zen         | 1         | 2%      |
| Skylake     | 1         | 2%      |
| Puma        | 1         | 2%      |
| Nehalem     | 1         | 2%      |
| Jaguar      | 1         | 2%      |
| IceLake     | 1         | 2%      |
| Haswell     | 1         | 2%      |
| Core        | 1         | 2%      |
| Bobcat      | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 35        | 64.81%  |
| AMD      | 13        | 24.07%  |
| Nvidia   | 4         | 7.41%   |
| Neomagic | 2         | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 3         | 5.26%   |
| Intel HD Graphics 500                                                                    | 3         | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.51%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 3.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 3.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.51%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.75%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.75%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.75%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.75%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.75%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.75%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.75%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.75%   |
| Intel HD Graphics 630                                                                    | 1         | 1.75%   |
| Intel HD Graphics 620                                                                    | 1         | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.75%   |
| Intel Coffee Lake-S GT2 [UHD Graphics P630]                                              | 1         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.75%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.75%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.75%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.75%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.75%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.75%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 1.75%   |
| AMD Renoir                                                                               | 1         | 1.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 52%     |
| 1 x AMD        | 10        | 20%     |
| 2 x Intel      | 4         | 8%      |
| Intel + Nvidia | 3         | 6%      |
| 1 x Neomagic   | 2         | 4%      |
| Intel + AMD    | 2         | 4%      |
| Other          | 1         | 2%      |
| 2 x AMD        | 1         | 2%      |
| 1 x Nvidia     | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 90.2%   |
| Unknown     | 4         | 7.84%   |
| Proprietary | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 90%     |
| 0.01-0.5   | 3         | 6%      |
| 1.01-2.0   | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 22.92%  |
| LG Display              | 9         | 18.75%  |
| Chimei Innolux          | 6         | 12.5%   |
| BOE                     | 4         | 8.33%   |
| Samsung Electronics     | 3         | 6.25%   |
| Chi Mei Optoelectronics | 3         | 6.25%   |
| LG Philips              | 2         | 4.17%   |
| ONN                     | 1         | 2.08%   |
| Lenovo                  | 1         | 2.08%   |
| InfoVision              | 1         | 2.08%   |
| HannStar                | 1         | 2.08%   |
| Goldstar                | 1         | 2.08%   |
| Envision                | 1         | 2.08%   |
| DENON                   | 1         | 2.08%   |
| CSO                     | 1         | 2.08%   |
| CPT                     | 1         | 2.08%   |
| Acer                    | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 4.17%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 2.08%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                      | 1         | 2.08%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.08%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 2.08%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch              | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 2.08%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 2.08%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 2.08%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 2.08%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 2.08%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                         | 1         | 2.08%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 2.08%   |
| CPT LCD Monitor CPT04E2 1024x600 222x130mm 10.1-inch                     | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 309x173mm 13.9-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO463D 1920x1080 309x174mm 14.0-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 21        | 43.75%  |
| 1920x1080 (FHD)   | 7         | 14.58%  |
| 1280x800 (WXGA)   | 5         | 10.42%  |
| 1024x600          | 3         | 6.25%   |
| 3840x2160 (4K)    | 2         | 4.17%   |
| 1600x900 (HD+)    | 2         | 4.17%   |
| 2880x1800         | 1         | 2.08%   |
| 2560x1700         | 1         | 2.08%   |
| 2560x1440 (QHD)   | 1         | 2.08%   |
| 2560x1080         | 1         | 2.08%   |
| 1920x1200 (WUXGA) | 1         | 2.08%   |
| 1360x768          | 1         | 2.08%   |
| 1280x768          | 1         | 2.08%   |
| 1280x1024 (SXGA)  | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 33.33%  |
| 13     | 8         | 16.67%  |
| 14     | 7         | 14.58%  |
| 17     | 4         | 8.33%   |
| 12     | 3         | 6.25%   |
| 11     | 3         | 6.25%   |
| 10     | 3         | 6.25%   |
| 60     | 1         | 2.08%   |
| 32     | 1         | 2.08%   |
| 31     | 1         | 2.08%   |
| 29     | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 62.5%   |
| 201-300     | 11        | 22.92%  |
| 351-400     | 3         | 6.25%   |
| 601-700     | 2         | 4.17%   |
| 701-800     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 78.26%  |
| 16/10 | 7         | 15.22%  |
| 5/4   | 1         | 2.17%   |
| 3/2   | 1         | 2.17%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 33.33%  |
| 81-90          | 13        | 27.08%  |
| 71-80          | 3         | 6.25%   |
| 51-60          | 3         | 6.25%   |
| 41-50          | 3         | 6.25%   |
| 61-70          | 2         | 4.17%   |
| 351-500        | 2         | 4.17%   |
| 121-130        | 2         | 4.17%   |
| More than 1000 | 1         | 2.08%   |
| 301-350        | 1         | 2.08%   |
| 141-150        | 1         | 2.08%   |
| 131-140        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 21        | 44.68%  |
| 121-160       | 13        | 27.66%  |
| 51-100        | 7         | 14.89%  |
| More than 240 | 2         | 4.26%   |
| 1-50          | 2         | 4.26%   |
| 161-240       | 2         | 4.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 82%     |
| 2     | 5         | 10%     |
| 0     | 4         | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 34.12%  |
| Intel                           | 24        | 28.24%  |
| Qualcomm Atheros                | 15        | 17.65%  |
| Broadcom                        | 7         | 8.24%   |
| Marvell Technology Group        | 3         | 3.53%   |
| Broadcom Limited                | 2         | 2.35%   |
| Qualcomm Atheros Communications | 1         | 1.18%   |
| Qualcomm                        | 1         | 1.18%   |
| LSI                             | 1         | 1.18%   |
| Google                          | 1         | 1.18%   |
| Dresden Elektronik              | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 12        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 9.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 7.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.08%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.04%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.04%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.04%   |
| Qualcomm Android                                                               | 1         | 1.04%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.04%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 1.04%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.04%   |
| LSI WinModem 56k                                                               | 1         | 1.04%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.04%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.04%   |
| Intel Wireless 8260                                                            | 1         | 1.04%   |
| Intel Wireless 7265                                                            | 1         | 1.04%   |
| Intel Wireless 7260                                                            | 1         | 1.04%   |
| Intel Wireless 3160                                                            | 1         | 1.04%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.04%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.04%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 44.68%  |
| Qualcomm Atheros                | 14        | 29.79%  |
| Broadcom                        | 5         | 10.64%  |
| Realtek Semiconductor           | 3         | 6.38%   |
| Broadcom Limited                | 2         | 4.26%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| Marvell Technology Group        | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 14.89%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 6.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 4.26%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 4.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 2.13%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.13%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 2.13%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.13%   |
| Intel Wireless-AC 9260                                                         | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.13%   |
| Intel Wireless 8260                                                            | 1         | 2.13%   |
| Intel Wireless 7265                                                            | 1         | 2.13%   |
| Intel Wireless 7260                                                            | 1         | 2.13%   |
| Intel Wireless 3160                                                            | 1         | 2.13%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.13%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 2.13%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.13%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                        | 1         | 2.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 60.47%  |
| Intel                    | 10        | 23.26%  |
| Broadcom                 | 3         | 6.98%   |
| Marvell Technology Group | 2         | 4.65%   |
| Qualcomm Atheros         | 1         | 2.33%   |
| Qualcomm                 | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 27.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 20.93%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.33%   |
| Qualcomm Android                                                  | 1         | 2.33%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.33%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 2.33%   |
| Intel WiMAX Connection 2400m                                      | 1         | 2.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.33%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express             | 1         | 2.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.33%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 50.55%  |
| Ethernet | 39        | 42.86%  |
| Modem    | 6         | 6.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 66.67%  |
| Ethernet | 17        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 70%     |
| 1     | 12        | 24%     |
| 0     | 3         | 6%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 84.31%  |
| Yes  | 8         | 15.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 37.93%  |
| Qualcomm Atheros Communications | 4         | 13.79%  |
| Lite-On Technology              | 3         | 10.34%  |
| Broadcom                        | 3         | 10.34%  |
| IMC Networks                    | 2         | 6.9%    |
| Realtek Semiconductor           | 1         | 3.45%   |
| Marvell Semiconductor           | 1         | 3.45%   |
| Hewlett-Packard                 | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| ASUSTek Computer                | 1         | 3.45%   |
| Alps Electric                   | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 17.24%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 13.79%  |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.9%    |
| Intel AX200 Bluetooth                               | 2         | 6.9%    |
| Realtek Bluetooth Radio                             | 1         | 3.45%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.45%   |
| Lite-On Bluetooth Device                            | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.45%   |
| IMC Networks Bluetooth Device                       | 1         | 3.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.45%   |
| Broadcom BCM20702A0                                 | 1         | 3.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.45%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.45%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 3.45%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 38        | 74.51%  |
| AMD                       | 10        | 19.61%  |
| Sennheiser Communications | 1         | 1.96%   |
| Realtek Semiconductor     | 1         | 1.96%   |
| Cirrus Logic              | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 8.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 6.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 4.84%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.84%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 4.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.23%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 3.23%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.61%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.61%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.61%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.61%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 25%     |
| Unknown             | 9         | 20.45%  |
| SK hynix            | 7         | 15.91%  |
| Micron Technology   | 4         | 9.09%   |
| Elpida              | 4         | 9.09%   |
| Crucial             | 3         | 6.82%   |
| A-DATA Technology   | 2         | 4.55%   |
| Unknown (ABCD)      | 1         | 2.27%   |
| Ramaxel Technology  | 1         | 2.27%   |
| Nanya Technology    | 1         | 2.27%   |
| Kingston            | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 6.38%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 4.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4.26%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 4.26%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 2.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 2.13%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 2.13%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 2.13%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 2.13%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.13%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.13%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4                    | 1         | 2.13%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.13%   |
| Samsung RAM M471B5273CH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 2.13%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.13%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.13%   |
| Samsung RAM K4E6E304EC-EGCF 4GB LPDDR3 1867MT/s                  | 1         | 2.13%   |
| Ramaxel RAM RMT3170EB68E9W160 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.13%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s        | 1         | 2.13%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 1         | 2.13%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s           | 1         | 2.13%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s        | 1         | 2.13%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 2.13%   |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.13%   |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s        | 1         | 2.13%   |
| Crucial RAM CT51264BF160B.C16 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Crucial RAM CT102464BF186D.M16 8GB SODIMM DDR3 1867MT/s          | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 18        | 45%     |
| DDR4   | 8         | 20%     |
| LPDDR3 | 4         | 10%     |
| DDR    | 4         | 10%     |
| SDRAM  | 2         | 5%      |
| LPDDR4 | 2         | 5%      |
| DRAM   | 1         | 2.5%    |
| DDR2   | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 87.5%   |
| Row Of Chips | 3         | 7.5%    |
| DIMM         | 1         | 2.5%    |
| Unknown      | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 17        | 38.64%  |
| 8192 | 12        | 27.27%  |
| 2048 | 7         | 15.91%  |
| 1024 | 3         | 6.82%   |
| 512  | 3         | 6.82%   |
| 256  | 1         | 2.27%   |
| 128  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 23.26%  |
| 1334    | 6         | 13.95%  |
| Unknown | 6         | 13.95%  |
| 2400    | 4         | 9.3%    |
| 2133    | 4         | 9.3%    |
| 3200    | 2         | 4.65%   |
| 2667    | 2         | 4.65%   |
| 1867    | 2         | 4.65%   |
| 1333    | 2         | 4.65%   |
| 4199    | 1         | 2.33%   |
| 1400    | 1         | 2.33%   |
| 1200    | 1         | 2.33%   |
| 1067    | 1         | 2.33%   |
| 533     | 1         | 2.33%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 30.77%  |
| Realtek Semiconductor                  | 5         | 12.82%  |
| Microdia                               | 4         | 10.26%  |
| Suyin                                  | 3         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Quanta                                 | 2         | 5.13%   |
| IMC Networks                           | 2         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.13%   |
| Acer                                   | 2         | 5.13%   |
| Syntek                                 | 1         | 2.56%   |
| Silicon Motion                         | 1         | 2.56%   |
| Ricoh                                  | 1         | 2.56%   |
| Lenovo                                 | 1         | 2.56%   |
| Apple                                  | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 5.13%   |
| Chicony Integrated Camera                           | 2         | 5.13%   |
| Chicony HD WebCam                                   | 2         | 5.13%   |
| Syntek EasyCamera                                   | 1         | 2.56%   |
| Suyin Integrated_Webcam_HD                          | 1         | 2.56%   |
| Suyin HP TrueVision HD                              | 1         | 2.56%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.56%   |
| Sunplus HP Universal Camera                         | 1         | 2.56%   |
| Sunplus HD WebCam                                   | 1         | 2.56%   |
| Silicon Motion NCM-G102                             | 1         | 2.56%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 2.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 2.56%   |
| Realtek USB Camera                                  | 1         | 2.56%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 2.56%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 2.56%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.56%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.56%   |
| Microdia Integrated Webcam                          | 1         | 2.56%   |
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
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.56%   |
| Acer Lenovo Integrated Webcam                       | 1         | 2.56%   |
| Acer BisonCam, NB Pro                               | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 42.86%  |
| AuthenTec          | 2         | 28.57%  |
| Synaptics          | 1         | 14.29%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
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


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 54.72%  |
| 1     | 15        | 28.3%   |
| 2     | 8         | 15.09%  |
| 4     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 20.59%  |
| Fingerprint reader       | 7         | 20.59%  |
| Modem                    | 6         | 17.65%  |
| Net/wireless             | 2         | 5.88%   |
| Chipcard                 | 2         | 5.88%   |
| Camera                   | 2         | 5.88%   |
| Bluetooth                | 2         | 5.88%   |
| Unclassified device      | 1         | 2.94%   |
| Storage                  | 1         | 2.94%   |
| Sound                    | 1         | 2.94%   |
| Network                  | 1         | 2.94%   |
| Multimedia controller    | 1         | 2.94%   |
| Communication controller | 1         | 2.94%   |


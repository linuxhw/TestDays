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

Total: 60

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alpine 3.16.0               | 6         | 12.24%  |
| Alpine 3.15.0               | 6         | 12.24%  |
| Alpine 3.15.0_alpha20210804 | 4         | 8.16%   |
| Alpine 3.14.0               | 4         | 8.16%   |
| Alpine 3.12.0               | 4         | 8.16%   |
| Alpine 3.16.2               | 2         | 4.08%   |
| Alpine 3.14.2               | 2         | 4.08%   |
| Alpine 3.13.5               | 2         | 4.08%   |
| Alpine 3.13.0_alpha20201218 | 2         | 4.08%   |
| Alpine 3.13.0_alpha20200917 | 2         | 4.08%   |
| Alpine 3.11.2               | 2         | 4.08%   |
| Alpine 3.17_alpha20220809   | 1         | 2.04%   |
| Alpine 3.16.1               | 1         | 2.04%   |
| Alpine 3.16.0_alpha20220316 | 1         | 2.04%   |
| Alpine 3.15.4               | 1         | 2.04%   |
| Alpine 3.15.2               | 1         | 2.04%   |
| Alpine 3.15.0_rc5           | 1         | 2.04%   |
| Alpine 3.14.0_alpha20210212 | 1         | 2.04%   |
| Alpine 3.13.1               | 1         | 2.04%   |
| Alpine 3.13.0_rc2           | 1         | 2.04%   |
| Alpine 3.13.0_alpha20200626 | 1         | 2.04%   |
| Alpine 3.12.3               | 1         | 2.04%   |
| Alpine 3.12.1               | 1         | 2.04%   |
| Alpine 3.11.5               | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.83-0-lts           | 2         | 4%      |
| 5.4.43-1-lts           | 2         | 4%      |
| 5.15.59-0-lts          | 2         | 4%      |
| 5.15.47-0-lts          | 2         | 4%      |
| 5.15.41-0-lts          | 2         | 4%      |
| 5.15.4-0-lts           | 2         | 4%      |
| 5.8.12-0-edge          | 1         | 2%      |
| 5.6.2-xanmod1-1-xanmod | 1         | 2%      |
| 5.4.84-0-lts           | 1         | 2%      |
| 5.4.72-0-lts           | 1         | 2%      |
| 5.4.64-0-lts           | 1         | 2%      |
| 5.4.46-0-lts           | 1         | 2%      |
| 5.4.27-0-lts           | 1         | 2%      |
| 5.17.9-0-edge          | 1         | 2%      |
| 5.17.0-0-edge          | 1         | 2%      |
| 5.16.12-may            | 1         | 2%      |
| 5.16.1-may             | 1         | 2%      |
| 5.15.73-0-lts          | 1         | 2%      |
| 5.15.60-0-lts          | 1         | 2%      |
| 5.15.46-1-lts          | 1         | 2%      |
| 5.15.37-0-lts          | 1         | 2%      |
| 5.15.34                | 1         | 2%      |
| 5.15.30-0-lts          | 1         | 2%      |
| 5.15.28-0-lts          | 1         | 2%      |
| 5.15.26-0-lts          | 1         | 2%      |
| 5.15.16-0-lts          | 1         | 2%      |
| 5.15.12-0-lts          | 1         | 2%      |
| 5.14.8-0-edge          | 1         | 2%      |
| 5.13.0-0-edge          | 1         | 2%      |
| 5.12.8-0-edge          | 1         | 2%      |
| 5.10.70-0-lts          | 1         | 2%      |
| 5.10.69-0-lts          | 1         | 2%      |
| 5.10.68-0-lts          | 1         | 2%      |
| 5.10.61-0-lts          | 1         | 2%      |
| 5.10.5-0-lts           | 1         | 2%      |
| 5.10.44-0-lts          | 1         | 2%      |
| 5.10.43-0-lts          | 1         | 2%      |
| 5.10.42-0-legacy       | 1         | 2%      |
| 5.10.4-0-lts           | 1         | 2%      |
| 5.10.38-0-lts          | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.83  | 2         | 4%      |
| 5.4.43  | 2         | 4%      |
| 5.15.59 | 2         | 4%      |
| 5.15.47 | 2         | 4%      |
| 5.15.41 | 2         | 4%      |
| 5.15.4  | 2         | 4%      |
| 5.8.12  | 1         | 2%      |
| 5.6.2   | 1         | 2%      |
| 5.4.84  | 1         | 2%      |
| 5.4.72  | 1         | 2%      |
| 5.4.64  | 1         | 2%      |
| 5.4.46  | 1         | 2%      |
| 5.4.27  | 1         | 2%      |
| 5.17.9  | 1         | 2%      |
| 5.17.0  | 1         | 2%      |
| 5.16.12 | 1         | 2%      |
| 5.16.1  | 1         | 2%      |
| 5.15.73 | 1         | 2%      |
| 5.15.60 | 1         | 2%      |
| 5.15.46 | 1         | 2%      |
| 5.15.37 | 1         | 2%      |
| 5.15.34 | 1         | 2%      |
| 5.15.30 | 1         | 2%      |
| 5.15.28 | 1         | 2%      |
| 5.15.26 | 1         | 2%      |
| 5.15.16 | 1         | 2%      |
| 5.15.12 | 1         | 2%      |
| 5.14.8  | 1         | 2%      |
| 5.13.0  | 1         | 2%      |
| 5.12.8  | 1         | 2%      |
| 5.10.70 | 1         | 2%      |
| 5.10.69 | 1         | 2%      |
| 5.10.68 | 1         | 2%      |
| 5.10.61 | 1         | 2%      |
| 5.10.5  | 1         | 2%      |
| 5.10.44 | 1         | 2%      |
| 5.10.43 | 1         | 2%      |
| 5.10.42 | 1         | 2%      |
| 5.10.4  | 1         | 2%      |
| 5.10.38 | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 18        | 37.5%   |
| 5.10    | 11        | 22.92%  |
| 5.4     | 9         | 18.75%  |
| 5.17    | 2         | 4.17%   |
| 5.8     | 1         | 2.08%   |
| 5.6     | 1         | 2.08%   |
| 5.16    | 1         | 2.08%   |
| 5.14    | 1         | 2.08%   |
| 5.13    | 1         | 2.08%   |
| 5.12    | 1         | 2.08%   |
| 4.4     | 1         | 2.08%   |
| 3.10    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 80.43%  |
| i686   | 7         | 15.22%  |
| i586   | 1         | 2.17%   |
| armv7l | 1         | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 37        | 80.43%  |
| XFCE    | 4         | 8.7%    |
| GNOME   | 4         | 8.7%    |
| KDE5    | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 47.92%  |
| X11     | 20        | 41.67%  |
| Wayland | 5         | 10.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 76.09%  |
| LightDM | 7         | 15.22%  |
| XDM     | 1         | 2.17%   |
| SDDM    | 1         | 2.17%   |
| LXDM    | 1         | 2.17%   |
| GDM     | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 28        | 58.33%  |
| Unknown | 14        | 29.17%  |
| en_US   | 4         | 8.33%   |
| ru_RU   | 1         | 2.08%   |
| en_GB   | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 32        | 69.57%  |
| EFI  | 14        | 30.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 78.72%  |
| Btrfs   | 4         | 8.51%   |
| Tmpfs   | 2         | 4.26%   |
| Overlay | 1         | 2.13%   |
| F2fs    | 1         | 2.13%   |
| Ext2    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 59.57%  |
| GPT     | 12        | 25.53%  |
| MBR     | 7         | 14.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 89.36%  |
| Yes       | 5         | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 91.3%   |
| Yes       | 4         | 8.7%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 10        | 21.74%  |
| Lenovo           | 7         | 15.22%  |
| Dell             | 6         | 13.04%  |
| ASUSTek Computer | 6         | 13.04%  |
| Acer             | 4         | 8.7%    |
| IBM              | 3         | 6.52%   |
| Toshiba          | 1         | 2.17%   |
| Synology         | 1         | 2.17%   |
| Sony             | 1         | 2.17%   |
| Pegatron         | 1         | 2.17%   |
| MSI              | 1         | 2.17%   |
| Haier            | 1         | 2.17%   |
| Google           | 1         | 2.17%   |
| Gateway          | 1         | 2.17%   |
| Fujitsu          | 1         | 2.17%   |
| Unknown          | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite M645                   | 1         | 2.17%   |
| Synology DS1019+                         | 1         | 2.17%   |
| Sony VGN-UX27GN                          | 1         | 2.17%   |
| Pegatron Deepcam                         | 1         | 2.17%   |
| MSI GL72M 7REX                           | 1         | 2.17%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 2.17%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 2.17%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 2.17%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 2.17%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 2.17%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 2.17%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 2.17%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 2.17%   |
| IBM 26446AG                              | 1         | 2.17%   |
| IBM 264070A                              | 1         | 2.17%   |
| HP ZBook 15 G5                           | 1         | 2.17%   |
| HP ProBook 4310s                         | 1         | 2.17%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 2.17%   |
| HP Mini 110-3500                         | 1         | 2.17%   |
| HP Laptop 14-dq1xxx                      | 1         | 2.17%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 2.17%   |
| HP EliteBook 8460p                       | 1         | 2.17%   |
| HP EliteBook 2740p                       | 1         | 2.17%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 2.17%   |
| HP Compaq Mini CQ10-600                  | 1         | 2.17%   |
| Haier U144S                              | 1         | 2.17%   |
| Google Samus                             | 1         | 2.17%   |
| Gateway MX3631m                          | 1         | 2.17%   |
| Fujitsu LIFEBOOK P702                    | 1         | 2.17%   |
| Dell XPS 15 7590                         | 1         | 2.17%   |
| Dell Studio 1747                         | 1         | 2.17%   |
| Dell Inspiron MM061                      | 1         | 2.17%   |
| Dell Inspiron 5566                       | 1         | 2.17%   |
| Dell Inspiron 5447                       | 1         | 2.17%   |
| Dell Inspiron 3180                       | 1         | 2.17%   |
| ASUS ZenBook UX431FA                     | 1         | 2.17%   |
| ASUS X555LAB                             | 1         | 2.17%   |
| ASUS X550EA                              | 1         | 2.17%   |
| ASUS X200MA                              | 1         | 2.17%   |
| ASUS N10Jc                               | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 10.87%  |
| Dell Inspiron     | 4         | 8.7%    |
| Acer Aspire       | 4         | 8.7%    |
| HP EliteBook      | 3         | 6.52%   |
| Toshiba Satellite | 1         | 2.17%   |
| Synology DS1019+  | 1         | 2.17%   |
| Sony VGN-UX27GN   | 1         | 2.17%   |
| Pegatron Deepcam  | 1         | 2.17%   |
| MSI GL72M         | 1         | 2.17%   |
| Lenovo Yoga       | 1         | 2.17%   |
| Lenovo IdeaPad    | 1         | 2.17%   |
| IBM ThinkPad      | 1         | 2.17%   |
| IBM 26446AG       | 1         | 2.17%   |
| IBM 264070A       | 1         | 2.17%   |
| HP ZBook          | 1         | 2.17%   |
| HP ProBook        | 1         | 2.17%   |
| HP Presario       | 1         | 2.17%   |
| HP Mini           | 1         | 2.17%   |
| HP Laptop         | 1         | 2.17%   |
| HP ENVY           | 1         | 2.17%   |
| HP Compaq         | 1         | 2.17%   |
| Haier U144S       | 1         | 2.17%   |
| Google Samus      | 1         | 2.17%   |
| Gateway MX3631m   | 1         | 2.17%   |
| Fujitsu LIFEBOOK  | 1         | 2.17%   |
| Dell XPS          | 1         | 2.17%   |
| Dell Studio       | 1         | 2.17%   |
| ASUS ZenBook      | 1         | 2.17%   |
| ASUS X555LAB      | 1         | 2.17%   |
| ASUS X550EA       | 1         | 2.17%   |
| ASUS X200MA       | 1         | 2.17%   |
| ASUS N10Jc        | 1         | 2.17%   |
| ASUS E502SA       | 1         | 2.17%   |
| Unknown           | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2014    | 6         | 13.04%  |
| 2019    | 5         | 10.87%  |
| 2018    | 5         | 10.87%  |
| 2010    | 4         | 8.7%    |
| 2017    | 3         | 6.52%   |
| 2006    | 3         | 6.52%   |
| 2021    | 2         | 4.35%   |
| 2016    | 2         | 4.35%   |
| 2013    | 2         | 4.35%   |
| 2012    | 2         | 4.35%   |
| 2011    | 2         | 4.35%   |
| 2009    | 2         | 4.35%   |
| 2005    | 2         | 4.35%   |
| Unknown | 2         | 4.35%   |
| 2015    | 1         | 2.17%   |
| 2008    | 1         | 2.17%   |
| 2007    | 1         | 2.17%   |
| 1999    | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 97.83%  |
| Yes  | 1         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 12        | 25.53%  |
| 4.01-8.0    | 11        | 23.4%   |
| 8.01-16.0   | 5         | 10.64%  |
| 16.01-24.0  | 4         | 8.51%   |
| 1.01-2.0    | 4         | 8.51%   |
| 0.51-1.0    | 4         | 8.51%   |
| 2.01-3.0    | 3         | 6.38%   |
| 0.01-0.5    | 2         | 4.26%   |
| 32.01-64.0  | 1         | 2.13%   |
| 64.01-256.0 | 1         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 15        | 31.25%  |
| 1.01-2.0  | 9         | 18.75%  |
| 0.51-1.0  | 8         | 16.67%  |
| 2.01-3.0  | 5         | 10.42%  |
| 4.01-8.0  | 4         | 8.33%   |
| 3.01-4.0  | 3         | 6.25%   |
| 0         | 2         | 4.17%   |
| 8.01-16.0 | 1         | 2.08%   |
| Unknown   | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 74.47%  |
| 2      | 10        | 21.28%  |
| 7      | 1         | 2.13%   |
| 0      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 67.39%  |
| Yes       | 15        | 32.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 82.61%  |
| No        | 8         | 17.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 91.3%   |
| No        | 4         | 8.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 56.52%  |
| No        | 20        | 43.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 28.26%  |
| Canada       | 5         | 10.87%  |
| UK           | 4         | 8.7%    |
| Russia       | 4         | 8.7%    |
| Germany      | 3         | 6.52%   |
| Brazil       | 3         | 6.52%   |
| Australia    | 2         | 4.35%   |
| Venezuela    | 1         | 2.17%   |
| Spain        | 1         | 2.17%   |
| South Africa | 1         | 2.17%   |
| Slovakia     | 1         | 2.17%   |
| Portugal     | 1         | 2.17%   |
| Poland       | 1         | 2.17%   |
| Mexico       | 1         | 2.17%   |
| Italy        | 1         | 2.17%   |
| Guatemala    | 1         | 2.17%   |
| France       | 1         | 2.17%   |
| Egypt        | 1         | 2.17%   |
| Czechia      | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| St Petersburg    | 3         | 6.38%   |
| Stratford        | 2         | 4.26%   |
| Springfield      | 2         | 4.26%   |
| Fulham           | 2         | 4.26%   |
| Vernon           | 1         | 2.13%   |
| Tymovskoye       | 1         | 2.13%   |
| Tampa            | 1         | 2.13%   |
| Sydney           | 1         | 2.13%   |
| Stewartstown     | 1         | 2.13%   |
| Sisteron         | 1         | 2.13%   |
| Semily           | 1         | 2.13%   |
| Sao Paulo        | 1         | 2.13%   |
| San Mateo        | 1         | 2.13%   |
| Saarbrücken     | 1         | 2.13%   |
| Rzeszów         | 1         | 2.13%   |
| Rostock          | 1         | 2.13%   |
| Purdys           | 1         | 2.13%   |
| Oakville         | 1         | 2.13%   |
| Merrill          | 1         | 2.13%   |
| Mérida          | 1         | 2.13%   |
| Manitowoc        | 1         | 2.13%   |
| Madrid           | 1         | 2.13%   |
| Lindavista Norte | 1         | 2.13%   |
| Lincoln          | 1         | 2.13%   |
| Leipzig          | 1         | 2.13%   |
| Larkspur         | 1         | 2.13%   |
| Johannesburg     | 1         | 2.13%   |
| Hampstead        | 1         | 2.13%   |
| Guatemala City   | 1         | 2.13%   |
| Funchal          | 1         | 2.13%   |
| Franklin         | 1         | 2.13%   |
| Ejido            | 1         | 2.13%   |
| Dallas           | 1         | 2.13%   |
| Corrego Novo     | 1         | 2.13%   |
| Chapel Hill      | 1         | 2.13%   |
| Cairo            | 1         | 2.13%   |
| Brockport        | 1         | 2.13%   |
| Brisbane         | 1         | 2.13%   |
| Bratislava       | 1         | 2.13%   |
| Boucherville     | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 12.73%  |
| Samsung Electronics | 6         | 7      | 10.91%  |
| Kingston            | 5         | 6      | 9.09%   |
| Unknown             | 4         | 5      | 7.27%   |
| Toshiba             | 4         | 6      | 7.27%   |
| Seagate             | 4         | 13     | 7.27%   |
| WDC                 | 3         | 4      | 5.45%   |
| HGST                | 3         | 3      | 5.45%   |
| Intel               | 2         | 4      | 3.64%   |
| Crucial             | 2         | 2      | 3.64%   |
| SPCC                | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| SanDisk             | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| KC600               | 1         | 1      | 1.82%   |
| JMicron Technology  | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| IBM                 | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| Emtec               | 1         | 1      | 1.82%   |
| Dell                | 1         | 2      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| AMD                 | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                    | 2         | 3.45%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 3.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 1.72%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 1.72%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 1.72%   |
| Unknown SD32G  32GB                       | 1         | 1.72%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 1.72%   |
| Toshiba NVMe SSD Drive 256GB              | 1         | 1.72%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.72%   |
| Toshiba MQ01ABD1 1TB                      | 1         | 1.72%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.72%   |
| Toshiba MK4009GAL 40GB                    | 1         | 1.72%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.72%   |
| SPCC Solid State Disk 256GB               | 1         | 1.72%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 1.72%   |
| Seagate ST98823A 80GB                     | 1         | 1.72%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 1.72%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.72%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1.72%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 1.72%   |
| Samsung Portable SSD T5 1TB               | 1         | 1.72%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.72%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 1.72%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 1.72%   |
| Samsung HM160HI 160GB                     | 1         | 1.72%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD       | 1         | 1.72%   |
| LITEON CV1-8B128-HP 128GB SSD             | 1         | 1.72%   |
| Kingston SV300S37A120G 120GB SSD          | 1         | 1.72%   |
| Kingston SUV500MS480G 480GB SSD           | 1         | 1.72%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 1.72%   |
| Kingston RBU-SUS151S364GD 64GB SSD        | 1         | 1.72%   |
| Kingston KC600 128GB SSD                  | 1         | 1.72%   |
| KC600 SSD 128GB                           | 1         | 1.72%   |
| JMicron Generic 500GB                     | 1         | 1.72%   |
| Intenso SSD 128GB                         | 1         | 1.72%   |
| Intel SSDPEKKA256G7 256GB                 | 1         | 1.72%   |
| Intel HBRPEKNX0101AHO 16GB                | 1         | 1.72%   |
| Intel HBRPEKNX0101AH 256GB                | 1         | 1.72%   |
| IBM DARA-212000 12GB                      | 1         | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 33.33%  |
| Seagate             | 4         | 13     | 19.05%  |
| Toshiba             | 3         | 4      | 14.29%  |
| HGST                | 3         | 3      | 14.29%  |
| WDC                 | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |
| IBM                 | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 6      | 23.81%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| SPCC                | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| KC600               | 1         | 1      | 4.76%   |
| Intenso             | 1         | 1      | 4.76%   |
| Emtec               | 1         | 1      | 4.76%   |
| Dell                | 1         | 2      | 4.76%   |
| China               | 1         | 1      | 4.76%   |
| AMD                 | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 32     | 40.38%  |
| SSD  | 19        | 23     | 36.54%  |
| NVMe | 9         | 15     | 17.31%  |
| MMC  | 3         | 3      | 5.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 53     | 72.55%  |
| NVMe | 8         | 14     | 15.69%  |
| SAS  | 3         | 3      | 5.88%   |
| MMC  | 3         | 3      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 37     | 80%     |
| 0.51-1.0   | 6         | 7      | 15%     |
| 1.01-2.0   | 1         | 1      | 2.5%    |
| 4.01-10.0  | 1         | 10     | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 27.08%  |
| 1-20           | 8         | 16.67%  |
| 251-500        | 6         | 12.5%   |
| Unknown        | 6         | 12.5%   |
| 21-50          | 5         | 10.42%  |
| 501-1000       | 5         | 10.42%  |
| 1001-2000      | 2         | 4.17%   |
| 51-100         | 2         | 4.17%   |
| More than 3000 | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 31        | 64.58%  |
| Unknown  | 6         | 12.5%   |
| 21-50    | 4         | 8.33%   |
| 101-250  | 3         | 6.25%   |
| 51-100   | 3         | 6.25%   |
| 501-1000 | 1         | 2.08%   |

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
| Works    | 29        | 49     | 58%     |
| Detected | 12        | 14     | 24%     |
| Malfunc  | 9         | 10     | 18%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 72%     |
| AMD                          | 6         | 12%     |
| Samsung Electronics          | 3         | 6%      |
| Toshiba America Info Systems | 1         | 2%      |
| SK hynix                     | 1         | 2%      |
| SanDisk                      | 1         | 2%      |
| Marvell Technology Group     | 1         | 2%      |
| ADATA Technology             | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 11.32%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 5.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 5.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 5.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 3.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 3.77%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 3.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 3.77%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.77%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.89%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 1.89%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.89%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 1.89%   |
| Intel SSD 600P Series                                                            | 1         | 1.89%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.89%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.89%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 62.75%  |
| IDE  | 9         | 17.65%  |
| NVMe | 8         | 15.69%  |
| RAID | 2         | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 82.61%  |
| AMD    | 7         | 15.22%  |
| ARM    | 1         | 2.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                      | 2         | 4.35%   |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 4.35%   |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 4.35%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 2.17%   |
| Intel Pentium M processor 1.70GHz                      | 1         | 2.17%   |
| Intel Pentium M processor 1.60GHz                      | 1         | 2.17%   |
| Intel Pentium M processor 1.50GHz                      | 1         | 2.17%   |
| Intel Pentium III (Coppermine)                         | 1         | 2.17%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 2.17%   |
| Intel Mobile Pentium MMX                               | 1         | 2.17%   |
| Intel Core Solo CPU U1500 @ 1.33GHz                    | 1         | 2.17%   |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 2.17%   |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 2.17%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 2.17%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 2.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz                      | 1         | 2.17%   |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 2.17%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 2.17%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 2.17%   |
| Intel Core i5 CPU M 480 @ 2.67GHz                      | 1         | 2.17%   |
| Intel Core i3-5020U CPU @ 2.20GHz                      | 1         | 2.17%   |
| Intel Core i3-3110M CPU @ 2.40GHz                      | 1         | 2.17%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 2.17%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 2.17%   |
| Intel Core 2 Duo CPU P7570 @ 2.26GHz                   | 1         | 2.17%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 2.17%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 2.17%   |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 2.17%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 1         | 2.17%   |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 2.17%   |
| Intel Atom CPU N270 @ 1.60GHz                          | 1         | 2.17%   |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 2.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 2.17%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx          | 1         | 2.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1         | 2.17%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G          | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 12        | 26.09%  |
| Intel Celeron     | 5         | 10.87%  |
| Intel Atom        | 4         | 8.7%    |
| Other             | 3         | 6.52%   |
| Intel Pentium M   | 3         | 6.52%   |
| Intel Core 2 Duo  | 3         | 6.52%   |
| Intel Core i7     | 2         | 4.35%   |
| Intel Core i3     | 2         | 4.35%   |
| AMD A4            | 2         | 4.35%   |
| Intel Xeon        | 1         | 2.17%   |
| Intel Pentium III | 1         | 2.17%   |
| Intel Pentium     | 1         | 2.17%   |
| Intel Core Solo   | 1         | 2.17%   |
| Intel Core i9     | 1         | 2.17%   |
| Intel Core 2      | 1         | 2.17%   |
| AMD Ryzen 7       | 1         | 2.17%   |
| AMD Ryzen 5       | 1         | 2.17%   |
| AMD A6            | 1         | 2.17%   |
| AMD A10           | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 50%     |
| 4      | 10        | 21.74%  |
| 1      | 9         | 19.57%  |
| 8      | 2         | 4.35%   |
| 6      | 1         | 2.17%   |
| 3      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 52.17%  |
| 2      | 22        | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 46.81%  |
| Unknown        | 22        | 46.81%  |
| 32-bit         | 3         | 6.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 54.17%  |
| 0x30678    | 3         | 6.25%   |
| 0x306a9    | 2         | 4.17%   |
| 0x206a7    | 2         | 4.17%   |
| 0x106ca    | 2         | 4.17%   |
| 0x06006704 | 2         | 4.17%   |
| 0x906ea    | 1         | 2.08%   |
| 0x806eb    | 1         | 2.08%   |
| 0x706e5    | 1         | 2.08%   |
| 0x683      | 1         | 2.08%   |
| 0x506c9    | 1         | 2.08%   |
| 0x406c4    | 1         | 2.08%   |
| 0x306d4    | 1         | 2.08%   |
| 0x20655    | 1         | 2.08%   |
| 0x106e5    | 1         | 2.08%   |
| 0x1067a    | 1         | 2.08%   |
| 0x0810100b | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 13.04%  |
| P6          | 5         | 10.87%  |
| Silvermont  | 4         | 8.7%    |
| Penryn      | 3         | 6.52%   |
| Goldmont    | 3         | 6.52%   |
| Excavator   | 3         | 6.52%   |
| Bonnell     | 3         | 6.52%   |
| Westmere    | 2         | 4.35%   |
| SandyBridge | 2         | 4.35%   |
| IvyBridge   | 2         | 4.35%   |
| Broadwell   | 2         | 4.35%   |
| Unknown     | 2         | 4.35%   |
| Zen 2       | 1         | 2.17%   |
| Zen         | 1         | 2.17%   |
| Skylake     | 1         | 2.17%   |
| Puma        | 1         | 2.17%   |
| Nehalem     | 1         | 2.17%   |
| Jaguar      | 1         | 2.17%   |
| IceLake     | 1         | 2.17%   |
| Haswell     | 1         | 2.17%   |
| Core        | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 32        | 64%     |
| AMD      | 12        | 24%     |
| Nvidia   | 4         | 8%      |
| Neomagic | 2         | 4%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 3         | 5.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.77%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 3.77%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.89%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.89%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.89%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.89%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.89%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.89%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.89%   |
| Intel HD Graphics 630                                                                    | 1         | 1.89%   |
| Intel HD Graphics 620                                                                    | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.89%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.89%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.89%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.89%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.89%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.89%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 1.89%   |
| AMD Renoir                                                                               | 1         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.89%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.89%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 50%     |
| 1 x AMD        | 9         | 19.57%  |
| 2 x Intel      | 4         | 8.7%    |
| Intel + Nvidia | 3         | 6.52%   |
| 1 x Neomagic   | 2         | 4.35%   |
| Intel + AMD    | 2         | 4.35%   |
| Other          | 1         | 2.17%   |
| 2 x AMD        | 1         | 2.17%   |
| 1 x Nvidia     | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 42        | 89.36%  |
| Unknown     | 4         | 8.51%   |
| Proprietary | 1         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 89.13%  |
| 0.01-0.5   | 3         | 6.52%   |
| 1.01-2.0   | 1         | 2.17%   |
| 0.51-1.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 20.45%  |
| LG Display              | 7         | 15.91%  |
| Chimei Innolux          | 6         | 13.64%  |
| BOE                     | 4         | 9.09%   |
| Samsung Electronics     | 3         | 6.82%   |
| Chi Mei Optoelectronics | 3         | 6.82%   |
| LG Philips              | 2         | 4.55%   |
| ONN                     | 1         | 2.27%   |
| Lenovo                  | 1         | 2.27%   |
| InfoVision              | 1         | 2.27%   |
| HannStar                | 1         | 2.27%   |
| Goldstar                | 1         | 2.27%   |
| Envision                | 1         | 2.27%   |
| DENON                   | 1         | 2.27%   |
| CSO                     | 1         | 2.27%   |
| CPT                     | 1         | 2.27%   |
| Acer                    | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 2.27%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                      | 1         | 2.27%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 2.27%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.27%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 2.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch              | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 2.27%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 2.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.27%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 2.27%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 2.27%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 2.27%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 2.27%   |
| CPT LCD Monitor CPT04E2 1024x600 222x130mm 10.1-inch                     | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 309x173mm 13.9-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 18        | 40.91%  |
| 1920x1080 (FHD)   | 6         | 13.64%  |
| 1280x800 (WXGA)   | 5         | 11.36%  |
| 1024x600          | 3         | 6.82%   |
| 3840x2160 (4K)    | 2         | 4.55%   |
| 1600x900 (HD+)    | 2         | 4.55%   |
| 2880x1800         | 1         | 2.27%   |
| 2560x1700         | 1         | 2.27%   |
| 2560x1440 (QHD)   | 1         | 2.27%   |
| 2560x1080         | 1         | 2.27%   |
| 1920x1200 (WUXGA) | 1         | 2.27%   |
| 1360x768          | 1         | 2.27%   |
| 1280x768          | 1         | 2.27%   |
| 1280x1024 (SXGA)  | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 31.82%  |
| 13     | 8         | 18.18%  |
| 14     | 6         | 13.64%  |
| 17     | 4         | 9.09%   |
| 12     | 3         | 6.82%   |
| 10     | 3         | 6.82%   |
| 31     | 2         | 4.55%   |
| 11     | 2         | 4.55%   |
| 32     | 1         | 2.27%   |
| 29     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 61.36%  |
| 201-300     | 10        | 22.73%  |
| 601-700     | 3         | 6.82%   |
| 351-400     | 3         | 6.82%   |
| 701-800     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 76.19%  |
| 16/10 | 7         | 16.67%  |
| 5/4   | 1         | 2.38%   |
| 3/2   | 1         | 2.38%   |
| 21/9  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 31.82%  |
| 81-90          | 12        | 27.27%  |
| 71-80          | 3         | 6.82%   |
| 351-500        | 3         | 6.82%   |
| 41-50          | 3         | 6.82%   |
| 61-70          | 2         | 4.55%   |
| 51-60          | 2         | 4.55%   |
| 121-130        | 2         | 4.55%   |
| 301-350        | 1         | 2.27%   |
| 141-150        | 1         | 2.27%   |
| 131-140        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 19        | 44.19%  |
| 121-160       | 12        | 27.91%  |
| 51-100        | 7         | 16.28%  |
| More than 240 | 2         | 4.65%   |
| 161-240       | 2         | 4.65%   |
| 1-50          | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 80.43%  |
| 2     | 5         | 10.87%  |
| 0     | 4         | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 27        | 34.62%  |
| Intel                           | 22        | 28.21%  |
| Qualcomm Atheros                | 15        | 19.23%  |
| Broadcom                        | 6         | 7.69%   |
| Marvell Technology Group        | 3         | 3.85%   |
| Qualcomm Atheros Communications | 1         | 1.28%   |
| Qualcomm                        | 1         | 1.28%   |
| LSI                             | 1         | 1.28%   |
| Dresden Elektronik              | 1         | 1.28%   |
| Broadcom Limited                | 1         | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 12.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 7.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.25%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.25%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.12%   |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                                         | 1         | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.12%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.12%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.12%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.12%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 1.12%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.12%   |
| LSI WinModem 56k                                                               | 1         | 1.12%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.12%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.12%   |
| Intel Wireless 8260                                                            | 1         | 1.12%   |
| Intel Wireless 7260                                                            | 1         | 1.12%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.12%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 44.19%  |
| Qualcomm Atheros                | 14        | 32.56%  |
| Broadcom                        | 4         | 9.3%    |
| Realtek Semiconductor           | 3         | 6.98%   |
| Qualcomm Atheros Communications | 1         | 2.33%   |
| Marvell Technology Group        | 1         | 2.33%   |
| Broadcom Limited                | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 16.28%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 4.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 4.65%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 4.65%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 4.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 4.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 2.33%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.33%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 2.33%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.33%   |
| Intel Wireless-AC 9260                                                         | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.33%   |
| Intel Wireless 8260                                                            | 1         | 2.33%   |
| Intel Wireless 7260                                                            | 1         | 2.33%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.33%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 2.33%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 24        | 58.54%  |
| Intel                    | 10        | 24.39%  |
| Broadcom                 | 3         | 7.32%   |
| Marvell Technology Group | 2         | 4.88%   |
| Qualcomm Atheros         | 1         | 2.44%   |
| Qualcomm                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 26.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 19.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.44%   |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                            | 1         | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.44%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 2.44%   |
| Intel WiMAX Connection 2400m                                      | 1         | 2.44%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.44%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.44%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express             | 1         | 2.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.44%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 50%     |
| Ethernet | 37        | 44.05%  |
| Modem    | 5         | 5.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 65.96%  |
| Ethernet | 16        | 34.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 71.74%  |
| 1     | 10        | 21.74%  |
| 0     | 3         | 6.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 82.98%  |
| Yes  | 8         | 17.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 34.62%  |
| Qualcomm Atheros Communications | 4         | 15.38%  |
| Lite-On Technology              | 3         | 11.54%  |
| IMC Networks                    | 2         | 7.69%   |
| Broadcom                        | 2         | 7.69%   |
| Realtek Semiconductor           | 1         | 3.85%   |
| Marvell Semiconductor           | 1         | 3.85%   |
| Hewlett-Packard                 | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |
| Alps Electric                   | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 15.38%  |
| Intel Bluetooth wireless interface                  | 3         | 11.54%  |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 7.69%   |
| Intel AX200 Bluetooth                               | 2         | 7.69%   |
| Realtek Bluetooth Radio                             | 1         | 3.85%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.85%   |
| IMC Networks Bluetooth Device                       | 1         | 3.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.85%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.85%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.85%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.85%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 3.85%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 35        | 74.47%  |
| AMD                       | 9         | 19.15%  |
| Sennheiser Communications | 1         | 2.13%   |
| Realtek Semiconductor     | 1         | 2.13%   |
| Cirrus Logic              | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 8.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 5.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 5.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 5.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.57%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.57%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 3.57%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.79%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.79%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.79%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.79%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.79%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.79%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25.64%  |
| Unknown             | 9         | 23.08%  |
| SK hynix            | 7         | 17.95%  |
| Elpida              | 4         | 10.26%  |
| Micron Technology   | 3         | 7.69%   |
| Crucial             | 2         | 5.13%   |
| A-DATA Technology   | 2         | 5.13%   |
| Unknown (ABCD)      | 1         | 2.56%   |
| Kingston            | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 7.14%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 4.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4.76%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 4.76%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 2.38%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 2.38%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 2.38%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.38%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 2.38%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 2.38%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.38%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 2.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 2.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.38%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.38%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 2.38%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.38%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.38%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.38%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s        | 1         | 2.38%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.38%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s           | 1         | 2.38%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s        | 1         | 2.38%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 2.38%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 2.38%   |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.38%   |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s        | 1         | 2.38%   |
| Crucial RAM CT102464BF186D.M16 8GB SODIMM DDR3 1867MT/s          | 1         | 2.38%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                       | 1         | 2.38%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 43.24%  |
| DDR4   | 8         | 21.62%  |
| DDR    | 4         | 10.81%  |
| LPDDR3 | 3         | 8.11%   |
| SDRAM  | 2         | 5.41%   |
| LPDDR4 | 2         | 5.41%   |
| DRAM   | 1         | 2.7%    |
| DDR2   | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 89.19%  |
| Row Of Chips | 3         | 8.11%   |
| DIMM         | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 15        | 37.5%   |
| 8192 | 11        | 27.5%   |
| 2048 | 6         | 15%     |
| 1024 | 3         | 7.5%    |
| 512  | 3         | 7.5%    |
| 256  | 1         | 2.5%    |
| 128  | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 20.51%  |
| Unknown | 6         | 15.38%  |
| 1334    | 5         | 12.82%  |
| 2400    | 4         | 10.26%  |
| 2133    | 4         | 10.26%  |
| 3200    | 2         | 5.13%   |
| 2667    | 2         | 5.13%   |
| 1333    | 2         | 5.13%   |
| 4199    | 1         | 2.56%   |
| 1867    | 1         | 2.56%   |
| 1400    | 1         | 2.56%   |
| 1200    | 1         | 2.56%   |
| 1067    | 1         | 2.56%   |
| 533     | 1         | 2.56%   |

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
| Chicony Electronics                    | 12        | 34.29%  |
| Realtek Semiconductor                  | 5         | 14.29%  |
| Suyin                                  | 3         | 8.57%   |
| Sunplus Innovation Technology          | 2         | 5.71%   |
| Microdia                               | 2         | 5.71%   |
| IMC Networks                           | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Syntek                                 | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| Ricoh                                  | 1         | 2.86%   |
| Quanta                                 | 1         | 2.86%   |
| Lenovo                                 | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |
| Acer                                   | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 5.71%   |
| Chicony Integrated Camera                           | 2         | 5.71%   |
| Chicony HD WebCam                                   | 2         | 5.71%   |
| Syntek EasyCamera                                   | 1         | 2.86%   |
| Suyin Integrated_Webcam_HD                          | 1         | 2.86%   |
| Suyin HP TrueVision HD                              | 1         | 2.86%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.86%   |
| Sunplus HP Universal Camera                         | 1         | 2.86%   |
| Sunplus HD WebCam                                   | 1         | 2.86%   |
| Silicon Motion NCM-G102                             | 1         | 2.86%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 2.86%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 2.86%   |
| Realtek USB Camera                                  | 1         | 2.86%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 2.86%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.86%   |
| Lenovo Integrated Webcam                            | 1         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.86%   |
| IMC Networks Integrated Camera                      | 1         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.86%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.86%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.86%   |
| Chicony HP HD Camera                                | 1         | 2.86%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.86%   |
| Chicony CNF8243 Webcam                              | 1         | 2.86%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.86%   |
| Acer BisonCam, NB Pro                               | 1         | 2.86%   |

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
| 0     | 27        | 55.1%   |
| 1     | 13        | 26.53%  |
| 2     | 8         | 16.33%  |
| 3     | 1         | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 22.58%  |
| Graphics card            | 6         | 19.35%  |
| Modem                    | 5         | 16.13%  |
| Net/wireless             | 2         | 6.45%   |
| Chipcard                 | 2         | 6.45%   |
| Camera                   | 2         | 6.45%   |
| Unclassified device      | 1         | 3.23%   |
| Storage                  | 1         | 3.23%   |
| Sound                    | 1         | 3.23%   |
| Network                  | 1         | 3.23%   |
| Multimedia controller    | 1         | 3.23%   |
| Communication controller | 1         | 3.23%   |
| Bluetooth                | 1         | 3.23%   |


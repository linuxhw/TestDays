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

Total: 54

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alpine 3.15.0               | 6         | 13.64%  |
| Alpine 3.16.0               | 5         | 11.36%  |
| Alpine 3.15.0_alpha20210804 | 4         | 9.09%   |
| Alpine 3.14.0               | 4         | 9.09%   |
| Alpine 3.12.0               | 4         | 9.09%   |
| Alpine 3.14.2               | 2         | 4.55%   |
| Alpine 3.13.5               | 2         | 4.55%   |
| Alpine 3.13.0_alpha20201218 | 2         | 4.55%   |
| Alpine 3.13.0_alpha20200917 | 2         | 4.55%   |
| Alpine 3.11.2               | 2         | 4.55%   |
| Alpine 3.16.0_alpha20220316 | 1         | 2.27%   |
| Alpine 3.15.4               | 1         | 2.27%   |
| Alpine 3.15.2               | 1         | 2.27%   |
| Alpine 3.15.0_rc5           | 1         | 2.27%   |
| Alpine 3.14.0_alpha20210212 | 1         | 2.27%   |
| Alpine 3.13.1               | 1         | 2.27%   |
| Alpine 3.13.0_rc2           | 1         | 2.27%   |
| Alpine 3.13.0_alpha20200626 | 1         | 2.27%   |
| Alpine 3.12.3               | 1         | 2.27%   |
| Alpine 3.12.1               | 1         | 2.27%   |
| Alpine 3.11.5               | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.83-0-lts           | 2         | 4.44%   |
| 5.4.43-1-lts           | 2         | 4.44%   |
| 5.15.47-0-lts          | 2         | 4.44%   |
| 5.15.41-0-lts          | 2         | 4.44%   |
| 5.15.4-0-lts           | 2         | 4.44%   |
| 5.8.12-0-edge          | 1         | 2.22%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 2.22%   |
| 5.4.84-0-lts           | 1         | 2.22%   |
| 5.4.72-0-lts           | 1         | 2.22%   |
| 5.4.64-0-lts           | 1         | 2.22%   |
| 5.4.46-0-lts           | 1         | 2.22%   |
| 5.4.27-0-lts           | 1         | 2.22%   |
| 5.17.9-0-edge          | 1         | 2.22%   |
| 5.17.0-0-edge          | 1         | 2.22%   |
| 5.16.12-may            | 1         | 2.22%   |
| 5.16.1-may             | 1         | 2.22%   |
| 5.15.37-0-lts          | 1         | 2.22%   |
| 5.15.34                | 1         | 2.22%   |
| 5.15.30-0-lts          | 1         | 2.22%   |
| 5.15.28-0-lts          | 1         | 2.22%   |
| 5.15.26-0-lts          | 1         | 2.22%   |
| 5.15.16-0-lts          | 1         | 2.22%   |
| 5.15.12-0-lts          | 1         | 2.22%   |
| 5.14.8-0-edge          | 1         | 2.22%   |
| 5.13.0-0-edge          | 1         | 2.22%   |
| 5.12.8-0-edge          | 1         | 2.22%   |
| 5.10.70-0-lts          | 1         | 2.22%   |
| 5.10.69-0-lts          | 1         | 2.22%   |
| 5.10.68-0-lts          | 1         | 2.22%   |
| 5.10.61-0-lts          | 1         | 2.22%   |
| 5.10.5-0-lts           | 1         | 2.22%   |
| 5.10.44-0-lts          | 1         | 2.22%   |
| 5.10.43-0-lts          | 1         | 2.22%   |
| 5.10.42-0-legacy       | 1         | 2.22%   |
| 5.10.4-0-lts           | 1         | 2.22%   |
| 5.10.38-0-lts          | 1         | 2.22%   |
| 5.10.29-0-lts          | 1         | 2.22%   |
| 5.10.11-0-lts          | 1         | 2.22%   |
| 4.4.59+                | 1         | 2.22%   |
| 3.10.18                | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.83  | 2         | 4.44%   |
| 5.4.43  | 2         | 4.44%   |
| 5.15.47 | 2         | 4.44%   |
| 5.15.41 | 2         | 4.44%   |
| 5.15.4  | 2         | 4.44%   |
| 5.8.12  | 1         | 2.22%   |
| 5.6.2   | 1         | 2.22%   |
| 5.4.84  | 1         | 2.22%   |
| 5.4.72  | 1         | 2.22%   |
| 5.4.64  | 1         | 2.22%   |
| 5.4.46  | 1         | 2.22%   |
| 5.4.27  | 1         | 2.22%   |
| 5.17.9  | 1         | 2.22%   |
| 5.17.0  | 1         | 2.22%   |
| 5.16.12 | 1         | 2.22%   |
| 5.16.1  | 1         | 2.22%   |
| 5.15.37 | 1         | 2.22%   |
| 5.15.34 | 1         | 2.22%   |
| 5.15.30 | 1         | 2.22%   |
| 5.15.28 | 1         | 2.22%   |
| 5.15.26 | 1         | 2.22%   |
| 5.15.16 | 1         | 2.22%   |
| 5.15.12 | 1         | 2.22%   |
| 5.14.8  | 1         | 2.22%   |
| 5.13.0  | 1         | 2.22%   |
| 5.12.8  | 1         | 2.22%   |
| 5.10.70 | 1         | 2.22%   |
| 5.10.69 | 1         | 2.22%   |
| 5.10.68 | 1         | 2.22%   |
| 5.10.61 | 1         | 2.22%   |
| 5.10.5  | 1         | 2.22%   |
| 5.10.44 | 1         | 2.22%   |
| 5.10.43 | 1         | 2.22%   |
| 5.10.42 | 1         | 2.22%   |
| 5.10.4  | 1         | 2.22%   |
| 5.10.38 | 1         | 2.22%   |
| 5.10.29 | 1         | 2.22%   |
| 5.10.11 | 1         | 2.22%   |
| 4.4.59  | 1         | 2.22%   |
| 3.10.18 | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 13        | 30.23%  |
| 5.10    | 11        | 25.58%  |
| 5.4     | 9         | 20.93%  |
| 5.17    | 2         | 4.65%   |
| 5.8     | 1         | 2.33%   |
| 5.6     | 1         | 2.33%   |
| 5.16    | 1         | 2.33%   |
| 5.14    | 1         | 2.33%   |
| 5.13    | 1         | 2.33%   |
| 5.12    | 1         | 2.33%   |
| 4.4     | 1         | 2.33%   |
| 3.10    | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 35        | 83.33%  |
| i686   | 5         | 11.9%   |
| i586   | 1         | 2.38%   |
| armv7l | 1         | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 34        | 80.95%  |
| GNOME   | 4         | 9.52%   |
| XFCE    | 3         | 7.14%   |
| KDE5    | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 50%     |
| X11     | 17        | 38.64%  |
| Wayland | 5         | 11.36%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 78.57%  |
| LightDM | 5         | 11.9%   |
| XDM     | 1         | 2.38%   |
| SDDM    | 1         | 2.38%   |
| LXDM    | 1         | 2.38%   |
| GDM     | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 24        | 55.81%  |
| Unknown | 13        | 30.23%  |
| en_US   | 4         | 9.3%    |
| ru_RU   | 1         | 2.33%   |
| en_GB   | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 29        | 69.05%  |
| EFI  | 13        | 30.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 34        | 79.07%  |
| Btrfs   | 4         | 9.3%    |
| Tmpfs   | 1         | 2.33%   |
| Overlay | 1         | 2.33%   |
| F2fs    | 1         | 2.33%   |
| Ext2    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 55.81%  |
| GPT     | 12        | 27.91%  |
| MBR     | 7         | 16.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 90.48%  |
| Yes       | 4         | 9.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 90.48%  |
| Yes       | 4         | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 9         | 21.43%  |
| Lenovo           | 7         | 16.67%  |
| ASUSTek Computer | 6         | 14.29%  |
| Dell             | 5         | 11.9%   |
| Acer             | 4         | 9.52%   |
| IBM              | 3         | 7.14%   |
| Synology         | 1         | 2.38%   |
| Sony             | 1         | 2.38%   |
| Pegatron         | 1         | 2.38%   |
| MSI              | 1         | 2.38%   |
| Haier            | 1         | 2.38%   |
| Google           | 1         | 2.38%   |
| Gateway          | 1         | 2.38%   |
| Unknown          | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Synology DS1019+                         | 1         | 2.38%   |
| Sony VGN-UX27GN                          | 1         | 2.38%   |
| Pegatron Deepcam                         | 1         | 2.38%   |
| MSI GL72M 7REX                           | 1         | 2.38%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 2.38%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 2.38%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 2.38%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 2.38%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 2.38%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 2.38%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 2.38%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 2.38%   |
| IBM 26446AG                              | 1         | 2.38%   |
| IBM 264070A                              | 1         | 2.38%   |
| HP ZBook 15 G5                           | 1         | 2.38%   |
| HP ProBook 4310s                         | 1         | 2.38%   |
| HP Mini 110-3500                         | 1         | 2.38%   |
| HP Laptop 14-dq1xxx                      | 1         | 2.38%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 2.38%   |
| HP EliteBook 8460p                       | 1         | 2.38%   |
| HP EliteBook 2740p                       | 1         | 2.38%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 2.38%   |
| HP Compaq Mini CQ10-600                  | 1         | 2.38%   |
| Haier U144S                              | 1         | 2.38%   |
| Google Samus                             | 1         | 2.38%   |
| Gateway MX3631m                          | 1         | 2.38%   |
| Dell XPS 15 7590                         | 1         | 2.38%   |
| Dell Studio 1747                         | 1         | 2.38%   |
| Dell Inspiron MM061                      | 1         | 2.38%   |
| Dell Inspiron 5566                       | 1         | 2.38%   |
| Dell Inspiron 3180                       | 1         | 2.38%   |
| ASUS ZenBook UX431FA                     | 1         | 2.38%   |
| ASUS X555LAB                             | 1         | 2.38%   |
| ASUS X550EA                              | 1         | 2.38%   |
| ASUS X200MA                              | 1         | 2.38%   |
| ASUS N10Jc                               | 1         | 2.38%   |
| ASUS E502SA                              | 1         | 2.38%   |
| Acer Aspire ES1-512                      | 1         | 2.38%   |
| Acer Aspire ES1-111M                     | 1         | 2.38%   |
| Acer Aspire E5-553G                      | 1         | 2.38%   |
| Acer Aspire 5920G                        | 1         | 2.38%   |
| Unknown                                  | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 5         | 11.9%   |
| Acer Aspire      | 4         | 9.52%   |
| HP EliteBook     | 3         | 7.14%   |
| Dell Inspiron    | 3         | 7.14%   |
| Synology DS1019+ | 1         | 2.38%   |
| Sony VGN-UX27GN  | 1         | 2.38%   |
| Pegatron Deepcam | 1         | 2.38%   |
| MSI GL72M        | 1         | 2.38%   |
| Lenovo Yoga      | 1         | 2.38%   |
| Lenovo IdeaPad   | 1         | 2.38%   |
| IBM ThinkPad     | 1         | 2.38%   |
| IBM 26446AG      | 1         | 2.38%   |
| IBM 264070A      | 1         | 2.38%   |
| HP ZBook         | 1         | 2.38%   |
| HP ProBook       | 1         | 2.38%   |
| HP Mini          | 1         | 2.38%   |
| HP Laptop        | 1         | 2.38%   |
| HP ENVY          | 1         | 2.38%   |
| HP Compaq        | 1         | 2.38%   |
| Haier U144S      | 1         | 2.38%   |
| Google Samus     | 1         | 2.38%   |
| Gateway MX3631m  | 1         | 2.38%   |
| Dell XPS         | 1         | 2.38%   |
| Dell Studio      | 1         | 2.38%   |
| ASUS ZenBook     | 1         | 2.38%   |
| ASUS X555LAB     | 1         | 2.38%   |
| ASUS X550EA      | 1         | 2.38%   |
| ASUS X200MA      | 1         | 2.38%   |
| ASUS N10Jc       | 1         | 2.38%   |
| ASUS E502SA      | 1         | 2.38%   |
| Unknown          | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 5         | 11.9%   |
| 2018    | 5         | 11.9%   |
| 2014    | 5         | 11.9%   |
| 2017    | 3         | 7.14%   |
| 2010    | 3         | 7.14%   |
| 2006    | 3         | 7.14%   |
| 2021    | 2         | 4.76%   |
| 2016    | 2         | 4.76%   |
| 2012    | 2         | 4.76%   |
| 2011    | 2         | 4.76%   |
| 2009    | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| 2015    | 1         | 2.38%   |
| 2013    | 1         | 2.38%   |
| 2008    | 1         | 2.38%   |
| 2007    | 1         | 2.38%   |
| 2005    | 1         | 2.38%   |
| 1999    | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 42        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 97.62%  |
| Yes  | 1         | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 11        | 25.58%  |
| 4.01-8.0    | 10        | 23.26%  |
| 8.01-16.0   | 5         | 11.63%  |
| 16.01-24.0  | 4         | 9.3%    |
| 1.01-2.0    | 4         | 9.3%    |
| 0.51-1.0    | 3         | 6.98%   |
| 2.01-3.0    | 2         | 4.65%   |
| 0.01-0.5    | 2         | 4.65%   |
| 32.01-64.0  | 1         | 2.33%   |
| 64.01-256.0 | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 12        | 27.27%  |
| 1.01-2.0  | 8         | 18.18%  |
| 0.51-1.0  | 8         | 18.18%  |
| 2.01-3.0  | 5         | 11.36%  |
| 4.01-8.0  | 4         | 9.09%   |
| 3.01-4.0  | 3         | 6.82%   |
| 0         | 2         | 4.55%   |
| 8.01-16.0 | 1         | 2.27%   |
| Unknown   | 1         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 74.42%  |
| 2      | 9         | 20.93%  |
| 7      | 1         | 2.33%   |
| 0      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 69.05%  |
| Yes       | 13        | 30.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 80.95%  |
| No        | 8         | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 92.86%  |
| No        | 3         | 7.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 59.52%  |
| No        | 17        | 40.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 28.57%  |
| Canada       | 5         | 11.9%   |
| UK           | 4         | 9.52%   |
| Russia       | 4         | 9.52%   |
| Germany      | 2         | 4.76%   |
| Brazil       | 2         | 4.76%   |
| Venezuela    | 1         | 2.38%   |
| Spain        | 1         | 2.38%   |
| South Africa | 1         | 2.38%   |
| Slovakia     | 1         | 2.38%   |
| Portugal     | 1         | 2.38%   |
| Poland       | 1         | 2.38%   |
| Mexico       | 1         | 2.38%   |
| Italy        | 1         | 2.38%   |
| Guatemala    | 1         | 2.38%   |
| France       | 1         | 2.38%   |
| Egypt        | 1         | 2.38%   |
| Czechia      | 1         | 2.38%   |
| Australia    | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| St Petersburg    | 3         | 7.14%   |
| Stratford        | 2         | 4.76%   |
| Fulham           | 2         | 4.76%   |
| Vernon           | 1         | 2.38%   |
| Tymovskoye       | 1         | 2.38%   |
| Tampa            | 1         | 2.38%   |
| Sydney           | 1         | 2.38%   |
| Stewartstown     | 1         | 2.38%   |
| Springfield      | 1         | 2.38%   |
| Sisteron         | 1         | 2.38%   |
| Semily           | 1         | 2.38%   |
| Sao Paulo        | 1         | 2.38%   |
| San Mateo        | 1         | 2.38%   |
| Rzeszów         | 1         | 2.38%   |
| Rostock          | 1         | 2.38%   |
| Purdys           | 1         | 2.38%   |
| Oakville         | 1         | 2.38%   |
| Merrill          | 1         | 2.38%   |
| Mérida          | 1         | 2.38%   |
| Manitowoc        | 1         | 2.38%   |
| Madrid           | 1         | 2.38%   |
| Lindavista Norte | 1         | 2.38%   |
| Lincoln          | 1         | 2.38%   |
| Leipzig          | 1         | 2.38%   |
| Larkspur         | 1         | 2.38%   |
| Johannesburg     | 1         | 2.38%   |
| Hampstead        | 1         | 2.38%   |
| Guatemala City   | 1         | 2.38%   |
| Funchal          | 1         | 2.38%   |
| Franklin         | 1         | 2.38%   |
| Dallas           | 1         | 2.38%   |
| Chapel Hill      | 1         | 2.38%   |
| Cairo            | 1         | 2.38%   |
| Brockport        | 1         | 2.38%   |
| Bratislava       | 1         | 2.38%   |
| Boucherville     | 1         | 2.38%   |
| Bolzano          | 1         | 2.38%   |
| Belém           | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 13.73%  |
| Samsung Electronics | 6         | 7      | 11.76%  |
| Unknown             | 4         | 5      | 7.84%   |
| Seagate             | 4         | 13     | 7.84%   |
| Kingston            | 4         | 5      | 7.84%   |
| WDC                 | 3         | 4      | 5.88%   |
| Toshiba             | 3         | 4      | 5.88%   |
| HGST                | 3         | 3      | 5.88%   |
| Intel               | 2         | 4      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| SPCC                | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| SanDisk             | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| KC600               | 1         | 1      | 1.96%   |
| JMicron Technology  | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| IBM                 | 1         | 1      | 1.96%   |
| EMTEC               | 1         | 1      | 1.96%   |
| Dell                | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| AMD                 | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                    | 2         | 3.77%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 3.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 1.89%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 1.89%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 1.89%   |
| Unknown SD32G  32GB                       | 1         | 1.89%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 1.89%   |
| Toshiba NVMe SSD Drive 256GB              | 1         | 1.89%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.89%   |
| Toshiba MK4009GAL 40GB                    | 1         | 1.89%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.89%   |
| SPCC Solid State Disk 256GB               | 1         | 1.89%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 1.89%   |
| Seagate ST98823A 80GB                     | 1         | 1.89%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 1.89%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.89%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1.89%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 1.89%   |
| Samsung Portable SSD T5 1TB               | 1         | 1.89%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.89%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 1.89%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 1.89%   |
| Samsung HM160HI 160GB                     | 1         | 1.89%   |
| LITEON CV1-8B128-HP 128GB SSD             | 1         | 1.89%   |
| Kingston SUV500MS480G 480GB SSD           | 1         | 1.89%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 1.89%   |
| Kingston RBU-SUS151S364GD 64GB SSD        | 1         | 1.89%   |
| Kingston KC600 128GB SSD                  | 1         | 1.89%   |
| KC600 SSD 128GB                           | 1         | 1.89%   |
| JMicron Generic 2TB                       | 1         | 1.89%   |
| Intenso SSD 128GB                         | 1         | 1.89%   |
| Intel SSDPEKKA256G7 256GB                 | 1         | 1.89%   |
| Intel HBRPEKNX0101AHO 16GB                | 1         | 1.89%   |
| Intel HBRPEKNX0101AH 256GB                | 1         | 1.89%   |
| IBM DARA-212000 12GB                      | 1         | 1.89%   |
| Hitachi HTS725025A9A364 250GB             | 1         | 1.89%   |
| Hitachi HTS723232L9A360 320GB             | 1         | 1.89%   |
| Hitachi HTS723232A7A364 320GB             | 1         | 1.89%   |
| Hitachi HTS72101 99GB                     | 1         | 1.89%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 1.89%   |
| Hitachi HTS541040G9AT00 40GB              | 1         | 1.89%   |
| Hitachi HTC426040G9AT00 40GB              | 1         | 1.89%   |
| HGST HTS545050A7E380 500GB                | 1         | 1.89%   |
| HGST HTS541010B7E610 1TB                  | 1         | 1.89%   |
| HGST HTS541010A9E680 1TB                  | 1         | 1.89%   |
| EMTEC X150 240GB                          | 1         | 1.89%   |
| Dell WR202KD032G E70290F5 32GB            | 1         | 1.89%   |
| China SSD 120GB                           | 1         | 1.89%   |
| AMD R5M120G8 120GB SSD                    | 1         | 1.89%   |
| A-DATA SU800 128GB SSD                    | 1         | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 36.84%  |
| Seagate             | 4         | 13     | 21.05%  |
| HGST                | 3         | 3      | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 2      | 5.26%   |
| IBM                 | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 5      | 21.05%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Crucial             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| SPCC                | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| LITEON              | 1         | 1      | 5.26%   |
| KC600               | 1         | 1      | 5.26%   |
| Intenso             | 1         | 1      | 5.26%   |
| EMTEC               | 1         | 1      | 5.26%   |
| Dell                | 1         | 1      | 5.26%   |
| China               | 1         | 1      | 5.26%   |
| AMD                 | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 29     | 39.58%  |
| SSD  | 17        | 20     | 35.42%  |
| NVMe | 9         | 15     | 18.75%  |
| MMC  | 3         | 3      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 47     | 70.21%  |
| NVMe | 8         | 14     | 17.02%  |
| SAS  | 3         | 3      | 6.38%   |
| MMC  | 3         | 3      | 6.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 33     | 80.56%  |
| 0.51-1.0   | 5         | 5      | 13.89%  |
| 1.01-2.0   | 1         | 1      | 2.78%   |
| 4.01-10.0  | 1         | 10     | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 25.58%  |
| 1-20           | 8         | 18.6%   |
| 251-500        | 6         | 13.95%  |
| 21-50          | 5         | 11.63%  |
| 501-1000       | 4         | 9.3%    |
| Unknown        | 4         | 9.3%    |
| 1001-2000      | 2         | 4.65%   |
| 51-100         | 2         | 4.65%   |
| More than 3000 | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 28        | 65.12%  |
| 21-50    | 4         | 9.3%    |
| Unknown  | 4         | 9.3%    |
| 101-250  | 3         | 6.98%   |
| 51-100   | 3         | 6.98%   |
| 501-1000 | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK4009GAL 40GB            | 1         | 1      | 12.5%   |
| Seagate ST2000LM015-2E81 2TB      | 1         | 1      | 12.5%   |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 12.5%   |
| Hitachi HTS725025A9A364 250GB     | 1         | 1      | 12.5%   |
| Hitachi HTS723232A7A364 320GB     | 1         | 1      | 12.5%   |
| Hitachi HTS72101 99GB             | 1         | 1      | 12.5%   |
| Hitachi HTC426040G9AT00 40GB      | 1         | 1      | 12.5%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 50%     |
| Toshiba             | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 2      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

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
| HDD  | 8         | 9      | 100%    |

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
| Works    | 26        | 44     | 56.52%  |
| Detected | 12        | 14     | 26.09%  |
| Malfunc  | 8         | 9      | 17.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 69.57%  |
| AMD                          | 6         | 13.04%  |
| Samsung Electronics          | 3         | 6.52%   |
| Toshiba America Info Systems | 1         | 2.17%   |
| SK hynix                     | 1         | 2.17%   |
| SanDisk                      | 1         | 2.17%   |
| Marvell Technology Group     | 1         | 2.17%   |
| ADATA Technology             | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 12.24%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 6.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 6.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 6.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 4.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 4.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 4.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 4.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 4.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 4.08%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 4.08%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.04%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 2.04%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 2.04%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 2.04%   |
| Intel SSD 600P Series                                                            | 1         | 2.04%   |
| Intel Non-Volatile memory controller                                             | 1         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.04%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.04%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 61.7%   |
| NVMe | 8         | 17.02%  |
| IDE  | 8         | 17.02%  |
| RAID | 2         | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 80.95%  |
| AMD    | 7         | 16.67%  |
| ARM    | 1         | 2.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                      | 2         | 4.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 4.76%   |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 4.76%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 2.38%   |
| Intel Pentium M processor 1.60GHz                      | 1         | 2.38%   |
| Intel Pentium M processor 1.50GHz                      | 1         | 2.38%   |
| Intel Pentium III (Coppermine)                         | 1         | 2.38%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 2.38%   |
| Intel Mobile Pentium MMX                               | 1         | 2.38%   |
| Intel Core Solo CPU U1500 @ 1.33GHz                    | 1         | 2.38%   |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 2.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 2.38%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 2.38%   |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 2.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 2.38%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 2.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 2.38%   |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 2.38%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 2.38%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 2.38%   |
| Intel Core i3-5020U CPU @ 2.20GHz                      | 1         | 2.38%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 2.38%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 2.38%   |
| Intel Core 2 Duo CPU P7570 @ 2.26GHz                   | 1         | 2.38%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 2.38%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 2.38%   |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 2.38%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 1         | 2.38%   |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 2.38%   |
| Intel Atom CPU N270 @ 1.60GHz                          | 1         | 2.38%   |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 2.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 2.38%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx          | 1         | 2.38%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1         | 2.38%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G          | 1         | 2.38%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics            | 1         | 2.38%   |
| AMD A4-5000 APU with Radeon HD Graphics                | 1         | 2.38%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G        | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 10        | 23.81%  |
| Intel Celeron     | 5         | 11.9%   |
| Intel Atom        | 4         | 9.52%   |
| Other             | 3         | 7.14%   |
| Intel Core 2 Duo  | 3         | 7.14%   |
| Intel Pentium M   | 2         | 4.76%   |
| Intel Core i7     | 2         | 4.76%   |
| AMD A4            | 2         | 4.76%   |
| Intel Xeon        | 1         | 2.38%   |
| Intel Pentium III | 1         | 2.38%   |
| Intel Pentium     | 1         | 2.38%   |
| Intel Core Solo   | 1         | 2.38%   |
| Intel Core i9     | 1         | 2.38%   |
| Intel Core i3     | 1         | 2.38%   |
| Intel Core 2      | 1         | 2.38%   |
| AMD Ryzen 7       | 1         | 2.38%   |
| AMD Ryzen 5       | 1         | 2.38%   |
| AMD A6            | 1         | 2.38%   |
| AMD A10           | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 47.62%  |
| 4      | 10        | 23.81%  |
| 1      | 8         | 19.05%  |
| 8      | 2         | 4.76%   |
| 6      | 1         | 2.38%   |
| 3      | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 54.76%  |
| 2      | 19        | 45.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 51.16%  |
| Unknown        | 18        | 41.86%  |
| 32-bit         | 3         | 6.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 53.49%  |
| 0x30678    | 3         | 6.98%   |
| 0x206a7    | 2         | 4.65%   |
| 0x106ca    | 2         | 4.65%   |
| 0x06006704 | 2         | 4.65%   |
| 0x906ea    | 1         | 2.33%   |
| 0x806eb    | 1         | 2.33%   |
| 0x706e5    | 1         | 2.33%   |
| 0x683      | 1         | 2.33%   |
| 0x506c9    | 1         | 2.33%   |
| 0x406c4    | 1         | 2.33%   |
| 0x306d4    | 1         | 2.33%   |
| 0x306a9    | 1         | 2.33%   |
| 0x106e5    | 1         | 2.33%   |
| 0x1067a    | 1         | 2.33%   |
| 0x0810100b | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 14.29%  |
| Silvermont  | 4         | 9.52%   |
| P6          | 4         | 9.52%   |
| Penryn      | 3         | 7.14%   |
| Goldmont    | 3         | 7.14%   |
| Excavator   | 3         | 7.14%   |
| Bonnell     | 3         | 7.14%   |
| SandyBridge | 2         | 4.76%   |
| Broadwell   | 2         | 4.76%   |
| Unknown     | 2         | 4.76%   |
| Zen 2       | 1         | 2.38%   |
| Zen         | 1         | 2.38%   |
| Westmere    | 1         | 2.38%   |
| Skylake     | 1         | 2.38%   |
| Puma        | 1         | 2.38%   |
| Nehalem     | 1         | 2.38%   |
| Jaguar      | 1         | 2.38%   |
| IvyBridge   | 1         | 2.38%   |
| IceLake     | 1         | 2.38%   |
| Core        | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 28        | 62.22%  |
| AMD      | 11        | 24.44%  |
| Nvidia   | 4         | 8.89%   |
| Neomagic | 2         | 4.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 3         | 6.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 6.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 4.17%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 4.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 2.08%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 2.08%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 2.08%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 2.08%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.08%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.08%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.08%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 2.08%   |
| Intel HD Graphics 630                                                                    | 1         | 2.08%   |
| Intel HD Graphics 620                                                                    | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.08%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.08%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.08%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 2.08%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 2.08%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 2.08%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 2.08%   |
| AMD Renoir                                                                               | 1         | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.08%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 2.08%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 50%     |
| 1 x AMD        | 9         | 21.43%  |
| 2 x Intel      | 3         | 7.14%   |
| Intel + Nvidia | 3         | 7.14%   |
| 1 x Neomagic   | 2         | 4.76%   |
| Other          | 1         | 2.38%   |
| 2 x AMD        | 1         | 2.38%   |
| 1 x Nvidia     | 1         | 2.38%   |
| Intel + AMD    | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 38        | 88.37%  |
| Unknown     | 4         | 9.3%    |
| Proprietary | 1         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 88.1%   |
| 0.01-0.5   | 3         | 7.14%   |
| 1.01-2.0   | 1         | 2.38%   |
| 0.51-1.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 20%     |
| LG Display              | 6         | 15%     |
| Chimei Innolux          | 5         | 12.5%   |
| BOE                     | 4         | 10%     |
| Samsung Electronics     | 3         | 7.5%    |
| LG Philips              | 2         | 5%      |
| Chi Mei Optoelectronics | 2         | 5%      |
| ONN                     | 1         | 2.5%    |
| Lenovo                  | 1         | 2.5%    |
| InfoVision              | 1         | 2.5%    |
| HannStar                | 1         | 2.5%    |
| Goldstar                | 1         | 2.5%    |
| Envision                | 1         | 2.5%    |
| DENON                   | 1         | 2.5%    |
| CSO                     | 1         | 2.5%    |
| CPT                     | 1         | 2.5%    |
| Acer                    | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 2.5%    |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 2.5%    |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 2.5%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.5%    |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 2.5%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 2.5%    |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 2.5%    |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 2.5%    |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 2.5%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 2.5%    |
| Goldstar LG ULTRAWIDE GSM5A2A 2560x1080 670x280mm 28.6-inch              | 1         | 2.5%    |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 2.5%    |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 2.5%    |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 2.5%    |
| CPT LCD Monitor CPT04E2 1024x600 222x130mm 10.1-inch                     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 2.5%    |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 2.5%    |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 2.5%    |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.5%    |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch           | 1         | 2.5%    |
| Acer V173 ACR002F 1280x1024 338x270mm 17.0-inch                          | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 16        | 40%     |
| 1920x1080 (FHD)   | 6         | 15%     |
| 1280x800 (WXGA)   | 3         | 7.5%    |
| 1024x600          | 3         | 7.5%    |
| 3840x2160 (4K)    | 2         | 5%      |
| 1600x900 (HD+)    | 2         | 5%      |
| 2880x1800         | 1         | 2.5%    |
| 2560x1700         | 1         | 2.5%    |
| 2560x1440 (QHD)   | 1         | 2.5%    |
| 2560x1080         | 1         | 2.5%    |
| 1920x1200 (WUXGA) | 1         | 2.5%    |
| 1360x768          | 1         | 2.5%    |
| 1280x768          | 1         | 2.5%    |
| 1280x1024 (SXGA)  | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 30%     |
| 13     | 7         | 17.5%   |
| 14     | 5         | 12.5%   |
| 17     | 4         | 10%     |
| 11     | 3         | 7.5%    |
| 10     | 3         | 7.5%    |
| 31     | 2         | 5%      |
| 12     | 2         | 5%      |
| 32     | 1         | 2.5%    |
| 29     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 57.5%   |
| 201-300     | 10        | 25%     |
| 601-700     | 3         | 7.5%    |
| 351-400     | 3         | 7.5%    |
| 701-800     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 78.95%  |
| 16/10 | 5         | 13.16%  |
| 5/4   | 1         | 2.63%   |
| 3/2   | 1         | 2.63%   |
| 21/9  | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 30%     |
| 81-90          | 10        | 25%     |
| 71-80          | 3         | 7.5%    |
| 51-60          | 3         | 7.5%    |
| 351-500        | 3         | 7.5%    |
| 41-50          | 3         | 7.5%    |
| 121-130        | 2         | 5%      |
| 61-70          | 1         | 2.5%    |
| 301-350        | 1         | 2.5%    |
| 141-150        | 1         | 2.5%    |
| 131-140        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 16        | 41.03%  |
| 121-160       | 12        | 30.77%  |
| 51-100        | 6         | 15.38%  |
| More than 240 | 2         | 5.13%   |
| 161-240       | 2         | 5.13%   |
| 1-50          | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 78.57%  |
| 2     | 5         | 11.9%   |
| 0     | 4         | 9.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 24        | 33.8%   |
| Intel                           | 19        | 26.76%  |
| Qualcomm Atheros                | 14        | 19.72%  |
| Broadcom                        | 6         | 8.45%   |
| Marvell Technology Group        | 3         | 4.23%   |
| Qualcomm Atheros Communications | 1         | 1.41%   |
| Qualcomm                        | 1         | 1.41%   |
| LSI                             | 1         | 1.41%   |
| Dresden Elektronik              | 1         | 1.41%   |
| Broadcom Limited                | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 13.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 7.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 7.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.25%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.25%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.25%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.25%   |
| Qualcomm Android                                                               | 1         | 1.25%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.25%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 1.25%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.25%   |
| LSI WinModem 56k                                                               | 1         | 1.25%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.25%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.25%   |
| Intel Wireless 8260                                                            | 1         | 1.25%   |
| Intel Wireless 7260                                                            | 1         | 1.25%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.25%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.25%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 1         | 1.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller              | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.25%   |
| Intel 82541GI Gigabit Ethernet Controller                                      | 1         | 1.25%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                  | 1         | 1.25%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                          | 1         | 1.25%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.25%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 1.25%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 1.25%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 42.5%   |
| Qualcomm Atheros                | 13        | 32.5%   |
| Broadcom                        | 4         | 10%     |
| Realtek Semiconductor           | 3         | 7.5%    |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| Marvell Technology Group        | 1         | 2.5%    |
| Broadcom Limited                | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 15%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 5%      |
| Intel Wi-Fi 6 AX200                                                            | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 5%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 2.5%    |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.5%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 2.5%    |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.5%    |
| Intel Wireless-AC 9260                                                         | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.5%    |
| Intel Wireless 8260                                                            | 1         | 2.5%    |
| Intel Wireless 7260                                                            | 1         | 2.5%    |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 2.5%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.5%    |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.5%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 58.33%  |
| Intel                    | 8         | 22.22%  |
| Broadcom                 | 3         | 8.33%   |
| Marvell Technology Group | 2         | 5.56%   |
| Qualcomm Atheros         | 1         | 2.78%   |
| Qualcomm                 | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 30.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 16.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.78%   |
| Qualcomm Android                                                  | 1         | 2.78%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.78%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 2.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.78%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.78%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express             | 1         | 2.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.78%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 51.32%  |
| Ethernet | 33        | 43.42%  |
| Modem    | 4         | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 69.77%  |
| Ethernet | 13        | 30.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 71.43%  |
| 1     | 9         | 21.43%  |
| 0     | 3         | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 83.72%  |
| Yes  | 7         | 16.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 36%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| Lite-On Technology              | 3         | 12%     |
| IMC Networks                    | 2         | 8%      |
| Broadcom                        | 2         | 8%      |
| Realtek Semiconductor           | 1         | 4%      |
| Marvell Semiconductor           | 1         | 4%      |
| Hewlett-Packard                 | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| ASUSTek Computer                | 1         | 4%      |
| Alps Electric                   | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 3         | 12%     |
| Intel Bluetooth wireless interface                  | 3         | 12%     |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 8%      |
| Intel AX200 Bluetooth                               | 2         | 8%      |
| Realtek Bluetooth Radio                             | 1         | 4%      |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 4%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4%      |
| IMC Networks Bluetooth Device                       | 1         | 4%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 4%      |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4%      |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 4%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 4%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 4%      |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 4%      |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 31        | 72.09%  |
| AMD                       | 9         | 20.93%  |
| Sennheiser Communications | 1         | 2.33%   |
| Realtek Semiconductor     | 1         | 2.33%   |
| Cirrus Logic              | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 9.8%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 5.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 5.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 5.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.92%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 3.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.92%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.92%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 3.92%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.96%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.96%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.96%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.96%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.96%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 22.86%  |
| Unknown             | 7         | 20%     |
| SK hynix            | 7         | 20%     |
| Elpida              | 4         | 11.43%  |
| Micron Technology   | 3         | 8.57%   |
| Crucial             | 2         | 5.71%   |
| A-DATA Technology   | 2         | 5.71%   |
| Unknown (ABCD)      | 1         | 2.86%   |
| Kingston            | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 5.41%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 5.41%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s         | 2         | 5.41%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 2.7%    |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 2.7%    |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 2.7%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 2.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.7%    |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 2.7%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.7%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.7%    |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s        | 1         | 2.7%    |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s           | 1         | 2.7%    |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s        | 1         | 2.7%    |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 2.7%    |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.7%    |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| Crucial RAM CT102464BF186D.M16 8GB SODIMM DDR3 1867MT/s          | 1         | 2.7%    |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                       | 1         | 2.7%    |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 14        | 42.42%  |
| DDR4   | 8         | 24.24%  |
| LPDDR3 | 3         | 9.09%   |
| DDR    | 3         | 9.09%   |
| LPDDR4 | 2         | 6.06%   |
| SDRAM  | 1         | 3.03%   |
| DRAM   | 1         | 3.03%   |
| DDR2   | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 87.88%  |
| Row Of Chips | 3         | 9.09%   |
| DIMM         | 1         | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 13        | 36.11%  |
| 8192 | 11        | 30.56%  |
| 2048 | 5         | 13.89%  |
| 1024 | 3         | 8.33%   |
| 512  | 2         | 5.56%   |
| 256  | 1         | 2.78%   |
| 128  | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 18.18%  |
| Unknown | 5         | 15.15%  |
| 2400    | 4         | 12.12%  |
| 2133    | 4         | 12.12%  |
| 1334    | 4         | 12.12%  |
| 2667    | 2         | 6.06%   |
| 1333    | 2         | 6.06%   |
| 3200    | 1         | 3.03%   |
| 1867    | 1         | 3.03%   |
| 1400    | 1         | 3.03%   |
| 1200    | 1         | 3.03%   |
| 1067    | 1         | 3.03%   |
| 533     | 1         | 3.03%   |

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
| Chicony Electronics                    | 11        | 33.33%  |
| Realtek Semiconductor                  | 5         | 15.15%  |
| Suyin                                  | 2         | 6.06%   |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Microdia                               | 2         | 6.06%   |
| IMC Networks                           | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.06%   |
| Syntek                                 | 1         | 3.03%   |
| Silicon Motion                         | 1         | 3.03%   |
| Ricoh                                  | 1         | 3.03%   |
| Quanta                                 | 1         | 3.03%   |
| Lenovo                                 | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |
| Acer                                   | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 6.06%   |
| Chicony Integrated Camera                           | 2         | 6.06%   |
| Chicony HD WebCam                                   | 2         | 6.06%   |
| Syntek EasyCamera                                   | 1         | 3.03%   |
| Suyin HP Truevision HD                              | 1         | 3.03%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 3.03%   |
| Sunplus HP Universal Camera                         | 1         | 3.03%   |
| Sunplus HD WebCam                                   | 1         | 3.03%   |
| Silicon Motion NCM-G102                             | 1         | 3.03%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 3.03%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 3.03%   |
| Realtek USB Camera                                  | 1         | 3.03%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 3.03%   |
| Quanta HP TrueVision HD Camera                      | 1         | 3.03%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.03%   |
| Lenovo Integrated Webcam                            | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 3.03%   |
| IMC Networks Integrated Camera                      | 1         | 3.03%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.03%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.03%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 3.03%   |
| Chicony HP HD Camera                                | 1         | 3.03%   |
| Chicony CNF8243 Webcam                              | 1         | 3.03%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 3.03%   |
| Acer BisonCam, NB Pro                               | 1         | 3.03%   |

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
| 0     | 23        | 52.27%  |
| 1     | 13        | 29.55%  |
| 2     | 7         | 15.91%  |
| 4     | 1         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 23.33%  |
| Graphics card            | 6         | 20%     |
| Modem                    | 4         | 13.33%  |
| Net/wireless             | 2         | 6.67%   |
| Chipcard                 | 2         | 6.67%   |
| Camera                   | 2         | 6.67%   |
| Unclassified device      | 1         | 3.33%   |
| Storage                  | 1         | 3.33%   |
| Sound                    | 1         | 3.33%   |
| Network                  | 1         | 3.33%   |
| Multimedia controller    | 1         | 3.33%   |
| Communication controller | 1         | 3.33%   |
| Bluetooth                | 1         | 3.33%   |


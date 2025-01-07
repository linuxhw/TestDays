Cyber Infra - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Cyber Infra.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Cyber_Infra/Desktop/README.md) and [notebooks](/Dist/Cyber_Infra/Notebook/README.md).

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

Total: 103

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | H12SSW-NT               | Server      | [4235f71014](https://linux-hardware.org/?probe=4235f71014) | Nov 29, 2024 |
| Supermicro    | X11SPM-F                | Server      | [a121b2a2e1](https://linux-hardware.org/?probe=a121b2a2e1) | Nov 25, 2024 |
| Supermicro    | H11SSL-C                | Server      | [ac82baedee](https://linux-hardware.org/?probe=ac82baedee) | Nov 21, 2024 |
| Supermicro    | H11SSL-C                | Server      | [b7c2ebcbef](https://linux-hardware.org/?probe=b7c2ebcbef) | Nov 20, 2024 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [3491bad189](https://linux-hardware.org/?probe=3491bad189) | Nov 04, 2024 |
| HP            | ProLiant BL460c Gen8    | Server      | [03ce72541e](https://linux-hardware.org/?probe=03ce72541e) | Oct 24, 2024 |
| HP            | ProLiant BL460c Gen8    | Server      | [2f48ddf276](https://linux-hardware.org/?probe=2f48ddf276) | Oct 24, 2024 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [d810cddf96](https://linux-hardware.org/?probe=d810cddf96) | Oct 15, 2024 |
| 3Logic Gro... | TUNDRA                  | Server      | [731c46b566](https://linux-hardware.org/?probe=731c46b566) | Aug 20, 2024 |
| Supermicro    | X11SPM-F                | Server      | [7463e5e2f9](https://linux-hardware.org/?probe=7463e5e2f9) | Jul 06, 2024 |
| ASRockRack    | EP2C621D16-4LP          | Server      | [5af2c77246](https://linux-hardware.org/?probe=5af2c77246) | Jul 05, 2024 |
| Supermicro    | X10DRL-i                | Server      | [ff8c7320cc](https://linux-hardware.org/?probe=ff8c7320cc) | Jun 24, 2024 |
| Supermicro    | X11SPM-F                | Server      | [b8a7becbee](https://linux-hardware.org/?probe=b8a7becbee) | Jun 20, 2024 |
| Supermicro    | X11DDW-L                | Server      | [a466d61b44](https://linux-hardware.org/?probe=a466d61b44) | Apr 30, 2024 |
| Supermicro    | X11DDW-L                | Server      | [35b92be9f4](https://linux-hardware.org/?probe=35b92be9f4) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [91829f13b3](https://linux-hardware.org/?probe=91829f13b3) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [26cb0d914d](https://linux-hardware.org/?probe=26cb0d914d) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [86ec1c52cf](https://linux-hardware.org/?probe=86ec1c52cf) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [02acab99ca](https://linux-hardware.org/?probe=02acab99ca) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [2743b737c5](https://linux-hardware.org/?probe=2743b737c5) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [6f4331e541](https://linux-hardware.org/?probe=6f4331e541) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [6dfa7a39f0](https://linux-hardware.org/?probe=6dfa7a39f0) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [c15ca5d532](https://linux-hardware.org/?probe=c15ca5d532) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [51b1b9f5d9](https://linux-hardware.org/?probe=51b1b9f5d9) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [4c17dc4de0](https://linux-hardware.org/?probe=4c17dc4de0) | Apr 29, 2024 |
| Supermicro    | X11DDW-L                | Server      | [5bb24704dd](https://linux-hardware.org/?probe=5bb24704dd) | Apr 29, 2024 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [42f99a1064](https://linux-hardware.org/?probe=42f99a1064) | Mar 20, 2024 |
| Supermicro    | H12SSW-NT               | Server      | [dcd6765539](https://linux-hardware.org/?probe=dcd6765539) | Mar 20, 2024 |
| Intel         | WHITLEY                 | Server      | [40863a6963](https://linux-hardware.org/?probe=40863a6963) | Mar 20, 2024 |
| Intel         | WHITLEY                 | Server      | [3801d427d7](https://linux-hardware.org/?probe=3801d427d7) | Nov 08, 2023 |
| Intel         | WHITLEY                 | Server      | [1d2875a6fc](https://linux-hardware.org/?probe=1d2875a6fc) | Nov 08, 2023 |
| Intel         | WHITLEY                 | Server      | [b58d16125d](https://linux-hardware.org/?probe=b58d16125d) | Nov 08, 2023 |
| HPE           | ProLiant DL360 Gen10    | Server      | [b8a4774f2c](https://linux-hardware.org/?probe=b8a4774f2c) | Oct 28, 2023 |
| HPE           | ProLiant DL360 Gen10    | Server      | [07d658316a](https://linux-hardware.org/?probe=07d658316a) | Oct 28, 2023 |
| HPE           | ProLiant DL360 Gen10    | Server      | [bb565b917d](https://linux-hardware.org/?probe=bb565b917d) | Oct 28, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [215f8e1d20](https://linux-hardware.org/?probe=215f8e1d20) | Oct 21, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [704c191431](https://linux-hardware.org/?probe=704c191431) | Oct 21, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [3c87db71c6](https://linux-hardware.org/?probe=3c87db71c6) | Oct 21, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [98afec32b2](https://linux-hardware.org/?probe=98afec32b2) | Oct 12, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [d19f06b547](https://linux-hardware.org/?probe=d19f06b547) | Oct 12, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [27dcd3ddcc](https://linux-hardware.org/?probe=27dcd3ddcc) | Oct 12, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [e18aaeccc6](https://linux-hardware.org/?probe=e18aaeccc6) | Oct 12, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [10beb03b80](https://linux-hardware.org/?probe=10beb03b80) | Oct 12, 2023 |
| Dell          | 04V528 A02              | Server      | [96ef3c9fdd](https://linux-hardware.org/?probe=96ef3c9fdd) | Sep 22, 2023 |
| Dell          | 0JMK61 A00              | Server      | [e0bd072160](https://linux-hardware.org/?probe=e0bd072160) | Sep 21, 2023 |
| Dell          | 0RGP26 A00              | Server      | [d35a82a9ec](https://linux-hardware.org/?probe=d35a82a9ec) | Sep 21, 2023 |
| Dell          | 06DKY5 A03              | Server      | [a86e860c3d](https://linux-hardware.org/?probe=a86e860c3d) | Sep 21, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [29cabf2b17](https://linux-hardware.org/?probe=29cabf2b17) | Jul 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [471a0154cb](https://linux-hardware.org/?probe=471a0154cb) | Jul 09, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [7f1e769c28](https://linux-hardware.org/?probe=7f1e769c28) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [6e33251220](https://linux-hardware.org/?probe=6e33251220) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [da1eee177b](https://linux-hardware.org/?probe=da1eee177b) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [f9074e4a79](https://linux-hardware.org/?probe=f9074e4a79) | Jul 05, 2023 |
| ASUSTek       | PRIME Z270-A            | Desktop     | [e2531ea6c8](https://linux-hardware.org/?probe=e2531ea6c8) | Jun 16, 2023 |
| Supermicro    | X11DDW-NT               | Server      | [6e0ca764b5](https://linux-hardware.org/?probe=6e0ca764b5) | Jun 14, 2023 |
| Intel         | M50CYP2SBSTD K42381-351 | Server      | [b1b7037d4f](https://linux-hardware.org/?probe=b1b7037d4f) | Jun 14, 2023 |
| Lenovo        | 7X06CTO1WW              | Server      | [dc3ea6dbb8](https://linux-hardware.org/?probe=dc3ea6dbb8) | Jun 14, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+   | Server      | [b4eb1cdd06](https://linux-hardware.org/?probe=b4eb1cdd06) | Jun 07, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [5950749033](https://linux-hardware.org/?probe=5950749033) | Jun 07, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [f8a6482d0e](https://linux-hardware.org/?probe=f8a6482d0e) | May 29, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [18b2bf9ff4](https://linux-hardware.org/?probe=18b2bf9ff4) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [844c562cb6](https://linux-hardware.org/?probe=844c562cb6) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [a7057f367a](https://linux-hardware.org/?probe=a7057f367a) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [0ce29ba75c](https://linux-hardware.org/?probe=0ce29ba75c) | Apr 05, 2023 |
| Supermicro    | X10DRL-i                | Server      | [5e92e7fe1e](https://linux-hardware.org/?probe=5e92e7fe1e) | Apr 05, 2023 |
| Supermicro    | X10SRi-FB               | Server      | [16a0245a41](https://linux-hardware.org/?probe=16a0245a41) | Apr 05, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+   | Server      | [c4b4851a88](https://linux-hardware.org/?probe=c4b4851a88) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [97e6e94ed2](https://linux-hardware.org/?probe=97e6e94ed2) | Apr 04, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [3e3cb25241](https://linux-hardware.org/?probe=3e3cb25241) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [19fddb0a01](https://linux-hardware.org/?probe=19fddb0a01) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [80e5cfeea5](https://linux-hardware.org/?probe=80e5cfeea5) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [83ff998a9a](https://linux-hardware.org/?probe=83ff998a9a) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [61af44de6d](https://linux-hardware.org/?probe=61af44de6d) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [dd8597fd65](https://linux-hardware.org/?probe=dd8597fd65) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [090720bc72](https://linux-hardware.org/?probe=090720bc72) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [8b83576100](https://linux-hardware.org/?probe=8b83576100) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [c33e8fab03](https://linux-hardware.org/?probe=c33e8fab03) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [2f3379adb9](https://linux-hardware.org/?probe=2f3379adb9) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [efc03f8d68](https://linux-hardware.org/?probe=efc03f8d68) | Feb 27, 2023 |
| Supermicro    | X12DAi-N6               | Server      | [814fc144ef](https://linux-hardware.org/?probe=814fc144ef) | Feb 03, 2023 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [bdfa203c78](https://linux-hardware.org/?probe=bdfa203c78) | Jan 16, 2023 |
| Supermicro    | X11SSM-F                | Server      | [b0100c59bb](https://linux-hardware.org/?probe=b0100c59bb) | Dec 12, 2022 |
| Supermicro    | X11SSL-F                | Server      | [7aa0eb0936](https://linux-hardware.org/?probe=7aa0eb0936) | Dec 12, 2022 |
| Supermicro    | X11SSL-F                | Server      | [1a5e57e9ef](https://linux-hardware.org/?probe=1a5e57e9ef) | Oct 31, 2022 |
| Supermicro    | X11SSM-F                | Server      | [c54a576ec0](https://linux-hardware.org/?probe=c54a576ec0) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                | Server      | [c13d2d5610](https://linux-hardware.org/?probe=c13d2d5610) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                | Server      | [2de30f0154](https://linux-hardware.org/?probe=2de30f0154) | Aug 30, 2022 |
| Supermicro    | X11SSL-F                | Server      | [3f8bec5c1b](https://linux-hardware.org/?probe=3f8bec5c1b) | Aug 30, 2022 |
| Supermicro    | X11SSM-F                | Server      | [f715802815](https://linux-hardware.org/?probe=f715802815) | Aug 30, 2022 |
| Supermicro    | X10DRL-i                | Server      | [5281defed3](https://linux-hardware.org/?probe=5281defed3) | Aug 15, 2022 |
| Supermicro    | X10DRL-i                | Server      | [88a4a3d13f](https://linux-hardware.org/?probe=88a4a3d13f) | Aug 04, 2022 |
| Supermicro    | X10DRL-i                | Server      | [9b4576c901](https://linux-hardware.org/?probe=9b4576c901) | Aug 03, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [60ec07883b](https://linux-hardware.org/?probe=60ec07883b) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [912e712657](https://linux-hardware.org/?probe=912e712657) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [3229b1f14c](https://linux-hardware.org/?probe=3229b1f14c) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [ad5b15b222](https://linux-hardware.org/?probe=ad5b15b222) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [6539922005](https://linux-hardware.org/?probe=6539922005) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [0c77bbd30d](https://linux-hardware.org/?probe=0c77bbd30d) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [85a5b4c02f](https://linux-hardware.org/?probe=85a5b4c02f) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [d9f3fb8d37](https://linux-hardware.org/?probe=d9f3fb8d37) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [fdf91b6130](https://linux-hardware.org/?probe=fdf91b6130) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [9c97cfa2bc](https://linux-hardware.org/?probe=9c97cfa2bc) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [6f63fd533c](https://linux-hardware.org/?probe=6f63fd533c) | May 13, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Cyber Infra 5.0.1 | 52        | 63.41%  |
| Cyber Infra 5.5.0 | 21        | 25.61%  |
| Cyber Infra 6.0.2 | 3         | 3.66%   |
| Cyber Infra 6.0.1 | 2         | 2.44%   |
| Cyber Infra 6.0.0 | 2         | 2.44%   |
| Cyber Infra 6.5.0 | 1         | 1.22%   |
| Cyber Infra 4.0.1 | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Cyber Infra | 77        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 3.10.0-1160.41.1.vz7.183.5    | 52        | 62.65%  |
| 3.10.0-1160.105.1.aip7.214.3  | 26        | 31.33%  |
| 3.10.0-1160.90.1.aip7.200.7.1 | 3         | 3.61%   |
| 3.10.0-1160.114.2.aip7.222.1  | 1         | 1.2%    |
| 3.10.0-1127.8.2.vz7.158.8     | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10.0  | 77        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 77        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 77        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 76        | 93.83%  |
| ru_RU | 5         | 6.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 56.96%  |
| BIOS | 34        | 43.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 77        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 77        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 93.67%  |
| Yes       | 5         | 6.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Supermicro       | 48        | 62.34%  |
| Unknown          | 8         | 10.39%  |
| Intel            | 4         | 5.19%   |
| Delta Computers  | 4         | 5.19%   |
| Dell             | 4         | 5.19%   |
| HPE              | 3         | 3.9%    |
| Hewlett-Packard  | 2         | 2.6%    |
| Lenovo           | 1         | 1.3%    |
| ASUSTek Computer | 1         | 1.3%    |
| ASRockRack       | 1         | 1.3%    |
| 3Logic Group     | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Supermicro Super Server                 | 13        | 16.88%  |
| Supermicro SYS-1029P-WTR                | 12        | 15.58%  |
| Supermicro SBI-6119P-T3N                | 10        | 12.99%  |
| Supermicro AS -1014S-WTRT               | 10        | 12.99%  |
| Unknown                                 | 8         | 10.39%  |
| Delta Computers DSS-C621LTG             | 4         | 5.19%   |
| Intel WHITLEY                           | 3         | 3.9%    |
| HPE ProLiant DL360 Gen10                | 3         | 3.9%    |
| HP ProLiant BL460c Gen8                 | 2         | 2.6%    |
| Supermicro X9DRi-LN4+/X9DR3-LN4+        | 1         | 1.3%    |
| Supermicro X12DAi-N6                    | 1         | 1.3%    |
| Supermicro SYS-6029P-WTRT               | 1         | 1.3%    |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 1.3%    |
| Intel M50CYP2SBSTD                      | 1         | 1.3%    |
| Dell XC640-10 CORE                      | 1         | 1.3%    |
| Dell PowerEdge R750                     | 1         | 1.3%    |
| Dell PowerEdge R740                     | 1         | 1.3%    |
| Dell PowerEdge R640                     | 1         | 1.3%    |
| ASUS PRIME Z270-A                       | 1         | 1.3%    |
| ASRockRack EP2C621D16-4LP               | 1         | 1.3%    |
| 3Logic Group Server Graviton            | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Supermicro Super            | 13        | 16.88%  |
| Supermicro SYS-1029P-WTR    | 12        | 15.58%  |
| Supermicro SBI-6119P-T3N    | 10        | 12.99%  |
| Supermicro AS               | 10        | 12.99%  |
| Unknown                     | 8         | 10.39%  |
| Delta Computers DSS-C621LTG | 4         | 5.19%   |
| Intel WHITLEY               | 3         | 3.9%    |
| HPE ProLiant                | 3         | 3.9%    |
| Dell PowerEdge              | 3         | 3.9%    |
| HP ProLiant                 | 2         | 2.6%    |
| Supermicro X9DRi-LN4+       | 1         | 1.3%    |
| Supermicro X12DAi-N6        | 1         | 1.3%    |
| Supermicro SYS-6029P-WTRT   | 1         | 1.3%    |
| Lenovo ThinkSystem          | 1         | 1.3%    |
| Intel M50CYP2SBSTD          | 1         | 1.3%    |
| Dell XC640-10               | 1         | 1.3%    |
| ASUS PRIME                  | 1         | 1.3%    |
| ASRockRack EP2C621D16-4LP   | 1         | 1.3%    |
| 3Logic Group Server         | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 24        | 31.17%  |
| 2022 | 15        | 19.48%  |
| 2019 | 14        | 18.18%  |
| 2015 | 9         | 11.69%  |
| 2018 | 7         | 9.09%   |
| 2023 | 4         | 5.19%   |
| 2021 | 2         | 2.6%    |
| 2024 | 1         | 1.3%    |
| 2016 | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Server  | 76        | 98.7%   |
| Desktop | 1         | 1.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 77        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 38        | 48.1%   |
| More than 256.0 | 35        | 44.3%   |
| 32.01-64.0      | 4         | 5.06%   |
| 16.01-24.0      | 2         | 2.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 25        | 27.78%  |
| 4.01-8.0    | 17        | 18.89%  |
| 16.01-24.0  | 13        | 14.44%  |
| 24.01-32.0  | 12        | 13.33%  |
| 64.01-256.0 | 8         | 8.89%   |
| 32.01-64.0  | 7         | 7.78%   |
| 3.01-4.0    | 5         | 5.56%   |
| 1.01-2.0    | 2         | 2.22%   |
| 2.01-3.0    | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 5      | 20        | 21.98%  |
| 10     | 18        | 19.78%  |
| 3      | 14        | 15.38%  |
| 4      | 8         | 8.79%   |
| 1      | 8         | 8.79%   |
| 9      | 5         | 5.49%   |
| 6      | 5         | 5.49%   |
| 8      | 4         | 4.4%    |
| 13     | 2         | 2.2%    |
| 2      | 2         | 2.2%    |
| 193    | 1         | 1.1%    |
| 36     | 1         | 1.1%    |
| 34     | 1         | 1.1%    |
| 17     | 1         | 1.1%    |
| 14     | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 97.4%   |
| Yes       | 2         | 2.6%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 77        | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Moscow      | 70        | 90.91%  |
| Chelyabinsk | 5         | 6.49%   |
| Perm        | 2         | 2.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 220    | 27.52%  |
| Seagate             | 30        | 94     | 20.13%  |
| Intel               | 23        | 91     | 15.44%  |
| Micron Technology   | 22        | 94     | 14.77%  |
| Toshiba             | 9         | 94     | 6.04%   |
| HGST                | 6         | 11     | 4.03%   |
| HPE                 | 3         | 3      | 2.01%   |
| WDC                 | 2         | 3      | 1.34%   |
| VSTORAGE            | 2         | 171    | 1.34%   |
| SCST_BIO            | 2         | 6      | 1.34%   |
| Hitachi             | 2         | 5      | 1.34%   |
| Hewlett-Packard     | 2         | 16     | 1.34%   |
| Lenovo              | 1         | 14     | 0.67%   |
| Kingston            | 1         | 1      | 0.67%   |
| Foxline             | 1         | 2      | 0.67%   |
| DGC                 | 1         | 6      | 0.67%   |
| DELLBOSS            | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung MZ7L3240HCHQ-00A07 240GB SSD                         | 15        | 6.91%   |
| Samsung MZ7L3960HCJR-00A07 960GB                             | 13        | 5.99%   |
| Seagate ST2000NX0403 2TB                                     | 12        | 5.53%   |
| Samsung MZ7L3480HBLT-00A07 480GB SSD                         | 12        | 5.53%   |
| Samsung MZ1L21T9 472GB                                       | 12        | 5.53%   |
| Seagate ST4000NM000A-2HZ100 4TB                              | 11        | 5.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB         | 11        | 5.07%   |
| Intel SSDSC2KG240G8 240GB                                    | 10        | 4.61%   |
| Intel SSDSC2KB960G8 960GB                                    | 10        | 4.61%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller] 2TB | 9         | 4.15%   |
| Seagate ST4000NM0035-1V4107 4TB                              | 6         | 2.76%   |
| Micron 5300_MTFDDAK1T9TDT 2TB SSD                            | 5         | 2.3%    |
| Samsung MZ7L31T9HBLT-00A07 2TB SSD                           | 4         | 1.84%   |
| Micron 7300_MTFDHBE3T8TDF 4TB                                | 4         | 1.84%   |
| Intel PCIe Data Center SSD 450GB                             | 4         | 1.84%   |
| Toshiba MG04ACA400E 4TB                                      | 3         | 1.38%   |
| Samsung MZQL23T8 4TB                                         | 3         | 1.38%   |
| Samsung MZILT3T8HBLS/007 4TB SSD                             | 3         | 1.38%   |
| Samsung MZ7L3480HCHQ-00A07 480GB SSD                         | 3         | 1.38%   |
| Micron 5300_MTFDDAK3T8TDT 4TB SSD                            | 3         | 1.38%   |
| Micron 5300_MTFD 2TB SSD                                     | 3         | 1.38%   |
| HPE LOGICAL VOLUME 7TB                                       | 3         | 1.38%   |
| VSTORAGE VSTOR-DISK 1.2TB                                    | 2         | 0.92%   |
| Toshiba MG03ACA100 1TB                                       | 2         | 0.92%   |
| Toshiba HDWD130 3TB                                          | 2         | 0.92%   |
| Seagate ST4000NM001B 4TB                                     | 2         | 0.92%   |
| Samsung SSD 850 PRO 512GB                                    | 2         | 0.92%   |
| Samsung MZ1L2960 960GB                                       | 2         | 0.92%   |
| Micron 5300_MTFDDAK7T6TDS 8TB SSD                            | 2         | 0.92%   |
| Micron 5300_MTFDDAK480TDS 480GB SSD                          | 2         | 0.92%   |
| Micron 5200_MTFDDAK480TDN 480GB SSD                          | 2         | 0.92%   |
| Micron 5100_MTFDDAK960TCB 960GB SSD                          | 2         | 0.92%   |
| Micron 1100_MTFDDAK512TBN 512GB SSD                          | 2         | 0.92%   |
| HGST HUS726040ALE614 4TB                                     | 2         | 0.92%   |
| HP HSV340 112GB                                              | 2         | 0.92%   |
| WDC WD4002FYYZ-01B7CB1 4TB                                   | 1         | 0.46%   |
| WDC WD1003FBYZ-010FB0 1TB                                    | 1         | 0.46%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                       | 1         | 0.46%   |
| Toshiba MG09SCA18TE 18TB                                     | 1         | 0.46%   |
| Toshiba MG03SCA100 1TB                                       | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 30        | 94     | 52.63%  |
| Toshiba         | 8         | 88     | 14.04%  |
| HGST            | 6         | 11     | 10.53%  |
| WDC             | 2         | 3      | 3.51%   |
| VSTORAGE        | 2         | 171    | 3.51%   |
| SCST_BIO        | 2         | 6      | 3.51%   |
| Hitachi         | 2         | 5      | 3.51%   |
| Hewlett-Packard | 2         | 16     | 3.51%   |
| Lenovo          | 1         | 10     | 1.75%   |
| DGC             | 1         | 6      | 1.75%   |
| DELLBOSS        | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 129    | 52.63%  |
| Micron Technology   | 21        | 73     | 27.63%  |
| Intel               | 10        | 38     | 13.16%  |
| HPE                 | 3         | 3      | 3.95%   |
| Lenovo              | 1         | 4      | 1.32%   |
| Foxline             | 1         | 2      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 66        | 249    | 40.74%  |
| HDD     | 48        | 411    | 29.63%  |
| NVMe    | 46        | 167    | 28.4%   |
| Unknown | 2         | 5      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 605    | 54.01%  |
| NVMe | 46        | 167    | 33.58%  |
| SAS  | 17        | 60     | 12.41%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 122    | 33.33%  |
| 0.51-1.0   | 33        | 78     | 21.57%  |
| 3.01-4.0   | 31        | 128    | 20.26%  |
| 1.01-2.0   | 27        | 255    | 17.65%  |
| 4.01-10.0  | 6         | 9      | 3.92%   |
| 2.01-3.0   | 3         | 39     | 1.96%   |
| 10.01-20.0 | 2         | 29     | 1.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 48        | 52.75%  |
| 1001-2000      | 21        | 23.08%  |
| 2001-3000      | 10        | 10.99%  |
| 251-500        | 8         | 8.79%   |
| 501-1000       | 2         | 2.2%    |
| 1-20           | 1         | 1.1%    |
| 51-100         | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 35        | 37.23%  |
| More than 3000 | 13        | 13.83%  |
| 101-250        | 13        | 13.83%  |
| 21-50          | 11        | 11.7%   |
| 251-500        | 10        | 10.64%  |
| 501-1000       | 5         | 5.32%   |
| 2001-3000      | 4         | 4.26%   |
| 51-100         | 3         | 3.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST4000NM0035-1V4107 4TB                | 2         | 2      | 28.57%  |
| Micron Technology 5300_MTFDDAK1T9TDT 2TB SSD   | 2         | 8      | 28.57%  |
| Micron Technology 5300_MTFDDAK7T6TDS 8TB SSD   | 1         | 2      | 14.29%  |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 1         | 3      | 14.29%  |
| Hitachi HDS721010CLA330 1TB                    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 4         | 13     | 57.14%  |
| Seagate           | 2         | 2      | 28.57%  |
| Hitachi           | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 13     | 57.14%  |
| HDD  | 3         | 3      | 42.86%  |

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
| Works    | 73        | 762    | 78.49%  |
| Detected | 13        | 54     | 13.98%  |
| Malfunc  | 7         | 16     | 7.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 60        | 41.38%  |
| Samsung Electronics          | 26        | 17.93%  |
| ASMedia Technology           | 14        | 9.66%   |
| AMD                          | 12        | 8.28%   |
| LSI Logic / Symbios Logic    | 10        | 6.9%    |
| Broadcom / LSI               | 9         | 6.21%   |
| Micron Technology            | 5         | 3.45%   |
| Adaptec                      | 3         | 2.07%   |
| Hewlett-Packard              | 2         | 1.38%   |
| Toshiba America Info Systems | 1         | 0.69%   |
| Marvell Technology Group     | 1         | 0.69%   |
| Kingston Technology Company  | 1         | 0.69%   |
| Areca Technology             | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 48        | 22.75%  |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 29        | 13.74%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 26        | 12.32%  |
| Intel SATA Controller [RAID Mode]                                             | 21        | 9.95%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 12        | 5.69%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 10        | 4.74%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 9         | 4.27%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                       | 5         | 2.37%   |
| Micron 7300 PRO NVMe SSD                                                      | 4         | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 4         | 1.9%    |
| Intel PCIe Data Center SSD                                                    | 4         | 1.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 4         | 1.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 4         | 1.9%    |
| ASMedia 106x SATA/RAID Controller                                             | 4         | 1.9%    |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                | 3         | 1.42%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                           | 3         | 1.42%   |
| Adaptec Smart Storage PQI SAS                                                 | 3         | 1.42%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                          | 2         | 0.95%   |
| HP Smart Array Gen8 Controllers                                               | 2         | 0.95%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                  | 2         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.47%   |
| Micron 7400 PRO NVMe SSD                                                      | 1         | 0.47%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 0.47%   |
| Kingston Company DC1000B NVMe SSD [E12DC]                                     | 1         | 0.47%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 0.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1         | 0.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 0.47%   |
| Broadcom / LSI SAS3408 Fusion-MPT Tri-Mode I/O Controller Chip (IOC)          | 1         | 0.47%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3508                                      | 1         | 0.47%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                | 1         | 0.47%   |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 0.47%   |
| Areca ARC-1886 series PCIe 4.0 to NVMe/SAS/SATA 16/12/6Gb RAID Controller     | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 43.64%  |
| NVMe | 46        | 27.88%  |
| RAID | 35        | 21.21%  |
| SAS  | 12        | 7.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 84.42%  |
| AMD    | 12        | 15.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel Xeon Silver 4208 CPU @ 2.10GHz  | 22        | 28.57%  |
| Intel Xeon Silver 4310 CPU @ 2.10GHz  | 11        | 14.29%  |
| AMD EPYC 7352 24-Core Processor       | 10        | 12.99%  |
| Intel Xeon Gold 6248 CPU @ 2.50GHz    | 4         | 5.19%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz   | 4         | 5.19%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz   | 2         | 2.6%    |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz   | 2         | 2.6%    |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz   | 2         | 2.6%    |
| AMD EPYC 7502P 32-Core Processor      | 2         | 2.6%    |
| Intel Xeon Silver 4214R CPU @ 2.40GHz | 1         | 1.3%    |
| Intel Xeon Silver 4210R CPU @ 2.40GHz | 1         | 1.3%    |
| Intel Xeon Silver 4210 CPU @ 2.20GHz  | 1         | 1.3%    |
| Intel Xeon Silver 4114 CPU @ 2.20GHz  | 1         | 1.3%    |
| Intel Xeon Gold 6346 CPU @ 3.10GHz    | 1         | 1.3%    |
| Intel Xeon Gold 6338 CPU @ 2.00GHz    | 1         | 1.3%    |
| Intel Xeon Gold 6326 CPU @ 2.90GHz    | 1         | 1.3%    |
| Intel Xeon Gold 6238R CPU @ 2.20GHz   | 1         | 1.3%    |
| Intel Xeon Gold 6230R CPU @ 2.10GHz   | 1         | 1.3%    |
| Intel Xeon Gold 6140 CPU @ 2.30GHz    | 1         | 1.3%    |
| Intel Xeon Gold 5220 CPU @ 2.20GHz    | 1         | 1.3%    |
| Intel Xeon Gold 5120 CPU @ 2.20GHz    | 1         | 1.3%    |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz    | 1         | 1.3%    |
| Intel Xeon CPU E5-2670 v2 @ 2.50GHz   | 1         | 1.3%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz    | 1         | 1.3%    |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz   | 1         | 1.3%    |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz   | 1         | 1.3%    |
| Intel Core i7-7700 CPU @ 3.60GHz      | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon Silver | 37        | 48.05%  |
| Intel Xeon Gold   | 16        | 20.78%  |
| AMD EPYC          | 12        | 15.58%  |
| Intel Xeon        | 11        | 14.29%  |
| Intel Core i7     | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 24     | 17        | 22.08%  |
| 16     | 14        | 18.18%  |
| 8      | 10        | 12.99%  |
| 12     | 9         | 11.69%  |
| 20     | 6         | 7.79%   |
| 4      | 5         | 6.49%   |
| 40     | 4         | 5.19%   |
| 32     | 4         | 5.19%   |
| 36     | 2         | 2.6%    |
| 64     | 1         | 1.3%    |
| 56     | 1         | 1.3%    |
| 52     | 1         | 1.3%    |
| 48     | 1         | 1.3%    |
| 28     | 1         | 1.3%    |
| 10     | 1         | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 50.65%  |
| 2      | 38        | 49.35%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 75        | 97.4%   |
| 1      | 2         | 2.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x50657    | 36        | 44.44%  |
| 0x606a6    | 13        | 16.05%  |
| 0x08301055 | 10        | 12.35%  |
| 0x406f1    | 4         | 4.94%   |
| 0x906e9    | 3         | 3.7%    |
| 0x50654    | 3         | 3.7%    |
| 0x0830107b | 3         | 3.7%    |
| Unknown    | 3         | 3.7%    |
| 0x506e3    | 2         | 2.47%   |
| 0x206d7    | 2         | 2.47%   |
| 0x306e4    | 1         | 1.23%   |
| 0x0830107c | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Skylake     | 41        | 53.25%  |
| Zen 2       | 12        | 15.58%  |
| Unknown     | 11        | 14.29%  |
| Broadwell   | 4         | 5.19%   |
| KabyLake    | 3         | 3.9%    |
| Icelake     | 3         | 3.9%    |
| SandyBridge | 2         | 2.6%    |
| IvyBridge   | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| ASPEED Technology          | 65        | 82.28%  |
| Matrox Electronics Systems | 11        | 13.92%  |
| Nvidia                     | 2         | 2.53%   |
| Intel                      | 1         | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                 | 65        | 81.25%  |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 4         | 5%      |
| Matrox Electronics Systems MGA G200eH3                                   | 3         | 3.75%   |
| Matrox Electronics Systems MGA G200EH                                    | 2         | 2.5%    |
| Nvidia GV100GL [Tesla V100 PCIe 32GB]                                    | 1         | 1.25%   |
| Nvidia GA107GL [A2 / A16]                                                | 1         | 1.25%   |
| Nvidia GA100 [A100 PCIe 40GB]                                            | 1         | 1.25%   |
| Matrox Electronics Systems MGA G200eW WPCM450                            | 1         | 1.25%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)        | 1         | 1.25%   |
| Intel HD Graphics 630                                                    | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x ASPEED              | 64        | 83.12%  |
| 1 x Matrox              | 10        | 12.99%  |
| 2 x Nvidia + 1 x ASPEED | 1         | 1.3%    |
| Nvidia + Matrox         | 1         | 1.3%    |
| 1 x Intel               | 1         | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 77        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 98.7%   |
| 24.01-32.0 | 1         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| KVM              | 2         | 28.57%  |
| BenQ             | 2         | 28.57%  |
| ViewSonic        | 1         | 14.29%  |
| Dell             | 1         | 14.29%  |
| ASUSTek Computer | 1         | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| KVM LCD Monitor1717 KVM4308 1280x1024 338x270mm 17.0-inch      | 2         | 28.57%  |
| BenQ E2220HD BNQ7912 1920x1080 477x268mm 21.5-inch             | 2         | 28.57%  |
| ViewSonic VA2245 Series VSCF42E 1920x1080 477x268mm 21.5-inch  | 1         | 14.29%  |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch              | 1         | 14.29%  |
| ASUSTek Computer PA247CV AUS2464 1920x1080 527x296mm 23.8-inch | 1         | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 4         | 66.67%  |
| 1280x1024 (SXGA) | 2         | 33.33%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 21     | 3         | 42.86%  |
| 19     | 2         | 28.57%  |
| 24     | 1         | 14.29%  |
| 23     | 1         | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 401-500     | 3         | 50%     |
| 351-400     | 2         | 33.33%  |
| 501-600     | 1         | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 4         | 66.67%  |
| 5/4   | 2         | 33.33%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 151-200        | 5         | 83.33%  |
| 201-250        | 1         | 16.67%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 3         | 50%     |
| 51-100  | 3         | 50%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 91.03%  |
| 1     | 6         | 7.69%   |
| 2     | 1         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 46.67%  |
| Mellanox Technologies | 41        | 27.33%  |
| Broadcom              | 24        | 16%     |
| Emulex                | 6         | 4%      |
| Broadcom Limited      | 3         | 2%      |
| Insyde Software       | 2         | 1.33%   |
| Dell                  | 2         | 1.33%   |
| IBM                   | 1         | 0.67%   |
| American Megatrends   | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Ethernet Controller E810-XXV for SFP                                    | 34        | 17.09%  |
| Intel Ethernet Connection X722 for 1GbE                                       | 18        | 9.05%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 15        | 7.54%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 7.04%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 7.04%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 13        | 6.53%   |
| Mellanox MT27700 Family [ConnectX-4]                                          | 13        | 6.53%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                  | 12        | 6.03%   |
| Broadcom BCM57412 NetXtreme-E 10Gb RDMA Ethernet Controller                   | 12        | 6.03%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 5.03%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 5.03%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 2.51%   |
| Intel Ethernet Connection X722                                                | 3         | 1.51%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.51%   |
| Broadcom Limited BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 3         | 1.51%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 1.01%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.01%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 1.01%   |
| Dell iDRAC Virtual NIC                                                        | 2         | 1.01%   |
| Broadcom Limited NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 2         | 1.01%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.5%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.5%    |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.5%    |
| IBM RNDIS/CDC ETHER                                                           | 1         | 0.5%    |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.5%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 0.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.5%    |
| American Megatrends Virtual Ethernet.                                         | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

Zero info for selected period =(

Wireless Model
--------------

Wireless models

Zero info for selected period =(

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 49.3%   |
| Mellanox Technologies | 33        | 23.24%  |
| Broadcom              | 24        | 16.9%   |
| Emulex                | 6         | 4.23%   |
| Broadcom Limited      | 3         | 2.11%   |
| Insyde Software       | 2         | 1.41%   |
| Dell                  | 2         | 1.41%   |
| IBM                   | 1         | 0.7%    |
| American Megatrends   | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Ethernet Controller E810-XXV for SFP                                    | 34        | 17.8%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 18        | 9.42%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 15        | 7.85%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 7.33%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 7.33%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 13        | 6.81%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                  | 12        | 6.28%   |
| Broadcom BCM57412 NetXtreme-E 10Gb RDMA Ethernet Controller                   | 12        | 6.28%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 5.24%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 5.24%   |
| Mellanox MT27700 Family [ConnectX-4]                                          | 5         | 2.62%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 2.62%   |
| Intel Ethernet Connection X722                                                | 3         | 1.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.57%   |
| Broadcom Limited BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 3         | 1.57%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 1.05%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.05%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 1.05%   |
| Dell iDRAC Virtual NIC                                                        | 2         | 1.05%   |
| Broadcom Limited NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 2         | 1.05%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.52%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.52%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.52%   |
| IBM RNDIS/CDC ETHER                                                           | 1         | 0.52%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.52%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 0.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.52%   |
| American Megatrends Virtual Ethernet.                                         | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 88.51%  |
| Unknown  | 10        | 11.49%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 98.7%   |
| Unknown  | 1         | 1.3%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 6     | 20        | 25%     |
| 2     | 18        | 22.5%   |
| 4     | 15        | 18.75%  |
| 8     | 14        | 17.5%   |
| 10    | 4         | 5%      |
| 5     | 4         | 5%      |
| 3     | 4         | 5%      |
| 1     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

Zero info for selected period =(

Bluetooth Model
---------------

Controller models

Zero info for selected period =(

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel Lewisburg MROM 0        | 1         | 50%     |
| Intel 200 Series PCH HD Audio | 1         | 50%     |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 56.25%  |
| Micron Technology   | 14        | 17.5%   |
| Nanya Technology    | 6         | 7.5%    |
| SK hynix            | 5         | 6.25%   |
| Kingston            | 4         | 5%      |
| HPE                 | 3         | 3.75%   |
| Unknown             | 2         | 2.5%    |
| Unknown             | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s   | 15        | 18.29%  |
| Samsung RAM M393A8G40BB4-CWE 64GB DIMM DDR4 3200MT/s   | 13        | 15.85%  |
| Micron RAM 36ASF4G72PZ-2G9E2 32GB DIMM DDR4 2933MT/s   | 10        | 12.2%   |
| Samsung RAM M393A2K40DB3-CWE 16GB DIMM DDR4 3200MT/s   | 8         | 9.76%   |
| Nanya RAM NT32GA72D4NBX3P-IX 32GB DIMM DDR4 2933MT/s   | 4         | 4.88%   |
| Samsung RAM M393A2K43FB3-CWE 16GB DIMM DDR4 3200MT/s   | 3         | 3.66%   |
| HPE RAM P03052-091 32GB DIMM DDR4 3200MT/s             | 3         | 3.66%   |
| Unknown RAM Module 16GB DIMM DDR3 1866MT/s             | 2         | 2.44%   |
| Unknown RAM Module 16GB DIMM DDR3 1333MT/s             | 2         | 2.44%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 2         | 2.44%   |
| Nanya RAM NT32GA72D4NFX3K-JR 32GB DIMM DDR4 3200MT/s   | 2         | 2.44%   |
| Micron RAM 18ASF2G72AZ-2G3B1 16GB DIMM DDR4 2400MT/s   | 2         | 2.44%   |
| SK hynix RAM HMT42GR7MFR4C-PB 16GB DIMM DDR3 1600MT/s  | 1         | 1.22%   |
| SK hynix RAM HMA84GR7DJR4N-WM 32GB DIMM DDR4 2933MT/s  | 1         | 1.22%   |
| SK hynix RAM HMA84GR7CJR4N-VK 32GB DIMM DDR4 2667MT/s  | 1         | 1.22%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2667MT/s  | 1         | 1.22%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s  | 1         | 1.22%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s   | 1         | 1.22%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s   | 1         | 1.22%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s   | 1         | 1.22%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s   | 1         | 1.22%   |
| Micron RAM 18ASF2G72PDZ-2G6E1 16GB DIMM DDR4 2667MT/s  | 1         | 1.22%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s   | 1         | 1.22%   |
| Kingston RAM 9965742-055.B00G 32GB DIMM DDR4 3200MT/s  | 1         | 1.22%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s  | 1         | 1.22%   |
| Kingston RAM 9965640-016.A00G 32GB DIMM DDR4 2133MT/s  | 1         | 1.22%   |
| Kingston RAM 9965516-071.A00LF 16GB DIMM DDR3 1066MT/s | 1         | 1.22%   |
| Unknown                                                | 1         | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 71        | 92.21%  |
| DRAM | 3         | 3.9%    |
| DDR3 | 3         | 3.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| DIMM | 77        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 32768 | 29        | 37.66%  |
| 65536 | 28        | 36.36%  |
| 16384 | 20        | 25.97%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 47        | 58.02%  |
| 2933  | 15        | 18.52%  |
| 2400  | 5         | 6.17%   |
| 2667  | 4         | 4.94%   |
| 1866  | 2         | 2.47%   |
| 1600  | 2         | 2.47%   |
| 1333  | 2         | 2.47%   |
| 3466  | 1         | 1.23%   |
| 2134  | 1         | 1.23%   |
| 2133  | 1         | 1.23%   |
| 1066  | 1         | 1.23%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 29        | 37.66%  |
| 0     | 19        | 24.68%  |
| 4     | 18        | 23.38%  |
| 2     | 7         | 9.09%   |
| 5     | 3         | 3.9%    |
| 1     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 58        | 47.15%  |
| Unassigned class         | 57        | 46.34%  |
| Graphics card            | 4         | 3.25%   |
| Net/ethernet             | 3         | 2.44%   |
| Storage/raid             | 1         | 0.81%   |


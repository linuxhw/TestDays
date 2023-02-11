AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 84

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cca8d74416](https://linux-hardware.org/?probe=cca8d74416) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f0884ec1aa](https://linux-hardware.org/?probe=f0884ec1aa) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [89430aeb82](https://linux-hardware.org/?probe=89430aeb82) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6d079ed3ca](https://linux-hardware.org/?probe=6d079ed3ca) | Jan 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d81d33bda5](https://linux-hardware.org/?probe=d81d33bda5) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [091b3e37fb](https://linux-hardware.org/?probe=091b3e37fb) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49654976af](https://linux-hardware.org/?probe=49654976af) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d41a70cbf5](https://linux-hardware.org/?probe=d41a70cbf5) | Jan 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [af868046e3](https://linux-hardware.org/?probe=af868046e3) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7c026252d0](https://linux-hardware.org/?probe=7c026252d0) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [bd3f6fa130](https://linux-hardware.org/?probe=bd3f6fa130) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [477f1a3aad](https://linux-hardware.org/?probe=477f1a3aad) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | Falco                       | Notebook    | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [56758aeb6f](https://linux-hardware.org/?probe=56758aeb6f) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec3b130618](https://linux-hardware.org/?probe=ec3b130618) | Jan 07, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | Falco                       | Notebook    | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4571b799f0](https://linux-hardware.org/?probe=4571b799f0) | Dec 20, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 11        | 20.75%  |
| AlmaLinux 8.6 | 10        | 18.87%  |
| AlmaLinux 9.0 | 9         | 16.98%  |
| AlmaLinux 8.4 | 9         | 16.98%  |
| AlmaLinux 8.7 | 7         | 13.21%  |
| AlmaLinux 8.3 | 4         | 7.55%   |
| AlmaLinux 8.5 | 3         | 5.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 8         | 15.38%  |
| 4.18.0-425.3.1.el8.x86_64     | 5         | 9.62%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 5.77%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 3         | 5.77%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 5.77%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 5.77%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 3.85%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 3.85%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 3.85%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 3.85%   |
| 4.18.0-305.el8.x86_64         | 2         | 3.85%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 3.85%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 3.85%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 1.92%   |
| 5.15.45-v8.1.el8              | 1         | 1.92%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 1.92%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 1.92%   |
| 5.10.60-v8.1.el8              | 1         | 1.92%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 1.92%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 1.92%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 1.92%   |
| 4.18.0-348.el8.x86_64         | 1         | 1.92%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 1.92%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 1.92%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 1.92%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 28        | 54.9%   |
| 5.14.0  | 20        | 39.22%  |
| 5.4.175 | 1         | 1.96%   |
| 5.15.45 | 1         | 1.96%   |
| 5.10.60 | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 28        | 54.9%   |
| 5.14    | 20        | 39.22%  |
| 5.4     | 1         | 1.96%   |
| 5.15    | 1         | 1.96%   |
| 5.10    | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 48        | 94.12%  |
| aarch64 | 3         | 5.88%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 31        | 60.78%  |
| Unknown       | 12        | 23.53%  |
| KDE5          | 3         | 5.88%   |
| XFCE          | 2         | 3.92%   |
| MATE          | 2         | 3.92%   |
| GNOME Classic | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 24        | 47.06%  |
| X11     | 20        | 39.22%  |
| Unknown | 5         | 9.8%    |
| Tty     | 2         | 3.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 68.63%  |
| GDM     | 12        | 23.53%  |
| SDDM    | 2         | 3.92%   |
| LightDM | 2         | 3.92%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 26        | 49.06%  |
| de_DE   | 7         | 13.21%  |
| en_GB   | 6         | 11.32%  |
| fr_FR   | 2         | 3.77%   |
| en_CA   | 2         | 3.77%   |
| C       | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| uk_UA   | 1         | 1.89%   |
| ru_UA   | 1         | 1.89%   |
| ru_RU   | 1         | 1.89%   |
| es_VE   | 1         | 1.89%   |
| es_ES   | 1         | 1.89%   |
| da_DK   | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 59.62%  |
| BIOS | 21        | 40.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 39        | 76.47%  |
| Ext4 | 12        | 23.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 25        | 49.02%  |
| Unknown | 20        | 39.22%  |
| MBR     | 6         | 11.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 80.39%  |
| Yes       | 10        | 19.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 80.39%  |
| Yes       | 10        | 19.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 13        | 25.49%  |
| Hewlett-Packard         | 10        | 19.61%  |
| Dell                    | 5         | 9.8%    |
| Gigabyte Technology     | 4         | 7.84%   |
| ASUSTek Computer        | 4         | 7.84%   |
| Supermicro              | 2         | 3.92%   |
| Raspberry Pi Foundation | 2         | 3.92%   |
| Intel                   | 2         | 3.92%   |
| ASRock                  | 2         | 3.92%   |
| Acer                    | 2         | 3.92%   |
| Toshiba                 | 1         | 1.96%   |
| Optimized Hosting       | 1         | 1.96%   |
| MSI                     | 1         | 1.96%   |
| Google                  | 1         | 1.96%   |
| ASRockRack              | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 3.92%   |
| Toshiba Satellite L50-C              | 1         | 1.96%   |
| Supermicro Super Server              | 1         | 1.96%   |
| Supermicro motherboard-H12 Series    | 1         | 1.96%   |
| Optimized Hosting KVM                | 1         | 1.96%   |
| MSI MS-7900                          | 1         | 1.96%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.96%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.96%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.96%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.96%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.96%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.96%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.96%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.96%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.96%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.96%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.96%   |
| Lenovo H520S 10093                   | 1         | 1.96%   |
| Lenovo B50-30 20382                  | 1         | 1.96%   |
| Intel powered classmate PC           | 1         | 1.96%   |
| Intel NUC8i5BEH                      | 1         | 1.96%   |
| HP Z620 Workstation                  | 1         | 1.96%   |
| HP Z600 Workstation                  | 1         | 1.96%   |
| HP ProLiant DL360p Gen8              | 1         | 1.96%   |
| HP Laptop 17-cp0xxx                  | 1         | 1.96%   |
| HP Laptop 15-ef1xxx                  | 1         | 1.96%   |
| HP Falco                             | 1         | 1.96%   |
| HP ENVY dv6                          | 1         | 1.96%   |
| HP EliteBook 8570w                   | 1         | 1.96%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 1.96%   |
| HP EliteBook 8470p                   | 1         | 1.96%   |
| Google Kohaku                        | 1         | 1.96%   |
| Gigabyte Z690 GAMING X DDR4          | 1         | 1.96%   |
| Gigabyte Z590 AORUS PRO AX           | 1         | 1.96%   |
| Gigabyte MP32-AR1-00                 | 1         | 1.96%   |
| Gigabyte H81M-D2V                    | 1         | 1.96%   |
| Dell XPS 13 9365                     | 1         | 1.96%   |
| Dell Precision 7920 Tower            | 1         | 1.96%   |
| Dell PowerEdge R6515                 | 1         | 1.96%   |
| Dell Latitude E6510                  | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo IdeaPad             | 3         | 5.88%   |
| HP EliteBook               | 3         | 5.88%   |
| RPi Raspberry              | 2         | 3.92%   |
| Lenovo ThinkPad            | 2         | 3.92%   |
| Lenovo Legion              | 2         | 3.92%   |
| HP Laptop                  | 2         | 3.92%   |
| Toshiba Satellite          | 1         | 1.96%   |
| Supermicro Super           | 1         | 1.96%   |
| Supermicro motherboard-H12 | 1         | 1.96%   |
| Optimized Hosting KVM      | 1         | 1.96%   |
| MSI MS-7900                | 1         | 1.96%   |
| Lenovo Yoga                | 1         | 1.96%   |
| Lenovo V14-ARE             | 1         | 1.96%   |
| Lenovo ThinkStation        | 1         | 1.96%   |
| Lenovo IdeaPadFlex         | 1         | 1.96%   |
| Lenovo H520S               | 1         | 1.96%   |
| Lenovo B50-30              | 1         | 1.96%   |
| Intel powered              | 1         | 1.96%   |
| Intel NUC8i5BEH            | 1         | 1.96%   |
| HP Z620                    | 1         | 1.96%   |
| HP Z600                    | 1         | 1.96%   |
| HP ProLiant                | 1         | 1.96%   |
| HP Falco                   | 1         | 1.96%   |
| HP ENVY                    | 1         | 1.96%   |
| Google Kohaku              | 1         | 1.96%   |
| Gigabyte Z690              | 1         | 1.96%   |
| Gigabyte Z590              | 1         | 1.96%   |
| Gigabyte MP32-AR1-00       | 1         | 1.96%   |
| Gigabyte H81M-D2V          | 1         | 1.96%   |
| Dell XPS                   | 1         | 1.96%   |
| Dell Precision             | 1         | 1.96%   |
| Dell PowerEdge             | 1         | 1.96%   |
| Dell Latitude              | 1         | 1.96%   |
| Dell Inspiron              | 1         | 1.96%   |
| ASUS TUF                   | 1         | 1.96%   |
| ASUS Q170M2                | 1         | 1.96%   |
| ASUS M5A78L-M              | 1         | 1.96%   |
| ASUS ASUS                  | 1         | 1.96%   |
| ASRockRack X470D4U2-2T     | 1         | 1.96%   |
| ASRock B460                | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 10        | 19.61%  |
| 2012    | 8         | 15.69%  |
| 2022    | 4         | 7.84%   |
| 2021    | 4         | 7.84%   |
| 2019    | 4         | 7.84%   |
| 2018    | 4         | 7.84%   |
| 2014    | 4         | 7.84%   |
| 2011    | 3         | 5.88%   |
| 2015    | 2         | 3.92%   |
| 2013    | 2         | 3.92%   |
| 2010    | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| 2016    | 1         | 1.96%   |
| 2009    | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 25        | 49.02%  |
| Desktop        | 15        | 29.41%  |
| Server         | 6         | 11.76%  |
| System on chip | 2         | 3.92%   |
| Convertible    | 2         | 3.92%   |
| Mini pc        | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 44        | 86.27%  |
| Enabled  | 7         | 13.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 96.08%  |
| Yes  | 2         | 3.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15        | 29.41%  |
| 8.01-16.0       | 10        | 19.61%  |
| 64.01-256.0     | 6         | 11.76%  |
| 16.01-24.0      | 6         | 11.76%  |
| 3.01-4.0        | 4         | 7.84%   |
| More than 256.0 | 3         | 5.88%   |
| 32.01-64.0      | 2         | 3.92%   |
| 1.01-2.0        | 2         | 3.92%   |
| 0.51-1.0        | 2         | 3.92%   |
| 24.01-32.0      | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 15        | 27.78%  |
| 3.01-4.0    | 10        | 18.52%  |
| 1.01-2.0    | 10        | 18.52%  |
| 4.01-8.0    | 6         | 11.11%  |
| 8.01-16.0   | 3         | 5.56%   |
| 0.51-1.0    | 3         | 5.56%   |
| 32.01-64.0  | 2         | 3.7%    |
| 0.01-0.5    | 2         | 3.7%    |
| 24.01-32.0  | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |
| 16.01-24.0  | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 46.15%  |
| 2      | 17        | 32.69%  |
| 4      | 4         | 7.69%   |
| 3      | 3         | 5.77%   |
| 11     | 1         | 1.92%   |
| 6      | 1         | 1.92%   |
| 5      | 1         | 1.92%   |
| 0      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 76.47%  |
| Yes       | 12        | 23.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 80.39%  |
| No        | 10        | 19.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 62.75%  |
| No        | 19        | 37.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 58.82%  |
| No        | 21        | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 27.45%  |
| Germany      | 8         | 15.69%  |
| France       | 4         | 7.84%   |
| UK           | 3         | 5.88%   |
| Canada       | 3         | 5.88%   |
| Ukraine      | 2         | 3.92%   |
| Spain        | 2         | 3.92%   |
| Russia       | 2         | 3.92%   |
| Netherlands  | 2         | 3.92%   |
| Venezuela    | 1         | 1.96%   |
| Switzerland  | 1         | 1.96%   |
| Sweden       | 1         | 1.96%   |
| South Africa | 1         | 1.96%   |
| Puerto Rico  | 1         | 1.96%   |
| Pakistan     | 1         | 1.96%   |
| Kazakhstan   | 1         | 1.96%   |
| India        | 1         | 1.96%   |
| Greenland    | 1         | 1.96%   |
| Finland      | 1         | 1.96%   |
| Bulgaria     | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Hamburg       | 3         | 5.77%   |
| Queens        | 2         | 3.85%   |
| Dallas        | 2         | 3.85%   |
| Zaporizhzhia  | 1         | 1.92%   |
| Winterswijk   | 1         | 1.92%   |
| Uppsala       | 1         | 1.92%   |
| Tuusula       | 1         | 1.92%   |
| Tampa         | 1         | 1.92%   |
| Strasbourg    | 1         | 1.92%   |
| Stadtilm      | 1         | 1.92%   |
| St. Paul      | 1         | 1.92%   |
| Sofia         | 1         | 1.92%   |
| Shimanovsk    | 1         | 1.92%   |
| San Diego     | 1         | 1.92%   |
| Rothwell      | 1         | 1.92%   |
| Parla         | 1         | 1.92%   |
| Paris         | 1         | 1.92%   |
| Moscow        | 1         | 1.92%   |
| Mangalore     | 1         | 1.92%   |
| Los Angeles   | 1         | 1.92%   |
| London        | 1         | 1.92%   |
| Liverpool     | 1         | 1.92%   |
| Lille         | 1         | 1.92%   |
| Lawrence      | 1         | 1.92%   |
| Land O' Lakes | 1         | 1.92%   |
| Lahore        | 1         | 1.92%   |
| Kyiv          | 1         | 1.92%   |
| Kitimat       | 1         | 1.92%   |
| Kennewick     | 1         | 1.92%   |
| Johannesburg  | 1         | 1.92%   |
| Ilulissat     | 1         | 1.92%   |
| Guglingen     | 1         | 1.92%   |
| Guanare       | 1         | 1.92%   |
| Groningen     | 1         | 1.92%   |
| Frankenthal   | 1         | 1.92%   |
| Essen         | 1         | 1.92%   |
| East Orange   | 1         | 1.92%   |
| Columbia      | 1         | 1.92%   |
| Castelginest  | 1         | 1.92%   |
| Bloomington   | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 10        | 12     | 13.51%  |
| Seagate                     | 9         | 17     | 12.16%  |
| Samsung Electronics         | 8         | 11     | 10.81%  |
| Kingston                    | 5         | 6      | 6.76%   |
| SK hynix                    | 4         | 4      | 5.41%   |
| Unknown                     | 3         | 5      | 4.05%   |
| Kingston Technology Company | 3         | 7      | 4.05%   |
| Toshiba                     | 2         | 2      | 2.7%    |
| Netac                       | 2         | 2      | 2.7%    |
| LITEONIT                    | 2         | 4      | 2.7%    |
| Intel                       | 2         | 2      | 2.7%    |
| Hewlett-Packard             | 2         | 9      | 2.7%    |
| Dell                        | 2         | 3      | 2.7%    |
| Crucial                     | 2         | 4      | 2.7%    |
| Union Memory                | 1         | 1      | 1.35%   |
| Transcend                   | 1         | 1      | 1.35%   |
| Team                        | 1         | 1      | 1.35%   |
| SSSTC                       | 1         | 1      | 1.35%   |
| Silicon Motion              | 1         | 4      | 1.35%   |
| Sandisk                     | 1         | 1      | 1.35%   |
| QEMU                        | 1         | 1      | 1.35%   |
| Plextor                     | 1         | 1      | 1.35%   |
| Micron Technology           | 1         | 1      | 1.35%   |
| LITEON                      | 1         | 1      | 1.35%   |
| KIOXIA                      | 1         | 1      | 1.35%   |
| Hitachi                     | 1         | 1      | 1.35%   |
| HGST                        | 1         | 1      | 1.35%   |
| EMTEC                       | 1         | 2      | 1.35%   |
| DELLBOSS                    | 1         | 1      | 1.35%   |
| China                       | 1         | 1      | 1.35%   |
| ASMT                        | 1         | 2      | 1.35%   |
| A-DATA Technology           | 1         | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                            | 2         | 2.41%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 2.41%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 2.41%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 2.41%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 1.2%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 1.2%    |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 1.2%    |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 1.2%    |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 1.2%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 1.2%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.2%    |
| Unknown SD64G  64GB                               | 1         | 1.2%    |
| Unknown SD/MMC/MS PRO 2GB                         | 1         | 1.2%    |
| Unknown EC2QT  64GB                               | 1         | 1.2%    |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 1.2%    |
| Transcend TS256GMTE220S 256GB                     | 1         | 1.2%    |
| Toshiba MK6475GSX 640GB                           | 1         | 1.2%    |
| Toshiba DT01ACA100 1TB                            | 1         | 1.2%    |
| Team T253X1480G 480GB SSD                         | 1         | 1.2%    |
| SSSTC CL1-3D256 256GB                             | 1         | 1.2%    |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 1.2%    |
| SK hynix PC300 NVMe Solid State Drive 256GB       | 1         | 1.2%    |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 1.2%    |
| SK hynix BC511 NVMe 256GB                         | 1         | 1.2%    |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 1.2%    |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1         | 1.2%    |
| Seagate ST4000NC001-1FS168 4TB                    | 1         | 1.2%    |
| Seagate ST4000DM000-1F2168 4TB                    | 1         | 1.2%    |
| Seagate ST31000528AS 1TB                          | 1         | 1.2%    |
| Seagate ST3000DM001-1CH166 3TB                    | 1         | 1.2%    |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 1.2%    |
| Seagate ST2000NM012A-2MP130 2TB                   | 1         | 1.2%    |
| Seagate ST2000LM015-2E8174 2TB                    | 1         | 1.2%    |
| Seagate ST2000DM001-1ER164 2TB                    | 1         | 1.2%    |
| Seagate ST2000DL003-9VT166 2TB                    | 1         | 1.2%    |
| Seagate ST1000NM0033-9ZM173 1TB                   | 1         | 1.2%    |
| Seagate ST1000DM003-9YN162 1TB                    | 1         | 1.2%    |
| Seagate ST10000NM0478-2H7100 10TB                 | 1         | 1.2%    |
| Seagate Expansion 240GB                           | 1         | 1.2%    |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 9         | 17     | 36%     |
| WDC             | 7         | 7      | 28%     |
| Toshiba         | 2         | 2      | 8%      |
| Unknown         | 1         | 2      | 4%      |
| QEMU            | 1         | 1      | 4%      |
| Hitachi         | 1         | 1      | 4%      |
| HGST            | 1         | 1      | 4%      |
| Hewlett-Packard | 1         | 8      | 4%      |
| DELLBOSS        | 1         | 1      | 4%      |
| ASMT            | 1         | 2      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 20%     |
| Samsung Electronics | 3         | 3      | 12%     |
| Netac               | 2         | 2      | 8%      |
| LITEONIT            | 2         | 4      | 8%      |
| Intel               | 2         | 2      | 8%      |
| WDC                 | 1         | 3      | 4%      |
| Team                | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Plextor             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Dell                | 1         | 2      | 4%      |
| Crucial             | 1         | 2      | 4%      |
| China               | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 24        | 31     | 33.33%  |
| HDD     | 23        | 42     | 31.94%  |
| NVMe    | 22        | 33     | 30.56%  |
| MMC     | 2         | 3      | 2.78%   |
| Unknown | 1         | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 67     | 56.92%  |
| NVMe | 22        | 33     | 33.85%  |
| SAS  | 4         | 8      | 6.15%   |
| MMC  | 2         | 3      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 35     | 53.06%  |
| 0.51-1.0   | 13        | 16     | 26.53%  |
| 1.01-2.0   | 4         | 9      | 8.16%   |
| 3.01-4.0   | 3         | 3      | 6.12%   |
| 4.01-10.0  | 2         | 9      | 4.08%   |
| 2.01-3.0   | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 30.19%  |
| 251-500        | 9         | 16.98%  |
| More than 3000 | 6         | 11.32%  |
| 501-1000       | 6         | 11.32%  |
| 51-100         | 5         | 9.43%   |
| Unknown        | 4         | 7.55%   |
| 21-50          | 2         | 3.77%   |
| 1001-2000      | 2         | 3.77%   |
| 1-20           | 2         | 3.77%   |
| 2001-3000      | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 40%     |
| 21-50          | 10        | 18.18%  |
| 101-250        | 6         | 10.91%  |
| 51-100         | 6         | 10.91%  |
| Unknown        | 4         | 7.27%   |
| 251-500        | 3         | 5.45%   |
| More than 3000 | 2         | 3.64%   |
| 2001-3000      | 1         | 1.82%   |
| 501-1000       | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J2GB0 2TB         | 1         | 1      | 33.33%  |
| SK hynix SH920 2.5 7MM 256GB SSD | 1         | 1      | 33.33%  |
| LITEONIT LSS-16L6G-HP 16GB SSD   | 1         | 3      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| SK hynix | 1         | 1      | 33.33%  |
| LITEONIT | 1         | 3      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 4      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 28        | 60     | 48.28%  |
| Detected | 27        | 46     | 46.55%  |
| Malfunc  | 3         | 5      | 5.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 31        | 44.93%  |
| AMD                            | 13        | 18.84%  |
| Samsung Electronics            | 6         | 8.7%    |
| Kingston Technology Company    | 4         | 5.8%    |
| Union Memory (Shenzhen)        | 2         | 2.9%    |
| SK hynix                       | 2         | 2.9%    |
| Silicon Motion                 | 2         | 2.9%    |
| SanDisk                        | 2         | 2.9%    |
| Toshiba America Info Systems   | 1         | 1.45%   |
| Solid State Storage Technology | 1         | 1.45%   |
| Red Hat                        | 1         | 1.45%   |
| Micron/Crucial Technology      | 1         | 1.45%   |
| Marvell Technology Group       | 1         | 1.45%   |
| Hewlett-Packard                | 1         | 1.45%   |
| Broadcom / LSI                 | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 13.16%  |
| Samsung NVMe SSD Controller 980                                               | 3         | 3.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 3.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.95%   |
| AMD 400 Series Chipset SATA Controller                                        | 3         | 3.95%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 2.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 2         | 2.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 2.63%   |
| Kingston Company KC2000 NVMe SSD                                              | 2         | 2.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.63%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 1.32%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 1.32%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 1.32%   |
| SK hynix BC511                                                                | 1         | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.32%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 1.32%   |
| Red Hat Virtio SCSI                                                           | 1         | 1.32%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.32%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 1.32%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.32%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.32%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.32%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 1         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.32%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 1         | 1.32%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1         | 1.32%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 1.32%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 1.32%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                      | 1         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 50%     |
| NVMe | 22        | 30.56%  |
| RAID | 7         | 9.72%   |
| IDE  | 5         | 6.94%   |
| SAS  | 1         | 1.39%   |
| SCSI | 1         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 64.71%  |
| AMD    | 15        | 29.41%  |
| ARM    | 3         | 5.88%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 5.88%   |
| ARM Processor                                 | 3         | 5.88%   |
| AMD EPYC 7282 16-Core Processor               | 2         | 3.92%   |
| Intel Xeon W-1350 @ 3.30GHz                   | 1         | 1.96%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz           | 1         | 1.96%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 1.96%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 1.96%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz            | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.96%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.96%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.96%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 1.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.96%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 1.96%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 1.96%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.96%   |
| Intel Core i3-2130 CPU @ 3.40GHz              | 1         | 1.96%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.96%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.96%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 1.96%   |
| Intel 12th Gen Core i7-12700KF                | 1         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.96%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.96%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 1.96%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.96%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 19.61%  |
| Other                   | 8         | 15.69%  |
| Intel Core i7           | 5         | 9.8%    |
| Intel Core i3           | 5         | 9.8%    |
| Intel Xeon              | 4         | 7.84%   |
| AMD EPYC                | 4         | 7.84%   |
| AMD Ryzen 5             | 3         | 5.88%   |
| AMD Ryzen 9             | 2         | 3.92%   |
| Intel Xeon Gold         | 1         | 1.96%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Pentium           | 1         | 1.96%   |
| Intel Celeron           | 1         | 1.96%   |
| Intel Atom              | 1         | 1.96%   |
| AMD Ryzen 7             | 1         | 1.96%   |
| AMD Ryzen 3             | 1         | 1.96%   |
| AMD FX                  | 1         | 1.96%   |
| AMD A6                  | 1         | 1.96%   |
| AMD A10                 | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 16        | 31.37%  |
| 4       | 15        | 29.41%  |
| 6       | 6         | 11.76%  |
| 16      | 4         | 7.84%   |
| 12      | 3         | 5.88%   |
| Unknown | 2         | 3.92%   |
| 80      | 1         | 1.96%   |
| 48      | 1         | 1.96%   |
| 24      | 1         | 1.96%   |
| 8       | 1         | 1.96%   |
| 1       | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 45        | 88.24%  |
| 2       | 3         | 5.88%   |
| Unknown | 2         | 3.92%   |
| 4       | 1         | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 41        | 80.39%  |
| 1       | 8         | 15.69%  |
| Unknown | 2         | 3.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 94.12%  |
| Unknown        | 3         | 5.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 20.75%  |
| 0x806ec    | 4         | 7.55%   |
| 0x306a9    | 4         | 7.55%   |
| 0x40651    | 3         | 5.66%   |
| 0xa0671    | 2         | 3.77%   |
| 0x806c1    | 2         | 3.77%   |
| 0x08701021 | 2         | 3.77%   |
| 0xa0655    | 1         | 1.89%   |
| 0xa0652    | 1         | 1.89%   |
| 0x906ea    | 1         | 1.89%   |
| 0x906e9    | 1         | 1.89%   |
| 0x90672    | 1         | 1.89%   |
| 0x806e9    | 1         | 1.89%   |
| 0x50657    | 1         | 1.89%   |
| 0x406e3    | 1         | 1.89%   |
| 0x306e4    | 1         | 1.89%   |
| 0x306c3    | 1         | 1.89%   |
| 0x30678    | 1         | 1.89%   |
| 0x206a7    | 1         | 1.89%   |
| 0x20655    | 1         | 1.89%   |
| 0x106ca    | 1         | 1.89%   |
| 0x106a5    | 1         | 1.89%   |
| 0x1067a    | 1         | 1.89%   |
| 0x08608103 | 1         | 1.89%   |
| 0x08600106 | 1         | 1.89%   |
| 0x08301055 | 1         | 1.89%   |
| 0x08108109 | 1         | 1.89%   |
| 0x0810100b | 1         | 1.89%   |
| 0x06006705 | 1         | 1.89%   |
| 0x06006704 | 1         | 1.89%   |
| 0x06003106 | 1         | 1.89%   |
| 0x06000852 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 8         | 15.69%  |
| KabyLake         | 8         | 15.69%  |
| IvyBridge        | 5         | 9.8%    |
| Haswell          | 4         | 7.84%   |
| Unknown          | 4         | 7.84%   |
| TigerLake        | 2         | 3.92%   |
| Skylake          | 2         | 3.92%   |
| SandyBridge      | 2         | 3.92%   |
| Icelake          | 2         | 3.92%   |
| Excavator        | 2         | 3.92%   |
| CometLake        | 2         | 3.92%   |
| Zen+             | 1         | 1.96%   |
| Zen              | 1         | 1.96%   |
| Westmere         | 1         | 1.96%   |
| Steamroller      | 1         | 1.96%   |
| Silvermont       | 1         | 1.96%   |
| Piledriver       | 1         | 1.96%   |
| Penryn           | 1         | 1.96%   |
| Nehalem          | 1         | 1.96%   |
| Bonnell          | 1         | 1.96%   |
| Alderlake Hybrid | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 24        | 46.15%  |
| AMD                        | 11        | 21.15%  |
| Nvidia                     | 10        | 19.23%  |
| ASPEED Technology          | 4         | 7.69%   |
| Matrox Electronics Systems | 2         | 3.85%   |
| Red Hat                    | 1         | 1.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 4         | 7.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 5.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 5.77%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 2         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 3.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 3.85%   |
| Red Hat QXL paravirtual graphic card                                      | 1         | 1.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 1.92%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 1.92%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1         | 1.92%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.92%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 1.92%   |
| Nvidia GA102GL [RTX A6000]                                                | 1         | 1.92%   |
| Matrox Electronics Systems MGA G200EH                                     | 1         | 1.92%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 1         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.92%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1         | 1.92%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.92%   |
| Intel HD Graphics 615                                                     | 1         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.92%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 1         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 1.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 1.92%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1         | 1.92%   |
| AMD RS780L [Radeon 3000]                                                  | 1         | 1.92%   |
| AMD Renoir                                                                | 1         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.92%   |
| AMD Lucienne                                                              | 1         | 1.92%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1         | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 41.18%  |
| 1 x AMD        | 11        | 21.57%  |
| 1 x Nvidia     | 7         | 13.73%  |
| 1 x ASPEED     | 4         | 7.84%   |
| Intel + Nvidia | 3         | 5.88%   |
| Other          | 2         | 3.92%   |
| 1 x Matrox     | 2         | 3.92%   |
| 1 x Red Hat    | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 78.43%  |
| Unknown     | 8         | 15.69%  |
| Proprietary | 3         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 66.67%  |
| 0.01-0.5   | 6         | 11.76%  |
| 1.01-2.0   | 4         | 7.84%   |
| 7.01-8.0   | 3         | 5.88%   |
| 32.01-64.0 | 1         | 1.96%   |
| 5.01-6.0   | 1         | 1.96%   |
| 3.01-4.0   | 1         | 1.96%   |
| 0.51-1.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 7         | 16.28%  |
| Samsung Electronics     | 6         | 13.95%  |
| LG Display              | 6         | 13.95%  |
| Sharp                   | 2         | 4.65%   |
| InfoVision              | 2         | 4.65%   |
| Goldstar                | 2         | 4.65%   |
| Dell                    | 2         | 4.65%   |
| Chimei Innolux          | 2         | 4.65%   |
| BOE                     | 2         | 4.65%   |
| BenQ                    | 2         | 4.65%   |
| ViewSonic               | 1         | 2.33%   |
| TopView                 | 1         | 2.33%   |
| STD                     | 1         | 2.33%   |
| Seiki                   | 1         | 2.33%   |
| Philips                 | 1         | 2.33%   |
| PANDA                   | 1         | 2.33%   |
| Medion                  | 1         | 2.33%   |
| Lenovo                  | 1         | 2.33%   |
| Chi Mei Optoelectronics | 1         | 2.33%   |
| AOC                     | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 4.55%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch               | 1         | 2.27%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                      | 1         | 2.27%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                        | 1         | 2.27%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch                  | 1         | 2.27%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 2.27%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 2.27%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 1         | 2.27%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 2.27%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 2.27%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 2.27%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                    | 1         | 2.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 2.27%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 2.27%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 2.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 2.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 1         | 2.27%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                    | 1         | 2.27%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 2.27%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 2.27%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                        | 1         | 2.27%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 2.27%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 56.82%  |
| 1366x768 (WXGA)   | 8         | 18.18%  |
| 1280x1024 (SXGA)  | 3         | 6.82%   |
| 3840x2160 (4K)    | 2         | 4.55%   |
| 3200x1800 (QHD+)  | 1         | 2.27%   |
| 2560x1440 (QHD)   | 1         | 2.27%   |
| 2560x1080         | 1         | 2.27%   |
| 1920x1200 (WUXGA) | 1         | 2.27%   |
| 1600x900 (HD+)    | 1         | 2.27%   |
| 1400x1050         | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 27.27%  |
| 14     | 7         | 15.91%  |
| 31     | 4         | 9.09%   |
| 24     | 4         | 9.09%   |
| 13     | 4         | 9.09%   |
| 21     | 3         | 6.82%   |
| 27     | 2         | 4.55%   |
| 19     | 2         | 4.55%   |
| 17     | 2         | 4.55%   |
| 34     | 1         | 2.27%   |
| 20     | 1         | 2.27%   |
| 18     | 1         | 2.27%   |
| 11     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 45.45%  |
| 501-600     | 6         | 13.64%  |
| 351-400     | 5         | 11.36%  |
| 601-700     | 4         | 9.09%   |
| 401-500     | 4         | 9.09%   |
| 201-300     | 4         | 9.09%   |
| 701-800     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 85.37%  |
| 5/4   | 2         | 4.88%   |
| 6/5   | 1         | 2.44%   |
| 4/3   | 1         | 2.44%   |
| 21/9  | 1         | 2.44%   |
| 16/10 | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 27.27%  |
| 81-90          | 8         | 18.18%  |
| 151-200        | 7         | 15.91%  |
| 351-500        | 5         | 11.36%  |
| 71-80          | 3         | 6.82%   |
| 201-250        | 3         | 6.82%   |
| 301-350        | 2         | 4.55%   |
| 121-130        | 2         | 4.55%   |
| 51-60          | 1         | 2.27%   |
| 251-300        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 35.71%  |
| 51-100        | 13        | 30.95%  |
| 101-120       | 9         | 21.43%  |
| More than 240 | 3         | 7.14%   |
| 1-50          | 1         | 2.38%   |
| 161-240       | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 60.78%  |
| 0     | 12        | 23.53%  |
| 2     | 8         | 15.69%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 32.86%  |
| Realtek Semiconductor | 16        | 22.86%  |
| Qualcomm Atheros      | 9         | 12.86%  |
| Broadcom              | 7         | 10%     |
| Broadcom Limited      | 3         | 4.29%   |
| TP-Link               | 2         | 2.86%   |
| Standard Microsystems | 2         | 2.86%   |
| Mellanox Technologies | 2         | 2.86%   |
| Insyde Software       | 2         | 2.86%   |
| Sierra Wireless       | 1         | 1.43%   |
| Samsung Electronics   | 1         | 1.43%   |
| Ralink                | 1         | 1.43%   |
| MediaTek              | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 13.48%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 3.37%   |
| Standard Microsystems Ethernet controller                         | 2         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.25%   |
| Intel Wireless 7260                                               | 2         | 2.25%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.25%   |
| Intel I350 Gigabit Network Connection                             | 2         | 2.25%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.25%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.25%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 2.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.12%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.12%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.12%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.12%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.12%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                           | 1         | 1.12%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.12%   |
| MediaTek TECNO CAMON 18P                                          | 1         | 1.12%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.12%   |
| Intel Wireless 8260                                               | 1         | 1.12%   |
| Intel Wireless 3165                                               | 1         | 1.12%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.12%   |
| Intel Ethernet Controller X550                                    | 1         | 1.12%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 42.42%  |
| Qualcomm Atheros      | 8         | 24.24%  |
| Realtek Semiconductor | 5         | 15.15%  |
| Broadcom              | 2         | 6.06%   |
| TP-Link               | 1         | 3.03%   |
| Sierra Wireless       | 1         | 3.03%   |
| Ralink                | 1         | 3.03%   |
| Broadcom Limited      | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 6.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 6.06%   |
| Intel Wireless 7260                                        | 2         | 6.06%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 6.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 3.03%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 3.03%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.03%   |
| Intel Wireless 8260                                        | 1         | 3.03%   |
| Intel Wireless 3165                                        | 1         | 3.03%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.03%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.03%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.03%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 3.03%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 31.25%  |
| Intel                 | 15        | 31.25%  |
| Broadcom              | 5         | 10.42%  |
| Standard Microsystems | 2         | 4.17%   |
| Qualcomm Atheros      | 2         | 4.17%   |
| Mellanox Technologies | 2         | 4.17%   |
| Insyde Software       | 2         | 4.17%   |
| Broadcom Limited      | 2         | 4.17%   |
| TP-Link               | 1         | 2.08%   |
| Samsung Electronics   | 1         | 2.08%   |
| MediaTek              | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 12        | 21.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5.36%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 5.36%   |
| Standard Microsystems Ethernet controller                             | 2         | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 3.57%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 3.57%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 3.57%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 3.57%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 3.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1         | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.79%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.79%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.79%   |
| MediaTek TECNO CAMON 18P                                              | 1         | 1.79%   |
| Intel Ethernet Controller X550                                        | 1         | 1.79%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.79%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.79%   |
| Intel 82574L Gigabit Network Connection                               | 1         | 1.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 1.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 1.79%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 1.79%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 56.16%  |
| WiFi     | 32        | 43.84%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 53.06%  |
| WiFi     | 23        | 46.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 52.94%  |
| 1     | 16        | 31.37%  |
| 0     | 3         | 5.88%   |
| 5     | 2         | 3.92%   |
| 4     | 2         | 3.92%   |
| 6     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 78.85%  |
| Yes  | 11        | 21.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 43.33%  |
| Qualcomm Atheros Communications | 6         | 20%     |
| Realtek Semiconductor           | 4         | 13.33%  |
| Broadcom                        | 3         | 10%     |
| Cambridge Silicon Radio         | 2         | 6.67%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| ASUSTek Computer                | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 6         | 20%     |
| Intel Bluetooth wireless interface                  | 5         | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 13.33%  |
| Realtek Bluetooth Radio                             | 3         | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.33%   |
| Intel AX200 Bluetooth                               | 1         | 3.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.33%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 30        | 52.63%  |
| AMD                  | 13        | 22.81%  |
| Nvidia               | 9         | 15.79%  |
| C-Media Electronics  | 2         | 3.51%   |
| Giga-Byte Technology | 1         | 1.75%   |
| Conrad Electronic SE | 1         | 1.75%   |
| Apple                | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.29%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 4.29%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.29%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 4.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.86%   |
| AMD High Definition Audio Controller                                       | 2         | 2.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.43%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.43%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.43%   |
| Intel Lewisburg MROM 0                                                     | 1         | 1.43%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.43%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.43%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.43%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.43%   |
| Giga-Byte Technology USB Audio                                             | 1         | 1.43%   |
| Conrad Electronic SE MIDI Cable UA0037                                     | 1         | 1.43%   |
| C-Media Electronics USB Audio Device                                       | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 22.86%  |
| Kingston            | 8         | 22.86%  |
| Micron Technology   | 6         | 17.14%  |
| SK hynix            | 4         | 11.43%  |
| Crucial             | 3         | 8.57%   |
| Unknown             | 2         | 5.71%   |
| Timetec             | 1         | 2.86%   |
| QEMU                | 1         | 2.86%   |
| Hewlett-Packard     | 1         | 2.86%   |
| Elpida              | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 2         | 5%      |
| Unknown RAM Module 8GB DIMM 1600MT/s                                      | 1         | 2.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.5%    |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 2.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 2.5%    |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s                     | 1         | 2.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 2.5%    |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 2.5%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.5%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 2.5%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 2.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.5%    |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                      | 1         | 2.5%    |
| QEMU RAM Module 8GB DIMM RAM                                              | 1         | 2.5%    |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s                       | 1         | 2.5%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.5%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                      | 1         | 2.5%    |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.5%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 1         | 2.5%    |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s                    | 1         | 2.5%    |
| Kingston RAM 9965742-029.B00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.5%    |
| Kingston RAM 9965640-033.C00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.5%    |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 2.5%    |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 2.5%    |
| HP RAM 712384-081 32GB DIMM DDR3 1866MT/s                                 | 1         | 2.5%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.5%    |
| Crucial RAM CT8G4SFS824A.C8FDD1 8GB SODIMM DDR4 2400MT/s                  | 1         | 2.5%    |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s                   | 1         | 2.5%    |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s                     | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 61.29%  |
| DDR3    | 7         | 22.58%  |
| LPDDR3  | 2         | 6.45%   |
| RAM     | 1         | 3.23%   |
| DDR2    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 15        | 48.39%  |
| SODIMM       | 13        | 41.94%  |
| Row Of Chips | 3         | 9.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 37.5%   |
| 4096  | 7         | 21.88%  |
| 32768 | 5         | 15.63%  |
| 16384 | 4         | 12.5%   |
| 65536 | 2         | 6.25%   |
| 2048  | 2         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 12        | 35.29%  |
| 1600    | 6         | 17.65%  |
| 2667    | 5         | 14.71%  |
| 2133    | 2         | 5.88%   |
| 1866    | 2         | 5.88%   |
| 1333    | 2         | 5.88%   |
| 3600    | 1         | 2.94%   |
| 3466    | 1         | 2.94%   |
| 2400    | 1         | 2.94%   |
| 667     | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

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
| Chicony Electronics                    | 8         | 26.67%  |
| IMC Networks                           | 5         | 16.67%  |
| Acer                                   | 4         | 13.33%  |
| Suyin                                  | 2         | 6.67%   |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Microdia                               | 2         | 6.67%   |
| Luxvisions Innotech Limited            | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Creative Technology                    | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 4         | 12.5%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 6.25%   |
| Chicony HP Truevision HD                                        | 2         | 6.25%   |
| Acer Integrated Camera                                          | 2         | 6.25%   |
| Syntek Integrated Camera                                        | 1         | 3.13%   |
| Suyin HD WebCam                                                 | 1         | 3.13%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.13%   |
| Realtek Integrated Webcam HD                                    | 1         | 3.13%   |
| Realtek EasyCamera                                              | 1         | 3.13%   |
| Microdia USB 2.0 Camera                                         | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 3.13%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 3.13%   |
| Logitech Webcam C120                                            | 1         | 3.13%   |
| Logitech Webcam B500                                            | 1         | 3.13%   |
| Logitech QuickCam Vision Pro                                    | 1         | 3.13%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 3.13%   |
| Creative Live! Cam Chat HD [VF0700]                             | 1         | 3.13%   |
| Chicony Web Camera - HD                                         | 1         | 3.13%   |
| Chicony Lenovo EasyCamera                                       | 1         | 3.13%   |
| Chicony EasyCamera                                              | 1         | 3.13%   |
| Chicony 8M Camera                                               | 1         | 3.13%   |
| Chicony 720p HD Camera                                          | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 3.13%   |
| Acer USB Camera                                                 | 1         | 3.13%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 75%     |
| Synaptics             | 1         | 12.5%   |
| Elan Microelectronics | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 25%     |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner              | 1         | 12.5%   |
| Elan ELAN:ARM-M4                                  | 1         | 12.5%   |
| Unknown                                           | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 31        | 60.78%  |
| 1     | 16        | 31.37%  |
| 2     | 2         | 3.92%   |
| 7     | 1         | 1.96%   |
| 5     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 28.57%  |
| Graphics card         | 5         | 17.86%  |
| Net/wireless          | 3         | 10.71%  |
| Sound                 | 2         | 7.14%   |
| Net/ethernet          | 2         | 7.14%   |
| Multimedia controller | 2         | 7.14%   |
| Unassigned class      | 1         | 3.57%   |
| Storage/ide           | 1         | 3.57%   |
| Firewire controller   | 1         | 3.57%   |
| Chipcard              | 1         | 3.57%   |
| Camera                | 1         | 3.57%   |
| Bluetooth             | 1         | 3.57%   |


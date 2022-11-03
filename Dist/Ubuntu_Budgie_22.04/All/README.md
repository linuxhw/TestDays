Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 88

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 11        | 14.67%  |
| 5.15.0-50-generic     | 6         | 8%      |
| 5.15.0-48-generic     | 6         | 8%      |
| 5.15.0-30-generic     | 6         | 8%      |
| 5.15.0-46-generic     | 5         | 6.67%   |
| 5.15.0-39-generic     | 5         | 6.67%   |
| 5.15.0-52-generic     | 4         | 5.33%   |
| 5.15.0-33-generic     | 4         | 5.33%   |
| 5.15.0-25-generic     | 4         | 5.33%   |
| 5.15.0-47-generic     | 3         | 4%      |
| 5.15.0-43-generic     | 3         | 4%      |
| 5.15.0-40-generic     | 3         | 4%      |
| 5.15.0-41-generic     | 2         | 2.67%   |
| 5.19.0-051900-generic | 1         | 1.33%   |
| 5.17.2-051702-generic | 1         | 1.33%   |
| 5.16.2                | 1         | 1.33%   |
| 5.15.0-52-lowlatency  | 1         | 1.33%   |
| 5.15.0-47-lowlatency  | 1         | 1.33%   |
| 5.15.0-35-generic     | 1         | 1.33%   |
| 5.15.0-18-generic     | 1         | 1.33%   |
| 5.15.0-10052-tuxedo   | 1         | 1.33%   |
| 5.15.0-10047-tuxedo   | 1         | 1.33%   |
| 5.15.0-10041-tuxedo   | 1         | 1.33%   |
| 5.13.0-44-generic     | 1         | 1.33%   |
| 5.13.0-35-generic     | 1         | 1.33%   |
| 5.13.0-19-generic     | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 66        | 91.67%  |
| 5.13.0  | 3         | 4.17%   |
| 5.19.0  | 1         | 1.39%   |
| 5.17.2  | 1         | 1.39%   |
| 5.16.2  | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 66        | 91.67%  |
| 5.13    | 3         | 4.17%   |
| 5.19    | 1         | 1.39%   |
| 5.17    | 1         | 1.39%   |
| 5.16    | 1         | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 72        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 70        | 97.22%  |
| GNOME  | 2         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 70        | 97.22%  |
| Wayland | 2         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 47        | 65.28%  |
| Unknown | 18        | 25%     |
| GDM3    | 6         | 8.33%   |
| GDM     | 1         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 28        | 38.89%  |
| de_DE | 10        | 13.89%  |
| fr_FR | 9         | 12.5%   |
| pt_BR | 5         | 6.94%   |
| en_GB | 3         | 4.17%   |
| hu_HU | 2         | 2.78%   |
| es_MX | 2         | 2.78%   |
| es_ES | 2         | 2.78%   |
| en_CA | 2         | 2.78%   |
| ru_RU | 1         | 1.39%   |
| it_IT | 1         | 1.39%   |
| fr_BE | 1         | 1.39%   |
| es_PE | 1         | 1.39%   |
| es_EC | 1         | 1.39%   |
| es_CL | 1         | 1.39%   |
| en_IE | 1         | 1.39%   |
| el_GR | 1         | 1.39%   |
| C     | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 60.27%  |
| EFI  | 29        | 39.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 88.89%  |
| Overlay | 5         | 6.94%   |
| Btrfs   | 2         | 2.78%   |
| Xfs     | 1         | 1.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 48.61%  |
| GPT     | 34        | 47.22%  |
| MBR     | 3         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 81.94%  |
| Yes       | 13        | 18.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 72.6%   |
| Yes       | 20        | 27.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 11        | 15.28%  |
| Hewlett-Packard        | 10        | 13.89%  |
| Dell                   | 9         | 12.5%   |
| Gigabyte Technology    | 8         | 11.11%  |
| ASUSTek Computer       | 7         | 9.72%   |
| Apple                  | 5         | 6.94%   |
| MSI                    | 4         | 5.56%   |
| TUXEDO                 | 3         | 4.17%   |
| Intel                  | 2         | 2.78%   |
| Google                 | 2         | 2.78%   |
| Toshiba                | 1         | 1.39%   |
| Timi                   | 1         | 1.39%   |
| Samsung Electronics    | 1         | 1.39%   |
| Razer                  | 1         | 1.39%   |
| Digibras               | 1         | 1.39%   |
| Chuwi                  | 1         | 1.39%   |
| Biostar                | 1         | 1.39%   |
| AXIOO                  | 1         | 1.39%   |
| Avell High Performance | 1         | 1.39%   |
| ASRock                 | 1         | 1.39%   |
| Acer                   | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Book XUX7 Gen11                               | 1         | 1.39%   |
| TUXEDO Book BA1510                                   | 1         | 1.39%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.39%   |
| Toshiba Satellite A505                               | 1         | 1.39%   |
| Timi TM1604                                          | 1         | 1.39%   |
| Samsung 740U3M                                       | 1         | 1.39%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.39%   |
| MSI MS-7B86                                          | 1         | 1.39%   |
| MSI MS-7A32                                          | 1         | 1.39%   |
| MSI Modern 15 A10M                                   | 1         | 1.39%   |
| MSI GL62 6QF                                         | 1         | 1.39%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.39%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.39%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.39%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.39%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.39%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.39%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.39%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.39%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.39%   |
| Lenovo G500 20236                                    | 1         | 1.39%   |
| Lenovo G50-45 80E3                                   | 1         | 1.39%   |
| Intel STK1A32SC                                      | 1         | 1.39%   |
| Intel DP55WB AAE64798-206                            | 1         | 1.39%   |
| HP Z440 Workstation                                  | 1         | 1.39%   |
| HP Spectre x360 Convertible 15t-df100                | 1         | 1.39%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.39%   |
| HP Pavilion g6                                       | 1         | 1.39%   |
| HP ENVY 17                                           | 1         | 1.39%   |
| HP ElitePad 1000 G2                                  | 1         | 1.39%   |
| HP EliteDesk 800 G1 DM                               | 1         | 1.39%   |
| HP EliteBook 840 G3                                  | 1         | 1.39%   |
| HP All-in-One 22-c0xx                                | 1         | 1.39%   |
| HP 750-417c                                          | 1         | 1.39%   |
| Google Rabbid                                        | 1         | 1.39%   |
| Google Boten                                         | 1         | 1.39%   |
| Gigabyte X570S AORUS PRO AX                          | 1         | 1.39%   |
| Gigabyte M68MT-S2                                    | 1         | 1.39%   |
| Gigabyte GA-890GPA-UD3H                              | 1         | 1.39%   |
| Gigabyte F2A78M-HD2                                  | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 5         | 6.94%   |
| Lenovo IdeaPad          | 4         | 5.56%   |
| Dell Inspiron           | 3         | 4.17%   |
| TUXEDO Book             | 2         | 2.78%   |
| Dell Latitude           | 2         | 2.78%   |
| ASUS VivoBook           | 2         | 2.78%   |
| TUXEDO Aura             | 1         | 1.39%   |
| Toshiba Satellite       | 1         | 1.39%   |
| Timi TM1604             | 1         | 1.39%   |
| Samsung 740U3M          | 1         | 1.39%   |
| Razer Blade             | 1         | 1.39%   |
| MSI MS-7B86             | 1         | 1.39%   |
| MSI MS-7A32             | 1         | 1.39%   |
| MSI Modern              | 1         | 1.39%   |
| MSI GL62                | 1         | 1.39%   |
| Lenovo G500             | 1         | 1.39%   |
| Lenovo G50-45           | 1         | 1.39%   |
| Intel STK1A32SC         | 1         | 1.39%   |
| Intel DP55WB            | 1         | 1.39%   |
| HP Z440                 | 1         | 1.39%   |
| HP Spectre              | 1         | 1.39%   |
| HP ProBook              | 1         | 1.39%   |
| HP Pavilion             | 1         | 1.39%   |
| HP ENVY                 | 1         | 1.39%   |
| HP ElitePad             | 1         | 1.39%   |
| HP EliteDesk            | 1         | 1.39%   |
| HP EliteBook            | 1         | 1.39%   |
| HP All-in-One           | 1         | 1.39%   |
| HP 750-417c             | 1         | 1.39%   |
| Google Rabbid           | 1         | 1.39%   |
| Google Boten            | 1         | 1.39%   |
| Gigabyte X570S          | 1         | 1.39%   |
| Gigabyte M68MT-S2       | 1         | 1.39%   |
| Gigabyte GA-890GPA-UD3H | 1         | 1.39%   |
| Gigabyte F2A78M-HD2     | 1         | 1.39%   |
| Gigabyte B75M-D3P       | 1         | 1.39%   |
| Gigabyte B75M-D3H       | 1         | 1.39%   |
| Gigabyte B550           | 1         | 1.39%   |
| Gigabyte B450           | 1         | 1.39%   |
| Digibras NH4CU03        | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 15.28%  |
| 2020 | 9         | 12.5%   |
| 2019 | 7         | 9.72%   |
| 2018 | 7         | 9.72%   |
| 2016 | 6         | 8.33%   |
| 2014 | 6         | 8.33%   |
| 2010 | 5         | 6.94%   |
| 2013 | 4         | 5.56%   |
| 2017 | 3         | 4.17%   |
| 2015 | 3         | 4.17%   |
| 2011 | 3         | 4.17%   |
| 2009 | 3         | 4.17%   |
| 2012 | 2         | 2.78%   |
| 2008 | 2         | 2.78%   |
| 2022 | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 46        | 63.89%  |
| Desktop     | 20        | 27.78%  |
| Convertible | 3         | 4.17%   |
| All in one  | 2         | 2.78%   |
| Mini pc     | 1         | 1.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 70        | 97.22%  |
| Enabled  | 2         | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 97.22%  |
| Yes  | 2         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 30.56%  |
| 16.01-24.0  | 22        | 30.56%  |
| 8.01-16.0   | 13        | 18.06%  |
| 3.01-4.0    | 7         | 9.72%   |
| 32.01-64.0  | 4         | 5.56%   |
| 64.01-256.0 | 2         | 2.78%   |
| 1.01-2.0    | 2         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 28        | 38.36%  |
| 2.01-3.0   | 22        | 30.14%  |
| 4.01-8.0   | 14        | 19.18%  |
| 3.01-4.0   | 5         | 6.85%   |
| 8.01-16.0  | 3         | 4.11%   |
| 24.01-32.0 | 1         | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 53.42%  |
| 2      | 24        | 32.88%  |
| 3      | 5         | 6.85%   |
| 4      | 3         | 4.11%   |
| 6      | 2         | 2.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 73.61%  |
| Yes       | 19        | 26.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 76.39%  |
| No        | 17        | 23.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 86.11%  |
| No        | 10        | 13.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 69.44%  |
| No        | 22        | 30.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 18        | 25%     |
| Germany            | 9         | 12.5%   |
| France             | 8         | 11.11%  |
| Brazil             | 6         | 8.33%   |
| UK                 | 2         | 2.78%   |
| Slovenia           | 2         | 2.78%   |
| Mexico             | 2         | 2.78%   |
| Hungary            | 2         | 2.78%   |
| Greece             | 2         | 2.78%   |
| Canada             | 2         | 2.78%   |
| Switzerland        | 1         | 1.39%   |
| Sweden             | 1         | 1.39%   |
| Spain              | 1         | 1.39%   |
| Russia             | 1         | 1.39%   |
| Peru               | 1         | 1.39%   |
| Norway             | 1         | 1.39%   |
| Italy              | 1         | 1.39%   |
| Ireland            | 1         | 1.39%   |
| Indonesia          | 1         | 1.39%   |
| Ghana              | 1         | 1.39%   |
| Ecuador            | 1         | 1.39%   |
| Dominican Republic | 1         | 1.39%   |
| Croatia            | 1         | 1.39%   |
| Chile              | 1         | 1.39%   |
| Cabo Verde         | 1         | 1.39%   |
| Belgium            | 1         | 1.39%   |
| Austria            | 1         | 1.39%   |
| Argentina          | 1         | 1.39%   |
| Algeria            | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milwaukee             | 2         | 2.78%   |
| Budapest              | 2         | 2.78%   |
| Athens                | 2         | 2.78%   |
| West Lafayette        | 1         | 1.39%   |
| Wertheim am Main      | 1         | 1.39%   |
| Walled Lake           | 1         | 1.39%   |
| Vienna                | 1         | 1.39%   |
| Victoria              | 1         | 1.39%   |
| Trondheim             | 1         | 1.39%   |
| Tocantins             | 1         | 1.39%   |
| Tarakan               | 1         | 1.39%   |
| Tampa                 | 1         | 1.39%   |
| Sunnyvale             | 1         | 1.39%   |
| St Petersburg         | 1         | 1.39%   |
| Siegen                | 1         | 1.39%   |
| Sétif                | 1         | 1.39%   |
| Seelze                | 1         | 1.39%   |
| Sao Paulo             | 1         | 1.39%   |
| Sao Bernardo do Campo | 1         | 1.39%   |
| Santo Domingo Este    | 1         | 1.39%   |
| Santiago              | 1         | 1.39%   |
| San Luis Potosí City | 1         | 1.39%   |
| Saint-Gilles          | 1         | 1.39%   |
| Rueil-Malmaison       | 1         | 1.39%   |
| Queens                | 1         | 1.39%   |
| Pula                  | 1         | 1.39%   |
| Puebla City           | 1         | 1.39%   |
| Praia                 | 1         | 1.39%   |
| Postojna              | 1         | 1.39%   |
| Pine Island           | 1         | 1.39%   |
| Orvault               | 1         | 1.39%   |
| Nuremberg             | 1         | 1.39%   |
| New York              | 1         | 1.39%   |
| Monza                 | 1         | 1.39%   |
| Mishawaka             | 1         | 1.39%   |
| Massaranduba          | 1         | 1.39%   |
| Maribor               | 1         | 1.39%   |
| Madrid                | 1         | 1.39%   |
| Lund                  | 1         | 1.39%   |
| Lima                  | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 15        | 18     | 13.16%  |
| Seagate                        | 12        | 17     | 10.53%  |
| Unknown                        | 9         | 9      | 7.89%   |
| WDC                            | 8         | 10     | 7.02%   |
| Crucial                        | 8         | 9      | 7.02%   |
| Toshiba                        | 7         | 7      | 6.14%   |
| SK hynix                       | 5         | 5      | 4.39%   |
| Intel                          | 5         | 7      | 4.39%   |
| SanDisk                        | 4         | 5      | 3.51%   |
| Micron Technology              | 4         | 4      | 3.51%   |
| Kingston                       | 4         | 5      | 3.51%   |
| SPCC                           | 3         | 3      | 2.63%   |
| JMicron Technology             | 3         | 3      | 2.63%   |
| Phison                         | 2         | 2      | 1.75%   |
| OCZ                            | 2         | 2      | 1.75%   |
| China                          | 2         | 3      | 1.75%   |
| A-DATA Technology              | 2         | 2      | 1.75%   |
| VISIPRO                        | 1         | 1      | 0.88%   |
| Union Memory                   | 1         | 1      | 0.88%   |
| Transcend                      | 1         | 1      | 0.88%   |
| TO Exter                       | 1         | 1      | 0.88%   |
| Solid State Storage Technology | 1         | 1      | 0.88%   |
| SABRENT                        | 1         | 1      | 0.88%   |
| Realtek Semiconductor          | 1         | 1      | 0.88%   |
| PNY                            | 1         | 1      | 0.88%   |
| OWC                            | 1         | 1      | 0.88%   |
| Netac                          | 1         | 1      | 0.88%   |
| Maxtor                         | 1         | 1      | 0.88%   |
| LITEON                         | 1         | 1      | 0.88%   |
| KIOXIA                         | 1         | 1      | 0.88%   |
| HGST                           | 1         | 1      | 0.88%   |
| Hewlett-Packard                | 1         | 1      | 0.88%   |
| Corsair                        | 1         | 2      | 0.88%   |
| ASMT109x                       | 1         | 1      | 0.88%   |
| Apple                          | 1         | 1      | 0.88%   |
| Unknown                        | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                   | 2         | 1.63%   |
| Unknown SD64G  64GB                        | 2         | 1.63%   |
| Unknown SD/MMC/MS PRO 1TB                  | 2         | 1.63%   |
| Seagate ST1000LM048-2E7172 1TB             | 2         | 1.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 1.63%   |
| SanDisk SDSSDA120G 120GB                   | 2         | 1.63%   |
| Samsung SSD 870 EVO 250GB                  | 2         | 1.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB     | 2         | 1.63%   |
| JMicron Generic 500GB                      | 2         | 1.63%   |
| Crucial CT240BX500SSD1 240GB               | 2         | 1.63%   |
| Crucial CT1000MX500SSD1 1TB                | 2         | 1.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB               | 1         | 0.81%   |
| WDC WD40PURZ-85TTDY0 4TB                   | 1         | 0.81%   |
| WDC WD1600AAJS-60WAA0 160GB                | 1         | 0.81%   |
| WDC WD10EARS-00Y5B1 1TB                    | 1         | 0.81%   |
| WDC WD10EADS-00M2B0 1TB                    | 1         | 0.81%   |
| WDC PC SN730 NVMe 256GB                    | 1         | 0.81%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB       | 1         | 0.81%   |
| VISIPRO SSD 256GB                          | 1         | 0.81%   |
| Unknown SL128  128GB                       | 1         | 0.81%   |
| Unknown SA16G  16GB                        | 1         | 0.81%   |
| Unknown NCard  4GB                         | 1         | 0.81%   |
| Unknown MMC128  128GB                      | 1         | 0.81%   |
| Unknown MMC Card  64GB                     | 1         | 0.81%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD     | 1         | 0.81%   |
| Transcend TS128GMTE110S 128GB              | 1         | 0.81%   |
| Toshiba TR150 480GB SSD                    | 1         | 0.81%   |
| Toshiba KXG50ZNV512G NVMe 512GB            | 1         | 0.81%   |
| Toshiba KBG40ZNT256G MEMORY 256GB          | 1         | 0.81%   |
| Toshiba KBG30ZMT256G 256GB                 | 1         | 0.81%   |
| Toshiba HDWD240 4TB                        | 1         | 0.81%   |
| Toshiba HDWD220 2TB                        | 1         | 0.81%   |
| Toshiba DT01ACA100 1TB                     | 1         | 0.81%   |
| TO Exter nal USB 3.0 1TB                   | 1         | 0.81%   |
| SPCC Solid State Disk 256GB                | 1         | 0.81%   |
| SPCC Solid State Disk 120GB                | 1         | 0.81%   |
| SPCC M.2 PCIe SSD 256GB                    | 1         | 0.81%   |
| Solid State Storage NVMe CA6-8D1024 1024GB | 1         | 0.81%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB  | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 16     | 41.38%  |
| WDC                 | 6         | 7      | 20.69%  |
| Toshiba             | 3         | 3      | 10.34%  |
| Unknown             | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 3      | 6.9%    |
| SABRENT             | 1         | 1      | 3.45%   |
| Maxtor              | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| ASMT109x            | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 8         | 9      | 20%     |
| Samsung Electronics | 7         | 8      | 17.5%   |
| SPCC                | 2         | 2      | 5%      |
| SanDisk             | 2         | 2      | 5%      |
| Micron Technology   | 2         | 2      | 5%      |
| China               | 2         | 3      | 5%      |
| WDC                 | 1         | 1      | 2.5%    |
| VISIPRO             | 1         | 1      | 2.5%    |
| Union Memory        | 1         | 1      | 2.5%    |
| Toshiba             | 1         | 1      | 2.5%    |
| TO Exter            | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| OWC                 | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 2      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| Corsair             | 1         | 2      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 35        | 45     | 36.08%  |
| NVMe    | 30        | 39     | 30.93%  |
| HDD     | 22        | 35     | 22.68%  |
| MMC     | 9         | 11     | 9.28%   |
| Unknown | 1         | 1      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 75     | 50.55%  |
| NVMe | 29        | 37     | 31.87%  |
| MMC  | 9         | 11     | 9.89%   |
| SAS  | 7         | 8      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 54     | 64.52%  |
| 0.51-1.0   | 14        | 17     | 22.58%  |
| 1.01-2.0   | 5         | 6      | 8.06%   |
| 3.01-4.0   | 3         | 3      | 4.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 36.11%  |
| 251-500        | 18        | 25%     |
| 51-100         | 9         | 12.5%   |
| 501-1000       | 6         | 8.33%   |
| 1001-2000      | 5         | 6.94%   |
| 21-50          | 3         | 4.17%   |
| 1-20           | 3         | 4.17%   |
| More than 3000 | 2         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 20        | 27.78%  |
| 1-20      | 20        | 27.78%  |
| 51-100    | 12        | 16.67%  |
| 101-250   | 10        | 13.89%  |
| 251-500   | 5         | 6.94%   |
| 501-1000  | 3         | 4.17%   |
| 2001-3000 | 1         | 1.39%   |
| 1001-2000 | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 48        | 83     | 60%     |
| Works    | 30        | 46     | 37.5%   |
| Malfunc  | 2         | 2      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 41        | 46.59%  |
| AMD                            | 14        | 15.91%  |
| Samsung Electronics            | 6         | 6.82%   |
| SanDisk                        | 3         | 3.41%   |
| Nvidia                         | 3         | 3.41%   |
| Kingston Technology Company    | 3         | 3.41%   |
| Toshiba America Info Systems   | 2         | 2.27%   |
| SK hynix                       | 2         | 2.27%   |
| Phison Electronics             | 2         | 2.27%   |
| Micron Technology              | 2         | 2.27%   |
| KIOXIA                         | 2         | 2.27%   |
| Transcend                      | 1         | 1.14%   |
| Solid State Storage Technology | 1         | 1.14%   |
| Seagate Technology             | 1         | 1.14%   |
| Realtek Semiconductor          | 1         | 1.14%   |
| OCZ Technology Group           | 1         | 1.14%   |
| Marvell Technology Group       | 1         | 1.14%   |
| JMicron Technology             | 1         | 1.14%   |
| ADATA Technology               | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 9%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 6%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 3%      |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3%      |
| Intel Non-Volatile memory controller                                             | 3         | 3%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3%      |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 2%      |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 2%      |
| Micron Non-Volatile memory controller                                            | 2         | 2%      |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 2%      |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 2%      |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2%      |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 2%      |
| Transcend Non-Volatile memory controller                                         | 1         | 1%      |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 1%      |
| Solid State Storage Non-Volatile memory controller                               | 1         | 1%      |
| SK hynix Non-Volatile memory controller                                          | 1         | 1%      |
| SK hynix Gold P31 SSD                                                            | 1         | 1%      |
| Seagate Non-Volatile memory controller                                           | 1         | 1%      |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1         | 1%      |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1%      |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1%      |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1%      |
| OCZ Group RD400/400A SSD                                                         | 1         | 1%      |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1%      |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 1%      |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1%      |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1%      |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1%      |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 53.33%  |
| NVMe | 29        | 32.22%  |
| IDE  | 8         | 8.89%   |
| RAID | 5         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 55        | 76.39%  |
| AMD    | 17        | 23.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 2.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 2.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.78%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.78%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 2.78%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 1.39%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.39%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.39%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.39%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.39%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 1.39%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 1.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.39%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.39%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 1.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.39%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.39%   |
| Intel Core i3-3225 CPU @ 3.30GHz              | 1         | 1.39%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.39%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.39%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 1         | 1.39%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 19        | 26.39%  |
| Other                | 8         | 11.11%  |
| Intel Core i7        | 8         | 11.11%  |
| AMD Ryzen 5          | 7         | 9.72%   |
| Intel Celeron        | 5         | 6.94%   |
| Intel Atom           | 4         | 5.56%   |
| Intel Core i3        | 3         | 4.17%   |
| Intel Core 2 Duo     | 3         | 4.17%   |
| AMD Ryzen 7          | 2         | 2.78%   |
| Intel Xeon           | 1         | 1.39%   |
| Intel Pentium Silver | 1         | 1.39%   |
| Intel Pentium        | 1         | 1.39%   |
| Intel Core i9        | 1         | 1.39%   |
| Intel Core 2 Quad    | 1         | 1.39%   |
| AMD Ryzen 9          | 1         | 1.39%   |
| AMD Phenom II X4     | 1         | 1.39%   |
| AMD FX               | 1         | 1.39%   |
| AMD Athlon II X3     | 1         | 1.39%   |
| AMD Athlon           | 1         | 1.39%   |
| AMD A8               | 1         | 1.39%   |
| AMD A4               | 1         | 1.39%   |
| AMD A10              | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 34        | 47.22%  |
| 2      | 26        | 36.11%  |
| 8      | 4         | 5.56%   |
| 6      | 4         | 5.56%   |
| 12     | 1         | 1.39%   |
| 10     | 1         | 1.39%   |
| 3      | 1         | 1.39%   |
| 1      | 1         | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 68.06%  |
| 1      | 23        | 31.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 72        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 50.68%  |
| 0x806c1    | 3         | 4.11%   |
| 0x206a7    | 3         | 4.11%   |
| 0x08108102 | 3         | 4.11%   |
| 0x806ec    | 2         | 2.74%   |
| 0x706a8    | 2         | 2.74%   |
| 0x306a9    | 2         | 2.74%   |
| 0x0a50000c | 2         | 2.74%   |
| 0x08600106 | 2         | 2.74%   |
| 0xa0671    | 1         | 1.37%   |
| 0x906eb    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x806d1    | 1         | 1.37%   |
| 0x506c9    | 1         | 1.37%   |
| 0x406f1    | 1         | 1.37%   |
| 0x406c4    | 1         | 1.37%   |
| 0x40651    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x30678    | 1         | 1.37%   |
| 0x20655    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x1067a    | 1         | 1.37%   |
| 0x10677    | 1         | 1.37%   |
| 0x08108109 | 1         | 1.37%   |
| 0x07030104 | 1         | 1.37%   |
| 0x06001119 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 18.06%  |
| Zen+          | 6         | 8.33%   |
| TigerLake     | 5         | 6.94%   |
| IvyBridge     | 5         | 6.94%   |
| Silvermont    | 4         | 5.56%   |
| Penryn        | 4         | 5.56%   |
| Zen 3         | 3         | 4.17%   |
| Skylake       | 3         | 4.17%   |
| SandyBridge   | 3         | 4.17%   |
| Icelake       | 3         | 4.17%   |
| Haswell       | 3         | 4.17%   |
| Goldmont plus | 3         | 4.17%   |
| Zen 2         | 2         | 2.78%   |
| Nehalem       | 2         | 2.78%   |
| K10           | 2         | 2.78%   |
| Broadwell     | 2         | 2.78%   |
| Unknown       | 2         | 2.78%   |
| Westmere      | 1         | 1.39%   |
| Steamroller   | 1         | 1.39%   |
| Puma          | 1         | 1.39%   |
| Piledriver    | 1         | 1.39%   |
| Goldmont      | 1         | 1.39%   |
| CometLake     | 1         | 1.39%   |
| Bulldozer     | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 55.29%  |
| Nvidia | 19        | 22.35%  |
| AMD    | 19        | 22.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 5.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 5.75%   |
| Intel UHD Graphics 620                                                      | 4         | 4.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 3.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 2.3%    |
| Intel HD Graphics 620                                                       | 2         | 2.3%    |
| Intel HD Graphics 530                                                       | 2         | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.3%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.3%    |
| AMD Renoir                                                                  | 2         | 2.3%    |
| AMD Cezanne                                                                 | 2         | 2.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 2.3%    |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                      | 1         | 1.15%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 1.15%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.15%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 1.15%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.15%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1         | 1.15%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 1.15%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.15%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1.15%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 1.15%   |
| Nvidia GF110 [GeForce GTX 570]                                              | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 1.15%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                          | 1         | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.15%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 1.15%   |
| Nvidia C79 [GeForce 9400]                                                   | 1         | 1.15%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 1.15%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.15%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 45.83%  |
| 1 x AMD        | 15        | 20.83%  |
| 1 x Nvidia     | 9         | 12.5%   |
| Intel + Nvidia | 9         | 12.5%   |
| Intel + AMD    | 2         | 2.78%   |
| Other          | 1         | 1.39%   |
| 2 x Intel      | 1         | 1.39%   |
| 2 x AMD        | 1         | 1.39%   |
| AMD + Nvidia   | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 84.72%  |
| Proprietary | 9         | 12.5%   |
| Unknown     | 2         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 73.61%  |
| 1.01-2.0   | 7         | 9.72%   |
| 0.01-0.5   | 5         | 6.94%   |
| 7.01-8.0   | 3         | 4.17%   |
| 0.51-1.0   | 3         | 4.17%   |
| 3.01-4.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 17.72%  |
| Samsung Electronics     | 13        | 16.46%  |
| BOE                     | 10        | 12.66%  |
| AU Optronics            | 7         | 8.86%   |
| LG Display              | 4         | 5.06%   |
| Hewlett-Packard         | 4         | 5.06%   |
| Apple                   | 4         | 5.06%   |
| Sharp                   | 3         | 3.8%    |
| Philips                 | 3         | 3.8%    |
| SANYO                   | 2         | 2.53%   |
| Goldstar                | 2         | 2.53%   |
| Vestel Elektronik       | 1         | 1.27%   |
| Unknown (XXX)           | 1         | 1.27%   |
| Unknown (AAA)           | 1         | 1.27%   |
| Sony                    | 1         | 1.27%   |
| ONN                     | 1         | 1.27%   |
| MStar                   | 1         | 1.27%   |
| Lenovo                  | 1         | 1.27%   |
| IBM                     | 1         | 1.27%   |
| Fujitsu Siemens         | 1         | 1.27%   |
| Dell                    | 1         | 1.27%   |
| Chi Mei Optoelectronics | 1         | 1.27%   |
| BenQ                    | 1         | 1.27%   |
| AOC                     | 1         | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 2.5%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 1.25%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 1.25%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 1.25%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 1.25%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 1.25%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 1.25%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 1.25%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 1.25%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 1.25%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 1.25%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 1.25%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 1.25%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 1.25%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 1.25%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 1.25%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 1.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 1.25%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 1.25%   |
| Philips PHL 241B7Q PHL0909 1920x1080 530x300mm 24.0-inch               | 1         | 1.25%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                | 1         | 1.25%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                    | 1         | 1.25%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                        | 1         | 1.25%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 1.25%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch            | 1         | 1.25%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch               | 1         | 1.25%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                  | 1         | 1.25%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 1         | 1.25%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch             | 1         | 1.25%   |
| Hewlett-Packard ALL-in-One HPN401E 1920x1080 476x268mm 21.5-inch       | 1         | 1.25%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch              | 1         | 1.25%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 43.42%  |
| 1366x768 (WXGA)    | 15        | 19.74%  |
| 3840x2160 (4K)     | 5         | 6.58%   |
| 1920x1200 (WUXGA)  | 4         | 5.26%   |
| 2560x1440 (QHD)    | 3         | 3.95%   |
| 1680x1050 (WSXGA+) | 3         | 3.95%   |
| 1600x900 (HD+)     | 3         | 3.95%   |
| 1280x800 (WXGA)    | 3         | 3.95%   |
| 1920x540           | 2         | 2.63%   |
| 2880x1800          | 1         | 1.32%   |
| 2560x1600          | 1         | 1.32%   |
| 1440x900 (WXGA+)   | 1         | 1.32%   |
| 1360x768           | 1         | 1.32%   |
| 1280x1024 (SXGA)   | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 26.25%  |
| 13      | 12        | 15%     |
| 27      | 6         | 7.5%    |
| 24      | 6         | 7.5%    |
| 21      | 5         | 6.25%   |
| 14      | 5         | 6.25%   |
| 23      | 4         | 5%      |
| 17      | 4         | 5%      |
| 11      | 3         | 3.75%   |
| Unknown | 3         | 3.75%   |
| 40      | 2         | 2.5%    |
| 84      | 1         | 1.25%   |
| 72      | 1         | 1.25%   |
| 54      | 1         | 1.25%   |
| 47      | 1         | 1.25%   |
| 33      | 1         | 1.25%   |
| 31      | 1         | 1.25%   |
| 26      | 1         | 1.25%   |
| 18      | 1         | 1.25%   |
| 10      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 39.24%  |
| 501-600     | 15        | 18.99%  |
| 201-300     | 10        | 12.66%  |
| 401-500     | 7         | 8.86%   |
| 351-400     | 5         | 6.33%   |
| Unknown     | 3         | 3.8%    |
| 801-900     | 2         | 2.53%   |
| 1501-2000   | 2         | 2.53%   |
| 1001-1500   | 2         | 2.53%   |
| 701-800     | 1         | 1.27%   |
| 601-700     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 57        | 79.17%  |
| 16/10   | 12        | 16.67%  |
| 32/9    | 1         | 1.39%   |
| 3/2     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 26.92%  |
| 81-90          | 13        | 16.67%  |
| 201-250        | 10        | 12.82%  |
| 301-350        | 6         | 7.69%   |
| 71-80          | 4         | 5.13%   |
| 121-130        | 4         | 5.13%   |
| More than 1000 | 3         | 3.85%   |
| 51-60          | 3         | 3.85%   |
| 251-300        | 3         | 3.85%   |
| 501-1000       | 3         | 3.85%   |
| Unknown        | 3         | 3.85%   |
| 351-500        | 2         | 2.56%   |
| 41-50          | 1         | 1.28%   |
| 151-200        | 1         | 1.28%   |
| 141-150        | 1         | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 26.92%  |
| 51-100        | 19        | 24.36%  |
| 101-120       | 18        | 23.08%  |
| 161-240       | 8         | 10.26%  |
| 1-50          | 5         | 6.41%   |
| More than 240 | 4         | 5.13%   |
| Unknown       | 3         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 84.72%  |
| 2     | 10        | 13.89%  |
| 0     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 36.54%  |
| Realtek Semiconductor | 36        | 34.62%  |
| Qualcomm Atheros      | 9         | 8.65%   |
| Broadcom              | 8         | 7.69%   |
| Nvidia                | 3         | 2.88%   |
| MediaTek              | 3         | 2.88%   |
| Hewlett-Packard       | 2         | 1.92%   |
| Broadcom Limited      | 2         | 1.92%   |
| Ralink Technology     | 1         | 0.96%   |
| Huawei Technologies   | 1         | 0.96%   |
| ASIX Electronics      | 1         | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 21        | 17.36%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 4.13%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.31%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.48%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 1.65%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.65%   |
| Intel Wireless 8260                                                     | 2         | 1.65%   |
| Intel Wireless 7265                                                     | 2         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.65%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.65%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.83%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.83%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.83%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.83%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.83%   |
| Intel Wireless 7260                                                     | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 49.21%  |
| Realtek Semiconductor | 11        | 17.46%  |
| Broadcom              | 8         | 12.7%   |
| Qualcomm Atheros      | 7         | 11.11%  |
| MediaTek              | 3         | 4.76%   |
| Ralink Technology     | 1         | 1.59%   |
| Hewlett-Packard       | 1         | 1.59%   |
| Broadcom Limited      | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 5         | 7.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 6.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 6.35%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 6.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 4.76%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.17%   |
| Intel Wireless 8260                                                     | 2         | 3.17%   |
| Intel Wireless 7265                                                     | 2         | 3.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 3.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 3.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.59%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.59%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.59%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.59%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.59%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.59%   |
| Intel Wireless 7260                                                     | 1         | 1.59%   |
| Intel Wireless 3165                                                     | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.59%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.59%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.59%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 57.14%  |
| Intel                 | 13        | 23.21%  |
| Nvidia                | 3         | 5.36%   |
| Broadcom              | 3         | 5.36%   |
| Qualcomm Atheros      | 2         | 3.57%   |
| Hewlett-Packard       | 1         | 1.79%   |
| Broadcom Limited      | 1         | 1.79%   |
| ASIX Electronics      | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 36.84%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 8.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.02%   |
| Nvidia MCP79 Ethernet                                             | 2         | 3.51%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.75%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.75%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.75%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.75%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.75%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 1         | 1.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.75%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 52.54%  |
| Ethernet | 55        | 46.61%  |
| Modem    | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 70.83%  |
| Ethernet | 21        | 29.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 52.78%  |
| 1     | 30        | 41.67%  |
| 0     | 4         | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 71.23%  |
| Yes  | 21        | 28.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 52%     |
| Apple                           | 5         | 10%     |
| Realtek Semiconductor           | 4         | 8%      |
| Qualcomm Atheros Communications | 4         | 8%      |
| Broadcom                        | 3         | 6%      |
| IMC Networks                    | 2         | 4%      |
| Dell                            | 2         | 4%      |
| Unknown                         | 1         | 2%      |
| MediaTek                        | 1         | 2%      |
| Foxconn International           | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 16%     |
| Intel AX201 Bluetooth                               | 7         | 14%     |
| Intel AX200 Bluetooth                               | 4         | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 6%      |
| Apple Bluetooth USB Host Controller                 | 3         | 6%      |
| Realtek Bluetooth Radio                             | 2         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4%      |
| Intel AX210 Bluetooth                               | 2         | 4%      |
| Dell DW375 Bluetooth Module                         | 2         | 4%      |
| Apple Bluetooth Host Controller                     | 2         | 4%      |
| Unknown Bluetooth Device                            | 1         | 2%      |
| Realtek RTL8723B Bluetooth                          | 1         | 2%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2%      |
| MediaTek Wireless_Device                            | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2%      |
| IMC Networks Wireless_Device                        | 1         | 2%      |
| IMC Networks Bluetooth Radio                        | 1         | 2%      |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 59.76%  |
| AMD                   | 19        | 23.17%  |
| Nvidia                | 11        | 13.41%  |
| Texas Instruments     | 1         | 1.22%   |
| Realtek Semiconductor | 1         | 1.22%   |
| Plantronics           | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 9%      |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 8%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 5%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3%      |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 3%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3%      |
| AMD FCH Azalia Controller                                                  | 3         | 3%      |
| Nvidia MCP79 High Definition Audio                                         | 2         | 2%      |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2%      |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 1%      |
| Realtek Semiconductor USB Audio                                            | 1         | 1%      |
| Plantronics Blackwire 5220 Series                                          | 1         | 1%      |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1%      |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1%      |
| Nvidia High Definition Audio Controller                                    | 1         | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1%      |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1%      |
| Intel Jasper Lake HD Audio                                                 | 1         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1%      |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 1         | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 25.49%  |
| Samsung Electronics | 11        | 21.57%  |
| Kingston            | 7         | 13.73%  |
| Crucial             | 4         | 7.84%   |
| Micron Technology   | 3         | 5.88%   |
| Unknown (ABCD)      | 2         | 3.92%   |
| Ramaxel Technology  | 2         | 3.92%   |
| Elpida              | 2         | 3.92%   |
| Unknown             | 1         | 1.96%   |
| Transcend           | 1         | 1.96%   |
| Teikon              | 1         | 1.96%   |
| fef5                | 1         | 1.96%   |
| Corsair             | 1         | 1.96%   |
| A-DATA Technology   | 1         | 1.96%   |
| Unknown             | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.7%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 3.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.85%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.85%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.85%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.85%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.85%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.85%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.85%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.85%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.85%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.85%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.85%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.85%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s             | 1         | 1.85%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 1.85%   |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s                | 1         | 1.85%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 50%     |
| DDR3    | 13        | 30.95%  |
| LPDDR4  | 6         | 14.29%  |
| SDRAM   | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 67.5%   |
| DIMM         | 8         | 20%     |
| Row Of Chips | 3         | 7.5%    |
| Chip         | 1         | 2.5%    |
| Unknown      | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 18        | 42.86%  |
| 4096  | 13        | 30.95%  |
| 16384 | 5         | 11.9%   |
| 2048  | 4         | 9.52%   |
| 32768 | 1         | 2.38%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 9         | 20%     |
| 3200  | 8         | 17.78%  |
| 2667  | 8         | 17.78%  |
| 2400  | 7         | 15.56%  |
| 1333  | 3         | 6.67%   |
| 4267  | 2         | 4.44%   |
| 1067  | 2         | 4.44%   |
| 1066  | 2         | 4.44%   |
| 3600  | 1         | 2.22%   |
| 3266  | 1         | 2.22%   |
| 2133  | 1         | 2.22%   |
| 1334  | 1         | 2.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 33.33%  |
| HP LaserJet 1320              | 1         | 33.33%  |
| Canon LiDE 400                | 1         | 33.33%  |

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
| Chicony Electronics                    | 11        | 24.44%  |
| IMC Networks                           | 6         | 13.33%  |
| Realtek Semiconductor                  | 4         | 8.89%   |
| Apple                                  | 4         | 8.89%   |
| Syntek                                 | 3         | 6.67%   |
| Sunplus Innovation Technology          | 3         | 6.67%   |
| Microdia                               | 2         | 4.44%   |
| Logitech                               | 2         | 4.44%   |
| Acer                                   | 2         | 4.44%   |
| Unknown                                | 1         | 2.22%   |
| Samsung Electronics                    | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Polycom                                | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |
| Alcor Micro                            | 1         | 2.22%   |
| Unknown                                | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 3         | 6.67%   |
| Syntek Integrated Camera                                       | 2         | 4.44%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 4.44%   |
| Logitech HD Pro Webcam C920                                    | 2         | 4.44%   |
| Chicony Integrated Camera                                      | 2         | 4.44%   |
| Apple FaceTime HD Camera                                       | 2         | 4.44%   |
| Unknown ATIV VGA CAMERA                                        | 1         | 2.22%   |
| Syntek Lenovo EasyCamera                                       | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2.22%   |
| Sunplus HD WebCam                                              | 1         | 2.22%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.22%   |
| Realtek Lenovo EasyCamera                                      | 1         | 2.22%   |
| Realtek Integrated Webcam                                      | 1         | 2.22%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 2.22%   |
| Polycom Poly Studio P5 webcam                                  | 1         | 2.22%   |
| Microdia Integrated Webcam HD                                  | 1         | 2.22%   |
| Microdia Camera                                                | 1         | 2.22%   |
| Luxvisions Innotech Limited HP HD Camera                       | 1         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 2.22%   |
| IMC Networks Integrated RGB Camera                             | 1         | 2.22%   |
| Chicony XiaoMi USB 2.0 Webcam                                  | 1         | 2.22%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 2.22%   |
| Chicony USB2.0 UVC WebCam                                      | 1         | 2.22%   |
| Chicony USB2.0 Camera                                          | 1         | 2.22%   |
| Chicony HP Wide Vision FHD Camera                              | 1         | 2.22%   |
| Chicony HP Truevision HD camera                                | 1         | 2.22%   |
| Chicony HP Integrated Webcam                                   | 1         | 2.22%   |
| Chicony HP HD Camera                                           | 1         | 2.22%   |
| Chicony HD Webcam                                              | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.22%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 2.22%   |
| Apple Built-in iSight                                          | 1         | 2.22%   |
| Alcor Micro USB 2.0 WebCamera                                  | 1         | 2.22%   |
| Acer SunplusIT Integrated Camera                               | 1         | 2.22%   |
| Acer EasyCamera                                                | 1         | 2.22%   |
| Unknown                                                        | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 40%     |
| Shenzhen Goodix Technology | 3         | 30%     |
| Validity Sensors           | 2         | 20%     |
| Elan Microelectronics      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 2         | 20%     |
| Unknown                                           | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                | 1         | 10%     |
| Elan ELAN:Fingerprint                             | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 70.83%  |
| 1     | 15        | 20.83%  |
| 2     | 3         | 4.17%   |
| 6     | 1         | 1.39%   |
| 4     | 1         | 1.39%   |
| 3     | 1         | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 31.03%  |
| Net/wireless             | 4         | 13.79%  |
| Graphics card            | 4         | 13.79%  |
| Sound                    | 3         | 10.34%  |
| Chipcard                 | 2         | 6.9%    |
| Camera                   | 2         | 6.9%    |
| Unassigned class         | 1         | 3.45%   |
| Net/ethernet             | 1         | 3.45%   |
| Multimedia controller    | 1         | 3.45%   |
| Communication controller | 1         | 3.45%   |
| Bluetooth                | 1         | 3.45%   |


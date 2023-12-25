Lilidog - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lilidog.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lilidog/Desktop/README.md) and [notebooks](/Dist/Lilidog/Notebook/README.md).

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

Total: 72

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite Pro L450          | Notebook    | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Acer          | AOD270                      | Notebook    | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Sony          | VPCF23P1E                   | Notebook    | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| Google        | Sand                        | Notebook    | [97e4755fe5](https://linux-hardware.org/?probe=97e4755fe5) | Nov 07, 2023 |
| Dell          | Inspiron 1318               | Notebook    | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [5dab721f9a](https://linux-hardware.org/?probe=5dab721f9a) | Aug 21, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | Notebook    | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | Notebook    | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | Notebook    | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | Notebook    | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [bd50784a0b](https://linux-hardware.org/?probe=bd50784a0b) | May 05, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4d91f9900d](https://linux-hardware.org/?probe=4d91f9900d) | Apr 25, 2023 |
| Dell          | 0GM819                      | Desktop     | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Google        | Sand                        | Notebook    | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| HP            | 805B                        | Desktop     | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [b74e119c7e](https://linux-hardware.org/?probe=b74e119c7e) | Nov 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar       | A320MH                      | Desktop     | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | Notebook    | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [209e0387a9](https://linux-hardware.org/?probe=209e0387a9) | Aug 27, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [5bfd5ddd59](https://linux-hardware.org/?probe=5bfd5ddd59) | Aug 26, 2022 |
| HP            | 805B                        | Desktop     | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b7173a46ac](https://linux-hardware.org/?probe=b7173a46ac) | Aug 21, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c9be76cad8](https://linux-hardware.org/?probe=c9be76cad8) | Aug 21, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [de75a91d9f](https://linux-hardware.org/?probe=de75a91d9f) | Jul 09, 2022 |
| Acer          | V5-131                      | Notebook    | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | Notebook    | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | Notebook    | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Acer          | AOD255E                     | Notebook    | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| eMachines     | EL1352                      | Desktop     | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP            | 212B                        | Desktop     | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| HP            | 21EF                        | Desktop     | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0HJ054                      | Desktop     | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Lilidog 22 | 40        | 67.8%   |
| Lilidog 23 | 19        | 32.2%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-16-amd64           | 6         | 9.09%   |
| 6.1.0-9-amd64             | 5         | 7.58%   |
| 5.10.0-18-amd64           | 5         | 7.58%   |
| 5.10.0-15-amd64           | 5         | 7.58%   |
| 6.1.0-10-amd64            | 4         | 6.06%   |
| 5.10.0-13-amd64           | 4         | 6.06%   |
| 5.10.0-21-amd64           | 3         | 4.55%   |
| 5.10.0-20-amd64           | 3         | 4.55%   |
| 6.5.0-0.deb12.1-amd64     | 2         | 3.03%   |
| 6.1.0-7-amd64             | 2         | 3.03%   |
| 6.1.0-11-amd64            | 2         | 3.03%   |
| 6.0.8-x64v1-xanmod1       | 2         | 3.03%   |
| 5.10.0-14-amd64           | 2         | 3.03%   |
| 6.5.0-0.deb12.4-amd64     | 1         | 1.52%   |
| 6.4.5-1-liquorix-amd64    | 1         | 1.52%   |
| 6.4.0-0.deb12.2-amd64     | 1         | 1.52%   |
| 6.2.12-x64v1-xanmod1      | 1         | 1.52%   |
| 6.2.11-x64v1-xanmod1      | 1         | 1.52%   |
| 6.1.0-7.2-liquorix-amd64  | 1         | 1.52%   |
| 6.1.0-13-amd64            | 1         | 1.52%   |
| 6.1.0-13-686-pae          | 1         | 1.52%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 1.52%   |
| 6.0.10-x64v1-xanmod1      | 1         | 1.52%   |
| 6.0.0-5-amd64             | 1         | 1.52%   |
| 6.0.0-2-amd64             | 1         | 1.52%   |
| 6.0.0-0.deb11.6-amd64     | 1         | 1.52%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 1.52%   |
| 5.19.0-7.1-liquorix-amd64 | 1         | 1.52%   |
| 5.19.0-0.deb11.2-amd64    | 1         | 1.52%   |
| 5.18.0-1-amd64            | 1         | 1.52%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 1.52%   |
| 5.10.0-22-amd64           | 1         | 1.52%   |
| 5.10.0-19-amd64           | 1         | 1.52%   |
| 5.10.0-17-amd64           | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 46.03%  |
| 6.1.0   | 16        | 25.4%   |
| 6.0.0   | 4         | 6.35%   |
| 6.5.0   | 3         | 4.76%   |
| 6.0.8   | 2         | 3.17%   |
| 5.19.0  | 2         | 3.17%   |
| 6.4.5   | 1         | 1.59%   |
| 6.4.0   | 1         | 1.59%   |
| 6.2.12  | 1         | 1.59%   |
| 6.2.11  | 1         | 1.59%   |
| 6.0.10  | 1         | 1.59%   |
| 5.18.0  | 1         | 1.59%   |
| 5.17.0  | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 29        | 46.03%  |
| 6.1     | 16        | 25.4%   |
| 6.0     | 7         | 11.11%  |
| 6.5     | 3         | 4.76%   |
| 6.4     | 2         | 3.17%   |
| 6.2     | 2         | 3.17%   |
| 5.19    | 2         | 3.17%   |
| 5.18    | 1         | 1.59%   |
| 5.17    | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 98.25%  |
| i686   | 1         | 1.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 51        | 85%     |
| openbox          | 9         | 15%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 57        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 57        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 42        | 72.41%  |
| de_DE | 4         | 6.9%    |
| es_MX | 2         | 3.45%   |
| es_ES | 2         | 3.45%   |
| en_GB | 2         | 3.45%   |
| ru_RU | 1         | 1.72%   |
| it_IT | 1         | 1.72%   |
| es_CO | 1         | 1.72%   |
| es_CL | 1         | 1.72%   |
| en_IE | 1         | 1.72%   |
| cs_CZ | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 29        | 50.88%  |
| BIOS | 28        | 49.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 66.1%   |
| Overlay | 16        | 27.12%  |
| Btrfs   | 4         | 6.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 35        | 60.34%  |
| MBR  | 23        | 39.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 64.41%  |
| Yes       | 21        | 35.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 82.46%  |
| Yes       | 10        | 17.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 19.3%   |
| Acer                | 7         | 12.28%  |
| Lenovo              | 6         | 10.53%  |
| Hewlett-Packard     | 6         | 10.53%  |
| Apple               | 5         | 8.77%   |
| Gigabyte Technology | 3         | 5.26%   |
| ASUSTek Computer    | 3         | 5.26%   |
| Panasonic           | 2         | 3.51%   |
| Google              | 2         | 3.51%   |
| TUXEDO              | 1         | 1.75%   |
| Toshiba             | 1         | 1.75%   |
| Sony                | 1         | 1.75%   |
| Inventec            | 1         | 1.75%   |
| Intel               | 1         | 1.75%   |
| GPU Company         | 1         | 1.75%   |
| Foxconn             | 1         | 1.75%   |
| Fanless Mini PC     | 1         | 1.75%   |
| eMachines           | 1         | 1.75%   |
| Biostar             | 1         | 1.75%   |
| BANGHO              | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 3.51%   |
| TUXEDO N8xEJEK                             | 1         | 1.75%   |
| Toshiba Satellite Pro L450                 | 1         | 1.75%   |
| Sony VPCF23P1E                             | 1         | 1.75%   |
| Panasonic CFMX4-1                          | 1         | 1.75%   |
| Panasonic CF-31ATXAX1M                     | 1         | 1.75%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 1.75%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 1.75%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1         | 1.75%   |
| Lenovo G500 20236                          | 1         | 1.75%   |
| Inventec Dell Thin Client Desktop 5060     | 1         | 1.75%   |
| Intel NUC11BTMi7                           | 1         | 1.75%   |
| HP t520 Flexible Series TC                 | 1         | 1.75%   |
| HP Laptop 15s-fq1xxx                       | 1         | 1.75%   |
| HP G62                                     | 1         | 1.75%   |
| HP EliteDesk 705 G2 MINI                   | 1         | 1.75%   |
| HP All-in-One Desktop 27-cb1xxx            | 1         | 1.75%   |
| HP 435                                     | 1         | 1.75%   |
| GPU Company GWNR71517                      | 1         | 1.75%   |
| Google Sand                                | 1         | 1.75%   |
| Google Auron_Yuna                          | 1         | 1.75%   |
| Gigabyte PERSONAL COMPUTER                 | 1         | 1.75%   |
| Gigabyte B450 AORUS PRO                    | 1         | 1.75%   |
| Gigabyte B365M DS3H                        | 1         | 1.75%   |
| Foxconn NETBOX NT-425/525                  | 1         | 1.75%   |
| Fanless Mini PC Quieter 3                  | 1         | 1.75%   |
| eMachines EL1352                           | 1         | 1.75%   |
| Dell XPS 8930                              | 1         | 1.75%   |
| Dell OptiPlex 780                          | 1         | 1.75%   |
| Dell OptiPlex 755                          | 1         | 1.75%   |
| Dell OptiPlex 390                          | 1         | 1.75%   |
| Dell OptiPlex 3020                         | 1         | 1.75%   |
| Dell Latitude E5440                        | 1         | 1.75%   |
| Dell Latitude 7414                         | 1         | 1.75%   |
| Dell Latitude 7390                         | 1         | 1.75%   |
| Dell Inspiron 3793                         | 1         | 1.75%   |
| Dell Inspiron 1318                         | 1         | 1.75%   |
| Dell DM051                                 | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell OptiPlex           | 4         | 7.02%   |
| Lenovo ThinkPad         | 3         | 5.26%   |
| Dell Latitude           | 3         | 5.26%   |
| Acer Aspire             | 3         | 5.26%   |
| Dell Inspiron           | 2         | 3.51%   |
| Acer AOD255E            | 2         | 3.51%   |
| TUXEDO N8xEJEK          | 1         | 1.75%   |
| Toshiba Satellite       | 1         | 1.75%   |
| Sony VPCF23P1E          | 1         | 1.75%   |
| Panasonic CFMX4-1       | 1         | 1.75%   |
| Panasonic CF-31ATXAX1M  | 1         | 1.75%   |
| Lenovo Yoga             | 1         | 1.75%   |
| Lenovo Legion           | 1         | 1.75%   |
| Lenovo G500             | 1         | 1.75%   |
| Inventec Dell           | 1         | 1.75%   |
| Intel NUC11BTMi7        | 1         | 1.75%   |
| HP t520                 | 1         | 1.75%   |
| HP Laptop               | 1         | 1.75%   |
| HP G62                  | 1         | 1.75%   |
| HP EliteDesk            | 1         | 1.75%   |
| HP All-in-One           | 1         | 1.75%   |
| HP 435                  | 1         | 1.75%   |
| GPU Company GWNR71517   | 1         | 1.75%   |
| Google Sand             | 1         | 1.75%   |
| Google Auron            | 1         | 1.75%   |
| Gigabyte PERSONAL       | 1         | 1.75%   |
| Gigabyte B450           | 1         | 1.75%   |
| Gigabyte B365M          | 1         | 1.75%   |
| Foxconn NETBOX          | 1         | 1.75%   |
| Fanless Mini PC Quieter | 1         | 1.75%   |
| eMachines EL1352        | 1         | 1.75%   |
| Dell XPS                | 1         | 1.75%   |
| Dell DM051              | 1         | 1.75%   |
| Biostar A320MH          | 1         | 1.75%   |
| BANGHO Suma             | 1         | 1.75%   |
| ASUS VivoBook           | 1         | 1.75%   |
| ASUS PRIME              | 1         | 1.75%   |
| ASUS H110M-A            | 1         | 1.75%   |
| Apple Macmini6          | 1         | 1.75%   |
| Apple Macmini4          | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 11        | 19.3%   |
| 2018 | 7         | 12.28%  |
| 2019 | 5         | 8.77%   |
| 2021 | 4         | 7.02%   |
| 2014 | 4         | 7.02%   |
| 2011 | 4         | 7.02%   |
| 2022 | 3         | 5.26%   |
| 2017 | 3         | 5.26%   |
| 2012 | 3         | 5.26%   |
| 2020 | 2         | 3.51%   |
| 2015 | 2         | 3.51%   |
| 2013 | 2         | 3.51%   |
| 2008 | 2         | 3.51%   |
| 2007 | 2         | 3.51%   |
| 2016 | 1         | 1.75%   |
| 2009 | 1         | 1.75%   |
| 2006 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 30        | 52.63%  |
| Desktop    | 18        | 31.58%  |
| Mini pc    | 5         | 8.77%   |
| All in one | 3         | 5.26%   |
| Tablet     | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 96.49%  |
| Enabled  | 2         | 3.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 94.74%  |
| Yes  | 3         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 33.33%  |
| 3.01-4.0   | 13        | 22.81%  |
| 16.01-24.0 | 9         | 15.79%  |
| 1.01-2.0   | 4         | 7.02%   |
| 8.01-16.0  | 4         | 7.02%   |
| 32.01-64.0 | 3         | 5.26%   |
| 2.01-3.0   | 3         | 5.26%   |
| 0.51-1.0   | 2         | 3.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 37        | 62.71%  |
| 1.01-2.0  | 15        | 25.42%  |
| 2.01-3.0  | 4         | 6.78%   |
| 0.01-0.5  | 2         | 3.39%   |
| 8.01-16.0 | 1         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 70.69%  |
| 2      | 14        | 24.14%  |
| 3      | 2         | 3.45%   |
| 4      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 62.07%  |
| Yes       | 22        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 87.93%  |
| No        | 7         | 12.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 80.7%   |
| No        | 11        | 19.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 50%     |
| No        | 29        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 35.09%  |
| Germany     | 8         | 14.04%  |
| UK          | 4         | 7.02%   |
| Spain       | 3         | 5.26%   |
| Italy       | 3         | 5.26%   |
| Netherlands | 2         | 3.51%   |
| Mexico      | 2         | 3.51%   |
| Argentina   | 2         | 3.51%   |
| Vietnam     | 1         | 1.75%   |
| Thailand    | 1         | 1.75%   |
| Taiwan      | 1         | 1.75%   |
| Russia      | 1         | 1.75%   |
| Romania     | 1         | 1.75%   |
| Portugal    | 1         | 1.75%   |
| Kenya       | 1         | 1.75%   |
| Indonesia   | 1         | 1.75%   |
| Czechia     | 1         | 1.75%   |
| Colombia    | 1         | 1.75%   |
| Chile       | 1         | 1.75%   |
| Belgium     | 1         | 1.75%   |
| Austria     | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 8.47%   |
| Fayetteville                | 5         | 8.47%   |
| Charlotte                   | 3         | 5.08%   |
| Milan                       | 2         | 3.39%   |
| Egan                        | 2         | 3.39%   |
| Denver                      | 2         | 3.39%   |
| Zapopan                     | 1         | 1.69%   |
| Workum                      | 1         | 1.69%   |
| Viña del Mar               | 1         | 1.69%   |
| Vienna                      | 1         | 1.69%   |
| Uelzen                      | 1         | 1.69%   |
| Stockport                   | 1         | 1.69%   |
| St Petersburg               | 1         | 1.69%   |
| Schiedam                    | 1         | 1.69%   |
| San Nicolás de los Arroyos | 1         | 1.69%   |
| Rome                        | 1         | 1.69%   |
| Rio Ceballos                | 1         | 1.69%   |
| Rinteln                     | 1         | 1.69%   |
| Ratchathewi                 | 1         | 1.69%   |
| Poricany                    | 1         | 1.69%   |
| Palembang                   | 1         | 1.69%   |
| Norderstedt                 | 1         | 1.69%   |
| Nairobi                     | 1         | 1.69%   |
| Morgantown                  | 1         | 1.69%   |
| Monclova                    | 1         | 1.69%   |
| Memphis                     | 1         | 1.69%   |
| Medellín                   | 1         | 1.69%   |
| Madrid                      | 1         | 1.69%   |
| Lisbon                      | 1         | 1.69%   |
| Leicester                   | 1         | 1.69%   |
| Langelsheim                 | 1         | 1.69%   |
| Idsegahuizum                | 1         | 1.69%   |
| Ho Chi Minh City            | 1         | 1.69%   |
| Golden Valley               | 1         | 1.69%   |
| Ghent                       | 1         | 1.69%   |
| Fongshan District           | 1         | 1.69%   |
| Filderstadt                 | 1         | 1.69%   |
| Eppelborn                   | 1         | 1.69%   |
| Düsseldorf                 | 1         | 1.69%   |
| Darmstadt                   | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 23.29%  |
| Samsung Electronics | 10        | 13     | 13.7%   |
| WDC                 | 8         | 12     | 10.96%  |
| Kingston            | 6         | 7      | 8.22%   |
| SanDisk             | 5         | 7      | 6.85%   |
| Toshiba             | 3         | 4      | 4.11%   |
| Hitachi             | 2         | 2      | 2.74%   |
| Crucial             | 2         | 2      | 2.74%   |
| Apacer              | 2         | 2      | 2.74%   |
| Wibtek              | 1         | 1      | 1.37%   |
| Unknown             | 1         | 1      | 1.37%   |
| SSK                 | 1         | 2      | 1.37%   |
| SK hynix            | 1         | 1      | 1.37%   |
| Silicon Motion      | 1         | 1      | 1.37%   |
| OWC                 | 1         | 2      | 1.37%   |
| Mushkin             | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 2      | 1.37%   |
| Lexar               | 1         | 1      | 1.37%   |
| KIOXIA              | 1         | 1      | 1.37%   |
| KingFast            | 1         | 1      | 1.37%   |
| Intel               | 1         | 1      | 1.37%   |
| China               | 1         | 1      | 1.37%   |
| Blackpcs            | 1         | 1      | 1.37%   |
| ASMedia             | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |
| A-DATA Technology   | 1         | 1      | 1.37%   |
| Unknown             | 1         | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 2         | 2.67%   |
| Seagate ST31000528AS 1TB             | 2         | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2.67%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 2.67%   |
| Wibtek W800S 512GB SSD               | 1         | 1.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 1.33%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1.33%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.33%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 1.33%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.33%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 1.33%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.33%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.33%   |
| Unknown NCard  32GB                  | 1         | 1.33%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.33%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.33%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.33%   |
| SSK Disk 240GB                       | 1         | 1.33%   |
| SK hynix C2S3T/480G 480GB SSD        | 1         | 1.33%   |
| Silicon Motion NE-128 128GB          | 1         | 1.33%   |
| Seagate ST9320325ASG 320GB           | 1         | 1.33%   |
| Seagate ST9320325AS 320GB            | 1         | 1.33%   |
| Seagate ST9250315AS 250GB            | 1         | 1.33%   |
| Seagate ST500VM000-1SD101 500GB      | 1         | 1.33%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.33%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1.33%   |
| Seagate ST3160023AS 160GB            | 1         | 1.33%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1.33%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.33%   |
| Seagate Expansion 1TB                | 1         | 1.33%   |
| Seagate BUP Slim BK 1TB              | 1         | 1.33%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1         | 1.33%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.33%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 1.33%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1         | 1.33%   |
| SanDisk DF4032  32GB                 | 1         | 1.33%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 1.33%   |
| Samsung SSD 980 1TB                  | 1         | 1.33%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.33%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 20     | 56.67%  |
| WDC     | 5         | 5      | 16.67%  |
| Toshiba | 3         | 4      | 10%     |
| Hitachi | 2         | 2      | 6.67%   |
| SSK     | 1         | 2      | 3.33%   |
| ASMedia | 1         | 1      | 3.33%   |
| Apple   | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 20.69%  |
| Kingston            | 5         | 6      | 17.24%  |
| SanDisk             | 4         | 4      | 13.79%  |
| Crucial             | 2         | 2      | 6.9%    |
| Apacer              | 2         | 2      | 6.9%    |
| Wibtek              | 1         | 1      | 3.45%   |
| WDC                 | 1         | 2      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| OWC                 | 1         | 2      | 3.45%   |
| Mushkin             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 2      | 3.45%   |
| KingFast            | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Blackpcs            | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 33     | 41.18%  |
| HDD  | 26        | 35     | 38.24%  |
| NVMe | 12        | 17     | 17.65%  |
| MMC  | 2         | 5      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 62     | 72.06%  |
| NVMe | 12        | 17     | 17.65%  |
| SAS  | 5         | 6      | 7.35%   |
| MMC  | 2         | 5      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 49     | 73.21%  |
| 0.51-1.0   | 12        | 15     | 21.43%  |
| 1.01-2.0   | 2         | 3      | 3.57%   |
| 4.01-10.0  | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 17        | 28.33%  |
| 101-250    | 15        | 25%     |
| 1-20       | 15        | 25%     |
| 1001-2000  | 4         | 6.67%   |
| 51-100     | 4         | 6.67%   |
| 501-1000   | 3         | 5%      |
| 21-50      | 2         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 49        | 83.05%  |
| 21-50     | 5         | 8.47%   |
| 101-250   | 2         | 3.39%   |
| 251-500   | 1         | 1.69%   |
| 1001-2000 | 1         | 1.69%   |
| 51-100    | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB    | 2         | 3      | 18.18%  |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 9.09%   |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 9.09%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 9.09%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 9.09%   |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 9.09%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 9.09%   |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 9.09%   |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 9.09%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 5      | 36.36%  |
| WDC      | 2         | 3      | 18.18%  |
| Toshiba  | 1         | 1      | 9.09%   |
| SanDisk  | 1         | 1      | 9.09%   |
| OWC      | 1         | 2      | 9.09%   |
| Mushkin  | 1         | 1      | 9.09%   |
| Kingston | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 54.55%  |
| SSD  | 5         | 7      | 45.45%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 45        | 63     | 70.31%  |
| Malfunc  | 11        | 14     | 17.19%  |
| Detected | 6         | 10     | 9.38%   |
| Failed   | 2         | 3      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 67.69%  |
| AMD                          | 8         | 12.31%  |
| Samsung Electronics          | 5         | 7.69%   |
| SanDisk                      | 2         | 3.08%   |
| Nvidia                       | 2         | 3.08%   |
| Silicon Motion               | 1         | 1.54%   |
| Shenzhen Longsys Electronics | 1         | 1.54%   |
| KIOXIA                       | 1         | 1.54%   |
| Kingston Technology Company  | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 7.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 3.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 3.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 3         | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 2.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 2         | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 2.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 1.27%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                             | 1         | 1.27%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 1         | 1.27%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 1         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.27%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 1.27%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 1.27%   |
| Nvidia MCP61 IDE                                                              | 1         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 1.27%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                            | 1         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.27%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 1         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.27%   |
| Intel NVMe Optane Memory Series                                               | 1         | 1.27%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 1.27%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.27%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 1         | 1.27%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 1.27%   |
| Intel 82Q35 Express PT IDER Controller                                        | 1         | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                    | 1         | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                    | 1         | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 45        | 63.38%  |
| NVMe | 12        | 16.9%   |
| IDE  | 10        | 14.08%  |
| RAID | 4         | 5.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 82.46%  |
| AMD    | 10        | 17.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 3.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 3.51%   |
| Intel Celeron CPU N2807 @ 1.58GHz           | 2         | 3.51%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.51%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz          | 1         | 1.75%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.75%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 1.75%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.75%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.75%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1         | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 1.75%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 1.75%   |
| Intel Celeron N5105 @ 2.00GHz               | 1         | 1.75%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1         | 1.75%   |
| Intel Celeron 3205U @ 1.50GHz               | 1         | 1.75%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 1.75%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 1.75%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1         | 1.75%   |
| Intel 12th Gen Core i5-1235U                | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 19.3%   |
| Intel Core i7           | 7         | 12.28%  |
| Intel Core 2 Duo        | 6         | 10.53%  |
| Intel Celeron           | 5         | 8.77%   |
| Intel Atom              | 5         | 8.77%   |
| Other                   | 4         | 7.02%   |
| Intel Core i3           | 3         | 5.26%   |
| Intel Pentium           | 2         | 3.51%   |
| AMD Ryzen 5             | 2         | 3.51%   |
| AMD GX                  | 2         | 3.51%   |
| Intel Xeon              | 1         | 1.75%   |
| Intel Pentium Gold      | 1         | 1.75%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Pentium D         | 1         | 1.75%   |
| AMD Ryzen 7             | 1         | 1.75%   |
| AMD PRO A10             | 1         | 1.75%   |
| AMD Phenom II           | 1         | 1.75%   |
| AMD Athlon II Dual-Core | 1         | 1.75%   |
| AMD Athlon II           | 1         | 1.75%   |
| AMD A12                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 54.39%  |
| 4      | 14        | 24.56%  |
| 6      | 4         | 7.02%   |
| 1      | 4         | 7.02%   |
| 8      | 2         | 3.51%   |
| 10     | 1         | 1.75%   |
| 3      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 56.14%  |
| 1      | 25        | 43.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 98.25%  |
| 32-bit         | 1         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 15%     |
| 0x1067a    | 4         | 6.67%   |
| 0x306a9    | 3         | 5%      |
| 0x106ca    | 3         | 5%      |
| 0x906ea    | 2         | 3.33%   |
| 0x806ea    | 2         | 3.33%   |
| 0x406e3    | 2         | 3.33%   |
| 0x40651    | 2         | 3.33%   |
| 0x306d4    | 2         | 3.33%   |
| 0x30678    | 2         | 3.33%   |
| 0x206a7    | 2         | 3.33%   |
| 0x20655    | 2         | 3.33%   |
| 0x0600611a | 2         | 3.33%   |
| 0x010000c8 | 2         | 3.33%   |
| 0xf44      | 1         | 1.67%   |
| 0xa0671    | 1         | 1.67%   |
| 0xa0653    | 1         | 1.67%   |
| 0x906ed    | 1         | 1.67%   |
| 0x906e9    | 1         | 1.67%   |
| 0x906c0    | 1         | 1.67%   |
| 0x906a4    | 1         | 1.67%   |
| 0x806d1    | 1         | 1.67%   |
| 0x806c1    | 1         | 1.67%   |
| 0x706e5    | 1         | 1.67%   |
| 0x6fa      | 1         | 1.67%   |
| 0x506c9    | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x206d7    | 1         | 1.67%   |
| 0x106c2    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x08600106 | 1         | 1.67%   |
| 0x08108109 | 1         | 1.67%   |
| 0x0810100b | 1         | 1.67%   |
| 0x07030105 | 1         | 1.67%   |
| 0x07030104 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 10.34%  |
| Penryn      | 5         | 8.62%   |
| Bonnell     | 5         | 8.62%   |
| SandyBridge | 4         | 6.9%    |
| Icelake     | 4         | 6.9%    |
| Westmere    | 3         | 5.17%   |
| K10         | 3         | 5.17%   |
| IvyBridge   | 3         | 5.17%   |
| Haswell     | 3         | 5.17%   |
| Skylake     | 2         | 3.45%   |
| Silvermont  | 2         | 3.45%   |
| Puma        | 2         | 3.45%   |
| Excavator   | 2         | 3.45%   |
| Core        | 2         | 3.45%   |
| Broadwell   | 2         | 3.45%   |
| Unknown     | 2         | 3.45%   |
| Zen+        | 1         | 1.72%   |
| Zen 2       | 1         | 1.72%   |
| Zen         | 1         | 1.72%   |
| Tremont     | 1         | 1.72%   |
| TigerLake   | 1         | 1.72%   |
| NetBurst    | 1         | 1.72%   |
| Goldmont    | 1         | 1.72%   |
| CometLake   | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 60%     |
| AMD    | 16        | 24.62%  |
| Nvidia | 10        | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 4.41%   |
| Intel UHD Graphics 620                                                        | 2         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2         | 2.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1         | 1.47%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.47%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 1.47%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                             | 1         | 1.47%   |
| Nvidia GA102 [GeForce RTX 3080]                                               | 1         | 1.47%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 1.47%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.47%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.47%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.47%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.47%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.47%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.47%   |
| Intel HD Graphics 630                                                         | 1         | 1.47%   |
| Intel HD Graphics 5500                                                        | 1         | 1.47%   |
| Intel HD Graphics                                                             | 1         | 1.47%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                      | 1         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.47%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.47%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 1.47%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                       | 1         | 1.47%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 1         | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 50%     |
| 1 x AMD        | 12        | 20.69%  |
| 1 x Nvidia     | 7         | 12.07%  |
| 2 x Intel      | 3         | 5.17%   |
| Intel + Nvidia | 3         | 5.17%   |
| Intel + AMD    | 3         | 5.17%   |
| 2 x AMD        | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 54        | 93.1%   |
| Unknown     | 3         | 5.17%   |
| Proprietary | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 61.02%  |
| 0.01-0.5   | 13        | 22.03%  |
| 3.01-4.0   | 3         | 5.08%   |
| 1.01-2.0   | 3         | 5.08%   |
| 0.51-1.0   | 2         | 3.39%   |
| 7.01-8.0   | 1         | 1.69%   |
| 8.01-16.0  | 1         | 1.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 22.22%  |
| Samsung Electronics     | 4         | 7.41%   |
| LG Display              | 4         | 7.41%   |
| Chimei Innolux          | 4         | 7.41%   |
| Lenovo                  | 3         | 5.56%   |
| Dell                    | 3         | 5.56%   |
| Zoran                   | 2         | 3.7%    |
| Sceptre Tech            | 2         | 3.7%    |
| Goldstar                | 2         | 3.7%    |
| Chi Mei Optoelectronics | 2         | 3.7%    |
| BOE                     | 2         | 3.7%    |
| Sony                    | 1         | 1.85%   |
| Sharp                   | 1         | 1.85%   |
| SAC                     | 1         | 1.85%   |
| Philips                 | 1         | 1.85%   |
| JDI                     | 1         | 1.85%   |
| Insignia                | 1         | 1.85%   |
| InfoVision              | 1         | 1.85%   |
| HUAWEI                  | 1         | 1.85%   |
| Hewlett-Packard         | 1         | 1.85%   |
| EQV                     | 1         | 1.85%   |
| eMachines               | 1         | 1.85%   |
| ASUSTek Computer        | 1         | 1.85%   |
| Apple                   | 1         | 1.85%   |
| AOC                     | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                        | 2         | 3.7%    |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                    | 2         | 3.7%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 3.7%    |
| Sony TV SNY0101 1360x768                                                  | 1         | 1.85%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch   | 1         | 1.85%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch         | 1         | 1.85%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch         | 1         | 1.85%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                     | 1         | 1.85%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                        | 1         | 1.85%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.85%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                  | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                   | 1         | 1.85%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                      | 1         | 1.85%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                     | 1         | 1.85%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch                    | 1         | 1.85%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch               | 1         | 1.85%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                      | 1         | 1.85%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch              | 1         | 1.85%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch                  | 1         | 1.85%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                    | 1         | 1.85%   |
| EQV LCD Monitor EQV1080 1920x1080 477x268mm 21.5-inch                     | 1         | 1.85%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                     | 1         | 1.85%   |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                         | 1         | 1.85%   |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                         | 1         | 1.85%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.85%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                      | 1         | 1.85%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch             | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 40.38%  |
| 1366x768 (WXGA)    | 11        | 21.15%  |
| 1360x768           | 4         | 7.69%   |
| 1024x600           | 4         | 7.69%   |
| 2560x1440 (QHD)    | 3         | 5.77%   |
| 3840x2160 (4K)     | 2         | 3.85%   |
| 1280x800 (WXGA)    | 2         | 3.85%   |
| 3440x1440          | 1         | 1.92%   |
| 1920x1200 (WUXGA)  | 1         | 1.92%   |
| 1680x1050 (WSXGA+) | 1         | 1.92%   |
| 1600x900 (HD+)     | 1         | 1.92%   |
| 1024x768 (XGA)     | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 12        | 22.22%  |
| 24      | 6         | 11.11%  |
| 14      | 6         | 11.11%  |
| 21      | 5         | 9.26%   |
| 10      | 5         | 9.26%   |
| 22      | 3         | 5.56%   |
| 17      | 3         | 5.56%   |
| 31      | 2         | 3.7%    |
| 23      | 2         | 3.7%    |
| 13      | 2         | 3.7%    |
| 84      | 1         | 1.85%   |
| 34      | 1         | 1.85%   |
| 32      | 1         | 1.85%   |
| 27      | 1         | 1.85%   |
| 16      | 1         | 1.85%   |
| 12      | 1         | 1.85%   |
| 11      | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 33.33%  |
| 501-600     | 9         | 16.67%  |
| 401-500     | 8         | 14.81%  |
| 201-300     | 8         | 14.81%  |
| 351-400     | 5         | 9.26%   |
| 701-800     | 2         | 3.7%    |
| 601-700     | 2         | 3.7%    |
| 1501-2000   | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 45        | 88.24%  |
| 16/10 | 4         | 7.84%   |
| 4/3   | 1         | 1.96%   |
| 21/9  | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 25.93%  |
| 101-110        | 12        | 22.22%  |
| 81-90          | 7         | 12.96%  |
| 41-50          | 5         | 9.26%   |
| 351-500        | 4         | 7.41%   |
| 121-130        | 3         | 5.56%   |
| 151-200        | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 71-80          | 1         | 1.85%   |
| 61-70          | 1         | 1.85%   |
| 51-60          | 1         | 1.85%   |
| 301-350        | 1         | 1.85%   |
| 111-120        | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 20        | 37.04%  |
| 51-100  | 16        | 29.63%  |
| 121-160 | 12        | 22.22%  |
| 161-240 | 4         | 7.41%   |
| 1-50    | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 51        | 86.44%  |
| 2     | 4         | 6.78%   |
| 0     | 4         | 6.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 27        | 31.76%  |
| Intel                           | 21        | 24.71%  |
| Qualcomm Atheros                | 17        | 20%     |
| Broadcom                        | 11        | 12.94%  |
| Qualcomm Atheros Communications | 3         | 3.53%   |
| Ralink Technology               | 1         | 1.18%   |
| Prolific Technology             | 1         | 1.18%   |
| Nvidia                          | 1         | 1.18%   |
| MediaTek                        | 1         | 1.18%   |
| Marvell Technology Group        | 1         | 1.18%   |
| ICS Advent                      | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 15        | 14.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 6         | 5.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.92%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 1.92%   |
| Intel Wireless 8260                                                                   | 2         | 1.92%   |
| Intel Wireless 7260                                                                   | 2         | 1.92%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.92%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.96%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 0.96%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.96%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.96%   |
| Prolific USB-Serial Controller                                                        | 1         | 0.96%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.96%   |
| MediaTek P8                                                                           | 1         | 0.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.96%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.96%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 0.96%   |
| Intel Wireless 7265                                                                   | 1         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 30.61%  |
| Qualcomm Atheros                | 14        | 28.57%  |
| Realtek Semiconductor           | 10        | 20.41%  |
| Broadcom                        | 6         | 12.24%  |
| Qualcomm Atheros Communications | 3         | 6.12%   |
| Ralink Technology               | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 8.16%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 6.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 4.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 4.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 4.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 4.08%   |
| Intel Wireless 8260                                                                   | 2         | 4.08%   |
| Intel Wireless 7260                                                                   | 2         | 4.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.08%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.04%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 2.04%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.04%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.04%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 2.04%   |
| Intel Wireless-AC 9260                                                                | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.04%   |
| Intel Wireless 7265                                                                   | 1         | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 2.04%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.04%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.04%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 2.04%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 42.59%  |
| Intel                    | 13        | 24.07%  |
| Broadcom                 | 8         | 14.81%  |
| Qualcomm Atheros         | 6         | 11.11%  |
| Nvidia                   | 1         | 1.85%   |
| MediaTek                 | 1         | 1.85%   |
| Marvell Technology Group | 1         | 1.85%   |
| ICS Advent               | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 27.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.7%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 3.7%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.85%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.85%   |
| MediaTek P8                                                       | 1         | 1.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.85%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.85%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.85%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.85%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.85%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 52.04%  |
| WiFi     | 46        | 46.94%  |
| Modem    | 1         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50%     |
| Ethernet | 30        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 60.34%  |
| 1     | 21        | 36.21%  |
| 3     | 1         | 1.72%   |
| 0     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 60.34%  |
| Yes  | 23        | 39.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 37.93%  |
| Apple                           | 5         | 17.24%  |
| Qualcomm Atheros Communications | 4         | 13.79%  |
| Realtek Semiconductor           | 3         | 10.34%  |
| Lite-On Technology              | 3         | 10.34%  |
| IMC Networks                    | 2         | 6.9%    |
| Broadcom                        | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 20.69%  |
| Intel AX201 Bluetooth                              | 3         | 10.34%  |
| Realtek 802.11ac WLAN Adapter                      | 2         | 6.9%    |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 6.9%    |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 6.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 2         | 6.9%    |
| Realtek RTL8723B Bluetooth                         | 1         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 3.45%   |
| Lite-On Bluetooth USB Host Controller              | 1         | 3.45%   |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 3.45%   |
| IMC Networks Bluetooth Radio                       | 1         | 3.45%   |
| IMC Networks Bluetooth Device                      | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.45%   |
| Apple Bluetooth USB Host Controller                | 1         | 3.45%   |
| Apple Bluetooth Host Controller                    | 1         | 3.45%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 61.64%  |
| AMD                   | 14        | 19.18%  |
| Nvidia                | 8         | 10.96%  |
| SAVITECH              | 1         | 1.37%   |
| Roland                | 1         | 1.37%   |
| Realtek Semiconductor | 1         | 1.37%   |
| JMTek                 | 1         | 1.37%   |
| Huawei Technologies   | 1         | 1.37%   |
| Anlya.cn              | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 6.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 4.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.3%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.3%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.3%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.3%    |
| AMD FCH Azalia Controller                                                  | 2         | 2.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.3%    |
| SAVITECH SA9123 USB Audio                                                  | 1         | 1.15%   |
| Roland QUAD-CAPTURE                                                        | 1         | 1.15%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.15%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.15%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.15%   |
| JMTek USB Audio Device                                                     | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.15%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.15%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.15%   |
| Intel HD Graphics SGPC                                                     | 1         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 17.39%  |
| Unknown             | 9         | 13.04%  |
| Crucial             | 7         | 10.14%  |
| Samsung Electronics | 6         | 8.7%    |
| Micron Technology   | 6         | 8.7%    |
| Kingston            | 6         | 8.7%    |
| A-DATA Technology   | 5         | 7.25%   |
| Elpida              | 3         | 4.35%   |
| Corsair             | 3         | 4.35%   |
| Timetec             | 2         | 2.9%    |
| Nanya Technology    | 2         | 2.9%    |
| Unknown (08C8)      | 1         | 1.45%   |
| Toshiba             | 1         | 1.45%   |
| Team                | 1         | 1.45%   |
| SK_Hynix            | 1         | 1.45%   |
| Patriot             | 1         | 1.45%   |
| Infineon            | 1         | 1.45%   |
| G.Skill             | 1         | 1.45%   |
| Unknown             | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 2.7%    |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 2.7%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.35%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.35%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.35%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s     | 1         | 1.35%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.35%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.35%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 1.35%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 1.35%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.35%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 1.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.35%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.35%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s                  | 1         | 1.35%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3                       | 1         | 1.35%   |
| Patriot RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.35%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 1         | 1.35%   |
| Nanya RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 1.35%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.35%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 26        | 47.27%  |
| DDR4   | 15        | 27.27%  |
| DDR2   | 8         | 14.55%  |
| LPDDR4 | 4         | 7.27%   |
| LPDDR3 | 1         | 1.82%   |
| DDR    | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 61.82%  |
| DIMM         | 15        | 27.27%  |
| Row Of Chips | 3         | 5.45%   |
| Unknown      | 2         | 3.64%   |
| Chip         | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 19        | 32.76%  |
| 8192  | 16        | 27.59%  |
| 2048  | 13        | 22.41%  |
| 1024  | 5         | 8.62%   |
| 16384 | 3         | 5.17%   |
| 32768 | 1         | 1.72%   |
| 512   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 23.33%  |
| 667     | 7         | 11.67%  |
| 2667    | 6         | 10%     |
| 1067    | 5         | 8.33%   |
| 3200    | 4         | 6.67%   |
| 2400    | 3         | 5%      |
| 3733    | 2         | 3.33%   |
| 1333    | 2         | 3.33%   |
| 1066    | 2         | 3.33%   |
| 533     | 2         | 3.33%   |
| 8400    | 1         | 1.67%   |
| 4267    | 1         | 1.67%   |
| 4266    | 1         | 1.67%   |
| 2800    | 1         | 1.67%   |
| 2733    | 1         | 1.67%   |
| 2666    | 1         | 1.67%   |
| 1867    | 1         | 1.67%   |
| 1866    | 1         | 1.67%   |
| 1800    | 1         | 1.67%   |
| 1334    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 800     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 50%     |
| HP DeskJet F4200 series               | 1         | 25%     |
| HP DeskJet 2130 series                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 26.67%  |
| Apple                         | 4         | 13.33%  |
| Microdia                      | 3         | 10%     |
| Sunplus Innovation Technology | 2         | 6.67%   |
| Realtek Semiconductor         | 2         | 6.67%   |
| Logitech                      | 2         | 6.67%   |
| IMC Networks                  | 2         | 6.67%   |
| ALi                           | 2         | 6.67%   |
| Suyin                         | 1         | 3.33%   |
| Ricoh                         | 1         | 3.33%   |
| Quanta                        | 1         | 3.33%   |
| Luxvisions Innotech Limited   | 1         | 3.33%   |
| Acer                          | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 2         | 6.67%   |
| Apple Built-in iSight                               | 2         | 6.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 3.33%   |
| Sunplus HD WebCam                                   | 1         | 3.33%   |
| Ricoh USB2.0 Camera                                 | 1         | 3.33%   |
| Realtek USB Camera                                  | 1         | 3.33%   |
| Realtek Lenovo EasyCamera                           | 1         | 3.33%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 3.33%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.33%   |
| Microdia Integrated Webcam                          | 1         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.33%   |
| Logitech Logitech Webcam C160                       | 1         | 3.33%   |
| Logitech HD Pro Webcam C920                         | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.33%   |
| IMC Networks Integrated Camera                      | 1         | 3.33%   |
| Chicony WebCam                                      | 1         | 3.33%   |
| Chicony USB 2.0 Camera                              | 1         | 3.33%   |
| Chicony Integrated Camera                           | 1         | 3.33%   |
| Chicony HP Webcam-101                               | 1         | 3.33%   |
| Chicony HD WebCam (Acer)                            | 1         | 3.33%   |
| Chicony Camera                                      | 1         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 3.33%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 3.33%   |
| ALi WebCam                                          | 1         | 3.33%   |
| ALi Gateway Webcam                                  | 1         | 3.33%   |
| Acer BisonCam, NB Pro                               | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 50%     |
| Focal-systems.Corp    | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 42        | 72.41%  |
| 1     | 15        | 25.86%  |
| 2     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 52.94%  |
| Multimedia controller    | 2         | 11.76%  |
| Fingerprint reader       | 2         | 11.76%  |
| Net/wireless             | 1         | 5.88%   |
| Communication controller | 1         | 5.88%   |
| Chipcard                 | 1         | 5.88%   |
| Camera                   | 1         | 5.88%   |


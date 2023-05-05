Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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

Total: 80

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c68576fce8](https://linux-hardware.org/?probe=c68576fce8) | Apr 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| HP            | 18E6                        | Desktop     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI           | MS-7360                     | Desktop     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| MSI           | MS-7360                     | Desktop     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pardus 21.4   | 12        | 19.67%  |
| Pardus 21.3   | 9         | 14.75%  |
| Pardus 21.2   | 9         | 14.75%  |
| Pardus 21.1   | 6         | 9.84%   |
| Pardus 19.5   | 5         | 8.2%    |
| Pardus 21.0   | 4         | 6.56%   |
| Pardus 19.4-1 | 3         | 4.92%   |
| Pardus 19.4   | 3         | 4.92%   |
| Pardus 19.3   | 3         | 4.92%   |
| Pardus 19.2   | 3         | 4.92%   |
| Pardus 19.1   | 2         | 3.28%   |
| Pardus 19.0   | 2         | 3.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 8         | 12.9%   |
| 5.10.0-13-amd64           | 6         | 9.68%   |
| 5.10.0-20-amd64           | 4         | 6.45%   |
| 5.10.0-19-amd64           | 4         | 6.45%   |
| 5.10.0-16-amd64           | 3         | 4.84%   |
| 5.10.0-11-amd64           | 3         | 4.84%   |
| 4.19.0-6-amd64            | 3         | 4.84%   |
| 4.19.0-13-amd64           | 3         | 4.84%   |
| 4.19.0-10-amd64           | 3         | 4.84%   |
| 5.9.0-0.bpo.2-amd64       | 2         | 3.23%   |
| 5.10.0-9-amd64            | 2         | 3.23%   |
| 5.10.0-8-amd64            | 2         | 3.23%   |
| 5.10.0-14-amd64           | 2         | 3.23%   |
| 5.10.0-10-amd64           | 2         | 3.23%   |
| 4.19.0-8-amd64            | 2         | 3.23%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.61%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 1.61%   |
| 5.10.0-18-amd64           | 1         | 1.61%   |
| 5.10.0-17-amd64           | 1         | 1.61%   |
| 5.10.0-15-amd64           | 1         | 1.61%   |
| 5.10.0-12-amd64           | 1         | 1.61%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 1.61%   |
| 4.19.0-5-amd64            | 1         | 1.61%   |
| 4.19.0-19-amd64           | 1         | 1.61%   |
| 4.19.0-18-amd64           | 1         | 1.61%   |
| 4.19.0-17-amd64           | 1         | 1.61%   |
| 4.19.0-16-amd64           | 1         | 1.61%   |
| 4.19.0-12-amd64           | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 39        | 66.1%   |
| 4.19.0  | 16        | 27.12%  |
| 5.9.0   | 2         | 3.39%   |
| 6.0.11  | 1         | 1.69%   |
| 5.4.0   | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 39        | 66.1%   |
| 4.19    | 16        | 27.12%  |
| 5.9     | 2         | 3.39%   |
| 6.0     | 1         | 1.69%   |
| 5.4     | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 34        | 58.62%  |
| GNOME      | 18        | 31.03%  |
| KDE5       | 3         | 5.17%   |
| Unknown    | 2         | 3.45%   |
| X-Cinnamon | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 56        | 98.25%  |
| Tty  | 1         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 62.07%  |
| GDM     | 8         | 13.79%  |
| TDM     | 6         | 10.34%  |
| LightDM | 6         | 10.34%  |
| SDDM    | 2         | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 46        | 79.31%  |
| en_US   | 4         | 6.9%    |
| Unknown | 3         | 5.17%   |
| pt_BR   | 1         | 1.72%   |
| hu_HU   | 1         | 1.72%   |
| fur_IT  | 1         | 1.72%   |
| fr_FR   | 1         | 1.72%   |
| en_GB   | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 43        | 72.88%  |
| EFI  | 16        | 27.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 98.25%  |
| Overlay | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 67.24%  |
| GPT     | 15        | 25.86%  |
| MBR     | 4         | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 92.98%  |
| Yes       | 4         | 7.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 85.96%  |
| Yes       | 8         | 14.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 24.56%  |
| Hewlett-Packard     | 8         | 14.04%  |
| ASUSTek Computer    | 7         | 12.28%  |
| MSI                 | 6         | 10.53%  |
| Toshiba             | 3         | 5.26%   |
| Gigabyte Technology | 3         | 5.26%   |
| Dell                | 3         | 5.26%   |
| Acer                | 3         | 5.26%   |
| Sony                | 2         | 3.51%   |
| Packard Bell        | 2         | 3.51%   |
| TUXEDO              | 1         | 1.75%   |
| Samsung Electronics | 1         | 1.75%   |
| Philco              | 1         | 1.75%   |
| Olidata             | 1         | 1.75%   |
| HUAWEI              | 1         | 1.75%   |
| Clevo               | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 3         | 5.26%   |
| Toshiba Satellite C855-1VM                 | 1         | 1.75%   |
| Toshiba Satellite C660                     | 1         | 1.75%   |
| Toshiba PORTEGE M780                       | 1         | 1.75%   |
| Sony SVF1521QSTB                           | 1         | 1.75%   |
| Sony SVE14A2V2ES                           | 1         | 1.75%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 1.75%   |
| Philco 14F                                 | 1         | 1.75%   |
| Packard Bell EasyNote_GN45                 | 1         | 1.75%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 1.75%   |
| Olidata T7700                              | 1         | 1.75%   |
| MSI MS-7C09                                | 1         | 1.75%   |
| MSI MS-7A65                                | 1         | 1.75%   |
| MSI MS-7817                                | 1         | 1.75%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 1.75%   |
| Lenovo V145-15AST 81MT                     | 1         | 1.75%   |
| Lenovo V110-15ISK 80TL                     | 1         | 1.75%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 1.75%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 1.75%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 1.75%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 1.75%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 1.75%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS          | 1         | 1.75%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 1.75%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 1.75%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 1.75%   |
| Lenovo G510 20238                          | 1         | 1.75%   |
| Lenovo G50-45 80E3                         | 1         | 1.75%   |
| HUAWEI KLVL-WXXW                           | 1         | 1.75%   |
| HP ProBook 4540s                           | 1         | 1.75%   |
| HP Pavilion 15                             | 1         | 1.75%   |
| HP Laptop 15-dw3xxx                        | 1         | 1.75%   |
| HP EliteOne 800 G1 AiO                     | 1         | 1.75%   |
| HP All-in-One 24-f0xx                      | 1         | 1.75%   |
| HP 530                                     | 1         | 1.75%   |
| HP 250 G3                                  | 1         | 1.75%   |
| HP 15                                      | 1         | 1.75%   |
| Gigabyte H410M H V3                        | 1         | 1.75%   |
| Gigabyte A320M-S2H                         | 1         | 1.75%   |
| Gigabyte A320M-H                           | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 7.02%   |
| MSI MS-7360              | 3         | 5.26%   |
| Toshiba Satellite        | 2         | 3.51%   |
| Packard Bell EasyNote    | 2         | 3.51%   |
| Lenovo IdeaPad           | 2         | 3.51%   |
| Acer Aspire              | 2         | 3.51%   |
| Toshiba PORTEGE          | 1         | 1.75%   |
| Sony SVF1521QSTB         | 1         | 1.75%   |
| Sony SVE14A2V2ES         | 1         | 1.75%   |
| Samsung 300E4A           | 1         | 1.75%   |
| Philco 14F               | 1         | 1.75%   |
| Olidata T7700            | 1         | 1.75%   |
| MSI MS-7C09              | 1         | 1.75%   |
| MSI MS-7A65              | 1         | 1.75%   |
| MSI MS-7817              | 1         | 1.75%   |
| Lenovo Yoga              | 1         | 1.75%   |
| Lenovo V145-15AST        | 1         | 1.75%   |
| Lenovo V110-15ISK        | 1         | 1.75%   |
| Lenovo ThinkCentre       | 1         | 1.75%   |
| Lenovo IdeaPadFlex       | 1         | 1.75%   |
| Lenovo IdeaPad-510-15IKB | 1         | 1.75%   |
| Lenovo G510              | 1         | 1.75%   |
| Lenovo G50-45            | 1         | 1.75%   |
| HUAWEI KLVL-WXXW         | 1         | 1.75%   |
| HP ProBook               | 1         | 1.75%   |
| HP Pavilion              | 1         | 1.75%   |
| HP Laptop                | 1         | 1.75%   |
| HP EliteOne              | 1         | 1.75%   |
| HP All-in-One            | 1         | 1.75%   |
| HP 530                   | 1         | 1.75%   |
| HP 250                   | 1         | 1.75%   |
| HP 15                    | 1         | 1.75%   |
| Gigabyte H410M           | 1         | 1.75%   |
| Gigabyte A320M-S2H       | 1         | 1.75%   |
| Gigabyte A320M-H         | 1         | 1.75%   |
| Dell OptiPlex            | 1         | 1.75%   |
| Dell Latitude            | 1         | 1.75%   |
| Dell G5                  | 1         | 1.75%   |
| Clevo W251EFQ            | 1         | 1.75%   |
| ASUS X555YI              | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 10        | 17.54%  |
| 2018 | 8         | 14.04%  |
| 2010 | 5         | 8.77%   |
| 2020 | 4         | 7.02%   |
| 2017 | 4         | 7.02%   |
| 2015 | 4         | 7.02%   |
| 2007 | 4         | 7.02%   |
| 2021 | 3         | 5.26%   |
| 2014 | 3         | 5.26%   |
| 2011 | 3         | 5.26%   |
| 2019 | 2         | 3.51%   |
| 2016 | 2         | 3.51%   |
| 2012 | 2         | 3.51%   |
| 2022 | 1         | 1.75%   |
| 2008 | 1         | 1.75%   |
| 2006 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 63.16%  |
| Desktop     | 17        | 29.82%  |
| Convertible | 2         | 3.51%   |
| All in one  | 2         | 3.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 20        | 34.48%  |
| 4.01-8.0   | 16        | 27.59%  |
| 8.01-16.0  | 9         | 15.52%  |
| 16.01-24.0 | 8         | 13.79%  |
| 2.01-3.0   | 2         | 3.45%   |
| 1.01-2.0   | 2         | 3.45%   |
| 32.01-64.0 | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 26        | 41.94%  |
| 2.01-3.0   | 19        | 30.65%  |
| 3.01-4.0   | 11        | 17.74%  |
| 4.01-8.0   | 3         | 4.84%   |
| 24.01-32.0 | 1         | 1.61%   |
| 8.01-16.0  | 1         | 1.61%   |
| 0.51-1.0   | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 66.67%  |
| 2      | 16        | 28.07%  |
| 3      | 2         | 3.51%   |
| 4      | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 52.63%  |
| No        | 27        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 92.98%  |
| No        | 4         | 7.02%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 63.16%  |
| No        | 21        | 36.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 50        | 87.72%  |
| Germany | 2         | 3.51%   |
| UK      | 1         | 1.75%   |
| Sweden  | 1         | 1.75%   |
| Italy   | 1         | 1.75%   |
| France  | 1         | 1.75%   |
| Brazil  | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Istanbul             | 19        | 31.67%  |
| Bursa                | 6         | 10%     |
| Ankara               | 6         | 10%     |
| Izmir                | 4         | 6.67%   |
| Aydin                | 4         | 6.67%   |
| Konya                | 3         | 5%      |
| Çanakkale           | 2         | 3.33%   |
| Yaman                | 1         | 1.67%   |
| Soleymieu            | 1         | 1.67%   |
| Serik                | 1         | 1.67%   |
| Sao Gabriel          | 1         | 1.67%   |
| Samsun               | 1         | 1.67%   |
| Malatya              | 1         | 1.67%   |
| London               | 1         | 1.67%   |
| Landskrona           | 1         | 1.67%   |
| Kirchheim unter Teck | 1         | 1.67%   |
| Gaziantep            | 1         | 1.67%   |
| Esenyurt             | 1         | 1.67%   |
| Castrop-Rauxel       | 1         | 1.67%   |
| Bolzano              | 1         | 1.67%   |
| Balıkesir           | 1         | 1.67%   |
| Artvin               | 1         | 1.67%   |
| Antalya              | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 14        | 18     | 18.42%  |
| Seagate                     | 10        | 13     | 13.16%  |
| Samsung Electronics         | 9         | 14     | 11.84%  |
| Sandisk                     | 8         | 8      | 10.53%  |
| Toshiba                     | 3         | 4      | 3.95%   |
| Kingston                    | 3         | 4      | 3.95%   |
| A-DATA Technology           | 3         | 3      | 3.95%   |
| Unknown                     | 2         | 3      | 2.63%   |
| SK hynix                    | 2         | 2      | 2.63%   |
| KIOXIA-EXCERIA              | 2         | 2      | 2.63%   |
| Hitachi                     | 2         | 2      | 2.63%   |
| HGST                        | 2         | 2      | 2.63%   |
| China                       | 2         | 2      | 2.63%   |
| Team                        | 1         | 1      | 1.32%   |
| SPCC                        | 1         | 1      | 1.32%   |
| Silicon Motion              | 1         | 1      | 1.32%   |
| Phison                      | 1         | 1      | 1.32%   |
| Micron Technology           | 1         | 2      | 1.32%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.32%   |
| Lexar                       | 1         | 1      | 1.32%   |
| KIOXIA                      | 1         | 1      | 1.32%   |
| KingSpec                    | 1         | 1      | 1.32%   |
| Intenso                     | 1         | 2      | 1.32%   |
| Corsair                     | 1         | 1      | 1.32%   |
| addlink                     | 1         | 1      | 1.32%   |
| 120G                        | 1         | 1      | 1.32%   |
| Unknown                     | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB                  | 3         | 3.8%    |
| A-DATA SU650 120GB SSD                       | 3         | 3.8%    |
| SanDisk SSD PLUS 240GB                       | 2         | 2.53%   |
| HGST HTS545050A7E680 500GB                   | 2         | 2.53%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD             | 1         | 1.27%   |
| WDC WD5000LPVX-55V0TT0 500GB                 | 1         | 1.27%   |
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1.27%   |
| WDC WD5000LPCX-21VHAT0 500GB                 | 1         | 1.27%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1.27%   |
| WDC WD3200BPVT-35JJ5T0 320GB                 | 1         | 1.27%   |
| WDC WD3200AAJB-00WGA0 320GB                  | 1         | 1.27%   |
| WDC WD2500BEVS-00UST0 250GB                  | 1         | 1.27%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 1.27%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1         | 1.27%   |
| Unknown SD/MMC/MS PRO 249GB                  | 1         | 1.27%   |
| Unknown MMC Card  64GB                       | 1         | 1.27%   |
| Toshiba MQ01ABD075 752GB                     | 1         | 1.27%   |
| Toshiba MK6475GSX 640GB                      | 1         | 1.27%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1.27%   |
| Team T253X1240G 240GB SSD                    | 1         | 1.27%   |
| SPCC Solid State Disk 512GB                  | 1         | 1.27%   |
| SK hynix SC311 SATA 256GB SSD                | 1         | 1.27%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB      | 1         | 1.27%   |
| Silicon Motion Longline SSD 512GB            | 1         | 1.27%   |
| Seagate ST9500325AS 500GB                    | 1         | 1.27%   |
| Seagate ST9120822AS 120GB                    | 1         | 1.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1.27%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1.27%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.27%   |
| Seagate ST3160318AS 160GB                    | 1         | 1.27%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1.27%   |
| Seagate ST1000LM035-1RK172 970GB             | 1         | 1.27%   |
| Seagate Expansion 4TB                        | 1         | 1.27%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB  | 1         | 1.27%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1.27%   |
| SanDisk Ultra II 240GB SSD                   | 1         | 1.27%   |
| SanDisk SSD U110 16GB                        | 1         | 1.27%   |
| SanDisk SSD PLUS 120GB                       | 1         | 1.27%   |
| SanDisk SDSSDA480G 480GB                     | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 17     | 39.39%  |
| Seagate             | 9         | 12     | 27.27%  |
| Toshiba             | 3         | 4      | 9.09%   |
| Samsung Electronics | 3         | 6      | 9.09%   |
| Hitachi             | 2         | 2      | 6.06%   |
| HGST                | 2         | 2      | 6.06%   |
| Unknown             | 1         | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 21.88%  |
| Samsung Electronics | 4         | 4      | 12.5%   |
| Kingston            | 3         | 4      | 9.38%   |
| A-DATA Technology   | 3         | 3      | 9.38%   |
| KIOXIA-EXCERIA      | 2         | 2      | 6.25%   |
| China               | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| Team                | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| Seagate             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 2      | 3.13%   |
| Lexar               | 1         | 1      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| Intenso             | 1         | 2      | 3.13%   |
| Corsair             | 1         | 1      | 3.13%   |
| 120G                | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 45     | 44.78%  |
| SSD     | 27        | 35     | 40.3%   |
| NVMe    | 7         | 10     | 10.45%  |
| Unknown | 2         | 2      | 2.99%   |
| MMC     | 1         | 1      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 79     | 83.33%  |
| NVMe | 7         | 10     | 11.67%  |
| SAS  | 2         | 3      | 3.33%   |
| MMC  | 1         | 1      | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 56     | 71.93%  |
| 0.51-1.0   | 14        | 20     | 24.56%  |
| 3.01-4.0   | 1         | 1      | 1.75%   |
| 1.01-2.0   | 1         | 3      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 28        | 48.28%  |
| 251-500    | 16        | 27.59%  |
| 501-1000   | 7         | 12.07%  |
| 51-100     | 4         | 6.9%    |
| 21-50      | 2         | 3.45%   |
| 2001-3000  | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 24        | 41.38%  |
| 21-50    | 13        | 22.41%  |
| 51-100   | 11        | 18.97%  |
| 101-250  | 7         | 12.07%  |
| 251-500  | 2         | 3.45%   |
| 501-1000 | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1      | 25%     |
| Seagate ST9120822AS 120GB        | 1         | 1      | 25%     |
| Seagate ST500DM002-1BD142 500GB  | 1         | 1      | 25%     |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 50%     |
| WDC      | 1         | 1      | 25%     |
| Kingston | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 39        | 66     | 65%     |
| Works    | 16        | 22     | 26.67%  |
| Malfunc  | 4         | 4      | 6.67%   |
| Failed   | 1         | 1      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 45        | 70.31%  |
| AMD                         | 8         | 12.5%   |
| Marvell Technology Group    | 3         | 4.69%   |
| Samsung Electronics         | 2         | 3.13%   |
| SK hynix                    | 1         | 1.56%   |
| Silicon Motion              | 1         | 1.56%   |
| SanDisk                     | 1         | 1.56%   |
| Phison Electronics          | 1         | 1.56%   |
| MAXIO Technology (Hangzhou) | 1         | 1.56%   |
| KIOXIA                      | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 9.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 7.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 6.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 5.26%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3         | 3.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 3.95%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3         | 3.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 3.95%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 2.63%   |
| AMD FCH SATA Controller D                                                               | 2         | 2.63%   |
| SK hynix BC511                                                                          | 1         | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.32%   |
| SanDisk NVMe Controller                                                                 | 1         | 1.32%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.32%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1         | 1.32%   |
| KIOXIA Non-Volatile memory controller                                                   | 1         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 1.32%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 1         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 1.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 70.97%  |
| IDE  | 10        | 16.13%  |
| NVMe | 7         | 11.29%  |
| RAID | 1         | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 84.21%  |
| AMD    | 9         | 15.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 3         | 5.26%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 3.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 3.51%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 3.51%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 3.51%   |
| Intel Pentium CPU G2010 @ 2.80GHz       | 1         | 1.75%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 1         | 1.75%   |
| Intel Pentium CPU B950 @ 2.10GHz        | 1         | 1.75%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.75%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1         | 1.75%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.75%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.75%   |
| Intel Core i5-7600 CPU @ 3.50GHz        | 1         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.75%   |
| Intel Core i5-6400T CPU @ 2.20GHz       | 1         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1         | 1.75%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 1.75%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.75%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 1.75%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 1.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.75%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 1.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.75%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 1         | 1.75%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.75%   |
| Intel Core i3 CPU 540 @ 3.07GHz         | 1         | 1.75%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz   | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz    | 1         | 1.75%   |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 1         | 1.75%   |
| Intel Core 2 CPU T5200 @ 1.60GHz        | 1         | 1.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 1         | 1.75%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 13        | 22.81%  |
| Intel Core i3     | 10        | 17.54%  |
| Intel Core i7     | 8         | 14.04%  |
| Other             | 6         | 10.53%  |
| Intel Core 2 Quad | 4         | 7.02%   |
| Intel Pentium     | 3         | 5.26%   |
| AMD A8            | 3         | 5.26%   |
| Intel Core 2      | 2         | 3.51%   |
| Intel Celeron     | 2         | 3.51%   |
| AMD Ryzen 5       | 2         | 3.51%   |
| Intel Core i9     | 1         | 1.75%   |
| Intel Core 2 Duo  | 1         | 1.75%   |
| AMD C-50          | 1         | 1.75%   |
| AMD A10           | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 50.88%  |
| 4      | 21        | 36.84%  |
| 6      | 6         | 10.53%  |
| 8      | 1         | 1.75%   |

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
| 2      | 34        | 59.65%  |
| 1      | 23        | 40.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 57.63%  |
| 0x306a9    | 4         | 6.78%   |
| 0x306c3    | 2         | 3.39%   |
| 0x07030105 | 2         | 3.39%   |
| 0x906ed    | 1         | 1.69%   |
| 0x906eb    | 1         | 1.69%   |
| 0x906ea    | 1         | 1.69%   |
| 0x906e9    | 1         | 1.69%   |
| 0x90675    | 1         | 1.69%   |
| 0x806ea    | 1         | 1.69%   |
| 0x806c1    | 1         | 1.69%   |
| 0x6f6      | 1         | 1.69%   |
| 0x506e3    | 1         | 1.69%   |
| 0x406e3    | 1         | 1.69%   |
| 0x306d4    | 1         | 1.69%   |
| 0x20655    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08608102 | 1         | 1.69%   |
| 0x06006705 | 1         | 1.69%   |
| 0x0600611a | 1         | 1.69%   |
| 0x05000029 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 15.79%  |
| Haswell     | 7         | 12.28%  |
| IvyBridge   | 6         | 10.53%  |
| Core        | 6         | 10.53%  |
| Excavator   | 4         | 7.02%   |
| Westmere    | 3         | 5.26%   |
| TigerLake   | 3         | 5.26%   |
| SandyBridge | 3         | 5.26%   |
| Broadwell   | 3         | 5.26%   |
| Skylake     | 2         | 3.51%   |
| Puma        | 2         | 3.51%   |
| CometLake   | 2         | 3.51%   |
| Unknown     | 2         | 3.51%   |
| Zen 2       | 1         | 1.75%   |
| Silvermont  | 1         | 1.75%   |
| Penryn      | 1         | 1.75%   |
| Goldmont    | 1         | 1.75%   |
| Bobcat      | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 54.29%  |
| AMD    | 18        | 25.71%  |
| Nvidia | 14        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 6.41%   |
| Nvidia GT200 [GeForce GTX 260]                                                        | 3         | 3.85%   |
| Intel UHD Graphics 620                                                                | 3         | 3.85%   |
| Intel HD Graphics 5500                                                                | 3         | 3.85%   |
| Nvidia GT218 [GeForce 210]                                                            | 2         | 2.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 2         | 2.56%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 2         | 2.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 2.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 2.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 2.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 2.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 2.56%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 2         | 2.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 1         | 1.28%   |
| Nvidia GT218M [GeForce 315M]                                                          | 1         | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 1.28%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 1.28%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 420M]                                                       | 1         | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 1         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 1         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 1         | 1.28%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.28%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.28%   |
| Intel HD Graphics 630                                                                 | 1         | 1.28%   |
| Intel HD Graphics 620                                                                 | 1         | 1.28%   |
| Intel HD Graphics 530                                                                 | 1         | 1.28%   |
| Intel HD Graphics 520                                                                 | 1         | 1.28%   |
| Intel HD Graphics 500                                                                 | 1         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 43.86%  |
| 1 x Nvidia     | 9         | 15.79%  |
| 1 x AMD        | 8         | 14.04%  |
| 2 x AMD        | 5         | 8.77%   |
| Intel + Nvidia | 5         | 8.77%   |
| Intel + AMD    | 5         | 8.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 98.25%  |
| Proprietary | 1         | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 75.86%  |
| 0.01-0.5   | 6         | 10.34%  |
| 0.51-1.0   | 4         | 6.9%    |
| 1.01-2.0   | 3         | 5.17%   |
| 5.01-6.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 15.79%  |
| Samsung Electronics     | 7         | 12.28%  |
| Chimei Innolux          | 7         | 12.28%  |
| Goldstar                | 6         | 10.53%  |
| BOE                     | 5         | 8.77%   |
| AU Optronics            | 5         | 8.77%   |
| LG Philips              | 2         | 3.51%   |
| Hewlett-Packard         | 2         | 3.51%   |
| Dell                    | 2         | 3.51%   |
| Chi Mei Optoelectronics | 2         | 3.51%   |
| Acer                    | 2         | 3.51%   |
| SAC                     | 1         | 1.75%   |
| Lenovo                  | 1         | 1.75%   |
| Iiyama                  | 1         | 1.75%   |
| HKC                     | 1         | 1.75%   |
| Beko                    | 1         | 1.75%   |
| AOC                     | 1         | 1.75%   |
| Ancor Communications    | 1         | 1.75%   |
| AGO                     | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 3         | 5.08%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch        | 1         | 1.69%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 1.69%   |
| Samsung Electronics S27H65x SAM0E1E 1920x1080 598x336mm 27.0-inch        | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 1.69%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                          | 1         | 1.69%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 1.69%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 1.69%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 1.69%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 1.69%   |
| HKC Monitor HKC2160 1920x1080 304x228mm 15.0-inch                        | 1         | 1.69%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x287mm 23.0-inch        | 1         | 1.69%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch         | 1         | 1.69%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                    | 1         | 1.69%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                     | 1         | 1.69%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 1.69%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                        | 1         | 1.69%   |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                       | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 39.29%  |
| 1366x768 (WXGA)    | 21        | 37.5%   |
| 1680x1050 (WSXGA+) | 3         | 5.36%   |
| 1600x900 (HD+)     | 3         | 5.36%   |
| 1280x800 (WXGA)    | 2         | 3.57%   |
| 1280x1024 (SXGA)   | 2         | 3.57%   |
| 3840x2160 (4K)     | 1         | 1.79%   |
| 2160x1440          | 1         | 1.79%   |
| 1440x900 (WXGA+)   | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 26        | 44.83%  |
| 23     | 8         | 13.79%  |
| 17     | 4         | 6.9%    |
| 13     | 4         | 6.9%    |
| 21     | 3         | 5.17%   |
| 14     | 3         | 5.17%   |
| 27     | 2         | 3.45%   |
| 12     | 2         | 3.45%   |
| 72     | 1         | 1.72%   |
| 31     | 1         | 1.72%   |
| 22     | 1         | 1.72%   |
| 20     | 1         | 1.72%   |
| 19     | 1         | 1.72%   |
| 11     | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 57.89%  |
| 401-500     | 9         | 15.79%  |
| 501-600     | 7         | 12.28%  |
| 201-300     | 4         | 7.02%   |
| 351-400     | 2         | 3.51%   |
| 601-700     | 1         | 1.75%   |
| 1501-2000   | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 76.79%  |
| 3/2   | 4         | 7.14%   |
| 16/10 | 4         | 7.14%   |
| 4/3   | 3         | 5.36%   |
| 5/4   | 2         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 44.83%  |
| 201-250        | 12        | 20.69%  |
| 81-90          | 7         | 12.07%  |
| 151-200        | 3         | 5.17%   |
| 301-350        | 2         | 3.45%   |
| 141-150        | 2         | 3.45%   |
| More than 1000 | 1         | 1.72%   |
| 71-80          | 1         | 1.72%   |
| 61-70          | 1         | 1.72%   |
| 51-60          | 1         | 1.72%   |
| 351-500        | 1         | 1.72%   |
| 131-140        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 21        | 36.21%  |
| 51-100  | 20        | 34.48%  |
| 121-160 | 13        | 22.41%  |
| 161-240 | 3         | 5.17%   |
| 1-50    | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 91.23%  |
| 2     | 4         | 7.02%   |
| 0     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 51.81%  |
| Intel                 | 19        | 22.89%  |
| Qualcomm Atheros      | 7         | 8.43%   |
| Broadcom              | 4         | 4.82%   |
| Ralink                | 3         | 3.61%   |
| Ralink Technology     | 2         | 2.41%   |
| ASUSTek Computer      | 2         | 2.41%   |
| ZyXEL Communications  | 1         | 1.2%    |
| Xiaomi                | 1         | 1.2%    |
| JMicron Technology    | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 32.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 6.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 2.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 2.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.92%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 1.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.92%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.96%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.96%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.96%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.96%   |
| Intel Wireless 7265                                               | 1         | 0.96%   |
| Intel Wireless 7260                                               | 1         | 0.96%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.96%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.96%   |
| Intel Centrino Wireless-N 130                                     | 1         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.96%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 32.65%  |
| Realtek Semiconductor | 15        | 30.61%  |
| Qualcomm Atheros      | 6         | 12.24%  |
| Broadcom              | 4         | 8.16%   |
| Ralink                | 3         | 6.12%   |
| Ralink Technology     | 2         | 4.08%   |
| ASUSTek Computer      | 2         | 4.08%   |
| ZyXEL Communications  | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 8.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 6.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 6.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 6.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 4.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 4.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 4.08%   |
| Intel Wireless 8265 / 8275                                     | 2         | 4.08%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 4.08%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 2.04%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| Intel Wireless 7265                                            | 1         | 2.04%   |
| Intel Wireless 7260                                            | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.04%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.04%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.04%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.04%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.04%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.04%   |
| ASUS 802.11ac NIC                                              | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 77.78%  |
| Intel                 | 8         | 14.81%  |
| Xiaomi                | 1         | 1.85%   |
| Qualcomm Atheros      | 1         | 1.85%   |
| JMicron Technology    | 1         | 1.85%   |
| Broadcom              | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 34        | 61.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 12.73%  |
| Intel Ethernet Connection I217-LM                                    | 2         | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 1.82%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 1.82%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.82%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 54.08%  |
| WiFi     | 45        | 45.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 65%     |
| Ethernet | 21        | 35%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 64.91%  |
| 1     | 20        | 35.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 92.98%  |
| Yes  | 4         | 7.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 30.56%  |
| Realtek Semiconductor           | 7         | 19.44%  |
| Qualcomm Atheros Communications | 3         | 8.33%   |
| Cambridge Silicon Radio         | 3         | 8.33%   |
| Toshiba                         | 2         | 5.56%   |
| Ralink                          | 2         | 5.56%   |
| Lite-On Technology              | 2         | 5.56%   |
| IMC Networks                    | 2         | 5.56%   |
| Realtek                         | 1         | 2.78%   |
| Foxconn International           | 1         | 2.78%   |
| Foxconn / Hon Hai               | 1         | 2.78%   |
| Broadcom                        | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 13.89%  |
| Realtek Bluetooth Radio                             | 4         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 8.33%   |
| Ralink RT3290 Bluetooth                             | 2         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.56%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.78%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 2.78%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.78%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.78%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.78%   |
| Intel AX201 Bluetooth                               | 1         | 2.78%   |
| Intel AX200 Bluetooth                               | 1         | 2.78%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.78%   |
| IMC Networks Bluetooth Device                       | 1         | 2.78%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2.78%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.78%   |
| Broadcom HP Portable Valentine                      | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 69.57%  |
| AMD                   | 13        | 18.84%  |
| Nvidia                | 6         | 8.7%    |
| Kingston Technology   | 1         | 1.45%   |
| Barco Display Systems | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 7.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 5.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 4.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 4.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 3.53%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.53%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 2.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.35%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 2.35%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.35%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.18%   |
| Kingston Technology HyperX QuadCast S                                                             | 1         | 1.18%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 1.18%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.18%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.18%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.18%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.18%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.18%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 37.5%   |
| SK hynix            | 3         | 12.5%   |
| Kingston            | 3         | 12.5%   |
| Micron Technology   | 2         | 8.33%   |
| A-DATA Technology   | 2         | 8.33%   |
| Unknown (0x4509)    | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |
| Kingmax             | 1         | 4.17%   |
| G.Skill             | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 2         | 8%      |
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 4%      |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 4%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 4%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 4%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 4%      |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s              | 1         | 4%      |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 4%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 4%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 4%      |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 4%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 4%      |
| Samsung RAM M378A2K43DB1-CTD 16GB DIMM DDR4 2667MT/s               | 1         | 4%      |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s               | 1         | 4%      |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s               | 1         | 4%      |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                  | 1         | 4%      |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s              | 1         | 4%      |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 4%      |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 4%      |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 4%      |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 4%      |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 4%      |
| Unknown                                                            | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 13        | 59.09%  |
| DDR3  | 7         | 31.82%  |
| SDRAM | 1         | 4.55%   |
| DDR2  | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 66.67%  |
| DIMM         | 6         | 28.57%  |
| Row Of Chips | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 54.55%  |
| 4096  | 6         | 27.27%  |
| 2048  | 3         | 13.64%  |
| 16384 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 5         | 22.73%  |
| 3200    | 4         | 18.18%  |
| 2667    | 4         | 18.18%  |
| 2133    | 4         | 18.18%  |
| 1333    | 2         | 9.09%   |
| 3400    | 1         | 4.55%   |
| 2400    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Zebra           | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Hewlett-Packard | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra TLP2844                    | 2         | 28.57%  |
| Zebra Zebra GC420d Label Printer | 1         | 14.29%  |
| HP LaserJet P1102                | 1         | 14.29%  |
| Canon PIXMA MX340                | 1         | 14.29%  |
| Canon LBP6030w/6018w             | 1         | 14.29%  |
| Canon LBP6000                    | 1         | 14.29%  |

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
| Chicony Electronics                    | 14        | 35.9%   |
| Realtek Semiconductor                  | 4         | 10.26%  |
| Microdia                               | 3         | 7.69%   |
| IMC Networks                           | 3         | 7.69%   |
| Luxvisions Innotech Limited            | 2         | 5.13%   |
| Acer                                   | 2         | 5.13%   |
| Syntek                                 | 1         | 2.56%   |
| Suyin                                  | 1         | 2.56%   |
| Silicon Motion                         | 1         | 2.56%   |
| MacroSilicon                           | 1         | 2.56%   |
| Lite-On Technology                     | 1         | 2.56%   |
| Foxconn / Hon Hai                      | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.56%   |
| Bison Electronics                      | 1         | 2.56%   |
| Arkmicro Technologies                  | 1         | 2.56%   |
| ALi                                    | 1         | 2.56%   |
| Alcor Micro                            | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                           | 2         | 5.13%   |
| Chicony Integrated Camera                           | 2         | 5.13%   |
| Chicony EasyCamera                                  | 2         | 5.13%   |
| Acer EasyCamera                                     | 2         | 5.13%   |
| Syntek Integrated Camera                            | 1         | 2.56%   |
| Suyin HP Webcam                                     | 1         | 2.56%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 2.56%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 2.56%   |
| Realtek HP 2.0MP High Definition Webcam             | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.56%   |
| Microdia Integrated Camera                          | 1         | 2.56%   |
| MacroSilicon USB Video                              | 1         | 2.56%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 2.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.56%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.56%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 2.56%   |
| IMC Networks EasyCamera                             | 1         | 2.56%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.56%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.56%   |
| Chicony USB2.0 Camera                               | 1         | 2.56%   |
| Chicony USB 2.0 Camera                              | 1         | 2.56%   |
| Chicony HP Truevision HD                            | 1         | 2.56%   |
| Chicony HP High Definition 1MP Webcam               | 1         | 2.56%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 2.56%   |
| Chicony Front Camera                                | 1         | 2.56%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.56%   |
| Chicony CNA7157                                     | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 2.56%   |
| Bison SunplusIT Integrated Camera                   | 1         | 2.56%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 2.56%   |
| ALi Gateway Webcam                                  | 1         | 2.56%   |
| Alcor Micro USB 2.0 PC Camera                       | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| AuthenTec                  | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 33.33%  |
| Shenzhen Goodix  Fingerprint Device          | 1         | 33.33%  |
| AuthenTec AES1600                            | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Advanced Card Systems | 2         | 66.67%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 76.27%  |
| 1     | 11        | 18.64%  |
| 2     | 3         | 5.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 25%     |
| Fingerprint reader       | 3         | 18.75%  |
| Communication controller | 2         | 12.5%   |
| Chipcard                 | 2         | 12.5%   |
| Camera                   | 2         | 12.5%   |
| Bluetooth                | 2         | 12.5%   |
| Net/wireless             | 1         | 6.25%   |


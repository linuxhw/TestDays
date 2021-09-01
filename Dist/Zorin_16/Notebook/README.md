Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 48        | 62.34%  |
| 5.11.0-25-generic | 7         | 9.09%   |
| 5.8.0-53-generic  | 6         | 7.79%   |
| 5.8.0-59-generic  | 5         | 6.49%   |
| 5.8.0-55-generic  | 5         | 6.49%   |
| 5.8.0-50-generic  | 4         | 5.19%   |
| 5.8.0-63-generic  | 1         | 1.3%    |
| 5.10.0-1044-oem   | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 55        | 71.43%  |
| 5.8.0   | 21        | 27.27%  |
| 5.10.0  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 55        | 71.43%  |
| 5.8     | 21        | 27.27%  |
| 5.10    | 1         | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 75        | 98.68%  |
| Unknown | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 73        | 96.05%  |
| Wayland | 2         | 2.63%   |
| Unknown | 1         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 81.58%  |
| GDM     | 14        | 18.42%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 25%     |
| de_DE | 10        | 13.16%  |
| en_GB | 9         | 11.84%  |
| pt_BR | 6         | 7.89%   |
| en_IN | 6         | 7.89%   |
| es_ES | 5         | 6.58%   |
| es_MX | 3         | 3.95%   |
| en_CA | 3         | 3.95%   |
| nl_NL | 2         | 2.63%   |
| hu_HU | 2         | 2.63%   |
| ru_UA | 1         | 1.32%   |
| pl_PL | 1         | 1.32%   |
| ja_JP | 1         | 1.32%   |
| it_IT | 1         | 1.32%   |
| fr_FR | 1         | 1.32%   |
| es_PE | 1         | 1.32%   |
| es_CL | 1         | 1.32%   |
| en_ZA | 1         | 1.32%   |
| en_PH | 1         | 1.32%   |
| en_NZ | 1         | 1.32%   |
| bg_BG | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 54        | 71.05%  |
| BIOS | 22        | 28.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 96.05%  |
| Zfs     | 1         | 1.32%   |
| Overlay | 1         | 1.32%   |
| Btrfs   | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 81.58%  |
| GPT     | 14        | 18.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 98.68%  |
| Yes       | 1         | 1.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 86.84%  |
| Yes       | 10        | 13.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 16        | 21.05%  |
| Dell             | 14        | 18.42%  |
| Acer             | 12        | 15.79%  |
| Hewlett-Packard  | 11        | 14.47%  |
| ASUSTek Computer | 8         | 10.53%  |
| LG Electronics   | 3         | 3.95%   |
| Apple            | 3         | 3.95%   |
| Toshiba          | 2         | 2.63%   |
| TianBei          | 1         | 1.32%   |
| Sony             | 1         | 1.32%   |
| Razer            | 1         | 1.32%   |
| Packard Bell     | 1         | 1.32%   |
| Insyde           | 1         | 1.32%   |
| Fujitsu          | 1         | 1.32%   |
| Unknown          | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 5566                       | 2         | 2.63%   |
| Unknown                                  | 2         | 2.63%   |
| Toshiba Satellite S75Dt-A                | 1         | 1.32%   |
| Toshiba Satellite C850D-11C              | 1         | 1.32%   |
| TianBei TB-H7                            | 1         | 1.32%   |
| Sony VGN-SR5                             | 1         | 1.32%   |
| Razer Book 13 - RZ09-0357                | 1         | 1.32%   |
| Packard Bell DOT S                       | 1         | 1.32%   |
| LG S460-G.BG31P1                         | 1         | 1.32%   |
| LG A410-K.BE47P1                         | 1         | 1.32%   |
| LG 17U70N-R.AAS7U1                       | 1         | 1.32%   |
| Lenovo Yoga 3 Pro-1370 80HE              | 1         | 1.32%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00      | 1         | 1.32%   |
| Lenovo ThinkPad X131e 3371AL2            | 1         | 1.32%   |
| Lenovo ThinkPad T520 4242W4F             | 1         | 1.32%   |
| Lenovo ThinkPad T440p 20AWS1CH00         | 1         | 1.32%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA     | 1         | 1.32%   |
| Lenovo IdeaPad Z510 20287                | 1         | 1.32%   |
| Lenovo IdeaPad Y570 0862                 | 1         | 1.32%   |
| Lenovo IdeaPad S540-14API 81NH           | 1         | 1.32%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.32%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 1.32%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 1         | 1.32%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 1.32%   |
| Lenovo G50-70 20351                      | 1         | 1.32%   |
| Lenovo G50-30 80G0                       | 1         | 1.32%   |
| Lenovo B50-70 80EU                       | 1         | 1.32%   |
| Insyde i101c                             | 1         | 1.32%   |
| HP ProBook 650 G2                        | 1         | 1.32%   |
| HP ProBook 450 G2                        | 1         | 1.32%   |
| HP ProBook 430 G6                        | 1         | 1.32%   |
| HP Pavilion 15                           | 1         | 1.32%   |
| HP Notebook                              | 1         | 1.32%   |
| HP ENVY Sleekbook 4 PC                   | 1         | 1.32%   |
| HP ENVY 15                               | 1         | 1.32%   |
| HP ENVY 14                               | 1         | 1.32%   |
| HP EliteBook 840 G1                      | 1         | 1.32%   |
| HP 15                                    | 1         | 1.32%   |
| Fujitsu LIFEBOOK AH532                   | 1         | 1.32%   |
| Dell XPS L501X                           | 1         | 1.32%   |
| Dell XPS 15 9560                         | 1         | 1.32%   |
| Dell XPS 13 9370                         | 1         | 1.32%   |
| Dell XPS 13 9310                         | 1         | 1.32%   |
| Dell Vostro 5490                         | 1         | 1.32%   |
| Dell Precision M4800                     | 1         | 1.32%   |
| Dell Inspiron N5040                      | 1         | 1.32%   |
| Dell Inspiron 7537                       | 1         | 1.32%   |
| Dell Inspiron 7520                       | 1         | 1.32%   |
| Dell Inspiron 3582                       | 1         | 1.32%   |
| Dell Inspiron 3576                       | 1         | 1.32%   |
| Dell G3 3579                             | 1         | 1.32%   |
| ASUS X550LD                              | 1         | 1.32%   |
| ASUS X406UAR                             | 1         | 1.32%   |
| ASUS X405UA                              | 1         | 1.32%   |
| ASUS TUF Gaming FX505DT_FX505DT          | 1         | 1.32%   |
| ASUS K73SV                               | 1         | 1.32%   |
| ASUS K56CA                               | 1         | 1.32%   |
| ASUS GR8                                 | 1         | 1.32%   |
| ASUS ASUS TUF Gaming A15 FA506IH_FA506IH | 1         | 1.32%   |
| Apple MacBookPro11,5                     | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 8         | 10.53%  |
| Lenovo IdeaPad     | 7         | 9.21%   |
| Dell Inspiron      | 7         | 9.21%   |
| Lenovo ThinkPad    | 5         | 6.58%   |
| Dell XPS           | 4         | 5.26%   |
| HP ProBook         | 3         | 3.95%   |
| HP ENVY            | 3         | 3.95%   |
| Toshiba Satellite  | 2         | 2.63%   |
| Apple MacBookPro11 | 2         | 2.63%   |
| Acer Swift         | 2         | 2.63%   |
| Unknown            | 2         | 2.63%   |
| TianBei TB-H7      | 1         | 1.32%   |
| Sony VGN-SR5       | 1         | 1.32%   |
| Razer Book         | 1         | 1.32%   |
| Packard Bell DOT   | 1         | 1.32%   |
| LG S460-G.BG31P1   | 1         | 1.32%   |
| LG A410-K.BE47P1   | 1         | 1.32%   |
| LG 17U70N-R.AAS7U1 | 1         | 1.32%   |
| Lenovo Yoga        | 1         | 1.32%   |
| Lenovo G50-70      | 1         | 1.32%   |
| Lenovo G50-30      | 1         | 1.32%   |
| Lenovo B50-70      | 1         | 1.32%   |
| Insyde i101c       | 1         | 1.32%   |
| HP Pavilion        | 1         | 1.32%   |
| HP Notebook        | 1         | 1.32%   |
| HP EliteBook       | 1         | 1.32%   |
| HP 15              | 1         | 1.32%   |
| Fujitsu LIFEBOOK   | 1         | 1.32%   |
| Dell Vostro        | 1         | 1.32%   |
| Dell Precision     | 1         | 1.32%   |
| Dell G3            | 1         | 1.32%   |
| ASUS X550LD        | 1         | 1.32%   |
| ASUS X406UAR       | 1         | 1.32%   |
| ASUS X405UA        | 1         | 1.32%   |
| ASUS TUF           | 1         | 1.32%   |
| ASUS K73SV         | 1         | 1.32%   |
| ASUS K56CA         | 1         | 1.32%   |
| ASUS GR8           | 1         | 1.32%   |
| ASUS ASUS          | 1         | 1.32%   |
| Apple MacBook4     | 1         | 1.32%   |
| Acer Nitro         | 1         | 1.32%   |
| Acer AO722         | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 15        | 19.74%  |
| 2020 | 9         | 11.84%  |
| 2019 | 9         | 11.84%  |
| 2018 | 7         | 9.21%   |
| 2014 | 7         | 9.21%   |
| 2011 | 6         | 7.89%   |
| 2012 | 5         | 6.58%   |
| 2015 | 4         | 5.26%   |
| 2017 | 3         | 3.95%   |
| 2013 | 3         | 3.95%   |
| 2008 | 3         | 3.95%   |
| 2016 | 2         | 2.63%   |
| 2010 | 1         | 1.32%   |
| 2009 | 1         | 1.32%   |
| 2006 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 76        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 62        | 81.58%  |
| Enabled  | 14        | 18.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 31.58%  |
| 3.01-4.0   | 22        | 28.95%  |
| 8.01-16.0  | 13        | 17.11%  |
| 16.01-24.0 | 11        | 14.47%  |
| 32.01-64.0 | 3         | 3.95%   |
| 1.01-2.0   | 3         | 3.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 35        | 45.45%  |
| 2.01-3.0 | 25        | 32.47%  |
| 3.01-4.0 | 11        | 14.29%  |
| 4.01-8.0 | 5         | 6.49%   |
| 0.51-1.0 | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 73.68%  |
| 2      | 18        | 23.68%  |
| 3      | 2         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 59.21%  |
| Yes       | 31        | 40.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 85.53%  |
| No        | 11        | 14.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 97.37%  |
| No        | 2         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 77.63%  |
| No        | 17        | 22.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 12        | 15.79%  |
| USA          | 9         | 11.84%  |
| Brazil       | 9         | 11.84%  |
| UK           | 7         | 9.21%   |
| India        | 7         | 9.21%   |
| Spain        | 5         | 6.58%   |
| Mexico       | 4         | 5.26%   |
| Hungary      | 3         | 3.95%   |
| Netherlands  | 2         | 2.63%   |
| Canada       | 2         | 2.63%   |
| Vietnam      | 1         | 1.32%   |
| Ukraine      | 1         | 1.32%   |
| South Africa | 1         | 1.32%   |
| Romania      | 1         | 1.32%   |
| Poland       | 1         | 1.32%   |
| Philippines  | 1         | 1.32%   |
| New Zealand  | 1         | 1.32%   |
| Madagascar   | 1         | 1.32%   |
| Kenya        | 1         | 1.32%   |
| Japan        | 1         | 1.32%   |
| Italy        | 1         | 1.32%   |
| France       | 1         | 1.32%   |
| Colombia     | 1         | 1.32%   |
| Chile        | 1         | 1.32%   |
| Bulgaria     | 1         | 1.32%   |
| Austria      | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| S??o Lu?�s               | 2         | 2.6%    |
| Madrid                   | 2         | 2.6%    |
| Hyderabad                | 2         | 2.6%    |
| Zabrze                   | 1         | 1.3%    |
| Yokohama                 | 1         | 1.3%    |
| Vienna                   | 1         | 1.3%    |
| Veracruz                 | 1         | 1.3%    |
| Vancouver                | 1         | 1.3%    |
| Taboao da Serra          | 1         | 1.3%    |
| Sutton Coldfield         | 1         | 1.3%    |
| Stadskanaal              | 1         | 1.3%    |
| Spremberg                | 1         | 1.3%    |
| Seville                  | 1         | 1.3%    |
| S??o Jo??o del Rei       | 1         | 1.3%    |
| Santa Cruz do Rio Pardo  | 1         | 1.3%    |
| Sant Carles de la Rapita | 1         | 1.3%    |
| San Francisco            | 1         | 1.3%    |
| Sainte-Marie             | 1         | 1.3%    |
| Rome                     | 1         | 1.3%    |
| R??sselsheim am Main     | 1         | 1.3%    |
| Quezon City              | 1         | 1.3%    |
| Pretoria                 | 1         | 1.3%    |
| Ohmbach                  | 1         | 1.3%    |
| Nyiregyhaza              | 1         | 1.3%    |
| Nottingham               | 1         | 1.3%    |
| Noblesville              | 1         | 1.3%    |
| New York                 | 1         | 1.3%    |
| Naumburg                 | 1         | 1.3%    |
| Nairobi                  | 1         | 1.3%    |
| Mérida                  | 1         | 1.3%    |
| Mumbai                   | 1         | 1.3%    |
| Morro do Chapeu          | 1         | 1.3%    |
| Montreal                 | 1         | 1.3%    |
| Montana                  | 1         | 1.3%    |
| Mexico City              | 1         | 1.3%    |
| Manchester               | 1         | 1.3%    |
| Macei??                  | 1         | 1.3%    |
| London                   | 1         | 1.3%    |
| Lathen                   | 1         | 1.3%    |
| Landshut                 | 1         | 1.3%    |
| Kyiv                     | 1         | 1.3%    |
| Kolkata                  | 1         | 1.3%    |
| Knoxville                | 1         | 1.3%    |
| Kingston                 | 1         | 1.3%    |
| Kelkheim (Taunus)        | 1         | 1.3%    |
| Ho Chi Minh City         | 1         | 1.3%    |
| Hartheim                 | 1         | 1.3%    |
| Hamm (Sieg)              | 1         | 1.3%    |
| Galgamacsa               | 1         | 1.3%    |
| Frechen                  | 1         | 1.3%    |
| Fortaleza                | 1         | 1.3%    |
| Finchley                 | 1         | 1.3%    |
| Ernakulam                | 1         | 1.3%    |
| Dudley                   | 1         | 1.3%    |
| Dortmund                 | 1         | 1.3%    |
| Coronel                  | 1         | 1.3%    |
| Concord                  | 1         | 1.3%    |
| Chennai                  | 1         | 1.3%    |
| Chatham                  | 1         | 1.3%    |
| Charlotte                | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 16.67%  |
| Samsung Electronics | 14        | 15     | 15.56%  |
| Toshiba             | 9         | 9      | 10%     |
| SanDisk             | 8         | 9      | 8.89%   |
| WDC                 | 6         | 6      | 6.67%   |
| Kingston            | 4         | 5      | 4.44%   |
| HGST                | 4         | 4      | 4.44%   |
| Unknown             | 3         | 3      | 3.33%   |
| Hitachi             | 3         | 3      | 3.33%   |
| Crucial             | 3         | 3      | 3.33%   |
| LITEONIT            | 2         | 3      | 2.22%   |
| Intel               | 2         | 2      | 2.22%   |
| Fujitsu             | 2         | 2      | 2.22%   |
| Apple               | 2         | 2      | 2.22%   |
| A-DATA Technology   | 2         | 2      | 2.22%   |
| Vaseky              | 1         | 1      | 1.11%   |
| SPCC                | 1         | 1      | 1.11%   |
| SK Hynix            | 1         | 1      | 1.11%   |
| PNY                 | 1         | 1      | 1.11%   |
| Phison              | 1         | 1      | 1.11%   |
| Micron Technology   | 1         | 1      | 1.11%   |
| KIOXIA              | 1         | 1      | 1.11%   |
| KingSpec            | 1         | 1      | 1.11%   |
| Intenso             | 1         | 1      | 1.11%   |
| China               | 1         | 1      | 1.11%   |
| BUFFALO             | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3.26%   |
| Unknown SD/MMC/MS PRO 128GB              | 2         | 2.17%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2.17%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 2.17%   |
| Seagate ST9500325AS 500GB                | 2         | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2.17%   |
| SanDisk SSD PLUS 480GB                   | 2         | 2.17%   |
| Sandisk NVMe SSD Drive 256GB             | 2         | 2.17%   |
| Samsung NVMe SSD Drive 512GB             | 2         | 2.17%   |
| Kingston SA400S37480G 480GB SSD          | 2         | 2.17%   |
| HGST HTS725050A7E630 500GB               | 2         | 2.17%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1.09%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1.09%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1.09%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1.09%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1.09%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB     | 1         | 1.09%   |
| Vaseky V820/256G 256GB                   | 1         | 1.09%   |
| Unknown NCard  32GB                      | 1         | 1.09%   |
| Toshiba THNSNJ128GCSU 128GB SSD          | 1         | 1.09%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1.09%   |
| Toshiba KXG50ZNV1T02 NVMe 1024GB         | 1         | 1.09%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1.09%   |
| Toshiba KBG40ZMT128G MEMORY 128GB        | 1         | 1.09%   |
| SPCC SPCCSolidStateDisk 256GB SSD        | 1         | 1.09%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.09%   |
| Seagate USB 500GB                        | 1         | 1.09%   |
| Seagate ST9750423AS 752GB                | 1         | 1.09%   |
| Seagate ST500LM030-1RK17D 500GB          | 1         | 1.09%   |
| Seagate ST500LM021-1KJ152 500GB          | 1         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1.09%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 1.09%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.09%   |
| Seagate ST1000LM014-1EJ1 1TB             | 1         | 1.09%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1.09%   |
| SanDisk SSD i100 24GB                    | 1         | 1.09%   |
| SanDisk SD8SN8U256G1002 256GB SSD        | 1         | 1.09%   |
| Sandisk NVMe SSD Drive 128GB             | 1         | 1.09%   |
| Samsung SSD SM841N mSATA 256GB SED       | 1         | 1.09%   |
| Samsung SSD PM830 2.5 7mm 128GB          | 1         | 1.09%   |
| Samsung SSD 860 PRO 256GB                | 1         | 1.09%   |
| Samsung SSD 860 EVO 250GB                | 1         | 1.09%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 1.09%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.09%   |
| Samsung SSD 840 EVO 250GB                | 1         | 1.09%   |
| Samsung NVMe SSD Drive 2TB               | 1         | 1.09%   |
| Samsung MZVLB512HBJQ-00A00 512GB         | 1         | 1.09%   |
| Samsung MZALQ512HBLU-00BL2 512GB         | 1         | 1.09%   |
| Samsung HM640JJ 640GB                    | 1         | 1.09%   |
| Samsung HM321HI 320GB                    | 1         | 1.09%   |
| Samsung HM160HI 160GB                    | 1         | 1.09%   |
| PNY CS900 120GB SSD                      | 1         | 1.09%   |
| Phison NVMe SSD Drive 2TB                | 1         | 1.09%   |
| Micron MTFDDAK256TBN-1AR1ZABHA 256GB SSD | 1         | 1.09%   |
| LITEONIT LMS-32L6M mSATA 32GB SSD        | 1         | 1.09%   |
| LITEONIT LCT-512L9S-11 2.5 7mm 512GB SSD | 1         | 1.09%   |
| LITEONIT LCS-512M6S 2.5 7mm 512GB SSD    | 1         | 1.09%   |
| KIOXIA NVMe SSD Drive 512GB              | 1         | 1.09%   |
| Kingston SA400S37960G 960GB SSD          | 1         | 1.09%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 38.89%  |
| WDC                 | 5         | 5      | 13.89%  |
| Toshiba             | 5         | 5      | 13.89%  |
| HGST                | 4         | 4      | 11.11%  |
| Samsung Electronics | 3         | 3      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| Fujitsu             | 2         | 2      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 18.18%  |
| SanDisk             | 5         | 6      | 15.15%  |
| Kingston            | 4         | 5      | 12.12%  |
| Crucial             | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| LITEONIT            | 2         | 3      | 6.06%   |
| Apple               | 2         | 2      | 6.06%   |
| SPCC                | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| BUFFALO             | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 36        | 36     | 41.86%  |
| SSD     | 29        | 37     | 33.72%  |
| NVMe    | 16        | 16     | 18.6%   |
| Unknown | 4         | 4      | 4.65%   |
| MMC     | 1         | 1      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 72     | 73.49%  |
| NVMe | 16        | 16     | 19.28%  |
| SAS  | 5         | 5      | 6.02%   |
| MMC  | 1         | 1      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 51     | 68.75%  |
| 0.51-1.0   | 19        | 21     | 29.69%  |
| 1.01-2.0   | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 27        | 35.53%  |
| 101-250    | 24        | 31.58%  |
| 501-1000   | 11        | 14.47%  |
| 51-100     | 7         | 9.21%   |
| 21-50      | 3         | 3.95%   |
| 1001-2000  | 3         | 3.95%   |
| Unknown    | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 41        | 53.95%  |
| 21-50    | 21        | 27.63%  |
| 101-250  | 5         | 6.58%   |
| 251-500  | 3         | 3.95%   |
| 51-100   | 3         | 3.95%   |
| 501-1000 | 2         | 2.63%   |
| Unknown  | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 66.67%  |
| HGST HTS725050A7E630 500GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 63        | 79     | 81.82%  |
| Works    | 10        | 11     | 12.99%  |
| Malfunc  | 3         | 3      | 3.9%    |
| Failed   | 1         | 1      | 1.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 63.86%  |
| AMD                              | 12        | 14.46%  |
| Samsung Electronics              | 7         | 8.43%   |
| Sandisk                          | 4         | 4.82%   |
| KIOXIA                           | 2         | 2.41%   |
| Toshiba America Info Systems     | 1         | 1.2%    |
| SK Hynix                         | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] | 1         | 1.2%    |
| Phison Electronics               | 1         | 1.2%    |
| ADATA Technology                 | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 11.49%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 9.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 9.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 4.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 4.6%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 3.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.3%    |
| Samsung NVMe Controller                                                          | 2         | 2.3%    |
| KIOXIA Non-Volatile memory controller                                            | 2         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.3%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.15%   |
| SK Hynix BC511                                                                   | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.15%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.15%   |
| Samsung Electronics SATA controller                                              | 1         | 1.15%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.15%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.15%   |
| Intel SSD 660P Series                                                            | 1         | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.15%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 1.15%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 1         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.15%   |
| AMD IXP SB4x0 IDE Controller                                                     | 1         | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 70.59%  |
| NVMe | 16        | 18.82%  |
| IDE  | 5         | 5.88%   |
| RAID | 4         | 4.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 81.58%  |
| AMD    | 14        | 18.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 5.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 3.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.63%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 1.32%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.32%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.32%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.32%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 1.32%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.32%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 1.32%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.32%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.32%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.32%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 1         | 1.32%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz          | 1         | 1.32%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.32%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 1.32%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.32%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 1.32%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.32%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 1         | 1.32%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.32%   |
| AMD Turion 64 Mobile Technology MK-36         | 1         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.32%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 1.32%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics   | 1         | 1.32%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 1.32%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.32%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 32.89%  |
| Intel Core i7           | 13        | 17.11%  |
| Intel Core i3           | 6         | 7.89%   |
| Other                   | 4         | 5.26%   |
| Intel Core 2 Duo        | 4         | 5.26%   |
| Intel Celeron           | 4         | 5.26%   |
| AMD Ryzen 5             | 4         | 5.26%   |
| Intel Pentium           | 2         | 2.63%   |
| Intel Atom              | 2         | 2.63%   |
| Intel Pentium Silver    | 1         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| AMD Turion 64 Mobile    | 1         | 1.32%   |
| AMD Ryzen 7             | 1         | 1.32%   |
| AMD FX                  | 1         | 1.32%   |
| AMD E2                  | 1         | 1.32%   |
| AMD E1                  | 1         | 1.32%   |
| AMD E                   | 1         | 1.32%   |
| AMD C-60                | 1         | 1.32%   |
| AMD Athlon              | 1         | 1.32%   |
| AMD A4                  | 1         | 1.32%   |
| AMD A10                 | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 57.89%  |
| 4      | 29        | 38.16%  |
| 8      | 1         | 1.32%   |
| 6      | 1         | 1.32%   |
| 1      | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 73.68%  |
| 1      | 20        | 26.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x40651    | 9         | 11.84%  |
| 0x306a9    | 6         | 7.89%   |
| Unknown    | 6         | 7.89%   |
| 0x806ea    | 5         | 6.58%   |
| 0x306d4    | 4         | 5.26%   |
| 0x306c3    | 4         | 5.26%   |
| 0x806ec    | 3         | 3.95%   |
| 0x806c1    | 3         | 3.95%   |
| 0x30678    | 3         | 3.95%   |
| 0x206a7    | 3         | 3.95%   |
| 0x08108109 | 3         | 3.95%   |
| 0x05000119 | 3         | 3.95%   |
| 0x806e9    | 2         | 2.63%   |
| 0x20655    | 2         | 2.63%   |
| 0x1067a    | 2         | 2.63%   |
| 0xa0652    | 1         | 1.32%   |
| 0x906ea    | 1         | 1.32%   |
| 0x906e9    | 1         | 1.32%   |
| 0x906c0    | 1         | 1.32%   |
| 0x706a1    | 1         | 1.32%   |
| 0x6fd      | 1         | 1.32%   |
| 0x6fb      | 1         | 1.32%   |
| 0x40661    | 1         | 1.32%   |
| 0x30661    | 1         | 1.32%   |
| 0x106e5    | 1         | 1.32%   |
| 0x10676    | 1         | 1.32%   |
| 0x08608102 | 1         | 1.32%   |
| 0x08600104 | 1         | 1.32%   |
| 0x08108102 | 1         | 1.32%   |
| 0x07030106 | 1         | 1.32%   |
| 0x0700010f | 1         | 1.32%   |
| 0x06003106 | 1         | 1.32%   |
| 0x06001119 | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 18.42%  |
| Haswell       | 14        | 18.42%  |
| IvyBridge     | 6         | 7.89%   |
| Zen+          | 4         | 5.26%   |
| Silvermont    | 4         | 5.26%   |
| Broadwell     | 4         | 5.26%   |
| TigerLake     | 3         | 3.95%   |
| SandyBridge   | 3         | 3.95%   |
| Penryn        | 3         | 3.95%   |
| Bobcat        | 3         | 3.95%   |
| Westmere      | 2         | 2.63%   |
| Nehalem       | 2         | 2.63%   |
| Core          | 2         | 2.63%   |
| Zen 2         | 1         | 1.32%   |
| Tremont       | 1         | 1.32%   |
| Steamroller   | 1         | 1.32%   |
| Skylake       | 1         | 1.32%   |
| Puma          | 1         | 1.32%   |
| Piledriver    | 1         | 1.32%   |
| K8 Hammer     | 1         | 1.32%   |
| Jaguar        | 1         | 1.32%   |
| Goldmont plus | 1         | 1.32%   |
| CometLake     | 1         | 1.32%   |
| Bonnell       | 1         | 1.32%   |
| Unknown       | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 59.14%  |
| AMD                              | 19        | 20.43%  |
| Nvidia                           | 18        | 19.35%  |
| Silicon Integrated Systems [SiS] | 1         | 1.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 9.47%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 6.32%   |
| Intel UHD Graphics 620                                                    | 5         | 5.26%   |
| Intel HD Graphics 620                                                     | 4         | 4.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 4.21%   |
| AMD Picasso                                                               | 4         | 4.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 3.16%   |
| Intel HD Graphics 5500                                                    | 3         | 3.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 2.11%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.05%   |
| Nvidia TU117M                                                             | 1         | 1.05%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.05%   |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 1.05%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.05%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.05%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.05%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.05%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 1         | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 555M]                                           | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 435M]                                           | 1         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.05%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                 | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.05%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.05%   |
| Intel HD Graphics 630                                                     | 1         | 1.05%   |
| Intel HD Graphics 5300                                                    | 1         | 1.05%   |
| Intel Haswell Integrated Graphics Controller                              | 1         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.05%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.05%   |
| AMD Wrestler [Radeon HD 7310]                                             | 1         | 1.05%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.05%   |
| AMD Wrestler [Radeon HD 6290]                                             | 1         | 1.05%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                           | 1         | 1.05%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1         | 1.05%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                         | 1         | 1.05%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                     | 1         | 1.05%   |
| AMD Richland [Radeon HD 8650G]                                            | 1         | 1.05%   |
| AMD Renoir                                                                | 1         | 1.05%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                   | 1         | 1.05%   |
| AMD Mullins [Radeon R3 Graphics]                                          | 1         | 1.05%   |
| AMD Lucienne                                                              | 1         | 1.05%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                        | 1         | 1.05%   |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 1.05%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]              | 1         | 1.05%   |
| AMD Chelsea LP [Radeon HD 7730M]                                          | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 52.63%  |
| 1 x AMD        | 13        | 17.11%  |
| Intel + Nvidia | 12        | 15.79%  |
| 1 x Nvidia     | 4         | 5.26%   |
| Intel + AMD    | 3         | 3.95%   |
| AMD + Nvidia   | 2         | 2.63%   |
| 2 x AMD        | 1         | 1.32%   |
| 1 x SiS        | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 81.58%  |
| Proprietary | 13        | 17.11%  |
| Unknown     | 1         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 60.53%  |
| 1.01-2.0   | 13        | 17.11%  |
| 0.01-0.5   | 9         | 11.84%  |
| 3.01-4.0   | 4         | 5.26%   |
| 0.51-1.0   | 4         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 17.5%   |
| AU Optronics            | 13        | 16.25%  |
| LG Display              | 11        | 13.75%  |
| Samsung Electronics     | 9         | 11.25%  |
| BOE                     | 8         | 10%     |
| Sharp                   | 4         | 5%      |
| Chi Mei Optoelectronics | 4         | 5%      |
| Apple                   | 3         | 3.75%   |
| PANDA                   | 2         | 2.5%    |
| Lenovo                  | 2         | 2.5%    |
| Dell                    | 2         | 2.5%    |
| Acer                    | 2         | 2.5%    |
| Vizio                   | 1         | 1.25%   |
| LGD                     | 1         | 1.25%   |
| LG Philips              | 1         | 1.25%   |
| Hewlett-Packard         | 1         | 1.25%   |
| BenQ                    | 1         | 1.25%   |
| AOC                     | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch           | 3         | 3.7%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 2         | 2.47%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                       | 1         | 1.23%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                   | 1         | 1.23%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 1         | 1.23%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.23%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch     | 1         | 1.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 1.23%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 1         | 1.23%   |
| LGD LCD Monitor 3840x1200                                                 | 1         | 1.23%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD02D1 1600x900 382x215mm 17.3-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 1         | 1.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 1         | 1.23%   |
| Hewlett-Packard LCD Monitor E241i                                         | 1         | 1.23%   |
| Dell U2414H DELA0B2 1920x1080 530x300mm 24.0-inch                         | 1         | 1.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN139E 1920x1080 293x165mm 13.2-inch          | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch  | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch  | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch  | 1         | 1.23%   |
| BOE LCD Monitor BOE08F2 1920x1080 310x174mm 14.0-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE082E 1920x1080 309x174mm 14.0-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE07DD 1920x1080 293x165mm 13.2-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 1         | 1.23%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                      | 1         | 1.23%   |
| BOE LCD Monitor BOE05E9 1366x768 256x144mm 11.6-inch                      | 1         | 1.23%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 34        | 43.59%  |
| 1920x1080 (FHD)  | 22        | 28.21%  |
| 1600x900 (HD+)   | 5         | 6.41%   |
| 3840x2160 (4K)   | 4         | 5.13%   |
| 1280x800 (WXGA)  | 3         | 3.85%   |
| 3840x2400        | 2         | 2.56%   |
| 2560x1600        | 2         | 2.56%   |
| 3840x1200        | 1         | 1.28%   |
| 3200x1800 (QHD+) | 1         | 1.28%   |
| 2880x1800        | 1         | 1.28%   |
| 2560x1440 (QHD)  | 1         | 1.28%   |
| 1024x600         | 1         | 1.28%   |
| Unknown          | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 49.37%  |
| 13      | 15        | 18.99%  |
| 14      | 7         | 8.86%   |
| 24      | 4         | 5.06%   |
| 17      | 4         | 5.06%   |
| 18      | 2         | 2.53%   |
| 11      | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 74      | 1         | 1.27%   |
| 27      | 1         | 1.27%   |
| 25      | 1         | 1.27%   |
| 10      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 65.82%  |
| 201-300     | 12        | 15.19%  |
| 501-600     | 6         | 7.59%   |
| 351-400     | 4         | 5.06%   |
| 401-500     | 2         | 2.53%   |
| Unknown     | 2         | 2.53%   |
| 1501-2000   | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 86.49%  |
| 16/10   | 8         | 10.81%  |
| Unknown | 2         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 48.75%  |
| 81-90          | 14        | 17.5%   |
| 71-80          | 8         | 10%     |
| 201-250        | 4         | 5%      |
| 121-130        | 4         | 5%      |
| 51-60          | 2         | 2.5%    |
| 141-150        | 2         | 2.5%    |
| Unknown        | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 41-50          | 1         | 1.25%   |
| 301-350        | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 91-100         | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 40        | 50.63%  |
| 121-160       | 18        | 22.78%  |
| 51-100        | 9         | 11.39%  |
| More than 240 | 5         | 6.33%   |
| 161-240       | 5         | 6.33%   |
| Unknown       | 2         | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 88.16%  |
| 2     | 8         | 10.53%  |
| 0     | 1         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 47        | 36.72%  |
| Intel                            | 32        | 25%     |
| Qualcomm Atheros                 | 19        | 14.84%  |
| Broadcom                         | 10        | 7.81%   |
| Broadcom Limited                 | 5         | 3.91%   |
| Ralink                           | 3         | 2.34%   |
| Marvell Technology Group         | 2         | 1.56%   |
| T & A Mobile Phones              | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Samsung Electronics              | 1         | 0.78%   |
| Qualcomm                         | 1         | 0.78%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.78%   |
| MediaTek                         | 1         | 0.78%   |
| ICS Advent                       | 1         | 0.78%   |
| DisplayLink                      | 1         | 0.78%   |
| D-Link System                    | 1         | 0.78%   |
| ASIX Electronics                 | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 28        | 19.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11        | 7.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 4.17%   |
| Intel Wireless 7260                                                           | 6         | 4.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 2.08%   |
| Intel WiFi Link 5100                                                          | 3         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 3         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.39%   |
| Intel Wireless 3160                                                           | 2         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.39%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 1.39%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 1.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.39%   |
| T & A Mobile Phones TCL T790S                                                 | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.69%   |
| Realtek 802.11ac NIC                                                          | 1         | 0.69%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.69%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.69%   |
| OnePlus (Shenzhen) IN2011                                                     | 1         | 0.69%   |
| MediaTek Armor X5                                                             | 1         | 0.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.69%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.69%   |
| Intel Wireless 8260                                                           | 1         | 0.69%   |
| Intel Wireless 7265                                                           | 1         | 0.69%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.69%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.69%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.69%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 0.69%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.69%   |
| Intel Centrino Wireless-N 105                                                 | 1         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1         | 0.69%   |
| Intel 82562GT 10/100 Network Connection                                       | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 39.47%  |
| Qualcomm Atheros      | 16        | 21.05%  |
| Realtek Semiconductor | 13        | 17.11%  |
| Broadcom              | 9         | 11.84%  |
| Ralink                | 3         | 3.95%   |
| Broadcom Limited      | 3         | 3.95%   |
| Qualcomm              | 1         | 1.32%   |
| D-Link System         | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 7.79%   |
| Intel Wireless 7260                                                           | 6         | 7.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 3.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 3.9%    |
| Intel WiFi Link 5100                                                          | 3         | 3.9%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 3         | 3.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 2.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 2.6%    |
| Intel Wireless 3160                                                           | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 2.6%    |
| Intel Centrino Wireless-N 2230                                                | 2         | 2.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 2.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.3%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 1.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 1.3%    |
| Realtek 802.11ac NIC                                                          | 1         | 1.3%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 1.3%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.3%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.3%    |
| Intel Wireless 8260                                                           | 1         | 1.3%    |
| Intel Wireless 7265                                                           | 1         | 1.3%    |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.3%    |
| Intel Centrino Wireless-N 130                                                 | 1         | 1.3%    |
| Intel Centrino Wireless-N 105                                                 | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 1.3%    |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1         | 1.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 1         | 1.3%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 1         | 1.3%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 1         | 1.3%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.3%    |
| Broadcom BCM43225 802.11b/g/n                                                 | 1         | 1.3%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 1.3%    |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.3%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 42        | 63.64%  |
| Intel                            | 7         | 10.61%  |
| Qualcomm Atheros                 | 5         | 7.58%   |
| Marvell Technology Group         | 2         | 3.03%   |
| Broadcom Limited                 | 2         | 3.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.52%   |
| Samsung Electronics              | 1         | 1.52%   |
| OnePlus Technology (Shenzhen)    | 1         | 1.52%   |
| MediaTek                         | 1         | 1.52%   |
| ICS Advent                       | 1         | 1.52%   |
| DisplayLink                      | 1         | 1.52%   |
| Broadcom                         | 1         | 1.52%   |
| ASIX Electronics                 | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 42.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 16.67%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.52%   |
| OnePlus (Shenzhen) IN2011                                         | 1         | 1.52%   |
| MediaTek Armor X5                                                 | 1         | 1.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.52%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.52%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.52%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.52%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.52%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 1.52%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 52.86%  |
| Ethernet | 65        | 46.43%  |
| Unknown  | 1         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 54.03%  |
| Ethernet | 56        | 45.16%  |
| Unknown  | 1         | 0.81%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 57        | 75%     |
| 1     | 18        | 23.68%  |
| 0     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 70.13%  |
| Yes  | 23        | 29.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 37.29%  |
| Qualcomm Atheros Communications | 7         | 11.86%  |
| Realtek Semiconductor           | 5         | 8.47%   |
| IMC Networks                    | 5         | 8.47%   |
| Lite-On Technology              | 4         | 6.78%   |
| Broadcom                        | 4         | 6.78%   |
| Ralink                          | 3         | 5.08%   |
| Foxconn / Hon Hai               | 3         | 5.08%   |
| Apple                           | 3         | 5.08%   |
| Foxconn International           | 2         | 3.39%   |
| Alps Electric                   | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 12        | 20.34%  |
| Qualcomm Atheros  Bluetooth Device                | 5         | 8.47%   |
| Intel Bluetooth Device                            | 5         | 8.47%   |
| Realtek Bluetooth Radio                           | 4         | 6.78%   |
| Ralink RT3290 Bluetooth                           | 3         | 5.08%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 3.39%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 3.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 3.39%   |
| IMC Networks Bluetooth Radio                      | 2         | 3.39%   |
| Foxconn International BCM43142A0 Bluetooth module | 2         | 3.39%   |
| Apple Bluetooth Host Controller                   | 2         | 3.39%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 1.69%   |
| Lite-On BCM43142A0                                | 1         | 1.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.69%   |
| IMC Networks Bluetooth Device                     | 1         | 1.69%   |
| IMC Networks Bluetooth                            | 1         | 1.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 1.69%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 1.69%   |
| Foxconn / Hon Hai BCM20702A0                      | 1         | 1.69%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 1         | 1.69%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module          | 1         | 1.69%   |
| Broadcom Bluetooth                                | 1         | 1.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.69%   |
| Apple Bluetooth HCI                               | 1         | 1.69%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 60        | 68.18%  |
| AMD                              | 16        | 18.18%  |
| Nvidia                           | 11        | 12.5%   |
| Silicon Integrated Systems [SiS] | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 8.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 7.76%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 7.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 5.17%   |
| AMD FCH Azalia Controller                                                  | 6         | 5.17%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 6         | 5.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 3.45%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.59%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.72%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.86%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.86%   |
| Intel Jasper Lake HD Graphics SGPC                                         | 1         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.86%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.86%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 28.57%  |
| Micron Technology   | 4         | 19.05%  |
| SK Hynix            | 3         | 14.29%  |
| Kingston            | 2         | 9.52%   |
| A-DATA Technology   | 2         | 9.52%   |
| Unknown             | 1         | 4.76%   |
| Strontium           | 1         | 4.76%   |
| Ramaxel Technology  | 1         | 4.76%   |
| Crucial             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s         | 2         | 8.7%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 1         | 4.35%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s              | 1         | 4.35%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 4.35%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 4.35%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 4.35%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 4.35%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 4.35%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s             | 1         | 4.35%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 4.35%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s          | 1         | 4.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 4.35%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s    | 1         | 4.35%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s          | 1         | 4.35%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 4.35%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 4.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s          | 1         | 4.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 1         | 4.35%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 4.35%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s              | 1         | 4.35%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 4.35%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s            | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 42.11%  |
| DDR3   | 8         | 42.11%  |
| SDRAM  | 1         | 5.26%   |
| LPDDR4 | 1         | 5.26%   |
| LPDDR3 | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 78.95%  |
| Row Of Chips | 4         | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 47.37%  |
| 8192  | 6         | 31.58%  |
| 2048  | 3         | 15.79%  |
| 16384 | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 7         | 35%     |
| 2667  | 4         | 20%     |
| 2400  | 3         | 15%     |
| 3200  | 2         | 10%     |
| 4267  | 1         | 5%      |
| 4199  | 1         | 5%      |
| 1867  | 1         | 5%      |
| 1333  | 1         | 5%      |

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
| Chicony Electronics                    | 11        | 16.67%  |
| IMC Networks                           | 9         | 13.64%  |
| Realtek Semiconductor                  | 8         | 12.12%  |
| Microdia                               | 7         | 10.61%  |
| Acer                                   | 7         | 10.61%  |
| Sunplus Innovation Technology          | 5         | 7.58%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.06%   |
| Suyin                                  | 3         | 4.55%   |
| Quanta                                 | 3         | 4.55%   |
| Syntek                                 | 2         | 3.03%   |
| Lite-On Technology                     | 2         | 3.03%   |
| Samsung Electronics                    | 1         | 1.52%   |
| Ricoh                                  | 1         | 1.52%   |
| Generalplus Technology                 | 1         | 1.52%   |
| ALi                                    | 1         | 1.52%   |
| Alcor Micro                            | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 6.06%   |
| Microdia Integrated_Webcam_HD                                            | 3         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 3         | 4.55%   |
| Acer Lenovo EasyCamera                                                   | 3         | 4.55%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 3.03%   |
| Quanta HD User Facing                                                    | 2         | 3.03%   |
| IMC Networks Integrated Camera                                           | 2         | 3.03%   |
| Chicony TOSHIBA Web Camera - HD                                          | 2         | 3.03%   |
| Chicony HP Truevision HD                                                 | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 3.03%   |
| Acer Integrated Camera                                                   | 2         | 3.03%   |
| Syntek USB Camera Device                                                 | 1         | 1.52%   |
| Syntek Integrated Camera                                                 | 1         | 1.52%   |
| Suyin HP Truevision HD                                                   | 1         | 1.52%   |
| Suyin HD Video WebCam                                                    | 1         | 1.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 1.52%   |
| Sunplus Integrated Webcam                                                | 1         | 1.52%   |
| Sunplus HD WebCam                                                        | 1         | 1.52%   |
| Sunplus HD User Facing                                                   | 1         | 1.52%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 1         | 1.52%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870]                      | 1         | 1.52%   |
| Realtek USB Camera                                                       | 1         | 1.52%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.52%   |
| Realtek Integrated Webcam                                                | 1         | 1.52%   |
| Realtek HD WebCam                                                        | 1         | 1.52%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                     | 1         | 1.52%   |
| Microdia Webcam Vitade AF                                                | 1         | 1.52%   |
| Microdia Lenovo EasyCamera                                               | 1         | 1.52%   |
| Microdia Integrated Webcam                                               | 1         | 1.52%   |
| Microdia Integrated HD Webcam                                            | 1         | 1.52%   |
| Lite-On HP HD Webcam                                                     | 1         | 1.52%   |
| Lite-On HP HD Camera                                                     | 1         | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.52%   |
| IMC Networks USB Camera                                                  | 1         | 1.52%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 1.52%   |
| IMC Networks EasyCamera                                                  | 1         | 1.52%   |
| Generalplus GENERAL WEBCAM                                               | 1         | 1.52%   |
| Chicony WebCam                                                           | 1         | 1.52%   |
| Chicony VGA Webcam                                                       | 1         | 1.52%   |
| Chicony LG HD WebCam                                                     | 1         | 1.52%   |
| Chicony Integrated Camera                                                | 1         | 1.52%   |
| Chicony HD WebCam (Acer)                                                 | 1         | 1.52%   |
| Chicony HD WebCam                                                        | 1         | 1.52%   |
| Chicony FJ Camera                                                        | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.52%   |
| ALi Gateway Webcam                                                       | 1         | 1.52%   |
| Alcor Micro Asus Integrated Webcam                                       | 1         | 1.52%   |
| Acer SunplusIT INC. Integrated Camera                                    | 1         | 1.52%   |
| Acer Lenovo EasyCamera integrated webcam                                 | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 50%     |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| LighTuning Technology      | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Focal-systems.Corp         | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 14.29%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 14.29%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 7.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 7.14%   |
| LighTuning Fingerprint Reader                                              | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 7.14%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 51        | 67.11%  |
| 1     | 17        | 22.37%  |
| 2     | 8         | 10.53%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 42.42%  |
| Graphics card         | 5         | 15.15%  |
| Net/wireless          | 4         | 12.12%  |
| Bluetooth             | 3         | 9.09%   |
| Multimedia controller | 2         | 6.06%   |
| Chipcard              | 2         | 6.06%   |
| Net/ethernet          | 1         | 3.03%   |
| Flash memory          | 1         | 3.03%   |
| Dvb card              | 1         | 3.03%   |


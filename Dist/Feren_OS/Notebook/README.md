Feren OS - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Feren OS.

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

Total: 74

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu   | LIFEBOOK U7511              | [b83365533f](https://linux-hardware.org/?probe=b83365533f) | Dec 20, 2025 |
| Lenovo    | ThinkPad T470 W10DG 20JN... | [373bdce267](https://linux-hardware.org/?probe=373bdce267) | Nov 16, 2025 |
| Lenovo    | Unknown                     | [c6a19b39f4](https://linux-hardware.org/?probe=c6a19b39f4) | Jun 24, 2025 |
| Google    | Blorb                       | [e8982a4633](https://linux-hardware.org/?probe=e8982a4633) | Apr 21, 2025 |
| Lenovo    | G50-70 20351                | [541549013e](https://linux-hardware.org/?probe=541549013e) | Apr 04, 2025 |
| Dell      | Latitude 7420               | [7d8d723547](https://linux-hardware.org/?probe=7d8d723547) | Oct 02, 2024 |
| Dell      | Latitude 7420               | [7b8bd6523c](https://linux-hardware.org/?probe=7b8bd6523c) | Aug 11, 2024 |
| Dell      | Latitude 7420               | [494ad08ba2](https://linux-hardware.org/?probe=494ad08ba2) | Aug 11, 2024 |
| Sony      | VGN-NR31MR_S                | [51d4f2f05a](https://linux-hardware.org/?probe=51d4f2f05a) | May 27, 2024 |
| Sony      | VGN-NR11Z_T                 | [d6921ab5ba](https://linux-hardware.org/?probe=d6921ab5ba) | Nov 09, 2023 |
| ASUSTek   | ZenBook UX425UA_UM425UA     | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP        | Stream Notebook PC 13       | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| ASUSTek   | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| ASUSTek   | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Acer      | Aspire E5-773               | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Apple     | MacBookAir6,2               | [0d098f7432](https://linux-hardware.org/?probe=0d098f7432) | Nov 29, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek   | N750JV                      | [04cc8b4e36](https://linux-hardware.org/?probe=04cc8b4e36) | Sep 24, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop M350... | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| MSI       | GS66 Stealth 10SE           | [fbdc7a2279](https://linux-hardware.org/?probe=fbdc7a2279) | Jun 17, 2022 |
| Dell      | Latitude E5570              | [f132300275](https://linux-hardware.org/?probe=f132300275) | Feb 23, 2022 |
| ASUSTek   | S400CA                      | [3d2d24d90e](https://linux-hardware.org/?probe=3d2d24d90e) | Jan 15, 2022 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [a53f185048](https://linux-hardware.org/?probe=a53f185048) | Dec 22, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [21ea8cfa3b](https://linux-hardware.org/?probe=21ea8cfa3b) | Dec 16, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [cd47b9ae21](https://linux-hardware.org/?probe=cd47b9ae21) | Dec 05, 2021 |
| ASUSTek   | P552LJ                      | [6dbe422798](https://linux-hardware.org/?probe=6dbe422798) | Nov 29, 2021 |
| MSI       | GP72 7RDX                   | [502ad3be8e](https://linux-hardware.org/?probe=502ad3be8e) | Nov 29, 2021 |
| MSI       | GE66 Raider 11UG            | [fe677aa4e9](https://linux-hardware.org/?probe=fe677aa4e9) | Nov 20, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [6d92264040](https://linux-hardware.org/?probe=6d92264040) | Nov 14, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [b3836e81d2](https://linux-hardware.org/?probe=b3836e81d2) | Nov 13, 2021 |
| MSI       | Traveller 1591              | [46430a6e00](https://linux-hardware.org/?probe=46430a6e00) | Oct 04, 2021 |
| Dell      | Latitude E5430 vPro         | [8c45da134f](https://linux-hardware.org/?probe=8c45da134f) | Aug 01, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| ASUSTek   | VivoBook_ASUS Laptop E21... | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Unknown   | Unknown                     | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| Lenovo    | XiaoXin Air 12 80UN         | [210f81171b](https://linux-hardware.org/?probe=210f81171b) | May 08, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| Lenovo    | Legion Y7000P 81LD          | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo    | Legion Y7000P 81LD          | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Sony      | VPCEE4J1E                   | [d919affcfd](https://linux-hardware.org/?probe=d919affcfd) | Jan 14, 2021 |
| Lenovo    | XiaoXin Air 12 80UN         | [7339b28f1b](https://linux-hardware.org/?probe=7339b28f1b) | Dec 26, 2020 |
| Lenovo    | XiaoXin Air 12 80UN         | [06c54d29ce](https://linux-hardware.org/?probe=06c54d29ce) | Dec 26, 2020 |
| Acer      | NG-VX5-591G-52AT            | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| HP        | ProBook 6560b               | [1e12011c45](https://linux-hardware.org/?probe=1e12011c45) | Nov 05, 2020 |
| ASUSTek   | X541NA                      | [fa42a090b5](https://linux-hardware.org/?probe=fa42a090b5) | Nov 03, 2020 |
| Sony      | SVF15318SNB                 | [600b06bc21](https://linux-hardware.org/?probe=600b06bc21) | Oct 15, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| Lenovo    | G550 2958                   | [6c33f8ea14](https://linux-hardware.org/?probe=6c33f8ea14) | Sep 13, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| HUAWEI    | BOHK-WAX9X                  | [58c99091e7](https://linux-hardware.org/?probe=58c99091e7) | Aug 29, 2020 |
| Toshiba   | Satellite T135D             | [e59691cfe7](https://linux-hardware.org/?probe=e59691cfe7) | Aug 28, 2020 |
| ASUSTek   | X550CA                      | [7f2bf35eb8](https://linux-hardware.org/?probe=7f2bf35eb8) | Jun 30, 2020 |
| ASUSTek   | X550CA                      | [fe533b45dd](https://linux-hardware.org/?probe=fe533b45dd) | Jun 17, 2020 |
| ASUSTek   | X550CA                      | [e07d0dce49](https://linux-hardware.org/?probe=e07d0dce49) | Jun 17, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [b7b58ba2d6](https://linux-hardware.org/?probe=b7b58ba2d6) | Jun 10, 2020 |
| HP        | EliteBook Folio 1040 G1     | [c7abaff76b](https://linux-hardware.org/?probe=c7abaff76b) | Jun 02, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [f3c754042c](https://linux-hardware.org/?probe=f3c754042c) | May 16, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [cfa1314238](https://linux-hardware.org/?probe=cfa1314238) | May 04, 2020 |
| Apple     | MacBookPro8,1               | [b2b19968b0](https://linux-hardware.org/?probe=b2b19968b0) | May 03, 2020 |
| Lenovo    | ThinkPad X240 20AMS72901    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Fujitsu   | LIFEBOOK E554               | [bb918daf7b](https://linux-hardware.org/?probe=bb918daf7b) | Mar 29, 2020 |
| Acer      | Aspire 5733Z                | [ebca80c932](https://linux-hardware.org/?probe=ebca80c932) | Jan 04, 2020 |
| Acer      | Aspire 5733Z                | [05ef4a2f12](https://linux-hardware.org/?probe=05ef4a2f12) | Jan 02, 2020 |
| Acer      | Aspire 5733Z                | [b1af19a6ad](https://linux-hardware.org/?probe=b1af19a6ad) | Jan 02, 2020 |
| Dell      | Inspiron 3421               | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Panasonic | CF-J10YYBHR                 | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Panasonic | CF-J10YYBHR                 | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| Exo       | CloudbookE15                | [9a16d4a087](https://linux-hardware.org/?probe=9a16d4a087) | Aug 19, 2019 |
| Lenovo    | G50-45 80E3                 | [440ce358c0](https://linux-hardware.org/?probe=440ce358c0) | May 04, 2019 |
| Lenovo    | G50-45 80E3                 | [fa158b6a96](https://linux-hardware.org/?probe=fa158b6a96) | Apr 16, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Feren OS 20.04   | 30        | 58.82%  |
| Feren OS 18.04   | 17        | 33.33%  |
| Feren OS 2025.03 | 4         | 7.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Feren OS | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 4         | 6.45%   |
| 5.8.0-55-generic        | 3         | 4.84%   |
| 5.3.0-51-generic        | 3         | 4.84%   |
| 5.8.0-50-generic        | 2         | 3.23%   |
| 5.4.0-52-generic        | 2         | 3.23%   |
| 5.4.0-42-generic        | 2         | 3.23%   |
| 5.3.0-53-generic        | 2         | 3.23%   |
| 5.15.0-69-generic       | 2         | 3.23%   |
| 5.15.0-48-generic       | 2         | 3.23%   |
| 5.0.0-37-generic        | 2         | 3.23%   |
| 6.8.0-90-generic        | 1         | 1.61%   |
| 6.8.0-87-generic        | 1         | 1.61%   |
| 6.8.0-60-generic        | 1         | 1.61%   |
| 6.8.0-57-generic        | 1         | 1.61%   |
| 5.8.0-53-generic        | 1         | 1.61%   |
| 5.8.0-48-generic        | 1         | 1.61%   |
| 5.8.0-36-generic        | 1         | 1.61%   |
| 5.4.0-58-generic        | 1         | 1.61%   |
| 5.4.0-54-generic        | 1         | 1.61%   |
| 5.4.0-51-generic        | 1         | 1.61%   |
| 5.4.0-48-generic        | 1         | 1.61%   |
| 5.4.0-47-generic        | 1         | 1.61%   |
| 5.4.0-45-generic        | 1         | 1.61%   |
| 5.3.0-59-generic        | 1         | 1.61%   |
| 5.3.0-42-generic        | 1         | 1.61%   |
| 5.17.5-76051705-generic | 1         | 1.61%   |
| 5.15.6-051506-generic   | 1         | 1.61%   |
| 5.15.0-88-generic       | 1         | 1.61%   |
| 5.15.0-73-generic       | 1         | 1.61%   |
| 5.15.0-67-generic       | 1         | 1.61%   |
| 5.15.0-60-generic       | 1         | 1.61%   |
| 5.15.0-56-generic       | 1         | 1.61%   |
| 5.15.0-53-generic       | 1         | 1.61%   |
| 5.15.0-41-generic       | 1         | 1.61%   |
| 5.15.0-122-generic      | 1         | 1.61%   |
| 5.15.0-117-generic      | 1         | 1.61%   |
| 5.15.0-107-generic      | 1         | 1.61%   |
| 5.13.0-40-generic       | 1         | 1.61%   |
| 5.13.0-30-generic       | 1         | 1.61%   |
| 5.13.0-22-generic       | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 11        | 20.75%  |
| 5.4.0   | 9         | 16.98%  |
| 5.8.0   | 7         | 13.21%  |
| 5.3.0   | 6         | 11.32%  |
| 5.11.0  | 6         | 11.32%  |
| 6.8.0   | 4         | 7.55%   |
| 5.13.0  | 3         | 5.66%   |
| 5.0.0   | 3         | 5.66%   |
| 4.15.0  | 2         | 3.77%   |
| 5.17.5  | 1         | 1.89%   |
| 5.15.6  | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 22.64%  |
| 5.4     | 9         | 16.98%  |
| 5.8     | 7         | 13.21%  |
| 5.3     | 6         | 11.32%  |
| 5.11    | 6         | 11.32%  |
| 6.8     | 4         | 7.55%   |
| 5.13    | 3         | 5.66%   |
| 5.0     | 3         | 5.66%   |
| 4.15    | 2         | 3.77%   |
| 5.17    | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 26        | 50%     |
| KDE        | 20        | 38.46%  |
| Unknown    | 4         | 7.69%   |
| X-Cinnamon | 1         | 1.92%   |
| GNOME      | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 50        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 70%     |
| LightDM | 14        | 28%     |
| TDM     | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 25.49%  |
| en_GB   | 9         | 17.65%  |
| de_DE   | 5         | 9.8%    |
| de_CH   | 5         | 9.8%    |
| en_IN   | 3         | 5.88%   |
| Unknown | 3         | 5.88%   |
| ru_RU   | 1         | 1.96%   |
| pl_PL   | 1         | 1.96%   |
| nl_BE   | 1         | 1.96%   |
| fi_FI   | 1         | 1.96%   |
| es_VE   | 1         | 1.96%   |
| es_UY   | 1         | 1.96%   |
| es_ES   | 1         | 1.96%   |
| es_CL   | 1         | 1.96%   |
| en_ZA   | 1         | 1.96%   |
| en_CA   | 1         | 1.96%   |
| en_AU   | 1         | 1.96%   |
| en_AG   | 1         | 1.96%   |
| de_AT   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 60%     |
| BIOS | 20        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 90.2%   |
| Btrfs   | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| Overlay | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 76%     |
| GPT     | 11        | 22%     |
| MBR     | 1         | 2%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 98%     |
| Yes       | 1         | 2%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 80%     |
| Yes       | 10        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 10        | 20%     |
| Lenovo           | 9         | 18%     |
| Hewlett-Packard  | 5         | 10%     |
| Dell             | 5         | 10%     |
| Sony             | 4         | 8%      |
| MSI              | 4         | 8%      |
| Acer             | 3         | 6%      |
| Fujitsu          | 2         | 4%      |
| Apple            | 2         | 4%      |
| Toshiba          | 1         | 2%      |
| Panasonic        | 1         | 2%      |
| HUAWEI           | 1         | 2%      |
| Google           | 1         | 2%      |
| Exo              | 1         | 2%      |
| Unknown          | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7420                       | 2         | 4%      |
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 2         | 4%      |
| Unknown                                  | 2         | 4%      |
| Toshiba Satellite T135D                  | 1         | 2%      |
| Sony VPCEE4J1E                           | 1         | 2%      |
| Sony VGN-NR31MR_S                        | 1         | 2%      |
| Sony VGN-NR11Z_T                         | 1         | 2%      |
| Sony SVF15318SNB                         | 1         | 2%      |
| Panasonic CF-J10YYBHR                    | 1         | 2%      |
| MSI Traveller 1591                       | 1         | 2%      |
| MSI GS66 Stealth 10SE                    | 1         | 2%      |
| MSI GP72 7RDX                            | 1         | 2%      |
| MSI GE66 Raider 11UG                     | 1         | 2%      |
| Lenovo XiaoXin Air 12 80UN               | 1         | 2%      |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 2%      |
| Lenovo ThinkPad X230 2325AT6             | 1         | 2%      |
| Lenovo ThinkPad T470 W10DG 20JNS0A800    | 1         | 2%      |
| Lenovo Legion Y7000P 81LD                | 1         | 2%      |
| Lenovo G550 2958                         | 1         | 2%      |
| Lenovo G50-70 20351                      | 1         | 2%      |
| Lenovo G50-45 80E3                       | 1         | 2%      |
| HUAWEI BOHK-WAX9X                        | 1         | 2%      |
| HP Stream Notebook PC 13                 | 1         | 2%      |
| HP ProBook 6560b                         | 1         | 2%      |
| HP Pavilion Laptop 14-bf0xx              | 1         | 2%      |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 2%      |
| HP EliteBook Folio 1040 G1               | 1         | 2%      |
| Google Blorb                             | 1         | 2%      |
| Fujitsu LIFEBOOK U7511                   | 1         | 2%      |
| Fujitsu LIFEBOOK E554                    | 1         | 2%      |
| Exo CloudbookE15                         | 1         | 2%      |
| Dell Latitude E5570                      | 1         | 2%      |
| Dell Latitude E5430 vPro                 | 1         | 2%      |
| Dell Inspiron 3421                       | 1         | 2%      |
| ASUS ZenBook UX425UA_UM425UA             | 1         | 2%      |
| ASUS X550CA                              | 1         | 2%      |
| ASUS X541NA                              | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 1         | 2%      |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA  | 1         | 2%      |
| ASUS S400CA                              | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 4         | 8%      |
| Lenovo ThinkPad       | 3         | 6%      |
| HP Pavilion           | 2         | 4%      |
| Fujitsu LIFEBOOK      | 2         | 4%      |
| ASUS VivoBook         | 2         | 4%      |
| ASUS ROG              | 2         | 4%      |
| Acer Aspire           | 2         | 4%      |
| Unknown               | 2         | 4%      |
| Toshiba Satellite     | 1         | 2%      |
| Sony VPCEE4J1E        | 1         | 2%      |
| Sony VGN-NR31MR       | 1         | 2%      |
| Sony VGN-NR11Z        | 1         | 2%      |
| Sony SVF15318SNB      | 1         | 2%      |
| Panasonic CF-J10YYBHR | 1         | 2%      |
| MSI Traveller         | 1         | 2%      |
| MSI GS66              | 1         | 2%      |
| MSI GP72              | 1         | 2%      |
| MSI GE66              | 1         | 2%      |
| Lenovo XiaoXin        | 1         | 2%      |
| Lenovo Legion         | 1         | 2%      |
| Lenovo G550           | 1         | 2%      |
| Lenovo G50-70         | 1         | 2%      |
| Lenovo G50-45         | 1         | 2%      |
| HUAWEI BOHK-WAX9X     | 1         | 2%      |
| HP Stream             | 1         | 2%      |
| HP ProBook            | 1         | 2%      |
| HP EliteBook          | 1         | 2%      |
| Google Blorb          | 1         | 2%      |
| Exo CloudbookE15      | 1         | 2%      |
| Dell Inspiron         | 1         | 2%      |
| ASUS ZenBook          | 1         | 2%      |
| ASUS X550CA           | 1         | 2%      |
| ASUS X541NA           | 1         | 2%      |
| ASUS S400CA           | 1         | 2%      |
| ASUS P552LJ           | 1         | 2%      |
| ASUS N750JV           | 1         | 2%      |
| Apple MacBookPro8     | 1         | 2%      |
| Apple MacBookAir6     | 1         | 2%      |
| Acer NG-VX5-591G-52AT | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 12%     |
| 2016 | 6         | 12%     |
| 2013 | 6         | 12%     |
| 2017 | 5         | 10%     |
| 2012 | 5         | 10%     |
| 2011 | 4         | 8%      |
| 2020 | 3         | 6%      |
| 2019 | 3         | 6%      |
| 2014 | 3         | 6%      |
| 2008 | 3         | 6%      |
| 2018 | 2         | 4%      |
| 2009 | 2         | 4%      |
| 2024 | 1         | 2%      |
| 2007 | 1         | 2%      |

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
| Disabled | 45        | 88.24%  |
| Enabled  | 6         | 11.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 26.92%  |
| 3.01-4.0    | 11        | 21.15%  |
| 16.01-24.0  | 10        | 19.23%  |
| 8.01-16.0   | 10        | 19.23%  |
| 32.01-64.0  | 2         | 3.85%   |
| 64.01-256.0 | 2         | 3.85%   |
| 1.01-2.0    | 2         | 3.85%   |
| 2.01-3.0    | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 40.35%  |
| 2.01-3.0 | 18        | 31.58%  |
| 3.01-4.0 | 9         | 15.79%  |
| 4.01-8.0 | 6         | 10.53%  |
| 0.51-1.0 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 72.55%  |
| 2      | 10        | 19.61%  |
| 3      | 4         | 7.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 66.67%  |
| Yes       | 17        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 80.39%  |
| No        | 10        | 19.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 96%     |
| No        | 2         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 72.55%  |
| No        | 14        | 27.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 18%     |
| Germany      | 6         | 12%     |
| Switzerland  | 5         | 10%     |
| UK           | 4         | 8%      |
| Poland       | 3         | 6%      |
| India        | 3         | 6%      |
| Turkey       | 2         | 4%      |
| Australia    | 2         | 4%      |
| Venezuela    | 1         | 2%      |
| Uruguay      | 1         | 2%      |
| UAE          | 1         | 2%      |
| Spain        | 1         | 2%      |
| South Africa | 1         | 2%      |
| Russia       | 1         | 2%      |
| Japan        | 1         | 2%      |
| Guam         | 1         | 2%      |
| Greece       | 1         | 2%      |
| Finland      | 1         | 2%      |
| Czechia      | 1         | 2%      |
| Chile        | 1         | 2%      |
| Canada       | 1         | 2%      |
| Bulgaria     | 1         | 2%      |
| Belgium      | 1         | 2%      |
| Argentina    | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Oberwil-Lieli  | 3         | 5.56%   |
| Zurich         | 2         | 3.7%    |
| Mesa           | 2         | 3.7%    |
| Leicester      | 2         | 3.7%    |
| Istanbul       | 2         | 3.7%    |
| Escondido      | 2         | 3.7%    |
| Ypsilanti      | 1         | 1.85%   |
| Yigo Village   | 1         | 1.85%   |
| Wroclaw        | 1         | 1.85%   |
| Winterthur     | 1         | 1.85%   |
| Varna          | 1         | 1.85%   |
| Surat          | 1         | 1.85%   |
| Stuttgart      | 1         | 1.85%   |
| Santiago       | 1         | 1.85%   |
| Saitama        | 1         | 1.85%   |
| Prague         | 1         | 1.85%   |
| Plymouth       | 1         | 1.85%   |
| Phoenix        | 1         | 1.85%   |
| Moscow         | 1         | 1.85%   |
| Montevideo     | 1         | 1.85%   |
| Moncton        | 1         | 1.85%   |
| Mieres         | 1         | 1.85%   |
| Melbourne      | 1         | 1.85%   |
| Maracay        | 1         | 1.85%   |
| Lancefield     | 1         | 1.85%   |
| Lafayette      | 1         | 1.85%   |
| Krakow         | 1         | 1.85%   |
| Kloten         | 1         | 1.85%   |
| Kassel         | 1         | 1.85%   |
| Karlsruhe      | 1         | 1.85%   |
| Johannesburg   | 1         | 1.85%   |
| Hyderabad      | 1         | 1.85%   |
| Hickory        | 1         | 1.85%   |
| Hämeenlinna   | 1         | 1.85%   |
| Gdynia         | 1         | 1.85%   |
| Gdansk         | 1         | 1.85%   |
| Essen          | 1         | 1.85%   |
| Ernakulam      | 1         | 1.85%   |
| Delmenhorst    | 1         | 1.85%   |
| Corpus Christi | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 11        | 14     | 16.18%  |
| Unknown                   | 9         | 13     | 13.24%  |
| SanDisk                   | 5         | 6      | 7.35%   |
| Intel                     | 5         | 6      | 7.35%   |
| HGST                      | 4         | 4      | 5.88%   |
| Toshiba                   | 3         | 5      | 4.41%   |
| Seagate                   | 3         | 3      | 4.41%   |
| Hitachi                   | 3         | 3      | 4.41%   |
| WDC                       | 2         | 2      | 2.94%   |
| SK hynix                  | 2         | 3      | 2.94%   |
| Phison                    | 2         | 2      | 2.94%   |
| OCZ                       | 2         | 2      | 2.94%   |
| KLEVV                     | 2         | 2      | 2.94%   |
| Kingston                  | 2         | 2      | 2.94%   |
| A-DATA Technology         | 2         | 2      | 2.94%   |
| StoreJet                  | 1         | 1      | 1.47%   |
| Realtek Semiconductor     | 1         | 1      | 1.47%   |
| PNY                       | 1         | 1      | 1.47%   |
| Micron/Crucial Technology | 1         | 1      | 1.47%   |
| LITEON                    | 1         | 1      | 1.47%   |
| KIOXIA                    | 1         | 1      | 1.47%   |
| Fujitsu                   | 1         | 1      | 1.47%   |
| Dogfish                   | 1         | 1      | 1.47%   |
| Crucial                   | 1         | 4      | 1.47%   |
| China                     | 1         | 1      | 1.47%   |
| Apple                     | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB                   | 2         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.86%   |
| Phison NVMe SSD Drive 1TB                         | 2         | 2.86%   |
| KLEVV CRAS C710 M.2 NVMe SSD 512GB                | 2         | 2.86%   |
| Intel NVMe SSD Drive 512GB                        | 2         | 2.86%   |
| HGST HTS721010A9E630 1TB                          | 2         | 2.86%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 1         | 1.43%   |
| WDC WD2500BPVT-00JJ5T0 250GB                      | 1         | 1.43%   |
| Unknown SDW32G  32GB                              | 1         | 1.43%   |
| Unknown SD/MMC/MS PRO 2GB                         | 1         | 1.43%   |
| Unknown SB128  128GB                              | 1         | 1.43%   |
| Unknown SA04G  4GB                                | 1         | 1.43%   |
| Unknown MMC Card  32GB                            | 1         | 1.43%   |
| Unknown MMC Card  256GB                           | 1         | 1.43%   |
| Unknown MMC Card  128GB                           | 1         | 1.43%   |
| Unknown External 2TB                              | 1         | 1.43%   |
| Unknown DA4128  128GB                             | 1         | 1.43%   |
| Unknown APPSD  134GB                              | 1         | 1.43%   |
| Toshiba THNSNC128GNSJ 128GB SSD                   | 1         | 1.43%   |
| Toshiba Q300. 240GB SSD                           | 1         | 1.43%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 1.43%   |
| StoreJet Transcend 1TB                            | 1         | 1.43%   |
| SK hynix HFS128G32TND-N210A 128GB SSD             | 1         | 1.43%   |
| SK hynix HFM001TD3JX013N 1024GB                   | 1         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.43%   |
| SanDisk SSD U100 24GB                             | 1         | 1.43%   |
| SanDisk SD9SB8W256G1002 256GB SSD                 | 1         | 1.43%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD               | 1         | 1.43%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD               | 1         | 1.43%   |
| SanDisk NVMe SSD Drive 256GB                      | 1         | 1.43%   |
| Samsung SSD 860 EVO 250GB                         | 1         | 1.43%   |
| Samsung SSD 840 Series 120GB                      | 1         | 1.43%   |
| Samsung Portable SSD T5 500GB                     | 1         | 1.43%   |
| Samsung NVMe SSD Drive 256GB                      | 1         | 1.43%   |
| Samsung NVMe SSD Drive 1TB                        | 1         | 1.43%   |
| Samsung NVMe SSD Drive 1024GB                     | 1         | 1.43%   |
| Samsung MZVLW256HEHP-000H1 256GB                  | 1         | 1.43%   |
| Samsung MZVLW128HEGR-00000 128GB                  | 1         | 1.43%   |
| Samsung MZNTY128HDHP-000L2 128GB SSD              | 1         | 1.43%   |
| Realtek NVMe SSD Drive 512GB                      | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 26.67%  |
| Seagate | 3         | 3      | 20%     |
| Hitachi | 3         | 3      | 20%     |
| Unknown | 2         | 2      | 13.33%  |
| WDC     | 1         | 1      | 6.67%   |
| Toshiba | 1         | 2      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 5      | 15.38%  |
| Samsung Electronics | 4         | 5      | 15.38%  |
| Toshiba             | 2         | 3      | 7.69%   |
| OCZ                 | 2         | 2      | 7.69%   |
| Kingston            | 2         | 2      | 7.69%   |
| A-DATA Technology   | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| StoreJet            | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 2      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Dogfish             | 1         | 1      | 3.85%   |
| Crucial             | 1         | 4      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 33     | 35.48%  |
| NVMe | 18        | 23     | 29.03%  |
| HDD  | 15        | 16     | 24.19%  |
| MMC  | 7         | 11     | 11.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 44     | 51.67%  |
| NVMe | 18        | 23     | 30%     |
| MMC  | 7         | 11     | 11.67%  |
| SAS  | 4         | 5      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 39     | 75%     |
| 0.51-1.0   | 8         | 9      | 22.22%  |
| 1.01-2.0   | 1         | 1      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 33.96%  |
| 251-500    | 14        | 26.42%  |
| 501-1000   | 6         | 11.32%  |
| 51-100     | 6         | 11.32%  |
| 1001-2000  | 5         | 9.43%   |
| 21-50      | 3         | 5.66%   |
| 1-20       | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 21        | 37.5%   |
| 1-20      | 12        | 21.43%  |
| 51-100    | 9         | 16.07%  |
| 101-250   | 7         | 12.5%   |
| 251-500   | 3         | 5.36%   |
| 501-1000  | 3         | 5.36%   |
| 1001-2000 | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 41        | 66     | 75.93%  |
| Works    | 10        | 14     | 18.52%  |
| Malfunc  | 3         | 3      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 34        | 60.71%  |
| Samsung Electronics       | 8         | 14.29%  |
| AMD                       | 4         | 7.14%   |
| Realtek Semiconductor     | 3         | 5.36%   |
| Phison Electronics        | 2         | 3.57%   |
| SK hynix                  | 1         | 1.79%   |
| SanDisk                   | 1         | 1.79%   |
| Nvidia                    | 1         | 1.79%   |
| Micron/Crucial Technology | 1         | 1.79%   |
| KIOXIA                    | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 6.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 6.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.76%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 4.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 4.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.17%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 2         | 3.17%   |
| Phison E12 NVMe Controller                                                     | 2         | 3.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 3.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 3.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.59%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.59%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.59%   |
| Nvidia nForce SATA Controller                                                  | 1         | 1.59%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 1.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.59%   |
| Intel SSD 600P Series                                                          | 1         | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 57.38%  |
| NVMe | 18        | 29.51%  |
| RAID | 5         | 8.2%    |
| IDE  | 3         | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 86%     |
| AMD    | 7         | 14%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 6%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 4%      |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 4%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 4%      |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 4%      |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 2%      |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 2%      |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2%      |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 2%      |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 2%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2%      |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 2%      |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2%      |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 2%      |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 2%      |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 2%      |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2%      |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 2%      |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2%      |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2%      |
| AMD Turion Neo X2 Dual Core Processor L625    | 1         | 2%      |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2%      |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 30%     |
| Other                   | 6         | 12%     |
| Intel Core i7           | 6         | 12%     |
| Intel Celeron           | 5         | 10%     |
| Intel Pentium           | 3         | 6%      |
| Intel Core i3           | 3         | 6%      |
| Intel Pentium Dual      | 1         | 2%      |
| Intel Core m3           | 1         | 2%      |
| Intel Core 2 Duo        | 1         | 2%      |
| Intel Celeron Dual-Core | 1         | 2%      |
| Intel Atom              | 1         | 2%      |
| AMD Turion Neo X2       | 1         | 2%      |
| AMD Ryzen 9             | 1         | 2%      |
| AMD Ryzen 7             | 1         | 2%      |
| AMD Ryzen 5             | 1         | 2%      |
| AMD Athlon X2           | 1         | 2%      |
| AMD Athlon II           | 1         | 2%      |
| AMD A6                  | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 60%     |
| 4      | 14        | 28%     |
| 8      | 6         | 12%     |

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
| 2      | 34        | 68%     |
| 1      | 16        | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 96%     |
| Unknown        | 2         | 4%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 12%     |
| 0x40651    | 5         | 10%     |
| 0x206a7    | 4         | 8%      |
| 0x806d1    | 3         | 6%      |
| 0x406e3    | 3         | 6%      |
| 0x306a9    | 3         | 6%      |
| 0x906e9    | 2         | 4%      |
| 0x806c1    | 2         | 4%      |
| 0x706a8    | 2         | 4%      |
| 0x6fd      | 2         | 4%      |
| 0x306c3    | 2         | 4%      |
| 0xa0652    | 1         | 2%      |
| 0x906ea    | 1         | 2%      |
| 0x806ea    | 1         | 2%      |
| 0x806e9    | 1         | 2%      |
| 0x506c9    | 1         | 2%      |
| 0x406c4    | 1         | 2%      |
| 0x406c3    | 1         | 2%      |
| 0x306d4    | 1         | 2%      |
| 0x20655    | 1         | 2%      |
| 0x1067a    | 1         | 2%      |
| 0x0a50000c | 1         | 2%      |
| 0x08608103 | 1         | 2%      |
| 0x08108109 | 1         | 2%      |
| 0x07030105 | 1         | 2%      |
| 0x02000032 | 1         | 2%      |
| 0x010000c8 | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Haswell         | 7         | 14%     |
| Skylake         | 5         | 10%     |
| KabyLake        | 5         | 10%     |
| SandyBridge     | 4         | 8%      |
| IvyBridge       | 4         | 8%      |
| TigerLake       | 3         | 6%      |
| Icelake         | 3         | 6%      |
| Goldmont plus   | 3         | 6%      |
| Silvermont      | 2         | 4%      |
| Core            | 2         | 4%      |
| Zen+            | 1         | 2%      |
| Zen 3           | 1         | 2%      |
| Westmere        | 1         | 2%      |
| Puma            | 1         | 2%      |
| Penryn          | 1         | 2%      |
| K8 Hammer       | 1         | 2%      |
| K8 & K10 hybrid | 1         | 2%      |
| K10             | 1         | 2%      |
| Goldmont        | 1         | 2%      |
| CometLake       | 1         | 2%      |
| Broadwell       | 1         | 2%      |
| Unknown         | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 66.13%  |
| Nvidia | 14        | 22.58%  |
| AMD    | 7         | 11.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 7.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 4.69%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 4.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 4.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.13%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 2         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.13%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia GM204M [GeForce GTX 980M]                                                         | 1         | 1.56%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.56%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.56%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.56%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 1.56%   |
| Intel Skylake-Y GT2 [HD Graphics 515]                                                    | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.56%   |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                  | 1         | 1.56%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 1         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.56%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 1         | 1.56%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.56%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.56%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.56%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.56%   |
| AMD Lucienne                                                                             | 1         | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 58%     |
| Intel + Nvidia | 10        | 20%     |
| 1 x AMD        | 5         | 10%     |
| 1 x Nvidia     | 3         | 6%      |
| Other          | 1         | 2%      |
| Intel + AMD    | 1         | 2%      |
| AMD + Nvidia   | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 44        | 86.27%  |
| Proprietary | 7         | 13.73%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 64.71%  |
| 1.01-2.0   | 5         | 9.8%    |
| 0.01-0.5   | 5         | 9.8%    |
| 3.01-4.0   | 4         | 7.84%   |
| 0.51-1.0   | 2         | 3.92%   |
| 7.01-8.0   | 1         | 1.96%   |
| 5.01-6.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 22%     |
| LG Display              | 10        | 20%     |
| Chimei Innolux          | 7         | 14%     |
| BOE                     | 7         | 14%     |
| Sharp                   | 3         | 6%      |
| Samsung Electronics     | 3         | 6%      |
| Apple                   | 2         | 4%      |
| Toshiba                 | 1         | 2%      |
| Sony                    | 1         | 2%      |
| Philips                 | 1         | 2%      |
| PANDA                   | 1         | 2%      |
| Panasonic               | 1         | 2%      |
| Chi Mei Optoelectronics | 1         | 2%      |
| Acer                    | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 3.92%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch           | 2         | 3.92%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 1.96%   |
| Sony AVAMP SNYF400 1920x1080                                             | 1         | 1.96%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Sharp LQ156M1JW24 SHP1534 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch        | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 1.96%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 1.96%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 1.96%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1543 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06A6 1366x768 309x174mm 14.0-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0582 1366x768 344x193mm 15.5-inch                     | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 42.86%  |
| 1366x768 (WXGA)    | 20        | 40.82%  |
| 2560x1600          | 2         | 4.08%   |
| 1680x1050 (WSXGA+) | 2         | 4.08%   |
| 2560x1440 (QHD)    | 1         | 2.04%   |
| 1600x900 (HD+)     | 1         | 2.04%   |
| 1440x900 (WXGA+)   | 1         | 2.04%   |
| 1280x800 (WXGA)    | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 50%     |
| 13     | 7         | 14%     |
| 14     | 5         | 10%     |
| 17     | 3         | 6%      |
| 22     | 2         | 4%      |
| 16     | 2         | 4%      |
| 12     | 2         | 4%      |
| 65     | 1         | 2%      |
| 31     | 1         | 2%      |
| 23     | 1         | 2%      |
| 11     | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 68%     |
| 201-300     | 7         | 14%     |
| 351-400     | 4         | 8%      |
| 401-500     | 2         | 4%      |
| 601-700     | 1         | 2%      |
| 501-600     | 1         | 2%      |
| 1001-1500   | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 87.23%  |
| 16/10 | 6         | 12.77%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 50%     |
| 81-90          | 10        | 20%     |
| 201-250        | 3         | 6%      |
| 121-130        | 3         | 6%      |
| 71-80          | 2         | 4%      |
| 61-70          | 2         | 4%      |
| 111-120        | 2         | 4%      |
| More than 1000 | 1         | 2%      |
| 51-60          | 1         | 2%      |
| 351-500        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 23        | 46.94%  |
| 101-120 | 16        | 32.65%  |
| 51-100  | 6         | 12.24%  |
| 161-240 | 3         | 6.12%   |
| 1-50    | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 92.31%  |
| 2     | 3         | 5.77%   |
| 3     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 31.65%  |
| Intel                    | 22        | 27.85%  |
| Qualcomm Atheros         | 10        | 12.66%  |
| Broadcom                 | 6         | 7.59%   |
| TP-Link                  | 3         | 3.8%    |
| MediaTek                 | 3         | 3.8%    |
| Sierra Wireless          | 2         | 2.53%   |
| Marvell Technology Group | 2         | 2.53%   |
| Research In Motion       | 1         | 1.27%   |
| Ralink Technology        | 1         | 1.27%   |
| Ralink                   | 1         | 1.27%   |
| Qualcomm                 | 1         | 1.27%   |
| Motorola PCS             | 1         | 1.27%   |
| Broadcom Limited         | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 16        | 16.33%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 4.08%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                          | 3         | 3.06%   |
| Intel Wireless 7260                                                                           | 3         | 3.06%   |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 3.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 2.04%   |
| Realtek PCIe GbE Family Controller                                                            | 2         | 2.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 2         | 2.04%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                          | 2         | 2.04%   |
| Intel Wireless 8260                                                                           | 2         | 2.04%   |
| Intel Ethernet Connection I219-LM                                                             | 2         | 2.04%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 2.04%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 1.02%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 1.02%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.02%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.02%   |
| Research In Motion BlackBerry                                                                 | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.02%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 1.02%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.02%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 1.02%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.02%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.02%   |
| Qualcomm Nokia X30 5G                                                                         | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.02%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 40.74%  |
| Realtek Semiconductor | 9         | 16.67%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| Broadcom              | 4         | 7.41%   |
| TP-Link               | 3         | 5.56%   |
| MediaTek              | 3         | 5.56%   |
| Sierra Wireless       | 2         | 3.7%    |
| Ralink Technology     | 1         | 1.85%   |
| Ralink                | 1         | 1.85%   |
| Broadcom Limited      | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 7.27%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                          | 3         | 5.45%   |
| Intel Wireless 7260                                                                           | 3         | 5.45%   |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 5.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 3.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 3.64%   |
| Intel Wireless 8260                                                                           | 2         | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 3.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 1.82%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 1.82%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.82%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.82%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.82%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.82%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.82%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.82%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 1         | 1.82%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.82%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 1.82%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 1         | 1.82%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 51.16%  |
| Intel                    | 10        | 23.26%  |
| Qualcomm Atheros         | 3         | 6.98%   |
| Broadcom                 | 3         | 6.98%   |
| Marvell Technology Group | 2         | 4.65%   |
| Research In Motion       | 1         | 2.33%   |
| Qualcomm                 | 1         | 2.33%   |
| Motorola PCS             | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 37.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 4.65%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 4.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 4.65%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 4.65%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 4.65%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.65%   |
| Research In Motion BlackBerry                                          | 1         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.33%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 2.33%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 2.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 2.33%   |
| Motorola PCS motorola one 5G ace                                       | 1         | 2.33%   |
| Intel WiMAX Connection 2400m                                           | 1         | 2.33%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 2.33%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 2.33%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 2.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 2.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 53.93%  |
| Ethernet | 41        | 46.07%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 75%     |
| Ethernet | 13        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 36        | 72%     |
| 1     | 12        | 24%     |
| 0     | 2         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 76.47%  |
| Yes  | 12        | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 42.11%  |
| Realtek Semiconductor           | 4         | 10.53%  |
| IMC Networks                    | 4         | 10.53%  |
| Cambridge Silicon Radio         | 3         | 7.89%   |
| Realtek                         | 2         | 5.26%   |
| Broadcom                        | 2         | 5.26%   |
| Apple                           | 2         | 5.26%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| Lite-On Technology              | 1         | 2.63%   |
| Hewlett-Packard                 | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| ASUSTek Computer                | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 18.42%  |
| Intel AX201 Bluetooth                               | 4         | 10.53%  |
| IMC Networks Wireless_Device                        | 3         | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.89%   |
| Realtek Bluetooth Radio                             | 2         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 5.26%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.63%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.63%   |
| Realtek Bluetooth Radio                             | 1         | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.63%   |
| Lite-On Bluetooth Device                            | 1         | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.63%   |
| Intel AX210 Bluetooth                               | 1         | 2.63%   |
| Intel AX200 Bluetooth                               | 1         | 2.63%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.63%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.63%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.63%   |
| Apple Bluetooth Host Controller                     | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 42        | 71.19%  |
| Nvidia            | 9         | 15.25%  |
| AMD               | 6         | 10.17%  |
| Texas Instruments | 1         | 1.69%   |
| Logitech          | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 6.85%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 6.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.11%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 4.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.11%   |
| AMD Ryzen HD Audio Controller                                                                     | 3         | 4.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.74%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.74%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 2.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.74%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 2         | 2.74%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.37%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Logitech Headset H390                                                                             | 1         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.37%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.37%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.37%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 6         | 26.09%  |
| Samsung Electronics | 5         | 21.74%  |
| Crucial             | 3         | 13.04%  |
| Unknown             | 2         | 8.7%    |
| SK hynix            | 2         | 8.7%    |
| Kingston            | 2         | 8.7%    |
| ff                  | 1         | 4.35%   |
| A-DATA Technology   | 1         | 4.35%   |
| 4ea5                | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 7.69%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 7.69%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 7.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 7.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                      | 1         | 3.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 3.85%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s      | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Micron RAM MT53E512M32D2NP-046 WT:E 2GB LPDDR4 2933MT/s    | 1         | 3.85%   |
| Micron RAM Module 2048MB Row Of Chips DDR3 1600MT/s        | 1         | 3.85%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Kingston RAM MSI24D4S7D8MH-16 16GB SODIMM DDR4 2400MT/s    | 1         | 3.85%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| ff RAM MT53E512M32D2NP-046 WT:E 2GB LPDDR4 2400MT/s        | 1         | 3.85%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 3.85%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| 4ea5 RAM MT53E512M32D2NP-046 WT:E 2GB LPDDR4 2400MT/s      | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 38.89%  |
| DDR4   | 6         | 33.33%  |
| LPDDR4 | 3         | 16.67%  |
| LPDDR3 | 1         | 5.56%   |
| DDR2   | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 77.78%  |
| Row Of Chips | 3         | 16.67%  |
| Unknown      | 1         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 33.33%  |
| 8192  | 6         | 28.57%  |
| 2048  | 4         | 19.05%  |
| 16384 | 2         | 9.52%   |
| 32768 | 1         | 4.76%   |
| 1024  | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 7         | 36.84%  |
| 3200    | 4         | 21.05%  |
| 2400    | 3         | 15.79%  |
| 4267    | 2         | 10.53%  |
| 2933    | 1         | 5.26%   |
| 1867    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP HP Laser 107w | 1         | 100%    |

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
| Chicony Electronics                    | 11        | 24.44%  |
| IMC Networks                           | 8         | 17.78%  |
| Bison Electronics                      | 5         | 11.11%  |
| Sunplus Innovation Technology          | 4         | 8.89%   |
| Realtek Semiconductor                  | 4         | 8.89%   |
| Microdia                               | 2         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Syntek                                 | 1         | 2.22%   |
| Samsung Electronics                    | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Pixart Imaging                         | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Lite-On Technology                     | 1         | 2.22%   |
| GEMBIRD                                | 1         | 2.22%   |
| Apple                                  | 1         | 2.22%   |
| Alcor Micro                            | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 8.89%   |
| Bison Lenovo EasyCamera                                 | 3         | 6.67%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 4.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.44%   |
| Chicony Integrated Camera                               | 2         | 4.44%   |
| Chicony FJ Camera                                       | 2         | 4.44%   |
| Syntek Lenovo EasyCamera                                | 1         | 2.22%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 2.22%   |
| Sunplus Asus Webcam                                     | 1         | 2.22%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 2.22%   |
| Realtek USB Camera                                      | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD                            | 1         | 2.22%   |
| Realtek HP Wide Vision HD Camera                        | 1         | 2.22%   |
| Realtek HD WebCam                                       | 1         | 2.22%   |
| Quanta HD User Facing                                   | 1         | 2.22%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 1         | 2.22%   |
| Microdia Lenovo EasyCamera                              | 1         | 2.22%   |
| Microdia Integrated Webcam                              | 1         | 2.22%   |
| Logitech Webcam C270                                    | 1         | 2.22%   |
| Lite-On Integrated Camera                               | 1         | 2.22%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 1         | 2.22%   |
| IMC Networks ov9734_azurewave_camera                    | 1         | 2.22%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 1         | 2.22%   |
| Chicony WebCam                                          | 1         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 2.22%   |
| Chicony USB 2.0 Camera                                  | 1         | 2.22%   |
| Chicony Sony Visual Communication Camera                | 1         | 2.22%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 2.22%   |
| Chicony HP Wide Vision HD Camera                        | 1         | 2.22%   |
| Chicony HD WebCam                                       | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 2.22%   |
| Bison Integrated Camera                                 | 1         | 2.22%   |
| Bison HD Camera                                         | 1         | 2.22%   |
| Apple FaceTime HD Camera                                | 1         | 2.22%   |
| Alcor Micro USB 2.0 Camera                              | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 80%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor    | 1         | 20%     |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 20%     |
| Shenzhen Goodix  Fingerprint Device        | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 75%     |
| OmniKey  | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| OmniKey CardMan 4321                                                        | 1         | 25%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 1         | 25%     |
| Broadcom 5880                                                               | 1         | 25%     |
| Broadcom 58200                                                              | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 59.62%  |
| 1     | 20        | 38.46%  |
| 2     | 1         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 5         | 23.81%  |
| Fingerprint reader    | 5         | 23.81%  |
| Graphics card         | 4         | 19.05%  |
| Chipcard              | 4         | 19.05%  |
| Multimedia controller | 2         | 9.52%   |
| Net/ethernet          | 1         | 4.76%   |


antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 79

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite T110              | [ecb4e047b3](https://linux-hardware.org/?probe=ecb4e047b3) | Aug 11, 2023 |
| Apple         | MacBookAir4,1               | [05b5124d92](https://linux-hardware.org/?probe=05b5124d92) | Aug 09, 2023 |
| HP            | 255 G3                      | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| HP            | Presario CQ56               | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [54dfdc8842](https://linux-hardware.org/?probe=54dfdc8842) | Jun 28, 2023 |
| HP            | Pavilion dv6700             | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| Dell          | Vostro 1015                 | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| HP            | 620                         | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| Intel         | powered classmate PC        | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Aspire E5-511               | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 23        | 37.7%   |
| antiX 22       | 19        | 31.15%  |
| antiX 19.2     | 6         | 9.84%   |
| antiX 19.3     | 3         | 4.92%   |
| antiX 21-runit | 2         | 3.28%   |
| antiX 19.4     | 2         | 3.28%   |
| antiX 19.1     | 2         | 3.28%   |
| antiX 19.5     | 1         | 1.64%   |
| antiX 17.4.1   | 1         | 1.64%   |
| antiX 17.2.1   | 1         | 1.64%   |
| antiX 17       | 1         | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 60        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 22.95%  |
| 5.10.142-antix.2-amd64-smp   | 8         | 13.11%  |
| 4.9.0-326-antix.1-amd64-smp  | 7         | 11.48%  |
| 4.9.0-279-antix.1-amd64-smp  | 5         | 8.2%    |
| 5.10.57-antix.1-amd64-smp    | 4         | 6.56%   |
| 4.9.0-326-antix.1-486-smp    | 4         | 6.56%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 3.28%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 3.28%   |
| 4.9.212-antix.1-486-smp      | 2         | 3.28%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.28%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.64%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.64%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.64%   |
| 4.9.160-antix.2-486-smp      | 1         | 1.64%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.64%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.64%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.64%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.64%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.64%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.64%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 31        | 51.67%  |
| 5.10.142 | 8         | 13.33%  |
| 5.10.57  | 4         | 6.67%   |
| 4.9.212  | 4         | 6.67%   |
| 4.9.235  | 2         | 3.33%   |
| 4.9.200  | 2         | 3.33%   |
| 4.9.160  | 2         | 3.33%   |
| 5.14.0   | 1         | 1.67%   |
| 5.10.88  | 1         | 1.67%   |
| 5.10.27  | 1         | 1.67%   |
| 4.19.202 | 1         | 1.67%   |
| 4.19.100 | 1         | 1.67%   |
| 4.19.0   | 1         | 1.67%   |
| 4.10.5   | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 41        | 68.33%  |
| 5.10    | 14        | 23.33%  |
| 4.19    | 3         | 5%      |
| 5.14    | 1         | 1.67%   |
| 4.10    | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 55%     |
| i686   | 26        | 43.33%  |
| i586   | 1         | 1.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| icewm    | 28        | 46.67%  |
| Unknown  | 27        | 45%     |
| fluxbox  | 2         | 3.33%   |
| XFCE     | 1         | 1.67%   |
| GNOME    | 1         | 1.67%   |
| Cinnamon | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 60        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 60%     |
| SLiM    | 15        | 25%     |
| SLIMSKI | 4         | 6.67%   |
| LightDM | 3         | 5%      |
| XDM     | 1         | 1.67%   |
| SDDM    | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 25        | 41.67%  |
| ru_RU | 6         | 10%     |
| de_DE | 5         | 8.33%   |
| pt_BR | 3         | 5%      |
| es_ES | 3         | 5%      |
| nl_NL | 2         | 3.33%   |
| ja_JP | 2         | 3.33%   |
| it_IT | 2         | 3.33%   |
| en_AU | 2         | 3.33%   |
| zh_HK | 1         | 1.67%   |
| uk_UA | 1         | 1.67%   |
| pl_PL | 1         | 1.67%   |
| hu_HU | 1         | 1.67%   |
| fr_BE | 1         | 1.67%   |
| es_VE | 1         | 1.67%   |
| es_MX | 1         | 1.67%   |
| en_NZ | 1         | 1.67%   |
| en_GB | 1         | 1.67%   |
| de_AT | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 50        | 83.33%  |
| EFI  | 10        | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 51        | 85%     |
| Overlay  | 8         | 13.33%  |
| Reiserfs | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 47        | 78.33%  |
| GPT     | 12        | 20%     |
| Unknown | 1         | 1.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 78.69%  |
| Yes       | 13        | 21.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 61.67%  |
| Yes       | 23        | 38.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 15%     |
| ASUSTek Computer    | 9         | 15%     |
| Lenovo              | 8         | 13.33%  |
| Acer                | 8         | 13.33%  |
| IBM                 | 5         | 8.33%   |
| Dell                | 4         | 6.67%   |
| Toshiba             | 3         | 5%      |
| Fujitsu             | 3         | 5%      |
| KOHJINSHA           | 2         | 3.33%   |
| Apple               | 2         | 3.33%   |
| Samsung Electronics | 1         | 1.67%   |
| Packard Bell        | 1         | 1.67%   |
| MSI                 | 1         | 1.67%   |
| Medion              | 1         | 1.67%   |
| Intel               | 1         | 1.67%   |
| Google              | 1         | 1.67%   |
| Compaq              | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 3.33%   |
| HP Mini 110-3700                   | 2         | 3.33%   |
| Fujitsu FMVNU6G1C                  | 2         | 3.33%   |
| Toshiba Satellite T110             | 1         | 1.67%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.67%   |
| Toshiba Satellite 1905             | 1         | 1.67%   |
| Samsung SQ1S                       | 1         | 1.67%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.67%   |
| MSI GE62 7RE                       | 1         | 1.67%   |
| Medion WIM2170                     | 1         | 1.67%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.67%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.67%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.67%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.67%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.67%   |
| Lenovo G550 2958                   | 1         | 1.67%   |
| Lenovo 3000 V100 076346G           | 1         | 1.67%   |
| KOHJINSHA SX series                | 1         | 1.67%   |
| KOHJINSHA SC series                | 1         | 1.67%   |
| Intel powered classmate PC         | 1         | 1.67%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.67%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.67%   |
| IBM ThinkPad T40 237342G           | 1         | 1.67%   |
| HP Presario CQ56                   | 1         | 1.67%   |
| HP Pavilion dv2700                 | 1         | 1.67%   |
| HP Mini 5101                       | 1         | 1.67%   |
| HP EliteBook 8770w                 | 1         | 1.67%   |
| HP EliteBook 2570p                 | 1         | 1.67%   |
| HP 620                             | 1         | 1.67%   |
| HP 255 G3                          | 1         | 1.67%   |
| Google Candy                       | 1         | 1.67%   |
| Fujitsu FMVS54EB                   | 1         | 1.67%   |
| Dell Vostro 1015                   | 1         | 1.67%   |
| Dell Latitude E6400                | 1         | 1.67%   |
| Dell Latitude 5480                 | 1         | 1.67%   |
| Dell Latitude 2120                 | 1         | 1.67%   |
| Compaq Tablet PC TC1000            | 1         | 1.67%   |
| ASUS X71SL                         | 1         | 1.67%   |
| ASUS X51RL                         | 1         | 1.67%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 11.67%  |
| Toshiba Satellite     | 3         | 5%      |
| Lenovo IdeaPad        | 3         | 5%      |
| IBM ThinkPad          | 3         | 5%      |
| HP Mini               | 3         | 5%      |
| Dell Latitude         | 3         | 5%      |
| Lenovo ThinkPad       | 2         | 3.33%   |
| IBM 260921H           | 2         | 3.33%   |
| HP EliteBook          | 2         | 3.33%   |
| Fujitsu FMVNU6G1C     | 2         | 3.33%   |
| ASUS VivoBook         | 2         | 3.33%   |
| Samsung SQ1S          | 1         | 1.67%   |
| Packard Bell EasyNote | 1         | 1.67%   |
| MSI GE62              | 1         | 1.67%   |
| Medion WIM2170        | 1         | 1.67%   |
| Lenovo G550           | 1         | 1.67%   |
| Lenovo 3000           | 1         | 1.67%   |
| KOHJINSHA SX          | 1         | 1.67%   |
| KOHJINSHA SC          | 1         | 1.67%   |
| Intel powered         | 1         | 1.67%   |
| HP Presario           | 1         | 1.67%   |
| HP Pavilion           | 1         | 1.67%   |
| HP 620                | 1         | 1.67%   |
| HP 255                | 1         | 1.67%   |
| Google Candy          | 1         | 1.67%   |
| Fujitsu FMVS54EB      | 1         | 1.67%   |
| Dell Vostro           | 1         | 1.67%   |
| Compaq Tablet         | 1         | 1.67%   |
| ASUS X71SL            | 1         | 1.67%   |
| ASUS X51RL            | 1         | 1.67%   |
| ASUS S3N              | 1         | 1.67%   |
| ASUS A3L              | 1         | 1.67%   |
| ASUS 900HA            | 1         | 1.67%   |
| ASUS 900A             | 1         | 1.67%   |
| ASUS 1011CX           | 1         | 1.67%   |
| Apple MacBookAir4     | 1         | 1.67%   |
| Apple MacBook7        | 1         | 1.67%   |
| Acer AOA150           | 1         | 1.67%   |
| Unknown               | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 10        | 16.67%  |
| 2007 | 9         | 15%     |
| 2012 | 5         | 8.33%   |
| 2010 | 5         | 8.33%   |
| 2008 | 5         | 8.33%   |
| 2013 | 4         | 6.67%   |
| 2014 | 3         | 5%      |
| 2003 | 3         | 5%      |
| 2020 | 2         | 3.33%   |
| 2017 | 2         | 3.33%   |
| 2011 | 2         | 3.33%   |
| 2005 | 2         | 3.33%   |
| 2004 | 2         | 3.33%   |
| 1999 | 2         | 3.33%   |
| 2022 | 1         | 1.67%   |
| 2019 | 1         | 1.67%   |
| 2016 | 1         | 1.67%   |
| 2006 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 60        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 19        | 31.67%  |
| 1.01-2.0   | 10        | 16.67%  |
| 0.51-1.0   | 10        | 16.67%  |
| 2.01-3.0   | 8         | 13.33%  |
| 4.01-8.0   | 4         | 6.67%   |
| 0.01-0.5   | 4         | 6.67%   |
| 32.01-64.0 | 2         | 3.33%   |
| 8.01-16.0  | 2         | 3.33%   |
| 16.01-24.0 | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 23        | 37.7%   |
| 0.51-1.0 | 22        | 36.07%  |
| 1.01-2.0 | 12        | 19.67%  |
| 2.01-3.0 | 4         | 6.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 81.97%  |
| 2      | 9         | 14.75%  |
| 3      | 1         | 1.64%   |
| 0      | 1         | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 51.67%  |
| Yes       | 29        | 48.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 83.33%  |
| No        | 10        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 96.67%  |
| No        | 2         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 55%     |
| Yes       | 27        | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 15%     |
| Hong Kong   | 9         | 15%     |
| Russia      | 7         | 11.67%  |
| Germany     | 6         | 10%     |
| Netherlands | 3         | 5%      |
| Brazil      | 3         | 5%      |
| Spain       | 2         | 3.33%   |
| Poland      | 2         | 3.33%   |
| Japan       | 2         | 3.33%   |
| Italy       | 2         | 3.33%   |
| Hungary     | 2         | 3.33%   |
| Australia   | 2         | 3.33%   |
| Uruguay     | 1         | 1.67%   |
| Ukraine     | 1         | 1.67%   |
| New Zealand | 1         | 1.67%   |
| Mexico      | 1         | 1.67%   |
| Kenya       | 1         | 1.67%   |
| Kazakhstan  | 1         | 1.67%   |
| Denmark     | 1         | 1.67%   |
| Chile       | 1         | 1.67%   |
| Bulgaria    | 1         | 1.67%   |
| Belgium     | 1         | 1.67%   |
| Austria     | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 9.68%   |
| Sydney                    | 2         | 3.23%   |
| St Petersburg             | 2         | 3.23%   |
| Moscow                    | 2         | 3.23%   |
| Central                   | 2         | 3.23%   |
| Yuzhno-Sakhalinsk         | 1         | 1.61%   |
| Yokohama                  | 1         | 1.61%   |
| Ybbs an der Donau         | 1         | 1.61%   |
| Whitney                   | 1         | 1.61%   |
| Warsaw                    | 1         | 1.61%   |
| Torricella Sicura         | 1         | 1.61%   |
| Toms River                | 1         | 1.61%   |
| Sofia                     | 1         | 1.61%   |
| Sheung Shui               | 1         | 1.61%   |
| Seattle                   | 1         | 1.61%   |
| Schloss Holte-Stukenbrock | 1         | 1.61%   |
| Santiago                  | 1         | 1.61%   |
| Salto                     | 1         | 1.61%   |
| Rotterdam                 | 1         | 1.61%   |
| Reutlingen                | 1         | 1.61%   |
| Purmerend                 | 1         | 1.61%   |
| Pritzwalk                 | 1         | 1.61%   |
| Portland                  | 1         | 1.61%   |
| Pomaz                     | 1         | 1.61%   |
| Norden                    | 1         | 1.61%   |
| Neyagawa                  | 1         | 1.61%   |
| Nairobi                   | 1         | 1.61%   |
| Montevideo                | 1         | 1.61%   |
| Mittegrossefehn           | 1         | 1.61%   |
| Milan                     | 1         | 1.61%   |
| Mechanicsburg             | 1         | 1.61%   |
| Marcinelle                | 1         | 1.61%   |
| Karaganda                 | 1         | 1.61%   |
| Jonesboro                 | 1         | 1.61%   |
| Hortolândia              | 1         | 1.61%   |
| Hobbs                     | 1         | 1.61%   |
| Hagenbach                 | 1         | 1.61%   |
| Grozny                    | 1         | 1.61%   |
| Greenville                | 1         | 1.61%   |
| Granja                    | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 12        | 12     | 18.18%  |
| WDC                 | 11        | 11     | 16.67%  |
| Seagate             | 11        | 11     | 16.67%  |
| Toshiba             | 6         | 6      | 9.09%   |
| Samsung Electronics | 5         | 5      | 7.58%   |
| Unknown             | 2         | 2      | 3.03%   |
| Kingston            | 2         | 2      | 3.03%   |
| HGST                | 2         | 2      | 3.03%   |
| Zheino              | 1         | 1      | 1.52%   |
| Unknown (CF)        | 1         | 1      | 1.52%   |
| Transcend           | 1         | 1      | 1.52%   |
| RECADATA            | 1         | 1      | 1.52%   |
| PNY                 | 1         | 1      | 1.52%   |
| OCZ                 | 1         | 1      | 1.52%   |
| Maxtor              | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| IBM/Hitachi         | 1         | 1      | 1.52%   |
| Hewlett-Packard     | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| BIWIN               | 1         | 1      | 1.52%   |
| BHT                 | 1         | 3      | 1.52%   |
| ASUS-PHISON         | 1         | 1      | 1.52%   |
| Unknown             | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 3.03%   |
| Seagate ST980811AS 80GB                 | 2         | 3.03%   |
| Samsung SSD 750 EVO 120GB               | 2         | 3.03%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 3.03%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 3.03%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.52%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.52%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.52%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.52%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.52%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.52%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.52%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 1.52%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.52%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.52%   |
| Unknown SR64G  64GB                     | 1         | 1.52%   |
| Unknown HAG2e  16GB                     | 1         | 1.52%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.52%   |
| Transcend SSD 2GB                       | 1         | 1.52%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.52%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.52%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.52%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.52%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.52%   |
| Toshiba MK2555GSX 250GB                 | 1         | 1.52%   |
| Seagate ST9320325AS 320GB               | 1         | 1.52%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.52%   |
| Seagate ST9160411AS 160GB               | 1         | 1.52%   |
| Seagate ST9160314AS 160GB               | 1         | 1.52%   |
| Seagate ST9160310AS 160GB               | 1         | 1.52%   |
| Seagate ST9160301AS 160GB               | 1         | 1.52%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.52%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.52%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1.52%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.52%   |
| Samsung MZALQ256HBJD-00BL2 256GB        | 1         | 1.52%   |
| Samsung HS06THB 64GB                    | 1         | 1.52%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 1.52%   |
| PNY CS900 960GB SSD                     | 1         | 1.52%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 12        | 12     | 27.91%  |
| WDC                 | 11        | 11     | 25.58%  |
| Seagate             | 11        | 11     | 25.58%  |
| Toshiba             | 4         | 4      | 9.3%    |
| HGST                | 2         | 2      | 4.65%   |
| Samsung Electronics | 1         | 1      | 2.33%   |
| IBM/Hitachi         | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 15%     |
| Toshiba             | 2         | 2      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Zheino              | 1         | 1      | 5%      |
| Unknown (CF)        | 1         | 1      | 5%      |
| Transcend           | 1         | 1      | 5%      |
| RECADATA            | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| OCZ                 | 1         | 1      | 5%      |
| Maxtor              | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |
| BIWIN               | 1         | 1      | 5%      |
| BHT                 | 1         | 3      | 5%      |
| ASUS-PHISON         | 1         | 1      | 5%      |
| Unknown             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 43     | 66.67%  |
| SSD  | 18        | 22     | 28.57%  |
| MMC  | 2         | 2      | 3.17%   |
| NVMe | 1         | 1      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 65     | 95%     |
| MMC  | 2         | 2      | 3.33%   |
| NVMe | 1         | 1      | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 60     | 91.53%  |
| 0.51-1.0   | 5         | 5      | 8.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 33.87%  |
| 1-20       | 17        | 27.42%  |
| 51-100     | 8         | 12.9%   |
| 21-50      | 7         | 11.29%  |
| 251-500    | 6         | 9.68%   |
| 501-1000   | 2         | 3.23%   |
| Unknown    | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 47        | 78.33%  |
| 21-50   | 6         | 10%     |
| 101-250 | 3         | 5%      |
| 51-100  | 3         | 5%      |
| Unknown | 1         | 1.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST980811AS 80GB         | 2         | 2      | 9.09%   |
| Hitachi HTS542525K9SA00 250GB   | 2         | 2      | 9.09%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 1         | 1      | 4.55%   |
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 4.55%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 4.55%   |
| WDC WD2500BEVT-22ZCT0 250GB     | 1         | 1      | 4.55%   |
| Toshiba MK2555GSX 250GB         | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 4.55%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 4.55%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 4.55%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 4.55%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 4.55%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 4.55%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 4.55%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 4.55%   |
| Hitachi HTS543225A7A384 250GB   | 1         | 1      | 4.55%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 4.55%   |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 4.55%   |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 4.55%   |
| BIWIN SSD 32GB                  | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 40.91%  |
| Seagate | 6         | 6      | 27.27%  |
| WDC     | 4         | 4      | 18.18%  |
| Toshiba | 1         | 1      | 4.55%   |
| HGST    | 1         | 1      | 4.55%   |
| BIWIN   | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 42.86%  |
| Seagate | 6         | 6      | 28.57%  |
| WDC     | 4         | 4      | 19.05%  |
| Toshiba | 1         | 1      | 4.76%   |
| HGST    | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 21     | 95.45%  |
| SSD  | 1         | 1      | 4.55%   |

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
| Works    | 35        | 42     | 57.38%  |
| Malfunc  | 22        | 22     | 36.07%  |
| Detected | 4         | 4      | 6.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 48        | 77.42%  |
| AMD                              | 5         | 8.06%   |
| VIA Technologies                 | 2         | 3.23%   |
| Silicon Integrated Systems [SiS] | 2         | 3.23%   |
| Nvidia                           | 2         | 3.23%   |
| Silicon Image                    | 1         | 1.61%   |
| Samsung Electronics              | 1         | 1.61%   |
| JMicron Technology               | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 6.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 6.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 6.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 5.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 5.48%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 5.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.11%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.74%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.74%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.74%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.74%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.37%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 1.37%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.37%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.37%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.37%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.37%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.37%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.37%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.37%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.37%   |
| AMD SB600 IDE                                                                  | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 50.75%  |
| IDE  | 29        | 43.28%  |
| RAID | 3         | 4.48%   |
| NVMe | 1         | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 53        | 88.33%  |
| AMD          | 5         | 8.33%   |
| GenuineTMx86 | 1         | 1.67%   |
| CentaurHauls | 1         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 6.67%   |
| Intel Pentium M processor 1.60GHz           | 2         | 3.33%   |
| Intel Pentium M processor 1.00GHz           | 2         | 3.33%   |
| Intel Genuine processor 800MHz              | 2         | 3.33%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 3.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 3.33%   |
| Intel Celeron (Mendocino)                   | 2         | 3.33%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.33%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.33%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 3.33%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.67%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.67%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.67%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.67%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.67%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.67%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.67%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.67%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.67%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.67%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.67%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.67%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.67%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.67%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.67%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 1.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.67%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.67%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.67%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.67%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 1         | 1.67%   |
| Intel Atom CPU N550 @ 1.50GHz               | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 12        | 20%     |
| Intel Core 2 Duo        | 7         | 11.67%  |
| Intel Celeron           | 7         | 11.67%  |
| Intel Pentium M         | 6         | 10%     |
| Intel Core i7           | 5         | 8.33%   |
| Intel Genuine           | 4         | 6.67%   |
| Intel Core i5           | 4         | 6.67%   |
| Intel Core i3           | 3         | 5%      |
| AMD E2                  | 2         | 3.33%   |
| Other                   | 1         | 1.67%   |
| Intel Pentium Silver    | 1         | 1.67%   |
| Intel Pentium Dual-Core | 1         | 1.67%   |
| Intel Pentium Dual      | 1         | 1.67%   |
| Intel Pentium 4         | 1         | 1.67%   |
| Intel Celeron Dual-Core | 1         | 1.67%   |
| CentaurHauls VIA Nano   | 1         | 1.67%   |
| AMD E1                  | 1         | 1.67%   |
| AMD Athlon II           | 1         | 1.67%   |
| AMD Athlon 64 X2        | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 51.67%  |
| 1      | 25        | 41.67%  |
| 4      | 4         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 60%     |
| 2      | 24        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 65%     |
| 32-bit         | 21        | 35%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 11.67%  |
| 0x1067a    | 7         | 11.67%  |
| 0x6fd      | 4         | 6.67%   |
| 0x6d6      | 4         | 6.67%   |
| 0x6d8      | 3         | 5%      |
| 0x306a9    | 3         | 5%      |
| 0x106ca    | 3         | 5%      |
| Unknown    | 3         | 5%      |
| 0x66a      | 2         | 3.33%   |
| 0x40651    | 2         | 3.33%   |
| 0x30678    | 2         | 3.33%   |
| 0x30661    | 2         | 3.33%   |
| 0x206a7    | 2         | 3.33%   |
| 0x10661    | 2         | 3.33%   |
| 0xf24      | 1         | 1.67%   |
| 0x906e9    | 1         | 1.67%   |
| 0x806e9    | 1         | 1.67%   |
| 0x706a8    | 1         | 1.67%   |
| 0x706a1    | 1         | 1.67%   |
| 0x6e8      | 1         | 1.67%   |
| 0x695      | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x20655    | 1         | 1.67%   |
| 0x20652    | 1         | 1.67%   |
| 0x07030106 | 1         | 1.67%   |
| 0x0700010f | 1         | 1.67%   |
| 0x06006704 | 1         | 1.67%   |
| 0x010000c8 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 12        | 20%     |
| P6            | 9         | 15%     |
| Penryn        | 7         | 11.67%  |
| Core          | 6         | 10%     |
| Unknown       | 4         | 6.67%   |
| IvyBridge     | 3         | 5%      |
| Haswell       | 3         | 5%      |
| Westmere      | 2         | 3.33%   |
| Silvermont    | 2         | 3.33%   |
| SandyBridge   | 2         | 3.33%   |
| KabyLake      | 2         | 3.33%   |
| Goldmont plus | 2         | 3.33%   |
| Puma          | 1         | 1.67%   |
| NetBurst      | 1         | 1.67%   |
| K8 Hammer     | 1         | 1.67%   |
| K10           | 1         | 1.67%   |
| Jaguar        | 1         | 1.67%   |
| Excavator     | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 61.9%   |
| AMD                              | 11        | 17.46%  |
| Nvidia                           | 9         | 14.29%  |
| Neomagic                         | 2         | 3.17%   |
| VIA Technologies                 | 1         | 1.59%   |
| Silicon Integrated Systems [SiS] | 1         | 1.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 10.96%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 6.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 5         | 6.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 4.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 4.11%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.74%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.74%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 2.74%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.74%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.74%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.37%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.37%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.37%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.37%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.37%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.37%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.37%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.37%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.37%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.37%   |
| Intel HD Graphics 630                                                         | 1         | 1.37%   |
| Intel HD Graphics 620                                                         | 1         | 1.37%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.37%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.37%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.37%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.37%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 1.37%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 56.67%  |
| 1 x AMD        | 11        | 18.33%  |
| 1 x Nvidia     | 6         | 10%     |
| Intel + Nvidia | 3         | 5%      |
| Other          | 2         | 3.33%   |
| 1 x Neomagic   | 2         | 3.33%   |
| 1 x VIA        | 1         | 1.67%   |
| 1 x SiS        | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 86.67%  |
| Unknown     | 6         | 10%     |
| Proprietary | 2         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 27        | 45%     |
| Unknown    | 23        | 38.33%  |
| 1.01-2.0   | 8         | 13.33%  |
| 3.01-4.0   | 1         | 1.67%   |
| 0.51-1.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 27.27%  |
| LG Display              | 10        | 22.73%  |
| Samsung Electronics     | 4         | 9.09%   |
| LG Philips              | 3         | 6.82%   |
| HannStar                | 3         | 6.82%   |
| Chimei Innolux          | 3         | 6.82%   |
| Lenovo                  | 2         | 4.55%   |
| Apple                   | 2         | 4.55%   |
| InfoVision              | 1         | 2.27%   |
| HJW                     | 1         | 2.27%   |
| CPT                     | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| BOE                     | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 4.55%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 2.27%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 2.27%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.27%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.27%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 2.27%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.27%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 1         | 2.27%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.27%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.27%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.27%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 18        | 41.86%  |
| 1024x600          | 7         | 16.28%  |
| 1920x1080 (FHD)   | 6         | 13.95%  |
| 1280x800 (WXGA)   | 6         | 13.95%  |
| 1440x900 (WXGA+)  | 3         | 6.98%   |
| 2288x1287         | 1         | 2.33%   |
| 1920x1200 (WUXGA) | 1         | 2.33%   |
| 1600x900 (HD+)    | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 36.36%  |
| 10     | 6         | 13.64%  |
| 14     | 5         | 11.36%  |
| 13     | 4         | 9.09%   |
| 17     | 3         | 6.82%   |
| 11     | 3         | 6.82%   |
| 12     | 2         | 4.55%   |
| 8      | 2         | 4.55%   |
| 32     | 1         | 2.27%   |
| 24     | 1         | 2.27%   |
| 18     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 50%     |
| 201-300     | 14        | 31.82%  |
| 351-400     | 4         | 9.09%   |
| 101-200     | 2         | 4.55%   |
| 701-800     | 1         | 2.27%   |
| 501-600     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 73.81%  |
| 16/10 | 10        | 23.81%  |
| 3/2   | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 36.36%  |
| 81-90          | 7         | 15.91%  |
| 41-50          | 6         | 13.64%  |
| 51-60          | 3         | 6.82%   |
| 71-80          | 2         | 4.55%   |
| 61-70          | 2         | 4.55%   |
| 1-40           | 2         | 4.55%   |
| 131-140        | 2         | 4.55%   |
| 351-500        | 1         | 2.27%   |
| 201-250        | 1         | 2.27%   |
| 141-150        | 1         | 2.27%   |
| 121-130        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 50%     |
| 121-160 | 14        | 31.82%  |
| 51-100  | 8         | 18.18%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 55        | 90.16%  |
| 2     | 3         | 4.92%   |
| 0     | 3         | 4.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 26        | 26.8%   |
| Realtek Semiconductor            | 20        | 20.62%  |
| Intel                            | 20        | 20.62%  |
| Broadcom                         | 15        | 15.46%  |
| Marvell Technology Group         | 3         | 3.09%   |
| Silicon Integrated Systems [SiS] | 2         | 2.06%   |
| Ralink                           | 2         | 2.06%   |
| Nvidia                           | 2         | 2.06%   |
| Texas Instruments                | 1         | 1.03%   |
| Qualcomm Atheros Communications  | 1         | 1.03%   |
| MediaTek                         | 1         | 1.03%   |
| Hewlett-Packard                  | 1         | 1.03%   |
| Broadcom Limited                 | 1         | 1.03%   |
| Attansic Technology              | 1         | 1.03%   |
| ASIX Electronics                 | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 7.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 7.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 4.24%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4         | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 3.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 3.39%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.54%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 2.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.69%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 2         | 1.69%   |
| Intel Wireless 7260                                                           | 2         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 1.69%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.69%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.85%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 0.85%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.85%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.85%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.85%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.85%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 0.85%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 23        | 37.7%   |
| Intel                           | 18        | 29.51%  |
| Broadcom                        | 11        | 18.03%  |
| Realtek Semiconductor           | 4         | 6.56%   |
| Ralink                          | 2         | 3.28%   |
| Texas Instruments               | 1         | 1.64%   |
| Qualcomm Atheros Communications | 1         | 1.64%   |
| MediaTek                        | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 14.52%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 6.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 6.45%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 4.84%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 4.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 4.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.23%   |
| Intel Wireless 7260                                                           | 2         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.23%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.61%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.61%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.61%   |
| Intel WiFi Link 5100                                                          | 1         | 1.61%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.61%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.61%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.61%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.61%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 18        | 36%     |
| Intel                            | 10        | 20%     |
| Broadcom                         | 7         | 14%     |
| Qualcomm Atheros                 | 5         | 10%     |
| Marvell Technology Group         | 3         | 6%      |
| Silicon Integrated Systems [SiS] | 2         | 4%      |
| Nvidia                           | 2         | 4%      |
| Broadcom Limited                 | 1         | 2%      |
| Attansic Technology              | 1         | 2%      |
| ASIX Electronics                 | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 18%     |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 10%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 8%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 4%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4%      |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4%      |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 4%      |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 4%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| Nvidia MCP89 Ethernet                                             | 1         | 2%      |
| Nvidia MCP67 Ethernet                                             | 1         | 2%      |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2%      |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2%      |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Intel 82551QM Ethernet Controller                                 | 1         | 2%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2%      |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 2%      |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2%      |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2%      |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 2%      |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 2%      |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 50.88%  |
| Ethernet | 50        | 43.86%  |
| Modem    | 6         | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 85.25%  |
| Ethernet | 9         | 14.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 78.33%  |
| 1     | 13        | 21.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 78.69%  |
| Yes  | 13        | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Broadcom                        | 8         | 30.77%  |
| Intel                           | 4         | 15.38%  |
| Qualcomm Atheros Communications | 2         | 7.69%   |
| Lite-On Technology              | 2         | 7.69%   |
| IMC Networks                    | 2         | 7.69%   |
| Apple                           | 2         | 7.69%   |
| Taiyo Yuden                     | 1         | 3.85%   |
| Realtek Semiconductor           | 1         | 3.85%   |
| Ralink Technology               | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 7.69%   |
| Intel Bluetooth wireless interface                  | 2         | 7.69%   |
| IMC Networks Bluetooth Device                       | 2         | 7.69%   |
| Broadcom HP Portable SoftSailing                    | 2         | 7.69%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 7.69%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 3.85%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.85%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.85%   |
| Intel Bluetooth Device                              | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.85%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.85%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 3.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.85%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 3.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.85%   |
| Apple Bluetooth Host Controller                     | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 47        | 74.6%   |
| AMD                              | 7         | 11.11%  |
| Nvidia                           | 3         | 4.76%   |
| VIA Technologies                 | 2         | 3.17%   |
| Silicon Integrated Systems [SiS] | 2         | 3.17%   |
| ESS Technology                   | 2         | 3.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 18.84%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 7.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 5.8%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.35%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.9%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.9%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.9%    |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.9%    |
| AMD FCH Azalia Controller                                                  | 2         | 2.9%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.45%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.45%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.45%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.45%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.45%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.45%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.45%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.45%   |
| AMD High Definition Audio Controller                                       | 1         | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 25        | 38.46%  |
| SK hynix            | 13        | 20%     |
| Samsung Electronics | 9         | 13.85%  |
| Unknown             | 7         | 10.77%  |
| Micron Technology   | 4         | 6.15%   |
| Kingston            | 3         | 4.62%   |
| Crucial             | 2         | 3.08%   |
| Unknown (8A02)      | 1         | 1.54%   |
| Avant               | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 7         | 10%     |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4.29%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.86%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 2.86%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.86%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 2.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 2.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 2.86%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 2         | 2.86%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 2         | 2.86%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.43%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.43%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.43%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.43%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.43%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.43%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.43%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.43%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.43%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.43%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.43%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.43%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 1.43%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.43%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.43%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.43%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.43%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.43%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 20        | 34.48%  |
| SDRAM | 12        | 20.69%  |
| DDR2  | 12        | 20.69%  |
| DDR4  | 5         | 8.62%   |
| DDR   | 5         | 8.62%   |
| DRAM  | 4         | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 92.98%  |
| DIMM         | 3         | 5.26%   |
| Row Of Chips | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 23        | 34.33%  |
| 1024  | 16        | 23.88%  |
| 4096  | 12        | 17.91%  |
| 512   | 5         | 7.46%   |
| 8192  | 4         | 5.97%   |
| 256   | 3         | 4.48%   |
| 64    | 2         | 2.99%   |
| 16384 | 1         | 1.49%   |
| 232   | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 31.67%  |
| 1600    | 11        | 18.33%  |
| 1067    | 5         | 8.33%   |
| 533     | 4         | 6.67%   |
| 4199    | 3         | 5%      |
| 2400    | 2         | 3.33%   |
| 1334    | 2         | 3.33%   |
| 1333    | 2         | 3.33%   |
| 800     | 2         | 3.33%   |
| 667     | 2         | 3.33%   |
| 200     | 2         | 3.33%   |
| 3266    | 1         | 1.67%   |
| 3200    | 1         | 1.67%   |
| 2667    | 1         | 1.67%   |
| 1866    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 266     | 1         | 1.67%   |

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
| Chicony Electronics                    | 9         | 21.95%  |
| Suyin                                  | 4         | 9.76%   |
| Microdia                               | 4         | 9.76%   |
| IMC Networks                           | 4         | 9.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.76%   |
| Bison Electronics                      | 4         | 9.76%   |
| Sunplus Innovation Technology          | 2         | 4.88%   |
| Silicon Motion                         | 2         | 4.88%   |
| Pixart Imaging                         | 2         | 4.88%   |
| Apple                                  | 2         | 4.88%   |
| Syntek                                 | 1         | 2.44%   |
| Realtek Semiconductor                  | 1         | 2.44%   |
| Lenovo                                 | 1         | 2.44%   |
| Importek                               | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                           | 3         | 7.32%   |
| Suyin USB 2.0 Camera                                    | 2         | 4.88%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 4.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.88%   |
| Bison BisonCam, NB Pro                                  | 2         | 4.88%   |
| Syntek Integrated Camera                                | 1         | 2.44%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.44%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.44%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.44%   |
| Sunplus HD WebCam                                       | 1         | 2.44%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.44%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.44%   |
| Realtek HD WebCam                                       | 1         | 2.44%   |
| Microdia Integrated Webcam                              | 1         | 2.44%   |
| Lenovo Integrated Webcam                                | 1         | 2.44%   |
| Importek FJ Camera                                      | 1         | 2.44%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.44%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.44%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.44%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.44%   |
| Chicony HP Webcam                                       | 1         | 2.44%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.44%   |
| Chicony HD WebCam                                       | 1         | 2.44%   |
| Chicony EasyCamera                                      | 1         | 2.44%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.44%   |
| Chicony CNF7050                                         | 1         | 2.44%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.44%   |
| Bison Lenovo EasyCamera                                 | 1         | 2.44%   |
| Bison Acer Crystal Eye Webcam                           | 1         | 2.44%   |
| Apple FaceTime Camera                                   | 1         | 2.44%   |
| Apple Built-in iSight                                   | 1         | 2.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 5         | 71.43%  |
| Validity Sensors | 1         | 14.29%  |
| Upek             | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 42.86%  |
| AuthenTec AES1600                                      | 2         | 28.57%  |
| Validity Sensors VFS491                                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 42        | 70%     |
| 1     | 17        | 28.33%  |
| 3     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 11        | 57.89%  |
| Fingerprint reader | 7         | 36.84%  |
| Chipcard           | 1         | 5.26%   |


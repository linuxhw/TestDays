Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 85

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Dell          | Inspiron 3543               | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Latitude 7480               | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 7         | 10.14%  |
| 5.15.0-50-generic     | 5         | 7.25%   |
| 5.15.0-48-generic     | 5         | 7.25%   |
| 5.15.0-52-generic     | 4         | 5.8%    |
| 5.19.0-35-generic     | 3         | 4.35%   |
| 5.15.0-53-generic     | 3         | 4.35%   |
| 5.15.0-40-generic     | 3         | 4.35%   |
| 5.15.0-39-generic     | 3         | 4.35%   |
| 5.15.0-30-generic     | 3         | 4.35%   |
| 5.19.0-38-generic     | 2         | 2.9%    |
| 5.15.0-67-generic     | 2         | 2.9%    |
| 5.15.0-56-generic     | 2         | 2.9%    |
| 5.15.0-47-generic     | 2         | 2.9%    |
| 5.15.0-46-generic     | 2         | 2.9%    |
| 5.15.0-33-generic     | 2         | 2.9%    |
| 5.15.0-25-generic     | 2         | 2.9%    |
| 6.1.0-060100-generic  | 1         | 1.45%   |
| 5.19.0-41-generic     | 1         | 1.45%   |
| 5.19.0-051900-generic | 1         | 1.45%   |
| 5.15.0-69-generic     | 1         | 1.45%   |
| 5.15.0-60-generic     | 1         | 1.45%   |
| 5.15.0-58-generic     | 1         | 1.45%   |
| 5.15.0-57-generic     | 1         | 1.45%   |
| 5.15.0-52-lowlatency  | 1         | 1.45%   |
| 5.15.0-43-generic     | 1         | 1.45%   |
| 5.15.0-41-generic     | 1         | 1.45%   |
| 5.15.0-35-generic     | 1         | 1.45%   |
| 5.15.0-18-generic     | 1         | 1.45%   |
| 5.15.0-10058-tuxedo   | 1         | 1.45%   |
| 5.15.0-10056-tuxedo   | 1         | 1.45%   |
| 5.15.0-10052-tuxedo   | 1         | 1.45%   |
| 5.15.0-10047-tuxedo   | 1         | 1.45%   |
| 5.15.0-10041-tuxedo   | 1         | 1.45%   |
| 5.13.0-35-generic     | 1         | 1.45%   |
| 5.13.0-19-generic     | 1         | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 56        | 84.85%  |
| 5.19.0  | 7         | 10.61%  |
| 5.13.0  | 2         | 3.03%   |
| 6.1.0   | 1         | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 56        | 84.85%  |
| 5.19    | 7         | 10.61%  |
| 5.13    | 2         | 3.03%   |
| 6.1     | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 62        | 95.38%  |
| GNOME  | 3         | 4.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 63        | 96.92%  |
| Wayland | 2         | 3.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 47        | 72.31%  |
| Unknown | 12        | 18.46%  |
| GDM3    | 6         | 9.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 29.23%  |
| fr_FR | 8         | 12.31%  |
| de_DE | 8         | 12.31%  |
| pt_BR | 5         | 7.69%   |
| it_IT | 3         | 4.62%   |
| en_GB | 3         | 4.62%   |
| ru_RU | 2         | 3.08%   |
| hu_HU | 2         | 3.08%   |
| fr_BE | 2         | 3.08%   |
| en_IE | 2         | 3.08%   |
| en_CA | 2         | 3.08%   |
| pl_PL | 1         | 1.54%   |
| mt_MT | 1         | 1.54%   |
| ja_JP | 1         | 1.54%   |
| es_PE | 1         | 1.54%   |
| es_MX | 1         | 1.54%   |
| es_EC | 1         | 1.54%   |
| es_CL | 1         | 1.54%   |
| cs_CZ | 1         | 1.54%   |
| C     | 1         | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 40        | 61.54%  |
| EFI  | 25        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 93.85%  |
| Overlay | 2         | 3.08%   |
| Xfs     | 1         | 1.54%   |
| Btrfs   | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 40        | 61.54%  |
| Unknown | 21        | 32.31%  |
| MBR     | 4         | 6.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 83.08%  |
| Yes       | 11        | 16.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 69.7%   |
| Yes       | 20        | 30.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 15        | 23.08%  |
| Dell                   | 11        | 16.92%  |
| ASUSTek Computer       | 10        | 15.38%  |
| Hewlett-Packard        | 8         | 12.31%  |
| TUXEDO                 | 5         | 7.69%   |
| MSI                    | 3         | 4.62%   |
| Apple                  | 3         | 4.62%   |
| Google                 | 2         | 3.08%   |
| Toshiba                | 1         | 1.54%   |
| Timi                   | 1         | 1.54%   |
| Razer                  | 1         | 1.54%   |
| Digibras               | 1         | 1.54%   |
| Chuwi                  | 1         | 1.54%   |
| AXIOO                  | 1         | 1.54%   |
| Avell High Performance | 1         | 1.54%   |
| Acer                   | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.54%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.54%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.54%   |
| TUXEDO Book BA1510                                   | 1         | 1.54%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.54%   |
| Toshiba Satellite A505                               | 1         | 1.54%   |
| Timi TM1604                                          | 1         | 1.54%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.54%   |
| MSI Modern 15 A10M                                   | 1         | 1.54%   |
| MSI GL62 6QF                                         | 1         | 1.54%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.54%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.54%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.54%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.54%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.54%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.54%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.54%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.54%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.54%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.54%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.54%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.54%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.54%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.54%   |
| Lenovo G500 20236                                    | 1         | 1.54%   |
| Lenovo G50-45 80E3                                   | 1         | 1.54%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.54%   |
| HP ProBook 450 G7                                    | 1         | 1.54%   |
| HP ProBook 445 G7                                    | 1         | 1.54%   |
| HP Pavilion g6                                       | 1         | 1.54%   |
| HP ENVY 17                                           | 1         | 1.54%   |
| HP ElitePad 1000 G2                                  | 1         | 1.54%   |
| HP EliteBook Folio 1040 G3                           | 1         | 1.54%   |
| HP EliteBook 840 G3                                  | 1         | 1.54%   |
| Google Rabbid                                        | 1         | 1.54%   |
| Google Boten                                         | 1         | 1.54%   |
| Digibras NH4CU03                                     | 1         | 1.54%   |
| Dell XPS 13 9360                                     | 1         | 1.54%   |
| Dell XPS 13 9310                                     | 1         | 1.54%   |
| Dell Vostro 15 5510                                  | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 6         | 9.23%   |
| Lenovo IdeaPad              | 5         | 7.69%   |
| Dell Inspiron               | 4         | 6.15%   |
| HP ProBook                  | 3         | 4.62%   |
| Dell Latitude               | 3         | 4.62%   |
| ASUS VivoBook               | 3         | 4.62%   |
| TUXEDO Book                 | 2         | 3.08%   |
| HP EliteBook                | 2         | 3.08%   |
| Dell XPS                    | 2         | 3.08%   |
| TUXEDO Polaris              | 1         | 1.54%   |
| TUXEDO InfinityBook         | 1         | 1.54%   |
| TUXEDO Aura                 | 1         | 1.54%   |
| Toshiba Satellite           | 1         | 1.54%   |
| Timi TM1604                 | 1         | 1.54%   |
| Razer Blade                 | 1         | 1.54%   |
| MSI Modern                  | 1         | 1.54%   |
| MSI GL62                    | 1         | 1.54%   |
| MSI Alpha                   | 1         | 1.54%   |
| Lenovo V15                  | 1         | 1.54%   |
| Lenovo Legion               | 1         | 1.54%   |
| Lenovo G500                 | 1         | 1.54%   |
| Lenovo G50-45               | 1         | 1.54%   |
| HP Pavilion                 | 1         | 1.54%   |
| HP ENVY                     | 1         | 1.54%   |
| HP ElitePad                 | 1         | 1.54%   |
| Google Rabbid               | 1         | 1.54%   |
| Google Boten                | 1         | 1.54%   |
| Digibras NH4CU03            | 1         | 1.54%   |
| Dell Vostro                 | 1         | 1.54%   |
| Dell Precision              | 1         | 1.54%   |
| Chuwi HeroBook              | 1         | 1.54%   |
| AXIOO Slimbook              | 1         | 1.54%   |
| Avell High Performance B.ON | 1         | 1.54%   |
| ASUS ZenBook                | 1         | 1.54%   |
| ASUS X555LAB                | 1         | 1.54%   |
| ASUS X205TA                 | 1         | 1.54%   |
| ASUS UX303UA                | 1         | 1.54%   |
| ASUS T200TAC                | 1         | 1.54%   |
| ASUS K52F                   | 1         | 1.54%   |
| ASUS ASUS                   | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 12        | 18.46%  |
| 2020 | 11        | 16.92%  |
| 2019 | 6         | 9.23%   |
| 2014 | 6         | 9.23%   |
| 2018 | 5         | 7.69%   |
| 2016 | 4         | 6.15%   |
| 2017 | 3         | 4.62%   |
| 2015 | 3         | 4.62%   |
| 2013 | 3         | 4.62%   |
| 2011 | 3         | 4.62%   |
| 2009 | 3         | 4.62%   |
| 2012 | 2         | 3.08%   |
| 2010 | 2         | 3.08%   |
| 2022 | 1         | 1.54%   |
| 2008 | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 65        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 90.77%  |
| Enabled  | 6         | 9.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 96.92%  |
| Yes  | 2         | 3.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 36.36%  |
| 16.01-24.0  | 18        | 27.27%  |
| 3.01-4.0    | 8         | 12.12%  |
| 8.01-16.0   | 8         | 12.12%  |
| 32.01-64.0  | 5         | 7.58%   |
| 64.01-256.0 | 2         | 3.03%   |
| 1.01-2.0    | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 21        | 31.34%  |
| 1.01-2.0   | 18        | 26.87%  |
| 4.01-8.0   | 16        | 23.88%  |
| 3.01-4.0   | 7         | 10.45%  |
| 8.01-16.0  | 4         | 5.97%   |
| 24.01-32.0 | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 74.63%  |
| 2      | 15        | 22.39%  |
| 3      | 2         | 2.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 81.54%  |
| Yes       | 12        | 18.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 76.92%  |
| No        | 15        | 23.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 96.92%  |
| No        | 2         | 3.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 86.15%  |
| No        | 9         | 13.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 10        | 15.38%  |
| Germany            | 8         | 12.31%  |
| France             | 8         | 12.31%  |
| Brazil             | 5         | 7.69%   |
| Italy              | 3         | 4.62%   |
| Poland             | 2         | 3.08%   |
| Ireland            | 2         | 3.08%   |
| Hungary            | 2         | 3.08%   |
| Canada             | 2         | 3.08%   |
| Belgium            | 2         | 3.08%   |
| UK                 | 1         | 1.54%   |
| Sweden             | 1         | 1.54%   |
| Slovenia           | 1         | 1.54%   |
| Russia             | 1         | 1.54%   |
| Romania            | 1         | 1.54%   |
| Peru               | 1         | 1.54%   |
| Mexico             | 1         | 1.54%   |
| Malta              | 1         | 1.54%   |
| Japan              | 1         | 1.54%   |
| Indonesia          | 1         | 1.54%   |
| Greece             | 1         | 1.54%   |
| Ghana              | 1         | 1.54%   |
| Ecuador            | 1         | 1.54%   |
| Dominican Republic | 1         | 1.54%   |
| Czechia            | 1         | 1.54%   |
| Chile              | 1         | 1.54%   |
| Cabo Verde         | 1         | 1.54%   |
| Bulgaria           | 1         | 1.54%   |
| Belarus            | 1         | 1.54%   |
| Austria            | 1         | 1.54%   |
| Algeria            | 1         | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 3.08%   |
| Dublin                | 2         | 3.08%   |
| Budapest              | 2         | 3.08%   |
| Wertheim am Main      | 1         | 1.54%   |
| Weisswasser           | 1         | 1.54%   |
| Weilheim              | 1         | 1.54%   |
| Vienna                | 1         | 1.54%   |
| Victoria              | 1         | 1.54%   |
| Vasto                 | 1         | 1.54%   |
| Targu Frumos          | 1         | 1.54%   |
| Tarakan               | 1         | 1.54%   |
| Sunnyvale             | 1         | 1.54%   |
| St Petersburg         | 1         | 1.54%   |
| Sofia                 | 1         | 1.54%   |
| Siegen                | 1         | 1.54%   |
| Sétif                | 1         | 1.54%   |
| Seelze                | 1         | 1.54%   |
| Sao Paulo             | 1         | 1.54%   |
| Sao Bernardo do Campo | 1         | 1.54%   |
| Santo Domingo Este    | 1         | 1.54%   |
| Santiago              | 1         | 1.54%   |
| Saint-Gilles          | 1         | 1.54%   |
| Renton                | 1         | 1.54%   |
| Recife                | 1         | 1.54%   |
| Queens                | 1         | 1.54%   |
| Puebla City           | 1         | 1.54%   |
| Praia                 | 1         | 1.54%   |
| Postojna              | 1         | 1.54%   |
| Ostrava               | 1         | 1.54%   |
| Orvault               | 1         | 1.54%   |
| Nuremberg             | 1         | 1.54%   |
| Naples                | 1         | 1.54%   |
| Monza                 | 1         | 1.54%   |
| Mishawaka             | 1         | 1.54%   |
| Massaranduba          | 1         | 1.54%   |
| Lund                  | 1         | 1.54%   |
| Lima                  | 1         | 1.54%   |
| Lille                 | 1         | 1.54%   |
| Leominster            | 1         | 1.54%   |
| Le Mee-sur-Seine      | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 17        | 18     | 20.73%  |
| Toshiba                        | 8         | 10     | 9.76%   |
| Unknown                        | 7         | 7      | 8.54%   |
| Crucial                        | 6         | 7      | 7.32%   |
| WDC                            | 5         | 6      | 6.1%    |
| Seagate                        | 5         | 5      | 6.1%    |
| Micron Technology              | 5         | 5      | 6.1%    |
| SK hynix                       | 4         | 4      | 4.88%   |
| Intel                          | 3         | 3      | 3.66%   |
| Kingston                       | 2         | 2      | 2.44%   |
| JMicron Technology             | 2         | 2      | 2.44%   |
| China                          | 2         | 3      | 2.44%   |
| VISIPRO                        | 1         | 1      | 1.22%   |
| Union Memory                   | 1         | 1      | 1.22%   |
| TO Exter                       | 1         | 1      | 1.22%   |
| SPCC                           | 1         | 1      | 1.22%   |
| Solid State Storage Technology | 1         | 1      | 1.22%   |
| SanDisk                        | 1         | 1      | 1.22%   |
| Realtek Semiconductor          | 1         | 1      | 1.22%   |
| Phison Electronics             | 1         | 1      | 1.22%   |
| OWC                            | 1         | 1      | 1.22%   |
| Netac                          | 1         | 1      | 1.22%   |
| KIOXIA                         | 1         | 1      | 1.22%   |
| Hewlett-Packard                | 1         | 1      | 1.22%   |
| Corsair                        | 1         | 2      | 1.22%   |
| Apple                          | 1         | 1      | 1.22%   |
| A-DATA Technology              | 1         | 1      | 1.22%   |
| Unknown                        | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                   | 2         | 2.41%   |
| Unknown SD64G  64GB                        | 2         | 2.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2.41%   |
| Samsung SSD 980 PRO 2TB                    | 2         | 2.41%   |
| Samsung SSD 980 500GB                      | 2         | 2.41%   |
| Samsung SSD 860 EVO M.2 500GB              | 2         | 2.41%   |
| Samsung MZVLQ512HALU-000H1 512GB           | 2         | 2.41%   |
| Crucial CT240BX500SSD1 240GB               | 2         | 2.41%   |
| WDC WD10JPVX-75JC3T0 1TB                   | 1         | 1.2%    |
| WDC PC SN730 NVMe 256GB                    | 1         | 1.2%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB       | 1         | 1.2%    |
| WDC PC SN520 SDAPNUW-512G-1002 512GB       | 1         | 1.2%    |
| VISIPRO SSD 256GB                          | 1         | 1.2%    |
| Unknown SL128  128GB                       | 1         | 1.2%    |
| Unknown SA16G  16GB                        | 1         | 1.2%    |
| Unknown NCard  4GB                         | 1         | 1.2%    |
| Unknown MMC128  128GB                      | 1         | 1.2%    |
| Unknown MMC Card  64GB                     | 1         | 1.2%    |
| Union Memory RTOTJ128VGD2EYX 128GB SSD     | 1         | 1.2%    |
| Toshiba XG6 NVMe SSD Controller 1024GB     | 1         | 1.2%    |
| Toshiba TR150 480GB SSD                    | 1         | 1.2%    |
| Toshiba MQ04ABF100 1TB                     | 1         | 1.2%    |
| Toshiba MQ01ABD100 1TB                     | 1         | 1.2%    |
| Toshiba MQ01ABD075 752GB                   | 1         | 1.2%    |
| Toshiba KXG50ZNV512G NVMe 512GB            | 1         | 1.2%    |
| Toshiba KBG40ZNT256G MEMORY 256GB          | 1         | 1.2%    |
| Toshiba KBG30ZMT256G 256GB                 | 1         | 1.2%    |
| TO Exter nal USB 3.0 320GB                 | 1         | 1.2%    |
| SPCC Solid State Disk 120GB                | 1         | 1.2%    |
| Solid State Storage NVMe CA6-8D1024 1024GB | 1         | 1.2%    |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB  | 1         | 1.2%    |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB    | 1         | 1.2%    |
| SK hynix HCG8e  64GB                       | 1         | 1.2%    |
| SK hynix HBG4e  32GB                       | 1         | 1.2%    |
| Seagate ST500LT012-9WS142 500GB            | 1         | 1.2%    |
| Seagate ST2000LM007-1R8174 2TB             | 1         | 1.2%    |
| Seagate ST1000LM014-1EJ164 1TB             | 1         | 1.2%    |
| SanDisk SD8SN8U-128G-1006 128GB SSD        | 1         | 1.2%    |
| Samsung SSD 870 QVO 1TB                    | 1         | 1.2%    |
| Samsung SSD 860 EVO M.2 250GB              | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 38.46%  |
| WDC                 | 3         | 3      | 23.08%  |
| Toshiba             | 3         | 3      | 23.08%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| JMicron Technology  | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 23.33%  |
| Crucial             | 6         | 7      | 20%     |
| Micron Technology   | 3         | 3      | 10%     |
| China               | 2         | 3      | 6.67%   |
| VISIPRO             | 1         | 1      | 3.33%   |
| Union Memory        | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| TO Exter            | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| OWC                 | 1         | 1      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| Corsair             | 1         | 2      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 28        | 32     | 36.36%  |
| SSD     | 27        | 33     | 35.06%  |
| HDD     | 13        | 13     | 16.88%  |
| MMC     | 8         | 10     | 10.39%  |
| Unknown | 1         | 1      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 44     | 48.65%  |
| NVMe | 28        | 32     | 37.84%  |
| MMC  | 8         | 10     | 10.81%  |
| SAS  | 2         | 3      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 31     | 64.29%  |
| 0.51-1.0   | 12        | 12     | 28.57%  |
| 1.01-2.0   | 3         | 3      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 38.46%  |
| 101-250        | 20        | 30.77%  |
| 501-1000       | 6         | 9.23%   |
| 51-100         | 6         | 9.23%   |
| 21-50          | 3         | 4.62%   |
| 1001-2000      | 3         | 4.62%   |
| More than 3000 | 1         | 1.54%   |
| 1-20           | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 25.76%  |
| 21-50     | 16        | 24.24%  |
| 101-250   | 14        | 21.21%  |
| 51-100    | 10        | 15.15%  |
| 251-500   | 6         | 9.09%   |
| 501-1000  | 2         | 3.03%   |
| 1001-2000 | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 41        | 51     | 60.29%  |
| Works    | 26        | 37     | 38.24%  |
| Malfunc  | 1         | 1      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 42        | 55.26%  |
| Samsung Electronics            | 9         | 11.84%  |
| AMD                            | 6         | 7.89%   |
| Toshiba America Info Systems   | 3         | 3.95%   |
| SanDisk                        | 3         | 3.95%   |
| SK hynix                       | 2         | 2.63%   |
| Micron Technology              | 2         | 2.63%   |
| KIOXIA                         | 2         | 2.63%   |
| Kingston Technology Company    | 2         | 2.63%   |
| Solid State Storage Technology | 1         | 1.32%   |
| Realtek Semiconductor          | 1         | 1.32%   |
| Phison Electronics             | 1         | 1.32%   |
| Nvidia                         | 1         | 1.32%   |
| ADATA Technology               | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 8.75%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 7.5%    |
| Samsung NVMe SSD Controller 980                                              | 5         | 6.25%   |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 5%      |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 3.75%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 3.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 3.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 2.5%    |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.25%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.25%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.25%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.25%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.25%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 1.25%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.25%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.25%   |
| Realtek NVMe Controller                                                      | 1         | 1.25%   |
| Phison NVMe Storage Controller                                               | 1         | 1.25%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.25%   |
| Micron NVMe Storage Controller                                               | 1         | 1.25%   |
| Micron NVMe Controller                                                       | 1         | 1.25%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.25%   |
| Kingston Company NVMe Controller                                             | 1         | 1.25%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 1.25%   |
| Intel SSD 660P Series                                                        | 1         | 1.25%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 56.41%  |
| NVMe | 28        | 35.9%   |
| RAID | 5         | 6.41%   |
| IDE  | 1         | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 86.15%  |
| AMD    | 9         | 13.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 6.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 3.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 3.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 3.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.08%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 3.08%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 3.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.08%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 3.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.08%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.54%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.54%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.54%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.54%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.54%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.54%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.54%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 16        | 24.62%  |
| Intel Core i7        | 12        | 18.46%  |
| Other                | 10        | 15.38%  |
| Intel Core i3        | 5         | 7.69%   |
| Intel Celeron        | 4         | 6.15%   |
| AMD Ryzen 5          | 4         | 6.15%   |
| Intel Atom           | 3         | 4.62%   |
| AMD Ryzen 7          | 3         | 4.62%   |
| Intel Pentium        | 2         | 3.08%   |
| Intel Core 2 Duo     | 2         | 3.08%   |
| Intel Pentium Silver | 1         | 1.54%   |
| Intel Core i9        | 1         | 1.54%   |
| AMD Ryzen 3          | 1         | 1.54%   |
| AMD A8               | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 29        | 44.62%  |
| 2      | 26        | 40%     |
| 8      | 6         | 9.23%   |
| 6      | 3         | 4.62%   |
| 10     | 1         | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 75.38%  |
| 1      | 16        | 24.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 56.06%  |
| 0x806ec    | 3         | 4.55%   |
| 0x806c1    | 3         | 4.55%   |
| 0x206a7    | 3         | 4.55%   |
| 0x08600106 | 3         | 4.55%   |
| 0x706a8    | 2         | 3.03%   |
| 0x20655    | 2         | 3.03%   |
| 0x08108102 | 2         | 3.03%   |
| 0x906ea    | 1         | 1.52%   |
| 0x806eb    | 1         | 1.52%   |
| 0x806ea    | 1         | 1.52%   |
| 0x806d1    | 1         | 1.52%   |
| 0x506c9    | 1         | 1.52%   |
| 0x40651    | 1         | 1.52%   |
| 0x306d4    | 1         | 1.52%   |
| 0x30678    | 1         | 1.52%   |
| 0x106e5    | 1         | 1.52%   |
| 0x0a50000c | 1         | 1.52%   |
| 0x07030104 | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 21.54%  |
| TigerLake     | 7         | 10.77%  |
| Skylake       | 5         | 7.69%   |
| IvyBridge     | 4         | 6.15%   |
| Unknown       | 4         | 6.15%   |
| Zen 2         | 3         | 4.62%   |
| Silvermont    | 3         | 4.62%   |
| SandyBridge   | 3         | 4.62%   |
| Goldmont plus | 3         | 4.62%   |
| Broadwell     | 3         | 4.62%   |
| Zen+          | 2         | 3.08%   |
| Zen 3         | 2         | 3.08%   |
| Westmere      | 2         | 3.08%   |
| Penryn        | 2         | 3.08%   |
| IceLake       | 2         | 3.08%   |
| Haswell       | 2         | 3.08%   |
| Puma          | 1         | 1.54%   |
| Nehalem       | 1         | 1.54%   |
| Goldmont      | 1         | 1.54%   |
| CometLake     | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 67.09%  |
| Nvidia | 15        | 18.99%  |
| AMD    | 11        | 13.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 8.64%   |
| Intel UHD Graphics 620                                                                | 5         | 6.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 4.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 4.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 4.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 3.7%    |
| Intel HD Graphics 5500                                                                | 3         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 3.7%    |
| AMD Renoir                                                                            | 3         | 3.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 2.47%   |
| Intel HD Graphics 620                                                                 | 2         | 2.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 2.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 2.47%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 1.23%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 1.23%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.23%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.23%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.23%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.23%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 1.23%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.23%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.23%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.23%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.23%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.23%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 1.23%   |
| Intel HD Graphics 530                                                                 | 1         | 1.23%   |
| Intel HD Graphics 500                                                                 | 1         | 1.23%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.23%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 60%     |
| Intel + Nvidia | 11        | 16.92%  |
| 1 x AMD        | 6         | 9.23%   |
| 1 x Nvidia     | 3         | 4.62%   |
| 2 x AMD        | 2         | 3.08%   |
| Intel + AMD    | 2         | 3.08%   |
| Other          | 1         | 1.54%   |
| AMD + Nvidia   | 1         | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 86.15%  |
| Proprietary | 8         | 12.31%  |
| Unknown     | 1         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 84.62%  |
| 1.01-2.0   | 4         | 6.15%   |
| 0.01-0.5   | 3         | 4.62%   |
| 0.51-1.0   | 2         | 3.08%   |
| 7.01-8.0   | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 18        | 24.32%  |
| BOE                     | 16        | 21.62%  |
| Samsung Electronics     | 9         | 12.16%  |
| AU Optronics            | 8         | 10.81%  |
| LG Display              | 7         | 9.46%   |
| Sharp                   | 3         | 4.05%   |
| Apple                   | 3         | 4.05%   |
| Goldstar                | 2         | 2.7%    |
| Unknown (AAA)           | 1         | 1.35%   |
| Philips                 | 1         | 1.35%   |
| MStar                   | 1         | 1.35%   |
| Lenovo                  | 1         | 1.35%   |
| KDC                     | 1         | 1.35%   |
| IBM                     | 1         | 1.35%   |
| Daewoo                  | 1         | 1.35%   |
| Chi Mei Optoelectronics | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 2.7%    |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 1.35%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 1.35%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 1.35%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 1.35%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 1.35%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 1.35%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 1.35%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 1.35%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 1.35%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 1         | 1.35%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch            | 1         | 1.35%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch            | 1         | 1.35%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch               | 1         | 1.35%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                  | 1         | 1.35%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                  | 1         | 1.35%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 1         | 1.35%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 1         | 1.35%   |
| Daewoo 23.6W Monitor DWE0236 1920x1080 521x293mm 23.5-inch             | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 42.65%  |
| 1366x768 (WXGA)    | 19        | 27.94%  |
| 2560x1440 (QHD)    | 3         | 4.41%   |
| 1600x900 (HD+)     | 3         | 4.41%   |
| 1280x800 (WXGA)    | 3         | 4.41%   |
| 3840x2160 (4K)     | 2         | 2.94%   |
| 1920x1200 (WUXGA)  | 2         | 2.94%   |
| 1680x1050 (WSXGA+) | 2         | 2.94%   |
| 3456x2160          | 1         | 1.47%   |
| 2880x1800          | 1         | 1.47%   |
| 2560x1600          | 1         | 1.47%   |
| 1440x900 (WXGA+)   | 1         | 1.47%   |
| 1360x768           | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 32        | 43.24%  |
| 13      | 15        | 20.27%  |
| 14      | 7         | 9.46%   |
| 17      | 4         | 5.41%   |
| 11      | 3         | 4.05%   |
| 40      | 2         | 2.7%    |
| 27      | 2         | 2.7%    |
| 23      | 2         | 2.7%    |
| 84      | 1         | 1.35%   |
| 60      | 1         | 1.35%   |
| 31      | 1         | 1.35%   |
| 24      | 1         | 1.35%   |
| 21      | 1         | 1.35%   |
| 10      | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 62.16%  |
| 201-300     | 11        | 14.86%  |
| 351-400     | 5         | 6.76%   |
| 501-600     | 4         | 5.41%   |
| 801-900     | 2         | 2.7%    |
| 401-500     | 2         | 2.7%    |
| 601-700     | 1         | 1.35%   |
| 1501-2000   | 1         | 1.35%   |
| 1001-1500   | 1         | 1.35%   |
| Unknown     | 1         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 83.08%  |
| 16/10 | 10        | 15.38%  |
| 3/2   | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 43.24%  |
| 81-90          | 18        | 24.32%  |
| 71-80          | 4         | 5.41%   |
| 201-250        | 4         | 5.41%   |
| 121-130        | 4         | 5.41%   |
| 51-60          | 3         | 4.05%   |
| More than 1000 | 2         | 2.7%    |
| 301-350        | 2         | 2.7%    |
| 501-1000       | 2         | 2.7%    |
| 351-500        | 1         | 1.35%   |
| 41-50          | 1         | 1.35%   |
| Unknown        | 1         | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 43.24%  |
| 101-120       | 20        | 27.03%  |
| 161-240       | 8         | 10.81%  |
| 51-100        | 7         | 9.46%   |
| More than 240 | 3         | 4.05%   |
| 1-50          | 3         | 4.05%   |
| Unknown       | 1         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 54        | 81.82%  |
| 2     | 11        | 16.67%  |
| 0     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 34.31%  |
| Intel                 | 35        | 34.31%  |
| Qualcomm Atheros      | 11        | 10.78%  |
| Broadcom              | 7         | 6.86%   |
| MediaTek              | 3         | 2.94%   |
| ASIX Electronics      | 3         | 2.94%   |
| Hewlett-Packard       | 2         | 1.96%   |
| TP-Link               | 1         | 0.98%   |
| Nvidia                | 1         | 0.98%   |
| JMicron Technology    | 1         | 0.98%   |
| Huawei Technologies   | 1         | 0.98%   |
| Fibocom               | 1         | 0.98%   |
| Broadcom Limited      | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 18        | 14.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 5.79%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 4.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 4.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.31%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.31%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.48%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 2.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.48%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.65%   |
| Intel Wireless 8260                                                     | 2         | 1.65%   |
| Intel Wireless 7265                                                     | 2         | 1.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.83%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.83%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Intel Wireless 7260                                                     | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 50.75%  |
| Realtek Semiconductor | 11        | 16.42%  |
| Qualcomm Atheros      | 9         | 13.43%  |
| Broadcom              | 7         | 10.45%  |
| MediaTek              | 3         | 4.48%   |
| TP-Link               | 1         | 1.49%   |
| Hewlett-Packard       | 1         | 1.49%   |
| Fibocom               | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 6         | 8.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.97%   |
| Intel Wireless 8265 / 8275                                              | 4         | 5.97%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 5.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 5.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 4.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.99%   |
| Intel Wireless 8260                                                     | 2         | 2.99%   |
| Intel Wireless 7265                                                     | 2         | 2.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.99%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.49%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.49%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.49%   |
| Intel Wireless 7260                                                     | 1         | 1.49%   |
| Intel Wireless 3165                                                     | 1         | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.49%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.49%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.49%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.49%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.49%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 1.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 61.54%  |
| Intel                 | 9         | 17.31%  |
| ASIX Electronics      | 3         | 5.77%   |
| Qualcomm Atheros      | 2         | 3.85%   |
| Broadcom              | 2         | 3.85%   |
| Nvidia                | 1         | 1.92%   |
| JMicron Technology    | 1         | 1.92%   |
| Hewlett-Packard       | 1         | 1.92%   |
| Broadcom Limited      | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 33.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 13.21%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 9.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 5.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.89%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.89%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.89%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 55.26%  |
| Ethernet | 50        | 43.86%  |
| Modem    | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 83.58%  |
| Ethernet | 11        | 16.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 66.15%  |
| 1     | 18        | 27.69%  |
| 0     | 4         | 6.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 64.18%  |
| Yes  | 24        | 35.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 55.36%  |
| Realtek Semiconductor           | 5         | 8.93%   |
| Qualcomm Atheros Communications | 5         | 8.93%   |
| Broadcom                        | 4         | 7.14%   |
| Apple                           | 3         | 5.36%   |
| IMC Networks                    | 2         | 3.57%   |
| Dell                            | 2         | 3.57%   |
| Smart Modular Technologies      | 1         | 1.79%   |
| Realtek                         | 1         | 1.79%   |
| MediaTek                        | 1         | 1.79%   |
| Foxconn International           | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 11        | 19.64%  |
| Intel AX201 Bluetooth                              | 11        | 19.64%  |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 8.93%   |
| Realtek Bluetooth Radio                            | 4         | 7.14%   |
| Intel AX200 Bluetooth                              | 4         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.57%   |
| Dell DW375 Bluetooth Module                        | 2         | 3.57%   |
| Apple Bluetooth Host Controller                    | 2         | 3.57%   |
| Smart Modular Bluetooth Device                     | 1         | 1.79%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.79%   |
| Realtek Bluetooth Radio                            | 1         | 1.79%   |
| MediaTek Wireless_Device                           | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.79%   |
| Intel AX210 Bluetooth                              | 1         | 1.79%   |
| IMC Networks Wireless_Device                       | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.79%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.79%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.79%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller                | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 52        | 73.24%  |
| AMD                  | 9         | 12.68%  |
| Nvidia               | 7         | 9.86%   |
| Plantronics          | 1         | 1.41%   |
| Logitech             | 1         | 1.41%   |
| LINE TECH INDUSTRIAL | 1         | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 12.79%  |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 9.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 8.14%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 6.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.49%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.49%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.33%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.33%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.16%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.16%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 1.16%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 1.16%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.16%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 33.33%  |
| SK hynix            | 12        | 26.67%  |
| Kingston            | 5         | 11.11%  |
| Micron Technology   | 3         | 6.67%   |
| Unknown (ABCD)      | 2         | 4.44%   |
| Ramaxel Technology  | 2         | 4.44%   |
| Elpida              | 2         | 4.44%   |
| Unknown             | 1         | 2.22%   |
| Teikon              | 1         | 2.22%   |
| fef5                | 1         | 2.22%   |
| 8945000080AD        | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 4.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 4.26%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 4.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 4.26%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 4.26%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 2.13%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.13%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 2.13%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.13%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 2.13%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 2.13%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.13%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.13%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.13%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 2.13%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 2.13%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.13%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Micron RAM 16JSS51264HY-1G1A1 4GB SODIMM DDR3 1067MT/s           | 1         | 2.13%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 2.13%   |
| Kingston RAM 9905703-008.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.13%   |
| Kingston RAM 9905700-084.A00G 16GB SODIMM DDR4 3200MT/s          | 1         | 2.13%   |
| Kingston RAM 9905624-059.A00G 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 61.11%  |
| DDR3    | 9         | 25%     |
| LPDDR4  | 4         | 11.11%  |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 88.89%  |
| Row Of Chips | 2         | 5.56%   |
| Chip         | 1         | 2.78%   |
| Unknown      | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 45.95%  |
| 4096  | 8         | 21.62%  |
| 16384 | 7         | 18.92%  |
| 32768 | 2         | 5.41%   |
| 2048  | 2         | 5.41%   |
| 1024  | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 28.21%  |
| 2667  | 8         | 20.51%  |
| 2400  | 6         | 15.38%  |
| 1600  | 6         | 15.38%  |
| 1334  | 2         | 5.13%   |
| 4267  | 1         | 2.56%   |
| 3266  | 1         | 2.56%   |
| 2133  | 1         | 2.56%   |
| 1333  | 1         | 2.56%   |
| 1067  | 1         | 2.56%   |
| 1066  | 1         | 2.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1320 | 1         | 50%     |
| Canon LiDE 400   | 1         | 50%     |

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
| Chicony Electronics                    | 16        | 28.57%  |
| IMC Networks                           | 8         | 14.29%  |
| Realtek Semiconductor                  | 6         | 10.71%  |
| Bison Electronics                      | 4         | 7.14%   |
| Syntek                                 | 3         | 5.36%   |
| Sunplus Innovation Technology          | 3         | 5.36%   |
| Microdia                               | 3         | 5.36%   |
| Luxvisions Innotech Limited            | 3         | 5.36%   |
| Apple                                  | 3         | 5.36%   |
| Samsung Electronics                    | 1         | 1.79%   |
| Quanta                                 | 1         | 1.79%   |
| Polycom                                | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.79%   |
| Alcor Micro                            | 1         | 1.79%   |
| Acer                                   | 1         | 1.79%   |
| Unknown                                | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 5.36%   |
| IMC Networks Integrated Camera                                             | 3         | 5.36%   |
| Bison SunplusIT Integrated Camera                                          | 3         | 5.36%   |
| Syntek Integrated Camera                                                   | 2         | 3.57%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.57%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.57%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 3.57%   |
| Chicony USB2.0 Camera                                                      | 2         | 3.57%   |
| Chicony Integrated Camera                                                  | 2         | 3.57%   |
| Chicony HP HD Camera                                                       | 2         | 3.57%   |
| Chicony HD Webcam                                                          | 2         | 3.57%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.57%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.79%   |
| Sunplus HD WebCam                                                          | 1         | 1.79%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 1.79%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.79%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.79%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.79%   |
| Realtek Integrated Webcam                                                  | 1         | 1.79%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.79%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.79%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.79%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.79%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.79%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.79%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.79%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.79%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.79%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.79%   |
| Bison EasyCamera                                                           | 1         | 1.79%   |
| Apple Built-in iSight                                                      | 1         | 1.79%   |
| Alcor Micro SHUNCCM2MP                                                     | 1         | 1.79%   |
| Acer Integrated Camera                                                     | 1         | 1.79%   |
| Unknown                                                                    | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 38.46%  |
| Shenzhen Goodix Technology | 4         | 30.77%  |
| Validity Sensors           | 3         | 23.08%  |
| Elan Microelectronics      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 15.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 15.38%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 15.38%  |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 7.69%   |
| Shenzhen Goodix FingerPrint                               | 1         | 7.69%   |
| Elan ELAN:Fingerprint                                     | 1         | 7.69%   |
| Unknown                                                   | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 63.08%  |
| 1     | 17        | 26.15%  |
| 2     | 5         | 7.69%   |
| 6     | 1         | 1.54%   |
| 3     | 1         | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 37.5%   |
| Net/wireless             | 4         | 12.5%   |
| Chipcard                 | 4         | 12.5%   |
| Graphics card            | 3         | 9.38%   |
| Communication controller | 3         | 9.38%   |
| Sound                    | 2         | 6.25%   |
| Camera                   | 2         | 6.25%   |
| Multimedia controller    | 1         | 3.13%   |
| Bluetooth                | 1         | 3.13%   |


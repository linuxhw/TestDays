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

Total: 98

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
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
| 5.15.0-27-generic     | 7         | 8.97%   |
| 5.15.0-50-generic     | 5         | 6.41%   |
| 5.15.0-48-generic     | 5         | 6.41%   |
| 5.15.0-52-generic     | 4         | 5.13%   |
| 5.19.0-41-generic     | 3         | 3.85%   |
| 5.19.0-35-generic     | 3         | 3.85%   |
| 5.15.0-53-generic     | 3         | 3.85%   |
| 5.15.0-40-generic     | 3         | 3.85%   |
| 5.15.0-39-generic     | 3         | 3.85%   |
| 5.15.0-30-generic     | 3         | 3.85%   |
| 6.2.0-10007-tuxedo    | 2         | 2.56%   |
| 5.19.0-42-generic     | 2         | 2.56%   |
| 5.19.0-38-generic     | 2         | 2.56%   |
| 5.15.0-67-generic     | 2         | 2.56%   |
| 5.15.0-58-generic     | 2         | 2.56%   |
| 5.15.0-56-generic     | 2         | 2.56%   |
| 5.15.0-47-generic     | 2         | 2.56%   |
| 5.15.0-46-generic     | 2         | 2.56%   |
| 5.15.0-33-generic     | 2         | 2.56%   |
| 5.15.0-25-generic     | 2         | 2.56%   |
| 6.3.1-060301-generic  | 1         | 1.28%   |
| 6.1.0-060100-generic  | 1         | 1.28%   |
| 5.19.0-40-generic     | 1         | 1.28%   |
| 5.19.0-051900-generic | 1         | 1.28%   |
| 5.15.0-69-generic     | 1         | 1.28%   |
| 5.15.0-60-generic     | 1         | 1.28%   |
| 5.15.0-57-generic     | 1         | 1.28%   |
| 5.15.0-52-lowlatency  | 1         | 1.28%   |
| 5.15.0-43-generic     | 1         | 1.28%   |
| 5.15.0-41-generic     | 1         | 1.28%   |
| 5.15.0-35-generic     | 1         | 1.28%   |
| 5.15.0-18-generic     | 1         | 1.28%   |
| 5.15.0-10058-tuxedo   | 1         | 1.28%   |
| 5.15.0-10056-tuxedo   | 1         | 1.28%   |
| 5.15.0-10052-tuxedo   | 1         | 1.28%   |
| 5.15.0-10047-tuxedo   | 1         | 1.28%   |
| 5.15.0-10041-tuxedo   | 1         | 1.28%   |
| 5.13.0-35-generic     | 1         | 1.28%   |
| 5.13.0-19-generic     | 1         | 1.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 57        | 77.03%  |
| 5.19.0  | 11        | 14.86%  |
| 6.2.0   | 2         | 2.7%    |
| 5.13.0  | 2         | 2.7%    |
| 6.3.1   | 1         | 1.35%   |
| 6.1.0   | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 57        | 77.03%  |
| 5.19    | 11        | 14.86%  |
| 6.2     | 2         | 2.7%    |
| 5.13    | 2         | 2.7%    |
| 6.3     | 1         | 1.35%   |
| 6.1     | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 71        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 67        | 94.37%  |
| GNOME  | 4         | 5.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 69        | 97.18%  |
| Wayland | 2         | 2.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 51        | 71.83%  |
| Unknown | 12        | 16.9%   |
| GDM3    | 8         | 11.27%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 23        | 32.39%  |
| de_DE | 9         | 12.68%  |
| fr_FR | 8         | 11.27%  |
| pt_BR | 5         | 7.04%   |
| en_GB | 4         | 5.63%   |
| it_IT | 3         | 4.23%   |
| ru_RU | 2         | 2.82%   |
| hu_HU | 2         | 2.82%   |
| fr_BE | 2         | 2.82%   |
| en_IE | 2         | 2.82%   |
| en_CA | 2         | 2.82%   |
| pl_PL | 1         | 1.41%   |
| mt_MT | 1         | 1.41%   |
| ja_JP | 1         | 1.41%   |
| es_PE | 1         | 1.41%   |
| es_MX | 1         | 1.41%   |
| es_EC | 1         | 1.41%   |
| es_CL | 1         | 1.41%   |
| cs_CZ | 1         | 1.41%   |
| C     | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 42        | 59.15%  |
| EFI  | 29        | 40.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 89.04%  |
| Tmpfs   | 3         | 4.11%   |
| Overlay | 2         | 2.74%   |
| Zfs     | 1         | 1.37%   |
| Xfs     | 1         | 1.37%   |
| Btrfs   | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 46        | 64.79%  |
| Unknown | 21        | 29.58%  |
| MBR     | 4         | 5.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 84.51%  |
| Yes       | 11        | 15.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 72.22%  |
| Yes       | 20        | 27.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 22.54%  |
| Dell                   | 12        | 16.9%   |
| ASUSTek Computer       | 10        | 14.08%  |
| Hewlett-Packard        | 9         | 12.68%  |
| TUXEDO                 | 7         | 9.86%   |
| Apple                  | 4         | 5.63%   |
| MSI                    | 3         | 4.23%   |
| Google                 | 2         | 2.82%   |
| Toshiba                | 1         | 1.41%   |
| Timi                   | 1         | 1.41%   |
| Razer                  | 1         | 1.41%   |
| Digibras               | 1         | 1.41%   |
| Chuwi                  | 1         | 1.41%   |
| AXIOO                  | 1         | 1.41%   |
| Avell High Performance | 1         | 1.41%   |
| Acer                   | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.41%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.41%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.41%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.41%   |
| TUXEDO Book XP1511                                   | 1         | 1.41%   |
| TUXEDO Book BA1510                                   | 1         | 1.41%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.41%   |
| Toshiba Satellite A505                               | 1         | 1.41%   |
| Timi TM1604                                          | 1         | 1.41%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.41%   |
| MSI Modern 15 A10M                                   | 1         | 1.41%   |
| MSI GL62 6QF                                         | 1         | 1.41%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.41%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.41%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.41%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.41%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.41%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.41%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.41%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.41%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.41%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.41%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.41%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.41%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.41%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.41%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.41%   |
| Lenovo G500 20236                                    | 1         | 1.41%   |
| Lenovo G50-45 80E3                                   | 1         | 1.41%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.41%   |
| HP ProBook 450 G7                                    | 1         | 1.41%   |
| HP ProBook 445 G7                                    | 1         | 1.41%   |
| HP Pavilion g6                                       | 1         | 1.41%   |
| HP ENVY 17                                           | 1         | 1.41%   |
| HP ElitePad 1000 G2                                  | 1         | 1.41%   |
| HP EliteBook Folio 1040 G3                           | 1         | 1.41%   |
| HP EliteBook 840 G3                                  | 1         | 1.41%   |
| HP Bloog                                             | 1         | 1.41%   |
| Google Rabbid                                        | 1         | 1.41%   |
| Google Boten                                         | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 7         | 9.86%   |
| Lenovo IdeaPad              | 5         | 7.04%   |
| Dell Latitude               | 4         | 5.63%   |
| Dell Inspiron               | 4         | 5.63%   |
| TUXEDO Book                 | 3         | 4.23%   |
| HP ProBook                  | 3         | 4.23%   |
| ASUS VivoBook               | 3         | 4.23%   |
| TUXEDO InfinityBook         | 2         | 2.82%   |
| HP EliteBook                | 2         | 2.82%   |
| Dell XPS                    | 2         | 2.82%   |
| TUXEDO Polaris              | 1         | 1.41%   |
| TUXEDO Aura                 | 1         | 1.41%   |
| Toshiba Satellite           | 1         | 1.41%   |
| Timi TM1604                 | 1         | 1.41%   |
| Razer Blade                 | 1         | 1.41%   |
| MSI Modern                  | 1         | 1.41%   |
| MSI GL62                    | 1         | 1.41%   |
| MSI Alpha                   | 1         | 1.41%   |
| Lenovo V15                  | 1         | 1.41%   |
| Lenovo Legion               | 1         | 1.41%   |
| Lenovo G500                 | 1         | 1.41%   |
| Lenovo G50-45               | 1         | 1.41%   |
| HP Pavilion                 | 1         | 1.41%   |
| HP ENVY                     | 1         | 1.41%   |
| HP ElitePad                 | 1         | 1.41%   |
| HP Bloog                    | 1         | 1.41%   |
| Google Rabbid               | 1         | 1.41%   |
| Google Boten                | 1         | 1.41%   |
| Digibras NH4CU03            | 1         | 1.41%   |
| Dell Vostro                 | 1         | 1.41%   |
| Dell Precision              | 1         | 1.41%   |
| Chuwi HeroBook              | 1         | 1.41%   |
| AXIOO Slimbook              | 1         | 1.41%   |
| Avell High Performance B.ON | 1         | 1.41%   |
| ASUS ZenBook                | 1         | 1.41%   |
| ASUS X555LAB                | 1         | 1.41%   |
| ASUS X205TA                 | 1         | 1.41%   |
| ASUS UX303UA                | 1         | 1.41%   |
| ASUS T200TAC                | 1         | 1.41%   |
| ASUS K52F                   | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 19.72%  |
| 2020 | 12        | 16.9%   |
| 2019 | 6         | 8.45%   |
| 2018 | 6         | 8.45%   |
| 2014 | 6         | 8.45%   |
| 2016 | 4         | 5.63%   |
| 2013 | 4         | 5.63%   |
| 2017 | 3         | 4.23%   |
| 2015 | 3         | 4.23%   |
| 2011 | 3         | 4.23%   |
| 2009 | 3         | 4.23%   |
| 2022 | 2         | 2.82%   |
| 2012 | 2         | 2.82%   |
| 2010 | 2         | 2.82%   |
| 2008 | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 71        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 65        | 91.55%  |
| Enabled  | 6         | 8.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 95.77%  |
| Yes  | 3         | 4.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 33.33%  |
| 16.01-24.0  | 19        | 26.39%  |
| 3.01-4.0    | 10        | 13.89%  |
| 8.01-16.0   | 8         | 11.11%  |
| 32.01-64.0  | 7         | 9.72%   |
| 64.01-256.0 | 3         | 4.17%   |
| 1.01-2.0    | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 32%     |
| 1.01-2.0   | 19        | 25.33%  |
| 4.01-8.0   | 16        | 21.33%  |
| 3.01-4.0   | 8         | 10.67%  |
| 8.01-16.0  | 5         | 6.67%   |
| 24.01-32.0 | 2         | 2.67%   |
| 16.01-24.0 | 1         | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 75.34%  |
| 2      | 16        | 21.92%  |
| 3      | 2         | 2.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 83.1%   |
| Yes       | 12        | 16.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 75%     |
| No        | 18        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 97.18%  |
| No        | 2         | 2.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 87.32%  |
| No        | 9         | 12.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 11        | 15.49%  |
| Germany            | 10        | 14.08%  |
| France             | 8         | 11.27%  |
| Brazil             | 5         | 7.04%   |
| Poland             | 3         | 4.23%   |
| Italy              | 3         | 4.23%   |
| UK                 | 2         | 2.82%   |
| Ireland            | 2         | 2.82%   |
| Hungary            | 2         | 2.82%   |
| Canada             | 2         | 2.82%   |
| Belgium            | 2         | 2.82%   |
| Austria            | 2         | 2.82%   |
| Sweden             | 1         | 1.41%   |
| Slovenia           | 1         | 1.41%   |
| Russia             | 1         | 1.41%   |
| Romania            | 1         | 1.41%   |
| Peru               | 1         | 1.41%   |
| Mexico             | 1         | 1.41%   |
| Malta              | 1         | 1.41%   |
| Japan              | 1         | 1.41%   |
| Indonesia          | 1         | 1.41%   |
| Greece             | 1         | 1.41%   |
| Ghana              | 1         | 1.41%   |
| Ecuador            | 1         | 1.41%   |
| Dominican Republic | 1         | 1.41%   |
| Czechia            | 1         | 1.41%   |
| Chile              | 1         | 1.41%   |
| Cabo Verde         | 1         | 1.41%   |
| Bulgaria           | 1         | 1.41%   |
| Belarus            | 1         | 1.41%   |
| Algeria            | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 2.74%   |
| Vienna                | 2         | 2.74%   |
| Dublin                | 2         | 2.74%   |
| Budapest              | 2         | 2.74%   |
| Berlin                | 2         | 2.74%   |
| Wertheim am Main      | 1         | 1.37%   |
| Weisswasser           | 1         | 1.37%   |
| Weilheim              | 1         | 1.37%   |
| Washington            | 1         | 1.37%   |
| Victoria              | 1         | 1.37%   |
| Torun                 | 1         | 1.37%   |
| Targu Frumos          | 1         | 1.37%   |
| Tarakan               | 1         | 1.37%   |
| Sunnyvale             | 1         | 1.37%   |
| St Petersburg         | 1         | 1.37%   |
| Sofia                 | 1         | 1.37%   |
| Siegen                | 1         | 1.37%   |
| Shirakuni             | 1         | 1.37%   |
| Sétif                | 1         | 1.37%   |
| Seelze                | 1         | 1.37%   |
| Sao Paulo             | 1         | 1.37%   |
| Sao Bernardo do Campo | 1         | 1.37%   |
| Santo Domingo Este    | 1         | 1.37%   |
| Santiago              | 1         | 1.37%   |
| Saint-Gilles          | 1         | 1.37%   |
| Renton                | 1         | 1.37%   |
| Recife                | 1         | 1.37%   |
| Queens                | 1         | 1.37%   |
| Quedlinburg           | 1         | 1.37%   |
| Puebla City           | 1         | 1.37%   |
| Praia                 | 1         | 1.37%   |
| Postojna              | 1         | 1.37%   |
| Ostrava               | 1         | 1.37%   |
| Orvault               | 1         | 1.37%   |
| Nuremberg             | 1         | 1.37%   |
| Monza                 | 1         | 1.37%   |
| Montesilvano Marina   | 1         | 1.37%   |
| Mishawaka             | 1         | 1.37%   |
| Massaranduba          | 1         | 1.37%   |
| Lund                  | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 21        | 24     | 23.86%  |
| Unknown                        | 8         | 8      | 9.09%   |
| Toshiba                        | 8         | 11     | 9.09%   |
| Crucial                        | 6         | 8      | 6.82%   |
| WDC                            | 5         | 6      | 5.68%   |
| Seagate                        | 5         | 5      | 5.68%   |
| Micron Technology              | 5         | 5      | 5.68%   |
| SK hynix                       | 4         | 4      | 4.55%   |
| Intel                          | 3         | 3      | 3.41%   |
| Kingston                       | 2         | 2      | 2.27%   |
| JMicron Technology             | 2         | 2      | 2.27%   |
| China                          | 2         | 3      | 2.27%   |
| Apple                          | 2         | 2      | 2.27%   |
| VISIPRO                        | 1         | 1      | 1.14%   |
| Union Memory                   | 1         | 1      | 1.14%   |
| TO Exter                       | 1         | 1      | 1.14%   |
| SPCC                           | 1         | 1      | 1.14%   |
| Solid State Storage Technology | 1         | 1      | 1.14%   |
| SanDisk                        | 1         | 1      | 1.14%   |
| Realtek Semiconductor          | 1         | 1      | 1.14%   |
| Phison Electronics             | 1         | 1      | 1.14%   |
| OWC                            | 1         | 1      | 1.14%   |
| Netac                          | 1         | 1      | 1.14%   |
| KIOXIA                         | 1         | 1      | 1.14%   |
| Hewlett-Packard                | 1         | 1      | 1.14%   |
| Corsair                        | 1         | 2      | 1.14%   |
| A-DATA Technology              | 1         | 1      | 1.14%   |
| Unknown                        | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 3.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2.25%   |
| Unknown SD64G  64GB                                 | 2         | 2.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2.25%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 2.25%   |
| Samsung SSD 980 500GB                               | 2         | 2.25%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 2.25%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 2.25%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 2.25%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1.12%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.12%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 1.12%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.12%   |
| VISIPRO SSD 256GB                                   | 1         | 1.12%   |
| Unknown SL128  128GB                                | 1         | 1.12%   |
| Unknown SA16G  16GB                                 | 1         | 1.12%   |
| Unknown NCard  4GB                                  | 1         | 1.12%   |
| Unknown MMC128  128GB                               | 1         | 1.12%   |
| Unknown MMC Card  64GB                              | 1         | 1.12%   |
| Unknown MMC Card  128GB                             | 1         | 1.12%   |
| Union Memory RTOTJ128VGD2EYX 128GB                  | 1         | 1.12%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 1.12%   |
| Toshiba TR150 480GB SSD                             | 1         | 1.12%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.12%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.12%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1.12%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.12%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.12%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.12%   |
| TO Exter nal USB 3.0 1TB                            | 1         | 1.12%   |
| SPCC Solid State Disk 120GB                         | 1         | 1.12%   |
| Solid State Storage NVMe CA6-8D1024 1TB             | 1         | 1.12%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.12%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB             | 1         | 1.12%   |
| SK hynix HCG8e  64GB                                | 1         | 1.12%   |
| SK hynix HBG4e  32GB                                | 1         | 1.12%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.12%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.12%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1.12%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD                 | 1         | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 41.67%  |
| WDC                 | 3         | 3      | 25%     |
| Toshiba             | 3         | 3      | 25%     |
| Samsung Electronics | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 21.88%  |
| Crucial             | 6         | 8      | 18.75%  |
| Micron Technology   | 3         | 3      | 9.38%   |
| China               | 2         | 3      | 6.25%   |
| Apple               | 2         | 2      | 6.25%   |
| VISIPRO             | 1         | 1      | 3.13%   |
| Union Memory        | 1         | 1      | 3.13%   |
| Toshiba             | 1         | 1      | 3.13%   |
| TO Exter            | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| OWC                 | 1         | 1      | 3.13%   |
| Netac               | 1         | 1      | 3.13%   |
| JMicron Technology  | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Corsair             | 1         | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 32        | 38     | 39.02%  |
| SSD     | 28        | 37     | 34.15%  |
| HDD     | 12        | 12     | 14.63%  |
| MMC     | 9         | 11     | 10.98%  |
| Unknown | 1         | 1      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 47     | 46.25%  |
| NVMe | 32        | 38     | 40%     |
| MMC  | 9         | 11     | 11.25%  |
| SAS  | 2         | 3      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 33     | 65.12%  |
| 0.51-1.0   | 12        | 13     | 27.91%  |
| 1.01-2.0   | 3         | 3      | 6.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 36.62%  |
| 101-250        | 22        | 30.99%  |
| 501-1000       | 7         | 9.86%   |
| 51-100         | 6         | 8.45%   |
| 1001-2000      | 4         | 5.63%   |
| 21-50          | 3         | 4.23%   |
| 1-20           | 2         | 2.82%   |
| More than 3000 | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 19        | 26.03%  |
| 1-20      | 19        | 26.03%  |
| 101-250   | 15        | 20.55%  |
| 51-100    | 10        | 13.7%   |
| 251-500   | 6         | 8.22%   |
| 1001-2000 | 2         | 2.74%   |
| 501-1000  | 2         | 2.74%   |

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
| Detected | 44        | 56     | 59.46%  |
| Works    | 29        | 42     | 39.19%  |
| Malfunc  | 1         | 1      | 1.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 45        | 53.57%  |
| Samsung Electronics            | 13        | 15.48%  |
| AMD                            | 6         | 7.14%   |
| Toshiba America Info Systems   | 3         | 3.57%   |
| SanDisk                        | 3         | 3.57%   |
| SK hynix                       | 2         | 2.38%   |
| Micron Technology              | 2         | 2.38%   |
| KIOXIA                         | 2         | 2.38%   |
| Kingston Technology Company    | 2         | 2.38%   |
| Solid State Storage Technology | 1         | 1.19%   |
| Realtek Semiconductor          | 1         | 1.19%   |
| Phison Electronics             | 1         | 1.19%   |
| Nvidia                         | 1         | 1.19%   |
| Marvell Technology Group       | 1         | 1.19%   |
| ADATA Technology               | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 7.95%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 6.82%   |
| Samsung NVMe SSD Controller 980                                              | 5         | 5.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 4         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 4.55%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 3.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 3.41%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 3.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 3.41%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.14%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.14%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.14%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.14%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.14%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 1.14%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.14%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.14%   |
| Realtek NVMe Controller                                                      | 1         | 1.14%   |
| Phison NVMe Storage Controller                                               | 1         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.14%   |
| Micron NVMe Storage Controller                                               | 1         | 1.14%   |
| Micron NVMe Controller                                                       | 1         | 1.14%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1.14%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.14%   |
| Kingston Company NVMe Controller                                             | 1         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 1.14%   |
| Intel SSD 660P Series                                                        | 1         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 55.81%  |
| NVMe | 32        | 37.21%  |
| RAID | 5         | 5.81%   |
| IDE  | 1         | 1.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 87.32%  |
| AMD    | 9         | 12.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 5.63%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.82%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.82%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.82%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.82%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.41%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.41%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.41%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.41%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.41%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.41%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 1         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.41%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 23.94%  |
| Intel Core i7        | 14        | 19.72%  |
| Other                | 12        | 16.9%   |
| Intel Core i3        | 5         | 7.04%   |
| Intel Celeron        | 4         | 5.63%   |
| AMD Ryzen 5          | 4         | 5.63%   |
| Intel Atom           | 3         | 4.23%   |
| AMD Ryzen 7          | 3         | 4.23%   |
| Intel Pentium Silver | 2         | 2.82%   |
| Intel Pentium        | 2         | 2.82%   |
| Intel Core 2 Duo     | 2         | 2.82%   |
| Intel Core i9        | 1         | 1.41%   |
| AMD Ryzen 3          | 1         | 1.41%   |
| AMD A8               | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 31        | 43.66%  |
| 2      | 27        | 38.03%  |
| 8      | 7         | 9.86%   |
| 6      | 4         | 5.63%   |
| 10     | 2         | 2.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 54        | 76.06%  |
| 1      | 17        | 23.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 57.53%  |
| 0x806ec    | 3         | 4.11%   |
| 0x806c1    | 3         | 4.11%   |
| 0x706a8    | 3         | 4.11%   |
| 0x206a7    | 3         | 4.11%   |
| 0x08600106 | 3         | 4.11%   |
| 0x806d1    | 2         | 2.74%   |
| 0x20655    | 2         | 2.74%   |
| 0x08108102 | 2         | 2.74%   |
| 0x906ea    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x806ea    | 1         | 1.37%   |
| 0x506c9    | 1         | 1.37%   |
| 0x40651    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x30678    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x0a50000c | 1         | 1.37%   |
| 0x07030104 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 21.13%  |
| TigerLake     | 7         | 9.86%   |
| Skylake       | 5         | 7.04%   |
| Unknown       | 5         | 7.04%   |
| IvyBridge     | 4         | 5.63%   |
| Goldmont plus | 4         | 5.63%   |
| Zen 2         | 3         | 4.23%   |
| Silvermont    | 3         | 4.23%   |
| SandyBridge   | 3         | 4.23%   |
| IceLake       | 3         | 4.23%   |
| Haswell       | 3         | 4.23%   |
| Broadwell     | 3         | 4.23%   |
| Zen+          | 2         | 2.82%   |
| Zen 3         | 2         | 2.82%   |
| Westmere      | 2         | 2.82%   |
| Penryn        | 2         | 2.82%   |
| CometLake     | 2         | 2.82%   |
| Puma          | 1         | 1.41%   |
| Nehalem       | 1         | 1.41%   |
| Goldmont      | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 67.82%  |
| Nvidia | 17        | 19.54%  |
| AMD    | 11        | 12.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 7.87%   |
| Intel UHD Graphics 620                                                    | 5         | 5.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 4.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 4.49%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 4.49%   |
| Intel HD Graphics 5500                                                    | 3         | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 3.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.37%   |
| AMD Renoir                                                                | 3         | 3.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 2.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.25%   |
| Intel HD Graphics 620                                                     | 2         | 2.25%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 2.25%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.25%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.25%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.12%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 1.12%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 1.12%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.12%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 1.12%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.12%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.12%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.12%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.12%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.12%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.12%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.12%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.12%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.12%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.12%   |
| Intel HD Graphics 530                                                     | 1         | 1.12%   |
| Intel HD Graphics 500                                                     | 1         | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 60.56%  |
| Intel + Nvidia | 13        | 18.31%  |
| 1 x AMD        | 6         | 8.45%   |
| 1 x Nvidia     | 3         | 4.23%   |
| 2 x AMD        | 2         | 2.82%   |
| Intel + AMD    | 2         | 2.82%   |
| Other          | 1         | 1.41%   |
| AMD + Nvidia   | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 60        | 84.51%  |
| Proprietary | 10        | 14.08%  |
| Unknown     | 1         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 84.51%  |
| 1.01-2.0   | 4         | 5.63%   |
| 0.01-0.5   | 3         | 4.23%   |
| 7.01-8.0   | 2         | 2.82%   |
| 0.51-1.0   | 2         | 2.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 19        | 22.89%  |
| BOE                     | 17        | 20.48%  |
| Samsung Electronics     | 10        | 12.05%  |
| AU Optronics            | 9         | 10.84%  |
| LG Display              | 7         | 8.43%   |
| Apple                   | 4         | 4.82%   |
| Sharp                   | 3         | 3.61%   |
| Lenovo                  | 2         | 2.41%   |
| Goldstar                | 2         | 2.41%   |
| Unknown (AAA)           | 1         | 1.2%    |
| Philips                 | 1         | 1.2%    |
| MStar                   | 1         | 1.2%    |
| KDC                     | 1         | 1.2%    |
| IBM                     | 1         | 1.2%    |
| HKC                     | 1         | 1.2%    |
| Daewoo                  | 1         | 1.2%    |
| Chi Mei Optoelectronics | 1         | 1.2%    |
| BenQ                    | 1         | 1.2%    |
| AOC                     | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 2.41%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 1.2%    |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 1.2%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 1.2%    |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 1.2%    |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch   | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch  | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 1.2%    |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch               | 1         | 1.2%    |
| MStar LCD TV MST9000 1360x768                                         | 1         | 1.2%    |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD060F 1920x1080 310x170mm 13.9-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.2%    |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                  | 1         | 1.2%    |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch              | 1         | 1.2%    |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                 | 1         | 1.2%    |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 1.2%    |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                  | 1         | 1.2%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 1         | 1.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 1.2%    |
| Daewoo 23.6 monitor DWE0236 1920x1080 521x293mm 23.5-inch             | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 340x190mm 15.3-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 42.67%  |
| 1366x768 (WXGA)    | 20        | 26.67%  |
| 3840x2160 (4K)     | 3         | 4%      |
| 2560x1440 (QHD)    | 3         | 4%      |
| 1920x1200 (WUXGA)  | 3         | 4%      |
| 1600x900 (HD+)     | 3         | 4%      |
| 1280x800 (WXGA)    | 3         | 4%      |
| 1680x1050 (WSXGA+) | 2         | 2.67%   |
| 1440x900 (WXGA+)   | 2         | 2.67%   |
| 3456x2160          | 1         | 1.33%   |
| 2880x1800          | 1         | 1.33%   |
| 2560x1600          | 1         | 1.33%   |
| 1360x768           | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 40.96%  |
| 13      | 17        | 20.48%  |
| 14      | 9         | 10.84%  |
| 17      | 4         | 4.82%   |
| 27      | 3         | 3.61%   |
| 11      | 3         | 3.61%   |
| 40      | 2         | 2.41%   |
| 24      | 2         | 2.41%   |
| 23      | 2         | 2.41%   |
| 21      | 2         | 2.41%   |
| 84      | 1         | 1.2%    |
| 60      | 1         | 1.2%    |
| 31      | 1         | 1.2%    |
| 10      | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 61.45%  |
| 201-300     | 12        | 14.46%  |
| 501-600     | 5         | 6.02%   |
| 351-400     | 5         | 6.02%   |
| 401-500     | 3         | 3.61%   |
| 801-900     | 2         | 2.41%   |
| 601-700     | 2         | 2.41%   |
| 1501-2000   | 1         | 1.2%    |
| 1001-1500   | 1         | 1.2%    |
| Unknown     | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 59        | 81.94%  |
| 16/10 | 12        | 16.67%  |
| 3/2   | 1         | 1.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 40.96%  |
| 81-90          | 22        | 26.51%  |
| 201-250        | 5         | 6.02%   |
| 71-80          | 4         | 4.82%   |
| 121-130        | 4         | 4.82%   |
| 51-60          | 3         | 3.61%   |
| 301-350        | 3         | 3.61%   |
| More than 1000 | 2         | 2.41%   |
| 501-1000       | 2         | 2.41%   |
| 351-500        | 1         | 1.2%    |
| 41-50          | 1         | 1.2%    |
| 151-200        | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 43.37%  |
| 101-120       | 22        | 26.51%  |
| 161-240       | 9         | 10.84%  |
| 51-100        | 8         | 9.64%   |
| More than 240 | 4         | 4.82%   |
| 1-50          | 3         | 3.61%   |
| Unknown       | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 79.17%  |
| 2     | 14        | 19.44%  |
| 0     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 34.82%  |
| Realtek Semiconductor | 38        | 33.93%  |
| Qualcomm Atheros      | 11        | 9.82%   |
| Broadcom              | 7         | 6.25%   |
| MediaTek              | 3         | 2.68%   |
| ASIX Electronics      | 3         | 2.68%   |
| Hewlett-Packard       | 2         | 1.79%   |
| Broadcom Limited      | 2         | 1.79%   |
| Xiaomi                | 1         | 0.89%   |
| TP-Link               | 1         | 0.89%   |
| Nvidia                | 1         | 0.89%   |
| Lenovo                | 1         | 0.89%   |
| JMicron Technology    | 1         | 0.89%   |
| Huawei Technologies   | 1         | 0.89%   |
| Fibocom               | 1         | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 20        | 15.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 5.26%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 3.76%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.76%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.26%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.26%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.5%    |
| Intel Wireless 8260                                                     | 2         | 1.5%    |
| Intel Wireless 7265                                                     | 2         | 1.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.75%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.75%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.75%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.75%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 52.05%  |
| Realtek Semiconductor | 12        | 16.44%  |
| Qualcomm Atheros      | 9         | 12.33%  |
| Broadcom              | 7         | 9.59%   |
| MediaTek              | 3         | 4.11%   |
| TP-Link               | 1         | 1.37%   |
| Hewlett-Packard       | 1         | 1.37%   |
| Fibocom               | 1         | 1.37%   |
| Broadcom Limited      | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 6         | 8.22%   |
| Intel Wireless 8265 / 8275                                              | 5         | 6.85%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 6.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 5.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.74%   |
| Intel Wireless 8260                                                     | 2         | 2.74%   |
| Intel Wireless 7265                                                     | 2         | 2.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.37%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.37%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.37%   |
| Intel Wireless 7260                                                     | 1         | 1.37%   |
| Intel Wireless 3165                                                     | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.37%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.37%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.37%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 1.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 58.62%  |
| Intel                 | 11        | 18.97%  |
| ASIX Electronics      | 3         | 5.17%   |
| Qualcomm Atheros      | 2         | 3.45%   |
| Broadcom              | 2         | 3.45%   |
| Xiaomi                | 1         | 1.72%   |
| Nvidia                | 1         | 1.72%   |
| Lenovo                | 1         | 1.72%   |
| JMicron Technology    | 1         | 1.72%   |
| Hewlett-Packard       | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 33.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 11.86%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 8.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 5.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.69%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.69%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.69%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.69%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.69%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.69%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.69%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 55.65%  |
| Ethernet | 54        | 43.55%  |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 82.19%  |
| Ethernet | 13        | 17.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 66.2%   |
| 1     | 20        | 28.17%  |
| 0     | 4         | 5.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 66.22%  |
| Yes  | 25        | 33.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 56.45%  |
| Realtek Semiconductor           | 6         | 9.68%   |
| Qualcomm Atheros Communications | 5         | 8.06%   |
| Broadcom                        | 4         | 6.45%   |
| Apple                           | 4         | 6.45%   |
| IMC Networks                    | 2         | 3.23%   |
| Dell                            | 2         | 3.23%   |
| Smart Modular Technologies      | 1         | 1.61%   |
| Realtek                         | 1         | 1.61%   |
| MediaTek                        | 1         | 1.61%   |
| Foxconn International           | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 12        | 19.35%  |
| Intel AX201 Bluetooth                              | 11        | 17.74%  |
| Realtek Bluetooth Radio                            | 5         | 8.06%   |
| Intel AX200 Bluetooth                              | 5         | 8.06%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.23%   |
| Intel AX210 Bluetooth                              | 2         | 3.23%   |
| Dell DW375 Bluetooth Module                        | 2         | 3.23%   |
| Apple Bluetooth USB Host Controller                | 2         | 3.23%   |
| Apple Bluetooth Host Controller                    | 2         | 3.23%   |
| Smart Modular Bluetooth Device                     | 1         | 1.61%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.61%   |
| Realtek Bluetooth Radio                            | 1         | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.61%   |
| MediaTek Wireless_Device                           | 1         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.61%   |
| Intel Bluetooth Device                             | 1         | 1.61%   |
| IMC Networks Wireless_Device                       | 1         | 1.61%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.61%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.61%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.61%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 58        | 73.42%  |
| AMD                  | 9         | 11.39%  |
| Nvidia               | 8         | 10.13%  |
| Plantronics          | 1         | 1.27%   |
| Logitech             | 1         | 1.27%   |
| LINE TECH INDUSTRIAL | 1         | 1.27%   |
| DSEA A/S             | 1         | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 11.58%  |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 8.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 7.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 6.32%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 4.21%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 4.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 4.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 3.16%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.16%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.11%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.11%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.05%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.05%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 1.05%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 1.05%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.05%   |
| DSEA A/S EPOS ADAPT 1x5                                                    | 1         | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 34%     |
| SK hynix            | 13        | 26%     |
| Kingston            | 5         | 10%     |
| Micron Technology   | 4         | 8%      |
| Elpida              | 3         | 6%      |
| Unknown (ABCD)      | 2         | 4%      |
| Ramaxel Technology  | 2         | 4%      |
| Unknown             | 1         | 2%      |
| Teikon              | 1         | 2%      |
| fef5                | 1         | 2%      |
| 8945000080AD        | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 5.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.77%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 3.77%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.89%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.89%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.89%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.89%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.89%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.89%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.89%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.89%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.89%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 1.89%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.89%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Micron RAM 16JSS51264HY-1G1A1 4GB SODIMM DDR3 1067MT/s           | 1         | 1.89%   |
| Micron RAM 16ATF4G64HZ-3G2B4 32GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 60.98%  |
| DDR3    | 10        | 24.39%  |
| LPDDR4  | 5         | 12.2%   |
| Unknown | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 87.8%   |
| Row Of Chips | 2         | 4.88%   |
| Unknown      | 2         | 4.88%   |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 40.48%  |
| 16384 | 8         | 19.05%  |
| 4096  | 8         | 19.05%  |
| 32768 | 4         | 9.52%   |
| 2048  | 3         | 7.14%   |
| 1024  | 2         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 31.82%  |
| 2667  | 8         | 18.18%  |
| 2400  | 7         | 15.91%  |
| 1600  | 7         | 15.91%  |
| 1334  | 2         | 4.55%   |
| 4267  | 1         | 2.27%   |
| 3266  | 1         | 2.27%   |
| 2133  | 1         | 2.27%   |
| 1333  | 1         | 2.27%   |
| 1067  | 1         | 2.27%   |
| 1066  | 1         | 2.27%   |

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
| Chicony Electronics                    | 17        | 27.87%  |
| IMC Networks                           | 8         | 13.11%  |
| Realtek Semiconductor                  | 6         | 9.84%   |
| Bison Electronics                      | 5         | 8.2%    |
| Sunplus Innovation Technology          | 4         | 6.56%   |
| Luxvisions Innotech Limited            | 4         | 6.56%   |
| Syntek                                 | 3         | 4.92%   |
| Microdia                               | 3         | 4.92%   |
| Apple                                  | 3         | 4.92%   |
| Quanta                                 | 2         | 3.28%   |
| Samsung Electronics                    | 1         | 1.64%   |
| Polycom                                | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.64%   |
| Alcor Micro                            | 1         | 1.64%   |
| Acer                                   | 1         | 1.64%   |
| Unknown                                | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 4.92%   |
| IMC Networks Integrated Camera                                             | 3         | 4.92%   |
| Chicony USB2.0 Camera                                                      | 3         | 4.92%   |
| Bison SunplusIT Integrated Camera                                          | 3         | 4.92%   |
| Syntek Integrated Camera                                                   | 2         | 3.28%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.28%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.28%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 3.28%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 3.28%   |
| Chicony Integrated Camera                                                  | 2         | 3.28%   |
| Chicony HP HD Camera                                                       | 2         | 3.28%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.28%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.64%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.64%   |
| Sunplus HD WebCam                                                          | 1         | 1.64%   |
| Sunplus FHD Camera Microphone                                              | 1         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 1.64%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.64%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.64%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.64%   |
| Realtek Integrated Webcam                                                  | 1         | 1.64%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.64%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 1.64%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.64%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.64%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.64%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.64%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.64%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.64%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.64%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.64%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.64%   |
| Chicony Integrated IR Camera                                               | 1         | 1.64%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.64%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.64%   |
| Chicony HD Webcam                                                          | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.64%   |
| Bison Integrated Camera                                                    | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 46.67%  |
| Shenzhen Goodix Technology | 4         | 26.67%  |
| Validity Sensors           | 3         | 20%     |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 13.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 13.33%  |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 6.67%   |
| Synaptics UWP WBDI Device                                 | 1         | 6.67%   |
| Synaptics UWP WBDI                                        | 1         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 6.67%   |
| Shenzhen Goodix FingerPrint                               | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                     | 1         | 6.67%   |
| Unknown                                                   | 1         | 6.67%   |

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
| 0     | 44        | 61.11%  |
| 1     | 18        | 25%     |
| 2     | 7         | 9.72%   |
| 3     | 2         | 2.78%   |
| 6     | 1         | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 35.9%   |
| Net/wireless             | 4         | 10.26%  |
| Communication controller | 4         | 10.26%  |
| Chipcard                 | 4         | 10.26%  |
| Graphics card            | 3         | 7.69%   |
| Camera                   | 3         | 7.69%   |
| Sound                    | 2         | 5.13%   |
| Multimedia controller    | 2         | 5.13%   |
| Card reader              | 2         | 5.13%   |
| Bluetooth                | 1         | 2.56%   |


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

Total: 100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| BANGHO        | BES G0304                   | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
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
| 5.15.0-27-generic     | 7         | 8.75%   |
| 5.15.0-50-generic     | 5         | 6.25%   |
| 5.15.0-48-generic     | 5         | 6.25%   |
| 5.15.0-52-generic     | 4         | 5%      |
| 5.19.0-41-generic     | 3         | 3.75%   |
| 5.19.0-35-generic     | 3         | 3.75%   |
| 5.15.0-53-generic     | 3         | 3.75%   |
| 5.15.0-40-generic     | 3         | 3.75%   |
| 5.15.0-39-generic     | 3         | 3.75%   |
| 5.15.0-30-generic     | 3         | 3.75%   |
| 6.2.0-10007-tuxedo    | 2         | 2.5%    |
| 5.19.0-42-generic     | 2         | 2.5%    |
| 5.19.0-38-generic     | 2         | 2.5%    |
| 5.15.0-67-generic     | 2         | 2.5%    |
| 5.15.0-58-generic     | 2         | 2.5%    |
| 5.15.0-56-generic     | 2         | 2.5%    |
| 5.15.0-47-generic     | 2         | 2.5%    |
| 5.15.0-46-generic     | 2         | 2.5%    |
| 5.15.0-33-generic     | 2         | 2.5%    |
| 5.15.0-25-generic     | 2         | 2.5%    |
| 6.3.1-060301-generic  | 1         | 1.25%   |
| 6.1.0-060100-generic  | 1         | 1.25%   |
| 5.19.0-45-generic     | 1         | 1.25%   |
| 5.19.0-40-generic     | 1         | 1.25%   |
| 5.19.0-32-generic     | 1         | 1.25%   |
| 5.19.0-051900-generic | 1         | 1.25%   |
| 5.15.0-69-generic     | 1         | 1.25%   |
| 5.15.0-60-generic     | 1         | 1.25%   |
| 5.15.0-57-generic     | 1         | 1.25%   |
| 5.15.0-52-lowlatency  | 1         | 1.25%   |
| 5.15.0-43-generic     | 1         | 1.25%   |
| 5.15.0-41-generic     | 1         | 1.25%   |
| 5.15.0-35-generic     | 1         | 1.25%   |
| 5.15.0-18-generic     | 1         | 1.25%   |
| 5.15.0-10058-tuxedo   | 1         | 1.25%   |
| 5.15.0-10056-tuxedo   | 1         | 1.25%   |
| 5.15.0-10052-tuxedo   | 1         | 1.25%   |
| 5.15.0-10047-tuxedo   | 1         | 1.25%   |
| 5.15.0-10041-tuxedo   | 1         | 1.25%   |
| 5.13.0-35-generic     | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 57        | 75%     |
| 5.19.0  | 13        | 17.11%  |
| 6.2.0   | 2         | 2.63%   |
| 5.13.0  | 2         | 2.63%   |
| 6.3.1   | 1         | 1.32%   |
| 6.1.0   | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 57        | 75%     |
| 5.19    | 13        | 17.11%  |
| 6.2     | 2         | 2.63%   |
| 5.13    | 2         | 2.63%   |
| 6.3     | 1         | 1.32%   |
| 6.1     | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 73        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 69        | 94.52%  |
| GNOME  | 4         | 5.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 71        | 97.26%  |
| Wayland | 2         | 2.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 53        | 72.6%   |
| Unknown | 12        | 16.44%  |
| GDM3    | 8         | 10.96%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 32.88%  |
| de_DE | 9         | 12.33%  |
| fr_FR | 8         | 10.96%  |
| pt_BR | 5         | 6.85%   |
| en_GB | 4         | 5.48%   |
| it_IT | 3         | 4.11%   |
| ru_RU | 2         | 2.74%   |
| hu_HU | 2         | 2.74%   |
| fr_BE | 2         | 2.74%   |
| en_IE | 2         | 2.74%   |
| en_CA | 2         | 2.74%   |
| pl_PL | 1         | 1.37%   |
| mt_MT | 1         | 1.37%   |
| ja_JP | 1         | 1.37%   |
| es_PE | 1         | 1.37%   |
| es_MX | 1         | 1.37%   |
| es_ES | 1         | 1.37%   |
| es_EC | 1         | 1.37%   |
| es_CL | 1         | 1.37%   |
| cs_CZ | 1         | 1.37%   |
| C     | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 58.9%   |
| EFI  | 30        | 41.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 88%     |
| Tmpfs   | 3         | 4%      |
| Overlay | 3         | 4%      |
| Zfs     | 1         | 1.33%   |
| Xfs     | 1         | 1.33%   |
| Btrfs   | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 47        | 64.38%  |
| Unknown | 21        | 28.77%  |
| MBR     | 5         | 6.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 84.93%  |
| Yes       | 11        | 15.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 70.27%  |
| Yes       | 22        | 29.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 21.92%  |
| Dell                   | 12        | 16.44%  |
| ASUSTek Computer       | 10        | 13.7%   |
| Hewlett-Packard        | 9         | 12.33%  |
| TUXEDO                 | 7         | 9.59%   |
| Apple                  | 4         | 5.48%   |
| MSI                    | 3         | 4.11%   |
| Google                 | 2         | 2.74%   |
| Toshiba                | 1         | 1.37%   |
| Timi                   | 1         | 1.37%   |
| Razer                  | 1         | 1.37%   |
| HUAWEI                 | 1         | 1.37%   |
| Digibras               | 1         | 1.37%   |
| Chuwi                  | 1         | 1.37%   |
| BANGHO                 | 1         | 1.37%   |
| AXIOO                  | 1         | 1.37%   |
| Avell High Performance | 1         | 1.37%   |
| Acer                   | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.37%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.37%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.37%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.37%   |
| TUXEDO Book XP1511                                   | 1         | 1.37%   |
| TUXEDO Book BA1510                                   | 1         | 1.37%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.37%   |
| Toshiba Satellite A505                               | 1         | 1.37%   |
| Timi TM1604                                          | 1         | 1.37%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.37%   |
| MSI Modern 15 A10M                                   | 1         | 1.37%   |
| MSI GL62 6QF                                         | 1         | 1.37%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.37%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.37%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.37%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.37%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.37%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.37%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.37%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.37%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.37%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.37%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.37%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.37%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.37%   |
| Lenovo G500 20236                                    | 1         | 1.37%   |
| Lenovo G50-45 80E3                                   | 1         | 1.37%   |
| HUAWEI HKD-WXX                                       | 1         | 1.37%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.37%   |
| HP ProBook 450 G7                                    | 1         | 1.37%   |
| HP ProBook 445 G7                                    | 1         | 1.37%   |
| HP Pavilion g6                                       | 1         | 1.37%   |
| HP ENVY 17                                           | 1         | 1.37%   |
| HP ElitePad 1000 G2                                  | 1         | 1.37%   |
| HP EliteBook Folio 1040 G3                           | 1         | 1.37%   |
| HP EliteBook 840 G3                                  | 1         | 1.37%   |
| HP Bloog                                             | 1         | 1.37%   |
| Google Rabbid                                        | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 7         | 9.59%   |
| Lenovo IdeaPad              | 5         | 6.85%   |
| Dell Latitude               | 4         | 5.48%   |
| Dell Inspiron               | 4         | 5.48%   |
| TUXEDO Book                 | 3         | 4.11%   |
| HP ProBook                  | 3         | 4.11%   |
| ASUS VivoBook               | 3         | 4.11%   |
| TUXEDO InfinityBook         | 2         | 2.74%   |
| HP EliteBook                | 2         | 2.74%   |
| Dell XPS                    | 2         | 2.74%   |
| TUXEDO Polaris              | 1         | 1.37%   |
| TUXEDO Aura                 | 1         | 1.37%   |
| Toshiba Satellite           | 1         | 1.37%   |
| Timi TM1604                 | 1         | 1.37%   |
| Razer Blade                 | 1         | 1.37%   |
| MSI Modern                  | 1         | 1.37%   |
| MSI GL62                    | 1         | 1.37%   |
| MSI Alpha                   | 1         | 1.37%   |
| Lenovo V15                  | 1         | 1.37%   |
| Lenovo Legion               | 1         | 1.37%   |
| Lenovo G500                 | 1         | 1.37%   |
| Lenovo G50-45               | 1         | 1.37%   |
| HUAWEI HKD-WXX              | 1         | 1.37%   |
| HP Pavilion                 | 1         | 1.37%   |
| HP ENVY                     | 1         | 1.37%   |
| HP ElitePad                 | 1         | 1.37%   |
| HP Bloog                    | 1         | 1.37%   |
| Google Rabbid               | 1         | 1.37%   |
| Google Boten                | 1         | 1.37%   |
| Digibras NH4CU03            | 1         | 1.37%   |
| Dell Vostro                 | 1         | 1.37%   |
| Dell Precision              | 1         | 1.37%   |
| Chuwi HeroBook              | 1         | 1.37%   |
| BANGHO BES                  | 1         | 1.37%   |
| AXIOO Slimbook              | 1         | 1.37%   |
| Avell High Performance B.ON | 1         | 1.37%   |
| ASUS ZenBook                | 1         | 1.37%   |
| ASUS X555LAB                | 1         | 1.37%   |
| ASUS X205TA                 | 1         | 1.37%   |
| ASUS UX303UA                | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 19.18%  |
| 2020 | 12        | 16.44%  |
| 2014 | 7         | 9.59%   |
| 2019 | 6         | 8.22%   |
| 2018 | 6         | 8.22%   |
| 2016 | 4         | 5.48%   |
| 2013 | 4         | 5.48%   |
| 2022 | 3         | 4.11%   |
| 2017 | 3         | 4.11%   |
| 2015 | 3         | 4.11%   |
| 2011 | 3         | 4.11%   |
| 2009 | 3         | 4.11%   |
| 2012 | 2         | 2.74%   |
| 2010 | 2         | 2.74%   |
| 2008 | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 73        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 66        | 90.41%  |
| Enabled  | 7         | 9.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 95.89%  |
| Yes  | 3         | 4.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 33.78%  |
| 16.01-24.0  | 20        | 27.03%  |
| 3.01-4.0    | 10        | 13.51%  |
| 8.01-16.0   | 8         | 10.81%  |
| 32.01-64.0  | 7         | 9.46%   |
| 64.01-256.0 | 3         | 4.05%   |
| 1.01-2.0    | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 31.17%  |
| 1.01-2.0   | 20        | 25.97%  |
| 4.01-8.0   | 16        | 20.78%  |
| 3.01-4.0   | 9         | 11.69%  |
| 8.01-16.0  | 5         | 6.49%   |
| 24.01-32.0 | 2         | 2.6%    |
| 16.01-24.0 | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 76%     |
| 2      | 16        | 21.33%  |
| 3      | 2         | 2.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 83.56%  |
| Yes       | 12        | 16.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 74.32%  |
| No        | 19        | 25.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 97.26%  |
| No        | 2         | 2.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 87.67%  |
| No        | 9         | 12.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 11        | 15.07%  |
| Germany            | 10        | 13.7%   |
| France             | 8         | 10.96%  |
| Brazil             | 5         | 6.85%   |
| Poland             | 3         | 4.11%   |
| Italy              | 3         | 4.11%   |
| UK                 | 2         | 2.74%   |
| Ireland            | 2         | 2.74%   |
| Hungary            | 2         | 2.74%   |
| Canada             | 2         | 2.74%   |
| Belgium            | 2         | 2.74%   |
| Austria            | 2         | 2.74%   |
| Sweden             | 1         | 1.37%   |
| Spain              | 1         | 1.37%   |
| Slovenia           | 1         | 1.37%   |
| Russia             | 1         | 1.37%   |
| Romania            | 1         | 1.37%   |
| Peru               | 1         | 1.37%   |
| Mexico             | 1         | 1.37%   |
| Malta              | 1         | 1.37%   |
| Japan              | 1         | 1.37%   |
| Indonesia          | 1         | 1.37%   |
| Greece             | 1         | 1.37%   |
| Ghana              | 1         | 1.37%   |
| Ecuador            | 1         | 1.37%   |
| Dominican Republic | 1         | 1.37%   |
| Czechia            | 1         | 1.37%   |
| Chile              | 1         | 1.37%   |
| Cabo Verde         | 1         | 1.37%   |
| Bulgaria           | 1         | 1.37%   |
| Belarus            | 1         | 1.37%   |
| Argentina          | 1         | 1.37%   |
| Algeria            | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 2.67%   |
| Vienna                | 2         | 2.67%   |
| Dublin                | 2         | 2.67%   |
| Budapest              | 2         | 2.67%   |
| Berlin                | 2         | 2.67%   |
| Wertheim am Main      | 1         | 1.33%   |
| Weisswasser           | 1         | 1.33%   |
| Weilheim              | 1         | 1.33%   |
| Washington            | 1         | 1.33%   |
| Victoria              | 1         | 1.33%   |
| Torun                 | 1         | 1.33%   |
| Targu Frumos          | 1         | 1.33%   |
| Tarakan               | 1         | 1.33%   |
| Sunnyvale             | 1         | 1.33%   |
| St Petersburg         | 1         | 1.33%   |
| Sofia                 | 1         | 1.33%   |
| Siegen                | 1         | 1.33%   |
| Shirakuni             | 1         | 1.33%   |
| Sétif                | 1         | 1.33%   |
| Seelze                | 1         | 1.33%   |
| Sao Paulo             | 1         | 1.33%   |
| Sao Bernardo do Campo | 1         | 1.33%   |
| Santo Domingo Este    | 1         | 1.33%   |
| Santiago              | 1         | 1.33%   |
| Saint-Gilles          | 1         | 1.33%   |
| Renton                | 1         | 1.33%   |
| Recife                | 1         | 1.33%   |
| Queens                | 1         | 1.33%   |
| Quedlinburg           | 1         | 1.33%   |
| Puebla City           | 1         | 1.33%   |
| Praia                 | 1         | 1.33%   |
| Postojna              | 1         | 1.33%   |
| Ostrava               | 1         | 1.33%   |
| Orvault               | 1         | 1.33%   |
| Nuremberg             | 1         | 1.33%   |
| Monza                 | 1         | 1.33%   |
| Montesilvano Marina   | 1         | 1.33%   |
| Mishawaka             | 1         | 1.33%   |
| Massaranduba          | 1         | 1.33%   |
| Lund                  | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 21        | 24     | 23.33%  |
| Unknown                        | 8         | 8      | 8.89%   |
| Toshiba                        | 8         | 11     | 8.89%   |
| Crucial                        | 6         | 8      | 6.67%   |
| WDC                            | 5         | 6      | 5.56%   |
| Seagate                        | 5         | 5      | 5.56%   |
| Micron Technology              | 5         | 5      | 5.56%   |
| SK hynix                       | 4         | 4      | 4.44%   |
| Kingston                       | 3         | 3      | 3.33%   |
| Intel                          | 3         | 3      | 3.33%   |
| JMicron Technology             | 2         | 2      | 2.22%   |
| China                          | 2         | 3      | 2.22%   |
| Apple                          | 2         | 2      | 2.22%   |
| YMTC                           | 1         | 1      | 1.11%   |
| VISIPRO                        | 1         | 1      | 1.11%   |
| Union Memory                   | 1         | 1      | 1.11%   |
| TO Exter                       | 1         | 1      | 1.11%   |
| SPCC                           | 1         | 1      | 1.11%   |
| Solid State Storage Technology | 1         | 1      | 1.11%   |
| SanDisk                        | 1         | 1      | 1.11%   |
| Realtek Semiconductor          | 1         | 1      | 1.11%   |
| Phison Electronics             | 1         | 1      | 1.11%   |
| OWC                            | 1         | 1      | 1.11%   |
| Netac                          | 1         | 1      | 1.11%   |
| KIOXIA                         | 1         | 1      | 1.11%   |
| Hewlett-Packard                | 1         | 1      | 1.11%   |
| Corsair                        | 1         | 2      | 1.11%   |
| A-DATA Technology              | 1         | 1      | 1.11%   |
| Unknown                        | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 3.3%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2.2%    |
| Unknown SD64G  64GB                                 | 2         | 2.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2.2%    |
| Samsung SSD 980 PRO 2TB                             | 2         | 2.2%    |
| Samsung SSD 980 500GB                               | 2         | 2.2%    |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 2.2%    |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 2.2%    |
| Crucial CT240BX500SSD1 240GB                        | 2         | 2.2%    |
| YMTC PC005 1TB                                      | 1         | 1.1%    |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1.1%    |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.1%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 1.1%    |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.1%    |
| VISIPRO SSD 256GB                                   | 1         | 1.1%    |
| Unknown SL128  128GB                                | 1         | 1.1%    |
| Unknown SA16G  16GB                                 | 1         | 1.1%    |
| Unknown NCard  4GB                                  | 1         | 1.1%    |
| Unknown MMC128  128GB                               | 1         | 1.1%    |
| Unknown MMC Card  64GB                              | 1         | 1.1%    |
| Unknown MMC Card  128GB                             | 1         | 1.1%    |
| Union Memory RTOTJ128VGD2EYX 128GB                  | 1         | 1.1%    |
| Toshiba XG6 NVMe SSD Controller 2TB                 | 1         | 1.1%    |
| Toshiba TR150 480GB SSD                             | 1         | 1.1%    |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.1%    |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.1%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1.1%    |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.1%    |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.1%    |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.1%    |
| TO Exter nal USB 3.0 1TB                            | 1         | 1.1%    |
| SPCC Solid State Disk 120GB                         | 1         | 1.1%    |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 1.1%    |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.1%    |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 1.1%    |
| SK hynix HCG8e  64GB                                | 1         | 1.1%    |
| SK hynix HBG4e  32GB                                | 1         | 1.1%    |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.1%    |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.1%    |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1.1%    |

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
| Kingston            | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Corsair             | 1         | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 33        | 40     | 39.29%  |
| SSD     | 29        | 37     | 34.52%  |
| HDD     | 12        | 12     | 14.29%  |
| MMC     | 9         | 11     | 10.71%  |
| Unknown | 1         | 1      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 48     | 46.34%  |
| NVMe | 33        | 39     | 40.24%  |
| MMC  | 9         | 11     | 10.98%  |
| SAS  | 2         | 3      | 2.44%   |

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
| 251-500        | 26        | 35.62%  |
| 101-250        | 23        | 31.51%  |
| 501-1000       | 7         | 9.59%   |
| 51-100         | 6         | 8.22%   |
| 21-50          | 4         | 5.48%   |
| 1001-2000      | 4         | 5.48%   |
| 1-20           | 2         | 2.74%   |
| More than 3000 | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 21        | 28%     |
| 21-50     | 19        | 25.33%  |
| 101-250   | 15        | 20%     |
| 51-100    | 10        | 13.33%  |
| 251-500   | 6         | 8%      |
| 1001-2000 | 2         | 2.67%   |
| 501-1000  | 2         | 2.67%   |

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
| Detected | 44        | 56     | 57.89%  |
| Works    | 31        | 44     | 40.79%  |
| Malfunc  | 1         | 1      | 1.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 46        | 53.49%  |
| Samsung Electronics            | 13        | 15.12%  |
| AMD                            | 6         | 6.98%   |
| Toshiba America Info Systems   | 3         | 3.49%   |
| SanDisk                        | 3         | 3.49%   |
| SK hynix                       | 2         | 2.33%   |
| Micron Technology              | 2         | 2.33%   |
| KIOXIA                         | 2         | 2.33%   |
| Kingston Technology Company    | 2         | 2.33%   |
| Yangtze Memory Technologies    | 1         | 1.16%   |
| Solid State Storage Technology | 1         | 1.16%   |
| Realtek Semiconductor          | 1         | 1.16%   |
| Phison Electronics             | 1         | 1.16%   |
| Nvidia                         | 1         | 1.16%   |
| Marvell Technology Group       | 1         | 1.16%   |
| ADATA Technology               | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 7.78%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 6.67%   |
| Samsung NVMe SSD Controller 980                                              | 5         | 5.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 4         | 4.44%   |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 4.44%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 3.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 3.33%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 3.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 3.33%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 2.22%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 2.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.22%   |
| Yangtze Memory Non-Volatile memory controller                                | 1         | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.11%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.11%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.11%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.11%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.11%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.11%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.11%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.11%   |
| Realtek NVMe Controller                                                      | 1         | 1.11%   |
| Phison NVMe Storage Controller                                               | 1         | 1.11%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.11%   |
| Micron NVMe Storage Controller                                               | 1         | 1.11%   |
| Micron NVMe Controller                                                       | 1         | 1.11%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1.11%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.11%   |
| Kingston Company NVMe Controller                                             | 1         | 1.11%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 1.11%   |
| Intel SSD 660P Series                                                        | 1         | 1.11%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 55.68%  |
| NVMe | 33        | 37.5%   |
| RAID | 5         | 5.68%   |
| IDE  | 1         | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 87.67%  |
| AMD    | 9         | 12.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 5.48%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.74%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.74%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.74%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.74%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.74%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.37%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.37%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.37%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.37%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.37%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.37%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 1         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 23.29%  |
| Intel Core i7        | 15        | 20.55%  |
| Other                | 13        | 17.81%  |
| Intel Core i3        | 5         | 6.85%   |
| Intel Celeron        | 4         | 5.48%   |
| AMD Ryzen 5          | 4         | 5.48%   |
| Intel Atom           | 3         | 4.11%   |
| AMD Ryzen 7          | 3         | 4.11%   |
| Intel Pentium Silver | 2         | 2.74%   |
| Intel Pentium        | 2         | 2.74%   |
| Intel Core 2 Duo     | 2         | 2.74%   |
| Intel Core i9        | 1         | 1.37%   |
| AMD Ryzen 3          | 1         | 1.37%   |
| AMD A8               | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 33        | 45.21%  |
| 2      | 27        | 36.99%  |
| 8      | 7         | 9.59%   |
| 6      | 4         | 5.48%   |
| 10     | 2         | 2.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 76.71%  |
| 1      | 17        | 23.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 73        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 56%     |
| 0x806c1    | 4         | 5.33%   |
| 0x806ec    | 3         | 4%      |
| 0x706a8    | 3         | 4%      |
| 0x206a7    | 3         | 4%      |
| 0x08600106 | 3         | 4%      |
| 0x806d1    | 2         | 2.67%   |
| 0x20655    | 2         | 2.67%   |
| 0x08108102 | 2         | 2.67%   |
| 0x906ea    | 1         | 1.33%   |
| 0x806eb    | 1         | 1.33%   |
| 0x806ea    | 1         | 1.33%   |
| 0x506c9    | 1         | 1.33%   |
| 0x40651    | 1         | 1.33%   |
| 0x306d4    | 1         | 1.33%   |
| 0x306c3    | 1         | 1.33%   |
| 0x30678    | 1         | 1.33%   |
| 0x106e5    | 1         | 1.33%   |
| 0x0a50000c | 1         | 1.33%   |
| 0x07030104 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 20.55%  |
| TigerLake     | 8         | 10.96%  |
| Skylake       | 5         | 6.85%   |
| Unknown       | 5         | 6.85%   |
| IvyBridge     | 4         | 5.48%   |
| Haswell       | 4         | 5.48%   |
| Goldmont plus | 4         | 5.48%   |
| Zen 2         | 3         | 4.11%   |
| Silvermont    | 3         | 4.11%   |
| SandyBridge   | 3         | 4.11%   |
| IceLake       | 3         | 4.11%   |
| Broadwell     | 3         | 4.11%   |
| Zen+          | 2         | 2.74%   |
| Zen 3         | 2         | 2.74%   |
| Westmere      | 2         | 2.74%   |
| Penryn        | 2         | 2.74%   |
| CometLake     | 2         | 2.74%   |
| Puma          | 1         | 1.37%   |
| Nehalem       | 1         | 1.37%   |
| Goldmont      | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 68.54%  |
| Nvidia | 17        | 19.1%   |
| AMD    | 11        | 12.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 8.79%   |
| Intel UHD Graphics 620                                                    | 5         | 5.49%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 4.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 4.4%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 4.4%    |
| Intel HD Graphics 5500                                                    | 3         | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 3.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.3%    |
| AMD Renoir                                                                | 3         | 3.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 2.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.2%    |
| Intel HD Graphics 620                                                     | 2         | 2.2%    |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 2.2%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.2%    |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.2%    |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 1.1%    |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 1.1%    |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.1%    |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.1%    |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.1%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.1%    |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.1%    |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.1%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.1%    |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.1%    |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.1%    |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.1%    |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.1%    |
| Intel Iris Plus Graphics G7                                               | 1         | 1.1%    |
| Intel HD Graphics 530                                                     | 1         | 1.1%    |
| Intel HD Graphics 500                                                     | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 61.64%  |
| Intel + Nvidia | 13        | 17.81%  |
| 1 x AMD        | 6         | 8.22%   |
| 1 x Nvidia     | 3         | 4.11%   |
| 2 x AMD        | 2         | 2.74%   |
| Intel + AMD    | 2         | 2.74%   |
| Other          | 1         | 1.37%   |
| AMD + Nvidia   | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 84.93%  |
| Proprietary | 10        | 13.7%   |
| Unknown     | 1         | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 84.93%  |
| 1.01-2.0   | 4         | 5.48%   |
| 0.01-0.5   | 3         | 4.11%   |
| 7.01-8.0   | 2         | 2.74%   |
| 0.51-1.0   | 2         | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 19        | 22.09%  |
| BOE                     | 18        | 20.93%  |
| Samsung Electronics     | 10        | 11.63%  |
| AU Optronics            | 9         | 10.47%  |
| LG Display              | 7         | 8.14%   |
| Apple                   | 4         | 4.65%   |
| Sharp                   | 3         | 3.49%   |
| Goldstar                | 3         | 3.49%   |
| Lenovo                  | 2         | 2.33%   |
| Unknown (AAA)           | 1         | 1.16%   |
| TMX                     | 1         | 1.16%   |
| Philips                 | 1         | 1.16%   |
| MStar                   | 1         | 1.16%   |
| KDC                     | 1         | 1.16%   |
| IBM                     | 1         | 1.16%   |
| HKC                     | 1         | 1.16%   |
| Daewoo                  | 1         | 1.16%   |
| Chi Mei Optoelectronics | 1         | 1.16%   |
| BenQ                    | 1         | 1.16%   |
| AOC                     | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 2.33%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                | 1         | 1.16%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                 | 1         | 1.16%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                 | 1         | 1.16%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 1.16%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch    | 1         | 1.16%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch   | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch   | 1         | 1.16%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 1         | 1.16%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                 | 1         | 1.16%   |
| MStar LCD TV MST9000 1360x768                                           | 1         | 1.16%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch             | 1         | 1.16%   |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                    | 1         | 1.16%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                | 1         | 1.16%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                   | 1         | 1.16%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                   | 1         | 1.16%   |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                    | 1         | 1.16%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1         | 1.16%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1         | 1.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1         | 1.16%   |
| Daewoo 23.6 monitor DWE0236 1920x1080 521x293mm 23.5-inch               | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch        | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 340x190mm 15.3-inch        | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 41.03%  |
| 1366x768 (WXGA)    | 21        | 26.92%  |
| 3840x2160 (4K)     | 3         | 3.85%   |
| 2560x1440 (QHD)    | 3         | 3.85%   |
| 1920x1200 (WUXGA)  | 3         | 3.85%   |
| 1600x900 (HD+)     | 3         | 3.85%   |
| 1280x800 (WXGA)    | 3         | 3.85%   |
| 1680x1050 (WSXGA+) | 2         | 2.56%   |
| 1440x900 (WXGA+)   | 2         | 2.56%   |
| 3456x2160          | 1         | 1.28%   |
| 2880x1800          | 1         | 1.28%   |
| 2560x1600          | 1         | 1.28%   |
| 2560x1080          | 1         | 1.28%   |
| 2520x1680          | 1         | 1.28%   |
| 1360x768           | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 39.53%  |
| 13      | 18        | 20.93%  |
| 14      | 10        | 11.63%  |
| 17      | 4         | 4.65%   |
| 27      | 3         | 3.49%   |
| 11      | 3         | 3.49%   |
| 40      | 2         | 2.33%   |
| 24      | 2         | 2.33%   |
| 23      | 2         | 2.33%   |
| 21      | 2         | 2.33%   |
| 84      | 1         | 1.16%   |
| 60      | 1         | 1.16%   |
| 34      | 1         | 1.16%   |
| 31      | 1         | 1.16%   |
| 10      | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 59.3%   |
| 201-300     | 14        | 16.28%  |
| 501-600     | 5         | 5.81%   |
| 351-400     | 5         | 5.81%   |
| 401-500     | 3         | 3.49%   |
| 801-900     | 2         | 2.33%   |
| 601-700     | 2         | 2.33%   |
| 701-800     | 1         | 1.16%   |
| 1501-2000   | 1         | 1.16%   |
| 1001-1500   | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 60        | 80%     |
| 16/10 | 12        | 16%     |
| 3/2   | 2         | 2.67%   |
| 21/9  | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 39.53%  |
| 81-90          | 22        | 25.58%  |
| 71-80          | 5         | 5.81%   |
| 201-250        | 5         | 5.81%   |
| 121-130        | 4         | 4.65%   |
| 51-60          | 3         | 3.49%   |
| 301-350        | 3         | 3.49%   |
| More than 1000 | 2         | 2.33%   |
| 351-500        | 2         | 2.33%   |
| 501-1000       | 2         | 2.33%   |
| 41-50          | 1         | 1.16%   |
| 151-200        | 1         | 1.16%   |
| 91-100         | 1         | 1.16%   |
| Unknown        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 41.86%  |
| 101-120       | 23        | 26.74%  |
| 161-240       | 10        | 11.63%  |
| 51-100        | 9         | 10.47%  |
| More than 240 | 4         | 4.65%   |
| 1-50          | 3         | 3.49%   |
| Unknown       | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 58        | 78.38%  |
| 2     | 15        | 20.27%  |
| 0     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 35.96%  |
| Realtek Semiconductor | 38        | 33.33%  |
| Qualcomm Atheros      | 11        | 9.65%   |
| Broadcom              | 7         | 6.14%   |
| MediaTek              | 3         | 2.63%   |
| ASIX Electronics      | 3         | 2.63%   |
| Hewlett-Packard       | 2         | 1.75%   |
| Broadcom Limited      | 2         | 1.75%   |
| Xiaomi                | 1         | 0.88%   |
| TP-Link               | 1         | 0.88%   |
| Nvidia                | 1         | 0.88%   |
| Lenovo                | 1         | 0.88%   |
| JMicron Technology    | 1         | 0.88%   |
| Huawei Technologies   | 1         | 0.88%   |
| Fibocom               | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 20        | 14.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 5.15%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 5.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 3.68%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.68%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.21%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 2.21%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.21%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.47%   |
| Intel Wireless 8260                                                     | 2         | 1.47%   |
| Intel Wireless 7265                                                     | 2         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.74%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.74%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.74%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 53.33%  |
| Realtek Semiconductor | 12        | 16%     |
| Qualcomm Atheros      | 9         | 12%     |
| Broadcom              | 7         | 9.33%   |
| MediaTek              | 3         | 4%      |
| TP-Link               | 1         | 1.33%   |
| Hewlett-Packard       | 1         | 1.33%   |
| Fibocom               | 1         | 1.33%   |
| Broadcom Limited      | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 7         | 9.33%   |
| Intel Wireless 8265 / 8275                                              | 5         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 5.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4%      |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.67%   |
| Intel Wireless 8260                                                     | 2         | 2.67%   |
| Intel Wireless 7265                                                     | 2         | 2.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.33%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.33%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.33%   |
| Intel Wireless 7260                                                     | 1         | 1.33%   |
| Intel Wireless 3165                                                     | 1         | 1.33%   |
| Intel Wireless 3160                                                     | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.33%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.33%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.33%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.33%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 57.63%  |
| Intel                 | 12        | 20.34%  |
| ASIX Electronics      | 3         | 5.08%   |
| Qualcomm Atheros      | 2         | 3.39%   |
| Broadcom              | 2         | 3.39%   |
| Xiaomi                | 1         | 1.69%   |
| Nvidia                | 1         | 1.69%   |
| Lenovo                | 1         | 1.69%   |
| JMicron Technology    | 1         | 1.69%   |
| Hewlett-Packard       | 1         | 1.69%   |
| Broadcom Limited      | 1         | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 11.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 8.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 5%      |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.67%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.67%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.67%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.67%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.67%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.67%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.67%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.67%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 55.91%  |
| Ethernet | 55        | 43.31%  |
| Modem    | 1         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 81.33%  |
| Ethernet | 14        | 18.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 65.75%  |
| 1     | 21        | 28.77%  |
| 0     | 4         | 5.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 67.11%  |
| Yes  | 25        | 32.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 57.81%  |
| Realtek Semiconductor           | 6         | 9.38%   |
| Qualcomm Atheros Communications | 5         | 7.81%   |
| Broadcom                        | 4         | 6.25%   |
| Apple                           | 4         | 6.25%   |
| IMC Networks                    | 2         | 3.13%   |
| Dell                            | 2         | 3.13%   |
| Smart Modular Technologies      | 1         | 1.56%   |
| Realtek                         | 1         | 1.56%   |
| MediaTek                        | 1         | 1.56%   |
| Foxconn International           | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 13        | 20.31%  |
| Intel AX201 Bluetooth                              | 12        | 18.75%  |
| Realtek Bluetooth Radio                            | 5         | 7.81%   |
| Intel AX200 Bluetooth                              | 5         | 7.81%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.13%   |
| Intel AX210 Bluetooth                              | 2         | 3.13%   |
| Dell DW375 Bluetooth Module                        | 2         | 3.13%   |
| Apple Bluetooth USB Host Controller                | 2         | 3.13%   |
| Apple Bluetooth Host Controller                    | 2         | 3.13%   |
| Smart Modular Bluetooth Device                     | 1         | 1.56%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.56%   |
| Realtek Bluetooth Radio                            | 1         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.56%   |
| MediaTek Wireless_Device                           | 1         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.56%   |
| Intel Bluetooth Device                             | 1         | 1.56%   |
| IMC Networks Wireless_Device                       | 1         | 1.56%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.56%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.56%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 60        | 74.07%  |
| AMD                  | 9         | 11.11%  |
| Nvidia               | 8         | 9.88%   |
| Plantronics          | 1         | 1.23%   |
| Logitech             | 1         | 1.23%   |
| LINE TECH INDUSTRIAL | 1         | 1.23%   |
| DSEA A/S             | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 11.22%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 8.16%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 8.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 6.12%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 4.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 4.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 3.06%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.06%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.04%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.02%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.02%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 1.02%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.02%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.02%   |
| DSEA A/S EPOS ADAPT 1x5                                                    | 1         | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.02%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 32.69%  |
| SK hynix            | 13        | 25%     |
| Kingston            | 5         | 9.62%   |
| Micron Technology   | 4         | 7.69%   |
| Elpida              | 3         | 5.77%   |
| Unknown (ABCD)      | 2         | 3.85%   |
| Ramaxel Technology  | 2         | 3.85%   |
| Unknown             | 1         | 1.92%   |
| Teikon              | 1         | 1.92%   |
| Magnum Tech         | 1         | 1.92%   |
| fef5                | 1         | 1.92%   |
| ChangXin Memory     | 1         | 1.92%   |
| 8945000080AD        | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 5.45%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 3.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.64%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 3.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.82%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.82%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.82%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.82%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.82%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.82%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.82%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 1.82%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.82%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Micron RAM 16JSS51264HY-1G1A1 4GB SODIMM DDR3 1067MT/s           | 1         | 1.82%   |
| Micron RAM 16ATF4G64HZ-3G2B4 32GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 58.14%  |
| DDR3    | 11        | 25.58%  |
| LPDDR4  | 6         | 13.95%  |
| Unknown | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 86.05%  |
| Row Of Chips | 3         | 6.98%   |
| Unknown      | 2         | 4.65%   |
| Chip         | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 40.91%  |
| 16384 | 8         | 18.18%  |
| 4096  | 8         | 18.18%  |
| 32768 | 4         | 9.09%   |
| 2048  | 4         | 9.09%   |
| 1024  | 2         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 30.43%  |
| 2667  | 8         | 17.39%  |
| 1600  | 8         | 17.39%  |
| 2400  | 7         | 15.22%  |
| 1334  | 2         | 4.35%   |
| 4267  | 1         | 2.17%   |
| 3733  | 1         | 2.17%   |
| 3266  | 1         | 2.17%   |
| 2133  | 1         | 2.17%   |
| 1333  | 1         | 2.17%   |
| 1067  | 1         | 2.17%   |
| 1066  | 1         | 2.17%   |

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
| Chicony Electronics                    | 17        | 27.42%  |
| IMC Networks                           | 8         | 12.9%   |
| Realtek Semiconductor                  | 6         | 9.68%   |
| Bison Electronics                      | 5         | 8.06%   |
| Sunplus Innovation Technology          | 4         | 6.45%   |
| Luxvisions Innotech Limited            | 4         | 6.45%   |
| Syntek                                 | 3         | 4.84%   |
| Microdia                               | 3         | 4.84%   |
| Apple                                  | 3         | 4.84%   |
| Quanta                                 | 2         | 3.23%   |
| Unknown (3730304231385631394831)       | 1         | 1.61%   |
| Samsung Electronics                    | 1         | 1.61%   |
| Polycom                                | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.61%   |
| Alcor Micro                            | 1         | 1.61%   |
| Acer                                   | 1         | 1.61%   |
| Unknown                                | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 4.84%   |
| IMC Networks Integrated Camera                                             | 3         | 4.84%   |
| Chicony USB2.0 Camera                                                      | 3         | 4.84%   |
| Bison SunplusIT Integrated Camera                                          | 3         | 4.84%   |
| Syntek Integrated Camera                                                   | 2         | 3.23%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.23%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.23%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 3.23%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 3.23%   |
| Chicony Integrated Camera                                                  | 2         | 3.23%   |
| Chicony HP HD Camera                                                       | 2         | 3.23%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.23%   |
| Unknown (3730304231385631394831) USB Camera                                | 1         | 1.61%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.61%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.61%   |
| Sunplus HD WebCam                                                          | 1         | 1.61%   |
| Sunplus FHD Camera Microphone                                              | 1         | 1.61%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.61%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.61%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.61%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.61%   |
| Realtek Integrated Webcam                                                  | 1         | 1.61%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.61%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 1.61%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.61%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.61%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.61%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.61%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.61%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.61%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.61%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.61%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.61%   |
| Chicony Integrated IR Camera                                               | 1         | 1.61%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.61%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.61%   |
| Chicony HD Webcam                                                          | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 41.18%  |
| Shenzhen Goodix Technology | 5         | 29.41%  |
| Validity Sensors           | 3         | 17.65%  |
| LighTuning Technology      | 1         | 5.88%   |
| Elan Microelectronics      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 3         | 17.65%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 11.76%  |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 5.88%   |
| Synaptics UWP WBDI Device                                 | 1         | 5.88%   |
| Synaptics UWP WBDI                                        | 1         | 5.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 5.88%   |
| Shenzhen Goodix FingerPrint                               | 1         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 5.88%   |
| Elan ELAN:Fingerprint                                     | 1         | 5.88%   |
| Unknown                                                   | 1         | 5.88%   |

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
| 0     | 44        | 59.46%  |
| 1     | 20        | 27.03%  |
| 2     | 7         | 9.46%   |
| 3     | 2         | 2.7%    |
| 7     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 39.02%  |
| Net/wireless             | 4         | 9.76%   |
| Communication controller | 4         | 9.76%   |
| Chipcard                 | 4         | 9.76%   |
| Graphics card            | 3         | 7.32%   |
| Camera                   | 3         | 7.32%   |
| Sound                    | 2         | 4.88%   |
| Multimedia controller    | 2         | 4.88%   |
| Card reader              | 2         | 4.88%   |
| Bluetooth                | 1         | 2.44%   |


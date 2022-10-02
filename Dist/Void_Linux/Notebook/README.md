Void Linux - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

Total: 88

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Exo           | Exomate X352                | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Nokia         | Booklet 3G                  | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| ASUSTek       | X751LD                      | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Acer          | Aspire E1-531               | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Acer          | Aspire E1-531               | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| Samsung       | 275E4E/275E5E               | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| Lenovo        | G50-45 80E3                 | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| HP            | Laptop 14-dk0xxx            | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| Acer          | Aspire SW5-015              | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| Dell          | Inspiron 11 - 3148          | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| Acer          | AO722                       | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| Acer          | Nitro AN715-51              | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| Acer          | AO722                       | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| Dell          | Inspiron 1501               | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| Digibras      | NH4CU03                     | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| Positivo      | Mobile                      | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 43        | 59.72%  |
| Void Linux         | 29        | 40.28%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 70        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 5         | 6.76%   |
| 5.8.18_1    | 3         | 4.05%   |
| 5.8.12_1    | 3         | 4.05%   |
| 5.3.9_1     | 3         | 4.05%   |
| 5.18.19_1   | 3         | 4.05%   |
| 5.10.17_1   | 3         | 4.05%   |
| 5.4.24_1    | 2         | 2.7%    |
| 5.18.14_1   | 2         | 2.7%    |
| 5.16.20_1   | 2         | 2.7%    |
| 5.15.32_1   | 2         | 2.7%    |
| 5.13.13_1   | 2         | 2.7%    |
| 5.12.10_1   | 2         | 2.7%    |
| 5.9.16_1    | 1         | 1.35%   |
| 5.9.14_1    | 1         | 1.35%   |
| 5.9.0-rc8_2 | 1         | 1.35%   |
| 5.8.9_1     | 1         | 1.35%   |
| 5.8.8_1     | 1         | 1.35%   |
| 5.8.7_1     | 1         | 1.35%   |
| 5.8.6_1     | 1         | 1.35%   |
| 5.8.12_2    | 1         | 1.35%   |
| 5.7.16_1    | 1         | 1.35%   |
| 5.4.35_1    | 1         | 1.35%   |
| 5.4.21_1    | 1         | 1.35%   |
| 5.4.13_2    | 1         | 1.35%   |
| 5.2.13_1    | 1         | 1.35%   |
| 5.18.7_1    | 1         | 1.35%   |
| 5.15.6_1    | 1         | 1.35%   |
| 5.15.45_1   | 1         | 1.35%   |
| 5.15.28_1   | 1         | 1.35%   |
| 5.15.26_1   | 1         | 1.35%   |
| 5.15.22_1   | 1         | 1.35%   |
| 5.15.17_1   | 1         | 1.35%   |
| 5.15.16_1   | 1         | 1.35%   |
| 5.15.14_1   | 1         | 1.35%   |
| 5.15.12_1   | 1         | 1.35%   |
| 5.14.0_1    | 1         | 1.35%   |
| 5.13.18_1   | 1         | 1.35%   |
| 5.13.15_1   | 1         | 1.35%   |
| 5.13.12_1   | 1         | 1.35%   |
| 5.13.10_1   | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.19 | 5         | 6.76%   |
| 5.8.12  | 4         | 5.41%   |
| 5.8.18  | 3         | 4.05%   |
| 5.3.9   | 3         | 4.05%   |
| 5.18.19 | 3         | 4.05%   |
| 5.10.17 | 3         | 4.05%   |
| 5.4.24  | 2         | 2.7%    |
| 5.18.14 | 2         | 2.7%    |
| 5.16.20 | 2         | 2.7%    |
| 5.15.32 | 2         | 2.7%    |
| 5.13.13 | 2         | 2.7%    |
| 5.12.10 | 2         | 2.7%    |
| 5.9.16  | 1         | 1.35%   |
| 5.9.14  | 1         | 1.35%   |
| 5.9.0   | 1         | 1.35%   |
| 5.8.9   | 1         | 1.35%   |
| 5.8.8   | 1         | 1.35%   |
| 5.8.7   | 1         | 1.35%   |
| 5.8.6   | 1         | 1.35%   |
| 5.7.16  | 1         | 1.35%   |
| 5.4.35  | 1         | 1.35%   |
| 5.4.21  | 1         | 1.35%   |
| 5.4.13  | 1         | 1.35%   |
| 5.2.13  | 1         | 1.35%   |
| 5.18.7  | 1         | 1.35%   |
| 5.15.6  | 1         | 1.35%   |
| 5.15.45 | 1         | 1.35%   |
| 5.15.28 | 1         | 1.35%   |
| 5.15.26 | 1         | 1.35%   |
| 5.15.22 | 1         | 1.35%   |
| 5.15.17 | 1         | 1.35%   |
| 5.15.16 | 1         | 1.35%   |
| 5.15.14 | 1         | 1.35%   |
| 5.15.12 | 1         | 1.35%   |
| 5.14.0  | 1         | 1.35%   |
| 5.13.18 | 1         | 1.35%   |
| 5.13.15 | 1         | 1.35%   |
| 5.13.12 | 1         | 1.35%   |
| 5.13.10 | 1         | 1.35%   |
| 5.12.7  | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 11        | 15.07%  |
| 5.15    | 11        | 15.07%  |
| 5.13    | 11        | 15.07%  |
| 5.12    | 7         | 9.59%   |
| 5.10    | 7         | 9.59%   |
| 5.18    | 6         | 8.22%   |
| 5.4     | 5         | 6.85%   |
| 5.9     | 3         | 4.11%   |
| 5.3     | 3         | 4.11%   |
| 5.16    | 2         | 2.74%   |
| 5.7     | 1         | 1.37%   |
| 5.2     | 1         | 1.37%   |
| 5.14    | 1         | 1.37%   |
| 5.11    | 1         | 1.37%   |
| 5.1     | 1         | 1.37%   |
| 4.4     | 1         | 1.37%   |
| 4.14    | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 65        | 92.86%  |
| i686    | 3         | 4.29%   |
| aarch64 | 2         | 2.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 46.58%  |
| XFCE       | 9         | 12.33%  |
| KDE        | 8         | 10.96%  |
| MATE       | 6         | 8.22%   |
| i3         | 4         | 5.48%   |
| GNOME      | 3         | 4.11%   |
| KDE5       | 2         | 2.74%   |
| bspwm      | 2         | 2.74%   |
| X-Cinnamon | 1         | 1.37%   |
| river      | 1         | 1.37%   |
| openbox    | 1         | 1.37%   |
| Lumina     | 1         | 1.37%   |
| awesome    | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 48        | 67.61%  |
| Tty     | 9         | 12.68%  |
| Wayland | 8         | 11.27%  |
| Unknown | 6         | 8.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 91.55%  |
| LXDM    | 3         | 4.23%   |
| LightDM | 2         | 2.82%   |
| SDDM    | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 41        | 56.94%  |
| Unknown | 9         | 12.5%   |
| en_GB   | 5         | 6.94%   |
| en_DK   | 4         | 5.56%   |
| de_DE   | 2         | 2.78%   |
| tr_TR   | 1         | 1.39%   |
| ru_UA   | 1         | 1.39%   |
| ru_RU   | 1         | 1.39%   |
| pt_BR   | 1         | 1.39%   |
| nb_NO   | 1         | 1.39%   |
| es_HN   | 1         | 1.39%   |
| es_ES   | 1         | 1.39%   |
| es_DO   | 1         | 1.39%   |
| en_NZ   | 1         | 1.39%   |
| en_CA   | 1         | 1.39%   |
| en_AU   | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 57.75%  |
| BIOS | 30        | 42.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 64.79%  |
| Btrfs   | 15        | 21.13%  |
| Unknown | 4         | 5.63%   |
| Xfs     | 3         | 4.23%   |
| Zfs     | 1         | 1.41%   |
| F2fs    | 1         | 1.41%   |
| Ext3    | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 41        | 56.94%  |
| Unknown | 20        | 27.78%  |
| MBR     | 11        | 15.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 90%     |
| Yes       | 7         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 81.43%  |
| Yes       | 13        | 18.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 20%     |
| Acer                | 12        | 17.14%  |
| ASUSTek Computer    | 11        | 15.71%  |
| Hewlett-Packard     | 10        | 14.29%  |
| Dell                | 7         | 10%     |
| HUAWEI              | 2         | 2.86%   |
| Unknown             | 2         | 2.86%   |
| Samsung Electronics | 1         | 1.43%   |
| Positivo            | 1         | 1.43%   |
| Pine Microsystems   | 1         | 1.43%   |
| Notebook            | 1         | 1.43%   |
| Nokia               | 1         | 1.43%   |
| MSI                 | 1         | 1.43%   |
| Getac               | 1         | 1.43%   |
| Framework           | 1         | 1.43%   |
| Exo                 | 1         | 1.43%   |
| Digibras            | 1         | 1.43%   |
| Chuwi               | 1         | 1.43%   |
| Apple               | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Laptop 15-bw0xx                    | 2         | 2.86%   |
| Acer Swift SF314-42                   | 2         | 2.86%   |
| Unknown                               | 2         | 2.86%   |
| Samsung 275E4E/275E5E                 | 1         | 1.43%   |
| Positivo Mobile                       | 1         | 1.43%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 1.43%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 1.43%   |
| Nokia Booklet 3G                      | 1         | 1.43%   |
| MSI Bravo 15 A4DDR                    | 1         | 1.43%   |
| Lenovo ThinkPad X260 20F5S08Q00       | 1         | 1.43%   |
| Lenovo ThinkPad X240 20AMA34HMN       | 1         | 1.43%   |
| Lenovo ThinkPad T480 20L6SA5Q00       | 1         | 1.43%   |
| Lenovo ThinkPad T460 20FMS0WN00       | 1         | 1.43%   |
| Lenovo ThinkPad T430 2349PS3          | 1         | 1.43%   |
| Lenovo ThinkPad T420 4180A21          | 1         | 1.43%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW | 1         | 1.43%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00 | 1         | 1.43%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200  | 1         | 1.43%   |
| Lenovo ThinkPad E595 20NFCTO1WW       | 1         | 1.43%   |
| Lenovo IdeaPad Z570 10246ZG           | 1         | 1.43%   |
| Lenovo IdeaPad S145-14IIL 81W6        | 1         | 1.43%   |
| Lenovo IdeaPad 710S-13IKB 80VQ        | 1         | 1.43%   |
| Lenovo G50-45 80E3                    | 1         | 1.43%   |
| HUAWEI KLVL-WXXW                      | 1         | 1.43%   |
| HUAWEI HN-WX9X                        | 1         | 1.43%   |
| HP Pavilion Notebook                  | 1         | 1.43%   |
| HP Pavilion Gaming Laptop 15-dk0xxx   | 1         | 1.43%   |
| HP Notebook                           | 1         | 1.43%   |
| HP Laptop 15s-eq2xxx                  | 1         | 1.43%   |
| HP Laptop 14-dk0xxx                   | 1         | 1.43%   |
| HP Laptop 14-bs0xx                    | 1         | 1.43%   |
| HP ENVY 6                             | 1         | 1.43%   |
| HP 15                                 | 1         | 1.43%   |
| Getac V110                            | 1         | 1.43%   |
| Framework Laptop                      | 1         | 1.43%   |
| Exo Exomate X352                      | 1         | 1.43%   |
| Digibras NH4CU03                      | 1         | 1.43%   |
| Dell Precision 3530                   | 1         | 1.43%   |
| Dell Latitude E4300                   | 1         | 1.43%   |
| Dell Latitude 3379                    | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 10        | 14.29%  |
| Acer Aspire              | 7         | 10%     |
| HP Laptop                | 5         | 7.14%   |
| ASUS VivoBook            | 4         | 5.71%   |
| Lenovo IdeaPad           | 3         | 4.29%   |
| Dell Inspiron            | 3         | 4.29%   |
| HP Pavilion              | 2         | 2.86%   |
| Dell Latitude            | 2         | 2.86%   |
| Acer Swift               | 2         | 2.86%   |
| Unknown                  | 2         | 2.86%   |
| Samsung 275E4E           | 1         | 1.43%   |
| Positivo Mobile          | 1         | 1.43%   |
| Pine Microsystems Pine64 | 1         | 1.43%   |
| Notebook NV4XMB          | 1         | 1.43%   |
| Nokia Booklet            | 1         | 1.43%   |
| MSI Bravo                | 1         | 1.43%   |
| Lenovo G50-45            | 1         | 1.43%   |
| HUAWEI KLVL-WXXW         | 1         | 1.43%   |
| HUAWEI HN-WX9X           | 1         | 1.43%   |
| HP Notebook              | 1         | 1.43%   |
| HP ENVY                  | 1         | 1.43%   |
| HP 15                    | 1         | 1.43%   |
| Getac V110               | 1         | 1.43%   |
| Framework Laptop         | 1         | 1.43%   |
| Exo Exomate              | 1         | 1.43%   |
| Digibras NH4CU03         | 1         | 1.43%   |
| Dell Precision           | 1         | 1.43%   |
| Dell G3                  | 1         | 1.43%   |
| Chuwi GemiBook           | 1         | 1.43%   |
| ASUS X751LD              | 1         | 1.43%   |
| ASUS X555UJ              | 1         | 1.43%   |
| ASUS X555LD              | 1         | 1.43%   |
| ASUS X510UAR             | 1         | 1.43%   |
| ASUS X455LF              | 1         | 1.43%   |
| ASUS TUF                 | 1         | 1.43%   |
| ASUS ASUS                | 1         | 1.43%   |
| Apple MacBookPro11       | 1         | 1.43%   |
| Acer Nitro               | 1         | 1.43%   |
| Acer AOA150              | 1         | 1.43%   |
| Acer AO722               | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 12        | 17.14%  |
| 2020    | 9         | 12.86%  |
| 2016    | 7         | 10%     |
| 2014    | 6         | 8.57%   |
| 2018    | 5         | 7.14%   |
| 2015    | 5         | 7.14%   |
| 2013    | 5         | 7.14%   |
| 2017    | 4         | 5.71%   |
| 2021    | 3         | 4.29%   |
| 2012    | 3         | 4.29%   |
| 2011    | 3         | 4.29%   |
| 2009    | 2         | 2.86%   |
| 2008    | 2         | 2.86%   |
| Unknown | 2         | 2.86%   |
| 2010    | 1         | 1.43%   |
| 2006    | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 70        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 70        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 29.58%  |
| 3.01-4.0    | 18        | 25.35%  |
| 8.01-16.0   | 13        | 18.31%  |
| 16.01-24.0  | 7         | 9.86%   |
| 1.01-2.0    | 5         | 7.04%   |
| 32.01-64.0  | 3         | 4.23%   |
| 0.51-1.0    | 2         | 2.82%   |
| 24.01-32.0  | 1         | 1.41%   |
| 64.01-256.0 | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 27        | 36.49%  |
| 2.01-3.0   | 16        | 21.62%  |
| 0.51-1.0   | 14        | 18.92%  |
| 4.01-8.0   | 6         | 8.11%   |
| 3.01-4.0   | 6         | 8.11%   |
| 0.01-0.5   | 3         | 4.05%   |
| 16.01-24.0 | 1         | 1.35%   |
| 8.01-16.0  | 1         | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 78.57%  |
| 2      | 13        | 18.57%  |
| 3      | 1         | 1.43%   |
| 0      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 72.86%  |
| Yes       | 19        | 27.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 74.29%  |
| No        | 18        | 25.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 94.29%  |
| No        | 4         | 5.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 80%     |
| No        | 14        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 10        | 14.29%  |
| India              | 8         | 11.43%  |
| Germany            | 6         | 8.57%   |
| Russia             | 5         | 7.14%   |
| Ukraine            | 4         | 5.71%   |
| Denmark            | 4         | 5.71%   |
| Brazil             | 4         | 5.71%   |
| Switzerland        | 3         | 4.29%   |
| UK                 | 2         | 2.86%   |
| Turkey             | 2         | 2.86%   |
| Netherlands        | 2         | 2.86%   |
| Morocco            | 2         | 2.86%   |
| Bulgaria           | 2         | 2.86%   |
| Vietnam            | 1         | 1.43%   |
| Spain              | 1         | 1.43%   |
| Peru               | 1         | 1.43%   |
| Norway             | 1         | 1.43%   |
| New Zealand        | 1         | 1.43%   |
| Mexico             | 1         | 1.43%   |
| Indonesia          | 1         | 1.43%   |
| Honduras           | 1         | 1.43%   |
| Greece             | 1         | 1.43%   |
| France             | 1         | 1.43%   |
| Ecuador            | 1         | 1.43%   |
| Dominican Republic | 1         | 1.43%   |
| Czechia            | 1         | 1.43%   |
| Canada             | 1         | 1.43%   |
| Australia          | 1         | 1.43%   |
| Argentina          | 1         | 1.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| St Petersburg | 2         | 2.82%   |
| Moscow        | 2         | 2.82%   |
| Meknes        | 2         | 2.82%   |
| Hyderabad     | 2         | 2.82%   |
| Geneva        | 2         | 2.82%   |
| Yambol        | 1         | 1.41%   |
| Weatherford   | 1         | 1.41%   |
| Vlaardingen   | 1         | 1.41%   |
| Viby J        | 1         | 1.41%   |
| Trujillo      | 1         | 1.41%   |
| Toulouse      | 1         | 1.41%   |
| Toms River    | 1         | 1.41%   |
| Tegucigalpa   | 1         | 1.41%   |
| Syktyvkar     | 1         | 1.41%   |
| Surabaya      | 1         | 1.41%   |
| Stratford     | 1         | 1.41%   |
| Solone        | 1         | 1.41%   |
| Sofia         | 1         | 1.41%   |
| Sistranda     | 1         | 1.41%   |
| Saxtons River | 1         | 1.41%   |
| Sao Paulo     | 1         | 1.41%   |
| Santo Domingo | 1         | 1.41%   |
| Rostock       | 1         | 1.41%   |
| Rosenheim     | 1         | 1.41%   |
| Regensburg    | 1         | 1.41%   |
| Pune          | 1         | 1.41%   |
| Prague        | 1         | 1.41%   |
| Porto Alegre  | 1         | 1.41%   |
| Pliening      | 1         | 1.41%   |
| Phoenix       | 1         | 1.41%   |
| Odense        | 1         | 1.41%   |
| New Delhi     | 1         | 1.41%   |
| Mossoro       | 1         | 1.41%   |
| Milford       | 1         | 1.41%   |
| Melbourne     | 1         | 1.41%   |
| Matos Costa   | 1         | 1.41%   |
| Los Angeles   | 1         | 1.41%   |
| Lakewood      | 1         | 1.41%   |
| Kremenchug    | 1         | 1.41%   |
| Izmir         | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 18     | 21.25%  |
| Seagate             | 14        | 15     | 17.5%   |
| WDC                 | 11        | 12     | 13.75%  |
| Unknown             | 6         | 10     | 7.5%    |
| Toshiba             | 5         | 5      | 6.25%   |
| Intel               | 5         | 6      | 6.25%   |
| HGST                | 5         | 6      | 6.25%   |
| SanDisk             | 4         | 5      | 5%      |
| SK hynix            | 2         | 2      | 2.5%    |
| Kingston            | 2         | 2      | 2.5%    |
| Hitachi             | 2         | 2      | 2.5%    |
| Transcend           | 1         | 1      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Patriot             | 1         | 1      | 1.25%   |
| Crucial             | 1         | 1      | 1.25%   |
| China               | 1         | 1      | 1.25%   |
| BHT                 | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 4         | 4.82%   |
| Toshiba MQ01ABF050 500GB                | 3         | 3.61%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 2.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 2.41%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 2.41%   |
| Samsung SSD 870 EVO 500GB               | 2         | 2.41%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 2.41%   |
| HGST HTS545050A7E680 500GB              | 2         | 2.41%   |
| HGST HTS541010B7E610 1TB                | 2         | 2.41%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 1.2%    |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 1.2%    |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1.2%    |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 1.2%    |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 1.2%    |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1.2%    |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 1.2%    |
| WDC WD Elements 500GB                   | 1         | 1.2%    |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 1.2%    |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 1.2%    |
| Unknown USB DISK 3.2 250GB              | 1         | 1.2%    |
| Unknown SD512  512MB                    | 1         | 1.2%    |
| Unknown SD16G  16GB                     | 1         | 1.2%    |
| Unknown MMC Card  8GB                   | 1         | 1.2%    |
| Unknown MMC Card  32GB                  | 1         | 1.2%    |
| Unknown MMC Card  128GB                 | 1         | 1.2%    |
| Unknown MMC Card                        | 1         | 1.2%    |
| Unknown CWBC3R  64GB                    | 1         | 1.2%    |
| Transcend TS128GMTS800 128GB SSD        | 1         | 1.2%    |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.2%    |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 1.2%    |
| Seagate ST98823AS 80GB                  | 1         | 1.2%    |
| Seagate ST9750420AS 752GB               | 1         | 1.2%    |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1.2%    |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.2%    |
| Seagate Expansion Desk 2TB              | 1         | 1.2%    |
| SanDisk SD9SN8W128G1102 128GB SSD       | 1         | 1.2%    |
| SanDisk SD9SN8W128G 128GB SSD           | 1         | 1.2%    |
| SanDisk SD8SN8U1T001122 1TB SSD         | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 41.18%  |
| WDC                 | 8         | 8      | 23.53%  |
| HGST                | 5         | 6      | 14.71%  |
| Toshiba             | 4         | 4      | 11.76%  |
| Hitachi             | 2         | 2      | 5.88%   |
| Samsung Electronics | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 38.89%  |
| SanDisk             | 3         | 3      | 16.67%  |
| Transcend           | 1         | 1      | 5.56%   |
| Patriot             | 1         | 1      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| China               | 1         | 1      | 5.56%   |
| BHT                 | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 36     | 42.31%  |
| NVMe    | 20        | 25     | 25.64%  |
| SSD     | 18        | 18     | 23.08%  |
| MMC     | 5         | 8      | 6.41%   |
| Unknown | 2         | 3      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 53     | 62.67%  |
| NVMe | 20        | 25     | 26.67%  |
| MMC  | 5         | 8      | 6.67%   |
| SAS  | 3         | 4      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 33     | 58.82%  |
| 0.51-1.0   | 20        | 20     | 39.22%  |
| 1.01-2.0   | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 29.17%  |
| 501-1000       | 17        | 23.61%  |
| 101-250        | 13        | 18.06%  |
| Unknown        | 7         | 9.72%   |
| 1-20           | 4         | 5.56%   |
| 21-50          | 3         | 4.17%   |
| 1001-2000      | 3         | 4.17%   |
| 51-100         | 3         | 4.17%   |
| More than 3000 | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 26.39%  |
| 101-250        | 18        | 25%     |
| 21-50          | 15        | 20.83%  |
| 51-100         | 7         | 9.72%   |
| Unknown        | 7         | 9.72%   |
| 251-500        | 4         | 5.56%   |
| More than 3000 | 1         | 1.39%   |
| 1001-2000      | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 9.09%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 9.09%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 9.09%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 9.09%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 36.36%  |
| Hitachi             | 2         | 2      | 18.18%  |
| HGST                | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| Hitachi | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Works    | 39        | 46     | 51.32%  |
| Detected | 26        | 33     | 34.21%  |
| Malfunc  | 11        | 11     | 14.47%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 51.95%  |
| AMD                              | 18        | 23.38%  |
| Samsung Electronics              | 10        | 12.99%  |
| SanDisk                          | 3         | 3.9%    |
| SK hynix                         | 2         | 2.6%    |
| Toshiba America Info Systems     | 1         | 1.3%    |
| Silicon Integrated Systems [SiS] | 1         | 1.3%    |
| Phison Electronics               | 1         | 1.3%    |
| Kingston Technology Company      | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 20%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 11.25%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 7.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 7.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 5%      |
| Intel SSD 660P Series                                                            | 3         | 3.75%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.5%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.5%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.25%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.25%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.25%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.25%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 1.25%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.25%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.25%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.25%   |
| AMD SB600 IDE                                                                    | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 62.82%  |
| NVMe | 20        | 25.64%  |
| RAID | 5         | 6.41%   |
| IDE  | 4         | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 64.29%  |
| AMD    | 23        | 32.86%  |
| ARM    | 2         | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.86%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.86%   |
| ARM Processor                                 | 2         | 2.86%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.86%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.86%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 2.86%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.43%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.43%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.43%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.43%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.43%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.43%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.43%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.43%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.43%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.43%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.43%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.43%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.43%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz          | 1         | 1.43%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.43%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 22.86%  |
| Intel Core i7           | 8         | 11.43%  |
| Intel Core i3           | 8         | 11.43%  |
| Other                   | 7         | 10%     |
| Intel Atom              | 5         | 7.14%   |
| AMD Ryzen 7             | 5         | 7.14%   |
| AMD Ryzen 5             | 5         | 7.14%   |
| Intel Celeron           | 3         | 4.29%   |
| AMD Ryzen 7 PRO         | 2         | 2.86%   |
| AMD A8                  | 2         | 2.86%   |
| Intel Pentium           | 1         | 1.43%   |
| Intel Genuine           | 1         | 1.43%   |
| Intel Core 2 Duo        | 1         | 1.43%   |
| AMD Turion 64 X2 Mobile | 1         | 1.43%   |
| AMD Ryzen 3             | 1         | 1.43%   |
| AMD E2                  | 1         | 1.43%   |
| AMD E1                  | 1         | 1.43%   |
| AMD C-60                | 1         | 1.43%   |
| AMD A4                  | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 45.71%  |
| 4      | 24        | 34.29%  |
| 8      | 5         | 7.14%   |
| 6      | 5         | 7.14%   |
| 1      | 4         | 5.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 98.57%  |
| 2      | 1         | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 47        | 67.14%  |
| 1      | 23        | 32.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 88.57%  |
| Unknown        | 4         | 5.71%   |
| 64-bit         | 2         | 2.86%   |
| 32-bit         | 2         | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 29.17%  |
| 0x40651    | 6         | 8.33%   |
| 0x306a9    | 4         | 5.56%   |
| 0x906ea    | 3         | 4.17%   |
| 0x806e9    | 3         | 4.17%   |
| 0x406e3    | 3         | 4.17%   |
| 0x08600104 | 3         | 4.17%   |
| 0x08108102 | 3         | 4.17%   |
| 0x806ec    | 2         | 2.78%   |
| 0x30678    | 2         | 2.78%   |
| 0x206a7    | 2         | 2.78%   |
| 0x106c2    | 2         | 2.78%   |
| 0x07030105 | 2         | 2.78%   |
| 0x06006705 | 2         | 2.78%   |
| 0x05000119 | 2         | 2.78%   |
| 0x806eb    | 1         | 1.39%   |
| 0x806ea    | 1         | 1.39%   |
| 0x406c4    | 1         | 1.39%   |
| 0x306d4    | 1         | 1.39%   |
| 0x106ca    | 1         | 1.39%   |
| 0x08608103 | 1         | 1.39%   |
| 0x08608102 | 1         | 1.39%   |
| 0x08600106 | 1         | 1.39%   |
| 0x08600102 | 1         | 1.39%   |
| 0x08108109 | 1         | 1.39%   |
| 0x08101007 | 1         | 1.39%   |
| 0x07030104 | 1         | 1.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 18.57%  |
| Haswell       | 7         | 10%     |
| Zen 2         | 6         | 8.57%   |
| Skylake       | 5         | 7.14%   |
| Zen+          | 4         | 5.71%   |
| IvyBridge     | 4         | 5.71%   |
| Excavator     | 4         | 5.71%   |
| Unknown       | 4         | 5.71%   |
| Silvermont    | 3         | 4.29%   |
| SandyBridge   | 3         | 4.29%   |
| Puma          | 3         | 4.29%   |
| Bonnell       | 3         | 4.29%   |
| TigerLake     | 2         | 2.86%   |
| Bobcat        | 2         | 2.86%   |
| Zen           | 1         | 1.43%   |
| Penryn        | 1         | 1.43%   |
| K8 Hammer     | 1         | 1.43%   |
| IceLake       | 1         | 1.43%   |
| Goldmont plus | 1         | 1.43%   |
| Core          | 1         | 1.43%   |
| Broadwell     | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 50.57%  |
| AMD                              | 24        | 27.59%  |
| Nvidia                           | 18        | 20.69%  |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 7.78%   |
| AMD Renoir                                                                               | 6         | 6.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 5.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 4.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 4.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.44%   |
| Intel HD Graphics 620                                                                    | 3         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.33%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.22%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.22%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.22%   |
| AMD Lucienne                                                                             | 2         | 2.22%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.11%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.11%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.11%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 1.11%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                                     | 1         | 1.11%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.11%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.11%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 1.11%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.11%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.11%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1.11%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.11%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 38.57%  |
| 1 x AMD        | 19        | 27.14%  |
| Intel + Nvidia | 16        | 22.86%  |
| Other          | 2         | 2.86%   |
| 2 x AMD        | 2         | 2.86%   |
| AMD + Nvidia   | 2         | 2.86%   |
| 1 x SiS        | 1         | 1.43%   |
| Intel + AMD    | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 77.14%  |
| Proprietary | 13        | 18.57%  |
| Unknown     | 3         | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 63.01%  |
| 0.01-0.5   | 12        | 16.44%  |
| 1.01-2.0   | 7         | 9.59%   |
| 0.51-1.0   | 6         | 8.22%   |
| 5.01-6.0   | 1         | 1.37%   |
| 3.01-4.0   | 1         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 23.29%  |
| Chimei Innolux      | 15        | 20.55%  |
| BOE                 | 12        | 16.44%  |
| LG Display          | 11        | 15.07%  |
| Samsung Electronics | 2         | 2.74%   |
| PANDA               | 2         | 2.74%   |
| Hewlett-Packard     | 2         | 2.74%   |
| Apple               | 2         | 2.74%   |
| AOC                 | 2         | 2.74%   |
| STD                 | 1         | 1.37%   |
| Philips             | 1         | 1.37%   |
| Panasonic           | 1         | 1.37%   |
| LG Philips          | 1         | 1.37%   |
| Lenovo              | 1         | 1.37%   |
| InnoLux Display     | 1         | 1.37%   |
| Iiyama              | 1         | 1.37%   |
| CHR                 | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 4.11%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 4.11%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch         | 2         | 2.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 2.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 2.74%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                        | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                     | 1         | 1.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1         | 1.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.37%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 1         | 1.37%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 1         | 1.37%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch     | 1         | 1.37%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1         | 1.37%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                | 1         | 1.37%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch     | 1         | 1.37%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch     | 1         | 1.37%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 1.37%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 27        | 38.03%  |
| 1366x768 (WXGA)   | 24        | 33.8%   |
| 2160x1440         | 3         | 4.23%   |
| 1600x900 (HD+)    | 3         | 4.23%   |
| 2560x1440 (QHD)   | 2         | 2.82%   |
| 1920x1200 (WUXGA) | 2         | 2.82%   |
| 1280x800 (WXGA)   | 2         | 2.82%   |
| 1024x600          | 2         | 2.82%   |
| 3840x2160 (4K)    | 1         | 1.41%   |
| 3440x1440         | 1         | 1.41%   |
| 2560x1600         | 1         | 1.41%   |
| 2256x1504         | 1         | 1.41%   |
| 1360x768          | 1         | 1.41%   |
| 1280x720 (HD)     | 1         | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 42.47%  |
| 13      | 12        | 16.44%  |
| 14      | 11        | 15.07%  |
| 12      | 3         | 4.11%   |
| 24      | 2         | 2.74%   |
| 23      | 2         | 2.74%   |
| 11      | 2         | 2.74%   |
| 10      | 2         | 2.74%   |
| 84      | 1         | 1.37%   |
| 39      | 1         | 1.37%   |
| 34      | 1         | 1.37%   |
| 33      | 1         | 1.37%   |
| 18      | 1         | 1.37%   |
| 17      | 1         | 1.37%   |
| 8       | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 63.01%  |
| 201-300     | 15        | 20.55%  |
| 501-600     | 4         | 5.48%   |
| 701-800     | 2         | 2.74%   |
| 801-900     | 1         | 1.37%   |
| 401-500     | 1         | 1.37%   |
| 351-400     | 1         | 1.37%   |
| 1501-2000   | 1         | 1.37%   |
| 101-200     | 1         | 1.37%   |
| Unknown     | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 83.82%  |
| 16/10 | 6         | 8.82%   |
| 3/2   | 4         | 5.88%   |
| 21/9  | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 42.47%  |
| 81-90          | 18        | 24.66%  |
| 71-80          | 5         | 6.85%   |
| 61-70          | 3         | 4.11%   |
| 51-60          | 2         | 2.74%   |
| 351-500        | 2         | 2.74%   |
| 41-50          | 2         | 2.74%   |
| 251-300        | 2         | 2.74%   |
| 201-250        | 2         | 2.74%   |
| More than 1000 | 1         | 1.37%   |
| 1-40           | 1         | 1.37%   |
| 141-150        | 1         | 1.37%   |
| 131-140        | 1         | 1.37%   |
| 501-1000       | 1         | 1.37%   |
| Unknown        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 29        | 39.73%  |
| 101-120 | 23        | 31.51%  |
| 51-100  | 11        | 15.07%  |
| 161-240 | 9         | 12.33%  |
| Unknown | 1         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 81.43%  |
| 2     | 11        | 15.71%  |
| 0     | 2         | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 39.18%  |
| Intel                            | 25        | 25.77%  |
| Qualcomm Atheros                 | 15        | 15.46%  |
| Broadcom                         | 6         | 6.19%   |
| Sierra Wireless                  | 3         | 3.09%   |
| Broadcom Limited                 | 3         | 3.09%   |
| Cypress Semiconductor            | 2         | 2.06%   |
| Xiaomi                           | 1         | 1.03%   |
| TP-Link                          | 1         | 1.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.03%   |
| Ralink Technology                | 1         | 1.03%   |
| Ralink                           | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 19.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.5%    |
| Intel Wi-Fi 6 AX200                                               | 7         | 5.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 4.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.25%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.25%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.63%   |
| Intel Wireless 8260                                               | 2         | 1.63%   |
| Intel Wireless 7260                                               | 2         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.63%   |
| Cypress K38231_03                                                 | 2         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.81%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.81%   |
| Sierra Wireless EM7455                                            | 1         | 0.81%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.81%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.81%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.81%   |
| Intel Wireless-AC 9260                                            | 1         | 0.81%   |
| Intel WiFi Link 5100                                              | 1         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 35.71%  |
| Realtek Semiconductor | 19        | 27.14%  |
| Qualcomm Atheros      | 14        | 20%     |
| Broadcom              | 4         | 5.71%   |
| Sierra Wireless       | 3         | 4.29%   |
| Broadcom Limited      | 3         | 4.29%   |
| Ralink Technology     | 1         | 1.43%   |
| Ralink                | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7         | 10%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 5.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 5.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 5.71%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.71%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 4.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 4.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.86%   |
| Intel Wireless 8260                                            | 2         | 2.86%   |
| Intel Wireless 7260                                            | 2         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.86%   |
| Sierra Wireless EM7455                                         | 1         | 1.43%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.43%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.43%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 1.43%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.43%   |
| Intel Wireless-AC 9260                                         | 1         | 1.43%   |
| Intel WiFi Link 5100                                           | 1         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.43%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.43%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.43%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.43%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.43%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 33        | 62.26%  |
| Intel                            | 10        | 18.87%  |
| Broadcom                         | 3         | 5.66%   |
| Qualcomm Atheros                 | 2         | 3.77%   |
| Cypress Semiconductor            | 2         | 3.77%   |
| Xiaomi                           | 1         | 1.89%   |
| TP-Link                          | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 45.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 15.09%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| Cypress K38231_03                                                 | 2         | 3.77%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.89%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.89%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.89%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 55.93%  |
| Ethernet | 52        | 44.07%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 85.71%  |
| Ethernet | 10        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 64.29%  |
| 1     | 20        | 28.57%  |
| 0     | 4         | 5.71%   |
| 3     | 1         | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 90.28%  |
| Yes  | 7         | 9.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 38.6%   |
| Realtek Semiconductor           | 12        | 21.05%  |
| Lite-On Technology              | 6         | 10.53%  |
| Qualcomm Atheros Communications | 3         | 5.26%   |
| IMC Networks                    | 3         | 5.26%   |
| Broadcom                        | 3         | 5.26%   |
| Realtek                         | 2         | 3.51%   |
| Foxconn / Hon Hai               | 2         | 3.51%   |
| Cambridge Silicon Radio         | 2         | 3.51%   |
| Dell                            | 1         | 1.75%   |
| Apple                           | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 14.04%  |
| Realtek Bluetooth Radio                             | 7         | 12.28%  |
| Intel AX200 Bluetooth                               | 7         | 12.28%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 7.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 5.26%   |
| Realtek Bluetooth Radio                             | 2         | 3.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.51%   |
| Intel AX201 Bluetooth                               | 2         | 3.51%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.75%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.75%   |
| Intel AX210 Bluetooth                               | 1         | 1.75%   |
| IMC Networks Bluetooth Device                       | 1         | 1.75%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.75%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.75%   |
| Broadcom HP Portable Valentine                      | 1         | 1.75%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.75%   |
| Apple Bluetooth Host Controller                     | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 56.58%  |
| AMD                              | 23        | 30.26%  |
| Nvidia                           | 6         | 7.89%   |
| Texas Instruments                | 2         | 2.63%   |
| Silicon Integrated Systems [SiS] | 1         | 1.32%   |
| Creative Technology              | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 11.54%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 6.73%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 6.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.85%   |
| AMD High Definition Audio Controller                                                              | 4         | 3.85%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 3.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.88%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.92%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.92%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.96%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.96%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.96%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 18        | 30%     |
| Samsung Electronics | 18        | 30%     |
| Micron Technology   | 8         | 13.33%  |
| Kingston            | 5         | 8.33%   |
| Unknown             | 4         | 6.67%   |
| A-DATA Technology   | 3         | 5%      |
| Transcend           | 1         | 1.67%   |
| Elpida              | 1         | 1.67%   |
| Corsair             | 1         | 1.67%   |
| 48spaces            | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 3         | 4.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 2         | 3.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 3.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 3.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 3.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 3.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 3.08%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 2         | 3.08%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                | 1         | 1.54%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DDR2                              | 1         | 1.54%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s            | 1         | 1.54%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.54%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.54%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s       | 1         | 1.54%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.54%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 1.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 1         | 1.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.54%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s          | 1         | 1.54%   |
| Samsung RAM K4EBE304EB-EGCF 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.54%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s            | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 24        | 46.15%  |
| DDR4   | 22        | 42.31%  |
| LPDDR4 | 3         | 5.77%   |
| DDR2   | 2         | 3.85%   |
| LPDDR3 | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 94.12%  |
| Row Of Chips | 2         | 3.92%   |
| DIMM         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 39.66%  |
| 4096  | 23        | 39.66%  |
| 2048  | 5         | 8.62%   |
| 16384 | 4         | 6.9%    |
| 1024  | 2         | 3.45%   |
| 512   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 33.33%  |
| 2667    | 13        | 24.07%  |
| 3200    | 7         | 12.96%  |
| 1334    | 3         | 5.56%   |
| 1333    | 3         | 5.56%   |
| 2400    | 2         | 3.7%    |
| 2133    | 2         | 3.7%    |
| 4266    | 1         | 1.85%   |
| 3733    | 1         | 1.85%   |
| 1867    | 1         | 1.85%   |
| 667     | 1         | 1.85%   |
| 533     | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

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
| Chicony Electronics                    | 20        | 31.25%  |
| IMC Networks                           | 12        | 18.75%  |
| Microdia                               | 7         | 10.94%  |
| Realtek Semiconductor                  | 6         | 9.38%   |
| Quanta                                 | 5         | 7.81%   |
| Acer                                   | 5         | 7.81%   |
| Sunplus Innovation Technology          | 3         | 4.69%   |
| Suyin                                  | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.13%   |
| Silicon Motion                         | 1         | 1.56%   |
| Logitech                               | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 6         | 9.23%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 6.15%   |
| Quanta HD User Facing                         | 3         | 4.62%   |
| Suyin HP TrueVision HD                        | 2         | 3.08%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 3.08%   |
| Realtek USB Camera                            | 2         | 3.08%   |
| Microdia HP Integrated Webcam                 | 2         | 3.08%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 3.08%   |
| IMC Networks HD Camera                        | 2         | 3.08%   |
| Chicony USB 2.0 Camera                        | 2         | 3.08%   |
| Chicony HP TrueVision HD Camera               | 2         | 3.08%   |
| Chicony HD WebCam                             | 2         | 3.08%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.54%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.54%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.54%   |
| Realtek Laptop Camera                         | 1         | 1.54%   |
| Realtek Integrated Webcam HD                  | 1         | 1.54%   |
| Realtek HD WebCam                             | 1         | 1.54%   |
| Quanta VGA WebCam                             | 1         | 1.54%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.54%   |
| Microdia Webcam Vitade AF                     | 1         | 1.54%   |
| Microdia Webcam                               | 1         | 1.54%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.54%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.54%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.54%   |
| Logitech C505 HD Webcam                       | 1         | 1.54%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.54%   |
| IMC Networks Integrated Camera                | 1         | 1.54%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.54%   |
| IMC Networks EasyCamera                       | 1         | 1.54%   |
| Chicony WebCam                                | 1         | 1.54%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.54%   |
| Chicony USB2.0 Camera                         | 1         | 1.54%   |
| Chicony USB 5M WebCam                         | 1         | 1.54%   |
| Chicony thinkpad t430s camera                 | 1         | 1.54%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.54%   |
| Chicony HP Wide Vision HD Camera              | 1         | 1.54%   |
| Chicony HD WebCam (Acer)                      | 1         | 1.54%   |
| Chicony HD User Facing                        | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 50%     |
| Validity Sensors           | 3         | 37.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 3         | 37.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 37.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 75%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 75%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 53        | 74.65%  |
| 1     | 13        | 18.31%  |
| 2     | 4         | 5.63%   |
| 3     | 1         | 1.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 34.78%  |
| Chipcard              | 4         | 17.39%  |
| Net/wireless          | 3         | 13.04%  |
| Multimedia controller | 2         | 8.7%    |
| Graphics card         | 2         | 8.7%    |
| Camera                | 2         | 8.7%    |
| Sound                 | 1         | 4.35%   |
| Net/ethernet          | 1         | 4.35%   |


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

Total: 91

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X201 3680BR4       | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
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
| Void Linux Rolling | 46        | 62.16%  |
| Void Linux         | 28        | 37.84%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 73        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 5         | 6.49%   |
| 5.8.18_1    | 3         | 3.9%    |
| 5.8.12_1    | 3         | 3.9%    |
| 5.3.9_1     | 3         | 3.9%    |
| 5.18.19_1   | 3         | 3.9%    |
| 5.10.17_1   | 3         | 3.9%    |
| 5.4.24_1    | 2         | 2.6%    |
| 5.19.16_1   | 2         | 2.6%    |
| 5.18.14_1   | 2         | 2.6%    |
| 5.16.20_1   | 2         | 2.6%    |
| 5.15.32_1   | 2         | 2.6%    |
| 5.13.13_1   | 2         | 2.6%    |
| 5.12.10_1   | 2         | 2.6%    |
| 5.9.16_1    | 1         | 1.3%    |
| 5.9.14_1    | 1         | 1.3%    |
| 5.9.0-rc8_2 | 1         | 1.3%    |
| 5.8.9_1     | 1         | 1.3%    |
| 5.8.8_1     | 1         | 1.3%    |
| 5.8.7_1     | 1         | 1.3%    |
| 5.8.6_1     | 1         | 1.3%    |
| 5.8.12_2    | 1         | 1.3%    |
| 5.7.16_1    | 1         | 1.3%    |
| 5.4.35_1    | 1         | 1.3%    |
| 5.4.21_1    | 1         | 1.3%    |
| 5.4.13_2    | 1         | 1.3%    |
| 5.2.13_1    | 1         | 1.3%    |
| 5.18.7_1    | 1         | 1.3%    |
| 5.15.6_1    | 1         | 1.3%    |
| 5.15.45_1   | 1         | 1.3%    |
| 5.15.41_1   | 1         | 1.3%    |
| 5.15.28_1   | 1         | 1.3%    |
| 5.15.26_1   | 1         | 1.3%    |
| 5.15.22_1   | 1         | 1.3%    |
| 5.15.17_1   | 1         | 1.3%    |
| 5.15.16_1   | 1         | 1.3%    |
| 5.15.14_1   | 1         | 1.3%    |
| 5.15.12_1   | 1         | 1.3%    |
| 5.14.0_1    | 1         | 1.3%    |
| 5.13.18_1   | 1         | 1.3%    |
| 5.13.15_1   | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.19 | 5         | 6.49%   |
| 5.8.12  | 4         | 5.19%   |
| 5.8.18  | 3         | 3.9%    |
| 5.3.9   | 3         | 3.9%    |
| 5.18.19 | 3         | 3.9%    |
| 5.10.17 | 3         | 3.9%    |
| 5.4.24  | 2         | 2.6%    |
| 5.19.16 | 2         | 2.6%    |
| 5.18.14 | 2         | 2.6%    |
| 5.16.20 | 2         | 2.6%    |
| 5.15.32 | 2         | 2.6%    |
| 5.13.13 | 2         | 2.6%    |
| 5.12.10 | 2         | 2.6%    |
| 5.9.16  | 1         | 1.3%    |
| 5.9.14  | 1         | 1.3%    |
| 5.9.0   | 1         | 1.3%    |
| 5.8.9   | 1         | 1.3%    |
| 5.8.8   | 1         | 1.3%    |
| 5.8.7   | 1         | 1.3%    |
| 5.8.6   | 1         | 1.3%    |
| 5.7.16  | 1         | 1.3%    |
| 5.4.35  | 1         | 1.3%    |
| 5.4.21  | 1         | 1.3%    |
| 5.4.13  | 1         | 1.3%    |
| 5.2.13  | 1         | 1.3%    |
| 5.18.7  | 1         | 1.3%    |
| 5.15.6  | 1         | 1.3%    |
| 5.15.45 | 1         | 1.3%    |
| 5.15.41 | 1         | 1.3%    |
| 5.15.28 | 1         | 1.3%    |
| 5.15.26 | 1         | 1.3%    |
| 5.15.22 | 1         | 1.3%    |
| 5.15.17 | 1         | 1.3%    |
| 5.15.16 | 1         | 1.3%    |
| 5.15.14 | 1         | 1.3%    |
| 5.15.12 | 1         | 1.3%    |
| 5.14.0  | 1         | 1.3%    |
| 5.13.18 | 1         | 1.3%    |
| 5.13.15 | 1         | 1.3%    |
| 5.13.12 | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 15.79%  |
| 5.8     | 11        | 14.47%  |
| 5.13    | 11        | 14.47%  |
| 5.12    | 7         | 9.21%   |
| 5.10    | 7         | 9.21%   |
| 5.18    | 6         | 7.89%   |
| 5.4     | 5         | 6.58%   |
| 5.9     | 3         | 3.95%   |
| 5.3     | 3         | 3.95%   |
| 5.19    | 2         | 2.63%   |
| 5.16    | 2         | 2.63%   |
| 5.7     | 1         | 1.32%   |
| 5.2     | 1         | 1.32%   |
| 5.14    | 1         | 1.32%   |
| 5.11    | 1         | 1.32%   |
| 5.1     | 1         | 1.32%   |
| 4.4     | 1         | 1.32%   |
| 4.14    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 68        | 93.15%  |
| i686    | 3         | 4.11%   |
| aarch64 | 2         | 2.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 46.05%  |
| XFCE       | 9         | 11.84%  |
| KDE        | 8         | 10.53%  |
| MATE       | 6         | 7.89%   |
| KDE5       | 4         | 5.26%   |
| i3         | 4         | 5.26%   |
| GNOME      | 3         | 3.95%   |
| bspwm      | 2         | 2.63%   |
| X-Cinnamon | 1         | 1.32%   |
| river      | 1         | 1.32%   |
| openbox    | 1         | 1.32%   |
| Lumina     | 1         | 1.32%   |
| awesome    | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 67.57%  |
| Tty     | 10        | 13.51%  |
| Wayland | 8         | 10.81%  |
| Unknown | 6         | 8.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 89.19%  |
| SDDM    | 3         | 4.05%   |
| LXDM    | 3         | 4.05%   |
| LightDM | 2         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 42        | 56%     |
| Unknown | 9         | 12%     |
| en_GB   | 5         | 6.67%   |
| en_DK   | 4         | 5.33%   |
| it_IT   | 2         | 2.67%   |
| de_DE   | 2         | 2.67%   |
| tr_TR   | 1         | 1.33%   |
| ru_UA   | 1         | 1.33%   |
| ru_RU   | 1         | 1.33%   |
| pt_BR   | 1         | 1.33%   |
| nb_NO   | 1         | 1.33%   |
| es_HN   | 1         | 1.33%   |
| es_ES   | 1         | 1.33%   |
| es_DO   | 1         | 1.33%   |
| en_NZ   | 1         | 1.33%   |
| en_CA   | 1         | 1.33%   |
| en_AU   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 42        | 56.76%  |
| BIOS | 32        | 43.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 64.86%  |
| Btrfs   | 16        | 21.62%  |
| Unknown | 4         | 5.41%   |
| Xfs     | 3         | 4.05%   |
| Zfs     | 1         | 1.35%   |
| F2fs    | 1         | 1.35%   |
| Ext3    | 1         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 43        | 57.33%  |
| Unknown | 20        | 26.67%  |
| MBR     | 12        | 16%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 89.04%  |
| Yes       | 8         | 10.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 82.19%  |
| Yes       | 13        | 17.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 21.92%  |
| Acer                | 12        | 16.44%  |
| ASUSTek Computer    | 11        | 15.07%  |
| Hewlett-Packard     | 10        | 13.7%   |
| Dell                | 8         | 10.96%  |
| HUAWEI              | 2         | 2.74%   |
| Unknown             | 2         | 2.74%   |
| Samsung Electronics | 1         | 1.37%   |
| Positivo            | 1         | 1.37%   |
| Pine Microsystems   | 1         | 1.37%   |
| Notebook            | 1         | 1.37%   |
| Nokia               | 1         | 1.37%   |
| MSI                 | 1         | 1.37%   |
| Getac               | 1         | 1.37%   |
| Framework           | 1         | 1.37%   |
| Exo                 | 1         | 1.37%   |
| Digibras            | 1         | 1.37%   |
| Chuwi               | 1         | 1.37%   |
| Apple               | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Laptop 15-bw0xx                    | 2         | 2.74%   |
| Acer Swift SF314-42                   | 2         | 2.74%   |
| Unknown                               | 2         | 2.74%   |
| Samsung 275E4E/275E5E                 | 1         | 1.37%   |
| Positivo Mobile                       | 1         | 1.37%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 1.37%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 1.37%   |
| Nokia Booklet 3G                      | 1         | 1.37%   |
| MSI Bravo 15 A4DDR                    | 1         | 1.37%   |
| Lenovo ThinkPad X260 20F5S08Q00       | 1         | 1.37%   |
| Lenovo ThinkPad X240 20AMA34HMN       | 1         | 1.37%   |
| Lenovo ThinkPad X201 3680BR4          | 1         | 1.37%   |
| Lenovo ThinkPad T480 20L6SA5Q00       | 1         | 1.37%   |
| Lenovo ThinkPad T460 20FMS0WN00       | 1         | 1.37%   |
| Lenovo ThinkPad T430 2349PS3          | 1         | 1.37%   |
| Lenovo ThinkPad T420 4236PG6          | 1         | 1.37%   |
| Lenovo ThinkPad T420 4180A21          | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW | 1         | 1.37%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00 | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200  | 1         | 1.37%   |
| Lenovo ThinkPad E595 20NFCTO1WW       | 1         | 1.37%   |
| Lenovo IdeaPad Z570 10246ZG           | 1         | 1.37%   |
| Lenovo IdeaPad S145-14IIL 81W6        | 1         | 1.37%   |
| Lenovo IdeaPad 710S-13IKB 80VQ        | 1         | 1.37%   |
| Lenovo G50-45 80E3                    | 1         | 1.37%   |
| HUAWEI KLVL-WXXW                      | 1         | 1.37%   |
| HUAWEI HN-WX9X                        | 1         | 1.37%   |
| HP Pavilion Notebook                  | 1         | 1.37%   |
| HP Pavilion Gaming Laptop 15-dk0xxx   | 1         | 1.37%   |
| HP Notebook                           | 1         | 1.37%   |
| HP Laptop 15s-eq2xxx                  | 1         | 1.37%   |
| HP Laptop 14-dk0xxx                   | 1         | 1.37%   |
| HP Laptop 14-bs0xx                    | 1         | 1.37%   |
| HP ENVY 6                             | 1         | 1.37%   |
| HP 15                                 | 1         | 1.37%   |
| Getac V110                            | 1         | 1.37%   |
| Framework Laptop                      | 1         | 1.37%   |
| Exo Exomate X352                      | 1         | 1.37%   |
| Digibras NH4CU03                      | 1         | 1.37%   |
| Dell XPS 15 9500                      | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 12        | 16.44%  |
| Acer Aspire              | 7         | 9.59%   |
| HP Laptop                | 5         | 6.85%   |
| ASUS VivoBook            | 4         | 5.48%   |
| Lenovo IdeaPad           | 3         | 4.11%   |
| Dell Inspiron            | 3         | 4.11%   |
| HP Pavilion              | 2         | 2.74%   |
| Dell Latitude            | 2         | 2.74%   |
| Acer Swift               | 2         | 2.74%   |
| Unknown                  | 2         | 2.74%   |
| Samsung 275E4E           | 1         | 1.37%   |
| Positivo Mobile          | 1         | 1.37%   |
| Pine Microsystems Pine64 | 1         | 1.37%   |
| Notebook NV4XMB          | 1         | 1.37%   |
| Nokia Booklet            | 1         | 1.37%   |
| MSI Bravo                | 1         | 1.37%   |
| Lenovo G50-45            | 1         | 1.37%   |
| HUAWEI KLVL-WXXW         | 1         | 1.37%   |
| HUAWEI HN-WX9X           | 1         | 1.37%   |
| HP Notebook              | 1         | 1.37%   |
| HP ENVY                  | 1         | 1.37%   |
| HP 15                    | 1         | 1.37%   |
| Getac V110               | 1         | 1.37%   |
| Framework Laptop         | 1         | 1.37%   |
| Exo Exomate              | 1         | 1.37%   |
| Digibras NH4CU03         | 1         | 1.37%   |
| Dell XPS                 | 1         | 1.37%   |
| Dell Precision           | 1         | 1.37%   |
| Dell G3                  | 1         | 1.37%   |
| Chuwi GemiBook           | 1         | 1.37%   |
| ASUS X751LD              | 1         | 1.37%   |
| ASUS X555UJ              | 1         | 1.37%   |
| ASUS X555LD              | 1         | 1.37%   |
| ASUS X510UAR             | 1         | 1.37%   |
| ASUS X455LF              | 1         | 1.37%   |
| ASUS TUF                 | 1         | 1.37%   |
| ASUS ASUS                | 1         | 1.37%   |
| Apple MacBookPro11       | 1         | 1.37%   |
| Acer Nitro               | 1         | 1.37%   |
| Acer AOA150              | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 12        | 16.44%  |
| 2020    | 10        | 13.7%   |
| 2016    | 7         | 9.59%   |
| 2014    | 6         | 8.22%   |
| 2018    | 5         | 6.85%   |
| 2015    | 5         | 6.85%   |
| 2013    | 5         | 6.85%   |
| 2017    | 4         | 5.48%   |
| 2011    | 4         | 5.48%   |
| 2021    | 3         | 4.11%   |
| 2012    | 3         | 4.11%   |
| 2010    | 2         | 2.74%   |
| 2009    | 2         | 2.74%   |
| 2008    | 2         | 2.74%   |
| Unknown | 2         | 2.74%   |
| 2006    | 1         | 1.37%   |

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
| Disabled | 73        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 31.08%  |
| 3.01-4.0    | 18        | 24.32%  |
| 8.01-16.0   | 13        | 17.57%  |
| 16.01-24.0  | 7         | 9.46%   |
| 1.01-2.0    | 5         | 6.76%   |
| 32.01-64.0  | 4         | 5.41%   |
| 0.51-1.0    | 2         | 2.7%    |
| 24.01-32.0  | 1         | 1.35%   |
| 64.01-256.0 | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 29        | 37.66%  |
| 2.01-3.0   | 17        | 22.08%  |
| 0.51-1.0   | 14        | 18.18%  |
| 4.01-8.0   | 6         | 7.79%   |
| 3.01-4.0   | 6         | 7.79%   |
| 0.01-0.5   | 3         | 3.9%    |
| 16.01-24.0 | 1         | 1.3%    |
| 8.01-16.0  | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 78.08%  |
| 2      | 13        | 17.81%  |
| 3      | 2         | 2.74%   |
| 0      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 73.97%  |
| Yes       | 19        | 26.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 73.97%  |
| No        | 19        | 26.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 94.52%  |
| No        | 4         | 5.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 78.08%  |
| No        | 16        | 21.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 10        | 13.7%   |
| India              | 8         | 10.96%  |
| Russia             | 6         | 8.22%   |
| Germany            | 6         | 8.22%   |
| Ukraine            | 4         | 5.48%   |
| Denmark            | 4         | 5.48%   |
| Brazil             | 4         | 5.48%   |
| Switzerland        | 3         | 4.11%   |
| UK                 | 2         | 2.74%   |
| Turkey             | 2         | 2.74%   |
| Netherlands        | 2         | 2.74%   |
| Morocco            | 2         | 2.74%   |
| Italy              | 2         | 2.74%   |
| Bulgaria           | 2         | 2.74%   |
| Vietnam            | 1         | 1.37%   |
| Spain              | 1         | 1.37%   |
| Peru               | 1         | 1.37%   |
| Norway             | 1         | 1.37%   |
| New Zealand        | 1         | 1.37%   |
| Mexico             | 1         | 1.37%   |
| Indonesia          | 1         | 1.37%   |
| Honduras           | 1         | 1.37%   |
| Greece             | 1         | 1.37%   |
| France             | 1         | 1.37%   |
| Ecuador            | 1         | 1.37%   |
| Dominican Republic | 1         | 1.37%   |
| Czechia            | 1         | 1.37%   |
| Canada             | 1         | 1.37%   |
| Australia          | 1         | 1.37%   |
| Argentina          | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 3         | 4.05%   |
| St Petersburg | 2         | 2.7%    |
| Rome          | 2         | 2.7%    |
| Meknes        | 2         | 2.7%    |
| Hyderabad     | 2         | 2.7%    |
| Geneva        | 2         | 2.7%    |
| Yambol        | 1         | 1.35%   |
| Weatherford   | 1         | 1.35%   |
| Vlaardingen   | 1         | 1.35%   |
| Viby J        | 1         | 1.35%   |
| Trujillo      | 1         | 1.35%   |
| Toulouse      | 1         | 1.35%   |
| Toms River    | 1         | 1.35%   |
| Tegucigalpa   | 1         | 1.35%   |
| Syktyvkar     | 1         | 1.35%   |
| Surabaya      | 1         | 1.35%   |
| Stratford     | 1         | 1.35%   |
| Solone        | 1         | 1.35%   |
| Sofia         | 1         | 1.35%   |
| Sistranda     | 1         | 1.35%   |
| Saxtons River | 1         | 1.35%   |
| Sao Paulo     | 1         | 1.35%   |
| Santo Domingo | 1         | 1.35%   |
| Rostock       | 1         | 1.35%   |
| Rosenheim     | 1         | 1.35%   |
| Regensburg    | 1         | 1.35%   |
| Pune          | 1         | 1.35%   |
| Prague        | 1         | 1.35%   |
| Porto Alegre  | 1         | 1.35%   |
| Pliening      | 1         | 1.35%   |
| Phoenix       | 1         | 1.35%   |
| Odense        | 1         | 1.35%   |
| New Delhi     | 1         | 1.35%   |
| Mossoro       | 1         | 1.35%   |
| Milford       | 1         | 1.35%   |
| Melbourne     | 1         | 1.35%   |
| Matos Costa   | 1         | 1.35%   |
| Los Angeles   | 1         | 1.35%   |
| Lakewood      | 1         | 1.35%   |
| Kremenchug    | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 20     | 22.35%  |
| Seagate             | 15        | 16     | 17.65%  |
| WDC                 | 11        | 12     | 12.94%  |
| Unknown             | 6         | 10     | 7.06%   |
| Toshiba             | 5         | 5      | 5.88%   |
| Intel               | 5         | 6      | 5.88%   |
| HGST                | 5         | 6      | 5.88%   |
| SanDisk             | 4         | 5      | 4.71%   |
| Kingston            | 3         | 3      | 3.53%   |
| SK hynix            | 2         | 2      | 2.35%   |
| Hitachi             | 2         | 2      | 2.35%   |
| Transcend           | 1         | 1      | 1.18%   |
| Phison              | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| Lenovo              | 1         | 1      | 1.18%   |
| Crucial             | 1         | 1      | 1.18%   |
| China               | 1         | 1      | 1.18%   |
| BHT                 | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 4         | 4.55%   |
| Toshiba MQ01ABF050 500GB                | 3         | 3.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 3.41%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 2.27%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 2.27%   |
| Samsung SSD 870 EVO 500GB               | 2         | 2.27%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 2.27%   |
| HGST HTS545050A7E680 500GB              | 2         | 2.27%   |
| HGST HTS541010B7E610 1TB                | 2         | 2.27%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 1.14%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 1.14%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1.14%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 1.14%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 1.14%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1.14%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 1.14%   |
| WDC WD Elements 512GB                   | 1         | 1.14%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 1.14%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 1.14%   |
| Unknown USB DISK 3.2 250GB              | 1         | 1.14%   |
| Unknown SD512  512MB                    | 1         | 1.14%   |
| Unknown SD16G  16GB                     | 1         | 1.14%   |
| Unknown MMC Card  8GB                   | 1         | 1.14%   |
| Unknown MMC Card  32GB                  | 1         | 1.14%   |
| Unknown MMC Card  128GB                 | 1         | 1.14%   |
| Unknown MMC Card                        | 1         | 1.14%   |
| Unknown CWBC3R  64GB                    | 1         | 1.14%   |
| Transcend TS128GMTS800 128GB SSD        | 1         | 1.14%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.14%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 1.14%   |
| Seagate ST98823AS 80GB                  | 1         | 1.14%   |
| Seagate ST9750420AS 752GB               | 1         | 1.14%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1.14%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.14%   |
| Seagate Expansion Desk 8TB              | 1         | 1.14%   |
| SanDisk SD9SN8W128G1102 128GB SSD       | 1         | 1.14%   |
| SanDisk SD9SN8W128G 128GB SSD           | 1         | 1.14%   |
| SanDisk SD8SN8U1T001122 1TB SSD         | 1         | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 42.86%  |
| WDC                 | 8         | 8      | 22.86%  |
| HGST                | 5         | 6      | 14.29%  |
| Toshiba             | 4         | 4      | 11.43%  |
| Hitachi             | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 38.1%   |
| SanDisk             | 3         | 3      | 14.29%  |
| Kingston            | 2         | 2      | 9.52%   |
| Transcend           | 1         | 1      | 4.76%   |
| Patriot             | 1         | 1      | 4.76%   |
| Lenovo              | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |
| BHT                 | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 34        | 37     | 41.46%  |
| NVMe    | 21        | 26     | 25.61%  |
| SSD     | 20        | 21     | 24.39%  |
| MMC     | 5         | 8      | 6.1%    |
| Unknown | 2         | 3      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 57     | 62.82%  |
| NVMe | 21        | 26     | 26.92%  |
| MMC  | 5         | 8      | 6.41%   |
| SAS  | 3         | 4      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 37     | 60.38%  |
| 0.51-1.0   | 20        | 20     | 37.74%  |
| 4.01-10.0  | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 28%     |
| 501-1000       | 18        | 24%     |
| 101-250        | 15        | 20%     |
| Unknown        | 7         | 9.33%   |
| 1-20           | 4         | 5.33%   |
| 21-50          | 3         | 4%      |
| 1001-2000      | 3         | 4%      |
| 51-100         | 3         | 4%      |
| More than 3000 | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 25.33%  |
| 101-250        | 18        | 24%     |
| 21-50          | 15        | 20%     |
| 51-100         | 9         | 12%     |
| Unknown        | 7         | 9.33%   |
| 251-500        | 5         | 6.67%   |
| More than 3000 | 1         | 1.33%   |
| 1001-2000      | 1         | 1.33%   |

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
| Works    | 42        | 51     | 53.16%  |
| Detected | 26        | 33     | 32.91%  |
| Malfunc  | 11        | 11     | 13.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 42        | 52.5%   |
| AMD                              | 18        | 22.5%   |
| Samsung Electronics              | 11        | 13.75%  |
| SanDisk                          | 3         | 3.75%   |
| SK hynix                         | 2         | 2.5%    |
| Toshiba America Info Systems     | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] | 1         | 1.25%   |
| Phison Electronics               | 1         | 1.25%   |
| Kingston Technology Company      | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 19.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 10.84%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 7.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 7.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 6.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 4.82%   |
| Intel SSD 660P Series                                                            | 3         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.61%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 2.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.41%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.41%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.2%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.2%    |
| Samsung Apple PCIe SSD                                                           | 1         | 1.2%    |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.2%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.2%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 1.2%    |
| Intel Non-Volatile memory controller                                             | 1         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.2%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.2%    |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.2%    |
| AMD SB600 IDE                                                                    | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 62.96%  |
| NVMe | 21        | 25.93%  |
| RAID | 5         | 6.17%   |
| IDE  | 4         | 4.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 65.75%  |
| AMD    | 23        | 31.51%  |
| ARM    | 2         | 2.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.74%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.74%   |
| ARM Processor                                 | 2         | 2.74%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.74%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 2.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.37%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.37%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.37%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.37%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.37%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.37%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.37%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.37%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.37%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.37%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.37%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz          | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 24.66%  |
| Intel Core i7           | 9         | 12.33%  |
| Intel Core i3           | 8         | 10.96%  |
| Other                   | 7         | 9.59%   |
| Intel Atom              | 5         | 6.85%   |
| AMD Ryzen 7             | 5         | 6.85%   |
| AMD Ryzen 5             | 5         | 6.85%   |
| Intel Celeron           | 3         | 4.11%   |
| AMD Ryzen 7 PRO         | 2         | 2.74%   |
| AMD A8                  | 2         | 2.74%   |
| Intel Pentium           | 1         | 1.37%   |
| Intel Genuine           | 1         | 1.37%   |
| Intel Core 2 Duo        | 1         | 1.37%   |
| AMD Turion 64 X2 Mobile | 1         | 1.37%   |
| AMD Ryzen 3             | 1         | 1.37%   |
| AMD E2                  | 1         | 1.37%   |
| AMD E1                  | 1         | 1.37%   |
| AMD C-60                | 1         | 1.37%   |
| AMD A4                  | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 46.58%  |
| 4      | 24        | 32.88%  |
| 6      | 6         | 8.22%   |
| 8      | 5         | 6.85%   |
| 1      | 4         | 5.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 98.63%  |
| 2      | 1         | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 50        | 68.49%  |
| 1      | 23        | 31.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 89.04%  |
| Unknown        | 4         | 5.48%   |
| 64-bit         | 2         | 2.74%   |
| 32-bit         | 2         | 2.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 28%     |
| 0x40651    | 6         | 8%      |
| 0x306a9    | 4         | 5.33%   |
| 0x906ea    | 3         | 4%      |
| 0x806e9    | 3         | 4%      |
| 0x406e3    | 3         | 4%      |
| 0x206a7    | 3         | 4%      |
| 0x08600104 | 3         | 4%      |
| 0x08108102 | 3         | 4%      |
| 0x806ec    | 2         | 2.67%   |
| 0x30678    | 2         | 2.67%   |
| 0x106c2    | 2         | 2.67%   |
| 0x07030105 | 2         | 2.67%   |
| 0x06006705 | 2         | 2.67%   |
| 0x05000119 | 2         | 2.67%   |
| 0xa0652    | 1         | 1.33%   |
| 0x806eb    | 1         | 1.33%   |
| 0x806ea    | 1         | 1.33%   |
| 0x406c4    | 1         | 1.33%   |
| 0x306d4    | 1         | 1.33%   |
| 0x20652    | 1         | 1.33%   |
| 0x106ca    | 1         | 1.33%   |
| 0x08608103 | 1         | 1.33%   |
| 0x08608102 | 1         | 1.33%   |
| 0x08600106 | 1         | 1.33%   |
| 0x08600102 | 1         | 1.33%   |
| 0x08108109 | 1         | 1.33%   |
| 0x08101007 | 1         | 1.33%   |
| 0x07030104 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 17.81%  |
| Haswell       | 7         | 9.59%   |
| Zen 2         | 6         | 8.22%   |
| Skylake       | 5         | 6.85%   |
| Zen+          | 4         | 5.48%   |
| SandyBridge   | 4         | 5.48%   |
| IvyBridge     | 4         | 5.48%   |
| Excavator     | 4         | 5.48%   |
| Unknown       | 4         | 5.48%   |
| Silvermont    | 3         | 4.11%   |
| Puma          | 3         | 4.11%   |
| Bonnell       | 3         | 4.11%   |
| TigerLake     | 2         | 2.74%   |
| Bobcat        | 2         | 2.74%   |
| Zen           | 1         | 1.37%   |
| Westmere      | 1         | 1.37%   |
| Penryn        | 1         | 1.37%   |
| K8 Hammer     | 1         | 1.37%   |
| IceLake       | 1         | 1.37%   |
| Goldmont plus | 1         | 1.37%   |
| Core          | 1         | 1.37%   |
| CometLake     | 1         | 1.37%   |
| Broadwell     | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 47        | 51.65%  |
| AMD                              | 24        | 26.37%  |
| Nvidia                           | 19        | 20.88%  |
| Silicon Integrated Systems [SiS] | 1         | 1.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 7.45%   |
| AMD Renoir                                                                    | 6         | 6.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 5.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 4         | 4.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 4.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 4         | 4.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 4.26%   |
| Intel HD Graphics 620                                                         | 3         | 3.19%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 2.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.13%   |
| Intel UHD Graphics 620                                                        | 2         | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 2         | 2.13%   |
| AMD Lucienne                                                                  | 2         | 2.13%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.06%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.06%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 1.06%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                          | 1         | 1.06%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 1.06%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.06%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 1.06%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.06%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 1.06%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 1.06%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.06%   |
| Intel HD Graphics 5500                                                        | 1         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 39.73%  |
| 1 x AMD        | 19        | 26.03%  |
| Intel + Nvidia | 17        | 23.29%  |
| Other          | 2         | 2.74%   |
| 2 x AMD        | 2         | 2.74%   |
| AMD + Nvidia   | 2         | 2.74%   |
| 1 x SiS        | 1         | 1.37%   |
| Intel + AMD    | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 78.08%  |
| Proprietary | 13        | 17.81%  |
| Unknown     | 3         | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 63.16%  |
| 0.01-0.5   | 12        | 15.79%  |
| 1.01-2.0   | 7         | 9.21%   |
| 0.51-1.0   | 6         | 7.89%   |
| 3.01-4.0   | 2         | 2.63%   |
| 5.01-6.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 22.37%  |
| Chimei Innolux      | 15        | 19.74%  |
| LG Display          | 12        | 15.79%  |
| BOE                 | 12        | 15.79%  |
| Samsung Electronics | 2         | 2.63%   |
| PANDA               | 2         | 2.63%   |
| Lenovo              | 2         | 2.63%   |
| Hewlett-Packard     | 2         | 2.63%   |
| Apple               | 2         | 2.63%   |
| AOC                 | 2         | 2.63%   |
| STD                 | 1         | 1.32%   |
| Sharp               | 1         | 1.32%   |
| Philips             | 1         | 1.32%   |
| Panasonic           | 1         | 1.32%   |
| LG Philips          | 1         | 1.32%   |
| InnoLux Display     | 1         | 1.32%   |
| Iiyama              | 1         | 1.32%   |
| CHR                 | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 3.95%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 3.95%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch         | 2         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 2.63%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                        | 1         | 1.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                     | 1         | 1.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1         | 1.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.32%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 1         | 1.32%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 1         | 1.32%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch          | 1         | 1.32%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch              | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 1.32%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch     | 1         | 1.32%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1         | 1.32%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                | 1         | 1.32%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch     | 1         | 1.32%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 27        | 36.49%  |
| 1366x768 (WXGA)   | 24        | 32.43%  |
| 1600x900 (HD+)    | 4         | 5.41%   |
| 2160x1440         | 3         | 4.05%   |
| 1920x1200 (WUXGA) | 3         | 4.05%   |
| 1280x800 (WXGA)   | 3         | 4.05%   |
| 2560x1440 (QHD)   | 2         | 2.7%    |
| 1024x600          | 2         | 2.7%    |
| 3840x2160 (4K)    | 1         | 1.35%   |
| 3440x1440         | 1         | 1.35%   |
| 2560x1600         | 1         | 1.35%   |
| 2256x1504         | 1         | 1.35%   |
| 1360x768          | 1         | 1.35%   |
| 1280x720 (HD)     | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 32        | 42.11%  |
| 14      | 12        | 15.79%  |
| 13      | 12        | 15.79%  |
| 12      | 4         | 5.26%   |
| 24      | 2         | 2.63%   |
| 23      | 2         | 2.63%   |
| 11      | 2         | 2.63%   |
| 10      | 2         | 2.63%   |
| 84      | 1         | 1.32%   |
| 39      | 1         | 1.32%   |
| 34      | 1         | 1.32%   |
| 33      | 1         | 1.32%   |
| 18      | 1         | 1.32%   |
| 17      | 1         | 1.32%   |
| 8       | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 63.16%  |
| 201-300     | 16        | 21.05%  |
| 501-600     | 4         | 5.26%   |
| 701-800     | 2         | 2.63%   |
| 801-900     | 1         | 1.32%   |
| 401-500     | 1         | 1.32%   |
| 351-400     | 1         | 1.32%   |
| 1501-2000   | 1         | 1.32%   |
| 101-200     | 1         | 1.32%   |
| Unknown     | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 81.69%  |
| 16/10 | 7         | 9.86%   |
| 3/2   | 5         | 7.04%   |
| 21/9  | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 42.11%  |
| 81-90          | 19        | 25%     |
| 71-80          | 5         | 6.58%   |
| 61-70          | 4         | 5.26%   |
| 51-60          | 2         | 2.63%   |
| 351-500        | 2         | 2.63%   |
| 41-50          | 2         | 2.63%   |
| 251-300        | 2         | 2.63%   |
| 201-250        | 2         | 2.63%   |
| More than 1000 | 1         | 1.32%   |
| 1-40           | 1         | 1.32%   |
| 141-150        | 1         | 1.32%   |
| 131-140        | 1         | 1.32%   |
| 501-1000       | 1         | 1.32%   |
| Unknown        | 1         | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 32        | 42.11%  |
| 101-120 | 23        | 30.26%  |
| 51-100  | 11        | 14.47%  |
| 161-240 | 9         | 11.84%  |
| Unknown | 1         | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 82.19%  |
| 2     | 11        | 15.07%  |
| 0     | 2         | 2.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 38%     |
| Intel                            | 28        | 28%     |
| Qualcomm Atheros                 | 15        | 15%     |
| Broadcom                         | 6         | 6%      |
| Sierra Wireless                  | 3         | 3%      |
| Broadcom Limited                 | 3         | 3%      |
| Cypress Semiconductor            | 2         | 2%      |
| Xiaomi                           | 1         | 1%      |
| TP-Link                          | 1         | 1%      |
| Silicon Integrated Systems [SiS] | 1         | 1%      |
| Ralink Technology                | 1         | 1%      |
| Ralink                           | 1         | 1%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 18.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.25%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 5.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.13%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.56%   |
| Intel Wireless 8260                                               | 2         | 1.56%   |
| Intel Wireless 7260                                               | 2         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.56%   |
| Cypress K38231_03                                                 | 2         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.78%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 0.78%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.78%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.78%   |
| Intel Wireless-AC 9260                                            | 1         | 0.78%   |
| Intel WiFi Link 5100                                              | 1         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 38.36%  |
| Realtek Semiconductor | 19        | 26.03%  |
| Qualcomm Atheros      | 14        | 19.18%  |
| Broadcom              | 4         | 5.48%   |
| Sierra Wireless       | 3         | 4.11%   |
| Broadcom Limited      | 3         | 4.11%   |
| Ralink Technology     | 1         | 1.37%   |
| Ralink                | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7         | 9.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 6.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 5.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 5.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 5.48%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.48%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 4.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 4.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.74%   |
| Intel Wireless 8260                                            | 2         | 2.74%   |
| Intel Wireless 7260                                            | 2         | 2.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.74%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 1.37%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.37%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.37%   |
| Intel Wireless-AC 9260                                         | 1         | 1.37%   |
| Intel WiFi Link 5100                                           | 1         | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.37%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.37%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.37%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.37%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 33        | 60%     |
| Intel                            | 12        | 21.82%  |
| Broadcom                         | 3         | 5.45%   |
| Qualcomm Atheros                 | 2         | 3.64%   |
| Cypress Semiconductor            | 2         | 3.64%   |
| Xiaomi                           | 1         | 1.82%   |
| TP-Link                          | 1         | 1.82%   |
| Silicon Integrated Systems [SiS] | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 43.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 14.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.45%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.64%   |
| Cypress K38231_03                                                 | 2         | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.82%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.82%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.82%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 56.1%   |
| Ethernet | 54        | 43.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 86.3%   |
| Ethernet | 10        | 13.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 64.38%  |
| 1     | 21        | 28.77%  |
| 0     | 4         | 5.48%   |
| 3     | 1         | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 90.67%  |
| Yes  | 7         | 9.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 37.93%  |
| Realtek Semiconductor           | 12        | 20.69%  |
| Lite-On Technology              | 6         | 10.34%  |
| Broadcom                        | 4         | 6.9%    |
| Qualcomm Atheros Communications | 3         | 5.17%   |
| IMC Networks                    | 3         | 5.17%   |
| Realtek                         | 2         | 3.45%   |
| Foxconn / Hon Hai               | 2         | 3.45%   |
| Cambridge Silicon Radio         | 2         | 3.45%   |
| Dell                            | 1         | 1.72%   |
| Apple                           | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 13.79%  |
| Realtek Bluetooth Radio                             | 7         | 12.07%  |
| Intel AX200 Bluetooth                               | 7         | 12.07%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 6.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 5.17%   |
| Realtek Bluetooth Radio                             | 2         | 3.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.45%   |
| Intel AX201 Bluetooth                               | 2         | 3.45%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.72%   |
| Intel AX210 Bluetooth                               | 1         | 1.72%   |
| IMC Networks Bluetooth Device                       | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.72%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.72%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.72%   |
| Broadcom HP Portable Valentine                      | 1         | 1.72%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.72%   |
| Apple Bluetooth Host Controller                     | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 58.23%  |
| AMD                              | 23        | 29.11%  |
| Nvidia                           | 6         | 7.59%   |
| Texas Instruments                | 2         | 2.53%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Creative Technology              | 1         | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 11.21%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 6.54%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 6.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 6.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.74%   |
| AMD High Definition Audio Controller                                                              | 4         | 3.74%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.8%    |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.87%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.87%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.93%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.93%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.93%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 31.75%  |
| Samsung Electronics | 19        | 30.16%  |
| Micron Technology   | 8         | 12.7%   |
| Kingston            | 5         | 7.94%   |
| Unknown             | 4         | 6.35%   |
| A-DATA Technology   | 3         | 4.76%   |
| Transcend           | 1         | 1.59%   |
| Elpida              | 1         | 1.59%   |
| Corsair             | 1         | 1.59%   |
| 48spaces            | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 3         | 4.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 2         | 2.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 2.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 2.94%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2                              | 1         | 1.47%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.47%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.47%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s          | 1         | 1.47%   |
| Samsung RAM K4EBE304EB-EGCF 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 26        | 48.15%  |
| DDR4   | 22        | 40.74%  |
| LPDDR4 | 3         | 5.56%   |
| DDR2   | 2         | 3.7%    |
| LPDDR3 | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 94.34%  |
| Row Of Chips | 2         | 3.77%   |
| DIMM         | 1         | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 41.67%  |
| 8192  | 23        | 38.33%  |
| 2048  | 5         | 8.33%   |
| 16384 | 4         | 6.67%   |
| 1024  | 2         | 3.33%   |
| 512   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 31.58%  |
| 2667    | 13        | 22.81%  |
| 3200    | 7         | 12.28%  |
| 1334    | 5         | 8.77%   |
| 1333    | 4         | 7.02%   |
| 2400    | 2         | 3.51%   |
| 2133    | 2         | 3.51%   |
| 4266    | 1         | 1.75%   |
| 3733    | 1         | 1.75%   |
| 1867    | 1         | 1.75%   |
| 667     | 1         | 1.75%   |
| 533     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

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
| Chicony Electronics                    | 21        | 32.31%  |
| IMC Networks                           | 12        | 18.46%  |
| Microdia                               | 7         | 10.77%  |
| Realtek Semiconductor                  | 6         | 9.23%   |
| Quanta                                 | 5         | 7.69%   |
| Acer                                   | 5         | 7.69%   |
| Sunplus Innovation Technology          | 3         | 4.62%   |
| Suyin                                  | 2         | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.08%   |
| Silicon Motion                         | 1         | 1.54%   |
| Logitech                               | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 7         | 10.61%  |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 6.06%   |
| Quanta HD User Facing                         | 3         | 4.55%   |
| Suyin HP TrueVision HD                        | 2         | 3.03%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 3.03%   |
| Realtek USB Camera                            | 2         | 3.03%   |
| Microdia HP Integrated Webcam                 | 2         | 3.03%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 3.03%   |
| IMC Networks HD Camera                        | 2         | 3.03%   |
| Chicony USB 2.0 Camera                        | 2         | 3.03%   |
| Chicony HP TrueVision HD Camera               | 2         | 3.03%   |
| Chicony HD WebCam                             | 2         | 3.03%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.52%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.52%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.52%   |
| Realtek Laptop Camera                         | 1         | 1.52%   |
| Realtek Integrated Webcam HD                  | 1         | 1.52%   |
| Realtek HD WebCam                             | 1         | 1.52%   |
| Quanta VGA WebCam                             | 1         | 1.52%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.52%   |
| Microdia Webcam Vitade AF                     | 1         | 1.52%   |
| Microdia Webcam                               | 1         | 1.52%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.52%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.52%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.52%   |
| Logitech C505 HD Webcam                       | 1         | 1.52%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.52%   |
| IMC Networks Integrated Camera                | 1         | 1.52%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.52%   |
| IMC Networks EasyCamera                       | 1         | 1.52%   |
| Chicony WebCam                                | 1         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.52%   |
| Chicony USB2.0 Camera                         | 1         | 1.52%   |
| Chicony USB 5M WebCam                         | 1         | 1.52%   |
| Chicony thinkpad t430s camera                 | 1         | 1.52%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.52%   |
| Chicony HP Wide Vision HD Camera              | 1         | 1.52%   |
| Chicony HD WebCam (Acer)                      | 1         | 1.52%   |
| Chicony HD User Facing                        | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| Validity Sensors           | 3         | 33.33%  |
| Upek                       | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Lenovo      | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| Lenovo Integrated Smart Card Reader            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 54        | 72.97%  |
| 1     | 15        | 20.27%  |
| 2     | 4         | 5.41%   |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 36%     |
| Chipcard              | 5         | 20%     |
| Net/wireless          | 3         | 12%     |
| Multimedia controller | 2         | 8%      |
| Graphics card         | 2         | 8%      |
| Camera                | 2         | 8%      |
| Sound                 | 1         | 4%      |
| Net/ethernet          | 1         | 4%      |


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

Total: 105

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | B50-80 80EW                 | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| MSI           | GV72 7RE                    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
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
| Void Linux Rolling | 56        | 66.67%  |
| Void Linux         | 28        | 33.33%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 83        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 5         | 5.75%   |
| 5.18.19_1   | 4         | 4.6%    |
| 6.1.4_1     | 3         | 3.45%   |
| 5.8.18_1    | 3         | 3.45%   |
| 5.8.12_1    | 3         | 3.45%   |
| 5.3.9_1     | 3         | 3.45%   |
| 5.19.17_1   | 3         | 3.45%   |
| 5.10.17_1   | 3         | 3.45%   |
| 5.4.24_1    | 2         | 2.3%    |
| 5.19.16_1   | 2         | 2.3%    |
| 5.18.14_1   | 2         | 2.3%    |
| 5.16.20_1   | 2         | 2.3%    |
| 5.15.32_1   | 2         | 2.3%    |
| 5.13.13_1   | 2         | 2.3%    |
| 5.12.10_1   | 2         | 2.3%    |
| 6.1.3_1     | 1         | 1.15%   |
| 6.0.9_1     | 1         | 1.15%   |
| 6.0.15_1    | 1         | 1.15%   |
| 5.9.16_1    | 1         | 1.15%   |
| 5.9.14_1    | 1         | 1.15%   |
| 5.9.0-rc8_2 | 1         | 1.15%   |
| 5.8.9_1     | 1         | 1.15%   |
| 5.8.8_1     | 1         | 1.15%   |
| 5.8.7_1     | 1         | 1.15%   |
| 5.8.6_1     | 1         | 1.15%   |
| 5.8.12_2    | 1         | 1.15%   |
| 5.7.16_1    | 1         | 1.15%   |
| 5.4.35_1    | 1         | 1.15%   |
| 5.4.21_1    | 1         | 1.15%   |
| 5.4.13_2    | 1         | 1.15%   |
| 5.2.13_1    | 1         | 1.15%   |
| 5.18.7_1    | 1         | 1.15%   |
| 5.15.6_1    | 1         | 1.15%   |
| 5.15.45_1   | 1         | 1.15%   |
| 5.15.41_1   | 1         | 1.15%   |
| 5.15.28_1   | 1         | 1.15%   |
| 5.15.26_1   | 1         | 1.15%   |
| 5.15.22_1   | 1         | 1.15%   |
| 5.15.17_1   | 1         | 1.15%   |
| 5.15.16_1   | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.19 | 5         | 5.75%   |
| 5.8.12  | 4         | 4.6%    |
| 5.18.19 | 4         | 4.6%    |
| 6.1.4   | 3         | 3.45%   |
| 5.8.18  | 3         | 3.45%   |
| 5.3.9   | 3         | 3.45%   |
| 5.19.17 | 3         | 3.45%   |
| 5.10.17 | 3         | 3.45%   |
| 5.4.24  | 2         | 2.3%    |
| 5.19.16 | 2         | 2.3%    |
| 5.18.14 | 2         | 2.3%    |
| 5.16.20 | 2         | 2.3%    |
| 5.15.32 | 2         | 2.3%    |
| 5.13.13 | 2         | 2.3%    |
| 5.12.10 | 2         | 2.3%    |
| 6.1.3   | 1         | 1.15%   |
| 6.0.9   | 1         | 1.15%   |
| 6.0.15  | 1         | 1.15%   |
| 5.9.16  | 1         | 1.15%   |
| 5.9.14  | 1         | 1.15%   |
| 5.9.0   | 1         | 1.15%   |
| 5.8.9   | 1         | 1.15%   |
| 5.8.8   | 1         | 1.15%   |
| 5.8.7   | 1         | 1.15%   |
| 5.8.6   | 1         | 1.15%   |
| 5.7.16  | 1         | 1.15%   |
| 5.4.35  | 1         | 1.15%   |
| 5.4.21  | 1         | 1.15%   |
| 5.4.13  | 1         | 1.15%   |
| 5.2.13  | 1         | 1.15%   |
| 5.18.7  | 1         | 1.15%   |
| 5.15.6  | 1         | 1.15%   |
| 5.15.45 | 1         | 1.15%   |
| 5.15.41 | 1         | 1.15%   |
| 5.15.28 | 1         | 1.15%   |
| 5.15.26 | 1         | 1.15%   |
| 5.15.22 | 1         | 1.15%   |
| 5.15.17 | 1         | 1.15%   |
| 5.15.16 | 1         | 1.15%   |
| 5.15.14 | 1         | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 13.95%  |
| 5.8     | 11        | 12.79%  |
| 5.13    | 11        | 12.79%  |
| 5.18    | 7         | 8.14%   |
| 5.12    | 7         | 8.14%   |
| 5.10    | 7         | 8.14%   |
| 5.4     | 5         | 5.81%   |
| 5.19    | 5         | 5.81%   |
| 6.1     | 4         | 4.65%   |
| 5.9     | 3         | 3.49%   |
| 5.3     | 3         | 3.49%   |
| 6.0     | 2         | 2.33%   |
| 5.16    | 2         | 2.33%   |
| 5.7     | 1         | 1.16%   |
| 5.2     | 1         | 1.16%   |
| 5.14    | 1         | 1.16%   |
| 5.11    | 1         | 1.16%   |
| 5.1     | 1         | 1.16%   |
| 4.4     | 1         | 1.16%   |
| 4.14    | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 78        | 93.98%  |
| i686    | 3         | 3.61%   |
| aarch64 | 2         | 2.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 45.35%  |
| XFCE       | 10        | 11.63%  |
| MATE       | 9         | 10.47%  |
| KDE        | 8         | 9.3%    |
| KDE5       | 4         | 4.65%   |
| i3         | 4         | 4.65%   |
| GNOME      | 4         | 4.65%   |
| bspwm      | 2         | 2.33%   |
| X-Cinnamon | 1         | 1.16%   |
| river      | 1         | 1.16%   |
| openbox    | 1         | 1.16%   |
| LXDE       | 1         | 1.16%   |
| Lumina     | 1         | 1.16%   |
| awesome    | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 66.67%  |
| Tty     | 12        | 14.29%  |
| Wayland | 9         | 10.71%  |
| Unknown | 7         | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 83.33%  |
| LXDM    | 5         | 5.95%   |
| LightDM | 4         | 4.76%   |
| SDDM    | 3         | 3.57%   |
| SLiM    | 1         | 1.19%   |
| LDM     | 1         | 1.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 57.65%  |
| Unknown | 9         | 10.59%  |
| en_GB   | 5         | 5.88%   |
| en_DK   | 4         | 4.71%   |
| it_IT   | 3         | 3.53%   |
| de_DE   | 2         | 2.35%   |
| tr_TR   | 1         | 1.18%   |
| ru_UA   | 1         | 1.18%   |
| ru_RU   | 1         | 1.18%   |
| pt_BR   | 1         | 1.18%   |
| nb_NO   | 1         | 1.18%   |
| fr_FR   | 1         | 1.18%   |
| es_HN   | 1         | 1.18%   |
| es_ES   | 1         | 1.18%   |
| es_DO   | 1         | 1.18%   |
| en_NZ   | 1         | 1.18%   |
| en_CA   | 1         | 1.18%   |
| en_AU   | 1         | 1.18%   |
| ca_ES   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 60.71%  |
| BIOS | 33        | 39.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 64.29%  |
| Btrfs   | 19        | 22.62%  |
| Xfs     | 4         | 4.76%   |
| Unknown | 4         | 4.76%   |
| Zfs     | 1         | 1.19%   |
| F2fs    | 1         | 1.19%   |
| Ext3    | 1         | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 52        | 61.18%  |
| Unknown | 21        | 24.71%  |
| MBR     | 12        | 14.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 89.16%  |
| Yes       | 9         | 10.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 77.11%  |
| Yes       | 19        | 22.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 24.1%   |
| Hewlett-Packard     | 12        | 14.46%  |
| ASUSTek Computer    | 12        | 14.46%  |
| Acer                | 12        | 14.46%  |
| Dell                | 9         | 10.84%  |
| MSI                 | 3         | 3.61%   |
| HUAWEI              | 2         | 2.41%   |
| Unknown             | 2         | 2.41%   |
| Samsung Electronics | 1         | 1.2%    |
| Positivo            | 1         | 1.2%    |
| Pine Microsystems   | 1         | 1.2%    |
| Notebook            | 1         | 1.2%    |
| Nokia               | 1         | 1.2%    |
| Getac               | 1         | 1.2%    |
| Framework           | 1         | 1.2%    |
| Exo                 | 1         | 1.2%    |
| Digibras            | 1         | 1.2%    |
| Chuwi               | 1         | 1.2%    |
| Apple               | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Laptop 15-bw0xx                    | 2         | 2.41%   |
| Acer Swift SF314-42                   | 2         | 2.41%   |
| Unknown                               | 2         | 2.41%   |
| Samsung 275E4E/275E5E                 | 1         | 1.2%    |
| Positivo Mobile                       | 1         | 1.2%    |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 1.2%    |
| Notebook NV4XMB,ME,MZ                 | 1         | 1.2%    |
| Nokia Booklet 3G                      | 1         | 1.2%    |
| MSI Summit E13FlipEvo A12MT           | 1         | 1.2%    |
| MSI GV72 7RE                          | 1         | 1.2%    |
| MSI Bravo 15 A4DDR                    | 1         | 1.2%    |
| Lenovo Y520-15IKB 80YY                | 1         | 1.2%    |
| Lenovo ThinkPad X260 20F5S08Q00       | 1         | 1.2%    |
| Lenovo ThinkPad X240 20AMA34HMN       | 1         | 1.2%    |
| Lenovo ThinkPad X201 3680BR4          | 1         | 1.2%    |
| Lenovo ThinkPad T490 20N20046US       | 1         | 1.2%    |
| Lenovo ThinkPad T480 20L6SA5Q00       | 1         | 1.2%    |
| Lenovo ThinkPad T460 20FMS0WN00       | 1         | 1.2%    |
| Lenovo ThinkPad T430 2349PS3          | 1         | 1.2%    |
| Lenovo ThinkPad T420 4236PG6          | 1         | 1.2%    |
| Lenovo ThinkPad T420 4180A21          | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00 | 1         | 1.2%    |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200  | 1         | 1.2%    |
| Lenovo ThinkPad E595 20NFCTO1WW       | 1         | 1.2%    |
| Lenovo Legion Y540-15IRH-PG0 81SY     | 1         | 1.2%    |
| Lenovo IdeaPad Z570 10246ZG           | 1         | 1.2%    |
| Lenovo IdeaPad S145-14IIL 81W6        | 1         | 1.2%    |
| Lenovo IdeaPad 710S-13IKB 80VQ        | 1         | 1.2%    |
| Lenovo IdeaPad 5 15ITL05 82FG         | 1         | 1.2%    |
| Lenovo G50-45 80E3                    | 1         | 1.2%    |
| HUAWEI KLVL-WXXW                      | 1         | 1.2%    |
| HUAWEI HN-WX9X                        | 1         | 1.2%    |
| HP Stream Notebook PC 11              | 1         | 1.2%    |
| HP Pavilion Notebook                  | 1         | 1.2%    |
| HP Pavilion Gaming Laptop 15-dk0xxx   | 1         | 1.2%    |
| HP Pavilion 15                        | 1         | 1.2%    |
| HP Notebook                           | 1         | 1.2%    |
| HP Laptop 15s-eq2xxx                  | 1         | 1.2%    |
| HP Laptop 14-dk0xxx                   | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 13        | 15.66%  |
| Acer Aspire              | 7         | 8.43%   |
| HP Laptop                | 5         | 6.02%   |
| ASUS VivoBook            | 5         | 6.02%   |
| Lenovo IdeaPad           | 4         | 4.82%   |
| Dell Inspiron            | 4         | 4.82%   |
| HP Pavilion              | 3         | 3.61%   |
| Dell Latitude            | 2         | 2.41%   |
| Acer Swift               | 2         | 2.41%   |
| Unknown                  | 2         | 2.41%   |
| Samsung 275E4E           | 1         | 1.2%    |
| Positivo Mobile          | 1         | 1.2%    |
| Pine Microsystems Pine64 | 1         | 1.2%    |
| Notebook NV4XMB          | 1         | 1.2%    |
| Nokia Booklet            | 1         | 1.2%    |
| MSI Summit               | 1         | 1.2%    |
| MSI GV72                 | 1         | 1.2%    |
| MSI Bravo                | 1         | 1.2%    |
| Lenovo Y520-15IKB        | 1         | 1.2%    |
| Lenovo Legion            | 1         | 1.2%    |
| Lenovo G50-45            | 1         | 1.2%    |
| HUAWEI KLVL-WXXW         | 1         | 1.2%    |
| HUAWEI HN-WX9X           | 1         | 1.2%    |
| HP Stream                | 1         | 1.2%    |
| HP Notebook              | 1         | 1.2%    |
| HP ENVY                  | 1         | 1.2%    |
| HP 15                    | 1         | 1.2%    |
| Getac V110               | 1         | 1.2%    |
| Framework Laptop         | 1         | 1.2%    |
| Exo Exomate              | 1         | 1.2%    |
| Digibras NH4CU03         | 1         | 1.2%    |
| Dell XPS                 | 1         | 1.2%    |
| Dell Precision           | 1         | 1.2%    |
| Dell G3                  | 1         | 1.2%    |
| Chuwi GemiBook           | 1         | 1.2%    |
| ASUS X751LD              | 1         | 1.2%    |
| ASUS X555UJ              | 1         | 1.2%    |
| ASUS X555LD              | 1         | 1.2%    |
| ASUS X510UAR             | 1         | 1.2%    |
| ASUS X455LF              | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 14        | 16.87%  |
| 2020    | 12        | 14.46%  |
| 2016    | 7         | 8.43%   |
| 2014    | 7         | 8.43%   |
| 2018    | 6         | 7.23%   |
| 2013    | 6         | 7.23%   |
| 2017    | 5         | 6.02%   |
| 2015    | 5         | 6.02%   |
| 2011    | 4         | 4.82%   |
| 2021    | 3         | 3.61%   |
| 2012    | 3         | 3.61%   |
| 2022    | 2         | 2.41%   |
| 2010    | 2         | 2.41%   |
| 2009    | 2         | 2.41%   |
| 2008    | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| 2006    | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 83        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 29.76%  |
| 3.01-4.0    | 19        | 22.62%  |
| 8.01-16.0   | 15        | 17.86%  |
| 16.01-24.0  | 11        | 13.1%   |
| 1.01-2.0    | 6         | 7.14%   |
| 32.01-64.0  | 4         | 4.76%   |
| 0.51-1.0    | 2         | 2.38%   |
| 24.01-32.0  | 1         | 1.19%   |
| 64.01-256.0 | 1         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 30        | 34.48%  |
| 2.01-3.0   | 21        | 24.14%  |
| 0.51-1.0   | 15        | 17.24%  |
| 4.01-8.0   | 8         | 9.2%    |
| 3.01-4.0   | 8         | 9.2%    |
| 0.01-0.5   | 3         | 3.45%   |
| 16.01-24.0 | 1         | 1.15%   |
| 8.01-16.0  | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 75.9%   |
| 2      | 17        | 20.48%  |
| 3      | 2         | 2.41%   |
| 0      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 75.9%   |
| Yes       | 20        | 24.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 72.29%  |
| No        | 23        | 27.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 95.18%  |
| No        | 4         | 4.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 80.72%  |
| No        | 16        | 19.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 13        | 15.66%  |
| India              | 9         | 10.84%  |
| Germany            | 8         | 9.64%   |
| Russia             | 7         | 8.43%   |
| Ukraine            | 4         | 4.82%   |
| Denmark            | 4         | 4.82%   |
| Brazil             | 4         | 4.82%   |
| Switzerland        | 3         | 3.61%   |
| UK                 | 2         | 2.41%   |
| Turkey             | 2         | 2.41%   |
| Spain              | 2         | 2.41%   |
| Netherlands        | 2         | 2.41%   |
| Morocco            | 2         | 2.41%   |
| Italy              | 2         | 2.41%   |
| Bulgaria           | 2         | 2.41%   |
| Australia          | 2         | 2.41%   |
| Vietnam            | 1         | 1.2%    |
| Peru               | 1         | 1.2%    |
| Norway             | 1         | 1.2%    |
| New Zealand        | 1         | 1.2%    |
| Mexico             | 1         | 1.2%    |
| Latvia             | 1         | 1.2%    |
| Indonesia          | 1         | 1.2%    |
| Honduras           | 1         | 1.2%    |
| Greece             | 1         | 1.2%    |
| France             | 1         | 1.2%    |
| Ecuador            | 1         | 1.2%    |
| Dominican Republic | 1         | 1.2%    |
| Czechia            | 1         | 1.2%    |
| Canada             | 1         | 1.2%    |
| Argentina          | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 3         | 3.57%   |
| St Petersburg | 2         | 2.38%   |
| Spring Hill   | 2         | 2.38%   |
| Rome          | 2         | 2.38%   |
| Meknes        | 2         | 2.38%   |
| Hyderabad     | 2         | 2.38%   |
| Geneva        | 2         | 2.38%   |
| Yambol        | 1         | 1.19%   |
| Weatherford   | 1         | 1.19%   |
| Volgograd     | 1         | 1.19%   |
| Vlaardingen   | 1         | 1.19%   |
| Viby J        | 1         | 1.19%   |
| Trujillo      | 1         | 1.19%   |
| Toulouse      | 1         | 1.19%   |
| Toms River    | 1         | 1.19%   |
| Tegucigalpa   | 1         | 1.19%   |
| Syktyvkar     | 1         | 1.19%   |
| Sydney        | 1         | 1.19%   |
| Surabaya      | 1         | 1.19%   |
| Stratford     | 1         | 1.19%   |
| Solone        | 1         | 1.19%   |
| Sofia         | 1         | 1.19%   |
| Sistranda     | 1         | 1.19%   |
| Saxtons River | 1         | 1.19%   |
| Sao Paulo     | 1         | 1.19%   |
| Santo Domingo | 1         | 1.19%   |
| Rostock       | 1         | 1.19%   |
| Rosenheim     | 1         | 1.19%   |
| Riga          | 1         | 1.19%   |
| Reutlingen    | 1         | 1.19%   |
| Regensburg    | 1         | 1.19%   |
| Pune          | 1         | 1.19%   |
| Prague        | 1         | 1.19%   |
| Porto Alegre  | 1         | 1.19%   |
| Pliening      | 1         | 1.19%   |
| Phoenix       | 1         | 1.19%   |
| Odense        | 1         | 1.19%   |
| Nuremberg     | 1         | 1.19%   |
| New Delhi     | 1         | 1.19%   |
| Mossoro       | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 22     | 21.21%  |
| Seagate             | 16        | 17     | 16.16%  |
| WDC                 | 11        | 12     | 11.11%  |
| Unknown             | 7         | 12     | 7.07%   |
| SanDisk             | 6         | 7      | 6.06%   |
| HGST                | 6         | 7      | 6.06%   |
| Toshiba             | 5         | 5      | 5.05%   |
| Intel               | 5         | 6      | 5.05%   |
| Kingston            | 4         | 4      | 4.04%   |
| SK hynix            | 2         | 2      | 2.02%   |
| Micron Technology   | 2         | 2      | 2.02%   |
| Hitachi             | 2         | 2      | 2.02%   |
| Crucial             | 2         | 2      | 2.02%   |
| Transcend           | 1         | 1      | 1.01%   |
| PNY                 | 1         | 1      | 1.01%   |
| Phison Electronics  | 1         | 1      | 1.01%   |
| Phison              | 1         | 1      | 1.01%   |
| Patriot             | 1         | 1      | 1.01%   |
| Lenovo              | 1         | 1      | 1.01%   |
| KIOXIA              | 1         | 1      | 1.01%   |
| China               | 1         | 1      | 1.01%   |
| BHT                 | 1         | 1      | 1.01%   |
| Apple               | 1         | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 4         | 3.88%   |
| Toshiba MQ01ABF050 500GB                       | 3         | 2.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 3         | 2.91%   |
| Unknown MMC Card  32GB                         | 2         | 1.94%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB        | 2         | 1.94%   |
| Seagate ST1000LM049-2GH172 1TB                 | 2         | 1.94%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB | 2         | 1.94%   |
| Samsung SSD 870 EVO 500GB                      | 2         | 1.94%   |
| Intel SSDPEKNW512G8 512GB                      | 2         | 1.94%   |
| HGST HTS545050A7E680 500GB                     | 2         | 1.94%   |
| HGST HTS541010B7E610 1TB                       | 2         | 1.94%   |
| HGST HTS541010A9E680 1TB                       | 2         | 1.94%   |
| Crucial CT500MX500SSD1 500GB                   | 2         | 1.94%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 0.97%   |
| WDC WD5000LPCX-21VHAT0 500GB                   | 1         | 0.97%   |
| WDC WD3200BPVT-22JJ5T0 320GB                   | 1         | 0.97%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 0.97%   |
| WDC WD1600BEVS-60VAT0 160GB                    | 1         | 0.97%   |
| WDC WD10SPZX-21Z10T0 1TB                       | 1         | 0.97%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 0.97%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 0.97%   |
| WDC WD Elements 512GB                          | 1         | 0.97%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB             | 1         | 0.97%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB           | 1         | 0.97%   |
| Unknown USB DISK 3.2 1TB                       | 1         | 0.97%   |
| Unknown SD512  512MB                           | 1         | 0.97%   |
| Unknown SD16G  16GB                            | 1         | 0.97%   |
| Unknown SD/MMC/MS PRO 2GB                      | 1         | 0.97%   |
| Unknown MMC Card  8GB                          | 1         | 0.97%   |
| Unknown MMC Card  128GB                        | 1         | 0.97%   |
| Unknown MMC Card                               | 1         | 0.97%   |
| Unknown CWBC3R  64GB                           | 1         | 0.97%   |
| Transcend TS128GMTS800 128GB SSD               | 1         | 0.97%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 0.97%   |
| Toshiba KXG50ZNV512G NVMe 512GB                | 1         | 0.97%   |
| Seagate ST98823AS 80GB                         | 1         | 0.97%   |
| Seagate ST9750420AS 752GB                      | 1         | 0.97%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 0.97%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 0.97%   |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 42.11%  |
| WDC                 | 8         | 8      | 21.05%  |
| HGST                | 6         | 7      | 15.79%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Hitachi             | 2         | 2      | 5.26%   |
| Unknown             | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 33.33%  |
| SanDisk             | 3         | 3      | 12.5%   |
| Kingston            | 3         | 3      | 12.5%   |
| Crucial             | 2         | 2      | 8.33%   |
| Transcend           | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Patriot             | 1         | 1      | 4.17%   |
| Lenovo              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| BHT                 | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 40     | 38.14%  |
| NVMe    | 29        | 34     | 29.9%   |
| SSD     | 23        | 24     | 23.71%  |
| MMC     | 6         | 9      | 6.19%   |
| Unknown | 2         | 3      | 2.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 62     | 58.06%  |
| NVMe | 29        | 34     | 31.18%  |
| MMC  | 6         | 9      | 6.45%   |
| SAS  | 4         | 5      | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 40     | 59.32%  |
| 0.51-1.0   | 22        | 22     | 37.29%  |
| 1.01-2.0   | 1         | 1      | 1.69%   |
| 4.01-10.0  | 1         | 1      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 30.59%  |
| 501-1000       | 19        | 22.35%  |
| 101-250        | 16        | 18.82%  |
| Unknown        | 7         | 8.24%   |
| 1001-2000      | 4         | 4.71%   |
| 1-20           | 4         | 4.71%   |
| 51-100         | 4         | 4.71%   |
| 21-50          | 3         | 3.53%   |
| More than 3000 | 1         | 1.18%   |
| 2001-3000      | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 24.71%  |
| 1-20           | 21        | 24.71%  |
| 21-50          | 15        | 17.65%  |
| 51-100         | 10        | 11.76%  |
| 251-500        | 7         | 8.24%   |
| Unknown        | 7         | 8.24%   |
| 1001-2000      | 3         | 3.53%   |
| More than 3000 | 1         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB              | 2         | 2      | 16.67%  |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 8.33%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 8.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 8.33%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 8.33%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 33.33%  |
| HGST                | 3         | 3      | 25%     |
| Hitachi             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 36.36%  |
| HGST    | 3         | 3      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Works    | 49        | 60     | 54.44%  |
| Detected | 29        | 38     | 32.22%  |
| Malfunc  | 12        | 12     | 13.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 51.58%  |
| AMD                              | 18        | 18.95%  |
| Samsung Electronics              | 13        | 13.68%  |
| SanDisk                          | 5         | 5.26%   |
| SK hynix                         | 2         | 2.11%   |
| Phison Electronics               | 2         | 2.11%   |
| Micron Technology                | 2         | 2.11%   |
| Toshiba America Info Systems     | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 1.05%   |
| KIOXIA                           | 1         | 1.05%   |
| Kingston Technology Company      | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 16.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 9.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 5.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 4.08%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 3.06%   |
| Intel SSD 660P Series                                                            | 3         | 3.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.06%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 2.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.04%   |
| Micron Non-Volatile memory controller                                            | 2         | 2.04%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.04%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.02%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.02%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.02%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.02%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.02%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.02%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 59.38%  |
| NVMe | 29        | 30.21%  |
| RAID | 6         | 6.25%   |
| IDE  | 4         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 69.88%  |
| AMD    | 23        | 27.71%  |
| ARM    | 2         | 2.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.41%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 2.41%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 2.41%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.41%   |
| ARM Processor                                 | 2         | 2.41%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.41%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.41%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 2.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.2%    |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.2%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.2%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.2%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.2%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.2%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.2%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.2%    |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.2%    |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.2%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.2%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.2%    |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 22.89%  |
| Intel Core i7           | 12        | 14.46%  |
| Other                   | 10        | 12.05%  |
| Intel Core i3           | 10        | 12.05%  |
| Intel Atom              | 5         | 6.02%   |
| AMD Ryzen 7             | 5         | 6.02%   |
| AMD Ryzen 5             | 5         | 6.02%   |
| Intel Celeron           | 4         | 4.82%   |
| AMD Ryzen 7 PRO         | 2         | 2.41%   |
| AMD A8                  | 2         | 2.41%   |
| Intel Pentium           | 1         | 1.2%    |
| Intel Genuine           | 1         | 1.2%    |
| Intel Core 2 Duo        | 1         | 1.2%    |
| AMD Turion 64 X2 Mobile | 1         | 1.2%    |
| AMD Ryzen 3             | 1         | 1.2%    |
| AMD E2                  | 1         | 1.2%    |
| AMD E1                  | 1         | 1.2%    |
| AMD C-60                | 1         | 1.2%    |
| AMD A4                  | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 44.58%  |
| 4      | 29        | 34.94%  |
| 6      | 6         | 7.23%   |
| 8      | 5         | 6.02%   |
| 1      | 4         | 4.82%   |
| 14     | 2         | 2.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 98.8%   |
| 2      | 1         | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 71.08%  |
| 1      | 24        | 28.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 75        | 90.36%  |
| Unknown        | 4         | 4.82%   |
| 64-bit         | 2         | 2.41%   |
| 32-bit         | 2         | 2.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 25.88%  |
| 0x40651    | 7         | 8.24%   |
| 0x306a9    | 4         | 4.71%   |
| 0x906ea    | 3         | 3.53%   |
| 0x806ec    | 3         | 3.53%   |
| 0x806e9    | 3         | 3.53%   |
| 0x406e3    | 3         | 3.53%   |
| 0x30678    | 3         | 3.53%   |
| 0x206a7    | 3         | 3.53%   |
| 0x08600104 | 3         | 3.53%   |
| 0x08108102 | 3         | 3.53%   |
| 0x906e9    | 2         | 2.35%   |
| 0x906a3    | 2         | 2.35%   |
| 0x106c2    | 2         | 2.35%   |
| 0x07030105 | 2         | 2.35%   |
| 0x06006705 | 2         | 2.35%   |
| 0x05000119 | 2         | 2.35%   |
| 0xa0652    | 1         | 1.18%   |
| 0x806eb    | 1         | 1.18%   |
| 0x806ea    | 1         | 1.18%   |
| 0x806c1    | 1         | 1.18%   |
| 0x706e5    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x20652    | 1         | 1.18%   |
| 0x106ca    | 1         | 1.18%   |
| 0x08608103 | 1         | 1.18%   |
| 0x08608102 | 1         | 1.18%   |
| 0x08600106 | 1         | 1.18%   |
| 0x08600102 | 1         | 1.18%   |
| 0x08108109 | 1         | 1.18%   |
| 0x08101007 | 1         | 1.18%   |
| 0x07030104 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 20.48%  |
| Haswell          | 8         | 9.64%   |
| Zen 2            | 6         | 7.23%   |
| Skylake          | 5         | 6.02%   |
| Zen+             | 4         | 4.82%   |
| Silvermont       | 4         | 4.82%   |
| SandyBridge      | 4         | 4.82%   |
| IvyBridge        | 4         | 4.82%   |
| Excavator        | 4         | 4.82%   |
| Unknown          | 4         | 4.82%   |
| TigerLake        | 3         | 3.61%   |
| Puma             | 3         | 3.61%   |
| Bonnell          | 3         | 3.61%   |
| IceLake          | 2         | 2.41%   |
| Bobcat           | 2         | 2.41%   |
| Alderlake Hybrid | 2         | 2.41%   |
| Zen              | 1         | 1.2%    |
| Westmere         | 1         | 1.2%    |
| Penryn           | 1         | 1.2%    |
| K8 Hammer        | 1         | 1.2%    |
| Goldmont plus    | 1         | 1.2%    |
| Core             | 1         | 1.2%    |
| CometLake        | 1         | 1.2%    |
| Broadwell        | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 57        | 54.29%  |
| AMD                              | 24        | 22.86%  |
| Nvidia                           | 23        | 21.9%   |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 7.41%   |
| AMD Renoir                                                                    | 6         | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 4.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 4.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 4         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 4         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.78%   |
| Intel HD Graphics 620                                                         | 3         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 2.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 1.85%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.85%   |
| Intel UHD Graphics 620                                                        | 2         | 1.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.85%   |
| Intel HD Graphics 630                                                         | 2         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 2         | 1.85%   |
| AMD Lucienne                                                                  | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.93%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                          | 1         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 0.93%   |
| Nvidia GM108M [GeForce 830M]                                                  | 1         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.93%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 42.17%  |
| Intel + Nvidia | 21        | 25.3%   |
| 1 x AMD        | 19        | 22.89%  |
| Other          | 2         | 2.41%   |
| 2 x AMD        | 2         | 2.41%   |
| AMD + Nvidia   | 2         | 2.41%   |
| 1 x SiS        | 1         | 1.2%    |
| Intel + AMD    | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 63        | 75.9%   |
| Proprietary | 17        | 20.48%  |
| Unknown     | 3         | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 67.44%  |
| 0.01-0.5   | 12        | 13.95%  |
| 1.01-2.0   | 7         | 8.14%   |
| 0.51-1.0   | 6         | 6.98%   |
| 3.01-4.0   | 2         | 2.33%   |
| 5.01-6.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 21        | 24.42%  |
| Chimei Innolux      | 18        | 20.93%  |
| LG Display          | 13        | 15.12%  |
| BOE                 | 12        | 13.95%  |
| Samsung Electronics | 3         | 3.49%   |
| Sharp               | 2         | 2.33%   |
| PANDA               | 2         | 2.33%   |
| Lenovo              | 2         | 2.33%   |
| Hewlett-Packard     | 2         | 2.33%   |
| Apple               | 2         | 2.33%   |
| AOC                 | 2         | 2.33%   |
| STD                 | 1         | 1.16%   |
| Philips             | 1         | 1.16%   |
| Panasonic           | 1         | 1.16%   |
| LG Philips          | 1         | 1.16%   |
| InnoLux Display     | 1         | 1.16%   |
| Iiyama              | 1         | 1.16%   |
| CHR                 | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 3.49%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 3.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 3.49%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.33%   |
| STD LCD Monitor STD0001 1920x1080                                     | 1         | 1.16%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 1.16%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 1.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 1.16%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.16%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.16%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 1         | 1.16%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.16%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.16%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch      | 1         | 1.16%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1         | 1.16%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                 | 1         | 1.16%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 1.16%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 33        | 39.29%  |
| 1366x768 (WXGA)   | 26        | 30.95%  |
| 1920x1200 (WUXGA) | 4         | 4.76%   |
| 1600x900 (HD+)    | 4         | 4.76%   |
| 2160x1440         | 3         | 3.57%   |
| 1280x800 (WXGA)   | 3         | 3.57%   |
| 2560x1440 (QHD)   | 2         | 2.38%   |
| 1024x600          | 2         | 2.38%   |
| 3840x2160 (4K)    | 1         | 1.19%   |
| 3440x1440         | 1         | 1.19%   |
| 2880x1800         | 1         | 1.19%   |
| 2560x1600         | 1         | 1.19%   |
| 2256x1504         | 1         | 1.19%   |
| 1360x768          | 1         | 1.19%   |
| 1280x720 (HD)     | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 37        | 43.02%  |
| 14      | 14        | 16.28%  |
| 13      | 13        | 15.12%  |
| 12      | 4         | 4.65%   |
| 11      | 3         | 3.49%   |
| 24      | 2         | 2.33%   |
| 23      | 2         | 2.33%   |
| 17      | 2         | 2.33%   |
| 10      | 2         | 2.33%   |
| 84      | 1         | 1.16%   |
| 39      | 1         | 1.16%   |
| 34      | 1         | 1.16%   |
| 33      | 1         | 1.16%   |
| 18      | 1         | 1.16%   |
| 8       | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 63.95%  |
| 201-300     | 18        | 20.93%  |
| 501-600     | 4         | 4.65%   |
| 701-800     | 2         | 2.33%   |
| 351-400     | 2         | 2.33%   |
| 801-900     | 1         | 1.16%   |
| 401-500     | 1         | 1.16%   |
| 1501-2000   | 1         | 1.16%   |
| 101-200     | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 81.48%  |
| 16/10 | 9         | 11.11%  |
| 3/2   | 5         | 6.17%   |
| 21/9  | 1         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 43.02%  |
| 81-90          | 20        | 23.26%  |
| 71-80          | 6         | 6.98%   |
| 61-70          | 4         | 4.65%   |
| 51-60          | 3         | 3.49%   |
| 351-500        | 2         | 2.33%   |
| 41-50          | 2         | 2.33%   |
| 251-300        | 2         | 2.33%   |
| 201-250        | 2         | 2.33%   |
| More than 1000 | 1         | 1.16%   |
| 1-40           | 1         | 1.16%   |
| 141-150        | 1         | 1.16%   |
| 131-140        | 1         | 1.16%   |
| 121-130        | 1         | 1.16%   |
| 501-1000       | 1         | 1.16%   |
| 91-100         | 1         | 1.16%   |
| Unknown        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 39        | 45.35%  |
| 101-120 | 23        | 26.74%  |
| 51-100  | 12        | 13.95%  |
| 161-240 | 11        | 12.79%  |
| Unknown | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 70        | 84.34%  |
| 2     | 11        | 13.25%  |
| 0     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 42        | 36.52%  |
| Intel                            | 35        | 30.43%  |
| Qualcomm Atheros                 | 17        | 14.78%  |
| Broadcom                         | 8         | 6.96%   |
| Sierra Wireless                  | 3         | 2.61%   |
| Broadcom Limited                 | 3         | 2.61%   |
| Cypress Semiconductor            | 2         | 1.74%   |
| Xiaomi                           | 1         | 0.87%   |
| TP-Link                          | 1         | 0.87%   |
| Silicon Integrated Systems [SiS] | 1         | 0.87%   |
| Ralink Technology                | 1         | 0.87%   |
| Ralink                           | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 18.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.94%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 4.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.39%   |
| Intel Wireless 8260                                               | 2         | 1.39%   |
| Intel Wireless 7260                                               | 2         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.39%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.39%   |
| Cypress K38231_03                                                 | 2         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.69%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.69%   |
| Sierra Wireless EM7455                                            | 1         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.69%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 42.17%  |
| Realtek Semiconductor | 19        | 22.89%  |
| Qualcomm Atheros      | 15        | 18.07%  |
| Broadcom              | 6         | 7.23%   |
| Sierra Wireless       | 3         | 3.61%   |
| Broadcom Limited      | 3         | 3.61%   |
| Ralink Technology     | 1         | 1.2%    |
| Ralink                | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7         | 8.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 6.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 6.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 4.82%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.82%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 3.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 3.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.41%   |
| Intel Wireless 8260                                            | 2         | 2.41%   |
| Intel Wireless 7260                                            | 2         | 2.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.41%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.41%   |
| Sierra Wireless EM7455                                         | 1         | 1.2%    |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.2%    |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.2%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 1.2%    |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.2%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.2%    |
| Intel Wireless-AC 9260                                         | 1         | 1.2%    |
| Intel WiFi Link 5100                                           | 1         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.2%    |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.2%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 37        | 60.66%  |
| Intel                            | 13        | 21.31%  |
| Qualcomm Atheros                 | 3         | 4.92%   |
| Broadcom                         | 3         | 4.92%   |
| Cypress Semiconductor            | 2         | 3.28%   |
| Xiaomi                           | 1         | 1.64%   |
| TP-Link                          | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 42.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 16.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.92%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.28%   |
| Cypress K38231_03                                                 | 2         | 3.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.64%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.64%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.64%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 56.83%  |
| Ethernet | 60        | 43.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 84.34%  |
| Ethernet | 13        | 15.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 63.86%  |
| 1     | 25        | 30.12%  |
| 0     | 4         | 4.82%   |
| 3     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 91.76%  |
| Yes  | 7         | 8.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 42.65%  |
| Realtek Semiconductor           | 12        | 17.65%  |
| Lite-On Technology              | 6         | 8.82%   |
| Broadcom                        | 6         | 8.82%   |
| Qualcomm Atheros Communications | 4         | 5.88%   |
| IMC Networks                    | 3         | 4.41%   |
| Realtek                         | 2         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Cambridge Silicon Radio         | 2         | 2.94%   |
| Dell                            | 1         | 1.47%   |
| Apple                           | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 11.76%  |
| Realtek Bluetooth Radio                             | 7         | 10.29%  |
| Intel AX200 Bluetooth                               | 7         | 10.29%  |
| Intel Bluetooth Device                              | 5         | 7.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.88%   |
| Lite-On Bluetooth Device                            | 3         | 4.41%   |
| Realtek Bluetooth Radio                             | 2         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.94%   |
| Intel AX210 Bluetooth                               | 2         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 2.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.47%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.47%   |
| IMC Networks Bluetooth Device                       | 1         | 1.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.47%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.47%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.47%   |
| Broadcom HP Portable Valentine                      | 1         | 1.47%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.47%   |
| Apple Bluetooth Host Controller                     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 56        | 61.54%  |
| AMD                              | 23        | 25.27%  |
| Nvidia                           | 8         | 8.79%   |
| Texas Instruments                | 2         | 2.2%    |
| Silicon Integrated Systems [SiS] | 1         | 1.1%    |
| Creative Technology              | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 10%     |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 8.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 6.67%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 5.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.33%   |
| AMD High Definition Audio Controller                                                              | 4         | 3.33%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.5%    |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.67%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.67%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.67%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.83%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.83%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 25        | 34.72%  |
| Samsung Electronics | 22        | 30.56%  |
| Micron Technology   | 8         | 11.11%  |
| Kingston            | 5         | 6.94%   |
| Unknown             | 4         | 5.56%   |
| A-DATA Technology   | 3         | 4.17%   |
| Transcend           | 1         | 1.39%   |
| Ramaxel Technology  | 1         | 1.39%   |
| Elpida              | 1         | 1.39%   |
| Corsair             | 1         | 1.39%   |
| 48spaces            | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 2.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 1.28%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.28%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.28%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 1.28%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.28%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.28%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.28%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.28%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.28%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 44.44%  |
| DDR3   | 28        | 44.44%  |
| LPDDR4 | 3         | 4.76%   |
| DDR2   | 2         | 3.17%   |
| LPDDR5 | 1         | 1.59%   |
| LPDDR3 | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 91.94%  |
| Row Of Chips | 4         | 6.45%   |
| DIMM         | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 40%     |
| 4096  | 27        | 38.57%  |
| 2048  | 7         | 10%     |
| 16384 | 5         | 7.14%   |
| 1024  | 2         | 2.86%   |
| 512   | 1         | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 30.3%   |
| 2667    | 16        | 24.24%  |
| 3200    | 10        | 15.15%  |
| 1334    | 5         | 7.58%   |
| 1333    | 4         | 6.06%   |
| 2400    | 2         | 3.03%   |
| 2133    | 2         | 3.03%   |
| 6400    | 1         | 1.52%   |
| 4266    | 1         | 1.52%   |
| 3733    | 1         | 1.52%   |
| 1867    | 1         | 1.52%   |
| 667     | 1         | 1.52%   |
| 533     | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

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
| Chicony Electronics                    | 23        | 31.08%  |
| IMC Networks                           | 13        | 17.57%  |
| Microdia                               | 8         | 10.81%  |
| Acer                                   | 7         | 9.46%   |
| Realtek Semiconductor                  | 6         | 8.11%   |
| Quanta                                 | 5         | 6.76%   |
| Suyin                                  | 3         | 4.05%   |
| Sunplus Innovation Technology          | 3         | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.05%   |
| Syntek                                 | 1         | 1.35%   |
| Silicon Motion                         | 1         | 1.35%   |
| Logitech                               | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 7         | 9.33%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 6.67%   |
| Suyin HP Truevision HD                        | 3         | 4%      |
| Quanta HD User Facing                         | 3         | 4%      |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.67%   |
| Realtek USB Camera                            | 2         | 2.67%   |
| Microdia Integrated_Webcam_HD                 | 2         | 2.67%   |
| Microdia HP Integrated Webcam                 | 2         | 2.67%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.67%   |
| IMC Networks HD Camera                        | 2         | 2.67%   |
| Chicony USB 2.0 Camera                        | 2         | 2.67%   |
| Chicony HP TrueVision HD Camera               | 2         | 2.67%   |
| Chicony HD WebCam                             | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 2.67%   |
| Acer SunplusIT Integrated Camera              | 2         | 2.67%   |
| Syntek Integrated Camera                      | 1         | 1.33%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.33%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.33%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.33%   |
| Realtek Laptop Camera                         | 1         | 1.33%   |
| Realtek Integrated Webcam HD                  | 1         | 1.33%   |
| Realtek HD WebCam                             | 1         | 1.33%   |
| Quanta VGA WebCam                             | 1         | 1.33%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.33%   |
| Microdia Webcam Vitade AF                     | 1         | 1.33%   |
| Microdia Webcam                               | 1         | 1.33%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.33%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.33%   |
| Logitech C505 HD Webcam                       | 1         | 1.33%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.33%   |
| IMC Networks Integrated Camera                | 1         | 1.33%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.33%   |
| IMC Networks EasyCamera                       | 1         | 1.33%   |
| Chicony WebCam                                | 1         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.33%   |
| Chicony USB2.0 Camera                         | 1         | 1.33%   |
| Chicony USB 5M WebCam                         | 1         | 1.33%   |
| Chicony ThinkPad T490 Webcam                  | 1         | 1.33%   |
| Chicony thinkpad t430s camera                 | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 45.45%  |
| Validity Sensors           | 3         | 27.27%  |
| Shenzhen Goodix Technology | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 36.36%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 27.27%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |

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
| 0     | 61        | 72.62%  |
| 1     | 18        | 21.43%  |
| 2     | 4         | 4.76%   |
| 3     | 1         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 39.29%  |
| Chipcard                 | 5         | 17.86%  |
| Net/wireless             | 3         | 10.71%  |
| Multimedia controller    | 2         | 7.14%   |
| Graphics card            | 2         | 7.14%   |
| Camera                   | 2         | 7.14%   |
| Sound                    | 1         | 3.57%   |
| Net/ethernet             | 1         | 3.57%   |
| Communication controller | 1         | 3.57%   |


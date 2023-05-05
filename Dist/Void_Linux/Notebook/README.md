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

Total: 114

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
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
| Void Linux Rolling | 65        | 69.89%  |
| Void Linux         | 28        | 30.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 92        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 5         | 5.21%   |
| 5.18.19_1   | 4         | 4.17%   |
| 6.1.4_1     | 3         | 3.13%   |
| 5.8.18_1    | 3         | 3.13%   |
| 5.8.12_1    | 3         | 3.13%   |
| 5.3.9_1     | 3         | 3.13%   |
| 5.19.17_1   | 3         | 3.13%   |
| 5.10.17_1   | 3         | 3.13%   |
| 6.1.21_1    | 2         | 2.08%   |
| 6.1.10_1    | 2         | 2.08%   |
| 5.4.24_1    | 2         | 2.08%   |
| 5.19.16_1   | 2         | 2.08%   |
| 5.18.14_1   | 2         | 2.08%   |
| 5.16.20_1   | 2         | 2.08%   |
| 5.15.32_1   | 2         | 2.08%   |
| 5.13.13_1   | 2         | 2.08%   |
| 5.12.10_1   | 2         | 2.08%   |
| 6.2.8_1     | 1         | 1.04%   |
| 6.2.11_1    | 1         | 1.04%   |
| 6.1.3_1     | 1         | 1.04%   |
| 6.1.18_1    | 1         | 1.04%   |
| 6.1.14_1    | 1         | 1.04%   |
| 6.1.13_1    | 1         | 1.04%   |
| 6.0.9_1     | 1         | 1.04%   |
| 6.0.15_1    | 1         | 1.04%   |
| 5.9.16_1    | 1         | 1.04%   |
| 5.9.14_1    | 1         | 1.04%   |
| 5.9.0-rc8_2 | 1         | 1.04%   |
| 5.8.9_1     | 1         | 1.04%   |
| 5.8.8_1     | 1         | 1.04%   |
| 5.8.7_1     | 1         | 1.04%   |
| 5.8.6_1     | 1         | 1.04%   |
| 5.8.12_2    | 1         | 1.04%   |
| 5.7.16_1    | 1         | 1.04%   |
| 5.4.35_1    | 1         | 1.04%   |
| 5.4.21_1    | 1         | 1.04%   |
| 5.4.13_2    | 1         | 1.04%   |
| 5.2.13_1    | 1         | 1.04%   |
| 5.18.7_1    | 1         | 1.04%   |
| 5.15.6_1    | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.19 | 5         | 5.21%   |
| 5.8.12  | 4         | 4.17%   |
| 5.18.19 | 4         | 4.17%   |
| 6.1.4   | 3         | 3.13%   |
| 5.8.18  | 3         | 3.13%   |
| 5.3.9   | 3         | 3.13%   |
| 5.19.17 | 3         | 3.13%   |
| 5.10.17 | 3         | 3.13%   |
| 6.1.21  | 2         | 2.08%   |
| 6.1.10  | 2         | 2.08%   |
| 5.4.24  | 2         | 2.08%   |
| 5.19.16 | 2         | 2.08%   |
| 5.18.14 | 2         | 2.08%   |
| 5.16.20 | 2         | 2.08%   |
| 5.15.32 | 2         | 2.08%   |
| 5.13.13 | 2         | 2.08%   |
| 5.12.10 | 2         | 2.08%   |
| 6.2.8   | 1         | 1.04%   |
| 6.2.11  | 1         | 1.04%   |
| 6.1.3   | 1         | 1.04%   |
| 6.1.18  | 1         | 1.04%   |
| 6.1.14  | 1         | 1.04%   |
| 6.1.13  | 1         | 1.04%   |
| 6.0.9   | 1         | 1.04%   |
| 6.0.15  | 1         | 1.04%   |
| 5.9.16  | 1         | 1.04%   |
| 5.9.14  | 1         | 1.04%   |
| 5.9.0   | 1         | 1.04%   |
| 5.8.9   | 1         | 1.04%   |
| 5.8.8   | 1         | 1.04%   |
| 5.8.7   | 1         | 1.04%   |
| 5.8.6   | 1         | 1.04%   |
| 5.7.16  | 1         | 1.04%   |
| 5.4.35  | 1         | 1.04%   |
| 5.4.21  | 1         | 1.04%   |
| 5.4.13  | 1         | 1.04%   |
| 5.2.13  | 1         | 1.04%   |
| 5.18.7  | 1         | 1.04%   |
| 5.15.6  | 1         | 1.04%   |
| 5.15.45 | 1         | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 12.63%  |
| 6.1     | 11        | 11.58%  |
| 5.8     | 11        | 11.58%  |
| 5.13    | 11        | 11.58%  |
| 5.18    | 7         | 7.37%   |
| 5.12    | 7         | 7.37%   |
| 5.10    | 7         | 7.37%   |
| 5.4     | 5         | 5.26%   |
| 5.19    | 5         | 5.26%   |
| 5.9     | 3         | 3.16%   |
| 5.3     | 3         | 3.16%   |
| 6.2     | 2         | 2.11%   |
| 6.0     | 2         | 2.11%   |
| 5.16    | 2         | 2.11%   |
| 5.7     | 1         | 1.05%   |
| 5.2     | 1         | 1.05%   |
| 5.14    | 1         | 1.05%   |
| 5.11    | 1         | 1.05%   |
| 5.1     | 1         | 1.05%   |
| 4.4     | 1         | 1.05%   |
| 4.14    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 87        | 94.57%  |
| i686    | 3         | 3.26%   |
| aarch64 | 2         | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 39        | 41.05%  |
| XFCE         | 11        | 11.58%  |
| MATE         | 9         | 9.47%   |
| KDE          | 8         | 8.42%   |
| KDE5         | 5         | 5.26%   |
| i3           | 5         | 5.26%   |
| GNOME        | 5         | 5.26%   |
| X-Cinnamon   | 2         | 2.11%   |
| sway         | 2         | 2.11%   |
| bspwm        | 2         | 2.11%   |
| river        | 1         | 1.05%   |
| openbox      | 1         | 1.05%   |
| LXQt         | 1         | 1.05%   |
| LXDE         | 1         | 1.05%   |
| Lumina       | 1         | 1.05%   |
| dot-xsession | 1         | 1.05%   |
| awesome      | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 63        | 67.74%  |
| Tty     | 12        | 12.9%   |
| Wayland | 11        | 11.83%  |
| Unknown | 7         | 7.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 79.57%  |
| LightDM | 7         | 7.53%   |
| LXDM    | 6         | 6.45%   |
| SDDM    | 4         | 4.3%    |
| SLiM    | 1         | 1.08%   |
| LDM     | 1         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 53        | 56.38%  |
| Unknown | 9         | 9.57%   |
| en_GB   | 5         | 5.32%   |
| en_DK   | 4         | 4.26%   |
| de_DE   | 4         | 4.26%   |
| it_IT   | 3         | 3.19%   |
| es_ES   | 3         | 3.19%   |
| en_CA   | 2         | 2.13%   |
| tr_TR   | 1         | 1.06%   |
| ru_UA   | 1         | 1.06%   |
| ru_RU   | 1         | 1.06%   |
| pt_BR   | 1         | 1.06%   |
| nb_NO   | 1         | 1.06%   |
| fr_FR   | 1         | 1.06%   |
| es_HN   | 1         | 1.06%   |
| es_DO   | 1         | 1.06%   |
| en_NZ   | 1         | 1.06%   |
| en_AU   | 1         | 1.06%   |
| ca_ES   | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 62.37%  |
| BIOS | 35        | 37.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 60        | 64.52%  |
| Btrfs   | 20        | 21.51%  |
| Unknown | 5         | 5.38%   |
| Xfs     | 4         | 4.3%    |
| Zfs     | 2         | 2.15%   |
| F2fs    | 1         | 1.08%   |
| Ext3    | 1         | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 59        | 62.77%  |
| Unknown | 23        | 24.47%  |
| MBR     | 12        | 12.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 89.13%  |
| Yes       | 10        | 10.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 77.17%  |
| Yes       | 21        | 22.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 26.09%  |
| Hewlett-Packard     | 13        | 14.13%  |
| ASUSTek Computer    | 13        | 14.13%  |
| Acer                | 13        | 14.13%  |
| Dell                | 10        | 10.87%  |
| MSI                 | 3         | 3.26%   |
| HUAWEI              | 2         | 2.17%   |
| Unknown             | 2         | 2.17%   |
| Timi                | 1         | 1.09%   |
| Samsung Electronics | 1         | 1.09%   |
| Positivo            | 1         | 1.09%   |
| Pine Microsystems   | 1         | 1.09%   |
| Notebook            | 1         | 1.09%   |
| Nokia               | 1         | 1.09%   |
| Getac               | 1         | 1.09%   |
| Framework           | 1         | 1.09%   |
| Exo                 | 1         | 1.09%   |
| Digibras            | 1         | 1.09%   |
| Chuwi               | 1         | 1.09%   |
| Apple               | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP Laptop 15-bw0xx                        | 2         | 2.17%   |
| Acer Swift SF314-42                       | 2         | 2.17%   |
| Unknown                                   | 2         | 2.17%   |
| Timi Redmi Book Pro 15 2022               | 1         | 1.09%   |
| Samsung 275E4E/275E5E                     | 1         | 1.09%   |
| Positivo Mobile                           | 1         | 1.09%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 1.09%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 1.09%   |
| Nokia Booklet 3G                          | 1         | 1.09%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 1.09%   |
| MSI GV72 7RE                              | 1         | 1.09%   |
| MSI Bravo 15 A4DDR                        | 1         | 1.09%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 1.09%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 1.09%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 1.09%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 1.09%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 1.09%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 1.09%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 1.09%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 1.09%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 1.09%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 1.09%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 1.09%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 1.09%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 1.09%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 1.09%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 1         | 1.09%   |
| Lenovo ThinkPad E595 20NFCTO1WW           | 1         | 1.09%   |
| Lenovo Legion Y540-15IRH-PG0 81SY         | 1         | 1.09%   |
| Lenovo IdeaPad Z570 10246ZG               | 1         | 1.09%   |
| Lenovo IdeaPad S145-14IIL 81W6            | 1         | 1.09%   |
| Lenovo IdeaPad 710S-13IKB 80VQ            | 1         | 1.09%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 1.09%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 1         | 1.09%   |
| Lenovo G50-70 20351                       | 1         | 1.09%   |
| Lenovo G50-45 80E3                        | 1         | 1.09%   |
| HUAWEI KLVL-WXXW                          | 1         | 1.09%   |
| HUAWEI HN-WX9X                            | 1         | 1.09%   |
| HP Stream Notebook PC 11                  | 1         | 1.09%   |
| HP Pavilion Notebook                      | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 15        | 16.3%   |
| Acer Aspire              | 7         | 7.61%   |
| ASUS VivoBook            | 6         | 6.52%   |
| Lenovo IdeaPad           | 5         | 5.43%   |
| HP Laptop                | 5         | 5.43%   |
| Dell Inspiron            | 4         | 4.35%   |
| HP Pavilion              | 3         | 3.26%   |
| Dell Latitude            | 3         | 3.26%   |
| HP ENVY                  | 2         | 2.17%   |
| Acer Swift               | 2         | 2.17%   |
| Unknown                  | 2         | 2.17%   |
| Timi Redmi               | 1         | 1.09%   |
| Samsung 275E4E           | 1         | 1.09%   |
| Positivo Mobile          | 1         | 1.09%   |
| Pine Microsystems Pine64 | 1         | 1.09%   |
| Notebook NV4XMB          | 1         | 1.09%   |
| Nokia Booklet            | 1         | 1.09%   |
| MSI Summit               | 1         | 1.09%   |
| MSI GV72                 | 1         | 1.09%   |
| MSI Bravo                | 1         | 1.09%   |
| Lenovo Y520-15IKB        | 1         | 1.09%   |
| Lenovo Legion            | 1         | 1.09%   |
| Lenovo G50-70            | 1         | 1.09%   |
| Lenovo G50-45            | 1         | 1.09%   |
| HUAWEI KLVL-WXXW         | 1         | 1.09%   |
| HUAWEI HN-WX9X           | 1         | 1.09%   |
| HP Stream                | 1         | 1.09%   |
| HP Notebook              | 1         | 1.09%   |
| HP 15                    | 1         | 1.09%   |
| Getac V110               | 1         | 1.09%   |
| Framework Laptop         | 1         | 1.09%   |
| Exo Exomate              | 1         | 1.09%   |
| Digibras NH4CU03         | 1         | 1.09%   |
| Dell XPS                 | 1         | 1.09%   |
| Dell Precision           | 1         | 1.09%   |
| Dell G3                  | 1         | 1.09%   |
| Chuwi GemiBook           | 1         | 1.09%   |
| ASUS X751LD              | 1         | 1.09%   |
| ASUS X555UJ              | 1         | 1.09%   |
| ASUS X555LD              | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 16        | 17.39%  |
| 2020    | 12        | 13.04%  |
| 2013    | 8         | 8.7%    |
| 2018    | 7         | 7.61%   |
| 2016    | 7         | 7.61%   |
| 2014    | 7         | 7.61%   |
| 2015    | 6         | 6.52%   |
| 2017    | 5         | 5.43%   |
| 2022    | 4         | 4.35%   |
| 2021    | 4         | 4.35%   |
| 2011    | 4         | 4.35%   |
| 2012    | 3         | 3.26%   |
| 2010    | 2         | 2.17%   |
| 2009    | 2         | 2.17%   |
| 2008    | 2         | 2.17%   |
| Unknown | 2         | 2.17%   |
| 2006    | 1         | 1.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 92        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 92        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 26.88%  |
| 3.01-4.0    | 21        | 22.58%  |
| 8.01-16.0   | 17        | 18.28%  |
| 16.01-24.0  | 14        | 15.05%  |
| 1.01-2.0    | 6         | 6.45%   |
| 32.01-64.0  | 5         | 5.38%   |
| 24.01-32.0  | 2         | 2.15%   |
| 0.51-1.0    | 2         | 2.15%   |
| 64.01-256.0 | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 35        | 36.46%  |
| 2.01-3.0   | 22        | 22.92%  |
| 0.51-1.0   | 16        | 16.67%  |
| 4.01-8.0   | 9         | 9.38%   |
| 3.01-4.0   | 9         | 9.38%   |
| 0.01-0.5   | 3         | 3.13%   |
| 16.01-24.0 | 1         | 1.04%   |
| 8.01-16.0  | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 76.09%  |
| 2      | 19        | 20.65%  |
| 3      | 2         | 2.17%   |
| 0      | 1         | 1.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 76.09%  |
| Yes       | 22        | 23.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 71.74%  |
| No        | 26        | 28.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 95.65%  |
| No        | 4         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 82.61%  |
| No        | 16        | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 14        | 15.22%  |
| Germany            | 10        | 10.87%  |
| India              | 9         | 9.78%   |
| Russia             | 8         | 8.7%    |
| Ukraine            | 4         | 4.35%   |
| Denmark            | 4         | 4.35%   |
| Brazil             | 4         | 4.35%   |
| Switzerland        | 3         | 3.26%   |
| UK                 | 2         | 2.17%   |
| Turkey             | 2         | 2.17%   |
| Spain              | 2         | 2.17%   |
| Netherlands        | 2         | 2.17%   |
| Morocco            | 2         | 2.17%   |
| Italy              | 2         | 2.17%   |
| France             | 2         | 2.17%   |
| Canada             | 2         | 2.17%   |
| Bulgaria           | 2         | 2.17%   |
| Australia          | 2         | 2.17%   |
| Vietnam            | 1         | 1.09%   |
| Serbia             | 1         | 1.09%   |
| Peru               | 1         | 1.09%   |
| Norway             | 1         | 1.09%   |
| New Zealand        | 1         | 1.09%   |
| Mexico             | 1         | 1.09%   |
| Latvia             | 1         | 1.09%   |
| Indonesia          | 1         | 1.09%   |
| Honduras           | 1         | 1.09%   |
| Guatemala          | 1         | 1.09%   |
| Greece             | 1         | 1.09%   |
| Ecuador            | 1         | 1.09%   |
| Dominican Republic | 1         | 1.09%   |
| Czechia            | 1         | 1.09%   |
| Austria            | 1         | 1.09%   |
| Argentina          | 1         | 1.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| St Petersburg | 3         | 3.23%   |
| Moscow        | 3         | 3.23%   |
| Spring Hill   | 2         | 2.15%   |
| Rome          | 2         | 2.15%   |
| Meknes        | 2         | 2.15%   |
| Hyderabad     | 2         | 2.15%   |
| Geneva        | 2         | 2.15%   |
| Yambol        | 1         | 1.08%   |
| Weatherford   | 1         | 1.08%   |
| Volgograd     | 1         | 1.08%   |
| Vlaardingen   | 1         | 1.08%   |
| Vienna        | 1         | 1.08%   |
| Viby J        | 1         | 1.08%   |
| Trujillo      | 1         | 1.08%   |
| Toulouse      | 1         | 1.08%   |
| Toms River    | 1         | 1.08%   |
| Tegucigalpa   | 1         | 1.08%   |
| Syktyvkar     | 1         | 1.08%   |
| Sydney        | 1         | 1.08%   |
| Surabaya      | 1         | 1.08%   |
| Sun Prairie   | 1         | 1.08%   |
| Stratford     | 1         | 1.08%   |
| Solone        | 1         | 1.08%   |
| Sofia         | 1         | 1.08%   |
| Sistranda     | 1         | 1.08%   |
| Saxtons River | 1         | 1.08%   |
| Sao Paulo     | 1         | 1.08%   |
| Santo Domingo | 1         | 1.08%   |
| Rostock       | 1         | 1.08%   |
| Rosenheim     | 1         | 1.08%   |
| Riga          | 1         | 1.08%   |
| Reutlingen    | 1         | 1.08%   |
| Regensburg    | 1         | 1.08%   |
| Pune          | 1         | 1.08%   |
| Prague        | 1         | 1.08%   |
| Porto Alegre  | 1         | 1.08%   |
| Pliening      | 1         | 1.08%   |
| Phoenix       | 1         | 1.08%   |
| Odense        | 1         | 1.08%   |
| Nuremberg     | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 21        | 22     | 19.09%  |
| Seagate                   | 16        | 17     | 14.55%  |
| WDC                       | 11        | 12     | 10%     |
| Unknown                   | 8         | 13     | 7.27%   |
| SanDisk                   | 7         | 8      | 6.36%   |
| HGST                      | 6         | 7      | 5.45%   |
| Toshiba                   | 5         | 5      | 4.55%   |
| SK hynix                  | 5         | 5      | 4.55%   |
| Kingston                  | 5         | 5      | 4.55%   |
| Intel                     | 5         | 6      | 4.55%   |
| Crucial                   | 4         | 4      | 3.64%   |
| Phison                    | 2         | 2      | 1.82%   |
| Micron Technology         | 2         | 2      | 1.82%   |
| Hitachi                   | 2         | 2      | 1.82%   |
| Transcend                 | 1         | 1      | 0.91%   |
| PNY                       | 1         | 1      | 0.91%   |
| Phison Electronics        | 1         | 1      | 0.91%   |
| Patriot                   | 1         | 1      | 0.91%   |
| Micron/Crucial Technology | 1         | 1      | 0.91%   |
| Lenovo                    | 1         | 1      | 0.91%   |
| KIOXIA                    | 1         | 1      | 0.91%   |
| INNOVATION IT             | 1         | 1      | 0.91%   |
| China                     | 1         | 1      | 0.91%   |
| BHT                       | 1         | 1      | 0.91%   |
| Apple                     | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                 | 4         | 3.51%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 2.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 3         | 2.63%   |
| Crucial CT500MX500SSD1 500GB                     | 3         | 2.63%   |
| Unknown MMC Card  32GB                           | 2         | 1.75%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB          | 2         | 1.75%   |
| Seagate ST1000LM049-2GH172 1TB                   | 2         | 1.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2         | 1.75%   |
| Samsung SSD 870 EVO 500GB                        | 2         | 1.75%   |
| Intel SSDPEKNW512G8 512GB                        | 2         | 1.75%   |
| HGST HTS545050A7E680 500GB                       | 2         | 1.75%   |
| HGST HTS541010B7E610 1TB                         | 2         | 1.75%   |
| HGST HTS541010A9E680 1TB                         | 2         | 1.75%   |
| WDC WD5000LPCX-22VHAT0 500GB                     | 1         | 0.88%   |
| WDC WD5000LPCX-21VHAT0 500GB                     | 1         | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 0.88%   |
| WDC WD2500BEVT-22A23T0 250GB                     | 1         | 0.88%   |
| WDC WD1600BEVS-60VAT0 160GB                      | 1         | 0.88%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 0.88%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 0.88%   |
| WDC WD Elements 320GB                            | 1         | 0.88%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB               | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB             | 1         | 0.88%   |
| Unknown USB DISK 3.2 250GB                       | 1         | 0.88%   |
| Unknown SD512  512MB                             | 1         | 0.88%   |
| Unknown SD16G  16GB                              | 1         | 0.88%   |
| Unknown SD/MMC/MS PRO 249GB                      | 1         | 0.88%   |
| Unknown MMC Card  8GB                            | 1         | 0.88%   |
| Unknown MMC Card  2GB                            | 1         | 0.88%   |
| Unknown MMC Card  128GB                          | 1         | 0.88%   |
| Unknown MMC Card                                 | 1         | 0.88%   |
| Unknown CWBC3R  64GB                             | 1         | 0.88%   |
| Transcend TS128GMTS800 128GB SSD                 | 1         | 0.88%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 0.88%   |
| Toshiba KXG50ZNV512G NVMe 512GB                  | 1         | 0.88%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB           | 1         | 0.88%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB           | 1         | 0.88%   |
| SK hynix SC313 SATA 512GB SSD                    | 1         | 0.88%   |
| Seagate ST98823AS 80GB                           | 1         | 0.88%   |

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
| Samsung Electronics | 8         | 8      | 26.67%  |
| SanDisk             | 4         | 4      | 13.33%  |
| Kingston            | 4         | 4      | 13.33%  |
| Crucial             | 4         | 4      | 13.33%  |
| Transcend           | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| PNY                 | 1         | 1      | 3.33%   |
| Patriot             | 1         | 1      | 3.33%   |
| Lenovo              | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| INNOVATION IT       | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| BHT                 | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 40     | 34.58%  |
| NVMe    | 33        | 38     | 30.84%  |
| SSD     | 28        | 30     | 26.17%  |
| MMC     | 7         | 10     | 6.54%   |
| Unknown | 2         | 3      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 67     | 56.73%  |
| NVMe | 33        | 38     | 31.73%  |
| MMC  | 7         | 10     | 6.73%   |
| SAS  | 5         | 6      | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 43     | 59.38%  |
| 0.51-1.0   | 24        | 25     | 37.5%   |
| 1.01-2.0   | 1         | 1      | 1.56%   |
| 4.01-10.0  | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 32.98%  |
| 501-1000       | 20        | 21.28%  |
| 101-250        | 18        | 19.15%  |
| Unknown        | 7         | 7.45%   |
| 1-20           | 5         | 5.32%   |
| 1001-2000      | 4         | 4.26%   |
| 51-100         | 4         | 4.26%   |
| 21-50          | 3         | 3.19%   |
| More than 3000 | 1         | 1.06%   |
| 2001-3000      | 1         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 26.6%   |
| 101-250        | 22        | 23.4%   |
| 21-50          | 17        | 18.09%  |
| 51-100         | 11        | 11.7%   |
| 251-500        | 8         | 8.51%   |
| Unknown        | 7         | 7.45%   |
| 1001-2000      | 3         | 3.19%   |
| More than 3000 | 1         | 1.06%   |

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
| Seagate ST1000LM035-1RK172 970GB      | 1         | 1      | 8.33%   |
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
| Works    | 56        | 67     | 56%     |
| Detected | 32        | 42     | 32%     |
| Malfunc  | 12        | 12     | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 50.48%  |
| AMD                              | 20        | 19.05%  |
| Samsung Electronics              | 13        | 12.38%  |
| SanDisk                          | 5         | 4.76%   |
| SK hynix                         | 4         | 3.81%   |
| Phison Electronics               | 3         | 2.86%   |
| Micron Technology                | 2         | 1.9%    |
| Toshiba America Info Systems     | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |
| Micron/Crucial Technology        | 1         | 0.95%   |
| KIOXIA                           | 1         | 0.95%   |
| Kingston Technology Company      | 1         | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 16.67%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 10.19%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 7.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 4.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.7%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.78%   |
| Intel SSD 660P Series                                                            | 3         | 2.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 2.78%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 1.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 1.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.85%   |
| Micron NVMe Storage Controller                                                   | 2         | 1.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.85%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.93%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.93%   |
| Phison Electronics Non-Volatile memory controller                                | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.93%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.93%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 64        | 60.38%  |
| NVMe | 33        | 31.13%  |
| RAID | 5         | 4.72%   |
| IDE  | 4         | 3.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 68.48%  |
| AMD    | 27        | 29.35%  |
| ARM    | 2         | 2.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 3.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.17%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 2.17%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 2.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 2.17%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.17%   |
| ARM Processor                                 | 2         | 2.17%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 2.17%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.09%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 1.09%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.09%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.09%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.09%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.09%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.09%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.09%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.09%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.09%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.09%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 20.65%  |
| Intel Core i7           | 15        | 16.3%   |
| Intel Core i3           | 11        | 11.96%  |
| Other                   | 10        | 10.87%  |
| AMD Ryzen 7             | 7         | 7.61%   |
| AMD Ryzen 5             | 6         | 6.52%   |
| Intel Atom              | 5         | 5.43%   |
| Intel Celeron           | 4         | 4.35%   |
| Intel Pentium           | 2         | 2.17%   |
| AMD Ryzen 7 PRO         | 2         | 2.17%   |
| AMD A8                  | 2         | 2.17%   |
| Intel Genuine           | 1         | 1.09%   |
| Intel Core 2 Duo        | 1         | 1.09%   |
| AMD Turion 64 X2 Mobile | 1         | 1.09%   |
| AMD Ryzen 5 PRO         | 1         | 1.09%   |
| AMD Ryzen 3             | 1         | 1.09%   |
| AMD E2                  | 1         | 1.09%   |
| AMD E1                  | 1         | 1.09%   |
| AMD C-60                | 1         | 1.09%   |
| AMD A4                  | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 42.39%  |
| 4      | 32        | 34.78%  |
| 6      | 9         | 9.78%   |
| 8      | 6         | 6.52%   |
| 1      | 4         | 4.35%   |
| 14     | 2         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 98.91%  |
| 2      | 1         | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 72.83%  |
| 1      | 25        | 27.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 91.3%   |
| Unknown        | 4         | 4.35%   |
| 64-bit         | 2         | 2.17%   |
| 32-bit         | 2         | 2.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 25.53%  |
| 0x40651    | 8         | 8.51%   |
| 0x406e3    | 4         | 4.26%   |
| 0x306a9    | 4         | 4.26%   |
| 0x08108102 | 4         | 4.26%   |
| 0x906ea    | 3         | 3.19%   |
| 0x806ec    | 3         | 3.19%   |
| 0x806e9    | 3         | 3.19%   |
| 0x30678    | 3         | 3.19%   |
| 0x206a7    | 3         | 3.19%   |
| 0x08600104 | 3         | 3.19%   |
| 0x906e9    | 2         | 2.13%   |
| 0x906a3    | 2         | 2.13%   |
| 0x106c2    | 2         | 2.13%   |
| 0x07030105 | 2         | 2.13%   |
| 0x06006705 | 2         | 2.13%   |
| 0x05000119 | 2         | 2.13%   |
| 0xa0652    | 1         | 1.06%   |
| 0x806eb    | 1         | 1.06%   |
| 0x806ea    | 1         | 1.06%   |
| 0x806c1    | 1         | 1.06%   |
| 0x706e5    | 1         | 1.06%   |
| 0x406c4    | 1         | 1.06%   |
| 0x306d4    | 1         | 1.06%   |
| 0x30673    | 1         | 1.06%   |
| 0x20652    | 1         | 1.06%   |
| 0x106ca    | 1         | 1.06%   |
| 0x0a50000c | 1         | 1.06%   |
| 0x0a404102 | 1         | 1.06%   |
| 0x0a404101 | 1         | 1.06%   |
| 0x08608103 | 1         | 1.06%   |
| 0x08608102 | 1         | 1.06%   |
| 0x08600106 | 1         | 1.06%   |
| 0x08600102 | 1         | 1.06%   |
| 0x08108109 | 1         | 1.06%   |
| 0x08101007 | 1         | 1.06%   |
| 0x07030104 | 1         | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 20.65%  |
| Haswell          | 9         | 9.78%   |
| Zen 2            | 6         | 6.52%   |
| Skylake          | 6         | 6.52%   |
| Unknown          | 6         | 6.52%   |
| Zen+             | 5         | 5.43%   |
| Silvermont       | 5         | 5.43%   |
| SandyBridge      | 4         | 4.35%   |
| IvyBridge        | 4         | 4.35%   |
| Excavator        | 4         | 4.35%   |
| TigerLake        | 3         | 3.26%   |
| Puma             | 3         | 3.26%   |
| Bonnell          | 3         | 3.26%   |
| IceLake          | 2         | 2.17%   |
| Bobcat           | 2         | 2.17%   |
| Alderlake Hybrid | 2         | 2.17%   |
| Zen 3            | 1         | 1.09%   |
| Zen              | 1         | 1.09%   |
| Westmere         | 1         | 1.09%   |
| Penryn           | 1         | 1.09%   |
| K8 Hammer        | 1         | 1.09%   |
| Goldmont plus    | 1         | 1.09%   |
| Core             | 1         | 1.09%   |
| CometLake        | 1         | 1.09%   |
| Broadwell        | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 61        | 52.59%  |
| AMD                              | 28        | 24.14%  |
| Nvidia                           | 26        | 22.41%  |
| Silicon Integrated Systems [SiS] | 1         | 0.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 7.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 5.04%   |
| AMD Renoir                                                                | 6         | 5.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 4.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 3.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 3.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 2.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 2.52%   |
| Intel UHD Graphics 620                                                    | 3         | 2.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.52%   |
| Intel HD Graphics 620                                                     | 3         | 2.52%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.68%   |
| Intel HD Graphics 630                                                     | 2         | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.68%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.68%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.68%   |
| AMD Lucienne                                                              | 2         | 1.68%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.84%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.84%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.84%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.84%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.84%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.84%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.84%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 0.84%   |
| Nvidia GM108M [GeForce 830M]                                              | 1         | 0.84%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.84%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 0.84%   |
| Nvidia GA107M [GeForce RTX 2050]                                          | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 41.3%   |
| Intel + Nvidia | 22        | 23.91%  |
| 1 x AMD        | 22        | 23.91%  |
| AMD + Nvidia   | 3         | 3.26%   |
| Other          | 2         | 2.17%   |
| 2 x AMD        | 2         | 2.17%   |
| 1 x SiS        | 1         | 1.09%   |
| 1 x Nvidia     | 1         | 1.09%   |
| Intel + AMD    | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 76.09%  |
| Proprietary | 19        | 20.65%  |
| Unknown     | 3         | 3.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 65.26%  |
| 0.01-0.5   | 12        | 12.63%  |
| 1.01-2.0   | 9         | 9.47%   |
| 0.51-1.0   | 6         | 6.32%   |
| 3.01-4.0   | 5         | 5.26%   |
| 5.01-6.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 21        | 22.34%  |
| Chimei Innolux       | 20        | 21.28%  |
| LG Display           | 15        | 15.96%  |
| BOE                  | 14        | 14.89%  |
| Samsung Electronics  | 3         | 3.19%   |
| Sharp                | 2         | 2.13%   |
| PANDA                | 2         | 2.13%   |
| Lenovo               | 2         | 2.13%   |
| Hewlett-Packard      | 2         | 2.13%   |
| Apple                | 2         | 2.13%   |
| AOC                  | 2         | 2.13%   |
| TMX                  | 1         | 1.06%   |
| STD                  | 1         | 1.06%   |
| Philips              | 1         | 1.06%   |
| Panasonic            | 1         | 1.06%   |
| LG Philips           | 1         | 1.06%   |
| InnoLux Display      | 1         | 1.06%   |
| Iiyama               | 1         | 1.06%   |
| CHR                  | 1         | 1.06%   |
| BOE Technology Group | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 3.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 3.19%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 3.19%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x194mm 15.5-inch       | 2         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.13%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 1.06%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                         | 1         | 1.06%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 1.06%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 1.06%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 1.06%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.06%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.06%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                    | 1         | 1.06%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.06%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch               | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.06%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch      | 1         | 1.06%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1         | 1.06%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                 | 1         | 1.06%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 1.06%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 36        | 39.13%  |
| 1366x768 (WXGA)   | 28        | 30.43%  |
| 1920x1200 (WUXGA) | 5         | 5.43%   |
| 1600x900 (HD+)    | 4         | 4.35%   |
| 2160x1440         | 3         | 3.26%   |
| 1280x800 (WXGA)   | 3         | 3.26%   |
| 2560x1600         | 2         | 2.17%   |
| 2560x1440 (QHD)   | 2         | 2.17%   |
| 1024x600          | 2         | 2.17%   |
| 3840x2160 (4K)    | 1         | 1.09%   |
| 3440x1440         | 1         | 1.09%   |
| 3200x2000         | 1         | 1.09%   |
| 2880x1800         | 1         | 1.09%   |
| 2256x1504         | 1         | 1.09%   |
| 1360x768          | 1         | 1.09%   |
| 1280x720 (HD)     | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 41.49%  |
| 14      | 15        | 15.96%  |
| 13      | 13        | 13.83%  |
| 17      | 4         | 4.26%   |
| 12      | 4         | 4.26%   |
| 11      | 3         | 3.19%   |
| 24      | 2         | 2.13%   |
| 23      | 2         | 2.13%   |
| 16      | 2         | 2.13%   |
| 10      | 2         | 2.13%   |
| Unknown | 2         | 2.13%   |
| 84      | 1         | 1.06%   |
| 39      | 1         | 1.06%   |
| 34      | 1         | 1.06%   |
| 33      | 1         | 1.06%   |
| 18      | 1         | 1.06%   |
| 8       | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 63.83%  |
| 201-300     | 18        | 19.15%  |
| 501-600     | 4         | 4.26%   |
| 351-400     | 4         | 4.26%   |
| 701-800     | 2         | 2.13%   |
| Unknown     | 2         | 2.13%   |
| 801-900     | 1         | 1.06%   |
| 401-500     | 1         | 1.06%   |
| 1501-2000   | 1         | 1.06%   |
| 101-200     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 70        | 78.65%  |
| 16/10   | 12        | 13.48%  |
| 3/2     | 5         | 5.62%   |
| 21/9    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 41.49%  |
| 81-90          | 21        | 22.34%  |
| 71-80          | 6         | 6.38%   |
| 61-70          | 4         | 4.26%   |
| 51-60          | 3         | 3.19%   |
| 121-130        | 3         | 3.19%   |
| 351-500        | 2         | 2.13%   |
| 41-50          | 2         | 2.13%   |
| 251-300        | 2         | 2.13%   |
| 201-250        | 2         | 2.13%   |
| 111-120        | 2         | 2.13%   |
| Unknown        | 2         | 2.13%   |
| More than 1000 | 1         | 1.06%   |
| 1-40           | 1         | 1.06%   |
| 141-150        | 1         | 1.06%   |
| 131-140        | 1         | 1.06%   |
| 501-1000       | 1         | 1.06%   |
| 91-100         | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 44.68%  |
| 101-120       | 24        | 25.53%  |
| 51-100        | 13        | 13.83%  |
| 161-240       | 12        | 12.77%  |
| Unknown       | 2         | 2.13%   |
| More than 240 | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 79        | 85.87%  |
| 2     | 11        | 11.96%  |
| 0     | 2         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 37.21%  |
| Intel                            | 39        | 30.23%  |
| Qualcomm Atheros                 | 18        | 13.95%  |
| Broadcom                         | 9         | 6.98%   |
| Sierra Wireless                  | 3         | 2.33%   |
| Broadcom Limited                 | 3         | 2.33%   |
| Cypress Semiconductor            | 2         | 1.55%   |
| Xiaomi                           | 1         | 0.78%   |
| TP-Link                          | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Ralink Technology                | 1         | 0.78%   |
| Ralink                           | 1         | 0.78%   |
| Qualcomm                         | 1         | 0.78%   |
| MediaTek                         | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 18.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.29%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 5.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.77%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 3.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 2.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.26%   |
| Intel Wireless 8260                                               | 2         | 1.26%   |
| Intel Wireless 7260                                               | 2         | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.26%   |
| Cypress K38231_03                                                 | 2         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.63%   |
| Sierra Wireless EM7455                                            | 1         | 0.63%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.63%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.63%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 42.86%  |
| Realtek Semiconductor | 20        | 21.98%  |
| Qualcomm Atheros      | 16        | 17.58%  |
| Broadcom              | 7         | 7.69%   |
| Broadcom Limited      | 3         | 3.3%    |
| Sierra Wireless       | 2         | 2.2%    |
| Ralink Technology     | 1         | 1.1%    |
| Ralink                | 1         | 1.1%    |
| Qualcomm              | 1         | 1.1%    |
| MediaTek              | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 8         | 8.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 6.59%   |
| Intel Wireless 8265 / 8275                                     | 6         | 6.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 5.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 4.4%    |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 4.4%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 3.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.2%    |
| Intel Wireless 8260                                            | 2         | 2.2%    |
| Intel Wireless 7260                                            | 2         | 2.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.2%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.2%    |
| Sierra Wireless EM7455                                         | 1         | 1.1%    |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.1%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.1%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.1%    |
| Intel Wireless-AC 9260                                         | 1         | 1.1%    |
| Intel Wireless 7265                                            | 1         | 1.1%    |
| Intel WiFi Link 5100                                           | 1         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.1%    |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 42        | 61.76%  |
| Intel                            | 14        | 20.59%  |
| Qualcomm Atheros                 | 3         | 4.41%   |
| Broadcom                         | 3         | 4.41%   |
| Cypress Semiconductor            | 2         | 2.94%   |
| Xiaomi                           | 1         | 1.47%   |
| TP-Link                          | 1         | 1.47%   |
| Silicon Integrated Systems [SiS] | 1         | 1.47%   |
| Sierra Wireless                  | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 14.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.41%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.94%   |
| Cypress K38231_03                                                 | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.47%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.47%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.47%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 57.14%  |
| Ethernet | 66        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 82.8%   |
| Ethernet | 16        | 17.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 63.04%  |
| 1     | 29        | 31.52%  |
| 0     | 4         | 4.35%   |
| 3     | 1         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 89.36%  |
| Yes  | 10        | 10.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 42.86%  |
| Realtek Semiconductor           | 12        | 15.58%  |
| Lite-On Technology              | 7         | 9.09%   |
| Broadcom                        | 6         | 7.79%   |
| Qualcomm Atheros Communications | 4         | 5.19%   |
| IMC Networks                    | 3         | 3.9%    |
| Foxconn / Hon Hai               | 3         | 3.9%    |
| Realtek                         | 2         | 2.6%    |
| Cambridge Silicon Radio         | 2         | 2.6%    |
| USI                             | 1         | 1.3%    |
| Opticis                         | 1         | 1.3%    |
| Foxconn International           | 1         | 1.3%    |
| Dell                            | 1         | 1.3%    |
| Apple                           | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 14.29%  |
| Intel AX200 Bluetooth                               | 8         | 10.39%  |
| Realtek Bluetooth Radio                             | 7         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 3.9%    |
| Intel AX201 Bluetooth                               | 3         | 3.9%    |
| Realtek 802.11ac WLAN Adapter                       | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.6%    |
| Intel Bluetooth Device                              | 2         | 2.6%    |
| Intel AX210 Bluetooth                               | 2         | 2.6%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.6%    |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 2.6%    |
| USI Bluetooth Device                                | 1         | 1.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.3%    |
| Opticis Bluetooth Radio                             | 1         | 1.3%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.3%    |
| IMC Networks Bluetooth Device                       | 1         | 1.3%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.3%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.3%    |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.3%    |
| Dell Wireless 365 Bluetooth                         | 1         | 1.3%    |
| Broadcom HP Portable Valentine                      | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.3%    |
| Apple Bluetooth Host Controller                     | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 61        | 60.4%   |
| AMD                              | 27        | 26.73%  |
| Nvidia                           | 9         | 8.91%   |
| Texas Instruments                | 2         | 1.98%   |
| Silicon Integrated Systems [SiS] | 1         | 0.99%   |
| Creative Technology              | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 11.85%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 6.67%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.7%    |
| AMD High Definition Audio Controller                                                              | 4         | 2.96%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.22%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.48%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.48%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.48%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.48%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.74%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.74%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 25        | 31.65%  |
| Samsung Electronics | 24        | 30.38%  |
| Micron Technology   | 11        | 13.92%  |
| Kingston            | 5         | 6.33%   |
| Unknown             | 4         | 5.06%   |
| A-DATA Technology   | 3         | 3.8%    |
| Ramaxel Technology  | 2         | 2.53%   |
| Transcend           | 1         | 1.27%   |
| Elpida              | 1         | 1.27%   |
| Crucial             | 1         | 1.27%   |
| Corsair             | 1         | 1.27%   |
| 48spaces            | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 3.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 2.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.18%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.18%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.18%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.18%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.18%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 30        | 43.48%  |
| DDR3   | 30        | 43.48%  |
| LPDDR5 | 3         | 4.35%   |
| LPDDR4 | 3         | 4.35%   |
| DDR2   | 2         | 2.9%    |
| LPDDR3 | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 89.71%  |
| Row Of Chips | 6         | 8.82%   |
| DIMM         | 1         | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 40.26%  |
| 4096  | 31        | 40.26%  |
| 16384 | 6         | 7.79%   |
| 2048  | 6         | 7.79%   |
| 1024  | 2         | 2.6%    |
| 512   | 1         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 22        | 30.56%  |
| 2667    | 17        | 23.61%  |
| 3200    | 11        | 15.28%  |
| 1334    | 5         | 6.94%   |
| 1333    | 4         | 5.56%   |
| 6400    | 3         | 4.17%   |
| 2400    | 2         | 2.78%   |
| 2133    | 2         | 2.78%   |
| 4266    | 1         | 1.39%   |
| 3733    | 1         | 1.39%   |
| 1867    | 1         | 1.39%   |
| 667     | 1         | 1.39%   |
| 533     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

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
| Chicony Electronics                    | 26        | 31.33%  |
| IMC Networks                           | 15        | 18.07%  |
| Microdia                               | 9         | 10.84%  |
| Realtek Semiconductor                  | 6         | 7.23%   |
| Quanta                                 | 5         | 6.02%   |
| Bison Electronics                      | 4         | 4.82%   |
| Acer                                   | 4         | 4.82%   |
| Suyin                                  | 3         | 3.61%   |
| Sunplus Innovation Technology          | 3         | 3.61%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.61%   |
| Syntek                                 | 1         | 1.2%    |
| SunplusIT                              | 1         | 1.2%    |
| Silicon Motion                         | 1         | 1.2%    |
| Logitech                               | 1         | 1.2%    |
| Intel                                  | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 9         | 10.71%  |
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 7.14%   |
| Suyin HP Truevision HD                        | 3         | 3.57%   |
| Quanta HD User Facing                         | 3         | 3.57%   |
| Microdia Integrated_Webcam_HD                 | 3         | 3.57%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.38%   |
| Realtek USB Camera                            | 2         | 2.38%   |
| Microdia HP Integrated Webcam                 | 2         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.38%   |
| IMC Networks Integrated Camera                | 2         | 2.38%   |
| IMC Networks HD Camera                        | 2         | 2.38%   |
| Chicony USB 2.0 Camera                        | 2         | 2.38%   |
| Chicony HP TrueVision HD Camera               | 2         | 2.38%   |
| Chicony HD WebCam (Acer)                      | 2         | 2.38%   |
| Chicony HD WebCam                             | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 2.38%   |
| Bison SunplusIT Integrated Camera             | 2         | 2.38%   |
| Syntek Integrated Camera                      | 1         | 1.19%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 1.19%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.19%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.19%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.19%   |
| Realtek Laptop Camera                         | 1         | 1.19%   |
| Realtek Integrated Webcam HD                  | 1         | 1.19%   |
| Realtek HD WebCam                             | 1         | 1.19%   |
| Quanta VGA WebCam                             | 1         | 1.19%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.19%   |
| Microdia Webcam Vitade AF                     | 1         | 1.19%   |
| Microdia Webcam                               | 1         | 1.19%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.19%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.19%   |
| Logitech C505 HD Webcam                       | 1         | 1.19%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 1.19%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.19%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.19%   |
| IMC Networks EasyCamera                       | 1         | 1.19%   |
| Chicony WebCam                                | 1         | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.19%   |
| Chicony USB2.0 Camera                         | 1         | 1.19%   |
| Chicony USB 5M WebCam                         | 1         | 1.19%   |

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
| 0     | 68        | 73.12%  |
| 1     | 19        | 20.43%  |
| 2     | 5         | 5.38%   |
| 3     | 1         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 35.48%  |
| Chipcard                 | 5         | 16.13%  |
| Net/wireless             | 4         | 12.9%   |
| Graphics card            | 4         | 12.9%   |
| Multimedia controller    | 2         | 6.45%   |
| Camera                   | 2         | 6.45%   |
| Sound                    | 1         | 3.23%   |
| Net/ethernet             | 1         | 3.23%   |
| Communication controller | 1         | 3.23%   |


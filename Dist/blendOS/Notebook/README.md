blendOS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for blendOS.

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

Total: 100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| LG Electro... | 16Z90Q-G.AP7BB              | [7ba27b35ec](https://linux-hardware.org/?probe=7ba27b35ec) | Oct 02, 2025 |
| LG Electro... | 16Z90Q-G.AP7BB              | [260d20352a](https://linux-hardware.org/?probe=260d20352a) | Oct 02, 2025 |
| HP            | Laptop 17-by3xxx            | [c964faff51](https://linux-hardware.org/?probe=c964faff51) | Sep 03, 2025 |
| HP            | ProBook 640 G2              | [a22d2ae9d1](https://linux-hardware.org/?probe=a22d2ae9d1) | Aug 03, 2025 |
| PINNACLEMI... | W76OC                       | [cc68f30710](https://linux-hardware.org/?probe=cc68f30710) | Jul 01, 2025 |
| OriginPC      | EON17-X                     | [16a89d1dc3](https://linux-hardware.org/?probe=16a89d1dc3) | May 09, 2025 |
| Lenovo        | G50-70 20351                | [82a4f5f99b](https://linux-hardware.org/?probe=82a4f5f99b) | Jan 01, 2025 |
| Apple         | MacBookPro8,2               | [e2f957298c](https://linux-hardware.org/?probe=e2f957298c) | Dec 17, 2024 |
| Apple         | MacBookPro8,2               | [504b00b57d](https://linux-hardware.org/?probe=504b00b57d) | Dec 17, 2024 |
| Apple         | MacBookPro5,1               | [3ba5637302](https://linux-hardware.org/?probe=3ba5637302) | Dec 07, 2024 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [2424c97650](https://linux-hardware.org/?probe=2424c97650) | Sep 24, 2024 |
| Lenovo        | B51-30 80LK                 | [e4f72a3222](https://linux-hardware.org/?probe=e4f72a3222) | Aug 08, 2024 |
| Lenovo        | B51-30 80LK                 | [8003cbb98e](https://linux-hardware.org/?probe=8003cbb98e) | Aug 08, 2024 |
| Alienware     | m15                         | [e088ad174b](https://linux-hardware.org/?probe=e088ad174b) | May 21, 2024 |
| Fujitsu       | LIFEBOOK U727               | [2d96690752](https://linux-hardware.org/?probe=2d96690752) | Apr 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e34eb800b2](https://linux-hardware.org/?probe=e34eb800b2) | Mar 29, 2024 |
| Acer          | Aspire 4752                 | [bb522b4ec1](https://linux-hardware.org/?probe=bb522b4ec1) | Mar 26, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [fced33a8a9](https://linux-hardware.org/?probe=fced33a8a9) | Mar 12, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7e150a29fb](https://linux-hardware.org/?probe=7e150a29fb) | Mar 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [33cf50568b](https://linux-hardware.org/?probe=33cf50568b) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [8845023d60](https://linux-hardware.org/?probe=8845023d60) | Mar 02, 2024 |
| Apple         | MacBookAir6,2               | [7ad397fc57](https://linux-hardware.org/?probe=7ad397fc57) | Jan 31, 2024 |
| Hampoo        | Cherry Trail CR             | [1c0466fe53](https://linux-hardware.org/?probe=1c0466fe53) | Jan 25, 2024 |
| MSI           | GS66 Stealth 10SF           | [fc256ee1dd](https://linux-hardware.org/?probe=fc256ee1dd) | Jan 18, 2024 |
| MSI           | GS66 Stealth 10SF           | [57eaf4a8c1](https://linux-hardware.org/?probe=57eaf4a8c1) | Jan 18, 2024 |
| ShangMai      | H                           | [aab28ab3ea](https://linux-hardware.org/?probe=aab28ab3ea) | Dec 27, 2023 |
| Lenovo        | ThinkPad E470 20H1004UIG    | [69efda7672](https://linux-hardware.org/?probe=69efda7672) | Dec 26, 2023 |
| Lenovo        | ThinkPad L470 20J5S0JM00    | [c8f1140dc5](https://linux-hardware.org/?probe=c8f1140dc5) | Dec 26, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [5f798fd0e0](https://linux-hardware.org/?probe=5f798fd0e0) | Dec 26, 2023 |
| HP            | EliteBook 840 G5            | [5b7a85e9fc](https://linux-hardware.org/?probe=5b7a85e9fc) | Dec 23, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [81dbec4f1a](https://linux-hardware.org/?probe=81dbec4f1a) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5e71510e4c](https://linux-hardware.org/?probe=5e71510e4c) | Dec 06, 2023 |
| Samsung       | 550P5C/550P7C               | [b7294ed55c](https://linux-hardware.org/?probe=b7294ed55c) | Nov 20, 2023 |
| Dell          | Latitude E7250              | [265c13751a](https://linux-hardware.org/?probe=265c13751a) | Nov 10, 2023 |
| Samsung       | 750XEE                      | [8fd9a5953f](https://linux-hardware.org/?probe=8fd9a5953f) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b837317e37](https://linux-hardware.org/?probe=b837317e37) | Nov 06, 2023 |
| HP            | ENVY 15                     | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| HP            | ENVY 15                     | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 750XEE                      | [fd74ae52f8](https://linux-hardware.org/?probe=fd74ae52f8) | Nov 04, 2023 |
| Notebook      | P65_P67SA                   | [a8bf179e25](https://linux-hardware.org/?probe=a8bf179e25) | Nov 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [342218fa56](https://linux-hardware.org/?probe=342218fa56) | Oct 28, 2023 |
| HP            | Notebook                    | [efb9814479](https://linux-hardware.org/?probe=efb9814479) | Oct 27, 2023 |
| Toshiba       | QOSMIO X75-A                | [8024d2e76b](https://linux-hardware.org/?probe=8024d2e76b) | Oct 26, 2023 |
| HP            | ProBook 655 G1              | [8e1cb99809](https://linux-hardware.org/?probe=8e1cb99809) | Oct 19, 2023 |
| HP            | ProBook 655 G1              | [a80cd678f2](https://linux-hardware.org/?probe=a80cd678f2) | Oct 18, 2023 |
| Lenovo        | G50-30 80G0                 | [3d308e7bb0](https://linux-hardware.org/?probe=3d308e7bb0) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [b97291313f](https://linux-hardware.org/?probe=b97291313f) | Oct 10, 2023 |
| HP            | 255 G5 Notebook PC          | [ecb99bea0c](https://linux-hardware.org/?probe=ecb99bea0c) | Oct 07, 2023 |
| MSI           | Pulse GL66 11UGK            | [706d9eb214](https://linux-hardware.org/?probe=706d9eb214) | Oct 06, 2023 |
| HP            | 255 G5 Notebook PC          | [4f758a2ce7](https://linux-hardware.org/?probe=4f758a2ce7) | Oct 05, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [604e4a5556](https://linux-hardware.org/?probe=604e4a5556) | Oct 05, 2023 |
| MSI           | Pulse GL66 11UGK            | [4484122a2c](https://linux-hardware.org/?probe=4484122a2c) | Oct 05, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [73ab8f124c](https://linux-hardware.org/?probe=73ab8f124c) | Oct 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6275e5c1d4](https://linux-hardware.org/?probe=6275e5c1d4) | Sep 29, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [fcb38d5424](https://linux-hardware.org/?probe=fcb38d5424) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | [26f998fafb](https://linux-hardware.org/?probe=26f998fafb) | Sep 19, 2023 |
| Dell          | Inspiron 15 5510            | [71a6a04c4c](https://linux-hardware.org/?probe=71a6a04c4c) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Apple         | MacBookPro9,2               | [a6d272539a](https://linux-hardware.org/?probe=a6d272539a) | Sep 03, 2023 |
| Dell          | Latitude 5410               | [e45d7975d2](https://linux-hardware.org/?probe=e45d7975d2) | Sep 03, 2023 |
| Acer          | Aspire 5750G                | [205a407b60](https://linux-hardware.org/?probe=205a407b60) | Aug 21, 2023 |
| Dell          | XPS 13 9350                 | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Panasonic     | CF-19ADNAXDA                | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| Dell          | Inspiron 3542               | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| Acer          | Aspire A715-71G             | [7f3c7327b7](https://linux-hardware.org/?probe=7f3c7327b7) | Aug 01, 2023 |
| Beelink       | Gemini X                    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| MSI           | GP63 Leopard 8RE            | [42a81e063a](https://linux-hardware.org/?probe=42a81e063a) | Jul 28, 2023 |
| Dell          | XPS 15 9570                 | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [352cc6e31d](https://linux-hardware.org/?probe=352cc6e31d) | Jul 17, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | [72015ffe3b](https://linux-hardware.org/?probe=72015ffe3b) | Jul 16, 2023 |
| ASUSTek       | G750JZA                     | [8a26d246e2](https://linux-hardware.org/?probe=8a26d246e2) | Jul 14, 2023 |
| HP            | Pavilion dv6                | [7f6c05f2d9](https://linux-hardware.org/?probe=7f6c05f2d9) | Jul 09, 2023 |
| Apple         | MacBookPro14,1              | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Acer          | Aspire V5-471G              | [f82fbc50e3](https://linux-hardware.org/?probe=f82fbc50e3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [627203a31f](https://linux-hardware.org/?probe=627203a31f) | Jun 18, 2023 |
| MSI           | MS-16Y1                     | [167889509f](https://linux-hardware.org/?probe=167889509f) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| HP            | Notebook                    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| ASUSTek       | K53SK                       | [39c63c5bd1](https://linux-hardware.org/?probe=39c63c5bd1) | May 31, 2023 |
| Lenovo        | G700 20251                  | [8ba2c6e5ed](https://linux-hardware.org/?probe=8ba2c6e5ed) | May 26, 2023 |
| Lenovo        | G550 2958                   | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| Lenovo        | G550 2958                   | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| HP            | Elite x2 1012 G1            | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| Dell          | Latitude XT2                | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | Aspire R7-571G              | [d4220bc210](https://linux-hardware.org/?probe=d4220bc210) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [006b9a2b3f](https://linux-hardware.org/?probe=006b9a2b3f) | Apr 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACS0640... | [711d09df05](https://linux-hardware.org/?probe=711d09df05) | Apr 04, 2023 |
| Samsung       | 750XED                      | [be19d0454d](https://linux-hardware.org/?probe=be19d0454d) | Mar 16, 2023 |
| Dell          | Precision M4800             | [57c57bb353](https://linux-hardware.org/?probe=57c57bb353) | Feb 22, 2023 |
| Gigabyte      | P65                         | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [ed7b51b8bc](https://linux-hardware.org/?probe=ed7b51b8bc) | Feb 01, 2023 |
| Apple         | MacBookPro11,1              | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| blendOS         | 74        | 97.37%  |
| blendOS Rolling | 2         | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| blendOS | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 6.3.9-zen1-1-zen               | 34        | 44.16%  |
| 6.5.5-zen1-1-zen               | 10        | 12.99%  |
| 6.2.12-arch1-1                 | 4         | 5.19%   |
| 6.3.6-zen1-1-zen               | 3         | 3.9%    |
| 6.1.8-arch1-1                  | 3         | 3.9%    |
| 6.3.5-arch1-1                  | 2         | 2.6%    |
| 6.2.13-arch1-1                 | 2         | 2.6%    |
| 6.1.8-zen1-1-zen               | 2         | 2.6%    |
| 6.8.7-zen1-1-zen               | 1         | 1.3%    |
| 6.4.0-Yagakimi-T2-xanmod1-1-t2 | 1         | 1.3%    |
| 6.3.4-arch1-1                  | 1         | 1.3%    |
| 6.3.2-arch1-1                  | 1         | 1.3%    |
| 6.2.11-arch1-1                 | 1         | 1.3%    |
| 6.16.7-zen1-1-zen              | 1         | 1.3%    |
| 6.16.4-zen1-1-zen              | 1         | 1.3%    |
| 6.15.8-zen1-2-zen              | 1         | 1.3%    |
| 6.15.2-zen1-1-zen              | 1         | 1.3%    |
| 6.14.5-zen1-1-zen              | 1         | 1.3%    |
| 6.12.4-zen1-1-zen              | 1         | 1.3%    |
| 6.12.1-zen1-1-zen              | 1         | 1.3%    |
| 6.10.7-zen1-1-zen              | 1         | 1.3%    |
| 6.10.3-zen1-2-zen              | 1         | 1.3%    |
| 6.1.9-zen1-1-zen               | 1         | 1.3%    |
| 6.1.12-zen1-1-zen              | 1         | 1.3%    |
| 6.1.11-zen1-1-zen              | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.9   | 34        | 44.16%  |
| 6.5.5   | 10        | 12.99%  |
| 6.1.8   | 5         | 6.49%   |
| 6.2.12  | 4         | 5.19%   |
| 6.3.6   | 3         | 3.9%    |
| 6.3.5   | 2         | 2.6%    |
| 6.2.13  | 2         | 2.6%    |
| 6.8.7   | 1         | 1.3%    |
| 6.4.0   | 1         | 1.3%    |
| 6.3.4   | 1         | 1.3%    |
| 6.3.2   | 1         | 1.3%    |
| 6.2.11  | 1         | 1.3%    |
| 6.16.7  | 1         | 1.3%    |
| 6.16.4  | 1         | 1.3%    |
| 6.15.8  | 1         | 1.3%    |
| 6.15.2  | 1         | 1.3%    |
| 6.14.5  | 1         | 1.3%    |
| 6.12.4  | 1         | 1.3%    |
| 6.12.1  | 1         | 1.3%    |
| 6.10.7  | 1         | 1.3%    |
| 6.10.3  | 1         | 1.3%    |
| 6.1.9   | 1         | 1.3%    |
| 6.1.12  | 1         | 1.3%    |
| 6.1.11  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3     | 41        | 53.95%  |
| 6.5     | 10        | 13.16%  |
| 6.2     | 7         | 9.21%   |
| 6.1     | 7         | 9.21%   |
| 6.16    | 2         | 2.63%   |
| 6.15    | 2         | 2.63%   |
| 6.12    | 2         | 2.63%   |
| 6.10    | 2         | 2.63%   |
| 6.8     | 1         | 1.32%   |
| 6.4     | 1         | 1.32%   |
| 6.14    | 1         | 1.32%   |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 46        | 60.53%  |
| KDE5  | 29        | 38.16%  |
| KDE6  | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 72        | 93.51%  |
| X11     | 5         | 6.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 97.37%  |
| SDDM    | 1         | 1.32%   |
| GDM     | 1         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 49        | 64.47%  |
| de_DE       | 5         | 6.58%   |
| en_GB       | 4         | 5.26%   |
| ru_RU       | 2         | 2.63%   |
| it_IT       | 2         | 2.63%   |
| fr_FR       | 2         | 2.63%   |
| es_ES       | 2         | 2.63%   |
| de_CH       | 2         | 2.63%   |
| tr_TR       | 1         | 1.32%   |
| fr_HT       | 1         | 1.32%   |
| es_UY       | 1         | 1.32%   |
| es_CO       | 1         | 1.32%   |
| es_AR       | 1         | 1.32%   |
| en_US.UTF.8 | 1         | 1.32%   |
| en_AU       | 1         | 1.32%   |
| de_AT       | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 75        | 98.68%  |
| EFI  | 1         | 1.32%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 60        | 78.95%  |
| Tmpfs | 10        | 13.16%  |
| Btrfs | 5         | 6.58%   |
| XXXfs | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 97.37%  |
| GPT     | 2         | 2.63%   |

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
| No        | 76        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 22.37%  |
| Hewlett-Packard     | 13        | 17.11%  |
| Dell                | 9         | 11.84%  |
| Apple               | 8         | 10.53%  |
| Samsung Electronics | 4         | 5.26%   |
| MSI                 | 4         | 5.26%   |
| ASUSTek Computer    | 4         | 5.26%   |
| Acer                | 4         | 5.26%   |
| Toshiba             | 1         | 1.32%   |
| ShangMai            | 1         | 1.32%   |
| PINNACLEMICRO       | 1         | 1.32%   |
| Panasonic           | 1         | 1.32%   |
| OriginPC            | 1         | 1.32%   |
| Notebook            | 1         | 1.32%   |
| LG Electronics      | 1         | 1.32%   |
| HUAWEI              | 1         | 1.32%   |
| Hampoo              | 1         | 1.32%   |
| Gigabyte Technology | 1         | 1.32%   |
| Fujitsu             | 1         | 1.32%   |
| Beelink             | 1         | 1.32%   |
| Alienware           | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 2         | 2.63%   |
| Apple MacBookPro11,1                | 2         | 2.63%   |
| Toshiba QOSMIO X75-A                | 1         | 1.32%   |
| ShangMai H                          | 1         | 1.32%   |
| Samsung 950XDB/951XDB/950XDY        | 1         | 1.32%   |
| Samsung 750XEE                      | 1         | 1.32%   |
| Samsung 750XED                      | 1         | 1.32%   |
| Samsung 550P5C/550P7C               | 1         | 1.32%   |
| PINNACLEMICRO W76OC                 | 1         | 1.32%   |
| Panasonic CF-19ADNAXDA              | 1         | 1.32%   |
| OriginPC EON17-X                    | 1         | 1.32%   |
| Notebook P65_P67SA                  | 1         | 1.32%   |
| MSI Pulse GL66 11UGK                | 1         | 1.32%   |
| MSI MS-16Y1                         | 1         | 1.32%   |
| MSI GS66 Stealth 10SF               | 1         | 1.32%   |
| MSI GP63 Leopard 8RE                | 1         | 1.32%   |
| LG 16Z90Q-G.AP7BB                   | 1         | 1.32%   |
| Lenovo Yoga 2 Pro 20266             | 1         | 1.32%   |
| Lenovo ThinkPad T431s 20ACS06400    | 1         | 1.32%   |
| Lenovo ThinkPad P52 20M9CTO1WW      | 1         | 1.32%   |
| Lenovo ThinkPad L580 20LW0010GE     | 1         | 1.32%   |
| Lenovo ThinkPad L470 20J5S0JM00     | 1         | 1.32%   |
| Lenovo ThinkPad E470 20H1004UIG     | 1         | 1.32%   |
| Lenovo Legion 7 15IMH05 81YT        | 1         | 1.32%   |
| Lenovo IdeaPadFlex 15 20309         | 1         | 1.32%   |
| Lenovo IdeaPad Slim 9 14ITL5 82D2   | 1         | 1.32%   |
| Lenovo IdeaPad S145-15AST 81N3      | 1         | 1.32%   |
| Lenovo IdeaPad 310-15ISK 80SM       | 1         | 1.32%   |
| Lenovo IdeaPad 3 15ITL6 82H8        | 1         | 1.32%   |
| Lenovo IdeaPad 3 14ITL05 81X7       | 1         | 1.32%   |
| Lenovo G700 20251                   | 1         | 1.32%   |
| Lenovo G550 2958                    | 1         | 1.32%   |
| Lenovo G50-30 80G0                  | 1         | 1.32%   |
| Lenovo B51-30 80LK                  | 1         | 1.32%   |
| HUAWEI BOHK-WAX9X                   | 1         | 1.32%   |
| HP ProBook 655 G1                   | 1         | 1.32%   |
| HP ProBook 640 G2                   | 1         | 1.32%   |
| HP ProBook 640 G1                   | 1         | 1.32%   |
| HP Pavilion Gaming Laptop 16-a0xxx  | 1         | 1.32%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 5         | 6.58%   |
| Lenovo IdeaPad         | 5         | 6.58%   |
| Acer Aspire            | 4         | 5.26%   |
| HP ProBook             | 3         | 3.95%   |
| HP Pavilion            | 3         | 3.95%   |
| Dell XPS               | 3         | 3.95%   |
| Dell Inspiron          | 3         | 3.95%   |
| HP Notebook            | 2         | 2.63%   |
| Dell Latitude          | 2         | 2.63%   |
| Apple MacBookPro8      | 2         | 2.63%   |
| Apple MacBookPro11     | 2         | 2.63%   |
| Toshiba QOSMIO         | 1         | 1.32%   |
| ShangMai H             | 1         | 1.32%   |
| Samsung 950XDB         | 1         | 1.32%   |
| Samsung 750XEE         | 1         | 1.32%   |
| Samsung 750XED         | 1         | 1.32%   |
| Samsung 550P5C         | 1         | 1.32%   |
| PINNACLEMICRO W76OC    | 1         | 1.32%   |
| Panasonic CF-19ADNAXDA | 1         | 1.32%   |
| OriginPC EON17-X       | 1         | 1.32%   |
| Notebook P65           | 1         | 1.32%   |
| MSI Pulse              | 1         | 1.32%   |
| MSI MS-16Y1            | 1         | 1.32%   |
| MSI GS66               | 1         | 1.32%   |
| MSI GP63               | 1         | 1.32%   |
| LG 16Z90Q-G.AP7BB      | 1         | 1.32%   |
| Lenovo Yoga            | 1         | 1.32%   |
| Lenovo Legion          | 1         | 1.32%   |
| Lenovo IdeaPadFlex     | 1         | 1.32%   |
| Lenovo G700            | 1         | 1.32%   |
| Lenovo G550            | 1         | 1.32%   |
| Lenovo G50-30          | 1         | 1.32%   |
| Lenovo B51-30          | 1         | 1.32%   |
| HUAWEI BOHK-WAX9X      | 1         | 1.32%   |
| HP Laptop              | 1         | 1.32%   |
| HP ENVY                | 1         | 1.32%   |
| HP EliteBook           | 1         | 1.32%   |
| HP Elite               | 1         | 1.32%   |
| HP 255                 | 1         | 1.32%   |
| Hampoo Tablet          | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 8         | 10.53%  |
| 2014 | 8         | 10.53%  |
| 2013 | 8         | 10.53%  |
| 2018 | 7         | 9.21%   |
| 2020 | 6         | 7.89%   |
| 2011 | 6         | 7.89%   |
| 2021 | 5         | 6.58%   |
| 2019 | 5         | 6.58%   |
| 2012 | 5         | 6.58%   |
| 2017 | 4         | 5.26%   |
| 2015 | 4         | 5.26%   |
| 2022 | 3         | 3.95%   |
| 2023 | 2         | 2.63%   |
| 2010 | 2         | 2.63%   |
| 2009 | 2         | 2.63%   |
| 2024 | 1         | 1.32%   |

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
| Disabled | 76        | 100%    |

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


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 43.42%  |
| 32.01-64.0  | 12        | 15.79%  |
| 16.01-24.0  | 11        | 14.47%  |
| 8.01-16.0   | 10        | 13.16%  |
| 3.01-4.0    | 8         | 10.53%  |
| 64.01-256.0 | 1         | 1.32%   |
| 1.01-2.0    | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 28        | 35.9%   |
| 3.01-4.0  | 21        | 26.92%  |
| 2.01-3.0  | 21        | 26.92%  |
| 1.01-2.0  | 6         | 7.69%   |
| 8.01-16.0 | 2         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 71.05%  |
| 2      | 20        | 26.32%  |
| 3      | 2         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 72.37%  |
| Yes       | 21        | 27.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 75%     |
| No        | 19        | 25%     |

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
| Yes       | 65        | 85.53%  |
| No        | 11        | 14.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 19        | 25%     |
| Germany            | 12        | 15.79%  |
| UK                 | 5         | 6.58%   |
| India              | 4         | 5.26%   |
| Poland             | 3         | 3.95%   |
| Italy              | 3         | 3.95%   |
| Spain              | 2         | 2.63%   |
| Russia             | 2         | 2.63%   |
| Kenya              | 2         | 2.63%   |
| France             | 2         | 2.63%   |
| Australia          | 2         | 2.63%   |
| Uruguay            | 1         | 1.32%   |
| Turkey             | 1         | 1.32%   |
| Switzerland        | 1         | 1.32%   |
| Sweden             | 1         | 1.32%   |
| South Africa       | 1         | 1.32%   |
| Portugal           | 1         | 1.32%   |
| Palestine          | 1         | 1.32%   |
| Nepal              | 1         | 1.32%   |
| Namibia            | 1         | 1.32%   |
| Morocco            | 1         | 1.32%   |
| Mexico             | 1         | 1.32%   |
| Malaysia           | 1         | 1.32%   |
| Greece             | 1         | 1.32%   |
| Egypt              | 1         | 1.32%   |
| Dominican Republic | 1         | 1.32%   |
| Colombia           | 1         | 1.32%   |
| Canada             | 1         | 1.32%   |
| Brazil             | 1         | 1.32%   |
| Austria            | 1         | 1.32%   |
| Argentina          | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Nairobi                 | 2         | 2.6%    |
| Birmingham              | 2         | 2.6%    |
| Würzburg               | 1         | 1.3%    |
| Windhoek                | 1         | 1.3%    |
| Walla Walla             | 1         | 1.3%    |
| Versailles              | 1         | 1.3%    |
| Unna                    | 1         | 1.3%    |
| The Bronx               | 1         | 1.3%    |
| Tarnówka               | 1         | 1.3%    |
| Tampa                   | 1         | 1.3%    |
| Sundern                 | 1         | 1.3%    |
| Stuttgart               | 1         | 1.3%    |
| Stratford-upon-Avon     | 1         | 1.3%    |
| Stockton-on-Tees        | 1         | 1.3%    |
| Southwest Harbor        | 1         | 1.3%    |
| Saratov                 | 1         | 1.3%    |
| Sao Domingos de Rana    | 1         | 1.3%    |
| Santo Domingo Este      | 1         | 1.3%    |
| San Antonio             | 1         | 1.3%    |
| Rogers                  | 1         | 1.3%    |
| Rehetobel               | 1         | 1.3%    |
| Pokhara                 | 1         | 1.3%    |
| Perth                   | 1         | 1.3%    |
| Pensacola               | 1         | 1.3%    |
| Paraná                 | 1         | 1.3%    |
| Padova                  | 1         | 1.3%    |
| Ocean Grove             | 1         | 1.3%    |
| Oberursel               | 1         | 1.3%    |
| New York                | 1         | 1.3%    |
| New Delhi               | 1         | 1.3%    |
| Munich                  | 1         | 1.3%    |
| Mumbai                  | 1         | 1.3%    |
| Moscow                  | 1         | 1.3%    |
| Morrisville             | 1         | 1.3%    |
| Montevideo              | 1         | 1.3%    |
| Minneapolis             | 1         | 1.3%    |
| Mexicali                | 1         | 1.3%    |
| Marrakesh               | 1         | 1.3%    |
| Mandriola-Sant'Agostino | 1         | 1.3%    |
| Manchester              | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 20        | 23     | 21.51%  |
| Sandisk                        | 8         | 9      | 8.6%    |
| WDC                            | 7         | 7      | 7.53%   |
| Crucial                        | 7         | 8      | 7.53%   |
| Kingston                       | 5         | 5      | 5.38%   |
| Unknown                        | 4         | 4      | 4.3%    |
| Apple                          | 4         | 5      | 4.3%    |
| Toshiba                        | 3         | 3      | 3.23%   |
| Seagate                        | 3         | 3      | 3.23%   |
| HGST                           | 3         | 4      | 3.23%   |
| China                          | 3         | 3      | 3.23%   |
| SK hynix                       | 2         | 2      | 2.15%   |
| Phison Electronics             | 2         | 3      | 2.15%   |
| Intenso                        | 2         | 2      | 2.15%   |
| Hitachi                        | 2         | 2      | 2.15%   |
| T-FORCE                        | 1         | 1      | 1.08%   |
| StoreJet                       | 1         | 1      | 1.08%   |
| Solid State Storage Technology | 1         | 1      | 1.08%   |
| Patriot                        | 1         | 1      | 1.08%   |
| NT-2TB                         | 1         | 2      | 1.08%   |
| MAS                            | 1         | 1      | 1.08%   |
| LITEON                         | 1         | 1      | 1.08%   |
| KIOXIA                         | 1         | 1      | 1.08%   |
| Kingston Technology Company    | 1         | 1      | 1.08%   |
| KingFast                       | 1         | 1      | 1.08%   |
| Intel                          | 1         | 2      | 1.08%   |
| INNOVATION IT                  | 1         | 1      | 1.08%   |
| HS-SSD-C100                    | 1         | 1      | 1.08%   |
| Gigabyte Technology            | 1         | 1      | 1.08%   |
| BR                             | 1         | 1      | 1.08%   |
| ADATA Technology               | 1         | 1      | 1.08%   |
| A-DATA Technology              | 1         | 1      | 1.08%   |
| Unknown                        | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 5         | 5.15%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 3.09%   |
| Unknown MMC Card  64GB                               | 2         | 2.06%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 2.06%   |
| Sandisk WD Black SN850 1TB                           | 2         | 2.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 2         | 2.06%   |
| HGST HTS725050A7E630 500GB                           | 2         | 2.06%   |
| Apple SSD SM0256F 256GB                              | 2         | 2.06%   |
| WDC WDS500G2B0A-00SM50 500GB                         | 1         | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 1.03%   |
| WDC WD6400BPVT-22HXZT1 640GB                         | 1         | 1.03%   |
| WDC WD5000LPCX-24C6HT0 500GB                         | 1         | 1.03%   |
| WDC WD3200BEVT-00A0RT0 320GB                         | 1         | 1.03%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 1.03%   |
| WDC WD10JPVX-08JC3T6 1TB                             | 1         | 1.03%   |
| Unknown MMC Card  8GB                                | 1         | 1.03%   |
| Unknown MMC Card  128GB                              | 1         | 1.03%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 1         | 1.03%   |
| Toshiba MQ01ABD100 1TB                               | 1         | 1.03%   |
| Toshiba MK7559GSXF 752GB                             | 1         | 1.03%   |
| T-FORCE 1TB                                          | 1         | 1.03%   |
| StoreJet Transcend 1TB                               | 1         | 1.03%   |
| Solid State Storage SSSTC CL1-8D256 256GB            | 1         | 1.03%   |
| SK hynix SC210 mSATA 256GB SSD                       | 1         | 1.03%   |
| SK hynix PC401 NVMe Solid State Drive 256GB          | 1         | 1.03%   |
| Seagate ST9250315AS 250GB                            | 1         | 1.03%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB         | 1         | 1.03%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 1         | 1.03%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB      | 1         | 1.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 1         | 1.03%   |
| SanDisk SSD PLUS 120 GB                              | 1         | 1.03%   |
| SanDisk SSD PLUS 1000GB                              | 1         | 1.03%   |
| Samsung SSD PM851 mSATA 128GB                        | 1         | 1.03%   |
| Samsung SSD 870 EVO 1TB                              | 1         | 1.03%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 1.03%   |
| Samsung SSD 850 PRO 256GB                            | 1         | 1.03%   |
| Samsung SSD 850 EVO 250GB                            | 1         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 1         | 1.03%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB        | 1         | 1.03%   |
| Samsung MZVLQ256HBJD-00B 256GB                       | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 31.25%  |
| Seagate | 3         | 3      | 18.75%  |
| HGST    | 3         | 4      | 18.75%  |
| Toshiba | 2         | 2      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| T-FORCE | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 25%     |
| Crucial             | 7         | 8      | 17.5%   |
| China               | 3         | 3      | 7.5%    |
| Apple               | 3         | 3      | 7.5%    |
| WDC                 | 2         | 2      | 5%      |
| SanDisk             | 2         | 3      | 5%      |
| Kingston            | 2         | 2      | 5%      |
| Intenso             | 2         | 2      | 5%      |
| StoreJet            | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| Patriot             | 1         | 1      | 2.5%    |
| NT-2TB              | 1         | 2      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| KingFast            | 1         | 1      | 2.5%    |
| INNOVATION IT       | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 36        | 44     | 40.45%  |
| NVMe    | 29        | 34     | 32.58%  |
| HDD     | 16        | 17     | 17.98%  |
| MMC     | 4         | 4      | 4.49%   |
| Unknown | 4         | 4      | 4.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 63     | 59.77%  |
| NVMe | 29        | 34     | 33.33%  |
| MMC  | 4         | 4      | 4.6%    |
| SAS  | 2         | 2      | 2.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 39     | 64.81%  |
| 0.51-1.0   | 15        | 17     | 27.78%  |
| 1.01-2.0   | 3         | 4      | 5.56%   |
| 3.01-4.0   | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 36.84%  |
| 501-1000       | 18        | 23.68%  |
| 251-500        | 16        | 21.05%  |
| 1001-2000      | 4         | 5.26%   |
| 51-100         | 3         | 3.95%   |
| More than 3000 | 2         | 2.63%   |
| 1-20           | 2         | 2.63%   |
| Unknown        | 2         | 2.63%   |
| 21-50          | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 38.96%  |
| 21-50          | 27        | 35.06%  |
| 51-100         | 9         | 11.69%  |
| 101-250        | 5         | 6.49%   |
| 251-500        | 2         | 2.6%    |
| Unknown        | 2         | 2.6%    |
| More than 3000 | 1         | 1.3%    |
| 501-1000       | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 75        | 99     | 97.4%   |
| Works    | 2         | 4      | 2.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 49        | 55.06%  |
| Samsung Electronics            | 12        | 13.48%  |
| AMD                            | 8         | 8.99%   |
| SanDisk                        | 6         | 6.74%   |
| Kingston Technology Company    | 4         | 4.49%   |
| Phison Electronics             | 2         | 2.25%   |
| Toshiba America Info Systems   | 1         | 1.12%   |
| Solid State Storage Technology | 1         | 1.12%   |
| SK hynix                       | 1         | 1.12%   |
| Nvidia                         | 1         | 1.12%   |
| Marvell Technology Group       | 1         | 1.12%   |
| KIOXIA                         | 1         | 1.12%   |
| Apple                          | 1         | 1.12%   |
| ADATA Technology               | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 6.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 6.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 6.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 6.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 6.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 5.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 4.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.16%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 2.11%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 2.11%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 2         | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.05%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 1.05%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.05%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 1.05%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 1.05%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.05%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.05%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                              | 1         | 1.05%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.05%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.05%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.05%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                             | 1         | 1.05%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                             | 1         | 1.05%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 1         | 1.05%   |
| Intel RST Volume Management Device Controller                                    | 1         | 1.05%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 1         | 1.05%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 56.99%  |
| NVMe | 29        | 31.18%  |
| RAID | 9         | 9.68%   |
| IDE  | 2         | 2.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 89.47%  |
| AMD    | 8         | 10.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 3.95%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 2.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.63%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 2         | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.63%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 2.63%   |
| Intel 12th Gen Core i7-1260P                | 2         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.32%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.32%   |
| Intel Genuine CPU 0000 @ 2.60GHz            | 1         | 1.32%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.32%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.32%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.32%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.32%   |
| Intel Core i7-3687U CPU @ 2.10GHz           | 1         | 1.32%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i7-2675QM CPU @ 2.20GHz          | 1         | 1.32%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.32%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 27.63%  |
| Intel Core i5           | 20        | 26.32%  |
| Other                   | 12        | 15.79%  |
| Intel Core i3           | 4         | 5.26%   |
| Intel Pentium           | 3         | 3.95%   |
| AMD A6                  | 3         | 3.95%   |
| Intel Core 2 Duo        | 2         | 2.63%   |
| Intel Celeron           | 2         | 2.63%   |
| AMD Ryzen 5             | 2         | 2.63%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Genuine           | 1         | 1.32%   |
| Intel Core m7           | 1         | 1.32%   |
| Intel Atom              | 1         | 1.32%   |
| AMD Ryzen 7             | 1         | 1.32%   |
| AMD E2                  | 1         | 1.32%   |
| AMD A10                 | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 50%     |
| 4      | 25        | 32.89%  |
| 6      | 7         | 9.21%   |
| 12     | 3         | 3.95%   |
| 24     | 1         | 1.32%   |
| 10     | 1         | 1.32%   |
| 8      | 1         | 1.32%   |

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
| 2      | 63        | 82.89%  |
| 1      | 13        | 17.11%  |

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


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Haswell       | 14        | 18.42%  |
| KabyLake      | 12        | 15.79%  |
| SandyBridge   | 8         | 10.53%  |
| Unknown       | 7         | 9.21%   |
| TigerLake     | 5         | 6.58%   |
| IvyBridge     | 5         | 6.58%   |
| Skylake       | 4         | 5.26%   |
| Zen+          | 3         | 3.95%   |
| Silvermont    | 3         | 3.95%   |
| Puma          | 3         | 3.95%   |
| Penryn        | 3         | 3.95%   |
| CometLake     | 3         | 3.95%   |
| Westmere      | 1         | 1.32%   |
| Piledriver    | 1         | 1.32%   |
| IceLake       | 1         | 1.32%   |
| Goldmont plus | 1         | 1.32%   |
| Excavator     | 1         | 1.32%   |
| Broadwell     | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 65%     |
| Nvidia | 25        | 25%     |
| AMD    | 10        | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 8.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 3.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.88%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 2.91%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 3         | 2.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.94%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.94%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.94%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.97%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.97%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.97%   |
| Nvidia GM204M [GeForce GTX 965M]                                                         | 1         | 0.97%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.97%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.97%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.97%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.97%   |
| Nvidia GK104M [GeForce GTX 880M]                                                         | 1         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.97%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.97%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.97%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.97%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.97%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 1         | 0.97%   |
| Nvidia AD104M [GeForce RTX 4080 Max-Q / Mobile]                                          | 1         | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.97%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 55.26%  |
| Intel + Nvidia | 20        | 26.32%  |
| 1 x AMD        | 6         | 7.89%   |
| 1 x Nvidia     | 3         | 3.95%   |
| Intel + AMD    | 2         | 2.63%   |
| 2 x Nvidia     | 1         | 1.32%   |
| 2 x AMD        | 1         | 1.32%   |
| AMD + Nvidia   | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 66        | 86.84%  |
| Proprietary | 9         | 11.84%  |
| Unknown     | 1         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 97.37%  |
| 7.01-8.0   | 1         | 1.32%   |
| 1.01-2.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 18.75%  |
| LG Display              | 12        | 15%     |
| Chimei Innolux          | 12        | 15%     |
| Samsung Electronics     | 11        | 13.75%  |
| BOE                     | 11        | 13.75%  |
| Apple                   | 6         | 7.5%    |
| Sharp                   | 4         | 5%      |
| Philips                 | 2         | 2.5%    |
| PANDA                   | 1         | 1.25%   |
| KDB                     | 1         | 1.25%   |
| InnoLux Display         | 1         | 1.25%   |
| InfoVision              | 1         | 1.25%   |
| Goldstar                | 1         | 1.25%   |
| Chi Mei Optoelectronics | 1         | 1.25%   |
| AOC                     | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM5448 1920x1080                      | 2         | 2.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 2         | 2.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 2.5%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 1         | 1.25%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch                | 1         | 1.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 1.25%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 1.25%   |
| Samsung Electronics F24G3xTF SAM710A 1920x1080 527x296mm 23.8-inch     | 1         | 1.25%   |
| Philips PHL345E2LE PHLC29D 3440x1440 797x334mm 34.0-inch               | 1         | 1.25%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 1.25%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 1.25%   |
| LG Display LP156WH2-TLQ1 LGD021B 1366x768 344x194mm 15.5-inch          | 1         | 1.25%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD070A 1920x1080 309x174mm 14.0-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD06EB 2560x1600 344x215mm 16.0-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD054C 1920x1080 276x156mm 12.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD03E0 1366x768 345x194mm 15.6-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch            | 1         | 1.25%   |
| KDB LCD Monitor KDB0526 1920x1080 344x194mm 15.5-inch                  | 1         | 1.25%   |
| InnoLux Display LCD Monitor INL0005 1366x768 344x194mm 15.5-inch       | 1         | 1.25%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch           | 1         | 1.25%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                    | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 41.77%  |
| 1366x768 (WXGA)    | 22        | 27.85%  |
| 2560x1600          | 3         | 3.8%    |
| 1600x900 (HD+)     | 3         | 3.8%    |
| 1280x800 (WXGA)    | 3         | 3.8%    |
| 3840x2160 (4K)     | 2         | 2.53%   |
| 3200x1800 (QHD+)   | 2         | 2.53%   |
| 2560x1440 (QHD)    | 2         | 2.53%   |
| 1440x900 (WXGA+)   | 2         | 2.53%   |
| 3440x1440          | 1         | 1.27%   |
| 2880x1800          | 1         | 1.27%   |
| 2160x1440          | 1         | 1.27%   |
| 1920x1280          | 1         | 1.27%   |
| 1920x1200 (WUXGA)  | 1         | 1.27%   |
| 1680x945           | 1         | 1.27%   |
| 1680x1050 (WSXGA+) | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 36        | 45%     |
| 13      | 12        | 15%     |
| 17      | 7         | 8.75%   |
| 14      | 7         | 8.75%   |
| 12      | 5         | 6.25%   |
| 16      | 3         | 3.75%   |
| Unknown | 2         | 2.5%    |
| 65      | 1         | 1.25%   |
| 48      | 1         | 1.25%   |
| 34      | 1         | 1.25%   |
| 24      | 1         | 1.25%   |
| 23      | 1         | 1.25%   |
| 21      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |
| 18      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 61.25%  |
| 201-300     | 13        | 16.25%  |
| 351-400     | 8         | 10%     |
| 401-500     | 3         | 3.75%   |
| 501-600     | 2         | 2.5%    |
| 1001-1500   | 2         | 2.5%    |
| Unknown     | 2         | 2.5%    |
| 701-800     | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 82.89%  |
| 16/10 | 11        | 14.47%  |
| 3/2   | 1         | 1.32%   |
| 21/9  | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 45%     |
| 81-90          | 14        | 17.5%   |
| 121-130        | 7         | 8.75%   |
| 71-80          | 5         | 6.25%   |
| 61-70          | 5         | 6.25%   |
| 111-120        | 3         | 3.75%   |
| More than 1000 | 2         | 2.5%    |
| 201-250        | 2         | 2.5%    |
| Unknown        | 2         | 2.5%    |
| 351-500        | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 151-200        | 1         | 1.25%   |
| 141-150        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 38.75%  |
| 101-120       | 30        | 37.5%   |
| 161-240       | 7         | 8.75%   |
| More than 240 | 5         | 6.25%   |
| 51-100        | 3         | 3.75%   |
| 1-50          | 2         | 2.5%    |
| Unknown       | 2         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 68        | 89.47%  |
| 2     | 4         | 5.26%   |
| 3     | 2         | 2.63%   |
| 0     | 2         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 32.03%  |
| Realtek Semiconductor           | 33        | 25.78%  |
| Broadcom                        | 17        | 13.28%  |
| Qualcomm Atheros                | 14        | 10.94%  |
| Broadcom Limited                | 5         | 3.91%   |
| Samsung Electronics             | 3         | 2.34%   |
| TP-Link                         | 2         | 1.56%   |
| Google                          | 2         | 1.56%   |
| Shenzhen Goodix Technology      | 1         | 0.78%   |
| Ralink Technology               | 1         | 0.78%   |
| Qualcomm Atheros Communications | 1         | 0.78%   |
| Nvidia                          | 1         | 0.78%   |
| JMicron Technology              | 1         | 0.78%   |
| Huawei Technologies             | 1         | 0.78%   |
| Hewlett-Packard                 | 1         | 0.78%   |
| Fibocom                         | 1         | 0.78%   |
| DisplayLink                     | 1         | 0.78%   |
| AVM                             | 1         | 0.78%   |
| Apple                           | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 13.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.08%   |
| Intel Wireless 8265 / 8275                                             | 5         | 3.4%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 2.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 2.72%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 2.72%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.04%   |
| Intel Wireless 7265                                                    | 3         | 2.04%   |
| Intel Wireless 7260                                                    | 3         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2         | 1.36%   |
| Intel Wireless 3165                                                    | 2         | 1.36%   |
| Intel Wireless 3160                                                    | 2         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.36%   |
| Intel Centrino Advanced-N 6235                                         | 2         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.36%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                     | 2         | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.68%   |
| Shenzhen Goodix Fingerprint Reader                                     | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.68%   |
| Realtek 802.11ac NIC                                                   | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 45.78%  |
| Broadcom                        | 15        | 18.07%  |
| Realtek Semiconductor           | 10        | 12.05%  |
| Qualcomm Atheros                | 9         | 10.84%  |
| Broadcom Limited                | 5         | 6.02%   |
| TP-Link                         | 2         | 2.41%   |
| Ralink Technology               | 1         | 1.2%    |
| Qualcomm Atheros Communications | 1         | 1.2%    |
| Fibocom                         | 1         | 1.2%    |
| AVM                             | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 5         | 6.02%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 4.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 4.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 4         | 4.82%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 4.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 3.61%   |
| Intel Wireless 7265                                                  | 3         | 3.61%   |
| Intel Wireless 7260                                                  | 3         | 3.61%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 3.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 2.41%   |
| Intel Wireless 3165                                                  | 2         | 2.41%   |
| Intel Wireless 3160                                                  | 2         | 2.41%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.41%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.41%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 2         | 2.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.2%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 1.2%    |
| Realtek 802.11ac NIC                                                 | 1         | 1.2%    |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 1.2%    |
| Intel Wireless 8260                                                  | 1         | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1         | 1.2%    |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 1.2%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 1         | 1.2%    |
| Intel Centrino Wireless-N 100                                        | 1         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 1.2%    |
| Intel 700 Series Chipset CNVi WiFi                                   | 1         | 1.2%    |
| Fibocom L830-EB-00 LTE WWAN Modem                                    | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 42.86%  |
| Intel                 | 14        | 22.22%  |
| Qualcomm Atheros      | 6         | 9.52%   |
| Broadcom              | 5         | 7.94%   |
| Samsung Electronics   | 3         | 4.76%   |
| Google                | 2         | 3.17%   |
| Nvidia                | 1         | 1.59%   |
| JMicron Technology    | 1         | 1.59%   |
| Huawei Technologies   | 1         | 1.59%   |
| Hewlett-Packard       | 1         | 1.59%   |
| DisplayLink           | 1         | 1.59%   |
| Apple                 | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 31.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 9.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 4.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 4.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.59%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.59%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 1.59%   |
| Intel Ethernet Controller I226-K                                       | 1         | 1.59%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.59%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.59%   |
| Huawei E353/E3131                                                      | 1         | 1.59%   |
| HP HP lt4120 Snapdragon X5 LTE                                         | 1         | 1.59%   |
| Google Pixel 9a                                                        | 1         | 1.59%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.59%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 1.59%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 56.39%  |
| Ethernet | 57        | 42.86%  |
| Modem    | 1         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 76.32%  |
| Ethernet | 18        | 23.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 68.42%  |
| 1     | 23        | 30.26%  |
| 0     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 68.42%  |
| Yes  | 24        | 31.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 53.03%  |
| Apple                           | 7         | 10.61%  |
| Realtek Semiconductor           | 6         | 9.09%   |
| Qualcomm Atheros Communications | 5         | 7.58%   |
| Broadcom                        | 5         | 7.58%   |
| Lite-On Technology              | 2         | 3.03%   |
| IMC Networks                    | 2         | 3.03%   |
| Realtek                         | 1         | 1.52%   |
| Foxconn International           | 1         | 1.52%   |
| Dell                            | 1         | 1.52%   |
| Alps Electric                   | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 15        | 22.73%  |
| Intel AX201 Bluetooth                             | 9         | 13.64%  |
| Apple Bluetooth Host Controller                   | 5         | 7.58%   |
| Realtek Bluetooth Radio                           | 4         | 6.06%   |
| Intel Bluetooth Device                            | 4         | 6.06%   |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                | 2         | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 3.03%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]       | 2         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 3.03%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 3.03%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 3.03%   |
| Apple Bluetooth USB Host Controller               | 2         | 3.03%   |
| Realtek Bluetooth Radio                           | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.52%   |
| Intel AX210 Bluetooth                             | 1         | 1.52%   |
| Intel AX200 Bluetooth                             | 1         | 1.52%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.52%   |
| IMC Networks Bluetooth Device                     | 1         | 1.52%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.52%   |
| Dell Broadcom BCM20702A0 Bluetooth                | 1         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth Device              | 1         | 1.52%   |
| Alps Electric UGTZ4 Bluetooth                     | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 66        | 70.21%  |
| Nvidia                 | 17        | 18.09%  |
| AMD                    | 9         | 9.57%   |
| SteelSeries ApS        | 1         | 1.06%   |
| Generalplus Technology | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 8.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 7.83%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 7.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 6.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 3.48%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.48%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.61%   |
| AMD Ryzen HD Audio Controller                                                                     | 3         | 2.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.74%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                                          | 1         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.87%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia AD104 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.87%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.87%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 1         | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.87%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 50%     |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 50%     |
| DDR3   | 1         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1         | 50%     |
| Row Of Chips | 1         | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 2         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4267  | 1         | 50%     |
| 2667  | 1         | 50%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung C48x Series | 1         | 100%    |

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
| Chicony Electronics                    | 14        | 20.9%   |
| Bison Electronics                      | 12        | 17.91%  |
| Sunplus Innovation Technology          | 5         | 7.46%   |
| Apple                                  | 5         | 7.46%   |
| Realtek Semiconductor                  | 4         | 5.97%   |
| Quanta                                 | 3         | 4.48%   |
| Microdia                               | 3         | 4.48%   |
| Syntek                                 | 2         | 2.99%   |
| Suyin                                  | 2         | 2.99%   |
| SunplusIT                              | 2         | 2.99%   |
| Silicon Motion                         | 2         | 2.99%   |
| Luxvisions Innotech Limited            | 2         | 2.99%   |
| Lite-On Technology                     | 2         | 2.99%   |
| IMC Networks                           | 2         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.99%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.49%   |
| Samsung Electronics                    | 1         | 1.49%   |
| Logitech                               | 1         | 1.49%   |
| Lenovo                                 | 1         | 1.49%   |
| Alcor Micro                            | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 3         | 4.48%   |
| Apple FaceTime HD Camera                            | 3         | 4.48%   |
| SunplusIT 720p HD Camera                            | 2         | 2.99%   |
| Sunplus HD WebCam                                   | 2         | 2.99%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.99%   |
| Realtek Integrated Camera                           | 2         | 2.99%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.99%   |
| Chicony HP TrueVision HD                            | 2         | 2.99%   |
| Chicony HP HD Webcam                                | 2         | 2.99%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.99%   |
| Bison HD Webcam                                     | 2         | 2.99%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.49%   |
| Syntek Integrated Camera                            | 1         | 1.49%   |
| Suyin HP Webcam                                     | 1         | 1.49%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.49%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.49%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.49%   |
| Sunplus 1.3M HD WebCam                              | 1         | 1.49%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 1.49%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 1.49%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 1         | 1.49%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.49%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 1.49%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.49%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.49%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.49%   |
| Luxvisions Innotech Limited LGE Camera              | 1         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.49%   |
| Logitech QuickCam Pro 9000                          | 1         | 1.49%   |
| Lite-On TOSHIBA Web Camera - FHD                    | 1         | 1.49%   |
| Lite-On HP HD Camera                                | 1         | 1.49%   |
| Lenovo Lenovo FHD Webcam Audio                      | 1         | 1.49%   |
| IMC Networks ov9734_azurewave_camera                | 1         | 1.49%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.49%   |
| Chicony HP Webcam                                   | 1         | 1.49%   |
| Chicony HP HD Camera                                | 1         | 1.49%   |
| Chicony HD WebCam                                   | 1         | 1.49%   |
| Chicony FJ Camera                                   | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 72.73%  |
| Synaptics                  | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 36.36%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 18.18%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 18.18%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Alcor Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 53.95%  |
| 1     | 28        | 36.84%  |
| 2     | 5         | 6.58%   |
| 4     | 1         | 1.32%   |
| 3     | 1         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 28.26%  |
| Fingerprint reader       | 11        | 23.91%  |
| Multimedia controller    | 6         | 13.04%  |
| Net/wireless             | 5         | 10.87%  |
| Chipcard                 | 5         | 10.87%  |
| Camera                   | 2         | 4.35%   |
| Net/ethernet             | 1         | 2.17%   |
| Modem                    | 1         | 2.17%   |
| Communication controller | 1         | 2.17%   |
| Bluetooth                | 1         | 2.17%   |


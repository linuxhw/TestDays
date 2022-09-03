Linux in Puerto Rico - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBook4,1                  | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | [c444890ad0](https://linux-hardware.org/?probe=c444890ad0) | Jul 21, 2022 |
| Apple         | MacBook4,1                  | [9122678102](https://linux-hardware.org/?probe=9122678102) | Jul 21, 2022 |
| Apple         | MacBook4,1                  | [69d676f7be](https://linux-hardware.org/?probe=69d676f7be) | Jul 12, 2022 |
| Apple         | MacBook4,1                  | [9d8195a435](https://linux-hardware.org/?probe=9d8195a435) | Jul 12, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | [a42903b516](https://linux-hardware.org/?probe=a42903b516) | Jul 10, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | [404e81318c](https://linux-hardware.org/?probe=404e81318c) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Dell          | Vostro 3550                 | [d0cfec8d80](https://linux-hardware.org/?probe=d0cfec8d80) | Jul 04, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| Dell          | Vostro 3550                 | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | Latitude E6330              | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| Dell          | Inspiron 17-7778            | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Dell          | Vostro 3550                 | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| Sony          | VGN-CS320J                  | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Acer          | Swift SF315-52              | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| GPU Compan... | GWTN156-9                   | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| Dell          | Vostro 3550                 | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| Dell          | Inspiron N5110              | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| Lenovo        | G50-45 80E3                 | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | ENVY dv7                    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| MSI           | GF65 Thin 10SDR             | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| HP            | Laptop 14-dk1xxx            | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| MSI           | GF65 Thin 10SDR             | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | K53E                        | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| MSI           | GF65 Thin 10SDR             | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| AZW           | GT-R                        | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Dell          | Inspiron 11-3168            | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Dell          | Latitude E6410              | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| Apple         | MacBookPro8,1               | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | ENVY dv7                    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| Acer          | Swift SF314-51              | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| HP            | Laptop 15-dy1xxx            | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| HP            | ENVY dv7                    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| ASUSTek       | X540SAA                     | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| HP            | ENVY dv7                    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Acer          | Aspire E5-575               | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Dell          | Inspiron 5559               | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| HP            | Notebook                    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| Dell          | Inspiron MP061              | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 17        | 30.91%  |
| Ubuntu 18.04        | 5         | 9.09%   |
| Ubuntu 22.04        | 4         | 7.27%   |
| Ubuntu 21.10        | 2         | 3.64%   |
| OpenMandriva 4.3    | 2         | 3.64%   |
| OpenMandriva 4.2    | 2         | 3.64%   |
| Linux Mint 19.3     | 2         | 3.64%   |
| BlackPanther 18.1   | 2         | 3.64%   |
| Zorin 16            | 1         | 1.82%   |
| Xubuntu 20.04       | 1         | 1.82%   |
| Ubuntu MATE 20.04   | 1         | 1.82%   |
| Ubuntu 19.10        | 1         | 1.82%   |
| ROSA R10            | 1         | 1.82%   |
| Peppermint 9        | 1         | 1.82%   |
| Parrot 5.0          | 1         | 1.82%   |
| Parrot 4.11         | 1         | 1.82%   |
| openSUSE Leap-15.2  | 1         | 1.82%   |
| OpenMandriva 4.50   | 1         | 1.82%   |
| Linux Mint 21       | 1         | 1.82%   |
| Linux Mint 20.1     | 1         | 1.82%   |
| KDE neon 20.04      | 1         | 1.82%   |
| Fedora 36           | 1         | 1.82%   |
| Fedora 33           | 1         | 1.82%   |
| Endless 3.7.8       | 1         | 1.82%   |
| EndeavourOS Rolling | 1         | 1.82%   |
| Debian 10           | 1         | 1.82%   |
| Arch Rolling        | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 28        | 51.85%  |
| OpenMandriva | 5         | 9.26%   |
| Linux Mint   | 4         | 7.41%   |
| Parrot       | 2         | 3.7%    |
| Fedora       | 2         | 3.7%    |
| BlackPanther | 2         | 3.7%    |
| Zorin        | 1         | 1.85%   |
| Xubuntu      | 1         | 1.85%   |
| Ubuntu MATE  | 1         | 1.85%   |
| ROSA         | 1         | 1.85%   |
| Peppermint   | 1         | 1.85%   |
| openSUSE     | 1         | 1.85%   |
| KDE neon     | 1         | 1.85%   |
| Endless      | 1         | 1.85%   |
| EndeavourOS  | 1         | 1.85%   |
| Debian       | 1         | 1.85%   |
| Arch         | 1         | 1.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.8.0-59-generic              | 3         | 4.62%   |
| 5.8.0-55-generic              | 2         | 3.08%   |
| 5.4.0-58-generic              | 2         | 3.08%   |
| 5.16.7-desktop-1omv4003       | 2         | 3.08%   |
| 5.15.0-46-generic             | 2         | 3.08%   |
| 5.13.0-35-generic             | 2         | 3.08%   |
| 5.11.0-38-generic             | 2         | 3.08%   |
| 5.11.0-27-generic             | 2         | 3.08%   |
| 5.10.14-desktop-1omv4002      | 2         | 3.08%   |
| 5.9.16-200.fc33.x86_64        | 1         | 1.54%   |
| 5.8.0-63-generic              | 1         | 1.54%   |
| 5.6.14-desktop-2bP            | 1         | 1.54%   |
| 5.4.0-84-generic              | 1         | 1.54%   |
| 5.4.0-77-generic              | 1         | 1.54%   |
| 5.4.0-73-generic              | 1         | 1.54%   |
| 5.4.0-70-generic              | 1         | 1.54%   |
| 5.4.0-62-generic              | 1         | 1.54%   |
| 5.4.0-60-generic              | 1         | 1.54%   |
| 5.4.0-55-generic              | 1         | 1.54%   |
| 5.4.0-52-generic              | 1         | 1.54%   |
| 5.4.0-48-generic              | 1         | 1.54%   |
| 5.4.0-47-generic              | 1         | 1.54%   |
| 5.4.0-40-generic              | 1         | 1.54%   |
| 5.4.0-29-generic              | 1         | 1.54%   |
| 5.3.6-050306-generic          | 1         | 1.54%   |
| 5.3.18-lp152.57-default       | 1         | 1.54%   |
| 5.3.0-41-generic              | 1         | 1.54%   |
| 5.3.0-40-generic              | 1         | 1.54%   |
| 5.3.0-28-generic              | 1         | 1.54%   |
| 5.18.6-200.fc36.x86_64        | 1         | 1.54%   |
| 5.18.0-1parrot1-amd64         | 1         | 1.54%   |
| 5.15.59-1-lts                 | 1         | 1.54%   |
| 5.15.0-41-generic             | 1         | 1.54%   |
| 5.15.0-40-generic             | 1         | 1.54%   |
| 5.15.0-25-generic             | 1         | 1.54%   |
| 5.13.0-51-generic             | 1         | 1.54%   |
| 5.13.0-44-generic             | 1         | 1.54%   |
| 5.13.0-40-generic             | 1         | 1.54%   |
| 5.13.0-37-generic             | 1         | 1.54%   |
| 5.13.0-30-generic             | 1         | 1.54%   |
| 5.13.0-28-generic             | 1         | 1.54%   |
| 5.13.0-27-generic             | 1         | 1.54%   |
| 5.13.0-22-generic             | 1         | 1.54%   |
| 5.12.4-desktop-1omv4050       | 1         | 1.54%   |
| 5.11.16-zen1-1-zen            | 1         | 1.54%   |
| 5.11.0-41-generic             | 1         | 1.54%   |
| 5.10.0-6parrot1-amd64         | 1         | 1.54%   |
| 4.9.60-nrj-desktop-1rosa-i586 | 1         | 1.54%   |
| 4.19.0-9-amd64                | 1         | 1.54%   |
| 4.18.16-desktop-1bP           | 1         | 1.54%   |
| 4.15.0-99-generic             | 1         | 1.54%   |
| 4.15.0-91-generic             | 1         | 1.54%   |
| 4.15.0-88-generic             | 1         | 1.54%   |
| 4.15.0-43-generic             | 1         | 1.54%   |
| 4.15.0-29-generic             | 1         | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 23.64%  |
| 5.13.0  | 6         | 10.91%  |
| 5.11.0  | 5         | 9.09%   |
| 5.8.0   | 4         | 7.27%   |
| 5.15.0  | 4         | 7.27%   |
| 5.3.0   | 3         | 5.45%   |
| 4.15.0  | 3         | 5.45%   |
| 5.16.7  | 2         | 3.64%   |
| 5.10.14 | 2         | 3.64%   |
| 5.9.16  | 1         | 1.82%   |
| 5.6.14  | 1         | 1.82%   |
| 5.3.6   | 1         | 1.82%   |
| 5.3.18  | 1         | 1.82%   |
| 5.18.6  | 1         | 1.82%   |
| 5.18.0  | 1         | 1.82%   |
| 5.15.59 | 1         | 1.82%   |
| 5.12.4  | 1         | 1.82%   |
| 5.11.16 | 1         | 1.82%   |
| 5.10.0  | 1         | 1.82%   |
| 4.9.60  | 1         | 1.82%   |
| 4.19.0  | 1         | 1.82%   |
| 4.18.16 | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 24.07%  |
| 5.13    | 6         | 11.11%  |
| 5.11    | 6         | 11.11%  |
| 5.3     | 5         | 9.26%   |
| 5.15    | 5         | 9.26%   |
| 5.8     | 4         | 7.41%   |
| 5.10    | 3         | 5.56%   |
| 4.15    | 3         | 5.56%   |
| 5.16    | 2         | 3.7%    |
| 5.9     | 1         | 1.85%   |
| 5.6     | 1         | 1.85%   |
| 5.18    | 1         | 1.85%   |
| 5.12    | 1         | 1.85%   |
| 4.9     | 1         | 1.85%   |
| 4.19    | 1         | 1.85%   |
| 4.18    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 47        | 95.92%  |
| i686   | 2         | 4.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 28        | 53.85%  |
| KDE5       | 10        | 19.23%  |
| MATE       | 4         | 7.69%   |
| XFCE       | 2         | 3.85%   |
| X-Cinnamon | 2         | 3.85%   |
| Unknown    | 2         | 3.85%   |
| Unity      | 1         | 1.92%   |
| LXDE       | 1         | 1.92%   |
| KDE4       | 1         | 1.92%   |
| i3         | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 45        | 88.24%  |
| Wayland | 6         | 11.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 52.83%  |
| GDM3    | 11        | 20.75%  |
| SDDM    | 7         | 13.21%  |
| TDM     | 2         | 3.77%   |
| LightDM | 2         | 3.77%   |
| GDM     | 2         | 3.77%   |
| KDM     | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 41        | 82%     |
| Unknown | 5         | 10%     |
| es_PR   | 3         | 6%      |
| C       | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 54%     |
| EFI  | 23        | 46%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 72%     |
| Overlay | 7         | 14%     |
| Btrfs   | 4         | 8%      |
| Unknown | 2         | 4%      |
| Zfs     | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 68.63%  |
| GPT     | 13        | 25.49%  |
| MBR     | 3         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 84.31%  |
| Yes       | 8         | 15.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 74%     |
| Yes       | 13        | 26%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 14        | 28.57%  |
| Dell             | 12        | 24.49%  |
| Lenovo           | 4         | 8.16%   |
| Acer             | 4         | 8.16%   |
| Toshiba          | 3         | 6.12%   |
| Apple            | 3         | 6.12%   |
| Sony             | 2         | 4.08%   |
| ASUSTek Computer | 2         | 4.08%   |
| TUXEDO           | 1         | 2.04%   |
| MSI              | 1         | 2.04%   |
| GPU Company      | 1         | 2.04%   |
| AZW              | 1         | 2.04%   |
| AMI              | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Vostro 3550                    | 3         | 6.12%   |
| TUXEDO Aura 15 Gen1                 | 1         | 2.04%   |
| Toshiba Satellite P755              | 1         | 2.04%   |
| Toshiba Satellite L655              | 1         | 2.04%   |
| Toshiba Satellite C55-C             | 1         | 2.04%   |
| Sony VPCEA36FX                      | 1         | 2.04%   |
| Sony VGN-CS320J                     | 1         | 2.04%   |
| MSI GF65 Thin 10SDR                 | 1         | 2.04%   |
| Lenovo ThinkPad T410 2516ADU        | 1         | 2.04%   |
| Lenovo ThinkPad E14 20RA004WUS      | 1         | 2.04%   |
| Lenovo IdeaPad 120S-11IAP 81A4      | 1         | 2.04%   |
| Lenovo G50-45 80E3                  | 1         | 2.04%   |
| HP Stream Laptop 14-CB1xxx          | 1         | 2.04%   |
| HP ProBook 6560b                    | 1         | 2.04%   |
| HP ProBook 6450b                    | 1         | 2.04%   |
| HP ProBook 450 G5                   | 1         | 2.04%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 1         | 2.04%   |
| HP Notebook                         | 1         | 2.04%   |
| HP Laptop 15-dy1xxx                 | 1         | 2.04%   |
| HP Laptop 15-dw0xxx                 | 1         | 2.04%   |
| HP Laptop 14-dk1xxx                 | 1         | 2.04%   |
| HP ENVY Laptop 17m-bw0xxx           | 1         | 2.04%   |
| HP ENVY Laptop 17-ce1xxx            | 1         | 2.04%   |
| HP ENVY dv7                         | 1         | 2.04%   |
| HP EliteBook 840 G2                 | 1         | 2.04%   |
| HP Compaq nc6400 (RB516UT#ABA)      | 1         | 2.04%   |
| GPU Company GWTN156-9               | 1         | 2.04%   |
| Dell Venue 11 Pro 7130 MS           | 1         | 2.04%   |
| Dell Precision M4700                | 1         | 2.04%   |
| Dell Latitude E6410                 | 1         | 2.04%   |
| Dell Latitude E6330                 | 1         | 2.04%   |
| Dell Inspiron N5110                 | 1         | 2.04%   |
| Dell Inspiron MP061                 | 1         | 2.04%   |
| Dell Inspiron 5559                  | 1         | 2.04%   |
| Dell Inspiron 17-7778               | 1         | 2.04%   |
| Dell Inspiron 11-3168               | 1         | 2.04%   |
| AZW GT-R                            | 1         | 2.04%   |
| ASUS X540SAA                        | 1         | 2.04%   |
| ASUS K53E                           | 1         | 2.04%   |
| Apple MacBookPro8,1                 | 1         | 2.04%   |
| Apple MacBookPro5,1                 | 1         | 2.04%   |
| Apple MacBook4,1                    | 1         | 2.04%   |
| AMI Intel                           | 1         | 2.04%   |
| Acer Swift SF315-52                 | 1         | 2.04%   |
| Acer Swift SF314-51                 | 1         | 2.04%   |
| Acer Aspire E5-575                  | 1         | 2.04%   |
| Acer Aspire E5-571                  | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 5         | 10.2%   |
| Toshiba Satellite     | 3         | 6.12%   |
| HP ProBook            | 3         | 6.12%   |
| HP Laptop             | 3         | 6.12%   |
| HP ENVY               | 3         | 6.12%   |
| Dell Vostro           | 3         | 6.12%   |
| Lenovo ThinkPad       | 2         | 4.08%   |
| Dell Latitude         | 2         | 4.08%   |
| Acer Swift            | 2         | 4.08%   |
| Acer Aspire           | 2         | 4.08%   |
| TUXEDO Aura           | 1         | 2.04%   |
| Sony VPCEA36FX        | 1         | 2.04%   |
| Sony VGN-CS320J       | 1         | 2.04%   |
| MSI GF65              | 1         | 2.04%   |
| Lenovo IdeaPad        | 1         | 2.04%   |
| Lenovo G50-45         | 1         | 2.04%   |
| HP Stream             | 1         | 2.04%   |
| HP Pavilion           | 1         | 2.04%   |
| HP Notebook           | 1         | 2.04%   |
| HP EliteBook          | 1         | 2.04%   |
| HP Compaq             | 1         | 2.04%   |
| GPU Company GWTN156-9 | 1         | 2.04%   |
| Dell Venue            | 1         | 2.04%   |
| Dell Precision        | 1         | 2.04%   |
| AZW GT-R              | 1         | 2.04%   |
| ASUS X540SAA          | 1         | 2.04%   |
| ASUS K53E             | 1         | 2.04%   |
| Apple MacBookPro8     | 1         | 2.04%   |
| Apple MacBookPro5     | 1         | 2.04%   |
| Apple MacBook4        | 1         | 2.04%   |
| AMI Intel             | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 8         | 16.33%  |
| 2011 | 8         | 16.33%  |
| 2015 | 5         | 10.2%   |
| 2020 | 4         | 8.16%   |
| 2012 | 4         | 8.16%   |
| 2010 | 4         | 8.16%   |
| 2018 | 3         | 6.12%   |
| 2016 | 3         | 6.12%   |
| 2017 | 2         | 4.08%   |
| 2014 | 2         | 4.08%   |
| 2009 | 2         | 4.08%   |
| 2021 | 1         | 2.04%   |
| 2008 | 1         | 2.04%   |
| 2006 | 1         | 2.04%   |
| 2005 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 43        | 87.76%  |
| Enabled  | 6         | 12.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 37.25%  |
| 3.01-4.0   | 13        | 25.49%  |
| 8.01-16.0  | 12        | 23.53%  |
| 16.01-24.0 | 4         | 7.84%   |
| 1.01-2.0   | 3         | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 33        | 54.1%   |
| 2.01-3.0 | 12        | 19.67%  |
| 3.01-4.0 | 8         | 13.11%  |
| 4.01-8.0 | 4         | 6.56%   |
| 0.51-1.0 | 4         | 6.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 66.67%  |
| 2      | 12        | 23.53%  |
| 3      | 4         | 7.84%   |
| 4      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 56%     |
| Yes       | 22        | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 97.96%  |
| No        | 1         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 75.51%  |
| No        | 12        | 24.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 49        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 27        | 51.92%  |
| Bayamón      | 9         | 17.31%  |
| Carolina      | 5         | 9.62%   |
| Ponce         | 3         | 5.77%   |
| Lares         | 2         | 3.85%   |
| Cayey         | 2         | 3.85%   |
| Sabana Grande | 1         | 1.92%   |
| Rio Grande    | 1         | 1.92%   |
| Guayama       | 1         | 1.92%   |
| Caguas        | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 16     | 19.4%   |
| Toshiba             | 7         | 7      | 10.45%  |
| Hitachi             | 7         | 22     | 10.45%  |
| Crucial             | 7         | 11     | 10.45%  |
| Unknown             | 5         | 6      | 7.46%   |
| Seagate             | 4         | 8      | 5.97%   |
| SanDisk             | 3         | 3      | 4.48%   |
| Samsung Electronics | 3         | 4      | 4.48%   |
| SK hynix            | 2         | 3      | 2.99%   |
| Intel               | 2         | 3      | 2.99%   |
| External            | 2         | 3      | 2.99%   |
| A-DATA Technology   | 2         | 2      | 2.99%   |
| W800SH              | 1         | 1      | 1.49%   |
| Silicon Motion      | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| Kingston            | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| HGST                | 1         | 1      | 1.49%   |
| China               | 1         | 2      | 1.49%   |
| Axiom               | 1         | 3      | 1.49%   |
| Unknown             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB            | 4         | 5.63%   |
| WDC WD5000LPVT-22G33T0 500GB            | 3         | 4.23%   |
| WDC WD2500BEVS-60UST0 250GB             | 2         | 2.82%   |
| Unknown MMC Card  2GB                   | 2         | 2.82%   |
| Toshiba MK3261GSYN 320GB                | 2         | 2.82%   |
| Hitachi HTS547550A9E384 500GB           | 2         | 2.82%   |
| External USB3.0 1TB                     | 2         | 2.82%   |
| Crucial CT240M500SSD1 240GB             | 2         | 2.82%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1.41%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 1.41%   |
| WDC WD5000BPVT-75HXZT1 500GB            | 1         | 1.41%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 1.41%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1.41%   |
| WDC WD10SPCX-75KHST0 1TB                | 1         | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 1.41%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB    | 1         | 1.41%   |
| W800SH 512GB SSD                        | 1         | 1.41%   |
| Unknown MMC Card  64GB                  | 1         | 1.41%   |
| Unknown MMC Card  10GB                  | 1         | 1.41%   |
| Unknown HBG4a2  32GB                    | 1         | 1.41%   |
| Unknown DA4064  64GB                    | 1         | 1.41%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.41%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.41%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.41%   |
| Toshiba MK3276GSX 320GB                 | 1         | 1.41%   |
| Toshiba MK3254GSY 320GB                 | 1         | 1.41%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 1.41%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1.41%   |
| Silicon Motion 256GB                    | 1         | 1.41%   |
| Seagate ST98823AS 80GB                  | 1         | 1.41%   |
| Seagate ST9500420AS 500GB               | 1         | 1.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1.41%   |
| Seagate ST1000LM014-1EJ164 1TB          | 1         | 1.41%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 1.41%   |
| SanDisk SD6SP1M128G1012 128GB SSD       | 1         | 1.41%   |
| SanDisk NVMe SSD Drive 512GB            | 1         | 1.41%   |
| Samsung SSD 840 EVO 750GB               | 1         | 1.41%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD    | 1         | 1.41%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1.41%   |
| PNY CS900 120GB SSD                     | 1         | 1.41%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 1.41%   |
| Kingston SKC2500M8250G 250GB            | 1         | 1.41%   |
| KingSpec MT-256 256GB SSD               | 1         | 1.41%   |
| Intel NVMe SSD Drive 32GB               | 1         | 1.41%   |
| Intel MEMPEK1J016GAH 16GB               | 1         | 1.41%   |
| Intel HBRPEKNX0202AH 512GB              | 1         | 1.41%   |
| Hitachi HTS547564A9E384 640GB           | 1         | 1.41%   |
| Hitachi HTS545032B9A300 320GB           | 1         | 1.41%   |
| Hitachi HTS545025B9A300 250GB           | 1         | 1.41%   |
| Hitachi HTS543232L9A300 320GB           | 1         | 1.41%   |
| Hitachi HTS543232A7A384 320GB           | 1         | 1.41%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1.41%   |
| Hitachi HTS541010A9E680 1TB             | 1         | 1.41%   |
| HGST HCC545050A7E380 500GB              | 1         | 1.41%   |
| Crucial CT250MX500SSD4 250GB            | 1         | 1.41%   |
| China SATA SSD 120GB                    | 1         | 1.41%   |
| Axiom 500GB                             | 1         | 1.41%   |
| A-DATA SU655 120GB SSD                  | 1         | 1.41%   |
| A-DATA SU630 480GB SSD                  | 1         | 1.41%   |
| Unknown                                 | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 11     | 34.48%  |
| Toshiba | 7         | 7      | 24.14%  |
| Hitachi | 7         | 22     | 24.14%  |
| Seagate | 4         | 8      | 13.79%  |
| HGST    | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 7         | 11     | 33.33%  |
| Samsung Electronics | 3         | 4      | 14.29%  |
| WDC                 | 2         | 3      | 9.52%   |
| SanDisk             | 2         | 2      | 9.52%   |
| A-DATA Technology   | 2         | 2      | 9.52%   |
| W800SH              | 1         | 1      | 4.76%   |
| PNY                 | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| KingSpec            | 1         | 1      | 4.76%   |
| China               | 1         | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 49     | 42.86%  |
| SSD     | 20        | 28     | 31.75%  |
| NVMe    | 9         | 14     | 14.29%  |
| MMC     | 6         | 7      | 9.52%   |
| Unknown | 1         | 3      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 80     | 74.14%  |
| NVMe | 7         | 11     | 12.07%  |
| MMC  | 6         | 7      | 10.34%  |
| SAS  | 2         | 3      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 56     | 70.45%  |
| 0.51-1.0   | 13        | 21     | 29.55%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 27.59%  |
| 251-500        | 13        | 22.41%  |
| 501-1000       | 13        | 22.41%  |
| 1-20           | 8         | 13.79%  |
| 1001-2000      | 3         | 5.17%   |
| 21-50          | 2         | 3.45%   |
| More than 3000 | 1         | 1.72%   |
| 51-100         | 1         | 1.72%   |
| Unknown        | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 38.71%  |
| 21-50     | 15        | 24.19%  |
| 101-250   | 7         | 11.29%  |
| 51-100    | 7         | 11.29%  |
| 501-1000  | 4         | 6.45%   |
| 251-500   | 3         | 4.84%   |
| 1001-2000 | 1         | 1.61%   |
| Unknown   | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 14.29%  |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 14.29%  |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 14.29%  |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 14.29%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 14.29%  |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 14.29%  |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SK hynix            | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Detected | 36        | 81     | 69.23%  |
| Works    | 9         | 13     | 17.31%  |
| Malfunc  | 7         | 7      | 13.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 76.92%  |
| AMD                         | 5         | 9.62%   |
| SK hynix                    | 2         | 3.85%   |
| Silicon Motion              | 1         | 1.92%   |
| SanDisk                     | 1         | 1.92%   |
| Nvidia                      | 1         | 1.92%   |
| Kingston Technology Company | 1         | 1.92%   |
| ASMedia Technology          | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 14.29%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 10.71%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 8.93%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 8.93%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 3.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.79%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.79%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.79%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.79%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.79%   |
| AMD FCH IDE Controller                                                           | 1         | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 38        | 69.09%  |
| NVMe | 7         | 12.73%  |
| RAID | 6         | 10.91%  |
| IDE  | 4         | 7.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 87.76%  |
| AMD    | 6         | 12.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 6.12%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 4.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 4.08%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 2.04%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 2.04%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 2.04%   |
| Intel Genuine CPU T2250 @ 1.73GHz             | 1         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 2.04%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 2.04%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 2.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.04%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.04%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i3-4020Y CPU @ 1.50GHz             | 1         | 2.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 2.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 2.04%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 2.04%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.04%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2.04%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.04%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.04%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 3 3300U with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD A8-7050 Radeon R5, 6 Compute Cores 2C+4G  | 1         | 2.04%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2.04%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 16        | 32.65%  |
| Intel Core i7        | 8         | 16.33%  |
| Intel Core i3        | 6         | 12.24%  |
| Intel Celeron        | 4         | 8.16%   |
| Intel Core 2 Duo     | 3         | 6.12%   |
| Intel Pentium        | 2         | 4.08%   |
| AMD Ryzen 5          | 2         | 4.08%   |
| AMD A8               | 2         | 4.08%   |
| Other                | 1         | 2.04%   |
| Intel Pentium Silver | 1         | 2.04%   |
| Intel Genuine        | 1         | 2.04%   |
| Intel Core 2         | 1         | 2.04%   |
| AMD Ryzen 3          | 1         | 2.04%   |
| AMD A10              | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 65.31%  |
| 4      | 14        | 28.57%  |
| 6      | 2         | 4.08%   |
| 1      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 69.39%  |
| 1      | 15        | 30.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 97.96%  |
| 32-bit         | 1         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 8         | 15.69%  |
| Unknown    | 7         | 13.73%  |
| 0x20655    | 4         | 7.84%   |
| 0x806ea    | 3         | 5.88%   |
| 0x706a1    | 3         | 5.88%   |
| 0x806ec    | 2         | 3.92%   |
| 0x406e3    | 2         | 3.92%   |
| 0x306d4    | 2         | 3.92%   |
| 0x306a9    | 2         | 3.92%   |
| 0x08108109 | 2         | 3.92%   |
| 0xa0652    | 1         | 1.96%   |
| 0x906ea    | 1         | 1.96%   |
| 0x806e9    | 1         | 1.96%   |
| 0x806c1    | 1         | 1.96%   |
| 0x706e5    | 1         | 1.96%   |
| 0x6e8      | 1         | 1.96%   |
| 0x506c9    | 1         | 1.96%   |
| 0x406c4    | 1         | 1.96%   |
| 0x406c3    | 1         | 1.96%   |
| 0x40651    | 1         | 1.96%   |
| 0x20652    | 1         | 1.96%   |
| 0x10676    | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x07030105 | 1         | 1.96%   |
| 0x06003106 | 1         | 1.96%   |
| 0x06001119 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 8         | 16.33%  |
| KabyLake      | 7         | 14.29%  |
| Westmere      | 5         | 10.2%   |
| Skylake       | 3         | 6.12%   |
| Penryn        | 3         | 6.12%   |
| Goldmont plus | 3         | 6.12%   |
| Zen+          | 2         | 4.08%   |
| Silvermont    | 2         | 4.08%   |
| IvyBridge     | 2         | 4.08%   |
| Haswell       | 2         | 4.08%   |
| Broadwell     | 2         | 4.08%   |
| Zen 2         | 1         | 2.04%   |
| TigerLake     | 1         | 2.04%   |
| Steamroller   | 1         | 2.04%   |
| Puma          | 1         | 2.04%   |
| Piledriver    | 1         | 2.04%   |
| P6            | 1         | 2.04%   |
| IceLake       | 1         | 2.04%   |
| Goldmont      | 1         | 2.04%   |
| Core          | 1         | 2.04%   |
| CometLake     | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 72.41%  |
| AMD    | 9         | 15.52%  |
| Nvidia | 7         | 12.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 12.9%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 8.06%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.84%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 4.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 3.23%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.61%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.61%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 1.61%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.61%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.61%   |
| Intel HD Graphics 620                                                                    | 1         | 1.61%   |
| Intel HD Graphics 500                                                                    | 1         | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.61%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.61%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 1         | 1.61%   |
| AMD Renoir                                                                               | 1         | 1.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.61%   |
| AMD Kaveri [Radeon R5 Graphics]                                                          | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 67.35%  |
| Intel + Nvidia | 6         | 12.24%  |
| 1 x AMD        | 6         | 12.24%  |
| Intel + AMD    | 3         | 6.12%   |
| 2 x Nvidia     | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 47        | 92.16%  |
| Proprietary | 3         | 5.88%   |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 68.63%  |
| 0.51-1.0   | 5         | 9.8%    |
| 0.01-0.5   | 4         | 7.84%   |
| 1.01-2.0   | 3         | 5.88%   |
| 3.01-4.0   | 2         | 3.92%   |
| 5.01-6.0   | 1         | 1.96%   |
| 2.01-3.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 17.31%  |
| Chimei Innolux          | 9         | 17.31%  |
| Samsung Electronics     | 7         | 13.46%  |
| AU Optronics            | 6         | 11.54%  |
| BOE                     | 5         | 9.62%   |
| Apple                   | 3         | 5.77%   |
| PANDA                   | 2         | 3.85%   |
| Goldstar                | 2         | 3.85%   |
| Dell                    | 2         | 3.85%   |
| Sony                    | 1         | 1.92%   |
| ONN                     | 1         | 1.92%   |
| Lenovo                  | 1         | 1.92%   |
| InnoLux Display         | 1         | 1.92%   |
| eMachines               | 1         | 1.92%   |
| Chi Mei Optoelectronics | 1         | 1.92%   |
| AOC                     | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 3         | 5.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 3.85%   |
| Sony TV SNYEA01 1920x1080                                                | 1         | 1.92%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch        | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 1.92%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch                  | 1         | 1.92%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch                  | 1         | 1.92%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 1.92%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 1         | 1.92%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch         | 1         | 1.92%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 1.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 1.92%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                    | 1         | 1.92%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                       | 1         | 1.92%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                  | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO1462 1280x800 303x189mm 14.1-inch | 1         | 1.92%   |
| BOE LCD Monitor BOE092B 1366x768 309x174mm 14.0-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE06AB 1366x768 256x144mm 11.6-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                     | 1         | 1.92%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 1         | 1.92%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 1         | 1.92%   |
| Apple LCD Monitor APP9C84 1440x900 331x207mm 15.4-inch                   | 1         | 1.92%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 1.92%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                         | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 22        | 44.9%   |
| 1920x1080 (FHD)  | 17        | 34.69%  |
| 1280x800 (WXGA)  | 4         | 8.16%   |
| 1440x900 (WXGA+) | 3         | 6.12%   |
| 3840x2160 (4K)   | 1         | 2.04%   |
| 2560x1080        | 1         | 2.04%   |
| 1600x900 (HD+)   | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 24        | 46.15%  |
| 14     | 6         | 11.54%  |
| 17     | 5         | 9.62%   |
| 13     | 4         | 7.69%   |
| 21     | 3         | 5.77%   |
| 31     | 2         | 3.85%   |
| 11     | 2         | 3.85%   |
| 72     | 1         | 1.92%   |
| 34     | 1         | 1.92%   |
| 27     | 1         | 1.92%   |
| 23     | 1         | 1.92%   |
| 19     | 1         | 1.92%   |
| 18     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 59.62%  |
| 351-400     | 6         | 11.54%  |
| 401-500     | 5         | 9.62%   |
| 201-300     | 4         | 7.69%   |
| 601-700     | 2         | 3.85%   |
| 501-600     | 2         | 3.85%   |
| 701-800     | 1         | 1.92%   |
| 1501-2000   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 83.67%  |
| 16/10 | 7         | 14.29%  |
| 21/9  | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 46.15%  |
| 81-90          | 10        | 19.23%  |
| 121-130        | 4         | 7.69%   |
| 351-500        | 3         | 5.77%   |
| 151-200        | 3         | 5.77%   |
| 51-60          | 2         | 3.85%   |
| 201-250        | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 301-350        | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |
| 131-140        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 53.85%  |
| 121-160 | 14        | 26.92%  |
| 51-100  | 8         | 15.38%  |
| 1-50    | 2         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 78.43%  |
| 2     | 9         | 17.65%  |
| 0     | 2         | 3.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 32.18%  |
| Realtek Semiconductor    | 27        | 31.03%  |
| Qualcomm Atheros         | 10        | 11.49%  |
| Broadcom                 | 6         | 6.9%    |
| Marvell Technology Group | 3         | 3.45%   |
| Broadcom Limited         | 3         | 3.45%   |
| Ralink Technology        | 2         | 2.3%    |
| NetGear                  | 2         | 2.3%    |
| TP-Link                  | 1         | 1.15%   |
| Samsung Electronics      | 1         | 1.15%   |
| Nvidia                   | 1         | 1.15%   |
| Dell                     | 1         | 1.15%   |
| Belkin Components        | 1         | 1.15%   |
| ASIX Electronics         | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                         | 16        | 16.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                     | 5         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 3         | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 3         | 3.16%   |
| Intel Wireless 7265                                                                       | 3         | 3.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                           | 2         | 2.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                | 2         | 2.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                     | 2         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 2         | 2.11%   |
| Intel Wi-Fi 6 AX200                                                                       | 2         | 2.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                     | 2         | 2.11%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 2         | 2.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 2         | 2.11%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                             | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                     | 2         | 2.11%   |
| Intel 82577LM Gigabit Network Connection                                                  | 2         | 2.11%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                   | 2         | 2.11%   |
| TP-Link TL-WN722N v2                                                                      | 1         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                                             | 1         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                        | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                  | 1         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                               | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                | 1         | 1.05%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                | 1         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                          | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                                | 1         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                             | 1         | 1.05%   |
| Nvidia MCP79 Ethernet                                                                     | 1         | 1.05%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                     | 1         | 1.05%   |
| NetGear LB1120-100NAS                                                                     | 1         | 1.05%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]            | 1         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                                   | 1         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                      | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.05%   |
| Intel Wireless 7260                                                                       | 1         | 1.05%   |
| Intel Wireless 3165                                                                       | 1         | 1.05%   |
| Intel Wireless 3160                                                                       | 1         | 1.05%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                                       | 1         | 1.05%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                                                     | 1         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                         | 1         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 1         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                              | 1         | 1.05%   |
| Intel 82579V Gigabit Network Connection                                                   | 1         | 1.05%   |
| Intel 82577LC Gigabit Network Connection                                                  | 1         | 1.05%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                               | 1         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                         | 1         | 1.05%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                                  | 1         | 1.05%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                                    | 1         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                    | 1         | 1.05%   |
| Broadcom BCM4321 802.11a/b/g/n                                                            | 1         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                                             | 1         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                       | 1         | 1.05%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.05%   |
| ASIX AX88772B                                                                             | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 42.59%  |
| Realtek Semiconductor | 10        | 18.52%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| Broadcom              | 5         | 9.26%   |
| Ralink Technology     | 2         | 3.7%    |
| Broadcom Limited      | 2         | 3.7%    |
| TP-Link               | 1         | 1.85%   |
| NetGear               | 1         | 1.85%   |
| Dell                  | 1         | 1.85%   |
| Belkin Components     | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 3         | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 3         | 5.45%   |
| Intel Wireless 7265                                                                       | 3         | 5.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                           | 2         | 3.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                | 2         | 3.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                     | 2         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 2         | 3.64%   |
| Intel Wi-Fi 6 AX200                                                                       | 2         | 3.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                     | 2         | 3.64%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 2         | 3.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 2         | 3.64%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                             | 2         | 3.64%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                   | 2         | 3.64%   |
| TP-Link TL-WN722N v2                                                                      | 1         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                        | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                  | 1         | 1.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                               | 1         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                | 1         | 1.82%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                | 1         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 1         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                          | 1         | 1.82%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                     | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.82%   |
| Intel Wireless 7260                                                                       | 1         | 1.82%   |
| Intel Wireless 3165                                                                       | 1         | 1.82%   |
| Intel Wireless 3160                                                                       | 1         | 1.82%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                                       | 1         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                         | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                              | 1         | 1.82%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                               | 1         | 1.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                    | 1         | 1.82%   |
| Broadcom BCM4321 802.11a/b/g/n                                                            | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                                             | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                       | 1         | 1.82%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 52.5%   |
| Intel                    | 7         | 17.5%   |
| Marvell Technology Group | 3         | 7.5%    |
| Qualcomm Atheros         | 2         | 5%      |
| Broadcom                 | 2         | 5%      |
| Samsung Electronics      | 1         | 2.5%    |
| Nvidia                   | 1         | 2.5%    |
| NetGear                  | 1         | 2.5%    |
| Broadcom Limited         | 1         | 2.5%    |
| ASIX Electronics         | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 16        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 5%      |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 5%      |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 2.5%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 2.5%    |
| NetGear LB1120-100NAS                                                          | 1         | 2.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.5%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 2.5%    |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 2.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 2.5%    |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 2.5%    |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 2.5%    |
| ASIX AX88772B                                                                  | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 54.55%  |
| Ethernet | 40        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 76.92%  |
| Ethernet | 12        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 71.43%  |
| 1     | 12        | 24.49%  |
| 3     | 1         | 2.04%   |
| 0     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 87.76%  |
| Yes  | 6         | 12.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 45.95%  |
| Realtek Semiconductor           | 6         | 16.22%  |
| Apple                           | 3         | 8.11%   |
| Qualcomm Atheros Communications | 2         | 5.41%   |
| Lite-On Technology              | 2         | 5.41%   |
| Foxconn / Hon Hai               | 2         | 5.41%   |
| Toshiba                         | 1         | 2.7%    |
| IMC Networks                    | 1         | 2.7%    |
| Hewlett-Packard                 | 1         | 2.7%    |
| Dell                            | 1         | 2.7%    |
| Alps Electric                   | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 7         | 18.92%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 13.51%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 10.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 8.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 5.41%   |
| Intel AX200 Bluetooth                                                               | 2         | 5.41%   |
| Apple Bluetooth Host Controller                                                     | 2         | 5.41%   |
| Toshiba BCM43142A0                                                                  | 1         | 2.7%    |
| Realtek Bluetooth Radio                                                             | 1         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 2.7%    |
| Lite-On Bluetooth Device                                                            | 1         | 2.7%    |
| Intel AX201 Bluetooth                                                               | 1         | 2.7%    |
| IMC Networks Bluetooth Device                                                       | 1         | 2.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 2.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.7%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 2.7%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.7%    |
| Apple Bluetooth HCI                                                                 | 1         | 2.7%    |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 80.77%  |
| AMD    | 6         | 11.54%  |
| Nvidia | 4         | 7.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 12.9%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 11.29%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 8.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 4.84%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.23%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 3.23%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.61%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 36.84%  |
| Samsung Electronics | 5         | 26.32%  |
| Kingston            | 2         | 10.53%  |
| Unknown             | 1         | 5.26%   |
| Silicon Power       | 1         | 5.26%   |
| Ramaxel Technology  | 1         | 5.26%   |
| Micron Technology   | 1         | 5.26%   |
| A-DATA Technology   | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 9.09%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s  | 1         | 4.55%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 4.55%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 4.55%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 4.55%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 4.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 4.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s  | 1         | 4.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 4.55%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 52.63%  |
| DDR3   | 6         | 31.58%  |
| LPDDR4 | 2         | 10.53%  |
| DDR    | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 10        | 50%     |
| 8192 | 9         | 45%     |
| 2048 | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 36.84%  |
| 1600  | 6         | 31.58%  |
| 3200  | 2         | 10.53%  |
| 3266  | 1         | 5.26%   |
| 2400  | 1         | 5.26%   |
| 800   | 1         | 5.26%   |
| 667   | 1         | 5.26%   |

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
| Ricoh                                  | 5         | 12.2%   |
| Realtek Semiconductor                  | 4         | 9.76%   |
| Quanta                                 | 3         | 7.32%   |
| Acer                                   | 3         | 7.32%   |
| Suyin                                  | 2         | 4.88%   |
| Microdia                               | 2         | 4.88%   |
| Lite-On Technology                     | 2         | 4.88%   |
| IMC Networks                           | 2         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Apple                                  | 2         | 4.88%   |
| Sunplus Innovation Technology          | 1         | 2.44%   |
| Luxvisions Innotech Limited            | 1         | 2.44%   |
| Lenovo                                 | 1         | 2.44%   |
| Goertek Electronics                    | 1         | 2.44%   |
| Alpha Imaging Technology               | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                         | 3         | 7.32%   |
| Chicony HD WebCam                                               | 2         | 4.88%   |
| Suyin USB 2.0 Camera                                            | 1         | 2.44%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.44%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.44%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam        | 1         | 2.44%   |
| Ricoh HD Webcam                                                 | 1         | 2.44%   |
| Realtek USB2.0 camera                                           | 1         | 2.44%   |
| Realtek USB Camera                                              | 1         | 2.44%   |
| Realtek Integrated Webcam HD                                    | 1         | 2.44%   |
| Realtek Integrated Webcam                                       | 1         | 2.44%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 2.44%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 2.44%   |
| Quanta HD WebCam                                                | 1         | 2.44%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 2.44%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.44%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 2.44%   |
| Lite-On HP HD Webcam                                            | 1         | 2.44%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 2.44%   |
| IMC Networks UVC VGA Webcam                                     | 1         | 2.44%   |
| IMC Networks Integrated Camera                                  | 1         | 2.44%   |
| Goertek USB2.0 VGA UVC WebCam                                   | 1         | 2.44%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.44%   |
| Chicony Toshiba Integrated Webcam                               | 1         | 2.44%   |
| Chicony Integrated HP HD Webcam                                 | 1         | 2.44%   |
| Chicony HP Webcam                                               | 1         | 2.44%   |
| Chicony HP Truevision HD                                        | 1         | 2.44%   |
| Chicony HP HD Camera                                            | 1         | 2.44%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.44%   |
| Apple FaceTime HD Camera                                        | 1         | 2.44%   |
| Apple Built-in iSight                                           | 1         | 2.44%   |
| Alpha Imaging Integrated_Webcam_8M                              | 1         | 2.44%   |
| Acer Lenovo EasyCamera                                          | 1         | 2.44%   |
| Acer EasyCamera                                                 | 1         | 2.44%   |
| Acer BisonCam,NB Pro                                            | 1         | 2.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 70%     |
| LighTuning Technology | 2         | 20%     |
| Synaptics             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 30%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors Fingerprint scanner        | 1         | 10%     |
| Unknown                                     | 1         | 10%     |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 64%     |
| 1     | 18        | 36%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 55.56%  |
| Net/wireless             | 3         | 16.67%  |
| Graphics card            | 2         | 11.11%  |
| Chipcard                 | 2         | 11.11%  |
| Communication controller | 1         | 5.56%   |


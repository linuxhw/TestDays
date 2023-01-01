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

Total: 106

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 3550                 | [0708d07cd4](https://linux-hardware.org/?probe=0708d07cd4) | Dec 28, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Latitude E6420              | [7d592f1759](https://linux-hardware.org/?probe=7d592f1759) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0c94171d5b](https://linux-hardware.org/?probe=0c94171d5b) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [3d516c4ca3](https://linux-hardware.org/?probe=3d516c4ca3) | Dec 06, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Dell          | Latitude E6420              | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | [fe69e51efe](https://linux-hardware.org/?probe=fe69e51efe) | Nov 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Dell          | G5 5505                     | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Apple         | MacBook4,1                  | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 16        | 25%     |
| Ubuntu 22.04                 | 5         | 7.81%   |
| Ubuntu 18.04                 | 5         | 7.81%   |
| Ubuntu 22.10                 | 2         | 3.13%   |
| Ubuntu 21.10                 | 2         | 3.13%   |
| OpenMandriva 4.3             | 2         | 3.13%   |
| OpenMandriva 4.2             | 2         | 3.13%   |
| Linux Mint 21                | 2         | 3.13%   |
| Linux Mint 19.3              | 2         | 3.13%   |
| Debian 11                    | 2         | 3.13%   |
| BlackPanther 18.1            | 2         | 3.13%   |
| Zorin 16                     | 1         | 1.56%   |
| Xubuntu 20.04                | 1         | 1.56%   |
| Ubuntu Unity 20.04           | 1         | 1.56%   |
| Ubuntu MATE 20.04            | 1         | 1.56%   |
| Ubuntu 19.10                 | 1         | 1.56%   |
| ROSA R10                     | 1         | 1.56%   |
| Peppermint 9                 | 1         | 1.56%   |
| Parrot 5.0                   | 1         | 1.56%   |
| Parrot 4.11                  | 1         | 1.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 1.56%   |
| openSUSE Leap-15.2           | 1         | 1.56%   |
| OpenMandriva 4.90            | 1         | 1.56%   |
| OpenMandriva 4.50            | 1         | 1.56%   |
| Linux Mint 20.1              | 1         | 1.56%   |
| KDE neon 20.04               | 1         | 1.56%   |
| Fedora 37                    | 1         | 1.56%   |
| Fedora 36                    | 1         | 1.56%   |
| Fedora 33                    | 1         | 1.56%   |
| Endless 3.7.8                | 1         | 1.56%   |
| EndeavourOS Rolling          | 1         | 1.56%   |
| Debian 10                    | 1         | 1.56%   |
| Arch Rolling                 | 1         | 1.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 29        | 46.77%  |
| OpenMandriva | 6         | 9.68%   |
| Linux Mint   | 5         | 8.06%   |
| Fedora       | 3         | 4.84%   |
| Debian       | 3         | 4.84%   |
| Parrot       | 2         | 3.23%   |
| openSUSE     | 2         | 3.23%   |
| BlackPanther | 2         | 3.23%   |
| Zorin        | 1         | 1.61%   |
| Xubuntu      | 1         | 1.61%   |
| Ubuntu Unity | 1         | 1.61%   |
| Ubuntu MATE  | 1         | 1.61%   |
| ROSA         | 1         | 1.61%   |
| Peppermint   | 1         | 1.61%   |
| KDE neon     | 1         | 1.61%   |
| Endless      | 1         | 1.61%   |
| EndeavourOS  | 1         | 1.61%   |
| Arch         | 1         | 1.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-59-generic         | 3         | 4%      |
| 5.8.0-55-generic         | 2         | 2.67%   |
| 5.4.0-58-generic         | 2         | 2.67%   |
| 5.16.7-desktop-1omv4003  | 2         | 2.67%   |
| 5.15.0-46-generic        | 2         | 2.67%   |
| 5.15.0-25-generic        | 2         | 2.67%   |
| 5.13.0-35-generic        | 2         | 2.67%   |
| 5.11.0-38-generic        | 2         | 2.67%   |
| 5.11.0-27-generic        | 2         | 2.67%   |
| 5.10.14-desktop-1omv4002 | 2         | 2.67%   |
| 5.10.0-19-amd64          | 2         | 2.67%   |
| 5.9.16-200.fc33.x86_64   | 1         | 1.33%   |
| 5.8.0-63-generic         | 1         | 1.33%   |
| 5.6.14-desktop-2bP       | 1         | 1.33%   |
| 5.4.0-84-generic         | 1         | 1.33%   |
| 5.4.0-77-generic         | 1         | 1.33%   |
| 5.4.0-73-generic         | 1         | 1.33%   |
| 5.4.0-70-generic         | 1         | 1.33%   |
| 5.4.0-62-generic         | 1         | 1.33%   |
| 5.4.0-60-generic         | 1         | 1.33%   |
| 5.4.0-55-generic         | 1         | 1.33%   |
| 5.4.0-52-generic         | 1         | 1.33%   |
| 5.4.0-48-generic         | 1         | 1.33%   |
| 5.4.0-47-generic         | 1         | 1.33%   |
| 5.4.0-40-generic         | 1         | 1.33%   |
| 5.4.0-29-generic         | 1         | 1.33%   |
| 5.3.6-050306-generic     | 1         | 1.33%   |
| 5.3.18-lp152.57-default  | 1         | 1.33%   |
| 5.3.0-41-generic         | 1         | 1.33%   |
| 5.3.0-40-generic         | 1         | 1.33%   |
| 5.3.0-28-generic         | 1         | 1.33%   |
| 5.19.7-300.fc37.x86_64   | 1         | 1.33%   |
| 5.19.0-28-generic        | 1         | 1.33%   |
| 5.19.0-26-generic        | 1         | 1.33%   |
| 5.18.6-200.fc36.x86_64   | 1         | 1.33%   |
| 5.18.15-1-default        | 1         | 1.33%   |
| 5.18.12-desktop-3omv4090 | 1         | 1.33%   |
| 5.18.0-1parrot1-amd64    | 1         | 1.33%   |
| 5.15.59-1-lts            | 1         | 1.33%   |
| 5.15.0-56-generic        | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 20.31%  |
| 5.15.0  | 6         | 9.38%   |
| 5.13.0  | 6         | 9.38%   |
| 5.11.0  | 5         | 7.81%   |
| 5.8.0   | 4         | 6.25%   |
| 5.3.0   | 3         | 4.69%   |
| 5.10.0  | 3         | 4.69%   |
| 4.15.0  | 3         | 4.69%   |
| 5.19.0  | 2         | 3.13%   |
| 5.16.7  | 2         | 3.13%   |
| 5.10.14 | 2         | 3.13%   |
| 5.9.16  | 1         | 1.56%   |
| 5.6.14  | 1         | 1.56%   |
| 5.3.6   | 1         | 1.56%   |
| 5.3.18  | 1         | 1.56%   |
| 5.19.7  | 1         | 1.56%   |
| 5.18.6  | 1         | 1.56%   |
| 5.18.15 | 1         | 1.56%   |
| 5.18.12 | 1         | 1.56%   |
| 5.18.0  | 1         | 1.56%   |
| 5.15.59 | 1         | 1.56%   |
| 5.12.4  | 1         | 1.56%   |
| 5.11.16 | 1         | 1.56%   |
| 4.9.60  | 1         | 1.56%   |
| 4.19.0  | 1         | 1.56%   |
| 4.18.16 | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 20.63%  |
| 5.15    | 7         | 11.11%  |
| 5.13    | 6         | 9.52%   |
| 5.11    | 6         | 9.52%   |
| 5.3     | 5         | 7.94%   |
| 5.10    | 5         | 7.94%   |
| 5.8     | 4         | 6.35%   |
| 5.19    | 3         | 4.76%   |
| 5.18    | 3         | 4.76%   |
| 4.15    | 3         | 4.76%   |
| 5.16    | 2         | 3.17%   |
| 5.9     | 1         | 1.59%   |
| 5.6     | 1         | 1.59%   |
| 5.12    | 1         | 1.59%   |
| 4.9     | 1         | 1.59%   |
| 4.19    | 1         | 1.59%   |
| 4.18    | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 96.49%  |
| i686   | 2         | 3.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 32        | 53.33%  |
| KDE5       | 12        | 20%     |
| MATE       | 4         | 6.67%   |
| X-Cinnamon | 3         | 5%      |
| XFCE       | 2         | 3.33%   |
| i3         | 2         | 3.33%   |
| Unknown    | 2         | 3.33%   |
| Unity      | 1         | 1.67%   |
| LXDE       | 1         | 1.67%   |
| KDE4       | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 51        | 85%     |
| Wayland | 9         | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 31        | 50%     |
| GDM3    | 14        | 22.58%  |
| SDDM    | 8         | 12.9%   |
| GDM     | 4         | 6.45%   |
| TDM     | 2         | 3.23%   |
| LightDM | 2         | 3.23%   |
| KDM     | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 48        | 82.76%  |
| Unknown | 5         | 8.62%   |
| es_PR   | 4         | 6.9%    |
| C       | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 53.45%  |
| EFI  | 27        | 46.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 74.14%  |
| Overlay | 8         | 13.79%  |
| Btrfs   | 4         | 6.9%    |
| Unknown | 2         | 3.45%   |
| Zfs     | 1         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 63.33%  |
| GPT     | 18        | 30%     |
| MBR     | 4         | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 81.36%  |
| Yes       | 11        | 18.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 72.41%  |
| Yes       | 16        | 27.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 15        | 26.32%  |
| Dell             | 14        | 24.56%  |
| Lenovo           | 7         | 12.28%  |
| ASUSTek Computer | 4         | 7.02%   |
| Acer             | 4         | 7.02%   |
| Toshiba          | 3         | 5.26%   |
| Apple            | 3         | 5.26%   |
| Sony             | 2         | 3.51%   |
| TUXEDO           | 1         | 1.75%   |
| MSI              | 1         | 1.75%   |
| GPU Company      | 1         | 1.75%   |
| AZW              | 1         | 1.75%   |
| AMI              | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Vostro 3550                         | 3         | 5.26%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.75%   |
| Toshiba Satellite P755                   | 1         | 1.75%   |
| Toshiba Satellite L655                   | 1         | 1.75%   |
| Toshiba Satellite C55-C                  | 1         | 1.75%   |
| Sony VPCEA36FX                           | 1         | 1.75%   |
| Sony VGN-CS320J                          | 1         | 1.75%   |
| MSI GF65 Thin 10SDR                      | 1         | 1.75%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 1.75%   |
| Lenovo Y50-70 Touch 20349                | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 1.75%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 1.75%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 1.75%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.75%   |
| Lenovo G50-45 80E3                       | 1         | 1.75%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 1.75%   |
| HP ProBook 6560b                         | 1         | 1.75%   |
| HP ProBook 6450b                         | 1         | 1.75%   |
| HP ProBook 450 G5                        | 1         | 1.75%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.75%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.75%   |
| HP Notebook                              | 1         | 1.75%   |
| HP Laptop 15-dy1xxx                      | 1         | 1.75%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.75%   |
| HP Laptop 14-dk1xxx                      | 1         | 1.75%   |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 1.75%   |
| HP ENVY Laptop 17-ce1xxx                 | 1         | 1.75%   |
| HP ENVY dv7                              | 1         | 1.75%   |
| HP EliteBook 840 G2                      | 1         | 1.75%   |
| HP Compaq nc6400 (RB516UT#ABA)           | 1         | 1.75%   |
| GPU Company GWTN156-9                    | 1         | 1.75%   |
| Dell Venue 11 Pro 7130 MS                | 1         | 1.75%   |
| Dell Precision M4700                     | 1         | 1.75%   |
| Dell Latitude E6420                      | 1         | 1.75%   |
| Dell Latitude E6410                      | 1         | 1.75%   |
| Dell Latitude E6330                      | 1         | 1.75%   |
| Dell Inspiron N5110                      | 1         | 1.75%   |
| Dell Inspiron MP061                      | 1         | 1.75%   |
| Dell Inspiron 5559                       | 1         | 1.75%   |
| Dell Inspiron 17-7778                    | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 5         | 8.77%   |
| Toshiba Satellite     | 3         | 5.26%   |
| Lenovo ThinkPad       | 3         | 5.26%   |
| HP ProBook            | 3         | 5.26%   |
| HP Laptop             | 3         | 5.26%   |
| HP ENVY               | 3         | 5.26%   |
| Dell Vostro           | 3         | 5.26%   |
| Dell Latitude         | 3         | 5.26%   |
| HP Pavilion           | 2         | 3.51%   |
| Acer Swift            | 2         | 3.51%   |
| Acer Aspire           | 2         | 3.51%   |
| TUXEDO Aura           | 1         | 1.75%   |
| Sony VPCEA36FX        | 1         | 1.75%   |
| Sony VGN-CS320J       | 1         | 1.75%   |
| MSI GF65              | 1         | 1.75%   |
| Lenovo Yoga           | 1         | 1.75%   |
| Lenovo Y50-70         | 1         | 1.75%   |
| Lenovo IdeaPad        | 1         | 1.75%   |
| Lenovo G50-45         | 1         | 1.75%   |
| HP Stream             | 1         | 1.75%   |
| HP Notebook           | 1         | 1.75%   |
| HP EliteBook          | 1         | 1.75%   |
| HP Compaq             | 1         | 1.75%   |
| GPU Company GWTN156-9 | 1         | 1.75%   |
| Dell Venue            | 1         | 1.75%   |
| Dell Precision        | 1         | 1.75%   |
| Dell G5               | 1         | 1.75%   |
| AZW GT-R              | 1         | 1.75%   |
| ASUS X540SAA          | 1         | 1.75%   |
| ASUS VivoBook         | 1         | 1.75%   |
| ASUS S500CA           | 1         | 1.75%   |
| ASUS K53E             | 1         | 1.75%   |
| Apple MacBookPro8     | 1         | 1.75%   |
| Apple MacBookPro5     | 1         | 1.75%   |
| Apple MacBook4        | 1         | 1.75%   |
| AMI Intel             | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 9         | 15.79%  |
| 2011 | 9         | 15.79%  |
| 2020 | 6         | 10.53%  |
| 2015 | 6         | 10.53%  |
| 2012 | 5         | 8.77%   |
| 2010 | 4         | 7.02%   |
| 2018 | 3         | 5.26%   |
| 2016 | 3         | 5.26%   |
| 2014 | 3         | 5.26%   |
| 2021 | 2         | 3.51%   |
| 2017 | 2         | 3.51%   |
| 2009 | 2         | 3.51%   |
| 2008 | 1         | 1.75%   |
| 2006 | 1         | 1.75%   |
| 2005 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 51        | 89.47%  |
| Enabled  | 6         | 10.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 40%     |
| 3.01-4.0   | 14        | 23.33%  |
| 8.01-16.0  | 12        | 20%     |
| 16.01-24.0 | 7         | 11.67%  |
| 1.01-2.0   | 3         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 37        | 52.86%  |
| 2.01-3.0 | 13        | 18.57%  |
| 3.01-4.0 | 11        | 15.71%  |
| 4.01-8.0 | 5         | 7.14%   |
| 0.51-1.0 | 4         | 5.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 67.8%   |
| 2      | 13        | 22.03%  |
| 3      | 4         | 6.78%   |
| 4      | 1         | 1.69%   |
| 0      | 1         | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 61.4%   |
| Yes       | 22        | 38.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 98.25%  |
| No        | 1         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 57        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 32        | 52.46%  |
| Bayamón      | 11        | 18.03%  |
| Carolina      | 5         | 8.2%    |
| Ponce         | 4         | 6.56%   |
| Lares         | 2         | 3.28%   |
| Cayey         | 2         | 3.28%   |
| San Sebastian | 1         | 1.64%   |
| Sabana Grande | 1         | 1.64%   |
| Rio Grande    | 1         | 1.64%   |
| Guayama       | 1         | 1.64%   |
| Caguas        | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 17     | 18.42%  |
| Hitachi             | 9         | 24     | 11.84%  |
| Toshiba             | 7         | 7      | 9.21%   |
| Crucial             | 7         | 12     | 9.21%   |
| Unknown             | 6         | 8      | 7.89%   |
| SanDisk             | 5         | 5      | 6.58%   |
| SK hynix            | 4         | 5      | 5.26%   |
| Seagate             | 4         | 8      | 5.26%   |
| Samsung Electronics | 3         | 4      | 3.95%   |
| Intel               | 2         | 3      | 2.63%   |
| External            | 2         | 3      | 2.63%   |
| A-DATA Technology   | 2         | 2      | 2.63%   |
| W800SH              | 1         | 1      | 1.32%   |
| Silicon Motion      | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Patriot             | 1         | 2      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| Kingston            | 1         | 1      | 1.32%   |
| KingSpec            | 1         | 1      | 1.32%   |
| HGST                | 1         | 1      | 1.32%   |
| China               | 1         | 2      | 1.32%   |
| Axiom               | 1         | 3      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB                | 4         | 5%      |
| WDC WD5000LPVT-22G33T0 500GB                | 3         | 3.75%   |
| WDC WD2500BEVS-60UST0 250GB                 | 2         | 2.5%    |
| Unknown MMC Card  2GB                       | 2         | 2.5%    |
| Toshiba MK3261GSYN 320GB                    | 2         | 2.5%    |
| Hitachi HTS547550A9E384 500GB               | 2         | 2.5%    |
| Hitachi HTS543232A7A384 320GB               | 2         | 2.5%    |
| External USB3.0 250GB                       | 2         | 2.5%    |
| Crucial CT240M500SSD1 240GB                 | 2         | 2.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1.25%   |
| WDC WDBNCE0010PNC 1TB SSD                   | 1         | 1.25%   |
| WDC WD5000BPVT-75HXZT1 500GB                | 1         | 1.25%   |
| WDC WD10SPZX-60Z10T0 1TB                    | 1         | 1.25%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 1         | 1.25%   |
| WDC WD10SPCX-75KHST0 1TB                    | 1         | 1.25%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1.25%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB        | 1         | 1.25%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB        | 1         | 1.25%   |
| W800SH 512GB SSD                            | 1         | 1.25%   |
| Unknown MMC Card  64GB                      | 1         | 1.25%   |
| Unknown MMC Card  128GB                     | 1         | 1.25%   |
| Unknown MMC Card  10GB                      | 1         | 1.25%   |
| Unknown HBG4a2  32GB                        | 1         | 1.25%   |
| Unknown DA4064  64GB                        | 1         | 1.25%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1.25%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1.25%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1.25%   |
| Toshiba MK3276GSX 320GB                     | 1         | 1.25%   |
| Toshiba MK3254GSY 320GB                     | 1         | 1.25%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 1.25%   |
| SK hynix BC511 NVMe 256GB                   | 1         | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1.25%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB     | 1         | 1.25%   |
| Silicon Motion 256GB                        | 1         | 1.25%   |
| Seagate ST98823AS 80GB                      | 1         | 1.25%   |
| Seagate ST9500420AS 500GB                   | 1         | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 1         | 1.25%   |
| Seagate ST1000LM014-1EJ164 1TB              | 1         | 1.25%   |
| Sandisk WD_BLACK SN770 500GB                | 1         | 1.25%   |
| SanDisk SSD PLUS 1000GB                     | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 11     | 32.26%  |
| Hitachi | 9         | 24     | 29.03%  |
| Toshiba | 7         | 7      | 22.58%  |
| Seagate | 4         | 8      | 12.9%   |
| HGST    | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 7         | 12     | 30.43%  |
| SanDisk             | 3         | 3      | 13.04%  |
| Samsung Electronics | 3         | 4      | 13.04%  |
| WDC                 | 2         | 3      | 8.7%    |
| A-DATA Technology   | 2         | 2      | 8.7%    |
| W800SH              | 1         | 1      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| Patriot             | 1         | 2      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| China               | 1         | 2      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 28        | 51     | 39.44%  |
| SSD     | 22        | 32     | 30.99%  |
| NVMe    | 13        | 18     | 18.31%  |
| MMC     | 7         | 9      | 9.86%   |
| Unknown | 1         | 3      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 86     | 69.7%   |
| NVMe | 11        | 15     | 16.67%  |
| MMC  | 7         | 9      | 10.61%  |
| SAS  | 2         | 3      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 61     | 70.21%  |
| 0.51-1.0   | 14        | 22     | 29.79%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 31.34%  |
| 501-1000       | 14        | 20.9%   |
| 251-500        | 13        | 19.4%   |
| 1-20           | 11        | 16.42%  |
| 1001-2000      | 3         | 4.48%   |
| 21-50          | 2         | 2.99%   |
| More than 3000 | 1         | 1.49%   |
| 51-100         | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 28        | 39.44%  |
| 21-50     | 16        | 22.54%  |
| 101-250   | 10        | 14.08%  |
| 51-100    | 8         | 11.27%  |
| 501-1000  | 4         | 5.63%   |
| 251-500   | 3         | 4.23%   |
| 1001-2000 | 1         | 1.41%   |
| Unknown   | 1         | 1.41%   |

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
| Detected | 40        | 90     | 67.8%   |
| Works    | 12        | 16     | 20.34%  |
| Malfunc  | 7         | 7      | 11.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 46        | 73.02%  |
| AMD                         | 6         | 9.52%   |
| SK hynix                    | 4         | 6.35%   |
| SanDisk                     | 3         | 4.76%   |
| Silicon Motion              | 1         | 1.59%   |
| Nvidia                      | 1         | 1.59%   |
| Kingston Technology Company | 1         | 1.59%   |
| ASMedia Technology          | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 11.94%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 10.45%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 8.96%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 8.96%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 4.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 4.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.99%   |
| SK hynix BC511                                                                   | 1         | 1.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.49%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.49%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.49%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.49%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.49%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.49%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.49%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.49%   |
| AMD FCH IDE Controller                                                           | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 65.15%  |
| NVMe | 11        | 16.67%  |
| RAID | 8         | 12.12%  |
| IDE  | 4         | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 87.72%  |
| AMD    | 7         | 12.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz        | 3         | 5.26%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 5.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 3.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 3.51%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 3.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 3.51%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.75%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 1.75%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 1         | 1.75%   |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 1.75%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 1.75%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.75%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.75%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.75%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.75%   |
| Intel Core i5 CPU M 460 @ 2.53GHz        | 1         | 1.75%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 1         | 1.75%   |
| Intel Core i3-4020Y CPU @ 1.50GHz        | 1         | 1.75%   |
| Intel Core i3-2365M CPU @ 1.40GHz        | 1         | 1.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 1         | 1.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz     | 1         | 1.75%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz     | 1         | 1.75%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz     | 1         | 1.75%   |
| Intel Core 2 CPU T5600 @ 1.83GHz         | 1         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 1         | 1.75%   |
| Intel Celeron J4115 CPU @ 1.80GHz        | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 29.82%  |
| Intel Core i7        | 11        | 19.3%   |
| Intel Core i3        | 8         | 14.04%  |
| Intel Celeron        | 4         | 7.02%   |
| Intel Core 2 Duo     | 3         | 5.26%   |
| AMD Ryzen 5          | 3         | 5.26%   |
| Other                | 2         | 3.51%   |
| Intel Pentium        | 2         | 3.51%   |
| AMD A8               | 2         | 3.51%   |
| Intel Pentium Silver | 1         | 1.75%   |
| Intel Genuine        | 1         | 1.75%   |
| Intel Core 2         | 1         | 1.75%   |
| AMD Ryzen 3          | 1         | 1.75%   |
| AMD A10              | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 63.16%  |
| 4      | 17        | 29.82%  |
| 6      | 3         | 5.26%   |
| 1      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 73.68%  |
| 1      | 15        | 26.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 98.25%  |
| 32-bit         | 1         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 18.33%  |
| 0x206a7    | 10        | 16.67%  |
| 0x20655    | 4         | 6.67%   |
| 0x806ec    | 3         | 5%      |
| 0x806ea    | 3         | 5%      |
| 0x706a1    | 3         | 5%      |
| 0x406e3    | 2         | 3.33%   |
| 0x306d4    | 2         | 3.33%   |
| 0x306a9    | 2         | 3.33%   |
| 0x08108109 | 2         | 3.33%   |
| 0xa0652    | 1         | 1.67%   |
| 0x906ea    | 1         | 1.67%   |
| 0x806e9    | 1         | 1.67%   |
| 0x806c1    | 1         | 1.67%   |
| 0x706e5    | 1         | 1.67%   |
| 0x6e8      | 1         | 1.67%   |
| 0x506c9    | 1         | 1.67%   |
| 0x406c4    | 1         | 1.67%   |
| 0x406c3    | 1         | 1.67%   |
| 0x40651    | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x20652    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x08600106 | 1         | 1.67%   |
| 0x08600104 | 1         | 1.67%   |
| 0x07030105 | 1         | 1.67%   |
| 0x06003106 | 1         | 1.67%   |
| 0x06001119 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 10        | 17.54%  |
| KabyLake      | 8         | 14.04%  |
| Westmere      | 5         | 8.77%   |
| Skylake       | 4         | 7.02%   |
| Penryn        | 3         | 5.26%   |
| Haswell       | 3         | 5.26%   |
| Goldmont plus | 3         | 5.26%   |
| Zen+          | 2         | 3.51%   |
| Zen 2         | 2         | 3.51%   |
| TigerLake     | 2         | 3.51%   |
| Silvermont    | 2         | 3.51%   |
| IvyBridge     | 2         | 3.51%   |
| IceLake       | 2         | 3.51%   |
| Broadwell     | 2         | 3.51%   |
| Steamroller   | 1         | 1.75%   |
| Puma          | 1         | 1.75%   |
| Piledriver    | 1         | 1.75%   |
| P6            | 1         | 1.75%   |
| Goldmont      | 1         | 1.75%   |
| Core          | 1         | 1.75%   |
| CometLake     | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 73.13%  |
| AMD    | 10        | 14.93%  |
| Nvidia | 8         | 11.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 13.89%  |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 6.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 5.56%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.17%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 2.78%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.78%   |
| AMD Renoir                                                                               | 2         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.39%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.39%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.39%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.39%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.39%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 1.39%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.39%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.39%   |
| Intel HD Graphics 620                                                                    | 1         | 1.39%   |
| Intel HD Graphics 500                                                                    | 1         | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.39%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 1.39%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.39%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 1         | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.39%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 68.42%  |
| Intel + Nvidia | 7         | 12.28%  |
| 1 x AMD        | 6         | 10.53%  |
| Intel + AMD    | 3         | 5.26%   |
| 2 x Nvidia     | 1         | 1.75%   |
| 2 x AMD        | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 91.53%  |
| Proprietary | 4         | 6.78%   |
| Unknown     | 1         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 71.67%  |
| 0.51-1.0   | 5         | 8.33%   |
| 0.01-0.5   | 4         | 6.67%   |
| 1.01-2.0   | 3         | 5%      |
| 5.01-6.0   | 2         | 3.33%   |
| 3.01-4.0   | 2         | 3.33%   |
| 2.01-3.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 17.46%  |
| Samsung Electronics     | 10        | 15.87%  |
| LG Display              | 10        | 15.87%  |
| AU Optronics            | 7         | 11.11%  |
| BOE                     | 6         | 9.52%   |
| PANDA                   | 3         | 4.76%   |
| Apple                   | 3         | 4.76%   |
| Goldstar                | 2         | 3.17%   |
| Dell                    | 2         | 3.17%   |
| Sony                    | 1         | 1.59%   |
| RTK                     | 1         | 1.59%   |
| ONN                     | 1         | 1.59%   |
| Lenovo                  | 1         | 1.59%   |
| InnoLux Display         | 1         | 1.59%   |
| eMachines               | 1         | 1.59%   |
| Chi Mei Optoelectronics | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |
| Ancor Communications    | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 4.76%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 3.17%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.59%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 1.59%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 1.59%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 1.59%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 1.59%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 1.59%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.59%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.59%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 1.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 1         | 1.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.59%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                 | 1         | 1.59%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                    | 1         | 1.59%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch               | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 24        | 40.68%  |
| 1920x1080 (FHD)  | 23        | 38.98%  |
| 1280x800 (WXGA)  | 4         | 6.78%   |
| 1440x900 (WXGA+) | 3         | 5.08%   |
| 1600x900 (HD+)   | 2         | 3.39%   |
| 3840x2160 (4K)   | 1         | 1.69%   |
| 3200x1800 (QHD+) | 1         | 1.69%   |
| 2560x1080        | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 29        | 46.77%  |
| 14     | 7         | 11.29%  |
| 17     | 6         | 9.68%   |
| 13     | 5         | 8.06%   |
| 31     | 3         | 4.84%   |
| 21     | 3         | 4.84%   |
| 11     | 2         | 3.23%   |
| 72     | 1         | 1.61%   |
| 34     | 1         | 1.61%   |
| 27     | 1         | 1.61%   |
| 24     | 1         | 1.61%   |
| 23     | 1         | 1.61%   |
| 19     | 1         | 1.61%   |
| 18     | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 59.68%  |
| 351-400     | 7         | 11.29%  |
| 401-500     | 5         | 8.06%   |
| 201-300     | 5         | 8.06%   |
| 601-700     | 3         | 4.84%   |
| 501-600     | 3         | 4.84%   |
| 701-800     | 1         | 1.61%   |
| 1501-2000   | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 85.96%  |
| 16/10 | 7         | 12.28%  |
| 21/9  | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 46.77%  |
| 81-90          | 11        | 17.74%  |
| 121-130        | 5         | 8.06%   |
| 351-500        | 4         | 6.45%   |
| 201-250        | 3         | 4.84%   |
| 151-200        | 3         | 4.84%   |
| 51-60          | 2         | 3.23%   |
| More than 1000 | 1         | 1.61%   |
| 71-80          | 1         | 1.61%   |
| 301-350        | 1         | 1.61%   |
| 141-150        | 1         | 1.61%   |
| 131-140        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 30        | 47.62%  |
| 121-160       | 19        | 30.16%  |
| 51-100        | 10        | 15.87%  |
| 1-50          | 3         | 4.76%   |
| More than 240 | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 77.97%  |
| 2     | 11        | 18.64%  |
| 0     | 2         | 3.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 35.35%  |
| Realtek Semiconductor    | 29        | 29.29%  |
| Qualcomm Atheros         | 11        | 11.11%  |
| Broadcom                 | 7         | 7.07%   |
| Marvell Technology Group | 3         | 3.03%   |
| Broadcom Limited         | 3         | 3.03%   |
| Ralink Technology        | 2         | 2.02%   |
| NetGear                  | 2         | 2.02%   |
| ASIX Electronics         | 2         | 2.02%   |
| TP-Link                  | 1         | 1.01%   |
| Samsung Electronics      | 1         | 1.01%   |
| Nvidia                   | 1         | 1.01%   |
| Dell                     | 1         | 1.01%   |
| Belkin Components        | 1         | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 18        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 4.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 2.78%   |
| Intel Wireless 7265                                                            | 3         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.85%   |
| Intel Wireless 3160                                                            | 2         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.85%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.85%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 2         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.93%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.93%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.93%   |
| NetGear LB1120-100NAS                                                          | 1         | 0.93%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.93%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.93%   |
| Intel Wireless 8260                                                            | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 46.77%  |
| Realtek Semiconductor | 10        | 16.13%  |
| Qualcomm Atheros      | 9         | 14.52%  |
| Broadcom              | 6         | 9.68%   |
| Ralink Technology     | 2         | 3.23%   |
| Broadcom Limited      | 2         | 3.23%   |
| TP-Link               | 1         | 1.61%   |
| NetGear               | 1         | 1.61%   |
| Dell                  | 1         | 1.61%   |
| Belkin Components     | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 3         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 3         | 4.76%   |
| Intel Wireless 7265                                         | 3         | 4.76%   |
| Intel Wi-Fi 6 AX200                                         | 3         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 2         | 3.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                  | 2         | 3.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                       | 2         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 2         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 2         | 3.17%   |
| Intel Wireless 3160                                         | 2         | 3.17%   |
| Intel Wi-Fi 6 AX201                                         | 2         | 3.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection       | 2         | 3.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]               | 2         | 3.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                | 2         | 3.17%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]               | 2         | 3.17%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                     | 2         | 3.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 2         | 3.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                | 1         | 1.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 1         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 1         | 1.59%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter  | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 1         | 1.59%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]       | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                  | 1         | 1.59%   |
| Intel Wireless 8260                                         | 1         | 1.59%   |
| Intel Wireless 7260                                         | 1         | 1.59%   |
| Intel Wireless 3165                                         | 1         | 1.59%   |
| Intel WiFi Link 5100                                        | 1         | 1.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                             | 1         | 1.59%   |
| Intel Gemini Lake PCH CNVi WiFi                             | 1         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 1         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 1         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                    | 1         | 1.59%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card | 1         | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                              | 1         | 1.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller      | 1         | 1.59%   |
| Broadcom BCM4321 802.11a/b/g/n                              | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 51.11%  |
| Intel                    | 8         | 17.78%  |
| Qualcomm Atheros         | 3         | 6.67%   |
| Marvell Technology Group | 3         | 6.67%   |
| Broadcom                 | 2         | 4.44%   |
| ASIX Electronics         | 2         | 4.44%   |
| Samsung Electronics      | 1         | 2.22%   |
| Nvidia                   | 1         | 2.22%   |
| NetGear                  | 1         | 2.22%   |
| Broadcom Limited         | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 18        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 6.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 4.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 2.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 2.22%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 2.22%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 2.22%   |
| NetGear LB1120-100NAS                                                          | 1         | 2.22%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.22%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 2.22%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 2.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 2.22%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 2.22%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 2.22%   |
| ASIX AX88772B                                                                  | 1         | 2.22%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 55.45%  |
| Ethernet | 45        | 44.55%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 78.33%  |
| Ethernet | 13        | 21.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 68.42%  |
| 1     | 16        | 28.07%  |
| 3     | 1         | 1.75%   |
| 0     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 79.31%  |
| Yes  | 12        | 20.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 51.11%  |
| Realtek Semiconductor           | 6         | 13.33%  |
| Apple                           | 3         | 6.67%   |
| Qualcomm Atheros Communications | 2         | 4.44%   |
| Lite-On Technology              | 2         | 4.44%   |
| IMC Networks                    | 2         | 4.44%   |
| Foxconn / Hon Hai               | 2         | 4.44%   |
| Dell                            | 2         | 4.44%   |
| Toshiba                         | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |
| Alps Electric                   | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 9         | 20%     |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 11.11%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 8.89%   |
| Intel AX200 Bluetooth                                                               | 3         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 4.44%   |
| Intel AX201 Bluetooth                                                               | 2         | 4.44%   |
| Apple Bluetooth Host Controller                                                     | 2         | 4.44%   |
| Toshiba BCM43142A0                                                                  | 1         | 2.22%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 2.22%   |
| Lite-On Bluetooth Device                                                            | 1         | 2.22%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 2.22%   |
| IMC Networks Bluetooth Device                                                       | 1         | 2.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 2.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.22%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 2.22%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.22%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.22%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.22%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 81.67%  |
| AMD    | 7         | 11.67%  |
| Nvidia | 4         | 6.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 12.33%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 10.96%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 6.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 5.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 4.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 4.11%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.74%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.37%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.37%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.37%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 34.78%  |
| Samsung Electronics | 6         | 26.09%  |
| Micron Technology   | 2         | 8.7%    |
| Kingston            | 2         | 8.7%    |
| Unknown             | 1         | 4.35%   |
| Silicon Power       | 1         | 4.35%   |
| Ramaxel Technology  | 1         | 4.35%   |
| PNY                 | 1         | 4.35%   |
| A-DATA Technology   | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s  | 2         | 7.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 7.69%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s  | 1         | 3.85%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 3.85%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 3.85%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 3.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 3.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.85%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 3.85%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 50%     |
| DDR3   | 7         | 31.82%  |
| LPDDR4 | 2         | 9.09%   |
| LPDDR3 | 1         | 4.55%   |
| DDR    | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 95.24%  |
| Row Of Chips | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 11        | 50%     |
| 4096 | 10        | 45.45%  |
| 2048 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 30.43%  |
| 1600  | 7         | 30.43%  |
| 3200  | 3         | 13.04%  |
| 3266  | 1         | 4.35%   |
| 2400  | 1         | 4.35%   |
| 2133  | 1         | 4.35%   |
| 1067  | 1         | 4.35%   |
| 800   | 1         | 4.35%   |
| 667   | 1         | 4.35%   |

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
| Chicony Electronics                    | 9         | 18.75%  |
| Ricoh                                  | 5         | 10.42%  |
| Realtek Semiconductor                  | 4         | 8.33%   |
| IMC Networks                           | 4         | 8.33%   |
| Acer                                   | 4         | 8.33%   |
| Quanta                                 | 3         | 6.25%   |
| Microdia                               | 3         | 6.25%   |
| Suyin                                  | 2         | 4.17%   |
| Sunplus Innovation Technology          | 2         | 4.17%   |
| Luxvisions Innotech Limited            | 2         | 4.17%   |
| Lite-On Technology                     | 2         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.17%   |
| Apple                                  | 2         | 4.17%   |
| Syntek                                 | 1         | 2.08%   |
| Lenovo                                 | 1         | 2.08%   |
| Goertek Electronics                    | 1         | 2.08%   |
| Alpha Imaging Technology               | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                         | 3         | 6.25%   |
| Chicony HD WebCam                                               | 2         | 4.17%   |
| Acer Lenovo EasyCamera                                          | 2         | 4.17%   |
| Syntek Lenovo EasyCamera                                        | 1         | 2.08%   |
| Suyin USB 2.0 Camera                                            | 1         | 2.08%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.08%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam        | 1         | 2.08%   |
| Ricoh HD Webcam                                                 | 1         | 2.08%   |
| Realtek USB2.0 camera                                           | 1         | 2.08%   |
| Realtek USB Camera                                              | 1         | 2.08%   |
| Realtek Integrated Webcam HD                                    | 1         | 2.08%   |
| Realtek Integrated Webcam                                       | 1         | 2.08%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 2.08%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 2.08%   |
| Quanta HD WebCam                                                | 1         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 2.08%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.08%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 1         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.08%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 2.08%   |
| Lite-On HP HD Webcam                                            | 1         | 2.08%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 2.08%   |
| IMC Networks UVC VGA Webcam                                     | 1         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 1         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 2.08%   |
| IMC Networks Integrated Camera                                  | 1         | 2.08%   |
| Goertek USB2.0 VGA UVC WebCam                                   | 1         | 2.08%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.08%   |
| Chicony Toshiba Integrated Webcam                               | 1         | 2.08%   |
| Chicony Integrated HP HD Webcam                                 | 1         | 2.08%   |
| Chicony HP Webcam                                               | 1         | 2.08%   |
| Chicony HP Truevision HD                                        | 1         | 2.08%   |
| Chicony HP HD Camera                                            | 1         | 2.08%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.08%   |
| Apple FaceTime HD Camera                                        | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 63.64%  |
| Synaptics             | 2         | 18.18%  |
| LighTuning Technology | 2         | 18.18%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 3         | 27.27%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner              | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Unknown                                           | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 65.52%  |
| 1     | 19        | 32.76%  |
| 2     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 50%     |
| Net/wireless             | 3         | 13.64%  |
| Graphics card            | 3         | 13.64%  |
| Chipcard                 | 3         | 13.64%  |
| Storage                  | 1         | 4.55%   |
| Communication controller | 1         | 4.55%   |


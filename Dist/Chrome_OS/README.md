Chrome OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Chrome OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Chrome_OS/Desktop/README.md) and [notebooks](/Dist/Chrome_OS/Notebook/README.md).

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

Total: 97

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google        | Gnawty                      | Notebook    | [e2b489f0a7](https://linux-hardware.org/?probe=e2b489f0a7) | Feb 01, 2023 |
| Google        | Gnawty                      | Notebook    | [4188917829](https://linux-hardware.org/?probe=4188917829) | Jan 31, 2023 |
| Intel Clie... | LAPKC71F                    | Notebook    | [3ae3afeece](https://linux-hardware.org/?probe=3ae3afeece) | Jul 13, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [91780395d8](https://linux-hardware.org/?probe=91780395d8) | Dec 25, 2021 |
| Google        | Grunt                       | Notebook    | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| Google        | Akemi                       | Notebook    | [d59a7856ce](https://linux-hardware.org/?probe=d59a7856ce) | Sep 04, 2021 |
| Google        | Akemi                       | Notebook    | [91212d1a8e](https://linux-hardware.org/?probe=91212d1a8e) | Sep 04, 2021 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [5452f92c7b](https://linux-hardware.org/?probe=5452f92c7b) | Mar 29, 2021 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [3d51048d61](https://linux-hardware.org/?probe=3d51048d61) | Mar 29, 2021 |
| Google        | Eve                         | Convertible | [cbc1bb3811](https://linux-hardware.org/?probe=cbc1bb3811) | Mar 19, 2021 |
| HP            | 3033h                       | Desktop     | [c2dace7dd3](https://linux-hardware.org/?probe=c2dace7dd3) | Mar 05, 2021 |
| HP            | 3033h                       | Desktop     | [dee35e0ef1](https://linux-hardware.org/?probe=dee35e0ef1) | Feb 27, 2021 |
| HP            | 3033h                       | Desktop     | [41495dac27](https://linux-hardware.org/?probe=41495dac27) | Feb 26, 2021 |
| HP            | Compaq 6510b (GB867ET#AK... | Notebook    | [c9c18dfdeb](https://linux-hardware.org/?probe=c9c18dfdeb) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Toshiba       | Satellite C850-14X          | Notebook    | [73977134ff](https://linux-hardware.org/?probe=73977134ff) | Feb 12, 2021 |
| Lenovo        | ThinkPad T500 22439AG       | Notebook    | [fe8ffb1fc3](https://linux-hardware.org/?probe=fe8ffb1fc3) | Jan 27, 2021 |
| Dell          | 0PU052                      | Desktop     | [855a0698a6](https://linux-hardware.org/?probe=855a0698a6) | Jan 10, 2021 |
| Dell          | 0PU052                      | Desktop     | [4472b7cd46](https://linux-hardware.org/?probe=4472b7cd46) | Jan 10, 2021 |
| Chuwi         | UBook Pro                   | Notebook    | [ae3077af50](https://linux-hardware.org/?probe=ae3077af50) | Jan 01, 2021 |
| HP            | Compaq 6510b (GB867ET#AK... | Notebook    | [65279b81c8](https://linux-hardware.org/?probe=65279b81c8) | Dec 28, 2020 |
| Dell          | 0CRH6C A00                  | Desktop     | [d23fabf572](https://linux-hardware.org/?probe=d23fabf572) | Dec 27, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | Notebook    | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | Notebook    | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| Chuwi         | UBook Pro                   | Notebook    | [e908ef1b8f](https://linux-hardware.org/?probe=e908ef1b8f) | Dec 22, 2020 |
| Chuwi         | UBook Pro                   | Notebook    | [022d7e1d0d](https://linux-hardware.org/?probe=022d7e1d0d) | Dec 22, 2020 |
| ASUSTek       | P5GD1                       | Desktop     | [5a7acf0d43](https://linux-hardware.org/?probe=5a7acf0d43) | Dec 19, 2020 |
| Google        | Stout                       | Notebook    | [2e966e7fba](https://linux-hardware.org/?probe=2e966e7fba) | Dec 11, 2020 |
| Google        | Stout                       | Notebook    | [e93637345c](https://linux-hardware.org/?probe=e93637345c) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | Notebook    | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| MSI           | P6N SLI                     | Desktop     | [ac24861b49](https://linux-hardware.org/?probe=ac24861b49) | Dec 06, 2020 |
| MSI           | P6N SLI                     | Desktop     | [04304ff21c](https://linux-hardware.org/?probe=04304ff21c) | Dec 06, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [e7e19a17c2](https://linux-hardware.org/?probe=e7e19a17c2) | Nov 23, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [4fccf7c912](https://linux-hardware.org/?probe=4fccf7c912) | Nov 15, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [00d5983461](https://linux-hardware.org/?probe=00d5983461) | Nov 15, 2020 |
| Intel         | DN2820FYK H24582-202        | Desktop     | [1379002508](https://linux-hardware.org/?probe=1379002508) | Nov 01, 2020 |
| Haier         | HI133L                      | Notebook    | [b475b32fbe](https://linux-hardware.org/?probe=b475b32fbe) | Oct 18, 2020 |
| Haier         | HI133L                      | Notebook    | [f3537f4f0c](https://linux-hardware.org/?probe=f3537f4f0c) | Oct 18, 2020 |
| HP            | 15 TouchSmart               | Notebook    | [8e8b2c7b3b](https://linux-hardware.org/?probe=8e8b2c7b3b) | Oct 02, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [8ca04b349d](https://linux-hardware.org/?probe=8ca04b349d) | Sep 18, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [fe0a0fac0f](https://linux-hardware.org/?probe=fe0a0fac0f) | Sep 18, 2020 |
| Acer          | Aspire ES1-411              | Notebook    | [8dcd17e446](https://linux-hardware.org/?probe=8dcd17e446) | Sep 15, 2020 |
| Dell          | 0V6D8J A00                  | Desktop     | [557355ba08](https://linux-hardware.org/?probe=557355ba08) | Sep 15, 2020 |
| Dell          | 0V6D8J A00                  | Desktop     | [bf4e456e50](https://linux-hardware.org/?probe=bf4e456e50) | Sep 15, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [fc28ab4623](https://linux-hardware.org/?probe=fc28ab4623) | Aug 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [2a1cb09252](https://linux-hardware.org/?probe=2a1cb09252) | Aug 17, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6ab94ce643](https://linux-hardware.org/?probe=6ab94ce643) | May 26, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [ba370ad4d4](https://linux-hardware.org/?probe=ba370ad4d4) | May 18, 2020 |
| Insyde        | MID-WIN1052                 | Notebook    | [c3623326f4](https://linux-hardware.org/?probe=c3623326f4) | May 13, 2020 |
| Insyde        | MID-WIN1052                 | Notebook    | [c0583f7e16](https://linux-hardware.org/?probe=c0583f7e16) | May 13, 2020 |
| HP            | Stream Notebook             | Notebook    | [1d99923bed](https://linux-hardware.org/?probe=1d99923bed) | May 10, 2020 |
| HP            | Stream Notebook             | Notebook    | [b8f59efc42](https://linux-hardware.org/?probe=b8f59efc42) | May 10, 2020 |
| Toshiba       | Satellite T130              | Notebook    | [0c6c8b85d4](https://linux-hardware.org/?probe=0c6c8b85d4) | May 06, 2020 |
| Toshiba       | Satellite T130              | Notebook    | [5a28a5cd81](https://linux-hardware.org/?probe=5a28a5cd81) | May 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [43b2da97bf](https://linux-hardware.org/?probe=43b2da97bf) | Apr 30, 2020 |
| Google        | Peppy                       | Notebook    | [417b93b591](https://linux-hardware.org/?probe=417b93b591) | Apr 28, 2020 |
| Google        | Peppy                       | Notebook    | [3a4c5d1adf](https://linux-hardware.org/?probe=3a4c5d1adf) | Apr 28, 2020 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [cd2222973b](https://linux-hardware.org/?probe=cd2222973b) | Apr 21, 2020 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [05c4106212](https://linux-hardware.org/?probe=05c4106212) | Apr 20, 2020 |
| HP            | Pavilion dv6                | Notebook    | [26098586ce](https://linux-hardware.org/?probe=26098586ce) | Apr 19, 2020 |
| Dell          | 05XGC8 A01                  | Desktop     | [f243c5fe72](https://linux-hardware.org/?probe=f243c5fe72) | Apr 17, 2020 |
| Dell          | 05XGC8 A01                  | Desktop     | [7e85fad5a0](https://linux-hardware.org/?probe=7e85fad5a0) | Apr 17, 2020 |
| ONDA          | OBOOK 11                    | Notebook    | [ee48f07c90](https://linux-hardware.org/?probe=ee48f07c90) | Apr 14, 2020 |
| ONDA          | OBOOK 11                    | Notebook    | [2833831652](https://linux-hardware.org/?probe=2833831652) | Apr 14, 2020 |
| ONDA          | OBOOK 11                    | Notebook    | [9f4ddc3830](https://linux-hardware.org/?probe=9f4ddc3830) | Apr 14, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [3117acfee5](https://linux-hardware.org/?probe=3117acfee5) | Apr 11, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [a3c88b9be1](https://linux-hardware.org/?probe=a3c88b9be1) | Apr 11, 2020 |
| Acer          | Aspire 3810T                | Notebook    | [10965a7219](https://linux-hardware.org/?probe=10965a7219) | Mar 23, 2020 |
| Google        | Panther                     | Desktop     | [fbc127e88c](https://linux-hardware.org/?probe=fbc127e88c) | Feb 17, 2020 |
| Google        | Panther                     | Desktop     | [5ead9de21a](https://linux-hardware.org/?probe=5ead9de21a) | Feb 17, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [d558a45887](https://linux-hardware.org/?probe=d558a45887) | Feb 09, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [b2a0d6b4ee](https://linux-hardware.org/?probe=b2a0d6b4ee) | Feb 09, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | Notebook    | [eaf4701374](https://linux-hardware.org/?probe=eaf4701374) | Feb 08, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | Notebook    | [1ca0264090](https://linux-hardware.org/?probe=1ca0264090) | Feb 04, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | Notebook    | [f1d169e079](https://linux-hardware.org/?probe=f1d169e079) | Feb 04, 2020 |
| Dell          | Latitude E5420              | Notebook    | [ad85615ed1](https://linux-hardware.org/?probe=ad85615ed1) | Jan 26, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [9afa4563ce](https://linux-hardware.org/?probe=9afa4563ce) | Jan 15, 2020 |
| Positivo      | Q232A                       | Notebook    | [7cbfc66813](https://linux-hardware.org/?probe=7cbfc66813) | Jan 15, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [7d7699569b](https://linux-hardware.org/?probe=7d7699569b) | Jan 08, 2020 |
| HP            | 635                         | Notebook    | [8bd618c5d7](https://linux-hardware.org/?probe=8bd618c5d7) | Jan 08, 2020 |
| ASUSTek       | P5B-PLUS Series             | Desktop     | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [6a1ec0281a](https://linux-hardware.org/?probe=6a1ec0281a) | Dec 11, 2019 |
| HP            | Pavilion dv3500             | Notebook    | [ba878abe40](https://linux-hardware.org/?probe=ba878abe40) | Dec 09, 2019 |
| HP            | Pavilion dv3500             | Notebook    | [089a351d46](https://linux-hardware.org/?probe=089a351d46) | Dec 09, 2019 |
| NEC Comput... | ECS-945G                    | Desktop     | [3494d9ef49](https://linux-hardware.org/?probe=3494d9ef49) | Nov 10, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Positivo      | S14CT01                     | Notebook    | [dc55febba4](https://linux-hardware.org/?probe=dc55febba4) | May 14, 2019 |
| Dell          | Latitude E6400              | Notebook    | [8ab390f2d4](https://linux-hardware.org/?probe=8ab390f2d4) | Mar 17, 2019 |
| HP            | 15 TouchSmart               | Notebook    | [d96ad40896](https://linux-hardware.org/?probe=d96ad40896) | Jan 04, 2019 |
| HP            | 15 TouchSmart               | Notebook    | [3cfc2a6f62](https://linux-hardware.org/?probe=3cfc2a6f62) | Jan 03, 2019 |
| Acer          | Swift SF114-31              | Notebook    | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Lenovo        | ThinkPad T500 224234U       | Notebook    | [81a4da9481](https://linux-hardware.org/?probe=81a4da9481) | Oct 30, 2018 |
| Lenovo        | ThinkPad T500 224234U       | Notebook    | [a738fda6fa](https://linux-hardware.org/?probe=a738fda6fa) | Oct 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Chrome OS    | 56        | 94.92%  |
| Chrome OS 94 | 2         | 3.39%   |
| Chrome OS 93 | 1         | 1.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Chrome OS | 59        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.4.53+                      | 12        | 19.05%  |
| 4.19.88+                     | 11        | 17.46%  |
| 4.19.65+                     | 11        | 17.46%  |
| 5.4.66+                      | 9         | 14.29%  |
| 5.4.25+                      | 8         | 12.7%   |
| 4.19.49+                     | 4         | 6.35%   |
| 4.14.86+                     | 2         | 3.17%   |
| 5.4.157-brunch-sebanc        | 1         | 1.59%   |
| 4.4.275-20726-g204ae1828356  | 1         | 1.59%   |
| 4.14.65+                     | 1         | 1.59%   |
| 4.14.58+                     | 1         | 1.59%   |
| 4.14.243-18084-g7bc10658733d | 1         | 1.59%   |
| 4.14.105+                    | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.53   | 12        | 19.05%  |
| 4.19.88  | 11        | 17.46%  |
| 4.19.65  | 11        | 17.46%  |
| 5.4.66   | 9         | 14.29%  |
| 5.4.25   | 8         | 12.7%   |
| 4.19.49  | 4         | 6.35%   |
| 4.14.86  | 2         | 3.17%   |
| 5.4.157  | 1         | 1.59%   |
| 4.4.275  | 1         | 1.59%   |
| 4.14.65  | 1         | 1.59%   |
| 4.14.58  | 1         | 1.59%   |
| 4.14.243 | 1         | 1.59%   |
| 4.14.105 | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 46.67%  |
| 4.19    | 25        | 41.67%  |
| 4.14    | 6         | 10%     |
| 4.4     | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 32        | 54.24%  |
| EFI  | 27        | 45.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 80%     |
| Unknown | 9         | 15%     |
| Ext2    | 3         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 94.92%  |
| GPT     | 3         | 5.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 94.92%  |
| Yes       | 3         | 5.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 98.31%  |
| Yes       | 1         | 1.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 16.95%  |
| Dell                | 10        | 16.95%  |
| Lenovo              | 7         | 11.86%  |
| Google              | 6         | 10.17%  |
| ASUSTek Computer    | 4         | 6.78%   |
| Acer                | 3         | 5.08%   |
| Unknown             | 3         | 5.08%   |
| Toshiba             | 2         | 3.39%   |
| Positivo            | 2         | 3.39%   |
| Samsung Electronics | 1         | 1.69%   |
| ONDA                | 1         | 1.69%   |
| NEC Computers       | 1         | 1.69%   |
| MSI                 | 1         | 1.69%   |
| Intel               | 1         | 1.69%   |
| Insyde              | 1         | 1.69%   |
| Hampoo              | 1         | 1.69%   |
| Haier               | 1         | 1.69%   |
| Gigabyte Technology | 1         | 1.69%   |
| Fujitsu Siemens     | 1         | 1.69%   |
| Chuwi               | 1         | 1.69%   |
| Apple               | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 3         | 5.08%   |
| HP Pavilion dv6                       | 2         | 3.39%   |
| Dell Inspiron 1545                    | 2         | 3.39%   |
| Toshiba Satellite T130                | 1         | 1.69%   |
| Toshiba Satellite C850-14X            | 1         | 1.69%   |
| Samsung DeskTop System                | 1         | 1.69%   |
| Positivo S14CT01                      | 1         | 1.69%   |
| Positivo Q232A                        | 1         | 1.69%   |
| ONDA OBOOK 11                         | 1         | 1.69%   |
| NEC Computers ECS-945G                | 1         | 1.69%   |
| MSI MS-7350                           | 1         | 1.69%   |
| Lenovo ThinkPad T500 22439AG          | 1         | 1.69%   |
| Lenovo ThinkPad T500 224234U          | 1         | 1.69%   |
| Lenovo ThinkPad T500 2055WYX          | 1         | 1.69%   |
| Lenovo ThinkPad SL400 27439MA         | 1         | 1.69%   |
| Lenovo IdeaPad S145-14IWL 81MU        | 1         | 1.69%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 1         | 1.69%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 1         | 1.69%   |
| Intel DN2820FYK H24582-202            | 1         | 1.69%   |
| Insyde MID-WIN1052                    | 1         | 1.69%   |
| HP Stream Notebook                    | 1         | 1.69%   |
| HP Stream Laptop 14-ax0XX             | 1         | 1.69%   |
| HP Pavilion dv3500                    | 1         | 1.69%   |
| HP EliteBook 8460p                    | 1         | 1.69%   |
| HP Compaq dc7900 Ultra-Slim Desktop   | 1         | 1.69%   |
| HP Compaq 6510b (GB867ET#AK8)         | 1         | 1.69%   |
| HP 635                                | 1         | 1.69%   |
| HP 15 TouchSmart                      | 1         | 1.69%   |
| Hampoo NA123                          | 1         | 1.69%   |
| Haier HI133L                          | 1         | 1.69%   |
| Google Stout                          | 1         | 1.69%   |
| Google Peppy                          | 1         | 1.69%   |
| Google Panther                        | 1         | 1.69%   |
| Google Grunt                          | 1         | 1.69%   |
| Google Gnawty                         | 1         | 1.69%   |
| Google Eve                            | 1         | 1.69%   |
| Gigabyte F2A68HM-H                    | 1         | 1.69%   |
| Fujitsu Siemens LIFEBOOK E8420        | 1         | 1.69%   |
| Dell XPS 15 7590                      | 1         | 1.69%   |
| Dell Precision WorkStation T5500      | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 6.78%   |
| Lenovo IdeaPad           | 3         | 5.08%   |
| HP Pavilion              | 3         | 5.08%   |
| Dell Latitude            | 3         | 5.08%   |
| Dell Inspiron            | 3         | 5.08%   |
| Unknown                  | 3         | 5.08%   |
| Toshiba Satellite        | 2         | 3.39%   |
| HP Stream                | 2         | 3.39%   |
| HP Compaq                | 2         | 3.39%   |
| Dell OptiPlex            | 2         | 3.39%   |
| Acer Aspire              | 2         | 3.39%   |
| Samsung DeskTop          | 1         | 1.69%   |
| Positivo S14CT01         | 1         | 1.69%   |
| Positivo Q232A           | 1         | 1.69%   |
| ONDA OBOOK               | 1         | 1.69%   |
| NEC Computers ECS-945G   | 1         | 1.69%   |
| MSI MS-7350              | 1         | 1.69%   |
| Intel DN2820FYK          | 1         | 1.69%   |
| Insyde MID-WIN1052       | 1         | 1.69%   |
| HP EliteBook             | 1         | 1.69%   |
| HP 635                   | 1         | 1.69%   |
| HP 15                    | 1         | 1.69%   |
| Hampoo NA123             | 1         | 1.69%   |
| Haier HI133L             | 1         | 1.69%   |
| Google Stout             | 1         | 1.69%   |
| Google Peppy             | 1         | 1.69%   |
| Google Panther           | 1         | 1.69%   |
| Google Grunt             | 1         | 1.69%   |
| Google Gnawty            | 1         | 1.69%   |
| Google Eve               | 1         | 1.69%   |
| Gigabyte F2A68HM-H       | 1         | 1.69%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.69%   |
| Dell XPS                 | 1         | 1.69%   |
| Dell Precision           | 1         | 1.69%   |
| Chuwi UBook              | 1         | 1.69%   |
| ASUS P5GD1               | 1         | 1.69%   |
| ASUS P5B-PLUS            | 1         | 1.69%   |
| ASUS E200HA              | 1         | 1.69%   |
| ASUS C8HM70-I            | 1         | 1.69%   |
| Apple MacBookPro11       | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 13        | 22.03%  |
| 2014 | 6         | 10.17%  |
| 2020 | 5         | 8.47%   |
| 2019 | 4         | 6.78%   |
| 2018 | 4         | 6.78%   |
| 2017 | 4         | 6.78%   |
| 2016 | 4         | 6.78%   |
| 2015 | 4         | 6.78%   |
| 2011 | 4         | 6.78%   |
| 2009 | 3         | 5.08%   |
| 2007 | 3         | 5.08%   |
| 2012 | 2         | 3.39%   |
| 2013 | 1         | 1.69%   |
| 2010 | 1         | 1.69%   |
| 2005 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 44        | 74.58%  |
| Desktop     | 14        | 23.73%  |
| Convertible | 1         | 1.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 88.33%  |
| Enabled  | 7         | 11.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 89.83%  |
| Yes  | 6         | 10.17%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 22        | 37.29%  |
| 4.01-8.0   | 13        | 22.03%  |
| 1.01-2.0   | 13        | 22.03%  |
| 8.01-16.0  | 7         | 11.86%  |
| 2.01-3.0   | 2         | 3.39%   |
| 24.01-32.0 | 1         | 1.69%   |
| 16.01-24.0 | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 32        | 50%     |
| 2.01-3.0 | 18        | 28.13%  |
| 4.01-8.0 | 6         | 9.38%   |
| 3.01-4.0 | 5         | 7.81%   |
| 0.51-1.0 | 3         | 4.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 74.58%  |
| 2      | 14        | 23.73%  |
| 0      | 1         | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 55.93%  |
| Yes       | 26        | 44.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 66.1%   |
| No        | 20        | 33.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 78.33%  |
| No        | 13        | 21.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 55%     |
| No        | 27        | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 20.34%  |
| Italy       | 7         | 11.86%  |
| UK          | 5         | 8.47%   |
| Netherlands | 3         | 5.08%   |
| Hong Kong   | 3         | 5.08%   |
| Canada      | 3         | 5.08%   |
| Brazil      | 3         | 5.08%   |
| Sweden      | 2         | 3.39%   |
| South Korea | 2         | 3.39%   |
| Russia      | 2         | 3.39%   |
| Indonesia   | 2         | 3.39%   |
| Germany     | 2         | 3.39%   |
| Turkey      | 1         | 1.69%   |
| Spain       | 1         | 1.69%   |
| Slovenia    | 1         | 1.69%   |
| Norway      | 1         | 1.69%   |
| Ireland     | 1         | 1.69%   |
| India       | 1         | 1.69%   |
| Hungary     | 1         | 1.69%   |
| Greece      | 1         | 1.69%   |
| France      | 1         | 1.69%   |
| Belgium     | 1         | 1.69%   |
| Austria     | 1         | 1.69%   |
| Australia   | 1         | 1.69%   |
| Argentina   | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Central            | 3         | 5.08%   |
| Turin              | 2         | 3.39%   |
| Rome               | 2         | 3.39%   |
| Montreal           | 2         | 3.39%   |
| Yekaterinburg      | 1         | 1.69%   |
| Winter Garden      | 1         | 1.69%   |
| Welwyn Garden City | 1         | 1.69%   |
| Thessaloniki       | 1         | 1.69%   |
| Suwon              | 1         | 1.69%   |
| Spokane            | 1         | 1.69%   |
| South Bend         | 1         | 1.69%   |
| Sidney             | 1         | 1.69%   |
| Senador Jose Bento | 1         | 1.69%   |
| San Francisco      | 1         | 1.69%   |
| Samara             | 1         | 1.69%   |
| Porter Ranch       | 1         | 1.69%   |
| Oslo               | 1         | 1.69%   |
| Omagh              | 1         | 1.69%   |
| Oklahoma City      | 1         | 1.69%   |
| Navan              | 1         | 1.69%   |
| Murici             | 1         | 1.69%   |
| Middle River       | 1         | 1.69%   |
| Melbourne          | 1         | 1.69%   |
| Mannheim           | 1         | 1.69%   |
| Los Angeles        | 1         | 1.69%   |
| Ljubljana          | 1         | 1.69%   |
| Kolkata            | 1         | 1.69%   |
| Istanbul           | 1         | 1.69%   |
| Hitchin            | 1         | 1.69%   |
| Henan              | 1         | 1.69%   |
| Haarlem            | 1         | 1.69%   |
| Green Bay          | 1         | 1.69%   |
| Forlì             | 1         | 1.69%   |
| Farnborough        | 1         | 1.69%   |
| Falun              | 1         | 1.69%   |
| Etobicoke          | 1         | 1.69%   |
| Deurne             | 1         | 1.69%   |
| Debrecen           | 1         | 1.69%   |
| Crispiano          | 1         | 1.69%   |
| Concesio           | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Unknown                 | 18        | 24     | 28.13%  |
| WDC                     | 7         | 8      | 10.94%  |
| Seagate                 | 6         | 7      | 9.38%   |
| Samsung Electronics     | 5         | 6      | 7.81%   |
| Hitachi                 | 5         | 5      | 7.81%   |
| Kingston                | 4         | 5      | 6.25%   |
| Toshiba                 | 2         | 2      | 3.13%   |
| HGST                    | 2         | 3      | 3.13%   |
| Fujitsu                 | 2         | 2      | 3.13%   |
| Crucial                 | 2         | 2      | 3.13%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.56%   |
| TO Exter                | 1         | 1      | 1.56%   |
| SPCC                    | 1         | 1      | 1.56%   |
| SanDisk                 | 1         | 1      | 1.56%   |
| Patriot                 | 1         | 2      | 1.56%   |
| Netac                   | 1         | 2      | 1.56%   |
| MyDigitalSSD            | 1         | 1      | 1.56%   |
| KingSpec                | 1         | 1      | 1.56%   |
| KingDian                | 1         | 1      | 1.56%   |
| Intel                   | 1         | 1      | 1.56%   |
| China                   | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                       | 9         | 13.43%  |
| Unknown MMC Card  64GB                       | 6         | 8.96%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 2.99%   |
| Hitachi HTS725032A9A364 320GB                | 2         | 2.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1.49%   |
| WDC WDS100T2B0C-00PXH0 1TB                   | 1         | 1.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1.49%   |
| WDC WD5000 500GB                             | 1         | 1.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB                 | 1         | 1.49%   |
| WDC WD2500BEVS-08VAT2 250GB                  | 1         | 1.49%   |
| WDC WD1200BEVS-22UST0 120GB                  | 1         | 1.49%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB         | 1         | 1.49%   |
| Unknown MMC Card  8GB                        | 1         | 1.49%   |
| Unknown MMC Card  4GB                        | 1         | 1.49%   |
| Unknown MMC Card  16GB                       | 1         | 1.49%   |
| Unknown MMC Card  128GB                      | 1         | 1.49%   |
| Unknown MMC Card  118MB                      | 1         | 1.49%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 1.49%   |
| Toshiba MQ01ABD032 320GB                     | 1         | 1.49%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1.49%   |
| TO Exter nal USB 3.0 1024GB                  | 1         | 1.49%   |
| SPCC Solid State Disk 128GB                  | 1         | 1.49%   |
| Seagate ST980811AS 80GB                      | 1         | 1.49%   |
| Seagate ST980210AS 80GB                      | 1         | 1.49%   |
| Seagate ST9160821AS 160GB                    | 1         | 1.49%   |
| Seagate ST3160812AS 41N3268 LEN 160GB        | 1         | 1.49%   |
| SanDisk SSD U100 16GB                        | 1         | 1.49%   |
| Samsung SSD PM800 2.5 128GB                  | 1         | 1.49%   |
| Samsung SSD 850 EVO 250GB                    | 1         | 1.49%   |
| Samsung SSD 850 EVO 120GB                    | 1         | 1.49%   |
| Samsung MZNLN128HAHQ-000L2 128GB SSD         | 1         | 1.49%   |
| Samsung HD502IJ 500GB                        | 1         | 1.49%   |
| Patriot Inferno 120GB SSD                    | 1         | 1.49%   |
| Netac SSD 256GB                              | 1         | 1.49%   |
| MyDigitalSSD SC2 M2 SSD 120GB                | 1         | 1.49%   |
| Kingston SUV500120G 120GB SSD                | 1         | 1.49%   |
| Kingston SH100S3120G 120GB SSD               | 1         | 1.49%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1.49%   |
| Kingston SA2000M81000G 1TB                   | 1         | 1.49%   |
| KingSpec NT-256 256GB                        | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 25%     |
| WDC                 | 5         | 5      | 20.83%  |
| Hitachi             | 5         | 5      | 20.83%  |
| Toshiba             | 2         | 2      | 8.33%   |
| HGST                | 2         | 3      | 8.33%   |
| Fujitsu             | 2         | 2      | 8.33%   |
| TO Exter            | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 21.05%  |
| Kingston            | 3         | 4      | 15.79%  |
| Crucial             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| SPCC                | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| Patriot             | 1         | 2      | 5.26%   |
| Netac               | 1         | 2      | 5.26%   |
| MyDigitalSSD        | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| KingDian            | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| China               | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 26     | 37.5%   |
| SSD  | 19        | 23     | 29.69%  |
| MMC  | 18        | 24     | 28.13%  |
| NVMe | 3         | 4      | 4.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 48     | 64.52%  |
| MMC  | 18        | 24     | 29.03%  |
| NVMe | 3         | 4      | 4.84%   |
| SAS  | 1         | 1      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 48     | 97.56%  |
| 1.01-2.0   | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 15        | 25.42%  |
| 101-250    | 13        | 22.03%  |
| 51-100     | 10        | 16.95%  |
| 21-50      | 9         | 15.25%  |
| 501-1000   | 9         | 15.25%  |
| 1-20       | 3         | 5.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 54        | 90%     |
| 21-50   | 4         | 6.67%   |
| 51-100  | 2         | 3.33%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 58        | 74     | 96.67%  |
| Works    | 2         | 3      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 42        | 82.35%  |
| AMD                           | 3         | 5.88%   |
| Union Memory (Shenzhen)       | 1         | 1.96%   |
| Nvidia                        | 1         | 1.96%   |
| Marvell Technology Group      | 1         | 1.96%   |
| Kingston Technology Company   | 1         | 1.96%   |
| JMicron Technology            | 1         | 1.96%   |
| Integrated Technology Express | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 10        | 16.67%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 4         | 6.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 6.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 3         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 5%      |
| Intel Mobile 4 Series Chipset PT IDER Controller                              | 2         | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 3.33%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB               | 1         | 1.67%   |
| Nvidia MCP51 Serial ATA Controller                                            | 1         | 1.67%   |
| Nvidia MCP51 IDE                                                              | 1         | 1.67%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo         | 1         | 1.67%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                    | 1         | 1.67%   |
| JMicron JMB363 SATA/IDE Controller                                            | 1         | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.67%   |
| Intel 82Q35 Express PT IDER Controller                                        | 1         | 1.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 1         | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 1         | 1.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1         | 1.67%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]           | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 1.67%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 1         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 1.67%   |
| Intel 82801FR/FRW (ICH6R/ICH6RW) SATA Controller                              | 1         | 1.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                      | 1         | 1.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 1.67%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 1         | 1.67%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                    | 1         | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                            | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 74.07%  |
| IDE  | 10        | 18.52%  |
| RAID | 2         | 3.7%    |
| NVMe | 2         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 55        | 93.22%  |
| AMD    | 4         | 6.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N3450 @ 1.10GHz           | 4         | 6.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 5.08%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 2         | 3.39%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 3.39%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 2         | 3.39%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 3.39%   |
| Intel Xeon CPU X5687 @ 3.60GHz              | 1         | 1.69%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.69%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.69%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.69%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.69%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.69%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1         | 1.69%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.69%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 1.69%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 1         | 1.69%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.69%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i5-7Y57 CPU @ 1.20GHz            | 1         | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.69%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.69%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 1         | 1.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 12        | 20.34%  |
| Intel Core 2 Duo        | 11        | 18.64%  |
| Intel Core i5           | 7         | 11.86%  |
| Intel Atom              | 6         | 10.17%  |
| Intel Core i3           | 5         | 8.47%   |
| Intel Pentium           | 3         | 5.08%   |
| Intel Pentium Dual-Core | 2         | 3.39%   |
| Intel Genuine           | 2         | 3.39%   |
| Intel Core i7           | 2         | 3.39%   |
| Intel Xeon              | 1         | 1.69%   |
| Intel Pentium Dual      | 1         | 1.69%   |
| Intel Pentium 4         | 1         | 1.69%   |
| Intel Core m3           | 1         | 1.69%   |
| Intel Core 2 Quad       | 1         | 1.69%   |
| AMD E                   | 1         | 1.69%   |
| AMD Athlon II           | 1         | 1.69%   |
| AMD A6                  | 1         | 1.69%   |
| AMD A4                  | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 62.71%  |
| 4      | 18        | 30.51%  |
| 1      | 3         | 5.08%   |
| 6      | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 86.67%  |
| 2      | 8         | 13.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 85%     |
| Unknown        | 9         | 15%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 9         | 15%     |
| 0x206a7    | 5         | 8.33%   |
| 0x506c9    | 4         | 6.67%   |
| 0x406c4    | 4         | 6.67%   |
| 0x406c3    | 4         | 6.67%   |
| 0x306a9    | 4         | 6.67%   |
| Unknown    | 4         | 6.67%   |
| 0x6fd      | 3         | 5%      |
| 0x30678    | 3         | 5%      |
| 0x906ea    | 2         | 3.33%   |
| 0x806e9    | 2         | 3.33%   |
| 0x6fb      | 2         | 3.33%   |
| 0x40651    | 2         | 3.33%   |
| 0x10676    | 2         | 3.33%   |
| 0xf43      | 1         | 1.67%   |
| 0x806eb    | 1         | 1.67%   |
| 0x506e3    | 1         | 1.67%   |
| 0x306d4    | 1         | 1.67%   |
| 0x30673    | 1         | 1.67%   |
| 0x206c2    | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |
| 0x06003106 | 1         | 1.67%   |
| 0x05000101 | 1         | 1.67%   |
| 0x010000c8 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 13        | 22.03%  |
| Penryn      | 11        | 18.64%  |
| Core        | 6         | 10.17%  |
| SandyBridge | 5         | 8.47%   |
| KabyLake    | 5         | 8.47%   |
| IvyBridge   | 4         | 6.78%   |
| Goldmont    | 4         | 6.78%   |
| Haswell     | 3         | 5.08%   |
| Westmere    | 1         | 1.69%   |
| Steamroller | 1         | 1.69%   |
| Skylake     | 1         | 1.69%   |
| NetBurst    | 1         | 1.69%   |
| K10         | 1         | 1.69%   |
| Excavator   | 1         | 1.69%   |
| Broadwell   | 1         | 1.69%   |
| Bobcat      | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 50        | 76.92%  |
| AMD    | 9         | 13.85%  |
| Nvidia | 6         | 9.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 13.24%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 11.76%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 7.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 7.35%   |
| Intel HD Graphics 500                                                                    | 4         | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.41%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.47%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.47%   |
| Nvidia G98 [GeForce 9300 GS]                                                             | 1         | 1.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.47%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.47%   |
| Intel HD Graphics 615                                                                    | 1         | 1.47%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.47%   |
| Intel HD Graphics 530                                                                    | 1         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.47%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 1.47%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 1.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.47%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.47%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.47%   |
| AMD RV380 [Radeon X550/X600] (Secondary)                                                 | 1         | 1.47%   |
| AMD RV380 [Radeon X550/X600]                                                             | 1         | 1.47%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.47%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1         | 1.47%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.47%   |
| AMD Kaveri [Radeon R5 Graphics]                                                          | 1         | 1.47%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 74.58%  |
| 1 x AMD        | 5         | 8.47%   |
| 1 x Nvidia     | 3         | 5.08%   |
| Intel + Nvidia | 3         | 5.08%   |
| 2 x AMD        | 2         | 3.39%   |
| Intel + AMD    | 2         | 3.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 59        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 68.33%  |
| 0.01-0.5   | 9         | 15%     |
| 1.01-2.0   | 5         | 8.33%   |
| 0.51-1.0   | 4         | 6.67%   |
| 2.01-3.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 15%     |
| Samsung Electronics     | 8         | 13.33%  |
| BOE                     | 7         | 11.67%  |
| LG Display              | 4         | 6.67%   |
| Dell                    | 4         | 6.67%   |
| AU Optronics            | 4         | 6.67%   |
| Lenovo                  | 3         | 5%      |
| Chi Mei Optoelectronics | 3         | 5%      |
| Sharp                   | 2         | 3.33%   |
| LG Philips              | 2         | 3.33%   |
| Goldstar                | 2         | 3.33%   |
| Apple                   | 2         | 3.33%   |
| Toshiba                 | 1         | 1.67%   |
| Sony                    | 1         | 1.67%   |
| OUT                     | 1         | 1.67%   |
| Lite-On                 | 1         | 1.67%   |
| InnoLux Display         | 1         | 1.67%   |
| Hewlett-Packard         | 1         | 1.67%   |
| HannStar                | 1         | 1.67%   |
| Gateway                 | 1         | 1.67%   |
| BenQ                    | 1         | 1.67%   |
| Ancor Communications    | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 5%      |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 5%      |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 3.33%   |
| Toshiba TV TSB0106 1366x768                                           | 1         | 1.67%   |
| Sony TV SNY9C01 1920x1080                                             | 1         | 1.67%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 1.67%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch  | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                      | 1         | 1.67%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                        | 1         | 1.67%   |
| Lite-On R17AAC/S LTN023F 1280x1024 338x270mm 17.0-inch                | 1         | 1.67%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 1         | 1.67%   |
| LG Philips LCD Monitor LPL2D01 1920x1200 331x207mm 15.4-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD01F7 1366x768 293x165mm 13.2-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD01BC 1366x768 294x166mm 13.3-inch           | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4057 1280x800 331x207mm 15.4-inch               | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch              | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.67%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 1.67%   |
| Hewlett-Packard S2031 HWP2904 1600x900 443x249mm 20.0-inch            | 1         | 1.67%   |
| HannStar HSD116PHW2A HSD0450 1366x768 260x140mm 11.6-inch             | 1         | 1.67%   |
| Goldstar W1952 GSM4B77 1440x900 410x260mm 19.1-inch                   | 1         | 1.67%   |
| Goldstar E2260 GSM57DF 1920x1080 477x268mm 21.5-inch                  | 1         | 1.67%   |
| Gateway FPD1775W GWY06AF 1280x1024 373x209mm 16.8-inch                | 1         | 1.67%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 1         | 1.67%   |
| Dell P2418HZm DELD0C4 1920x1080 527x296mm 23.8-inch                   | 1         | 1.67%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                     | 1         | 1.67%   |
| Dell 2407WFP DELA016 1920x1200 519x324mm 24.1-inch                    | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch       | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 24        | 40%     |
| 1920x1080 (FHD)    | 14        | 23.33%  |
| 1920x1200 (WUXGA)  | 4         | 6.67%   |
| 1280x800 (WXGA)    | 4         | 6.67%   |
| 2560x1600          | 2         | 3.33%   |
| 1680x1050 (WSXGA+) | 2         | 3.33%   |
| 1440x900 (WXGA+)   | 2         | 3.33%   |
| 1280x1024 (SXGA)   | 2         | 3.33%   |
| 2736x1824          | 1         | 1.67%   |
| 2400x1600          | 1         | 1.67%   |
| 1920x540           | 1         | 1.67%   |
| 1920x1280          | 1         | 1.67%   |
| 1600x900 (HD+)     | 1         | 1.67%   |
| 1360x768           | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 15        | 25%     |
| 13     | 11        | 18.33%  |
| 11     | 7         | 11.67%  |
| 14     | 5         | 8.33%   |
| 24     | 3         | 5%      |
| 12     | 3         | 5%      |
| 27     | 2         | 3.33%   |
| 23     | 2         | 3.33%   |
| 17     | 2         | 3.33%   |
| 16     | 2         | 3.33%   |
| 72     | 1         | 1.67%   |
| 47     | 1         | 1.67%   |
| 31     | 1         | 1.67%   |
| 29     | 1         | 1.67%   |
| 22     | 1         | 1.67%   |
| 21     | 1         | 1.67%   |
| 20     | 1         | 1.67%   |
| 19     | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 46.67%  |
| 201-300     | 15        | 25%     |
| 501-600     | 7         | 11.67%  |
| 401-500     | 4         | 6.67%   |
| 601-700     | 2         | 3.33%   |
| 351-400     | 2         | 3.33%   |
| 1501-2000   | 1         | 1.67%   |
| 1001-1500   | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 69.64%  |
| 16/10 | 12        | 21.43%  |
| 3/2   | 3         | 5.36%   |
| 5/4   | 1         | 1.79%   |
| 4/3   | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 25%     |
| 81-90          | 11        | 18.33%  |
| 51-60          | 7         | 11.67%  |
| 71-80          | 5         | 8.33%   |
| 201-250        | 5         | 8.33%   |
| 61-70          | 3         | 5%      |
| 351-500        | 2         | 3.33%   |
| 301-350        | 2         | 3.33%   |
| 251-300        | 2         | 3.33%   |
| 151-200        | 2         | 3.33%   |
| 131-140        | 2         | 3.33%   |
| More than 1000 | 1         | 1.67%   |
| 141-150        | 1         | 1.67%   |
| 121-130        | 1         | 1.67%   |
| 501-1000       | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 21        | 35%     |
| 51-100        | 16        | 26.67%  |
| 121-160       | 15        | 25%     |
| 161-240       | 4         | 6.67%   |
| 1-50          | 3         | 5%      |
| More than 240 | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 86.67%  |
| 2     | 5         | 8.33%   |
| 0     | 3         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 28        | 33.73%  |
| Intel                             | 22        | 26.51%  |
| Qualcomm Atheros                  | 13        | 15.66%  |
| Broadcom                          | 5         | 6.02%   |
| TP-Link                           | 3         | 3.61%   |
| Ralink Technology                 | 3         | 3.61%   |
| Marvell Technology Group          | 3         | 3.61%   |
| Broadcom Limited                  | 3         | 3.61%   |
| Nvidia                            | 1         | 1.2%    |
| Ericsson Business Mobile Networks | 1         | 1.2%    |
| Dell                              | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 15        | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 4.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 4.12%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 4.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 3.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.09%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 3.09%   |
| Intel Wireless 7260                                                     | 3         | 3.09%   |
| Intel WiFi Link 5100                                                    | 3         | 3.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 2.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.06%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 2.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 2.06%   |
| Intel Wireless 7265                                                     | 2         | 2.06%   |
| Intel Wireless 3165                                                     | 2         | 2.06%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.06%   |
| TP-Link USB 10/100 LAN                                                  | 1         | 1.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.03%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.03%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 1         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.03%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.03%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 1         | 1.03%   |
| Intel 82567LF Gigabit Network Connection                                | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 39.22%  |
| Realtek Semiconductor | 11        | 21.57%  |
| Qualcomm Atheros      | 10        | 19.61%  |
| Broadcom              | 4         | 7.84%   |
| Ralink Technology     | 3         | 5.88%   |
| TP-Link               | 2         | 3.92%   |
| Broadcom Limited      | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 7.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 7.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 5.66%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 5.66%   |
| Intel Wireless 7260                                                     | 3         | 5.66%   |
| Intel WiFi Link 5100                                                    | 3         | 5.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 3.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 3.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.77%   |
| Intel Wireless 7265                                                     | 2         | 3.77%   |
| Intel Wireless 3165                                                     | 2         | 3.77%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 3.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.89%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.89%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.89%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 1         | 1.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 51.22%  |
| Intel                    | 9         | 21.95%  |
| Qualcomm Atheros         | 3         | 7.32%   |
| Marvell Technology Group | 3         | 7.32%   |
| Broadcom Limited         | 2         | 4.88%   |
| TP-Link                  | 1         | 2.44%   |
| Nvidia                   | 1         | 2.44%   |
| Broadcom                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 9.52%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 9.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 7.14%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.76%   |
| TP-Link USB 10/100 LAN                                                 | 1         | 2.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 2.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 2.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 2.38%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 2.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 2.38%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 2.38%   |
| Intel 82567LF Gigabit Network Connection                               | 1         | 2.38%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 2.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 2.38%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 2.38%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 53.41%  |
| Ethernet | 39        | 44.32%  |
| Modem    | 2         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 71.67%  |
| Ethernet | 17        | 28.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 50.85%  |
| 1     | 21        | 35.59%  |
| 0     | 8         | 13.56%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 27.27%  |
| Qualcomm Atheros Communications | 4         | 12.12%  |
| Cambridge Silicon Radio         | 4         | 12.12%  |
| Broadcom                        | 4         | 12.12%  |
| Hewlett-Packard                 | 3         | 9.09%   |
| Realtek Semiconductor           | 2         | 6.06%   |
| IMC Networks                    | 2         | 6.06%   |
| Foxconn / Hon Hai               | 2         | 6.06%   |
| Toshiba                         | 1         | 3.03%   |
| Lite-On Technology              | 1         | 3.03%   |
| Apple                           | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 21.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 12.12%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 4         | 12.12%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.06%   |
| IMC Networks Bluetooth Device                       | 2         | 6.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 6.06%   |
| Toshiba Askey for                                   | 1         | 3.03%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.03%   |
| Realtek Bluetooth Radio                             | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.03%   |
| Intel AX200 Bluetooth                               | 1         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.03%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 3.03%   |
| Apple Bluetooth Host Controller                     | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 48        | 82.76%  |
| AMD                    | 6         | 10.34%  |
| Nvidia                 | 3         | 5.17%   |
| Generalplus Technology | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 18.46%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 7.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 6.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 6.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 4.62%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 3.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 3.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 3.08%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.54%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 1.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.54%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 1.54%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.54%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.54%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 1.54%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.54%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Micron Technology   | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1         | 33.33%  |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s | 1         | 33.33%  |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 1         | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 2         | 66.67%  |
| DDR3 | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 1         | 33.33%  |
| 8192  | 1         | 33.33%  |
| 2048  | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 1         | 33.33%  |
| 2667  | 1         | 33.33%  |
| 1600  | 1         | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3150 Series | 1         | 50%     |
| HP LaserJet 1012         | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson GT-9700F [Perfection 2450 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Alcor Micro                            | 6         | 17.14%  |
| Suyin                                  | 4         | 11.43%  |
| Realtek Semiconductor                  | 4         | 11.43%  |
| Chicony Electronics                    | 4         | 11.43%  |
| Lenovo                                 | 3         | 8.57%   |
| Ricoh                                  | 2         | 5.71%   |
| Microdia                               | 2         | 5.71%   |
| Lite-On Technology                     | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Sunplus Innovation Technology          | 1         | 2.86%   |
| Importek                               | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |
| Bison Electronics                      | 1         | 2.86%   |
| ARC International                      | 1         | 2.86%   |
| Acer                                   | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                              | 6         | 17.14%  |
| Lenovo UVC Camera                                       | 3         | 8.57%   |
| Ricoh Integrated Webcam                                 | 2         | 5.71%   |
| Lite-On Integrated Camera                               | 2         | 5.71%   |
| Suyin VGA Webcam                                        | 1         | 2.86%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 2.86%   |
| Suyin HP Truevision HD                                  | 1         | 2.86%   |
| Suyin HD Video WebCam                                   | 1         | 2.86%   |
| Sunplus HD WebCam                                       | 1         | 2.86%   |
| Realtek WebCamera                                       | 1         | 2.86%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 2.86%   |
| Realtek Acer 640 x 480 laptop camera                    | 1         | 2.86%   |
| Realtek 2SF022                                          | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                           | 1         | 2.86%   |
| Microdia HP Webcam                                      | 1         | 2.86%   |
| Importek HP Webcam                                      | 1         | 2.86%   |
| IMC Networks Lenovo EasyCamera                          | 1         | 2.86%   |
| Chicony USB 2.0 Camera                                  | 1         | 2.86%   |
| Chicony TOSHIBA Web Camera - HD                         | 1         | 2.86%   |
| Chicony Integrated Camera                               | 1         | 2.86%   |
| Chicony HD WebCam                                       | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 2.86%   |
| Bison VGA WebCam                                        | 1         | 2.86%   |
| ARC International Camera                                | 1         | 2.86%   |
| Acer EasyCamera                                         | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 3         | 60%     |
| Validity Sensors | 2         | 40%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AuthenTec AES2810                          | 3         | 60%     |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 20%     |
| Validity Sensors Fingerprint scanner       | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 58.33%  |
| 1     | 19        | 31.67%  |
| 2     | 6         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 6         | 20%     |
| Graphics card            | 6         | 20%     |
| Net/wireless             | 5         | 16.67%  |
| Fingerprint reader       | 5         | 16.67%  |
| Chipcard                 | 3         | 10%     |
| Storage                  | 2         | 6.67%   |
| Storage/ide              | 1         | 3.33%   |
| Modem                    | 1         | 3.33%   |
| Communication controller | 1         | 3.33%   |


Lilidog - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lilidog.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lilidog/Desktop/README.md) and [notebooks](/Dist/Lilidog/Notebook/README.md).

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

Total: 81

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 11 x360 PC         | Notebook    | [1d8dbbd8af](https://linux-hardware.org/?probe=1d8dbbd8af) | Jan 29, 2024 |
| Acer          | Aspire E1-470               | Notebook    | [732a523ea8](https://linux-hardware.org/?probe=732a523ea8) | Jan 28, 2024 |
| ASUSTek       | X550VC                      | Notebook    | [90ebdf4197](https://linux-hardware.org/?probe=90ebdf4197) | Jan 22, 2024 |
| HP            | ProBook 6560b               | Notebook    | [6d2bbcc556](https://linux-hardware.org/?probe=6d2bbcc556) | Jan 21, 2024 |
| HP            | 1998                        | Desktop     | [b193235ba4](https://linux-hardware.org/?probe=b193235ba4) | Jan 17, 2024 |
| Lenovo        | ThinkPad T430s 2356GUU      | Notebook    | [df4e542b16](https://linux-hardware.org/?probe=df4e542b16) | Jan 15, 2024 |
| PC Special... | P65_67RSRP                  | Notebook    | [f2af84bdfc](https://linux-hardware.org/?probe=f2af84bdfc) | Jan 13, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [6d15625c9b](https://linux-hardware.org/?probe=6d15625c9b) | Jan 05, 2024 |
| Lenovo        | ThinkPad X280 20KES63G00    | Notebook    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Toshiba       | Satellite Pro L450          | Notebook    | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Acer          | AOD270                      | Notebook    | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Sony          | VPCF23P1E                   | Notebook    | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| Google        | Sand                        | Notebook    | [97e4755fe5](https://linux-hardware.org/?probe=97e4755fe5) | Nov 07, 2023 |
| Dell          | Inspiron 1318               | Notebook    | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [5dab721f9a](https://linux-hardware.org/?probe=5dab721f9a) | Aug 21, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | Notebook    | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | Notebook    | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | Notebook    | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | Notebook    | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [bd50784a0b](https://linux-hardware.org/?probe=bd50784a0b) | May 05, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4d91f9900d](https://linux-hardware.org/?probe=4d91f9900d) | Apr 25, 2023 |
| Dell          | 0GM819                      | Desktop     | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Google        | Sand                        | Notebook    | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| HP            | 805B                        | Desktop     | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [b74e119c7e](https://linux-hardware.org/?probe=b74e119c7e) | Nov 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar       | A320MH                      | Desktop     | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | Notebook    | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [209e0387a9](https://linux-hardware.org/?probe=209e0387a9) | Aug 27, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [5bfd5ddd59](https://linux-hardware.org/?probe=5bfd5ddd59) | Aug 26, 2022 |
| HP            | 805B                        | Desktop     | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b7173a46ac](https://linux-hardware.org/?probe=b7173a46ac) | Aug 21, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c9be76cad8](https://linux-hardware.org/?probe=c9be76cad8) | Aug 21, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [de75a91d9f](https://linux-hardware.org/?probe=de75a91d9f) | Jul 09, 2022 |
| Acer          | V5-131                      | Notebook    | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | Notebook    | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | Notebook    | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Acer          | AOD255E                     | Notebook    | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| eMachines     | EL1352                      | Desktop     | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP            | 212B                        | Desktop     | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| HP            | 21EF                        | Desktop     | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0HJ054                      | Desktop     | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Lilidog 22 | 40        | 58.82%  |
| Lilidog 23 | 28        | 41.18%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.5.0-0.deb12.4-amd64     | 8         | 10.67%  |
| 5.10.0-16-amd64           | 6         | 8%      |
| 6.1.0-9-amd64             | 5         | 6.67%   |
| 5.10.0-18-amd64           | 5         | 6.67%   |
| 5.10.0-15-amd64           | 5         | 6.67%   |
| 6.1.0-10-amd64            | 4         | 5.33%   |
| 5.10.0-13-amd64           | 4         | 5.33%   |
| 5.10.0-21-amd64           | 3         | 4%      |
| 5.10.0-20-amd64           | 3         | 4%      |
| 6.5.0-0.deb12.1-amd64     | 2         | 2.67%   |
| 6.1.0-7-amd64             | 2         | 2.67%   |
| 6.1.0-16-amd64            | 2         | 2.67%   |
| 6.1.0-11-amd64            | 2         | 2.67%   |
| 6.0.8-x64v1-xanmod1       | 2         | 2.67%   |
| 5.10.0-14-amd64           | 2         | 2.67%   |
| 6.4.5-1-liquorix-amd64    | 1         | 1.33%   |
| 6.4.0-0.deb12.2-amd64     | 1         | 1.33%   |
| 6.2.12-x64v1-xanmod1      | 1         | 1.33%   |
| 6.2.11-x64v1-xanmod1      | 1         | 1.33%   |
| 6.1.0-7.2-liquorix-amd64  | 1         | 1.33%   |
| 6.1.0-13-amd64            | 1         | 1.33%   |
| 6.1.0-13-686-pae          | 1         | 1.33%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 1.33%   |
| 6.0.10-x64v1-xanmod1      | 1         | 1.33%   |
| 6.0.0-5-amd64             | 1         | 1.33%   |
| 6.0.0-2-amd64             | 1         | 1.33%   |
| 6.0.0-0.deb11.6-amd64     | 1         | 1.33%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 1.33%   |
| 5.19.0-7.1-liquorix-amd64 | 1         | 1.33%   |
| 5.19.0-0.deb11.2-amd64    | 1         | 1.33%   |
| 5.18.0-1-amd64            | 1         | 1.33%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 1.33%   |
| 5.10.0-22-amd64           | 1         | 1.33%   |
| 5.10.0-19-amd64           | 1         | 1.33%   |
| 5.10.0-17-amd64           | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 40.28%  |
| 6.1.0   | 18        | 25%     |
| 6.5.0   | 10        | 13.89%  |
| 6.0.0   | 4         | 5.56%   |
| 6.0.8   | 2         | 2.78%   |
| 5.19.0  | 2         | 2.78%   |
| 6.4.5   | 1         | 1.39%   |
| 6.4.0   | 1         | 1.39%   |
| 6.2.12  | 1         | 1.39%   |
| 6.2.11  | 1         | 1.39%   |
| 6.0.10  | 1         | 1.39%   |
| 5.18.0  | 1         | 1.39%   |
| 5.17.0  | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 29        | 40.28%  |
| 6.1     | 18        | 25%     |
| 6.5     | 10        | 13.89%  |
| 6.0     | 7         | 9.72%   |
| 6.4     | 2         | 2.78%   |
| 6.2     | 2         | 2.78%   |
| 5.19    | 2         | 2.78%   |
| 5.18    | 1         | 1.39%   |
| 5.17    | 1         | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 98.48%  |
| i686   | 1         | 1.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 56        | 81.16%  |
| openbox          | 13        | 18.84%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 66        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 66        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 45        | 67.16%  |
| en_GB | 4         | 5.97%   |
| de_DE | 4         | 5.97%   |
| pl_PL | 2         | 2.99%   |
| es_MX | 2         | 2.99%   |
| es_ES | 2         | 2.99%   |
| es_CO | 2         | 2.99%   |
| ru_RU | 1         | 1.49%   |
| pt_BR | 1         | 1.49%   |
| it_IT | 1         | 1.49%   |
| es_CL | 1         | 1.49%   |
| en_IE | 1         | 1.49%   |
| cs_CZ | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 54.55%  |
| BIOS | 30        | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 47        | 69.12%  |
| Overlay | 17        | 25%     |
| Btrfs   | 4         | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 42        | 62.69%  |
| MBR  | 25        | 37.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 64.71%  |
| Yes       | 24        | 35.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 81.82%  |
| Yes       | 12        | 18.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 16.67%  |
| Hewlett-Packard     | 9         | 13.64%  |
| Lenovo              | 8         | 12.12%  |
| Acer                | 8         | 12.12%  |
| Apple               | 6         | 9.09%   |
| ASUSTek Computer    | 4         | 6.06%   |
| Gigabyte Technology | 3         | 4.55%   |
| Panasonic           | 2         | 3.03%   |
| Google              | 2         | 3.03%   |
| TUXEDO              | 1         | 1.52%   |
| Toshiba             | 1         | 1.52%   |
| Sony                | 1         | 1.52%   |
| PC Specialist       | 1         | 1.52%   |
| Inventec            | 1         | 1.52%   |
| Intel               | 1         | 1.52%   |
| GPU Company         | 1         | 1.52%   |
| Foxconn             | 1         | 1.52%   |
| Fanless Mini PC     | 1         | 1.52%   |
| eMachines           | 1         | 1.52%   |
| Biostar             | 1         | 1.52%   |
| BANGHO              | 1         | 1.52%   |
| Unknown             | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 3.03%   |
| TUXEDO N8xEJEK                             | 1         | 1.52%   |
| Toshiba Satellite Pro L450                 | 1         | 1.52%   |
| Sony VPCF23P1E                             | 1         | 1.52%   |
| PC Specialist P65_67RSRP                   | 1         | 1.52%   |
| Panasonic CFMX4-1                          | 1         | 1.52%   |
| Panasonic CF-31ATXAX1M                     | 1         | 1.52%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 1.52%   |
| Lenovo ThinkPad X280 20KES63G00            | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 1.52%   |
| Lenovo ThinkPad T430s 2356GUU              | 1         | 1.52%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 1.52%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1         | 1.52%   |
| Lenovo G500 20236                          | 1         | 1.52%   |
| Inventec Dell Thin Client Desktop 5060     | 1         | 1.52%   |
| Intel NUC11BTMi7                           | 1         | 1.52%   |
| HP t520 Flexible Series TC                 | 1         | 1.52%   |
| HP ProBook 6560b                           | 1         | 1.52%   |
| HP Pavilion 11 x360 PC                     | 1         | 1.52%   |
| HP Laptop 15s-fq1xxx                       | 1         | 1.52%   |
| HP G62                                     | 1         | 1.52%   |
| HP EliteDesk 800 G1 SFF                    | 1         | 1.52%   |
| HP EliteDesk 705 G2 MINI                   | 1         | 1.52%   |
| HP All-in-One Desktop 27-cb1xxx            | 1         | 1.52%   |
| HP 435                                     | 1         | 1.52%   |
| GPU Company GWNR71517                      | 1         | 1.52%   |
| Google Sand                                | 1         | 1.52%   |
| Google Auron_Yuna                          | 1         | 1.52%   |
| Gigabyte PERSONAL COMPUTER                 | 1         | 1.52%   |
| Gigabyte B450 AORUS PRO                    | 1         | 1.52%   |
| Gigabyte B365M DS3H                        | 1         | 1.52%   |
| Foxconn NETBOX NT-425/525                  | 1         | 1.52%   |
| Fanless Mini PC Quieter 3                  | 1         | 1.52%   |
| eMachines EL1352                           | 1         | 1.52%   |
| Dell XPS 8930                              | 1         | 1.52%   |
| Dell OptiPlex 780                          | 1         | 1.52%   |
| Dell OptiPlex 755                          | 1         | 1.52%   |
| Dell OptiPlex 390                          | 1         | 1.52%   |
| Dell OptiPlex 3020                         | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 5         | 7.58%   |
| Dell OptiPlex           | 4         | 6.06%   |
| Acer Aspire             | 4         | 6.06%   |
| Dell Latitude           | 3         | 4.55%   |
| HP EliteDesk            | 2         | 3.03%   |
| Dell Inspiron           | 2         | 3.03%   |
| Acer AOD255E            | 2         | 3.03%   |
| TUXEDO N8xEJEK          | 1         | 1.52%   |
| Toshiba Satellite       | 1         | 1.52%   |
| Sony VPCF23P1E          | 1         | 1.52%   |
| PC Specialist P65       | 1         | 1.52%   |
| Panasonic CFMX4-1       | 1         | 1.52%   |
| Panasonic CF-31ATXAX1M  | 1         | 1.52%   |
| Lenovo Yoga             | 1         | 1.52%   |
| Lenovo Legion           | 1         | 1.52%   |
| Lenovo G500             | 1         | 1.52%   |
| Inventec Dell           | 1         | 1.52%   |
| Intel NUC11BTMi7        | 1         | 1.52%   |
| HP t520                 | 1         | 1.52%   |
| HP ProBook              | 1         | 1.52%   |
| HP Pavilion             | 1         | 1.52%   |
| HP Laptop               | 1         | 1.52%   |
| HP G62                  | 1         | 1.52%   |
| HP All-in-One           | 1         | 1.52%   |
| HP 435                  | 1         | 1.52%   |
| GPU Company GWNR71517   | 1         | 1.52%   |
| Google Sand             | 1         | 1.52%   |
| Google Auron            | 1         | 1.52%   |
| Gigabyte PERSONAL       | 1         | 1.52%   |
| Gigabyte B450           | 1         | 1.52%   |
| Gigabyte B365M          | 1         | 1.52%   |
| Foxconn NETBOX          | 1         | 1.52%   |
| Fanless Mini PC Quieter | 1         | 1.52%   |
| eMachines EL1352        | 1         | 1.52%   |
| Dell XPS                | 1         | 1.52%   |
| Dell DM051              | 1         | 1.52%   |
| Biostar A320MH          | 1         | 1.52%   |
| BANGHO Suma             | 1         | 1.52%   |
| ASUS X550VC             | 1         | 1.52%   |
| ASUS VivoBook           | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 10        | 15.15%  |
| 2018 | 8         | 12.12%  |
| 2019 | 5         | 7.58%   |
| 2014 | 5         | 7.58%   |
| 2013 | 5         | 7.58%   |
| 2011 | 5         | 7.58%   |
| 2021 | 4         | 6.06%   |
| 2012 | 4         | 6.06%   |
| 2022 | 3         | 4.55%   |
| 2017 | 3         | 4.55%   |
| 2008 | 3         | 4.55%   |
| 2020 | 2         | 3.03%   |
| 2016 | 2         | 3.03%   |
| 2015 | 2         | 3.03%   |
| 2009 | 2         | 3.03%   |
| 2007 | 2         | 3.03%   |
| 2006 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 38        | 57.58%  |
| Desktop    | 19        | 28.79%  |
| Mini pc    | 5         | 7.58%   |
| All in one | 3         | 4.55%   |
| Tablet     | 1         | 1.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 64        | 96.97%  |
| Enabled  | 2         | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 95.45%  |
| Yes  | 3         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 23        | 34.85%  |
| 3.01-4.0   | 15        | 22.73%  |
| 16.01-24.0 | 11        | 16.67%  |
| 8.01-16.0  | 5         | 7.58%   |
| 1.01-2.0   | 4         | 6.06%   |
| 32.01-64.0 | 3         | 4.55%   |
| 2.01-3.0   | 3         | 4.55%   |
| 0.51-1.0   | 2         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 44        | 64.71%  |
| 1.01-2.0  | 16        | 23.53%  |
| 2.01-3.0  | 5         | 7.35%   |
| 0.01-0.5  | 2         | 2.94%   |
| 8.01-16.0 | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 70.15%  |
| 2      | 15        | 22.39%  |
| 3      | 3         | 4.48%   |
| 4      | 2         | 2.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 62.69%  |
| Yes       | 25        | 37.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 89.55%  |
| No        | 7         | 10.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 81.82%  |
| No        | 12        | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 55.22%  |
| No        | 30        | 44.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 30.3%   |
| Germany     | 8         | 12.12%  |
| UK          | 5         | 7.58%   |
| Spain       | 3         | 4.55%   |
| Poland      | 3         | 4.55%   |
| Netherlands | 3         | 4.55%   |
| Italy       | 3         | 4.55%   |
| Mexico      | 2         | 3.03%   |
| Colombia    | 2         | 3.03%   |
| Argentina   | 2         | 3.03%   |
| Vietnam     | 1         | 1.52%   |
| Thailand    | 1         | 1.52%   |
| Taiwan      | 1         | 1.52%   |
| Russia      | 1         | 1.52%   |
| Romania     | 1         | 1.52%   |
| Portugal    | 1         | 1.52%   |
| Kenya       | 1         | 1.52%   |
| Indonesia   | 1         | 1.52%   |
| Finland     | 1         | 1.52%   |
| Czechia     | 1         | 1.52%   |
| Chile       | 1         | 1.52%   |
| Canada      | 1         | 1.52%   |
| Brazil      | 1         | 1.52%   |
| Belgium     | 1         | 1.52%   |
| Austria     | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 7.35%   |
| Fayetteville                | 5         | 7.35%   |
| Charlotte                   | 3         | 4.41%   |
| Milan                       | 2         | 2.94%   |
| Medellín                   | 2         | 2.94%   |
| Egan                        | 2         | 2.94%   |
| Denver                      | 2         | 2.94%   |
| Zduny                       | 1         | 1.47%   |
| Zapopan                     | 1         | 1.47%   |
| Workum                      | 1         | 1.47%   |
| Viña del Mar               | 1         | 1.47%   |
| Vienna                      | 1         | 1.47%   |
| Uelzen                      | 1         | 1.47%   |
| Stockton-on-Tees            | 1         | 1.47%   |
| Stockport                   | 1         | 1.47%   |
| St Petersburg               | 1         | 1.47%   |
| Schiedam                    | 1         | 1.47%   |
| San Nicolás de los Arroyos | 1         | 1.47%   |
| Rzeszów                    | 1         | 1.47%   |
| Rumia                       | 1         | 1.47%   |
| Rome                        | 1         | 1.47%   |
| Rio Ceballos                | 1         | 1.47%   |
| Rinteln                     | 1         | 1.47%   |
| Ratchathewi                 | 1         | 1.47%   |
| Poricany                    | 1         | 1.47%   |
| Palembang                   | 1         | 1.47%   |
| Norderstedt                 | 1         | 1.47%   |
| Nairobi                     | 1         | 1.47%   |
| Morgantown                  | 1         | 1.47%   |
| Monclova                    | 1         | 1.47%   |
| Memphis                     | 1         | 1.47%   |
| Madrid                      | 1         | 1.47%   |
| Lisbon                      | 1         | 1.47%   |
| Leicester                   | 1         | 1.47%   |
| Langelsheim                 | 1         | 1.47%   |
| Idsegahuizum                | 1         | 1.47%   |
| Ho Chi Minh City            | 1         | 1.47%   |
| Helsinki                    | 1         | 1.47%   |
| Groningen                   | 1         | 1.47%   |
| Golden Valley               | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 21.84%  |
| WDC                 | 10        | 15     | 11.49%  |
| Samsung Electronics | 10        | 13     | 11.49%  |
| Kingston            | 7         | 8      | 8.05%   |
| SanDisk             | 5         | 7      | 5.75%   |
| Toshiba             | 4         | 5      | 4.6%    |
| Crucial             | 4         | 4      | 4.6%    |
| Intel               | 2         | 2      | 2.3%    |
| Hitachi             | 2         | 2      | 2.3%    |
| Apacer              | 2         | 2      | 2.3%    |
| A-DATA Technology   | 2         | 2      | 2.3%    |
| Wibtek              | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |
| SSK                 | 1         | 2      | 1.15%   |
| SK hynix            | 1         | 1      | 1.15%   |
| Silicon Motion      | 1         | 1      | 1.15%   |
| PNY                 | 1         | 1      | 1.15%   |
| OWC                 | 1         | 2      | 1.15%   |
| Mushkin             | 1         | 1      | 1.15%   |
| Micron Technology   | 1         | 2      | 1.15%   |
| Lexar               | 1         | 1      | 1.15%   |
| KIOXIA              | 1         | 1      | 1.15%   |
| KingSpec            | 1         | 1      | 1.15%   |
| KingFast            | 1         | 1      | 1.15%   |
| Integral            | 1         | 1      | 1.15%   |
| GOODRAM             | 1         | 1      | 1.15%   |
| China               | 1         | 1      | 1.15%   |
| Blackpcs            | 1         | 1      | 1.15%   |
| ASMedia             | 1         | 1      | 1.15%   |
| Apple               | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 2         | 2.22%   |
| Seagate ST31000528AS 1TB             | 2         | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2.22%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 2.22%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.22%   |
| Wibtek W800S 512GB SSD               | 1         | 1.11%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1.11%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 1.11%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 1.11%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.11%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 1.11%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.11%   |
| WDC WD10SPCX-60KHST0 1TB             | 1         | 1.11%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 1.11%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.11%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.11%   |
| Unknown NCard  32GB                  | 1         | 1.11%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.11%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.11%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.11%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.11%   |
| SSK Disk 240GB                       | 1         | 1.11%   |
| SK hynix C2S3T/480G 480GB SSD        | 1         | 1.11%   |
| Silicon Motion NE-128 128GB          | 1         | 1.11%   |
| Seagate ST9320325ASG 320GB           | 1         | 1.11%   |
| Seagate ST9320325AS 320GB            | 1         | 1.11%   |
| Seagate ST9250315AS 250GB            | 1         | 1.11%   |
| Seagate ST500VM000-1SD101 500GB      | 1         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.11%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1.11%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1.11%   |
| Seagate ST3160023AS 160GB            | 1         | 1.11%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.11%   |
| Seagate OneTouch HDD 1TB             | 1         | 1.11%   |
| Seagate Expansion 1TB                | 1         | 1.11%   |
| Seagate BUP Slim BK 1TB              | 1         | 1.11%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1         | 1.11%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 22     | 55.88%  |
| WDC     | 6         | 6      | 17.65%  |
| Toshiba | 4         | 5      | 11.76%  |
| Hitachi | 2         | 2      | 5.88%   |
| SSK     | 1         | 2      | 2.94%   |
| ASMedia | 1         | 1      | 2.94%   |
| Apple   | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 15.79%  |
| Kingston            | 6         | 7      | 15.79%  |
| SanDisk             | 4         | 4      | 10.53%  |
| Crucial             | 4         | 4      | 10.53%  |
| WDC                 | 2         | 3      | 5.26%   |
| Apacer              | 2         | 2      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| Wibtek              | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| OWC                 | 1         | 2      | 2.63%   |
| Mushkin             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 2      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| KingFast            | 1         | 1      | 2.63%   |
| Integral            | 1         | 1      | 2.63%   |
| GOODRAM             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| Blackpcs            | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 36        | 42     | 45%     |
| HDD  | 28        | 39     | 35%     |
| NVMe | 14        | 19     | 17.5%   |
| MMC  | 2         | 5      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 74     | 72.15%  |
| NVMe | 14        | 19     | 17.72%  |
| SAS  | 6         | 7      | 7.59%   |
| MMC  | 2         | 5      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 58     | 73.85%  |
| 0.51-1.0   | 14        | 19     | 21.54%  |
| 1.01-2.0   | 2         | 3      | 3.08%   |
| 4.01-10.0  | 1         | 1      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 28.99%  |
| 251-500    | 18        | 26.09%  |
| 1-20       | 16        | 23.19%  |
| 1001-2000  | 5         | 7.25%   |
| 51-100     | 5         | 7.25%   |
| 501-1000   | 3         | 4.35%   |
| 21-50      | 2         | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 57        | 83.82%  |
| 21-50     | 5         | 7.35%   |
| 101-250   | 3         | 4.41%   |
| 251-500   | 1         | 1.47%   |
| 1001-2000 | 1         | 1.47%   |
| 51-100    | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB    | 2         | 3      | 18.18%  |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 9.09%   |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 9.09%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 9.09%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 9.09%   |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 9.09%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 9.09%   |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 9.09%   |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 9.09%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 5      | 36.36%  |
| WDC      | 2         | 3      | 18.18%  |
| Toshiba  | 1         | 1      | 9.09%   |
| SanDisk  | 1         | 1      | 9.09%   |
| OWC      | 1         | 2      | 9.09%   |
| Mushkin  | 1         | 1      | 9.09%   |
| Kingston | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 54.55%  |
| SSD  | 5         | 7      | 45.45%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 54        | 77     | 72.97%  |
| Malfunc  | 11        | 14     | 14.86%  |
| Detected | 7         | 11     | 9.46%   |
| Failed   | 2         | 3      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 53        | 70.67%  |
| AMD                          | 8         | 10.67%  |
| Samsung Electronics          | 5         | 6.67%   |
| SanDisk                      | 3         | 4%      |
| Nvidia                       | 2         | 2.67%   |
| Silicon Motion               | 1         | 1.33%   |
| Shenzhen Longsys Electronics | 1         | 1.33%   |
| KIOXIA                       | 1         | 1.33%   |
| Kingston Technology Company  | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 6         | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 6         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 3         | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 3         | 3.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 3         | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 3         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 3         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 3         | 3.33%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                                          | 2         | 2.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 2         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 2         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 2         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 2         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 2         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 2.22%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 1         | 1.11%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 1.11%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 1         | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 1.11%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                                           | 1         | 1.11%   |
| Nvidia MCP61 SATA Controller                                                                                       | 1         | 1.11%   |
| Nvidia MCP61 IDE                                                                                                   | 1         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 1.11%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                                                 | 1         | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 1         | 1.11%   |
| Intel Tiger Lake SATA AHCI Controller                                                                              | 1         | 1.11%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 1         | 1.11%   |
| Intel SATA Controller [RAID Mode]                                                                                  | 1         | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 1         | 1.11%   |
| Intel NVMe Optane Memory Series                                                                                    | 1         | 1.11%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 1         | 1.11%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 1         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 1         | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 1         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 1         | 1.11%   |
| Intel Alder Lake-P SATA AHCI Controller                                                                            | 1         | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 64.63%  |
| NVMe | 14        | 17.07%  |
| IDE  | 11        | 13.41%  |
| RAID | 4         | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 56        | 84.85%  |
| AMD    | 10        | 15.15%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 3.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 3.03%   |
| Intel Celeron CPU N2807 @ 1.58GHz           | 2         | 3.03%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.03%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz          | 1         | 1.52%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1         | 1.52%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.52%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 1.52%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.52%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.52%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.52%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.52%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.52%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.52%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 1.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.52%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1         | 1.52%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 1.52%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1         | 1.52%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 1.52%   |
| Intel Celeron N5105 @ 2.00GHz               | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 21.21%  |
| Intel Core i7           | 9         | 13.64%  |
| Intel Core 2 Duo        | 7         | 10.61%  |
| Intel Celeron           | 7         | 10.61%  |
| Intel Atom              | 5         | 7.58%   |
| Other                   | 4         | 6.06%   |
| Intel Core i3           | 4         | 6.06%   |
| Intel Pentium           | 2         | 3.03%   |
| AMD Ryzen 5             | 2         | 3.03%   |
| AMD GX                  | 2         | 3.03%   |
| Intel Xeon              | 1         | 1.52%   |
| Intel Pentium Gold      | 1         | 1.52%   |
| Intel Pentium Dual-Core | 1         | 1.52%   |
| Intel Pentium D         | 1         | 1.52%   |
| AMD Ryzen 7             | 1         | 1.52%   |
| AMD PRO A10             | 1         | 1.52%   |
| AMD Phenom II           | 1         | 1.52%   |
| AMD Athlon II Dual-Core | 1         | 1.52%   |
| AMD Athlon II           | 1         | 1.52%   |
| AMD A12                 | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 56.06%  |
| 4      | 17        | 25.76%  |
| 6      | 4         | 6.06%   |
| 1      | 4         | 6.06%   |
| 8      | 2         | 3.03%   |
| 10     | 1         | 1.52%   |
| 3      | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 56.06%  |
| 1      | 29        | 43.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 98.48%  |
| 32-bit         | 1         | 1.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 23.19%  |
| 0x306a9    | 4         | 5.8%    |
| 0x1067a    | 4         | 5.8%    |
| 0x206a7    | 3         | 4.35%   |
| 0x106ca    | 3         | 4.35%   |
| 0x906ea    | 2         | 2.9%    |
| 0x806ea    | 2         | 2.9%    |
| 0x406e3    | 2         | 2.9%    |
| 0x40651    | 2         | 2.9%    |
| 0x306d4    | 2         | 2.9%    |
| 0x30678    | 2         | 2.9%    |
| 0x20655    | 2         | 2.9%    |
| 0x0600611a | 2         | 2.9%    |
| 0x010000c8 | 2         | 2.9%    |
| 0xf44      | 1         | 1.45%   |
| 0xa0671    | 1         | 1.45%   |
| 0xa0653    | 1         | 1.45%   |
| 0x906ed    | 1         | 1.45%   |
| 0x906e9    | 1         | 1.45%   |
| 0x906c0    | 1         | 1.45%   |
| 0x906a4    | 1         | 1.45%   |
| 0x806d1    | 1         | 1.45%   |
| 0x806c1    | 1         | 1.45%   |
| 0x706e5    | 1         | 1.45%   |
| 0x6fa      | 1         | 1.45%   |
| 0x506c9    | 1         | 1.45%   |
| 0x306c3    | 1         | 1.45%   |
| 0x206d7    | 1         | 1.45%   |
| 0x106c2    | 1         | 1.45%   |
| 0x10676    | 1         | 1.45%   |
| 0x08600106 | 1         | 1.45%   |
| 0x08108109 | 1         | 1.45%   |
| 0x0810100b | 1         | 1.45%   |
| 0x07030105 | 1         | 1.45%   |
| 0x07030104 | 1         | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 10.45%  |
| Penryn      | 6         | 8.96%   |
| IvyBridge   | 6         | 8.96%   |
| SandyBridge | 5         | 7.46%   |
| Bonnell     | 5         | 7.46%   |
| IceLake     | 4         | 5.97%   |
| Haswell     | 4         | 5.97%   |
| Westmere    | 3         | 4.48%   |
| Skylake     | 3         | 4.48%   |
| Silvermont  | 3         | 4.48%   |
| K10         | 3         | 4.48%   |
| Puma        | 2         | 2.99%   |
| Excavator   | 2         | 2.99%   |
| Core        | 2         | 2.99%   |
| Broadwell   | 2         | 2.99%   |
| Unknown     | 2         | 2.99%   |
| Zen+        | 1         | 1.49%   |
| Zen 2       | 1         | 1.49%   |
| Zen         | 1         | 1.49%   |
| Tremont     | 1         | 1.49%   |
| TigerLake   | 1         | 1.49%   |
| NetBurst    | 1         | 1.49%   |
| Goldmont    | 1         | 1.49%   |
| CometLake   | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 62.67%  |
| AMD    | 16        | 21.33%  |
| Nvidia | 12        | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 7.59%   |
| Intel UHD Graphics 620                                                        | 3         | 3.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 3.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 3.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 2.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.53%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2         | 2.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1         | 1.27%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.27%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 1.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.27%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 1.27%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                             | 1         | 1.27%   |
| Nvidia GA102 [GeForce RTX 3080]                                               | 1         | 1.27%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 1.27%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.27%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.27%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.27%   |
| Intel HD Graphics 630                                                         | 1         | 1.27%   |
| Intel HD Graphics 5500                                                        | 1         | 1.27%   |
| Intel HD Graphics                                                             | 1         | 1.27%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                      | 1         | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1         | 1.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.27%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.27%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 52.24%  |
| 1 x AMD        | 12        | 17.91%  |
| 1 x Nvidia     | 8         | 11.94%  |
| 2 x Intel      | 4         | 5.97%   |
| Intel + Nvidia | 4         | 5.97%   |
| Intel + AMD    | 3         | 4.48%   |
| 2 x AMD        | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 94.03%  |
| Unknown     | 3         | 4.48%   |
| Proprietary | 1         | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 63.24%  |
| 0.01-0.5   | 13        | 19.12%  |
| 1.01-2.0   | 4         | 5.88%   |
| 3.01-4.0   | 3         | 4.41%   |
| 7.01-8.0   | 2         | 2.94%   |
| 0.51-1.0   | 2         | 2.94%   |
| 8.01-16.0  | 1         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 22.22%  |
| LG Display              | 7         | 11.11%  |
| Chimei Innolux          | 5         | 7.94%   |
| Samsung Electronics     | 4         | 6.35%   |
| Lenovo                  | 3         | 4.76%   |
| Dell                    | 3         | 4.76%   |
| Chi Mei Optoelectronics | 3         | 4.76%   |
| Zoran                   | 2         | 3.17%   |
| Sceptre Tech            | 2         | 3.17%   |
| Goldstar                | 2         | 3.17%   |
| BOE                     | 2         | 3.17%   |
| Apple                   | 2         | 3.17%   |
| Sony                    | 1         | 1.59%   |
| Sharp                   | 1         | 1.59%   |
| SAC                     | 1         | 1.59%   |
| Philips                 | 1         | 1.59%   |
| Packard Bell            | 1         | 1.59%   |
| JDI                     | 1         | 1.59%   |
| Insignia                | 1         | 1.59%   |
| InfoVision              | 1         | 1.59%   |
| HUAWEI                  | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| EQV                     | 1         | 1.59%   |
| eMachines               | 1         | 1.59%   |
| ASUSTek Computer        | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                        | 2         | 3.17%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch            | 2         | 3.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 3.17%   |
| Sony TV SNY0101 1360x768                                                  | 1         | 1.59%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch     | 1         | 1.59%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch         | 1         | 1.59%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch         | 1         | 1.59%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                     | 1         | 1.59%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                        | 1         | 1.59%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch          | 1         | 1.59%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.59%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                  | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                   | 1         | 1.59%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                      | 1         | 1.59%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                     | 1         | 1.59%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch                    | 1         | 1.59%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch               | 1         | 1.59%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                      | 1         | 1.59%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch              | 1         | 1.59%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch                  | 1         | 1.59%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                    | 1         | 1.59%   |
| EQV LCD Monitor EQV1080 1920x1080 477x268mm 21.5-inch                     | 1         | 1.59%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                     | 1         | 1.59%   |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                         | 1         | 1.59%   |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                         | 1         | 1.59%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 290x170mm 13.2-inch          | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 37.7%   |
| 1366x768 (WXGA)    | 16        | 26.23%  |
| 1360x768           | 4         | 6.56%   |
| 1024x600           | 4         | 6.56%   |
| 2560x1440 (QHD)    | 3         | 4.92%   |
| 1280x800 (WXGA)    | 3         | 4.92%   |
| 3840x2160 (4K)     | 2         | 3.28%   |
| 1600x900 (HD+)     | 2         | 3.28%   |
| 3440x1440          | 1         | 1.64%   |
| 1920x1200 (WUXGA)  | 1         | 1.64%   |
| 1680x1050 (WSXGA+) | 1         | 1.64%   |
| 1024x768 (XGA)     | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 22.22%  |
| 14      | 8         | 12.7%   |
| 24      | 6         | 9.52%   |
| 21      | 6         | 9.52%   |
| 10      | 5         | 7.94%   |
| 17      | 4         | 6.35%   |
| 22      | 3         | 4.76%   |
| 13      | 3         | 4.76%   |
| 31      | 2         | 3.17%   |
| 23      | 2         | 3.17%   |
| 12      | 2         | 3.17%   |
| 11      | 2         | 3.17%   |
| 84      | 1         | 1.59%   |
| 34      | 1         | 1.59%   |
| 32      | 1         | 1.59%   |
| 27      | 1         | 1.59%   |
| 16      | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 34.92%  |
| 201-300     | 11        | 17.46%  |
| 501-600     | 9         | 14.29%  |
| 401-500     | 9         | 14.29%  |
| 351-400     | 6         | 9.52%   |
| 701-800     | 2         | 3.17%   |
| 601-700     | 2         | 3.17%   |
| 1501-2000   | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 88.33%  |
| 16/10 | 5         | 8.33%   |
| 4/3   | 1         | 1.67%   |
| 21/9  | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 23.81%  |
| 101-110        | 14        | 22.22%  |
| 81-90          | 10        | 15.87%  |
| 41-50          | 5         | 7.94%   |
| 351-500        | 4         | 6.35%   |
| 121-130        | 4         | 6.35%   |
| 61-70          | 2         | 3.17%   |
| 51-60          | 2         | 3.17%   |
| 151-200        | 2         | 3.17%   |
| More than 1000 | 1         | 1.59%   |
| 71-80          | 1         | 1.59%   |
| 301-350        | 1         | 1.59%   |
| 111-120        | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 23        | 36.51%  |
| 51-100  | 18        | 28.57%  |
| 121-160 | 16        | 25.4%   |
| 161-240 | 4         | 6.35%   |
| 1-50    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 88.24%  |
| 2     | 4         | 5.88%   |
| 0     | 4         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 31        | 30.69%  |
| Intel                           | 26        | 25.74%  |
| Qualcomm Atheros                | 19        | 18.81%  |
| Broadcom                        | 13        | 12.87%  |
| Qualcomm Atheros Communications | 3         | 2.97%   |
| Marvell Technology Group        | 2         | 1.98%   |
| Research In Motion              | 1         | 0.99%   |
| Ralink Technology               | 1         | 0.99%   |
| Ralink                          | 1         | 0.99%   |
| Prolific Technology             | 1         | 0.99%   |
| Nvidia                          | 1         | 0.99%   |
| MediaTek                        | 1         | 0.99%   |
| ICS Advent                      | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 18        | 14.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 7         | 5.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 3.28%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 2.46%   |
| Intel Wireless 8260                                                                   | 3         | 2.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 1.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 1.64%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.64%   |
| Intel Wireless 7260                                                                   | 2         | 1.64%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 1.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.64%   |
| Research In Motion BlackBerry                                                         | 1         | 0.82%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.82%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 0.82%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 0.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.82%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.82%   |
| Prolific USB-Serial Controller                                                        | 1         | 0.82%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.82%   |
| MediaTek moto e22                                                                     | 1         | 0.82%   |
| Intel Wireless 7265                                                                   | 1         | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 1         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 31.58%  |
| Qualcomm Atheros                | 16        | 28.07%  |
| Realtek Semiconductor           | 10        | 17.54%  |
| Broadcom                        | 8         | 14.04%  |
| Qualcomm Atheros Communications | 3         | 5.26%   |
| Ralink Technology               | 1         | 1.75%   |
| Ralink                          | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 7.02%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 5.26%   |
| Intel Wireless 8260                                                                   | 3         | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 3.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 3.51%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 3.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 3.51%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 3.51%   |
| Intel Wireless 7260                                                                   | 2         | 3.51%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.75%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.75%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.75%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.75%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.75%   |
| Intel Wireless 7265                                                                   | 1         | 1.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.75%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.75%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 1.75%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 1.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 42.19%  |
| Intel                    | 17        | 26.56%  |
| Broadcom                 | 8         | 12.5%   |
| Qualcomm Atheros         | 6         | 9.38%   |
| Marvell Technology Group | 2         | 3.13%   |
| Research In Motion       | 1         | 1.56%   |
| Nvidia                   | 1         | 1.56%   |
| MediaTek                 | 1         | 1.56%   |
| ICS Advent               | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18        | 28.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 10.94%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 3.13%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 3.13%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 3.13%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 3.13%   |
| Research In Motion BlackBerry                                          | 1         | 1.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.56%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.56%   |
| MediaTek moto e22                                                      | 1         | 1.56%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1         | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.56%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.56%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.56%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 1.56%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 1.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.56%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 1.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.56%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 60        | 52.17%  |
| WiFi     | 54        | 46.96%  |
| Modem    | 1         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 52.11%  |
| Ethernet | 34        | 47.89%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 43        | 64.18%  |
| 1     | 22        | 32.84%  |
| 3     | 1         | 1.49%   |
| 0     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 61.19%  |
| Yes  | 26        | 38.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 35.14%  |
| Apple                           | 6         | 16.22%  |
| Qualcomm Atheros Communications | 4         | 10.81%  |
| Lite-On Technology              | 4         | 10.81%  |
| Realtek Semiconductor           | 3         | 8.11%   |
| IMC Networks                    | 3         | 8.11%   |
| Broadcom                        | 2         | 5.41%   |
| Ralink                          | 1         | 2.7%    |
| Hewlett-Packard                 | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 8         | 21.62%  |
| Intel AX201 Bluetooth                              | 3         | 8.11%   |
| Realtek Bluetooth Radio                            | 2         | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 5.41%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 5.41%   |
| Lite-On Atheros AR3012 Bluetooth                   | 2         | 5.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 2         | 5.41%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 2         | 5.41%   |
| Realtek RTL8723B Bluetooth                         | 1         | 2.7%    |
| Ralink RT3290 Bluetooth                            | 1         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 2.7%    |
| Lite-On Bluetooth USB Host Controller              | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                       | 1         | 2.7%    |
| IMC Networks Bluetooth Device                      | 1         | 2.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 1         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 2.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.7%    |
| Apple Bluetooth USB Host Controller                | 1         | 2.7%    |
| Apple Bluetooth Host Controller                    | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 65.06%  |
| AMD                   | 14        | 16.87%  |
| Nvidia                | 9         | 10.84%  |
| SAVITECH              | 1         | 1.2%    |
| Roland                | 1         | 1.2%    |
| Realtek Semiconductor | 1         | 1.2%    |
| JMTek                 | 1         | 1.2%    |
| Huawei Technologies   | 1         | 1.2%    |
| Anlya.cn              | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 7.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 4.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 3.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 3.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.04%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.04%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.04%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.04%   |
| SAVITECH USB HIFI Audio                                                    | 1         | 1.02%   |
| Roland QUAD-CAPTURE                                                        | 1         | 1.02%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.02%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.02%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.02%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.02%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.02%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 14        | 17.28%  |
| Unknown                      | 11        | 13.58%  |
| Samsung Electronics          | 8         | 9.88%   |
| Kingston                     | 8         | 9.88%   |
| Crucial                      | 8         | 9.88%   |
| Micron Technology            | 6         | 7.41%   |
| A-DATA Technology            | 5         | 6.17%   |
| Elpida                       | 4         | 4.94%   |
| Timetec                      | 3         | 3.7%    |
| Corsair                      | 3         | 3.7%    |
| Nanya Technology             | 2         | 2.47%   |
| Unknown (0xFFFF000000000000) | 1         | 1.23%   |
| Unknown (08C8)               | 1         | 1.23%   |
| Toshiba                      | 1         | 1.23%   |
| Team                         | 1         | 1.23%   |
| SK_Hynix                     | 1         | 1.23%   |
| Patriot                      | 1         | 1.23%   |
| Infineon                     | 1         | 1.23%   |
| G.Skill                      | 1         | 1.23%   |
| Unknown                      | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 2.33%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 2.33%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s         | 2         | 2.33%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 2.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 1.16%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.16%   |
| Unknown (0xFFFF000000000000) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 1.16%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s    | 1         | 1.16%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s           | 1         | 1.16%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s            | 1         | 1.16%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.16%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s             | 1         | 1.16%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.16%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s            | 1         | 1.16%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 1.16%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 1.16%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                 | 1         | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1         | 1.16%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s          | 1         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 1         | 1.16%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.16%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.16%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s          | 1         | 1.16%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s                 | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 49.21%  |
| DDR4   | 17        | 26.98%  |
| DDR2   | 9         | 14.29%  |
| LPDDR4 | 4         | 6.35%   |
| LPDDR3 | 1         | 1.59%   |
| DDR    | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 65.08%  |
| DIMM         | 16        | 25.4%   |
| Row Of Chips | 3         | 4.76%   |
| Unknown      | 2         | 3.17%   |
| Chip         | 1         | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 24        | 36.36%  |
| 8192  | 18        | 27.27%  |
| 2048  | 14        | 21.21%  |
| 1024  | 5         | 7.58%   |
| 16384 | 3         | 4.55%   |
| 32768 | 1         | 1.52%   |
| 512   | 1         | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 24.64%  |
| 667     | 8         | 11.59%  |
| 2667    | 6         | 8.7%    |
| 1067    | 5         | 7.25%   |
| 3200    | 4         | 5.8%    |
| 2400    | 4         | 5.8%    |
| 1333    | 3         | 4.35%   |
| 3733    | 2         | 2.9%    |
| 1800    | 2         | 2.9%    |
| 1334    | 2         | 2.9%    |
| 1066    | 2         | 2.9%    |
| 533     | 2         | 2.9%    |
| 8400    | 1         | 1.45%   |
| 4267    | 1         | 1.45%   |
| 4266    | 1         | 1.45%   |
| 3066    | 1         | 1.45%   |
| 2733    | 1         | 1.45%   |
| 2666    | 1         | 1.45%   |
| 2133    | 1         | 1.45%   |
| 1867    | 1         | 1.45%   |
| 1866    | 1         | 1.45%   |
| 975     | 1         | 1.45%   |
| 800     | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 50%     |
| HP DeskJet F4200 series               | 1         | 25%     |
| HP DeskJet 2130 series                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 33.33%  |
| Apple                                  | 4         | 11.11%  |
| Microdia                               | 3         | 8.33%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Realtek Semiconductor                  | 2         | 5.56%   |
| Logitech                               | 2         | 5.56%   |
| IMC Networks                           | 2         | 5.56%   |
| ALi                                    | 2         | 5.56%   |
| Acer                                   | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Ricoh                                  | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Luxvisions Innotech Limited            | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                              | 2         | 5.56%   |
| Chicony HD WebCam (Acer)                            | 2         | 5.56%   |
| Chicony HD WebCam                                   | 2         | 5.56%   |
| Apple Built-in iSight                               | 2         | 5.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.78%   |
| Sunplus HD WebCam                                   | 1         | 2.78%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.78%   |
| Realtek USB Camera                                  | 1         | 2.78%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.78%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 2.78%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.78%   |
| Microdia Integrated Webcam                          | 1         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.78%   |
| Logitech Logitech Webcam C160                       | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                         | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.78%   |
| IMC Networks Integrated Camera                      | 1         | 2.78%   |
| Chicony WebCam                                      | 1         | 2.78%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.78%   |
| Chicony Integrated Camera                           | 1         | 2.78%   |
| Chicony HP Webcam-101                               | 1         | 2.78%   |
| Chicony Camera                                      | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.78%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 2.78%   |
| ALi WebCam                                          | 1         | 2.78%   |
| ALi Gateway Webcam                                  | 1         | 2.78%   |
| Acer Integrated Camera                              | 1         | 2.78%   |
| Acer BisonCam, NB Pro                               | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 66.67%  |
| Focal-systems.Corp    | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 2         | 66.67%  |
| Focal-systems.Corp FT9201Fingerprint.Ì | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 74.24%  |
| 1     | 16        | 24.24%  |
| 2     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 8         | 44.44%  |
| Fingerprint reader       | 3         | 16.67%  |
| Multimedia controller    | 2         | 11.11%  |
| Net/wireless             | 1         | 5.56%   |
| Communication controller | 1         | 5.56%   |
| Chipcard                 | 1         | 5.56%   |
| Camera                   | 1         | 5.56%   |
| Bluetooth                | 1         | 5.56%   |


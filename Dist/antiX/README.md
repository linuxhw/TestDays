antiX - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for antiX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/antiX/Desktop/README.md) and [notebooks](/Dist/antiX/Notebook/README.md).

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

Total: 83

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-571G              | Notebook    | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| VXL           | M6V90AI-VL                  | Desktop     | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | Notebook    | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | Notebook    | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | Notebook    | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | Notebook    | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | Notebook    | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Unknown       | K8NF3-VSTA                  | Desktop     | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| AZW           | GK mini                     | Mini pc     | [9d00f58b53](https://linux-hardware.org/?probe=9d00f58b53) | May 04, 2022 |
| AZW           | GK mini                     | Mini pc     | [d474b9b330](https://linux-hardware.org/?probe=d474b9b330) | May 04, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | Notebook    | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | Notebook    | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Unknown       | NF-CK804                    | Desktop     | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | Notebook    | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | Notebook    | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | Notebook    | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | Notebook    | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | Notebook    | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [4a3e3cd4ee](https://linux-hardware.org/?probe=4a3e3cd4ee) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [e751bd8090](https://linux-hardware.org/?probe=e751bd8090) | Jan 14, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [cac53c0d21](https://linux-hardware.org/?probe=cac53c0d21) | Jan 14, 2021 |
| HP            | Mini 110-3700               | Notebook    | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| HP            | 8430 1000                   | All in one  | [db9e0da88a](https://linux-hardware.org/?probe=db9e0da88a) | Dec 06, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | Notebook    | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | Notebook    | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | 3641h                       | Desktop     | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| HP            | Mini 5101                   | Notebook    | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | Notebook    | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | Notebook    | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | Notebook    | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | Notebook    | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | Notebook    | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo        | ThinkCentre M91p 4480B9U    | Desktop     | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 29        | 43.94%  |
| antiX 22       | 10        | 15.15%  |
| antiX 19.2     | 8         | 12.12%  |
| antiX 19.3     | 4         | 6.06%   |
| antiX 17.4.1   | 4         | 6.06%   |
| antiX 21-runit | 3         | 4.55%   |
| antiX 19.4     | 2         | 3.03%   |
| antiX 19.1     | 2         | 3.03%   |
| antiX 17.2.1   | 1         | 1.52%   |
| antiX 17.1     | 1         | 1.52%   |
| antiX 17       | 1         | 1.52%   |
| antiX 15       | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 65        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 21.21%  |
| 5.10.57-antix.1-amd64-smp    | 8         | 12.12%  |
| 4.9.0-279-antix.1-amd64-smp  | 8         | 12.12%  |
| 5.10.142-antix.2-amd64-smp   | 5         | 7.58%   |
| 4.9.160-antix.2-486-smp      | 4         | 6.06%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 4.55%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 4.55%   |
| 4.9.212-antix.1-486-smp      | 3         | 4.55%   |
| 4.9.0-326-antix.1-amd64-smp  | 3         | 4.55%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 3.03%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.03%   |
| 4.9.0-326-antix.1-486-smp    | 2         | 3.03%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.52%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.52%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.52%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.52%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.52%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.52%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.52%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.52%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 27        | 41.54%  |
| 5.10.57  | 8         | 12.31%  |
| 4.9.212  | 6         | 9.23%   |
| 5.10.142 | 5         | 7.69%   |
| 4.9.160  | 5         | 7.69%   |
| 4.9.235  | 3         | 4.62%   |
| 5.10.88  | 2         | 3.08%   |
| 4.9.200  | 2         | 3.08%   |
| 5.14.0   | 1         | 1.54%   |
| 5.10.27  | 1         | 1.54%   |
| 4.9.87   | 1         | 1.54%   |
| 4.19.202 | 1         | 1.54%   |
| 4.19.100 | 1         | 1.54%   |
| 4.19.0   | 1         | 1.54%   |
| 4.10.5   | 1         | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 44        | 67.69%  |
| 5.10    | 16        | 24.62%  |
| 4.19    | 3         | 4.62%   |
| 5.14    | 1         | 1.54%   |
| 4.10    | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 55.38%  |
| i686   | 28        | 43.08%  |
| i586   | 1         | 1.54%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 33        | 50.77%  |
| icewm        | 24        | 36.92%  |
| XFCE         | 4         | 6.15%   |
| jwm          | 1         | 1.54%   |
| herbstluftwm | 1         | 1.54%   |
| GNOME        | 1         | 1.54%   |
| fluxbox      | 1         | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 64        | 98.46%  |
| Tty  | 1         | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 34        | 52.31%  |
| SLiM    | 21        | 32.31%  |
| LightDM | 5         | 7.69%   |
| SLIMSKI | 4         | 6.15%   |
| SDDM    | 1         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 29        | 44.62%  |
| ru_RU   | 6         | 9.23%   |
| de_DE   | 4         | 6.15%   |
| ja_JP   | 3         | 4.62%   |
| Unknown | 3         | 4.62%   |
| sk_SK   | 2         | 3.08%   |
| pt_BR   | 2         | 3.08%   |
| pl_PL   | 2         | 3.08%   |
| nl_NL   | 2         | 3.08%   |
| it_IT   | 2         | 3.08%   |
| en_GB   | 2         | 3.08%   |
| en_AU   | 2         | 3.08%   |
| zh_HK   | 1         | 1.54%   |
| uk_UA   | 1         | 1.54%   |
| es_VE   | 1         | 1.54%   |
| es_MX   | 1         | 1.54%   |
| es_AR   | 1         | 1.54%   |
| de_AT   | 1         | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 54        | 83.08%  |
| EFI  | 11        | 16.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 56        | 86.15%  |
| Overlay  | 8         | 12.31%  |
| Reiserfs | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 51        | 78.46%  |
| GPT     | 12        | 18.46%  |
| Unknown | 2         | 3.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 78.79%  |
| Yes       | 14        | 21.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 60%     |
| Yes       | 26        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 11        | 16.92%  |
| Hewlett-Packard     | 8         | 12.31%  |
| Lenovo              | 7         | 10.77%  |
| IBM                 | 5         | 7.69%   |
| Dell                | 4         | 6.15%   |
| Acer                | 4         | 6.15%   |
| MSI                 | 3         | 4.62%   |
| Unknown             | 3         | 4.62%   |
| Toshiba             | 2         | 3.08%   |
| KOHJINSHA           | 2         | 3.08%   |
| Gigabyte Technology | 2         | 3.08%   |
| Fujitsu             | 2         | 3.08%   |
| VXL                 | 1         | 1.54%   |
| Samsung Electronics | 1         | 1.54%   |
| Radiant Systems     | 1         | 1.54%   |
| Packard Bell        | 1         | 1.54%   |
| Medion              | 1         | 1.54%   |
| Intel               | 1         | 1.54%   |
| Google              | 1         | 1.54%   |
| Compaq              | 1         | 1.54%   |
| Biostar             | 1         | 1.54%   |
| AZW                 | 1         | 1.54%   |
| Apple               | 1         | 1.54%   |
| AMI                 | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 6.15%   |
| MSI US Desktop                     | 2         | 3.08%   |
| IBM 260921H                        | 2         | 3.08%   |
| HP Mini 110-3700                   | 2         | 3.08%   |
| VXL TC7520d                        | 1         | 1.54%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.54%   |
| Toshiba Satellite 1905             | 1         | 1.54%   |
| Samsung SQ1S                       | 1         | 1.54%   |
| Radiant Systems P845               | 1         | 1.54%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.54%   |
| MSI GE62 7RE                       | 1         | 1.54%   |
| Medion WIM2170                     | 1         | 1.54%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.54%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.54%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.54%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.54%   |
| Lenovo G550 2958                   | 1         | 1.54%   |
| Lenovo 3000 V100 076346G           | 1         | 1.54%   |
| KOHJINSHA SX series                | 1         | 1.54%   |
| KOHJINSHA SC series                | 1         | 1.54%   |
| Intel D525MW AAE93082-401          | 1         | 1.54%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.54%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.54%   |
| IBM ThinkPad T40 237342G           | 1         | 1.54%   |
| HP t5740                           | 1         | 1.54%   |
| HP Pavilion dv2700                 | 1         | 1.54%   |
| HP Mini 5101                       | 1         | 1.54%   |
| HP EliteBook 8770w                 | 1         | 1.54%   |
| HP EliteBook 2570p                 | 1         | 1.54%   |
| HP All-in-One 24-f0xx              | 1         | 1.54%   |
| Google Candy                       | 1         | 1.54%   |
| Gigabyte F2A85XM-D3H               | 1         | 1.54%   |
| Gigabyte 945GCMX-S2                | 1         | 1.54%   |
| Fujitsu FMVS54EB                   | 1         | 1.54%   |
| Fujitsu FMVNU6G1C                  | 1         | 1.54%   |
| Dell OptiPlex 960                  | 1         | 1.54%   |
| Dell Latitude E6400                | 1         | 1.54%   |
| Dell Latitude 5480                 | 1         | 1.54%   |
| Dell Latitude 2120                 | 1         | 1.54%   |
| Compaq Tablet PC TC1000            | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 4         | 6.15%   |
| IBM ThinkPad          | 3         | 4.62%   |
| HP Mini               | 3         | 4.62%   |
| Dell Latitude         | 3         | 4.62%   |
| Acer Aspire           | 3         | 4.62%   |
| Toshiba Satellite     | 2         | 3.08%   |
| MSI US                | 2         | 3.08%   |
| Lenovo ThinkPad       | 2         | 3.08%   |
| IBM 260921H           | 2         | 3.08%   |
| HP EliteBook          | 2         | 3.08%   |
| ASUS VivoBook         | 2         | 3.08%   |
| VXL TC7520d           | 1         | 1.54%   |
| Samsung SQ1S          | 1         | 1.54%   |
| Radiant Systems P845  | 1         | 1.54%   |
| Packard Bell EasyNote | 1         | 1.54%   |
| MSI GE62              | 1         | 1.54%   |
| Medion WIM2170        | 1         | 1.54%   |
| Lenovo ThinkCentre    | 1         | 1.54%   |
| Lenovo IdeaPad        | 1         | 1.54%   |
| Lenovo G550           | 1         | 1.54%   |
| Lenovo 3000           | 1         | 1.54%   |
| KOHJINSHA SX          | 1         | 1.54%   |
| KOHJINSHA SC          | 1         | 1.54%   |
| Intel D525MW          | 1         | 1.54%   |
| HP t5740              | 1         | 1.54%   |
| HP Pavilion           | 1         | 1.54%   |
| HP All-in-One         | 1         | 1.54%   |
| Google Candy          | 1         | 1.54%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.54%   |
| Gigabyte 945GCMX-S2   | 1         | 1.54%   |
| Fujitsu FMVS54EB      | 1         | 1.54%   |
| Fujitsu FMVNU6G1C     | 1         | 1.54%   |
| Dell OptiPlex         | 1         | 1.54%   |
| Compaq Tablet         | 1         | 1.54%   |
| Biostar G31-M7        | 1         | 1.54%   |
| AZW GK                | 1         | 1.54%   |
| ASUS X71SL            | 1         | 1.54%   |
| ASUS X51RL            | 1         | 1.54%   |
| ASUS S3N              | 1         | 1.54%   |
| ASUS P5KPL            | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 9         | 13.85%  |
| 2008    | 9         | 13.85%  |
| 2007    | 9         | 13.85%  |
| 2012    | 4         | 6.15%   |
| 2011    | 4         | 6.15%   |
| 2021    | 3         | 4.62%   |
| 2013    | 3         | 4.62%   |
| 2010    | 3         | 4.62%   |
| 2005    | 3         | 4.62%   |
| 2003    | 3         | 4.62%   |
| 2018    | 2         | 3.08%   |
| 2014    | 2         | 3.08%   |
| 2004    | 2         | 3.08%   |
| 1999    | 2         | 3.08%   |
| 2022    | 1         | 1.54%   |
| 2020    | 1         | 1.54%   |
| 2019    | 1         | 1.54%   |
| 2017    | 1         | 1.54%   |
| 2016    | 1         | 1.54%   |
| 2006    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 46        | 70.77%  |
| Desktop    | 15        | 23.08%  |
| Mini pc    | 3         | 4.62%   |
| All in one | 1         | 1.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 65        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 98.46%  |
| Yes  | 1         | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 23.08%  |
| 1.01-2.0   | 12        | 18.46%  |
| 0.51-1.0   | 10        | 15.38%  |
| 2.01-3.0   | 9         | 13.85%  |
| 4.01-8.0   | 5         | 7.69%   |
| 0.01-0.5   | 5         | 7.69%   |
| 32.01-64.0 | 4         | 6.15%   |
| 8.01-16.0  | 3         | 4.62%   |
| 16.01-24.0 | 2         | 3.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 25        | 38.46%  |
| 0.51-1.0 | 23        | 35.38%  |
| 1.01-2.0 | 11        | 16.92%  |
| 2.01-3.0 | 5         | 7.69%   |
| 4.01-8.0 | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 72.31%  |
| 2      | 10        | 15.38%  |
| 3      | 4         | 6.15%   |
| 0      | 3         | 4.62%   |
| 4      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 58.46%  |
| Yes       | 27        | 41.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 89.23%  |
| No        | 7         | 10.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 80%     |
| No        | 13        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 64.62%  |
| Yes       | 23        | 35.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 18.46%  |
| Hong Kong   | 9         | 13.85%  |
| Russia      | 8         | 12.31%  |
| Germany     | 6         | 9.23%   |
| Poland      | 3         | 4.62%   |
| Netherlands | 3         | 4.62%   |
| Japan       | 3         | 4.62%   |
| Slovakia    | 2         | 3.08%   |
| Italy       | 2         | 3.08%   |
| Brazil      | 2         | 3.08%   |
| Australia   | 2         | 3.08%   |
| Ukraine     | 1         | 1.54%   |
| UK          | 1         | 1.54%   |
| Mexico      | 1         | 1.54%   |
| Kenya       | 1         | 1.54%   |
| Kazakhstan  | 1         | 1.54%   |
| Hungary     | 1         | 1.54%   |
| Greece      | 1         | 1.54%   |
| France      | 1         | 1.54%   |
| Denmark     | 1         | 1.54%   |
| Chile       | 1         | 1.54%   |
| Bulgaria    | 1         | 1.54%   |
| Austria     | 1         | 1.54%   |
| Argentina   | 1         | 1.54%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 10.61%  |
| Sydney                    | 2         | 3.03%   |
| St Petersburg             | 2         | 3.03%   |
| Moscow                    | 2         | 3.03%   |
| Bratislava                | 2         | 3.03%   |
| Żyrardów                | 1         | 1.52%   |
| Zagnansk                  | 1         | 1.52%   |
| Yuzhno-Sakhalinsk         | 1         | 1.52%   |
| Yokohama                  | 1         | 1.52%   |
| Ybbs an der Donau         | 1         | 1.52%   |
| Whitney                   | 1         | 1.52%   |
| Violes                    | 1         | 1.52%   |
| Trissino                  | 1         | 1.52%   |
| Toms River                | 1         | 1.52%   |
| Sofia                     | 1         | 1.52%   |
| Sheung Shui               | 1         | 1.52%   |
| Schloss Holte-Stukenbrock | 1         | 1.52%   |
| Santiago                  | 1         | 1.52%   |
| Salto                     | 1         | 1.52%   |
| Rotterdam                 | 1         | 1.52%   |
| Reutlingen                | 1         | 1.52%   |
| Purmerend                 | 1         | 1.52%   |
| Portland                  | 1         | 1.52%   |
| Otwock                    | 1         | 1.52%   |
| Nova Londrina             | 1         | 1.52%   |
| Norden                    | 1         | 1.52%   |
| Neyagawa                  | 1         | 1.52%   |
| Nairobi                   | 1         | 1.52%   |
| Mittegrossefehn           | 1         | 1.52%   |
| Milan                     | 1         | 1.52%   |
| Mechanicsburg             | 1         | 1.52%   |
| Mason                     | 1         | 1.52%   |
| Maidstone                 | 1         | 1.52%   |
| Kazan’                  | 1         | 1.52%   |
| Karaganda                 | 1         | 1.52%   |
| Kagoshima                 | 1         | 1.52%   |
| Jonesboro                 | 1         | 1.52%   |
| Houston                   | 1         | 1.52%   |
| Hobbs                     | 1         | 1.52%   |
| Heraklion                 | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 15.58%  |
| Seagate             | 12        | 12     | 15.58%  |
| Hitachi             | 12        | 13     | 15.58%  |
| Samsung Electronics | 8         | 9      | 10.39%  |
| Toshiba             | 7         | 7      | 9.09%   |
| Unknown             | 4         | 4      | 5.19%   |
| Kingston            | 2         | 2      | 2.6%    |
| BHT                 | 2         | 3      | 2.6%    |
| Zheino              | 1         | 1      | 1.3%    |
| Unknown (CF)        | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| SanDisk             | 1         | 1      | 1.3%    |
| RECADATA            | 1         | 1      | 1.3%    |
| PNY                 | 1         | 1      | 1.3%    |
| OCZ                 | 1         | 1      | 1.3%    |
| Maxtor              | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| IBM/Hitachi         | 1         | 1      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |
| Fujitsu             | 1         | 1      | 1.3%    |
| Crucial             | 1         | 1      | 1.3%    |
| China               | 1         | 1      | 1.3%    |
| ASUS-PHISON         | 1         | 1      | 1.3%    |
| Apacer              | 1         | 1      | 1.3%    |
| Unknown             | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 120GB               | 2         | 2.53%   |
| Samsung SSD 750 EVO 120GB               | 2         | 2.53%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2.53%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.53%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.27%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 1.27%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 1.27%   |
| WDC WD800AAJS-75M0A0 80GB               | 1         | 1.27%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.27%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.27%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.27%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.27%   |
| WDC WD205BA 21GB                        | 1         | 1.27%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 1.27%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.27%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 1.27%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.27%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 1.27%   |
| Unknown SR64G  64GB                     | 1         | 1.27%   |
| Unknown SD/MMC/MS PRO 16GB              | 1         | 1.27%   |
| Unknown HAG2e  16GB                     | 1         | 1.27%   |
| Unknown 2GB ATA Flash Disk              | 1         | 1.27%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.27%   |
| Transcend SSD 2GB                       | 1         | 1.27%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.27%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.27%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.27%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.27%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 1.27%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.27%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.27%   |
| Seagate ST9320325AS 320GB               | 1         | 1.27%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.27%   |
| Seagate ST9160411AS 160GB               | 1         | 1.27%   |
| Seagate ST9160314AS 160GB               | 1         | 1.27%   |
| Seagate ST9160310AS 160GB               | 1         | 1.27%   |
| Seagate ST9160301AS 160GB               | 1         | 1.27%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.27%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.27%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 24%     |
| Seagate             | 12        | 12     | 24%     |
| Hitachi             | 12        | 13     | 24%     |
| Toshiba             | 5         | 5      | 10%     |
| Samsung Electronics | 4         | 5      | 8%      |
| Unknown             | 2         | 2      | 4%      |
| IBM/Hitachi         | 1         | 1      | 2%      |
| HGST                | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16%     |
| Toshiba             | 2         | 2      | 8%      |
| Kingston            | 2         | 2      | 8%      |
| BHT                 | 2         | 3      | 8%      |
| Zheino              | 1         | 1      | 4%      |
| Unknown (CF)        | 1         | 1      | 4%      |
| Transcend           | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| RECADATA            | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| OCZ                 | 1         | 1      | 4%      |
| Maxtor              | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| China               | 1         | 1      | 4%      |
| ASUS-PHISON         | 1         | 1      | 4%      |
| Apacer              | 1         | 1      | 4%      |
| Unknown             | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 53     | 62.86%  |
| SSD  | 24        | 26     | 34.29%  |
| MMC  | 2         | 2      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 78     | 95.31%  |
| MMC  | 2         | 2      | 3.13%   |
| SAS  | 1         | 1      | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 70     | 86.76%  |
| 0.51-1.0   | 8         | 8      | 11.76%  |
| 1.01-2.0   | 1         | 1      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 30.3%   |
| 1-20       | 18        | 27.27%  |
| 21-50      | 9         | 13.64%  |
| 51-100     | 9         | 13.64%  |
| 251-500    | 4         | 6.06%   |
| 501-1000   | 4         | 6.06%   |
| 1001-2000  | 1         | 1.52%   |
| Unknown    | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 51        | 78.46%  |
| 21-50    | 6         | 9.23%   |
| 101-250  | 4         | 6.15%   |
| 51-100   | 2         | 3.08%   |
| 501-1000 | 1         | 1.54%   |
| Unknown  | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB      | 1         | 1      | 4.35%   |
| WDC WD800JB-00ETA0 80GB          | 1         | 1      | 4.35%   |
| WDC WD800AAJS-75M0A0 80GB        | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-60ZCT1 320GB      | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-22ZCT0 250GB      | 1         | 1      | 4.35%   |
| WDC WD205BA 21GB                 | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB        | 1         | 1      | 4.35%   |
| Seagate ST9160314AS 160GB        | 1         | 1      | 4.35%   |
| Seagate ST9160310AS 160GB        | 1         | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB  | 1         | 1      | 4.35%   |
| Seagate ST3320620AS 320GB        | 1         | 1      | 4.35%   |
| Seagate ST3320413CS 320GB        | 1         | 1      | 4.35%   |
| SanDisk sandisk120 120GB SSD     | 1         | 1      | 4.35%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 1      | 4.35%   |
| Hitachi HTS721060G9AT00 64GB     | 1         | 1      | 4.35%   |
| Hitachi HTS548040M9AT00 40GB     | 1         | 1      | 4.35%   |
| Hitachi HTS543225A7A384 250GB    | 1         | 1      | 4.35%   |
| Hitachi HTS542525K9SA00 250GB    | 1         | 1      | 4.35%   |
| Hitachi HTS541612J9SA00 120GB    | 1         | 1      | 4.35%   |
| Hitachi HTC426040G8CE00 40GB     | 1         | 1      | 4.35%   |
| China M.2 SSD 128GB              | 1         | 1      | 4.35%   |
| Apacer 32GB SATA Flash Drive SSD | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 34.78%  |
| WDC     | 6         | 6      | 26.09%  |
| Seagate | 6         | 6      | 26.09%  |
| SanDisk | 1         | 1      | 4.35%   |
| China   | 1         | 1      | 4.35%   |
| Apacer  | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 40%     |
| WDC     | 6         | 6      | 30%     |
| Seagate | 6         | 6      | 30%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 86.96%  |
| SSD  | 3         | 3      | 13.04%  |

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
| Works    | 39        | 49     | 55.71%  |
| Malfunc  | 23        | 23     | 32.86%  |
| Detected | 8         | 9      | 11.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 50        | 71.43%  |
| Nvidia                           | 4         | 5.71%   |
| ASMedia Technology               | 4         | 5.71%   |
| AMD                              | 4         | 5.71%   |
| VIA Technologies                 | 3         | 4.29%   |
| Silicon Integrated Systems [SiS] | 2         | 2.86%   |
| ULi Electronics                  | 1         | 1.43%   |
| Silicon Image                    | 1         | 1.43%   |
| JMicron Technology               | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                             | 7         | 8.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 5         | 5.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]         | 4         | 4.6%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                | 4         | 4.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                     | 3         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]         | 3         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                      | 3         | 3.45%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                         | 3         | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                 | 3         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 3         | 3.45%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode           | 2         | 2.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                  | 2         | 2.3%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller            | 2         | 2.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                | 2         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 2         | 2.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]        | 2         | 2.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 2         | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 2         | 2.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                  | 2         | 2.3%    |
| VIA VX900 Series Serial-ATA Controller                                | 1         | 1.15%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE           | 1         | 1.15%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller       | 1         | 1.15%   |
| ULi ULi M5288 SATA                                                    | 1         | 1.15%   |
| ULi M5229 IDE                                                         | 1         | 1.15%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller      | 1         | 1.15%   |
| Nvidia nForce3 Serial ATA Controller                                  | 1         | 1.15%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                              | 1         | 1.15%   |
| Nvidia MCP67 IDE Controller                                           | 1         | 1.15%   |
| Nvidia MCP67 AHCI Controller                                          | 1         | 1.15%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                            | 1         | 1.15%   |
| Nvidia CK804 Serial ATA Controller                                    | 1         | 1.15%   |
| Nvidia CK804 IDE                                                      | 1         | 1.15%   |
| JMicron JMB360 AHCI Controller                                        | 1         | 1.15%   |
| Intel SATA Controller [RAID mode]                                     | 1         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                 | 1         | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                | 1         | 1.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]  | 1         | 1.15%   |
| Intel 82801FBM (ICH6M) SATA Controller                                | 1         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller              | 1         | 1.15%   |
| Intel 82801DB (ICH4) IDE Controller                                   | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 38        | 51.35%  |
| SATA | 32        | 43.24%  |
| RAID | 4         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 55        | 84.62%  |
| AMD          | 7         | 10.77%  |
| CentaurHauls | 2         | 3.08%   |
| GenuineTMx86 | 1         | 1.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 6.15%   |
| Intel Pentium M processor 1.60GHz           | 2         | 3.08%   |
| Intel Pentium M processor 1.00GHz           | 2         | 3.08%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 3.08%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 3.08%   |
| Intel Celeron (Mendocino)                   | 2         | 3.08%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.08%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.08%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.08%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 3.08%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.54%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.54%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.54%   |
| Intel Pentium II (Deschutes)                | 1         | 1.54%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.54%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.54%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.54%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.54%   |
| Intel Genuine processor 800MHz              | 1         | 1.54%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.54%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.54%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.54%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.54%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.54%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.54%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.54%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.54%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 1.54%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.54%   |
| Intel Celeron M processor 900MHz            | 1         | 1.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.54%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.54%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 1.54%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 13        | 20%     |
| Intel Celeron           | 7         | 10.77%  |
| Intel Pentium M         | 6         | 9.23%   |
| Intel Core 2 Duo        | 6         | 9.23%   |
| Other                   | 4         | 6.15%   |
| Intel Core i7           | 4         | 6.15%   |
| Intel Core i5           | 3         | 4.62%   |
| Intel Core i3           | 3         | 4.62%   |
| Intel Pentium Dual      | 2         | 3.08%   |
| Intel Genuine           | 2         | 3.08%   |
| AMD Athlon 64 X2        | 2         | 3.08%   |
| Intel Xeon              | 1         | 1.54%   |
| Intel Pentium Dual-Core | 1         | 1.54%   |
| Intel Pentium 4         | 1         | 1.54%   |
| Intel Pentium           | 1         | 1.54%   |
| Intel Core 2 Quad       | 1         | 1.54%   |
| Intel Celeron M         | 1         | 1.54%   |
| Intel Celeron Dual-Core | 1         | 1.54%   |
| CentaurHauls VIA Nano   | 1         | 1.54%   |
| CentaurHauls VIA Eden   | 1         | 1.54%   |
| AMD Sempron             | 1         | 1.54%   |
| AMD E2                  | 1         | 1.54%   |
| AMD Athlon 64           | 1         | 1.54%   |
| AMD A6                  | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 43.08%  |
| 1      | 28        | 43.08%  |
| 4      | 7         | 10.77%  |
| 6      | 2         | 3.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 61.54%  |
| 2      | 25        | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 64.62%  |
| 32-bit         | 23        | 35.38%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 8         | 12.31%  |
| Unknown    | 7         | 10.77%  |
| 0x1067a    | 6         | 9.23%   |
| 0x6fd      | 5         | 7.69%   |
| 0x6d6      | 4         | 6.15%   |
| 0x106ca    | 4         | 6.15%   |
| 0x6d8      | 3         | 4.62%   |
| 0x306a9    | 3         | 4.62%   |
| 0xa0671    | 2         | 3.08%   |
| 0x66a      | 2         | 3.08%   |
| 0x30678    | 2         | 3.08%   |
| 0x206a7    | 2         | 3.08%   |
| 0xf24      | 1         | 1.54%   |
| 0x906e9    | 1         | 1.54%   |
| 0x806e9    | 1         | 1.54%   |
| 0x706a8    | 1         | 1.54%   |
| 0x706a1    | 1         | 1.54%   |
| 0x6e8      | 1         | 1.54%   |
| 0x695      | 1         | 1.54%   |
| 0x652      | 1         | 1.54%   |
| 0x40651    | 1         | 1.54%   |
| 0x306c3    | 1         | 1.54%   |
| 0x30661    | 1         | 1.54%   |
| 0x20655    | 1         | 1.54%   |
| 0x10676    | 1         | 1.54%   |
| 0x10661    | 1         | 1.54%   |
| 0x07030106 | 1         | 1.54%   |
| 0x06006705 | 1         | 1.54%   |
| 0x06001116 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 13        | 20%     |
| P6            | 9         | 13.85%  |
| Unknown       | 8         | 12.31%  |
| Penryn        | 7         | 10.77%  |
| Core          | 6         | 9.23%   |
| K8 Hammer     | 4         | 6.15%   |
| IvyBridge     | 3         | 4.62%   |
| Silvermont    | 2         | 3.08%   |
| SandyBridge   | 2         | 3.08%   |
| KabyLake      | 2         | 3.08%   |
| Haswell       | 2         | 3.08%   |
| Goldmont plus | 2         | 3.08%   |
| Westmere      | 1         | 1.54%   |
| Puma          | 1         | 1.54%   |
| Piledriver    | 1         | 1.54%   |
| NetBurst      | 1         | 1.54%   |
| Excavator     | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 52.94%  |
| Nvidia                           | 14        | 20.59%  |
| AMD                              | 13        | 19.12%  |
| VIA Technologies                 | 2         | 2.94%   |
| Neomagic                         | 2         | 2.94%   |
| Silicon Integrated Systems [SiS] | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 8.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 6.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 4         | 5%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 3.75%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 3.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 2.5%    |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.5%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.5%    |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.5%    |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                  | 1         | 1.25%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.25%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.25%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.25%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.25%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.25%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 1.25%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.25%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.25%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.25%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.25%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.25%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.25%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.25%   |
| Intel HD Graphics 630                                                         | 1         | 1.25%   |
| Intel HD Graphics 620                                                         | 1         | 1.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.25%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.25%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 47.69%  |
| 1 x Nvidia     | 11        | 16.92%  |
| 1 x AMD        | 9         | 13.85%  |
| 2 x AMD        | 4         | 6.15%   |
| Intel + Nvidia | 3         | 4.62%   |
| Other          | 2         | 3.08%   |
| 1 x VIA        | 2         | 3.08%   |
| 1 x Neomagic   | 2         | 3.08%   |
| 1 x SiS        | 1         | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 78.46%  |
| Unknown     | 10        | 15.38%  |
| Proprietary | 4         | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 29        | 44.62%  |
| Unknown    | 25        | 38.46%  |
| 1.01-2.0   | 8         | 12.31%  |
| 5.01-6.0   | 1         | 1.54%   |
| 3.01-4.0   | 1         | 1.54%   |
| 0.51-1.0   | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 23.26%  |
| LG Display              | 6         | 13.95%  |
| Samsung Electronics     | 5         | 11.63%  |
| HannStar                | 3         | 6.98%   |
| Goldstar                | 3         | 6.98%   |
| Acer                    | 3         | 6.98%   |
| LG Philips              | 2         | 4.65%   |
| Vizio                   | 1         | 2.33%   |
| Lenovo                  | 1         | 2.33%   |
| HJW                     | 1         | 2.33%   |
| Hewlett-Packard         | 1         | 2.33%   |
| Dell                    | 1         | 2.33%   |
| CPT                     | 1         | 2.33%   |
| Chimei Innolux          | 1         | 2.33%   |
| Chi Mei Optoelectronics | 1         | 2.33%   |
| BOE                     | 1         | 2.33%   |
| Arnos Instruments       | 1         | 2.33%   |
| Apple                   | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 4.65%   |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.33%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.33%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.33%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.33%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.33%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.33%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x296mm 23.8-inch         | 1         | 2.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.33%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.33%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 1         | 2.33%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                    | 1         | 2.33%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                     | 1         | 2.33%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 2.33%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.33%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.33%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch            | 1         | 2.33%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 2.33%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                        | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 12        | 28.57%  |
| 1920x1080 (FHD)  | 9         | 21.43%  |
| 1024x600         | 7         | 16.67%  |
| 1280x800 (WXGA)  | 6         | 14.29%  |
| 1440x900 (WXGA+) | 4         | 9.52%   |
| 1600x1200        | 2         | 4.76%   |
| 2560x1080        | 1         | 2.38%   |
| 1280x1024 (SXGA) | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 8         | 18.6%   |
| 10     | 6         | 13.95%  |
| 21     | 4         | 9.3%    |
| 17     | 4         | 9.3%    |
| 14     | 4         | 9.3%    |
| 13     | 4         | 9.3%    |
| 12     | 2         | 4.65%   |
| 8      | 2         | 4.65%   |
| 38     | 1         | 2.33%   |
| 34     | 1         | 2.33%   |
| 32     | 1         | 2.33%   |
| 27     | 1         | 2.33%   |
| 24     | 1         | 2.33%   |
| 23     | 1         | 2.33%   |
| 19     | 1         | 2.33%   |
| 18     | 1         | 2.33%   |
| 11     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 32.56%  |
| 201-300     | 12        | 27.91%  |
| 401-500     | 6         | 13.95%  |
| 501-600     | 3         | 6.98%   |
| 351-400     | 3         | 6.98%   |
| 701-800     | 2         | 4.65%   |
| 101-200     | 2         | 4.65%   |
| 801-900     | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 64.29%  |
| 16/10 | 10        | 23.81%  |
| 4/3   | 2         | 4.76%   |
| 5/4   | 1         | 2.38%   |
| 3/2   | 1         | 2.38%   |
| 21/9  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 18.6%   |
| 81-90          | 6         | 13.95%  |
| 41-50          | 6         | 13.95%  |
| 201-250        | 5         | 11.63%  |
| 71-80          | 2         | 4.65%   |
| 61-70          | 2         | 4.65%   |
| 351-500        | 2         | 4.65%   |
| 1-40           | 2         | 4.65%   |
| 151-200        | 2         | 4.65%   |
| 141-150        | 2         | 4.65%   |
| 131-140        | 2         | 4.65%   |
| 51-60          | 1         | 2.33%   |
| 301-350        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |
| 501-1000       | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 38.1%   |
| 51-100  | 14        | 33.33%  |
| 121-160 | 11        | 26.19%  |
| 1-50    | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 83.33%  |
| 0     | 9         | 13.64%  |
| 2     | 2         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 26        | 25.24%  |
| Intel                            | 26        | 25.24%  |
| Qualcomm Atheros                 | 19        | 18.45%  |
| Broadcom                         | 12        | 11.65%  |
| Nvidia                           | 4         | 3.88%   |
| Marvell Technology Group         | 3         | 2.91%   |
| Silicon Integrated Systems [SiS] | 2         | 1.94%   |
| Qualcomm Atheros Communications  | 2         | 1.94%   |
| Texas Instruments                | 1         | 0.97%   |
| Ralink Technology                | 1         | 0.97%   |
| Ralink                           | 1         | 0.97%   |
| MediaTek                         | 1         | 0.97%   |
| LSI                              | 1         | 0.97%   |
| Hewlett-Packard                  | 1         | 0.97%   |
| Broadcom Limited                 | 1         | 0.97%   |
| Attansic Technology              | 1         | 0.97%   |
| ASIX Electronics                 | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8         | 6.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 6.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 5.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 3.2%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.4%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.6%    |
| Intel Wireless 7260                                                           | 2         | 1.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.6%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.6%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.6%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.6%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.8%    |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.8%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.8%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.8%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.8%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.8%    |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 36.84%  |
| Qualcomm Atheros                | 17        | 29.82%  |
| Broadcom                        | 9         | 15.79%  |
| Realtek Semiconductor           | 4         | 7.02%   |
| Qualcomm Atheros Communications | 2         | 3.51%   |
| Texas Instruments               | 1         | 1.75%   |
| Ralink Technology               | 1         | 1.75%   |
| Ralink                          | 1         | 1.75%   |
| MediaTek                        | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 13.79%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 6.9%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 5.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 5.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.45%   |
| Intel Wireless 7260                                                           | 2         | 3.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.45%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.72%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.72%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.72%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.72%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.72%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.72%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.72%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.72%   |
| Intel Wireless 3165                                                           | 1         | 1.72%   |
| Intel WiFi Link 5100                                                          | 1         | 1.72%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.72%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.72%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.72%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.72%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 41.67%  |
| Intel                            | 13        | 21.67%  |
| Broadcom                         | 6         | 10%     |
| Qualcomm Atheros                 | 4         | 6.67%   |
| Nvidia                           | 4         | 6.67%   |
| Marvell Technology Group         | 3         | 5%      |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| Broadcom Limited                 | 1         | 1.67%   |
| Attansic Technology              | 1         | 1.67%   |
| ASIX Electronics                 | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 13.33%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 11.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.33%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 3.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 3.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.67%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.67%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.67%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.67%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.67%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.67%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.67%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.67%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.67%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.67%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.67%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.67%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 58        | 49.57%  |
| WiFi     | 52        | 44.44%  |
| Modem    | 7         | 5.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 67.16%  |
| Ethernet | 22        | 32.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 44        | 67.69%  |
| 1     | 21        | 32.31%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 84.85%  |
| Yes  | 10        | 15.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 8         | 34.78%  |
| Intel                   | 6         | 26.09%  |
| IMC Networks            | 2         | 8.7%    |
| Cambridge Silicon Radio | 2         | 8.7%    |
| Realtek Semiconductor   | 1         | 4.35%   |
| Ralink Technology       | 1         | 4.35%   |
| Foxconn / Hon Hai       | 1         | 4.35%   |
| ASUSTek Computer        | 1         | 4.35%   |
| Apple                   | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 13.04%  |
| Intel AX201 Bluetooth                               | 2         | 8.7%    |
| IMC Networks Bluetooth Device                       | 2         | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8.7%    |
| Broadcom HP Portable SoftSailing                    | 2         | 8.7%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.35%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 4.35%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 4.35%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 4.35%   |
| Apple Bluetooth Host Controller                     | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 63.01%  |
| Nvidia                           | 8         | 10.96%  |
| AMD                              | 6         | 8.22%   |
| VIA Technologies                 | 3         | 4.11%   |
| Silicon Integrated Systems [SiS] | 2         | 2.74%   |
| ESS Technology                   | 2         | 2.74%   |
| Creative Labs                    | 2         | 2.74%   |
| C-Media Electronics              | 2         | 2.74%   |
| ULi Electronics                  | 1         | 1.37%   |
| Ensoniq                          | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 17.95%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.85%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2         | 2.56%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.56%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 2.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.56%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.56%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.28%   |
| VIA Technologies High Definition Audio Controller                          | 1         | 1.28%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.28%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.28%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.28%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.28%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.28%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.28%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.28%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.28%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.28%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.28%   |
| C-Media Electronics CM6501                                                 | 1         | 1.28%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 30        | 42.86%  |
| SK hynix            | 11        | 15.71%  |
| Samsung Electronics | 6         | 8.57%   |
| Unknown             | 5         | 7.14%   |
| Kingston            | 4         | 5.71%   |
| Micron Technology   | 3         | 4.29%   |
| Crucial             | 2         | 2.86%   |
| Corsair             | 2         | 2.86%   |
| Unknown (ABCD)      | 1         | 1.43%   |
| Unknown (8A02)      | 1         | 1.43%   |
| tigo                | 1         | 1.43%   |
| Smart               | 1         | 1.43%   |
| Patriot             | 1         | 1.43%   |
| Kllisre             | 1         | 1.43%   |
| Avant               | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 6.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 4%      |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4%      |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 2.67%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.67%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 2.67%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 2         | 2.67%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.33%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.33%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1         | 1.33%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.33%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 1.33%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 1.33%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.33%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 1.33%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.33%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s             | 1         | 1.33%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.33%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.33%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 1.33%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.33%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 19        | 31.15%  |
| DDR2    | 11        | 18.03%  |
| SDRAM   | 10        | 16.39%  |
| DDR     | 8         | 13.11%  |
| DDR4    | 6         | 9.84%   |
| DRAM    | 4         | 6.56%   |
| Unknown | 2         | 3.28%   |
| LPDDR4  | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 44        | 72.13%  |
| DIMM   | 17        | 27.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 21        | 29.58%  |
| 1024  | 17        | 23.94%  |
| 4096  | 11        | 15.49%  |
| 512   | 8         | 11.27%  |
| 16384 | 4         | 5.63%   |
| 8192  | 4         | 5.63%   |
| 256   | 3         | 4.23%   |
| 64    | 2         | 2.82%   |
| 232   | 1         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 34.92%  |
| 1600    | 12        | 19.05%  |
| 667     | 5         | 7.94%   |
| 1067    | 3         | 4.76%   |
| 800     | 3         | 4.76%   |
| 3534    | 2         | 3.17%   |
| 3266    | 2         | 3.17%   |
| 2400    | 2         | 3.17%   |
| 1333    | 2         | 3.17%   |
| 533     | 2         | 3.17%   |
| 3200    | 1         | 1.59%   |
| 2667    | 1         | 1.59%   |
| 1334    | 1         | 1.59%   |
| 975     | 1         | 1.59%   |
| 400     | 1         | 1.59%   |
| 333     | 1         | 1.59%   |
| 266     | 1         | 1.59%   |
| 200     | 1         | 1.59%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 16.13%  |
| IMC Networks                           | 4         | 12.9%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 12.9%   |
| Acer                                   | 4         | 12.9%   |
| Microdia                               | 3         | 9.68%   |
| Suyin                                  | 2         | 6.45%   |
| Pixart Imaging                         | 2         | 6.45%   |
| Sunplus Innovation Technology          | 1         | 3.23%   |
| Silicon Motion                         | 1         | 3.23%   |
| Realtek Semiconductor                  | 1         | 3.23%   |
| Lite-On Technology                     | 1         | 3.23%   |
| Lenovo                                 | 1         | 3.23%   |
| Importek                               | 1         | 3.23%   |
| Apple                                  | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 6.45%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 6.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 6.45%   |
| Acer BisonCam, NB Pro                                   | 2         | 6.45%   |
| Suyin Lenovo EasyCamera                                 | 1         | 3.23%   |
| Suyin Integrated_Webcam_HD                              | 1         | 3.23%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.23%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.23%   |
| Realtek HD WebCam                                       | 1         | 3.23%   |
| Microdia Integrated Webcam                              | 1         | 3.23%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 3.23%   |
| Lenovo Integrated Webcam                                | 1         | 3.23%   |
| Importek FJ Camera                                      | 1         | 3.23%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.23%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 3.23%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.23%   |
| Chicony Integrated HP HD Webcam                         | 1         | 3.23%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.23%   |
| Chicony CNF8243 Webcam                                  | 1         | 3.23%   |
| Chicony CNF7050                                         | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.23%   |
| Apple Built-in iSight                                   | 1         | 3.23%   |
| Acer Lenovo EasyCamera                                  | 1         | 3.23%   |
| Acer Crystal Eye Webcam                                 | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 4         | 66.67%  |
| Validity Sensors | 1         | 16.67%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 33.33%  |
| AuthenTec AES1600                                      | 2         | 33.33%  |
| Validity Sensors VFS491                                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 46        | 70.77%  |
| 1     | 14        | 21.54%  |
| 2     | 3         | 4.62%   |
| 3     | 2         | 3.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 50%     |
| Fingerprint reader       | 6         | 23.08%  |
| Communication controller | 3         | 11.54%  |
| Sound                    | 1         | 3.85%   |
| Net/ethernet             | 1         | 3.85%   |
| Modem                    | 1         | 3.85%   |
| Chipcard                 | 1         | 3.85%   |


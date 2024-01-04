antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 86

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir6,1               | [0275987230](https://linux-hardware.org/?probe=0275987230) | Dec 22, 2023 |
| Unknown       | TK23D                       | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| Acer          | AO531h                      | [25d156801c](https://linux-hardware.org/?probe=25d156801c) | Nov 28, 2023 |
| Acer          | AO531h                      | [1b430bd7c0](https://linux-hardware.org/?probe=1b430bd7c0) | Nov 28, 2023 |
| Google        | Lava                        | [8fb77bcc40](https://linux-hardware.org/?probe=8fb77bcc40) | Oct 09, 2023 |
| Fujitsu       | FMVA05007                   | [265b66f904](https://linux-hardware.org/?probe=265b66f904) | Oct 05, 2023 |
| HP            | G5000 (RY492EA#ACB)         | [0f0a19a64c](https://linux-hardware.org/?probe=0f0a19a64c) | Sep 14, 2023 |
| Toshiba       | Satellite T110              | [ecb4e047b3](https://linux-hardware.org/?probe=ecb4e047b3) | Aug 11, 2023 |
| Apple         | MacBookAir4,1               | [05b5124d92](https://linux-hardware.org/?probe=05b5124d92) | Aug 09, 2023 |
| HP            | 255 G3                      | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| HP            | Presario CQ56               | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [54dfdc8842](https://linux-hardware.org/?probe=54dfdc8842) | Jun 28, 2023 |
| HP            | Pavilion dv6700             | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| Dell          | Vostro 1015                 | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| HP            | 620                         | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| Intel         | powered classmate PC        | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Aspire E5-511               | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 24        | 35.82%  |
| antiX 22       | 19        | 28.36%  |
| antiX 19.2     | 6         | 8.96%   |
| antiX 23       | 5         | 7.46%   |
| antiX 19.3     | 3         | 4.48%   |
| antiX 21-runit | 2         | 2.99%   |
| antiX 19.4     | 2         | 2.99%   |
| antiX 19.1     | 2         | 2.99%   |
| antiX 19.5     | 1         | 1.49%   |
| antiX 17.4.1   | 1         | 1.49%   |
| antiX 17.2.1   | 1         | 1.49%   |
| antiX 17       | 1         | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 15        | 22.39%  |
| 5.10.142-antix.2-amd64-smp   | 8         | 11.94%  |
| 4.9.0-326-antix.1-amd64-smp  | 7         | 10.45%  |
| 4.9.0-279-antix.1-amd64-smp  | 5         | 7.46%   |
| 5.10.57-antix.1-amd64-smp    | 4         | 5.97%   |
| 4.9.0-326-antix.1-486-smp    | 4         | 5.97%   |
| 5.10.188-antix.1-amd64-smp   | 2         | 2.99%   |
| 5.10.188-antix.1-486-smp     | 2         | 2.99%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 2.99%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 2.99%   |
| 4.9.212-antix.1-486-smp      | 2         | 2.99%   |
| 4.9.200-antix.1-486-smp      | 2         | 2.99%   |
| 6.1.55-antix.1-amd64-smp     | 1         | 1.49%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.49%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.49%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.49%   |
| 4.9.160-antix.2-486-smp      | 1         | 1.49%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.49%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.49%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.49%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.49%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.49%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.49%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 32        | 48.48%  |
| 5.10.142 | 8         | 12.12%  |
| 5.10.57  | 4         | 6.06%   |
| 5.10.188 | 4         | 6.06%   |
| 4.9.212  | 4         | 6.06%   |
| 4.9.235  | 2         | 3.03%   |
| 4.9.200  | 2         | 3.03%   |
| 4.9.160  | 2         | 3.03%   |
| 6.1.55   | 1         | 1.52%   |
| 5.14.0   | 1         | 1.52%   |
| 5.10.88  | 1         | 1.52%   |
| 5.10.27  | 1         | 1.52%   |
| 4.19.202 | 1         | 1.52%   |
| 4.19.100 | 1         | 1.52%   |
| 4.19.0   | 1         | 1.52%   |
| 4.10.5   | 1         | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 42        | 63.64%  |
| 5.10    | 18        | 27.27%  |
| 4.19    | 3         | 4.55%   |
| 6.1     | 1         | 1.52%   |
| 5.14    | 1         | 1.52%   |
| 4.10    | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 54.55%  |
| i686   | 29        | 43.94%  |
| i586   | 1         | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| icewm    | 31        | 46.97%  |
| Unknown  | 27        | 40.91%  |
| jwm      | 2         | 3.03%   |
| fluxbox  | 2         | 3.03%   |
| XFCE     | 1         | 1.52%   |
| LXQt     | 1         | 1.52%   |
| GNOME    | 1         | 1.52%   |
| Cinnamon | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 66        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 37        | 56.06%  |
| SLiM    | 15        | 22.73%  |
| SLIMSKI | 8         | 12.12%  |
| LightDM | 3         | 4.55%   |
| XDM     | 1         | 1.52%   |
| SDDM    | 1         | 1.52%   |
| LXDM    | 1         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 39.39%  |
| ru_RU | 8         | 12.12%  |
| de_DE | 5         | 7.58%   |
| pt_BR | 3         | 4.55%   |
| ja_JP | 3         | 4.55%   |
| it_IT | 3         | 4.55%   |
| es_ES | 3         | 4.55%   |
| nl_NL | 2         | 3.03%   |
| en_AU | 2         | 3.03%   |
| zh_HK | 1         | 1.52%   |
| uk_UA | 1         | 1.52%   |
| pl_PL | 1         | 1.52%   |
| hu_HU | 1         | 1.52%   |
| fr_BE | 1         | 1.52%   |
| es_VE | 1         | 1.52%   |
| es_MX | 1         | 1.52%   |
| en_NZ | 1         | 1.52%   |
| en_GB | 1         | 1.52%   |
| de_AT | 1         | 1.52%   |
| da_DK | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 53        | 80.3%   |
| EFI  | 13        | 19.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 57        | 86.36%  |
| Overlay  | 8         | 12.12%  |
| Reiserfs | 1         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 50        | 75.76%  |
| GPT     | 15        | 22.73%  |
| Unknown | 1         | 1.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 79.1%   |
| Yes       | 14        | 20.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 63.64%  |
| Yes       | 24        | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 15.15%  |
| ASUSTek Computer    | 9         | 13.64%  |
| Acer                | 9         | 13.64%  |
| Lenovo              | 8         | 12.12%  |
| IBM                 | 5         | 7.58%   |
| Fujitsu             | 4         | 6.06%   |
| Dell                | 4         | 6.06%   |
| Toshiba             | 3         | 4.55%   |
| Apple               | 3         | 4.55%   |
| KOHJINSHA           | 2         | 3.03%   |
| Google              | 2         | 3.03%   |
| Samsung Electronics | 1         | 1.52%   |
| Packard Bell        | 1         | 1.52%   |
| MSI                 | 1         | 1.52%   |
| Medion              | 1         | 1.52%   |
| Intel               | 1         | 1.52%   |
| Compaq              | 1         | 1.52%   |
| Unknown             | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 3.03%   |
| HP Mini 110-3700                   | 2         | 3.03%   |
| Fujitsu FMVNU6G1C                  | 2         | 3.03%   |
| Unknown                            | 2         | 3.03%   |
| Toshiba Satellite T110             | 1         | 1.52%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.52%   |
| Toshiba Satellite 1905             | 1         | 1.52%   |
| Samsung SQ1S                       | 1         | 1.52%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.52%   |
| MSI GE62 7RE                       | 1         | 1.52%   |
| Medion WIM2170                     | 1         | 1.52%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.52%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.52%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.52%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.52%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.52%   |
| Lenovo G550 2958                   | 1         | 1.52%   |
| Lenovo 3000 V100 076346G           | 1         | 1.52%   |
| KOHJINSHA SX series                | 1         | 1.52%   |
| KOHJINSHA SC series                | 1         | 1.52%   |
| Intel powered classmate PC         | 1         | 1.52%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.52%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.52%   |
| IBM ThinkPad T40 237342G           | 1         | 1.52%   |
| HP Presario CQ56                   | 1         | 1.52%   |
| HP Pavilion dv2700                 | 1         | 1.52%   |
| HP Mini 5101                       | 1         | 1.52%   |
| HP G5000 (RY492EA#ACB)             | 1         | 1.52%   |
| HP EliteBook 8770w                 | 1         | 1.52%   |
| HP EliteBook 2570p                 | 1         | 1.52%   |
| HP 620                             | 1         | 1.52%   |
| HP 255 G3                          | 1         | 1.52%   |
| Google Lava                        | 1         | 1.52%   |
| Google Candy                       | 1         | 1.52%   |
| Fujitsu FMVS54EB                   | 1         | 1.52%   |
| Fujitsu FMVA05007                  | 1         | 1.52%   |
| Dell Vostro 1015                   | 1         | 1.52%   |
| Dell Latitude E6400                | 1         | 1.52%   |
| Dell Latitude 5480                 | 1         | 1.52%   |
| Dell Latitude 2120                 | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 10.61%  |
| Toshiba Satellite     | 3         | 4.55%   |
| Lenovo IdeaPad        | 3         | 4.55%   |
| IBM ThinkPad          | 3         | 4.55%   |
| HP Mini               | 3         | 4.55%   |
| Dell Latitude         | 3         | 4.55%   |
| Lenovo ThinkPad       | 2         | 3.03%   |
| IBM 260921H           | 2         | 3.03%   |
| HP EliteBook          | 2         | 3.03%   |
| Fujitsu FMVNU6G1C     | 2         | 3.03%   |
| ASUS VivoBook         | 2         | 3.03%   |
| Unknown               | 2         | 3.03%   |
| Samsung SQ1S          | 1         | 1.52%   |
| Packard Bell EasyNote | 1         | 1.52%   |
| MSI GE62              | 1         | 1.52%   |
| Medion WIM2170        | 1         | 1.52%   |
| Lenovo G550           | 1         | 1.52%   |
| Lenovo 3000           | 1         | 1.52%   |
| KOHJINSHA SX          | 1         | 1.52%   |
| KOHJINSHA SC          | 1         | 1.52%   |
| Intel powered         | 1         | 1.52%   |
| HP Presario           | 1         | 1.52%   |
| HP Pavilion           | 1         | 1.52%   |
| HP G5000              | 1         | 1.52%   |
| HP 620                | 1         | 1.52%   |
| HP 255                | 1         | 1.52%   |
| Google Lava           | 1         | 1.52%   |
| Google Candy          | 1         | 1.52%   |
| Fujitsu FMVS54EB      | 1         | 1.52%   |
| Fujitsu FMVA05007     | 1         | 1.52%   |
| Dell Vostro           | 1         | 1.52%   |
| Compaq Tablet         | 1         | 1.52%   |
| ASUS X71SL            | 1         | 1.52%   |
| ASUS X51RL            | 1         | 1.52%   |
| ASUS S3N              | 1         | 1.52%   |
| ASUS A3L              | 1         | 1.52%   |
| ASUS 900HA            | 1         | 1.52%   |
| ASUS 900A             | 1         | 1.52%   |
| ASUS 1011CX           | 1         | 1.52%   |
| Apple MacBookAir6     | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 10        | 15.15%  |
| 2007 | 10        | 15.15%  |
| 2008 | 6         | 9.09%   |
| 2013 | 5         | 7.58%   |
| 2012 | 5         | 7.58%   |
| 2010 | 5         | 7.58%   |
| 2014 | 4         | 6.06%   |
| 2011 | 3         | 4.55%   |
| 2003 | 3         | 4.55%   |
| 2020 | 2         | 3.03%   |
| 2017 | 2         | 3.03%   |
| 2005 | 2         | 3.03%   |
| 2004 | 2         | 3.03%   |
| 1999 | 2         | 3.03%   |
| 2023 | 1         | 1.52%   |
| 2022 | 1         | 1.52%   |
| 2019 | 1         | 1.52%   |
| 2016 | 1         | 1.52%   |
| 2006 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 66        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 66        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 96.97%  |
| Yes  | 2         | 3.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 22        | 33.33%  |
| 0.51-1.0   | 12        | 18.18%  |
| 1.01-2.0   | 10        | 15.15%  |
| 2.01-3.0   | 9         | 13.64%  |
| 4.01-8.0   | 4         | 6.06%   |
| 0.01-0.5   | 4         | 6.06%   |
| 32.01-64.0 | 2         | 3.03%   |
| 8.01-16.0  | 2         | 3.03%   |
| 16.01-24.0 | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 25        | 37.31%  |
| 0.51-1.0 | 24        | 35.82%  |
| 1.01-2.0 | 12        | 17.91%  |
| 2.01-3.0 | 6         | 8.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 82.09%  |
| 2      | 9         | 13.43%  |
| 3      | 2         | 2.99%   |
| 0      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 53.03%  |
| Yes       | 31        | 46.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 80.3%   |
| No        | 13        | 19.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 96.97%  |
| No        | 2         | 3.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 54.55%  |
| Yes       | 30        | 45.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 15.15%  |
| Russia      | 9         | 13.64%  |
| Hong Kong   | 9         | 13.64%  |
| Germany     | 6         | 9.09%   |
| Netherlands | 3         | 4.55%   |
| Japan       | 3         | 4.55%   |
| Italy       | 3         | 4.55%   |
| Brazil      | 3         | 4.55%   |
| Spain       | 2         | 3.03%   |
| Poland      | 2         | 3.03%   |
| Hungary     | 2         | 3.03%   |
| Denmark     | 2         | 3.03%   |
| Australia   | 2         | 3.03%   |
| Uruguay     | 1         | 1.52%   |
| Ukraine     | 1         | 1.52%   |
| New Zealand | 1         | 1.52%   |
| Mexico      | 1         | 1.52%   |
| Kenya       | 1         | 1.52%   |
| Kazakhstan  | 1         | 1.52%   |
| Chile       | 1         | 1.52%   |
| Bulgaria    | 1         | 1.52%   |
| Belgium     | 1         | 1.52%   |
| Austria     | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 8.82%   |
| Sydney                    | 2         | 2.94%   |
| St Petersburg             | 2         | 2.94%   |
| Moscow                    | 2         | 2.94%   |
| Central                   | 2         | 2.94%   |
| Yuzhno-Sakhalinsk         | 1         | 1.47%   |
| Yokohama                  | 1         | 1.47%   |
| Ybbs an der Donau         | 1         | 1.47%   |
| Whitney                   | 1         | 1.47%   |
| Warsaw                    | 1         | 1.47%   |
| Tver                      | 1         | 1.47%   |
| Trecate                   | 1         | 1.47%   |
| Torricella Sicura         | 1         | 1.47%   |
| Toms River                | 1         | 1.47%   |
| Sofia                     | 1         | 1.47%   |
| Sheung Shui               | 1         | 1.47%   |
| Seattle                   | 1         | 1.47%   |
| Schloss Holte-Stukenbrock | 1         | 1.47%   |
| Santiago                  | 1         | 1.47%   |
| Salto                     | 1         | 1.47%   |
| Rotterdam                 | 1         | 1.47%   |
| Reutlingen                | 1         | 1.47%   |
| Purmerend                 | 1         | 1.47%   |
| Pritzwalk                 | 1         | 1.47%   |
| Portland                  | 1         | 1.47%   |
| Pomaz                     | 1         | 1.47%   |
| Norden                    | 1         | 1.47%   |
| Neyagawa                  | 1         | 1.47%   |
| Nairobi                   | 1         | 1.47%   |
| Montevideo                | 1         | 1.47%   |
| Mittegrossefehn           | 1         | 1.47%   |
| Milan                     | 1         | 1.47%   |
| Mechanicsburg             | 1         | 1.47%   |
| Marcinelle                | 1         | 1.47%   |
| Karaganda                 | 1         | 1.47%   |
| Jonesboro                 | 1         | 1.47%   |
| Hudson                    | 1         | 1.47%   |
| Hortolândia              | 1         | 1.47%   |
| Hobbs                     | 1         | 1.47%   |
| Hagenbach                 | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 19.18%  |
| WDC                 | 12        | 12     | 16.44%  |
| Hitachi             | 12        | 12     | 16.44%  |
| Toshiba             | 6         | 6      | 8.22%   |
| Samsung Electronics | 5         | 5      | 6.85%   |
| Unknown             | 4         | 4      | 5.48%   |
| Kingston            | 2         | 2      | 2.74%   |
| HGST                | 2         | 2      | 2.74%   |
| Zheino              | 1         | 1      | 1.37%   |
| Unknown (CF)        | 1         | 1      | 1.37%   |
| Transcend           | 1         | 1      | 1.37%   |
| RECADATA            | 1         | 1      | 1.37%   |
| PNY                 | 1         | 1      | 1.37%   |
| OCZ                 | 1         | 1      | 1.37%   |
| Maxtor              | 1         | 1      | 1.37%   |
| Intel               | 1         | 1      | 1.37%   |
| IBM/Hitachi         | 1         | 1      | 1.37%   |
| Hewlett-Packard     | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |
| BIWIN               | 1         | 1      | 1.37%   |
| BHT                 | 1         | 3      | 1.37%   |
| ASUS-PHISON         | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |
| Unknown             | 1         | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2.74%   |
| Seagate ST980811AS 80GB                 | 2         | 2.74%   |
| Samsung SSD 750 EVO 120GB               | 2         | 2.74%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.74%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 2.74%   |
| Zheino CHN-mSATAM3-128 128GB SSD        | 1         | 1.37%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.37%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.37%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.37%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.37%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.37%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.37%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 1.37%   |
| WDC WD1600BEVT-00M9YT0 160GB            | 1         | 1.37%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.37%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.37%   |
| Unknown SR64G  64GB                     | 1         | 1.37%   |
| Unknown SD16G  16GB                     | 1         | 1.37%   |
| Unknown hB8aP  32GB                     | 1         | 1.37%   |
| Unknown HAG2e  16GB                     | 1         | 1.37%   |
| Unknown (CF) Card 32GB                  | 1         | 1.37%   |
| Transcend SSD 2GB                       | 1         | 1.37%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.37%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.37%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.37%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.37%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.37%   |
| Toshiba MK2555GSX 250GB                 | 1         | 1.37%   |
| Seagate ST980812AS 80GB                 | 1         | 1.37%   |
| Seagate ST9320325AS 320GB               | 1         | 1.37%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.37%   |
| Seagate ST9250315AS 250GB               | 1         | 1.37%   |
| Seagate ST9160411AS 160GB               | 1         | 1.37%   |
| Seagate ST9160314AS 40GB                | 1         | 1.37%   |
| Seagate ST9160310AS 160GB               | 1         | 1.37%   |
| Seagate ST9160301AS 160GB               | 1         | 1.37%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.37%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.37%   |
| Seagate ST320LT012-1DG14C 320GB         | 1         | 1.37%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 29.79%  |
| WDC                 | 12        | 12     | 25.53%  |
| Hitachi             | 12        | 12     | 25.53%  |
| Toshiba             | 4         | 4      | 8.51%   |
| HGST                | 2         | 2      | 4.26%   |
| Samsung Electronics | 1         | 1      | 2.13%   |
| IBM/Hitachi         | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Zheino              | 1         | 1      | 4.76%   |
| Unknown (CF)        | 1         | 1      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| RECADATA            | 1         | 1      | 4.76%   |
| PNY                 | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Maxtor              | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |
| BIWIN               | 1         | 1      | 4.76%   |
| BHT                 | 1         | 3      | 4.76%   |
| ASUS-PHISON         | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |
| Unknown             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 47     | 65.71%  |
| SSD  | 19        | 23     | 27.14%  |
| MMC  | 4         | 4      | 5.71%   |
| NVMe | 1         | 1      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 70     | 92.54%  |
| MMC  | 4         | 4      | 5.97%   |
| NVMe | 1         | 1      | 1.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 65     | 92.19%  |
| 0.51-1.0   | 5         | 5      | 7.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 24        | 35.29%  |
| 1-20       | 17        | 25%     |
| 51-100     | 10        | 14.71%  |
| 21-50      | 8         | 11.76%  |
| 251-500    | 6         | 8.82%   |
| 501-1000   | 2         | 2.94%   |
| Unknown    | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 50        | 75.76%  |
| 21-50   | 8         | 12.12%  |
| 101-250 | 4         | 6.06%   |
| 51-100  | 3         | 4.55%   |
| Unknown | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST980811AS 80GB         | 2         | 2      | 8%      |
| Hitachi HTS542525K9SA00 250GB   | 2         | 2      | 8%      |
| WDC WD5000LPVX-22V0TT0 500GB    | 1         | 1      | 4%      |
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 4%      |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 4%      |
| WDC WD2500BEVT-22ZCT0 250GB     | 1         | 1      | 4%      |
| WDC WD1600BEVT-00M9YT0 160GB    | 1         | 1      | 4%      |
| Toshiba MK2555GSX 250GB         | 1         | 1      | 4%      |
| Seagate ST980812AS 80GB         | 1         | 1      | 4%      |
| Seagate ST9320325AS 320GB       | 1         | 1      | 4%      |
| Seagate ST9250315AS 250GB       | 1         | 1      | 4%      |
| Seagate ST9160314AS 40GB        | 1         | 1      | 4%      |
| Seagate ST9160310AS 160GB       | 1         | 1      | 4%      |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 4%      |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 4%      |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 4%      |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 4%      |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 4%      |
| Hitachi HTS543225A7A384 250GB   | 1         | 1      | 4%      |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 4%      |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 4%      |
| BIWIN SSD 32GB                  | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 36%     |
| Seagate | 8         | 8      | 32%     |
| WDC     | 5         | 5      | 20%     |
| Toshiba | 1         | 1      | 4%      |
| HGST    | 1         | 1      | 4%      |
| BIWIN   | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 37.5%   |
| Seagate | 8         | 8      | 33.33%  |
| WDC     | 5         | 5      | 20.83%  |
| Toshiba | 1         | 1      | 4.17%   |
| HGST    | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 24     | 96%     |
| SSD  | 1         | 1      | 4%      |

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
| Works    | 37        | 44     | 54.41%  |
| Malfunc  | 25        | 25     | 36.76%  |
| Detected | 6         | 6      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 77.61%  |
| AMD                              | 5         | 7.46%   |
| VIA Technologies                 | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] | 2         | 2.99%   |
| Nvidia                           | 2         | 2.99%   |
| Silicon Image                    | 1         | 1.49%   |
| Samsung Electronics              | 1         | 1.49%   |
| Marvell Technology Group         | 1         | 1.49%   |
| JMicron Technology               | 1         | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 8.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 6.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 6.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 5         | 6.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 5%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 5%      |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 5%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 3.75%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.75%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.5%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.5%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.25%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 1.25%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.25%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.25%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.25%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.25%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.25%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.25%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.25%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.25%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.25%   |
| AMD SB600 IDE                                                                  | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 39        | 52.7%   |
| IDE  | 31        | 41.89%  |
| RAID | 3         | 4.05%   |
| NVMe | 1         | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 59        | 89.39%  |
| AMD          | 5         | 7.58%   |
| GenuineTMx86 | 1         | 1.52%   |
| CentaurHauls | 1         | 1.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 9.09%   |
| Intel Pentium M processor 1.60GHz           | 2         | 3.03%   |
| Intel Pentium M processor 1.00GHz           | 2         | 3.03%   |
| Intel Genuine processor 800MHz              | 2         | 3.03%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 3.03%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 3.03%   |
| Intel Celeron (Mendocino)                   | 2         | 3.03%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.03%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.03%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 3.03%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.52%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.52%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.52%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.52%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.52%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.52%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.52%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.52%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.52%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.52%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.52%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.52%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.52%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.52%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.52%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.52%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.52%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 1.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.52%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.52%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 14        | 21.21%  |
| Intel Celeron           | 8         | 12.12%  |
| Intel Core 2 Duo        | 7         | 10.61%  |
| Intel Pentium M         | 6         | 9.09%   |
| Intel Genuine           | 5         | 7.58%   |
| Intel Core i7           | 5         | 7.58%   |
| Intel Core i5           | 5         | 7.58%   |
| Intel Core i3           | 4         | 6.06%   |
| AMD E2                  | 2         | 3.03%   |
| Other                   | 1         | 1.52%   |
| Intel Pentium Silver    | 1         | 1.52%   |
| Intel Pentium Dual-Core | 1         | 1.52%   |
| Intel Pentium Dual      | 1         | 1.52%   |
| Intel Pentium 4         | 1         | 1.52%   |
| Intel Celeron Dual-Core | 1         | 1.52%   |
| CentaurHauls VIA Nano   | 1         | 1.52%   |
| AMD E1                  | 1         | 1.52%   |
| AMD Athlon II           | 1         | 1.52%   |
| AMD Athlon 64 X2        | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 53.03%  |
| 1      | 27        | 40.91%  |
| 4      | 4         | 6.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 57.58%  |
| 2      | 28        | 42.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 63.64%  |
| 32-bit         | 24        | 36.36%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 9         | 13.64%  |
| 0x1067a    | 7         | 10.61%  |
| 0x6fd      | 4         | 6.06%   |
| 0x6d6      | 4         | 6.06%   |
| 0x6d8      | 3         | 4.55%   |
| 0x40651    | 3         | 4.55%   |
| 0x306a9    | 3         | 4.55%   |
| 0x106ca    | 3         | 4.55%   |
| Unknown    | 3         | 4.55%   |
| 0x6e8      | 2         | 3.03%   |
| 0x66a      | 2         | 3.03%   |
| 0x306c3    | 2         | 3.03%   |
| 0x30678    | 2         | 3.03%   |
| 0x30661    | 2         | 3.03%   |
| 0x206a7    | 2         | 3.03%   |
| 0x10661    | 2         | 3.03%   |
| 0xf24      | 1         | 1.52%   |
| 0x906e9    | 1         | 1.52%   |
| 0x806e9    | 1         | 1.52%   |
| 0x706a8    | 1         | 1.52%   |
| 0x706a1    | 1         | 1.52%   |
| 0x695      | 1         | 1.52%   |
| 0x506c9    | 1         | 1.52%   |
| 0x20655    | 1         | 1.52%   |
| 0x20652    | 1         | 1.52%   |
| 0x07030106 | 1         | 1.52%   |
| 0x0700010f | 1         | 1.52%   |
| 0x06006704 | 1         | 1.52%   |
| 0x010000c8 | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 14        | 21.21%  |
| P6            | 10        | 15.15%  |
| Penryn        | 7         | 10.61%  |
| Core          | 6         | 9.09%   |
| Haswell       | 5         | 7.58%   |
| Unknown       | 4         | 6.06%   |
| IvyBridge     | 3         | 4.55%   |
| Westmere      | 2         | 3.03%   |
| Silvermont    | 2         | 3.03%   |
| SandyBridge   | 2         | 3.03%   |
| KabyLake      | 2         | 3.03%   |
| Goldmont plus | 2         | 3.03%   |
| Puma          | 1         | 1.52%   |
| NetBurst      | 1         | 1.52%   |
| K8 Hammer     | 1         | 1.52%   |
| K10           | 1         | 1.52%   |
| Jaguar        | 1         | 1.52%   |
| Goldmont      | 1         | 1.52%   |
| Excavator     | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 65.22%  |
| AMD                              | 11        | 15.94%  |
| Nvidia                           | 9         | 13.04%  |
| Neomagic                         | 2         | 2.9%    |
| VIA Technologies                 | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] | 1         | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 11        | 13.41%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 7         | 8.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 5         | 6.1%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 4.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 3.66%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 3.66%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.44%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.44%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 2.44%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.44%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.44%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.22%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.22%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.22%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.22%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.22%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.22%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.22%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.22%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.22%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.22%   |
| Intel HD Graphics 630                                                         | 1         | 1.22%   |
| Intel HD Graphics 620                                                         | 1         | 1.22%   |
| Intel HD Graphics 500                                                         | 1         | 1.22%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.22%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.22%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.22%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.22%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.22%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 57.58%  |
| 1 x AMD        | 11        | 16.67%  |
| 1 x Nvidia     | 6         | 9.09%   |
| Intel + Nvidia | 3         | 4.55%   |
| Other          | 2         | 3.03%   |
| 2 x Intel      | 2         | 3.03%   |
| 1 x Neomagic   | 2         | 3.03%   |
| 1 x VIA        | 1         | 1.52%   |
| 1 x SiS        | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 86.36%  |
| Unknown     | 7         | 10.61%  |
| Proprietary | 2         | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 28        | 42.42%  |
| Unknown    | 28        | 42.42%  |
| 1.01-2.0   | 8         | 12.12%  |
| 3.01-4.0   | 1         | 1.52%   |
| 0.51-1.0   | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 25%     |
| LG Display              | 10        | 20.83%  |
| Samsung Electronics     | 5         | 10.42%  |
| LG Philips              | 4         | 8.33%   |
| Chimei Innolux          | 4         | 8.33%   |
| HannStar                | 3         | 6.25%   |
| Apple                   | 3         | 6.25%   |
| Lenovo                  | 2         | 4.17%   |
| InfoVision              | 1         | 2.08%   |
| HJW                     | 1         | 2.08%   |
| CPT                     | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| BOE                     | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 4.17%   |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 1         | 2.08%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.08%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 2.08%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.08%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 2.08%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.08%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.08%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.08%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.08%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1144 1366x768 256x144mm 11.6-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 20        | 42.55%  |
| 1280x800 (WXGA)   | 7         | 14.89%  |
| 1024x600          | 7         | 14.89%  |
| 1920x1080 (FHD)   | 6         | 12.77%  |
| 1440x900 (WXGA+)  | 3         | 6.38%   |
| 2288x1287         | 1         | 2.13%   |
| 1920x1200 (WUXGA) | 1         | 2.13%   |
| 1600x900 (HD+)    | 1         | 2.13%   |
| 1280x720 (HD)     | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 35.42%  |
| 10     | 7         | 14.58%  |
| 14     | 5         | 10.42%  |
| 11     | 5         | 10.42%  |
| 13     | 4         | 8.33%   |
| 17     | 3         | 6.25%   |
| 12     | 2         | 4.17%   |
| 8      | 2         | 4.17%   |
| 32     | 1         | 2.08%   |
| 24     | 1         | 2.08%   |
| 18     | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 47.92%  |
| 201-300     | 17        | 35.42%  |
| 351-400     | 4         | 8.33%   |
| 101-200     | 2         | 4.17%   |
| 701-800     | 1         | 2.08%   |
| 501-600     | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 73.91%  |
| 16/10 | 11        | 23.91%  |
| 3/2   | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 35.42%  |
| 81-90          | 7         | 14.58%  |
| 41-50          | 7         | 14.58%  |
| 51-60          | 5         | 10.42%  |
| 71-80          | 2         | 4.17%   |
| 61-70          | 2         | 4.17%   |
| 1-40           | 2         | 4.17%   |
| 131-140        | 2         | 4.17%   |
| 351-500        | 1         | 2.08%   |
| 201-250        | 1         | 2.08%   |
| 141-150        | 1         | 2.08%   |
| 121-130        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 45.83%  |
| 121-160 | 17        | 35.42%  |
| 51-100  | 9         | 18.75%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 89.55%  |
| 0     | 4         | 5.97%   |
| 2     | 3         | 4.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 28        | 26.67%  |
| Realtek Semiconductor            | 22        | 20.95%  |
| Intel                            | 22        | 20.95%  |
| Broadcom                         | 16        | 15.24%  |
| Marvell Technology Group         | 3         | 2.86%   |
| Silicon Integrated Systems [SiS] | 2         | 1.9%    |
| Ralink                           | 2         | 1.9%    |
| Nvidia                           | 2         | 1.9%    |
| Broadcom Limited                 | 2         | 1.9%    |
| Texas Instruments                | 1         | 0.95%   |
| Qualcomm Atheros Communications  | 1         | 0.95%   |
| MediaTek                         | 1         | 0.95%   |
| Hewlett-Packard                  | 1         | 0.95%   |
| Attansic Technology              | 1         | 0.95%   |
| ASIX Electronics                 | 1         | 0.95%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 10        | 7.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 7.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 4.72%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 3.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 3.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 3.15%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3         | 2.36%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.36%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.36%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.57%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 2         | 1.57%   |
| Intel Wireless 7260                                                           | 2         | 1.57%   |
| Intel WiFi Link 5100                                                          | 2         | 1.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.57%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 1.57%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 1.57%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.79%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 0.79%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.79%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.79%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.79%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 25        | 37.31%  |
| Intel                           | 20        | 29.85%  |
| Broadcom                        | 12        | 17.91%  |
| Realtek Semiconductor           | 4         | 5.97%   |
| Ralink                          | 2         | 2.99%   |
| Texas Instruments               | 1         | 1.49%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| MediaTek                        | 1         | 1.49%   |
| Broadcom Limited                | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 10        | 14.71%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 5.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 4.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 4.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 4.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.94%   |
| Intel Wireless 7260                                                           | 2         | 2.94%   |
| Intel WiFi Link 5100                                                          | 2         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.94%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.94%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 2.94%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.47%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.47%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.47%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.47%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.47%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.47%   |
| Intel Wireless 7265                                                           | 1         | 1.47%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.47%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.47%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.47%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.47%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 20        | 37.74%  |
| Intel                            | 10        | 18.87%  |
| Broadcom                         | 7         | 13.21%  |
| Qualcomm Atheros                 | 6         | 11.32%  |
| Marvell Technology Group         | 3         | 5.66%   |
| Silicon Integrated Systems [SiS] | 2         | 3.77%   |
| Nvidia                           | 2         | 3.77%   |
| Broadcom Limited                 | 1         | 1.89%   |
| Attansic Technology              | 1         | 1.89%   |
| ASIX Electronics                 | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 16.98%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 11.32%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 9.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 5.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 3.77%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 3.77%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 3.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.89%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.89%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.89%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.89%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.89%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.89%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.89%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 52.03%  |
| Ethernet | 53        | 43.09%  |
| Modem    | 6         | 4.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 85.07%  |
| Ethernet | 10        | 14.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 75.76%  |
| 1     | 16        | 24.24%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 79.1%   |
| Yes  | 14        | 20.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Broadcom                        | 8         | 27.59%  |
| Intel                           | 5         | 17.24%  |
| Apple                           | 3         | 10.34%  |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| Lite-On Technology              | 2         | 6.9%    |
| IMC Networks                    | 2         | 6.9%    |
| Taiyo Yuden                     | 1         | 3.45%   |
| Realtek Semiconductor           | 1         | 3.45%   |
| Ralink Technology               | 1         | 3.45%   |
| Fujitsu                         | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| ASUSTek Computer                | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 10.34%  |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 6.9%    |
| IMC Networks Bluetooth Device                       | 2         | 6.9%    |
| Broadcom HP Portable SoftSailing                    | 2         | 6.9%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 6.9%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 3.45%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.45%   |
| Fujitsu Bluetooth Device                            | 1         | 3.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.45%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.45%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 3.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.45%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.45%   |
| Apple Bluetooth Host Controller                     | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 76.81%  |
| AMD                              | 7         | 10.14%  |
| Nvidia                           | 3         | 4.35%   |
| VIA Technologies                 | 2         | 2.9%    |
| Silicon Integrated Systems [SiS] | 2         | 2.9%    |
| ESS Technology                   | 2         | 2.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 20.78%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 6.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 5.19%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 5.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.9%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.9%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.6%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.6%    |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.6%    |
| AMD FCH Azalia Controller                                                  | 2         | 2.6%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.3%    |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.3%    |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.3%    |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.3%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.3%    |
| Intel CM238 HD Audio Controller                                            | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.3%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.3%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.3%    |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.3%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.3%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.3%    |
| AMD High Definition Audio Controller                                       | 1         | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 27        | 37.5%   |
| SK hynix            | 15        | 20.83%  |
| Samsung Electronics | 9         | 12.5%   |
| Unknown             | 7         | 9.72%   |
| Micron Technology   | 5         | 6.94%   |
| Kingston            | 3         | 4.17%   |
| Crucial             | 2         | 2.78%   |
| Unknown (8A02)      | 1         | 1.39%   |
| Kingmax             | 1         | 1.39%   |
| fef5                | 1         | 1.39%   |
| Avant               | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 7         | 9.09%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 3.9%    |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.6%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 2.6%    |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.6%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 2.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 2.6%    |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s       | 2         | 2.6%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s               | 2         | 2.6%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 2         | 2.6%    |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.3%    |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.3%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.3%    |
| Unknown RAM Module 512MB SODIMM DDR2                           | 1         | 1.3%    |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.3%    |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.3%    |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.3%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.3%    |
| Unknown RAM Module 1GB SODIMM SDRAM                            | 1         | 1.3%    |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.3%    |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.3%    |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.3%    |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.3%    |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.3%    |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.3%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.3%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.3%    |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.3%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s          | 1         | 1.3%    |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.3%    |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.3%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.3%    |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.3%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 33.85%  |
| DDR2    | 14        | 21.54%  |
| SDRAM   | 13        | 20%     |
| DDR4    | 5         | 7.69%   |
| DDR     | 5         | 7.69%   |
| DRAM    | 4         | 6.15%   |
| LPDDR4  | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 92.06%  |
| DIMM         | 3         | 4.76%   |
| Row Of Chips | 1         | 1.59%   |
| Unknown      | 1         | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 25        | 34.25%  |
| 1024  | 18        | 24.66%  |
| 4096  | 13        | 17.81%  |
| 512   | 6         | 8.22%   |
| 8192  | 4         | 5.48%   |
| 256   | 3         | 4.11%   |
| 64    | 2         | 2.74%   |
| 16384 | 1         | 1.37%   |
| 232   | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 31.82%  |
| 1600    | 13        | 19.7%   |
| 1067    | 5         | 7.58%   |
| 533     | 5         | 7.58%   |
| 4199    | 3         | 4.55%   |
| 2400    | 3         | 4.55%   |
| 1334    | 2         | 3.03%   |
| 1333    | 2         | 3.03%   |
| 800     | 2         | 3.03%   |
| 667     | 2         | 3.03%   |
| 200     | 2         | 3.03%   |
| 3266    | 1         | 1.52%   |
| 3200    | 1         | 1.52%   |
| 2667    | 1         | 1.52%   |
| 1866    | 1         | 1.52%   |
| 975     | 1         | 1.52%   |
| 266     | 1         | 1.52%   |

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
| Chicony Electronics                    | 10        | 23.26%  |
| Suyin                                  | 5         | 11.63%  |
| Microdia                               | 4         | 9.3%    |
| IMC Networks                           | 4         | 9.3%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.3%    |
| Acer                                   | 3         | 6.98%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Silicon Motion                         | 2         | 4.65%   |
| Pixart Imaging                         | 2         | 4.65%   |
| Apple                                  | 2         | 4.65%   |
| Syntek                                 | 1         | 2.33%   |
| Realtek Semiconductor                  | 1         | 2.33%   |
| Lenovo                                 | 1         | 2.33%   |
| Importek                               | 1         | 2.33%   |
| Bison Electronics                      | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                           | 3         | 6.98%   |
| Suyin USB 2.0 Camera                                    | 2         | 4.65%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 4.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.65%   |
| Chicony HD WebCam                                       | 2         | 4.65%   |
| Syntek Integrated Camera                                | 1         | 2.33%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.33%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.33%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.33%   |
| Sunplus HD WebCam                                       | 1         | 2.33%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.33%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.33%   |
| Realtek HD WebCam                                       | 1         | 2.33%   |
| Microdia Integrated Webcam                              | 1         | 2.33%   |
| Lenovo Integrated Webcam                                | 1         | 2.33%   |
| Importek FJ Camera                                      | 1         | 2.33%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.33%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.33%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.33%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.33%   |
| Chicony HP Webcam                                       | 1         | 2.33%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.33%   |
| Chicony EasyCamera                                      | 1         | 2.33%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.33%   |
| Chicony CNF7050                                         | 1         | 2.33%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.33%   |
| Bison BisonCam, NB Pro                                  | 1         | 2.33%   |
| Apple FaceTime Camera                                   | 1         | 2.33%   |
| Apple Built-in iSight                                   | 1         | 2.33%   |
| Acer Lenovo EasyCamera                                  | 1         | 2.33%   |
| Acer Crystal Eye Webcam                                 | 1         | 2.33%   |
| Acer BisonCam, NB Pro                                   | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 5         | 71.43%  |
| Validity Sensors | 1         | 14.29%  |
| Upek             | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 42.86%  |
| AuthenTec AES1600                                      | 2         | 28.57%  |
| Validity Sensors VFS491                                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |

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


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 45        | 68.18%  |
| 1     | 19        | 28.79%  |
| 3     | 1         | 1.52%   |
| 2     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 13        | 59.09%  |
| Fingerprint reader    | 7         | 31.82%  |
| Multimedia controller | 1         | 4.55%   |
| Chipcard              | 1         | 4.55%   |


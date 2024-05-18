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

Total: 101

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S12 20021,2959      | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| HP            | Compaq 8510w                | [6761a4250d](https://linux-hardware.org/?probe=6761a4250d) | Apr 27, 2024 |
| Lenovo        | ThinkPad SL500 27463ZG      | [e1df9eba9c](https://linux-hardware.org/?probe=e1df9eba9c) | Apr 24, 2024 |
| Clevo         | M66xN                       | [e25bed6466](https://linux-hardware.org/?probe=e25bed6466) | Apr 19, 2024 |
| Unknown       | TK23D                       | [47ffc66996](https://linux-hardware.org/?probe=47ffc66996) | Apr 05, 2024 |
| Dell          | Latitude 5480               | [995ea90b66](https://linux-hardware.org/?probe=995ea90b66) | Apr 05, 2024 |
| Apple         | MacBookAir6,2               | [7ad5a4d115](https://linux-hardware.org/?probe=7ad5a4d115) | Mar 14, 2024 |
| Fujitsu       | FARQ10003                   | [c65688098c](https://linux-hardware.org/?probe=c65688098c) | Mar 13, 2024 |
| Lenovo        | IdeaPad Y460                | [0af494c148](https://linux-hardware.org/?probe=0af494c148) | Mar 10, 2024 |
| Lenovo        | G560 20042                  | [d7fffe52e5](https://linux-hardware.org/?probe=d7fffe52e5) | Mar 05, 2024 |
| Sony          | VGN-TX690P                  | [2cb1120670](https://linux-hardware.org/?probe=2cb1120670) | Feb 20, 2024 |
| Dell          | Latitude E6500              | [58652601f6](https://linux-hardware.org/?probe=58652601f6) | Feb 17, 2024 |
| Dell          | Latitude E6500              | [1ffdcc3b16](https://linux-hardware.org/?probe=1ffdcc3b16) | Feb 17, 2024 |
| Lenovo        | S10-3                       | [e9d3156b70](https://linux-hardware.org/?probe=e9d3156b70) | Feb 09, 2024 |
| Apple         | MacBookPro1,2               | [5e40347a6e](https://linux-hardware.org/?probe=5e40347a6e) | Feb 01, 2024 |
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
| antiX 21       | 25        | 32.47%  |
| antiX 22       | 21        | 27.27%  |
| antiX 23       | 9         | 11.69%  |
| antiX 19.2     | 6         | 7.79%   |
| antiX 23.1     | 3         | 3.9%    |
| antiX 19.3     | 3         | 3.9%    |
| antiX 21-runit | 2         | 2.6%    |
| antiX 19.4     | 2         | 2.6%    |
| antiX 19.1     | 2         | 2.6%    |
| antiX 19.5     | 1         | 1.3%    |
| antiX 17.4.1   | 1         | 1.3%    |
| antiX 17.2.1   | 1         | 1.3%    |
| antiX 17       | 1         | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 15        | 19.48%  |
| 5.10.142-antix.2-amd64-smp   | 8         | 10.39%  |
| 4.9.0-326-antix.1-amd64-smp  | 8         | 10.39%  |
| 4.9.0-279-antix.1-amd64-smp  | 6         | 7.79%   |
| 4.9.0-326-antix.1-486-smp    | 5         | 6.49%   |
| 5.10.57-antix.1-amd64-smp    | 4         | 5.19%   |
| 5.10.188-antix.1-486-smp     | 3         | 3.9%    |
| 6.1.60-antix.1-amd64-smp     | 2         | 2.6%    |
| 6.1.55-antix.1-amd64-smp     | 2         | 2.6%    |
| 6.1.42-antix.1-amd64-smp     | 2         | 2.6%    |
| 5.10.188-antix.1-amd64-smp   | 2         | 2.6%    |
| 4.9.235-antix.1-amd64-smp    | 2         | 2.6%    |
| 4.9.212-antix.1-amd64-smp    | 2         | 2.6%    |
| 4.9.212-antix.1-486-smp      | 2         | 2.6%    |
| 4.9.200-antix.1-486-smp      | 2         | 2.6%    |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.3%    |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.3%    |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.3%    |
| 5.10.197-antix.1-486-smp     | 1         | 1.3%    |
| 4.9.160-antix.2-486-smp      | 1         | 1.3%    |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.3%    |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.3%    |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.3%    |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.3%    |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.3%    |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.3%    |
| 4.10.5-antix.1-486-smp       | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 35        | 46.05%  |
| 5.10.142 | 8         | 10.53%  |
| 5.10.188 | 5         | 6.58%   |
| 5.10.57  | 4         | 5.26%   |
| 4.9.212  | 4         | 5.26%   |
| 6.1.60   | 2         | 2.63%   |
| 6.1.55   | 2         | 2.63%   |
| 6.1.42   | 2         | 2.63%   |
| 4.9.235  | 2         | 2.63%   |
| 4.9.200  | 2         | 2.63%   |
| 4.9.160  | 2         | 2.63%   |
| 5.14.0   | 1         | 1.32%   |
| 5.10.88  | 1         | 1.32%   |
| 5.10.27  | 1         | 1.32%   |
| 5.10.197 | 1         | 1.32%   |
| 4.19.202 | 1         | 1.32%   |
| 4.19.100 | 1         | 1.32%   |
| 4.19.0   | 1         | 1.32%   |
| 4.10.5   | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 45        | 59.21%  |
| 5.10    | 20        | 26.32%  |
| 6.1     | 6         | 7.89%   |
| 4.19    | 3         | 3.95%   |
| 5.14    | 1         | 1.32%   |
| 4.10    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 56.58%  |
| i686   | 32        | 42.11%  |
| i586   | 1         | 1.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| icewm    | 38        | 49.35%  |
| Unknown  | 28        | 36.36%  |
| fluxbox  | 4         | 5.19%   |
| jwm      | 2         | 2.6%    |
| GNOME    | 2         | 2.6%    |
| XFCE     | 1         | 1.3%    |
| LXQt     | 1         | 1.3%    |
| Cinnamon | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 75        | 98.68%  |
| Unknown | 1         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 52.63%  |
| SLIMSKI | 15        | 19.74%  |
| SLiM    | 15        | 19.74%  |
| LightDM | 3         | 3.95%   |
| XDM     | 1         | 1.32%   |
| SDDM    | 1         | 1.32%   |
| LXDM    | 1         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 30        | 39.47%  |
| ru_RU | 8         | 10.53%  |
| de_DE | 6         | 7.89%   |
| it_IT | 4         | 5.26%   |
| es_ES | 4         | 5.26%   |
| pt_BR | 3         | 3.95%   |
| ja_JP | 3         | 3.95%   |
| nl_NL | 2         | 2.63%   |
| fr_FR | 2         | 2.63%   |
| en_GB | 2         | 2.63%   |
| en_AU | 2         | 2.63%   |
| zh_HK | 1         | 1.32%   |
| uk_UA | 1         | 1.32%   |
| pl_PL | 1         | 1.32%   |
| hu_HU | 1         | 1.32%   |
| fr_BE | 1         | 1.32%   |
| es_VE | 1         | 1.32%   |
| es_MX | 1         | 1.32%   |
| en_NZ | 1         | 1.32%   |
| de_AT | 1         | 1.32%   |
| da_DK | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 61        | 80.26%  |
| EFI  | 15        | 19.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 68        | 89.47%  |
| Overlay  | 7         | 9.21%   |
| Reiserfs | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 57        | 75%     |
| GPT     | 18        | 23.68%  |
| Unknown | 1         | 1.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 80.52%  |
| Yes       | 15        | 19.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 64.47%  |
| Yes       | 27        | 35.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 15.79%  |
| Hewlett-Packard     | 11        | 14.47%  |
| ASUSTek Computer    | 9         | 11.84%  |
| Acer                | 9         | 11.84%  |
| Dell                | 6         | 7.89%   |
| IBM                 | 5         | 6.58%   |
| Fujitsu             | 4         | 5.26%   |
| Apple               | 4         | 5.26%   |
| Toshiba             | 3         | 3.95%   |
| KOHJINSHA           | 2         | 2.63%   |
| Google              | 2         | 2.63%   |
| Sony                | 1         | 1.32%   |
| Samsung Electronics | 1         | 1.32%   |
| Packard Bell        | 1         | 1.32%   |
| MSI                 | 1         | 1.32%   |
| Medion              | 1         | 1.32%   |
| Intel               | 1         | 1.32%   |
| Compaq              | 1         | 1.32%   |
| Clevo               | 1         | 1.32%   |
| Unknown             | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 2.63%   |
| HP Mini 110-3700                   | 2         | 2.63%   |
| Fujitsu FMVNU6G1C                  | 2         | 2.63%   |
| Dell Latitude 5480                 | 2         | 2.63%   |
| Unknown                            | 2         | 2.63%   |
| Toshiba Satellite T110             | 1         | 1.32%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.32%   |
| Toshiba Satellite 1905             | 1         | 1.32%   |
| Sony VGN-TX690P                    | 1         | 1.32%   |
| Samsung SQ1S                       | 1         | 1.32%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.32%   |
| MSI GE62 7RE                       | 1         | 1.32%   |
| Medion WIM2170                     | 1         | 1.32%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.32%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.32%   |
| Lenovo ThinkPad SL500 27463ZG      | 1         | 1.32%   |
| Lenovo S10-3                       | 1         | 1.32%   |
| Lenovo IdeaPad Y460                | 1         | 1.32%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.32%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.32%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.32%   |
| Lenovo G560 20042                  | 1         | 1.32%   |
| Lenovo G550 2958                   | 1         | 1.32%   |
| Lenovo 3000 V100 076346G           | 1         | 1.32%   |
| KOHJINSHA SX series                | 1         | 1.32%   |
| KOHJINSHA SC series                | 1         | 1.32%   |
| Intel powered classmate PC         | 1         | 1.32%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.32%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.32%   |
| IBM ThinkPad T40 237342G           | 1         | 1.32%   |
| HP Presario CQ56                   | 1         | 1.32%   |
| HP Pavilion dv2700                 | 1         | 1.32%   |
| HP Mini 5101                       | 1         | 1.32%   |
| HP G5000 (RY492EA#ACB)             | 1         | 1.32%   |
| HP EliteBook 8770w                 | 1         | 1.32%   |
| HP EliteBook 2570p                 | 1         | 1.32%   |
| HP Compaq 8510w                    | 1         | 1.32%   |
| HP 620                             | 1         | 1.32%   |
| HP 255 G3                          | 1         | 1.32%   |
| Google Lava                        | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 9.21%   |
| Dell Latitude         | 5         | 6.58%   |
| Lenovo IdeaPad        | 4         | 5.26%   |
| Toshiba Satellite     | 3         | 3.95%   |
| Lenovo ThinkPad       | 3         | 3.95%   |
| IBM ThinkPad          | 3         | 3.95%   |
| HP Mini               | 3         | 3.95%   |
| IBM 260921H           | 2         | 2.63%   |
| HP EliteBook          | 2         | 2.63%   |
| Fujitsu FMVNU6G1C     | 2         | 2.63%   |
| ASUS VivoBook         | 2         | 2.63%   |
| Unknown               | 2         | 2.63%   |
| Sony VGN-TX690P       | 1         | 1.32%   |
| Samsung SQ1S          | 1         | 1.32%   |
| Packard Bell EasyNote | 1         | 1.32%   |
| MSI GE62              | 1         | 1.32%   |
| Medion WIM2170        | 1         | 1.32%   |
| Lenovo S10-3          | 1         | 1.32%   |
| Lenovo G560           | 1         | 1.32%   |
| Lenovo G550           | 1         | 1.32%   |
| Lenovo 3000           | 1         | 1.32%   |
| KOHJINSHA SX          | 1         | 1.32%   |
| KOHJINSHA SC          | 1         | 1.32%   |
| Intel powered         | 1         | 1.32%   |
| HP Presario           | 1         | 1.32%   |
| HP Pavilion           | 1         | 1.32%   |
| HP G5000              | 1         | 1.32%   |
| HP Compaq             | 1         | 1.32%   |
| HP 620                | 1         | 1.32%   |
| HP 255                | 1         | 1.32%   |
| Google Lava           | 1         | 1.32%   |
| Google Candy          | 1         | 1.32%   |
| Fujitsu FMVS54EB      | 1         | 1.32%   |
| Fujitsu FMVA05007     | 1         | 1.32%   |
| Dell Vostro           | 1         | 1.32%   |
| Compaq Tablet         | 1         | 1.32%   |
| Clevo M66xN           | 1         | 1.32%   |
| ASUS X71SL            | 1         | 1.32%   |
| ASUS X51RL            | 1         | 1.32%   |
| ASUS S3N              | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 11        | 14.47%  |
| 2007 | 11        | 14.47%  |
| 2008 | 8         | 10.53%  |
| 2010 | 7         | 9.21%   |
| 2013 | 5         | 6.58%   |
| 2012 | 5         | 6.58%   |
| 2014 | 4         | 5.26%   |
| 2017 | 3         | 3.95%   |
| 2011 | 3         | 3.95%   |
| 2006 | 3         | 3.95%   |
| 2005 | 3         | 3.95%   |
| 2003 | 3         | 3.95%   |
| 2020 | 2         | 2.63%   |
| 2004 | 2         | 2.63%   |
| 1999 | 2         | 2.63%   |
| 2023 | 1         | 1.32%   |
| 2022 | 1         | 1.32%   |
| 2019 | 1         | 1.32%   |
| 2016 | 1         | 1.32%   |

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
| No   | 74        | 97.37%  |
| Yes  | 2         | 2.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 25        | 32.89%  |
| 1.01-2.0   | 15        | 19.74%  |
| 0.51-1.0   | 12        | 15.79%  |
| 2.01-3.0   | 10        | 13.16%  |
| 4.01-8.0   | 5         | 6.58%   |
| 0.01-0.5   | 4         | 5.26%   |
| 32.01-64.0 | 2         | 2.63%   |
| 8.01-16.0  | 2         | 2.63%   |
| 16.01-24.0 | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 28        | 35.9%   |
| 0.51-1.0 | 26        | 33.33%  |
| 1.01-2.0 | 18        | 23.08%  |
| 2.01-3.0 | 6         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 81.82%  |
| 2      | 11        | 14.29%  |
| 3      | 2         | 2.6%    |
| 0      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 51.32%  |
| No        | 37        | 48.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 82.89%  |
| No        | 13        | 17.11%  |

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
| No        | 42        | 54.55%  |
| Yes       | 35        | 45.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 15.79%  |
| Russia       | 9         | 11.84%  |
| Hong Kong    | 9         | 11.84%  |
| Germany      | 7         | 9.21%   |
| Italy        | 4         | 5.26%   |
| Spain        | 3         | 3.95%   |
| Netherlands  | 3         | 3.95%   |
| Japan        | 3         | 3.95%   |
| Brazil       | 3         | 3.95%   |
| Poland       | 2         | 2.63%   |
| Hungary      | 2         | 2.63%   |
| France       | 2         | 2.63%   |
| Denmark      | 2         | 2.63%   |
| Australia    | 2         | 2.63%   |
| Uruguay      | 1         | 1.32%   |
| Ukraine      | 1         | 1.32%   |
| South Africa | 1         | 1.32%   |
| New Zealand  | 1         | 1.32%   |
| Mexico       | 1         | 1.32%   |
| Kenya        | 1         | 1.32%   |
| Kazakhstan   | 1         | 1.32%   |
| Indonesia    | 1         | 1.32%   |
| Chile        | 1         | 1.32%   |
| Bulgaria     | 1         | 1.32%   |
| Belgium      | 1         | 1.32%   |
| Austria      | 1         | 1.32%   |
| Algeria      | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 7.59%   |
| Sydney                    | 2         | 2.53%   |
| St Petersburg             | 2         | 2.53%   |
| Moscow                    | 2         | 2.53%   |
| Milan                     | 2         | 2.53%   |
| Central                   | 2         | 2.53%   |
| Yuzhno-Sakhalinsk         | 1         | 1.27%   |
| Yokohama                  | 1         | 1.27%   |
| Ybbs an der Donau         | 1         | 1.27%   |
| Whitney                   | 1         | 1.27%   |
| Warsaw                    | 1         | 1.27%   |
| Varna                     | 1         | 1.27%   |
| Tver                      | 1         | 1.27%   |
| Trecate                   | 1         | 1.27%   |
| Torricella Sicura         | 1         | 1.27%   |
| Toms River                | 1         | 1.27%   |
| Templeton                 | 1         | 1.27%   |
| Sofia                     | 1         | 1.27%   |
| Sheung Shui               | 1         | 1.27%   |
| Seattle                   | 1         | 1.27%   |
| Schloss Holte-Stukenbrock | 1         | 1.27%   |
| Santiago                  | 1         | 1.27%   |
| Salto                     | 1         | 1.27%   |
| Rotterdam                 | 1         | 1.27%   |
| Reutlingen                | 1         | 1.27%   |
| Purmerend                 | 1         | 1.27%   |
| Pritzwalk                 | 1         | 1.27%   |
| Portland                  | 1         | 1.27%   |
| Pomaz                     | 1         | 1.27%   |
| Oran                      | 1         | 1.27%   |
| Norden                    | 1         | 1.27%   |
| Neyagawa                  | 1         | 1.27%   |
| Nairobi                   | 1         | 1.27%   |
| Montevideo                | 1         | 1.27%   |
| Mittegrossefehn           | 1         | 1.27%   |
| Mechanicsburg             | 1         | 1.27%   |
| Marcinelle                | 1         | 1.27%   |
| Madrid                    | 1         | 1.27%   |
| Ligueil                   | 1         | 1.27%   |
| La Roche-sur-Yon          | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 19.28%  |
| WDC                 | 15        | 16     | 18.07%  |
| Hitachi             | 14        | 14     | 16.87%  |
| Toshiba             | 7         | 7      | 8.43%   |
| Samsung Electronics | 6         | 6      | 7.23%   |
| Unknown             | 4         | 4      | 4.82%   |
| Kingston            | 2         | 2      | 2.41%   |
| HGST                | 2         | 2      | 2.41%   |
| Zheino              | 1         | 1      | 1.2%    |
| Unknown (CF)        | 1         | 1      | 1.2%    |
| Transcend           | 1         | 1      | 1.2%    |
| RECADATA            | 1         | 1      | 1.2%    |
| PNY                 | 1         | 2      | 1.2%    |
| OCZ                 | 1         | 1      | 1.2%    |
| Maxtor              | 1         | 1      | 1.2%    |
| KIOXIA              | 1         | 1      | 1.2%    |
| Intel               | 1         | 1      | 1.2%    |
| IBM/Hitachi         | 1         | 1      | 1.2%    |
| Hewlett-Packard     | 1         | 1      | 1.2%    |
| Fujitsu             | 1         | 1      | 1.2%    |
| BIWIN               | 1         | 1      | 1.2%    |
| BHT                 | 1         | 3      | 1.2%    |
| ASUS-PHISON         | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |
| Unknown             | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2.41%   |
| Seagate ST980811AS 80GB                 | 2         | 2.41%   |
| Seagate ST9320325AS 320GB               | 2         | 2.41%   |
| Samsung SSD 750 EVO 120GB               | 2         | 2.41%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.41%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 2.41%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 2.41%   |
| Zheino CHN-mSATAM3-128 128GB SSD        | 1         | 1.2%    |
| WDC WD800BEVT-75ZCT2 80GB               | 1         | 1.2%    |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.2%    |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.2%    |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1.2%    |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.2%    |
| WDC WD3200BPVT-24ZEST0 320GB            | 1         | 1.2%    |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.2%    |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.2%    |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.2%    |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 1.2%    |
| WDC WD1600BEVT-00M9YT0 160GB            | 1         | 1.2%    |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.2%    |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.2%    |
| Unknown SR64G  64GB                     | 1         | 1.2%    |
| Unknown SD16G  16GB                     | 1         | 1.2%    |
| Unknown hB8aP  32GB                     | 1         | 1.2%    |
| Unknown HAG2e  16GB                     | 1         | 1.2%    |
| Unknown (CF) CARD 16GB                  | 1         | 1.2%    |
| Transcend SSD 2GB                       | 1         | 1.2%    |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.2%    |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.2%    |
| Toshiba MQ01ABF050 500GB                | 1         | 1.2%    |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.2%    |
| Toshiba MK6006GAH 64GB                  | 1         | 1.2%    |
| Toshiba MK2576GSX 250GB                 | 1         | 1.2%    |
| Toshiba MK2555GSX 250GB                 | 1         | 1.2%    |
| Seagate ST980812AS 80GB                 | 1         | 1.2%    |
| Seagate ST9250421ASG 250GB              | 1         | 1.2%    |
| Seagate ST9250315AS 250GB               | 1         | 1.2%    |
| Seagate ST9160827AS 160GB               | 1         | 1.2%    |
| Seagate ST9160411AS 160GB               | 1         | 1.2%    |
| Seagate ST9160314AS 160GB               | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 28.57%  |
| WDC                 | 15        | 16     | 26.79%  |
| Hitachi             | 14        | 14     | 25%     |
| Toshiba             | 5         | 5      | 8.93%   |
| HGST                | 2         | 2      | 3.57%   |
| Unknown (CF)        | 1         | 1      | 1.79%   |
| Samsung Electronics | 1         | 1      | 1.79%   |
| IBM/Hitachi         | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 19.05%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Zheino              | 1         | 1      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| RECADATA            | 1         | 1      | 4.76%   |
| PNY                 | 1         | 2      | 4.76%   |
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
| HDD  | 55        | 57     | 67.9%   |
| SSD  | 20        | 24     | 24.69%  |
| MMC  | 4         | 4      | 4.94%   |
| NVMe | 2         | 2      | 2.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 71        | 81     | 92.21%  |
| MMC  | 4         | 4      | 5.19%   |
| NVMe | 2         | 2      | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 75     | 93.15%  |
| 0.51-1.0   | 5         | 6      | 6.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 27        | 34.62%  |
| 1-20       | 18        | 23.08%  |
| 51-100     | 14        | 17.95%  |
| 251-500    | 8         | 10.26%  |
| 21-50      | 8         | 10.26%  |
| 501-1000   | 3         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 59        | 77.63%  |
| 21-50    | 8         | 10.53%  |
| 101-250  | 5         | 6.58%   |
| 51-100   | 3         | 3.95%   |
| 501-1000 | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST980811AS 80GB         | 2         | 2      | 6.67%   |
| Seagate ST9320325AS 320GB       | 2         | 2      | 6.67%   |
| Hitachi HTS542525K9SA00 250GB   | 2         | 2      | 6.67%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 1         | 1      | 3.33%   |
| WDC WD5000BEVT-24A0RT0 500GB    | 1         | 1      | 3.33%   |
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 3.33%   |
| WDC WD3200BPVT-24ZEST0 320GB    | 1         | 1      | 3.33%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 3.33%   |
| WDC WD2500BEVT-22ZCT0 250GB     | 1         | 1      | 3.33%   |
| WDC WD1600BEVT-00M9YT0 160GB    | 1         | 2      | 3.33%   |
| Toshiba MK6006GAH 64GB          | 1         | 1      | 3.33%   |
| Toshiba MK2555GSX 250GB         | 1         | 1      | 3.33%   |
| Seagate ST980812AS 80GB         | 1         | 1      | 3.33%   |
| Seagate ST9250315AS 250GB       | 1         | 1      | 3.33%   |
| Seagate ST9160827AS 160GB       | 1         | 1      | 3.33%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 3.33%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 3.33%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 3.33%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 3.33%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 3.33%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 3.33%   |
| Hitachi HTS543225A7A384 250GB   | 1         | 1      | 3.33%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 3.33%   |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 3.33%   |
| BIWIN SSD 32GB                  | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 33.33%  |
| Hitachi | 9         | 9      | 30%     |
| WDC     | 7         | 8      | 23.33%  |
| Toshiba | 2         | 2      | 6.67%   |
| HGST    | 1         | 1      | 3.33%   |
| BIWIN   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 34.48%  |
| Hitachi | 9         | 9      | 31.03%  |
| WDC     | 7         | 8      | 24.14%  |
| Toshiba | 2         | 2      | 6.9%    |
| HGST    | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 30     | 96.67%  |
| SSD  | 1         | 1      | 3.33%   |

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
| Works    | 42        | 50     | 53.85%  |
| Malfunc  | 30        | 31     | 38.46%  |
| Detected | 6         | 6      | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 62        | 79.49%  |
| AMD                              | 5         | 6.41%   |
| VIA Technologies                 | 2         | 2.56%   |
| Silicon Integrated Systems [SiS] | 2         | 2.56%   |
| Nvidia                           | 2         | 2.56%   |
| Silicon Image                    | 1         | 1.28%   |
| Samsung Electronics              | 1         | 1.28%   |
| Marvell Technology Group         | 1         | 1.28%   |
| KIOXIA                           | 1         | 1.28%   |
| JMicron Technology               | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 8.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 6.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 6.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 6.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 5.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 5         | 5.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 4.26%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 3.19%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.19%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.13%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.13%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 2.13%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.06%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 1.06%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.06%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.06%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.06%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.06%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.06%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.06%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.06%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.06%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 46        | 52.87%  |
| IDE  | 35        | 40.23%  |
| RAID | 4         | 4.6%    |
| NVMe | 2         | 2.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 69        | 90.79%  |
| AMD          | 5         | 6.58%   |
| GenuineTMx86 | 1         | 1.32%   |
| CentaurHauls | 1         | 1.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 7.89%   |
| Intel Pentium M processor 1.60GHz           | 2         | 2.63%   |
| Intel Pentium M processor 1.00GHz           | 2         | 2.63%   |
| Intel Genuine processor 800MHz              | 2         | 2.63%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 2.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 2.63%   |
| Intel Celeron (Mendocino)                   | 2         | 2.63%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.63%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 2.63%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 2.63%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.63%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.32%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.32%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.32%   |
| Intel Pentium M processor 1.20GHz           | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.32%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.32%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.32%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.32%   |
| Intel Genuine CPU T2600 @ 2.16GHz           | 1         | 1.32%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.32%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.32%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.32%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.32%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 1         | 1.32%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 15        | 19.74%  |
| Intel Core 2 Duo        | 10        | 13.16%  |
| Intel Celeron           | 8         | 10.53%  |
| Intel Pentium M         | 7         | 9.21%   |
| Intel Genuine           | 6         | 7.89%   |
| Intel Core i5           | 6         | 7.89%   |
| Intel Core i3           | 6         | 7.89%   |
| Intel Core i7           | 5         | 6.58%   |
| AMD E2                  | 2         | 2.63%   |
| Other                   | 1         | 1.32%   |
| Intel Pentium Silver    | 1         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Pentium Dual      | 1         | 1.32%   |
| Intel Pentium 4         | 1         | 1.32%   |
| Intel Core 2            | 1         | 1.32%   |
| Intel Celeron Dual-Core | 1         | 1.32%   |
| CentaurHauls VIA Nano   | 1         | 1.32%   |
| AMD E1                  | 1         | 1.32%   |
| AMD Athlon II           | 1         | 1.32%   |
| AMD Athlon 64 X2        | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 57.89%  |
| 1      | 28        | 36.84%  |
| 4      | 4         | 5.26%   |

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
| 1      | 44        | 57.89%  |
| 2      | 32        | 42.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 65.79%  |
| 32-bit         | 26        | 34.21%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 9         | 11.84%  |
| 0x1067a    | 7         | 9.21%   |
| 0x6fd      | 5         | 6.58%   |
| Unknown    | 5         | 6.58%   |
| 0x6d8      | 4         | 5.26%   |
| 0x6d6      | 4         | 5.26%   |
| 0x6e8      | 3         | 3.95%   |
| 0x40651    | 3         | 3.95%   |
| 0x306a9    | 3         | 3.95%   |
| 0x106ca    | 3         | 3.95%   |
| 0x66a      | 2         | 2.63%   |
| 0x306c3    | 2         | 2.63%   |
| 0x30678    | 2         | 2.63%   |
| 0x30661    | 2         | 2.63%   |
| 0x206a7    | 2         | 2.63%   |
| 0x20655    | 2         | 2.63%   |
| 0x20652    | 2         | 2.63%   |
| 0x10676    | 2         | 2.63%   |
| 0x10661    | 2         | 2.63%   |
| 0xf24      | 1         | 1.32%   |
| 0x906e9    | 1         | 1.32%   |
| 0x806e9    | 1         | 1.32%   |
| 0x706a8    | 1         | 1.32%   |
| 0x706a1    | 1         | 1.32%   |
| 0x6f6      | 1         | 1.32%   |
| 0x695      | 1         | 1.32%   |
| 0x506c9    | 1         | 1.32%   |
| 0x07030106 | 1         | 1.32%   |
| 0x0700010f | 1         | 1.32%   |
| 0x06006704 | 1         | 1.32%   |
| 0x010000c8 | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 15        | 19.74%  |
| P6            | 12        | 15.79%  |
| Penryn        | 9         | 11.84%  |
| Core          | 8         | 10.53%  |
| Haswell       | 5         | 6.58%   |
| Westmere      | 4         | 5.26%   |
| Unknown       | 4         | 5.26%   |
| KabyLake      | 3         | 3.95%   |
| IvyBridge     | 3         | 3.95%   |
| Silvermont    | 2         | 2.63%   |
| SandyBridge   | 2         | 2.63%   |
| Goldmont plus | 2         | 2.63%   |
| Puma          | 1         | 1.32%   |
| NetBurst      | 1         | 1.32%   |
| K8 Hammer     | 1         | 1.32%   |
| K10           | 1         | 1.32%   |
| Jaguar        | 1         | 1.32%   |
| Goldmont      | 1         | 1.32%   |
| Excavator     | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 66.25%  |
| AMD                              | 14        | 17.5%   |
| Nvidia                           | 9         | 11.25%  |
| Neomagic                         | 2         | 2.5%    |
| VIA Technologies                 | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] | 1         | 1.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 12        | 12.77%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 7         | 7.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 7         | 7.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 5         | 5.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 4         | 4.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 3.19%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.13%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.13%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 2.13%   |
| Intel HD Graphics 620                                                         | 2         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.13%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 2.13%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.13%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.13%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                      | 2         | 2.13%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.06%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.06%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.06%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.06%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.06%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.06%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.06%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.06%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.06%   |
| Intel HD Graphics 630                                                         | 1         | 1.06%   |
| Intel HD Graphics 500                                                         | 1         | 1.06%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.06%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                       | 1         | 1.06%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.06%   |
| AMD RV530/M56-P [Mobility Radeon X1600]                                       | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 56.58%  |
| 1 x AMD        | 13        | 17.11%  |
| 1 x Nvidia     | 6         | 7.89%   |
| 2 x Intel      | 4         | 5.26%   |
| Intel + Nvidia | 3         | 3.95%   |
| Other          | 2         | 2.63%   |
| 1 x Neomagic   | 2         | 2.63%   |
| 1 x VIA        | 1         | 1.32%   |
| 1 x SiS        | 1         | 1.32%   |
| Intel + AMD    | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 88.16%  |
| Unknown     | 7         | 9.21%   |
| Proprietary | 2         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 44.74%  |
| 0.01-0.5   | 31        | 40.79%  |
| 1.01-2.0   | 9         | 11.84%  |
| 3.01-4.0   | 1         | 1.32%   |
| 0.51-1.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 25%     |
| LG Display              | 11        | 19.64%  |
| Samsung Electronics     | 6         | 10.71%  |
| Chimei Innolux          | 5         | 8.93%   |
| LG Philips              | 4         | 7.14%   |
| Lenovo                  | 4         | 7.14%   |
| Apple                   | 4         | 7.14%   |
| HannStar                | 3         | 5.36%   |
| InfoVision              | 1         | 1.79%   |
| HJW                     | 1         | 1.79%   |
| CPT                     | 1         | 1.79%   |
| Chi Mei Optoelectronics | 1         | 1.79%   |
| BOE                     | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 3.57%   |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4346 1920x1200 331x207mm 15.4-inch    | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 1         | 1.79%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 1.79%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 1.79%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 1.79%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 1.79%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 1.79%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 1.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.79%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 1.79%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 1.79%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.79%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 1.79%   |
| HannStar HSD089IFW1 HSD0325 1024x600 195x113mm 8.9-inch                  | 1         | 1.79%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1144 1366x768 256x144mm 11.6-inch          | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 1.79%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 22        | 40%     |
| 1280x800 (WXGA)    | 9         | 16.36%  |
| 1920x1080 (FHD)    | 7         | 12.73%  |
| 1024x600           | 7         | 12.73%  |
| 1440x900 (WXGA+)   | 4         | 7.27%   |
| 1920x1200 (WUXGA)  | 2         | 3.64%   |
| 2288x1287          | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |
| 1600x900 (HD+)     | 1         | 1.82%   |
| 1280x720 (HD)      | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 39.29%  |
| 10     | 7         | 12.5%   |
| 14     | 6         | 10.71%  |
| 13     | 5         | 8.93%   |
| 11     | 5         | 8.93%   |
| 17     | 4         | 7.14%   |
| 12     | 2         | 3.57%   |
| 8      | 2         | 3.57%   |
| 32     | 1         | 1.79%   |
| 24     | 1         | 1.79%   |
| 18     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 53.57%  |
| 201-300     | 17        | 30.36%  |
| 351-400     | 5         | 8.93%   |
| 101-200     | 2         | 3.57%   |
| 701-800     | 1         | 1.79%   |
| 501-600     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 68.52%  |
| 16/10 | 16        | 29.63%  |
| 3/2   | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 39.29%  |
| 81-90          | 9         | 16.07%  |
| 41-50          | 7         | 12.5%   |
| 51-60          | 5         | 8.93%   |
| 131-140        | 3         | 5.36%   |
| 71-80          | 2         | 3.57%   |
| 61-70          | 2         | 3.57%   |
| 1-40           | 2         | 3.57%   |
| 351-500        | 1         | 1.79%   |
| 201-250        | 1         | 1.79%   |
| 141-150        | 1         | 1.79%   |
| 121-130        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 25        | 44.64%  |
| 121-160 | 19        | 33.93%  |
| 51-100  | 12        | 21.43%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 69        | 89.61%  |
| 0     | 5         | 6.49%   |
| 2     | 3         | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 29        | 23.39%  |
| Intel                            | 29        | 23.39%  |
| Realtek Semiconductor            | 26        | 20.97%  |
| Broadcom                         | 18        | 14.52%  |
| Marvell Technology Group         | 4         | 3.23%   |
| Broadcom Limited                 | 3         | 2.42%   |
| Silicon Integrated Systems [SiS] | 2         | 1.61%   |
| Ralink                           | 2         | 1.61%   |
| Nvidia                           | 2         | 1.61%   |
| Texas Instruments                | 1         | 0.81%   |
| Qualcomm Atheros Communications  | 1         | 0.81%   |
| NetGear                          | 1         | 0.81%   |
| Motorola PCS                     | 1         | 0.81%   |
| MediaTek                         | 1         | 0.81%   |
| Linksys                          | 1         | 0.81%   |
| Hewlett-Packard                  | 1         | 0.81%   |
| Attansic Technology              | 1         | 0.81%   |
| ASIX Electronics                 | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 7.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 7.33%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 6         | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 2.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 2%      |
| Intel WiFi Link 5100                                                    | 3         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 2%      |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 2%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.33%   |
| Intel Wireless 7260                                                     | 2         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 1.33%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 1.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.33%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.67%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                        | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 34.18%  |
| Qualcomm Atheros                | 26        | 32.91%  |
| Broadcom                        | 14        | 17.72%  |
| Realtek Semiconductor           | 4         | 5.06%   |
| Ralink                          | 2         | 2.53%   |
| Texas Instruments               | 1         | 1.27%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |
| NetGear                         | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Linksys                         | 1         | 1.27%   |
| Broadcom Limited                | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 11        | 13.75%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 5         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 5%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 5%      |
| Intel WiFi Link 5100                                                          | 3         | 3.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 3.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 3.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.5%    |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.5%    |
| Intel Wireless 7260                                                           | 2         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 2.5%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.25%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.25%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.25%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.25%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.25%   |
| NetGear A6150                                                                 | 1         | 1.25%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.25%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                             | 1         | 1.25%   |
| Intel Wireless 7265                                                           | 1         | 1.25%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.25%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 1.25%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.25%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.25%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 37.5%   |
| Intel                            | 14        | 21.88%  |
| Broadcom                         | 7         | 10.94%  |
| Qualcomm Atheros                 | 6         | 9.38%   |
| Marvell Technology Group         | 4         | 6.25%   |
| Silicon Integrated Systems [SiS] | 2         | 3.13%   |
| Nvidia                           | 2         | 3.13%   |
| Broadcom Limited                 | 2         | 3.13%   |
| Motorola PCS                     | 1         | 1.56%   |
| Attansic Technology              | 1         | 1.56%   |
| ASIX Electronics                 | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 17.19%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6         | 9.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 9.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 4.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 3.13%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.13%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 3.13%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 2         | 3.13%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 3.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.56%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 1.56%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 1.56%   |
| Motorola PCS moto g(7) power                                           | 1         | 1.56%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 1.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.56%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                           | 1         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.56%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.56%   |
| Intel 82562EM/EX/GX - PRO/100 VM (LOM) Ethernet Controller Mobile      | 1         | 1.56%   |
| Intel 82551QM Ethernet Controller                                      | 1         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.56%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 1.56%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.56%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 1.56%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 1         | 1.56%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 1         | 1.56%   |
| ASIX AX88772A Fast Ethernet                                            | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 51.75%  |
| Ethernet | 63        | 44.06%  |
| Modem    | 6         | 4.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 84.81%  |
| Ethernet | 12        | 15.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 60        | 78.95%  |
| 1     | 16        | 21.05%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 78.21%  |
| Yes  | 17        | 21.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Broadcom                        | 9         | 26.47%  |
| Intel                           | 5         | 14.71%  |
| Apple                           | 4         | 11.76%  |
| Qualcomm Atheros Communications | 2         | 5.88%   |
| Lite-On Technology              | 2         | 5.88%   |
| IMC Networks                    | 2         | 5.88%   |
| Foxconn / Hon Hai               | 2         | 5.88%   |
| Taiyo Yuden                     | 1         | 2.94%   |
| Realtek Semiconductor           | 1         | 2.94%   |
| Ralink Technology               | 1         | 2.94%   |
| Hewlett-Packard                 | 1         | 2.94%   |
| Fujitsu                         | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |
| Alps Electric                   | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.88%   |
| Intel Bluetooth wireless interface                  | 2         | 5.88%   |
| IMC Networks Bluetooth Device                       | 2         | 5.88%   |
| Broadcom HP Portable SoftSailing                    | 2         | 5.88%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 5.88%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.94%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.94%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| Intel Bluetooth Device                              | 1         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.94%   |
| Fujitsu Bluetooth Device                            | 1         | 2.94%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.94%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.94%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.94%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |
| Apple Bluetooth HCI                                 | 1         | 2.94%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 63        | 77.78%  |
| AMD                              | 9         | 11.11%  |
| Nvidia                           | 3         | 3.7%    |
| VIA Technologies                 | 2         | 2.47%   |
| Silicon Integrated Systems [SiS] | 2         | 2.47%   |
| ESS Technology                   | 2         | 2.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 21.35%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 7.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 5.62%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 4.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 4.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.37%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.37%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 2         | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.25%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.25%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 2.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.25%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.25%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.12%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.12%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.12%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.12%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.12%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.12%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.12%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 1.12%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.12%   |
| AMD High Definition Audio Controller                                       | 1         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 30        | 33.71%  |
| SK hynix            | 19        | 21.35%  |
| Samsung Electronics | 10        | 11.24%  |
| Unknown             | 9         | 10.11%  |
| Micron Technology   | 6         | 6.74%   |
| Kingston            | 5         | 5.62%   |
| Crucial             | 2         | 2.25%   |
| Unknown (8A02)      | 1         | 1.12%   |
| Ramaxel Technology  | 1         | 1.12%   |
| Nanya Technology    | 1         | 1.12%   |
| Kingmax             | 1         | 1.12%   |
| fef5                | 1         | 1.12%   |
| Elpida              | 1         | 1.12%   |
| Avant               | 1         | 1.12%   |
| Apacer              | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 9         | 9.57%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 3.19%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 3         | 3.19%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 2.13%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 2.13%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.13%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 2.13%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 2         | 2.13%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s          | 2         | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 2.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s       | 2         | 2.13%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DDR2                           | 1         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DDR 100MT/s                    | 1         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.06%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM SDRAM                            | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.06%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.06%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.06%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.06%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.06%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.06%   |
| SK hynix RAM Module 2GB DIMM DDR2 667MT/s                      | 1         | 1.06%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.06%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 32.89%  |
| DDR2    | 20        | 26.32%  |
| SDRAM   | 13        | 17.11%  |
| DDR4    | 6         | 7.89%   |
| DDR     | 6         | 7.89%   |
| DRAM    | 4         | 5.26%   |
| LPDDR4  | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 91.89%  |
| DIMM         | 4         | 5.41%   |
| Row Of Chips | 1         | 1.35%   |
| Unknown      | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 31        | 36.05%  |
| 1024  | 21        | 24.42%  |
| 4096  | 13        | 15.12%  |
| 512   | 8         | 9.3%    |
| 8192  | 6         | 6.98%   |
| 256   | 3         | 3.49%   |
| 64    | 2         | 2.33%   |
| 16384 | 1         | 1.16%   |
| 232   | 1         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 26.58%  |
| 1600    | 15        | 18.99%  |
| 667     | 7         | 8.86%   |
| 1067    | 6         | 7.59%   |
| 533     | 5         | 6.33%   |
| 4199    | 3         | 3.8%    |
| 2400    | 3         | 3.8%    |
| 1334    | 3         | 3.8%    |
| 800     | 3         | 3.8%    |
| 2667    | 2         | 2.53%   |
| 1333    | 2         | 2.53%   |
| 975     | 2         | 2.53%   |
| 200     | 2         | 2.53%   |
| 3266    | 1         | 1.27%   |
| 3200    | 1         | 1.27%   |
| 1866    | 1         | 1.27%   |
| 266     | 1         | 1.27%   |
| 100     | 1         | 1.27%   |

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
| Chicony Electronics                    | 10        | 20.83%  |
| Suyin                                  | 5         | 10.42%  |
| Microdia                               | 4         | 8.33%   |
| IMC Networks                           | 4         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8.33%   |
| Acer                                   | 3         | 6.25%   |
| Sunplus Innovation Technology          | 2         | 4.17%   |
| Silicon Motion                         | 2         | 4.17%   |
| Realtek Semiconductor                  | 2         | 4.17%   |
| Pixart Imaging                         | 2         | 4.17%   |
| Lenovo                                 | 2         | 4.17%   |
| Bison Electronics                      | 2         | 4.17%   |
| Apple                                  | 2         | 4.17%   |
| Z-Star Microelectronics                | 1         | 2.08%   |
| Syntek                                 | 1         | 2.08%   |
| Jieli Technology                       | 1         | 2.08%   |
| Importek                               | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                           | 3         | 6.25%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 4.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.17%   |
| Chicony HD WebCam                                       | 2         | 4.17%   |
| Acer Lenovo EasyCamera                                  | 2         | 4.17%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 2.08%   |
| Syntek Integrated Camera                                | 1         | 2.08%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 2.08%   |
| Suyin USB 2.0 Camera                                    | 1         | 2.08%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.08%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.08%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.08%   |
| Sunplus HD WebCam                                       | 1         | 2.08%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.08%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.08%   |
| Realtek Integrated Webcam HD                            | 1         | 2.08%   |
| Realtek HD WebCam                                       | 1         | 2.08%   |
| Microdia Integrated Webcam                              | 1         | 2.08%   |
| Lenovo Integrated Webcam                                | 1         | 2.08%   |
| Lenovo CNF7237&CNF7238                                  | 1         | 2.08%   |
| Jieli USB PHY 2.0                                       | 1         | 2.08%   |
| Importek FJ Camera                                      | 1         | 2.08%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.08%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.08%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.08%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.08%   |
| Chicony HP Webcam                                       | 1         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.08%   |
| Chicony EasyCamera                                      | 1         | 2.08%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.08%   |
| Chicony CNF7050                                         | 1         | 2.08%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.08%   |
| Bison BisonCam, NB Pro                                  | 1         | 2.08%   |
| Bison Acer Crystal Eye Webcam                           | 1         | 2.08%   |
| Apple FaceTime Camera                                   | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 6         | 66.67%  |
| Upek             | 2         | 22.22%  |
| Validity Sensors | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 4         | 44.44%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 22.22%  |
| AuthenTec AES1600                                      | 2         | 22.22%  |
| Validity Sensors VFS491                                | 1         | 11.11%  |

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


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 66.67%  |
| Broadcom 5880                                  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 49        | 64.47%  |
| 1     | 24        | 31.58%  |
| 2     | 2         | 2.63%   |
| 3     | 1         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 16        | 53.33%  |
| Fingerprint reader    | 9         | 30%     |
| Multimedia controller | 2         | 6.67%   |
| Chipcard              | 2         | 6.67%   |
| Net/wireless          | 1         | 3.33%   |


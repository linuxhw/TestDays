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

Total: 116

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro5,5               | [f0a067c40e](https://linux-hardware.org/?probe=f0a067c40e) | Dec 26, 2024 |
| Google        | Terra                       | [35133a4a83](https://linux-hardware.org/?probe=35133a4a83) | Dec 10, 2024 |
| Apple         | MacBookPro8,1               | [5a3f525db9](https://linux-hardware.org/?probe=5a3f525db9) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [6d1e58c127](https://linux-hardware.org/?probe=6d1e58c127) | Oct 19, 2024 |
| HP            | ProBook 640 G1              | [20a7878d28](https://linux-hardware.org/?probe=20a7878d28) | Oct 12, 2024 |
| Google        | Grabbiter                   | [2a3731211a](https://linux-hardware.org/?probe=2a3731211a) | Oct 06, 2024 |
| HP            | Presario CQ42               | [bd24eb99d5](https://linux-hardware.org/?probe=bd24eb99d5) | Sep 09, 2024 |
| ASUSTek       | X441SA                      | [35fe8d4aa5](https://linux-hardware.org/?probe=35fe8d4aa5) | Sep 09, 2024 |
| Lenovo        | ThinkPad P51 20HJS49Q00     | [00383b8346](https://linux-hardware.org/?probe=00383b8346) | Aug 27, 2024 |
| Insyde        | BayTrail                    | [6e2a85feb0](https://linux-hardware.org/?probe=6e2a85feb0) | Aug 19, 2024 |
| Dell          | Vostro 14-3468              | [dd8f759e76](https://linux-hardware.org/?probe=dd8f759e76) | Aug 14, 2024 |
| Dell          | Vostro 14-3468              | [225da9f323](https://linux-hardware.org/?probe=225da9f323) | Aug 14, 2024 |
| Dell          | Latitude D820               | [27ec5b3e2e](https://linux-hardware.org/?probe=27ec5b3e2e) | Jun 27, 2024 |
| HP            | Compaq 6735s                | [eddd6a81e1](https://linux-hardware.org/?probe=eddd6a81e1) | Jun 09, 2024 |
| HP            | Mini 210-2100               | [95983d6f48](https://linux-hardware.org/?probe=95983d6f48) | Jun 09, 2024 |
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
| antiX 21       | 25        | 27.47%  |
| antiX 22       | 22        | 24.18%  |
| antiX 23.1     | 14        | 15.38%  |
| antiX 23       | 10        | 10.99%  |
| antiX 19.2     | 6         | 6.59%   |
| antiX 21-runit | 3         | 3.3%    |
| antiX 19.3     | 3         | 3.3%    |
| antiX 19.4     | 2         | 2.2%    |
| antiX 19.1     | 2         | 2.2%    |
| antiX 19.5     | 1         | 1.1%    |
| antiX 17.4.1   | 1         | 1.1%    |
| antiX 17.2.1   | 1         | 1.1%    |
| antiX 17       | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 90        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 15        | 16.48%  |
| 5.10.142-antix.2-amd64-smp   | 9         | 9.89%   |
| 4.9.0-326-antix.1-amd64-smp  | 8         | 8.79%   |
| 4.9.0-279-antix.1-amd64-smp  | 6         | 6.59%   |
| 6.1.60-antix.1-amd64-smp     | 5         | 5.49%   |
| 4.9.0-326-antix.1-486-smp    | 5         | 5.49%   |
| 5.10.57-antix.1-amd64-smp    | 4         | 4.4%    |
| 6.1.42-antix.1-amd64-smp     | 3         | 3.3%    |
| 5.10.224-antix.1-amd64-smp   | 3         | 3.3%    |
| 5.10.197-antix.1-486-smp     | 3         | 3.3%    |
| 5.10.188-antix.1-486-smp     | 3         | 3.3%    |
| 6.1.55-antix.1-amd64-smp     | 2         | 2.2%    |
| 5.10.188-antix.1-amd64-smp   | 2         | 2.2%    |
| 4.9.235-antix.1-amd64-smp    | 2         | 2.2%    |
| 4.9.212-antix.1-amd64-smp    | 2         | 2.2%    |
| 4.9.212-antix.1-486-smp      | 2         | 2.2%    |
| 4.9.200-antix.1-486-smp      | 2         | 2.2%    |
| 6.10.9-1-liquorix-amd64      | 1         | 1.1%    |
| 6.1.90-antix.1-amd64-smp     | 1         | 1.1%    |
| 5.4.0-17.1-liquorix-amd64    | 1         | 1.1%    |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.1%    |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.1%    |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.1%    |
| 5.10.199-antix.1-amd64-smp   | 1         | 1.1%    |
| 4.9.160-antix.2-486-smp      | 1         | 1.1%    |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.1%    |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.1%    |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.1%    |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.1%    |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.1%    |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.1%    |
| 4.10.5-antix.1-486-smp       | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 35        | 38.89%  |
| 5.10.142 | 9         | 10%     |
| 6.1.60   | 5         | 5.56%   |
| 5.10.188 | 5         | 5.56%   |
| 5.10.57  | 4         | 4.44%   |
| 4.9.212  | 4         | 4.44%   |
| 6.1.42   | 3         | 3.33%   |
| 5.10.224 | 3         | 3.33%   |
| 5.10.197 | 3         | 3.33%   |
| 6.1.55   | 2         | 2.22%   |
| 4.9.235  | 2         | 2.22%   |
| 4.9.200  | 2         | 2.22%   |
| 4.9.160  | 2         | 2.22%   |
| 6.10.9   | 1         | 1.11%   |
| 6.1.90   | 1         | 1.11%   |
| 5.4.0    | 1         | 1.11%   |
| 5.14.0   | 1         | 1.11%   |
| 5.10.88  | 1         | 1.11%   |
| 5.10.27  | 1         | 1.11%   |
| 5.10.199 | 1         | 1.11%   |
| 4.19.202 | 1         | 1.11%   |
| 4.19.100 | 1         | 1.11%   |
| 4.19.0   | 1         | 1.11%   |
| 4.10.5   | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 45        | 50%     |
| 5.10    | 27        | 30%     |
| 6.1     | 11        | 12.22%  |
| 4.19    | 3         | 3.33%   |
| 6.10    | 1         | 1.11%   |
| 5.4     | 1         | 1.11%   |
| 5.14    | 1         | 1.11%   |
| 4.10    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 61.11%  |
| i686   | 34        | 37.78%  |
| i586   | 1         | 1.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| icewm    | 50        | 54.95%  |
| Unknown  | 29        | 31.87%  |
| fluxbox  | 5         | 5.49%   |
| jwm      | 2         | 2.2%    |
| GNOME    | 2         | 2.2%    |
| XFCE     | 1         | 1.1%    |
| LXQt     | 1         | 1.1%    |
| Cinnamon | 1         | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 98.89%  |
| Unknown | 1         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 46.67%  |
| SLIMSKI | 27        | 30%     |
| SLiM    | 15        | 16.67%  |
| LightDM | 3         | 3.33%   |
| XDM     | 1         | 1.11%   |
| SDDM    | 1         | 1.11%   |
| LXDM    | 1         | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 37        | 41.11%  |
| ru_RU | 8         | 8.89%   |
| de_DE | 7         | 7.78%   |
| it_IT | 5         | 5.56%   |
| pt_BR | 4         | 4.44%   |
| ja_JP | 4         | 4.44%   |
| es_ES | 4         | 4.44%   |
| fr_FR | 3         | 3.33%   |
| nl_NL | 2         | 2.22%   |
| en_NZ | 2         | 2.22%   |
| en_GB | 2         | 2.22%   |
| en_AU | 2         | 2.22%   |
| zh_HK | 1         | 1.11%   |
| uk_UA | 1         | 1.11%   |
| pl_PL | 1         | 1.11%   |
| hu_HU | 1         | 1.11%   |
| fr_BE | 1         | 1.11%   |
| fi_FI | 1         | 1.11%   |
| es_VE | 1         | 1.11%   |
| es_MX | 1         | 1.11%   |
| de_AT | 1         | 1.11%   |
| da_DK | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 65        | 72.22%  |
| EFI  | 25        | 27.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 81        | 90%     |
| Overlay  | 8         | 8.89%   |
| Reiserfs | 1         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 61        | 67.78%  |
| GPT     | 28        | 31.11%  |
| Unknown | 1         | 1.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 81.32%  |
| Yes       | 17        | 18.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 65.56%  |
| Yes       | 31        | 34.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 16.67%  |
| Lenovo              | 13        | 14.44%  |
| ASUSTek Computer    | 11        | 12.22%  |
| Acer                | 9         | 10%     |
| Dell                | 8         | 8.89%   |
| Apple               | 6         | 6.67%   |
| IBM                 | 5         | 5.56%   |
| Google              | 4         | 4.44%   |
| Fujitsu             | 4         | 4.44%   |
| Toshiba             | 3         | 3.33%   |
| KOHJINSHA           | 2         | 2.22%   |
| Sony                | 1         | 1.11%   |
| Samsung Electronics | 1         | 1.11%   |
| Packard Bell        | 1         | 1.11%   |
| MSI                 | 1         | 1.11%   |
| Medion              | 1         | 1.11%   |
| Intel               | 1         | 1.11%   |
| Insyde              | 1         | 1.11%   |
| Compaq              | 1         | 1.11%   |
| Clevo               | 1         | 1.11%   |
| Unknown             | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 2.22%   |
| HP Mini 110-3700                   | 2         | 2.22%   |
| Fujitsu FMVNU6G1C                  | 2         | 2.22%   |
| Dell Latitude 5480                 | 2         | 2.22%   |
| Unknown                            | 2         | 2.22%   |
| Toshiba Satellite T110             | 1         | 1.11%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.11%   |
| Toshiba Satellite 1905             | 1         | 1.11%   |
| Sony VGN-TX690P                    | 1         | 1.11%   |
| Samsung SQ1S                       | 1         | 1.11%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.11%   |
| MSI GE62 7RE                       | 1         | 1.11%   |
| Medion WIM2170                     | 1         | 1.11%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.11%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.11%   |
| Lenovo ThinkPad SL500 27463ZG      | 1         | 1.11%   |
| Lenovo ThinkPad P51 20HJS49Q00     | 1         | 1.11%   |
| Lenovo S10-3                       | 1         | 1.11%   |
| Lenovo IdeaPad Y460                | 1         | 1.11%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.11%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.11%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.11%   |
| Lenovo G560 20042                  | 1         | 1.11%   |
| Lenovo G550 2958                   | 1         | 1.11%   |
| Lenovo 3000 V100 076346G           | 1         | 1.11%   |
| KOHJINSHA SX series                | 1         | 1.11%   |
| KOHJINSHA SC series                | 1         | 1.11%   |
| Intel powered classmate PC         | 1         | 1.11%   |
| Insyde BayTrail                    | 1         | 1.11%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.11%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.11%   |
| IBM ThinkPad T40 237342G           | 1         | 1.11%   |
| HP ProBook 640 G1                  | 1         | 1.11%   |
| HP Presario CQ56                   | 1         | 1.11%   |
| HP Presario CQ42                   | 1         | 1.11%   |
| HP Pavilion dv2700                 | 1         | 1.11%   |
| HP Mini 5101                       | 1         | 1.11%   |
| HP Mini 210-2100                   | 1         | 1.11%   |
| HP G5000 (RY492EA#ACB)             | 1         | 1.11%   |
| HP EliteBook 8770w                 | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 7.78%   |
| Dell Latitude         | 6         | 6.67%   |
| Lenovo ThinkPad       | 4         | 4.44%   |
| Lenovo IdeaPad        | 4         | 4.44%   |
| HP Mini               | 4         | 4.44%   |
| Toshiba Satellite     | 3         | 3.33%   |
| IBM ThinkPad          | 3         | 3.33%   |
| IBM 260921H           | 2         | 2.22%   |
| HP Presario           | 2         | 2.22%   |
| HP EliteBook          | 2         | 2.22%   |
| HP Compaq             | 2         | 2.22%   |
| Fujitsu FMVNU6G1C     | 2         | 2.22%   |
| Dell Vostro           | 2         | 2.22%   |
| ASUS VivoBook         | 2         | 2.22%   |
| Unknown               | 2         | 2.22%   |
| Sony VGN-TX690P       | 1         | 1.11%   |
| Samsung SQ1S          | 1         | 1.11%   |
| Packard Bell EasyNote | 1         | 1.11%   |
| MSI GE62              | 1         | 1.11%   |
| Medion WIM2170        | 1         | 1.11%   |
| Lenovo S10-3          | 1         | 1.11%   |
| Lenovo G560           | 1         | 1.11%   |
| Lenovo G550           | 1         | 1.11%   |
| Lenovo 3000           | 1         | 1.11%   |
| KOHJINSHA SX          | 1         | 1.11%   |
| KOHJINSHA SC          | 1         | 1.11%   |
| Intel powered         | 1         | 1.11%   |
| Insyde BayTrail       | 1         | 1.11%   |
| HP ProBook            | 1         | 1.11%   |
| HP Pavilion           | 1         | 1.11%   |
| HP G5000              | 1         | 1.11%   |
| HP 620                | 1         | 1.11%   |
| HP 255                | 1         | 1.11%   |
| Google Terra          | 1         | 1.11%   |
| Google Lava           | 1         | 1.11%   |
| Google Grabbiter      | 1         | 1.11%   |
| Google Candy          | 1         | 1.11%   |
| Fujitsu FMVS54EB      | 1         | 1.11%   |
| Fujitsu FMVA05007     | 1         | 1.11%   |
| Compaq Tablet         | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 12        | 13.33%  |
| 2007 | 11        | 12.22%  |
| 2008 | 9         | 10%     |
| 2010 | 8         | 8.89%   |
| 2013 | 6         | 6.67%   |
| 2012 | 6         | 6.67%   |
| 2017 | 5         | 5.56%   |
| 2014 | 4         | 4.44%   |
| 2011 | 4         | 4.44%   |
| 2006 | 4         | 4.44%   |
| 2005 | 3         | 3.33%   |
| 2003 | 3         | 3.33%   |
| 2023 | 2         | 2.22%   |
| 2022 | 2         | 2.22%   |
| 2020 | 2         | 2.22%   |
| 2016 | 2         | 2.22%   |
| 2004 | 2         | 2.22%   |
| 1999 | 2         | 2.22%   |
| 2024 | 1         | 1.11%   |
| 2019 | 1         | 1.11%   |
| 2015 | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 90        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 90        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 95.56%  |
| Yes  | 4         | 4.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 31        | 34.44%  |
| 1.01-2.0   | 18        | 20%     |
| 0.51-1.0   | 12        | 13.33%  |
| 2.01-3.0   | 10        | 11.11%  |
| 4.01-8.0   | 8         | 8.89%   |
| 0.01-0.5   | 4         | 4.44%   |
| 8.01-16.0  | 3         | 3.33%   |
| 32.01-64.0 | 2         | 2.22%   |
| 16.01-24.0 | 2         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 32        | 34.78%  |
| 0.51-1.0 | 28        | 30.43%  |
| 1.01-2.0 | 24        | 26.09%  |
| 2.01-3.0 | 8         | 8.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 79.12%  |
| 2      | 14        | 15.38%  |
| 0      | 3         | 3.3%    |
| 3      | 2         | 2.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 50%     |
| No        | 45        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 82.22%  |
| No        | 16        | 17.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 96.67%  |
| No        | 3         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 51.65%  |
| Yes       | 44        | 48.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 14        | 15.56%  |
| Russia              | 10        | 11.11%  |
| Hong Kong           | 9         | 10%     |
| Germany             | 8         | 8.89%   |
| Italy               | 5         | 5.56%   |
| Japan               | 4         | 4.44%   |
| Brazil              | 4         | 4.44%   |
| Spain               | 3         | 3.33%   |
| Netherlands         | 3         | 3.33%   |
| South Africa        | 2         | 2.22%   |
| Poland              | 2         | 2.22%   |
| New Zealand         | 2         | 2.22%   |
| Hungary             | 2         | 2.22%   |
| France              | 2         | 2.22%   |
| Denmark             | 2         | 2.22%   |
| Australia           | 2         | 2.22%   |
| Algeria             | 2         | 2.22%   |
| Uruguay             | 1         | 1.11%   |
| Ukraine             | 1         | 1.11%   |
| Trinidad and Tobago | 1         | 1.11%   |
| Mexico              | 1         | 1.11%   |
| Kenya               | 1         | 1.11%   |
| Kazakhstan          | 1         | 1.11%   |
| Indonesia           | 1         | 1.11%   |
| India               | 1         | 1.11%   |
| Guam                | 1         | 1.11%   |
| Finland             | 1         | 1.11%   |
| Chile               | 1         | 1.11%   |
| Bulgaria            | 1         | 1.11%   |
| Belgium             | 1         | 1.11%   |
| Austria             | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 6.45%   |
| Milan                     | 3         | 3.23%   |
| Sydney                    | 2         | 2.15%   |
| St Petersburg             | 2         | 2.15%   |
| Norden                    | 2         | 2.15%   |
| Moscow                    | 2         | 2.15%   |
| Central                   | 2         | 2.15%   |
| Yuzhno-Sakhalinsk         | 1         | 1.08%   |
| Yokohama                  | 1         | 1.08%   |
| Ybbs an der Donau         | 1         | 1.08%   |
| Whitney                   | 1         | 1.08%   |
| Warsaw                    | 1         | 1.08%   |
| Varna                     | 1         | 1.08%   |
| Tver                      | 1         | 1.08%   |
| Tunapuna                  | 1         | 1.08%   |
| Trecate                   | 1         | 1.08%   |
| Torricella Sicura         | 1         | 1.08%   |
| Toms River                | 1         | 1.08%   |
| Templeton                 | 1         | 1.08%   |
| Sofia                     | 1         | 1.08%   |
| Sheung Shui               | 1         | 1.08%   |
| Seattle                   | 1         | 1.08%   |
| Schloss Holte-Stukenbrock | 1         | 1.08%   |
| Santiago                  | 1         | 1.08%   |
| Salto                     | 1         | 1.08%   |
| Sagamino                  | 1         | 1.08%   |
| Rotterdam                 | 1         | 1.08%   |
| Reutlingen                | 1         | 1.08%   |
| Purmerend                 | 1         | 1.08%   |
| Pritzwalk                 | 1         | 1.08%   |
| Portland                  | 1         | 1.08%   |
| Port Elizabeth            | 1         | 1.08%   |
| Pomaz                     | 1         | 1.08%   |
| Oran                      | 1         | 1.08%   |
| Neyagawa                  | 1         | 1.08%   |
| Nairobi                   | 1         | 1.08%   |
| Mudgere                   | 1         | 1.08%   |
| Montevideo                | 1         | 1.08%   |
| Mittegrossefehn           | 1         | 1.08%   |
| Mechanicsburg             | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 19     | 19.59%  |
| WDC                 | 16        | 17     | 16.49%  |
| Hitachi             | 15        | 15     | 15.46%  |
| Samsung Electronics | 8         | 8      | 8.25%   |
| Unknown             | 7         | 7      | 7.22%   |
| Toshiba             | 7         | 7      | 7.22%   |
| HGST                | 3         | 3      | 3.09%   |
| Kingston            | 2         | 2      | 2.06%   |
| Unknown             | 2         | 2      | 2.06%   |
| Zheino              | 1         | 1      | 1.03%   |
| Unknown (CF)        | 1         | 1      | 1.03%   |
| Transcend           | 1         | 1      | 1.03%   |
| SPCC                | 1         | 1      | 1.03%   |
| SanDisk             | 1         | 1      | 1.03%   |
| RECADATA            | 1         | 1      | 1.03%   |
| PNY                 | 1         | 2      | 1.03%   |
| OCZ                 | 1         | 1      | 1.03%   |
| Maxtor              | 1         | 1      | 1.03%   |
| KIOXIA              | 1         | 1      | 1.03%   |
| Intel               | 1         | 1      | 1.03%   |
| IBM/Hitachi         | 1         | 1      | 1.03%   |
| Hewlett-Packard     | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| BIWIN               | 1         | 1      | 1.03%   |
| BHT                 | 1         | 3      | 1.03%   |
| ASUS-PHISON         | 1         | 1      | 1.03%   |
| Apple               | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2.06%   |
| Seagate ST980811AS 80GB                 | 2         | 2.06%   |
| Seagate ST9320325AS 320GB               | 2         | 2.06%   |
| Samsung SSD 750 EVO 120GB               | 2         | 2.06%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.06%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 2.06%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 2.06%   |
| Unknown                                 | 2         | 2.06%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.03%   |
| WDC WD800BEVT-75ZCT2 80GB               | 1         | 1.03%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.03%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.03%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1.03%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.03%   |
| WDC WD3200BPVT-24ZEST0 320GB            | 1         | 1.03%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.03%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.03%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.03%   |
| WDC WD2500BEKT-60PVMT0 250GB            | 1         | 1.03%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 1.03%   |
| WDC WD1600BEVT-00M9YT0 160GB            | 1         | 1.03%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.03%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.03%   |
| Unknown SR64G  64GB                     | 1         | 1.03%   |
| Unknown SD16G  16GB                     | 1         | 1.03%   |
| Unknown hB8aP  32GB                     | 1         | 1.03%   |
| Unknown HAG4a2  16GB                    | 1         | 1.03%   |
| Unknown HAG2e  16GB                     | 1         | 1.03%   |
| Unknown DA4032  32GB                    | 1         | 1.03%   |
| Unknown 032GE4  32GB                    | 1         | 1.03%   |
| Unknown (CF) Card 4GB                   | 1         | 1.03%   |
| Transcend SSD 2GB                       | 1         | 1.03%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.03%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.03%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.03%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.03%   |
| Toshiba MK6006GAH 64GB                  | 1         | 1.03%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.03%   |
| Toshiba MK2555GSX 250GB                 | 1         | 1.03%   |
| SPCC Solid State Disk 512GB             | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 19     | 30.16%  |
| WDC                 | 16        | 17     | 25.4%   |
| Hitachi             | 15        | 15     | 23.81%  |
| Toshiba             | 5         | 5      | 7.94%   |
| HGST                | 3         | 3      | 4.76%   |
| Samsung Electronics | 2         | 2      | 3.17%   |
| Unknown (CF)        | 1         | 1      | 1.59%   |
| IBM/Hitachi         | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 18.18%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Zheino              | 1         | 1      | 4.55%   |
| Transcend           | 1         | 1      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| RECADATA            | 1         | 1      | 4.55%   |
| PNY                 | 1         | 2      | 4.55%   |
| OCZ                 | 1         | 1      | 4.55%   |
| Maxtor              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |
| BIWIN               | 1         | 1      | 4.55%   |
| BHT                 | 1         | 3      | 4.55%   |
| ASUS-PHISON         | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |
| Unknown             | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 64     | 65.96%  |
| SSD  | 21        | 25     | 22.34%  |
| MMC  | 7         | 8      | 7.45%   |
| NVMe | 4         | 4      | 4.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 88     | 86.67%  |
| MMC  | 7         | 8      | 7.78%   |
| NVMe | 4         | 4      | 4.44%   |
| SAS  | 1         | 1      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 80     | 90.12%  |
| 0.51-1.0   | 7         | 8      | 8.64%   |
| 1.01-2.0   | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 32        | 34.78%  |
| 1-20       | 19        | 20.65%  |
| 51-100     | 15        | 16.3%   |
| 251-500    | 11        | 11.96%  |
| 21-50      | 11        | 11.96%  |
| 501-1000   | 3         | 3.26%   |
| 2001-3000  | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 68        | 75.56%  |
| 21-50    | 11        | 12.22%  |
| 101-250  | 5         | 5.56%   |
| 51-100   | 4         | 4.44%   |
| 251-500  | 1         | 1.11%   |
| 501-1000 | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST980811AS 80GB              | 2         | 2      | 5.88%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 5.88%   |
| Hitachi HTS542525K9SA00 250GB        | 2         | 2      | 5.88%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-24A0RT0 500GB         | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 2.94%   |
| WDC WD3200BPVT-24ZEST0 320GB         | 1         | 1      | 2.94%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 1      | 2.94%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 1      | 2.94%   |
| WDC WD2500BEKT-60PVMT0 250GB         | 1         | 1      | 2.94%   |
| WDC WD1600BEVT-00M9YT0 160GB         | 1         | 2      | 2.94%   |
| Toshiba MK6006GAH 64GB               | 1         | 1      | 2.94%   |
| Toshiba MK2555GSX 250GB              | 1         | 1      | 2.94%   |
| Seagate ST980812AS 80GB              | 1         | 1      | 2.94%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 2.94%   |
| Seagate ST9160827AS 160GB            | 1         | 1      | 2.94%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 2.94%   |
| Seagate ST9160310AS 160GB            | 1         | 1      | 2.94%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 2.94%   |
| Samsung Electronics HN-M500MBB 500GB | 1         | 1      | 2.94%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 2.94%   |
| Hitachi HTS721060G9AT00 64GB         | 1         | 1      | 2.94%   |
| Hitachi HTS548040M9AT00 40GB         | 1         | 1      | 2.94%   |
| Hitachi HTS543225A7A384 250GB        | 1         | 1      | 2.94%   |
| Hitachi HTS541612J9SA00 120GB        | 1         | 1      | 2.94%   |
| Hitachi HTC426040G8CE00 40GB         | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB           | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB           | 1         | 1      | 2.94%   |
| BIWIN SSD 32GB                       | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 32.35%  |
| Hitachi             | 9         | 9      | 26.47%  |
| WDC                 | 8         | 9      | 23.53%  |
| Toshiba             | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| BIWIN               | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 33.33%  |
| Hitachi             | 9         | 9      | 27.27%  |
| WDC                 | 8         | 9      | 24.24%  |
| Toshiba             | 2         | 2      | 6.06%   |
| HGST                | 2         | 2      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 34     | 97.06%  |
| SSD  | 1         | 1      | 2.94%   |

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
| Works    | 46        | 54     | 51.11%  |
| Malfunc  | 34        | 35     | 37.78%  |
| Detected | 10        | 12     | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 68        | 77.27%  |
| AMD                              | 6         | 6.82%   |
| Nvidia                           | 3         | 3.41%   |
| VIA Technologies                 | 2         | 2.27%   |
| Silicon Integrated Systems [SiS] | 2         | 2.27%   |
| Samsung Electronics              | 2         | 2.27%   |
| Silicon Image                    | 1         | 1.14%   |
| SanDisk                          | 1         | 1.14%   |
| Marvell Technology Group         | 1         | 1.14%   |
| KIOXIA                           | 1         | 1.14%   |
| JMicron Technology               | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 7.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 6.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 6.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 6         | 5.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 5.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 4.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 3.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 2.88%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.92%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.92%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 1.92%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.96%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 0.96%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.96%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.96%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.96%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 0.96%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 0.96%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 0.96%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.96%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 54.64%  |
| IDE  | 36        | 37.11%  |
| RAID | 4         | 4.12%   |
| NVMe | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 81        | 90%     |
| AMD          | 7         | 7.78%   |
| GenuineTMx86 | 1         | 1.11%   |
| CentaurHauls | 1         | 1.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 6.67%   |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 3.33%   |
| Intel Pentium M processor 1.60GHz           | 2         | 2.22%   |
| Intel Pentium M processor 1.00GHz           | 2         | 2.22%   |
| Intel Genuine processor 800MHz              | 2         | 2.22%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 2         | 2.22%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 2.22%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 2.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 2.22%   |
| Intel Celeron (Mendocino)                   | 2         | 2.22%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.22%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 2.22%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.22%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.11%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.11%   |
| Intel Pentium M processor 1.20GHz           | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.11%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.11%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.11%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.11%   |
| Intel Genuine CPU T2600 @ 2.16GHz           | 1         | 1.11%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.11%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.11%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.11%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.11%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.11%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.11%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.11%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-2435M CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.11%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.11%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 17        | 18.89%  |
| Intel Core 2 Duo        | 12        | 13.33%  |
| Intel Celeron           | 11        | 12.22%  |
| Intel Core i5           | 8         | 8.89%   |
| Intel Pentium M         | 7         | 7.78%   |
| Intel Genuine           | 7         | 7.78%   |
| Intel Core i3           | 7         | 7.78%   |
| Intel Core i7           | 6         | 6.67%   |
| AMD E2                  | 2         | 2.22%   |
| Other                   | 1         | 1.11%   |
| Intel Pentium Silver    | 1         | 1.11%   |
| Intel Pentium Dual-Core | 1         | 1.11%   |
| Intel Pentium Dual      | 1         | 1.11%   |
| Intel Pentium 4         | 1         | 1.11%   |
| Intel Core 2            | 1         | 1.11%   |
| Intel Celeron Dual-Core | 1         | 1.11%   |
| CentaurHauls VIA Nano   | 1         | 1.11%   |
| AMD Sempron             | 1         | 1.11%   |
| AMD Ryzen 7             | 1         | 1.11%   |
| AMD E1                  | 1         | 1.11%   |
| AMD Athlon II           | 1         | 1.11%   |
| AMD Athlon 64 X2        | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 57.78%  |
| 1      | 31        | 34.44%  |
| 4      | 6         | 6.67%   |
| 8      | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 58.89%  |
| 2      | 37        | 41.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 70%     |
| 32-bit         | 27        | 30%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 9         | 10%     |
| 0x1067a    | 7         | 7.78%   |
| Unknown    | 7         | 7.78%   |
| 0x6fd      | 5         | 5.56%   |
| 0x6e8      | 4         | 4.44%   |
| 0x6d8      | 4         | 4.44%   |
| 0x6d6      | 4         | 4.44%   |
| 0x106ca    | 4         | 4.44%   |
| 0x40651    | 3         | 3.33%   |
| 0x306c3    | 3         | 3.33%   |
| 0x306a9    | 3         | 3.33%   |
| 0x30678    | 3         | 3.33%   |
| 0x206a7    | 3         | 3.33%   |
| 0x906e9    | 2         | 2.22%   |
| 0x806e9    | 2         | 2.22%   |
| 0x706a8    | 2         | 2.22%   |
| 0x66a      | 2         | 2.22%   |
| 0x406c4    | 2         | 2.22%   |
| 0x30661    | 2         | 2.22%   |
| 0x20655    | 2         | 2.22%   |
| 0x20652    | 2         | 2.22%   |
| 0x10676    | 2         | 2.22%   |
| 0x10661    | 2         | 2.22%   |
| 0xf24      | 1         | 1.11%   |
| 0x706a1    | 1         | 1.11%   |
| 0x6f6      | 1         | 1.11%   |
| 0x695      | 1         | 1.11%   |
| 0x506c9    | 1         | 1.11%   |
| 0x0a404102 | 1         | 1.11%   |
| 0x07030106 | 1         | 1.11%   |
| 0x0700010f | 1         | 1.11%   |
| 0x06006704 | 1         | 1.11%   |
| 0x02000032 | 1         | 1.11%   |
| 0x010000c8 | 1         | 1.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Bonnell         | 16        | 17.78%  |
| P6              | 13        | 14.44%  |
| Penryn          | 11        | 12.22%  |
| Core            | 8         | 8.89%   |
| Haswell         | 6         | 6.67%   |
| Silvermont      | 5         | 5.56%   |
| KabyLake        | 5         | 5.56%   |
| Unknown         | 5         | 5.56%   |
| Westmere        | 4         | 4.44%   |
| SandyBridge     | 3         | 3.33%   |
| IvyBridge       | 3         | 3.33%   |
| Goldmont plus   | 3         | 3.33%   |
| Puma            | 1         | 1.11%   |
| NetBurst        | 1         | 1.11%   |
| K8 Hammer       | 1         | 1.11%   |
| K8 & K10 hybrid | 1         | 1.11%   |
| K10             | 1         | 1.11%   |
| Jaguar          | 1         | 1.11%   |
| Goldmont        | 1         | 1.11%   |
| Excavator       | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 67.37%  |
| AMD                              | 16        | 16.84%  |
| Nvidia                           | 11        | 11.58%  |
| Neomagic                         | 2         | 2.11%   |
| VIA Technologies                 | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 13        | 11.71%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 7.21%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 6.31%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 5.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 4.5%    |
| Intel HD Graphics 620                                                                    | 3         | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.7%    |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 2         | 1.8%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 2         | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.8%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 1.8%    |
| Intel HD Graphics 630                                                                    | 2         | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.8%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.8%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.8%    |
| AMD RV200/M7 [Mobility Radeon 7500]                                                      | 2         | 1.8%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.8%    |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                            | 1         | 0.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.9%    |
| Nvidia NV11M [GeForce2 Go]                                                               | 1         | 0.9%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.9%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.9%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.9%    |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.9%    |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.9%    |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.9%    |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.9%    |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 0.9%    |
| Intel HD Graphics 500                                                                    | 1         | 0.9%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 57.78%  |
| 1 x AMD        | 14        | 15.56%  |
| 1 x Nvidia     | 7         | 7.78%   |
| 2 x Intel      | 5         | 5.56%   |
| Intel + Nvidia | 4         | 4.44%   |
| Other          | 2         | 2.22%   |
| 1 x Neomagic   | 2         | 2.22%   |
| 2 x AMD        | 1         | 1.11%   |
| 1 x VIA        | 1         | 1.11%   |
| 1 x SiS        | 1         | 1.11%   |
| Intel + AMD    | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 86.67%  |
| Unknown     | 9         | 10%     |
| Proprietary | 3         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 52.22%  |
| 0.01-0.5   | 32        | 35.56%  |
| 1.01-2.0   | 9         | 10%     |
| 3.01-4.0   | 1         | 1.11%   |
| 0.51-1.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 28.36%  |
| LG Display              | 11        | 16.42%  |
| Samsung Electronics     | 6         | 8.96%   |
| LG Philips              | 5         | 7.46%   |
| Chimei Innolux          | 5         | 7.46%   |
| Apple                   | 5         | 7.46%   |
| Lenovo                  | 4         | 5.97%   |
| BOE                     | 4         | 5.97%   |
| HannStar                | 3         | 4.48%   |
| Chi Mei Optoelectronics | 2         | 2.99%   |
| InfoVision              | 1         | 1.49%   |
| HJW                     | 1         | 1.49%   |
| CPT                     | 1         | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 2.99%   |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4346 1920x1200 331x207mm 15.4-inch    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 1.49%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 1.49%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 1.49%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 1.49%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 1.49%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 1.49%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 1.49%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.49%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 1.49%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 1.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.49%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 1.49%   |
| HannStar HSD089IFW1 HSD0325 1024x600 195x113mm 8.9-inch                  | 1         | 1.49%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 28        | 42.42%  |
| 1280x800 (WXGA)    | 12        | 18.18%  |
| 1024x600           | 8         | 12.12%  |
| 1920x1080 (FHD)    | 7         | 10.61%  |
| 1440x900 (WXGA+)   | 4         | 6.06%   |
| 1920x1200 (WUXGA)  | 2         | 3.03%   |
| 3840x2160 (4K)     | 1         | 1.52%   |
| 2288x1287          | 1         | 1.52%   |
| 1680x1050 (WSXGA+) | 1         | 1.52%   |
| 1600x900 (HD+)     | 1         | 1.52%   |
| 1280x720 (HD)      | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 37.31%  |
| 13     | 10        | 14.93%  |
| 10     | 8         | 11.94%  |
| 11     | 7         | 10.45%  |
| 14     | 6         | 8.96%   |
| 17     | 4         | 5.97%   |
| 12     | 2         | 2.99%   |
| 8      | 2         | 2.99%   |
| 32     | 1         | 1.49%   |
| 24     | 1         | 1.49%   |
| 18     | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 55.22%  |
| 201-300     | 21        | 31.34%  |
| 351-400     | 5         | 7.46%   |
| 101-200     | 2         | 2.99%   |
| 701-800     | 1         | 1.49%   |
| 501-600     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 45        | 69.23%  |
| 16/10 | 19        | 29.23%  |
| 3/2   | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 37.31%  |
| 81-90          | 14        | 20.9%   |
| 41-50          | 8         | 11.94%  |
| 51-60          | 7         | 10.45%  |
| 131-140        | 3         | 4.48%   |
| 71-80          | 2         | 2.99%   |
| 61-70          | 2         | 2.99%   |
| 1-40           | 2         | 2.99%   |
| 351-500        | 1         | 1.49%   |
| 201-250        | 1         | 1.49%   |
| 141-150        | 1         | 1.49%   |
| 121-130        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 31        | 46.27%  |
| 121-160       | 21        | 31.34%  |
| 51-100        | 14        | 20.9%   |
| More than 240 | 1         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 81        | 89.01%  |
| 0     | 7         | 7.69%   |
| 2     | 3         | 3.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 23.97%  |
| Realtek Semiconductor            | 31        | 21.23%  |
| Qualcomm Atheros                 | 29        | 19.86%  |
| Broadcom                         | 24        | 16.44%  |
| Marvell Technology Group         | 5         | 3.42%   |
| Nvidia                           | 3         | 2.05%   |
| Broadcom Limited                 | 3         | 2.05%   |
| Silicon Integrated Systems [SiS] | 2         | 1.37%   |
| Ralink                           | 2         | 1.37%   |
| MediaTek                         | 2         | 1.37%   |
| Texas Instruments                | 1         | 0.68%   |
| Samsung Electronics              | 1         | 0.68%   |
| Qualcomm Atheros Communications  | 1         | 0.68%   |
| NetGear                          | 1         | 0.68%   |
| Motorola PCS                     | 1         | 0.68%   |
| Linksys                          | 1         | 0.68%   |
| Huawei Technologies              | 1         | 0.68%   |
| Hewlett-Packard                  | 1         | 0.68%   |
| Attansic Technology              | 1         | 0.68%   |
| ASIX Electronics                 | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 7.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 6.25%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 8         | 4.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 3.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 3.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.27%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 1.7%    |
| Intel Wireless 8265 / 8275                                              | 3         | 1.7%    |
| Intel Wireless 7260                                                     | 3         | 1.7%    |
| Intel WiFi Link 5100                                                    | 3         | 1.7%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 1.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.7%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 1.7%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.14%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 1.14%   |
| Intel Wireless 7265                                                     | 2         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 1.14%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 1.14%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.14%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.57%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 35.87%  |
| Qualcomm Atheros                | 26        | 28.26%  |
| Broadcom                        | 19        | 20.65%  |
| Realtek Semiconductor           | 5         | 5.43%   |
| Ralink                          | 2         | 2.17%   |
| MediaTek                        | 2         | 2.17%   |
| Texas Instruments               | 1         | 1.09%   |
| Qualcomm Atheros Communications | 1         | 1.09%   |
| NetGear                         | 1         | 1.09%   |
| Linksys                         | 1         | 1.09%   |
| Broadcom Limited                | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 11        | 11.83%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 6         | 6.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 5         | 5.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 4.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 4         | 4.3%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 4.3%    |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.23%   |
| Intel Wireless 7260                                                           | 3         | 3.23%   |
| Intel WiFi Link 5100                                                          | 3         | 3.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 3.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 3         | 3.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.15%   |
| Intel Wireless 7265                                                           | 2         | 2.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 2.15%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.15%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.08%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                   | 1         | 1.08%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.08%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.08%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.08%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.08%   |
| NetGear A6150                                                                 | 1         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 1.08%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.08%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                             | 1         | 1.08%   |
| Intel Wireless 3165                                                           | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.08%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 1.08%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 29        | 38.16%  |
| Intel                            | 16        | 21.05%  |
| Broadcom                         | 9         | 11.84%  |
| Qualcomm Atheros                 | 6         | 7.89%   |
| Marvell Technology Group         | 5         | 6.58%   |
| Nvidia                           | 3         | 3.95%   |
| Silicon Integrated Systems [SiS] | 2         | 2.63%   |
| Broadcom Limited                 | 2         | 2.63%   |
| Samsung Electronics              | 1         | 1.32%   |
| Motorola PCS                     | 1         | 1.32%   |
| Attansic Technology              | 1         | 1.32%   |
| ASIX Electronics                 | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 18.42%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 10.53%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 7.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 3.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 2.63%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.63%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.63%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 2         | 2.63%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 2.63%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.32%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 1.32%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.32%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 1.32%   |
| Motorola PCS moto g84 5G                                               | 1         | 1.32%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 1.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.32%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 1.32%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.32%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.32%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                           | 1         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.32%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.32%   |
| Intel 82562EM/EX/GX - PRO/100 VM (LOM) Ethernet Controller Mobile      | 1         | 1.32%   |
| Intel 82551QM Ethernet Controller                                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.32%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.32%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.32%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 1.32%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 51.79%  |
| Ethernet | 74        | 44.05%  |
| Modem    | 7         | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 85.87%  |
| Ethernet | 13        | 14.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 71        | 78.89%  |
| 1     | 18        | 20%     |
| 0     | 1         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 79.35%  |
| Yes  | 19        | 20.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 20.93%  |
| Broadcom                        | 9         | 20.93%  |
| Apple                           | 6         | 13.95%  |
| IMC Networks                    | 3         | 6.98%   |
| Qualcomm Atheros Communications | 2         | 4.65%   |
| Lite-On Technology              | 2         | 4.65%   |
| Hewlett-Packard                 | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Cambridge Silicon Radio         | 2         | 4.65%   |
| Taiyo Yuden                     | 1         | 2.33%   |
| Realtek Semiconductor           | 1         | 2.33%   |
| Ralink Technology               | 1         | 2.33%   |
| Fujitsu                         | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |
| Alps Electric                   | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 13.95%  |
| Apple Bluetooth Host Controller                     | 3         | 6.98%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.65%   |
| IMC Networks Bluetooth Device                       | 2         | 4.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.65%   |
| Broadcom HP Portable SoftSailing                    | 2         | 4.65%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.33%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| IMC Networks Wireless_Device                        | 1         | 2.33%   |
| Fujitsu Bluetooth Device                            | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.33%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.33%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |
| Apple Bluetooth HCI                                 | 1         | 2.33%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 76.84%  |
| AMD                              | 11        | 11.58%  |
| Nvidia                           | 5         | 5.26%   |
| VIA Technologies                 | 2         | 2.11%   |
| Silicon Integrated Systems [SiS] | 2         | 2.11%   |
| ESS Technology                   | 2         | 2.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 19.81%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 7.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 4.72%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 4         | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.83%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.83%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.89%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 1.89%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.89%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 1.89%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                                             | 2         | 1.89%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.89%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.89%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.94%   |
| VIA Technologies VT82C686 AC97 Audio Controller                                                   | 1         | 0.94%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.94%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.94%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.94%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.94%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                                          | 1         | 0.94%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 0.94%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.94%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 1         | 0.94%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.94%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 31        | 28.97%  |
| SK hynix            | 25        | 23.36%  |
| Samsung Electronics | 16        | 14.95%  |
| Unknown             | 9         | 8.41%   |
| Micron Technology   | 6         | 5.61%   |
| Kingston            | 5         | 4.67%   |
| Ramaxel Technology  | 2         | 1.87%   |
| Nanya Technology    | 2         | 1.87%   |
| Crucial             | 2         | 1.87%   |
| Unknown (8A02)      | 1         | 0.93%   |
| Kingmax             | 1         | 0.93%   |
| G.Skill             | 1         | 0.93%   |
| ff                  | 1         | 0.93%   |
| fef5                | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Avant               | 1         | 0.93%   |
| Apacer              | 1         | 0.93%   |
| 4ea5                | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 9         | 7.96%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 4         | 3.54%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 2.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s       | 3         | 2.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 2.65%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 1.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 1.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 1.77%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 1.77%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 1.77%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 2         | 1.77%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 1.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.77%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 1.77%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s               | 2         | 1.77%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2                           | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR 100MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 0.88%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM SDRAM                            | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.88%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.88%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 0.88%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 0.88%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.88%   |
| SK hynix RAM Module 2GB DIMM DDR2 667MT/s                      | 1         | 0.88%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 32        | 35.56%  |
| DDR2    | 21        | 23.33%  |
| SDRAM   | 14        | 15.56%  |
| DDR4    | 7         | 7.78%   |
| DDR     | 6         | 6.67%   |
| DRAM    | 4         | 4.44%   |
| LPDDR4  | 3         | 3.33%   |
| LPDDR3  | 1         | 1.11%   |
| DDR5    | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 80        | 90.91%  |
| DIMM         | 4         | 4.55%   |
| Unknown      | 3         | 3.41%   |
| Row Of Chips | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 37        | 35.92%  |
| 1024  | 22        | 21.36%  |
| 4096  | 20        | 19.42%  |
| 8192  | 9         | 8.74%   |
| 512   | 8         | 7.77%   |
| 256   | 3         | 2.91%   |
| 64    | 2         | 1.94%   |
| 16384 | 1         | 0.97%   |
| 232   | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 22.11%  |
| 1600    | 18        | 18.95%  |
| 1067    | 8         | 8.42%   |
| 667     | 8         | 8.42%   |
| 533     | 5         | 5.26%   |
| 2667    | 4         | 4.21%   |
| 2400    | 4         | 4.21%   |
| 1334    | 4         | 4.21%   |
| 1333    | 4         | 4.21%   |
| 4199    | 3         | 3.16%   |
| 975     | 3         | 3.16%   |
| 800     | 3         | 3.16%   |
| 200     | 2         | 2.11%   |
| 5600    | 1         | 1.05%   |
| 3266    | 1         | 1.05%   |
| 3200    | 1         | 1.05%   |
| 2048    | 1         | 1.05%   |
| 1867    | 1         | 1.05%   |
| 1866    | 1         | 1.05%   |
| 266     | 1         | 1.05%   |
| 100     | 1         | 1.05%   |

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
| Chicony Electronics                    | 14        | 22.95%  |
| IMC Networks                           | 6         | 9.84%   |
| Suyin                                  | 5         | 8.2%    |
| Microdia                               | 5         | 8.2%    |
| Realtek Semiconductor                  | 4         | 6.56%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.56%   |
| Bison Electronics                      | 4         | 6.56%   |
| Apple                                  | 4         | 6.56%   |
| Sunplus Innovation Technology          | 3         | 4.92%   |
| Syntek                                 | 2         | 3.28%   |
| Silicon Motion                         | 2         | 3.28%   |
| Pixart Imaging                         | 2         | 3.28%   |
| Lenovo                                 | 2         | 3.28%   |
| Z-Star Microelectronics                | 1         | 1.64%   |
| Jieli Technology                       | 1         | 1.64%   |
| Importek                               | 1         | 1.64%   |
| Acer                                   | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                  | 3         | 4.92%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 3.28%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 2         | 3.28%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 3.28%   |
| Chicony HD WebCam                              | 2         | 3.28%   |
| Bison BisonCam, NB Pro                         | 2         | 3.28%   |
| Apple Built-in iSight                          | 2         | 3.28%   |
| Z-Star Vimicro USB Camera (Altair)             | 1         | 1.64%   |
| Syntek Integrated Camera                       | 1         | 1.64%   |
| Syntek HP Webcam                               | 1         | 1.64%   |
| Suyin USB2.0 UVC 1.3M WebCam                   | 1         | 1.64%   |
| Suyin USB 2.0 Camera                           | 1         | 1.64%   |
| Suyin Laptop_Integrated_Webcam_2HDM            | 1         | 1.64%   |
| Suyin Integrated_Webcam_HD                     | 1         | 1.64%   |
| Suyin Acer/Lenovo Webcam [CN0316]              | 1         | 1.64%   |
| Sunplus HD WebCam                              | 1         | 1.64%   |
| Silicon Motion Lenovo EasyCamera               | 1         | 1.64%   |
| Silicon Motion HP Webcam-101 Integrated Camera | 1         | 1.64%   |
| Realtek USB2.0 VGA UVC WebCam                  | 1         | 1.64%   |
| Realtek Integrated_Webcam_HD                   | 1         | 1.64%   |
| Realtek Integrated Webcam HD                   | 1         | 1.64%   |
| Realtek HD WebCam                              | 1         | 1.64%   |
| Microdia Integrated_Webcam_5M                  | 1         | 1.64%   |
| Microdia Integrated Webcam                     | 1         | 1.64%   |
| Lenovo Integrated Webcam                       | 1         | 1.64%   |
| Lenovo CNF7237&CNF7238                         | 1         | 1.64%   |
| Jieli USB PHY 2.0                              | 1         | 1.64%   |
| Importek FJ Camera                             | 1         | 1.64%   |
| IMC Networks USB 2.0 UVC VGA WebCam            | 1         | 1.64%   |
| IMC Networks TOSHIBA Web Camera - HD           | 1         | 1.64%   |
| Chicony Webcam-101                             | 1         | 1.64%   |
| Chicony VGA 30fps UVC Webcam                   | 1         | 1.64%   |
| Chicony Integrated HP HD Webcam                | 1         | 1.64%   |
| Chicony Integrated Camera                      | 1         | 1.64%   |
| Chicony HP Webcam                              | 1         | 1.64%   |
| Chicony HP HD Webcam [Fixed]                   | 1         | 1.64%   |
| Chicony HP HD Webcam                           | 1         | 1.64%   |
| Chicony EasyCamera                             | 1         | 1.64%   |
| Chicony CNF8243 Webcam                         | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 6         | 60%     |
| Validity Sensors | 2         | 20%     |
| Upek             | 2         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 4         | 40%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 20%     |
| AuthenTec AES1600                                      | 2         | 20%     |
| Validity Sensors VFS491                                | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor                | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 75%     |
| O2 Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 50%     |
| O2 Micro Oz776 SmartCard Reader                | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 60        | 66.67%  |
| 1     | 23        | 25.56%  |
| 2     | 6         | 6.67%   |
| 3     | 1         | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 20        | 55.56%  |
| Fingerprint reader    | 10        | 27.78%  |
| Chipcard              | 3         | 8.33%   |
| Multimedia controller | 2         | 5.56%   |
| Net/wireless          | 1         | 2.78%   |


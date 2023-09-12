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

Total: 110

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite T110              | Notebook    | [ecb4e047b3](https://linux-hardware.org/?probe=ecb4e047b3) | Aug 11, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [05b5124d92](https://linux-hardware.org/?probe=05b5124d92) | Aug 09, 2023 |
| HP            | 255 G3                      | Notebook    | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | Notebook    | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| HP            | Presario CQ56               | Notebook    | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [dc0f48314d](https://linux-hardware.org/?probe=dc0f48314d) | Jul 15, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [54dfdc8842](https://linux-hardware.org/?probe=54dfdc8842) | Jun 28, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| HP            | 620                         | Notebook    | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Intel         | H61                         | Desktop     | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| HP            | G61                         | Notebook    | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [f33074a4c8](https://linux-hardware.org/?probe=f33074a4c8) | Apr 03, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [2f380f0d1a](https://linux-hardware.org/?probe=2f380f0d1a) | Apr 03, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
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
| antiX 21       | 34        | 39.53%  |
| antiX 22       | 23        | 26.74%  |
| antiX 19.2     | 8         | 9.3%    |
| antiX 19.3     | 5         | 5.81%   |
| antiX 17.4.1   | 4         | 4.65%   |
| antiX 21-runit | 3         | 3.49%   |
| antiX 19.4     | 2         | 2.33%   |
| antiX 19.1     | 2         | 2.33%   |
| antiX 19.5     | 1         | 1.16%   |
| antiX 17.2.1   | 1         | 1.16%   |
| antiX 17.1     | 1         | 1.16%   |
| antiX 17       | 1         | 1.16%   |
| antiX 15       | 1         | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 15        | 17.44%  |
| 5.10.142-antix.2-amd64-smp   | 11        | 12.79%  |
| 4.9.0-279-antix.1-amd64-smp  | 10        | 11.63%  |
| 4.9.0-326-antix.1-amd64-smp  | 9         | 10.47%  |
| 5.10.57-antix.1-amd64-smp    | 8         | 9.3%    |
| 4.9.235-antix.1-amd64-smp    | 4         | 4.65%   |
| 4.9.160-antix.2-486-smp      | 4         | 4.65%   |
| 4.9.0-326-antix.1-486-smp    | 4         | 4.65%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 3.49%   |
| 4.9.212-antix.1-486-smp      | 3         | 3.49%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 2.33%   |
| 4.9.200-antix.1-486-smp      | 2         | 2.33%   |
| 6.2.9-1-liquorix-amd64       | 1         | 1.16%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.16%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.16%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.16%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.16%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.16%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.16%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.16%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.16%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.16%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 39        | 45.88%  |
| 5.10.142 | 11        | 12.94%  |
| 5.10.57  | 8         | 9.41%   |
| 4.9.212  | 6         | 7.06%   |
| 4.9.160  | 5         | 5.88%   |
| 4.9.235  | 4         | 4.71%   |
| 5.10.88  | 2         | 2.35%   |
| 4.9.200  | 2         | 2.35%   |
| 6.2.9    | 1         | 1.18%   |
| 5.14.0   | 1         | 1.18%   |
| 5.10.27  | 1         | 1.18%   |
| 4.9.87   | 1         | 1.18%   |
| 4.19.202 | 1         | 1.18%   |
| 4.19.100 | 1         | 1.18%   |
| 4.19.0   | 1         | 1.18%   |
| 4.10.5   | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 57        | 67.06%  |
| 5.10    | 22        | 25.88%  |
| 4.19    | 3         | 3.53%   |
| 6.2     | 1         | 1.18%   |
| 5.14    | 1         | 1.18%   |
| 4.10    | 1         | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 62.35%  |
| i686   | 31        | 36.47%  |
| i586   | 1         | 1.18%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 38        | 44.71%  |
| icewm        | 37        | 43.53%  |
| XFCE         | 4         | 4.71%   |
| fluxbox      | 2         | 2.35%   |
| jwm          | 1         | 1.18%   |
| herbstluftwm | 1         | 1.18%   |
| GNOME        | 1         | 1.18%   |
| Cinnamon     | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 83        | 97.65%  |
| Tty  | 2         | 2.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 55.29%  |
| SLiM    | 22        | 25.88%  |
| SLIMSKI | 8         | 9.41%   |
| LightDM | 6         | 7.06%   |
| XDM     | 1         | 1.18%   |
| SDDM    | 1         | 1.18%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 32        | 37.65%  |
| ru_RU   | 8         | 9.41%   |
| pt_BR   | 5         | 5.88%   |
| de_DE   | 5         | 5.88%   |
| pl_PL   | 3         | 3.53%   |
| ja_JP   | 3         | 3.53%   |
| it_IT   | 3         | 3.53%   |
| es_ES   | 3         | 3.53%   |
| en_GB   | 3         | 3.53%   |
| Unknown | 3         | 3.53%   |
| sk_SK   | 2         | 2.35%   |
| nl_NL   | 2         | 2.35%   |
| es_AR   | 2         | 2.35%   |
| en_AU   | 2         | 2.35%   |
| zh_HK   | 1         | 1.18%   |
| uk_UA   | 1         | 1.18%   |
| hu_HU   | 1         | 1.18%   |
| fr_FR   | 1         | 1.18%   |
| fr_BE   | 1         | 1.18%   |
| es_VE   | 1         | 1.18%   |
| es_MX   | 1         | 1.18%   |
| en_NZ   | 1         | 1.18%   |
| de_AT   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 67        | 78.82%  |
| EFI  | 18        | 21.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 73        | 85.88%  |
| Overlay  | 10        | 11.76%  |
| Xfs      | 1         | 1.18%   |
| Reiserfs | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 63        | 74.12%  |
| GPT     | 20        | 23.53%  |
| Unknown | 2         | 2.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 77.91%  |
| Yes       | 19        | 22.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 63.53%  |
| Yes       | 31        | 36.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 12.94%  |
| ASUSTek Computer    | 11        | 12.94%  |
| Lenovo              | 9         | 10.59%  |
| Acer                | 8         | 9.41%   |
| MSI                 | 5         | 5.88%   |
| IBM                 | 5         | 5.88%   |
| Dell                | 5         | 5.88%   |
| Intel               | 4         | 4.71%   |
| Toshiba             | 3         | 3.53%   |
| Gigabyte Technology | 3         | 3.53%   |
| Fujitsu             | 3         | 3.53%   |
| Unknown             | 3         | 3.53%   |
| KOHJINSHA           | 2         | 2.35%   |
| Apple               | 2         | 2.35%   |
| VXL                 | 1         | 1.18%   |
| Samsung Electronics | 1         | 1.18%   |
| Radiant Systems     | 1         | 1.18%   |
| Pegatron            | 1         | 1.18%   |
| Packard Bell        | 1         | 1.18%   |
| Medion              | 1         | 1.18%   |
| Google              | 1         | 1.18%   |
| Compaq              | 1         | 1.18%   |
| Biostar             | 1         | 1.18%   |
| AZW                 | 1         | 1.18%   |
| AMI                 | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 4.71%   |
| MSI US Desktop                     | 2         | 2.35%   |
| IBM 260921H                        | 2         | 2.35%   |
| HP Mini 110-3700                   | 2         | 2.35%   |
| Fujitsu FMVNU6G1C                  | 2         | 2.35%   |
| VXL TC7520d                        | 1         | 1.18%   |
| Toshiba Satellite T110             | 1         | 1.18%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.18%   |
| Toshiba Satellite 1905             | 1         | 1.18%   |
| Samsung SQ1S                       | 1         | 1.18%   |
| Radiant Systems P845               | 1         | 1.18%   |
| Pegatron VC902AA-ABF p6136fr       | 1         | 1.18%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.18%   |
| MSI MS-7C56                        | 1         | 1.18%   |
| MSI MS-7B17                        | 1         | 1.18%   |
| MSI GE62 7RE                       | 1         | 1.18%   |
| Medion WIM2170                     | 1         | 1.18%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.18%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.18%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.18%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.18%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.18%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.18%   |
| Lenovo G550 2958                   | 1         | 1.18%   |
| Lenovo 3000 V100 076346G           | 1         | 1.18%   |
| KOHJINSHA SX series                | 1         | 1.18%   |
| KOHJINSHA SC series                | 1         | 1.18%   |
| Intel powered classmate PC         | 1         | 1.18%   |
| Intel H61                          | 1         | 1.18%   |
| Intel D525MW AAE93082-401          | 1         | 1.18%   |
| Intel D425KT AAE93083-400          | 1         | 1.18%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.18%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.18%   |
| IBM ThinkPad T40 237342G           | 1         | 1.18%   |
| HP t5740                           | 1         | 1.18%   |
| HP Presario CQ56                   | 1         | 1.18%   |
| HP Pavilion dv2700                 | 1         | 1.18%   |
| HP Mini 5101                       | 1         | 1.18%   |
| HP EliteBook 8770w                 | 1         | 1.18%   |
| HP EliteBook 2570p                 | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 8.24%   |
| Unknown               | 4         | 4.71%   |
| Toshiba Satellite     | 3         | 3.53%   |
| Lenovo IdeaPad        | 3         | 3.53%   |
| IBM ThinkPad          | 3         | 3.53%   |
| HP Mini               | 3         | 3.53%   |
| Dell Latitude         | 3         | 3.53%   |
| MSI US                | 2         | 2.35%   |
| Lenovo ThinkPad       | 2         | 2.35%   |
| IBM 260921H           | 2         | 2.35%   |
| HP EliteBook          | 2         | 2.35%   |
| Fujitsu FMVNU6G1C     | 2         | 2.35%   |
| ASUS VivoBook         | 2         | 2.35%   |
| VXL TC7520d           | 1         | 1.18%   |
| Samsung SQ1S          | 1         | 1.18%   |
| Radiant Systems P845  | 1         | 1.18%   |
| Pegatron VC902AA-ABF  | 1         | 1.18%   |
| Packard Bell EasyNote | 1         | 1.18%   |
| MSI MS-7C56           | 1         | 1.18%   |
| MSI MS-7B17           | 1         | 1.18%   |
| MSI GE62              | 1         | 1.18%   |
| Medion WIM2170        | 1         | 1.18%   |
| Lenovo ThinkCentre    | 1         | 1.18%   |
| Lenovo G550           | 1         | 1.18%   |
| Lenovo 3000           | 1         | 1.18%   |
| KOHJINSHA SX          | 1         | 1.18%   |
| KOHJINSHA SC          | 1         | 1.18%   |
| Intel powered         | 1         | 1.18%   |
| Intel H61             | 1         | 1.18%   |
| Intel D525MW          | 1         | 1.18%   |
| Intel D425KT          | 1         | 1.18%   |
| HP t5740              | 1         | 1.18%   |
| HP Presario           | 1         | 1.18%   |
| HP Pavilion           | 1         | 1.18%   |
| HP All-in-One         | 1         | 1.18%   |
| HP 620                | 1         | 1.18%   |
| HP 255                | 1         | 1.18%   |
| Google Candy          | 1         | 1.18%   |
| Gigabyte Z790         | 1         | 1.18%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 13        | 15.29%  |
| 2007    | 11        | 12.94%  |
| 2008    | 9         | 10.59%  |
| 2012    | 6         | 7.06%   |
| 2010    | 6         | 7.06%   |
| 2014    | 4         | 4.71%   |
| 2013    | 4         | 4.71%   |
| 2011    | 4         | 4.71%   |
| 2021    | 3         | 3.53%   |
| 2020    | 3         | 3.53%   |
| 2018    | 3         | 3.53%   |
| 2017    | 3         | 3.53%   |
| 2005    | 3         | 3.53%   |
| 2003    | 3         | 3.53%   |
| 2022    | 2         | 2.35%   |
| 2004    | 2         | 2.35%   |
| 1999    | 2         | 2.35%   |
| 2019    | 1         | 1.18%   |
| 2016    | 1         | 1.18%   |
| 2006    | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 60        | 70.59%  |
| Desktop    | 20        | 23.53%  |
| Mini pc    | 4         | 4.71%   |
| All in one | 1         | 1.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 85        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 98.82%  |
| Yes  | 1         | 1.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 25        | 29.41%  |
| 1.01-2.0    | 14        | 16.47%  |
| 0.51-1.0    | 11        | 12.94%  |
| 2.01-3.0    | 10        | 11.76%  |
| 4.01-8.0    | 6         | 7.06%   |
| 0.01-0.5    | 6         | 7.06%   |
| 32.01-64.0  | 5         | 5.88%   |
| 8.01-16.0   | 4         | 4.71%   |
| 64.01-256.0 | 2         | 2.35%   |
| 16.01-24.0  | 2         | 2.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 31        | 36.05%  |
| 0.01-0.5   | 30        | 34.88%  |
| 1.01-2.0   | 16        | 18.6%   |
| 2.01-3.0   | 6         | 6.98%   |
| 4.01-8.0   | 2         | 2.33%   |
| 32.01-64.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 72.09%  |
| 2      | 13        | 15.12%  |
| 3      | 4         | 4.65%   |
| 4      | 3         | 3.49%   |
| 0      | 3         | 3.49%   |
| 5      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 56.47%  |
| Yes       | 37        | 43.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 88.24%  |
| No        | 10        | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 80%     |
| No        | 17        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 58.82%  |
| Yes       | 35        | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 16.47%  |
| Russia      | 10        | 11.76%  |
| Hong Kong   | 10        | 11.76%  |
| Germany     | 7         | 8.24%   |
| Brazil      | 5         | 5.88%   |
| Poland      | 4         | 4.71%   |
| Netherlands | 3         | 3.53%   |
| Japan       | 3         | 3.53%   |
| Italy       | 3         | 3.53%   |
| UK          | 2         | 2.35%   |
| Spain       | 2         | 2.35%   |
| Slovakia    | 2         | 2.35%   |
| Hungary     | 2         | 2.35%   |
| France      | 2         | 2.35%   |
| Australia   | 2         | 2.35%   |
| Argentina   | 2         | 2.35%   |
| Uruguay     | 1         | 1.18%   |
| Ukraine     | 1         | 1.18%   |
| New Zealand | 1         | 1.18%   |
| Mexico      | 1         | 1.18%   |
| Kenya       | 1         | 1.18%   |
| Kazakhstan  | 1         | 1.18%   |
| Greece      | 1         | 1.18%   |
| Denmark     | 1         | 1.18%   |
| Chile       | 1         | 1.18%   |
| Bulgaria    | 1         | 1.18%   |
| Belgium     | 1         | 1.18%   |
| Austria     | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 8.05%   |
| Sydney                    | 2         | 2.3%    |
| St Petersburg             | 2         | 2.3%    |
| Moscow                    | 2         | 2.3%    |
| Central                   | 2         | 2.3%    |
| Bratislava                | 2         | 2.3%    |
| Zagnansk                  | 1         | 1.15%   |
| Yuzhno-Sakhalinsk         | 1         | 1.15%   |
| Yokohama                  | 1         | 1.15%   |
| Ybbs an der Donau         | 1         | 1.15%   |
| Whitney                   | 1         | 1.15%   |
| Warsaw                    | 1         | 1.15%   |
| Violes                    | 1         | 1.15%   |
| Torricella Sicura         | 1         | 1.15%   |
| Toms River                | 1         | 1.15%   |
| Sofia                     | 1         | 1.15%   |
| Sheung Shui               | 1         | 1.15%   |
| Seattle                   | 1         | 1.15%   |
| Schloss Holte-Stukenbrock | 1         | 1.15%   |
| Santiago                  | 1         | 1.15%   |
| Salto                     | 1         | 1.15%   |
| Rotterdam                 | 1         | 1.15%   |
| Romilly-sur-Seine         | 1         | 1.15%   |
| Reutlingen                | 1         | 1.15%   |
| Purmerend                 | 1         | 1.15%   |
| Pritzwalk                 | 1         | 1.15%   |
| Portland                  | 1         | 1.15%   |
| Pomaz                     | 1         | 1.15%   |
| Padova                    | 1         | 1.15%   |
| Otwock                    | 1         | 1.15%   |
| Nova Londrina             | 1         | 1.15%   |
| Norden                    | 1         | 1.15%   |
| Neyagawa                  | 1         | 1.15%   |
| Nairobi                   | 1         | 1.15%   |
| Montevideo                | 1         | 1.15%   |
| Mittegrossefehn           | 1         | 1.15%   |
| Milan                     | 1         | 1.15%   |
| Miami                     | 1         | 1.15%   |
| Mechanicsburg             | 1         | 1.15%   |
| Mason                     | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 19        | 21     | 18.1%   |
| Seagate                   | 15        | 15     | 14.29%  |
| Hitachi                   | 13        | 14     | 12.38%  |
| Samsung Electronics       | 12        | 14     | 11.43%  |
| Toshiba                   | 10        | 11     | 9.52%   |
| Unknown                   | 4         | 4      | 3.81%   |
| Kingston                  | 4         | 5      | 3.81%   |
| BHT                       | 3         | 5      | 2.86%   |
| Micron/Crucial Technology | 2         | 2      | 1.9%    |
| Maxtor                    | 2         | 2      | 1.9%    |
| Intel                     | 2         | 2      | 1.9%    |
| HGST                      | 2         | 2      | 1.9%    |
| Unknown                   | 2         | 2      | 1.9%    |
| Zheino                    | 1         | 1      | 0.95%   |
| Unknown (CF)              | 1         | 1      | 0.95%   |
| Transcend                 | 1         | 1      | 0.95%   |
| SanDisk                   | 1         | 1      | 0.95%   |
| RECADATA                  | 1         | 1      | 0.95%   |
| PNY                       | 1         | 1      | 0.95%   |
| OCZ                       | 1         | 1      | 0.95%   |
| IBM/Hitachi               | 1         | 1      | 0.95%   |
| Hewlett-Packard           | 1         | 1      | 0.95%   |
| Fujitsu                   | 1         | 1      | 0.95%   |
| Crucial                   | 1         | 1      | 0.95%   |
| China                     | 1         | 1      | 0.95%   |
| BIWIN                     | 1         | 1      | 0.95%   |
| ASUS-PHISON               | 1         | 1      | 0.95%   |
| Apacer                    | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD800AAJS-75M0A0 80GB               | 2         | 1.85%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 1.85%   |
| WDC WD10SPZX-80Z10T2 1TB                | 2         | 1.85%   |
| Toshiba MQ01ABD050V -63 500GB           | 2         | 1.85%   |
| Seagate ST980811AS 80GB                 | 2         | 1.85%   |
| Samsung SSD 850 EVO 120GB               | 2         | 1.85%   |
| Samsung SSD 750 EVO 120GB               | 2         | 1.85%   |
| Maxtor Z1 SSD 240GB                     | 2         | 1.85%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.85%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 1.85%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 1.85%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 1.85%   |
| BHT WR202F0032G 670270F5 32GB SSD       | 2         | 1.85%   |
| Unknown                                 | 2         | 1.85%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 0.93%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 0.93%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 0.93%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.93%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.93%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 0.93%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 0.93%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.93%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.93%   |
| WDC WD205BA 21GB                        | 1         | 0.93%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.93%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 0.93%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.93%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 0.93%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 0.93%   |
| WDC WD10EADS-65M2B0 1TB                 | 1         | 0.93%   |
| Unknown SR64G  64GB                     | 1         | 0.93%   |
| Unknown SD/MMC/MS PRO 1GB               | 1         | 0.93%   |
| Unknown HAG2e  16GB                     | 1         | 0.93%   |
| Unknown 2GB ATA Flash Disk              | 1         | 0.93%   |
| Unknown (CF) Card 16GB SSD              | 1         | 0.93%   |
| Transcend SSD 2GB                       | 1         | 0.93%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 0.93%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 21     | 28.79%  |
| Seagate             | 15        | 15     | 22.73%  |
| Hitachi             | 13        | 14     | 19.7%   |
| Toshiba             | 8         | 9      | 12.12%  |
| Samsung Electronics | 5         | 6      | 7.58%   |
| Unknown             | 2         | 2      | 3.03%   |
| HGST                | 2         | 2      | 3.03%   |
| IBM/Hitachi         | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 15.63%  |
| Kingston            | 4         | 5      | 12.5%   |
| BHT                 | 3         | 5      | 9.38%   |
| Toshiba             | 2         | 2      | 6.25%   |
| Maxtor              | 2         | 2      | 6.25%   |
| Unknown             | 2         | 2      | 6.25%   |
| Zheino              | 1         | 1      | 3.13%   |
| Unknown (CF)        | 1         | 1      | 3.13%   |
| Transcend           | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| RECADATA            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| BIWIN               | 1         | 1      | 3.13%   |
| ASUS-PHISON         | 1         | 1      | 3.13%   |
| Apacer              | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 71     | 62.11%  |
| SSD  | 30        | 35     | 31.58%  |
| NVMe | 4         | 6      | 4.21%   |
| MMC  | 2         | 2      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 105    | 91.95%  |
| NVMe | 4         | 6      | 4.6%    |
| MMC  | 2         | 2      | 2.3%    |
| SAS  | 1         | 1      | 1.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 92     | 85.39%  |
| 0.51-1.0   | 11        | 11     | 12.36%  |
| 1.01-2.0   | 1         | 1      | 1.12%   |
| 4.01-10.0  | 1         | 2      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 31.03%  |
| 1-20           | 21        | 24.14%  |
| 51-100         | 11        | 12.64%  |
| 21-50          | 10        | 11.49%  |
| 251-500        | 9         | 10.34%  |
| 501-1000       | 6         | 6.9%    |
| More than 3000 | 1         | 1.15%   |
| 1001-2000      | 1         | 1.15%   |
| Unknown        | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 76.47%  |
| 21-50          | 7         | 8.24%   |
| 101-250        | 6         | 7.06%   |
| 51-100         | 4         | 4.71%   |
| More than 3000 | 1         | 1.18%   |
| 501-1000       | 1         | 1.18%   |
| Unknown        | 1         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2         | 2      | 5.71%   |
| Seagate ST980811AS 80GB                     | 2         | 2      | 5.71%   |
| Hitachi HTS542525K9SA00 250GB               | 2         | 2      | 5.71%   |
| WDC WD800JB-00ETA0 80GB                     | 1         | 1      | 2.86%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.86%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 1         | 1      | 2.86%   |
| WDC WD2500BEVT-22ZCT0 250GB                 | 1         | 1      | 2.86%   |
| WDC WD205BA 21GB                            | 1         | 1      | 2.86%   |
| WDC WD10EADS-65M2B0 1TB                     | 1         | 1      | 2.86%   |
| Toshiba MK2555GSX 250GB                     | 1         | 1      | 2.86%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.86%   |
| Seagate ST9160314AS 160GB                   | 1         | 1      | 2.86%   |
| Seagate ST9160310AS 160GB                   | 1         | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.86%   |
| Seagate ST3320620AS 320GB                   | 1         | 1      | 2.86%   |
| Seagate ST3320413CS 320GB                   | 1         | 1      | 2.86%   |
| Seagate ST320LT007-9ZV142 320GB             | 1         | 1      | 2.86%   |
| SanDisk sandisk120 120GB SSD                | 1         | 1      | 2.86%   |
| Samsung Electronics HM161GI 160GB           | 1         | 1      | 2.86%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1         | 1      | 2.86%   |
| Hitachi HTS725050A7E630 500GB               | 1         | 1      | 2.86%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 2.86%   |
| Hitachi HTS721060G9AT00 64GB                | 1         | 1      | 2.86%   |
| Hitachi HTS548040M9AT00 40GB                | 1         | 1      | 2.86%   |
| Hitachi HTS543225A7A384 250GB               | 1         | 1      | 2.86%   |
| Hitachi HTS541612J9SA00 120GB               | 1         | 1      | 2.86%   |
| Hitachi HTC426040G8CE00 40GB                | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.86%   |
| China M.2 SSD 128GB                         | 1         | 1      | 2.86%   |
| BIWIN SSD 32GB                              | 1         | 1      | 2.86%   |
| Apacer 32GB SATA Flash Drive SSD            | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 9         | 9      | 25.71%  |
| Seagate                   | 9         | 9      | 25.71%  |
| Hitachi                   | 9         | 9      | 25.71%  |
| Toshiba                   | 1         | 1      | 2.86%   |
| SanDisk                   | 1         | 1      | 2.86%   |
| Samsung Electronics       | 1         | 1      | 2.86%   |
| Micron/Crucial Technology | 1         | 1      | 2.86%   |
| HGST                      | 1         | 1      | 2.86%   |
| China                     | 1         | 1      | 2.86%   |
| BIWIN                     | 1         | 1      | 2.86%   |
| Apacer                    | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 30%     |
| Seagate             | 9         | 9      | 30%     |
| Hitachi             | 9         | 9      | 30%     |
| Toshiba             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 30     | 85.71%  |
| SSD  | 4         | 4      | 11.43%  |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 48        | 70     | 52.75%  |
| Malfunc  | 35        | 35     | 38.46%  |
| Detected | 8         | 9      | 8.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 65        | 68.42%  |
| AMD                              | 8         | 8.42%   |
| Nvidia                           | 5         | 5.26%   |
| ASMedia Technology               | 4         | 4.21%   |
| VIA Technologies                 | 3         | 3.16%   |
| Silicon Integrated Systems [SiS] | 2         | 2.11%   |
| Samsung Electronics              | 2         | 2.11%   |
| Micron/Crucial Technology        | 2         | 2.11%   |
| ULi Electronics                  | 1         | 1.05%   |
| Silicon Image                    | 1         | 1.05%   |
| LSI Logic / Symbios Logic        | 1         | 1.05%   |
| JMicron Technology               | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                     | 8         | 6.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 6         | 5.22%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 5.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 5         | 4.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 4         | 3.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 4         | 3.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 4         | 3.48%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                        | 4         | 3.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 3         | 2.61%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 3         | 2.61%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3         | 2.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                   | 2         | 1.74%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2         | 1.74%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                    | 2         | 1.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 2         | 1.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.74%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1         | 0.87%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 0.87%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller               | 1         | 0.87%   |
| ULi ULi M5288 SATA                                                            | 1         | 0.87%   |
| ULi M5229 IDE                                                                 | 1         | 0.87%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller              | 1         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.87%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 0.87%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1         | 0.87%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 0.87%   |
| Nvidia MCP67 IDE Controller                                                   | 1         | 0.87%   |
| Nvidia MCP67 AHCI Controller                                                  | 1         | 0.87%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 0.87%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1         | 0.87%   |
| Nvidia CK804 Serial ATA Controller                                            | 1         | 0.87%   |
| Nvidia CK804 IDE                                                              | 1         | 0.87%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 47.96%  |
| IDE  | 42        | 42.86%  |
| RAID | 4         | 4.08%   |
| NVMe | 4         | 4.08%   |
| SAS  | 1         | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 70        | 82.35%  |
| AMD          | 12        | 14.12%  |
| CentaurHauls | 2         | 2.35%   |
| GenuineTMx86 | 1         | 1.18%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 4.71%   |
| Intel Pentium M processor 1.60GHz           | 2         | 2.35%   |
| Intel Pentium M processor 1.00GHz           | 2         | 2.35%   |
| Intel Genuine processor 800MHz              | 2         | 2.35%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 2.35%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 2.35%   |
| Intel Celeron (Mendocino)                   | 2         | 2.35%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.35%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 2.35%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 2.35%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.35%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 2.35%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.18%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.18%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.18%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.18%   |
| Intel Pentium II (Deschutes)                | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.18%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.18%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.18%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.18%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.18%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.18%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.18%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.18%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.18%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.18%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.18%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.18%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.18%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.18%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.18%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.18%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 15        | 17.65%  |
| Intel Celeron           | 9         | 10.59%  |
| Intel Core 2 Duo        | 7         | 8.24%   |
| Intel Pentium M         | 6         | 7.06%   |
| Intel Core i7           | 6         | 7.06%   |
| Other                   | 5         | 5.88%   |
| Intel Core i5           | 5         | 5.88%   |
| Intel Genuine           | 4         | 4.71%   |
| Intel Core i3           | 3         | 3.53%   |
| Intel Pentium Dual-Core | 2         | 2.35%   |
| Intel Pentium Dual      | 2         | 2.35%   |
| AMD E2                  | 2         | 2.35%   |
| AMD Athlon 64 X2        | 2         | 2.35%   |
| Intel Xeon              | 1         | 1.18%   |
| Intel Pentium Silver    | 1         | 1.18%   |
| Intel Pentium 4         | 1         | 1.18%   |
| Intel Pentium           | 1         | 1.18%   |
| Intel Core i9           | 1         | 1.18%   |
| Intel Core 2 Quad       | 1         | 1.18%   |
| Intel Celeron M         | 1         | 1.18%   |
| Intel Celeron Dual-Core | 1         | 1.18%   |
| CentaurHauls VIA Nano   | 1         | 1.18%   |
| CentaurHauls VIA Eden   | 1         | 1.18%   |
| AMD Sempron             | 1         | 1.18%   |
| AMD Ryzen 7             | 1         | 1.18%   |
| AMD Phenom              | 1         | 1.18%   |
| AMD E1                  | 1         | 1.18%   |
| AMD Athlon II           | 1         | 1.18%   |
| AMD Athlon 64           | 1         | 1.18%   |
| AMD A6                  | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 43.53%  |
| 1      | 32        | 37.65%  |
| 4      | 11        | 12.94%  |
| 8      | 2         | 2.35%   |
| 6      | 2         | 2.35%   |
| 24     | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 60%     |
| 2      | 34        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 61        | 71.76%  |
| 32-bit         | 24        | 28.24%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 9         | 10.59%  |
| Unknown    | 9         | 10.59%  |
| 0x106c2    | 8         | 9.41%   |
| 0x6fd      | 5         | 5.88%   |
| 0x106ca    | 5         | 5.88%   |
| 0x6d8      | 4         | 4.71%   |
| 0x6d6      | 4         | 4.71%   |
| 0x206a7    | 4         | 4.71%   |
| 0x306a9    | 3         | 3.53%   |
| 0x30678    | 3         | 3.53%   |
| 0xa0671    | 2         | 2.35%   |
| 0x706a8    | 2         | 2.35%   |
| 0x66a      | 2         | 2.35%   |
| 0x40651    | 2         | 2.35%   |
| 0x30661    | 2         | 2.35%   |
| 0x10661    | 2         | 2.35%   |
| 0xf24      | 1         | 1.18%   |
| 0x906ed    | 1         | 1.18%   |
| 0x906e9    | 1         | 1.18%   |
| 0x806e9    | 1         | 1.18%   |
| 0x706a1    | 1         | 1.18%   |
| 0x6e8      | 1         | 1.18%   |
| 0x695      | 1         | 1.18%   |
| 0x652      | 1         | 1.18%   |
| 0x306c3    | 1         | 1.18%   |
| 0x20655    | 1         | 1.18%   |
| 0x20652    | 1         | 1.18%   |
| 0x10676    | 1         | 1.18%   |
| 0x07030106 | 1         | 1.18%   |
| 0x0700010f | 1         | 1.18%   |
| 0x06006705 | 1         | 1.18%   |
| 0x06006704 | 1         | 1.18%   |
| 0x06001116 | 1         | 1.18%   |
| 0x010000c8 | 1         | 1.18%   |
| 0x01000095 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Bonnell          | 15        | 17.65%  |
| Penryn           | 10        | 11.76%  |
| P6               | 10        | 11.76%  |
| Unknown          | 8         | 9.41%   |
| Core             | 7         | 8.24%   |
| SandyBridge      | 4         | 4.71%   |
| K8 Hammer        | 4         | 4.71%   |
| Silvermont       | 3         | 3.53%   |
| KabyLake         | 3         | 3.53%   |
| IvyBridge        | 3         | 3.53%   |
| Haswell          | 3         | 3.53%   |
| Goldmont plus    | 3         | 3.53%   |
| Westmere         | 2         | 2.35%   |
| K10              | 2         | 2.35%   |
| Excavator        | 2         | 2.35%   |
| Zen+             | 1         | 1.18%   |
| Puma             | 1         | 1.18%   |
| Piledriver       | 1         | 1.18%   |
| NetBurst         | 1         | 1.18%   |
| Jaguar           | 1         | 1.18%   |
| Alderlake Hybrid | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 55.06%  |
| AMD                              | 18        | 20.22%  |
| Nvidia                           | 17        | 19.1%   |
| VIA Technologies                 | 2         | 2.25%   |
| Neomagic                         | 2         | 2.25%   |
| Silicon Integrated Systems [SiS] | 1         | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 7.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 5.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 4.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 5         | 4.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 2.91%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 2.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 1.94%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 1.94%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 1.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 1.94%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.94%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 1.94%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.94%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 1.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.94%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                  | 1         | 0.97%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 0.97%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.97%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 0.97%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.97%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.97%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.97%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.97%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.97%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 0.97%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                            | 1         | 0.97%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 0.97%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 0.97%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 0.97%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 0.97%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                    | 1         | 0.97%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 50.59%  |
| 1 x AMD        | 14        | 16.47%  |
| 1 x Nvidia     | 13        | 15.29%  |
| 2 x AMD        | 4         | 4.71%   |
| Intel + Nvidia | 4         | 4.71%   |
| Other          | 2         | 2.35%   |
| 1 x VIA        | 2         | 2.35%   |
| 1 x Neomagic   | 2         | 2.35%   |
| 1 x SiS        | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 68        | 80%     |
| Unknown     | 11        | 12.94%  |
| Proprietary | 6         | 7.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 35        | 41.18%  |
| Unknown    | 33        | 38.82%  |
| 1.01-2.0   | 12        | 14.12%  |
| 0.51-1.0   | 2         | 2.35%   |
| 5.01-6.0   | 1         | 1.18%   |
| 3.01-4.0   | 1         | 1.18%   |
| 16.01-24.0 | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 19.05%  |
| LG Display              | 10        | 15.87%  |
| Samsung Electronics     | 8         | 12.7%   |
| Acer                    | 4         | 6.35%   |
| LG Philips              | 3         | 4.76%   |
| HannStar                | 3         | 4.76%   |
| Goldstar                | 3         | 4.76%   |
| Chimei Innolux          | 3         | 4.76%   |
| Lenovo                  | 2         | 3.17%   |
| Apple                   | 2         | 3.17%   |
| Vizio                   | 1         | 1.59%   |
| LG Electronics          | 1         | 1.59%   |
| InfoVision              | 1         | 1.59%   |
| HJW                     | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| Dell                    | 1         | 1.59%   |
| CPT                     | 1         | 1.59%   |
| Chi Mei Optoelectronics | 1         | 1.59%   |
| BOE                     | 1         | 1.59%   |
| Arnos Instruments       | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |
| Ancor Communications    | 1         | 1.59%   |
| Unknown                 | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 3.17%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch     | 1         | 1.59%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 1.59%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 1.59%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 1.59%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                         | 1         | 1.59%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 1.59%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.59%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 1         | 1.59%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 1.59%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch            | 1         | 1.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.59%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 1.59%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 1.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 1.59%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                    | 1         | 1.59%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                     | 1         | 1.59%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 1.59%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 20        | 32.26%  |
| 1920x1080 (FHD)   | 15        | 24.19%  |
| 1024x600          | 7         | 11.29%  |
| 1280x800 (WXGA)   | 6         | 9.68%   |
| 1440x900 (WXGA+)  | 4         | 6.45%   |
| 1600x1200         | 2         | 3.23%   |
| 1280x1024 (SXGA)  | 2         | 3.23%   |
| 4480x3600         | 1         | 1.61%   |
| 2560x1080         | 1         | 1.61%   |
| 2288x1287         | 1         | 1.61%   |
| 1920x1200 (WUXGA) | 1         | 1.61%   |
| 1600x900 (HD+)    | 1         | 1.61%   |
| Unknown           | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 27.42%  |
| 21      | 7         | 11.29%  |
| 10      | 6         | 9.68%   |
| 14      | 5         | 8.06%   |
| 17      | 4         | 6.45%   |
| 13      | 4         | 6.45%   |
| 11      | 3         | 4.84%   |
| 24      | 2         | 3.23%   |
| 23      | 2         | 3.23%   |
| 18      | 2         | 3.23%   |
| 12      | 2         | 3.23%   |
| 8       | 2         | 3.23%   |
| 38      | 1         | 1.61%   |
| 34      | 1         | 1.61%   |
| 32      | 1         | 1.61%   |
| 27      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 38.71%  |
| 201-300     | 14        | 22.58%  |
| 401-500     | 9         | 14.52%  |
| 501-600     | 5         | 8.06%   |
| 351-400     | 4         | 6.45%   |
| 701-800     | 2         | 3.23%   |
| 101-200     | 2         | 3.23%   |
| 801-900     | 1         | 1.61%   |
| Unknown     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 70%     |
| 16/10   | 11        | 18.33%  |
| 4/3     | 3         | 5%      |
| 5/4     | 1         | 1.67%   |
| 3/2     | 1         | 1.67%   |
| 21/9    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 25.81%  |
| 201-250        | 9         | 14.52%  |
| 81-90          | 7         | 11.29%  |
| 41-50          | 6         | 9.68%   |
| 51-60          | 3         | 4.84%   |
| 151-200        | 3         | 4.84%   |
| 141-150        | 3         | 4.84%   |
| 71-80          | 2         | 3.23%   |
| 61-70          | 2         | 3.23%   |
| 351-500        | 2         | 3.23%   |
| 1-40           | 2         | 3.23%   |
| 131-140        | 2         | 3.23%   |
| 301-350        | 1         | 1.61%   |
| 121-130        | 1         | 1.61%   |
| 111-120        | 1         | 1.61%   |
| 501-1000       | 1         | 1.61%   |
| Unknown        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 45.9%   |
| 51-100  | 17        | 27.87%  |
| 121-160 | 14        | 22.95%  |
| 1-50    | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 84.88%  |
| 0     | 9         | 10.47%  |
| 2     | 4         | 4.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 37        | 27.82%  |
| Intel                            | 29        | 21.8%   |
| Qualcomm Atheros                 | 26        | 19.55%  |
| Broadcom                         | 16        | 12.03%  |
| Nvidia                           | 5         | 3.76%   |
| Marvell Technology Group         | 4         | 3.01%   |
| Silicon Integrated Systems [SiS] | 2         | 1.5%    |
| Ralink Technology                | 2         | 1.5%    |
| Ralink                           | 2         | 1.5%    |
| Qualcomm Atheros Communications  | 2         | 1.5%    |
| Texas Instruments                | 1         | 0.75%   |
| Samsung Electronics              | 1         | 0.75%   |
| MediaTek                         | 1         | 0.75%   |
| LSI                              | 1         | 0.75%   |
| Hewlett-Packard                  | 1         | 0.75%   |
| Broadcom Limited                 | 1         | 0.75%   |
| Attansic Technology              | 1         | 0.75%   |
| ASIX Electronics                 | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 12        | 7.55%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 11        | 6.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 5.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 2.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 2.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 1.89%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 1.89%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 1.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.26%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.26%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 1.26%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.26%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 2         | 1.26%   |
| Intel Wireless 7260                                                           | 2         | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.26%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.26%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.26%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 1.26%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.63%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.63%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 32.88%  |
| Qualcomm Atheros                | 23        | 31.51%  |
| Broadcom                        | 11        | 15.07%  |
| Realtek Semiconductor           | 7         | 9.59%   |
| Ralink Technology               | 2         | 2.74%   |
| Ralink                          | 2         | 2.74%   |
| Qualcomm Atheros Communications | 2         | 2.74%   |
| Texas Instruments               | 1         | 1.37%   |
| MediaTek                        | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 12.16%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 5.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 4.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 4.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 4.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 2.7%    |
| Ralink RT5370 Wireless Adapter                                                | 2         | 2.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.7%    |
| Intel Wireless 7260                                                           | 2         | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.7%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.7%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.35%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.35%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.35%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.35%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.35%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.35%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.35%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.35%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.35%   |
| Intel Wireless 3165                                                           | 1         | 1.35%   |
| Intel WiFi Link 5100                                                          | 1         | 1.35%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.35%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.35%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.35%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 35        | 44.87%  |
| Intel                            | 15        | 19.23%  |
| Broadcom                         | 8         | 10.26%  |
| Qualcomm Atheros                 | 5         | 6.41%   |
| Nvidia                           | 5         | 6.41%   |
| Marvell Technology Group         | 4         | 5.13%   |
| Silicon Integrated Systems [SiS] | 2         | 2.56%   |
| Samsung Electronics              | 1         | 1.28%   |
| Broadcom Limited                 | 1         | 1.28%   |
| Attansic Technology              | 1         | 1.28%   |
| ASIX Electronics                 | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 15.38%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 14.1%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 8.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 2.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 2.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 2.56%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 2.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.28%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.28%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.28%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.28%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.28%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.28%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.28%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.28%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.28%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.28%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.28%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.28%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.28%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.28%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.28%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.28%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.28%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.28%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 75        | 50%     |
| WiFi     | 68        | 45.33%  |
| Modem    | 7         | 4.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 65.52%  |
| Ethernet | 30        | 34.48%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 65.88%  |
| 1     | 29        | 34.12%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 79.07%  |
| Yes  | 18        | 20.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 26.47%  |
| Broadcom                        | 8         | 23.53%  |
| Cambridge Silicon Radio         | 3         | 8.82%   |
| Realtek Semiconductor           | 2         | 5.88%   |
| Qualcomm Atheros Communications | 2         | 5.88%   |
| Lite-On Technology              | 2         | 5.88%   |
| IMC Networks                    | 2         | 5.88%   |
| Apple                           | 2         | 5.88%   |
| Taiyo Yuden                     | 1         | 2.94%   |
| Ralink Technology               | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 8.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 8.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.88%   |
| Intel Bluetooth Device                              | 2         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.88%   |
| Intel AX201 Bluetooth                               | 2         | 5.88%   |
| IMC Networks Bluetooth Device                       | 2         | 5.88%   |
| Broadcom HP Portable SoftSailing                    | 2         | 5.88%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 5.88%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.94%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.94%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.94%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.94%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 60        | 62.5%   |
| Nvidia                           | 11        | 11.46%  |
| AMD                              | 11        | 11.46%  |
| VIA Technologies                 | 3         | 3.13%   |
| C-Media Electronics              | 3         | 3.13%   |
| Silicon Integrated Systems [SiS] | 2         | 2.08%   |
| ESS Technology                   | 2         | 2.08%   |
| Creative Labs                    | 2         | 2.08%   |
| ULi Electronics                  | 1         | 1.04%   |
| Ensoniq                          | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 15.24%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 5.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 3.81%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.86%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.86%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2         | 1.9%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 1.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.9%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 1.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.9%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.9%    |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.9%    |
| AMD High Definition Audio Controller                                       | 2         | 1.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.9%    |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.95%   |
| VIA Technologies High Definition Audio Controller                          | 1         | 0.95%   |
| ULi Electronics HD Audio Controller                                        | 1         | 0.95%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.95%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.95%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.95%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.95%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.95%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.95%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 34        | 36.17%  |
| SK hynix            | 15        | 15.96%  |
| Samsung Electronics | 13        | 13.83%  |
| Unknown             | 8         | 8.51%   |
| Kingston            | 6         | 6.38%   |
| Micron Technology   | 4         | 4.26%   |
| Crucial             | 2         | 2.13%   |
| Corsair             | 2         | 2.13%   |
| Unknown (ABCD)      | 1         | 1.06%   |
| Unknown (8A02)      | 1         | 1.06%   |
| Unknown (0x0DA2)    | 1         | 1.06%   |
| tigo                | 1         | 1.06%   |
| Smart               | 1         | 1.06%   |
| Ramaxel Technology  | 1         | 1.06%   |
| Patriot             | 1         | 1.06%   |
| Kllisre             | 1         | 1.06%   |
| Avant               | 1         | 1.06%   |
| A-DATA Technology   | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 8         | 7.92%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 2.97%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 2.97%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 1.98%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 1.98%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 2         | 1.98%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 1.98%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 1.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 1.98%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 2         | 1.98%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 1.98%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 2         | 1.98%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 0.99%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 0.99%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 0.99%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 0.99%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 0.99%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 0.99%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.99%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 0.99%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 0.99%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 0.99%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.99%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 0.99%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.99%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 0.99%   |
| Unknown (0x0DA2) RAM SB-DR5U-32G 32GB DIMM DDR5 4800MT/s       | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 34.15%  |
| SDRAM   | 14        | 17.07%  |
| DDR2    | 14        | 17.07%  |
| DDR4    | 10        | 12.2%   |
| DDR     | 8         | 9.76%   |
| DRAM    | 4         | 4.88%   |
| Unknown | 2         | 2.44%   |
| LPDDR4  | 1         | 1.22%   |
| DDR5    | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 70.37%  |
| DIMM         | 23        | 28.4%   |
| Row Of Chips | 1         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 30        | 31.58%  |
| 1024  | 21        | 22.11%  |
| 4096  | 17        | 17.89%  |
| 512   | 9         | 9.47%   |
| 16384 | 6         | 6.32%   |
| 8192  | 5         | 5.26%   |
| 256   | 3         | 3.16%   |
| 64    | 2         | 2.11%   |
| 32768 | 1         | 1.05%   |
| 232   | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 25.58%  |
| 1600    | 16        | 18.6%   |
| 2400    | 5         | 5.81%   |
| 1067    | 5         | 5.81%   |
| 800     | 5         | 5.81%   |
| 667     | 4         | 4.65%   |
| 533     | 4         | 4.65%   |
| 4199    | 3         | 3.49%   |
| 1333    | 3         | 3.49%   |
| 3534    | 2         | 2.33%   |
| 3266    | 2         | 2.33%   |
| 3200    | 2         | 2.33%   |
| 2667    | 2         | 2.33%   |
| 1334    | 2         | 2.33%   |
| 200     | 2         | 2.33%   |
| 4800    | 1         | 1.16%   |
| 2048    | 1         | 1.16%   |
| 1866    | 1         | 1.16%   |
| 975     | 1         | 1.16%   |
| 400     | 1         | 1.16%   |
| 333     | 1         | 1.16%   |
| 266     | 1         | 1.16%   |

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
| Chicony Electronics                    | 9         | 20.93%  |
| Microdia                               | 5         | 11.63%  |
| Suyin                                  | 4         | 9.3%    |
| IMC Networks                           | 4         | 9.3%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.3%    |
| Bison Electronics                      | 4         | 9.3%    |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Silicon Motion                         | 2         | 4.65%   |
| Pixart Imaging                         | 2         | 4.65%   |
| Apple                                  | 2         | 4.65%   |
| Syntek                                 | 1         | 2.33%   |
| Realtek Semiconductor                  | 1         | 2.33%   |
| Lite-On Technology                     | 1         | 2.33%   |
| Lenovo                                 | 1         | 2.33%   |
| Importek                               | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                           | 3         | 6.98%   |
| Suyin USB 2.0 Camera                                    | 2         | 4.65%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 4.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.65%   |
| Bison BisonCam, NB Pro                                  | 2         | 4.65%   |
| Syntek Integrated Camera                                | 1         | 2.33%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.33%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.33%   |
| Sunplus HD WebCam                                       | 1         | 2.33%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.33%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.33%   |
| Realtek HD WebCam                                       | 1         | 2.33%   |
| Microdia Integrated Webcam                              | 1         | 2.33%   |
| Microdia Integrated Camera                              | 1         | 2.33%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 2.33%   |
| Lenovo Integrated Webcam                                | 1         | 2.33%   |
| Importek FJ Camera                                      | 1         | 2.33%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.33%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.33%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.33%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.33%   |
| Chicony HP Webcam                                       | 1         | 2.33%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.33%   |
| Chicony HD WebCam                                       | 1         | 2.33%   |
| Chicony EasyCamera                                      | 1         | 2.33%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.33%   |
| Chicony CNF7050                                         | 1         | 2.33%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.33%   |
| Bison Lenovo EasyCamera                                 | 1         | 2.33%   |
| Bison Acer Crystal Eye Webcam                           | 1         | 2.33%   |
| Apple FaceTime Camera                                   | 1         | 2.33%   |
| Apple Built-in iSight                                   | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 5         | 71.43%  |
| Validity Sensors | 1         | 14.29%  |
| Upek             | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 42.86%  |
| AuthenTec AES1600                                      | 2         | 28.57%  |
| Validity Sensors VFS491                                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |

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
| 0     | 61        | 71.76%  |
| 1     | 19        | 22.35%  |
| 3     | 3         | 3.53%   |
| 2     | 2         | 2.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 17        | 54.84%  |
| Fingerprint reader       | 7         | 22.58%  |
| Communication controller | 3         | 9.68%   |
| Sound                    | 1         | 3.23%   |
| Net/ethernet             | 1         | 3.23%   |
| Modem                    | 1         | 3.23%   |
| Chipcard                 | 1         | 3.23%   |


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

Total: 115

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pegatron      | Eureka3                     | Desktop     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| ASRock        | G31M-S                      | Desktop     | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| HP            | G5000 (RY492EA#ACB)         | Notebook    | [0f0a19a64c](https://linux-hardware.org/?probe=0f0a19a64c) | Sep 14, 2023 |
| Intel         | DG41TY AAE47335-202         | Desktop     | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel         | DG41TY AAE47335-202         | Desktop     | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 34        | 37.78%  |
| antiX 22       | 25        | 27.78%  |
| antiX 19.2     | 8         | 8.89%   |
| antiX 19.3     | 5         | 5.56%   |
| antiX 17.4.1   | 4         | 4.44%   |
| antiX 21-runit | 3         | 3.33%   |
| antiX 23       | 2         | 2.22%   |
| antiX 19.4     | 2         | 2.22%   |
| antiX 19.1     | 2         | 2.22%   |
| antiX 19.5     | 1         | 1.11%   |
| antiX 17.2.1   | 1         | 1.11%   |
| antiX 17.1     | 1         | 1.11%   |
| antiX 17       | 1         | 1.11%   |
| antiX 15       | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 89        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 15        | 16.67%  |
| 5.10.142-antix.2-amd64-smp   | 12        | 13.33%  |
| 4.9.0-279-antix.1-amd64-smp  | 10        | 11.11%  |
| 4.9.0-326-antix.1-amd64-smp  | 9         | 10%     |
| 5.10.57-antix.1-amd64-smp    | 8         | 8.89%   |
| 4.9.235-antix.1-amd64-smp    | 4         | 4.44%   |
| 4.9.160-antix.2-486-smp      | 4         | 4.44%   |
| 4.9.0-326-antix.1-486-smp    | 4         | 4.44%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 3.33%   |
| 4.9.212-antix.1-486-smp      | 3         | 3.33%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 2.22%   |
| 4.9.200-antix.1-486-smp      | 2         | 2.22%   |
| 6.2.9-1-liquorix-amd64       | 1         | 1.11%   |
| 6.1.0-0.deb11.9-rt-amd64     | 1         | 1.11%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.11%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.11%   |
| 5.10.188-antix.1-amd64-smp   | 1         | 1.11%   |
| 5.10.188-antix.1-486-smp     | 1         | 1.11%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.11%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.11%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.11%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.11%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.11%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.11%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.11%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 39        | 43.82%  |
| 5.10.142 | 12        | 13.48%  |
| 5.10.57  | 8         | 8.99%   |
| 4.9.212  | 6         | 6.74%   |
| 4.9.160  | 5         | 5.62%   |
| 4.9.235  | 4         | 4.49%   |
| 5.10.88  | 2         | 2.25%   |
| 5.10.188 | 2         | 2.25%   |
| 4.9.200  | 2         | 2.25%   |
| 6.2.9    | 1         | 1.12%   |
| 6.1.0    | 1         | 1.12%   |
| 5.14.0   | 1         | 1.12%   |
| 5.10.27  | 1         | 1.12%   |
| 4.9.87   | 1         | 1.12%   |
| 4.19.202 | 1         | 1.12%   |
| 4.19.100 | 1         | 1.12%   |
| 4.19.0   | 1         | 1.12%   |
| 4.10.5   | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 57        | 64.04%  |
| 5.10    | 25        | 28.09%  |
| 4.19    | 3         | 3.37%   |
| 6.2     | 1         | 1.12%   |
| 6.1     | 1         | 1.12%   |
| 5.14    | 1         | 1.12%   |
| 4.10    | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 62.92%  |
| i686   | 32        | 35.96%  |
| i586   | 1         | 1.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| icewm        | 40        | 44.94%  |
| Unknown      | 38        | 42.7%   |
| XFCE         | 5         | 5.62%   |
| fluxbox      | 2         | 2.25%   |
| jwm          | 1         | 1.12%   |
| herbstluftwm | 1         | 1.12%   |
| GNOME        | 1         | 1.12%   |
| Cinnamon     | 1         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 87        | 97.75%  |
| Tty  | 2         | 2.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 53.93%  |
| SLiM    | 22        | 24.72%  |
| SLIMSKI | 10        | 11.24%  |
| LightDM | 7         | 7.87%   |
| XDM     | 1         | 1.12%   |
| SDDM    | 1         | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 33        | 37.08%  |
| ru_RU   | 9         | 10.11%  |
| pt_BR   | 5         | 5.62%   |
| de_DE   | 5         | 5.62%   |
| pl_PL   | 3         | 3.37%   |
| ja_JP   | 3         | 3.37%   |
| it_IT   | 3         | 3.37%   |
| es_ES   | 3         | 3.37%   |
| en_GB   | 3         | 3.37%   |
| Unknown | 3         | 3.37%   |
| sk_SK   | 2         | 2.25%   |
| nl_NL   | 2         | 2.25%   |
| es_AR   | 2         | 2.25%   |
| en_AU   | 2         | 2.25%   |
| zh_HK   | 1         | 1.12%   |
| uk_UA   | 1         | 1.12%   |
| tr_TR   | 1         | 1.12%   |
| hu_HU   | 1         | 1.12%   |
| fr_FR   | 1         | 1.12%   |
| fr_BE   | 1         | 1.12%   |
| es_VE   | 1         | 1.12%   |
| es_PE   | 1         | 1.12%   |
| es_MX   | 1         | 1.12%   |
| en_NZ   | 1         | 1.12%   |
| de_AT   | 1         | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 71        | 79.78%  |
| EFI  | 18        | 20.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 77        | 86.52%  |
| Overlay  | 10        | 11.24%  |
| Xfs      | 1         | 1.12%   |
| Reiserfs | 1         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 66        | 74.16%  |
| GPT     | 21        | 23.6%   |
| Unknown | 2         | 2.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 77.78%  |
| Yes       | 20        | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 64.04%  |
| Yes       | 32        | 35.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 13.48%  |
| ASUSTek Computer    | 11        | 12.36%  |
| Lenovo              | 9         | 10.11%  |
| Acer                | 8         | 8.99%   |
| MSI                 | 5         | 5.62%   |
| Intel               | 5         | 5.62%   |
| IBM                 | 5         | 5.62%   |
| Dell                | 5         | 5.62%   |
| Toshiba             | 3         | 3.37%   |
| Gigabyte Technology | 3         | 3.37%   |
| Fujitsu             | 3         | 3.37%   |
| Unknown             | 3         | 3.37%   |
| Pegatron            | 2         | 2.25%   |
| KOHJINSHA           | 2         | 2.25%   |
| Apple               | 2         | 2.25%   |
| VXL                 | 1         | 1.12%   |
| Samsung Electronics | 1         | 1.12%   |
| Radiant Systems     | 1         | 1.12%   |
| Packard Bell        | 1         | 1.12%   |
| Medion              | 1         | 1.12%   |
| Google              | 1         | 1.12%   |
| Compaq              | 1         | 1.12%   |
| Biostar             | 1         | 1.12%   |
| AZW                 | 1         | 1.12%   |
| ASRock              | 1         | 1.12%   |
| AMI                 | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 4.49%   |
| MSI US Desktop                     | 2         | 2.25%   |
| IBM 260921H                        | 2         | 2.25%   |
| HP Mini 110-3700                   | 2         | 2.25%   |
| Fujitsu FMVNU6G1C                  | 2         | 2.25%   |
| VXL TC7520d                        | 1         | 1.12%   |
| Toshiba Satellite T110             | 1         | 1.12%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.12%   |
| Toshiba Satellite 1905             | 1         | 1.12%   |
| Samsung SQ1S                       | 1         | 1.12%   |
| Radiant Systems P845               | 1         | 1.12%   |
| Pegatron VC902AA-ABF p6136fr       | 1         | 1.12%   |
| Pegatron AU930AA-ACJ p6270in       | 1         | 1.12%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.12%   |
| MSI MS-7C56                        | 1         | 1.12%   |
| MSI MS-7B17                        | 1         | 1.12%   |
| MSI GE62 7RE                       | 1         | 1.12%   |
| Medion WIM2170                     | 1         | 1.12%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.12%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.12%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.12%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.12%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.12%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.12%   |
| Lenovo G550 2958                   | 1         | 1.12%   |
| Lenovo 3000 V100 076346G           | 1         | 1.12%   |
| KOHJINSHA SX series                | 1         | 1.12%   |
| KOHJINSHA SC series                | 1         | 1.12%   |
| Intel powered classmate PC         | 1         | 1.12%   |
| Intel H61                          | 1         | 1.12%   |
| Intel DG41TY AAE47335-202          | 1         | 1.12%   |
| Intel D525MW AAE93082-401          | 1         | 1.12%   |
| Intel D425KT AAE93083-400          | 1         | 1.12%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.12%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.12%   |
| IBM ThinkPad T40 237342G           | 1         | 1.12%   |
| HP t5740                           | 1         | 1.12%   |
| HP Presario CQ56                   | 1         | 1.12%   |
| HP Pavilion dv2700                 | 1         | 1.12%   |
| HP Mini 5101                       | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 7.87%   |
| Unknown               | 4         | 4.49%   |
| Toshiba Satellite     | 3         | 3.37%   |
| Lenovo IdeaPad        | 3         | 3.37%   |
| IBM ThinkPad          | 3         | 3.37%   |
| HP Mini               | 3         | 3.37%   |
| Dell Latitude         | 3         | 3.37%   |
| MSI US                | 2         | 2.25%   |
| Lenovo ThinkPad       | 2         | 2.25%   |
| IBM 260921H           | 2         | 2.25%   |
| HP EliteBook          | 2         | 2.25%   |
| Fujitsu FMVNU6G1C     | 2         | 2.25%   |
| ASUS VivoBook         | 2         | 2.25%   |
| VXL TC7520d           | 1         | 1.12%   |
| Samsung SQ1S          | 1         | 1.12%   |
| Radiant Systems P845  | 1         | 1.12%   |
| Pegatron VC902AA-ABF  | 1         | 1.12%   |
| Pegatron AU930AA-ACJ  | 1         | 1.12%   |
| Packard Bell EasyNote | 1         | 1.12%   |
| MSI MS-7C56           | 1         | 1.12%   |
| MSI MS-7B17           | 1         | 1.12%   |
| MSI GE62              | 1         | 1.12%   |
| Medion WIM2170        | 1         | 1.12%   |
| Lenovo ThinkCentre    | 1         | 1.12%   |
| Lenovo G550           | 1         | 1.12%   |
| Lenovo 3000           | 1         | 1.12%   |
| KOHJINSHA SX          | 1         | 1.12%   |
| KOHJINSHA SC          | 1         | 1.12%   |
| Intel powered         | 1         | 1.12%   |
| Intel H61             | 1         | 1.12%   |
| Intel DG41TY          | 1         | 1.12%   |
| Intel D525MW          | 1         | 1.12%   |
| Intel D425KT          | 1         | 1.12%   |
| HP t5740              | 1         | 1.12%   |
| HP Presario           | 1         | 1.12%   |
| HP Pavilion           | 1         | 1.12%   |
| HP G5000              | 1         | 1.12%   |
| HP All-in-One         | 1         | 1.12%   |
| HP 620                | 1         | 1.12%   |
| HP 255                | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 14        | 15.73%  |
| 2007    | 12        | 13.48%  |
| 2008    | 11        | 12.36%  |
| 2012    | 6         | 6.74%   |
| 2010    | 6         | 6.74%   |
| 2014    | 4         | 4.49%   |
| 2013    | 4         | 4.49%   |
| 2011    | 4         | 4.49%   |
| 2021    | 3         | 3.37%   |
| 2020    | 3         | 3.37%   |
| 2018    | 3         | 3.37%   |
| 2017    | 3         | 3.37%   |
| 2005    | 3         | 3.37%   |
| 2003    | 3         | 3.37%   |
| 2022    | 2         | 2.25%   |
| 2004    | 2         | 2.25%   |
| 1999    | 2         | 2.25%   |
| 2019    | 1         | 1.12%   |
| 2016    | 1         | 1.12%   |
| 2006    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 61        | 68.54%  |
| Desktop    | 23        | 25.84%  |
| Mini pc    | 4         | 4.49%   |
| All in one | 1         | 1.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 89        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 98.88%  |
| Yes  | 1         | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 25        | 28.09%  |
| 1.01-2.0    | 17        | 19.1%   |
| 0.51-1.0    | 12        | 13.48%  |
| 2.01-3.0    | 10        | 11.24%  |
| 4.01-8.0    | 6         | 6.74%   |
| 0.01-0.5    | 6         | 6.74%   |
| 32.01-64.0  | 5         | 5.62%   |
| 8.01-16.0   | 4         | 4.49%   |
| 64.01-256.0 | 2         | 2.25%   |
| 16.01-24.0  | 2         | 2.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 32        | 35.56%  |
| 0.01-0.5   | 31        | 34.44%  |
| 1.01-2.0   | 18        | 20%     |
| 2.01-3.0   | 6         | 6.67%   |
| 4.01-8.0   | 2         | 2.22%   |
| 32.01-64.0 | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 66        | 73.33%  |
| 2      | 13        | 14.44%  |
| 3      | 4         | 4.44%   |
| 4      | 3         | 3.33%   |
| 0      | 3         | 3.33%   |
| 5      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 56.18%  |
| Yes       | 39        | 43.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 87.64%  |
| No        | 11        | 12.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 78.65%  |
| No        | 19        | 21.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 60.67%  |
| Yes       | 35        | 39.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 15.73%  |
| Russia      | 11        | 12.36%  |
| Hong Kong   | 10        | 11.24%  |
| Germany     | 7         | 7.87%   |
| Brazil      | 5         | 5.62%   |
| Poland      | 4         | 4.49%   |
| Japan       | 4         | 4.49%   |
| Netherlands | 3         | 3.37%   |
| Italy       | 3         | 3.37%   |
| UK          | 2         | 2.25%   |
| Spain       | 2         | 2.25%   |
| Slovakia    | 2         | 2.25%   |
| Hungary     | 2         | 2.25%   |
| France      | 2         | 2.25%   |
| Australia   | 2         | 2.25%   |
| Argentina   | 2         | 2.25%   |
| Uruguay     | 1         | 1.12%   |
| Ukraine     | 1         | 1.12%   |
| Peru        | 1         | 1.12%   |
| New Zealand | 1         | 1.12%   |
| Mexico      | 1         | 1.12%   |
| Kenya       | 1         | 1.12%   |
| Kazakhstan  | 1         | 1.12%   |
| India       | 1         | 1.12%   |
| Greece      | 1         | 1.12%   |
| Denmark     | 1         | 1.12%   |
| Chile       | 1         | 1.12%   |
| Bulgaria    | 1         | 1.12%   |
| Belgium     | 1         | 1.12%   |
| Austria     | 1         | 1.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 7.69%   |
| Sydney                    | 2         | 2.2%    |
| St Petersburg             | 2         | 2.2%    |
| Moscow                    | 2         | 2.2%    |
| Central                   | 2         | 2.2%    |
| Bratislava                | 2         | 2.2%    |
| Zagnansk                  | 1         | 1.1%    |
| Yuzhno-Sakhalinsk         | 1         | 1.1%    |
| Yokohama                  | 1         | 1.1%    |
| Ybbs an der Donau         | 1         | 1.1%    |
| Whitney                   | 1         | 1.1%    |
| Warsaw                    | 1         | 1.1%    |
| Violes                    | 1         | 1.1%    |
| Torricella Sicura         | 1         | 1.1%    |
| Toms River                | 1         | 1.1%    |
| Tokyo                     | 1         | 1.1%    |
| Sofia                     | 1         | 1.1%    |
| Sheung Shui               | 1         | 1.1%    |
| Seattle                   | 1         | 1.1%    |
| Schloss Holte-Stukenbrock | 1         | 1.1%    |
| Santiago                  | 1         | 1.1%    |
| Salto                     | 1         | 1.1%    |
| Rotterdam                 | 1         | 1.1%    |
| Romilly-sur-Seine         | 1         | 1.1%    |
| Reutlingen                | 1         | 1.1%    |
| Purmerend                 | 1         | 1.1%    |
| Pritzwalk                 | 1         | 1.1%    |
| Portland                  | 1         | 1.1%    |
| Pomaz                     | 1         | 1.1%    |
| Padova                    | 1         | 1.1%    |
| Otwock                    | 1         | 1.1%    |
| Nova Londrina             | 1         | 1.1%    |
| Norden                    | 1         | 1.1%    |
| Neyagawa                  | 1         | 1.1%    |
| Nairobi                   | 1         | 1.1%    |
| Montevideo                | 1         | 1.1%    |
| Mittegrossefehn           | 1         | 1.1%    |
| Milan                     | 1         | 1.1%    |
| Miami                     | 1         | 1.1%    |
| Mechanicsburg             | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 20        | 22     | 18.35%  |
| Seagate                   | 17        | 17     | 15.6%   |
| Hitachi                   | 13        | 14     | 11.93%  |
| Samsung Electronics       | 12        | 14     | 11.01%  |
| Toshiba                   | 11        | 12     | 10.09%  |
| Unknown                   | 4         | 4      | 3.67%   |
| Kingston                  | 4         | 5      | 3.67%   |
| BHT                       | 3         | 5      | 2.75%   |
| Micron/Crucial Technology | 2         | 2      | 1.83%   |
| Maxtor                    | 2         | 2      | 1.83%   |
| Intel                     | 2         | 2      | 1.83%   |
| HGST                      | 2         | 2      | 1.83%   |
| Unknown                   | 2         | 2      | 1.83%   |
| Zheino                    | 1         | 1      | 0.92%   |
| Unknown (CF)              | 1         | 1      | 0.92%   |
| Transcend                 | 1         | 1      | 0.92%   |
| SanDisk                   | 1         | 1      | 0.92%   |
| RECADATA                  | 1         | 1      | 0.92%   |
| PNY                       | 1         | 1      | 0.92%   |
| OCZ                       | 1         | 1      | 0.92%   |
| IBM/Hitachi               | 1         | 1      | 0.92%   |
| Hewlett-Packard           | 1         | 1      | 0.92%   |
| Fujitsu                   | 1         | 1      | 0.92%   |
| Crucial                   | 1         | 1      | 0.92%   |
| China                     | 1         | 1      | 0.92%   |
| BIWIN                     | 1         | 1      | 0.92%   |
| ASUS-PHISON               | 1         | 1      | 0.92%   |
| Apacer                    | 1         | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD800AAJS-75M0A0 80GB               | 2         | 1.79%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 1.79%   |
| WDC WD10SPZX-80Z10T2 1TB                | 2         | 1.79%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.79%   |
| Toshiba MQ01ABD050V -63 500GB           | 2         | 1.79%   |
| Seagate ST980811AS 80GB                 | 2         | 1.79%   |
| Samsung SSD 850 EVO 120GB               | 2         | 1.79%   |
| Samsung SSD 750 EVO 120GB               | 2         | 1.79%   |
| Maxtor Z1 SSD 240GB                     | 2         | 1.79%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.79%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 1.79%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 1.79%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 1.79%   |
| BHT WR202F0032G 670270F5 32GB SSD       | 2         | 1.79%   |
| Unknown                                 | 2         | 1.79%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 0.89%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 0.89%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 0.89%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.89%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.89%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 0.89%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 1         | 0.89%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 0.89%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.89%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.89%   |
| WDC WD205BA 21GB                        | 1         | 0.89%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.89%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 0.89%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.89%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 0.89%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 0.89%   |
| WDC WD10EADS-65M2B0 1TB                 | 1         | 0.89%   |
| Unknown SR64G  64GB                     | 1         | 0.89%   |
| Unknown SD/MMC/MS PRO 128GB             | 1         | 0.89%   |
| Unknown HAG2e  16GB                     | 1         | 0.89%   |
| Unknown 2GB ATA Flash Disk              | 1         | 0.89%   |
| Unknown (CF) Card 16GB SSD              | 1         | 0.89%   |
| Transcend SSD 2GB                       | 1         | 0.89%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 0.89%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 22     | 28.57%  |
| Seagate             | 17        | 17     | 24.29%  |
| Hitachi             | 13        | 14     | 18.57%  |
| Toshiba             | 9         | 10     | 12.86%  |
| Samsung Electronics | 5         | 6      | 7.14%   |
| Unknown             | 2         | 2      | 2.86%   |
| HGST                | 2         | 2      | 2.86%   |
| IBM/Hitachi         | 1         | 1      | 1.43%   |
| Fujitsu             | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 75     | 63.64%  |
| SSD  | 30        | 35     | 30.3%   |
| NVMe | 4         | 6      | 4.04%   |
| MMC  | 2         | 2      | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 109    | 92.31%  |
| NVMe | 4         | 6      | 4.4%    |
| MMC  | 2         | 2      | 2.2%    |
| SAS  | 1         | 1      | 1.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 95     | 84.95%  |
| 0.51-1.0   | 12        | 12     | 12.9%   |
| 1.01-2.0   | 1         | 1      | 1.08%   |
| 4.01-10.0  | 1         | 2      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 30.77%  |
| 1-20           | 21        | 23.08%  |
| 51-100         | 12        | 13.19%  |
| 21-50          | 11        | 12.09%  |
| 251-500        | 10        | 10.99%  |
| 501-1000       | 6         | 6.59%   |
| More than 3000 | 1         | 1.1%    |
| 1001-2000      | 1         | 1.1%    |
| Unknown        | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 69        | 77.53%  |
| 21-50          | 7         | 7.87%   |
| 101-250        | 6         | 6.74%   |
| 51-100         | 4         | 4.49%   |
| More than 3000 | 1         | 1.12%   |
| 501-1000       | 1         | 1.12%   |
| Unknown        | 1         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2         | 2      | 5.13%   |
| Seagate ST980811AS 80GB                     | 2         | 2      | 5.13%   |
| Hitachi HTS542525K9SA00 250GB               | 2         | 2      | 5.13%   |
| WDC WD800JB-00ETA0 80GB                     | 1         | 1      | 2.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 2.56%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.56%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 1      | 2.56%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 1         | 1      | 2.56%   |
| WDC WD2500BEVT-22ZCT0 250GB                 | 1         | 1      | 2.56%   |
| WDC WD205BA 21GB                            | 1         | 1      | 2.56%   |
| WDC WD10EADS-65M2B0 1TB                     | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.56%   |
| Toshiba MK2555GSX 250GB                     | 1         | 1      | 2.56%   |
| Seagate ST980812AS 80GB                     | 1         | 1      | 2.56%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.56%   |
| Seagate ST9160314AS 160GB                   | 1         | 1      | 2.56%   |
| Seagate ST9160310AS 160GB                   | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.56%   |
| Seagate ST3500312CS 500GB                   | 1         | 1      | 2.56%   |
| Seagate ST3320620AS 320GB                   | 1         | 1      | 2.56%   |
| Seagate ST3320413CS 320GB                   | 1         | 1      | 2.56%   |
| Seagate ST320LT007-9ZV142 320GB             | 1         | 1      | 2.56%   |
| SanDisk sandisk120 120GB SSD                | 1         | 1      | 2.56%   |
| Samsung Electronics HM161GI 160GB           | 1         | 1      | 2.56%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1         | 1      | 2.56%   |
| Hitachi HTS725050A7E630 500GB               | 1         | 1      | 2.56%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 2.56%   |
| Hitachi HTS721060G9AT00 64GB                | 1         | 1      | 2.56%   |
| Hitachi HTS548040M9AT00 40GB                | 1         | 1      | 2.56%   |
| Hitachi HTS543225A7A384 250GB               | 1         | 1      | 2.56%   |
| Hitachi HTS541612J9SA00 120GB               | 1         | 1      | 2.56%   |
| Hitachi HTC426040G8CE00 40GB                | 1         | 1      | 2.56%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.56%   |
| China M.2 SSD 128GB                         | 1         | 1      | 2.56%   |
| BIWIN SSD 32GB                              | 1         | 1      | 2.56%   |
| Apacer 32GB SATA Flash Drive SSD            | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 11        | 11     | 28.21%  |
| WDC                       | 10        | 10     | 25.64%  |
| Hitachi                   | 9         | 9      | 23.08%  |
| Toshiba                   | 2         | 2      | 5.13%   |
| SanDisk                   | 1         | 1      | 2.56%   |
| Samsung Electronics       | 1         | 1      | 2.56%   |
| Micron/Crucial Technology | 1         | 1      | 2.56%   |
| HGST                      | 1         | 1      | 2.56%   |
| China                     | 1         | 1      | 2.56%   |
| BIWIN                     | 1         | 1      | 2.56%   |
| Apacer                    | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 32.35%  |
| WDC                 | 10        | 10     | 29.41%  |
| Hitachi             | 9         | 9      | 26.47%  |
| Toshiba             | 2         | 2      | 5.88%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 34     | 87.18%  |
| SSD  | 4         | 4      | 10.26%  |
| NVMe | 1         | 1      | 2.56%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 48        | 70     | 50.53%  |
| Malfunc  | 39        | 39     | 41.05%  |
| Detected | 8         | 9      | 8.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 69.7%   |
| AMD                              | 8         | 8.08%   |
| Nvidia                           | 5         | 5.05%   |
| ASMedia Technology               | 4         | 4.04%   |
| VIA Technologies                 | 3         | 3.03%   |
| Silicon Integrated Systems [SiS] | 2         | 2.02%   |
| Samsung Electronics              | 2         | 2.02%   |
| Micron/Crucial Technology        | 2         | 2.02%   |
| ULi Electronics                  | 1         | 1.01%   |
| Silicon Image                    | 1         | 1.01%   |
| LSI Logic / Symbios Logic        | 1         | 1.01%   |
| JMicron Technology               | 1         | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                     | 11        | 9.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 6         | 4.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 6         | 4.92%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 4.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 5         | 4.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 4         | 3.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 4         | 3.28%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                        | 4         | 3.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 2.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 3         | 2.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 3         | 2.46%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 3         | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3         | 2.46%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                   | 2         | 1.64%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2         | 1.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                    | 2         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.64%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1         | 0.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 0.82%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller               | 1         | 0.82%   |
| ULi ULi M5288 SATA                                                            | 1         | 0.82%   |
| ULi M5229 IDE                                                                 | 1         | 0.82%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller              | 1         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.82%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 0.82%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1         | 0.82%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 0.82%   |
| Nvidia MCP67 IDE Controller                                                   | 1         | 0.82%   |
| Nvidia MCP67 AHCI Controller                                                  | 1         | 0.82%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 0.82%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1         | 0.82%   |
| Nvidia CK804 Serial ATA Controller                                            | 1         | 0.82%   |
| Nvidia CK804 IDE                                                              | 1         | 0.82%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 46.6%   |
| IDE  | 46        | 44.66%  |
| RAID | 4         | 3.88%   |
| NVMe | 4         | 3.88%   |
| SAS  | 1         | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 74        | 83.15%  |
| AMD          | 12        | 13.48%  |
| CentaurHauls | 2         | 2.25%   |
| GenuineTMx86 | 1         | 1.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 4.49%   |
| Intel Pentium M processor 1.60GHz           | 2         | 2.25%   |
| Intel Pentium M processor 1.00GHz           | 2         | 2.25%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2         | 2.25%   |
| Intel Genuine processor 800MHz              | 2         | 2.25%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 2.25%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 2.25%   |
| Intel Celeron (Mendocino)                   | 2         | 2.25%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.25%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 2.25%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 2.25%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.25%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 2.25%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.12%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.12%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.12%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.12%   |
| Intel Pentium II (Deschutes)                | 1         | 1.12%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.12%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.12%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.12%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.12%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.12%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.12%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.12%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.12%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.12%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.12%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.12%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.12%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.12%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.12%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 15        | 16.85%  |
| Intel Core 2 Duo        | 9         | 10.11%  |
| Intel Celeron           | 9         | 10.11%  |
| Intel Pentium M         | 6         | 6.74%   |
| Intel Core i7           | 6         | 6.74%   |
| Other                   | 5         | 5.62%   |
| Intel Genuine           | 5         | 5.62%   |
| Intel Core i5           | 5         | 5.62%   |
| Intel Pentium Dual-Core | 3         | 3.37%   |
| Intel Core i3           | 3         | 3.37%   |
| Intel Pentium Dual      | 2         | 2.25%   |
| AMD E2                  | 2         | 2.25%   |
| AMD Athlon 64 X2        | 2         | 2.25%   |
| Intel Xeon              | 1         | 1.12%   |
| Intel Pentium Silver    | 1         | 1.12%   |
| Intel Pentium 4         | 1         | 1.12%   |
| Intel Pentium           | 1         | 1.12%   |
| Intel Core i9           | 1         | 1.12%   |
| Intel Core 2 Quad       | 1         | 1.12%   |
| Intel Celeron M         | 1         | 1.12%   |
| Intel Celeron Dual-Core | 1         | 1.12%   |
| CentaurHauls VIA Nano   | 1         | 1.12%   |
| CentaurHauls VIA Eden   | 1         | 1.12%   |
| AMD Sempron             | 1         | 1.12%   |
| AMD Ryzen 7             | 1         | 1.12%   |
| AMD Phenom              | 1         | 1.12%   |
| AMD E1                  | 1         | 1.12%   |
| AMD Athlon II           | 1         | 1.12%   |
| AMD Athlon 64           | 1         | 1.12%   |
| AMD A6                  | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 46.07%  |
| 1      | 32        | 35.96%  |
| 4      | 11        | 12.36%  |
| 8      | 2         | 2.25%   |
| 6      | 2         | 2.25%   |
| 24     | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 61.8%   |
| 2      | 34        | 38.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 71.91%  |
| 32-bit         | 25        | 28.09%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 12        | 13.48%  |
| Unknown    | 9         | 10.11%  |
| 0x106c2    | 8         | 8.99%   |
| 0x6fd      | 5         | 5.62%   |
| 0x106ca    | 5         | 5.62%   |
| 0x6d8      | 4         | 4.49%   |
| 0x6d6      | 4         | 4.49%   |
| 0x206a7    | 4         | 4.49%   |
| 0x306a9    | 3         | 3.37%   |
| 0x30678    | 3         | 3.37%   |
| 0xa0671    | 2         | 2.25%   |
| 0x706a8    | 2         | 2.25%   |
| 0x6e8      | 2         | 2.25%   |
| 0x66a      | 2         | 2.25%   |
| 0x40651    | 2         | 2.25%   |
| 0x30661    | 2         | 2.25%   |
| 0x10661    | 2         | 2.25%   |
| 0xf24      | 1         | 1.12%   |
| 0x906ed    | 1         | 1.12%   |
| 0x906e9    | 1         | 1.12%   |
| 0x806e9    | 1         | 1.12%   |
| 0x706a1    | 1         | 1.12%   |
| 0x695      | 1         | 1.12%   |
| 0x652      | 1         | 1.12%   |
| 0x306c3    | 1         | 1.12%   |
| 0x20655    | 1         | 1.12%   |
| 0x20652    | 1         | 1.12%   |
| 0x10676    | 1         | 1.12%   |
| 0x07030106 | 1         | 1.12%   |
| 0x0700010f | 1         | 1.12%   |
| 0x06006705 | 1         | 1.12%   |
| 0x06006704 | 1         | 1.12%   |
| 0x06001116 | 1         | 1.12%   |
| 0x010000c8 | 1         | 1.12%   |
| 0x01000095 | 1         | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Bonnell          | 15        | 16.85%  |
| Penryn           | 13        | 14.61%  |
| P6               | 11        | 12.36%  |
| Unknown          | 8         | 8.99%   |
| Core             | 7         | 7.87%   |
| SandyBridge      | 4         | 4.49%   |
| K8 Hammer        | 4         | 4.49%   |
| Silvermont       | 3         | 3.37%   |
| KabyLake         | 3         | 3.37%   |
| IvyBridge        | 3         | 3.37%   |
| Haswell          | 3         | 3.37%   |
| Goldmont plus    | 3         | 3.37%   |
| Westmere         | 2         | 2.25%   |
| K10              | 2         | 2.25%   |
| Excavator        | 2         | 2.25%   |
| Zen+             | 1         | 1.12%   |
| Puma             | 1         | 1.12%   |
| Piledriver       | 1         | 1.12%   |
| NetBurst         | 1         | 1.12%   |
| Jaguar           | 1         | 1.12%   |
| Alderlake Hybrid | 1         | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 55.91%  |
| Nvidia                           | 18        | 19.35%  |
| AMD                              | 18        | 19.35%  |
| VIA Technologies                 | 2         | 2.15%   |
| Neomagic                         | 2         | 2.15%   |
| Silicon Integrated Systems [SiS] | 1         | 1.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 9         | 8.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 5.56%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 4.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 5         | 4.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 2.78%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 1.85%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 1.85%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.85%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 1.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.85%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                  | 1         | 0.93%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.93%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 0.93%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.93%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 0.93%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1         | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.93%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.93%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.93%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 0.93%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                            | 1         | 0.93%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 0.93%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 0.93%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 0.93%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 0.93%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                    | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 50.56%  |
| 1 x Nvidia     | 14        | 15.73%  |
| 1 x AMD        | 14        | 15.73%  |
| 2 x AMD        | 4         | 4.49%   |
| Intel + Nvidia | 4         | 4.49%   |
| Other          | 2         | 2.25%   |
| 1 x VIA        | 2         | 2.25%   |
| 1 x Neomagic   | 2         | 2.25%   |
| 2 x Intel      | 1         | 1.12%   |
| 1 x SiS        | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 72        | 80.9%   |
| Unknown     | 11        | 12.36%  |
| Proprietary | 6         | 6.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 40.45%  |
| 0.01-0.5   | 35        | 39.33%  |
| 1.01-2.0   | 12        | 13.48%  |
| 0.51-1.0   | 3         | 3.37%   |
| 5.01-6.0   | 1         | 1.12%   |
| 3.01-4.0   | 1         | 1.12%   |
| 16.01-24.0 | 1         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 18.46%  |
| LG Display              | 10        | 15.38%  |
| Samsung Electronics     | 8         | 12.31%  |
| LG Philips              | 4         | 6.15%   |
| Goldstar                | 4         | 6.15%   |
| Acer                    | 4         | 6.15%   |
| HannStar                | 3         | 4.62%   |
| Chimei Innolux          | 3         | 4.62%   |
| Lenovo                  | 2         | 3.08%   |
| Apple                   | 2         | 3.08%   |
| Vizio                   | 1         | 1.54%   |
| LG Electronics          | 1         | 1.54%   |
| InfoVision              | 1         | 1.54%   |
| HJW                     | 1         | 1.54%   |
| Hewlett-Packard         | 1         | 1.54%   |
| Dell                    | 1         | 1.54%   |
| CPT                     | 1         | 1.54%   |
| Chi Mei Optoelectronics | 1         | 1.54%   |
| BOE                     | 1         | 1.54%   |
| Arnos Instruments       | 1         | 1.54%   |
| AOC                     | 1         | 1.54%   |
| Ancor Communications    | 1         | 1.54%   |
| Unknown                 | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 3.08%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 2         | 3.08%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                  | 1         | 1.54%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch | 1         | 1.54%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch | 1         | 1.54%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch          | 1         | 1.54%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch          | 1         | 1.54%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 1.54%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 1.54%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                     | 1         | 1.54%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch        | 1         | 1.54%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 1.54%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 1         | 1.54%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 1.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 1.54%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 1.54%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch             | 1         | 1.54%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 1.54%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch          | 1         | 1.54%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 1.54%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch        | 1         | 1.54%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 1.54%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 1.54%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch            | 1         | 1.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1         | 1.54%   |
| Goldstar TV GSM9CF5 1360x768 700x392mm 31.6-inch                     | 1         | 1.54%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                | 1         | 1.54%   |
| Goldstar M198WA GSM4B36 1440x900 408x255mm 18.9-inch                 | 1         | 1.54%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 1         | 1.54%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 20        | 31.25%  |
| 1920x1080 (FHD)   | 15        | 23.44%  |
| 1280x800 (WXGA)   | 7         | 10.94%  |
| 1024x600          | 7         | 10.94%  |
| 1440x900 (WXGA+)  | 4         | 6.25%   |
| 1600x1200         | 2         | 3.13%   |
| 1280x1024 (SXGA)  | 2         | 3.13%   |
| 4480x3600         | 1         | 1.56%   |
| 2560x1080         | 1         | 1.56%   |
| 2288x1287         | 1         | 1.56%   |
| 1920x1200 (WUXGA) | 1         | 1.56%   |
| 1600x900 (HD+)    | 1         | 1.56%   |
| 1360x768          | 1         | 1.56%   |
| Unknown           | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 28.13%  |
| 21      | 7         | 10.94%  |
| 10      | 6         | 9.38%   |
| 14      | 5         | 7.81%   |
| 17      | 4         | 6.25%   |
| 13      | 4         | 6.25%   |
| 11      | 3         | 4.69%   |
| 24      | 2         | 3.13%   |
| 23      | 2         | 3.13%   |
| 18      | 2         | 3.13%   |
| 12      | 2         | 3.13%   |
| 8       | 2         | 3.13%   |
| 38      | 1         | 1.56%   |
| 34      | 1         | 1.56%   |
| 32      | 1         | 1.56%   |
| 31      | 1         | 1.56%   |
| 27      | 1         | 1.56%   |
| 19      | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 39.06%  |
| 201-300     | 14        | 21.88%  |
| 401-500     | 9         | 14.06%  |
| 501-600     | 5         | 7.81%   |
| 351-400     | 4         | 6.25%   |
| 701-800     | 2         | 3.13%   |
| 101-200     | 2         | 3.13%   |
| 801-900     | 1         | 1.56%   |
| 601-700     | 1         | 1.56%   |
| Unknown     | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 43        | 69.35%  |
| 16/10   | 12        | 19.35%  |
| 4/3     | 3         | 4.84%   |
| 5/4     | 1         | 1.61%   |
| 3/2     | 1         | 1.61%   |
| 21/9    | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 26.56%  |
| 201-250        | 9         | 14.06%  |
| 81-90          | 7         | 10.94%  |
| 41-50          | 6         | 9.38%   |
| 51-60          | 3         | 4.69%   |
| 351-500        | 3         | 4.69%   |
| 151-200        | 3         | 4.69%   |
| 141-150        | 3         | 4.69%   |
| 71-80          | 2         | 3.13%   |
| 61-70          | 2         | 3.13%   |
| 1-40           | 2         | 3.13%   |
| 131-140        | 2         | 3.13%   |
| 301-350        | 1         | 1.56%   |
| 121-130        | 1         | 1.56%   |
| 111-120        | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 44.44%  |
| 51-100  | 18        | 28.57%  |
| 121-160 | 14        | 22.22%  |
| 1-50    | 2         | 3.17%   |
| Unknown | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 85.56%  |
| 0     | 9         | 10%     |
| 2     | 4         | 4.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 40        | 28.99%  |
| Intel                            | 29        | 21.01%  |
| Qualcomm Atheros                 | 26        | 18.84%  |
| Broadcom                         | 17        | 12.32%  |
| Nvidia                           | 5         | 3.62%   |
| Marvell Technology Group         | 4         | 2.9%    |
| Ralink                           | 3         | 2.17%   |
| Silicon Integrated Systems [SiS] | 2         | 1.45%   |
| Ralink Technology                | 2         | 1.45%   |
| Qualcomm Atheros Communications  | 2         | 1.45%   |
| Texas Instruments                | 1         | 0.72%   |
| Samsung Electronics              | 1         | 0.72%   |
| MediaTek                         | 1         | 0.72%   |
| LSI                              | 1         | 0.72%   |
| Hewlett-Packard                  | 1         | 0.72%   |
| Broadcom Limited                 | 1         | 0.72%   |
| Attansic Technology              | 1         | 0.72%   |
| ASIX Electronics                 | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 7.93%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12        | 7.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 5.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.44%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 2.44%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 1.83%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.83%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 1.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.22%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 1.22%   |
| Intel Wireless 7260                                                     | 2         | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.22%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 1.22%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.22%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.61%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.61%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 32%     |
| Qualcomm Atheros                | 23        | 30.67%  |
| Broadcom                        | 12        | 16%     |
| Realtek Semiconductor           | 7         | 9.33%   |
| Ralink                          | 3         | 4%      |
| Ralink Technology               | 2         | 2.67%   |
| Qualcomm Atheros Communications | 2         | 2.67%   |
| Texas Instruments               | 1         | 1.33%   |
| MediaTek                        | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 11.84%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 5.26%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 3.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 3.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 3.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 2.63%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 2.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.63%   |
| Intel Wireless 7260                                                           | 2         | 2.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 2.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.63%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 2.63%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.32%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.32%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.32%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 1.32%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 1.32%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.32%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.32%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.32%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.32%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.32%   |
| Intel Wireless 3165                                                           | 1         | 1.32%   |
| Intel WiFi Link 5100                                                          | 1         | 1.32%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.32%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.32%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 46.91%  |
| Intel                            | 15        | 18.52%  |
| Broadcom                         | 8         | 9.88%   |
| Qualcomm Atheros                 | 5         | 6.17%   |
| Nvidia                           | 5         | 6.17%   |
| Marvell Technology Group         | 4         | 4.94%   |
| Silicon Integrated Systems [SiS] | 2         | 2.47%   |
| Samsung Electronics              | 1         | 1.23%   |
| Broadcom Limited                 | 1         | 1.23%   |
| Attansic Technology              | 1         | 1.23%   |
| ASIX Electronics                 | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 16.05%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 14.81%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 9.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.7%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 2.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 2.47%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 2.47%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 2.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.23%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.23%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.23%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.23%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.23%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.23%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.23%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.23%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.23%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.23%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.23%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.23%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.23%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 50.32%  |
| WiFi     | 70        | 45.16%  |
| Modem    | 7         | 4.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 64.84%  |
| Ethernet | 32        | 35.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 64.04%  |
| 1     | 32        | 35.96%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 78.89%  |
| Yes  | 19        | 21.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 8.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 8.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.88%   |
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
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| Intel Bluetooth Device                              | 1         | 2.94%   |
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

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 63.37%  |
| Nvidia                           | 12        | 11.88%  |
| AMD                              | 11        | 10.89%  |
| VIA Technologies                 | 3         | 2.97%   |
| C-Media Electronics              | 3         | 2.97%   |
| Silicon Integrated Systems [SiS] | 2         | 1.98%   |
| ESS Technology                   | 2         | 1.98%   |
| Creative Labs                    | 2         | 1.98%   |
| ULi Electronics                  | 1         | 0.99%   |
| Ensoniq                          | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 17.27%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 5.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 3.64%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.73%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.73%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2         | 1.82%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.82%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 1.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.82%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.82%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.82%   |
| AMD High Definition Audio Controller                                       | 2         | 1.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.82%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.91%   |
| VIA Technologies High Definition Audio Controller                          | 1         | 0.91%   |
| ULi Electronics HD Audio Controller                                        | 1         | 0.91%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.91%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.91%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.91%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.91%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.91%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 36        | 37.11%  |
| SK hynix            | 16        | 16.49%  |
| Samsung Electronics | 13        | 13.4%   |
| Unknown             | 8         | 8.25%   |
| Kingston            | 6         | 6.19%   |
| Micron Technology   | 4         | 4.12%   |
| Crucial             | 2         | 2.06%   |
| Corsair             | 2         | 2.06%   |
| Unknown (ABCD)      | 1         | 1.03%   |
| Unknown (8A02)      | 1         | 1.03%   |
| Unknown (0x0DA2)    | 1         | 1.03%   |
| tigo                | 1         | 1.03%   |
| Smart               | 1         | 1.03%   |
| Ramaxel Technology  | 1         | 1.03%   |
| Patriot             | 1         | 1.03%   |
| Kllisre             | 1         | 1.03%   |
| Avant               | 1         | 1.03%   |
| A-DATA Technology   | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 8         | 7.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 4         | 3.85%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 2.88%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 1.92%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 1.92%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 2         | 1.92%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 2         | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.92%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s       | 2         | 1.92%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 2         | 1.92%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 2         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 1.92%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 2         | 1.92%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 0.96%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 0.96%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 0.96%   |
| Unknown RAM Module 512MB SODIMM DDR2                           | 1         | 0.96%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 0.96%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.96%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 0.96%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.96%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 0.96%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 0.96%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 0.96%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.96%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 0.96%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1         | 0.96%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 32.94%  |
| SDRAM   | 16        | 18.82%  |
| DDR2    | 15        | 17.65%  |
| DDR4    | 10        | 11.76%  |
| DDR     | 8         | 9.41%   |
| DRAM    | 4         | 4.71%   |
| Unknown | 2         | 2.35%   |
| LPDDR4  | 1         | 1.18%   |
| DDR5    | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 69.05%  |
| DIMM         | 25        | 29.76%  |
| Row Of Chips | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 32        | 32.65%  |
| 1024  | 21        | 21.43%  |
| 4096  | 17        | 17.35%  |
| 512   | 10        | 10.2%   |
| 16384 | 6         | 6.12%   |
| 8192  | 5         | 5.1%    |
| 256   | 3         | 3.06%   |
| 64    | 2         | 2.04%   |
| 32768 | 1         | 1.02%   |
| 232   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 26.97%  |
| 1600    | 16        | 17.98%  |
| 2400    | 5         | 5.62%   |
| 1067    | 5         | 5.62%   |
| 800     | 5         | 5.62%   |
| 1333    | 4         | 4.49%   |
| 667     | 4         | 4.49%   |
| 533     | 4         | 4.49%   |
| 4199    | 3         | 3.37%   |
| 3534    | 2         | 2.25%   |
| 3266    | 2         | 2.25%   |
| 3200    | 2         | 2.25%   |
| 2667    | 2         | 2.25%   |
| 1334    | 2         | 2.25%   |
| 200     | 2         | 2.25%   |
| 4800    | 1         | 1.12%   |
| 2048    | 1         | 1.12%   |
| 1866    | 1         | 1.12%   |
| 975     | 1         | 1.12%   |
| 400     | 1         | 1.12%   |
| 333     | 1         | 1.12%   |
| 266     | 1         | 1.12%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 20.45%  |
| Microdia                               | 5         | 11.36%  |
| Suyin                                  | 4         | 9.09%   |
| IMC Networks                           | 4         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.09%   |
| Bison Electronics                      | 4         | 9.09%   |
| Pixart Imaging                         | 3         | 6.82%   |
| Sunplus Innovation Technology          | 2         | 4.55%   |
| Silicon Motion                         | 2         | 4.55%   |
| Apple                                  | 2         | 4.55%   |
| Syntek                                 | 1         | 2.27%   |
| Realtek Semiconductor                  | 1         | 2.27%   |
| Lite-On Technology                     | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| Importek                               | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 3         | 6.82%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 6.82%   |
| Suyin USB 2.0 Camera                                    | 2         | 4.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.55%   |
| Bison BisonCam, NB Pro                                  | 2         | 4.55%   |
| Syntek Integrated Camera                                | 1         | 2.27%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.27%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.27%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.27%   |
| Sunplus HD WebCam                                       | 1         | 2.27%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.27%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.27%   |
| Realtek HD WebCam                                       | 1         | 2.27%   |
| Microdia Integrated Webcam                              | 1         | 2.27%   |
| Microdia Integrated Camera                              | 1         | 2.27%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 2.27%   |
| Lenovo Integrated Webcam                                | 1         | 2.27%   |
| Importek FJ Camera                                      | 1         | 2.27%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.27%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.27%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.27%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.27%   |
| Chicony HP Webcam                                       | 1         | 2.27%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.27%   |
| Chicony HD WebCam                                       | 1         | 2.27%   |
| Chicony EasyCamera                                      | 1         | 2.27%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.27%   |
| Chicony CNF7050                                         | 1         | 2.27%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.27%   |
| Bison Lenovo EasyCamera                                 | 1         | 2.27%   |
| Bison Acer Crystal Eye Webcam                           | 1         | 2.27%   |
| Apple FaceTime Camera                                   | 1         | 2.27%   |
| Apple Built-in iSight                                   | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 5         | 71.43%  |
| Validity Sensors | 1         | 14.29%  |
| Upek             | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 42.86%  |
| AuthenTec AES1600                                      | 2         | 28.57%  |
| Validity Sensors VFS491                                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 62        | 69.66%  |
| 1     | 22        | 24.72%  |
| 3     | 3         | 3.37%   |
| 2     | 2         | 2.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 20        | 58.82%  |
| Fingerprint reader       | 7         | 20.59%  |
| Communication controller | 3         | 8.82%   |
| Sound                    | 1         | 2.94%   |
| Net/ethernet             | 1         | 2.94%   |
| Modem                    | 1         | 2.94%   |
| Chipcard                 | 1         | 2.94%   |


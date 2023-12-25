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

Total: 124

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir6,1               | Notebook    | [0275987230](https://linux-hardware.org/?probe=0275987230) | Dec 22, 2023 |
| Unknown       | TK23D                       | Notebook    | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| Dell          | 0FG011                      | Desktop     | [4a5701f000](https://linux-hardware.org/?probe=4a5701f000) | Dec 04, 2023 |
| Acer          | AO531h                      | Notebook    | [25d156801c](https://linux-hardware.org/?probe=25d156801c) | Nov 28, 2023 |
| Acer          | AO531h                      | Notebook    | [1b430bd7c0](https://linux-hardware.org/?probe=1b430bd7c0) | Nov 28, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3baedd7e19](https://linux-hardware.org/?probe=3baedd7e19) | Oct 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Google        | Lava                        | Notebook    | [8fb77bcc40](https://linux-hardware.org/?probe=8fb77bcc40) | Oct 09, 2023 |
| Fujitsu       | FMVA05007                   | Notebook    | [265b66f904](https://linux-hardware.org/?probe=265b66f904) | Oct 05, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 35        | 35.71%  |
| antiX 22       | 26        | 26.53%  |
| antiX 19.2     | 8         | 8.16%   |
| antiX 23       | 7         | 7.14%   |
| antiX 19.3     | 5         | 5.1%    |
| antiX 17.4.1   | 4         | 4.08%   |
| antiX 21-runit | 3         | 3.06%   |
| antiX 19.4     | 3         | 3.06%   |
| antiX 19.1     | 2         | 2.04%   |
| antiX 19.5     | 1         | 1.02%   |
| antiX 17.2.1   | 1         | 1.02%   |
| antiX 17.1     | 1         | 1.02%   |
| antiX 17       | 1         | 1.02%   |
| antiX 15       | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 97        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 16        | 16.33%  |
| 5.10.142-antix.2-amd64-smp   | 13        | 13.27%  |
| 4.9.0-279-antix.1-amd64-smp  | 10        | 10.2%   |
| 4.9.0-326-antix.1-amd64-smp  | 9         | 9.18%   |
| 5.10.57-antix.1-amd64-smp    | 8         | 8.16%   |
| 4.9.235-antix.1-amd64-smp    | 4         | 4.08%   |
| 4.9.160-antix.2-486-smp      | 4         | 4.08%   |
| 4.9.0-326-antix.1-486-smp    | 4         | 4.08%   |
| 5.10.188-antix.1-amd64-smp   | 3         | 3.06%   |
| 5.10.188-antix.1-486-smp     | 3         | 3.06%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 3.06%   |
| 4.9.212-antix.1-486-smp      | 3         | 3.06%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 2.04%   |
| 4.9.200-antix.1-486-smp      | 2         | 2.04%   |
| 6.2.9-1-liquorix-amd64       | 1         | 1.02%   |
| 6.1.55-antix.1-amd64-smp     | 1         | 1.02%   |
| 6.1.0-0.deb11.9-rt-amd64     | 1         | 1.02%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.02%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.02%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.02%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.02%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.02%   |
| 4.9.0-264-antix.1-amd64-smp  | 1         | 1.02%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.02%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.02%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.02%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.02%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 41        | 42.27%  |
| 5.10.142 | 13        | 13.4%   |
| 5.10.57  | 8         | 8.25%   |
| 5.10.188 | 6         | 6.19%   |
| 4.9.212  | 6         | 6.19%   |
| 4.9.160  | 5         | 5.15%   |
| 4.9.235  | 4         | 4.12%   |
| 5.10.88  | 2         | 2.06%   |
| 4.9.200  | 2         | 2.06%   |
| 6.2.9    | 1         | 1.03%   |
| 6.1.55   | 1         | 1.03%   |
| 6.1.0    | 1         | 1.03%   |
| 5.14.0   | 1         | 1.03%   |
| 5.10.27  | 1         | 1.03%   |
| 4.9.87   | 1         | 1.03%   |
| 4.19.202 | 1         | 1.03%   |
| 4.19.100 | 1         | 1.03%   |
| 4.19.0   | 1         | 1.03%   |
| 4.10.5   | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 59        | 60.82%  |
| 5.10    | 30        | 30.93%  |
| 4.19    | 3         | 3.09%   |
| 6.1     | 2         | 2.06%   |
| 6.2     | 1         | 1.03%   |
| 5.14    | 1         | 1.03%   |
| 4.10    | 1         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 61        | 62.89%  |
| i686   | 35        | 36.08%  |
| i586   | 1         | 1.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| icewm        | 44        | 45.36%  |
| Unknown      | 39        | 40.21%  |
| XFCE         | 5         | 5.15%   |
| jwm          | 3         | 3.09%   |
| fluxbox      | 2         | 2.06%   |
| LXQt         | 1         | 1.03%   |
| herbstluftwm | 1         | 1.03%   |
| GNOME        | 1         | 1.03%   |
| Cinnamon     | 1         | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 95        | 97.94%  |
| Tty  | 2         | 2.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 51.55%  |
| SLiM    | 23        | 23.71%  |
| SLIMSKI | 14        | 14.43%  |
| LightDM | 7         | 7.22%   |
| XDM     | 1         | 1.03%   |
| SDDM    | 1         | 1.03%   |
| LXDM    | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 35        | 36.08%  |
| ru_RU   | 10        | 10.31%  |
| de_DE   | 6         | 6.19%   |
| pt_BR   | 5         | 5.15%   |
| ja_JP   | 4         | 4.12%   |
| it_IT   | 4         | 4.12%   |
| en_GB   | 4         | 4.12%   |
| pl_PL   | 3         | 3.09%   |
| es_ES   | 3         | 3.09%   |
| Unknown | 3         | 3.09%   |
| sk_SK   | 2         | 2.06%   |
| nl_NL   | 2         | 2.06%   |
| es_AR   | 2         | 2.06%   |
| en_AU   | 2         | 2.06%   |
| zh_HK   | 1         | 1.03%   |
| uk_UA   | 1         | 1.03%   |
| tr_TR   | 1         | 1.03%   |
| hu_HU   | 1         | 1.03%   |
| fr_FR   | 1         | 1.03%   |
| fr_BE   | 1         | 1.03%   |
| es_VE   | 1         | 1.03%   |
| es_PE   | 1         | 1.03%   |
| es_MX   | 1         | 1.03%   |
| en_NZ   | 1         | 1.03%   |
| de_AT   | 1         | 1.03%   |
| da_DK   | 1         | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 76        | 78.35%  |
| EFI  | 21        | 21.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 83        | 85.57%  |
| Overlay  | 11        | 11.34%  |
| Xfs      | 1         | 1.03%   |
| Reiserfs | 1         | 1.03%   |
| Ext2     | 1         | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 69        | 71.13%  |
| GPT     | 26        | 26.8%   |
| Unknown | 2         | 2.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 77.55%  |
| Yes       | 22        | 22.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 62.89%  |
| Yes       | 36        | 37.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 13.4%   |
| Hewlett-Packard     | 12        | 12.37%  |
| Lenovo              | 9         | 9.28%   |
| Acer                | 9         | 9.28%   |
| Dell                | 6         | 6.19%   |
| MSI                 | 5         | 5.15%   |
| Intel               | 5         | 5.15%   |
| IBM                 | 5         | 5.15%   |
| Fujitsu             | 4         | 4.12%   |
| Unknown             | 4         | 4.12%   |
| Toshiba             | 3         | 3.09%   |
| Gigabyte Technology | 3         | 3.09%   |
| Apple               | 3         | 3.09%   |
| Pegatron            | 2         | 2.06%   |
| KOHJINSHA           | 2         | 2.06%   |
| Google              | 2         | 2.06%   |
| VXL                 | 1         | 1.03%   |
| Samsung Electronics | 1         | 1.03%   |
| Radiant Systems     | 1         | 1.03%   |
| Packard Bell        | 1         | 1.03%   |
| Medion              | 1         | 1.03%   |
| Compaq              | 1         | 1.03%   |
| Biostar             | 1         | 1.03%   |
| AZW                 | 1         | 1.03%   |
| ASRock              | 1         | 1.03%   |
| AMI                 | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 5         | 5.15%   |
| MSI US Desktop                     | 2         | 2.06%   |
| IBM 260921H                        | 2         | 2.06%   |
| HP Mini 110-3700                   | 2         | 2.06%   |
| Fujitsu FMVNU6G1C                  | 2         | 2.06%   |
| VXL TC7520d                        | 1         | 1.03%   |
| Toshiba Satellite T110             | 1         | 1.03%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.03%   |
| Toshiba Satellite 1905             | 1         | 1.03%   |
| Samsung SQ1S                       | 1         | 1.03%   |
| Radiant Systems P845               | 1         | 1.03%   |
| Pegatron VC902AA-ABF p6136fr       | 1         | 1.03%   |
| Pegatron AU930AA-ACJ p6270in       | 1         | 1.03%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.03%   |
| MSI MS-7C56                        | 1         | 1.03%   |
| MSI MS-7B17                        | 1         | 1.03%   |
| MSI GE62 7RE                       | 1         | 1.03%   |
| Medion WIM2170                     | 1         | 1.03%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.03%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.03%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.03%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.03%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.03%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.03%   |
| Lenovo G550 2958                   | 1         | 1.03%   |
| Lenovo 3000 V100 076346G           | 1         | 1.03%   |
| KOHJINSHA SX series                | 1         | 1.03%   |
| KOHJINSHA SC series                | 1         | 1.03%   |
| Intel powered classmate PC         | 1         | 1.03%   |
| Intel H61                          | 1         | 1.03%   |
| Intel DG41TY AAE47335-202          | 1         | 1.03%   |
| Intel D525MW AAE93082-401          | 1         | 1.03%   |
| Intel D425KT AAE93083-400          | 1         | 1.03%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.03%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.03%   |
| IBM ThinkPad T40 237342G           | 1         | 1.03%   |
| HP t5740                           | 1         | 1.03%   |
| HP Presario CQ56                   | 1         | 1.03%   |
| HP Pavilion dv2700                 | 1         | 1.03%   |
| HP Mini 5101                       | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 7.22%   |
| Unknown               | 5         | 5.15%   |
| Toshiba Satellite     | 3         | 3.09%   |
| Lenovo IdeaPad        | 3         | 3.09%   |
| IBM ThinkPad          | 3         | 3.09%   |
| HP Mini               | 3         | 3.09%   |
| Dell Latitude         | 3         | 3.09%   |
| MSI US                | 2         | 2.06%   |
| Lenovo ThinkPad       | 2         | 2.06%   |
| IBM 260921H           | 2         | 2.06%   |
| HP EliteBook          | 2         | 2.06%   |
| Fujitsu FMVNU6G1C     | 2         | 2.06%   |
| Dell OptiPlex         | 2         | 2.06%   |
| ASUS VivoBook         | 2         | 2.06%   |
| ASUS PRIME            | 2         | 2.06%   |
| VXL TC7520d           | 1         | 1.03%   |
| Samsung SQ1S          | 1         | 1.03%   |
| Radiant Systems P845  | 1         | 1.03%   |
| Pegatron VC902AA-ABF  | 1         | 1.03%   |
| Pegatron AU930AA-ACJ  | 1         | 1.03%   |
| Packard Bell EasyNote | 1         | 1.03%   |
| MSI MS-7C56           | 1         | 1.03%   |
| MSI MS-7B17           | 1         | 1.03%   |
| MSI GE62              | 1         | 1.03%   |
| Medion WIM2170        | 1         | 1.03%   |
| Lenovo ThinkCentre    | 1         | 1.03%   |
| Lenovo G550           | 1         | 1.03%   |
| Lenovo 3000           | 1         | 1.03%   |
| KOHJINSHA SX          | 1         | 1.03%   |
| KOHJINSHA SC          | 1         | 1.03%   |
| Intel powered         | 1         | 1.03%   |
| Intel H61             | 1         | 1.03%   |
| Intel DG41TY          | 1         | 1.03%   |
| Intel D525MW          | 1         | 1.03%   |
| Intel D425KT          | 1         | 1.03%   |
| HP t5740              | 1         | 1.03%   |
| HP Presario           | 1         | 1.03%   |
| HP Pavilion           | 1         | 1.03%   |
| HP G5000              | 1         | 1.03%   |
| HP All-in-One         | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 14        | 14.43%  |
| 2008    | 12        | 12.37%  |
| 2007    | 12        | 12.37%  |
| 2012    | 6         | 6.19%   |
| 2010    | 6         | 6.19%   |
| 2014    | 5         | 5.15%   |
| 2013    | 5         | 5.15%   |
| 2011    | 5         | 5.15%   |
| 2018    | 4         | 4.12%   |
| 2021    | 3         | 3.09%   |
| 2020    | 3         | 3.09%   |
| 2017    | 3         | 3.09%   |
| 2005    | 3         | 3.09%   |
| 2004    | 3         | 3.09%   |
| 2003    | 3         | 3.09%   |
| 2022    | 2         | 2.06%   |
| 2019    | 2         | 2.06%   |
| 1999    | 2         | 2.06%   |
| 2023    | 1         | 1.03%   |
| 2016    | 1         | 1.03%   |
| 2006    | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 66        | 68.04%  |
| Desktop    | 26        | 26.8%   |
| Mini pc    | 4         | 4.12%   |
| All in one | 1         | 1.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 97.94%  |
| Yes  | 2         | 2.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 28        | 28.87%  |
| 1.01-2.0    | 18        | 18.56%  |
| 0.51-1.0    | 13        | 13.4%   |
| 2.01-3.0    | 11        | 11.34%  |
| 4.01-8.0    | 6         | 6.19%   |
| 32.01-64.0  | 6         | 6.19%   |
| 0.01-0.5    | 6         | 6.19%   |
| 8.01-16.0   | 4         | 4.12%   |
| 16.01-24.0  | 3         | 3.09%   |
| 64.01-256.0 | 2         | 2.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 35        | 35.71%  |
| 0.01-0.5   | 32        | 32.65%  |
| 1.01-2.0   | 19        | 19.39%  |
| 2.01-3.0   | 9         | 9.18%   |
| 4.01-8.0   | 2         | 2.04%   |
| 32.01-64.0 | 1         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 73.47%  |
| 2      | 14        | 14.29%  |
| 3      | 5         | 5.1%    |
| 4      | 3         | 3.06%   |
| 0      | 3         | 3.06%   |
| 5      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 56.7%   |
| Yes       | 42        | 43.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 85.57%  |
| No        | 14        | 14.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 77.32%  |
| No        | 22        | 22.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 59.79%  |
| Yes       | 39        | 40.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 15        | 15.46%  |
| Russia      | 12        | 12.37%  |
| Hong Kong   | 10        | 10.31%  |
| Germany     | 8         | 8.25%   |
| Poland      | 5         | 5.15%   |
| Japan       | 5         | 5.15%   |
| Brazil      | 5         | 5.15%   |
| Italy       | 4         | 4.12%   |
| UK          | 3         | 3.09%   |
| Netherlands | 3         | 3.09%   |
| Spain       | 2         | 2.06%   |
| Slovakia    | 2         | 2.06%   |
| Hungary     | 2         | 2.06%   |
| France      | 2         | 2.06%   |
| Denmark     | 2         | 2.06%   |
| Australia   | 2         | 2.06%   |
| Argentina   | 2         | 2.06%   |
| Uruguay     | 1         | 1.03%   |
| Ukraine     | 1         | 1.03%   |
| Peru        | 1         | 1.03%   |
| New Zealand | 1         | 1.03%   |
| Mexico      | 1         | 1.03%   |
| Kenya       | 1         | 1.03%   |
| Kazakhstan  | 1         | 1.03%   |
| India       | 1         | 1.03%   |
| Greece      | 1         | 1.03%   |
| Chile       | 1         | 1.03%   |
| Bulgaria    | 1         | 1.03%   |
| Belgium     | 1         | 1.03%   |
| Austria     | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 7.07%   |
| Sydney                    | 2         | 2.02%   |
| St Petersburg             | 2         | 2.02%   |
| Moscow                    | 2         | 2.02%   |
| Central                   | 2         | 2.02%   |
| Bratislava                | 2         | 2.02%   |
| Zagnansk                  | 1         | 1.01%   |
| Yuzhno-Sakhalinsk         | 1         | 1.01%   |
| Yokohama                  | 1         | 1.01%   |
| Ybbs an der Donau         | 1         | 1.01%   |
| Whitney                   | 1         | 1.01%   |
| Warsaw                    | 1         | 1.01%   |
| Violes                    | 1         | 1.01%   |
| Tver                      | 1         | 1.01%   |
| Trecate                   | 1         | 1.01%   |
| Torricella Sicura         | 1         | 1.01%   |
| Toms River                | 1         | 1.01%   |
| Tokyo                     | 1         | 1.01%   |
| St Albans                 | 1         | 1.01%   |
| Sofia                     | 1         | 1.01%   |
| Sheung Shui               | 1         | 1.01%   |
| Seattle                   | 1         | 1.01%   |
| Schloss Holte-Stukenbrock | 1         | 1.01%   |
| Santiago                  | 1         | 1.01%   |
| Salto                     | 1         | 1.01%   |
| Rotterdam                 | 1         | 1.01%   |
| Romilly-sur-Seine         | 1         | 1.01%   |
| Reutlingen                | 1         | 1.01%   |
| Purmerend                 | 1         | 1.01%   |
| Pritzwalk                 | 1         | 1.01%   |
| Portland                  | 1         | 1.01%   |
| Pomaz                     | 1         | 1.01%   |
| Padova                    | 1         | 1.01%   |
| Otwock                    | 1         | 1.01%   |
| Nova Londrina             | 1         | 1.01%   |
| Norden                    | 1         | 1.01%   |
| Neyagawa                  | 1         | 1.01%   |
| Nairobi                   | 1         | 1.01%   |
| Montevideo                | 1         | 1.01%   |
| Mittegrossefehn           | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 22        | 24     | 18.49%  |
| Seagate                   | 19        | 19     | 15.97%  |
| Samsung Electronics       | 13        | 15     | 10.92%  |
| Hitachi                   | 13        | 14     | 10.92%  |
| Toshiba                   | 11        | 12     | 9.24%   |
| Unknown                   | 6         | 6      | 5.04%   |
| Kingston                  | 4         | 5      | 3.36%   |
| Maxtor                    | 3         | 3      | 2.52%   |
| BHT                       | 3         | 5      | 2.52%   |
| Micron/Crucial Technology | 2         | 2      | 1.68%   |
| Intel                     | 2         | 2      | 1.68%   |
| HGST                      | 2         | 2      | 1.68%   |
| Unknown                   | 2         | 2      | 1.68%   |
| Zheino                    | 1         | 1      | 0.84%   |
| Unknown (CF)              | 1         | 1      | 0.84%   |
| Transcend                 | 1         | 1      | 0.84%   |
| SanDisk                   | 1         | 1      | 0.84%   |
| RECADATA                  | 1         | 1      | 0.84%   |
| PNY                       | 1         | 1      | 0.84%   |
| OCZ                       | 1         | 1      | 0.84%   |
| NVMe                      | 1         | 1      | 0.84%   |
| IBM/Hitachi               | 1         | 1      | 0.84%   |
| Hewlett-Packard           | 1         | 1      | 0.84%   |
| Fujitsu                   | 1         | 1      | 0.84%   |
| Crucial                   | 1         | 1      | 0.84%   |
| China                     | 1         | 1      | 0.84%   |
| BIWIN                     | 1         | 1      | 0.84%   |
| ASUS-PHISON               | 1         | 1      | 0.84%   |
| Apple                     | 1         | 1      | 0.84%   |
| Apacer                    | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| WDC WD800AAJS-75M0A0 80GB         | 2         | 1.64%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 2         | 1.64%   |
| WDC WD10SPZX-80Z10T2 1TB          | 2         | 1.64%   |
| Toshiba MQ01ABD100 1TB            | 2         | 1.64%   |
| Toshiba MQ01ABD050V -63 500GB     | 2         | 1.64%   |
| Seagate ST980811AS 80GB           | 2         | 1.64%   |
| Samsung SSD 850 EVO 120GB         | 2         | 1.64%   |
| Samsung SSD 750 EVO 120GB         | 2         | 1.64%   |
| Maxtor Z1 SSD 240GB               | 2         | 1.64%   |
| Kingston SA400S37240G 240GB SSD   | 2         | 1.64%   |
| Hitachi HTS723232A7A364 320GB     | 2         | 1.64%   |
| Hitachi HTS548040M9AT00 40GB      | 2         | 1.64%   |
| Hitachi HTS542525K9SA00 250GB     | 2         | 1.64%   |
| BHT WR202F0032G 670270F5 32GB SSD | 2         | 1.64%   |
| Unknown                           | 2         | 1.64%   |
| Zheino CHN-mSATAM3-128 128GB SSD  | 1         | 0.82%   |
| WDC WD8088AADS-00M2B0 809GB       | 1         | 0.82%   |
| WDC WD800JB-00ETA0 80GB           | 1         | 0.82%   |
| WDC WD5000LPLX-08ZNTT0 500GB      | 1         | 0.82%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 0.82%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 0.82%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 0.82%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 0.82%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 0.82%   |
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 0.82%   |
| WDC WD205BA 21GB                  | 1         | 0.82%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1         | 0.82%   |
| WDC WD1600BEVT-60ZCT1 160GB       | 1         | 0.82%   |
| WDC WD1600BEVT-00M9YT0 160GB      | 1         | 0.82%   |
| WDC WD1600BEVS-22RST0 160GB       | 1         | 0.82%   |
| WDC WD1600AAJS-00PSA0 160GB       | 1         | 0.82%   |
| WDC WD1200BEVE-00A0HT0 120GB      | 1         | 0.82%   |
| WDC WD10EADS-65M2B0 1TB           | 1         | 0.82%   |
| WDC WD1005FBYZ-01YCBB3 1TB        | 1         | 0.82%   |
| Unknown SR64G  64GB               | 1         | 0.82%   |
| Unknown SD16G  16GB               | 1         | 0.82%   |
| Unknown SD/MMC/MS PRO 128GB       | 1         | 0.82%   |
| Unknown hB8aP  32GB               | 1         | 0.82%   |
| Unknown HAG2e  16GB               | 1         | 0.82%   |
| Unknown 2GB ATA Flash Disk        | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 28.95%  |
| Seagate             | 19        | 19     | 25%     |
| Hitachi             | 13        | 14     | 17.11%  |
| Toshiba             | 9         | 10     | 11.84%  |
| Samsung Electronics | 6         | 7      | 7.89%   |
| Unknown             | 2         | 2      | 2.63%   |
| HGST                | 2         | 2      | 2.63%   |
| Maxtor              | 1         | 1      | 1.32%   |
| IBM/Hitachi         | 1         | 1      | 1.32%   |
| Fujitsu             | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 15.15%  |
| Kingston            | 4         | 5      | 12.12%  |
| BHT                 | 3         | 5      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Maxtor              | 2         | 2      | 6.06%   |
| Unknown             | 2         | 2      | 6.06%   |
| Zheino              | 1         | 1      | 3.03%   |
| Unknown (CF)        | 1         | 1      | 3.03%   |
| Transcend           | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| RECADATA            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| BIWIN               | 1         | 1      | 3.03%   |
| ASUS-PHISON         | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| Apacer              | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 68        | 81     | 62.96%  |
| SSD  | 31        | 36     | 28.7%   |
| NVMe | 5         | 7      | 4.63%   |
| MMC  | 4         | 4      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 115    | 89.11%  |
| NVMe | 5         | 7      | 4.95%   |
| MMC  | 4         | 4      | 3.96%   |
| SAS  | 2         | 2      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 101    | 84.85%  |
| 0.51-1.0   | 13        | 13     | 13.13%  |
| 1.01-2.0   | 1         | 1      | 1.01%   |
| 4.01-10.0  | 1         | 2      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 31.31%  |
| 1-20           | 21        | 21.21%  |
| 21-50          | 13        | 13.13%  |
| 51-100         | 13        | 13.13%  |
| 251-500        | 11        | 11.11%  |
| 501-1000       | 6         | 6.06%   |
| More than 3000 | 2         | 2.02%   |
| 1001-2000      | 1         | 1.01%   |
| Unknown        | 1         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 72        | 74.23%  |
| 21-50          | 9         | 9.28%   |
| 101-250        | 8         | 8.25%   |
| 51-100         | 4         | 4.12%   |
| More than 3000 | 2         | 2.06%   |
| 501-1000       | 1         | 1.03%   |
| Unknown        | 1         | 1.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2         | 2      | 4.76%   |
| Seagate ST980811AS 80GB                     | 2         | 2      | 4.76%   |
| Hitachi HTS542525K9SA00 250GB               | 2         | 2      | 4.76%   |
| WDC WD800JB-00ETA0 80GB                     | 1         | 1      | 2.38%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 2.38%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 1      | 2.38%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 1         | 1      | 2.38%   |
| WDC WD2500BEVT-22ZCT0 250GB                 | 1         | 1      | 2.38%   |
| WDC WD205BA 21GB                            | 1         | 1      | 2.38%   |
| WDC WD1600BEVT-00M9YT0 160GB                | 1         | 1      | 2.38%   |
| WDC WD10EADS-65M2B0 1TB                     | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.38%   |
| Toshiba MK2555GSX 250GB                     | 1         | 1      | 2.38%   |
| Seagate ST980812AS 80GB                     | 1         | 1      | 2.38%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.38%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 2.38%   |
| Seagate ST9160314AS 40GB                    | 1         | 1      | 2.38%   |
| Seagate ST9160310AS 160GB                   | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3500312CS 500GB                   | 1         | 1      | 2.38%   |
| Seagate ST3320620AS 320GB                   | 1         | 1      | 2.38%   |
| Seagate ST3320413CS 320GB                   | 1         | 1      | 2.38%   |
| Seagate ST320LT007-9ZV142 320GB             | 1         | 1      | 2.38%   |
| SanDisk sandisk120 120GB SSD                | 1         | 1      | 2.38%   |
| Samsung Electronics HM161GI 160GB           | 1         | 1      | 2.38%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1         | 1      | 2.38%   |
| Maxtor 2F040L0 41GB                         | 1         | 1      | 2.38%   |
| Hitachi HTS725050A7E630 500GB               | 1         | 1      | 2.38%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 2.38%   |
| Hitachi HTS721060G9AT00 64GB                | 1         | 1      | 2.38%   |
| Hitachi HTS548040M9AT00 40GB                | 1         | 1      | 2.38%   |
| Hitachi HTS543225A7A384 250GB               | 1         | 1      | 2.38%   |
| Hitachi HTS541612J9SA00 120GB               | 1         | 1      | 2.38%   |
| Hitachi HTC426040G8CE00 40GB                | 1         | 1      | 2.38%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.38%   |
| China M.2 SSD 128GB                         | 1         | 1      | 2.38%   |
| BIWIN SSD 32GB                              | 1         | 1      | 2.38%   |
| Apacer 32GB SATA Flash Drive SSD            | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 12        | 12     | 28.57%  |
| WDC                       | 11        | 11     | 26.19%  |
| Hitachi                   | 9         | 9      | 21.43%  |
| Toshiba                   | 2         | 2      | 4.76%   |
| SanDisk                   | 1         | 1      | 2.38%   |
| Samsung Electronics       | 1         | 1      | 2.38%   |
| Micron/Crucial Technology | 1         | 1      | 2.38%   |
| Maxtor                    | 1         | 1      | 2.38%   |
| HGST                      | 1         | 1      | 2.38%   |
| China                     | 1         | 1      | 2.38%   |
| BIWIN                     | 1         | 1      | 2.38%   |
| Apacer                    | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 32.43%  |
| WDC                 | 11        | 11     | 29.73%  |
| Hitachi             | 9         | 9      | 24.32%  |
| Toshiba             | 2         | 2      | 5.41%   |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 37     | 88.1%   |
| SSD  | 4         | 4      | 9.52%   |
| NVMe | 1         | 1      | 2.38%   |

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
| Works    | 51        | 73     | 48.57%  |
| Malfunc  | 42        | 42     | 40%     |
| Detected | 12        | 13     | 11.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 68.22%  |
| AMD                              | 10        | 9.35%   |
| Nvidia                           | 5         | 4.67%   |
| ASMedia Technology               | 4         | 3.74%   |
| VIA Technologies                 | 3         | 2.8%    |
| Silicon Integrated Systems [SiS] | 2         | 1.87%   |
| Samsung Electronics              | 2         | 1.87%   |
| Micron/Crucial Technology        | 2         | 1.87%   |
| ULi Electronics                  | 1         | 0.93%   |
| Silicon Image                    | 1         | 0.93%   |
| Marvell Technology Group         | 1         | 0.93%   |
| LSI Logic / Symbios Logic        | 1         | 0.93%   |
| JMicron Technology               | 1         | 0.93%   |
| ADATA Technology                 | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 12        | 9.02%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 6.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 4.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 4.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 3.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 5         | 3.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 3.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 3.01%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 3.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 2.26%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 2.26%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 2.26%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.5%    |
| VIA VX900 Series Serial-ATA Controller                                         | 1         | 0.75%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.75%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 0.75%   |
| ULi ULi M5288 SATA                                                             | 1         | 0.75%   |
| ULi M5229 IDE                                                                  | 1         | 0.75%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.75%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 0.75%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.75%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 0.75%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 0.75%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.75%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 0.75%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 0.75%   |
| Nvidia CK804 IDE                                                               | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 48.67%  |
| IDE  | 48        | 42.48%  |
| NVMe | 5         | 4.42%   |
| RAID | 4         | 3.54%   |
| SAS  | 1         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 80        | 82.47%  |
| AMD          | 14        | 14.43%  |
| CentaurHauls | 2         | 2.06%   |
| GenuineTMx86 | 1         | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 6.19%   |
| Intel Pentium M processor 1.60GHz           | 2         | 2.06%   |
| Intel Pentium M processor 1.00GHz           | 2         | 2.06%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2         | 2.06%   |
| Intel Genuine processor 800MHz              | 2         | 2.06%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 2.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 2.06%   |
| Intel Celeron (Mendocino)                   | 2         | 2.06%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.06%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 2.06%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 2.06%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.06%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 2.06%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.03%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.03%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.03%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.03%   |
| Intel Pentium II (Deschutes)                | 1         | 1.03%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.03%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.03%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.03%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1         | 1.03%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.03%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 1.03%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.03%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.03%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.03%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.03%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.03%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.03%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.03%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.03%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.03%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.03%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 1         | 1.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 17        | 17.53%  |
| Intel Celeron           | 10        | 10.31%  |
| Intel Core 2 Duo        | 9         | 9.28%   |
| Intel Pentium M         | 6         | 6.19%   |
| Intel Core i7           | 6         | 6.19%   |
| Intel Core i5           | 6         | 6.19%   |
| Other                   | 5         | 5.15%   |
| Intel Genuine           | 5         | 5.15%   |
| Intel Core i3           | 4         | 4.12%   |
| Intel Pentium Dual-Core | 3         | 3.09%   |
| Intel Pentium Dual      | 2         | 2.06%   |
| Intel Pentium 4         | 2         | 2.06%   |
| AMD Ryzen 7             | 2         | 2.06%   |
| AMD E2                  | 2         | 2.06%   |
| AMD Athlon 64 X2        | 2         | 2.06%   |
| Intel Xeon              | 1         | 1.03%   |
| Intel Pentium Silver    | 1         | 1.03%   |
| Intel Pentium           | 1         | 1.03%   |
| Intel Core i9           | 1         | 1.03%   |
| Intel Core 2 Quad       | 1         | 1.03%   |
| Intel Celeron M         | 1         | 1.03%   |
| Intel Celeron Dual-Core | 1         | 1.03%   |
| CentaurHauls VIA Nano   | 1         | 1.03%   |
| CentaurHauls VIA Eden   | 1         | 1.03%   |
| AMD Sempron             | 1         | 1.03%   |
| AMD Ryzen 5             | 1         | 1.03%   |
| AMD Phenom              | 1         | 1.03%   |
| AMD E1                  | 1         | 1.03%   |
| AMD Athlon II           | 1         | 1.03%   |
| AMD Athlon 64           | 1         | 1.03%   |
| AMD A6                  | 1         | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 45.36%  |
| 1      | 35        | 36.08%  |
| 4      | 11        | 11.34%  |
| 8      | 3         | 3.09%   |
| 6      | 3         | 3.09%   |
| 24     | 1         | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 97        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 58.76%  |
| 2      | 40        | 41.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 71.13%  |
| 32-bit         | 28        | 28.87%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 12        | 12.37%  |
| 0x106c2    | 10        | 10.31%  |
| Unknown    | 9         | 9.28%   |
| 0x6fd      | 5         | 5.15%   |
| 0x106ca    | 5         | 5.15%   |
| 0x6d8      | 4         | 4.12%   |
| 0x6d6      | 4         | 4.12%   |
| 0x206a7    | 4         | 4.12%   |
| 0x40651    | 3         | 3.09%   |
| 0x306a9    | 3         | 3.09%   |
| 0x30678    | 3         | 3.09%   |
| 0xa0671    | 2         | 2.06%   |
| 0x706a8    | 2         | 2.06%   |
| 0x6e8      | 2         | 2.06%   |
| 0x66a      | 2         | 2.06%   |
| 0x306c3    | 2         | 2.06%   |
| 0x30661    | 2         | 2.06%   |
| 0x10661    | 2         | 2.06%   |
| 0xf29      | 1         | 1.03%   |
| 0xf24      | 1         | 1.03%   |
| 0x906ed    | 1         | 1.03%   |
| 0x906e9    | 1         | 1.03%   |
| 0x806e9    | 1         | 1.03%   |
| 0x706a1    | 1         | 1.03%   |
| 0x695      | 1         | 1.03%   |
| 0x652      | 1         | 1.03%   |
| 0x506c9    | 1         | 1.03%   |
| 0x20655    | 1         | 1.03%   |
| 0x20652    | 1         | 1.03%   |
| 0x10676    | 1         | 1.03%   |
| 0x08701021 | 1         | 1.03%   |
| 0x08001138 | 1         | 1.03%   |
| 0x07030106 | 1         | 1.03%   |
| 0x0700010f | 1         | 1.03%   |
| 0x06006705 | 1         | 1.03%   |
| 0x06006704 | 1         | 1.03%   |
| 0x06001116 | 1         | 1.03%   |
| 0x010000c8 | 1         | 1.03%   |
| 0x01000095 | 1         | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Bonnell          | 17        | 17.53%  |
| Penryn           | 13        | 13.4%   |
| P6               | 11        | 11.34%  |
| Unknown          | 8         | 8.25%   |
| Core             | 7         | 7.22%   |
| Haswell          | 5         | 5.15%   |
| SandyBridge      | 4         | 4.12%   |
| K8 Hammer        | 4         | 4.12%   |
| Silvermont       | 3         | 3.09%   |
| KabyLake         | 3         | 3.09%   |
| IvyBridge        | 3         | 3.09%   |
| Goldmont plus    | 3         | 3.09%   |
| Westmere         | 2         | 2.06%   |
| NetBurst         | 2         | 2.06%   |
| K10              | 2         | 2.06%   |
| Excavator        | 2         | 2.06%   |
| Zen+             | 1         | 1.03%   |
| Zen 2            | 1         | 1.03%   |
| Zen              | 1         | 1.03%   |
| Puma             | 1         | 1.03%   |
| Piledriver       | 1         | 1.03%   |
| Jaguar           | 1         | 1.03%   |
| Goldmont         | 1         | 1.03%   |
| Alderlake Hybrid | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 58        | 57.43%  |
| Nvidia                           | 20        | 19.8%   |
| AMD                              | 18        | 17.82%  |
| VIA Technologies                 | 2         | 1.98%   |
| Neomagic                         | 2         | 1.98%   |
| Silicon Integrated Systems [SiS] | 1         | 0.99%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 11        | 9.32%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 7         | 5.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 5.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 5         | 4.24%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 2.54%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 2.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 1.69%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 1.69%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.69%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.69%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.69%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.69%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                  | 1         | 0.85%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 1         | 0.85%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 0.85%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.85%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 0.85%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.85%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.85%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.85%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 0.85%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                            | 1         | 0.85%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 0.85%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 0.85%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 51.55%  |
| 1 x Nvidia     | 16        | 16.49%  |
| 1 x AMD        | 14        | 14.43%  |
| 2 x AMD        | 4         | 4.12%   |
| Intel + Nvidia | 4         | 4.12%   |
| Other          | 2         | 2.06%   |
| 2 x Intel      | 2         | 2.06%   |
| 1 x VIA        | 2         | 2.06%   |
| 1 x Neomagic   | 2         | 2.06%   |
| 1 x SiS        | 1         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 78        | 80.41%  |
| Unknown     | 12        | 12.37%  |
| Proprietary | 7         | 7.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 42.27%  |
| 0.01-0.5   | 36        | 37.11%  |
| 1.01-2.0   | 13        | 13.4%   |
| 0.51-1.0   | 3         | 3.09%   |
| 5.01-6.0   | 2         | 2.06%   |
| 3.01-4.0   | 1         | 1.03%   |
| 16.01-24.0 | 1         | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 16.9%   |
| LG Display              | 10        | 14.08%  |
| Samsung Electronics     | 9         | 12.68%  |
| LG Philips              | 4         | 5.63%   |
| Goldstar                | 4         | 5.63%   |
| Chimei Innolux          | 4         | 5.63%   |
| Acer                    | 4         | 5.63%   |
| HannStar                | 3         | 4.23%   |
| Apple                   | 3         | 4.23%   |
| Lenovo                  | 2         | 2.82%   |
| Hewlett-Packard         | 2         | 2.82%   |
| Vizio                   | 1         | 1.41%   |
| ViewSonic               | 1         | 1.41%   |
| Unknown (XXX)           | 1         | 1.41%   |
| LG Electronics          | 1         | 1.41%   |
| InfoVision              | 1         | 1.41%   |
| HJW                     | 1         | 1.41%   |
| Dell                    | 1         | 1.41%   |
| CPT                     | 1         | 1.41%   |
| Chi Mei Optoelectronics | 1         | 1.41%   |
| BOE                     | 1         | 1.41%   |
| Arnos Instruments       | 1         | 1.41%   |
| AOC                     | 1         | 1.41%   |
| Ancor Communications    | 1         | 1.41%   |
| Unknown                 | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 2.82%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 2         | 2.82%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                  | 1         | 1.41%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 1         | 1.41%   |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch             | 1         | 1.41%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch | 1         | 1.41%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch | 1         | 1.41%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch          | 1         | 1.41%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch          | 1         | 1.41%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 1.41%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 1.41%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                     | 1         | 1.41%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch        | 1         | 1.41%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 1.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 1         | 1.41%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch         | 1         | 1.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 1.41%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 1.41%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch             | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 1.41%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 1         | 1.41%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 1.41%   |
| Hewlett-Packard LP2475w HWP26F7 1920x1200 540x350mm 25.3-inch        | 1         | 1.41%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch        | 1         | 1.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 1.41%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 1.41%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch            | 1         | 1.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 1         | 1.41%   |
| Goldstar TV GSM9CF5 1360x768 700x392mm 31.6-inch                     | 1         | 1.41%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                | 1         | 1.41%   |
| Goldstar M198WA GSM4B36 1440x900 408x255mm 18.9-inch                 | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 22        | 31.43%  |
| 1920x1080 (FHD)   | 17        | 24.29%  |
| 1280x800 (WXGA)   | 7         | 10%     |
| 1024x600          | 7         | 10%     |
| 1440x900 (WXGA+)  | 4         | 5.71%   |
| 1920x1200 (WUXGA) | 2         | 2.86%   |
| 1600x1200         | 2         | 2.86%   |
| 1280x1024 (SXGA)  | 2         | 2.86%   |
| 4480x3600         | 1         | 1.43%   |
| 2560x1080         | 1         | 1.43%   |
| 2288x1287         | 1         | 1.43%   |
| 1600x900 (HD+)    | 1         | 1.43%   |
| 1360x768          | 1         | 1.43%   |
| 1280x720 (HD)     | 1         | 1.43%   |
| Unknown           | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 25.71%  |
| 21      | 7         | 10%     |
| 10      | 7         | 10%     |
| 14      | 5         | 7.14%   |
| 11      | 5         | 7.14%   |
| 17      | 4         | 5.71%   |
| 13      | 4         | 5.71%   |
| 27      | 2         | 2.86%   |
| 24      | 2         | 2.86%   |
| 23      | 2         | 2.86%   |
| 18      | 2         | 2.86%   |
| 12      | 2         | 2.86%   |
| 8       | 2         | 2.86%   |
| 43      | 1         | 1.43%   |
| 38      | 1         | 1.43%   |
| 34      | 1         | 1.43%   |
| 32      | 1         | 1.43%   |
| 31      | 1         | 1.43%   |
| 25      | 1         | 1.43%   |
| 19      | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 35.71%  |
| 201-300     | 17        | 24.29%  |
| 401-500     | 9         | 12.86%  |
| 501-600     | 7         | 10%     |
| 351-400     | 4         | 5.71%   |
| 801-900     | 2         | 2.86%   |
| 701-800     | 2         | 2.86%   |
| 101-200     | 2         | 2.86%   |
| 601-700     | 1         | 1.43%   |
| Unknown     | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 47        | 69.12%  |
| 16/10   | 13        | 19.12%  |
| 4/3     | 4         | 5.88%   |
| 5/4     | 1         | 1.47%   |
| 3/2     | 1         | 1.47%   |
| 21/9    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 24.29%  |
| 201-250        | 9         | 12.86%  |
| 81-90          | 7         | 10%     |
| 41-50          | 7         | 10%     |
| 51-60          | 5         | 7.14%   |
| 351-500        | 3         | 4.29%   |
| 151-200        | 3         | 4.29%   |
| 141-150        | 3         | 4.29%   |
| 71-80          | 2         | 2.86%   |
| 61-70          | 2         | 2.86%   |
| 1-40           | 2         | 2.86%   |
| 301-350        | 2         | 2.86%   |
| 131-140        | 2         | 2.86%   |
| 501-1000       | 2         | 2.86%   |
| 251-300        | 1         | 1.43%   |
| 121-130        | 1         | 1.43%   |
| 111-120        | 1         | 1.43%   |
| Unknown        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 40.58%  |
| 51-100  | 20        | 28.99%  |
| 121-160 | 17        | 24.64%  |
| 1-50    | 3         | 4.35%   |
| Unknown | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 84        | 85.71%  |
| 0     | 10        | 10.2%   |
| 2     | 4         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 41        | 27.89%  |
| Intel                            | 34        | 23.13%  |
| Qualcomm Atheros                 | 28        | 19.05%  |
| Broadcom                         | 17        | 11.56%  |
| Nvidia                           | 5         | 3.4%    |
| Marvell Technology Group         | 4         | 2.72%   |
| Ralink                           | 3         | 2.04%   |
| Silicon Integrated Systems [SiS] | 2         | 1.36%   |
| Ralink Technology                | 2         | 1.36%   |
| Qualcomm Atheros Communications  | 2         | 1.36%   |
| Broadcom Limited                 | 2         | 1.36%   |
| Texas Instruments                | 1         | 0.68%   |
| Samsung Electronics              | 1         | 0.68%   |
| MediaTek                         | 1         | 0.68%   |
| LSI                              | 1         | 0.68%   |
| Hewlett-Packard                  | 1         | 0.68%   |
| Attansic Technology              | 1         | 0.68%   |
| ASIX Electronics                 | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 13        | 7.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 7.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 5.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 4.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.3%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 2.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 1.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 1.72%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.72%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 1.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.15%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.15%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 1.15%   |
| Intel Wireless 7260                                                     | 2         | 1.15%   |
| Intel WiFi Link 5100                                                    | 2         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.15%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.15%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 1.15%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.15%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.15%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 32.5%   |
| Qualcomm Atheros                | 25        | 31.25%  |
| Broadcom                        | 12        | 15%     |
| Realtek Semiconductor           | 7         | 8.75%   |
| Ralink                          | 3         | 3.75%   |
| Ralink Technology               | 2         | 2.5%    |
| Qualcomm Atheros Communications | 2         | 2.5%    |
| Texas Instruments               | 1         | 1.25%   |
| MediaTek                        | 1         | 1.25%   |
| Broadcom Limited                | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 10        | 12.35%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 4.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 4.94%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 3.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 3.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 2.47%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 2.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.47%   |
| Intel Wireless 7260                                                           | 2         | 2.47%   |
| Intel WiFi Link 5100                                                          | 2         | 2.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 2.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.47%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.47%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 2.47%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.23%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.23%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 1.23%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.23%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.23%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.23%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.23%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.23%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.23%   |
| Intel Wireless 7265                                                           | 1         | 1.23%   |
| Intel Wireless 3165                                                           | 1         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.23%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.23%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 39        | 45.88%  |
| Intel                            | 18        | 21.18%  |
| Broadcom                         | 8         | 9.41%   |
| Qualcomm Atheros                 | 6         | 7.06%   |
| Nvidia                           | 5         | 5.88%   |
| Marvell Technology Group         | 4         | 4.71%   |
| Silicon Integrated Systems [SiS] | 2         | 2.35%   |
| Broadcom Limited                 | 1         | 1.18%   |
| Attansic Technology              | 1         | 1.18%   |
| ASIX Electronics                 | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 15.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 15.29%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 9.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 2.35%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 2.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.35%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 2.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.18%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.18%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.18%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.18%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.18%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.18%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.18%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.18%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.18%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.18%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.18%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1         | 1.18%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.18%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.18%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 50%     |
| WiFi     | 75        | 45.18%  |
| Modem    | 8         | 4.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 63.64%  |
| Ethernet | 36        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 60.82%  |
| 1     | 38        | 39.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 78.57%  |
| Yes  | 21        | 21.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 26.32%  |
| Broadcom                        | 9         | 23.68%  |
| Cambridge Silicon Radio         | 3         | 7.89%   |
| Apple                           | 3         | 7.89%   |
| Realtek Semiconductor           | 2         | 5.26%   |
| Qualcomm Atheros Communications | 2         | 5.26%   |
| Lite-On Technology              | 2         | 5.26%   |
| IMC Networks                    | 2         | 5.26%   |
| Taiyo Yuden                     | 1         | 2.63%   |
| Ralink Technology               | 1         | 2.63%   |
| Fujitsu                         | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| ASUSTek Computer                | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 10.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.89%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.26%   |
| Intel AX201 Bluetooth                               | 2         | 5.26%   |
| IMC Networks Bluetooth Device                       | 2         | 5.26%   |
| Broadcom HP Portable SoftSailing                    | 2         | 5.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 5.26%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 5.26%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.63%   |
| Realtek Bluetooth Radio                             | 1         | 2.63%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.63%   |
| Intel Bluetooth Device                              | 1         | 2.63%   |
| Fujitsu Bluetooth Device                            | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.63%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.63%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.63%   |
| Apple Bluetooth Host Controller                     | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 70        | 63.06%  |
| Nvidia                           | 14        | 12.61%  |
| AMD                              | 12        | 10.81%  |
| VIA Technologies                 | 3         | 2.7%    |
| Creative Labs                    | 3         | 2.7%    |
| C-Media Electronics              | 3         | 2.7%    |
| Silicon Integrated Systems [SiS] | 2         | 1.8%    |
| ESS Technology                   | 2         | 1.8%    |
| ULi Electronics                  | 1         | 0.9%    |
| Ensoniq                          | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21        | 17.21%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 4.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 3.28%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.28%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.46%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.46%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.46%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2         | 1.64%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 1.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 1.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.64%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.64%   |
| AMD High Definition Audio Controller                                       | 2         | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.64%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.82%   |
| VIA Technologies High Definition Audio Controller                          | 1         | 0.82%   |
| ULi Electronics HD Audio Controller                                        | 1         | 0.82%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.82%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 0.82%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.82%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 0.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 38        | 35.85%  |
| SK hynix            | 18        | 16.98%  |
| Samsung Electronics | 13        | 12.26%  |
| Unknown             | 8         | 7.55%   |
| Kingston            | 6         | 5.66%   |
| Micron Technology   | 5         | 4.72%   |
| Corsair             | 3         | 2.83%   |
| Crucial             | 2         | 1.89%   |
| Unknown (ABCD)      | 1         | 0.94%   |
| Unknown (8A02)      | 1         | 0.94%   |
| Unknown (0x0DA2)    | 1         | 0.94%   |
| tigo                | 1         | 0.94%   |
| Smart               | 1         | 0.94%   |
| Ramaxel Technology  | 1         | 0.94%   |
| Patriot             | 1         | 0.94%   |
| Kllisre             | 1         | 0.94%   |
| Kingmax             | 1         | 0.94%   |
| G.Skill             | 1         | 0.94%   |
| fef5                | 1         | 0.94%   |
| Avant               | 1         | 0.94%   |
| A-DATA Technology   | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 8         | 7.02%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 4         | 3.51%   |
| Unknown RAM Module 1024MB SODIMM DDR                   | 3         | 2.63%   |
| Unknown RAM Module 512MB SODIMM DDR                    | 2         | 1.75%   |
| Unknown RAM Module 2GB SODIMM SDRAM                    | 2         | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s               | 2         | 1.75%   |
| Unknown RAM Module 256MB SODIMM DRAM                   | 2         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s             | 2         | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 2         | 1.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s  | 2         | 1.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 2         | 1.75%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s  | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s  | 2         | 1.75%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 2         | 1.75%   |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DRAM                   | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s           | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2                   | 1         | 0.88%   |
| Unknown RAM Module 512MB DIMM SDRAM 333MT/s            | 1         | 0.88%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s              | 1         | 0.88%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1         | 0.88%   |
| Unknown RAM Module 512MB DIMM                          | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DRAM                     | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s             | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s             | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR                      | 1         | 0.88%   |
| Unknown RAM Module 256MB DIMM SDRAM 333MT/s            | 1         | 0.88%   |
| Unknown RAM Module 256MB DIMM SDRAM                    | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                 | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s          | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM SDRAM                    | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DRAM                     | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 0.88%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 1         | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                | 1         | 0.88%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                 | 1         | 0.88%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 31.91%  |
| SDRAM   | 18        | 19.15%  |
| DDR2    | 16        | 17.02%  |
| DDR4    | 12        | 12.77%  |
| DDR     | 8         | 8.51%   |
| DRAM    | 4         | 4.26%   |
| Unknown | 3         | 3.19%   |
| LPDDR4  | 2         | 2.13%   |
| DDR5    | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 62        | 67.39%  |
| DIMM         | 28        | 30.43%  |
| Row Of Chips | 1         | 1.09%   |
| Unknown      | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 34        | 31.78%  |
| 1024  | 23        | 21.5%   |
| 4096  | 18        | 16.82%  |
| 512   | 11        | 10.28%  |
| 8192  | 7         | 6.54%   |
| 16384 | 6         | 5.61%   |
| 256   | 4         | 3.74%   |
| 64    | 2         | 1.87%   |
| 32768 | 1         | 0.93%   |
| 232   | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 25.77%  |
| 1600    | 18        | 18.56%  |
| 2400    | 6         | 6.19%   |
| 1067    | 5         | 5.15%   |
| 800     | 5         | 5.15%   |
| 533     | 5         | 5.15%   |
| 1333    | 4         | 4.12%   |
| 667     | 4         | 4.12%   |
| 4199    | 3         | 3.09%   |
| 3200    | 3         | 3.09%   |
| 3534    | 2         | 2.06%   |
| 3266    | 2         | 2.06%   |
| 2667    | 2         | 2.06%   |
| 1334    | 2         | 2.06%   |
| 333     | 2         | 2.06%   |
| 200     | 2         | 2.06%   |
| 4800    | 1         | 1.03%   |
| 3533    | 1         | 1.03%   |
| 2048    | 1         | 1.03%   |
| 1866    | 1         | 1.03%   |
| 975     | 1         | 1.03%   |
| 400     | 1         | 1.03%   |
| 266     | 1         | 1.03%   |

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
| Chicony Electronics                    | 10        | 21.74%  |
| Suyin                                  | 5         | 10.87%  |
| Microdia                               | 5         | 10.87%  |
| IMC Networks                           | 4         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8.7%    |
| Pixart Imaging                         | 3         | 6.52%   |
| Acer                                   | 3         | 6.52%   |
| Sunplus Innovation Technology          | 2         | 4.35%   |
| Silicon Motion                         | 2         | 4.35%   |
| Apple                                  | 2         | 4.35%   |
| Syntek                                 | 1         | 2.17%   |
| Realtek Semiconductor                  | 1         | 2.17%   |
| Lite-On Technology                     | 1         | 2.17%   |
| Lenovo                                 | 1         | 2.17%   |
| Importek                               | 1         | 2.17%   |
| Bison Electronics                      | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 3         | 6.52%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 6.52%   |
| Suyin USB 2.0 Camera                                    | 2         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 4.35%   |
| Chicony HD WebCam                                       | 2         | 4.35%   |
| Syntek Integrated Camera                                | 1         | 2.17%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 2.17%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.17%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 2.17%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.17%   |
| Sunplus HD WebCam                                       | 1         | 2.17%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.17%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 2.17%   |
| Realtek HD WebCam                                       | 1         | 2.17%   |
| Microdia Integrated Webcam                              | 1         | 2.17%   |
| Microdia Integrated Camera                              | 1         | 2.17%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 2.17%   |
| Lenovo Integrated Webcam                                | 1         | 2.17%   |
| Importek FJ Camera                                      | 1         | 2.17%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.17%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.17%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.17%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.17%   |
| Chicony HP Webcam                                       | 1         | 2.17%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.17%   |
| Chicony EasyCamera                                      | 1         | 2.17%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.17%   |
| Chicony CNF7050                                         | 1         | 2.17%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.17%   |
| Bison BisonCam, NB Pro                                  | 1         | 2.17%   |
| Apple FaceTime Camera                                   | 1         | 2.17%   |
| Apple Built-in iSight                                   | 1         | 2.17%   |
| Acer Lenovo EasyCamera                                  | 1         | 2.17%   |
| Acer Crystal Eye Webcam                                 | 1         | 2.17%   |
| Acer BisonCam, NB Pro                                   | 1         | 2.17%   |

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
| 0     | 69        | 71.13%  |
| 1     | 22        | 22.68%  |
| 3     | 3         | 3.09%   |
| 2     | 3         | 3.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 54.29%  |
| Fingerprint reader       | 7         | 20%     |
| Communication controller | 3         | 8.57%   |
| Sound                    | 2         | 5.71%   |
| Net/ethernet             | 1         | 2.86%   |
| Multimedia controller    | 1         | 2.86%   |
| Modem                    | 1         | 2.86%   |
| Chipcard                 | 1         | 2.86%   |


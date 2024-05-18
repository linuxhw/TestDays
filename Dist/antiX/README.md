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

Total: 145

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| HP            | Compaq 8510w                | Notebook    | [6761a4250d](https://linux-hardware.org/?probe=6761a4250d) | Apr 27, 2024 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [e1df9eba9c](https://linux-hardware.org/?probe=e1df9eba9c) | Apr 24, 2024 |
| Clevo         | M66xN                       | Notebook    | [e25bed6466](https://linux-hardware.org/?probe=e25bed6466) | Apr 19, 2024 |
| Prestigio     | Smartbook PSB116A           | Desktop     | [044fc5c4f8](https://linux-hardware.org/?probe=044fc5c4f8) | Apr 14, 2024 |
| Unknown       | TK23D                       | Notebook    | [47ffc66996](https://linux-hardware.org/?probe=47ffc66996) | Apr 05, 2024 |
| Dell          | Latitude 5480               | Notebook    | [995ea90b66](https://linux-hardware.org/?probe=995ea90b66) | Apr 05, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [7ad5a4d115](https://linux-hardware.org/?probe=7ad5a4d115) | Mar 14, 2024 |
| Fujitsu       | FARQ10003                   | Notebook    | [c65688098c](https://linux-hardware.org/?probe=c65688098c) | Mar 13, 2024 |
| Lenovo        | IdeaPad Y460                | Notebook    | [0af494c148](https://linux-hardware.org/?probe=0af494c148) | Mar 10, 2024 |
| Lenovo        | G560 20042                  | Notebook    | [d7fffe52e5](https://linux-hardware.org/?probe=d7fffe52e5) | Mar 05, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [740b57ea8c](https://linux-hardware.org/?probe=740b57ea8c) | Mar 03, 2024 |
| Sony          | VGN-TX690P                  | Notebook    | [2cb1120670](https://linux-hardware.org/?probe=2cb1120670) | Feb 20, 2024 |
| Dell          | Latitude E6500              | Notebook    | [58652601f6](https://linux-hardware.org/?probe=58652601f6) | Feb 17, 2024 |
| Dell          | Latitude E6500              | Notebook    | [1ffdcc3b16](https://linux-hardware.org/?probe=1ffdcc3b16) | Feb 17, 2024 |
| Lenovo        | S10-3                       | Notebook    | [e9d3156b70](https://linux-hardware.org/?probe=e9d3156b70) | Feb 09, 2024 |
| Apple         | MacBookPro1,2               | Notebook    | [5e40347a6e](https://linux-hardware.org/?probe=5e40347a6e) | Feb 01, 2024 |
| ASUSTek       | P5K                         | Desktop     | [2835d63be5](https://linux-hardware.org/?probe=2835d63be5) | Jan 31, 2024 |
| ASUSTek       | P5K                         | Desktop     | [5db8fad897](https://linux-hardware.org/?probe=5db8fad897) | Jan 31, 2024 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [d6436b1ea4](https://linux-hardware.org/?probe=d6436b1ea4) | Jan 29, 2024 |
| Unknown       | Alviso                      | Desktop     | [fe4096f520](https://linux-hardware.org/?probe=fe4096f520) | Dec 29, 2023 |
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
| antiX 21       | 36        | 31.86%  |
| antiX 22       | 28        | 24.78%  |
| antiX 23       | 14        | 12.39%  |
| antiX 19.2     | 8         | 7.08%   |
| antiX 23.1     | 5         | 4.42%   |
| antiX 19.3     | 5         | 4.42%   |
| antiX 17.4.1   | 4         | 3.54%   |
| antiX 21-runit | 3         | 2.65%   |
| antiX 19.4     | 3         | 2.65%   |
| antiX 19.1     | 2         | 1.77%   |
| antiX 19.5     | 1         | 0.88%   |
| antiX 17.2.1   | 1         | 0.88%   |
| antiX 17.1     | 1         | 0.88%   |
| antiX 17       | 1         | 0.88%   |
| antiX 15       | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 112       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 16        | 14.16%  |
| 5.10.142-antix.2-amd64-smp   | 13        | 11.5%   |
| 4.9.0-279-antix.1-amd64-smp  | 11        | 9.73%   |
| 4.9.0-326-antix.1-amd64-smp  | 10        | 8.85%   |
| 5.10.57-antix.1-amd64-smp    | 8         | 7.08%   |
| 5.10.188-antix.1-amd64-smp   | 5         | 4.42%   |
| 5.10.188-antix.1-486-smp     | 5         | 4.42%   |
| 4.9.0-326-antix.1-486-smp    | 5         | 4.42%   |
| 6.1.60-antix.1-amd64-smp     | 4         | 3.54%   |
| 4.9.235-antix.1-amd64-smp    | 4         | 3.54%   |
| 4.9.160-antix.2-486-smp      | 4         | 3.54%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 2.65%   |
| 4.9.212-antix.1-486-smp      | 3         | 2.65%   |
| 6.1.55-antix.1-amd64-smp     | 2         | 1.77%   |
| 6.1.42-antix.1-amd64-smp     | 2         | 1.77%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 1.77%   |
| 4.9.200-antix.1-486-smp      | 2         | 1.77%   |
| 6.2.9-1-liquorix-amd64       | 1         | 0.88%   |
| 6.1.0-0.deb11.9-rt-amd64     | 1         | 0.88%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 0.88%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 0.88%   |
| 5.10.197-antix.1-486-smp     | 1         | 0.88%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 0.88%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 0.88%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 0.88%   |
| 4.9.0-264-antix.1-amd64-smp  | 1         | 0.88%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 0.88%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 0.88%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 0.88%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 0.88%   |
| 4.10.5-antix.1-486-smp       | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 44        | 39.29%  |
| 5.10.142 | 13        | 11.61%  |
| 5.10.188 | 10        | 8.93%   |
| 5.10.57  | 8         | 7.14%   |
| 4.9.212  | 6         | 5.36%   |
| 4.9.160  | 5         | 4.46%   |
| 6.1.60   | 4         | 3.57%   |
| 4.9.235  | 4         | 3.57%   |
| 6.1.55   | 2         | 1.79%   |
| 6.1.42   | 2         | 1.79%   |
| 5.10.88  | 2         | 1.79%   |
| 4.9.200  | 2         | 1.79%   |
| 6.2.9    | 1         | 0.89%   |
| 6.1.0    | 1         | 0.89%   |
| 5.14.0   | 1         | 0.89%   |
| 5.10.27  | 1         | 0.89%   |
| 5.10.197 | 1         | 0.89%   |
| 4.9.87   | 1         | 0.89%   |
| 4.19.202 | 1         | 0.89%   |
| 4.19.100 | 1         | 0.89%   |
| 4.19.0   | 1         | 0.89%   |
| 4.10.5   | 1         | 0.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 62        | 55.36%  |
| 5.10    | 35        | 31.25%  |
| 6.1     | 9         | 8.04%   |
| 4.19    | 3         | 2.68%   |
| 6.2     | 1         | 0.89%   |
| 5.14    | 1         | 0.89%   |
| 4.10    | 1         | 0.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 72        | 64.29%  |
| i686   | 39        | 34.82%  |
| i586   | 1         | 0.89%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| icewm        | 56        | 49.56%  |
| Unknown      | 40        | 35.4%   |
| XFCE         | 5         | 4.42%   |
| fluxbox      | 4         | 3.54%   |
| jwm          | 3         | 2.65%   |
| GNOME        | 2         | 1.77%   |
| LXQt         | 1         | 0.88%   |
| herbstluftwm | 1         | 0.88%   |
| Cinnamon     | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 109       | 97.32%  |
| Tty     | 2         | 1.79%   |
| Unknown | 1         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 47.32%  |
| SLIMSKI | 26        | 23.21%  |
| SLiM    | 23        | 20.54%  |
| LightDM | 7         | 6.25%   |
| XDM     | 1         | 0.89%   |
| SDDM    | 1         | 0.89%   |
| LXDM    | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 37.5%   |
| ru_RU   | 10        | 8.93%   |
| de_DE   | 9         | 8.04%   |
| pt_BR   | 5         | 4.46%   |
| it_IT   | 5         | 4.46%   |
| en_GB   | 5         | 4.46%   |
| ja_JP   | 4         | 3.57%   |
| es_ES   | 4         | 3.57%   |
| pl_PL   | 3         | 2.68%   |
| fr_FR   | 3         | 2.68%   |
| Unknown | 3         | 2.68%   |
| sk_SK   | 2         | 1.79%   |
| nl_NL   | 2         | 1.79%   |
| es_AR   | 2         | 1.79%   |
| en_AU   | 2         | 1.79%   |
| zh_HK   | 1         | 0.89%   |
| uk_UA   | 1         | 0.89%   |
| tr_TR   | 1         | 0.89%   |
| hu_HU   | 1         | 0.89%   |
| fr_BE   | 1         | 0.89%   |
| es_VE   | 1         | 0.89%   |
| es_PE   | 1         | 0.89%   |
| es_MX   | 1         | 0.89%   |
| en_NZ   | 1         | 0.89%   |
| de_AT   | 1         | 0.89%   |
| da_DK   | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 88        | 78.57%  |
| EFI  | 24        | 21.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 98        | 87.5%   |
| Overlay  | 11        | 9.82%   |
| Xfs      | 1         | 0.89%   |
| Reiserfs | 1         | 0.89%   |
| Ext2     | 1         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 79        | 70.54%  |
| GPT     | 31        | 27.68%  |
| Unknown | 2         | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 78.76%  |
| Yes       | 24        | 21.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 63.39%  |
| Yes       | 41        | 36.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 14        | 12.5%   |
| Lenovo              | 13        | 11.61%  |
| Hewlett-Packard     | 13        | 11.61%  |
| Acer                | 9         | 8.04%   |
| Dell                | 8         | 7.14%   |
| MSI                 | 5         | 4.46%   |
| Intel               | 5         | 4.46%   |
| IBM                 | 5         | 4.46%   |
| Gigabyte Technology | 5         | 4.46%   |
| Unknown             | 5         | 4.46%   |
| Fujitsu             | 4         | 3.57%   |
| Apple               | 4         | 3.57%   |
| Toshiba             | 3         | 2.68%   |
| Pegatron            | 2         | 1.79%   |
| KOHJINSHA           | 2         | 1.79%   |
| Google              | 2         | 1.79%   |
| VXL                 | 1         | 0.89%   |
| Sony                | 1         | 0.89%   |
| Samsung Electronics | 1         | 0.89%   |
| Radiant Systems     | 1         | 0.89%   |
| Prestigio           | 1         | 0.89%   |
| Packard Bell        | 1         | 0.89%   |
| Medion              | 1         | 0.89%   |
| Compaq              | 1         | 0.89%   |
| Clevo               | 1         | 0.89%   |
| Biostar             | 1         | 0.89%   |
| AZW                 | 1         | 0.89%   |
| ASRock              | 1         | 0.89%   |
| AMI                 | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 6         | 5.36%   |
| MSI US Desktop                     | 2         | 1.79%   |
| IBM 260921H                        | 2         | 1.79%   |
| HP Mini 110-3700                   | 2         | 1.79%   |
| Fujitsu FMVNU6G1C                  | 2         | 1.79%   |
| Dell Latitude 5480                 | 2         | 1.79%   |
| VXL TC7520d                        | 1         | 0.89%   |
| Toshiba Satellite T110             | 1         | 0.89%   |
| Toshiba Satellite C50-A-1HF        | 1         | 0.89%   |
| Toshiba Satellite 1905             | 1         | 0.89%   |
| Sony VGN-TX690P                    | 1         | 0.89%   |
| Samsung SQ1S                       | 1         | 0.89%   |
| Radiant Systems P845               | 1         | 0.89%   |
| Prestigio Smartbook PSB116A        | 1         | 0.89%   |
| Pegatron VC902AA-ABF p6136fr       | 1         | 0.89%   |
| Pegatron AU930AA-ACJ p6270in       | 1         | 0.89%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 0.89%   |
| MSI MS-7C56                        | 1         | 0.89%   |
| MSI MS-7B17                        | 1         | 0.89%   |
| MSI GE62 7RE                       | 1         | 0.89%   |
| Medion WIM2170                     | 1         | 0.89%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 0.89%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 0.89%   |
| Lenovo ThinkPad SL500 27463ZG      | 1         | 0.89%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 0.89%   |
| Lenovo S10-3                       | 1         | 0.89%   |
| Lenovo IdeaPad Y460                | 1         | 0.89%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 0.89%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 0.89%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 0.89%   |
| Lenovo G560 20042                  | 1         | 0.89%   |
| Lenovo G550 2958                   | 1         | 0.89%   |
| Lenovo 3000 V100 076346G           | 1         | 0.89%   |
| KOHJINSHA SX series                | 1         | 0.89%   |
| KOHJINSHA SC series                | 1         | 0.89%   |
| Intel powered classmate PC         | 1         | 0.89%   |
| Intel H61                          | 1         | 0.89%   |
| Intel DG41TY AAE47335-202          | 1         | 0.89%   |
| Intel D525MW AAE93082-401          | 1         | 0.89%   |
| Intel D425KT AAE93083-400          | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 6.25%   |
| Unknown               | 6         | 5.36%   |
| Dell Latitude         | 5         | 4.46%   |
| Lenovo IdeaPad        | 4         | 3.57%   |
| Toshiba Satellite     | 3         | 2.68%   |
| Lenovo ThinkPad       | 3         | 2.68%   |
| IBM ThinkPad          | 3         | 2.68%   |
| HP Mini               | 3         | 2.68%   |
| MSI US                | 2         | 1.79%   |
| IBM 260921H           | 2         | 1.79%   |
| HP EliteBook          | 2         | 1.79%   |
| Fujitsu FMVNU6G1C     | 2         | 1.79%   |
| Dell OptiPlex         | 2         | 1.79%   |
| ASUS VivoBook         | 2         | 1.79%   |
| ASUS PRIME            | 2         | 1.79%   |
| VXL TC7520d           | 1         | 0.89%   |
| Sony VGN-TX690P       | 1         | 0.89%   |
| Samsung SQ1S          | 1         | 0.89%   |
| Radiant Systems P845  | 1         | 0.89%   |
| Prestigio Smartbook   | 1         | 0.89%   |
| Pegatron VC902AA-ABF  | 1         | 0.89%   |
| Pegatron AU930AA-ACJ  | 1         | 0.89%   |
| Packard Bell EasyNote | 1         | 0.89%   |
| MSI MS-7C56           | 1         | 0.89%   |
| MSI MS-7B17           | 1         | 0.89%   |
| MSI GE62              | 1         | 0.89%   |
| Medion WIM2170        | 1         | 0.89%   |
| Lenovo ThinkCentre    | 1         | 0.89%   |
| Lenovo S10-3          | 1         | 0.89%   |
| Lenovo G560           | 1         | 0.89%   |
| Lenovo G550           | 1         | 0.89%   |
| Lenovo 3000           | 1         | 0.89%   |
| KOHJINSHA SX          | 1         | 0.89%   |
| KOHJINSHA SC          | 1         | 0.89%   |
| Intel powered         | 1         | 0.89%   |
| Intel H61             | 1         | 0.89%   |
| Intel DG41TY          | 1         | 0.89%   |
| Intel D525MW          | 1         | 0.89%   |
| Intel D425KT          | 1         | 0.89%   |
| HP t5740              | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 16        | 14.29%  |
| 2008    | 15        | 13.39%  |
| 2007    | 14        | 12.5%   |
| 2010    | 8         | 7.14%   |
| 2012    | 6         | 5.36%   |
| 2011    | 6         | 5.36%   |
| 2014    | 5         | 4.46%   |
| 2013    | 5         | 4.46%   |
| 2018    | 4         | 3.57%   |
| 2017    | 4         | 3.57%   |
| 2005    | 4         | 3.57%   |
| 2021    | 3         | 2.68%   |
| 2020    | 3         | 2.68%   |
| 2006    | 3         | 2.68%   |
| 2004    | 3         | 2.68%   |
| 2003    | 3         | 2.68%   |
| 2022    | 2         | 1.79%   |
| 2019    | 2         | 1.79%   |
| 2016    | 2         | 1.79%   |
| 1999    | 2         | 1.79%   |
| 2023    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 76        | 67.86%  |
| Desktop    | 31        | 27.68%  |
| Mini pc    | 4         | 3.57%   |
| All in one | 1         | 0.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 110       | 98.21%  |
| Yes  | 2         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 32        | 28.57%  |
| 1.01-2.0    | 24        | 21.43%  |
| 0.51-1.0    | 14        | 12.5%   |
| 2.01-3.0    | 12        | 10.71%  |
| 4.01-8.0    | 7         | 6.25%   |
| 32.01-64.0  | 6         | 5.36%   |
| 8.01-16.0   | 6         | 5.36%   |
| 0.01-0.5    | 6         | 5.36%   |
| 16.01-24.0  | 3         | 2.68%   |
| 64.01-256.0 | 2         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 39        | 34.21%  |
| 0.01-0.5   | 35        | 30.7%   |
| 1.01-2.0   | 28        | 24.56%  |
| 2.01-3.0   | 9         | 7.89%   |
| 4.01-8.0   | 2         | 1.75%   |
| 32.01-64.0 | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 81        | 71.68%  |
| 2      | 18        | 15.93%  |
| 3      | 6         | 5.31%   |
| 0      | 4         | 3.54%   |
| 4      | 3         | 2.65%   |
| 5      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 53.57%  |
| Yes       | 52        | 46.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 86.61%  |
| No        | 15        | 13.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 75.89%  |
| No        | 27        | 24.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 61.06%  |
| Yes       | 44        | 38.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 15.18%  |
| Russia       | 12        | 10.71%  |
| Germany      | 11        | 9.82%   |
| Hong Kong    | 10        | 8.93%   |
| Poland       | 6         | 5.36%   |
| Italy        | 6         | 5.36%   |
| Japan        | 5         | 4.46%   |
| Brazil       | 5         | 4.46%   |
| France       | 4         | 3.57%   |
| UK           | 3         | 2.68%   |
| Spain        | 3         | 2.68%   |
| Netherlands  | 3         | 2.68%   |
| Slovakia     | 2         | 1.79%   |
| Hungary      | 2         | 1.79%   |
| Denmark      | 2         | 1.79%   |
| Australia    | 2         | 1.79%   |
| Argentina    | 2         | 1.79%   |
| Uruguay      | 1         | 0.89%   |
| Ukraine      | 1         | 0.89%   |
| South Africa | 1         | 0.89%   |
| Peru         | 1         | 0.89%   |
| New Zealand  | 1         | 0.89%   |
| Mexico       | 1         | 0.89%   |
| Kenya        | 1         | 0.89%   |
| Kazakhstan   | 1         | 0.89%   |
| Indonesia    | 1         | 0.89%   |
| India        | 1         | 0.89%   |
| Greece       | 1         | 0.89%   |
| Czechia      | 1         | 0.89%   |
| Chile        | 1         | 0.89%   |
| Bulgaria     | 1         | 0.89%   |
| Belgium      | 1         | 0.89%   |
| Austria      | 1         | 0.89%   |
| Algeria      | 1         | 0.89%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 6.09%   |
| Sydney                    | 2         | 1.74%   |
| St Petersburg             | 2         | 1.74%   |
| Moscow                    | 2         | 1.74%   |
| Milan                     | 2         | 1.74%   |
| Central                   | 2         | 1.74%   |
| Bratislava                | 2         | 1.74%   |
| Zagnansk                  | 1         | 0.87%   |
| Yuzhno-Sakhalinsk         | 1         | 0.87%   |
| Yokohama                  | 1         | 0.87%   |
| Ybbs an der Donau         | 1         | 0.87%   |
| Whitney                   | 1         | 0.87%   |
| Warsaw                    | 1         | 0.87%   |
| Violes                    | 1         | 0.87%   |
| Varna                     | 1         | 0.87%   |
| Tver                      | 1         | 0.87%   |
| Trecate                   | 1         | 0.87%   |
| Torricella Sicura         | 1         | 0.87%   |
| Toms River                | 1         | 0.87%   |
| Tokyo                     | 1         | 0.87%   |
| Templeton                 | 1         | 0.87%   |
| St Albans                 | 1         | 0.87%   |
| Sofia                     | 1         | 0.87%   |
| Sheung Shui               | 1         | 0.87%   |
| Seattle                   | 1         | 0.87%   |
| Schloss Holte-Stukenbrock | 1         | 0.87%   |
| Santiago                  | 1         | 0.87%   |
| Salto                     | 1         | 0.87%   |
| Rotterdam                 | 1         | 0.87%   |
| Romilly-sur-Seine         | 1         | 0.87%   |
| Reutlingen                | 1         | 0.87%   |
| Purmerend                 | 1         | 0.87%   |
| Pritzwalk                 | 1         | 0.87%   |
| Prague                    | 1         | 0.87%   |
| Portland                  | 1         | 0.87%   |
| Pomaz                     | 1         | 0.87%   |
| Padova                    | 1         | 0.87%   |
| Otwock                    | 1         | 0.87%   |
| Oran                      | 1         | 0.87%   |
| Nova Londrina             | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 26        | 29     | 19.26%  |
| Seagate                   | 22        | 22     | 16.3%   |
| Hitachi                   | 16        | 18     | 11.85%  |
| Samsung Electronics       | 14        | 16     | 10.37%  |
| Toshiba                   | 13        | 14     | 9.63%   |
| Unknown                   | 6         | 6      | 4.44%   |
| Kingston                  | 4         | 5      | 2.96%   |
| SanDisk                   | 3         | 3      | 2.22%   |
| Maxtor                    | 3         | 3      | 2.22%   |
| BHT                       | 3         | 5      | 2.22%   |
| Micron/Crucial Technology | 2         | 2      | 1.48%   |
| Intel                     | 2         | 2      | 1.48%   |
| HGST                      | 2         | 2      | 1.48%   |
| Unknown                   | 2         | 2      | 1.48%   |
| Zheino                    | 1         | 1      | 0.74%   |
| Unknown (CF)              | 1         | 1      | 0.74%   |
| Transcend                 | 1         | 1      | 0.74%   |
| RECADATA                  | 1         | 1      | 0.74%   |
| PNY                       | 1         | 2      | 0.74%   |
| OCZ                       | 1         | 1      | 0.74%   |
| NVMe                      | 1         | 1      | 0.74%   |
| KIOXIA                    | 1         | 1      | 0.74%   |
| IBM/Hitachi               | 1         | 1      | 0.74%   |
| Hewlett-Packard           | 1         | 1      | 0.74%   |
| Fujitsu                   | 1         | 1      | 0.74%   |
| Crucial                   | 1         | 1      | 0.74%   |
| China                     | 1         | 1      | 0.74%   |
| BIWIN                     | 1         | 1      | 0.74%   |
| ASUS-PHISON               | 1         | 1      | 0.74%   |
| Apple                     | 1         | 1      | 0.74%   |
| Apacer                    | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| WDC WD800AAJS-75M0A0 80GB         | 2         | 1.45%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 2         | 1.45%   |
| WDC WD10SPZX-80Z10T2 1TB          | 2         | 1.45%   |
| Toshiba MQ01ABD100 1TB            | 2         | 1.45%   |
| Toshiba MQ01ABD050V -63 500GB     | 2         | 1.45%   |
| Seagate ST980811AS 80GB           | 2         | 1.45%   |
| Seagate ST9320325AS 320GB         | 2         | 1.45%   |
| Samsung SSD 850 EVO 120GB         | 2         | 1.45%   |
| Samsung SSD 750 EVO 120GB         | 2         | 1.45%   |
| Maxtor Z1 SSD 240GB               | 2         | 1.45%   |
| Kingston SA400S37240G 240GB SSD   | 2         | 1.45%   |
| Hitachi HTS723232A7A364 320GB     | 2         | 1.45%   |
| Hitachi HTS548040M9AT00 40GB      | 2         | 1.45%   |
| Hitachi HTS545025B9A300 250GB     | 2         | 1.45%   |
| Hitachi HTS542525K9SA00 250GB     | 2         | 1.45%   |
| BHT WR202F0032G 670270F5 32GB SSD | 2         | 1.45%   |
| Unknown                           | 2         | 1.45%   |
| Zheino CHN-mSATAM3-128 128GB SSD  | 1         | 0.72%   |
| WDC WD8088AADS-00M2B0 809GB       | 1         | 0.72%   |
| WDC WD800JB-00ETA0 80GB           | 1         | 0.72%   |
| WDC WD800BEVT-75ZCT2 80GB         | 1         | 0.72%   |
| WDC WD5000LPLX-08ZNTT0 500GB      | 1         | 0.72%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 0.72%   |
| WDC WD5000BEVT-24A0RT0 500GB      | 1         | 0.72%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 0.72%   |
| WDC WD5000AVDS-63U7B1 500GB       | 1         | 0.72%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 0.72%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 0.72%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 0.72%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 0.72%   |
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 0.72%   |
| WDC WD205BA 21GB                  | 1         | 0.72%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1         | 0.72%   |
| WDC WD1600BEVT-60ZCT1 160GB       | 1         | 0.72%   |
| WDC WD1600BEVT-00M9YT0 160GB      | 1         | 0.72%   |
| WDC WD1600BEVS-22RST0 160GB       | 1         | 0.72%   |
| WDC WD1600AAJS-00PSA0 160GB       | 1         | 0.72%   |
| WDC WD1200BEVE-00A0HT0 120GB      | 1         | 0.72%   |
| WDC WD10EADS-65M2B0 1TB           | 1         | 0.72%   |
| WDC WD1005FBYZ-01YCBB3 1TB        | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 29     | 29.21%  |
| Seagate             | 22        | 22     | 24.72%  |
| Hitachi             | 16        | 18     | 17.98%  |
| Toshiba             | 11        | 12     | 12.36%  |
| Samsung Electronics | 6         | 7      | 6.74%   |
| Unknown             | 2         | 2      | 2.25%   |
| HGST                | 2         | 2      | 2.25%   |
| Unknown (CF)        | 1         | 1      | 1.12%   |
| Maxtor              | 1         | 1      | 1.12%   |
| IBM/Hitachi         | 1         | 1      | 1.12%   |
| Fujitsu             | 1         | 1      | 1.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 17.65%  |
| Kingston            | 4         | 5      | 11.76%  |
| BHT                 | 3         | 5      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Maxtor              | 2         | 2      | 5.88%   |
| Unknown             | 2         | 2      | 5.88%   |
| Zheino              | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| RECADATA            | 1         | 1      | 2.94%   |
| PNY                 | 1         | 2      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| BIWIN               | 1         | 1      | 2.94%   |
| ASUS-PHISON         | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |
| Apacer              | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 80        | 96     | 64.52%  |
| SSD  | 33        | 38     | 26.61%  |
| NVMe | 6         | 8      | 4.84%   |
| MMC  | 5         | 5      | 4.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 132    | 88.7%   |
| NVMe | 6         | 8      | 5.22%   |
| MMC  | 5         | 5      | 4.35%   |
| SAS  | 2         | 2      | 1.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 115    | 85.71%  |
| 0.51-1.0   | 14        | 16     | 12.5%   |
| 1.01-2.0   | 1         | 1      | 0.89%   |
| 4.01-10.0  | 1         | 2      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 29.82%  |
| 1-20           | 23        | 20.18%  |
| 51-100         | 18        | 15.79%  |
| 251-500        | 14        | 12.28%  |
| 21-50          | 14        | 12.28%  |
| 501-1000       | 7         | 6.14%   |
| More than 3000 | 2         | 1.75%   |
| 1001-2000      | 2         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 76.79%  |
| 21-50          | 9         | 8.04%   |
| 101-250        | 9         | 8.04%   |
| 51-100         | 4         | 3.57%   |
| More than 3000 | 2         | 1.79%   |
| 501-1000       | 2         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2         | 2      | 4.26%   |
| Seagate ST980811AS 80GB                     | 2         | 2      | 4.26%   |
| Seagate ST9320325AS 320GB                   | 2         | 2      | 4.26%   |
| Hitachi HTS542525K9SA00 250GB               | 2         | 2      | 4.26%   |
| WDC WD800JB-00ETA0 80GB                     | 1         | 1      | 2.13%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 2.13%   |
| WDC WD5000BEVT-24A0RT0 500GB                | 1         | 1      | 2.13%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 1      | 2.13%   |
| WDC WD3200BPVT-24ZEST0 320GB                | 1         | 1      | 2.13%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 1         | 1      | 2.13%   |
| WDC WD2500BEVT-22ZCT0 250GB                 | 1         | 1      | 2.13%   |
| WDC WD205BA 21GB                            | 1         | 1      | 2.13%   |
| WDC WD1600BEVT-00M9YT0 160GB                | 1         | 2      | 2.13%   |
| WDC WD10EADS-65M2B0 1TB                     | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.13%   |
| Toshiba MK6006GAH 64GB                      | 1         | 1      | 2.13%   |
| Toshiba MK2555GSX 250GB                     | 1         | 1      | 2.13%   |
| Seagate ST980812AS 80GB                     | 1         | 1      | 2.13%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 2.13%   |
| Seagate ST9160827AS 160GB                   | 1         | 1      | 2.13%   |
| Seagate ST9160314AS 160GB                   | 1         | 1      | 2.13%   |
| Seagate ST9160310AS 160GB                   | 1         | 1      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.13%   |
| Seagate ST3500312CS 500GB                   | 1         | 1      | 2.13%   |
| Seagate ST3320620AS 320GB                   | 1         | 1      | 2.13%   |
| Seagate ST3320413CS 320GB                   | 1         | 1      | 2.13%   |
| Seagate ST320LT007-9ZV142 320GB             | 1         | 1      | 2.13%   |
| SanDisk sandisk120 120GB SSD                | 1         | 1      | 2.13%   |
| Samsung Electronics HM161GI 160GB           | 1         | 1      | 2.13%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1         | 1      | 2.13%   |
| Maxtor 2F040L0 41GB                         | 1         | 1      | 2.13%   |
| Hitachi HTS725050A7E630 500GB               | 1         | 1      | 2.13%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 2.13%   |
| Hitachi HTS721060G9AT00 64GB                | 1         | 1      | 2.13%   |
| Hitachi HTS548040M9AT00 40GB                | 1         | 1      | 2.13%   |
| Hitachi HTS543225A7A384 250GB               | 1         | 1      | 2.13%   |
| Hitachi HTS541612J9SA00 120GB               | 1         | 1      | 2.13%   |
| Hitachi HTC426040G8CE00 40GB                | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 14        | 14     | 29.79%  |
| WDC                       | 13        | 14     | 27.66%  |
| Hitachi                   | 9         | 9      | 19.15%  |
| Toshiba                   | 3         | 3      | 6.38%   |
| SanDisk                   | 1         | 1      | 2.13%   |
| Samsung Electronics       | 1         | 1      | 2.13%   |
| Micron/Crucial Technology | 1         | 1      | 2.13%   |
| Maxtor                    | 1         | 1      | 2.13%   |
| HGST                      | 1         | 1      | 2.13%   |
| China                     | 1         | 1      | 2.13%   |
| BIWIN                     | 1         | 1      | 2.13%   |
| Apacer                    | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 33.33%  |
| WDC                 | 13        | 14     | 30.95%  |
| Hitachi             | 9         | 9      | 21.43%  |
| Toshiba             | 3         | 3      | 7.14%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| Maxtor              | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 43     | 89.36%  |
| SSD  | 4         | 4      | 8.51%   |
| NVMe | 1         | 1      | 2.13%   |

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
| Works    | 59        | 83     | 49.17%  |
| Malfunc  | 47        | 48     | 39.17%  |
| Detected | 14        | 16     | 11.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 86        | 69.92%  |
| AMD                              | 11        | 8.94%   |
| Nvidia                           | 5         | 4.07%   |
| ASMedia Technology               | 4         | 3.25%   |
| VIA Technologies                 | 3         | 2.44%   |
| Silicon Integrated Systems [SiS] | 2         | 1.63%   |
| Samsung Electronics              | 2         | 1.63%   |
| Micron/Crucial Technology        | 2         | 1.63%   |
| JMicron Technology               | 2         | 1.63%   |
| ULi Electronics                  | 1         | 0.81%   |
| Silicon Image                    | 1         | 0.81%   |
| Marvell Technology Group         | 1         | 0.81%   |
| LSI Logic / Symbios Logic        | 1         | 0.81%   |
| KIOXIA                           | 1         | 0.81%   |
| ADATA Technology                 | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13        | 8.44%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 5.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 3.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 3.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 3.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 5         | 3.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 2.6%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 2.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.95%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.95%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.95%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.95%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.3%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.3%    |
| VIA VX900 Series Serial-ATA Controller                                         | 1         | 0.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.65%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 0.65%   |
| ULi ULi M5288 SATA                                                             | 1         | 0.65%   |
| ULi M5229 IDE                                                                  | 1         | 0.65%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.65%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 0.65%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.65%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 0.65%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 62        | 47.69%  |
| IDE  | 56        | 43.08%  |
| NVMe | 6         | 4.62%   |
| RAID | 5         | 3.85%   |
| SAS  | 1         | 0.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 94        | 83.93%  |
| AMD          | 15        | 13.39%  |
| CentaurHauls | 2         | 1.79%   |
| GenuineTMx86 | 1         | 0.89%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 5.36%   |
| Intel Pentium M processor 1.60GHz           | 2         | 1.79%   |
| Intel Pentium M processor 1.00GHz           | 2         | 1.79%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2         | 1.79%   |
| Intel Genuine processor 800MHz              | 2         | 1.79%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 1.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.79%   |
| Intel Celeron (Mendocino)                   | 2         | 1.79%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 1.79%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.79%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 1.79%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 1.79%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 1.79%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 1.79%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 0.89%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.89%   |
| Intel Pentium M processor 1600MHz           | 1         | 0.89%   |
| Intel Pentium M processor 1.86GHz           | 1         | 0.89%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.89%   |
| Intel Pentium M processor 1.20GHz           | 1         | 0.89%   |
| Intel Pentium II (Deschutes)                | 1         | 0.89%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.89%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.89%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.89%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.89%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1         | 0.89%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 0.89%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 0.89%   |
| Intel Genuine CPU T2600 @ 2.16GHz           | 1         | 0.89%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 0.89%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.89%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.89%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.89%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 0.89%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.89%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 19        | 16.96%  |
| Intel Core 2 Duo        | 13        | 11.61%  |
| Intel Celeron           | 10        | 8.93%   |
| Intel Pentium M         | 8         | 7.14%   |
| Intel Core i5           | 7         | 6.25%   |
| Intel Genuine           | 6         | 5.36%   |
| Intel Core i7           | 6         | 5.36%   |
| Intel Core i3           | 6         | 5.36%   |
| Other                   | 5         | 4.46%   |
| Intel Pentium Dual-Core | 4         | 3.57%   |
| Intel Pentium Dual      | 2         | 1.79%   |
| Intel Pentium 4         | 2         | 1.79%   |
| AMD Ryzen 7             | 2         | 1.79%   |
| AMD E2                  | 2         | 1.79%   |
| AMD Athlon 64 X2        | 2         | 1.79%   |
| Intel Xeon              | 1         | 0.89%   |
| Intel Pentium Silver    | 1         | 0.89%   |
| Intel Pentium           | 1         | 0.89%   |
| Intel Core i9           | 1         | 0.89%   |
| Intel Core 2 Quad       | 1         | 0.89%   |
| Intel Core 2            | 1         | 0.89%   |
| Intel Celeron M         | 1         | 0.89%   |
| Intel Celeron Dual-Core | 1         | 0.89%   |
| CentaurHauls VIA Nano   | 1         | 0.89%   |
| CentaurHauls VIA Eden   | 1         | 0.89%   |
| AMD Sempron             | 1         | 0.89%   |
| AMD Ryzen 5             | 1         | 0.89%   |
| AMD Phenom II X4        | 1         | 0.89%   |
| AMD Phenom              | 1         | 0.89%   |
| AMD E1                  | 1         | 0.89%   |
| AMD Athlon II           | 1         | 0.89%   |
| AMD Athlon 64           | 1         | 0.89%   |
| AMD A6                  | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 49.11%  |
| 1      | 37        | 33.04%  |
| 4      | 13        | 11.61%  |
| 8      | 3         | 2.68%   |
| 6      | 3         | 2.68%   |
| 24     | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 68        | 60.71%  |
| 2      | 44        | 39.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 72.32%  |
| 32-bit         | 31        | 27.68%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 13        | 11.61%  |
| Unknown    | 11        | 9.82%   |
| 0x106c2    | 10        | 8.93%   |
| 0x6fd      | 6         | 5.36%   |
| 0x6d8      | 6         | 5.36%   |
| 0x106ca    | 5         | 4.46%   |
| 0x6d6      | 4         | 3.57%   |
| 0x30678    | 4         | 3.57%   |
| 0x206a7    | 4         | 3.57%   |
| 0x10676    | 4         | 3.57%   |
| 0x6e8      | 3         | 2.68%   |
| 0x40651    | 3         | 2.68%   |
| 0x306a9    | 3         | 2.68%   |
| 0xa0671    | 2         | 1.79%   |
| 0x706a8    | 2         | 1.79%   |
| 0x66a      | 2         | 1.79%   |
| 0x306c3    | 2         | 1.79%   |
| 0x30661    | 2         | 1.79%   |
| 0x20655    | 2         | 1.79%   |
| 0x20652    | 2         | 1.79%   |
| 0x10661    | 2         | 1.79%   |
| 0x010000c8 | 2         | 1.79%   |
| 0xf29      | 1         | 0.89%   |
| 0xf24      | 1         | 0.89%   |
| 0x906ed    | 1         | 0.89%   |
| 0x906e9    | 1         | 0.89%   |
| 0x806e9    | 1         | 0.89%   |
| 0x706a1    | 1         | 0.89%   |
| 0x6f6      | 1         | 0.89%   |
| 0x695      | 1         | 0.89%   |
| 0x652      | 1         | 0.89%   |
| 0x506c9    | 1         | 0.89%   |
| 0x08701021 | 1         | 0.89%   |
| 0x08001138 | 1         | 0.89%   |
| 0x07030106 | 1         | 0.89%   |
| 0x0700010f | 1         | 0.89%   |
| 0x06006705 | 1         | 0.89%   |
| 0x06006704 | 1         | 0.89%   |
| 0x06001116 | 1         | 0.89%   |
| 0x01000095 | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Bonnell          | 18        | 16.07%  |
| Penryn           | 17        | 15.18%  |
| P6               | 14        | 12.5%   |
| Core             | 9         | 8.04%   |
| Unknown          | 8         | 7.14%   |
| Haswell          | 5         | 4.46%   |
| Westmere         | 4         | 3.57%   |
| Silvermont       | 4         | 3.57%   |
| SandyBridge      | 4         | 3.57%   |
| KabyLake         | 4         | 3.57%   |
| K8 Hammer        | 4         | 3.57%   |
| K10              | 3         | 2.68%   |
| IvyBridge        | 3         | 2.68%   |
| Goldmont plus    | 3         | 2.68%   |
| NetBurst         | 2         | 1.79%   |
| Excavator        | 2         | 1.79%   |
| Zen+             | 1         | 0.89%   |
| Zen 2            | 1         | 0.89%   |
| Zen              | 1         | 0.89%   |
| Puma             | 1         | 0.89%   |
| Piledriver       | 1         | 0.89%   |
| Jaguar           | 1         | 0.89%   |
| Goldmont         | 1         | 0.89%   |
| Alderlake Hybrid | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 58.47%  |
| Nvidia                           | 22        | 18.64%  |
| AMD                              | 22        | 18.64%  |
| VIA Technologies                 | 2         | 1.69%   |
| Neomagic                         | 2         | 1.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 12        | 8.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 8         | 5.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 7         | 5.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 6         | 4.41%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 5         | 3.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 4         | 2.94%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 3         | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.21%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 2.21%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 2.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.21%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 1.47%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 1.47%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.47%   |
| Intel HD Graphics 620                                                         | 2         | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.47%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 2         | 1.47%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.47%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 1.47%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                      | 2         | 1.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.47%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                  | 1         | 0.74%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 1         | 0.74%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 0.74%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.74%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 0.74%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.74%   |
| Nvidia GM204 [GeForce GTX 980]                                                | 1         | 0.74%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.74%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.74%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 50%     |
| 1 x Nvidia     | 17        | 15.18%  |
| 1 x AMD        | 17        | 15.18%  |
| 2 x Intel      | 5         | 4.46%   |
| Intel + Nvidia | 5         | 4.46%   |
| 2 x AMD        | 4         | 3.57%   |
| Other          | 2         | 1.79%   |
| 1 x VIA        | 2         | 1.79%   |
| 1 x Neomagic   | 2         | 1.79%   |
| 1 x SiS        | 1         | 0.89%   |
| Intel + AMD    | 1         | 0.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 91        | 81.25%  |
| Unknown     | 13        | 11.61%  |
| Proprietary | 8         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 44.64%  |
| 0.01-0.5   | 40        | 35.71%  |
| 1.01-2.0   | 14        | 12.5%   |
| 0.51-1.0   | 3         | 2.68%   |
| 5.01-6.0   | 2         | 1.79%   |
| 3.01-4.0   | 2         | 1.79%   |
| 16.01-24.0 | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 17.07%  |
| Samsung Electronics     | 11        | 13.41%  |
| LG Display              | 11        | 13.41%  |
| Chimei Innolux          | 5         | 6.1%    |
| LG Philips              | 4         | 4.88%   |
| Lenovo                  | 4         | 4.88%   |
| Goldstar                | 4         | 4.88%   |
| Apple                   | 4         | 4.88%   |
| Acer                    | 4         | 4.88%   |
| HannStar                | 3         | 3.66%   |
| Hewlett-Packard         | 2         | 2.44%   |
| BOE                     | 2         | 2.44%   |
| Ancor Communications    | 2         | 2.44%   |
| Vizio                   | 1         | 1.22%   |
| ViewSonic               | 1         | 1.22%   |
| Unknown (XXX)           | 1         | 1.22%   |
| LG Electronics          | 1         | 1.22%   |
| InfoVision              | 1         | 1.22%   |
| HJW                     | 1         | 1.22%   |
| Dell                    | 1         | 1.22%   |
| CPT                     | 1         | 1.22%   |
| Chi Mei Optoelectronics | 1         | 1.22%   |
| Arnos Instruments       | 1         | 1.22%   |
| AOC                     | 1         | 1.22%   |
| Unknown                 | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 2         | 2.44%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1         | 1.22%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1         | 1.22%   |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch              | 1         | 1.22%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 474x296mm 22.0-inch  | 1         | 1.22%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1         | 1.22%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch   | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4346 1920x1200 331x207mm 15.4-inch | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch  | 1         | 1.22%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 1.22%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch           | 1         | 1.22%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 1         | 1.22%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.22%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                      | 1         | 1.22%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch         | 1         | 1.22%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch         | 1         | 1.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch              | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 1.22%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch               | 1         | 1.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.22%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch          | 1         | 1.22%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                 | 1         | 1.22%   |
| Hewlett-Packard LP2475w HWP26F7 1920x1200 546x352mm 25.6-inch         | 1         | 1.22%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch      | 1         | 1.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.22%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch             | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 25        | 30.86%  |
| 1920x1080 (FHD)    | 19        | 23.46%  |
| 1280x800 (WXGA)    | 9         | 11.11%  |
| 1024x600           | 7         | 8.64%   |
| 1440x900 (WXGA+)   | 5         | 6.17%   |
| 1920x1200 (WUXGA)  | 3         | 3.7%    |
| 1680x1050 (WSXGA+) | 2         | 2.47%   |
| 1600x1200          | 2         | 2.47%   |
| 1280x1024 (SXGA)   | 2         | 2.47%   |
| 4480x3600          | 1         | 1.23%   |
| 2560x1080          | 1         | 1.23%   |
| 2288x1287          | 1         | 1.23%   |
| 1600x900 (HD+)     | 1         | 1.23%   |
| 1360x768           | 1         | 1.23%   |
| 1280x720 (HD)      | 1         | 1.23%   |
| Unknown            | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 28.4%   |
| 21      | 7         | 8.64%   |
| 10      | 7         | 8.64%   |
| 14      | 6         | 7.41%   |
| 11      | 6         | 7.41%   |
| 17      | 5         | 6.17%   |
| 13      | 5         | 6.17%   |
| 27      | 3         | 3.7%    |
| 24      | 2         | 2.47%   |
| 23      | 2         | 2.47%   |
| 18      | 2         | 2.47%   |
| 12      | 2         | 2.47%   |
| 8       | 2         | 2.47%   |
| 43      | 1         | 1.23%   |
| 38      | 1         | 1.23%   |
| 34      | 1         | 1.23%   |
| 32      | 1         | 1.23%   |
| 31      | 1         | 1.23%   |
| 25      | 1         | 1.23%   |
| 22      | 1         | 1.23%   |
| 19      | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 39.51%  |
| 201-300     | 18        | 22.22%  |
| 401-500     | 10        | 12.35%  |
| 501-600     | 8         | 9.88%   |
| 351-400     | 5         | 6.17%   |
| 801-900     | 2         | 2.47%   |
| 701-800     | 2         | 2.47%   |
| 101-200     | 2         | 2.47%   |
| 601-700     | 1         | 1.23%   |
| Unknown     | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 65.82%  |
| 16/10   | 19        | 24.05%  |
| 4/3     | 4         | 5.06%   |
| 5/4     | 1         | 1.27%   |
| 3/2     | 1         | 1.27%   |
| 21/9    | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 27.16%  |
| 201-250        | 10        | 12.35%  |
| 81-90          | 9         | 11.11%  |
| 41-50          | 7         | 8.64%   |
| 51-60          | 6         | 7.41%   |
| 351-500        | 3         | 3.7%    |
| 301-350        | 3         | 3.7%    |
| 151-200        | 3         | 3.7%    |
| 141-150        | 3         | 3.7%    |
| 131-140        | 3         | 3.7%    |
| 71-80          | 2         | 2.47%   |
| 61-70          | 2         | 2.47%   |
| 1-40           | 2         | 2.47%   |
| 501-1000       | 2         | 2.47%   |
| 251-300        | 1         | 1.23%   |
| 121-130        | 1         | 1.23%   |
| 111-120        | 1         | 1.23%   |
| Unknown        | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 31        | 38.75%  |
| 51-100  | 25        | 31.25%  |
| 121-160 | 20        | 25%     |
| 1-50    | 3         | 3.75%   |
| Unknown | 1         | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 85.84%  |
| 0     | 12        | 10.62%  |
| 2     | 4         | 3.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 28.07%  |
| Intel                            | 42        | 24.56%  |
| Qualcomm Atheros                 | 30        | 17.54%  |
| Broadcom                         | 19        | 11.11%  |
| Nvidia                           | 5         | 2.92%   |
| Marvell Technology Group         | 5         | 2.92%   |
| Ralink                           | 3         | 1.75%   |
| Broadcom Limited                 | 3         | 1.75%   |
| Silicon Integrated Systems [SiS] | 2         | 1.17%   |
| Ralink Technology                | 2         | 1.17%   |
| Qualcomm Atheros Communications  | 2         | 1.17%   |
| Texas Instruments                | 1         | 0.58%   |
| Samsung Electronics              | 1         | 0.58%   |
| NetGear                          | 1         | 0.58%   |
| Motorola PCS                     | 1         | 0.58%   |
| MediaTek                         | 1         | 0.58%   |
| LSI                              | 1         | 0.58%   |
| Linksys                          | 1         | 0.58%   |
| Hewlett-Packard                  | 1         | 0.58%   |
| Attansic Technology              | 1         | 0.58%   |
| ASIX Electronics                 | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 16        | 7.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 7.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 5.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 3.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 4         | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.97%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 1.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 1.48%   |
| Intel WiFi Link 5100                                                    | 3         | 1.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.48%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.48%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.99%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.99%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.99%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 0.99%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.99%   |
| Intel Wireless 7260                                                     | 2         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.99%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.99%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 0.99%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.99%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 35.87%  |
| Qualcomm Atheros                | 26        | 28.26%  |
| Broadcom                        | 14        | 15.22%  |
| Realtek Semiconductor           | 7         | 7.61%   |
| Ralink                          | 3         | 3.26%   |
| Ralink Technology               | 2         | 2.17%   |
| Qualcomm Atheros Communications | 2         | 2.17%   |
| Texas Instruments               | 1         | 1.09%   |
| NetGear                         | 1         | 1.09%   |
| MediaTek                        | 1         | 1.09%   |
| Linksys                         | 1         | 1.09%   |
| Broadcom Limited                | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 11        | 11.83%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 5         | 5.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 4.3%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 4.3%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 4.3%    |
| Intel WiFi Link 5100                                                          | 3         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 3.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 3.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 2.15%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 2.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.15%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.15%   |
| Intel Wireless 7260                                                           | 2         | 2.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 2.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 2.15%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.15%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 2.15%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.08%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 1.08%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.08%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.08%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.08%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.08%   |
| NetGear A6150                                                                 | 1         | 1.08%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.08%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                             | 1         | 1.08%   |
| Intel Wireless 7265                                                           | 1         | 1.08%   |
| Intel Wireless 3165                                                           | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 46        | 45.1%   |
| Intel                            | 23        | 22.55%  |
| Broadcom                         | 8         | 7.84%   |
| Qualcomm Atheros                 | 7         | 6.86%   |
| Nvidia                           | 5         | 4.9%    |
| Marvell Technology Group         | 5         | 4.9%    |
| Silicon Integrated Systems [SiS] | 2         | 1.96%   |
| Broadcom Limited                 | 2         | 1.96%   |
| Samsung Electronics              | 1         | 0.98%   |
| Motorola PCS                     | 1         | 0.98%   |
| Attansic Technology              | 1         | 0.98%   |
| ASIX Electronics                 | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 15.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 14.56%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 7.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 4         | 3.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.91%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.94%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 1.94%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 1.94%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.94%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.94%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 2         | 1.94%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.94%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.97%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.97%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 0.97%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.97%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.97%   |
| Nvidia CK8S Ethernet Controller                                        | 1         | 0.97%   |
| Nvidia CK804 Ethernet Controller                                       | 1         | 0.97%   |
| Motorola PCS moto g(7) power                                           | 1         | 0.97%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.97%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.97%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1         | 0.97%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.97%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.97%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                     | 1         | 0.97%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                           | 1         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 0.97%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.97%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE Ethernet Controller                | 1         | 0.97%   |
| Intel 82562EM/EX/GX - PRO/100 VM (LOM) Ethernet Controller Mobile      | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 51.32%  |
| WiFi     | 85        | 44.97%  |
| Modem    | 7         | 3.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 63.48%  |
| Ethernet | 42        | 36.52%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 63.39%  |
| 1     | 40        | 35.71%  |
| 0     | 1         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 77.19%  |
| Yes  | 26        | 22.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 23.26%  |
| Broadcom                        | 10        | 23.26%  |
| Apple                           | 4         | 9.3%    |
| Cambridge Silicon Radio         | 3         | 6.98%   |
| Realtek Semiconductor           | 2         | 4.65%   |
| Qualcomm Atheros Communications | 2         | 4.65%   |
| Lite-On Technology              | 2         | 4.65%   |
| IMC Networks                    | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Taiyo Yuden                     | 1         | 2.33%   |
| Ralink Technology               | 1         | 2.33%   |
| Hewlett-Packard                 | 1         | 2.33%   |
| Fujitsu                         | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |
| Alps Electric                   | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 6.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.98%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.65%   |
| Intel AX201 Bluetooth                               | 2         | 4.65%   |
| IMC Networks Bluetooth Device                       | 2         | 4.65%   |
| Broadcom HP Portable SoftSailing                    | 2         | 4.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 4.65%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.33%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| Intel Bluetooth Device                              | 1         | 2.33%   |
| Intel AX211 Bluetooth                               | 1         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.33%   |
| Fujitsu Bluetooth Device                            | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.33%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.33%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |
| Apple Bluetooth Host Controller                     | 1         | 2.33%   |
| Apple Bluetooth HCI                                 | 1         | 2.33%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 83        | 63.85%  |
| Nvidia                           | 16        | 12.31%  |
| AMD                              | 15        | 11.54%  |
| VIA Technologies                 | 4         | 3.08%   |
| Creative Labs                    | 3         | 2.31%   |
| C-Media Electronics              | 3         | 2.31%   |
| Silicon Integrated Systems [SiS] | 2         | 1.54%   |
| ESS Technology                   | 2         | 1.54%   |
| ULi Electronics                  | 1         | 0.77%   |
| Ensoniq                          | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 25        | 17.61%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 9         | 6.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 5         | 3.52%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller           | 4         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 4         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 4         | 2.82%   |
| Nvidia TU116 High Definition Audio Controller                               | 3         | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                       | 3         | 2.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                | 3         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 3         | 2.11%   |
| Intel 8 Series HD Audio Controller                                          | 3         | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 3         | 2.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 3         | 2.11%   |
| AMD FCH Azalia Controller                                                   | 3         | 2.11%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 2         | 1.41%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                    | 2         | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                               | 2         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                               | 2         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 2         | 1.41%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller             | 2         | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                      | 2         | 1.41%   |
| Intel Sunrise Point-LP HD Audio                                             | 2         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller  | 2         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller            | 2         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 2         | 1.41%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                       | 2         | 1.41%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                              | 2         | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                    | 2         | 1.41%   |
| AMD High Definition Audio Controller                                        | 2         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                            | 2         | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2         | 1.41%   |
| VIA Technologies VT82C686 AC97 Audio Controller                             | 1         | 0.7%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1         | 0.7%    |
| VIA Technologies High Definition Audio Controller                           | 1         | 0.7%    |
| ULi Electronics HD Audio Controller                                         | 1         | 0.7%    |
| Nvidia MCP89 High Definition Audio                                          | 1         | 0.7%    |
| Nvidia MCP67 High Definition Audio                                          | 1         | 0.7%    |
| Nvidia High Definition Audio Controller                                     | 1         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                          | 1         | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                               | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 46        | 35.94%  |
| SK hynix            | 22        | 17.19%  |
| Samsung Electronics | 14        | 10.94%  |
| Unknown             | 10        | 7.81%   |
| Kingston            | 8         | 6.25%   |
| Micron Technology   | 6         | 4.69%   |
| Corsair             | 3         | 2.34%   |
| Ramaxel Technology  | 2         | 1.56%   |
| Crucial             | 2         | 1.56%   |
| Unknown (ABCD)      | 1         | 0.78%   |
| Unknown (8A02)      | 1         | 0.78%   |
| Unknown (0x0DA2)    | 1         | 0.78%   |
| tigo                | 1         | 0.78%   |
| Smart               | 1         | 0.78%   |
| Patriot             | 1         | 0.78%   |
| Nanya Technology    | 1         | 0.78%   |
| Kllisre             | 1         | 0.78%   |
| Kingmax             | 1         | 0.78%   |
| G.Skill             | 1         | 0.78%   |
| fef5                | 1         | 0.78%   |
| Elpida              | 1         | 0.78%   |
| Avant               | 1         | 0.78%   |
| Apacer              | 1         | 0.78%   |
| A-DATA Technology   | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 10        | 7.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 4         | 2.94%   |
| Unknown RAM Module 1024MB SODIMM DDR                     | 3         | 2.21%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 3         | 2.21%   |
| Unknown RAM Module 512MB SODIMM DDR                      | 2         | 1.47%   |
| Unknown RAM Module 2GB SODIMM SDRAM                      | 2         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 2         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 2         | 1.47%   |
| Unknown RAM Module 256MB SODIMM DRAM                     | 2         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s               | 2         | 1.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s             | 2         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s    | 2         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 2         | 1.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 2         | 1.47%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s | 2         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 1.47%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2         | 1.47%   |
| Unknown RAM Module 512MB SODIMM SDRAM                    | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DRAM                     | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DDR2                     | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DDR 100MT/s              | 1         | 0.74%   |
| Unknown RAM Module 512MB DIMM SDRAM 333MT/s              | 1         | 0.74%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1         | 0.74%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1         | 0.74%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1         | 0.74%   |
| Unknown RAM Module 512MB DIMM                            | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s               | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s               | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR                        | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1         | 0.74%   |
| Unknown RAM Module 256MB DIMM SDRAM 333MT/s              | 1         | 0.74%   |
| Unknown RAM Module 256MB DIMM SDRAM                      | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                   | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 34        | 30.91%  |
| DDR2    | 23        | 20.91%  |
| SDRAM   | 19        | 17.27%  |
| DDR4    | 13        | 11.82%  |
| DDR     | 9         | 8.18%   |
| Unknown | 5         | 4.55%   |
| DRAM    | 4         | 3.64%   |
| LPDDR4  | 2         | 1.82%   |
| DDR5    | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 66.67%  |
| DIMM         | 34        | 31.48%  |
| Row Of Chips | 1         | 0.93%   |
| Unknown      | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 41        | 32.8%   |
| 1024  | 27        | 21.6%   |
| 4096  | 20        | 16%     |
| 512   | 14        | 11.2%   |
| 8192  | 8         | 6.4%    |
| 16384 | 7         | 5.6%    |
| 256   | 4         | 3.2%    |
| 64    | 2         | 1.6%    |
| 32768 | 1         | 0.8%    |
| 232   | 1         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 22.61%  |
| 1600    | 20        | 17.39%  |
| 667     | 9         | 7.83%   |
| 800     | 8         | 6.96%   |
| 2400    | 6         | 5.22%   |
| 1067    | 6         | 5.22%   |
| 1333    | 5         | 4.35%   |
| 533     | 5         | 4.35%   |
| 4199    | 3         | 2.61%   |
| 3200    | 3         | 2.61%   |
| 2667    | 3         | 2.61%   |
| 1334    | 3         | 2.61%   |
| 3534    | 2         | 1.74%   |
| 3266    | 2         | 1.74%   |
| 975     | 2         | 1.74%   |
| 400     | 2         | 1.74%   |
| 333     | 2         | 1.74%   |
| 200     | 2         | 1.74%   |
| 4800    | 1         | 0.87%   |
| 3600    | 1         | 0.87%   |
| 2048    | 1         | 0.87%   |
| 1866    | 1         | 0.87%   |
| 266     | 1         | 0.87%   |
| 100     | 1         | 0.87%   |

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
| Chicony Electronics                    | 10        | 18.87%  |
| Suyin                                  | 5         | 9.43%   |
| Microdia                               | 5         | 9.43%   |
| IMC Networks                           | 4         | 7.55%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.55%   |
| Pixart Imaging                         | 3         | 5.66%   |
| Acer                                   | 3         | 5.66%   |
| Sunplus Innovation Technology          | 2         | 3.77%   |
| Silicon Motion                         | 2         | 3.77%   |
| Realtek Semiconductor                  | 2         | 3.77%   |
| Lenovo                                 | 2         | 3.77%   |
| Bison Electronics                      | 2         | 3.77%   |
| Apple                                  | 2         | 3.77%   |
| Z-Star Microelectronics                | 1         | 1.89%   |
| Syntek                                 | 1         | 1.89%   |
| Lite-On Technology                     | 1         | 1.89%   |
| Jieli Technology                       | 1         | 1.89%   |
| Importek                               | 1         | 1.89%   |
| Generalplus Technology                 | 1         | 1.89%   |
| Alcor Micro                            | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 3         | 5.66%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 5.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 3.77%   |
| Chicony HD WebCam                                       | 2         | 3.77%   |
| Acer Lenovo EasyCamera                                  | 2         | 3.77%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 1.89%   |
| Syntek Integrated Camera                                | 1         | 1.89%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 1.89%   |
| Suyin USB 2.0 Camera                                    | 1         | 1.89%   |
| Suyin Laptop_Integrated_Webcam_2HDM                     | 1         | 1.89%   |
| Suyin Integrated_Webcam_HD                              | 1         | 1.89%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 1.89%   |
| Sunplus HD WebCam                                       | 1         | 1.89%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 1.89%   |
| Silicon Motion HP Webcam-101 Integrated Camera          | 1         | 1.89%   |
| Realtek Integrated Webcam HD                            | 1         | 1.89%   |
| Realtek HD WebCam                                       | 1         | 1.89%   |
| Microdia Integrated Webcam                              | 1         | 1.89%   |
| Microdia Integrated Camera                              | 1         | 1.89%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 1.89%   |
| Lenovo Integrated Webcam                                | 1         | 1.89%   |
| Lenovo CNF7237&CNF7238                                  | 1         | 1.89%   |
| Jieli USB PHY 2.0                                       | 1         | 1.89%   |
| Importek FJ Camera                                      | 1         | 1.89%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 1.89%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 1.89%   |
| Generalplus 808 Camera                                  | 1         | 1.89%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 1.89%   |
| Chicony Integrated HP HD Webcam                         | 1         | 1.89%   |
| Chicony HP Webcam                                       | 1         | 1.89%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 1.89%   |
| Chicony EasyCamera                                      | 1         | 1.89%   |
| Chicony CNF8243 Webcam                                  | 1         | 1.89%   |
| Chicony CNF7050                                         | 1         | 1.89%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 6         | 66.67%  |
| Upek             | 2         | 22.22%  |
| Validity Sensors | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 4         | 44.44%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 22.22%  |
| AuthenTec AES1600                                      | 2         | 22.22%  |
| Validity Sensors VFS491                                | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 66.67%  |
| Broadcom 5880                                  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 67.86%  |
| 1     | 27        | 24.11%  |
| 2     | 5         | 4.46%   |
| 3     | 3         | 2.68%   |
| 4     | 1         | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 23        | 50%     |
| Fingerprint reader       | 9         | 19.57%  |
| Sound                    | 3         | 6.52%   |
| Communication controller | 3         | 6.52%   |
| Multimedia controller    | 2         | 4.35%   |
| Chipcard                 | 2         | 4.35%   |
| Net/wireless             | 1         | 2.17%   |
| Net/ethernet             | 1         | 2.17%   |
| Modem                    | 1         | 2.17%   |
| Camera                   | 1         | 2.17%   |


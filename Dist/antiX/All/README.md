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

Total: 169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Q524UQK                     | Convertible | [ae899f88af](https://linux-hardware.org/?probe=ae899f88af) | Dec 29, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [f0a067c40e](https://linux-hardware.org/?probe=f0a067c40e) | Dec 26, 2024 |
| Google        | Terra                       | Notebook    | [35133a4a83](https://linux-hardware.org/?probe=35133a4a83) | Dec 10, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [5a3f525db9](https://linux-hardware.org/?probe=5a3f525db9) | Nov 21, 2024 |
| Panasonic     | FZB2-2                      | Tablet      | [beeb215141](https://linux-hardware.org/?probe=beeb215141) | Nov 10, 2024 |
| Maxtang       | BYT30                       | Desktop     | [5891779efd](https://linux-hardware.org/?probe=5891779efd) | Oct 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [6d1e58c127](https://linux-hardware.org/?probe=6d1e58c127) | Oct 19, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [bd91238c40](https://linux-hardware.org/?probe=bd91238c40) | Oct 12, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [20a7878d28](https://linux-hardware.org/?probe=20a7878d28) | Oct 12, 2024 |
| Google        | Grabbiter                   | Notebook    | [2a3731211a](https://linux-hardware.org/?probe=2a3731211a) | Oct 06, 2024 |
| HP            | Presario CQ42               | Notebook    | [bd24eb99d5](https://linux-hardware.org/?probe=bd24eb99d5) | Sep 09, 2024 |
| ASUSTek       | X441SA                      | Notebook    | [35fe8d4aa5](https://linux-hardware.org/?probe=35fe8d4aa5) | Sep 09, 2024 |
| Lenovo        | ThinkPad P51 20HJS49Q00     | Notebook    | [00383b8346](https://linux-hardware.org/?probe=00383b8346) | Aug 27, 2024 |
| Insyde        | BayTrail                    | Notebook    | [6e2a85feb0](https://linux-hardware.org/?probe=6e2a85feb0) | Aug 19, 2024 |
| Dell          | Vostro 14-3468              | Notebook    | [dd8f759e76](https://linux-hardware.org/?probe=dd8f759e76) | Aug 14, 2024 |
| Dell          | Vostro 14-3468              | Notebook    | [225da9f323](https://linux-hardware.org/?probe=225da9f323) | Aug 14, 2024 |
| Pegatron      | Eureka3                     | Desktop     | [e1be68932e](https://linux-hardware.org/?probe=e1be68932e) | Jul 17, 2024 |
| Dell          | Latitude D820               | Notebook    | [27ec5b3e2e](https://linux-hardware.org/?probe=27ec5b3e2e) | Jun 27, 2024 |
| Pegatron      | Eureka3                     | Desktop     | [20309be77a](https://linux-hardware.org/?probe=20309be77a) | Jun 15, 2024 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [2689cb3210](https://linux-hardware.org/?probe=2689cb3210) | Jun 14, 2024 |
| HP            | Compaq 6735s                | Notebook    | [eddd6a81e1](https://linux-hardware.org/?probe=eddd6a81e1) | Jun 09, 2024 |
| HP            | Mini 210-2100               | Notebook    | [95983d6f48](https://linux-hardware.org/?probe=95983d6f48) | Jun 09, 2024 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [e999e71c4a](https://linux-hardware.org/?probe=e999e71c4a) | Jun 07, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ced441dcb5](https://linux-hardware.org/?probe=ced441dcb5) | Jun 07, 2024 |
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

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 36        | 26.67%  |
| antiX 22       | 30        | 22.22%  |
| antiX 23.1     | 23        | 17.04%  |
| antiX 23       | 15        | 11.11%  |
| antiX 19.2     | 8         | 5.93%   |
| antiX 19.3     | 5         | 3.7%    |
| antiX 21-runit | 4         | 2.96%   |
| antiX 17.4.1   | 4         | 2.96%   |
| antiX 19.4     | 3         | 2.22%   |
| antiX 19.1     | 2         | 1.48%   |
| antiX 19.5     | 1         | 0.74%   |
| antiX 17.2.1   | 1         | 0.74%   |
| antiX 17.1     | 1         | 0.74%   |
| antiX 17       | 1         | 0.74%   |
| antiX 15       | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 133       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 16        | 11.85%  |
| 5.10.142-antix.2-amd64-smp   | 14        | 10.37%  |
| 6.1.60-antix.1-amd64-smp     | 11        | 8.15%   |
| 4.9.0-326-antix.1-amd64-smp  | 11        | 8.15%   |
| 4.9.0-279-antix.1-amd64-smp  | 11        | 8.15%   |
| 5.10.57-antix.1-amd64-smp    | 8         | 5.93%   |
| 5.10.188-antix.1-amd64-smp   | 5         | 3.7%    |
| 5.10.188-antix.1-486-smp     | 5         | 3.7%    |
| 4.9.0-326-antix.1-486-smp    | 5         | 3.7%    |
| 5.10.197-antix.1-486-smp     | 4         | 2.96%   |
| 4.9.235-antix.1-amd64-smp    | 4         | 2.96%   |
| 4.9.160-antix.2-486-smp      | 4         | 2.96%   |
| 6.1.42-antix.1-amd64-smp     | 3         | 2.22%   |
| 5.10.224-antix.1-amd64-smp   | 3         | 2.22%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 2.22%   |
| 4.9.212-antix.1-486-smp      | 3         | 2.22%   |
| 6.1.55-antix.1-amd64-smp     | 2         | 1.48%   |
| 6.1.105-antix.1-amd64-smp    | 2         | 1.48%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 1.48%   |
| 4.9.200-antix.1-486-smp      | 2         | 1.48%   |
| 6.2.9-1-liquorix-amd64       | 1         | 0.74%   |
| 6.10.9-1-liquorix-amd64      | 1         | 0.74%   |
| 6.1.90-antix.1-amd64-smp     | 1         | 0.74%   |
| 6.1.0-0.deb11.9-rt-amd64     | 1         | 0.74%   |
| 5.4.0-17.1-liquorix-amd64    | 1         | 0.74%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 0.74%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 0.74%   |
| 5.10.199-antix.1-amd64-smp   | 1         | 0.74%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 0.74%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 0.74%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 0.74%   |
| 4.9.0-264-antix.1-amd64-smp  | 1         | 0.74%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 0.74%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 0.74%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 0.74%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 0.74%   |
| 4.10.5-antix.1-486-smp       | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 45        | 33.58%  |
| 5.10.142 | 14        | 10.45%  |
| 6.1.60   | 11        | 8.21%   |
| 5.10.188 | 10        | 7.46%   |
| 5.10.57  | 8         | 5.97%   |
| 4.9.212  | 6         | 4.48%   |
| 4.9.160  | 5         | 3.73%   |
| 5.10.197 | 4         | 2.99%   |
| 4.9.235  | 4         | 2.99%   |
| 6.1.42   | 3         | 2.24%   |
| 5.10.224 | 3         | 2.24%   |
| 6.1.55   | 2         | 1.49%   |
| 6.1.105  | 2         | 1.49%   |
| 5.10.88  | 2         | 1.49%   |
| 4.9.200  | 2         | 1.49%   |
| 6.2.9    | 1         | 0.75%   |
| 6.10.9   | 1         | 0.75%   |
| 6.1.90   | 1         | 0.75%   |
| 6.1.0    | 1         | 0.75%   |
| 5.4.0    | 1         | 0.75%   |
| 5.14.0   | 1         | 0.75%   |
| 5.10.27  | 1         | 0.75%   |
| 5.10.199 | 1         | 0.75%   |
| 4.9.87   | 1         | 0.75%   |
| 4.19.202 | 1         | 0.75%   |
| 4.19.100 | 1         | 0.75%   |
| 4.19.0   | 1         | 0.75%   |
| 4.10.5   | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 63        | 47.37%  |
| 5.10    | 43        | 32.33%  |
| 6.1     | 19        | 14.29%  |
| 4.19    | 3         | 2.26%   |
| 6.2     | 1         | 0.75%   |
| 6.10    | 1         | 0.75%   |
| 5.4     | 1         | 0.75%   |
| 5.14    | 1         | 0.75%   |
| 4.10    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 90        | 67.67%  |
| i686   | 42        | 31.58%  |
| i586   | 1         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| icewm        | 74        | 54.41%  |
| Unknown      | 42        | 30.88%  |
| XFCE         | 5         | 3.68%   |
| fluxbox      | 5         | 3.68%   |
| JWM          | 3         | 2.21%   |
| herbstluftwm | 2         | 1.47%   |
| GNOME        | 2         | 1.47%   |
| LXQt         | 1         | 0.74%   |
| dwm          | 1         | 0.74%   |
| Cinnamon     | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 130       | 97.74%  |
| Tty     | 2         | 1.5%    |
| Unknown | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 41.79%  |
| SLIMSKI | 45        | 33.58%  |
| SLiM    | 23        | 17.16%  |
| LightDM | 7         | 5.22%   |
| XDM     | 1         | 0.75%   |
| SDDM    | 1         | 0.75%   |
| LXDM    | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 54        | 40.6%   |
| de_DE   | 11        | 8.27%   |
| ru_RU   | 10        | 7.52%   |
| pt_BR   | 6         | 4.51%   |
| it_IT   | 6         | 4.51%   |
| ja_JP   | 5         | 3.76%   |
| en_GB   | 5         | 3.76%   |
| fr_FR   | 4         | 3.01%   |
| es_ES   | 4         | 3.01%   |
| pl_PL   | 3         | 2.26%   |
| Unknown | 3         | 2.26%   |
| sk_SK   | 2         | 1.5%    |
| nl_NL   | 2         | 1.5%    |
| hu_HU   | 2         | 1.5%    |
| es_AR   | 2         | 1.5%    |
| en_NZ   | 2         | 1.5%    |
| en_AU   | 2         | 1.5%    |
| zh_HK   | 1         | 0.75%   |
| uk_UA   | 1         | 0.75%   |
| tr_TR   | 1         | 0.75%   |
| fr_BE   | 1         | 0.75%   |
| fi_FI   | 1         | 0.75%   |
| es_VE   | 1         | 0.75%   |
| es_PE   | 1         | 0.75%   |
| es_MX   | 1         | 0.75%   |
| de_AT   | 1         | 0.75%   |
| da_DK   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 94        | 70.68%  |
| EFI  | 39        | 29.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 118       | 88.72%  |
| Overlay  | 12        | 9.02%   |
| Xfs      | 1         | 0.75%   |
| Reiserfs | 1         | 0.75%   |
| Ext2     | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 85        | 63.91%  |
| GPT     | 46        | 34.59%  |
| Unknown | 2         | 1.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 79.1%   |
| Yes       | 28        | 20.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 65.41%  |
| Yes       | 46        | 34.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 13.53%  |
| Hewlett-Packard     | 17        | 12.78%  |
| Lenovo              | 14        | 10.53%  |
| Dell                | 10        | 7.52%   |
| Acer                | 9         | 6.77%   |
| Apple               | 7         | 5.26%   |
| Gigabyte Technology | 6         | 4.51%   |
| MSI                 | 5         | 3.76%   |
| Intel               | 5         | 3.76%   |
| IBM                 | 5         | 3.76%   |
| Unknown             | 5         | 3.76%   |
| Google              | 4         | 3.01%   |
| Fujitsu             | 4         | 3.01%   |
| Toshiba             | 3         | 2.26%   |
| Pegatron            | 2         | 1.5%    |
| KOHJINSHA           | 2         | 1.5%    |
| VXL                 | 1         | 0.75%   |
| TYAN Computer       | 1         | 0.75%   |
| Sony                | 1         | 0.75%   |
| Samsung Electronics | 1         | 0.75%   |
| Radiant Systems     | 1         | 0.75%   |
| Prestigio           | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| Packard Bell        | 1         | 0.75%   |
| Medion              | 1         | 0.75%   |
| Maxtang             | 1         | 0.75%   |
| Insyde              | 1         | 0.75%   |
| Compaq              | 1         | 0.75%   |
| Clevo               | 1         | 0.75%   |
| Biostar             | 1         | 0.75%   |
| AZW                 | 1         | 0.75%   |
| ASRock              | 1         | 0.75%   |
| AMI                 | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 6         | 4.51%   |
| MSI US Desktop                     | 2         | 1.5%    |
| IBM 260921H                        | 2         | 1.5%    |
| HP Mini 110-3700                   | 2         | 1.5%    |
| Fujitsu FMVNU6G1C                  | 2         | 1.5%    |
| Dell Latitude 5480                 | 2         | 1.5%    |
| VXL TC7520d                        | 1         | 0.75%   |
| TYAN Intel 440BX/GX Rev. 4         | 1         | 0.75%   |
| Toshiba Satellite T110             | 1         | 0.75%   |
| Toshiba Satellite C50-A-1HF        | 1         | 0.75%   |
| Toshiba Satellite 1905             | 1         | 0.75%   |
| Sony VGN-TX690P                    | 1         | 0.75%   |
| Samsung SQ1S                       | 1         | 0.75%   |
| Radiant Systems P845               | 1         | 0.75%   |
| Prestigio Smartbook PSB116A        | 1         | 0.75%   |
| Pegatron VC902AA-ABF p6136fr       | 1         | 0.75%   |
| Pegatron AU930AA-ACJ p6270in       | 1         | 0.75%   |
| Panasonic FZB2-2                   | 1         | 0.75%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 0.75%   |
| MSI MS-7C56                        | 1         | 0.75%   |
| MSI MS-7B17                        | 1         | 0.75%   |
| MSI GE62 7RE                       | 1         | 0.75%   |
| Medion WIM2170                     | 1         | 0.75%   |
| Maxtang BYT30                      | 1         | 0.75%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 0.75%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 0.75%   |
| Lenovo ThinkPad SL500 27463ZG      | 1         | 0.75%   |
| Lenovo ThinkPad P51 20HJS49Q00     | 1         | 0.75%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 0.75%   |
| Lenovo S10-3                       | 1         | 0.75%   |
| Lenovo IdeaPad Y460                | 1         | 0.75%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 0.75%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 0.75%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 0.75%   |
| Lenovo G560 20042                  | 1         | 0.75%   |
| Lenovo G550 2958                   | 1         | 0.75%   |
| Lenovo 3000 V100 076346G           | 1         | 0.75%   |
| KOHJINSHA SX series                | 1         | 0.75%   |
| KOHJINSHA SC series                | 1         | 0.75%   |
| Intel powered classmate PC         | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 5.26%   |
| Dell Latitude         | 6         | 4.51%   |
| Unknown               | 6         | 4.51%   |
| Lenovo ThinkPad       | 4         | 3.01%   |
| Lenovo IdeaPad        | 4         | 3.01%   |
| HP Mini               | 4         | 3.01%   |
| Toshiba Satellite     | 3         | 2.26%   |
| IBM ThinkPad          | 3         | 2.26%   |
| MSI US                | 2         | 1.5%    |
| IBM 260921H           | 2         | 1.5%    |
| HP Presario           | 2         | 1.5%    |
| HP EliteBook          | 2         | 1.5%    |
| HP Compaq             | 2         | 1.5%    |
| Fujitsu FMVNU6G1C     | 2         | 1.5%    |
| Dell Vostro           | 2         | 1.5%    |
| Dell OptiPlex         | 2         | 1.5%    |
| ASUS VivoBook         | 2         | 1.5%    |
| ASUS PRIME            | 2         | 1.5%    |
| VXL TC7520d           | 1         | 0.75%   |
| TYAN Intel            | 1         | 0.75%   |
| Sony VGN-TX690P       | 1         | 0.75%   |
| Samsung SQ1S          | 1         | 0.75%   |
| Radiant Systems P845  | 1         | 0.75%   |
| Prestigio Smartbook   | 1         | 0.75%   |
| Pegatron VC902AA-ABF  | 1         | 0.75%   |
| Pegatron AU930AA-ACJ  | 1         | 0.75%   |
| Panasonic FZB2-2      | 1         | 0.75%   |
| Packard Bell EasyNote | 1         | 0.75%   |
| MSI MS-7C56           | 1         | 0.75%   |
| MSI MS-7B17           | 1         | 0.75%   |
| MSI GE62              | 1         | 0.75%   |
| Medion WIM2170        | 1         | 0.75%   |
| Maxtang BYT30         | 1         | 0.75%   |
| Lenovo ThinkCentre    | 1         | 0.75%   |
| Lenovo S10-3          | 1         | 0.75%   |
| Lenovo G560           | 1         | 0.75%   |
| Lenovo G550           | 1         | 0.75%   |
| Lenovo 3000           | 1         | 0.75%   |
| KOHJINSHA SX          | 1         | 0.75%   |
| KOHJINSHA SC          | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 17        | 12.78%  |
| 2008    | 16        | 12.03%  |
| 2007    | 15        | 11.28%  |
| 2010    | 9         | 6.77%   |
| 2012    | 8         | 6.02%   |
| 2011    | 7         | 5.26%   |
| 2017    | 6         | 4.51%   |
| 2013    | 6         | 4.51%   |
| 2018    | 5         | 3.76%   |
| 2014    | 5         | 3.76%   |
| 2016    | 4         | 3.01%   |
| 2006    | 4         | 3.01%   |
| 2005    | 4         | 3.01%   |
| 2022    | 3         | 2.26%   |
| 2021    | 3         | 2.26%   |
| 2020    | 3         | 2.26%   |
| 2019    | 3         | 2.26%   |
| 2004    | 3         | 2.26%   |
| 2003    | 3         | 2.26%   |
| 2023    | 2         | 1.5%    |
| 2015    | 2         | 1.5%    |
| 1999    | 2         | 1.5%    |
| Unknown | 2         | 1.5%    |
| 2024    | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 90        | 67.67%  |
| Desktop     | 35        | 26.32%  |
| Mini pc     | 4         | 3.01%   |
| All in one  | 2         | 1.5%    |
| Tablet      | 1         | 0.75%   |
| Convertible | 1         | 0.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 133       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 96.99%  |
| Yes  | 4         | 3.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 40        | 30.08%  |
| 1.01-2.0    | 28        | 21.05%  |
| 0.51-1.0    | 15        | 11.28%  |
| 2.01-3.0    | 12        | 9.02%   |
| 4.01-8.0    | 11        | 8.27%   |
| 8.01-16.0   | 7         | 5.26%   |
| 0.01-0.5    | 7         | 5.26%   |
| 32.01-64.0  | 6         | 4.51%   |
| 16.01-24.0  | 5         | 3.76%   |
| 64.01-256.0 | 2         | 1.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 43        | 31.62%  |
| 0.01-0.5   | 40        | 29.41%  |
| 1.01-2.0   | 37        | 27.21%  |
| 2.01-3.0   | 11        | 8.09%   |
| 4.01-8.0   | 3         | 2.21%   |
| 32.01-64.0 | 1         | 0.74%   |
| 3.01-4.0   | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 70.9%   |
| 2      | 23        | 17.16%  |
| 3      | 6         | 4.48%   |
| 0      | 6         | 4.48%   |
| 4      | 3         | 2.24%   |
| 5      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 54.89%  |
| Yes       | 60        | 45.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 85.82%  |
| No        | 19        | 14.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 76.69%  |
| No        | 31        | 23.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 58.21%  |
| Yes       | 56        | 41.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 21        | 15.79%  |
| Russia              | 13        | 9.77%   |
| Germany             | 13        | 9.77%   |
| Hong Kong           | 10        | 7.52%   |
| Italy               | 7         | 5.26%   |
| Poland              | 6         | 4.51%   |
| Japan               | 6         | 4.51%   |
| Brazil              | 6         | 4.51%   |
| Spain               | 5         | 3.76%   |
| France              | 4         | 3.01%   |
| UK                  | 3         | 2.26%   |
| Netherlands         | 3         | 2.26%   |
| Hungary             | 3         | 2.26%   |
| South Africa        | 2         | 1.5%    |
| Slovakia            | 2         | 1.5%    |
| New Zealand         | 2         | 1.5%    |
| India               | 2         | 1.5%    |
| Denmark             | 2         | 1.5%    |
| Czechia             | 2         | 1.5%    |
| Australia           | 2         | 1.5%    |
| Argentina           | 2         | 1.5%    |
| Algeria             | 2         | 1.5%    |
| Uruguay             | 1         | 0.75%   |
| Ukraine             | 1         | 0.75%   |
| Trinidad and Tobago | 1         | 0.75%   |
| Peru                | 1         | 0.75%   |
| Mexico              | 1         | 0.75%   |
| Kenya               | 1         | 0.75%   |
| Kazakhstan          | 1         | 0.75%   |
| Indonesia           | 1         | 0.75%   |
| Guam                | 1         | 0.75%   |
| Greece              | 1         | 0.75%   |
| Finland             | 1         | 0.75%   |
| Chile               | 1         | 0.75%   |
| Bulgaria            | 1         | 0.75%   |
| Belgium             | 1         | 0.75%   |
| Austria             | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 5.07%   |
| Milan                     | 3         | 2.17%   |
| Sydney                    | 2         | 1.45%   |
| St Petersburg             | 2         | 1.45%   |
| Norden                    | 2         | 1.45%   |
| Moscow                    | 2         | 1.45%   |
| Maringá                  | 2         | 1.45%   |
| Central                   | 2         | 1.45%   |
| Budapest                  | 2         | 1.45%   |
| Bratislava                | 2         | 1.45%   |
| Zagnansk                  | 1         | 0.72%   |
| Yuzhno-Sakhalinsk         | 1         | 0.72%   |
| Yokohama                  | 1         | 0.72%   |
| Ybbs an der Donau         | 1         | 0.72%   |
| Whitney                   | 1         | 0.72%   |
| Warsaw                    | 1         | 0.72%   |
| Violes                    | 1         | 0.72%   |
| Varna                     | 1         | 0.72%   |
| Tver                      | 1         | 0.72%   |
| Tunapuna                  | 1         | 0.72%   |
| Trecate                   | 1         | 0.72%   |
| Torricella Sicura         | 1         | 0.72%   |
| Toms River                | 1         | 0.72%   |
| Tokyo                     | 1         | 0.72%   |
| Templeton                 | 1         | 0.72%   |
| St Albans                 | 1         | 0.72%   |
| Sofia                     | 1         | 0.72%   |
| Sheung Shui               | 1         | 0.72%   |
| Seattle                   | 1         | 0.72%   |
| Schloss Holte-Stukenbrock | 1         | 0.72%   |
| Santiago                  | 1         | 0.72%   |
| Salto                     | 1         | 0.72%   |
| Sagamino                  | 1         | 0.72%   |
| Rotterdam                 | 1         | 0.72%   |
| Romilly-sur-Seine         | 1         | 0.72%   |
| Reutlingen                | 1         | 0.72%   |
| Purmerend                 | 1         | 0.72%   |
| Pritzwalk                 | 1         | 0.72%   |
| Prague                    | 1         | 0.72%   |
| Portland                  | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 28        | 33     | 17.72%  |
| Seagate                   | 26        | 26     | 16.46%  |
| Hitachi                   | 17        | 19     | 10.76%  |
| Samsung Electronics       | 16        | 18     | 10.13%  |
| Toshiba                   | 13        | 14     | 8.23%   |
| Unknown                   | 10        | 10     | 6.33%   |
| Kingston                  | 6         | 7      | 3.8%    |
| SanDisk                   | 4         | 4      | 2.53%   |
| Unknown                   | 4         | 4      | 2.53%   |
| Maxtor                    | 3         | 3      | 1.9%    |
| HGST                      | 3         | 3      | 1.9%    |
| BHT                       | 3         | 5      | 1.9%    |
| PNY                       | 2         | 3      | 1.27%   |
| Micron/Crucial Technology | 2         | 2      | 1.27%   |
| Intel                     | 2         | 2      | 1.27%   |
| China                     | 2         | 2      | 1.27%   |
| Zheino                    | 1         | 1      | 0.63%   |
| Unknown (CF)              | 1         | 1      | 0.63%   |
| Transcend                 | 1         | 1      | 0.63%   |
| SPCC                      | 1         | 1      | 0.63%   |
| RECADATA                  | 1         | 1      | 0.63%   |
| Patriot                   | 1         | 1      | 0.63%   |
| OCZ                       | 1         | 1      | 0.63%   |
| NVMe                      | 1         | 1      | 0.63%   |
| KIOXIA                    | 1         | 1      | 0.63%   |
| IBM/Hitachi               | 1         | 1      | 0.63%   |
| Hewlett-Packard           | 1         | 1      | 0.63%   |
| Fujitsu                   | 1         | 1      | 0.63%   |
| Crucial                   | 1         | 1      | 0.63%   |
| BIWIN                     | 1         | 1      | 0.63%   |
| ASUS-PHISON               | 1         | 1      | 0.63%   |
| Apple                     | 1         | 1      | 0.63%   |
| Apacer                    | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 4         | 2.48%   |
| WDC WD800AAJS-75M0A0 80GB         | 2         | 1.24%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 2         | 1.24%   |
| WDC WD10SPZX-80Z10T2 1TB          | 2         | 1.24%   |
| Toshiba MQ01ABD100 1TB            | 2         | 1.24%   |
| Toshiba MQ01ABD050V -63 500GB     | 2         | 1.24%   |
| Seagate ST980811AS 80GB           | 2         | 1.24%   |
| Seagate ST9320325AS 320GB         | 2         | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB    | 2         | 1.24%   |
| Samsung SSD 850 EVO 120GB         | 2         | 1.24%   |
| Samsung SSD 750 EVO 120GB         | 2         | 1.24%   |
| Maxtor Z1 SSD 240GB               | 2         | 1.24%   |
| Kingston SA400S37240G 240GB SSD   | 2         | 1.24%   |
| Hitachi HTS723232A7A364 320GB     | 2         | 1.24%   |
| Hitachi HTS548040M9AT00 40GB      | 2         | 1.24%   |
| Hitachi HTS545025B9A300 250GB     | 2         | 1.24%   |
| Hitachi HTS542525K9SA00 250GB     | 2         | 1.24%   |
| BHT WR202F0032G 670270F5 32GB SSD | 2         | 1.24%   |
| Zheino CHN mSATAM3 128 128GB SSD  | 1         | 0.62%   |
| WDC WD8088AADS-00M2B0 809GB       | 1         | 0.62%   |
| WDC WD800JB-00ETA0 80GB           | 1         | 0.62%   |
| WDC WD800BEVT-75ZCT2 80GB         | 1         | 0.62%   |
| WDC WD5000LPLX-08ZNTT0 500GB      | 1         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 0.62%   |
| WDC WD5000BEVT-24A0RT0 500GB      | 1         | 0.62%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 0.62%   |
| WDC WD5000AVDS-63U7B1 500GB       | 1         | 0.62%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 0.62%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 0.62%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 0.62%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 0.62%   |
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 0.62%   |
| WDC WD2500BEKT-60PVMT0 250GB      | 1         | 0.62%   |
| WDC WD20SPZX-75UA7T1 2TB          | 1         | 0.62%   |
| WDC WD205BA 21GB                  | 1         | 0.62%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1         | 0.62%   |
| WDC WD1600BEVT-60ZCT1 160GB       | 1         | 0.62%   |
| WDC WD1600BEVT-00M9YT0 160GB      | 1         | 0.62%   |
| WDC WD1600BEVS-22RST0 160GB       | 1         | 0.62%   |
| WDC WD1600AAJS-00PSA0 160GB       | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 33     | 28.57%  |
| Seagate             | 26        | 26     | 26.53%  |
| Hitachi             | 17        | 19     | 17.35%  |
| Toshiba             | 11        | 12     | 11.22%  |
| Samsung Electronics | 7         | 8      | 7.14%   |
| HGST                | 3         | 3      | 3.06%   |
| Unknown             | 2         | 2      | 2.04%   |
| Unknown (CF)        | 1         | 1      | 1.02%   |
| Maxtor              | 1         | 1      | 1.02%   |
| IBM/Hitachi         | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 1      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 15.38%  |
| Kingston            | 5         | 6      | 12.82%  |
| BHT                 | 3         | 5      | 7.69%   |
| Toshiba             | 2         | 2      | 5.13%   |
| SanDisk             | 2         | 2      | 5.13%   |
| PNY                 | 2         | 3      | 5.13%   |
| Maxtor              | 2         | 2      | 5.13%   |
| China               | 2         | 2      | 5.13%   |
| Unknown             | 2         | 2      | 5.13%   |
| Zheino              | 1         | 1      | 2.56%   |
| Transcend           | 1         | 1      | 2.56%   |
| SPCC                | 1         | 1      | 2.56%   |
| RECADATA            | 1         | 1      | 2.56%   |
| Patriot             | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| Crucial             | 1         | 1      | 2.56%   |
| BIWIN               | 1         | 1      | 2.56%   |
| ASUS-PHISON         | 1         | 1      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |
| Apacer              | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 89        | 107    | 61.38%  |
| SSD  | 38        | 43     | 26.21%  |
| MMC  | 9         | 11     | 6.21%   |
| NVMe | 9         | 11     | 6.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 147    | 84.56%  |
| NVMe | 9         | 11     | 6.62%   |
| MMC  | 9         | 11     | 6.62%   |
| SAS  | 3         | 3      | 2.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 126    | 83.33%  |
| 0.51-1.0   | 17        | 19     | 13.49%  |
| 1.01-2.0   | 3         | 3      | 2.38%   |
| 4.01-10.0  | 1         | 2      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 30.15%  |
| 1-20           | 25        | 18.38%  |
| 51-100         | 22        | 16.18%  |
| 251-500        | 18        | 13.24%  |
| 21-50          | 17        | 12.5%   |
| 501-1000       | 8         | 5.88%   |
| More than 3000 | 2         | 1.47%   |
| 1001-2000      | 2         | 1.47%   |
| 2001-3000      | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 99        | 73.88%  |
| 21-50          | 15        | 11.19%  |
| 101-250        | 10        | 7.46%   |
| 51-100         | 5         | 3.73%   |
| More than 3000 | 2         | 1.49%   |
| 501-1000       | 2         | 1.49%   |
| 251-500        | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2         | 2      | 3.85%   |
| Seagate ST980811AS 80GB                     | 2         | 2      | 3.85%   |
| Seagate ST9320325AS 320GB                   | 2         | 2      | 3.85%   |
| Hitachi HTS542525K9SA00 250GB               | 2         | 2      | 3.85%   |
| WDC WD800JB-00ETA0 80GB                     | 1         | 1      | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.92%   |
| WDC WD5000BEVT-24A0RT0 500GB                | 1         | 1      | 1.92%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 3      | 1.92%   |
| WDC WD3200BPVT-24ZEST0 320GB                | 1         | 1      | 1.92%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 1         | 1      | 1.92%   |
| WDC WD2500BEVT-22ZCT0 250GB                 | 1         | 1      | 1.92%   |
| WDC WD2500BEKT-60PVMT0 250GB                | 1         | 1      | 1.92%   |
| WDC WD205BA 21GB                            | 1         | 1      | 1.92%   |
| WDC WD1600BEVT-00M9YT0 160GB                | 1         | 2      | 1.92%   |
| WDC WD10EADS-65M2B0 1TB                     | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 1.92%   |
| Toshiba MK6006GAH 64GB                      | 1         | 1      | 1.92%   |
| Toshiba MK2555GSX 250GB                     | 1         | 1      | 1.92%   |
| Seagate ST980812AS 80GB                     | 1         | 1      | 1.92%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 1.92%   |
| Seagate ST9160827AS 160GB                   | 1         | 1      | 1.92%   |
| Seagate ST9160314AS 160GB                   | 1         | 1      | 1.92%   |
| Seagate ST9160310AS 160GB                   | 1         | 1      | 1.92%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 1.92%   |
| Seagate ST3500312CS 500GB                   | 1         | 1      | 1.92%   |
| Seagate ST3320620AS 320GB                   | 1         | 1      | 1.92%   |
| Seagate ST3320413CS 320GB                   | 1         | 1      | 1.92%   |
| Seagate ST320LT007-9ZV142 320GB             | 1         | 1      | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 1.92%   |
| Seagate ST1000DM010-2EP102 1TB              | 1         | 1      | 1.92%   |
| SanDisk sandisk120 120GB SSD                | 1         | 1      | 1.92%   |
| Samsung Electronics HN-M500MBB 500GB        | 1         | 1      | 1.92%   |
| Samsung Electronics HM161GI 160GB           | 1         | 1      | 1.92%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1         | 1      | 1.92%   |
| Maxtor 2F040L0 41GB                         | 1         | 1      | 1.92%   |
| Hitachi HTS725050A7E630 500GB               | 1         | 1      | 1.92%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 1.92%   |
| Hitachi HTS721060G9AT00 64GB                | 1         | 1      | 1.92%   |
| Hitachi HTS548040M9AT00 40GB                | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 16        | 16     | 30.77%  |
| WDC                       | 14        | 17     | 26.92%  |
| Hitachi                   | 9         | 9      | 17.31%  |
| Toshiba                   | 3         | 3      | 5.77%   |
| Samsung Electronics       | 2         | 2      | 3.85%   |
| HGST                      | 2         | 2      | 3.85%   |
| SanDisk                   | 1         | 1      | 1.92%   |
| Micron/Crucial Technology | 1         | 1      | 1.92%   |
| Maxtor                    | 1         | 1      | 1.92%   |
| China                     | 1         | 1      | 1.92%   |
| BIWIN                     | 1         | 1      | 1.92%   |
| Apacer                    | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 34.04%  |
| WDC                 | 14        | 17     | 29.79%  |
| Hitachi             | 9         | 9      | 19.15%  |
| Toshiba             | 3         | 3      | 6.38%   |
| Samsung Electronics | 2         | 2      | 4.26%   |
| HGST                | 2         | 2      | 4.26%   |
| Maxtor              | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 50     | 90.38%  |
| SSD  | 4         | 4      | 7.69%   |
| NVMe | 1         | 1      | 1.92%   |

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
| Works    | 68        | 93     | 48.92%  |
| Malfunc  | 52        | 55     | 37.41%  |
| Detected | 19        | 24     | 13.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 69.29%  |
| AMD                              | 13        | 9.29%   |
| Nvidia                           | 6         | 4.29%   |
| ASMedia Technology               | 4         | 2.86%   |
| VIA Technologies                 | 3         | 2.14%   |
| Samsung Electronics              | 3         | 2.14%   |
| Silicon Integrated Systems [SiS] | 2         | 1.43%   |
| Micron/Crucial Technology        | 2         | 1.43%   |
| JMicron Technology               | 2         | 1.43%   |
| ULi Electronics                  | 1         | 0.71%   |
| Silicon Image                    | 1         | 0.71%   |
| SanDisk                          | 1         | 0.71%   |
| Marvell Technology Group         | 1         | 0.71%   |
| LSI Logic / Symbios Logic        | 1         | 0.71%   |
| KIOXIA                           | 1         | 0.71%   |
| Kingston Technology Company      | 1         | 0.71%   |
| ADATA Technology                 | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13        | 7.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 8         | 4.62%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 4.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 4.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 4.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 3.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 6         | 3.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 3.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.89%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 2.31%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 4         | 2.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.73%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.73%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.73%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.16%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.16%   |
| VIA VX900 Series Serial-ATA Controller                                         | 1         | 0.58%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.58%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 0.58%   |
| ULi ULi M5288 SATA                                                             | 1         | 0.58%   |
| ULi M5229 IDE                                                                  | 1         | 0.58%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.58%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.58%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 49.66%  |
| IDE  | 60        | 40.27%  |
| NVMe | 9         | 6.04%   |
| RAID | 5         | 3.36%   |
| SAS  | 1         | 0.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 112       | 84.21%  |
| AMD          | 18        | 13.53%  |
| CentaurHauls | 2         | 1.5%    |
| GenuineTMx86 | 1         | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 4.51%   |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 2.26%   |
| Intel Pentium M processor 1.60GHz           | 2         | 1.5%    |
| Intel Pentium M processor 1.00GHz           | 2         | 1.5%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2         | 1.5%    |
| Intel Genuine processor 800MHz              | 2         | 1.5%    |
| Intel Genuine CPU T2400 @ 1.83GHz           | 2         | 1.5%    |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 1.5%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.5%    |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2         | 1.5%    |
| Intel Celeron (Mendocino)                   | 2         | 1.5%    |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 1.5%    |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.5%    |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.5%    |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 1.5%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 1.5%    |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 1.5%    |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 0.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.75%   |
| Intel Pentium M processor 1600MHz           | 1         | 0.75%   |
| Intel Pentium M processor 1.86GHz           | 1         | 0.75%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.75%   |
| Intel Pentium M processor 1.20GHz           | 1         | 0.75%   |
| Intel Pentium III (Katmai)                  | 1         | 0.75%   |
| Intel Pentium II (Deschutes)                | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.75%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.75%   |
| Intel Pentium CPU G2130 @ 3.20GHz           | 1         | 0.75%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1         | 0.75%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 0.75%   |
| Intel Genuine CPU U2700 @ 1.30GHz           | 1         | 0.75%   |
| Intel Genuine CPU T2600 @ 2.16GHz           | 1         | 0.75%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.75%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 22        | 16.54%  |
| Intel Core 2 Duo        | 16        | 12.03%  |
| Intel Celeron           | 14        | 10.53%  |
| Intel Core i5           | 9         | 6.77%   |
| Intel Pentium M         | 8         | 6.02%   |
| Intel Core i7           | 8         | 6.02%   |
| Intel Genuine           | 7         | 5.26%   |
| Intel Core i3           | 7         | 5.26%   |
| Other                   | 5         | 3.76%   |
| Intel Pentium Dual-Core | 4         | 3.01%   |
| AMD Ryzen 7             | 3         | 2.26%   |
| Intel Pentium Dual      | 2         | 1.5%    |
| Intel Pentium 4         | 2         | 1.5%    |
| Intel Pentium           | 2         | 1.5%    |
| AMD Sempron             | 2         | 1.5%    |
| AMD E2                  | 2         | 1.5%    |
| AMD Athlon 64 X2        | 2         | 1.5%    |
| Intel Xeon              | 1         | 0.75%   |
| Intel Pentium Silver    | 1         | 0.75%   |
| Intel Pentium III       | 1         | 0.75%   |
| Intel Core i9           | 1         | 0.75%   |
| Intel Core 2 Quad       | 1         | 0.75%   |
| Intel Core 2            | 1         | 0.75%   |
| Intel Celeron M         | 1         | 0.75%   |
| Intel Celeron Dual-Core | 1         | 0.75%   |
| CentaurHauls VIA Nano   | 1         | 0.75%   |
| CentaurHauls VIA Eden   | 1         | 0.75%   |
| AMD Ryzen 5             | 1         | 0.75%   |
| AMD Ryzen 3             | 1         | 0.75%   |
| AMD Phenom II X4        | 1         | 0.75%   |
| AMD Phenom              | 1         | 0.75%   |
| AMD E1                  | 1         | 0.75%   |
| AMD Athlon II           | 1         | 0.75%   |
| AMD Athlon 64           | 1         | 0.75%   |
| AMD A6                  | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 50.38%  |
| 1      | 40        | 30.08%  |
| 4      | 18        | 13.53%  |
| 8      | 4         | 3.01%   |
| 6      | 3         | 2.26%   |
| 24     | 1         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 99.25%  |
| 2      | 1         | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 62.41%  |
| 2      | 50        | 37.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 75.19%  |
| 32-bit         | 33        | 24.81%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 13        | 9.77%   |
| Unknown    | 13        | 9.77%   |
| 0x106c2    | 10        | 7.52%   |
| 0x6fd      | 6         | 4.51%   |
| 0x6d8      | 6         | 4.51%   |
| 0x30678    | 6         | 4.51%   |
| 0x106ca    | 6         | 4.51%   |
| 0x206a7    | 5         | 3.76%   |
| 0x6e8      | 4         | 3.01%   |
| 0x6d6      | 4         | 3.01%   |
| 0x306a9    | 4         | 3.01%   |
| 0x10676    | 4         | 3.01%   |
| 0x806e9    | 3         | 2.26%   |
| 0x706a8    | 3         | 2.26%   |
| 0x406c4    | 3         | 2.26%   |
| 0x40651    | 3         | 2.26%   |
| 0x306c3    | 3         | 2.26%   |
| 0xa0671    | 2         | 1.5%    |
| 0x906e9    | 2         | 1.5%    |
| 0x66a      | 2         | 1.5%    |
| 0x30661    | 2         | 1.5%    |
| 0x20655    | 2         | 1.5%    |
| 0x20652    | 2         | 1.5%    |
| 0x10661    | 2         | 1.5%    |
| 0x010000c8 | 2         | 1.5%    |
| 0xf29      | 1         | 0.75%   |
| 0xf24      | 1         | 0.75%   |
| 0x906ed    | 1         | 0.75%   |
| 0x706a1    | 1         | 0.75%   |
| 0x6fa      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x695      | 1         | 0.75%   |
| 0x673      | 1         | 0.75%   |
| 0x652      | 1         | 0.75%   |
| 0x506c9    | 1         | 0.75%   |
| 0x0a404102 | 1         | 0.75%   |
| 0x08701021 | 1         | 0.75%   |
| 0x08108109 | 1         | 0.75%   |
| 0x08001138 | 1         | 0.75%   |
| 0x07030106 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 19        | 14.29%  |
| Bonnell          | 19        | 14.29%  |
| P6               | 16        | 12.03%  |
| Core             | 10        | 7.52%   |
| Silvermont       | 9         | 6.77%   |
| Unknown          | 9         | 6.77%   |
| KabyLake         | 7         | 5.26%   |
| Haswell          | 6         | 4.51%   |
| SandyBridge      | 5         | 3.76%   |
| Westmere         | 4         | 3.01%   |
| K8 Hammer        | 4         | 3.01%   |
| IvyBridge        | 4         | 3.01%   |
| Goldmont plus    | 4         | 3.01%   |
| K10              | 3         | 2.26%   |
| Zen+             | 2         | 1.5%    |
| NetBurst         | 2         | 1.5%    |
| Excavator        | 2         | 1.5%    |
| Zen 2            | 1         | 0.75%   |
| Zen              | 1         | 0.75%   |
| Puma             | 1         | 0.75%   |
| Piledriver       | 1         | 0.75%   |
| K8 & K10 hybrid  | 1         | 0.75%   |
| Jaguar           | 1         | 0.75%   |
| Goldmont         | 1         | 0.75%   |
| Alderlake Hybrid | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 59.57%  |
| Nvidia                           | 26        | 18.44%  |
| AMD                              | 26        | 18.44%  |
| VIA Technologies                 | 2         | 1.42%   |
| Neomagic                         | 2         | 1.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 13        | 8.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 5.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 4.35%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 4.35%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 3.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.73%   |
| Intel HD Graphics 620                                                                    | 4         | 2.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 2.48%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.86%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 3         | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 1.24%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.24%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 2         | 1.24%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 2         | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.24%   |
| Intel HD Graphics 630                                                                    | 2         | 1.24%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.24%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.24%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                      | 2         | 1.24%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.24%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.24%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                             | 1         | 0.62%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                            | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.62%   |
| Nvidia NV44A [GeForce 6200]                                                              | 1         | 0.62%   |
| Nvidia NV11M [GeForce2 Go]                                                               | 1         | 0.62%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.62%   |
| Nvidia GT218 [GeForce G210]                                                              | 1         | 0.62%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.62%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 51.13%  |
| 1 x AMD        | 20        | 15.04%  |
| 1 x Nvidia     | 19        | 14.29%  |
| Intel + Nvidia | 7         | 5.26%   |
| 2 x Intel      | 6         | 4.51%   |
| 2 x AMD        | 5         | 3.76%   |
| Other          | 2         | 1.5%    |
| 1 x VIA        | 2         | 1.5%    |
| 1 x Neomagic   | 2         | 1.5%    |
| 1 x SiS        | 1         | 0.75%   |
| Intel + AMD    | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 107       | 80.45%  |
| Unknown     | 17        | 12.78%  |
| Proprietary | 9         | 6.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 51.13%  |
| 0.01-0.5   | 42        | 31.58%  |
| 1.01-2.0   | 15        | 11.28%  |
| 0.51-1.0   | 3         | 2.26%   |
| 5.01-6.0   | 2         | 1.5%    |
| 3.01-4.0   | 2         | 1.5%    |
| 16.01-24.0 | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 19%     |
| Samsung Electronics     | 11        | 11%     |
| LG Display              | 11        | 11%     |
| BOE                     | 6         | 6%      |
| Apple                   | 6         | 6%      |
| LG Philips              | 5         | 5%      |
| Chimei Innolux          | 5         | 5%      |
| Acer                    | 5         | 5%      |
| Lenovo                  | 4         | 4%      |
| HannStar                | 4         | 4%      |
| Goldstar                | 4         | 4%      |
| Ancor Communications    | 3         | 3%      |
| Hewlett-Packard         | 2         | 2%      |
| CPT                     | 2         | 2%      |
| Chi Mei Optoelectronics | 2         | 2%      |
| Vizio                   | 1         | 1%      |
| ViewSonic               | 1         | 1%      |
| Unknown (XXX)           | 1         | 1%      |
| OUT                     | 1         | 1%      |
| LG Electronics          | 1         | 1%      |
| InfoVision              | 1         | 1%      |
| HJW                     | 1         | 1%      |
| Dell                    | 1         | 1%      |
| Arnos Instruments       | 1         | 1%      |
| AOC                     | 1         | 1%      |
| Unknown                 | 1         | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 2%      |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 2         | 2%      |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 2%      |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 2%      |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 2%      |
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                      | 1         | 1%      |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch            | 1         | 1%      |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch                 | 1         | 1%      |
| Samsung Electronics SyncMaster SAM030D 1680x1050 474x296mm 22.0-inch     | 1         | 1%      |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch     | 1         | 1%      |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch      | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC564E 1280x720 223x125mm 10.1-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4346 1920x1200 331x207mm 15.4-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 1%      |
| OUT Analog OUT0170 1280x768 368x207mm 16.6-inch                          | 1         | 1%      |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 1%      |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 1%      |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1%      |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 1%      |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 1%      |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                         | 1         | 1%      |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 1%      |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 1%      |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch              | 1         | 1%      |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 1%      |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 1         | 1%      |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 1         | 1%      |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1%      |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 32        | 32.32%  |
| 1920x1080 (FHD)    | 21        | 21.21%  |
| 1280x800 (WXGA)    | 13        | 13.13%  |
| 1024x600           | 8         | 8.08%   |
| 1440x900 (WXGA+)   | 5         | 5.05%   |
| 1920x1200 (WUXGA)  | 3         | 3.03%   |
| 1680x1050 (WSXGA+) | 3         | 3.03%   |
| 1280x1024 (SXGA)   | 3         | 3.03%   |
| 3840x2160 (4K)     | 2         | 2.02%   |
| 1600x1200          | 2         | 2.02%   |
| 4480x3600          | 1         | 1.01%   |
| 2560x1080          | 1         | 1.01%   |
| 2288x1287          | 1         | 1.01%   |
| 1600x900 (HD+)     | 1         | 1.01%   |
| 1360x768           | 1         | 1.01%   |
| 1280x720 (HD)      | 1         | 1.01%   |
| Unknown            | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 27.27%  |
| 13      | 10        | 10.1%   |
| 21      | 8         | 8.08%   |
| 11      | 8         | 8.08%   |
| 10      | 8         | 8.08%   |
| 14      | 6         | 6.06%   |
| 17      | 5         | 5.05%   |
| 27      | 3         | 3.03%   |
| 18      | 3         | 3.03%   |
| 24      | 2         | 2.02%   |
| 23      | 2         | 2.02%   |
| 12      | 2         | 2.02%   |
| 8       | 2         | 2.02%   |
| Unknown | 2         | 2.02%   |
| 43      | 1         | 1.01%   |
| 38      | 1         | 1.01%   |
| 34      | 1         | 1.01%   |
| 32      | 1         | 1.01%   |
| 31      | 1         | 1.01%   |
| 26      | 1         | 1.01%   |
| 25      | 1         | 1.01%   |
| 22      | 1         | 1.01%   |
| 20      | 1         | 1.01%   |
| 19      | 1         | 1.01%   |
| 16      | 1         | 1.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 40.4%   |
| 201-300     | 22        | 22.22%  |
| 401-500     | 13        | 13.13%  |
| 501-600     | 9         | 9.09%   |
| 351-400     | 6         | 6.06%   |
| 801-900     | 2         | 2.02%   |
| 701-800     | 2         | 2.02%   |
| 101-200     | 2         | 2.02%   |
| Unknown     | 2         | 2.02%   |
| 601-700     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 66.67%  |
| 16/10   | 24        | 25%     |
| 4/3     | 4         | 4.17%   |
| 5/4     | 1         | 1.04%   |
| 3/2     | 1         | 1.04%   |
| 21/9    | 1         | 1.04%   |
| Unknown | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 26.26%  |
| 81-90          | 14        | 14.14%  |
| 201-250        | 11        | 11.11%  |
| 51-60          | 8         | 8.08%   |
| 41-50          | 8         | 8.08%   |
| 301-350        | 4         | 4.04%   |
| 151-200        | 4         | 4.04%   |
| 141-150        | 4         | 4.04%   |
| 351-500        | 3         | 3.03%   |
| 131-140        | 3         | 3.03%   |
| 71-80          | 2         | 2.02%   |
| 61-70          | 2         | 2.02%   |
| 1-40           | 2         | 2.02%   |
| 111-120        | 2         | 2.02%   |
| 501-1000       | 2         | 2.02%   |
| Unknown        | 2         | 2.02%   |
| 251-300        | 1         | 1.01%   |
| 121-130        | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 38        | 38.78%  |
| 51-100        | 30        | 30.61%  |
| 121-160       | 23        | 23.47%  |
| 1-50          | 3         | 3.06%   |
| Unknown       | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |
| 161-240       | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 114       | 85.07%  |
| 0     | 15        | 11.19%  |
| 2     | 5         | 3.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 57        | 27.8%   |
| Intel                            | 50        | 24.39%  |
| Qualcomm Atheros                 | 30        | 14.63%  |
| Broadcom                         | 26        | 12.68%  |
| Marvell Technology Group         | 7         | 3.41%   |
| Nvidia                           | 6         | 2.93%   |
| Ralink                           | 3         | 1.46%   |
| Broadcom Limited                 | 3         | 1.46%   |
| Silicon Integrated Systems [SiS] | 2         | 0.98%   |
| Samsung Electronics              | 2         | 0.98%   |
| Ralink Technology                | 2         | 0.98%   |
| Qualcomm Atheros Communications  | 2         | 0.98%   |
| MediaTek                         | 2         | 0.98%   |
| vivo                             | 1         | 0.49%   |
| Texas Instruments                | 1         | 0.49%   |
| Sierra Wireless                  | 1         | 0.49%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.49%   |
| NetGear                          | 1         | 0.49%   |
| Motorola PCS                     | 1         | 0.49%   |
| LSI                              | 1         | 0.49%   |
| Linksys                          | 1         | 0.49%   |
| Huawei Technologies              | 1         | 0.49%   |
| Hewlett-Packard                  | 1         | 0.49%   |
| Attansic Technology              | 1         | 0.49%   |
| ASIX Electronics                 | 1         | 0.49%   |
| 3Com                             | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 21        | 8.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 7.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 4.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 3.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 2.07%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 4         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.65%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 1.24%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.24%   |
| Intel Wireless 7260                                                     | 3         | 1.24%   |
| Intel WiFi Link 5100                                                    | 3         | 1.24%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 3         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.24%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.24%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 1.24%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.83%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.83%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 2         | 0.83%   |
| Intel Wireless 8260                                                     | 2         | 0.83%   |
| Intel Wireless 7265                                                     | 2         | 0.83%   |
| Intel Wireless 3165                                                     | 2         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.83%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.83%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.83%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 2         | 0.83%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 37.27%  |
| Qualcomm Atheros                | 26        | 23.64%  |
| Broadcom                        | 20        | 18.18%  |
| Realtek Semiconductor           | 9         | 8.18%   |
| Ralink                          | 3         | 2.73%   |
| Ralink Technology               | 2         | 1.82%   |
| Qualcomm Atheros Communications | 2         | 1.82%   |
| MediaTek                        | 2         | 1.82%   |
| Texas Instruments               | 1         | 0.91%   |
| Sierra Wireless                 | 1         | 0.91%   |
| NetGear                         | 1         | 0.91%   |
| Linksys                         | 1         | 0.91%   |
| Broadcom Limited                | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 11        | 9.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 6         | 5.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 5         | 4.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 3.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 4         | 3.6%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 3.6%    |
| Intel Wireless 8265 / 8275                                                    | 3         | 2.7%    |
| Intel Wireless 7260                                                           | 3         | 2.7%    |
| Intel WiFi Link 5100                                                          | 3         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 2.7%    |
| Broadcom BCM4311 802.11b/g WLAN                                               | 3         | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.8%    |
| Ralink RT5370 Wireless Adapter                                                | 2         | 1.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.8%    |
| Intel Wireless 8260                                                           | 2         | 1.8%    |
| Intel Wireless 7265                                                           | 2         | 1.8%    |
| Intel Wireless 3165                                                           | 2         | 1.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 1.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.8%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.8%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.9%    |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.9%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.9%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                   | 1         | 0.9%    |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 0.9%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 0.9%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 0.9%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.9%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 55        | 45.45%  |
| Intel                            | 25        | 20.66%  |
| Broadcom                         | 10        | 8.26%   |
| Qualcomm Atheros                 | 7         | 5.79%   |
| Marvell Technology Group         | 7         | 5.79%   |
| Nvidia                           | 6         | 4.96%   |
| Silicon Integrated Systems [SiS] | 2         | 1.65%   |
| Broadcom Limited                 | 2         | 1.65%   |
| vivo                             | 1         | 0.83%   |
| Samsung Electronics              | 1         | 0.83%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.83%   |
| Motorola PCS                     | 1         | 0.83%   |
| Attansic Technology              | 1         | 0.83%   |
| ASIX Electronics                 | 1         | 0.83%   |
| 3Com                             | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 21        | 17.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 14.75%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 6.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 4         | 3.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 1.64%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 1.64%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.64%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 2         | 1.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.64%   |
| vivo 1820                                                              | 1         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.82%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.82%   |
| OnePlus (Shenzhen) OnePlus                                             | 1         | 0.82%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 0.82%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.82%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.82%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.82%   |
| Nvidia CK8S Ethernet Controller                                        | 1         | 0.82%   |
| Nvidia CK804 Ethernet Controller                                       | 1         | 0.82%   |
| Motorola PCS moto g84 5G                                               | 1         | 0.82%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.82%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.82%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.82%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1         | 0.82%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 115       | 50.88%  |
| WiFi     | 102       | 45.13%  |
| Modem    | 9         | 3.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 64.23%  |
| Ethernet | 49        | 35.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 84        | 63.16%  |
| 1     | 46        | 34.59%  |
| 0     | 2         | 1.5%    |
| 3     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 105       | 77.78%  |
| Yes  | 30        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 27.27%  |
| Broadcom                        | 10        | 18.18%  |
| Apple                           | 7         | 12.73%  |
| Cambridge Silicon Radio         | 5         | 9.09%   |
| IMC Networks                    | 3         | 5.45%   |
| Realtek Semiconductor           | 2         | 3.64%   |
| Qualcomm Atheros Communications | 2         | 3.64%   |
| Lite-On Technology              | 2         | 3.64%   |
| Hewlett-Packard                 | 2         | 3.64%   |
| Foxconn / Hon Hai               | 2         | 3.64%   |
| Taiyo Yuden                     | 1         | 1.82%   |
| Ralink Technology               | 1         | 1.82%   |
| Fujitsu                         | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |
| Alps Electric                   | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 14.55%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.45%   |
| Apple Bluetooth Host Controller                     | 3         | 5.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.64%   |
| Intel AX201 Bluetooth                               | 2         | 3.64%   |
| IMC Networks Bluetooth Device                       | 2         | 3.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.64%   |
| Broadcom HP Portable SoftSailing                    | 2         | 3.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 3.64%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.64%   |
| Apple Bluetooth HCI                                 | 2         | 3.64%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 1.82%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.82%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.82%   |
| Intel AX211 Bluetooth                               | 1         | 1.82%   |
| IMC Networks Wireless_Device                        | 1         | 1.82%   |
| Fujitsu Bluetooth Device                            | 1         | 1.82%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.82%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.82%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.82%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.82%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 64.67%  |
| Nvidia                           | 19        | 12.67%  |
| AMD                              | 18        | 12%     |
| VIA Technologies                 | 4         | 2.67%   |
| Creative Labs                    | 3         | 2%      |
| C-Media Electronics              | 3         | 2%      |
| Silicon Integrated Systems [SiS] | 2         | 1.33%   |
| ESS Technology                   | 2         | 1.33%   |
| ULi Electronics                  | 1         | 0.67%   |
| Ensoniq                          | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 16.27%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 6.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.41%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 4         | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.81%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.81%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 1.2%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.2%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.2%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.2%    |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                                             | 2         | 1.2%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.2%    |
| AMD High Definition Audio Controller                                                              | 2         | 1.2%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 2         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.2%    |
| VIA Technologies VT82C686 AC97 Audio Controller                                                   | 1         | 0.6%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.6%    |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 0.6%    |
| ULi Electronics HD Audio Controller                                                               | 1         | 0.6%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 47        | 31.13%  |
| SK hynix            | 30        | 19.87%  |
| Samsung Electronics | 20        | 13.25%  |
| Kingston            | 10        | 6.62%   |
| Unknown             | 10        | 6.62%   |
| Micron Technology   | 6         | 3.97%   |
| Ramaxel Technology  | 3         | 1.99%   |
| Corsair             | 3         | 1.99%   |
| Nanya Technology    | 2         | 1.32%   |
| G.Skill             | 2         | 1.32%   |
| Crucial             | 2         | 1.32%   |
| Unknown (ABCD)      | 1         | 0.66%   |
| Unknown (8A02)      | 1         | 0.66%   |
| Unknown (0x0DA2)    | 1         | 0.66%   |
| tigo                | 1         | 0.66%   |
| Smart               | 1         | 0.66%   |
| Patriot             | 1         | 0.66%   |
| Kllisre             | 1         | 0.66%   |
| Kingmax             | 1         | 0.66%   |
| GOODRAM             | 1         | 0.66%   |
| ff                  | 1         | 0.66%   |
| fef5                | 1         | 0.66%   |
| Elpida              | 1         | 0.66%   |
| Avant               | 1         | 0.66%   |
| Apacer              | 1         | 0.66%   |
| A-DATA Technology   | 1         | 0.66%   |
| 4ea5                | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 10        | 6.21%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 4         | 2.48%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 4         | 2.48%   |
| Unknown RAM Module 1024MB SODIMM DDR                     | 3         | 1.86%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s | 3         | 1.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 3         | 1.86%   |
| Unknown RAM Module 512MB SODIMM DDR                      | 2         | 1.24%   |
| Unknown RAM Module 2GB SODIMM SDRAM                      | 2         | 1.24%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 2         | 1.24%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 2         | 1.24%   |
| Unknown RAM Module 256MB SODIMM DRAM                     | 2         | 1.24%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s               | 2         | 1.24%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s             | 2         | 1.24%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s             | 2         | 1.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.24%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 2         | 1.24%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s         | 2         | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 1.24%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2         | 1.24%   |
| Unknown RAM Module 512MB SODIMM SDRAM                    | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM DRAM                     | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM DDR2                     | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM DDR 100MT/s              | 1         | 0.62%   |
| Unknown RAM Module 512MB DIMM SDRAM 333MT/s              | 1         | 0.62%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1         | 0.62%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1         | 0.62%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1         | 0.62%   |
| Unknown RAM Module 512MB DIMM                            | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s               | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s               | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR                        | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1         | 0.62%   |
| Unknown RAM Module 256MB DIMM SDRAM 333MT/s              | 1         | 0.62%   |
| Unknown RAM Module 256MB DIMM SDRAM                      | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 43        | 33.33%  |
| DDR2    | 25        | 19.38%  |
| SDRAM   | 20        | 15.5%   |
| DDR4    | 16        | 12.4%   |
| DDR     | 9         | 6.98%   |
| Unknown | 5         | 3.88%   |
| LPDDR4  | 4         | 3.1%    |
| DRAM    | 4         | 3.1%    |
| DDR5    | 2         | 1.55%   |
| LPDDR3  | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 67.72%  |
| DIMM         | 37        | 29.13%  |
| Unknown      | 3         | 2.36%   |
| Row Of Chips | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 47        | 31.97%  |
| 4096  | 29        | 19.73%  |
| 1024  | 29        | 19.73%  |
| 512   | 14        | 9.52%   |
| 8192  | 13        | 8.84%   |
| 16384 | 7         | 4.76%   |
| 256   | 4         | 2.72%   |
| 64    | 2         | 1.36%   |
| 32768 | 1         | 0.68%   |
| 232   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 18.98%  |
| 1600    | 25        | 18.25%  |
| 667     | 11        | 8.03%   |
| 1067    | 8         | 5.84%   |
| 800     | 8         | 5.84%   |
| 2667    | 7         | 5.11%   |
| 2400    | 7         | 5.11%   |
| 1333    | 7         | 5.11%   |
| 533     | 5         | 3.65%   |
| 1334    | 4         | 2.92%   |
| 4199    | 3         | 2.19%   |
| 3200    | 3         | 2.19%   |
| 975     | 3         | 2.19%   |
| 3534    | 2         | 1.46%   |
| 3266    | 2         | 1.46%   |
| 2048    | 2         | 1.46%   |
| 400     | 2         | 1.46%   |
| 333     | 2         | 1.46%   |
| 200     | 2         | 1.46%   |
| 5600    | 1         | 0.73%   |
| 4800    | 1         | 0.73%   |
| 3600    | 1         | 0.73%   |
| 2133    | 1         | 0.73%   |
| 1867    | 1         | 0.73%   |
| 1866    | 1         | 0.73%   |
| 266     | 1         | 0.73%   |
| 100     | 1         | 0.73%   |

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
| Chicony Electronics                    | 15        | 22.06%  |
| Microdia                               | 6         | 8.82%   |
| IMC Networks                           | 6         | 8.82%   |
| Suyin                                  | 5         | 7.35%   |
| Apple                                  | 5         | 7.35%   |
| Realtek Semiconductor                  | 4         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.88%   |
| Bison Electronics                      | 4         | 5.88%   |
| Sunplus Innovation Technology          | 3         | 4.41%   |
| Pixart Imaging                         | 3         | 4.41%   |
| Syntek                                 | 2         | 2.94%   |
| Silicon Motion                         | 2         | 2.94%   |
| Lenovo                                 | 2         | 2.94%   |
| Z-Star Microelectronics                | 1         | 1.47%   |
| Lite-On Technology                     | 1         | 1.47%   |
| Jieli Technology                       | 1         | 1.47%   |
| Importek                               | 1         | 1.47%   |
| Generalplus Technology                 | 1         | 1.47%   |
| Alcor Micro                            | 1         | 1.47%   |
| Acer                                   | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 3         | 4.41%   |
| Microdia Sonix USB 2.0 Camera                  | 3         | 4.41%   |
| Apple Built-in iSight                          | 3         | 4.41%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 2.94%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.94%   |
| Chicony HD WebCam                              | 2         | 2.94%   |
| Bison BisonCam, NB Pro                         | 2         | 2.94%   |
| Z-Star Vimicro USB Camera (Altair)             | 1         | 1.47%   |
| Syntek Integrated Camera                       | 1         | 1.47%   |
| Syntek HP Webcam                               | 1         | 1.47%   |
| Suyin USB2.0 UVC 1.3M WebCam                   | 1         | 1.47%   |
| Suyin USB 2.0 Camera                           | 1         | 1.47%   |
| Suyin Laptop_Integrated_Webcam_2HDM            | 1         | 1.47%   |
| Suyin Integrated_Webcam_HD                     | 1         | 1.47%   |
| Suyin Acer/Lenovo Webcam [CN0316]              | 1         | 1.47%   |
| Sunplus HD WebCam                              | 1         | 1.47%   |
| Silicon Motion Lenovo EasyCamera               | 1         | 1.47%   |
| Silicon Motion HP Webcam-101 Integrated Camera | 1         | 1.47%   |
| Realtek USB2.0 VGA UVC WebCam                  | 1         | 1.47%   |
| Realtek Integrated_Webcam_HD                   | 1         | 1.47%   |
| Realtek Integrated Webcam HD                   | 1         | 1.47%   |
| Realtek HD WebCam                              | 1         | 1.47%   |
| Microdia Integrated_Webcam_5M                  | 1         | 1.47%   |
| Microdia Integrated Webcam                     | 1         | 1.47%   |
| Microdia Integrated Camera                     | 1         | 1.47%   |
| Lite-On HP TrueVision HD Camera                | 1         | 1.47%   |
| Lenovo Integrated Webcam                       | 1         | 1.47%   |
| Lenovo CNF7237&CNF7238                         | 1         | 1.47%   |
| Jieli USB PHY 2.0                              | 1         | 1.47%   |
| Importek FJ Camera                             | 1         | 1.47%   |
| IMC Networks USB 2.0 UVC VGA WebCam            | 1         | 1.47%   |
| IMC Networks TOSHIBA Web Camera - HD           | 1         | 1.47%   |
| Generalplus 808 Camera #9 (web-cam mode)       | 1         | 1.47%   |
| Chicony Webcam-101                             | 1         | 1.47%   |
| Chicony VGA 30fps UVC Webcam                   | 1         | 1.47%   |
| Chicony USB2.0 HD UVC WebCam                   | 1         | 1.47%   |
| Chicony Integrated HP HD Webcam                | 1         | 1.47%   |
| Chicony Integrated Camera                      | 1         | 1.47%   |
| Chicony HP Webcam                              | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 6         | 60%     |
| Validity Sensors | 2         | 20%     |
| Upek             | 2         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
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


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 75%     |
| O2 Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 89        | 66.92%  |
| 1     | 31        | 23.31%  |
| 2     | 9         | 6.77%   |
| 3     | 3         | 2.26%   |
| 4     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 56.14%  |
| Fingerprint reader       | 10        | 17.54%  |
| Sound                    | 3         | 5.26%   |
| Communication controller | 3         | 5.26%   |
| Chipcard                 | 3         | 5.26%   |
| Multimedia controller    | 2         | 3.51%   |
| Net/wireless             | 1         | 1.75%   |
| Net/ethernet             | 1         | 1.75%   |
| Modem                    | 1         | 1.75%   |
| Camera                   | 1         | 1.75%   |


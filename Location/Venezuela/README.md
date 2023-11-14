Linux in Venezuela - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Venezuela/Desktop/README.md) and [notebooks](/Location/Venezuela/Notebook/README.md).

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

Total: 558

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [3e5d819c23](https://linux-hardware.org/?probe=3e5d819c23) | Nov 03, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [9fb5c6d4d3](https://linux-hardware.org/?probe=9fb5c6d4d3) | Nov 03, 2023 |
| Intel         | powered classmate PC        | Notebook    | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| VIT           | P1400                       | Notebook    | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| ASRock        | D1800M                      | Desktop     | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| HP            | 18E5                        | Desktop     | [95cc2c3a9c](https://linux-hardware.org/?probe=95cc2c3a9c) | Oct 22, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [eb8522ff13](https://linux-hardware.org/?probe=eb8522ff13) | Oct 21, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [deb1dc3eaa](https://linux-hardware.org/?probe=deb1dc3eaa) | Oct 21, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| Intel         | D945GTP AAC97837-309        | Other       | [49d064bc5d](https://linux-hardware.org/?probe=49d064bc5d) | Oct 15, 2023 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [447110886e](https://linux-hardware.org/?probe=447110886e) | Oct 14, 2023 |
| Gateway       | NV57H                       | Notebook    | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [3b45c6b974](https://linux-hardware.org/?probe=3b45c6b974) | Oct 08, 2023 |
| Lenovo        | ThinkCentre A57 9702AB7     | Desktop     | [3237019933](https://linux-hardware.org/?probe=3237019933) | Oct 07, 2023 |
| HP            | Compaq Presario C768        | Notebook    | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| VIT           | P2400                       | Notebook    | [1896f1962a](https://linux-hardware.org/?probe=1896f1962a) | Oct 06, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [def181c0e4](https://linux-hardware.org/?probe=def181c0e4) | Sep 26, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| HP            | Pavilion m6                 | Notebook    | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [a0abff6d5f](https://linux-hardware.org/?probe=a0abff6d5f) | Sep 08, 2023 |
| VIT           | M2400-01                    | Mini pc     | [8d658beb19](https://linux-hardware.org/?probe=8d658beb19) | Sep 07, 2023 |
| VIT           | P2400                       | Notebook    | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| VENEZOLANA... | VIT P2460-02                | Notebook    | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| Biostar       | G41D3                       | Desktop     | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [71b31f4a43](https://linux-hardware.org/?probe=71b31f4a43) | Aug 31, 2023 |
| Panasonic     | CF-31RECAXDR                | Notebook    | [2c021f93de](https://linux-hardware.org/?probe=2c021f93de) | Aug 30, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| Intel         | DG41TY AAE47335-301         | Desktop     | [1f8897e1a2](https://linux-hardware.org/?probe=1f8897e1a2) | Aug 29, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [dd6f1d7cac](https://linux-hardware.org/?probe=dd6f1d7cac) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| Biostar       | G41D3C                      | Desktop     | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Lenovo        | ThinkCentre M72e 3597A56    | Desktop     | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| VIT           | P2402                       | Notebook    | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | Notebook    | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| Inspur        | H110H4-EM                   | Desktop     | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Siragon       | MN-50                       | Notebook    | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [ae0cada933](https://linux-hardware.org/?probe=ae0cada933) | Aug 07, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [566421a903](https://linux-hardware.org/?probe=566421a903) | Jul 21, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [be9d638406](https://linux-hardware.org/?probe=be9d638406) | Jul 21, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [67db76ffed](https://linux-hardware.org/?probe=67db76ffed) | Jul 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | Desktop     | [90a2c4e2d0](https://linux-hardware.org/?probe=90a2c4e2d0) | Jul 18, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | Notebook    | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3734a0a9bf](https://linux-hardware.org/?probe=3734a0a9bf) | Jul 07, 2023 |
| HP            | 0A80h                       | Desktop     | [54635d0b1b](https://linux-hardware.org/?probe=54635d0b1b) | Jul 05, 2023 |
| Acer          | Aspire 6930                 | Notebook    | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| HP            | 0A80h                       | Desktop     | [83691b49d2](https://linux-hardware.org/?probe=83691b49d2) | Jul 03, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| VIT           | P2423                       | Notebook    | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | Desktop     | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [722b363829](https://linux-hardware.org/?probe=722b363829) | Jun 17, 2023 |
| Intel         | powered classmate PC        | Notebook    | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [2e0c1fbe0d](https://linux-hardware.org/?probe=2e0c1fbe0d) | Jun 06, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [5832b8b801](https://linux-hardware.org/?probe=5832b8b801) | Jun 06, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ef4a96955c](https://linux-hardware.org/?probe=ef4a96955c) | Jun 01, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a106c6a98a](https://linux-hardware.org/?probe=a106c6a98a) | Jun 01, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [c207b5f41c](https://linux-hardware.org/?probe=c207b5f41c) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| VIT           | P2400                       | Notebook    | [dca6cca8a2](https://linux-hardware.org/?probe=dca6cca8a2) | May 26, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| VIT           | M2400-01                    | Mini pc     | [64e5a3aa50](https://linux-hardware.org/?probe=64e5a3aa50) | May 16, 2023 |
| Lenovo        | ThinkCentre A57 9702AB7     | Desktop     | [f045709958](https://linux-hardware.org/?probe=f045709958) | May 12, 2023 |
| Intel         | H55AD17                     | Desktop     | [7d393c3814](https://linux-hardware.org/?probe=7d393c3814) | May 11, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [974c00cb61](https://linux-hardware.org/?probe=974c00cb61) | May 09, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7f1bc5a99c](https://linux-hardware.org/?probe=7f1bc5a99c) | May 06, 2023 |
| ASRock        | 945GCM-S                    | Desktop     | [940d88bfce](https://linux-hardware.org/?probe=940d88bfce) | May 06, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [fa6f088b8d](https://linux-hardware.org/?probe=fa6f088b8d) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| HP            | 1998                        | Desktop     | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| Lenovo        | 3000 V200 07642XU           | Notebook    | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| Biostar       | H61MHV                      | Desktop     | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [fdb331baab](https://linux-hardware.org/?probe=fdb331baab) | Apr 10, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| VIT           | P2402                       | Notebook    | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Biostar       | G41D3                       | Desktop     | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| Notebook      | W54BL                       | Notebook    | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [615409e462](https://linux-hardware.org/?probe=615409e462) | Mar 12, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [cc778f466a](https://linux-hardware.org/?probe=cc778f466a) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [d94d167f13](https://linux-hardware.org/?probe=d94d167f13) | Mar 11, 2023 |
| Pegatron      | H36Y                        | Notebook    | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | Notebook    | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | Notebook    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [9a9f442174](https://linux-hardware.org/?probe=9a9f442174) | Mar 03, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | Notebook    | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| HP            | 1495                        | Desktop     | [627c584065](https://linux-hardware.org/?probe=627c584065) | Feb 09, 2023 |
| Dell          | 0YF8P5 A00                  | Desktop     | [4bb4dd8a98](https://linux-hardware.org/?probe=4bb4dd8a98) | Feb 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [76be6a1404](https://linux-hardware.org/?probe=76be6a1404) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [9b0f53b46c](https://linux-hardware.org/?probe=9b0f53b46c) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | EP35-DS3L                   | Desktop     | [5be0362f3e](https://linux-hardware.org/?probe=5be0362f3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | Notebook    | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | Notebook    | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [c48a8fe525](https://linux-hardware.org/?probe=c48a8fe525) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [28c3cf967d](https://linux-hardware.org/?probe=28c3cf967d) | Jan 16, 2023 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| Pegatron      | B74                         | Notebook    | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4ed227f8af](https://linux-hardware.org/?probe=4ed227f8af) | Jan 09, 2023 |
| Intel         | powered classmate PC        | Tablet      | [c35a8d75ce](https://linux-hardware.org/?probe=c35a8d75ce) | Jan 05, 2023 |
| Intel         | powered classmate PC        | Tablet      | [dbca24d9e5](https://linux-hardware.org/?probe=dbca24d9e5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de0a127527](https://linux-hardware.org/?probe=de0a127527) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [515785c9c4](https://linux-hardware.org/?probe=515785c9c4) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a656b96d5f](https://linux-hardware.org/?probe=a656b96d5f) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6275a6ee8f](https://linux-hardware.org/?probe=6275a6ee8f) | Dec 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e1a4335a71](https://linux-hardware.org/?probe=e1a4335a71) | Dec 01, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | Tablet      | [44cc912fe3](https://linux-hardware.org/?probe=44cc912fe3) | Nov 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [906ad9a3c1](https://linux-hardware.org/?probe=906ad9a3c1) | Nov 25, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [b252a902f4](https://linux-hardware.org/?probe=b252a902f4) | Nov 24, 2022 |
| VIT           | M2400-01                    | Mini pc     | [4b590aa76a](https://linux-hardware.org/?probe=4b590aa76a) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3469b1e624](https://linux-hardware.org/?probe=3469b1e624) | Nov 07, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Intel         | H61                         | Desktop     | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| Intel         | powered classmate PC        | Tablet      | [d047cd6e73](https://linux-hardware.org/?probe=d047cd6e73) | Oct 22, 2022 |
| Google        | Candy                       | Notebook    | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | Notebook    | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| ECS           | A890GXM-A2                  | Desktop     | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | Notebook    | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| Intel         | powered classmate PC        | Tablet      | [1abacce964](https://linux-hardware.org/?probe=1abacce964) | Jul 06, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Google        | Cyan                        | Notebook    | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | Desktop     | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | Notebook    | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Lenovo        | 11051CS ThinkServer TS13... | Desktop     | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| IP3 Tech      | TB20                        | Desktop     | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Intel         | H61                         | Desktop     | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| VIT           | P2402                       | Notebook    | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur        | Computer All in one PC V... | Desktop     | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | NP3020M3                    | Server      | [9fbb87a829](https://linux-hardware.org/?probe=9fbb87a829) | Mar 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron      | 2ACC                        | Desktop     | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Intel         | powered classmate PC        | Tablet      | [a2b7a04dfa](https://linux-hardware.org/?probe=a2b7a04dfa) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | Notebook    | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| ECS           | KAM1-I                      | Desktop     | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASRock        | A55M-HVS                    | Desktop     | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| ASUSTek       | P6X58-E PRO                 | Desktop     | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| VIT           | M2421                       | Notebook    | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP            | 3398                        | Desktop     | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Lenovo        | B40-70 20392                | Notebook    | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | Notebook    | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP            | 1495                        | Desktop     | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| Clevo         | W54xEU                      | Notebook    | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | Notebook    | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | Notebook    | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| VIT           | P2400                       | Notebook    | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar       | G41D3                       | Desktop     | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP            | 3397                        | Desktop     | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | Desktop     | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS           | Livermore                   | Desktop     | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| VIT           | P2400                       | Notebook    | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS           | G31T-M7                     | Desktop     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M55E 9645BN2    | Desktop     | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| VIT           | P1400                       | Notebook    | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| Biostar       | G41D3C                      | Desktop     | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | Notebook    | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | Notebook    | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | Notebook    | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Acer          | Aspire 4935                 | Notebook    | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 1495                        | Desktop     | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell          | 0GX297                      | Desktop     | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Intel         | S5500BC E25124-407          | Server      | [fe3d758c20](https://linux-hardware.org/?probe=fe3d758c20) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP            | 1493                        | Desktop     | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP            | 1495                        | Desktop     | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | Notebook    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Intel         | powered classmate PC        | Tablet      | [4f4efbc5c6](https://linux-hardware.org/?probe=4f4efbc5c6) | Sep 06, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar       | N68S3B                      | Desktop     | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| HP            | Presario V2000 (EW997LA#... | Notebook    | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | Notebook    | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI           | K9N2 Diamond                | Desktop     | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [f2fdb4f618](https://linux-hardware.org/?probe=f2fdb4f618) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| VIT           | M2421                       | Notebook    | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| Intel         | powered classmate PC        | Notebook    | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | Notebook    | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Standard      | AHV                         | All in one  | [989175dbdc](https://linux-hardware.org/?probe=989175dbdc) | Jun 08, 2020 |
| Standard      | AHV                         | All in one  | [f0bd9ac2e1](https://linux-hardware.org/?probe=f0bd9ac2e1) | Jun 07, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| VIT           | P3400                       | Notebook    | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| VIT           | P3400                       | Notebook    | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | Notebook    | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b55d1daea5](https://linux-hardware.org/?probe=b55d1daea5) | May 11, 2020 |
| VIT           | P2402                       | Notebook    | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| VIT           | P3400                       | Notebook    | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | Notebook    | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | Notebook    | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo        | ThinkCentre A58 7515A33     | Desktop     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | Notebook    | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| Acer          | Aspire Z3730                | All in one  | [24d42a520e](https://linux-hardware.org/?probe=24d42a520e) | Mar 03, 2020 |
| VIT           | P2402                       | Notebook    | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | ThinkCentre XXXX 8705A84    | Desktop     | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [e79318e87d](https://linux-hardware.org/?probe=e79318e87d) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [3e6bc93a39](https://linux-hardware.org/?probe=3e6bc93a39) | Jan 31, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b6ba4394f7](https://linux-hardware.org/?probe=b6ba4394f7) | Jan 29, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| VIT           | Aptio CRB                   | Mini pc     | [d999c674f1](https://linux-hardware.org/?probe=d999c674f1) | Dec 23, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [41131b1d8e](https://linux-hardware.org/?probe=41131b1d8e) | Dec 23, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | Desktop     | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [2d4b473d59](https://linux-hardware.org/?probe=2d4b473d59) | Dec 01, 2019 |
| Pegatron      | 2A73h                       | Desktop     | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [aba5fa885d](https://linux-hardware.org/?probe=aba5fa885d) | Nov 25, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn       | 8657MF-series               | Desktop     | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Intel         | powered classmate PC        | Tablet      | [05f47d610a](https://linux-hardware.org/?probe=05f47d610a) | Aug 22, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| Pegatron      | 2AF0                        | Desktop     | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo        | H220 10028                  | Desktop     | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| HP            | Pavilion dv4                | Notebook    | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel         | powered classmate PC        | Notebook    | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | Notebook    | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |
| ASRock        | 945GCM-S                    | Desktop     | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Venezuela/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Debian 11          | 37        | 9.05%   |
| Ubuntu 22.04       | 25        | 6.11%   |
| Ubuntu 20.04       | 25        | 6.11%   |
| OpenMandriva 4.3   | 18        | 4.4%    |
| Ubuntu 18.04       | 16        | 3.91%   |
| OpenMandriva 23.03 | 12        | 2.93%   |
| Zorin 16           | 11        | 2.69%   |
| OpenMandriva 4.2   | 11        | 2.69%   |
| OpenMandriva 23.08 | 10        | 2.44%   |
| Debian 10          | 10        | 2.44%   |
| Linux Mint 21.1    | 9         | 2.2%    |
| Linux Mint 20.3    | 9         | 2.2%    |
| KDE neon 20.04     | 9         | 2.2%    |
| Xubuntu 18.04      | 7         | 1.71%   |
| OpenMandriva 23.01 | 7         | 1.71%   |
| Kubuntu 20.04      | 6         | 1.47%   |
| Debian 12          | 6         | 1.47%   |
| ROSA R9            | 5         | 1.22%   |
| ROSA R11           | 5         | 1.22%   |
| Linux Mint 21.2    | 5         | 1.22%   |
| Linux Mint 20      | 5         | 1.22%   |
| Linux Mint 19.3    | 5         | 1.22%   |
| ArcoLinux Rolling  | 5         | 1.22%   |
| Arch Rolling       | 5         | 1.22%   |
| Zorin 15           | 4         | 0.98%   |
| Ubuntu MATE 19.10  | 4         | 0.98%   |
| Ubuntu 19.10       | 4         | 0.98%   |
| KDE neon 22.04     | 4         | 0.98%   |
| Fedora 38          | 4         | 0.98%   |
| Fedora 35          | 4         | 0.98%   |
| Xubuntu 22.04      | 3         | 0.73%   |
| Ubuntu 21.10       | 3         | 0.73%   |
| OpenMandriva 4.50  | 3         | 0.73%   |
| MX 21              | 3         | 0.73%   |
| Manjaro            | 3         | 0.73%   |
| Linux Mint 20.1    | 3         | 0.73%   |
| KDE neon 18.04     | 3         | 0.73%   |
| Fedora 36          | 3         | 0.73%   |
| Xubuntu 20.04      | 2         | 0.49%   |
| Xubuntu 16.04      | 2         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 77        | 19.59%  |
| OpenMandriva | 60        | 15.27%  |
| Debian       | 55        | 13.99%  |
| Linux Mint   | 39        | 9.92%   |
| Zorin        | 15        | 3.82%   |
| ROSA         | 15        | 3.82%   |
| KDE neon     | 15        | 3.82%   |
| Fedora       | 15        | 3.82%   |
| Xubuntu      | 14        | 3.56%   |
| Kubuntu      | 9         | 2.29%   |
| Manjaro      | 8         | 2.04%   |
| Ubuntu MATE  | 7         | 1.78%   |
| Arch         | 7         | 1.78%   |
| Elementary   | 6         | 1.53%   |
| Pop!_OS      | 5         | 1.27%   |
| ArcoLinux    | 5         | 1.27%   |
| MX           | 4         | 1.02%   |
| Kali         | 4         | 1.02%   |
| Ubuntu Unity | 3         | 0.76%   |
| Nobara       | 3         | 0.76%   |
| LMDE         | 3         | 0.76%   |
| Xero         | 2         | 0.51%   |
| Solus        | 2         | 0.51%   |
| Q4OS         | 2         | 0.51%   |
| openSUSE     | 2         | 0.51%   |
| Lubuntu      | 2         | 0.51%   |
| Garuda Linux | 2         | 0.51%   |
| Feren OS     | 2         | 0.51%   |
| Sparky       | 1         | 0.25%   |
| PCLinuxOS    | 1         | 0.25%   |
| Linux Lite   | 1         | 0.25%   |
| Frnsf        | 1         | 0.25%   |
| Endless      | 1         | 0.25%   |
| EndeavourOS  | 1         | 0.25%   |
| Deepin       | 1         | 0.25%   |
| BunsenLabs   | 1         | 0.25%   |
| Alpine       | 1         | 0.25%   |
| AlmaLinux    | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 4.04%   |
| 6.2.6-desktop-1omv2390          | 12        | 2.69%   |
| 5.10.14-desktop-1omv4002        | 11        | 2.47%   |
| 5.4.0-42-generic                | 8         | 1.79%   |
| 6.1.1-desktop-1omv2290          | 7         | 1.57%   |
| 6.4.11-desktop-1omv2390         | 6         | 1.35%   |
| 5.3.0-40-generic                | 6         | 1.35%   |
| 5.15.0-56-generic               | 6         | 1.35%   |
| 5.15.0-46-generic               | 6         | 1.35%   |
| 5.19.0-41-generic               | 5         | 1.12%   |
| 5.10.0-23-amd64                 | 5         | 1.12%   |
| 6.4.8-desktop-2omv2390          | 4         | 0.9%    |
| 6.2.0-26-generic                | 4         | 0.9%    |
| 5.4.0-77-generic                | 4         | 0.9%    |
| 5.15.0-76-generic               | 4         | 0.9%    |
| 5.15.0-67-generic               | 4         | 0.9%    |
| 5.13.0-39-generic               | 4         | 0.9%    |
| 5.10.0-16-amd64                 | 4         | 0.9%    |
| 5.10.0-13-amd64                 | 4         | 0.9%    |
| 5.10.0-11-amd64                 | 4         | 0.9%    |
| 5.0.0-37-generic                | 4         | 0.9%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 0.9%    |
| 4.19.0-17-amd64                 | 4         | 0.9%    |
| 6.2.0-32-generic                | 3         | 0.67%   |
| 5.4.0-74-generic                | 3         | 0.67%   |
| 5.4.0-73-generic                | 3         | 0.67%   |
| 5.4.0-52-generic                | 3         | 0.67%   |
| 5.3.0-29-generic                | 3         | 0.67%   |
| 5.15.0-58-generic               | 3         | 0.67%   |
| 5.15.0-52-generic               | 3         | 0.67%   |
| 5.11.0-37-generic               | 3         | 0.67%   |
| 5.10.0-21-amd64                 | 3         | 0.67%   |
| 4.15.0-48-generic               | 3         | 0.67%   |
| 6.4.11-arch2-1                  | 2         | 0.45%   |
| 6.2.0-35-generic                | 2         | 0.45%   |
| 6.2.0-34-generic                | 2         | 0.45%   |
| 6.1.0-10-amd64                  | 2         | 0.45%   |
| 5.8.0-63-generic                | 2         | 0.45%   |
| 5.8.0-55-generic                | 2         | 0.45%   |
| 5.8.0-44-generic                | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 12.05%  |
| 5.15.0  | 47        | 11.33%  |
| 5.10.0  | 39        | 9.4%    |
| 4.15.0  | 24        | 5.78%   |
| 5.13.0  | 19        | 4.58%   |
| 5.16.7  | 18        | 4.34%   |
| 6.2.0   | 15        | 3.61%   |
| 5.19.0  | 14        | 3.37%   |
| 6.2.6   | 12        | 2.89%   |
| 5.3.0   | 12        | 2.89%   |
| 4.19.0  | 12        | 2.89%   |
| 5.10.14 | 11        | 2.65%   |
| 5.8.0   | 10        | 2.41%   |
| 5.11.0  | 9         | 2.17%   |
| 6.4.11  | 8         | 1.93%   |
| 6.1.1   | 7         | 1.69%   |
| 5.0.0   | 7         | 1.69%   |
| 6.1.0   | 6         | 1.45%   |
| 4.9.20  | 5         | 1.2%    |
| 6.4.8   | 4         | 0.96%   |
| 6.2.12  | 3         | 0.72%   |
| 5.14.10 | 3         | 0.72%   |
| 6.4.6   | 2         | 0.48%   |
| 6.4.3   | 2         | 0.48%   |
| 6.4.2   | 2         | 0.48%   |
| 5.18.0  | 2         | 0.48%   |
| 5.15.6  | 2         | 0.48%   |
| 5.15.2  | 2         | 0.48%   |
| 5.12.4  | 2         | 0.48%   |
| 4.9.0   | 2         | 0.48%   |
| 4.18.0  | 2         | 0.48%   |
| 6.5.7   | 1         | 0.24%   |
| 6.5.1   | 1         | 0.24%   |
| 6.4.7   | 1         | 0.24%   |
| 6.4.12  | 1         | 0.24%   |
| 6.3.8   | 1         | 0.24%   |
| 6.3.6   | 1         | 0.24%   |
| 6.3.5   | 1         | 0.24%   |
| 6.3.0   | 1         | 0.24%   |
| 6.1.8   | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 57        | 13.87%  |
| 5.10    | 57        | 13.87%  |
| 5.4     | 52        | 12.65%  |
| 6.2     | 30        | 7.3%    |
| 4.15    | 24        | 5.84%   |
| 5.13    | 22        | 5.35%   |
| 6.4     | 20        | 4.87%   |
| 5.16    | 20        | 4.87%   |
| 6.1     | 17        | 4.14%   |
| 5.19    | 16        | 3.89%   |
| 5.8     | 13        | 3.16%   |
| 5.3     | 12        | 2.92%   |
| 4.19    | 12        | 2.92%   |
| 5.11    | 9         | 2.19%   |
| 5.0     | 7         | 1.7%    |
| 4.9     | 7         | 1.7%    |
| 6.3     | 4         | 0.97%   |
| 6.0     | 4         | 0.97%   |
| 5.17    | 4         | 0.97%   |
| 5.14    | 4         | 0.97%   |
| 5.6     | 3         | 0.73%   |
| 5.18    | 3         | 0.73%   |
| 5.12    | 3         | 0.73%   |
| 6.5     | 2         | 0.49%   |
| 5.9     | 2         | 0.49%   |
| 4.18    | 2         | 0.49%   |
| 5.7     | 1         | 0.24%   |
| 5.5     | 1         | 0.24%   |
| 4.4     | 1         | 0.24%   |
| 4.13    | 1         | 0.24%   |
| 4.1     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 350       | 92.35%  |
| i686   | 29        | 7.65%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 123       | 30.75%  |
| KDE5            | 103       | 25.75%  |
| XFCE            | 48        | 12%     |
| X-Cinnamon      | 28        | 7%      |
| Unknown         | 27        | 6.75%   |
| MATE            | 15        | 3.75%   |
| KDE             | 12        | 3%      |
| LXQt            | 8         | 2%      |
| KDE4            | 7         | 1.75%   |
| Pantheon        | 5         | 1.25%   |
| LXDE            | 5         | 1.25%   |
| Cinnamon        | 5         | 1.25%   |
| Unity           | 3         | 0.75%   |
| GNOME Classic   | 2         | 0.5%    |
| Budgie          | 2         | 0.5%    |
| xmonad          | 1         | 0.25%   |
| Trinity         | 1         | 0.25%   |
| Openbox         | 1         | 0.25%   |
| i3              | 1         | 0.25%   |
| GNOME Flashback | 1         | 0.25%   |
| Deepin          | 1         | 0.25%   |
| awesome         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 310       | 80.1%   |
| Wayland | 68        | 17.57%  |
| Unknown | 6         | 1.55%   |
| Tty     | 3         | 0.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 141       | 36.06%  |
| SDDM    | 93        | 23.79%  |
| LightDM | 53        | 13.55%  |
| GDM3    | 42        | 10.74%  |
| GDM     | 42        | 10.74%  |
| TDM     | 11        | 2.81%   |
| KDM     | 7         | 1.79%   |
| SLiM    | 2         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 231       | 59.23%  |
| en_US   | 90        | 23.08%  |
| Unknown | 26        | 6.67%   |
| es_ES   | 23        | 5.9%    |
| es_MX   | 10        | 2.56%   |
| es_US   | 4         | 1.03%   |
| C       | 3         | 0.77%   |
| es_CO   | 1         | 0.26%   |
| en_CA   | 1         | 0.26%   |
| de_DE   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 277       | 72.51%  |
| EFI  | 105       | 27.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 289       | 74.68%  |
| Overlay | 47        | 12.14%  |
| Btrfs   | 24        | 6.2%    |
| Tmpfs   | 9         | 2.33%   |
| Unknown | 8         | 2.07%   |
| Xfs     | 6         | 1.55%   |
| Ext2    | 2         | 0.52%   |
| XXX4    | 1         | 0.26%   |
| Ext3    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 157       | 40.57%  |
| MBR     | 116       | 29.97%  |
| GPT     | 114       | 29.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 315       | 81.61%  |
| Yes       | 71        | 18.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 234       | 61.26%  |
| Yes       | 148       | 38.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 43        | 11.41%  |
| Hewlett-Packard                          | 39        | 10.34%  |
| Dell                                     | 37        | 9.81%   |
| ASRock                                   | 33        | 8.75%   |
| Intel                                    | 32        | 8.49%   |
| VIT                                      | 31        | 8.22%   |
| ASUSTek Computer                         | 24        | 6.37%   |
| ECS                                      | 18        | 4.77%   |
| Pegatron                                 | 17        | 4.51%   |
| Gigabyte Technology                      | 15        | 3.98%   |
| Biostar                                  | 12        | 3.18%   |
| Acer                                     | 12        | 3.18%   |
| MSI                                      | 8         | 2.12%   |
| Foxconn                                  | 7         | 1.86%   |
| langchao                                 | 6         | 1.59%   |
| Unknown                                  | 6         | 1.59%   |
| Apple                                    | 4         | 1.06%   |
| Siragon                                  | 3         | 0.8%    |
| Shanghai Zhaoxin Semiconductor           | 3         | 0.8%    |
| Inspur                                   | 3         | 0.8%    |
| Google                                   | 3         | 0.8%    |
| Toshiba                                  | 2         | 0.53%   |
| Samsung Electronics                      | 2         | 0.53%   |
| Notebook                                 | 2         | 0.53%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.27%   |
| UNIQCELL                                 | 1         | 0.27%   |
| Standard                                 | 1         | 0.27%   |
| Sony                                     | 1         | 0.27%   |
| Soncview                                 | 1         | 0.27%   |
| Panasonic                                | 1         | 0.27%   |
| Microsoft                                | 1         | 0.27%   |
| IP3 Tech                                 | 1         | 0.27%   |
| IBM                                      | 1         | 0.27%   |
| GPU Company                              | 1         | 0.27%   |
| Gateway                                  | 1         | 0.27%   |
| Exo                                      | 1         | 0.27%   |
| Clevo                                    | 1         | 0.27%   |
| AVITA                                    | 1         | 0.27%   |
| Alienware                                | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel powered classmate PC                | 13        | 3.45%   |
| ECS H61H2-CM                              | 10        | 2.65%   |
| VIT P2400                                 | 8         | 2.12%   |
| ASRock G41M-VS3                           | 7         | 1.86%   |
| langchao 12345                            | 6         | 1.59%   |
| Unknown                                   | 6         | 1.59%   |
| VIT P2402                                 | 5         | 1.33%   |
| ASRock N68-VS3 UCC                        | 4         | 1.06%   |
| VIT P3400                                 | 3         | 0.8%    |
| VIT P1400                                 | 3         | 0.8%    |
| VIT M2420                                 | 3         | 0.8%    |
| VIT M2400-01                              | 3         | 0.8%    |
| Shanghai Zhaoxin ZXE CRB                  | 3         | 0.8%    |
| Pegatron Compaq dx2400 Microtower         | 3         | 0.8%    |
| HP Compaq 8200 Elite SFF PC               | 3         | 0.8%    |
| Biostar G41D3                             | 3         | 0.8%    |
| ASRock N68C-S UCC                         | 3         | 0.8%    |
| VIT M2421                                 | 2         | 0.53%   |
| VIT Aptio CRB                             | 2         | 0.53%   |
| Pegatron IPM41-D3                         | 2         | 0.53%   |
| Lenovo ThinkCentre A57 9702AB7            | 2         | 0.53%   |
| Lenovo IdeaPad S100c 20194                | 2         | 0.53%   |
| Lenovo 3000 N200 0769ARS                  | 2         | 0.53%   |
| Intel H61                                 | 2         | 0.53%   |
| HP Pavilion dv5                           | 2         | 0.53%   |
| HP EliteDesk 800 G1 USDT                  | 2         | 0.53%   |
| HP Compaq Presario C700                   | 2         | 0.53%   |
| Google Candy                              | 2         | 0.53%   |
| Gigabyte 970A-DS3P                        | 2         | 0.53%   |
| ECS H61H2-MV                              | 2         | 0.53%   |
| ECS G31T-M7                               | 2         | 0.53%   |
| Dell OptiPlex 9020                        | 2         | 0.53%   |
| Dell OptiPlex 790                         | 2         | 0.53%   |
| Dell Inspiron 1545                        | 2         | 0.53%   |
| Biostar G41D3C                            | 2         | 0.53%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM | 2         | 0.53%   |
| ASRock Wolfdale1333-D667                  | 2         | 0.53%   |
| ASRock 945GCM-S                           | 2         | 0.53%   |
| Apple iMac11,2                            | 2         | 0.53%   |
| Acer Aspire 4739Z                         | 2         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 14        | 3.71%   |
| Intel powered        | 13        | 3.45%   |
| HP Compaq            | 12        | 3.18%   |
| Lenovo ThinkCentre   | 11        | 2.92%   |
| Lenovo IdeaPad       | 11        | 2.92%   |
| Acer Aspire          | 11        | 2.92%   |
| ECS H61H2-CM         | 10        | 2.65%   |
| HP Pavilion          | 9         | 2.39%   |
| VIT P2400            | 8         | 2.12%   |
| Lenovo ThinkPad      | 7         | 1.86%   |
| Dell OptiPlex        | 7         | 1.86%   |
| Dell Latitude        | 7         | 1.86%   |
| ASRock G41M-VS3      | 7         | 1.86%   |
| langchao 12345       | 6         | 1.59%   |
| Dell Vostro          | 6         | 1.59%   |
| Unknown              | 6         | 1.59%   |
| VIT P2402            | 5         | 1.33%   |
| ASUS ASUS            | 5         | 1.33%   |
| ASRock N68-VS3       | 5         | 1.33%   |
| Pegatron Compaq      | 4         | 1.06%   |
| Lenovo 3000          | 4         | 1.06%   |
| HP Laptop            | 4         | 1.06%   |
| VIT P3400            | 3         | 0.8%    |
| VIT P1400            | 3         | 0.8%    |
| VIT M2420            | 3         | 0.8%    |
| VIT M2400-01         | 3         | 0.8%    |
| Shanghai Zhaoxin ZXE | 3         | 0.8%    |
| HP EliteDesk         | 3         | 0.8%    |
| Biostar G41D3        | 3         | 0.8%    |
| ASRock N68C-S        | 3         | 0.8%    |
| VIT M2421            | 2         | 0.53%   |
| VIT Aptio            | 2         | 0.53%   |
| Pegatron IPM41-D3    | 2         | 0.53%   |
| Lenovo Legion        | 2         | 0.53%   |
| Intel H61            | 2         | 0.53%   |
| Intel DG41TY         | 2         | 0.53%   |
| HP Presario          | 2         | 0.53%   |
| HP ENVY              | 2         | 0.53%   |
| HP EliteBook         | 2         | 0.53%   |
| Google Candy         | 2         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 64        | 16.98%  |
| 2010    | 49        | 13%     |
| 2012    | 41        | 10.88%  |
| 2013    | 30        | 7.96%   |
| 2008    | 30        | 7.96%   |
| 2007    | 24        | 6.37%   |
| 2014    | 23        | 6.1%    |
| 2022    | 16        | 4.24%   |
| 2020    | 16        | 4.24%   |
| 2009    | 14        | 3.71%   |
| 2019    | 12        | 3.18%   |
| 2021    | 11        | 2.92%   |
| 2018    | 9         | 2.39%   |
| 2006    | 9         | 2.39%   |
| 2017    | 8         | 2.12%   |
| 2015    | 8         | 2.12%   |
| 2016    | 6         | 1.59%   |
| Unknown | 3         | 0.8%    |
| 2023    | 2         | 0.53%   |
| 2005    | 1         | 0.27%   |
| 2002    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 186       | 49.34%  |
| Notebook    | 168       | 44.56%  |
| All in one  | 7         | 1.86%   |
| Tablet      | 5         | 1.33%   |
| Mini pc     | 5         | 1.33%   |
| Server      | 3         | 0.8%    |
| Convertible | 2         | 0.53%   |
| Other       | 1         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 372       | 98.67%  |
| Enabled  | 5         | 1.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 374       | 99.2%   |
| Yes  | 3         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 107       | 27.79%  |
| 4.01-8.0    | 85        | 22.08%  |
| 1.01-2.0    | 64        | 16.62%  |
| 8.01-16.0   | 57        | 14.81%  |
| 16.01-24.0  | 39        | 10.13%  |
| 2.01-3.0    | 15        | 3.9%    |
| 32.01-64.0  | 8         | 2.08%   |
| 24.01-32.0  | 5         | 1.3%    |
| 0.51-1.0    | 3         | 0.78%   |
| 64.01-256.0 | 2         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 164       | 39.05%  |
| 2.01-3.0   | 104       | 24.76%  |
| 0.51-1.0   | 51        | 12.14%  |
| 4.01-8.0   | 47        | 11.19%  |
| 3.01-4.0   | 40        | 9.52%   |
| 0.01-0.5   | 7         | 1.67%   |
| 8.01-16.0  | 6         | 1.43%   |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 233       | 60.21%  |
| 2      | 121       | 31.27%  |
| 3      | 26        | 6.72%   |
| 4      | 5         | 1.29%   |
| 6      | 1         | 0.26%   |
| 0      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 217       | 56.81%  |
| Yes       | 165       | 43.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 348       | 91.82%  |
| No        | 31        | 8.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 277       | 72.7%   |
| No        | 104       | 27.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 244       | 64.04%  |
| Yes       | 137       | 35.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 377       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 167       | 40.93%  |
| Maracaibo                  | 31        | 7.6%    |
| Maracay                    | 18        | 4.41%   |
| Valencia                   | 17        | 4.17%   |
| Barquisimeto               | 17        | 4.17%   |
| San Cristóbal             | 15        | 3.68%   |
| San Carlos del Zulia       | 10        | 2.45%   |
| Mérida                    | 10        | 2.45%   |
| Barcelona                  | 10        | 2.45%   |
| Maturín                   | 8         | 1.96%   |
| Ciudad Guayana             | 8         | 1.96%   |
| Barinas                    | 5         | 1.23%   |
| Vigia                      | 4         | 0.98%   |
| Porlamar                   | 4         | 0.98%   |
| Ciudad Bolívar            | 4         | 0.98%   |
| San Antonio de Los Altos   | 3         | 0.74%   |
| Parroquia El Recreo        | 3         | 0.74%   |
| Lecherias                  | 3         | 0.74%   |
| La Guaira                  | 3         | 0.74%   |
| Guatire                    | 3         | 0.74%   |
| Carrizal                   | 3         | 0.74%   |
| Anaco                      | 3         | 0.74%   |
| Acarigua                   | 3         | 0.74%   |
| San Juan Bautista          | 2         | 0.49%   |
| Punto Fijo                 | 2         | 0.49%   |
| Puerto Ordaz and San Felix | 2         | 0.49%   |
| Petare                     | 2         | 0.49%   |
| Los Teques                 | 2         | 0.49%   |
| Los Palos Grandes          | 2         | 0.49%   |
| Las Vegas                  | 2         | 0.49%   |
| Guarenas                   | 2         | 0.49%   |
| Cua                        | 2         | 0.49%   |
| Cambural                   | 2         | 0.49%   |
| Cagua                      | 2         | 0.49%   |
| Cabudare                   | 2         | 0.49%   |
| Araure                     | 2         | 0.49%   |
| Zulia                      | 1         | 0.25%   |
| Villa de Cura              | 1         | 0.25%   |
| Valle de La Pascua         | 1         | 0.25%   |
| Tucupita                   | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 118       | 164    | 23.46%  |
| Seagate                   | 108       | 155    | 21.47%  |
| Hitachi                   | 46        | 63     | 9.15%   |
| Toshiba                   | 38        | 41     | 7.55%   |
| Samsung Electronics       | 38        | 42     | 7.55%   |
| Kingston                  | 20        | 24     | 3.98%   |
| Unknown                   | 14        | 19     | 2.78%   |
| Intel                     | 11        | 14     | 2.19%   |
| SanDisk                   | 10        | 15     | 1.99%   |
| Crucial                   | 10        | 14     | 1.99%   |
| SK hynix                  | 9         | 11     | 1.79%   |
| PNY                       | 7         | 9      | 1.39%   |
| Maxtor                    | 7         | 7      | 1.39%   |
| HGST                      | 7         | 7      | 1.39%   |
| SPCC                      | 5         | 8      | 0.99%   |
| Patriot                   | 5         | 5      | 0.99%   |
| Micron Technology         | 5         | 8      | 0.99%   |
| addlink                   | 5         | 5      | 0.99%   |
| Team                      | 4         | 4      | 0.8%    |
| LITEONIT                  | 4         | 8      | 0.8%    |
| Fujitsu                   | 4         | 4      | 0.8%    |
| Silicon Motion            | 2         | 2      | 0.4%    |
| HUAWEI                    | 2         | 2      | 0.4%    |
| ExcelStor                 | 2         | 2      | 0.4%    |
| Emtec                     | 2         | 2      | 0.4%    |
| BIWIN                     | 2         | 3      | 0.4%    |
| A-DATA Technology         | 2         | 2      | 0.4%    |
| Vaseky                    | 1         | 1      | 0.2%    |
| PUSKILL                   | 1         | 1      | 0.2%    |
| Phison Electronics        | 1         | 1      | 0.2%    |
| Phison                    | 1         | 1      | 0.2%    |
| Netac                     | 1         | 1      | 0.2%    |
| Micron/Crucial Technology | 1         | 1      | 0.2%    |
| Lexar                     | 1         | 1      | 0.2%    |
| KingFast                  | 1         | 3      | 0.2%    |
| JMicron Technology        | 1         | 1      | 0.2%    |
| Intenso                   | 1         | 1      | 0.2%    |
| IBM/Hitachi               | 1         | 2      | 0.2%    |
| HPE                       | 1         | 2      | 0.2%    |
| Dogfish                   | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 16        | 2.93%   |
| Toshiba DT01ACA050 500GB            | 11        | 2.01%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 10        | 1.83%   |
| Kingston SA400S37240G 240GB SSD     | 7         | 1.28%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 1.1%    |
| Seagate ST320LM000 HM321HI 320GB    | 6         | 1.1%    |
| Samsung HD502HJ 500GB               | 6         | 1.1%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.91%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 5         | 0.91%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 4         | 0.73%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.73%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4         | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4         | 0.73%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.73%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.73%   |
| Seagate ST3320418AS 320GB           | 4         | 0.73%   |
| Seagate ST320LT012-9WS14C 320GB     | 4         | 0.73%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 4         | 0.73%   |
| Samsung HN-M320MBB 320GB            | 4         | 0.73%   |
| Samsung HD161HJ 160GB               | 4         | 0.73%   |
| Hitachi HTS543225L9A300 250GB       | 4         | 0.73%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.55%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.55%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 0.55%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.55%   |
| Toshiba MK3275GSX 320GB             | 3         | 0.55%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 0.55%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.55%   |
| Samsung HD161GJ 160GB               | 3         | 0.55%   |
| Maxtor STM3160215AS 160GB           | 3         | 0.55%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.55%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 0.55%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.55%   |
| Hitachi HDS728080PLA380 82GB        | 3         | 0.55%   |
| Hitachi HDS5C1050CLA382 500GB       | 3         | 0.55%   |
| HGST HTS545050A7E380 500GB          | 3         | 0.55%   |
| Crucial CT480BX500SSD1 480GB        | 3         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 114       | 157    | 32.39%  |
| Seagate             | 105       | 152    | 29.83%  |
| Hitachi             | 46        | 63     | 13.07%  |
| Toshiba             | 37        | 40     | 10.51%  |
| Samsung Electronics | 26        | 29     | 7.39%   |
| Maxtor              | 7         | 7      | 1.99%   |
| HGST                | 7         | 7      | 1.99%   |
| Fujitsu             | 4         | 4      | 1.14%   |
| Unknown             | 2         | 2      | 0.57%   |
| ExcelStor           | 2         | 2      | 0.57%   |
| IBM/Hitachi         | 1         | 2      | 0.28%   |
| HPE                 | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 21     | 20.24%  |
| Crucial             | 10        | 14     | 11.9%   |
| Samsung Electronics | 7         | 8      | 8.33%   |
| PNY                 | 7         | 9      | 8.33%   |
| Patriot             | 5         | 5      | 5.95%   |
| SPCC                | 4         | 6      | 4.76%   |
| LITEONIT            | 4         | 8      | 4.76%   |
| Team                | 3         | 3      | 3.57%   |
| SK hynix            | 3         | 3      | 3.57%   |
| SanDisk             | 3         | 4      | 3.57%   |
| addlink             | 3         | 3      | 3.57%   |
| Emtec               | 2         | 2      | 2.38%   |
| A-DATA Technology   | 2         | 2      | 2.38%   |
| WDC                 | 1         | 1      | 1.19%   |
| Vaseky              | 1         | 1      | 1.19%   |
| Toshiba             | 1         | 1      | 1.19%   |
| PUSKILL             | 1         | 1      | 1.19%   |
| Netac               | 1         | 1      | 1.19%   |
| Micron Technology   | 1         | 3      | 1.19%   |
| Lexar               | 1         | 1      | 1.19%   |
| KingFast            | 1         | 3      | 1.19%   |
| Intenso             | 1         | 1      | 1.19%   |
| Intel               | 1         | 1      | 1.19%   |
| Dogfish             | 1         | 1      | 1.19%   |
| Dell                | 1         | 2      | 1.19%   |
| China               | 1         | 1      | 1.19%   |
| BIWIN               | 1         | 2      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 286       | 466    | 66.51%  |
| SSD     | 79        | 108    | 18.37%  |
| NVMe    | 50        | 69     | 11.63%  |
| MMC     | 9         | 12     | 2.09%   |
| Unknown | 6         | 6      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 331       | 571    | 82.96%  |
| NVMe | 49        | 68     | 12.28%  |
| SAS  | 10        | 10     | 2.51%   |
| MMC  | 9         | 12     | 2.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 299       | 461    | 79.95%  |
| 0.51-1.0   | 55        | 80     | 14.71%  |
| 1.01-2.0   | 12        | 20     | 3.21%   |
| 3.01-4.0   | 4         | 8      | 1.07%   |
| 2.01-3.0   | 2         | 3      | 0.53%   |
| 4.01-10.0  | 2         | 2      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 131       | 32.59%  |
| 101-250        | 91        | 22.64%  |
| 501-1000       | 53        | 13.18%  |
| 1-20           | 42        | 10.45%  |
| 51-100         | 33        | 8.21%   |
| 21-50          | 18        | 4.48%   |
| 1001-2000      | 17        | 4.23%   |
| 2001-3000      | 7         | 1.74%   |
| Unknown        | 6         | 1.49%   |
| More than 3000 | 4         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 166       | 40%     |
| 21-50          | 73        | 17.59%  |
| 101-250        | 58        | 13.98%  |
| 51-100         | 46        | 11.08%  |
| 251-500        | 35        | 8.43%   |
| 501-1000       | 19        | 4.58%   |
| 1001-2000      | 6         | 1.45%   |
| Unknown        | 6         | 1.45%   |
| 2001-3000      | 4         | 0.96%   |
| More than 3000 | 2         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6         | 7      | 5%      |
| WDC WD5000AAKX-22ERMA0 500GB      | 5         | 6      | 4.17%   |
| Toshiba DT01ACA050 500GB          | 4         | 5      | 3.33%   |
| Hitachi HTS543225L9A300 250GB     | 4         | 4      | 3.33%   |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 1.67%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 1.67%   |
| WDC WD3200AAJS-08L7A0 320GB       | 2         | 3      | 1.67%   |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 1.67%   |
| Toshiba MK3275GSX 320GB           | 2         | 2      | 1.67%   |
| Seagate ST9500325AS 500GB         | 2         | 2      | 1.67%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 1.67%   |
| Seagate ST3500312CS 500GB         | 2         | 2      | 1.67%   |
| Samsung Electronics HM321HI 320GB | 2         | 2      | 1.67%   |
| Samsung Electronics HD161GJ 160GB | 2         | 2      | 1.67%   |
| Maxtor STM3160215AS 160GB         | 2         | 2      | 1.67%   |
| Hitachi HTS725050A9A364 500GB     | 2         | 2      | 1.67%   |
| Hitachi HDS728080PLA380 82GB      | 2         | 2      | 1.67%   |
| Hitachi HDS721616PLA380 164GB     | 2         | 2      | 1.67%   |
| HGST HTS545050A7E380 500GB        | 2         | 2      | 1.67%   |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 0.83%   |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 0.83%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 0.83%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 0.83%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 2      | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1         | 1      | 0.83%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1         | 1      | 0.83%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 0.83%   |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 0.83%   |
| WDC WD3200BEVT-00A0RT0 320GB      | 1         | 1      | 0.83%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 0.83%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 1      | 0.83%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 0.83%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 0.83%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 0.83%   |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 0.83%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 27.68%  |
| WDC                 | 25        | 35     | 22.32%  |
| Hitachi             | 23        | 23     | 20.54%  |
| Toshiba             | 11        | 13     | 9.82%   |
| Samsung Electronics | 9         | 10     | 8.04%   |
| Maxtor              | 3         | 3      | 2.68%   |
| HGST                | 3         | 3      | 2.68%   |
| Intel               | 2         | 2      | 1.79%   |
| ExcelStor           | 2         | 2      | 1.79%   |
| Kingston            | 1         | 1      | 0.89%   |
| JMicron Technology  | 1         | 1      | 0.89%   |
| IBM/Hitachi         | 1         | 2      | 0.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 28.7%   |
| WDC                 | 25        | 35     | 23.15%  |
| Hitachi             | 23        | 23     | 21.3%   |
| Toshiba             | 11        | 13     | 10.19%  |
| Samsung Electronics | 9         | 10     | 8.33%   |
| Maxtor              | 3         | 3      | 2.78%   |
| HGST                | 3         | 3      | 2.78%   |
| ExcelStor           | 2         | 2      | 1.85%   |
| IBM/Hitachi         | 1         | 2      | 0.93%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 93        | 125    | 95.88%  |
| NVMe | 3         | 3      | 3.09%   |
| SSD  | 1         | 1      | 1.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB  | 2         | 2      | 50%     |
| WDC WD800JD-00MSA1 80GB   | 1         | 1      | 25%     |
| Seagate ST9320423AS 320GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 191       | 352    | 45.58%  |
| Works    | 128       | 176    | 30.55%  |
| Malfunc  | 96        | 129    | 22.91%  |
| Failed   | 4         | 4      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 301       | 71.84%  |
| AMD                         | 41        | 9.79%   |
| Nvidia                      | 17        | 4.06%   |
| SanDisk                     | 10        | 2.39%   |
| SK hynix                    | 6         | 1.43%   |
| Marvell Technology Group    | 6         | 1.43%   |
| JMicron Technology          | 6         | 1.43%   |
| Samsung Electronics         | 5         | 1.19%   |
| Phison Electronics          | 4         | 0.95%   |
| Micron Technology           | 4         | 0.95%   |
| Jiangsu Huacun Elec.        | 4         | 0.95%   |
| VIA Technologies            | 3         | 0.72%   |
| Silicon Motion              | 3         | 0.72%   |
| Kingston Technology Company | 3         | 0.72%   |
| ASMedia Technology          | 3         | 0.72%   |
| Micron/Crucial Technology   | 1         | 0.24%   |
| MAXIO Technology (Hangzhou) | 1         | 0.24%   |
| Adaptec                     | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 52        | 9.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41        | 7.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26        | 4.68%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 3.24%   |
| Nvidia MCP61 SATA Controller                                                            | 16        | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 16        | 2.88%   |
| Nvidia MCP61 IDE                                                                        | 14        | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9         | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.26%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7         | 1.26%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.9%    |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                            | 4         | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.54%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 3         | 0.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 0.54%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 219       | 50.11%  |
| IDE  | 143       | 32.72%  |
| NVMe | 49        | 11.21%  |
| RAID | 24        | 5.49%   |
| SAS  | 1         | 0.23%   |
| SCSI | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 311       | 82.49%  |
| AMD          | 63        | 16.71%  |
| CentaurHauls | 3         | 0.8%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 9         | 2.39%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 2.12%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 7         | 1.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 7         | 1.86%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 6         | 1.59%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 6         | 1.59%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 5         | 1.33%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 5         | 1.33%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz    | 4         | 1.06%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 4         | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4         | 1.06%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 1.06%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 4         | 1.06%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 1.06%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 3         | 0.8%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 3         | 0.8%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 3         | 0.8%    |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 0.8%    |
| Intel Pentium CPU N3710 @ 1.60GHz              | 3         | 0.8%    |
| Intel Pentium CPU G2030 @ 3.00GHz              | 3         | 0.8%    |
| Intel Pentium 4 CPU 3.00GHz                    | 3         | 0.8%    |
| Intel Core i5-3330 CPU @ 3.00GHz               | 3         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 0.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 0.8%    |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3         | 0.8%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3         | 0.8%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 3         | 0.8%    |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 0.8%    |
| AMD Sempron 145 Processor                      | 3         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 3         | 0.8%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 2         | 0.53%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 2         | 0.53%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 2         | 0.53%   |
| Intel Pentium CPU G640 @ 2.80GHz               | 2         | 0.53%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 2         | 0.53%   |
| Intel Pentium 4 CPU 3.20GHz                    | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 63        | 16.71%  |
| Intel Core i3                        | 39        | 10.34%  |
| Intel Pentium Dual-Core              | 34        | 9.02%   |
| Intel Core i7                        | 27        | 7.16%   |
| Intel Core 2 Duo                     | 27        | 7.16%   |
| Intel Celeron                        | 26        | 6.9%    |
| Intel Pentium                        | 25        | 6.63%   |
| Other                                | 20        | 5.31%   |
| Intel Pentium Dual                   | 12        | 3.18%   |
| Intel Atom                           | 12        | 3.18%   |
| AMD Ryzen 5                          | 12        | 3.18%   |
| Intel Xeon                           | 7         | 1.86%   |
| Intel Pentium 4                      | 7         | 1.86%   |
| AMD Sempron                          | 7         | 1.86%   |
| Intel Core 2 Quad                    | 6         | 1.59%   |
| AMD Ryzen 7                          | 6         | 1.59%   |
| Intel Core 2                         | 5         | 1.33%   |
| AMD FX                               | 4         | 1.06%   |
| AMD Athlon II X2                     | 4         | 1.06%   |
| AMD Phenom II X4                     | 3         | 0.8%    |
| Intel Pentium D                      | 2         | 0.53%   |
| Intel Genuine                        | 2         | 0.53%   |
| AMD Ryzen 3                          | 2         | 0.53%   |
| AMD Phenom                           | 2         | 0.53%   |
| AMD E1                               | 2         | 0.53%   |
| AMD Athlon II X4                     | 2         | 0.53%   |
| AMD Athlon 64 X2                     | 2         | 0.53%   |
| AMD Athlon                           | 2         | 0.53%   |
| AMD A6                               | 2         | 0.53%   |
| AMD A10                              | 2         | 0.53%   |
| Intel Pentium Silver                 | 1         | 0.27%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.27%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.27%   |
| AMD Quad-Core                        | 1         | 0.27%   |
| AMD Phenom II X2                     | 1         | 0.27%   |
| AMD Mobile Sempron                   | 1         | 0.27%   |
| AMD E                                | 1         | 0.27%   |
| AMD C-70                             | 1         | 0.27%   |
| AMD Athlon II                        | 1         | 0.27%   |
| AMD A8                               | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 219       | 58.09%  |
| 4       | 100       | 26.53%  |
| 1       | 25        | 6.63%   |
| 6       | 13        | 3.45%   |
| 8       | 9         | 2.39%   |
| 3       | 5         | 1.33%   |
| Unknown | 4         | 1.06%   |
| 14      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 377       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 216       | 57.29%  |
| 2       | 157       | 41.64%  |
| Unknown | 4         | 1.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 366       | 97.08%  |
| 64-bit         | 5         | 1.33%   |
| 32-bit         | 5         | 1.33%   |
| Unknown        | 1         | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 28.06%  |
| 0x1067a    | 43        | 10.97%  |
| 0x206a7    | 40        | 10.2%   |
| 0x306a9    | 28        | 7.14%   |
| 0x6fd      | 14        | 3.57%   |
| 0x306c3    | 9         | 2.3%    |
| 0x106ca    | 7         | 1.79%   |
| 0x806c1    | 6         | 1.53%   |
| 0x30673    | 6         | 1.53%   |
| 0x806e9    | 5         | 1.28%   |
| 0x6fb      | 5         | 1.28%   |
| 0x30678    | 5         | 1.28%   |
| 0x20655    | 5         | 1.28%   |
| 0x010000c8 | 5         | 1.28%   |
| 0xf65      | 4         | 1.02%   |
| 0x806ec    | 3         | 0.77%   |
| 0x6f2      | 3         | 0.77%   |
| 0x406e3    | 3         | 0.77%   |
| 0x40651    | 3         | 0.77%   |
| 0x106a5    | 3         | 0.77%   |
| 0x10676    | 3         | 0.77%   |
| 0x05000119 | 3         | 0.77%   |
| 0x010000c7 | 3         | 0.77%   |
| 0x010000b6 | 3         | 0.77%   |
| 0xa0671    | 2         | 0.51%   |
| 0x906e9    | 2         | 0.51%   |
| 0x806ea    | 2         | 0.51%   |
| 0x806d1    | 2         | 0.51%   |
| 0x506e3    | 2         | 0.51%   |
| 0x406c4    | 2         | 0.51%   |
| 0x306d4    | 2         | 0.51%   |
| 0x206d7    | 2         | 0.51%   |
| 0x20652    | 2         | 0.51%   |
| 0x0a50000d | 2         | 0.51%   |
| 0x08608103 | 2         | 0.51%   |
| 0x08600104 | 2         | 0.51%   |
| 0x08108102 | 2         | 0.51%   |
| 0x0810100b | 2         | 0.51%   |
| 0x06000852 | 2         | 0.51%   |
| 0x0600063e | 2         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 57        | 15.12%  |
| Penryn           | 55        | 14.59%  |
| IvyBridge        | 44        | 11.67%  |
| Core             | 34        | 9.02%   |
| K10              | 18        | 4.77%   |
| Haswell          | 18        | 4.77%   |
| KabyLake         | 17        | 4.51%   |
| Silvermont       | 16        | 4.24%   |
| Westmere         | 13        | 3.45%   |
| Bonnell          | 11        | 2.92%   |
| NetBurst         | 9         | 2.39%   |
| Unknown          | 9         | 2.39%   |
| TigerLake        | 8         | 2.12%   |
| Zen+             | 6         | 1.59%   |
| Zen 2            | 5         | 1.33%   |
| Skylake          | 5         | 1.33%   |
| K8 Hammer        | 5         | 1.33%   |
| IceLake          | 5         | 1.33%   |
| Nehalem          | 4         | 1.06%   |
| Bobcat           | 4         | 1.06%   |
| Zen 3            | 3         | 0.8%    |
| Zen              | 3         | 0.8%    |
| Piledriver       | 3         | 0.8%    |
| Goldmont plus    | 3         | 0.8%    |
| Excavator        | 3         | 0.8%    |
| Broadwell        | 3         | 0.8%    |
| Alderlake Hybrid | 3         | 0.8%    |
| K8 & K10 hybrid  | 2         | 0.53%   |
| K10 Llano        | 2         | 0.53%   |
| Jaguar           | 2         | 0.53%   |
| CometLake        | 2         | 0.53%   |
| Bulldozer        | 2         | 0.53%   |
| Steamroller      | 1         | 0.27%   |
| P6               | 1         | 0.27%   |
| Goldmont         | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 258       | 64.5%   |
| AMD                        | 70        | 17.5%   |
| Nvidia                     | 64        | 16%     |
| Zhaoxin                    | 3         | 0.75%   |
| VIA Technologies           | 3         | 0.75%   |
| Matrox Electronics Systems | 1         | 0.25%   |
| ASPEED Technology          | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 12.02%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 24        | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 5.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 2.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 11        | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 2.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 9         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.96%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 0.96%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 0.96%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.96%   |
| Intel HD Graphics 620                                                                    | 4         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.96%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 0.96%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 0.96%   |
| AMD Lucienne                                                                             | 4         | 0.96%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 3         | 0.72%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.72%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 0.72%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 3         | 0.72%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.72%   |
| Intel HD Graphics 630                                                                    | 3         | 0.72%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.72%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 3         | 0.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.72%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 236       | 62.27%  |
| 1 x AMD         | 62        | 16.36%  |
| 1 x Nvidia      | 52        | 13.72%  |
| Intel + Nvidia  | 9         | 2.37%   |
| 2 x Intel       | 4         | 1.06%   |
| 2 x AMD         | 3         | 0.79%   |
| 1 x Zhaoxin     | 3         | 0.79%   |
| 1 x VIA         | 3         | 0.79%   |
| AMD + Nvidia    | 3         | 0.79%   |
| Intel + AMD     | 2         | 0.53%   |
| Nvidia + ASPEED | 1         | 0.26%   |
| 1 x Matrox      | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 329       | 86.81%  |
| Proprietary | 30        | 7.92%   |
| Unknown     | 20        | 5.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 260       | 67.36%  |
| 0.01-0.5   | 48        | 12.44%  |
| 0.51-1.0   | 41        | 10.62%  |
| 1.01-2.0   | 26        | 6.74%   |
| 3.01-4.0   | 9         | 2.33%   |
| 5.01-6.0   | 2         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 71        | 19.19%  |
| AU Optronics                          | 31        | 8.38%   |
| BOE                                   | 30        | 8.11%   |
| Hewlett-Packard                       | 24        | 6.49%   |
| LG Display                            | 23        | 6.22%   |
| Goldstar                              | 23        | 6.22%   |
| Chimei Innolux                        | 20        | 5.41%   |
| Lenovo                                | 16        | 4.32%   |
| Dell                                  | 14        | 3.78%   |
| Acer                                  | 12        | 3.24%   |
| Toshiba                               | 11        | 2.97%   |
| AOC                                   | 11        | 2.97%   |
| InfoVision                            | 10        | 2.7%    |
| Vita                                  | 7         | 1.89%   |
| Chi Mei Optoelectronics               | 7         | 1.89%   |
| LG Philips                            | 6         | 1.62%   |
| HannStar                              | 4         | 1.08%   |
| BenQ                                  | 4         | 1.08%   |
| Apple                                 | 4         | 1.08%   |
| LG Electronics                        | 3         | 0.81%   |
| ViewSonic                             | 2         | 0.54%   |
| Unknown (XXX)                         | 2         | 0.54%   |
| Sony                                  | 2         | 0.54%   |
| PANDA                                 | 2         | 0.54%   |
| MStar                                 | 2         | 0.54%   |
| ITL                                   | 2         | 0.54%   |
| Envision                              | 2         | 0.54%   |
| Vizio                                 | 1         | 0.27%   |
| Unknown (CEA)                         | 1         | 0.27%   |
| Toshiba Matsushita Display Technology | 1         | 0.27%   |
| TCL                                   | 1         | 0.27%   |
| Sharp                                 | 1         | 0.27%   |
| Sceptre Tech                          | 1         | 0.27%   |
| PXO                                   | 1         | 0.27%   |
| Plain Tree Systems                    | 1         | 0.27%   |
| PEGA                                  | 1         | 0.27%   |
| Parker                                | 1         | 0.27%   |
| NEC Computers                         | 1         | 0.27%   |
| MSI                                   | 1         | 0.27%   |
| LSC                                   | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 8         | 2.12%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 7         | 1.86%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 7         | 1.86%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 1.59%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 5         | 1.33%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 5         | 1.33%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.06%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                  | 3         | 0.8%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 0.8%    |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3         | 0.8%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 0.8%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3         | 0.8%    |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 0.8%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 3         | 0.8%    |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.53%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.53%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.53%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 2         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.53%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 2         | 0.53%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.53%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2         | 0.53%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 2         | 0.53%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.53%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.53%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2         | 0.53%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2         | 0.53%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                   | 2         | 0.53%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.53%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch       | 2         | 0.53%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 131       | 36.49%  |
| 1920x1080 (FHD)    | 82        | 22.84%  |
| 1280x1024 (SXGA)   | 33        | 9.19%   |
| 1440x900 (WXGA+)   | 25        | 6.96%   |
| 1600x900 (HD+)     | 19        | 5.29%   |
| 1280x800 (WXGA)    | 16        | 4.46%   |
| 1680x1050 (WSXGA+) | 10        | 2.79%   |
| 1360x768           | 10        | 2.79%   |
| 1024x768 (XGA)     | 8         | 2.23%   |
| 3840x2160 (4K)     | 5         | 1.39%   |
| 2560x1440 (QHD)    | 4         | 1.11%   |
| 1920x1200 (WUXGA)  | 4         | 1.11%   |
| 1280x720 (HD)      | 4         | 1.11%   |
| 1024x600           | 3         | 0.84%   |
| Unknown            | 2         | 0.56%   |
| 3840x1080          | 1         | 0.28%   |
| 3240x2160          | 1         | 0.28%   |
| 2240x1400          | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 78        | 21.14%  |
| 18      | 44        | 11.92%  |
| 14      | 38        | 10.3%   |
| 13      | 34        | 9.21%   |
| 17      | 33        | 8.94%   |
| 21      | 30        | 8.13%   |
| 19      | 26        | 7.05%   |
| Unknown | 16        | 4.34%   |
| 23      | 12        | 3.25%   |
| 10      | 10        | 2.71%   |
| 20      | 9         | 2.44%   |
| 22      | 6         | 1.63%   |
| 27      | 5         | 1.36%   |
| 11      | 5         | 1.36%   |
| 74      | 3         | 0.81%   |
| 32      | 3         | 0.81%   |
| 24      | 3         | 0.81%   |
| 16      | 3         | 0.81%   |
| 72      | 2         | 0.54%   |
| 52      | 2         | 0.54%   |
| 31      | 2         | 0.54%   |
| 12      | 2         | 0.54%   |
| 54      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 39      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 167       | 46.01%  |
| 401-500     | 106       | 29.2%   |
| 201-300     | 21        | 5.79%   |
| 501-600     | 19        | 5.23%   |
| 351-400     | 19        | 5.23%   |
| Unknown     | 16        | 4.41%   |
| 1501-2000   | 5         | 1.38%   |
| 701-800     | 3         | 0.83%   |
| 1001-1500   | 3         | 0.83%   |
| 601-700     | 2         | 0.55%   |
| 801-900     | 1         | 0.28%   |
| 901-1000    | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 67.65%  |
| 16/10   | 57        | 16.76%  |
| 5/4     | 31        | 9.12%   |
| Unknown | 11        | 3.24%   |
| 4/3     | 8         | 2.35%   |
| 3/2     | 3         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 21.2%   |
| 81-90          | 69        | 18.75%  |
| 141-150        | 58        | 15.76%  |
| 151-200        | 55        | 14.95%  |
| 201-250        | 38        | 10.33%  |
| Unknown        | 16        | 4.35%   |
| 41-50          | 10        | 2.72%   |
| 121-130        | 10        | 2.72%   |
| More than 1000 | 8         | 2.17%   |
| 51-60          | 5         | 1.36%   |
| 351-500        | 5         | 1.36%   |
| 301-350        | 5         | 1.36%   |
| 71-80          | 2         | 0.54%   |
| 61-70          | 2         | 0.54%   |
| 251-300        | 2         | 0.54%   |
| 131-140        | 2         | 0.54%   |
| 501-1000       | 2         | 0.54%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 158       | 43.65%  |
| 101-120       | 118       | 32.6%   |
| 121-160       | 54        | 14.92%  |
| Unknown       | 16        | 4.42%   |
| 1-50          | 11        | 3.04%   |
| 161-240       | 3         | 0.83%   |
| More than 240 | 2         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 317       | 82.55%  |
| 2     | 39        | 10.16%  |
| 0     | 24        | 6.25%   |
| 3     | 4         | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 235       | 39.23%  |
| Intel                             | 110       | 18.36%  |
| Qualcomm Atheros                  | 105       | 17.53%  |
| Broadcom                          | 30        | 5.01%   |
| Ralink                            | 19        | 3.17%   |
| Nvidia                            | 17        | 2.84%   |
| Ralink Technology                 | 12        | 2%      |
| Xiaomi                            | 8         | 1.34%   |
| Marvell Technology Group          | 8         | 1.34%   |
| TP-Link                           | 7         | 1.17%   |
| Broadcom Limited                  | 7         | 1.17%   |
| Qualcomm Atheros Communications   | 6         | 1%      |
| MediaTek                          | 6         | 1%      |
| JMicron Technology                | 4         | 0.67%   |
| VIA Technologies                  | 3         | 0.5%    |
| Samsung Electronics               | 3         | 0.5%    |
| Trendchip Technologies            | 2         | 0.33%   |
| Sundance Technology Inc / IC Plus | 2         | 0.33%   |
| Mercucys                          | 2         | 0.33%   |
| D-Link System                     | 2         | 0.33%   |
| ZyXEL Communications              | 1         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.17%   |
| National Semiconductor            | 1         | 0.17%   |
| Motorola PCS                      | 1         | 0.17%   |
| Motorola BCS                      | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Digium                            | 1         | 0.17%   |
| Davicom Semiconductor             | 1         | 0.17%   |
| ASIX Electronics                  | 1         | 0.17%   |
| AMD                               | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 143       | 21.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 46        | 6.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 25        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 2.68%   |
| Nvidia MCP61 Ethernet                                                         | 16        | 2.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 11        | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 11        | 1.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 11        | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 10        | 1.49%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 9         | 1.34%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 8         | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 8         | 1.19%   |
| Intel Wireless 7265                                                           | 8         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 7         | 1.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 7         | 1.04%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 0.89%   |
| Ralink MT7601U Wireless Adapter                                               | 6         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6         | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 6         | 0.89%   |
| Intel Wi-Fi 6 AX201                                                           | 6         | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 5         | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 5         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 5         | 0.75%   |
| Intel Wireless 7260                                                           | 5         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 4         | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4         | 0.6%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 4         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 4         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 4         | 0.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 4         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 0.6%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 0.6%    |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.6%    |
| Intel WiFi Link 5100                                                          | 4         | 0.6%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 78        | 26.9%   |
| Realtek Semiconductor           | 69        | 23.79%  |
| Intel                           | 68        | 23.45%  |
| Ralink                          | 19        | 6.55%   |
| Broadcom                        | 16        | 5.52%   |
| Ralink Technology               | 12        | 4.14%   |
| TP-Link                         | 6         | 2.07%   |
| Qualcomm Atheros Communications | 6         | 2.07%   |
| MediaTek                        | 6         | 2.07%   |
| Broadcom Limited                | 3         | 1.03%   |
| Xiaomi                          | 2         | 0.69%   |
| Mercucys                        | 2         | 0.69%   |
| D-Link System                   | 2         | 0.69%   |
| Marvell Technology Group        | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 25        | 8.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 11        | 3.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 11        | 3.79%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9         | 3.1%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 8         | 2.76%   |
| Intel Wireless 7265                                                            | 8         | 2.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 2.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7         | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 6         | 2.07%   |
| Ralink MT7601U Wireless Adapter                                                | 6         | 2.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 6         | 2.07%   |
| Intel Wi-Fi 6 AX201                                                            | 6         | 2.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 5         | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 5         | 1.72%   |
| Intel Wireless 7260                                                            | 5         | 1.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 1.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4         | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 4         | 1.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 4         | 1.38%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4         | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 1.38%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 1.38%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4         | 1.38%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.38%   |
| Intel WiFi Link 5100                                                           | 4         | 1.38%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 1.38%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.38%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.03%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.03%   |
| Intel Wireless 3165                                                            | 3         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 3         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                                 | 3         | 1.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 3         | 1.03%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                              | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 202       | 54.45%  |
| Intel                             | 61        | 16.44%  |
| Qualcomm Atheros                  | 37        | 9.97%   |
| Nvidia                            | 17        | 4.58%   |
| Broadcom                          | 15        | 4.04%   |
| Marvell Technology Group          | 7         | 1.89%   |
| Xiaomi                            | 6         | 1.62%   |
| JMicron Technology                | 4         | 1.08%   |
| Broadcom Limited                  | 4         | 1.08%   |
| VIA Technologies                  | 3         | 0.81%   |
| Samsung Electronics               | 3         | 0.81%   |
| Trendchip Technologies            | 2         | 0.54%   |
| Sundance Technology Inc / IC Plus | 2         | 0.54%   |
| ZyXEL Communications              | 1         | 0.27%   |
| TP-Link                           | 1         | 0.27%   |
| National Semiconductor            | 1         | 0.27%   |
| Motorola PCS                      | 1         | 0.27%   |
| Motorola BCS                      | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| Davicom Semiconductor             | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 143       | 37.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 46        | 12.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18        | 4.77%   |
| Nvidia MCP61 Ethernet                                                      | 16        | 4.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 11        | 2.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 10        | 2.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 8         | 2.12%   |
| Intel Ethernet Connection I217-LM                                          | 7         | 1.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 6         | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 1.06%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.06%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 0.8%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 0.8%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3         | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 3         | 0.8%    |
| Intel PRO/100 VE Network Connection                                        | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 0.8%    |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.53%   |
| Trendchip Ethernet controller                                              | 2         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.53%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                    | 2         | 0.53%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                        | 2         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                            | 2         | 0.53%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.53%   |
| ZyXEL ADSL Modem Prestige 600 series                                       | 1         | 0.27%   |
| TP-Link M7200                                                              | 1         | 0.27%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.27%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1         | 0.27%   |
| Realtek PCIe GbE Family Controller                                         | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 347       | 55.25%  |
| WiFi     | 277       | 44.11%  |
| Modem    | 3         | 0.48%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 50.63%  |
| Ethernet | 195       | 49.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 216       | 56.54%  |
| 1     | 157       | 41.1%   |
| 3     | 4         | 1.05%   |
| 0     | 3         | 0.79%   |
| 33    | 1         | 0.26%   |
| 4     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 376       | 99.21%  |
| Yes  | 3         | 0.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 31.88%  |
| Realtek Semiconductor           | 18        | 13.04%  |
| Qualcomm Atheros Communications | 16        | 11.59%  |
| Cambridge Silicon Radio         | 16        | 11.59%  |
| IMC Networks                    | 15        | 10.87%  |
| Broadcom                        | 10        | 7.25%   |
| Lite-On Technology              | 5         | 3.62%   |
| Apple                           | 4         | 2.9%    |
| ASUSTek Computer                | 3         | 2.17%   |
| Hewlett-Packard                 | 2         | 1.45%   |
| Marvell Semiconductor           | 1         | 0.72%   |
| ISSC                            | 1         | 0.72%   |
| Foxconn / Hon Hai               | 1         | 0.72%   |
| Dell                            | 1         | 0.72%   |
| Alps Electric                   | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 15.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 16        | 11.59%  |
| Intel AX201 Bluetooth                                       | 11        | 7.97%   |
| Realtek Bluetooth Radio                                     | 8         | 5.8%    |
| Realtek RTL8723B Bluetooth                                  | 7         | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 3.62%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 3.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 2.9%    |
| Intel AX200 Bluetooth                                       | 4         | 2.9%    |
| IMC Networks Bluetooth                                      | 4         | 2.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 2.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.17%   |
| IMC Networks Wireless_Device                                | 3         | 2.17%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.45%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.45%   |
| Lite-On Wireless_Device                                     | 2         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.45%   |
| Intel Bluetooth Device                                      | 2         | 1.45%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.45%   |
| IMC Networks Bluetooth Module                               | 2         | 1.45%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.72%   |
| Marvell Bluetooth and Wireless LAN Composite                | 1         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.72%   |
| Lite-On Bluetooth Device                                    | 1         | 0.72%   |
| Lite-On BCM20702A0                                          | 1         | 0.72%   |
| ISSC Bluetooth Device                                       | 1         | 0.72%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.72%   |
| Broadcom HP Portable Valentine                              | 1         | 0.72%   |
| Broadcom Bluetooth 2.0+eDR dongle                           | 1         | 0.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle         | 1         | 0.72%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.72%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.72%   |
| Broadcom BCM2035B3 Bluetooth Adapter                        | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 301       | 63.64%  |
| AMD                       | 73        | 15.43%  |
| Nvidia                    | 55        | 11.63%  |
| C-Media Electronics       | 8         | 1.69%   |
| VIA Technologies          | 5         | 1.06%   |
| Creative Labs             | 5         | 1.06%   |
| Zhaoxin                   | 3         | 0.63%   |
| Logitech                  | 3         | 0.63%   |
| JMTek                     | 3         | 0.63%   |
| Generalplus Technology    | 3         | 0.63%   |
| Sennheiser Communications | 2         | 0.42%   |
| Microsoft                 | 2         | 0.42%   |
| Corsair                   | 2         | 0.42%   |
| Unknown                   | 1         | 0.21%   |
| Realtek Semiconductor     | 1         | 0.21%   |
| Megawin Technology        | 1         | 0.21%   |
| M-Audio                   | 1         | 0.21%   |
| Giga-Byte Technology      | 1         | 0.21%   |
| Cirrus Logic              | 1         | 0.21%   |
| Aureal Semiconductor      | 1         | 0.21%   |
| ASUSTek Computer          | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 61        | 11.42%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 59        | 11.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 7.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 3.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 18        | 3.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 2.81%   |
| Nvidia MCP61 High Definition Audio                                                                | 14        | 2.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 1.87%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.87%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 9         | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.31%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 7         | 1.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.12%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.75%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 0.56%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000 High Definition Audio Controller                 | 3         | 0.56%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.56%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.56%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.56%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.56%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.56%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 68        | 21.12%  |
| Samsung Electronics        | 49        | 15.22%  |
| SK hynix                   | 41        | 12.73%  |
| Ramaxel Technology         | 35        | 10.87%  |
| Kingston                   | 30        | 9.32%   |
| Micron Technology          | 19        | 5.9%    |
| Crucial                    | 17        | 5.28%   |
| Corsair                    | 12        | 3.73%   |
| Elpida                     | 7         | 2.17%   |
| Team                       | 4         | 1.24%   |
| Unknown                    | 4         | 1.24%   |
| Qimonda                    | 3         | 0.93%   |
| Nanya Technology           | 3         | 0.93%   |
| A-DATA Technology          | 3         | 0.93%   |
| Unknown (ABCD)             | 2         | 0.62%   |
| Unknown (0x07D5)           | 2         | 0.62%   |
| Shenzhen WODPOSIT          | 2         | 0.62%   |
| PNY                        | 2         | 0.62%   |
| Memox                      | 2         | 0.62%   |
| Kreton                     | 2         | 0.62%   |
| Avant                      | 2         | 0.62%   |
| Unknown (FFFF000000000000) | 1         | 0.31%   |
| Unknown (7F7F7F7F7F7F7F83) | 1         | 0.31%   |
| Unknown (0x0CBA)           | 1         | 0.31%   |
| Unknown (081A)             | 1         | 0.31%   |
| Unknown (07F7)             | 1         | 0.31%   |
| Transcend                  | 1         | 0.31%   |
| Super Talent               | 1         | 0.31%   |
| OCZ                        | 1         | 0.31%   |
| Hikvision                  | 1         | 0.31%   |
| Gold Key                   | 1         | 0.31%   |
| Apacer                     | 1         | 0.31%   |
| <Invalid>                  | 1         | 0.31%   |
| 48spaces                   | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                          | 6         | 1.7%    |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s    | 6         | 1.7%    |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s | 5         | 1.42%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 5         | 1.42%   |
| Unknown RAM Module 4GB DIMM SDRAM                          | 4         | 1.13%   |
| Unknown RAM Module 4GB DIMM 400MT/s                        | 4         | 1.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 4         | 1.13%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s    | 4         | 1.13%   |
| Unknown                                                    | 4         | 1.13%   |
| Unknown RAM Module 2GB DIMM DDR2                           | 3         | 0.85%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 3         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR2                        | 3         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 0.85%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s     | 3         | 0.85%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s      | 3         | 0.85%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s        | 3         | 0.85%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s    | 3         | 0.85%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s      | 3         | 0.85%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s    | 3         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                  | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                   | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM 400MT/s                        | 2         | 0.57%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 2         | 0.57%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 2         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                | 2         | 0.57%   |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s       | 2         | 0.57%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s    | 2         | 0.57%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s     | 2         | 0.57%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 2         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 2         | 0.57%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s      | 2         | 0.57%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.57%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                  | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 102       | 40.96%  |
| DDR4    | 54        | 21.69%  |
| DDR2    | 42        | 16.87%  |
| SDRAM   | 25        | 10.04%  |
| Unknown | 15        | 6.02%   |
| DDR     | 6         | 2.41%   |
| LPDDR4  | 3         | 1.2%    |
| LPDDR3  | 1         | 0.4%    |
| DDR5    | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 119       | 49.17%  |
| SODIMM       | 118       | 48.76%  |
| Row Of Chips | 5         | 2.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 97        | 33.8%   |
| 4096  | 86        | 29.97%  |
| 8192  | 61        | 21.25%  |
| 1024  | 25        | 8.71%   |
| 16384 | 13        | 4.53%   |
| 32768 | 3         | 1.05%   |
| 512   | 2         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 64        | 22.78%  |
| 1333    | 39        | 13.88%  |
| 3200    | 26        | 9.25%   |
| Unknown | 25        | 8.9%    |
| 2667    | 18        | 6.41%   |
| 667     | 18        | 6.41%   |
| 800     | 12        | 4.27%   |
| 2400    | 9         | 3.2%    |
| 533     | 8         | 2.85%   |
| 1066    | 7         | 2.49%   |
| 1334    | 6         | 2.14%   |
| 400     | 6         | 2.14%   |
| 2048    | 5         | 1.78%   |
| 2133    | 4         | 1.42%   |
| 1867    | 4         | 1.42%   |
| 3733    | 3         | 1.07%   |
| 2666    | 3         | 1.07%   |
| 1639    | 3         | 1.07%   |
| 1067    | 3         | 1.07%   |
| 133     | 3         | 1.07%   |
| 4199    | 2         | 0.71%   |
| 3600    | 2         | 0.71%   |
| 3266    | 2         | 0.71%   |
| 1800    | 2         | 0.71%   |
| 975     | 2         | 0.71%   |
| 4800    | 1         | 0.36%   |
| 3800    | 1         | 0.36%   |
| 2000    | 1         | 0.36%   |
| 1024    | 1         | 0.36%   |
| 266     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 58.33%  |
| Seiko Epson         | 3         | 25%     |
| Samsung Electronics | 2         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 8.33%   |
| Seiko Epson L6160 Series                     | 1         | 8.33%   |
| Seiko Epson L210 Series                      | 1         | 8.33%   |
| Samsung ML-216x Series Laser Printer         | 1         | 8.33%   |
| Samsung ML-1865                              | 1         | 8.33%   |
| HP LaserJet Professional P1102w              | 1         | 8.33%   |
| HP LaserJet P1006                            | 1         | 8.33%   |
| HP LaserJet P1005                            | 1         | 8.33%   |
| HP LaserJet 1018                             | 1         | 8.33%   |
| HP DeskJet F4100 Printer series              | 1         | 8.33%   |
| HP DeskJet 2300 series                       | 1         | 8.33%   |
| HP Color LaserJet CP1215                     | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| KYE Systems (Mouse Systems) | 1         | 33.33%  |
| Hewlett-Packard             | 1         | 33.33%  |
| Canon                       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1         | 33.33%  |
| HP Scanjet 200                                      | 1         | 33.33%  |
| Canon CanoScan LiDE 110                             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 19.19%  |
| Microdia                               | 16        | 9.3%    |
| Bison Electronics                      | 15        | 8.72%   |
| IMC Networks                           | 13        | 7.56%   |
| Realtek Semiconductor                  | 12        | 6.98%   |
| Suyin                                  | 10        | 5.81%   |
| Quanta                                 | 6         | 3.49%   |
| Logitech                               | 6         | 3.49%   |
| Syntek                                 | 5         | 2.91%   |
| Sunplus Innovation Technology          | 5         | 2.91%   |
| Apple                                  | 5         | 2.91%   |
| Sonix Technology                       | 4         | 2.33%   |
| Microsoft                              | 4         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.33%   |
| Samsung Electronics                    | 3         | 1.74%   |
| Ricoh                                  | 3         | 1.74%   |
| Luxvisions Innotech Limited            | 3         | 1.74%   |
| Lite-On Technology                     | 3         | 1.74%   |
| ALi                                    | 3         | 1.74%   |
| KYE Systems (Mouse Systems)            | 2         | 1.16%   |
| Importek                               | 2         | 1.16%   |
| Cubeternet                             | 2         | 1.16%   |
| Alcor Micro                            | 2         | 1.16%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Tobii Technology AB                    | 1         | 0.58%   |
| SN0002                                 | 1         | 0.58%   |
| Silicon Motion                         | 1         | 0.58%   |
| SiGma Micro                            | 1         | 0.58%   |
| OmniVision Technologies                | 1         | 0.58%   |
| LG Electronics                         | 1         | 0.58%   |
| Lenovo                                 | 1         | 0.58%   |
| icSpring                               | 1         | 0.58%   |
| Aveo Technology                        | 1         | 0.58%   |
| Acer                                   | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 12        | 6.98%   |
| Microdia USB 2.0 Camera                                       | 6         | 3.49%   |
| Bison HD Webcam                                               | 5         | 2.91%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 2.33%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 2.33%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.33%   |
| Chicony Integrated Camera                                     | 4         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                  | 3         | 1.74%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 3         | 1.74%   |
| Logitech Webcam C270                                          | 3         | 1.74%   |
| IMC Networks XHC Camera                                       | 3         | 1.74%   |
| IMC Networks Integrated Camera                                | 3         | 1.74%   |
| Chicony HD Webcam                                             | 3         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 1.74%   |
| Bison USB Camera                                              | 3         | 1.74%   |
| Apple Built-in iSight                                         | 3         | 1.74%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.16%   |
| Suyin HP Webcam 101                                           | 2         | 1.16%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.16%   |
| Realtek Integrated Webcam HD                                  | 2         | 1.16%   |
| Quanta ACER HD User Facing                                    | 2         | 1.16%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.16%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.16%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.16%   |
| Cubeternet USB2.0 Camera                                      | 2         | 1.16%   |
| Chicony HP Wide Vision HD Camera                              | 2         | 1.16%   |
| Bison Lenovo EasyCamera                                       | 2         | 1.16%   |
| ALi WebCam                                                    | 2         | 1.16%   |
| Z-Star Venus USB2.0 Camera                                    | 1         | 0.58%   |
| Tobii AB EyeChip                                              | 1         | 0.58%   |
| Syntek USB Camera Device                                      | 1         | 0.58%   |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.58%   |
| Syntek Integrated Webcam                                      | 1         | 0.58%   |
| Syntek Integrated Camera                                      | 1         | 0.58%   |
| Syntek EasyCamera                                             | 1         | 0.58%   |
| Suyin USB 2.0 Camera                                          | 1         | 0.58%   |
| Suyin Integrated Webcam                                       | 1         | 0.58%   |
| Suyin HP Webcam                                               | 1         | 0.58%   |
| Suyin HP TrueVision HD                                        | 1         | 0.58%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 44.44%  |
| Synaptics                  | 3         | 16.67%  |
| AuthenTec                  | 3         | 16.67%  |
| Upek                       | 1         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 5.56%   |
| Futronic Technology        | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 11.11%  |
| Validity Sensors Fingerprint scanner                   | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Synaptics UWP WBDI                                     | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.56%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.56%   |
| AuthenTec AES1600                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| Alcor Micro | 2         | 28.57%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 28.57%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 292       | 76.64%  |
| 1     | 73        | 19.16%  |
| 2     | 13        | 3.41%   |
| 4     | 2         | 0.52%   |
| 3     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 39        | 35.78%  |
| Fingerprint reader       | 18        | 16.51%  |
| Communication controller | 11        | 10.09%  |
| Net/wireless             | 9         | 8.26%   |
| Sound                    | 8         | 7.34%   |
| Chipcard                 | 7         | 6.42%   |
| Multimedia controller    | 5         | 4.59%   |
| Camera                   | 5         | 4.59%   |
| Network                  | 2         | 1.83%   |
| Video                    | 1         | 0.92%   |
| Storage/ide              | 1         | 0.92%   |
| Storage                  | 1         | 0.92%   |
| Firewire controller      | 1         | 0.92%   |
| Bluetooth                | 1         | 0.92%   |


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

Total: 533

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Debian 11          | 37        | 9.46%   |
| Ubuntu 20.04       | 25        | 6.39%   |
| Ubuntu 22.04       | 22        | 5.63%   |
| OpenMandriva 4.3   | 18        | 4.6%    |
| Ubuntu 18.04       | 16        | 4.09%   |
| OpenMandriva 23.03 | 12        | 3.07%   |
| Zorin 16           | 11        | 2.81%   |
| OpenMandriva 4.2   | 10        | 2.56%   |
| Debian 10          | 10        | 2.56%   |
| Linux Mint 21.1    | 9         | 2.3%    |
| Linux Mint 20.3    | 9         | 2.3%    |
| KDE neon 20.04     | 9         | 2.3%    |
| Xubuntu 18.04      | 7         | 1.79%   |
| OpenMandriva 23.01 | 7         | 1.79%   |
| OpenMandriva 23.08 | 6         | 1.53%   |
| Kubuntu 20.04      | 6         | 1.53%   |
| Debian 12          | 6         | 1.53%   |
| ROSA R9            | 5         | 1.28%   |
| ROSA R11           | 5         | 1.28%   |
| Linux Mint 20      | 5         | 1.28%   |
| Linux Mint 19.3    | 5         | 1.28%   |
| ArcoLinux Rolling  | 5         | 1.28%   |
| Arch Rolling       | 5         | 1.28%   |
| Zorin 15           | 4         | 1.02%   |
| Ubuntu MATE 19.10  | 4         | 1.02%   |
| Ubuntu 19.10       | 4         | 1.02%   |
| KDE neon 22.04     | 4         | 1.02%   |
| Fedora 35          | 4         | 1.02%   |
| Xubuntu 22.04      | 3         | 0.77%   |
| Ubuntu 21.10       | 3         | 0.77%   |
| OpenMandriva 4.50  | 3         | 0.77%   |
| MX 21              | 3         | 0.77%   |
| Manjaro            | 3         | 0.77%   |
| Linux Mint 20.1    | 3         | 0.77%   |
| KDE neon 18.04     | 3         | 0.77%   |
| Fedora 38          | 3         | 0.77%   |
| Fedora 36          | 3         | 0.77%   |
| Xubuntu 20.04      | 2         | 0.51%   |
| Xubuntu 16.04      | 2         | 0.51%   |
| Xero Rolling       | 2         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 74        | 19.68%  |
| OpenMandriva | 55        | 14.63%  |
| Debian       | 55        | 14.63%  |
| Linux Mint   | 36        | 9.57%   |
| Zorin        | 15        | 3.99%   |
| ROSA         | 15        | 3.99%   |
| KDE neon     | 15        | 3.99%   |
| Xubuntu      | 14        | 3.72%   |
| Fedora       | 14        | 3.72%   |
| Kubuntu      | 9         | 2.39%   |
| Manjaro      | 8         | 2.13%   |
| Arch         | 7         | 1.86%   |
| Ubuntu MATE  | 5         | 1.33%   |
| Pop!_OS      | 5         | 1.33%   |
| Elementary   | 5         | 1.33%   |
| ArcoLinux    | 5         | 1.33%   |
| MX           | 4         | 1.06%   |
| Kali         | 4         | 1.06%   |
| Ubuntu Unity | 3         | 0.8%    |
| Nobara       | 3         | 0.8%    |
| LMDE         | 3         | 0.8%    |
| Xero         | 2         | 0.53%   |
| Solus        | 2         | 0.53%   |
| Q4OS         | 2         | 0.53%   |
| Lubuntu      | 2         | 0.53%   |
| Garuda Linux | 2         | 0.53%   |
| Feren OS     | 2         | 0.53%   |
| Sparky       | 1         | 0.27%   |
| PCLinuxOS    | 1         | 0.27%   |
| openSUSE     | 1         | 0.27%   |
| Linux Lite   | 1         | 0.27%   |
| Endless      | 1         | 0.27%   |
| EndeavourOS  | 1         | 0.27%   |
| Deepin       | 1         | 0.27%   |
| BunsenLabs   | 1         | 0.27%   |
| Alpine       | 1         | 0.27%   |
| AlmaLinux    | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 4.25%   |
| 6.2.6-desktop-1omv2390          | 12        | 2.83%   |
| 5.10.14-desktop-1omv4002        | 10        | 2.36%   |
| 5.4.0-42-generic                | 8         | 1.89%   |
| 6.1.1-desktop-1omv2290          | 7         | 1.65%   |
| 5.3.0-40-generic                | 6         | 1.42%   |
| 5.15.0-56-generic               | 6         | 1.42%   |
| 5.15.0-46-generic               | 6         | 1.42%   |
| 6.4.11-desktop-1omv2390         | 5         | 1.18%   |
| 5.19.0-41-generic               | 5         | 1.18%   |
| 5.10.0-23-amd64                 | 5         | 1.18%   |
| 6.2.0-26-generic                | 4         | 0.94%   |
| 5.4.0-77-generic                | 4         | 0.94%   |
| 5.15.0-76-generic               | 4         | 0.94%   |
| 5.15.0-67-generic               | 4         | 0.94%   |
| 5.13.0-39-generic               | 4         | 0.94%   |
| 5.10.0-16-amd64                 | 4         | 0.94%   |
| 5.10.0-13-amd64                 | 4         | 0.94%   |
| 5.10.0-11-amd64                 | 4         | 0.94%   |
| 5.0.0-37-generic                | 4         | 0.94%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 0.94%   |
| 4.19.0-17-amd64                 | 4         | 0.94%   |
| 5.4.0-74-generic                | 3         | 0.71%   |
| 5.4.0-73-generic                | 3         | 0.71%   |
| 5.4.0-52-generic                | 3         | 0.71%   |
| 5.3.0-29-generic                | 3         | 0.71%   |
| 5.15.0-58-generic               | 3         | 0.71%   |
| 5.15.0-52-generic               | 3         | 0.71%   |
| 5.11.0-37-generic               | 3         | 0.71%   |
| 5.10.0-21-amd64                 | 3         | 0.71%   |
| 4.15.0-48-generic               | 3         | 0.71%   |
| 6.4.11-arch2-1                  | 2         | 0.47%   |
| 6.1.0-10-amd64                  | 2         | 0.47%   |
| 5.8.0-63-generic                | 2         | 0.47%   |
| 5.8.0-55-generic                | 2         | 0.47%   |
| 5.8.0-44-generic                | 2         | 0.47%   |
| 5.4.0-89-generic                | 2         | 0.47%   |
| 5.4.0-66-generic                | 2         | 0.47%   |
| 5.4.0-54-generic                | 2         | 0.47%   |
| 5.4.0-48-generic                | 2         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 12.69%  |
| 5.15.0  | 44        | 11.17%  |
| 5.10.0  | 39        | 9.9%    |
| 4.15.0  | 24        | 6.09%   |
| 5.13.0  | 19        | 4.82%   |
| 5.16.7  | 18        | 4.57%   |
| 5.19.0  | 14        | 3.55%   |
| 6.2.6   | 12        | 3.05%   |
| 5.3.0   | 12        | 3.05%   |
| 4.19.0  | 12        | 3.05%   |
| 5.8.0   | 10        | 2.54%   |
| 5.10.14 | 10        | 2.54%   |
| 5.11.0  | 9         | 2.28%   |
| 6.4.11  | 7         | 1.78%   |
| 6.2.0   | 7         | 1.78%   |
| 6.1.1   | 7         | 1.78%   |
| 5.0.0   | 7         | 1.78%   |
| 6.1.0   | 5         | 1.27%   |
| 4.9.20  | 5         | 1.27%   |
| 6.2.12  | 3         | 0.76%   |
| 5.14.10 | 3         | 0.76%   |
| 6.4.6   | 2         | 0.51%   |
| 6.4.3   | 2         | 0.51%   |
| 6.4.2   | 2         | 0.51%   |
| 5.18.0  | 2         | 0.51%   |
| 5.15.6  | 2         | 0.51%   |
| 5.15.2  | 2         | 0.51%   |
| 5.12.4  | 2         | 0.51%   |
| 4.9.0   | 2         | 0.51%   |
| 4.18.0  | 2         | 0.51%   |
| 6.4.8   | 1         | 0.25%   |
| 6.4.7   | 1         | 0.25%   |
| 6.4.12  | 1         | 0.25%   |
| 6.3.8   | 1         | 0.25%   |
| 6.3.6   | 1         | 0.25%   |
| 6.3.5   | 1         | 0.25%   |
| 6.3.0   | 1         | 0.25%   |
| 6.1.8   | 1         | 0.25%   |
| 6.1.20  | 1         | 0.25%   |
| 6.1.14  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 56        | 14.36%  |
| 5.15    | 54        | 13.85%  |
| 5.4     | 52        | 13.33%  |
| 4.15    | 24        | 6.15%   |
| 6.2     | 22        | 5.64%   |
| 5.13    | 22        | 5.64%   |
| 5.16    | 20        | 5.13%   |
| 6.4     | 16        | 4.1%    |
| 5.19    | 16        | 4.1%    |
| 6.1     | 15        | 3.85%   |
| 5.8     | 13        | 3.33%   |
| 5.3     | 12        | 3.08%   |
| 4.19    | 12        | 3.08%   |
| 5.11    | 9         | 2.31%   |
| 5.0     | 7         | 1.79%   |
| 4.9     | 7         | 1.79%   |
| 6.3     | 4         | 1.03%   |
| 6.0     | 4         | 1.03%   |
| 5.17    | 4         | 1.03%   |
| 5.6     | 3         | 0.77%   |
| 5.18    | 3         | 0.77%   |
| 5.14    | 3         | 0.77%   |
| 5.12    | 3         | 0.77%   |
| 5.9     | 2         | 0.51%   |
| 4.18    | 2         | 0.51%   |
| 5.7     | 1         | 0.26%   |
| 5.5     | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |
| 4.13    | 1         | 0.26%   |
| 4.1     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 333       | 91.99%  |
| i686   | 29        | 8.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 119       | 31.07%  |
| KDE5            | 99        | 25.85%  |
| XFCE            | 47        | 12.27%  |
| Unknown         | 27        | 7.05%   |
| X-Cinnamon      | 26        | 6.79%   |
| MATE            | 13        | 3.39%   |
| KDE             | 12        | 3.13%   |
| KDE4            | 7         | 1.83%   |
| LXQt            | 6         | 1.57%   |
| LXDE            | 5         | 1.31%   |
| Cinnamon        | 5         | 1.31%   |
| Pantheon        | 4         | 1.04%   |
| Unity           | 3         | 0.78%   |
| GNOME Classic   | 2         | 0.52%   |
| Budgie          | 2         | 0.52%   |
| xmonad          | 1         | 0.26%   |
| Trinity         | 1         | 0.26%   |
| Openbox         | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |
| Deepin          | 1         | 0.26%   |
| awesome         | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 301       | 81.57%  |
| Wayland | 61        | 16.53%  |
| Unknown | 5         | 1.36%   |
| Tty     | 2         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 139       | 37.17%  |
| SDDM    | 88        | 23.53%  |
| LightDM | 48        | 12.83%  |
| GDM     | 41        | 10.96%  |
| GDM3    | 38        | 10.16%  |
| TDM     | 11        | 2.94%   |
| KDM     | 7         | 1.87%   |
| SLiM    | 2         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 218       | 58.76%  |
| en_US   | 87        | 23.45%  |
| Unknown | 26        | 7.01%   |
| es_ES   | 22        | 5.93%   |
| es_MX   | 8         | 2.16%   |
| es_US   | 4         | 1.08%   |
| C       | 3         | 0.81%   |
| es_CO   | 1         | 0.27%   |
| en_CA   | 1         | 0.27%   |
| de_DE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 265       | 72.6%   |
| EFI  | 100       | 27.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 275       | 74.73%  |
| Overlay | 45        | 12.23%  |
| Btrfs   | 24        | 6.52%   |
| Unknown | 8         | 2.17%   |
| Tmpfs   | 7         | 1.9%    |
| Xfs     | 6         | 1.63%   |
| Ext2    | 2         | 0.54%   |
| XXX4    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 42.12%  |
| MBR     | 109       | 29.62%  |
| GPT     | 104       | 28.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 302       | 82.07%  |
| Yes       | 66        | 17.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 225       | 61.81%  |
| Yes       | 139       | 38.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 40        | 11.11%  |
| Dell                                     | 37        | 10.28%  |
| Hewlett-Packard                          | 36        | 10%     |
| ASRock                                   | 32        | 8.89%   |
| Intel                                    | 29        | 8.06%   |
| VIT                                      | 28        | 7.78%   |
| ASUSTek Computer                         | 22        | 6.11%   |
| Pegatron                                 | 17        | 4.72%   |
| ECS                                      | 17        | 4.72%   |
| Gigabyte Technology                      | 14        | 3.89%   |
| Biostar                                  | 12        | 3.33%   |
| Acer                                     | 12        | 3.33%   |
| MSI                                      | 8         | 2.22%   |
| Foxconn                                  | 7         | 1.94%   |
| langchao                                 | 6         | 1.67%   |
| Unknown                                  | 6         | 1.67%   |
| Apple                                    | 4         | 1.11%   |
| Siragon                                  | 3         | 0.83%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 0.83%   |
| Inspur                                   | 3         | 0.83%   |
| Google                                   | 3         | 0.83%   |
| Toshiba                                  | 2         | 0.56%   |
| Samsung Electronics                      | 2         | 0.56%   |
| Notebook                                 | 2         | 0.56%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.28%   |
| UNIQCELL                                 | 1         | 0.28%   |
| Standard                                 | 1         | 0.28%   |
| Sony                                     | 1         | 0.28%   |
| Soncview                                 | 1         | 0.28%   |
| Panasonic                                | 1         | 0.28%   |
| Microsoft                                | 1         | 0.28%   |
| IP3 Tech                                 | 1         | 0.28%   |
| IBM                                      | 1         | 0.28%   |
| GPU Company                              | 1         | 0.28%   |
| Gateway                                  | 1         | 0.28%   |
| Exo                                      | 1         | 0.28%   |
| Clevo                                    | 1         | 0.28%   |
| AVITA                                    | 1         | 0.28%   |
| Alienware                                | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel powered classmate PC                            | 12        | 3.33%   |
| ECS H61H2-CM                                          | 10        | 2.78%   |
| VIT P2400                                             | 7         | 1.94%   |
| ASRock G41M-VS3                                       | 7         | 1.94%   |
| langchao 12345                                        | 6         | 1.67%   |
| Unknown                                               | 6         | 1.67%   |
| VIT P2402                                             | 5         | 1.39%   |
| ASRock N68-VS3 UCC                                    | 4         | 1.11%   |
| VIT P3400                                             | 3         | 0.83%   |
| VIT M2420                                             | 3         | 0.83%   |
| Shanghai Zhaoxin ZXE CRB                              | 3         | 0.83%   |
| Pegatron Compaq dx2400 Microtower                     | 3         | 0.83%   |
| HP Compaq 8200 Elite SFF PC                           | 3         | 0.83%   |
| Biostar G41D3                                         | 3         | 0.83%   |
| ASRock N68C-S UCC                                     | 3         | 0.83%   |
| VIT P1400                                             | 2         | 0.56%   |
| VIT M2421                                             | 2         | 0.56%   |
| VIT M2400-01                                          | 2         | 0.56%   |
| VIT Aptio CRB                                         | 2         | 0.56%   |
| Pegatron IPM41-D3                                     | 2         | 0.56%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 0.56%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 0.56%   |
| Intel H61                                             | 2         | 0.56%   |
| HP Pavilion dv5                                       | 2         | 0.56%   |
| HP Compaq Presario C700                               | 2         | 0.56%   |
| Google Candy                                          | 2         | 0.56%   |
| Gigabyte 970A-DS3P                                    | 2         | 0.56%   |
| ECS G31T-M7                                           | 2         | 0.56%   |
| Dell OptiPlex 9020                                    | 2         | 0.56%   |
| Dell OptiPlex 790                                     | 2         | 0.56%   |
| Dell Inspiron 1545                                    | 2         | 0.56%   |
| Biostar G41D3C                                        | 2         | 0.56%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 0.56%   |
| ASRock Wolfdale1333-D667                              | 2         | 0.56%   |
| ASRock 945GCM-S                                       | 2         | 0.56%   |
| Apple iMac11,2                                        | 2         | 0.56%   |
| Acer Aspire 4739Z                                     | 2         | 0.56%   |
| VIT P2423                                             | 1         | 0.28%   |
| VIT NP3020M3                                          | 1         | 0.28%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 14        | 3.89%   |
| Intel powered        | 12        | 3.33%   |
| Lenovo IdeaPad       | 11        | 3.06%   |
| HP Compaq            | 11        | 3.06%   |
| Acer Aspire          | 11        | 3.06%   |
| ECS H61H2-CM         | 10        | 2.78%   |
| Lenovo ThinkCentre   | 9         | 2.5%    |
| HP Pavilion          | 8         | 2.22%   |
| VIT P2400            | 7         | 1.94%   |
| Dell OptiPlex        | 7         | 1.94%   |
| Dell Latitude        | 7         | 1.94%   |
| ASRock G41M-VS3      | 7         | 1.94%   |
| Lenovo ThinkPad      | 6         | 1.67%   |
| langchao 12345       | 6         | 1.67%   |
| Dell Vostro          | 6         | 1.67%   |
| Unknown              | 6         | 1.67%   |
| VIT P2402            | 5         | 1.39%   |
| ASUS ASUS            | 5         | 1.39%   |
| ASRock N68-VS3       | 5         | 1.39%   |
| Pegatron Compaq      | 4         | 1.11%   |
| Lenovo 3000          | 4         | 1.11%   |
| HP Laptop            | 4         | 1.11%   |
| VIT P3400            | 3         | 0.83%   |
| VIT M2420            | 3         | 0.83%   |
| Shanghai Zhaoxin ZXE | 3         | 0.83%   |
| Biostar G41D3        | 3         | 0.83%   |
| ASRock N68C-S        | 3         | 0.83%   |
| VIT P1400            | 2         | 0.56%   |
| VIT M2421            | 2         | 0.56%   |
| VIT M2400-01         | 2         | 0.56%   |
| VIT Aptio            | 2         | 0.56%   |
| Pegatron IPM41-D3    | 2         | 0.56%   |
| Lenovo Legion        | 2         | 0.56%   |
| Intel H61            | 2         | 0.56%   |
| Intel DG41TY         | 2         | 0.56%   |
| HP Presario          | 2         | 0.56%   |
| HP ENVY              | 2         | 0.56%   |
| HP EliteDesk         | 2         | 0.56%   |
| HP EliteBook         | 2         | 0.56%   |
| Google Candy         | 2         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 63        | 17.5%   |
| 2010    | 49        | 13.61%  |
| 2012    | 37        | 10.28%  |
| 2013    | 28        | 7.78%   |
| 2008    | 28        | 7.78%   |
| 2007    | 24        | 6.67%   |
| 2014    | 21        | 5.83%   |
| 2022    | 15        | 4.17%   |
| 2020    | 15        | 4.17%   |
| 2009    | 13        | 3.61%   |
| 2021    | 11        | 3.06%   |
| 2019    | 11        | 3.06%   |
| 2018    | 9         | 2.5%    |
| 2017    | 8         | 2.22%   |
| 2015    | 8         | 2.22%   |
| 2006    | 8         | 2.22%   |
| 2016    | 6         | 1.67%   |
| 2023    | 2         | 0.56%   |
| Unknown | 2         | 0.56%   |
| 2005    | 1         | 0.28%   |
| 2002    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 177       | 49.17%  |
| Notebook    | 162       | 45%     |
| All in one  | 7         | 1.94%   |
| Tablet      | 5         | 1.39%   |
| Mini pc     | 4         | 1.11%   |
| Server      | 3         | 0.83%   |
| Convertible | 2         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 355       | 98.61%  |
| Enabled  | 5         | 1.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 357       | 99.17%  |
| Yes  | 3         | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 105       | 28.61%  |
| 4.01-8.0    | 80        | 21.8%   |
| 1.01-2.0    | 60        | 16.35%  |
| 8.01-16.0   | 53        | 14.44%  |
| 16.01-24.0  | 37        | 10.08%  |
| 2.01-3.0    | 15        | 4.09%   |
| 32.01-64.0  | 8         | 2.18%   |
| 24.01-32.0  | 4         | 1.09%   |
| 0.51-1.0    | 3         | 0.82%   |
| 64.01-256.0 | 2         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 158       | 39.5%   |
| 2.01-3.0   | 100       | 25%     |
| 0.51-1.0   | 50        | 12.5%   |
| 4.01-8.0   | 44        | 11%     |
| 3.01-4.0   | 37        | 9.25%   |
| 8.01-16.0  | 5         | 1.25%   |
| 0.01-0.5   | 5         | 1.25%   |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 225       | 60.98%  |
| 2      | 116       | 31.44%  |
| 3      | 21        | 5.69%   |
| 4      | 5         | 1.36%   |
| 6      | 1         | 0.27%   |
| 0      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 56.71%  |
| Yes       | 158       | 43.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 331       | 91.44%  |
| No        | 31        | 8.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 73.08%  |
| No        | 98        | 26.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 233       | 64.19%  |
| Yes       | 130       | 35.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 360       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Caracas                  | 160       | 41.34%  |
| Maracaibo                | 29        | 7.49%   |
| Maracay                  | 18        | 4.65%   |
| Valencia                 | 17        | 4.39%   |
| Barquisimeto             | 16        | 4.13%   |
| San Cristóbal           | 14        | 3.62%   |
| Mérida                  | 10        | 2.58%   |
| Barcelona                | 10        | 2.58%   |
| San Carlos del Zulia     | 8         | 2.07%   |
| Maturín                 | 8         | 2.07%   |
| Ciudad Guayana           | 8         | 2.07%   |
| Barinas                  | 5         | 1.29%   |
| Porlamar                 | 4         | 1.03%   |
| Ciudad Bolívar          | 4         | 1.03%   |
| Vigia                    | 3         | 0.78%   |
| San Antonio de Los Altos | 3         | 0.78%   |
| Parroquia El Recreo      | 3         | 0.78%   |
| Lecherias                | 3         | 0.78%   |
| La Guaira                | 3         | 0.78%   |
| Guatire                  | 3         | 0.78%   |
| Carrizal                 | 3         | 0.78%   |
| Acarigua                 | 3         | 0.78%   |
| San Juan Bautista        | 2         | 0.52%   |
| Los Teques               | 2         | 0.52%   |
| Los Palos Grandes        | 2         | 0.52%   |
| Las Vegas                | 2         | 0.52%   |
| Guarenas                 | 2         | 0.52%   |
| Cua                      | 2         | 0.52%   |
| Cambural                 | 2         | 0.52%   |
| Cagua                    | 2         | 0.52%   |
| Cabudare                 | 2         | 0.52%   |
| Anaco                    | 2         | 0.52%   |
| Villa de Cura            | 1         | 0.26%   |
| Valle de La Pascua       | 1         | 0.26%   |
| Tucupita                 | 1         | 0.26%   |
| Tucape                   | 1         | 0.26%   |
| Santa Rita               | 1         | 0.26%   |
| San Francisco            | 1         | 0.26%   |
| San Felipe               | 1         | 0.26%   |
| San Diego                | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 113       | 156    | 23.84%  |
| Seagate                   | 104       | 151    | 21.94%  |
| Hitachi                   | 45        | 62     | 9.49%   |
| Toshiba                   | 37        | 40     | 7.81%   |
| Samsung Electronics       | 35        | 39     | 7.38%   |
| Kingston                  | 16        | 20     | 3.38%   |
| Unknown                   | 13        | 18     | 2.74%   |
| Intel                     | 10        | 13     | 2.11%   |
| SanDisk                   | 9         | 14     | 1.9%    |
| SK hynix                  | 8         | 9      | 1.69%   |
| PNY                       | 7         | 8      | 1.48%   |
| Maxtor                    | 7         | 7      | 1.48%   |
| HGST                      | 7         | 7      | 1.48%   |
| Crucial                   | 7         | 9      | 1.48%   |
| Micron Technology         | 5         | 8      | 1.05%   |
| addlink                   | 5         | 5      | 1.05%   |
| Team                      | 4         | 4      | 0.84%   |
| SPCC                      | 4         | 7      | 0.84%   |
| Patriot                   | 4         | 4      | 0.84%   |
| LITEONIT                  | 4         | 8      | 0.84%   |
| Fujitsu                   | 4         | 4      | 0.84%   |
| Silicon Motion            | 2         | 2      | 0.42%   |
| HUAWEI                    | 2         | 2      | 0.42%   |
| BIWIN                     | 2         | 3      | 0.42%   |
| A-DATA Technology         | 2         | 2      | 0.42%   |
| Vaseky                    | 1         | 1      | 0.21%   |
| PUSKILL                   | 1         | 1      | 0.21%   |
| Phison Electronics        | 1         | 1      | 0.21%   |
| Phison                    | 1         | 1      | 0.21%   |
| Netac                     | 1         | 1      | 0.21%   |
| Micron/Crucial Technology | 1         | 1      | 0.21%   |
| Lexar                     | 1         | 1      | 0.21%   |
| KingFast                  | 1         | 3      | 0.21%   |
| JMicron Technology        | 1         | 1      | 0.21%   |
| Intenso                   | 1         | 1      | 0.21%   |
| IBM/Hitachi               | 1         | 2      | 0.21%   |
| HPE                       | 1         | 2      | 0.21%   |
| ExcelStor                 | 1         | 1      | 0.21%   |
| Emtec                     | 1         | 1      | 0.21%   |
| Dogfish                   | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 16        | 3.09%   |
| Toshiba DT01ACA050 500GB            | 11        | 2.13%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 9         | 1.74%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 1.16%   |
| Seagate ST320LM000 HM321HI 320GB    | 6         | 1.16%   |
| Samsung HD502HJ 500GB               | 6         | 1.16%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 1.16%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.97%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 5         | 0.97%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.77%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4         | 0.77%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4         | 0.77%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.77%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.77%   |
| Seagate ST3320418AS 320GB           | 4         | 0.77%   |
| Seagate ST320LT012-9WS14C 320GB     | 4         | 0.77%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 4         | 0.77%   |
| Samsung HD161HJ 160GB               | 4         | 0.77%   |
| Hitachi HTS543225L9A300 250GB       | 4         | 0.77%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.58%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.58%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 3         | 0.58%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.58%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 0.58%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.58%   |
| Toshiba MK3275GSX 320GB             | 3         | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 0.58%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.58%   |
| Samsung HD161GJ 160GB               | 3         | 0.58%   |
| Maxtor STM3160215AS 160GB           | 3         | 0.58%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.58%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 0.58%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.58%   |
| Hitachi HDS728080PLA380 82GB        | 3         | 0.58%   |
| Hitachi HDS5C1050CLA382 500GB       | 3         | 0.58%   |
| HGST HTS545050A7E380 500GB          | 3         | 0.58%   |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.39%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 110       | 150    | 32.54%  |
| Seagate             | 101       | 148    | 29.88%  |
| Hitachi             | 45        | 62     | 13.31%  |
| Toshiba             | 36        | 39     | 10.65%  |
| Samsung Electronics | 23        | 26     | 6.8%    |
| Maxtor              | 7         | 7      | 2.07%   |
| HGST                | 7         | 7      | 2.07%   |
| Fujitsu             | 4         | 4      | 1.18%   |
| Unknown             | 2         | 2      | 0.59%   |
| IBM/Hitachi         | 1         | 2      | 0.3%    |
| HPE                 | 1         | 1      | 0.3%    |
| ExcelStor           | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 18     | 18.92%  |
| Samsung Electronics | 7         | 8      | 9.46%   |
| PNY                 | 7         | 8      | 9.46%   |
| Crucial             | 7         | 9      | 9.46%   |
| Patriot             | 4         | 4      | 5.41%   |
| LITEONIT            | 4         | 8      | 5.41%   |
| Team                | 3         | 3      | 4.05%   |
| SPCC                | 3         | 5      | 4.05%   |
| SanDisk             | 3         | 4      | 4.05%   |
| addlink             | 3         | 3      | 4.05%   |
| SK hynix            | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| Vaseky              | 1         | 1      | 1.35%   |
| Toshiba             | 1         | 1      | 1.35%   |
| PUSKILL             | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 3      | 1.35%   |
| Lexar               | 1         | 1      | 1.35%   |
| KingFast            | 1         | 3      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| Intenso             | 1         | 1      | 1.35%   |
| Intel               | 1         | 1      | 1.35%   |
| Emtec               | 1         | 1      | 1.35%   |
| Dogfish             | 1         | 1      | 1.35%   |
| Dell                | 1         | 2      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| BIWIN               | 1         | 2      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 276       | 449    | 67.98%  |
| SSD     | 70        | 95     | 17.24%  |
| NVMe    | 46        | 64     | 11.33%  |
| MMC     | 8         | 11     | 1.97%   |
| Unknown | 6         | 6      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 316       | 540    | 83.16%  |
| NVMe | 46        | 64     | 12.11%  |
| SAS  | 10        | 10     | 2.63%   |
| MMC  | 8         | 11     | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 284       | 432    | 79.11%  |
| 0.51-1.0   | 55        | 79     | 15.32%  |
| 1.01-2.0   | 12        | 20     | 3.34%   |
| 3.01-4.0   | 4         | 8      | 1.11%   |
| 2.01-3.0   | 2         | 3      | 0.56%   |
| 4.01-10.0  | 2         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 128       | 33.33%  |
| 101-250        | 87        | 22.66%  |
| 501-1000       | 48        | 12.5%   |
| 1-20           | 41        | 10.68%  |
| 51-100         | 30        | 7.81%   |
| 21-50          | 17        | 4.43%   |
| 1001-2000      | 16        | 4.17%   |
| 2001-3000      | 7         | 1.82%   |
| Unknown        | 6         | 1.56%   |
| More than 3000 | 4         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 39.39%  |
| 21-50          | 72        | 18.18%  |
| 101-250        | 55        | 13.89%  |
| 51-100         | 44        | 11.11%  |
| 251-500        | 34        | 8.59%   |
| 501-1000       | 18        | 4.55%   |
| Unknown        | 6         | 1.52%   |
| 1001-2000      | 5         | 1.26%   |
| 2001-3000      | 4         | 1.01%   |
| More than 3000 | 2         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6         | 7      | 5.41%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4         | 5      | 3.6%    |
| Toshiba DT01ACA050 500GB          | 4         | 5      | 3.6%    |
| Hitachi HTS543225L9A300 250GB     | 4         | 4      | 3.6%    |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 1.8%    |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 1.8%    |
| WDC WD3200AAJS-08L7A0 320GB       | 2         | 3      | 1.8%    |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 1.8%    |
| Toshiba MK3275GSX 320GB           | 2         | 2      | 1.8%    |
| Seagate ST9500325AS 500GB         | 2         | 2      | 1.8%    |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 1.8%    |
| Samsung Electronics HM321HI 320GB | 2         | 2      | 1.8%    |
| Samsung Electronics HD161GJ 160GB | 2         | 2      | 1.8%    |
| Maxtor STM3160215AS 160GB         | 2         | 2      | 1.8%    |
| Hitachi HTS725050A9A364 500GB     | 2         | 2      | 1.8%    |
| Hitachi HDS728080PLA380 82GB      | 2         | 2      | 1.8%    |
| Hitachi HDS721616PLA380 160GB     | 2         | 2      | 1.8%    |
| HGST HTS545050A7E380 500GB        | 2         | 2      | 1.8%    |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 0.9%    |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 0.9%    |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 0.9%    |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 0.9%    |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 2      | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 1         | 1      | 0.9%    |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 0.9%    |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 0.9%    |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 0.9%    |
| WDC WD3200BEVT-00A0RT0 320GB      | 1         | 1      | 0.9%    |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 0.9%    |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 1      | 0.9%    |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 0.9%    |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 0.9%    |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 0.9%    |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 0.9%    |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 0.9%    |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 0.9%    |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 0.9%    |
| Toshiba MK3265GSX 320GB           | 1         | 1      | 0.9%    |
| Toshiba MK2565GSX 250GB           | 1         | 1      | 0.9%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 31     | 27.18%  |
| WDC                 | 23        | 33     | 22.33%  |
| Hitachi             | 22        | 22     | 21.36%  |
| Toshiba             | 10        | 12     | 9.71%   |
| Samsung Electronics | 9         | 10     | 8.74%   |
| Maxtor              | 3         | 3      | 2.91%   |
| HGST                | 3         | 3      | 2.91%   |
| Intel               | 2         | 2      | 1.94%   |
| JMicron Technology  | 1         | 1      | 0.97%   |
| IBM/Hitachi         | 1         | 2      | 0.97%   |
| ExcelStor           | 1         | 1      | 0.97%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 31     | 28%     |
| WDC                 | 23        | 33     | 23%     |
| Hitachi             | 22        | 22     | 22%     |
| Toshiba             | 10        | 12     | 10%     |
| Samsung Electronics | 9         | 10     | 9%      |
| Maxtor              | 3         | 3      | 3%      |
| HGST                | 3         | 3      | 3%      |
| IBM/Hitachi         | 1         | 2      | 1%      |
| ExcelStor           | 1         | 1      | 1%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 86        | 117    | 96.63%  |
| NVMe | 2         | 2      | 2.25%   |
| SSD  | 1         | 1      | 1.12%   |

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
| Detected | 188       | 342    | 47.72%  |
| Works    | 114       | 159    | 28.93%  |
| Malfunc  | 88        | 120    | 22.34%  |
| Failed   | 4         | 4      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 286       | 71.5%   |
| AMD                         | 40        | 10%     |
| Nvidia                      | 17        | 4.25%   |
| SanDisk                     | 9         | 2.25%   |
| SK hynix                    | 6         | 1.5%    |
| Marvell Technology Group    | 6         | 1.5%    |
| JMicron Technology          | 6         | 1.5%    |
| Samsung Electronics         | 5         | 1.25%   |
| Phison Electronics          | 4         | 1%      |
| Micron Technology           | 4         | 1%      |
| Jiangsu Huacun Elec.        | 4         | 1%      |
| VIA Technologies            | 3         | 0.75%   |
| Silicon Motion              | 3         | 0.75%   |
| Kingston Technology Company | 2         | 0.5%    |
| ASMedia Technology          | 2         | 0.5%    |
| Micron/Crucial Technology   | 1         | 0.25%   |
| MAXIO Technology (Hangzhou) | 1         | 0.25%   |
| Adaptec                     | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50        | 9.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39        | 7.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 25        | 4.74%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17        | 3.23%   |
| Nvidia MCP61 SATA Controller                                                            | 16        | 3.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 16        | 3.04%   |
| Nvidia MCP61 IDE                                                                        | 14        | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 2.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 9         | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.33%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7         | 1.33%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.95%   |
| Jiangsu Huacun Elec. Non-Volatile memory controller                                     | 4         | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.76%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.57%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 210       | 50.36%  |
| IDE  | 136       | 32.61%  |
| NVMe | 46        | 11.03%  |
| RAID | 23        | 5.52%   |
| SAS  | 1         | 0.24%   |
| SCSI | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 295       | 81.94%  |
| AMD          | 62        | 17.22%  |
| CentaurHauls | 3         | 0.83%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 9         | 2.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 7         | 1.94%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 7         | 1.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 6         | 1.67%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 6         | 1.67%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 5         | 1.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 1.39%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 5         | 1.39%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz    | 4         | 1.11%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 4         | 1.11%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 1.11%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 4         | 1.11%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 4         | 1.11%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 3         | 0.83%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 3         | 0.83%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 3         | 0.83%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 3         | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                    | 3         | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3         | 0.83%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 0.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 0.83%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3         | 0.83%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3         | 0.83%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 0.83%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 3         | 0.83%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 0.83%   |
| AMD Sempron 145 Processor                      | 3         | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 3         | 0.83%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.56%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 2         | 0.56%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 2         | 0.56%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 2         | 0.56%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 2         | 0.56%   |
| Intel Pentium CPU G640 @ 2.80GHz               | 2         | 0.56%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 2         | 0.56%   |
| Intel Pentium 4 CPU 3.20GHz                    | 2         | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 57        | 15.83%  |
| Intel Core i3                        | 39        | 10.83%  |
| Intel Pentium Dual-Core              | 34        | 9.44%   |
| Intel Core 2 Duo                     | 26        | 7.22%   |
| Intel Pentium                        | 25        | 6.94%   |
| Intel Core i7                        | 24        | 6.67%   |
| Intel Celeron                        | 24        | 6.67%   |
| Other                                | 19        | 5.28%   |
| Intel Pentium Dual                   | 11        | 3.06%   |
| Intel Atom                           | 11        | 3.06%   |
| AMD Ryzen 5                          | 11        | 3.06%   |
| Intel Xeon                           | 7         | 1.94%   |
| AMD Sempron                          | 7         | 1.94%   |
| Intel Pentium 4                      | 6         | 1.67%   |
| Intel Core 2 Quad                    | 6         | 1.67%   |
| AMD Ryzen 7                          | 6         | 1.67%   |
| Intel Core 2                         | 5         | 1.39%   |
| AMD FX                               | 4         | 1.11%   |
| AMD Athlon II X2                     | 4         | 1.11%   |
| AMD Phenom II X4                     | 3         | 0.83%   |
| Intel Pentium D                      | 2         | 0.56%   |
| Intel Genuine                        | 2         | 0.56%   |
| AMD Ryzen 3                          | 2         | 0.56%   |
| AMD Phenom                           | 2         | 0.56%   |
| AMD E1                               | 2         | 0.56%   |
| AMD Athlon II X4                     | 2         | 0.56%   |
| AMD Athlon 64 X2                     | 2         | 0.56%   |
| AMD Athlon                           | 2         | 0.56%   |
| AMD A6                               | 2         | 0.56%   |
| AMD A10                              | 2         | 0.56%   |
| Intel Pentium Silver                 | 1         | 0.28%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.28%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.28%   |
| AMD Quad-Core                        | 1         | 0.28%   |
| AMD Phenom II X2                     | 1         | 0.28%   |
| AMD Mobile Sempron                   | 1         | 0.28%   |
| AMD E                                | 1         | 0.28%   |
| AMD C-70                             | 1         | 0.28%   |
| AMD Athlon II                        | 1         | 0.28%   |
| AMD A8                               | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 213       | 59.17%  |
| 4       | 92        | 25.56%  |
| 1       | 23        | 6.39%   |
| 6       | 12        | 3.33%   |
| 8       | 9         | 2.5%    |
| 3       | 5         | 1.39%   |
| Unknown | 4         | 1.11%   |
| 14      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 360       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 208       | 57.78%  |
| 2       | 148       | 41.11%  |
| Unknown | 4         | 1.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 349       | 96.94%  |
| 64-bit         | 5         | 1.39%   |
| 32-bit         | 5         | 1.39%   |
| Unknown        | 1         | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 26.34%  |
| 0x1067a    | 43        | 11.56%  |
| 0x206a7    | 39        | 10.48%  |
| 0x306a9    | 28        | 7.53%   |
| 0x6fd      | 13        | 3.49%   |
| 0x306c3    | 9         | 2.42%   |
| 0x106ca    | 7         | 1.88%   |
| 0x806c1    | 6         | 1.61%   |
| 0x30673    | 6         | 1.61%   |
| 0x806e9    | 5         | 1.34%   |
| 0x30678    | 5         | 1.34%   |
| 0x20655    | 5         | 1.34%   |
| 0x010000c8 | 5         | 1.34%   |
| 0xf65      | 4         | 1.08%   |
| 0x6fb      | 4         | 1.08%   |
| 0x6f2      | 3         | 0.81%   |
| 0x406e3    | 3         | 0.81%   |
| 0x40651    | 3         | 0.81%   |
| 0x106a5    | 3         | 0.81%   |
| 0x10676    | 3         | 0.81%   |
| 0x05000119 | 3         | 0.81%   |
| 0x010000c7 | 3         | 0.81%   |
| 0x010000b6 | 3         | 0.81%   |
| 0xa0671    | 2         | 0.54%   |
| 0x906e9    | 2         | 0.54%   |
| 0x806ec    | 2         | 0.54%   |
| 0x806ea    | 2         | 0.54%   |
| 0x806d1    | 2         | 0.54%   |
| 0x506e3    | 2         | 0.54%   |
| 0x406c4    | 2         | 0.54%   |
| 0x306d4    | 2         | 0.54%   |
| 0x20652    | 2         | 0.54%   |
| 0x08608103 | 2         | 0.54%   |
| 0x08600104 | 2         | 0.54%   |
| 0x08108102 | 2         | 0.54%   |
| 0x0810100b | 2         | 0.54%   |
| 0x06000852 | 2         | 0.54%   |
| 0x0600063e | 2         | 0.54%   |
| 0x03000027 | 2         | 0.54%   |
| 0x02000057 | 2         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 55        | 15.28%  |
| SandyBridge      | 54        | 15%     |
| IvyBridge        | 40        | 11.11%  |
| Core             | 32        | 8.89%   |
| K10              | 18        | 5%      |
| Haswell          | 17        | 4.72%   |
| KabyLake         | 16        | 4.44%   |
| Silvermont       | 15        | 4.17%   |
| Westmere         | 13        | 3.61%   |
| Bonnell          | 10        | 2.78%   |
| Unknown          | 9         | 2.5%    |
| NetBurst         | 8         | 2.22%   |
| TigerLake        | 7         | 1.94%   |
| Zen+             | 6         | 1.67%   |
| Zen 2            | 5         | 1.39%   |
| Skylake          | 5         | 1.39%   |
| K8 Hammer        | 5         | 1.39%   |
| Icelake          | 5         | 1.39%   |
| Bobcat           | 4         | 1.11%   |
| Zen              | 3         | 0.83%   |
| Piledriver       | 3         | 0.83%   |
| Nehalem          | 3         | 0.83%   |
| Goldmont plus    | 3         | 0.83%   |
| Excavator        | 3         | 0.83%   |
| Broadwell        | 3         | 0.83%   |
| Alderlake Hybrid | 3         | 0.83%   |
| Zen 3            | 2         | 0.56%   |
| K8 & K10 hybrid  | 2         | 0.56%   |
| K10 Llano        | 2         | 0.56%   |
| Jaguar           | 2         | 0.56%   |
| CometLake        | 2         | 0.56%   |
| Bulldozer        | 2         | 0.56%   |
| Steamroller      | 1         | 0.28%   |
| P6               | 1         | 0.28%   |
| Goldmont         | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 247       | 64.49%  |
| AMD                        | 68        | 17.75%  |
| Nvidia                     | 60        | 15.67%  |
| Zhaoxin                    | 3         | 0.78%   |
| VIA Technologies           | 3         | 0.78%   |
| Matrox Electronics Systems | 1         | 0.26%   |
| ASPEED Technology          | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 12.06%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 24        | 6.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 5.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.51%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 10        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 2.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 2.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 2.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.01%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 1.01%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.01%   |
| Intel HD Graphics 620                                                                    | 4         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.01%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 1.01%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 1.01%   |
| AMD Lucienne                                                                             | 4         | 1.01%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 3         | 0.75%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 0.75%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 0.75%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 3         | 0.75%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.75%   |
| Intel HD Graphics 630                                                                    | 3         | 0.75%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.75%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 3         | 0.75%   |
| AMD Renoir                                                                               | 3         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.75%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 3         | 0.75%   |
| Nvidia TU117M                                                                            | 2         | 0.5%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 226       | 62.6%   |
| 1 x AMD         | 60        | 16.62%  |
| 1 x Nvidia      | 48        | 13.3%   |
| Intel + Nvidia  | 8         | 2.22%   |
| 2 x Intel       | 3         | 0.83%   |
| 2 x AMD         | 3         | 0.83%   |
| 1 x Zhaoxin     | 3         | 0.83%   |
| 1 x VIA         | 3         | 0.83%   |
| AMD + Nvidia    | 3         | 0.83%   |
| Intel + AMD     | 2         | 0.55%   |
| Nvidia + ASPEED | 1         | 0.28%   |
| 1 x Matrox      | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 312       | 86.19%  |
| Proprietary | 30        | 8.29%   |
| Unknown     | 20        | 5.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 248       | 67.21%  |
| 0.01-0.5   | 46        | 12.47%  |
| 0.51-1.0   | 39        | 10.57%  |
| 1.01-2.0   | 25        | 6.78%   |
| 3.01-4.0   | 9         | 2.44%   |
| 5.01-6.0   | 2         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 66        | 18.91%  |
| AU Optronics                          | 30        | 8.6%    |
| BOE                                   | 28        | 8.02%   |
| LG Display                            | 22        | 6.3%    |
| Hewlett-Packard                       | 22        | 6.3%    |
| Goldstar                              | 20        | 5.73%   |
| Chimei Innolux                        | 20        | 5.73%   |
| Lenovo                                | 15        | 4.3%    |
| Dell                                  | 14        | 4.01%   |
| Toshiba                               | 11        | 3.15%   |
| Acer                                  | 11        | 3.15%   |
| InfoVision                            | 10        | 2.87%   |
| AOC                                   | 10        | 2.87%   |
| Chi Mei Optoelectronics               | 7         | 2.01%   |
| Vita                                  | 6         | 1.72%   |
| LG Philips                            | 6         | 1.72%   |
| HannStar                              | 4         | 1.15%   |
| BenQ                                  | 4         | 1.15%   |
| Apple                                 | 4         | 1.15%   |
| LG Electronics                        | 3         | 0.86%   |
| ViewSonic                             | 2         | 0.57%   |
| Unknown (XXX)                         | 2         | 0.57%   |
| Sony                                  | 2         | 0.57%   |
| PANDA                                 | 2         | 0.57%   |
| MStar                                 | 2         | 0.57%   |
| ITL                                   | 2         | 0.57%   |
| Envision                              | 2         | 0.57%   |
| Vizio                                 | 1         | 0.29%   |
| Unknown (CEA)                         | 1         | 0.29%   |
| Toshiba Matsushita Display Technology | 1         | 0.29%   |
| TCL                                   | 1         | 0.29%   |
| Sharp                                 | 1         | 0.29%   |
| Sceptre Tech                          | 1         | 0.29%   |
| Plain Tree Systems                    | 1         | 0.29%   |
| PEGA                                  | 1         | 0.29%   |
| Parker                                | 1         | 0.29%   |
| NEC Computers                         | 1         | 0.29%   |
| MSI                                   | 1         | 0.29%   |
| LSC                                   | 1         | 0.29%   |
| LED                                   | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 8         | 2.25%   |
| Vita V195EW-W VIT1950 1600x900 430x240mm 19.4-inch                   | 6         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 6         | 1.69%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 1.69%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 5         | 1.4%    |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 5         | 1.4%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.12%   |
| Toshiba TV TSB0206 1920x1080                                         | 3         | 0.84%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3         | 0.84%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 0.84%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3         | 0.84%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 0.84%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 2         | 0.56%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.56%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 2         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.56%   |
| MStar Demo MST0030 2288x1430 708x398mm 32.0-inch                     | 2         | 0.56%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.56%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2         | 0.56%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.56%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.56%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2         | 0.56%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                   | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.56%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.56%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 2         | 0.56%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch       | 2         | 0.56%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.56%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2         | 0.56%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.28%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 125       | 36.98%  |
| 1920x1080 (FHD)    | 76        | 22.49%  |
| 1280x1024 (SXGA)   | 32        | 9.47%   |
| 1440x900 (WXGA+)   | 23        | 6.8%    |
| 1600x900 (HD+)     | 18        | 5.33%   |
| 1280x800 (WXGA)    | 15        | 4.44%   |
| 1360x768           | 9         | 2.66%   |
| 1680x1050 (WSXGA+) | 8         | 2.37%   |
| 1024x768 (XGA)     | 8         | 2.37%   |
| 3840x2160 (4K)     | 5         | 1.48%   |
| 1920x1200 (WUXGA)  | 4         | 1.18%   |
| 1280x720 (HD)      | 4         | 1.18%   |
| 2560x1440 (QHD)    | 3         | 0.89%   |
| 1024x600           | 3         | 0.89%   |
| Unknown            | 2         | 0.59%   |
| 3840x1080          | 1         | 0.3%    |
| 3240x2160          | 1         | 0.3%    |
| 2240x1400          | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 21.55%  |
| 18      | 42        | 12.07%  |
| 14      | 37        | 10.63%  |
| 17      | 32        | 9.2%    |
| 13      | 32        | 9.2%    |
| 21      | 29        | 8.33%   |
| 19      | 22        | 6.32%   |
| Unknown | 15        | 4.31%   |
| 23      | 11        | 3.16%   |
| 10      | 10        | 2.87%   |
| 20      | 9         | 2.59%   |
| 11      | 5         | 1.44%   |
| 27      | 4         | 1.15%   |
| 22      | 4         | 1.15%   |
| 74      | 3         | 0.86%   |
| 16      | 3         | 0.86%   |
| 72      | 2         | 0.57%   |
| 52      | 2         | 0.57%   |
| 32      | 2         | 0.57%   |
| 31      | 2         | 0.57%   |
| 24      | 2         | 0.57%   |
| 12      | 2         | 0.57%   |
| 54      | 1         | 0.29%   |
| 42      | 1         | 0.29%   |
| 39      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 46.65%  |
| 401-500     | 98        | 28.57%  |
| 201-300     | 21        | 6.12%   |
| 351-400     | 19        | 5.54%   |
| 501-600     | 16        | 4.66%   |
| Unknown     | 15        | 4.37%   |
| 1501-2000   | 5         | 1.46%   |
| 1001-1500   | 3         | 0.87%   |
| 701-800     | 2         | 0.58%   |
| 601-700     | 2         | 0.58%   |
| 801-900     | 1         | 0.29%   |
| 901-1000    | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 218       | 67.49%  |
| 16/10   | 53        | 16.41%  |
| 5/4     | 30        | 9.29%   |
| Unknown | 11        | 3.41%   |
| 4/3     | 8         | 2.48%   |
| 3/2     | 3         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 21.61%  |
| 81-90          | 66        | 19.02%  |
| 141-150        | 55        | 15.85%  |
| 151-200        | 51        | 14.7%   |
| 201-250        | 33        | 9.51%   |
| Unknown        | 15        | 4.32%   |
| 41-50          | 10        | 2.88%   |
| 121-130        | 10        | 2.88%   |
| More than 1000 | 8         | 2.31%   |
| 51-60          | 5         | 1.44%   |
| 351-500        | 4         | 1.15%   |
| 301-350        | 4         | 1.15%   |
| 71-80          | 2         | 0.58%   |
| 61-70          | 2         | 0.58%   |
| 251-300        | 2         | 0.58%   |
| 131-140        | 2         | 0.58%   |
| 501-1000       | 2         | 0.58%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 148       | 43.15%  |
| 101-120       | 111       | 32.36%  |
| 121-160       | 53        | 15.45%  |
| Unknown       | 15        | 4.37%   |
| 1-50          | 11        | 3.21%   |
| 161-240       | 3         | 0.87%   |
| More than 240 | 2         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 302       | 82.74%  |
| 2     | 36        | 9.86%   |
| 0     | 24        | 6.58%   |
| 3     | 3         | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 224       | 39.23%  |
| Intel                             | 102       | 17.86%  |
| Qualcomm Atheros                  | 101       | 17.69%  |
| Broadcom                          | 30        | 5.25%   |
| Ralink                            | 18        | 3.15%   |
| Nvidia                            | 17        | 2.98%   |
| Ralink Technology                 | 11        | 1.93%   |
| Xiaomi                            | 8         | 1.4%    |
| Marvell Technology Group          | 7         | 1.23%   |
| TP-Link                           | 6         | 1.05%   |
| Qualcomm Atheros Communications   | 6         | 1.05%   |
| MediaTek                          | 6         | 1.05%   |
| Broadcom Limited                  | 6         | 1.05%   |
| JMicron Technology                | 4         | 0.7%    |
| VIA Technologies                  | 3         | 0.53%   |
| Samsung Electronics               | 3         | 0.53%   |
| Trendchip Technologies            | 2         | 0.35%   |
| Sundance Technology Inc / IC Plus | 2         | 0.35%   |
| Mercucys                          | 2         | 0.35%   |
| D-Link System                     | 2         | 0.35%   |
| ZyXEL Communications              | 1         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| National Semiconductor            | 1         | 0.18%   |
| Motorola PCS                      | 1         | 0.18%   |
| Motorola BCS                      | 1         | 0.18%   |
| ICS Advent                        | 1         | 0.18%   |
| Huawei Technologies               | 1         | 0.18%   |
| Digium                            | 1         | 0.18%   |
| Davicom Semiconductor             | 1         | 0.18%   |
| ASIX Electronics                  | 1         | 0.18%   |
| AMD                               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 134       | 20.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 45        | 7.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 23        | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 2.8%    |
| Nvidia MCP61 Ethernet                                                         | 16        | 2.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 11        | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 11        | 1.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 11        | 1.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9         | 1.4%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 9         | 1.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 8         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 8         | 1.25%   |
| Intel Wireless 7265                                                           | 8         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 7         | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 7         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6         | 0.93%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 5         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                               | 5         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 5         | 0.78%   |
| Intel Wireless 7260                                                           | 5         | 0.78%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 4         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 0.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4         | 0.62%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 4         | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 4         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 4         | 0.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.62%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 4         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 0.62%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 0.62%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.62%   |
| Intel WiFi Link 5100                                                          | 4         | 0.62%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 74        | 26.62%  |
| Realtek Semiconductor           | 69        | 24.82%  |
| Intel                           | 64        | 23.02%  |
| Ralink                          | 18        | 6.47%   |
| Broadcom                        | 16        | 5.76%   |
| Ralink Technology               | 11        | 3.96%   |
| Qualcomm Atheros Communications | 6         | 2.16%   |
| MediaTek                        | 6         | 2.16%   |
| TP-Link                         | 5         | 1.8%    |
| Xiaomi                          | 2         | 0.72%   |
| Mercucys                        | 2         | 0.72%   |
| D-Link System                   | 2         | 0.72%   |
| Broadcom Limited                | 2         | 0.72%   |
| Marvell Technology Group        | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 23        | 8.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 11        | 3.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 11        | 3.96%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9         | 3.24%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 8         | 2.88%   |
| Intel Wireless 7265                                                            | 8         | 2.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 2.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7         | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 6         | 2.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5         | 1.8%    |
| Ralink MT7601U Wireless Adapter                                                | 5         | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 5         | 1.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 5         | 1.8%    |
| Intel Wireless 7260                                                            | 5         | 1.8%    |
| Intel Wi-Fi 6 AX201                                                            | 5         | 1.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 4         | 1.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 1.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4         | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 4         | 1.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 4         | 1.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 1.44%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 1.44%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4         | 1.44%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.44%   |
| Intel WiFi Link 5100                                                           | 4         | 1.44%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 1.44%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.44%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.08%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.08%   |
| Intel Wireless 3165                                                            | 3         | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 3         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                                 | 3         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 3         | 1.08%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                              | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 191       | 53.95%  |
| Intel                             | 56        | 15.82%  |
| Qualcomm Atheros                  | 37        | 10.45%  |
| Nvidia                            | 17        | 4.8%    |
| Broadcom                          | 15        | 4.24%   |
| Xiaomi                            | 6         | 1.69%   |
| Marvell Technology Group          | 6         | 1.69%   |
| JMicron Technology                | 4         | 1.13%   |
| Broadcom Limited                  | 4         | 1.13%   |
| VIA Technologies                  | 3         | 0.85%   |
| Samsung Electronics               | 3         | 0.85%   |
| Trendchip Technologies            | 2         | 0.56%   |
| Sundance Technology Inc / IC Plus | 2         | 0.56%   |
| ZyXEL Communications              | 1         | 0.28%   |
| TP-Link                           | 1         | 0.28%   |
| National Semiconductor            | 1         | 0.28%   |
| Motorola PCS                      | 1         | 0.28%   |
| Motorola BCS                      | 1         | 0.28%   |
| ICS Advent                        | 1         | 0.28%   |
| Davicom Semiconductor             | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 134       | 37.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 45        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18        | 5%      |
| Nvidia MCP61 Ethernet                                                      | 16        | 4.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 11        | 3.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 9         | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 8         | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 6         | 1.67%   |
| Intel Ethernet Connection I217-LM                                          | 6         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 1.11%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.11%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 3         | 0.83%   |
| Intel PRO/100 VE Network Connection                                        | 3         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 0.83%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.56%   |
| Trendchip Ethernet controller                                              | 2         | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.56%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.56%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                        | 2         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                            | 2         | 0.56%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.56%   |
| ZyXEL ADSL Modem Prestige 600 series                                       | 1         | 0.28%   |
| TP-Link M7200                                                              | 1         | 0.28%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.28%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.28%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1         | 0.28%   |
| Realtek PCIe GbE Family Controller                                         | 1         | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1         | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 330       | 55%     |
| WiFi     | 266       | 44.33%  |
| Modem    | 3         | 0.5%    |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 194       | 51.46%  |
| Ethernet | 183       | 48.54%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 206       | 56.44%  |
| 1     | 150       | 41.1%   |
| 3     | 4         | 1.1%    |
| 0     | 3         | 0.82%   |
| 33    | 1         | 0.27%   |
| 4     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 359       | 99.17%  |
| Yes  | 3         | 0.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 32.06%  |
| Realtek Semiconductor           | 18        | 13.74%  |
| Qualcomm Atheros Communications | 16        | 12.21%  |
| IMC Networks                    | 15        | 11.45%  |
| Cambridge Silicon Radio         | 13        | 9.92%   |
| Broadcom                        | 9         | 6.87%   |
| Lite-On Technology              | 5         | 3.82%   |
| Apple                           | 4         | 3.05%   |
| ASUSTek Computer                | 3         | 2.29%   |
| Hewlett-Packard                 | 2         | 1.53%   |
| Marvell Semiconductor           | 1         | 0.76%   |
| Foxconn / Hon Hai               | 1         | 0.76%   |
| Dell                            | 1         | 0.76%   |
| Alps Electric                   | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 16.03%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 13        | 9.92%   |
| Intel AX201 Bluetooth                                       | 10        | 7.63%   |
| Realtek Bluetooth Radio                                     | 9         | 6.87%   |
| Realtek RTL8723B Bluetooth                                  | 6         | 4.58%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 3.82%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 3.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 3.05%   |
| Intel AX200 Bluetooth                                       | 4         | 3.05%   |
| IMC Networks Bluetooth                                      | 4         | 3.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 3.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.29%   |
| IMC Networks Wireless_Device                                | 3         | 2.29%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.53%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.53%   |
| Lite-On Wireless_Device                                     | 2         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.53%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.53%   |
| IMC Networks Bluetooth Module                               | 2         | 1.53%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.76%   |
| Marvell Bluetooth and Wireless LAN Composite                | 1         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.76%   |
| Lite-On Bluetooth Device                                    | 1         | 0.76%   |
| Lite-On BCM20702A0                                          | 1         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.76%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.76%   |
| Broadcom HP Portable Valentine                              | 1         | 0.76%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle         | 1         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.76%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.76%   |
| Broadcom BCM2035B3 Bluetooth Adapter                        | 1         | 0.76%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 285       | 63.33%  |
| AMD                       | 71        | 15.78%  |
| Nvidia                    | 53        | 11.78%  |
| C-Media Electronics       | 8         | 1.78%   |
| VIA Technologies          | 5         | 1.11%   |
| Creative Labs             | 5         | 1.11%   |
| Zhaoxin                   | 3         | 0.67%   |
| Logitech                  | 3         | 0.67%   |
| JMTek                     | 3         | 0.67%   |
| Generalplus Technology    | 3         | 0.67%   |
| Sennheiser Communications | 2         | 0.44%   |
| Microsoft                 | 2         | 0.44%   |
| Unknown                   | 1         | 0.22%   |
| Realtek Semiconductor     | 1         | 0.22%   |
| Megawin Technology        | 1         | 0.22%   |
| Giga-Byte Technology      | 1         | 0.22%   |
| Cirrus Logic              | 1         | 0.22%   |
| Aureal Semiconductor      | 1         | 0.22%   |
| ASUSTek Computer          | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 58        | 11.39%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 57        | 11.2%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 6.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 18        | 3.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 3.54%   |
| Nvidia MCP61 High Definition Audio                                                                | 14        | 2.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 2.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.96%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.77%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 8         | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 7         | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.79%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 0.59%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 3         | 0.59%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.59%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.59%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.59%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.59%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.59%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 66        | 22%     |
| Samsung Electronics        | 45        | 15%     |
| SK hynix                   | 40        | 13.33%  |
| Ramaxel Technology         | 30        | 10%     |
| Kingston                   | 27        | 9%      |
| Micron Technology          | 18        | 6%      |
| Crucial                    | 16        | 5.33%   |
| Corsair                    | 10        | 3.33%   |
| Elpida                     | 7         | 2.33%   |
| Team                       | 4         | 1.33%   |
| Unknown                    | 4         | 1.33%   |
| Qimonda                    | 3         | 1%      |
| Nanya Technology           | 3         | 1%      |
| A-DATA Technology          | 3         | 1%      |
| Unknown (ABCD)             | 2         | 0.67%   |
| Unknown (0x07D5)           | 2         | 0.67%   |
| Shenzhen WODPOSIT          | 2         | 0.67%   |
| PNY                        | 2         | 0.67%   |
| Memox                      | 2         | 0.67%   |
| Avant                      | 2         | 0.67%   |
| Unknown (FFFF000000000000) | 1         | 0.33%   |
| Unknown (7F7F7F7F7F7F7F83) | 1         | 0.33%   |
| Unknown (0x0CBA)           | 1         | 0.33%   |
| Unknown (081A)             | 1         | 0.33%   |
| Unknown (07F7)             | 1         | 0.33%   |
| Super Talent               | 1         | 0.33%   |
| OCZ                        | 1         | 0.33%   |
| Kreton                     | 1         | 0.33%   |
| Hikvision                  | 1         | 0.33%   |
| Gold Key                   | 1         | 0.33%   |
| Apacer                     | 1         | 0.33%   |
| <Invalid>                  | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 6         | 1.82%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s  | 5         | 1.52%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s  | 5         | 1.52%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 4         | 1.21%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 4         | 1.21%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 4         | 1.21%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s  | 4         | 1.21%   |
| Unknown                                                  | 4         | 1.21%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 3         | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 3         | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 3         | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 0.91%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s   | 3         | 0.91%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s      | 3         | 0.91%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s  | 3         | 0.91%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s    | 3         | 0.91%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s  | 3         | 0.91%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s  | 3         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 2         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s              | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s               | 2         | 0.61%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 2         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s              | 2         | 0.61%   |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s     | 2         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s     | 2         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 2         | 0.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s   | 2         | 0.61%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 2         | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 2         | 0.61%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s    | 2         | 0.61%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 0.61%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 2         | 0.61%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s | 2         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 93        | 39.74%  |
| DDR4    | 51        | 21.79%  |
| DDR2    | 39        | 16.67%  |
| SDRAM   | 25        | 10.68%  |
| Unknown | 15        | 6.41%   |
| DDR     | 6         | 2.56%   |
| LPDDR4  | 3         | 1.28%   |
| LPDDR3  | 1         | 0.43%   |
| DDR5    | 1         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 112       | 49.34%  |
| SODIMM       | 110       | 48.46%  |
| Row Of Chips | 5         | 2.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 88        | 33.08%  |
| 4096  | 81        | 30.45%  |
| 8192  | 57        | 21.43%  |
| 1024  | 23        | 8.65%   |
| 16384 | 12        | 4.51%   |
| 32768 | 3         | 1.13%   |
| 512   | 2         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 22.31%  |
| 1333    | 36        | 13.85%  |
| Unknown | 25        | 9.62%   |
| 3200    | 22        | 8.46%   |
| 2667    | 16        | 6.15%   |
| 667     | 16        | 6.15%   |
| 800     | 11        | 4.23%   |
| 2400    | 9         | 3.46%   |
| 1066    | 7         | 2.69%   |
| 533     | 7         | 2.69%   |
| 400     | 6         | 2.31%   |
| 2048    | 5         | 1.92%   |
| 1334    | 5         | 1.92%   |
| 2133    | 4         | 1.54%   |
| 1867    | 4         | 1.54%   |
| 2666    | 3         | 1.15%   |
| 1639    | 3         | 1.15%   |
| 1067    | 3         | 1.15%   |
| 133     | 3         | 1.15%   |
| 4199    | 2         | 0.77%   |
| 3733    | 2         | 0.77%   |
| 3600    | 2         | 0.77%   |
| 3266    | 2         | 0.77%   |
| 1800    | 2         | 0.77%   |
| 975     | 2         | 0.77%   |
| 4800    | 1         | 0.38%   |
| 3800    | 1         | 0.38%   |
| 2000    | 1         | 0.38%   |
| 1024    | 1         | 0.38%   |
| 266     | 1         | 0.38%   |

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
| Chicony Electronics                    | 33        | 20%     |
| Microdia                               | 16        | 9.7%    |
| Realtek Semiconductor                  | 12        | 7.27%   |
| IMC Networks                           | 12        | 7.27%   |
| Bison Electronics                      | 12        | 7.27%   |
| Suyin                                  | 9         | 5.45%   |
| Quanta                                 | 6         | 3.64%   |
| Sunplus Innovation Technology          | 5         | 3.03%   |
| Logitech                               | 5         | 3.03%   |
| Apple                                  | 5         | 3.03%   |
| Syntek                                 | 4         | 2.42%   |
| Sonix Technology                       | 4         | 2.42%   |
| Microsoft                              | 4         | 2.42%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.42%   |
| Samsung Electronics                    | 3         | 1.82%   |
| Ricoh                                  | 3         | 1.82%   |
| Luxvisions Innotech Limited            | 3         | 1.82%   |
| Lite-On Technology                     | 3         | 1.82%   |
| ALi                                    | 3         | 1.82%   |
| Acer                                   | 3         | 1.82%   |
| KYE Systems (Mouse Systems)            | 2         | 1.21%   |
| Importek                               | 2         | 1.21%   |
| Cubeternet                             | 2         | 1.21%   |
| Alcor Micro                            | 2         | 1.21%   |
| Tobii Technology AB                    | 1         | 0.61%   |
| Silicon Motion                         | 1         | 0.61%   |
| SiGma Micro                            | 1         | 0.61%   |
| OmniVision Technologies                | 1         | 0.61%   |
| LG Electronics                         | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| icSpring                               | 1         | 0.61%   |
| Aveo Technology                        | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 12        | 7.27%   |
| Microdia USB 2.0 Camera                                       | 6         | 3.64%   |
| Bison HD Webcam                                               | 5         | 3.03%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 2.42%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 2.42%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.42%   |
| Chicony Integrated Camera                                     | 4         | 2.42%   |
| Sunplus Integrated_Webcam_HD                                  | 3         | 1.82%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 3         | 1.82%   |
| Logitech Webcam C270                                          | 3         | 1.82%   |
| IMC Networks XHC Camera                                       | 3         | 1.82%   |
| Chicony HD Webcam                                             | 3         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 1.82%   |
| Apple Built-in iSight                                         | 3         | 1.82%   |
| Suyin Webcam-101                                              | 2         | 1.21%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.21%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.21%   |
| Realtek Integrated Webcam HD                                  | 2         | 1.21%   |
| Quanta ACER HD User Facing                                    | 2         | 1.21%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.21%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.21%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.21%   |
| IMC Networks Integrated Camera                                | 2         | 1.21%   |
| Cubeternet USB2.0 Camera                                      | 2         | 1.21%   |
| Chicony HP Wide Vision HD Camera                              | 2         | 1.21%   |
| Bison BisonCam, NB Pro                                        | 2         | 1.21%   |
| ALi WebCam                                                    | 2         | 1.21%   |
| Tobii AB EyeChip                                              | 1         | 0.61%   |
| Syntek USB Camera Device                                      | 1         | 0.61%   |
| Syntek Integrated Webcam                                      | 1         | 0.61%   |
| Syntek Integrated Camera                                      | 1         | 0.61%   |
| Syntek EasyCamera                                             | 1         | 0.61%   |
| Suyin USB 2.0 Camera                                          | 1         | 0.61%   |
| Suyin Integrated Webcam                                       | 1         | 0.61%   |
| Suyin HP Webcam                                               | 1         | 0.61%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 0.61%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.61%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.61%   |
| Sunplus Camera                                                | 1         | 0.61%   |
| Silicon Motion WebCam SC-10HDD13335N                          | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 43.75%  |
| AuthenTec                  | 3         | 18.75%  |
| Synaptics                  | 2         | 12.5%   |
| Upek                       | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Futronic Technology        | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 18.75%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 12.5%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics UWP WBDI                                     | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 6.25%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                       | 1         | 6.25%   |
| AuthenTec AES1600                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 281       | 77.41%  |
| 1     | 68        | 18.73%  |
| 2     | 12        | 3.31%   |
| 4     | 2         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 37        | 37.37%  |
| Fingerprint reader       | 16        | 16.16%  |
| Communication controller | 11        | 11.11%  |
| Sound                    | 8         | 8.08%   |
| Net/wireless             | 8         | 8.08%   |
| Chipcard                 | 6         | 6.06%   |
| Camera                   | 5         | 5.05%   |
| Multimedia controller    | 3         | 3.03%   |
| Network                  | 2         | 2.02%   |
| Storage/ide              | 1         | 1.01%   |
| Storage                  | 1         | 1.01%   |
| Bluetooth                | 1         | 1.01%   |


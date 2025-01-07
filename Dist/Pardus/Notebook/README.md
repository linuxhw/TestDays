Pardus - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

Total: 96

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire VN7-791G             | [89b69495ff](https://linux-hardware.org/?probe=89b69495ff) | Dec 26, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [683eb64afb](https://linux-hardware.org/?probe=683eb64afb) | Dec 23, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [d050dbd2b8](https://linux-hardware.org/?probe=d050dbd2b8) | Dec 10, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [d0b421c346](https://linux-hardware.org/?probe=d0b421c346) | Dec 08, 2024 |
| Timi          | TM1604                      | [d62ad5b401](https://linux-hardware.org/?probe=d62ad5b401) | Nov 12, 2024 |
| Acer          | Aspire E5-573G              | [33184ea465](https://linux-hardware.org/?probe=33184ea465) | Sep 15, 2024 |
| HP            | Victus by Gaming Laptop ... | [4ead1d0723](https://linux-hardware.org/?probe=4ead1d0723) | Sep 14, 2024 |
| HP            | Victus by Gaming Laptop ... | [7ddf239141](https://linux-hardware.org/?probe=7ddf239141) | Sep 14, 2024 |
| Lenovo        | 21DL                        | [379438cc01](https://linux-hardware.org/?probe=379438cc01) | Sep 11, 2024 |
| Acer          | Aspire 6930G                | [5e21634173](https://linux-hardware.org/?probe=5e21634173) | Aug 13, 2024 |
| HUAWEI        | BOM-WXX9                    | [5fe062c7bf](https://linux-hardware.org/?probe=5fe062c7bf) | Aug 10, 2024 |
| HUAWEI        | BOM-WXX9                    | [526fba2875](https://linux-hardware.org/?probe=526fba2875) | Aug 10, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [690eababb1](https://linux-hardware.org/?probe=690eababb1) | Aug 08, 2024 |
| Lenovo        | Y50-70 20378                | [d6967574c9](https://linux-hardware.org/?probe=d6967574c9) | Jul 13, 2024 |
| Toshiba       | Satellite C660              | [823341d12b](https://linux-hardware.org/?probe=823341d12b) | Jun 01, 2024 |
| Toshiba       | Satellite L755              | [5734dd0c41](https://linux-hardware.org/?probe=5734dd0c41) | May 27, 2024 |
| HP            | Victus by Gaming Laptop ... | [f584b00194](https://linux-hardware.org/?probe=f584b00194) | May 02, 2024 |
| HP            | Victus by Gaming Laptop ... | [6dbbe3a7b2](https://linux-hardware.org/?probe=6dbbe3a7b2) | May 02, 2024 |
| Pegatron      | A15                         | [259d4c4051](https://linux-hardware.org/?probe=259d4c4051) | Apr 30, 2024 |
| Pegatron      | A15                         | [555c8aa911](https://linux-hardware.org/?probe=555c8aa911) | Apr 30, 2024 |
| Lenovo        | G510 20238                  | [ef88845d13](https://linux-hardware.org/?probe=ef88845d13) | Apr 20, 2024 |
| HP            | ProBook 4540s               | [ace6254b85](https://linux-hardware.org/?probe=ace6254b85) | Apr 14, 2024 |
| HP            | ProBook 4540s               | [1d64c374de](https://linux-hardware.org/?probe=1d64c374de) | Apr 14, 2024 |
| Lenovo        | G510 20238                  | [3c1f7c3f35](https://linux-hardware.org/?probe=3c1f7c3f35) | Apr 04, 2024 |
| Lenovo        | G510 20238                  | [94e26adce2](https://linux-hardware.org/?probe=94e26adce2) | Apr 01, 2024 |
| Lenovo        | G510 20238                  | [c780c8e75c](https://linux-hardware.org/?probe=c780c8e75c) | Mar 30, 2024 |
| HP            | Pavilion g6                 | [0590dc2c6d](https://linux-hardware.org/?probe=0590dc2c6d) | Mar 02, 2024 |
| Dell          | Inspiron 14 5401            | [58f0a8c87c](https://linux-hardware.org/?probe=58f0a8c87c) | Feb 25, 2024 |
| Lenovo        | G510 20238                  | [586fb5dfba](https://linux-hardware.org/?probe=586fb5dfba) | Feb 18, 2024 |
| Lenovo        | G510 20238                  | [9098ece7f8](https://linux-hardware.org/?probe=9098ece7f8) | Feb 08, 2024 |
| Acer          | Aspire 5742G                | [1fdb1cdc5f](https://linux-hardware.org/?probe=1fdb1cdc5f) | Feb 06, 2024 |
| HP            | Pavilion Notebook           | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| Lenovo        | G510 20238                  | [d93b9b007a](https://linux-hardware.org/?probe=d93b9b007a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| Lenovo        | G510 20238                  | [da159bff10](https://linux-hardware.org/?probe=da159bff10) | Jan 31, 2024 |
| Lenovo        | G510 20238                  | [192a3a0ab1](https://linux-hardware.org/?probe=192a3a0ab1) | Jan 30, 2024 |
| Lenovo        | G510 20238                  | [bb879ce9b9](https://linux-hardware.org/?probe=bb879ce9b9) | Jan 27, 2024 |
| HP            | EliteBook 830 G5            | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| HP            | EliteBook 820 G2            | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Casper        | EXCALIBUR G770              | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| Toshiba       | Satellite L755              | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| ASUSTek       | X550DP                      | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Toshiba       | Satellite L755              | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| Toshiba       | Satellite L755              | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Dell          | Vostro 5502                 | [5d42ac567c](https://linux-hardware.org/?probe=5d42ac567c) | Jun 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [7ffc12366e](https://linux-hardware.org/?probe=7ffc12366e) | May 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| Lenovo        | G510 20238                  | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | G50-45 80E3                 | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| TUXEDO        | Unknown                     | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Sony          | SVE14A2V2ES                 | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Acer          | Aspire 5742G                | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| Sony          | SVE14A2V2ES                 | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| Toshiba       | Satellite C855-1VM          | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| ASUSTek       | X555YI                      | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | E402BP                      | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pardus 23.1   | 9         | 13.64%  |
| Pardus 23.2   | 8         | 12.12%  |
| Pardus 21.4   | 7         | 10.61%  |
| Pardus 21.5   | 6         | 9.09%   |
| Pardus 21.3   | 5         | 7.58%   |
| Pardus 21.1   | 5         | 7.58%   |
| Pardus 21.2   | 4         | 6.06%   |
| Pardus 21.0   | 3         | 4.55%   |
| Pardus 19.5   | 3         | 4.55%   |
| Pardus 19.3   | 3         | 4.55%   |
| Pardus 23.3   | 2         | 3.03%   |
| Pardus 23.0   | 2         | 3.03%   |
| Pardus 19.4-1 | 2         | 3.03%   |
| Pardus 19.2   | 2         | 3.03%   |
| Pardus 19.1   | 2         | 3.03%   |
| Pardus 19.0   | 2         | 3.03%   |
| Pardus 19.4   | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 59        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-17-amd64            | 6         | 8.96%   |
| 5.10.0-21-amd64           | 5         | 7.46%   |
| 5.10.0-19-amd64           | 4         | 5.97%   |
| 6.1.0-23-amd64            | 3         | 4.48%   |
| 5.10.0-13-amd64           | 3         | 4.48%   |
| 5.10.0-11-amd64           | 3         | 4.48%   |
| 4.19.0-6-amd64            | 3         | 4.48%   |
| 4.19.0-10-amd64           | 3         | 4.48%   |
| 6.1.0-26-amd64            | 2         | 2.99%   |
| 5.10.0-9-amd64            | 2         | 2.99%   |
| 5.10.0-23-amd64           | 2         | 2.99%   |
| 5.10.0-20-amd64           | 2         | 2.99%   |
| 5.10.0-10-amd64           | 2         | 2.99%   |
| 4.19.0-13-amd64           | 2         | 2.99%   |
| 6.7.12+bpo-amd64          | 1         | 1.49%   |
| 6.6.13+bpo-amd64          | 1         | 1.49%   |
| 6.10.6+bpo-amd64          | 1         | 1.49%   |
| 6.10.11+bpo-amd64         | 1         | 1.49%   |
| 6.1.0-28-amd64            | 1         | 1.49%   |
| 6.1.0-25-amd64            | 1         | 1.49%   |
| 6.1.0-22-amd64            | 1         | 1.49%   |
| 6.1.0-20-amd64            | 1         | 1.49%   |
| 6.1.0-13-amd64            | 1         | 1.49%   |
| 6.1.0-11-amd64            | 1         | 1.49%   |
| 6.1.0-0.deb11.13-amd64    | 1         | 1.49%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.49%   |
| 5.9.0-0.bpo.2-amd64       | 1         | 1.49%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 1.49%   |
| 5.10.0-8-amd64            | 1         | 1.49%   |
| 5.10.0-33-amd64           | 1         | 1.49%   |
| 5.10.0-25-amd64           | 1         | 1.49%   |
| 5.10.0-17-amd64           | 1         | 1.49%   |
| 5.10.0-16-amd64           | 1         | 1.49%   |
| 5.10.0-14-amd64           | 1         | 1.49%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 1.49%   |
| 4.19.0-8-amd64            | 1         | 1.49%   |
| 4.19.0-5-amd64            | 1         | 1.49%   |
| 4.19.0-19-amd64           | 1         | 1.49%   |
| 4.19.0-16-amd64           | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 28        | 43.75%  |
| 6.1.0   | 18        | 28.13%  |
| 4.19.0  | 11        | 17.19%  |
| 6.7.12  | 1         | 1.56%   |
| 6.6.13  | 1         | 1.56%   |
| 6.10.6  | 1         | 1.56%   |
| 6.10.11 | 1         | 1.56%   |
| 6.0.11  | 1         | 1.56%   |
| 5.9.0   | 1         | 1.56%   |
| 5.4.0   | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 28        | 43.75%  |
| 6.1     | 18        | 28.13%  |
| 4.19    | 11        | 17.19%  |
| 6.10    | 2         | 3.13%   |
| 6.7     | 1         | 1.56%   |
| 6.6     | 1         | 1.56%   |
| 6.0     | 1         | 1.56%   |
| 5.9     | 1         | 1.56%   |
| 5.4     | 1         | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 31        | 51.67%  |
| GNOME   | 25        | 41.67%  |
| KDE5    | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 59        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 57.38%  |
| LightDM | 10        | 16.39%  |
| TDM     | 6         | 9.84%   |
| GDM3    | 6         | 9.84%   |
| GDM     | 4         | 6.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 45        | 76.27%  |
| en_US   | 5         | 8.47%   |
| Unknown | 3         | 5.08%   |
| pt_BR   | 1         | 1.69%   |
| it_IT   | 1         | 1.69%   |
| hu_HU   | 1         | 1.69%   |
| fur_IT  | 1         | 1.69%   |
| en_GB   | 1         | 1.69%   |
| de_AT   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 69.35%  |
| EFI  | 19        | 30.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 57        | 96.61%  |
| Overlay | 2         | 3.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 59.02%  |
| GPT     | 19        | 31.15%  |
| MBR     | 6         | 9.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 91.53%  |
| Yes       | 5         | 8.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 81.36%  |
| Yes       | 11        | 18.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 25.42%  |
| Hewlett-Packard     | 13        | 22.03%  |
| Acer                | 5         | 8.47%   |
| Toshiba             | 4         | 6.78%   |
| Dell                | 4         | 6.78%   |
| ASUSTek Computer    | 3         | 5.08%   |
| Sony                | 2         | 3.39%   |
| Samsung Electronics | 2         | 3.39%   |
| Packard Bell        | 2         | 3.39%   |
| HUAWEI              | 2         | 3.39%   |
| TUXEDO              | 1         | 1.69%   |
| Timi                | 1         | 1.69%   |
| Philco              | 1         | 1.69%   |
| Pegatron            | 1         | 1.69%   |
| Olidata             | 1         | 1.69%   |
| Clevo               | 1         | 1.69%   |
| Casper              | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP ProBook 4540s                           | 2         | 3.39%   |
| Toshiba Satellite L755                     | 1         | 1.69%   |
| Toshiba Satellite C855-1VM                 | 1         | 1.69%   |
| Toshiba Satellite C660                     | 1         | 1.69%   |
| Toshiba PORTEGE M780                       | 1         | 1.69%   |
| Timi TM1604                                | 1         | 1.69%   |
| Sony SVF1521QSTB                           | 1         | 1.69%   |
| Sony SVE14A2V2ES                           | 1         | 1.69%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 1.69%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 1.69%   |
| Philco 14F                                 | 1         | 1.69%   |
| Pegatron A15                               | 1         | 1.69%   |
| Packard Bell EasyNote_GN45                 | 1         | 1.69%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 1.69%   |
| Olidata T7700                              | 1         | 1.69%   |
| Lenovo Y50-70 20378                        | 1         | 1.69%   |
| Lenovo V145-15AST 81MT                     | 1         | 1.69%   |
| Lenovo V110-15ISK 80TL                     | 1         | 1.69%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 1.69%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 1.69%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 1.69%   |
| Lenovo ThinkPad P15v Gen 1 20TRS1UB00      | 1         | 1.69%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 1.69%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 1.69%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 1.69%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 1.69%   |
| Lenovo IdeaPad 1 15IGL7 82V7               | 1         | 1.69%   |
| Lenovo G510 20238                          | 1         | 1.69%   |
| Lenovo G50-45 80E3                         | 1         | 1.69%   |
| Lenovo 21DL                                | 1         | 1.69%   |
| HUAWEI KLVL-WXXW                           | 1         | 1.69%   |
| HUAWEI BOM-WXX9                            | 1         | 1.69%   |
| HP Victus by Gaming Laptop 16-s0xxx        | 1         | 1.69%   |
| HP Pavilion Notebook                       | 1         | 1.69%   |
| HP Pavilion g6                             | 1         | 1.69%   |
| HP Pavilion 15                             | 1         | 1.69%   |
| HP Laptop 15-dw3xxx                        | 1         | 1.69%   |
| HP EliteBook 850 G8 Notebook PC            | 1         | 1.69%   |
| HP EliteBook 830 G5                        | 1         | 1.69%   |
| HP EliteBook 820 G2                        | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 5         | 8.47%   |
| Acer Aspire              | 5         | 8.47%   |
| Toshiba Satellite        | 3         | 5.08%   |
| Lenovo IdeaPad           | 3         | 5.08%   |
| HP Pavilion              | 3         | 5.08%   |
| HP EliteBook             | 3         | 5.08%   |
| Packard Bell EasyNote    | 2         | 3.39%   |
| HP ProBook               | 2         | 3.39%   |
| Toshiba PORTEGE          | 1         | 1.69%   |
| Timi TM1604              | 1         | 1.69%   |
| Sony SVF1521QSTB         | 1         | 1.69%   |
| Sony SVE14A2V2ES         | 1         | 1.69%   |
| Samsung 300E4C           | 1         | 1.69%   |
| Samsung 300E4A           | 1         | 1.69%   |
| Philco 14F               | 1         | 1.69%   |
| Pegatron A15             | 1         | 1.69%   |
| Olidata T7700            | 1         | 1.69%   |
| Lenovo Y50-70            | 1         | 1.69%   |
| Lenovo V145-15AST        | 1         | 1.69%   |
| Lenovo V110-15ISK        | 1         | 1.69%   |
| Lenovo IdeaPad-510-15IKB | 1         | 1.69%   |
| Lenovo G510              | 1         | 1.69%   |
| Lenovo G50-45            | 1         | 1.69%   |
| Lenovo 21DL              | 1         | 1.69%   |
| HUAWEI KLVL-WXXW         | 1         | 1.69%   |
| HUAWEI BOM-WXX9          | 1         | 1.69%   |
| HP Victus                | 1         | 1.69%   |
| HP Laptop                | 1         | 1.69%   |
| HP 530                   | 1         | 1.69%   |
| HP 250                   | 1         | 1.69%   |
| HP 15                    | 1         | 1.69%   |
| Dell Vostro              | 1         | 1.69%   |
| Dell Latitude            | 1         | 1.69%   |
| Dell Inspiron            | 1         | 1.69%   |
| Dell G5                  | 1         | 1.69%   |
| Clevo W251EFQ            | 1         | 1.69%   |
| Casper EXCALIBUR         | 1         | 1.69%   |
| ASUS X555YI              | 1         | 1.69%   |
| ASUS X550DP              | 1         | 1.69%   |
| ASUS E402BP              | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 13.56%  |
| 2015 | 6         | 10.17%  |
| 2020 | 5         | 8.47%   |
| 2018 | 5         | 8.47%   |
| 2014 | 5         | 8.47%   |
| 2011 | 5         | 8.47%   |
| 2019 | 4         | 6.78%   |
| 2012 | 4         | 6.78%   |
| 2021 | 3         | 5.08%   |
| 2017 | 3         | 5.08%   |
| 2010 | 3         | 5.08%   |
| 2008 | 2         | 3.39%   |
| 2024 | 1         | 1.69%   |
| 2023 | 1         | 1.69%   |
| 2022 | 1         | 1.69%   |
| 2016 | 1         | 1.69%   |
| 2007 | 1         | 1.69%   |
| 2006 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 59        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 30%     |
| 3.01-4.0   | 17        | 28.33%  |
| 8.01-16.0  | 12        | 20%     |
| 16.01-24.0 | 8         | 13.33%  |
| 32.01-64.0 | 2         | 3.33%   |
| 1.01-2.0   | 2         | 3.33%   |
| 2.01-3.0   | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 22        | 33.85%  |
| 2.01-3.0  | 21        | 32.31%  |
| 3.01-4.0  | 12        | 18.46%  |
| 4.01-8.0  | 7         | 10.77%  |
| 8.01-16.0 | 2         | 3.08%   |
| 0.51-1.0  | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 62.71%  |
| 2      | 19        | 32.2%   |
| 3      | 3         | 5.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 58.33%  |
| Yes       | 25        | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 88.14%  |
| No        | 7         | 11.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 98.31%  |
| No        | 1         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 83.33%  |
| No        | 10        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Turkey     | 49        | 81.67%  |
| Germany    | 2         | 3.33%   |
| UK         | 1         | 1.67%   |
| Sweden     | 1         | 1.67%   |
| Poland     | 1         | 1.67%   |
| Libya      | 1         | 1.67%   |
| Italy      | 1         | 1.67%   |
| Bulgaria   | 1         | 1.67%   |
| Brazil     | 1         | 1.67%   |
| Azerbaijan | 1         | 1.67%   |
| Austria    | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Istanbul             | 21        | 33.33%  |
| Ankara               | 8         | 12.7%   |
| Izmir                | 6         | 9.52%   |
| Çanakkale           | 2         | 3.17%   |
| Bursa                | 2         | 3.17%   |
| Vienna               | 1         | 1.59%   |
| Tripoli              | 1         | 1.59%   |
| Sofia                | 1         | 1.59%   |
| Serik                | 1         | 1.59%   |
| Sao Gabriel          | 1         | 1.59%   |
| Samsun               | 1         | 1.59%   |
| Malatya              | 1         | 1.59%   |
| London               | 1         | 1.59%   |
| Landskrona           | 1         | 1.59%   |
| Kołobrzeg           | 1         | 1.59%   |
| Konya                | 1         | 1.59%   |
| Kirchheim unter Teck | 1         | 1.59%   |
| Hacilar              | 1         | 1.59%   |
| Gaziantep            | 1         | 1.59%   |
| Esenyurt             | 1         | 1.59%   |
| Erzurum              | 1         | 1.59%   |
| Castrop-Rauxel       | 1         | 1.59%   |
| Bolzano              | 1         | 1.59%   |
| Balıkesir           | 1         | 1.59%   |
| Baku                 | 1         | 1.59%   |
| Aydin                | 1         | 1.59%   |
| Artvin               | 1         | 1.59%   |
| Antalya              | 1         | 1.59%   |
| Aksaray              | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 17     | 16.67%  |
| WDC                         | 11        | 13     | 14.1%   |
| Seagate                     | 9         | 13     | 11.54%  |
| SanDisk                     | 7         | 7      | 8.97%   |
| SK hynix                    | 4         | 5      | 5.13%   |
| Toshiba                     | 3         | 5      | 3.85%   |
| Kingston                    | 3         | 4      | 3.85%   |
| Hitachi                     | 3         | 3      | 3.85%   |
| Unknown                     | 2         | 2      | 2.56%   |
| SPCC                        | 2         | 2      | 2.56%   |
| Silicon Motion              | 2         | 2      | 2.56%   |
| Lexar                       | 2         | 2      | 2.56%   |
| Kingston Technology Company | 2         | 2      | 2.56%   |
| HGST                        | 2         | 2      | 2.56%   |
| USB3.0                      | 1         | 1      | 1.28%   |
| Phison                      | 1         | 1      | 1.28%   |
| Micron/Crucial Technology   | 1         | 1      | 1.28%   |
| Micron Technology           | 1         | 2      | 1.28%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 1.28%   |
| LITEON                      | 1         | 1      | 1.28%   |
| KIOXIA-EXCERIA              | 1         | 1      | 1.28%   |
| KingSpec                    | 1         | 1      | 1.28%   |
| Intenso                     | 1         | 2      | 1.28%   |
| Initio                      | 1         | 1      | 1.28%   |
| China                       | 1         | 1      | 1.28%   |
| addlink                     | 1         | 1      | 1.28%   |
| Unknown                     | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| SPCC Solid State Disk 512GB                 | 2         | 2.47%   |
| Seagate ST1000LM035-1RK172 1TB              | 2         | 2.47%   |
| SanDisk SSD PLUS 240GB                      | 2         | 2.47%   |
| Kingston SA400S37240G 240GB SSD             | 2         | 2.47%   |
| HGST HTS545050A7E680 500GB                  | 2         | 2.47%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD            | 1         | 1.23%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 1.23%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 1.23%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 1.23%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 1.23%   |
| WDC WD3200BEVT-22ZCT0 320GB                 | 1         | 1.23%   |
| WDC WD2500BEVS-00UST0 250GB                 | 1         | 1.23%   |
| WDC WD10SPCX-24HWST1 1TB                    | 1         | 1.23%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1.23%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1.23%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 1.23%   |
| USB3.0 Super Speed 500GB SSD                | 1         | 1.23%   |
| Unknown SD32G  32GB                         | 1         | 1.23%   |
| Unknown MMC Card  128GB                     | 1         | 1.23%   |
| Toshiba MQ01ABD075 752GB                    | 1         | 1.23%   |
| Toshiba MK6475GSX 640GB                     | 1         | 1.23%   |
| Toshiba MK5061GSYN 500GB                    | 1         | 1.23%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB      | 1         | 1.23%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 1.23%   |
| SK hynix BC711 HFM512GD3JX013N 512GB        | 1         | 1.23%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 1.23%   |
| Silicon Motion PCIe-8 SSD 512GB             | 1         | 1.23%   |
| Silicon Motion Longline SSD 512GB           | 1         | 1.23%   |
| Seagate ST9500325AS 500GB                   | 1         | 1.23%   |
| Seagate ST9120822AS 120GB                   | 1         | 1.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB         | 1         | 1.23%   |
| Seagate ST500LM000-1EJ162 500GB             | 1         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1.23%   |
| Seagate Expansion 1TB                       | 1         | 1.23%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 1.23%   |
| SanDisk SSD U110 16GB                       | 1         | 1.23%   |
| SanDisk SSD PLUS 480GB                      | 1         | 1.23%   |
| SanDisk SSD PLUS 120GB                      | 1         | 1.23%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 1.23%   |
| SanDisk SDSSDA240G 240GB                    | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 35.71%  |
| Seagate             | 8         | 12     | 28.57%  |
| Toshiba             | 3         | 5      | 10.71%  |
| Hitachi             | 3         | 3      | 10.71%  |
| HGST                | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Initio              | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 23.33%  |
| Samsung Electronics | 6         | 8      | 20%     |
| Kingston            | 3         | 4      | 10%     |
| SPCC                | 2         | 2      | 6.67%   |
| Lexar               | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| USB3.0              | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Seagate             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 2      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.33%   |
| KingSpec            | 1         | 1      | 3.33%   |
| Intenso             | 1         | 2      | 3.33%   |
| China               | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 28        | 36     | 39.44%  |
| SSD     | 25        | 35     | 35.21%  |
| NVMe    | 14        | 20     | 19.72%  |
| MMC     | 2         | 2      | 2.82%   |
| Unknown | 2         | 2      | 2.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 70     | 71.43%  |
| NVMe | 14        | 20     | 22.22%  |
| SAS  | 2         | 3      | 3.17%   |
| MMC  | 2         | 2      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 52     | 72%     |
| 0.51-1.0   | 14        | 19     | 28%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 27        | 43.55%  |
| 251-500    | 20        | 32.26%  |
| 501-1000   | 9         | 14.52%  |
| 21-50      | 3         | 4.84%   |
| 51-100     | 3         | 4.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 25        | 39.06%  |
| 21-50   | 15        | 23.44%  |
| 51-100  | 14        | 21.88%  |
| 101-250 | 8         | 12.5%   |
| 251-500 | 2         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB   | 1         | 1      | 25%     |
| WDC WD10JPVX-22JC3T0 1TB       | 1         | 1      | 25%     |
| Seagate ST9120822AS 120GB      | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 2         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 2         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 38        | 60     | 58.46%  |
| Works    | 22        | 30     | 33.85%  |
| Malfunc  | 4         | 4      | 6.15%   |
| Failed   | 1         | 1      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 63.08%  |
| AMD                         | 8         | 12.31%  |
| Samsung Electronics         | 6         | 9.23%   |
| SK hynix                    | 3         | 4.62%   |
| Silicon Motion              | 2         | 3.08%   |
| Kingston Technology Company | 2         | 3.08%   |
| Phison Electronics          | 1         | 1.54%   |
| Micron/Crucial Technology   | 1         | 1.54%   |
| MAXIO Technology (Hangzhou) | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 11.43%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 10%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 5.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 3         | 4.29%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.86%   |
| SK hynix BC511 NVMe SSD                                                                | 1         | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 1         | 1.43%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.43%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                    | 1         | 1.43%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                   | 1         | 1.43%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                               | 1         | 1.43%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.43%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                   | 1         | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 69.23%  |
| NVMe | 14        | 21.54%  |
| IDE  | 4         | 6.15%   |
| RAID | 2         | 3.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 79.66%  |
| AMD    | 12        | 20.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 5.08%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 3.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 3.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 3.39%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 3.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.39%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 1         | 1.69%   |
| Intel Pentium CPU B950 @ 2.10GHz        | 1         | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.69%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 1         | 1.69%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.69%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.69%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.69%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.69%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.69%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 1.69%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.69%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 1         | 1.69%   |
| Intel Core i3-2370M CPU @ 2.40GHz       | 1         | 1.69%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 1         | 1.69%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.69%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 1         | 1.69%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz    | 1         | 1.69%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 1.69%   |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 1         | 1.69%   |
| Intel Core 2 CPU T5200 @ 1.60GHz        | 1         | 1.69%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 1         | 1.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 1         | 1.69%   |
| Intel Celeron CPU 1005M @ 1.90GHz       | 1         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.69%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 12        | 20.34%  |
| Intel Core i5    | 11        | 18.64%  |
| Intel Core i3    | 11        | 18.64%  |
| Other            | 6         | 10.17%  |
| Intel Celeron    | 3         | 5.08%   |
| AMD Ryzen 7      | 3         | 5.08%   |
| AMD A10          | 3         | 5.08%   |
| Intel Pentium    | 2         | 3.39%   |
| Intel Core 2 Duo | 2         | 3.39%   |
| Intel Core 2     | 2         | 3.39%   |
| AMD A8           | 2         | 3.39%   |
| AMD Ryzen 5      | 1         | 1.69%   |
| AMD C-50         | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 56.67%  |
| 4      | 20        | 33.33%  |
| 8      | 3         | 5%      |
| 6      | 3         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 76.27%  |
| 1      | 14        | 23.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 57.14%  |
| 0x306a9    | 5         | 7.94%   |
| 0x306d4    | 3         | 4.76%   |
| 0x806c1    | 2         | 3.17%   |
| 0x07030105 | 2         | 3.17%   |
| 0x0600611a | 2         | 3.17%   |
| 0x906ea    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x6f6      | 1         | 1.59%   |
| 0x406e3    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x206a7    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x10676    | 1         | 1.59%   |
| 0x0a704103 | 1         | 1.59%   |
| 0x08608103 | 1         | 1.59%   |
| 0x08608102 | 1         | 1.59%   |
| 0x06006705 | 1         | 1.59%   |
| 0x05000029 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 11.86%  |
| IvyBridge     | 7         | 11.86%  |
| SandyBridge   | 6         | 10.17%  |
| Haswell       | 6         | 10.17%  |
| Broadwell     | 5         | 8.47%   |
| TigerLake     | 4         | 6.78%   |
| Excavator     | 4         | 6.78%   |
| Core          | 3         | 5.08%   |
| Unknown       | 3         | 5.08%   |
| Westmere      | 2         | 3.39%   |
| Puma          | 2         | 3.39%   |
| CometLake     | 2         | 3.39%   |
| Zen 3         | 1         | 1.69%   |
| Skylake       | 1         | 1.69%   |
| Silvermont    | 1         | 1.69%   |
| Piledriver    | 1         | 1.69%   |
| Penryn        | 1         | 1.69%   |
| IceLake       | 1         | 1.69%   |
| Goldmont plus | 1         | 1.69%   |
| Bobcat        | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 55.13%  |
| AMD    | 19        | 24.36%  |
| Nvidia | 16        | 20.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 7         | 7.95%   |
| Intel HD Graphics 5500                                                                | 5         | 5.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 4.55%   |
| Intel UHD Graphics 620                                                                | 3         | 3.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 3.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 3.41%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 3.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 2.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 2.27%   |
| Intel HD Graphics 620                                                                 | 2         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 2         | 2.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 2.27%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 2         | 2.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 2.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 2         | 2.27%   |
| AMD Lucienne                                                                          | 2         | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 1.14%   |
| Nvidia GT218M [GeForce 315M]                                                          | 1         | 1.14%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.14%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 1.14%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 1.14%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.14%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 1.14%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 1.14%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.14%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.14%   |
| Nvidia GF108M [GeForce GT 525M]                                                       | 1         | 1.14%   |
| Nvidia GF108M [GeForce GT 420M]                                                       | 1         | 1.14%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.14%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                       | 1         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.14%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 1         | 1.14%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.14%   |
| Intel HD Graphics 520                                                                 | 1         | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 42.37%  |
| Intel + Nvidia | 11        | 18.64%  |
| 2 x AMD        | 7         | 11.86%  |
| Intel + AMD    | 7         | 11.86%  |
| 1 x Nvidia     | 4         | 6.78%   |
| 1 x AMD        | 4         | 6.78%   |
| AMD + Nvidia   | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 93.33%  |
| Proprietary | 4         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 71.43%  |
| 0.01-0.5   | 9         | 14.29%  |
| 0.51-1.0   | 4         | 6.35%   |
| 1.01-2.0   | 3         | 4.76%   |
| 5.01-6.0   | 1         | 1.59%   |
| 3.01-4.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 22.95%  |
| Chimei Innolux          | 11        | 18.03%  |
| AU Optronics            | 9         | 14.75%  |
| BOE                     | 8         | 13.11%  |
| Samsung Electronics     | 7         | 11.48%  |
| LG Philips              | 2         | 3.28%   |
| Chi Mei Optoelectronics | 2         | 3.28%   |
| Sharp                   | 1         | 1.64%   |
| Philips                 | 1         | 1.64%   |
| PANDA                   | 1         | 1.64%   |
| Lenovo                  | 1         | 1.64%   |
| Hewlett-Packard         | 1         | 1.64%   |
| Goldstar                | 1         | 1.64%   |
| Dell                    | 1         | 1.64%   |
| AOC                     | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch              | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 1         | 1.61%   |
| Philips PHL 288E2 PHLC231 3840x2160 621x341mm 27.9-inch              | 1         | 1.61%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch              | 1         | 1.61%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch          | 1         | 1.61%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch          | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 1         | 1.61%   |
| Hewlett-Packard E24 G4 HPN3689 1920x1080 530x300mm 24.0-inch         | 1         | 1.61%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 1         | 1.61%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN162D 1920x1080 355x199mm 16.0-inch     | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch     | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 28        | 46.67%  |
| 1920x1080 (FHD)   | 24        | 40%     |
| 1280x800 (WXGA)   | 2         | 3.33%   |
| 3840x2160 (4K)    | 1         | 1.67%   |
| 2160x1440         | 1         | 1.67%   |
| 1920x1200 (WUXGA) | 1         | 1.67%   |
| 1600x900 (HD+)    | 1         | 1.67%   |
| 1440x900 (WXGA+)  | 1         | 1.67%   |
| 1280x1024 (SXGA)  | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 42        | 67.74%  |
| 13     | 5         | 8.06%   |
| 14     | 4         | 6.45%   |
| 17     | 3         | 4.84%   |
| 24     | 2         | 3.23%   |
| 12     | 2         | 3.23%   |
| 27     | 1         | 1.61%   |
| 23     | 1         | 1.61%   |
| 22     | 1         | 1.61%   |
| 16     | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 75.41%  |
| 351-400     | 5         | 8.2%    |
| 201-300     | 5         | 8.2%    |
| 501-600     | 3         | 4.92%   |
| 601-700     | 1         | 1.64%   |
| 401-500     | 1         | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 88.33%  |
| 16/10 | 5         | 8.33%   |
| 5/4   | 1         | 1.67%   |
| 3/2   | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 69.35%  |
| 81-90          | 7         | 11.29%  |
| 201-250        | 3         | 4.84%   |
| 71-80          | 2         | 3.23%   |
| 61-70          | 2         | 3.23%   |
| 301-350        | 1         | 1.61%   |
| 251-300        | 1         | 1.61%   |
| 141-150        | 1         | 1.61%   |
| 131-140        | 1         | 1.61%   |
| 121-130        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 24        | 39.34%  |
| 121-160 | 19        | 31.15%  |
| 51-100  | 13        | 21.31%  |
| 161-240 | 5         | 8.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 54        | 91.53%  |
| 2     | 5         | 8.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 42.55%  |
| Intel                 | 25        | 26.6%   |
| Qualcomm Atheros      | 14        | 14.89%  |
| Broadcom              | 6         | 6.38%   |
| Ralink                | 3         | 3.19%   |
| ASUSTek Computer      | 2         | 2.13%   |
| Xiaomi                | 1         | 1.06%   |
| Ralink Technology     | 1         | 1.06%   |
| MediaTek              | 1         | 1.06%   |
| JMicron Technology    | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 22.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 7.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 3.45%   |
| Intel Wireless 8265 / 8275                                             | 4         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 2.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.72%   |
| Intel Wireless 7265                                                    | 2         | 1.72%   |
| Intel Wireless 7260                                                    | 2         | 1.72%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.86%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 1         | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1         | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1         | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.86%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.86%   |
| Intel Wireless 3160                                                    | 1         | 0.86%   |
| Intel WiFi Link 5100                                                   | 1         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 40.32%  |
| Realtek Semiconductor | 14        | 22.58%  |
| Qualcomm Atheros      | 11        | 17.74%  |
| Broadcom              | 5         | 8.06%   |
| Ralink                | 3         | 4.84%   |
| ASUSTek Computer      | 2         | 3.23%   |
| Ralink Technology     | 1         | 1.61%   |
| MediaTek              | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.45%   |
| Intel Wireless 8265 / 8275                                     | 4         | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 4.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 4.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.23%   |
| Intel Wireless 7265                                            | 2         | 3.23%   |
| Intel Wireless 7260                                            | 2         | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.61%   |
| Intel Wireless 3160                                            | 1         | 1.61%   |
| Intel WiFi Link 5100                                           | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.61%   |
| Intel Centrino Wireless-N 130                                  | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.61%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.61%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.61%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 1.61%   |
| ASUS 802.11ac NIC                                              | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 69.81%  |
| Intel                 | 8         | 15.09%  |
| Qualcomm Atheros      | 4         | 7.55%   |
| Broadcom              | 2         | 3.77%   |
| Xiaomi                | 1         | 1.89%   |
| JMicron Technology    | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 48.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 16.67%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 3.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.85%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.85%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 1.85%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.85%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile   | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 52.73%  |
| Ethernet | 52        | 47.27%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 79.69%  |
| Ethernet | 13        | 20.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 84.75%  |
| 1     | 9         | 15.25%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 91.53%  |
| Yes  | 5         | 8.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 36%     |
| Realtek Semiconductor           | 8         | 16%     |
| Qualcomm Atheros Communications | 5         | 10%     |
| Lite-On Technology              | 3         | 6%      |
| Broadcom                        | 3         | 6%      |
| Toshiba                         | 2         | 4%      |
| Realtek                         | 2         | 4%      |
| Ralink                          | 2         | 4%      |
| IMC Networks                    | 2         | 4%      |
| Foxconn / Hon Hai               | 2         | 4%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Foxconn International           | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 18%     |
| Realtek Bluetooth Radio                             | 5         | 10%     |
| Intel AX201 Bluetooth                               | 4         | 8%      |
| Realtek Bluetooth Radio                             | 2         | 4%      |
| Ralink RT3290 Bluetooth                             | 2         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 4%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4%      |
| Broadcom HP Portable Valentine                      | 2         | 4%      |
| Toshiba RT Bluetooth Radio                          | 1         | 2%      |
| Toshiba Integrated Bluetooth HCI                    | 1         | 2%      |
| Realtek RTL8821A Bluetooth                          | 1         | 2%      |
| Realtek RTL8723B Bluetooth                          | 1         | 2%      |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2%      |
| IMC Networks Wireless_Device                        | 1         | 2%      |
| IMC Networks Bluetooth Device                       | 1         | 2%      |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2%      |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 70.15%  |
| AMD                   | 12        | 17.91%  |
| Nvidia                | 7         | 10.45%  |
| Barco Display Systems | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 5.68%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 4.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 4.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 4.55%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 3.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.41%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.27%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.27%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.27%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 2         | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.14%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.14%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.14%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.14%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.14%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 31.03%  |
| SK hynix            | 6         | 20.69%  |
| Unknown             | 4         | 13.79%  |
| Kingston            | 4         | 13.79%  |
| Unknown (0x4509)    | 1         | 3.45%   |
| Ramaxel Technology  | 1         | 3.45%   |
| Micron Technology   | 1         | 3.45%   |
| Kingmax             | 1         | 3.45%   |
| Apacer              | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 3.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 3.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 3.33%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 3.33%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 3.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s             | 1         | 3.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 3.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 3.33%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s             | 1         | 3.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 3.33%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 3.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s           | 1         | 3.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 3.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 3.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s        | 1         | 3.33%   |
| Ramaxel RAM RMSA3330MJ78HBF-3200 16GB SODIMM DDR4 3200MT/s         | 1         | 3.33%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 3.33%   |
| Kingston RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 3.33%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 3.33%   |
| Apacer RAM 76.B302G.C3Z0B 4GB SODIMM DDR3 1600MT/s                 | 1         | 3.33%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 11        | 42.31%  |
| DDR3  | 11        | 42.31%  |
| DDR2  | 2         | 7.69%   |
| SDRAM | 1         | 3.85%   |
| DDR5  | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 88%     |
| Row Of Chips | 2         | 8%      |
| DIMM         | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 42.86%  |
| 4096  | 7         | 25%     |
| 2048  | 5         | 17.86%  |
| 16384 | 4         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 30.77%  |
| 3200    | 6         | 23.08%  |
| 2667    | 4         | 15.38%  |
| 2133    | 2         | 7.69%   |
| 5600    | 1         | 3.85%   |
| 2400    | 1         | 3.85%   |
| 1333    | 1         | 3.85%   |
| 1067    | 1         | 3.85%   |
| 667     | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung CLP-325 Color Laser Printer | 1         | 33.33%  |
| Canon PIXMA MX340                   | 1         | 33.33%  |
| Canon LBP6030/6030B/6018L           | 1         | 33.33%  |

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
| Chicony Electronics                    | 18        | 35.29%  |
| Realtek Semiconductor                  | 6         | 11.76%  |
| IMC Networks                           | 4         | 7.84%   |
| Microdia                               | 3         | 5.88%   |
| Luxvisions Innotech Limited            | 3         | 5.88%   |
| Bison Electronics                      | 3         | 5.88%   |
| Suyin                                  | 2         | 3.92%   |
| Silicon Motion                         | 2         | 3.92%   |
| Quanta                                 | 2         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Syntek                                 | 1         | 1.96%   |
| Lite-On Technology                     | 1         | 1.96%   |
| Foxconn / Hon Hai                      | 1         | 1.96%   |
| ALi                                    | 1         | 1.96%   |
| Alcor Micro                            | 1         | 1.96%   |
| Acer                                   | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                                | 2         | 3.92%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 3.92%   |
| Luxvisions Innotech Limited Integrated Camera                            | 2         | 3.92%   |
| Chicony Integrated Camera                                                | 2         | 3.92%   |
| Chicony HP HD Camera                                                     | 2         | 3.92%   |
| Chicony HD WebCam                                                        | 2         | 3.92%   |
| Chicony EasyCamera                                                       | 2         | 3.92%   |
| Syntek Integrated Camera                                                 | 1         | 1.96%   |
| Suyin HP Webcam                                                          | 1         | 1.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 1.96%   |
| Silicon Motion WebCam SC-03FFL11939N                                     | 1         | 1.96%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 1.96%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 1.96%   |
| Realtek HP Truevision HD integrated webcam                               | 1         | 1.96%   |
| Realtek HP Truevision HD                                                 | 1         | 1.96%   |
| Realtek Asus laptop camera                                               | 1         | 1.96%   |
| Quanta USB HD Webcam                                                     | 1         | 1.96%   |
| Quanta HP True Vision FHD Camera                                         | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 1         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.96%   |
| Lite-On TOSHIBA Web Camera - HD                                          | 1         | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.96%   |
| IMC Networks ov9734_azurewave_camera                                     | 1         | 1.96%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 1.96%   |
| IMC Networks EasyCamera                                                  | 1         | 1.96%   |
| Foxconn / Hon Hai USB2.0 Camera                                          | 1         | 1.96%   |
| Chicony XiaoMi USB 2.0 Webcam                                            | 1         | 1.96%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 1         | 1.96%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.96%   |
| Chicony USB 2.0 Camera                                                   | 1         | 1.96%   |
| Chicony HP Truevision HD                                                 | 1         | 1.96%   |
| Chicony HP HD Webcam [Fixed]                                             | 1         | 1.96%   |
| Chicony Gateway USB 2.0 Webcam                                           | 1         | 1.96%   |
| Chicony Front Camera                                                     | 1         | 1.96%   |
| Chicony CNF9055 Toshiba Webcam                                           | 1         | 1.96%   |
| Chicony CNA7157                                                          | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.96%   |
| Bison SunplusIT Integrated Camera                                        | 1         | 1.96%   |
| Bison Integrated Camera                                                  | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Shenzhen Goodix Technology | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Synaptics                  | 1         | 10%     |
| Elan Microelectronics      | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 10%     |
| Validity Sensors VFS491                                                    | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 10%     |
| Elan ELAN:Fingerprint                                                      | 1         | 10%     |
| AuthenTec AES1600                                                          | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 64.52%  |
| 1     | 16        | 25.81%  |
| 2     | 6         | 9.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 35.71%  |
| Camera                   | 6         | 21.43%  |
| Graphics card            | 4         | 14.29%  |
| Bluetooth                | 4         | 14.29%  |
| Net/wireless             | 1         | 3.57%   |
| Multimedia controller    | 1         | 3.57%   |
| Communication controller | 1         | 3.57%   |
| Chipcard                 | 1         | 3.57%   |


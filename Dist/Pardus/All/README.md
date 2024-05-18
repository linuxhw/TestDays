Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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

Total: 126

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Victus by Gaming Laptop ... | Notebook    | [f584b00194](https://linux-hardware.org/?probe=f584b00194) | May 02, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6dbbe3a7b2](https://linux-hardware.org/?probe=6dbbe3a7b2) | May 02, 2024 |
| Pegatron      | A15                         | Notebook    | [259d4c4051](https://linux-hardware.org/?probe=259d4c4051) | Apr 30, 2024 |
| Pegatron      | A15                         | Notebook    | [555c8aa911](https://linux-hardware.org/?probe=555c8aa911) | Apr 30, 2024 |
| Gigabyte      | MH310BP-R6                  | Desktop     | [68e0a22e4d](https://linux-hardware.org/?probe=68e0a22e4d) | Apr 22, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [ef88845d13](https://linux-hardware.org/?probe=ef88845d13) | Apr 20, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ace6254b85](https://linux-hardware.org/?probe=ace6254b85) | Apr 14, 2024 |
| HP            | ProBook 4540s               | Notebook    | [1d64c374de](https://linux-hardware.org/?probe=1d64c374de) | Apr 14, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [3c1f7c3f35](https://linux-hardware.org/?probe=3c1f7c3f35) | Apr 04, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [94e26adce2](https://linux-hardware.org/?probe=94e26adce2) | Apr 01, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [c780c8e75c](https://linux-hardware.org/?probe=c780c8e75c) | Mar 30, 2024 |
| Dell          | 0VNM11 A03                  | Desktop     | [178c559906](https://linux-hardware.org/?probe=178c559906) | Mar 14, 2024 |
| Dell          | 0VNM11 A03                  | Desktop     | [c56a91f121](https://linux-hardware.org/?probe=c56a91f121) | Mar 14, 2024 |
| HP            | Pavilion g6                 | Notebook    | [0590dc2c6d](https://linux-hardware.org/?probe=0590dc2c6d) | Mar 02, 2024 |
| Dell          | Inspiron 14 5401            | Notebook    | [58f0a8c87c](https://linux-hardware.org/?probe=58f0a8c87c) | Feb 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [586fb5dfba](https://linux-hardware.org/?probe=586fb5dfba) | Feb 18, 2024 |
| Dell          | 05WXFV A02                  | Desktop     | [9c231dbc1a](https://linux-hardware.org/?probe=9c231dbc1a) | Feb 13, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [9098ece7f8](https://linux-hardware.org/?probe=9098ece7f8) | Feb 08, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [1fdb1cdc5f](https://linux-hardware.org/?probe=1fdb1cdc5f) | Feb 06, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [d93b9b007a](https://linux-hardware.org/?probe=d93b9b007a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [da159bff10](https://linux-hardware.org/?probe=da159bff10) | Jan 31, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [192a3a0ab1](https://linux-hardware.org/?probe=192a3a0ab1) | Jan 30, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [bb879ce9b9](https://linux-hardware.org/?probe=bb879ce9b9) | Jan 27, 2024 |
| Fujitsu Si... | D2581-A5 S26361-D2581-A5    | Desktop     | [986a67391f](https://linux-hardware.org/?probe=986a67391f) | Jan 09, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| HP            | 82DD                        | All in one  | [5d63cf94b5](https://linux-hardware.org/?probe=5d63cf94b5) | Dec 19, 2023 |
| HP            | 82DD                        | All in one  | [04f88f72a8](https://linux-hardware.org/?probe=04f88f72a8) | Dec 18, 2023 |
| HP            | 82DD                        | All in one  | [3ffc09317f](https://linux-hardware.org/?probe=3ffc09317f) | Dec 18, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [a9b6f1553d](https://linux-hardware.org/?probe=a9b6f1553d) | Dec 16, 2023 |
| HP            | 82DD                        | All in one  | [0ea0ece8c7](https://linux-hardware.org/?probe=0ea0ece8c7) | Dec 15, 2023 |
| HP            | 82DD                        | All in one  | [a70d193fa2](https://linux-hardware.org/?probe=a70d193fa2) | Dec 06, 2023 |
| HP            | 82DD                        | All in one  | [c45bd18bc5](https://linux-hardware.org/?probe=c45bd18bc5) | Dec 06, 2023 |
| HP            | 82DD                        | All in one  | [b302adc5f9](https://linux-hardware.org/?probe=b302adc5f9) | Dec 05, 2023 |
| Intel         | H55                         | Desktop     | [edff4a2637](https://linux-hardware.org/?probe=edff4a2637) | Oct 25, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [9bc8520da8](https://linux-hardware.org/?probe=9bc8520da8) | Sep 04, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [5d42ac567c](https://linux-hardware.org/?probe=5d42ac567c) | Jun 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [7ffc12366e](https://linux-hardware.org/?probe=7ffc12366e) | May 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c68576fce8](https://linux-hardware.org/?probe=c68576fce8) | Apr 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| HP            | 18E6                        | Desktop     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI           | MS-7360                     | Desktop     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| MSI           | MS-7360                     | Desktop     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pardus 21.4   | 12        | 14.29%  |
| Pardus 21.3   | 9         | 10.71%  |
| Pardus 21.2   | 9         | 10.71%  |
| Pardus 21.5   | 8         | 9.52%   |
| Pardus 23.1   | 7         | 8.33%   |
| Pardus 23.0   | 7         | 8.33%   |
| Pardus 21.1   | 6         | 7.14%   |
| Pardus 19.5   | 5         | 5.95%   |
| Pardus 21.0   | 4         | 4.76%   |
| Pardus 19.4-1 | 3         | 3.57%   |
| Pardus 19.4   | 3         | 3.57%   |
| Pardus 19.3   | 3         | 3.57%   |
| Pardus 19.2   | 3         | 3.57%   |
| Pardus 19.0   | 3         | 3.57%   |
| Pardus 19.1   | 2         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 8         | 9.41%   |
| 5.10.0-13-amd64            | 6         | 7.06%   |
| 6.1.0-17-amd64             | 5         | 5.88%   |
| 6.1.0-13-amd64             | 5         | 5.88%   |
| 5.10.0-19-amd64            | 5         | 5.88%   |
| 5.10.0-20-amd64            | 4         | 4.71%   |
| 5.10.0-16-amd64            | 3         | 3.53%   |
| 5.10.0-11-amd64            | 3         | 3.53%   |
| 4.19.0-6-amd64             | 3         | 3.53%   |
| 4.19.0-13-amd64            | 3         | 3.53%   |
| 4.19.0-10-amd64            | 3         | 3.53%   |
| 6.1.0-11-amd64             | 2         | 2.35%   |
| 5.9.0-0.bpo.2-amd64        | 2         | 2.35%   |
| 5.18.0-0.deb11.4-amd64     | 2         | 2.35%   |
| 5.10.0-9-amd64             | 2         | 2.35%   |
| 5.10.0-8-amd64             | 2         | 2.35%   |
| 5.10.0-23-amd64            | 2         | 2.35%   |
| 5.10.0-14-amd64            | 2         | 2.35%   |
| 5.10.0-10-amd64            | 2         | 2.35%   |
| 4.19.0-8-amd64             | 2         | 2.35%   |
| 6.6.13+bpo-amd64           | 1         | 1.18%   |
| 6.1.0-20-amd64             | 1         | 1.18%   |
| 6.1.0-0.deb11.13-amd64     | 1         | 1.18%   |
| 6.0.11-x64v2-rt14-xanmod1  | 1         | 1.18%   |
| 5.4.0-0.bpo.3-amd64        | 1         | 1.18%   |
| 5.19.0-14.1-liquorix-amd64 | 1         | 1.18%   |
| 5.10.0-26-amd64            | 1         | 1.18%   |
| 5.10.0-25-amd64            | 1         | 1.18%   |
| 5.10.0-18-amd64            | 1         | 1.18%   |
| 5.10.0-17-amd64            | 1         | 1.18%   |
| 5.10.0-15-amd64            | 1         | 1.18%   |
| 5.10.0-12-amd64            | 1         | 1.18%   |
| 5.10.0-0.bpo.8-amd64       | 1         | 1.18%   |
| 4.19.0-5-amd64             | 1         | 1.18%   |
| 4.19.0-19-amd64            | 1         | 1.18%   |
| 4.19.0-18-amd64            | 1         | 1.18%   |
| 4.19.0-17-amd64            | 1         | 1.18%   |
| 4.19.0-16-amd64            | 1         | 1.18%   |
| 4.19.0-12-amd64            | 1         | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 44        | 53.66%  |
| 4.19.0  | 16        | 19.51%  |
| 6.1.0   | 14        | 17.07%  |
| 5.9.0   | 2         | 2.44%   |
| 5.18.0  | 2         | 2.44%   |
| 6.6.13  | 1         | 1.22%   |
| 6.0.11  | 1         | 1.22%   |
| 5.4.0   | 1         | 1.22%   |
| 5.19.0  | 1         | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 44        | 53.66%  |
| 4.19    | 16        | 19.51%  |
| 6.1     | 14        | 17.07%  |
| 5.9     | 2         | 2.44%   |
| 5.18    | 2         | 2.44%   |
| 6.6     | 1         | 1.22%   |
| 6.0     | 1         | 1.22%   |
| 5.4     | 1         | 1.22%   |
| 5.19    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 41        | 51.9%   |
| GNOME      | 32        | 40.51%  |
| KDE5       | 3         | 3.8%    |
| Unknown    | 2         | 2.53%   |
| X-Cinnamon | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 74        | 94.87%  |
| Wayland | 2         | 2.56%   |
| Tty     | 2         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 57.5%   |
| LightDM | 10        | 12.5%   |
| GDM     | 10        | 12.5%   |
| TDM     | 6         | 7.5%    |
| GDM3    | 6         | 7.5%    |
| SDDM    | 2         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 62        | 78.48%  |
| en_US   | 9         | 11.39%  |
| Unknown | 3         | 3.8%    |
| pt_BR   | 1         | 1.27%   |
| hu_HU   | 1         | 1.27%   |
| fur_IT  | 1         | 1.27%   |
| fr_FR   | 1         | 1.27%   |
| en_GB   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 58        | 71.6%   |
| EFI  | 23        | 28.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 76        | 97.44%  |
| Overlay | 2         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 49        | 61.25%  |
| GPT     | 23        | 28.75%  |
| MBR     | 8         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 92.31%  |
| Yes       | 6         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 83.33%  |
| Yes       | 13        | 16.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 20.51%  |
| Lenovo              | 14        | 17.95%  |
| ASUSTek Computer    | 9         | 11.54%  |
| Dell                | 7         | 8.97%   |
| MSI                 | 6         | 7.69%   |
| Toshiba             | 4         | 5.13%   |
| Gigabyte Technology | 4         | 5.13%   |
| Acer                | 3         | 3.85%   |
| Sony                | 2         | 2.56%   |
| Packard Bell        | 2         | 2.56%   |
| TUXEDO              | 1         | 1.28%   |
| Samsung Electronics | 1         | 1.28%   |
| Philco              | 1         | 1.28%   |
| Pegatron            | 1         | 1.28%   |
| Olidata             | 1         | 1.28%   |
| Intel               | 1         | 1.28%   |
| HUAWEI              | 1         | 1.28%   |
| Fujitsu Siemens     | 1         | 1.28%   |
| Clevo               | 1         | 1.28%   |
| Casper              | 1         | 1.28%   |
| Apple               | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 3         | 3.85%   |
| HP ProBook 4540s                           | 2         | 2.56%   |
| HP 22-b309nt                               | 2         | 2.56%   |
| Toshiba Satellite L755                     | 1         | 1.28%   |
| Toshiba Satellite C855-1VM                 | 1         | 1.28%   |
| Toshiba Satellite C660                     | 1         | 1.28%   |
| Toshiba PORTEGE M780                       | 1         | 1.28%   |
| Sony SVF1521QSTB                           | 1         | 1.28%   |
| Sony SVE14A2V2ES                           | 1         | 1.28%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 1.28%   |
| Philco 14F                                 | 1         | 1.28%   |
| Pegatron A15                               | 1         | 1.28%   |
| Packard Bell EasyNote_GN45                 | 1         | 1.28%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 1.28%   |
| Olidata T7700                              | 1         | 1.28%   |
| MSI MS-7C09                                | 1         | 1.28%   |
| MSI MS-7A65                                | 1         | 1.28%   |
| MSI MS-7817                                | 1         | 1.28%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 1.28%   |
| Lenovo V145-15AST 81MT                     | 1         | 1.28%   |
| Lenovo V110-15ISK 80TL                     | 1         | 1.28%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 1.28%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 1.28%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 1.28%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 1.28%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 1.28%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS          | 1         | 1.28%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 1.28%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 1.28%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 1.28%   |
| Lenovo G510 20238                          | 1         | 1.28%   |
| Lenovo G50-45 80E3                         | 1         | 1.28%   |
| Intel H55                                  | 1         | 1.28%   |
| HUAWEI KLVL-WXXW                           | 1         | 1.28%   |
| HP Victus by Gaming Laptop 16-s0xxx        | 1         | 1.28%   |
| HP Pavilion Notebook                       | 1         | 1.28%   |
| HP Pavilion g6                             | 1         | 1.28%   |
| HP Pavilion 15                             | 1         | 1.28%   |
| HP Laptop 15-dw3xxx                        | 1         | 1.28%   |
| HP EliteOne 800 G1 AiO                     | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 5.13%   |
| Toshiba Satellite        | 3         | 3.85%   |
| MSI MS-7360              | 3         | 3.85%   |
| HP Pavilion              | 3         | 3.85%   |
| Dell OptiPlex            | 3         | 3.85%   |
| Packard Bell EasyNote    | 2         | 2.56%   |
| Lenovo IdeaPad           | 2         | 2.56%   |
| HP ProBook               | 2         | 2.56%   |
| HP EliteBook             | 2         | 2.56%   |
| HP 22-b309nt             | 2         | 2.56%   |
| Acer Aspire              | 2         | 2.56%   |
| Toshiba PORTEGE          | 1         | 1.28%   |
| Sony SVF1521QSTB         | 1         | 1.28%   |
| Sony SVE14A2V2ES         | 1         | 1.28%   |
| Samsung 300E4A           | 1         | 1.28%   |
| Philco 14F               | 1         | 1.28%   |
| Pegatron A15             | 1         | 1.28%   |
| Olidata T7700            | 1         | 1.28%   |
| MSI MS-7C09              | 1         | 1.28%   |
| MSI MS-7A65              | 1         | 1.28%   |
| MSI MS-7817              | 1         | 1.28%   |
| Lenovo Yoga              | 1         | 1.28%   |
| Lenovo V145-15AST        | 1         | 1.28%   |
| Lenovo V110-15ISK        | 1         | 1.28%   |
| Lenovo ThinkCentre       | 1         | 1.28%   |
| Lenovo IdeaPadFlex       | 1         | 1.28%   |
| Lenovo IdeaPad-510-15IKB | 1         | 1.28%   |
| Lenovo G510              | 1         | 1.28%   |
| Lenovo G50-45            | 1         | 1.28%   |
| Intel H55                | 1         | 1.28%   |
| HUAWEI KLVL-WXXW         | 1         | 1.28%   |
| HP Victus                | 1         | 1.28%   |
| HP Laptop                | 1         | 1.28%   |
| HP EliteOne              | 1         | 1.28%   |
| HP All-in-One            | 1         | 1.28%   |
| HP 530                   | 1         | 1.28%   |
| HP 250                   | 1         | 1.28%   |
| HP 15                    | 1         | 1.28%   |
| Gigabyte MH310BP-R6      | 1         | 1.28%   |
| Gigabyte H410M           | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 11        | 14.1%   |
| 2013 | 11        | 14.1%   |
| 2020 | 6         | 7.69%   |
| 2011 | 6         | 7.69%   |
| 2017 | 5         | 6.41%   |
| 2015 | 5         | 6.41%   |
| 2014 | 5         | 6.41%   |
| 2010 | 5         | 6.41%   |
| 2021 | 4         | 5.13%   |
| 2019 | 4         | 5.13%   |
| 2007 | 4         | 5.13%   |
| 2012 | 3         | 3.85%   |
| 2023 | 2         | 2.56%   |
| 2022 | 2         | 2.56%   |
| 2016 | 2         | 2.56%   |
| 2009 | 1         | 1.28%   |
| 2008 | 1         | 1.28%   |
| 2006 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 48        | 61.54%  |
| Desktop     | 23        | 29.49%  |
| All in one  | 4         | 5.13%   |
| Convertible | 2         | 2.56%   |
| Mini pc     | 1         | 1.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 26        | 32.5%   |
| 4.01-8.0    | 24        | 30%     |
| 8.01-16.0   | 13        | 16.25%  |
| 16.01-24.0  | 10        | 12.5%   |
| 32.01-64.0  | 2         | 2.5%    |
| 2.01-3.0    | 2         | 2.5%    |
| 1.01-2.0    | 2         | 2.5%    |
| 64.01-256.0 | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 32        | 37.65%  |
| 2.01-3.0   | 25        | 29.41%  |
| 3.01-4.0   | 17        | 20%     |
| 4.01-8.0   | 7         | 8.24%   |
| 24.01-32.0 | 1         | 1.18%   |
| 16.01-24.0 | 1         | 1.18%   |
| 8.01-16.0  | 1         | 1.18%   |
| 0.51-1.0   | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 61.54%  |
| 2      | 25        | 32.05%  |
| 3      | 4         | 5.13%   |
| 4      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 54.43%  |
| Yes       | 36        | 45.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 93.59%  |
| No        | 5         | 6.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 78.21%  |
| No        | 17        | 21.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 62.82%  |
| No        | 29        | 37.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Turkey     | 68        | 86.08%  |
| Germany    | 2         | 2.53%   |
| UK         | 1         | 1.27%   |
| Sweden     | 1         | 1.27%   |
| Poland     | 1         | 1.27%   |
| Libya      | 1         | 1.27%   |
| Italy      | 1         | 1.27%   |
| France     | 1         | 1.27%   |
| Bulgaria   | 1         | 1.27%   |
| Brazil     | 1         | 1.27%   |
| Azerbaijan | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Istanbul             | 23        | 27.71%  |
| Ankara               | 10        | 12.05%  |
| Izmir                | 6         | 7.23%   |
| Bursa                | 6         | 7.23%   |
| Aydin                | 6         | 7.23%   |
| Konya                | 3         | 3.61%   |
| Malatya              | 2         | 2.41%   |
| Çorlu               | 2         | 2.41%   |
| Çanakkale           | 2         | 2.41%   |
| Yaman                | 1         | 1.2%    |
| Tripoli              | 1         | 1.2%    |
| Soleymieu            | 1         | 1.2%    |
| Sofia                | 1         | 1.2%    |
| Serik                | 1         | 1.2%    |
| Sao Gabriel          | 1         | 1.2%    |
| Samsun               | 1         | 1.2%    |
| Niğde               | 1         | 1.2%    |
| Mugla                | 1         | 1.2%    |
| London               | 1         | 1.2%    |
| Landskrona           | 1         | 1.2%    |
| Kołobrzeg           | 1         | 1.2%    |
| Kirchheim unter Teck | 1         | 1.2%    |
| Hacilar              | 1         | 1.2%    |
| Gaziantep            | 1         | 1.2%    |
| Esenyurt             | 1         | 1.2%    |
| Castrop-Rauxel       | 1         | 1.2%    |
| Bolzano              | 1         | 1.2%    |
| Bigadic              | 1         | 1.2%    |
| Balıkesir           | 1         | 1.2%    |
| Baku                 | 1         | 1.2%    |
| Artvin               | 1         | 1.2%    |
| Antalya              | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 16        | 23     | 14.55%  |
| WDC                         | 14        | 18     | 12.73%  |
| Samsung Electronics         | 14        | 20     | 12.73%  |
| SanDisk                     | 9         | 9      | 8.18%   |
| Unknown                     | 5         | 6      | 4.55%   |
| Kingston                    | 5         | 6      | 4.55%   |
| Toshiba                     | 4         | 5      | 3.64%   |
| China                       | 4         | 4      | 3.64%   |
| KIOXIA-EXCERIA              | 3         | 3      | 2.73%   |
| KIOXIA                      | 3         | 3      | 2.73%   |
| Hitachi                     | 3         | 3      | 2.73%   |
| A-DATA Technology           | 3         | 3      | 2.73%   |
| SPCC                        | 2         | 2      | 1.82%   |
| SK hynix                    | 2         | 2      | 1.82%   |
| Phison                      | 2         | 2      | 1.82%   |
| Lexar                       | 2         | 2      | 1.82%   |
| Kingston Technology Company | 2         | 2      | 1.82%   |
| HGST                        | 2         | 2      | 1.82%   |
| Corsair                     | 2         | 2      | 1.82%   |
| USB3.0                      | 1         | 1      | 0.91%   |
| Team                        | 1         | 1      | 0.91%   |
| Silicon Motion              | 1         | 1      | 0.91%   |
| Micron/Crucial Technology   | 1         | 1      | 0.91%   |
| Micron Technology           | 1         | 2      | 0.91%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.91%   |
| LITEON                      | 1         | 1      | 0.91%   |
| KingSpec                    | 1         | 1      | 0.91%   |
| Intenso                     | 1         | 2      | 0.91%   |
| Initio                      | 1         | 1      | 0.91%   |
| addlink                     | 1         | 1      | 0.91%   |
| 120G                        | 1         | 1      | 0.91%   |
| Unknown                     | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB             | 3         | 2.65%   |
| Unknown SD/MMC/MS PRO 128GB             | 3         | 2.65%   |
| KIOXIA KBG50ZNS256G NVMe 256GB          | 3         | 2.65%   |
| A-DATA SU650 120GB SSD                  | 3         | 2.65%   |
| SPCC Solid State Disk 512GB             | 2         | 1.77%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 1.77%   |
| Seagate ST1000DM003-1SB102 1TB          | 2         | 1.77%   |
| SanDisk SSD PLUS 240GB                  | 2         | 1.77%   |
| SanDisk SDSSDA240G 240GB                | 2         | 1.77%   |
| KIOXIA-EXCERIA SATA SSD 480GB           | 2         | 1.77%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.77%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.77%   |
| China SATA SSD 240GB                    | 2         | 1.77%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 0.88%   |
| WDC WD5000LPVX-55V0TT0 500GB            | 1         | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.88%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.88%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1         | 0.88%   |
| WDC WD3200BPVT-35JJ5T0 320GB            | 1         | 0.88%   |
| WDC WD3200AAJB-00WGA0 320GB             | 1         | 0.88%   |
| WDC WD2500BEVS-00UST0 250GB             | 1         | 0.88%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.88%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.88%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 0.88%   |
| USB3.0 Super Speed 240GB                | 1         | 0.88%   |
| Unknown SD32G  32GB                     | 1         | 0.88%   |
| Unknown MMC Card  64GB                  | 1         | 0.88%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.88%   |
| Toshiba MK6475GSX 640GB                 | 1         | 0.88%   |
| Toshiba MK5061GSYN 500GB                | 1         | 0.88%   |
| Toshiba DT01ACA100 1TB                  | 1         | 0.88%   |
| Team T253X1240G 240GB SSD               | 1         | 0.88%   |
| SK hynix SC311 SATA 256GB SSD           | 1         | 0.88%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.88%   |
| Silicon Motion Longline SSD 512GB       | 1         | 0.88%   |
| Seagate ST9500325AS 500GB               | 1         | 0.88%   |
| Seagate ST9120822AS 120GB               | 1         | 0.88%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 0.88%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 0.88%   |
| Seagate ST3160318AS 160GB               | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 34.09%  |
| WDC                 | 13        | 17     | 29.55%  |
| Toshiba             | 4         | 5      | 9.09%   |
| Unknown             | 3         | 4      | 6.82%   |
| Samsung Electronics | 3         | 6      | 6.82%   |
| Hitachi             | 3         | 3      | 6.82%   |
| HGST                | 2         | 2      | 4.55%   |
| Initio              | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 17.78%  |
| Samsung Electronics | 6         | 7      | 13.33%  |
| Kingston            | 5         | 6      | 11.11%  |
| China               | 4         | 4      | 8.89%   |
| KIOXIA-EXCERIA      | 3         | 3      | 6.67%   |
| A-DATA Technology   | 3         | 3      | 6.67%   |
| SPCC                | 2         | 2      | 4.44%   |
| Lexar               | 2         | 2      | 4.44%   |
| WDC                 | 1         | 1      | 2.22%   |
| USB3.0              | 1         | 1      | 2.22%   |
| Team                | 1         | 1      | 2.22%   |
| SK hynix            | 1         | 1      | 2.22%   |
| Seagate             | 1         | 1      | 2.22%   |
| Phison              | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 2      | 2.22%   |
| LITEON              | 1         | 1      | 2.22%   |
| KingSpec            | 1         | 1      | 2.22%   |
| Intenso             | 1         | 2      | 2.22%   |
| Corsair             | 1         | 1      | 2.22%   |
| 120G                | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 39        | 60     | 40.63%  |
| SSD     | 38        | 49     | 39.58%  |
| NVMe    | 15        | 20     | 15.63%  |
| MMC     | 2         | 2      | 2.08%   |
| Unknown | 2         | 2      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 104    | 75%     |
| NVMe | 15        | 20     | 17.05%  |
| SAS  | 5         | 7      | 5.68%   |
| MMC  | 2         | 2      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 78     | 70.51%  |
| 0.51-1.0   | 20        | 26     | 25.64%  |
| 1.01-2.0   | 3         | 5      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 40        | 50%     |
| 251-500    | 20        | 25%     |
| 501-1000   | 12        | 15%     |
| 51-100     | 4         | 5%      |
| 21-50      | 3         | 3.75%   |
| 2001-3000  | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 32        | 39.51%  |
| 51-100   | 19        | 23.46%  |
| 21-50    | 16        | 19.75%  |
| 101-250  | 10        | 12.35%  |
| 251-500  | 3         | 3.7%    |
| 501-1000 | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1      | 25%     |
| Seagate ST9120822AS 120GB        | 1         | 1      | 25%     |
| Seagate ST500DM002-1BD142 500GB  | 1         | 1      | 25%     |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 50%     |
| WDC      | 1         | 1      | 25%     |
| Kingston | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 53        | 89     | 61.63%  |
| Works    | 28        | 39     | 32.56%  |
| Malfunc  | 4         | 4      | 4.65%   |
| Failed   | 1         | 1      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 59        | 65.56%  |
| AMD                         | 11        | 12.22%  |
| Samsung Electronics         | 5         | 5.56%   |
| Marvell Technology Group    | 3         | 3.33%   |
| KIOXIA                      | 3         | 3.33%   |
| Phison Electronics          | 2         | 2.22%   |
| Kingston Technology Company | 2         | 2.22%   |
| SK hynix                    | 1         | 1.11%   |
| Silicon Motion              | 1         | 1.11%   |
| SanDisk                     | 1         | 1.11%   |
| Micron/Crucial Technology   | 1         | 1.11%   |
| MAXIO Technology (Hangzhou) | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 9.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 3.81%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 4         | 3.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 4         | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 3.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 2.86%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 3         | 2.86%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 3         | 2.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 3         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.9%    |
| AMD FCH SATA Controller D                                                        | 2         | 1.9%    |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.95%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.95%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 0.95%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 1         | 0.95%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.95%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 1         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 67.05%  |
| NVMe | 15        | 17.05%  |
| IDE  | 12        | 13.64%  |
| RAID | 2         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 83.33%  |
| AMD    | 13        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 3.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 3         | 3.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 2.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 2.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 2.56%   |
| Intel 12th Gen Core i5-12500T           | 2         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.56%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 2.56%   |
| Intel Pentium CPU G2010 @ 2.80GHz       | 1         | 1.28%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 1         | 1.28%   |
| Intel Pentium CPU B950 @ 2.10GHz        | 1         | 1.28%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.28%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.28%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1         | 1.28%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.28%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.28%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.28%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i5-7600 CPU @ 3.50GHz        | 1         | 1.28%   |
| Intel Core i5-6400T CPU @ 2.20GHz       | 1         | 1.28%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1         | 1.28%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 1.28%   |
| Intel Core i5-4260U CPU @ 1.40GHz       | 1         | 1.28%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.28%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.28%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.28%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 1.28%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.28%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.28%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 1.28%   |
| Intel Core i3-8100T CPU @ 3.10GHz       | 1         | 1.28%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.28%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.28%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 20        | 25.64%  |
| Intel Core i3     | 14        | 17.95%  |
| Intel Core i7     | 10        | 12.82%  |
| Other             | 9         | 11.54%  |
| Intel Core 2 Quad | 4         | 5.13%   |
| Intel Pentium     | 3         | 3.85%   |
| AMD A8            | 3         | 3.85%   |
| AMD A10           | 3         | 3.85%   |
| Intel Core 2 Duo  | 2         | 2.56%   |
| Intel Core 2      | 2         | 2.56%   |
| Intel Celeron     | 2         | 2.56%   |
| AMD Ryzen 7       | 2         | 2.56%   |
| AMD Ryzen 5       | 2         | 2.56%   |
| Intel Core i9     | 1         | 1.28%   |
| AMD C-50          | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 51.28%  |
| 4      | 27        | 34.62%  |
| 6      | 7         | 8.97%   |
| 8      | 3         | 3.85%   |
| 12     | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 66.67%  |
| 1      | 26        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 51.22%  |
| 0x306a9    | 5         | 6.1%    |
| 0x306c3    | 3         | 3.66%   |
| 0x906eb    | 2         | 2.44%   |
| 0x90675    | 2         | 2.44%   |
| 0x806ea    | 2         | 2.44%   |
| 0x806e9    | 2         | 2.44%   |
| 0x306d4    | 2         | 2.44%   |
| 0x20655    | 2         | 2.44%   |
| 0x1067a    | 2         | 2.44%   |
| 0x07030105 | 2         | 2.44%   |
| 0x0600611a | 2         | 2.44%   |
| 0x906ed    | 1         | 1.22%   |
| 0x906ea    | 1         | 1.22%   |
| 0x906e9    | 1         | 1.22%   |
| 0x90672    | 1         | 1.22%   |
| 0x806c1    | 1         | 1.22%   |
| 0x6f6      | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x406e3    | 1         | 1.22%   |
| 0x206a7    | 1         | 1.22%   |
| 0x0a704103 | 1         | 1.22%   |
| 0x0a50000d | 1         | 1.22%   |
| 0x08608102 | 1         | 1.22%   |
| 0x06006705 | 1         | 1.22%   |
| 0x05000029 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 16.67%  |
| Haswell          | 8         | 10.26%  |
| IvyBridge        | 7         | 8.97%   |
| SandyBridge      | 6         | 7.69%   |
| Core             | 6         | 7.69%   |
| Excavator        | 5         | 6.41%   |
| Westmere         | 4         | 5.13%   |
| TigerLake        | 4         | 5.13%   |
| Broadwell        | 4         | 5.13%   |
| CometLake        | 3         | 3.85%   |
| Unknown          | 3         | 3.85%   |
| Skylake          | 2         | 2.56%   |
| Puma             | 2         | 2.56%   |
| Penryn           | 2         | 2.56%   |
| Alderlake Hybrid | 2         | 2.56%   |
| Zen 3            | 1         | 1.28%   |
| Zen 2            | 1         | 1.28%   |
| Silvermont       | 1         | 1.28%   |
| Piledriver       | 1         | 1.28%   |
| IceLake          | 1         | 1.28%   |
| Goldmont         | 1         | 1.28%   |
| Bobcat           | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 54.64%  |
| AMD    | 26        | 26.8%   |
| Nvidia | 18        | 18.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 6         | 5.61%   |
| Intel UHD Graphics 620                                                                | 4         | 3.74%   |
| Intel HD Graphics 5500                                                                | 4         | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 3.74%   |
| Nvidia GT200 [GeForce GTX 260]                                                        | 3         | 2.8%    |
| Intel HD Graphics 620                                                                 | 3         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 2.8%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 3         | 2.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 2.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 2.8%    |
| Nvidia GT218 [GeForce 210]                                                            | 2         | 1.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 2         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 1.87%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 2         | 1.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 1.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 2         | 1.87%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                             | 2         | 1.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.87%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 2         | 1.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 1.87%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                    | 2         | 1.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 1         | 0.93%   |
| Nvidia GT218M [GeForce 315M]                                                          | 1         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 525M]                                                       | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 420M]                                                       | 1         | 0.93%   |
| Nvidia GA102 [GeForce RTX 3090]                                                       | 1         | 0.93%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                       | 1         | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 1         | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 1         | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 46.15%  |
| 1 x Nvidia     | 10        | 12.82%  |
| 1 x AMD        | 10        | 12.82%  |
| 2 x AMD        | 7         | 8.97%   |
| Intel + AMD    | 7         | 8.97%   |
| Intel + Nvidia | 6         | 7.69%   |
| AMD + Nvidia   | 2         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 76        | 97.44%  |
| Proprietary | 2         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 71.95%  |
| 0.01-0.5   | 10        | 12.2%   |
| 0.51-1.0   | 6         | 7.32%   |
| 1.01-2.0   | 5         | 6.1%    |
| 5.01-6.0   | 1         | 1.22%   |
| 3.01-4.0   | 1         | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 12        | 15.58%  |
| Samsung Electronics     | 9         | 11.69%  |
| Chimei Innolux          | 9         | 11.69%  |
| Goldstar                | 7         | 9.09%   |
| BOE                     | 7         | 9.09%   |
| AU Optronics            | 7         | 9.09%   |
| Hewlett-Packard         | 4         | 5.19%   |
| Dell                    | 4         | 5.19%   |
| LG Philips              | 2         | 2.6%    |
| Chi Mei Optoelectronics | 2         | 2.6%    |
| Beko                    | 2         | 2.6%    |
| Acer                    | 2         | 2.6%    |
| SAC                     | 1         | 1.3%    |
| Philips                 | 1         | 1.3%    |
| PANDA                   | 1         | 1.3%    |
| Lenovo                  | 1         | 1.3%    |
| Iiyama                  | 1         | 1.3%    |
| HKC                     | 1         | 1.3%    |
| Casper                  | 1         | 1.3%    |
| AOC                     | 1         | 1.3%    |
| Ancor Communications    | 1         | 1.3%    |
| AGO                     | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 3         | 3.8%    |
| Hewlett-Packard ALL-in-One HPN4274 1920x1080 476x268mm 21.5-inch     | 2         | 2.53%   |
| Beko BK UHD TV BEK4448 3840x2160 1210x680mm 54.6-inch                | 2         | 2.53%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch    | 1         | 1.27%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch    | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 1         | 1.27%   |
| Samsung Electronics S27H65x SAM0E1E 1920x1080 598x336mm 27.0-inch    | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 1         | 1.27%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                      | 1         | 1.27%   |
| Philips PHL 243B9 PHL0941 1920x1080 527x296mm 23.8-inch              | 1         | 1.27%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch              | 1         | 1.27%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch          | 1         | 1.27%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.27%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch         | 1         | 1.27%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch         | 1         | 1.27%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch         | 1         | 1.27%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch          | 1         | 1.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 1         | 1.27%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                | 1         | 1.27%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                         | 1         | 1.27%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x287mm 23.0-inch    | 1         | 1.27%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch     | 1         | 1.27%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 1         | 1.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1         | 1.27%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                 | 1         | 1.27%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 1         | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 42.67%  |
| 1366x768 (WXGA)    | 27        | 36%     |
| 3840x2160 (4K)     | 3         | 4%      |
| 1680x1050 (WSXGA+) | 3         | 4%      |
| 1600x900 (HD+)     | 3         | 4%      |
| 1440x900 (WXGA+)   | 2         | 2.67%   |
| 1280x800 (WXGA)    | 2         | 2.67%   |
| 1280x1024 (SXGA)   | 2         | 2.67%   |
| 2160x1440          | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 34        | 43.59%  |
| 23     | 9         | 11.54%  |
| 21     | 7         | 8.97%   |
| 13     | 5         | 6.41%   |
| 14     | 4         | 5.13%   |
| 17     | 3         | 3.85%   |
| 12     | 3         | 3.85%   |
| 72     | 2         | 2.56%   |
| 27     | 2         | 2.56%   |
| 24     | 2         | 2.56%   |
| 19     | 2         | 2.56%   |
| 31     | 1         | 1.28%   |
| 22     | 1         | 1.28%   |
| 20     | 1         | 1.28%   |
| 16     | 1         | 1.28%   |
| 11     | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 53.95%  |
| 401-500     | 14        | 18.42%  |
| 501-600     | 9         | 11.84%  |
| 201-300     | 6         | 7.89%   |
| 351-400     | 3         | 3.95%   |
| 1501-2000   | 2         | 2.63%   |
| 601-700     | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 62        | 82.67%  |
| 16/10 | 5         | 6.67%   |
| 3/2   | 4         | 5.33%   |
| 5/4   | 2         | 2.67%   |
| 4/3   | 2         | 2.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 45.45%  |
| 201-250        | 16        | 20.78%  |
| 81-90          | 8         | 10.39%  |
| 151-200        | 5         | 6.49%   |
| More than 1000 | 2         | 2.6%    |
| 71-80          | 2         | 2.6%    |
| 61-70          | 2         | 2.6%    |
| 301-350        | 2         | 2.6%    |
| 141-150        | 2         | 2.6%    |
| 51-60          | 1         | 1.3%    |
| 351-500        | 1         | 1.3%    |
| 131-140        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 29        | 37.66%  |
| 51-100  | 25        | 32.47%  |
| 121-160 | 16        | 20.78%  |
| 161-240 | 5         | 6.49%   |
| 1-50    | 2         | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 71        | 91.03%  |
| 2     | 5         | 6.41%   |
| 0     | 2         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 54        | 46.96%  |
| Intel                 | 29        | 25.22%  |
| Qualcomm Atheros      | 11        | 9.57%   |
| Broadcom              | 7         | 6.09%   |
| Ralink Technology     | 3         | 2.61%   |
| Ralink                | 3         | 2.61%   |
| ASUSTek Computer      | 2         | 1.74%   |
| ZyXEL Communications  | 1         | 0.87%   |
| Xiaomi                | 1         | 0.87%   |
| MediaTek              | 1         | 0.87%   |
| JMicron Technology    | 1         | 0.87%   |
| Broadcom Limited      | 1         | 0.87%   |
| Aquantia              | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 42        | 29.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 7.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 2.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 2.11%   |
| Intel Wireless 8265 / 8275                                             | 3         | 2.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 2.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2         | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.41%   |
| Intel Wireless 7265                                                    | 2         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.41%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.41%   |
| Intel Ethernet Connection (17) I219-LM                                 | 2         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.41%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]           | 1         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 1         | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                           | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.7%    |
| Intel Wireless 7260                                                    | 1         | 0.7%    |
| Intel Wireless 3160                                                    | 1         | 0.7%    |
| Intel Wi-Fi 6 AX200                                                    | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 34.85%  |
| Realtek Semiconductor | 18        | 27.27%  |
| Qualcomm Atheros      | 9         | 13.64%  |
| Broadcom              | 5         | 7.58%   |
| Ralink Technology     | 3         | 4.55%   |
| Ralink                | 3         | 4.55%   |
| ASUSTek Computer      | 2         | 3.03%   |
| ZyXEL Communications  | 1         | 1.52%   |
| MediaTek              | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 7.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 4.55%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 4.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 3.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 3.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.03%   |
| Intel Wireless 7265                                            | 2         | 3.03%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.03%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.52%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.52%   |
| Intel Wireless 7260                                            | 1         | 1.52%   |
| Intel Wireless 3160                                            | 1         | 1.52%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.52%   |
| Intel Centrino Wireless-N 130                                  | 1         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.52%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.52%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 70.67%  |
| Intel                 | 13        | 17.33%  |
| Qualcomm Atheros      | 3         | 4%      |
| Broadcom              | 3         | 4%      |
| Xiaomi                | 1         | 1.33%   |
| JMicron Technology    | 1         | 1.33%   |
| Aquantia              | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 42        | 55.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 10        | 13.16%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 2         | 2.63%   |
| Intel Ethernet Connection I217-LM                                               | 2         | 2.63%   |
| Intel Ethernet Connection (17) I219-LM                                          | 2         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 1         | 1.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 1         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1         | 1.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                          | 1         | 1.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                          | 1         | 1.32%   |
| Intel Ethernet Controller I225-V                                                | 1         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                                           | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                                            | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                           | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-V                                            | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                           | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                            | 1         | 1.32%   |
| Intel 82577LC Gigabit Network Connection                                        | 1         | 1.32%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile            | 1         | 1.32%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 1         | 1.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                         | 1         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                 | 1         | 1.32%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 54.48%  |
| WiFi     | 61        | 45.52%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 63.86%  |
| Ethernet | 30        | 36.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 66.67%  |
| 1     | 26        | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 92.31%  |
| Yes  | 6         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 36.73%  |
| Realtek Semiconductor           | 9         | 18.37%  |
| Qualcomm Atheros Communications | 5         | 10.2%   |
| Cambridge Silicon Radio         | 3         | 6.12%   |
| Toshiba                         | 2         | 4.08%   |
| Ralink                          | 2         | 4.08%   |
| Lite-On Technology              | 2         | 4.08%   |
| IMC Networks                    | 2         | 4.08%   |
| Broadcom                        | 2         | 4.08%   |
| Realtek                         | 1         | 2.04%   |
| Foxconn International           | 1         | 2.04%   |
| Foxconn / Hon Hai               | 1         | 2.04%   |
| Apple                           | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 10.2%   |
| Realtek Bluetooth Radio                             | 4         | 8.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 6.12%   |
| Intel Bluetooth Device                              | 3         | 6.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.12%   |
| Ralink RT3290 Bluetooth                             | 2         | 4.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 4.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4.08%   |
| Intel AX201 Bluetooth                               | 2         | 4.08%   |
| Broadcom HP Portable Valentine                      | 2         | 4.08%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.04%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 2.04%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.04%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.04%   |
| Realtek Bluetooth Radio                             | 1         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.04%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.04%   |
| Intel AX200 Bluetooth                               | 1         | 2.04%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.04%   |
| IMC Networks Bluetooth Device                       | 1         | 2.04%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2.04%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.04%   |
| Apple Bluetooth Host Controller                     | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 67.71%  |
| AMD                   | 19        | 19.79%  |
| Nvidia                | 10        | 10.42%  |
| Kingston Technology   | 1         | 1.04%   |
| Barco Display Systems | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 4.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.54%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 2.54%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.54%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.54%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.69%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.69%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 2         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.69%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.85%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia Audio device                                                                               | 1         | 0.85%   |
| Kingston Technology HyperX QuadCast S                                                             | 1         | 0.85%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 32.43%  |
| SK hynix            | 5         | 13.51%  |
| Micron Technology   | 5         | 13.51%  |
| Kingston            | 4         | 10.81%  |
| Unknown             | 3         | 8.11%   |
| G.Skill             | 2         | 5.41%   |
| A-DATA Technology   | 2         | 5.41%   |
| Unknown (0x4509)    | 1         | 2.7%    |
| Kingmax             | 1         | 2.7%    |
| Crucial             | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 2         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s              | 2         | 5.26%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s               | 2         | 5.26%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 2.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 2.63%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 2.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 2.63%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s             | 1         | 2.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 2.63%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s              | 1         | 2.63%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 2.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 1         | 2.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 2.63%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 2.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 2.63%   |
| Samsung RAM M378A2K43DB1-CTD 16384MB DIMM DDR4 2667MT/s            | 1         | 2.63%   |
| Samsung RAM M378A1G44BB0-CWE 8GB DIMM DDR4 3200MT/s                | 1         | 2.63%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 2.63%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s               | 1         | 2.63%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s                  | 1         | 2.63%   |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s              | 1         | 2.63%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s            | 1         | 2.63%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 2.63%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 2.63%   |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s              | 1         | 2.63%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 2.63%   |
| Crucial RAM CT16G4SFS8266.C8FE 16GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 2.63%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 2.63%   |
| Unknown                                                            | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 20        | 58.82%  |
| DDR3  | 11        | 32.35%  |
| SDRAM | 1         | 2.94%   |
| DDR5  | 1         | 2.94%   |
| DDR2  | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 72.73%  |
| DIMM         | 8         | 24.24%  |
| Row Of Chips | 1         | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 50%     |
| 4096  | 9         | 26.47%  |
| 16384 | 4         | 11.76%  |
| 2048  | 3         | 8.82%   |
| 32768 | 1         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 8         | 23.53%  |
| 3200    | 7         | 20.59%  |
| 1600    | 7         | 20.59%  |
| 2133    | 4         | 11.76%  |
| 1333    | 2         | 5.88%   |
| 5600    | 1         | 2.94%   |
| 3400    | 1         | 2.94%   |
| 2666    | 1         | 2.94%   |
| 2400    | 1         | 2.94%   |
| 1067    | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Zebra               | 4         | 44.44%  |
| Canon               | 3         | 33.33%  |
| Samsung Electronics | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Zebra TLP2844                       | 3         | 33.33%  |
| Zebra Zebra GC420d Label Printer    | 1         | 11.11%  |
| Samsung CLP-325 Color Laser Printer | 1         | 11.11%  |
| HP LaserJet P1102                   | 1         | 11.11%  |
| Canon PIXMA MX340                   | 1         | 11.11%  |
| Canon LBP6030w/6018w                | 1         | 11.11%  |
| Canon LBP6000                       | 1         | 11.11%  |

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
| Chicony Electronics                    | 16        | 30.77%  |
| Realtek Semiconductor                  | 7         | 13.46%  |
| Microdia                               | 4         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.69%   |
| IMC Networks                           | 3         | 5.77%   |
| Bison Electronics                      | 3         | 5.77%   |
| Quanta                                 | 2         | 3.85%   |
| Luxvisions Innotech Limited            | 2         | 3.85%   |
| Alcor Micro                            | 2         | 3.85%   |
| Syntek                                 | 1         | 1.92%   |
| Suyin                                  | 1         | 1.92%   |
| Silicon Motion                         | 1         | 1.92%   |
| MacroSilicon                           | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Foxconn / Hon Hai                      | 1         | 1.92%   |
| Arkmicro Technologies                  | 1         | 1.92%   |
| Allwinner Technology                   | 1         | 1.92%   |
| ALi                                    | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                                | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 3.85%   |
| Chicony Integrated Camera                                                | 2         | 3.85%   |
| Chicony EasyCamera                                                       | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Integrated Webcam              | 2         | 3.85%   |
| Bison EasyCamera                                                         | 2         | 3.85%   |
| Syntek Integrated Camera                                                 | 1         | 1.92%   |
| Suyin HP Webcam                                                          | 1         | 1.92%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 1.92%   |
| Realtek HP Truevision HD integrated webcam                               | 1         | 1.92%   |
| Realtek HP Truevision HD                                                 | 1         | 1.92%   |
| Realtek HP 2.0MP High Definition Webcam                                  | 1         | 1.92%   |
| Realtek Asus laptop camera                                               | 1         | 1.92%   |
| Quanta USB HD Webcam                                                     | 1         | 1.92%   |
| Quanta HP True Vision FHD Camera                                         | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 1         | 1.92%   |
| Microdia Integrated Camera                                               | 1         | 1.92%   |
| MacroSilicon MiraBox Capture                                             | 1         | 1.92%   |
| Luxvisions Innotech Limited Integrated Camera                            | 1         | 1.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.92%   |
| Lite-On TOSHIBA Web Camera - HD                                          | 1         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.92%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 1.92%   |
| IMC Networks EasyCamera                                                  | 1         | 1.92%   |
| Foxconn / Hon Hai USB2.0 Camera                                          | 1         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 1         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                                             | 1         | 1.92%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.92%   |
| Chicony USB 2.0 Camera                                                   | 1         | 1.92%   |
| Chicony HP Truevision HD                                                 | 1         | 1.92%   |
| Chicony HP High Definition 1MP Webcam                                    | 1         | 1.92%   |
| Chicony HP HD Webcam [Fixed]                                             | 1         | 1.92%   |
| Chicony HP HD Camera                                                     | 1         | 1.92%   |
| Chicony Gateway USB 2.0 Webcam                                           | 1         | 1.92%   |
| Chicony Front Camera                                                     | 1         | 1.92%   |
| Chicony CNF9055 Toshiba Webcam                                           | 1         | 1.92%   |
| Chicony CNA7157                                                          | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 66.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 16.67%  |
| Validity Sensors VFS491                                                    | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 16.67%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 16.67%  |
| AuthenTec AES1600                                                          | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Advanced Card Systems | 2         | 66.67%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 59        | 72.84%  |
| 1     | 18        | 22.22%  |
| 2     | 4         | 4.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 24%     |
| Graphics card            | 5         | 20%     |
| Net/wireless             | 3         | 12%     |
| Communication controller | 3         | 12%     |
| Camera                   | 3         | 12%     |
| Bluetooth                | 3         | 12%     |
| Chipcard                 | 2         | 8%      |


Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2805

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P30AD                       | Desktop     | [63322c386f](https://linux-hardware.org/?probe=63322c386f) | Nov 05, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [f8a30d78d3](https://linux-hardware.org/?probe=f8a30d78d3) | Nov 04, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [b0d77e36b1](https://linux-hardware.org/?probe=b0d77e36b1) | Nov 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [0af35bd53b](https://linux-hardware.org/?probe=0af35bd53b) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [32a001fb07](https://linux-hardware.org/?probe=32a001fb07) | Nov 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| Google        | Akemi                       | Notebook    | [75082d5cf9](https://linux-hardware.org/?probe=75082d5cf9) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [64a6524677](https://linux-hardware.org/?probe=64a6524677) | Oct 31, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| Intel         | X99                         | Desktop     | [426c412f62](https://linux-hardware.org/?probe=426c412f62) | Oct 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [4d9e5a7157](https://linux-hardware.org/?probe=4d9e5a7157) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [8e871997f7](https://linux-hardware.org/?probe=8e871997f7) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [f8e77bd53a](https://linux-hardware.org/?probe=f8e77bd53a) | Oct 28, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [a4bed1729d](https://linux-hardware.org/?probe=a4bed1729d) | Oct 28, 2023 |
| ASUSTek       | V241FA                      | All in one  | [92f8ffc191](https://linux-hardware.org/?probe=92f8ffc191) | Oct 27, 2023 |
| Intel         | DX79TO AAG28805-401         | Desktop     | [75e8f73b6a](https://linux-hardware.org/?probe=75e8f73b6a) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e622e81e16](https://linux-hardware.org/?probe=e622e81e16) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | Notebook    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a7a49e3d3f](https://linux-hardware.org/?probe=a7a49e3d3f) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX534FTC            | Notebook    | [a268a7a10e](https://linux-hardware.org/?probe=a268a7a10e) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [75f2f0b411](https://linux-hardware.org/?probe=75f2f0b411) | Oct 21, 2023 |
| HP            | 3397                        | Desktop     | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b96d2e0be9](https://linux-hardware.org/?probe=b96d2e0be9) | Oct 16, 2023 |
| HP            | 2000                        | Notebook    | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| Dell          | 0V52N7 A00                  | Server      | [757c40f561](https://linux-hardware.org/?probe=757c40f561) | Oct 15, 2023 |
| Dell          | 0V52N7 A00                  | Server      | [8b00ca5242](https://linux-hardware.org/?probe=8b00ca5242) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [66a5a05425](https://linux-hardware.org/?probe=66a5a05425) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | Notebook    | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [551ff39482](https://linux-hardware.org/?probe=551ff39482) | Oct 14, 2023 |
| Lenovo        | 3112 SDK0J40697 WIN 3305... | All in one  | [dec3f47001](https://linux-hardware.org/?probe=dec3f47001) | Oct 14, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [ca520343c8](https://linux-hardware.org/?probe=ca520343c8) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [662b033cee](https://linux-hardware.org/?probe=662b033cee) | Oct 12, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [3069c746fd](https://linux-hardware.org/?probe=3069c746fd) | Oct 12, 2023 |
| HP            | 8437                        | Desktop     | [ac8d6773a3](https://linux-hardware.org/?probe=ac8d6773a3) | Oct 11, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [13dd011d9b](https://linux-hardware.org/?probe=13dd011d9b) | Oct 10, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [cb78c82e7a](https://linux-hardware.org/?probe=cb78c82e7a) | Oct 09, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| HP            | 0A58h                       | Desktop     | [f55b84ff65](https://linux-hardware.org/?probe=f55b84ff65) | Oct 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5324f47bcf](https://linux-hardware.org/?probe=5324f47bcf) | Oct 07, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [cad844c720](https://linux-hardware.org/?probe=cad844c720) | Oct 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [60d5b8f4c0](https://linux-hardware.org/?probe=60d5b8f4c0) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [99f8282319](https://linux-hardware.org/?probe=99f8282319) | Oct 06, 2023 |
| HP            | ProBook 6450b               | Notebook    | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| Google        | Magpie                      | Notebook    | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [504010f96c](https://linux-hardware.org/?probe=504010f96c) | Oct 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [96c62ad87e](https://linux-hardware.org/?probe=96c62ad87e) | Oct 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Google        | Magpie                      | Notebook    | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | Notebook    | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [eab41d0848](https://linux-hardware.org/?probe=eab41d0848) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| HP            | 1496                        | Desktop     | [3867e7af58](https://linux-hardware.org/?probe=3867e7af58) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d59518d612](https://linux-hardware.org/?probe=d59518d612) | Sep 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9ea546d36c](https://linux-hardware.org/?probe=9ea546d36c) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [65e95a03e9](https://linux-hardware.org/?probe=65e95a03e9) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [34857762c0](https://linux-hardware.org/?probe=34857762c0) | Sep 21, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c40b9df526](https://linux-hardware.org/?probe=c40b9df526) | Sep 21, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9caba9ee44](https://linux-hardware.org/?probe=9caba9ee44) | Sep 21, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [07431109a7](https://linux-hardware.org/?probe=07431109a7) | Sep 21, 2023 |
| ASUSTek       | B150M-C D3                  | Desktop     | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [6ed76f72d7](https://linux-hardware.org/?probe=6ed76f72d7) | Sep 19, 2023 |
| HP            | 158B                        | Desktop     | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [afbaf99497](https://linux-hardware.org/?probe=afbaf99497) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [effa0104c0](https://linux-hardware.org/?probe=effa0104c0) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [72ec01815f](https://linux-hardware.org/?probe=72ec01815f) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [365a5e674f](https://linux-hardware.org/?probe=365a5e674f) | Sep 15, 2023 |
| HP            | 158B                        | Desktop     | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [356d6d3e13](https://linux-hardware.org/?probe=356d6d3e13) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [7ae470ffa8](https://linux-hardware.org/?probe=7ae470ffa8) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| HP            | 339A                        | Desktop     | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | Desktop     | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [78a9c8ba47](https://linux-hardware.org/?probe=78a9c8ba47) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a8f64806fe](https://linux-hardware.org/?probe=a8f64806fe) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [015ea66c32](https://linux-hardware.org/?probe=015ea66c32) | Sep 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Acer          | Nitro AN515-41              | Notebook    | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| HP            | 15                          | Notebook    | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | TMP645-M                    | Notebook    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8169effdbe](https://linux-hardware.org/?probe=8169effdbe) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [78a62eeefe](https://linux-hardware.org/?probe=78a62eeefe) | Aug 26, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| Acer          | EQ45LM                      | Desktop     | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | Desktop     | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | Notebook    | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [74d96ec17a](https://linux-hardware.org/?probe=74d96ec17a) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [8e4f3bf14e](https://linux-hardware.org/?probe=8e4f3bf14e) | Aug 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Allview       | Allbook H                   | Notebook    | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [144f77980e](https://linux-hardware.org/?probe=144f77980e) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | AO756                       | Notebook    | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Acer          | EQ45LM                      | Desktop     | [b9be16315e](https://linux-hardware.org/?probe=b9be16315e) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c279d0ba16](https://linux-hardware.org/?probe=c279d0ba16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | Notebook    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [9f04167710](https://linux-hardware.org/?probe=9f04167710) | Jul 27, 2023 |
| Acer          | EQ45LM                      | Desktop     | [29e2f587cd](https://linux-hardware.org/?probe=29e2f587cd) | Jul 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [37f6c76c11](https://linux-hardware.org/?probe=37f6c76c11) | Jul 25, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3057a60e0f](https://linux-hardware.org/?probe=3057a60e0f) | Jul 17, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [052b5c1741](https://linux-hardware.org/?probe=052b5c1741) | Jul 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f35543549c](https://linux-hardware.org/?probe=f35543549c) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [3cafc83ffb](https://linux-hardware.org/?probe=3cafc83ffb) | Jul 08, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| Dell          | Latitude 3500               | Notebook    | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| Dell          | Studio 1749                 | Notebook    | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [79d631563a](https://linux-hardware.org/?probe=79d631563a) | Jul 01, 2023 |
| Acer          | EQ45LM                      | Desktop     | [30781f8f1b](https://linux-hardware.org/?probe=30781f8f1b) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Acer          | Swift SF314-52G             | Notebook    | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [c6a929a9ec](https://linux-hardware.org/?probe=c6a929a9ec) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [d72b8e616f](https://linux-hardware.org/?probe=d72b8e616f) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [f1f16d8add](https://linux-hardware.org/?probe=f1f16d8add) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| HP            | 81B3                        | Desktop     | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [b9eb9677f5](https://linux-hardware.org/?probe=b9eb9677f5) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [7cd25ddbda](https://linux-hardware.org/?probe=7cd25ddbda) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | Notebook    | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Dell          | Latitude E6440              | Notebook    | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Dell          | G15 5510                    | Notebook    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [7a892801c0](https://linux-hardware.org/?probe=7a892801c0) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Dell          | Precision 7540              | Notebook    | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [cb3e4d2c2b](https://linux-hardware.org/?probe=cb3e4d2c2b) | May 24, 2023 |
| Allview       | Allbook H                   | Notebook    | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| HP            | 805D                        | Desktop     | [2ac4992bcd](https://linux-hardware.org/?probe=2ac4992bcd) | May 22, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ceeff309eb](https://linux-hardware.org/?probe=ceeff309eb) | May 18, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af96be2497](https://linux-hardware.org/?probe=af96be2497) | May 11, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f4146c326](https://linux-hardware.org/?probe=5f4146c326) | May 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [8f9a64c245](https://linux-hardware.org/?probe=8f9a64c245) | May 08, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [62813124bb](https://linux-hardware.org/?probe=62813124bb) | May 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [862ef64565](https://linux-hardware.org/?probe=862ef64565) | May 05, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| HP            | Notebook                    | Notebook    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e055c16455](https://linux-hardware.org/?probe=e055c16455) | May 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [4607549f5a](https://linux-hardware.org/?probe=4607549f5a) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [754b22a59c](https://linux-hardware.org/?probe=754b22a59c) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [01458c55a9](https://linux-hardware.org/?probe=01458c55a9) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [df53e54c69](https://linux-hardware.org/?probe=df53e54c69) | Apr 28, 2023 |
| Acer          | Aspire 5110                 | Notebook    | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| Samsung       | 730QDA                      | Convertible | [a6fef02901](https://linux-hardware.org/?probe=a6fef02901) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [481c5a9169](https://linux-hardware.org/?probe=481c5a9169) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1127dfa79c](https://linux-hardware.org/?probe=1127dfa79c) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | 1495                        | Desktop     | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | Notebook    | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [0fbd47b12e](https://linux-hardware.org/?probe=0fbd47b12e) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [90796fbad9](https://linux-hardware.org/?probe=90796fbad9) | Mar 31, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | Notebook    | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| HP            | Compaq 6735b                | Notebook    | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9fba7bceb7](https://linux-hardware.org/?probe=9fba7bceb7) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [ea8bb4c0e4](https://linux-hardware.org/?probe=ea8bb4c0e4) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| HP            | 0AA8h                       | Desktop     | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a2729c9880](https://linux-hardware.org/?probe=a2729c9880) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 1494                        | Desktop     | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0c14eb04ce](https://linux-hardware.org/?probe=0c14eb04ce) | Feb 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | Notebook    | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| ASRock        | J4125M                      | Desktop     | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | Notebook    | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| Dell          | Precision M6600             | Notebook    | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6584beb723](https://linux-hardware.org/?probe=6584beb723) | Jan 15, 2023 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [6a4e71bb84](https://linux-hardware.org/?probe=6a4e71bb84) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [f12439ce42](https://linux-hardware.org/?probe=f12439ce42) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| HP            | 21F5                        | Desktop     | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [564c992a69](https://linux-hardware.org/?probe=564c992a69) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | Notebook    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | Notebook    | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | Notebook    | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | Notebook    | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | Notebook    | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Dell          | System XPS L702X            | Notebook    | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | Notebook    | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | Desktop     | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | Notebook    | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [d678cbb1cc](https://linux-hardware.org/?probe=d678cbb1cc) | Mar 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | Desktop     | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c57b3c9081](https://linux-hardware.org/?probe=c57b3c9081) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [a7034fd62e](https://linux-hardware.org/?probe=a7034fd62e) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [61c4a46887](https://linux-hardware.org/?probe=61c4a46887) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | Notebook    | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | Notebook    | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [be010e2d04](https://linux-hardware.org/?probe=be010e2d04) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | 09F8h                       | Desktop     | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | Desktop     | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | Desktop     | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | Notebook    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | Notebook    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [275d33a826](https://linux-hardware.org/?probe=275d33a826) | Feb 06, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Allview       | Allbook H                   | Notebook    | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Acer          | Extensa 2510                | Notebook    | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | Notebook    | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [12db3650f6](https://linux-hardware.org/?probe=12db3650f6) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Acer          | Aspire T3-710 V:1.1         | Desktop     | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [1630e680bc](https://linux-hardware.org/?probe=1630e680bc) | Jan 06, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 211       | 10.22%  |
| Ubuntu 18.04                 | 106       | 5.14%   |
| Ubuntu 22.04                 | 96        | 4.65%   |
| BlackPanther 18.1            | 62        | 3%      |
| OpenMandriva 4.3             | 50        | 2.42%   |
| OpenMandriva 4.2             | 45        | 2.18%   |
| Manjaro                      | 33        | 1.6%    |
| Arch Rolling                 | 32        | 1.55%   |
| Debian 11                    | 30        | 1.45%   |
| Zorin 16                     | 28        | 1.36%   |
| Arch                         | 28        | 1.36%   |
| ROSA R10                     | 27        | 1.31%   |
| KDE neon 20.04               | 24        | 1.16%   |
| Pop!_OS 22.04                | 23        | 1.11%   |
| Pop!_OS 21.04                | 23        | 1.11%   |
| ArcoLinux Rolling            | 23        | 1.11%   |
| Linux Mint 21.1              | 21        | 1.02%   |
| Ubuntu 21.10                 | 20        | 0.97%   |
| Pop!_OS 20.04                | 20        | 0.97%   |
| Endless 3.7.8                | 20        | 0.97%   |
| Zorin 15                     | 19        | 0.92%   |
| Fedora 35                    | 19        | 0.92%   |
| Ubuntu 23.04                 | 18        | 0.87%   |
| Ubuntu 20.10                 | 18        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 0.87%   |
| Endless 3.9.5                | 18        | 0.87%   |
| Endless 3.9.1                | 18        | 0.87%   |
| Ubuntu 19.10                 | 17        | 0.82%   |
| OpenMandriva 23.01           | 17        | 0.82%   |
| Ubuntu 21.04                 | 16        | 0.78%   |
| Fedora 38                    | 16        | 0.78%   |
| Ubuntu 19.04                 | 15        | 0.73%   |
| Pop!_OS 20.10                | 15        | 0.73%   |
| Linux Mint 20.3              | 15        | 0.73%   |
| Linux Mint 20.2              | 15        | 0.73%   |
| Fedora 34                    | 15        | 0.73%   |
| Endless 3.8.6                | 15        | 0.73%   |
| Endless 3.8.0                | 15        | 0.73%   |
| Ubuntu 22.10                 | 14        | 0.68%   |
| Linux Mint 20.1              | 14        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 523       | 27.38%  |
| Endless       | 253       | 13.25%  |
| OpenMandriva  | 157       | 8.22%   |
| Linux Mint    | 112       | 5.86%   |
| Fedora        | 105       | 5.5%    |
| Pop!_OS       | 89        | 4.66%   |
| ROSA          | 67        | 3.51%   |
| BlackPanther  | 64        | 3.35%   |
| Manjaro       | 63        | 3.3%    |
| Debian        | 61        | 3.19%   |
| Arch          | 59        | 3.09%   |
| Zorin         | 50        | 2.62%   |
| KDE neon      | 33        | 1.73%   |
| ArcoLinux     | 26        | 1.36%   |
| Xubuntu       | 24        | 1.26%   |
| openSUSE      | 23        | 1.2%    |
| Kubuntu       | 22        | 1.15%   |
| Ubuntu Unity  | 14        | 0.73%   |
| Clear Linux   | 14        | 0.73%   |
| Kali          | 12        | 0.63%   |
| Gentoo        | 11        | 0.58%   |
| Ubuntu MATE   | 10        | 0.52%   |
| Elementary    | 10        | 0.52%   |
| EndeavourOS   | 9         | 0.47%   |
| SteamOS       | 8         | 0.42%   |
| Peppermint    | 7         | 0.37%   |
| Garuda Linux  | 7         | 0.37%   |
| MX            | 6         | 0.31%   |
| LMDE          | 6         | 0.31%   |
| Linux Lite    | 6         | 0.31%   |
| Nobara        | 5         | 0.26%   |
| Lubuntu       | 5         | 0.26%   |
| Xero          | 4         | 0.21%   |
| Ubuntu Budgie | 4         | 0.21%   |
| Raspbian      | 4         | 0.21%   |
| CentOS        | 4         | 0.21%   |
| Artix         | 4         | 0.21%   |
| Solus         | 3         | 0.16%   |
| Ubuntu Studio | 2         | 0.1%    |
| RHEL          | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 70        | 3.21%   |
| 5.4.0-42-generic                | 50        | 2.29%   |
| 4.18.16-desktop-1bP             | 47        | 2.16%   |
| 5.10.14-desktop-1omv4002        | 44        | 2.02%   |
| 5.16.7-desktop-1omv4003         | 42        | 1.93%   |
| 5.4.0-19-generic                | 32        | 1.47%   |
| 5.3.0-28-generic                | 26        | 1.19%   |
| 5.11.0-35-generic               | 19        | 0.87%   |
| 5.3.0-23-generic                | 18        | 0.83%   |
| 6.1.1-desktop-1omv2290          | 17        | 0.78%   |
| 4.18.0-15-generic               | 17        | 0.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.73%   |
| 5.6.14-desktop-2bP              | 15        | 0.69%   |
| 5.0.0-25-generic                | 15        | 0.69%   |
| 6.2.6-desktop-1omv2390          | 14        | 0.64%   |
| 5.4.0-40-generic                | 14        | 0.64%   |
| 5.15.0-58-generic               | 14        | 0.64%   |
| 5.3.0-46-generic                | 13        | 0.6%    |
| 5.0.0-20-generic                | 12        | 0.55%   |
| 5.4.0-52-generic                | 11        | 0.5%    |
| 5.4.0-29-generic                | 11        | 0.5%    |
| 5.4.0-26-generic                | 11        | 0.5%    |
| 5.3.0-19-generic                | 11        | 0.5%    |
| 5.15.0-52-generic               | 11        | 0.5%    |
| 5.4.0-56-generic                | 10        | 0.46%   |
| 5.4.0-54-generic                | 10        | 0.46%   |
| 5.15.0-56-generic               | 10        | 0.46%   |
| 5.13.0-28-generic               | 10        | 0.46%   |
| 5.11.0-7620-generic             | 10        | 0.46%   |
| 5.11.0-43-generic               | 10        | 0.46%   |
| 5.0.0-37-generic                | 10        | 0.46%   |
| 4.15.0-15-generic               | 10        | 0.46%   |
| 5.8.0-50-generic                | 9         | 0.41%   |
| 5.4.0-7634-generic              | 9         | 0.41%   |
| 5.4.0-74-generic                | 9         | 0.41%   |
| 5.4.0-66-generic                | 9         | 0.41%   |
| 5.4.0-47-generic                | 9         | 0.41%   |
| 5.4.0-37-generic                | 9         | 0.41%   |
| 5.4.0-31-generic                | 9         | 0.41%   |
| 5.3.0-51-generic                | 9         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 306       | 14.65%  |
| 5.8.0   | 151       | 7.23%   |
| 5.15.0  | 142       | 6.8%    |
| 5.3.0   | 117       | 5.6%    |
| 5.11.0  | 102       | 4.88%   |
| 4.15.0  | 97        | 4.64%   |
| 5.0.0   | 80        | 3.83%   |
| 5.13.0  | 68        | 3.26%   |
| 4.18.0  | 54        | 2.58%   |
| 5.19.0  | 50        | 2.39%   |
| 4.18.16 | 47        | 2.25%   |
| 5.10.14 | 45        | 2.15%   |
| 5.16.7  | 42        | 2.01%   |
| 5.10.0  | 39        | 1.87%   |
| 6.2.0   | 38        | 1.82%   |
| 6.1.0   | 21        | 1.01%   |
| 6.1.1   | 20        | 0.96%   |
| 6.2.6   | 19        | 0.91%   |
| 4.9.60  | 18        | 0.86%   |
| 5.6.14  | 16        | 0.77%   |
| 4.9.20  | 15        | 0.72%   |
| 6.5.5   | 11        | 0.53%   |
| 6.4.11  | 11        | 0.53%   |
| 6.3.5   | 11        | 0.53%   |
| 4.19.0  | 11        | 0.53%   |
| 6.1.12  | 10        | 0.48%   |
| 4.13.0  | 10        | 0.48%   |
| 5.16.13 | 9         | 0.43%   |
| 4.9.76  | 8         | 0.38%   |
| 6.0.11  | 7         | 0.34%   |
| 5.8.18  | 7         | 0.34%   |
| 6.0.0   | 6         | 0.29%   |
| 5.18.10 | 6         | 0.29%   |
| 5.17.0  | 6         | 0.29%   |
| 6.5.6   | 5         | 0.24%   |
| 6.0.6   | 5         | 0.24%   |
| 6.0.12  | 5         | 0.24%   |
| 5.9.16  | 5         | 0.24%   |
| 5.9.0   | 5         | 0.24%   |
| 5.18.12 | 5         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 328       | 15.88%  |
| 5.15    | 189       | 9.15%   |
| 5.8     | 178       | 8.62%   |
| 5.3     | 127       | 6.15%   |
| 5.11    | 116       | 5.61%   |
| 5.10    | 107       | 5.18%   |
| 4.18    | 103       | 4.99%   |
| 4.15    | 97        | 4.7%    |
| 5.0     | 85        | 4.11%   |
| 5.16    | 75        | 3.63%   |
| 5.13    | 75        | 3.63%   |
| 6.1     | 73        | 3.53%   |
| 6.2     | 72        | 3.48%   |
| 5.19    | 69        | 3.34%   |
| 4.9     | 50        | 2.42%   |
| 6.0     | 36        | 1.74%   |
| 6.5     | 31        | 1.5%    |
| 5.6     | 30        | 1.45%   |
| 5.18    | 26        | 1.26%   |
| 6.4     | 25        | 1.21%   |
| 6.3     | 23        | 1.11%   |
| 5.9     | 22        | 1.06%   |
| 5.17    | 22        | 1.06%   |
| 5.14    | 20        | 0.97%   |
| 5.12    | 18        | 0.87%   |
| 4.19    | 14        | 0.68%   |
| 5.7     | 10        | 0.48%   |
| 4.13    | 10        | 0.48%   |
| 4.1     | 8         | 0.39%   |
| 5.5     | 7         | 0.34%   |
| 5.2     | 5         | 0.24%   |
| 5.1     | 4         | 0.19%   |
| 4.8     | 3         | 0.15%   |
| 4.12    | 2         | 0.1%    |
| 4.4     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 3.10    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1796      | 97.61%  |
| i686    | 34        | 1.85%   |
| armv7l  | 5         | 0.27%   |
| aarch64 | 5         | 0.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 898       | 46.87%  |
| KDE5             | 376       | 19.62%  |
| Unknown          | 229       | 11.95%  |
| XFCE             | 108       | 5.64%   |
| X-Cinnamon       | 82        | 4.28%   |
| KDE4             | 44        | 2.3%    |
| KDE              | 39        | 2.04%   |
| MATE             | 29        | 1.51%   |
| LXQt             | 16        | 0.84%   |
| Unity            | 14        | 0.73%   |
| LXDE             | 14        | 0.73%   |
| Cinnamon         | 14        | 0.73%   |
| i3               | 10        | 0.52%   |
| Pantheon         | 8         | 0.42%   |
| Budgie           | 5         | 0.26%   |
| sway             | 3         | 0.16%   |
| Openbox          | 3         | 0.16%   |
| Hyprland         | 3         | 0.16%   |
| GNOME Classic    | 3         | 0.16%   |
| Deepin           | 3         | 0.16%   |
| xmonad           | 2         | 0.1%    |
| GNOME Flashback  | 2         | 0.1%    |
| awesome          | 2         | 0.1%    |
| sussy_bspwm      | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| jwm              | 1         | 0.05%   |
| GNUstep          | 1         | 0.05%   |
| GNOME-Flashback  | 1         | 0.05%   |
| Endless:GNOME    | 1         | 0.05%   |
| dusk             | 1         | 0.05%   |
| bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1435      | 76.05%  |
| Wayland     | 273       | 14.47%  |
| Unknown     | 150       | 7.95%   |
| Tty         | 28        | 1.48%   |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 997       | 52.06%  |
| SDDM    | 335       | 17.49%  |
| GDM3    | 178       | 9.3%    |
| GDM     | 178       | 9.3%    |
| LightDM | 132       | 6.89%   |
| KDM     | 44        | 2.3%    |
| TDM     | 41        | 2.14%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 3         | 0.16%   |
| Ly      | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1137      | 60.06%  |
| ro_RO       | 317       | 16.75%  |
| Unknown     | 313       | 16.53%  |
| en_GB       | 38        | 2.01%   |
| C           | 28        | 1.48%   |
| hu_HU       | 15        | 0.79%   |
| it_IT       | 10        | 0.53%   |
| es_ES       | 7         | 0.37%   |
| fr_FR       | 4         | 0.21%   |
| de_DE       | 4         | 0.21%   |
| en_IL       | 3         | 0.16%   |
| ru_RU       | 2         | 0.11%   |
| en_IN       | 2         | 0.11%   |
| en_AG       | 2         | 0.11%   |
| uk_UA       | 1         | 0.05%   |
| nl_NL       | 1         | 0.05%   |
| fr_CH       | 1         | 0.05%   |
| es_MX       | 1         | 0.05%   |
| en_US.UTF8  | 1         | 0.05%   |
| en_US.UTF.8 | 1         | 0.05%   |
| en_US.utf-8 | 1         | 0.05%   |
| en_DE       | 1         | 0.05%   |
| en_CA       | 1         | 0.05%   |
| en_001      | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 968       | 51.57%  |
| BIOS | 909       | 48.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1345      | 71.16%  |
| Overlay | 189       | 10%     |
| Unknown | 154       | 8.15%   |
| Btrfs   | 136       | 7.2%    |
| Tmpfs   | 31        | 1.64%   |
| Xfs     | 20        | 1.06%   |
| Zfs     | 7         | 0.37%   |
| F2fs    | 3         | 0.16%   |
| Ext2    | 3         | 0.16%   |
| Jfs     | 1         | 0.05%   |
| Ext3    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1027      | 54.74%  |
| GPT     | 601       | 32.04%  |
| MBR     | 248       | 13.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1620      | 86.45%  |
| Yes       | 254       | 13.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1358      | 72.47%  |
| Yes       | 516       | 27.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 476       | 25.9%   |
| Lenovo                  | 291       | 15.83%  |
| Hewlett-Packard         | 221       | 12.02%  |
| Dell                    | 209       | 11.37%  |
| Acer                    | 139       | 7.56%   |
| Gigabyte Technology     | 133       | 7.24%   |
| MSI                     | 80        | 4.35%   |
| ASRock                  | 49        | 2.67%   |
| Toshiba                 | 27        | 1.47%   |
| Intel                   | 18        | 0.98%   |
| Fujitsu Siemens         | 14        | 0.76%   |
| Apple                   | 14        | 0.76%   |
| Complet                 | 12        | 0.65%   |
| Fujitsu                 | 11        | 0.6%    |
| Unknown                 | 11        | 0.6%    |
| Sony                    | 10        | 0.54%   |
| Medion                  | 9         | 0.49%   |
| HUAWEI                  | 9         | 0.49%   |
| Raspberry Pi Foundation | 8         | 0.44%   |
| Valve                   | 7         | 0.38%   |
| Samsung Electronics     | 7         | 0.38%   |
| Allview                 | 7         | 0.38%   |
| Pegatron                | 6         | 0.33%   |
| Foxconn                 | 6         | 0.33%   |
| Chuwi                   | 5         | 0.27%   |
| Packard Bell            | 4         | 0.22%   |
| Alienware               | 3         | 0.16%   |
| WesternDigital          | 2         | 0.11%   |
| TUXEDO                  | 2         | 0.11%   |
| Timi                    | 2         | 0.11%   |
| Supermicro              | 2         | 0.11%   |
| IBM                     | 2         | 0.11%   |
| Google                  | 2         | 0.11%   |
| BESSTAR Tech            | 2         | 0.11%   |
| AZW                     | 2         | 0.11%   |
| AMI                     | 2         | 0.11%   |
| ZOTAC                   | 1         | 0.05%   |
| WEIGO                   | 1         | 0.05%   |
| Visual Fan              | 1         | 0.05%   |
| VALE                    | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 0.92%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 17        | 0.92%   |
| ASUS All Series                            | 15        | 0.82%   |
| Unknown                                    | 14        | 0.76%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 10        | 0.54%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.54%   |
| Acer Veriton L670G                         | 10        | 0.54%   |
| Valve Jupiter                              | 7         | 0.38%   |
| Gigabyte B450M DS3H                        | 7         | 0.38%   |
| Dell XPS 15 9530                           | 7         | 0.38%   |
| Complet MY8312                             | 7         | 0.38%   |
| ASUS X541UAK                               | 7         | 0.38%   |
| ASUS X406UAR                               | 7         | 0.38%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.33%   |
| ASUS X541UVK                               | 6         | 0.33%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.33%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.33%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.27%   |
| HP Notebook                                | 5         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 5         | 0.27%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.27%   |
| ASUS PRIME A320M-K                         | 5         | 0.27%   |
| ASUS GL552JX                               | 5         | 0.27%   |
| Allview Allbook H                          | 5         | 0.27%   |
| Acer Aspire A315-21G                       | 5         | 0.27%   |
| MSI MS-7996                                | 4         | 0.22%   |
| MSI MS-7721                                | 4         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.22%   |
| Lenovo G510 20238                          | 4         | 0.22%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.22%   |
| Dell OptiPlex 7010                         | 4         | 0.22%   |
| Dell Latitude E6410                        | 4         | 0.22%   |
| Dell Inspiron 5558                         | 4         | 0.22%   |
| Dell Inspiron 1545                         | 4         | 0.22%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.22%   |
| ASUS X542UAR                               | 4         | 0.22%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.22%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 124       | 6.75%   |
| Acer Aspire             | 87        | 4.73%   |
| Lenovo IdeaPad          | 86        | 4.68%   |
| Lenovo ThinkPad         | 85        | 4.62%   |
| Dell Latitude           | 58        | 3.16%   |
| Dell Inspiron           | 52        | 2.83%   |
| HP Compaq               | 39        | 2.12%   |
| ASUS PRIME              | 34        | 1.85%   |
| HP ProBook              | 31        | 1.69%   |
| HP EliteBook            | 30        | 1.63%   |
| Dell OptiPlex           | 30        | 1.63%   |
| ASUS ROG                | 30        | 1.63%   |
| Toshiba Satellite       | 26        | 1.41%   |
| Lenovo Legion           | 26        | 1.41%   |
| HP Pavilion             | 24        | 1.31%   |
| ASUS ASUS               | 21        | 1.14%   |
| Dell XPS                | 20        | 1.09%   |
| Lenovo ThinkCentre      | 19        | 1.03%   |
| ASUS TUF                | 18        | 0.98%   |
| HP Laptop               | 17        | 0.92%   |
| ASUS X541NA             | 17        | 0.92%   |
| ASUS All                | 15        | 0.82%   |
| Acer Veriton            | 15        | 0.82%   |
| Dell Vostro             | 14        | 0.76%   |
| ASUS ZenBook            | 14        | 0.76%   |
| Unknown                 | 14        | 0.76%   |
| Dell Precision          | 12        | 0.65%   |
| Lenovo ThinkBook        | 10        | 0.54%   |
| HP 250                  | 10        | 0.54%   |
| Lenovo Yoga             | 9         | 0.49%   |
| Gigabyte B450M          | 9         | 0.49%   |
| Fujitsu Siemens ESPRIMO | 9         | 0.49%   |
| Acer Nitro              | 9         | 0.49%   |
| RPi Raspberry           | 8         | 0.44%   |
| Valve Jupiter           | 7         | 0.38%   |
| HP ZBook                | 7         | 0.38%   |
| HP OMEN                 | 7         | 0.38%   |
| Dell PowerEdge          | 7         | 0.38%   |
| Complet MY8312          | 7         | 0.38%   |
| ASUS X541UAK            | 7         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 224       | 12.19%  |
| 2018    | 206       | 11.21%  |
| 2020    | 161       | 8.76%   |
| 2017    | 154       | 8.38%   |
| 2015    | 119       | 6.47%   |
| 2021    | 118       | 6.42%   |
| 2013    | 115       | 6.26%   |
| 2012    | 104       | 5.66%   |
| 2011    | 101       | 5.5%    |
| 2014    | 93        | 5.06%   |
| 2010    | 83        | 4.52%   |
| 2008    | 76        | 4.13%   |
| 2016    | 72        | 3.92%   |
| 2009    | 57        | 3.1%    |
| 2007    | 56        | 3.05%   |
| 2022    | 54        | 2.94%   |
| 2006    | 19        | 1.03%   |
| 2023    | 10        | 0.54%   |
| Unknown | 9         | 0.49%   |
| 2005    | 5         | 0.27%   |
| 2004    | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1187      | 64.58%  |
| Desktop        | 564       | 30.69%  |
| All in one     | 24        | 1.31%   |
| Convertible    | 18        | 0.98%   |
| Mini pc        | 18        | 0.98%   |
| System on chip | 9         | 0.49%   |
| Tablet         | 9         | 0.49%   |
| Server         | 9         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1755      | 94.86%  |
| Enabled  | 95        | 5.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1836      | 99.89%  |
| Yes  | 2         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 494       | 26.36%  |
| 4.01-8.0        | 439       | 23.43%  |
| 8.01-16.0       | 332       | 17.72%  |
| 16.01-24.0      | 305       | 16.28%  |
| 32.01-64.0      | 132       | 7.04%   |
| 1.01-2.0        | 76        | 4.06%   |
| 64.01-256.0     | 42        | 2.24%   |
| 24.01-32.0      | 20        | 1.07%   |
| 2.01-3.0        | 17        | 0.91%   |
| 0.51-1.0        | 15        | 0.8%    |
| More than 256.0 | 2         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 759       | 36.99%  |
| 2.01-3.0    | 525       | 25.58%  |
| 3.01-4.0    | 240       | 11.7%   |
| 4.01-8.0    | 210       | 10.23%  |
| 0.51-1.0    | 196       | 9.55%   |
| 8.01-16.0   | 66        | 3.22%   |
| 0.01-0.5    | 44        | 2.14%   |
| 16.01-24.0  | 5         | 0.24%   |
| 32.01-64.0  | 3         | 0.15%   |
| 24.01-32.0  | 2         | 0.1%    |
| 64.01-256.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1229      | 64.85%  |
| 2      | 429       | 22.64%  |
| 3      | 122       | 6.44%   |
| 4      | 50        | 2.64%   |
| 5      | 27        | 1.42%   |
| 0      | 14        | 0.74%   |
| 6      | 8         | 0.42%   |
| 9      | 4         | 0.21%   |
| 7      | 4         | 0.21%   |
| 8      | 3         | 0.16%   |
| 24     | 1         | 0.05%   |
| 15     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1149      | 62.04%  |
| Yes       | 703       | 37.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1518      | 82.5%   |
| No        | 322       | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1419      | 76.7%   |
| No        | 431       | 23.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1149      | 61.77%  |
| No        | 711       | 38.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1838      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 587       | 30.03%  |
| Cluj-Napoca           | 131       | 6.7%    |
| Iasi                  | 90        | 4.6%    |
| Timișoara            | 73        | 3.73%   |
| Brasov                | 58        | 2.97%   |
| Târgu Mureş         | 57        | 2.92%   |
| Ploieşti             | 46        | 2.35%   |
| Constanța            | 38        | 1.94%   |
| Sibiu                 | 37        | 1.89%   |
| Oradea                | 34        | 1.74%   |
| Arad                  | 31        | 1.59%   |
| Piteşti              | 30        | 1.53%   |
| Craiova               | 25        | 1.28%   |
| Baia Mare             | 23        | 1.18%   |
| Popesti-Leordeni      | 21        | 1.07%   |
| Galati                | 20        | 1.02%   |
| Zalău                | 19        | 0.97%   |
| Voluntari             | 18        | 0.92%   |
| Râmnicu Vâlcea      | 17        | 0.87%   |
| Bacau                 | 16        | 0.82%   |
| Targoviste            | 14        | 0.72%   |
| Satu Mare             | 14        | 0.72%   |
| Miercurea-Ciuc        | 14        | 0.72%   |
| Botosani              | 14        | 0.72%   |
| Piatra Neamţ         | 13        | 0.66%   |
| Reşiţa              | 12        | 0.61%   |
| Floresti              | 12        | 0.61%   |
| Tulcea                | 11        | 0.56%   |
| Focşani              | 11        | 0.56%   |
| Braila                | 11        | 0.56%   |
| Alba Iulia            | 11        | 0.56%   |
| Drobeta-Turnu Severin | 10        | 0.51%   |
| Deva                  | 10        | 0.51%   |
| Târgu Jiu            | 9         | 0.46%   |
| Mediaş               | 9         | 0.46%   |
| Suceava               | 8         | 0.41%   |
| Sfantu Gheorghe       | 8         | 0.41%   |
| Buzau                 | 8         | 0.41%   |
| Beiuș                | 8         | 0.41%   |
| Alexandria            | 8         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 389       | 569    | 14.92%  |
| Seagate                     | 383       | 594    | 14.69%  |
| Samsung Electronics         | 347       | 476    | 13.31%  |
| Kingston                    | 304       | 418    | 11.66%  |
| Toshiba                     | 171       | 215    | 6.56%   |
| Unknown                     | 99        | 128    | 3.8%    |
| SanDisk                     | 99        | 120    | 3.8%    |
| A-DATA Technology           | 96        | 119    | 3.68%   |
| Intel                       | 87        | 109    | 3.34%   |
| SK hynix                    | 75        | 100    | 2.88%   |
| Hitachi                     | 68        | 87     | 2.61%   |
| HGST                        | 61        | 79     | 2.34%   |
| Micron Technology           | 48        | 61     | 1.84%   |
| Crucial                     | 37        | 48     | 1.42%   |
| Patriot                     | 22        | 26     | 0.84%   |
| Kingston Technology Company | 19        | 21     | 0.73%   |
| Maxtor                      | 17        | 24     | 0.65%   |
| Phison                      | 16        | 19     | 0.61%   |
| SPCC                        | 15        | 18     | 0.58%   |
| KIOXIA                      | 15        | 15     | 0.58%   |
| Hewlett-Packard             | 15        | 17     | 0.58%   |
| OCZ                         | 11        | 21     | 0.42%   |
| XPG                         | 9         | 13     | 0.35%   |
| FORESEE                     | 9         | 10     | 0.35%   |
| Corsair                     | 9         | 17     | 0.35%   |
| Transcend                   | 8         | 10     | 0.31%   |
| Silicon Motion              | 8         | 10     | 0.31%   |
| Gigabyte Technology         | 8         | 11     | 0.31%   |
| Realtek Semiconductor       | 7         | 8      | 0.27%   |
| Phison Electronics          | 7         | 8      | 0.27%   |
| Netac                       | 7         | 9      | 0.27%   |
| Kingmax                     | 7         | 8      | 0.27%   |
| Fujitsu                     | 7         | 8      | 0.27%   |
| China                       | 7         | 7      | 0.27%   |
| Apple                       | 7         | 10     | 0.27%   |
| Team                        | 6         | 6      | 0.23%   |
| Plextor                     | 6         | 7      | 0.23%   |
| GOODRAM                     | 6         | 6      | 0.23%   |
| ASMT                        | 6         | 6      | 0.23%   |
| Verbatim                    | 4         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 71        | 2.53%   |
| Seagate ST1000LM035-1RK172 1TB                     | 46        | 1.64%   |
| Toshiba MQ01ABF050 500GB                           | 45        | 1.6%    |
| Kingston SA400S37480G 480GB SSD                    | 35        | 1.25%   |
| Seagate ST500LT012-1DG142 500GB                    | 30        | 1.07%   |
| Kingston SA400S37120G 120GB SSD                    | 30        | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB                     | 26        | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                   | 24        | 0.85%   |
| Unknown MMC Card  32GB                             | 22        | 0.78%   |
| Toshiba MQ04ABF100 1TB                             | 22        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                       | 21        | 0.75%   |
| HGST HTS721010A9E630 1TB                           | 20        | 0.71%   |
| Samsung SSD 860 EVO 500GB                          | 19        | 0.68%   |
| Samsung SSD 850 EVO 250GB                          | 19        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 18        | 0.64%   |
| SanDisk NVMe SSD Drive 256GB                       | 18        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 18        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                       | 17        | 0.61%   |
| A-DATA SU650 240GB SSD                             | 16        | 0.57%   |
| Seagate ST500DM002-1BD142 500GB                    | 15        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 15        | 0.53%   |
| Kingston SV300S37A240G 240GB SSD                   | 15        | 0.53%   |
| Toshiba MQ01ABD100 1TB                             | 14        | 0.5%    |
| Seagate Expansion 1TB                              | 14        | 0.5%    |
| Kingston SUV400S37120G 120GB SSD                   | 13        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                      | 12        | 0.43%   |
| Samsung SSD 860 EVO 250GB                          | 12        | 0.43%   |
| Patriot Burst 120GB SSD                            | 12        | 0.43%   |
| Intel NVMe SSD Drive 512GB                         | 12        | 0.43%   |
| Toshiba DT01ACA050 500GB                           | 11        | 0.39%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 11        | 0.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 11        | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 11        | 0.39%   |
| HGST HTS545050A7E680 500GB                         | 11        | 0.39%   |
| WDC WD1600AAJS-22L7A0 160GB                        | 10        | 0.36%   |
| Unknown MMC Card  64GB                             | 10        | 0.36%   |
| HGST HTS541010A9E680 1TB                           | 10        | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 9         | 0.32%   |
| Unknown SD/MMC/MS PRO 16GB                         | 9         | 0.32%   |
| Unknown MMC Card  128GB                            | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 377       | 584    | 35.77%  |
| WDC                 | 322       | 486    | 30.55%  |
| Toshiba             | 145       | 182    | 13.76%  |
| Hitachi             | 68        | 87     | 6.45%   |
| HGST                | 61        | 79     | 5.79%   |
| Samsung Electronics | 34        | 42     | 3.23%   |
| Maxtor              | 16        | 23     | 1.52%   |
| Unknown             | 9         | 10     | 0.85%   |
| Fujitsu             | 7         | 8      | 0.66%   |
| Apple               | 3         | 4      | 0.28%   |
| LaCie               | 2         | 8      | 0.19%   |
| IBM/Hitachi         | 2         | 2      | 0.19%   |
| Hewlett-Packard     | 2         | 3      | 0.19%   |
| Intenso             | 1         | 1      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| ASMT109x            | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 265       | 357    | 30.67%  |
| Samsung Electronics | 142       | 195    | 16.44%  |
| A-DATA Technology   | 89        | 112    | 10.3%   |
| SanDisk             | 43        | 57     | 4.98%   |
| Crucial             | 33        | 44     | 3.82%   |
| WDC                 | 30        | 34     | 3.47%   |
| Intel               | 29        | 32     | 3.36%   |
| SK hynix            | 24        | 33     | 2.78%   |
| Patriot             | 21        | 25     | 2.43%   |
| Micron Technology   | 19        | 23     | 2.2%    |
| SPCC                | 15        | 18     | 1.74%   |
| OCZ                 | 11        | 21     | 1.27%   |
| Toshiba             | 10        | 11     | 1.16%   |
| Hewlett-Packard     | 10        | 10     | 1.16%   |
| FORESEE             | 9         | 10     | 1.04%   |
| Transcend           | 7         | 9      | 0.81%   |
| Netac               | 7         | 9      | 0.81%   |
| Kingmax             | 7         | 8      | 0.81%   |
| Gigabyte Technology | 7         | 10     | 0.81%   |
| Corsair             | 7         | 14     | 0.81%   |
| China               | 7         | 7      | 0.81%   |
| Team                | 6         | 6      | 0.69%   |
| GOODRAM             | 6         | 6      | 0.69%   |
| ASMT                | 5         | 5      | 0.58%   |
| Verbatim            | 4         | 6      | 0.46%   |
| Emtec               | 4         | 4      | 0.46%   |
| Apacer              | 4         | 5      | 0.46%   |
| TO Exter            | 3         | 6      | 0.35%   |
| PNY                 | 3         | 4      | 0.35%   |
| LITEON              | 3         | 3      | 0.35%   |
| Teclast             | 2         | 2      | 0.23%   |
| Seagate             | 2         | 2      | 0.23%   |
| MicroFrom           | 2         | 2      | 0.23%   |
| LITEONIT            | 2         | 2      | 0.23%   |
| Lite-On             | 2         | 2      | 0.23%   |
| Intenso             | 2         | 2      | 0.23%   |
| Apple               | 2         | 3      | 0.23%   |
| Wibtek              | 1         | 1      | 0.12%   |
| W800S               | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 911       | 1524   | 38.85%  |
| SSD     | 768       | 1124   | 32.75%  |
| NVMe    | 563       | 774    | 24.01%  |
| MMC     | 84        | 109    | 3.58%   |
| Unknown | 19        | 24     | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1359      | 2544   | 64.99%  |
| NVMe | 562       | 773    | 26.88%  |
| SAS  | 86        | 129    | 4.11%   |
| MMC  | 84        | 109    | 4.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1060      | 1688   | 63.1%   |
| 0.51-1.0   | 465       | 646    | 27.68%  |
| 1.01-2.0   | 91        | 146    | 5.42%   |
| 3.01-4.0   | 24        | 46     | 1.43%   |
| 2.01-3.0   | 19        | 59     | 1.13%   |
| 4.01-10.0  | 18        | 58     | 1.07%   |
| 10.01-20.0 | 3         | 5      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 545       | 27.79%  |
| 251-500        | 424       | 21.62%  |
| 501-1000       | 307       | 15.66%  |
| 1-20           | 186       | 9.48%   |
| 51-100         | 135       | 6.88%   |
| 1001-2000      | 107       | 5.46%   |
| 21-50          | 82        | 4.18%   |
| Unknown        | 79        | 4.03%   |
| More than 3000 | 52        | 2.65%   |
| 2001-3000      | 44        | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 806       | 39.94%  |
| 21-50          | 405       | 20.07%  |
| 101-250        | 220       | 10.9%   |
| 51-100         | 210       | 10.41%  |
| 251-500        | 123       | 6.1%    |
| 501-1000       | 95        | 4.71%   |
| Unknown        | 79        | 3.91%   |
| 1001-2000      | 52        | 2.58%   |
| More than 3000 | 19        | 0.94%   |
| 2001-3000      | 9         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB        | 7         | 7      | 3.18%   |
| HGST HTS541010A9E680 1TB             | 5         | 5      | 2.27%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 1.82%   |
| WDC WD5000AAKX-001CA0 500GB          | 3         | 3      | 1.36%   |
| WDC WD3200AAJS-60Z0A0 320GB          | 3         | 6      | 1.36%   |
| Seagate ST9500420AS 500GB            | 3         | 3      | 1.36%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 3      | 1.36%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 1.36%   |
| Maxtor STM3250310AS 250GB            | 3         | 4      | 1.36%   |
| HGST HTS725050A7E630 500GB           | 3         | 4      | 1.36%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 2      | 0.91%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 2      | 0.91%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 2         | 2      | 0.91%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 0.91%   |
| Seagate STM3250318AS 250GB           | 2         | 3      | 0.91%   |
| Seagate ST95005620AS 500GB           | 2         | 5      | 0.91%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.91%   |
| Seagate ST9160821AS 160GB            | 2         | 2      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 0.91%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 2      | 0.91%   |
| Seagate ST3500320AS 500GB            | 2         | 3      | 0.91%   |
| Seagate ST3250318AS 250GB            | 2         | 3      | 0.91%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 2      | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 0.91%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 3      | 0.91%   |
| OCZ ARC100 240GB SSD                 | 2         | 2      | 0.91%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 0.91%   |
| Hitachi HTS725032A9A364 320GB        | 2         | 2      | 0.91%   |
| Hitachi HTS545016B9A300 160GB        | 2         | 2      | 0.91%   |
| Hitachi HDS721616PLA380 164GB        | 2         | 2      | 0.91%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 3      | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1      | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 1      | 0.45%   |
| WDC WD7500BPVT-60HXZT3 752GB         | 1         | 2      | 0.45%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 1      | 0.45%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.45%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 2      | 0.45%   |
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 69     | 25.59%  |
| WDC                 | 50        | 76     | 23.7%   |
| Hitachi             | 24        | 27     | 11.37%  |
| Samsung Electronics | 15        | 17     | 7.11%   |
| HGST                | 15        | 16     | 7.11%   |
| Toshiba             | 11        | 12     | 5.21%   |
| Maxtor              | 7         | 9      | 3.32%   |
| Kingston            | 7         | 9      | 3.32%   |
| SK hynix            | 5         | 5      | 2.37%   |
| Intel               | 3         | 3      | 1.42%   |
| Hewlett-Packard     | 3         | 3      | 1.42%   |
| Patriot             | 2         | 2      | 0.95%   |
| OCZ                 | 2         | 2      | 0.95%   |
| Fujitsu             | 2         | 2      | 0.95%   |
| Apacer              | 2         | 3      | 0.95%   |
| A-DATA Technology   | 2         | 2      | 0.95%   |
| Teclast             | 1         | 1      | 0.47%   |
| SanDisk             | 1         | 1      | 0.47%   |
| Plextor             | 1         | 1      | 0.47%   |
| Micron Technology   | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| Crucial             | 1         | 1      | 0.47%   |
| Corsair             | 1         | 7      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 69     | 31.58%  |
| WDC                 | 46        | 72     | 26.9%   |
| Hitachi             | 24        | 27     | 14.04%  |
| HGST                | 15        | 16     | 8.77%   |
| Samsung Electronics | 12        | 14     | 7.02%   |
| Toshiba             | 11        | 12     | 6.43%   |
| Maxtor              | 7         | 9      | 4.09%   |
| Fujitsu             | 2         | 2      | 1.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 159       | 221    | 79.9%   |
| SSD  | 39        | 48     | 19.6%   |
| NVMe | 1         | 1      | 0.5%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1150      | 2102   | 57.02%  |
| Works    | 674       | 1180   | 33.42%  |
| Malfunc  | 190       | 270    | 9.42%   |
| Failed   | 3         | 3      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1331      | 58.02%  |
| AMD                              | 306       | 13.34%  |
| Samsung Electronics              | 194       | 8.46%   |
| SanDisk                          | 95        | 4.14%   |
| Kingston Technology Company      | 64        | 2.79%   |
| SK hynix                         | 50        | 2.18%   |
| Micron Technology                | 29        | 1.26%   |
| ASMedia Technology               | 26        | 1.13%   |
| Phison Electronics               | 23        | 1%      |
| ADATA Technology                 | 20        | 0.87%   |
| Toshiba America Info Systems     | 17        | 0.74%   |
| Marvell Technology Group         | 17        | 0.74%   |
| KIOXIA                           | 17        | 0.74%   |
| Nvidia                           | 16        | 0.7%    |
| JMicron Technology               | 15        | 0.65%   |
| Silicon Motion                   | 13        | 0.57%   |
| Realtek Semiconductor            | 13        | 0.57%   |
| Lite-On Technology               | 6         | 0.26%   |
| Silicon Integrated Systems [SiS] | 5         | 0.22%   |
| Micron/Crucial Technology        | 5         | 0.22%   |
| Broadcom / LSI                   | 5         | 0.22%   |
| VIA Technologies                 | 4         | 0.17%   |
| Silicon Image                    | 4         | 0.17%   |
| LSI Logic / Symbios Logic        | 4         | 0.17%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Solidigm                         | 2         | 0.09%   |
| Solid State Storage Technology   | 2         | 0.09%   |
| Seagate Technology               | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 224       | 8.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 117       | 4.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 93        | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 82        | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 82        | 3.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 72        | 2.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 67        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 50        | 1.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 49        | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 49        | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 48        | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 39        | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 38        | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 34        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 34        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 30        | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 29        | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 29        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 29        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 28        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 27        | 1.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 27        | 1.03%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 27        | 1.03%   |
| Intel SSD 660P Series                                                          | 26        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 0.91%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 24        | 0.91%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 23        | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 23        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 23        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 22        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 22        | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1365      | 57.81%  |
| NVMe | 571       | 24.18%  |
| IDE  | 237       | 10.04%  |
| RAID | 180       | 7.62%   |
| SAS  | 8         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1437      | 78.18%  |
| AMD    | 391       | 21.27%  |
| ARM    | 10        | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 43        | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 1.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 1.3%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 20        | 1.09%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 19        | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.81%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 15        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 12        | 0.65%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 0.65%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 12        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.54%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.54%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.54%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.49%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.49%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.49%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.43%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 8         | 0.43%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.43%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 345       | 18.75%  |
| Intel Core i5           | 344       | 18.7%   |
| Intel Core i3           | 190       | 10.33%  |
| Intel Celeron           | 153       | 8.32%   |
| Other                   | 114       | 6.2%    |
| AMD Ryzen 5             | 96        | 5.22%   |
| Intel Core 2 Duo        | 90        | 4.89%   |
| AMD Ryzen 7             | 84        | 4.57%   |
| Intel Pentium           | 59        | 3.21%   |
| AMD Ryzen 3             | 32        | 1.74%   |
| Intel Xeon              | 28        | 1.52%   |
| Intel Atom              | 28        | 1.52%   |
| AMD Ryzen 9             | 26        | 1.41%   |
| Intel Pentium Dual-Core | 21        | 1.14%   |
| AMD A4                  | 18        | 0.98%   |
| Intel Core 2 Quad       | 17        | 0.92%   |
| AMD FX                  | 16        | 0.87%   |
| Intel Core i9           | 15        | 0.82%   |
| Intel Core 2            | 14        | 0.76%   |
| AMD A8                  | 13        | 0.71%   |
| Intel Genuine           | 10        | 0.54%   |
| Intel Pentium Dual      | 9         | 0.49%   |
| AMD Phenom II X4        | 8         | 0.43%   |
| AMD Ryzen Threadripper  | 6         | 0.33%   |
| AMD Ryzen 7 PRO         | 6         | 0.33%   |
| AMD E                   | 6         | 0.33%   |
| AMD Athlon              | 6         | 0.33%   |
| Intel Pentium Silver    | 5         | 0.27%   |
| AMD E2                  | 5         | 0.27%   |
| AMD A6                  | 5         | 0.27%   |
| Intel Celeron M         | 4         | 0.22%   |
| ARM BCM                 | 4         | 0.22%   |
| AMD Sempron             | 4         | 0.22%   |
| AMD Athlon II X4        | 4         | 0.22%   |
| AMD A10                 | 4         | 0.22%   |
| AMD Turion 64 X2 Mobile | 3         | 0.16%   |
| AMD Athlon II X3        | 3         | 0.16%   |
| AMD Athlon 64 X2        | 3         | 0.16%   |
| Intel Pentium Gold      | 2         | 0.11%   |
| Intel Pentium D         | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 800       | 43.5%   |
| 4       | 648       | 35.24%  |
| 6       | 145       | 7.88%   |
| 8       | 130       | 7.07%   |
| 1       | 42        | 2.28%   |
| 12      | 24        | 1.31%   |
| 10      | 12        | 0.65%   |
| 16      | 10        | 0.54%   |
| 3       | 10        | 0.54%   |
| 14      | 7         | 0.38%   |
| 32      | 4         | 0.22%   |
| 24      | 3         | 0.16%   |
| 64      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1822      | 99.13%  |
| 2       | 15        | 0.82%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1183      | 64.33%  |
| 1       | 653       | 35.51%  |
| 4       | 2         | 0.11%   |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1742      | 94.42%  |
| Unknown        | 89        | 4.82%   |
| 32-bit         | 14        | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 440       | 23.13%  |
| 0x206a7    | 89        | 4.68%   |
| 0x306c3    | 87        | 4.57%   |
| 0x306a9    | 80        | 4.21%   |
| 0x1067a    | 62        | 3.26%   |
| 0x806ea    | 61        | 3.21%   |
| 0x906ea    | 57        | 3%      |
| 0x806ec    | 55        | 2.89%   |
| 0x706a1    | 51        | 2.68%   |
| 0x906e9    | 45        | 2.37%   |
| 0x40651    | 38        | 2%      |
| 0x806c1    | 35        | 1.84%   |
| 0x506e3    | 35        | 1.84%   |
| 0x506c9    | 34        | 1.79%   |
| 0x806e9    | 33        | 1.74%   |
| 0x20655    | 32        | 1.68%   |
| 0x306d4    | 29        | 1.52%   |
| 0x10676    | 25        | 1.31%   |
| 0x806eb    | 24        | 1.26%   |
| 0x406e3    | 24        | 1.26%   |
| 0x0a50000c | 24        | 1.26%   |
| 0x08108109 | 22        | 1.16%   |
| 0x6fd      | 20        | 1.05%   |
| 0x010000c8 | 20        | 1.05%   |
| 0x706e5    | 19        | 1%      |
| 0x406c4    | 19        | 1%      |
| 0x08108102 | 17        | 0.89%   |
| 0xa0652    | 13        | 0.68%   |
| 0x08701021 | 13        | 0.68%   |
| 0x08600106 | 13        | 0.68%   |
| 0x08600104 | 13        | 0.68%   |
| 0x0810100b | 13        | 0.68%   |
| 0x906ed    | 12        | 0.63%   |
| 0x6fb      | 12        | 0.63%   |
| 0x06001119 | 12        | 0.63%   |
| 0x706a8    | 11        | 0.58%   |
| 0x406c3    | 11        | 0.58%   |
| 0x08701013 | 10        | 0.53%   |
| 0x0800820d | 10        | 0.53%   |
| 0x806d1    | 9         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 360       | 19.53%  |
| Haswell          | 164       | 8.9%    |
| SandyBridge      | 112       | 6.08%   |
| Penryn           | 104       | 5.64%   |
| IvyBridge        | 101       | 5.48%   |
| Skylake          | 77        | 4.18%   |
| Zen 2            | 74        | 4.02%   |
| Goldmont plus    | 72        | 3.91%   |
| Zen+             | 65        | 3.53%   |
| Core             | 61        | 3.31%   |
| Unknown          | 60        | 3.26%   |
| Westmere         | 56        | 3.04%   |
| Zen 3            | 53        | 2.88%   |
| Silvermont       | 53        | 2.88%   |
| TigerLake        | 50        | 2.71%   |
| Broadwell        | 42        | 2.28%   |
| Zen              | 40        | 2.17%   |
| Goldmont         | 39        | 2.12%   |
| CometLake        | 36        | 1.95%   |
| IceLake          | 33        | 1.79%   |
| K10              | 30        | 1.63%   |
| Piledriver       | 29        | 1.57%   |
| Alderlake Hybrid | 23        | 1.25%   |
| Excavator        | 20        | 1.09%   |
| K8 Hammer        | 13        | 0.71%   |
| P6               | 12        | 0.65%   |
| Nehalem          | 11        | 0.6%    |
| Bonnell          | 11        | 0.6%    |
| Bobcat           | 8         | 0.43%   |
| Puma             | 7         | 0.38%   |
| NetBurst         | 6         | 0.33%   |
| K10 Llano        | 5         | 0.27%   |
| Tremont          | 4         | 0.22%   |
| K8 & K10 hybrid  | 4         | 0.22%   |
| Jaguar           | 4         | 0.22%   |
| Steamroller      | 3         | 0.16%   |
| Bulldozer        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1161      | 51.44%  |
| Nvidia                           | 616       | 27.29%  |
| AMD                              | 464       | 20.56%  |
| Matrox Electronics Systems       | 6         | 0.27%   |
| Silicon Integrated Systems [SiS] | 5         | 0.22%   |
| ASPEED Technology                | 4         | 0.18%   |
| VIA Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84        | 3.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 2.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 2.8%    |
| Intel UHD Graphics 620                                                                   | 62        | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 57        | 2.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 47        | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 45        | 1.94%   |
| Intel HD Graphics 620                                                                    | 43        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 1.77%   |
| Intel HD Graphics 630                                                                    | 40        | 1.73%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 36        | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 1.42%   |
| Intel HD Graphics 530                                                                    | 31        | 1.34%   |
| Intel HD Graphics 500                                                                    | 28        | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 25        | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 22        | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.73%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 16        | 0.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.65%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 773       | 41.92%  |
| 1 x AMD        | 331       | 17.95%  |
| Intel + Nvidia | 306       | 16.59%  |
| 1 x Nvidia     | 263       | 14.26%  |
| Intel + AMD    | 60        | 3.25%   |
| AMD + Nvidia   | 46        | 2.49%   |
| 2 x AMD        | 26        | 1.41%   |
| 2 x Intel      | 11        | 0.6%    |
| Other          | 10        | 0.54%   |
| 1 x Matrox     | 6         | 0.33%   |
| 1 x SiS        | 5         | 0.27%   |
| 1 x ASPEED     | 3         | 0.16%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 1 x VIA        | 1         | 0.05%   |
| AMD + ASPEED   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1454      | 78.21%  |
| Proprietary | 352       | 18.93%  |
| Unknown     | 53        | 2.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1062      | 55.95%  |
| 1.01-2.0   | 256       | 13.49%  |
| 0.01-0.5   | 198       | 10.43%  |
| 3.01-4.0   | 133       | 7.01%   |
| 0.51-1.0   | 121       | 6.38%   |
| 7.01-8.0   | 62        | 3.27%   |
| 5.01-6.0   | 37        | 1.95%   |
| 8.01-16.0  | 12        | 0.63%   |
| 2.01-3.0   | 11        | 0.58%   |
| 16.01-24.0 | 5         | 0.26%   |
| 0          | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 241       | 12.37%  |
| Samsung Electronics     | 238       | 12.21%  |
| Chimei Innolux          | 216       | 11.08%  |
| BOE                     | 209       | 10.72%  |
| LG Display              | 187       | 9.59%   |
| Dell                    | 134       | 6.88%   |
| Goldstar                | 101       | 5.18%   |
| Philips                 | 68        | 3.49%   |
| PANDA                   | 51        | 2.62%   |
| BenQ                    | 45        | 2.31%   |
| Lenovo                  | 39        | 2%      |
| Chi Mei Optoelectronics | 35        | 1.8%    |
| Hewlett-Packard         | 33        | 1.69%   |
| AOC                     | 33        | 1.69%   |
| Ancor Communications    | 32        | 1.64%   |
| Acer                    | 32        | 1.64%   |
| Sharp                   | 29        | 1.49%   |
| Fujitsu Siemens         | 21        | 1.08%   |
| ASUSTek Computer        | 18        | 0.92%   |
| LG Philips              | 14        | 0.72%   |
| LG Electronics          | 12        | 0.62%   |
| Unknown                 | 10        | 0.51%   |
| Eizo                    | 10        | 0.51%   |
| Apple                   | 10        | 0.51%   |
| Sony                    | 9         | 0.46%   |
| InfoVision              | 8         | 0.41%   |
| CSO                     | 8         | 0.41%   |
| KTC                     | 7         | 0.36%   |
| Vestel Elektronik       | 6         | 0.31%   |
| Lenovo Group Limited    | 6         | 0.31%   |
| ViewSonic               | 5         | 0.26%   |
| Toshiba                 | 5         | 0.26%   |
| Panasonic               | 5         | 0.26%   |
| LGD                     | 4         | 0.21%   |
| Iiyama                  | 4         | 0.21%   |
| HannStar                | 4         | 0.21%   |
| CPT                     | 4         | 0.21%   |
| Valve                   | 3         | 0.15%   |
| InnoLux Display         | 3         | 0.15%   |
| Belinea                 | 3         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 25        | 1.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 22        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.8%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 14        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 11        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.5%    |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                     | 10        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.45%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 9         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 9         | 0.45%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 8         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.4%    |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 8         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.4%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 7         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.35%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.35%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 6         | 0.3%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 6         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.3%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 6         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.3%    |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 877       | 46.9%   |
| 1366x768 (WXGA)    | 399       | 21.34%  |
| 3840x2160 (4K)     | 78        | 4.17%   |
| 1280x1024 (SXGA)   | 76        | 4.06%   |
| 2560x1440 (QHD)    | 62        | 3.32%   |
| 1600x900 (HD+)     | 59        | 3.16%   |
| 1680x1050 (WSXGA+) | 48        | 2.57%   |
| 1280x800 (WXGA)    | 40        | 2.14%   |
| 1920x1200 (WUXGA)  | 35        | 1.87%   |
| 1440x900 (WXGA+)   | 28        | 1.5%    |
| Unknown            | 21        | 1.12%   |
| 1360x768           | 15        | 0.8%    |
| 2880x1800          | 14        | 0.75%   |
| 2560x1080          | 13        | 0.7%    |
| 3440x1440          | 11        | 0.59%   |
| 3200x1800 (QHD+)   | 11        | 0.59%   |
| 2560x1600          | 11        | 0.59%   |
| 1024x600           | 8         | 0.43%   |
| 3840x1080          | 7         | 0.37%   |
| 1024x768 (XGA)     | 7         | 0.37%   |
| 800x1280           | 6         | 0.32%   |
| 2160x1440          | 6         | 0.32%   |
| 1600x1200          | 3         | 0.16%   |
| 5760x2160          | 2         | 0.11%   |
| 5120x1440          | 2         | 0.11%   |
| 3840x2400          | 2         | 0.11%   |
| 3840x1600          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.11%   |
| 800x600            | 1         | 0.05%   |
| 7680x1440          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |
| 6000x1440          | 1         | 0.05%   |
| 4960x1080          | 1         | 0.05%   |
| 3926x1440          | 1         | 0.05%   |
| 3840x2524          | 1         | 0.05%   |
| 3600x1200          | 1         | 0.05%   |
| 3360x1080          | 1         | 0.05%   |
| 3286x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 730       | 37.78%  |
| 14      | 135       | 6.99%   |
| 24      | 131       | 6.78%   |
| 13      | 125       | 6.47%   |
| 17      | 117       | 6.06%   |
| 21      | 111       | 5.75%   |
| 23      | 102       | 5.28%   |
| 27      | 94        | 4.87%   |
| Unknown | 77        | 3.99%   |
| 19      | 54        | 2.8%    |
| 22      | 33        | 1.71%   |
| 18      | 27        | 1.4%    |
| 31      | 26        | 1.35%   |
| 34      | 22        | 1.14%   |
| 12      | 18        | 0.93%   |
| 84      | 15        | 0.78%   |
| 16      | 15        | 0.78%   |
| 20      | 13        | 0.67%   |
| 54      | 11        | 0.57%   |
| 11      | 10        | 0.52%   |
| 10      | 9         | 0.47%   |
| 40      | 7         | 0.36%   |
| 72      | 6         | 0.31%   |
| 65      | 6         | 0.31%   |
| 32      | 6         | 0.31%   |
| 28      | 3         | 0.16%   |
| 26      | 3         | 0.16%   |
| 7       | 3         | 0.16%   |
| 3       | 3         | 0.16%   |
| 52      | 2         | 0.1%    |
| 46      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| 29      | 2         | 0.1%    |
| 25      | 2         | 0.1%    |
| 8       | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 86      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 958       | 50.16%  |
| 501-600        | 305       | 15.97%  |
| 401-500        | 194       | 10.16%  |
| 351-400        | 153       | 8.01%   |
| 201-300        | 90        | 4.71%   |
| Unknown        | 77        | 4.03%   |
| 601-700        | 38        | 1.99%   |
| 701-800        | 28        | 1.47%   |
| 1001-1500      | 25        | 1.31%   |
| 1501-2000      | 21        | 1.1%    |
| 801-900        | 9         | 0.47%   |
| 1-100          | 6         | 0.31%   |
| 901-1000       | 3         | 0.16%   |
| 101-200        | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1414      | 79.04%  |
| 16/10   | 175       | 9.78%   |
| 5/4     | 68        | 3.8%    |
| Unknown | 67        | 3.75%   |
| 21/9    | 25        | 1.4%    |
| 4/3     | 14        | 0.78%   |
| 3/2     | 12        | 0.67%   |
| 6/5     | 8         | 0.45%   |
| 0.67    | 3         | 0.17%   |
| 32/9    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 731       | 38.05%  |
| 201-250        | 305       | 15.88%  |
| 81-90          | 216       | 11.24%  |
| 151-200        | 97        | 5.05%   |
| 301-350        | 96        | 5%      |
| 121-130        | 84        | 4.37%   |
| Unknown        | 77        | 4.01%   |
| 351-500        | 56        | 2.92%   |
| 141-150        | 46        | 2.39%   |
| 251-300        | 45        | 2.34%   |
| More than 1000 | 44        | 2.29%   |
| 71-80          | 41        | 2.13%   |
| 61-70          | 16        | 0.83%   |
| 501-1000       | 15        | 0.78%   |
| 51-60          | 10        | 0.52%   |
| 131-140        | 10        | 0.52%   |
| 111-120        | 10        | 0.52%   |
| 41-50          | 9         | 0.47%   |
| 1-40           | 8         | 0.42%   |
| 91-100         | 5         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 576       | 30.38%  |
| 101-120       | 549       | 28.96%  |
| 51-100        | 539       | 28.43%  |
| 161-240       | 79        | 4.17%   |
| Unknown       | 77        | 4.06%   |
| More than 240 | 40        | 2.11%   |
| 1-50          | 36        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1574      | 83.99%  |
| 2     | 209       | 11.15%  |
| 0     | 64        | 3.42%   |
| 3     | 26        | 1.39%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1055      | 39.2%   |
| Intel                             | 805       | 29.91%  |
| Qualcomm Atheros                  | 314       | 11.67%  |
| Broadcom                          | 141       | 5.24%   |
| TP-Link                           | 58        | 2.16%   |
| MediaTek                          | 57        | 2.12%   |
| Broadcom Limited                  | 28        | 1.04%   |
| Ralink                            | 24        | 0.89%   |
| Marvell Technology Group          | 23        | 0.85%   |
| Ralink Technology                 | 22        | 0.82%   |
| Nvidia                            | 14        | 0.52%   |
| ASUSTek Computer                  | 13        | 0.48%   |
| Huawei Technologies               | 11        | 0.41%   |
| Xiaomi                            | 9         | 0.33%   |
| D-Link                            | 9         | 0.33%   |
| ASIX Electronics                  | 9         | 0.33%   |
| Samsung Electronics               | 8         | 0.3%    |
| Ericsson Business Mobile Networks | 7         | 0.26%   |
| Qualcomm Atheros Communications   | 6         | 0.22%   |
| Aquantia                          | 6         | 0.22%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.19%   |
| Microsoft                         | 5         | 0.19%   |
| Hewlett-Packard                   | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.15%   |
| Lenovo                            | 4         | 0.15%   |
| JMicron Technology                | 4         | 0.15%   |
| Google                            | 4         | 0.15%   |
| VIA Technologies                  | 3         | 0.11%   |
| Tenda                             | 2         | 0.07%   |
| Standard Microsystems             | 2         | 0.07%   |
| IMC Networks                      | 2         | 0.07%   |
| Giga-Byte Technology              | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| Edimax Technology                 | 2         | 0.07%   |
| DisplayLink                       | 2         | 0.07%   |
| Dell                              | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Belkin Components                 | 2         | 0.07%   |
| U-Blox                            | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 692       | 22.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 4.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 82        | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 75        | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66        | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 63        | 2.01%   |
| Intel Wi-Fi 6 AX200                                               | 60        | 1.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 56        | 1.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 54        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 47        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 40        | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 39        | 1.24%   |
| Intel Wi-Fi 6 AX201                                               | 36        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 36        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 0.95%   |
| Intel I211 Gigabit Network Connection                             | 30        | 0.95%   |
| Intel Wireless 7260                                               | 29        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 28        | 0.89%   |
| Intel Wireless 7265                                               | 28        | 0.89%   |
| Intel Wireless 8260                                               | 23        | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 23        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 23        | 0.73%   |
| Intel Wireless 3165                                               | 22        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 22        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 22        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.6%    |
| Intel Wireless 3160                                               | 19        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 16        | 0.51%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 14        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 601       | 40.47%  |
| Realtek Semiconductor             | 321       | 21.62%  |
| Qualcomm Atheros                  | 255       | 17.17%  |
| Broadcom                          | 92        | 6.2%    |
| MediaTek                          | 50        | 3.37%   |
| TP-Link                           | 49        | 3.3%    |
| Ralink                            | 24        | 1.62%   |
| Ralink Technology                 | 22        | 1.48%   |
| Broadcom Limited                  | 14        | 0.94%   |
| ASUSTek Computer                  | 13        | 0.88%   |
| D-Link                            | 9         | 0.61%   |
| Qualcomm Atheros Communications   | 6         | 0.4%    |
| Microsoft                         | 5         | 0.34%   |
| Ericsson Business Mobile Networks | 4         | 0.27%   |
| Tenda                             | 2         | 0.13%   |
| IMC Networks                      | 2         | 0.13%   |
| Fibocom                           | 2         | 0.13%   |
| Edimax Technology                 | 2         | 0.13%   |
| Belkin Components                 | 2         | 0.13%   |
| Sitecom Europe                    | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| Qcom                              | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Micro Star International          | 1         | 0.07%   |
| Mercucys                          | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |
| Belkin                            | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 82        | 5.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 5.03%   |
| Intel Wireless 8265 / 8275                                              | 63        | 4.22%   |
| Intel Wi-Fi 6 AX200                                                     | 60        | 4.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 56        | 3.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 47        | 3.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 36        | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 2.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 2.01%   |
| Intel Wireless 7260                                                     | 29        | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 1.88%   |
| Intel Wireless 7265                                                     | 28        | 1.88%   |
| Intel Wireless 8260                                                     | 23        | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 23        | 1.54%   |
| Intel Wireless 3165                                                     | 22        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.34%   |
| Intel Wireless 3160                                                     | 19        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.21%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 16        | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 12        | 0.8%    |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 10        | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.6%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 9         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 897       | 56.13%  |
| Intel                            | 397       | 24.84%  |
| Qualcomm Atheros                 | 92        | 5.76%   |
| Broadcom                         | 73        | 4.57%   |
| Marvell Technology Group         | 23        | 1.44%   |
| Nvidia                           | 14        | 0.88%   |
| Broadcom Limited                 | 14        | 0.88%   |
| Xiaomi                           | 9         | 0.56%   |
| TP-Link                          | 9         | 0.56%   |
| Huawei Technologies              | 9         | 0.56%   |
| ASIX Electronics                 | 9         | 0.56%   |
| Samsung Electronics              | 8         | 0.5%    |
| MediaTek                         | 7         | 0.44%   |
| Aquantia                         | 6         | 0.38%   |
| Silicon Integrated Systems [SiS] | 4         | 0.25%   |
| Lenovo                           | 4         | 0.25%   |
| JMicron Technology               | 4         | 0.25%   |
| Google                           | 4         | 0.25%   |
| VIA Technologies                 | 3         | 0.19%   |
| Standard Microsystems            | 2         | 0.13%   |
| Giga-Byte Technology             | 2         | 0.13%   |
| DisplayLink                      | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| QLogic                           | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Dell                             | 1         | 0.06%   |
| D-Link System                    | 1         | 0.06%   |
| 3Com                             | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 692       | 42.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66        | 4.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31        | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 30        | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 23        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 1.17%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.49%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 8         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 7         | 0.43%   |
| MediaTek Wiko U316AT                                              | 7         | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.43%   |
| Huawei ALP-AL00                                                   | 7         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1516      | 51.27%  |
| WiFi     | 1416      | 47.89%  |
| Modem    | 20        | 0.68%   |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1126      | 59.01%  |
| Ethernet | 781       | 40.93%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 989       | 53.69%  |
| 1     | 774       | 42.02%  |
| 0     | 37        | 2.01%   |
| 3     | 35        | 1.9%    |
| 4     | 5         | 0.27%   |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1559      | 82.93%  |
| Yes  | 321       | 17.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 481       | 41.61%  |
| IMC Networks                    | 159       | 13.75%  |
| Realtek Semiconductor           | 144       | 12.46%  |
| Qualcomm Atheros Communications | 77        | 6.66%   |
| Lite-On Technology              | 62        | 5.36%   |
| Broadcom                        | 41        | 3.55%   |
| Cambridge Silicon Radio         | 36        | 3.11%   |
| Foxconn / Hon Hai               | 29        | 2.51%   |
| ASUSTek Computer                | 29        | 2.51%   |
| Dell                            | 19        | 1.64%   |
| Hewlett-Packard                 | 15        | 1.3%    |
| Toshiba                         | 13        | 1.12%   |
| Apple                           | 11        | 0.95%   |
| Ralink                          | 9         | 0.78%   |
| MediaTek                        | 8         | 0.69%   |
| Realtek                         | 3         | 0.26%   |
| Alps Electric                   | 3         | 0.26%   |
| SINO WEALTH                     | 2         | 0.17%   |
| Integrated System Solution      | 2         | 0.17%   |
| Chicony Electronics             | 2         | 0.17%   |
| USI                             | 1         | 0.09%   |
| TP-Link                         | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Conwise Technology              | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |
| Accel Semiconductor             | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 190       | 16.44%  |
| Realtek Bluetooth Radio                             | 99        | 8.56%   |
| IMC Networks Bluetooth Radio                        | 96        | 8.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 92        | 7.96%   |
| Intel AX201 Bluetooth                               | 88        | 7.61%   |
| Intel AX200 Bluetooth                               | 58        | 5.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 43        | 3.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 36        | 3.11%   |
| IMC Networks Bluetooth Device                       | 33        | 2.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 2.25%   |
| IMC Networks Wireless_Device                        | 23        | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 1.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 19        | 1.64%   |
| Intel Bluetooth Device                              | 16        | 1.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 1.12%   |
| Lite-On Bluetooth Device                            | 12        | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.87%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 0.78%   |
| Intel AX210 Bluetooth                               | 9         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.78%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.69%   |
| MediaTek Wireless_Device                            | 8         | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.69%   |
| Lite-On Wireless_Device                             | 7         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.61%   |
| Broadcom BCM2045A0                                  | 7         | 0.61%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.61%   |
| Toshiba Bluetooth Device                            | 6         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.43%   |
| Apple Bluetooth Host Controller                     | 5         | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1388      | 57%     |
| AMD                                          | 444       | 18.23%  |
| Nvidia                                       | 396       | 16.26%  |
| C-Media Electronics                          | 38        | 1.56%   |
| Creative Labs                                | 23        | 0.94%   |
| Logitech                                     | 15        | 0.62%   |
| GN Netcom                                    | 10        | 0.41%   |
| Creative Technology                          | 9         | 0.37%   |
| ASUSTek Computer                             | 8         | 0.33%   |
| Trust                                        | 7         | 0.29%   |
| Texas Instruments                            | 6         | 0.25%   |
| Kingston Technology                          | 6         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.21%   |
| Lenovo                                       | 5         | 0.21%   |
| Giga-Byte Technology                         | 5         | 0.21%   |
| DSEA A/S                                     | 5         | 0.21%   |
| Realtek Semiconductor                        | 4         | 0.16%   |
| Razer USA                                    | 4         | 0.16%   |
| Plantronics                                  | 4         | 0.16%   |
| Generalplus Technology                       | 4         | 0.16%   |
| VIA Technologies                             | 3         | 0.12%   |
| Tenx Technology                              | 3         | 0.12%   |
| Dell                                         | 3         | 0.12%   |
| XMOS                                         | 2         | 0.08%   |
| Sennheiser Communications                    | 2         | 0.08%   |
| JMTek                                        | 2         | 0.08%   |
| GYROCOM C&C                                  | 2         | 0.08%   |
| Focusrite-Novation                           | 2         | 0.08%   |
| Edifier Technology                           | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| Audio-Technica                               | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| Unknown                                      | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| TEAC                                         | 1         | 0.04%   |
| Studiologic                                  | 1         | 0.04%   |
| Sony                                         | 1         | 0.04%   |
| Samson Technologies                          | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.04%   |
| Nam Tai E&E Products                         | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 176       | 6.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 144       | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 102       | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 99        | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 96        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 78        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 76        | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 73        | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 72        | 2.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 71        | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 61        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 58        | 2.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 55        | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 54        | 1.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 51        | 1.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 1.73%   |
| Intel 8 Series HD Audio Controller                                                                | 50        | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 45        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 43        | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 40        | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.35%   |
| AMD FCH Azalia Controller                                                                         | 38        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 37        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 36        | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 34        | 1.18%   |
| Intel 200 Series PCH HD Audio                                                                     | 34        | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 33        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 25        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.83%   |
| Intel CM238 HD Audio Controller                                                                   | 23        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 22        | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 22        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 21        | 0.73%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 258       | 24.29%  |
| SK hynix                     | 183       | 17.23%  |
| Kingston                     | 158       | 14.88%  |
| Micron Technology            | 100       | 9.42%   |
| Unknown                      | 86        | 8.1%    |
| Corsair                      | 75        | 7.06%   |
| Crucial                      | 30        | 2.82%   |
| A-DATA Technology            | 28        | 2.64%   |
| Ramaxel Technology           | 26        | 2.45%   |
| Nanya Technology             | 21        | 1.98%   |
| Elpida                       | 19        | 1.79%   |
| G.Skill                      | 16        | 1.51%   |
| Kingmax                      | 11        | 1.04%   |
| Unknown (ABCD)               | 10        | 0.94%   |
| Unknown                      | 5         | 0.47%   |
| Patriot                      | 4         | 0.38%   |
| Apacer                       | 4         | 0.38%   |
| GOODRAM                      | 3         | 0.28%   |
| Transcend                    | 2         | 0.19%   |
| Silicon Power                | 2         | 0.19%   |
| Qimonda                      | 2         | 0.19%   |
| Kingmax Semiconductor        | 2         | 0.19%   |
| Unknown (7F7F7F94FFFFFFFF)   | 1         | 0.09%   |
| Unknown (0x9801)             | 1         | 0.09%   |
| Unknown (0x7FDA000000000000) | 1         | 0.09%   |
| Unknown (0B45)               | 1         | 0.09%   |
| Team                         | 1         | 0.09%   |
| TakeMS                       | 1         | 0.09%   |
| SK_Hynix                     | 1         | 0.09%   |
| SHARETRONIC                  | 1         | 0.09%   |
| S                            | 1         | 0.09%   |
| KingFast                     | 1         | 0.09%   |
| Infineon                     | 1         | 0.09%   |
| H                            | 1         | 0.09%   |
| Exceleram                    | 1         | 0.09%   |
| Avant                        | 1         | 0.09%   |
| Atermiter                    | 1         | 0.09%   |
| ASint Technology             | 1         | 0.09%   |
| AMD                          | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 1.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 11        | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.95%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.86%   |
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR2 667MT/s            | 10        | 0.86%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.69%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 8         | 0.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.6%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 6         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.52%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s                | 6         | 0.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.43%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 5         | 0.43%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.43%   |
| Unknown                                                          | 5         | 0.43%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 4         | 0.34%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 4         | 0.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 427       | 47.13%  |
| DDR3    | 298       | 32.89%  |
| DDR2    | 64        | 7.06%   |
| SDRAM   | 31        | 3.42%   |
| LPDDR4  | 22        | 2.43%   |
| Unknown | 22        | 2.43%   |
| LPDDR3  | 17        | 1.88%   |
| DDR5    | 12        | 1.32%   |
| LPDDR5  | 7         | 0.77%   |
| DDR     | 4         | 0.44%   |
| DRAM    | 2         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 553       | 61.86%  |
| DIMM         | 292       | 32.66%  |
| Row Of Chips | 43        | 4.81%   |
| Chip         | 4         | 0.45%   |
| RIMM         | 1         | 0.11%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 359       | 36.48%  |
| 4096  | 285       | 28.96%  |
| 16384 | 135       | 13.72%  |
| 2048  | 126       | 12.8%   |
| 1024  | 51        | 5.18%   |
| 32768 | 22        | 2.24%   |
| 512   | 6         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 195       | 19.36%  |
| 3200    | 150       | 14.9%   |
| 2667    | 143       | 14.2%   |
| 2400    | 90        | 8.94%   |
| 1333    | 60        | 5.96%   |
| 2133    | 40        | 3.97%   |
| 1334    | 40        | 3.97%   |
| 667     | 36        | 3.57%   |
| 800     | 30        | 2.98%   |
| 3600    | 19        | 1.89%   |
| Unknown | 19        | 1.89%   |
| 3266    | 18        | 1.79%   |
| 3000    | 10        | 0.99%   |
| 2666    | 10        | 0.99%   |
| 1867    | 10        | 0.99%   |
| 1067    | 10        | 0.99%   |
| 975     | 9         | 0.89%   |
| 4267    | 8         | 0.79%   |
| 3400    | 8         | 0.79%   |
| 6400    | 7         | 0.7%    |
| 1866    | 7         | 0.7%    |
| 3733    | 6         | 0.6%    |
| 2933    | 6         | 0.6%    |
| 1066    | 6         | 0.6%    |
| 533     | 6         | 0.6%    |
| 4800    | 5         | 0.5%    |
| 4199    | 5         | 0.5%    |
| 2048    | 5         | 0.5%    |
| 2800    | 4         | 0.4%    |
| 1800    | 4         | 0.4%    |
| 4266    | 3         | 0.3%    |
| 3866    | 3         | 0.3%    |
| 3500    | 3         | 0.3%    |
| 400     | 3         | 0.3%    |
| 6000    | 2         | 0.2%    |
| 3466    | 2         | 0.2%    |
| 1648    | 2         | 0.2%    |
| 1639    | 2         | 0.2%    |
| 49926   | 1         | 0.1%    |
| 8192    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 24.53%  |
| Canon                 | 10        | 18.87%  |
| Samsung Electronics   | 8         | 15.09%  |
| Brother Industries    | 8         | 15.09%  |
| Seiko Epson           | 7         | 13.21%  |
| Xerox                 | 2         | 3.77%   |
| Lexmark International | 2         | 3.77%   |
| Zebra                 | 1         | 1.89%   |
| QinHeng Electronics   | 1         | 1.89%   |
| ATEN International    | 1         | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                      | 2         | 3.77%   |
| Seiko Epson ET-2710 Series                    | 2         | 3.77%   |
| Samsung M2070 Series                          | 2         | 3.77%   |
| Samsung Composite Device                      | 2         | 3.77%   |
| Lexmark International InkJet Color Printer    | 2         | 3.77%   |
| HP DeskJet 2130 series                        | 2         | 3.77%   |
| Canon MF4010 series                           | 2         | 3.77%   |
| Brother HL-1110 series                        | 2         | 3.77%   |
| Zebra GK420t Label Printer                    | 1         | 1.89%   |
| Xerox Phaser 6130N                            | 1         | 1.89%   |
| Xerox Phaser 3020                             | 1         | 1.89%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.89%   |
| Seiko Epson L6160 Series                      | 1         | 1.89%   |
| Seiko Epson ET-2600 Series                    | 1         | 1.89%   |
| Samsung ML-216x Series Laser Printer          | 1         | 1.89%   |
| Samsung M267x 287x Series                     | 1         | 1.89%   |
| Samsung M2020 Series                          | 1         | 1.89%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 1.89%   |
| QinHeng CH340S                                | 1         | 1.89%   |
| HP LaserJet M14-M17                           | 1         | 1.89%   |
| HP LaserJet 3050                              | 1         | 1.89%   |
| HP LaserJet 1022                              | 1         | 1.89%   |
| HP LaserJet 1018                              | 1         | 1.89%   |
| HP Laser 107a                                 | 1         | 1.89%   |
| HP Deskjet F4500 series                       | 1         | 1.89%   |
| HP DeskJet F2492 All-in-One                   | 1         | 1.89%   |
| HP Deskjet 3050A                              | 1         | 1.89%   |
| HP DeskJet 2700 series                        | 1         | 1.89%   |
| HP DeskJet 2300 series                        | 1         | 1.89%   |
| HP Deskjet 2050 J510                          | 1         | 1.89%   |
| Canon PIXMA MP280                             | 1         | 1.89%   |
| Canon PIXMA MP250                             | 1         | 1.89%   |
| Canon MF4320-4350                             | 1         | 1.89%   |
| Canon MF3200 series                           | 1         | 1.89%   |
| Canon MF3110                                  | 1         | 1.89%   |
| Canon LiDE 300                                | 1         | 1.89%   |
| Canon LBP2900                                 | 1         | 1.89%   |
| Canon iP7200 series                           | 1         | 1.89%   |
| Brother MFC-7420                              | 1         | 1.89%   |
| Brother HL-5380DN series                      | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 266       | 22.35%  |
| Chicony Electronics                    | 242       | 20.34%  |
| Realtek Semiconductor                  | 102       | 8.57%   |
| Microdia                               | 87        | 7.31%   |
| Bison Electronics                      | 62        | 5.21%   |
| Sunplus Innovation Technology          | 61        | 5.13%   |
| Quanta                                 | 57        | 4.79%   |
| Syntek                                 | 30        | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 2.35%   |
| Lite-On Technology                     | 26        | 2.18%   |
| Alcor Micro                            | 26        | 2.18%   |
| Logitech                               | 25        | 2.1%    |
| Suyin                                  | 21        | 1.76%   |
| Sonix Technology                       | 19        | 1.6%    |
| Acer                                   | 19        | 1.6%    |
| Luxvisions Innotech Limited            | 12        | 1.01%   |
| Apple                                  | 12        | 1.01%   |
| Samsung Electronics                    | 11        | 0.92%   |
| Ricoh                                  | 10        | 0.84%   |
| Microsoft                              | 10        | 0.84%   |
| Silicon Motion                         | 7         | 0.59%   |
| Z-Star Microelectronics                | 6         | 0.5%    |
| OmniVision Technologies                | 5         | 0.42%   |
| ALi                                    | 4         | 0.34%   |
| Primax Electronics                     | 3         | 0.25%   |
| Lenovo                                 | 3         | 0.25%   |
| GEMBIRD                                | 3         | 0.25%   |
| Cubeternet                             | 3         | 0.25%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Jieli Technology                       | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| Aveo Technology                        | 2         | 0.17%   |
| Arkmicro Technologies                  | 2         | 0.17%   |
| WaveRider Communications               | 1         | 0.08%   |
| Unknown                                | 1         | 0.08%   |
| Trust                                  | 1         | 0.08%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.08%   |
| Philips (or NXP)                       | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 110       | 9.23%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 84        | 7.05%   |
| Chicony Integrated Camera                           | 53        | 4.45%   |
| Realtek Integrated_Webcam_HD                        | 33        | 2.77%   |
| IMC Networks Integrated Camera                      | 33        | 2.77%   |
| Microdia Integrated_Webcam_HD                       | 26        | 2.18%   |
| Chicony USB2.0 VGA UVC WebCam                       | 19        | 1.59%   |
| Syntek Integrated Camera                            | 17        | 1.43%   |
| Chicony HD Webcam                                   | 16        | 1.34%   |
| Sonix USB2.0 HD UVC WebCam                          | 15        | 1.26%   |
| Chicony USB2.0 HD UVC WebCam                        | 15        | 1.26%   |
| Sunplus HD WebCam                                   | 14        | 1.17%   |
| Realtek USB Camera                                  | 13        | 1.09%   |
| Quanta VGA WebCam                                   | 13        | 1.09%   |
| Bison Integrated Camera                             | 13        | 1.09%   |
| Bison Lenovo EasyCamera                             | 12        | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)             | 11        | 0.92%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 0.92%   |
| Acer Integrated Camera                              | 11        | 0.92%   |
| Chicony EasyCamera                                  | 10        | 0.84%   |
| Lite-On Integrated Camera                           | 9         | 0.76%   |
| Chicony HP Webcam                                   | 9         | 0.76%   |
| Bison SunplusIT Integrated Camera                   | 9         | 0.76%   |
| Alcor Micro USB 2.0 PC Camera                       | 9         | 0.76%   |
| Microsoft LifeCam HD-3000                           | 8         | 0.67%   |
| Microdia Integrated Webcam                          | 8         | 0.67%   |
| Microdia Camera                                     | 8         | 0.67%   |
| Chicony VGA WebCam                                  | 8         | 0.67%   |
| Bison EasyCamera                                    | 8         | 0.67%   |
| Alcor Micro USB 2.0 Camera                          | 8         | 0.67%   |
| Syntek EasyCamera                                   | 7         | 0.59%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                       | 7         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.59%   |
| Realtek Integrated Webcam                           | 7         | 0.59%   |
| Quanta ACER HD User Facing                          | 7         | 0.59%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 7         | 0.59%   |
| Sunplus ASUS Webcam                                 | 6         | 0.5%    |
| Realtek Lenovo EasyCamera                           | 6         | 0.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 6         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 58        | 33.14%  |
| Synaptics                  | 46        | 26.29%  |
| Shenzhen Goodix Technology | 22        | 12.57%  |
| Elan Microelectronics      | 16        | 9.14%   |
| Upek                       | 11        | 6.29%   |
| AuthenTec                  | 9         | 5.14%   |
| LighTuning Technology      | 8         | 4.57%   |
| Focal-systems.Corp         | 2         | 1.14%   |
| STMicroelectronics         | 1         | 0.57%   |
| Samsung Electronics        | 1         | 0.57%   |
| GDMicroelectronics         | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 8%      |
| Shenzhen Goodix  Fingerprint Device                                        | 14        | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 7.43%   |
| Synaptics  WBDI                                                            | 11        | 6.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 5.71%   |
| Elan ELAN:Fingerprint                                                      | 10        | 5.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.43%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.43%   |
| Elan ELAN:ARM-M4                                                           | 6         | 3.43%   |
| AuthenTec AES2810                                                          | 6         | 3.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.86%   |
| Validity Sensors VFS491                                                    | 4         | 2.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.71%   |
| Synaptics WBDI                                                             | 3         | 1.71%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.71%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.71%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.14%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.14%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.14%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.57%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.57%   |
| Synaptics UWP WBDI                                                         | 1         | 0.57%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.57%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.57%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.57%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.57%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 43        | 55.13%  |
| Alcor Micro               | 18        | 23.08%  |
| Upek                      | 5         | 6.41%   |
| Lenovo                    | 5         | 6.41%   |
| O2 Micro                  | 3         | 3.85%   |
| Gemalto (was Gemplus)     | 1         | 1.28%   |
| Fujitsu Siemens Computers | 1         | 1.28%   |
| Chicony Electronics       | 1         | 1.28%   |
| Aladdin Knowledge Systems | 1         | 1.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 23.08%  |
| Broadcom 58200                                                               | 13        | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 14.1%   |
| Broadcom 5880                                                                | 11        | 14.1%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 10.26%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 6.41%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 6.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.85%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.28%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.28%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1358      | 72.66%  |
| 1     | 412       | 22.04%  |
| 2     | 89        | 4.76%   |
| 3     | 8         | 0.43%   |
| 10    | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 174       | 28.62%  |
| Graphics card            | 136       | 22.37%  |
| Net/wireless             | 74        | 12.17%  |
| Chipcard                 | 71        | 11.68%  |
| Multimedia controller    | 39        | 6.41%   |
| Camera                   | 23        | 3.78%   |
| Communication controller | 22        | 3.62%   |
| Storage                  | 16        | 2.63%   |
| Bluetooth                | 16        | 2.63%   |
| Card reader              | 8         | 1.32%   |
| Sound                    | 7         | 1.15%   |
| Unassigned class         | 5         | 0.82%   |
| Net/ethernet             | 4         | 0.66%   |
| Network                  | 3         | 0.49%   |
| Storage/ide              | 2         | 0.33%   |
| Flash memory             | 2         | 0.33%   |
| Unclassified device      | 1         | 0.16%   |
| Storage/raid             | 1         | 0.16%   |
| Storage/nvme             | 1         | 0.16%   |
| Modem                    | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |


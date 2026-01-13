OpenMandriva 23.08 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.08.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_23.08/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_23.08/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2673

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro6,2               | Notebook    | [c000bcbafb](https://linux-hardware.org/?probe=c000bcbafb) | Jan 02, 2026 |
| Dell          | Inspiron N5050              | Notebook    | [03edb766a6](https://linux-hardware.org/?probe=03edb766a6) | Dec 31, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [4c7327e543](https://linux-hardware.org/?probe=4c7327e543) | Dec 30, 2025 |
| Acer          | Extensa 5635Z               | Notebook    | [6072e75059](https://linux-hardware.org/?probe=6072e75059) | Dec 30, 2025 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [c453556728](https://linux-hardware.org/?probe=c453556728) | Dec 27, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [dc36d440bb](https://linux-hardware.org/?probe=dc36d440bb) | Dec 25, 2025 |
| Intel         | X79-SERVER V1.1             | Desktop     | [b39495b335](https://linux-hardware.org/?probe=b39495b335) | Dec 24, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [a7dea29293](https://linux-hardware.org/?probe=a7dea29293) | Dec 23, 2025 |
| OE            | B75 Ver:1.51                | Desktop     | [cb67b893d9](https://linux-hardware.org/?probe=cb67b893d9) | Dec 22, 2025 |
| OEM           | PB-1900-A                   | Desktop     | [495d273691](https://linux-hardware.org/?probe=495d273691) | Dec 18, 2025 |
| Gigabyte      | A520M K V2                  | Desktop     | [ba9ffb859e](https://linux-hardware.org/?probe=ba9ffb859e) | Dec 18, 2025 |
| Gigabyte      | P55A-UD3                    | Desktop     | [67a6cdab27](https://linux-hardware.org/?probe=67a6cdab27) | Dec 17, 2025 |
| Gigabyte      | H410M S2H V2                | Desktop     | [dc55be6862](https://linux-hardware.org/?probe=dc55be6862) | Dec 16, 2025 |
| HP            | ProBook 4440s               | Notebook    | [eb344b3ec7](https://linux-hardware.org/?probe=eb344b3ec7) | Dec 13, 2025 |
| Acer          | Aspire A315-23              | Notebook    | [ce62a45be1](https://linux-hardware.org/?probe=ce62a45be1) | Dec 09, 2025 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [9c8c4bb508](https://linux-hardware.org/?probe=9c8c4bb508) | Dec 03, 2025 |
| Acer          | Aspire 7736                 | Notebook    | [3fc0431f30](https://linux-hardware.org/?probe=3fc0431f30) | Nov 29, 2025 |
| Lenovo        | 10064                       | All in one  | [6e0a79a977](https://linux-hardware.org/?probe=6e0a79a977) | Nov 29, 2025 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [52cdc15403](https://linux-hardware.org/?probe=52cdc15403) | Nov 28, 2025 |
| Toshiba       | Satellite L775D             | Notebook    | [f0e0bea0a1](https://linux-hardware.org/?probe=f0e0bea0a1) | Nov 27, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0937729d43](https://linux-hardware.org/?probe=0937729d43) | Nov 25, 2025 |
| Clevo         | W760T/M740T/M760T           | Notebook    | [ce0bec48c1](https://linux-hardware.org/?probe=ce0bec48c1) | Nov 23, 2025 |
| Dell          | Precision 7760              | Notebook    | [95bbbaca85](https://linux-hardware.org/?probe=95bbbaca85) | Nov 11, 2025 |
| Intel         | H81                         | Desktop     | [68787f2b50](https://linux-hardware.org/?probe=68787f2b50) | Nov 10, 2025 |
| Dell          | Vostro 3560                 | Notebook    | [93f7879121](https://linux-hardware.org/?probe=93f7879121) | Nov 04, 2025 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [c1c93e6c44](https://linux-hardware.org/?probe=c1c93e6c44) | Nov 01, 2025 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [161c3f4fc6](https://linux-hardware.org/?probe=161c3f4fc6) | Oct 28, 2025 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [a6c3c8f68d](https://linux-hardware.org/?probe=a6c3c8f68d) | Oct 25, 2025 |
| Intel         | H110                        | Desktop     | [38c0fd96ce](https://linux-hardware.org/?probe=38c0fd96ce) | Oct 24, 2025 |
| Intel         | H61                         | Desktop     | [9fbbaac6f4](https://linux-hardware.org/?probe=9fbbaac6f4) | Oct 24, 2025 |
| Gateway       | NE56R                       | Notebook    | [ee5d3d1793](https://linux-hardware.org/?probe=ee5d3d1793) | Oct 17, 2025 |
| Dell          | 07N90W A00                  | Desktop     | [5f2dd0fe56](https://linux-hardware.org/?probe=5f2dd0fe56) | Oct 15, 2025 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [6d0a9115bc](https://linux-hardware.org/?probe=6d0a9115bc) | Oct 15, 2025 |
| HP            | Compaq Presario CQ40        | Notebook    | [06fa762ed5](https://linux-hardware.org/?probe=06fa762ed5) | Oct 15, 2025 |
| Dell          | Latitude E6320              | Notebook    | [cd3838e8fb](https://linux-hardware.org/?probe=cd3838e8fb) | Oct 03, 2025 |
| Dell          | 0YXT71 A03                  | Desktop     | [cd65870da5](https://linux-hardware.org/?probe=cd65870da5) | Oct 03, 2025 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [8ef6b66d7c](https://linux-hardware.org/?probe=8ef6b66d7c) | Sep 23, 2025 |
| Lenovo        | MAHOBAY                     | Desktop     | [9c9d66fb22](https://linux-hardware.org/?probe=9c9d66fb22) | Sep 21, 2025 |
| Acer          | TravelMate Spin B311R-31    | Convertible | [6418dc78d3](https://linux-hardware.org/?probe=6418dc78d3) | Sep 21, 2025 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [3ebcfe13e5](https://linux-hardware.org/?probe=3ebcfe13e5) | Sep 18, 2025 |
| ASUSTek       | UX30                        | Notebook    | [4dca49a778](https://linux-hardware.org/?probe=4dca49a778) | Sep 15, 2025 |
| HP            | 1494                        | Desktop     | [9de6ae42ce](https://linux-hardware.org/?probe=9de6ae42ce) | Sep 14, 2025 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [f6481d6114](https://linux-hardware.org/?probe=f6481d6114) | Sep 08, 2025 |
| ASRock        | X370 Gaming K4              | Desktop     | [ad55b58518](https://linux-hardware.org/?probe=ad55b58518) | Sep 07, 2025 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [587f34a876](https://linux-hardware.org/?probe=587f34a876) | Sep 05, 2025 |
| Toshiba       | Satellite C665              | Notebook    | [4509419eed](https://linux-hardware.org/?probe=4509419eed) | Sep 05, 2025 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [152647fc7b](https://linux-hardware.org/?probe=152647fc7b) | Aug 24, 2025 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [fbf37c4602](https://linux-hardware.org/?probe=fbf37c4602) | Aug 23, 2025 |
| Lenovo        | ThinkPad T500 208252G       | Notebook    | [f24a106720](https://linux-hardware.org/?probe=f24a106720) | Aug 18, 2025 |
| Gigabyte      | RC14UD                      | Notebook    | [88f468f96a](https://linux-hardware.org/?probe=88f468f96a) | Aug 17, 2025 |
| Packard Be... | EasyNote LM85               | Notebook    | [f4deb1b1a2](https://linux-hardware.org/?probe=f4deb1b1a2) | Aug 14, 2025 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [ebc6312c94](https://linux-hardware.org/?probe=ebc6312c94) | Aug 10, 2025 |
| Acer          | Aspire 5517                 | Notebook    | [8841e7dc7b](https://linux-hardware.org/?probe=8841e7dc7b) | Aug 02, 2025 |
| Dell          | Inspiron 7720               | Notebook    | [f0b81caeff](https://linux-hardware.org/?probe=f0b81caeff) | Jul 27, 2025 |
| AZW           | Green G3                    | Desktop     | [17802cd0e4](https://linux-hardware.org/?probe=17802cd0e4) | Jul 19, 2025 |
| HP            | 83F2                        | Desktop     | [58768de8fa](https://linux-hardware.org/?probe=58768de8fa) | Jul 11, 2025 |
| Gigabyte      | G41M-Combo                  | Desktop     | [97d0d9ab65](https://linux-hardware.org/?probe=97d0d9ab65) | Jun 29, 2025 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ff1648e05b](https://linux-hardware.org/?probe=ff1648e05b) | Jun 27, 2025 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [055eb4dbac](https://linux-hardware.org/?probe=055eb4dbac) | Jun 16, 2025 |
| Lenovo        | ThinkPad X260 20F5S3WQ00    | Notebook    | [a2a15b5c22](https://linux-hardware.org/?probe=a2a15b5c22) | Jun 12, 2025 |
| Core Innov... | CLC14364                    | Notebook    | [50f6ea57d0](https://linux-hardware.org/?probe=50f6ea57d0) | May 21, 2025 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [b73243925d](https://linux-hardware.org/?probe=b73243925d) | May 21, 2025 |
| Google        | Kip                         | Notebook    | [cbd824350f](https://linux-hardware.org/?probe=cbd824350f) | May 19, 2025 |
| MSI           | H110M PRO-D                 | Desktop     | [6221e60ba0](https://linux-hardware.org/?probe=6221e60ba0) | May 19, 2025 |
| ASUSTek       | H110M-R                     | Desktop     | [48cf8253f7](https://linux-hardware.org/?probe=48cf8253f7) | May 14, 2025 |
| Packard Be... | IMEDIA S2110A               | Desktop     | [59366f9ac9](https://linux-hardware.org/?probe=59366f9ac9) | May 12, 2025 |
| Compaq        | PRESARIOCQ18                | Notebook    | [1d657ad9df](https://linux-hardware.org/?probe=1d657ad9df) | May 05, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [13d7fcb898](https://linux-hardware.org/?probe=13d7fcb898) | May 04, 2025 |
| Lenovo        | ThinkPad Edge E440 20C5S... | Notebook    | [addb6f6aa4](https://linux-hardware.org/?probe=addb6f6aa4) | May 03, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [ca27d69a65](https://linux-hardware.org/?probe=ca27d69a65) | May 03, 2025 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [876e026a35](https://linux-hardware.org/?probe=876e026a35) | May 02, 2025 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [850c825b8b](https://linux-hardware.org/?probe=850c825b8b) | May 02, 2025 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [60072d7050](https://linux-hardware.org/?probe=60072d7050) | May 01, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [e34b1c594e](https://linux-hardware.org/?probe=e34b1c594e) | Apr 29, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [b464ea2947](https://linux-hardware.org/?probe=b464ea2947) | Apr 29, 2025 |
| Dell          | Latitude E6510              | Notebook    | [ef5c10759f](https://linux-hardware.org/?probe=ef5c10759f) | Apr 28, 2025 |
| MSI           | 2AE0                        | Desktop     | [fe3b3af8f0](https://linux-hardware.org/?probe=fe3b3af8f0) | Apr 27, 2025 |
| Lenovo        | ThinkPad R61 8932AFG        | Notebook    | [c632fab9cd](https://linux-hardware.org/?probe=c632fab9cd) | Apr 25, 2025 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f51a8aa9d7](https://linux-hardware.org/?probe=f51a8aa9d7) | Apr 25, 2025 |
| Dell          | Latitude E5540              | Notebook    | [82ce2367a0](https://linux-hardware.org/?probe=82ce2367a0) | Apr 21, 2025 |
| Garbarino ... | A24                         | Notebook    | [e0ccfbe5bf](https://linux-hardware.org/?probe=e0ccfbe5bf) | Apr 20, 2025 |
| ASUSTek       | K52F                        | Notebook    | [e5183f2f85](https://linux-hardware.org/?probe=e5183f2f85) | Apr 20, 2025 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [e604c5aa4e](https://linux-hardware.org/?probe=e604c5aa4e) | Apr 13, 2025 |
| Dynabook      | Satellite Pro C50-G-10A     | Notebook    | [28f1b14289](https://linux-hardware.org/?probe=28f1b14289) | Apr 12, 2025 |
| HP            | 1497                        | Desktop     | [82f816f609](https://linux-hardware.org/?probe=82f816f609) | Apr 10, 2025 |
| Dell          | Latitude E5550              | Notebook    | [acafc2bbf2](https://linux-hardware.org/?probe=acafc2bbf2) | Apr 09, 2025 |
| MSI           | G41M-E43                    | Desktop     | [4c93bca35f](https://linux-hardware.org/?probe=4c93bca35f) | Apr 08, 2025 |
| Medion        | S14406                      | Convertible | [9097058c60](https://linux-hardware.org/?probe=9097058c60) | Apr 05, 2025 |
| HP            | OMEN by Laptop              | Notebook    | [52639085ca](https://linux-hardware.org/?probe=52639085ca) | Apr 01, 2025 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [c989e4a14a](https://linux-hardware.org/?probe=c989e4a14a) | Mar 31, 2025 |
| Dell          | 02YRK5 A02                  | Desktop     | [e2daa3cd61](https://linux-hardware.org/?probe=e2daa3cd61) | Mar 29, 2025 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [be662a36d5](https://linux-hardware.org/?probe=be662a36d5) | Mar 29, 2025 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1c02be5e87](https://linux-hardware.org/?probe=1c02be5e87) | Mar 28, 2025 |
| Lenovo        | ThinkPad SL510 28477LG      | Notebook    | [7ec79f3a57](https://linux-hardware.org/?probe=7ec79f3a57) | Mar 21, 2025 |
| Dell          | Vostro 3300                 | Notebook    | [29b728be5f](https://linux-hardware.org/?probe=29b728be5f) | Mar 20, 2025 |
| Acer          | TravelMate B115-M           | Notebook    | [bf54eb4e1d](https://linux-hardware.org/?probe=bf54eb4e1d) | Mar 19, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [47f0c1410b](https://linux-hardware.org/?probe=47f0c1410b) | Mar 15, 2025 |
| OEM           | Intel H81                   | Desktop     | [3db1e329ea](https://linux-hardware.org/?probe=3db1e329ea) | Mar 15, 2025 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [9e9920330b](https://linux-hardware.org/?probe=9e9920330b) | Mar 14, 2025 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2692031b95](https://linux-hardware.org/?probe=2692031b95) | Mar 14, 2025 |
| Unknown       | Unknown                     | Notebook    | [68fd60a5d0](https://linux-hardware.org/?probe=68fd60a5d0) | Mar 14, 2025 |
| ASUSTek       | X550CC                      | Notebook    | [bbb8906fa4](https://linux-hardware.org/?probe=bbb8906fa4) | Mar 13, 2025 |
| MSI           | H77MA-G43                   | Desktop     | [1adf7d4b88](https://linux-hardware.org/?probe=1adf7d4b88) | Mar 12, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [49bbb4dce0](https://linux-hardware.org/?probe=49bbb4dce0) | Mar 11, 2025 |
| AMI           | Intel                       | Desktop     | [c19ddfc065](https://linux-hardware.org/?probe=c19ddfc065) | Mar 10, 2025 |
| Dell          | 088DT1 A01                  | Desktop     | [cd97b0b4bf](https://linux-hardware.org/?probe=cd97b0b4bf) | Mar 09, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [816accfc42](https://linux-hardware.org/?probe=816accfc42) | Mar 06, 2025 |
| Gfast         | N-550 SW                    | Notebook    | [3927cca0a2](https://linux-hardware.org/?probe=3927cca0a2) | Mar 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [cf77bfc03e](https://linux-hardware.org/?probe=cf77bfc03e) | Mar 03, 2025 |
| Lenovo        | ThinkPad P70 20ER002KUS     | Notebook    | [42a36ab17c](https://linux-hardware.org/?probe=42a36ab17c) | Mar 02, 2025 |
| Acer          | Swift SF114-34              | Notebook    | [6d75f1f7ae](https://linux-hardware.org/?probe=6d75f1f7ae) | Mar 01, 2025 |
| Acer          | Swift SF114-34              | Notebook    | [2b1a4d787a](https://linux-hardware.org/?probe=2b1a4d787a) | Mar 01, 2025 |
| Dell          | Latitude E5470              | Notebook    | [ff161f7304](https://linux-hardware.org/?probe=ff161f7304) | Feb 28, 2025 |
| Biostar       | A320MH                      | Desktop     | [b1a89f13fa](https://linux-hardware.org/?probe=b1a89f13fa) | Feb 27, 2025 |
| Dell          | 0XM091 A00                  | Server      | [003d801304](https://linux-hardware.org/?probe=003d801304) | Feb 27, 2025 |
| Acer          | Veriton N4640G              | Desktop     | [3c39bd1f1e](https://linux-hardware.org/?probe=3c39bd1f1e) | Feb 26, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [1ffee5f851](https://linux-hardware.org/?probe=1ffee5f851) | Feb 25, 2025 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [60c8a1683a](https://linux-hardware.org/?probe=60c8a1683a) | Feb 25, 2025 |
| HP            | Notebook                    | Notebook    | [f42a146312](https://linux-hardware.org/?probe=f42a146312) | Feb 22, 2025 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [7a908522fb](https://linux-hardware.org/?probe=7a908522fb) | Feb 21, 2025 |
| Gigabyte      | B650 EAGLE AX               | Desktop     | [358d0304dc](https://linux-hardware.org/?probe=358d0304dc) | Feb 17, 2025 |
| Jumper        | EZbook                      | Notebook    | [a3f477db1a](https://linux-hardware.org/?probe=a3f477db1a) | Feb 16, 2025 |
| Fujitsu       | FMVNE4N1E                   | Notebook    | [cd59edb27b](https://linux-hardware.org/?probe=cd59edb27b) | Feb 15, 2025 |
| HP            | 3105m                       | Notebook    | [3877a9396d](https://linux-hardware.org/?probe=3877a9396d) | Feb 14, 2025 |
| PT Zyrexin... | Sky 232                     | Notebook    | [18461e2dfb](https://linux-hardware.org/?probe=18461e2dfb) | Feb 12, 2025 |
| ASUSTek       | PRIME B760M-K               | Desktop     | [a3200946c9](https://linux-hardware.org/?probe=a3200946c9) | Feb 11, 2025 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [95c78d15c8](https://linux-hardware.org/?probe=95c78d15c8) | Feb 10, 2025 |
| Dell          | 0XFWHV A00                  | Desktop     | [6c7b9ae61d](https://linux-hardware.org/?probe=6c7b9ae61d) | Feb 09, 2025 |
| Dell          | 02YYK5 A01                  | Desktop     | [34df1838f8](https://linux-hardware.org/?probe=34df1838f8) | Feb 09, 2025 |
| BESSTAR Te... | UM700                       | Desktop     | [19e4ca1daa](https://linux-hardware.org/?probe=19e4ca1daa) | Feb 09, 2025 |
| Acer          | TravelMate 5330             | Notebook    | [66efdf9ec2](https://linux-hardware.org/?probe=66efdf9ec2) | Feb 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [42bda51288](https://linux-hardware.org/?probe=42bda51288) | Feb 08, 2025 |
| Valve         | Jupiter                     | Notebook    | [6f0493da5b](https://linux-hardware.org/?probe=6f0493da5b) | Feb 08, 2025 |
| ASRock        | A520M-HVS                   | Desktop     | [9319f87279](https://linux-hardware.org/?probe=9319f87279) | Feb 04, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [e7f297cb0c](https://linux-hardware.org/?probe=e7f297cb0c) | Feb 02, 2025 |
| Intel         | D34010WYK H14771-302        | Desktop     | [b4294292b5](https://linux-hardware.org/?probe=b4294292b5) | Feb 02, 2025 |
| Lenovo        | 3130 SEK0N11843 IOT 3806... | Mini pc     | [e22e2cc019](https://linux-hardware.org/?probe=e22e2cc019) | Feb 01, 2025 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [856a9062bf](https://linux-hardware.org/?probe=856a9062bf) | Jan 31, 2025 |
| Gigabyte      | H510M H V2                  | Desktop     | [8c2cbda31c](https://linux-hardware.org/?probe=8c2cbda31c) | Jan 31, 2025 |
| Dell          | Inspiron 5565               | Notebook    | [4f0e393088](https://linux-hardware.org/?probe=4f0e393088) | Jan 31, 2025 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [ae3326de42](https://linux-hardware.org/?probe=ae3326de42) | Jan 29, 2025 |
| Gigabyte      | H510M S2H V2                | Desktop     | [bd73d384b7](https://linux-hardware.org/?probe=bd73d384b7) | Jan 29, 2025 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [fa12d7157e](https://linux-hardware.org/?probe=fa12d7157e) | Jan 28, 2025 |
| Lenovo        | G500 20236                  | Notebook    | [6791db1f86](https://linux-hardware.org/?probe=6791db1f86) | Jan 27, 2025 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [140af0a66d](https://linux-hardware.org/?probe=140af0a66d) | Jan 25, 2025 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [9d3ab9fe07](https://linux-hardware.org/?probe=9d3ab9fe07) | Jan 23, 2025 |
| Acer          | Nitro AN515-54              | Notebook    | [47b66de1a2](https://linux-hardware.org/?probe=47b66de1a2) | Jan 23, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [c4f2b5b63c](https://linux-hardware.org/?probe=c4f2b5b63c) | Jan 23, 2025 |
| Unknown       | Unknown                     | Notebook    | [8339e23e57](https://linux-hardware.org/?probe=8339e23e57) | Jan 23, 2025 |
| Dell          | XPS M1330                   | Notebook    | [1b61e7b15d](https://linux-hardware.org/?probe=1b61e7b15d) | Jan 21, 2025 |
| Dell          | XPS 13 9360                 | Notebook    | [faf23fcd86](https://linux-hardware.org/?probe=faf23fcd86) | Jan 20, 2025 |
| System76      | Gazelle Professional        | Notebook    | [16cb24761f](https://linux-hardware.org/?probe=16cb24761f) | Jan 20, 2025 |
| Dell          | 04Y8V0 A02                  | Desktop     | [e1f743a64e](https://linux-hardware.org/?probe=e1f743a64e) | Jan 19, 2025 |
| Acer          | TPDS03                      | Desktop     | [a2880368f6](https://linux-hardware.org/?probe=a2880368f6) | Jan 18, 2025 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | Notebook    | [afcd493408](https://linux-hardware.org/?probe=afcd493408) | Jan 17, 2025 |
| Dell          | 0D28YY A03                  | Desktop     | [7ca351f7c2](https://linux-hardware.org/?probe=7ca351f7c2) | Jan 15, 2025 |
| Biostar       | H510MHP                     | Desktop     | [2b13c6cb40](https://linux-hardware.org/?probe=2b13c6cb40) | Jan 14, 2025 |
| Lenovo        | MAHOBAY                     | Desktop     | [e9c4e8df86](https://linux-hardware.org/?probe=e9c4e8df86) | Jan 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [742a75a9eb](https://linux-hardware.org/?probe=742a75a9eb) | Jan 13, 2025 |
| Dell          | Latitude E6520              | Notebook    | [863e21f8e5](https://linux-hardware.org/?probe=863e21f8e5) | Jan 12, 2025 |
| Dell          | Precision M6500             | Notebook    | [88cc3adff6](https://linux-hardware.org/?probe=88cc3adff6) | Jan 12, 2025 |
| Dell          | Latitude E7450              | Notebook    | [3574b3e7a6](https://linux-hardware.org/?probe=3574b3e7a6) | Jan 12, 2025 |
| Lenovo        | ThinkPad R61 8932H2U        | Notebook    | [d5d05cd75e](https://linux-hardware.org/?probe=d5d05cd75e) | Jan 11, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [91a08fd20b](https://linux-hardware.org/?probe=91a08fd20b) | Jan 09, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [557655b58a](https://linux-hardware.org/?probe=557655b58a) | Jan 09, 2025 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [9e7bfc1a79](https://linux-hardware.org/?probe=9e7bfc1a79) | Jan 08, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [08fe93de5e](https://linux-hardware.org/?probe=08fe93de5e) | Jan 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3752f86e5a](https://linux-hardware.org/?probe=3752f86e5a) | Jan 08, 2025 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [5e36b2cdba](https://linux-hardware.org/?probe=5e36b2cdba) | Jan 08, 2025 |
| Lenovo        | ThinkPad T410 25375S9       | Notebook    | [2c99a8cf6c](https://linux-hardware.org/?probe=2c99a8cf6c) | Jan 08, 2025 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6cdf8af1ac](https://linux-hardware.org/?probe=6cdf8af1ac) | Jan 07, 2025 |
| Lenovo        | ThinkCentre M81 5048W4K     | Desktop     | [49285e67cd](https://linux-hardware.org/?probe=49285e67cd) | Jan 07, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ca54bfccd](https://linux-hardware.org/?probe=2ca54bfccd) | Jan 07, 2025 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [0c0f6ef206](https://linux-hardware.org/?probe=0c0f6ef206) | Jan 06, 2025 |
| Acer          | Aspire ES1-731              | Notebook    | [721fdec99d](https://linux-hardware.org/?probe=721fdec99d) | Jan 05, 2025 |
| MSI           | A55M-E33                    | Desktop     | [491adf615a](https://linux-hardware.org/?probe=491adf615a) | Jan 04, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [1f3dee2cf2](https://linux-hardware.org/?probe=1f3dee2cf2) | Jan 02, 2025 |
| Acer          | Predator PH315-53           | Notebook    | [17816e7d6b](https://linux-hardware.org/?probe=17816e7d6b) | Jan 01, 2025 |
| Dell          | Latitude 3340               | Notebook    | [b22cafbc3b](https://linux-hardware.org/?probe=b22cafbc3b) | Jan 01, 2025 |
| Lenovo        | ThinkPad T510 4313A11       | Notebook    | [ecf4a20d48](https://linux-hardware.org/?probe=ecf4a20d48) | Jan 01, 2025 |
| HP            | 2AF3                        | Desktop     | [27a5a9b662](https://linux-hardware.org/?probe=27a5a9b662) | Jan 01, 2025 |
| MSI           | Z97 GAMING 5                | Desktop     | [40b22f7ebe](https://linux-hardware.org/?probe=40b22f7ebe) | Dec 30, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | Desktop     | [e13ed7c057](https://linux-hardware.org/?probe=e13ed7c057) | Dec 30, 2024 |
| HP            | 805D                        | Desktop     | [1c1e40f526](https://linux-hardware.org/?probe=1c1e40f526) | Dec 28, 2024 |
| ASRock        | A620M-HDV/M.2               | Desktop     | [7bd64010ea](https://linux-hardware.org/?probe=7bd64010ea) | Dec 28, 2024 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [317b3a0d60](https://linux-hardware.org/?probe=317b3a0d60) | Dec 28, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0215708466](https://linux-hardware.org/?probe=0215708466) | Dec 26, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [1808c0b1a3](https://linux-hardware.org/?probe=1808c0b1a3) | Dec 26, 2024 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [e642f51eb3](https://linux-hardware.org/?probe=e642f51eb3) | Dec 25, 2024 |
| ASUSTek       | D700SA                      | Desktop     | [cdea79b4a9](https://linux-hardware.org/?probe=cdea79b4a9) | Dec 25, 2024 |
| MSI           | A78M-E35 V2                 | Desktop     | [37ed0bfc1f](https://linux-hardware.org/?probe=37ed0bfc1f) | Dec 24, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [ea4a7e6f67](https://linux-hardware.org/?probe=ea4a7e6f67) | Dec 21, 2024 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [5d6d1c59a4](https://linux-hardware.org/?probe=5d6d1c59a4) | Dec 21, 2024 |
| ASUSTek       | UX430UAR                    | Notebook    | [b7824c3d65](https://linux-hardware.org/?probe=b7824c3d65) | Dec 20, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [407784b097](https://linux-hardware.org/?probe=407784b097) | Dec 19, 2024 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [f50786aff4](https://linux-hardware.org/?probe=f50786aff4) | Dec 19, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f0168d3f71](https://linux-hardware.org/?probe=f0168d3f71) | Dec 19, 2024 |
| Dell          | Latitude E6500              | Notebook    | [f173d0af82](https://linux-hardware.org/?probe=f173d0af82) | Dec 19, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [35f435cd1f](https://linux-hardware.org/?probe=35f435cd1f) | Dec 18, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [aa3a93dbc4](https://linux-hardware.org/?probe=aa3a93dbc4) | Dec 18, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [26fb82a499](https://linux-hardware.org/?probe=26fb82a499) | Dec 18, 2024 |
| HP            | 2B2C                        | Desktop     | [0b3869847d](https://linux-hardware.org/?probe=0b3869847d) | Dec 17, 2024 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [69b82b01c8](https://linux-hardware.org/?probe=69b82b01c8) | Dec 16, 2024 |
| Dell          | Latitude E6430              | Notebook    | [8169d8c98d](https://linux-hardware.org/?probe=8169d8c98d) | Dec 16, 2024 |
| Lenovo        | ThinkPad R500 2714AAG       | Notebook    | [d4c46ae3a8](https://linux-hardware.org/?probe=d4c46ae3a8) | Dec 16, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [fe744f8173](https://linux-hardware.org/?probe=fe744f8173) | Dec 15, 2024 |
| Dell          | 0TDG4V A00                  | Desktop     | [e8c33005d3](https://linux-hardware.org/?probe=e8c33005d3) | Dec 14, 2024 |
| Lenovo        | RD450X                      | Server      | [142ea5aaab](https://linux-hardware.org/?probe=142ea5aaab) | Dec 14, 2024 |
| Lenovo        | B490 20205                  | Notebook    | [68e4babaf4](https://linux-hardware.org/?probe=68e4babaf4) | Dec 14, 2024 |
| ASRock        | X299 Taichi XE              | Desktop     | [23e15f73e6](https://linux-hardware.org/?probe=23e15f73e6) | Dec 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [8ff95feafc](https://linux-hardware.org/?probe=8ff95feafc) | Dec 13, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [263df008c5](https://linux-hardware.org/?probe=263df008c5) | Dec 13, 2024 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [b6c3e35ea6](https://linux-hardware.org/?probe=b6c3e35ea6) | Dec 12, 2024 |
| ASUSTek       | M2N-SLI                     | Desktop     | [137df4dff6](https://linux-hardware.org/?probe=137df4dff6) | Dec 12, 2024 |
| Lenovo        | ThinkPad SL500 274678G      | Notebook    | [c42768093f](https://linux-hardware.org/?probe=c42768093f) | Dec 12, 2024 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [1b40e982de](https://linux-hardware.org/?probe=1b40e982de) | Dec 11, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a60bd4a552](https://linux-hardware.org/?probe=a60bd4a552) | Dec 11, 2024 |
| Lenovo        | G700 20251                  | Notebook    | [8c886cba43](https://linux-hardware.org/?probe=8c886cba43) | Dec 11, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [3b062636e0](https://linux-hardware.org/?probe=3b062636e0) | Dec 11, 2024 |
| Dell          | 082WXT A01                  | Desktop     | [2af24c92cd](https://linux-hardware.org/?probe=2af24c92cd) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [ed080e6dcc](https://linux-hardware.org/?probe=ed080e6dcc) | Dec 06, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [de445fbbb8](https://linux-hardware.org/?probe=de445fbbb8) | Dec 05, 2024 |
| Dell          | 0YP806 A02                  | Desktop     | [e738237e89](https://linux-hardware.org/?probe=e738237e89) | Dec 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [c832be89c4](https://linux-hardware.org/?probe=c832be89c4) | Dec 03, 2024 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [62b0bcca48](https://linux-hardware.org/?probe=62b0bcca48) | Dec 02, 2024 |
| ASUSTek       | K42F                        | Notebook    | [1f69b601e7](https://linux-hardware.org/?probe=1f69b601e7) | Dec 01, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [45efa5fcaa](https://linux-hardware.org/?probe=45efa5fcaa) | Nov 30, 2024 |
| Acer          | Predator PT316-51s          | Notebook    | [59b81c6d72](https://linux-hardware.org/?probe=59b81c6d72) | Nov 29, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3419013123](https://linux-hardware.org/?probe=3419013123) | Nov 29, 2024 |
| HP            | 1497                        | Desktop     | [a0ee162b98](https://linux-hardware.org/?probe=a0ee162b98) | Nov 23, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R5A0... | Convertible | [9b87a450bd](https://linux-hardware.org/?probe=9b87a450bd) | Nov 22, 2024 |
| Toshiba       | Satellite C660D             | Notebook    | [1a7221b221](https://linux-hardware.org/?probe=1a7221b221) | Nov 22, 2024 |
| Dell          | Inspiron N5050              | Notebook    | [0770122667](https://linux-hardware.org/?probe=0770122667) | Nov 22, 2024 |
| Lenovo        | ThinkPad T400 2768W2X       | Notebook    | [3614ea7cf1](https://linux-hardware.org/?probe=3614ea7cf1) | Nov 20, 2024 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [cc54459990](https://linux-hardware.org/?probe=cc54459990) | Nov 18, 2024 |
| Dell          | Latitude E5540              | Notebook    | [08e9607f7c](https://linux-hardware.org/?probe=08e9607f7c) | Nov 16, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [a875301ed0](https://linux-hardware.org/?probe=a875301ed0) | Nov 15, 2024 |
| Dell          | 0NV0M7 A01                  | Desktop     | [9dfc73bd5d](https://linux-hardware.org/?probe=9dfc73bd5d) | Nov 12, 2024 |
| ASRock        | H55M                        | Desktop     | [dd4d6e3552](https://linux-hardware.org/?probe=dd4d6e3552) | Nov 12, 2024 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [f00ff7ef01](https://linux-hardware.org/?probe=f00ff7ef01) | Nov 09, 2024 |
| Lenovo        | ThinkPad T560 20FJS1WT00    | Notebook    | [ab509efa05](https://linux-hardware.org/?probe=ab509efa05) | Nov 07, 2024 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [93d34614a7](https://linux-hardware.org/?probe=93d34614a7) | Nov 06, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [cfe914638e](https://linux-hardware.org/?probe=cfe914638e) | Nov 06, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a50c814c14](https://linux-hardware.org/?probe=a50c814c14) | Nov 06, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [b9654bc74b](https://linux-hardware.org/?probe=b9654bc74b) | Nov 05, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [81013698ba](https://linux-hardware.org/?probe=81013698ba) | Nov 05, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [50a513535d](https://linux-hardware.org/?probe=50a513535d) | Oct 31, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [43f03f4788](https://linux-hardware.org/?probe=43f03f4788) | Oct 28, 2024 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [039371fc2a](https://linux-hardware.org/?probe=039371fc2a) | Oct 28, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f714c9c792](https://linux-hardware.org/?probe=f714c9c792) | Oct 28, 2024 |
| ASUSTek       | G73Sw                       | Notebook    | [0ff1e91524](https://linux-hardware.org/?probe=0ff1e91524) | Oct 24, 2024 |
| Gigabyte      | H510M H                     | Desktop     | [f9526923ef](https://linux-hardware.org/?probe=f9526923ef) | Oct 24, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [b5bc47c079](https://linux-hardware.org/?probe=b5bc47c079) | Oct 22, 2024 |
| Lenovo        | V320-17IKB 81CN             | Notebook    | [3b1411efb7](https://linux-hardware.org/?probe=3b1411efb7) | Oct 19, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [1af65cb620](https://linux-hardware.org/?probe=1af65cb620) | Oct 19, 2024 |
| Acer          | AO756                       | Notebook    | [a4411d830b](https://linux-hardware.org/?probe=a4411d830b) | Oct 15, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [ea88aa96e7](https://linux-hardware.org/?probe=ea88aa96e7) | Oct 14, 2024 |
| Lenovo        | ThinkPad T490 20N3S7PL00    | Notebook    | [599154f22e](https://linux-hardware.org/?probe=599154f22e) | Oct 12, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [817fd73eeb](https://linux-hardware.org/?probe=817fd73eeb) | Oct 11, 2024 |
| Samsung       | 370E4K                      | Notebook    | [a2b6c4cb49](https://linux-hardware.org/?probe=a2b6c4cb49) | Oct 11, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [be211444da](https://linux-hardware.org/?probe=be211444da) | Oct 11, 2024 |
| Lenovo        | 0x36C017AA NOK              | Desktop     | [435957e3d2](https://linux-hardware.org/?probe=435957e3d2) | Oct 10, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [05648513d8](https://linux-hardware.org/?probe=05648513d8) | Oct 09, 2024 |
| Lenovo        | B50-30 80ES                 | Notebook    | [bd698857f2](https://linux-hardware.org/?probe=bd698857f2) | Oct 07, 2024 |
| Lenovo        | ThinkPad X201 3323BSG       | Notebook    | [f1d6f061f1](https://linux-hardware.org/?probe=f1d6f061f1) | Oct 05, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [8053e3651e](https://linux-hardware.org/?probe=8053e3651e) | Oct 05, 2024 |
| MSI           | H81M-E33                    | Desktop     | [cd077d54a9](https://linux-hardware.org/?probe=cd077d54a9) | Oct 04, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [ff0ca8bb9f](https://linux-hardware.org/?probe=ff0ca8bb9f) | Oct 03, 2024 |
| Clevo         | E7130                       | Notebook    | [ede1b275ef](https://linux-hardware.org/?probe=ede1b275ef) | Oct 03, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [634a831e43](https://linux-hardware.org/?probe=634a831e43) | Sep 30, 2024 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [bf4c0a4115](https://linux-hardware.org/?probe=bf4c0a4115) | Sep 28, 2024 |
| Acer          | Aspire 5100                 | Notebook    | [b14b5cd608](https://linux-hardware.org/?probe=b14b5cd608) | Sep 27, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [e6ccabb39d](https://linux-hardware.org/?probe=e6ccabb39d) | Sep 27, 2024 |
| Dell          | 0HY9JP A02                  | Desktop     | [34ec1e561d](https://linux-hardware.org/?probe=34ec1e561d) | Sep 27, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [e9a05a14d5](https://linux-hardware.org/?probe=e9a05a14d5) | Sep 21, 2024 |
| Pegatron      | 2A99                        | Desktop     | [df53c2fdc1](https://linux-hardware.org/?probe=df53c2fdc1) | Sep 17, 2024 |
| Fujitsu       | FARR01002                   | Notebook    | [496acfd8d9](https://linux-hardware.org/?probe=496acfd8d9) | Sep 17, 2024 |
| Medion        | Akoya E1317T                | Notebook    | [7ad74493a9](https://linux-hardware.org/?probe=7ad74493a9) | Sep 16, 2024 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f6f40bbae2](https://linux-hardware.org/?probe=f6f40bbae2) | Sep 16, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [75b0157161](https://linux-hardware.org/?probe=75b0157161) | Sep 15, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [b62390cebe](https://linux-hardware.org/?probe=b62390cebe) | Sep 15, 2024 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [6055f6f61a](https://linux-hardware.org/?probe=6055f6f61a) | Sep 14, 2024 |
| HP            | 3397                        | Desktop     | [7f9f3926c3](https://linux-hardware.org/?probe=7f9f3926c3) | Sep 14, 2024 |
| KGN           | Kogan Atlas G600 Mini PC... | Mini pc     | [8ed900ce92](https://linux-hardware.org/?probe=8ed900ce92) | Sep 14, 2024 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [22db01d914](https://linux-hardware.org/?probe=22db01d914) | Sep 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8206f3715c](https://linux-hardware.org/?probe=8206f3715c) | Sep 12, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [6c2bf872f2](https://linux-hardware.org/?probe=6c2bf872f2) | Sep 12, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [51f8cded37](https://linux-hardware.org/?probe=51f8cded37) | Sep 10, 2024 |
| ASUSTek       | T100TA                      | Notebook    | [46d4d907c1](https://linux-hardware.org/?probe=46d4d907c1) | Sep 09, 2024 |
| Acer          | Aspire XC100A               | Desktop     | [1ad96742a9](https://linux-hardware.org/?probe=1ad96742a9) | Sep 08, 2024 |
| Getac         | V110G5                      | Notebook    | [8d2f734bbe](https://linux-hardware.org/?probe=8d2f734bbe) | Sep 07, 2024 |
| ASUSTek       | K52Jc                       | Notebook    | [c98eab26fb](https://linux-hardware.org/?probe=c98eab26fb) | Sep 07, 2024 |
| ECS           | Alhena5                     | Desktop     | [f5243d4e22](https://linux-hardware.org/?probe=f5243d4e22) | Sep 07, 2024 |
| HP            | ProBook 6555b               | Notebook    | [9c54971659](https://linux-hardware.org/?probe=9c54971659) | Sep 06, 2024 |
| HP            | Pavilion dv7                | Notebook    | [3d7f0838c5](https://linux-hardware.org/?probe=3d7f0838c5) | Sep 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [da9a9487f7](https://linux-hardware.org/?probe=da9a9487f7) | Sep 05, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a841980936](https://linux-hardware.org/?probe=a841980936) | Sep 04, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [0d1003a111](https://linux-hardware.org/?probe=0d1003a111) | Sep 04, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5196388966](https://linux-hardware.org/?probe=5196388966) | Sep 04, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [646d172aa3](https://linux-hardware.org/?probe=646d172aa3) | Sep 04, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [90787e672c](https://linux-hardware.org/?probe=90787e672c) | Sep 03, 2024 |
| Acer          | Aspire E1-731               | Notebook    | [a39e9ee7ee](https://linux-hardware.org/?probe=a39e9ee7ee) | Sep 03, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [a1a2754ecc](https://linux-hardware.org/?probe=a1a2754ecc) | Sep 03, 2024 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [2c57038ccf](https://linux-hardware.org/?probe=2c57038ccf) | Sep 03, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [a09742cd2c](https://linux-hardware.org/?probe=a09742cd2c) | Sep 03, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [42c8ab64a2](https://linux-hardware.org/?probe=42c8ab64a2) | Sep 02, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [5f9f543837](https://linux-hardware.org/?probe=5f9f543837) | Sep 02, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [07f002f74d](https://linux-hardware.org/?probe=07f002f74d) | Sep 01, 2024 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [9cebc8ab4a](https://linux-hardware.org/?probe=9cebc8ab4a) | Sep 01, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [cc73e58de2](https://linux-hardware.org/?probe=cc73e58de2) | Sep 01, 2024 |
| Acer          | Spin SP513-52N              | Convertible | [4116f7820f](https://linux-hardware.org/?probe=4116f7820f) | Sep 01, 2024 |
| Compaq        | Presario 21                 | Notebook    | [d3296aeef8](https://linux-hardware.org/?probe=d3296aeef8) | Aug 31, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [fcc932f938](https://linux-hardware.org/?probe=fcc932f938) | Aug 31, 2024 |
| Lenovo        | ThinkCentre M57e 9482CP1    | Desktop     | [e4fb5c4a3d](https://linux-hardware.org/?probe=e4fb5c4a3d) | Aug 29, 2024 |
| ASUSTek       | K30AM-J                     | Desktop     | [912c2ae503](https://linux-hardware.org/?probe=912c2ae503) | Aug 29, 2024 |
| Positivo      | POS-PIG41BA POSITIVO        | Desktop     | [6605b92414](https://linux-hardware.org/?probe=6605b92414) | Aug 29, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6ef394b941](https://linux-hardware.org/?probe=6ef394b941) | Aug 27, 2024 |
| NOBLEX        | SF20BA                      | Notebook    | [0994013255](https://linux-hardware.org/?probe=0994013255) | Aug 27, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6b34ecf844](https://linux-hardware.org/?probe=6b34ecf844) | Aug 26, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [95ec5259c5](https://linux-hardware.org/?probe=95ec5259c5) | Aug 25, 2024 |
| Lenovo        | IdeaPad Z360                | Notebook    | [e87a8556e8](https://linux-hardware.org/?probe=e87a8556e8) | Aug 25, 2024 |
| Dell          | Latitude E7440              | Notebook    | [e34eb2cc1f](https://linux-hardware.org/?probe=e34eb2cc1f) | Aug 24, 2024 |
| Dell          | Inspiron N5050              | Notebook    | [1b5da9d1f9](https://linux-hardware.org/?probe=1b5da9d1f9) | Aug 23, 2024 |
| GPU Compan... | GWNR71517                   | Notebook    | [d512d40dcd](https://linux-hardware.org/?probe=d512d40dcd) | Aug 21, 2024 |
| NOBLEX        | SF20BA                      | Notebook    | [4e4ca474ff](https://linux-hardware.org/?probe=4e4ca474ff) | Aug 19, 2024 |
| Dell          | 0F1HC1 A02                  | Desktop     | [480813bb87](https://linux-hardware.org/?probe=480813bb87) | Aug 19, 2024 |
| Acer          | Aspire V3-571G              | Notebook    | [d5e42e65ba](https://linux-hardware.org/?probe=d5e42e65ba) | Aug 19, 2024 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [321fd04e93](https://linux-hardware.org/?probe=321fd04e93) | Aug 19, 2024 |
| Dell          | Inspiron 1420               | Notebook    | [de7c486914](https://linux-hardware.org/?probe=de7c486914) | Aug 19, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [bfd7ae60a1](https://linux-hardware.org/?probe=bfd7ae60a1) | Aug 18, 2024 |
| HP            | 1495                        | Desktop     | [732805c466](https://linux-hardware.org/?probe=732805c466) | Aug 17, 2024 |
| MSI           | MS-AAC11                    | All in one  | [3b989ccaa0](https://linux-hardware.org/?probe=3b989ccaa0) | Aug 17, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [36cbab14da](https://linux-hardware.org/?probe=36cbab14da) | Aug 16, 2024 |
| ASRock        | H77 Pro4-M                  | Desktop     | [920c2d7d1d](https://linux-hardware.org/?probe=920c2d7d1d) | Aug 15, 2024 |
| ASUSTek       | P5GC-MX/GBL                 | Desktop     | [ce7187e567](https://linux-hardware.org/?probe=ce7187e567) | Aug 15, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [264ec74f2a](https://linux-hardware.org/?probe=264ec74f2a) | Aug 14, 2024 |
| Lenovo        | ThinkPad L480 20LTS21U03    | Notebook    | [9330eabf54](https://linux-hardware.org/?probe=9330eabf54) | Aug 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [de436e6dee](https://linux-hardware.org/?probe=de436e6dee) | Aug 14, 2024 |
| HP            | 3648h                       | Desktop     | [8c2f4df269](https://linux-hardware.org/?probe=8c2f4df269) | Aug 14, 2024 |
| Acer          | Aspire A515-56G             | Notebook    | [352a0cd2f6](https://linux-hardware.org/?probe=352a0cd2f6) | Aug 13, 2024 |
| Acer          | Aspire 7750ZG               | Notebook    | [4668032b84](https://linux-hardware.org/?probe=4668032b84) | Aug 11, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [c5a7b37c75](https://linux-hardware.org/?probe=c5a7b37c75) | Aug 11, 2024 |
| Lenovo        | ThinkPad P50 20EQS20D00     | Notebook    | [f1e7259f48](https://linux-hardware.org/?probe=f1e7259f48) | Aug 10, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8df996f30f](https://linux-hardware.org/?probe=8df996f30f) | Aug 10, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [c7c8508e19](https://linux-hardware.org/?probe=c7c8508e19) | Aug 09, 2024 |
| Digibras      | NH4CU53                     | Notebook    | [ab93cac3a8](https://linux-hardware.org/?probe=ab93cac3a8) | Aug 09, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [8478f8a8a8](https://linux-hardware.org/?probe=8478f8a8a8) | Aug 09, 2024 |
| Intel         | DCP847SKE G79416-106        | Desktop     | [9533769267](https://linux-hardware.org/?probe=9533769267) | Aug 09, 2024 |
| Toshiba       | Satellite A135              | Notebook    | [b6676b057d](https://linux-hardware.org/?probe=b6676b057d) | Aug 09, 2024 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [c6367fd908](https://linux-hardware.org/?probe=c6367fd908) | Aug 05, 2024 |
| HP            | G62                         | Notebook    | [cfd261d7d1](https://linux-hardware.org/?probe=cfd261d7d1) | Aug 04, 2024 |
| Positivo      | POS-EC945AL                 | Desktop     | [4291daa596](https://linux-hardware.org/?probe=4291daa596) | Aug 02, 2024 |
| Lenovo        | ThinkPad T530 2429B69       | Notebook    | [cfe8e9461f](https://linux-hardware.org/?probe=cfe8e9461f) | Aug 02, 2024 |
| HP            | 8299                        | Desktop     | [9295b0b5b3](https://linux-hardware.org/?probe=9295b0b5b3) | Aug 02, 2024 |
| HP            | 1825                        | Desktop     | [5b9b648342](https://linux-hardware.org/?probe=5b9b648342) | Aug 02, 2024 |
| Packard Be... | EasyNote TJ65               | Notebook    | [e306fe8ecc](https://linux-hardware.org/?probe=e306fe8ecc) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [0eb7d255f3](https://linux-hardware.org/?probe=0eb7d255f3) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9f72b57572](https://linux-hardware.org/?probe=9f72b57572) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [0f9769121d](https://linux-hardware.org/?probe=0f9769121d) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [ed267f1e53](https://linux-hardware.org/?probe=ed267f1e53) | Aug 02, 2024 |
| Alienware     | 0J560M A03                  | Desktop     | [59b665b374](https://linux-hardware.org/?probe=59b665b374) | Aug 02, 2024 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [8a7ddf4baf](https://linux-hardware.org/?probe=8a7ddf4baf) | Aug 01, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [7bcbf232f8](https://linux-hardware.org/?probe=7bcbf232f8) | Aug 01, 2024 |
| ASUSTek       | GA15DH                      | Desktop     | [20c5bb0dcd](https://linux-hardware.org/?probe=20c5bb0dcd) | Aug 01, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [97eeb04e17](https://linux-hardware.org/?probe=97eeb04e17) | Jul 31, 2024 |
| Biostar       | A68MHE                      | Desktop     | [a5f30c5c54](https://linux-hardware.org/?probe=a5f30c5c54) | Jul 31, 2024 |
| Dell          | Latitude E4300              | Notebook    | [0f4d8b2b9f](https://linux-hardware.org/?probe=0f4d8b2b9f) | Jul 30, 2024 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [3476d0940e](https://linux-hardware.org/?probe=3476d0940e) | Jul 30, 2024 |
| Toshiba       | Satellite C655D             | Notebook    | [e81fee8a6c](https://linux-hardware.org/?probe=e81fee8a6c) | Jul 29, 2024 |
| PCWare        | IPMH61R1                    | Desktop     | [c865528f1c](https://linux-hardware.org/?probe=c865528f1c) | Jul 29, 2024 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ef85a1e7](https://linux-hardware.org/?probe=48ef85a1e7) | Jul 29, 2024 |
| Chuwi         | HeroBox                     | Mini pc     | [c4f00ac58a](https://linux-hardware.org/?probe=c4f00ac58a) | Jul 29, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [30bb835251](https://linux-hardware.org/?probe=30bb835251) | Jul 28, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [acb85bcfe6](https://linux-hardware.org/?probe=acb85bcfe6) | Jul 28, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [bc2b62ae1b](https://linux-hardware.org/?probe=bc2b62ae1b) | Jul 27, 2024 |
| HP            | 339A                        | Desktop     | [ea89e47f4e](https://linux-hardware.org/?probe=ea89e47f4e) | Jul 27, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [d1a65ccc57](https://linux-hardware.org/?probe=d1a65ccc57) | Jul 26, 2024 |
| MSI           | GP75 Leopard 10SFK          | Notebook    | [71a1b61be1](https://linux-hardware.org/?probe=71a1b61be1) | Jul 25, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [b166d93b76](https://linux-hardware.org/?probe=b166d93b76) | Jul 24, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [1d54fe19db](https://linux-hardware.org/?probe=1d54fe19db) | Jul 24, 2024 |
| Dell          | Latitude 3420               | Notebook    | [e19f560b4b](https://linux-hardware.org/?probe=e19f560b4b) | Jul 24, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [fea5573927](https://linux-hardware.org/?probe=fea5573927) | Jul 23, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [d2e4abf5f4](https://linux-hardware.org/?probe=d2e4abf5f4) | Jul 23, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [0a7c685c42](https://linux-hardware.org/?probe=0a7c685c42) | Jul 23, 2024 |
| Samsung       | 275E4E/275E5E               | Notebook    | [76664dd4c1](https://linux-hardware.org/?probe=76664dd4c1) | Jul 23, 2024 |
| ONKYO         | ONKYOPC                     | Notebook    | [09b23f2d51](https://linux-hardware.org/?probe=09b23f2d51) | Jul 23, 2024 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [fb251e81e1](https://linux-hardware.org/?probe=fb251e81e1) | Jul 22, 2024 |
| Dell          | Latitude E5570              | Notebook    | [0165747ee0](https://linux-hardware.org/?probe=0165747ee0) | Jul 22, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [310f665bb6](https://linux-hardware.org/?probe=310f665bb6) | Jul 22, 2024 |
| Dell          | Latitude E6400              | Notebook    | [39f3a73c4e](https://linux-hardware.org/?probe=39f3a73c4e) | Jul 21, 2024 |
| Dell          | Latitude E5540              | Notebook    | [34bee156ca](https://linux-hardware.org/?probe=34bee156ca) | Jul 21, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [43941683fc](https://linux-hardware.org/?probe=43941683fc) | Jul 21, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9340309f3d](https://linux-hardware.org/?probe=9340309f3d) | Jul 21, 2024 |
| Samsung       | N150P                       | Notebook    | [29634e5ef3](https://linux-hardware.org/?probe=29634e5ef3) | Jul 21, 2024 |
| Intel         | H61                         | Desktop     | [659abbba46](https://linux-hardware.org/?probe=659abbba46) | Jul 21, 2024 |
| HP            | G62                         | Notebook    | [212822c040](https://linux-hardware.org/?probe=212822c040) | Jul 20, 2024 |
| Acer          | Aspire V5-561G              | Notebook    | [42de9c9a13](https://linux-hardware.org/?probe=42de9c9a13) | Jul 20, 2024 |
| HP            | 18E4                        | Desktop     | [bcfb2d82b4](https://linux-hardware.org/?probe=bcfb2d82b4) | Jul 20, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [f64e5045de](https://linux-hardware.org/?probe=f64e5045de) | Jul 20, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [e932f08d1f](https://linux-hardware.org/?probe=e932f08d1f) | Jul 20, 2024 |
| HC            | HCAR357-MI V1.0             | Desktop     | [5c18bea34f](https://linux-hardware.org/?probe=5c18bea34f) | Jul 20, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [fdda23379d](https://linux-hardware.org/?probe=fdda23379d) | Jul 20, 2024 |
| HP            | 8924 0101                   | All in one  | [5f8fb2667f](https://linux-hardware.org/?probe=5f8fb2667f) | Jul 19, 2024 |
| HP            | 339A                        | Desktop     | [2156013e3f](https://linux-hardware.org/?probe=2156013e3f) | Jul 19, 2024 |
| Dell          | G5 5590                     | Notebook    | [32e5d24257](https://linux-hardware.org/?probe=32e5d24257) | Jul 18, 2024 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [af6e4e0234](https://linux-hardware.org/?probe=af6e4e0234) | Jul 18, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [e033fa91df](https://linux-hardware.org/?probe=e033fa91df) | Jul 18, 2024 |
| HP            | 0A68h                       | Desktop     | [6a608ec580](https://linux-hardware.org/?probe=6a608ec580) | Jul 17, 2024 |
| Biostar       | A320MH                      | Desktop     | [89ca8f23b5](https://linux-hardware.org/?probe=89ca8f23b5) | Jul 17, 2024 |
| HP            | Presario CQ57               | Notebook    | [08d89f4239](https://linux-hardware.org/?probe=08d89f4239) | Jul 17, 2024 |
| MSI           | MS-1759                     | Notebook    | [671a5518e5](https://linux-hardware.org/?probe=671a5518e5) | Jul 17, 2024 |
| AIR           | CX28000W                    | Notebook    | [16137fe940](https://linux-hardware.org/?probe=16137fe940) | Jul 16, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [b1904ce50a](https://linux-hardware.org/?probe=b1904ce50a) | Jul 16, 2024 |
| Toshiba       | Satellite L645              | Notebook    | [7c46019cc3](https://linux-hardware.org/?probe=7c46019cc3) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [f43f547c9f](https://linux-hardware.org/?probe=f43f547c9f) | Jul 16, 2024 |
| Dell          | Latitude 7480               | Notebook    | [c5b3a19dc6](https://linux-hardware.org/?probe=c5b3a19dc6) | Jul 16, 2024 |
| ASUSTek       | VM40B                       | Desktop     | [f279df4081](https://linux-hardware.org/?probe=f279df4081) | Jul 15, 2024 |
| Dell          | Latitude E6420              | Notebook    | [ed2dfd4697](https://linux-hardware.org/?probe=ed2dfd4697) | Jul 15, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [114f593d2e](https://linux-hardware.org/?probe=114f593d2e) | Jul 14, 2024 |
| Valve         | Galileo                     | Notebook    | [c81b1ef308](https://linux-hardware.org/?probe=c81b1ef308) | Jul 14, 2024 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [b75277d22d](https://linux-hardware.org/?probe=b75277d22d) | Jul 13, 2024 |
| ATOPNUC       | MA90                        | Mini pc     | [3085542a35](https://linux-hardware.org/?probe=3085542a35) | Jul 13, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [02fe034f42](https://linux-hardware.org/?probe=02fe034f42) | Jul 13, 2024 |
| Dell          | Latitude E6430s             | Notebook    | [e3f7513a9e](https://linux-hardware.org/?probe=e3f7513a9e) | Jul 13, 2024 |
| Dell          | 0MF252                      | Desktop     | [2451c65503](https://linux-hardware.org/?probe=2451c65503) | Jul 13, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [958ce79a36](https://linux-hardware.org/?probe=958ce79a36) | Jul 12, 2024 |
| PCBOX         | Kant                        | Desktop     | [15c4a5cbe5](https://linux-hardware.org/?probe=15c4a5cbe5) | Jul 12, 2024 |
| Unknown       | Unknown                     | Notebook    | [d05d63f9bd](https://linux-hardware.org/?probe=d05d63f9bd) | Jul 11, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [617fd7c71a](https://linux-hardware.org/?probe=617fd7c71a) | Jul 11, 2024 |
| ASRock        | G31M-S                      | Desktop     | [91753f29af](https://linux-hardware.org/?probe=91753f29af) | Jul 11, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [a95b373628](https://linux-hardware.org/?probe=a95b373628) | Jul 11, 2024 |
| Acer          | Aspire ES1-732              | Notebook    | [dd239232f2](https://linux-hardware.org/?probe=dd239232f2) | Jul 11, 2024 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [d840119eb6](https://linux-hardware.org/?probe=d840119eb6) | Jul 11, 2024 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [973f1cb205](https://linux-hardware.org/?probe=973f1cb205) | Jul 10, 2024 |
| Lenovo        | ThinkPad P50 20EQS37300     | Notebook    | [2fc66ed5e8](https://linux-hardware.org/?probe=2fc66ed5e8) | Jul 10, 2024 |
| Gigabyte      | Z490 VISION G               | Desktop     | [bf2543da0b](https://linux-hardware.org/?probe=bf2543da0b) | Jul 10, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [05c079d282](https://linux-hardware.org/?probe=05c079d282) | Jul 09, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [7ec7af2a2b](https://linux-hardware.org/?probe=7ec7af2a2b) | Jul 09, 2024 |
| Shuttle       | FZ270                       | Desktop     | [434e447cc2](https://linux-hardware.org/?probe=434e447cc2) | Jul 09, 2024 |
| Gigabyte      | P41T-D3                     | Desktop     | [cc80c6a7cb](https://linux-hardware.org/?probe=cc80c6a7cb) | Jul 09, 2024 |
| HP            | Presario CQ56               | Notebook    | [1de5f0e8b0](https://linux-hardware.org/?probe=1de5f0e8b0) | Jul 07, 2024 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [4df9a2e9f2](https://linux-hardware.org/?probe=4df9a2e9f2) | Jul 07, 2024 |
| Lenovo        | ThinkPad 11e 20DAS0VG00     | Notebook    | [944f1cf225](https://linux-hardware.org/?probe=944f1cf225) | Jul 07, 2024 |
| MSI           | KA790GX                     | Desktop     | [8c3c570301](https://linux-hardware.org/?probe=8c3c570301) | Jul 07, 2024 |
| HP            | 1493                        | Desktop     | [04b4232ad9](https://linux-hardware.org/?probe=04b4232ad9) | Jul 07, 2024 |
| Dell          | Latitude 7490               | Notebook    | [7cd32fcab4](https://linux-hardware.org/?probe=7cd32fcab4) | Jul 07, 2024 |
| Dell          | Inspiron 1564               | Notebook    | [3c5c95d839](https://linux-hardware.org/?probe=3c5c95d839) | Jul 07, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [5730fa5e66](https://linux-hardware.org/?probe=5730fa5e66) | Jul 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [972c0527aa](https://linux-hardware.org/?probe=972c0527aa) | Jul 07, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [fc381ab0cd](https://linux-hardware.org/?probe=fc381ab0cd) | Jul 07, 2024 |
| Lenovo        | ThinkPad T440p 20AWA1PKA... | Notebook    | [5f96cb15b8](https://linux-hardware.org/?probe=5f96cb15b8) | Jul 07, 2024 |
| GPU Compan... | GWNC31514                   | Notebook    | [866bc18b85](https://linux-hardware.org/?probe=866bc18b85) | Jul 07, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [c5062c2b4e](https://linux-hardware.org/?probe=c5062c2b4e) | Jul 07, 2024 |
| ECS           | H61H2-M2                    | Desktop     | [123fb7680a](https://linux-hardware.org/?probe=123fb7680a) | Jul 07, 2024 |
| Gigabyte      | H410M H                     | Desktop     | [4a179a1ec9](https://linux-hardware.org/?probe=4a179a1ec9) | Jul 07, 2024 |
| MSI           | 2AE0                        | Desktop     | [a8d3498fb0](https://linux-hardware.org/?probe=a8d3498fb0) | Jul 06, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6ec43479a8](https://linux-hardware.org/?probe=6ec43479a8) | Jul 06, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [0f5813286e](https://linux-hardware.org/?probe=0f5813286e) | Jul 06, 2024 |
| Acer          | Aspire ES1-731              | Notebook    | [c34f46808e](https://linux-hardware.org/?probe=c34f46808e) | Jul 06, 2024 |
| ASUSTek       | K53E                        | Notebook    | [d3a0f69d1b](https://linux-hardware.org/?probe=d3a0f69d1b) | Jul 06, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [6e435ae17c](https://linux-hardware.org/?probe=6e435ae17c) | Jul 06, 2024 |
| ASRock        | H71M-DGS                    | Desktop     | [53971fc966](https://linux-hardware.org/?probe=53971fc966) | Jul 06, 2024 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bb1db7e4cf](https://linux-hardware.org/?probe=bb1db7e4cf) | Jul 06, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [09991bde50](https://linux-hardware.org/?probe=09991bde50) | Jul 06, 2024 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [b541df6068](https://linux-hardware.org/?probe=b541df6068) | Jul 06, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [2ee11e7de8](https://linux-hardware.org/?probe=2ee11e7de8) | Jul 06, 2024 |
| ASUSTek       | X510UAR                     | Notebook    | [c93c6cabe1](https://linux-hardware.org/?probe=c93c6cabe1) | Jul 06, 2024 |
| HP            | 1497                        | Desktop     | [be525ac03c](https://linux-hardware.org/?probe=be525ac03c) | Jul 05, 2024 |
| Dell          | 0GXM1W A00                  | Desktop     | [e44c5d6c4f](https://linux-hardware.org/?probe=e44c5d6c4f) | Jul 05, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f8e0a5453b](https://linux-hardware.org/?probe=f8e0a5453b) | Jul 05, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [e025d87bfa](https://linux-hardware.org/?probe=e025d87bfa) | Jul 05, 2024 |
| MSI           | H270 GAMING M3              | Desktop     | [117d7740f8](https://linux-hardware.org/?probe=117d7740f8) | Jul 05, 2024 |
| Dell          | Latitude E5530 vPro         | Notebook    | [0aee03627c](https://linux-hardware.org/?probe=0aee03627c) | Jul 05, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [61d934db3e](https://linux-hardware.org/?probe=61d934db3e) | Jul 05, 2024 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [e1fab4870a](https://linux-hardware.org/?probe=e1fab4870a) | Jul 05, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [32be2b30f2](https://linux-hardware.org/?probe=32be2b30f2) | Jul 05, 2024 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | Desktop     | [f45604d7f6](https://linux-hardware.org/?probe=f45604d7f6) | Jul 05, 2024 |
| Acer          | Aspire TC-875 V:1.0         | Desktop     | [56bb0a8004](https://linux-hardware.org/?probe=56bb0a8004) | Jul 05, 2024 |
| ASRock        | B365M IB-R                  | Desktop     | [b9fe5565b5](https://linux-hardware.org/?probe=b9fe5565b5) | Jul 05, 2024 |
| Dell          | Latitude E6400              | Notebook    | [e45fd27a11](https://linux-hardware.org/?probe=e45fd27a11) | Jul 04, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [54a8595e70](https://linux-hardware.org/?probe=54a8595e70) | Jul 04, 2024 |
| MSI           | PRO B760M-P                 | Desktop     | [bcbbe706a6](https://linux-hardware.org/?probe=bcbbe706a6) | Jul 04, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [e62a05f921](https://linux-hardware.org/?probe=e62a05f921) | Jul 04, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [c2f7345f39](https://linux-hardware.org/?probe=c2f7345f39) | Jul 04, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [abc15903ab](https://linux-hardware.org/?probe=abc15903ab) | Jul 04, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [647ca9ecb0](https://linux-hardware.org/?probe=647ca9ecb0) | Jul 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5b82d8232e](https://linux-hardware.org/?probe=5b82d8232e) | Jul 04, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [6df32aa15e](https://linux-hardware.org/?probe=6df32aa15e) | Jul 04, 2024 |
| Gigabyte      | P17FR5                      | Notebook    | [3e99f8eb2c](https://linux-hardware.org/?probe=3e99f8eb2c) | Jul 04, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [44645f9599](https://linux-hardware.org/?probe=44645f9599) | Jul 04, 2024 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [6d10ca7208](https://linux-hardware.org/?probe=6d10ca7208) | Jul 04, 2024 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [84a42d41f7](https://linux-hardware.org/?probe=84a42d41f7) | Jul 04, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [72c4059807](https://linux-hardware.org/?probe=72c4059807) | Jul 04, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c5052cf8b8](https://linux-hardware.org/?probe=c5052cf8b8) | Jul 04, 2024 |
| Lenovo        | ThinkPad L540 20AUS28100    | Notebook    | [b59c2a69f9](https://linux-hardware.org/?probe=b59c2a69f9) | Jul 04, 2024 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [d6e0c0e321](https://linux-hardware.org/?probe=d6e0c0e321) | Jul 04, 2024 |
| HP            | 8954                        | Desktop     | [e4a7684a2a](https://linux-hardware.org/?probe=e4a7684a2a) | Jul 03, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [cad2cf8bff](https://linux-hardware.org/?probe=cad2cf8bff) | Jul 03, 2024 |
| Dell          | 0K06NC A00                  | All in one  | [1aafe0b525](https://linux-hardware.org/?probe=1aafe0b525) | Jul 03, 2024 |
| Dell          | 0D28YY A03                  | Desktop     | [e4581c717c](https://linux-hardware.org/?probe=e4581c717c) | Jul 03, 2024 |
| GEEKOM        | A8                          | Desktop     | [30b6883c52](https://linux-hardware.org/?probe=30b6883c52) | Jul 02, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [316499457a](https://linux-hardware.org/?probe=316499457a) | Jul 01, 2024 |
| HP            | ProBook 6450b               | Notebook    | [719cb2b099](https://linux-hardware.org/?probe=719cb2b099) | Jul 01, 2024 |
| HP            | 0A08h                       | Desktop     | [3c13100cd4](https://linux-hardware.org/?probe=3c13100cd4) | Jul 01, 2024 |
| HP            | Compaq 6910p                | Notebook    | [2ba8c6fe46](https://linux-hardware.org/?probe=2ba8c6fe46) | Jul 01, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [3f4c9aeb8b](https://linux-hardware.org/?probe=3f4c9aeb8b) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b4793633f9](https://linux-hardware.org/?probe=b4793633f9) | Jul 01, 2024 |
| MSI           | Thin GF63 12VE              | Notebook    | [55256ad8b1](https://linux-hardware.org/?probe=55256ad8b1) | Jul 01, 2024 |
| Dell          | Latitude 3340               | Notebook    | [792e2d71b0](https://linux-hardware.org/?probe=792e2d71b0) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4232ba0ac9](https://linux-hardware.org/?probe=4232ba0ac9) | Jul 01, 2024 |
| ASUSTek       | X99-A/USB                   | Desktop     | [f75ecb76e4](https://linux-hardware.org/?probe=f75ecb76e4) | Jun 30, 2024 |
| Unknown       | FLASH i7-11800H PLUS        | Desktop     | [bc4a7261d4](https://linux-hardware.org/?probe=bc4a7261d4) | Jun 30, 2024 |
| ASUSTek       | T100TAF                     | Notebook    | [05c827f54c](https://linux-hardware.org/?probe=05c827f54c) | Jun 29, 2024 |
| Lenovo        | ThinkPad T420s 4174W4T      | Notebook    | [d234dada87](https://linux-hardware.org/?probe=d234dada87) | Jun 29, 2024 |
| MSI           | MS-7392                     | Desktop     | [fbfd1ecd6e](https://linux-hardware.org/?probe=fbfd1ecd6e) | Jun 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a6e35dde0d](https://linux-hardware.org/?probe=a6e35dde0d) | Jun 29, 2024 |
| MSI           | A88XM-E35                   | Desktop     | [d77265cc89](https://linux-hardware.org/?probe=d77265cc89) | Jun 29, 2024 |
| Gigabyte      | P85-D3                      | Desktop     | [d3f906eda8](https://linux-hardware.org/?probe=d3f906eda8) | Jun 29, 2024 |
| Chuwi         | AeroBook Plus               | Notebook    | [5d09b59053](https://linux-hardware.org/?probe=5d09b59053) | Jun 29, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [99b998a45a](https://linux-hardware.org/?probe=99b998a45a) | Jun 28, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [7bfeaeecf5](https://linux-hardware.org/?probe=7bfeaeecf5) | Jun 28, 2024 |
| HP            | 0A98h                       | Desktop     | [b67771e6ef](https://linux-hardware.org/?probe=b67771e6ef) | Jun 28, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [9964f3c440](https://linux-hardware.org/?probe=9964f3c440) | Jun 28, 2024 |
| Dell          | Latitude E5520              | Notebook    | [2a06da6b0d](https://linux-hardware.org/?probe=2a06da6b0d) | Jun 27, 2024 |
| Acer          | Aspire GX-781               | Desktop     | [137ae977af](https://linux-hardware.org/?probe=137ae977af) | Jun 27, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [752d814af3](https://linux-hardware.org/?probe=752d814af3) | Jun 27, 2024 |
| Positivo      | UW3                         | Notebook    | [f37c824400](https://linux-hardware.org/?probe=f37c824400) | Jun 27, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [aa123bef20](https://linux-hardware.org/?probe=aa123bef20) | Jun 26, 2024 |
| HP            | Pavilion dm1                | Notebook    | [46eca8c33a](https://linux-hardware.org/?probe=46eca8c33a) | Jun 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a2804074c3](https://linux-hardware.org/?probe=a2804074c3) | Jun 26, 2024 |
| ASUSTek       | P5GC-MX                     | Desktop     | [23b3a67905](https://linux-hardware.org/?probe=23b3a67905) | Jun 25, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [c7fba61395](https://linux-hardware.org/?probe=c7fba61395) | Jun 25, 2024 |
| NEC Comput... | PC-VJ26MBZCF                | Notebook    | [8ba01f3c6c](https://linux-hardware.org/?probe=8ba01f3c6c) | Jun 25, 2024 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [617f1b7020](https://linux-hardware.org/?probe=617f1b7020) | Jun 25, 2024 |
| Unknown       | NH4CU53                     | Notebook    | [c2afeac9a3](https://linux-hardware.org/?probe=c2afeac9a3) | Jun 23, 2024 |
| HP            | 304Bh                       | Desktop     | [385a52ece1](https://linux-hardware.org/?probe=385a52ece1) | Jun 23, 2024 |
| ASRock        | N68-S3 FX                   | Desktop     | [c67bf51171](https://linux-hardware.org/?probe=c67bf51171) | Jun 22, 2024 |
| MSI           | 785GTM-E45                  | Desktop     | [50af260321](https://linux-hardware.org/?probe=50af260321) | Jun 22, 2024 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [8e48fda0ee](https://linux-hardware.org/?probe=8e48fda0ee) | Jun 22, 2024 |
| MSI           | G41M-P33 Combo              | Desktop     | [dd6b3518ed](https://linux-hardware.org/?probe=dd6b3518ed) | Jun 22, 2024 |
| Pegatron      | NARRA5                      | Desktop     | [3f2465cb2f](https://linux-hardware.org/?probe=3f2465cb2f) | Jun 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [03d8e18e1c](https://linux-hardware.org/?probe=03d8e18e1c) | Jun 22, 2024 |
| ASRock        | J3355B-ITX                  | Desktop     | [fe967c69f9](https://linux-hardware.org/?probe=fe967c69f9) | Jun 21, 2024 |
| Lenovo        | ThinkPad T490 20N3SGFY00    | Notebook    | [78506c6bed](https://linux-hardware.org/?probe=78506c6bed) | Jun 21, 2024 |
| Positivo      | Mobile                      | Notebook    | [927af43a1e](https://linux-hardware.org/?probe=927af43a1e) | Jun 21, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [157fc29a20](https://linux-hardware.org/?probe=157fc29a20) | Jun 21, 2024 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [ccf2b3ec9d](https://linux-hardware.org/?probe=ccf2b3ec9d) | Jun 20, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [82c23cabe2](https://linux-hardware.org/?probe=82c23cabe2) | Jun 20, 2024 |
| Intel         | H61                         | Desktop     | [da1a1d129a](https://linux-hardware.org/?probe=da1a1d129a) | Jun 19, 2024 |
| HP            | 0A98h                       | Desktop     | [0c6652df6e](https://linux-hardware.org/?probe=0c6652df6e) | Jun 19, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [33df6bfe30](https://linux-hardware.org/?probe=33df6bfe30) | Jun 19, 2024 |
| Packard Be... | EasyNote_MX52-B-702NCD      | Notebook    | [a701f521e6](https://linux-hardware.org/?probe=a701f521e6) | Jun 18, 2024 |
| ASUSTek       | N76VB                       | Notebook    | [04add030f4](https://linux-hardware.org/?probe=04add030f4) | Jun 18, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [540399cfff](https://linux-hardware.org/?probe=540399cfff) | Jun 18, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d23fd860dc](https://linux-hardware.org/?probe=d23fd860dc) | Jun 17, 2024 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [1f1d42d470](https://linux-hardware.org/?probe=1f1d42d470) | Jun 17, 2024 |
| Intel         | B85                         | Desktop     | [83f3947827](https://linux-hardware.org/?probe=83f3947827) | Jun 17, 2024 |
| HP            | 18E4                        | Desktop     | [aa89247575](https://linux-hardware.org/?probe=aa89247575) | Jun 16, 2024 |
| Gigabyte      | RC14UD                      | Notebook    | [70d3f45ff7](https://linux-hardware.org/?probe=70d3f45ff7) | Jun 15, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [1688f3e6ec](https://linux-hardware.org/?probe=1688f3e6ec) | Jun 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [fd4fa297ee](https://linux-hardware.org/?probe=fd4fa297ee) | Jun 15, 2024 |
| Intel         | H61 V1.6B                   | Desktop     | [930c36f35d](https://linux-hardware.org/?probe=930c36f35d) | Jun 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3cb9c14764](https://linux-hardware.org/?probe=3cb9c14764) | Jun 15, 2024 |
| MSI           | Z97 GAMING 5                | Desktop     | [bd481829f1](https://linux-hardware.org/?probe=bd481829f1) | Jun 15, 2024 |
| MSI           | GP75 Leopard 10SFK          | Notebook    | [440f78fb36](https://linux-hardware.org/?probe=440f78fb36) | Jun 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [acd6f7384f](https://linux-hardware.org/?probe=acd6f7384f) | Jun 14, 2024 |
| Intel         | H61                         | Desktop     | [593dc22666](https://linux-hardware.org/?probe=593dc22666) | Jun 12, 2024 |
| HP            | 2B0C                        | All in one  | [ce31398bf7](https://linux-hardware.org/?probe=ce31398bf7) | Jun 12, 2024 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [f153cb875f](https://linux-hardware.org/?probe=f153cb875f) | Jun 12, 2024 |
| Lenovo        | ThinkPad T520 42404DG       | Notebook    | [0ebf60097e](https://linux-hardware.org/?probe=0ebf60097e) | Jun 11, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [61ed5fb52e](https://linux-hardware.org/?probe=61ed5fb52e) | Jun 11, 2024 |
| Lenovo        | ThinkPad X201 3680F7G       | Notebook    | [cd02d8af64](https://linux-hardware.org/?probe=cd02d8af64) | Jun 11, 2024 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | Desktop     | [c779d45043](https://linux-hardware.org/?probe=c779d45043) | Jun 11, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [ebf60ad1d4](https://linux-hardware.org/?probe=ebf60ad1d4) | Jun 11, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [186867bd2c](https://linux-hardware.org/?probe=186867bd2c) | Jun 10, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [e410fbc83c](https://linux-hardware.org/?probe=e410fbc83c) | Jun 10, 2024 |
| Toshiba       | Satellite C650              | Notebook    | [5bc2771fec](https://linux-hardware.org/?probe=5bc2771fec) | Jun 10, 2024 |
| HP            | 3398                        | Desktop     | [59527c7be0](https://linux-hardware.org/?probe=59527c7be0) | Jun 10, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | Notebook    | [93ba271535](https://linux-hardware.org/?probe=93ba271535) | Jun 10, 2024 |
| Intel         | Unknown                     | Desktop     | [c4f6ab3dd2](https://linux-hardware.org/?probe=c4f6ab3dd2) | Jun 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [73535f78d4](https://linux-hardware.org/?probe=73535f78d4) | Jun 09, 2024 |
| HP            | 2B36                        | Desktop     | [3f48e6e1f0](https://linux-hardware.org/?probe=3f48e6e1f0) | Jun 09, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [12d93a151d](https://linux-hardware.org/?probe=12d93a151d) | Jun 09, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e526a53470](https://linux-hardware.org/?probe=e526a53470) | Jun 08, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ca6db29fc2](https://linux-hardware.org/?probe=ca6db29fc2) | Jun 08, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [ac98ad5119](https://linux-hardware.org/?probe=ac98ad5119) | Jun 08, 2024 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [02c80e63f3](https://linux-hardware.org/?probe=02c80e63f3) | Jun 08, 2024 |
| Dell          | Precision M4800             | Notebook    | [9ffdda9098](https://linux-hardware.org/?probe=9ffdda9098) | Jun 07, 2024 |
| Dell          | Studio 1537                 | Notebook    | [9c73780c05](https://linux-hardware.org/?probe=9c73780c05) | Jun 07, 2024 |
| Gigabyte      | H410M H V2                  | Desktop     | [20465abb0a](https://linux-hardware.org/?probe=20465abb0a) | Jun 07, 2024 |
| MSI           | A320M PRO-VH                | Desktop     | [569d81676c](https://linux-hardware.org/?probe=569d81676c) | Jun 07, 2024 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [eba6036446](https://linux-hardware.org/?probe=eba6036446) | Jun 07, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [f965df9dc9](https://linux-hardware.org/?probe=f965df9dc9) | Jun 06, 2024 |
| Unknown       | T3 MRD                      | Desktop     | [ce12a5263c](https://linux-hardware.org/?probe=ce12a5263c) | Jun 06, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [6cd669ce9d](https://linux-hardware.org/?probe=6cd669ce9d) | Jun 06, 2024 |
| Intel         | H61                         | Desktop     | [59f9cc58f5](https://linux-hardware.org/?probe=59f9cc58f5) | Jun 05, 2024 |
| Pegatron      | Benicia                     | Desktop     | [6827b37cff](https://linux-hardware.org/?probe=6827b37cff) | Jun 05, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [ed0b846bce](https://linux-hardware.org/?probe=ed0b846bce) | Jun 05, 2024 |
| Lenovo        | B575e 36852BG               | Notebook    | [703312be48](https://linux-hardware.org/?probe=703312be48) | Jun 05, 2024 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [5cd9b65fe2](https://linux-hardware.org/?probe=5cd9b65fe2) | Jun 05, 2024 |
| Biostar       | IH61MF-Q5                   | Desktop     | [85f2d92c2f](https://linux-hardware.org/?probe=85f2d92c2f) | Jun 05, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [a659934c95](https://linux-hardware.org/?probe=a659934c95) | Jun 05, 2024 |
| HP            | 304Ah                       | Desktop     | [d7b5fb1612](https://linux-hardware.org/?probe=d7b5fb1612) | Jun 04, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [8ee6674025](https://linux-hardware.org/?probe=8ee6674025) | Jun 04, 2024 |
| Fujitsu       | LIFEBOOK U9310X             | Convertible | [507ae90408](https://linux-hardware.org/?probe=507ae90408) | Jun 04, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [ebb7d86561](https://linux-hardware.org/?probe=ebb7d86561) | Jun 04, 2024 |
| HP            | 14 Laptop PC                | Notebook    | [5b165f8d7c](https://linux-hardware.org/?probe=5b165f8d7c) | Jun 04, 2024 |
| Acer          | Veriton L4620G v1.0         | Desktop     | [24db2893da](https://linux-hardware.org/?probe=24db2893da) | Jun 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [19a04d6fe8](https://linux-hardware.org/?probe=19a04d6fe8) | Jun 03, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [af058de203](https://linux-hardware.org/?probe=af058de203) | Jun 03, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [3240239bf4](https://linux-hardware.org/?probe=3240239bf4) | Jun 03, 2024 |
| Acer          | Nitro AN517-41              | Notebook    | [541f9885c5](https://linux-hardware.org/?probe=541f9885c5) | Jun 03, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [5c504aa546](https://linux-hardware.org/?probe=5c504aa546) | Jun 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [65c0ac7dbe](https://linux-hardware.org/?probe=65c0ac7dbe) | Jun 03, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [a83bb7fac6](https://linux-hardware.org/?probe=a83bb7fac6) | Jun 03, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [075953fb1c](https://linux-hardware.org/?probe=075953fb1c) | Jun 03, 2024 |
| Toshiba       | Satellite C55D-A            | Notebook    | [057a330a3f](https://linux-hardware.org/?probe=057a330a3f) | Jun 03, 2024 |
| NOBLEX        | E11IS2                      | Notebook    | [327a12cc82](https://linux-hardware.org/?probe=327a12cc82) | Jun 02, 2024 |
| HP            | Compaq Mini CQ10-400        | Notebook    | [ad9a195e34](https://linux-hardware.org/?probe=ad9a195e34) | Jun 02, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b29da130f8](https://linux-hardware.org/?probe=b29da130f8) | Jun 01, 2024 |
| HP            | Pavilion g6                 | Notebook    | [824387472c](https://linux-hardware.org/?probe=824387472c) | Jun 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [2c3cb89d8d](https://linux-hardware.org/?probe=2c3cb89d8d) | Jun 01, 2024 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [b5b1e4990e](https://linux-hardware.org/?probe=b5b1e4990e) | Jun 01, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [41250af6e1](https://linux-hardware.org/?probe=41250af6e1) | Jun 01, 2024 |
| Medion        | E11201                      | Notebook    | [f71bc55f73](https://linux-hardware.org/?probe=f71bc55f73) | May 31, 2024 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [da55eec4ab](https://linux-hardware.org/?probe=da55eec4ab) | May 31, 2024 |
| Microtech     | CoreBook                    | Notebook    | [d6615711df](https://linux-hardware.org/?probe=d6615711df) | May 30, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [6210e40c07](https://linux-hardware.org/?probe=6210e40c07) | May 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [696126a9c6](https://linux-hardware.org/?probe=696126a9c6) | May 29, 2024 |
| ASUSTek       | P9X79 WS                    | Desktop     | [272fdc5776](https://linux-hardware.org/?probe=272fdc5776) | May 29, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [af3d9d57b2](https://linux-hardware.org/?probe=af3d9d57b2) | May 29, 2024 |
| Dell          | Latitude E5550              | Notebook    | [7a9c252c6c](https://linux-hardware.org/?probe=7a9c252c6c) | May 29, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [4b5c79152f](https://linux-hardware.org/?probe=4b5c79152f) | May 29, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [1c6bc44029](https://linux-hardware.org/?probe=1c6bc44029) | May 29, 2024 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [34f894fbbe](https://linux-hardware.org/?probe=34f894fbbe) | May 29, 2024 |
| MACHINIST     | E5-K9 V2.1                  | Desktop     | [5d058e6d3e](https://linux-hardware.org/?probe=5d058e6d3e) | May 29, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [13fae37ce0](https://linux-hardware.org/?probe=13fae37ce0) | May 29, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [2835662b9a](https://linux-hardware.org/?probe=2835662b9a) | May 28, 2024 |
| Dell          | 0K83V0 A00                  | Desktop     | [6def61be90](https://linux-hardware.org/?probe=6def61be90) | May 27, 2024 |
| Biostar       | B550GTQ                     | Desktop     | [285d09979c](https://linux-hardware.org/?probe=285d09979c) | May 27, 2024 |
| Gigabyte      | B760 DS3H DDR4              | Desktop     | [6f84904cc3](https://linux-hardware.org/?probe=6f84904cc3) | May 27, 2024 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [740702872c](https://linux-hardware.org/?probe=740702872c) | May 27, 2024 |
| HP            | ZBook 17                    | Notebook    | [3f754c6dda](https://linux-hardware.org/?probe=3f754c6dda) | May 25, 2024 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [5e056a0de3](https://linux-hardware.org/?probe=5e056a0de3) | May 25, 2024 |
| HP            | EPROM DATA AREA             | Notebook    | [0e28fcd875](https://linux-hardware.org/?probe=0e28fcd875) | May 24, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3cbc575f22](https://linux-hardware.org/?probe=3cbc575f22) | May 24, 2024 |
| PCWare        | IPMH110G-DDR3               | Desktop     | [583ce9e1b1](https://linux-hardware.org/?probe=583ce9e1b1) | May 24, 2024 |
| Lenovo        | ThinkPad SL510 2847CZU      | Notebook    | [eec29ec098](https://linux-hardware.org/?probe=eec29ec098) | May 24, 2024 |
| Sony          | VPCEE47FJ                   | Notebook    | [33e7fc3dcf](https://linux-hardware.org/?probe=33e7fc3dcf) | May 22, 2024 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [7fd5b705f5](https://linux-hardware.org/?probe=7fd5b705f5) | May 21, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c95d40f047](https://linux-hardware.org/?probe=c95d40f047) | May 21, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2101f14aa7](https://linux-hardware.org/?probe=2101f14aa7) | May 20, 2024 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [9bae5aee55](https://linux-hardware.org/?probe=9bae5aee55) | May 20, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [58a289770a](https://linux-hardware.org/?probe=58a289770a) | May 20, 2024 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [15c0b89aa9](https://linux-hardware.org/?probe=15c0b89aa9) | May 20, 2024 |
| Dell          | 0G3HR7 A00                  | Desktop     | [8e85e2f4cb](https://linux-hardware.org/?probe=8e85e2f4cb) | May 20, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | Notebook    | [630273772a](https://linux-hardware.org/?probe=630273772a) | May 19, 2024 |
| ASUSTek       | X55A                        | Notebook    | [08f3d84aeb](https://linux-hardware.org/?probe=08f3d84aeb) | May 19, 2024 |
| Standard      | ECT                         | Notebook    | [584581a35c](https://linux-hardware.org/?probe=584581a35c) | May 19, 2024 |
| Dell          | Precision 7530              | Notebook    | [96ee9bf811](https://linux-hardware.org/?probe=96ee9bf811) | May 19, 2024 |
| Lenovo        | ThinkPad P70 20ER000BGE     | Notebook    | [3b9c970a19](https://linux-hardware.org/?probe=3b9c970a19) | May 19, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [71b0f12af8](https://linux-hardware.org/?probe=71b0f12af8) | May 19, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [002b703f8a](https://linux-hardware.org/?probe=002b703f8a) | May 18, 2024 |
| Lenovo        | G770 1037                   | Notebook    | [81fd5a2b86](https://linux-hardware.org/?probe=81fd5a2b86) | May 18, 2024 |
| HP            | 0AECh D                     | Desktop     | [7173a4bf88](https://linux-hardware.org/?probe=7173a4bf88) | May 18, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4813119a7b](https://linux-hardware.org/?probe=4813119a7b) | May 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [62962b0cec](https://linux-hardware.org/?probe=62962b0cec) | May 17, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [d7bb8a4ea8](https://linux-hardware.org/?probe=d7bb8a4ea8) | May 17, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [cfad66c8d2](https://linux-hardware.org/?probe=cfad66c8d2) | May 16, 2024 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [476306fee7](https://linux-hardware.org/?probe=476306fee7) | May 15, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [0891be8a65](https://linux-hardware.org/?probe=0891be8a65) | May 15, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [1bfcf071de](https://linux-hardware.org/?probe=1bfcf071de) | May 15, 2024 |
| Dell          | Latitude 5400               | Notebook    | [04e76cc72b](https://linux-hardware.org/?probe=04e76cc72b) | May 14, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [f92d0dae39](https://linux-hardware.org/?probe=f92d0dae39) | May 14, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [81cce5b7bc](https://linux-hardware.org/?probe=81cce5b7bc) | May 14, 2024 |
| ECS           | BSWI-D2                     | Desktop     | [d8a75a2978](https://linux-hardware.org/?probe=d8a75a2978) | May 14, 2024 |
| MSI           | H61M-P20                    | Desktop     | [5b41f32988](https://linux-hardware.org/?probe=5b41f32988) | May 14, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [0c023bc45c](https://linux-hardware.org/?probe=0c023bc45c) | May 14, 2024 |
| Lenovo        | ThinkPad L450 20DT0003XS    | Notebook    | [76c50cca06](https://linux-hardware.org/?probe=76c50cca06) | May 13, 2024 |
| Lenovo        | 31900058 STD                | Desktop     | [9eaada84d1](https://linux-hardware.org/?probe=9eaada84d1) | May 13, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1092e372ee](https://linux-hardware.org/?probe=1092e372ee) | May 13, 2024 |
| Lenovo        | E50-80 80J2                 | Notebook    | [a7568cbcc1](https://linux-hardware.org/?probe=a7568cbcc1) | May 13, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [c523181e20](https://linux-hardware.org/?probe=c523181e20) | May 13, 2024 |
| Dell          | 0WR7PY A02                  | Desktop     | [928f4cb666](https://linux-hardware.org/?probe=928f4cb666) | May 12, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [bf17334774](https://linux-hardware.org/?probe=bf17334774) | May 12, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [0483794088](https://linux-hardware.org/?probe=0483794088) | May 11, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [cae77e5760](https://linux-hardware.org/?probe=cae77e5760) | May 11, 2024 |
| HP            | Mini 210-1000               | Notebook    | [74f692bfab](https://linux-hardware.org/?probe=74f692bfab) | May 11, 2024 |
| Dell          | 06D7TR A02                  | Desktop     | [b9cd12037a](https://linux-hardware.org/?probe=b9cd12037a) | May 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e0cb5549df](https://linux-hardware.org/?probe=e0cb5549df) | May 10, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [a826b2d2e4](https://linux-hardware.org/?probe=a826b2d2e4) | May 10, 2024 |
| CYBERGENO     | GENOCYBER                   | Desktop     | [8766fe0791](https://linux-hardware.org/?probe=8766fe0791) | May 10, 2024 |
| HP            | 15                          | Notebook    | [deaab49b1d](https://linux-hardware.org/?probe=deaab49b1d) | May 10, 2024 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [c166fb3c82](https://linux-hardware.org/?probe=c166fb3c82) | May 10, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [c4cd355a10](https://linux-hardware.org/?probe=c4cd355a10) | May 09, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [afd5a26a47](https://linux-hardware.org/?probe=afd5a26a47) | May 09, 2024 |
| HP            | 3396                        | Desktop     | [5e68a536f2](https://linux-hardware.org/?probe=5e68a536f2) | May 09, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [6ce58b40cb](https://linux-hardware.org/?probe=6ce58b40cb) | May 09, 2024 |
| Dell          | 0VNP2H A00                  | Desktop     | [28953f7c6a](https://linux-hardware.org/?probe=28953f7c6a) | May 09, 2024 |
| Getac         | V110G3                      | Notebook    | [f2bd63cfb8](https://linux-hardware.org/?probe=f2bd63cfb8) | May 09, 2024 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2de4ca3c36](https://linux-hardware.org/?probe=2de4ca3c36) | May 09, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [4f2761bde5](https://linux-hardware.org/?probe=4f2761bde5) | May 09, 2024 |
| HP            | Stream x360 Convertible ... | Convertible | [0fd35e9fda](https://linux-hardware.org/?probe=0fd35e9fda) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [098e62d52a](https://linux-hardware.org/?probe=098e62d52a) | May 08, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [fa48702e03](https://linux-hardware.org/?probe=fa48702e03) | May 08, 2024 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [97598b9cc3](https://linux-hardware.org/?probe=97598b9cc3) | May 07, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8c2b9bb30a](https://linux-hardware.org/?probe=8c2b9bb30a) | May 07, 2024 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [263e934dc2](https://linux-hardware.org/?probe=263e934dc2) | May 07, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | Desktop     | [ae1edad2ab](https://linux-hardware.org/?probe=ae1edad2ab) | May 06, 2024 |
| HP            | 8053                        | Desktop     | [06b48e5ec6](https://linux-hardware.org/?probe=06b48e5ec6) | May 06, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [c741f249e2](https://linux-hardware.org/?probe=c741f249e2) | May 06, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [083cfcc0f3](https://linux-hardware.org/?probe=083cfcc0f3) | May 06, 2024 |
| HP            | 650                         | Notebook    | [8fa3b11e2c](https://linux-hardware.org/?probe=8fa3b11e2c) | May 05, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [780a67ef79](https://linux-hardware.org/?probe=780a67ef79) | May 05, 2024 |
| HP            | Compaq 6720s                | Notebook    | [e51bd60d05](https://linux-hardware.org/?probe=e51bd60d05) | May 05, 2024 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [8d1ee988ad](https://linux-hardware.org/?probe=8d1ee988ad) | May 05, 2024 |
| Lenovo        | ThinkPad Edge E530 32597... | Notebook    | [a216f0b6d5](https://linux-hardware.org/?probe=a216f0b6d5) | May 05, 2024 |
| Acer          | Switch SW312-31             | Tablet      | [e7fe09d066](https://linux-hardware.org/?probe=e7fe09d066) | May 04, 2024 |
| Lenovo        | ThinkPad T520 4243W29       | Notebook    | [b1e4dde68e](https://linux-hardware.org/?probe=b1e4dde68e) | May 04, 2024 |
| Dell          | 0R6PCT A01                  | Desktop     | [61f596b724](https://linux-hardware.org/?probe=61f596b724) | May 04, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [64b195310b](https://linux-hardware.org/?probe=64b195310b) | May 04, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [ea3a8f97a7](https://linux-hardware.org/?probe=ea3a8f97a7) | May 04, 2024 |
| HP            | 339A                        | Desktop     | [a5f44d3bdb](https://linux-hardware.org/?probe=a5f44d3bdb) | May 04, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [15375b5d97](https://linux-hardware.org/?probe=15375b5d97) | May 04, 2024 |
| HP            | 246                         | Notebook    | [83140d67e2](https://linux-hardware.org/?probe=83140d67e2) | May 03, 2024 |
| ASUSTek       | K8V-MX                      | Desktop     | [64054e7bf3](https://linux-hardware.org/?probe=64054e7bf3) | May 03, 2024 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [dd201d321b](https://linux-hardware.org/?probe=dd201d321b) | May 03, 2024 |
| ASUSTek       | X751SA                      | Notebook    | [7dadfc10b4](https://linux-hardware.org/?probe=7dadfc10b4) | May 03, 2024 |
| Dell          | 0WR7PY A04                  | Desktop     | [b48e977e84](https://linux-hardware.org/?probe=b48e977e84) | May 03, 2024 |
| Toshiba       | Satellite Pro L650          | Notebook    | [4e0111f9c9](https://linux-hardware.org/?probe=4e0111f9c9) | May 02, 2024 |
| Intel         | B75                         | Desktop     | [4c39b0616d](https://linux-hardware.org/?probe=4c39b0616d) | May 02, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ff4a31241b](https://linux-hardware.org/?probe=ff4a31241b) | May 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [d7c901b5d7](https://linux-hardware.org/?probe=d7c901b5d7) | May 02, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b8a7fbfad1](https://linux-hardware.org/?probe=b8a7fbfad1) | May 01, 2024 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [e7d0c76f65](https://linux-hardware.org/?probe=e7d0c76f65) | May 01, 2024 |
| Packard Be... | EasyNote TJ71               | Notebook    | [f421f823ec](https://linux-hardware.org/?probe=f421f823ec) | May 01, 2024 |
| Google        | Bluebird                    | Notebook    | [75db9dc248](https://linux-hardware.org/?probe=75db9dc248) | May 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [5d6cdceb37](https://linux-hardware.org/?probe=5d6cdceb37) | May 01, 2024 |
| Packard Be... | IMEDIA S2185                | Desktop     | [47d64869d6](https://linux-hardware.org/?probe=47d64869d6) | Apr 30, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [b8ab800603](https://linux-hardware.org/?probe=b8ab800603) | Apr 30, 2024 |
| Acer          | Aspire 7745G                | Notebook    | [1854a5b427](https://linux-hardware.org/?probe=1854a5b427) | Apr 30, 2024 |
| Biostar       | H310MHP                     | Desktop     | [1faa8b5213](https://linux-hardware.org/?probe=1faa8b5213) | Apr 30, 2024 |
| Biostar       | H310MHP                     | Desktop     | [d5bc5a946f](https://linux-hardware.org/?probe=d5bc5a946f) | Apr 30, 2024 |
| Lenovo        | 30C9 SEK0N11843 IOT 3806... | Desktop     | [517daa7c85](https://linux-hardware.org/?probe=517daa7c85) | Apr 30, 2024 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [9c6f64ecd9](https://linux-hardware.org/?probe=9c6f64ecd9) | Apr 29, 2024 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e204e319f8](https://linux-hardware.org/?probe=e204e319f8) | Apr 29, 2024 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [e3c17dccb5](https://linux-hardware.org/?probe=e3c17dccb5) | Apr 29, 2024 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [b1f251b92c](https://linux-hardware.org/?probe=b1f251b92c) | Apr 29, 2024 |
| EVGA          | NF66 2                      | Desktop     | [ef1a49773b](https://linux-hardware.org/?probe=ef1a49773b) | Apr 29, 2024 |
| Google        | Gandof                      | Notebook    | [539c66172b](https://linux-hardware.org/?probe=539c66172b) | Apr 28, 2024 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [51efe9cdc9](https://linux-hardware.org/?probe=51efe9cdc9) | Apr 28, 2024 |
| Dell          | Latitude E6410              | Notebook    | [14cad1b34b](https://linux-hardware.org/?probe=14cad1b34b) | Apr 28, 2024 |
| MSI           | A68HM GRENADE               | Desktop     | [c1a1b60624](https://linux-hardware.org/?probe=c1a1b60624) | Apr 28, 2024 |
| Intel         | D945GCL AAD67193-205        | Desktop     | [2520d8fe1d](https://linux-hardware.org/?probe=2520d8fe1d) | Apr 28, 2024 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [15d91ebe7c](https://linux-hardware.org/?probe=15d91ebe7c) | Apr 28, 2024 |
| Lenovo        | ThinkPad T420 4236L35       | Notebook    | [df6f046778](https://linux-hardware.org/?probe=df6f046778) | Apr 28, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [40c7e6e4a3](https://linux-hardware.org/?probe=40c7e6e4a3) | Apr 28, 2024 |
| Intel         | powered classmate PC MP ... | Notebook    | [7b243a5cb5](https://linux-hardware.org/?probe=7b243a5cb5) | Apr 28, 2024 |
| Lenovo        | ThinkPad T430 23492F5       | Notebook    | [8d26be4497](https://linux-hardware.org/?probe=8d26be4497) | Apr 28, 2024 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | Notebook    | [1856484488](https://linux-hardware.org/?probe=1856484488) | Apr 27, 2024 |
| ASRock        | A320M-DVS R3.0              | Desktop     | [3af9ef3df5](https://linux-hardware.org/?probe=3af9ef3df5) | Apr 27, 2024 |
| MSI           | G31M3-L V2                  | Desktop     | [0a033139d1](https://linux-hardware.org/?probe=0a033139d1) | Apr 27, 2024 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [364be8242a](https://linux-hardware.org/?probe=364be8242a) | Apr 27, 2024 |
| Notebook      | W54BL                       | Notebook    | [adb804fa7f](https://linux-hardware.org/?probe=adb804fa7f) | Apr 27, 2024 |
| Dell          | Latitude 5580               | Notebook    | [e646939794](https://linux-hardware.org/?probe=e646939794) | Apr 27, 2024 |
| Acer          | Aspire ES1-732              | Notebook    | [dda97c8536](https://linux-hardware.org/?probe=dda97c8536) | Apr 26, 2024 |
| Lenovo        | ThinkPad X220 4290RW1       | Notebook    | [306c586e02](https://linux-hardware.org/?probe=306c586e02) | Apr 26, 2024 |
| HP            | ZBook 17 G3 Mobile Works... | Notebook    | [e56b499574](https://linux-hardware.org/?probe=e56b499574) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4f05e448a7](https://linux-hardware.org/?probe=4f05e448a7) | Apr 26, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [bba16f5bc3](https://linux-hardware.org/?probe=bba16f5bc3) | Apr 26, 2024 |
| HP            | 3029h                       | Desktop     | [70cd5cbc22](https://linux-hardware.org/?probe=70cd5cbc22) | Apr 26, 2024 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [edf573962d](https://linux-hardware.org/?probe=edf573962d) | Apr 25, 2024 |
| MAXSUN        | MS-Terminator B550M         | Desktop     | [4960448326](https://linux-hardware.org/?probe=4960448326) | Apr 25, 2024 |
| HP            | 2AF7                        | Desktop     | [dcff3bbb91](https://linux-hardware.org/?probe=dcff3bbb91) | Apr 25, 2024 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [8252280757](https://linux-hardware.org/?probe=8252280757) | Apr 25, 2024 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [826b210e79](https://linux-hardware.org/?probe=826b210e79) | Apr 24, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [8e54a2234f](https://linux-hardware.org/?probe=8e54a2234f) | Apr 24, 2024 |
| HP            | Compaq Presario C700        | Notebook    | [062cdaa3a3](https://linux-hardware.org/?probe=062cdaa3a3) | Apr 24, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [847dec6d8e](https://linux-hardware.org/?probe=847dec6d8e) | Apr 24, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [006661b0c2](https://linux-hardware.org/?probe=006661b0c2) | Apr 23, 2024 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [88daeba4af](https://linux-hardware.org/?probe=88daeba4af) | Apr 23, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [246047bf8e](https://linux-hardware.org/?probe=246047bf8e) | Apr 23, 2024 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [ad67ecab25](https://linux-hardware.org/?probe=ad67ecab25) | Apr 23, 2024 |
| Computer D... | W240EU/W250EUQ/W270EUQ      | Notebook    | [2064944dc4](https://linux-hardware.org/?probe=2064944dc4) | Apr 23, 2024 |
| HP            | 2B0C                        | All in one  | [e84d8e93ef](https://linux-hardware.org/?probe=e84d8e93ef) | Apr 23, 2024 |
| ASUSTek       | K53SD                       | Notebook    | [777dfb666e](https://linux-hardware.org/?probe=777dfb666e) | Apr 23, 2024 |
| Gigabyte      | Z390 UD                     | Desktop     | [36a382f0da](https://linux-hardware.org/?probe=36a382f0da) | Apr 23, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [faae79a749](https://linux-hardware.org/?probe=faae79a749) | Apr 23, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [c495b7e3d7](https://linux-hardware.org/?probe=c495b7e3d7) | Apr 23, 2024 |
| ASRock        | G31M-S                      | Desktop     | [591e58940a](https://linux-hardware.org/?probe=591e58940a) | Apr 22, 2024 |
| Dell          | 0VHXCD A01                  | Desktop     | [4b7a01c41a](https://linux-hardware.org/?probe=4b7a01c41a) | Apr 22, 2024 |
| HP            | Pavilion dv7                | Notebook    | [c7af52e729](https://linux-hardware.org/?probe=c7af52e729) | Apr 21, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a2b7475561](https://linux-hardware.org/?probe=a2b7475561) | Apr 21, 2024 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [5a536be44c](https://linux-hardware.org/?probe=5a536be44c) | Apr 21, 2024 |
| Positivo      | POS-PIG41BA POSITIVO        | Desktop     | [d5e1581050](https://linux-hardware.org/?probe=d5e1581050) | Apr 21, 2024 |
| Acer          | Aspire F5-573               | Notebook    | [c71f150bd8](https://linux-hardware.org/?probe=c71f150bd8) | Apr 21, 2024 |
| Dell          | 0XFN1D A00                  | All in one  | [99aa3181a2](https://linux-hardware.org/?probe=99aa3181a2) | Apr 21, 2024 |
| Acer          | WG43M                       | Desktop     | [93fcdbd13d](https://linux-hardware.org/?probe=93fcdbd13d) | Apr 20, 2024 |
| GEEKOM        | Mini Air12                  | Server      | [fef2c94714](https://linux-hardware.org/?probe=fef2c94714) | Apr 20, 2024 |
| Lenovo        | ThinkPad X260 20F5S4CC00    | Notebook    | [56a80212e2](https://linux-hardware.org/?probe=56a80212e2) | Apr 20, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [fa44624ceb](https://linux-hardware.org/?probe=fa44624ceb) | Apr 20, 2024 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [c823822177](https://linux-hardware.org/?probe=c823822177) | Apr 20, 2024 |
| HP            | 339A                        | Desktop     | [8cb48fe045](https://linux-hardware.org/?probe=8cb48fe045) | Apr 19, 2024 |
| MSI           | MS-7235                     | Desktop     | [d0b1ac0e44](https://linux-hardware.org/?probe=d0b1ac0e44) | Apr 19, 2024 |
| MSI           | B85I                        | Desktop     | [8751cf893f](https://linux-hardware.org/?probe=8751cf893f) | Apr 19, 2024 |
| Sony          | SVE1111M1EW                 | Notebook    | [4303a7cc13](https://linux-hardware.org/?probe=4303a7cc13) | Apr 19, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [50de89d752](https://linux-hardware.org/?probe=50de89d752) | Apr 18, 2024 |
| Dell          | 0Y958C A00                  | Desktop     | [88a0060933](https://linux-hardware.org/?probe=88a0060933) | Apr 18, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [3f587bf3dd](https://linux-hardware.org/?probe=3f587bf3dd) | Apr 18, 2024 |
| Acer          | V5-171                      | Notebook    | [1c5fdb6bae](https://linux-hardware.org/?probe=1c5fdb6bae) | Apr 18, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [bb34072490](https://linux-hardware.org/?probe=bb34072490) | Apr 18, 2024 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [c186027176](https://linux-hardware.org/?probe=c186027176) | Apr 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [686220b484](https://linux-hardware.org/?probe=686220b484) | Apr 17, 2024 |
| Acer          | Aspire A317-52              | Notebook    | [bf62cb2dba](https://linux-hardware.org/?probe=bf62cb2dba) | Apr 17, 2024 |
| Pegatron      | Narra6                      | Desktop     | [fb336cac9b](https://linux-hardware.org/?probe=fb336cac9b) | Apr 17, 2024 |
| Intel         | H61                         | Desktop     | [e0bacf6b01](https://linux-hardware.org/?probe=e0bacf6b01) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [41c197d579](https://linux-hardware.org/?probe=41c197d579) | Apr 16, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [f0d8580bfc](https://linux-hardware.org/?probe=f0d8580bfc) | Apr 16, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [be2b691a57](https://linux-hardware.org/?probe=be2b691a57) | Apr 15, 2024 |
| Lenovo        | ThinkPad X280 20KESA5000    | Notebook    | [8571fb3b5c](https://linux-hardware.org/?probe=8571fb3b5c) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4fb5756438](https://linux-hardware.org/?probe=4fb5756438) | Apr 14, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6720cd6b1d](https://linux-hardware.org/?probe=6720cd6b1d) | Apr 14, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [c6fd918c6e](https://linux-hardware.org/?probe=c6fd918c6e) | Apr 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [9d776d1a83](https://linux-hardware.org/?probe=9d776d1a83) | Apr 14, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [59540c163c](https://linux-hardware.org/?probe=59540c163c) | Apr 13, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [ca76c3d3ec](https://linux-hardware.org/?probe=ca76c3d3ec) | Apr 13, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [2998b9027d](https://linux-hardware.org/?probe=2998b9027d) | Apr 13, 2024 |
| Sony          | VPCEH30EB                   | Notebook    | [a3ce44d34f](https://linux-hardware.org/?probe=a3ce44d34f) | Apr 12, 2024 |
| Samsung       | 370E4K                      | Notebook    | [362fb05bf2](https://linux-hardware.org/?probe=362fb05bf2) | Apr 12, 2024 |
| Dell          | OptiPlex 7050               | Desktop     | [e6f968f709](https://linux-hardware.org/?probe=e6f968f709) | Apr 11, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [5757303d9a](https://linux-hardware.org/?probe=5757303d9a) | Apr 11, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [288ebeb8ba](https://linux-hardware.org/?probe=288ebeb8ba) | Apr 11, 2024 |
| MSI           | GE72 2QD                    | Notebook    | [4918e63b82](https://linux-hardware.org/?probe=4918e63b82) | Apr 11, 2024 |
| Dell          | 0NKW6Y A02                  | Desktop     | [fcd30b6392](https://linux-hardware.org/?probe=fcd30b6392) | Apr 11, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [b643ba4fed](https://linux-hardware.org/?probe=b643ba4fed) | Apr 11, 2024 |
| HP            | 1998                        | Desktop     | [4e592f29d7](https://linux-hardware.org/?probe=4e592f29d7) | Apr 11, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [9d16faea24](https://linux-hardware.org/?probe=9d16faea24) | Apr 10, 2024 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [e236ba52be](https://linux-hardware.org/?probe=e236ba52be) | Apr 10, 2024 |
| ASUSTek       | H61M-C                      | Desktop     | [a0e36b103b](https://linux-hardware.org/?probe=a0e36b103b) | Apr 10, 2024 |
| Quanta        | QL3 TBD                     | Notebook    | [0f0abe3406](https://linux-hardware.org/?probe=0f0abe3406) | Apr 09, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1163ac6ace](https://linux-hardware.org/?probe=1163ac6ace) | Apr 09, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [5b676c4d65](https://linux-hardware.org/?probe=5b676c4d65) | Apr 09, 2024 |
| ASUSTek       | N50Vc                       | Notebook    | [e7ae85215d](https://linux-hardware.org/?probe=e7ae85215d) | Apr 07, 2024 |
| MSI           | G41M-P26                    | Desktop     | [c337a993c8](https://linux-hardware.org/?probe=c337a993c8) | Apr 07, 2024 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [69cf49e1b1](https://linux-hardware.org/?probe=69cf49e1b1) | Apr 07, 2024 |
| Intel         | B75                         | Desktop     | [7ac22ca55d](https://linux-hardware.org/?probe=7ac22ca55d) | Apr 07, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [901e9f9640](https://linux-hardware.org/?probe=901e9f9640) | Apr 07, 2024 |
| Dell          | 0KP561                      | Desktop     | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| Gigabyte      | H410M S2H V2                | Desktop     | [2713f1fbb2](https://linux-hardware.org/?probe=2713f1fbb2) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [0f08ac20fe](https://linux-hardware.org/?probe=0f08ac20fe) | Apr 06, 2024 |
| HP            | 1497                        | Desktop     | [bc9fcab61a](https://linux-hardware.org/?probe=bc9fcab61a) | Apr 06, 2024 |
| HP            | 1790                        | Desktop     | [0038bf2917](https://linux-hardware.org/?probe=0038bf2917) | Apr 06, 2024 |
| Biostar       | TB250-BTC PRO               | Desktop     | [3fceee8ca7](https://linux-hardware.org/?probe=3fceee8ca7) | Apr 06, 2024 |
| HP            | 8446                        | All in one  | [16d954acab](https://linux-hardware.org/?probe=16d954acab) | Apr 06, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [e407d84cc9](https://linux-hardware.org/?probe=e407d84cc9) | Apr 06, 2024 |
| Acer          | Aspire 5536                 | Notebook    | [40d6361edd](https://linux-hardware.org/?probe=40d6361edd) | Apr 06, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [edfce73a66](https://linux-hardware.org/?probe=edfce73a66) | Apr 06, 2024 |
| HP            | ZBook 15u G6                | Notebook    | [a1865e5d26](https://linux-hardware.org/?probe=a1865e5d26) | Apr 06, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [529868adc3](https://linux-hardware.org/?probe=529868adc3) | Apr 06, 2024 |
| Dell          | Latitude E4300              | Notebook    | [43c75dde9f](https://linux-hardware.org/?probe=43c75dde9f) | Apr 05, 2024 |
| Medion        | S14406                      | Convertible | [5fc361d14e](https://linux-hardware.org/?probe=5fc361d14e) | Apr 05, 2024 |
| Lenovo        | G40-80 80E4                 | Notebook    | [76642434b9](https://linux-hardware.org/?probe=76642434b9) | Apr 05, 2024 |
| ASRock        | H87 Pro4                    | Desktop     | [46c9acd849](https://linux-hardware.org/?probe=46c9acd849) | Apr 05, 2024 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [2d8c4c947f](https://linux-hardware.org/?probe=2d8c4c947f) | Apr 05, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | Desktop     | [1750bd22db](https://linux-hardware.org/?probe=1750bd22db) | Apr 05, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cee5393de5](https://linux-hardware.org/?probe=cee5393de5) | Apr 05, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [4b0127a449](https://linux-hardware.org/?probe=4b0127a449) | Apr 04, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [f5fc4b58c7](https://linux-hardware.org/?probe=f5fc4b58c7) | Apr 04, 2024 |
| MSI           | Prestige 14Evo B13M         | Notebook    | [f118f2e24a](https://linux-hardware.org/?probe=f118f2e24a) | Apr 04, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [3fbe8de966](https://linux-hardware.org/?probe=3fbe8de966) | Apr 04, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8ad07875a5](https://linux-hardware.org/?probe=8ad07875a5) | Apr 04, 2024 |
| Dell          | Latitude E4310              | Notebook    | [e182d9e891](https://linux-hardware.org/?probe=e182d9e891) | Apr 03, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e3541ebcf4](https://linux-hardware.org/?probe=e3541ebcf4) | Apr 03, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8d409a59ec](https://linux-hardware.org/?probe=8d409a59ec) | Apr 03, 2024 |
| MSI           | GP60 2OD                    | Notebook    | [134464f908](https://linux-hardware.org/?probe=134464f908) | Apr 03, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [8f67355bed](https://linux-hardware.org/?probe=8f67355bed) | Apr 03, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [f7c3e17f2e](https://linux-hardware.org/?probe=f7c3e17f2e) | Apr 03, 2024 |
| HP            | 3396                        | Desktop     | [641a1891ba](https://linux-hardware.org/?probe=641a1891ba) | Apr 02, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [70bd1ca499](https://linux-hardware.org/?probe=70bd1ca499) | Apr 02, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [ea24de6920](https://linux-hardware.org/?probe=ea24de6920) | Apr 02, 2024 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [1abe698880](https://linux-hardware.org/?probe=1abe698880) | Apr 02, 2024 |
| Dell          | Studio 1537                 | Notebook    | [3e7ce8de4a](https://linux-hardware.org/?probe=3e7ce8de4a) | Apr 02, 2024 |
| Toshiba       | Satellite A205              | Notebook    | [4fcbf3184c](https://linux-hardware.org/?probe=4fcbf3184c) | Apr 02, 2024 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [0eda4797d3](https://linux-hardware.org/?probe=0eda4797d3) | Apr 01, 2024 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [402894f9cd](https://linux-hardware.org/?probe=402894f9cd) | Apr 01, 2024 |
| Intel         | H81                         | Desktop     | [b7c3224542](https://linux-hardware.org/?probe=b7c3224542) | Apr 01, 2024 |
| HP            | 2171                        | Desktop     | [3cd1f729a4](https://linux-hardware.org/?probe=3cd1f729a4) | Apr 01, 2024 |
| QIYIDA        | X79-M6 V1.0                 | Desktop     | [ab18c6c58f](https://linux-hardware.org/?probe=ab18c6c58f) | Mar 31, 2024 |
| Pegatron      | Benicia                     | Desktop     | [22f74ed745](https://linux-hardware.org/?probe=22f74ed745) | Mar 31, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2ec08fd0c4](https://linux-hardware.org/?probe=2ec08fd0c4) | Mar 31, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [30575319dc](https://linux-hardware.org/?probe=30575319dc) | Mar 31, 2024 |
| ASUSTek       | P8Z77-V PREMIUM             | Desktop     | [3c3064e23a](https://linux-hardware.org/?probe=3c3064e23a) | Mar 31, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [cd85e4d384](https://linux-hardware.org/?probe=cd85e4d384) | Mar 30, 2024 |
| Positivo      | POS-AG31AP                  | Desktop     | [606557f097](https://linux-hardware.org/?probe=606557f097) | Mar 30, 2024 |
| Dell          | Latitude E6440              | Notebook    | [82a2e96578](https://linux-hardware.org/?probe=82a2e96578) | Mar 30, 2024 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [9eadaaa051](https://linux-hardware.org/?probe=9eadaaa051) | Mar 29, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [b75c8663ed](https://linux-hardware.org/?probe=b75c8663ed) | Mar 29, 2024 |
| Lenovo        | ThinkPad T540p 20BE00B2G... | Notebook    | [158444c545](https://linux-hardware.org/?probe=158444c545) | Mar 29, 2024 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [f99b737a3e](https://linux-hardware.org/?probe=f99b737a3e) | Mar 29, 2024 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [00fe1930d3](https://linux-hardware.org/?probe=00fe1930d3) | Mar 29, 2024 |
| Toshiba       | dynabook R63/F              | Notebook    | [953540775e](https://linux-hardware.org/?probe=953540775e) | Mar 29, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [77d9027069](https://linux-hardware.org/?probe=77d9027069) | Mar 29, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [4169f19794](https://linux-hardware.org/?probe=4169f19794) | Mar 29, 2024 |
| HP            | Presario CQ62               | Notebook    | [354d7a9fe2](https://linux-hardware.org/?probe=354d7a9fe2) | Mar 29, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [54a537a410](https://linux-hardware.org/?probe=54a537a410) | Mar 29, 2024 |
| Fujitsu Si... | ESPRIMO Mobile M9400        | Notebook    | [d056f67a21](https://linux-hardware.org/?probe=d056f67a21) | Mar 28, 2024 |
| GEEKOM        | A5                          | Desktop     | [c7e07714cc](https://linux-hardware.org/?probe=c7e07714cc) | Mar 28, 2024 |
| HP            | 2AE3                        | Desktop     | [f068c22e6c](https://linux-hardware.org/?probe=f068c22e6c) | Mar 28, 2024 |
| Acer          | Aspire E5-772G              | Notebook    | [1900649358](https://linux-hardware.org/?probe=1900649358) | Mar 28, 2024 |
| HP            | ProBook 4515s               | Notebook    | [3048353db9](https://linux-hardware.org/?probe=3048353db9) | Mar 27, 2024 |
| Dell          | 0YXT71 A03                  | Desktop     | [d854505a5b](https://linux-hardware.org/?probe=d854505a5b) | Mar 27, 2024 |
| HP            | 2AA6 PVT                    | Desktop     | [899a3e57bb](https://linux-hardware.org/?probe=899a3e57bb) | Mar 27, 2024 |
| System76      | Adder WS                    | Notebook    | [9d181cd8bf](https://linux-hardware.org/?probe=9d181cd8bf) | Mar 27, 2024 |
| HP            | ENVY Sleekbook 4            | Notebook    | [5814881985](https://linux-hardware.org/?probe=5814881985) | Mar 26, 2024 |
| ASRock        | H310CM-HDV                  | Desktop     | [b4c034c103](https://linux-hardware.org/?probe=b4c034c103) | Mar 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [50ff654c73](https://linux-hardware.org/?probe=50ff654c73) | Mar 26, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [1ca23339d5](https://linux-hardware.org/?probe=1ca23339d5) | Mar 26, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3f052410d3](https://linux-hardware.org/?probe=3f052410d3) | Mar 26, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [de5dac0125](https://linux-hardware.org/?probe=de5dac0125) | Mar 26, 2024 |
| ASRock        | H110M-HG4                   | Desktop     | [0ef9ca77ad](https://linux-hardware.org/?probe=0ef9ca77ad) | Mar 26, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [1c4843f354](https://linux-hardware.org/?probe=1c4843f354) | Mar 26, 2024 |
| ASUSTek       | K53SC                       | Notebook    | [c089e8153d](https://linux-hardware.org/?probe=c089e8153d) | Mar 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [f39e53816d](https://linux-hardware.org/?probe=f39e53816d) | Mar 25, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [786693fab4](https://linux-hardware.org/?probe=786693fab4) | Mar 25, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [000bb993d1](https://linux-hardware.org/?probe=000bb993d1) | Mar 25, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [c250bda654](https://linux-hardware.org/?probe=c250bda654) | Mar 25, 2024 |
| Pegatron      | 2AB5                        | Desktop     | [713be0f3f0](https://linux-hardware.org/?probe=713be0f3f0) | Mar 25, 2024 |
| Dell          | Latitude E6510              | Notebook    | [f8ffac43ca](https://linux-hardware.org/?probe=f8ffac43ca) | Mar 24, 2024 |
| Lenovo        | ThinkPad X200T 7450CTO      | Notebook    | [71d0b95323](https://linux-hardware.org/?probe=71d0b95323) | Mar 24, 2024 |
| Qilive        | QW2214FR                    | Notebook    | [4a5e116692](https://linux-hardware.org/?probe=4a5e116692) | Mar 24, 2024 |
| Dell          | 084J0R A00                  | Desktop     | [691f19e56c](https://linux-hardware.org/?probe=691f19e56c) | Mar 24, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [352c177531](https://linux-hardware.org/?probe=352c177531) | Mar 23, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [45e2102834](https://linux-hardware.org/?probe=45e2102834) | Mar 23, 2024 |
| Qilive        | QW2214FR                    | Notebook    | [caa8ca0076](https://linux-hardware.org/?probe=caa8ca0076) | Mar 23, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b7426e4e08](https://linux-hardware.org/?probe=b7426e4e08) | Mar 23, 2024 |
| Intel         | NUC11PABi3 M68269-400       | Mini pc     | [ffb06dd581](https://linux-hardware.org/?probe=ffb06dd581) | Mar 23, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [05cfb55044](https://linux-hardware.org/?probe=05cfb55044) | Mar 23, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [42aee3b9b6](https://linux-hardware.org/?probe=42aee3b9b6) | Mar 22, 2024 |
| Dell          | Latitude 7490               | Notebook    | [869b39d5bd](https://linux-hardware.org/?probe=869b39d5bd) | Mar 22, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [5a8a94c103](https://linux-hardware.org/?probe=5a8a94c103) | Mar 22, 2024 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [5a656756e0](https://linux-hardware.org/?probe=5a656756e0) | Mar 22, 2024 |
| Acer          | Aspire E5-571               | Notebook    | [f3e2cf7bad](https://linux-hardware.org/?probe=f3e2cf7bad) | Mar 22, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [69bd8b3475](https://linux-hardware.org/?probe=69bd8b3475) | Mar 22, 2024 |
| HP            | Pavilion 17                 | Notebook    | [fcbbdc0161](https://linux-hardware.org/?probe=fcbbdc0161) | Mar 22, 2024 |
| AMI           | Intel                       | Desktop     | [4bb3934f7d](https://linux-hardware.org/?probe=4bb3934f7d) | Mar 21, 2024 |
| Intel         | X99                         | Desktop     | [c85af1f29d](https://linux-hardware.org/?probe=c85af1f29d) | Mar 21, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [6428f854e6](https://linux-hardware.org/?probe=6428f854e6) | Mar 21, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e778bbfc4b](https://linux-hardware.org/?probe=e778bbfc4b) | Mar 20, 2024 |
| HP            | 8768 A                      | Desktop     | [6c296786d2](https://linux-hardware.org/?probe=6c296786d2) | Mar 19, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [cec4a4b661](https://linux-hardware.org/?probe=cec4a4b661) | Mar 19, 2024 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [052aae188c](https://linux-hardware.org/?probe=052aae188c) | Mar 19, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [345e2df2db](https://linux-hardware.org/?probe=345e2df2db) | Mar 19, 2024 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [044c3275da](https://linux-hardware.org/?probe=044c3275da) | Mar 19, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [e85fec8591](https://linux-hardware.org/?probe=e85fec8591) | Mar 18, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [8d5dfb7293](https://linux-hardware.org/?probe=8d5dfb7293) | Mar 18, 2024 |
| Toshiba       | Satellite C660D             | Notebook    | [63b9e3f1b8](https://linux-hardware.org/?probe=63b9e3f1b8) | Mar 18, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [89b3ca44e4](https://linux-hardware.org/?probe=89b3ca44e4) | Mar 17, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [195c54fe84](https://linux-hardware.org/?probe=195c54fe84) | Mar 17, 2024 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [82c42946af](https://linux-hardware.org/?probe=82c42946af) | Mar 17, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [2e1e84fe15](https://linux-hardware.org/?probe=2e1e84fe15) | Mar 16, 2024 |
| HP            | 097Ch                       | Desktop     | [23bc1b2344](https://linux-hardware.org/?probe=23bc1b2344) | Mar 15, 2024 |
| AZW           | MINI S 10                   | Desktop     | [843a0455d6](https://linux-hardware.org/?probe=843a0455d6) | Mar 15, 2024 |
| HP            | Notebook                    | Notebook    | [a8f1904e27](https://linux-hardware.org/?probe=a8f1904e27) | Mar 15, 2024 |
| Qilive        | QW2214FR                    | Notebook    | [29901f6a01](https://linux-hardware.org/?probe=29901f6a01) | Mar 15, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [076c34493c](https://linux-hardware.org/?probe=076c34493c) | Mar 15, 2024 |
| MSI           | Z270 PC MATE                | Desktop     | [87ef1a815e](https://linux-hardware.org/?probe=87ef1a815e) | Mar 15, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [708c2c7987](https://linux-hardware.org/?probe=708c2c7987) | Mar 15, 2024 |
| Compaq        | 420                         | Notebook    | [af5f1900e1](https://linux-hardware.org/?probe=af5f1900e1) | Mar 15, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [585d283a71](https://linux-hardware.org/?probe=585d283a71) | Mar 15, 2024 |
| UMAX          | 13Wr                        | Notebook    | [88c71ba263](https://linux-hardware.org/?probe=88c71ba263) | Mar 14, 2024 |
| MSI           | B85M-G43                    | Desktop     | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4c8d39a7ab](https://linux-hardware.org/?probe=4c8d39a7ab) | Mar 14, 2024 |
| Dell          | Precision M6600             | Notebook    | [8af490c831](https://linux-hardware.org/?probe=8af490c831) | Mar 14, 2024 |
| ASUSTek       | K52F                        | Notebook    | [63015aee4d](https://linux-hardware.org/?probe=63015aee4d) | Mar 13, 2024 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [fa1bce30a0](https://linux-hardware.org/?probe=fa1bce30a0) | Mar 13, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [75bc4f3af5](https://linux-hardware.org/?probe=75bc4f3af5) | Mar 13, 2024 |
| eMachines     | E727                        | Notebook    | [af56e195f8](https://linux-hardware.org/?probe=af56e195f8) | Mar 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [d89d81deb7](https://linux-hardware.org/?probe=d89d81deb7) | Mar 12, 2024 |
| MSI           | Katana 15 B13VGK            | Notebook    | [b442691d34](https://linux-hardware.org/?probe=b442691d34) | Mar 12, 2024 |
| Acer          | Aspire 5742                 | Notebook    | [280af1d066](https://linux-hardware.org/?probe=280af1d066) | Mar 12, 2024 |
| Dell          | Inspiron 15 3515            | Notebook    | [ed5c4423dc](https://linux-hardware.org/?probe=ed5c4423dc) | Mar 12, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [754b3828fc](https://linux-hardware.org/?probe=754b3828fc) | Mar 12, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [f5f2c6557f](https://linux-hardware.org/?probe=f5f2c6557f) | Mar 12, 2024 |
| OEM           | X79-Turbo                   | Desktop     | [b19889facd](https://linux-hardware.org/?probe=b19889facd) | Mar 12, 2024 |
| Intel         | B75                         | Desktop     | [f78757e7b2](https://linux-hardware.org/?probe=f78757e7b2) | Mar 11, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [fba62e6832](https://linux-hardware.org/?probe=fba62e6832) | Mar 11, 2024 |
| Philco        | 14I                         | Notebook    | [67e82d4b02](https://linux-hardware.org/?probe=67e82d4b02) | Mar 11, 2024 |
| Dell          | Latitude E6500              | Notebook    | [0c10bab3da](https://linux-hardware.org/?probe=0c10bab3da) | Mar 10, 2024 |
| Acer          | AOD270                      | Notebook    | [87f42bf5b3](https://linux-hardware.org/?probe=87f42bf5b3) | Mar 10, 2024 |
| Dell          | Latitude 5490               | Notebook    | [ace23bd1bf](https://linux-hardware.org/?probe=ace23bd1bf) | Mar 09, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [a32383cf3e](https://linux-hardware.org/?probe=a32383cf3e) | Mar 09, 2024 |
| Core Innov... | CLC14364                    | Notebook    | [445912b935](https://linux-hardware.org/?probe=445912b935) | Mar 08, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [2187f5b3b3](https://linux-hardware.org/?probe=2187f5b3b3) | Mar 08, 2024 |
| Lenovo        | ThinkPad T520 42434WG       | Notebook    | [d491000477](https://linux-hardware.org/?probe=d491000477) | Mar 08, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [dd85c61d0d](https://linux-hardware.org/?probe=dd85c61d0d) | Mar 07, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [2171fc67cb](https://linux-hardware.org/?probe=2171fc67cb) | Mar 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5722090995](https://linux-hardware.org/?probe=5722090995) | Mar 07, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [8b9fbadb38](https://linux-hardware.org/?probe=8b9fbadb38) | Mar 07, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [1df3b86749](https://linux-hardware.org/?probe=1df3b86749) | Mar 06, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.08/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.4.11-desktop-1omv2390       | 1968      | 76.34%  |
| 6.4.8-desktop-2omv2390        | 567       | 21.99%  |
| 6.5.0-desktop-1omv2390        | 20        | 0.78%   |
| 6.6.2-desktop-1omv2390        | 5         | 0.19%   |
| 6.10.1-desktop-1omv2490       | 5         | 0.19%   |
| 6.5.1-desktop-1omv2390        | 2         | 0.08%   |
| 6.3.5-desktop-3omv2390        | 2         | 0.08%   |
| 6.9.3-desktop-2omv2490        | 1         | 0.04%   |
| 6.9.3-desktop-1omv2490        | 1         | 0.04%   |
| 6.8.1-desktop-3omv2490        | 1         | 0.04%   |
| 6.6.0-desktop-1omv2390        | 1         | 0.04%   |
| 6.5.0-desktop-0.rc7.1omv2390  | 1         | 0.04%   |
| 6.5.0-desktop-0.rc4.1omv2390  | 1         | 0.04%   |
| 6.15.0-desktop-0.rc2.3omv2590 | 1         | 0.04%   |
| 6.13.5-desktop-1omv2590       | 1         | 0.04%   |
| 6.10.0-desktop-1omv2490       | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.11  | 1968      | 76.34%  |
| 6.4.8   | 567       | 21.99%  |
| 6.5.0   | 22        | 0.85%   |
| 6.6.2   | 5         | 0.19%   |
| 6.10.1  | 5         | 0.19%   |
| 6.9.3   | 2         | 0.08%   |
| 6.5.1   | 2         | 0.08%   |
| 6.3.5   | 2         | 0.08%   |
| 6.8.1   | 1         | 0.04%   |
| 6.6.0   | 1         | 0.04%   |
| 6.15.0  | 1         | 0.04%   |
| 6.13.5  | 1         | 0.04%   |
| 6.10.0  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 2533      | 98.33%  |
| 6.5     | 24        | 0.93%   |
| 6.6     | 6         | 0.23%   |
| 6.10    | 6         | 0.23%   |
| 6.9     | 2         | 0.08%   |
| 6.3     | 2         | 0.08%   |
| 6.8     | 1         | 0.04%   |
| 6.15    | 1         | 0.04%   |
| 6.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2575      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 2233      | 86.62%  |
| GNOME    | 177       | 6.87%   |
| LXQt     | 159       | 6.17%   |
| Unknown  | 4         | 0.16%   |
| Budgie   | 3         | 0.12%   |
| Cinnamon | 2         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 2493      | 96.7%   |
| X11     | 83        | 3.22%   |
| Unknown | 2         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2399      | 93.06%  |
| GDM     | 177       | 6.87%   |
| Unknown | 2         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1302      | 50.41%  |
| de_DE | 172       | 6.66%   |
| pt_BR | 146       | 5.65%   |
| fr_FR | 139       | 5.38%   |
| ru_RU | 127       | 4.92%   |
| en_GB | 109       | 4.22%   |
| pl_PL | 88        | 3.41%   |
| it_IT | 72        | 2.79%   |
| es_ES | 60        | 2.32%   |
| es_MX | 31        | 1.2%    |
| es_AR | 26        | 1.01%   |
| en_CA | 25        | 0.97%   |
| cs_CZ | 24        | 0.93%   |
| hu_HU | 23        | 0.89%   |
| pt_PT | 18        | 0.7%    |
| en_IN | 18        | 0.7%    |
| en_AU | 17        | 0.66%   |
| tr_TR | 16        | 0.62%   |
| es_VE | 15        | 0.58%   |
| fr_BE | 14        | 0.54%   |
| nl_BE | 11        | 0.43%   |
| es_CO | 11        | 0.43%   |
| de_AT | 10        | 0.39%   |
| fr_CA | 8         | 0.31%   |
| es_CL | 8         | 0.31%   |
| ro_RO | 7         | 0.27%   |
| nl_NL | 7         | 0.27%   |
| en_SG | 6         | 0.23%   |
| de_CH | 6         | 0.23%   |
| UTF-8 | 5         | 0.19%   |
| es_UY | 5         | 0.19%   |
| en_ZA | 5         | 0.19%   |
| en_IE | 5         | 0.19%   |
| fr_CH | 4         | 0.15%   |
| en_DK | 4         | 0.15%   |
| en_HK | 3         | 0.12%   |
| da_DK | 3         | 0.12%   |
| uk_UA | 2         | 0.08%   |
| ja_JP | 2         | 0.08%   |
| it_CH | 2         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1557      | 60.35%  |
| BIOS | 1023      | 39.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1219      | 47.05%  |
| Overlay  | 1217      | 46.97%  |
| Btrfs    | 109       | 4.21%   |
| Xfs      | 21        | 0.81%   |
| F2fs     | 9         | 0.35%   |
| Reiserfs | 5         | 0.19%   |
| Ext3     | 4         | 0.15%   |
| Jfs      | 3         | 0.12%   |
| Ext2     | 3         | 0.12%   |
| Udf      | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2036      | 78.73%  |
| MBR     | 548       | 21.19%  |
| Unknown | 2         | 0.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1419      | 54.75%  |
| Yes       | 1173      | 45.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1521      | 58.84%  |
| Yes       | 1064      | 41.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 394       | 15.3%   |
| ASUSTek Computer                     | 375       | 14.56%  |
| Hewlett-Packard                      | 348       | 13.51%  |
| Dell                                 | 278       | 10.8%   |
| Gigabyte Technology                  | 181       | 7.03%   |
| Acer                                 | 147       | 5.71%   |
| MSI                                  | 144       | 5.59%   |
| Intel                                | 89        | 3.46%   |
| ASRock                               | 83        | 3.22%   |
| Fujitsu                              | 44        | 1.71%   |
| Toshiba                              | 40        | 1.55%   |
| Apple                                | 40        | 1.55%   |
| Samsung Electronics                  | 30        | 1.17%   |
| Core Innovations                     | 23        | 0.89%   |
| Unknown                              | 23        | 0.89%   |
| Positivo                             | 18        | 0.7%    |
| Medion                               | 16        | 0.62%   |
| Foxconn                              | 16        | 0.62%   |
| AZW                                  | 15        | 0.58%   |
| Biostar                              | 14        | 0.54%   |
| Sony                                 | 13        | 0.5%    |
| Pegatron                             | 13        | 0.5%    |
| Packard Bell                         | 12        | 0.47%   |
| HUAWEI                               | 10        | 0.39%   |
| Chuwi                                | 10        | 0.39%   |
| LG Electronics                       | 8         | 0.31%   |
| ECS                                  | 8         | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 7         | 0.27%   |
| Google                               | 7         | 0.27%   |
| OEM                                  | 6         | 0.23%   |
| Microsoft                            | 6         | 0.23%   |
| GPU Company                          | 5         | 0.19%   |
| Compaq                               | 5         | 0.19%   |
| Clevo                                | 5         | 0.19%   |
| System76                             | 4         | 0.16%   |
| Panasonic                            | 4         | 0.16%   |
| UMAX                                 | 3         | 0.12%   |
| Shuttle                              | 3         | 0.12%   |
| Qilive                               | 3         | 0.12%   |
| Philco                               | 3         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL7 82V6         | 40        | 1.55%   |
| Unknown                              | 28        | 1.09%   |
| Core Innovations CLC14364            | 23        | 0.89%   |
| ASUS All Series                      | 16        | 0.62%   |
| Intel H61                            | 13        | 0.5%    |
| HP Pavilion g6                       | 9         | 0.35%   |
| Dell OptiPlex 7010                   | 9         | 0.35%   |
| Intel H81                            | 8         | 0.31%   |
| HP Compaq Pro 6300 SFF               | 8         | 0.31%   |
| HP Notebook                          | 6         | 0.23%   |
| Positivo Mobile                      | 5         | 0.19%   |
| MSI MS-7C51                          | 5         | 0.19%   |
| MSI MS-7817                          | 5         | 0.19%   |
| Lenovo ThinkPad L13 Gen 3 21BAS0X700 | 5         | 0.19%   |
| Intel X99                            | 5         | 0.19%   |
| Gigabyte B75M-D3H                    | 5         | 0.19%   |
| Gigabyte A320M-S2H                   | 5         | 0.19%   |
| Dell OptiPlex 9020                   | 5         | 0.19%   |
| Dell OptiPlex 3010                   | 5         | 0.19%   |
| Dell Latitude E6400                  | 5         | 0.19%   |
| AZW SER                              | 5         | 0.19%   |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.19%   |
| ASUS TUF Gaming B550-PLUS            | 5         | 0.19%   |
| Positivo POS-PIG41BA                 | 4         | 0.16%   |
| MSI MS-7C91                          | 4         | 0.16%   |
| MSI MS-7996                          | 4         | 0.16%   |
| MSI MS-7721                          | 4         | 0.16%   |
| Lenovo IdeaPad 3 15ALC6 82MF         | 4         | 0.16%   |
| Intel B75                            | 4         | 0.16%   |
| HP Z400 Workstation                  | 4         | 0.16%   |
| HP Laptop 15s-eq2xxx                 | 4         | 0.16%   |
| HP EliteBook 840 G5                  | 4         | 0.16%   |
| HP EliteBook 840 G3                  | 4         | 0.16%   |
| HP Compaq 6200 Pro SFF PC            | 4         | 0.16%   |
| Gigabyte X299 AORUS Gaming           | 4         | 0.16%   |
| Dell OptiPlex 9010                   | 4         | 0.16%   |
| Dell OptiPlex 790                    | 4         | 0.16%   |
| Dell Latitude E6420                  | 4         | 0.16%   |
| Dell Latitude E6410                  | 4         | 0.16%   |
| Dell Latitude 7480                   | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 132       | 5.13%   |
| Lenovo IdeaPad            | 117       | 4.54%   |
| Acer Aspire               | 96        | 3.73%   |
| Dell Latitude             | 84        | 3.26%   |
| Dell Inspiron             | 72        | 2.8%    |
| Dell OptiPlex             | 62        | 2.41%   |
| HP Compaq                 | 59        | 2.29%   |
| ASUS PRIME                | 54        | 2.1%    |
| ASUS VivoBook             | 47        | 1.83%   |
| HP Pavilion               | 45        | 1.75%   |
| Lenovo ThinkCentre        | 39        | 1.51%   |
| HP Laptop                 | 37        | 1.44%   |
| HP EliteBook              | 37        | 1.44%   |
| Toshiba Satellite         | 32        | 1.24%   |
| Unknown                   | 28        | 1.09%   |
| ASUS TUF                  | 27        | 1.05%   |
| HP ProBook                | 26        | 1.01%   |
| Core Innovations CLC14364 | 23        | 0.89%   |
| Fujitsu ESPRIMO           | 20        | 0.78%   |
| ASUS ROG                  | 20        | 0.78%   |
| HP EliteDesk              | 19        | 0.74%   |
| ASUS All                  | 16        | 0.62%   |
| Dell Precision            | 15        | 0.58%   |
| Intel H61                 | 14        | 0.54%   |
| Dell Vostro               | 14        | 0.54%   |
| Lenovo Yoga               | 12        | 0.47%   |
| HP ProDesk                | 12        | 0.47%   |
| Acer Veriton              | 12        | 0.47%   |
| Dell XPS                  | 11        | 0.43%   |
| Lenovo IdeaCentre         | 10        | 0.39%   |
| Packard Bell EasyNote     | 9         | 0.35%   |
| Intel H81                 | 9         | 0.35%   |
| HP 250                    | 9         | 0.35%   |
| Fujitsu LIFEBOOK          | 9         | 0.35%   |
| ASUS M5A78L-M             | 9         | 0.35%   |
| HP Slim                   | 8         | 0.31%   |
| HP ENVY                   | 8         | 0.31%   |
| Acer TravelMate           | 8         | 0.31%   |
| Acer Nitro                | 8         | 0.31%   |
| Lenovo IdeaPadFlex        | 7         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 241       | 9.36%   |
| 2021    | 208       | 8.08%   |
| 2011    | 203       | 7.88%   |
| 2013    | 194       | 7.53%   |
| 2022    | 176       | 6.83%   |
| 2020    | 175       | 6.8%    |
| 2018    | 162       | 6.29%   |
| 2010    | 157       | 6.1%    |
| 2014    | 154       | 5.98%   |
| 2017    | 151       | 5.86%   |
| 2019    | 148       | 5.75%   |
| 2016    | 129       | 5.01%   |
| 2009    | 116       | 4.5%    |
| 2015    | 110       | 4.27%   |
| 2008    | 82        | 3.18%   |
| 2023    | 80        | 3.11%   |
| 2007    | 50        | 1.94%   |
| 2006    | 20        | 0.78%   |
| 2024    | 12        | 0.47%   |
| 2005    | 3         | 0.12%   |
| 2004    | 2         | 0.08%   |
| 2025    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1280      | 49.71%  |
| Desktop     | 1151      | 44.7%   |
| Mini pc     | 49        | 1.9%    |
| Convertible | 37        | 1.44%   |
| All in one  | 36        | 1.4%    |
| Tablet      | 15        | 0.58%   |
| Server      | 6         | 0.23%   |
| Other       | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2575      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2565      | 99.61%  |
| Yes  | 10        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 722       | 27.96%  |
| 3.01-4.0    | 556       | 21.53%  |
| 16.01-24.0  | 465       | 18.01%  |
| 8.01-16.0   | 403       | 15.61%  |
| 32.01-64.0  | 179       | 6.93%   |
| 1.01-2.0    | 77        | 2.98%   |
| 2.01-3.0    | 74        | 2.87%   |
| 64.01-256.0 | 47        | 1.82%   |
| 24.01-32.0  | 46        | 1.78%   |
| 0.51-1.0    | 13        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1706      | 65.46%  |
| 2.01-3.0  | 541       | 20.76%  |
| 0.51-1.0  | 208       | 7.98%   |
| 3.01-4.0  | 95        | 3.65%   |
| 4.01-8.0  | 29        | 1.11%   |
| 0.01-0.5  | 25        | 0.96%   |
| 8.01-16.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1548      | 59.7%   |
| 2      | 632       | 24.37%  |
| 3      | 210       | 8.1%    |
| 4      | 89        | 3.43%   |
| 5      | 45        | 1.74%   |
| 0      | 35        | 1.35%   |
| 6      | 18        | 0.69%   |
| 8      | 6         | 0.23%   |
| 7      | 6         | 0.23%   |
| 10     | 2         | 0.08%   |
| 11     | 1         | 0.04%   |
| 9      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1491      | 57.84%  |
| Yes       | 1087      | 42.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2259      | 87.73%  |
| No        | 316       | 12.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1813      | 70.35%  |
| No        | 764       | 29.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1385      | 53.68%  |
| No        | 1195      | 46.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 426       | 16.53%  |
| Germany      | 248       | 9.62%   |
| Brazil       | 224       | 8.69%   |
| France       | 158       | 6.13%   |
| Russia       | 153       | 5.94%   |
| Poland       | 124       | 4.81%   |
| Italy        | 104       | 4.04%   |
| UK           | 94        | 3.65%   |
| Spain        | 88        | 3.41%   |
| Canada       | 61        | 2.37%   |
| Australia    | 44        | 1.71%   |
| India        | 41        | 1.59%   |
| Mexico       | 39        | 1.51%   |
| Argentina    | 37        | 1.44%   |
| Netherlands  | 33        | 1.28%   |
| Hungary      | 32        | 1.24%   |
| Czechia      | 31        | 1.2%    |
| Turkey       | 30        | 1.16%   |
| Japan        | 29        | 1.13%   |
| Belgium      | 29        | 1.13%   |
| Romania      | 27        | 1.05%   |
| Greece       | 24        | 0.93%   |
| Indonesia    | 23        | 0.89%   |
| Portugal     | 22        | 0.85%   |
| Colombia     | 22        | 0.85%   |
| Bulgaria     | 20        | 0.78%   |
| Austria      | 20        | 0.78%   |
| Venezuela    | 18        | 0.7%    |
| Finland      | 18        | 0.7%    |
| Thailand     | 15        | 0.58%   |
| Sweden       | 15        | 0.58%   |
| Slovakia     | 14        | 0.54%   |
| Ukraine      | 13        | 0.5%    |
| Switzerland  | 13        | 0.5%    |
| South Africa | 13        | 0.5%    |
| Malaysia     | 13        | 0.5%    |
| Israel       | 13        | 0.5%    |
| China        | 13        | 0.5%    |
| Chile        | 12        | 0.47%   |
| Serbia       | 10        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Los Angeles    | 59        | 2.27%   |
| Berlin         | 26        | 1%      |
| Warsaw         | 25        | 0.96%   |
| Moscow         | 24        | 0.92%   |
| Melbourne      | 15        | 0.58%   |
| Krakow         | 15        | 0.58%   |
| Sydney         | 14        | 0.54%   |
| Sao Paulo      | 14        | 0.54%   |
| Paris          | 14        | 0.54%   |
| Milan          | 14        | 0.54%   |
| Vienna         | 13        | 0.5%    |
| Istanbul       | 13        | 0.5%    |
| St Petersburg  | 12        | 0.46%   |
| Rio de Janeiro | 12        | 0.46%   |
| Munich         | 12        | 0.46%   |
| Rome           | 11        | 0.42%   |
| Athens         | 11        | 0.42%   |
| Novosibirsk    | 10        | 0.38%   |
| Madrid         | 10        | 0.38%   |
| Topeka         | 9         | 0.35%   |
| Stuttgart      | 9         | 0.35%   |
| Sao Goncalo    | 9         | 0.35%   |
| Prague         | 9         | 0.35%   |
| Wroclaw        | 8         | 0.31%   |
| Thousand Oaks  | 8         | 0.31%   |
| Sofia          | 8         | 0.31%   |
| Lodz           | 8         | 0.31%   |
| Hamburg        | 8         | 0.31%   |
| Curitiba       | 8         | 0.31%   |
| Budapest       | 8         | 0.31%   |
| Yekaterinburg  | 7         | 0.27%   |
| San Cristóbal | 7         | 0.27%   |
| Oak Creek      | 7         | 0.27%   |
| Bengaluru      | 7         | 0.27%   |
| Belgrade       | 7         | 0.27%   |
| Vancouver      | 6         | 0.23%   |
| Tehran         | 6         | 0.23%   |
| Porto Alegre   | 6         | 0.23%   |
| Portland       | 6         | 0.23%   |
| Katowice       | 6         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 557       | 672    | 14.81%  |
| Seagate                     | 464       | 539    | 12.34%  |
| Samsung Electronics         | 436       | 537    | 11.6%   |
| Toshiba                     | 248       | 274    | 6.6%    |
| Kingston                    | 232       | 263    | 6.17%   |
| SanDisk                     | 160       | 167    | 4.26%   |
| Unknown                     | 155       | 184    | 4.12%   |
| Crucial                     | 152       | 177    | 4.04%   |
| Hitachi                     | 111       | 117    | 2.95%   |
| China                       | 80        | 86     | 2.13%   |
| Unknown                     | 67        | 71     | 1.78%   |
| A-DATA Technology           | 66        | 69     | 1.76%   |
| Intel                       | 64        | 66     | 1.7%    |
| SK hynix                    | 63        | 65     | 1.68%   |
| HGST                        | 50        | 52     | 1.33%   |
| Micron Technology           | 45        | 45     | 1.2%    |
| SPCC                        | 41        | 43     | 1.09%   |
| Intenso                     | 33        | 39     | 0.88%   |
| PNY                         | 28        | 29     | 0.74%   |
| GOODRAM                     | 28        | 33     | 0.74%   |
| Patriot                     | 27        | 28     | 0.72%   |
| Apple                       | 25        | 26     | 0.66%   |
| JMicron Technology          | 24        | 25     | 0.64%   |
| Maxtor                      | 23        | 27     | 0.61%   |
| Lexar                       | 20        | 23     | 0.53%   |
| Netac                       | 19        | 21     | 0.51%   |
| Kingston Technology Company | 19        | 22     | 0.51%   |
| Silicon Motion              | 18        | 19     | 0.48%   |
| Phison                      | 18        | 20     | 0.48%   |
| Apacer                      | 18        | 19     | 0.48%   |
| KIOXIA                      | 17        | 17     | 0.45%   |
| Transcend                   | 16        | 17     | 0.43%   |
| Team                        | 16        | 16     | 0.43%   |
| SSSTC                       | 16        | 16     | 0.43%   |
| LITEON                      | 16        | 16     | 0.43%   |
| Fanxiang                    | 16        | 16     | 0.43%   |
| KingSpec                    | 12        | 13     | 0.32%   |
| Hewlett-Packard             | 11        | 11     | 0.29%   |
| T-FORCE                     | 10        | 11     | 0.27%   |
| OCZ                         | 10        | 10     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 67        | 1.65%   |
| Kingston SA400S37240G 240GB SSD    | 48        | 1.18%   |
| Kingston SA400S37480G 480GB SSD    | 43        | 1.06%   |
| Unknown MMC64G  64GB               | 41        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB    | 37        | 0.91%   |
| Crucial CT500MX500SSD1 500GB       | 28        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB     | 27        | 0.66%   |
| Seagate ST500LT012-1DG142 500GB    | 25        | 0.61%   |
| Toshiba MQ04ABF100 1TB             | 23        | 0.56%   |
| SanDisk NVMe SSD Drive 1TB         | 22        | 0.54%   |
| Unknown SD/MMC/MS PRO 2GB          | 21        | 0.52%   |
| Kingston SA400S37120G 120GB SSD    | 21        | 0.52%   |
| Toshiba MQ01ABF050 500GB           | 20        | 0.49%   |
| Toshiba DT01ACA100 1TB             | 20        | 0.49%   |
| Samsung SSD 850 EVO 250GB          | 20        | 0.49%   |
| Crucial CT240BX500SSD1 240GB       | 20        | 0.49%   |
| Toshiba MQ01ABD100 1TB             | 19        | 0.47%   |
| Samsung SSD 860 EVO 500GB          | 17        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 16        | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB     | 16        | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 16        | 0.39%   |
| Toshiba DT01ACA050 500GB           | 15        | 0.37%   |
| Seagate ST3500418AS 500GB          | 15        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB     | 15        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 15        | 0.37%   |
| Samsung SSD 850 EVO 500GB          | 14        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD   | 14        | 0.34%   |
| JMicron Generic 320GB              | 14        | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 13        | 0.32%   |
| Toshiba HDWD110 1TB                | 13        | 0.32%   |
| Crucial CT1000MX500SSD1 1TB        | 13        | 0.32%   |
| SanDisk SSD PLUS 1000GB            | 12        | 0.29%   |
| SanDisk NVMe SSD Drive 500GB       | 12        | 0.29%   |
| Samsung SSD 980 500GB              | 12        | 0.29%   |
| Samsung SSD 970 EVO Plus 2TB       | 12        | 0.29%   |
| Samsung SSD 870 QVO 1TB            | 12        | 0.29%   |
| Kingston SNV2S500G 500GB           | 12        | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB           | 11        | 0.27%   |
| Crucial CT1000BX500SSD1 1TB        | 11        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 458       | 532    | 31.2%   |
| WDC                 | 439       | 526    | 29.9%   |
| Toshiba             | 217       | 237    | 14.78%  |
| Hitachi             | 111       | 117    | 7.56%   |
| Samsung Electronics | 85        | 92     | 5.79%   |
| HGST                | 50        | 52     | 3.41%   |
| Unknown             | 23        | 24     | 1.57%   |
| Maxtor              | 22        | 26     | 1.5%    |
| JMicron Technology  | 14        | 14     | 0.95%   |
| Apple               | 12        | 12     | 0.82%   |
| USB3.0              | 6         | 6      | 0.41%   |
| Fujitsu             | 6         | 7      | 0.41%   |
| ExcelStor           | 3         | 3      | 0.2%    |
| TO Exter            | 2         | 2      | 0.14%   |
| SAGE                | 2         | 2      | 0.14%   |
| Min Yi U            | 2         | 2      | 0.14%   |
| Inateck             | 2         | 2      | 0.14%   |
| External            | 2         | 2      | 0.14%   |
| ASMT                | 2         | 3      | 0.14%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| USB                 | 1         | 1      | 0.07%   |
| SSK                 | 1         | 1      | 0.07%   |
| Shenzhen            | 1         | 1      | 0.07%   |
| PRO-T5              | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| IB-AC703            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |
| Unknown             | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 208       | 241    | 14.94%  |
| Kingston            | 176       | 198    | 12.64%  |
| Crucial             | 112       | 119    | 8.05%   |
| SanDisk             | 99        | 104    | 7.11%   |
| China               | 80        | 86     | 5.75%   |
| WDC                 | 69        | 76     | 4.96%   |
| A-DATA Technology   | 45        | 46     | 3.23%   |
| SPCC                | 35        | 35     | 2.51%   |
| Intenso             | 32        | 38     | 2.3%    |
| GOODRAM             | 28        | 33     | 2.01%   |
| PNY                 | 27        | 28     | 1.94%   |
| Intel               | 27        | 27     | 1.94%   |
| Patriot             | 26        | 27     | 1.87%   |
| Micron Technology   | 23        | 23     | 1.65%   |
| SK hynix            | 17        | 18     | 1.22%   |
| Toshiba             | 15        | 19     | 1.08%   |
| Netac               | 15        | 17     | 1.08%   |
| Transcend           | 14        | 15     | 1.01%   |
| Apacer              | 14        | 14     | 1.01%   |
| Unknown             | 14        | 14     | 1.01%   |
| LITEON              | 13        | 13     | 0.93%   |
| Apple               | 13        | 13     | 0.93%   |
| KingSpec            | 12        | 13     | 0.86%   |
| Team                | 11        | 11     | 0.79%   |
| Fanxiang            | 11        | 11     | 0.79%   |
| OCZ                 | 10        | 10     | 0.72%   |
| Lexar               | 10        | 11     | 0.72%   |
| Verbatim            | 9         | 9      | 0.65%   |
| KingFast            | 7         | 8      | 0.5%    |
| Hewlett-Packard     | 7         | 7      | 0.5%    |
| XrayDisk            | 6         | 6      | 0.43%   |
| T-FORCE             | 6         | 7      | 0.43%   |
| LITEONIT            | 6         | 6      | 0.43%   |
| KIOXIA-EXCERIA      | 6         | 6      | 0.43%   |
| Seagate             | 5         | 5      | 0.36%   |
| Plextor             | 5         | 5      | 0.36%   |
| INNOVATION IT       | 5         | 5      | 0.36%   |
| WALRAM              | 4         | 5      | 0.29%   |
| Teclast             | 4         | 4      | 0.29%   |
| SSSTC               | 4         | 4      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1243      | 1675   | 37.39%  |
| SSD     | 1195      | 1506   | 35.95%  |
| NVMe    | 670       | 817    | 20.16%  |
| MMC     | 169       | 185    | 5.08%   |
| Unknown | 47        | 66     | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2019      | 3028   | 66.28%  |
| NVMe | 665       | 797    | 21.83%  |
| SAS  | 193       | 239    | 6.34%   |
| MMC  | 169       | 185    | 5.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1566      | 2040   | 62.34%  |
| 0.51-1.0   | 688       | 819    | 27.39%  |
| 1.01-2.0   | 167       | 203    | 6.65%   |
| 3.01-4.0   | 42        | 52     | 1.67%   |
| 2.01-3.0   | 29        | 36     | 1.15%   |
| 4.01-10.0  | 16        | 24     | 0.64%   |
| 10.01-20.0 | 4         | 7      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 883       | 33.91%  |
| 101-250        | 538       | 20.66%  |
| 251-500        | 369       | 14.17%  |
| 501-1000       | 215       | 8.26%   |
| 51-100         | 207       | 7.95%   |
| Unknown        | 134       | 5.15%   |
| 21-50          | 115       | 4.42%   |
| 1001-2000      | 83        | 3.19%   |
| More than 3000 | 31        | 1.19%   |
| 2001-3000      | 29        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2101      | 80.99%  |
| Unknown        | 134       | 5.17%   |
| 21-50          | 132       | 5.09%   |
| 51-100         | 69        | 2.66%   |
| 101-250        | 64        | 2.47%   |
| 251-500        | 38        | 1.46%   |
| 501-1000       | 25        | 0.96%   |
| 1001-2000      | 17        | 0.66%   |
| More than 3000 | 9         | 0.35%   |
| 2001-3000      | 5         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 14        | 14     | 2.05%   |
| Seagate ST500LT012-1DG142 500GB      | 10        | 10     | 1.47%   |
| Seagate ST3500418AS 500GB            | 9         | 9      | 1.32%   |
| Toshiba MQ01ABD100 1TB               | 7         | 7      | 1.03%   |
| Toshiba DT01ACA050 500GB             | 6         | 6      | 0.88%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 6      | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB       | 6         | 7      | 0.88%   |
| Seagate ST9500325AS 500GB            | 5         | 6      | 0.73%   |
| Seagate ST3500312CS 500GB            | 5         | 5      | 0.73%   |
| Samsung Electronics HD322HJ 320GB    | 5         | 6      | 0.73%   |
| Hitachi HTS543225L9A300 250GB        | 5         | 5      | 0.73%   |
| Hitachi HTS541616J9SA00 160GB        | 5         | 5      | 0.73%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 4         | 4      | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB              | 4         | 4      | 0.59%   |
| Toshiba MQ01ABF050 500GB             | 4         | 4      | 0.59%   |
| Toshiba MQ01ABD075 752GB             | 4         | 4      | 0.59%   |
| Toshiba MK3259GSXP 320GB             | 4         | 4      | 0.59%   |
| Toshiba DT01ACA100 1TB               | 4         | 4      | 0.59%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.59%   |
| Seagate ST9250315AS 250GB            | 4         | 4      | 0.59%   |
| Seagate ST3160318AS 160GB            | 4         | 4      | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 5      | 0.59%   |
| SanDisk SSD PLUS 480GB               | 4         | 4      | 0.59%   |
| Maxtor STM380815AS 80GB              | 4         | 5      | 0.59%   |
| Kingston SV300S37A120G 120GB SSD     | 4         | 4      | 0.59%   |
| HGST HTS725050A7E630 500GB           | 4         | 4      | 0.59%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 0.59%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 0.59%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 3         | 3      | 0.44%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 3         | 3      | 0.44%   |
| WDC WD5000AVCS-632DY1 500GB          | 3         | 3      | 0.44%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 3         | 3      | 0.44%   |
| WDC WD3200AAJS-56B4A0 320GB          | 3         | 3      | 0.44%   |
| WDC WD1600BEVS-00VAT0 160GB          | 3         | 3      | 0.44%   |
| WDC WD10EZEX-60M2NA0 1TB             | 3         | 3      | 0.44%   |
| Toshiba MQ04ABF100 1TB               | 3         | 3      | 0.44%   |
| Toshiba MK6475GSX 640GB              | 3         | 3      | 0.44%   |
| SSSTC CVB-8D128-HP 128GB             | 3         | 3      | 0.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 3         | 3      | 0.44%   |
| Seagate ST980811AS 80GB              | 3         | 3      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 175    | 24.78%  |
| WDC                 | 151       | 165    | 22.54%  |
| Hitachi             | 70        | 71     | 10.45%  |
| Toshiba             | 67        | 69     | 10%     |
| Samsung Electronics | 52        | 56     | 7.76%   |
| HGST                | 19        | 19     | 2.84%   |
| Kingston            | 16        | 17     | 2.39%   |
| SanDisk             | 15        | 15     | 2.24%   |
| Maxtor              | 15        | 17     | 2.24%   |
| SK hynix            | 14        | 14     | 2.09%   |
| A-DATA Technology   | 9         | 9      | 1.34%   |
| Intel               | 8         | 8      | 1.19%   |
| China               | 8         | 8      | 1.19%   |
| Micron Technology   | 5         | 5      | 0.75%   |
| SSSTC               | 4         | 4      | 0.6%    |
| SPCC                | 4         | 4      | 0.6%    |
| Crucial             | 4         | 4      | 0.6%    |
| Netac               | 3         | 3      | 0.45%   |
| LITEONIT            | 3         | 3      | 0.45%   |
| XPG                 | 2         | 2      | 0.3%    |
| OCZ                 | 2         | 2      | 0.3%    |
| Intenso             | 2         | 2      | 0.3%    |
| ExcelStor           | 2         | 2      | 0.3%    |
| ASMT                | 2         | 2      | 0.3%    |
| XrayDisk            | 1         | 1      | 0.15%   |
| Wibtek              | 1         | 2      | 0.15%   |
| USB3.0              | 1         | 1      | 0.15%   |
| SandForce           | 1         | 1      | 0.15%   |
| SAGE                | 1         | 1      | 0.15%   |
| Reeinno             | 1         | 1      | 0.15%   |
| PNY                 | 1         | 1      | 0.15%   |
| Plextor             | 1         | 1      | 0.15%   |
| OCZ-AGIL            | 1         | 1      | 0.15%   |
| LITEON              | 1         | 1      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| KINGCOMP            | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| INNOVATION IT       | 1         | 1      | 0.15%   |
| HS-SSD-C100         | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 175    | 31.26%  |
| WDC                 | 142       | 155    | 26.74%  |
| Hitachi             | 70        | 71     | 13.18%  |
| Toshiba             | 67        | 69     | 12.62%  |
| Samsung Electronics | 44        | 47     | 8.29%   |
| HGST                | 19        | 19     | 3.58%   |
| Maxtor              | 15        | 17     | 2.82%   |
| ExcelStor           | 2         | 2      | 0.38%   |
| USB3.0              | 1         | 1      | 0.19%   |
| SAGE                | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |
| ASMT                | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 491       | 561    | 78.18%  |
| SSD  | 122       | 128    | 19.43%  |
| NVMe | 15        | 15     | 2.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-00ZCT0 320GB             | 3         | 3      | 11.11%  |
| Toshiba MK2555GSX 250GB                 | 2         | 2      | 7.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1      | 3.7%    |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 1      | 3.7%    |
| WDC WD10EZEX-00BN5A0 1TB                | 1         | 1      | 3.7%    |
| Transcend TS1TMTE110S 1TB               | 1         | 1      | 3.7%    |
| Toshiba MQ01ABF032 320GB                | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 3.7%    |
| Toshiba MK7575GSX 752GB                 | 1         | 1      | 3.7%    |
| Toshiba MK3265GSXV 320GB                | 1         | 1      | 3.7%    |
| Toshiba MK2575GSX 250GB                 | 1         | 1      | 3.7%    |
| Toshiba MK1234GSX 120GB                 | 1         | 1      | 3.7%    |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 3.7%    |
| Seagate ST9320325AS 320GB               | 1         | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1      | 3.7%    |
| Seagate ST3320613AS 320GB               | 1         | 1      | 3.7%    |
| Seagate ST3320418AS 320GB               | 1         | 1      | 3.7%    |
| Seagate ST3250318AS 250GB               | 1         | 1      | 3.7%    |
| Seagate ST31000528AS 1TB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD203WI 2TB         | 1         | 1      | 3.7%    |
| Intel SSDSCKKF256H6 SATA 256GB          | 1         | 1      | 3.7%    |
| Hitachi HTS545032B9A300 320GB           | 1         | 1      | 3.7%    |
| Hitachi HDS721050CLA360 500GB           | 1         | 1      | 3.7%    |
| Apple HDD HTS541010A9E662 1TB           | 1         | 1      | 3.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 29.63%  |
| WDC                 | 6         | 6      | 22.22%  |
| Seagate             | 6         | 6      | 22.22%  |
| Hitachi             | 2         | 2      | 7.41%   |
| Transcend           | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1990      | 3063   | 66.36%  |
| Malfunc  | 615       | 704    | 20.51%  |
| Detected | 367       | 455    | 12.24%  |
| Failed   | 27        | 27     | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1871      | 58.67%  |
| AMD                              | 473       | 14.83%  |
| Samsung Electronics              | 183       | 5.74%   |
| SanDisk                          | 117       | 3.67%   |
| Kingston Technology Company      | 79        | 2.48%   |
| Phison Electronics               | 44        | 1.38%   |
| SK hynix                         | 43        | 1.35%   |
| Micron/Crucial Technology        | 40        | 1.25%   |
| ASMedia Technology               | 37        | 1.16%   |
| Silicon Motion                   | 33        | 1.03%   |
| Nvidia                           | 32        | 1%      |
| Micron Technology                | 30        | 0.94%   |
| JMicron Technology               | 28        | 0.88%   |
| Marvell Technology Group         | 25        | 0.78%   |
| MAXIO Technology (Hangzhou)      | 24        | 0.75%   |
| KIOXIA                           | 23        | 0.72%   |
| ADATA Technology                 | 18        | 0.56%   |
| Realtek Semiconductor            | 14        | 0.44%   |
| Toshiba America Info Systems     | 13        | 0.41%   |
| Solid State Storage Technology   | 13        | 0.41%   |
| Shenzhen Longsys Electronics     | 10        | 0.31%   |
| VIA Technologies                 | 7         | 0.22%   |
| Broadcom / LSI                   | 5         | 0.16%   |
| Union Memory (Shenzhen)          | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 4         | 0.13%   |
| LSI Logic / Symbios Logic        | 3         | 0.09%   |
| Lite-On Technology               | 3         | 0.09%   |
| INNOGRIT                         | 3         | 0.09%   |
| Netac Technology                 | 2         | 0.06%   |
| Transcend                        | 1         | 0.03%   |
| Sony                             | 1         | 0.03%   |
| Solidigm                         | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Nextorage                        | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| Integrated Technology Express    | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 279       | 7.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 135       | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 117       | 3.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 113       | 3.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 94        | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 91        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 88        | 2.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 84        | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 75        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 75        | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 73        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 71        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 63        | 1.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 60        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 56        | 1.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 53        | 1.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 52        | 1.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 51        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 49        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 49        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 47        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 45        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 45        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 43        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 39        | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 39        | 1.07%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 35        | 0.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 34        | 0.93%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 34        | 0.93%   |
| Intel SATA Controller [RAID mode]                                                       | 33        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 33        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 33        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 30        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 29        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 29        | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 28        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 27        | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 27        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25        | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 25        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1999      | 62.2%   |
| NVMe | 665       | 20.69%  |
| IDE  | 359       | 11.17%  |
| RAID | 182       | 5.66%   |
| SAS  | 5         | 0.16%   |
| SCSI | 4         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2009      | 78.02%  |
| AMD    | 566       | 21.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz       | 63        | 2.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 36        | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 26        | 1.01%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 19        | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 18        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 17        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor       | 17        | 0.66%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 16        | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 15        | 0.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 15        | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 15        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 14        | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 14        | 0.54%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 13        | 0.5%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 13        | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 12        | 0.47%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.47%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 12        | 0.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 12        | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 12        | 0.47%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 12        | 0.47%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 12        | 0.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 12        | 0.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 12        | 0.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 11        | 0.43%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 11        | 0.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 11        | 0.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 11        | 0.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 11        | 0.43%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 11        | 0.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 11        | 0.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 10        | 0.39%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 10        | 0.39%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 10        | 0.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 10        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 595       | 23.09%  |
| Intel Core i7           | 307       | 11.91%  |
| Intel Core i3           | 269       | 10.44%  |
| Intel Celeron           | 265       | 10.28%  |
| Other                   | 170       | 6.6%    |
| AMD Ryzen 5             | 130       | 5.04%   |
| Intel Pentium           | 96        | 3.73%   |
| AMD Ryzen 7             | 94        | 3.65%   |
| Intel Core 2 Duo        | 91        | 3.53%   |
| Intel Pentium Dual-Core | 49        | 1.9%    |
| AMD Ryzen 3             | 43        | 1.67%   |
| Intel Xeon              | 41        | 1.59%   |
| Intel Atom              | 35        | 1.36%   |
| Intel Core 2 Quad       | 31        | 1.2%    |
| AMD FX                  | 29        | 1.13%   |
| AMD Ryzen 9             | 27        | 1.05%   |
| AMD A6                  | 22        | 0.85%   |
| AMD A8                  | 19        | 0.74%   |
| AMD A4                  | 18        | 0.7%    |
| Intel Pentium Silver    | 17        | 0.66%   |
| AMD Athlon II X2        | 16        | 0.62%   |
| AMD Athlon              | 14        | 0.54%   |
| Intel Pentium Dual      | 13        | 0.5%    |
| AMD A10                 | 13        | 0.5%    |
| Intel Core 2            | 12        | 0.47%   |
| AMD Ryzen 5 PRO         | 12        | 0.47%   |
| Intel Genuine           | 11        | 0.43%   |
| AMD Phenom II X4        | 11        | 0.43%   |
| AMD E                   | 11        | 0.43%   |
| AMD E1                  | 9         | 0.35%   |
| AMD Athlon 64 X2        | 9         | 0.35%   |
| Intel Pentium Gold      | 8         | 0.31%   |
| AMD E2                  | 7         | 0.27%   |
| AMD Sempron             | 5         | 0.19%   |
| Intel Pentium D         | 4         | 0.16%   |
| Intel Core i9           | 4         | 0.16%   |
| AMD Ryzen 7 PRO         | 4         | 0.16%   |
| AMD GX                  | 4         | 0.16%   |
| AMD Athlon II Dual-Core | 4         | 0.16%   |
| Intel Pentium 4         | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1249      | 48.47%  |
| 4      | 819       | 31.78%  |
| 6      | 218       | 8.46%   |
| 8      | 129       | 5.01%   |
| 1      | 64        | 2.48%   |
| 12     | 34        | 1.32%   |
| 10     | 22        | 0.85%   |
| 14     | 14        | 0.54%   |
| 16     | 11        | 0.43%   |
| 3      | 11        | 0.43%   |
| 24     | 4         | 0.16%   |
| 36     | 1         | 0.04%   |
| 5      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2564      | 99.57%  |
| 2      | 9         | 0.35%   |
| 16     | 1         | 0.04%   |
| 14     | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1498      | 58.15%  |
| 1      | 1071      | 41.58%  |
| 8      | 3         | 0.12%   |
| 4      | 3         | 0.12%   |
| 12     | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2575      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2040      | 79.22%  |
| 0x08108109 | 44        | 1.71%   |
| 0x0a50000d | 36        | 1.4%    |
| 0x010000c8 | 23        | 0.89%   |
| 0x0a20120a | 22        | 0.85%   |
| 0x08608103 | 18        | 0.7%    |
| 0x06001119 | 18        | 0.7%    |
| 0x08701030 | 17        | 0.66%   |
| 0x08701021 | 17        | 0.66%   |
| 0x06006705 | 17        | 0.66%   |
| 0x0a50000c | 16        | 0.62%   |
| 0x0800820d | 14        | 0.54%   |
| 0x06000822 | 14        | 0.54%   |
| 0x0600611a | 13        | 0.5%    |
| 0x0a404102 | 12        | 0.47%   |
| 0x0810100b | 12        | 0.47%   |
| 0x06003106 | 12        | 0.47%   |
| 0x0500010d | 12        | 0.47%   |
| 0x08600106 | 11        | 0.43%   |
| 0x08108102 | 9         | 0.35%   |
| 0x010000b6 | 9         | 0.35%   |
| 0x08101016 | 8         | 0.31%   |
| 0x0700010b | 8         | 0.31%   |
| 0x05000028 | 8         | 0.31%   |
| 0x06000817 | 7         | 0.27%   |
| 0x0a601206 | 6         | 0.23%   |
| 0x06003104 | 6         | 0.23%   |
| 0x0600081c | 6         | 0.23%   |
| 0x05000101 | 6         | 0.23%   |
| 0x0a50000f | 5         | 0.19%   |
| 0x0a201025 | 5         | 0.19%   |
| 0x08608104 | 5         | 0.19%   |
| 0x08200103 | 5         | 0.19%   |
| 0x08001138 | 5         | 0.19%   |
| 0x03000027 | 5         | 0.19%   |
| 0x03000014 | 5         | 0.19%   |
| 0x0a601203 | 4         | 0.16%   |
| 0x08a00006 | 4         | 0.16%   |
| 0x08600109 | 4         | 0.16%   |
| 0x08101007 | 4         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 267       | 10.36%  |
| Haswell          | 237       | 9.2%    |
| IvyBridge        | 220       | 8.54%   |
| SandyBridge      | 216       | 8.39%   |
| Penryn           | 150       | 5.82%   |
| Skylake          | 136       | 5.28%   |
| Westmere         | 103       | 4%      |
| Goldmont plus    | 102       | 3.96%   |
| Zen 3            | 96        | 3.73%   |
| Alderlake Hybrid | 84        | 3.26%   |
| Silvermont       | 77        | 2.99%   |
| Zen+             | 75        | 2.91%   |
| Core             | 74        | 2.87%   |
| Unknown          | 65        | 2.52%   |
| CometLake        | 61        | 2.37%   |
| Zen 2            | 59        | 2.29%   |
| Goldmont         | 53        | 2.06%   |
| Broadwell        | 52        | 2.02%   |
| Piledriver       | 50        | 1.94%   |
| K10              | 50        | 1.94%   |
| IceLake          | 47        | 1.82%   |
| Zen              | 39        | 1.51%   |
| TigerLake        | 38        | 1.48%   |
| Excavator        | 34        | 1.32%   |
| Bobcat           | 27        | 1.05%   |
| Nehalem          | 25        | 0.97%   |
| Bonnell          | 25        | 0.97%   |
| Tremont          | 20        | 0.78%   |
| K8 Hammer        | 20        | 0.78%   |
| Steamroller      | 19        | 0.74%   |
| Gracemont        | 13        | 0.5%    |
| K10 Llano        | 12        | 0.47%   |
| Jaguar           | 11        | 0.43%   |
| Puma             | 7         | 0.27%   |
| NetBurst         | 7         | 0.27%   |
| K8 & K10 hybrid  | 4         | 0.16%   |
| Bulldozer        | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1574      | 55.31%  |
| AMD                              | 646       | 22.7%   |
| Nvidia                           | 615       | 21.61%  |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Red Hat                          | 2         | 0.07%   |
| Matrox Electronics Systems       | 2         | 0.07%   |
| ATI Technologies                 | 2         | 0.07%   |
| ASPEED Technology                | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 170       | 5.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 101       | 3.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 91        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 73        | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 70        | 2.41%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 56        | 1.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 56        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 1.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.65%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 48        | 1.65%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 47        | 1.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 43        | 1.48%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 38        | 1.31%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 35        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 1.17%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 33        | 1.14%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 33        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 33        | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 30        | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 0.96%   |
| AMD Lucienne                                                                             | 26        | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 22        | 0.76%   |
| Intel JasperLake [UHD Graphics]                                                          | 21        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 20        | 0.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 0.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 0.69%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 20        | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 18        | 0.62%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 18        | 0.62%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 0.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 0.62%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 18        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1226      | 47.52%  |
| 1 x AMD                | 549       | 21.28%  |
| 1 x Nvidia             | 398       | 15.43%  |
| Intel + Nvidia         | 191       | 7.4%    |
| 2 x Intel              | 104       | 4.03%   |
| Intel + AMD            | 50        | 1.94%   |
| 2 x AMD                | 27        | 1.05%   |
| AMD + Nvidia           | 21        | 0.81%   |
| 2 x Nvidia             | 3         | 0.12%   |
| 1 x SiS                | 3         | 0.12%   |
| 2 x Intel + 1 x Nvidia | 2         | 0.08%   |
| 1 x Red Hat            | 2         | 0.08%   |
| 1 x Matrox             | 2         | 0.08%   |
| Nvidia + ASPEED        | 1         | 0.04%   |
| AMD + ASPEED           | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2501      | 97.09%  |
| Unknown     | 61        | 2.37%   |
| Proprietary | 14        | 0.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1392      | 53.93%  |
| 1.01-2.0   | 330       | 12.79%  |
| 0.01-0.5   | 300       | 11.62%  |
| 0.51-1.0   | 218       | 8.45%   |
| 3.01-4.0   | 153       | 5.93%   |
| 7.01-8.0   | 92        | 3.56%   |
| 8.01-16.0  | 36        | 1.39%   |
| 5.01-6.0   | 35        | 1.36%   |
| 2.01-3.0   | 20        | 0.77%   |
| 16.01-24.0 | 3         | 0.12%   |
| 4.01-5.0   | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 338       | 13.05%  |
| AU Optronics            | 275       | 10.62%  |
| BOE                     | 223       | 8.61%   |
| LG Display              | 220       | 8.49%   |
| Chimei Innolux          | 210       | 8.11%   |
| Goldstar                | 141       | 5.44%   |
| Dell                    | 115       | 4.44%   |
| Acer                    | 100       | 3.86%   |
| Hewlett-Packard         | 98        | 3.78%   |
| AOC                     | 75        | 2.9%    |
| Philips                 | 61        | 2.36%   |
| BenQ                    | 52        | 2.01%   |
| Lenovo                  | 46        | 1.78%   |
| Ancor Communications    | 45        | 1.74%   |
| Chi Mei Optoelectronics | 42        | 1.62%   |
| ViewSonic               | 37        | 1.43%   |
| Apple                   | 33        | 1.27%   |
| InfoVision              | 26        | 1%      |
| Iiyama                  | 25        | 0.97%   |
| Sony                    | 24        | 0.93%   |
| RGT                     | 24        | 0.93%   |
| ASUSTek Computer        | 23        | 0.89%   |
| Sharp                   | 22        | 0.85%   |
| PANDA                   | 20        | 0.77%   |
| MSI                     | 18        | 0.69%   |
| NEC Computers           | 16        | 0.62%   |
| Fujitsu Siemens         | 15        | 0.58%   |
| LG Philips              | 14        | 0.54%   |
| Eizo                    | 12        | 0.46%   |
| Panasonic               | 11        | 0.42%   |
| Toshiba                 | 10        | 0.39%   |
| HKC                     | 10        | 0.39%   |
| Unknown                 | 9         | 0.35%   |
| HannStar                | 9         | 0.35%   |
| Unknown (XXX)           | 8         | 0.31%   |
| RTK                     | 8         | 0.31%   |
| Hitachi                 | 8         | 0.31%   |
| Sceptre Tech            | 7         | 0.27%   |
| ___                     | 6         | 0.23%   |
| Medion                  | 5         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 44        | 1.69%   |
| RGT LCD Monitor RGT5211 1366x768 518x333mm 24.2-inch                      | 23        | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 17        | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 12        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 12        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 10        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 9         | 0.34%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 9         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.31%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 8         | 0.31%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                        | 8         | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 7         | 0.27%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch             | 7         | 0.27%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch      | 6         | 0.23%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 6         | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 6         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 5         | 0.19%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 5         | 0.19%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                        | 5         | 0.19%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 5         | 0.19%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 5         | 0.19%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 5         | 0.19%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch               | 5         | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 5         | 0.19%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 5         | 0.19%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch              | 5         | 0.19%   |
| Dell P2311H DEL4066 1920x1080 510x290mm 23.1-inch                         | 5         | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 5         | 0.19%   |
| BOE LCD Monitor BOE0A84 1920x1200 286x179mm 13.3-inch                     | 5         | 0.19%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                      | 5         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1063      | 41.65%  |
| 1366x768 (WXGA)    | 633       | 24.8%   |
| 3840x2160 (4K)     | 127       | 4.98%   |
| 1600x900 (HD+)     | 117       | 4.58%   |
| 2560x1440 (QHD)    | 88        | 3.45%   |
| 1280x1024 (SXGA)   | 80        | 3.13%   |
| 1440x900 (WXGA+)   | 75        | 2.94%   |
| 1920x1200 (WUXGA)  | 74        | 2.9%    |
| 1680x1050 (WSXGA+) | 69        | 2.7%    |
| 1280x800 (WXGA)    | 47        | 1.84%   |
| 1360x768           | 25        | 0.98%   |
| 3440x1440          | 15        | 0.59%   |
| 1920x540           | 14        | 0.55%   |
| 2880x1800          | 13        | 0.51%   |
| 2560x1080          | 12        | 0.47%   |
| 2560x1600          | 11        | 0.43%   |
| 1024x768 (XGA)     | 11        | 0.43%   |
| 1024x600           | 11        | 0.43%   |
| 1600x1200          | 10        | 0.39%   |
| 2160x1440          | 8         | 0.31%   |
| 2288x1287          | 7         | 0.27%   |
| 1280x720 (HD)      | 6         | 0.24%   |
| 2880x1920          | 5         | 0.2%    |
| 2256x1504          | 4         | 0.16%   |
| 3840x2400          | 3         | 0.12%   |
| 3200x1800 (QHD+)   | 3         | 0.12%   |
| 1280x960           | 3         | 0.12%   |
| Unknown            | 3         | 0.12%   |
| 800x1280           | 2         | 0.08%   |
| 3840x1600          | 2         | 0.08%   |
| 2560x1397          | 2         | 0.08%   |
| 1152x864           | 2         | 0.08%   |
| 3072x1920          | 1         | 0.04%   |
| 2880x1620          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |
| 1600x2560          | 1         | 0.04%   |
| 1360x765           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 627       | 24.24%  |
| 13      | 225       | 8.7%    |
| 24      | 207       | 8%      |
| 23      | 181       | 7%      |
| 14      | 174       | 6.73%   |
| 17      | 171       | 6.61%   |
| 27      | 166       | 6.42%   |
| 21      | 162       | 6.26%   |
| 19      | 84        | 3.25%   |
| 31      | 77        | 2.98%   |
| 18      | 64        | 2.47%   |
| 20      | 54        | 2.09%   |
| 22      | 47        | 1.82%   |
| 12      | 45        | 1.74%   |
| 11      | 39        | 1.51%   |
| Unknown | 29        | 1.12%   |
| 84      | 25        | 0.97%   |
| 16      | 25        | 0.97%   |
| 72      | 21        | 0.81%   |
| 34      | 21        | 0.81%   |
| 10      | 21        | 0.81%   |
| 32      | 13        | 0.5%    |
| 54      | 10        | 0.39%   |
| 40      | 8         | 0.31%   |
| 28      | 8         | 0.31%   |
| 26      | 7         | 0.27%   |
| 25      | 7         | 0.27%   |
| 63      | 6         | 0.23%   |
| 46      | 6         | 0.23%   |
| 52      | 5         | 0.19%   |
| 37      | 5         | 0.19%   |
| 142     | 4         | 0.15%   |
| 39      | 4         | 0.15%   |
| 75      | 3         | 0.12%   |
| 74      | 3         | 0.12%   |
| 48      | 3         | 0.12%   |
| 43      | 3         | 0.12%   |
| 29      | 3         | 0.12%   |
| 85      | 2         | 0.08%   |
| 42      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 989       | 38.41%  |
| 501-600        | 548       | 21.28%  |
| 401-500        | 371       | 14.41%  |
| 201-300        | 190       | 7.38%   |
| 351-400        | 186       | 7.22%   |
| 601-700        | 98        | 3.81%   |
| 1501-2000      | 54        | 2.1%    |
| 1001-1500      | 38        | 1.48%   |
| 701-800        | 37        | 1.44%   |
| Unknown        | 29        | 1.13%   |
| 801-900        | 20        | 0.78%   |
| 901-1000       | 7         | 0.27%   |
| More than 2000 | 4         | 0.16%   |
| 101-200        | 2         | 0.08%   |
| 1-100          | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1986      | 79.6%   |
| 16/10   | 323       | 12.95%  |
| 5/4     | 87        | 3.49%   |
| 3/2     | 27        | 1.08%   |
| 21/9    | 27        | 1.08%   |
| 4/3     | 26        | 1.04%   |
| Unknown | 7         | 0.28%   |
| 1.00    | 4         | 0.16%   |
| 32/9    | 3         | 0.12%   |
| 0.63    | 2         | 0.08%   |
| 1.96    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 624       | 24.19%  |
| 201-250        | 443       | 17.17%  |
| 81-90          | 323       | 12.52%  |
| 151-200        | 188       | 7.29%   |
| 301-350        | 172       | 6.67%   |
| 351-500        | 119       | 4.61%   |
| 251-300        | 119       | 4.61%   |
| 121-130        | 106       | 4.11%   |
| 141-150        | 103       | 3.99%   |
| More than 1000 | 89        | 3.45%   |
| 71-80          | 76        | 2.95%   |
| 61-70          | 41        | 1.59%   |
| 51-60          | 40        | 1.55%   |
| 501-1000       | 35        | 1.36%   |
| Unknown        | 29        | 1.12%   |
| 111-120        | 22        | 0.85%   |
| 41-50          | 20        | 0.78%   |
| 131-140        | 19        | 0.74%   |
| 91-100         | 8         | 0.31%   |
| 1-40           | 4         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 998       | 39.38%  |
| 101-120       | 779       | 30.74%  |
| 121-160       | 525       | 20.72%  |
| 161-240       | 111       | 4.38%   |
| 1-50          | 69        | 2.72%   |
| Unknown       | 29        | 1.14%   |
| More than 240 | 23        | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2325      | 90.05%  |
| 2     | 163       | 6.31%   |
| 0     | 84        | 3.25%   |
| 3     | 10        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1538      | 41.42%  |
| Intel                             | 1070      | 28.82%  |
| Qualcomm Atheros                  | 405       | 10.91%  |
| Broadcom                          | 187       | 5.04%   |
| MediaTek                          | 55        | 1.48%   |
| TP-Link                           | 45        | 1.21%   |
| Ralink Technology                 | 40        | 1.08%   |
| Broadcom Limited                  | 40        | 1.08%   |
| Ralink                            | 33        | 0.89%   |
| ASIX Electronics                  | 32        | 0.86%   |
| Nvidia                            | 28        | 0.75%   |
| Marvell Technology Group          | 26        | 0.7%    |
| Qualcomm Atheros Communications   | 17        | 0.46%   |
| D-Link                            | 16        | 0.43%   |
| JMicron Technology                | 15        | 0.4%    |
| Samsung Electronics               | 12        | 0.32%   |
| Ericsson Business Mobile Networks | 12        | 0.32%   |
| Dell                              | 12        | 0.32%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.3%    |
| Huawei Technologies               | 10        | 0.27%   |
| Sierra Wireless                   | 9         | 0.24%   |
| NetGear                           | 7         | 0.19%   |
| Qualcomm                          | 6         | 0.16%   |
| OPPO Electronics                  | 6         | 0.16%   |
| ASUSTek Computer                  | 5         | 0.13%   |
| Xiaomi                            | 4         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.11%   |
| Lenovo                            | 4         | 0.11%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| DisplayLink                       | 4         | 0.11%   |
| VIA Technologies                  | 3         | 0.08%   |
| Motorola PCS                      | 3         | 0.08%   |
| Microchip Technology              | 3         | 0.08%   |
| Mercucys                          | 3         | 0.08%   |
| Sundance Technology Inc / IC Plus | 2         | 0.05%   |
| Shenzhen Goodix Technology        | 2         | 0.05%   |
| Microsoft                         | 2         | 0.05%   |
| LG Electronics                    | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| Fibocom                           | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 977       | 22.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 210       | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 130       | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 86        | 1.98%   |
| Intel Wireless 8265 / 8275                                             | 62        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 61        | 1.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 58        | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 57        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 55        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 55        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 51        | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 48        | 1.11%   |
| Intel Wireless 7265                                                    | 47        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                    | 45        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 43        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 41        | 0.95%   |
| Intel Wireless 7260                                                    | 40        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 40        | 0.92%   |
| Intel Wireless 8260                                                    | 39        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 38        | 0.88%   |
| Intel Ethernet Controller I225-V                                       | 33        | 0.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 32        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 31        | 0.72%   |
| Realtek 802.11n WLAN Adapter                                           | 31        | 0.72%   |
| Intel Wi-Fi 6 AX201                                                    | 31        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 30        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 30        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 29        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 0.67%   |
| Intel Wireless 3165                                                    | 28        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 28        | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 26        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 25        | 0.58%   |
| Intel 82579V Gigabit Network Connection                                | 25        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                  | 23        | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 23        | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 22        | 0.51%   |
| Intel Ethernet Connection I219-LM                                      | 22        | 0.51%   |
| Intel Wireless 3160                                                    | 21        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 734       | 39.04%  |
| Realtek Semiconductor           | 451       | 23.99%  |
| Qualcomm Atheros                | 312       | 16.6%   |
| Broadcom                        | 105       | 5.59%   |
| MediaTek                        | 52        | 2.77%   |
| TP-Link                         | 41        | 2.18%   |
| Ralink Technology               | 40        | 2.13%   |
| Ralink                          | 33        | 1.76%   |
| Broadcom Limited                | 25        | 1.33%   |
| Qualcomm Atheros Communications | 17        | 0.9%    |
| D-Link                          | 16        | 0.85%   |
| Sierra Wireless                 | 9         | 0.48%   |
| NetGear                         | 7         | 0.37%   |
| ASUSTek Computer                | 5         | 0.27%   |
| Mercucys                        | 3         | 0.16%   |
| Dell                            | 3         | 0.16%   |
| Qualcomm                        | 2         | 0.11%   |
| Microsoft                       | 2         | 0.11%   |
| Marvell Technology Group        | 2         | 0.11%   |
| Fibocom                         | 2         | 0.11%   |
| D-Link System                   | 2         | 0.11%   |
| BUFFALO                         | 2         | 0.11%   |
| Belkin Components               | 2         | 0.11%   |
| AVM                             | 2         | 0.11%   |
| ZyXEL Communications            | 1         | 0.05%   |
| ZyDAS                           | 1         | 0.05%   |
| Tenda                           | 1         | 0.05%   |
| Samsung Electronics             | 1         | 0.05%   |
| Realtek                         | 1         | 0.05%   |
| Linksys                         | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Gemtek                          | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| CyberTAN Technology             | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 86        | 4.57%   |
| Intel Wireless 8265 / 8275                                              | 62        | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 61        | 3.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 57        | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 55        | 2.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 53        | 2.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 51        | 2.71%   |
| Intel Wireless 7265                                                     | 47        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                     | 45        | 2.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 2.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.18%   |
| Intel Wireless 7260                                                     | 40        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 2.12%   |
| Intel Wireless 8260                                                     | 39        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 38        | 2.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 32        | 1.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 31        | 1.65%   |
| Realtek 802.11n WLAN Adapter                                            | 31        | 1.65%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 30        | 1.59%   |
| Intel Wireless 3165                                                     | 28        | 1.49%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 22        | 1.17%   |
| Intel Wireless 3160                                                     | 21        | 1.12%   |
| Realtek 802.11ac NIC                                                    | 20        | 1.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 19        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 17        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 17        | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 16        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 0.8%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 15        | 0.8%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 15        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 0.74%   |
| Intel WiFi Link 5100                                                    | 14        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 14        | 0.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 14        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1307      | 55.4%   |
| Intel                             | 622       | 26.37%  |
| Qualcomm Atheros                  | 134       | 5.68%   |
| Broadcom                          | 104       | 4.41%   |
| ASIX Electronics                  | 32        | 1.36%   |
| Nvidia                            | 28        | 1.19%   |
| Marvell Technology Group          | 24        | 1.02%   |
| JMicron Technology                | 15        | 0.64%   |
| Broadcom Limited                  | 15        | 0.64%   |
| Samsung Electronics               | 11        | 0.47%   |
| Huawei Technologies               | 8         | 0.34%   |
| OPPO Electronics                  | 6         | 0.25%   |
| TP-Link                           | 5         | 0.21%   |
| Xiaomi                            | 4         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.17%   |
| Qualcomm                          | 4         | 0.17%   |
| Lenovo                            | 4         | 0.17%   |
| DisplayLink                       | 4         | 0.17%   |
| VIA Technologies                  | 3         | 0.13%   |
| Motorola PCS                      | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| MediaTek                          | 3         | 0.13%   |
| Sundance Technology Inc / IC Plus | 2         | 0.08%   |
| LG Electronics                    | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| Aquantia                          | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Mellanox Technologies             | 1         | 0.04%   |
| Hewlett-Packard                   | 1         | 0.04%   |
| Attansic Technology               | 1         | 0.04%   |
| Apple                             | 1         | 0.04%   |
| 3Com                              | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 977       | 40.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 210       | 8.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 130       | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                      | 55        | 2.29%   |
| Intel Ethernet Connection I217-LM                                      | 48        | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 1.75%   |
| Intel Ethernet Controller I225-V                                       | 33        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 30        | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 29        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 28        | 1.16%   |
| Intel 82579V Gigabit Network Connection                                | 25        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 23        | 0.96%   |
| Intel Ethernet Connection I219-LM                                      | 22        | 0.91%   |
| Intel I211 Gigabit Network Connection                                  | 19        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 18        | 0.75%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.75%   |
| Nvidia MCP61 Ethernet                                                  | 15        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 0.58%   |
| Intel 82578DM Gigabit Network Connection                               | 14        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 14        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 13        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 13        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13        | 0.54%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 13        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 13        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 12        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 12        | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 12        | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 12        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 11        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 11        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 10        | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                  | 10        | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 9         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2259      | 54.87%  |
| WiFi     | 1813      | 44.04%  |
| Modem    | 43        | 1.04%   |
| Unknown  | 2         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1315      | 52.58%  |
| WiFi     | 1178      | 47.1%   |
| Modem    | 8         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1296      | 50.33%  |
| 1     | 1188      | 46.14%  |
| 0     | 60        | 2.33%   |
| 3     | 26        | 1.01%   |
| 4     | 5         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1695      | 65.57%  |
| Yes  | 890       | 34.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 588       | 42.06%  |
| Realtek Semiconductor           | 227       | 16.24%  |
| Qualcomm Atheros Communications | 102       | 7.3%    |
| Cambridge Silicon Radio         | 95        | 6.8%    |
| Broadcom                        | 75        | 5.36%   |
| IMC Networks                    | 62        | 4.43%   |
| Foxconn / Hon Hai               | 50        | 3.58%   |
| Lite-On Technology              | 47        | 3.36%   |
| Apple                           | 39        | 2.79%   |
| Dell                            | 23        | 1.65%   |
| MediaTek                        | 14        | 1%      |
| Hewlett-Packard                 | 13        | 0.93%   |
| Toshiba                         | 11        | 0.79%   |
| ASUSTek Computer                | 11        | 0.79%   |
| TP-Link                         | 9         | 0.64%   |
| Unknown                         | 7         | 0.5%    |
| Ralink                          | 5         | 0.36%   |
| Foxconn International           | 4         | 0.29%   |
| USI                             | 2         | 0.14%   |
| Realtek                         | 2         | 0.14%   |
| Marvell Semiconductor           | 2         | 0.14%   |
| Integrated System Solution      | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Qcom                            | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Dynex                           | 1         | 0.07%   |
| Alps Electric                   | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 235       | 16.81%  |
| Realtek Bluetooth Radio                             | 161       | 11.52%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 95        | 6.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 92        | 6.58%   |
| Intel AX201 Bluetooth                               | 78        | 5.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 49        | 3.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 43        | 3.08%   |
| Intel AX200 Bluetooth                               | 43        | 3.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 40        | 2.86%   |
| IMC Networks Bluetooth Radio                        | 35        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 28        | 2%      |
| Intel AX210 Bluetooth                               | 27        | 1.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 21        | 1.5%    |
| Intel Bluetooth Device                              | 19        | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 1.22%   |
| Apple Bluetooth Host Controller                     | 17        | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1%      |
| MediaTek Wireless_Device                            | 13        | 0.93%   |
| Lite-On Bluetooth Device                            | 13        | 0.93%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.86%   |
| Apple Bluetooth USB Host Controller                 | 11        | 0.79%   |
| IMC Networks Bluetooth Device                       | 10        | 0.72%   |
| TP-Link TP-T@- UB500 Adapter                        | 9         | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 9         | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.5%    |
| IMC Networks Wireless_Device                        | 7         | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.5%    |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 0.5%    |
| Unknown                                             | 7         | 0.5%    |
| Lite-On Wireless_Device                             | 6         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1971      | 58.52%  |
| AMD                                          | 684       | 20.31%  |
| Nvidia                                       | 490       | 14.55%  |
| C-Media Electronics                          | 44        | 1.31%   |
| Creative Labs                                | 17        | 0.5%    |
| Texas Instruments                            | 12        | 0.36%   |
| Generalplus Technology                       | 11        | 0.33%   |
| ASUSTek Computer                             | 10        | 0.3%    |
| Realtek Semiconductor                        | 8         | 0.24%   |
| Creative Technology                          | 8         | 0.24%   |
| GN Netcom                                    | 6         | 0.18%   |
| Razer USA                                    | 5         | 0.15%   |
| JMTek                                        | 5         | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.12%   |
| Tenx Technology                              | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.12%   |
| Lenovo                                       | 4         | 0.12%   |
| Focusrite-Novation                           | 4         | 0.12%   |
| SAVITECH                                     | 3         | 0.09%   |
| Nordic Semiconductor ASA                     | 3         | 0.09%   |
| Micro Star International                     | 3         | 0.09%   |
| M-Audio                                      | 3         | 0.09%   |
| Logitech                                     | 3         | 0.09%   |
| KTMicro                                      | 3         | 0.09%   |
| Kingston Technology                          | 3         | 0.09%   |
| Jieli Technology                             | 3         | 0.09%   |
| Bose                                         | 3         | 0.09%   |
| VIA Technologies                             | 2         | 0.06%   |
| TerraTec Electronic                          | 2         | 0.06%   |
| PreSonus Audio Electronics                   | 2         | 0.06%   |
| Plantronics                                  | 2         | 0.06%   |
| GYROCOM C&C                                  | 2         | 0.06%   |
| FiiO Electronics Technology                  | 2         | 0.06%   |
| Fifine Microphones                           | 2         | 0.06%   |
| ATI Technologies                             | 2         | 0.06%   |
| Xilinx                                       | 1         | 0.03%   |
| Valve Software                               | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| SteelSeries ApS                              | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 220       | 5.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 219       | 5.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 206       | 5.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 157       | 3.9%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 154       | 3.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 112       | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 111       | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 107       | 2.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 102       | 2.53%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 102       | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 89        | 2.21%   |
| AMD FCH Azalia Controller                                                                         | 81        | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 74        | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 73        | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 71        | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 71        | 1.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 59        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 57        | 1.42%   |
| Intel 8 Series HD Audio Controller                                                                | 57        | 1.42%   |
| Intel 200 Series PCH HD Audio                                                                     | 56        | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 53        | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 48        | 1.19%   |
| Intel Broadwell-U Audio Controller                                                                | 46        | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 46        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 43        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 42        | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 41        | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 38        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 35        | 0.87%   |
| AMD Radeon High Definition Audio Controller                                                       | 35        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 34        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 34        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 33        | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 29        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 29        | 0.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 26        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 634       | 20.5%   |
| SK hynix                     | 437       | 14.13%  |
| Kingston                     | 369       | 11.93%  |
| Unknown                      | 308       | 9.96%   |
| Micron Technology            | 288       | 9.31%   |
| Crucial                      | 152       | 4.91%   |
| Corsair                      | 122       | 3.94%   |
| G.Skill                      | 81        | 2.62%   |
| A-DATA Technology            | 60        | 1.94%   |
| Ramaxel Technology           | 55        | 1.78%   |
| Unknown (ABCD)               | 54        | 1.75%   |
| Unknown                      | 54        | 1.75%   |
| Nanya Technology             | 52        | 1.68%   |
| Elpida                       | 47        | 1.52%   |
| Smart                        | 42        | 1.36%   |
| Patriot                      | 23        | 0.74%   |
| GOODRAM                      | 23        | 0.74%   |
| Team                         | 22        | 0.71%   |
| Transcend                    | 16        | 0.52%   |
| Apacer                       | 16        | 0.52%   |
| AMD                          | 13        | 0.42%   |
| ASint Technology             | 11        | 0.36%   |
| PNY                          | 10        | 0.32%   |
| Atermiter                    | 9         | 0.29%   |
| Teikon                       | 8         | 0.26%   |
| 48spaces                     | 8         | 0.26%   |
| Goldkey                      | 7         | 0.23%   |
| Kllisre                      | 6         | 0.19%   |
| Avant                        | 6         | 0.19%   |
| Timetec                      | 5         | 0.16%   |
| Hikvision                    | 5         | 0.16%   |
| 4ea5                         | 5         | 0.16%   |
| Wodposit                     | 4         | 0.13%   |
| V-GeN                        | 4         | 0.13%   |
| Unknown (0x0E9D)             | 4         | 0.13%   |
| Smart Brazil                 | 4         | 0.13%   |
| Patriot Memory (PDP Systems) | 4         | 0.13%   |
| Kingmax Semiconductor        | 4         | 0.13%   |
| Kingmax                      | 4         | 0.13%   |
| Juhor                        | 4         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 54        | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 50        | 1.49%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 40        | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 28        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 21        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 18        | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 17        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 15        | 0.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 15        | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 13        | 0.39%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 13        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 12        | 0.36%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 12        | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 12        | 0.36%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.36%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 12        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 10        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 10        | 0.3%    |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 10        | 0.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 10        | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 10        | 0.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                       | 10        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 9         | 0.27%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 9         | 0.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 9         | 0.27%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1049      | 40.08%  |
| DDR4    | 987       | 37.71%  |
| DDR2    | 147       | 5.62%   |
| SDRAM   | 127       | 4.85%   |
| LPDDR4  | 96        | 3.67%   |
| Unknown | 90        | 3.44%   |
| DDR5    | 43        | 1.64%   |
| LPDDR5  | 29        | 1.11%   |
| LPDDR3  | 21        | 0.8%    |
| DDR     | 16        | 0.61%   |
| DRAM    | 10        | 0.38%   |
| RAM     | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1353      | 52.58%  |
| DIMM            | 1056      | 41.04%  |
| Row Of Chips    | 145       | 5.64%   |
| Unknown         | 9         | 0.35%   |
| FB-DIMM         | 4         | 0.16%   |
| Chip            | 4         | 0.16%   |
| RIMM            | 1         | 0.04%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1023      | 35.03%  |
| 4096  | 951       | 32.57%  |
| 2048  | 481       | 16.47%  |
| 16384 | 277       | 9.49%   |
| 1024  | 103       | 3.53%   |
| 32768 | 70        | 2.4%    |
| 512   | 9         | 0.31%   |
| 65536 | 1         | 0.03%   |
| 24576 | 1         | 0.03%   |
| 15616 | 1         | 0.03%   |
| 12333 | 1         | 0.03%   |
| 3072  | 1         | 0.03%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 692       | 23.77%  |
| 3200    | 320       | 10.99%  |
| 2667    | 288       | 9.89%   |
| 2400    | 250       | 8.59%   |
| 1333    | 247       | 8.49%   |
| 2133    | 116       | 3.98%   |
| 1334    | 91        | 3.13%   |
| 667     | 85        | 2.92%   |
| 800     | 79        | 2.71%   |
| 3600    | 76        | 2.61%   |
| Unknown | 68        | 2.34%   |
| 1067    | 44        | 1.51%   |
| 1867    | 35        | 1.2%    |
| 1866    | 32        | 1.1%    |
| 1066    | 28        | 0.96%   |
| 8400    | 26        | 0.89%   |
| 4800    | 26        | 0.89%   |
| 6400    | 25        | 0.86%   |
| 4199    | 24        | 0.82%   |
| 1800    | 22        | 0.76%   |
| 3733    | 21        | 0.72%   |
| 3266    | 21        | 0.72%   |
| 2666    | 20        | 0.69%   |
| 533     | 18        | 0.62%   |
| 400     | 18        | 0.62%   |
| 2048    | 16        | 0.55%   |
| 4267    | 15        | 0.52%   |
| 3800    | 15        | 0.52%   |
| 3466    | 15        | 0.52%   |
| 4000    | 14        | 0.48%   |
| 2933    | 13        | 0.45%   |
| 3400    | 11        | 0.38%   |
| 975     | 11        | 0.38%   |
| 333     | 8         | 0.27%   |
| 6000    | 7         | 0.24%   |
| 5600    | 7         | 0.24%   |
| 4266    | 7         | 0.24%   |
| 3066    | 7         | 0.24%   |
| 3000    | 7         | 0.24%   |
| 1648    | 7         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 33        | 41.77%  |
| Canon                 | 13        | 16.46%  |
| Brother Industries    | 12        | 15.19%  |
| Samsung Electronics   | 8         | 10.13%  |
| Seiko Epson           | 7         | 8.86%   |
| Prolific Technology   | 3         | 3.8%    |
| Oki Data              | 1         | 1.27%   |
| Lexmark International | 1         | 1.27%   |
| Apple                 | 1         | 1.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                | 3         | 3.75%   |
| HP DeskJet 4100 series                       | 3         | 3.75%   |
| HP DeskJet 2700 series                       | 3         | 3.75%   |
| HP DeskJet 2600 series                       | 3         | 3.75%   |
| Samsung ML-1660 Series                       | 2         | 2.5%    |
| HP LaserJet 1200                             | 2         | 2.5%    |
| HP ENVY 5000 series                          | 2         | 2.5%    |
| Canon MF110/910 Series                       | 2         | 2.5%    |
| Brother HL-L2350DW series                    | 2         | 2.5%    |
| Seiko Epson XP-2100 Series                   | 1         | 1.25%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.25%   |
| Seiko Epson L3210 Series                     | 1         | 1.25%   |
| Seiko Epson L120 Series                      | 1         | 1.25%   |
| Seiko Epson ET-4850 Series                   | 1         | 1.25%   |
| Seiko Epson ET-2710 Series                   | 1         | 1.25%   |
| Seiko Epson EPSON L300 Series                | 1         | 1.25%   |
| Samsung SCX-6x55X Series                     | 1         | 1.25%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.25%   |
| Samsung ML-1865                              | 1         | 1.25%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 1.25%   |
| Samsung M2020 Series                         | 1         | 1.25%   |
| Samsung Composite Device                     | 1         | 1.25%   |
| Oki Data MC363 Multifunction Printer         | 1         | 1.25%   |
| Lexmark International MS510dn                | 1         | 1.25%   |
| HP Printing Support                          | 1         | 1.25%   |
| HP PhotoSmart 7150                           | 1         | 1.25%   |
| HP OfficeJet Pro 7740 series                 | 1         | 1.25%   |
| HP OfficeJet Pro 6960                        | 1         | 1.25%   |
| HP Officejet J4500 series                    | 1         | 1.25%   |
| HP OfficeJet 8010 series                     | 1         | 1.25%   |
| HP OfficeJet 3830 series                     | 1         | 1.25%   |
| HP LaserJet M14-M17                          | 1         | 1.25%   |
| HP LaserJet 1020                             | 1         | 1.25%   |
| HP LaserJet 1015                             | 1         | 1.25%   |
| HP ENVY 4520 series                          | 1         | 1.25%   |
| HP DeskJet Plus 6400 series                  | 1         | 1.25%   |
| HP DeskJet 6940 series                       | 1         | 1.25%   |
| HP DeskJet 4530 series                       | 1         | 1.25%   |
| HP DeskJet 3700 series                       | 1         | 1.25%   |
| HP DeskJet 3630 series                       | 1         | 1.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 69.23%  |
| Seiko Epson     | 2         | 15.38%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                           | 3         | 23.08%  |
| Canon CanoScan LIDE 25                            | 2         | 15.38%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1         | 7.69%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 7.69%   |
| HP Scanjet G2710                                  | 1         | 7.69%   |
| HP ScanJet 2400c                                  | 1         | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 7.69%   |
| Canon CanoScan N650U/N656U                        | 1         | 7.69%   |
| Canon CanoScan LiDE 220                           | 1         | 7.69%   |
| Canon CanoScan 1220U                              | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 318       | 24.11%  |
| Microdia                               | 118       | 8.95%   |
| IMC Networks                           | 109       | 8.26%   |
| Bison Electronics                      | 105       | 7.96%   |
| Realtek Semiconductor                  | 84        | 6.37%   |
| Quanta                                 | 58        | 4.4%    |
| Sunplus Innovation Technology          | 54        | 4.09%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 3.71%   |
| Logitech                               | 47        | 3.56%   |
| Syntek                                 | 39        | 2.96%   |
| Suyin                                  | 37        | 2.81%   |
| icSpring                               | 31        | 2.35%   |
| Apple                                  | 26        | 1.97%   |
| Alcor Micro                            | 21        | 1.59%   |
| Luxvisions Innotech Limited            | 20        | 1.52%   |
| Silicon Motion                         | 18        | 1.36%   |
| Lite-On Technology                     | 18        | 1.36%   |
| Lenovo                                 | 14        | 1.06%   |
| Z-Star Microelectronics                | 13        | 0.99%   |
| Acer                                   | 12        | 0.91%   |
| Ricoh                                  | 11        | 0.83%   |
| Microsoft                              | 10        | 0.76%   |
| Importek                               | 9         | 0.68%   |
| ALi                                    | 8         | 0.61%   |
| SunplusIT                              | 6         | 0.45%   |
| Sonix Technology                       | 6         | 0.45%   |
| Unknown                                | 5         | 0.38%   |
| Y Media                                | 3         | 0.23%   |
| Tripath Technology                     | 3         | 0.23%   |
| Samsung Electronics                    | 3         | 0.23%   |
| Primax Electronics                     | 3         | 0.23%   |
| OYT Tech                               | 3         | 0.23%   |
| KYE Systems (Mouse Systems)            | 3         | 0.23%   |
| Hewlett-Packard                        | 3         | 0.23%   |
| Genesys Logic                          | 3         | 0.23%   |
| DigiTech                               | 3         | 0.23%   |
| webcam                                 | 2         | 0.15%   |
| OmniVision Technologies                | 2         | 0.15%   |
| MacroSilicon                           | 2         | 0.15%   |
| kingcome                               | 2         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 92        | 6.93%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 31        | 2.34%   |
| icSpring camera                                                            | 31        | 2.34%   |
| Bison Integrated Camera                                                    | 28        | 2.11%   |
| Microdia Integrated_Webcam_HD                                              | 26        | 1.96%   |
| Syntek Integrated Camera                                                   | 23        | 1.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 23        | 1.73%   |
| Chicony HD WebCam                                                          | 23        | 1.73%   |
| Realtek Integrated_Webcam_HD                                               | 20        | 1.51%   |
| IMC Networks Integrated Camera                                             | 19        | 1.43%   |
| Logitech Webcam C270                                                       | 16        | 1.21%   |
| Sunplus Integrated_Webcam_HD                                               | 15        | 1.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 14        | 1.06%   |
| Chicony HP TrueVision HD Camera                                            | 14        | 1.06%   |
| Bison Lenovo EasyCamera                                                    | 13        | 0.98%   |
| Apple FaceTime HD Camera (Built-in)                                        | 13        | 0.98%   |
| Quanta HD User Facing                                                      | 12        | 0.9%    |
| Microdia Integrated Webcam                                                 | 11        | 0.83%   |
| Chicony HP Webcam                                                          | 11        | 0.83%   |
| Alcor Micro USB 2.0 Camera                                                 | 11        | 0.83%   |
| Quanta VGA WebCam                                                          | 10        | 0.75%   |
| Bison Lenovo Integrated Webcam                                             | 10        | 0.75%   |
| Microdia USB 2.0 Camera                                                    | 9         | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                                               | 9         | 0.68%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 9         | 0.68%   |
| Chicony HP HD Webcam                                                       | 9         | 0.68%   |
| Chicony FJ Camera                                                          | 9         | 0.68%   |
| Bison HD Webcam                                                            | 9         | 0.68%   |
| Bison EasyCamera                                                           | 9         | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 8         | 0.6%    |
| Lite-On Integrated Camera                                                  | 8         | 0.6%    |
| Lenovo Integrated Webcam                                                   | 8         | 0.6%    |
| IMC Networks Integrated Webcam                                             | 8         | 0.6%    |
| Chicony HP HD Camera                                                       | 8         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 8         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 8         | 0.6%    |
| Bison BisonCam, NB Pro                                                     | 8         | 0.6%    |
| ALi Gateway Webcam                                                         | 8         | 0.6%    |
| Acer Integrated Camera                                                     | 8         | 0.6%    |
| Microdia Webcam Vitade AF                                                  | 7         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 76        | 42.7%   |
| Synaptics                          | 28        | 15.73%  |
| Upek                               | 24        | 13.48%  |
| AuthenTec                          | 16        | 8.99%   |
| Shenzhen Goodix Technology         | 11        | 6.18%   |
| Elan Microelectronics              | 9         | 5.06%   |
| LighTuning Technology              | 8         | 4.49%   |
| Focal-systems.Corp                 | 3         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.12%   |
| STMicroelectronics                 | 1         | 0.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 12.36%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 10.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.06%   |
| AuthenTec AES2810                                                          | 9         | 5.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.49%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 4.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 3.93%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 3.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 3.37%   |
| Validity Sensors VFS491                                                    | 6         | 3.37%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.37%   |
| Synaptics WBDI                                                             | 5         | 2.81%   |
| Synaptics  WBDI                                                            | 5         | 2.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.81%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 2.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.25%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.25%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.69%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.69%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.69%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.12%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.12%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 1.12%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.12%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.12%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.56%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.56%   |
| Synaptics UWP WBDI                                                         | 1         | 0.56%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.56%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 51        | 55.43%  |
| Alcor Micro           | 15        | 16.3%   |
| O2 Micro              | 8         | 8.7%    |
| Upek                  | 5         | 5.43%   |
| Lenovo                | 4         | 4.35%   |
| SCM Microsystems      | 2         | 2.17%   |
| Gemalto (was Gemplus) | 2         | 2.17%   |
| Cherry                | 2         | 2.17%   |
| OmniKey               | 1         | 1.09%   |
| Chicony Electronics   | 1         | 1.09%   |
| Advanced Card Systems | 1         | 1.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 32.61%  |
| Broadcom 5880                                                                | 16        | 17.39%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 15.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 7.61%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.43%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.26%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 2.17%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 2.17%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.09%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 1.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.09%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.09%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.09%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.09%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2101      | 81.53%  |
| 1     | 398       | 15.44%  |
| 2     | 71        | 2.76%   |
| 3     | 7         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 178       | 32.6%   |
| Graphics card            | 163       | 29.85%  |
| Chipcard                 | 88        | 16.12%  |
| Net/wireless             | 31        | 5.68%   |
| Multimedia controller    | 26        | 4.76%   |
| Storage                  | 15        | 2.75%   |
| Unassigned class         | 14        | 2.56%   |
| Communication controller | 13        | 2.38%   |
| Bluetooth                | 7         | 1.28%   |
| Storage/raid             | 3         | 0.55%   |
| Card reader              | 3         | 0.55%   |
| Network                  | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |
| Flash memory             | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |
| Camera                   | 1         | 0.18%   |


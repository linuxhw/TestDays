Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 830

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a889f37319](https://linux-hardware.org/?probe=a889f37319) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Vostro 5470                 | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a3397b67bd](https://linux-hardware.org/?probe=a3397b67bd) | Feb 05, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5e934e6551](https://linux-hardware.org/?probe=5e934e6551) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Acer          | Aspire 4720Z                | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [e31b235787](https://linux-hardware.org/?probe=e31b235787) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| ASUSTek       | X455LD                      | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| Acer          | Swift SF514-53T             | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | G40-45 80E1                 | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Dell          | Latitude E6440              | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| ASUSTek       | K43SV                       | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| HP            | Pavilion 14                 | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [82560e5d03](https://linux-hardware.org/?probe=82560e5d03) | Oct 04, 2021 |
| HP            | Laptop 14-bw0xx             | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| Acer          | Aspire 4750                 | [bf7fef3aa9](https://linux-hardware.org/?probe=bf7fef3aa9) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Swift SFX14-41G             | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [5a43bd347f](https://linux-hardware.org/?probe=5a43bd347f) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| ASUSTek       | GL553VD                     | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [49f141b749](https://linux-hardware.org/?probe=49f141b749) | Aug 26, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| Acer          | Swift SF314-41              | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| ASUSTek       | X441SA                      | [157096a598](https://linux-hardware.org/?probe=157096a598) | Aug 14, 2021 |
| Toshiba       | Satellite R630              | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| HP            | ENVY Notebook               | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| ASUSTek       | X441SA                      | [7b26cd5c2b](https://linux-hardware.org/?probe=7b26cd5c2b) | Aug 08, 2021 |
| Lenovo        | G40-45 80E1                 | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [cc7e14cb7d](https://linux-hardware.org/?probe=cc7e14cb7d) | Aug 06, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Dell          | Inspiron 3458               | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GE_FX80G... | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Aspire V5-431               | [9341c3a517](https://linux-hardware.org/?probe=9341c3a517) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | K84L                        | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Acer          | Aspire E5-475G              | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| HP            | EliteBook Folio 9470m       | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| ASUSTek       | X550JX                      | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Acer          | Okinawa                     | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [d10568a71e](https://linux-hardware.org/?probe=d10568a71e) | May 17, 2021 |
| Acer          | Aspire 4752                 | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [c0380fe4fa](https://linux-hardware.org/?probe=c0380fe4fa) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| Acer          | Aspire 4750                 | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| Acer          | Aspire A514-53              | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Acer          | Swift SF314-41              | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| Acer          | Aspire 4739                 | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [806d57e31a](https://linux-hardware.org/?probe=806d57e31a) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Lenovo        | V310-14ISK 80SX             | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [23dee03df5](https://linux-hardware.org/?probe=23dee03df5) | Mar 14, 2021 |
| Dell          | Vostro 3481                 | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ceb4b7fdab](https://linux-hardware.org/?probe=ceb4b7fdab) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [04c46743cb](https://linux-hardware.org/?probe=04c46743cb) | Mar 05, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| ASUSTek       | UX303UB                     | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Acer          | Aspire 4752                 | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| Acer          | Swift SF514-52T             | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| HP            | ZBook 15 G2                 | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [875b3b45f2](https://linux-hardware.org/?probe=875b3b45f2) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| HP            | ZBook 15 G2                 | [bc918bf558](https://linux-hardware.org/?probe=bc918bf558) | Jan 03, 2021 |
| ASUSTek       | X455LAB                     | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| HP            | 1000                        | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| ASUSTek       | X455LAB                     | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |
| HP            | EliteBook Folio 9470m       | [5bd5d77342](https://linux-hardware.org/?probe=5bd5d77342) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| Acer          | Aspire 4738Z                | [26c4af7060](https://linux-hardware.org/?probe=26c4af7060) | Dec 22, 2020 |
| Acer          | Aspire 4738Z                | [b9708063b2](https://linux-hardware.org/?probe=b9708063b2) | Dec 21, 2020 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [be0654391c](https://linux-hardware.org/?probe=be0654391c) | Dec 21, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [9b9208c30b](https://linux-hardware.org/?probe=9b9208c30b) | Dec 18, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [23766674a9](https://linux-hardware.org/?probe=23766674a9) | Dec 18, 2020 |
| Acer          | Aspire 4738Z                | [418e7c3efb](https://linux-hardware.org/?probe=418e7c3efb) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | [86bca93d29](https://linux-hardware.org/?probe=86bca93d29) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | [300d21973e](https://linux-hardware.org/?probe=300d21973e) | Dec 16, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| ASUSTek       | 1015BX                      | [5cb5d5f2a8](https://linux-hardware.org/?probe=5cb5d5f2a8) | Dec 15, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [406d93673b](https://linux-hardware.org/?probe=406d93673b) | Dec 13, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [785196a6d7](https://linux-hardware.org/?probe=785196a6d7) | Dec 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [5f56870146](https://linux-hardware.org/?probe=5f56870146) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| ASUSTek       | X456URK                     | [be6b2ec83a](https://linux-hardware.org/?probe=be6b2ec83a) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [b664b71a15](https://linux-hardware.org/?probe=b664b71a15) | Nov 28, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Acer          | NXHATSN00190808A906600      | [402e6fe81a](https://linux-hardware.org/?probe=402e6fe81a) | Nov 26, 2020 |
| Toshiba       | Satellite L40               | [ffafc05e1f](https://linux-hardware.org/?probe=ffafc05e1f) | Nov 25, 2020 |
| HP            | 14                          | [1a02430025](https://linux-hardware.org/?probe=1a02430025) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [b17dd2d085](https://linux-hardware.org/?probe=b17dd2d085) | Nov 21, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| HP            | 14                          | [548056d4e9](https://linux-hardware.org/?probe=548056d4e9) | Nov 18, 2020 |
| HP            | 14                          | [a08766aff4](https://linux-hardware.org/?probe=a08766aff4) | Nov 18, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [82dbd47dff](https://linux-hardware.org/?probe=82dbd47dff) | Nov 15, 2020 |
| Dell          | XPS 13 7390                 | [8844beb362](https://linux-hardware.org/?probe=8844beb362) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| Acer          | Aspire E5-421               | [625727a34f](https://linux-hardware.org/?probe=625727a34f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [0b2411ab89](https://linux-hardware.org/?probe=0b2411ab89) | Nov 12, 2020 |
| Lenovo        | G400 20235                  | [e8b5212a0b](https://linux-hardware.org/?probe=e8b5212a0b) | Nov 11, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [923558f59a](https://linux-hardware.org/?probe=923558f59a) | Nov 08, 2020 |
| ASUSTek       | X453SA                      | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| ASUSTek       | X442UQR                     | [98225dbf74](https://linux-hardware.org/?probe=98225dbf74) | Nov 03, 2020 |
| Unknown       | Unknown                     | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | G40-30 80FY                 | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [64b38989db](https://linux-hardware.org/?probe=64b38989db) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [45b0065d49](https://linux-hardware.org/?probe=45b0065d49) | Oct 28, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Clevo         | M7x0S                       | [8559d7b074](https://linux-hardware.org/?probe=8559d7b074) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Lenovo        | V330-14IKB 81B0             | [0a1f42ff5e](https://linux-hardware.org/?probe=0a1f42ff5e) | Oct 18, 2020 |
| Lenovo        | V330-14IKB 81B0             | [327a983226](https://linux-hardware.org/?probe=327a983226) | Oct 18, 2020 |
| Acer          | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [646054c190](https://linux-hardware.org/?probe=646054c190) | Oct 08, 2020 |
| ASUSTek       | X442URR                     | [5e9f9ee314](https://linux-hardware.org/?probe=5e9f9ee314) | Oct 06, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Z480                | [36a5cbc73c](https://linux-hardware.org/?probe=36a5cbc73c) | Oct 03, 2020 |
| Lenovo        | IdeaPad Z480                | [f7282459cf](https://linux-hardware.org/?probe=f7282459cf) | Oct 03, 2020 |
| Acer          | NXHATSN00190808A906600      | [ece82b096b](https://linux-hardware.org/?probe=ece82b096b) | Oct 01, 2020 |
| HP            | Pavilion x2 Detachable      | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| ASUSTek       | X450EA                      | [2646942e92](https://linux-hardware.org/?probe=2646942e92) | Sep 30, 2020 |
| HP            | 430                         | [9eef183864](https://linux-hardware.org/?probe=9eef183864) | Sep 27, 2020 |
| Toshiba       | Satellite L730              | [28ff46aa6b](https://linux-hardware.org/?probe=28ff46aa6b) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [24b078a7f0](https://linux-hardware.org/?probe=24b078a7f0) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | X455YA                      | [0959901fca](https://linux-hardware.org/?probe=0959901fca) | Sep 23, 2020 |
| HP            | ENVY Laptop 13-aq1xxx       | [ed83ee1e30](https://linux-hardware.org/?probe=ed83ee1e30) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | [4a9dbc9937](https://linux-hardware.org/?probe=4a9dbc9937) | Sep 19, 2020 |
| Acer          | Aspire ES1-111M             | [0e2694227b](https://linux-hardware.org/?probe=0e2694227b) | Sep 19, 2020 |
| Acer          | Aspire 4738Z                | [505e48fb8c](https://linux-hardware.org/?probe=505e48fb8c) | Sep 19, 2020 |
| Apple         | MacBookPro12,1              | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| HP            | Laptop 15-bw0xx             | [ca58f62a6f](https://linux-hardware.org/?probe=ca58f62a6f) | Sep 15, 2020 |
| HP            | 430                         | [bfb152e615](https://linux-hardware.org/?probe=bfb152e615) | Sep 10, 2020 |
| ASUSTek       | GL503VD                     | [820f4da953](https://linux-hardware.org/?probe=820f4da953) | Sep 09, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d545f007f9](https://linux-hardware.org/?probe=d545f007f9) | Sep 05, 2020 |
| Acer          | Nitro AN515-43              | [7e0202ac18](https://linux-hardware.org/?probe=7e0202ac18) | Sep 04, 2020 |
| Acer          | Nitro AN515-43              | [152a400df9](https://linux-hardware.org/?probe=152a400df9) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| HP            | Pavilion Gaming Notebook    | [5bcdd6aa5a](https://linux-hardware.org/?probe=5bcdd6aa5a) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| Lenovo        | G405 20239                  | [518d27feca](https://linux-hardware.org/?probe=518d27feca) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2325WLB       | [e558c503f8](https://linux-hardware.org/?probe=e558c503f8) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2324AS7       | [676f1b8dce](https://linux-hardware.org/?probe=676f1b8dce) | Sep 03, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [24bdd07050](https://linux-hardware.org/?probe=24bdd07050) | Sep 02, 2020 |
| HP            | Pavilion dm1                | [1723b44134](https://linux-hardware.org/?probe=1723b44134) | Sep 02, 2020 |
| HP            | Pavilion Gaming Notebook    | [0c63fa76a6](https://linux-hardware.org/?probe=0c63fa76a6) | Sep 01, 2020 |
| HP            | EliteBook 2570p             | [a70aa343a9](https://linux-hardware.org/?probe=a70aa343a9) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [687538cadf](https://linux-hardware.org/?probe=687538cadf) | Aug 24, 2020 |
| Lenovo        | G400 20235                  | [f209fc4fd1](https://linux-hardware.org/?probe=f209fc4fd1) | Aug 22, 2020 |
| ASUSTek       | X550IK                      | [70aa141880](https://linux-hardware.org/?probe=70aa141880) | Aug 21, 2020 |
| Dell          | Inspiron 3180               | [cd7328883c](https://linux-hardware.org/?probe=cd7328883c) | Aug 18, 2020 |
| Fujitsu       | LIFEBOOK E734               | [977a611718](https://linux-hardware.org/?probe=977a611718) | Aug 16, 2020 |
| Dell          | Latitude E6400              | [177b63fda5](https://linux-hardware.org/?probe=177b63fda5) | Aug 15, 2020 |
| HP            | ProBook 440 G7              | [5291acaadc](https://linux-hardware.org/?probe=5291acaadc) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| Dell          | Latitude E6230              | [da6d9fdf1d](https://linux-hardware.org/?probe=da6d9fdf1d) | Aug 14, 2020 |
| HP            | Notebook                    | [8e7a53706c](https://linux-hardware.org/?probe=8e7a53706c) | Aug 13, 2020 |
| HP            | ProBook 440 G4              | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| Fujitsu       | LIFEBOOK E734               | [411fe99fda](https://linux-hardware.org/?probe=411fe99fda) | Aug 10, 2020 |
| Fujitsu       | LIFEBOOK E734               | [74050bb5dd](https://linux-hardware.org/?probe=74050bb5dd) | Aug 10, 2020 |
| HP            | Pavilion g4                 | [0ea8276f60](https://linux-hardware.org/?probe=0ea8276f60) | Aug 07, 2020 |
| HP            | Pavilion g4                 | [227e2e8de7](https://linux-hardware.org/?probe=227e2e8de7) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [8a63857dec](https://linux-hardware.org/?probe=8a63857dec) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [99bb1cd9d9](https://linux-hardware.org/?probe=99bb1cd9d9) | Aug 06, 2020 |
| Dell          | Latitude E6400              | [e8eb12590e](https://linux-hardware.org/?probe=e8eb12590e) | Aug 05, 2020 |
| Dell          | Latitude E6400              | [a1d10698bc](https://linux-hardware.org/?probe=a1d10698bc) | Aug 05, 2020 |
| Toshiba       | Satellite L745              | [4770498bee](https://linux-hardware.org/?probe=4770498bee) | Aug 02, 2020 |
| Toshiba       | Satellite L745              | [8f86800c3c](https://linux-hardware.org/?probe=8f86800c3c) | Aug 02, 2020 |
| ASUSTek       | N46VM                       | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [81ca2030be](https://linux-hardware.org/?probe=81ca2030be) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [47067cf62f](https://linux-hardware.org/?probe=47067cf62f) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [5cc61ff85e](https://linux-hardware.org/?probe=5cc61ff85e) | Jul 29, 2020 |
| ASUSTek       | N46VM                       | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| ASUSTek       | N43SN                       | [8652a9c307](https://linux-hardware.org/?probe=8652a9c307) | Jul 24, 2020 |
| ASUSTek       | N43SN                       | [6417be2a1c](https://linux-hardware.org/?probe=6417be2a1c) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [2c5b59d1df](https://linux-hardware.org/?probe=2c5b59d1df) | Jul 22, 2020 |
| ASUSTek       | X451CAP                     | [b4a3b63689](https://linux-hardware.org/?probe=b4a3b63689) | Jul 21, 2020 |
| ASUSTek       | X451CAP                     | [948bec3418](https://linux-hardware.org/?probe=948bec3418) | Jul 21, 2020 |
| HP            | Laptop 14-bs0xx             | [be0c3117b4](https://linux-hardware.org/?probe=be0c3117b4) | Jul 20, 2020 |
| ASUSTek       | X451CAP                     | [0e79d96e64](https://linux-hardware.org/?probe=0e79d96e64) | Jul 20, 2020 |
| ASUSTek       | X451CAP                     | [9043a7e401](https://linux-hardware.org/?probe=9043a7e401) | Jul 20, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | [2db5fa6bb3](https://linux-hardware.org/?probe=2db5fa6bb3) | Jul 19, 2020 |
| HP            | Pavilion g4                 | [cfa0470ff1](https://linux-hardware.org/?probe=cfa0470ff1) | Jul 18, 2020 |
| HP            | Pavilion g4                 | [582ab446a1](https://linux-hardware.org/?probe=582ab446a1) | Jul 17, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [50272ea6ea](https://linux-hardware.org/?probe=50272ea6ea) | Jul 16, 2020 |
| HP            | Pavilion g4                 | [49aa05e652](https://linux-hardware.org/?probe=49aa05e652) | Jul 15, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [a8dfb4b56d](https://linux-hardware.org/?probe=a8dfb4b56d) | Jul 15, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2b9f97d49e](https://linux-hardware.org/?probe=2b9f97d49e) | Jul 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [acf40c367c](https://linux-hardware.org/?probe=acf40c367c) | Jul 14, 2020 |
| HP            | 14                          | [c49bc9fa04](https://linux-hardware.org/?probe=c49bc9fa04) | Jul 13, 2020 |
| HP            | 14                          | [16f518d4d1](https://linux-hardware.org/?probe=16f518d4d1) | Jul 12, 2020 |
| ASUSTek       | X550ZE                      | [95e148ab0b](https://linux-hardware.org/?probe=95e148ab0b) | Jul 11, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ce870d391e](https://linux-hardware.org/?probe=ce870d391e) | Jul 09, 2020 |
| Acer          | Aspire E1-451G              | [4765a08df1](https://linux-hardware.org/?probe=4765a08df1) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Lenovo        | IdeaPad S210 20256          | [31723f3abc](https://linux-hardware.org/?probe=31723f3abc) | Jul 04, 2020 |
| ASUSTek       | X555BP                      | [e34500bb1c](https://linux-hardware.org/?probe=e34500bb1c) | Jul 03, 2020 |
| Acer          | Aspire F5-571T              | [61e70ca838](https://linux-hardware.org/?probe=61e70ca838) | Jun 29, 2020 |
| Acer          | Aspire F5-571T              | [6ab96eef7f](https://linux-hardware.org/?probe=6ab96eef7f) | Jun 29, 2020 |
| Acer          | Aspire F5-571T              | [bfc16ddd86](https://linux-hardware.org/?probe=bfc16ddd86) | Jun 28, 2020 |
| Lenovo        | ThinkPad X131e 33684SU      | [1ed3f7e63d](https://linux-hardware.org/?probe=1ed3f7e63d) | Jun 28, 2020 |
| ASUSTek       | UX331UN                     | [3bf2e1fb3c](https://linux-hardware.org/?probe=3bf2e1fb3c) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [20fe5eb234](https://linux-hardware.org/?probe=20fe5eb234) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [34c449d22e](https://linux-hardware.org/?probe=34c449d22e) | Jun 26, 2020 |
| HP            | 14                          | [4de0326f3b](https://linux-hardware.org/?probe=4de0326f3b) | Jun 24, 2020 |
| Acer          | Swift SF314-54G             | [e69e144ab8](https://linux-hardware.org/?probe=e69e144ab8) | Jun 21, 2020 |
| Lenovo        | G400 20235                  | [b3d56039ce](https://linux-hardware.org/?probe=b3d56039ce) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f186fc19d1](https://linux-hardware.org/?probe=f186fc19d1) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f4a05ff8fe](https://linux-hardware.org/?probe=f4a05ff8fe) | Jun 19, 2020 |
| Dell          | Latitude E6420              | [d065b3f6cd](https://linux-hardware.org/?probe=d065b3f6cd) | Jun 19, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [6af138a9a7](https://linux-hardware.org/?probe=6af138a9a7) | Jun 18, 2020 |
| Dell          | Inspiron N4110              | [4d8d8ad86f](https://linux-hardware.org/?probe=4d8d8ad86f) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Dell          | Latitude E6420              | [d7a5e67910](https://linux-hardware.org/?probe=d7a5e67910) | Jun 16, 2020 |
| Acer          | Aspire 4752                 | [c1bf847a06](https://linux-hardware.org/?probe=c1bf847a06) | Jun 15, 2020 |
| Dell          | Latitude E6420              | [b4e34247b1](https://linux-hardware.org/?probe=b4e34247b1) | Jun 14, 2020 |
| Dell          | Latitude E6420              | [90047024c8](https://linux-hardware.org/?probe=90047024c8) | Jun 12, 2020 |
| Dell          | Latitude E6420              | [9f81490571](https://linux-hardware.org/?probe=9f81490571) | Jun 12, 2020 |
| ASUSTek       | K46CM                       | [f50bd98e01](https://linux-hardware.org/?probe=f50bd98e01) | Jun 06, 2020 |
| Toshiba       | NB510                       | [034e807bf8](https://linux-hardware.org/?probe=034e807bf8) | Jun 05, 2020 |
| HP            | Pavilion g4                 | [a6a626b9ca](https://linux-hardware.org/?probe=a6a626b9ca) | Jun 04, 2020 |
| Acer          | Aspire 5050                 | [0c4de1a1a1](https://linux-hardware.org/?probe=0c4de1a1a1) | Jun 01, 2020 |
| Acer          | Aspire 5050                 | [ec8759bd69](https://linux-hardware.org/?probe=ec8759bd69) | Jun 01, 2020 |
| Acer          | Aspire A315-41              | [e91778b012](https://linux-hardware.org/?probe=e91778b012) | May 31, 2020 |
| ASUSTek       | K46CM                       | [b2b5f9db8d](https://linux-hardware.org/?probe=b2b5f9db8d) | May 31, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [dcc2d3e59f](https://linux-hardware.org/?probe=dcc2d3e59f) | May 31, 2020 |
| Lenovo        | G40-45 80E1                 | [4002bc5fb1](https://linux-hardware.org/?probe=4002bc5fb1) | May 30, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [b45d1eb089](https://linux-hardware.org/?probe=b45d1eb089) | May 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [00f65112c3](https://linux-hardware.org/?probe=00f65112c3) | May 28, 2020 |
| ASUSTek       | X200CA                      | [838a34d93c](https://linux-hardware.org/?probe=838a34d93c) | May 22, 2020 |
| MSI           | MS-1481                     | [e32bed7fb1](https://linux-hardware.org/?probe=e32bed7fb1) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [412ba3814d](https://linux-hardware.org/?probe=412ba3814d) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [ba05f4ff6a](https://linux-hardware.org/?probe=ba05f4ff6a) | May 15, 2020 |
| HP            | Pavilion 14                 | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo        | G400s 20244                 | [c53de49fbc](https://linux-hardware.org/?probe=c53de49fbc) | May 10, 2020 |
| Lenovo        | ThinkPad T430 2349FC3       | [00f6deaf61](https://linux-hardware.org/?probe=00f6deaf61) | May 09, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [3dee72a67f](https://linux-hardware.org/?probe=3dee72a67f) | May 08, 2020 |
| Apple         | MacBookPro12,1              | [b0c6f48549](https://linux-hardware.org/?probe=b0c6f48549) | May 08, 2020 |
| ASUSTek       | N46VM                       | [dac0d32083](https://linux-hardware.org/?probe=dac0d32083) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [d1670dbbdd](https://linux-hardware.org/?probe=d1670dbbdd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [dbb1d688e9](https://linux-hardware.org/?probe=dbb1d688e9) | Apr 28, 2020 |
| Dell          | Vostro 14-3468              | [66350e55ef](https://linux-hardware.org/?probe=66350e55ef) | Apr 28, 2020 |
| Toshiba       | Satellite L510              | [a27037c0e1](https://linux-hardware.org/?probe=a27037c0e1) | Apr 26, 2020 |
| Lenovo        | ThinkPad T410 2522CTO       | [0342587f2b](https://linux-hardware.org/?probe=0342587f2b) | Apr 26, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [09b7ff4a7f](https://linux-hardware.org/?probe=09b7ff4a7f) | Apr 25, 2020 |
| HP            | EliteBook 840 G1            | [8d9870131a](https://linux-hardware.org/?probe=8d9870131a) | Apr 24, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [2aa0175c4b](https://linux-hardware.org/?probe=2aa0175c4b) | Apr 22, 2020 |
| ASUSTek       | X450CC                      | [8395776e77](https://linux-hardware.org/?probe=8395776e77) | Apr 21, 2020 |
| Acer          | Swift SF314-56G             | [f2608b9796](https://linux-hardware.org/?probe=f2608b9796) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | X442UR                      | [b96b676ec0](https://linux-hardware.org/?probe=b96b676ec0) | Apr 16, 2020 |
| Apple         | MacBook4,1                  | [17f5daf01e](https://linux-hardware.org/?probe=17f5daf01e) | Apr 16, 2020 |
| HP            | EliteBook 2560p             | [61ff7566f0](https://linux-hardware.org/?probe=61ff7566f0) | Apr 13, 2020 |
| HP            | EliteBook 2560p             | [e830e91c74](https://linux-hardware.org/?probe=e830e91c74) | Apr 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| HP            | 540                         | [6fa99c27dd](https://linux-hardware.org/?probe=6fa99c27dd) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Toshiba       | Satellite L510              | [659bf517f1](https://linux-hardware.org/?probe=659bf517f1) | Apr 08, 2020 |
| HP            | EliteBook 2560p             | [9e472a05c5](https://linux-hardware.org/?probe=9e472a05c5) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [faa78e08dd](https://linux-hardware.org/?probe=faa78e08dd) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [e03334549f](https://linux-hardware.org/?probe=e03334549f) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [488c8306ff](https://linux-hardware.org/?probe=488c8306ff) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [98fdaa9d0e](https://linux-hardware.org/?probe=98fdaa9d0e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| Toshiba       | Satellite Pro C640          | [322a06db55](https://linux-hardware.org/?probe=322a06db55) | Mar 29, 2020 |
| AXIOO         | Mybook Lite                 | [0ec3e1d33f](https://linux-hardware.org/?probe=0ec3e1d33f) | Mar 28, 2020 |
| AXIOO         | Mybook Lite                 | [539bf6ca99](https://linux-hardware.org/?probe=539bf6ca99) | Mar 28, 2020 |
| ASUSTek       | X450CA                      | [0c5e774258](https://linux-hardware.org/?probe=0c5e774258) | Mar 27, 2020 |
| Chuwi         | LapBook SE                  | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| Dell          | Latitude E5450              | [8a4a9dcec1](https://linux-hardware.org/?probe=8a4a9dcec1) | Mar 24, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [f08c6424b7](https://linux-hardware.org/?probe=f08c6424b7) | Mar 22, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [9fe1bc84d4](https://linux-hardware.org/?probe=9fe1bc84d4) | Mar 22, 2020 |
| Acer          | Aspire 4738Z                | [b3d6891b2b](https://linux-hardware.org/?probe=b3d6891b2b) | Mar 20, 2020 |
| Dell          | Inspiron 5490               | [79cbbe0dff](https://linux-hardware.org/?probe=79cbbe0dff) | Mar 20, 2020 |
| Acer          | Aspire 4738Z                | [7d9e5d58c6](https://linux-hardware.org/?probe=7d9e5d58c6) | Mar 19, 2020 |
| Acer          | Aspire 4738Z                | [c607c036b4](https://linux-hardware.org/?probe=c607c036b4) | Mar 19, 2020 |
| Acer          | Aspire 4738Z                | [e34aa3ebf4](https://linux-hardware.org/?probe=e34aa3ebf4) | Mar 14, 2020 |
| Acer          | Aspire 4738Z                | [14ebaa4c99](https://linux-hardware.org/?probe=14ebaa4c99) | Mar 14, 2020 |
| Acer          | Aspire 4738Z                | [95d760c06e](https://linux-hardware.org/?probe=95d760c06e) | Mar 13, 2020 |
| Acer          | Aspire 4738Z                | [c898bc3309](https://linux-hardware.org/?probe=c898bc3309) | Mar 13, 2020 |
| Acer          | Aspire 4738Z                | [aaf1e32b99](https://linux-hardware.org/?probe=aaf1e32b99) | Mar 13, 2020 |
| Acer          | Aspire 4738Z                | [14e20c3231](https://linux-hardware.org/?probe=14e20c3231) | Mar 13, 2020 |
| Acer          | Aspire 4738Z                | [4895887d9e](https://linux-hardware.org/?probe=4895887d9e) | Mar 13, 2020 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [023e57edf3](https://linux-hardware.org/?probe=023e57edf3) | Mar 11, 2020 |
| Acer          | Swift SF314-56G             | [c62b3c237f](https://linux-hardware.org/?probe=c62b3c237f) | Mar 10, 2020 |
| Dell          | Inspiron 3493               | [23e7a2104b](https://linux-hardware.org/?probe=23e7a2104b) | Mar 09, 2020 |
| ASUSTek       | K43SV                       | [a036dac000](https://linux-hardware.org/?probe=a036dac000) | Mar 06, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [b94b74f6d4](https://linux-hardware.org/?probe=b94b74f6d4) | Mar 05, 2020 |
| Dell          | Latitude 7490               | [d03108116d](https://linux-hardware.org/?probe=d03108116d) | Mar 02, 2020 |
| Dell          | Latitude 7490               | [7600f02bbe](https://linux-hardware.org/?probe=7600f02bbe) | Mar 02, 2020 |
| MSI           | PS42 Modern 8RA             | [ab8a74e1ac](https://linux-hardware.org/?probe=ab8a74e1ac) | Mar 01, 2020 |
| Dell          | Inspiron 5490               | [1d589a5695](https://linux-hardware.org/?probe=1d589a5695) | Feb 24, 2020 |
| MSI           | CX420/CX420 MX              | [f1112049d2](https://linux-hardware.org/?probe=f1112049d2) | Feb 23, 2020 |
| Sony          | SVE11125CVW                 | [bee034816a](https://linux-hardware.org/?probe=bee034816a) | Feb 21, 2020 |
| HP            | EliteBook 2530p             | [55fb907088](https://linux-hardware.org/?probe=55fb907088) | Feb 17, 2020 |
| Dell          | Latitude 7490               | [39de737132](https://linux-hardware.org/?probe=39de737132) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b41b751782](https://linux-hardware.org/?probe=b41b751782) | Feb 14, 2020 |
| AXIOO         | NEON MNW                    | [ad58a21877](https://linux-hardware.org/?probe=ad58a21877) | Feb 11, 2020 |
| HP            | EliteBook 2530p             | [0ffc694ed0](https://linux-hardware.org/?probe=0ffc694ed0) | Feb 08, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [eaf4701374](https://linux-hardware.org/?probe=eaf4701374) | Feb 08, 2020 |
| HP            | 15                          | [e0d98d2e3d](https://linux-hardware.org/?probe=e0d98d2e3d) | Feb 05, 2020 |
| Lenovo        | ThinkPad T430s 2356GC9      | [08223129d8](https://linux-hardware.org/?probe=08223129d8) | Feb 05, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [1ca0264090](https://linux-hardware.org/?probe=1ca0264090) | Feb 04, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [f1d169e079](https://linux-hardware.org/?probe=f1d169e079) | Feb 04, 2020 |
| ASUSTek       | GL503VD                     | [3937c14284](https://linux-hardware.org/?probe=3937c14284) | Feb 02, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [7b9cdcc838](https://linux-hardware.org/?probe=7b9cdcc838) | Jan 29, 2020 |
| HP            | Compaq 6910p                | [b790eb4d3d](https://linux-hardware.org/?probe=b790eb4d3d) | Jan 28, 2020 |
| HP            | Presario C500 (RU924PA#U... | [f22ab20bae](https://linux-hardware.org/?probe=f22ab20bae) | Jan 28, 2020 |
| Dell          | Inspiron 5570               | [997718dc61](https://linux-hardware.org/?probe=997718dc61) | Jan 28, 2020 |
| HP            | Presario C500 (RU924PA#U... | [9f7ac6a60c](https://linux-hardware.org/?probe=9f7ac6a60c) | Jan 28, 2020 |
| HP            | Presario C500 (RU924PA#U... | [efe0249933](https://linux-hardware.org/?probe=efe0249933) | Jan 28, 2020 |
| Lenovo        | G40-45 80E1                 | [eeeb376a99](https://linux-hardware.org/?probe=eeeb376a99) | Jan 26, 2020 |
| ASUSTek       | S451LB                      | [0f309bac4f](https://linux-hardware.org/?probe=0f309bac4f) | Jan 24, 2020 |
| Acer          | Aspire 4738Z                | [f6d23a2b44](https://linux-hardware.org/?probe=f6d23a2b44) | Jan 24, 2020 |
| Lenovo        | G50-80 80E5                 | [8beff1830f](https://linux-hardware.org/?probe=8beff1830f) | Jan 24, 2020 |
| Dell          | Inspiron 3580               | [7a1e23b953](https://linux-hardware.org/?probe=7a1e23b953) | Jan 22, 2020 |
| Dell          | Inspiron 3580               | [0f76a113c1](https://linux-hardware.org/?probe=0f76a113c1) | Jan 22, 2020 |
| Acer          | TravelMate B115e            | [5dd85d88a5](https://linux-hardware.org/?probe=5dd85d88a5) | Jan 22, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7075d2c989](https://linux-hardware.org/?probe=7075d2c989) | Jan 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f1b9fa59ec](https://linux-hardware.org/?probe=f1b9fa59ec) | Jan 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f766995e7e](https://linux-hardware.org/?probe=f766995e7e) | Jan 16, 2020 |
| Toshiba       | Satellite L55-B             | [67b00cee9e](https://linux-hardware.org/?probe=67b00cee9e) | Jan 15, 2020 |
| Lenovo        | G40-80 80E4                 | [f4e0f183f5](https://linux-hardware.org/?probe=f4e0f183f5) | Jan 10, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [5ec506d808](https://linux-hardware.org/?probe=5ec506d808) | Jan 09, 2020 |
| Lenovo        | G40-80 80E4                 | [d20a535458](https://linux-hardware.org/?probe=d20a535458) | Jan 09, 2020 |
| Acer          | Aspire E5-553G              | [b2aad899be](https://linux-hardware.org/?probe=b2aad899be) | Jan 02, 2020 |
| Acer          | Aspire E5-553G              | [3cb532fd7e](https://linux-hardware.org/?probe=3cb532fd7e) | Dec 27, 2019 |
| Acer          | Aspire E5-553G              | [e694f1b28a](https://linux-hardware.org/?probe=e694f1b28a) | Dec 27, 2019 |
| HP            | Laptop 14-bw0xx             | [47b10cd4f1](https://linux-hardware.org/?probe=47b10cd4f1) | Dec 25, 2019 |
| Acer          | Aspire 4750                 | [94a0b4fab9](https://linux-hardware.org/?probe=94a0b4fab9) | Dec 10, 2019 |
| Lenovo        | G40-45 80E1                 | [a89268fd79](https://linux-hardware.org/?probe=a89268fd79) | Dec 10, 2019 |
| Sony          | SVE14A35CVS                 | [405f4def54](https://linux-hardware.org/?probe=405f4def54) | Dec 01, 2019 |
| Acer          | AO725                       | [0143e45ad7](https://linux-hardware.org/?probe=0143e45ad7) | Nov 19, 2019 |
| Acer          | Aspire E5-475G              | [177939d114](https://linux-hardware.org/?probe=177939d114) | Nov 18, 2019 |
| Acer          | Aspire E5-475G              | [44dd5d0924](https://linux-hardware.org/?probe=44dd5d0924) | Nov 18, 2019 |
| HP            | Laptop 14s-cf1xxx           | [4d0bbf965b](https://linux-hardware.org/?probe=4d0bbf965b) | Nov 07, 2019 |
| HP            | Pavilion 14                 | [80979c9b2c](https://linux-hardware.org/?probe=80979c9b2c) | Oct 27, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [961235a0ff](https://linux-hardware.org/?probe=961235a0ff) | Oct 26, 2019 |
| ASUSTek       | GL553VD                     | [65246f893a](https://linux-hardware.org/?probe=65246f893a) | Oct 24, 2019 |
| Sony          | VPCZ227GG                   | [6e74a95929](https://linux-hardware.org/?probe=6e74a95929) | Oct 23, 2019 |
| ASUSTek       | GL553VD                     | [a97dc59515](https://linux-hardware.org/?probe=a97dc59515) | Oct 22, 2019 |
| ASUSTek       | X450LCP                     | [0f412b6c32](https://linux-hardware.org/?probe=0f412b6c32) | Oct 19, 2019 |
| ASUSTek       | X200MA                      | [ed6cbea554](https://linux-hardware.org/?probe=ed6cbea554) | Oct 14, 2019 |
| ASUSTek       | X450JN                      | [b16321a8a5](https://linux-hardware.org/?probe=b16321a8a5) | Oct 09, 2019 |
| ASUSTek       | X450JN                      | [9745c5a328](https://linux-hardware.org/?probe=9745c5a328) | Oct 09, 2019 |
| ASUSTek       | X200MA                      | [219d395e20](https://linux-hardware.org/?probe=219d395e20) | Oct 08, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [d5d77d3c0d](https://linux-hardware.org/?probe=d5d77d3c0d) | Oct 07, 2019 |
| Acer          | Aspire 4740                 | [b10fe6845e](https://linux-hardware.org/?probe=b10fe6845e) | Oct 06, 2019 |
| Lenovo        | G40-45 80E1                 | [88db11e321](https://linux-hardware.org/?probe=88db11e321) | Oct 06, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [156a080f13](https://linux-hardware.org/?probe=156a080f13) | Oct 05, 2019 |
| Acer          | Aspire 4750                 | [eb02531024](https://linux-hardware.org/?probe=eb02531024) | Sep 22, 2019 |
| HP            | G42                         | [5b701c891f](https://linux-hardware.org/?probe=5b701c891f) | Sep 18, 2019 |
| Acer          | Aspire 4750                 | [0315d96606](https://linux-hardware.org/?probe=0315d96606) | Sep 04, 2019 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [51c94c839c](https://linux-hardware.org/?probe=51c94c839c) | Aug 28, 2019 |
| ASUSTek       | GL552VXK                    | [facf474182](https://linux-hardware.org/?probe=facf474182) | Aug 28, 2019 |
| ASUSTek       | GL552VXK                    | [4f463b9a07](https://linux-hardware.org/?probe=4f463b9a07) | Aug 26, 2019 |
| Acer          | Aspire 4755                 | [90e4eaf7b2](https://linux-hardware.org/?probe=90e4eaf7b2) | Aug 24, 2019 |
| Acer          | Swift SF314-56G             | [5114f08197](https://linux-hardware.org/?probe=5114f08197) | Aug 24, 2019 |
| ASUSTek       | K43E                        | [8b6fca544b](https://linux-hardware.org/?probe=8b6fca544b) | Aug 24, 2019 |
| Clevo         | M7x0S                       | [6d5922e42c](https://linux-hardware.org/?probe=6d5922e42c) | Aug 23, 2019 |
| HP            | 14                          | [0ebab40d1e](https://linux-hardware.org/?probe=0ebab40d1e) | Aug 19, 2019 |
| Acer          | Swift SF314-56G             | [6410bd1b82](https://linux-hardware.org/?probe=6410bd1b82) | Aug 17, 2019 |
| Panasonic     | CF-Y8FWMCAS                 | [c3f2c78e79](https://linux-hardware.org/?probe=c3f2c78e79) | Aug 16, 2019 |
| Lenovo        | ThinkPad X120e 0611AM2      | [96c790e992](https://linux-hardware.org/?probe=96c790e992) | Aug 16, 2019 |
| Acer          | Aspire E1-410               | [b7d83d359d](https://linux-hardware.org/?probe=b7d83d359d) | Aug 16, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [e425b40f79](https://linux-hardware.org/?probe=e425b40f79) | Aug 09, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | [02c5d418e9](https://linux-hardware.org/?probe=02c5d418e9) | Aug 09, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [a4da95311b](https://linux-hardware.org/?probe=a4da95311b) | Aug 09, 2019 |
| HP            | Notebook                    | [2ec22fa87a](https://linux-hardware.org/?probe=2ec22fa87a) | Jul 25, 2019 |
| HP            | Notebook                    | [3225ed388d](https://linux-hardware.org/?probe=3225ed388d) | Jul 25, 2019 |
| Apple         | MacBook3,1                  | [b7ff730ca4](https://linux-hardware.org/?probe=b7ff730ca4) | Jul 20, 2019 |
| Apple         | MacBook3,1                  | [7c2cb6e38f](https://linux-hardware.org/?probe=7c2cb6e38f) | Jul 20, 2019 |
| Apple         | MacBook3,1                  | [72555b95bc](https://linux-hardware.org/?probe=72555b95bc) | Jul 20, 2019 |
| Acer          | Aspire E1-451G              | [994ae0cfbf](https://linux-hardware.org/?probe=994ae0cfbf) | Jul 19, 2019 |
| Acer          | Aspire E5-571G              | [6f1f1687b8](https://linux-hardware.org/?probe=6f1f1687b8) | Jul 12, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [fa7155b0e4](https://linux-hardware.org/?probe=fa7155b0e4) | Jul 11, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [27bb2f0366](https://linux-hardware.org/?probe=27bb2f0366) | Jul 07, 2019 |
| Acer          | Okinawa                     | [ce7e2b4d22](https://linux-hardware.org/?probe=ce7e2b4d22) | Jul 04, 2019 |
| Sony          | VPCZ227GG                   | [9109d4a264](https://linux-hardware.org/?probe=9109d4a264) | Jul 03, 2019 |
| HP            | Laptop 14-cm0xxx            | [908e49b930](https://linux-hardware.org/?probe=908e49b930) | Jun 27, 2019 |
| HP            | Laptop 14-cm0xxx            | [d2d977663d](https://linux-hardware.org/?probe=d2d977663d) | Jun 27, 2019 |
| Acer          | Aspire 4755                 | [b8fb16b9f4](https://linux-hardware.org/?probe=b8fb16b9f4) | Jun 26, 2019 |
| HP            | Laptop 14-cm0xxx            | [eca46a8357](https://linux-hardware.org/?probe=eca46a8357) | Jun 25, 2019 |
| HP            | Laptop 14-cm0xxx            | [8d739bcda2](https://linux-hardware.org/?probe=8d739bcda2) | Jun 25, 2019 |
| HP            | Laptop 14-cm0xxx            | [a5e8d15902](https://linux-hardware.org/?probe=a5e8d15902) | Jun 25, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | [578f1342d9](https://linux-hardware.org/?probe=578f1342d9) | Jun 17, 2019 |
| Acer          | TravelMate P243             | [47fda1ca09](https://linux-hardware.org/?probe=47fda1ca09) | Jun 15, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [703e5773b1](https://linux-hardware.org/?probe=703e5773b1) | Jun 15, 2019 |
| ASUSTek       | GL503VD                     | [b8be17d96b](https://linux-hardware.org/?probe=b8be17d96b) | Jun 04, 2019 |
| Acer          | AO756                       | [8f2835ae3b](https://linux-hardware.org/?probe=8f2835ae3b) | May 31, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [b20a13a602](https://linux-hardware.org/?probe=b20a13a602) | May 30, 2019 |
| HP            | Presario V3000 (RL377PA#... | [400439715d](https://linux-hardware.org/?probe=400439715d) | May 30, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7420b6037e](https://linux-hardware.org/?probe=7420b6037e) | May 15, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ede8d39081](https://linux-hardware.org/?probe=ede8d39081) | May 15, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [cf4c74151b](https://linux-hardware.org/?probe=cf4c74151b) | May 14, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [29a42058db](https://linux-hardware.org/?probe=29a42058db) | May 14, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6aad582567](https://linux-hardware.org/?probe=6aad582567) | May 14, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [47e88cfbd1](https://linux-hardware.org/?probe=47e88cfbd1) | May 14, 2019 |
| Acer          | AO532h                      | [26399c140a](https://linux-hardware.org/?probe=26399c140a) | May 13, 2019 |
| Acer          | Aspire 4755                 | [f2b6448161](https://linux-hardware.org/?probe=f2b6448161) | May 13, 2019 |
| Acer          | Aspire 4755                 | [a800461b6d](https://linux-hardware.org/?probe=a800461b6d) | May 13, 2019 |
| ASUSTek       | K42JZ                       | [b2218d3c9f](https://linux-hardware.org/?probe=b2218d3c9f) | May 11, 2019 |
| Toshiba       | PORTEGE M780                | [9f5e64a19a](https://linux-hardware.org/?probe=9f5e64a19a) | May 10, 2019 |
| Toshiba       | PORTEGE M780                | [27436c537b](https://linux-hardware.org/?probe=27436c537b) | May 10, 2019 |
| ASUSTek       | 1215B                       | [31e97aedc6](https://linux-hardware.org/?probe=31e97aedc6) | May 09, 2019 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4adfd3a1c3](https://linux-hardware.org/?probe=4adfd3a1c3) | May 02, 2019 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [90dd7d30ec](https://linux-hardware.org/?probe=90dd7d30ec) | May 02, 2019 |
| HP            | Laptop 14-bs0xx             | [f74ea44f1a](https://linux-hardware.org/?probe=f74ea44f1a) | Apr 21, 2019 |
| HP            | Laptop 14-bs0xx             | [73779c26b3](https://linux-hardware.org/?probe=73779c26b3) | Apr 14, 2019 |
| ASUSTek       | X540NA                      | [21f04e1abe](https://linux-hardware.org/?probe=21f04e1abe) | Apr 11, 2019 |
| HP            | Laptop 14s-cf0xxx           | [46a39369f4](https://linux-hardware.org/?probe=46a39369f4) | Apr 09, 2019 |
| ASUSTek       | X456URK                     | [5fa130cbb4](https://linux-hardware.org/?probe=5fa130cbb4) | Apr 01, 2019 |
| Acer          | Aspire E1-451G              | [3631187d23](https://linux-hardware.org/?probe=3631187d23) | Mar 31, 2019 |
| ASUSTek       | X455LA                      | [c019eb486b](https://linux-hardware.org/?probe=c019eb486b) | Mar 24, 2019 |
| HP            | 1000                        | [b813049f31](https://linux-hardware.org/?probe=b813049f31) | Mar 03, 2019 |
| Lenovo        | G400 20235                  | [cd3d7d1c40](https://linux-hardware.org/?probe=cd3d7d1c40) | Feb 23, 2019 |
| Lenovo        | G400 20235                  | [2ca2f87846](https://linux-hardware.org/?probe=2ca2f87846) | Feb 23, 2019 |
| HP            | Laptop 14-bs0xx             | [82b35c05bb](https://linux-hardware.org/?probe=82b35c05bb) | Feb 15, 2019 |
| HP            | Laptop 14-bs0xx             | [520eb1f482](https://linux-hardware.org/?probe=520eb1f482) | Jan 27, 2019 |
| ASUSTek       | K43TA                       | [811cc55c64](https://linux-hardware.org/?probe=811cc55c64) | Jan 06, 2019 |
| ASUSTek       | X455LAB                     | [6952701375](https://linux-hardware.org/?probe=6952701375) | Jan 05, 2019 |
| ASUSTek       | X441UV                      | [82144bfe29](https://linux-hardware.org/?probe=82144bfe29) | Dec 30, 2018 |
| ASUSTek       | X441UV                      | [32b213b99f](https://linux-hardware.org/?probe=32b213b99f) | Dec 29, 2018 |
| ASUSTek       | X441UV                      | [09791d4c52](https://linux-hardware.org/?probe=09791d4c52) | Dec 29, 2018 |
| ASUSTek       | X441UV                      | [93dd582dab](https://linux-hardware.org/?probe=93dd582dab) | Dec 29, 2018 |
| ASUSTek       | X550IU                      | [7e184779a7](https://linux-hardware.org/?probe=7e184779a7) | Dec 16, 2018 |
| Lenovo        | ThinkPad E420 11417NA       | [4b07a8c051](https://linux-hardware.org/?probe=4b07a8c051) | Oct 04, 2018 |
| Lenovo        | ThinkPad E420 11417NA       | [9d5fad95db](https://linux-hardware.org/?probe=9d5fad95db) | Aug 22, 2018 |
| ASUSTek       | S451LB                      | [ba8f3b9a74](https://linux-hardware.org/?probe=ba8f3b9a74) | May 17, 2018 |
| HP            | Notebook                    | [a6ecdfef67](https://linux-hardware.org/?probe=a6ecdfef67) | Aug 14, 2017 |
| Dell          | Vostro 1014                 | [6006f3386e](https://linux-hardware.org/?probe=6006f3386e) | Jul 22, 2017 |
| Lenovo        | ThinkPad Edge E445 20B1A... | [66cb77a61b](https://linux-hardware.org/?probe=66cb77a61b) | Apr 17, 2017 |
| ASUSTek       | N53SV                       | [bc8d639ebe](https://linux-hardware.org/?probe=bc8d639ebe) | Mar 29, 2017 |
| ASUSTek       | N53SV                       | [82afd214cb](https://linux-hardware.org/?probe=82afd214cb) | Mar 29, 2017 |
| Apple         | MacBookPro12,1              | [322a47ba97](https://linux-hardware.org/?probe=322a47ba97) | Mar 10, 2017 |
| HP            | 14                          | [645b644da7](https://linux-hardware.org/?probe=645b644da7) | Oct 31, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 93        | 16.37%  |
| Ubuntu 18.04        | 59        | 10.39%  |
| OpenMandriva 4.2    | 23        | 4.05%   |
| OpenMandriva 4.3    | 20        | 3.52%   |
| Arch                | 15        | 2.64%   |
| Pop!_OS 20.04       | 14        | 2.46%   |
| Zorin 15            | 13        | 2.29%   |
| Ubuntu 19.10        | 12        | 2.11%   |
| Fedora 35           | 12        | 2.11%   |
| Manjaro             | 11        | 1.94%   |
| Ubuntu 21.10        | 10        | 1.76%   |
| KDE neon 20.04      | 9         | 1.58%   |
| Arch Rolling        | 9         | 1.58%   |
| Linux Mint 19.3     | 8         | 1.41%   |
| Kubuntu 20.04       | 8         | 1.41%   |
| Xubuntu 20.04       | 7         | 1.23%   |
| Pop!_OS 21.04       | 7         | 1.23%   |
| Debian 11           | 7         | 1.23%   |
| ArcoLinux Rolling   | 7         | 1.23%   |
| Ubuntu 21.04        | 6         | 1.06%   |
| Ubuntu 19.04        | 6         | 1.06%   |
| Linux Mint 20.2     | 6         | 1.06%   |
| Fedora 34           | 6         | 1.06%   |
| Fedora 32           | 6         | 1.06%   |
| Debian 10           | 6         | 1.06%   |
| Xubuntu 18.04       | 5         | 0.88%   |
| Ubuntu 16.04        | 5         | 0.88%   |
| Fedora 33           | 5         | 0.88%   |
| EndeavourOS Rolling | 5         | 0.88%   |
| Elementary 6.1      | 5         | 0.88%   |
| Elementary 5.1.7    | 5         | 0.88%   |
| Zorin 16            | 4         | 0.7%    |
| Pop!_OS 20.10       | 4         | 0.7%    |
| Linux Mint 20.3     | 4         | 0.7%    |
| Linux Mint 20.1     | 4         | 0.7%    |
| Zorin 12            | 3         | 0.53%   |
| Ubuntu MATE 20.04   | 3         | 0.53%   |
| ROSA R9             | 3         | 0.53%   |
| Manjaro 18.1.5      | 3         | 0.53%   |
| LMDE 4              | 3         | 0.53%   |
| Linux Mint 20       | 3         | 0.53%   |
| Kali 2020.4         | 3         | 0.53%   |
| Endless 3.5.7       | 3         | 0.53%   |
| Elementary 6        | 3         | 0.53%   |
| Ubuntu Budgie 20.04 | 2         | 0.35%   |
| Ubuntu 20.10        | 2         | 0.35%   |
| Solus 4.1           | 2         | 0.35%   |
| ROSA R8.1           | 2         | 0.35%   |
| ROSA R10            | 2         | 0.35%   |
| Pop!_OS 21.10       | 2         | 0.35%   |
| Parrot 4.8          | 2         | 0.35%   |
| Manjaro 21.1.0      | 2         | 0.35%   |
| Manjaro 20.2.1      | 2         | 0.35%   |
| Manjaro 20.2        | 2         | 0.35%   |
| Manjaro 20.0.3      | 2         | 0.35%   |
| Manjaro 18.1.0      | 2         | 0.35%   |
| Manjaro 18.0.4      | 2         | 0.35%   |
| Lubuntu 20.04       | 2         | 0.35%   |
| Kubuntu 21.10       | 2         | 0.35%   |
| Kubuntu 18.04       | 2         | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 186       | 33.94%  |
| OpenMandriva  | 43        | 7.85%   |
| Fedora        | 32        | 5.84%   |
| Manjaro       | 31        | 5.66%   |
| Pop!_OS       | 27        | 4.93%   |
| Arch          | 25        | 4.56%   |
| Linux Mint    | 23        | 4.2%    |
| Zorin         | 20        | 3.65%   |
| Elementary    | 18        | 3.28%   |
| Xubuntu       | 15        | 2.74%   |
| Kubuntu       | 15        | 2.74%   |
| Debian        | 15        | 2.74%   |
| Endless       | 14        | 2.55%   |
| KDE neon      | 11        | 2.01%   |
| ROSA          | 8         | 1.46%   |
| Kali          | 8         | 1.46%   |
| ArcoLinux     | 8         | 1.46%   |
| Lubuntu       | 6         | 1.09%   |
| EndeavourOS   | 5         | 0.91%   |
| Ubuntu MATE   | 4         | 0.73%   |
| Parrot        | 4         | 0.73%   |
| Deepin        | 4         | 0.73%   |
| LMDE          | 3         | 0.55%   |
| Ubuntu Budgie | 2         | 0.36%   |
| Solus         | 2         | 0.36%   |
| openSUSE      | 2         | 0.36%   |
| Gentoo        | 2         | 0.36%   |
| Clear Linux   | 2         | 0.36%   |
| Chrome OS     | 2         | 0.36%   |
| CentOS        | 2         | 0.36%   |
| BlackPanther  | 2         | 0.36%   |
| Artix         | 2         | 0.36%   |
| Trisquel      | 1         | 0.18%   |
| Pear OS       | 1         | 0.18%   |
| NST           | 1         | 0.18%   |
| MX            | 1         | 0.18%   |
| Mageia        | 1         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 3.78%   |
| 5.16.7-desktop-1omv4003  | 20        | 3.28%   |
| 5.4.0-42-generic         | 16        | 2.63%   |
| 5.4.0-26-generic         | 11        | 1.81%   |
| 5.4.0-52-generic         | 9         | 1.48%   |
| 5.0.0-25-generic         | 8         | 1.31%   |
| 4.18.0-15-generic        | 8         | 1.31%   |
| 5.4.0-58-generic         | 7         | 1.15%   |
| 5.4.0-54-generic         | 7         | 1.15%   |
| 5.11.0-37-generic        | 7         | 1.15%   |
| 5.8.0-48-generic         | 6         | 0.99%   |
| 5.3.0-46-generic         | 6         | 0.99%   |
| 5.8.0-41-generic         | 5         | 0.82%   |
| 5.4.0-80-generic         | 5         | 0.82%   |
| 5.4.0-45-generic         | 5         | 0.82%   |
| 5.11.0-7620-generic      | 5         | 0.82%   |
| 5.11.0-40-generic        | 5         | 0.82%   |
| 5.0.0-23-generic         | 5         | 0.82%   |
| 5.4.0-7634-generic       | 4         | 0.66%   |
| 5.4.0-48-generic         | 4         | 0.66%   |
| 5.4.0-33-generic         | 4         | 0.66%   |
| 5.3.0-26-generic         | 4         | 0.66%   |
| 5.11.0-41-generic        | 4         | 0.66%   |
| 5.11.0-38-generic        | 4         | 0.66%   |
| 5.11.0-27-generic        | 4         | 0.66%   |
| 5.0.0-37-generic         | 4         | 0.66%   |
| 5.0.0-20-generic         | 4         | 0.66%   |
| 5.8.0-63-generic         | 3         | 0.49%   |
| 5.8.0-59-generic         | 3         | 0.49%   |
| 5.8.0-55-generic         | 3         | 0.49%   |
| 5.8.0-50-generic         | 3         | 0.49%   |
| 5.8.0-38-generic         | 3         | 0.49%   |
| 5.8.0-14-generic         | 3         | 0.49%   |
| 5.4.0-91-generic         | 3         | 0.49%   |
| 5.4.0-65-generic         | 3         | 0.49%   |
| 5.4.0-59-generic         | 3         | 0.49%   |
| 5.4.0-47-generic         | 3         | 0.49%   |
| 5.4.0-37-generic         | 3         | 0.49%   |
| 5.4.0-31-generic         | 3         | 0.49%   |
| 5.3.0-42-generic         | 3         | 0.49%   |
| 5.3.0-40-generic         | 3         | 0.49%   |
| 5.13.0-7620-generic      | 3         | 0.49%   |
| 5.13.0-30-generic        | 3         | 0.49%   |
| 5.13.0-28-generic        | 3         | 0.49%   |
| 5.13.0-27-generic        | 3         | 0.49%   |
| 5.11.0-7612-generic      | 3         | 0.49%   |
| 5.11.0-25-generic        | 3         | 0.49%   |
| 5.10.53-1-MANJARO        | 3         | 0.49%   |
| 5.0.0-32-generic         | 3         | 0.49%   |
| 4.15.0-76-generic        | 3         | 0.49%   |
| 5.9.11-3-MANJARO         | 2         | 0.33%   |
| 5.9.10-200.fc33.x86_64   | 2         | 0.33%   |
| 5.9.1-arch1-1            | 2         | 0.33%   |
| 5.8.5-arch1-1            | 2         | 0.33%   |
| 5.8.0-7642-generic       | 2         | 0.33%   |
| 5.8.0-7630-generic       | 2         | 0.33%   |
| 5.8.0-43-generic         | 2         | 0.33%   |
| 5.8.0-40-generic         | 2         | 0.33%   |
| 5.5.10-921.native        | 2         | 0.33%   |
| 5.4.0-96-generic         | 2         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 119       | 20.31%  |
| 5.11.0  | 47        | 8.02%   |
| 5.8.0   | 41        | 7%      |
| 5.3.0   | 33        | 5.63%   |
| 5.0.0   | 30        | 5.12%   |
| 4.15.0  | 27        | 4.61%   |
| 5.13.0  | 24        | 4.1%    |
| 5.10.14 | 24        | 4.1%    |
| 5.16.7  | 21        | 3.58%   |
| 4.18.0  | 17        | 2.9%    |
| 5.10.0  | 11        | 1.88%   |
| 4.19.0  | 11        | 1.88%   |
| 5.16.0  | 4         | 0.68%   |
| 5.15.12 | 4         | 0.68%   |
| 5.14.16 | 4         | 0.68%   |
| 5.9.11  | 3         | 0.51%   |
| 5.9.1   | 3         | 0.51%   |
| 5.17.5  | 3         | 0.51%   |
| 5.16.12 | 3         | 0.51%   |
| 5.15.0  | 3         | 0.51%   |
| 5.14.0  | 3         | 0.51%   |
| 5.11.11 | 3         | 0.51%   |
| 5.10.53 | 3         | 0.51%   |
| 4.9.20  | 3         | 0.51%   |
| 4.4.0   | 3         | 0.51%   |
| 5.9.10  | 2         | 0.34%   |
| 5.8.5   | 2         | 0.34%   |
| 5.8.3   | 2         | 0.34%   |
| 5.8.12  | 2         | 0.34%   |
| 5.7.7   | 2         | 0.34%   |
| 5.5.7   | 2         | 0.34%   |
| 5.5.10  | 2         | 0.34%   |
| 5.17.0  | 2         | 0.34%   |
| 5.16.19 | 2         | 0.34%   |
| 5.16.14 | 2         | 0.34%   |
| 5.15.6  | 2         | 0.34%   |
| 5.15.13 | 2         | 0.34%   |
| 5.15.11 | 2         | 0.34%   |
| 5.14.11 | 2         | 0.34%   |
| 5.13.12 | 2         | 0.34%   |
| 5.12.13 | 2         | 0.34%   |
| 5.10.49 | 2         | 0.34%   |
| 5.10.16 | 2         | 0.34%   |
| 5.10.11 | 2         | 0.34%   |
| 4.9.60  | 2         | 0.34%   |
| 4.19.69 | 2         | 0.34%   |
| 4.18.16 | 2         | 0.34%   |
| 4.13.0  | 2         | 0.34%   |
| 4.10.0  | 2         | 0.34%   |
| 5.9.4   | 1         | 0.17%   |
| 5.9.2   | 1         | 0.17%   |
| 5.9.16  | 1         | 0.17%   |
| 5.9.14  | 1         | 0.17%   |
| 5.8.9   | 1         | 0.17%   |
| 5.8.6   | 1         | 0.17%   |
| 5.8.4   | 1         | 0.17%   |
| 5.8.18  | 1         | 0.17%   |
| 5.8.1   | 1         | 0.17%   |
| 5.7.8   | 1         | 0.17%   |
| 5.7.14  | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 127       | 21.93%  |
| 5.10    | 57        | 9.84%   |
| 5.8     | 52        | 8.98%   |
| 5.11    | 50        | 8.64%   |
| 5.16    | 37        | 6.39%   |
| 5.3     | 35        | 6.04%   |
| 5.0     | 32        | 5.53%   |
| 5.13    | 29        | 5.01%   |
| 4.15    | 27        | 4.66%   |
| 4.18    | 20        | 3.45%   |
| 5.15    | 19        | 3.28%   |
| 4.19    | 16        | 2.76%   |
| 5.14    | 15        | 2.59%   |
| 5.9     | 12        | 2.07%   |
| 5.6     | 7         | 1.21%   |
| 5.17    | 7         | 1.21%   |
| 4.9     | 7         | 1.21%   |
| 5.12    | 6         | 1.04%   |
| 5.7     | 5         | 0.86%   |
| 5.5     | 5         | 0.86%   |
| 4.4     | 4         | 0.69%   |
| 5.2     | 2         | 0.35%   |
| 4.13    | 2         | 0.35%   |
| 4.10    | 2         | 0.35%   |
| 4.1     | 2         | 0.35%   |
| 5       | 1         | 0.17%   |
| 3.16    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 510       | 96.41%  |
| i686   | 19        | 3.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 227       | 41.42%  |
| KDE5            | 87        | 15.88%  |
| Unknown         | 70        | 12.77%  |
| XFCE            | 45        | 8.21%   |
| X-Cinnamon      | 24        | 4.38%   |
| KDE             | 18        | 3.28%   |
| Pantheon        | 17        | 3.1%    |
| MATE            | 14        | 2.55%   |
| Cinnamon        | 7         | 1.28%   |
| LXQt            | 6         | 1.09%   |
| Deepin          | 5         | 0.91%   |
| Budgie          | 5         | 0.91%   |
| Unity           | 3         | 0.55%   |
| sway            | 3         | 0.55%   |
| KDE4            | 3         | 0.55%   |
| qtile           | 2         | 0.36%   |
| ICEWM           | 2         | 0.36%   |
| i3              | 2         | 0.36%   |
| bspwm           | 2         | 0.36%   |
| xmonad          | 1         | 0.18%   |
| Lubuntu         | 1         | 0.18%   |
| GNOME Flashback | 1         | 0.18%   |
| dwm             | 1         | 0.18%   |
| Cutefish        | 1         | 0.18%   |
| awesomeminimal  | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 442       | 82.16%  |
| Wayland | 48        | 8.92%   |
| Unknown | 46        | 8.55%   |
| Tty     | 2         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 283       | 51.83%  |
| SDDM    | 90        | 16.48%  |
| GDM     | 87        | 15.93%  |
| LightDM | 38        | 6.96%   |
| TDM     | 28        | 5.13%   |
| GDM3    | 15        | 2.75%   |
| KDM     | 3         | 0.55%   |
| SLiM    | 1         | 0.18%   |
| Ly      | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 412       | 76.44%  |
| Unknown | 73        | 13.54%  |
| id_ID   | 39        | 7.24%   |
| en_GB   | 6         | 1.11%   |
| C       | 4         | 0.74%   |
| jv_ID   | 1         | 0.19%   |
| en_SG   | 1         | 0.19%   |
| en_IN   | 1         | 0.19%   |
| en_AU   | 1         | 0.19%   |
| de_CH   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 297       | 54.9%   |
| BIOS | 244       | 45.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 424       | 78.81%  |
| Btrfs   | 42        | 7.81%   |
| Overlay | 38        | 7.06%   |
| Unknown | 25        | 4.65%   |
| Ext2    | 3         | 0.56%   |
| Zfs     | 2         | 0.37%   |
| Xfs     | 2         | 0.37%   |
| F2fs    | 1         | 0.19%   |
| Ext3    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 294       | 54.75%  |
| GPT     | 171       | 31.84%  |
| MBR     | 72        | 13.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 473       | 88.25%  |
| Yes       | 63        | 11.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 298       | 55.19%  |
| Yes       | 242       | 44.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 134       | 25.33%  |
| ASUSTek Computer    | 124       | 23.44%  |
| Hewlett-Packard     | 85        | 16.07%  |
| Acer                | 74        | 13.99%  |
| Dell                | 40        | 7.56%   |
| Toshiba             | 18        | 3.4%    |
| MSI                 | 12        | 2.27%   |
| Apple               | 7         | 1.32%   |
| Sony                | 6         | 1.13%   |
| Fujitsu             | 6         | 1.13%   |
| Clevo               | 3         | 0.57%   |
| AXIOO               | 3         | 0.57%   |
| Samsung Electronics | 2         | 0.38%   |
| HUAWEI              | 2         | 0.38%   |
| Gigabyte Technology | 2         | 0.38%   |
| Unknown             | 2         | 0.38%   |
| Timi                | 1         | 0.19%   |
| Sole                | 1         | 0.19%   |
| Phoenix/SiS         | 1         | 0.19%   |
| Panasonic           | 1         | 0.19%   |
| Notebook            | 1         | 0.19%   |
| Infinix             | 1         | 0.19%   |
| Hampoo              | 1         | 0.19%   |
| Compal              | 1         | 0.19%   |
| Chuwi               | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G40-45 80E1                       | 9         | 1.7%    |
| HP Notebook                              | 8         | 1.51%   |
| Lenovo IdeaPad 330-14AST 81D5            | 6         | 1.13%   |
| HP Pavilion Aero Laptop 13-be0xxx        | 6         | 1.13%   |
| Acer Aspire 4752                         | 6         | 1.13%   |
| Lenovo IdeaPad S340-14API 81NB           | 5         | 0.95%   |
| HP 14                                    | 5         | 0.95%   |
| Lenovo G400 20235                        | 4         | 0.76%   |
| HP Pavilion 14                           | 4         | 0.76%   |
| HP Laptop 14-bw0xx                       | 4         | 0.76%   |
| HP Laptop 14-bs0xx                       | 4         | 0.76%   |
| ASUS X455YA                              | 4         | 0.76%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA  | 4         | 0.76%   |
| Acer Aspire 4750                         | 4         | 0.76%   |
| Unknown                                  | 4         | 0.76%   |
| Lenovo IdeaPad 320-14AST 80XU            | 3         | 0.57%   |
| Lenovo G400s 20244                       | 3         | 0.57%   |
| HP Pavilion g4                           | 3         | 0.57%   |
| HP Laptop 14-cm0xxx                      | 3         | 0.57%   |
| HP 1000                                  | 3         | 0.57%   |
| ASUS X450EA                              | 3         | 0.57%   |
| ASUS X442URR                             | 3         | 0.57%   |
| ASUS X200MA                              | 3         | 0.57%   |
| ASUS VivoBook_ASUSLaptop X412DA_A412DA   | 3         | 0.57%   |
| ASUS GL553VD                             | 3         | 0.57%   |
| Apple MacBookPro12,1                     | 3         | 0.57%   |
| Acer Swift SF314-56G                     | 3         | 0.57%   |
| Acer Swift SF314-41                      | 3         | 0.57%   |
| Acer Aspire E5-475G                      | 3         | 0.57%   |
| Lenovo V330-14IKB 81B0                   | 2         | 0.38%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS002BAU | 2         | 0.38%   |
| Lenovo IdeaPad Z460 20059                | 2         | 0.38%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 2         | 0.38%   |
| Lenovo IdeaPad 330-14IKB 81G2            | 2         | 0.38%   |
| Lenovo IdeaPad 3 14IIL05 81WD            | 2         | 0.38%   |
| Lenovo IdeaPad 100-14IBD 80RK            | 2         | 0.38%   |
| Lenovo G50-80 80E5                       | 2         | 0.38%   |
| Lenovo G40-30 80FY                       | 2         | 0.38%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.38%   |
| HP Laptop 15-bw0xx                       | 2         | 0.38%   |
| HP Laptop 14s-cf3xxx                     | 2         | 0.38%   |
| HP G42                                   | 2         | 0.38%   |
| HP EliteBook 840 G1                      | 2         | 0.38%   |
| HP EliteBook 2570p                       | 2         | 0.38%   |
| HP EliteBook 2560p                       | 2         | 0.38%   |
| Dell Vostro 5470                         | 2         | 0.38%   |
| Dell Vostro 14-3468                      | 2         | 0.38%   |
| Dell Latitude E7240                      | 2         | 0.38%   |
| Dell Latitude E6230                      | 2         | 0.38%   |
| Dell Latitude 5400                       | 2         | 0.38%   |
| Dell Inspiron 3458                       | 2         | 0.38%   |
| Clevo M7x0S                              | 2         | 0.38%   |
| ASUS X550ZE                              | 2         | 0.38%   |
| ASUS X456URK                             | 2         | 0.38%   |
| ASUS X456UQK                             | 2         | 0.38%   |
| ASUS X455LAB                             | 2         | 0.38%   |
| ASUS X453SA                              | 2         | 0.38%   |
| ASUS X450LCP                             | 2         | 0.38%   |
| ASUS X441UV                              | 2         | 0.38%   |
| ASUS X441BA                              | 2         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 53        | 10.02%  |
| Acer Aspire        | 46        | 8.7%    |
| Lenovo ThinkPad    | 44        | 8.32%   |
| ASUS VivoBook      | 21        | 3.97%   |
| HP Laptop          | 20        | 3.78%   |
| HP Pavilion        | 19        | 3.59%   |
| Dell Latitude      | 17        | 3.21%   |
| Toshiba Satellite  | 12        | 2.27%   |
| Dell Inspiron      | 11        | 2.08%   |
| Acer Swift         | 11        | 2.08%   |
| HP EliteBook       | 10        | 1.89%   |
| Lenovo G40-45      | 9         | 1.7%    |
| Dell Vostro        | 9         | 1.7%    |
| HP Notebook        | 8         | 1.51%   |
| ASUS TUF           | 6         | 1.13%   |
| Acer Nitro         | 6         | 1.13%   |
| HP ProBook         | 5         | 0.95%   |
| HP 14              | 5         | 0.95%   |
| Toshiba PORTEGE    | 4         | 0.76%   |
| Lenovo Yoga        | 4         | 0.76%   |
| Lenovo ThinkBook   | 4         | 0.76%   |
| Lenovo G400        | 4         | 0.76%   |
| ASUS X455YA        | 4         | 0.76%   |
| Unknown            | 4         | 0.76%   |
| MSI Modern         | 3         | 0.57%   |
| Lenovo G400s       | 3         | 0.57%   |
| HP ENVY            | 3         | 0.57%   |
| HP 1000            | 3         | 0.57%   |
| ASUS ZenBook       | 3         | 0.57%   |
| ASUS X450EA        | 3         | 0.57%   |
| ASUS X442URR       | 3         | 0.57%   |
| ASUS X200MA        | 3         | 0.57%   |
| ASUS GL553VD       | 3         | 0.57%   |
| Apple MacBookPro12 | 3         | 0.57%   |
| MSI GL65           | 2         | 0.38%   |
| Lenovo V330-14IKB  | 2         | 0.38%   |
| Lenovo Legion      | 2         | 0.38%   |
| Lenovo G50-80      | 2         | 0.38%   |
| Lenovo G40-30      | 2         | 0.38%   |
| HUAWEI BOHK-WAX9X  | 2         | 0.38%   |
| HP ZBook           | 2         | 0.38%   |
| HP Presario        | 2         | 0.38%   |
| HP G42             | 2         | 0.38%   |
| HP Compaq          | 2         | 0.38%   |
| Fujitsu LIFEBOOK   | 2         | 0.38%   |
| Dell XPS           | 2         | 0.38%   |
| Clevo M7x0S        | 2         | 0.38%   |
| AXIOO NEON         | 2         | 0.38%   |
| ASUS X550ZE        | 2         | 0.38%   |
| ASUS X456URK       | 2         | 0.38%   |
| ASUS X456UQK       | 2         | 0.38%   |
| ASUS X455LAB       | 2         | 0.38%   |
| ASUS X453SA        | 2         | 0.38%   |
| ASUS X450LCP       | 2         | 0.38%   |
| ASUS X441UV        | 2         | 0.38%   |
| ASUS X441BA        | 2         | 0.38%   |
| ASUS U36SD         | 2         | 0.38%   |
| ASUS S451LB        | 2         | 0.38%   |
| ASUS ROG           | 2         | 0.38%   |
| ASUS N46VM         | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 62        | 11.72%  |
| 2018 | 59        | 11.15%  |
| 2013 | 57        | 10.78%  |
| 2011 | 52        | 9.83%   |
| 2012 | 49        | 9.26%   |
| 2014 | 43        | 8.13%   |
| 2017 | 34        | 6.43%   |
| 2015 | 34        | 6.43%   |
| 2016 | 29        | 5.48%   |
| 2020 | 28        | 5.29%   |
| 2010 | 23        | 4.35%   |
| 2021 | 21        | 3.97%   |
| 2009 | 14        | 2.65%   |
| 2008 | 14        | 2.65%   |
| 2007 | 7         | 1.32%   |
| 2006 | 3         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 529       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 485       | 90.99%  |
| Enabled  | 48        | 9.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 529       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 169       | 31.77%  |
| 3.01-4.0    | 142       | 26.69%  |
| 8.01-16.0   | 86        | 16.17%  |
| 1.01-2.0    | 57        | 10.71%  |
| 16.01-24.0  | 54        | 10.15%  |
| 2.01-3.0    | 9         | 1.69%   |
| 32.01-64.0  | 6         | 1.13%   |
| 0.51-1.0    | 5         | 0.94%   |
| 24.01-32.0  | 3         | 0.56%   |
| 64.01-256.0 | 1         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 216       | 37.5%   |
| 2.01-3.0  | 169       | 29.34%  |
| 3.01-4.0  | 78        | 13.54%  |
| 4.01-8.0  | 64        | 11.11%  |
| 0.51-1.0  | 35        | 6.08%   |
| 8.01-16.0 | 10        | 1.74%   |
| 0.01-0.5  | 4         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 387       | 71.93%  |
| 2      | 133       | 24.72%  |
| 3      | 13        | 2.42%   |
| 0      | 3         | 0.56%   |
| 4      | 2         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 309       | 57.97%  |
| Yes       | 224       | 42.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 84.34%  |
| No        | 83        | 15.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 520       | 98.11%  |
| No        | 10        | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 406       | 76.6%   |
| No        | 124       | 23.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 529       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Jakarta             | 161       | 28.5%   |
| Surabaya            | 75        | 13.27%  |
| Bandung             | 32        | 5.66%   |
| Bekasi              | 27        | 4.78%   |
| Bogor               | 24        | 4.25%   |
| Semarang            | 19        | 3.36%   |
| Yogyakarta          | 17        | 3.01%   |
| Sleman              | 12        | 2.12%   |
| Malang              | 12        | 2.12%   |
| Denpasar            | 12        | 2.12%   |
| Tangerang           | 11        | 1.95%   |
| Medan               | 11        | 1.95%   |
| Makassar            | 9         | 1.59%   |
| Cirebon             | 6         | 1.06%   |
| Pontianak           | 5         | 0.88%   |
| Depok               | 5         | 0.88%   |
| Tasikmalaya         | 4         | 0.71%   |
| Palembang           | 4         | 0.71%   |
| Mataram             | 4         | 0.71%   |
| Batam               | 4         | 0.71%   |
| Banjarmasin         | 4         | 0.71%   |
| Surakarta           | 3         | 0.53%   |
| South Tangerang     | 3         | 0.53%   |
| Purwokerto          | 3         | 0.53%   |
| Pekan Baru          | 3         | 0.53%   |
| Palangkaraya        | 3         | 0.53%   |
| Kudus               | 3         | 0.53%   |
| Kediri              | 3         | 0.53%   |
| Jember              | 3         | 0.53%   |
| Balikpapan          | 3         | 0.53%   |
| Wonosari            | 2         | 0.35%   |
| Wonogiri            | 2         | 0.35%   |
| Sidoarjo            | 2         | 0.35%   |
| Samarinda           | 2         | 0.35%   |
| Lagadar             | 2         | 0.35%   |
| Jambi City          | 2         | 0.35%   |
| Gresik              | 2         | 0.35%   |
| Garut               | 2         | 0.35%   |
| Ciapus              | 2         | 0.35%   |
| Bengkulu            | 2         | 0.35%   |
| Watampone           | 1         | 0.18%   |
| Tulungagung         | 1         | 0.18%   |
| Ternate             | 1         | 0.18%   |
| Tegalgede           | 1         | 0.18%   |
| Tegal               | 1         | 0.18%   |
| Tabanan             | 1         | 0.18%   |
| Sungai Raya         | 1         | 0.18%   |
| Sumedang            | 1         | 0.18%   |
| Sukoharjo           | 1         | 0.18%   |
| South Jakarta       | 1         | 0.18%   |
| Sorong              | 1         | 0.18%   |
| Singaraja           | 1         | 0.18%   |
| Sindanglaya         | 1         | 0.18%   |
| Rintis              | 1         | 0.18%   |
| Rembangan           | 1         | 0.18%   |
| Purwakarta          | 1         | 0.18%   |
| Puruk Cahu          | 1         | 0.18%   |
| Pugeran Maguwoharjo | 1         | 0.18%   |
| Probolinggo         | 1         | 0.18%   |
| Poso                | 1         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 122       | 156    | 18.37%  |
| WDC                   | 88        | 103    | 13.25%  |
| Toshiba               | 75        | 82     | 11.3%   |
| Samsung Electronics   | 58        | 75     | 8.73%   |
| HGST                  | 42        | 46     | 6.33%   |
| Hitachi               | 29        | 35     | 4.37%   |
| Unknown               | 24        | 30     | 3.61%   |
| Kingston              | 21        | 28     | 3.16%   |
| Intel                 | 21        | 35     | 3.16%   |
| Sandisk               | 20        | 27     | 3.01%   |
| SK Hynix              | 15        | 15     | 2.26%   |
| A-DATA Technology     | 15        | 15     | 2.26%   |
| Micron Technology     | 13        | 14     | 1.96%   |
| V-GeN                 | 11        | 11     | 1.66%   |
| JMicron               | 8         | 9      | 1.2%    |
| Fujitsu               | 8         | 9      | 1.2%    |
| Apacer                | 7         | 7      | 1.05%   |
| Crucial               | 6         | 7      | 0.9%    |
| China                 | 6         | 6      | 0.9%    |
| Team                  | 5         | 8      | 0.75%   |
| MidasForce            | 5         | 5      | 0.75%   |
| Unknown               | 5         | 5      | 0.75%   |
| Silicon Motion        | 4         | 4      | 0.6%    |
| Patriot               | 4         | 6      | 0.6%    |
| RX7                   | 3         | 3      | 0.45%   |
| Pioneer               | 3         | 3      | 0.45%   |
| LITEON                | 3         | 4      | 0.45%   |
| Apple                 | 3         | 3      | 0.45%   |
| Realtek Semiconductor | 2         | 2      | 0.3%    |
| Phison                | 2         | 2      | 0.3%    |
| LITEONIT              | 2         | 2      | 0.3%    |
| Lexar                 | 2         | 2      | 0.3%    |
| HUAWEI                | 2         | 2      | 0.3%    |
| GALAX                 | 2         | 2      | 0.3%    |
| Corsair               | 2         | 2      | 0.3%    |
| XSTAR                 | 1         | 1      | 0.15%   |
| Vaseky                | 1         | 2      | 0.15%   |
| Varro                 | 1         | 1      | 0.15%   |
| Union Memory          | 1         | 1      | 0.15%   |
| UMIS                  | 1         | 1      | 0.15%   |
| Transcend             | 1         | 2      | 0.15%   |
| TO Exter              | 1         | 1      | 0.15%   |
| SPCC                  | 1         | 1      | 0.15%   |
| SNX                   | 1         | 1      | 0.15%   |
| Smart                 | 1         | 1      | 0.15%   |
| SDVPSA18              | 1         | 1      | 0.15%   |
| Realtek               | 1         | 1      | 0.15%   |
| PNY                   | 1         | 1      | 0.15%   |
| OSCOO                 | 1         | 1      | 0.15%   |
| OSC                   | 1         | 1      | 0.15%   |
| NGFF                  | 1         | 1      | 0.15%   |
| Memory                | 1         | 1      | 0.15%   |
| Lenovo                | 1         | 1      | 0.15%   |
| KIOXIA                | 1         | 1      | 0.15%   |
| KingDian              | 1         | 1      | 0.15%   |
| HGST HTS              | 1         | 3      | 0.15%   |
| Hewlett-Packard       | 1         | 1      | 0.15%   |
| FORESEE               | 1         | 1      | 0.15%   |
| External              | 1         | 1      | 0.15%   |
| Colorful              | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 27        | 3.97%   |
| Seagate ST500LT012-1DG142 500GB      | 25        | 3.68%   |
| Toshiba MQ01ABF050 500GB             | 15        | 2.21%   |
| Toshiba MQ01ABD100 1TB               | 15        | 2.21%   |
| Toshiba MQ04ABF100 1TB               | 13        | 1.91%   |
| HGST HTS545050A7E680 500GB           | 11        | 1.62%   |
| Seagate ST9500325AS 500GB            | 9         | 1.32%   |
| Sandisk NVMe SSD Drive 512GB         | 8         | 1.18%   |
| HGST HTS725050A7E630 500GB           | 8         | 1.18%   |
| A-DATA SU650 120GB SSD               | 8         | 1.18%   |
| Intel SSDPEKNW512G8 512GB            | 7         | 1.03%   |
| Hitachi HTS545050A7E380 500GB        | 7         | 1.03%   |
| Seagate ST2000LM007-1R8174 2TB       | 6         | 0.88%   |
| Samsung SSD 850 EVO 250GB            | 6         | 0.88%   |
| Hitachi HTS543232A7A384 320GB        | 6         | 0.88%   |
| HGST HTS721010A9E630 1TB             | 6         | 0.88%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 5         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 5         | 0.74%   |
| Unknown MMC Card  32GB               | 5         | 0.74%   |
| Seagate ST9320325AS 320GB            | 5         | 0.74%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 0.74%   |
| Seagate ST1000LX015-1U7172 1TB       | 5         | 0.74%   |
| HGST HTS545050A7E380 500GB           | 5         | 0.74%   |
| HGST HTS541010A9E680 1TB             | 5         | 0.74%   |
| Unknown                              | 5         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.59%   |
| Toshiba MQ01ABD032 320GB             | 4         | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB      | 4         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.59%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.59%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB | 4         | 0.59%   |
| JMicron Generic 160GB                | 4         | 0.59%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.59%   |
| Apacer AS340 240GB SSD               | 4         | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.44%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 3         | 0.44%   |
| WDC WD10SPZX-60Z10T0 1TB             | 3         | 0.44%   |
| WDC WD10JPVX-60JC3T0 1TB             | 3         | 0.44%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 3         | 0.44%   |
| Toshiba MQ01ABD050 500GB             | 3         | 0.44%   |
| Toshiba MK3265GSX 320GB              | 3         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.44%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.44%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.44%   |
| Micron NVMe SSD Drive 512GB          | 3         | 0.44%   |
| JMicron Tech 250GB                   | 3         | 0.44%   |
| Hitachi HTS545025B9A300 250GB        | 3         | 0.44%   |
| China SSD 120GB                      | 3         | 0.44%   |
| A-DATA SU650 240GB SSD               | 3         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.29%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 0.29%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.29%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.29%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.29%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 0.29%   |
| WDC WD10JPVX-00JC3T0 1TB             | 2         | 0.29%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 121       | 152    | 35.28%  |
| WDC                 | 68        | 75     | 19.83%  |
| Toshiba             | 68        | 75     | 19.83%  |
| HGST                | 42        | 46     | 12.24%  |
| Hitachi             | 29        | 35     | 8.45%   |
| Fujitsu             | 7         | 7      | 2.04%   |
| Samsung Electronics | 3         | 3      | 0.87%   |
| Unknown             | 2         | 2      | 0.58%   |
| JMicron             | 1         | 1      | 0.29%   |
| HGST HTS            | 1         | 3      | 0.29%   |
| Hewlett-Packard     | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 43     | 20.12%  |
| WDC                 | 12        | 19     | 7.1%    |
| Kingston            | 11        | 12     | 6.51%   |
| A-DATA Technology   | 11        | 11     | 6.51%   |
| SanDisk             | 10        | 15     | 5.92%   |
| Intel               | 7         | 11     | 4.14%   |
| Apacer              | 7         | 7      | 4.14%   |
| Crucial             | 6         | 7      | 3.55%   |
| China               | 6         | 6      | 3.55%   |
| V-GeN               | 5         | 5      | 2.96%   |
| MidasForce          | 5         | 5      | 2.96%   |
| Patriot             | 4         | 6      | 2.37%   |
| JMicron             | 4         | 4      | 2.37%   |
| Unknown             | 4         | 4      | 2.37%   |
| Team                | 3         | 6      | 1.78%   |
| Seagate             | 3         | 3      | 1.78%   |
| Pioneer             | 3         | 3      | 1.78%   |
| Micron Technology   | 3         | 4      | 1.78%   |
| LITEON              | 3         | 4      | 1.78%   |
| Apple               | 3         | 3      | 1.78%   |
| RX7                 | 2         | 2      | 1.18%   |
| LITEONIT            | 2         | 2      | 1.18%   |
| Lexar               | 2         | 2      | 1.18%   |
| GALAX               | 2         | 2      | 1.18%   |
| XSTAR               | 1         | 1      | 0.59%   |
| Vaseky              | 1         | 2      | 0.59%   |
| Varro               | 1         | 1      | 0.59%   |
| Toshiba             | 1         | 1      | 0.59%   |
| TO Exter            | 1         | 1      | 0.59%   |
| SPCC                | 1         | 1      | 0.59%   |
| Smart               | 1         | 1      | 0.59%   |
| SK Hynix            | 1         | 1      | 0.59%   |
| PNY                 | 1         | 1      | 0.59%   |
| OSCOO               | 1         | 1      | 0.59%   |
| NGFF                | 1         | 1      | 0.59%   |
| Memory              | 1         | 1      | 0.59%   |
| KingDian            | 1         | 1      | 0.59%   |
| FORESEE             | 1         | 1      | 0.59%   |
| External            | 1         | 1      | 0.59%   |
| Corsair             | 1         | 1      | 0.59%   |
| Colorful            | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 333       | 400    | 51.55%  |
| SSD     | 161       | 204    | 24.92%  |
| NVMe    | 114       | 145    | 17.65%  |
| Unknown | 20        | 24     | 3.1%    |
| MMC     | 18        | 22     | 2.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 437       | 603    | 73.82%  |
| NVMe | 114       | 144    | 19.26%  |
| SAS  | 23        | 26     | 3.89%   |
| MMC  | 18        | 22     | 3.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 323       | 416    | 68.14%  |
| 0.51-1.0   | 141       | 170    | 29.75%  |
| 1.01-2.0   | 10        | 18     | 2.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 149       | 27.04%  |
| 101-250        | 141       | 25.59%  |
| 501-1000       | 64        | 11.62%  |
| 51-100         | 63        | 11.43%  |
| 1001-2000      | 42        | 7.62%   |
| 1-20           | 40        | 7.26%   |
| 21-50          | 39        | 7.08%   |
| Unknown        | 6         | 1.09%   |
| More than 3000 | 4         | 0.73%   |
| 2001-3000      | 3         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 218       | 37.72%  |
| 21-50     | 110       | 19.03%  |
| 51-100    | 71        | 12.28%  |
| 101-250   | 70        | 12.11%  |
| 251-500   | 57        | 9.86%   |
| 501-1000  | 36        | 6.23%   |
| 1001-2000 | 8         | 1.38%   |
| Unknown   | 6         | 1.04%   |
| 2001-3000 | 2         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD032 320GB                       | 3         | 3      | 5.36%   |
| Seagate ST9500325AS 500GB                      | 3         | 3      | 5.36%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 5.36%   |
| HGST HTS545050A7E680 500GB                     | 3         | 3      | 5.36%   |
| Seagate ST500LT012-1DG142 500GB                | 2         | 2      | 3.57%   |
| Seagate ST1000LX015-1U7172 1TB                 | 2         | 3      | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 3.57%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 3.57%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 1.79%   |
| WDC WD5000L 500GB                              | 1         | 1      | 1.79%   |
| WDC WD5000BPVT-60HXZT3 500GB                   | 1         | 1      | 1.79%   |
| WDC WD3200BEKT-60V5T1 320GB                    | 1         | 1      | 1.79%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 1.79%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.79%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.79%   |
| Toshiba MK7575GSX 752GB                        | 1         | 2      | 1.79%   |
| Toshiba MK5075GSX 500GB                        | 1         | 1      | 1.79%   |
| Toshiba MK3276GSX 320GB                        | 1         | 1      | 1.79%   |
| Toshiba MK3275GSX 320GB                        | 1         | 1      | 1.79%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 1.79%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.79%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 1.79%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.79%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 5      | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 1      | 1.79%   |
| Seagate OOS1000G128M 1TB                       | 1         | 1      | 1.79%   |
| SanDisk SSD PLUS 120 GB                        | 1         | 1      | 1.79%   |
| SanDisk SDSSDA120G 120GB                       | 1         | 1      | 1.79%   |
| Samsung Electronics MZVLB512HAJQ-00000 512GB   | 1         | 1      | 1.79%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 1.79%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 1.79%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 1.79%   |
| Intel SSDSC2KF480H6L 480GB                     | 1         | 1      | 1.79%   |
| Hitachi HTS725016A9A364 160GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.79%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 1.79%   |
| HGST HTS545050A7E660 500GB                     | 1         | 1      | 1.79%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 1.79%   |
| Crucial CT512M550SSD3 512GB                    | 1         | 1      | 1.79%   |
| China SSD 120GB                                | 1         | 1      | 1.79%   |
| A-DATA Technology SU650 240GB SSD              | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 30.91%  |
| Toshiba             | 10        | 11     | 18.18%  |
| WDC                 | 6         | 6      | 10.91%  |
| Hitachi             | 6         | 6      | 10.91%  |
| HGST                | 6         | 6      | 10.91%  |
| SanDisk             | 2         | 2      | 3.64%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| Micron Technology   | 2         | 2      | 3.64%   |
| Intel               | 1         | 1      | 1.82%   |
| Crucial             | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 36.96%  |
| Toshiba             | 10        | 11     | 21.74%  |
| WDC                 | 6         | 6      | 13.04%  |
| Hitachi             | 6         | 6      | 13.04%  |
| HGST                | 6         | 6      | 13.04%  |
| Samsung Electronics | 1         | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 53     | 83.64%  |
| SSD  | 8         | 8      | 14.55%  |
| NVMe | 1         | 1      | 1.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 311       | 458    | 55.24%  |
| Works    | 196       | 274    | 34.81%  |
| Malfunc  | 55        | 62     | 9.77%   |
| Failed   | 1         | 1      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 372       | 62.21%  |
| AMD                              | 113       | 18.9%   |
| Samsung Electronics              | 26        | 4.35%   |
| Sandisk                          | 19        | 3.18%   |
| SK Hynix                         | 14        | 2.34%   |
| Micron Technology                | 10        | 1.67%   |
| Kingston Technology Company      | 10        | 1.67%   |
| Silicon Motion                   | 6         | 1%      |
| Toshiba America Info Systems     | 5         | 0.84%   |
| Phison Electronics               | 5         | 0.84%   |
| Silicon Integrated Systems [SiS] | 4         | 0.67%   |
| ADATA Technology                 | 4         | 0.67%   |
| Union Memory (Shenzhen)          | 3         | 0.5%    |
| Realtek Semiconductor            | 3         | 0.5%    |
| KIOXIA                           | 2         | 0.33%   |
| Lenovo                           | 1         | 0.17%   |
| ASMedia Technology               | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 104       | 16.3%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 54        | 8.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 46        | 7.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 40        | 6.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 32        | 5.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 27        | 4.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 20        | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 17        | 2.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 12        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 11        | 1.72%   |
| Intel SSD 660P Series                                                                  | 11        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 11        | 1.72%   |
| Micron Non-Volatile memory controller                                                  | 10        | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 10        | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 10        | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 10        | 1.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 9         | 1.41%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 8         | 1.25%   |
| Sandisk PC SN520 NVMe SSD                                                              | 7         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 0.94%   |
| SK Hynix BC511                                                                         | 5         | 0.78%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 5         | 0.78%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 5         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 5         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 4         | 0.63%   |
| Phison E12 NVMe Controller                                                             | 4         | 0.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 4         | 0.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 0.63%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 4         | 0.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 3         | 0.47%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.47%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                            | 3         | 0.47%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 3         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 3         | 0.47%   |
| Samsung Electronics SATA controller                                                    | 3         | 0.47%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.47%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 0.47%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 3         | 0.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 0.47%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.31%   |
| SK Hynix Gold P31 SSD                                                                  | 2         | 0.31%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 2         | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.31%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.31%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.31%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 439       | 71.15%  |
| NVMe | 114       | 18.48%  |
| IDE  | 34        | 5.51%   |
| RAID | 30        | 4.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 395       | 74.67%  |
| AMD    | 134       | 25.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 2.46%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 2.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 1.89%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 10        | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 7         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 1.32%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 7         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.32%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 7         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 1.13%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 6         | 1.13%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 5         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.95%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.95%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.95%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.95%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.95%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.95%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 5         | 0.95%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.95%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.95%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 5         | 0.95%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 5         | 0.95%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 5         | 0.95%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.76%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.76%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.76%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 4         | 0.76%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 4         | 0.76%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 4         | 0.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.76%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 4         | 0.76%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 4         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.57%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.57%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.57%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 3         | 0.57%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 3         | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.57%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.57%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 3         | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.57%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 144       | 27.22%  |
| Intel Core i7           | 85        | 16.07%  |
| Intel Core i3           | 74        | 13.99%  |
| Intel Celeron           | 33        | 6.24%   |
| AMD Ryzen 5             | 31        | 5.86%   |
| Other                   | 19        | 3.59%   |
| Intel Core 2 Duo        | 18        | 3.4%    |
| AMD A8                  | 17        | 3.21%   |
| Intel Pentium           | 13        | 2.46%   |
| AMD Ryzen 3             | 13        | 2.46%   |
| AMD Ryzen 7             | 9         | 1.7%    |
| Intel Atom              | 8         | 1.51%   |
| AMD E1                  | 8         | 1.51%   |
| AMD A4                  | 8         | 1.51%   |
| AMD A6                  | 7         | 1.32%   |
| Intel Pentium Dual      | 5         | 0.95%   |
| AMD E2                  | 5         | 0.95%   |
| AMD E                   | 5         | 0.95%   |
| Intel Genuine           | 4         | 0.76%   |
| AMD A10                 | 4         | 0.76%   |
| Intel Pentium Dual-Core | 3         | 0.57%   |
| AMD FX                  | 3         | 0.57%   |
| AMD C-60                | 3         | 0.57%   |
| AMD Athlon              | 3         | 0.57%   |
| Intel Core 2            | 2         | 0.38%   |
| AMD Ryzen 9             | 2         | 0.38%   |
| AMD A12                 | 2         | 0.38%   |
| AMD Turion 64 Mobile    | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 348       | 65.78%  |
| 4      | 138       | 26.09%  |
| 6      | 29        | 5.48%   |
| 1      | 8         | 1.51%   |
| 8      | 6         | 1.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 529       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 381       | 72.02%  |
| 1      | 148       | 27.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 515       | 97.35%  |
| Unknown        | 11        | 2.08%   |
| 32-bit         | 3         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 13.21%  |
| 0x206a7    | 49        | 8.99%   |
| 0x306a9    | 41        | 7.52%   |
| 0x40651    | 29        | 5.32%   |
| 0x306d4    | 21        | 3.85%   |
| 0x806ea    | 20        | 3.67%   |
| 0x806ec    | 18        | 3.3%    |
| 0x806e9    | 17        | 3.12%   |
| 0x20655    | 17        | 3.12%   |
| 0x06006705 | 16        | 2.94%   |
| 0x906ea    | 14        | 2.57%   |
| 0x806eb    | 13        | 2.39%   |
| 0x08108109 | 12        | 2.2%    |
| 0x07030105 | 12        | 2.2%    |
| 0x406e3    | 11        | 2.02%   |
| 0x1067a    | 11        | 2.02%   |
| 0x0a50000c | 10        | 1.83%   |
| 0x08108102 | 10        | 1.83%   |
| 0x6fd      | 9         | 1.65%   |
| 0x706e5    | 8         | 1.47%   |
| 0x306c3    | 8         | 1.47%   |
| 0x30678    | 8         | 1.47%   |
| 0x20652    | 7         | 1.28%   |
| 0x806c1    | 6         | 1.1%    |
| 0x406c4    | 6         | 1.1%    |
| 0x406c3    | 6         | 1.1%    |
| 0x06001119 | 6         | 1.1%    |
| 0x906e9    | 5         | 0.92%   |
| 0x506e3    | 5         | 0.92%   |
| 0x10676    | 5         | 0.92%   |
| 0x0810100b | 5         | 0.92%   |
| 0x0700010f | 5         | 0.92%   |
| 0x0600611a | 5         | 0.92%   |
| 0x05000119 | 5         | 0.92%   |
| 0x03000027 | 4         | 0.73%   |
| 0x08600104 | 3         | 0.55%   |
| 0x08101007 | 3         | 0.55%   |
| 0x06006704 | 3         | 0.55%   |
| 0x906ed    | 2         | 0.37%   |
| 0x706a1    | 2         | 0.37%   |
| 0x6fa      | 2         | 0.37%   |
| 0x6f6      | 2         | 0.37%   |
| 0x6ec      | 2         | 0.37%   |
| 0x506c9    | 2         | 0.37%   |
| 0x30673    | 2         | 0.37%   |
| 0x106ca    | 2         | 0.37%   |
| 0x08608103 | 2         | 0.37%   |
| 0x08608102 | 2         | 0.37%   |
| 0x08600103 | 2         | 0.37%   |
| 0x07030104 | 2         | 0.37%   |
| 0x0500010d | 2         | 0.37%   |
| 0x05000029 | 2         | 0.37%   |
| 0xa0660    | 1         | 0.18%   |
| 0x706a8    | 1         | 0.18%   |
| 0x6fb      | 1         | 0.18%   |
| 0x106c2    | 1         | 0.18%   |
| 0x0a50000b | 1         | 0.18%   |
| 0x08600106 | 1         | 0.18%   |
| 0x08600102 | 1         | 0.18%   |
| 0x07030106 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 99        | 18.71%  |
| SandyBridge   | 57        | 10.78%  |
| IvyBridge     | 45        | 8.51%   |
| Haswell       | 44        | 8.32%   |
| Excavator     | 27        | 5.1%    |
| Westmere      | 26        | 4.91%   |
| Zen+          | 25        | 4.73%   |
| Broadwell     | 24        | 4.54%   |
| Silvermont    | 23        | 4.35%   |
| Skylake       | 18        | 3.4%    |
| Puma          | 17        | 3.21%   |
| Penryn        | 17        | 3.21%   |
| Core          | 14        | 2.65%   |
| Zen 3         | 12        | 2.27%   |
| Bobcat        | 11        | 2.08%   |
| Zen           | 9         | 1.7%    |
| Zen 2         | 8         | 1.51%   |
| IceLake       | 8         | 1.51%   |
| Piledriver    | 7         | 1.32%   |
| Jaguar        | 7         | 1.32%   |
| TigerLake     | 6         | 1.13%   |
| K10 Llano     | 4         | 0.76%   |
| Bonnell       | 4         | 0.76%   |
| Unknown       | 4         | 0.76%   |
| Goldmont plus | 3         | 0.57%   |
| Goldmont      | 3         | 0.57%   |
| Steamroller   | 2         | 0.38%   |
| P6            | 2         | 0.38%   |
| CometLake     | 2         | 0.38%   |
| K8 Hammer     | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 382       | 54.96%  |
| AMD                              | 172       | 24.75%  |
| Nvidia                           | 137       | 19.71%  |
| Silicon Integrated Systems [SiS] | 4         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 54        | 7.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 45        | 6.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 4.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 3.38%   |
| Intel UHD Graphics 620                                                                   | 23        | 3.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 3.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2.98%   |
| Intel HD Graphics 5500                                                                   | 21        | 2.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 2.71%   |
| Intel HD Graphics 620                                                                    | 18        | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 2.3%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 2.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 15        | 2.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.62%   |
| AMD Cezanne                                                                              | 12        | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.22%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 1.08%   |
| AMD Renoir                                                                               | 8         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.95%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 7         | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.95%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.95%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.81%   |
| Intel HD Graphics 630                                                                    | 6         | 0.81%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.68%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 5         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.68%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 5         | 0.68%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.54%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.54%   |
| Intel HD Graphics 530                                                                    | 4         | 0.54%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 4         | 0.54%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.54%   |
| AMD Lucienne                                                                             | 4         | 0.54%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 4         | 0.54%   |
| Nvidia TU117M                                                                            | 3         | 0.41%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.41%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 3         | 0.41%   |
| Nvidia GF119M [GeForce 610M]                                                             | 3         | 0.41%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 3         | 0.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.41%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.41%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.41%   |
| Intel Iris Graphics 6100                                                                 | 3         | 0.41%   |
| Intel HD Graphics 500                                                                    | 3         | 0.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.41%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 233       | 43.8%   |
| Intel + Nvidia | 118       | 22.18%  |
| 1 x AMD        | 96        | 18.05%  |
| Intel + AMD    | 34        | 6.39%   |
| 2 x AMD        | 28        | 5.26%   |
| AMD + Nvidia   | 14        | 2.63%   |
| 1 x Nvidia     | 5         | 0.94%   |
| 1 x SiS        | 4         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 459       | 85.32%  |
| Proprietary | 67        | 12.45%  |
| Unknown     | 12        | 2.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 306       | 56.35%  |
| 1.01-2.0   | 102       | 18.78%  |
| 0.01-0.5   | 72        | 13.26%  |
| 0.51-1.0   | 32        | 5.89%   |
| 3.01-4.0   | 24        | 4.42%   |
| 5.01-6.0   | 5         | 0.92%   |
| 7.01-8.0   | 2         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 130       | 22.85%  |
| Chimei Innolux          | 103       | 18.1%   |
| BOE                     | 88        | 15.47%  |
| LG Display              | 79        | 13.88%  |
| Samsung Electronics     | 49        | 8.61%   |
| Goldstar                | 23        | 4.04%   |
| Lenovo                  | 11        | 1.93%   |
| PANDA                   | 7         | 1.23%   |
| Chi Mei Optoelectronics | 7         | 1.23%   |
| Apple                   | 7         | 1.23%   |
| Sharp                   | 6         | 1.05%   |
| Acer                    | 6         | 1.05%   |
| LG Philips              | 5         | 0.88%   |
| InnoLux Display         | 5         | 0.88%   |
| InfoVision              | 5         | 0.88%   |
| ViewSonic               | 4         | 0.7%    |
| Dell                    | 4         | 0.7%    |
| Philips                 | 3         | 0.53%   |
| HannStar                | 3         | 0.53%   |
| CPT                     | 3         | 0.53%   |
| AOC                     | 3         | 0.53%   |
| Toshiba                 | 2         | 0.35%   |
| Sony                    | 2         | 0.35%   |
| Seiko/Epson             | 2         | 0.35%   |
| Quanta Display          | 2         | 0.35%   |
| Panasonic               | 2         | 0.35%   |
| Hewlett-Packard         | 2         | 0.35%   |
| BenQ                    | 2         | 0.35%   |
| Mi                      | 1         | 0.18%   |
| HIC                     | 1         | 0.18%   |
| CSO                     | 1         | 0.18%   |
| Armaggeddon             | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 13        | 2.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 12        | 2.1%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 11        | 1.93%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 9         | 1.58%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 9         | 1.58%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 8         | 1.4%    |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 8         | 1.4%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 7         | 1.23%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 7         | 1.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 7         | 1.23%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 6         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 6         | 1.05%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 1.05%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 1.05%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 6         | 1.05%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 5         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 5         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 5         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch  | 4         | 0.7%    |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch          | 4         | 0.7%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 4         | 0.7%    |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 4         | 0.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.7%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.7%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 4         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.53%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 3         | 0.53%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 3         | 0.53%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 3         | 0.53%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 3         | 0.53%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch              | 3         | 0.53%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.53%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 3         | 0.53%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 3         | 0.53%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 3         | 0.53%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                  | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 3         | 0.53%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 2         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch | 2         | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.35%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.35%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.35%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 2         | 0.35%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 305       | 55.96%  |
| 1920x1080 (FHD)   | 157       | 28.81%  |
| 1280x800 (WXGA)   | 19        | 3.49%   |
| 1600x900 (HD+)    | 16        | 2.94%   |
| 3840x2160 (4K)    | 10        | 1.83%   |
| 1440x900 (WXGA+)  | 7         | 1.28%   |
| 1920x1200 (WUXGA) | 6         | 1.1%    |
| 2560x1440 (QHD)   | 5         | 0.92%   |
| 1360x768          | 4         | 0.73%   |
| 1024x600          | 4         | 0.73%   |
| 2560x1600         | 3         | 0.55%   |
| 3200x1800 (QHD+)  | 2         | 0.37%   |
| 2560x1080         | 2         | 0.37%   |
| 3440x1440         | 1         | 0.18%   |
| 2966x900          | 1         | 0.18%   |
| 2880x1800         | 1         | 0.18%   |
| 2736x1824         | 1         | 0.18%   |
| Unknown           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 175       | 30.81%  |
| 14      | 158       | 27.82%  |
| 15      | 113       | 19.89%  |
| 12      | 26        | 4.58%   |
| 23      | 18        | 3.17%   |
| 11      | 18        | 3.17%   |
| 18      | 14        | 2.46%   |
| 21      | 8         | 1.41%   |
| 19      | 6         | 1.06%   |
| 17      | 6         | 1.06%   |
| 24      | 5         | 0.88%   |
| 10      | 4         | 0.7%    |
| 34      | 3         | 0.53%   |
| Unknown | 3         | 0.53%   |
| 48      | 2         | 0.35%   |
| 40      | 2         | 0.35%   |
| 27      | 2         | 0.35%   |
| 72      | 1         | 0.18%   |
| 54      | 1         | 0.18%   |
| 31      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |
| 9       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 401       | 71.23%  |
| 201-300     | 83        | 14.74%  |
| 401-500     | 28        | 4.97%   |
| 501-600     | 24        | 4.26%   |
| 351-400     | 13        | 2.31%   |
| 701-800     | 3         | 0.53%   |
| 1001-1500   | 3         | 0.53%   |
| Unknown     | 3         | 0.53%   |
| 801-900     | 2         | 0.36%   |
| 601-700     | 2         | 0.36%   |
| 1501-2000   | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 469       | 91.07%  |
| 16/10   | 38        | 7.38%   |
| 21/9    | 3         | 0.58%   |
| Unknown | 3         | 0.58%   |
| 4/3     | 1         | 0.19%   |
| 3/2     | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 301       | 52.99%  |
| 101-110        | 113       | 19.89%  |
| 201-250        | 31        | 5.46%   |
| 71-80          | 29        | 5.11%   |
| 61-70          | 25        | 4.4%    |
| 51-60          | 18        | 3.17%   |
| 141-150        | 14        | 2.46%   |
| 151-200        | 7         | 1.23%   |
| 41-50          | 5         | 0.88%   |
| More than 1000 | 4         | 0.7%    |
| 351-500        | 4         | 0.7%    |
| 121-130        | 4         | 0.7%    |
| 91-100         | 4         | 0.7%    |
| Unknown        | 3         | 0.53%   |
| 301-350        | 2         | 0.35%   |
| 131-140        | 2         | 0.35%   |
| 501-1000       | 2         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 274       | 48.93%  |
| 121-160       | 178       | 31.79%  |
| 51-100        | 66        | 11.79%  |
| 161-240       | 25        | 4.46%   |
| More than 240 | 9         | 1.61%   |
| 1-50          | 5         | 0.89%   |
| Unknown       | 3         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 464       | 85.93%  |
| 2     | 60        | 11.11%  |
| 0     | 14        | 2.59%   |
| 3     | 2         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 319       | 36.92%  |
| Qualcomm Atheros                  | 196       | 22.69%  |
| Intel                             | 189       | 21.88%  |
| Broadcom                          | 60        | 6.94%   |
| Broadcom Limited                  | 14        | 1.62%   |
| MEDIATEK                          | 9         | 1.04%   |
| Xiaomi                            | 8         | 0.93%   |
| Ralink Technology                 | 8         | 0.93%   |
| Samsung Electronics               | 7         | 0.81%   |
| Marvell Technology Group          | 7         | 0.81%   |
| Ralink                            | 6         | 0.69%   |
| TP-Link                           | 5         | 0.58%   |
| Qualcomm Atheros Communications   | 5         | 0.58%   |
| JMicron Technology                | 5         | 0.58%   |
| Huawei Technologies               | 4         | 0.46%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.35%   |
| OPPO Electronics                  | 3         | 0.35%   |
| Attansic Technology               | 3         | 0.35%   |
| Sierra Wireless                   | 2         | 0.23%   |
| Qualcomm                          | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| ICS Advent                        | 1         | 0.12%   |
| HTC (High Tech Computer)          | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Foxconn / Hon Hai                 | 1         | 0.12%   |
| ASUSTek Computer                  | 1         | 0.12%   |
| ASIX Electronics                  | 1         | 0.12%   |
| AboCom Systems                    | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 200       | 19.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 78        | 7.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 53        | 5.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 43        | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 2.54%   |
| Intel Wireless 8265 / 8275                                              | 23        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 2.15%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 17        | 1.66%   |
| Intel Wireless 7265                                                     | 17        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.56%   |
| Intel Wireless 7260                                                     | 14        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 13        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 10        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 10        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 8         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                   | 8         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 6         | 0.59%   |
| Intel Wireless 3165                                                     | 6         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 5         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.49%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.49%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.39%   |
| Intel Wireless 8260                                                     | 4         | 0.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.39%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.39%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 4         | 0.39%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 3         | 0.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.29%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 179       | 33.03%  |
| Intel                           | 175       | 32.29%  |
| Realtek Semiconductor           | 99        | 18.27%  |
| Broadcom                        | 48        | 8.86%   |
| Broadcom Limited                | 11        | 2.03%   |
| Ralink Technology               | 8         | 1.48%   |
| MEDIATEK                        | 7         | 1.29%   |
| Ralink                          | 6         | 1.11%   |
| Qualcomm Atheros Communications | 5         | 0.92%   |
| TP-Link                         | 2         | 0.37%   |
| Sierra Wireless                 | 1         | 0.18%   |
| AboCom Systems                  | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 53        | 9.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 43        | 7.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 4.76%   |
| Intel Wireless 8265 / 8275                                              | 23        | 4.21%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 17        | 3.11%   |
| Intel Wireless 7265                                                     | 17        | 3.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 2.93%   |
| Intel Wireless 7260                                                     | 14        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 2.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 2.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.1%    |
| Intel Wireless 3165                                                     | 6         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.73%   |
| Intel Wireless 8260                                                     | 4         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.73%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.73%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 4         | 0.73%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.55%   |
| Intel Wireless 3160                                                     | 3         | 0.55%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.55%   |
| Intel Centrino Wireless-N 135                                           | 3         | 0.55%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.55%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.55%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.55%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.37%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.37%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.37%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.37%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.37%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 2         | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 287       | 60.68%  |
| Intel                            | 67        | 14.16%  |
| Qualcomm Atheros                 | 44        | 9.3%    |
| Broadcom                         | 19        | 4.02%   |
| Xiaomi                           | 8         | 1.69%   |
| Samsung Electronics              | 7         | 1.48%   |
| Marvell Technology Group         | 7         | 1.48%   |
| JMicron Technology               | 5         | 1.06%   |
| Broadcom Limited                 | 5         | 1.06%   |
| TP-Link                          | 3         | 0.63%   |
| Silicon Integrated Systems [SiS] | 3         | 0.63%   |
| OPPO Electronics                 | 3         | 0.63%   |
| Attansic Technology              | 3         | 0.63%   |
| Qualcomm                         | 2         | 0.42%   |
| MediaTek                         | 2         | 0.42%   |
| Sierra Wireless                  | 1         | 0.21%   |
| ICS Advent                       | 1         | 0.21%   |
| Huawei Technologies              | 1         | 0.21%   |
| HTC (High Tech Computer)         | 1         | 0.21%   |
| Hewlett-Packard                  | 1         | 0.21%   |
| Foxconn / Hon Hai                | 1         | 0.21%   |
| ASUSTek Computer                 | 1         | 0.21%   |
| ASIX Electronics                 | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 200       | 42.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 78        | 16.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 4.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 2.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 2.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 2.11%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.84%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.63%   |
| OPPO SDM665-IDP _SN:18689828                                      | 3         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.63%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.63%   |
| TP-Link USB 10/100 LAN                                            | 2         | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.42%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.42%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 2         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.21%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.21%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.21%   |
| Qualcomm Mi A1                                                    | 1         | 0.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.21%   |
| MediaTek WP7                                                      | 1         | 0.21%   |
| MediaTek NOA N2                                                   | 1         | 0.21%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.21%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.21%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.21%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.21%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.21%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.21%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.21%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.21%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.21%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.21%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.21%   |
| Huawei E353/E3131                                                 | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 520       | 53.55%  |
| Ethernet | 446       | 45.93%  |
| Modem    | 5         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 472       | 73.63%  |
| Ethernet | 168       | 26.21%  |
| Modem    | 1         | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 417       | 78.53%  |
| 1     | 107       | 20.15%  |
| 0     | 4         | 0.75%   |
| 3     | 3         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 521       | 98.3%   |
| Yes  | 9         | 1.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 129       | 31.7%   |
| Realtek Semiconductor           | 65        | 15.97%  |
| Qualcomm Atheros Communications | 48        | 11.79%  |
| IMC Networks                    | 44        | 10.81%  |
| Lite-On Technology              | 35        | 8.6%    |
| Broadcom                        | 28        | 6.88%   |
| Foxconn / Hon Hai               | 17        | 4.18%   |
| Toshiba                         | 8         | 1.97%   |
| Apple                           | 7         | 1.72%   |
| Dell                            | 5         | 1.23%   |
| Ralink                          | 4         | 0.98%   |
| Hewlett-Packard                 | 3         | 0.74%   |
| Foxconn International           | 3         | 0.74%   |
| Cambridge Silicon Radio         | 3         | 0.74%   |
| Realtek                         | 2         | 0.49%   |
| Micro Star International        | 2         | 0.49%   |
| ASUSTek Computer                | 2         | 0.49%   |
| MediaTek                        | 1         | 0.25%   |
| Chicony Electronics             | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 61        | 14.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 41        | 10.07%  |
| Realtek Bluetooth Radio                                    | 34        | 8.35%   |
| IMC Networks Bluetooth Device                              | 28        | 6.88%   |
| Qualcomm Atheros  Bluetooth Device                         | 20        | 4.91%   |
| Realtek 802.11n WLAN Adapter                               | 16        | 3.93%   |
| Qualcomm Atheros AR3011 Bluetooth                          | 13        | 3.19%   |
| Lite-On Bluetooth Device                                   | 13        | 3.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 11        | 2.7%    |
| Intel AX200 Bluetooth                                      | 9         | 2.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                 | 8         | 1.97%   |
| Intel AX201 Bluetooth                                      | 8         | 1.97%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter          | 8         | 1.97%   |
| Realtek RTL8723B Bluetooth                                 | 7         | 1.72%   |
| Realtek RTL8821A Bluetooth                                 | 6         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver              | 6         | 1.47%   |
| Lite-On Atheros Bluetooth                                  | 5         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                           | 5         | 1.23%   |
| IMC Networks Bluetooth Radio                               | 5         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                          | 5         | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 5         | 1.23%   |
| Toshiba RT Bluetooth Radio                                 | 4         | 0.98%   |
| Ralink RT3290 Bluetooth                                    | 4         | 0.98%   |
| Apple Bluetooth Host Controller                            | 4         | 0.98%   |
| Lite-On Wireless_Device                                    | 3         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module          | 3         | 0.74%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller            | 3         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                         | 3         | 0.74%   |
| Foxconn / Hon Hai Acer Module                              | 3         | 0.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 3         | 0.74%   |
| Broadcom HP Portable SoftSailing                           | 3         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth Device                       | 3         | 0.74%   |
| Broadcom BCM20702A0                                        | 3         | 0.74%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                       | 3         | 0.74%   |
| Apple Bluetooth HCI                                        | 3         | 0.74%   |
| Toshiba Integrated Bluetooth HCI                           | 2         | 0.49%   |
| Realtek  Bluetooth 4.2 Adapter                             | 2         | 0.49%   |
| Realtek Bluetooth Radio                                    | 2         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 2         | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller             | 2         | 0.49%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device | 2         | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                           | 2         | 0.49%   |
| Intel Bluetooth Device                                     | 2         | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                           | 2         | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                          | 2         | 0.49%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device            | 2         | 0.49%   |
| Foxconn / Hon Hai BCM20702A0                               | 2         | 0.49%   |
| Dell DW375 Bluetooth Module                                | 2         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                                | 2         | 0.49%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                 | 1         | 0.25%   |
| Toshiba Bluetooth Device                                   | 1         | 0.25%   |
| MediaTek Wireless_Device                                   | 1         | 0.25%   |
| Lite-On Bluetooth Radio                                    | 1         | 0.25%   |
| IMC Networks Broadcom Bluetooth 2.1                        | 1         | 0.25%   |
| IMC Networks Bluetooth USB Host Controller                 | 1         | 0.25%   |
| IMC Networks BCM20702A0                                    | 1         | 0.25%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]              | 1         | 0.25%   |
| Foxconn / Hon Hai BT                                       | 1         | 0.25%   |
| Foxconn / Hon Hai Acer Bluetooth module                    | 1         | 0.25%   |
| Dell Wireless 365 Bluetooth                                | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 387       | 66.49%  |
| AMD                              | 136       | 23.37%  |
| Nvidia                           | 38        | 6.53%   |
| Silicon Integrated Systems [SiS] | 4         | 0.69%   |
| Samson Technologies              | 3         | 0.52%   |
| JMTek                            | 3         | 0.52%   |
| Samsung Electronics              | 2         | 0.34%   |
| Generalplus Technology           | 2         | 0.34%   |
| C-Media Electronics              | 2         | 0.34%   |
| USB-MIC                          | 1         | 0.17%   |
| SAVITECH                         | 1         | 0.17%   |
| Logitech                         | 1         | 0.17%   |
| Cooler Master                    | 1         | 0.17%   |
| ASUSTek Computer                 | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 58        | 7.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 57        | 7.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 7.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 45        | 5.81%   |
| AMD FCH Azalia Controller                                                                         | 42        | 5.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 4.39%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 4.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 31        | 4.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 4.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 27        | 3.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 3.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 3.1%    |
| Intel Broadwell-U Audio Controller                                                                | 24        | 3.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 2.84%   |
| AMD High Definition Audio Controller                                                              | 20        | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 2.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.29%   |
| AMD Wrestler HDMI Audio                                                                           | 10        | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 7         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.78%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.65%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.52%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.39%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.39%   |
| Samsung Electronics USBC Headset                                                                  | 2         | 0.26%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.26%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.26%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 2         | 0.26%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 0.26%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 2         | 0.26%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.26%   |
| USB-MIC USB-MIC                                                                                   | 1         | 0.13%   |
| SAVITECH FiiO USB DAC K1                                                                          | 1         | 0.13%   |
| Samson Technologies Q2U handheld microphone with XLR                                              | 1         | 0.13%   |
| Samson Technologies GoMic compact condenser mic                                                   | 1         | 0.13%   |
| Samson Technologies C01U Pro condenser microphone                                                 | 1         | 0.13%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.13%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.13%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.13%   |
| Nvidia Audio device                                                                               | 1         | 0.13%   |
| Logitech Headset H340                                                                             | 1         | 0.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 116       | 31.35%  |
| SK Hynix            | 71        | 19.19%  |
| Micron Technology   | 42        | 11.35%  |
| Kingston            | 30        | 8.11%   |
| Unknown             | 28        | 7.57%   |
| Team                | 13        | 3.51%   |
| Corsair             | 13        | 3.51%   |
| V-GeN               | 11        | 2.97%   |
| Ramaxel Technology  | 11        | 2.97%   |
| Elpida              | 10        | 2.7%    |
| Nanya Technology    | 6         | 1.62%   |
| A-DATA Technology   | 3         | 0.81%   |
| Visipro             | 2         | 0.54%   |
| ASint Technology    | 2         | 0.54%   |
| Apacer              | 2         | 0.54%   |
| A Force             | 2         | 0.54%   |
| Transcend           | 1         | 0.27%   |
| Strontium           | 1         | 0.27%   |
| Silicon Power       | 1         | 0.27%   |
| SHARETRONIC         | 1         | 0.27%   |
| Patriot             | 1         | 0.27%   |
| GOODRAM             | 1         | 0.27%   |
| Crucial             | 1         | 0.27%   |
| Unknown             | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 11        | 2.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 11        | 2.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 7         | 1.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 1.75%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 1.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 1.5%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 1.5%    |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 6         | 1.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 1.25%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 5         | 1.25%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s               | 4         | 1%      |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s             | 4         | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1%      |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s              | 4         | 1%      |
| V-GeN RAM D4R8GS24A8R 8GB SODIMM DDR4 2400MT/s                      | 3         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 3         | 0.75%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.75%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.75%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 3         | 0.75%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.75%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 3         | 0.75%   |
| Samsung RAM M471B5674-M0-YK0 4096MB Chip DDR3 1600MT/s              | 3         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.75%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 3         | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.75%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.75%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 3         | 0.75%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.75%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.75%   |
| V-GeN RAM D3R4GS16B8R 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                          | 2         | 0.5%    |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s                | 2         | 0.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                        | 2         | 0.5%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.5%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.5%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.5%    |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.5%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.5%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 0.5%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.5%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.5%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s       | 2         | 0.5%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 2         | 0.5%    |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s               | 2         | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 0.5%    |
| Samsung RAM M471B5273DH0-YKO 4GB SODIMM DDR4 2400MT/s               | 2         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.5%    |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s               | 2         | 0.5%    |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.5%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 2         | 0.5%    |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 2         | 0.5%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 2         | 0.5%    |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s                | 2         | 0.5%    |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s    | 2         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 130       | 46.1%   |
| DDR4    | 125       | 44.33%  |
| DDR2    | 11        | 3.9%    |
| LPDDR4  | 5         | 1.77%   |
| LPDDR3  | 5         | 1.77%   |
| SDRAM   | 4         | 1.42%   |
| DRAM    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 266       | 93.99%  |
| Row Of Chips | 14        | 4.95%   |
| Chip         | 3         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 141       | 43.65%  |
| 8192  | 99        | 30.65%  |
| 2048  | 56        | 17.34%  |
| 16384 | 15        | 4.64%   |
| 1024  | 6         | 1.86%   |
| 32768 | 5         | 1.55%   |
| 512   | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 97        | 28.87%  |
| 2667    | 67        | 19.94%  |
| 2400    | 34        | 10.12%  |
| 3200    | 27        | 8.04%   |
| 2133    | 20        | 5.95%   |
| 1334    | 20        | 5.95%   |
| 1333    | 18        | 5.36%   |
| 3266    | 11        | 3.27%   |
| 1067    | 7         | 2.08%   |
| 667     | 6         | 1.79%   |
| 800     | 5         | 1.49%   |
| Unknown | 5         | 1.49%   |
| 8400    | 4         | 1.19%   |
| 4266    | 4         | 1.19%   |
| 4199    | 3         | 0.89%   |
| 533     | 3         | 0.89%   |
| 4267    | 1         | 0.3%    |
| 2048    | 1         | 0.3%    |
| 1867    | 1         | 0.3%    |
| 1776    | 1         | 0.3%    |
| 333     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 6         | 60%     |
| Canon              | 2         | 20%     |
| Brother Industries | 2         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L312 Series | 2         | 20%     |
| Seiko Epson L222 Series | 2         | 20%     |
| Canon iP2700 series     | 2         | 20%     |
| Brother DCP-T300        | 2         | 20%     |
| Seiko Epson L405 Series | 1         | 10%     |
| Seiko Epson L355 Series | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 143       | 29.98%  |
| IMC Networks                           | 73        | 15.3%   |
| Realtek Semiconductor                  | 43        | 9.01%   |
| Acer                                   | 38        | 7.97%   |
| Sunplus Innovation Technology          | 32        | 6.71%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 5.03%   |
| Syntek                                 | 22        | 4.61%   |
| Quanta                                 | 19        | 3.98%   |
| Suyin                                  | 16        | 3.35%   |
| Alcor Micro                            | 16        | 3.35%   |
| Microdia                               | 14        | 2.94%   |
| Lite-On Technology                     | 9         | 1.89%   |
| Importek                               | 4         | 0.84%   |
| Apple                                  | 4         | 0.84%   |
| Silicon Motion                         | 3         | 0.63%   |
| Ricoh                                  | 3         | 0.63%   |
| Lenovo                                 | 2         | 0.42%   |
| webcam                                 | 1         | 0.21%   |
| Sunplus Technology                     | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| Omnivision                             | 1         | 0.21%   |
| Luxvisions Innotech Limited            | 1         | 0.21%   |
| Logitech                               | 1         | 0.21%   |
| Jieli Technology                       | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| DigiTech                               | 1         | 0.21%   |
| ALi                                    | 1         | 0.21%   |
| 8SSC20F27114V1GZ07N14V2                | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                               | 24        | 5.01%   |
| Chicony Integrated Camera                                       | 21        | 4.38%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 20        | 4.18%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 16        | 3.34%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 15        | 3.13%   |
| Chicony USB2.0 HD UVC WebCam                                    | 14        | 2.92%   |
| Syntek Integrated Camera                                        | 13        | 2.71%   |
| Acer Lenovo EasyCamera                                          | 11        | 2.3%    |
| Realtek USB2.0 VGA UVC WebCam                                   | 10        | 2.09%   |
| IMC Networks Lenovo EasyCamera                                  | 10        | 2.09%   |
| Realtek Integrated_Webcam_HD                                    | 9         | 1.88%   |
| IMC Networks Integrated Camera                                  | 8         | 1.67%   |
| IMC Networks EasyCamera                                         | 8         | 1.67%   |
| Chicony Lenovo EasyCamera                                       | 8         | 1.67%   |
| Sunplus ASUS USB2.0 Webcam                                      | 7         | 1.46%   |
| Chicony HP TrueVision HD Camera                                 | 7         | 1.46%   |
| Chicony HP Truevision HD                                        | 7         | 1.46%   |
| Quanta HD User Facing                                           | 6         | 1.25%   |
| Alcor Micro Asus Integrated Webcam                              | 6         | 1.25%   |
| Syntek EasyCamera                                               | 5         | 1.04%   |
| Suyin 1.3M HD WebCam                                            | 5         | 1.04%   |
| Sunplus Integrated_Webcam_HD                                    | 5         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam                                    | 5         | 1.04%   |
| Realtek USB Camera                                              | 5         | 1.04%   |
| Microdia Integrated_Webcam_HD                                   | 5         | 1.04%   |
| Microdia Integrated Webcam                                      | 5         | 1.04%   |
| Lite-On Integrated Camera                                       | 5         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 5         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 5         | 1.04%   |
| Acer Integrated Camera                                          | 5         | 1.04%   |
| Acer EasyCamera                                                 | 5         | 1.04%   |
| Acer BisonCam, NB Pro                                           | 5         | 1.04%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.84%   |
| Sunplus HP TrueVision HD Camera                                 | 4         | 0.84%   |
| Sunplus HD WebCam                                               | 4         | 0.84%   |
| Realtek HP Truevision HD                                        | 4         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 4         | 0.84%   |
| Acer HD Webcam                                                  | 4         | 0.84%   |
| Sunplus Integrated Webcam                                       | 3         | 0.63%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 0.63%   |
| Quanta HD Webcam                                                | 3         | 0.63%   |
| IMC Networks USB2.0 UVC 2M WebCam                               | 3         | 0.63%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 3         | 0.63%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 3         | 0.63%   |
| Chicony EasyCamera                                              | 3         | 0.63%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 0.63%   |
| Suyin HD WebCam                                                 | 2         | 0.42%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 2         | 0.42%   |
| Sunplus HP Truevision HD                                        | 2         | 0.42%   |
| Sunplus 1.3M HD WebCam                                          | 2         | 0.42%   |
| Realtek Integrated Webcam                                       | 2         | 0.42%   |
| Realtek HD WebCam                                               | 2         | 0.42%   |
| Quanta USB2.0 VGA UVC WebCam                                    | 2         | 0.42%   |
| Quanta ov9734_techfront_camera                                  | 2         | 0.42%   |
| Lenovo Integrated Webcam [R5U877]                               | 2         | 0.42%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 2         | 0.42%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 2         | 0.42%   |
| IMC Networks USB Camera                                         | 2         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 33.33%  |
| Elan Microelectronics      | 17        | 20.99%  |
| LighTuning Technology      | 11        | 13.58%  |
| Synaptics                  | 9         | 11.11%  |
| Shenzhen Goodix Technology | 8         | 9.88%   |
| AuthenTec                  | 5         | 6.17%   |
| Upek                       | 2         | 2.47%   |
| STMicroelectronics         | 2         | 2.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor            | 10        | 12.35%  |
| Elan ELAN:Fingerprint                                  | 10        | 12.35%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 7         | 8.64%   |
| Elan ELAN:ARM-M4                                       | 6         | 7.41%   |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 6.17%   |
| Shenzhen Goodix  FingerPrint Device                    | 5         | 6.17%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 3.7%    |
| Validity Sensors VFS Fingerprint sensor                | 3         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor              | 3         | 3.7%    |
| Synaptics  WBDI                                        | 3         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 3.7%    |
| Unknown                                                | 3         | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 2.47%   |
| Validity Sensors VFS491                                | 2         | 2.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 2.47%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 2.47%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.47%   |
| AuthenTec AES1600                                      | 2         | 2.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 1.23%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 1.23%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 1.23%   |
| AuthenTec AES2810                                      | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 47.62%  |
| Upek        | 4         | 19.05%  |
| Alcor Micro | 3         | 14.29%  |
| O2 Micro    | 2         | 9.52%   |
| Lenovo      | 2         | 9.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 19.05%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 9.52%   |
| Broadcom 58200                                                               | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 366       | 67.9%   |
| 1     | 133       | 24.68%  |
| 2     | 35        | 6.49%   |
| 3     | 4         | 0.74%   |
| 6     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 38.39%  |
| Graphics card            | 50        | 23.7%   |
| Net/wireless             | 22        | 10.43%  |
| Chipcard                 | 20        | 9.48%   |
| Bluetooth                | 12        | 5.69%   |
| Multimedia controller    | 8         | 3.79%   |
| Communication controller | 4         | 1.9%    |
| Camera                   | 4         | 1.9%    |
| Storage                  | 3         | 1.42%   |
| Net/ethernet             | 3         | 1.42%   |
| Flash memory             | 2         | 0.95%   |
| Video                    | 1         | 0.47%   |
| Card reader              | 1         | 0.47%   |


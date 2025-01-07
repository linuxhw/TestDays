Linux in Bosnia and Herzegovina - Tested Hardware & Statistics
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bosnia_and_Herzegovina/Desktop/README.md) and [notebooks](/Location/Bosnia_and_Herzegovina/Notebook/README.md).

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

Total: 314

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [976937be1b](https://linux-hardware.org/?probe=976937be1b) | Jan 04, 2025 |
| Dell          | Latitude 5400               | Notebook    | [a0a87d0a74](https://linux-hardware.org/?probe=a0a87d0a74) | Dec 20, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [1ddb9a6cc4](https://linux-hardware.org/?probe=1ddb9a6cc4) | Dec 16, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [166754f7f0](https://linux-hardware.org/?probe=166754f7f0) | Dec 15, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [07be2a8da3](https://linux-hardware.org/?probe=07be2a8da3) | Dec 04, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [63d611d479](https://linux-hardware.org/?probe=63d611d479) | Dec 04, 2024 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [8e7c6af74e](https://linux-hardware.org/?probe=8e7c6af74e) | Dec 03, 2024 |
| HP            | 3647h                       | Desktop     | [51467508f1](https://linux-hardware.org/?probe=51467508f1) | Nov 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [62f849e117](https://linux-hardware.org/?probe=62f849e117) | Nov 03, 2024 |
| Dell          | Precision 7760              | Notebook    | [4501715128](https://linux-hardware.org/?probe=4501715128) | Oct 23, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [51933b9433](https://linux-hardware.org/?probe=51933b9433) | Oct 02, 2024 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [653a368c95](https://linux-hardware.org/?probe=653a368c95) | Aug 23, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f97ff2ebb7](https://linux-hardware.org/?probe=f97ff2ebb7) | Aug 22, 2024 |
| Dell          | Latitude 5310               | Notebook    | [df5c866666](https://linux-hardware.org/?probe=df5c866666) | Aug 22, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6111dba761](https://linux-hardware.org/?probe=6111dba761) | Jul 09, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ac6b23dc13](https://linux-hardware.org/?probe=ac6b23dc13) | Jun 25, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b46f1b99c](https://linux-hardware.org/?probe=4b46f1b99c) | Jun 25, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [e46cc0b4af](https://linux-hardware.org/?probe=e46cc0b4af) | Jun 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [672b23493e](https://linux-hardware.org/?probe=672b23493e) | May 20, 2024 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [b9a73e885c](https://linux-hardware.org/?probe=b9a73e885c) | May 20, 2024 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [30b88ebda2](https://linux-hardware.org/?probe=30b88ebda2) | May 12, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [789d6cf5b0](https://linux-hardware.org/?probe=789d6cf5b0) | May 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303ebb0865](https://linux-hardware.org/?probe=303ebb0865) | Apr 23, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [4a8c3625a7](https://linux-hardware.org/?probe=4a8c3625a7) | Apr 21, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [daefa26759](https://linux-hardware.org/?probe=daefa26759) | Apr 07, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [3a9aaf0732](https://linux-hardware.org/?probe=3a9aaf0732) | Apr 07, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [d70516fc56](https://linux-hardware.org/?probe=d70516fc56) | Apr 06, 2024 |
| ASUSTek       | N53SM                       | Notebook    | [bcb219bdc4](https://linux-hardware.org/?probe=bcb219bdc4) | Mar 24, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [55b19ba38d](https://linux-hardware.org/?probe=55b19ba38d) | Mar 12, 2024 |
| Gigabyte      | H81M-DS2                    | Desktop     | [db79be4310](https://linux-hardware.org/?probe=db79be4310) | Mar 09, 2024 |
| Lenovo        | ThinkPad L460 20FVS0F300    | Notebook    | [ded1a91bc6](https://linux-hardware.org/?probe=ded1a91bc6) | Feb 12, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [289b01375b](https://linux-hardware.org/?probe=289b01375b) | Feb 09, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [e28911df4d](https://linux-hardware.org/?probe=e28911df4d) | Feb 08, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [8898fc6264](https://linux-hardware.org/?probe=8898fc6264) | Feb 07, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [8fb8a8b448](https://linux-hardware.org/?probe=8fb8a8b448) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [80e1b72580](https://linux-hardware.org/?probe=80e1b72580) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [4904a2c798](https://linux-hardware.org/?probe=4904a2c798) | Jan 22, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [aa2c5d9a1a](https://linux-hardware.org/?probe=aa2c5d9a1a) | Jan 20, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a358114f21](https://linux-hardware.org/?probe=a358114f21) | Jan 12, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [dc6bb19505](https://linux-hardware.org/?probe=dc6bb19505) | Jan 10, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [66eedf0a68](https://linux-hardware.org/?probe=66eedf0a68) | Jan 10, 2024 |
| Notebook      | NL5xRU                      | Notebook    | [8e36b92a02](https://linux-hardware.org/?probe=8e36b92a02) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e832f6b336](https://linux-hardware.org/?probe=e832f6b336) | Dec 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b3e3c041d7](https://linux-hardware.org/?probe=b3e3c041d7) | Dec 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [42a7acfe4b](https://linux-hardware.org/?probe=42a7acfe4b) | Dec 09, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [34a16ab09d](https://linux-hardware.org/?probe=34a16ab09d) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cf6dd1eb40](https://linux-hardware.org/?probe=cf6dd1eb40) | Dec 01, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [ed93047829](https://linux-hardware.org/?probe=ed93047829) | Dec 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5bbcf82cf2](https://linux-hardware.org/?probe=5bbcf82cf2) | Nov 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3aa5e4bed1](https://linux-hardware.org/?probe=3aa5e4bed1) | Nov 30, 2023 |
| HP            | 1495                        | Desktop     | [cf77f4899b](https://linux-hardware.org/?probe=cf77f4899b) | Nov 29, 2023 |
| HP            | 1495                        | Desktop     | [eafdff069c](https://linux-hardware.org/?probe=eafdff069c) | Nov 29, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9388f41e11](https://linux-hardware.org/?probe=9388f41e11) | Nov 25, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [fb0f45f5b0](https://linux-hardware.org/?probe=fb0f45f5b0) | Nov 24, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [af55920808](https://linux-hardware.org/?probe=af55920808) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [d1351ee5be](https://linux-hardware.org/?probe=d1351ee5be) | Nov 22, 2023 |
| Dell          | Latitude E6510              | Notebook    | [1ac84451c5](https://linux-hardware.org/?probe=1ac84451c5) | Nov 21, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [e65cf40bcb](https://linux-hardware.org/?probe=e65cf40bcb) | Nov 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5ddcb0cf64](https://linux-hardware.org/?probe=5ddcb0cf64) | Nov 15, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [8d5332d643](https://linux-hardware.org/?probe=8d5332d643) | Nov 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [99b0c9edcf](https://linux-hardware.org/?probe=99b0c9edcf) | Nov 06, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [705aaea029](https://linux-hardware.org/?probe=705aaea029) | Oct 22, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [665eba904c](https://linux-hardware.org/?probe=665eba904c) | Oct 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [452da22731](https://linux-hardware.org/?probe=452da22731) | Oct 13, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [805de64f39](https://linux-hardware.org/?probe=805de64f39) | Oct 13, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7287dcbe60](https://linux-hardware.org/?probe=7287dcbe60) | Oct 13, 2023 |
| Medion        | MS-7800                     | Desktop     | [806b81f839](https://linux-hardware.org/?probe=806b81f839) | Oct 11, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [6f4fb2dff4](https://linux-hardware.org/?probe=6f4fb2dff4) | Oct 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a9cdcdc284](https://linux-hardware.org/?probe=a9cdcdc284) | Sep 14, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [a747d33ab9](https://linux-hardware.org/?probe=a747d33ab9) | Sep 09, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [d72c4b5cce](https://linux-hardware.org/?probe=d72c4b5cce) | Sep 06, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [ac307135fa](https://linux-hardware.org/?probe=ac307135fa) | Sep 02, 2023 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| HP            | 1497                        | Desktop     | [8bb03862e2](https://linux-hardware.org/?probe=8bb03862e2) | Aug 24, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [13edff3291](https://linux-hardware.org/?probe=13edff3291) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [194ec12831](https://linux-hardware.org/?probe=194ec12831) | Aug 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [8a30480f48](https://linux-hardware.org/?probe=8a30480f48) | Jul 26, 2023 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| MSI           | Pulse GL66 12UDK            | Notebook    | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| Toshiba       | Satellite L850-1HQ          | Notebook    | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| Dell          | Precision 5570              | Notebook    | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [4f5efbc9fe](https://linux-hardware.org/?probe=4f5efbc9fe) | May 16, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [8041b17525](https://linux-hardware.org/?probe=8041b17525) | May 16, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | Notebook    | [48009f1be4](https://linux-hardware.org/?probe=48009f1be4) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | Notebook    | [49e6d93eb1](https://linux-hardware.org/?probe=49e6d93eb1) | May 15, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [f87cd6e36c](https://linux-hardware.org/?probe=f87cd6e36c) | May 07, 2023 |
| Toshiba       | Satellite C855              | Notebook    | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [bb2041a761](https://linux-hardware.org/?probe=bb2041a761) | Apr 11, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [e0fcb10ef5](https://linux-hardware.org/?probe=e0fcb10ef5) | Apr 04, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [24d0950a77](https://linux-hardware.org/?probe=24d0950a77) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [76f456d63a](https://linux-hardware.org/?probe=76f456d63a) | Mar 10, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [149a0b40c6](https://linux-hardware.org/?probe=149a0b40c6) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [0f1c657481](https://linux-hardware.org/?probe=0f1c657481) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [94f5848c13](https://linux-hardware.org/?probe=94f5848c13) | Mar 05, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [fa70608ed8](https://linux-hardware.org/?probe=fa70608ed8) | Mar 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [68ea374074](https://linux-hardware.org/?probe=68ea374074) | Mar 02, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9b4ed72eaa](https://linux-hardware.org/?probe=9b4ed72eaa) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [319d6a8bc3](https://linux-hardware.org/?probe=319d6a8bc3) | Mar 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce63d81075](https://linux-hardware.org/?probe=ce63d81075) | Mar 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [81ec9ba8b3](https://linux-hardware.org/?probe=81ec9ba8b3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d6243ec239](https://linux-hardware.org/?probe=d6243ec239) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [c219f70324](https://linux-hardware.org/?probe=c219f70324) | Jan 11, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [03dd6fafbb](https://linux-hardware.org/?probe=03dd6fafbb) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [143bdba9bc](https://linux-hardware.org/?probe=143bdba9bc) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [ea19c0ace0](https://linux-hardware.org/?probe=ea19c0ace0) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| HP            | 1495                        | Desktop     | [681abdb8a2](https://linux-hardware.org/?probe=681abdb8a2) | Dec 25, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [b2ae663fec](https://linux-hardware.org/?probe=b2ae663fec) | Dec 16, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4241008f07](https://linux-hardware.org/?probe=4241008f07) | Oct 16, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [03a74f0a7b](https://linux-hardware.org/?probe=03a74f0a7b) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| HP            | ProBook 6560b               | Notebook    | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [f646dceb7c](https://linux-hardware.org/?probe=f646dceb7c) | Aug 10, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc99c10d57](https://linux-hardware.org/?probe=fc99c10d57) | Jul 13, 2022 |
| Dell          | Latitude E6410              | Notebook    | [cde668d556](https://linux-hardware.org/?probe=cde668d556) | Jul 12, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a15b38ef5e](https://linux-hardware.org/?probe=a15b38ef5e) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | Notebook    | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [3fff5f40c3](https://linux-hardware.org/?probe=3fff5f40c3) | Apr 24, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [090b87ad9b](https://linux-hardware.org/?probe=090b87ad9b) | Apr 24, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f26ffb9177](https://linux-hardware.org/?probe=f26ffb9177) | Apr 11, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [636817086a](https://linux-hardware.org/?probe=636817086a) | Apr 08, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| HP            | 0A54h                       | Desktop     | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [076c89e071](https://linux-hardware.org/?probe=076c89e071) | Mar 22, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [565a9dc93c](https://linux-hardware.org/?probe=565a9dc93c) | Mar 22, 2022 |
| Dell          | Inspiron 5323               | Notebook    | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [456ab60c06](https://linux-hardware.org/?probe=456ab60c06) | Feb 22, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | Notebook    | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [95ccf112af](https://linux-hardware.org/?probe=95ccf112af) | Feb 14, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [bc32230a7f](https://linux-hardware.org/?probe=bc32230a7f) | Feb 09, 2022 |
| HP            | 550                         | Notebook    | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | Notebook    | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [52eb9930ad](https://linux-hardware.org/?probe=52eb9930ad) | Nov 14, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | Notebook    | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [63b6ade950](https://linux-hardware.org/?probe=63b6ade950) | Sep 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| eMachines     | eME728                      | Notebook    | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | Notebook    | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| HP            | 1497                        | Desktop     | [e68557fd01](https://linux-hardware.org/?probe=e68557fd01) | Jul 07, 2021 |
| Dell          | Latitude E7470              | Notebook    | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [bc2d293d15](https://linux-hardware.org/?probe=bc2d293d15) | Jun 18, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ef21ac93c3](https://linux-hardware.org/?probe=ef21ac93c3) | Jun 18, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | Notebook    | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | Notebook    | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| ASRock        | H61M-HVGS                   | Desktop     | [3f3962df59](https://linux-hardware.org/?probe=3f3962df59) | May 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10dd12b38c](https://linux-hardware.org/?probe=10dd12b38c) | May 15, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [30aeb41807](https://linux-hardware.org/?probe=30aeb41807) | May 14, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | Notebook    | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [19df1ffb17](https://linux-hardware.org/?probe=19df1ffb17) | Apr 27, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bee3da385c](https://linux-hardware.org/?probe=bee3da385c) | Mar 23, 2021 |
| HP            | 198E                        | Desktop     | [85ba542969](https://linux-hardware.org/?probe=85ba542969) | Mar 10, 2021 |
| HP            | 198E                        | Desktop     | [8a79f9e398](https://linux-hardware.org/?probe=8a79f9e398) | Mar 10, 2021 |
| Dell          | G3 3590                     | Notebook    | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | Notebook    | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9b37eaa9f8](https://linux-hardware.org/?probe=9b37eaa9f8) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7d18048067](https://linux-hardware.org/?probe=7d18048067) | Jan 26, 2021 |
| Acer          | AO756                       | Notebook    | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | Notebook    | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| HP            | 1496                        | Desktop     | [7d2d9cd210](https://linux-hardware.org/?probe=7d2d9cd210) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [5532ead8e7](https://linux-hardware.org/?probe=5532ead8e7) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| HP            | 3032h                       | Desktop     | [63d3c61c19](https://linux-hardware.org/?probe=63d3c61c19) | Nov 03, 2020 |
| HP            | 3032h                       | Desktop     | [d8cfe55684](https://linux-hardware.org/?probe=d8cfe55684) | Nov 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [1f8e16d74f](https://linux-hardware.org/?probe=1f8e16d74f) | Oct 25, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [188328b998](https://linux-hardware.org/?probe=188328b998) | Sep 27, 2020 |
| HP            | 8446                        | All in one  | [a12a0781b1](https://linux-hardware.org/?probe=a12a0781b1) | Sep 25, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35560a3a70](https://linux-hardware.org/?probe=35560a3a70) | Sep 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ECS           | G31T-M7                     | Desktop     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2726ac41f8](https://linux-hardware.org/?probe=2726ac41f8) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [92e454c839](https://linux-hardware.org/?probe=92e454c839) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cac26af0fc](https://linux-hardware.org/?probe=cac26af0fc) | Sep 07, 2020 |
| ASUSTek       | X75VBP                      | Notebook    | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Dell          | 0M858N A01                  | Desktop     | [5b7ae4f768](https://linux-hardware.org/?probe=5b7ae4f768) | Aug 13, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | Notebook    | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | Notebook    | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| Dell          | 0RF703                      | Desktop     | [e23b194d28](https://linux-hardware.org/?probe=e23b194d28) | Jul 25, 2020 |
| ASUSTek       | Z97-P                       | Desktop     | [d0375fe030](https://linux-hardware.org/?probe=d0375fe030) | Jul 15, 2020 |
| Acer          | Aspire M1200                | Desktop     | [9311c4fa37](https://linux-hardware.org/?probe=9311c4fa37) | Jun 27, 2020 |
| Acer          | Aspire M1200                | Desktop     | [8d9a1aefd5](https://linux-hardware.org/?probe=8d9a1aefd5) | Jun 27, 2020 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [1a6102d9f3](https://linux-hardware.org/?probe=1a6102d9f3) | Jun 17, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | Notebook    | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| Acer          | Aspire M1200                | Desktop     | [2cbc71cc6f](https://linux-hardware.org/?probe=2cbc71cc6f) | May 24, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c668c517d8](https://linux-hardware.org/?probe=c668c517d8) | Apr 24, 2020 |
| HP            | Compaq CQ58                 | Notebook    | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | Notebook    | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4e3e7a0cca](https://linux-hardware.org/?probe=4e3e7a0cca) | Apr 20, 2020 |
| HP            | 255 G2                      | Notebook    | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Gigabyte      | nForce                      | Desktop     | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [fa5624c697](https://linux-hardware.org/?probe=fa5624c697) | Mar 27, 2020 |
| Acer          | Aspire 9300                 | Notebook    | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [0dbb663114](https://linux-hardware.org/?probe=0dbb663114) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ce73a67dba](https://linux-hardware.org/?probe=ce73a67dba) | Mar 26, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [84bed079c2](https://linux-hardware.org/?probe=84bed079c2) | Mar 23, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [10793053f1](https://linux-hardware.org/?probe=10793053f1) | Mar 23, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [7121b34b5e](https://linux-hardware.org/?probe=7121b34b5e) | Feb 21, 2020 |
| ASUSTek       | X751MD                      | Notebook    | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| MSI           | GF615M-P33                  | Desktop     | [34605f2e7f](https://linux-hardware.org/?probe=34605f2e7f) | Feb 06, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [64c7222709](https://linux-hardware.org/?probe=64c7222709) | Dec 22, 2019 |
| Dell          | 0RF703                      | Desktop     | [3cc8664913](https://linux-hardware.org/?probe=3cc8664913) | Nov 09, 2019 |
| Pegatron      | Eureka3                     | Desktop     | [5d42e73d08](https://linux-hardware.org/?probe=5d42e73d08) | Oct 20, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Dell          | 0RF703                      | Desktop     | [e97de552d8](https://linux-hardware.org/?probe=e97de552d8) | Jul 29, 2019 |
| Dell          | 0RF703                      | Desktop     | [08019d8b5f](https://linux-hardware.org/?probe=08019d8b5f) | Jul 29, 2019 |
| Dell          | 0MM599                      | Desktop     | [0b9fef01ec](https://linux-hardware.org/?probe=0b9fef01ec) | Jun 19, 2019 |
| Dell          | 0MM599                      | Desktop     | [8376d2c77c](https://linux-hardware.org/?probe=8376d2c77c) | Jun 19, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [aa5f7a836b](https://linux-hardware.org/?probe=aa5f7a836b) | May 04, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3aed29ae25](https://linux-hardware.org/?probe=3aed29ae25) | Apr 27, 2019 |
| HP            | 0A64h                       | Desktop     | [ab563902ff](https://linux-hardware.org/?probe=ab563902ff) | Apr 22, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [3ce6d97f47](https://linux-hardware.org/?probe=3ce6d97f47) | Apr 21, 2019 |
| Gigabyte      | Z390 UD                     | Desktop     | [48041296ca](https://linux-hardware.org/?probe=48041296ca) | Mar 15, 2019 |
| Sony          | VGN-BX41VN                  | Notebook    | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | Notebook    | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |
| ASUSTek       | M2N-SLI                     | Desktop     | [77800cbaf6](https://linux-hardware.org/?probe=77800cbaf6) | Mar 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 22        | 10.23%  |
| Ubuntu 22.04       | 13        | 6.05%   |
| Ubuntu 18.04       | 10        | 4.65%   |
| Pop!_OS 21.04      | 6         | 2.79%   |
| OpenMandriva 4.3   | 6         | 2.79%   |
| Arch Rolling       | 6         | 2.79%   |
| Zorin 16           | 5         | 2.33%   |
| Ubuntu 23.04       | 4         | 1.86%   |
| Manjaro            | 4         | 1.86%   |
| Linux Mint 21.1    | 4         | 1.86%   |
| Linux Mint 20.2    | 4         | 1.86%   |
| Linux Mint 19.3    | 4         | 1.86%   |
| ArcoLinux Rolling  | 4         | 1.86%   |
| Zorin 17           | 3         | 1.4%    |
| Xubuntu 20.04      | 3         | 1.4%    |
| Ubuntu 24.04       | 3         | 1.4%    |
| Ubuntu 20.10       | 3         | 1.4%    |
| Pop!_OS 20.04      | 3         | 1.4%    |
| OpenMandriva 23.03 | 3         | 1.4%    |
| Linux Mint 19.1    | 3         | 1.4%    |
| KDE neon 20.04     | 3         | 1.4%    |
| Fedora 39          | 3         | 1.4%    |
| Fedora 38          | 3         | 1.4%    |
| Fedora 32          | 3         | 1.4%    |
| Debian 10          | 3         | 1.4%    |
| Zorin 15           | 2         | 0.93%   |
| Ubuntu 21.10       | 2         | 0.93%   |
| Ubuntu 19.04       | 2         | 0.93%   |
| TUXEDO OS 22.04    | 2         | 0.93%   |
| ROSA R10           | 2         | 0.93%   |
| ROSA 12.4          | 2         | 0.93%   |
| Pop!_OS 20.10      | 2         | 0.93%   |
| OpenMandriva 23.01 | 2         | 0.93%   |
| MX 23              | 2         | 0.93%   |
| Lubuntu 19.10      | 2         | 0.93%   |
| Linux Mint 21      | 2         | 0.93%   |
| Linux Mint 20.1    | 2         | 0.93%   |
| Kubuntu 22.04      | 2         | 0.93%   |
| Fedora 41          | 2         | 0.93%   |
| Fedora 37          | 2         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 55        | 26.96%  |
| Linux Mint       | 22        | 10.78%  |
| Fedora           | 17        | 8.33%   |
| Pop!_OS          | 13        | 6.37%   |
| OpenMandriva     | 12        | 5.88%   |
| Zorin            | 10        | 4.9%    |
| Debian           | 9         | 4.41%   |
| Manjaro          | 7         | 3.43%   |
| Arch             | 7         | 3.43%   |
| ROSA             | 5         | 2.45%   |
| KDE neon         | 5         | 2.45%   |
| Endless          | 5         | 2.45%   |
| Xubuntu          | 4         | 1.96%   |
| ArcoLinux        | 4         | 1.96%   |
| Lubuntu          | 3         | 1.47%   |
| Elementary       | 3         | 1.47%   |
| Ubuntu Unity     | 2         | 0.98%   |
| TUXEDO OS        | 2         | 0.98%   |
| MX               | 2         | 0.98%   |
| LMDE             | 2         | 0.98%   |
| Kubuntu          | 2         | 0.98%   |
| Xero             | 1         | 0.49%   |
| Ubuntu Studio    | 1         | 0.49%   |
| Ubuntu Budgie    | 1         | 0.49%   |
| Rocky Linux      | 1         | 0.49%   |
| PureOS           | 1         | 0.49%   |
| Parrot           | 1         | 0.49%   |
| org.kde.Platform | 1         | 0.49%   |
| openSUSE         | 1         | 0.49%   |
| Nobara           | 1         | 0.49%   |
| Kali             | 1         | 0.49%   |
| Garuda Linux     | 1         | 0.49%   |
| EndeavourOS      | 1         | 0.49%   |
| BunsenLabs       | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 6         | 2.58%   |
| 5.3.0-28-generic                | 5         | 2.15%   |
| 5.4.0-52-generic                | 4         | 1.72%   |
| 5.15.0-56-generic               | 4         | 1.72%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.29%   |
| 6.2.0-20-generic                | 3         | 1.29%   |
| 5.3.0-46-generic                | 3         | 1.29%   |
| 5.15.0-48-generic               | 3         | 1.29%   |
| 5.13.0-39-generic               | 3         | 1.29%   |
| 6.5.0-14-generic                | 2         | 0.86%   |
| 6.2.0-36-generic                | 2         | 0.86%   |
| 6.2.0-32-generic                | 2         | 0.86%   |
| 6.2.0-26-generic                | 2         | 0.86%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.86%   |
| 6.1.0-13-amd64                  | 2         | 0.86%   |
| 5.8.0-7630-generic              | 2         | 0.86%   |
| 5.8.0-59-generic                | 2         | 0.86%   |
| 5.4.0-89-generic                | 2         | 0.86%   |
| 5.4.0-67-generic                | 2         | 0.86%   |
| 5.3.0-42-generic                | 2         | 0.86%   |
| 5.19.0-35-generic               | 2         | 0.86%   |
| 5.15.0-92-generic               | 2         | 0.86%   |
| 5.15.0-50-generic               | 2         | 0.86%   |
| 5.15.0-39-generic               | 2         | 0.86%   |
| 5.15.0-25-generic               | 2         | 0.86%   |
| 5.13.0-7620-generic             | 2         | 0.86%   |
| 5.13.0-7614-generic             | 2         | 0.86%   |
| 5.11.0-40-generic               | 2         | 0.86%   |
| 5.11.0-38-generic               | 2         | 0.86%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.86%   |
| 4.19.0-13-amd64                 | 2         | 0.86%   |
| 4.18.0-15-generic               | 2         | 0.86%   |
| 4.15.0-94-generic               | 2         | 0.86%   |
| 4.15.0-47-generic               | 2         | 0.86%   |
| 4.15.0-20-generic               | 2         | 0.86%   |
| 6.9.3-76060903-generic          | 1         | 0.43%   |
| 6.8.9-200.fc39.x86_64           | 1         | 0.43%   |
| 6.8.4-200.fc39.x86_64           | 1         | 0.43%   |
| 6.8.0-49-generic                | 1         | 0.43%   |
| 6.8.0-45-generic                | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 27        | 12.16%  |
| 5.15.0  | 20        | 9.01%   |
| 5.13.0  | 14        | 6.31%   |
| 5.3.0   | 11        | 4.95%   |
| 5.8.0   | 10        | 4.5%    |
| 4.15.0  | 10        | 4.5%    |
| 6.5.0   | 9         | 4.05%   |
| 6.2.0   | 9         | 4.05%   |
| 5.11.0  | 9         | 4.05%   |
| 5.16.7  | 6         | 2.7%    |
| 6.1.0   | 5         | 2.25%   |
| 5.19.0  | 5         | 2.25%   |
| 5.0.0   | 5         | 2.25%   |
| 6.8.0   | 4         | 1.8%    |
| 5.10.0  | 4         | 1.8%    |
| 4.18.0  | 4         | 1.8%    |
| 6.2.6   | 3         | 1.35%   |
| 6.1.1   | 2         | 0.9%    |
| 6.0.8   | 2         | 0.9%    |
| 4.9.60  | 2         | 0.9%    |
| 4.19.0  | 2         | 0.9%    |
| 6.9.3   | 1         | 0.45%   |
| 6.8.9   | 1         | 0.45%   |
| 6.8.4   | 1         | 0.45%   |
| 6.6.8   | 1         | 0.45%   |
| 6.6.6   | 1         | 0.45%   |
| 6.6.3   | 1         | 0.45%   |
| 6.6.21  | 1         | 0.45%   |
| 6.6.2   | 1         | 0.45%   |
| 6.6.1   | 1         | 0.45%   |
| 6.5.7   | 1         | 0.45%   |
| 6.5.5   | 1         | 0.45%   |
| 6.4.8   | 1         | 0.45%   |
| 6.4.7   | 1         | 0.45%   |
| 6.4.14  | 1         | 0.45%   |
| 6.4.12  | 1         | 0.45%   |
| 6.3.5   | 1         | 0.45%   |
| 6.3.1   | 1         | 0.45%   |
| 6.2.15  | 1         | 0.45%   |
| 6.12.4  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 13.76%  |
| 5.15    | 24        | 11.01%  |
| 5.13    | 15        | 6.88%   |
| 6.2     | 13        | 5.96%   |
| 5.8     | 12        | 5.5%    |
| 5.11    | 12        | 5.5%    |
| 6.5     | 11        | 5.05%   |
| 5.3     | 11        | 5.05%   |
| 6.1     | 10        | 4.59%   |
| 4.15    | 10        | 4.59%   |
| 5.16    | 8         | 3.67%   |
| 5.10    | 8         | 3.67%   |
| 6.6     | 6         | 2.75%   |
| 5.19    | 6         | 2.75%   |
| 6.8     | 5         | 2.29%   |
| 5.0     | 5         | 2.29%   |
| 6.4     | 4         | 1.83%   |
| 6.11    | 4         | 1.83%   |
| 4.18    | 4         | 1.83%   |
| 6.0     | 3         | 1.38%   |
| 5.14    | 3         | 1.38%   |
| 4.9     | 3         | 1.38%   |
| 6.3     | 2         | 0.92%   |
| 5.9     | 2         | 0.92%   |
| 4.19    | 2         | 0.92%   |
| 6.9     | 1         | 0.46%   |
| 6.12    | 1         | 0.46%   |
| 6.10    | 1         | 0.46%   |
| 5.7     | 1         | 0.46%   |
| 5.6     | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 186       | 95.88%  |
| i686    | 7         | 3.61%   |
| aarch64 | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 96        | 47.52%  |
| KDE5          | 26        | 12.87%  |
| XFCE          | 20        | 9.9%    |
| Unknown       | 18        | 8.91%   |
| X-Cinnamon    | 13        | 6.44%   |
| MATE          | 4         | 1.98%   |
| Pantheon      | 3         | 1.49%   |
| KDE6          | 3         | 1.49%   |
| KDE           | 3         | 1.49%   |
| Unity         | 2         | 0.99%   |
| LXQt          | 2         | 0.99%   |
| KDE4          | 2         | 0.99%   |
| sway          | 1         | 0.5%    |
| LXDE          | 1         | 0.5%    |
| i3            | 1         | 0.5%    |
| Hyprland      | 1         | 0.5%    |
| GNOME Classic | 1         | 0.5%    |
| DDE           | 1         | 0.5%    |
| Cinnamon      | 1         | 0.5%    |
| BunsenLabs    | 1         | 0.5%    |
| Budgie        | 1         | 0.5%    |
| bspwm         | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 147       | 73.87%  |
| Wayland | 45        | 22.61%  |
| Unknown | 6         | 3.02%   |
| Tty     | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 113       | 54.85%  |
| SDDM    | 28        | 13.59%  |
| GDM     | 21        | 10.19%  |
| GDM3    | 20        | 9.71%   |
| LightDM | 18        | 8.74%   |
| TDM     | 4         | 1.94%   |
| KDM     | 2         | 0.97%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 142       | 71.36%  |
| Unknown | 17        | 8.54%   |
| hr_HR   | 14        | 7.04%   |
| bs_BA   | 9         | 4.52%   |
| C       | 4         | 2.01%   |
| sr_RS   | 3         | 1.51%   |
| en_GB   | 3         | 1.51%   |
| en_AU   | 2         | 1.01%   |
| de_CH   | 2         | 1.01%   |
| it_IT   | 1         | 0.5%    |
| en_CA   | 1         | 0.5%    |
| de_DE   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 119       | 60.41%  |
| EFI  | 78        | 39.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 149       | 75.25%  |
| Btrfs   | 22        | 11.11%  |
| Overlay | 11        | 5.56%   |
| Unknown | 7         | 3.54%   |
| Tmpfs   | 6         | 3.03%   |
| Zfs     | 1         | 0.51%   |
| Xfs     | 1         | 0.51%   |
| Ext2    | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 59.61%  |
| GPT     | 67        | 33%     |
| MBR     | 15        | 7.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 90.16%  |
| Yes       | 19        | 9.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 77.66%  |
| Yes       | 44        | 22.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 45        | 23.32%  |
| ASUSTek Computer    | 42        | 21.76%  |
| Lenovo              | 34        | 17.62%  |
| Dell                | 21        | 10.88%  |
| Acer                | 13        | 6.74%   |
| Gigabyte Technology | 9         | 4.66%   |
| MSI                 | 5         | 2.59%   |
| Toshiba             | 4         | 2.07%   |
| Fujitsu             | 3         | 1.55%   |
| Pegatron            | 2         | 1.04%   |
| Medion              | 2         | 1.04%   |
| Fujitsu Siemens     | 2         | 1.04%   |
| Wistron             | 1         | 0.52%   |
| Sony                | 1         | 0.52%   |
| Packard Bell        | 1         | 0.52%   |
| Notebook            | 1         | 0.52%   |
| NEC Computers       | 1         | 0.52%   |
| Microsoft           | 1         | 0.52%   |
| HUAWEI              | 1         | 0.52%   |
| eMachines           | 1         | 0.52%   |
| ECS                 | 1         | 0.52%   |
| ASRock              | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 5         | 2.59%   |
| HP EliteBook 8460p                       | 3         | 1.55%   |
| HP EliteBook 840 G5                      | 3         | 1.55%   |
| ASUS PRIME A320M-K                       | 3         | 1.55%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF         | 2         | 1.04%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 1.04%   |
| HP Compaq 8200 Elite SFF PC              | 2         | 1.04%   |
| HP 250 G7 Notebook PC                    | 2         | 1.04%   |
| Dell OptiPlex 745                        | 2         | 1.04%   |
| Dell G3 3590                             | 2         | 1.04%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA   | 2         | 1.04%   |
| ASUS P8H61-M LX3 R2.0                    | 2         | 1.04%   |
| ASUS P5KPL-AM SE                         | 2         | 1.04%   |
| ASUS P5G41T-M LX3                        | 2         | 1.04%   |
| Wistron ProLiant ML110 G5                | 1         | 0.52%   |
| Toshiba Satellite L850-1HQ               | 1         | 0.52%   |
| Toshiba Satellite C855                   | 1         | 0.52%   |
| Toshiba Satellite C850-1GF               | 1         | 0.52%   |
| Toshiba PORTEGE Z930                     | 1         | 0.52%   |
| Sony VGN-BX41VN                          | 1         | 0.52%   |
| Pegatron VS170AA-UUZ p6244ch             | 1         | 0.52%   |
| Pegatron IPMIP-GS                        | 1         | 0.52%   |
| Packard Bell EasyNote TE69KB             | 1         | 0.52%   |
| Notebook NL5xRU                          | 1         | 0.52%   |
| NEC Computers VERSAP550 NN951700753      | 1         | 0.52%   |
| MSI Pulse GL66 12UDK                     | 1         | 0.52%   |
| MSI MS-AA1511                            | 1         | 0.52%   |
| MSI MS-7B86                              | 1         | 0.52%   |
| MSI MS-7978                              | 1         | 0.52%   |
| MSI MS-7597                              | 1         | 0.52%   |
| Microsoft Surface Pro 4                  | 1         | 0.52%   |
| Medion MS-7800                           | 1         | 0.52%   |
| Medion MS-7366                           | 1         | 0.52%   |
| Lenovo Yoga 920-13IKB 80Y7               | 1         | 0.52%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.52%   |
| Lenovo Yoga 730-13IKB 81CT               | 1         | 0.52%   |
| Lenovo Yoga 2 11 20332                   | 1         | 0.52%   |
| Lenovo V15 G4 AMN 82YU                   | 1         | 0.52%   |
| Lenovo ThinkPad X301 277418G             | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 14        | 7.25%   |
| Lenovo ThinkPad         | 12        | 6.22%   |
| Lenovo IdeaPad          | 12        | 6.22%   |
| HP Compaq               | 10        | 5.18%   |
| Acer Aspire             | 9         | 4.66%   |
| Dell Latitude           | 7         | 3.63%   |
| ASUS PRIME              | 7         | 3.63%   |
| HP ProBook              | 5         | 2.59%   |
| ASUS All                | 5         | 2.59%   |
| Lenovo Yoga             | 4         | 2.07%   |
| ASUS VivoBook           | 4         | 2.07%   |
| Toshiba Satellite       | 3         | 1.55%   |
| Lenovo Legion           | 3         | 1.55%   |
| HP ENVY                 | 3         | 1.55%   |
| HP 250                  | 3         | 1.55%   |
| Dell OptiPlex           | 3         | 1.55%   |
| ASUS ROG                | 3         | 1.55%   |
| ASUS P5G41T-M           | 3         | 1.55%   |
| HP ZBook                | 2         | 1.04%   |
| HP Pavilion             | 2         | 1.04%   |
| Fujitsu LIFEBOOK        | 2         | 1.04%   |
| Dell XPS                | 2         | 1.04%   |
| Dell Vostro             | 2         | 1.04%   |
| Dell Precision          | 2         | 1.04%   |
| Dell Inspiron           | 2         | 1.04%   |
| Dell G3                 | 2         | 1.04%   |
| ASUS TUF                | 2         | 1.04%   |
| ASUS P8H61-M            | 2         | 1.04%   |
| ASUS P5KPL-AM           | 2         | 1.04%   |
| Wistron ProLiant        | 1         | 0.52%   |
| Toshiba PORTEGE         | 1         | 0.52%   |
| Sony VGN-BX41VN         | 1         | 0.52%   |
| Pegatron VS170AA-UUZ    | 1         | 0.52%   |
| Pegatron IPMIP-GS       | 1         | 0.52%   |
| Packard Bell EasyNote   | 1         | 0.52%   |
| Notebook NL5xRU         | 1         | 0.52%   |
| NEC Computers VERSAP550 | 1         | 0.52%   |
| MSI Pulse               | 1         | 0.52%   |
| MSI MS-AA1511           | 1         | 0.52%   |
| MSI MS-7B86             | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 20        | 10.36%  |
| 2011    | 18        | 9.33%   |
| 2018    | 15        | 7.77%   |
| 2013    | 15        | 7.77%   |
| 2019    | 14        | 7.25%   |
| 2017    | 13        | 6.74%   |
| 2021    | 12        | 6.22%   |
| 2016    | 12        | 6.22%   |
| 2014    | 11        | 5.7%    |
| 2009    | 11        | 5.7%    |
| 2020    | 10        | 5.18%   |
| 2010    | 10        | 5.18%   |
| 2007    | 7         | 3.63%   |
| 2022    | 6         | 3.11%   |
| 2008    | 6         | 3.11%   |
| 2015    | 5         | 2.59%   |
| 2006    | 3         | 1.55%   |
| 2005    | 3         | 1.55%   |
| 2023    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 119       | 61.66%  |
| Desktop     | 65        | 33.68%  |
| Convertible | 6         | 3.11%   |
| All in one  | 2         | 1.04%   |
| Tablet      | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 185       | 95.36%  |
| Enabled  | 9         | 4.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 193       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 32.14%  |
| 8.01-16.0   | 33        | 16.84%  |
| 3.01-4.0    | 32        | 16.33%  |
| 16.01-24.0  | 31        | 15.82%  |
| 1.01-2.0    | 16        | 8.16%   |
| 32.01-64.0  | 7         | 3.57%   |
| 2.01-3.0    | 7         | 3.57%   |
| 64.01-256.0 | 4         | 2.04%   |
| 0.51-1.0    | 2         | 1.02%   |
| 0.01-0.5    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 70        | 33.02%  |
| 2.01-3.0  | 61        | 28.77%  |
| 3.01-4.0  | 28        | 13.21%  |
| 4.01-8.0  | 26        | 12.26%  |
| 0.51-1.0  | 16        | 7.55%   |
| 8.01-16.0 | 8         | 3.77%   |
| 0.01-0.5  | 3         | 1.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 69.35%  |
| 2      | 49        | 24.62%  |
| 3      | 7         | 3.52%   |
| 5      | 2         | 1.01%   |
| 4      | 2         | 1.01%   |
| 0      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 59.18%  |
| Yes       | 80        | 40.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 85.13%  |
| No        | 29        | 14.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 76.17%  |
| No        | 46        | 23.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 52.58%  |
| No        | 92        | 47.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 193       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 67        | 33.5%   |
| Banja Luka        | 30        | 15%     |
| Tuzla             | 11        | 5.5%    |
| Doboj             | 8         | 4%      |
| Teslic            | 5         | 2.5%    |
| Gracanica         | 5         | 2.5%    |
| Zenica            | 4         | 2%      |
| Prijedor          | 4         | 2%      |
| Srebrenik         | 3         | 1.5%    |
| Prnjavor          | 3         | 1.5%    |
| Novi Travnik      | 3         | 1.5%    |
| Mostar            | 3         | 1.5%    |
| Gradacac          | 3         | 1.5%    |
| Cazin             | 3         | 1.5%    |
| Brcko             | 3         | 1.5%    |
| Bijeljina         | 3         | 1.5%    |
| Zepce             | 2         | 1%      |
| Vitez             | 2         | 1%      |
| Trebinje          | 2         | 1%      |
| Pale              | 2         | 1%      |
| Maglaj            | 2         | 1%      |
| Lukavac           | 2         | 1%      |
| Banovici          | 2         | 1%      |
| Zvornik           | 1         | 0.5%    |
| Zivinice          | 1         | 0.5%    |
| Zavidovici        | 1         | 0.5%    |
| Visoko            | 1         | 0.5%    |
| Velika KladuÅ¡a | 1         | 0.5%    |
| Tarcin            | 1         | 0.5%    |
| Stjepan-Polje     | 1         | 0.5%    |
| Solina            | 1         | 0.5%    |
| Sokolac           | 1         | 0.5%    |
| Siroki Brijeg     | 1         | 0.5%    |
| Posusje           | 1         | 0.5%    |
| Orahovica Donja   | 1         | 0.5%    |
| Nova Topola       | 1         | 0.5%    |
| Nevesinje         | 1         | 0.5%    |
| Mrkonjic Grad     | 1         | 0.5%    |
| Lukavica          | 1         | 0.5%    |
| Ljubuski          | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 41        | 64     | 16.4%   |
| WDC                         | 36        | 51     | 14.4%   |
| Kingston                    | 33        | 43     | 13.2%   |
| Seagate                     | 29        | 37     | 11.6%   |
| Toshiba                     | 20        | 23     | 8%      |
| Hitachi                     | 17        | 18     | 6.8%    |
| SK hynix                    | 12        | 16     | 4.8%    |
| SanDisk                     | 11        | 13     | 4.4%    |
| Intel                       | 7         | 7      | 2.8%    |
| Unknown                     | 6         | 6      | 2.4%    |
| Micron Technology           | 5         | 9      | 2%      |
| KIOXIA                      | 4         | 4      | 1.6%    |
| China                       | 4         | 6      | 1.6%    |
| A-DATA Technology           | 3         | 3      | 1.2%    |
| Gigabyte Technology         | 2         | 2      | 0.8%    |
| Crucial                     | 2         | 3      | 0.8%    |
| Vaseky                      | 1         | 1      | 0.4%    |
| Union Memory                | 1         | 1      | 0.4%    |
| Transcend                   | 1         | 2      | 0.4%    |
| Team                        | 1         | 1      | 0.4%    |
| SPCC                        | 1         | 1      | 0.4%    |
| Phison                      | 1         | 1      | 0.4%    |
| Patriot                     | 1         | 1      | 0.4%    |
| ORGE                        | 1         | 1      | 0.4%    |
| OCZ                         | 1         | 2      | 0.4%    |
| Maxtor                      | 1         | 1      | 0.4%    |
| LITEON                      | 1         | 1      | 0.4%    |
| Kingston Technology Company | 1         | 1      | 0.4%    |
| Intenso                     | 1         | 1      | 0.4%    |
| HGST                        | 1         | 1      | 0.4%    |
| GOODRAM                     | 1         | 1      | 0.4%    |
| Fujitsu                     | 1         | 1      | 0.4%    |
| ASMT                        | 1         | 1      | 0.4%    |
| Unknown                     | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD                     | 7         | 2.62%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.87%   |
| Seagate ST500DM002-1BD142 500GB                     | 5         | 1.87%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 1.87%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 1.12%   |
| Samsung SSD 980 500GB                               | 3         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3         | 1.12%   |
| Kingston SHFS37A120G 120GB SSD                      | 3         | 1.12%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 1.12%   |
| Hitachi HDS721050CLA362 500GB                       | 3         | 1.12%   |
| WDC WD800JD-00MSA1 80GB                             | 2         | 0.75%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2         | 0.75%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 2         | 0.75%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.75%   |
| Unknown MMC Card  32GB                              | 2         | 0.75%   |
| Toshiba HDWD120 2TB                                 | 2         | 0.75%   |
| Toshiba DT01ACA100 1TB                              | 2         | 0.75%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.75%   |
| Seagate ST3500413AS 500GB                           | 2         | 0.75%   |
| Seagate ST250LT021-1AF14C 250GB                     | 2         | 0.75%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.75%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.75%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.75%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.75%   |
| Samsung MZ7TD256HAFV-000L9 256GB SSD                | 2         | 0.75%   |
| Micron MTFDHBA256TCK-1AS1AABHA 256GB                | 2         | 0.75%   |
| Kingston SUV500120G 120GB SSD                       | 2         | 0.75%   |
| Kingston SUV400S37240G 240GB SSD                    | 2         | 0.75%   |
| Kingston SHFS37A240G 240GB SSD                      | 2         | 0.75%   |
| Hitachi HTS723232A7A364 320GB                       | 2         | 0.75%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 0.75%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                    | 2         | 0.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.37%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                    | 1         | 0.37%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                    | 1         | 0.37%   |
| WDC WD800JD-75MSA3 80GB                             | 1         | 0.37%   |
| WDC WD800JD-60LSA5 80GB                             | 1         | 0.37%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 45     | 30.39%  |
| Seagate             | 29        | 37     | 28.43%  |
| Hitachi             | 17        | 18     | 16.67%  |
| Toshiba             | 16        | 17     | 15.69%  |
| Samsung Electronics | 3         | 3      | 2.94%   |
| Unknown             | 2         | 2      | 1.96%   |
| Maxtor              | 1         | 1      | 0.98%   |
| HGST                | 1         | 1      | 0.98%   |
| Fujitsu             | 1         | 1      | 0.98%   |
| ASMT                | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 27        | 33     | 32.14%  |
| Samsung Electronics | 22        | 27     | 26.19%  |
| WDC                 | 4         | 4      | 4.76%   |
| SanDisk             | 4         | 5      | 4.76%   |
| Intel               | 4         | 4      | 4.76%   |
| China               | 4         | 6      | 4.76%   |
| A-DATA Technology   | 3         | 3      | 3.57%   |
| SK hynix            | 2         | 4      | 2.38%   |
| Gigabyte Technology | 2         | 2      | 2.38%   |
| Vaseky              | 1         | 1      | 1.19%   |
| Transcend           | 1         | 2      | 1.19%   |
| Toshiba             | 1         | 1      | 1.19%   |
| Team                | 1         | 1      | 1.19%   |
| SPCC                | 1         | 1      | 1.19%   |
| Patriot             | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 2      | 1.19%   |
| Micron Technology   | 1         | 1      | 1.19%   |
| LITEON              | 1         | 1      | 1.19%   |
| Intenso             | 1         | 1      | 1.19%   |
| GOODRAM             | 1         | 1      | 1.19%   |
| Unknown             | 1         | 1      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 126    | 38.89%  |
| SSD     | 80        | 102    | 34.19%  |
| NVMe    | 57        | 91     | 24.36%  |
| MMC     | 5         | 5      | 2.14%   |
| Unknown | 1         | 1      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 225    | 67.32%  |
| NVMe | 57        | 90     | 27.8%   |
| SAS  | 5         | 5      | 2.44%   |
| MMC  | 5         | 5      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 189    | 79.5%   |
| 0.51-1.0   | 25        | 27     | 15.53%  |
| 1.01-2.0   | 5         | 7      | 3.11%   |
| 3.01-4.0   | 1         | 2      | 0.62%   |
| 2.01-3.0   | 1         | 2      | 0.62%   |
| 4.01-10.0  | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 31.86%  |
| 251-500        | 52        | 25.49%  |
| 501-1000       | 21        | 10.29%  |
| 51-100         | 16        | 7.84%   |
| 21-50          | 14        | 6.86%   |
| 1-20           | 13        | 6.37%   |
| Unknown        | 7         | 3.43%   |
| 1001-2000      | 6         | 2.94%   |
| More than 3000 | 5         | 2.45%   |
| 2001-3000      | 5         | 2.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 37.04%  |
| 21-50          | 56        | 25.93%  |
| 51-100         | 28        | 12.96%  |
| 101-250        | 21        | 9.72%   |
| 501-1000       | 11        | 5.09%   |
| 251-500        | 8         | 3.7%    |
| Unknown        | 7         | 3.24%   |
| 1001-2000      | 3         | 1.39%   |
| More than 3000 | 1         | 0.46%   |
| 2001-3000      | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 5.26%   |
| WDC WD5000AVDS-73U7B1 500GB                                     | 1         | 1      | 5.26%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1         | 1      | 5.26%   |
| WDC WD3200AAJS-00B4A0 320GB                                     | 1         | 1      | 5.26%   |
| WDC WD1600AAJS-60WAA0 160GB                                     | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 5.26%   |
| Seagate ST3120813AS 120GB                                       | 1         | 1      | 5.26%   |
| Seagate ST3000DM001-1CH166 3TB                                  | 1         | 2      | 5.26%   |
| Seagate ST250LT021-1AF14C 250GB                                 | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 980 500GB                               | 1         | 1      | 5.26%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 5.26%   |
| Samsung Electronics MZVKW512HMJP-000H1 512GB                    | 1         | 1      | 5.26%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD                   | 1         | 1      | 5.26%   |
| Samsung Electronics HD322HJ 320GB                               | 1         | 1      | 5.26%   |
| Hitachi HTS542525K9SA00 250GB                                   | 1         | 2      | 5.26%   |
| Hitachi HDS721050CLA362 500GB                                   | 1         | 1      | 5.26%   |
| Crucial CT500P1SSD8 500GB                                       | 1         | 1      | 5.26%   |
| China SSD 128GB                                                 | 1         | 1      | 5.26%   |
| China SATA SSD 240GB                                            | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 27.78%  |
| Seagate             | 4         | 5      | 22.22%  |
| Samsung Electronics | 4         | 5      | 22.22%  |
| Hitachi             | 2         | 3      | 11.11%  |
| China               | 2         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 4         | 5      | 36.36%  |
| Hitachi             | 2         | 3      | 18.18%  |
| Samsung Electronics | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 13     | 53.33%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 3         | 4      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 210    | 63.41%  |
| Works    | 60        | 93     | 29.27%  |
| Malfunc  | 14        | 21     | 6.83%   |
| Failed   | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 137       | 59.83%  |
| AMD                          | 27        | 11.79%  |
| Samsung Electronics          | 17        | 7.42%   |
| SK hynix                     | 10        | 4.37%   |
| SanDisk                      | 8         | 3.49%   |
| Kingston Technology Company  | 7         | 3.06%   |
| Nvidia                       | 6         | 2.62%   |
| Micron Technology            | 4         | 1.75%   |
| KIOXIA                       | 4         | 1.75%   |
| Toshiba America Info Systems | 3         | 1.31%   |
| Micron/Crucial Technology    | 2         | 0.87%   |
| Union Memory (Shenzhen)      | 1         | 0.44%   |
| Phison Electronics           | 1         | 0.44%   |
| Marvell Technology Group     | 1         | 0.44%   |
| JMicron Technology           | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 8.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 4.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 4.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9         | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6         | 2.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.48%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.11%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 1.11%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 3         | 1.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 1.11%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.11%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 3         | 1.11%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 2         | 0.74%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 2         | 0.74%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 2         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.74%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2         | 0.74%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 2         | 0.74%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 2         | 0.74%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                          | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 127       | 53.36%  |
| NVMe | 57        | 23.95%  |
| IDE  | 35        | 14.71%  |
| RAID | 19        | 7.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 79.27%  |
| AMD    | 39        | 20.21%  |
| ARM    | 1         | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 2.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.07%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 2.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.55%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.55%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 1.55%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.04%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 1.04%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.04%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 1.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.04%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.04%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 1.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.04%   |
| Intel Celeron CPU 430 @ 1.80GHz               | 2         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.04%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 2         | 1.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.04%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.04%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.52%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.52%   |
| Intel Xeon CPU X3210 @ 2.13GHz                | 1         | 0.52%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 54        | 27.98%  |
| Intel Core i7           | 33        | 17.1%   |
| Other                   | 15        | 7.77%   |
| Intel Core i3           | 12        | 6.22%   |
| Intel Celeron           | 9         | 4.66%   |
| AMD Ryzen 5             | 9         | 4.66%   |
| Intel Core 2 Duo        | 8         | 4.15%   |
| Intel Pentium Dual-Core | 7         | 3.63%   |
| Intel Pentium           | 4         | 2.07%   |
| AMD Ryzen 7             | 4         | 2.07%   |
| AMD Ryzen 3             | 4         | 2.07%   |
| AMD E1                  | 4         | 2.07%   |
| Intel Xeon              | 3         | 1.55%   |
| Intel Core 2 Quad       | 2         | 1.04%   |
| Intel Core 2            | 2         | 1.04%   |
| AMD Ryzen 9             | 2         | 1.04%   |
| AMD Ryzen 5 PRO         | 2         | 1.04%   |
| AMD Athlon 64 X2        | 2         | 1.04%   |
| AMD A6                  | 2         | 1.04%   |
| Intel Pentium M         | 1         | 0.52%   |
| Intel Pentium Dual      | 1         | 0.52%   |
| Intel Pentium 4         | 1         | 0.52%   |
| Intel Celeron D         | 1         | 0.52%   |
| Intel Atom              | 1         | 0.52%   |
| AMD Turion 64 Mobile    | 1         | 0.52%   |
| AMD Phenom              | 1         | 0.52%   |
| AMD FX                  | 1         | 0.52%   |
| AMD E2                  | 1         | 0.52%   |
| AMD C-60                | 1         | 0.52%   |
| AMD Athlon X4           | 1         | 0.52%   |
| AMD Athlon II X3        | 1         | 0.52%   |
| AMD Athlon 64           | 1         | 0.52%   |
| AMD A8                  | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 43.52%  |
| 4      | 71        | 36.79%  |
| 6      | 12        | 6.22%   |
| 8      | 8         | 4.15%   |
| 1      | 7         | 3.63%   |
| 14     | 5         | 2.59%   |
| 3      | 3         | 1.55%   |
| 12     | 2         | 1.04%   |
| 10     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 99.48%  |
| 2      | 1         | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 117       | 60.31%  |
| 1      | 77        | 39.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 186       | 96.37%  |
| Unknown        | 6         | 3.11%   |
| 32-bit         | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 38.19%  |
| 0x206a7    | 14        | 7.04%   |
| 0x306a9    | 12        | 6.03%   |
| 0x306c3    | 9         | 4.52%   |
| 0x1067a    | 9         | 4.52%   |
| 0x406e3    | 6         | 3.02%   |
| 0x806ea    | 5         | 2.51%   |
| 0x806ec    | 4         | 2.01%   |
| 0x906a3    | 3         | 1.51%   |
| 0x806c1    | 3         | 1.51%   |
| 0x506e3    | 3         | 1.51%   |
| 0x40651    | 3         | 1.51%   |
| 0x10676    | 3         | 1.51%   |
| 0x806eb    | 2         | 1.01%   |
| 0x806e9    | 2         | 1.01%   |
| 0x506c9    | 2         | 1.01%   |
| 0x30678    | 2         | 1.01%   |
| 0x20655    | 2         | 1.01%   |
| 0x08600106 | 2         | 1.01%   |
| 0x08108109 | 2         | 1.01%   |
| 0x0700010f | 2         | 1.01%   |
| 0x05000119 | 2         | 1.01%   |
| 0xf65      | 1         | 0.5%    |
| 0xf43      | 1         | 0.5%    |
| 0xa0653    | 1         | 0.5%    |
| 0xa0652    | 1         | 0.5%    |
| 0x906ec    | 1         | 0.5%    |
| 0x906eb    | 1         | 0.5%    |
| 0x906ea    | 1         | 0.5%    |
| 0x906e9    | 1         | 0.5%    |
| 0x706e5    | 1         | 0.5%    |
| 0x6fd      | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x6fa      | 1         | 0.5%    |
| 0x6f6      | 1         | 0.5%    |
| 0x6f2      | 1         | 0.5%    |
| 0x6d8      | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x406c3    | 1         | 0.5%    |
| 0x106e5    | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 16.06%  |
| SandyBridge      | 20        | 10.36%  |
| IvyBridge        | 18        | 9.33%   |
| Haswell          | 16        | 8.29%   |
| Penryn           | 14        | 7.25%   |
| Skylake          | 10        | 5.18%   |
| Core             | 9         | 4.66%   |
| Unknown          | 8         | 4.15%   |
| Zen+             | 7         | 3.63%   |
| Westmere         | 6         | 3.11%   |
| TigerLake        | 6         | 3.11%   |
| Zen 2            | 5         | 2.59%   |
| Silvermont       | 5         | 2.59%   |
| Alderlake Hybrid | 5         | 2.59%   |
| K8 Hammer        | 4         | 2.07%   |
| Zen              | 3         | 1.55%   |
| Jaguar           | 3         | 1.55%   |
| Zen 3            | 2         | 1.04%   |
| NetBurst         | 2         | 1.04%   |
| K10              | 2         | 1.04%   |
| IceLake          | 2         | 1.04%   |
| Goldmont         | 2         | 1.04%   |
| Excavator        | 2         | 1.04%   |
| CometLake        | 2         | 1.04%   |
| Bobcat           | 2         | 1.04%   |
| Steamroller      | 1         | 0.52%   |
| Puma             | 1         | 0.52%   |
| Piledriver       | 1         | 0.52%   |
| P6               | 1         | 0.52%   |
| Nehalem          | 1         | 0.52%   |
| K10 Llano        | 1         | 0.52%   |
| Bulldozer        | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 110       | 47.01%  |
| Nvidia                     | 66        | 28.21%  |
| AMD                        | 57        | 24.36%  |
| Matrox Electronics Systems | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.17%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.08%   |
| Intel HD Graphics 620                                                                    | 5         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.08%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.67%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.67%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.25%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.25%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.25%   |
| AMD Lucienne                                                                             | 3         | 1.25%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 1.25%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.83%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.83%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.83%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 2         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.83%   |
| Intel HD Graphics 500                                                                    | 2         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.83%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.83%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 36.41%  |
| 1 x AMD        | 47        | 24.1%   |
| 1 x Nvidia     | 33        | 16.92%  |
| Intel + Nvidia | 32        | 16.41%  |
| Intel + AMD    | 4         | 2.05%   |
| 2 x AMD        | 3         | 1.54%   |
| AMD + Nvidia   | 2         | 1.03%   |
| Other          | 1         | 0.51%   |
| 3 x AMD        | 1         | 0.51%   |
| 1 x Matrox     | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 79.08%  |
| Proprietary | 34        | 17.35%  |
| Unknown     | 7         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 54.77%  |
| 1.01-2.0   | 27        | 13.57%  |
| 0.01-0.5   | 26        | 13.07%  |
| 0.51-1.0   | 18        | 9.05%   |
| 3.01-4.0   | 9         | 4.52%   |
| 7.01-8.0   | 4         | 2.01%   |
| 5.01-6.0   | 3         | 1.51%   |
| 2.01-3.0   | 2         | 1.01%   |
| 8.01-16.0  | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 14.78%  |
| Samsung Electronics     | 24        | 11.82%  |
| LG Display              | 24        | 11.82%  |
| BOE                     | 21        | 10.34%  |
| Chimei Innolux          | 14        | 6.9%    |
| Goldstar                | 10        | 4.93%   |
| Dell                    | 10        | 4.93%   |
| Philips                 | 8         | 3.94%   |
| AOC                     | 8         | 3.94%   |
| Sharp                   | 6         | 2.96%   |
| Hewlett-Packard         | 4         | 1.97%   |
| Chi Mei Optoelectronics | 4         | 1.97%   |
| Ancor Communications    | 4         | 1.97%   |
| Sony                    | 3         | 1.48%   |
| InfoVision              | 3         | 1.48%   |
| Fujitsu Siemens         | 3         | 1.48%   |
| ASUSTek Computer        | 3         | 1.48%   |
| Unknown                 | 2         | 0.99%   |
| PANDA                   | 2         | 0.99%   |
| LG Philips              | 2         | 0.99%   |
| IBM                     | 2         | 0.99%   |
| BenQ                    | 2         | 0.99%   |
| Acer                    | 2         | 0.99%   |
| ViewSonic               | 1         | 0.49%   |
| Vestel Elektronik       | 1         | 0.49%   |
| NEC Computers           | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| Mi                      | 1         | 0.49%   |
| LTM                     | 1         | 0.49%   |
| LGD                     | 1         | 0.49%   |
| Lenovo                  | 1         | 0.49%   |
| Eizo                    | 1         | 0.49%   |
| CTV                     | 1         | 0.49%   |
| CSO                     | 1         | 0.49%   |
| Belinea                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 4         | 1.9%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 3         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 2         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 2         | 0.95%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 2         | 0.95%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 2         | 0.95%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 2         | 0.95%   |
| IBM C170 CRT IBM1A51 1280x1024 310x230mm 15.2-inch                     | 2         | 0.95%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.95%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.95%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                  | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch         | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.95%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                          | 2         | 0.95%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 2         | 0.95%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                     | 2         | 0.95%   |
| ViewSonic VA702 VSC1C1C 1280x1024 338x270mm 17.0-inch                  | 1         | 0.48%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 1         | 0.48%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1         | 0.48%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B_101920 1280x1024                 | 1         | 0.48%   |
| Sony TV SNY6604 1920x1080                                              | 1         | 0.48%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.48%   |
| Sony TV *00 SNY4904 3840x2160                                          | 1         | 0.48%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                | 1         | 0.48%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.48%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.48%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.48%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch                | 1         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                       | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM03E2 1680x1050 433x271mm 20.1-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0169 1280x1024 380x300mm 19.1-inch   | 1         | 0.48%   |
| Samsung Electronics SAMTRON 50X/V STN0011 1024x768 304x228mm 15.0-inch | 1         | 0.48%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1         | 0.48%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch      | 1         | 0.48%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 46.7%   |
| 1366x768 (WXGA)    | 34        | 17.26%  |
| 1600x900 (HD+)     | 16        | 8.12%   |
| 1280x1024 (SXGA)   | 14        | 7.11%   |
| 3840x2160 (4K)     | 8         | 4.06%   |
| 1680x1050 (WSXGA+) | 6         | 3.05%   |
| 1440x900 (WXGA+)   | 6         | 3.05%   |
| 2560x1440 (QHD)    | 5         | 2.54%   |
| 1920x1200 (WUXGA)  | 4         | 2.03%   |
| 3440x1440          | 2         | 1.02%   |
| 2560x1600          | 2         | 1.02%   |
| 1280x800 (WXGA)    | 2         | 1.02%   |
| 3200x1800 (QHD+)   | 1         | 0.51%   |
| 3200x1080          | 1         | 0.51%   |
| 2736x1824          | 1         | 0.51%   |
| 1360x768           | 1         | 0.51%   |
| 1024x768 (XGA)     | 1         | 0.51%   |
| Unknown            | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 30.43%  |
| 14      | 20        | 9.66%   |
| 17      | 19        | 9.18%   |
| 13      | 15        | 7.25%   |
| 21      | 13        | 6.28%   |
| 23      | 12        | 5.8%    |
| Unknown | 11        | 5.31%   |
| 24      | 8         | 3.86%   |
| 27      | 6         | 2.9%    |
| 19      | 6         | 2.9%    |
| 18      | 5         | 2.42%   |
| 31      | 4         | 1.93%   |
| 22      | 4         | 1.93%   |
| 72      | 3         | 1.45%   |
| 12      | 3         | 1.45%   |
| 11      | 3         | 1.45%   |
| 84      | 2         | 0.97%   |
| 34      | 2         | 0.97%   |
| 20      | 2         | 0.97%   |
| 16      | 2         | 0.97%   |
| 54      | 1         | 0.48%   |
| 40      | 1         | 0.48%   |
| 33      | 1         | 0.48%   |
| 26      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 49.02%  |
| 401-500     | 26        | 12.75%  |
| 501-600     | 25        | 12.25%  |
| 351-400     | 16        | 7.84%   |
| 201-300     | 12        | 5.88%   |
| Unknown     | 11        | 5.39%   |
| 1501-2000   | 5         | 2.45%   |
| 601-700     | 4         | 1.96%   |
| 701-800     | 3         | 1.47%   |
| 801-900     | 1         | 0.49%   |
| 1001-1500   | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 75.81%  |
| 16/10   | 18        | 9.68%   |
| 5/4     | 11        | 5.91%   |
| Unknown | 9         | 4.84%   |
| 4/3     | 3         | 1.61%   |
| 3/2     | 2         | 1.08%   |
| 21/9    | 2         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 28.92%  |
| 81-90          | 29        | 14.22%  |
| 201-250        | 29        | 14.22%  |
| 151-200        | 11        | 5.39%   |
| 141-150        | 11        | 5.39%   |
| Unknown        | 11        | 5.39%   |
| 121-130        | 9         | 4.41%   |
| 71-80          | 7         | 3.43%   |
| 351-500        | 7         | 3.43%   |
| More than 1000 | 6         | 2.94%   |
| 301-350        | 6         | 2.94%   |
| 111-120        | 5         | 2.45%   |
| 251-300        | 4         | 1.96%   |
| 51-60          | 3         | 1.47%   |
| 131-140        | 3         | 1.47%   |
| 61-70          | 2         | 0.98%   |
| 501-1000       | 1         | 0.49%   |
| 91-100         | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 32.66%  |
| 51-100        | 55        | 27.64%  |
| 101-120       | 50        | 25.13%  |
| Unknown       | 11        | 5.53%   |
| 161-240       | 9         | 4.52%   |
| 1-50          | 5         | 2.51%   |
| More than 240 | 4         | 2.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 159       | 80.71%  |
| 2     | 30        | 15.23%  |
| 0     | 6         | 3.05%   |
| 3     | 2         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 89        | 31.67%  |
| Intel                                  | 80        | 28.47%  |
| Qualcomm Atheros                       | 40        | 14.23%  |
| Broadcom                               | 12        | 4.27%   |
| Ralink Technology                      | 9         | 3.2%    |
| Qualcomm Atheros Communications        | 7         | 2.49%   |
| TP-Link                                | 6         | 2.14%   |
| Ralink                                 | 4         | 1.42%   |
| Nvidia                                 | 4         | 1.42%   |
| MediaTek                               | 4         | 1.42%   |
| Marvell Technology Group               | 4         | 1.42%   |
| Hewlett-Packard                        | 3         | 1.07%   |
| Broadcom Limited                       | 3         | 1.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.71%   |
| Sierra Wireless                        | 2         | 0.71%   |
| ICS Advent                             | 2         | 0.71%   |
| ASIX Electronics                       | 2         | 0.71%   |
| Xiaomi                                 | 1         | 0.36%   |
| Toshiba                                | 1         | 0.36%   |
| Qualcomm                               | 1         | 0.36%   |
| Mercucys                               | 1         | 0.36%   |
| HTC (High Tech Computer)               | 1         | 0.36%   |
| Ericsson Business Mobile Networks      | 1         | 0.36%   |
| D-Link                                 | 1         | 0.36%   |
| Aquantia                               | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 65        | 19.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 4.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.38%   |
| Qualcomm Atheros AR9271 802.11n                                        | 7         | 2.08%   |
| Intel Wireless 8265 / 8275                                             | 7         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.79%   |
| Intel Wireless 8260                                                    | 6         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.19%   |
| Intel Wireless 7260                                                    | 4         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.19%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 1.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.89%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.89%   |
| Sony Ericsson Mobile AB D2005                                          | 2         | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.6%    |
| Realtek 802.11ac NIC                                                   | 2         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 38.06%  |
| Qualcomm Atheros                | 32        | 20.65%  |
| Realtek Semiconductor           | 23        | 14.84%  |
| Ralink Technology               | 9         | 5.81%   |
| Broadcom                        | 8         | 5.16%   |
| Qualcomm Atheros Communications | 7         | 4.52%   |
| TP-Link                         | 5         | 3.23%   |
| Ralink                          | 4         | 2.58%   |
| MediaTek                        | 3         | 1.94%   |
| Sierra Wireless                 | 2         | 1.29%   |
| Mercucys                        | 1         | 0.65%   |
| Marvell Technology Group        | 1         | 0.65%   |
| D-Link                          | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.13%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 4.49%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.49%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.85%   |
| Intel Wireless 8260                                            | 6         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 3.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.56%   |
| Intel Wireless 7260                                            | 4         | 2.56%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 1.92%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.92%   |
| Realtek 802.11ac NIC                                           | 2         | 1.28%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.28%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.28%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.64%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 0.64%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.64%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 81        | 46.55%  |
| Intel                                  | 52        | 29.89%  |
| Qualcomm Atheros                       | 13        | 7.47%   |
| Broadcom                               | 5         | 2.87%   |
| Nvidia                                 | 4         | 2.3%    |
| Marvell Technology Group               | 3         | 1.72%   |
| Broadcom Limited                       | 3         | 1.72%   |
| Sony Ericsson Mobile Communications AB | 2         | 1.15%   |
| ICS Advent                             | 2         | 1.15%   |
| ASIX Electronics                       | 2         | 1.15%   |
| Xiaomi                                 | 1         | 0.57%   |
| TP-Link                                | 1         | 0.57%   |
| Qualcomm                               | 1         | 0.57%   |
| MediaTek                               | 1         | 0.57%   |
| HTC (High Tech Computer)               | 1         | 0.57%   |
| Hewlett-Packard                        | 1         | 0.57%   |
| Aquantia                               | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 65        | 37.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 8.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 5.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.29%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 2.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.29%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 2.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.71%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.71%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.71%   |
| Sony Ericsson Mobile AB D2005                                          | 2         | 1.14%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 1.14%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.14%   |
| Intel Ethernet Connection I217-V                                       | 2         | 1.14%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 2         | 1.14%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.57%   |
| Qualcomm POCO F3                                                       | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.57%   |
| Nvidia MCP73 Ethernet                                                  | 1         | 0.57%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 0.57%   |
| Nvidia CK8S Ethernet Controller                                        | 1         | 0.57%   |
| Nvidia CK804 Ethernet Controller                                       | 1         | 0.57%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.57%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.57%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.57%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.57%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 52.2%   |
| WiFi     | 147       | 46.23%  |
| Modem    | 5         | 1.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 128       | 64.32%  |
| Ethernet | 71        | 35.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 50.26%  |
| 1     | 88        | 45.13%  |
| 0     | 8         | 4.1%    |
| 3     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 182       | 93.81%  |
| Yes  | 12        | 6.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 36.27%  |
| Qualcomm Atheros Communications | 15        | 14.71%  |
| Realtek Semiconductor           | 11        | 10.78%  |
| IMC Networks                    | 8         | 7.84%   |
| Broadcom                        | 6         | 5.88%   |
| Lite-On Technology              | 5         | 4.9%    |
| Ralink                          | 3         | 2.94%   |
| Hewlett-Packard                 | 3         | 2.94%   |
| Foxconn / Hon Hai               | 3         | 2.94%   |
| Cambridge Silicon Radio         | 3         | 2.94%   |
| Toshiba                         | 2         | 1.96%   |
| Realtek                         | 1         | 0.98%   |
| Marvell Semiconductor           | 1         | 0.98%   |
| Integrated System Solution      | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |
| Askey Computer                  | 1         | 0.98%   |
| Alps Electric                   | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 14.71%  |
| Intel AX201 Bluetooth                               | 8         | 7.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 6.86%   |
| Realtek Bluetooth Radio                             | 4         | 3.92%   |
| Intel AX211 Bluetooth                               | 4         | 3.92%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.92%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 2.94%   |
| Ralink RT3290 Bluetooth                             | 3         | 2.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 2.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.94%   |
| Intel AX200 Bluetooth                               | 3         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.96%   |
| IMC Networks Bluetooth Device                       | 2         | 1.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.96%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.98%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.98%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.98%   |
| Realtek Bluetooth Radio                             | 1         | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.98%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.98%   |
| Intel AX210 Bluetooth                               | 1         | 0.98%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.98%   |
| IMC Networks Wireless_Device                        | 1         | 0.98%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.98%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.98%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.98%   |
| Broadcom HP Portable Valentine                      | 1         | 0.98%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.98%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 147       | 57.2%   |
| AMD                   | 54        | 21.01%  |
| Nvidia                | 43        | 16.73%  |
| Logitech              | 3         | 1.17%   |
| Creative Labs         | 2         | 0.78%   |
| C-Media Electronics   | 2         | 0.78%   |
| VIA Technologies      | 1         | 0.39%   |
| Texas Instruments     | 1         | 0.39%   |
| Realtek Semiconductor | 1         | 0.39%   |
| JMTek                 | 1         | 0.39%   |
| Focusrite-Novation    | 1         | 0.39%   |
| DSEA A/S              | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 7.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 7.05%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 18        | 6.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 5.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.02%   |
| AMD FCH Azalia Controller                                                  | 9         | 3.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 2.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.01%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.68%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.34%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4         | 1.34%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.01%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.01%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.67%   |
| Nvidia GK110 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 23.76%  |
| SK hynix            | 21        | 20.79%  |
| Kingston            | 21        | 20.79%  |
| Micron Technology   | 14        | 13.86%  |
| Unknown             | 7         | 6.93%   |
| A-DATA Technology   | 4         | 3.96%   |
| Crucial             | 3         | 2.97%   |
| Corsair             | 3         | 2.97%   |
| Nanya Technology    | 1         | 0.99%   |
| INNOVATION PC       | 1         | 0.99%   |
| G.Skill             | 1         | 0.99%   |
| Apacer              | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.75%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.75%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 1.75%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2         | 1.75%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 2         | 1.75%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2         | 1.75%   |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s    | 2         | 1.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1         | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                  | 1         | 0.88%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 1         | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                   | 1         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                | 1         | 0.88%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2133MT/s             | 1         | 0.88%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM SDRAM 2048MT/s     | 1         | 0.88%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB DIMM SDRAM 2048MT/s        | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.88%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s            | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s         | 1         | 0.88%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s        | 1         | 0.88%   |
| SK hynix RAM HMAA4GS7AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 0.88%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 35        | 39.77%  |
| DDR3    | 35        | 39.77%  |
| DDR2    | 5         | 5.68%   |
| DDR5    | 3         | 3.41%   |
| SDRAM   | 2         | 2.27%   |
| LPDDR4  | 2         | 2.27%   |
| LPDDR3  | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| LPDDR5  | 1         | 1.14%   |
| DDR     | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 59.3%   |
| DIMM         | 29        | 33.72%  |
| Row Of Chips | 5         | 5.81%   |
| Unknown      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 36.36%  |
| 4096  | 34        | 34.34%  |
| 2048  | 13        | 13.13%  |
| 16384 | 8         | 8.08%   |
| 1024  | 5         | 5.05%   |
| 32768 | 3         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 23        | 24.21%  |
| 3200  | 12        | 12.63%  |
| 2667  | 10        | 10.53%  |
| 1333  | 8         | 8.42%   |
| 2133  | 7         | 7.37%   |
| 2400  | 5         | 5.26%   |
| 800   | 4         | 4.21%   |
| 4800  | 3         | 3.16%   |
| 1867  | 3         | 3.16%   |
| 1334  | 3         | 3.16%   |
| 3266  | 2         | 2.11%   |
| 1866  | 2         | 2.11%   |
| 6400  | 1         | 1.05%   |
| 4266  | 1         | 1.05%   |
| 4199  | 1         | 1.05%   |
| 3733  | 1         | 1.05%   |
| 3400  | 1         | 1.05%   |
| 2800  | 1         | 1.05%   |
| 2048  | 1         | 1.05%   |
| 2000  | 1         | 1.05%   |
| 1800  | 1         | 1.05%   |
| 1067  | 1         | 1.05%   |
| 1066  | 1         | 1.05%   |
| 667   | 1         | 1.05%   |
| 333   | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 33.33%  |
| HP LaserJet 1000                           | 1         | 33.33%  |
| HP DeskJet F2100 Printer series            | 1         | 33.33%  |

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
| Chicony Electronics                    | 30        | 24.39%  |
| Realtek Semiconductor                  | 12        | 9.76%   |
| IMC Networks                           | 12        | 9.76%   |
| Bison Electronics                      | 10        | 8.13%   |
| Sunplus Innovation Technology          | 8         | 6.5%    |
| Microdia                               | 8         | 6.5%    |
| Quanta                                 | 7         | 5.69%   |
| Logitech                               | 5         | 4.07%   |
| Lite-On Technology                     | 5         | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.07%   |
| Syntek                                 | 3         | 2.44%   |
| Suyin                                  | 3         | 2.44%   |
| Ricoh                                  | 3         | 2.44%   |
| Apple                                  | 2         | 1.63%   |
| UltraSemi                              | 1         | 0.81%   |
| Samsung Electronics                    | 1         | 0.81%   |
| Primax Electronics                     | 1         | 0.81%   |
| Luxvisions Innotech Limited            | 1         | 0.81%   |
| Lenovo                                 | 1         | 0.81%   |
| KYE Systems (Mouse Systems)            | 1         | 0.81%   |
| Importek                               | 1         | 0.81%   |
| Guillemot                              | 1         | 0.81%   |
| ALi                                    | 1         | 0.81%   |
| Acer                                   | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 10        | 8.13%   |
| Microdia Integrated_Webcam_HD                               | 8         | 6.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 4.07%   |
| Realtek Integrated_Webcam_HD                                | 4         | 3.25%   |
| Bison EasyCamera                                            | 4         | 3.25%   |
| Quanta HP HD Camera                                         | 3         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 3         | 2.44%   |
| Syntek Integrated Camera                                    | 2         | 1.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.63%   |
| Sunplus HP Universal Camera                                 | 2         | 1.63%   |
| Realtek HD WebCam                                           | 2         | 1.63%   |
| Lite-On HP HD Webcam                                        | 2         | 1.63%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.63%   |
| Chicony HP Truevision HD                                    | 2         | 1.63%   |
| Chicony HD WebCam                                           | 2         | 1.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.63%   |
| Bison Integrated Camera                                     | 2         | 1.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                          | 2         | 1.63%   |
| UltraSemi USB3 Video                                        | 1         | 0.81%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.81%   |
| Suyin HP TrueVision HD                                      | 1         | 0.81%   |
| Sunplus TOSHIBA Web Camera - HD                             | 1         | 0.81%   |
| Sunplus Lenovo EasyCamera                                   | 1         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.81%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.81%   |
| Sunplus HD WebCam                                           | 1         | 0.81%   |
| Sunplus ASUS Webcam                                         | 1         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.81%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.81%   |
| Ricoh Pavilion Webcam                                       | 1         | 0.81%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 0.81%   |
| Realtek VGA WebCam                                          | 1         | 0.81%   |
| Realtek USB Camera                                          | 1         | 0.81%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 0.81%   |
| Realtek Integrated Webcam HD                                | 1         | 0.81%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 0.81%   |
| Realtek FJ Camera                                           | 1         | 0.81%   |
| Quanta USB Webcam                                           | 1         | 0.81%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.81%   |
| Quanta HP Webcam                                            | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 53.57%  |
| Synaptics                  | 7         | 25%     |
| Shenzhen Goodix Technology | 2         | 7.14%   |
| LighTuning Technology      | 2         | 7.14%   |
| AuthenTec                  | 2         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 17.86%  |
| Validity Sensors VFS471 Fingerprint Reader               | 5         | 17.86%  |
| Validity Sensors Synaptics WBDI                          | 2         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor                | 2         | 7.14%   |
| Synaptics  WBDI                                          | 2         | 7.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.57%   |
| Synaptics WBDI                                           | 1         | 3.57%   |
| Synaptics UWP WBDI                                       | 1         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.57%   |
| LighTuning Fingerprint Reader                            | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 3.57%   |
| AuthenTec Fingerprint Sensor                             | 1         | 3.57%   |
| AuthenTec AES2810                                        | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 72.73%  |
| Upek        | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 4         | 36.36%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 131       | 66.16%  |
| 1     | 61        | 30.81%  |
| 2     | 5         | 2.53%   |
| 3     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 38.89%  |
| Graphics card            | 14        | 19.44%  |
| Net/wireless             | 9         | 12.5%   |
| Chipcard                 | 9         | 12.5%   |
| Multimedia controller    | 3         | 4.17%   |
| Bluetooth                | 3         | 4.17%   |
| Sound                    | 2         | 2.78%   |
| Storage/raid             | 1         | 1.39%   |
| Modem                    | 1         | 1.39%   |
| Firewire controller      | 1         | 1.39%   |
| Communication controller | 1         | 1.39%   |


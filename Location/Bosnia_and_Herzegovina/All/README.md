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

Total: 279

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 22        | 11.58%  |
| Ubuntu 22.04       | 10        | 5.26%   |
| Ubuntu 18.04       | 10        | 5.26%   |
| Pop!_OS 21.04      | 6         | 3.16%   |
| OpenMandriva 4.3   | 6         | 3.16%   |
| Zorin 16           | 5         | 2.63%   |
| Arch Rolling       | 5         | 2.63%   |
| Ubuntu 23.04       | 4         | 2.11%   |
| Manjaro            | 4         | 2.11%   |
| Linux Mint 21.1    | 4         | 2.11%   |
| Linux Mint 20.2    | 4         | 2.11%   |
| Linux Mint 19.3    | 4         | 2.11%   |
| ArcoLinux Rolling  | 4         | 2.11%   |
| Xubuntu 20.04      | 3         | 1.58%   |
| Ubuntu 20.10       | 3         | 1.58%   |
| Pop!_OS 20.04      | 3         | 1.58%   |
| OpenMandriva 23.03 | 3         | 1.58%   |
| Linux Mint 19.1    | 3         | 1.58%   |
| KDE neon 20.04     | 3         | 1.58%   |
| Fedora 38          | 3         | 1.58%   |
| Fedora 32          | 3         | 1.58%   |
| Debian 10          | 3         | 1.58%   |
| Zorin 17           | 2         | 1.05%   |
| Zorin 15           | 2         | 1.05%   |
| Ubuntu 21.10       | 2         | 1.05%   |
| Ubuntu 19.04       | 2         | 1.05%   |
| ROSA R10           | 2         | 1.05%   |
| ROSA 12.4          | 2         | 1.05%   |
| Pop!_OS 20.10      | 2         | 1.05%   |
| OpenMandriva 23.01 | 2         | 1.05%   |
| MX 23              | 2         | 1.05%   |
| Lubuntu 19.10      | 2         | 1.05%   |
| Linux Mint 21      | 2         | 1.05%   |
| Linux Mint 20.1    | 2         | 1.05%   |
| Kubuntu 22.04      | 2         | 1.05%   |
| Fedora 39          | 2         | 1.05%   |
| Fedora 37          | 2         | 1.05%   |
| Fedora 33          | 2         | 1.05%   |
| Endless 3.7.8      | 2         | 1.05%   |
| Elementary 7.1     | 2         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 50        | 27.78%  |
| Linux Mint       | 19        | 10.56%  |
| Fedora           | 13        | 7.22%   |
| Pop!_OS          | 12        | 6.67%   |
| OpenMandriva     | 11        | 6.11%   |
| Zorin            | 9         | 5%      |
| Manjaro          | 7         | 3.89%   |
| Debian           | 7         | 3.89%   |
| Arch             | 6         | 3.33%   |
| KDE neon         | 5         | 2.78%   |
| Endless          | 5         | 2.78%   |
| Xubuntu          | 4         | 2.22%   |
| ROSA             | 4         | 2.22%   |
| ArcoLinux        | 4         | 2.22%   |
| Lubuntu          | 3         | 1.67%   |
| Elementary       | 3         | 1.67%   |
| Ubuntu Unity     | 2         | 1.11%   |
| MX               | 2         | 1.11%   |
| LMDE             | 2         | 1.11%   |
| Kubuntu          | 2         | 1.11%   |
| Xero             | 1         | 0.56%   |
| Ubuntu Studio    | 1         | 0.56%   |
| Ubuntu Budgie    | 1         | 0.56%   |
| TUXEDO OS        | 1         | 0.56%   |
| Rocky Linux      | 1         | 0.56%   |
| PureOS           | 1         | 0.56%   |
| org.kde.Platform | 1         | 0.56%   |
| Garuda Linux     | 1         | 0.56%   |
| EndeavourOS      | 1         | 0.56%   |
| BunsenLabs       | 1         | 0.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 6         | 2.94%   |
| 5.3.0-28-generic                | 5         | 2.45%   |
| 5.4.0-52-generic                | 4         | 1.96%   |
| 5.15.0-56-generic               | 4         | 1.96%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.47%   |
| 6.2.0-20-generic                | 3         | 1.47%   |
| 5.3.0-46-generic                | 3         | 1.47%   |
| 5.15.0-48-generic               | 3         | 1.47%   |
| 5.13.0-39-generic               | 3         | 1.47%   |
| 6.5.0-14-generic                | 2         | 0.98%   |
| 6.2.0-36-generic                | 2         | 0.98%   |
| 6.2.0-32-generic                | 2         | 0.98%   |
| 6.2.0-26-generic                | 2         | 0.98%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.98%   |
| 6.1.0-13-amd64                  | 2         | 0.98%   |
| 5.8.0-7630-generic              | 2         | 0.98%   |
| 5.8.0-59-generic                | 2         | 0.98%   |
| 5.4.0-89-generic                | 2         | 0.98%   |
| 5.4.0-67-generic                | 2         | 0.98%   |
| 5.3.0-42-generic                | 2         | 0.98%   |
| 5.19.0-35-generic               | 2         | 0.98%   |
| 5.15.0-50-generic               | 2         | 0.98%   |
| 5.15.0-39-generic               | 2         | 0.98%   |
| 5.15.0-25-generic               | 2         | 0.98%   |
| 5.13.0-7620-generic             | 2         | 0.98%   |
| 5.13.0-7614-generic             | 2         | 0.98%   |
| 5.11.0-40-generic               | 2         | 0.98%   |
| 5.11.0-38-generic               | 2         | 0.98%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.98%   |
| 4.19.0-13-amd64                 | 2         | 0.98%   |
| 4.18.0-15-generic               | 2         | 0.98%   |
| 4.15.0-94-generic               | 2         | 0.98%   |
| 4.15.0-47-generic               | 2         | 0.98%   |
| 4.15.0-20-generic               | 2         | 0.98%   |
| 6.6.8-200.fc39.x86_64           | 1         | 0.49%   |
| 6.6.6-200.fc39.x86_64           | 1         | 0.49%   |
| 6.6.3-zen1-1-zen                | 1         | 0.49%   |
| 6.6.2-arch1-1                   | 1         | 0.49%   |
| 6.6.1-arch1-1                   | 1         | 0.49%   |
| 6.5.7-200.fc38.x86_64           | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 13.27%  |
| 5.15.0  | 17        | 8.67%   |
| 5.13.0  | 14        | 7.14%   |
| 5.3.0   | 11        | 5.61%   |
| 5.8.0   | 10        | 5.1%    |
| 4.15.0  | 10        | 5.1%    |
| 6.2.0   | 9         | 4.59%   |
| 5.11.0  | 9         | 4.59%   |
| 5.16.7  | 6         | 3.06%   |
| 5.19.0  | 5         | 2.55%   |
| 5.0.0   | 5         | 2.55%   |
| 6.5.0   | 4         | 2.04%   |
| 5.10.0  | 4         | 2.04%   |
| 4.18.0  | 4         | 2.04%   |
| 6.2.6   | 3         | 1.53%   |
| 6.1.0   | 3         | 1.53%   |
| 6.1.1   | 2         | 1.02%   |
| 6.0.8   | 2         | 1.02%   |
| 4.9.60  | 2         | 1.02%   |
| 4.19.0  | 2         | 1.02%   |
| 6.6.8   | 1         | 0.51%   |
| 6.6.6   | 1         | 0.51%   |
| 6.6.3   | 1         | 0.51%   |
| 6.6.2   | 1         | 0.51%   |
| 6.6.1   | 1         | 0.51%   |
| 6.5.7   | 1         | 0.51%   |
| 6.5.5   | 1         | 0.51%   |
| 6.4.8   | 1         | 0.51%   |
| 6.4.7   | 1         | 0.51%   |
| 6.4.14  | 1         | 0.51%   |
| 6.4.12  | 1         | 0.51%   |
| 6.3.5   | 1         | 0.51%   |
| 6.3.1   | 1         | 0.51%   |
| 6.2.15  | 1         | 0.51%   |
| 6.1.46  | 1         | 0.51%   |
| 6.1.26  | 1         | 0.51%   |
| 6.1.15  | 1         | 0.51%   |
| 6.0.15  | 1         | 0.51%   |
| 6.0.12  | 1         | 0.51%   |
| 5.9.8   | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 15.03%  |
| 5.15    | 21        | 10.88%  |
| 5.13    | 15        | 7.77%   |
| 6.2     | 13        | 6.74%   |
| 5.8     | 12        | 6.22%   |
| 5.11    | 12        | 6.22%   |
| 5.3     | 11        | 5.7%    |
| 4.15    | 10        | 5.18%   |
| 6.1     | 8         | 4.15%   |
| 5.16    | 8         | 4.15%   |
| 5.10    | 8         | 4.15%   |
| 6.5     | 6         | 3.11%   |
| 5.19    | 6         | 3.11%   |
| 6.6     | 5         | 2.59%   |
| 5.0     | 5         | 2.59%   |
| 6.4     | 4         | 2.07%   |
| 4.18    | 4         | 2.07%   |
| 6.0     | 3         | 1.55%   |
| 4.9     | 3         | 1.55%   |
| 6.3     | 2         | 1.04%   |
| 5.9     | 2         | 1.04%   |
| 5.14    | 2         | 1.04%   |
| 4.19    | 2         | 1.04%   |
| 5.7     | 1         | 0.52%   |
| 5.6     | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 163       | 95.32%  |
| i686    | 7         | 4.09%   |
| aarch64 | 1         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 85        | 48.02%  |
| KDE5       | 22        | 12.43%  |
| XFCE       | 20        | 11.3%   |
| Unknown    | 16        | 9.04%   |
| X-Cinnamon | 11        | 6.21%   |
| Pantheon   | 3         | 1.69%   |
| KDE        | 3         | 1.69%   |
| Unity      | 2         | 1.13%   |
| MATE       | 2         | 1.13%   |
| LXQt       | 2         | 1.13%   |
| KDE4       | 2         | 1.13%   |
| sway       | 1         | 0.56%   |
| LXDE       | 1         | 0.56%   |
| i3         | 1         | 0.56%   |
| Hyprland   | 1         | 0.56%   |
| DDE        | 1         | 0.56%   |
| Cinnamon   | 1         | 0.56%   |
| BunsenLabs | 1         | 0.56%   |
| Budgie     | 1         | 0.56%   |
| bspwm      | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 136       | 77.71%  |
| Wayland | 33        | 18.86%  |
| Unknown | 6         | 3.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 55.8%   |
| SDDM    | 23        | 12.71%  |
| GDM     | 20        | 11.05%  |
| GDM3    | 16        | 8.84%   |
| LightDM | 15        | 8.29%   |
| TDM     | 4         | 2.21%   |
| KDM     | 2         | 1.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 127       | 72.16%  |
| Unknown | 17        | 9.66%   |
| hr_HR   | 10        | 5.68%   |
| bs_BA   | 8         | 4.55%   |
| C       | 3         | 1.7%    |
| sr_RS   | 2         | 1.14%   |
| en_GB   | 2         | 1.14%   |
| en_AU   | 2         | 1.14%   |
| de_CH   | 2         | 1.14%   |
| it_IT   | 1         | 0.57%   |
| en_CA   | 1         | 0.57%   |
| de_DE   | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 105       | 60.34%  |
| EFI  | 69        | 39.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 137       | 78.74%  |
| Btrfs   | 15        | 8.62%   |
| Overlay | 11        | 6.32%   |
| Unknown | 7         | 4.02%   |
| Tmpfs   | 2         | 1.15%   |
| Xfs     | 1         | 0.57%   |
| Ext2    | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 110       | 61.8%   |
| GPT     | 55        | 30.9%   |
| MBR     | 13        | 7.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 89.41%  |
| Yes       | 18        | 10.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 77.46%  |
| Yes       | 39        | 22.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 40        | 23.53%  |
| ASUSTek Computer    | 38        | 22.35%  |
| Lenovo              | 27        | 15.88%  |
| Dell                | 17        | 10%     |
| Acer                | 12        | 7.06%   |
| Gigabyte Technology | 8         | 4.71%   |
| MSI                 | 5         | 2.94%   |
| Toshiba             | 4         | 2.35%   |
| Fujitsu             | 3         | 1.76%   |
| Pegatron            | 2         | 1.18%   |
| Medion              | 2         | 1.18%   |
| Fujitsu Siemens     | 2         | 1.18%   |
| Wistron             | 1         | 0.59%   |
| Sony                | 1         | 0.59%   |
| Notebook            | 1         | 0.59%   |
| NEC Computers       | 1         | 0.59%   |
| Microsoft           | 1         | 0.59%   |
| HUAWEI              | 1         | 0.59%   |
| eMachines           | 1         | 0.59%   |
| ECS                 | 1         | 0.59%   |
| ASRock              | 1         | 0.59%   |
| Unknown             | 1         | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 5         | 2.94%   |
| HP EliteBook 8460p                       | 3         | 1.76%   |
| ASUS PRIME A320M-K                       | 3         | 1.76%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF         | 2         | 1.18%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 1.18%   |
| HP Compaq 8200 Elite SFF PC              | 2         | 1.18%   |
| HP 250 G7 Notebook PC                    | 2         | 1.18%   |
| Dell OptiPlex 745                        | 2         | 1.18%   |
| Dell G3 3590                             | 2         | 1.18%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA   | 2         | 1.18%   |
| ASUS P8H61-M LX3 R2.0                    | 2         | 1.18%   |
| ASUS P5KPL-AM SE                         | 2         | 1.18%   |
| ASUS P5G41T-M LX3                        | 2         | 1.18%   |
| Wistron ProLiant ML110 G5                | 1         | 0.59%   |
| Toshiba Satellite L850-1HQ               | 1         | 0.59%   |
| Toshiba Satellite C855                   | 1         | 0.59%   |
| Toshiba Satellite C850-1GF               | 1         | 0.59%   |
| Toshiba PORTEGE Z930                     | 1         | 0.59%   |
| Sony VGN-BX41VN                          | 1         | 0.59%   |
| Pegatron VS170AA-UUZ p6244ch             | 1         | 0.59%   |
| Pegatron IPMIP-GS                        | 1         | 0.59%   |
| Notebook NL5xRU                          | 1         | 0.59%   |
| NEC Computers VERSAP550 NN951700753      | 1         | 0.59%   |
| MSI Pulse GL66 12UDK                     | 1         | 0.59%   |
| MSI MS-AA1511                            | 1         | 0.59%   |
| MSI MS-7B86                              | 1         | 0.59%   |
| MSI MS-7978                              | 1         | 0.59%   |
| MSI MS-7597                              | 1         | 0.59%   |
| Microsoft Surface Pro 4                  | 1         | 0.59%   |
| Medion MS-7800                           | 1         | 0.59%   |
| Medion MS-7366                           | 1         | 0.59%   |
| Lenovo Yoga 920-13IKB 80Y7               | 1         | 0.59%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.59%   |
| Lenovo V15 G4 AMN 82YU                   | 1         | 0.59%   |
| Lenovo ThinkPad X301 277418G             | 1         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ | 1         | 0.59%   |
| Lenovo ThinkPad W530 24411M9             | 1         | 0.59%   |
| Lenovo ThinkPad T470s W10DG 20JTS0CJ0E   | 1         | 0.59%   |
| Lenovo ThinkPad T430 2349G2G             | 1         | 0.59%   |
| Lenovo ThinkPad T420 4180WAP             | 1         | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 11        | 6.47%   |
| Lenovo ThinkPad         | 10        | 5.88%   |
| Lenovo IdeaPad          | 9         | 5.29%   |
| HP Compaq               | 9         | 5.29%   |
| Acer Aspire             | 8         | 4.71%   |
| ASUS PRIME              | 6         | 3.53%   |
| HP ProBook              | 5         | 2.94%   |
| Dell Latitude           | 5         | 2.94%   |
| ASUS All                | 5         | 2.94%   |
| ASUS VivoBook           | 4         | 2.35%   |
| Toshiba Satellite       | 3         | 1.76%   |
| Lenovo Legion           | 3         | 1.76%   |
| HP ENVY                 | 3         | 1.76%   |
| HP 250                  | 3         | 1.76%   |
| Dell OptiPlex           | 3         | 1.76%   |
| ASUS P5G41T-M           | 3         | 1.76%   |
| Lenovo Yoga             | 2         | 1.18%   |
| HP ZBook                | 2         | 1.18%   |
| HP Pavilion             | 2         | 1.18%   |
| Fujitsu LIFEBOOK        | 2         | 1.18%   |
| Dell XPS                | 2         | 1.18%   |
| Dell Inspiron           | 2         | 1.18%   |
| Dell G3                 | 2         | 1.18%   |
| ASUS TUF                | 2         | 1.18%   |
| ASUS ROG                | 2         | 1.18%   |
| ASUS P8H61-M            | 2         | 1.18%   |
| ASUS P5KPL-AM           | 2         | 1.18%   |
| Wistron ProLiant        | 1         | 0.59%   |
| Toshiba PORTEGE         | 1         | 0.59%   |
| Sony VGN-BX41VN         | 1         | 0.59%   |
| Pegatron VS170AA-UUZ    | 1         | 0.59%   |
| Pegatron IPMIP-GS       | 1         | 0.59%   |
| Notebook NL5xRU         | 1         | 0.59%   |
| NEC Computers VERSAP550 | 1         | 0.59%   |
| MSI Pulse               | 1         | 0.59%   |
| MSI MS-AA1511           | 1         | 0.59%   |
| MSI MS-7B86             | 1         | 0.59%   |
| MSI MS-7978             | 1         | 0.59%   |
| MSI MS-7597             | 1         | 0.59%   |
| Microsoft Surface       | 1         | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 20        | 11.76%  |
| 2011    | 17        | 10%     |
| 2019    | 13        | 7.65%   |
| 2017    | 12        | 7.06%   |
| 2013    | 12        | 7.06%   |
| 2016    | 11        | 6.47%   |
| 2014    | 11        | 6.47%   |
| 2018    | 10        | 5.88%   |
| 2010    | 10        | 5.88%   |
| 2009    | 9         | 5.29%   |
| 2021    | 8         | 4.71%   |
| 2020    | 7         | 4.12%   |
| 2007    | 7         | 4.12%   |
| 2008    | 6         | 3.53%   |
| 2022    | 5         | 2.94%   |
| 2015    | 4         | 2.35%   |
| 2006    | 3         | 1.76%   |
| 2005    | 3         | 1.76%   |
| 2023    | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 102       | 60%     |
| Desktop     | 60        | 35.29%  |
| Convertible | 5         | 2.94%   |
| All in one  | 2         | 1.18%   |
| Tablet      | 1         | 0.59%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 164       | 95.91%  |
| Enabled  | 7         | 4.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 57        | 32.95%  |
| 3.01-4.0    | 27        | 15.61%  |
| 16.01-24.0  | 27        | 15.61%  |
| 8.01-16.0   | 27        | 15.61%  |
| 1.01-2.0    | 16        | 9.25%   |
| 32.01-64.0  | 7         | 4.05%   |
| 2.01-3.0    | 7         | 4.05%   |
| 64.01-256.0 | 2         | 1.16%   |
| 0.51-1.0    | 2         | 1.16%   |
| 0.01-0.5    | 1         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 36.36%  |
| 2.01-3.0  | 53        | 28.34%  |
| 3.01-4.0  | 22        | 11.76%  |
| 4.01-8.0  | 21        | 11.23%  |
| 0.51-1.0  | 15        | 8.02%   |
| 8.01-16.0 | 6         | 3.21%   |
| 0.01-0.5  | 2         | 1.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 68.75%  |
| 2      | 44        | 25%     |
| 3      | 7         | 3.98%   |
| 4      | 2         | 1.14%   |
| 5      | 1         | 0.57%   |
| 0      | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 56.65%  |
| Yes       | 75        | 43.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 86.05%  |
| No        | 24        | 13.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 74.71%  |
| No        | 43        | 25.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 50.29%  |
| No        | 85        | 49.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 170       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 60        | 34.09%  |
| Banja Luka        | 25        | 14.2%   |
| Tuzla             | 10        | 5.68%   |
| Doboj             | 6         | 3.41%   |
| Gracanica         | 5         | 2.84%   |
| Zenica            | 4         | 2.27%   |
| Teslic            | 4         | 2.27%   |
| Prijedor          | 4         | 2.27%   |
| Prnjavor          | 3         | 1.7%    |
| Novi Travnik      | 3         | 1.7%    |
| Gradacac          | 3         | 1.7%    |
| Brcko             | 3         | 1.7%    |
| Bijeljina         | 3         | 1.7%    |
| Zepce             | 2         | 1.14%   |
| Vitez             | 2         | 1.14%   |
| Trebinje          | 2         | 1.14%   |
| Srebrenik         | 2         | 1.14%   |
| Pale              | 2         | 1.14%   |
| Maglaj            | 2         | 1.14%   |
| Lukavac           | 2         | 1.14%   |
| Cazin             | 2         | 1.14%   |
| Banovici          | 2         | 1.14%   |
| Zvornik           | 1         | 0.57%   |
| Zivinice          | 1         | 0.57%   |
| Zavidovici        | 1         | 0.57%   |
| Visoko            | 1         | 0.57%   |
| Velika KladuÅ¡a | 1         | 0.57%   |
| Tarcin            | 1         | 0.57%   |
| Stjepan-Polje     | 1         | 0.57%   |
| Solina            | 1         | 0.57%   |
| Siroki Brijeg     | 1         | 0.57%   |
| Posusje           | 1         | 0.57%   |
| Orahovica Donja   | 1         | 0.57%   |
| Nova Topola       | 1         | 0.57%   |
| Nevesinje         | 1         | 0.57%   |
| Mostar            | 1         | 0.57%   |
| Lukavica          | 1         | 0.57%   |
| Ljubuski          | 1         | 0.57%   |
| Kobilja Glava     | 1         | 0.57%   |
| Jablanica         | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 36        | 55     | 16.44%  |
| WDC                         | 33        | 48     | 15.07%  |
| Kingston                    | 30        | 39     | 13.7%   |
| Seagate                     | 25        | 33     | 11.42%  |
| Toshiba                     | 20        | 23     | 9.13%   |
| Hitachi                     | 17        | 18     | 7.76%   |
| SK hynix                    | 9         | 12     | 4.11%   |
| SanDisk                     | 9         | 11     | 4.11%   |
| Intel                       | 5         | 5      | 2.28%   |
| Unknown                     | 4         | 4      | 1.83%   |
| China                       | 4         | 6      | 1.83%   |
| Micron Technology           | 3         | 7      | 1.37%   |
| A-DATA Technology           | 3         | 3      | 1.37%   |
| Gigabyte Technology         | 2         | 2      | 0.91%   |
| Vaseky                      | 1         | 1      | 0.46%   |
| Union Memory                | 1         | 1      | 0.46%   |
| Transcend                   | 1         | 2      | 0.46%   |
| Team                        | 1         | 1      | 0.46%   |
| SPCC                        | 1         | 1      | 0.46%   |
| Patriot                     | 1         | 1      | 0.46%   |
| ORGE                        | 1         | 1      | 0.46%   |
| OCZ                         | 1         | 2      | 0.46%   |
| Maxtor                      | 1         | 1      | 0.46%   |
| LITEON                      | 1         | 1      | 0.46%   |
| KIOXIA                      | 1         | 1      | 0.46%   |
| Kingston Technology Company | 1         | 1      | 0.46%   |
| Intenso                     | 1         | 1      | 0.46%   |
| HGST                        | 1         | 1      | 0.46%   |
| GOODRAM                     | 1         | 1      | 0.46%   |
| Fujitsu                     | 1         | 1      | 0.46%   |
| Crucial                     | 1         | 1      | 0.46%   |
| ASMT                        | 1         | 1      | 0.46%   |
| Unknown                     | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD                     | 7         | 2.98%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 2.13%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.13%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.7%    |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 1.28%   |
| Kingston SHFS37A120G 120GB SSD                      | 3         | 1.28%   |
| Hitachi HDS721050CLA362 500GB                       | 3         | 1.28%   |
| WDC WD800JD-00MSA1 80GB                             | 2         | 0.85%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 2         | 0.85%   |
| Unknown SD/MMC/MS PRO 256GB                         | 2         | 0.85%   |
| Unknown MMC Card  32GB                              | 2         | 0.85%   |
| Toshiba HDWD120 2TB                                 | 2         | 0.85%   |
| Toshiba DT01ACA100 1TB                              | 2         | 0.85%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.85%   |
| Seagate ST3500413AS 500GB                           | 2         | 0.85%   |
| Seagate ST250LT021-1AF14C 250GB                     | 2         | 0.85%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.85%   |
| Samsung SSD 980 500GB                               | 2         | 0.85%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.85%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.85%   |
| Kingston SUV400S37240G 240GB SSD                    | 2         | 0.85%   |
| Kingston SHFS37A240G 240GB SSD                      | 2         | 0.85%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.85%   |
| Hitachi HTS723232A7A364 320GB                       | 2         | 0.85%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 0.85%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                | 2         | 0.85%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.43%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                    | 1         | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                    | 1         | 0.43%   |
| WDC WD800JD-75MSA3 80GB                             | 1         | 0.43%   |
| WDC WD800JD-60LSA5 80GB                             | 1         | 0.43%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 0.43%   |
| WDC WD7500BPVT-75HXZT3 752GB                        | 1         | 0.43%   |
| WDC WD7500BPVT-24HXZT3 752GB                        | 1         | 0.43%   |
| WDC WD7500AACS-00D6B0 752GB                         | 1         | 0.43%   |
| WDC WD6400AARS-00Y5B1 640GB                         | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.43%   |
| WDC WD5000LPVT-75G33T0 500GB                        | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 43     | 30.53%  |
| Seagate             | 25        | 33     | 26.32%  |
| Hitachi             | 17        | 18     | 17.89%  |
| Toshiba             | 16        | 17     | 16.84%  |
| Samsung Electronics | 3         | 3      | 3.16%   |
| Unknown             | 2         | 2      | 2.11%   |
| Maxtor              | 1         | 1      | 1.05%   |
| HGST                | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 25        | 30     | 31.65%  |
| Samsung Electronics | 19        | 24     | 24.05%  |
| WDC                 | 4         | 4      | 5.06%   |
| SanDisk             | 4         | 5      | 5.06%   |
| China               | 4         | 6      | 5.06%   |
| Intel               | 3         | 3      | 3.8%    |
| A-DATA Technology   | 3         | 3      | 3.8%    |
| SK hynix            | 2         | 4      | 2.53%   |
| Gigabyte Technology | 2         | 2      | 2.53%   |
| Vaseky              | 1         | 1      | 1.27%   |
| Transcend           | 1         | 2      | 1.27%   |
| Toshiba             | 1         | 1      | 1.27%   |
| Team                | 1         | 1      | 1.27%   |
| SPCC                | 1         | 1      | 1.27%   |
| Patriot             | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 2      | 1.27%   |
| Micron Technology   | 1         | 1      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| Intenso             | 1         | 1      | 1.27%   |
| GOODRAM             | 1         | 1      | 1.27%   |
| ASMT                | 1         | 1      | 1.27%   |
| Unknown             | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 86        | 119    | 41.55%  |
| SSD     | 74        | 96     | 35.75%  |
| NVMe    | 43        | 68     | 20.77%  |
| MMC     | 3         | 3      | 1.45%   |
| Unknown | 1         | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 128       | 212    | 71.91%  |
| NVMe | 43        | 68     | 24.16%  |
| SAS  | 4         | 4      | 2.25%   |
| MMC  | 3         | 3      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 176    | 78.15%  |
| 0.51-1.0   | 25        | 27     | 16.56%  |
| 1.01-2.0   | 5         | 7      | 3.31%   |
| 3.01-4.0   | 1         | 2      | 0.66%   |
| 2.01-3.0   | 1         | 2      | 0.66%   |
| 4.01-10.0  | 1         | 1      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 31.67%  |
| 251-500        | 43        | 23.89%  |
| 501-1000       | 20        | 11.11%  |
| 51-100         | 16        | 8.89%   |
| 21-50          | 14        | 7.78%   |
| 1-20           | 13        | 7.22%   |
| 1001-2000      | 5         | 2.78%   |
| Unknown        | 5         | 2.78%   |
| 2001-3000      | 4         | 2.22%   |
| More than 3000 | 3         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 75        | 39.06%  |
| 21-50     | 50        | 26.04%  |
| 51-100    | 25        | 13.02%  |
| 101-250   | 16        | 8.33%   |
| 501-1000  | 10        | 5.21%   |
| 251-500   | 8         | 4.17%   |
| Unknown   | 5         | 2.6%    |
| 1001-2000 | 2         | 1.04%   |
| 2001-3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 6.25%   |
| WDC WD5000AVDS-73U7B1 500GB                                     | 1         | 1      | 6.25%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1         | 1      | 6.25%   |
| WDC WD3200AAJS-00B4A0 320GB                                     | 1         | 1      | 6.25%   |
| Seagate ST3120813AS 120GB                                       | 1         | 1      | 6.25%   |
| Seagate ST3000DM001-1CH166 3TB                                  | 1         | 2      | 6.25%   |
| Seagate ST250LT021-1AF14C 250GB                                 | 1         | 1      | 6.25%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 6.25%   |
| Samsung Electronics MZVKW512HMJP-000H1 512GB                    | 1         | 1      | 6.25%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD                   | 1         | 1      | 6.25%   |
| Samsung Electronics HD322HJ 320GB                               | 1         | 1      | 6.25%   |
| Hitachi HTS542525K9SA00 250GB                                   | 1         | 2      | 6.25%   |
| Hitachi HDS721050CLA362 500GB                                   | 1         | 1      | 6.25%   |
| Crucial CT500P1SSD8 500GB                                       | 1         | 1      | 6.25%   |
| China SSD 128GB                                                 | 1         | 1      | 6.25%   |
| China SATA SSD 240GB                                            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 26.67%  |
| Seagate             | 3         | 4      | 20%     |
| Samsung Electronics | 3         | 4      | 20%     |
| Hitachi             | 2         | 3      | 13.33%  |
| China               | 2         | 2      | 13.33%  |
| Crucial             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 33.33%  |
| Seagate             | 3         | 4      | 33.33%  |
| Hitachi             | 2         | 3      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 11     | 53.85%  |
| SSD  | 4         | 4      | 30.77%  |
| NVMe | 2         | 3      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 115       | 188    | 64.25%  |
| Works    | 51        | 80     | 28.49%  |
| Malfunc  | 12        | 18     | 6.7%    |
| Failed   | 1         | 1      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 125       | 63.45%  |
| AMD                          | 22        | 11.17%  |
| Samsung Electronics          | 16        | 8.12%   |
| SK hynix                     | 7         | 3.55%   |
| Nvidia                       | 6         | 3.05%   |
| Kingston Technology Company  | 6         | 3.05%   |
| SanDisk                      | 5         | 2.54%   |
| Toshiba America Info Systems | 3         | 1.52%   |
| Micron Technology            | 2         | 1.02%   |
| Union Memory (Shenzhen)      | 1         | 0.51%   |
| Micron/Crucial Technology    | 1         | 0.51%   |
| Marvell Technology Group     | 1         | 0.51%   |
| KIOXIA                       | 1         | 0.51%   |
| JMicron Technology           | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 7.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 5.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 4.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 2.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6         | 2.54%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.69%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 1.27%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.27%   |
| AMD FCH SATA Controller D                                                               | 3         | 1.27%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 2         | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2         | 0.85%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 2         | 0.85%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.85%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2         | 0.85%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                          | 2         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.85%   |
| Intel SSD 600P Series                                                                   | 2         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 113       | 54.85%  |
| NVMe | 43        | 20.87%  |
| IDE  | 34        | 16.5%   |
| RAID | 16        | 7.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 137       | 80.59%  |
| AMD    | 32        | 18.82%  |
| ARM    | 1         | 0.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 2.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.76%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.76%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.18%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 1.18%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.18%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.18%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.18%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 1.18%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.18%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.18%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 1.18%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.18%   |
| Intel Celeron CPU 430 @ 1.80GHz               | 2         | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.18%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2         | 1.18%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.18%   |
| Intel Xeon CPU X3210 @ 2.13GHz                | 1         | 0.59%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.59%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.59%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.59%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1         | 0.59%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.59%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.59%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 0.59%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.59%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 47        | 27.65%  |
| Intel Core i7           | 31        | 18.24%  |
| Other                   | 13        | 7.65%   |
| Intel Core i3           | 11        | 6.47%   |
| Intel Celeron           | 9         | 5.29%   |
| AMD Ryzen 5             | 8         | 4.71%   |
| Intel Pentium Dual-Core | 7         | 4.12%   |
| Intel Core 2 Duo        | 7         | 4.12%   |
| Intel Pentium           | 3         | 1.76%   |
| AMD Ryzen 3             | 3         | 1.76%   |
| AMD E1                  | 3         | 1.76%   |
| Intel Core 2 Quad       | 2         | 1.18%   |
| Intel Core 2            | 2         | 1.18%   |
| AMD Ryzen 9             | 2         | 1.18%   |
| AMD Ryzen 7             | 2         | 1.18%   |
| AMD Athlon 64 X2        | 2         | 1.18%   |
| Intel Xeon              | 1         | 0.59%   |
| Intel Pentium M         | 1         | 0.59%   |
| Intel Pentium Dual      | 1         | 0.59%   |
| Intel Pentium 4         | 1         | 0.59%   |
| Intel Celeron D         | 1         | 0.59%   |
| Intel Atom              | 1         | 0.59%   |
| AMD Turion 64 Mobile    | 1         | 0.59%   |
| AMD Ryzen 5 PRO         | 1         | 0.59%   |
| AMD Phenom              | 1         | 0.59%   |
| AMD FX                  | 1         | 0.59%   |
| AMD E2                  | 1         | 0.59%   |
| AMD C-60                | 1         | 0.59%   |
| AMD Athlon X4           | 1         | 0.59%   |
| AMD Athlon II X3        | 1         | 0.59%   |
| AMD Athlon 64           | 1         | 0.59%   |
| AMD A8                  | 1         | 0.59%   |
| AMD A6                  | 1         | 0.59%   |
| AMD A10                 | 1         | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 46.47%  |
| 4      | 61        | 35.88%  |
| 6      | 9         | 5.29%   |
| 1      | 7         | 4.12%   |
| 14     | 5         | 2.94%   |
| 8      | 5         | 2.94%   |
| 3      | 3         | 1.76%   |
| 12     | 1         | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 170       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 100       | 58.48%  |
| 1      | 71        | 41.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 163       | 95.88%  |
| Unknown        | 6         | 3.53%   |
| 32-bit         | 1         | 0.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 32.57%  |
| 0x206a7    | 14        | 8%      |
| 0x306a9    | 12        | 6.86%   |
| 0x306c3    | 9         | 5.14%   |
| 0x1067a    | 9         | 5.14%   |
| 0x406e3    | 5         | 2.86%   |
| 0x806ec    | 4         | 2.29%   |
| 0x806ea    | 4         | 2.29%   |
| 0x906a3    | 3         | 1.71%   |
| 0x806c1    | 3         | 1.71%   |
| 0x506e3    | 3         | 1.71%   |
| 0x40651    | 3         | 1.71%   |
| 0x10676    | 3         | 1.71%   |
| 0x806eb    | 2         | 1.14%   |
| 0x806e9    | 2         | 1.14%   |
| 0x506c9    | 2         | 1.14%   |
| 0x20655    | 2         | 1.14%   |
| 0x08600106 | 2         | 1.14%   |
| 0x08108109 | 2         | 1.14%   |
| 0x05000119 | 2         | 1.14%   |
| 0xf65      | 1         | 0.57%   |
| 0xf43      | 1         | 0.57%   |
| 0xa0653    | 1         | 0.57%   |
| 0xa0652    | 1         | 0.57%   |
| 0x906ec    | 1         | 0.57%   |
| 0x906eb    | 1         | 0.57%   |
| 0x906ea    | 1         | 0.57%   |
| 0x906e9    | 1         | 0.57%   |
| 0x706e5    | 1         | 0.57%   |
| 0x6fd      | 1         | 0.57%   |
| 0x6fb      | 1         | 0.57%   |
| 0x6fa      | 1         | 0.57%   |
| 0x6f6      | 1         | 0.57%   |
| 0x6f2      | 1         | 0.57%   |
| 0x6d8      | 1         | 0.57%   |
| 0x406c4    | 1         | 0.57%   |
| 0x406c3    | 1         | 0.57%   |
| 0x30678    | 1         | 0.57%   |
| 0x106e5    | 1         | 0.57%   |
| 0x10661    | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 14.12%  |
| SandyBridge      | 19        | 11.18%  |
| IvyBridge        | 18        | 10.59%  |
| Haswell          | 15        | 8.82%   |
| Penryn           | 13        | 7.65%   |
| Skylake          | 9         | 5.29%   |
| Core             | 9         | 5.29%   |
| Zen+             | 7         | 4.12%   |
| Unknown          | 6         | 3.53%   |
| Westmere         | 5         | 2.94%   |
| TigerLake        | 5         | 2.94%   |
| Alderlake Hybrid | 5         | 2.94%   |
| Silvermont       | 4         | 2.35%   |
| K8 Hammer        | 4         | 2.35%   |
| Zen 2            | 3         | 1.76%   |
| Zen              | 2         | 1.18%   |
| NetBurst         | 2         | 1.18%   |
| K10              | 2         | 1.18%   |
| Jaguar           | 2         | 1.18%   |
| Goldmont         | 2         | 1.18%   |
| Excavator        | 2         | 1.18%   |
| CometLake        | 2         | 1.18%   |
| Bobcat           | 2         | 1.18%   |
| Zen 3            | 1         | 0.59%   |
| Steamroller      | 1         | 0.59%   |
| Piledriver       | 1         | 0.59%   |
| P6               | 1         | 0.59%   |
| Nehalem          | 1         | 0.59%   |
| K10 Llano        | 1         | 0.59%   |
| IceLake          | 1         | 0.59%   |
| Bulldozer        | 1         | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 96        | 46.6%   |
| Nvidia                     | 59        | 28.64%  |
| AMD                        | 50        | 24.27%  |
| Matrox Electronics Systems | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.83%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.36%   |
| Intel HD Graphics 620                                                                    | 5         | 2.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.36%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.89%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.42%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.42%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 1.42%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.94%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.94%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.94%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 2         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.94%   |
| Intel HD Graphics 500                                                                    | 2         | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.94%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.94%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.94%   |
| AMD Lucienne                                                                             | 2         | 0.94%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.94%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2         | 0.94%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 35.47%  |
| 1 x AMD        | 41        | 23.84%  |
| 1 x Nvidia     | 30        | 17.44%  |
| Intel + Nvidia | 29        | 16.86%  |
| Intel + AMD    | 4         | 2.33%   |
| 2 x AMD        | 3         | 1.74%   |
| Other          | 1         | 0.58%   |
| 3 x AMD        | 1         | 0.58%   |
| 1 x Matrox     | 1         | 0.58%   |
| AMD + Nvidia   | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 135       | 78.49%  |
| Proprietary | 31        | 18.02%  |
| Unknown     | 6         | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 51.14%  |
| 1.01-2.0   | 27        | 15.34%  |
| 0.01-0.5   | 22        | 12.5%   |
| 0.51-1.0   | 18        | 10.23%  |
| 3.01-4.0   | 9         | 5.11%   |
| 7.01-8.0   | 4         | 2.27%   |
| 5.01-6.0   | 3         | 1.7%    |
| 2.01-3.0   | 2         | 1.14%   |
| 8.01-16.0  | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 14.04%  |
| LG Display              | 24        | 13.48%  |
| Samsung Electronics     | 23        | 12.92%  |
| BOE                     | 16        | 8.99%   |
| Chimei Innolux          | 11        | 6.18%   |
| Goldstar                | 9         | 5.06%   |
| Dell                    | 9         | 5.06%   |
| Philips                 | 8         | 4.49%   |
| AOC                     | 7         | 3.93%   |
| Sharp                   | 5         | 2.81%   |
| Ancor Communications    | 4         | 2.25%   |
| Sony                    | 3         | 1.69%   |
| Fujitsu Siemens         | 3         | 1.69%   |
| Chi Mei Optoelectronics | 3         | 1.69%   |
| Unknown                 | 2         | 1.12%   |
| LG Philips              | 2         | 1.12%   |
| InfoVision              | 2         | 1.12%   |
| IBM                     | 2         | 1.12%   |
| Hewlett-Packard         | 2         | 1.12%   |
| BenQ                    | 2         | 1.12%   |
| ASUSTek Computer        | 2         | 1.12%   |
| Acer                    | 2         | 1.12%   |
| ViewSonic               | 1         | 0.56%   |
| Vestel Elektronik       | 1         | 0.56%   |
| PANDA                   | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| MSI                     | 1         | 0.56%   |
| Mi                      | 1         | 0.56%   |
| LTM                     | 1         | 0.56%   |
| LGD                     | 1         | 0.56%   |
| Lenovo                  | 1         | 0.56%   |
| CTV                     | 1         | 0.56%   |
| CSO                     | 1         | 0.56%   |
| Belinea                 | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 4         | 2.17%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 3         | 1.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 2         | 1.09%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 2         | 1.09%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 2         | 1.09%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 2         | 1.09%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 2         | 1.09%   |
| IBM C170 CRT IBM1A51 1280x1024 310x230mm 15.2-inch                     | 2         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 1.09%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                  | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 1.09%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                          | 2         | 1.09%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 2         | 1.09%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                     | 2         | 1.09%   |
| ViewSonic VA702 VSC1C1C 1280x1024 338x270mm 17.0-inch                  | 1         | 0.54%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch   | 1         | 0.54%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1         | 0.54%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B_101920 1280x1024                 | 1         | 0.54%   |
| Sony TV SNY6604 1920x1080                                              | 1         | 0.54%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.54%   |
| Sony TV *00 SNY4904 3840x2160                                          | 1         | 0.54%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                | 1         | 0.54%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.54%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.54%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch                | 1         | 0.54%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                       | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM03E2 1680x1050 433x271mm 20.1-inch   | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0169 1280x1024 380x300mm 19.1-inch   | 1         | 0.54%   |
| Samsung Electronics SAMTRON 50X/V STN0011 1024x768 304x228mm 15.0-inch | 1         | 0.54%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1         | 0.54%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch      | 1         | 0.54%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.54%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch   | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 44.83%  |
| 1366x768 (WXGA)    | 31        | 17.82%  |
| 1600x900 (HD+)     | 15        | 8.62%   |
| 1280x1024 (SXGA)   | 12        | 6.9%    |
| 3840x2160 (4K)     | 7         | 4.02%   |
| 1680x1050 (WSXGA+) | 6         | 3.45%   |
| 1440x900 (WXGA+)   | 6         | 3.45%   |
| 2560x1440 (QHD)    | 5         | 2.87%   |
| 3440x1440          | 2         | 1.15%   |
| 2560x1600          | 2         | 1.15%   |
| 1920x1200 (WUXGA)  | 2         | 1.15%   |
| 1280x800 (WXGA)    | 2         | 1.15%   |
| 3200x1800 (QHD+)   | 1         | 0.57%   |
| 3200x1080          | 1         | 0.57%   |
| 2736x1824          | 1         | 0.57%   |
| 1360x768           | 1         | 0.57%   |
| 1024x768 (XGA)     | 1         | 0.57%   |
| Unknown            | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 31.49%  |
| 17      | 17        | 9.39%   |
| 14      | 17        | 9.39%   |
| 21      | 12        | 6.63%   |
| 23      | 10        | 5.52%   |
| Unknown | 10        | 5.52%   |
| 13      | 9         | 4.97%   |
| 27      | 6         | 3.31%   |
| 24      | 6         | 3.31%   |
| 18      | 5         | 2.76%   |
| 31      | 4         | 2.21%   |
| 19      | 4         | 2.21%   |
| 72      | 3         | 1.66%   |
| 22      | 3         | 1.66%   |
| 12      | 3         | 1.66%   |
| 11      | 3         | 1.66%   |
| 84      | 2         | 1.1%    |
| 34      | 2         | 1.1%    |
| 20      | 2         | 1.1%    |
| 16      | 2         | 1.1%    |
| 54      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 33      | 1         | 0.55%   |
| 26      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 88        | 49.44%  |
| 401-500     | 24        | 13.48%  |
| 501-600     | 21        | 11.8%   |
| 351-400     | 12        | 6.74%   |
| Unknown     | 10        | 5.62%   |
| 201-300     | 9         | 5.06%   |
| 1501-2000   | 5         | 2.81%   |
| 601-700     | 4         | 2.25%   |
| 701-800     | 3         | 1.69%   |
| 801-900     | 1         | 0.56%   |
| 1001-1500   | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 75.46%  |
| 16/10   | 16        | 9.82%   |
| 5/4     | 9         | 5.52%   |
| Unknown | 8         | 4.91%   |
| 4/3     | 3         | 1.84%   |
| 3/2     | 2         | 1.23%   |
| 21/9    | 2         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 29.78%  |
| 201-250        | 25        | 14.04%  |
| 81-90          | 23        | 12.92%  |
| 141-150        | 11        | 6.18%   |
| Unknown        | 10        | 5.62%   |
| 151-200        | 9         | 5.06%   |
| 351-500        | 7         | 3.93%   |
| 121-130        | 7         | 3.93%   |
| More than 1000 | 6         | 3.37%   |
| 301-350        | 6         | 3.37%   |
| 111-120        | 5         | 2.81%   |
| 71-80          | 4         | 2.25%   |
| 51-60          | 3         | 1.69%   |
| 131-140        | 3         | 1.69%   |
| 61-70          | 2         | 1.12%   |
| 251-300        | 2         | 1.12%   |
| 501-1000       | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 32.37%  |
| 51-100        | 47        | 27.17%  |
| 101-120       | 46        | 26.59%  |
| Unknown       | 10        | 5.78%   |
| 161-240       | 6         | 3.47%   |
| 1-50          | 5         | 2.89%   |
| More than 240 | 3         | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 81.03%  |
| 2     | 25        | 14.37%  |
| 0     | 6         | 3.45%   |
| 3     | 2         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 83        | 33.2%   |
| Intel                                  | 68        | 27.2%   |
| Qualcomm Atheros                       | 37        | 14.8%   |
| Broadcom                               | 11        | 4.4%    |
| Ralink Technology                      | 7         | 2.8%    |
| Qualcomm Atheros Communications        | 7         | 2.8%    |
| TP-Link                                | 5         | 2%      |
| Ralink                                 | 4         | 1.6%    |
| Nvidia                                 | 4         | 1.6%    |
| Marvell Technology Group               | 4         | 1.6%    |
| Hewlett-Packard                        | 3         | 1.2%    |
| Broadcom Limited                       | 3         | 1.2%    |
| Sony Ericsson Mobile Communications AB | 2         | 0.8%    |
| Sierra Wireless                        | 2         | 0.8%    |
| MediaTek                               | 2         | 0.8%    |
| ICS Advent                             | 2         | 0.8%    |
| Toshiba                                | 1         | 0.4%    |
| Mercucys                               | 1         | 0.4%    |
| HTC (High Tech Computer)               | 1         | 0.4%    |
| Ericsson Business Mobile Networks      | 1         | 0.4%    |
| D-Link                                 | 1         | 0.4%    |
| ASIX Electronics                       | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 20.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 5.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.7%    |
| Qualcomm Atheros AR9271 802.11n                                        | 7         | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 2.03%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.35%   |
| Intel Wireless 8260                                                    | 4         | 1.35%   |
| Intel Wireless 7260                                                    | 4         | 1.35%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.01%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.01%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 1.01%   |
| Sony Ericsson Mobile AB D2005                                          | 2         | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.68%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.68%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.68%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 35.82%  |
| Qualcomm Atheros                | 29        | 21.64%  |
| Realtek Semiconductor           | 21        | 15.67%  |
| Broadcom                        | 8         | 5.97%   |
| Ralink Technology               | 7         | 5.22%   |
| Qualcomm Atheros Communications | 7         | 5.22%   |
| TP-Link                         | 4         | 2.99%   |
| Ralink                          | 4         | 2.99%   |
| Sierra Wireless                 | 2         | 1.49%   |
| Mercucys                        | 1         | 0.75%   |
| MediaTek                        | 1         | 0.75%   |
| Marvell Technology Group        | 1         | 0.75%   |
| D-Link                          | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 5.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4.44%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 3.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.96%   |
| Intel Wireless 8260                                            | 4         | 2.96%   |
| Intel Wireless 7260                                            | 4         | 2.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 2.22%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.22%   |
| Realtek 802.11ac NIC                                           | 2         | 1.48%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.48%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.48%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.48%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.74%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.74%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.74%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 76        | 49.03%  |
| Intel                                  | 44        | 28.39%  |
| Qualcomm Atheros                       | 12        | 7.74%   |
| Nvidia                                 | 4         | 2.58%   |
| Broadcom                               | 4         | 2.58%   |
| Marvell Technology Group               | 3         | 1.94%   |
| Broadcom Limited                       | 3         | 1.94%   |
| Sony Ericsson Mobile Communications AB | 2         | 1.29%   |
| ICS Advent                             | 2         | 1.29%   |
| TP-Link                                | 1         | 0.65%   |
| MediaTek                               | 1         | 0.65%   |
| HTC (High Tech Computer)               | 1         | 0.65%   |
| Hewlett-Packard                        | 1         | 0.65%   |
| ASIX Electronics                       | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 39.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 9.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.56%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.92%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.92%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 1.92%   |
| Sony Ericsson Mobile AB D2005                                          | 2         | 1.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 1.28%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.28%   |
| Intel Ethernet Connection I217-V                                       | 2         | 1.28%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 2         | 1.28%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 2         | 1.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.64%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.64%   |
| Nvidia MCP73 Ethernet                                                  | 1         | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 0.64%   |
| Nvidia CK8S Ethernet Controller                                        | 1         | 0.64%   |
| Nvidia CK804 Ethernet Controller                                       | 1         | 0.64%   |
| MediaTek File-CD Gadget                                                | 1         | 0.64%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.64%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.64%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.64%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 52.86%  |
| WiFi     | 127       | 45.36%  |
| Modem    | 5         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 63.43%  |
| Ethernet | 64        | 36.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 50.58%  |
| 1     | 77        | 44.77%  |
| 0     | 7         | 4.07%   |
| 3     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 161       | 94.15%  |
| Yes  | 10        | 5.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 32.56%  |
| Qualcomm Atheros Communications | 13        | 15.12%  |
| Realtek Semiconductor           | 9         | 10.47%  |
| IMC Networks                    | 7         | 8.14%   |
| Broadcom                        | 6         | 6.98%   |
| Lite-On Technology              | 4         | 4.65%   |
| Ralink                          | 3         | 3.49%   |
| Hewlett-Packard                 | 3         | 3.49%   |
| Cambridge Silicon Radio         | 3         | 3.49%   |
| Toshiba                         | 2         | 2.33%   |
| Foxconn / Hon Hai               | 2         | 2.33%   |
| Realtek                         | 1         | 1.16%   |
| Marvell Semiconductor           | 1         | 1.16%   |
| Integrated System Solution      | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |
| Askey Computer                  | 1         | 1.16%   |
| Alps Electric                   | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 11.63%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 8.14%   |
| Realtek Bluetooth Radio                             | 6         | 6.98%   |
| Intel AX201 Bluetooth                               | 6         | 6.98%   |
| Intel Bluetooth Device                              | 4         | 4.65%   |
| IMC Networks Bluetooth Radio                        | 4         | 4.65%   |
| Ralink RT3290 Bluetooth                             | 3         | 3.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 3.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.33%   |
| Intel AX200 Bluetooth                               | 2         | 2.33%   |
| IMC Networks Bluetooth Device                       | 2         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 2.33%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.16%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 1.16%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.16%   |
| Realtek Bluetooth Radio                             | 1         | 1.16%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.16%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.16%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.16%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.16%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.16%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.16%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.16%   |
| Broadcom HP Portable Valentine                      | 1         | 1.16%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.16%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.16%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.16%   |
| Askey Bluetooth Device                              | 1         | 1.16%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 133       | 58.08%  |
| AMD                 | 47        | 20.52%  |
| Nvidia              | 37        | 16.16%  |
| Logitech            | 3         | 1.31%   |
| Creative Labs       | 2         | 0.87%   |
| C-Media Electronics | 2         | 0.87%   |
| VIA Technologies    | 1         | 0.44%   |
| Texas Instruments   | 1         | 0.44%   |
| JMTek               | 1         | 0.44%   |
| Focusrite-Novation  | 1         | 0.44%   |
| DSEA A/S            | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 8.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 6.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 6.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.67%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.91%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.91%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.53%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.15%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.15%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.76%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.76%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.76%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 22.22%  |
| Kingston            | 20        | 22.22%  |
| SK hynix            | 19        | 21.11%  |
| Micron Technology   | 11        | 12.22%  |
| Unknown             | 6         | 6.67%   |
| A-DATA Technology   | 4         | 4.44%   |
| Crucial             | 3         | 3.33%   |
| Corsair             | 3         | 3.33%   |
| Nanya Technology    | 1         | 1.11%   |
| INNOVATION PC       | 1         | 1.11%   |
| G.Skill             | 1         | 1.11%   |
| Apacer              | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.94%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 2         | 1.94%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 1.94%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.94%   |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s        | 2         | 1.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                          | 1         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.97%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 0.97%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.97%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.97%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                 | 1         | 0.97%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM SDRAM 2048MT/s         | 1         | 0.97%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB DIMM SDRAM 2048MT/s            | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 1         | 0.97%   |
| SK hynix RAM HMT351U6CFR8C 4096MB DIMM DDR3 1333MT/s             | 1         | 0.97%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 1         | 0.97%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.97%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.97%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.97%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 33        | 42.86%  |
| DDR4    | 28        | 36.36%  |
| DDR2    | 5         | 6.49%   |
| DDR5    | 3         | 3.9%    |
| SDRAM   | 2         | 2.6%    |
| LPDDR3  | 2         | 2.6%    |
| LPDDR5  | 1         | 1.3%    |
| LPDDR4  | 1         | 1.3%    |
| DDR     | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 57.89%  |
| DIMM         | 27        | 35.53%  |
| Row Of Chips | 4         | 5.26%   |
| Unknown      | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 33        | 37.5%   |
| 4096  | 31        | 35.23%  |
| 2048  | 11        | 12.5%   |
| 16384 | 6         | 6.82%   |
| 1024  | 5         | 5.68%   |
| 32768 | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 23        | 27.38%  |
| 3200  | 10        | 11.9%   |
| 2667  | 10        | 11.9%   |
| 2133  | 6         | 7.14%   |
| 1333  | 5         | 5.95%   |
| 800   | 4         | 4.76%   |
| 4800  | 3         | 3.57%   |
| 1867  | 3         | 3.57%   |
| 1334  | 3         | 3.57%   |
| 2400  | 2         | 2.38%   |
| 1866  | 2         | 2.38%   |
| 6400  | 1         | 1.19%   |
| 4199  | 1         | 1.19%   |
| 3733  | 1         | 1.19%   |
| 3400  | 1         | 1.19%   |
| 3266  | 1         | 1.19%   |
| 2800  | 1         | 1.19%   |
| 2048  | 1         | 1.19%   |
| 2000  | 1         | 1.19%   |
| 1800  | 1         | 1.19%   |
| 1067  | 1         | 1.19%   |
| 1066  | 1         | 1.19%   |
| 667   | 1         | 1.19%   |
| 333   | 1         | 1.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 22.86%  |
| Realtek Semiconductor                  | 10        | 9.52%   |
| Bison Electronics                      | 9         | 8.57%   |
| IMC Networks                           | 8         | 7.62%   |
| Microdia                               | 7         | 6.67%   |
| Sunplus Innovation Technology          | 6         | 5.71%   |
| Quanta                                 | 5         | 4.76%   |
| Logitech                               | 5         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.76%   |
| Lite-On Technology                     | 4         | 3.81%   |
| Syntek                                 | 3         | 2.86%   |
| Suyin                                  | 3         | 2.86%   |
| Ricoh                                  | 3         | 2.86%   |
| Apple                                  | 2         | 1.9%    |
| Acer                                   | 2         | 1.9%    |
| Samsung Electronics                    | 1         | 0.95%   |
| Primax Electronics                     | 1         | 0.95%   |
| MacroSilicon                           | 1         | 0.95%   |
| Luxvisions Innotech Limited            | 1         | 0.95%   |
| Lenovo                                 | 1         | 0.95%   |
| KYE Systems (Mouse Systems)            | 1         | 0.95%   |
| Importek                               | 1         | 0.95%   |
| Guillemot                              | 1         | 0.95%   |
| ALi                                    | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 7         | 6.67%   |
| Chicony Integrated Camera                                   | 6         | 5.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 4.76%   |
| Bison EasyCamera                                            | 4         | 3.81%   |
| Syntek Integrated Camera                                    | 2         | 1.9%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.9%    |
| Sunplus HP Universal Camera                                 | 2         | 1.9%    |
| Realtek Integrated_Webcam_HD                                | 2         | 1.9%    |
| Realtek HD WebCam                                           | 2         | 1.9%    |
| Lite-On HP HD Webcam                                        | 2         | 1.9%    |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.9%    |
| Chicony HP Truevision HD                                    | 2         | 1.9%    |
| Chicony HD WebCam                                           | 2         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                          | 2         | 1.9%    |
| Syntek Lenovo EasyCamera                                    | 1         | 0.95%   |
| Suyin HP TrueVision HD                                      | 1         | 0.95%   |
| Sunplus TOSHIBA Web Camera - HD                             | 1         | 0.95%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.95%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.95%   |
| Sunplus HD WebCam                                           | 1         | 0.95%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.95%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.95%   |
| Ricoh Pavilion Webcam                                       | 1         | 0.95%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 0.95%   |
| Realtek VGA WebCam                                          | 1         | 0.95%   |
| Realtek USB Camera                                          | 1         | 0.95%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 0.95%   |
| Realtek Integrated Webcam HD                                | 1         | 0.95%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 0.95%   |
| Realtek FJ Camera                                           | 1         | 0.95%   |
| Quanta USB Webcam                                           | 1         | 0.95%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.95%   |
| Quanta HP Webcam                                            | 1         | 0.95%   |
| Quanta HP TrueVision HD Camera                              | 1         | 0.95%   |
| Quanta HP HD Camera                                         | 1         | 0.95%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 0.95%   |
| MacroSilicon USB3. 0 capture                                | 1         | 0.95%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 0.95%   |
| Logitech Webcam C270                                        | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 55.56%  |
| Synaptics                  | 6         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 7.41%   |
| LighTuning Technology      | 2         | 7.41%   |
| AuthenTec                  | 2         | 7.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 18.52%  |
| Validity Sensors VFS471 Fingerprint Reader               | 5         | 18.52%  |
| Validity Sensors Synaptics WBDI                          | 2         | 7.41%   |
| Validity Sensors Swipe Fingerprint Sensor                | 2         | 7.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 7.41%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.7%    |
| Synaptics WBDI                                           | 1         | 3.7%    |
| Synaptics UWP WBDI                                       | 1         | 3.7%    |
| Synaptics  WBDI                                          | 1         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.7%    |
| LighTuning Fingerprint Reader                            | 1         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 3.7%    |
| AuthenTec Fingerprint Sensor                             | 1         | 3.7%    |
| AuthenTec AES2810                                        | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| Upek        | 1         | 12.5%   |
| Lenovo      | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 58200                                                               | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 114       | 65.14%  |
| 1     | 56        | 32%     |
| 2     | 4         | 2.29%   |
| 3     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 41.54%  |
| Graphics card            | 12        | 18.46%  |
| Chipcard                 | 8         | 12.31%  |
| Net/wireless             | 6         | 9.23%   |
| Multimedia controller    | 3         | 4.62%   |
| Bluetooth                | 3         | 4.62%   |
| Sound                    | 2         | 3.08%   |
| Storage/raid             | 1         | 1.54%   |
| Modem                    | 1         | 1.54%   |
| Firewire controller      | 1         | 1.54%   |
| Communication controller | 1         | 1.54%   |


Gentoo 2.8 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.8/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.8/Notebook/README.md).

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

Total: 161

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 17 9710                 | Notebook    | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [6492614879](https://linux-hardware.org/?probe=6492614879) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3c1ff82bb0](https://linux-hardware.org/?probe=3c1ff82bb0) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Dell          | G5 5505                     | Notebook    | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASRock        | Z170A-X1                    | Desktop     | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5240890472](https://linux-hardware.org/?probe=5240890472) | Mar 29, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| Unknown       | Unknown                     | Soc         | [dad2f6c4ba](https://linux-hardware.org/?probe=dad2f6c4ba) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| MSI           | MS-7A34                     | Notebook    | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Framework     | Laptop                      | Notebook    | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Framework     | Laptop                      | Notebook    | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [bc052daf77](https://linux-hardware.org/?probe=bc052daf77) | Mar 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [4a717f6348](https://linux-hardware.org/?probe=4a717f6348) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [7f7720253e](https://linux-hardware.org/?probe=7f7720253e) | Feb 01, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| MSI           | GE73 Raider RGB 8RF         | Notebook    | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | Notebook    | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| TYAN Compu... | S7025                       | Server      | [c5f294d367](https://linux-hardware.org/?probe=c5f294d367) | Jan 12, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [dcf0799dd1](https://linux-hardware.org/?probe=dcf0799dd1) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fb3838c0db](https://linux-hardware.org/?probe=fb3838c0db) | Jan 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| TYAN Compu... | S7025                       | Server      | [4a4fe05b48](https://linux-hardware.org/?probe=4a4fe05b48) | Dec 27, 2021 |
| EVGA          | Z390 DARK                   | Desktop     | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Intel         | S1200RP G62251-406          | Server      | [986c6d1f51](https://linux-hardware.org/?probe=986c6d1f51) | Dec 24, 2021 |
| Framework     | Laptop                      | Notebook    | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| TYAN Compu... | S7025                       | Server      | [88ee246f4e](https://linux-hardware.org/?probe=88ee246f4e) | Dec 21, 2021 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [36ad5ef96a](https://linux-hardware.org/?probe=36ad5ef96a) | Dec 16, 2021 |
| BESSTAR Te... | ATB15                       | Server      | [783d1d7b6f](https://linux-hardware.org/?probe=783d1d7b6f) | Dec 16, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [40748c60b0](https://linux-hardware.org/?probe=40748c60b0) | Nov 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [95cd0c0751](https://linux-hardware.org/?probe=95cd0c0751) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                         | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| 5.17.1-gentoo-r1                                | 5         | 4%      |
| 5.16.2-gentoo                                   | 3         | 2.4%    |
| 5.15.10-gentoo-x86_64                           | 3         | 2.4%    |
| 5.15.10-gentoo                                  | 3         | 2.4%    |
| 5.14.9-gentoo-x86_64                            | 3         | 2.4%    |
| 5.17.9-gentoo-x86_64                            | 2         | 1.6%    |
| 5.17.8-gentoo-x86_64                            | 2         | 1.6%    |
| 5.17.0-gentoo-x86_64                            | 2         | 1.6%    |
| 5.17.0-gentoo                                   | 2         | 1.6%    |
| 5.16.9-gentoo                                   | 2         | 1.6%    |
| 5.16.4-gentoo                                   | 2         | 1.6%    |
| 5.16.11-gentoo-x86_64                           | 2         | 1.6%    |
| 5.16.11-gentoo-dist                             | 2         | 1.6%    |
| 5.16.0-gentoo-x86_64                            | 2         | 1.6%    |
| 5.15.6-gentoo                                   | 2         | 1.6%    |
| 5.15.1-gentoo-x86_64                            | 2         | 1.6%    |
| 5.14.14-gentoo-x86_64                           | 2         | 1.6%    |
| 5.14.14-gentoo-dist                             | 2         | 1.6%    |
| 5.14.13-gentoo                                  | 2         | 1.6%    |
| 5.14.12-gentoo                                  | 2         | 1.6%    |
| 6.0.0-Phaco-g8f10ff49057f                       | 1         | 0.8%    |
| 5.18.1-gentoo-r1                                | 1         | 0.8%    |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 0.8%    |
| 5.18.0-gentoo                                   | 1         | 0.8%    |
| 5.17.9-gentoo-x86                               | 1         | 0.8%    |
| 5.17.9-gentoo-dist                              | 1         | 0.8%    |
| 5.17.9-gentoo                                   | 1         | 0.8%    |
| 5.17.7-gentoo-limelight                         | 1         | 0.8%    |
| 5.17.7-gentoo-groovin                           | 1         | 0.8%    |
| 5.17.7-gentoo-dist                              | 1         | 0.8%    |
| 5.17.6-gentoo-x86_64                            | 1         | 0.8%    |
| 5.17.5-gentoo-dist                              | 1         | 0.8%    |
| 5.17.3-gentoo-11-02-22                          | 1         | 0.8%    |
| 5.17.3-gentoo                                   | 1         | 0.8%    |
| 5.17.2-gentoo-limelight                         | 1         | 0.8%    |
| 5.17.2-gentoo-groovin                           | 1         | 0.8%    |
| 5.17.2-gentoo                                   | 1         | 0.8%    |
| 5.17.1-gentoo-r1-x86_64                         | 1         | 0.8%    |
| 5.16.9-gentoo-dist                              | 1         | 0.8%    |
| 5.16.8-gentoo-x86_64                            | 1         | 0.8%    |
| 5.16.8-gentoo-gentoo-dist                       | 1         | 0.8%    |
| 5.16.7-tkg-cacule                               | 1         | 0.8%    |
| 5.16.5-gentoo-x86_64                            | 1         | 0.8%    |
| 5.16.5-gentoo-dist                              | 1         | 0.8%    |
| 5.16.3-gentoo                                   | 1         | 0.8%    |
| 5.16.2-gentoo-x86_64                            | 1         | 0.8%    |
| 5.16.15                                         | 1         | 0.8%    |
| 5.16.14-gentoo-x86_64-lto                       | 1         | 0.8%    |
| 5.16.14-gentoo-x86_64                           | 1         | 0.8%    |
| 5.16.14-gentoo-girlhog                          | 1         | 0.8%    |
| 5.16.14-gentoo                                  | 1         | 0.8%    |
| 5.16.13-gentoo                                  | 1         | 0.8%    |
| 5.16.10-gentoo-x86_64                           | 1         | 0.8%    |
| 5.16.10-gentoo--20-feb-2022                     | 1         | 0.8%    |
| 5.16.10-gentoo                                  | 1         | 0.8%    |
| 5.16.1-gentoo-x86_64                            | 1         | 0.8%    |
| 5.16.1-gentoo                                   | 1         | 0.8%    |
| 5.16.0-xanmod1                                  | 1         | 0.8%    |
| 5.16.0-pf5                                      | 1         | 0.8%    |
| 5.16.0-gentoo-gentoo-dist                       | 1         | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.17.1   | 6         | 4.8%    |
| 5.16.0   | 6         | 4.8%    |
| 5.15.10  | 6         | 4.8%    |
| 5.17.9   | 5         | 4%      |
| 5.14.14  | 5         | 4%      |
| 5.17.0   | 4         | 3.2%    |
| 5.16.2   | 4         | 3.2%    |
| 5.16.14  | 4         | 3.2%    |
| 5.16.11  | 4         | 3.2%    |
| 5.14.9   | 4         | 3.2%    |
| 5.17.7   | 3         | 2.4%    |
| 5.17.2   | 3         | 2.4%    |
| 5.16.9   | 3         | 2.4%    |
| 5.16.10  | 3         | 2.4%    |
| 5.15.5   | 3         | 2.4%    |
| 5.15.12  | 3         | 2.4%    |
| 5.18.0   | 2         | 1.6%    |
| 5.17.8   | 2         | 1.6%    |
| 5.17.3   | 2         | 1.6%    |
| 5.16.8   | 2         | 1.6%    |
| 5.16.5   | 2         | 1.6%    |
| 5.16.4   | 2         | 1.6%    |
| 5.16.1   | 2         | 1.6%    |
| 5.15.6   | 2         | 1.6%    |
| 5.15.4   | 2         | 1.6%    |
| 5.15.33  | 2         | 1.6%    |
| 5.15.2   | 2         | 1.6%    |
| 5.15.13  | 2         | 1.6%    |
| 5.15.1   | 2         | 1.6%    |
| 5.15.0   | 2         | 1.6%    |
| 5.14.13  | 2         | 1.6%    |
| 5.14.12  | 2         | 1.6%    |
| 6.0.0    | 1         | 0.8%    |
| 5.18.1   | 1         | 0.8%    |
| 5.17.6   | 1         | 0.8%    |
| 5.17.5   | 1         | 0.8%    |
| 5.16.7   | 1         | 0.8%    |
| 5.16.3   | 1         | 0.8%    |
| 5.16.15  | 1         | 0.8%    |
| 5.16.13  | 1         | 0.8%    |
| 5.15.7   | 1         | 0.8%    |
| 5.15.41  | 1         | 0.8%    |
| 5.15.35  | 1         | 0.8%    |
| 5.15.32  | 1         | 0.8%    |
| 5.15.3   | 1         | 0.8%    |
| 5.15.19  | 1         | 0.8%    |
| 5.15.16  | 1         | 0.8%    |
| 5.15.11  | 1         | 0.8%    |
| 5.14.7   | 1         | 0.8%    |
| 5.14.6   | 1         | 0.8%    |
| 5.14.15  | 1         | 0.8%    |
| 5.14.11  | 1         | 0.8%    |
| 5.10.84  | 1         | 0.8%    |
| 5.10.83  | 1         | 0.8%    |
| 5.10.76  | 1         | 0.8%    |
| 5.10.74  | 1         | 0.8%    |
| 5.10.70  | 1         | 0.8%    |
| 5.10.11  | 1         | 0.8%    |
| 5.10.103 | 1         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 34        | 29.06%  |
| 5.15    | 32        | 27.35%  |
| 5.17    | 24        | 20.51%  |
| 5.14    | 17        | 14.53%  |
| 5.10    | 6         | 5.13%   |
| 5.18    | 3         | 2.56%   |
| 6.0     | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 104       | 97.2%   |
| aarch64 | 2         | 1.87%   |
| i686    | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 36        | 32.73%  |
| Unknown       | 36        | 32.73%  |
| GNOME         | 17        | 15.45%  |
| XFCE          | 8         | 7.27%   |
| DWM           | 3         | 2.73%   |
| Enlightenment | 2         | 1.82%   |
| sway          | 1         | 0.91%   |
| MATE          | 1         | 0.91%   |
| LXQt          | 1         | 0.91%   |
| LeftWM        | 1         | 0.91%   |
| KDE           | 1         | 0.91%   |
| i3            | 1         | 0.91%   |
| fvwm          | 1         | 0.91%   |
| Cinnamon      | 1         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 50        | 45.05%  |
| Wayland | 25        | 22.52%  |
| Unknown | 19        | 17.12%  |
| Tty     | 17        | 15.32%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 45.87%  |
| SDDM    | 34        | 31.19%  |
| LightDM | 12        | 11.01%  |
| GDM     | 8         | 7.34%   |
| SLiM    | 2         | 1.83%   |
| XDM     | 1         | 0.92%   |
| LXDM    | 1         | 0.92%   |
| GREETD  | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 47        | 43.93%  |
| en_GB      | 12        | 11.21%  |
| Unknown    | 11        | 10.28%  |
| C.UTF8     | 8         | 7.48%   |
| ru_RU      | 4         | 3.74%   |
| de_DE      | 4         | 3.74%   |
| C          | 3         | 2.8%    |
| pl_PL      | 2         | 1.87%   |
| fr_FR      | 2         | 1.87%   |
| es_AR      | 2         | 1.87%   |
| el_GR      | 2         | 1.87%   |
| tr_TR      | 1         | 0.93%   |
| sl_SI      | 1         | 0.93%   |
| pt_BR      | 1         | 0.93%   |
| it_IT      | 1         | 0.93%   |
| fr_CA      | 1         | 0.93%   |
| es_ES      | 1         | 0.93%   |
| en_US.UTF8 | 1         | 0.93%   |
| en_NZ      | 1         | 0.93%   |
| en_AU      | 1         | 0.93%   |
| de_CH      | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 93        | 83.78%  |
| BIOS | 18        | 16.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 60        | 56.07%  |
| Btrfs | 36        | 33.64%  |
| F2fs  | 4         | 3.74%   |
| Zfs   | 3         | 2.8%    |
| Xfs   | 2         | 1.87%   |
| XXX   | 1         | 0.93%   |
| Xtrfs | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 99        | 90.83%  |
| MBR     | 5         | 4.59%   |
| Unknown | 5         | 4.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 67.89%  |
| Yes       | 35        | 32.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 73.83%  |
| Yes       | 28        | 26.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 25        | 23.36%  |
| Lenovo                  | 21        | 19.63%  |
| MSI                     | 12        | 11.21%  |
| Dell                    | 10        | 9.35%   |
| Hewlett-Packard         | 6         | 5.61%   |
| Gigabyte Technology     | 6         | 5.61%   |
| ASRock                  | 6         | 5.61%   |
| Intel                   | 4         | 3.74%   |
| Acer                    | 3         | 2.8%    |
| Timi                    | 2         | 1.87%   |
| Framework               | 2         | 1.87%   |
| TYAN Computer           | 1         | 0.93%   |
| Toshiba                 | 1         | 0.93%   |
| System76                | 1         | 0.93%   |
| Supermicro              | 1         | 0.93%   |
| Raspberry Pi Foundation | 1         | 0.93%   |
| Neousys Technology      | 1         | 0.93%   |
| EVGA                    | 1         | 0.93%   |
| BESSTAR Tech            | 1         | 0.93%   |
| BANGHO                  | 1         | 0.93%   |
| Unknown                 | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel S1200RP                            | 2         | 1.87%   |
| HP Laptop 15s-eq0xxx                     | 2         | 1.87%   |
| Framework Laptop                         | 2         | 1.87%   |
| ASUS Z170-A                              | 2         | 1.87%   |
| ASUS TUF GAMING B550-PLUS                | 2         | 1.87%   |
| TYAN S7025                               | 1         | 0.93%   |
| Toshiba Satellite C850D-118              | 1         | 0.93%   |
| Timi RedmiBook 13                        | 1         | 0.93%   |
| Timi Mi Laptop Pro 15                    | 1         | 0.93%   |
| System76 Gazelle                         | 1         | 0.93%   |
| Supermicro Super Server                  | 1         | 0.93%   |
| RPi Raspberry Pi                         | 1         | 0.93%   |
| Neousys Nuvo-8208GC Series               | 1         | 0.93%   |
| MSI MS-7D31                              | 1         | 0.93%   |
| MSI MS-7D25                              | 1         | 0.93%   |
| MSI MS-7C94                              | 1         | 0.93%   |
| MSI MS-7C56                              | 1         | 0.93%   |
| MSI MS-7B98                              | 1         | 0.93%   |
| MSI MS-7B86                              | 1         | 0.93%   |
| MSI MS-7B17                              | 1         | 0.93%   |
| MSI MS-7A34                              | 1         | 0.93%   |
| MSI MS-7996                              | 1         | 0.93%   |
| MSI GS63VR 6RF                           | 1         | 0.93%   |
| MSI GE73 Raider RGB 8RF                  | 1         | 0.93%   |
| MSI GE66 Raider 11UE                     | 1         | 0.93%   |
| Lenovo Yoga Slim 7 14IIL05 82A1          | 1         | 0.93%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 0.93%   |
| Lenovo ThinkPad X390 Yoga 20NN0027MH     | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291QT1             | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI | 1         | 0.93%   |
| Lenovo ThinkPad T470p 20J7S06Q00         | 1         | 0.93%   |
| Lenovo ThinkPad T460 20FMS421US          | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00     | 1         | 0.93%   |
| Lenovo ThinkPad P73 20QSS09S00           | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437      | 1         | 0.93%   |
| Lenovo ThinkPad E495 20NE000BGE          | 1         | 0.93%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX     | 1         | 0.93%   |
| Lenovo ThinkPad 20FMCT01WW               | 1         | 0.93%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 1         | 0.93%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 0.93%   |
| Lenovo Legion R7000 2020 82B6            | 1         | 0.93%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 1         | 0.93%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT        | 1         | 0.93%   |
| Lenovo IdeaPad C340-14IML 81TK           | 1         | 0.93%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 0.93%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 0.93%   |
| Intel NUC8i7HVK                          | 1         | 0.93%   |
| Intel NUC10i7FNH                         | 1         | 0.93%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 0.93%   |
| HP ProBook 6570b                         | 1         | 0.93%   |
| HP Pavilion Notebook                     | 1         | 0.93%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 0.93%   |
| Gigabyte Z87X-UD3H                       | 1         | 0.93%   |
| Gigabyte Z590 UD                         | 1         | 0.93%   |
| Gigabyte Z490 UD                         | 1         | 0.93%   |
| Gigabyte X570 AORUS MASTER               | 1         | 0.93%   |
| Gigabyte H470 HD3                        | 1         | 0.93%   |
| Gigabyte B450M S2H                       | 1         | 0.93%   |
| EVGA Z390 DARK                           | 1         | 0.93%   |
| Dell XPS 17 9710                         | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 10.28%  |
| ASUS ROG            | 10        | 9.35%   |
| ASUS TUF            | 5         | 4.67%   |
| Dell XPS            | 4         | 3.74%   |
| Lenovo Legion       | 3         | 2.8%    |
| Lenovo IdeaPad      | 3         | 2.8%    |
| ASUS PRIME          | 3         | 2.8%    |
| Lenovo Yoga         | 2         | 1.87%   |
| Intel S1200RP       | 2         | 1.87%   |
| HP Pavilion         | 2         | 1.87%   |
| HP Laptop           | 2         | 1.87%   |
| Framework Laptop    | 2         | 1.87%   |
| Dell OptiPlex       | 2         | 1.87%   |
| ASUS Z170-A         | 2         | 1.87%   |
| ASRock X370         | 2         | 1.87%   |
| Acer Aspire         | 2         | 1.87%   |
| TYAN S7025          | 1         | 0.93%   |
| Toshiba Satellite   | 1         | 0.93%   |
| Timi RedmiBook      | 1         | 0.93%   |
| Timi Mi             | 1         | 0.93%   |
| System76 Gazelle    | 1         | 0.93%   |
| Supermicro Super    | 1         | 0.93%   |
| RPi Raspberry       | 1         | 0.93%   |
| Neousys Nuvo-8208GC | 1         | 0.93%   |
| MSI MS-7D31         | 1         | 0.93%   |
| MSI MS-7D25         | 1         | 0.93%   |
| MSI MS-7C94         | 1         | 0.93%   |
| MSI MS-7C56         | 1         | 0.93%   |
| MSI MS-7B98         | 1         | 0.93%   |
| MSI MS-7B86         | 1         | 0.93%   |
| MSI MS-7B17         | 1         | 0.93%   |
| MSI MS-7A34         | 1         | 0.93%   |
| MSI MS-7996         | 1         | 0.93%   |
| MSI GS63VR          | 1         | 0.93%   |
| MSI GE73            | 1         | 0.93%   |
| MSI GE66            | 1         | 0.93%   |
| Lenovo ThinkBook    | 1         | 0.93%   |
| Lenovo IdeaPadFlex  | 1         | 0.93%   |
| Intel NUC8i7HVK     | 1         | 0.93%   |
| Intel NUC10i7FNH    | 1         | 0.93%   |
| HP Victus           | 1         | 0.93%   |
| HP ProBook          | 1         | 0.93%   |
| Gigabyte Z87X-UD3H  | 1         | 0.93%   |
| Gigabyte Z590       | 1         | 0.93%   |
| Gigabyte Z490       | 1         | 0.93%   |
| Gigabyte X570       | 1         | 0.93%   |
| Gigabyte H470       | 1         | 0.93%   |
| Gigabyte B450M      | 1         | 0.93%   |
| EVGA Z390           | 1         | 0.93%   |
| Dell Precision      | 1         | 0.93%   |
| Dell Latitude       | 1         | 0.93%   |
| Dell Inspiron       | 1         | 0.93%   |
| Dell G5             | 1         | 0.93%   |
| BESSTAR Tech X400   | 1         | 0.93%   |
| BANGHO MAX          | 1         | 0.93%   |
| ASUS Z170           | 1         | 0.93%   |
| ASUS UX430UAR       | 1         | 0.93%   |
| ASUS P6X58D-E       | 1         | 0.93%   |
| ASUS P5LD2-Deluxe   | 1         | 0.93%   |
| ASUS 1005HA         | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 25        | 23.36%  |
| 2019    | 22        | 20.56%  |
| 2020    | 19        | 17.76%  |
| 2018    | 11        | 10.28%  |
| 2017    | 7         | 6.54%   |
| 2016    | 6         | 5.61%   |
| 2015    | 3         | 2.8%    |
| 2012    | 3         | 2.8%    |
| 2014    | 2         | 1.87%   |
| 2011    | 2         | 1.87%   |
| Unknown | 2         | 1.87%   |
| 2022    | 1         | 0.93%   |
| 2013    | 1         | 0.93%   |
| 2010    | 1         | 0.93%   |
| 2009    | 1         | 0.93%   |
| 2005    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 49        | 45.79%  |
| Desktop        | 44        | 41.12%  |
| Server         | 6         | 5.61%   |
| Convertible    | 4         | 3.74%   |
| System on chip | 2         | 1.87%   |
| Mini pc        | 2         | 1.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 104       | 95.41%  |
| Enabled  | 5         | 4.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 26        | 24.3%   |
| 16.01-24.0  | 25        | 23.36%  |
| 8.01-16.0   | 18        | 16.82%  |
| 64.01-256.0 | 15        | 14.02%  |
| 4.01-8.0    | 12        | 11.21%  |
| 24.01-32.0  | 5         | 4.67%   |
| 3.01-4.0    | 3         | 2.8%    |
| 2.01-3.0    | 1         | 0.93%   |
| 1.01-2.0    | 1         | 0.93%   |
| 0.51-1.0    | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 29.06%  |
| 1.01-2.0   | 23        | 19.66%  |
| 8.01-16.0  | 19        | 16.24%  |
| 2.01-3.0   | 18        | 15.38%  |
| 3.01-4.0   | 12        | 10.26%  |
| 0.51-1.0   | 6         | 5.13%   |
| 16.01-24.0 | 3         | 2.56%   |
| 24.01-32.0 | 1         | 0.85%   |
| 0.01-0.5   | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 42.2%   |
| 2      | 27        | 24.77%  |
| 3      | 12        | 11.01%  |
| 5      | 9         | 8.26%   |
| 4      | 9         | 8.26%   |
| 6      | 3         | 2.75%   |
| 7      | 2         | 1.83%   |
| 26     | 1         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 87.96%  |
| Yes       | 13        | 12.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 80.37%  |
| No        | 21        | 19.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 69.44%  |
| No        | 33        | 30.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 67.89%  |
| No        | 35        | 32.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 28        | 25.93%  |
| Russia      | 9         | 8.33%   |
| Germany     | 9         | 8.33%   |
| UK          | 6         | 5.56%   |
| Poland      | 6         | 5.56%   |
| Spain       | 5         | 4.63%   |
| India       | 3         | 2.78%   |
| Greece      | 3         | 2.78%   |
| France      | 3         | 2.78%   |
| Belarus     | 3         | 2.78%   |
| Australia   | 3         | 2.78%   |
| Switzerland | 2         | 1.85%   |
| Netherlands | 2         | 1.85%   |
| Hong Kong   | 2         | 1.85%   |
| Finland     | 2         | 1.85%   |
| Czechia     | 2         | 1.85%   |
| China       | 2         | 1.85%   |
| Canada      | 2         | 1.85%   |
| Argentina   | 2         | 1.85%   |
| Uruguay     | 1         | 0.93%   |
| Turkey      | 1         | 0.93%   |
| Sweden      | 1         | 0.93%   |
| Slovenia    | 1         | 0.93%   |
| Romania     | 1         | 0.93%   |
| Philippines | 1         | 0.93%   |
| Norway      | 1         | 0.93%   |
| New Zealand | 1         | 0.93%   |
| Mexico      | 1         | 0.93%   |
| Malaysia    | 1         | 0.93%   |
| Italy       | 1         | 0.93%   |
| Ireland     | 1         | 0.93%   |
| Brazil      | 1         | 0.93%   |
| Bangladesh  | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sterling            | 3         | 2.75%   |
| Moscow              | 3         | 2.75%   |
| Zurich              | 2         | 1.83%   |
| Sydney              | 2         | 1.83%   |
| Swansea             | 2         | 1.83%   |
| Ocala               | 2         | 1.83%   |
| Minsk               | 2         | 1.83%   |
| Los Angeles         | 2         | 1.83%   |
| Kulmbach            | 2         | 1.83%   |
| Kallithea           | 2         | 1.83%   |
| Hyderabad           | 2         | 1.83%   |
| Houston             | 2         | 1.83%   |
| Central             | 2         | 1.83%   |
| Barcelona           | 2         | 1.83%   |
| Winston-Salem       | 1         | 0.92%   |
| West Orange         | 1         | 0.92%   |
| Warsaw              | 1         | 0.92%   |
| Vigo                | 1         | 0.92%   |
| Vantaa              | 1         | 0.92%   |
| Utrecht             | 1         | 0.92%   |
| Ufa                 | 1         | 0.92%   |
| Svobodnyy           | 1         | 0.92%   |
| Storsteinnes        | 1         | 0.92%   |
| St Louis            | 1         | 0.92%   |
| Schwieberdingen     | 1         | 0.92%   |
| Sao Paulo           | 1         | 0.92%   |
| Santa Rosa          | 1         | 0.92%   |
| Sacramento          | 1         | 0.92%   |
| Redmond             | 1         | 0.92%   |
| Ratingen            | 1         | 0.92%   |
| Radovljica          | 1         | 0.92%   |
| Québec             | 1         | 0.92%   |
| Punta Gorda         | 1         | 0.92%   |
| Pujaut              | 1         | 0.92%   |
| Paris               | 1         | 0.92%   |
| Orange              | 1         | 0.92%   |
| Nuremberg           | 1         | 0.92%   |
| Novosibirsk         | 1         | 0.92%   |
| Nizhniy Novgorod    | 1         | 0.92%   |
| Niederdorla         | 1         | 0.92%   |
| New York            | 1         | 0.92%   |
| Neath               | 1         | 0.92%   |
| Murmansk            | 1         | 0.92%   |
| Motala              | 1         | 0.92%   |
| Morcenx             | 1         | 0.92%   |
| Monroe              | 1         | 0.92%   |
| Milton Keynes       | 1         | 0.92%   |
| Milan               | 1         | 0.92%   |
| Mariánské Lázně | 1         | 0.92%   |
| Leidschendam        | 1         | 0.92%   |
| Laziska Gorne       | 1         | 0.92%   |
| Laka                | 1         | 0.92%   |
| Kuala Lumpur        | 1         | 0.92%   |
| Krakow              | 1         | 0.92%   |
| Killeen             | 1         | 0.92%   |
| Kailua-Kona         | 1         | 0.92%   |
| Hyannis             | 1         | 0.92%   |
| Helsinki            | 1         | 0.92%   |
| Guangzhou           | 1         | 0.92%   |
| Gomel               | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 41        | 85     | 21.47%  |
| Samsung Electronics            | 37        | 69     | 19.37%  |
| Seagate                        | 19        | 34     | 9.95%   |
| Intel                          | 11        | 14     | 5.76%   |
| Crucial                        | 10        | 23     | 5.24%   |
| Toshiba                        | 8         | 9      | 4.19%   |
| SK Hynix                       | 8         | 9      | 4.19%   |
| SanDisk                        | 8         | 9      | 4.19%   |
| Hitachi                        | 6         | 8      | 3.14%   |
| A-DATA Technology              | 5         | 6      | 2.62%   |
| Unknown                        | 4         | 9      | 2.09%   |
| Kingston                       | 4         | 4      | 2.09%   |
| Corsair                        | 4         | 5      | 2.09%   |
| Micron Technology              | 3         | 3      | 1.57%   |
| KIOXIA-EXCERIA                 | 3         | 6      | 1.57%   |
| HGST                           | 3         | 3      | 1.57%   |
| Team                           | 2         | 4      | 1.05%   |
| XrayDisk                       | 1         | 1      | 0.52%   |
| Transcend                      | 1         | 1      | 0.52%   |
| Solid State Storage Technology | 1         | 1      | 0.52%   |
| Silicon Motion                 | 1         | 1      | 0.52%   |
| PNY                            | 1         | 1      | 0.52%   |
| PLEXTOR                        | 1         | 2      | 0.52%   |
| Phison                         | 1         | 1      | 0.52%   |
| OCZ-VERTEX                     | 1         | 1      | 0.52%   |
| Netac                          | 1         | 1      | 0.52%   |
| LaCie                          | 1         | 2      | 0.52%   |
| KIOXIA                         | 1         | 2      | 0.52%   |
| Kingchuxing                    | 1         | 2      | 0.52%   |
| GOODRAM                        | 1         | 1      | 0.52%   |
| Apacer                         | 1         | 1      | 0.52%   |
| 2.5"                           | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD10EZEX-08M2NA0 1TB         | 3         | 1.3%    |
| Samsung SSD 980 PRO 2TB          | 3         | 1.3%    |
| Crucial CT2000MX500SSD1 2TB      | 3         | 1.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.87%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2         | 0.87%   |
| Toshiba KXG6AZNV512G 512GB       | 2         | 0.87%   |
| Toshiba DT01ACA100 1TB           | 2         | 0.87%   |
| SK Hynix PC711 NVMe 512GB        | 2         | 0.87%   |
| Seagate ST4000DM005-2DP166 4TB   | 2         | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB   | 2         | 0.87%   |
| Samsung SSD 980 PRO 1TB          | 2         | 0.87%   |
| Samsung SSD 980 1TB              | 2         | 0.87%   |
| Samsung SSD 970 EVO Plus 2TB     | 2         | 0.87%   |
| Samsung SSD 970 EVO Plus 250GB   | 2         | 0.87%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.87%   |
| Samsung SSD 970 EVO 500GB        | 2         | 0.87%   |
| Samsung SSD 970 EVO 250GB        | 2         | 0.87%   |
| Samsung SSD 850 EVO 500GB        | 2         | 0.87%   |
| Samsung NVMe SSD Drive 512GB     | 2         | 0.87%   |
| Samsung MZVLB512HBJQ-000L2 512GB | 2         | 0.87%   |
| KIOXIA-EXCERIA SSD 500GB         | 2         | 0.87%   |
| Intel SSDPEKNW010T8 1TB          | 2         | 0.87%   |
| Intel SSDPEKNU512GZ 512GB        | 2         | 0.87%   |
| Intel SSDPEKKF256G8L 256GB       | 2         | 0.87%   |
| Hitachi HDS723020BLA642 2TB      | 2         | 0.87%   |
| HGST HTS721010A9E630 1TB         | 2         | 0.87%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.87%   |
| Crucial CT1000P1SSD8 1TB         | 2         | 0.87%   |
| Crucial CT1000MX500SSD1 1TB      | 2         | 0.87%   |
| A-DATA SX8200PNP 512GB           | 2         | 0.87%   |
| A-DATA SX8200PNP 1TB             | 2         | 0.87%   |
| XrayDisk SSD 128GB               | 1         | 0.43%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1         | 0.43%   |
| WDC WDS500G2X0C-00L350 500GB     | 1         | 0.43%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.43%   |
| WDC WDS250G2X0C-00L350 250GB     | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.43%   |
| WDC WDS240G2G0A 240GB SSD        | 1         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.43%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1         | 0.43%   |
| WDC WD60EZRX-00MVLB1 6TB         | 1         | 0.43%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1         | 0.43%   |
| WDC WD5000AZLX-00JKKA0 500GB     | 1         | 0.43%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 0.43%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.43%   |
| WDC WD3200LPVX-22V0TT0 320GB     | 1         | 0.43%   |
| WDC WD3200AAJS-22RYA0 320GB      | 1         | 0.43%   |
| WDC WD30EFRX-68N32N0 3TB         | 1         | 0.43%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1         | 0.43%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 0.43%   |
| WDC WD20NPVX-00EA4T0 2TB         | 1         | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.43%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1         | 0.43%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1         | 0.43%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 0.43%   |
| WDC WD2003FYYS-18W0B0 2TB        | 1         | 0.43%   |
| WDC WD10SPSX-08A6W 1TB           | 1         | 0.43%   |
| WDC WD10PURX-64E5EY0 1TB         | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 25        | 65     | 45.45%  |
| Seagate | 17        | 32     | 30.91%  |
| Hitachi | 6         | 8      | 10.91%  |
| Toshiba | 3         | 3      | 5.45%   |
| HGST    | 3         | 3      | 5.45%   |
| LaCie   | 1         | 2      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 24     | 30.36%  |
| Crucial             | 7         | 19     | 12.5%   |
| WDC                 | 6         | 7      | 10.71%  |
| SanDisk             | 6         | 7      | 10.71%  |
| Kingston            | 3         | 3      | 5.36%   |
| Corsair             | 3         | 4      | 5.36%   |
| Toshiba             | 2         | 3      | 3.57%   |
| Intel               | 2         | 2      | 3.57%   |
| A-DATA Technology   | 2         | 2      | 3.57%   |
| XrayDisk            | 1         | 1      | 1.79%   |
| Transcend           | 1         | 1      | 1.79%   |
| Team                | 1         | 2      | 1.79%   |
| PNY                 | 1         | 1      | 1.79%   |
| OCZ-VERTEX          | 1         | 1      | 1.79%   |
| GOODRAM             | 1         | 1      | 1.79%   |
| Apacer              | 1         | 1      | 1.79%   |
| 2.5"                | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 76        | 117    | 44.97%  |
| SSD     | 46        | 80     | 27.22%  |
| HDD     | 43        | 113    | 25.44%  |
| MMC     | 3         | 6      | 1.78%   |
| Unknown | 1         | 3      | 0.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 76        | 117    | 51.7%   |
| SATA | 65        | 189    | 44.22%  |
| SAS  | 3         | 7      | 2.04%   |
| MMC  | 3         | 6      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 62     | 35%     |
| 0.51-1.0   | 32        | 42     | 32%     |
| 1.01-2.0   | 19        | 53     | 19%     |
| 3.01-4.0   | 6         | 9      | 6%      |
| 4.01-10.0  | 5         | 21     | 5%      |
| 2.01-3.0   | 3         | 6      | 3%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 24.55%  |
| 501-1000       | 22        | 20%     |
| More than 3000 | 14        | 12.73%  |
| 1001-2000      | 14        | 12.73%  |
| 101-250        | 11        | 10%     |
| 2001-3000      | 9         | 8.18%   |
| 1-20           | 5         | 4.55%   |
| 51-100         | 3         | 2.73%   |
| Unknown        | 3         | 2.73%   |
| 21-50          | 2         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 20.54%  |
| 1-20           | 17        | 15.18%  |
| 101-250        | 16        | 14.29%  |
| 1001-2000      | 12        | 10.71%  |
| 21-50          | 11        | 9.82%   |
| 51-100         | 11        | 9.82%   |
| 501-1000       | 9         | 8.04%   |
| More than 3000 | 8         | 7.14%   |
| Unknown        | 3         | 2.68%   |
| 2001-3000      | 2         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 3      | 4.76%   |
| WDC WD30EFRX-68AX9N0 3TB          | 1         | 2      | 4.76%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1         | 1      | 4.76%   |
| WDC WD10EZEX-08M2NA0 1TB          | 1         | 2      | 4.76%   |
| WDC WD1002FBYS-18W8B0 1TB         | 1         | 1      | 4.76%   |
| Transcend TS512GSSD720 512GB      | 1         | 1      | 4.76%   |
| Seagate ST3160023AS 160GB         | 1         | 1      | 4.76%   |
| Seagate ST2000DX001-1CM164 2TB    | 1         | 1      | 4.76%   |
| Seagate ST1000LM049-2GH172 1TB    | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 2      | 4.76%   |
| SanDisk SSD PLUS 1000GB           | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 4.76%   |
| Kingston SV100S2128G 128GB SSD    | 1         | 1      | 4.76%   |
| Intel SSDPEKKF256G8L 256GB        | 1         | 1      | 4.76%   |
| Hitachi HUA721010KLA330 1TB       | 1         | 1      | 4.76%   |
| Hitachi HDS722020ALA330 2TB       | 1         | 2      | 4.76%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 4.76%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 1      | 4.76%   |
| Crucial CT1000P1SSD8 1TB          | 1         | 1      | 4.76%   |
| A-DATA Technology SP550 240GB SSD | 1         | 1      | 4.76%   |
| 2.5" SATA SSD 3TG6-P 480GB        | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 9      | 23.81%  |
| Seagate             | 4         | 5      | 19.05%  |
| Hitachi             | 2         | 3      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| Transcend           | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |
| 2.5"                | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 9      | 41.67%  |
| Seagate | 4         | 5      | 33.33%  |
| Hitachi | 2         | 3      | 16.67%  |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 18     | 52.63%  |
| SSD  | 6         | 6      | 31.58%  |
| NVMe | 3         | 3      | 15.79%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 97        | 264    | 76.38%  |
| Malfunc  | 18        | 27     | 14.17%  |
| Detected | 11        | 27     | 8.66%   |
| Failed   | 1         | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 59        | 33.33%  |
| Samsung Electronics            | 30        | 16.95%  |
| AMD                            | 30        | 16.95%  |
| Sandisk                        | 14        | 7.91%   |
| SK Hynix                       | 8         | 4.52%   |
| ASMedia Technology             | 6         | 3.39%   |
| Toshiba America Info Systems   | 4         | 2.26%   |
| Micron Technology              | 4         | 2.26%   |
| Silicon Motion                 | 3         | 1.69%   |
| Phison Electronics             | 3         | 1.69%   |
| KIOXIA                         | 3         | 1.69%   |
| ADATA Technology               | 3         | 1.69%   |
| Solid State Storage Technology | 2         | 1.13%   |
| Seagate Technology             | 2         | 1.13%   |
| Micron/Crucial Technology      | 2         | 1.13%   |
| Silicon Image                  | 1         | 0.56%   |
| Marvell Technology Group       | 1         | 0.56%   |
| LSI Logic / Symbios Logic      | 1         | 0.56%   |
| Kingston Technology Company    | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 13.02%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 8.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 4.17%   |
| SK Hynix Gold P31 SSD                                                          | 6         | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 3.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 3.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 3.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 2.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 2.6%    |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.6%    |
| Micron Non-Volatile memory controller                                          | 4         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.56%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.56%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.56%   |
| Intel SSD 660P Series                                                          | 3         | 1.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 1.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 1.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.04%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.04%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.04%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.04%   |
| KIOXIA NVMe SSD                                                                | 2         | 1.04%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.04%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 1.04%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.52%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.52%   |
| SK Hynix Non-Volatile memory controller                                        | 1         | 0.52%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 0.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.52%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.52%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.52%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.52%   |
| Sandisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.52%   |
| Phison E7 NVMe Controller                                                      | 1         | 0.52%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.52%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.52%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1         | 0.52%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.52%   |
| Intel Optane SSD 900P Series                                                   | 1         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.52%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 48.15%  |
| NVMe | 76        | 46.91%  |
| RAID | 5         | 3.09%   |
| IDE  | 2         | 1.23%   |
| SAS  | 1         | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 62.62%  |
| AMD    | 38        | 35.51%  |
| ARM    | 2         | 1.87%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 3.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 2.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz       | 3         | 2.8%    |
| AMD Ryzen 9 5900X 12-Core Processor     | 3         | 2.8%    |
| AMD Ryzen 9 3950X 16-Core Processor     | 3         | 2.8%    |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz     | 2         | 1.87%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2         | 1.87%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 1.87%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 1.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 1.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.87%   |
| Intel 12th Gen Core i7-12700K           | 2         | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.87%   |
| ARM Processor                           | 2         | 1.87%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 1.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 1.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 1.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 1.87%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 2         | 1.87%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2         | 1.87%   |
| Intel Xeon CPU X5690 @ 3.47GHz          | 1         | 0.93%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 0.93%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.93%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 0.93%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.93%   |
| Intel Core i7-8809G CPU @ 3.10GHz       | 1         | 0.93%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.93%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 0.93%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 0.93%   |
| Intel Core i7-10700F CPU @ 2.90GHz      | 1         | 0.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 0.93%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.93%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 0.93%   |
| Intel Core i5-8200Y CPU @ 1.30GHz       | 1         | 0.93%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 1         | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 0.93%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 0.93%   |
| Intel Core i5-4670K CPU @ 3.40GHz       | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 0.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 1         | 0.93%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 0.93%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 0.93%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 1         | 0.93%   |
| Intel Atom CPU N280 @ 1.66GHz           | 1         | 0.93%   |
| Intel 12th Gen Core i7-12700KF          | 1         | 0.93%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz | 1         | 0.93%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 1         | 0.93%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz | 1         | 0.93%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 22        | 20.56%  |
| Intel Core i7          | 21        | 19.63%  |
| Other                  | 16        | 14.95%  |
| AMD Ryzen 7            | 12        | 11.21%  |
| AMD Ryzen 9            | 10        | 9.35%   |
| AMD Ryzen 5            | 9         | 8.41%   |
| Intel Xeon             | 4         | 3.74%   |
| Intel Core i9          | 3         | 2.8%    |
| AMD Ryzen 3            | 2         | 1.87%   |
| Intel Pentium 4        | 1         | 0.93%   |
| Intel Core i3          | 1         | 0.93%   |
| Intel Atom             | 1         | 0.93%   |
| AMD Ryzen Threadripper | 1         | 0.93%   |
| AMD Ryzen 7 PRO        | 1         | 0.93%   |
| AMD Ryzen 5 PRO        | 1         | 0.93%   |
| AMD EPYC               | 1         | 0.93%   |
| AMD E1                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 35        | 32.71%  |
| 8       | 27        | 25.23%  |
| 6       | 19        | 17.76%  |
| 2       | 9         | 8.41%   |
| 12      | 8         | 7.48%   |
| 16      | 5         | 4.67%   |
| 1       | 2         | 1.87%   |
| 24      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 105       | 98.13%  |
| 2       | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 93        | 86.92%  |
| 1       | 13        | 12.15%  |
| Unknown | 1         | 0.93%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 99.07%  |
| 32-bit         | 1         | 0.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 12.84%  |
| 0x906ea    | 6         | 5.5%    |
| 0x806ec    | 6         | 5.5%    |
| 0x0a50000c | 6         | 5.5%    |
| 0x906ed    | 5         | 4.59%   |
| 0x806d1    | 5         | 4.59%   |
| 0x506e3    | 5         | 4.59%   |
| 0x0a201016 | 4         | 3.67%   |
| 0x08701021 | 4         | 3.67%   |
| 0x906e9    | 3         | 2.75%   |
| 0x90672    | 3         | 2.75%   |
| 0x806c1    | 3         | 2.75%   |
| 0x306c3    | 3         | 2.75%   |
| 0x08001138 | 3         | 2.75%   |
| 0xa0671    | 2         | 1.83%   |
| 0xa0655    | 2         | 1.83%   |
| 0xa0653    | 2         | 1.83%   |
| 0x706e5    | 2         | 1.83%   |
| 0x206c2    | 2         | 1.83%   |
| 0x206a7    | 2         | 1.83%   |
| 0x08608103 | 2         | 1.83%   |
| 0x08600106 | 2         | 1.83%   |
| 0x08600103 | 2         | 1.83%   |
| 0x08108109 | 2         | 1.83%   |
| 0xf43      | 1         | 0.92%   |
| 0xa0660    | 1         | 0.92%   |
| 0xa0652    | 1         | 0.92%   |
| 0x906ec    | 1         | 0.92%   |
| 0x806ea    | 1         | 0.92%   |
| 0x806e9    | 1         | 0.92%   |
| 0x406e3    | 1         | 0.92%   |
| 0x306d4    | 1         | 0.92%   |
| 0x306a9    | 1         | 0.92%   |
| 0x0a50000b | 1         | 0.92%   |
| 0x0a201205 | 1         | 0.92%   |
| 0x08608102 | 1         | 0.92%   |
| 0x08600102 | 1         | 0.92%   |
| 0x0830104d | 1         | 0.92%   |
| 0x08301039 | 1         | 0.92%   |
| 0x08108102 | 1         | 0.92%   |
| 0x0800820d | 1         | 0.92%   |
| 0x08001105 | 1         | 0.92%   |
| 0x05000119 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 22.94%  |
| Zen 2            | 13        | 11.93%  |
| Zen 3            | 12        | 11.01%  |
| Icelake          | 10        | 9.17%   |
| Skylake          | 7         | 6.42%   |
| Unknown          | 7         | 6.42%   |
| CometLake        | 6         | 5.5%    |
| Zen+             | 5         | 4.59%   |
| Zen              | 4         | 3.67%   |
| TigerLake        | 4         | 3.67%   |
| Haswell          | 4         | 3.67%   |
| Alderlake Hybrid | 3         | 2.75%   |
| Westmere         | 2         | 1.83%   |
| SandyBridge      | 2         | 1.83%   |
| NetBurst         | 1         | 0.92%   |
| IvyBridge        | 1         | 0.92%   |
| Broadwell        | 1         | 0.92%   |
| Bonnell          | 1         | 0.92%   |
| Bobcat           | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 47        | 34.81%  |
| Intel                      | 46        | 34.07%  |
| AMD                        | 39        | 28.89%  |
| Matrox Electronics Systems | 2         | 1.48%   |
| ASPEED Technology          | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 9         | 6.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 4.96%   |
| AMD Cezanne                                                                   | 6         | 4.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 3.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 2.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 2.84%   |
| AMD Renoir                                                                    | 4         | 2.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 2.13%   |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 2.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 3         | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 2.13%   |
| Intel HD Graphics 630                                                         | 3         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 2.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 3         | 2.13%   |
| AMD Lucienne                                                                  | 3         | 2.13%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                     | 2         | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2         | 1.42%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 2         | 1.42%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.42%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 2         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.42%   |
| Intel UHD Graphics 620                                                        | 2         | 1.42%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.42%   |
| Intel HD Graphics 530                                                         | 2         | 1.42%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2         | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2         | 1.42%   |
| Intel AlderLake-S GT1                                                         | 2         | 1.42%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.71%   |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1650]                                               | 1         | 0.71%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1         | 0.71%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 0.71%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                         | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.71%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 1         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 0.71%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 1         | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.71%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 0.71%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                            | 1         | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.71%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 1         | 0.71%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 0.71%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                            | 1         | 0.71%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                            | 1         | 0.71%   |
| Intel UHD Graphics 615                                                        | 1         | 0.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 0.71%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 27        | 25.23%  |
| 1 x Nvidia     | 21        | 19.63%  |
| Intel + Nvidia | 20        | 18.69%  |
| 1 x Intel      | 20        | 18.69%  |
| AMD + Nvidia   | 6         | 5.61%   |
| 2 x AMD        | 4         | 3.74%   |
| Other          | 3         | 2.8%    |
| 1 x Matrox     | 2         | 1.87%   |
| Intel + AMD    | 2         | 1.87%   |
| 2 x Intel      | 1         | 0.93%   |
| 1 x ASPEED     | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 57.01%  |
| Proprietary | 39        | 36.45%  |
| Unknown     | 7         | 6.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 43.64%  |
| 7.01-8.0   | 15        | 13.64%  |
| 3.01-4.0   | 12        | 10.91%  |
| 1.01-2.0   | 10        | 9.09%   |
| 8.01-16.0  | 8         | 7.27%   |
| 5.01-6.0   | 6         | 5.45%   |
| 0.51-1.0   | 5         | 4.55%   |
| 0.01-0.5   | 4         | 3.64%   |
| 2.01-3.0   | 2         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 14        | 10.61%  |
| AU Optronics            | 11        | 8.33%   |
| Samsung Electronics     | 9         | 6.82%   |
| Goldstar                | 9         | 6.82%   |
| Chimei Innolux          | 9         | 6.82%   |
| LG Display              | 6         | 4.55%   |
| Lenovo                  | 6         | 4.55%   |
| Hewlett-Packard         | 6         | 4.55%   |
| Dell                    | 6         | 4.55%   |
| Sharp                   | 5         | 3.79%   |
| BenQ                    | 4         | 3.03%   |
| ASUSTek Computer        | 4         | 3.03%   |
| AOC                     | 4         | 3.03%   |
| Ancor Communications    | 4         | 3.03%   |
| Acer                    | 4         | 3.03%   |
| ViewSonic               | 3         | 2.27%   |
| Philips                 | 3         | 2.27%   |
| Iiyama                  | 3         | 2.27%   |
| HannStar                | 2         | 1.52%   |
| Unknown                 | 2         | 1.52%   |
| Valve                   | 1         | 0.76%   |
| Toshiba                 | 1         | 0.76%   |
| Sceptre Tech            | 1         | 0.76%   |
| Sceptre                 | 1         | 0.76%   |
| PANDA                   | 1         | 0.76%   |
| Onkyo                   | 1         | 0.76%   |
| NEC Computers           | 1         | 0.76%   |
| MXX                     | 1         | 0.76%   |
| MStar                   | 1         | 0.76%   |
| Microstep               | 1         | 0.76%   |
| Mi                      | 1         | 0.76%   |
| LYC                     | 1         | 0.76%   |
| KTC                     | 1         | 0.76%   |
| Gigabyte Technology     | 1         | 0.76%   |
| Gateway                 | 1         | 0.76%   |
| CSO                     | 1         | 0.76%   |
| Chi Mei Optoelectronics | 1         | 0.76%   |
| Belinea                 | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 4         | 2.86%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 2         | 1.43%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.43%   |
| Unknown                                                               | 2         | 1.43%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch            | 1         | 0.71%   |
| ViewSonic LCD Monitor VSCCB25 1920x1080 480x270mm 21.7-inch           | 1         | 0.71%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch           | 1         | 0.71%   |
| Valve Index HMD VLV91A8                                               | 1         | 0.71%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                  | 1         | 0.71%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1515 1920x1200 340x210mm 15.7-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch       | 1         | 0.71%   |
| Sceptre LCD Monitor C305W-2560UN                                      | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 1         | 0.71%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch   | 1         | 0.71%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.71%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch    | 1         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.71%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.71%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 1         | 0.71%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                  | 1         | 0.71%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch          | 1         | 0.71%   |
| MXX O-3-H MXX0001 3840x2160 1872x1053mm 84.6-inch                     | 1         | 0.71%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                        | 1         | 0.71%   |
| Microstep LCD Monitor MSI MPG27CQ 2560x1440                           | 1         | 0.71%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.71%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                       | 1         | 0.71%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05BE 1920x1080 382x215mm 17.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0536 1920x1080 294x165mm 13.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 0.71%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                  | 1         | 0.71%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1         | 0.71%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                     | 1         | 0.71%   |
| Lenovo LEN T34w-20 LEN61F3 3440x1440 800x330mm 34.1-inch              | 1         | 0.71%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch              | 1         | 0.71%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch              | 1         | 0.71%   |
| KTC Q2711SH KTC2700 2560x1440 597x336mm 27.0-inch                     | 1         | 0.71%   |
| Iiyama PLG2488H IVM6127 1920x1080 530x300mm 24.0-inch                 | 1         | 0.71%   |
| Iiyama PL3288UH IVM7610 3840x2160 698x393mm 31.5-inch                 | 1         | 0.71%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                  | 1         | 0.71%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                  | 1         | 0.71%   |
| Iiyama PL2760Q IVM663D 2560x1440 600x340mm 27.2-inch                  | 1         | 0.71%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch          | 1         | 0.71%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch         | 1         | 0.71%   |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch           | 1         | 0.71%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1         | 0.71%   |
| Hewlett-Packard 27fw HPN354A 1920x1080 598x336mm 27.0-inch            | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 44.09%  |
| 2560x1440 (QHD)    | 23        | 18.11%  |
| 3840x2160 (4K)     | 13        | 10.24%  |
| 1366x768 (WXGA)    | 6         | 4.72%   |
| 3440x1440          | 5         | 3.94%   |
| 1280x1024 (SXGA)   | 4         | 3.15%   |
| Unknown            | 3         | 2.36%   |
| 3840x1080          | 2         | 1.57%   |
| 2560x1600          | 2         | 1.57%   |
| 2560x1080          | 2         | 1.57%   |
| 2256x1504          | 2         | 1.57%   |
| 1920x1200 (WUXGA)  | 2         | 1.57%   |
| 1600x900 (HD+)     | 2         | 1.57%   |
| 6400x1080          | 1         | 0.79%   |
| 3840x2400          | 1         | 0.79%   |
| 1680x1050 (WSXGA+) | 1         | 0.79%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |
| 1024x600           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 19.7%   |
| 27      | 25        | 18.94%  |
| 23      | 12        | 9.09%   |
| 13      | 12        | 9.09%   |
| 14      | 8         | 6.06%   |
| 21      | 7         | 5.3%    |
| 17      | 7         | 5.3%    |
| 34      | 6         | 4.55%   |
| 24      | 6         | 4.55%   |
| Unknown | 5         | 3.79%   |
| 25      | 3         | 2.27%   |
| 19      | 3         | 2.27%   |
| 49      | 2         | 1.52%   |
| 31      | 2         | 1.52%   |
| 16      | 2         | 1.52%   |
| 84      | 1         | 0.76%   |
| 29      | 1         | 0.76%   |
| 28      | 1         | 0.76%   |
| 20      | 1         | 0.76%   |
| 12      | 1         | 0.76%   |
| 10      | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 37.7%   |
| 501-600     | 37        | 30.33%  |
| 401-500     | 9         | 7.38%   |
| 201-300     | 7         | 5.74%   |
| 701-800     | 6         | 4.92%   |
| 601-700     | 5         | 4.1%    |
| Unknown     | 5         | 4.1%    |
| 351-400     | 4         | 3.28%   |
| 1001-1500   | 2         | 1.64%   |
| 1501-2000   | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 75.89%  |
| 16/10   | 8         | 7.14%   |
| 21/9    | 7         | 6.25%   |
| Unknown | 5         | 4.46%   |
| 5/4     | 4         | 3.57%   |
| 3/2     | 2         | 1.79%   |
| 32/9    | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 25        | 19.23%  |
| 101-110        | 25        | 19.23%  |
| 201-250        | 21        | 16.15%  |
| 81-90          | 17        | 13.08%  |
| 351-500        | 9         | 6.92%   |
| 151-200        | 6         | 4.62%   |
| Unknown        | 5         | 3.85%   |
| 251-300        | 4         | 3.08%   |
| 141-150        | 4         | 3.08%   |
| 71-80          | 3         | 2.31%   |
| 121-130        | 3         | 2.31%   |
| 111-120        | 3         | 2.31%   |
| More than 1000 | 2         | 1.54%   |
| 61-70          | 1         | 0.77%   |
| 41-50          | 1         | 0.77%   |
| 501-1000       | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 30.33%  |
| 101-120       | 34        | 27.87%  |
| 51-100        | 28        | 22.95%  |
| 161-240       | 12        | 9.84%   |
| More than 240 | 5         | 4.1%    |
| Unknown       | 5         | 4.1%    |
| 1-50          | 1         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 71        | 65.14%  |
| 2     | 23        | 21.1%   |
| 0     | 7         | 6.42%   |
| 3     | 6         | 5.5%    |
| 4     | 2         | 1.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 54.86%  |
| Realtek Semiconductor             | 39        | 27.08%  |
| Qualcomm Atheros                  | 4         | 2.78%   |
| MEDIATEK                          | 3         | 2.08%   |
| Aquantia                          | 3         | 2.08%   |
| Marvell Technology Group          | 2         | 1.39%   |
| Broadcom                          | 2         | 1.39%   |
| ASIX Electronics                  | 2         | 1.39%   |
| Samsung Electronics               | 1         | 0.69%   |
| Raspberry Pi                      | 1         | 0.69%   |
| Ralink Technology                 | 1         | 0.69%   |
| NetGear                           | 1         | 0.69%   |
| Microsoft                         | 1         | 0.69%   |
| Lenovo                            | 1         | 0.69%   |
| ICS Advent                        | 1         | 0.69%   |
| Google                            | 1         | 0.69%   |
| Ericsson Business Mobile Networks | 1         | 0.69%   |
| D-Link                            | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 13.74%  |
| Intel Wi-Fi 6 AX200                                               | 16        | 8.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 6         | 3.3%    |
| Intel Ethernet Controller I225-V                                  | 6         | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 3.3%    |
| Intel Wireless 8265 / 8275                                        | 5         | 2.75%   |
| Intel I210 Gigabit Network Connection                             | 5         | 2.75%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 2.75%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.65%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.65%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 1.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.1%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.1%    |
| Intel Wireless-AC 9260                                            | 2         | 1.1%    |
| Intel Wireless 8260                                               | 2         | 1.1%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.1%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 2         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.1%    |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.1%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.55%   |
| Raspberry Pi Pico                                                 | 1         | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.55%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 0.55%   |
| NetGear A6210                                                     | 1         | 0.55%   |
| Microsoft XBOX ACC                                                | 1         | 0.55%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.55%   |
| Intel Wireless 3160                                               | 1         | 0.55%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 75.32%  |
| Realtek Semiconductor | 9         | 11.69%  |
| MEDIATEK              | 3         | 3.9%    |
| Qualcomm Atheros      | 2         | 2.6%    |
| Ralink Technology     | 1         | 1.3%    |
| NetGear               | 1         | 1.3%    |
| Microsoft             | 1         | 1.3%    |
| D-Link                | 1         | 1.3%    |
| Broadcom              | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 16        | 20.51%  |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 7.69%   |
| Intel Wireless 8265 / 8275                                     | 5         | 6.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 6.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 5.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 5.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 3.85%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.56%   |
| Intel Wireless-AC 9260                                         | 2         | 2.56%   |
| Intel Wireless 8260                                            | 2         | 2.56%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.28%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 1.28%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1         | 1.28%   |
| NetGear A6210                                                  | 1         | 1.28%   |
| Microsoft XBOX ACC                                             | 1         | 1.28%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.28%   |
| Intel Wireless 3160                                            | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.28%   |
| D-Link 802.11 n WLAN                                           | 1         | 1.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 44        | 46.32%  |
| Realtek Semiconductor    | 36        | 37.89%  |
| Qualcomm Atheros         | 3         | 3.16%   |
| Aquantia                 | 3         | 3.16%   |
| Marvell Technology Group | 2         | 2.11%   |
| ASIX Electronics         | 2         | 2.11%   |
| Samsung Electronics      | 1         | 1.05%   |
| Lenovo                   | 1         | 1.05%   |
| ICS Advent               | 1         | 1.05%   |
| Google                   | 1         | 1.05%   |
| Broadcom                 | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 25        | 24.51%  |
| Realtek RTL8125 2.5GbE Controller                                     | 7         | 6.86%   |
| Intel I211 Gigabit Network Connection                                 | 6         | 5.88%   |
| Intel Ethernet Controller I225-V                                      | 6         | 5.88%   |
| Intel I210 Gigabit Network Connection                                 | 5         | 4.9%    |
| Intel Ethernet Connection (7) I219-V                                  | 5         | 4.9%    |
| Intel Ethernet Connection (2) I219-V                                  | 5         | 4.9%    |
| Intel 82574L Gigabit Network Connection                               | 3         | 2.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]     | 3         | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 2         | 1.96%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                      | 2         | 1.96%   |
| Intel Ethernet Connection (7) I219-LM                                 | 2         | 1.96%   |
| Intel Ethernet Connection (14) I219-V                                 | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                         | 1         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1         | 0.98%   |
| Realtek Killer E3000 2.5GbE Controller                                | 1         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller             | 1         | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller             | 1         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller               | 1         | 0.98%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller               | 1         | 0.98%   |
| Lenovo ThinkPad TBT 3 Dock                                            | 1         | 0.98%   |
| Intel I350 Gigabit Network Connection                                 | 1         | 0.98%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 0.98%   |
| Intel Ethernet Connection I217-V                                      | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-V                                 | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-LM                                | 1         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                                 | 1         | 0.98%   |
| Intel Ethernet Connection (10) I219-LM                                | 1         | 0.98%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 0.98%   |
| ICS Advent DM9601 Fast Ethernet Adapter                               | 1         | 0.98%   |
| Google Nexus/Pixel Device (tether)                                    | 1         | 0.98%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 0.98%   |
| ASIX AX88772                                                          | 1         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 86        | 53.09%  |
| WiFi     | 74        | 45.68%  |
| Modem    | 2         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 51.82%  |
| Ethernet | 53        | 48.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 47        | 43.93%  |
| 2     | 46        | 42.99%  |
| 3     | 8         | 7.48%   |
| 0     | 3         | 2.8%    |
| 4     | 2         | 1.87%   |
| 6     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 74.55%  |
| Yes  | 28        | 25.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 56        | 74.67%  |
| Realtek Semiconductor   | 6         | 8%      |
| Cambridge Silicon Radio | 5         | 6.67%   |
| ASUSTek Computer        | 2         | 2.67%   |
| Toshiba                 | 1         | 1.33%   |
| MediaTek                | 1         | 1.33%   |
| IMC Networks            | 1         | 1.33%   |
| Foxconn / Hon Hai       | 1         | 1.33%   |
| Edimax Technology       | 1         | 1.33%   |
| Broadcom                | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 16        | 21.33%  |
| Intel AX201 Bluetooth                               | 14        | 18.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 14.67%  |
| Intel Bluetooth wireless interface                  | 7         | 9.33%   |
| Intel AX210 Bluetooth                               | 5         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 6.67%   |
| Realtek Bluetooth Radio                             | 3         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.67%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.33%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.33%   |
| MediaTek Wireless_Device                            | 1         | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.33%   |
| IMC Networks Wireless_Device                        | 1         | 1.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.33%   |
| Edimax Bluetooth Device                             | 1         | 1.33%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.33%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 63        | 34.43%  |
| AMD                                  | 48        | 26.23%  |
| Nvidia                               | 35        | 19.13%  |
| Thesycon Systemsoftware & Consulting | 3         | 1.64%   |
| Logitech                             | 3         | 1.64%   |
| C-Media Electronics                  | 3         | 1.64%   |
| AudioQuest                           | 3         | 1.64%   |
| ASUSTek Computer                     | 3         | 1.64%   |
| Yamaha                               | 2         | 1.09%   |
| SteelSeries ApS                      | 2         | 1.09%   |
| Creative Labs                        | 2         | 1.09%   |
| Valve Software                       | 1         | 0.55%   |
| Texas Instruments                    | 1         | 0.55%   |
| Sony                                 | 1         | 0.55%   |
| Sennheiser Communications            | 1         | 0.55%   |
| SAVITECH                             | 1         | 0.55%   |
| RODE Microphones                     | 1         | 0.55%   |
| Realtek Semiconductor                | 1         | 0.55%   |
| Razer USA                            | 1         | 0.55%   |
| Lenovo                               | 1         | 0.55%   |
| Kingston Technology                  | 1         | 0.55%   |
| JOUNIVO                              | 1         | 0.55%   |
| JMTek                                | 1         | 0.55%   |
| Generalplus Technology               | 1         | 0.55%   |
| FiiO Electronics Technology          | 1         | 0.55%   |
| Creative Technology                  | 1         | 0.55%   |
| ACTIONS                              | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 8.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 5.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 5.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 5.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 4.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 3.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 2.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 2.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 2.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.3%    |
| Nvidia Audio device                                                        | 4         | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.84%   |
| Thesycon Systemsoftware & Consulting E30                                   | 3         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.92%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.92%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.92%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.92%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 0.92%   |
| AudioQuest DragonFly Red                                                   | 2         | 0.92%   |
| ASUSTek Computer USB Audio                                                 | 2         | 0.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.92%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.92%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.46%   |
| Yamaha Steinberg UR22C                                                     | 1         | 0.46%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.46%   |
| Texas Instruments PCM2912A Audio Codec                                     | 1         | 0.46%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.46%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1         | 0.46%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.46%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                          | 1         | 0.46%   |
| SAVITECH SA9023 audio controller                                           | 1         | 0.46%   |
| RODE Microphones RODE VideoMic NTG                                         | 1         | 0.46%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.46%   |
| Razer USA Kraken Tournament Edition                                        | 1         | 0.46%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.46%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.46%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.46%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.46%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.46%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.46%   |
| Logitech Z-5 Speakers                                                      | 1         | 0.46%   |
| Logitech Yeti X                                                            | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 26.32%  |
| SK Hynix            | 17        | 14.91%  |
| Kingston            | 17        | 14.91%  |
| G.Skill             | 14        | 12.28%  |
| Crucial             | 13        | 11.4%   |
| Micron Technology   | 6         | 5.26%   |
| Unknown             | 5         | 4.39%   |
| Corsair             | 4         | 3.51%   |
| Patriot             | 2         | 1.75%   |
| Transcend           | 1         | 0.88%   |
| Team                | 1         | 0.88%   |
| Magnum Tech         | 1         | 0.88%   |
| Innodisk            | 1         | 0.88%   |
| A-DATA Technology   | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.68%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.68%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 1.68%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s          | 2         | 1.68%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 1.68%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.84%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.84%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.84%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.84%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                       | 1         | 0.84%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                       | 1         | 0.84%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 0.84%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.84%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.84%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.84%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.84%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.84%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.84%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.84%   |
| Samsung RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.84%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.84%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.84%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.84%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.84%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.84%   |
| Samsung RAM M471A2G43BB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 0.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.84%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s              | 1         | 0.84%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s             | 1         | 0.84%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.84%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 0.84%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 0.84%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s               | 1         | 0.84%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.84%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 0.84%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s               | 1         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 0.84%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 0.84%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 0.84%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 0.84%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 0.84%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 1         | 0.84%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 1         | 0.84%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s             | 1         | 0.84%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 81.37%  |
| DDR3    | 10        | 9.8%    |
| LPDDR3  | 3         | 2.94%   |
| SDRAM   | 2         | 1.96%   |
| LPDDR4  | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 49.02%  |
| DIMM         | 45        | 44.12%  |
| Row Of Chips | 7         | 6.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 56        | 51.38%  |
| 16384 | 27        | 24.77%  |
| 32768 | 11        | 10.09%  |
| 4096  | 11        | 10.09%  |
| 1024  | 2         | 1.83%   |
| 2048  | 1         | 0.92%   |
| 512   | 1         | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 34        | 30.91%  |
| 2667    | 23        | 20.91%  |
| 2133    | 8         | 7.27%   |
| 1600    | 8         | 7.27%   |
| 3600    | 5         | 4.55%   |
| 2400    | 4         | 3.64%   |
| 4800    | 2         | 1.82%   |
| 3666    | 2         | 1.82%   |
| 3533    | 2         | 1.82%   |
| 3466    | 2         | 1.82%   |
| 3400    | 2         | 1.82%   |
| 3000    | 2         | 1.82%   |
| 2933    | 2         | 1.82%   |
| 1867    | 2         | 1.82%   |
| 1333    | 2         | 1.82%   |
| Unknown | 2         | 1.82%   |
| 4000    | 1         | 0.91%   |
| 3866    | 1         | 0.91%   |
| 3266    | 1         | 0.91%   |
| 2733    | 1         | 0.91%   |
| 2666    | 1         | 0.91%   |
| 2197    | 1         | 0.91%   |
| 1067    | 1         | 0.91%   |
| 1066    | 1         | 0.91%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 11        | 18.33%  |
| Chicony Electronics           | 11        | 18.33%  |
| Logitech                      | 6         | 10%     |
| Realtek Semiconductor         | 4         | 6.67%   |
| Acer                          | 4         | 6.67%   |
| Sunplus Innovation Technology | 3         | 5%      |
| Microdia                      | 3         | 5%      |
| Luxvisions Innotech Limited   | 3         | 5%      |
| Lite-On Technology            | 3         | 5%      |
| Quanta                        | 2         | 3.33%   |
| Valve Software                | 1         | 1.67%   |
| Syntek                        | 1         | 1.67%   |
| SunplusIT                     | 1         | 1.67%   |
| Ruision                       | 1         | 1.67%   |
| MacroSilicon                  | 1         | 1.67%   |
| KYE Systems (Mouse Systems)   | 1         | 1.67%   |
| HD WEBCAM                     | 1         | 1.67%   |
| Generalplus Technology        | 1         | 1.67%   |
| Cubeternet                    | 1         | 1.67%   |
| Creative Technology           | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                      | 9         | 15%     |
| Chicony Integrated Camera                                           | 5         | 8.33%   |
| Sunplus Integrated_Webcam_HD                                        | 2         | 3.33%   |
| Realtek Integrated Webcam HD                                        | 2         | 3.33%   |
| Microdia Integrated_Webcam_HD                                       | 2         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                 | 2         | 3.33%   |
| Chicony HD User Facing                                              | 2         | 3.33%   |
| Acer Integrated Camera                                              | 2         | 3.33%   |
| Valve Software 3D Camera                                            | 1         | 1.67%   |
| Syntek Integrated Camera                                            | 1         | 1.67%   |
| SunplusIT AUKEY PCÃ¢Â€Â”LM4                                 | 1         | 1.67%   |
| Sunplus Canyon CNS CWC5 Webcam                                      | 1         | 1.67%   |
| Ruision UVC Camera                                                  | 1         | 1.67%   |
| Realtek Laptop Camera                                               | 1         | 1.67%   |
| Realtek Integrated Camera                                           | 1         | 1.67%   |
| Quanta RGB-IR Camera                                                | 1         | 1.67%   |
| Quanta HD Webcam                                                    | 1         | 1.67%   |
| Microdia HP Webcam-101                                              | 1         | 1.67%   |
| MacroSilicon USB Video                                              | 1         | 1.67%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                | 1         | 1.67%   |
| Logitech Webcam C270                                                | 1         | 1.67%   |
| Logitech StreamCam                                                  | 1         | 1.67%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1         | 1.67%   |
| Logitech HD Webcam C510                                             | 1         | 1.67%   |
| Logitech HD Pro Webcam C920                                         | 1         | 1.67%   |
| Logitech BRIO Ultra HD Webcam                                       | 1         | 1.67%   |
| Lite-On TOSHIBA Web Camera - HD                                     | 1         | 1.67%   |
| Lite-On Integrated Camera                                           | 1         | 1.67%   |
| Lite-On HP Wide Vision HD Camera                                    | 1         | 1.67%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1         | 1.67%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                                 | 1         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                                   | 1         | 1.67%   |
| HD WEBCAM Web Camera                                                | 1         | 1.67%   |
| Generalplus CAMERA - UVC                                            | 1         | 1.67%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1         | 1.67%   |
| Creative Live! Cam Sync 1080p                                       | 1         | 1.67%   |
| Chicony XiaoMi USB 2.0 Webcam                                       | 1         | 1.67%   |
| Chicony USB2.0 Camera                                               | 1         | 1.67%   |
| Chicony USB 2.0 Camera                                              | 1         | 1.67%   |
| Chicony HP Truevision HD                                            | 1         | 1.67%   |
| Acer NEC HD WebCam                                                  | 1         | 1.67%   |
| Acer HD Webcam                                                      | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Synaptics                  | 3         | 27.27%  |
| Elan Microelectronics      | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| DigitalPersona             | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                             | 2         | 18.18%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 9.09%   |
| Elan ELAN:ARM-M4                                  | 1         | 9.09%   |
| DigitalPersona Fingerprint Reader                 | 1         | 9.09%   |
| Unknown                                           | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 58.93%  |
| 1     | 26        | 23.21%  |
| 2     | 10        | 8.93%   |
| 3     | 6         | 5.36%   |
| 4     | 4         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 14        | 19.44%  |
| Fingerprint reader       | 11        | 15.28%  |
| Graphics card            | 8         | 11.11%  |
| Camera                   | 8         | 11.11%  |
| Bluetooth                | 8         | 11.11%  |
| Net/wireless             | 5         | 6.94%   |
| Multimedia controller    | 4         | 5.56%   |
| Chipcard                 | 3         | 4.17%   |
| Storage/ata              | 2         | 2.78%   |
| Network                  | 2         | 2.78%   |
| Modem                    | 2         | 2.78%   |
| Card reader              | 2         | 2.78%   |
| Storage/raid             | 1         | 1.39%   |
| Sound                    | 1         | 1.39%   |
| Firewire controller      | 1         | 1.39%   |


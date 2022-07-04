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

Total: 196

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Timi          | RedmiBook 13                | Notebook    | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Dell          | Precision 7550              | Notebook    | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [bab7d495b0](https://linux-hardware.org/?probe=bab7d495b0) | Jun 21, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Intel         | S5000XVN                    | Server      | [da50147a63](https://linux-hardware.org/?probe=da50147a63) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
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
| 5.17.1-gentoo-r1                                | 5         | 3.29%   |
| 5.15.41-gentoo                                  | 4         | 2.63%   |
| 5.18.1-gentoo-r2                                | 3         | 1.97%   |
| 5.16.2-gentoo                                   | 3         | 1.97%   |
| 5.15.41-gentoo-dist                             | 3         | 1.97%   |
| 5.15.10-gentoo-x86_64                           | 3         | 1.97%   |
| 5.15.10-gentoo                                  | 3         | 1.97%   |
| 5.14.9-gentoo-x86_64                            | 3         | 1.97%   |
| 5.18.4-gentoo                                   | 2         | 1.32%   |
| 5.17.9-gentoo-x86_64                            | 2         | 1.32%   |
| 5.17.8-gentoo-x86_64                            | 2         | 1.32%   |
| 5.17.0-gentoo-x86_64                            | 2         | 1.32%   |
| 5.17.0-gentoo                                   | 2         | 1.32%   |
| 5.16.9-gentoo                                   | 2         | 1.32%   |
| 5.16.4-gentoo                                   | 2         | 1.32%   |
| 5.16.11-gentoo-x86_64                           | 2         | 1.32%   |
| 5.16.11-gentoo-dist                             | 2         | 1.32%   |
| 5.16.0-gentoo-x86_64                            | 2         | 1.32%   |
| 5.15.6-gentoo                                   | 2         | 1.32%   |
| 5.15.41-gentoo-x86_64                           | 2         | 1.32%   |
| 5.15.12-gentoo-x86_64                           | 2         | 1.32%   |
| 5.15.1-gentoo-x86_64                            | 2         | 1.32%   |
| 5.14.14-gentoo-x86_64                           | 2         | 1.32%   |
| 5.14.14-gentoo-dist                             | 2         | 1.32%   |
| 5.14.13-gentoo                                  | 2         | 1.32%   |
| 5.14.12-gentoo                                  | 2         | 1.32%   |
| 6.0.0-Phaco-g8f10ff49057f                       | 1         | 0.66%   |
| 5.18.8-gentoo                                   | 1         | 0.66%   |
| 5.18.6-gentoo-x86_64                            | 1         | 0.66%   |
| 5.18.6-gentoo                                   | 1         | 0.66%   |
| 5.18.5-gentoo                                   | 1         | 0.66%   |
| 5.18.2-gentoo                                   | 1         | 0.66%   |
| 5.18.1-gentoo-r1-x86_64                         | 1         | 0.66%   |
| 5.18.1-gentoo-r1                                | 1         | 0.66%   |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 0.66%   |
| 5.18.0-gentoo                                   | 1         | 0.66%   |
| 5.18.0-g95ff72a6c129                            | 1         | 0.66%   |
| 5.17.9-gentoo-x86                               | 1         | 0.66%   |
| 5.17.9-gentoo-dist                              | 1         | 0.66%   |
| 5.17.9-gentoo                                   | 1         | 0.66%   |
| 5.17.8-gentoo                                   | 1         | 0.66%   |
| 5.17.7-gentoo-limelight                         | 1         | 0.66%   |
| 5.17.7-gentoo-groovin                           | 1         | 0.66%   |
| 5.17.7-gentoo-dist                              | 1         | 0.66%   |
| 5.17.6-zen1                                     | 1         | 0.66%   |
| 5.17.6-gentoo-x86_64                            | 1         | 0.66%   |
| 5.17.5-gentoo-dist                              | 1         | 0.66%   |
| 5.17.3-gentoo-11-02-22                          | 1         | 0.66%   |
| 5.17.3-gentoo                                   | 1         | 0.66%   |
| 5.17.2-gentoo-limelight                         | 1         | 0.66%   |
| 5.17.2-gentoo-groovin                           | 1         | 0.66%   |
| 5.17.2-gentoo                                   | 1         | 0.66%   |
| 5.17.13-gentoo                                  | 1         | 0.66%   |
| 5.17.12-gentoo-dist                             | 1         | 0.66%   |
| 5.17.1-gentoo-r1-x86_64                         | 1         | 0.66%   |
| 5.16.9-gentoo-dist                              | 1         | 0.66%   |
| 5.16.8-gentoo-x86_64                            | 1         | 0.66%   |
| 5.16.8-gentoo-gentoo-dist                       | 1         | 0.66%   |
| 5.16.7-tkg-cacule                               | 1         | 0.66%   |
| 5.16.5-gentoo-x86_64                            | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.41 | 10        | 6.58%   |
| 5.17.1  | 6         | 3.95%   |
| 5.16.0  | 6         | 3.95%   |
| 5.15.10 | 6         | 3.95%   |
| 5.18.1  | 5         | 3.29%   |
| 5.17.9  | 5         | 3.29%   |
| 5.14.14 | 5         | 3.29%   |
| 5.17.0  | 4         | 2.63%   |
| 5.16.2  | 4         | 2.63%   |
| 5.16.14 | 4         | 2.63%   |
| 5.16.11 | 4         | 2.63%   |
| 5.15.12 | 4         | 2.63%   |
| 5.14.9  | 4         | 2.63%   |
| 5.18.0  | 3         | 1.97%   |
| 5.17.8  | 3         | 1.97%   |
| 5.17.7  | 3         | 1.97%   |
| 5.17.2  | 3         | 1.97%   |
| 5.16.9  | 3         | 1.97%   |
| 5.16.10 | 3         | 1.97%   |
| 5.15.5  | 3         | 1.97%   |
| 5.18.6  | 2         | 1.32%   |
| 5.18.4  | 2         | 1.32%   |
| 5.17.6  | 2         | 1.32%   |
| 5.17.3  | 2         | 1.32%   |
| 5.16.8  | 2         | 1.32%   |
| 5.16.5  | 2         | 1.32%   |
| 5.16.4  | 2         | 1.32%   |
| 5.16.1  | 2         | 1.32%   |
| 5.15.6  | 2         | 1.32%   |
| 5.15.4  | 2         | 1.32%   |
| 5.15.33 | 2         | 1.32%   |
| 5.15.2  | 2         | 1.32%   |
| 5.15.13 | 2         | 1.32%   |
| 5.15.1  | 2         | 1.32%   |
| 5.15.0  | 2         | 1.32%   |
| 5.14.13 | 2         | 1.32%   |
| 5.14.12 | 2         | 1.32%   |
| 6.0.0   | 1         | 0.66%   |
| 5.18.8  | 1         | 0.66%   |
| 5.18.5  | 1         | 0.66%   |
| 5.18.2  | 1         | 0.66%   |
| 5.17.5  | 1         | 0.66%   |
| 5.17.13 | 1         | 0.66%   |
| 5.17.12 | 1         | 0.66%   |
| 5.16.7  | 1         | 0.66%   |
| 5.16.3  | 1         | 0.66%   |
| 5.16.15 | 1         | 0.66%   |
| 5.16.13 | 1         | 0.66%   |
| 5.15.7  | 1         | 0.66%   |
| 5.15.35 | 1         | 0.66%   |
| 5.15.32 | 1         | 0.66%   |
| 5.15.3  | 1         | 0.66%   |
| 5.15.19 | 1         | 0.66%   |
| 5.15.16 | 1         | 0.66%   |
| 5.15.11 | 1         | 0.66%   |
| 5.14.7  | 1         | 0.66%   |
| 5.14.6  | 1         | 0.66%   |
| 5.14.15 | 1         | 0.66%   |
| 5.14.11 | 1         | 0.66%   |
| 5.10.84 | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 42        | 29.17%  |
| 5.16    | 34        | 23.61%  |
| 5.17    | 28        | 19.44%  |
| 5.14    | 17        | 11.81%  |
| 5.18    | 15        | 10.42%  |
| 5.10    | 6         | 4.17%   |
| 6.0     | 1         | 0.69%   |
| 4.9     | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 124       | 96.12%  |
| i686    | 2         | 1.55%   |
| aarch64 | 2         | 1.55%   |
| ppc     | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 42        | 31.82%  |
| KDE5          | 41        | 31.06%  |
| GNOME         | 21        | 15.91%  |
| XFCE          | 10        | 7.58%   |
| DWM           | 4         | 3.03%   |
| MATE          | 3         | 2.27%   |
| sway          | 2         | 1.52%   |
| Enlightenment | 2         | 1.52%   |
| xmonad        | 1         | 0.76%   |
| LXQt          | 1         | 0.76%   |
| LeftWM        | 1         | 0.76%   |
| KDE           | 1         | 0.76%   |
| i3            | 1         | 0.76%   |
| fvwm          | 1         | 0.76%   |
| Cinnamon      | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 47.41%  |
| Wayland | 29        | 21.48%  |
| Tty     | 21        | 15.56%  |
| Unknown | 21        | 15.56%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 42.75%  |
| SDDM    | 40        | 30.53%  |
| LightDM | 18        | 13.74%  |
| GDM     | 11        | 8.4%    |
| XDM     | 2         | 1.53%   |
| SLiM    | 2         | 1.53%   |
| LXDM    | 1         | 0.76%   |
| GREETD  | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 58        | 44.96%  |
| en_GB      | 13        | 10.08%  |
| C.UTF8     | 11        | 8.53%   |
| Unknown    | 11        | 8.53%   |
| ru_RU      | 6         | 4.65%   |
| de_DE      | 5         | 3.88%   |
| pl_PL      | 3         | 2.33%   |
| fr_FR      | 3         | 2.33%   |
| C          | 3         | 2.33%   |
| it_IT      | 2         | 1.55%   |
| es_AR      | 2         | 1.55%   |
| el_GR      | 2         | 1.55%   |
| tr_TR      | 1         | 0.78%   |
| sl_SI      | 1         | 0.78%   |
| pt_BR      | 1         | 0.78%   |
| fr_CA      | 1         | 0.78%   |
| es_ES      | 1         | 0.78%   |
| en_US.UTF8 | 1         | 0.78%   |
| en_NZ      | 1         | 0.78%   |
| en_CA      | 1         | 0.78%   |
| en_AU      | 1         | 0.78%   |
| de_CH      | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 111       | 83.46%  |
| BIOS | 22        | 16.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 75        | 58.14%  |
| Btrfs    | 39        | 30.23%  |
| F2fs     | 6         | 4.65%   |
| Zfs      | 3         | 2.33%   |
| Xfs      | 2         | 1.55%   |
| XXXXXXX  | 1         | 0.78%   |
| XXX      | 1         | 0.78%   |
| Xtrfs    | 1         | 0.78%   |
| Bcachefs | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 118       | 90.08%  |
| MBR     | 7         | 5.34%   |
| Unknown | 6         | 4.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 67.42%  |
| Yes       | 43        | 32.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 70%     |
| Yes       | 39        | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 30        | 23.26%  |
| Lenovo                  | 24        | 18.6%   |
| Dell                    | 14        | 10.85%  |
| MSI                     | 13        | 10.08%  |
| Hewlett-Packard         | 8         | 6.2%    |
| Gigabyte Technology     | 7         | 5.43%   |
| ASRock                  | 6         | 4.65%   |
| Intel                   | 5         | 3.88%   |
| Acer                    | 3         | 2.33%   |
| Timi                    | 2         | 1.55%   |
| Framework               | 2         | 1.55%   |
| Unknown                 | 2         | 1.55%   |
| TYAN Computer           | 1         | 0.78%   |
| Toshiba                 | 1         | 0.78%   |
| System76                | 1         | 0.78%   |
| Supermicro              | 1         | 0.78%   |
| Raspberry Pi Foundation | 1         | 0.78%   |
| Pegatron                | 1         | 0.78%   |
| Neousys Technology      | 1         | 0.78%   |
| HUAWEI                  | 1         | 0.78%   |
| Fujitsu                 | 1         | 0.78%   |
| EVGA                    | 1         | 0.78%   |
| BESSTAR Tech            | 1         | 0.78%   |
| BANGHO                  | 1         | 0.78%   |
| AVITA                   | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel S1200RP                             | 2         | 1.55%   |
| HP Laptop 15s-eq0xxx                      | 2         | 1.55%   |
| Framework Laptop                          | 2         | 1.55%   |
| ASUS Z170-A                               | 2         | 1.55%   |
| ASUS TUF Gaming B550-PLUS                 | 2         | 1.55%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 1.55%   |
| Unknown                                   | 2         | 1.55%   |
| TYAN S7025                                | 1         | 0.78%   |
| Toshiba Satellite C850D-118               | 1         | 0.78%   |
| Timi RedmiBook 13                         | 1         | 0.78%   |
| Timi Mi Laptop Pro 15                     | 1         | 0.78%   |
| System76 Gazelle                          | 1         | 0.78%   |
| Supermicro Super Server                   | 1         | 0.78%   |
| RPi Raspberry Pi                          | 1         | 0.78%   |
| Pegatron 810-170st                        | 1         | 0.78%   |
| Neousys Nuvo-8208GC Series                | 1         | 0.78%   |
| MSI MS-7D31                               | 1         | 0.78%   |
| MSI MS-7D25                               | 1         | 0.78%   |
| MSI MS-7C94                               | 1         | 0.78%   |
| MSI MS-7C56                               | 1         | 0.78%   |
| MSI MS-7C37                               | 1         | 0.78%   |
| MSI MS-7B98                               | 1         | 0.78%   |
| MSI MS-7B86                               | 1         | 0.78%   |
| MSI MS-7B17                               | 1         | 0.78%   |
| MSI MS-7A34                               | 1         | 0.78%   |
| MSI MS-7996                               | 1         | 0.78%   |
| MSI GS63VR 6RF                            | 1         | 0.78%   |
| MSI GE73 Raider RGB 8RF                   | 1         | 0.78%   |
| MSI GE66 Raider 11UE                      | 1         | 0.78%   |
| Lenovo Yoga Slim 7 14IIL05 82A1           | 1         | 0.78%   |
| Lenovo Yoga S740-14IIL 81RS               | 1         | 0.78%   |
| Lenovo ThinkPad X390 Yoga 20NN0027MH      | 1         | 0.78%   |
| Lenovo ThinkPad X220 4291QT1              | 1         | 0.78%   |
| Lenovo ThinkPad X13 Yoga Gen 2 20W8002GCD | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI  | 1         | 0.78%   |
| Lenovo ThinkPad T470p 20J7S06Q00          | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS421US           | 1         | 0.78%   |
| Lenovo ThinkPad T14 Gen 2a 20XK002SCK     | 1         | 0.78%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00      | 1         | 0.78%   |
| Lenovo ThinkPad P73 20QSS09S00            | 1         | 0.78%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437       | 1         | 0.78%   |
| Lenovo ThinkPad E495 20NE000BGE           | 1         | 0.78%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX      | 1         | 0.78%   |
| Lenovo ThinkPad 20FMCT01WW                | 1         | 0.78%   |
| Lenovo ThinkBook 14 G3 ACL 21A2           | 1         | 0.78%   |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 0.78%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 0.78%   |
| Lenovo Legion R7000 2020 82B6             | 1         | 0.78%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 1         | 0.78%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT         | 1         | 0.78%   |
| Lenovo IdeaPad C340-14IML 81TK            | 1         | 0.78%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 0.78%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 1         | 0.78%   |
| Intel S5000XVN                            | 1         | 0.78%   |
| Intel NUC8i7HVK                           | 1         | 0.78%   |
| Intel NUC10i7FNH                          | 1         | 0.78%   |
| HUAWEI BOHB-WAX9                          | 1         | 0.78%   |
| HP Victus by Laptop 16-e0xxx              | 1         | 0.78%   |
| HP ProBook 6570b                          | 1         | 0.78%   |
| HP Pavilion Notebook                      | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 13        | 10.08%  |
| ASUS ROG              | 12        | 9.3%    |
| ASUS TUF              | 6         | 4.65%   |
| Dell XPS              | 5         | 3.88%   |
| Lenovo Legion         | 4         | 3.1%    |
| Lenovo IdeaPad        | 3         | 2.33%   |
| ASUS PRIME            | 3         | 2.33%   |
| Lenovo Yoga           | 2         | 1.55%   |
| Intel S1200RP         | 2         | 1.55%   |
| HP Pavilion           | 2         | 1.55%   |
| HP OMEN               | 2         | 1.55%   |
| HP Laptop             | 2         | 1.55%   |
| Framework Laptop      | 2         | 1.55%   |
| Dell Precision        | 2         | 1.55%   |
| Dell OptiPlex         | 2         | 1.55%   |
| Dell Latitude         | 2         | 1.55%   |
| Dell Inspiron         | 2         | 1.55%   |
| ASUS Z170-A           | 2         | 1.55%   |
| ASRock X370           | 2         | 1.55%   |
| Acer Aspire           | 2         | 1.55%   |
| Unknown               | 2         | 1.55%   |
| TYAN S7025            | 1         | 0.78%   |
| Toshiba Satellite     | 1         | 0.78%   |
| Timi RedmiBook        | 1         | 0.78%   |
| Timi Mi               | 1         | 0.78%   |
| System76 Gazelle      | 1         | 0.78%   |
| Supermicro Super      | 1         | 0.78%   |
| RPi Raspberry         | 1         | 0.78%   |
| Pegatron 810-170st    | 1         | 0.78%   |
| Neousys Nuvo-8208GC   | 1         | 0.78%   |
| MSI MS-7D31           | 1         | 0.78%   |
| MSI MS-7D25           | 1         | 0.78%   |
| MSI MS-7C94           | 1         | 0.78%   |
| MSI MS-7C56           | 1         | 0.78%   |
| MSI MS-7C37           | 1         | 0.78%   |
| MSI MS-7B98           | 1         | 0.78%   |
| MSI MS-7B86           | 1         | 0.78%   |
| MSI MS-7B17           | 1         | 0.78%   |
| MSI MS-7A34           | 1         | 0.78%   |
| MSI MS-7996           | 1         | 0.78%   |
| MSI GS63VR            | 1         | 0.78%   |
| MSI GE73              | 1         | 0.78%   |
| MSI GE66              | 1         | 0.78%   |
| Lenovo ThinkBook      | 1         | 0.78%   |
| Lenovo IdeaPadFlex    | 1         | 0.78%   |
| Intel S5000XVN        | 1         | 0.78%   |
| Intel NUC8i7HVK       | 1         | 0.78%   |
| Intel NUC10i7FNH      | 1         | 0.78%   |
| HUAWEI BOHB-WAX9      | 1         | 0.78%   |
| HP Victus             | 1         | 0.78%   |
| HP ProBook            | 1         | 0.78%   |
| Gigabyte Z87X-UD3H    | 1         | 0.78%   |
| Gigabyte Z590         | 1         | 0.78%   |
| Gigabyte Z490         | 1         | 0.78%   |
| Gigabyte X570         | 1         | 0.78%   |
| Gigabyte H470         | 1         | 0.78%   |
| Gigabyte B450M        | 1         | 0.78%   |
| Gigabyte AB350-Gaming | 1         | 0.78%   |
| Fujitsu D3417-B2      | 1         | 0.78%   |
| EVGA Z390             | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 30        | 23.26%  |
| 2019    | 25        | 19.38%  |
| 2020    | 22        | 17.05%  |
| 2018    | 13        | 10.08%  |
| 2017    | 9         | 6.98%   |
| 2016    | 6         | 4.65%   |
| 2015    | 4         | 3.1%    |
| 2014    | 4         | 3.1%    |
| 2012    | 3         | 2.33%   |
| Unknown | 3         | 2.33%   |
| 2011    | 2         | 1.55%   |
| 2022    | 1         | 0.78%   |
| 2013    | 1         | 0.78%   |
| 2010    | 1         | 0.78%   |
| 2009    | 1         | 0.78%   |
| 2008    | 1         | 0.78%   |
| 2007    | 1         | 0.78%   |
| 2006    | 1         | 0.78%   |
| 2005    | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 60        | 46.51%  |
| Desktop        | 53        | 41.09%  |
| Server         | 7         | 5.43%   |
| Convertible    | 5         | 3.88%   |
| System on chip | 2         | 1.55%   |
| Mini pc        | 2         | 1.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 95.42%  |
| Enabled  | 6         | 4.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 99.22%  |
| Yes  | 1         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 31        | 24.03%  |
| 16.01-24.0  | 29        | 22.48%  |
| 8.01-16.0   | 21        | 16.28%  |
| 64.01-256.0 | 18        | 13.95%  |
| 4.01-8.0    | 15        | 11.63%  |
| 24.01-32.0  | 6         | 4.65%   |
| 3.01-4.0    | 4         | 3.1%    |
| 2.01-3.0    | 2         | 1.55%   |
| 0.51-1.0    | 2         | 1.55%   |
| 1.01-2.0    | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 41        | 28.47%  |
| 1.01-2.0   | 27        | 18.75%  |
| 2.01-3.0   | 24        | 16.67%  |
| 8.01-16.0  | 20        | 13.89%  |
| 3.01-4.0   | 16        | 11.11%  |
| 0.51-1.0   | 7         | 4.86%   |
| 16.01-24.0 | 4         | 2.78%   |
| 0.01-0.5   | 3         | 2.08%   |
| 32.01-64.0 | 1         | 0.69%   |
| 24.01-32.0 | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 42.75%  |
| 2      | 34        | 25.95%  |
| 3      | 14        | 10.69%  |
| 5      | 10        | 7.63%   |
| 4      | 9         | 6.87%   |
| 6      | 5         | 3.82%   |
| 7      | 2         | 1.53%   |
| 26     | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 114       | 87.69%  |
| Yes       | 16        | 12.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 81.4%   |
| No        | 24        | 18.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 70%     |
| No        | 39        | 30%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 66.67%  |
| No        | 44        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 32        | 24.62%  |
| Russia      | 11        | 8.46%   |
| Germany     | 11        | 8.46%   |
| Poland      | 10        | 7.69%   |
| UK          | 7         | 5.38%   |
| Spain       | 6         | 4.62%   |
| France      | 4         | 3.08%   |
| Belarus     | 4         | 3.08%   |
| Netherlands | 3         | 2.31%   |
| India       | 3         | 2.31%   |
| Greece      | 3         | 2.31%   |
| Czechia     | 3         | 2.31%   |
| China       | 3         | 2.31%   |
| Canada      | 3         | 2.31%   |
| Australia   | 3         | 2.31%   |
| Switzerland | 2         | 1.54%   |
| Italy       | 2         | 1.54%   |
| Hong Kong   | 2         | 1.54%   |
| Finland     | 2         | 1.54%   |
| Argentina   | 2         | 1.54%   |
| Uruguay     | 1         | 0.77%   |
| Turkey      | 1         | 0.77%   |
| Sweden      | 1         | 0.77%   |
| Slovenia    | 1         | 0.77%   |
| Romania     | 1         | 0.77%   |
| Philippines | 1         | 0.77%   |
| Norway      | 1         | 0.77%   |
| New Zealand | 1         | 0.77%   |
| Mexico      | 1         | 0.77%   |
| Malaysia    | 1         | 0.77%   |
| Ireland     | 1         | 0.77%   |
| Brazil      | 1         | 0.77%   |
| Belgium     | 1         | 0.77%   |
| Bangladesh  | 1         | 0.77%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Warsaw              | 3         | 2.26%   |
| Sterling            | 3         | 2.26%   |
| Moscow              | 3         | 2.26%   |
| Minsk               | 3         | 2.26%   |
| Cieszyn             | 3         | 2.26%   |
| Zurich              | 2         | 1.5%    |
| Yekaterinburg       | 2         | 1.5%    |
| Sydney              | 2         | 1.5%    |
| Swansea             | 2         | 1.5%    |
| Paris               | 2         | 1.5%    |
| Ocala               | 2         | 1.5%    |
| Nuremberg           | 2         | 1.5%    |
| Milan               | 2         | 1.5%    |
| Los Angeles         | 2         | 1.5%    |
| Kulmbach            | 2         | 1.5%    |
| Kallithea           | 2         | 1.5%    |
| Hyderabad           | 2         | 1.5%    |
| Houston             | 2         | 1.5%    |
| Guangzhou           | 2         | 1.5%    |
| Central             | 2         | 1.5%    |
| Barcelona           | 2         | 1.5%    |
| Winston-Salem       | 1         | 0.75%   |
| West Orange         | 1         | 0.75%   |
| Vigo                | 1         | 0.75%   |
| Vantaa              | 1         | 0.75%   |
| Vancouver           | 1         | 0.75%   |
| Utrecht             | 1         | 0.75%   |
| Ufa                 | 1         | 0.75%   |
| Svobodnyy           | 1         | 0.75%   |
| Storsteinnes        | 1         | 0.75%   |
| St Louis            | 1         | 0.75%   |
| Seattle             | 1         | 0.75%   |
| Schwieberdingen     | 1         | 0.75%   |
| Sao Paulo           | 1         | 0.75%   |
| Santa Rosa          | 1         | 0.75%   |
| Sacramento          | 1         | 0.75%   |
| Redmond             | 1         | 0.75%   |
| Ratingen            | 1         | 0.75%   |
| Radovljica          | 1         | 0.75%   |
| Québec             | 1         | 0.75%   |
| Punta Gorda         | 1         | 0.75%   |
| Pujaut              | 1         | 0.75%   |
| Prague              | 1         | 0.75%   |
| Perm                | 1         | 0.75%   |
| Orange              | 1         | 0.75%   |
| Novosibirsk         | 1         | 0.75%   |
| Nizhniy Novgorod    | 1         | 0.75%   |
| Niederdorla         | 1         | 0.75%   |
| New York            | 1         | 0.75%   |
| Neath               | 1         | 0.75%   |
| Murmansk            | 1         | 0.75%   |
| Motala              | 1         | 0.75%   |
| Morcenx             | 1         | 0.75%   |
| Monroe              | 1         | 0.75%   |
| Milton Keynes       | 1         | 0.75%   |
| Mariánské Lázně | 1         | 0.75%   |
| London              | 1         | 0.75%   |
| Lochristi           | 1         | 0.75%   |
| Leidschendam        | 1         | 0.75%   |
| Laziska Gorne       | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 43        | 89     | 18.86%  |
| Samsung Electronics            | 43        | 81     | 18.86%  |
| Seagate                        | 24        | 43     | 10.53%  |
| Toshiba                        | 12        | 15     | 5.26%   |
| Intel                          | 12        | 15     | 5.26%   |
| Crucial                        | 11        | 24     | 4.82%   |
| SK hynix                       | 10        | 11     | 4.39%   |
| SanDisk                        | 9         | 11     | 3.95%   |
| Kingston                       | 7         | 7      | 3.07%   |
| Hitachi                        | 7         | 11     | 3.07%   |
| A-DATA Technology              | 5         | 6      | 2.19%   |
| Unknown                        | 4         | 9      | 1.75%   |
| Micron Technology              | 4         | 4      | 1.75%   |
| KIOXIA-EXCERIA                 | 4         | 7      | 1.75%   |
| HGST                           | 4         | 5      | 1.75%   |
| Corsair                        | 4         | 5      | 1.75%   |
| Goodram                        | 3         | 3      | 1.32%   |
| Team                           | 2         | 4      | 0.88%   |
| Silicon Motion                 | 2         | 3      | 0.88%   |
| Plextor                        | 2         | 3      | 0.88%   |
| Phison                         | 2         | 2      | 0.88%   |
| XrayDisk                       | 1         | 1      | 0.44%   |
| Transcend                      | 1         | 1      | 0.44%   |
| Solid State Storage Technology | 1         | 1      | 0.44%   |
| PNY                            | 1         | 1      | 0.44%   |
| OCZ-VERTEX                     | 1         | 1      | 0.44%   |
| Netac                          | 1         | 1      | 0.44%   |
| LITEON                         | 1         | 1      | 0.44%   |
| LaCie                          | 1         | 2      | 0.44%   |
| KIOXIA                         | 1         | 2      | 0.44%   |
| Kingchuxing                    | 1         | 2      | 0.44%   |
| Hoodisk                        | 1         | 1      | 0.44%   |
| Fujitsu                        | 1         | 1      | 0.44%   |
| Apacer                         | 1         | 1      | 0.44%   |
| 2.5"                           | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Crucial CT2000MX500SSD1 2TB      | 4         | 1.47%   |
| WDC WD10EZEX-08M2NA0 1TB         | 3         | 1.1%    |
| Toshiba KXG6AZNV512G 512GB       | 3         | 1.1%    |
| Samsung SSD 980 PRO 2TB          | 3         | 1.1%    |
| Intel SSDPEKNU512GZ 512GB        | 3         | 1.1%    |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2         | 0.74%   |
| Toshiba DT01ACA100 1TB           | 2         | 0.74%   |
| SK hynix PC711 NVMe 512GB        | 2         | 0.74%   |
| SK hynix PC611 NVMe 512GB        | 2         | 0.74%   |
| Seagate ST4000DM005-2DP166 4TB   | 2         | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.74%   |
| Seagate ST2000DM001-1ER164 2TB   | 2         | 0.74%   |
| Samsung SSD 980 PRO 1TB          | 2         | 0.74%   |
| Samsung SSD 980 1TB              | 2         | 0.74%   |
| Samsung SSD 970 PRO 1TB          | 2         | 0.74%   |
| Samsung SSD 970 EVO Plus 2TB     | 2         | 0.74%   |
| Samsung SSD 970 EVO Plus 250GB   | 2         | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.74%   |
| Samsung SSD 970 EVO 500GB        | 2         | 0.74%   |
| Samsung SSD 970 EVO 250GB        | 2         | 0.74%   |
| Samsung SSD 870 EVO 1TB          | 2         | 0.74%   |
| Samsung SSD 850 EVO 500GB        | 2         | 0.74%   |
| Samsung SSD 850 EVO 250GB        | 2         | 0.74%   |
| Samsung NVMe SSD Drive 512GB     | 2         | 0.74%   |
| Samsung MZVLB512HBJQ-000L2 512GB | 2         | 0.74%   |
| KIOXIA-EXCERIA SSD 500GB         | 2         | 0.74%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.74%   |
| Intel SSDPEKNW010T8 1TB          | 2         | 0.74%   |
| Intel SSDPEKKF256G8L 256GB       | 2         | 0.74%   |
| Hitachi HDS723020BLA642 2TB      | 2         | 0.74%   |
| HGST HTS721010A9E630 1TB         | 2         | 0.74%   |
| Goodram SSDPR-CL100-480-G2 480GB | 2         | 0.74%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.74%   |
| Crucial CT1000P1SSD8 1TB         | 2         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB      | 2         | 0.74%   |
| A-DATA SX8200PNP 512GB           | 2         | 0.74%   |
| A-DATA SX8200PNP 1TB             | 2         | 0.74%   |
| XrayDisk SSD 128GB               | 1         | 0.37%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1         | 0.37%   |
| WDC WDS500G2X0C-00L350 500GB     | 1         | 0.37%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.37%   |
| WDC WDS250G2X0C-00L350 250GB     | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.37%   |
| WDC WDS240G2G0A 240GB SSD        | 1         | 0.37%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.37%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1         | 0.37%   |
| WDC WD60EZRX-00MVLB1 6TB         | 1         | 0.37%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1         | 0.37%   |
| WDC WD5000AZLX-00JKKA0 500GB     | 1         | 0.37%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.37%   |
| WDC WD3200LPVX-22V0TT0 320GB     | 1         | 0.37%   |
| WDC WD3200AAJS-22RYA0 320GB      | 1         | 0.37%   |
| WDC WD30EFRX-68N32N0 3TB         | 1         | 0.37%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1         | 0.37%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 0.37%   |
| WDC WD20NPVX-00EA4T0 2TB         | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 26        | 68     | 38.81%  |
| Seagate | 22        | 41     | 32.84%  |
| Hitachi | 7         | 11     | 10.45%  |
| Toshiba | 6         | 7      | 8.96%   |
| HGST    | 4         | 5      | 5.97%   |
| LaCie   | 1         | 2      | 1.49%   |
| Fujitsu | 1         | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 31     | 30.88%  |
| Crucial             | 8         | 20     | 11.76%  |
| SanDisk             | 7         | 9      | 10.29%  |
| WDC                 | 6         | 7      | 8.82%   |
| Kingston            | 5         | 5      | 7.35%   |
| Goodram             | 3         | 3      | 4.41%   |
| Corsair             | 3         | 4      | 4.41%   |
| Toshiba             | 2         | 3      | 2.94%   |
| Intel               | 2         | 2      | 2.94%   |
| A-DATA Technology   | 2         | 2      | 2.94%   |
| XrayDisk            | 1         | 1      | 1.47%   |
| Transcend           | 1         | 1      | 1.47%   |
| Team                | 1         | 2      | 1.47%   |
| PNY                 | 1         | 1      | 1.47%   |
| Plextor             | 1         | 1      | 1.47%   |
| OCZ-VERTEX          | 1         | 1      | 1.47%   |
| Hoodisk             | 1         | 1      | 1.47%   |
| Apacer              | 1         | 1      | 1.47%   |
| 2.5"                | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 88        | 135    | 44%     |
| SSD     | 57        | 96     | 28.5%   |
| HDD     | 51        | 135    | 25.5%   |
| MMC     | 3         | 6      | 1.5%    |
| Unknown | 1         | 3      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 88        | 135    | 50.29%  |
| SATA | 81        | 227    | 46.29%  |
| SAS  | 3         | 7      | 1.71%   |
| MMC  | 3         | 6      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 76     | 36.59%  |
| 0.51-1.0   | 35        | 45     | 28.46%  |
| 1.01-2.0   | 23        | 59     | 18.7%   |
| 3.01-4.0   | 8         | 12     | 6.5%    |
| 4.01-10.0  | 7         | 29     | 5.69%   |
| 2.01-3.0   | 4         | 9      | 3.25%   |
| 10.01-20.0 | 1         | 1      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 23.48%  |
| 501-1000       | 26        | 19.7%   |
| More than 3000 | 18        | 13.64%  |
| 101-250        | 17        | 12.88%  |
| 1001-2000      | 16        | 12.12%  |
| 2001-3000      | 9         | 6.82%   |
| 1-20           | 5         | 3.79%   |
| 21-50          | 4         | 3.03%   |
| 51-100         | 3         | 2.27%   |
| Unknown        | 3         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 17.65%  |
| 101-250        | 22        | 16.18%  |
| 1-20           | 22        | 16.18%  |
| 21-50          | 15        | 11.03%  |
| 51-100         | 14        | 10.29%  |
| 1001-2000      | 12        | 8.82%   |
| 501-1000       | 11        | 8.09%   |
| More than 3000 | 10        | 7.35%   |
| 2001-3000      | 3         | 2.21%   |
| Unknown        | 3         | 2.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1         | 3      | 4.35%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1         | 2      | 4.35%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1      | 4.35%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 2      | 4.35%   |
| WDC WD1002FBYS-18W8B0 1TB           | 1         | 1      | 4.35%   |
| Transcend TS512GSSD720 512GB        | 1         | 1      | 4.35%   |
| Toshiba MK6008GAH 64GB              | 1         | 1      | 4.35%   |
| Seagate ST3160023AS 160GB           | 1         | 1      | 4.35%   |
| Seagate ST2000DX001-1CM164 2TB      | 1         | 1      | 4.35%   |
| Seagate ST1000LM049-2GH172 1TB      | 1         | 1      | 4.35%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 2      | 4.35%   |
| SanDisk SSD PLUS 1000GB             | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 980 1TB     | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 970 EVO 1TB | 1         | 1      | 4.35%   |
| Kingston SV100S2128G 128GB SSD      | 1         | 1      | 4.35%   |
| Intel SSDPEKKF256G8L 256GB          | 1         | 1      | 4.35%   |
| Hitachi HUA721010KLA330 1TB         | 1         | 1      | 4.35%   |
| Hitachi HDS722020ALA330 2TB         | 1         | 2      | 4.35%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 4.35%   |
| Crucial CT525MX300SSD1 528GB        | 1         | 1      | 4.35%   |
| Crucial CT1000P1SSD8 1TB            | 1         | 1      | 4.35%   |
| A-DATA Technology SP550 240GB SSD   | 1         | 1      | 4.35%   |
| 2.5" SATA SSD 3TG6-P 480GB          | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 9      | 21.74%  |
| Seagate             | 4         | 5      | 17.39%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Hitachi             | 2         | 3      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| Transcend           | 1         | 1      | 4.35%   |
| Toshiba             | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |
| 2.5"                | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 9      | 38.46%  |
| Seagate | 4         | 5      | 30.77%  |
| Hitachi | 2         | 3      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 19     | 52.38%  |
| SSD  | 6         | 6      | 28.57%  |
| NVMe | 4         | 4      | 19.05%  |

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
| Works    | 118       | 318    | 78.67%  |
| Malfunc  | 20        | 29     | 13.33%  |
| Detected | 11        | 27     | 7.33%   |
| Failed   | 1         | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 70        | 33.65%  |
| AMD                            | 36        | 17.31%  |
| Samsung Electronics            | 33        | 15.87%  |
| SanDisk                        | 15        | 7.21%   |
| SK hynix                       | 10        | 4.81%   |
| ASMedia Technology             | 7         | 3.37%   |
| Toshiba America Info Systems   | 5         | 2.4%    |
| Micron Technology              | 5         | 2.4%    |
| Silicon Motion                 | 4         | 1.92%   |
| Phison Electronics             | 4         | 1.92%   |
| KIOXIA                         | 4         | 1.92%   |
| ADATA Technology               | 3         | 1.44%   |
| Solid State Storage Technology | 2         | 0.96%   |
| Seagate Technology             | 2         | 0.96%   |
| Micron/Crucial Technology      | 2         | 0.96%   |
| Kingston Technology Company    | 2         | 0.96%   |
| Silicon Image                  | 1         | 0.48%   |
| Marvell Technology Group       | 1         | 0.48%   |
| LSI Logic / Symbios Logic      | 1         | 0.48%   |
| Lite-On Technology             | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 13.22%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 8.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 3.52%   |
| SK hynix Gold P31 SSD                                                          | 7         | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 3.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 3.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 3.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.2%    |
| Micron Non-Volatile memory controller                                          | 5         | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 2.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.32%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.32%   |
| KIOXIA NVMe SSD                                                                | 3         | 1.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.32%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.32%   |
| Intel SSD 660P Series                                                          | 3         | 1.32%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.32%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 1.32%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.32%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 1.32%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.88%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.88%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.88%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 0.88%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.44%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.44%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.44%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.44%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.44%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.44%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.44%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.44%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.44%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.44%   |
| Phison E7 NVMe Controller                                                      | 1         | 0.44%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.44%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.44%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.44%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1         | 0.44%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.44%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.44%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.44%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.44%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 47.92%  |
| NVMe | 88        | 45.83%  |
| RAID | 6         | 3.13%   |
| IDE  | 5         | 2.6%    |
| SAS  | 1         | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 80        | 62.02%  |
| AMD          | 46        | 35.66%  |
| ARM          | 2         | 1.55%   |
| PowerBook6,7 | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 3.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.33%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 3         | 2.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.33%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 2.33%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 3         | 2.33%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 3         | 2.33%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 2.33%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz           | 2         | 1.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 1.55%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 1.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.55%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 1.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 1.55%   |
| Intel 12th Gen Core i7-12700K                 | 2         | 1.55%   |
| ARM Processor                                 | 2         | 1.55%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.55%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 1.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.55%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.55%   |
| PowerBook6,7 7447A, altivec supported         | 1         | 0.78%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 1         | 0.78%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.78%   |
| Intel Xeon CPU E5335 @ 2.00GHz                | 1         | 0.78%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz           | 1         | 0.78%   |
| Intel Pentium 4 CPU 3.20GHz                   | 1         | 0.78%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.78%   |
| Intel Core i7-8809G CPU @ 3.10GHz             | 1         | 0.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.78%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.78%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.78%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.78%   |
| Intel Core i7-10700F CPU @ 2.90GHz            | 1         | 0.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1         | 0.78%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.78%   |
| Intel Core i5-8200Y CPU @ 1.30GHz             | 1         | 0.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.78%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.78%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 1         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 27        | 20.93%  |
| Intel Core i5          | 24        | 18.6%   |
| Other                  | 19        | 14.73%  |
| AMD Ryzen 9            | 13        | 10.08%  |
| AMD Ryzen 7            | 13        | 10.08%  |
| AMD Ryzen 5            | 10        | 7.75%   |
| Intel Xeon             | 6         | 4.65%   |
| Intel Core i9          | 3         | 2.33%   |
| AMD Ryzen 3            | 3         | 2.33%   |
| AMD Ryzen 7 PRO        | 2         | 1.55%   |
| Intel Pentium 4        | 1         | 0.78%   |
| Intel Core i3          | 1         | 0.78%   |
| Intel Core Duo         | 1         | 0.78%   |
| Intel Atom             | 1         | 0.78%   |
| AMD Ryzen Threadripper | 1         | 0.78%   |
| AMD Ryzen 5 PRO        | 1         | 0.78%   |
| AMD Phenom II X4       | 1         | 0.78%   |
| AMD EPYC               | 1         | 0.78%   |
| AMD E1                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 43        | 33.33%  |
| 8       | 31        | 24.03%  |
| 6       | 23        | 17.83%  |
| 2       | 12        | 9.3%    |
| 12      | 9         | 6.98%   |
| 16      | 6         | 4.65%   |
| 1       | 3         | 2.33%   |
| 24      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 126       | 97.67%  |
| 2       | 2         | 1.55%   |
| Unknown | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 110       | 85.27%  |
| 1       | 18        | 13.95%  |
| Unknown | 1         | 0.78%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 97.67%  |
| 32-bit         | 3         | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 12.21%  |
| 0x906ea    | 8         | 6.11%   |
| 0x0a50000c | 8         | 6.11%   |
| 0x806ec    | 7         | 5.34%   |
| 0x906ed    | 5         | 3.82%   |
| 0x806d1    | 5         | 3.82%   |
| 0x506e3    | 5         | 3.82%   |
| 0x08701021 | 5         | 3.82%   |
| 0x906e9    | 4         | 3.05%   |
| 0x806c1    | 4         | 3.05%   |
| 0x306c3    | 4         | 3.05%   |
| 0x0a201016 | 4         | 3.05%   |
| 0x90672    | 3         | 2.29%   |
| 0x08108109 | 3         | 2.29%   |
| 0x0800820d | 3         | 2.29%   |
| 0x08001138 | 3         | 2.29%   |
| 0xa0671    | 2         | 1.53%   |
| 0xa0655    | 2         | 1.53%   |
| 0xa0653    | 2         | 1.53%   |
| 0xa0652    | 2         | 1.53%   |
| 0x706e5    | 2         | 1.53%   |
| 0x306d4    | 2         | 1.53%   |
| 0x206c2    | 2         | 1.53%   |
| 0x206a7    | 2         | 1.53%   |
| 0x08608103 | 2         | 1.53%   |
| 0x08600106 | 2         | 1.53%   |
| 0x08600103 | 2         | 1.53%   |
| 0xf43      | 1         | 0.76%   |
| 0xa0660    | 1         | 0.76%   |
| 0x906ec    | 1         | 0.76%   |
| 0x806ea    | 1         | 0.76%   |
| 0x806e9    | 1         | 0.76%   |
| 0x806c2    | 1         | 0.76%   |
| 0x6f7      | 1         | 0.76%   |
| 0x6ec      | 1         | 0.76%   |
| 0x406e3    | 1         | 0.76%   |
| 0x306e4    | 1         | 0.76%   |
| 0x306a9    | 1         | 0.76%   |
| 0x0a50000b | 1         | 0.76%   |
| 0x0a201205 | 1         | 0.76%   |
| 0x0a201204 | 1         | 0.76%   |
| 0x08608102 | 1         | 0.76%   |
| 0x08600102 | 1         | 0.76%   |
| 0x0830104d | 1         | 0.76%   |
| 0x08301039 | 1         | 0.76%   |
| 0x08108102 | 1         | 0.76%   |
| 0x08001105 | 1         | 0.76%   |
| 0x05000119 | 1         | 0.76%   |
| 0x010000db | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 22.9%   |
| Zen 3            | 15        | 11.45%  |
| Zen 2            | 14        | 10.69%  |
| Icelake          | 10        | 7.63%   |
| Zen+             | 8         | 6.11%   |
| Unknown          | 8         | 6.11%   |
| Skylake          | 7         | 5.34%   |
| CometLake        | 7         | 5.34%   |
| TigerLake        | 6         | 4.58%   |
| Haswell          | 5         | 3.82%   |
| Zen              | 4         | 3.05%   |
| Alderlake Hybrid | 3         | 2.29%   |
| Westmere         | 2         | 1.53%   |
| SandyBridge      | 2         | 1.53%   |
| IvyBridge        | 2         | 1.53%   |
| Broadwell        | 2         | 1.53%   |
| P6               | 1         | 0.76%   |
| NetBurst         | 1         | 0.76%   |
| K10              | 1         | 0.76%   |
| Core             | 1         | 0.76%   |
| Bonnell          | 1         | 0.76%   |
| Bobcat           | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 56        | 35%     |
| Intel                      | 54        | 33.75%  |
| AMD                        | 47        | 29.38%  |
| Matrox Electronics Systems | 2         | 1.25%   |
| ASPEED Technology          | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 10        | 5.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 8         | 4.76%   |
| AMD Cezanne                                                                   | 8         | 4.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 2.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 2.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 2.38%   |
| Intel HD Graphics 630                                                         | 4         | 2.38%   |
| AMD Renoir                                                                    | 4         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.79%   |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 1.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 1.79%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 3         | 1.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 3         | 1.79%   |
| AMD Lucienne                                                                  | 3         | 1.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                     | 2         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2         | 1.19%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 2         | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 2         | 1.19%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 2         | 1.19%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 1.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.19%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 2         | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.19%   |
| Intel UHD Graphics 620                                                        | 2         | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.19%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.19%   |
| Intel HD Graphics 5500                                                        | 2         | 1.19%   |
| Intel HD Graphics 530                                                         | 2         | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2         | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2         | 1.19%   |
| Intel AlderLake-S GT1                                                         | 2         | 1.19%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 2         | 1.19%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.6%    |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.6%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650]                                               | 1         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.6%    |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1         | 0.6%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 0.6%    |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                         | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.6%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 0.6%    |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.6%    |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.6%    |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.6%    |
| Nvidia GM107 [GeForce GTX 745]                                                | 1         | 0.6%    |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.6%    |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 0.6%    |
| Nvidia GK110B [GeForce GTX 780 Ti]                                            | 1         | 0.6%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.6%    |
| Nvidia GA106 [Geforce RTX 3050]                                               | 1         | 0.6%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 34        | 26.36%  |
| 1 x Nvidia     | 27        | 20.93%  |
| 1 x Intel      | 24        | 18.6%   |
| Intel + Nvidia | 23        | 17.83%  |
| AMD + Nvidia   | 6         | 4.65%   |
| 2 x AMD        | 5         | 3.88%   |
| Other          | 3         | 2.33%   |
| 2 x Intel      | 2         | 1.55%   |
| 1 x Matrox     | 2         | 1.55%   |
| Intel + AMD    | 2         | 1.55%   |
| 1 x ASPEED     | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 61.24%  |
| Proprietary | 43        | 33.33%  |
| Unknown     | 7         | 5.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 43.61%  |
| 7.01-8.0   | 18        | 13.53%  |
| 3.01-4.0   | 14        | 10.53%  |
| 1.01-2.0   | 10        | 7.52%   |
| 8.01-16.0  | 10        | 7.52%   |
| 0.51-1.0   | 7         | 5.26%   |
| 0.01-0.5   | 7         | 5.26%   |
| 5.01-6.0   | 6         | 4.51%   |
| 2.01-3.0   | 3         | 2.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 19        | 11.88%  |
| Samsung Electronics     | 14        | 8.75%   |
| Chimei Innolux          | 12        | 7.5%    |
| AU Optronics            | 12        | 7.5%    |
| Goldstar                | 11        | 6.88%   |
| LG Display              | 8         | 5%      |
| Hewlett-Packard         | 7         | 4.38%   |
| Lenovo                  | 6         | 3.75%   |
| Dell                    | 6         | 3.75%   |
| ASUSTek Computer        | 6         | 3.75%   |
| ViewSonic               | 5         | 3.13%   |
| Sharp                   | 5         | 3.13%   |
| BenQ                    | 5         | 3.13%   |
| Ancor Communications    | 5         | 3.13%   |
| Iiyama                  | 4         | 2.5%    |
| AOC                     | 4         | 2.5%    |
| Acer                    | 4         | 2.5%    |
| Philips                 | 3         | 1.88%   |
| HannStar                | 2         | 1.25%   |
| Unknown                 | 2         | 1.25%   |
| Valve                   | 1         | 0.63%   |
| Toshiba                 | 1         | 0.63%   |
| Sceptre Tech            | 1         | 0.63%   |
| Sceptre                 | 1         | 0.63%   |
| PNP                     | 1         | 0.63%   |
| PANDA                   | 1         | 0.63%   |
| Onkyo                   | 1         | 0.63%   |
| NEC Computers           | 1         | 0.63%   |
| MXX                     | 1         | 0.63%   |
| MStar                   | 1         | 0.63%   |
| Microstep               | 1         | 0.63%   |
| Mi                      | 1         | 0.63%   |
| LYC                     | 1         | 0.63%   |
| KTC                     | 1         | 0.63%   |
| Gigabyte Technology     | 1         | 0.63%   |
| Gateway                 | 1         | 0.63%   |
| CSO                     | 1         | 0.63%   |
| Chi Mei Optoelectronics | 1         | 0.63%   |
| Belinea                 | 1         | 0.63%   |
| Apple                   | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4         | 2.38%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch        | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.19%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 1.19%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.19%   |
| Unknown                                                                | 2         | 1.19%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch             | 1         | 0.6%    |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch          | 1         | 0.6%    |
| ViewSonic LCD Monitor VSCCB25 1920x1080 480x270mm 21.7-inch            | 1         | 0.6%    |
| ViewSonic LCD Monitor VSC2034 2560x1440 600x340mm 27.2-inch            | 1         | 0.6%    |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch            | 1         | 0.6%    |
| Valve Index HMD VLV91A8                                                | 1         | 0.6%    |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1         | 0.6%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.6%    |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch        | 1         | 0.6%    |
| Sceptre LCD Monitor C305W-2560UN                                       | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch   | 1         | 0.6%    |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1         | 0.6%    |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch      | 1         | 0.6%    |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1         | 0.6%    |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 261x163mm 12.1-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 0.6%    |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1         | 0.6%    |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1         | 0.6%    |
| PNP LCD Monitor PNP0801 1280x960                                       | 1         | 0.6%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1         | 0.6%    |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                | 1         | 0.6%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.6%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1         | 0.6%    |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1         | 0.6%    |
| MXX A-2 MXX0001 1920x540                                               | 1         | 0.6%    |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1         | 0.6%    |
| Microstep LCD Monitor MSI MPG27CQ 2560x1440                            | 1         | 0.6%    |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1         | 0.6%    |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                        | 1         | 0.6%    |
| LG Display LCD Monitor LGD06BA 2560x1600 286x179mm 13.3-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD05BE 1920x1080 382x215mm 17.3-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0536 1920x1080 294x165mm 13.3-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 0.6%    |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 0.6%    |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1         | 0.6%    |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                      | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 47.33%  |
| 2560x1440 (QHD)    | 25        | 16.67%  |
| 3840x2160 (4K)     | 13        | 8.67%   |
| 1366x768 (WXGA)    | 7         | 4.67%   |
| 3440x1440          | 5         | 3.33%   |
| 1280x1024 (SXGA)   | 4         | 2.67%   |
| 2560x1600          | 3         | 2%      |
| Unknown            | 3         | 2%      |
| 3840x1080          | 2         | 1.33%   |
| 2560x1080          | 2         | 1.33%   |
| 2256x1504          | 2         | 1.33%   |
| 1920x1200 (WUXGA)  | 2         | 1.33%   |
| 1600x900 (HD+)     | 2         | 1.33%   |
| 1440x900 (WXGA+)   | 2         | 1.33%   |
| 6400x1080          | 1         | 0.67%   |
| 3840x2400          | 1         | 0.67%   |
| 2048x1152          | 1         | 0.67%   |
| 1680x1050 (WSXGA+) | 1         | 0.67%   |
| 1280x960           | 1         | 0.67%   |
| 1024x768 (XGA)     | 1         | 0.67%   |
| 1024x600           | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 22.15%  |
| 27      | 28        | 17.72%  |
| 23      | 15        | 9.49%   |
| 13      | 14        | 8.86%   |
| 14      | 11        | 6.96%   |
| 21      | 9         | 5.7%    |
| 24      | 7         | 4.43%   |
| 17      | 7         | 4.43%   |
| 34      | 6         | 3.8%    |
| Unknown | 6         | 3.8%    |
| 25      | 3         | 1.9%    |
| 19      | 3         | 1.9%    |
| 49      | 2         | 1.27%   |
| 31      | 2         | 1.27%   |
| 16      | 2         | 1.27%   |
| 84      | 1         | 0.63%   |
| 54      | 1         | 0.63%   |
| 29      | 1         | 0.63%   |
| 28      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 18      | 1         | 0.63%   |
| 12      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 39.46%  |
| 501-600     | 43        | 29.25%  |
| 401-500     | 12        | 8.16%   |
| 201-300     | 9         | 6.12%   |
| 701-800     | 6         | 4.08%   |
| Unknown     | 6         | 4.08%   |
| 601-700     | 5         | 3.4%    |
| 351-400     | 4         | 2.72%   |
| 1001-1500   | 3         | 2.04%   |
| 1501-2000   | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 76.87%  |
| 16/10   | 10        | 7.46%   |
| 21/9    | 7         | 5.22%   |
| Unknown | 5         | 3.73%   |
| 5/4     | 4         | 2.99%   |
| 4/3     | 2         | 1.49%   |
| 3/2     | 2         | 1.49%   |
| 32/9    | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 21.79%  |
| 301-350        | 28        | 17.95%  |
| 201-250        | 27        | 17.31%  |
| 81-90          | 20        | 12.82%  |
| 351-500        | 9         | 5.77%   |
| 151-200        | 6         | 3.85%   |
| Unknown        | 6         | 3.85%   |
| 141-150        | 5         | 3.21%   |
| 71-80          | 4         | 2.56%   |
| 251-300        | 4         | 2.56%   |
| More than 1000 | 3         | 1.92%   |
| 121-130        | 3         | 1.92%   |
| 111-120        | 3         | 1.92%   |
| 61-70          | 1         | 0.64%   |
| 41-50          | 1         | 0.64%   |
| 501-1000       | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 31.51%  |
| 101-120       | 38        | 26.03%  |
| 51-100        | 35        | 23.97%  |
| 161-240       | 14        | 9.59%   |
| Unknown       | 6         | 4.11%   |
| More than 240 | 5         | 3.42%   |
| 1-50          | 2         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 65.65%  |
| 2     | 30        | 22.9%   |
| 0     | 7         | 5.34%   |
| 3     | 6         | 4.58%   |
| 4     | 2         | 1.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 90        | 50.28%  |
| Realtek Semiconductor             | 51        | 28.49%  |
| Qualcomm Atheros                  | 7         | 3.91%   |
| MediaTek                          | 4         | 2.23%   |
| Broadcom                          | 4         | 2.23%   |
| Aquantia                          | 3         | 1.68%   |
| Samsung Electronics               | 2         | 1.12%   |
| Marvell Technology Group          | 2         | 1.12%   |
| Lenovo                            | 2         | 1.12%   |
| ASIX Electronics                  | 2         | 1.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.56%   |
| Raspberry Pi                      | 1         | 0.56%   |
| Ralink Technology                 | 1         | 0.56%   |
| Quectel Wireless Solutions        | 1         | 0.56%   |
| NetGear                           | 1         | 0.56%   |
| Microsoft                         | 1         | 0.56%   |
| ICS Advent                        | 1         | 0.56%   |
| Google                            | 1         | 0.56%   |
| Ericsson Business Mobile Networks | 1         | 0.56%   |
| D-Link                            | 1         | 0.56%   |
| Broadcom Limited                  | 1         | 0.56%   |
| Apple                             | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 16.82%  |
| Intel Wi-Fi 6 AX200                                               | 17        | 7.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 3.18%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.18%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.73%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.27%   |
| Intel I210 Gigabit Network Connection                             | 5         | 2.27%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.82%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.36%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.91%   |
| Intel Wireless-AC 9260                                            | 2         | 0.91%   |
| Intel Wireless 8260                                               | 2         | 0.91%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 2         | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.91%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.91%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 0.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.91%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.45%   |
| Raspberry Pi Pico                                                 | 1         | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.45%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 0.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.45%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 0.45%   |
| NetGear A6210                                                     | 1         | 0.45%   |
| Microsoft XBOX ACC                                                | 1         | 0.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 67        | 71.28%  |
| Realtek Semiconductor      | 10        | 10.64%  |
| Qualcomm Atheros           | 5         | 5.32%   |
| MediaTek                   | 4         | 4.26%   |
| Broadcom                   | 2         | 2.13%   |
| Ralink Technology          | 1         | 1.06%   |
| Quectel Wireless Solutions | 1         | 1.06%   |
| NetGear                    | 1         | 1.06%   |
| Microsoft                  | 1         | 1.06%   |
| D-Link                     | 1         | 1.06%   |
| Broadcom Limited           | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 17        | 17.89%  |
| Intel Cannon Lake PCH CNVi WiFi                                     | 8         | 8.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 6         | 6.32%   |
| Intel Wireless 8265 / 8275                                          | 5         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4         | 4.21%   |
| Intel Wi-Fi 6 AX201                                                 | 4         | 4.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 4         | 4.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 3         | 3.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 3         | 3.16%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3         | 3.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 2         | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 2.11%   |
| Intel Wireless-AC 9260                                              | 2         | 2.11%   |
| Intel Wireless 8260                                                 | 2         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 2         | 2.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 2         | 2.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 1         | 1.05%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 1         | 1.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 1.05%   |
| Quectel Wireless Solutions Quectel EM05-CE                          | 1         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1         | 1.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1         | 1.05%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1         | 1.05%   |
| NetGear A6210                                                       | 1         | 1.05%   |
| Microsoft XBOX ACC                                                  | 1         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1         | 1.05%   |
| Intel Wireless 7265                                                 | 1         | 1.05%   |
| Intel Wireless 3160                                                 | 1         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 1         | 1.05%   |
| D-Link 802.11 n WLAN                                                | 1         | 1.05%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1         | 1.05%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 48        | 41.38%  |
| Intel                      | 48        | 41.38%  |
| Qualcomm Atheros           | 3         | 2.59%   |
| Aquantia                   | 3         | 2.59%   |
| Samsung Electronics        | 2         | 1.72%   |
| Marvell Technology Group   | 2         | 1.72%   |
| Lenovo                     | 2         | 1.72%   |
| Broadcom                   | 2         | 1.72%   |
| ASIX Electronics           | 2         | 1.72%   |
| ZTE WCDMA Technologies MSM | 1         | 0.86%   |
| ICS Advent                 | 1         | 0.86%   |
| Google                     | 1         | 0.86%   |
| Apple                      | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 37        | 30.08%  |
| Realtek RTL8125 2.5GbE Controller                                     | 7         | 5.69%   |
| Intel I211 Gigabit Network Connection                                 | 7         | 5.69%   |
| Intel Ethernet Controller I225-V                                      | 6         | 4.88%   |
| Intel I210 Gigabit Network Connection                                 | 5         | 4.07%   |
| Intel Ethernet Connection (7) I219-V                                  | 5         | 4.07%   |
| Intel Ethernet Connection (2) I219-V                                  | 5         | 4.07%   |
| Intel 82574L Gigabit Network Connection                               | 3         | 2.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]     | 3         | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 2         | 1.63%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                      | 2         | 1.63%   |
| Intel Ethernet Connection (7) I219-LM                                 | 2         | 1.63%   |
| Intel Ethernet Connection (2) I219-LM                                 | 2         | 1.63%   |
| Intel Ethernet Connection (14) I219-V                                 | 2         | 1.63%   |
| Intel Ethernet Connection (11) I219-LM                                | 2         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 1.63%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                        | 1         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                         | 1         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                                | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller             | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller             | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller               | 1         | 0.81%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller               | 1         | 0.81%   |
| Lenovo USB-C Dock Ethernet                                            | 1         | 0.81%   |
| Lenovo ThinkPad TBT 3 Dock                                            | 1         | 0.81%   |
| Intel I350 Gigabit Network Connection                                 | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 0.81%   |
| Intel Ethernet Connection I217-V                                      | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 0.81%   |
| Intel Ethernet Connection (11) I219-V                                 | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                                 | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-LM                                | 1         | 0.81%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 0.81%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                | 1         | 0.81%   |
| ICS Advent DM9601 Fast Ethernet Adapter                               | 1         | 0.81%   |
| Google Nexus/Pixel Device (tether)                                    | 1         | 0.81%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express               | 1         | 0.81%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 0.81%   |
| ASIX AX88772                                                          | 1         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 0.81%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                       | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 105       | 53.3%   |
| WiFi     | 90        | 45.69%  |
| Modem    | 2         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 50.77%  |
| Ethernet | 64        | 49.23%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 58        | 44.96%  |
| 1     | 56        | 43.41%  |
| 3     | 9         | 6.98%   |
| 0     | 3         | 2.33%   |
| 4     | 2         | 1.55%   |
| 6     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 76.12%  |
| Yes  | 32        | 23.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 71.91%  |
| Realtek Semiconductor           | 7         | 7.87%   |
| Cambridge Silicon Radio         | 5         | 5.62%   |
| IMC Networks                    | 3         | 3.37%   |
| Broadcom                        | 2         | 2.25%   |
| ASUSTek Computer                | 2         | 2.25%   |
| Toshiba                         | 1         | 1.12%   |
| Qualcomm Atheros Communications | 1         | 1.12%   |
| MediaTek                        | 1         | 1.12%   |
| Foxconn / Hon Hai               | 1         | 1.12%   |
| Edimax Technology               | 1         | 1.12%   |
| Apple                           | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 17        | 19.1%   |
| Intel AX200 Bluetooth                               | 17        | 19.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 15.73%  |
| Intel Bluetooth wireless interface                  | 8         | 8.99%   |
| Realtek Bluetooth Radio                             | 5         | 5.62%   |
| Intel AX210 Bluetooth                               | 5         | 5.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 5.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.25%   |
| IMC Networks Wireless_Device                        | 2         | 2.25%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.12%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.12%   |
| MediaTek Wireless_Device                            | 1         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.12%   |
| IMC Networks Bluetooth Device                       | 1         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.12%   |
| Edimax Bluetooth Device                             | 1         | 1.12%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.12%   |
| Broadcom BCM20702A0                                 | 1         | 1.12%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.12%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 76        | 34.39%  |
| AMD                                  | 56        | 25.34%  |
| Nvidia                               | 43        | 19.46%  |
| C-Media Electronics                  | 4         | 1.81%   |
| Thesycon Systemsoftware & Consulting | 3         | 1.36%   |
| SteelSeries ApS                      | 3         | 1.36%   |
| Realtek Semiconductor                | 3         | 1.36%   |
| Logitech                             | 3         | 1.36%   |
| AudioQuest                           | 3         | 1.36%   |
| ASUSTek Computer                     | 3         | 1.36%   |
| Yamaha                               | 2         | 0.9%    |
| Sony                                 | 2         | 0.9%    |
| Razer USA                            | 2         | 0.9%    |
| Lenovo                               | 2         | 0.9%    |
| Creative Technology                  | 2         | 0.9%    |
| Creative Labs                        | 2         | 0.9%    |
| Valve Software                       | 1         | 0.45%   |
| Texas Instruments                    | 1         | 0.45%   |
| Sennheiser Communications            | 1         | 0.45%   |
| SAVITECH                             | 1         | 0.45%   |
| RODE Microphones                     | 1         | 0.45%   |
| Kingston Technology                  | 1         | 0.45%   |
| JOUNIVO                              | 1         | 0.45%   |
| JMTek                                | 1         | 0.45%   |
| Generalplus Technology               | 1         | 0.45%   |
| FiiO Electronics Technology          | 1         | 0.45%   |
| Astro Gaming                         | 1         | 0.45%   |
| ACTIONS                              | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 7.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 5.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 5.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 4.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 4.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 3.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 3.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 3.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 2.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.28%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 2.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.28%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 1.52%   |
| Nvidia Audio device                                                        | 4         | 1.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.52%   |
| Thesycon Systemsoftware & Consulting E30                                   | 3         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.14%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2         | 0.76%   |
| Realtek Semiconductor USB Condenser Microphone                             | 2         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.76%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.76%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 0.76%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.76%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.76%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 0.76%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.76%   |
| AudioQuest DragonFly Red                                                   | 2         | 0.76%   |
| ASUSTek Computer USB Audio                                                 | 2         | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.76%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.76%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.38%   |
| Yamaha Steinberg UR22C                                                     | 1         | 0.38%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.38%   |
| Texas Instruments PCM2912A Audio Codec                                     | 1         | 0.38%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.38%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1         | 0.38%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1         | 0.38%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                          | 1         | 0.38%   |
| SAVITECH SA9023 audio controller                                           | 1         | 0.38%   |
| RODE Microphones RODE VideoMic NTG                                         | 1         | 0.38%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.38%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.38%   |
| Razer USA Kraken Tournament Edition                                        | 1         | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 25.55%  |
| SK hynix            | 19        | 13.87%  |
| Kingston            | 18        | 13.14%  |
| G.Skill             | 15        | 10.95%  |
| Crucial             | 14        | 10.22%  |
| Micron Technology   | 11        | 8.03%   |
| Unknown             | 6         | 4.38%   |
| Corsair             | 5         | 3.65%   |
| A-DATA Technology   | 4         | 2.92%   |
| Patriot             | 3         | 2.19%   |
| Unknown             | 2         | 1.46%   |
| Transcend           | 1         | 0.73%   |
| Team                | 1         | 0.73%   |
| Qimonda             | 1         | 0.73%   |
| Magnum Tech         | 1         | 0.73%   |
| Innodisk            | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.39%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.39%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.39%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s               | 2         | 1.39%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.39%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s          | 2         | 1.39%   |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s         | 2         | 1.39%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 1.39%   |
| Unknown                                                          | 2         | 1.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.69%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.69%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                       | 1         | 0.69%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 0.69%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.69%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.69%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.69%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.69%   |
| Samsung RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.69%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.69%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.69%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.69%   |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s             | 1         | 0.69%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s              | 1         | 0.69%   |
| Samsung RAM M378A2G43MX3-CTD 16384MB DIMM DDR4 3466MT/s          | 1         | 0.69%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB Row Of Chips LPDDR3 2133MT/s  | 1         | 0.69%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 0.69%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 0.69%   |
| Qimonda RAM 72T256920EFA3SC 2GB DIMM DDR2 667MT/s                | 1         | 0.69%   |
| Qimonda RAM 72T256420EFD3SB2 2GB DIMM DDR2 667MT/s               | 1         | 0.69%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 0.69%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 96        | 78.69%  |
| DDR3    | 13        | 10.66%  |
| LPDDR4  | 3         | 2.46%   |
| LPDDR3  | 3         | 2.46%   |
| SDRAM   | 2         | 1.64%   |
| DDR2    | 2         | 1.64%   |
| Unknown | 2         | 1.64%   |
| DDR     | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 48.78%  |
| DIMM         | 54        | 43.9%   |
| Row Of Chips | 8         | 6.5%    |
| Chip         | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 61        | 46.21%  |
| 16384 | 33        | 25%     |
| 4096  | 16        | 12.12%  |
| 32768 | 13        | 9.85%   |
| 2048  | 5         | 3.79%   |
| 1024  | 2         | 1.52%   |
| 512   | 2         | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 39        | 29.77%  |
| 2667    | 26        | 19.85%  |
| 1600    | 10        | 7.63%   |
| 2133    | 8         | 6.11%   |
| 3600    | 5         | 3.82%   |
| 2400    | 5         | 3.82%   |
| 3400    | 3         | 2.29%   |
| 1333    | 3         | 2.29%   |
| 667     | 3         | 2.29%   |
| 4800    | 2         | 1.53%   |
| 3866    | 2         | 1.53%   |
| 3666    | 2         | 1.53%   |
| 3533    | 2         | 1.53%   |
| 3466    | 2         | 1.53%   |
| 3000    | 2         | 1.53%   |
| 2933    | 2         | 1.53%   |
| 1867    | 2         | 1.53%   |
| Unknown | 2         | 1.53%   |
| 4267    | 1         | 0.76%   |
| 4000    | 1         | 0.76%   |
| 3733    | 1         | 0.76%   |
| 3266    | 1         | 0.76%   |
| 2866    | 1         | 0.76%   |
| 2733    | 1         | 0.76%   |
| 2666    | 1         | 0.76%   |
| 2197    | 1         | 0.76%   |
| 1067    | 1         | 0.76%   |
| 1066    | 1         | 0.76%   |
| 533     | 1         | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| HP LaserJet M14-M17 | 1         | 100%    |

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
| Chicony Electronics           | 12        | 16.67%  |
| IMC Networks                  | 11        | 15.28%  |
| Logitech                      | 7         | 9.72%   |
| Realtek Semiconductor         | 6         | 8.33%   |
| Acer                          | 6         | 8.33%   |
| Sunplus Innovation Technology | 4         | 5.56%   |
| Microdia                      | 4         | 5.56%   |
| Lite-On Technology            | 4         | 5.56%   |
| Quanta                        | 3         | 4.17%   |
| Luxvisions Innotech Limited   | 3         | 4.17%   |
| Xiaomi                        | 1         | 1.39%   |
| Valve Software                | 1         | 1.39%   |
| Syntek                        | 1         | 1.39%   |
| SunplusIT                     | 1         | 1.39%   |
| Ruision                       | 1         | 1.39%   |
| MacroSilicon                  | 1         | 1.39%   |
| KYE Systems (Mouse Systems)   | 1         | 1.39%   |
| HD WEBCAM                     | 1         | 1.39%   |
| Generalplus Technology        | 1         | 1.39%   |
| Cubeternet                    | 1         | 1.39%   |
| Creative Technology           | 1         | 1.39%   |
| Alcor Micro                   | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                      | 9         | 12.5%   |
| Chicony Integrated Camera                                           | 6         | 8.33%   |
| Acer Integrated Camera                                              | 4         | 5.56%   |
| Microdia Integrated_Webcam_HD                                       | 3         | 4.17%   |
| Sunplus Integrated_Webcam_HD                                        | 2         | 2.78%   |
| Realtek Integrated Webcam HD                                        | 2         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                 | 2         | 2.78%   |
| Lite-On HP Wide Vision HD Camera                                    | 2         | 2.78%   |
| Chicony HD User Facing                                              | 2         | 2.78%   |
| Xiaomi MI 9                                                         | 1         | 1.39%   |
| Valve Software 3D Camera                                            | 1         | 1.39%   |
| Syntek Integrated Camera                                            | 1         | 1.39%   |
| SunplusIT AUKEY PCÃ¢Â€Â”LM4                                 | 1         | 1.39%   |
| Sunplus HP Wide Vision HD                                           | 1         | 1.39%   |
| Sunplus Full HD webcam                                              | 1         | 1.39%   |
| Ruision UVC Camera                                                  | 1         | 1.39%   |
| Realtek USB Camera                                                  | 1         | 1.39%   |
| Realtek Laptop Camera                                               | 1         | 1.39%   |
| Realtek Integrated_Webcam_HD                                        | 1         | 1.39%   |
| Realtek Integrated Camera                                           | 1         | 1.39%   |
| Quanta RGB-IR Camera                                                | 1         | 1.39%   |
| Quanta HD Webcam                                                    | 1         | 1.39%   |
| Quanta HD Camera                                                    | 1         | 1.39%   |
| Microdia HP Webcam-101                                              | 1         | 1.39%   |
| MacroSilicon MiraBox Capture                                        | 1         | 1.39%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                | 1         | 1.39%   |
| Logitech Webcam C270                                                | 1         | 1.39%   |
| Logitech StreamCam                                                  | 1         | 1.39%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1         | 1.39%   |
| Logitech HD Webcam C615                                             | 1         | 1.39%   |
| Logitech HD Webcam C510                                             | 1         | 1.39%   |
| Logitech HD Pro Webcam C920                                         | 1         | 1.39%   |
| Logitech BRIO Ultra HD Webcam                                       | 1         | 1.39%   |
| Lite-On TOSHIBA Web Camera - HD                                     | 1         | 1.39%   |
| Lite-On Integrated Camera                                           | 1         | 1.39%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1         | 1.39%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                                 | 1         | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam                                   | 1         | 1.39%   |
| HD WEBCAM Web Camera                                                | 1         | 1.39%   |
| Generalplus GENERAL WEBCAM                                          | 1         | 1.39%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1         | 1.39%   |
| Creative Live! Cam Sync 1080p                                       | 1         | 1.39%   |
| Chicony XiaoMi USB 2.0 Webcam                                       | 1         | 1.39%   |
| Chicony USB2.0 Camera                                               | 1         | 1.39%   |
| Chicony USB 2.0 Camera                                              | 1         | 1.39%   |
| Chicony HP Truevision HD                                            | 1         | 1.39%   |
| Alcor Micro 720P USB Webcam                                         | 1         | 1.39%   |
| Acer NEC HD WebCam                                                  | 1         | 1.39%   |
| Acer HD Webcam                                                      | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 33.33%  |
| Validity Sensors           | 3         | 25%     |
| Elan Microelectronics      | 3         | 25%     |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| DigitalPersona             | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 16.67%  |
| Elan ELAN:Fingerprint                             | 2         | 16.67%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                   | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                  | 1         | 8.33%   |
| DigitalPersona Fingerprint Reader                 | 1         | 8.33%   |
| Unknown                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Alcor Micro | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 58200                      | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 2         | 33.33%  |
| O2 Micro Oz776 SmartCard Reader     | 1         | 16.67%  |
| Broadcom 5880                       | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 59.26%  |
| 1     | 29        | 21.48%  |
| 2     | 12        | 8.89%   |
| 3     | 7         | 5.19%   |
| 4     | 6         | 4.44%   |
| 6     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 17        | 18.28%  |
| Fingerprint reader       | 12        | 12.9%   |
| Camera                   | 11        | 11.83%  |
| Bluetooth                | 10        | 10.75%  |
| Graphics card            | 9         | 9.68%   |
| Net/wireless             | 7         | 7.53%   |
| Chipcard                 | 6         | 6.45%   |
| Multimedia controller    | 4         | 4.3%    |
| Sound                    | 3         | 3.23%   |
| Network                  | 3         | 3.23%   |
| Card reader              | 3         | 3.23%   |
| Storage/ata              | 2         | 2.15%   |
| Modem                    | 2         | 2.15%   |
| Firewire controller      | 2         | 2.15%   |
| Storage/raid             | 1         | 1.08%   |
| Net/ethernet             | 1         | 1.08%   |

